



<script lang="js">
    const features = [
        {
            title: "Email marketing",
            desc: " Create automations, send to, and receive emails from your students and build a strong community with Courselify's email new visual builder",
                    
        },

        {
            title: "Email marketing",
            desc: " Create automations, send to, and receive emails from your students and build a strong community with Courselify's email new visual builder",
                    
        },
        {
            title: "Email marketing",
            desc: " Create automations, send to, and receive emails from your students and build a strong community with Courselify's email new visual builder",
                    
        },
        {
            title: "Email marketing",
            desc: " Create automations, send to, and receive emails from your students and build a strong community with Courselify's email new visual builder",
                    
        },
        {
            title: "Email marketing",
            desc: " Create automations, send to, and receive emails from your students and build a strong community with Courselify's email new visual builder",
                    
        },
        {
            title: "Email marketing",
            desc: " Create automations, send to, and receive emails from your students and build a strong community with Courselify's email new visual builder",
                    
        },
        {
            title: "Email marketing",
            desc: " Create automations, send to, and receive emails from your students and build a strong community with Courselify's email new visual builder",
                    
        },
        {
            title: "Email marketing",
            desc: " Create automations, send to, and receive emails from your students and build a strong community with Courselify's email new visual builder",
                    
        },
    ]
</script>



<section class="w-full p-6 md:p-12">
	
    <div class=" animate__animated animate__bounceInLeft text-center pt-10">
		<h2 class="text-2xl md:text-4xl font-bold text-[#04082f]">Features</h2>
	</div>
	<main class="w-full max-w-7xl mx-auto bg-gray-50 py-10 md:py-24 mt-6  rounded-2xl flex flex-wrap justify-around gap-5 md:gap-10">
		


        {#each features as feature}

        <div class="w-full sm:w-[430px] bg-orange-100 custom-shadow flex gap-6 items-center p-2 rounded-xl shadow-sm hover:shadow-xl">
            <div class="border-l-4 h-32 border-orange-400 flex items-center justify-center">
                <span class="px-2 h-full"></span>
                <span><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 9v.906a2.25 2.25 0 0 1-1.183 1.981l-6.478 3.488M2.25 9v.906a2.25 2.25 0 0 0 1.183 1.981l6.478 3.488m8.839 2.51-4.66-2.51m0 0-1.023-.55a2.25 2.25 0 0 0-2.134 0l-1.022.55m0 0-4.661 2.51m16.5 1.615a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V8.844a2.25 2.25 0 0 1 1.183-1.981l7.5-4.039a2.25 2.25 0 0 1 2.134 0l7.5 4.039a2.25 2.25 0 0 1 1.183 1.98V19.5Z" />
                  </svg>
                  </span>
            </div>
            <div>
                <h5 class="text-lg text-[#04082f] font-semibold">{feature.title}</h5>
                <p class="py-2">
                   {feature.desc}
                </p>
            </div>
        </div>
        {/each}


	</main>
</section>
