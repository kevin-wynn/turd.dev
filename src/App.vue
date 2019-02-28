<template>
  <div id="app">
    <Intro/>
  </div>
</template>

<script>
import Intro from "./components/Intro.vue";

export default {
  name: "app",
  components: {
    Intro
  }
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #5d4037;
}
</style>
