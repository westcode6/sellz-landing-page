<script>
	import logo from '$lib/assets/sellz-logo.png';
</script>

<footer class="bg-[#04082f] px-8 sm:px-10 lg:px-32 py-4 lg:py-8">
	<section class="w-full max-w-7xl mx-auto mt-10 flex flex-col justify-between items-center">
		<div class="w-full">
			<img src={logo} class="w-20" alt="" />
		</div>

		<div class="w-full flex flex-col md:flex-row gap-10 justify-between items-start">
			<div class="w-52 mt-12">
				<h4 class="text-lg sm:text-2xl text-white font-semibold">Company</h4>

				<ul class="mt-10">
					<li class="py-2 text-sm text-gray-400 hover:underline"><a href="/about">About</a></li>
					<li class="py-2 text-sm text-gray-400 hover:underline"><a href="/">Blog</a></li>
					<li class="py-2 text-sm text-gray-400 hover:underline"><a href="/contact">Contact</a></li>
				</ul>
			</div>

			<div class="w-52 mt-12">
				<h4 class="text-lg sm:text-2xl text-white font-semibold">Explore</h4>
				<ul class="mt-10">
					<li class="py-2 text-sm text-gray-400 hover:underline"><a href="/">Pricing</a></li>
					<li class="py-2 text-sm text-gray-400 hover:underline"><a href="/">FAQs</a></li>
					<li class="py-2 text-sm text-gray-400 hover:underline"><a href="/">Features</a></li>
				</ul>
			</div>

			<div class="w-52 mt-12">
				<h4 class="text-lg sm:text-2xl text-white font-semibold">Resources</h4>
				<ul class="mt-10">
					<li class="py-2 text-sm text-gray-400 hover:underline">
						<a href="/documentation">Documentation</a>
					</li>
					<li class="py-2 text-sm text-gray-400 hover:underline">
						<a href="/">Video Tutorials</a>
					</li>
					<li class="py-2 text-sm text-gray-400 hover:underline"><a href="/">Report Center</a></li>
				</ul>
			</div>

			<div class="w-52 mt-12">
				<h4 class="text-lg sm:text-2xl text-white font-semibold">Legal</h4>
				<ul class="mt-10">
					<li class="py-2 text-sm text-gray-400 hover:underline"><a href="/">Privacy Policy</a></li>
					<li class="py-2 text-sm text-gray-400 hover:underline"><a href="/">Terms of Use</a></li>
					<li class="py-2 text-sm text-gray-400 hover:underline"><a href="/">Cookie Policy</a></li>
				</ul>
			</div>
		</div>
	</section>
	<div class="mt-20 sm:mt-52 flex items-center justify-center text-gray-400">
		<p>@2021 Sellz, All Rights Reserved</p>
	</div>
</footer>
