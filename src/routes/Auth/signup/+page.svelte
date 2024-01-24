<script>
    import logo from "$lib/assets/sellz-logo.png"
</script>
<section>
    <nav class="p-4 border-b border-gray-400 flex items-center justify-between">
        <img src={logo} class="w-24 h-6 object-cover object-center" alt="sellz-logo">


        <div>
            <a href="/" class="text-base text-gray-600 hover:underline font-medium">Sign In to Sellz</a>
        </div>
    </nav>


    <form action="POST">
        <div>
            <div class="border border-gray-400">
                <span><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                  </svg>
                  </span>
                <input type="text" class="w-full border-none ">
            </div>
        </div>
    </form>
</section>