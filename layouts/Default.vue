<template>
  <div class="flex bg-[#1d1d1d] relative">
    <div class="w-[13rem] relative">
      <Sidebar />
    </div>
    <div class="main flex-1 relative overflow-x-hidden">
      <Header />
      <slot />
    </div>
  </div>
</template>
