<template>
  <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  <MyMenu/>

</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import MyMenu from "./components/MyMenu.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    MyMenu,
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
