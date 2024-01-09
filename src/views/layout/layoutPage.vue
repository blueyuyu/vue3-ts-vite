<script setup lang="ts"></script>

<template>
  <div class="layout-page">
    <div style="width: 100%; height: 30px; background-color: pink">1111</div>
    <div class="main">
      <router-view></router-view>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.layout-page {
  width: 100vw;
  height: 100vh;
  background-color: skyblue;
}
</style>
