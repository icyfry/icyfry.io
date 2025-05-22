<template>
  <AppHeader />
    <!--
    <div id="nav">
      <router-link to="/">Home</router-link>
    </div>
    -->
    <router-view />
  <AppFooter />
</template>

<script setup lang="ts">
import AppHeader from './components/AppHeader.vue'
import AppFooter from './components/AppFooter.vue'
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  padding-top: 10px;
  background-color: #fcf0e4;
}
img.animated-gif {
  width: 220px;
  height: auto;
  margin: 15px;
}
</style>
