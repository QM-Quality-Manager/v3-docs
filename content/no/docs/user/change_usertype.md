---
title: "Endre brukertype"
linkTitle: "Endre brukertype"
date: 2017-01-06
description: >
 Funksjon under brukertyper for å endre data om brukertyper.
---
Man må ha systemrollen systemrolleadministrator for å kunne gjøre endringer på siden.

Obs. Vær spesielt oppmerksom om du gjør endringer på brukertypen du er logget på med. Det går an å fjerne tilgangen til å reverse endringer, for eksempel ved å ta vekk sin egen tilgang til Admin arkfanen.

Obs2. Alle endringer gjordt på brukertyper er umiddelbart synlige for alle brukere som er logget på med den aktuelle brukertypen, med unntak av arkfaner på det øverste nivået. De trenger en relasting av siden for å vise endringen. Dette kan eksempelvis gjøres ved å trykke på F5 tasten på tastaturet.

### Felter

- Vis for språket: Brukes til å velge språk for navnefeltet. Vises kun dersom mer enn ett språk er aktivert.
- Navn: Navnet på brukertypen. Brukes alle steder der brukertypen omtales.
- Posisjon: Brukes for å sortere lister der brukertypen er med. Posisjon 1 kommer først.
- Informasjon: Ekstra informasjon om brukertypen.
- Grensesnitt: Bestemmer om brukertypen skal ha fullstendig (tidligere kalt Leder grensesnitt) eller forenklet (tidligere kalt medarbeidergrensesnitt) grensesnitt. Valget her avgjør hvilke systemroller brukertypen kan tilknyttes.

### Rolleoversikt

Oversikt over alle roller som er tilknyttet denne brukertypen. Systemrollene vises først. En pålogget bruker har alle rettigheter som rollene tilknyttet brukertypen brukeren er logget på med har, i tillegg til de rettighetene rollene direkte tilknyttet brukeren gir. Systemroller for arkfaner kan kun tilknyttes brukertyper.

- Avkryssede systemroller gir konkrete egenskaper i systemet.
- Avkryssede brukerdefinerte roller gir ingen direkte rettigheter til brukeren med mindre de aktuelle rollene også er tilknyttet elementer som meldingsskjemaer, aktiviteter eller dokumenter.
- Velg feltet setter eller fjerner avkryssingen for alle roller i sin tabell.
- {{< onlystaticimg src="/images/Help.png" >}}. Trykk på dette ikonet for å lese mer om systemrollen på samme linje.

### Knapper

- {{< onlystaticimg src="/images/Tick.png" >}} Lagre: Lagrer endringer gjordt i siden.
- {{< onlystaticimg src="/images/Cross.png" >}} Lukk: Tar deg tilbake til siden du kom fra.
