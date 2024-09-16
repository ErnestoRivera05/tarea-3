<script>
	import Navbar from "$lib/components/Navbar.svelte";
	import Footer from "$lib/components/Footer.svelte";
	import jardinera from "$lib/assets/logos/jardinera.png";
	import ensaladacrispy from "$lib/assets/logos/ensaladacrispy.png";
</script>

<Navbar />
<div class="flex flex-col items-center mx-8 mb-8">
	<div>
		<h1 class="text-2xl">Ensalada</h1>
	</div>
</div>

<main class="flex flex-grow min-h-screen mx-8 gap-48 justify-center items-center">
	<!-- Primera columna 01 -->
	<div class="">
		<div class=" flex items-center justify-center">
			<div
				class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
			>
				<a href="/"><img src={jardinera} width="250" height="250" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Ensalada Jardinera
				</h1>
			</div>
		</div>
	</div>
	<!-- Segunda columna 02 -->
	<div class="">
		<div class=" flex items-center justify-center">
			<div
				class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
			>
				<a href="/"><img src={ensaladacrispy} width="250" height="250" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Ensalada con pechuga crispy
				</h1>
			</div>
		</div>
	</div>
</main>

<Footer />
