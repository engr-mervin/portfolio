<script>
	import Link from '../../Link.svelte';
	import Title from '../../Title.svelte';
	import Info from '../../Info.svelte';
	import List from '../../List.svelte';
	import Back from '../../Back.svelte';
	import Video from '../../Video.svelte';
</script>

<Title>Harvest Town</Title>
<List>
	<Video src="/videos/HARVEST-TOWN.mp4" />
	<Info
		>A 2d topdown game I worked on for the first half of 2020. Implements touch movement, zooming
		and panning, creation of walls, floors. You can also buy carpets, wallpapers and various
		furnitures to put in your house.
	</Info>
	<Link link="https://github.com/engr-mervin/harvest-town">Check Repository</Link>
	<Back link="/gamedev">Back</Back>
</List>
