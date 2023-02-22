<template>
  <div class="flex bg-[#1d1d1d] relative">
    <div class="w-[13rem] relative">
      <Sidebar />
    </div>
    <div class="main w-full flex-1 relative">
      <Header />
      <slot />
    </div>
  </div>
</template>
