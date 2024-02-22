---
title: "Systemroller"
linkTitle: "Systemroller"
date: 2017-01-06
description: >
  Systemroller er roller som gir bestemte utvidede rettigheter definert i systemet. Nye systemroller kan kun defineres av QmPlus AS. 
---
Rollene er markert med (L,S,V,M) om de i standardversjonen, slik det er satt opp fra QmPlus AS, er knyttet til brukertypene Leder, Saksbehandler, Verneombud eller Medarbeider. Merk at superbruker fra versjon 3.60 kan endre på navn og innhold i disse. 

### Roller som styrer tilgang til arkfaner

Alle disse rollene gir brukeren tilgang til arkfanen med samme navn.

#### Roller som gir tilgang til arkfaner i det fullstendige grensesnittet

- Hjem:
- Info: (L,S,V)
- Rapporter: (L,S,V)
- Admin: (L)
- Innstillinger: (S,V)
- Aktivitetsplan: (L,S,V)
- Innboks:
- Risiko:
- Arkiv: (L,S,V)
- Hjelp: (L,S,V)

#### Roller som styrer tilgang til arkfaner under Admin

- Admin_Organisasjon: (L)
- Admin_Brukere: (L)
- Admin_Kategorier: (L)
- Admin_Skjemaer: (L)
- Admin_Dokumenter: (L)
- Admin_Roller: (L)
- Admin_Regler: (L)
- Admin_Ansvar:

#### Roller som styrer tilgang til arkfaner under Inboks

- Innboks_Avdelingens saker: (L,S,V)

#### Roller som styrer tilgang til arkfaner under Arkiv og Rapporter

- Arkiv_Avvik: (L,S,V)
- Arkiv_Tiltak: (L), Bare i Arkiv.
- Arkiv_Kommentarer:
- Arkiv_Log: (L,S,V)
- Arkiv_Bare lukkede saker: Users with this role will only be able to see the Closed cases under Archive/Messages, Archive/Comments, Archive/Order and Archive/Logs. The other status tabs will be visible but the user will not be able to select them.
- Rapporter_Brukerrapporter:

#### Roller som styrer tilgang til arkfaner under Info

- Info_Favorittdokumenter:

#### Roller som styrer tilganger til arkfaner i det forenklede grensesnittet

- Info: (M)
- Mine saker: (M)
- Innstillinger: (M)
- Hjelp: (M)

#### Roller som styrer tilganger til arkfaner under Mine saker

- Mine saker_Meldinger: (M)
- Mine saker_Tiltak: (M)
- Mine saker_Spørreskjemaer: (M)
- Mine saker_Logg: (M)

### Roller som definerer tilganger og hvordan en bruker oppfører seg

#### Dokumenter

- Høringsdeltaker: (L,S) Kan delta i høringer. Brukere med det forenklede grensesnittet kan også ha denne selv om det ikke er standard.
- Godkjenne dokument: (L,S) Kan godkjenne dokumenter i høringer. Brukere med det forenklede grensesnittet kan også ha denne selv om det ikke er standard.
- Revidere dokument: (L) Kan settes opp som mottaker av revisjonsvarsler og kan lage ny revisjon og utføre revisjoner.
- Publisere dokument: (). Skrudd av som standard. Når den er aktivert, så kreves denne rollen for å kunne publisere et dokument.

#### Meldinger / Tiltak

- Melder: (L,S,V,M) Navnet på brukeren vises i Meldernedfallsmenyen når man registrer en ny melding.
- Lage / Endre melding: (L,S,V,M) Brukeren kan lage og endre egne meldinger.
- Lage / Endre melding, annen avdeling: (L,S) Brukeren kan lage / endre meldinger på alle avdelinger som er tilgjenglige i navigatoren.
- Tiltaksutfører: (L,S,V,M) Brukeren kan få som oppgave å utføre et tiltak.
- Tilgang til skjulte tekstfelter: (L) Brukeren kan se innholdet i skjulte tekstfelter. Dersom denne rollen er tilknyttet brukerens brukertype gis tilgang til skjulte tekstfelter meldinger brukeren er satt til å være behandler for. Dersom rollen er tilknyttet brukeren vil skjulte tekstfelter, i alle meldinger brukeren har tilgang til, være synlig i endre melding bildet.
- Se alle meldinger: Brukeren kan se alle meldinger i sin organisasjon, også meldinger fra meldingsskjemaer som har en rollebegrensning av typen "Se meldinger", selv om brukeren ikke har den rollen.
- Behandle melding: (L,S) Kan behandle meldinger.
- Standard meldingsmottaker: (L)
  - Nye meldinger, som ikke har fått en spesiell saksbehandler, vises i Innboks/Saker jeg er ansvarlig for i den avdelingen som ligger nærmest den avdelingen meldingen ble registrert på, der det er en bruker med denne rollen. Rollen kan være tilknyttet brukeren eller brukerens brukertype. Dette tilsvarer den tidligere "Vises for nærmeste linjeleder" funksjonen.
  - Dersom opsjonen Tidlig saksbehandling er skrudd på, dvs at valg av saksbehandler skjer i "Registrer ny melding" uten at det er lagt opp "Tidlig saksbehandler" regel for det, vil brukere med denne rollen komme med i listen over brukere man kan velge blandt.
- Standard mulig informasjonsmottaker: (L,S,V,M) Vises som en del av "Alle" og "Alle i egen organisasjon" når man velger "Informer flere" i meldingsbehandlingsbildet.
- Standard mulig meldingsmottaker: (L,S) Vises som mulig valg når man velger "Velg saksbehandler" i "Velg handling" i meldingsbehandlingsbildet.
- Informeres shortlist: (L,S,V) Vises som mulig mottaker når man velger "Saksbehandlerliste" når man velger "Informer flere" i meldingsbehandlingsbildet.
- Begrenset til skjemaer i saksbehandlerregler: Brukere med denne rollen får kun opp egne meldinger/tiltak i Innboks og Arkiv med mindre brukeren er definert som enten "Ekstra saksbehandler" eller "Tidlig saksbehandler" for enkelte meldingsskjemaer i Admin/Regler.
- Brukergraf: Kan se graf for hvor mange meldinger som er registrert per bruker på en valgt avdeling under Rapporter.
- Facilit: Kan overføre saker til Facilit om integrasjonsmodulen mot Facilit er skrudd på.
- SMS-ansvarlig. Kan sende SMS fra Admin/Brukere.
- Flytte melding: Kan skifte avdeling på meldinger brukeren har skrivetilgang til. Denne rollen trengs ikke om brukeren har Innholdsadministrator.

#### Grafer

- Kan ikke klikke på grafer: Brukere med denne rollen vil ikke kunne klikke på grafer under Rapporter eller Hjem (Dashboard). Dette er for å tillate brukere å se grafer uten direkte videre tilgang til de faktiske sakene. For å forhindre slik tilgang generelt, må andre faneroller også fjernes for den brukeren eller brukertypen.

#### Aktivitetsplan

- Aktivitetsdeltaker: (L,S,V,M) Skal delta i aktiviteter. Brukere uten denne rollen vil ikke telles med i antallet når antall gjennstående svar telles opp. Dersom en bruker har flere brukertyper på flere avdelinger og kun skal delta i aktivitetsplanen på noen av dem, pass på å sette denne rollen kun for de brukertypene som skal delta.
- Fylle ut aktivitet, annen avdeling: (L,S) Kan fylle ut aktiviteter for alle avdeliger brukeren har i navigatoren.

#### Administrasjonsroller

- Organisasjonsadministrator: (L) Kan lage / endre avdelinger.
- Brukeradministrator: (L) Kan lage / endre brukere og sette vikar.
- Skjemaadministrator: (L) Kan lage / endre lister, meldingsskjemaer og kategorier.
- Aktivitetsadministrator: (L) Kan lage / endre aktiviteter.
- Dokumentadministrator: (L) Kan lage / endre dokumenter.
- Rolleadministrator: (L) Kan lage / endre brukerdefinerte roller. Systemroller kan ikke endres av bruker.
- Regeladministrator: Kan lage / endre regler.
- Ansvarsadministrator: Kan lage / endre ansvarskoder.

#### Roller som gir utvidete superbrukerrettigheter

- Systemrolleadministrator: Brukeren kan administrere Systemroller. Ikke delt ut til noen i standardløsningen. Kun superbrukeren bør ha denne rollen.
- Innholdsadministrator: Brukeren kan endre låste skjemaer, flytte utfylte meldinger og åpne lukkede saker. Ikke delt ut til noen i standardløsningen. Kun superbrukeren bør ha denne rollen

#### Roller som gir tilgang til spesiell funksjonalitet i ledergrensesnittet

- Kompetansemodul: Endrer funksjonalitet i systemet for å passe med kompetansemodulen. Vises kun om kompetansemodulen er aktivert.
