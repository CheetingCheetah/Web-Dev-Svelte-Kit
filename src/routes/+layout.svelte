<!-- Video: 8f, Time: 13:00 -->
<script>
	import '$lib/style.css'
	import Header from "$lib/Header.svelte";
	import Footer from "$lib/Footer.svelte";
</script>

<!-- 
	Prettier file exception

	"files": "*.svelte",
		"options": {
			"parser": "svelte"
		} 
-->

<div class="wrapper">
	<Header />

	<main>
		<slot></slot>
	</main>

	<Footer />
</div>

<style>
	.wrapper {
		min-height: 100dvh;
		display: grid;
		grid-template-rows: auto 1fr auto ;
	}
</style>