<script>
	import Link from '../../Link.svelte';
	import Title from '../../Title.svelte';
	import Info from '../../Info.svelte';
	import List from '../../List.svelte';
	import Image from '../../Image.svelte';
	import Back from '../../Back.svelte';
</script>

<Title>DSWD App</Title>
<List>
	<Image src="/images/DSWD.png" alt="DSWD App Calculator" />
	<Info
		>A materials calculator for Road Projects built for DSWD KALAHI. Built with SASS and Vanilla
		JavaScript.</Info
	>
	<Link link="https://dswd.eonox.dev">View Website</Link>
	<Link link="https://github.com/engr-mervin/tf-mervin">Check Repository</Link>
	<Back link="/projects">Back</Back>
</List>
