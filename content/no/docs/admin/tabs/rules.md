---
title: "Regler"
linkTitle: "Regler"
date: 2017-01-06
description: >
 Regler er en arkfane under Admin. 
---
Her kan du administrere regler. Regler brukes for å sette opp kriterier, som når de er tilfredsstilt, utløser spesifiserte reaksjoner. Slike reaksjoner kan bare defineres av QmPlus AS.

I gjeldende versjon, kan brukere, skjemaer, kategorier, avdelinger og i noen tilfeller henvendelsestype brukes som kriterier i en regel.

- Eksempel 1: Bruker Kåre Knall er ekstra saksbehandler for HMS-skjema og POL-Skjema fra og med avdelingene Teknisk, Kultur og Administrasjon.
- Eksempel 2: Brukerne Bård Kjekk og Anne Tøff varsles med e-post hver gang det registreres en melding med skjema HMS-Skjema og kategori Brannsikring fra og med avdeling Oppvekst og omsorg.

I gjeldende versjon, kan regler bare lages og endres av brukere som har systemrollen Innholdsadministrator eller Regeladministrator. 

Vær oppmerksom på at deaktiverte brukere, avdelinger, skjemaer eller kategorier er merket med "DEAKTIVERT". Disse reglene vil åpenbart ikke være gyldige. De slettes imidlertid ikke automatisk i tilfelle de deaktiverte brukerne eller avdelingene må erstattes med en annen. Brukerne som er ansvarlige for å lage regler bør gå gjennom dem av og til for å rydde opp.

### Regeltyper

Det er i gjeldende versjon 8 ulike regeltyper:

#### Ekstra saksbehandlere

Her kan du administrere hvem som skal dukke opp som ekstra saksbehandlere når "Send til saksbehandler" funksjonen brukes i meldingsbehandlingssiden

{{< onlystaticimg src="/images/SendTilSaksbehandler.png" >}}.

Ekstra saksbehandlere vises i nedfallsmenyen over mulige mottakere når "Send til saksbehandler" er valgt som handling i meldingsbehandlingssiden. Se bildet over.

Nedfallsmenyen inneholder automatisk alle brukere med systemrollen Standard mulig meldingsmottaker - i Standardversjonen: brukertype leder og saksbehandler fra de følgende stedene:

- Avdelingen den aktive brukeren har valgt i navigatoren.
- Avdelingen direkte over avdelingen den aktive brukeren har valgt i navigatoren.
- Alle avdelinger direkte under avdelingen den aktive brukeren har valgt i navigatoren.

Dette brukes når brukerne skal kunne sende meldinger uten å følge den vanlige linjen, for eksempel på tvers av organisasjonen eller rett til en fagansvarlig i en helt annen del av organisasjonen.

Dersom opsjonen for Automatisk tidlig saksbehandling er aktivert, så vil Ekstra saksbehandlere også tas med i nedfallsmenyen for valg av saksbehandler i Registrer ny melding.

Listen viser alle brukere som har blitt registrert som ekstra saksbehandlere i hele virksomheten. I kolonnen "Fra avdeling" i tabellen kan du se fra hvilken avdeling funksjonen trer i kraft.

Sett ikke opp ekstra saksbehandlere dersom du ikke er helt sikker på hva du gjør. Er du i tvil kontakt QmPlus AS for nærmere forklaring.

#### Tidlig saksbehandlere

Her kan du definere brukere som skal være standard saksbehandlere for ett eller flere meldingsskjemaer.

MERK: Regler for Tidlig saksbehandling er ment å håndtere unntak. Dersom man ønsker at alle meldinger som hovedregel skal sendes til nærmeste leder, bestill heller opsjonen for Automatisk tidlig saksbehandler.

{{< onlystaticimg src="/images/TidligSaksbehandling.png" >}}

Feltet som viser at et meldingsskjema er satt opp med "Tidlig saksbehandling" og Sjur Krog som standard saksbehandler heter Send til saksbehandler / linjeleder.

I "Fra avdeling" nedfallsmenyen, velg fra hvilken avdeling (inklusive) standard saksbehandler funksjonen vil gjelde. Dersom flere brukere er satt opp som standard saksbehandler fra ulike avdelinger for det samme meldingsskjemaet, blir brukeren tilhører den avdelingen som ligger nærmest avdelingen valgt i navigatoren når meldingen registreres være forhåndsvalgt i en nedfallsmeny i meldingsskjemaet.

En vanlig måte å bruke dette på er om du har et meldingsskjema som alltid skal gå til en spesiell mottaker uansett hvor i organisasjonen meldingen blir registrert.

Merk at når en melding får satt en tidlig saksbehandler på denne måten får den status sendt til saksbehandler i stedet for nye saker når den er registrert.

For skjemaer med Tidlig saksbehandlingsregler definert, vil aldri de Ekstra saksbehandlerne tas med i Registrer ny melding. Dersom opsjonen for Automatisk tidlig saksbehandler er skrudd på, vil egendefinerte regler med tidlig saksbehandlere overstyre de automatiske. Dersom man ikke ønsker å overstyre, men legge til, benyttes Ekstra saksbehandler regler som beskrevet i forrige avsnitt.

#### Opsjon

Som standard er ikke kategoriene en del av Tidlig saksbehandler reglene. Det finnes en opsjon som skrur det på. Det medfører at listen med mulige saksbehandlere lastes på nytt fra serveren ved hvert klikk på en kategori. Kontakt drift@qmplus.com om dere ønsker denne opsjonen aktivert.

#### Tiltaksgodkjennere

I utgangspunktet kan alle brukere med brukertype som inneholder systemrollen Behandle melding (leder eller saksbehandler i standardversjonen) behandle alle meldinger som de har tilgjengelig innenfor sitt ansvarsområde. For å begrense hvem som kan lukke enkelte meldinger kan du legge opp regler her. Disse reglene begrenser de følgende handlingene i meldingsbehandlingssiden:

- Avvis
- Avslutt saken.

I tiltaksbehandling begrenses handlingen:

- Godkjenn tiltak.

#### Informeres ved ny melding

Når en ny melding registreres vil brukere som tilfredstiller en av reglene her få tilsendt en beskjed om den nye meldingen. Kommentarkolonnen kan brukes for tilpassing av teksten i beskjeden. Beskjeden sendes enten som e-post, SMS eller begge deler. E-post er standard. De andre to typene (SMS, e-post og SMS) vises bare for de som har aktivert SMS modulen.
Informeres ved lukking av melding

Når en melding blir lukket vil brukere som tilfredstiller en av reglene her få tilsendt en beskjed. Kommentarkolonnen kan brukes for tilpassing av teksten i beskjeden. Beskjeden sendes enten som e-post, SMS eller begge deler. E-post er standard. De andre to typene (SMS, e-post og SMS) vises bare for de som har aktivert SMS modulen. En melding er definert som lukket når den kun er tilknyttet godkjente tiltak eller den er avvist.

#### Informeres ved brudd på terskelverdi

- Ved brudd på en terskelverdi, sendes det varsel til brukerne definert i regelen.
- Varslene sendes som epost ved kjøring av nattjobben, på lik linje som varsel for overskredet tidsfrist.
- Man kan velge mellom Periodisk varsel og Daglig varsel for diverse tidsrammer.
  - Et periodisk varsel sender varsel en gang etter at terskelverdien er brutt.
    - Dersom det blir lagt til brukere som skal varsles etter at et periodisk varsel er sendt eller utsendelse av epost til en av deltakerne feilet, så vil det sendes på nytt til disse ved neste anledning.
  - Daglige varsler sender varsel så lenge terskelverdien er brutt for den valgte tidsrammen, men kun hver gang nattjobben kjører for den aktuelle kunden.
- Terskelverdien måles kun mot antall meldinger.

#### Oppsett for dynamiske grafer

Brukes til å definere hvilke verdier som skal brukes på X-aksen og Y-aksen for de dynamiske grafene i Rapporter siden. De dynamiske grafene vises når man trykker på Dynamiske grafer, se bildet nedenfor.

{{< onlystaticimg src="/images/DynamiskeGrafer.png" >}}

Dersom det ikke er definert noen regler her, vil det ikke være noen Dynamiske grafer på Rapporter siden. Regler av denne typen lagres en rad om gangen. Lagresymbolet dukker opp straks du legger til en ny regel eller du endrer en eksisterende.

#### Oppsett for utregningsrapporter

Denne regeltypen kan brukes til å definere en utregning som kan vises under rapporttypen Uttregningsrapporter i siden Rapporter. Ta kontakt om det er behov for slike utregninger.

- Eksempel - Utregning av H-verdi = (antall personskader * 1000000) / Total antall timer brukt.

For å kunne bruke regnestykket over, så må det registreres meldinger i Qm+ med kategori for personskader. Det må også periodisk registreres totalt antall timer. Den periodiske registreringen av timer må også passe med perioden som brukes for å vise utregningsrapportene, om resultatet skal gi mening.

#### Filterregler

Dette er regler som kan brukes som en del av en regel for uttregningsrapporter for å dele opp restriksjonsuttrykkene.

- Eksempel - Ta kun med en kategori fra meldinger med et bestemt meldingsskjema med en gitt prioritet og legge verdien sammen med kategorier fra et annet skjema med en annen prioritet. Da kan man lage to ulike filtre og koble dem på hver sin kategori i utregningsreglen.

### Kolonner

- Navn: Navnet på brukeren som denne regelen gjelder.
  - For noen typer regler kan du velge mellom alle bruker i virksomheten, uavhengig av brukertype. For andre må brukertypen ha bestemte rettigheter for å kunne velges.
    - Eksempel: Rettighet for å sakbehandle en melding kreves for å kunne settes opp som tidlig saksbehandler.
  - Uten bruker vil regelen ikke ha noe effekt i systemet.
  - Flere brukere kan være i samme regel. Den vil da gjelde likt for alle de valgte brukerne.
  - Nedfallsmenyen i tabellhodet er et filter for tabellen under og inneholder kun brukere som allerede har en regel for den valgte regeltypen.
- Fra avdeling: Styrer hvilke deler av virksomheten regelen gjelder for.
  - Hvis avdeling ikke er satt, vil regelen gjelde for alle meldinger uavhengig av hvilken avdeling den blir registrert på.
  - Regelen vil gjelde fra og med den/de valgte avdelingen(e). Du kan velge mellom alle avdelinger fra og med avdelingen du er logget inn på.
  - Obligatorisk felt for Tidlig saksbehandler regeltypen, valgfritt felt for resten.
- Meldingsskjema: Styrer hvilke meldingsskjemaer regelen gjelder for.
  - Hvis meldingsskjema ikke er valgt, vil regelen gjelde for alle meldingsskjemaer.
  - Ellers gjelder den kun meldinger registrert i de spesifiserte meldingsskjemaene.
  - Du kan velge mellom de meldingsskjemaene som er tilgjengelig på avdelingen valgt i navigatoren.
- Kategorier: Styrer hvilke kategorier regelen gjelder for.
  - Hvis kategori ikke er valgt, vil regelen gjelde for alle meldinger.
  - Ellers gjelder den kun meldinger som har de de spesifiserte kategoriene krysset av.
  - Når du trykker på {{< onlystaticimg src="/images/Add.png" >}}, så vil det vises to nedfallsmenyer. Den første inneholder kategorigrupper og den andre kategoriene som tilhører kategorigruppen valgt i den første.
  - Vises ikke for regeltypen tidlig saksbehandler.
- Prioritet: Styrer hvilke prioriteter regelen gjelder for.
  - Hvis prioritet ikke er valgt, vil regelen gjelde alle meldinger uavhengig av prioritet.
  - Vises ikke for regeltypen tidlig saksbehandler.
- Kommentar: En kommentar til regelen.
  - Vises ikke for regeltypen Informeres ved ny melding.
- Send som: Bestemmer hvordan det automatisk varslet skal sendes.
  - Mulige valg er e-post, SMS og Epost og SMS.
  - Vises kun for regeltypen Informeres ved ny melding for kunder som har SMS aktivert, for andre blir e-post valgt automatisk.
- Tekst for SMS / Epost varsel: Her kan man legge inn en ekstra tekst som sendes sammen med varselet om ny melding til brukerne definert i kolonnen Navn for meldinger som tilfredsstiller kriteriene i resten av kolonnene når en ny melding blir registrert.
  - Vises kun for regeltypen Informeres ved ny melding.
- Tidsrom: Sett et tidsrom som begrensing. Kun mulig med en verdi for Terskelverdiregler som er eneste type som bruker denne.
  - Periodisk varsel. Varsel sendes ut ved første gang terskelverdien brytes.
  - Daglig varsel. Varsel sendes ut hver gang terskelverdien er brutt.
- Terskelverdi: Sett et antall meldinger som må oppfylle kravet i regelen for at varselet skal sendes ut. Kun mulig med en verdi for Terskelverdiregler som er eneste type som bruker denne.
- Endre: Brukere som kan lage og redigere regler får her ikonet {{< onlystaticimg src="/images/Delete.png" >}}. Det kan brukes til å slette en regel.

### Knapper

- {{< onlystaticimg src="/images/Wrench.png" >}} Ny regel: Lager en ny regel uten kriterier. Denne vises som en tom rad markert med gult i tabellen. Trykk på {{< onlystaticimg src="/images/Add.png" >}} til en eller flere av kolonnene for å legge til kriterier. Knappen vises bare for brukere med brukertype leder på den øverste avdelingen og brukere som har systemrollen Innholdsadministrator.

### Ikoner

Når du holder pekeren over data i noen kolonner i tabellen, kan det være du ser at den endrer form. I noen nettlesere ser den slik ut: {{< onlystaticimg src="/images/Pencil.png" >}}, mens i andre vil den se ut som hånd ikonet. Dette betyr at feltet i tabellen er redigerbart. Trykk på feltet for å redigere det. Når du har trykket på et felt vises de følgende ikonene (Merk: Ikons beskrevet nedenfor vises bare for brukere med brukertype leder på øverste avdeling og brukere som har systemrollen Innholdsadministrator):

- {{< onlystaticimg src="/images/Accept.png" >}} Lagre: Lagrer endringen.
- {{< onlystaticimg src="/images/Cancel.png" >}} Avbryt: Avbryter endringen. Feltet får sin forrige verdi.
- {{< onlystaticimg src="/images/Delete.png" >}} Slett: Sletter det valgte kriteriet fra regelen eller hele regelen (hvis du trykker på ikonet i Endre kolonnen).
- {{< onlystaticimg src="/images/Arrow_refresh.png" >}} Angre: Vises etter at du har lagret en endring. Feltet får tilbake sin tidligere lagrede verdi.
- {{< onlystaticimg src="/images/Add.png" >}} Ny: Legger til et nytt kriterie i den valgte kolonnen til denne regelen.
