<template>
  <img class="animated-gif" alt="pusheen" src="./assets/pusheen_2.gif" />
  <ReferralsLinks head="" />
  <Footer />
</template>

<script setup lang="ts">
// import AppFooter from './components/AppFooter.vue'
import ReferralsLinks from './components/ReferralsLinks.vue'
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  padding-top: 60px;
  background-color: #fcf0e4;
}
img.animated-gif {
  width: 220px;
  height: auto;
}
</style>
