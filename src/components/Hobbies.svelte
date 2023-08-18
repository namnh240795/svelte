<script>
	import Text from './Text.svelte';
	import { getContext } from 'svelte';
	let locale = getContext('locale');
</script>

<div class="hobbies__header">
	<Text variant="h4">{locale?.hobbiesAndInterest}</Text>
</div>
<div class="hobbies__container">
	<ul>
		<li>
			<Text variant="span">{locale?.hobbies1}</Text>
		</li>
		<li>
			<Text variant="span">{locale?.hobbies2}</Text>
		</li>
		<li>
			<Text variant="span">{locale?.hobbies3}</Text>
		</li>
		<li>
			<Text variant="span">{locale?.hobbies4}</Text>
		</li>
		<li>
			<Text variant="span">{locale?.hobbies5}</Text>
		</li>
		<li>
			<Text variant="span">{locale?.hobbies6}</Text>
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
