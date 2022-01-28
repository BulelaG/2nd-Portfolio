<template>
  <div class="projects">
   <Navbar />
   <!-- Portfolio section -->

     <section id="portfolio-page" style=" padding-right: 90px; padding-left: 90px;">
      <h1 class=" text-center" style="padding-top: 2px; padding-bottom: 20px; border-bottom:solid 2px; font-family: sans-serif -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; "  id= purple-myname >My Projects</h1>
     <div id="portfolio-row" style="padding-top: 110px;"  class="row row-cols-1 row-cols-md-3 g-4">
      <div class="col col-md-12 col-md-4 col-lg-4">
        <div class="card h-100">
          <img style="height:70%; width :60%; display: flex; justify-content: center;"  id="portfolio-image" src="../assets/NeededFiles/mock-portfolio.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Mock Portfolio</h5>
            <p class="card-text">First ever portfolio created with Html and Css </p>
          </div>
          <div class="card-footer">
            <button type="button" class="btn btn-muted btn-lg px-4 gap-3">
              <a style="color: rgb(76, 86, 88);" href=" https://github.com/BulelaG" target="_blank"><i  class="bi bi-github" style="font-size: 2em;padding-bottom: 400px;"></i></a>
             </button>
            <small class="text-muted">Last updated 3 weeks ago</small>
          </div>
        </div>
      </div>
      <div class="col col-md-12 col-md-4 col-lg-4">
        <div class="card h-100"> 
          <img style="height:70%; width :60%"  id="portfolio-image" src="../assets/NeededFiles/carousel.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Carousels Practice</h5>
            <p class="card-text">This is a task where we practised carousels and modals.</p>
          </div>
          <div class="card-footer"><button type="button" class="btn btn-muted btn-lg px-4 gap-3">
            <a style="color: rgb(76, 86, 88);" href="https://github.com/BulelaG/carousels" target="_blank"><i  class="bi bi-github" style="font-size: 2em;padding-bottom: 400px;"></i></a>
           </button>
            <small class="text-muted">Last updated a week ago</small>
          </div>
        </div>
      </div>
      <div class="col col-md-12 col-md-4 col-lg-4">
        <div class="card h-100">
          <img style="height:70%; width :60%" id="portfolio-image" src="../assets/NeededFiles/Calculator.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title ">Calculator</h5>
            <p class="card-text"> This is I am currently working on.</p>
          </div>
          <div class="card-footer">
            <button type="button" class="btn btn-muted btn-lg px-4 gap-3">
              <a style="color: rgb(76, 86, 88);" href=" https://github.com/BulelaG" target="_blank"><i  class="bi bi-github" style="font-size: 2em;padding-bottom: 400px;"></i></a>
             </button>
            <small class="text-muted">Last updated a week ago</small>
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
    name: 'Projects',
    components: {Navbar,Footer}
  }

</script>