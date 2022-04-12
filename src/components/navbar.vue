<template>
    <div id= "nav">
         <button class="btn btn-primary offie" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight">Toggle right offcanvas</button>


<!-- big screen -->
<nav width="140%" height="40%" class="navbar navbar-expand-lg navbar-light bg-light">

<router-link style="  padding-right:50% ;
" class="navbar-brand" to="/">
     <img href="/"
          id="logo"
          class="d-block mx-auto mb-4 img-responsive"
          src="@/assets/NeededFiles/LOGO.png"
          alt=""
          style="border: 1px solid white;"
          width="80"
          border-radius="45%"
          height="40"
        />
  </router-link>  
   <button class="btn offie btn-secondary" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight"> <span class="navbar-toggler-icon"></span></button>

  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <div class="navbar-nav">
      <router-link id="menu" to="/" class="nav-item nav-link active" >Home <span class="sr-only"></span></router-link>
      <router-link id="menu" to="/about" class="nav-item nav-link" > About </router-link>
      <router-link id="menu" to="/timeline" class="nav-item nav-link" > Timeline </router-link>
      <router-link id="menu" to="/projects" class="nav-item nav-link" > Projects </router-link>
      <router-link id="menu" to="/testimonials" class="nav-item nav-link" > Testimonials </router-link>
      <router-link  id="menu" to="/contact" class="nav-item nav-link" > Contact </router-link>
    </div>
  </div>
</nav>

    </div>
    <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasRight" aria-labelledby="offcanvasRightLabel">
  <div class="offcanvas-header">
    <h5 id="offcanvasRightLabel">Menu</h5>
    <button width="60px" type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
  </div>
  <div class="offcanvas-body">
     <div class="navbar-nav">
      <router-link id="menu" to="/" class="nav-item nav-link active" >Home <span class="sr-only"></span></router-link>
      <router-link id="menu" to="/about" class="nav-item nav-link" > About </router-link>
      <router-link id="menu" to="/timeline" class="nav-item nav-link" > Timeline </router-link>
      <router-link id="menu" to="/projects" class="nav-item nav-link" > Projects </router-link>
      <router-link id="menu" to="/testimonials" class="nav-item nav-link" > Testimonials </router-link>
      <router-link  id="menu" to="/contact" class="nav-item nav-link" > Contact </router-link>
    </div>
  </div>
</div>
</template>

<script>
export default {
    name: 'Navbar'
}

</script>
<style scoped>
.offcanvas-end {
    width: 200px;
    height: fit-content;
}

.navbar-toggler-icon{

    width: 2em;
    height: 2em;

}

button{
  margin: 30px
  




}
#nav {
  
  background-color: white;
  position: fixed;
  padding-top: 0;
  padding-bottom: 0;
  width: 100%;
  z-index: 1;
  
}
.navbar-nav{
  padding-right:1100px ;
   padding-top: 0;
  padding-bottom: 0;
  
}

#nav a {
  font-weight: normal;
  color: #2c3e50;

  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}

#nav a.router-link-exact-active {
 
 
  color: rgb(2, 26, 136);
}
#menu{
  font-size: 1.5em;
  

}
.off-canvas{
    z-index:998939428247892389299999;
}
.offie{display: none}
@media only screen and (max-width: 700px){
    /* --------------------------------------------HOME-PAGE-------------------------------- */ 

.offie{
  display: initial;
  position: fixed;
  top: 0;
  right: 0;

}
}



@media only screen and (max-width: 480px){
    /* --------------------------------------------HOME-PAGE-------------------------------- */ 

.offie{
  display: initial;
  position: fixed;
  top: 0;
  right: 0;

}
}

@media only screen and (max-width: 1203px){
    /* --------------------------------------------HOME-PAGE-------------------------------- */ 

.offie{
  display: initial;
  position: fixed;
  top: 0;
  right: 0;

}
}

</style>