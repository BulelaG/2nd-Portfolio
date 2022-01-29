<template>
  <!-- <div id="nav">
     <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
     <router-link to="/projects">Projects</router-link> |
      <router-link to="/testimonials">Testimonials</router-link> |
      <router-linkrouter-link to="/contact">Contact</router-link> 
       </div> -->
<!-- The Nav -->
<div id="nav">
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <router-link class="navbar-brand" to="/">
     <img
          id="logo"
          class="d-block mx-auto mb-4 img-responsive"
          src="./assets/NeededFiles/LOGO.png"
          alt=""
          style="border: 3px solid white;"
          width="80"
          border-radius="45%"
          height="80"
        />
  </router-link>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <div class="navbar-nav">
      <router-link id="menu" to="/" class="nav-item nav-link active" >Home <span class="sr-only"></span></router-link>
      <router-link id="menu" to="/about" class="nav-item nav-link" >About</router-link>
            <router-link id="menu" to="/timeline" class="nav-item nav-link" >Timeline</router-link>
      <router-link id="menu" to="/projects" class="nav-item nav-link" >Projects</router-link>
      <router-link id="menu" to="/testimonials" class="nav-item nav-link" >Testimonials</router-link>
      <router-link  id="menu" to="/contact" class="nav-item nav-link" >Contact</router-link>
    </div>
  </div>
</nav>
  </div>
<!-- The Nav -end-->


 
  
  
  <router-view/>

  <Footer/>
</template>



<script>
// @ is an alias to /src

import Navbar from '@/components/navbar.vue';
import Footer from '@/components/Footer.vue';
import LandingPage from '@/components/LandingPage.vue';


export default {

  components: {
   
    Navbar,
    Footer,
    LandingPage
  }
}
</script>


<style>

 

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
   overflow-x: hidden;
   
}


#nav {
  padding: ;
  background-color: white;
  position: fixed;
  padding-top: 0;
  padding-bottom: 0;
  width: 100%;
  z-index: 1;
}
a{
  padding-right:1100px ;
   padding-top: 0;
  padding-bottom: 0;
}

#nav a {
  font-weight: normal;
  color: #2c3e50;
  padding:px;
  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}

#nav a.router-link-exact-active {
 
  color: #507597;
}
#menu{
  font-size: 1.5em;
}
/* -----------------------------------------Landing styling---------------------------------------------------------------------- */
#landing-page{
    box-sizing: content-box;
    background-color: #ececec;
    /* background-image: url(keyboard.jpg); */
    object-fit: cover;   
}
#landing-photo{
    border-radius: 50%;
    border-style: solid;
    border: 8px;
    border-color: rgb(228, 215, 215);
}

</style>
