<template>
<section class="Nikkie" id="Testimonials">
<h2 class="d-flex justify-content-center align-items center">Testimonials</h2>
 <div class="testimonial">
    <div class="card" v-for="t of testimonials" :key="t.name">
      <div class="layer"></div>
      <div class="content">
        <p>"{{t.testimonial}}"</p>
        <div class="image"><img :src="t.profile" :alt="t.name"> 
        </div>
        <div class="details">
          <h2 class="word">{{ t.name }} - <span>{{t.occupation}}</span></h2>
        </div>
             </div>
    </div>
    
    
  </div>
</section>
</template>
<script>
export default {
    name: "Testimonials",
    data(){
      return {
        testimonials: [
        {

            testimonial: "Chanique is not afraid of seeking clarity with things she does not understand.She will be a core part of improving team morale.",
            profile: "https://i.postimg.cc/QCZYCHKX/Tristan.jpg",
            name: "Tristan",
            occupation: "Colleague",
            },
  
        {
          testimonial: "Chanique is a GOAT🐐. She works well with new work and strives to achieve her best in every situation. I wish Chanique the best in her future as a developer.",
            profile: "https://i.postimg.cc/DZWynftf/jason.jpg",
            name: "Jason",
            occupation: "Lecturer",
            },
  
        {
          testimonial: "🐐🐐👌",
            profile: "https://i.postimg.cc/P5fXQ0fB/ricardo-gomez-angel-o-X-c-UTE-IUo-unsplash.jpg",
            name: "Goat Man",
            occupation: "Goat",
            },
  
        {
          testimonial: "Chanique is a very hardworking person, who gives and does her best in all aspects. She also has a very patient and bubbly personality.",
            profile: "https://i.postimg.cc/MHfRGn99/Cameron-1.jpg",
            name: "Cameron",
            occupation: "Colleague",
            },
   
 
        {
          testimonial: "Chanique is a fun, loving and hard-working person. She always focuses on the job at hand.",
            profile: "https://i.postimg.cc/wB9hkTBB/Sunethia-2.jpg",
            name: "Sunethia",
            occupation: "Colleague",
            },
    ]
      }
    }
}
</script>
<style scoped>
section {
    min-height: 100vh;
    background-image: url(landing.jpg);
   background-size: cover;
}
    body{
  margin:0;
  padding:0;
  
  height:100vh;
  background:#262626;
  color:#fff;
  font-family:sans-serif;

}
.testimonial{
  display:grid;
  grid-template-columns:repeat(auto-fit, minmax(350px, 1fr));
  grid-gap:20px;
}

.card{
  display: flex;
  align-items: center;
}

.testimonial .card{
  position:relative;
  margin:0 auto;
  width:350px;
  background:#333;
  padding:20px;
  box-sizing:border-box;
  text-align:center;
  box-shadow:0 10px 40px rgba(0,0,0,.5);
  overflow:hidden;
}
.testimonial .card .layer{
  position:absolute;
  top:calc(100% - 2px);
  left:0;
  height:100%;
  width:100%;
  background:linear-gradient(#03a9f4, #e91ee3);
  z-index:1;
  transition:0.5s;
}
.testimonial .card:hover .layer{
  top:0;
}
.testimonial .card .content{
  position:relative;
  z-index:2;
}
.testimonial .card .content p{
  font-size:12px;
  line-height:24px;
}
.testimonial .card .content .image{
  width:128px;
  height:128px;
  margin:0 auto;
  border-radius:50%;
  overflow:hidden;
  border:4px solid #fff;
  box-shadow:0 10px 20px
    rgba(0,0,0,.2);
}
.testimonial .card .content .details h2{
  font-size:18px;
}
.testimonial .card .content .details span{
  color:#03a9f4;
  font-size:14px;
  transition:0.5s;
}
.testimonial .card:hover .content .details span{
  color:#fff;
}

h2{
  font-family: 'Lobster', cursive;
}
.word{
  color: white;
}


p{
  color: white;
}
  

img{
  width: 100%;
  border-radius: 50%;
  aspect-ratio: 1;
  object-fit: cover;
}



</style>