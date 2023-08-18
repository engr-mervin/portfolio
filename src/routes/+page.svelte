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
	<Link link="/gamedev">Game Development</Link>
	<Link link="/certifications">Certifications</Link>
</List>
<div class="flex justify-center gap-6">
	<a href="https://github.com/engr-mervin" class="h-10 w-10 mt-16"
		><img src="/icons/logo-github.svg" alt="Github Icon" /></a
	><a href="https://www.linkedin.com/in/engr-mervin/" class="h-10 w-10 mt-16"
		><img src="/icons/logo-linkedin.svg" alt="LinkedIn Icon" /></a
	><a href="mailto:johnmervin.bocatcat@gmail.com" class="h-10 w-10 mt-16"
		><img src="/icons/logo-google.svg" alt="Google Icon" /></a
	>
</div>
