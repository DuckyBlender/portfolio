<script lang="ts">
	// todo: mouse event updates the gradient slightly
</script>

<!-- Simple portfolio, using tailwind css. Beatuiful reactive dark mode theme. -->

<!-- First, beautiful blurred generated background gradient, a little responsive using mousemove event -->
<div
	class="fixed top-0 left-0 -z-10 h-screen w-screen overflow-hidden bg-gradient-to-r from-blue-900 to-purple-800"
/>

<!-- Second, the main box with the content in the middle of the page. It is going to have a logo on the left, a title and quick about me with 3 buttons directing a more detailed about me -->
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

	<!-- Title -->
	<h1 class="text-5xl font-bold text-white">
		Hello, I'm <span class="text-blue-600">Alan</span>
	</h1>

	<!-- About me -->
	<div class="flex flex-row items-center ">
		<p class="text-2xl font-bold text-white">
			I'm a <span class="rounded-md bg-red-900 p-1"> Rust developer</span>
			from the
			<span class="text-red-500">UK</span>
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
	</div>
</div>
