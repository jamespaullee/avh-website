<template>
  <nav class="z-50 pt-3 drop-shadow-md">
    <TheHeader />
  </nav>
  <div class="z-10">
    <router-view />
  </div>
</template>

<script setup>
import TheHeader from "@/components/TheHeader.vue";
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
} */

nav {
  /* padding: 30px; */
  margin-bottom: 4px;
  margin-top: 4px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #3049a4;
  font-weight: 600;
}
</style>
