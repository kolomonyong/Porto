<template>
  <div class="bg-gray-50 text-gray-800 font-sans">
    <Navbar />
    <main class="max-w-5xl mx-auto px-6">
      <Hero />
      <About />
      <Experience />
      <Projects />
      <Skills />
    </main>
    <Footer />
  </div>
</template>

<script setup>
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";
import About from "./components/About.vue";
import Experience from "./components/Experience.vue";
import Projects from "./components/Projects.vue";
import Skills from "./components/Skills.vue";
import Footer from "./components/Footer.vue";
</script>

<style>
/* Global style for smooth scrolling */
html {
  scroll-behavior: smooth;
}
</style>
