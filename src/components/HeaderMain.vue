<template>
  <div>
	<header>
		<h1 class="titulo">Luis Angel Ramos Mejia <span>Freelancer</span></h1>
	</header>
	<div class="nav-bg">
		<nav class="navegacion-principal contenedor">
			<a href="#">Inicio</a>
			<a href="#">Sobre Mi</a>
			<a href="#">Clientes</a>
			<a href="#">Contacto</a>
		</nav>
	</div>


	<section class="hero">
		<div class="contenido-hero">
			<h2>Diseño y Desarrollo Web <span>Freelancer</span></h2>
			<div class="ubicacion">
				<svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-map-pin" width="88" height="88" viewBox="0 0 24 24" stroke-width="1.5" stroke="#FFC107" fill="none" stroke-linecap="round" stroke-linejoin="round">
					<path stroke="none" d="M0 0h24v24H0z" fill="none"/>
					<circle cx="12" cy="11" r="3" />
					<path d="M17.657 16.657l-4.243 4.243a2 2 0 0 1 -2.827 0l-4.244 -4.243a8 8 0 1 1 11.314 0z" />
				</svg>
				<p>Zempoala, Hidalgo</p>
			</div>
			<a href="#" class="button">Contactar</a>
		</div>
		
	</section>

  </div>
</template>

<script lang="ts">
	import { defineComponent } from 'vue';

	export default defineComponent({
		name: 'HeaderMain',
		props: {
		}
	});
</script>