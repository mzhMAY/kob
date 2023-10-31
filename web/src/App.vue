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
    // $.ajax({
    //   url: "http://127.0.0.1:3000/user/account/register/",
    //   type: "post",
    //   data: {
    //     username: "mzh2",
    //     password: "pmzh",
    //     confirmedPassword: "pmzh",
    //   },
    //   success(resp) {
    //     console.log(resp);
    //   },
    //   error(resp) {
    //     console.log(resp);
    //   }
    // });
  }
}
</script>

<style>
body{
  background-image: url("@/assets/images/background.png");
  background-size: cover;
}
</style>
