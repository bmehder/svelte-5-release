<script>
	import Title from '$lib/Title.svelte'

	export let data
</script>

<Title name={data.post.title} />

<section>
	<div class="outer">
		<div class="inner flow">
			<div class="post-body">{data.post.body}</div>
		</div>
	</div>
</section>

<style>
	.post-body {
		max-width: 65ch;
	}
</style>
