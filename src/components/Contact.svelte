<script>
	import Text from "./Text.svelte";
    
</script>

<div class="contact-container">
    <Text variant='p'>
        <slot />
    </Text>
</div>

<style>
    .contact-container {
        padding: 4px 8px;
        border-radius: 4px;
        background-color: antiquewhite;
        color: #000000;
        margin-top: 16px;
    }
</style>