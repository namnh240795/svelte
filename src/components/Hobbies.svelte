<script>
	import Text from './Text.svelte';
</script>

<div class="hobbies__header">
	<Text variant="h4">Hobbies And Interest</Text>
</div>
<div class="hobbies__container">
	<ul>
		<li>
			<Text variant="span">Money</Text>
		</li>
		<li>
			<Text variant="span">Traveling</Text>
		</li>
		<li>
			<Text variant="span">Programming Theory, New Technology</Text>
		</li>
		<li>
			<Text variant="span">3D China's Anime</Text>
		</li>
		<li>
			<Text variant="span">Gym</Text>
		</li>
		<li>
			<Text variant="span">Music</Text>
		</li>
	</ul>
</div>

<style>
	.hobbies__container {
		padding: 0px 16px;
	}
	.hobbies__container ul {
		list-style-type: square;
	}
	.hobbies__container li {
		margin-top: 8px;
	}
	.hobbies__header {
		margin-top: 16px;
		margin-left: 0;
	}
</style>
