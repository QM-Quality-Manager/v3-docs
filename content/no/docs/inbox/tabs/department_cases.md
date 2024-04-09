---
title: "Avdelingens saker"
linkTitle: "Avdelingens saker"
date: 2017-01-06
description: >
  Avdelingens saker
---
{{< onlystaticimg src="/images/Chart_organisation.png" >}} Avdelingens saker er en arkfane under {{< onlystaticimg src="/images/Table_edit.png" >}} Innboks

Avdelingens saker viser saker det jobbes med på den avdelingen som er valgt i navigatoren.

Rosa saker er meldinger, gule saker er tiltak og blågrå saker er høringer

### Valg
- {{< onlystaticimg src="/images/Application_form_edit.png" >}} Registrer ny melding: Velg et meldingsskjema for å registrere en ny melding. Åpner endre melding. Meldingsksjemaene vises om individuelle knapper dersom det er 4 eller færre skjemaer. Er det fler, må først knappen Application form add.png Registrer ny melding trykkes på. Den åpner en liste over alle aktive meldingsskjemaer.

- Alle meldinger: Velg et meldingsskjema og kun saker med opprinnelse i et slikt skjema vises

### Ikoner
- {{< onlystaticimg src="/images/LeftArrow.gif" >}} og {{< onlystaticimg src="/images/RightArrow.gif" >}} Sideskift: Pilene brukes til å skifte side når det er mer enn 20 saker som kan vises i tabellen.

- {{< onlystaticimg src="/images/Sort_down.png" >}} og {{< onlystaticimg src="/images/No_sort.png" >}} Sortering: Tabellen er sortert etter kolonnen med {{< onlystaticimg src="/images/Sort_down.png" >}}g. Trykk på {{< onlystaticimg src="/images/No_sort.png" >}} for å sortere på den kolonnen.

- {{< onlystaticimg src="/images/Flag_green.png" >}},{{< onlystaticimg src="/images/Flag_yellow.png" >}},{{< onlystaticimg src="/images/Flag_red.png" >}} symboliserer lav, middels og høy prioritet.

### Hovedtabellen
Ved å trykke på en linje i hovedtabellen vil saken åpnes i sitt behandlingsbilde. Meldinger åpnes i meldingsbehandlingsbildet, tiltak åpnes i tilltaksbehandlingsbildet og høringer åpnes i besvar høring.

- \+ Utvidet informasjon og historikk: Hold pekeren over denne til å få opp utvidet informasjon om saken. Foreløpig kun meldinger og tiltak.

- Meldingsskjema: Hvilket meldingsskjema saken er opprettet med.

- Registrert: Dato for når saken ble registrert. For meldinger når den ble registrert, for tiltak når det ble opprettet.

- Frist: For meldinger behandlingsfrist, for tiltak gjennomføringsfrist og godkjenningsfrist.

- Beskrivelse: For meldinger teksten i det første tekstfeltet i meldingen, for tiltak navnet.

- Prioritet: Fargekodet prioritet. For tiltak gjelder prioriteten til den tilkoblede meldingen som er høyest.

- Status: Sakens status.

- Registrert på avdeling: Avdelingen saken er registrert på.

- Saken ligger nå hos: Avhenger av sakens type og status.
  - Meldinger:
    - Blank: Saken er registeret på denne avdelingen og er ikke tilordnet en ansvarlig.
    - <Navn på bruker>: Den navngitte brukeren er tilordnet som ansvarlig for saken.
  - Tiltak:
    - Med status <<Under planlegging>>: Navnet på den brukeren som har opprettet tiltaket og er overordnet ansvarlig for det.
    - Med status <<Under gjennomføring>>: Navnene på de brukerne som skal gjennomføre tiltaket.
    - Med status <<Under godkjenning>>: Navnet på den brukeren som har opprettet tiltaket og er ansvarlig for å godkjenne det.
  - Høring:
    - Med status <<Ute på høring>>: Navnene på de brukerne som skal delta i høringen.
    - Med status <<Til godkjenning>>: Navnet på den brukeren som skal godkjenne høringen.

### Hvilke saker vises i tabellen?
- Meldinger som er sendt til en bruker i den valgte avdelingen via Send til saksbehandler i Behandlingsbildet eller via tidlig saksbehandling i Endre melding.

- For ledere:
	- Meldinger registrert på valgt avdling hvis den har en lederen, som ikke har fått tilordnet en annen ansvarlig person.
	- Meldinger registrert på en underliggende avdlingen, hvor det ikke er en egen leder som ikke har fått tilordnet en annen ansvarlig person. Meldinger registrert på avdelinger uten leder vil flyte oppover i organisasjonen og vises i Innboks på den første overliggende avdelingen som har en leder.

- Tiltak under planlegging opprettet av en bruker på avdelingen.

- Tiltak under gjennomføring som skal utføres av en bruker på avdelingen.

- Tiltak under godkjenning som skal godkjennes av en bruker på avdelingen.

- Høringer som er ute til høring der en bruker på avdelingen skal delta.

- Høringer som er til godkjenning der en bruker på avdelingen skal godkjenne den.

Merk at meldinger andre brukere har registrert som er laget med meldingsskjemaer som har en rolle med "Se meldinger" begrensning, ikke blir vist her med mindre den påloggede brukeren har den samme rollen eller Systemrollen Se alle meldinger tilknyttet seg eller den brukertypen brukeren er logget på med. Meldinger brukeren selv har registrert blir vist.