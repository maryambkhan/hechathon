<template>
  <p class="flex flex-col justify-center box-content max-w-screen-md m-auto ">
    {{ props.cardInfo }}
  </p>
</template>

<script setup>
const props = defineProps({
  cardInfo: {
    type: String,
    default: 'detail'
  }
});
</script>