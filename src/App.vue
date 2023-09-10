<template>
  <div class="flex flex-col min-h-screen font-Roboto">
    <SiteNavigation />
    <RouterView />
  </div>
</template>

<script setup lang="ts">
import { RouterView } from 'vue-router';
</script>
