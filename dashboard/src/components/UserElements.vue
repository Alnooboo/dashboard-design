<script setup>
import ViewElements from './ViewElements.vue';
</script>

<template>
  <li>
    <button class="w-236 flex items-center py-2 px-3">
      <svg
        class="mx-1"
        width="12"
        height="12"
        viewBox="0 0 12 12"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <circle
          cx="6"
          cy="6"
          r="4.5"
          stroke="#2F2B3D"
          stroke-opacity="0.7"
          stroke-width="1.5"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
      </svg>
      <p class="px-2">List</p>
    </button>
  </li>
  <li>
    <button
      class="w-236 flex items-center rounded-lg bg-actionSelected py-2 px-3"
    >
      <svg
        class="mx-1"
        width="12"
        height="12"
        viewBox="0 0 12 12"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <circle
          cx="6"
          cy="6"
          r="4.5"
          stroke="#2F2B3D"
          stroke-opacity="0.7"
          stroke-width="1.5"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
      </svg>
      <p class="px-2">View</p>
      <svg
        class="ml-auto"
        width="22"
        height="22"
        viewBox="0 0 22 22"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M5.5 8.25L11 13.75L16.5 8.25"
          stroke="#2F2B3D"
          stroke-opacity="0.9"
          stroke-width="1.5"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
      </svg>
    </button>
    <ul class="flex flex-col gap-y-1 mt-1">
      <ViewElements />
    </ul>
  </li>
</template>

<style scoped></style>
