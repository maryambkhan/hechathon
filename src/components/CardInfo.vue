<template>
  <p class="box-content max-w-screen-md mx-auto">
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