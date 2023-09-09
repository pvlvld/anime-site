<template>
  <div class="container content-center grid grid-cols-6 gap-4 h-screen noise">
    <div class="col-start-1 col-end-3">
      <h3 class="text-5xl">
        <slot name="title"></slot>
      </h3>
      <p class="text-2xl">
        <slot name="description"></slot>
      </p>
    </div>

    <div class="col-end-7 col-span-2 bg-flag relative">
      <UAFlag></UAFlag>
    </div>
  </div>
</template>

<script setup lang="ts">
const test = 0;
import UAFlag from './UAFlag.vue';
</script>
<style scoped>
.bg-flag {
  background-position: 100vh;
  /* background-image: url('/Flag_of_Ukraine.png'); */
}
</style>
