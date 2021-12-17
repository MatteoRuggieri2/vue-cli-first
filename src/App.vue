<template>
  <div id="app">
    <Title />
    <Hero />
    <!-- <img alt="Vue logo" src="./assets/img/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Title from "./components/Title.vue";
import Hero from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    Title,
    Hero
  },
};
</script>

<style lang="scss">
#app {
  text-align: center;
  margin-top: 60px;
}
</style>
