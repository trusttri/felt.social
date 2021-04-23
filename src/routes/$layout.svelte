<script>
	import '../app.css';
</script>

<main>
	<slot />
</main>

<style>
	main {
		position: relative;
		max-width: 980px;
		padding: 2em;
		margin: 0 auto;
		display: flex;
		flex-direction: column;
		align-items: center;
	}
</style>
