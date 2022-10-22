<script>
	import Card from '../card.svelte';
	export let card = [
		{
			plan: 'Online Shop',
		description: 'ecommerce store like JUMIA, JIJI, SHEIN etc.',
		features: ['10 free product slot', '₦500 to add a product', '₦1000 to add a category'],
		price: '₦15,000'
		},
		{plan: 'Company Website',
		description: 'Real Estate website, Forex academy website, Car dealership website',
		features: [
			'2 free pages',
			'₦1000 to add a page',
			'extra charges applied for any other features'
		],
		price: '₦15,000'}
	]
</script>

<section id="pricing">
	<div class="container mx-auto md:my-40 my-20">
		<div class="mb-20">
			<p class="text-xs text-center">PRICING</p>
			<h2 class="md:text-5xl text-4xl text-center">Choose your <br class="md:hidden" />website</h2>
		</div>
		<div class="flex flex-col md:flex-row gap-y-6 justify-center items-center ">
			<Card card={card[0]}/>
			<Card  card={card[1]}/>
		</div>
	</div>
</section>
