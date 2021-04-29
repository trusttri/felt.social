<script lang="ts">
	import Header from '$lib/Header.svelte';
	import SocialLinks from '$lib/SocialLinks.svelte';
	import Intro from '$lib/Intro.svelte';
	import LearnAboutFelt from '$lib/LearnAboutFelt.svelte';
	import WeAreLive from '$lib/WeAreLive.svelte';
	import Footer from '$lib/Footer.svelte';
</script>

<section>
	<Header>
		<h2>customizable communities that feel good</h2>
	</Header>
</section>
<section class="intro">
	<Intro />
</section>
<section>
	<LearnAboutFelt />
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
