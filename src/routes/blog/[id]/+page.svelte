<script>
    import Title from "$lib/Title.svelte";

	export let data
</script>

<Title name="{data.post.title}"/>

<div class="outer">
    <div class="inner">
        <p>{data.post.body}</p>
    </div>
</div>
