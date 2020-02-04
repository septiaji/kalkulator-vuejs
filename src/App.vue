<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Kalkulator/>
  </div>
</template>

<script>
import Kalkulator from './components/Kalkulator.vue'

export default {
  name: 'app',
  components: {
    Kalkulator
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
