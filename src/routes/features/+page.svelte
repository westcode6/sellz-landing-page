

<script>
	import Branded from "../../components/Branded.svelte";
import Features from "../../components/Features.svelte";
	import Feedbacks from "../../components/Feedbacks.svelte";
	import Footer from "../../components/Footer.svelte";
	import HowItWorks from "../../components/HowItWorks.svelte";
	import Navbar from "../../components/Navbar.svelte";
	import Share from "../../components/Share.svelte";
	import StillNeedHelp from "../../components/StillNeedHelp.svelte";

 import featureBackground from "$lib/assets/features.png"
</script>

<Navbar />
<!-- HERO SECTION -->
<section class="">
	<div class="w-full bg-[#e7eafd]">
		<div class="w-full max-w-7xl mx-auto bg-[#E7EAFD] py-6">
			<div class="w-full max-w-lg mx-auto text-center pt-1 px-6">
				<h1 class="text-2xl md:text-4xl font-bold text-[#04082f]">Learn How Courselify Can Drive You Sales</h1>
				<p class="py-4 text-base md:text-xl font-medium text-gray-700">Share and sell your ideas the smarter way in few minutes
					all with all these features for FREE</p>
	
				
			</div>
		</div>
		<div class="w-full shadow-md">
			<img src={featureBackground} class="w-full max-w-7xl mx-auto" alt="">
		</div>
	</div>
	
</section>
<Features />
<HowItWorks />
<Feedbacks />
<StillNeedHelp />
<br/>
<Share />
<Branded />
<Footer />