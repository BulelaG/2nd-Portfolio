<template>
  <div class="home">
    <Navbar />
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <LandingPage msg="Welcome to my page.js App"/>
  
  </div>


  
</template>

<script>
// @ is an alias to /src
import LandingPage from '@/components/LandingPage.vue';
import Navbar from '@/components/navbar.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'Home',
  components: {
    LandingPage,
    Navbar,
    Footer
  }
}
</script>
<style scoped>

template {

overflow-x: hidden;


}
</style>
