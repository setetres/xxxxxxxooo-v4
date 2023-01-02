<script setup lang="ts">
const route = useRoute()
</script>
<template>
  <div class="flex flex-col xl:flex-row min-h-screen bg-zinc-900 max-w-14xl border-r border-zinc-700">
    <NuxtLoadingIndicator color="#d946ef" />
    <div class="m-6 mb-0 md:m-12 md:mb-0 xl:mb-12 xl:mr-0 max-w-7xl">
      <div class="divide-y divide-zinc-700 overflow-hidden rounded-lg bg-zinc-700 shadow sm:grid sm:grid-cols-2 sm:gap-px sm:divide-y-0 border border-zinc-700">
        <NuxtPage />
      </div>
    </div>
    <Header />
  </div>
</template>
