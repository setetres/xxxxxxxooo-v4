<script setup lang="ts">
  const route = useRoute()
</script>
<template>
  <App>
    <NuxtLoadingIndicator color="#d946ef" />
    <Content>
      <NuxtPage />
    </Content>
    <Header />
  </App>
</template>
