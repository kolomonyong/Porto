<template>
  <div
    class="bg-white rounded-xl shadow-md overflow-hidden transform hover:-translate-y-2 transition-transform duration-300 border border-gray-100 h-full flex flex-col"
  >
    <div class="p-8 flex-grow">
      <h3 class="text-2xl font-bold text-gray-900 mb-3">{{ title }}</h3>
      <p class="text-gray-600 mb-6">{{ description }}</p>
    </div>
    <div class="px-8 pb-6 mt-auto">
      <div class="flex flex-wrap gap-2">
        <span
          v-for="tech in techStack"
          :key="tech"
          class="bg-gray-100 text-gray-800 text-sm font-medium px-4 py-1.5 rounded-full"
        >
          {{ tech }}
        </span>
      </div>

      <div v-if="projectUrl" class="mt-6">
        <a
          :href="projectUrl"
          target="_blank"
          rel="noopener noreferrer"
          class="inline-flex items-center text-gray-800 font-semibold border border-gray-300 py-2 px-5 rounded-lg hover:bg-gray-100 transition-colors"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5 mr-2"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            stroke-width="2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
            />
          </svg>
          View Project
        </a>
      </div>
    </div>
  </div>
</template>

<script setup>
defineProps({
  title: String,
  description: String,
  techStack: Array,
  projectUrl: String, // <-- ADD THIS PROP
});
</script>
