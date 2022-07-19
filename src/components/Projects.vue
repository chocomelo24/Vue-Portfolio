<template>
 <!--Start of Projects-->
        <section id="projects">
          <div class="container-fluid">
            <h2 class="d-flex justify-content-center align-items center">Projects</h2>
            <div class="d-flex flex-wrap">
              <div class="col-md-4">
                <img src="https://i.postimg.cc/zXG0vjHx/1st-port-project.png" alt="project" class="p-image">
                <p class="text-center">First Portfolio</p>
                <div class="project_btn d-flex justify-content-center">
                  <a href="https://unique-crumble-d487cf.netlify.app" target="_blank"><button>Live</button></a>
                  <a href="https://github.com/chocomelo24/portfolio.git" target="_blank"><button>Github</button></a>
                </div>
              </div>
            
              <div class="col-md-4">
                <img src="https://i.postimg.cc/dQpLZQLg/calculator-project.png" alt="project" class="p-image">
                <p class="text-center">Calculator Project</p>
                <div class="project_btn d-flex justify-content-center">
                  <a href="https://tiny-cat-8c838b.netlify.app/" target="_blank"><button>Live</button></a>
                  <a href="https://github.com/chocomelo24/My-Calculator.git" target="_blank"><button>Github</button></a>
                </div>
              </div>
            
              <div class="col-md-4">
                <img src="https://i.postimg.cc/L4czfFXQ/holiday-project.png" alt="project" class="p-image">
                <p class="text-center">Holiday Project</p>
                <div class="project_btn d-flex justify-content-center">
                  <a href="https://polite-swan-9e70b8.netlify.app/" target="_blank"><button>Live</button></a>
                  <a href="https://github.com/chocomelo24/Holiday-destination.git" target="_blank"><button>Github</button></a>
                </div>  
              </div>

              <div class="col-md-4">
                  <img src="https://i.postimg.cc/P5rNvSmF/restaurant.png" alt="project" class="p-image">
                  <p class="text-center">Restaurantly</p>
                  <div class="project_btn d-flex justify-content-center">
                    <a href="https://spectacular-chimera-f08961.netlify.app" target="_blank"><button>Live</button></a>
                    <a href="https://github.com/chocomelo24/Restaurant.git" target="_blank"><button>Github</button></a>
                  </div>
              </div>

              <div class="col-md-4">
                    <img src="https://i.postimg.cc/Dw9k3Zyd/mock-Copy.png" alt="project" class="p-image">
                    <p class="text-center">Mock Portfolio</p>
                    <div class="project_btn d-flex justify-content-center">
                      <a href="https://dazzling-kitsune-3699f5.netlify.app/" target="_blank"><button>Live</button></a>
                      <a href="https://github.com/chocomelo24/Mock-portfolio.git" target="_blank"><button>Github</button></a>
                    </div>
              </div>
              

              </div>
          </div>
   </section>
   <!--End of Projects-->
</template>
<script>
export default {
  name: "Projects",
}


const projects= [
    {
        title: "First Porfolio",
        description: "My first portfolio",
        techStack: "HTML/CSS/JS",
        github: "https://github.com/chocomelo24/portfolio.git",
        live: "https://unique-crumble-d487cf.netlify.app",
        imgURL: "https://i.postimg.cc/zXG0vjHx/1st-port-project.png",
    },

        {
            title: "Caculator Project",
            description: "My first Calculator Project",
            techStack: "HTML/CSS/JS",
            github: "https://github.com/chocomelo24/My-Calculator.git",
            live: "https://tiny-cat-8c838b.netlify.app/",
            imgURL: "https://i.postimg.cc/dQpLZQLg/calculator-project.png",
        },
   
            {
                title: "Holiday Project",
                description: "My first holiday project",
                techStack: "HTML/CSS/JS",
                github: "https://github.com/chocomelo24/Holiday-destination.git",
                live: "https://polite-swan-9e70b8.netlify.app/",
                imgURL: "https://i.postimg.cc/L4czfFXQ/holiday-project.png",
            },

                {
                    title: "Restaurantly",
                    description: "My Restaurantly project",
                    techStack: "HTML/CSS/JS",
                    github: "https://github.com/chocomelo24/Restaurant.git",
                    live: "https://spectacular-chimera-f08961.netlify.app",
                    imgURL: "https://i.postimg.cc/P5rNvSmF/restaurant.png",
                },
  
                    {
                        title: "Mock Portfolio",
                        description: "My Mock Porfolio project",
                        techStack: "HTML/CSS/JS",
                        github: "https://github.com/chocomelo24/Mock-portfolio.git",
                        live: "https://dazzling-kitsune-3699f5.netlify.app/",
                        imgURL: "https://i.postimg.cc/Dw9k3Zyd/mock-Copy.png",
                    },
                    ];
</script>
<style scoped>
    #projects{
  background-image: url(landing.jpg);
  background-size: cover;
  height: 100vh;
  width: 100%;
}

.p-image {
  width: 222px;
  aspect-ratio: 1;
  padding-top: 20px;
  margin-left: 75px;
}
.project_btn button{
  width: 80px;
  border-radius: 20px;
  align-items: center;
}

.p-image:hover {
  transform:scale(1.2)
}

</style>