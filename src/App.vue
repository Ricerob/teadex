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
    <div class="container-fluid" id="blurb-1">
      <div class="row p-3">
        <h1 class="title" style="font-size: 30px;">"Where there's tea, there's hope."</h1>
        <p class="text px-3" style="padding-top: -10px;"><i>Ralph Waldo Emerson</i></p>
        <p class="text px-3">Welcome to TeaDex, your premier spot for deciding on your next cup of happiness. TeaDex offers a few different services:</p>
      </div>
      <div class="container d-flex justify-content-around">
        <div class="row px-3">
          <div class="col border-box mx-3 text-center">
            <h2 class="title">Tea Database</h2>
            <p class="text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Mollitia cum nihil dolore. Esse eius similique exercitationem dolorum vitae dignissimos nobis, quaerat corporis laudantium neque non pariatur minima culpa in adipisci!</p>
          </div>
          <div class="col border-box mx-3 text-center">
            <h2 class="title">Quiz</h2>
            <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi eum possimus at iure quasi quos delectus unde, amet sed ratione modi numquam, ad fuga neque in, atque porro corrupti enim!</p>
          </div>
      </div>
    </div>
    </div>
    <div class="container-fluid mt-3" style="background-color: #DDBEA9;">
      <div class="row justify-content-center">
        <div class="col text-center pt-1 pb-3">
          <h3 class="title">Indecisive? No worries.</h3>
          <p class="text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Officia excepturi repellat aut distinctio tenetur fugiat consequatur magni quos omnis illum, doloribus, quidem nihil officiis quam, cupiditate necessitatibus ab error. Amet.</p>
          <a href="#" class="btn" id="quiz-btn">Take me there!</a>
        </div>
      </div>
    </div>
    <BottomNav />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import BottomNav from './components/BottomNav.vue'

export default {
  name: 'App',
  components: {
    Navbar, BottomNav
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
#quiz-btn {
  background-color: #A5A58D;
  border: 2px solid #6B705C;
}
.title {
  font-family: 'PT Sans', sans-serif;
}
.text {
  font-family: 'PT Serif', serif;
}
.border-box {
  border: 2px solid #6B705C;
  border-radius: 25px;
}
</style>