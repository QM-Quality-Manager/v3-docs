---
title: "Skjemaer"
linkTitle: "Skjemaer"
date: 2017-01-06
description: >
  Skjemaer er en arkfane under admin
---
Her administreres virksomhetens sjekklister, risikoanalyser, spørreskjemaer og meldingsskjemaer

### Arkfaner

- Sjekklister: Viser en oversikt over alle tilgjenglige sjekklister.
- Risikoanalyser: Viser en oversikt over alle tilgjenglige risikoanalyser.
- Meldingsskjemaer: Viser en oversikt over alle tilgjenglige meldingsskjemaer.
- Spørreskjemaer: Viser en oversikt over alle tilgjenglige spørreskjemaer.

### Meldingsskjema
Et meldingsskjema brukes til å registrere meldinger i Qm+. Meldingsskjemaet skiller seg fra en liste ved at det kan brukes når som helst, så mange ganger brukeren har behov for det. Når et meldingsskjema er laget er det automatisk tilgjengelig for alle brukere fra og med avdelingen det ble opprettet på med mindre roller er brukt for å begrense tilgjengeligheten.

Et meldingsskjema kan ha et ubegrenset antall avkryssningsfelter, nedfallsmenyer og tekstfelter. Avkryssningsfeltene og nedfallsmenyene bygges opp av kategorier.

Meldingsskjemaer vedlikeholdes i endre meldingsskjema.

### Data

- Vis for språket: Brukes for å velge språket navnet på meldingsskjemaet skal redigeres for. Vises bare for kunder som har flere aktive språk.
- Skjemanavn: Brukes til å identifisere meldingsskjemaet i tabeller og lister.
- Tekst til knapp: Vises på knappen eller i nedfallsmenyen for de brukerne som skal registrere en ny melding.
- Fra avdeling: Meldingsskjemaet er tilgjengelig fra denne avdelingen.
- Skjematype: Melding, Risiko eller Log. Vises kun dersom Risiko eller Log er aktivert for denne virksomheten.
- Anonym: Alle meldinger som blir registrert anonymt vil inneholde nn istedenfor navnet på brukeren som registrerte den. Et meldingsskjema kan være:
  - Ikke anonymt, standard (Anonym: Nei).
  - Anonymt (Anonym: Ja).
  - Ha avkryssningsboks for anonymitet som starter ikke avkrysset (Anonym: Brukervalgt, standard nei).
  - Ha avkryssningsboks for anonymitet som starter avkrysset (Anonym: Brukervalgt, standard ja).
- Informasjon: Informativ tekst om meldingsskjemaet. Vises når brukeren holder pekeren over knappen eller nedfallsmenyen når ny melding skal registreres. Vises også øverst i meldingsskjemaet.
- Kategorier: Et ubegrenset antall kategorier kan tilknyttes et meldingsskjema. Blir avkryssningsfelter eller nedfallsmenyer i meldingsskjemaet. Dette redigeres under undermenyen Kategorier i endre meldingsskjema. Alle avkryssede kategorier i en melding blir oppsummert i grafene under Rapporter.
- Dokumenter: Et ubegrenset antall dokumenter kan tilknyttes et meldingsskjema. Vises øverst i meldingsskjemaet med en blå tekstlinje per dokument.
- Roller: Et ubegrenset antall roller kan tilknyttes et meldingsskjema. En bruker må ha en av rollene som er tilknyttet et meldingsskjema for å kunne registrere en melding med det. Dersom meldingsskjemaet ikke har roller vil det være tilgjengelig for alle.
- Tekstfelter: Brukes til å skrive inn tekst i meldingen. Maks lengde 5000 tegn per felt.
- Kostnadsfelter: Det kan være fra null til to i et meldingsskjema. Det første feltet vil bli brukt i kostnadsgrafen under Rapporter og er opprinnelig tenkt å symbolisere feilkostnaden. Kundene står selvfølgelig fritt til å bruke også disse feltene slik de selv ønsker.

### Dokumenter undermeny meldingsskjema
{{< onlystaticimg src="/images/Link.png" >}} Dokumenter undermeny meldingsskjema er en arkfane under endre meldingsskjema.

Denne siden brukes for å administrere dokumentene i meldingsskjemaet.

#### Legg dokumenter til skjemaet

- Dokumentarkfane: Valg av dokumentarkfane. Kun dokumenter tilhørende dokumentarkfanen valgt her vises i valgboksen under.
- Dokument: Velg dokumentet du vil legge til meldingsskjemaet og trykk deretter på knappen {{< onlystaticimg src="/images/Link_add.png" >}} Legg til. Hvis du vil fjerne et dokument fra meldingsskjemaet, trykk på det tilhørende slettikonet {{< onlystaticimg src="/images/Page_white_delete.png" >}}.
