<template>
 <Navbar />
 <main>
  <HelloWorld />
  <About />
  <Resume />
  <Skills />
  <Projects />
  <Testimonials />
  <Contacts />

 </main>
  <!-- <router-view /> -->
</template>

<script>
import Navbar from "./components/Navbar.vue";
import About from './components/About.vue';
import HelloWorld from "./components/HelloWorld.vue";
import Resume from "./components/Resume.vue";
import Skills from "./components/Skills.vue";
import Projects from "./components/Projects.vue";
import Testimonials from "./components/Testimonials.vue";
import Contacts from "./components/Contacts.vue";
export default {
  components: {
    Navbar,
    About,
    HelloWorld,
    Resume,
    Skills,
    Projects,
    Testimonials,
    Contacts,
  },
};
</script>
<style>
main{
  margin-left: 300px
}
</style>
