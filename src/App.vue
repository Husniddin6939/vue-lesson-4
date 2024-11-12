<template>
  <MainLayout>
    <template #header="slot">
      <h1>
        header {{ slot.title }}
      </h1>
    </template>

    <template #main="slot">
      <h1>
        Main
      </h1>
    </template>

    <template #footer="slot">
      <h1>
        footer
      </h1>
    </template>

  </MainLayout>
  
</template>

<script setup>
import MainLayout from "./layouts/main-layout.vue";
</script>