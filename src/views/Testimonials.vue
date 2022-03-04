<template>
  <div class="testimonials">

  <!-- Testimonials Section -->
    <section style="padding-top: 120px;  padding-bottom: 120px; padding-right: 90px; padding-left: 90px;" id="testimonials-page">
      <br>
      <h1 id= "purple-myname" style="padding-top: 20px; padding-bottom: 20px; border-bottom:solid 2px; font-family: sans-serif -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;" class="text-center">Testimonials</h1>
      <br>
      <br>

      

      <div class="row" style="">
        <div class="col-lg-4">
          <img class="rounded-circle" src="../assets/NeededFiles/Godwin.jpeg" alt="Generic placeholder image" width="160" height="160">
          <h5  id="purple-myname" >Godwin Dzvapatsva <a style="color:rgb(0, 0, 184)" href="https://www.linkedin.com/in/gpdzvapatsva/" target="_blank" > <img style="color:rgb(0, 0, 184)" src="https://img.icons8.com/ios-glyphs/30/000000/linkedin.png"/></a>
</h5>            

          <h6 id= "purple-myname">Head of Curriculum and Learning </h6>

          <p>.<em>
            I have no hesitancy in writing a letter of recommendation for Bulela. </em></p><br>

        </div>
        <!-- /.col-lg-4 -->

        <div class="col-lg-4">
          <img class="rounded-circle" src="../assets/NeededFiles/SEKO.jpeg" alt="Generic placeholder image" width="160" height="160">
          <h5  id= purple-myname >Nomvuyiseko Mpofu<a style="color:rgb(0, 0, 184)" href="https://www.linkedin.com/in/nomvuyiseko-mpofu-0a782b117/" target="_blank" > <img style="color:rgb(0, 0, 184)" src="https://img.icons8.com/ios-glyphs/30/000000/linkedin.png"/></a>
</h5>            
          <h6 id= purple-myname>Computer Programming Student </h6>
          <p> <em>"Bulela is quite an intereresting person, he works well with people and he is one dedicated student." </em> </p><br>
          <div>
          </div>
        </div>
        
      
        <!-- /.col-lg-4 -->

        <div class="col-lg-4">
          <img class="rounded-circle" src="../assets/NeededFiles/Akha2.jpg" alt="Generic placeholder image" width="160" height="160">
          <h5 id= purple-myname> Akha Kambora <a style="color:rgb(0, 0, 184)" href="https://www.linkedin.com/in/akha-kombora-965959226/" target="_blank" > <img style="color:rgb(0, 0, 184)" src="https://img.icons8.com/ios-glyphs/30/000000/linkedin.png"/></a>
</h5>             

          <h6 id= purple-myname>Coding Student </h6>

          <p> <em>"Bulela is a smart student with a bright future.
              He always has a smile on his face and is a pleasure to work with.
              I look forward to seeing what he will achieve in the future and highly reccomend him
            ."</em></p><br>
            <div>
            </div>
        </div>
        <!-- /.col-lg-4 -->
      </div>
      <div class="row" style=";">
        <div class="col-lg-4">
          <img class="rounded-circle" src="../assets/NeededFiles/Xola1.jpg" alt="Generic placeholder image" width="160" height="160">
          <h5 id= purple-myname> Xola Magatya <a style="color:rgb(0, 0, 184)" href="https://www.linkedin.com/in/xola-magatya-644242216/" target="_blank" > <img style="color:rgb(0, 0, 184)" src="https://img.icons8.com/ios-glyphs/30/000000/linkedin.png"/></a>
</h5>            

          <h6 id= purple-myname>Coding Student</h6>

          <p><em>"Bulela is a hard working with peserverance, always eager to learn or work and he is quite friendly." </em> </p><br>
           <div>
           </div>
        </div>
        <!-- /.col-lg-4 -->

        <div class="col-lg-4">
          <img class="rounded-circle" src="../assets/NeededFiles/Seth4.jpg" alt="Generic placeholder image" width="160" height="160">
          <h5 id= purple-myname>Seth Kleynhans<a style="color:rgb(0, 0, 184)" href="https://www.linkedin.com/in/webdevseth/" target="_blank" > <img style="color:rgb(0, 0, 184)" src="https://img.icons8.com/ios-glyphs/30/000000/linkedin.png"/></a>
</h5>  

        
          <h6 id= purple-myname>Computer Programming Student </h6>

          <p> <em> "As a fellow student, I think Bulela has a friendly and caring personality. He loves participating when he knows the answer. He is a hard working individual who always shows determination to learn and to help others."</em></p><br>
          <div>
          
          </div>
        </div>
        
      
        <!-- /.col-lg-4 -->

        <div class="col-lg-4">
          <img class="rounded-circle" src="../assets/NeededFiles/Ashley.jpeg" alt="Generic placeholder image" width="160" height="160">
          <h5 id= purple-myname> Ashley Kannemyer<a style="color:rgb(0, 0, 184)" href="https://www.linkedin.com/in/ashley-kannemeyer-01b37121b/" target="_blank" > <img style="color:rgb(0, 0, 184)" src="https://img.icons8.com/ios-glyphs/30/000000/linkedin.png"/></a>
</h5>          

          <h6 id= purple-myname>Coding Student </h6>
          <p> <em>"Bulela is a hard worker and a determined person in general. Additionally, he is a person who loves a challenge."</em></p><br>
          <div>
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
    name: 'Testimonials',
    components: {Navbar,Footer}
  
  }

</script>
<style scoped>
.testimonials{

 padding-left: 150px;
    padding-right: 150px; 

}
/* -------------------------------------------Portfolio CSS ----------------------------------------------------------------
#portfolio-page{
    
    padding-top: 150px;
    padding-bottom: 10px;
    padding-left: 150px;
    padding-right: 150px;
   


} */
#portfolio-row{
    padding-top: 19px;
    padding-bottom: 19px;


}
#portfolio-image{
    height: 300px;
    width: 100%;
    object-fit: cover;
    

}
/* ---------------------- */
@media only screen and (max-width: 1080px){


.timeline{

 padding-left: 0px;
    padding-right: 0px; 

}

}

@media only screen and (max-width: 780px){


.timeline{

 padding-left: 0px;
    padding-right: 0px; 

}

}


@media only screen and (max-width: 480px){

  .timeline{

 padding-left: 0px;
    padding-right: 0px; 

}
}





</style>
  
