<script>
	import Box from "$lib/Box.svelte";
	import HeadingBox from "$lib/HeadingBox.svelte";
	import Hero from "$lib/Hero.svelte";
</script>

<Hero />

<section>
	<div class="outer bg-gradient-gray">
		<div class="inner auto-fit">
			<HeadingBox heading="Check out our most popular categories!"/>
			<Box src="/icons/icon-animation.svg" heading="Animation"/>
			<Box src="/icons/icon-business.svg" heading="Business"/>
			<Box src="/icons/icon-design.svg" heading="Design"/>
			<Box src="/icons/icon-photography.svg" heading="Photography"/>
			<Box src="/icons/icon-programming.svg" heading="Programming"/>
		</div>
	</div>
</section>

<style>
	.inner{
		padding-block: 8rem;
	}
</style>
