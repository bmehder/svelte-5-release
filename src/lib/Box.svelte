<script>
	let {
		src,
		heading,
		description = 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat minus.',
		href = '/blog',
		linkText = 'Read More &raquo;',
	} = $props()
</script>

<div class="bg-white flow">
	<img {src} alt="" />
	<h3>{heading}</h3>
	<p>
		{description}
	</p>
	<a {href}>Read More &raquo;</a>
</div>

<style>
	div {
		position: relative;
		padding: 2rem;
		font-size: 1.125rem;
		border-radius: 1rem;
	}

	img {
		max-width: 3.5rem;
		position: absolute;
		top: -1.5rem;
	}

	a {
		display: inline-block;
		font-weight: 600;
	}
</style>
