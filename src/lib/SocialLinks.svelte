<script lang="ts">
	import TwitterLogo from './TwitterLogo.svelte';
	import GithubLogo from './GithubLogo.svelte';

	export let iconHeight = 64;
</script>

<div class="wrapper">
	<div class="links">
		<a
			class="focusable"
			style="height: {iconHeight}px;"
			href="https://twitter.com/feltcoop"
			rel="noopener"
		>
			<TwitterLogo size={iconHeight} />
		</a>
		<a
			class="focusable"
			style="height: {iconHeight}px;"
			href="https://github.com/feltcoop"
			rel="noopener"
		>
			<GithubLogo size={iconHeight} />
		</a>
	</div>
</div>

<style>
	.wrapper {
		text-align: center;
	}
	.links {
		display: flex;
	}
	.links a {
		text-decoration: none;
		margin: 0 5px;
	}
</style>
