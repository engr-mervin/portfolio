<script lang="ts">
	export let link: string;
</script>

<a
	href={link}
	class="hover:underline py-4 px-8 hover:bg-slate-500 text-center bg-white border-solid border-zinc-800 border max-w-xs self-center w-4/5 rounded-lg"
>
	<slot />
</a>
