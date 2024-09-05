<script setup lang="ts">
import Link from "@/components/atoms/Link.vue";
import Searchbar from "@/components/molecules/Searchbar.vue";
</script>

<template>
  <nav class="flex justify-around my-6 mx-10">
    <Link linkTitle="Characters" />
    <Link linkTitle="Episodes" />
    <Searchbar />
  </nav>
</template>
