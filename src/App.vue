<script setup>
import Content from "./components/Content.vue";
import Sidebar from "./components/Sidebar.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="container mx-auto max-w-screen-xl">
    <main id="wrapper" class="flex flex-col sm:flex-row-reverse sm:m-12 shadow-2xl">
      <Sidebar />
      <Content />
    </main>
  </div>
  <Footer />
</template>

<style>
@import "./assets/base.css";
</style>
