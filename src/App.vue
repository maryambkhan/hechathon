<template>
  <TheHeader />
  <TheLogo />
  
  <!-- Page Header -->
  <header class="flex flex-col items-center justify-center h-40 py-4">
    <h1 class="text-5xl uppercase md:text-6xl lg:text-7xl">
    </h1>
  </header>
   <HeroSection />
    <TheFooter />
</template>


<script setup>
import TheHeader from "./components/TheHeader.vue";
import HeroSection from "./components/HeroSection.vue";
import TheFooter from "./components/TheFooter.vue";
import TheNavBar from "./components/TheNavBar.vue";



</script>