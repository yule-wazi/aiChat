<template>
  <div class="App">
    <RouterView />
  </div>
</template>

<script setup>
import { RouterView } from 'vue-router'
</script>

<style scoped>
.App {
  height: 100vh;
  width: 100vw;
  overflow: hidden;
  background-image: url('./assets/img/【哲风壁纸】下雨-绿色护眼-车站.png');
  background-position: center;
  background-size: cover;
}
</style>
