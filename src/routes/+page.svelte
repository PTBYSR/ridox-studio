<script>
	import Pricing from '../components/sections/pricing.svelte';
	import Header from '../components/sections/header.svelte';
	import Landing from '../components/sections/landing.svelte';
	import About from '../components/sections/about.svelte';
	import Footer from '../components/sections/footer.svelte';
</script>

<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
	<link
		href="https://fonts.googleapis.com/css2?family=Inter&family=Libre+Baskerville&display=swap"
		rel="stylesheet"
	/>
</svelte:head>
<Header />
<Landing />
<Pricing />
<About />
<Footer />
