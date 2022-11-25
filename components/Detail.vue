<template>
    <div class="py-4 sm:grid sm:grid-cols-3 sm:gap-4 sm:py-5">
        <dt class="font-medium text-gray-500">{{ name }}</dt>
        <dd class="mt-1 flex text-white sm:col-span-2 sm:mt-0">
            <span class="flex-grow">
                <slot />
            </span>
        </dd>
    </div>
</template>
<script>
  export default {
    props: ['name']
  }
</script>