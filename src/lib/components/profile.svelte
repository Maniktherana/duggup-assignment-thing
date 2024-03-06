<script>
	import { Button } from '$lib/components/ui/button';
	import * as DropdownMenu from '$lib/components/ui/dropdown-menu';
</script>

<section class="max-w-screen-xl flex flex-row justify-center items-center mt-10 w-full gap-10">
	<div class="flex flex-col justify-center items-center min-w-[120px]">
		<img
			src="/avatar1.jpeg"
			alt="avatar"
			class="w-[120px] h-[120px] border-[5px] border-[#EAEFF5] rounded-full"
		/>
		<h1 class="font-bold text-xl text-[#4B5C6D] text-center">Krishna <br /> Kiran</h1>
	</div>
	<div class="flex flex-col justify-between items-center gap-5">
		<div class="flex flex-row justify-between items-center gap-24">
			<p class="max-w-screen-sm text-sm">
				Co-Founder and CEO at Duggup - Social network for people in tech. Ex-Amazon Head of
				Engineering. I write hot-takes on building a business, shipping delightful products and
				accelerating product and career growth.
			</p>
			<div class="flex flex-col justify-end items-end">
				<img src="/logo1.png" alt="logo" class="w-[36px] rounded-full" />
				<p class="font-bold">Duggup</p>
				<p class="text-sm text-[#7A9299]">Co-Founder and CEO</p>
			</div>
		</div>
		<div class="w-full flex flex-row justify-between items-center">
			<Button variant="default">Following</Button>
			<div class="flex flex-row items-center">
				<a href="/" target="_blank">
					<Button variant="link" size="sm" class="gap-2">
						<p>My website</p>
						<svg
							width="16"
							height="16"
							viewBox="0 0 16 16"
							fill="none"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								d="M7.20156 1.59961H4.00156C2.67608 1.59961 1.60156 2.67413 1.60156 3.99961V11.9997C1.60156 13.3252 2.67608 14.3997 4.00156 14.3997H12.0016C13.327 14.3997 14.4016 13.3252 14.4016 11.9997V8.79961M10.4012 1.5998L14.4016 1.59961M14.4016 1.59961V5.19971M14.4016 1.59961L7.60098 8.39942"
								stroke="#4D4D4D"
								stroke-width="1.5"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
						</svg>
					</Button>
				</a>
				<DropdownMenu.Root>
					<DropdownMenu.Trigger>
						<Button variant="link" size="sm">
							<svg
								width="24"
								height="6"
								viewBox="0 0 24 6"
								fill="none"
								xmlns="http://www.w3.org/2000/svg"
							>
								<path
									d="M4.90078 2.99922C4.90078 3.71719 4.31875 4.29922 3.60078 4.29922C2.88281 4.29922 2.30078 3.71719 2.30078 2.99922C2.30078 2.28125 2.88281 1.69922 3.60078 1.69922C4.31875 1.69922 4.90078 2.28125 4.90078 2.99922ZM13.3008 2.99922C13.3008 3.71719 12.7188 4.29922 12.0008 4.29922C11.2828 4.29922 10.7008 3.71719 10.7008 2.99922C10.7008 2.28125 11.2828 1.69922 12.0008 1.69922C12.7188 1.69922 13.3008 2.28125 13.3008 2.99922ZM21.7008 2.99922C21.7008 3.71719 21.1188 4.29922 20.4008 4.29922C19.6828 4.29922 19.1008 3.71719 19.1008 2.99922C19.1008 2.28125 19.6828 1.69922 20.4008 1.69922C21.1188 1.69922 21.7008 2.28125 21.7008 2.99922Z"
									stroke="#A5B9D3"
									stroke-width="3"
								/>
							</svg>
						</Button>
					</DropdownMenu.Trigger>
					<DropdownMenu.Content side="bottom" sideOffset={10}>
						<DropdownMenu.Group>
							<DropdownMenu.Label>Options</DropdownMenu.Label>
							<DropdownMenu.Separator />
							<DropdownMenu.Item>Share</DropdownMenu.Item>
							<DropdownMenu.Item>Edit</DropdownMenu.Item>
						</DropdownMenu.Group>
					</DropdownMenu.Content>
				</DropdownMenu.Root>
			</div>
		</div>
	</div>
</section>
