<script>
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";
import Login from "./components/Login.vue";

export default {
  components: {
    Navbar,
    Hero,
    Login,
  },
};
</script>

<template>
  <Navbar />
  <Hero />
  <Login />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 10px;
}
</style>
