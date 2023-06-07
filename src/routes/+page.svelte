<script>
	import "../app.css";

    var projects = [
        {
            "title": "Personal Protection Equipment (PPE) Vending App",
            "description": "A showcase of a PPE vending app I created, providing easy access to personal protective equipment.",
            "image": "vending.png",
            "link": "https://github.com/brentvblake/PPE_Vending_App"
        },
        {
            "title": "Evolution of Music Taste",
            "description": "Analysing Popular Music Trends Over Time",
            "image": "songs.png",
            "link": "https://github.com/brentvblake/Popular-Music-Evolution-analysed"
        },
        {
            "title": "WhatsApp Chat Data Visualizer",
            "description": "Transforms exported WhatsApp chat data into insightful visualizations",
            "image": "whatsapp.png",
            "link": "https://github.com/brentvblake/WhatsApp-Chat-Analysis-and-Data-Visuals"
        },
        {
            "title": "Fantasy F1 Data Visualised",
            "description": "This is project 1",
            "image": "f1data.png",
            "link": "https://github.com/brentvblake/f1_2022_fantasy_data_visualized"
        },
        {
            "title": "This Website",
            "description": "A personal website to showcase my projects and skills",
            "image": "site.png",
            "link": "https://github.com/brentvblake/f1_2022_fantasy_data_visualized"
        },
    ];
</script>

<body>

<main class="flex flex-col items-center md:flex-row">
	<section class="w-full md:w-2/5 p-4 text-secondary overflow-y-auto md:fixed top-0">
		<div>
            <div class="mt-10 md:mt-0 p-5 md:p-5 bg-tertiary rounded-lg inline-block">
                <h2 class="text-2xl font-semibold capitalize">Brent Blake</h2>
                <p class="text-lg">Cape Town, South Africa</p>
                <p class="text-lg">github.com/brentvblake</p>
                <p class="text-lg">brent99blake@gmail.com</p>
                <p class="text-lg">linkedin.com/in/brentvblake</p>
                <!-- Add more personal information as needed -->
            </div>
        </div>
        <div class="md:fixed bottom-4 left-1/2 md:left-[20%] md:transform md:-translate-x-1/2 flex items-center space-x-4">
            <img src="/dino.jpeg" alt="Brent" class="w-10 h-10 rounded-full ring-4 ring-purple-500">
            <div class="flex space-x-4">
                <div class="flex items-center space-x-2 text-tertiary bg-secondary p-4 rounded-lg hover:bg-purple-500 transition-all duration-200">
                    <a href="https://github.com/brentvblake" target="_blank" rel="noopener noreferrer" class="flex items-center space-x-2">
                        <img src="/github.svg" alt="GitHub logo" class="w-6 h-6 text-tertiary fill=currentColor">
                        <span>Github</span>
                        <img src="/share.svg" alt="share icon" class="w-6 h-6 text-tertiary fill=currentColor">
                    </a>
                </div>
                <div class="flex items-center space-x-2 text-tertiary bg-secondary p-4 rounded-lg hover:bg-purple-500 transition-all duration-200">
                    <a href="https://linkedin.com/in/brentvblake" target="_blank" rel="noopener noreferrer" class="flex items-center space-x-2">
                        <img src="/linkedin.svg" alt="LinkedIn logo" class="w-6 h-6 text-tertiary fill=currentColor">
                        <span>LinkedIn</span>
                        <img src="/share.svg" alt="share icon" class="w-6 h-6 text-tertiary fill=currentColor">
                    </a>
                </div>
            </div>
        </div>
        
        
	</section>
	
	
	<section class="w-full md:w-3/5 md:ml-[40%] mt-10 md:mt-0 overflow-y-auto">
    <div class="container px-6 py-10 mx-auto">

        <div class="flex justify-items-center">
            <h1 class="text-4xl font-semibold text-center text-secondary bg-tertiary p-2 rounded-lg inline-block mx-auto">Projects
            </h1>
        </div>
        <div class="grid grid-cols-1 gap-8 mt-8 xl:mt-12 xl:gap-12 md:grid-cols-1 xl:grid-cols-1">
            {#each projects as project}
            <div class="overflow-hidden bg-center bg-cover rounded-lg cursor-pointer h-96 group"
                style={"background-image:url("+project.image +")"}>
                <a href={project.link} target="_blank">
                    <div
                        class="flex flex-col justify-center w-full h-full px-8 py-4 transition-opacity duration-700 opacity-0 backdrop-blur-sm bg-gray-800/60 group-hover:opacity-100">
                        <div class="bg-primary/50 p-2 rounded-lg">
                        <h2 class="mt-2 text-xl font-semibold text-secondary capitalize">{project.title}</h2>
                        <p class="mt-2 text-lg tracking-wider text-purple-500 uppercase ">{project.description}</p>
                    </div>
                    </div>
                </a>
            </div>
            {/each}
        </div>
    </div>
</section>
</main>
</body>
