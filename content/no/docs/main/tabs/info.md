---
title: "Info"
linkTitle: "Info"
date: 2017-01-06
description: >
 Brukes for å se på dokumentoversikten i systemet.
---
Brukes for å se på dokumentoversikten i systemet. Dokumentene er organisert i ulike felter i skjermbildet. De kan også være delt på flere arkfaner. Organiseringen bestemmes av virksomhetens lokale superbruker. {{< onlystaticimg src="/images/Collapse.png" >}} og {{< onlystaticimg src="/images/Expand.png" >}} brukes til å brette ut og brette sammen dokumentets underdokumenter. Det er også en søkefunskjon her som gjør fritekstsøk i alle dokumenter som vises i denne siden.

Dokumentnavnene fungerer som lenker. Klikk på et dokumentnavn for å åpne dokumentet. Spesielt for dokumenter opprettet i Qm+: Du kan enten åpne HTML-versjonen ved å klikke på dokumentnavnet, eller du kan få en PDF-versjon av dokumentet ved å klikke på {{< onlystaticimg src="/images/Page_white_acrobat.png" >}}-ikonet til høyre for dokumentnavnet.

Når du klikker på {{< onlystaticimg src="/images/Page_white_acrobat.png" >}}-ikonet til høyre for dokumenter skrevet i Qm+ som har underdokumenter (de har {{< onlystaticimg src="/images/Expand.png" >}}-ikonet foran dem), får du opp et popup-vindu hvor du kan velge om du vil at den eksporterte .pdf skal inkludere kun gjeldende dokument eller også underdokumenter.

Mapper som inneholder dokumenter skrevet i Qm+ har også et pdf-ikon, som skriver ut alle slike dokumenter i den valgte mappen i én .pdf-fil. Pdf-rapporten fra en mappe inkluderer også alle underdokumenter til html-dokumenter i den trykte filen (ikke bare underdokumentene til mappen). Dette er ment å rette opp i problemet som oppstår når man har skrevet hvert kapittel av et stort dokument i et eget Qm+ html-dokument og ønsker å skrive ut hele dokumentet som en helhet.

Du kan også få dokumentet i .docx-format ved å klikke på {{< onlystaticimg src="/images/Page_white_word.png" >}}-ikonet. Alternativet for eksport til .docx er ikke inkludert i standardversjonen. Hvis du vil ha dette alternativet aktivert, kontakt drift@qmplus.com. Vær oppmerksom på at .pdf-versjonen er den mest egnede for utskrift. På dette tidspunktet kan vi ikke garantere at den .docx-produserte filen vil se lik ut i alle redaktører eller at den åpnes riktig i alle versjoner av Microsoft Office eller OpenOffice. Dette eksportformatet skal kun brukes når det er behov for å oppdatere rapporten manuelt. Denne funksjonaliteten er fortsatt i testmodus.

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
- Avansert: Se Lucene Query Syntax (https://www.lucenetutorial.com/lucene-query-syntax.html - kun engelsk) for detaljert informasjon om syntaks for søkefeltet.
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