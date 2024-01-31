<script>
	import 'animate.css';

	import smile from '$lib/assets/laugh.png';
	import smilers from '$lib/assets/shes.png';
	import laughBanner from '$lib/assets/laugn-png.png';
	import Navbar from '../../components/Navbar.svelte';
	import Branded from '../../components/Branded.svelte';
	import Achieves from '../../components/Achieves.svelte';
	import Footer from '../../components/Footer.svelte';
</script>

<Navbar />
<section class="w-full bg-blue-100 p-12">
	<div class="w-full max-w-7xl mx-auto">
		<div class="flex flex-col md:flex-row justify-between">
			<div class="md:w-1/2 max-w-lg mx-auto flex flex-col justify-center">
				<h4 class="text-base text-[#04082f] flex items-center gap-4 font-semibold">
					Our #1 Goal <span class=" block w-20 border-b-4 border-orange-400"></span>
				</h4>
				<h1 class="my-6 md:text-5xl text-5xl text-[#04082f] capitalize font-black">
					To make teaching and learning online easy for everyone
				</h1>
				<p class="text-base md:text-xl mt-6 text-gray-400">
					<a href="/signup" class="text-base text-orange-500 font-semibold flex gap-2"
						>Get Started for FREE <span
							><svg
								xmlns="http://www.w3.org/2000/svg"
								fill="none"
								viewBox="0 0 24 24"
								stroke-width="1.5"
								stroke="currentColor"
								class="w-6 h-6"
							>
								<path
									stroke-linecap="round"
									stroke-linejoin="round"
									d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"
								/>
							</svg>
						</span></a
					>
				</p>
			</div>
			<div class="w-full md:w-1/2 mx-auto flex items-center justify-center lg:justify-end">
				<div class="">
					<div class="w-full max-w-lg mx-auto z-10 rounded-lg mt-6 md:mt-0 lg:ml-4">
						<img alt="card img" class="object-cover object-center" src={laughBanner} />
						<!-- <div class="text-2xl p-10 bg-white"><img alt="quote" class="float-left mr-1" src="https://assets-global.website-files.com/5b5a66e9f3166b36708705fa/5cf8fb1f994fb7168d0d66fb_quote-intro.svg"> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam</div> -->
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<!-- BRANDED SECTION -->
<Branded />

<!-- WHAT THIS IS ALL ABOUT -->

<!-- General Communication  -->
<section class="p-6 md:p-12 bg-[#04082f] text-blue-50 rounded-b-3xl">
	<div class="w-full max-w-7xl mx-auto flex flex-col sm:flex-row items-center justify-between">
		<div class="w-full max-w-lg flex gap-4 items-start justify-start py-10 px-10">
			<span class="w-10 h-3 bg-orange-400 rounded-full animate-ping"></span>
			<div class="flex flex-col items-start text-left">
				<h3 class="text-white text-xl font-semibold">What is this for</h3>
				<p class="py-4 text-base">
					All you need is an idea and one simple tool - Sellz. Create, build, and sell online
					courses the smarter way by leveraging on this powerful tool to share and sell your ideas
					by having your school under your brand name.
				</p>
			</div>
		</div>

		<div class="w-full max-w-lg flex items-start gap-5 justify-start text-left py-10 px-10">
			<span class="w-10 h-3 bg-orange-400 rounded-full animate-ping"></span>
			<div class="flex flex-col items-start text-left">
				<h3 class="text-white text-xl font-semibold">Who is this for</h3>
				<p class="py-4 text-base">
					All you need is an idea and one simple tool - Courselify. Create, build, and sell online
					courses the smarter way by leveraging on this powerful tool to share and sell your ideas
					by having your school under your brand name.
				</p>
			</div>
		</div>
	</div>
</section>

<!-- THE PROBLEM -->
<section class="p-6 md:p-12">
	<div class="w-full max-w-7xl mx-auto flex flex-col sm:flex-row justify-between gap-5 items-center">
		<div class="w-full max-w-lg">
			<img src={smile} class="w-full object-center object-cover" alt="smiles" />
		</div>

		<div class="w-full max-w-lg px-4">
			<h1 class="text-[#04082f] font-semibold text-2xl sm:text-4xl">The Problem</h1>
			<h4 class="mt-4 text-orange-500 font-medium flex items-center gap-2">
				<span
					class="w-8 h-8 bg-orange-500 rounded-full flex items-center justify-center text-white text-xs"
					>1</span
				> Create Engaging Courses, connect with Studentss
			</h4>

			<h4 class="mt-4 text-sm md:text-lg text-gray-500 flex items-center gap-2">
				<span class="w-8 h-8 rounded-full flex items-center justify-center text-gray-500 text-sm"
					>2</span
				> Create Engaging Courses, connect with Studentss
			</h4>

			<h4 class="mt-4 text-sm md:text-lg text-gray-500 flex items-center gap-2">
				<span class="w-8 h-8 rounded-full flex items-center justify-center text-gray-500 text-sm"
					>3</span
				> Create Engaging Courses, connect with Studentss
			</h4>

			<h4 class="mt-4 text-sm md:text-lg text-gray-500 flex items-center gap-2">
				<span class="w-8 h-8 rounded-full flex items-center justify-center text-gray-500 text-sm"
					>4</span
				> Create Engaging Courses, connect with Studentss
			</h4>
			<h4 class="mt-4 text-sm md:text-lg text-gray-500 flex items-center gap-2">
				<span class="w-8 h-8 rounded-full flex items-center justify-center text-gray-500 text-sm"
					>5</span
				> Create Engaging Courses, connect with Studentss
			</h4>

			<div class="mt-10">
				<a
					href="/signup"
					class="text-base sm:text-lg text-orange-400 font-semibold ml-4 flex items-center gap-4"
					>Sign up for FREE <span
						><svg
							xmlns="http://www.w3.org/2000/svg"
							fill="none"
							viewBox="0 0 24 24"
							stroke-width="1.5"
							stroke="currentColor"
							class="w-6 h-6"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"
							/>
						</svg>
					</span></a
				>
			</div>
		</div>
	</div>
</section>

<!-- OUR SOLUTION -->
<section class="p-6 md:p-12">
	<div class="w-full max-w-7xl mx-auto flex flex-col sm:flex-row justify-between gap-10 md:gap-5 items-center">
		<div class="w-full max-w-lg px-4">
			<h1 class="text-[#04082f] font-semibold text-2xl sm:text-4xl">Our Solution</h1>
			<h4 class="mt-4 text-sm md:text-lg text-orange-500 font-medium flex items-center gap-2">
				<span
					class="w-8 h-8 bg-orange-500 rounded-full flex items-center justify-center text-white text-xs"
					>1</span
				> Create Engaging Courses, connect with Studentss
			</h4>

			<h4 class="mt-4 text-sm md:text-lg text-gray-500 flex items-center gap-2">
				<span class="w-8 h-8 rounded-full flex items-center justify-center text-gray-500 text-sm"
					>2</span
				> Create Engaging Courses, connect with Studentss
			</h4>

			<h4 class="mt-4 text-sm md:text-lg text-gray-500 flex items-center gap-2">
				<span class="w-8 h-8 rounded-full flex items-center justify-center text-gray-500 text-sm"
					>3</span
				> Create Engaging Courses, connect with Studentss
			</h4>

			<h4 class="mt-4 text-sm md:text-lg text-gray-500 flex items-center gap-2">
				<span class="w-8 h-8 rounded-full flex items-center justify-center text-gray-500 text-sm"
					>4</span
				> Create Engaging Courses, connect with Studentss
			</h4>
			<h4 class="mt-4 text-sm md:text-lg text-gray-500 flex items-center gap-2">
				<span class="w-8 h-8 rounded-full flex items-center justify-center text-gray-500 text-sm"
					>5</span
				> Create Engaging Courses, connect with Studentss
			</h4>

			<div class="mt-10">
				<a
					href="/signup"
					class="text-base sm:text-lg bg-orange-500 px-6 py-2 w-fit rounded-full text-white font-semibold ml-4 flex items-center gap-4"
					>Sign up for FREE <span
						><svg
							xmlns="http://www.w3.org/2000/svg"
							fill="none"
							viewBox="0 0 24 24"
							stroke-width="1.5"
							stroke="currentColor"
							class="w-6 h-6"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"
							/>
						</svg>
					</span></a
				>
			</div>
		</div>

		<div class="w-full max-w-lg">
			<img src={smile} class="w-full object-center object-cover" alt="smiles" />
		</div>
	</div>
</section>

<!-- BRING CONTENT -->
<Achieves />

<!-- BUILDING YOUR COMMUNITY -->
<section>
	<main class="p-6 md:p-12 bg-[#04082f] text-blue-50">
		<div class="w-full max-w-7xl mx-auto flex flex-col sm:flex-row justify-between gap-10 md:gap-5 items-center">
			<div class="w-full max-w-md">
				<img src={smilers} class="w-full object-center object-cover" alt="smiles" />
			</div>
			<div class="w-full max-w-lg">
				<h1 class="text-white font-semibold text-2xl sm:text-4xl">Building Your Community</h1>

				<p class="mt-6 text-lg md:text-2xl">
					Leverage on our beautiful platform designed for you and your students to grow your
					teaching business and build your professional school with just a few clicks, in minutes.
				</p>
			</div>
		</div>

		<section class="w-full sm:max-w-7xl mx-auto mt-10 p-2 md:p-12">
			<div
				class="bg-blue-100 rounded-2xl p-6 md:p-12 flex flex-col items-start md:items-center md:flex-row justify-between gap-10 shadow-xl"
			>
				<div class="w-full max-w-md mt-6">
					<h3 class="text-2xl md:text-2xl text-[#04082f] font-semibold">Join other Creators</h3>
					<p class="mt-3 text-gray-600 text-xl font-semibold">
						Join other active creators to help people's lives by embracing teaching online
					</p>
				</div>

				<div class="w-full max-w-52 flex">
					<a
						href="/"
						class="w-full px-4 py-3 bg-orange-500 text-orange-100 text-center font-semibold hover:underline transform transition hover:-translate-x-1 flex items-center justify-center gap-4"
						>Get Started for FREE
					</a>
				</div>
			</div>
		</section>
	</main>
</section>

<!-- STILL NEED HELP -->

<section
	class="bg-orange-50 rounded-2xl p-6 md:p-12 flex flex-col items-center md:flex-row justify-between"
>
	<div class="w-full max-w-7xl mx-auto flex flex-col md:flex-row gap-10 md:gap-5 items-center justify-around">
		<div class="w-full max-w-60 md:max-w-sm mt-6 md:mt-0 px-4">
			<h1 class="text-2xl md:text-4xl text-[#04082f] font-bold">Still Need Help?</h1>
			<p class="mt-2 pr-10 md:mt-2 text-sm md:text-xl text-[#04082f] font-normal">
				Please reach out to our customer care team and we’ll assist you.
			</p>

			<a
				href="/"
				class="w-fit mt-10 px-8 py-3 bg-orange-500 text-orange-100 font-semibold hover:underline transform transition hover:-translate-x-1 flex gap-4"
				>Talk To Support <span
					><svg
						xmlns="http://www.w3.org/2000/svg"
						fill="none"
						viewBox="0 0 24 24"
						stroke-width="1.5"
						stroke="currentColor"
						class="w-6 h-6"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3"
						/>
					</svg>
				</span></a
			>
		</div>

		<div class="w-full max-w-lg lg:p-12">
			<img src={laughBanner} class="w-full h-full object-cover object-center" alt="" />
		</div>
	</div>
</section>

<!-- GET STARTED -->

<section class="w-full sm:max-w-7xl mx-auto mt-10 p-6 md:p-12">
	<div
		class="bg-blue-100 rounded-2xl p-6 md:p-12 flex flex-col items-start md:items-center md:flex-row justify-between gap-10"
	>
		<div class="w-full max-w-2xl mt-6">
			<h3 class="text-2xl md:text-2xl text-[#04082f] font-semibold">
				Create your course, build your brand, grow your business.
			</h3>
		</div>

		<div class="w-full max-w-52 flex ">
			<a
				href="/"
				class="w-full px-4 py-3 text-orange-500 text-center font-semibold hover:underline transform transition hover:-translate-x-1 flex items-center justify-center gap-4"
				>Get Started for FREE
			</a>
		</div>
	</div>
</section>
<!-- FOOTER SECTION -->

<Footer />
