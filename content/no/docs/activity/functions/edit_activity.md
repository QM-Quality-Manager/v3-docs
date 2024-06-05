---
title: "Endre aktivitet"
linkTitle: "Endre aktivitet"
date: 2017-01-06
description: >
 Endre aktivitet er en funksjon for å vedlikeholde aktiviteter. 
---
Tilgjengelig fra aktiviteter. 

### Felter

- Delplan: Velg hvilken delplan aktiviteten skal tilhøre.
- Navn på aktiviteten: Identifiserer aktiviteten i tabeller og oversikter. Brukes også som overskrift når en tilknyttetliste fylles ut.
- Liste tilknyttet: Dersom en liste skal fylles ut velges den her. Listene i nedfallsmenyen er sortert etter listetype. Dette feltet kan ikke endres etter at noen har besvart aktiviteten.
  - {{< onlystaticimg src="/images/Page.png" >}} Vis papirversjon: Åpner papirversjonen av den valgte listen. Trykk på det når en liste er valgt for å se hvordan den ser ut.
- Fra: Tidspunktet aktiviteten starter. Trykk {{< onlystaticimg src="/images/Calendar_icon.png" >}} for å åpne en kalender for datovalg.
- Til: Aktiviteten avsluttes. Trykk {{< onlystaticimg src="/images/Calendar_icon.png" >}} for å åpne en kalender for datovalg.

### Knapper

- {{< onlystaticimg src="/images/Tick.png" >}} Lagre: Lagrer endringene utført i feltene.
- {{< onlystaticimg src="/images/Cross.png" >}} Lukk: Tar deg tilbake til siden du kom fra.
- {{< onlystaticimg src="/images/Cog_add.png" >}} Vis / {{< onlystaticimg src="/images/Cog_delete.png" >}} Fjern avanserte muligheter: Viser eller skjuler de avanserte mulighetene.

### Avanserte muligheter

Dette er muligheter som kommer opp når knappen {{< onlystaticimg src="/images/Cog_add.png" >}} Vis avanserte muligheter brukes. De avanserte mulighetene fjernes ved å bruke knappen {{< onlystaticimg src="/images/Cog_delete.png" >}} Fjern avanserte muligheter.

#### Felter

- Vis for språket: Nedfallsmeny med et valg per språk som er aktivisert i systemet. Gjør at navnet på aktiviteten kan registreres en gang per språk.

- Aktivitetens distribusjon:
  - Normal: Svarene til deltagerne registreres på deres egen avdeling.
  - Revisjon: De som deltar kan besvare aktiviteten en gang for hver avdeling de har tilgang til. Er aktiviteten repeterende kan de besvare den et ubegrenset antall ganger per avdeling.
  - Lest og forstått: En Lest og forstått aktivitet brukes for å distribuere et dokument og få kvittert tilbake at det er lest og forstått. Lest og forstått aktiviteter oppfører seg ellers helt som vanlig aktiviteter, med unntak av at de ikke kan sendes ut periodisk, repeterende eller anonymt. Disse mulighetene skjules derfor når typen Lest og forstått velges som type. De som ønsker denne funksjonen skrudd på, må gi beskjed.

- Underavdelingene skal utføre aktiviteten: Fjern krysset bare dersom det kun er avdelingen valgt i navigatoren som skal utføre aktiviteten.

- Hvor ofte skal aktiviteten utføres?: Nedfallsmeny for å bestemme aktivitetstypen.
  - En gang: Vanlig aktivitet som kan fylles ut en gang av alle brukere som kan delta.
  - Repeterende: Repeterende aktivitet. Kan fylles ut et ubegrenset antall ganger av alle brukere som kan delta. Brukes når man på forhånd ikke vet hvor mange ganger en liste behøves å fylles ut. Kan også brukes til anonyme eksterne undersøkelser.
  - Periodisk: Brukes når du vil planlegge en periodisk utførelse av en aktivitet fremmover i tid. Sett Fra og Til tidsrommet til å dekke hele perioden du vil planlegge. Gjør alle de andre valgene i dette bildte du behøver og trykk Lagre. Da kommer du inn i bildet for å Oppsett av periodisk aktivitet. Der kan bestemmes perioden, f.eks daglig, ukentlig, årlig. Dette valget anbefales ikke brukt de første gangene du lager en aktivitet. Det er kun hensiktsmessig å lage periodiske aktiviteter dersom du er sikker på at listen som er tilknyttet ikke kommer til å endre seg innenfor perioden.
    
- Vil du ha tilsendt en e-postpåminnelse før tidsfristen går ut? Systemet kan sende en e-post til den som har laget aktiviteten det antall dager før den avsluttes som velges i denne nedfallsmenyen. E-posten vil inneholde opplysninger som hvor mange som har deltatt og hvor mange som skal delta, samt en link til Oppfølging der en purre e-post til de som ikke har svart kan skrives.
    
- Send ny påminnelse?
    
- Skal det sendes en e-postpåminnelse til deltakerne før tidsfristen går ut? Systemet kan sende en e-post til deltakerne som ennå ikke har svart på aktiviteten på valgt tidspunkt (1, 2, 3, 5, 7, 14, 21 eller 30 dager før sluttdatoen).
    
- Send ny påminnelse?
    
- Det skal svares anonymt på denne aktiviteten: Krysses av hvis skal være anonym.
        Antall besvarelser før resultatet vises: Vises kun for anonyme aktiviteter: Listegrafen viser ingen resultater for en avdeling før antallet besvarelser valgt her er registrert.

- Vis som liste: Listen skal besvares i listeversjon. Trykk på {{< onlystaticimg src="/images/Page.png" >}} for å se hvordan det ser ut. Bør brukes for sjekklister og risikoanalyser. Kan brukes for spørreskjemaer.
    
- Vis som serie av enkeltspørsmål (kun påminnelseslink): Listen skal besvares som serie av enkeltspørsmål. Trykk på {{< onlystaticimg src="/images/Page.png" >}} for å se hvordan det ser ut. Brukes for å gi spørreskjemaer et mer tradisjonelt spørreundersøkelsesutseende. Dersom listen ikke åpnes ved å trykke på en link i e-post som er blitt sendt ut som et varsel for aktiviteten blir den vist som liste. Dvs fyller man ut listen når man er pålogget Qm+ på vanlig måte, brukes alltid listeversjonen.
    
- Vis som kontrolliste: Merk at for kontrolliste lages et avkryssningsfelt per dag per spørsmål. Den ser helt bort fra valgte svaralternativer.
    
- Legg roller til aktiviteten: Tilordningsfelt for roller. Kun de brukerne som har samme rolle som aktiviteten kan delta i den. Hvis ingen roller velges, kan alle innenfor de valgte avdelingene delta.
    
- Valg av dokumentarkfane Tilordningsfeltene for dokumenter viser kun dokumenter som tilhører den dokumentarkfanen som er valgt her.
    
- Legg dokumenter til aktiviteten: Tilordningsfelt for dokumenter. Dokumenter lagt til aktiviteten vises som blå klikkbare lenker øverst i den tilknyttede listen når den besvares. Brukes hvis de som skal svare trenger å ha referansematriell eller yttligere informasjon tilgjengelig når de skal besvare listen.

#### Knapper

- << Legg til: Legger et eller flere element valgt i det høyre feltet til aktiviteten.
- Fjern >>: Fjerner et eller flere element valgt i det venstre feltet til aktiviteten.
