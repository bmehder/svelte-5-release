<script>
	import '$lib/style.css'
	import 'cheekycss'
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
