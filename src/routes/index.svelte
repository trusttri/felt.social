<script lang="ts">
	import Logo from '$lib/Logo.svelte';
	import SocialLinks from '$lib/SocialLinks.svelte';
	import Intro from '$lib/Intro.svelte';
	import WeAreLive from '$lib/WeAreLive.svelte';
	import Footer from '$lib/Footer.svelte';
</script>

<section>
	<Logo />
	<h2>customizable communities that feel good</h2>
</section>
<section class="intro">
	<Intro />
</section>
<section>
	<WeAreLive />
</section>
<section>
	<SocialLinks />
</section>
<section>
	<Footer />
</section>

<style>
	section {
		margin-bottom: 40px;
		max-width: 600px;
	}
	h2,
	.intro {
		text-align: center;
	}
</style>
