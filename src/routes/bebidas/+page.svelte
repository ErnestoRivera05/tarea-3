<script>
	import Navbar from "$lib/components/Navbar.svelte";
	import Footer from "$lib/components/Footer.svelte";
	import coca from "$lib/assets/logos/coca.png";
	import cocasinazucar from "$lib/assets/logos/cocasinazucar.png";
	import ginger from "$lib/assets/logos/ginger.png";
	import fanta from "$lib/assets/logos/fanta.png";
	import fuze from "$lib/assets/logos/fuze.png";
	import fuzezero from "$lib/assets/logos/fuzezero.png";
	import americano from "$lib/assets/logos/americano.png";
	import cappuccino from "$lib/assets/logos/cappuccino.png";
	import jugo from "$lib/assets/logos/jugo.png";
</script>

<Navbar />
<div class="flex flex-col items-center mx-8 mb-8">
	<div>
		<h1 class="text-2xl">Bebidas</h1>
	</div>
</div>

<main class="flex flex-grow min-h-screen mx-8">
	<!-- Primera columna 01 -->
	<div class="flex flex-col">
		<div class="flex-col flex items-start justify-start gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
			>
				<a href="/"><img src={coca} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Coca-cola
				</h1>
			</div>
		</div>
		<!-- Segunda columna 01 -->
		<div class="flex-col flex items-center justify-center gap-48">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={cocasinazucar} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Coca-cola sin azucar
				</h1>
			</div>
		</div>
		<!-- Tercera columna 01 -->
		<div class="flex-col flex items-end justify-end gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={ginger} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Ginger ale
				</h1>
			</div>
		</div>
	</div>
	<!-- Primera columna 02  -->
	<div class=" flex flex-col items-center justify-center flex-grow">
		<div class="flex-col flex items-start justify-start gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
			>
				<a href="/"><img src={fanta} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Fanta-naranja
				</h1>
			</div>
		</div>
		<!-- Segunda columna 02	 -->
		<div class="flex-col flex items-center justify-center gap-48 d">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={fuze} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Fuze-tea
				</h1>
			</div>
		</div>
		<!-- Tercera columna 02 -->
		<div class="flex-col flex items-end justify-end gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={fuzezero} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Fuze-tea zero
				</h1>
			</div>
		</div>
	</div>
	<div class="flex flex-col">
		<!-- Primera columna 03 -->
		<div class="flex-col flex items-start justify-start gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
			>
				<a href="/"><img src={americano} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Café americano
				</h1>
			</div>
		</div>
		<!-- Segunda columna 03 -->
		<div class="flex-col flex items-center justify-end gap-48 d">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={cappuccino} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Café cappuccino
				</h1>
			</div>
		</div>
		<!-- Tercera columna 03 -->
		<div class="flex-col flex items-end justify-end gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={jugo} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Triple con Bacon
				</h1>
			</div>
		</div>
	</div>
</main>

<Footer />
