<script setup lang="ts">
const route = useRoute()
</script>
<template>
	<div class="flex min-h-screen bg-zinc-900 max-w-14xl border-r border-zinc-700">
		<NuxtLoadingIndicator />
		<div class="m-12 mr-0 max-w-7xl">
			<div class="divide-y divide-zinc-700 overflow-hidden rounded-lg bg-zinc-700 shadow sm:grid sm:grid-cols-2 sm:gap-px sm:divide-y-0 border border-zinc-700">
				<NuxtPage />
			</div>
		</div>
    	<Header />
	</div>
</template>
<script lang="ts">
export default {
	mounted() {
	},
}
</script>