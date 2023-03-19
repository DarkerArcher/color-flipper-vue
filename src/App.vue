<template>
  <ColorFlipper />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import ColorFlipper from './components/ColorFlipper.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    ColorFlipper
  }
}
</script>

<style>
#app {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
