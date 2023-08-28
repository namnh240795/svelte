<script>
	import Text from './Text.svelte';
	import { getContext } from 'svelte';
	let locale = getContext('locale');
</script>

<div class="mt-[16px] ml-0">
	<Text variant="h4">{locale?.openSourceProject}</Text>
</div>
<div class="px-[16px] py-0">
	<ul class="list-[square] [&>li]:mt-[8px]">
		<li>
			<Text variant="span">
				<a
					class="text-[salmon]"
					href="https://www.npmjs.com/package/brainless-token-manager"
					target="_blank"
				>
					brainless-token-manager:
				</a>
				<br />
				{locale?.brainlessTokenManagerDescription}
				<br />
			</Text>
		</li>
		<li>
			<Text variant="span">
				<a
					class="text-[salmon]"
					href="https://www.npmjs.com/package/number-to-text-vietnamese"
					target="_blank"
				>
					number-to-text-vietnamese
				</a>
				<br />
				{locale?.numberToTextVietnameseDescription}
				<br />
			</Text>
		</li>
		<li>
			<Text variant="span">
				<a
					class="text-[salmon]"
					href="https://www.npmjs.com/package/react-native-svgs-to-icon"
					target="_blank"
				>
					react-native-svgs-to-icon
				</a>
				<br />
				{locale?.reactNativeSvgsToIconDescription}
				<br />
			</Text>
		</li>
	</ul>
</div>
