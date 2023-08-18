<script>
	import Link from '../../Link.svelte';
	import Title from '../../Title.svelte';
	import Info from '../../Info.svelte';
	import List from '../../List.svelte';
	import Image from '../../Image.svelte';
	import Back from '../../Back.svelte';
</script>

<Title>Mapty</Title>
<List>
	<Image src="/images/MAPTY.png" alt="Mapty App." />
	<Info
		>An app for tracking your cycling/jogging locations. Made with Vanilla JavaScript, HTML & CSS.</Info
	>
	<Link link="https://mapty.eonox.dev">View Website</Link>
	<Link link="https://github.com/engr-mervin/mapty">Check Repository</Link>
	<Back link="/training">Back</Back>
</List>
