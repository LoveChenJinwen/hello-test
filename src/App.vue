<template>
  <div id="app">
    test
    <img alt="Vue logo" src="./assets/logo.png">
    <vueCanvasNest :config="config" />
  </div>
</template>

<script>
import vueCanvasNest from 'vue-canvas-nest'
export default {
  name: 'app',
  components: {
    vueCanvasNest
  },
  data() {
    return {
      config: {
        color: "49,126,243",
        count: 66
      }
    }
  }
}
</script>

<style>
html {
  /* background-color: #1e1e1e; */
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
