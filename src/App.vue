<template>
  <div id="app">
    <Navbar />
    <Hero />
    <Projects />
    <Contact />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';
import Projects from './components/Projects.vue';
import Contact from './components/Contact.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Hero,
    Projects,
    Contact
  }
};
</script>

<style>
/* Add your styles here */
</style>