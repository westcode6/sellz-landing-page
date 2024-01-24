<script>
	import clement from '$lib/assets/clement.jpg';
	import programmer from '$lib/assets/programmer.jpg';
	import boss from '$lib/assets/boss.png';

	const feedback = [
		{
			caption: 'Incredible experience',

			name: 'James Jeffery',
			profile: clement,
			feed: ' We had an incredible experience working with Sellz and were impressed they made such  big difference in only three weeks. Our team is so grateful for the wonderful improvements  they made and their ability to get familiar with the concept so quickly.',
			comapany: 'CEO, Gogluva'
		},

		{
			caption: 'Incredible experience',

			name: 'Franklin Dave',
			profile: boss,
			feed: ' We had an incredible experience working with Sellz and were impressed they made such  big difference in only three weeks. Our team is so grateful for the wonderful improvements  they made and their ability to get familiar with the concept so quickly.',
			comapany: 'CEO, Gogluva'
		},

		{
			caption: 'Incredible experience',
			name: 'Smith Anderson',
			profile: programmer,
			feed: ' We had an incredible experience working with Sellz and were impressed they made such  big difference in only three weeks. Our team is so grateful for the wonderful improvements  they made and their ability to get familiar with the concept so quickly.',
			comapany: 'CEO, Gogluva'
		}
	];
</script>

<main class="bg-bag">
	<section class="bg-[#04082f] bg-opacity-90 mt-10 md:mt-20 px-8 sm:px-10 lg:px-40 py-4 lg:py-20">
		<div class="flex items-center justify-between">
			<h2 class="w-72 text-white text-2xl md:text-4xl font-semibold">
				Real Stories from Real Customers
			</h2>

			<span class=" md:block">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="h-[149px] w-[80px] md:w-[176px]"
					viewBox="0 0 176 149"
					fill="none"
				>
					<g opacity="0.1" clip-path="url(#clip0_1_51727)">
						<path
							fill-rule="evenodd"
							clip-rule="evenodd"
							d="M0.771866 125.729C27.0171 112.8 40.1395 97.6096 40.1395 80.1562C28.953 78.8633 19.7028 74.2846 12.3885 66.4197C5.0743 58.5549 1.41725 49.4512 1.41725 39.1085C1.41725 28.1193 4.96675 18.854 12.0659 11.3124C19.165 3.77075 28.0925 0 38.8488 0C50.8958 0 61.3292 4.90198 70.1493 14.7061C78.9694 24.5102 83.3794 36.415 83.3794 50.4208C83.3794 92.4384 59.9312 125.298 13.0339 149L0.771866 125.729ZM93.3924 125.729C119.853 112.8 133.083 97.6096 133.083 80.1562C121.681 78.8633 112.323 74.2846 105.009 66.4197C97.6949 58.5549 94.0378 49.4512 94.0378 39.1085C94.0378 28.1193 97.6411 18.854 104.848 11.3124C112.054 3.77075 121.036 0 131.792 0C143.839 0 154.219 4.90198 162.931 14.7061C171.644 24.5102 176 36.415 176 50.4208C176 92.4384 152.659 125.298 105.977 149L93.3924 125.729Z"
							fill="white"
						/>
					</g>
					<defs>
						<clipPath id="clip0_1_51727">
							<rect width="176" height="149" fill="white" transform="matrix(-1 0 0 -1 176 149)" />
						</clipPath>
					</defs>
				</svg>
			</span>
		</div>

		<div class="my-10 sm:my-12">
			<section class="flex flex-wrap  items-center justify-around gap-2 md:gap-10">
				{#each feedback as feed}
					<div
						class="w-full mt-10 sm:w-[350px] custom-shadow  gap-4 flex flex-col items-center justify-center"
					>
						<div
							class="bg-white custom-shadow rounded-tr-xl rounded-bl-2xl rounded-tl-none p-4 flex flex-col items-center justify-center text-center"
						>
							<h3 class="text-lg text-[#04082f] font-bold">{feed.caption}</h3>
							<p class="py-4 text-sm">
								{feed.feed}
							</p>
						</div>
						<div class="flex items-center gap-4 rounded-xl py-4">
							<img src={clement} class="w-10 h-10 rounded-full object-cover object-center" alt="" />

							<div class="px-2">
								<h5 class="text-white text-base font-bold">{feed.name}</h5>
								<span class="text-gray-200 text-xs">{feed.comapany}</span>
							</div>
						</div>
					</div>
				{/each}
			</section>
		</div>
	</section>
</main>
