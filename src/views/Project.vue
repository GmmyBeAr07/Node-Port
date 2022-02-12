<template>
    <Navbar/>
    <Projekt/>

</template>

<script>

import Navbar from '../components/Navbar.vue'
import Projekt from '../components/Projekt.vue'


export default {
  name: 'Project',
  components: { Navbar, Projekt,
  },
};
</script>
