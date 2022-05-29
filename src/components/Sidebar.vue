<script setup>
import Avatar from "./sidebar/Avatar.vue";
import Contact from "./sidebar/Contact.vue";
import OnTheWeb from "./sidebar/OnTheWeb.vue";
import Skills from "./sidebar/Skills.vue";
import Tools from "./sidebar/Tools.vue";
import Education from "./sidebar/Education.vue";
import Languages from "./sidebar/Languages.vue";
</script>

<template>
  <div class="w-full sm:max-w-sm p-8 bg-gradient-to-b from-indigo-300 via-green-300 to-white">
    <Avatar />
    <Contact />
    <OnTheWeb />
    <Skills />
    <Tools />
    <Education />
    <Languages />
  </div>
</template>
