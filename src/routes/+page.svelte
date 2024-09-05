<script>
	import SectionPlan from './components/homepage/section-plan.svelte';
	import SectionClient from './components/homepage/section-client.svelte';
	import Header from "./components/header.svelte";
	import SectionFeature from "./components/homepage/section-feature.svelte";
	import SectionHero from "./components/homepage/section-hero.svelte";
	import SectionTrust from "./components/homepage/section-trust.svelte";
	import Card from './components/card.svelte';
	import Btn from './components/btn.svelte';

</script>


<main>
<div id="network" class="network"></div>
	<Header />
	<SectionHero />
	<SectionTrust />
	<SectionFeature />
	<SectionClient />
	<SectionPlan />
	<Btn />
</main>
	


<style>
	@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}
	main {
		background-color: #ffffff;
	}
	
</style>
