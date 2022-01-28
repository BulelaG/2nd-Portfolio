<template>
  <div class="contact">
   <Navbar />
<br>
<!-- Section: Contact v.1 -->
<section class="my-5">

  <!-- Section heading -->
  <h1 class="h1-responsive font-weight-bold text-center my-5">Contact us</h1>
  <!-- Section description -->
  <p class="text-center w-responsive mx-auto pb-5">Do you have any questions? Please do not hesitate to contact me directly. I will come back to you within a matter of hours to help you.

</p>

  <!-- Grid row -->
  <div class="row">

    <!-- Grid column -->
    <div class="col-lg-5 mb-lg-0 mb-4">

      <!-- Form with header -->
      <div class="card">
        <div class="card-body">
          <!-- Header -->
          <div class="form-header blue accent-1">
            <h3 class="mt-2"><i class="fas fa-envelope"></i> Write to us:</h3>
          </div>
          <p class="dark-grey-text">We'll write rarely, but only the best content.</p>
          <!-- Body -->
          <div class="md-form">
            <i class="fas fa-user prefix grey-text"></i>
            <input type="text" id="form-name" class="form-control">
            <label for="form-name">Your name</label>
          </div>
          <div class="md-form">
            <i class="fas fa-envelope prefix grey-text"></i>
            <input type="text" id="form-email" class="form-control">
            <label for="form-email">Your email</label>
          </div>
          <div class="md-form">
            <i class="fas fa-tag prefix grey-text"></i>
            <input type="text" id="form-Subject" class="form-control">
            <label for="form-Subject">Subject</label>
          </div>
          <div class="md-form">
            <i class="fas fa-pencil-alt prefix grey-text"></i>
            <textarea id="form-text" class="form-control md-textarea" rows="3"></textarea>
            <label for="form-text">Send message</label>
          </div>
          <div class="text-center">
            <button class="btn btn-light-blue">Submit</button>
          </div>
        </div>
      </div>
      <!-- Form with header -->

    </div>
    <!-- Grid column -->

    <!-- Grid column -->
    <div class="col-lg-7">

      <!--Google map-->
      <div id="map">
      <div id="map-container-section" class="z-depth-1-half map-container-section mb-4" style= "height: 300px; border:1px border-radius: 89px; ">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3308.2934215261566!2d18.490473614807716!3d-33.9849962806242!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1dcc433bfcf832a1%3A0x3b4439b8cc517802!2s314%20Imam%20Haron%20Rd%2C%20Lansdowne%2C%20Cape%20Town%2C%207780!5e0!3m2!1sen!2sza!4v1633096149800!5m2!1sen!2sza" frameborder="0"
          style=" ; width:600px; height: 457px" allowfullscreen></iframe>
      </div>
      </div>

      <br>
      <br>
      <!-- Buttons-->
      <div class="row text-center">
        <div class="col-md-4">
          <a class="btn-floating blue accent-1">
            <i class="fas fa-map-marker-alt"></i>
          </a>
          <p> 314 Imam Haron Rd, Lansdowne, Cape Town, 7780</p>
          <p class="mb-md-0">South Africa</p>
        </div>
        <div class="col-md-4">
          <a class="btn-floating blue accent-1">
            <i class="fas fa-phone"></i>
          </a>
          <p>+27 67 216 9078</p>
          <p class="mb-md-0">Mon - Fri, 8:00-17:00</p>
        </div>
        <div class="col-md-4">
          <a class="btn-floating blue accent-1">
            <i class="fas fa-envelope"></i>
          </a>
          <p>info@gmail.com</p>
          <p class="mb-0">bulelagomoshe1@gmail.com</p>
        </div>
      </div>

    </div>
    <!-- Grid column -->

  </div>
  <!-- Grid row -->

</section>
<!-- Section: Contact v.1 -->
  </div>
  
</template>

<script>
import Navbar from '@/components/navbar.vue'
import Footer from '@/components/Footer.vue'

export default {
    name: 'Contact',
    components: {Navbar,Footer}
  }

</script>
<style scoped>
.map-container-section {
  overflow:hidden;
  padding-bottom:56.25%;
  position:relative;
  height:0;
}
.map-container-section iframe {
  left:0;
  top:0;
  height:100%;
  width:100%;
  position:absolute;
  
  }

/* .contact {background-color:#ebebeb;} */

.card{

  border:1px solid;
  border-radius: 45px;

}

iframe {

  border:1px solid;
  border-radius: 45px;
}

.z-depth-1-half{


}

#map{
 
 padding-left: 350px;

}

.card{
  width:1000px;
}
template {
  overflow-x: 0;
}

</style>