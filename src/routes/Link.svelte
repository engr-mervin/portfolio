<script lang="ts">
	export let link: string;
</script>

<a href={link} class="hover:underline py-4 px-8 hover:bg-slate-500 text-center">
	<slot />
</a>
