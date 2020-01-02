<template>
  <div id="app">
    <h1 class="title">
      Terms & Privacy
    </h1>
    <div class="textspace">
      <h3 class="text">
        <p>
          La presente Política de Privacidad establece los términos en que umbra
          usa y protege la información que es proporcionada por sus usuarios al
          momento de utilizar su sitio web. Este proyecto está comprometido con
          la seguridad de los datos de sus usuarios. Cuando le pedimos llenar
          los campos de información personal con la cual usted pueda ser
          identificado, lo hacemos asegurando que solo se empleará de acuerdo
          con los siguientes términos.
        </p>
        <p>
          Nuestro sitio web podrá recoger información personal, por ejemplo:
          Nombre, situación geográfica y año de nacimiento. Umbra emplea la
          información con el fin de proporcionar el mejor servicio posible,
          particularmente para crear una mayor experiencia inmersiva y mejorar
          nuestro servicio. Estamos altamente comprometido para cumplir con el
          compromiso de mantener su información segura.
        </p>
        <p>
          Una cookie se refiere a un fichero que es enviado con la finalidad de
          solicitar permiso para almacenarse en su ordenador, al aceptar dicho
          fichero se crea y las cookies sirven entonces para tener información
          respecto al tráfico web, y también facilita las futuras visitas a una
          web recurrente. Nuestro sitio web no emplea las cookies para poder
          identificar las páginas que son visitadas y su frecuencia.
        </p>
        <p>
          Este sitio web contiene enlaces a otros sitios que pudieran ser de su
          interés. Una vez que usted de clic en estos enlaces y abandone nuestra
          página, ya no tenemos control sobre al sitio al que es redirigido y
          por lo tanto no somos responsables de los términos o privacidad ni de
          la protección de sus datos en esos otros sitios terceros. Dichos
          sitios están sujetos a sus propias políticas de privacidad por lo cual
          es recomendable que los consulte para confirmar que usted está de
          acuerdo con estas.
        </p>
        <p>
          Este proyecto no venderá, cederá ni distribuirá la información
          personal que es recopilada sin su consentimiento, salvo que sea
          requerido por un juez con un orden judicial.
        </p>
      </h3>
      <nav class="navbar">
        <ul>
          <li style="font-size:1.5rem">Project</li>
          <li style="font-size:1.5rem">Credits</li>
          <li style="font-size:1.5rem">Contribute</li>
          <li style="font-size:1.5rem">Privacy</li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "app",
  components: {}
};
</script>

<style>
html,
body {
  max-width: 100%;
  overflow-y: hidden;
}
body {
  background-color: #0f0f10;
}
body * {
  color: #b4b4b4;
}
#app {
  font-family: serif;
  text-align: center;
  height: 100%;
  font-family: "Tiempos Headline Light", Times, serif;
  filter: blur(0.07rem);
  transition: filter 2s ease-in-out;
}

h3 {
  font-family: "Tiempos Headline Regular", Times, serif;
  font-size: 1.3rem;
  text-align: left;
  line-height: 1, 5rem;
  color: #f5f9fb;
}
p {
  font-weight: 600;
  cursor:ns-resize; 
}

.textspace {
  margin-right: 16.93rem;
  margin-top: -1.5rem;
  float: right;
  height: 41rem;
  width: 42rem;
  padding: 3px;
}

.text {
  height: 21rem;
  overflow: auto;
}

.navbar ul {
  display: flex;
  margin-left: 0.8rem;
  margin-top: 3.2rem;
  cursor: pointer;
}

li {
  text-align: center;
  list-style: none;
  padding-right: 5rem;
  font-size: 100px;
  font-weight: 500;
  color: #f5f9fb;
  transition: filter 0.15s ease-in-out, color 0.15s ease-in-out;
}

li:hover {
  filter: blur(0.19rem);
}

h1 {
  font-family: "Tiempos Headline Regular", Times, serif;
  font-size: 3.15rem;
  font-weight: 500;
  text-align: left;
  margin-top: 5.1rem;
  margin-left: 13.5rem;
  color: #f5f9fb;
}

@media only screen and (max-width: 450px) and (min-width: 420px) {
  h1 {
    font-size: 2.2rem;
    margin-top: 3.5rem;
    margin-left: 3rem;
  }
  h3 {
    font-size: 0.875rem;
  }
  .text {
    height: 38rem;
    width: 17rem;
    margin-top: 0.5rem;
    margin-left: 39.7rem;
  }
  li {
    font-size: 1.3rem;
  }
  .navbar {
    display: none;
  }
}

@media only screen and (max-width: 420px) and (min-width: 400px) {
  h1 {
    font-size: 2.2rem;
    margin-top: 3.5rem;
    margin-left: 3rem;
  }
  h3 {
    font-size: 0.875rem;
  }
  .text {
    height: 32.9rem;
    width: 17rem;
    margin-top: 0.5rem;
    margin-left: 39.7rem;
  }
  li {
    font-size: 1.3rem;
  }
  .navbar {
    display: none;
  }
}

@media screen and (max-width: 399px) and (min-width: 340px) {
  h1 {
    font-size: 2.2rem;
    margin-top: 3.5rem;
    margin-left: 2.5rem;
  }
  h3 {
    font-size: 0.875rem;
  }
  .text {
    height: 28rem;
    width: 16rem;
    margin-top: 1rem;
    margin-left: 41.4rem;
    padding: 0rem;
  }
  li {
    font-size: 1.3rem;
  }
  .navbar {
    display: none;
  }
}

@media screen and (max-width: 339px) and (min-width: 300px) {
  h1 {
    font-size: 2rem;
    margin-top: 3rem;
    margin-left: 2rem;
  }
  h3 {
    font-size: 0.875rem;
  }
  .text {
    height: 23.5rem;
    width: 14rem;
    margin-top: 1rem;
    margin-left: 43.6rem;
    padding: 0rem;
  }
  li {
    font-size: 1.3rem;
  }
  .navbar {
    display: none;
  }
}

@media only screen and (max-height: 820px) and (min-height: 800px) {
  h1 {
    font-size: 2.2rem;
    margin-top: 3rem;
    margin-left: 2rem;
  }
  h3 {
    font-size: 0.875rem;
  }
  .text {
    height: 37.5rem!important;
    width: 16rem;
    margin-top: 1rem;
    margin-left: 40.9rem;
    padding: 0rem;
  }
  li {
    font-size: 1.3rem;
  }
  .navbar {
    display: none;
  }
}

@media only screen and (max-height: 840px) and (min-height: 820px) {
  h1 {
    font-size: 2.2rem;
    margin-top: 3rem;
    margin-left: 2rem;
  }
  h3 {
    font-size: 0.875rem;
  }
  .text {
    height: 37.5rem;
    width: 18rem;
    margin-top: 1rem;
    margin-left: 38.9rem;
    padding: 0rem;
  }
  li {
    font-size: 1.3rem;
  }
  .navbar {
    display: none;
  }
}

</style>
