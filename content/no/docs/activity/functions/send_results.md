---
title: "Send resultat"
linkTitle: "Send resultat"
date: 2017-01-06
description: >
  Funksjon under Aktivitetsplan/Grafer for listen. 
---
Brukes til å sende resultatet fra en aktivitet til brukere som normalt ikke har tilgang til dem. Resultatet sendes med e-post som inneholder en link som åpner grafen for aktiviteten.

### Felter

- Overskrift: Navnet på aktiviteten.
- Tittel: Tittelfeltet i den e-posten som skal sendes ut.
- Tekstfelt: Her skrives teksten som skal være med i e-posten. Teksten "http://www.qmplus.com/Resultat" kan plassers hvor som helst i e-posten og vil byttes ut med en individuell link for hver mottaker. Denne linken vil da kunne brukes til å vise grafen for aktiviteten.
- Avsenderadresse: Denne e-postadressen vil stå i avsenderfeltet. Settes automatisk til den e-postadressen brukeren som skriver varselet er registrert med. Denne adressen vil også motta alle feilmeldinger om ugyldige e-postadresser. E-postadresser kan endres i endre bruker under Brukere under Admin.
- Tidligere resultatmeldinger sendt for denne aktiviteten: Dersom resultatet er sendt for denne aktiviteten tidligere vil det listes opp her. Dersom du vil bruke samme tekst som ved et tidligere utsendelse, kryss av i Velgkolonnen og trykk på Bruk valgt tidligere melding knappen.

### Send resultat til

Brukes til å lage en liste over mulige mottakere.

- Avdeling: Siden resultatet som sendes ut er grafen for den avdelingen som er valgt i navigatoren, kan man her velge avdeling for de brukerne som skal motta resultatet.
- De som har svart: Tar med alle brukere som har besvart aktiviteten.
- De som kunne svare: Tar med alle brukere som kunne besvare aktiviteten.
- Alle som har følgende rolle: Åpner en ny dialog der man kan velge et sett av roller. Alle brukere som har minst en av de valgte rollene taes med.
- Velg blant alle brukere: Gir mulighet til å velge blant alle brukere fra og med valgt avdeling.

Velg et av alternativene over og trykk på "Velg"-knappen.

- Øverst står det en oppsummering av hvor mange brukere som er i listen og hvor mange av disse som har en tilsynelatende lovlig e-postadresse.
- Send til: Avkryssningsfelt for de som skal motta varselet. Alle brukere i listen som har en tilsynelatende lovlig e-postadresse er i utgangspunktet krysset av.

### Knapper

- Velg alle: Krysser av for alle brukere i listen som har en tilsynelatende lovlig e-postadresse.
- Velg ingen: Fjerner alle avkryssninger i brukerlisten. Kan for eksempel være nyttig dersom man ønsker å teste et varsel til seg selv eller et lite utvalg før man sender det ut til alle.
- Send resultat: Sender resultatet til alle brukere det er krysset av for i brukerlisten. Dersom det er mange (>100) brukere i listen kan det ta noe tid før alle e-postene er sendt ut. Det er mulig å lukke send resultat vinduet mens e-postene blir sendt. Når alle e-postene er sendt vil du få en melding om det dersom du ikke har lukket send resultat vinduet. Det betyr ikke at alle nødvendigvis har mottatt sin e-post. E-post i enkelte tilfeller ta lengre tid før de er fremme enn man forventer. Husk også å se i din egen e-post etter meldinger om ugyldige e-postadresser. Disse adressene må rettes opp før du kan sende varselet på nytt til dem.
- Bruk valgt tidligere melding: Vises kun for aktiviteter som har sendt ut resultatet før. Henter tittel og tekst for den valgte tidligere meldingen slik at det kan brukes på nytt. Du kan gjøre endringer i den tidligere teksten før du sender meldingen ved å bruke Send resultat på vanlig måte.
