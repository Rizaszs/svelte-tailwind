<script>
	import Tailwindcss from './Tailwind.svelte';
	import NavBar from '../components/NavBar.svelte';
	import Hero from '../components/Hero.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<Tailwindcss />

<section class="min-h-screen flex flex-col justify-between items-center bg-base-200">
	<NavBar />
	<Hero />
	<Footer />
</section>
