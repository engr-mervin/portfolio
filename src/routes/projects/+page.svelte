<script>
	import Back from '../Back.svelte';
	import Link from '../Link.svelte';
	import List from '../List.svelte';
	import Title from '../Title.svelte';
</script>

<svelte:head>
	<title>Projects</title>
</svelte:head>
<Title>Personal Projects</Title>
<List>
	<Link link="/projects/flavory">Flavory</Link>
	<Link link="/projects/dswd">DSWD App</Link>
	<Link link="/projects/ce-mervin">My CE Resume</Link>
	<Back link="/">Back</Back>
</List>
