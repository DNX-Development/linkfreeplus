<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <LinkPage />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import LinkPage from "./components/LinkPage.vue";

export default {
  name: 'App',
  components: {
    LinkPage
  }
}
</script>

<style>
@import "./assets/galaxy/css/style.css";
@import "./assets/galaxy/css/font-awesome.min.css";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
