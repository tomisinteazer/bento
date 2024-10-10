<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import Projects from '@/components/Projects.vue';
import Testimonial from '@/components/Testimonial.vue';
</script>

<template>
  <main>
    <TheWelcome />
    <Projects />
    <Testimonial />


  </main>



</template>
<style>
img {
  opacity: 20%;
}

img:hover {
  opacity: 100%;
}
</style>