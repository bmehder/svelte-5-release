<script>
	import 'cheekycss'
	import '$lib/style.css'
	import Footer from '$lib/Footer.svelte'
	import Header from '$lib/Header.svelte'
</script>

<div class="wrapper">
	<Header />
	<main>
		<slot></slot>
	</main>
	<Footer />
</div>
