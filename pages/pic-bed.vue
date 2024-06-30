<template>
 <main class="min-h-screen">
  <AppHeader class="mb-8" title="图床" :description="description" />
  <div class="relative" ref="imgWall" />
 </main>
</template>

<script setup lang="ts">
  const description = "🌁功能开发中,敬请期待...";
  useSeoMeta({
    title: "图床 | ixyz",
    description,
  });
</script>
