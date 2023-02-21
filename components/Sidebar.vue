<script setup>
// import { Icon } from "@iconify/vue";
import Home from "~/components/icons/Home.vue";
import Search from "~/components/icons/Search.vue";
import Library from "~/components/icons/Library.vue";
import Add from "~/components/icons/Add.vue";
import Love from "~/components/icons/Love.vue";
import Globe from "~/components/icons/Globe.vue";
</script>

<template>
  <div
    class="sidebar h-full max-w-[15rem] bg-black text-white px-6 py-6 flex flex-col justify-between"
  >
    <section class="main-links flex flex-col gap-y-10">
      <div class="logo w-[8rem]">
        <img src="/logo.png" alt="" />
      </div>
      <article class="flex flex-col text-sm font-bold gap-y-4">
        <a href="#" class="flex items-center gap-x-4">
          <Home />
          <p>Home</p>
        </a>
        <a href="#" class="flex items-center gap-x-4">
          <Search />
          <p>Search</p>
        </a>
        <a href="#" class="flex items-center gap-x-4">
          <Library />
          <p>Your Library</p>
        </a>
      </article>
      <article class="flex flex-col items-start gap-y-4 text-sm font-bold">
        <a href="#" class="flex items-center gap-x-4">
          <Add />
          <p>Create Playlist</p>
        </a>
        <a href="#" class="flex items-center gap-x-4">
          <Love />
          <p>Likes Songs</p>
        </a>
      </article>
    </section>
    <section class="flex flex-col items-start gap-y-8">
      <ul class="max-w-[10rem] flex gap-4 flex-wrap text-xs">
        <li><a href="">Legal</a></li>
        <li><a href="">Privacy Center</a></li>
        <li><a href="">Privacy Policy</a></li>
        <li><a href="">Cookies</a></li>
        <li><a href="">About Ads</a></li>
        <li><a href="">Cookies</a></li>
      </ul>

      <button
        class="flex items-center gap-x-2 text-sm font-bold border border-1 px-3 py-1 rounded-full"
      >
        <Globe />
        English
      </button>
    </section>
  </div>
</template>
