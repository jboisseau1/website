<template>
<vs-row vs-w="12">
  <vs-col vs-lg="2">
    <div>
      <nav-bar></nav-bar>
    </div>
  </vs-col>



  <vs-col vs-lg="10">
    <Title></Title>

    <div class="row text-center">
      <div class="col-12">
        <h2>Projects</h2>
      </div>
    </div>
    <div class="card-deck text-center">
      <div class="card">
        <img class="card-img-top" src="./images/bombeo-new.jpg" alt="Card image cap">
        <div class="card-body">
          <h5 class="card-title">Bombeo</h5>
          <p class="card-text">Bombeo was a 24 hour project between 4 brilliant programmers. The Android app utilized bluetooth to create an 'off-the-grid' form of communication between multiple users. </p>
        </div>
      </div>
      <div class="card">
        <img class="card-img-top" src="./images/sm.jpg" alt="Card image cap">
        <div class="card-body">
          <h5 class="card-title">Smart Mirror</h5>
          <p class="card-text">Smart Mirror was a STEM Fair project inspired by DIY'ers on the internet as well as Google's aspirations to create a smart mirror. The product was designed to show the judges our vision of the Internet of Things.</p>
          <p class="card-text"></p>

        </div>
      </div>
    </div>
  </vs-col>

</vs-row>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Title from './components/Title.vue';
export default {
  name: 'app',
  components: {
    NavBar,
    Title
  }
};
</script>

<style>
</style>
