<script>
	let bioCount = 3;
</script>

<section class="w-full md:w-[768px] m-auto">
	<header class="text-center w-[405px] m-auto">
		<h1 class="text-7xl uppercase font-black text-white">Geoffrey</h1>
		<h2 class="text-7xl uppercase tracking-wide bg-white text-gray-900 p-2 px-4">Shepard</h2>
		<h3 class="text-lg mt-3 font-black font-sans text-white">
			Web Architect . Developer . Designer
		</h3>
	</header>

	<div class="my-32 w-full md:w-[768px] z-1">
		<div>
			<p class="text-center text-xs tracking-wider uppercase mb-4 text-teal-400">
				Biography Length:
			</p>
		</div>
		<div class="flex justify-center items-center">
			<span class="text-center text-xs tracking-wider mr-2 text-teal-400">Quick</span>
			<span
				class="inline-flex w-[16px] h-[16px] p-2 mx-2 cursor-pointer rounded-full border-2 border-teal-400 z-10 relative {bioCount ==
				1
					? 'bg-teal-400 border-teal-400'
					: ''}"
				on:click={() => {
					bioCount = 1;
				}}
			/>
			<span
				class="inline-flex w-[16px] h-[16px] p-2 mx-2 cursor-pointer rounded-full border-2 border-teal-400 z-10 relative {bioCount ==
				2
					? 'bg-teal-400 border-teal-400'
					: ''}"
				on:click={() => {
					bioCount = 2;
				}}
			/>
			<span
				class="inline-flex w-[16px] h-[16px] p-2 mx-2 cursor-pointer rounded-full border-2 border-teal-400 z-10 relative {bioCount ==
				3
					? 'bg-teal-400 border-teal-400'
					: ''}"
				on:click={() => {
					bioCount = 3;
				}}
			/>
			<span
				class="inline-flex w-[16px] h-[16px] p-2 mx-2 cursor-pointer rounded-full border-2 border-teal-400 z-10 relative {bioCount ==
				4
					? 'bg-teal-400 border-teal-400'
					: ''}"
				on:click={() => {
					bioCount = 4;
				}}
			/>
			<span
				class="inline-flex w-[16px] h-[16px] p-2 mx-2 cursor-pointer rounded-full border-2 border-teal-400 z-10 relative {bioCount ==
				5
					? 'bg-teal-400 border-teal-400'
					: ''}"
				on:click={() => {
					bioCount = 5;
				}}
			/>
			<span class="text-center text-xs tracking-wider ml-2 text-teal-400">Fast</span>
		</div>

		<div class="mt-10 mb-10 w-full md:w-[500px] px-12 m-auto h-96 z-10">
			<div>
				{#if bioCount == 1}
					<p class="text-white z-10 relative">I like making things on the internet.</p>
				{:else if bioCount == 2}
					<p class="text-white z-10 relative">
						I like making things on the internet that are fast, beautiful, and functional.
					</p>
				{:else if bioCount == 3}
					<p class="text-white z-10 relative">
						I like making things on the internet that are fast, beautiful, and functional I love to
						use these <a href="/about#tools" class="underline text-teal-400 cursor-pointer">tools</a
						>
						and have worked on some cool projects
					</p>
				{:else if bioCount == 4}
					<p class="text-white z-10 relative">
						I like making things on the internet that are fast, beautiful, and functional I love to
						use these <a href="/about#tools" class="underline text-teal-400 cursor-pointer">tools</a
						>
						and have worked on some cool projects
					</p>
					<p class="text-white z-10 relative mt-4">
						I have an amazing wife and 2 year old daughter.
					</p>
				{:else if bioCount == 5}
					<p class="text-white z-10 relative">
						I like making things on the internet that are fast, beautiful, and functional I love to
						use these <a href="/about#tools" class="underline text-teal-400 cursor-pointer">tools</a
						>
						and have worked on some cool projects
					</p>
					<p class="text-white z-10 mt-4">
						I have an amazing wife and 2 year old daughter. I love sports especially the Kansas City
						Chiefs & Sporting KC.
					</p>
				{/if}
			</div>
		</div>
	</div>
</section>
