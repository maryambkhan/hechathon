<template>
  <img
    :src="props.img.url"
    :alt="props.img.alt"
    class="flex justify-center w-full h-full mt-2"
  />
</template>

<script setup>
import { defineProps } from "vue";
const props = defineProps({
  img: {
    type: Object
  }
});
</script>