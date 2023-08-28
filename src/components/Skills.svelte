<script>
	import Text from './Text.svelte';
	import { getContext } from 'svelte';
	let locale = getContext('locale');
</script>

<div class="animate-fade">
	<div
		class="mt-[24px] text-[black] border-b-[3px] [border-bottom-color:black] border-solid w-[fit-content]"
	>
		<Text variant="h4">Skills</Text>
	</div>
	<div class="mt-[16px] text-[black]">
		<div class="ml-4">
			<ul class="list-[circle]">
				<li>
					<Text variant="span">{locale?.skills1}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills2}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills3}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills4}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills5}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills6}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills7}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills8}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills9}</Text>
				</li>
			</ul>
		</div>
	</div>
</div>
