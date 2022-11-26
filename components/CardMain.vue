<template>
    <div class="relative group bg-zinc-900 p-12 focus-within:ring-2 focus-within:ring-inset focus-within:ring-white">
        <span class="rounded-lg flex text-white overflow-hidden">
            <slot />
        </span>
        <div class="mt-6">
            <h3 class="font-medium">
                <NuxtLink :to="url" class="focus:outline-none">
                    <span class="absolute inset-0" aria-hidden="true"></span>
                    <HeadingSans>{{ label }}</HeadingSans>
                    <HeadingSerif class="text-4xl group-hover:text-fuchsia-400">
                        {{ title }}
                    </HeadingSerif>
                </NuxtLink>
            </h3>
            <p class="mt-2 text-gray-400 uppercase">{{ description }}</p>
        </div>
    </div>
</template>
<script>
export default {
    props: [
        "label",
        "title",
        "description",
        "url",
    ],
}
</script>