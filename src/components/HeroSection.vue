<template>  
  <img
    :src="props.img.url"
    :alt="props.img.alt"
    class="flex justify-center  h-1/4 mt-1"
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