---
title: "Dokumentdata"
linkTitle: "Dokumentdata"
date: 2017-01-06
description: >
  Dokumentdata: Brukes til å redigere dokumentdata for et dokument. Åpnes fra Endre data for dokumentet. 
---
### Felter

#### Dokumentnavn og type

- Navn: Navn på dokumentet.

- Informasjon: Beskrivelse av dokumentet (maks 500 tegn). Teksten vises når brukeren holder pekeren over navnet på dokumentet i Info, meldingsskjemaer og lister.

- Dokumenttype:
  - Skriv et dokument: Brukes dersom man ønsker å skrive et dokument rett inn i Qm+. Dokumentet blir lagret som et htmldokument og har en del formateringsmuligheter. Tekstredigeringsfeltet benytter TinyMCE.
  - Link: Brukes hvis man ønsker å linke til en resurs på internett eller til et dokument på en lokal filserver. Dokumenter det ikke er tilgang til fra internett vil ikke bli indeksert i vår søkemotor og vil vises med Linkfeil i dokumenter. Pass på at adressen som skrives inn er en gyldig http eller https adresse.
  - Fil: Brukes om man ønsker å laste opp en fil fra sin lokale datamaskin til Qm+serveren. Dette lager en kopi av filen på serveren. For å gjøre endringer i filen, må den redigeres lokalt og så lastes opp på nytt igjen.
  - Mappe: Brukes for å lage en mappestruktur under Info. Kan ikke åpnes som et dokument.
  - Prosesskart: Brukes når man ønsker å lage et prosesskart i Qm+. Når du lagrer et dokument med denne typen, blir arkfanen Prosesskartoppsett tilgjengelig. Dette låser også typen til dokumentet slik at den ikke kan endres.

#### Velg hvor dokumentet skal vises under INFO

- Dokumentets avdelinger. Tabell som viser hvilke avdelinger dokumentet er tilknyttet.
  - Fra avdeling. Dokumentet vil være synlig under Info og Admin/Dokumenter på de avdelingene som legges inn. Bruk knappen "{{< onlystaticimg src="/images/Add.png" >}} Legg til avdeling" for å få en ny valgboks i tabellen.
  - Vises for underavdelinger. Hvis krysset av, vil dokumentet også være synlig i Info i underavdelinger av avdelingen valgt i "Fra avdeling".
  - Slette. Kun aktiv om dokumentet er tilknyttet mer enn 1 avdeling. Trykk på sletteikonet {{< onlystaticimg src="/images/Delete.png" >}} for å slette tilknyttingen til den aktuelle avdelingen.
    
- Dokumentarkfane: Bestemmer hvilken arkfane dokumentet vises i under Info. Obligatorisk.
    
- Dokumentgruppe: Dokumentets gruppe. Bestemmer hvilken boks dokumentet vises i under Info. Obligatorisk.
    
- Underdokument av: Et underdokument blir ikke vist under Info før dokumentet det ligger under er utvidet ved å holde pekeren over Arrowclosed.gif symbolet.
    
- Offentlig dokument: Hvis krysset av, dokumentet vil være tilgjengelig for alle, ingen autentisering kreves. Vises kun for dokumenter av type "Skriv et dokument", "Link" og "Fil".
    
- Posisjon: Brukes kun dersom alfabetisk sortering er skrudd av. Normalt kan man se bort fra denne.

#### Kundespesifiserte dokumenthodefelt

Felt som må bestilles spesielt. Brukes til å legge inn ekstra informasjon som skal inn i dokumenthodet. Mulige felttyper:

- Fritekst.
- Dato.
- Valg av avdeling. Gir nedfallsmeny som viser alle avdelinger. Denne kan ha rollefiltrering, dvs at kun avdelinger med gitt rolle vises.
- Valg av bruker. Gir nedfallsmeny som viser alle brukere. Denne kan ha rollefiltrering, dvs at kun brukere med gitt rolle vises.

#### Status

Denne delen vises kun for dokumenter som er lagret minst en gang.

- Versjon: Dokumentets versjon. Vises som x.y, der x er hovedversjonsnummer og y er endringsnummer.
  - Hovedversjonsnummeret øker med en 1 hver gang knappen "{{< onlystaticimg src="/images/Disc_multiple.png" >}} Opprett ny versjon" brukes.
  - Endringsnummeret økes med 1 hver gang denne siden lagres og enten navnet, dokumentets innhold - dersom dette er et dokument som er skrevet inn i Qm+, lenkens adresse er endret eller det er lastet opp et nytt dokument.
  - Endringsnummeret starter på 1 for hver ny versjon som lagres. Endringsnummeret ble i tidligere versjoner av Qm+ omtalt som revisjonsnummer.
  - Versjonsnummeret er vist som en lenke som kan trykkes på. Det åpner dokumentet i den aktuelle versjonen.
  - Dersom versjonen som er vist i bildet er nyere enn den versjonen av dokumentet som er publisert, eller dokumentet aldri har vært publisert, vises knappen {{< onlystaticimg src="/images/Page_lightning.png" >}} Publiser. Den lagrer eventuelle endringer i dokumentet og setter den aktuelle versjonen til å være publisert.
  - Dersom man er inne i en versjon av et dokument som har en nyere versjon, blir det varslet ved {{< onlystaticimg src="/images/Exclamation.png" >}} og teksten "Dette dokumentet har en nyere versjon". Denne teksten er en lenke som åpen den aktuelle nyere versjonen.
  - Dokumenter som har en nyere versjon kan endres, men man kan ikke lage nye versjoner av de.
    
- Publisert versjon. Hvis den versjonen av dokumentet som er vist i bildet er den aktuelle publiserte versjonen, den som vises under Info, vises teksten "Dette er den publiserte versjonen". Hvis ikke, vises versjonsnummeret til den aktuelle publiserte versjonen av dokumentet.
    
- Lagt inn av: Navn på brukeren som har lagt inn dette dokumentet.
    
- Sist endret av: Den brukeren som siste endret dokumentet.
    
- Høringsstatus for denne versjonen: Vises kun dersom den valgte versjonen er tilknyttet en høring. Viser status for høringen og lenker til besvar høring.
    
- Adressen til dokumentet: Vises for lagrede dokumenter. Hvis du ønsker at et annet dokument i Qm+ skal refere til dette dokumentet, så kan du bruke denne adressen som lenke. Denne adressen kan nå også brukes utenfor Qm+ og vil alltid for dokumenter lagret i (Fil) eller skrevet i (Skriv et dokument) Qm+ gi nyeste publiserte versjon. Dersom man ikke allerede er pålogget Qm+ vil man bli bedt om brukernavn og passord for å få se dokumentet.

#### Revisjon

- Aktiver regelmessig revisjon. Brukes når man ønsker at en bruker regelmessig skal bli varslet om at dokumentet skal revideres. Resten av alternativene vises når dette feltet er krysset av.
- Varslingsdato for revisjon. Dato når brukeren skal varsles om revisjonen.
- Revisjonsintervall. Perioden mellom hvert varsel. Når et dokument som har passert revisjonsfristen er tilknyttet en revisjon som blir avsluttet, blir varslingsdatoen økt med verdien i dette feltet. Blir dokumentet revidert før varslingsfristen, blir ikke varslingsdatoen automatisk oppdatert. Ønsker man oppdatering i slike tilfeller, må det gjøres manuelt.
- Revisjonsansvarlig. Bruker som får varsel om dokumentrevisjon i sin innboks. Kun brukere med Systemrollen Revidere dokument tilknyttet sin bruker eller brukertype kan velges.

#### Ekstra attributter

- Dokumentet er et maldokument. Ja/Nei. Standard Nei. Kun aktuelt for dokumenter av typen "Skriv et dokument". Et maldokument er en skisse eller starten på et dokument, eksempelvis et sett av faste overskrifter. Maldokumenter som er lagret og publisert kan lastes av alle brukere inn i, fortrinnsvis nye, dokumenter fra Dokumentinnhold. Maldokumenter vises ikke under Info.
- Dokumenthodetype. Vises kun for de som har opsjonen om valgbare dokumenthodetype satt. Kun aktuelt for dokumenter av typen "Skriv et dokument". Bestemmer hvilken av de mulige dokumenthodetypene som vil bli brukt for dette dokumentet.

