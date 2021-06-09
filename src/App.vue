<template>
  <headers/>
</template>

<script lang="ts">

import "./components/Headers.vue";
import Headers from "./components/Headers.vue";
export default {
  name: "App",
  components: {
    Headers,
  },
};
</script>

<style>
* {
  padding: 0px;
  margin: 0px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
