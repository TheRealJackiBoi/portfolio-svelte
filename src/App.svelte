<script>
	import Router from "./routes/index.svelte"
</script>

<main>
	<Router />
</main>

<style>

	main {
		overflow-y: auto;
	}
	
	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
	
</style>