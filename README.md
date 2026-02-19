# Svelte:element 

## Installatie
- Open een code editor programma
- Clone de code van de repository main branch en zorg dat je 'contribute for my own purposes' aanklikt.
- Gebruik de main branche of maak een feature branche aan.
- Type in "npm install" zodat je de nodige dependencies download.
- Type in "npm run dev" of "npm run dev -- --open" zodat het project kan gestart worden.
- Klik op de local host als je npm run dev hebt gedaan en je ziet het project of het project start automatische op met npm run -- --open.

## Uitleg 
Svelte:element is een speciaal Svelte-element waarmee je dynamisch kunt kiezen welk HTML-element er wordt gemaakt.<br>
In het <script> geef je aan wat het standaard HTML-element is. Daarna kun je dit dynamisch veranderen.
In de HTML gebruik je dan <svelte:element> met this={...}, zodat Svelte weet welk element het moet renderen.
Het is handig om te gebruiken als je componenten gebruikt, zo zijn die herbruikbaar. 



