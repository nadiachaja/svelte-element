<script>
    import { Text } from "$lib/index.js";
    import svelte from "$lib/assets/svelte.png";
</script>


    <section>
        <img src={svelte} alt="" height="100" width="250" />
        <Text as="h2"></Text>
        <p>Je kan hiermee kiezen welke html element je wil gebruiken. Zo kan
            je herbruikbare componenten maken.</p>
    </section>

    <style>
        section {
        background-color: orange;
        display: flex;
        flex-direction: column;
        gap: 1em;
        width: 20em;
        border-radius: 1em;
    }

    img {
        display: flex;
        align-self: center;
        margin: 1em;
    }

    p {
      margin: 1em;
      text-align: center;
    }
    </style>