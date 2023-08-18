<script>
	import Link from '../../Link.svelte';
	import Title from '../../Title.svelte';
	import Info from '../../Info.svelte';
	import List from '../../List.svelte';
	import Image from '../../Image.svelte';
	import Back from '../../Back.svelte';
</script>

<Title>My CE Resume</Title>
<List>
	<Image src="/images/CE-MERVIN.png" alt="My Resume as a Civil Engineer" />
	<Info
		>My Resume showcasing my experience as a Civil Engineer for 5 years. Built with HTML & CSS.</Info
	>
	<Link link="https://ce-mervin.eonox.dev">View Website</Link>
	<Link link="https://github.com/engr-mervin/mervin-resume">Check Repository</Link>
	<Back link="/projects">Back</Back>
</List>
