<script>
	import Link from '../Link.svelte';
	import List from '../List.svelte';
	import Title from '../Title.svelte';
</script>

<svelte:head>
	<title>Certifications</title>
</svelte:head>
<Title>Certifications</Title>
<List>
	<Link link="/certifications/JavaScript"
		>The Complete JavaScript Course 2023: From Zero to Expert!</Link
	>
	<Link link="/certifications/HTMLCSS1">Build Responsive Real-World Websites with HTML and CSS</Link
	>
	<Link link="/certifications/HTMLCSS2"
		>Advanced CSS and SASS: Flexbox, Grid, Animations and More!</Link
	>
	<Link link="/certifications/ReactJS"
		>React - The Complete Guide 2023 (incl. React Router & Redux)</Link
	>
	<Link link="/certifications/Agile">Agile Fundamentals: Including Scrum & Kanban</Link>
	<Link link="/">Back</Link>
</List>
