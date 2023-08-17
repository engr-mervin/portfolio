<script>
	import Link from './Link.svelte';
	import Title from './Title.svelte';
	import List from './List.svelte';
</script>

<svelte:head>
	<title>Eonox</title>
</svelte:head>
<Title>John Mervin C. Bocatcat</Title>
<List>
	<Link link="/projects">Personal Projects</Link>
	<Link link="/training">Training Projects</Link>
	<Link link="/certifications">Certifications</Link>
</List>
