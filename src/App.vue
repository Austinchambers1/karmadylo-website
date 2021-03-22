<template>
  <div id="app">
    <LandingPage msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import LandingPage from "./components/LandingPage.vue";

export default {
  name: "App",
  components: {
    LandingPage,
  },
};
</script>

<style>
body,
html {
  height: 100%;
}
.parallax {
  background-image: url("./assets/karmadylo.jpg");
  /* Full height */
  height: 100%;

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
#app {
  text-align: center;
  height: 3000px;
  background-color: #d7c5eb;
}
</style>
