<script lang="ts">
	import Logo from '$lib/Logo.svelte';
	import SocialLinks from '$lib/SocialLinks.svelte';
</script>

<footer>
	<SocialLinks />
	<a href="/">
		<Logo />
	</a>
</footer>

<style>
	footer {
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
	}
	a {
		margin-top: 20px;
	}
</style>
