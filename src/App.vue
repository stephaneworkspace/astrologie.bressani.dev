<template>
  <div id="app" class="bg">
    <img alt="Vue logo" src="./assets/logo.png">
    <p></p>
    <HelloWorld msg="Astrologie - bressani.dev"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
.bg {
  background-image: url("~@/assets/bg.png");
}
</style>
