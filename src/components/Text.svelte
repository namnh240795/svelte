<script lang="ts">
    type TextType = 'h1' | 'h2' | 'h3' | 'h4' | 'h5' | 'h6' | 'span' |'p';
    export let variant: TextType = 'p';
</script>

{#if variant === 'h1'} 
    <h1>
        <slot />
    </h1>
{:else if variant === 'h2'}
    <h2>
        <slot />
    </h2>
{:else if variant === 'h3'}
    <h3>
        <slot />
    </h3>
{:else if variant === 'h4'}
    <h4>
        <slot />
    </h4>
{:else if variant === 'h5'}
    <h5>
        <slot />
    </h5>
{:else if variant === 'h6'}
    <h6>
        <slot />
    </h6>
{:else if variant === 'span'}
    <span>
        <slot />
    </span>
{:else if variant === 'p'}
    <p>
        <slot />
    </p>
{/if}

<style>
    h1 {
        font-size: 38px;
        font-weight: 600;
        line-height: 46px;
    }
    h2 {
        font-size: 30px;
        font-weight: 600;
        line-height: 38px;
    }

    h3 {
        font-size: 24px;
        font-weight: 600;
        line-height: 32px;
    }

    h4 {
        font-size: 20px;
        font-weight: 600;
        line-height: 28px;
    }

    h5 {
        font-size: 16px;
        font-weight: 500;
        line-height: 24px;
    }

    h6 {
        font-size: 14px;
        font-weight: 600;
        line-height: 22px;
    }

    p {
        font-size: 12px;
        font-weight: 400;
        line-height: 20px;
    }
    
    span {
        font-size: 12px;
        font-weight: 400;
        line-height: 20px;
    }

</style>