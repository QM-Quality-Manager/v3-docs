---
title: "Endre bruker"
linkTitle: "Endre bruker"
date: 2017-01-06
description: >
 Funksjon under brukere for å endre data om brukere
---
### Felter

- Brukernavn: Brukes av brukeren for pålogging til systemet. Skiller mellom store og små bokstaver. Må være unik for hver kunde.
- Avdeling / Type. Dette feltet angir brukerens tilgang til systemet.
  - Avdelingen brukeren tilhører.
    - Dersom avdelingstilknyttingen er markert med {{< onlystaticimg src="/images/Server_connect.png" >}}, kan den ikke slettes. Det er lov å endre avdeling og brukertype. Bare aktuelt for kunder med AD / LDAP integrering.
  - Type: Brukerens brukertype.
  - Vikar: Vikarfunksjonen gir mulighet for en definert bruker til å logge inn med samme tilgangsrettigheter som tilgangen man er vikar for. Det kan settes en vikar for hver tilgang en bruker har. For hver tilgang en bruker har:
    - Dersom det er satt opp en vikar for tilgangen vises navnet på vikaren. Trykk på navnet for å endre eller ta bort vikaren.
    - Dersom det ikke er definert en vikar, vises en knapp for å sette vikar.
- Passord: Brukes av brukeren for pålogging til systemet. Skiller mellom store og små bokstaver.
- Gjenta passord: Må være lik passordfeltet for å få lagret brukeren.
- Fornavn: Brukerens fornavn.
- Mellomnavn: Brukerens mellomnavn.
- Etternavn: Brukerens etternavn.
- E-postadresse: Brukerens e-postadresse. En del funksjonalitet i systemet er knyttet opp mot brukerens e-postadresse. Det er derfor en fordel at hver bruker har en unik e-postadresse.
- Språk: Valg av visningsspråk for brukeren. Tilgjenglige språk i systemet: norsk (bokmål), norsk (nynorsk), engelsk, svensk og dansk (ikke oversatt rammeverk for dansk). Språkene tilgjenglige for den enkelte kunde vil variere.
- Mobilnummer: Kan brukes for utsendelse av SMS dersom SMS er aktivert.
- Kommentar: Fritekstfelt for ytteligere informasjon om brukeren.

#### Knapper

- {{< onlystaticimg src="/images/Add.png" >}} Legg til avdeling: Legg en avdeling til brukeren. Det er mulig å tilordne flere avdelinger til hver bruker. For hver avdeling brukeren hører til, må brukeren ha en tilhørende brukertype. Brukere som tilhører flere avdelinger må velge hvilken avdeling de ønsker å logge seg på i innloggingssiden.
- {{< onlystaticimg src="/images/Delete.png" >}} Slett avdeling: Sletter valgt avdeling fra brukeren. Vises kun for brukere som tilhører flere avdelinger.
- {{< onlystaticimg src="/images/User_go.png" >}} Sett vikar: Åpner muligheten til å sette vikar for en brukertilgang.
- {{< onlystaticimg src="/images/Accept.png" >}} Lagre
- {{< onlystaticimg src="/images/Cancel.png" >}} Avbryt
- {{< onlystaticimg src="/images/Delete.png" >}} Slette
- {{< onlystaticimg src="/images/Tick.png" >}} Lagre: Lagrer endringer gjordt i feltene.
- {{< onlystaticimg src="/images/Cross.png" >}} Lukk: Tar deg tilbake til siden du kom fra.
- {{< onlystaticimg src="/images/Cog_add.png" >}} Vis / {{< onlystaticimg src="/images/Cog_delete.png" >}} Fjern avanserte muligheter: De avanserte mulighetene vises eller skjules.

### Avanserte muligheter

Dette er ting som kommer opp når knappen Vis avanserte muligheter brukes. De avanserte mulighetene fjernes ved å bruke knappen Fjern avanserte muligheter.
Felter

- Brukerens roller: De rollene som er tilknyttet denne brukeren.
- Rollebank: De rollene som ikke er tilknyttet denne brukeren.

#### Knapper

- << Legg til: Legger de valgte rollene i Rollebanken til brukerens roller.
- Fjern >>: Fjerner de valgte rollene fra brukerens roller. De blir da synlige igjen i rollebanken.
- Cog add.png Vis / Cog delete.png Fjern systemroller: Avgjør om Systemroller blir vist i listen over roller. Denne knappen vises kun dersom brukeren har rollen Systemroller.
