---
title: "Info"
linkTitle: "Info"
date: 2017-01-06
description: >
 Brukes for å se på dokumentoversikten i systemet.
---
Brukes for å se på dokumentoversikten i systemet. Dokumentene er organisert i ulike felter i skjermbildet. De kan også være delt på flere arkfaner. Organiseringen bestemmes av virksomhetens lokale superbruker. Collapse.png og Expand.png brukes til å brette ut og brette sammen dokumentets underdokumenter. Det er også en søkefunskjon her som gjør fritekstsøk i alle dokumenter som vises i denne siden.

Det kan bestilles at dokumenter vises direkte i siden under enkelte arkfaner i steden for at navnet på dokumentet vises som en link. Ta kontakt med drift@qmplus.com om dere ønsker en slik løsning.

### {{< onlystaticimg src="/images/Info.png" >}} Hva kan jeg gjøre her?
* Jeg kan søke etter dokumenter: Klikk **"Søk"**-knappen nederst i bildet.
* Jeg kan velge mellom Arkfaner og Dokumentgrupper for å se i spesielle dokumentsamlinger.
* Alle dokumenter i INFO kan lenkes til fra ulike skjemaer og kategorier i for eksempel meldingsskjemaer.

### Funksjoner

{{< onlystaticimg src="/images/Printer.png" >}} Skriv ut: Skriver ut det aktive skjermbildet.

{{< onlystaticimg src="/images/Help.png" >}} Hjelp: Åpner denne siden.

{{< onlystaticimg src="/images/Find.png" >}} Søk: Søker etter teksten som er skrevet inn i tekstfeltet foran knappen. Søkeresultatet avhenger av valgt avdeling i [navigatoren]({{< ref "/docs/other/navigator" >}} "navigatoren"), men ikke hvilken arkfane som er valgt. Søkefunksjonen bruker søkemotoren [Lucene](http://lucene.apache.org/core/).

- Plasseringen til dokumentet vises under tittelen på hvert dokument i søkeresultatet. Den blir vist som Dokument arkfane / Dokument gruppe / Eventuelle overliggende dokument(er) / Dokument tittel.
- Når man har utført et fritekstsøk, vil det over listen over søkeresultater vises tre nedfallsmenyer som kan brukes til å filtrere søkeresultatet. Verdiene i filteret holder seg om man skifter avdeling i navigatoren, men nullstilles til neste søk når man trykker Lukk søkeresultatene.
  - Dokumentarkfane: Ta med resultater fra alle eller fra en valgt dokumentarkfane.
  - Dokumentgruppe: Ta med resultater fra alle eller fra en valgt dokumentgruppe.
  - Avdelingsvalg: Velg mellom Alle tilgjenglige dokumenter som vises for avdelingen valgt i navigatoren eller Kun dokumenter registrert på valgt avdeling.
- Tips
  - Ta bare med interessante ord. Dvs skal du søke etter prosedyrer knyttet til brann, bruk: prosedyrer brann.
  - Om du vil ha treff på deler av ord, bruk * for å få med alle ord som starter med ordet ditt. Eksempel : søk på redning gir ikke treff på redningsvest, men det gjør redning* .
- Avansert: Se Lucene Query Syntax (kun engelsk) for detaljert informasjon om syntaks for søkefeltet.
  - Søkbare felt: Text, URL, DocumentId, Name, Information.
  - Dersom man ikke oppgir felt, søkes det i alle felt. Navnefeltet gis da ekstra vekt.

{{< onlystaticimg src="/images/Heart_add.png" >}} Legg til i favoritter: Denne funksjonen er tilgjengelig for brukere som har systemrollen Info_Favorittdokumenter, og for alle dokumenter bortsett fra de av typen Mappe. Ikonet vises når brukeren holder markøren over dokumentnavnet. Ved å klikke på ikonet, markeres dokumentet som et favorittdokument. Disse dokumentene kan senere finnes i fanen Favorittdokumenter.

{{< onlystaticimg src="/images/Heart_delete.png" >}} Ta vekk fra favoritter: Denne funksjonen er tilgjengelig for brukere som har systemrollen Info_Favorittdokumenter. Alle dokumenter som er lagt til som et favorittdokument, kan fjernes som favoritt. Ikonet vises når brukeren holder markøren over et dokument som er merket som en favoritt før. Ved å klikke på ikonet, fjernes dokumentet som et favorittdokument fra fanen Favorittdokumenter.

#### Ikoner
Ikoner brukt til å symbolisere ulike dokumenttyper

{{< onlystaticimg src="/images/Page_white_world.png" >}} Link til dokument på nettet

{{< onlystaticimg src="/images/Lovdata_icon.png" >}} Link til side hos Lovdata

{{< onlystaticimg src="/images/Page_white_word.png" >}} Worddokument

{{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Pdfdokument

{{< onlystaticimg src="/images/Page_white_excel.png" >}} Exceldokument

{{< onlystaticimg src="/images/Page_white_powerpoint.png" >}} Powerpointdokument

{{< onlystaticimg src="/images/Page_white_text.png" >}} Dokument laget i Qm+

{{< onlystaticimg src="/images/Shape_align_center.png" >}} Dokument av type prosesskart, laget i Qm+

{{< onlystaticimg src="/images/Image.png" >}} Bilde

{{< onlystaticimg src="/images/Page_white.png" >}} Ukjent eller tomt dokument

{{< onlystaticimg src="/images/Folder_page_white.png" >}} Mappe. Kan ikke åpnes, brukes kun for å lage en dokumentstruktur.

#### Arkfaner
Brukes til å sortere dokumenter. Bestemmes av superbrukeren. I standarversjonen er det

- Styrende dokumenter
- Mål
- Favorittdokumenter

### Mål
Mål er en arkfane under {{< onlystaticimg src="/images/Info_16px.png" >}} Info

Brukes i standardversjonen til å vise en tekstlig beskrivelse av virksomhetens mål. Det er et felt for Mål for kvalitetsstyrings-arbeidet og et for Mål for HMS-arbeidet. Brukere med brukertypen Leder som er registrert på øverste avdeling har en lagre knapp som gjør at de kan endre innholdet i disse feltene.

Mål er ikke flerspråklig og er lik for alle avdelinger. Dersom slik funksjonalitet ønskes, benytt de vanlige mekanismene for dokumenter se Info. Arkfanen Mål er tenkt fjernet på sikt. 
