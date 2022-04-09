<template>
  <div class="links">
    <h1>{{ head }}</h1>
    <br />
    <br />
  </div>
</template>

<script setup lang="ts">
defineProps({
  head: String
})
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
