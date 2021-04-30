<script lang="ts">
	import Logo from '$lib/Logo.svelte';
</script>

<header>
	<a href="/">
		<Logo />
	</a>
	<slot />
</header>

<style>
	header {
		text-align: center;
	}
</style>
