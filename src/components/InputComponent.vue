<script setup lang="ts">
defineProps<{
  title: string,
  description: string,
}>();

defineEmits(['update:title', 'update:description']);
</script>

<template>
  <input type="text" :value="title" @input="$emit('update:title', $event.target.value)" />
  <input type="text" :value="description" @input="$emit('update:description', $event.target.value)" />
</template>

<style scoped>

</style>