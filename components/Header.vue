<script setup>
import { Icon } from "@iconify/vue";
// import Arrows from "./icons/Arrows.vue";
import Button from "./logins/Button.vue";
</script>

<template>
  <header
    class="w-full px-8 py-2 bg-[#101010] flex justify-between items-center sticky top-0"
  >
    <div class="arrows text-white flex gap-x-8">
      <Icon icon="material-symbols:arrow-back-ios" />
      <Icon icon="material-symbols:arrow-forward-ios" />
      <!-- <Arrows /> -->
    </div>
    <div class="logins flex gap-x-1">
      <Button class="text-white px-8 py-3" buttonText="Sign up" />
      <Button class="px-8 py-3 bg-white" buttonText="Log in" />
    </div>
  </header>
</template>
