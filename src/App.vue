<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <AppTitle/>
    <Hero/>
  </div>
</template>

<script>

import AppTitle from './components/AppTitle.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    AppTitle,
    Hero
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
