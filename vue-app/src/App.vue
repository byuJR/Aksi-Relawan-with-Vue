<script setup>
import NavBar from './components/NavBar.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <div>
    <NavBar />
    <div class="container mx-auto">
      <router-view />
    </div>
    <Footer />
  </div>
</template>

<style>
/* Global styles can go here */
body {
  font-family: 'Inter', sans-serif;
  color: #333;
  line-height: 1.5;
}

.container {
  width: 100%;
  max-width: 1280px;
  margin: 0 auto;
}
</style>
