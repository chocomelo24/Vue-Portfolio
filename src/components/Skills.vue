<template>
   <!--Start of Skills-->
        <section id="skills" class="d-flex flex-column">
            <div class="Skills">
              <div class="card">
                <div class="skills-card">
                  <h2>Skills</h2>
                <p></p>
                <div class="skills-col">
                    <div class="skills-title">
                      <h3>HTML 70%</h3>
                        <p></p>
                      </div>
                    <meter value="70" min="0" max="100">2 out of 10</meter>
    
                  </div>
                <div class="skills-col">
                    <div class="skills-title">
                      <h3>CSS 50%</h3>
                      <p></p>
                    </div>
                    <meter value="50" min="0" max="100">2 out of 10</meter>
    
                </div>
                <div class="skills-col">
                    <div class="skills-title">
                        <h3>Javascript 20%</h3>
                        <p></p>
                      </div>
                      <meter value="20" min="0" max="100">2 out of 10</meter>
    
                    </div>
                <div class="skills-col">
                    <div class="skills-title">
                      <h3>VUE 20%</h3>
                      <p></p>
                    </div>
                    <meter value="20" min="0" max="100">2 out of 10</meter>
                    
                </div>
                <div class="skills-col">
                  <div class="skills-title">
                    <h3>Node 20%</h3>
                        <p></p>
                 </div>
                    <meter value="20" min="0" max="100">2 out of 10</meter>
    
                  </div>
                <div class="skills-col">
                    <div class="skills-title">
                      <h3>Databases 20%</h3>
                        <p></p>
                      </div>
                      <meter value="20" min="0" max="100">2 out of 10</meter>
    
                </div>
                </div>
              </div>
            </div>
            <div class="skill-icon">
              <div class="row">
              <div class="soos col-md-4">
                <i class="fa-brands fa-html5"></i>
                <h6>HTML</h6>
              </div>
              <div class="soos col-md-4">
                <i class="fa-brands fa-css3"></i>
                <h6>CSS</h6>
              </div>
              <div class="soos col-md-4">
                <i class="fa-brands fa-js"></i>
                <h6>Javascript</h6>
              </div>
              <div class="soos col-md-4">
                <i class="fa-brands fa-vuejs"></i>
                <h6>VueJS</h6>
              </div>
              <div class="soos col-md-4">
                <i class="fa-brands fa-node-js"></i>
                <h6>Node</h6>
              </div>
              <div class="soos col-md-4">
                <i class="fa-solid fa-database"></i>
                <h6>Database</h6>
              </div>
            </div>
            </div>
        </section>
      <!--End of Skills--> 
</template>
<script>
export default {
   name: "Skills", 
}
</script>
<style scoped>
    #skills{
        background-image: url(landing.jpg);
        background-size: cover;
         display: flex;
         justify-content: center;
    }
    .skills-title{
        display:flex;
        justify-content: space-between;
        color:blue;
    }

    .Skills{
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      }

    .skill-icon {
      font-size: 80px;
      display: flex;
      justify-content: center;
    }

    .row .soos :hover {
      color: blue;
    }

    .card {
      background-color: lightgray;
    }

    h2{
        color:blue;
        
    }
    
    .skills-col{
        display: flex;
        flex-direction: column;
        width: 500px;
    }
    meter{
        width: 100%;
    }
    .skills-card{
      width:300px
    }
    .skills-col{
      width: 50%;
    }
</style>