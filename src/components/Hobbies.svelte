<script>
	import Text from './Text.svelte';
	import { getContext } from 'svelte';
	let locale = getContext('locale');
</script>

<div>
<div class="mt-2">
	<Text variant="h4">{locale?.hobbiesAndInterest}</Text>
</div>
<div class="px-4">
	<ul class="list-[square]">
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
</div>