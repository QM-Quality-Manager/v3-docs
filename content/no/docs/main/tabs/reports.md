---
title: "Rapporter"
linkTitle: "Rapporter"
date: 2017-01-06
description: >
 Rapporter (tidligere kalt Grafer) er en arkfane på Hovedsiden.
---
Brukes for å få grafisk oversikter over aktiviteten i systemet. Nedfallsmenyene og eventuelle søkekriterier styrer hva slags graf du får. Alle grafer kan trykkes på for å åpne den underliggende rapporten. 

### {{< onlystaticimg src="/images/Info.png" >}} Hva kan jeg gjøre her?

- Velg rapporttype i den første nedfallsmenyen. Den viser rapporten Per avdeling som standard.
- Jeg kan se resultatene i hele eller deler av organisasjonen med ett tastetrykk: velg avdeling i Navigatoren.
- Jeg kan justere hvilke grafer som vises ved å klikke på hurtigvalgsknappene over grafbildet, for eksempel "Fordeling over tid",
- eller jeg kan klikke på en farge i grafen og få denne ut som en tabelloversikt,
- eller jeg kan klikke på "Pr. avdeling oversiktstabell" for å hente ut sammenligninger mellom tidsperioder. Denne kan kopieres inn i et Excell-ark.

### {{< onlystaticimg src="/images/64px-Monitor.png" >}} Interaktiv opplæring

**Her kan du lære:**

- Å lage og hente rapporter
- Å få oversikt over avdelingene ved hjelp av grafer
- Graftyper
- Nedfallsmenyer
- Forskjellen på fargene i grafene
- Hvordan du skal lese grafene

Page white acrobat.png pdf

### Knapper

- {{< onlystaticimg src="/images/Printer.png" >}} Skriv ut: Skriver ut det aktive skjermbildet.
- {{< onlystaticimg src="/images/Help.png" >}} Hjelp: Åpner denne siden.
- {{< onlystaticimg src="/images/Report_edit.png" >}} Skriv rapport: Åpner en side under Endre data for dokumentet der man kan skrive et dokument som inneholder alle grafer som var aktivert når man trykket på denne knappen. Kun brukere som har tilgang til å lage dokumenter får opp denne knappen. Grafer i PDF utskrifter og i HTML versjonen av det ferdige rapport dokumentet vil være 600 piksler bredt for å sikkre lesbarheten.

### Arkfaner

Arkfanene Meldinger/UH, Logg, Kommentarer og Risiko gir de samme grafmulighetene for ulike typer meldinger. De kan også brukes til å nullstille søkekriteriene dersom du har utført et søk. Er man i søkemodus vil arkfanen Søk vises som valgt og de søkekriteriene som er satt for søket vises i en egen tabell.

- Meldinger/UH: Meldingsgraf
- Oppdrag: Meldingsgraf. Vises kun hvis oppsjonen for oppdragsmeldinger er aktivert.
- Logg: Meldingsgraf. Vises kun hvis oppsjonen for loggmeldinger er aktivert.
- Risiko: Meldingsgraf. Vises kun hvis oppsjonen for risikomeldinger er aktivert.
- Kommentarer: Meldingsgraf
- Brukere: Gir oversikt over pålogginger og dokumentbruk.
- Søk: Meldingsgraf for søk.

### Nedfallsmenyer
#### Rapporter

Valg av rapporttype
#### UH / Meldingsrapporter

Meldinger/UH er en arkfane under {{< onlystaticimg src="/images/Icon_graph2.png" >}} Rapporter.

Her vises grafer for vanlige meldinger. Hvis du har gjort et søk, kan du trykke på denne arkfanen for å nullstille alle søkekriteriene. 

{{< onlystaticimg src="/images/Graph-search.png" >}}

#### Standardrapport graf

- Viser oversikt over antall registreringer, status, brukte meldingsskjemaer, prioritet, over tid og kategorier, avhengig av hvilke delrapporter det er krysset av for.
- Klikk på enhver graf for å se meldingene som utgjør de bakenforliggende dataene for den aktuelle grafen.

#### Standardrapport tabell

Periodisk rapport som viser en tabelloversikt over de aller fleste meldingsdata summert opp til avdelingen valgt i Navigatoren. Dataene blir listet opp under hverandre fordelt etter tidsperioder. Periodene lages automatisk basert på tidsperioden man har valgt for rapporten. Dette skjer på samme måte som i "Fordeling over tid" grafen. Det er foreløbig ikke noen eksport eller trykk på (drill down) mulighet i denne rapporten. Det er planlagte utvidelser etter hvert.

- Bruk nedfallsmenyen for Periodetype dersom du ønsker annen periodisering enn den automatiske. Dersom tidsrommet du søker på ikke dekker en hel periode, vil siste periode og totalperioden (første kolonne i tabellen) vise et tidsrom som spenner over en hel periode. Det vil likevel ikke være data i rapporten utenfor det tidsrommet du har valgt.

#### Risikooversikt

Viser en risikomatrise for alle meldinger i det aktuelle utvalget som inneholder en kategori fra en kategorigruppe av typen Risiko med risikoverdi > 0.

#### Utregningsrapporter

### Tiltaksrapporter

Tid per tiltak og Timeliste for tiltak vises kun dersom opsjonen for Tidsregistrering på tiltak er aktivert. I alle de tre rapportene, kan man trykke på tiltakenes navn eller nummer for å åpne det aktuelle tiltaket.

#### Tiltaksmatrise

- Rapport som viser status for alle åpne tiltak.
- Fargekodene for status vises over tabellen.
- Trykk på navnet på et tiltak for å åpne det.
- Brukt sammen med opsjonen for starttid felt for tiltak, kan denne oversikten brukes til å vise planlagte tiltak.
- Oversikten starter 3 dager før dagens dato og tar med de neste 26 dagene.
- Overgangen fra dagens dato til datoen for dagen etter markeres med en svart vertikal linje.
- Matrisen er sortert etter tiltakenes startdato, hvis denne er satt. Hvis ikke, brukes datoen tiltakene ble registrert.

#### Tid per tiltak

- Rapporten viser hvor mye tid som er registrert på tiltak i den valgte tidsperioden.
- Tiltak uten registrert tid er ikke med i rapporten.
- Rapporten tar med alle tiltak registrert fra og med valgt avdeling i navigatoren.
- Viser per bruker og total.
- Tiltakene er sortert etter tiltaksnummer.
- Vises kun når opsjonen for tidsregistrering for tiltak er på.

#### Timeliste for tiltak

- Rapporten viser hvor mye tid for valgt periode som er registret på tiltak per bruker per dag.
- Oppsummering per dag per bruker og for alle brukere.
- Vises kun når opsjonen for tidsregistrering for tiltak er på.

### Blandede rapporter
#### Rapport for behandlingstid

Periodisk rapport som viser informasjon om registrerte og behandlede meldinger og tiltak. Denne rapporten tar kun hensyn til valgt tidsperiode og valgt meldingstype. Tallene for Gjennomsnittstid tar kun hensyn til meldinger som har oppnådd aktuell status. De siste periodene i rapporten vil derfor som regel ha lavere tid enn de første, da de siste som regel vil ha flere åpne saker som ikke er med i utregningen.

- Meldinger registrert på.. Viser antall meldinger registrert på avdelingen(e).
- Meldinger ferdigbehandlet i.. Viser antall meldinger ferdigbehandlet (avvist eller tiltak opprettet) i den valgte perioden, uavhengig av hvor og når meldingen er registrert.
- Meldinger lukket i... Viser antall meldinger lukket (avvist eller tiltak godkjent) i avdelingen(e), uavhengig av hvor meldingen er registrert.
- Meldinger avvist i... Viser antall meldinger avvist i avdelingen(e), uavhengig av hvor meldingen er registrert.
- Tiltak opprettet i... Viser antall tiltak opprettet i avdelingen(e).
- Tiltak godkjent i... Viser antall tiltak godkjent i avdelingen(e).
- Ferdigbehandlede meldinger registrert på... Viser hvor mange av meldingene registrert på avdelingen(e) som er ferdig behandlet. Brukes for å regne ut Gjennomsnittlig behandlingstid.
- Lukkede meldinger registrert på... Viser hvor mange av meldingene registrert på avdelingen(e) som er lukket. Brukes for å regne ut Gjennomsnittlig lukketid.
- Avviset meldinger registrert på... Viser hvor mange av meldingene registrert på avdelingen(e) som er avvist.
- Gjennomsnittlig behandlingstid i dager for meldinger registrert på... Tid brukt fra registrering for alle ferdigbehandlede meldinger registrert på avdelingen(e) / Antall ferdigbehandlede meldinger registrert på avdelingen(e).
- Gjennomsnittlig behandlingstid i dager for meldinger behandlet på... Tid brukt fra registrering for alle ferdigbehandlede meldinger behandlet på avdelingen(e) / Antall ferdigbehandlede meldinger behandlet på avdelingen(e).
- Gjennomsnittlig lukketid i dager for meldinger registrert på... Tid brukt fra registrering for alle lukkede meldinger registrert på avdelingen(e) / Antall lukkede meldinger registrert på avdelingen(e).
- Gjennomsnittlig lukketid i dager for meldinger behandlet på... Tid brukt fra registrering for alle lukkede meldinger behandlet på avdelingen(e) / Antall lukkede meldinger behandlet på avdelingen(e).

Bruk nedfallsmenyen for Periodetype dersom du ønsker annen periodisering enn den automatiske. Dersom tidsrommet du søker på ikke dekker en hel periode, vil siste periode og totalperioden (første kolonne i tabellen) vise et tidsrom som spenner over en hel periode. Det vil likevel ikke være data i rapporten utenfor det tidsrommet du har valgt.

Merk:

- Meldinger som ennå ikke er lukket kan inngå i oversikten for behandlingstid uten å være med i oversikten for lukketid. Dermed er det mulig å ha lengre behandlingstid enn lukketid.
- For behandlingstid brukes kun den siste avdelingen meldingen er sendt til - aktuell avdeling.

### Meldingsskjema

Dersom et spesielt meldingsskjema er valgt her, så vil kun meldinger registrert med det valgte meldingsskjemaet taes med i rapporten.

### Kategorigrupper

Dersom en kategorigruppe velges her, vil kun meldinger med avkryssninger i den valgte kategorigruppen tas med i rapporten.

### Graftyper

Liste over avkryssingsbokser som aktiverer eller deaktiverer den gitt graftypen. Oversikt etter skjemaer, status og prioritet er aktivert som standard. Dette kan endres per kunde etter behov.

- Oversikt etter avdelinger: Viser en samlet oversikt over meldinger registrert i denne avdelingen, det vil si avdelingen valgt i navigatoren og meldinger registrert i underliggende avdelinger.
- Oversikt etter skjemaer: Viser hvilke meldingsskjemaer som har vært i bruk. Denne grafen skjules dersom et meldingsskjema er valgt i nedfallsmenyen over.
- Oversikt etter status: Viser hvilken status meldingene har.
- Oversikt etter prioritet: Viser meldingenes prioritet.
- Fordeling over tid: Vise når meldingene er registrert. Tidsaksen endres med lengden på perioden som er valgt. Mulige skalaer: dager, uker, måneder og år.
- Oversikt etter kategorier: Viser en graf per kategorigruppe det er gjort registreringer med.
- Oversikt etter brukere: Vises ikke i standardversjonen. Viser hvor mange meldinger brukerne på den valgte avdelingen har registrert. Brukere registrert på en annen avdeling som har gjordt registeringer på den valgte avdelingen vises også. Meldinger rapportert anonymt er utelatt i denne grafen.
- Dynamiske grafer: Alle grafer definert i Admin / Regler / Oppsett for dynamiske grafer vises her. Dette er grafer den lokal systemadministratoren sette opp og bestemme hvilke verdier som vises for Y-aksen og for X-aksen.

### Grafene

Hver graf har et sett med avkryssingsfelter som styrer hva de inneholder og hva slags graf som vises.

- Bytt akser: Bytter om hvilke data som vises som x og som y akse i grafen.

- Vis total: Vises bare for kategorigrafer.
  - Avkrysset: Den første delen av stolpen inneholder den summerte totalverdiene for de etterfølgende stolpene i samme linje. De etterfølgende delene av diagrammet viser summen fra og med den navngitte avdelingen. Brukes dersom man for eksempel vil ha ut alle meldinger i hele virksomheten hvor en gitt kategori er avkrysset.
  - Ikke avkrysset: Første del av stolpen viser kun registreringer i avdelingen valgt i navigatoren. De etterfølgende delene av diagrammet viser også her summen fra og med den navngitte avdelingen.

- Antall meldinger: Grafen som viser antall meldinger vises. Er standard forhåndsvalgt for alle grafer, untatt kategorigrafer for kategorigrupper av typen tall.

- Sum: Vises kun for kategorigrupper av typen tall. Er forhåndsvalgt for disse. Denne typen kategorigrupper besvares med et tall istedet for en avkryssing. Denne grafen viser summen av disse tallene for alle meldinger som inngår i rapporten.

- Prosentgraf: Viser prosentvis fordeling.
  - For andre grafer enn kategorigrafene betyr det at antallgrafen blir skalert til 100.
  - For kategorigrafen vises prosentvis fordeling av meldinger for hver avdeling per kategori innenfor hver kategorigruppe. Hver avdeling summerer i denne grafen opp til 100%, så noen stolper kan gå langt over 100. I det tilfellet, kan grafen være lettere å lese om aksene byttes. Bruk Bytt akser for å gjøre det.
  - For prosentgrafen vises resultatet aggregert opp til underavdelingene, mens resultatet for valgt avdeling vises separat. Dette for at ikke hele resultatet skal vises flere ganger, noe som ikke ser forståelig ut i standardformatet (uten bytt akser).

- Kostnadsgraf: Viser summen av kostnadsfeltet i meldingene grafen inneholder.
