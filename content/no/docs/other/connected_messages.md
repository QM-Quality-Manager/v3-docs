---
title: "Tilknyttede meldinger"
linkTitle: "Tilknyttede meldinger"
date: 2017-01-06
description: >
  Alle arkfaner for lister.
---
Tilknyttede meldinger er en arkfane under {{< onlystaticimg src="/images/Table_edit.png" >}} Innboks og {{< onlystaticimg src="/images/Book.png" >}} Arkiv.

Denne siden brukes til å få oversikt over de meldingene som er tilknytett dette tiltaket. Flere meldinger kan kobles til eller kobles fra tiltaket. Godkjente tiltak kan ikke kobles til flere meldinger eller kobles fra meldinger. 

### Meldinger tilknyttet dette tiltaket

Tabell som vise meldinger tilknyttet dette tiltaket. Det må alltid være minst en melding tilkoblet et tiltak.

- Hold pekeren over + symbolet i første kolonne for å få opp mer informasjon om en melding.
- Trykk på {{< onlystaticimg src="/images/Application_form_magnify.png" >}} i siste kolonne for å åpne en melding.
- Trykk på {{< onlystaticimg src="/images/Application_form_delete.png" >}} for å koble en melding fra tiltaket.

### Meldinger som ikke er lukket

Tabell som vise åpne meldinger som ikke er tilknyttet dette tiltaket. Over tabellen er det litt søkefunksjonalitet slik at ikke alle åpne meldinger vises samtidig.

- Valg av kategorigruppe: Her velges hvilket kriterie som skal være likt meldinger allerede tilkoblet tiltaket for å bli vist i tabellen under.
  - Definerende kategori: Meldingen må ha krysset av for samme definerende kategori.
  - <Navn på kategorigruppe>: Meldingen må ha krysset av for samme kategori i den valgte kategorigruppen.
  - En eller annen kategori: Meldingen må ha krysset av for samme kategori i minst en kategorigruppe.
  - Aktivitet: Meldingen må være kommentarmelding til samme aktivitet.
  - Listeelement: Meldingen må være kommentarmelding til samme spørsmål.
- Ta med meldinger fra denne og underliggende avdelinger
  - Ja: Meldinger fra fra denne og underliggende avdelinger blir med.
  - Nei: Kun meldinger fra fra denne avdelingen blir med.
- Utfør søk: Trykk på denne når du har gjordt valgene i feltene over for å oppdatere tabellen under.
- Hold pekeren over + symbolet i første kolonne for å få opp mer informasjon om en melding.
- Trykk på {{< onlystaticimg src="/images/Application_form_magnify.png" >}} i siste kolonne for å åpne en melding.
- Trykk på {{< onlystaticimg src="/images/Application_form_add.png" >}} for å koble en melding til tiltaket.

### Knapper

- Tiltaksbehandling: Åpner Tiltaksbehandling
- Slett tiltak

Knapp som kun synes for brukere med systemrollen innholdsadministrator. Kobler alle meldinger fra dette tiltaket og sletter tiltaket. Meldinger koblet til andre åpne tiltak får status tiltaksprosess. Meldinger kun koblet til andre godkjente tiltak får status lukket. Meldinger ikke koblet til andre tiltak får status Ny.

### Arkfaner

- Endre melding: Åpner Endre melding
- Meldingsbehandling: Åpner Meldingsbehandling
- Tiltaksbehandling: Laster dette skjermbildet på nytt.
