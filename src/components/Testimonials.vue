<template>
   <!--Start of Testimonials-->
        <section id="testimonials">
        <h2 class="d-flex justify-content-center align-items center">Testimonials</h2>
        <div id="carouselExampleCaptions" class="carousel slide row" data-bs-ride="carousel">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3" aria-label="Slide 4"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="4" aria-label="Slide 5"></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item carousel-padding active">
              <div class="d-flex justify-content-center">
                <img src="https://i.postimg.cc/QCZYCHKX/Tristan.jpg" class="mimi d-block" alt="Male">
              </div>
              <div class="carousel-caption ">
                <h5>Tristan</h5>
                <p>"Chanique is not afraid of seeking clarity with things she does not understand.She will be a core part of improving team morale."</p>
              </div>
            </div>
            <div class="carousel-item carousel-padding ">
              <div class="d-flex justify-content-center">
                <img src="https://i.postimg.cc/DZWynftf/jason.jpg" class="jay d-block" alt="Male">
              </div>
              <div class="carousel-caption ">
                <h5>Jason</h5>
                <p>"Chanique is a very kind and social individual who brightens the day of the people she surrounds herself with. She works well with new work and strives to achieve her best in every situation. I wish Chanique the best in her future as a developer."</p>
              </div>
            </div>
            <div class="carousel-item carousel-padding">
              <div class="d-flex justify-content-center">
                <img src="https://i.postimg.cc/MHfRGn99/Cameron-1.jpg
" class="cam d-block" alt="Women">
              </div>
              <div class="carousel-caption ">
                <h5>Cameron</h5>
                <p>"Chanique is a very hardworking person, who gives and does her best in all aspects. She also has a very patient and bubbly personality."</p>
              </div>
            </div>

            <div class="carousel-item carousel-padding">
              <div class="d-flex justify-content-center"><img src="https://i.postimg.cc/hjjTHyTW/Zachary-2.jpg
" class="zach d-block" alt="Male"></div>
              <div class="carousel-caption d-none d-md-block">
                <h5>Zachary</h5>
                <p>"Chanique Mansoor is a bright and talented individual, who pushes to improve herself.She has a great sense of humour.She will be great attribute in any working environment."</p>
              </div>
            </div>
            <div class="carousel-item carousel-padding">
              <div class="d-flex justify-content-center align-items-center"><img src="https://i.postimg.cc/wB9hkTBB/Sunethia-2.jpg
" class="sun d-block" alt="Women"></div>
              <div class="carousel-caption d-none d-md-block">
                <h5>Sunethia</h5>
                <p>"Chanique is a fun, loving and hard-working person. She always focuses on the job at hand."</p>
              </div>
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
            <span class="carousel-control-prev-i2 con" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
        </section>
      <!--Start of Testimonials-->
</template>
<script>
export default {
    name: "Testimonials",
}

let testimonials = [
        {
            name: "Mika",
            testimonials: "Chanique is not afraid of seeking clarity with things she does not understand.She will be a core part of improving team morale.",
            occupation: "Student",
            profile: "./images/Mika.jpg",
        },
  
        {
            name: "Jason",
            testimonials: "Chanique is a very kind and social individual who brightens the day of the people she surrounds herself with. She works well with new work and strives to achieve her best in every situation. I wish Chanique the best in her future as a developer.",
            occupation: "Lecturer",
            profile: "https://i.postimg.cc/DZWynftf/jason.jpg",
        },
  
        {
            name: "Cameron",
            testimonials: "Chanique is a very hardworking person, who gives and does her best in all aspects. She also has a very patient and bubbly personality.",
            occupation: "Student",
            profile: "https://i.postimg.cc/MHfRGn99/Cameron-1.jpg",
        },
   
        {
            name: "Zachary",
            testimonials: "Chanique Mansoor is a bright and talented individual, who pushes to improve herself.She has a great sense of humour.She will be great attribute in any working environment.",
            occupation: "Student",
            profile: "https://i.postimg.cc/hjjTHyTW/Zachary-2.jpg",
        },
 
        {
            name: "Sunethia",
            testimonials: "Chanique is a fun, loving and hard-working person. She always focuses on the job at hand.",
            occupation: "Student",
            profile: "https://i.postimg.cc/wB9hkTBB/Sunethia-2.jpg",
        },
    ];
    
</script>
<style scoped>
     #testimonials{
      background-image: url(landing.jpg);
      background-size: cover;
      height: 100vh;
      width: 100%;
      padding-top: 55px;
      
    }

    .carousel-item {
      background-color: lightgray;
    }

    .carousel-caption {
       color: black;
    }

    .carousel-padding{
      padding-bottom: 140px;
    }
    .carousel-indicators{
      margin-left: 0%;
    }
/* 
    .carousel-indicators {
      position: absolute;
      right: 0;
      bottom: 0;
      left: 0;
      z-index: 2;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 0;
      margin-right: 15%;
      margin-bottom: 1rem;
      list-style: none;
    } */

    .mimi{
      width: 300px;
      height: 400px;
    }

    .jay{
      width: 300px;
      height: 400px;
    }
    


    .zach{
      width: 300px;
      height: 400px;
    }

    .cam{
      width: 300px;
      height: 400px;
      
    }
  

    .sun{
      width: 300px;
      height: 400px;
    }

</style>