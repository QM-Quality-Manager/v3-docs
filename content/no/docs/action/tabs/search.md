---
title: "Tiltak søk"
linkTitle: "Tiltak søk"
date: 2017-01-06
description: >
  Arkfane under Tiltak.
---
Denne siden brukes for å gjøre søk blandt registrerte tiltak. I mange tilfeller er det mer hensiktsmessig å bruke Rapporter til å finne frem til bestemte tiltak enn denne siden, men denne siden gir flere muligheter. Denne siden kan også benyttes sammen med Rapporter via knappen Utvid søk i søkeresultater.

### Generelle søkekriterier
#### Felt som bruker data fra tiltaket

- Tidsrom: Fra og med og til og med dato felt.
- Status: Ta med tiltak med de valgte status.
- Tiltaksnummer: Søk etter tiltaket med dette nummeret.

#### Felt som bruker data fra tilkoblede meldinger

- Prioritet: Ta med tiltak med den valgte prioritet.
- Skjematype: Vises kun om Logmeldinger eller Risikomeldinger er aktivert. Ta med tiltak koblet til meldinger med den valgte skjematype.
- Skjema: Hvis man velger noe annet enn Alle her, vil kategorigruppene og kategoriene i Type kategori å søke på delen under kun vise de som er i bruk i det valgte meldingsskjemaet.
- Meldingsnummer: Søk etter tiltak koblet til meldingen med valgt meldingsnummeret. Når dette feltet brukes sees det bort fra alle andre søkekriterier.
- Fritekst: Søk etter meldinger som inneholder en gitt tekst. Detksten kan være i alle fritekstfelter i meldingen. Det skilles ikke mellom store og små bokstaver. Lucene brukes som søkemotor for denne funksjonen. Se Lucene Query Syntax (kun engelsk) for detaljert informasjon om syntaks for søkefeltet.
- Vis meldinger fra:
  - Denne avdelingen: Kun meldinger regisrert på avdelingen valgt i navigatoren vises.
  - Denne og underliggende avdelinger: Alle meldinger registrert fra og med avdelingen valgt i navigatoren vises.
  - Kun underliggende avdelinger: Kun meldinger registrert i avdelinger under den avdelingen som er valgt i navigatoren vises.
- Vis tiltak som er: Begge valgene tar med tiltak fra og med valgt avdeling i navigatoren.
  - Opprettet på valgte avdelinger: Avdelingen tiltaket er opprettet på.
  - Behandlet av personer fra valgte avdelinger: Avdelingen til de som skal utføre tiltaket.
- Risiko: Vis tiltak koblet til meldinger med kategorier av kategorigruppetypen Risiko. Velg S og K verdi for meldingene som skal brukes.
  - S: Sannsynlighet. Verdi fra 0 - 5. 0 betyr at denne parameteren ikke skal brukes.
  - K: Konsekvens. Verdi fra 0 - 5. 0 betyr at denne parameteren ikke skal brukes.

### Type kategori å søke på

Alle parametere i dette feltet brukes mot meldingene som er tilkoblet tiltakene.

Dette feltet brukes til å søke etter kategorigrupper og kategorier. Kryss av for en eller flere kategorigrupper og / eller velg kategorier fra menyene. De definerende kategorigruppene vises øverst. Blandt dem kan du bare søke på en kategorigruppe og eller kategori. Hvis meldingstype eller meldingsskjema velges, vil det i dette feltet kun vises kategorigrupper og kategorier brukt i disse meldingsskjemaene.

### Sorter etter

Velg hvilken kolonne resultattabellen skal være sortert etter.

### Vis resultatet i

- Tabell: Viser resultatet i tabell på søkeresultatsiden for tiltak.
- Utvidet visning: Viser resultatet i en utvidet form som tar med alle detaljer i tiltakene på søkeresultatsiden for tiltak.
- Graf: Viser resultatet som graf under Rapporter.
