<script>
	import Text from './Text.svelte';
	import { getContext } from 'svelte';
	let locale = getContext('locale');
</script>

<div class="opensource__header">
	<Text variant="h4">{locale?.openSourceProject}</Text>
</div>
<div class="opensource__container">
	<ul>
		<li>
			<Text variant="span">
				<a href="https://www.npmjs.com/package/brainless-token-manager" target="_blank">
					brainless-token-manager:
				</a>
				<br />
					{locale?.brainlessTokenManagerDescription}
				<br />
			</Text>
		</li>
		<li>
			<Text variant="span">
				<a href="https://www.npmjs.com/package/number-to-text-vietnamese" target="_blank">
					number-to-text-vietnamese
				</a>
				<br />
				{locale?.numberToTextVietnameseDescription}
				<br />
			</Text>
		</li>
		<li>
			<Text variant="span">
				<a href="https://www.npmjs.com/package/react-native-svgs-to-icon" target="_blank">
					react-native-svgs-to-icon
				</a>
				<br />
				{locale?.reactNativeSvgsToIconDescription}
				<br />
			</Text>
		</li>
	</ul>
</div>

<style>
	.opensource__container {
		padding: 0px 16px;
	}
	.opensource__container ul {
		list-style-type: square;
	}
	.opensource__container li {
		margin-top: 8px;
	}
	.opensource__header {
		margin-top: 16px;
		margin-left: 0;
	}

	.opensource__container a {
		color: salmon;
	}
</style>
