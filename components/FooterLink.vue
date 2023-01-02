<template>
  <a :href="url" class="p-1 text-white hover:text-fuchsia-500 rounded-full">
    <span class="sr-only">{{ label }}</span>
    <slot />
  </a>
</template>
<script>
export default {
  props: [
  'label',
  'url',
  ]
}
</script>
