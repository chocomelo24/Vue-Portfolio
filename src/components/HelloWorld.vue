<template>  
<!--Start of Landing-->
        <section class="min-vh-100" id="landing">
            <div class="text">
        <h1>Hello There, I'm Chanique</h1>
        <h2>An Aspiring Web Developer</h2>
            </div>
        </section>
    <!--End of Landing-->
</template>

<script>
export default {
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');
/* CSS Reset */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
  }
  section {
    min-height: 100vh;
    min-width: 100vh;
}

 #landing{
      background-image: url(landing-port.gif);
      background-size: cover;
      height: 100vh;
      width: 100%;
      display: flex;
    align-content: center;
    justify-content: center;
    align-items: center;
     }
    
     .text h1,h2{
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: center;
        color: blue;
        text-shadow: 1px 3px 4px white;
        font-family: 'Lobster', cursive;    
     }

     .text h1 {
        font-size: 70px;
     }
  
     .text h2 {
         font-size: 40px;
     }

     @media only screen and (max-width: 900px) {
        #landing{
            width: 100vh;
            height: 0;
        }
     }


</style>
