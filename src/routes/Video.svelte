<script lang="ts">
	export let src: string;
</script>

<video autoplay muted loop class="self-center w-full border-2 border-slate-500 rounded-lg">
	<source {src} type="video/mp4" />
</video>
