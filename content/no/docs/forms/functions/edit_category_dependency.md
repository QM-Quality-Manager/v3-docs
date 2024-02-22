---
title: "Endre kategoriavhengighet"
linkTitle: "Endre kategoriavhengighet"
date: 2017-01-06
description: >
 Endre kategoriavhengighet er en funksjon for å vedlikeholde kategoriavhengigheter. Startes fra Endre meldingsskjema / Kategorier. 
---
Sidens overskrift forteller hvilken kategori man redigerer kategoriavhengigheter for og hvilken kategorigruppe den tilhører. En kategoriavhengighet gjelder kun for det aktuelle meldingsskjemaet den legges opp for. En kategori kan kun ha en avhengighet mot hver av de andre kategoriene i det aktuelle meldingsskjemaet.

En kategori oppfyller sine avhengigheter når den både:

- Oppfyller alle "Og" avhengigheter. Har den ingen "Og" avhengighet er alle oppfyllt.
- Oppfyller minst en "Eller" avhengighet eller ikke har noen "Eller" avhengighet.

Merk at når man lukker denne siden må man laste {{< onlystaticimg src="/images/Note.png" >}} Kategorier eller Endre meldingsskjema på nytt for at endringen skal være synlig i kategoritabellen. Dette gjør man enklest ved å trykke på {{< onlystaticimg src="/images/Note.png" >}} Kategorier arkfanen over kategoritabellen.

### Felter

- Eksisterende kategoriavhengigheter viser de avhengighetene den valgte kategorien allerede har. Her kan man:
  - Endre type avhengighet mellom "Og" og "Eller".
  - Slette en avhengighet.
    
- Ny kategoriavhengighet. Her kan man legge til en ny avhengighet.
  - Velg kategorigruppe den kategorien man skal lage en avhengighet mot tilhører i nedfallsmeny 1.
  - Velg så kategori fra nedfallsmeny 2. Merk at innholdet her avhenger av hva du valgte i nedfallsmeny 1.
  - Velg så type avhengighet. "Og" er standard.

### Knapper

- {{< onlystaticimg src="/images/Delete.png" >}}: Sletter aktuell avhengighet.
    
- {{< onlystaticimg src="/images/Tick.png" >}} Lagre: Lagrer endringene gjordt i bildet. Dersom feltene i Ny kategoriavhengighet delen er satt, lages det en ny avhengighet.
    
- {{< onlystaticimg src="/images/Tick.png" >}} Lagre for gruppen: Lagrer endringene gjordt i bildet. Dersom feltene i Ny kategoriavhengighet delen er satt, lages det en ny avhengighet som legges til alle kategorier i den kategorigruppen som er navngitt i sidens overskrift.
    
- {{< onlystaticimg src="/images/Cross.png" >}} Lukk: Tar deg tilbake til siden du kom fra.
