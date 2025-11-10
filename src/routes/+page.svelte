<script>
	import Box from "$lib/Box.svelte";
	import HeadingBox from "$lib/HeadingBox.svelte";
	import Hero from "$lib/Hero.svelte";
</script>

<Hero />

<section>
	<div class="outer bg-gradient-gray">
		<div class="inner">
			<HeadingBox heading="Check out our most popular categories!"/>
			<Box />
		</div>
	</div>
</section>

<style>
	.inner{
		padding-block: 8rem;
	}
</style>
