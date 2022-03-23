<template>
  <p class="box-content max-w-screen-md mx-auto">
    {{props.cardInfo}}
  </p>
</template>

<script setup>
import { defineProps } from "vue";
const props = defineProps({
  cardInfo: {
    type: String
  }
});
</script>