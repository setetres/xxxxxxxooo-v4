<template>
    <Bar />
    <div class="divide-y divide-zinc-700 overflow-hidden rounded-lg bg-zinc-700 shadow sm:grid sm:grid-cols-2 sm:gap-px sm:divide-y-0 border border-zinc-700">
        <div class="relative group sm:col-span-2 bg-zinc-900 p-12 focus-within:ring-2 focus-within:ring-inset focus-within:ring-fuchsia-500">
            <div>
                <span class="rounded-lg inline-flex text-white overflow-hidden">
                    <img src="~assets/images/v1.png" width="2560" height="1440" alt="" />
                </span>
            </div>
            <dl class="uppercase divide-y divide-zinc-800">
                <Detail name="Project">
                    v1
                </Detail>
                <Detail name="Description">
                    👻 v1.0 of my website.
                </Detail>
                <Detail name="Framework">
                    Vue / NuxtJS
                </Detail>
                <Detail name="Responsive">
                    <Tag>
                        Yes
                    </Tag>
                </Detail>
                <Detail name="Year">
                    2008
                </Detail>
            </dl>
        </div>
        <CardExternal
        label="Source Code"
        title="View on GitHub"
        description="github.com/setetres/v1"
        url="https://github.com/setetres/v1"
        class="rounded-bl-lg"
        >
    </CardExternal>
    <CardExternal
    label="Live"
    title="View Project"
    description="v1.setetres.st"
    url="https://github.com/setetres/v1"
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
