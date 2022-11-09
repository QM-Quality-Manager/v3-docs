---
title: "Systeminnstillinger"
linkTitle: "Systeminnstillinger"
date: 2017-01-06
description: >
  Systeminnstillinger er justerbare elementer som brukes til å gjøre individuelle tilpassninger per kunde. Endringer fra standardversjonen bestilles av kundens kontaktperson mot QmPlus AS. 
---
REPORT

- LISTLENGTH: How many lines are shown in the four most common / most expensive tables.
  - - 1 gives all. -1 turns off the four parts of the heading (four most common / most expensive).

> Standardverdi 4

- LISTCOST
  - 0 - The listCost field is not shown in the table.
  - 1 - Shows the listCost.

> Standardverdi 1

- LISTAMOUNT
  - 0 - The listAmount field is not shown in the table. // ORDER BY Data_Element_4 DESC
  - 1 - Shows the listAmount. // ORDER BY Data_Element_2 DESC
  - -1 - The listAmount field is not shown // ORDER BY TEXTTAG ASC

> Standardverdi 1

- GRAPHAMOUNT
  - 0 - Viser ikke amount grafen.
  - 1 - Viser amount grafen.

> Standardverdi 1.

- GRAPHCOST
  - 0 - Viser ikke cost grafen.
  - 1 - Viser cost grafen.

> Standardverdi 1.

- GRAPHORDER
  - 0 - ALPHABETICAL
  - 1 - OCCURENCES
  - 2 - COST

> Standardverdi 0.

- TABLEORDER
  - 0 - OCCURENCES
  - 1 - COST

> Standardverdi 0.

- SORTTYPE
  - 0 - ASCENDING
  - 1 - DESCENDING

> Standardverdi 1.

- PAPERVERSION
  - 0 - Viser ikke papirversjonsknappen
  - 1 - Viser den.

> Standardverdi 0.

- EMPLOYEEGRAPH
  - 0 - Viser ikke employeegrafen
  - 1 - Viser den

> Standardverdi 0.

- SHOWDATESELECT
  - 0 - Viser ikke nedfallsmenyen for tidsperioder
  - 1 - Viser nedfallsmenyen for tidsperioder

> Standardverdi 1.

- DISPLAYCATEGORYCHART
  - 0 - Kategorigrafen starter skjult
  - 1 - Kategorigrafen starter synlig

> Standardverdi 0

- DISPLAYTOTALCHART
  - 0 - Totalgrafen starter skjult (Oversikt etter Avdelinger checkbox unselected)
  - 1 - Totalgrafen starter synlig (Oversikt etter Avdelinger checkbox unselected)

> Standardverdi 0

- DISPLAYSTATUSCHART
  - 0 - Statusgrafen starter skjult
  - 1 - Statusgrafen starter synlig

> Standardverdi 1

- DISPLAYFORMCHART
  - 0 - Skjemagrafen starter skjult
  - 1 - Skjemagrafen starter synlig

> Standardverdi 1

- DISPLAYPRIORITYCHART
  - 0 - Priorietsgrafen chart starter skjult
  - 1 - Prioritetsgrafen starter synlig

> Standardverdi 1

- DISPLAYUSERCHART
  - 0 - Brukergrafen starter skjult
  - 1 - Brukergrafen starter synlig

> Standardverdi 0

- DISPLAYTRENDCHART
  - 0 - Fordeling over tid grafen starter skjult
  - 1 - Fordeling over tid grafen starter synlig

> Standardverdi 0

- REPORT_INCLUDE_BLANK_DEPARTMENTS
  - 0 - Avdelinger uten meldinger vises ikke i Oversikt etter avdelinger
  - 1 - Avdelinger uten meldinger vises i Oversikt etter avdelinger

> Standardverdi 0


- SHOWFORMSELECT Om grafer etter skjema skal vises eller ikke i grafsiden.
  - 0 - Av
  - 1 - På

> Standardverdi 1

- SHOWPRDEPCAT (Ikke i bruk)

> Standardverdi 1

FAULTCASEPROCESS

  - SENDEMAIL (NOT IN USE, replaced by ACTIONCASEPROCESS_SENDEMAIL)
    - 0 - Send epost til saksbehandler ved send avvik til saksbehandler er Standardverdi ikke avvkrysset.
    - 1 - Send epost til saksbehandler ved send avvik til saksbehandler er Standardverdi avvkrysset.

> Standardverdi 1.

- USERSENDEMAIL (Ikke i bruk)
  - 0 - Epost til feilmelderfeltet ikke avkrysset
  - 1 - Epost til feilmelderfeltet avkrysset

> Standardverdi 0.

- CASEPROCESSSENDEMAIL
  - 0 - E-post til saksbehandlderfeltet ikke avkrysset
  - 1 - E-post til saksbehandlderfeltet avkrysset

> Standardverdi 1.
 
- SETDEFAULOWNER
  - 0 - Owner må settes manuelt når et tiltak lages
  - 1 - Owner settes lik den aktive brukeren når et tiltak lages

> Standardverdi 1.

- ACTIONTAB
  - 0 - Tilknytt tiltakarkfanen vises ikke
  - 1 - Tilknytt tiltakarkfanen vises

> Standardverdi 0.

- EXPANDEDFIXEDDIRECTLY : Registrer navn på og beskrivelse av tiltaket ved rettet straks. Parameteren kun påvirker Avslutt saken.
  - 0 - Av
  - 1 - På

> Standardverdi 1.

- USENROFTEXTFIELDS : Når tiltak lages fra meldingsskjemaer med mer enn 2 tekstfelter, styres tekstfeltene til tiltaket. standard
  - 0 - Tekstfelt 1 i meldingen -> felt 1 i tiltaket.
  - 2 - Alle tesktfelt i meldingen -> felt 1 i tiltaket
  - 3 - Tekstfelt 1 i meldingen -> felt 1 i tiltaket. Resten av tekstfeltene i meldingen -> forhindre gjentakelse feltet i tiltaket.

> Standardverdi 0.

- COMMENTTEXTFIELDS : Når tiltak lages fra meldingsskjemaer tas alle tekstfelter fra og med tekstfeltet med nummer gitt her og legges til i kommentarfeltet i tiltaket automatisk. Både navnet på feltet og innholdet i feltet blir tatt med. Spesialbestilt av Tess.
  - 0 - Av
  - X - Nummer. Ta med tekstfelt fra og med dette nummer.

> Standardverdi 0.

- CASEDOCUMENTS : Vedlegg til meldinger
  - 0 - Av
  - 1 - På

> Standardverdi 1.

- SHOWCOMPLETEMESSAGE : Når man åpner meldingsbehandling blir alle kategoriene vist.
  - 0 - Av
  - 1 - På

> Standardverdi 0.

- FAULTCASEPROCESS_USERFEEDBACK_DEFAULT_ON_CLOSE : Send en beskjed om saken starter avkrysset som standard for alle handlinger som lukker saken
  - 0 - Av
  - 1 - På

> Standardverdi 0.

- INFOSENDEMPTYEMAIL (Ikke i bruk)

- INFOTOPUSERDEP : Brukes for å sette hvilken avdeling som brukes som utgansgpunkt for å hente brukerne for "Alle" valget i "Informer flere"
  - 0 - "Alle" valget er ikke tilgjengelig
  - -1 - "Alle" valget er tilgjengelig, men bruker avdelingen spesifisert i SPAN som utgangspunkt
    - Span: Hvis INFOTOPUSERDEP = -1, brukes span til å justere øverste avdeling
    - 0 - Bruk avdelingen over innlogget avdeling (standardverdi)
    - X - Kun avdelinger under dette avdelingsnummeret kan brukes
  - Alle andre verdier, "Alle" valget tilgjengelig. Bruk verdien som avdelingsnummer, f.eks 1 for at alle skal kunne velge alle.

Standardverdi null (Bruk øverste tilgjenglige avdeling for den aktive brukeren).


- INFOROLESETUP : Justerer øverste avdeling å hente brukere fra for rollevalgene i Informer flere
  - 0 - Bruk øverste avdeling 1
  - 1 - Bruk brukerens innloggede avdeling
  - 2 - Bruk valgt avdeling
  - -1 - Bruk avdelingen over innlogget avdeling

> Standardverdi 0.

- NOACTIONNAME : Om navnet på tiltaket skal starte tomt eller ikke.
  - 0 - Navnet på tiltaket blir satt opp med de første 20 bokstavene fra første tekstfelt i meldingen
  - 1 - Starter blankt.

> Standardverdi 1.

- NOACTIONDESCRIPTION : Om første tekstfelt i tiltaket skal starte tomt eller ikke.
  - 0 - Tekstfeltet blir satt opp som kopi av første tekstfelt i meldingen
  - 1 - Starter blankt.

> Standardverdi 1.

- NOPREVENTIONDESCRIPTION : Om andre tekstfelt i tiltaket skal starte tomt eller ikke.
  - 0 - Tekstfeltet blir satt opp som kopi av første tekstfelt i meldingen
  - 1 - Starter blankt.

> Standardverdi 1.

- STANDARDACTIONTYPE : (Ikke i bruk)

- DEFAULTACTIONOWNER  : (Ikke i bruk)

- SHOWALLCATEGORIESINEMAILS : Alle kategorier i meldingen inkluderes i eposter om saken, ikke kun definerende.
  - 0 - Av
  - 1 - På

> Standardverdi 0.

ACTIONCASEPROCESS

  - SENDEMAIL
    - 0 - Send epost til ansvarlig for utførelse ved tiltakstildeling er Standardverdi ikke avkrysset.
    - 1 - Send epost til ansvarlig for utførelse ved tiltakstildeling er Standardverdi avkrysset.

> Standardverdi 1.

  - STRICTAPPROVAL
    - 0 - Alle ledere kan godkjenne et tiltak
    - 1 - Kun den lederen som står som ansvarlig for å godkjenne tiltaket kan godkjenne det.

> Standardverdi 1.

  - ACTIONTOPUSERDEP Brukes for å sette hvilken avdeling som brukes som utgangspunkt for å hente brukerne man kan tilordne til tiltak
    - -1 - Bruk avdelingen over den øverste tilgjengelige avdeling for den aktive brukeren
    - 0 - Bruk øverste tilgjengelige avdeling for den aktive brukeren, activeDepNr
    - andre - Bruk verdien som avdelingsnummer, f.eks 1 for at alle skal kunne velge alle.

 > Standardverdi 0

  - ACTIONTEXTTAG Brukes for å bestemme hva som står over tiltaksbeskrivelsesfeltet.
    - 1 Jobbeskrivelse
    - 2 Korrigerende tiltak
    - 3 Tiltaksbeskrivelse / Vurdering av effekten av tiltaket

> Standardverdi 1.

  - COST

 > Standardverdi 0

  - TIME

> Standardverdi 0

  - START_DATE_FIELD

> Standardverdi 0

  - CHANGEMESSAGEDUEDATE Endre frist for melding for å matche tiltaksfristen, hvis frist for melding er tidligere.
    - 0 - Frist for melding er uavhengig av frist for tiltak
    - 1 - Frist for melding oppdateres automatisk for å matche tiltaksfristen hvis forfallsdato for tiltaket er etter forfallsdatoen for meldingen

 > Standardverdi 0

LOGON

  - TOPSELECTABLELOGONDEPNR
    - -1 - Bruk PRESETLOGONDEPNR.
    - Ellers - Øverste avdelingsnummer i avdelingstreet det er lov til å logge seg på anonymt eller opprette bruker på. Har bare effekt dersom slik pålogging er tillat fra innstillinger i control databasen.

> Standardverdi 1.

  - PRESETLOGONDEPNR : Dersom anonym pålogging eller egengenerering av brukere er tillat, og man ikke ønsker at brukerne selv skal velge avdeling, setter man avdelingsnummeret her.

> Standardverdi 1

  - DIRECTLOGONHEADER : Hva skal stå i overskriften på directlogon siden ved siden av velg.
    - 0 - Sted
    - 1 - Avdeling
    - 2 - Organisasjon

> Standardverdi 1

  - LOGONHEADER : Hva skal stå i overskriften på påloggingssiden.
    - 0 - Sikkerhetsstyring
    - 1 - Kvalitetssystem
    - 2 - Kartlegging
    - 3 - Kvalitetsstyringssystem
    - 4 - HMS-rapportering
    - 5 - Avviks-/HMS-meldingssystem
    - 6 - Kvalitetsportalen
    - 7 - HMS og Kvalitetssystem
    - 8 - HMSSK styringssystem
    - 9 - Kvalitets- og avvikssystem
    - 10 - Ledelsessystem
    - 11 - Kvalitet og internkontroll
    - 12 - Ledelsessystem for kvalitet og miljø

> Standardverdi 1

  - WORKERSTARTPAGE : Åpningsbildet for Brukere
    - 0 - Avvik og forslag
    - 1 - Forebyggende aktiviteter

 > Standardverdi 0

  - MANAGERSTARTPAGE: Defines the starting tab after login, if the user has that tab based on access rights.
    - 0 - HOME
    - 1 - ACTIVITY PLAN
    - 2 - INFO
    - 4 - ARCHIVE
    - 5 - Message form selection (Register message button list)
    - Any other other number - RISK

 Default value 0

SETUP

  - GOAL : Folderkontrol
    - 0 - Skjul
    - 1 - Vis

> Standardverdi 1

  - CALENDAR : Folderkontrol. Aktivitetsplan
    - 0 - SKjul
    - 1 - Vis

> Standardverdi 1

  - ADMIN : Folderkontrol
    - 0 - SKjul
    - 1 - Vis

> Standardverdi 1

  - REPORTS : Folderkontrol
    - 0 - SKjul
    - 1 - Vis

> Standardverdi 1

  - FAULT : Folderkontrol
    - 0 - SKjul
    - 1 - Vis

> Standardverdi 1

  - ACTION : Folderkontrol
    - 0 - Skjul
    - 1 - Vis

> Standardverdi 1

  - HELP : Folderkontrol
    - 0 - SKjul
    - 1 - Vis

> Standardverdi 1

  - RISK : Aktiver risikomodulen
    - 0 - Skjul
    - 1 - Vis

> Standardverdi 1

  - LOGMESSAGES : Aktiver loggmeldingsmodulen
    - 0 - Skjul
    - 1 - Vis

> Standardverdi 1

  - WORKORDER : Aktiver oppdragsmeldinger og Arbeidsordre
    - 0 - Skjul
    - 1 - Vis

> Standardverdi 1

  - MAILTYPE : Epostutsendelse
    - 0 - multipart/alternative; html + tekst
    - 1 - html
    - 2 - tekst

 > Standardverdi 0

  - ADVANCEDDOCSYSTEM: Vis "Dokumentarkfaner" under Admin / Dokumenter og disse vises også som ekstra arkfaner under Info
    - 0 - Av
    - 1 - på

> Standardverdi 1

  - ROLESACTIVATED: Aktiver rollestyring av arkfanen under admin
    - 0 - Av
    - 1 - på

 > Standardverdi 0

  - MENUROLECONTROL: Vis systemroller for arkfane nivå 1 kontrol
    - 0 - Av
    - 1 - på

 > Standardverdi 0

  - FIELDROLECONTROL: Vis systemroller for feltkontrol
    - 0 - Av
    - 1 - på

 > Standardverdi 0

  - NOPASSWORDDIRECTLOGON: Godta direkte pålogging uten passord
    - 0 - Av
    - 1 - på
    - 2 - Godta lenker uten passord. Brukes for pseudo SSO login.

> Standardverdi 1

  - RMSHOWNAME: Inkluder navnet på mottageren foran linken i påminnelsesepost. Viktig ved delt epostadresse, f.eks Torshov
    - 0 - Av
    - 1 - på

> Standardverdi 1

- SHOWUSERCOUNT: Vis aggregert antall brukere pr avdeling i navigatoren. Hvis på og span = 1, vises bare for innholdsadministrator.
  - 0 - Av
  - 1 - på

> Standardverdi 0

- REPORTFORM: Tilknytt et ekstra meldingsskjema til en liste. Brukes til å lage en rapport/konklusjon for en aktivitet.
  - 0 - Av
  - 1 - på

> Standardverdi 0

- SIMPLECASEPROCESS: Eneste saksbehandling avvist, rettet straks og send til saksbehandler. Tiltak fjernet.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- ACTIVITYDISTRIBUTION: Velg mellom NORMAL, REVISION og LEST OG FORSTÅTT.
  - 0 - Av
  - 1 - På

> Standardverdi 1

- EMAILPREAMBLE: Sett inn ekstra tekst i tittelfeltet for identifikasjon
  - 0 - Av
  - 1 -> Tekstnummer å sette inn

> Standardverdi 0

- SHOWUSERNAMEINFULLNAME: Styrer hvordan navnet på en bruker vises.
  - 0 - Fornavn, mellomnavn, etternavn
  - 1 - Etternavn, fornavn, mellomnavn
  - 2 - Brukernavn fornavn, mellomnavn, etternavn
  - 3 - Brukernavn etternavn, fornavn, mellomnavn

> Standardverdi 0

- NAVIGATORSTARTCLOSED: Styrer om navigatoren starter lukket.
  - 0 - Start åpen
  - 1 - Start lukket
  - 2 - Start lukket dersom avdeling brukeren logger inn på ikke har noen underavdelinger.

> Standardverdi 0

- LOG_MESSAGE_ACCESS: Styrer om tilgang til meldingsinnhold skal logges.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- SENDSMS : Styrer om SMS modulen er aktiv eller ikke
  - 0 - Av
  - 1 - På

> Standardverdi 0

- USER_NAME_SORT_TYPE : Styrer hvordan brukere er sortert
  - 0 Sorter etter Etternavn, Fornavn, Mellomnavn
  - 1 Sorter på visningsnavnet til brukeren

> Standardverdi 0

- CASEOFFICERLISTSETUP

- ENCRYPTPASSWORDS. Denne innstillingen er ikke lenger i bruk (v3.95)

- MFT : (Ikke i bruk)

- FACILIT : (Ikke i bruk)

- COMBINEDLIST : (Ikke i bruk)

- CASESENSITIVEPASSWORD : (Ikke i bruk)

- CASE_INSENSITIVE_USERNAME : Se bort fra store og små bokstaver i brukernavnet
  - 0 - Av
  - 1 - På

> Standardverdi 0

- COMPETENCE : Var funksjon laget for VFK som endret litt på visning av resultater for spørreundersøkelser. Brukes ikke av noen.

- EXTRA_USER_ATTRIBUTES : Legger til en mulighet i brukeradministrasjon for flere felter
  - 0 - Av
  - 1 - På

> Standardverdi 0

- ARCHIVE : (Ikke i bruk - byttet ut med FOLDER_ARCHIVE systemrolle knyttet til brukertyper)

- PREFERENCESADMIN : (Ikke i bruk)

- USE_V4_TOPMENU:
  - 0 - Av
  - 1 - På

> Standardverdi 0

- FORMTYPE_EXTERNAL : Meldingsskjematype Ekstern kan brukes til å koble meldingsregistreringsknapper til eksterne systemer.
  - 1 - På

> Standardverdi 0

- MULTIPLE_LOGOS : Mulighet for å ha forskjellige logoer per avdeling (i dokumentoverskrifter og på innloggingsskjermbilder). - IKKE I BRUK
  - 0 - Av
  - 1 - På

> Standardverdi 0

WORKERSETUP

Innstillinger for brukertypen medarbeider.

- GOAL: Folderkontrol
  - 0 - Skjul
  - 1 - Vis

> Standardverdi 1

- OVERVIEW: Folderkontrol
  - 0 - Skjul
  - 1 - Vis

> Standardverdi 1

- PREFERENCES: Folderkontrol
  - 0 - Skjul
  - 1 - Vis

> Standardverdi 1

- HELP: Folderkontrol
  - 0 - SKjul
  - 1 - Vis

> Standardverdi 1

- FAULT: Folderkontrol
  - 0 - Skjul
  - 1 - Vis

> Standardverdi 1

- ACTION: Folderkontrol
  - 0 - Skjul
  - 1 - Vis

> Standardverdi 1

- LIST: Folderkontrol
  - 0 - Skjul
  - 1 - Vis

> Standardverdi 1

- CONFUSED: Bruk Avvik og forslag i øverste verktøylinje istedenfor Mine saker. Bfk.
  - 0 - Ikke aktiv
  - 1 - Aktiv

> Standardverdi 0

- SHOWUSERREPORT
  - 0 - Endre melding
  - 1 - Dialog

> Standardverdi 0

- MSGLINKSTARTPAGE : Hvilken side som vises når man åpner en melding i forenklet grensesnitt
  - 0 - Endre melding
  - 1 - Dialog

> Standardverdi 0

FAULT

- COST: Vis kostnad i meldingssystemet
  - 0 - Skjul
  - 1 - Vis

> Standardverdi 1 i meldingen, 0 i oversikten

- PRIORITY: Vis prioritet i meldingssystemet
  - 0 - Skjul
  - 1 - Vis

> Standardverdi 1

- PRIORITY_TYPE: Hva prioritetsfeltet kalles
  - 0 - Prioritet
  - 1 - Alvorlighetsgrad

> Standardverdi 0

- OCCURENCES: Vis antall i meldingssystemet
  - 0 - Skjul
  - 1 - Vis

> Standardverdi 1

- SINGLEPROB: Bruk samme sannsynlighet for alle risikokategorier i meldingen
  - 0 - Av
  - 1 - På

> Standardverdi 0

- MESSAGESPRPAGE: antall meldinger pr side

> Standardverdi 20 

- AUTOMATICPROCESSDELAY: Antall dager tilgjenglig ved automatisk frist for saksbehandling

> Standardverdi 7
    -   

- EARLYCASEPROCESS

Send til saksbehandler dialogen aktivert av denne opsjonen tar med all brukere med systemrollen Standard meldingsmottaker (standard, brukertypen Leder), samt alle brukere som er definert i ekstra saksbehandler regler i forhold til valgt avdeling i navigatoren. For skjemaer med Tidlig saksbehandlingsregler definert,vil egendefinerte regler med tidlig saksbehandlere overstyre de automatiske - også når denne opsjonen er satt til 0.

  - 0 - Viser ikke send til saksbehandler i meldingsskjemaet
  - 1 - Viser send til saksbehandler i meldingsskjemaet
  - 2 - På, dropp ekstra saksbehandlere.
  - 3 - På, dropp underavdelinger.
  - 4 - På, dropp ekstra saksbehandlere og underavdelinger.
  - 5 - På, med sjekk og oppdatering av saksbehandlerlisten for hver endring i meldingen.

> Standardverdi 0

- EARLYCASEPROCESSINFO
  - 0 - no extra inform
  - 1 - inform some user. Span then contains the preselectedInformUser

> Standardverdi 0

- EARLYCASEPROCESSSELECT
  - 0 - Bare standard saksbehandler vises i valgboksen
  - 1 - Kan velge saksbehandler selv

> Standardverdi 1

- DEFAULTCASEPROCESSOR: Uid for den brukeren som skal være valgt i liste over saksbehandlere dersom ikke annen bruker er valgt tidligere. SetBy kolonnen kan ha et avdelingsnr som begrenser effekten til den avdelingen. Span er tenkt brukt til å begrense til skjemanr (ikke laget)

- VIEWALLVERSIONS: Kunne velge å se på tidligere versjoner av en melding for komplett endringshistorikk
  - 0 - Skjul
  - 1 - Vis

> Standardverdi 1

- SHOWCOMMENTS: Ta med kommentarer til lister og spørreskejmaer i grafer og meldingslister
  - 0 - Skjul
  - 1 - Vis

> Standardverdi 0

- SEARCHDATE : Setter hva som skal være standard fra dato på søkesiden
  - 0 - Et år
  - 1 - 01.01.00

> Standardverdi 0

- CHOOSELOGGER : Regulerer om alle brukere får lov til å registrere meldinger på andre på sin avdeling enn seg selv
  - 0 - Av
  - 1 - På. For på brukes Spanverdien også
    - 0: Endringen gjelder alle brukertyper.
    - 1: Endringen gjelder kun saksbehandlere.

> Standardverdier 0 og 0

- ACTIONSHORTCUTBUTTON : Vis / fjern lag tiltaksknappen i meldingsskjemaet.
  - 0 - Fjern
  - 1 - Vis

> Standardverdi 1

- COSTREADONLY : Gjør første kostnadsfelt kun redigerbart for Innholdsadministrator.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- SHOW_REPORTED_BY_IN_SEARCH_RESULT : Viser registrert på / melder kolonnen i tabellen og i PDF visning for søkeresultater.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- FAULT_RISK_DUE_DATE : Fristkolonnen vises i tabellen i Risikoarkfanen
  - 0 - Av
  - 1 - På

> Standardverdi 0

- CHOOSEDEPARTMENT : Om brukeren får lov til å registrere melding på annen avdeling enn egen
  - 0 - Nei
  - 1 - Alle tilgjengelige avdelinger
  - -1 - Fra og med avdelingen over innlogget avdeling

> Standardverdi 0

- FIELDROLECONTROL : (Ikke i bruk)

- RISKSCALE : Id til hvilken skala som skal brukes. Mappes mot et sett med tekstfelter i språkdatabasen MANAGERFAULTOVERVIEW.RISK
    - Se på Sannsynlighetssiden og Konsekvenssiden for de mulige verdiene hittil. Vær oppmerksom på at samme settnummer skal bli brukt for både sannsynlighet og konsekvens. Hvis et annet settnummer må brukes for konsekvens, kan du sette det i SPAN-feltet.

> Standardverdi 1

- SHOWFORMSELECT

- SHOWPRDEPCAT

- CASEPROCESSORFORMFILTER : (Ikke i bruk)

- CASEDOCUMENTS : Om last opp fil komponenten skal vises i meldingsskjemaet eller ikke.
  - 0 - Av
  - 1 - På

 > Standardverdi 0

- SEND_MESSAGE_REGISTERED_CONFIRMATION : Send kvittering på epost til melder når en ny melding registreres.
  - 0 - Av
  - 1 - Send kvittering når melding registreres via nettsidene.
  - 2 - Send kvittering når melding registreres via web-service (mobil).
  - 3 - Send kvittering uansett hvordan melding registreres.

 > Standardverdi  0

- DEPARTMENTPATH : Styrer hvor mye av stien til valgt avdeling som vises i Ny / Endre melding og i siden for forhåndsvisning av meldingsskjema.
    - 0 - Hele stien vises.
    - X - Viser bare de X siste nivående i stien.

 > Standardverdi 0

- GPS_ACTIVE : Option to enable location services in the Qm+ app and to display location for the registered messages on a map afterwards.
  - 0 - Av
  - 1 - På

> Standardverdi 0

MYPAGE

- SHOWBUTTONS : Bestemmer om det skal være nedfallsmeny eller knapper for å regsitrere ny melding.
  - 0 - Nedfallsmeny
  - 1 - Knapper

> Standardverdi 0

- SHOW_ID : Skal saksnummer vises i Innboks
  - 0 - Nei
  - 1 - Ja

> Standardverdi 1

- MAXBUTTONS : Antall skjemaer som gjør at knapperaden for å registrere ny melding blir byttet ut med fellesknapp i Innboks og medarbeidersiden

> Standardverdi 4

- CATEGORY_GROUP_TABLE_DISPLAY: When this is set to 1, display one column per category group, ordered alphabetically.
  - 0 - Nei
  - 1 - Ja

> Standardverdi 0

ACTION

- MESSAGESPRPAGE: antall meldinger pr side

 Standardverdi 20 

- COST: Vis kostnad i avvikssystemet
  - 0 - Skjul
  - 1 - Vis

> Standardverdi 0

- TIME: Show the action time fields
  - 0 - Skjul
  - 1 - Vis

> Standardverdi 0

- PREVENTION_FIELD: Show or hide the action prevention field ("Hvordan hindre gjentakelse (årsaksanalyse)")
  - 0 Skjul
  - 1 Vis
  - 2 Skjul feltet for alle tiltak opprettet etter datoen som er angitt i SPAN-feltet (datoformat: ÅÅÅÅMMDD)

> Standardverdi 0

INFO

- ORDER:
  - 0 - Sorter alfabetisk
  - 1 - Sorter etter posisjon

> Standardverdi 0

- PRCOL:
  - 1 - 1 kolonne med linkkategorier
  - 2 - 2 kolonner med linkkategorier

Standardverdi 2

- NOGOAL:
  - 0 - Målarkfanen vises
  - 1 - Målarkfanen vises ikke

> Standardverdi 0

- INLINEPAGE
  - 0 - Vanlig visning med navn på dokumenter som åpnes når man trykker på dem.
  - 1 - Dokumenter i en gitt arkfane vises direkte i Qm+ siden.

> Standardverdi 0

- SHOWPDFICON
  - 0 - PDF ikon for eksport til PDF dokument vises ikke for dokumenter skrevet i Qm+
  - 1 - PDF ikon for eksport til PDF dokument vises for dokumenter skrevet i Qm+

> Standardverdi 1

- SHOWPDFGROUPICON - PDF ikon for eksport av alle dokumenter i en mappe som kan eksporteres til PDF. Kun dokumenter skrevet i Qm+ kan idag eksporteres til PDF. Mapper uten slike dokumenter viser ikke ikonet.
  - 0 - PDF ikon vises ikke for mapper
  - 1 - PDF ikon vises for mapper

> Standardverdi 1

- SHOWWORDICON
  - 0 - Word ikon for eksport til docx dokument vises ikke for dokumenter skrevet i Qm+
  - 1 - Word ikon for eksport til docx dokument vises for dokumenter skrevet i Qm+

> Standardverdi 0

- TABLE_LAYOUT : Om dokumentgruppene følger tabell eller flyt layout
  - 1 - Flytlayout
  - 2 - Tabell

> Standardverdi 1

- INFO_COMMON_LAWS_TAB : Aktiver lovoversikten "Lovgrunnlag for kommuner" fra fellesdatabasen.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- INFO_COMMON_PROCEDURES_TAB : Aktiver prosedyreoversikten fra fellesdatabasen. ("Eksempel - Dokumentstruktur")
  - 0 - Av
  - 1 - På

> Standardverdi 0

- INFO_COMMON_LAWS_CONSTRUCTION_TAB : Aktiver lovoversikten "Lovgrunnlag for byggebransjen" fra fellesdatabasen.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- INFO_COMMON_LAWS_REGION_TAB : Aktiver lovoversikten "Lovgrunnlag for fylkeskommuner" fra fellesdatabasen. (DEAKTIVERT NÅ!!)
  - 0 - Av
  - 1 - På

> Standardverdi 0

- INFO_COMMON_LAWS_COMPANY_TAB : Aktiver lovoversikten "Lovgrunnlag for bedrifter" fra fellesdatabasen.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- INFO_COMMON_PROCEDURES_REGION_TAB :
  - 0 - Av
  - 1 - På

> Standardverdi 0

- INFO_COMMON_PROCEDURES_COMPANY_TAB :
  - 0 - Av
  - 1 - På

> Standardverdi 0

- INFO_COMMON_CUSTOM_TAB :
  - 0 - Av
  - 1 - På

> Standardverdi 0

- INFO_COMMON_DOCUMENTS_AFK :
  - 0 - Av
  - 1 - På

> Standardverdi 0

RISK

- LEVEL1: Laveste risikotall med gul advarsel

 Standardverdi 5

- LEVEL2: Laveste risikotall med rød advarsel

> Standardverdi 15

LIST

- ANONYMOUSPARTICIPATIONLIMIT : Antall svar som må være registrert før en graf for en anonym aktivitet kan vises
    - 0 - Grafen vises uansett antall svar
    - x > 0 - Grafen vises kun dersom antall registrerte svar er < x for valgt utvalg.

> Standardverdi 0

- ANONYMOUSPARTICIPATIONMINIMUMLIMIT : Minimum value for the drop-down "Number of answers before the result is visible" in the Edit activity page.

> Standardverdi 4

- HIDECOMMENTDIRECTLOGON : Skjul listen over kommentarer for de som har fått tilsent resultatet via Send resultat
  - 0 - Deaktivert
  - 1 - Aktivert

> Standardverdi 0

- EDITAFTERDUEDATE : Fylle ut nye svar og endre gamle for ledere og saksbehandlere etter at fristen er gått ut
  - 0 - Deaktivert
  - 1 - Aktivert

> Standardverdi 1

- SHOWGROUPMEAN : Vis gjennomsnittsverdien for hele gruppen samlet i grafen.
  - 0 - Deaktivert
  - 1 - Aktivert
  - Span brukes for å sette antall siffre etter , for desimaltall.

> Standardverdi 0
Standardverdi for span 2


- DEFAULTCOMMENTFORMID : Standard meldingsskjema å bruke for kommentarer til lister. Denne bør settes til id for Kommentarskjema for nye kunder.

> Standardverdi 0

- DEFAULTCOMMENTCATEGORYNR : Standard kategori å bruke for kommentarer til lister. Denne bør settes til id for kategorien Kommentar i Kommentarskjema for nye kunder.

> Standardverdi 0

- DOELEMENTOR : Om det skal gjøres AND eller OR sjekk for for alternativer i hvert spørsmpl ved svaralternativfiltrering i listegrafen
  - 0 - Bruk AND
  - 1 - Bruk OR

> Standardverdi 1

- INDIVIDUALCOMMENTFIELDS : Om det for flervalgspørsmål skal vises eget kommentarfelt for hvert alternativ.
  - 0 - Deaktivert
  - 1 - Aktivert

> Standardverdi 1

CALENDAR

- ADDCHILDACTIVITY : Ha muligheten til å lage underaktiviteter til aktiviteter i Aktivitetsplan. Underaktiviteter fungerer som vanlige aktiviteter, men de sorterer under hovedaktiviteten.
  - 0 - Deaktivert
  - 1 - Aktivert

> Standardverdi 0

- SHOWREFERENCE : Vis navnet på tilknyttede dokumenter til en aktivitet som en referanse for aktiviteten i tabellene som gir oversikt over aktiviteter i Aktivitetsplan.
  - 0 - Deaktivert
  - 1 - Aktivert

> Standardverdi 0

- SHOWFULLCOMMENTFORM : Alltid ha muligheten til å få opp fulstendig meldingsskjema med siden Har du kommentarer? selv om tekstfeltet har vært aktivit rett i listen.
  - 0 - Deaktivert
  - 1 - Aktivert

> Standardverdi 0

- CALENDAR_DEFAULT_READ_AND_UNDERSTOOD_LISTID : Id på liste som skal brukes som standard for lest og forstått aktiviteter. Brukes når SETUP_ACTIVITYDISTRIBUTION = 1.
  - Id på list som skal være forhåndsvalgt
  - Span verdien brukes for å sette id for delplanen som skal være forhåndsvalgt

> Standardverdi 0

CALENDAR_EXCHANGE_INTEGRATION : Styrer om feltene som indikerer mulig Exchange integrasjon er aktivert.

  - 0 - Deaktivert
  - 1 - Aktivert

> Standardverdi 0

WARNING

- CASEPROCESSORWARNING: Send epost til bruker som har meldinger eller tiltak der tidsfristen er gått ut. Det sendes 1 epost per bruker. Denne epostmeldingen inneholder lenker til alle meldingene, tiltakene og varsler for dokumenter som skal revideres brukeren er ansvarlig for, hvor fristen er gått ut.
  - 0 - Deaktivert
  - 1 - Aktivert: Ny epost sendes hver natt, så lenge sakene forblir ubehandlet.
  - 2 - hver søndag: For 2->8 sendes epost ukentlig på valgt dag.
  - 3 - hver mandag
  - 4 - hver tirsdag
  - 5 - hver onsdag
  - 6 - hver torsdag
  - 7 - hver fredag
  - 8 - hver lørdag

> Standardverdi 0

- ESCALATION_DAYS : Bestemmer om saker eskaleres etter å ha gått over frist. Verdien av opsjonen bestemmer hvor mange dager over fristen som må til før saken eskaleres. Eskaleringen utføres av nattjobben. Når en melding eskaleres, endres meldingens saksbehandler til å være første bruker rutinen møter på i et søk etter brukere med Systemrollen Standard meldingsmottaker i overliggende avdeling. Er det ikke treff i første overliggende avdeling, forsøkes neste nivå, inntil eventuelt toppen av organisasjonen nås. Span field can be used to define the days allowed to the new case handler, by moving the due date of the case ahead by this number of days.
  - 0 - Deaktivert
  - 1 -> Antall dager før eskalering inntreffer. Span field can be used to define the days allowed to the new case handler, by moving the due date of the case this number of days ahead.

> Standardverdi 0

- OVERDUEACTIONCREATOR: Når et tiltak er over frist, send e-postmeldingen ikke bare til de som skal utføre det, men også til brukeren som opprettet det.
  - 0 - Av
  - 1 - På

> Standardverdi 0

MAIL

- INCLUDEAPPDATA : Styrer om applikasjonsdata feltet i epost er med eller ikke. Bør bare være på for kunder med epostservere som ikke støtter "In-Reply-to" feltet i epost hodet.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- HIGHLIGHTLINKWARNING : Skal advarselen "Videresend aldri eposter fra Qm+ som inneholder lenke..." være på toppen i eposter sendt fra systemet og med rød farge?
  - 0 - nei, advarselen legges nederst med svart tekst
  - 1 - ja, advarselen legges øverst med rød tekst

Standardverdi  0

- INCLUDE_DESCRIPTION_IN_INFORM_EMAIL : Legger til det første tekstfeltet fra meldingen (saksbeskrivelse) til Inform-eposten (fra regelen)
  - 0 - Av
  - 1 - På

> Standardverdi 0

- PERSONALIZE_SENDER : For å gjøre e-poster fra systemet mer brukervennlige, setter vi at avsenderen av e-posten skal se ut til å være e-posten til den faktiske avsenderbrukeren, i stedet for msg-handler@qmplus.com, som er den faktiske avsenderadressen. Men noen e-postservere avviser e-poster der den faktiske avsenderen ikke er den samme som avsenderen som vises for mottakeren av sikkerhetsgrunner. For disse må denne preferansen settes til 0.
  - 0 - Av
  - 1 - På

> Standardverdi 1

DOCUMENTS

- CUSTOMHEADING : Styrer om virksomheten bruker egendefinert dokumenthode.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- AUTO_PUBLISH : Styrer om virksomhetens dokumenter trenger publisering før de er synlige under Info.
  - 0 - Av
  - 1 - På

> Standardverdi 1

- PUBLISH_DEPARTMENT : Styrer om det skal være mulig å legge inn dokumenter fra andre enn sine egne avdelinger.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- DOCUMENTS_EDITOR_MANUAL_STYLE_OPTIONS : Styrer om brukeren har opsjonene for å justere font og font størrelse manuelt aktivert.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- CUSTOMHEADINGFIELDS : Styrer funksjonen for kundespesifike dokumenthodefelt. Feltene må i tillegg kodes inn i kundens database for at dennefunksjonen skal virke.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- DOCUMENTS_AUTO_INCREASE_REVISION_PUBLISHED_ONLY : Styrer om dokumentet lagres med eget revisjonsnummer før dokumentet er publisert. Dersom denne opsjonen er aktivert, vil ikke dokumentet ha endringshistorikk før det publiseres.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- DOCUMENTS_STYLE_SHEET : Styrer om virksomheten bruker eget stilark for html editor og dokumentinnhold.
  - 0 - Av
  - Tallverdi - id for .css filen som skal brukes

> Standardverdi 0

- DOCUMENTS_PUBLISH_ONLY_APPROVED : Styrer om et dokument må ha en godkjent høring hør det kan publiseres.
  - 0 - Av
  - 1 - På

> Standardverdi 0

Span feltet kan brukes til å gi et avdelingsnummer der begrensningen starter.

- DOCUMENTS_COMMON_LAWS_TAB : Aktiver lovoversikten fra fellesdatabasen.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- DOCUMENTS_PROCEDURES_LAWS_TAB : Aktiver prosedyreoversikten fra fellesdatabasen.
  - 0 - Av
  - 1 - På

> Standardverdi 0

- DOCUMENTS_SHOW_HEARING_IN_HEADER : Om høringsinformasjonen skal tas med i dokumenthodet
  - 0 - Av
  - 1 - På

> Standardverdi 1

- DOCUMENTS_SKIP_CONTROLLERS_IN_HEADER : Om høringsdeltakerne skal droppes i dokumenthodet. Har ingen effekt om DOCUMENTS_SHOW_HEARING_IN_HEADER er 0
  - 0 - Av
  - 1 - På

> Standardverdi 0

- DOCUMENTS_MAX_FILE_SIZE : Kan økes opp til 50 MB

> Standardverdi 10 MB


LDAP

- LDAPINTEGRATION_ACTIVE : Determines if the night job runs LDAP synchronisation for this customer
  - 0 - Off
  - 1 - On

> Default value 0

- LDAPINTEGRATION_SEND_DEACTIVATE_USER_NOTICE
  - 0 - Off
  - 1 - On

> Default value 0
