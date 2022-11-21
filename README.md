# Project Team Workshop Git IIb

Als het goed is hebben jullie allemaal het individuele deel van de workshop afgerond, en hebben jullie een idee hoe om te gaan met meerdere Git-tijdlijnen. In dit tweede deel gaan jullie met je groepje oefenen door middel van het spelen van *20 questions*, via een tekstbestand in deze Git repo (`GAME.md`). Het bestand bevat al een voorbeeldspel, [waarvan de historie ook zichtbaar is](https://github.com/hu-ict-projb/git-20-questions/network).

## Rollen
20 questions wordt gespeeld in rondes. Een persoon is steeds de spelleider, dit is degene die de vorige ronde gewonnen heeft (of nog niet aan de beurt is geweest). Voor de eerste ronde begint de student met de meeste Git-kennis.

De spelleider neemt een persoon of personage in diens hoofd. Deze persoon moet algemeen bekend zijn. De andere spelers mogen elk steeds een ja-nee vraag stellen (Is de persoon bekend van TV? Is de persoon een Nederlander? Etc.), door deze toe te voegen aan het bestand `GAME.md`. Iedere speler behalve de spelleider werkt op een eigen branch (deze kun je in PyCharm aanmaken via het Git > Branch > New Branches menu, of met het commando `git branch naam`). Nadat je een vraag toevoegt moet je deze aanpassing committen op je eigen branch, en deze pushen. Behalve de spelleider mag niemand naar main comitten / pushen.

Zodra mensen hun vragen hebben gepusht, kan de spelleider met Fetch en Merge de verschillende branches binnenhalen. Het idee is steeds een vraag te beantwoorden door de branch in `main` te mergen, een antwoord bij de vraag te geven, en vervolgens het resultaat te committen en pushen. Hierna kan iedereen een Fetch doen om de bijgewerkte `main` binnen te krijgen, hun eigen branch bij te werken, en een nieuwe vraag klaar te zetten.

Zodra iemand de persoon heeft geraden (door de vraag te stellen "Is de persoon Tijmen?") dan heeft die deze ronde gewonnen. De vorige spelleider voegt de nog openstaande branches samen, waarna de winnaar van de vorige ronde spelleider wordt en verantwoordelijk is voor de main branch. De oude spelleider moet nu een eigen branch maken, als die deze nog niet had.

Succes & veel plezier!
