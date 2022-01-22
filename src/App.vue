<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Terminal msg="Terminal"/>
  </div>
</template>

<script>
import Terminal from './components/Terminal.vue'

export default {
  name: 'App',
  components: {
    Terminal
  }
}
</script>

<style>
body {
  background-color: black;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: whitesmoke;
  margin-top: 60px;
  background-color: black;
}
</style>
