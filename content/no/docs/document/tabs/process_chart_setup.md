---
title: "Prosesskartoppsett"
linkTitle: "Prosesskartoppsett"
date: 2017-01-06
description: >
 Prosesskartoppsett: Brukes til å redigere innholdet i et dokument av typen "Prosesskart". Dette er dokumenter som skrives rett inn i Qm+. Åpnes fra Endre data for dokumentet. 
---
Prosesser laget i denne siden kan vises på to måter. Som prosesskart eller som ansvarsmatrise. Når dokumentet åpnes, vil det først vises som prosesskart. Derfra vil du kunne endre visning til ansvarsmatrise om minst en av fasene i prosessen er tilordnet en ansvarlig. Dokumentet vil også automatisk få et dokumenthode med informasjon om dokumentet, tilsvarende det tekstdokumenter skrevet i har Qm+.

Denne siden er delt i to deler. Den venstre siden viser en trestruktur for prosessen, mens den gøyre viser detaljer for den delen av treet som er valgt i den venstre siden. 

### Generelt

- Når du oppretter en ny prosess, så får den samme navn som dokumentet den er laget i. Dette kan du endre.
- Et prosesskart kan lages for alle språk tilgjenglig i systemet.
- En prosess kan inneholde steg (noe som skal utføres i en rekkefølge) eller oppgaver (kan utføres i vilkårlig rekkefølge). Du kan ikke ha både steg og oppgaver på samme nivå. En ny prosess inneholder som standard 4 steg. Disse kan du så endre og tilpasse. Når man ser på prosesskartet, vises steg i gult og oppgaver i blått. Vi bruker fase som fellesbetegnelse for steg og oppgaver.
- Hver fase kan ha en eller flere ansvarlige. Det må tilordnes ansvarlige til minst en fase om prosessen skal kunne vises som ansvarsmatrise. Ansvarlige kan være av typene:
  - Objekt: bruker, rolle, brukertype, avdeling.
  - Tekst: tekstfelt med begrenset størrelse (50 bokstaver).
- Hver fase kan ha attributter (selv om det er en prosess med underprosesser). Attributtene kan være av type:
  - Objekt: bruker,rolle, brukertype, meldingsskjema, dokument eller avdeling.
  - Tekst: begrenset lengde, vises inne i samme boks som navnet på steget/oppgaven (50 bokstaver).
  - Notat: lenger tekstfelt som vises i egen tabell under prosesskartet.

### {{< onlystaticimg src="/images/64px-Monitor.png" >}} Interaktiv opplæring

Her kan du lære:

- Opprette prosesskart
- Ansvarskoder
- Steg
- Attributt
- Oppgaver

{{< onlystaticimg src="/images/Page_white_acrobat.png" >}} 
{{< assetlink src="/assets/prosesskart.pdf" title="pdf" >}}

### Hvordan lage et prosesskart

Etter at du har laget et nytt dokument av typen prosesskart og fyllt inn de vanlige dokumentrelaterte opplysningene, så trykker du Lagre. Dette gjør arkfanen Prosesskartoppsett vises. Når du trykker på den første gangen, lager systemet automatisk en prosess med samme navn som dokumentet som inneholder 4 hovedsteg. Om du ser på treestrukturen til ventre i bildet, så ser du disse 4 stegene. Hver gang du trykker på en fase i treet, så viser den høyre delen av bildet informasjon om den aktuelle fasen. Fasene i treet kan klikkes på med høyre musetast for en hurtigmeny for å utføre operasjoner på den aktuelle fasen. Dette er som regel mye raskere enn å bruke tilsvarende knapper i det høyre hovedbildet.

#### Endre prosessen
{{< onlystaticimg src="/images/Keyboard.png" >}} Språkinnstillinger

Her vises språkene som er tilgjengelig i din virksomhet. Kryss av for de språkene du ønsker prosesskartet skal være tilgjenglig i og gi det navn i alle språkene. Språkene du velger her vil gjelde for hele prosesskartet.

#### {{< onlystaticimg src="/images/Group_gear.png" >}} Velg ansvarskoder for prosessen

Her kan du velge hvilke av de tilgjenglige ansvarskodene som skal brukes i dette prosesskartet. Velg de du ønsker fra listen til høyre og trykk på Legg til knappen. Ansvarskodene du velger her vil senere kunne brukes når du legger til ansvarlige for de ulike fasene. Dersom du trenger å lage en ny ansvarskode, så kan du lukke dette vinduet og trykke på {{< onlystaticimg src="/images/Group_add.png" >}} Ny ansvarskode knappen. Det vil ta deg til ansvarskode arkfanen hvor du kan lage den nye ansvarskoden. Når du trykker Lagre og Lukk der, vil du komme tilbake til denne siden. Det må tilordnes ansvarskoder til prosessen om den skal kunne vises som ansvarsmatrise.

#### Sett standard attributt type

Her får du en liste med de tilgjengelige attributtypene. Det du velger her vil være forhåndsvalgt hver gang du legger til en ansvarlig eller et attributt av typen Objekt til en fase. Om du ikke velger noe her, vil typen øverst i listen være forhåndsvalgt. Denne operasjonen er kun ment for å spare arbeid senere og har ingen effekt utover dette.
Endre en fase

#### {{< onlystaticimg src="/images/Stepimage.png" >}} Legg til steg

Her kan du legge inn navnet på steget i alle språkene du valgte i Språkinnstillinger tidligere. Du kan også legge inn posisjon, som viser hvor i rekkefølgen dette steget kommer. Denne knappen er kun synlig om det ikke er laget noen faser av typen oppgave på dette nivået.

Merk: Som standard settes prosessen opp med 4 hovedsteg. Du kan lage flere av dem om du bruker denne knappen når prosessnavnet er valgt i treet, eller du høyreklikker på denne. Hvis prosessen din skal bestå av oppgaver istedet for steg, så må du slette de eksisterende stegene. Det gjør du ved å høyreklikke på et steg i treet og velge Slett. Når alle stegene er slette, vil muligheten for å legge til oppgaver bli synlig.

#### {{< onlystaticimg src="/images/Taskimage.png" >}} Legg til oppgave

Her kan du legge inn navnet på steget i alle språkene du valgte i Språkinnstillinger tidligere. Du kan også velge posisjon, som kun vil påvirke hvor oppgaven vil vises i trestrukturen under den overliggende fasen. Denne knappen er kun synlig om det ikke er laget noen faser av typen steg på dette nivået.

#### {{< onlystaticimg src="/images/Shape_align_center.png" >}} Importer prosesskart

Med denne knappen kan du importere et eksisterende prosesskart inn i dette prosesskartet. Endringer utført på orginalen etter importen vil ikke påvirke dette prosesskartet. Du kan også fritt endre enhver av de importerte fasene uten at det påvirker prosesskartet som ble importert. Denne knappen er kun synlig om det ikke er laget noen faser på dette nivået.

#### Endre

Denne muligheten vises når du høyreklikker på en fase i teet og gir samme muligheter som de so vises på høyre side når du trykker på fasen i treet med venstre museknapp.

#### Slett

Denne muligheten vises når du høyreklikker på en fase i teet. Hvis fasen du forsøker å slette har underfaser blir du spurt om hva du vil gjøre med disse. Du kan enten slette dem eller flytte dem under en annen fase. Dersom fasen du forsøker å slette ikke har underfaser, vil du kun bli spurt om du virkelig ønsker å slette fasen.

#### Legg til ansvarlig

Her kan du velge hvem som skal være ansvarlig for den valgte fasen og hvilken ansvarskode den ansvarlige skal ha. Du kan ha flere ansvarlige for samme fase, både med samme eller ulik ansvarkode. Når du legger til en ansvarlig, velger du først ansvarskoden, deretter typen til den ansvarlige. Du kan velge mellom objekt eller tekst. Velg objekt om du ønsker å tilknytte enten en bruker,rolle, brukertype eller avdeling (her vil den typen du har valgt som standard attributtype være forhåndsvalgt). Hvis ikke, velger du tekst som gir deg muligheten til å legge inn en kort beskrivende tekst (maks 50 tegn). Alle ansvarlige du legger til her, vil vises i en tabell under Legg til ansvarlig knappn. Der vil du senere kunne gjøre endringer ved å bruke knappene for {{< onlystaticimg src="/images/Group_edit.png" >}} endre eller {{< onlystaticimg src="/images/Group_delete.png" >}} slette.

#### Legg til attributt

Her kan du legge til flere attributrer til fasen. Først velger du typen til attributtet. Her vil den typen du har valgt som standard attributtype være forhåndsvalgt. De tilgjenglige typene er:

- Objekt: Gir ekstra valg av objekttype:
  - Bruker: Brukerens navn vises i prosesskartet.
  - Rolle: Rollens navn vises i prosesskartet.
  - Brukertype: Brukertypens navn vises i prosesskartet.
  - Avdeling: Avdelingens navn vises i prosesskartet. Denne fasen vil vises som standard når prosesskartet vises senere dersom samme avdeling er valgt i navigatoren.
  - Dokument: Dokumentets navn vises i prosesskartet sammen med dokumentikonet. Trykker man på navnet eller ikonet, vil dokumentet åpnes i et eget vindu. Dokumentattributter vises også i ansvarskartet.
  - Meldingsskjema: Skjemaet navn, sammen med meldingsskjemaikonet vises i prosesskartet. Trykker man på skjemaet der, vil det åpnes klart til utfylling.
- Tekst: Tekstfelt med begrenset størrelse (50 tegn).
- Notat: Gir mulighet for å skrive en lengre tekst. I prosesskartet vises notater kun som ordet notat med et nummer bak i listen over attributter. Selve notatteksten vises i en egen tabell nederst i siden.

Du kan også velge posisjon som bestemmer rekkefølgen til attributtene i fasen.

Alle attributter du legger til vil vises i tabellen under knappen. Der kan du senere endre attributtene ved å bruke {{< onlystaticimg src="/images/Group_edit.png" >}} endre eller {{< onlystaticimg src="/images/Group_delete.png" >}} slette.

### Visning

Et dokument av typen prosesskart kan vises på to måter: som {{< onlystaticimg src="/images/Shape_align_center.png" >}} prosesskart (grafisk presentasjon av prosessen) eller {{< onlystaticimg src="/images/Application_side_tree.png" >}} ansvarsmatrise (dersom noen ansvarlige er lagt til prosessen). Knapper for å åpne disse bildene vises nederst på siden og åpner visningen i et nytt vindu.

- Når dokumentet er åpnet, får det automatisk et dokumenthode med informasjon om dokumentet, likt den tekstdokumenter skrevet i Qm+ får.
- Begge visningsmåtene kan eksporteres til en .pdf fil. Om man trykker på Vis som pdf knappen åpnes Alternativer for prosessrapporter.

#### Prosesskart

- Navnet på prosessen vises sentralt over selve prosesskartet.
- Steg vises som gule bokser. De er forbundet med overliggende faser via svarte piler.
- Oppgaver vises med blå bokser og er forbumnet med overliggende faser med små, blå piler.
- Dersom visning av hele prosesskartet ikke er skrudd på, så kan de fasene som har underliggende faser trykkes på for å utvide den delen av prosesskartet.

#### Velg hva du vil se

Øverst til høyre ser du et felt som inneholder avkryssingsfelt for hva som skal vises i prosesskartet. Det som er krysset av her vil også være med om man bruker Vis som pdf knappen.

- Vis ansvarlige: Skrur visningen av de ansvarlige av og på. De ansvarlige vises med ansvarskode og navn med rød skrift i de fasene de er lagt inn.
- Vis attrbutter:
  - Meldingsskjemaer vises med blå skrift og har ikonet {{< onlystaticimg src="/images/Application_form_edit.png" >}} forran. Om man trykker på navnet eller ikonet vil vinduet med prosesskartet lukkes og skjemaet kommer opp klar til utfylling. Når du lukker meldingsskjemaet blir du tatt tilbake igjen til siden du åpnet prosesskartet fra.
  - Dokumenter vises med blå skrift og har ikonet {{< onlystaticimg src="/images/Link.png" >}}. Om du klikker på navnet på dokumentet eller ikonet åpnes dokumentet i et nytt vindu.
  - Notater vises som Notat<nummer> med cvart skrift i prosesskartet. Disse kan trykkes på og endrer da fokus til tabellen under prosesskartet hvor notatene er listet opp.
  - Alle andre typer attributter vises med svart skrift. Det har ingen effekt å trykke på de.
- Vis hele prosesskartet: Skrur visning av hele prosesskartet av og på. Når denne er skrudd av, vises kun fasene på første nivå. Dersom noen av disse har underfaser, så kan de trykkes på for å vise disse. Hvis musepekeren bli til en hånd når du holder pekeren over fasen, kan den trykkes på for å utvides.

#### Ansvarsmatrise

Dersom en prosess har minst en ansvarlig definert for en fase, kan prosessen vises som en ansvarsmatrise. Ansvarsmatrisen lister opp alle fasene i en trestruktur sammen med navnene på de ansvarlige og ansvarskoden de har i de ulike fasene.

- Dersom en fase har et dokumentattributt, vises ikonet {{< onlystaticimg src="/images/Link.png" >}} ved siden av prosessnavnet. Trykker du på dette vil feltet uvide seg og vis navnene på alle dokumentattributter i den fasen. Disse kan igjen trykkes på for å åpne de aktuelle dokumentene.
- Under ansvarsmatrisen ligger en egen tabell med navnene og informasjonsfeltene for alle ansvarskodene tilknyttet denne prosessen.
