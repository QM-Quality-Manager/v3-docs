---
title: "Tiltak"
linkTitle: "Tiltak"
date: 2017-01-06
description: >
  Et tiltak er en måte å følge opp og lukke en melding på. En melding kan ha flere tiltak og et tiltak kan ha flere meldinger. 
---
Redigeres i tiltaksbehandling.

Opprettes vanligvis fra meldingsbehandling.

Kan slettes og få koblet til eller koblet fra meldinger i tilknyttede meldinger 

### Data
- Navn: Brukes til å identifisere tiltaket. Obligatorisk felt.

- Kostndadsramme: Brukes til å fortelle hvor mye penger som er satt av til dette tiltaket.

- Faktisk kostnad: Beskriver hva den faktiske kostnaden ble. Dette feltet brukes som kostnadsfelt i rapporten for tiltak.

- Status: Under planlegging, under gjennomføring, under godkjenning, godkjent. Se tiltaksstatus.

- Tiltakskategorier: Kategoriene av typen tiltak i den meldingen dette tiltaket ble laget til kan brukes i tiltaket for å kategoriesere det. Dette feltet er flervalg.

### Tekstfelter
- Opprinnelig hendelse: Beskrivelse av hva som var den opprinnelige hendelsen. Kopieres fra det første tekstfeltet i den meldingen dette tiltaket ble laget fra.

- Korrigerende tiltak: Beskrivelse av hva som er det korrigerende tiltaket. Opsjon: Kan kopieres fra det andre tekstfeltet i den meldingen dette tiltaket ble laget fra. Teksten koppiert inn her bør ofte tolkes som et forslag og endres av den som opprettet tiltakser til å bli en jobbbeskrivelse.

- Hvordan hindre gjentakelse: Beskrivelse av hvordan man skal hindre at hendelsen gjentar seg. Må man gjøre noe mer enn bare å rette feilen. Opsjon: Kan kopieres fra et eventuelt tredje tekstfelt i meldingen.

- Kommentar: Ekstra kommentar til tiltaket.

### Ansvarlige personer

- Opprinnelig melder: Den/de som har laget de meldingene som er koblet til dette tiltaket.
- Tiltaket ble opprettet av: Den som opprettet og eier - dvs er ansvarlig for tiltaket. Denne brukeren vil også måtte godkjenne tiltaket for å avslutte
- Tiltaket utføres av: Den/de brukerne som skal utføre selve jobben. Kan velges blandt samtlige brukere i systemet.
- Tiltaket godkjennes av: Alltid den som opprettet tiltaket. Kan også gjøres av en superbruker med systemrollen Innholdsadministrator.

### Tilgangskontroll

Alle tiltak registreres på en avdeling og får status Under planlegging eller Under utførelse dersom valg av gjennomførere gjøres i meldingsbehandlingsbildet. Hvilken tilgang en bruker har til et tiltak avgjøres av tiltakets status og avdeling og brukerens brukertype, avdeling og roller.

#### De ulike tilgangstypene gir disse rettighetene

- Lesetilgang
  - Kan lese tiltaket.
  - Sende epostkommentarer til det.
- Skrivetilgang
  - Kan endre tiltaket.
  - Noen felt krever også behandlingstilgang for å kunne redigere.
  - Aktiverer lagreknappen.
- Utføre selv
  - Kan melde tiltaket utført for sin egen bruker.
- Utføre andre
  - Kan melde tiltaket utført for brukere innenfor eget hierarki.
  - Med behandlingstilgang, kan melde tiltaket utført for brukere utenfor eget hierarki.
- Behandlingstilgang
  - Kan behandle tiltaket
  - Skifte status
  - Tilordne eller fjerne ansvarlige for gjennomføring.
  - Kan koble tiltaket til flere meldinger eller koble fra meldinger.
  - Redigere feltet for opprinnelig hendelse.
- Slettetilgang
  - Kan slette tiltaket. Alle tilkoblede meldinger blir koblet fra og får status ny eller sendt til saksbehandler avhengig av tidligere status.
- Administrasjonstilgang
  - Kan redigere et tiltak selv om det er lukket og låst.
  - Kan gjenåpne lukkede tiltak.
  - Kan også utføre alle handlinger gitt for de øvrige tilgangstypene.

#### Krav for å få de ulike tilgangstypene

- Lesetilgang
  - Opprinnelig melder for en melding som er koblet til tiltaket.
  - Utfører av tiltaket.
  - Brukere med brukertype leder, saksbehandler eller verneombud som har samme avdeling som tiltaket er registert på eller en overliggende avdeling av denne.
  - Brukere med brukertype leder, saksbehandler eller verneombud som har samme avdeling som en melding tilkoblet tiltaket er registert på eller en overliggende avdeling av denne.
  - Brukere som har vært definert som saksbehandler for en meldingen og denne meldingen er tilknyttet dette tiltaket.
  - Brukere med brukertype leder, saksbehandler eller verneombud som har samme avdeling som en bruker som har vært saksbehandler for en melding tilkoblet tiltaket eller en overliggende avdeling av denne.
  - Brukere som er informert om en melding gjennom en epost fra meldingsbehandlingsbildet og denne meldingen er tilknyttet dette tiltaket.

- Skrivetilgang gis kun når tiltakets status ikke er godkjent.
  - Brukere med brukertype leder eller saksbehandler som har samme avdeling som tiltaket er registert på eller en overliggende avdeling av denne.
  - Brukerne som skal utføre tiltaket og tiltakets status er under gjennomføring.
  - Brukere med brukertype leder og saksbehandler som har samme avdeling som en av tiltakets utførere eller en overliggende avdeling av disse.

- Utfører selv
  - Brukerne som skal utføre tiltaket og tiltakets status er under gjennomføring.

- Utfører andre
  - Brukere med brukertype leder eller saksbehandler som har samme eller overliggende avdeling som en av tiltakets utførere og tiltakets status er under gjennomføring.

- Behandlingstilgang
  - Brukere med brukertype leder eller saksbehandler som har samme avdeling som tiltaket er registert på eller en overliggende avdeling av denne.

- Slettetilgang
  - Eier av tiltaket, den brukeren som skal godkjenne tiltaket, kan slette det dersom det har status under planlegging.

- Administrasjonstilgang
  - Gis til brukere med systemrollen Innholdsadministrator.
