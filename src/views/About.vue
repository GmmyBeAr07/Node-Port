<template>
    <Navbar/>
    <AboutInfo/>
</template>

<script>

import Navbar from '../components/Navbar.vue'
import AboutInfo from '../components/AboutInfo.vue'


export default {
  name: 'Home',
  components: { Navbar, AboutInfo,
  },
};
</script>