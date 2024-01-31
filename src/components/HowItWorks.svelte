<script>
    import icon from "$lib/assets/01.svg"
    import dashboard from "$lib/assets/dash.png"




</script>

<section class="mt-0 md:mt-0 px-2 sm:px-10 lg:px-32 py-4 lg:py-8 relative">
	<div class="w-full sm:max-w-lg mx-auto text-center">
		<h2 class="text-2xl md:text-4xl font-bold text-[#04082f]">
            How It Works?
		</h2>
	</div>

	<main class="w-full max-w-7xl mx-auto my-10 sm:mt-20 flex flex-col lg:flex-row items-center lg:justify-between relative">
		<aside class="w-full lg:max-w-2xl pb-40 px-4 md:px-8 flex flex-col items-start">
			<div class="w-full flex items-start border-b border-gray-200 pb-4 px-2 shadow-sm hover:shadow-xl rounded-xl mt-4 lg:px-12">
				<div class="w-20 h-20 flex items-center justify-center">
					<img src={icon} alt="" />
				</div>
				<div class="p-2">
					<h5 class="text-lg font-semibold">Step-1</h5>
					<p class="w-full sm:max-w-xs mt-2">
						Link your domain, create engaging sessions via text, videos, coaching sessions, and
						customize your online school with our custom school builder.
					</p>
				</div>
			</div>

			<div class="w-full flex items-start border-b border-gray-200 pb-4 px-2 shadow-xl hover:shadow-xl rounded-xl mt-4 lg:px-12">
				<div class="w-20 h-20 flex items-center justify-center">
					<img src={icon} class="" alt="" />
				</div>
				<div class="p-2">
					<h5 class="text-lg font-semibold">Step-2</h5>
					<p class="w-full sm:max-w-xs mt-2">
						Use our drag and drop page builder, edit and modify your school - all tailored to your
						needs.
					</p>
				</div>
			</div>

			<div class="w-full flex items-start border-b border-gray-200 pb-4 px-2 shadow-sm hover:shadow-xl rounded-xl mt-4 lg:px-12">
				<div class="w-20 h-20 flex items-center justify-center">
					<img src={icon} alt="" />
				</div>
				<div class="p-2">
					<h5 class="text-lg font-semibold">Step-3</h5>
					<p class="w-full sm:max-w-xs mt-2">
						Track sales and increase your reach. Manage your earnings as you grow on the platform.
					</p>
				</div>
			</div>

			<div class="w-full flex items-start border-b border-gray-200 pb-4 px-2 mt-4 shadow-sm hover:shadow-sm rounded-xl lg:px-12">
				<div class="w-20 h-20 flex items-center justify-center">
					<img src={icon} alt="" />
				</div>
				<div class="p-2">
					<h5 class="text-lg font-semibold">Step-4</h5>
					<p class="w-full sm:max-w-xs mt-2">
						Make real impact with the best online learning experience. Create quizzes, offer
						assessments and certificates, track students progress and follow up with communities and
						memberships.
					</p>
				</div>
			</div>
		</aside>

		<div class="w-full mt-20  py-10">
		<div class="">
			<img
			src={dashboard}
			class="rounded-xl w-[90%] md:w-[50%] absolute right-0 bottom-0 lg:top-10  object-cover object-center"
			alt="dashboard view"
		/>
		</div>
		</div>
	</main>
</section>
