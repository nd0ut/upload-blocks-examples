<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Uploader />
</template>

<script>
import Uploader from "./components/Uploader.vue";

export default {
  name: "App",
  components: {
    Uploader,
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

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
