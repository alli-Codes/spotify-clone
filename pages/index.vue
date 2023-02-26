<script setup>
import Category from "~~/components/category/Category.vue";
</script>

<template>
  <div
    class="px-10 py-6 flex flex-col gap-y-8 relative overflow-x-hidden bg-green-500"
  >
    <Category categoryName="Focus" />
    <Category categoryName="Spotify Playlists" />
  </div>
</template>
