<template>
  <div class="projects">
    <Navbar />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />

    <!-- new projects code-->
    <h1
      class="text-center"
      style="
        padding-top: 2px;
        padding-bottom: px;
        border-bottom: solid 2px;
        font-family: sans-serif -apple-system, BlinkMacSystemFont, 'Segoe UI',
          Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue',
          sans-serif;
      "
      id="purple-myname"
    >
      My Projects
    </h1>
    <br /><br />
    <br /><br />

    <section id="gallery" style="padding-bottom: 16px">
      <div class="container">
        <div class="row" v-if="projects">
          <div
            v-for="(project, index) of projects"
            :key="index"
            class="col-lg-4 mb-4"
          >
            <div class="card">
              <img :src="project.image" alt="" class="card-img-top" />
              <div class="card-body">
                <br />
                <h5 class="card-title">{{ project.title }}</h5>
                <p class="card-text">{{ project.description }}</p>
              </div>
              <div class="card-footer">
               <!-- github link ----------------------------------------->
                <button
                  type="button"
                  class="btn btn-muted btn-lg px-4 gap-3"
                  target="_blank"
                >
                  <a style="color: rgb(76, 86, 88)" :href="project.link"
                    ><i
                      class="bi bi-github"
                      style="font-size: 1em; padding-bottom: 400px"
                      >Github link</i
                    ></a
                  >
                </button>

             <!--netlify link ---------------------------------------- -->
                 <button
                  type="button"
                  class="btn btn-muted btn-lg px-4 gap-3"
                  target="_blank"
                >
                  <a style="color: rgb(76, 86, 88)" target="_blank" :href="project.site"
                    ><i
                      class="bi bi-github"
                      style="font-size: 1em; padding-bottom: 400px"
                      >Netlify link</i
                    ></a
                  >
                </button>
                <br>

                <small class="text-muted">{{ project.progress }}</small>
              </div>
              
              <br>
              <br>
              <!-- <div class="card-body">
        <h5 class="card-title">Sunset</h5>
        <p class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ut eum similique repellat a laborum, rerum voluptates ipsam eos quo tempore iusto dolore modi dolorum in pariatur. Incidunt repellendus praesentium quae!</p>
       <a href="" class="btn btn-outline-success btn-sm">Read More</a>
        <a href="" class="btn btn-outline-danger btn-sm"><i class="far fa-heart"></i></a>
      </div> -->
            </div>
          </div>
          <!-- <div class="col-lg-4 mb-4">
  <div class="card">
      <img src="../assets/NeededFiles/BMI.png" alt="" class="card-img-top">
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
    <div class="col-lg-4 mb-4">
    <div class="card">
      <img src="../assets/NeededFiles/carousel.png" alt="" class="card-img-top">
      <div class="card-body">
            <h5 class="card-title">Mock Portfolio</h5>
            <br>
            <p class="card-text">First ever portfolio created with Html and Css </p>
            
          </div>
          <div class="card-footer">
            <button type="button" class="btn btn-muted btn-lg px-4 gap-3">
              <a style="color: rgb(76, 86, 88);" href=" https://github.com/BulelaG" target="_blank"><i  class="bi bi-github" style="font-size: 2em;padding-bottom: 400px;"></i></a>
             </button>
            <small class="text-muted">Last updated 3 weeks ago</small>
          </div>

    
     </div>
    </div> -->
        </div>
      </div>
    </section>

    <!-- calling array -->

    <!-- calling an array -->

    <br /><br />
    <br /><br />
    <br /><br />
    <br />

    <!-- new projects code -->
  </div>
</template>

<script>
import Navbar from "@/components/navbar.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Projects",
  components: { Navbar, Footer },

  data() {
    return {
      projects: null,
    };
  },
  mounted() {
    fetch("http://localhost:5500")
      .then((response) => {
        return response.json();
      })
      .then((data) => {
        console.log(data);
        this.projects = data;
      });
  },
};
</script>

<style scoped>
.card-img-top {
  height: 300px;
}

.projects {
  background: #e8cbc0;
  background: -webkit-linear-gradient(to right, #e8cbc0, #636fa4);
  background: linear-gradient(to right, #e8cbc0, #636fa4);
  min-height: 100vh;
  padding-left: 200px;
  padding-right: 200px;
}

.social-link {
  width: 30px;
  height: 30px;
  border: 1px solid #ddd;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #666;
  border-radius: 50%;
  transition: all 0.3s;
  font-size: 0.9rem;
}

.social-link:hover,
.social-link:focus {
  background: #ddd;
  text-decoration: none;
  color: #555;
}
</style>
