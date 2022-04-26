<template>
  <main>
	<h2>Mis Servicios</h2>

	<Box1 title="Diseño Web" content="Iste illo, nobis rerum asperiores et fugiat ratione enim tenetur recusandae quidem nisi harum tempore sapiente rem dolorum saepe voluptatem unde dolor." />	
	<Box1 title="Aplicaciones Web" content="Iste illo, nobis rerum asperiores et fugiat ratione enim tenetur recusandae quidem nisi harum tempore sapiente rem dolorum saepe voluptatem unde dolor." />	
	<Box1 title="E-Commerce" content="Iste illo, nobis rerum asperiores et fugiat ratione enim tenetur recusandae quidem nisi harum tempore sapiente rem dolorum saepe voluptatem unde dolor." />	
	
	<section>
		<h2>Contacto</h2>
	</section>

	<footer>
		<p>Todos los derechos reservados. Luis Ramos Full Stack</p>
	</footer>
  </main>
</template>
<script lang="ts">
	import { defineComponent } from 'vue';
	import Box1 from './Box1.vue';

	export default defineComponent({
	name: 'BodyContent',
	components: {
		Box1
	},
	props: {
	}
	});
</script>