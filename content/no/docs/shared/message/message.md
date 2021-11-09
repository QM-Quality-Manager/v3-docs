---
title: "Melding"
linkTitle: "Melding"
date: 2017-01-06
description: >
 En melding er et utfyllt meldingsskjema som brukes til å lagre en registrering i systemet.
---
En melding kan kobles til et eller flere tiltak. Et tiltak kan også kobles til en eller flere meldinger. En melding kan kobles til flere tiltak uansett hvilken status meldingen har.

Meldinger registrers og endres i endre melding og behandles i meldingsbehandlingsbildet.

Meldinger er fellesbetegnelsen for vanlige meldinger, risikomeldinger, loggmeldinger og kommentarmeldinger. Risikomeldinger og loggmeldinger er ikke aktivert i standardversjonen. De er identiske med vanlige meldinger på alle vis bortsett fra at de er tenkt brukt på en egen måte. 

### Data

- Kategorier: En melding kan ha et ubegrenset antall avkryssede kategorier.
- Tekstfelter: En melding kan ha et ubegrenset antall tekstfelter. Meldingene i standardversjonen har stort sett 2 tekstfelter.
- Prioritet: Viser meldingens prioritet. Kan ha verdiene Lav (grønn), Middels (gul), Høy (rød). Settes automatisk på bakgrunn av forhåndskodede verdier for de avkryssede kategoriene. Kan overstyres av melder og behandler.
- Kostnad: En melding kan ha 0 - 2 kostnadsfelter. I standardversjonen brukes 1 kostnadsfelt per meldingsskjema.
- Registreringsdato: Når inntraff hendelsen som er registrert.
- Registrert av bruker: Den brukeren som utfører registreringen.
- Melder: Den brukeren som rapporterer meldingen. Det er denne brukeren som blir meldingens opprinnelige melder eller avsender.
- Registrert på avdeling: Avdelingen meldingen er registrert på. Det er denne avdelingen meldingen vil bli vist på i rapporter og grafer.
- Aktuell avdeling: Den avdelingen som meldingens aktuelle saksbehandler er registrert på.
- Status: Mulige statuser for en melding:
  - Ny: En melding får status ny når den registreres.
  - Sendt til saksbehandler: En melding som har fått tilordnet en saksbehandler og har fått en frist.
  - Avvist: En melding som er avvist. Denne er lukket og kan ikke behandles videre.
  - Tiltaksbehandles: En melding som er tilknyttet minst ett tiltak som ikke er godkjent.
  - Lukket: En melding som er tilknyttet kun tiltak som er godkjent.

### Tilgangskontroll

Alle meldinger registreres på en avdeling og får status Ny eller Sendt til saksbehandler dersom valg av saksbehandler gjøres i selve registreringsbildet. Hvilken tilgang en bruker har til en melding avgjøres av meldingens status og avdeling og brukerens brukertype, avdeling og roller.

#### De ulike tilgangstypene gir disse rettighetene

- Lesetilgang: Kan lese meldingen og sende epostkommentarer til den.
- Skrivetilgang: Kan endre meldingen.
- Behandlingstilgang: Kan behandle meldingen og koble den til tiltak.
- Administrasjonstilgang: Kan redigere en melding selv om den er lukket og låst. Kan gjenåpne lukkede meldinger, skifte registreringsdato, kan skifte avdeling og kan skifte hvilken bruker meldingen er registrert på. Kan også utføre alle handlinger gitt for de øvrige tilgangstypene.

For å avvise eller sende en melding til saksbehandler, kreves både skrivetilgang og behandlingstilgang.

#### Krav for å få de ulike tilgangstypene

Følgende tar i utgangspunkt i Standardversjonen. Kunden kan selv definere egne brukertyper eller endre rettighetene til eksisterende brukertyper.

- Lesetilgang
  - Brukeren meldingen er registrert på.
  - Brukere med brukertype leder, saksbehandler og verneombud som har samme avdeling som meldingen er registert på eller en direkte overliggende avdeling av denne.
  - Brukere med brukertype leder, saksbehandler og verneombud som har samme avdeling som meldingens aktuelle avdeling eller en direkte overliggende avdeling av denne.
  - Brukere som er informert om en melding gjennom en epost fra meldingsbehandlingsbildet.
  - Brukere som har vært definert som saksbehandler for meldingen men har sent den videre.

- Skrivetilgang gis kun når meldingens status er ny eller sendt til saksbehandler.
  - Brukeren meldingen er registrert på.
  - Brukere med brukertype leder og saksbehandler som har samme avdeling som meldingen er registert på eller en direkte overliggende avdeling av denne.
  - Brukere med brukertype leder og saksbehandler som har samme avdeling som meldingens aktuelle avdeling eller en direkte overliggende avdeling av denne.
  - Brukere som har vært definert som saksbehandler for meldingen men har sent den videre.

- Behandlingstilgang
  - Brukere med brukertype leder og saksbehandler som har samme avdeling som meldingen er registert på eller en direkte overliggende avdeling av denne.
  - Brukere med brukertype leder og saksbehandler som har samme avdeling som meldingens aktuelle avdeling eller en direkte overliggende avdeling av denne.
  - Brukere som har vært definert som saksbehandler for meldingen men har sent den videre.

- Administrasjonstilgang
  - Gis til brukere med systemrollen Innholdsadministrator.
