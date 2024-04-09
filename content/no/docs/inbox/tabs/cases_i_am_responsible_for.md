---
title: "Saker jeg er ansvarlig for"
linkTitle: "Saker jeg er ansvarlig for"
date: 2017-01-06
description: >
  Saker jeg er ansvarlig for er en arkfane under Innboks
---
Saker jeg er ansvarlig for viser saker den påloggede brukeren skal jobbe med, uavhengig av avdeling valgt i navigatoren. Arkfanen vises ikke dersom brukeren hverken kan behandle meldinger, utføre tiltak, delta i høringer eller gjennomføre revisjoner.

Rosa saker er meldinger, gule saker er tiltak, blågrå saker er høringer. Varseler om revisjon er fargeløse. 

### Valg

- {{< onlystaticimg src="/images/Application_form_edit.png" >}} Registrer ny melding: Velg et meldingsskjema for å registrere en ny melding. Åpner endre melding. Meldingskjemaene vises om individuelle knapper dersom det er 4 eller færre skjemaer. Er det fler, må først knappen {{< onlystaticimg src="/images/Application_form_add.png" >}} Registrer ny melding trykkes på. Den åpner en liste over alle aktive meldingsskjemaer.

- Alle meldinger: Velg et meldingsskjema og kun saker med opprinnelse i et slikt skjema vises

- Saker jeg er ansvarlig for / Alle saker jeg har vært involvert i: Saker jeg er ansvarlig viser kun saker den påloggede brukeren skal gjøre noe med. Alle saker jeg har vært involvert endrer visningen til å inneholde de sakene den påloggede brukeren har gjort noe med som fremdeles ikke er lukket.

### Ikoner

- {{< onlystaticimg src="/images/Sort_down.png" >}} og {{< onlystaticimg src="/images/No_sort.png" >}} Sortering: Tabellen er sortert etter kolonnen med {{< onlystaticimg src="/images/Sort_down.png" >}}. Trykk på {{< onlystaticimg src="/images/No_sort.png" >}} for å sortere på den kolonnen.
    
- {{< onlystaticimg src="/images/Flag_green.png" >}},{{< onlystaticimg src="/images/Flag_yellow.png" >}},{{< onlystaticimg src="/images/Flag_red.png" >}} Prioritet: Symboliserer lav, middels og høy prioritet.

### Hovedtabellen

Ved å trykke på en linje i hovedtabellen vil saken åpnes i sitt behandlingsbilde. Meldinger åpnes i meldingsbehandlingsbildet, tiltak åpnes i tilltaksbehandlingsbildet og høringer åpnes i besvar høring.

- \+ Utvidet informasjon og historikk: Hold pekeren over denne til å få opp utvidet informasjon om saken. Foreløpig kun meldinger og tiltak.
    
- Meldingsskjema: Hvilket meldingsskjema saken er opprettet med.
    
- Registrert: Dato for når saken ble registrert. For meldinger når den ble registrert, for tiltak når det ble opprettet.
    
- Frist: For meldinger behandlingsfrist, for tiltak gjennomføringsfrist og godkjenningsfrist.
    
- Beskrivelse: For meldinger teksten i det første tekstfeltet i meldingen, for tiltak navnet.
    
- Prioritet: {{< onlystaticimg src="/images/Flag_green.png" >}},{{< onlystaticimg src="/images/Flag_yellow.png" >}},{{< onlystaticimg src="/images/Flag_red.png" >}} symboliserer lav, middels og høy prioritet. For tiltak gjelder prioriteten til den tilkoblede meldingen som er høyest.
    
- Status: Statusen til saken.
    
- Registrert på avdeling: Avdelingen saken er registrert på.
    
- Saken ligger nå hos: Den brukeren som har ansvaret for å gjøre noe med saken. Avhenger av sakens type og status. Vises bare når "Alle saker jeg har vært involvert i" er valgt.
  - Meldinger:
    - <Navn på bruker>: Den navngitte brukeren er tilordnet som ansvarlig for saken.
  - Tiltak:
    - Med status <<Under planlegging>>: Navnet på den brukeren som har opprettet tiltaket og er overordnet ansvarlig for det.
    - Med status <<Under gjennomføring>>: Navnene på de brukerne som skal gjennomføre tiltaket.
    - Med status <<Under godkjenning>>: Navnet på den brukeren som har opprettet tiltaket og er ansvarlig for å godkjenne det.
  - Høring:
    - Med status <<Ute på høring>>: Navnene på de brukerne som skal delta i høringen.
    - Med status <<Til godkjenning>>: Navnet på den brukeren som skal godkjenne høringen.
- Sideskift: Knappene markert med Først, Forrige, Neste, Siste og eventuelle nummererte knapper i mellom brukes til å skifte side når det er mer enn 20 saker som kan vises i tabellen.

### Hvilke saker vises i tabellen?

- Meldinger som er sendt til den påloggede brukeren via Send til saksbehandler i Behandlingsbildet eller via tidlig saksbehandling i Endre melding.
- For ledere:
  - Meldinger registrert på avdlingen lederen er registrert på som ikke har fått tilordnet en annen ansvarlig person.
  - Meldinger registrert på underliggende avdelinger, hvor det ikke er en egen leder som ikke har fått tilordnet en annen ansvarlig person. Meldinger registrert på avdelinger uten leder vil flyte oppover i organisasjonen og vises i Innboks på den første overliggende avdelingen som har en leder.
- Tiltak brukeren har opprettet som er under planlegging.
- Tiltak brukeren skal utføre som er under gjennomføring.
- Tiltak brukeren er satt til godkjenner for som skal godkjennes. Man blir godkjenner for et tiltak om man har laget det, eller via en regel av typen tiltaksgodkjenner.
- Høringer brukeren skal delta i som er ute til høring.
- Høringer brukeren skal godkjenne som er til godkjenning.
- Revisjonsvarsel for dokumenter som har passert sin revisjonsvarslingsfrist og brukeren er satt som revisjonsansvarlig.
- Revisjoner brukeren skal gjennomføre.

Merk at meldinger andre brukere har registrert som er laget med meldingsskjemaer som har en rolle med "Se meldinger" begrensning, ikke blir vist her med mindre den påloggede brukeren har den samme rollen eller Systemrollen Se alle meldinger tilknyttet seg eller den brukertypen brukeren er logget på med. Meldinger brukeren selv har registrert blir vist. 