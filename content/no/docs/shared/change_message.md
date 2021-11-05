---
title: "Endre melding"
linkTitle: "Endre melding"
date: 2017-01-06
description: >
 Arkfane under Innboks og Arkiv.
---
Et meldingsskjema har avkryssningsfelter eller nedfallsmenyer og tekstfelter spesifisert av virksomhetens superbruker. Minst et felt vil ha en oransjeaktig bakgrunnsfarge. Slike felt er obligatoriske og må fylles ut for at meldingen skal kunne lagres.

Når en melding lagres blir den registrert på den avdelingen som har navnet sitt i øverst i den midterste spalten i meldingsskjemaet. Meldingen vil øyeblikkelig dukke opp i Innboksbildet til den/de som er definert som leder på den valgte avdelingen med mindre tidlig saksbehandling er aktivert, se nedenfor. Meldingen vil også øyeblikkelig være med i Rapporter og rapporter laget fra samme eller en overliggende avdeling.

### Utfylling
- Husk å krysse av i alle felt med oransjeaktig bakgrunnsfarge. Det vil som regel ligge ett slikt felt øverst til venstre i bildet. Du vil få en feilmelding om du forsøker å lagre en melding uten at alle slike obligatoriske felter er fyllt ut. Merk at dersom flere felter er markert med Tag blue.png, så vil du kun få fyllt ut ett av dem.

- Avkryssningsfelt:
  - Enkeltvalg: Felt som har en rund boks foran hvert alternativ. Det betyr at du kan sette ett kryss i denne gruppen. Har du først satt ett kryss i et felt som er enkeltvalg, så kan du ikke ta det bort igjen.
  - Flervalg: Felt som har en firkantet boks foran hvert alternativ. Her kan du kryss av for alle eller ingen alternativer.

- Sett kryss og skriv tekst i de feltene du føler anngår deg. Det kan være at noen meldingsskjemaer er generelle og at kun noen felter er aktuelle i din situasjon.

- Husk at den som behandler din melding kan gjøre endringer, typisk komme ned supplerende informasjon og endre kostnadsfeltet og prioritet.

- Hvis det er et forslagsfelt, skriv ditt forslag der. Det er viktig for forbedringsprosessen i virksomheten. Enkelte virksomheter premierer månedens eller halvårets beste forbedringsforslag.

- Prioritet: Dette feltet får en verdi ut ifra de kryssene du har satt i meldingsskjemaet. Denne verdien kan overstyres.

- Kostnad: Dette feltet er tenkt å representere de eventuelle kostnadene hendelsen du registrerer har medført. Dette feltet får en verdi ut ifra de kryssene du har satt i meldingsskjemaet. Denne verdien kan overstyres. Superbruker kan fjerne kostnadsfeltet fra et meldingsskjema.

- Risikovurdering: Enkelte meldingsskjemaer kan ha en innebygd risikovurdering. I noen tilfeller skal man da vurdere sannsynlighet og konsekvens for om den registrerte hendelsen skjer i gjen, i andre tilfeller skal man vurdere sannsynlighet og konsekvens for en tenkt hendelse. Risikoverdien blir så automatisk regnet ut og vist med farge tilsvarende plasseringen i risikomatrisen.

- Tallfelt: Kategorier kan vises som tallfelt i stedet for avkryssningsbokser. Slike tallfelt kan brukes til å rapportere f.eks antall liter vannforbruk eller andre antall eller mengde anngivelser.

### Knapper
- {{< onlystaticimg src="/images/Tick.png" >}} Lagre / Send: Lagrer endringer du har gjordt.

- {{< onlystaticimg src="/images/Folder_table.png" >}} Behandle: Kun leder og saksbehandler. Lagrer endringer du har gjordt og tar deg til behandlingsbildet.

- {{< onlystaticimg src="/images/Page_copy.png" >}} Kopier: Kopierer denne meldingen og åpner kopien. Vises kun for risikomeldinger.

- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Vis som pdf: Åpner Alternativer for rapporter hvor du kan lage et pdfdokument for meldingen du er inne i. Denne er beregnet på utskrift til papir.

- {{< onlystaticimg src="/images/Cross.png" >}} Lukk: Sender deg tilbake til siden du kom fra.

- Endre meldingsskjema: Bare for brukere med systemrollen innholdsadministrator. Gir mulighet til å endre meldingsskjema av en melding. Det viser bare hvordan den gjeldende meldingen ville se ut om et annet skjema ble brukt. Meldingsskjemaet er faktisk ikke endret før brukeren trykker på Lagre-knappen. Anonymitet, avdeling, prioritet, tekstfeltene, kostnadsfeltene og de valgte kategoriene som finnes i begge meldingsskjemaer (det som ble brukt for den opprinnelige meldingen og det nye) er bevart.

- {{< onlystaticimg src="/images/Printer.png" >}} Skriv ut: Skriver ut det aktive skjermbildet.

- {{< onlystaticimg src="/images/Help.png" >}} Hjelp: Åpner denne siden.

### Nedfallsmenyer
- Versjonsoversikt: Kun for lagrede meldinger. Nyeste versjon er alltid valgt når meldingen åpnes. En hvilken som helst annen tidligere versjon kan velges. Da vil meldingen bli vist slik den så ut på det tidspunktet. Det kan kun gjøres endringer i nyeste versjon. Alle endringer av en melding fører til at det lages en ny versjon. Nye versjoner merkes med hvem som har gjordt endringen og når den ble utført.
-  Registrert på avdeling: Kun for brukere med systemrollen Innholdsadministrator. Brukes til å flytte registrerte meldinger.

### Tidlig saksbehandling
Dette feltet vises kun for meldinger som ikke er lagret og bare dersom det er aktivert for det meldingsskjemaet man ser på. Aktivering av tidlig saksbehandling anbefales ikke for nye kunder, med mindre de har helt spesielle behov.

Tidlig saksbehandling gjør at meldingen kan tilordnes en ansvarlig behandler allerede når den registreres. Normalt gjøres ikke dette av den som registrerer meldingen men først i behandling av en leder eller saksbehandler på den avdelingen der meldingen ble registrert. Tidlig saksbehandling kan aktiveres av virksomhetens superbruker under Regler i Admin ved å lage regler av typen "Tidlig saksbehandler". Det er også mulig å aktivere en opsjon som gjør at en meny tilsvarende den som vises for "Send til saksbehandler" i meldingsbehandlingsbildet vises i "Ny melding". Denne opsjonen gjør at man ikke trenger "Tidlig saksbehandler" regler, men de kan brukes selv om denne opsjonen er på og nedfallsmenyen i "Ny melding" vil da kun vise disse.

- Send til saksbehandler/linjeleder: Nedfallsmeny der man kan velge hvem som skal få denne meldingen tilsendt. Dette endrer ikke hvilken avdeling meldingen blir registrert på selv om den valgte brukeren befinner seg på en annen avdeling.

- Send e-post: Hvis det krysses av her, vil det gå en e-post til den brukeren som er valgt over når man trykker på Lagre.

- Frist: Dato / Tid. Dette tidspunktet vil komme opp som frist for den som får tilsendt meldingen.

### Arkfaner
Arkfanene her er kun aktive for lagrede meldinger. Endringer i bildet blir ikke lagret om du trykker på en arkfane.

- Endre melding: Laster meldingen på nytt. Bruk denne hvis du vil fjerne endringer du har utført som ikke er lagret.

- Dialog: For medarbeidere. Tar deg til dialogskjermbildet.

- Behandling: For ledere, saksbeahndlere og verneombud. Tar deg til behandlingsbildet.
