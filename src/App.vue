<template>
  <div class="container-fluid px-0" id="main">
    <Navbar />
    <div class="container-fluid" id="hero">
      <div class="row">
        <div class="col-md-4 ml-5">
          <h1 class="title pt-3" style="font-size: 64px; padding-left:30px;">TeaDex</h1>
          <h3 class="text pb-5" style="font-size: 18px; padding-left:40px;">Your first stop for all things tea.</h3>
          <div class="py-5"/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>

<style>
html {
   background-color: #FFE8D6; 
}
#hero {
  background-color: #A5A58D;
}
#main {
  background-color:#FFE8D6;
}
.title {
  font-family: 'PT Sans', sans-serif;
}
.text {
  font-family: 'PT Serif', serif;
}
</style>