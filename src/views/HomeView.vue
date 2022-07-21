<template>
 <About/>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import About from "../components/About.vue";
export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    About,
  }
 
}
</script>
