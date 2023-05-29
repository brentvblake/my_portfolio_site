<script>
	import "../app.css";

    var projects = [
        {
            "title": "Fantasy F1 Data Visualised",
            "description": "This is project 1",
            "image": "f1data.png",
            "link": "https://github.com/brentvblake/f1_2022_fantasy_data_visualized"
        },
    ];

    function allProjects(){
        var projectList = [];
        for (var i = 0; i < projects.length; i++) {
            projectList.push(
                <div class="overflow-hidden bg-center bg-cover rounded-lg cursor-pointer h-96 group"
                    style={"background-image:url("+projects[i].image +")"}>
                    <a href={projects[i].link} target="_blank">
                        <div
                            class="flex flex-col justify-center w-full h-full px-8 py-4 transition-opacity duration-700 opacity-0 backdrop-blur-sm bg-gray-800/60 group-hover:opacity-100">
                            <h2 class="mt-4 text-xl font-semibold text-white capitalize">{projects[i].title}</h2>
                            <p class="mt-2 text-lg tracking-wider text-purple-500 uppercase ">{projects[i].description}</p>
                        </div>
                    </a>
                </div>
            )
        }
        return projectList;
    }
</script>

<body class="bg-radial-gradient">
    

<main class="flex flex-col items-center md:flex-row">
	<section class="w-full md:w-2/5 p-4 text-white h-screen overflow-y-auto md:fixed top-0">
		<div class="mt-10 md:mt-0 p-10 md:p-10">
			<h2 class="text-2xl font-semibold capitalize">Brent Blake</h2>
			<p class="text-lg">Walvis Bay, Namibia</p>
			<p class="text-lg">github.com/brentvblake</p>
			<p class="text-lg">brent99blake@gmail.com</p>
			<p class="text-lg">linkedin.com/in/brentvblake</p>
			<!-- Add more personal information as needed -->
		</div>
        <div class="md:fixed bottom-4 left-1/2 md:left-[20%] md:transform md:-translate-x-1/2 flex items-center space-x-4">
            <img src="/dino.jpeg" alt="Brent" class="w-10 h-10 rounded-full ring-4 ring-purple-500">
            <div class="flex space-x-4">
                <div class="flex items-center space-x-2 text-white bg-gray-800 p-4 rounded-lg hover:bg-purple-500 transition-all duration-200">
                    <a href="https://github.com/brentvblake" target="_blank" rel="noopener noreferrer" class="flex items-center space-x-2">
                        <img src="/github.svg" alt="GitHub logo" class="w-6 h-6 text-white fill=currentColor">
                        <span>Github</span>
                        <img src="/share.svg" alt="share icon" class="w-6 h-6 text-white fill=currentColor">
                    </a>
                </div>
                <div class="flex items-center space-x-2 text-white bg-gray-800 p-4 rounded-lg hover:bg-purple-500 transition-all duration-200">
                    <a href="https://linkedin.com/in/brentvblake" target="_blank" rel="noopener noreferrer" class="flex items-center space-x-2">
                        <img src="/linkedin.svg" alt="LinkedIn logo" class="w-6 h-6 text-white fill=currentColor">
                        <span>LinkedIn</span>
                        <img src="/share.svg" alt="share icon" class="w-6 h-6 text-white fill=currentColor">
                    </a>
                </div>
            </div>
        </div>
        
        
	</section>
	
	
	<section class="w-full md:w-3/5 md:ml-[40%] mt-10 md:mt-0">
    <div class="container px-6 py-10 mx-auto">
        <h1 class="text-2xl font-semibold text-center text-white">Portfolio
        </h1>

        <p class="mt-4 text-center text-gray-300">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nostrum quam voluptatibus
        </p>


        <div class="grid grid-cols-1 gap-8 mt-8 xl:mt-12 xl:gap-12 md:grid-cols-1 xl:grid-cols-1">
            <div class="overflow-hidden bg-center bg-cover rounded-lg cursor-pointer h-96 group"
                style={"background-image:url("+projects[0].image +")"}>
                <a href={projects[0].link} target="_blank">
                    <div
                        class="flex flex-col justify-center w-full h-full px-8 py-4 transition-opacity duration-700 opacity-0 backdrop-blur-sm bg-gray-800/60 group-hover:opacity-100">
                        <h2 class="mt-4 text-xl font-semibold text-white capitalize">{projects[0].title}</h2>
                        <p class="mt-2 text-lg tracking-wider text-purple-500 uppercase ">{projects[0].description}</p>
                    </div>
                </a>
            </div>
        </div>
    </div>
</section>
</main>
</body>
