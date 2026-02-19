<script>
  import { Text, ContainerCards, Link } from "$lib/index.js";
</script>

<Text as="h1"></Text>
<Link></Link>

<ContainerCards></ContainerCards>

<ul>
  <li>
    In dit voorbeeld heb ik <code>&lt;svelte:element&gt;</code>
    twee keer gebruikt: één keer als een h1 en één keer als een h2.
  </li>
  <li>
    Met <code>&lt;svelte:element&gt;</code>
    kun je tijdens het draaien van de website bepalen welk HTML-element er gebruikt
    wordt.
  </li>
  <li>
    In het <code>&lt;script&gt;</code>
    geef je aan wat het standaard HTML-element is. Daarna kun je dit dynamisch veranderen.
  </li>
  <li>
    In de HTML gebruik je dan <code>&lt;svelte:element&gt;</code>
    met <code>this=</code>, zodat Svelte weet welk element het moet renderen.
  </li>
</ul>

<style>
    ul{
        display: flex;
        flex-direction: column;
        justify-self: center;
        margin: 3em;
    }

    li{
        list-style: none;
    }
</style>