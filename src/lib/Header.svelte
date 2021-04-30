<script lang="ts">
	import Logo from './Logo.svelte';
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
