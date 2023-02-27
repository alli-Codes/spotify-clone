<template>
  <div class="grid grid-cols-12 bg-[#1d1d1d] relative">
    <div class="col-span-2 relative">
      <Sidebar />
    </div>
    <div class="bg-[#121212] main col-span-10 relative">
      <Header />
      <slot />
    </div>
  </div>
</template>
