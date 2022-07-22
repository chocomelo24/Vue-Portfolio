<template>
   <!-- Start of navbar -->
    <nav id="nav-bar">
         <img
        src="https://i.postimg.cc/Kvhs2ZVZ/Chanique.jpg"
        alt=""
        class="female m-auto img-fluid"
        />
        <h1 class="name">Chanique Mansoor</h1>
        <div class="socials">
            <a href="https://www.linkedin.com/in/chanique-mansoor-235a83237/" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
            <a href="https://github.com/chocomelo24"><i class="fa-brands fa-github" target="_blank"></i></a>
            <a href="https://app.netlify.com/teams/mansoorchanique/overview?_ga=2.68972633.99398783.1652165200-1667476014.1652165200" target="_blank"><i class='bx bxl-netlify'></i></a>
        </div>
        <ul class="nav-links ">
            <li class="nav-link">
                <a href="#landing" class="link"><i class="bx bx-home"></i>Home</a>
            </li>
            <li class="nav-link">
            <a href="#about" class="link"><i class="bx bx-user"></i>About</a>
        </li>
        <li class="nav-link">
            <a href="#resume" class="link"
            ><i class="bx bx-file-blank"></i>Resume</a
            >
        </li>
            <li class="nav-link">
                <a href="#skills" class="link"
                ><i class="fa-solid fa-bars-progress"></i>Skills</a
                >
            </li>
        <li class="nav-link">
            <a href="#projects" class="link"
            ><i class="bx bx-book-content"></i>Projects</a
            >
        </li>
        <li class="nav-link">
            <a href="#Testimonials" class="link"
            ><i class="fa-solid fa-comment-dots"></i>Testimonials</a
            >
        </li>
        <li class="nav-link">
            <a href="#contacts" class="link"
            ><i class="bx bx-envelope"></i>Contacts</a
            >
        </li>
    </ul>
    <footer>
        <p><small>© 
            Copyright 2022 All rights reserved. Made  by Chanique Mansoor</small></p>
        </footer>
    </nav>
    <button class="button bg-light d-flex" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight"><i class="fa-solid fa-bars"></i><p class="ms-2 mt-2"></p></button>

<div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasRight" aria-labelledby="offcanvasRightLabel">
  <div class="offcanvas-header">
    <button type="button" class="btn-close bg-light text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
  </div>
  <div class="offcanvas-body">
  <nav id="nav-bar2">
         <img
        src="https://i.postimg.cc/Kvhs2ZVZ/Chanique.jpg"
        alt=""
        class="female m-auto img-fluid"
        />
        <h1 class="name">Chanique Mansoor</h1>
        <div class="socials">
            <a href="https://www.linkedin.com/in/chanique-mansoor-235a83237/" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
            <a href="https://github.com/chocomelo24"><i class="fa-brands fa-github" target="_blank"></i></a>
            <a href="https://app.netlify.com/teams/mansoorchanique/overview?_ga=2.68972633.99398783.1652165200-1667476014.1652165200" target="_blank"><i class='bx bxl-netlify'></i></a>
        </div>
        <ul class="nav-links ">
            <li class="nav-link">
                <a href="#landing" class="link"><i class="bx bx-home"></i>Home</a>
            </li>
            <li class="nav-link">
            <a href="#about" class="link"><i class="bx bx-user"></i>About</a>
        </li>
        <li class="nav-link">
            <a href="#resume" class="link"
            ><i class="bx bx-file-blank"></i>Resume</a
            >
        </li>
            <li class="nav-link">
                <a href="#skills" class="link"
                ><i class="fa-solid fa-bars-progress"></i>Skills</a
                >
            </li>
        <li class="nav-link">
            <a href="#projects" class="link"
            ><i class="bx bx-book-content"></i>Projects</a
            >
        </li>
        <li class="nav-link">
            <a href="#Testimonials" class="link"
            ><i class="fa-solid fa-comment-dots"></i>Testimonials</a
            >
        </li>
        <li class="nav-link">
            <a href="#contacts" class="link"
            ><i class="bx bx-envelope"></i>Contacts</a
            >
        </li>
    </ul>
    <footer>
        <p><small>© 
            Copyright 2022 All rights reserved. Made  by Chanique Mansoor</small></p>
        </footer>
    </nav>
  </div>
</div>
    <!--End of Navbar-->  
</template>
<script>
export default {
    name: "Navbar",
}
</script>
<style scoped>
    #nav-bar {
    border: 1px solid;
    width: 300px;
    height: 100%;
    background-color: #040B14;
    left: 0;
    position: fixed;
  }
  #nav-bar2{
    background-color: #040B14;
    color: white;
  }
  .offcanvas{
    background-color: #040B14;
  }
  .button{
    display: none;
  }
  .female {
    display: block;
    width: 120px;
    aspect-ratio: 1;
    border-radius: 100%;
    border: 8px solid #2C2F3F;
    object-fit: cover;
  }
  #nav-bar h1 {
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 24px;
    font-family: "Poppins", sans-serif;
    color: white;
    font-weight: 600;
    margin-block-start: 0.67em;
    margin-block-end: 0.67em;
  }
  .socials {
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    margin: 16px 0px 0px;
  }
  .socials i:hover {
    background-color: #149DDD;
  }
  .socials i {
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    border: 1px solid #2C2F3F;
    border-radius: 50%;
    background-color: #212431;
    font-size: 18px;
    margin-right: 10px;
    color: white;
    width: 36px;
    height: 36px;
  }
  .nav-links {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    margin-left: 10%;
    padding: 10px 0px 0px;
    font-family: "Open Sans", sans-serif;
    
  }
  ul i {
    font-size: 24px;
  }
  .nav-link {
    list-style: none;
    font-size: 15px;
    padding: 30px 0px 0px;
    
  }
  a {
    text-decoration: none !important;
    color: #A8A9B4;
  } 
  a.link {
    display: flex;
    align-items: center;
    gap: 10px;
  }
  li:hover > a {
    color: white;
  }
  li:hover > a > i {
    color: #149DDD;
  }
  li:visited > a {
    color: white;
  }
  li:visited > a > i {
    color: #149DDD;
  }
  li:focus > a {
    color: white;
  }
  li:focus > a > i {
    color: #149DDD;
  }
  .btn-primary {
    right: 30px;
    position: fixed;
    font-size: 25px;
    height: 50px;
    width: 50px;
    border-radius: 50%; 
    background-color: #149DDD;
    color: white;
  }
  
 #content {
     margin-left: 300px;
 }

 .btn {
   position: absolute;
   display: flex;
   justify-content: end;
   align-items: center;
 }
@media screen and (max-width: 901px){
  #nav-bar{
    display: none;
  }
  #nav-bar2{
    right:0;
  }
  .button{
    display: block;
    position: fixed;
    z-index: 1000;
    top: 50px;
    left: 10px;
  }
  .skills{
    width: 50%;
  }
} 
</style>