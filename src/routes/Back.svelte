<script lang="ts">
	export let link: string;
</script>

<a
	href={link}
	class="hover:underline py-4 px-8 bg-white rounded-lg hover:bg-slate-500 text-center border-solid border-zinc-800 border max-w-xs self-center w-4/5 mt-8"
>
	<slot />
</a>
