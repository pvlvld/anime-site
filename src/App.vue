<template>
  <div class="flex flex-col min-h-screen font-Roboto bg-anime-background">
    <SiteNavigation />
    <RouterView />
  </div>
</template>

<script setup lang="ts">
import { RouterView } from 'vue-router';
</script>
