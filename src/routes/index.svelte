<svelte:head>
    <title>
        Morxemplum - Main
    </title>
</svelte:head>
<div class="h-screen grid-cols-2 md:grid">
	<div class="relative">
		<a href="/career" class="group relative">
			<div
				class="absolute h-screen w-full bg-black bg-opacity-0 transition-all duration-200 group-hover:bg-opacity-25 group-hover:brightness-75"
			/>
			<div
				class="absolute flex h-screen w-full items-center justify-center text-center text-[70px] font-bold text-transparent transition-all duration-200 group-hover:text-white"
			>
				<div class="hover:underline">My Career</div>
			</div>
			<img
				class="z-0 h-screen w-full object-cover"
				src="/images/banner1.webp"
				alt="My Career"
			/>
		</a>
	</div>
	<div class="h-screen">
		<div class="h-2/4 w-full bg-black">
			<a href="/career" class="group relative">
				<div
					class="absolute h-full w-full bg-black bg-opacity-0 transition-all duration-200 group-hover:bg-opacity-25 group-hover:brightness-75"
				/>
				<div
					class="absolute flex h-full w-full items-center justify-center text-center text-[70px] font-bold text-transparent transition-all duration-200 group-hover:text-white"
				>
					<div class="hover:underline">Other Projects</div>
				</div>
				<img
					class="z-0 h-full w-full object-cover"
					src="/images/banner3.webp"
					alt="Other Projects"
				/>
			</a>
		</div>
		<div class="h-2/4 w-full bg-black">
			<a href="/about" class="group relative">
				<div
					class="absolute h-full w-full bg-black bg-opacity-0 transition-all duration-200 group-hover:bg-opacity-25 group-hover:brightness-75"
				/>
				<div
					class="absolute flex h-full w-full items-center justify-center text-center text-[70px] font-bold text-transparent transition-all duration-200 group-hover:text-white"
				>
					<div class="hover:underline">About Me</div>
				</div>
				<img
					class="z-0 h-full w-full object-cover object-bottom"
					src="/images/banner2.webp"
					alt="About Me"
				/>
			</a>
		</div>
	</div>
</div>
