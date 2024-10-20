<script>
	let {
		src,
		heading,
		description = 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat minus.',
		href = '/blog',
		linkText = 'Read More &raquo;',
	} = $props()
</script>

<div class="relative p-2 radius-4 bg-white flow">
	<img class="absolute" {src} alt="" />
	<h3>{heading}</h3>
	<p>{description}</p>
	<a class="inline-block fw-600" {href}>{@html linkText}</a>
</div>

<style>
	div {
		font-size: 1.125rem;
	}

	img {
		width: 3.5rem;
		top: -1.5rem;
	}
</style>
