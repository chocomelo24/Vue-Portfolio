<template>
  <!--Start of Resume-->
    <section id="resume">
        <div class="timelines">
              </div>
              <div class="timeline education">
                <h2 class="timeline-title">Resume</h2>
                <div class="timeline-items">
                      <div class="timeline-item" v-for="r of resume" :key="r">
                        <h3>{{r.occupation}}</h3>
                        <time datetime="2017/2019">{{ r.date }}</time>
                        <div class="location">{{r.place}}</div>
                      </div>
                    </div>
                  </div>
    </section>
      <!--End of Resume-->
</template>
<script>
export default {
    name: "Resume",
    data(){
      return {
        resume: [
        {
            date: "2017-2019",
            place: "Phoenix Secondary School",
            occupation: "Student",
            responsabilities: "Learn",
        },
   
        {
            date: "2020-2021",
            place: "Little Bugs Educare",
            occupation: "Teachers Assistent",
            responsabilities: "Teach Litracy And Numracy.",
        },
   
        {
            date: "2019",
            place: "Wimpy",
            occupation: "Hostess",
            responsabilities: "Greet,seat and serve guests.",
        },
    ]
      }
    }
}

</script>
<style scoped>
         #resume{
         background-image: url(landing.jpg);
         background-size: cover;
         padding: 20px
     }
     .section title h2{
        font-size: 32px;
        font-weight: bold;
        margin-bottom: 15px;
        padding-bottom:15px;
        position: relative;
        color: purple;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    
    .header{
        font-size: 20px;
        color: white;
    }
    
    .section title p{
        color: purple;
    }
    
    
    .section-title h2{
        font-size: 32px;
        font-weight: bold;
        margin-bottom: 15px;
        position: relative;
        color: purple;
        text-shadow: 2px 3px 8px solid black;
        font-family: "Playfair Display",serif;
        display: flex;
        justify-content: center;
        align-items: center;
        }
    .timelines {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-evenly;
      align-items: center;
      background-color: transparent;
    }    
   
    
    .timeline-item {
      margin-bottom: 2em;
    }
    .timeline-item h3 {
      font-size: 1em;
      font-weight: bold;
      text-transform: uppercase;
      margin: 0;
      position: relative;
    }
    .timeline-item h3::before {
      content: "";
      position: absolute;
      left: -2.35em;
      background-color: blue;
      width: 0.7em;
      height: 0.7em;
      border-radius: 50%;
      transform: translate(-0.5px, 0.2em);
    }
    
    .timeline-items {
      /* margin: 2em; */
      padding: 0.01em 0 3em 2em;
      border-left: 1px solid blue;
    }
    
    .timeline-item {
      margin-top: -0.3em;
      background-color:lightgray;
      border-radius: 10px;
      padding: 20px;
    }
    .timeline-item time {
      display: block;
      float: left;
      background-color:#c2c1c2;
      padding: 0.2em 0.4em;
    }
    .timeline-item > * {
      margin: 1em 0;
    }
    .timeline-item .location {
      clear: both;
      font-size: 0.85em;
      font-style: italic;
    }

    @media only screen and (max-width: 900px) {
      /* #resume{
         94vh;
        height: 0;
      } */
    }
</style>