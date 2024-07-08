<script setup>
import Dashboard from './Dashboard.vue';
import SectionSeparator from './SectionSeparator.vue';
import ApplicationsSection from './ApplicationsSection.vue';
import PagesSection from './PagesSection.vue';
</script>

<template>
  <div class="my-1 mx-3">
    <Dashboard />
    <SectionSeparator />
    <ApplicationsSection />
    <SectionSeparator />
    <PagesSection />
  </div>
</template>

<style scoped></style>
