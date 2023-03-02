<!-- This is our / route -->
<script lang=ts>
	import Grid from "./Grid.svelte";
	export let days: number[] = [0, 1, 0, 0, 0, 1, 0]
	export let days2: number[] = [0, 1, 0, 2, 0, 1, 0]
</script>

<svelte:head>
	<title>Calendar Testing</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<h1>
		New Route for Testing
	</h1>

</section>

<Grid days={days}/>

<br>
<br>

<Grid days={days2}/>

<style>

</style>
