<template>
  <div class="flex flex-col xl:flex-row min-h-screen bg-zinc-900 max-w-14xl border-r border-zinc-700">
    <Header />
  </div>
</template>
<script setup>
  const props = defineProps({
    error: Object
  })
</script>
