<script>
	import Navbar from '../../components/Navbar.svelte';

    import smiles from "$lib/assets/laugh.png"
	import Share from '../../components/Share.svelte';
	import Branded from '../../components/Branded.svelte';
	import Footer from '../../components/Footer.svelte';
</script>

<Navbar />
<section class="bg-blue-100 p-12">
	<div class="p-12 w-full max-w-xl mx-auto">
		<div class="flex flex-col items-center justify-center">
			<h1 class="text-2xl md:text-4xl font-bold text-[#04082f]">Contact Us</h1>
			<p class="text-base sm:text-xl mt-4">Have any quetions?</p>
			<p class="text-base sm:text-xl">We'd love to hear from you.</p>
		</div>
	</div>
</section>

<!-- Contact Support and Contact Sales -->
<section class="p-6 md:p-12">
	<div class="p-6 md:p-12 w-full max-w-7xl mx-auto flex flex-col sm:flex-row items-start justify-between gap-10">
		<div
			class="w-full max-w-sm flex flex-col items-center justify-center text-center border-t-2 bg-orange-50 border-orange-400 py-10 px-10"
		>
			<h2 class="text-[#04082f] text-xl font-semibold">Contact Support</h2>
			<p class="py-4 text-base">
				Do you have general enquires or need support? Please send us an email or click the button
				below
			</p>
			<button
				class="w-fit mt-6 bg-orange-400 rounded-full text-white text-sm font-semibold px-6 py-2"
				>Visit Support Page</button
			>

			<span class="mt-4 text-orange-400 font-semibold">SUBMIT A REQUEST</span>
		</div>

		<div
			class="w-full max-w-sm flex flex-col items-center justify-center text-center border-t-2 bg-orange-50 border-orange-400 py-10 px-10"
		>
			<h2 class="text-[#04082f] text-xl font-semibold">Contact Sales</h2>
			<p class="py-4 text-base">
				We look forward to working with you. Get in touch with our sales team to see how we can work
				together
			</p>
			<button
				class="w-fit mt-6 border-2 border-orange-400 text-orange-400 hover:bg-orange-400 rounded-full hover:text-white text-sm font-semibold px-6 py-2"
				>Contact Sales</button
			>
		</div>
	</div>
</section>

<!-- General Communication  -->
<section class="p-6 md:p-12">
    
<div 
class="p-12 w-full max-w-7xl mx-auto flex flex-col sm:flex-row items-center justify-between"
>
<div class="w-full max-w-sm flex flex-col items-center justify-center text-center  py-10 px-10">
    <h3 class="text-[#04082f] text-xl font-semibold">Contact Support</h3>
    <p class="py-4 text-base">For general queries, including partnership opportunities, please email info@Sellz.com</p>
</div>

<div class="w-full max-w-sm flex flex-col items-center justify-center text-center border-l border-r border-orange-400  py-10 px-10">
   
</div>

<div class="w-full max-w-sm flex flex-col items-center justify-center text-center py-10 px-10">
    <h3 class="text-[#04082f] text-xl font-semibold">Contact Sales</h3>
    <p class="py-4 text-base">
        Reporting fraud is important to prevent others from falling victims, discovered a fraud? Email
        policy@Sellz.com
    </p>
</div>
</div>

</section>


<!-- Need a quick response -->
<section class="p-6 md:p-12 bg-[#04082f]">
    <div class="w-full max-w-7xl mx-auto flex flex-col sm:flex-row gap-10 md:gap-5 justify-between items-center ">
        <div class="w-full max-w-lg">
                <img src={smiles} class="w-full object-center object-cover" alt="smiles">
        </div>

        <div>
            <h1 class="text-white text-2xl sm:text-4xl">Need a quick response?</h1>
            <h4 class="mt-4 text-gray-100">The Sellz Documentation Has</h4>

            <div class="my-4">
                <div class="flex items-center text-cyan-400 gap-2 py-4">
                    <span><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                      </svg>
                      </span>
                    <p>Step-by-step Tutorials</p>
                </div>

                <div class="flex items-center text-cyan-400 hover:underline hover:text-cyan-500 gap-2 py-4">
                    <span><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                      </svg>
                      </span>
                    <p>How-to Video Guides</p>
                </div>

                <div class="flex items-center text-cyan-400 hover:underline hover:text-cyan-500 gap-2 py-4">
                    <span><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                      </svg>
                      </span>
                    <p>Frequently Asked Questions</p>
                </div>

                <div class="mt-10">
                    <a href="/doc" class="text-base sm:text-lg text-orange-400">Search Documentation <span></span></a>
                </div>
        </div>
    </div>
</section>

<!-- Ready to Share your knowledge -->

<section class="px-6 md:p-12">
    <Share />
</section>

<Branded />

<Footer />

