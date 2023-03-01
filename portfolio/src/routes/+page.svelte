<script lang="ts">
</script>

<!-- Simple portfolio, using tailwind css. Beatuiful reactive dark mode theme. -->

<!-- First, beautiful blurred generated background gradient, a little responsive using mousemove event -->
<div
	class="bg-gradient-to-r from-blue-900 to-purple-800 h-screen w-screen fixed top-0 left-0 -z-10"
/>

<!-- Second, the main box with the content in the middle of the page -->
<!-- <div class="flex flex-col h-screen justify-center items-center flex-nowrap font-lexend"> -->
<!-- To set max width to half of the screen -->
<div
	class="flex flex-col h-screen justify-center items-center flex-nowrap font-lexend max-w-screen-md mx-auto"
>
	<div
		class="bg-slate-800 rounded-xl shadow-2xl flex items-center space-x-4 p-6 hover:scale-105 transform transition duration-300 ease-in-out cursor-pointer"
	>
		<!-- The avatar image -->
		<!-- <img
			class="h-128 w-128 rounded-3xl flex-shrink-0"
			src="https://avatars.githubusercontent.com/u/42645784"
			alt="DuckyBlender Github Avatar"
		/> -->
		<!-- On avatar click, go to github profile -->
		<a href="https://google.com" target="_blank" rel="noreferrer">
			<!-- <img
				class="rounded-3xl flex-shrink-0 hover:rotate-1 transform transition duration-300 ease-in-out w-48 h-48"
				src="https://avatars.githubusercontent.com/u/42645784"
				alt="DuckyBlender Github Avatar"
			/> -->
			<!-- To make the image not squished, use object-fit: cover -->
			<img
				class="rounded-3xl flex-shrink-0 hover:rotate-1 transform transition duration-300 ease-in-out w-48 h-48 object-cover"
				src="https://avatars.githubusercontent.com/u/42645784"
				alt="DuckyBlender Github Avatar"
			/>
		</a>
		<div>
			<div class="flex flex-col">
				<h1 class="text-6xl font-bold text-slate-100 mb-5">DuckyBlender</h1>
				<h2
					class="text-2xl text-slate-300 hover:text-slate-100 transition duration-300 ease-in-out"
				>
					Full Stack Developer
				</h2>
				<h3 class="text-m text-slate-300 hover:text-slate-100 transition duration-300 ease-in-out">
					I am a software developer with a passion for Rust and Python. I love creating discord bots
					and have experience building them using the Python programming language. I am also a
					member of the Moveit organization, which aim to help with public transport delays. I
					contribute to a variety of projects and collaborate with other like-minded developers. In
					my free time, I enjoy staying up-to-date with the latest developments in the world of
					technology (epecially AI) and attending hackathons and programming competitions. Thanks
					for visiting my profile and I hope to collaborate with you on future projects!
				</h3>
			</div>
		</div>
	</div>
</div>
