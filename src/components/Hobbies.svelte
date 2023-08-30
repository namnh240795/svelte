<script>
	import Text from './Text.svelte';
	import { getContext } from 'svelte';
	let locale = getContext('locale');
</script>

<div class="animate-fade">
	<div
		class="mt-[24px] text-[black] border-b-[3px] [border-bottom-color:black] border-solid w-[fit-content]"
	>
		<Text variant="h4">{locale?.hobbiesAndInterest}</Text>
	</div>
	<div class="mt-[16px] text-[black] ml-4">
		<ul class="list-[circle]">
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
