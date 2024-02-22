---
title: "Organisasjon"
linkTitle: "Organisasjon"
date: 2017-01-06
description: >
 Organisasjon er en arkfane under admin. 
---
Her administreres virksomhetens avdelinger. Aktive avdelinger vises i navigatoren og brukere i disse kan benytte systemet normalt. Deaktiverte avdelinger vises ikke i navigatoren, brukere i disse vil ikke kunne logge seg på systemet og ingen annen informasjon som er lagt inn i disse vil være synlige i rapporter og oversikter. Unntaket er meldinger og tiltak som er sendt videre til andre avdelinger. Besvarelser av aktiviteter med lister som er lagt opp på en avdeling over den deaktiverte avdelingen og deres kommentar meldinger vil også være tilgjenglig via rapportene på aktivitetsplan men det vil ikke være mulig å endre eller lage nye besvarelser i en deaktivert avdeling. 

### {{< onlystaticimg src="/images/Info.png" >}} Hva kan jeg gjøre her?

- ADMIN-arkfanen+ Organisasjon gir meg muligheter for å gjøre forandringer i organisasjon.
- Mitt valg i Navigatoren + et klikk på "Ny avdeling" nederst i bildet, gir underavdelinger i den avdelingen du valgte i navigatoren.
- Endre"-kolonnen til høyre i tabellene har i hovedsak to funksjoner: Sort pil deaktiverer, og ikoner som har gult i seg gir endringsmulighetene.


### {{< onlystaticimg src="/images/64px-Monitor.png" >}} Interaktiv opplæring

Her kan du lære:

- Opprette ny avdeling
- Flytte avdeling
- Deaktivere avdeling
- Aktivere avdeling

{{< onlystaticimg src="/images/Page_white_acrobat.png" >}} 
{{< assetlink src="/assets/03_admin_organisasjon.pdf" title="pdf" >}}

### Knapper

- {{< onlystaticimg src="/images/Chart_organisation_add.png" >}} Ny avdeling: Oppretter en ny avdeling og tar deg til endre avdeling skjermbildet.
- {{< onlystaticimg src="/images/Printer.png" >}} Skriv ut: Skriver ut det aktive skjermbildet.
- {{< onlystaticimg src="/images/Help.png" >}} Hjelp: Åpner denne siden.

### Ikoner

- {{< onlystaticimg src="/images/Folder.png" >}} Tar deg til endre avdeling skjermbildet for å endre den avdelingen som linjen det ble trykket på tilhører.
- {{< onlystaticimg src="/images/Turnarrow.gif" >}} Aktiverer/Deaktiverer - avhengig av valgt arkfane avdelingen som linjen det ble trykket på tilhører.
- {{< onlystaticimg src="/images/Chart_organisation_delete.png" >}} Sletter avdelingen som linjen det ble trykket på tilhører. Dette ikonet kommer kun opp dersom arkfanen deaktiverte avdelinger er valgt og avdelingen det gjelder ikke inneholder brukere, besvarte skjemaer eller skjemadefinisjoner.

### Arkfaner

- Aktiverte avdelinger: Viser de aktive underliggende avdelingene til den avdelingen som er valgt i navigatoren.
- Deaktiverte avdelinger: Viser de deaktiverte underliggende avdelingene til den avdelingen som er valgt i navigatoren.

### LDAP / AD Modul

Dersom virksomheten har aktivert modulen for LDAP / AD integrasjon og den påloggede brukeren har systemrollen LDAP integrasjonsansvarlig, vises muligheten i dette bildet for å gjøre LDAP / AD tilknyttninger mot de underliggende avdelingene.

- {{< onlystaticimg src="/images/Database_gear.png" >}} LDAP / AD: Åpner LDAP / AD grensesnittet for tilknyttninger for denne avdelingen.
- {{< onlystaticimg src="/images/Add.png" >}} Legg til LDAP / AD tilknyttning. Åpner muligheten for til å skrive inn data for en ny tilknyttning. Vises etter at Database gear.png ikonet er trykket på.
- {{< onlystaticimg src="/images/Tick.png" >}} Lagre: Lagrer ny eller endret LDAP / AD tilknyttning.
- {{< onlystaticimg src="/images/Delete.png" >}} Slette: Sletter valgt LDAP / AD tilknyttning.
