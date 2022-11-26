<template>
    <nav class="flex justify-end col-span-2 bg-zinc-900 uppercase" aria-label="Breadcrumb">
        <ol role="list" class="flex">
            <li class="flex pattern px-6 py-1 mx-4 my-4 rounded-lg">
                <div class="flex items-center">
                    <span class="text-white" aria-current="page">{{ title }}</span>
                </div>
            </li>
            <li class="flex border-r border-zinc-900 rounded-b-lg">
                <div class="flex items-center">
                    <NuxtLink to="/" class=px-12 py-6 text-gray-400 hover:text-fuchsia-400 focus-within:ring-2 focus-within:ring-inset focus-within:ring-white rounded-tr-lg">
                        <svg class="h-5 w-5 flex-shrink-0" fill="currentColor" viewBox="0 0 448 512">
                            <path d="M9.4 233.4c-12.5 12.5-12.5 32.8 0 45.3l160 160c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L109.2 288 416 288c17.7 0 32-14.3 32-32s-14.3-32-32-32l-306.7 0L214.6 118.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0l-160 160z"/>
                        </svg>
                        <span class="sr-only">Home</span>
                    </NuxtLink>
                </div>
            </li>
        </ol>
    </nav>
</template>
<script>
export default {
    props: [
    'title',
    ]
}
</script>