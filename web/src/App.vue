<template>
  <Navbar />
  <router-view/>
</template>

<script>
import Navbar from './components/NavBar.vue'
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap/dist/js/bootstrap" 
// import $ from 'jquery'

export default{
  components: {
    Navbar,
  },
  setup() {
    
  }
}
</script>

<style>
body{
  background-image: url("@/assets/images/background.png");
  background-size: cover;
}
</style>
