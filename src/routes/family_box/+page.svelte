<script>
	import Navbar from "$lib/components/Navbar.svelte";
	import Footer from "$lib/components/Footer.svelte";
	import familybox from "$lib/assets/logos/familybox.png";
</script>

<Navbar />
<div class="flex flex-col items-center mx-8 mb-8">
	<div>
		<h1 class="text-2xl">Family Box</h1>
	</div>
</div>

<main class="flex flex-grow min-h-screen mx-8 justify-center items-center">
	<!-- Primera columna 01 -->
	<div class="">
		<div class=" flex items-center justify-center">
			<div
				class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
			>
				<a href="/"><img src={familybox} width="250" height="250" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Family Box
				</h1>
			</div>
		</div>
	</div>
</main>

<Footer />
