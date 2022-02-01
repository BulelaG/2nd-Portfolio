<template>
  <div class="contact">
   <Navbar />
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<section class="mb-4">

<!--Section: Contact v.2-->
<section class="mb-4">

  <div > <h1 class="text-center"  id= purple-myname style="padding-top: 20px; padding-bottom: 20px; padding-right: 20px; font-family: sans-serif -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; border-bottom:solid 2px;"   >Contact me</h1></div>


  <!--Section heading-->
  <h2 class="h1-responsive font-weight-bold text-center my-4"></h2>
  <!--Section description-->
  <p  id= purple-myname class="text-center w-responsive  mx-auto mb-5">Do you have any questions? Please do not hesitate to contact me directly. I will come back to you within
      a matter of hours to help you.</p>

  <div class="row " style="border:solid  1px; padding-top:10px ;  padding-bottom:10px; border-radius: 20px;">

      <!--Grid column-->
      <div class="col-md-9 mb-md-0 mb-5">
          <form id="contact-form" name="contact-form" action="https://formspree.io/f/mlezrjaw" method="POST">

              <!--Grid row-->
              <div style=" " class="row">

                  <!--Grid column-->
                  <div class="col-md-6">
                      <div class="md-form mb-0">
                          <input type="text" id="name" name="name" class="form-control" required>
                          <label for="name" class="">Your name</label>
                      </div>
                  </div>
                  <!--Grid column-->

                  <!--Grid column-->
                  <div class="col-md-6">
                      <div class="md-form mb-0">
                          <input type="email" id="email" name="email" class="form-control" required>
                          <label for="email" class="">Your email</label>
                      </div>
                  </div>
                  <!--Grid column-->

              </div>
              <!--Grid row-->

              <!--Grid row-->
              <div style=" height:110px;" class="row">
                  <div class="col-md-12">
                      <div class="md-form mb-0">
                          <input type="text" id="subject" name="subject" class="form-control" required>
                          <label for="subject" class="">Subject</label>
                      </div>
                  </div>
              </div>
              <!--Grid row-->

              <!--Grid row-->
              <div style=" height:110px;" class="row">

                  <!--Grid column-->
                  <div class="col-md-12">

                      <div class="md-form">
                          <textarea type="text" id="message" name="message" rows="2" class="form-control md-textarea" required></textarea>
                          <label for="message">Your message</label>
                      </div>

                  </div>
              </div>
              <!--Grid row-->

          </form>

          <div class="text-center text-md-left">
              <a class="btn btn-primary" onclick="document.getElementById('contact-form').submit();">Send</a>
          </div>
          <div class="status"></div>
      </div>
      <!--Grid column-->

      <!--Grid column-->
      <div style="border:solid  1px; padding-top:10px ;;  border-radius: 20px;" class="col-md-3 text-center">
          <ul class="list-unstyled mb-0">
              <li>  <div>
                <p> CAMPUS ADDRESS </p>
                  </div>
                <div>
            <iframe style="float: bottom; border-radius: 15%; border:0;" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3308.2934215261566!2d18.490473614807716!3d-33.9849962806242!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1dcc433bfcf832a1%3A0x3b4439b8cc517802!2s314%20Imam%20Haron%20Rd%2C%20Lansdowne%2C%20Cape%20Town%2C%207780!5e0!3m2!1sen!2sza!4v1633096149800!5m2!1sen!2sza" width="200" height="120"  allowfullscreen="" loading="lazy"></iframe>
            </div>
                  <p>
                    
                    
                    314 Imam Haron Road, Cape Town,
                    South Africa,
                    7780
                    SA</p>
                    
              </li>

              <li>
                  <p>+ 27 672 169 078</p>
              </li>

              <li><i class="fas fa-envelope mt-4 fa-2x"></i>
                  <p>bulelagomoshe1@gmai.com</p>
                    <a style="color: rgb(196, 19, 101);" href=" https://github.com/BulelaG" target="_blank"><i  class="bi bi-instagram" style="font-size: 3em;padding-bottom: 400px;"></i></a>
                    <a style="color: rgb(59, 61, 179);" href="https://www.linkedin.com/in/bulelag/" target="_blank"><i class="bi bi-linkedin" style="font-size: 3em;padding-bottom: 400px;"></i></a>
                      
              </li>
          </ul>
      </div>
      <!--Grid column-->

  </div>

</section>
<!--Section: Contact v.2-->

</section>
  </div>
  <br>
    <br>
      <br>
        <br>
          <br>
            <br>
              <br>
                
                    
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

.contact{

padding-left: 200px;
padding-right: 200px;
}


</style>