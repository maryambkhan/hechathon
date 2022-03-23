<template>
    <h1 class="flex justify-center font-semibold">{{props.cardTitle}}</h1>
    </template>

    <script setup>
import { defineProps } from "vue";
const props = defineProps({
  cardTitle: {
    type: String
  }
  });
</script>