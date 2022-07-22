<template>
<!--Start of About-->
        <section class="mt-3" id="about">
            <div class="container-fluid">
            <div class="row flex-sm-row flex-md-row">
            <div  data-aos="fade-left" class="about-title col-md-6 text-center ">
              <div class="card">
                <div class="card-body">
                  <div data-aos="fade-up-left">
                    <h2>About me</h2>
                  </div>
                <div class="mt-4 bio">
                  <h3>Bio</h3>
I like to describe myself as an extroverted - introvert, someone who loves outgoing yet reserved and humbled. I love gaining new experiences and exploring every aspect of life. I've always wanted to do coding because I was intrigued by how websites work and interested in how applications are developed.
I became interested in coding at a young age. I would try and fiddle around trying to figure out how certain codes made up certain websites. After I matriculated in 2019 I went to study IT and it wasn't really what I wanted to do. A few years later after working in different career fields, I came across Life Choices Academy and their coding course. I immediately knew I had to apply after doing research on their curriculum and what I could expect, it was exactly what I had been wanting to learn all this time. I am learning new things every day and it's fascinating especially CSS because I love the styling aspect. I  appreciate that I got an opportunity to study at the Academy.
              </div>
              <div data-aos="fade-up-left" class="passion d-flex flex-column text-center justify-content-center"><h4>Passion Board</h4>
                singing, dancing, soccer, karate, judo, reading, song-writing, gaming, hiking, photography.
                
                </div>
                <div  data-aos="fade-up-left">
                  <h4>Soft Skills</h4>
leadership, problem-solving, teamwork, listener, communication.
                  </div>
                </div>
              </div>
            </div>
            <div class="col-md-6 d-flex flex-column">
              <div class="img d-flex justify-content-center mb-5"><img src="https://i.postimg.cc/NjYMmcrb/me.jpg
" alt="Me" class="nikkie img-fluid"></div> 
              <div data-aos="fade-right" class="personal d-flex flex-column text-center justify-content-center"><h4>Personal details:</h4>
               <div>Full name: Chanique Chelsea Mansoor</div>  
               <div> Date of birth:24/02/2001</div>
               <div>Gender: Female</div> 
               <div>Location: Manenberg</div> 
               <div> Cell Phone number: +27 63 247 8567</div>
               <div>Email Address: mansoorchanique@gmail.com</div> 
               <div> Willing to Relocate: Yes</div>
                

              </div>
               </div>
            </div>
            </div>
        </section>
      <!--End of About-->
</template>
<script>
import AOS from 'aos'

export default {
    name: "About",
    mounted() {
    AOS.init()
  },
}
</script>
<style scoped>
  #about{

         background-image: url(landing.jpg);
         background-size: cover;
         display: flex;
         align-items: center;
       }

       

     .about-title > h2 {
         justify-content: center;
         align-items: center;
     }
     h2, h3, h4{
        font-family: 'Lobster', cursive;
      }
     
     .nikkie {
         height: 350px;
         width: 300px;
         float: right;
         border-radius: 50%;
     }
</style>