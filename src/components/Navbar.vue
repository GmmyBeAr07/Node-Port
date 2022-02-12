<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="/"><img src="../assets/images/logo/Logo.png" style="height: 70px; width: 100px"></a>
    
    <button
      class="navbar-toggler"
      type="button"
      data-mdb-toggle="collapse"
      data-mdb-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation">
      <i class="fas fa-bars">
      </i>
      </button>

    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
       <router-link to="/">Home</router-link>

       <router-link to="/about">About</router-link>

       <router-link to="/WaE">Work & Education</router-link>

       <router-link to="/project">Project</router-link>

       <router-link to="/timeline">Timeline</router-link>

       <router-link to="/testimonial">Testimonial</router-link>
       
       <router-link to="/contact">Contact</router-link>        
      </ul>
    </div>
  </div>
</nav>
</template>

<script>

</script>

<style scoped>
.container-fluid {
  background: rgb(90, 85, 85);
}



</style>