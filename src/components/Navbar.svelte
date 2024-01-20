<script lang="js">

import logo from "$lib/assets/sellz-logo.png"

	function hideNav() {
		var stikyNav = document.getElementById('stickyNav');
		if (stikyNav?.classList.contains('block')) {
			stikyNav.classList.remove('block');
			stikyNav.classList.add('hidden');
		}
	}


    function showNav() {
		var stikyNav = document.getElementById('stickyNav');
		if (stikyNav?.classList.contains('hidden')) {
			stikyNav.classList.remove('hidden');
			stikyNav.classList.add('block');
		}
	}
</script>

<nav
	class="w-full bg-[#04082F] px-4 sm:px-10 lg:px-32 py-4 lg:py-8 flex items-center justify-between"
>
	<div class="w-full md:w-3/6 flex items-center justify-between">
		<ul class="hidden md:flex">
			<li
				class="w-32 bg-[#04082f] rounded-full shadow-2xl transform transition ease-in-out hover:-translate-y-1 flex-grow text-white"
			>
				<a href="/product">Features</a>
			</li>
			<li
				class="w-32 bg-[#04082f] rounded-full shadow-2xl transform transition ease-in-out hover:-translate-y-1 flex-grow text-white"
			>
				<a href="/product">Pricing</a>
			</li>
			<li
				class="w-32 bg-[#04082f] rounded-full shadow-2xl transform transition ease-in-out hover:-translate-y-1 flex-grow text-white flex items-center"
			>
				<a href="/product">Resourses</a>
				<span
					><svg
						xmlns="http://www.w3.org/2000/svg"
						fill="none"
						viewBox="0 0 24 24"
						stroke-width="1.5"
						stroke="currentColor"
						class="w-4 h-4 ml-2"
					>
						<path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
					</svg>
				</span>
			</li>
		</ul>
		<div class="w-full flex items-center justify-between md:justify-end">
			<a href="/">
				<img src={logo} class="h-6 object-contain" alt="" />
			</a>

			<button on:click={showNav} class="block md:hidden">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="#fff"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="w-7 h-7 text-white"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
					/>
				</svg>
			</button>
		</div>
	</div>
	<div class="w-1/5 hidden md:flex items-center">
		<div class="w-full text-white flex items-center justify-between">
			<button>Sign In</button>
			<button class="border border-amber-400 text-amber-400 px-6 py-2">Sign Up for Free</button>
		</div>
	</div>
</nav>

<div id="stickyNav" class="absolute z-10 animate__animated animate__bounceInDown hidden top-0 bg-[#04082f] w-full h-full">
	<div class="w-full bg-[#04082] px-4 py-2 flex items-center justify-between">
        <a href="/">
            <img src={logo} class="h-6 object-contain" alt="" />
        </a>
		<button
			on:click={hideNav}
			id="closeNav"
			class="text-3xl text-white rounded-full p-1 shadow-2xl">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
                <path stroke-linecap="round" stroke-linejoin="round" d="m9.75 9.75 4.5 4.5m0-4.5-4.5 4.5M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
              </svg>
              
            </button
            
		>
	</div>

	<div class="w-full pt-16 md:flex flex-col items-center justify-center text-center">
		<ul class="flex flex-col items-center gap-10">
			<li
				class="w-32 bg-[#04082f] rounded-full shadow-2xl transform transition ease-in-out hover:-translate-y-1 flex-grow text-white"
			>
				<a href="/product">Features</a>
			</li>
			<li
				class="w-32 bg-[#04082f] rounded-full shadow-2xl transform transition ease-in-out hover:-translate-y-1 flex-grow text-white"
			>
				<a href="/product">Pricing</a>
			</li>
			<li class=" flex-grow text-white flex items-center"><a href="/product">Resourses</a></li>
		</ul>

		<div class="w-full text-white flex flex-col mt-10 items-center justify-between">
			<button>Sign In</button>
			<button class="mt-10 border border-amber-600 text-amber-600 px-6 py-2"
				>Sign Up for Free</button
			>
		</div>
	</div>
</div>
