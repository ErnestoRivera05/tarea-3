<script>
	import Navbar from "$lib/components/Navbar.svelte";
	import Footer from "$lib/components/Footer.svelte";
	import nuggets from "$lib/assets/logos/nuggets.png";
	import macnuggets_10 from "$lib/assets/logos/macnuggets_10.png";
	import pollocrispy from "$lib/assets/logos/pollocrispy.png";
	import pollo3pz from "$lib/assets/logos/pollo3pz.png";
	import papaskid from "$lib/assets/logos/papaskid.png";
	import pollo1pz from "$lib/assets/logos/pollo1pz.png";
</script>

<Navbar />
<div class="flex flex-col items-center mx-8 mb-8">
	<div>
		<h1 class="text-2xl">Pollo</h1>
	</div>
</div>

<main class="flex flex-grow min-h-screen mx-8">
	<!-- Primera columna 01 -->
	<div class="flex flex-col">
		<div class="flex-col flex items-start justify-start gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
			>
				<a href="/"><img src={nuggets} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					MacNuggets
				</h1>
			</div>
		</div>
		<!-- Segunda columna 01 -->
		<div class="flex-col flex items-center justify-center gap-48">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={macnuggets_10} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					macnuggets 10 pz
				</h1>
			</div>
		</div>
		<!-- Tercera columna 01 -->
		<div class="flex-col flex items-end justify-end gap-48 flex-grow">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={pollocrispy} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					2 pz. Pollo McCrispy
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
				<a href="/"><img src={pollo3pz} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					3 pz. Pollo McCrispy
				</h1>
			</div>
		</div>
		<!-- Segunda columna 02	 -->
		<div class="flex-col flex items-end justify-end gap-48 d">
			<div
				class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
			>
				<a href="/"><img src={pollo1pz} width="65" height="65" alt="Hamburguesa" /></a>
				<h1
					class="border-orange-300 border-2 rounded-full p-2
				shadow-md hover:shadow-lime-500 transition-all duration-1000"
				>
					1 pz. Pollo McCrispy
				</h1>
			</div>
		</div>
	</div>
</main>

<Footer />
