<script lang="js">
	const achievments = [
		{
			count: '50+',
			desc: 'Course Creators'
		},
		{
			count: '100+',
			desc: 'Courses'
		},
		{
			count: '3',
			desc: 'Countries'
		},
		{
			count: '$10k+',
			desc: 'Course Creators'
		}
	];
</script>

<section class="bg-blue-50 shadow-sm px-12 py-4">
	<div
		class="w-full md:max-w-7xl mx-auto flex flex-wrap items-center justify-center lg:justify-around py-10 gap-10"
	>
		{#each achievments as achieved}
			<div
				class="w-[200px] bg-white shadow transition transform hover:-translate-x-0.5 flex flex-col items-center justify-center rounded-lg px-6 py-3"
			>
				<h3 class="text-2xl font-bold">{achieved.count}</h3>
				<p class="text-[#04082f] font-normal mt-2">{achieved.desc}</p>
			</div>
		{/each}
	</div>
</section>
