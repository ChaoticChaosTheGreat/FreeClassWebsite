<script>

import Navbar from './Navbar.svelte';
import MainScreen from './MainScreen.svelte';
import Features from './Features.svelte';
import Testimonial from './Testimonial.svelte';
import Newsletter from './Newsletter.svelte';
import FAQ from './FAQ.svelte';
</script>

<svelte:head>
	<title>Free Python For Kids</title>
	<meta name="description" content="Free Python Class For Kids" />
</svelte:head>

<div class="bg-black relative isolate">
	<Navbar/>
	<MainScreen/>
	<Features/>
	<Testimonial/>
	<Newsletter/>
	<FAQ/>
</div>

