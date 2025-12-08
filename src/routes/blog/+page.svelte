<script>
	import Title from "$lib/Title.svelte";

	export let data
</script>

<Title name="Blog" />

<section>
	<div class="outer">
		<div class="inner auto-fit">
			{#each data.posts.posts as post}
				<div class="flow">
					<h2><a href="/blog/{post.slug}">{@html post.title}</a></h2>
					<p>{@html post.excerpt}</p>
				</div>
			{/each}
		</div>
	</div>
</section>
