<template>
  <div class="landing">

    <!--HOME Landing Section  -->
    <section style="object-fit: cover;  padding-bottom: 50px;" id="landing-page">
      <div class="px-4 py-5 text-center">
        <br><br><br><br><br>
        <img
          id="landing-photo"
          class="d-block mx-auto mb-4 img-responsive"
          src="../assets/NeededFiles/Bulela.jpeg"
          alt=""
          style="border: 3px solid white;"
          width="372"
          height="357"
        />
       
          <h1  id= purple-myname class="display-5 fw-bold" style="font-family: sans-serif -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;" > <b> Bulela Gomoshe</b></h1> <br>
        
        <div class="col-lg-6 mx-auto">
          <h2 class=" text-dark text-size-10pxlead mb-4">
            I am an aspirant <b>Fullstack Developer</b>. 
            <p>I offer <b>Web Development</b> services.</p> 
            <p> Lets connect!</p>
          </h2>
          </div>
          <div class="d-grid gap-2 d-flex justify-content-center">
            <button type="button" style="color: rgb(106, 85, 117);" class="btn btn-muted btn-lg px-4 gap-3">
             <a style="color: rgb(76, 86, 88); padding-left:;" href=" https://github.com/BulelaG" target="_blank"><i  class="bi bi-github" style="font-size: 2em;padding-bottom: 0px;"></i></a>
            </button>
         
            <br><br><br>
          </div>      
        </div>
      
    </section>
  

     
     <!--Landing page end -->
 
    </div>
    
  
</template>

<script>
export default {
  name: 'Landing-page',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

