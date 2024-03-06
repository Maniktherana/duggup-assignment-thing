<script>
	import * as Card from '$lib/components/ui/card';
</script>

<section class="relative">
	<div class="w-full">
		<div
			class="flex flex-col sm:flex-row items-start mb-1 group-last:before:hidden before:absolute before:left-2 sm:before:left-0 before:h-full before:px-px before:bg-slate-300 sm:before:ml-[7rem] before:self-start before:-translate-x-1/2 before:translate-y-3"
		></div>
		<div class="relative pl-8 sm:pl-32 py-6 group">
			<!-- Vertical line (::before) ~ Date ~ Title ~ Circle marker (::after) -->
			<div
				class="flex flex-col sm:flex-row items-start mb-1 group-last:before:hidden before:absolute before:left-2 sm:before:left-0 before:h-full before:px-px before:bg-slate-300 sm:before:ml-[7rem] before:self-start before:-translate-x-1/2 before:translate-y-3 after:absolute after:left-2 sm:after:left-0 after:w-3 after:h-3 after:bg-white after:box-content after:border-[#0066FF] after:border-[3px] after:rounded-full sm:after:ml-[7rem] after:-translate-x-1/2 after:translate-y-32"
			>
				<time
					class="sm:absolute left-0 translate-y-32 mt-[-5px] inline-flex items-center justify-center text-xs font-light w-20 h-6 mb-3 sm:mb-0 text-[#7A9299]"
					>Dec, 2023</time
				>
			</div>
			<!-- Content -->
			<div class="flex flex-row justify-start items-center gap-10 flex-wrap ml-10">
				<Card.Root class="rounded-xl max-w-[350px] shadow-sm">
					<Card.Header class="m-0 p-0">
						<img
							src="/card1.jpeg"
							alt="card"
							class="max-w-[350px] h-[150px] object-cover rounded-t-xl"
						/>
					</Card.Header>
					<Card.Content>
						<p class="text-[#141618] text-sm font-light mt-5">
							No amount of technology can convert a bad story into a good story.
						</p>
					</Card.Content>
				</Card.Root>

				<Card.Root class="rounded-xl max-w-[350px] shadow-sm">
					<Card.Header class="m-0 p-0">
						<img
							src="/card2.jpeg"
							alt="card"
							class="max-w-[350px] h-[150px] object-cover rounded-t-xl"
						/>
					</Card.Header>
					<Card.Content>
						<p class="text-[#141618] text-sm font-light mt-5 overflow-hidden">
							Most people don't have original ideas. Here is how Sam Altman pushes...
						</p>
					</Card.Content>
				</Card.Root>
			</div>
		</div>

		<div class="relative pl-8 sm:pl-32 py-6 group">
			<!-- Vertical line (::before) ~ Date ~ Title ~ Circle marker (::after) -->
			<div
				class="flex flex-col sm:flex-row items-start mb-1 group-last:before:hidden before:absolute before:left-2 sm:before:left-0 before:h-full before:px-px before:bg-slate-300 sm:before:ml-[7rem] before:self-start before:-translate-x-1/2 before:translate-y-3 after:absolute after:left-2 sm:after:left-0 after:w-3 after:h-3 after:bg-white after:box-content after:border-[#0066FF] after:border-[9px] after:rounded-full sm:after:ml-[7rem] after:-translate-x-1/2 after:translate-y-12"
			>
				<div class="sm:absolute left-0 -translate-x-12 inline-flex flex-col items-end justify-end">
					<img src="/logo1.png" alt="logo" class="w-[48px] rounded-full" />
					<h3 class="font-bold text-lg">Duggup</h3>
					<p class="text-[#7A9299] text-xs font-light">San Francisco Bay Area</p>
					<p class="text-[#7A9299] text-xs font-light">Joined</p>
					<p class="text-[#7A9299] text-xs font-light">Nov 2022</p>
				</div>
			</div>
			<!-- Content -->
			<Card.Root class="w-full rounded-xl shadow-sm ml-10">
				<Card.Header class="pb-0">
					<h3 class="text-2xl font-bold">Co-Founder and CEO</h3>
				</Card.Header>
				<Card.Content class="pt-0 mt-1">
					<p class="text-[#7A9299] text-sm font-light mt-5">Full-time · Remote</p>
				</Card.Content>
			</Card.Root>
		</div>

		<div class="relative pl-8 sm:pl-32 py-6 group">
			<!-- Vertical line (::before) ~ Date ~ Title ~ Circle marker (::after) -->
			<div
				class="flex flex-col sm:flex-row items-start mb-1 group-last:before:hidden before:absolute before:left-2 sm:before:left-0 before:h-full before:px-px before:bg-slate-300 sm:before:ml-[7rem] before:self-start before:-translate-x-1/2 before:translate-y-3 after:absolute after:left-2 sm:after:left-0 after:w-3 after:h-3 after:bg-white after:box-content after:border-[#0066FF] after:border-[3px] after:rounded-full sm:after:ml-[7rem] after:-translate-x-1/2 after:translate-y-32"
			>
				<time
					class="sm:absolute left-0 translate-y-32 mt-[-5px] inline-flex items-center justify-center text-xs font-light w-20 h-6 mb-3 sm:mb-0 text-[#7A9299]"
					>Dec, 2023</time
				>
			</div>
			<!-- Content -->
			<div class="flex flex-row justify-start items-center gap-10 flex-wrap ml-10">
				<Card.Root class="rounded-xl max-w-[350px] shadow-sm">
					<Card.Header class="m-0 p-0">
						<img
							src="/card3.jpeg"
							alt="card"
							class="max-w-[350px] h-[150px] object-cover rounded-t-xl"
						/>
					</Card.Header>
					<Card.Content>
						<p class="text-[#141618] text-sm font-light mt-5">
							Startup Lesson I am reflecting. Don't build for the "average person".
						</p>
					</Card.Content>
				</Card.Root>

				<Card.Root class="rounded-xl max-w-[350px] shadow-sm">
					<Card.Header class="m-0 p-0">
						<img
							src="/card4.png"
							alt="card"
							class="max-w-[350px] h-[150px] object-cover rounded-t-xl"
						/>
					</Card.Header>
					<Card.Content>
						<p class="text-[#141618] text-sm font-light mt-5 overflow-hidden">
							Your biggest regrets at 80 will be acts of omission.
						</p>
					</Card.Content>
				</Card.Root>
			</div>
		</div>

		<div class="relative pl-8 sm:pl-32 py-6 group">
			<!-- Vertical line (::before) ~ Date ~ Title ~ Circle marker (::after) -->
			<div
				class="flex flex-col sm:flex-row items-start mb-1 group-last:before:hidden before:absolute before:left-2 sm:before:left-0 before:h-full before:px-px before:bg-slate-300 sm:before:ml-[7rem] before:self-start before:-translate-x-1/2 before:translate-y-3 after:absolute after:left-2 sm:after:left-0 after:w-3 after:h-3 after:bg-white after:box-content after:border-[#0066FF] after:border-[9px] after:rounded-full sm:after:ml-[7rem] after:-translate-x-1/2 after:translate-y-12"
			>
				<div class="sm:absolute left-0 -translate-x-12 inline-flex flex-col items-end justify-end">
					<img src="/logo2.jpeg" alt="logo" class="w-[48px] rounded-full" />
					<h3 class="font-bold text-lg">BetterUp</h3>
					<p class="text-[#7A9299] text-xs font-light">San Francisco Bay Area</p>
					<p class="text-[#7A9299] text-xs font-light">Joined</p>
					<p class="text-[#7A9299] text-xs font-light">Sep 2022</p>
				</div>
			</div>
			<!-- Content -->
			<Card.Root class="w-full rounded-xl shadow-sm ml-10">
				<Card.Header class="pb-0">
					<h3 class="text-2xl font-bold">VP Engineering</h3>
				</Card.Header>
				<Card.Content class="pt-0 mt-1">
					<p class="text-[#7A9299] text-sm font-light mt-5">Full-time</p>
				</Card.Content>
			</Card.Root>
		</div>
	</div>
</section>
