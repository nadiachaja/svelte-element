<script>
        import { ContainerCard } from "$lib/index.js";
</script>

<div>
    <ContainerCard></ContainerCard>
    <ContainerCard></ContainerCard>
</div>

<style>
    div {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 1em;
        
        @media (min-width: 768px) {
            display: grid;
            grid-template-columns: max-content max-content;
            justify-content: center;
        }
    }
</style>