<script>
	import NavBorder from '$lib/components/nav-border.svelte';
	import Nav from '$lib/components/nav.svelte';
	import Profile from '$lib/components/profile.svelte';
</script>

<div class="flex flex-col justify-center items-center">
	<Nav />
	<NavBorder />
	<Profile />
	<section class="max-w-screen-xl"></section>
</div>

<style lang="postcss">
	:global(html) {
		background-color: '#FCFCFF';
	}
</style>
