<script>
	import TwitterLogo from './TwitterLogo.svelte';
	import GithubLogo from './GithubLogo.svelte';
</script>

<div class="wrapper">
	<h2>
		source code at
		<a class="felt-social-repo" href="https://github.com/feltcoop" rel="noopener">
			<span>github.com/feltcoop</span>
		</a>
		and
		<a class="felt-social-repo" href="https://github.com/feltcoop/felt.social" rel="noopener">
			<span>github.com/feltcoop/felt.social</span>
		</a>
	</h2>
</div>

<style>
	.wrapper {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
	img {
		width: 192px;
		height: 192px;
		color: transparent;
	}
	h2 {
		display: flex;
		flex-direction: column;
		align-items: center;
		text-align: center;
	}
	.felt-repo {
		margin-bottom: 20px;
		padding-bottom: 10px;
	}
	.felt-social-repo {
		padding: 5px 10px;
	}
</style>
