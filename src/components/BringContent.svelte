<script>
	import mentorship from '$lib/assets/mentorship.jpg';
	import funnel from '$lib/assets/funnel.jpg';
	import creator from '$lib/assets/creator.png';
	import programmer from '$lib/assets/programmer.jpg';

	const contents = [
		{
			banner: funnel,
			desc: 'Funnel Builder'
		},
		{
			banner: mentorship,
			desc: 'Mentorship Site'
		},
		{
			banner: creator,
			desc: 'Customer Services'
		},
		{
			banner: programmer,
			desc: 'Course Creator'
		}
	];
</script>
<section class="p-12">
	
<div class="py-12 w-full max-w-7xl mx-auto">
	<div class=" animate__animated animate__bounceInLeft text-center">
		<h2 class="text-2xl md:text-4xl font-semibold text-[#04082f]">
			Bring your Content and <br /> Community Together!
		</h2>
	</div>
	<div
		class="w-full md:max-w-7xl mx-auto mt-10 md:mt-20 flex flex-wrap justify-around lg:justify-between py-10 gap-10"
	>
		{#each contents as content}
			<div
				class="w-72 bg-white rounded-xl animate__animated animate__tada flex flex-col items-center justify-center gap-6 px-4 py-3"
			>
				<div class="w-32 h-32 rounded-full mx-auto overflow-hidden">
					<img
						src={content.banner}
						class="w-full h-full object-cover object-center rounded-full custom-shadow "
						alt=""
					/>
				</div>
				<h3 class="text-lg font-semibold">{content.desc}</h3>
			</div>
		{/each}
	</div>

	<div class="w-full flex items-center justify-center mt-2 md:mt-20">
		<button
			class="w-fit px-10 py-4 animate__animated animate__bounceInUp animate__delay-2s bg-[#FBBD23] text-white text-lg font-semibold rounded-sm"
			>Get Started for Free</button
		>
	</div>
</div>

</section>