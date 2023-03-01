<script lang="ts">
	// todo: mouse event updates the gradient slightly
</script>

<!-- Simple portfolio, using tailwind css. Beatuiful reactive dark mode theme. -->

<!-- First, beautiful blurred generated background gradient, a little responsive using mousemove event -->
<div
	class="fixed top-0 left-0 -z-10 h-screen w-screen overflow-hidden bg-gradient-to-r from-blue-900 to-purple-800"
/>

<!-- Second, the main box with the content in the middle of the page. It is going to have a logo on the left, a title and quick about me with 3 buttons directing a more detailed about me -->
<!-- <div
	class="flex flex-col flex-nowrap items-center justify-center w-screen max-w-md mx-auto bg-slate-700 shadow-xl rounded-2xl space-x-4 space-y-4 p-4 align-middle"
> -->
<!-- To center this div, we need to use absolute positioning -->
<div
	class="rounded-2x absolute top-1/2 left-1/2 mx-auto flex w-screen max-w-md -translate-x-1/2 -translate-y-1/2 transform flex-col flex-nowrap items-center justify-center space-x-4 space-y-4 rounded-2xl bg-slate-700 p-4 align-middle shadow-xl"
>
	<!-- Logo -->
	<div class="flex flex-row items-center space-x-2">
		<img
			src="https://avatars.githubusercontent.com/u/42645784"
			class="h-24 w-24 transform rounded-full shadow-md transition duration-500 ease-in-out hover:rotate-[360deg]"
			alt="DuckyBlender's Github Avatar"
		/>
		<h1 class="text-5xl font-bold text-white">DuckyBlender</h1>
	</div>

	<!-- About me -->
	<div class="flex flex-row items-center ">
		<p class="font-normal text-white">
			I am a software developer with a passion for Rust and Python. I love creating discord bots and
			have experience building them using the Python programming language. I am also a member of the
			Moveit organization, which aim to help with public transport delays. I contribute to a variety
			of projects and collaborate with other like-minded developers. In my free time, I enjoy
			staying up-to-date with the latest developments in the world of technology (epecially AI) and
			attending hackathons and programming competitions. Thanks for visiting my profile and I hope
			to collaborate with you on future projects!
		</p>
	</div>

	<!-- Buttons -->
	<div class="flex flex-row items-center space-x-2">
		<a href="/about">
			<button class="rounded-full bg-blue-600 py-2 px-4 font-bold text-white">About </button>
		</a>
		<a href="/projects">
			<button class="rounded-full bg-blue-600 py-2 px-4 font-bold text-white"> Projects </button>
		</a>
		<a href="/contact">
			<button class="rounded-full bg-blue-600 py-2 px-4 font-bold text-white"> Contact </button>
		</a>
        <a href="/">
			<button class="rounded-full bg-blue-800 py-2 px-4 font-bold text-white"> Home </button>
		</a>
	</div>
</div>
