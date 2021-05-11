<template>
  <div id="app">
    <box />
    <tab />
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import Box from "../src/components/Box";
import HelloWorld from "./components/HelloWorld.vue";
import Tab from "./components/Tab.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Box,
    Tab,
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
