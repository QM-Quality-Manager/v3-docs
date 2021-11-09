---
title: "Brukertype"
linkTitle: "Brukertype"
date: 2017-01-06
description: >
  Navn og roller for all brukertyper kan endres av systemets administrator. Brukertyper kan også endres og slettes.
---
Rettighetene til en brukertype er definert av systemrollene tilknyttet den. En bruker må ha en brukertype for hver avdeling brukeren er tilknyttet. For en innlogget bruker med flere brukertyper, er det kun rollene tilknyttet avdelingen brukeren er logget inn på som vil gjelde. I standardversjonen er det fire forhåndsdefinerte brukertyper: Leder, Saksbehandler og Verneombud har det fullstendige grensesnittet, mens Medarbeider har det forenklede grensesnittet. 

### Leder

Gir full tilgang til systemet i standardversjonen. Kan få begrenset/øket tilgang ved hjelp av Systemroller. Meldinger uten fastsatt behandler vises automatisk i Innboks/Saker jer er ansvarlig for. Det vil si at alle registrerte meldinger der "tidlig saksbehandling" ikke er skrudd på vises i Innboks/Mine saker for nærmeste leder.

### Saksbehandler

Samme tilgang som Leder i standardversjonen, bortsett fra at tilgangen til Admin er byttet ut med Innstillinger. Meldinger uten fastsatt behandler vises ikke automatisk i Innboks/Mine saker.

Ledere og Saksbehandlere dukker automatisk opp som mulige brukere å sende meldinger til i Meldinger/UH/Behandling på sin avdeling. Dersom det skal være mulig å sende meldinger på tvers av organisasjonen f.eks fra Helse og omsorg til Teknisk avdeling, så må i tillegg minst en bruker med brukertype Leder eller Saksbehandler legges opp under arkfanen Admin/Regler, Reaksjon "Ekstra saksbehandlere".

### Verneombud

Samme lesetilgang som Leder i standardversjonen, men kan kun redigere sine egne opplysninger. Dukker automatisk opp som mulig mottager av meldinger under Informeres i Meldinger/UH/Behandling på sin avdeling. Har Innstillinger istedenfor Admin

### Medarbeider

Eget enkelt grensesnitt i standardversjonen som kun gir tilgang brukerens egne opplysninger. 