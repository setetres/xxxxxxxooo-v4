<template>
    <div class="relative group bg-zinc-900 p-12 focus-within:ring-2 focus-within:ring-inset focus-within:ring-white">
        <div class="mt-6">
            <h3 class="font-medium">
                <a :href="'https://' + url" class="focus:outline-none" target="_blank" rel="noopener noreferrer">
                    <span class="absolute inset-0" aria-hidden="true"></span>
                    <HeadingSans>{{ label }}</HeadingSans>
                    <HeadingSerif class="text-4xl group-hover:text-fuchsia-400">
                        {{ title }}
                    </HeadingSerif>
                </a>
            </h3>
            <p class="mt-2 text-gray-400 uppercase">{{ description }}</p>
        </div>
        <span class="pointer-events-none absolute top-6 right-6 text-zinc-300 group-hover:text-white" aria-hidden="true">
            <IconArrow class="h-6 w-6"/>
        </span>
    </div>
</template>
<script>
export default {
    props: [
    'label',
    'title',
    'description',
    'url',
    ]
}
</script>