<script>
	import MailingListCallout from '@app/MailingListCallout.svelte';
	import Logo from '@app/Logo.svelte';
	import SocialLinks from '@app/SocialLinks.svelte';
	import Intro from '@app/Intro.svelte';
	import Footer from '@app/Footer.svelte';
</script>

<svelte:head>
	<title>felt</title>
</svelte:head>

<section>
	<Logo />
</section>
<section>
	<Intro />
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
	}
</style>
