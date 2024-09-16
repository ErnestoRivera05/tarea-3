<script>
	import Navbar from "$lib/components/Navbar.svelte";
	import Footer from "$lib/components/Footer.svelte";
	import papasmc from "$lib/assets/logos/papasmc.png";
	import papasmedianas from "$lib/assets/logos/papasmedianas.png";
	import papasgrandes from "$lib/assets/logos/papasgrandes.png";
	import papasbacon from "$lib/assets/logos/papasbacon.png";
	import papaskid from "$lib/assets/logos/papaskid.png";
</script>

<Navbar />
<div class="flex flex-col items-center mx-8 mb-8">
	<div>
		<h1 class="text-2xl">Acompañamientos</h1>
	</div>
</div>

<main class="flex flex-grow min-h-screen mx-8">
	<!-- Primera columna 01 -->
	<div class="flex flex-col">
		<div class="flex-col flex items-start justify-start gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
			>
				<a href="/"><img src={papasmc} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					MacPapas pequeñas
				</h1>
			</div>
		</div>
		<!-- Segunda columna 01 -->
		<div class="flex-col flex items-center justify-center gap-48">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={papasmedianas} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Macpapas Medianas
				</h1>
			</div>
		</div>
		<!-- Tercera columna 01 -->
		<div class="flex-col flex items-end justify-end gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={papasgrandes} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Macpapas Grandes
				</h1>
			</div>
		</div>
	</div>
	<!-- Primera columna 02  -->
	<div class=" flex flex-col items-end justify-end flex-grow">
		<div class="flex-col flex items-start justify-start gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
			>
				<a href="/"><img src={papasbacon} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Papas Cheddar Bacon
				</h1>
			</div>
		</div>
		<!-- Segunda columna 02	 -->
		<div class="flex-col flex items-end justify-end gap-48 d">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={papaskid} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Papas kid(Cajita feliz)
				</h1>
			</div>
		</div>
	</div>
</main>

<Footer />
