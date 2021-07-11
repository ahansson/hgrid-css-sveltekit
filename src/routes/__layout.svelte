<script>
	import Header from '$lib/Header/index.svelte';
	import '../app.scss';
</script>

<Header />

<main class="flex flex-1 f-direction-column padding-10 width-100pct margin-0-auto box-sizing-border-box">
	<slot />
</main>

<footer class="text-center">
	<p>visit <a href="https://kit.svelte.dev" target="_blank" rel="noopener">kit.svelte.dev</a> to learn <code>SvelteKit</code></p>
	<p>visit <a href="https://hgrid.io" target="_blank" rel="noopener">hgrid.io</a> to get going with <code>hgrid-css</code></p>
</footer>

<style>
	@media (min-width: 480px) {
		footer {
			padding: 4rem 0;
		}
	}
</style>
