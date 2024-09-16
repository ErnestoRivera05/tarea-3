<script>
	import Navbar from "$lib/components/Navbar.svelte";
	import Footer from "$lib/components/Footer.svelte";
	import nuggets from "$lib/assets/logos/nuggets.png";
	import pieza from "$lib/assets/logos/pieza.png";
	import hamburguesa_1 from "$lib/assets/logos/hamburguesa_1.png";
</script>

<Navbar />
<div class="flex flex-col items-center mx-8 mb-8">
	<div>
		<h1 class="text-2xl">Acompañamientos</h1>
	</div>
</div>

<main class="flex flex-grow min-h-screen mx-8">
	<!-- Primera columna 01 -->
	<div class="flex justify-center items-center gap-48">
		<div class="flex items-start justify-start gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
			>
				<a href="/"><img src={nuggets} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Nuggets 4 unidades(Cajita feliz)
				</h1>
			</div>
		</div>
		<!-- Segunda columna 01 -->
		<div class="flex items-center justify-center gap-48">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={pieza} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Pieza de pollo(Cajita feliz)
				</h1>
			</div>
		</div>
		<!-- Tercera columna 01 -->
		<div class="flex items-end justify-end gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={hamburguesa_1} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Hamburguesa(Cajita feliz)
				</h1>
			</div>
		</div>
	</div>
</main>

<Footer />
