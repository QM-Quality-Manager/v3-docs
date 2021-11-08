---
title: "Definisjoner"
linkTitle: "Definisjoner"
date: 2017-01-06
description: >
  Oversikt over definisjoner.
---
# Arkfane
Navigasjonsstrukturen i Qm+ er bygd opp av arkfaner.

De har et navn som beskriver det stedet i systemet man kommer til hvis man trykker på den. De fleste har også en beskrivende tekst som kommer opp når man holder musepekeren i ro over den.

Arkfanene beskriver også hvor i systemet man er. De arkfanene som er mørkere enn de andre er valgt.

Eksempel :

{{< onlystaticimg src="/images/Arkfanebeskrivelse.png" >}}

Her står vi i Arkiv / Meldinger/UH / Nye saker.

# Sak
En sak i Qm+ er enten en melding, et tiltak, en høring eller en revisjon. 

# Risikomelding
Risikomeldinger er meldinger som brukes for å lage en risikooversikt for virksomheten. Det er opp til virksomheten om risikomeldingene skal behandles eller om de kun skal registreres og lagres i arkivet. Vår anbefaling er at de ikke behandles, kun oppdateres årlig. Risikomeldinger kan bare lukkes av QmPlus AS (som et unntak), siden de normalt ikke skal behandles. Meldinger registrert her dukker ikke opp i Innboks med mindre man bruker behandling for å aktivere dem. Meldingstypen risikomelding er ikke aktivert i standardversjonen. 

# Sjekkliste
En sjekkliste er en liste som blir vist med avkryssningsfelt forran spørsmålet. For å kunne redigere svaralternativer må listetypen spørreskjema benyttes. En sjekkliste er tenkt brukt som en "finn feilen liste". Dvs list opp en rekke vanlige feil innenfor det området som skal undersøkes. Brukerne krysser så av for punktet i listen dersom de kjenner til feilen. Se liste for forklaring på datafeltene. 

# Standard saksbehandler
Hvis et meldingsskjema har satt en standard saksbehandler vil meldinger registrert med dette meldingsskjemaet dukke opp i Saker jeg er ansvarlig for siden til standard saksbehandleren i stedenfor til lederen på avdelingen der meldingen ble registrert. Meldingen vil fremdeles være registrert på avdelingen den ble registrert og vises der i rapporter og søk.

Dersom samme meldingsskjema er satt opp med flere standard saksbehandlere med overlappende avdelinger vil melderen kunne velge mellom disse i en nedfallsmeny når meldingen registreres. I registreringsbildet er det også et avkryssningsfelt for om det skal sendes epost til den valgte saksbehandleren når meldingen registreres. 

# Superbruker
Superbrukeren er en bruker som har bestått superbrukerkurset for Qm+. Superbrukeren har virksomhetens høyeste tilgang til Qm+. Dette betyr tilgang som brukertypen leder uten begrensende roller og ofte noen ekstra systemroller.

Superbrukeren skal bistå de andre brukerne i virksomheten og fungere som lokal brukerstøtte for Qm+.

Alle superbrukere har rett på gratis telefonsupport fra Qm+ og kan benytte seg av denne dersom han mottar spørsmål fra sin virksomhets brukere han trenger hjelp til å besvare. En eller fler av virksomhetens superbrukere fungerer som regel også som kontaktperson for virksomheten mot QmPlus AS.

Alle ønsker om endret funksjonalitet i systemet må formidles via kundens kontaktperson slik at vi vet at ønsket har støtte i hele virksomheten. 

# Svaralternativgruppe
En samling med svaralternativ som kan kobles til spørsmål i et spørreskjema. Vedlikeholdes i svaralternativgrupper.

En svaralternativgruppen sorterer under en bestemt svaralternativgruppeoversikt. Dette brukes kun til å skille svaralternativgrupper fra hverandre i endre svaralternativer og svaralternativgrupper. 

# Svartype
Hvert spørsmål i en liste kan ha en svartype.

**Svartypene:**
- Enkeltvalg: En avkryssningen til hvert spørsmål. Er det først krysset av for et spørsmål må spørsmålet besvares. Dette er standardvalget som blir brukt dersom det ikke foretas en endring.
- Flervalg: Ingen til alle svaralternativene til hvert spørsmål kan krysses av.
- Tekst: Det blir ikke vist noen avkryssningsboks for dette spørsmålet, kun kommentarfelt. Fungerer ikke for listeversjon.
- Fritekst tall: Et tall kan skrives inn som svar på dette spørsmålet. Grafen vil vise summen av alle tallene skrevet inn til et slikt spørsmål.

Tips: Bruk svartype Flervalg for spørsmål med kun ett svaralternativ, slik som i en sjekkliste. Ellers vil det ikke være mulig å ta vekk avkryssingen om man skulle ombestemme seg. 

# Søkekriterie
Søkekriterie er det som er søkt etter når man gjør et søk.

Vises som en tabell over søkeresultatet etter et utført søk. Søk kan startes fra Rapporter, Søk meldinger, Søk tiltak eller ved å trykke på risikomatrisen i Risiko. Alle søkeresultater vises i tabellform i Arkiv eller som grafer under Rapporter under sin tilhørende Arkfane.

- Alle data vist i nedfallsmenyer kan endres. Slike endringer medfører at søket oppdaterer seg.
- Data etterfulgt av {{< onlystaticimg src="/images/Delete.png" >}} kan fjernes fra søkekriteriene. Det medfører at søket oppdaterer seg.

# Tiltaksprosessen
Tiltaksprosessen er prosessen fra et tiltak opprettes til det blir godkjent og lukket.

Følges opp gjennom tiltaksbehandling.

- Under planlegging: Alle tiltak starter med denne statusen. I denne fasen skal tiltaket planlegges. Gi først tiltaket et navn slik at det blir lett å identifisere senere, og fyll inn kostnadsrammen dersom dere bruker dette feltet. Tekstfeltene Korrigerende tiltak og Hvordan hindre gjentakelse må fylles ut slik at de som skal gjennomføre tiltaket skjønner hva de skal gjøre. Tiltakskategoriene kan også fylles ut nå. Siste punkt er å plukke ut de som skal utføre tiltaket og gi dem en frist. Dette gjøres i det obligatoriske Oversikt over ansvarlige feltet. Trykk så på Send til gjennomføring >> eller >> knappen i statusfeltet for å lagre tiltaket og skifte status til Under gjennomføring.
- Under gjennomføring: I denne fasen skal jobben som beskrives i tiltaket gjennomføres. Deretter skal det krysses av for utført av de som utført tiltaket. Det kan også skrives en kommentar i kommentarfeltet og den faktisk kostnaden kan fylles hvis den er tilgjengelig. Når alle avkryssninger er gjordt, brukes knappen Send til godkjenning eller >> knappen i statusfeltet. Dette lagrer tiltaket og endrer status til Under godkjenning.
- Under godkjenning: Her skal den som opprette tiltaket kontrollere at alt er i orden før tiltaket godkjennes.
- Godkjent: Et godkjent tiltak er lukket og låst og kan ikke endres annet enn av brukere med systemrollen innholdsadministrator. Kommentarer til alle involverte brukere kan fortsatt sendes.

# Visningsform
Styrer hvordan listen blir vist.

Mulige visningsformer: Papirversjon, listeversjon (eller listeform), Vis som enkeltspørsmål. 

# Definerende kategori
En definerende kategori er den kategorien som beskriver hva meldingen dreier seg om. Det er obligatorisk å krysse av for en definerende kategori for at et meldingsskjema skal kunne lagres. En definerende kategori defineres ved at den tilhører en kategorigruppe med kategorigruppetypen definerende. I et meldingsskjema blir definerende kategorier markert med ikonet Tag blue.png og de er alltid enkeltvalg. Kun en definerende kategori kan være avkrysset per melding. Dersom det er flere kategorigrupper av typen definerende kategori, kan kun en av dem være avkrysset. 

# Delplan
Aktiviteter organiseres i delplaner.

Denne organiseringen har ingen betydning i systemet utover det å gjøre det enklere å finne frem til aktiviteter når det bli mange av dem. I Kalender under Aktivitetsplan blir aktivitetene vist per delplan

# Mobilversjonen
Mobilversjonen av Qm+ er et eget grensesnitt tilpasset visning på mobile enheter. Tilpassningen gjøres ved at det kun sendes over det aller nødvendigste av informasjon og alt vises som korte tekster. Det er mulig å registrere både meldinger, sjekklister og spørreskjemaer i denne versjonen. All informasjon registrert er er synlig i den vanlige Qm+ versjonen på samme måte som ellers.

Startsiden for mobilversjonen er wap.qmplus.net. Pålogging skjer ved bruk av samme virksomhet, brukernavn og passord som ved vanlig pålogging.

Mobilversjonen er en ekstramodul som må bestilles spesielt.

# Endre dato
Endre dato er en funksjon for å endre enkeltdatoer for periodiske aktiviteter.

Tilgjengelig fra aktiviteter.

##### Felter
- Fra: Tidspunktet aktiviteten starter.

- Til: Aktiviteten avsluttes.

##### Knapper
- {{< onlystaticimg src="/images/Tick.png" >}} Lagre: Lagrer endringene utført i feltene.

- {{< onlystaticimg src="/images/Cross.png" >}} Lukk: Tar deg tilbake til siden du kom fra.

# Prioritet
Meldinger i Qm+ kan ha ulik prioritet. 

- Lav: Markeres med grønt.
- Middels: Markeres med gult.
- Høy: Markeres med rødt.

Et tiltak får samme prioritet som den meldingen med høyest prioritet den har tilkoblet. 

# Kategori
En kategori er i de fleste tilfeller et avkryssningspunkt i et meldingsskjema. Alle kategorier er med i en kategorigruppe. Kategorigruppetypen til kategorigruppen bestemmer hvordan kategorien blir vist i meldingsskjemaet. All informasjon som blir lagt inn i forhold til en kategori i et meldingsskjema kan hentes ut som en rapport via Rapporter. Kategoriene kan også brukes til å finne frem til grupper av bestemte meldinger via søksidene for meldinger og tiltak.

Vedlikeholdes under endre kategori.

#### Data

- Vis for språket: Brukes for å velge språket navnet på Kategorigruppen skal redigeres for. Vises bare for kunder som har flere aktive språk.
- Kategorigruppe: Kategoriens gruppe.
- Kategorinavn: Navnet som blir brukt til å representere kategorien. En kategori kan ha et navn per aktive språk i systemet.
- Prioritet: Lav, Middels, Høy. Den forhåndsdefinerte prioriteten til en kategori. Kan overstyres av den som fyller ut et meldingsskjema. En meldings prioritet blir den høyeste prioriteten til de avkryssede kategoriene med mindre den blir overstyrt av brukeren.
- Kostnad: Den forhåndsdefinerte kostnaden for en kategori. Kan overstyres av den som fyller ut et meldingsskjema. En meldings kostnad blir summen av kostnadene til de avkryssede kategoriene, med mindre den overstyres av brukeren. Kostnadsfunksjonaliteten kan fjernes for de som ønsker det.
- Fra avdeling: Avdelingen kategorien er tilgjengelig fra.
- Tilknyttet dokument: Et dokument som vil aktiveres dersom man trykker på kategorien i meldingsskjemaet.
- Informasjon: Tekstfelt som blir synlig når man holder pekeren over kategorien i meldingsskjemaet.
- Risikodata: Vises kun for kategorier som tilhører en kategorigruppe med Kategorigruppetypen risiko. Brukes for å sette ulike akseptansekriterier for ulike risikokategorier.
  - Start gult risikoområde: Oversikter for denne kategorien vil gi gul risikoverdi fra og med denne risikoverdien.
  - Start rødt risikoområde: Oversikter for denne kategorien vil gi rød risikoverdi fra og med denne risikoverdien.

# Kategorigruppetype
Kategorigruppetypen til en kategorigruppe bestemmer hvordan kategoriene i gruppen vises og besvares i et meldingsskjema.

#### Typer

##### Definerende kategori

Er ment til å beskrive hva som er temaet for en melding. Enkeltvalg for hele meldingsskjemaet. Dersom det er flere definerende grupper i et meldingsskjema, vil det kun være mulig å krysse av for en kategori i en av gruppene. Et meldingsskjema kan bare lagres dersom en kategori som tilhører en definerende kategorigruppe er krysset av. Definerende kategorier er de eneste som i utgangspunktet er obligatoriske å fylle ut i et meldingsskjema. Definerende kategorier vises som standard øverst til venstre med en oransj bakgrunnsfarge og er markert med ikonet Tag blue.png.

##### Enkeltvalg

Brukes for å gi utfyllende informasjon i et meldingsskjema. Enkeltvalg per gruppe. Vises til venstre under de definerende kategoriene.

##### Flervalg

Brukes for å gi utfyllende informasjon i et meldingsskjema. Vilkårlig mange kan krysses av. Vises til høyre.

##### Tiltak

Brukes for å gi utfyllende informasjon om hva slags tiltak som bør brukes for å ta seg av forholdene meldingen dreier seg om. Vilkårlig mange kan krysses av. Kategorier i denne gruppen blir tatt med videre i tiltaket dersom det lages et tiltak for en melding. Vises sentralt under tekstfeltene i meldingsskjemaet.

##### Tall

Gir et tekstfelt der et vilkårlig tall kan skrives inn. Velges en gruppe av denne typen under Rapporter vil kostnadsgrafen være byttet ut med en graf som viser summen av verdiene i disse feltene. Vises til høyre i meldingsskjemaet.

##### Risiko

Hver kategori av denne typen får to nedfallsmenyer der en verdi fra 1 til 5 kan velges. Den første symboliserer sannsynligheten for at hendelsen vil intreffe den andre konsekvensen. Disse verdiene blir automatisk multiplisert til en risikoverdi. Risikoverdien får en farge basert på grenseverdiene som er satt for kategorien. Meldinger med verdier > 0 for en risikokategori kommer opp i risikorapporten under Rapporter. Vises sentralt i meldingsskjemaet under tiltakskategoriene. 

# Kommentarmelding
Kommentarmeldinger er meldinger som er registrert som svar på en liste delt ut via Aktivitetsplan. Kommentarmeldinger er registrert i et vanlig meldingsskjema. Bare det første tekstfeltet i melsdingsskjemaet som er koblet sammen med listen vises som kommentarfelt inne i listen.

Kommentarmeldinger kan behandles som andre meldinger. I standardversjonen vises ikke kommentarmeldinger under Innboks med mindre noen overfører dem til en saksbehandler, har gitt dem en frist eller laget et tiltak til dem.

Kommentarer til aktiviteten i Aktivitetsplan brukes for å få en oversikt over alle kommentarmeldinger for en aktivitet.

For en oversikt over alle kommentarmeldinger kan Kommentarer under Rapporter eller Kommentarer under Arkiv brukes. 

# Listeversjon
Visningsform for lister. Brukes fortrinnsvis til sjekklister og risikoanalyser. Viser alle spørsmålene i en liste. Kommentarmuligheten kommer opp på side to etter at Lagre er trykket på.

Alle lister som vises når man er pålogget Qm+ på vanlig måte, dvs ikke pålogget via link i e-post direkte til listen bruker listeversjonen. 

# Loggmelding
Loggmeldinger er meldinger som normalt ikke behøver å behandles, kun registreres og lagt i arkivet. Eksempler på slik bruk kan være: referater og dokumentasjon av rett utførelse. Loggmeldinger vises derfor ikke under Innboks med mindre man bruker behandling for å aktivere dem. I Rapporter vises de i en egen arkfane. Meldingsskjemaer for å fylle ut loggmeldinger vises med grønn knapp i Innboks, istedet for den vanlige gule for vanlige meldinger.

Meldingstypen loggmelding er ikke aktivert i standardversjonen.

Loggmeldinger er på alle andre måter identiske med vanlige meldinger. 

# Medarbeider
Brukertype i standardversjonen som gir brukeren et enkelt skjermbilde der kun brukerens egne saker kan endres. 

# Meldingstype
Alle meldinger har en meldingstype. En melding får den meldingstype meldingsskjemaet den ble registrert med har.

#### De ulike meldingstypene

- Melding: Vanlige meldinger.
- Loggmelding: Registreres under Logg under Arkiv. Ikke med i standardversjonen.
- Risikomelding: Registreres under Risiko under Arkiv. Ikke med i standardversjonen.

Dersom hverken loggmeldinger eller risikomeldinger er aktivert i ditt system vil ikke betegnelsen meldingstype bli brukt der. 

# Periodisk aktivitet
En periodisk aktivitet brukes når du vil planlegge en periodisk utførelse av en aktivitet fremmover i tid. Perioden er hvor hyppig aktiviteten skal utføres for eksempel daglig, ukentlig, årlig.

Perioden og de individuelle datoene vedlikeholdes i Oppsett av periodisk aktivitet og de andre [[aktivitet|aktivitetsdatane] i endre aktivitet. Individuelle datoer for en periodisk aktivitet kan slettes i aktiviteter. 

# Rolle
En rolle kan kobles mot brukere, brukertyper, avdelinger, aktiviteter, meldingsskjemaer og dokumenter. De gir rettigheter og restriksjoner. Generelt kan man si at en bruker, brukerens brukertype eller brukerens avdeling må ha den samme rollen som en aktivitet, meldingsskjema eller dokument for å ha tilgang til denne. Vanlige roller kan lages av kundens superbruker.

Roller sorteres i rollegrupper og vedlikeholdes i endre rolle.

En spesiell type roller kalles systemrolle de gir utvidede rettigheter til bruk av Qm+. Systemrollene lages av QmPlus AS men kan tilordnes av enkelte superbrukere. Dette er avansert funksjonalitet og er som regel ikke slått på ved oppstart for nye kunder. Ta kontakt med drift@qmplus.com ved behov for denne rettigheten eller spørsmål.

#### Data

- Navn: En rolle kan ha et navn per språk som er aktivert i systemet.

# Skriv ut
Åpner utskriftsdialogen til nettleseren for å skrive ut de aktive siden.

Dersom du ikke vil ha ut hele bildet eller skriv ut kommandoen ikke skriver ut den delen av skjermbildet du ønsker deg, kan du prøve å trykke med høyreknappen i det feltet du ønsker skrevet ut. Velg så Skriv ut fra menyen som kommer opp.

For brukere med høy skjermoppløsning kan utskriften bli større enn arket det skal skrives til. Triks for å rette på det:

    Velg redusert størelse for utskriften. Hvordan det gjøres varierer mellom ulike nettlesere og printere. Se etter Skalering, Reduce/Enlarge eller annet oppgit i %. Slikt befinner seg i de fleste tilfeller under avanserte muligheter.
    Reduser størelsen på nettleservinduet ditt dvs, dra det sammen slik at det ligner mer på arket du skal skrive til.
    Sett lavere oppløsning for skjermbildet ditt.
    Ta bilde av siden du vil skrive ut og lim den inn i et eksternt program, f.eks Word eller et bildeprogram, før du skriver siden ut derfra. Bilder tas ved å trykke på Prt Scr (Print screen) på tastaturet og limes inn ved ctrl + v i ønsket program.

Dersom du ønsker å lagre siden som en pdf-fil istedenfor å skrive den ut på en skriver last ned og installer programmet PDFCreator. Neste gang du velger Skriv ut eller trykker Ctrl + P i nettleseren vil du da kunne velge PDFCreator som skriver. 

# Standardversjonen
Standardversjonen av Qm+ er det sett med systeminnstillinger som gis til nye kunder dersom de ikke ber om noen endringer.

Kundens kontaktperson mot QmPlus AS kan bestille endringer fra standardversjonen. De fleste endringer av systeminnstillinger gjøres kostnadsfritt. Ta kontakt med drift@qmplus.com ved spørsmål eller endringsønsker.

Se Systemroller for oppsettet av brukertypene i standardversjonen. 

# Svaralternativgruppeoversikt
Alle svaralternativgrupper tilhører en svaralternativgruppeoversikt. Dette brukes kun til å skille svaralternativgrupper fra hverandre i endre svaralternativer og svaralternativgrupper. Vedlikeholdes i svaralternativgrupper. 