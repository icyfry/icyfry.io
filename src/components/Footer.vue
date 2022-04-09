<template>
  <div class="footer">
    <a href="https://github.com/icyfry/icyfry.io">
      <img
        src="https://img.shields.io/badge/Github-icyfry.io-green?style=for-the-badge&logo=github"
      />
    </a>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {},
})
export default class Footer extends Vue {}
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
.footer {
  padding-top: 10px;
  padding-bottom: 7px;
  background-color: #d6d6d6;
}
</style>
