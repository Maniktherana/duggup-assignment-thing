<div>
	<div class="hidden md:flex flex-row justify-between gap-1 w-full max-w-screen-2xl">
		{#each new Array(350) as _, i}
			<div class="w-[1px] h-[1px] bg-[#525C69] rounded-full"></div>
		{/each}
	</div>
	<div class="md:hidden flex flex-row justify-between gap-1 w-full">
		{#each new Array(100) as _, i}
			<div class="w-[1px] h-[1px] bg-[#525C69] rounded-full"></div>
		{/each}
	</div>
</div>
