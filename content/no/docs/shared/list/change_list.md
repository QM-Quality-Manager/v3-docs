---
title: "Endre listeinformasjon"
linkTitle: "Endre listeinformasjon"
date: 2017-01-06
description: >
 Funksjon som brukes av alle lister for å endre informasjon om dem. 
---
Tilgjengelig fra sjekklister, risikoanalyser og spørreskjemaer. 

### Felter

- Vis for språket: Navnet på en liste kan registreres en gang per språk som er aktivisert i systemet.
- Listenavn: Identifiserer listen i tabeller og oversikter.
- Listetype: Gruppering for listen. Vises kun for sjekklister.
- Registrert av avdeling: Listen er tilgjengelig fra og med denne avdelingen. Endringer kan kun gjøres i listen fra denne avdelingen.
- Tilknyttet meldingsskjema: Det meldingsskjemaet som blir brukt som kommentarskjema når denne listen brukes. Dersom Ingen kommentar velges (kun individulle grupper og spørsmål for spørreskjema), vil det ikke være mulig å kommentere spørsmål i denne listen.
- Tilknyttet kategori: Denne kategorien vil være forhåndsvalgt for kommentarskjemaet. Dersom Alle kategorier velges vil ingen kategori være forhåndsvalgt. Dette forhindrer at visningsformen vis som enkeltspørsmål kan benyttes.
- Tilknyttet rapportskjema: Det meldingsskjemaet som blir brukt som rapportskjema når denne listen brukes. Ikke aktivert i standardversjonen.
- Tilknyttet rapportkategori: Denne kategorien vil være forhåndsvalgt for rapportskjemaet. Ikke aktivert i standardversjonen.
- Kommentar til listen: Fritekstfelt for yttligere informasjon om listen. Blir vist øverst i listen når denne besvares.
- Risikoalternativ: Vises kun for Risikoanalyser.

### Knapper

- {{< onlystaticimg src="/images/Page_edit.png" >}} Endre listeinnhold. Tar deg til endre listeinnhold skjermbildet for å endre spørsmålene i den sjekklisten som linjen det ble trykket på tilhører.
- {{< onlystaticimg src="/images/Page_key.png" >}} Endre svaralternativer. Tar deg til endre svaralternativer skjermbildet for å endre innholdet i listen som linjen det ble trykket på tilhører. Det er kun mulig å endre svaralternativer i spørreskjemaer som er lagt opp på den avdelingen som er valgt i navigatoren.
- {{< onlystaticimg src="/images/Page.png" >}} Forhåndsvisning. Åpner forhåndsvisningsvinduet for å se hvordan listen ser ut i papirversjon. I dette vinduet kan du også velge å se listen i listeform og som liste av enkeltspørsmål slik den ser ut når den skal fylles ut.
- {{< onlystaticimg src="/images/Tick.png" >}} Lagre: Lagrer endringene utført i feltene.
- {{< onlystaticimg src="/images/Cross.png" >}} Lukk: Tar deg tilbake til siden du kom fra.
- {{< onlystaticimg src="/images/Cog_add.png" >}} Vis / {{< onlystaticimg src="/images/Cog_delete.png" >}}Fjern avanserte muligheter. Viser og fjerner de avanserte mulighetene.

### Avanserte muligheter

Dette er ting som kommer opp når knappen Vis avanserte muligheter brukes. De avanserte mulighetene fjernes ved å bruke knappen Fjern avanserte muligheter.

#### Felter

- Listens dokumenter: De dokumentene som er tilknyttet denne listen.

#### Knapper

- {{< onlystaticimg src="/images/Link_add.png" >}} Legg til: Legger det valgte dokumentet til denne listen.
- {{< onlystaticimg src="/images/Page_white_delete.png" >}} Slette: Fjerner det valgte dokumentet i listens dokumenter fra denne listen.

### Kun for spørreskjemaer

Feltene tilknyttet meldingsskjema og tilknyttet kategori gjentas i en tabell for alle temaer og spørsmål i listen. Dette kan brukes til å justere tilknyttningen som er gjordt for hele listen slik at noen spørsmål får andre kommentarskjemaer eller avkrysset kategori.

Dersom du vil endre alle tilknyttningene for alle spørsmål undre et tema, gjør endringen i tema linjen og trykk Lagre. Da vil automatisk alle spørsmålene under dette temaet få samme tilknyttning som ble valgt for temaet. Tilsvarende, hvis tilknyttningen blir endret for listen og Lagre trykket på, vil alle spørsmålene også bli endret. 