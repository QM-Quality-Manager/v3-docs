---
title: "Felter undermeny meldingsskjema"
linkTitle: "Felter undermeny meldingsskjema"
date: 2017-01-06
description: >
 Felter undermeny meldingsskjema er en arkfane under endre meldingsskjema. 
---
Denne siden brukes for å administrere tekst- og kostnadsfeltene i meldingsskjemaet. 

### Tekstfelter

Et meldingsskjema kan ha 0 eller så mange tekstfelter det ønskes.

- Feltnavn: Navn over feltet i meldingsskjemaet.
- Skjult: Kryss av hvis feltet skal være skjult. Innholdet i skjulte tekstfelter vises kun i endre meldingsbildet for den som har registrert meldingen eller bruker med systemrollen Tilgang til skjulte tekstfelter og samtidig er satt som meldingens saksbehandler. I standardversjonen har brukertypen leder den Systemrollen.
  - Er Tilgang til skjulte tekstfelter tilknyttet brukertypen gis tilgang kun om brukeren er saksbehandler for den aktuelle meldingen.
  - Er Tilgang til skjulte tekstfelter tilknyttet brukeren gis tilgang uansett melding.

I alle andre skjermbilder blir innholdet kun vist som -- skjult tekstfelt --.

- Obligatorisk: Kryss av dersom tekstfeltet skal være obligatorisk. Det betyr at feltet må ha innhold for at meldingen skal kunne lagres.
- Rader: Hvor mange rader tekstfeltet skal ha.
- Kolonner: Hvor mange kolonner tekstfeltet skal ha. 0 brukes for at tekstfeltet skal fylle all tilgjengelig plass.
- {{< onlystaticimg src="/images/Page_white_delete.png" >}} Slette: Trykk på dette ikonet for å slette tekstfeltet.
- {{< onlystaticimg src="/images/Page_white_add.png" >}} Legg til felt: Brukes for å opprette et nytt tekstfelt.

### Kostnadsfelter

Et meldingsskjema kan ha 0, 1 eller 2 kostnadsfelter.

- Feltnavn: Navn over feltet i meldingsskjemaet.
- {{< onlystaticimg src="/images/Page_white_delete.png" >}} Slette: Trykk på dette ikonet for å slette kostnadsfeltet.
- {{< onlystaticimg src="/images/Page_white_add.png" >}} Legg til felt: Brukes for å opprette et nytt kostnadsfelt.
