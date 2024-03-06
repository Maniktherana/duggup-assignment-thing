<script>
	import Nav from '$lib/components/nav.svelte';
</script>

<div class="flex flex-col justify-center items-center">
	<Nav />
	<div class="flex flex-row justify-between items-center gap-1 w-full max-w-screen-2xl">
		{#each new Array(300) as _, i}
			<div class="w-[1px] h-[1px] bg-[#525C69] rounded-full"></div>
		{/each}
	</div>
	<section class="max-w-screen-xl"></section>
	<section class="max-w-screen-xl"></section>
</div>

<style lang="postcss">
	:global(html) {
		background-color: '#FCFCFF';
	}
</style>
