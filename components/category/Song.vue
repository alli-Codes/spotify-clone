<script setup>
import { ref } from "vue";
import Play from "../icons/Play.vue";
let isHover = ref(false);
const changeHoverState = (event) => {
  isHover.value = !isHover.value;
  //   console.log(event);
};
</script>

<template>
  <div
    class="container bg-[#181818] hover:bg-[#2a2a2a] transition-colors duration-500 w-48 p-4 rounded cursor-pointer relative"
  >
    <section class="image__section bg-red-400 rounded overflow-hidden relative">
      <img src="/images/miles.jpeg" class="h-40 object-cover" alt="" />
      <i class="bg-white p-2 m-1 rounded-full absolute top-0 left-0"></i>
    </section>
    <section class="text__section py-1 pt-4 flex flex-col gap-y-2 text-white">
      <h1 class="font-bold">Peaceful Piano</h1>
      <p class="text-sm">Relax and indulge with beautiful piano pieces</p>
    </section>
    <div
      class="overlay h-full w-full bg-transparent px-4 absolute top-0 left-0 hover:last:text-white z-30 rounded"
      @mouseover="changeHoverState"
      @mouseout="changeHoverState"
    >
      <div class="h-full flex items-center relative">
        <button
          class="h-1 w-1 p-6 flex justify-center items-center rounded-full absolute top-[45%] right-0 transition-all duration-500 ease"
          :class="isHover ? 'play__button' : ''"
        >
          <Play :fill="isHover ? 'black' : 'transparent'" />
        </button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.play__button {
  background-color: #1ed760;
  color: white;
  display: flex;
  top: 40%;
}
/*.overlay {
  background-color: #000000e7;
}*/
</style>
