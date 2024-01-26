<script>
    import 'animate.css';

 import smile from "$lib/assets/laugh.png"
	import Navbar from '../../components/Navbar.svelte';

</script>

<Navbar />
<section class="w-full bg-blue-100  p-12">
    

    <div class="w-full  max-w-7xl mx-auto">
        <div class="flex flex-col md:flex-row justify-between">
           <div class="md:w-1/2 max-w-lg mx-auto flex flex-col justify-center">
            <h4 class="text-base text-[#04082f] flex items-center gap-4 font-semibold">Our #1 Goal <span class=" block w-40 border-b-4 border-orange-400"></span></h4>
              <h1 class="my-6 md:text-5xl text-5xl text-[#04082f] capitalize font-black">To make teaching and learning online easy for everyone</h1>
              <p class="text-base md:text-xl mt-6 text-gray-400"><a href="/signup" class="text-base text-orange-400 font-semibold flex gap-2">Get Started for FREE <span><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3" />
              </svg>
              </span></a></p>
             
           </div>
           <div  class="w-full md:w-1/2 mx-auto flex items-center justify-center lg:justify-end">
              <div class="">
                 <div class="w-full shadow-2xl max-w-lg mx-auto z-10 rounded-lg  p-4 mt-6 md:mt-0 mr-4 lg:ml-4">
                    <img alt="card img" class="object-cover object-center  " src={smile}> 
                    <!-- <div class="text-2xl p-10 bg-white"><img alt="quote" class="float-left mr-1" src="https://assets-global.website-files.com/5b5a66e9f3166b36708705fa/5cf8fb1f994fb7168d0d66fb_quote-intro.svg"> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam</div> -->
                 </div>
              </div>
           </div>
        </div>
     </div>
    </section>