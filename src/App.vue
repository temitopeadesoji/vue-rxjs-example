<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <RxJs />
</template>

<script>
import RxJs from "./components/RxJs.vue";

export default {
  name: "App",
  components: {
    RxJs,
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
