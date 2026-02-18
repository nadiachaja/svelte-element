<script>
    let { as = "p", children, ...restProps } = $props();
</script>

<svelte:element this={as} {...restProps}>
    {@render children?.()}
</svelte:element>

<style>

    h1{
        text-align: center;
    }

    h2{
        text-align: center;
    }

    p{
      margin: 1em;
      text-align: center;
    }
</style>