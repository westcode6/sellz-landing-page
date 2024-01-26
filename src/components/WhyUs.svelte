<script>
	import icon from '$lib/assets/01.svg';
	import dashboard from '$lib/assets/dash.png';

	const whychooseus = [
		{
			title: 'Manage everything in one place',
			desc: 'Link your domain, create engaging sessions via text, videos, coaching sessins and customize your online school with our custom school builder'
		},

		{
			title: 'Zero Experience Needed',
			desc: 'Use our drag and drop page builder, edit and modify your school - all tailored to your need'
		},

		{
			title: 'Get paid from everywhere',
			desc: '	Track sales and increase your reach. Manage your earnings as you grow on the platform.'
		},

		{
			title: 'Manage everything in one place',
			desc: 'Link your domain, create engaging sessions via text, videos, coaching sessins and customize your online school with our custom school builder'
		},

		{
			title: 'Deliver Exceptional Results',
			desc: 'Make real impact with the best online learning experience. Create quizzes, offer assessments and certificates, track students progress and follow up with communities and memberships'
		}
	];
</script>

<section class="mt-10 md:mt-20 p-12 w-full max-w-7xl mx-auto ">
	<div class="w-full sm:max-w-lg mx-auto text-center">
		<h2 class="text-2xl md:text-4xl font-semibold text-[#04082f]">Why Choose Sellz ?</h2>
	</div>

	<main class="w-full my-10 sm:my-20 flex flex-col lg:flex-row items-center justify-between">
		<aside class="w-full lg:max-w-xl  flex flex-wrap items-center justify-start">
			{#each whychooseus as why}
				<div
					class="w-[95%] md:w-[90%] flex items-center border-b border-gray-200 pb-4 px-2 mt-4 shadow-sm hover:shadow-sm rounded-xl lg:px-12"
				>
					<div class="w-20 h-20 flex items-start justify-center">
						<img src={icon} alt="" />
					</div>
					<div class="px-6 lg:px-2 py-2">
						<h5 class="text-lg font-semibold">{why.title}</h5>
						<p class="w-full sm:max-w-xs mt-2">
							{why.desc}
						</p>
					</div>
				</div>
			{/each}
		</aside>

		<div class="w-[90%] md:w-[50%] mt-20 ">
			<img
				src={dashboard}
				class="rounded-xl shadow-lg  object-cover object-center"
				alt="dashboard view"
			/>
		</div>
	</main>
</section>
