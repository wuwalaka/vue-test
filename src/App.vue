<template>
  <div id="app">
    <box />
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <img />
  </div>
</template>

<script>
import Box from "../src/components/Box";
import HelloWorld from "./components/HelloWorld.vue";
import HelloWorld from "./components/HelloWorld.vue";
import Img from "./components/Img.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Box,
    Img,
  },
};
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
