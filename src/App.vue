<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <MessagesComponent />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import MessagesComponent from "./components/MessagesComponent.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    MessagesComponent,
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
