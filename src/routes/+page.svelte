<script>
	import "../app.css";
</script>

<body class="bg-radial-gradient">
    

<main class="flex">
	<section class="w-2/5 flex-1 p-4 text-white fixed h-screen overflow-y-auto">
		<div class="p-10">
			<h2 class="text-2xl font-semibold capitalize">Brent Blake</h2>
			<p class="text-lg">Walvis Bay, Namibia</p>
			<p class="text-lg">github.com/brentvblake</p>
			<p class="text-lg">brent99blake@gmail.com</p>
			<p class="text-lg">linkedin.com/in/brentvblake</p>
			<!-- Add more personal information as needed -->
		</div>
        <div class = "fixed bottom-4 left-4 bg-gray-800 p-4 rounded-lg">
            <div class="flex items-center space-x-4">
                <img src="/dino.jpeg" alt="Brent" class="w-10 h-10 rounded-full ring-4 ring-purple-500">
            
                <a href="https://github.com/brentvblake" target="_blank" rel="noopener noreferrer" class="flex items-center space-x-2 text-white hover:text-blue-400">
                    <img src="/github.svg" alt="GitHub logo" class="w-10 h-10 text-white fill=currentColor">
                    <span>Github</span>
                </a>
            
                <a href="https://linkedin.com/in/brentvblake" target="_blank" rel="noopener noreferrer" class="flex items-center space-x-2 text-white hover:text-blue-400">
                    <img src="/linkedin.svg" alt="LinkedIn logo" class="w-10 h-10 text-white fill-currentColor ">
                    <span>LinkedIn</span>
                </a>
            </div>
        </div>
	</section>
	
	
	<section class="w-3/5 ml-[40%]">
    <div class="container px-6 py-10 mx-auto">
        <h1 class="text-2xl font-semibold text-center text-white">Portfolio
        </h1>

        <p class="mt-4 text-center text-gray-300">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nostrum quam voluptatibus
        </p>


        <div class="grid grid-cols-1 gap-8 mt-8 xl:mt-12 xl:gap-12 md:grid-cols-1 xl:grid-cols-1">
            <div class="overflow-hidden bg-cover rounded-lg cursor-pointer h-96 group"
                style="background-image:url('https://images.unsplash.com/photo-1621111848501-8d3634f82336?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1565&q=80')">
                <div
                    class="flex flex-col justify-center w-full h-full px-8 py-4 transition-opacity duration-700 opacity-0 backdrop-blur-sm bg-gray-800/60 group-hover:opacity-100">
                    <h2 class="mt-4 text-xl font-semibold text-white capitalize">Best website collections</h2>
                    <p class="mt-2 text-lg tracking-wider text-blue-400 uppercase ">Website</p>
                </div>
            </div>

            <div class="overflow-hidden bg-cover rounded-lg cursor-pointer h-96 group"
                style="background-image:url('https://images.unsplash.com/photo-1621609764180-2ca554a9d6f2?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=764&q=80')">
                <div
                    class="flex flex-col justify-center w-full h-full px-8 py-4 transition-opacity duration-700 opacity-0 backdrop-blur-sm bg-gray-800/60 group-hover:opacity-100">
                    <h2 class="mt-4 text-xl font-semibold text-white capitalize">Block of Ui kit collections</h2>
                    <p class="mt-2 text-lg tracking-wider text-blue-400 uppercase ">Ui kit</p>
                </div>
            </div>

            <div class="overflow-hidden bg-cover rounded-lg cursor-pointer h-96 group"
                style="background-image:url('https://images.unsplash.com/photo-1531403009284-440f080d1e12?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80')">
                <div
                    class="flex flex-col justify-center w-full h-full px-8 py-4 transition-opacity duration-700 opacity-0 backdrop-blur-sm bg-gray-800/60 group-hover:opacity-100">
                    <h2 class="mt-4 text-xl font-semibold text-white capitalize">Ton’s of mobile mockup</h2>
                    <p class="mt-2 text-lg tracking-wider text-blue-400 uppercase ">Mockups</p>
                </div>
            </div>
        </div>
    </div>
</section>
</main>
</body>
