---
title: "Definisjoner"
linkTitle: "Definisjoner"
date: 2017-01-06
description: >
  Oversikt over definisjoner.
---
### Arkfane
Navigasjonsstrukturen i Qm+ er bygd opp av arkfaner.

De har et navn som beskriver det stedet i systemet man kommer til hvis man trykker på den. De fleste har også en beskrivende tekst som kommer opp når man holder musepekeren i ro over den.

Arkfanene beskriver også hvor i systemet man er. De arkfanene som er mørkere enn de andre er valgt.

Eksempel :

{{< onlystaticimg src="/images/Arkfanebeskrivelse.png" >}}

Her står vi i Arkiv / Meldinger/UH / Nye saker.

### Sak
En sak i Qm+ er enten en melding, et tiltak, en høring eller en revisjon. 

### Risikomelding
Risikomeldinger er meldinger som brukes for å lage en risikooversikt for virksomheten. Det er opp til virksomheten om risikomeldingene skal behandles eller om de kun skal registreres og lagres i arkivet. Vår anbefaling er at de ikke behandles, kun oppdateres årlig. Risikomeldinger kan bare lukkes av QmPlus AS (som et unntak), siden de normalt ikke skal behandles. Meldinger registrert her dukker ikke opp i Innboks med mindre man bruker behandling for å aktivere dem. Meldingstypen risikomelding er ikke aktivert i standardversjonen. 

### Sjekkliste
En sjekkliste er en liste som blir vist med avkryssningsfelt forran spørsmålet. For å kunne redigere svaralternativer må listetypen spørreskjema benyttes. En sjekkliste er tenkt brukt som en "finn feilen liste". Dvs list opp en rekke vanlige feil innenfor det området som skal undersøkes. Brukerne krysser så av for punktet i listen dersom de kjenner til feilen. Se liste for forklaring på datafeltene. 

### Standard saksbehandler
Hvis et meldingsskjema har satt en standard saksbehandler vil meldinger registrert med dette meldingsskjemaet dukke opp i Saker jeg er ansvarlig for siden til standard saksbehandleren i stedenfor til lederen på avdelingen der meldingen ble registrert. Meldingen vil fremdeles være registrert på avdelingen den ble registrert og vises der i rapporter og søk.

Dersom samme meldingsskjema er satt opp med flere standard saksbehandlere med overlappende avdelinger vil melderen kunne velge mellom disse i en nedfallsmeny når meldingen registreres. I registreringsbildet er det også et avkryssningsfelt for om det skal sendes epost til den valgte saksbehandleren når meldingen registreres. 

### Superbruker
Superbrukeren er en bruker som har bestått superbrukerkurset for Qm+. Superbrukeren har virksomhetens høyeste tilgang til Qm+. Dette betyr tilgang som brukertypen leder uten begrensende roller og ofte noen ekstra systemroller.

Superbrukeren skal bistå de andre brukerne i virksomheten og fungere som lokal brukerstøtte for Qm+.

Alle superbrukere har rett på gratis telefonsupport fra Qm+ og kan benytte seg av denne dersom han mottar spørsmål fra sin virksomhets brukere han trenger hjelp til å besvare. En eller fler av virksomhetens superbrukere fungerer som regel også som kontaktperson for virksomheten mot QmPlus AS.

Alle ønsker om endret funksjonalitet i systemet må formidles via kundens kontaktperson slik at vi vet at ønsket har støtte i hele virksomheten. 

### Svaralternativgruppe
En samling med svaralternativ som kan kobles til spørsmål i et spørreskjema. Vedlikeholdes i svaralternativgrupper.

En svaralternativgruppen sorterer under en bestemt svaralternativgruppeoversikt. Dette brukes kun til å skille svaralternativgrupper fra hverandre i endre svaralternativer og svaralternativgrupper. 

### Svartype
Hvert spørsmål i en liste kan ha en svartype.

**Svartypene:**
- Enkeltvalg: En avkryssningen til hvert spørsmål. Er det først krysset av for et spørsmål må spørsmålet besvares. Dette er standardvalget som blir brukt dersom det ikke foretas en endring.
- Flervalg: Ingen til alle svaralternativene til hvert spørsmål kan krysses av.
- Tekst: Det blir ikke vist noen avkryssningsboks for dette spørsmålet, kun kommentarfelt. Fungerer ikke for listeversjon.
- Fritekst tall: Et tall kan skrives inn som svar på dette spørsmålet. Grafen vil vise summen av alle tallene skrevet inn til et slikt spørsmål.

Tips: Bruk svartype Flervalg for spørsmål med kun ett svaralternativ, slik som i en sjekkliste. Ellers vil det ikke være mulig å ta vekk avkryssingen om man skulle ombestemme seg. 

### Søkekriterie
Søkekriterie er det som er søkt etter når man gjør et søk.

Vises som en tabell over søkeresultatet etter et utført søk. Søk kan startes fra Rapporter, Søk meldinger, Søk tiltak eller ved å trykke på risikomatrisen i Risiko. Alle søkeresultater vises i tabellform i Arkiv eller som grafer under Rapporter under sin tilhørende Arkfane.

- Alle data vist i nedfallsmenyer kan endres. Slike endringer medfører at søket oppdaterer seg.
- Data etterfulgt av {{< onlystaticimg src="/images/Delete.png" >}} kan fjernes fra søkekriteriene. Det medfører at søket oppdaterer seg.

### Tiltaksprosessen
Tiltaksprosessen er prosessen fra et tiltak opprettes til det blir godkjent og lukket.

Følges opp gjennom tiltaksbehandling.

- Under planlegging: Alle tiltak starter med denne statusen. I denne fasen skal tiltaket planlegges. Gi først tiltaket et navn slik at det blir lett å identifisere senere, og fyll inn kostnadsrammen dersom dere bruker dette feltet. Tekstfeltene Korrigerende tiltak og Hvordan hindre gjentakelse må fylles ut slik at de som skal gjennomføre tiltaket skjønner hva de skal gjøre. Tiltakskategoriene kan også fylles ut nå. Siste punkt er å plukke ut de som skal utføre tiltaket og gi dem en frist. Dette gjøres i det obligatoriske Oversikt over ansvarlige feltet. Trykk så på Send til gjennomføring >> eller >> knappen i statusfeltet for å lagre tiltaket og skifte status til Under gjennomføring.
- Under gjennomføring: I denne fasen skal jobben som beskrives i tiltaket gjennomføres. Deretter skal det krysses av for utført av de som utført tiltaket. Det kan også skrives en kommentar i kommentarfeltet og den faktisk kostnaden kan fylles hvis den er tilgjengelig. Når alle avkryssninger er gjordt, brukes knappen Send til godkjenning eller >> knappen i statusfeltet. Dette lagrer tiltaket og endrer status til Under godkjenning.
- Under godkjenning: Her skal den som opprette tiltaket kontrollere at alt er i orden før tiltaket godkjennes.
- Godkjent: Et godkjent tiltak er lukket og låst og kan ikke endres annet enn av brukere med systemrollen innholdsadministrator. Kommentarer til alle involverte brukere kan fortsatt sendes.

### Visningsform
Styrer hvordan listen blir vist.

Mulige visningsformer: Papirversjon, listeversjon (eller listeform), Vis som enkeltspørsmål. 
