<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <p>Hallo Volker, <br />DU packst das!</p>
  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style>
@import url("./assets/reset.css");
</style>
