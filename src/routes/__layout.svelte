<script>
	import '../app.scss';
	import Header from '$lib/Header.svelte';
	import Footer from '$lib/Footer.svelte';
</script>

<!-- Nav bar and Header -->
<Header />

<slot />

<!-- Footer -->
<Footer />

