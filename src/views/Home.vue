<template>
  <div class="home">
    <Navbar />
    <Header />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import Header from '@/components/Header.vue'
export default {
  name: 'Home',
  components: {
    Navbar,
    Header

    
  }
}
</script>
