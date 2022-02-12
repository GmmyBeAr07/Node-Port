<template>
  <Navbar/>
  <Testies/>
</template>

<script>

import Navbar from '../components/Navbar.vue'
import Testies from '../components/Testies.vue'

export default {
 name: 'Home',
  components: { Navbar, Testies,
  },
};

</script>
