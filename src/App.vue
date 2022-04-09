<template>
  <img alt="Vue logo" src="./assets/pusheen_1.gif" />
  <Links head="icyfry.io" />
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import Links from "./components/Links.vue";

@Options({
  components: {
    Links,
  },
})
export default class App extends Vue {}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background-color: #fcf0e4;
}
</style>
