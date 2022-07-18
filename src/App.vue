<template>
 <Navbar />
  <!-- <router-view /> -->
  <HelloWorld />
  <About />
</template>

<script>
import About from './components/About.vue';
import HelloWorld from "./components/HelloWorld.vue";
import Navbar from "./components/Navbar.vue";
export default {
  components: {
    Navbar,
    About,
    HelloWorld,
  },
};
</script>
<style>
</style>
