---
title: "Grafer for listen"
linkTitle: "Grafer for listen"
date: 2017-01-06
description: >
 Funksjon under Aktivitetsplan for å vise resultatet av aktiviteter.
---
Ved å bruke Listeresultater kan resultatet fra flere aktiviteter som benytter samme liste vises og sammenlignes i samme bilde.

### Felter
- Overskrift: Sier hvilken liste som er brukt i aktiviteten. Trykk på denne for å vise kommentarer til aktiviteten for alle aktivitetene som er vist i denne siden.

- Aktiviteter vist i disse grafene: Liste over alle aktiviteter som inngår i grafene nedenfor. Vil kun være en med mindre man har brukt Listeresultater. Trykk på denne for å vise kommentarer til aktiviteten for den valgte aktiviteten.

### Nedfallsmenyer
- Avdelingsvalg:
  - Fordelt på denne og underliggende avdelinger: Det blir vist en blå graf for resultatet fra den avdelingen som er valgt i navigatoren og en oransj graf for summen resultatene fra avdelingene under den valgte avdelingen.
  - Totalt for denne og underliggende avdelinger: Det blir vist en blå graf som er summen av resultatene i den valgte avdelingen og dens underliggende avdelinger.

- Graftype:
  - Vist som antall: Grafen viser resultatet som antall svar.
  - Vist i prosent: Grafen viser resultatet som en prosentandel av det totale antall besvarelser for det enkelte spørsmål. Hvis fordelt på denne og underliggende avdelinger er valgt, regnes det en prosentsats for den valgte avdelingen og en prosentsats for de underliggende avdelingene.
    - For spørreskjemaer regnes prosentsatsen for hvert svaralternativ utifra hvor mange som har besvart hvert enkelt spørsmål.
    - For sjekklister regnes prosentsatsen utifra alle som har besvart listen. Blanke svar er også med her.
  - Vis som gjennomsnitt: Viser gjennomsnittsverdier for svarene. Dersom svaralternativene begynner med et tall, så skal det tallet brukes som vekting, hvis ikke får det første alternativet verdi 1, det neste 2 osv. Alternativer som begynner med tallet 0 regnes ikke med i snittverdien, hverken i summen eller for antall besvarelser det deles på. For alternativer som begynner med et tall vil snittverdien bli det utregnede tallet. For andre alternativer, vil det bli teksten på det alternativet som har indeks nærmest det utregnede tallet.

### Graf
Grafenes utseende avhenger av listetype.

- Sjekklister får en graf per spørsmål.

- Risikoanalyser har en total risikomatrise over listen med spørsmål. En ekstra nedfallsmeny "Vis grafen" styrer om siden bruker antall eller gjennomsnittsvisning.
  - Antall: Totalmatrisen viser antall svar på spørsmålene i listen som faller innenfor hvert risikoområde. Hvert spørsmål i listen får en egen risikomatrise som viser fordelingen av svarene til det aktuelle spørsmålet. Til høyre for hver risikomatrise ligger the en tabell som viser fordelingen av svar til det aktuelle spørsmålet innenfor hver risikogruppe (rød,gul,grønn). Antall er forhåndsvalgt når man først åpner siden.
  - Gjennomsnitt: Totalmatrisen viser oversikt over antall spørsmål fordelt etter gjennomsnittsverdien av svarene til hvert spørsmål. Hvert spørsmål får to grafer som viser gjennomsnittsverdien for svar avgitt av brukere i avdelingen valgt i navigatoren (blått) og gjennomsnittsverdien for svar avgitt av brukere i avdelingen valgt i navigatoren (oransj).

- Spørreskjemaer får en graf per svaralternativ.

### Klikkfunksjonalitet
- Alle spørsmålene i listen kan trykkes på. Da får man opp kommentarer til aktiviteten for det valgte spørsmålet. Det gjør man også ved å trykke på {{< onlystaticimg src="/images/Folder.png" >}} ikonet.

- Klikk på aktivitetsnavnet eller det tilhørende {{< onlystaticimg src="/images/Folder.png" >}} ikonet viser kommentarer til aktiviteten for den valgte aktiviteten.

- Klikk på listenavnet viser kommentarer til aktiviteten for alle aktiviteter i grafen. Normalt er det kun en aktivitet i grafen, men ved å bruke listeresultater kan man lage grafer som inneholder resultater fra flere aktiviteter samtidig.
- Alle grafer i tabellen kan trykkes på. Dette åpner brukere som har svart på elementet for det valgte spørsmålet.

### Knapper
- {{< onlystaticimg src="/images/Key_add.png" >}} Vis / {{< onlystaticimg src="/images/Key_delete.png" >}} Skjul resultatfilter: Viser eller skjuler resultatfilteret.
  - Når resultatfilteret er aktivisert kan man krysse av for de spørsmålene eller svaralternativer man vil filtrere på.
  - Kun besvarelser som tilfredsstiller alle avkryssningene vil være med i grafen etter at knappen Vis valgte resultater benyttes.
  - Resultatfilteret påvirker også hva som vises i kommentarer til aktiviteten og brukere som har svart på elementet.
  - Åpner også mulighet for å filtrere resultatet på en rolle tilknyttet den som har svart.
  - Om man velger en rolle i nedfallsmenyen, vil kun de brukerne som har den valgte rollen tilknyttet sin bruker, brukertype eller den avdelingen svaret er registrert på være med i resultatet.

- {{< onlystaticimg src="/images/Email_edit.png" >}} Send resultat: Åpner Send resultat for å publisere den grafen man ser på til andre.

- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Vis som pdf: Skriver ut den aktive siden som .pdf fil.

- {{< onlystaticimg src="/images/Cross.png" >}} Lukk: Returnerer deg til siden du åpnet denne siden fra.

- {{< onlystaticimg src="/images/Printer.png" >}} Skriv ut: Skriver ut den aktive siden. Pass på at Skriv ut bakgrunnsfarger og bilder er krysset av i Alternativer for Internett / Avansert / Utskrift om du bruker Internet Explorer, Fil / Sideoppsett / Skriv ut bakgrunn (farger og bilder) i Mozilla Firefox. Hvis ikke blir ikke grafstolpene med i utskriften. Mozilla Firefox har i noen tilfeller problemer med å skrive ut skjermbilder som går over flere sider. Dette kan være avhengig av oppsett, men ser ut til å være et utbredt problem.

- {{< onlystaticimg src="/images/Help.png" >}} Hjelp: Åpner denne siden.

### Tiltak
For å lage tiltak til en aktivitet har man flere muligheter fra dette bildet.

- Åpne kommentarer til aktiviteten ved å trykke på et spørsmål, tittelen på aktiviteten eller tittelen for listen. Dette vil knytte tiltaket til de kommentarmeldingene som vises i denne siden. Dersom det ikke er noen kommentarmeldinger, vil tiltaket likevel knyttes til spørsmålet eller listen avhengig av hva man trykket på.

- Åpne brukere som har svart på elementet ved å trykke på en graf. Dette gjør man om man vil lage et tiltak for de som har gitt et bestemt svar på et spørsmål.

Hvilken side du går til, vil påvirke hva tiltaket tilknyttes. Så hva som er rett avhenger av om man ønsker at det skal være felles for hele listen, tilknyttes et enkelt spørsmål eller til et svaralternativ.