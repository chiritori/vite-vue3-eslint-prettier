<script setup>
import HelloWorld from './components/HelloWorld.vue';
</script>

<template>
  <img alt="Vue logo" src="./assets/vue.svg" class="logo vue" />
  <HelloWorld msg="Hello Vue 3 + Vite" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
