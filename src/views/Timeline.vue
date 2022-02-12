<template>
    <Navbar/>
    <TimeLine/>

</template>

<script>

import Navbar from '../components/Navbar.vue'
import TimeLine from '../components/TimeLine.vue'


export default {
  name: 'Home',
  components: { Navbar, TimeLine,
  },
};
</script>
