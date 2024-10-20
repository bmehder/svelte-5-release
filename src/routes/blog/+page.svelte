<script>
	import Title from '$lib/Title.svelte'

	export let data
</script>

<Title name="Blog" />

<section>
	<div class="outer">
		<div class="inner py-3 auto-fit gap-3">
			{#each data.posts as post}
				<div class="flow">
					<h2 class="capitalize"><a href="/blog/{post.id}">{post.title}</a></h2>
					<p>{post.body}</p>
				</div>
			{/each}
		</div>
	</div>
</section>
