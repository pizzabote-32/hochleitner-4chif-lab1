<script setup lang="ts">
defineProps<{
  linkTitle: string;
}>();
</script>

<template>
  <NuxtLink class="p-2 bg-blue-200" :to="`${linkTitle}`">
    {{ linkTitle }}</NuxtLink
  >
</template>
