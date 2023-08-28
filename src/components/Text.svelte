<script lang="ts">
	type TextType = 'h1' | 'h2' | 'h3' | 'h4' | 'h5' | 'h6' | 'span' | 'p';
	export let variant: TextType = 'p';
</script>

{#if variant === 'h1'}
	<h1 class="font-semibold leading-[46px]">
		<slot />
	</h1>
{:else if variant === 'h2'}
	<h2 class="text-3xl font-semibold leading-[38px]">
		<slot />
	</h2>
{:else if variant === 'h3'}
	<h3 class="text-2xl font-semibold leading-[32px]">
		<slot />
	</h3>
{:else if variant === 'h4'}
	<h4 class="text-xl font-semibold leading-[28px]">
		<slot />
	</h4>
{:else if variant === 'h5'}
	<h5 class="text-base font-medium leading-[24px]">
		<slot />
	</h5>
{:else if variant === 'h6'}
	<h6 class="text-sm font-semibold leading-[22px]">
		<slot />
	</h6>
{:else if variant === 'span'}
	<span class="text-xs font-normal leading-[20px]">
		<slot />
	</span>
{:else if variant === 'p'}
	<p class="text-xs font-normal leading-[20px]">
		<slot />
	</p>
{/if}
