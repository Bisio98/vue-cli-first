<template>
  <div id="app">
    <Title/>
    <Jumbo/>
  </div>
</template>

<script>
import Title from "./components/title.vue";
import Jumbo from "./components/hero.vue"

export default {
  name: "App",
  components: {
    Title,
    Jumbo
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

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>