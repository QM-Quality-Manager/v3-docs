---
title: "Risiko"
linkTitle: "Risiko"
date: 2017-01-06
description: >
 Risiko er en arkfane på Hovedsiden.
---
Vises kun for de virksomhetene som har aktivisert Risikomeldingsmodulen for de brukerne som har systemrollen Risiko. Hensikten er å vise risikobildet for virksomheten akurat nå.

Risiko inneholder alle risikomeldinger i systemet fra avdelinger som er aktive. Risikomeldinger er meldinger som brukes for å lage en risikooversikt for virksomheten. Det er opp til virksomheten om risikomeldingene skal behandles eller om de kun skal registreres og lagres i arkivet. Vår anbefaling er at de ikke behandles, kun oppdateres årlig. Meldinger registrert her dukker ikke opp i Innboks med mindre man bruker behandling for å aktivere dem. Meldingstypen risikomelding er ikke aktivert i standardversjonen.

Ved søk enten fra Rapporter, Søk for meldinger eller ved trykk i risikomatrisen vises det over resultattabellen en oversikt over de søkekriteriene som er satt for søket. 

### Risikomatrise

Risikomatrisen gir et risikobilde for den valgte delen av virksomheten. Tallene i matrisen viser hvor mange av meldingene i tabellen nedenfor som har risikokategorier med verdier tilsvarende feltet i risikomatrisen.

- Tallene i risikomatrisen viser kun kategorier fra meldinger i tabellen under.
- Navigatoren brukes for å sette startavdeling for risikooversikten.
- Trykk på et felt i risikomatrisen for å se på kun de meldingene som har kategorier i dette feltet. Dette utføres som et søk og skifter arkfane. Risikofeltet i søkekriteriene viser hvilket felt du trykket på.
- Meldinger med kun verdien 0 for alle sine risikokategorier vises ikke i risikomatrisen.

### Nedfallsmenyer

Ikke med i forenklet grensesnitt.

- Avdelingsvalg:
  - Denne avdelingen: Kun meldinger registrert på avdelingen valgt i navigatoren vises.
  - Denne og underliggende avdelinger: Alle meldinger registrert fra og med avdelingen valgt i navigatoren vises.
  - Kun underliggende avdelinger: Kun meldinger registrert på avdelingen under avdelingen valgt i navigatoren vises.
- Visningstype:
  - Totalt: Det vises en risikomatrise for det samlede resultat av alle risikokategorier for meldingene i tabellen.
  - Per kategori: Det vises en risikomatrise for hver risikokategori som er brukt i meldingene i tabellen.
        Individuell: Det vises en risikomatrise for den risikokategorien som er valgt i risikokategori nedfallsmenyen.
- Risikokategori: Vises kun for Visningstypen Individuell. Bestemmer hvilken risikokategori som vises i risikomatrisen. Kun meldinger med en registrert risikoverdi > 0 for den valgte risikokategorien vil bli vist.

### Valg

Ikke med i forenklet grensesnitt.

- Nedfallsmeny Alle meldinger: Velg et meldingsskjema og kun meldinger registrert med dettemeldingsskjema vises. Kun meldingsskjemaer av typen Risiko vises her.
- {{< onlystaticimg src="/images/Calendar_icon.png" >}} Datofelt: Brukes for å sette fra og til dato for meldingene som skal vises i tabellen.

### Aktiv tabell

- Ved å trykke på en linje i hovedtabellen vil meldingen åpnes i endre melding.
- Hold pekeren over + symbolet i første kolonne for å få opp mer informasjon om en melding, inkludert historikken.

### Knapper

- Tilpass kolonner: Brukes til å justere hvilke kolonner som vises.
  - Siden lastes på nytt etter hver endring.
  - Kolonnejusteringene varer til du logger ut.
  - Kolonnejusteringene gjelder også om du eksporterer til PDF som Oversiktstabell.
- {{< onlystaticimg src="/images/Application_form_edit.png" >}} Registrer ny melding: Velg en knapp med navnet på et meldingsskjema for å registrere en ny melding. Kun meldingsskjemaer av typen Risiko vises her.
- {{< onlystaticimg src="/images/Find.png" >}} Søk: Oppdater listen av meldinger til å bli basert på valgt dato.
- {{< onlystaticimg src="/images/Page.png" >}} Utvidet visning/Tabell: Skift mellom tabell og utvidet visning. Tabellen gir en kompakt beskrivelse av meldingene beregnet til bruk når man jobber med dem. Utvidet visning gir en mer fullstendig beskrivelse av hele meldingen beregnet til bruk når man vil se en oversikt over hele innholdet i meldingen.
- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Vis som pdf: Åpner Alternativer for rapporter som gir mulighet til å lage en rapport i et pdfdokument. Denne er beregnet på utskrift til papir.
- {{< onlystaticimg src="/images/LeftArrow.gif" >}} og {{< onlystaticimg src="/images/RightArrow.gif" >}} Sideskift: Pilene brukes til å skifte side når det er mer enn 20 saker som kan vises i tabellen.
- {{< onlystaticimg src="/images/Arrowopen.gif" >}} og {{< onlystaticimg src="/images/Arrowclosed.gif" >}} Sortering: Tabellen er sortert etter kolonnen med {{< onlystaticimg src="/images/Arrowopen.gif" >}}. Trykk på {{< onlystaticimg src="/images/Arrowclosed.gif" >}} for å sortere på en annen kolonne.
- {{< onlystaticimg src="/images/Printer.png" >}} Skriv ut: Skriver ut det skjermbildet som vises på skjermen.
- {{< onlystaticimg src="/images/Help.png" >}} Hjelp: Åpner denne siden.

### Arkfaner

- Risikooversikt: Alle risikomeldinger registrert på den avdelingen som er valgt i navigatoren.
- Søk: Åpner søk for meldinger med skjematype Risiko forhåndsvalgt.
