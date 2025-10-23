<template>
  <section id="skills" class="py-24 bg-white rounded-xl shadow-md">
    <div class="text-center mb-12">
      <h2 class="text-4xl font-bold text-gray-900">Skills & Competencies</h2>
      <p class="text-gray-500 mt-2">Technologies and methods I work with</p>
    </div>
    <div class="max-w-4xl mx-auto grid grid-cols-2 md:grid-cols-4 gap-8">
      <div class="skill-item">
        <div class="icon-wrapper">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-8 h-8"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M17.25 6.75L22.5 12l-5.25 5.25m-10.5 0L1.5 12l5.25-5.25m7.5-3l-4.5 16.5"
            />
          </svg>
        </div>
        <h3 class="text-xl font-semibold text-gray-900 mt-4">Languages</h3>
        <p class="text-gray-600 mt-1">Python, PHP, JavaScript, TypeScript, SQL</p>
      </div>

      <div class="skill-item">
        <div class="icon-wrapper">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-8 h-8"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M21 7.5l-9-5.25L3 7.5m18 0l-9 5.25m9-5.25v9l-9 5.25M3 7.5l9 5.25M3 7.5v9l9 5.25m0-9v9"
            />
          </svg>
        </div>
        <h3 class="text-xl font-semibold text-gray-900 mt-4">Frameworks</h3>
        <p class="text-gray-600 mt-1">Laravel, Vue.js, React.js, Next.js, Flask, Scikit-learn</p>
      </div>

      <div class="skill-item">
        <div class="icon-wrapper">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-8 h-8"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M11.42 15.17L17.25 21A2.652 2.652 0 0021 17.25l-5.877-5.877M11.42 15.17l2.472-2.472a3.375 3.375 0 00-4.773-4.773L6.75 5.25l-2.472 2.472a3.375 3.375 0 004.773 4.773z"
            />
          </svg>
        </div>
        <h3 class="text-xl font-semibold text-gray-900 mt-4">Tools & Tech</h3>
        <p class="text-gray-600 mt-1">Git, GitHub, Docker, REST APIs</p>
      </div>

      <div class="skill-item">
        <div class="icon-wrapper">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-8 h-8"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M10.125 2.25h-4.5c-1.125 0-2.063.938-2.063 2.063v15.375c0 1.125.938 2.063 2.063 2.063h12.75c1.125 0 2.063-.938 2.063-2.063V11.19a2.063 2.063 0 00-.603-1.465l-4.225-4.225a2.063 2.063 0 00-1.465-.603h-1.688a2.063 2.063 0 01-2.063-2.063v-1.688z"
            />
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M15 1.5v5.52a1 1 0 001 1h5.52M9 13.5l3 3m0 0l3-3m-3 3v-6"
            />
          </svg>
        </div>
        <h3 class="text-xl font-semibold text-gray-900 mt-4">Methodologies</h3>
        <p class="text-gray-600 mt-1">Quality Control, 5S, Data Reporting</p>
      </div>
    </div>
  </section>
</template>

<script setup>
// No script logic needed
</script>

<style scoped>
.skill-item {
  @apply text-center;
}
.icon-wrapper {
  @apply w-16 h-16 bg-gray-100 rounded-full flex items-center justify-center mx-auto text-gray-800;
}
</style>
