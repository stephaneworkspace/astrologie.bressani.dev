<template>
  <div id="app" class="center">
    <div class="bg1">
      <div class="bg2">
        <img alt="Vue logo" src="./assets/logo.png" class="logo">
        <p></p>
        <HelloWorld msg="Astrologie"/>
      </div>
    </div>
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
.center {
  width: 1300px;
  display: inline-block;
}
.bg2 {
  border-radius: 25px;
  background-image: linear-gradient(to right, #ffeedd, transparent),
  linear-gradient(to left, #ffeedd, transparent) !important;
  background-repeat: repeat-y, repeat-y;
  background-position: left top, right top;
  background-size: 300px 100%, 300px 100%;
  min-height: 100vh;
}
.bg1 {
  display: inline-block;
  background-image: url("~@/assets/bg.png");
  background-repeat: no-repeat;
}
.logo {
  border-radius: 25px;
  background-color: rgba(204, 153, 51, .1);
  padding: 20px;
  display: block;
  margin-left: auto;
  margin-right: auto;
}

</style>
