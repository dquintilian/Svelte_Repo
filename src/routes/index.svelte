<script context="module">
	export const prerender = true;
</script>

<script>
	
	import IndexNavbar from "../Navbars/IndexNavbar.svelte";
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<section>
	
		<div class="welcome">
			<picture>
				<source srcset="svelte-welcome.webp" type="image/webp" />
				<!-- <img src="svelte-welcome.png" alt="Welcome" /> -->
			</picture>

			<p class="text-center font-sans mt-20 p-10 text-cyan-500 text-6xl font-semibold">
				Toy Rocket Ship 
			</p>
		</div>
<div class="text-center">
	<p class="p-5 font-sans font-medium text-2xl">
		The website for product people
	</p>

	<!-- <h2>
		try editing <strong>src/routes/index.svelte</strong>
	</h2> -->
</div>
	<IndexNavbar />
</section>

<style>
	
</style>
