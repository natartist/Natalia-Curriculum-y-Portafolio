<template>
<div>
  <Navbar/>
  <!-- <Footer/> -->
  <router-view/>
  </div>


</template>

<style>

</style>

<script>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";

export default {
  components: {
    Navbar,
    Footer

  }
}
</script>
