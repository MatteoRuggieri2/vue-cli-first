<template>
  <div id="app">
    <Title />
    <!-- <img alt="Vue logo" src="./assets/img/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Title from "./components/Title.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    Title
  },
};
</script>

<style lang="scss">
#app {
  text-align: center;
  margin-top: 60px;
}
</style>
