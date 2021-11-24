Isotop Arbetsprov
===============================
Forka detta projekt och bygg en app med teknikerna Android (Kotlin), iOS (Swift) eller Flutter, där man kan skriva in namnet på en stad och som visar vilket väder det är där.

Resultaten av sökningarna ska visas och man ska även kunna ta bort dom.

## Kravspecifikation
*	Om temperaturen är 20 grader och uppåt ska kortet vara rött
* Om temperaturen är mellan 1 och 19 grader ska kortet vara gult
* Om temperaturen är 0 grader och nedåt ska kortet vara blått
* Om det regnar ska kortet vara blått oavsett temperatur
* Om staden du söker på inte ger något svar från API:et ska meddelandet "Det finns ingen stad som matchar din sökning" visas under input-fältet
* Hitta en ikon i Figma-dokumentet som matchar resultatet av sökningen. Använd ×-ikonen som fallback.

### Extrabeställning (om det blir tid över)
* Trevliga animationer
* Resultaten ska sorteras efter hur nära användern är platsen (mha GPS)
* Resultaten ska sparas på mobilen, så att när appen öppnas visas tidigare sökningar
* Resultaten ska automatiskt uppdateras en gång i timmen (och varje gång appen öppnas)
* Anpassa appen för landscape och surfplattor

## Design
I Figma kan du exportera ikoner och liknande som SVG.
* [Designdokument](https://www.figma.com/file/iDOGMdsvp7WAR0g5spLcno/Arbetsprov?node-id=1%3A675)

## Resurser:
* Väder-API - https://weatherstack.com/
* Typsnitt Roboto - https://fonts.google.com/specimen/Roboto

## Vad letar vi efter?
* Vi vill få en känsla av hur du tar dig an problem och hur du strukturerar din kod

## Redo att skicka in?
Gör en pull request med din lösning till detta repo och meddela din kontaktperson på Isotop. Vi bokar sedan in ett möte där vi tillsammans går igenom provet med dig.

![Design](https://raw.githubusercontent.com/isotopsweden/Arbetsprov-FE/main/mobile.png)
