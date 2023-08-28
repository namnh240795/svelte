<script>
	import { getContext } from 'svelte';
	let locale = getContext('locale');
	import Text from './Text.svelte';
</script>

<div>
	<div class="about__title animate-fade">
		<Text variant="h4">{locale?.about}</Text>
	</div>
	<div class="about__description animate-fade">
		<Text variant="h5">
			{locale?.aboutDescription}
		</Text>
	</div>
</div>

<style>
	.about__title {
		margin-top: 24px;
		color: black;
		border-bottom-width: 3px;
		border-bottom-color: black;
		border-style: solid;
		width: fit-content;

	}

	.about__description {
		margin-top: 16px;
		color: black;
	}
</style>
