<template>
 <Navbar />
 <main id="all">
  <section>
  <HelloWorld />
  </section>
  <section>
  <About />
  </section>
  <section>
  <Resume />
  </section>
  <section>
  <Skills />
  </section>
  <section>
  <Projects />
  </section>
  <section>
  <Testimonials />
  </section>
  <section>
  <Contacts />
</section>
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
#all{
  margin-left: 300px
}

@media only screen and (max-width: 900px) {
  #all{
   margin-left:0;
  }
 }
</style>
