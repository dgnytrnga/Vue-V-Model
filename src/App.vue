<template>
  <div id="app">
    <Vue-Form />
  </div>
</template>

<script>
import VueForm from "./components/Form-App.vue"

export default {
  name: 'App',
  components: {
    VueForm
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
