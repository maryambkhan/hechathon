<template>
    <h1 class="flex justify-center font-semibold text-lg">{{props.cardTitle}}</h1>
    </template>

    <script setup>
const props = defineProps({
  cardTitle: {
    type: String,
    default:'Heading'
  }
  });
</script>