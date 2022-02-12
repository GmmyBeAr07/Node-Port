<template>
    <Navbar/>
    <LandingPage/>
</template>

<script>
import Navbar from '../components/Navbar.vue'
import LandingPage from '../components/LandingPage.vue'



export default {
  name: 'Home',
  components: { Navbar, LandingPage
  },
};
</script>
