<template>
  <div id="app">
    <ComponentOne :author="author" :skills="skills"></ComponentOne>
  </div>
</template>

<script>
import ComponentOne from "./components/ComponentOne";

export default {
  name: "App",
  components: {
    ComponentOne,
  },
  data() {
    return {
      author: "Arefin Tanweer",
      skills: ["JavaScript", "VueJS"],
    };
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
