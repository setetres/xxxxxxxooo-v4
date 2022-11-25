<template>
    <a :href="url" class="text-zinc-300 hover:text-fuchsia-400 rounded-full p-1">
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