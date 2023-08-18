<script>
	import Back from '../Back.svelte';
	import Link from '../Link.svelte';
	import List from '../List.svelte';
	import Title from '../Title.svelte';
</script>

<svelte:head>
	<title>Game Development</title>
</svelte:head>
<Title>Game Development</Title>
<List>
	<Link link="/gamedev/flappy-cube">Flappy Cube</Link>
	<Link link="/gamedev/harvest-town">Harvest Town</Link>
	<Back link="/">Back</Back>
</List>
