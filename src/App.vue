<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue'
import Footer from './components/Footer.vue'

</script>

<template>

<NavBar />
  
  <div class="container">
  <RouterView />
  </div>

<Footer />
</template>

<style scoped>

.container{
background-color: #eeeeee;
}


</style>
