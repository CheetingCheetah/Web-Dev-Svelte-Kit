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
			<Box src="/icons/icon-animation.svg" heading="Animation" text="Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates, odio?" href="/blog"/>
			<Box src="/icons/icon-business.svg" heading="Business" text="Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates, odio?" href="/blog"/>
			<Box src="/icons/icon-design.svg" heading="Design" text="Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates, odio?" href="/blog"/>
			<Box src="/icons/icon-photography.svg" heading="Photography" text="Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates, odio?" href="/blog"/>
			<Box src="/icons/icon-programming.svg" heading="Programming" text="Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates, odio?" href="/blog"/>
		</div>
	</div>
</section>

<style>
	.inner{
		padding-block: 8rem;
	}
</style>
