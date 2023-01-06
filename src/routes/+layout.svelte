<script>
	import Header from './Header.svelte';
	import Footer from './Footer.svelte';
	import './css/style.css';
	import './css/bootstrap.min.css';
</script>

<div class="app">
	<Header />

	<main>
		<slot />
	</main>

	<Footer />
</div>

<style>

</style>
