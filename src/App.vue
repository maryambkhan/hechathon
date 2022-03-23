<template>
  <TheHeader />
  <main>
  <HeroSection :img="heroImage"/>
  <div>
  <CardImage :img="cardImage" />
  <CardHeader :cardTitle="cardTitle" />
  <CardInfo :cardInfo="cardInfo" />
  <CardImage :img="cardsImage" />
  <CardHeader :cardTitle="cardsTitle" />
  <CardInfo :cardInfo="cardsInfo" />
  </div>
  </main>
  <TheFooter :title="'&copy;  2022'" />
</template>

// imports
<script setup>
import TheHeader from "./components/TheHeader.vue";
import HeroSection from "./components/HeroSection.vue";
import CardHeader from "./components/CardHeader.vue";
import CardImage from "./components/CardImage.vue";
import CardInfo from "./components/CardInfo.vue";
import TheFooter from "./components/TheFooter.vue";

// first card
const cardTitle = "Lipstic";

const cardInfo = "Lorem Ipsum is simply dummy text of the printing and typesetting industry Lorem Ipsum has been the industrys standard dummy text ever since the 1500s";

const cardImage = {
  url : "https://images.pexels.com/photos/2533266/pexels-photo-2533266.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260",
  alt:"product"
}
// hero section
const heroImage = {
  url : "https://images.pexels.com/photos/7290089/pexels-photo-7290089.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260",
  alt: "Hero Image"
}

// second card
const cardsTitle = "Brushes";

const cardsInfo = "Lorem Ipsum is simply dummy text of the printing and typesetting industry Lorem Ipsum has been the industrys standard dummy text ever since the 1500s";

const cardsImage = {
  url : "https://images.pexels.com/photos/208052/pexels-photo-208052.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260",
  alt:"product"
}
</script>