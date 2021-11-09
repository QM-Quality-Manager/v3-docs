---
title: "Arkfaner"
linkTitle: "Arkfaner"
date: 2017-01-06
description: >
  Alle arkfaner for meldinger.
---
# Regler undermeny meldingsskjema
{{< onlystaticimg src="/images/Wrench.png" >}} Regler undermeny meldingsskjema er en arkfane under endre meldingsskjema.

Denne siden brukes for å få en oversikt over hvilke regler som er tilknytte dette meldingsskjemaet.

En melding registrert med et meldingsskjema uten saksbehandlere følger normal saksgang og blir vist i Innboks/Mine saker for nærmeste leder. Dette er i de fleste tilfeller den beste løsningen. 

# Dialog
Dialog er en arkfane for å sende tilbakemeldinger til den som er ansvarlig for å behandle meldingen.
Felter

- Status: Meldingens status og hvem som er ansvarlig for den vises øverst i siden.
- Tilbakemelding til saksbehandler: Her kan en tekst skrives inn og sendes på e-post. Tekster som sendes slik blir også registret på saken og vil følge den. Den vil vises i dette bildet i tabellen nedenfor.
- Send epost til: Velg den som skal motta meldingen. Listen er sortert etter avdeling og inneholder:
  - Nærmeste leder(e) vises alltid.
  - Aktuell saksbehandler for den valgte meldingen, dersom en behandler er satt.
  - Enhver som har sendt en melding til den påloggede brukeren om den aktuelle saken.
- Tabell som viser tidligere kommunikasjon om denne saken.

# {{< onlystaticimg src="/images/Map.png" >}} GPS-koordinater er en arkfane under endre meldingsskjema.

Meldinger registrert gjennom den mobile applikasjonen sender GPS-koordinatene til beliggenhet av den mobile enheten på tidspunktet for registrering. Bruk denne siden til å avgjøre om disse koordinatene vil vises i meldingsbehandlingsiden og i pdf-rapporter. Flere alternativer vil dukke opp på denne siden snart. 

# Roller undermeny meldingsskjema
{{< onlystaticimg src="/images/Group.png" >}} Roller undermeny meldingsskjema er en arkfane under endre meldingsskjema.

Denne siden brukes når man ønsker å lage restriksjoner for registrering av nye meldinger eller for å se eksisterende meldinger. For å legge på en restriksjon, krysser man av for ønsket rolle, under ønsket restriksjonstype. Det er to avkryssingsmuligheter per rolle, en per restriksjonstype. Det kontrolleres i begge tilfeller om brukeren har denne rollen i sin brukertype eller på sin bruker. Dersom det krysses av for flere roller, så holder det at man har en av dem for å oppfylle kravet. Meldingsskjemaer uten roller har ingen ekstra restriksjoner og kan brukes som normalt.

### Restriksjonstyper

- Ny melding. Skjuler knappen for å registrere nye meldinger med dette meldingsskjemaet.
- Se meldinger og grafer. Skjuler meldinger registrert med dette meldingsskjemaet i Rapporter, Innboks og Arkiv.

# Sendt til saksbehandler
Arkfane under Meldinger/UH

Sendt til saksbehandler viser alle meldinger som er overført til en ansvarlig person. Dette brukes til å finne igjen meldinger man har sendt avgårde slik at de ikke lenger tilgjengelig på egen avdeling. Hvilke meldinger som vises i tabellen nedenfor avgjøres av valgene i nedfallsmenyene. Kun meldinger registrert de siste 3 måneder vises i dette bildet. For eldre meldinger benytt Rapporter eller søk. 

### Funksjoner

#### Nedfallsmenyer

- Alle meldinger: Velg et meldingsskjema og kun meldinger med opprinnelse i et slikt meldingsskjema vises.
- Meldingstype:
  - Fra saksbehandler på denne avdelingen: Viser meldinger sendt fra en bruker på den avdelingen som er valgt i navigatoren.
  - Fra meg: Viser meldinger sendt av den påloggede brukeren.
  - Til saksbehandler på denne avdelingen: Viser meldinger som har fått tilordnet en ansvarlig person fra den avdelingen som er valgt i navigatoren.
  - Registrert på denne avdelingen: Viser meldinger som opprinnelig er registrert på den avdelingen som er valgt i navigatoren.
- Status: Kun meldinger med den valgte status vises i tabellen.
  - Alle status: Alle meldinger vises.
  - Meldingsprosess: Kun meldinger med status Ny eller Sendt til saksbehandler vises.
  - Tiltaksprosess: Kun meldinger tilkoblet et tiltak som ikke er godkjent vises.
  - Avvist: Kun avviste meldinger vises.

#### Aktiv tabell

- Ved å trykke på en linje i hovedtabellen vil meldingen åpnes i behandlingsbildet.
- Hold pekeren over + symbolet i første kolonne for å få opp mer informasjon om en melding inkludert historikken.

#### Knapper

- {{< onlystaticimg src="/images/Page.png" >}} Utvidet visning / {{< onlystaticimg src="/images/Page_white_acrobat.png" >}}Table.png Tabell: Skift mellom tabell og utvidet visning. Tabellen gir en kompakt beskrivelse av meldingene beregnet til bruk når man jobber med dem. Utvidet visning gir en mer fullstendig beskrivelse av hele meldingen beregnet til bruk når man vil se en oversikt over hele innholdet i meldingene.
- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Vis som pdf: Åpner Alternativer for rapporter som gir mulighet til å lage en rapport i et pdfdokument. Denne er beregnet på utskrift til papir.
- Sideskift: Pilene {{< onlystaticimg src="/images/LeftArrow.gif" >}} og {{< onlystaticimg src="/images/RightArrow.gif" >}} brukes til å skifte side når det er mer enn 20 meldinger som kan vises i tabellen.
- Sortering: Tabellen er sortert etter kolonnen med {{< onlystaticimg src="/images/Arrowopen.gif" >}}. Trykk på {{< onlystaticimg src="/images/Arrowclosed.gif" >}} for å sortere på en annen kolonne.
- {{< onlystaticimg src="/images/Printer.png" >}} Skriv ut: Skriver ut det skjermbildet som vises på skjermen.
- {{< onlystaticimg src="/images/Help.png" >}} Hjelp: Åpner denne siden.

# Skjemadata
{{< onlystaticimg src="/images/Page_edit.png" >}} Skjemadata er en arkfane under endre meldingsskjema.

Denne siden brukes for å administrere meldingsskjemadataene.

### Felter

- Vis for språket: Tekstfeltene i et meldingsskjema som skjemanavn og tekst til knapp kan lagres en gang per språk som er aktivisert i systemet.
- Skjemanavn: Identifiserer meldingsskjemaet i tabeller og oversikter.
- Tekst til knapp: Identifiserer meldingsskjemaet på knappen eller i nedfallsmenyen i Innboks og Arkiv.
- Fra avdeling: Meldingsskjemaet er tilgjengelig fra og med denne avdelingen.
- Skjematype: Meldingsskjemaets type. Enten melding, log eller risiko. Vises kun dersom meldingstypene log eller risiko er aktivisert.
- Anonym: Alle meldinger som blir registrert anonymt vil inneholde nn istedenfor navnet på brukeren som registrerte den. Et meldingsskjema kan være:
  - Ikke anonymt, standard (Anonym: Nei).
  - Anonymt (Anonym: Ja).
  - Ha avkryssningsboks for anonymitet som starter ikke avkrysset (Anonym: Brukervalgt, standard nei).
  - Ha avkryssningsboks for anonymitet som starter avkrysset (Anonym: Brukervalgt, standard ja).
- Informasjon: Tekst som vises når pekeren holdes over knappen eller i nedfallsmenyen i Innboks og Arkiv. Denne teksten vises også øverst i meldingsskjemaet når meldingen registreres i endre meldingskjermbildet.
