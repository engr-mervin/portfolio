<script>
	import Link from '../../Link.svelte';
	import Title from '../../Title.svelte';
	import Info from '../../Info.svelte';
	import List from '../../List.svelte';
	import Image from '../../Image.svelte';
	import Back from '../../Back.svelte';
</script>

<Title>Flavory</Title>
<List>
	<Image src="/images/FLAVORY.png" alt="Flavory landing page." />
	<Info
		>A full stack food recipe app where you can create account, search recipes, post recipes and
		bookmark recipes. Built with NextJS 12, Prisma, SASS and Supabase.</Info
	>
	<Link link="https://flavory.eonox.dev">View Website</Link>
	<Link link="https://github.com/engr-mervin/flavory">Check Repository</Link>
	<Back link="/projects">Back</Back>
</List>
