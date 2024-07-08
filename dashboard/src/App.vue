<script setup>
import SideBar from './components/SideBar.vue';
import Screen from './components/Screen.vue';
</script>

<template>
  <div class="container flex">
    <div class="left-sections">
      <SideBar />
    </div>
    <div class="right-sections bg-screenBackground">
      <Screen />
    </div>
  </div>
</template>

<style scoped></style>
