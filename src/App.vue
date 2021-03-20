<template>
  <div id="app" class="container">
    <LandingPage msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import LandingPage from './components/LandingPage.vue'

export default {
  name: 'App',
  components: {
    LandingPage
  }
}
</script>

<style>
#app {
  text-align: center;
}
</style>
