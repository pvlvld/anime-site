<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue';
import WelcomeScreen from './WelcomeScreen.vue';
import ToolingIcon from './icons/IconTooling.vue';
</script>

<template>
  <WelcomeScreen>
    <template #title> Хуха-Моховинка </template>
    <template #description> Test </template>
    <template #image> Test </template>
  </WelcomeScreen>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tooling</template>

    This project is served and bundled with
    <a
      href="https://vitejs.dev/guide/features.html"
      target="_blank"
      rel="noopener"
      >Vite</a
    >. The recommended IDE setup is
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener"
      >VSCode</a
    >
    +
    <a
      href="https://github.com/johnsoncodehk/volar"
      target="_blank"
      rel="noopener"
      >Volar</a
    >. If you need to test your components and web pages, check out
    <a href="https://www.cypress.io/" target="_blank" rel="noopener">Cypress</a>
    and
    <a href="https://on.cypress.io/component" target="_blank"
      >Cypress Component Testing</a
    >.

    <br />

    More instructions are available in <code>README.md</code>.
  </WelcomeItem>
</template>
