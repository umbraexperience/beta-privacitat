<template>
  <div id="app">
    <h1 class="title">
      Terms & Privacy
    </h1>
    <div class="textspace">
      <h3 class="text">
        The company, Umbra, Carrer Sant Antoni 1 Edifici Kropotkin, 1ª Planta
        Factoria Cultural Coma Cros, 17190 Salt, Girona proposed as executive
        producer in association with ARTE France, BR and the NFB, a multimedia
        program available on the Internet at URL http://www.umbraexperience.com
        composed of a series of interactive and participatory documentaries
        produced by Brett GAYLOR (hereinafter the “Site”).<br />
        <br />
        The company, Umbra, is editor of this Site.The Site is designed to
        explore the "tracking" universe, that is to say the collection of
        personal data and targeting of Internet users, and allows Internet users
        to discover, through participatory experiences the ways in which their
        personal data is used.<br />
        <br />The present document is intended to define the general terms and
        conditions applicable to the Site and for participating Internet
        users.<br />
        <br />Anyone who wishes to participate in the experiment claims to have
        previously read and expressly accepted these general terms and
        conditions (hereinafter “GTC”).
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

.textspace {
  margin-right: 16.93rem;
  margin-top: 1.9rem;
  float: right;
  height: 39rem;
  width: 42rem;
  padding: 3px;
}

.text {
  height: 21rem;
  overflow: auto;
}

.navbar ul{
  display: flex;
  margin-left: 0.8rem;
  margin-top: 3.2rem;
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

@media screen and (max-width: 400px) {
  h1 {
    font-size: 3.1rem;
    margin-top: 3.3rem;
    margin-left: 3rem;
  }
}

@media screen and (max-width: 450px) {
  h3 {
    font-size: 0.9rem;
    margin-top: -1rem;

  }
}

@media screen and (max-width: 450px) {
  .text {
    height: 20rem;
    width: 19rem;
    margin-top: -3rem;
    margin-left: 39.8rem;
    overflow: hidden;

  }
}

@media screen and (max-width: 450px) {
  li {
    font-size: 1.3rem;
  }
}
</style>
