<script setup>
import Song from "./Song.vue";
defineProps({
  categoryName: String,
});
</script>

<template>
  <div class="category w-full">
    <header class="flex justify-between pb-8 text-white">
      <h1 class="font-bold text-2xl">{{ categoryName }}</h1>
      <a href="#" class="text-sm font-bold">Show all</a>
    </header>
    <main class="w-full grid grid-flow-col gap-x-6 px-4 overflow-hidden">
      <Song />
      <Song />
      <Song />
      <Song />
      <Song />
      <Song />
      <Song />
      <Song />
      <Song />
    </main>
  </div>
</template>
