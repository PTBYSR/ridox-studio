<script>
	import Pricing from '../components/sections/pricing.svelte';
	import Header from '../components/sections/header.svelte';
	import Landing from '../components/sections/landing.svelte';
	import About from '../components/sections/about.svelte';
	import Footer from '../components/sections/footer.svelte';
    import { MetaTags } from 'svelte-meta-tags';
</script>

<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
	<link
		href="https://fonts.googleapis.com/css2?family=Inter&family=Libre+Baskerville&display=swap"
		rel="stylesheet"
	/>
</svelte:head>
<MetaTags
  title="Ridox Studio"
  titleTemplate="%s  "
  description="Get a website connected to your Whatsapp Business on a budget"
  canonical=""
  openGraph={{
    url: 'https://ridox-studio.vercel.app/',
    title: 'Ridox Studio',
    description: 'Open Graph Description',
    images: [
      {
        url: 'https://ridox-studio.vercel.app/ridox-tab-icon.png',
        width: 800,
        height: 600,
        alt: ''
      },
      {
        url: 'https://ridox-studio.vercel.app/ridox-tab-icon.png',
        width: 900,
        height: 800,
        alt: 'Og Image Alt Second'
      },
    ],
    site_name: 'Ridox Studio'
  }}
  twitter={{
    handle: '@ptbthefirst',
    site: '@site',
    cardType: 'summary',
    title: 'Ridox Studio',
    description: 'Get a website connected to your Whatsapp Business on a budget.',
    image: 'https://ridox-studio.vercel.app/ridox-tab-icon.png',
    imageAlt: 'Twitter image alt'
  }}
  facebook={{
    appId: '1234567890'
  }}
/>
<Header />
<Landing />
<Pricing />
<About />
<Footer />
