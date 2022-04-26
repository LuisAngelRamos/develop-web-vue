<template>
    <section>
        <h3>{{ title }}</h3>
        <p>{{ content }}</p>
    </section>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

	export default defineComponent({
		name: 'HeaderMain',
		props: {
            title: String,
            content: String
		}
	});
</script>
