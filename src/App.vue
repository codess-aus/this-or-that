<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/microsoftsource.png"> -->
    <DetectImage msg="What do you see"/>
  </div>
</template>

<script>
import DetectImage from './components/DetectImage.vue'

export default {
  name: 'App',
  components: {
    DetectImage
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
