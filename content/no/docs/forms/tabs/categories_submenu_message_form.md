---
title: "Kategorier undermeny meldingsskjema"
linkTitle: "Kategorier undermeny meldingsskjema"
date: 2017-01-06
description: >
 Kategorier undermeny meldingsskjema er en arkfane under endre meldingsskjema. 
---
Denne siden brukes for å administrere kategoriene i meldingsskjemaet. 

### Legg kategorier til meldingsskjemaet

Felt for å administrere kategoriene i meldingsskjemaet.

Det venstre feltet viser kategorier i meldingsskjemaet, det høyre kategorier som kan legges til. Feltene filtreres på kategorigruppen valgt i kategorigruppenedfallsmenyen over det venstre feltet.

Dersom kategoriene i det venstre feltet er markert med gult, vil de vises i meldingsskjemaet når det åpnes på avdelingen kategorien ble lagt til på eller på en av denne avdelingens underavdelinger. Kategorier i hvit blir kun vist når man åpner meldingsskjemaet på den samme avdelingen som kategorien ble lagt til på. Dette bestemmes av om avkryssingsfeltet "Vis for underavdelinger" er krysset av eller ikke når man legger en kategori til meldingsskjemaet.

### Nedfallsmenyer

Punktene merket med (Avansert mulighet) vises bare når knappen "Vis avanserte muligheter" i Endre meldingsskjema siden har blitt trykket på.

- Velg kategorigruppe: Feltene under denne nedfallsmenyen vil kun inneholde kategorier tilhørende den valgte kategorigruppen. Kategorigruppene i denne nedfallsmenyen er gruppert etter kategorigruppetype.
- Sorteringstype (Avansert mulighet): Vises over kategorigruppenedfallsmenyen ved feltet Legg kategorier til meldingsskjemaet.
  - Sortering etter type er standard og betyr at kategorigruppene blir sortert etter sin kategorigruppetype.
  - Sortering etter indeks betyr at man kan tilordne en kolonne - venstre, senter eller høyre og en indeks til hver kategorigruppe i meldingsskjemaet. Dersom sortering etter indeks bør man gå gjennom alle kategorigruppene og sette kolonne og indeks. Lagreknappen må benyttes mellom hver endring for at den skal tre ikraft.

Merk at en kategorigruppe må ha minst en av sine kategorier tilknyttet meldingsskjemaet for at de følgende opsjonene skal ha noen effekt.

- Vis som: Avgjør hvordan den valgte kategorigruppen blir vist i meldingsskjemaet (Avkryssningsboks/Nedfallsmeny).
- Visning i meldingsskjemaet (Avansert mulighet): Avgjør om og hvordan den gitte kategorigruppen blir vist i meldingsskjemaet.
- Visning i meldingsbehandlingssiden (Avansert mulighet): Avgjør om og hvordan den gitte kategorigruppen blir vist i meldingsbehandlings siden.
- Visning i tiltaksbehandlingssiden (Avansert mulighet): Avgjør om og hvordan den gitte kategorigruppen blir vist i tiltaksbehandlings siden.
- Visning i Innboks (Avansert mulighet): Hvis satt til ja, så vil det i innboks bli vist en ekstra kolonne der avkryssede kategorier i meldinger tilhørende denne kategorigruppen listes opp.
- Visning i mobilapplikasjonen (Avansert mulighet): Hvis nei, vil denne kategorigruppen ikke vises i meldingsskjemaet når det vises i mobilapplikasjonen. Dette feltet vises bare om mobilapplikasjonen er aktivert.
- Obligatorisk: Hvis ja, må det krysses av i denne gruppen for at en melding med dette meldingsskjemaet skal kunne lagres. Definerende kategorigrupper er et spesialtilfelle og vil alltid ha ja her. Merk at om et meldingsskjema har mer enn en definerende kategorigruppe, så gjelder obligatorisk kravet slik at kun en av de definerende kategorigruppene må være krysset av.

### Knapper

- {{< onlystaticimg src="/images/Note_add.png" >}} Ny kategori: Åpner ny kategori skjermbildet med Kategoritype satt til samme kategorigruppe som den som er valgt i nedfallsmenyen.
- {{< onlystaticimg src="/images/Note_add.png" >}} << Legg til: Legger de valgte kategoriene i høyre felt til dette meldingsskjemaet.
- {{< onlystaticimg src="/images/Note_delete.png" >}} Fjern >>: Fjerner de valgte kategoriene i venstre felt fra dette meldingsskjemaet.
- {{< onlystaticimg src="/images/Note_go.png" >}}: Endre kategoriavhengighet for den aktuelle kategorien. Åpner Endre kategoriavhengighet.

### Kategorier i dette meldingsskjemaet

Viser en tabell for hver kategorigruppe med kategorier tilknyttet meldingsskjemaet. Tabellene viser navnet på kategorien og hvilken avdeling den er tilknyttet fra. For å slette en kategori fra et meldingsskjema, så må man ha valgt samme avdeling i navigatoren som kategorien er lagt inn fra. 
