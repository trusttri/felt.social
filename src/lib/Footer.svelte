<script lang="ts">
	import SocialLinks from '$lib/SocialLinks.svelte';
</script>

<footer>
	<slot />
	<SocialLinks />
</footer>

<style>
	footer {
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
	}
</style>
