<script setup>
import Song from "./Song.vue";
</script>

<template>
  <div class="category">
    <header>
      <h1>Focus</h1>
      <a href="#">Show all</a>
    </header>
    <main class="flex gap-x-5">
      <Song />
      <Song />
      <Song />
      <!-- <Song />
      <Song />
      <Song /> -->
    </main>
  </div>
</template>
