<script setup lang="ts">
defineProps<{
  msg: string;
}>();
</script>

<template>
  <p>{{ msg }}</p>
</template>

<style scoped>
p {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}
</style>
