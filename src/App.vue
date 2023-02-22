<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="wrapper">
    <div class="nav">
      <RouterLink to="/publish">发布订阅者模式</RouterLink>
      <RouterLink to="/about">装饰器模式</RouterLink>
    </div>
    <RouterView />
  </div>
</template>

<style scoped>
.wrapper {
  display: flex;

}

.nav {
  display: flex;
  flex-direction: column;
}
</style>
