<script>
	import Navbar from "$lib/components/Navbar.svelte";
	import Footer from "$lib/components/Footer.svelte";
	import frappe from "$lib/assets/logos/frappe.png";
	import caramelo from "$lib/assets/logos/caramelo.png";
	import chai from "$lib/assets/logos/chai.png";
	import chocomenta from "$lib/assets/logos/chocomenta.png";
	import mocca from "$lib/assets/logos/mocca.png";
	import oreo from "$lib/assets/logos/oreo.png";
	import fraichai from "$lib/assets/logos/fraichai.png";
	import chocolate from "$lib/assets/logos/chocolate.png";
	import cappuccinomenta from "$lib/assets/logos/cappuccinomenta.png";
</script>

<Navbar />
<div class="flex flex-col items-center mx-8 mb-8">
	<div>
		<h1 class="text-2xl">McCafé</h1>
	</div>
</div>

<main class="flex flex-grow min-h-screen mx-8">
	<!-- Primera columna 01 -->
	<div class="flex flex-col">
		<div class="flex-col flex items-start justify-start gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
			>
				<a href="/"><img src={frappe} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Frappé Cappuccino
				</h1>
			</div>
		</div>
		<!-- Segunda columna 01 -->
		<div class="flex-col flex items-center justify-center gap-48">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={caramelo} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Frappé Caramelo
				</h1>
			</div>
		</div>
		<!-- Tercera columna 01 -->
		<div class="flex-col flex items-end justify-end gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={chai} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Frappé Chai
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
				<a href="/"><img src={chocomenta} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Frappé Chocomenta
				</h1>
			</div>
		</div>
		<!-- Segunda columna 02	 -->
		<div class="flex-col flex items-center justify-center gap-48 d">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={mocca} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Frappé Mocca
				</h1>
			</div>
		</div>
		<!-- Tercera columna 02 -->
		<div class="flex-col flex items-end justify-end gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={oreo} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Frappé Oreo
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
				<a href="/"><img src={fraichai} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Chaitea
				</h1>
			</div>
		</div>
		<!-- Segunda columna 03 -->
		<div class="flex-col flex items-center justify-end gap-48 d">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={chocolate} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Chocolate
				</h1>
			</div>
		</div>
		<!-- Tercera columna 03 -->
		<div class="flex-col flex items-end justify-end gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={cappuccinomenta} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					Cappuccino Menta
				</h1>
			</div>
		</div>
	</div>
</main>

<Footer />
