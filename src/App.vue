<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Recetas msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Recetas from './components/Recetas.vue'

export default {
  name: 'app',
  components: {
    Recetas
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat:400,700');
body {
  background-color: rgb(255, 255, 255);
  font-family: 'Montserrat', sans-serif;
  display: grid;
  grid-template-rows: auto;
  justify-items: center;
  padding-top: 40px;
}
body, html {
  margin: 0;
  height: 100%;
}
#app {
    width: 70%;
}
nav {
  padding: 20px 20px 20px 0;
}
</style>
