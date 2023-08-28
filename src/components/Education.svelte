<script>
	import Text from './Text.svelte';
	import { getContext } from 'svelte';
	let locale = getContext('locale');
</script>

<div class="animate-fade">
	<div class="mt-[24px] text-[black] border-b-[3px] [border-bottom-color:black] border-solid w-[fit-content]">
		<Text variant="h4">{locale?.education}</Text>
	</div>
	<div class="mt-[16px] text-[black]">
		<Text variant="h5">{locale?.educationCertificate}</Text>
		<div class="text-[#666666]">
			<Text variant="h5">{locale?.educationCertificationDate}</Text>
		</div>
	</div>
</div>

