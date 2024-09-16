<script>
	import Hamburguesa from "$lib/assets/logos/hamburguesa.png";
	import bebidas from "$lib/assets/logos/bebidas.png";
	import Acompañamientos from "$lib/assets/logos/acompañamientos.png";
	import Pollo from "$lib/assets/logos/Pollo.png";
	import cajita from "$lib/assets/logos/cajita.png";
	import family from "$lib/assets/logos/family.png";
	import ensaladas from "$lib/assets/logos/ensaladas.png";
	import Mccafe from "$lib/assets/logos/Mccafe.png";
	import helado from "$lib/assets/logos/helado.png";
</script>

<div class="flex flex-col items-center mx-8 mb-8">
	<div class="">
		<h1 class="text-2xl">Productos</h1>
	</div>
</div>
<!-- Primera columna -->
<div class="flex mx-8">
	<div class="flex-col flex items-start justify-start gap-48 flex-grow">
		<div
			class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
		>
			<a href="/"><img src={Hamburguesa} width="65" height="65" alt="Hamburguesa" /></a>
			<a href="/hamburguesas"
				><button
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000">Hamburguesas</button
				></a
			>
		</div>
	</div>
	<!-- Segunda columna -->
	<div class="flex-col flex items-center justify-center gap-48 d">
		<div
			class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
		>
			<a href="/"><img src={bebidas} width="65" height="65" alt="Hamburguesa" /></a>
			<a href="/bebidas"
				><button
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000">Bebidas</button
				></a
			>
		</div>
	</div>
	<!-- Tercera columna -->
	<div class="flex-col flex items-end justify-end gap-48 flex-grow">
		<div
			class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
		>
			<a href="/"><img src={Acompañamientos} width="65" height="65" alt="Hamburguesa" /></a>
			<a href="/acompañamientos"
				><button
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000">Acompañamientos</button
				></a
			>
		</div>
	</div>
</div>

<!-- Primera columna -->
<div class="flex mx-8 my-48">
	<div class="flex-col flex items-start justify-start gap-48 flex-grow">
		<div
			class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
		>
			<a href="/"><img src={cajita} width="65" height="65" alt="Hamburguesa" /></a>
			<a href="/cajita_feliz"
				><button
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000">Cajita feliz</button
				></a
			>
		</div>
	</div>
	<!-- Segunda columna -->
	<div class="flex-col flex items-center justify-center gap-48 d">
		<div
			class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
		>
			<a href="/"><img src={family} width="65" height="65" alt="Hamburguesa" /></a>
			<a href="/family_box"
				><button
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000">Family box</button
				></a
			>
		</div>
	</div>
	<!-- Tercera columna -->
	<div class="flex-col flex items-end justify-end gap-48 flex-grow">
		<div
			class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
		>
			<a href="/"><img src={ensaladas} width="65" height="65" alt="Hamburguesa" /></a>
			<a href="/ensaladas"
				><button
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000">Ensaladas</button
				></a
			>
		</div>
	</div>
</div>

<!-- Primera columna -->
<div class="flex mx-8">
	<div class="flex-col flex items-start justify-start gap-48 flex-grow">
		<div
			class="flex items-center gap-4 border-2 border-amber-700 rounded-3xl p-4 shadow-md shadow-black"
		>
			<a href="/"><img src={Pollo} width="65" height="65" alt="Hamburguesa" /></a>
			<a href="/pollo"
				><button
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000">Pollo</button
				></a
			>
		</div>
	</div>
	<!-- Segunda columna -->
	<div class="flex-col flex items-center justify-center gap-48 d">
		<div
			class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
		>
			<a href="/"><img src={Mccafe} width="65" height="65" alt="Hamburguesa" /></a>
			<a href="/mccafe"
				><button
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000">McCafé</button
				></a
			>
		</div>
	</div>
	<!-- Tercera columna -->
	<div class="flex-col flex items-end justify-end gap-48 flex-grow">
		<div
			class="flex items-center gap-4 border-2 p-4 border-amber-700 rounded-3xl shadow-md shadow-black"
		>
			<a href="/"><img src={helado} width="65" height="65" alt="Hamburguesa" /></a>
			<a href="/postres"
				><button
					class="border-orange-300 border-2 rounded-full p-2
			shadow-md hover:shadow-lime-500 transition-all duration-1000">Postres</button
				></a
			>
		</div>
	</div>
</div>
