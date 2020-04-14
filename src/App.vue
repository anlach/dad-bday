<template>
  <div id="app">
    <birthday msg="Happy Birthday!"/>
    <img alt="People on boat" src="./assets/dadonboat.jpg">
    <cake></cake>
  </div>
</template>

<script>
import birthday from './components/birthday.vue'
import cake from './components/cake.vue'

export default {
  name: 'App',
  components: {
    birthday,
    cake
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
