<template>
  <section id="projects" class="py-24">
    <div class="text-center mb-12">
      <h2 class="text-4xl font-bold text-gray-900">Projects</h2>
      <p class="text-gray-500 mt-2">A selection of my recent work</p>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-10">
      <ProjectCard
        v-for="project in projects"
        :key="project.title"
        :title="project.title"
        :description="project.description"
        :techStack="project.techStack"
        :projectUrl="project.url"
      />
    </div>
  </section>
</template>

<script setup>
import { ref } from "vue";
import ProjectCard from "./ProjectCard.vue";

const projects = ref([
  {
    title: "Warehouse Management Application",
    description:
      "A full-stack web app built with Laravel to digitize and streamline QC sample management, helping non-staff to easily manage samples.",
    techStack: ["Laravel", "PHP", "MySQL", "Full-Stack"],
    url: "#", // <-- UPDATE THIS URL (e.g., your GitHub repo)
  },
  {
    title: "Milk Quality Prediction Tool",
    description:
      "A machine learning app using Python & Flask that allows non-analysts to predict milk quality, improving lab workflow efficiency.",
    techStack: ["Python", "Flask", "Machine Learning", "Data Science"],
    url: "#", // <-- UPDATE THIS URL
  },
  {
    title: "Perkutut News",
    description:
      "A Magazine website built with Laravel, featuring a user-friendly interface and robust content management system for seamless article publishing.",
    techStack: [
      "Laravel",
      "PHP",
      "MySQL",
      "Filament",
      "Blade",
      "Tailwind CSS",
      "Full-Stack",
    ],
    url: "#", // <-- UPDATE THIS URL
  },
  {
    title: "Portofolio Website",
    description:
      "A personal portfolio website built with Vue.js, showcasing my projects and skills.",
    techStack: ["Vue.js", "JavaScript", "CSS", "Tailwind CSS", "Frontend"],
    url: "#", // <-- UPDATE THIS URL
  },
]);
</script>
