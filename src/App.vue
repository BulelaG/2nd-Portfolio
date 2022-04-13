<template>
 
<Navbar/>
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
#purple-myname{
  color: rgb(2, 26, 136);
}

.offie{
  display: none;
  float: right;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
   overflow-x: hidden;
   
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
    height: 400px;
    object-fit: cover;
    border-style: solid;
    border: 8px;
    border-color: #e4d7d7;
}
@media only screen and (max-width: 700px){
    /* --------------------------------------------HOME-PAGE-------------------------------- */ 

.offie{
  display: initial;
  position: fixed;
  top: 0;
  right: 0;

}template{

width: 100%;
display:initial;

}

}

@media only screen and (max-width: 780px){

    template{

width: 100%;
display:initial;

}
}

@media only screen and (max-width: 480px){
#landing-image{
 
    padding: 0px;
    padding-left: 0px !important;

}
    template{

width: 100%;
display:initial;

}
}
@media only screen and (max-width: 380px){

#landing-photo{
    object-fit: cover;
    padding: 0px;
    padding-left: 0px !important;

}
    template{

width: 100%;
display:initial;

}


}

@media only screen and (max-width: 320px){

#landing-photo{
 width: 70%;
 height: 30%;
    padding: 0px;
    padding-left: 0px !important;

}
    template{

width: 100%;
display:initial;

}


}
</style>
