<template>
  <div class="about">
    <ElementsPage />
  </div>
</template>

<script setup lang="ts">
import ElementsPage from '../components/elementsPage.vue'
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
