<script context="module">
	export const prerender = true;
</script>

<script>
	import Counter from '$lib/Counter/index.svelte';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<section class="flex f-direction-column justify-content-center align-items-center flex-1 text-center">

	<h1 class="mt-80">
		Welcome to your <br />SvelteKit demo app with CSS from <strong>hgrid</strong>
	</h1>

	<h2 class="h5 font-normal">
		This content is located in <code><mark>src/routes/index.svelte</mark></code>
	</h2>

	<Counter />
</section>
