<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <NavBar />
    <router-view />
    <Footer />
  </div>
</template>

<script>
import NavBar from '@/components/navs/NavBar.vue'
import Footer from '@/components/navs/Footer.vue'
export default {
  components: {
    NavBar,
    Footer
  }
}
</script>
