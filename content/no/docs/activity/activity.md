---
title: "Aktivitet"
linkTitle: "Aktivitet"
date: 2017-01-06
description: >
 En aktivitet brukes hovedsaklig til å dele ut lister slik at disse kan besvares av brukerne. En aktivitet uten en tilknyttet liste får ingen graf, men kan likevel brukes til å måle oppsluttning om f.eks et møte eller lignende.
---
### Data
- Delplan: Hvilken delplan denne aktiviteten skal sortere under.

- Navn på aktiviteten: Navnet brukes for å identifisere aktiviteten der den brukes.

- Liste tilknyttet: Listen som er tilknyttet denne aktiviteten.

- Fra: Tidspunktet da aktiviteten starter.

- Til: Tidspunktet da aktiviteten slutter. Merk: En dag begynner kl 00:00 og slutter kl 23:59.

- Vis for språket: En aktivitet kan være aktiv på flere språk samtidig. Du må skrive inn et navn for hvert språk du vil at den skal ha.

- Underavdelingene skal utføre aktiviteten: Krysses av hvis underavdelingene til den valgte avdelingen skal delta i aktiviteten.

- Hvor ofte skal aktiviteten utføres?: En gang er det vanlige, repeterende brukes dersom den skal kunne fylles ut et ubegrenset antall ganger av hver deltaker, periodisk brukes om aktiviteten skal gjennomføres i satte perioder - f.eks ukentlig. For periodiske aktiviteter må Fra og Til tidspunktet inneholde hele perioden. F.eks et helt år dersom man vil planlegge ukentlige aktiviteter for et helt år.

- Vil du ha tilsendt en e-postpåminnelse før tidsfristen går ut?: Sender en e-post til den som laget aktiviteten når en antall dager gjenstår av den. E-posten innholder forløbig oppsluttning og en link til oppfølgingsbildet.

- Det skal svares anonymt på denne aktiviteten: Avkryssningsboks som gjør aktiviteten anonym. Kommentarer til annonyme aktiviteter blir anonymisert.

- Antall besvarelser før resultatet vises: Vises kun når det er krysset av for anonymitet. Tallet gitt her styrer hvor mange besvarelser en enkelt avdeling må ha før det blir vist en graf for denne avdelingen. Ved for få svar må sumgraf fra overliggende avdeling benyttes for å få et resultat.

- Vis som liste/Vis som serie av enkeltspørsmål (kun påminnelseslink)/Vis som kontrolliste: Avgjør visningsformen for listen. Trykk på {{< onlystaticimg src="/images/Page.png" >}} ikonet for å se hvordan den valgte listen ser ut i denne visningsformen. Kun spørreskjemaer bør benytte Vis som serie av enkeltspørsmål. "Kun påminnelseslink" betyr at denne visningsformen kun benyttes når den som skal svare har kommet til listen ved å trykke på linken i den e-posten som er sendt ut som varsel for aktiviteten. Merk at for kontrolliste lages et avkryssningsfelt per dag per spørsmål. Den ser helt bort fra valgte svaralternativer.

- Aktivitetens distribusjon: Normal eller Revisjon. Revisjon gjør at aktiviteten kan besvares 1 gang per avdeling deltagerne har tilgang til. Benyttes som regel hvis man går en kontrollrunde eller revisjon som skal utføres av samme bruker flere steder. Dette valget er ikke med i standardversjonen. Dersom dere vil ha denne muligheten aktivert, ta kontakt med drift@qmplus.com.

- Roller som skal utføre aktiviteten: Ved å koble roller til en aktivitet blir det kun mulig å delta i denne for de brukerne som har den samme rollen. Kun disse vil telle med i aktivitetens oppsluttning.

- Legg dokumenter til aktiviteten: Dokumenter koblet til aktiviteten vil bli vist øverst i listen under overskriften.

### Tilgangskontroll
#### De ulike tilgangstypene gir disse rettighetene
- Lestilgang
  - Kan lese innholdet i en utfyllt aktivitet.
- Skrivetilgang
  - Kan fylle ut eller endre på innholdet i en utfyllt aktivitet.

#### Krav for å få de ulike tilgangstypene
- Lestilgang
  - Medarbeidere har lesetilgang for alle egne aktiviteter.
  - Ledere, saksbehandlere og verneombud har lesetilgang til alle aktiviteter innenfor deres ansvarsområde.

- Skrivetilgang
  - Medarbeidere og verneombud har skrivetilgang for alle egne aktiviteter innenfor perioden de kan fylles ut.
  - Ledere og saksbehandlere har skrivetilgang til alle aktiviteter innenfor deres ansvarsområde innenfor perioden de kan fylles ut
  - Superbrukere med systemrollen innholdsadministrator har skrivetilgang for alle aktiviteter innenfor deres ansvarsområde.