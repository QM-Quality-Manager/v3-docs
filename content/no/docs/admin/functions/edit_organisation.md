---
title: "Rediger avdeling"
linkTitle: "Rediger avdeling"
date: 2017-01-06
description: >
 Funksjon under Organisasjon for endre data om avdelinger
---
### Felter

- Avdelingsnavn: Navnet som brukes på avdelingen i systemet. Vil vises i navigatoren
- Underavdeling av: Avdelingen denne avdelingen vises under i navigatoren. Denne avdelingen vil arve skjemaer, dokumenter og aktiviteter fra sine overliggende avdelinger.

### Knapper

- {{< onlystaticimg src="/images/Cog_add.png" >}} Vis / {{< onlystaticimg src="/images/Cog_delete.png" >}} Fjern avanserte muligheter: Brukes for å vise eller fjerne de avanserte mulighetene for siden.
- {{< onlystaticimg src="/images/Tick.png" >}} Lagre: Lagrer endringene utført i feltene.
- {{< onlystaticimg src="/images/Cross.png" >}} Lukk: Tar deg tilbake til siden du kom fra.

### Avanserte muligheter

Dette er ting som kommer opp når knappen Vis avanserte muligheter brukes. De avanserte mulighetene fjernes ved å bruke knappen Fjern avanserte muligheter.

### Roller

- Avdelingens roller: De rollene som er tilknyttet denne avdelingen.
  - Roller tilknyttet en avdeling gjelder for alle brukere for den aktive avdelingen. Dvs alle medarbeidere på avdelingen og alle andre brukere som har valgt avdelingen i navigatoren.
  - Roller tilknyttes en avdeling for å styre tilgjengelighet av dokumenter, skjemaer og aktiviteter.
- Rollebank: De rollene som ikke er tilknyttet denne avdelingen.

### Knapper

- {{< onlystaticimg src="/images/User_add.png" >}} << Legg til: Legger de valgte rollene i Rollebanken til Avdelingensroller.
- {{< onlystaticimg src="/images/User_delete.png" >}} Fjern >>: Fjerner de valgte rollene fra Avdelingensroller. De blir da synlige igjen i Rollebanken.
- {{< onlystaticimg src="/images/Cog_add.png" >}} Vis / {{< onlystaticimg src="/images/Cog_delete.png" >}} Fjern systemroller: Avgjør om Systemroller blir vist i listen over roller. Denne knappen vises kun dersom brukeren har rollen Systemroller.

### Hovedoppgaver

Avdelinger kan tilknyttes kategorier i en gruppe med klassifisering Oppgaver. Dette er ment for å visualisere avdelingens hovedoppgaver, og har ingen direkte funksjon i systemet ut over dette.

### Knapper

- {{< onlystaticimg src="/images/Note_edit.png" >}} Tilpass oppgaver.
- {{< onlystaticimg src="/images/Note.png" >}} Vis som liste.
- {{< onlystaticimg src="/images/Note_add.png" >}} << Legg til: Legger de valgte oppgaver i Oppgavebanken til Avdelingens hovedoppgaver.
- {{< onlystaticimg src="/images/Note_delete.png" >}} Fjern >>: Fjerner de valgte oppgaver fra Avdelingens hovedoppgaver. De blir da synlige igjen i Oppgavebanken.
