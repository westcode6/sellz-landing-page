<script>
	import Branded from '../../components/Branded.svelte';
	import Footer from '../../components/Footer.svelte';
	import Navbar from '../../components/Navbar.svelte';


    // Images
    import smiles from "$lib/assets/laugh.png"

</script>

<Navbar />
<section class="bg-blue-100 p-6 md:p-12">
	<div class="p-6 md:p-12 w-full max-w-xl mx-auto">
		<div class="flex flex-col items-center justify-center">
			<h1 class="text-2xl md:text-4xl font-bold text-[#04082f]">How can we help?</h1>
			<p class="text-base sm:text-xl mt-4">Sellz Documentation</p>
			<div class="w-full relative py-10">
				<input
					type="text"
					class="w-full h-12 px-4 rounded bg-white text-gray-500"
					placeholder="Search something..."
				/>

				<button class="px-4 py-3 absolute right-0 bg-orange-400 hover:bg-orange-500 transform transition hover:-translate-x-1 duration-150 text-white rounded-xl"
					>Search</button
				>
			</div>
		</div>
	</div>
</section>

<section class="p-6 md:p-12">
	<h1 class="text-2xl md:text-4xl font-medium text-gray-400 text-center">
		Explore the Documentation
	</h1>

	<!-- Contact Support and Contact Sales -->
	<div class="">
		<div
			class="p-6 md:p-12 w-full max-w-7xl mx-auto flex flex-col sm:flex-row items-start justify-between gap-10"
		>
			<div
				class="w-full max-w-sm flex flex-col items-center justify-center text-center border-t-2 bg-orange-50 border-orange-400 py-10 px-10"
			>
				<h2 class="text-[#04082f] text-xl font-semibold">Contact Support</h2>
				<p class="py-4 text-base">
					Discover the basics of running a profitable school through Sellz
				</p>
				<button
					class="w-fit mt-6 border-2 border-orange-400 hover:bg-orange-400 rounded-full text-orange-400 hover:text-white text-sm font-semibold px-6 py-2"
					>See more</button
				>
			</div>

			<div
				class="w-full max-w-sm flex flex-col items-center justify-center text-center border-t-2 bg-orange-50 border-orange-400 py-10 px-10"
			>
				<h2 class="text-[#04082f] text-xl font-semibold">Contact Support</h2>
				<p class="py-4 text-base">
					Discover the basics of running a profitable school through Sellz
				</p>
				<button
					class="w-fit mt-6 border-2 border-orange-400 hover:bg-orange-400 rounded-full text-orange-400 hover:text-white text-sm font-semibold px-6 py-2"
					>See more</button
				>
			</div>

			<div
				class="w-full max-w-sm flex flex-col items-center justify-center text-center border-t-2 bg-orange-50 border-orange-400 py-10 px-10"
			>
				<h2 class="text-[#04082f] text-xl font-semibold">Contact Support</h2>
				<p class="py-4 text-base">
					Discover the basics of running a profitable school through Sellz
				</p>
				<button
					class="w-fit mt-6 border-2 border-orange-400 hover:bg-orange-400 rounded-full text-orange-400 hover:text-white text-sm font-semibold px-6 py-2"
					>See more</button
				>
			</div>
		</div>
	</div>
</section>


<!-- Cant find what you're looking for? -->

<section class="w-full max-w-7xl mx-auto rounded-2xl p-12 flex flex-col items-center md:flex-row gap-10 justify-between">
	
    <div class="w-full md:w-1/2 lg:p-12">
		<img src={smiles} class="w-full h-full object-cover object-center" alt="" />
	</div>


	<div class="w-full md:w-1/2 lg:px-24 mt-6 md:mt-0 px-4">
		<h1 class="text-2xl md:text-4xl text-[#04082f] font-bold">Can't find what you're looking for?</h1>
		<p class="mt-2 md:mt-2 text-sm md:text-xl text-[#04082f] font-normal">
            Please reach out to our customer
            care team and we’ll assist you.
		</p>

        <a href="/" class="w-fit mt-10 px-8 py-3 bg-orange-500 text-orange-100 font-semibold hover:underline transform transition hover:-translate-x-1 flex gap-4">Contact Us <span><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3" />
          </svg>
          </span></a>
	</div>

  
</section>

<Branded />
<Footer />
