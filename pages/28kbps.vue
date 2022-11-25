<template>
    <div class="divide-y divide-zinc-700 overflow-hidden rounded-lg bg-zinc-700 shadow sm:grid sm:grid-cols-2 sm:gap-px sm:divide-y-0 border border-zinc-700">
        <Bar title="v14" />
        <div class="relative group sm:col-span-2 bg-zinc-900 p-12 focus-within:ring-2 focus-within:ring-inset focus-within:ring-fuchsia-500">
            <div>
                <span class="rounded-lg inline-flex text-white overflow-hidden">
                    <img src="~assets/images/28kbps.png" width="2560" height="1440" alt="" />
                </span>
            </div>
            <div class="aspect-w-16 aspect-h-9">
                <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/o7GLLbly_6A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
            <dl class="uppercase divide-y divide-zinc-800">
                <Detail name="Project">
                    28kbps
                </Detail>
                <Detail name="Description">
                    ✏️ v14.0 of my website.
                </Detail>
                <Detail name="Framework">
                    EP
                </Detail>
                <Detail name="Responsive">
                    <Tag>
                        Yes
                    </Tag>
                </Detail>
                <Detail name="Year">
                    2022
                </Detail>
            </dl>
        </div>
        <CardExternal
            label="Source Code"
            title="View on GitHub"
            description="github.com/setetres/v14"
            url="https://github.com/setetres/v14"
            class="rounded-bl-lg"
        >
        </CardExternal>
        <CardExternal
            label="Live"
            title="View Project"
            description="v14.setetres.st"
            url="https://github.com/setetres/v14"
            class="rounded-br-lg pattern"
        >
        </CardExternal>
    </div>
</template>
<script lang="ts">
export default {
    mounted() {
    },
}
</script>
