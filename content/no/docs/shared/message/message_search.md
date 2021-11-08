---
title: "Melding søk"
linkTitle: "Melding søk"
date: 2017-01-06
description: >
 Arkfane under Meldinger/UH, Logg og Risiko.
---
Denne siden brukes for å fjøre søk blandt registrerte meldinger. Hvilken arkfane man åpner denne siden fra bestemmer hvilken verdi skjematypefeltet starter med. I mange tilfeller er det mer hensikstmessig å bruke Rapporter til å finne frem til bestemte meldinger enn denne siden, men denne siden gir flere muligheter. Denne siden kan også benyttes sammen med Rapporter via knappen Utvid søk i søkeresultater.

### Generelle søkekriterier
- Tidsrom: Søk etter saker fra et bestemt tidsrom. Fra og med og til og med dato felt.

- Status: Ta med meldinger med de valgte status.

- Prioritet: Ta med meldinger med den valgte prioritet.

- Skjematype: Vises kun om Logmeldinger eller Risikomeldinger er aktivert. Ta med meldinger med den valgte skjematype. Resultatet vil vises i den arkfanen som tilsvarer valgt skjematype.

- Skjema: Kun meldinger laget med meldingsskjemaet valgt her blir tatt med. Hvis man velger noe annet enn Alle her, vil kategorigruppene og kategoriene i Type kategori å søke på delen under kun vise de som er i bruk i det valgte meldingsskjemaet.

- Meldingsnummer: Søk etter meldingen med valgt meldingsnummeret. Når dette feltet brukes sees det bort fra alle andre søkekriterier.

- Melder: Søk etter meldinger som den valgte brukeren har rapportert.

- Fritekst: Søk etter meldinger som inneholder en gitt tekst. Detksten kan være i alle fritekstfelter i meldingen. Det skilles ikke mellom store og små bokstaver. Lucene brukes som søkemotor for denne funksjonen. Se Lucene Query Syntax (kun engelsk) for detaljert informasjon om syntaks for søkefeltet.

- Vis meldinger fra:
  - Denne avdelingen: Kun meldinger regisrert på avdelingen valgt i navigatoren vises.
  - Denne og underliggende avdelinger: Alle meldinger registrert fra og med avdelingen valgt i navigatoren vises.
  - Kun underliggende avdelinger: Kun meldinger registrert i avdelinger under den avdelingen som er valgt i navigatoren vises.

- Risiko: Vis meldinger med kategorier av kategorigruppetypen Risiko. Velg S og K verdi for meldingene som skal tas med.
  - S: Sannsynlighet. Verdi fra 0 - 5. 0 betyr at denne parameteren ikke skal brukes.
  - K: Konsekvens. Verdi fra 0 - 5. 0 betyr at denne parameteren ikke skal brukes.

### Type kategori å søke på
Dette feltet brukes til å søke etter kategorigrupper og kategorier. Kryss av for en eller flere kategorigrupper og / eller velg kategorier fra menyene. De definerende kategorigruppene vises øverst. Blandt dem kan du bare søke på en kategorigruppe og eller kategori. Hvis meldingstype eller meldingsskjema velges, vil det i dette feltet kun vises kategorigrupper og kategorier brukt i disse meldingsskjemaene.

### Sorter etter
Velg hvilken kolonne resultattabellen skal være sortert etter.

### Vis resultatet i
- Tabell: Viser resultatet i tabell på søkeresultatsiden for meldinger.

- Utvidet visning: Viser resultatet i en utvidet visningsform som tar med alle detaljer i meldingene på søkeresultatsiden for meldinger.

- Graf: Viser resultatet som graf under Rapporter.
