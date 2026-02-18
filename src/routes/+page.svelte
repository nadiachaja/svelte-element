<script>
    import { Text } from "$lib/index.js";
    import svelte from "$lib/assets/svelte.png";
</script>

<Text as="h1">Svelte:element</Text>

<div>
    <section>
        <img src={svelte} alt="" height="100" width="250" />
        <Text as="h2">Svelte:element</Text>
        <Text as="p"
            >Je kan hiermee kiezen welke html element je wil gebruiken. Zo kan
            je herbruikbare componenten maken.</Text
        >
    </section>

    <section>
        <img src={svelte} alt="" height="100" width="250" />
        <Text as="h2">Svelte:element</Text>
        <Text as="p"
            >Je kan hiermee kiezen welke html element je wil gebruiken. Zo kan
            je herbruikbare componenten maken.</Text
        >
    </section>

    <section>
        <img src={svelte} alt="" height="100" width="250" />
        <Text as="h2">Svelte:element</Text>
        <Text as="p"
            >Je kan hiermee kiezen welke html element je wil gebruiken. Zo kan
            je herbruikbare componenten maken.</Text
        >
    </section>

    <section>
        <img src={svelte} alt="" height="100" width="250" />
        <Text as="h2">Svelte:element</Text>
        <Text as="p"
            >Je kan hiermee kiezen welke html element je wil gebruiken. Zo kan
            je herbruikbare componenten maken.</Text
        >
    </section>
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

    section {
        background-color: orange;
        display: flex;
        flex-direction: column;
        gap: 1em;
        width: 20em;
    }

    img {
        display: flex;
        align-self: center;
        margin: 1em;
    }
</style>
