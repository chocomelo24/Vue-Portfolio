<template>
  <!--Start of Contacts-->
        <section id="contacts">
          <h2 class="d-flex justify-content-center align-items center">Contacts</h2>
          <form action="https://formspree.io/f/xnqwgend" target="_blank"
          method="post">
          <div class="row">
            <div class="col-md-6 mb-3">
              <label for="name" class="form-label">Name and Surname </label>
              <input type="text" class="form-control" id="name" name="name" aria-describedby="emailHelp" required>
            </div>

            <div class="col-md-6 mb-3">
              <label for="email" class="form-label">Email address</label>
              <input type="email" class="form-control" id="email" name="email" aria-describedby="emailHelp" required>
            </div>
          </div>
            <div class="mb-3">
              <label for="phone" class="form-label">Phone Number</label>
              <input type="tel" class="form-control" id="phone" name="phone" required>
            </div>

            <div class="mb-3">
              <textarea placeholder="Message" required id="mess"></textarea>
            </div>
         
            <button type="submit" class="btn btn-dark">Submit</button>
          </form>
        </section>
      <!--End of Contacts-->  
</template>
<script>
export default {
 name: 'Contacts',  
}
</script>
<style scoped>
    #contacts{
      background-image: url(landing.jpg);
      background-size: cover;
      height: 100vh;
      width: 100%;
      padding: 100px;
    }
    
#mess {
  height: 180px;
  width: 100%;
}

h2{
  font-family: 'Lobster', cursive;
}

@media only screen and (max-width: 900px) {
  #contacts{
  width: 100vh;
  height: 0;
  padding: 0;
  }

  #mess{
    width: 90%;
  }

  .mb-3{
    margin-left: 20px;
  }

  .form control{
    width: 80%;
  }
}
</style>