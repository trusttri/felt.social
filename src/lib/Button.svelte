<script lang="ts">
	// TODO import from @feltcoop/felt

	export let classes = '';
	export let el: HTMLButtonElement | undefined = undefined;
	export let disabled = false;
</script>

<button class={classes} {disabled} type="button" on:click bind:this={el}>
	<slot />
</button>

<style>
	button {
		border-radius: 3px;
		border-width: 2px;
		padding: 10px 16px;
		color: var(--color_0);
		border-color: var(--color_0);
		background-color: rgba(73, 84, 153, 0.1);
		font-size: 24px;
		font-weight: bold;
		cursor: pointer;
		border-top-left-radius: 2px;
		border-top-right-radius: 8px;
		border-bottom-left-radius: 8px;
		border-bottom-right-radius: 2px;
		border-bottom-width: 4px;
		border-left-width: 4px;
	}

	button:hover {
		text-decoration: underline;
	}

	button:active {
		border-bottom-width: 2px;
		border-left-width: 2px;
		border-top-width: 4px;
		border-right-width: 4px;
	}

	button:focus {
		outline: 5px dotted var(--color_0);
	}

	button[disabled] {
		top: 0;
		background-color: rgba(203, 208, 233, 0.35);
	}
</style>
