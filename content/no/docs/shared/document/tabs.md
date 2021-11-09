---
title: "Arkfaner"
linkTitle: "Arkfaner"
date: 2017-01-06
description: >
  Alle arkfaner for dokumenter.
---
# Revisjonsoversikt
{{< onlystaticimg src="/images/Page_code.png" >}} Revisjonsoversikt er en arkfane under endre data for dokumentet.

Viser tabell med alle revisjoner dokumentet har deltatt i. Trykk på en rad i tabellen for å åpne den aktuelle revisjonen.

#### Tabell

- Revisjonsnummer. Identifikator for revisjonen.
- Informasjon. Fritekstfelt med informasjon skrevet inn av den revsjonsansvarlige.
- Revisjonsansvarlig. Navn på bruker som er ansvarlig for gjennomføringen av revisjonen.
- Avdeling. Navn på avdelingen der revisjonen er opprettet på.
- Startdato. Tidspunkt revisjonen starter.
- Frist. Tidspunkt for frist for revisjonen.
- Avsluttet. Tidspunkt for når revisjonen ble avsluttet. Ellers blank.

# Versjonsoversikt
- {{< onlystaticimg src="/images/Folder_link.png" >}} Versjonsoversikt: Arkfane under endre data for dokumentet. Brukes til å gi en oversikt over alle versjoner av dokumentet.

### Tabell

Tabellen har en rad per Versjon (Hovedversjon) dokumentet har vært gjennom.

- Navn: Navn på dokumentet for denne versjonen.
- Versjon: Versjonsnummer.Endringsnummer. Lag ny versjon når det er gjort større endringer i dokumentet. Må endres manuelt. Endringsnummeret endres for hver lagrede endring i dokumentet.
  - Klikk {{< onlystaticimg src="/images/RightArrow.gif" >}} for å vise underversjonene.
  - Den versjonen som er publisert og vises under Info markeres med {{< onlystaticimg src="/images/Tick.png" >}}.
  - {{< onlystaticimg src="/images/Page_white_put.png" >}} Kopier og sett som siste versjon: Klikk på denne for å kopiere denne versjonen og sette den som en ny versjon. Kopierer alt innhold og dokumentdata, inkludert navnet. Viser bare for dokumenter av typen "Skriv et dokument".
- Adresse: Adressen til dokumentet. Trykk på denne for å åpne dokumentet i valgt versjon.
- Lagt inn av: Den som lagde denne versjonen.
- Opprettet: Tidspunktet den aktuelle versjonen ble opprettet.
- Sist endret av: Brukeren som sist endret dokumentet.
- Sist endret: Når ble siste endring utført.
- Sammenlign:

# Alternativer for dokumenter
Side for å velge opsjoner for eksport til pdf. Vises når man trykker på Vis som pdf - knappen fra et dokument ...

### Valg

- Inkluder underdokumenter. Forhåndsvalgt.
- Kun hoveddokumentet

### Knapper

- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Lag rapport: Lager rapporten med de valgte opsjoner. Vær oppmerksom på at du ikke må lukke denne siden før rapporten er ferdig, ellers vil du ikke få rapporten opp. Etter at rapporten åpner, kan du enten lage en ny rapport med andre opsjoner eller lukke denne siden.
- {{< onlystaticimg src="/images/Cross.png" >}} Lukk: Lukker Alternativer for dokumenter.
- {{< onlystaticimg src="/images/Help.png" >}} Hjelp: Åpner denne siden.

# Besvar høring
Besvar høring er en arkfane som vises under Table multiple.png Info når en høring skal besvares. Denne siden kan åpnes fra Innboks for de som skal utføre den og fra endre data for dokumentet under Admin/Dokumenter for brukere med tilgang dit.

Denne siden brukes til å besvare en høring. Brukere som gar fått ansvar for å delta i høringen kan besvare den og gi sine kommentarer. Høringens status kan endres av den som har fått tildelt ansvaret for å godkjenne den.

### Felter

- Dokument: Lenke som åpner selve dokumentet. Nummer og versjon for dokumentet høringen er tilknyttet.
- Ansvarlig for godkjenning av dokumentet: Den som skal godkjenne høringen og kan endre status på den.
- Status: Status. Kan ha verdiene Ute på høring, Til godkjenning og godkjent.
- Høringsnummer: Løpenummer for alle høringer i systemet.
- Opprettet: Opprettelsestidspunkt.
- Ansvarlig for høringen: Den som har opprettet høringen.
- Høringsfrist.
- Mitt svar til høringen: brukes av de som skal delta i høringen for å gi tilbakemelding på dokumentet.
- Høringens status: brukes av den som er ansvarlig for godkjenning til å endre status på høringen.
- Kommentar: Tekstfelt som kan brukes av alle med tilgang til høringen.
- Mitt svar: Meny for å velge hvem som skal motta beskjeden skrevet i fletet Kommentar.

### Knapper

- {{< onlystaticimg src="/images/Tick.png" >}} Lagre: Lagrer endringer du har gjordt i bildet. Dersom du har skrevet en kommentar blir den sendt på den måten du har valgt i Mitt svar.
- {{< onlystaticimg src="/images/Cross.png" >}} Lukk: Lukker dette bildet og tar deg tilbake dit du var.
- {{< onlystaticimg src="/images/Printer.png" >}} Skriv ut: Skriver ut det aktive skjermbildet.
- {{< onlystaticimg src="/images/Help.png" >}} Hjelp: Åpner denne siden.

### Tabeller

- Deltakere i høringen: Oversikt over de som skal besvare høringen, hva de har svart og når de sist endret svaret sitt.
- Kommentarer til høringen: Alle kommentarer laget til høringen.

# Dokumentgrupper
Arkfane under dokumenter

Her administreres virksomhetens dokumentgrupper.

Deaktiverte dokumentgrupper vises ikke i Info og kan ikke tilordnes dokumenter. Dokumenter tilhørende deaktiverte dokumentgrupper vises ikke under Info.

### Nedfallsmenyer

- Avdelingsvalg: Tabellen viser enten alle dokumentgrupper lagt inn i avdelingen som er valgt i navigatoren eller dokumentgrupper lagt inn i avdelinger fra og med avdelingen som er valgt i navigatoren.

### Knapper

- Ny dokumentgruppe: Åpner endre dokumentgruppe skjermbildet for å lage en ny dokumentgruppe.

### Ikoner

- {{< onlystaticimg src="/images/Folder.png" >}}: Åpner endre dokumentgruppe skjermbildet for å endre en eksisterende dokumentgruppe.
- {{< onlystaticimg src="/images/Turnarrow.gif" >}}: Deaktiverer eller aktiverer dokumentgruppen avhengig av om man man står i Aktive dokumentgrupper eller Deaktiverte dokumentgrupper.
