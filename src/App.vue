<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>

<template>
  <div class="view">
    <RouterView />
  </div>
</template>

<style scoped>
.view {
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
