<main>
	<slot />
</main>

<style>
	main {
		position: relative;
		max-width: 980px;
		padding: 2em;
		margin: 0 auto;
	}

	:global(a) {
		color: #495499;
		font-size: 32px;
		text-decoration: none;
	}
	:global(a:hover) {
		text-decoration: underline;
	}
	:global(a:visited) {
		color: #495499;
	}
</style>
