<template>
  <div class="about">
   <Navbar />

    <!-- About Section -->
 <section style="padding-top: 100px;padding-bottom: 130px;" id="about-page">

  
  <h1 class="text-center" style="padding-top: 20px; padding-bottom: 20px; border-bottom:solid 2px; font-family: sans-serif -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;" id= purple-myname >About Me</h1>
  <div style="padding-top: 60px;">    </div>
    <div  class="card-group"    >
      <div class="card border-radius-10px">
        <img id=about-image class="card-img-top" style="width: 400px;height: 500px;" src="../assets/NeededFiles/B-MOVING.jpg" alt="Card image cap">
        <div class="card-body">
       
        </div>
      </div>
      <div class="card">
        <div class="card-body">
       
           <h4 id="purple-myname" class="card-title"><strong> Personal Details </strong></h4>
          <!-- <p class="card-text">    -->
            
            <h5>Full name:</h5><p>Bulela Gomoshe</p>
            <h5> Date of birth:</h5> 26/02/2000
            <h5>  Location:</h5> Cape Town
            <h5> Cell Phone number:</h5> 0672169078
            <h5>Email Address:</h5> bulelagomoshe1@gmail.com <br>
            <!-- </p> -->
          <p class="card-text"><small id="purple-myname"> <button class="download" >Download CV <a  href="./Bulela G'sCURRICULUM VITAE .pdf" download="./Bulela G'sCURRICULUM VITAE .pdf"></a> </button></small></p>
        </div>
      </div>
      <div class="card">
       
        <div  class="card-body">
          <h5 class="card-title">
            <strong> <h4 id=purple-myname >Bio</h4> </strong></h5>
          <p class="card-text">
            I am an aspiring Full-Stack Developer. I am a dedicated, honest and
            optimistic young man residing in Cape Town. Not only that, but I am
            fluent in both English and isiXhosa. Furthermore, I am willing to
            learn in any environment, and I enjoy working with people. I am a
            person who believes in leading by example. I believe my web
            development skills will align with my future endeavours in the
            Entertainment Industry.
            

            </p>
             

           <strong> <h4 id=purple-myname >Where did my passion for coding start?</h4> </strong>
            <br />
            <p> Computer Science has always been an interest at the back of my mind.
            Generally I am a curious person, so I've always wondered how a
            computer works. In the past three years coding has been something
            I've been seeing on my screen, and so I realised it is a fundamental
            skill to learn in this day and age.</p>
          </div>
      </div>
    </div>
   
  </section>

      <!-- MY SKILLS SECTION -->

      <section style=" padding-right: 90px; padding-left: 90px;" >
      <div id="myskills-cards display-flex">


<h3 class="text-center" style="padding-top: 20px; padding-bottom: 20px; border-bottom:solid 2px font-family: sans-serif -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;;"  id= purple-myname >Technical Skills</h3>
<br><br>

  


  <!-- HTML card -->

<div class="card-group">
  <div class="card">  <h5 class="card-title text-muted text-center" >HTML </h5><br>     
    <img style="height: 280px;" src="https://img.icons8.com/color/2000/000000/html-5--v1.png"/>
    <div class="card-body">
     
        </div>
  </div>
  
  <!-- Bootstrap card -->


  <div class="card">
          <h5 class="card-title text-muted text-center" >Bootstrap</h5>

    <img style="height: 280px;" src="https://img.icons8.com/color/250/000000/bootstrap.png" class="card-img-top" alt="...">
    <div class="card-body">
        </div>
  </div>

<!-- CSS card -->


  <div class="card">      <h5 class="card-title text-muted text-center" >CSS</h5>

    <img style="height: 280px;" src="https://img.icons8.com/ios-filled/250/000000/css3.png" class="card-img-top" alt="...">
    <div class="card-body">
       </div>
  </div>
</div>


  <!-- SQL card -->

  <div class="card-group">
    <div class="card">  <h5 class="card-title text-muted text-center" >SQL </h5><br>     
      <img style="height: 280px;" src="../assets/NeededFiles/sql.png"/>
      <div class="card-body">
       
          </div>
    </div>
    
    <!-- Javascript card -->
  
  
    <div class="card">
            <h5 class="card-title text-muted text-center" >Javascript</h5><br>
  
      <img style="padding-left: 30px; " src="../assets/NeededFiles/JS.png" class="card-img-top" alt="...">
      <div class="card-body">
          </div>
    </div>
  
  <!-- Github card -->
  
  
    <div class="card">      <h5 class="card-title text-muted text-center" >Git</h5><br>
  
      <img src="../assets/NeededFiles/git-logo.png" class="card-img-top" alt="...">
      <div class="card-body">
         </div>
    </div>
  </div>

</div>
</section>

  </div>
  
</template>

<script>
import Navbar from '@/components/navbar.vue'
import Footer from '@/components/Footer.vue'


export default {
    name: 'About',
    components: {Navbar,Footer}
  
  }

</script>
<style scoped>

/* -------------------------------------------About page CSS--------------------------------------------------------------------- */
.download{

  width: 150px;

}


h1, #purple-myname{
padding-top: 20px;
}
#about-page{
padding-left: 150px;
padding-right: 150px;
}

/* -----------------------------------------About image----------------------------- */
#about-image{
    border-radius: 10%;
}
.card {
    border: none !important;
}
</style>