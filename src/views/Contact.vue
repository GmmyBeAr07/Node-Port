<template>
    <Navbar/>
    <Kontact/>
</template>

<script>

import Navbar from '../components/Navbar.vue'
import Kontact from '../components/Kontact.vue'

export default {
  name: 'Home',
  components: { Navbar, Kontact
  },
};
</script>
