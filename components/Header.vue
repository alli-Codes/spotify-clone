<script setup>
// import { Icon } from "@iconify/vue";
import Arrows from "./icons/Arrows.vue";
import Button from "./logins/Button.vue";
</script>

<template>
  <header
    class="w-full px-8 py-5 bg-[#101010] flex justify-between sticky top-0"
  >
    <div class="arrows text-white">
      <Arrows />
    </div>
    <div class="logins">
      <Button />
    </div>
  </header>
</template>
