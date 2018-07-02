<template>
  <div id="app">
    <vue-rate/>
  </div>
</template>

<script>
import vueRate from './components/vue-rate.vue'

export default {
  name: 'App',
  components: {
    vueRate
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
