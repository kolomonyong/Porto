<template>
  <nav class="sticky top-0 z-50 bg-white/80 backdrop-blur-lg shadow-sm">
    <div class="max-w-5xl mx-auto px-6">
      <div class="flex justify-between items-center h-16">
        <a href="#" class="text-xl font-bold text-gray-900">Irfan Fauzan R.</a>
        <div class="hidden md:flex space-x-8">
          <a href="#about" class="nav-link">About</a>
          <a href="#experience" class="nav-link">Experience</a>
          <a href="#projects" class="nav-link">Projects</a>
          <a href="#skills" class="nav-link">Skills</a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script setup>
// No script logic needed
</script>

<style scoped>
.nav-link {
  @apply text-gray-600 hover:text-gray-900 transition-colors duration-300;
}
</style>
