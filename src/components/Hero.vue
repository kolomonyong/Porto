<template>
  <section
    id="home"
    class="min-h-[90vh] flex flex-col justify-center items-center py-16 md:py-20 lg:py-24"
  >
    <div
      class="flex flex-col md:flex-row-reverse items-center justify-between max-w-5xl mx-auto gap-12"
    >
      <div
        class="flex-shrink-0 w-64 h-64 md:w-80 md:h-80 lg:w-96 lg:h-96 relative group"
      >
        <img
          src="/irfan-profile.jpg"
          alt="Irfan Fauzan Rahman"
          class="w-full h-full object-cover rounded-xl shadow-xl transition-transform duration-300 group-hover:scale-105"
        />
        <div
          class="absolute inset-0 bg-gradient-to-br from-gray-900 to-gray-600 opacity-10 rounded-xl"
        ></div>
      </div>

      <div class="text-center md:text-left flex-grow">
        <h1
          class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight leading-tight"
        >
          <span
            class="block bg-clip-text text-transparent bg-gradient-to-r from-gray-900 to-gray-600 pb-1"
          >
            Irfan Fauzan Rahman
          </span>
        </h1>

        <p
          class="text-lg md:text-xl lg:text-2xl text-gray-600 mt-4 max-w-xl md:max-w-none"
        >
          Informatics Engineering Student & Software Developer with a passion
          passion for building elegant solutions.
        </p>

        <div
          class="mt-8 flex flex-col sm:flex-row justify-center md:justify-start gap-4"
        >
          <a
            href="mailto:ifauzanrahman@gmail.com"
            class="inline-flex items-center justify-center bg-gray-900 text-white font-semibold py-3 px-8 rounded-lg shadow-lg transform hover:scale-105 transition-transform duration-300"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-5 w-5 mr-2"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"
              />
              <path
                d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"
              />
            </svg>
            Get In Touch
          </a>
          <a
            href="#projects"
            class="inline-flex items-center justify-center bg-white text-gray-800 font-semibold py-3 px-8 rounded-lg shadow-lg border border-gray-200 transform hover:scale-105 transition-transform duration-300"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-5 w-5 mr-2"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M3 4a1 1 0 011-1h12a1 1 0 011 1v10a1 1 0 01-1 1H4a1 1 0 01-1-1V4zm2 7v4h10v-4H5zm0-2h10V5H5v4zm5-2a1 1 0 00-1 1v1a1 1 0 102 0V7a1 1 0 00-1-1z"
                clip-rule="evenodd"
              />
            </svg>
            View My Work
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
// No script needed
</script>
