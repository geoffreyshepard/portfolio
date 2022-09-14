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
						use these <a href="/resume" class="underline text-teal-400 cursor-pointer">tools</a>
						and have worked on some cool
						<a href="/resume" class="underline text-teal-400 cursor-pointer">projects</a>
					</p>
				{:else if bioCount == 4}
					<p class="text-white z-10 relative">
						I like making things on the internet that are fast, beautiful, and functional I love to
						use these <a href="/resume" class="underline text-teal-400 cursor-pointer">tools</a>
						and have worked on some cool
						<a href="/resume" class="underline text-teal-400 cursor-pointer">projects</a>
					</p>
					<p class="text-white z-10 relative mt-4">
						I have an amazing wife and 2 year old daughter.
					</p>
				{:else if bioCount == 5}
					<p class="text-white z-10 relative">
						I like making things on the internet that are fast, beautiful, and functional I love to
						use these <a href="/resume" class="underline text-teal-400 cursor-pointer">tools</a>
						and have worked on some cool
						<a href="/resume" class="underline text-teal-400 cursor-pointer">projects</a>
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

<svg
	viewbox="0 0 1440 320"
	xmlns="http://www.w3.org/2000/svg"
	class="rotate-180 fixed bottom-0 hidden sm:block z-0"
>
	<defs>
		<style type="text/css">
			.wave {
				animation: wave 12s linear infinite;
			}

			.wave1 {
				animation: wave1 16s linear infinite;
			}

			.wave2 {
				animation: wave2 20s linear infinite;
			}

			@keyframes wave {
				0% {
					transform: translateX(0%);
				}

				100% {
					transform: translateX(100%);
				}
			}

			@keyframes wave1 {
				0% {
					transform: scaleY(1.2) translateX(0%);
				}

				100% {
					transform: scaleY(1.2) translateX(100%);
				}
			}

			@keyframes wave2 {
				0% {
					transform: scaleY(0.8) translateX(0%);
				}

				100% {
					transform: scaleY(0.8) translateX(100%);
				}
			}
		</style>
		<path
			id="sineWave"
			fill="#2dd4bf"
			fill-opacity="0.2"
			d="M0,160 C320,300,420,300,740,160 C1060,20,1120,20,1440,160 V0 H0"
			height="200px"
		/>
	</defs>
	<use class="z-0 wave" href="#sineWave" />
	<use class="z-0 wave" x="-100%" href="#sineWave" />
	<use class="z-0 wave1" href="#sineWave" />
	<use class="z-0 wave1" x="-100%" href="#sineWave" />
	<use class="z-0 wave2" href="#sineWave" />
	<use class="z-0 wave2" x="-100%" href="#sineWave" />
</svg>
