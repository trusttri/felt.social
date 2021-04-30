<script lang="ts">
	import Logo from '$lib/Logo.svelte';
	import SocialLinks from '$lib/SocialLinks.svelte';
</script>

<footer>
	<div class="inner">
		<hr />
		<SocialLinks />
		<hr />
		<a href="/">
			<Logo />
		</a>
	</div>
</footer>

<style>
	footer {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	a {
		margin-top: 20px;
	}
	.inner {
		display: flex;
		justify-content: center;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
	}
</style>
