<template>
  <div>
    <br />
    <Navbar/>
    <Meals />
  </div>
</template>

<script>
import Meals from "./components/Meals.vue";
import Navbar from "./components/Navbar.vue";

export default {
  name: "App",
  components: {
    Meals,
    Navbar,
  }
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
