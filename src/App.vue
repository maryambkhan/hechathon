<template>
  <TheHeader />
  <main>
  <HeroSection :img="heroImage"/>
  <CardImage :img="cardImage" />
  <CardHeader :cardTitle="'cardTitle'" />
  <CardInfo :cardInfo="'cardInfo'" />
  </main>
  <TheFooter :title="'&copy; Maryam Khan 2022'" />
</template>

// imports
<script setup>
import TheHeader from "./components/TheHeader.vue";
import HeroSection from "./components/HeroSection.vue";
import CardHeader from "./components/CardHeader.vue";
import CardImage from "./components/CardImage.vue";
import CardInfo from "./components/CardInfo.vue";
import TheFooter from "./components/TheFooter.vue";

const cardHeader = "Lipstic";

const cardInfo = "Lorem Ipsum is simply dummy text of the printing and typesetting industry Lorem Ipsum has been the industrys standard dummy text ever since the 1500s";

const cardImage = {
  url : "https://images.pexels.com/photos/2533266/pexels-photo-2533266.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260",
  alt:"product"
}

const heroImage = {
  url : "https://images.pexels.com/photos/7290089/pexels-photo-7290089.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260",
  alt: "Hero Image"
}
</script>