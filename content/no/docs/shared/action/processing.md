---
title: "Tiltaksbehandling"
linkTitle: "Tiltaksbehandling"
date: 2017-01-06
description: >
 Arkfane under Innboks og Arkiv. 
---
### Tiltaksdata

- Tiltaksnummer: Unikt nummer for hvert tiltak.
- Navn på tiltaket: Brukes til å identifisere tiltaket i tabeller og oversikter. Obligatorisk felt.
- Kostnadsramme: Hvor mye er satt av til gjennomføringen av tiltaket.
- Faktisk kostnad: Hvor mye ble brukt på gjennomføringen av tiltaket. Dette feltet blir brukt for å beregne kostnadsgrafen for tiltak under Rapporter.

### Beskrivelse av tiltaket

- Opprinnelig hendelse: Kopierers fra det første tekstfeltet i den opprinnelige meldingen.
- Jobbeskrivelse: Kopierers fra det andre tekstfeltet i den opprinnelige meldingen. Bør ofte endres til en konkret arbeidsoppgave for de som skal utføre tiltaket.
- Hvordan hindre gjentakelse: Kopierers fra et eventuelt tredje tekstfelt i den opprinnelige meldingen. Her kan man skrive litt om andre endringer enn selve det som skal utføres i dette tiltaket for at den opprinneligehendelsen ikke skal gjenta seg.
- Kommentar: Ekstra kommentar til tiltaket.

### Tiltakskategorier

Brukes for å kategorisere tiltaket.

### Status

Dette feltet forteller hvor tiltaket er i tiltaksprosessen. Det styrer en del av utseende til resten av dette skjermbildet.

- Under planlegging: Alle tiltak starter med denne statusen. I denne fasen skal tiltaket planlegges. Gi først tiltaket et navn slik at det blir lett å identifisere senere, fyll inn kostnadsrammen dersom dere bruker dette feltet. Tekstfeltene Korrigerende tiltak og Hvordan hindre gjentakelse må fylles ut slik at de som skal gjennomføre tiltaket skjønner hva de skal gjøre. Tiltakskategoriene kan også fylles ut nå. Siste punkt er å plukke ut de som skal utføre tiltaket og gi dem en frist. Dette gjøres i det obligatoriske Oversikt over ansvarlige feltet. Trykk så på "Lagre og send til gjennomføring" eller >> knappen i statusfeltet for å lagre tiltaket og skifte status til Under gjennomføring.
- Under gjennomføring: I denne fasen skal jobben som beskrives i tiltaket gjennomføres. Deretter skal det krysses av for utført av de som utført tiltaket. Det kan også skrives en kommentar i kommentarfeltet og den faktisk kostnaden kan fylles hvis den er tilgjengelig. Når alle avkryssninger er gjordt, brukes knappen "Send til godkjenning" eller >> knappen i statusfeltet. Dette lagrer tiltaket og endrer status til Under godkjenning.
- Under godkjenning: Her skal den som opprettte tiltaket kontrollere at alt er i orden før tiltaket godkjennes.
- Godkjent: Et godkjent tiltak er lukket og låst og kan ikke endres annet enn av brukere med systemrollen innholdsadministrator. Kommentarer til alle involverte brukere kan fortsatt sendes.

### Oversikt over ansvarlige

Viser oversikt over alle som har vært involvert i saken. Alle har et avkryssningsfelt ved siden av seg som brukes hvis man ønsker å sende en beskjed på e-post til noen av disse anngående denne saken. Alle beskjeder som blir sendt vil også vises nederst i dette skjermbildet.

- Opprinnelig melder: Brukerne som har opprettet meldinger tilkoblet dette tiltaket.
- Tiltaket ble opprettet av: Brukeren som opprettet tiltaket og dermed er ansvarlig for det. Må godkjenne tiltaket før det lukkes.
- Tiltaket ble utført av: De som skal utføre tiltaket.
- Tiltaket godkjennes av: Den som skal godkjenne tiltaket. I standardversjonen er det alltid samme bruker som opprettet tiltaket.

### Sakens historie

Viser en oversikt over hendelser for dette tiltaket

- Alle redigeringer av innhold eller status.
- Tilknyttning eller fjerning av meldinger.
- Alle epostkommentarer sendt ut tilknyttet dette tiltaket.

### Knapper

- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Vis som pdf: Åpner Alternativer for rapporter som gir mulighet til å lage en rapport i et pdfdokument av tiltaket du er inne i. Denne er beregnet på utskrift til papir.
- {{< onlystaticimg src="/images/Application_form_delete.png" >}} Slett tiltaket: Sletter tiltaket. Vises bare for brukeren som har opprettet tiltaket så lenge det fremdeles har status under planlegging, og for Innholdsadministrator. Slettede tiltak kan ikke gjenopprettes eller bli funnet igjen.
- {{< onlystaticimg src="/images/Tick.png" >}} Lagre tiltak: Lagrer de endringene du har gjordt. Husk at denne knappen aldri endrer status.
- {{< onlystaticimg src="/images/Tick.png" >}} Send: Vises når man ikke har tilgang til å gjøre endringer i tiltaket. Brukes for å sende epostkommentarer knyttet til tiltaket.
- {{< onlystaticimg src="/images/Cross.png" >}} Lukk: Returnerer deg dit du kom fra, med mindre du sto i en melding og laget et tiltak. Da vil du komme dit du åpnet denne meldingen fra.
- {{< onlystaticimg src="/images/Calendar_icon.png" >}} Kalender: Åpner kalenderen for datovalg.
- {{< onlystaticimg src="/images/Printer.png" >}} Skriv ut: Skriver ut den aktive siden.
- {{< onlystaticimg src="/images/Help.png" >}} Hjelp: Viser denne siden.
- {{< onlystaticimg src="/images/Application_form.png" >}} Tilknyttede meldinger: Viser de meldingene som er tilknyttet dette tiltaket. Mulighet til å koble til og koble fra fler og til å slette tiltaket for de brukerne som har rettighetene til det.

### Arkfaner

- Tiltaksbehandling: Laster denne siden på nytt igjen. Alle endringer du har gjordt uten å trykke lagre blir borte.
