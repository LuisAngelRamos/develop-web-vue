<template>
	<main class="contenedor sombra">
		<h2>Mis Servicios</h2>

		<div class="servicios">
			<Box1 title="Diseño Web" content="Iste illo, nobis rerum asperiores et fugiat ratione enim tenetur recusandae quidem nisi harum tempore sapiente rem dolorum saepe voluptatem unde dolor." />	
			<Box1 title="Aplicaciones Web" content="Iste illo, nobis rerum asperiores et fugiat ratione enim tenetur recusandae quidem nisi harum tempore sapiente rem dolorum saepe voluptatem unde dolor." />	
			<Box1 title="E-Commerce" content="Iste illo, nobis rerum asperiores et fugiat ratione enim tenetur recusandae quidem nisi harum tempore sapiente rem dolorum saepe voluptatem unde dolor." />	
		</div>
		
		<section>
			<h2>Contacto</h2>
			<form class="formulario">
				<fieldset>
					<legend>Contactanos llenando todos los campos</legend>
					
					<div class="contenedor-campos">
						<div class="campo">
							<label for="">Nombre</label>
							<input class="input-text" type="text" placeholder="Nombre"/>
						</div>

						<div class="campo">
							<label for="">Telefono</label>
							<input class="input-text" type="tel" placeholder="Telefono"/>
						</div>

						<div class="campo">
							<label for="">Correo</label>
							<input class="input-text" type="email" placeholder="Email"/>
						</div>

						<div class="campo">
							<label for="">Mensaje</label>
							<textarea class="input-text" name="" id="" cols="30" rows="10"></textarea>
						</div>
					</div>
					
					<div class="flex alinear-derecha">
						<input class="button w-sm-100" type="submit" value="Enviar" />
					</div>
				</fieldset>
			</form>
		</section>
	</main>
	<footer class="footer">
		<p>Todos los derechos reservados. Luis Ramos Full Stack</p>
	</footer>
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