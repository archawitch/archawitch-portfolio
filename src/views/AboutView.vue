<script setup>
import { RouterLink } from 'vue-router'
import Contact from '../components/Contact.vue'
</script>

<template>
  <main id="about">
    <h1>I'm Archawit Changtor</h1>
    <p>
      Hi there! I'm a programmer living in Pathum Thani, Thailand. My interests lie in web
      development, mobile app development, and cyber security.
      <br />
      <br />
      I'm still thinking about what to do ᯓᯓ
      <br />
      <br />
      For more information about my personal projects, feel free to check those out at
      <router-link class="link" to="projects">Projects</router-link>.
    </p>
  </main>
  <Contact></Contact>
</template>

<style scoped>
#about {
  display: flex;
  align-items: center;
  flex-direction: column;
}

#about h1 {
  margin-bottom: 1.1rem;
  width: 100%;
}
</style>
