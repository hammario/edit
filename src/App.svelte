<script>
	import TailwindCSS from "./TailwindCSS.svelte";
	export let name;
</script>

<main>
	<h1 class="">Hello {name}!</h1>
	<p class="text-red-500">Test tets test test</p>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<TailwindCSS />