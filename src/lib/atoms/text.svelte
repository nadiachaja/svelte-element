<script>
    let { as = "p", ...restProps } = $props();
</script>

<svelte:element this={as} {...restProps}>
    Svelte:element
</svelte:element>

<style>

    h1{
        text-align: center;
    }

    h2{
        text-align: center;
        margin: 0;
    }
</style>