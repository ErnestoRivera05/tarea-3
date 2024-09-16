<script>
	import Navbar from "$lib/components/Navbar.svelte";
	import Footer from "$lib/components/Footer.svelte";
	import crispy from "$lib/assets/logos/crispy.png";
	import spicy from "$lib/assets/logos/spicy.png";
	import deluxu from "$lib/assets/logos/deluxu.png";
	import mcpollo from "$lib/assets/logos/mcpollo.png";
	import housepollo from "$lib/assets/logos/housepollo.png";
	import bigmac from "$lib/assets/logos/bigmac.png";
	import libra from "$lib/assets/logos/libra.png";
	import bacon from "$lib/assets/logos/bacon.png";
	import triplebacon from "$lib/assets/logos/triplebacon.png";
</script>

<Navbar />
<div class="flex flex-col items-center mx-8 mb-8">
	<div>
		<h1 class="text-2xl">Hamburguesas</h1>
	</div>
</div>
<main class="flex flex-grow min-h-screen mx-8">
	<!-- Primera columna 01 -->
	<div class="flex flex-col">
		<div class="flex-col flex items-start justify-start gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
			>
				<a href="/"><img src={crispy} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Crispy Chicken Classic
				</h1>
			</div>
		</div>
		<!-- Segunda columna 01 -->
		<div class="flex-col flex items-center justify-center gap-48">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={spicy} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Crispy chicken Spicy
				</h1>
			</div>
		</div>
		<!-- Tercera columna 01 -->
		<div class="flex-col flex items-end justify-end gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={deluxu} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Crispy Chicken Deluxu
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
				<a href="/"><img src={mcpollo} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					McPollo
				</h1>
			</div>
		</div>
		<!-- Segunda columna 02	 -->
		<div class="flex-col flex items-center justify-center gap-48 d">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={housepollo} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Club House Pollo Crispy
				</h1>
			</div>
		</div>
		<!-- Tercera columna 02 -->
		<div class="flex-col flex items-end justify-end gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={bigmac} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Big Mac
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
				<a href="/"><img src={libra} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Cuarto de libra con queso
				</h1>
			</div>
		</div>
		<!-- Segunda columna 03 -->
		<div class="flex-col flex items-center justify-end gap-48 d">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={bacon} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Premium Bacon
				</h1>
			</div>
		</div>
		<!-- Tercera columna 03 -->
		<div class="flex-col flex items-end justify-end gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={triplebacon} width="65" height="65" alt="Hamburguesa" /></a>
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
