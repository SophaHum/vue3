<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <img alt="Vue logo" src="./assets/photo_2021-12-27_11-17-59.jpg" />
  <HelloWorld msg="Hello Vue 3 in CodeSandbox! By Dev Pha" />
  <WellCome msg="New testing" />
</template>

<script>
import HelloWorldVue from "./components/HelloWorld.vue";
import WellComeVue from "./components/WellCome.vue";
export default {
  name: "App",
  components: {
    HelloWorld: HelloWorldVue,
    WellCome: WellComeVue,
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
