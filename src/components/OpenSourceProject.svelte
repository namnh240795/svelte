<script>
	import Text from './Text.svelte';
</script>

<div class="opensource__header">
	<Text variant="h4">Open Source Projects</Text>
</div>
<div class="opensource__container">
	<ul>
		<li>
			<Text variant="span">
				<a href="https://www.npmjs.com/package/brainless-token-manager" target="_blank">
					brainless-token-manager:
				</a>
				<br />
				Help you manage your token and refresh token in your project (Javascript, Typescript)
				<br />
			</Text>
		</li>
		<li>
			<Text variant="span">
				<a href="https://www.npmjs.com/package/number-to-text-vietnamese" target="_blank">
					number-to-text-vietnamese
				</a>
				<br />
				Transform Integer Number To Vietnamese (Javascript, Typescript)
				<br />
			</Text>
		</li>
		<li>
			<Text variant="span">
				<a href="https://www.npmjs.com/package/react-native-svgs-to-icon" target="_blank">
					react-native-svgs-to-icon
				</a>
				<br />
				Generate iconfont and icon components in react-native (Similar as AntDesign Icons, MaterialIcons)
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
