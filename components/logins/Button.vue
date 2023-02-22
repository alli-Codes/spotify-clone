<script setup>
defineProps({
  buttonText: String,
});
</script>

<template>
  <button class="rounded-full font-bold text-sm">{{ buttonText }}</button>
</template>
