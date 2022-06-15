<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Navbar from './components/Navbar.vue';
import PacificInfo from './components/PacificInfo.vue';
import Cards from './components/Cards.vue';
import Architecture from './components/Architecture.vue';
import Carousel from './components/Carousel.vue';
</script>

<template>
  <div class="container mx-auto w-11/12">
    <Navbar />
    <PacificInfo />
    <Cards />
    <Architecture />
    <Carousel />
  </div>
  
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
