<template>
    <h1 class="flex justify-center font-semibold">{{props.cardTitle}}</h1>
    </template>

    <script setup>
const props = defineProps({
  cardTitle: {
    type: String,
    default:'Heading'
  }
  });
</script>