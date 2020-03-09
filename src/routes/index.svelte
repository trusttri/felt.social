<script>
	import MailingListCallout from '@app/MailingListCallout.svelte';
	import Logo from '@app/Logo.svelte';
	import SocialLinks from '@app/SocialLinks.svelte';
	import Intro from '@app/Intro.svelte';
	import WeAreLive from '@app/WeAreLive.svelte';
	import Footer from '@app/Footer.svelte';
</script>

<svelte:head>
	<title>felt</title>
</svelte:head>

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
	<MailingListCallout />
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
