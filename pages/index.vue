<script setup>
import Category from "~~/components/category/Category.vue";
</script>

<template>
  <div class="grad"></div>
  <div class="px-10 py-6 flex flex-col gap-y-8 relative overflow-x-hidden">
    <Category categoryName="Focus" />
    <Category categoryName="Spotify Playlists" />
  </div>
</template>

<style scoped>
.grad {
  background-color: rgb(83, 83, 83);
  background-image: linear-gradient(rgba(0, 0, 0, 0.6) 0, #121212, #121212);
  height: 332px;
  width: 100%;
  position: absolute;
}
</style>
