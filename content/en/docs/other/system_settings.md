---
title: "System settings"
linkTitle: "System settings"
date: 2017-01-04
description: >
  System settings are adjustable elements used for making individual adjustments per customer. Changes from the standard version can be ordered by the customer's contact person with QmPlus AS. 
---
# REPORT

- LISTLENGTH: How many lines are shown in the four most common / most expensive tables.
  - - 1 gives all. -1 turns off the four parts of the heading (four most common / most expensive).

> Default value 4

- LISTCOST
  - 0 - The listCost field is not shown in the table.
  - 1 - Shows the listCost.

> Default value 1.

- LISTAMOUNT
  - 0 - The listAmount field is not shown in the table. // ORDER BY Data_Element_4 DESC
  - 1 - Shows the listAmount. // ORDER BY Data_Element_2 DESC
  - -1 - The listAmount field is not shown // ORDER BY TEXTTAG ASC

> Default value 1.

- GRAPHAMOUNT
  - 0 - The amount graph is not shown.
  - 1 - Shows the amount graph.

> Default value 1.

- GRAPHCOST
  - 0 - The cost graph is not shown.
  - 1 - Shows the cost graph.

> Default value 1.

- GRAPHORDER
  - 0 - ALPHABETICAL
  - 1 - OCCURENCES
  - 2 - COST

> Default value 0.

- TABLEORDER
  - 0 - OCCURENCES
  - 1 - COST

> Default value 0.

- SORTTYPE
  - 0 - ASCENDING
  - 1 - DESCENDING

> Default value 1.

- PAPERVERSION
  - 0 - The Extended view (previously: Printer friendly) button is not shown.
  - 1 - It shows.

> Default value 0.

- EMPLOYEEGRAPH
  - 0 - The employee graph is not shown.
  - 1 - It shows

> Default value 0.

- SHOWDATESELECT
  - 0 - The drop-down menu for the time period is not shown.
  - 1 - Shows the drop-down menu for the time period.

> Default value 1.

- DISPLAYCATEGORYCHART
  - 0 - The category chart starts hidden
  - 1 - The category chart starts shown

> Default value 0

- DISPLAYTOTALCHART
  - 0 - The total chart starts hidden (Overview by Departments checkbox unselected)
  - 1 - The total chart starts shown (Overview by Departments checkbox selected)

> Default value 0

- DISPLAYSTATUSCHART
  - 0 - The status chart starts hidden
  - 1 - The status chart starts shown

> Default value 1

- DISPLAYFORMCHART
  - 0 - The form chart starts hidden
  - 1 - The form chart starts shown

> Default value 1

- DISPLAYPRIORITYCHART
  - 0 - The priority chart starts hidden
  - 1 - The priority chart starts shown

> Default value 1

- DISPLAYUSERCHART
  - 0 - The user chart starts hidden
  - 1 - The user chart starts shown

> Default value 0

- DISPLAYTRENDCHART
  - 0 - The trend chart starts hidden
  - 1 - The trend chart starts shown

> Default value 0

- REPORT_INCLUDE_BLANK_DEPARTMENTS
  - 0 - Departments without messages are not shown in the Overview by departments
  - 1 - Departments without messages are shown in the Overview by departments

> Default value 0

- SHOWFORMSELECT If the charts by form should be displayed or not on the Reports page.
  - 0 - Off
  - 1 - On

 > Default value 1

- SHOWPRDEPCAT

 > Default value 1

# FAULTCASEPROCESS

- SENDEMAIL (NOT IN USE, replaced by ACTIONCASEPROCESS_SENDEMAIL)
  - 0 - The option Send email to case handler when sending an action to case handler is not checked by default.
  - 1 - The option Send email to case handler when sending an action to case handler is checked by default.

> Default value 1.

- USERSENDEMAIL (NOT IN USE, NOT IMPLEMENTED. PLEASE USE FAULTCASEPROCESS_USERFEEDBACK_DEFAULT_ON_CLOSE FOR OPTION 1)
  - 0 - The option Email to message originator is not checked by default.
  - 1 - The option Email to message originator is checked by default on any user action that closes the case (Message process: Close the case, Reject. Action process: Approved).
  - 2 - The option Email to message originator is checked by default on any user action that closes the case, as well as when the case is sent to a case handler or when an action is created (Message process: Choose case handler / Return to former case handler, Plan an action, Close the case, Reject. Action process: Approved).
  - 3 - The option Email to message originator is checked by default on any user action that closes the case, as well as when the case is sent to a case handler or when an action is created, and on every step in the action process (Message process: Choose case handler / Return to former case handler, Plan an action, Close the case, Reject. Action process: Send to execution, Send to approval, Approved)

> Default value 0.

- CASEPROCESSSENDEMAIL
  - 0 - The option Email to case handler is not checked by default.
  - 1 - The option Email to case handler is checked by default.

> Default value 1.
 

- SETDEFAULOWNER
- 0 - The owner must be set manually when creating an action.
- 1 - The owner is set to the current user when creating an action.

> Default value 1.

- ACTIONTAB
  - 0 - The Attach action tab is not shown.
  - 1 - The Attach action tab is shown.

> Default value 0.

- EXPANDEDFIXEDDIRECTLY : Register the name and description of the action immediately when forwarded. The parameter only affects the "Close the case" option on the Message process page.
  - 0 - Off
  - 1 - On

> Default value 1.

- USENROFTEXTFIELDS : When an action is created from message forms with more than two text fields, this command can be used to control where in the action they go.
  - 0 - Text field 1 in message -> text field 1 in action.
  - 2 - All text fields in the message -> text field 1 in action.
  - 3 - Text field 1 in message -> text field 1 in action. Rest of message text fields -> prevention field in action.

> Default value 0.

- COMMENTTEXTFIELDS : When an action is created from message forms all text fields including this one, are copied into the action comment. Both the name and value of the field are copied. Specially ordered by Tess.
  - 0 - Off
  - X - Number. Copy all text fields including this one, to the comment in the new action.

> Default value 0.

- CASEDOCUMENTS : Attachments to messages.
  - 0 - Off
  - 1 - On

> Default value 1.

- SHOWCOMPLETEMESSAGE : When you open the Message process page all categories will be visible.
  - 0 - Off
  - 1 - On

> Default value 0.

- FAULTCASEPROCESS_USERFEEDBACK_DEFAULT_ON_CLOSE : Send a note about the case starts preselected by default for all actions that close the case
  - 0 - Off
  - 1 - On

> Default value 0.

- INFOSENDEMPTYEMAIL (not in use)

- INFOTOPUSERDEP : Brukes for å sette hvilken avdeling som brukes som utgansgpunkt for å hente brukerne for "Alle" valget i "Informer flere"
  - 0 - "Alle" valget er ikke tilgjengelig
  - -1 - "Alle" valget er tilgjengelig, men bruker avdelingen spesifisert i SPAN som utgangspunkt
  --  Span: Hvis INFOTOPUSERDEP = -1, brukes span til å justere øverste avdeling
  -   - 0 - Bruk avdelingen over innlogget avdeling (standardverdi)
  -   - X - Kun avdelinger under dette avdelingsnummeret kan brukes
  - Alle andre verdier, "Alle" valget tilgjengelig. Bruk verdien som avdelingsnummer, f.eks 1 for at alle skal kunne velge alle.

> Default value null (Bruk øverste tilgjenglige avdeling for den aktive brukeren).

- INFOROLESETUP : Justerer øverste avdeling å hente brukere fra for rollevalgene i Informer flere
  - 0 - Bruk øverste avdeling 1
  - 1 - Bruk brukerens innloggede avdeling
  - 2 - Bruk valgt avdeling
  - -1 - Bruk avdelingen over innlogget avdeling

> Default value 0.

- NOACTIONNAME : Om navnet på tiltaket skal starte tomt eller ikke.
  - 0 - Navnet på tiltaket blir satt opp med de første 20 bokstavene fra første tekstfelt i meldingen
  - 1 - Starter blankt.

> Default value 1.

- NOACTIONDESCRIPTION : Om første tekstfelt i tiltaket skal starte tomt eller ikke.
  - 0 - Tekstfeltet blir satt opp som kopi av første tekstfelt i meldingen
  - 1 - Starter blankt.

> Default value 1.

- NOPREVENTIONDESCRIPTION : Om andre tekstfelt i tiltaket skal starte tomt eller ikke.
  - 0 - Tekstfeltet blir satt opp som kopi av første tekstfelt i meldingen
  - 1 - Starter blankt.

> Default value 1.

- STANDARDACTIONTYPE (not in use)

- DEFAULTACTIONOWNER (not in use)

- SHOWALLCATEGORIESINEMAILS : All the selected categories of the message are included in the email about the case, not just the defining one.
  - 0 - Off
  - 1 - On

> Default value 0.

# ACTIONCASEPROCESS

- SENDEMAIL
  - 0 - The option Send email to responsible for execution when creating an action is not checked by default.
  - 1 - The option Send email to responsible for execution when creating an action is checked by default.

> Default value 1.

- STRICTAPPROVAL
  - 0 - All managers can approve an action.
  - 1 - Only the manager who is set as the Responsible for approving the action can approve it.

> Default value 1.

- ACTIONTOPUSERDEP Used to set which department can be used as entry point for getting users to perform an action
  - -1 - Use the department above the active department (the department the user logged in to), for the user.
  - 0 - Use the active department for the user, activeDepNr
  - others - Use the value as a department number, example: 1 makes it possible for all to select users from the whole organisation.

> Default value 0

- ACTIONTEXTTAG Used to set the title for the action description field.
  - 1 Work description
  - 2 Corrective action
  - 3 Action description / Assessment of the effect of the action

> Default value 1.

- COST

> Default value 0

- TIME

> Default value 0

- START_DATE_FIELD

> Default value 0

- CHANGEMESSAGEDUEDATE Change the message due date to match the action due date, if message due date is earlier.
  - 0 - Message due date is independent of action(s) due date
  - 1 - Message due date gets updated automatically to match the action due date if action due date is after the message due date

> Default value 0

# LOGON

- TOPSELECTABLELOGONDEPNR
  - -1 - Use PRESETLOGONDEPNR.
  - Otherwise -The highest department number in the department hierarchy is allowed to log in anonymously or create users. Effective only if such a login is allowed from the settings in the control database.

> Default value 1.

- PRESETLOGONDEPNR : If anonymous login or self-generation of users is allowed, and you do not want the users themselves to choose department, set the department number here.

> Default value 1

- DIRECTLOGONHEADER : What should be written in the header of the direct login page next to Select.
  - 0 - Location
  - 1 - Department
  - 2 - Organisation

> Default value 1

- LOGONHEADER : What should be written in the header of the login page
  - 0 - Sikkerhetsstyring
  - 1 - Quality management system
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

> Default value 1

- WORKERSTARTPAGE : Opening page for users
  - 0 - Non conformance / Proposals
  - 1 - Preventive activities

> Default value 0

- MANAGERSTARTPAGE: Defines the starting tab after login, if the user has that tab based on access rights.
  - 0 - HOME
  - 1 - ACTIVITY PLAN
  - 2 - INFO
  - 4 - ARCHIVE
  - 5 - Message form selection (Register message button list)
  - Any other other number - RISK

> Default value 0

# SETUP

- GOAL : Tab control
  - 0 - Hide
  - 1 - Show

> Default value 1

- CALENDAR : Tab control for Activity plan menu
  - 0 - Hide
  - 1 - Show

> Default value 1

- ADMIN : Tab control
  - 0 - Hide
  - 1 - Show

> Default value 1

- REPORTS : Tab control
  - 0 - Hide
  - 1 - Show

> Default value 1

- FAULT : Tab control
  - 0 - Hide
  - 1 - Show

> Default value 1

- ACTION : Tab control
  - 0 - Hide
  - 1 - Show

> Default value 1

- HELP : Tab control
  - 0 - Hide
  - 1 - Show

> Default value 1

- RISK : Activates the risk module
  - 0 - Hide
  - 1 - Show

> Default value 1

- LOGMESSAGES : Activates the log messages module
  - 0 - Hide
  - 1 - Show

> Default value 1

- WORKORDER : Activates work messages and Work order replacement for Actions
  - 0 - Hide
  - 1 - Show

> Default value 1

- MAILTYPE : Email sending
  - 0 - multipart/alternative; html + text
  - 1 - html
  - 2 - text

> Default value 0

- ADVANCEDDOCSYSTEM: Shows the "Document tabs" under Admin/Documents and these also show as extra tabs under Info
  - 0 - Off
  - 1 - On

> Default value 1

- ROLESACTIVATED: Activates the role management tab under Admin
  - 0 - Off
  - 1 - On

> Default value 0

- MENUROLECONTROL: Shows the system roles for the tab Level 1 Control
  - 0 - Off
  - 1 - On

> Default value 0

- FIELDROLECONTROL: Shows the system roles for fields control
  - 0 - Off
  - 1 - On

> Default value 0

- NOPASSWORDDIRECTLOGON: Accept direct login without password
  - 0 - Off
  - 1 - On
  - 2 - Accept links without password. Used for the pseudo SSO login.

> Default value 1

- RMSHOWNAME: Include the name of the recipient in front of the link in the reminder email. Important for shared email address, eg Torshov
  - 0 - Off
  - 1 - On

> Default value 1

- SHOWUSERCOUNT: Show the aggregated number of users per department in the Navigator. If On and span = 1, only show for content administrator.
  - 0 - Off
  - 1 - On

> Default value 0

- REPORTFORM: Attach an additional message form to a list. Used to create a report / conclusion for an activity.
  - 0 - Off
  - 1 - On

> Default value 0

- SIMPLECASEPROCESS: Allowed actions are: Choose case handler, Close the case and Reject. Plan an action option removed.
  - 0 - Off
  - 1 - On

> Default value 0

- ACTIVITYDISTRIBUTION: Select between NORMAL, AUDIT, READ AND UNDERSTOOD (optional)
  - 0 - Off
  - 1 - On

> Default value 1

- EMAILPREAMBLE: Set additional text in the Subject field for identification
  - 0 - Off
  - 1 -> Text number to set

> Default value 0

- SHOWUSERNAMEINFULLNAME: Controls how the name of a user is displayed.
  - 0 - First name, middle name, last name
  - 1 - Last name, first name, middle name
  - 2 - Username first name, middle name, last name
  - 3 - Username last name, first name, middle name

> Default value 0

- NAVIGATORSTARTCLOSED: Should the navigator start closed or open.
  - 0 - Start open
  - 1 - Start closed
  - 2 - Start closed if the department the user is logging in to has no subdepartments.

> Default value 0

- LOG_MESSAGE_ACCESS : Controls if logging of message content access should be logged
  - 0 - Off
  - 1 - On

> Default value 0

- SENDSMS : Controls if the SMS module is active or not
  - 0 - Off
  - 1 - On

> Default value 0

- USER_NAME_SORT_TYPE : Controls how users are sorted
  - 0 Order by Last name, first name, middle name
  - 1 Order by full name

> Default value 0

- CASEOFFICERLISTSETUP

- ENCRYPTPASSWORDS. This preference is no longer in use (v3.95)

- MFT (not in use)

- FACILIT (not in use)

- COMBINEDLIST (not in use)

- CASESENSITIVEPASSWORD (not in use)

- CASE_INSENSITIVE_USERNAME : Se bort fra store og små bokstaver i brukernavnet
  - 0 - Off
  - 1 - On

> Default value 0

- COMPETENCE : Var funksjon laget for VFK som endret litt på visning av resultater for spørreundersøkelser. Brukes ikke av noen.

- EXTRA_USER_ATTRIBUTES : Legger til en mulighet i brukeradministrasjon for flere felter
  - 0 - Off
  - 1 - On

> Default value 0

- ARCHIVE : (Ikke i bruk - byttet ut med FOLDER_ARCHIVE systemrolle knyttet til brukertyper)

- PREFERENCESADMIN (not in use)

- USE_V4_TOPMENU: Use the icons from the v4 in the top tab row
  - 0 - Off (Keep the old look with the normal tabs)
  - 1 - On (Use the new look with the large tabs)

> Default value 0

- FORMTYPE_EXTERNAL : Message form type External can be used for linking message registration buttons to external systems
  - 0 - Off
  - 1 - On

> Default value 0

- MULTIPLE_LOGOS : Possibility to have different logos per department (in document headers and in login screens) - NOT IN USE
  - 0 - Off
  - 1 - On

> Default value 0

# WORKERSETUP

Settings the simplified interface.

- GOAL: Tab control
  - 0 - Hide
  - 1 - Show

> Default value 1

- OVERVIEW: Tab control
  - 0 - Hide
  - 1 - Show

> Default value 1

- PREFERENCES: Tab control
  - 0 - Hide
  - 1 - Show

> Default value 1

- HELP: Tab control
  - 0 - Hide
  - 1 - Show

> Default value 1

- FAULT: Tab control
  - 0 - Hide
  - 1 - Show

> Default value 1

- ACTION: Tab control
  - 0 - Hide
  - 1 - Show

> Default value 1

- LIST: Tab control
  - 0 - Hide
  - 1 - Show

> Default value 1

- CONFUSED: Use Non conformance / Proposals in the upper toolbar instead of My cases. Bfk.
  - 0 - Not activated
  - 1 - Activated

> Default value 0

- SHOWUSERREPORT
  - 0 - Endre melding
  - 1 - Dialog

> Default value 0

- MSGLINKSTARTPAGE : Hvilken side som vises når man åpner en melding i forenklet grensesnitt
  - 0 - Endre melding
  - 1 - Dialog

> Default value 0

# FAULT

- COST: Show the cost in the action system
  - 0 - Hide
  - 1 - Show

> Default value 1 in messages, 0 in the overview

- PRIORITY: Show the priority in the message system
  - 0 - Hide
  - 1 - Show

> Default value 1

- PRIORITY_TYPE: What the priority field is called
  - 0 - Priority
  - 1 - Severity

> Default value 0

- OCCURENCES: Show the number in the message system
  - 0 - Hide
  - 1 - Show

> Default value 1

- SINGLEPROB: Use the same probability for all risk categories in the message
  - 0 - Off
  - 1 - On

> Default value 0

- MESSAGESPRPAGE: number of messages per page

> Default value 20 

- AUTOMATICPROCESSDELAY: Number of days available for the automatic deadline for processing a case

> Default value 7
     

- EARLYCASEPROCESS

The Send to case handler dialogue that is enabled by this option includes all users with the system role Default message receiver (by default, user type Manager), and all the users defined in the rules for additional case handlers in relation to the department which is selected in the navigator. For forms that have Early case handler rules defined, the defined rules with the early case handlers will override the default ones - including when this option has value 0.

  - 0 - Does not show the Send to case handler option in the message form
  - 1 - Shows the Send to case handler option in the message form. If the span is also set, it only affects the form with the given formId (i.e. early case process is only activated for the form set in the span field)
  - 2 - On, skip extra case handlers.
  - 3 - On, skip sub departments
  - 4 - On, skip both extra case handlers and sub departments
  - 5 - On, checking and updating the case handler select after each change in the Edit message page.

> Default value 0

- EARLYCASEPROCESSINFO.
  - 0 - no extra inform
  - 1 - inform some user. Span then contains the preselectedInformUser.

> Default value 0

- EARLYCASEPROCESSSELECT
  - 0 - Only the default case handler will appear in the selection box
  - 1 - The user can select the case handler himself / herself.

> Default value 1

- DEFAULTCASEPROCESSOR: Uid for the user who will be selected in the list of case handlers unless another user was previously selected. SetBy column can have a department number that limits the impact to the department. Span is intended to be used for limiting the form number (not created)

- VIEWALLVERSIONS: Could choose to look at earlier versions of a message for the complete edit history
  - 0 - Hide
  - 1 - Show

> Default value 1

- SHOWCOMMENTS: Include comments to lists and survey forms in graphs and message lists
  - 0 - Hide
  - 1 - Show

> Default value 0

- SEARCHDATE : Sets what will be the default "From" date on the search page
  - 0 - One year
  - 1 - 01.01.00

> Default value 0

- CHOOSELOGGER : Determines if all users are allowed to register messages on others in their department besides themselves
  - 0 - Off
  - 1 - On. For On also the Span value is used
  --  0: The change applies to all user types
  --  1: The change applies only to case handlers.

> Default value 0 and 0

- ACTIONSHORTCUTBUTTON : Show / hide the Create action button in the message form
  - 0 -Hide
  - 1 - Show

> Default value 1

- COSTREADONLY : Makes the first cost field editable only for the Content administrator
  - 0 - Off
  - 1 - On

> Default value 0

- SHOW_REPORTED_BY_IN_SEARCH_RESULT : Shows the registered on / Message originator column in the table and PDF view for search results.
  - 0 - Off
  - 1 - On

> Default value 0

- FAULT_RISK_DUE_DATE : Show or hide due date column in Risk tab
  - 0 - Av
  - 1 - På

> Default value 0

- CHOOSEDEPARTMENT : Om brukeren får lov til å registrere melding på annen avdeling enn egen
  - 0 - Nei
  - 1 - Alle tilgjengelige avdelinger
  - -1 - Fra og med avdelingen over innlogget avdeling

> Default value 0

- FIELDROLECONTROL (not in use)

- RISKSCALE : Id of scale to use for labels in the risk matrix. Mapped against a set of textfields in language database MANAGERFAULTOVERVIEW.RISK
  - See the Probability page and the Consequence page for the possible values so far. Please note that by setting an id here, the same set number will be used for both Probability and Consequence. If a different set number needs to be used for Consequence, you can set it in the SPAN field.

> Default value 1

- SHOWFORMSELECT

- SHOWPRDEPCAT

- CASEPROCESSORFORMFILTER (not in use)

- CASEDOCUMENTS : File component activated or not in message form page
  - 0 - Off
  - 1 - On

> Default value 0

- SEND_MESSAGE_REGISTERED_CONFIRMATION : Send an email to the message originator upon new message registration.
  - 0 - Do not send an email
  - 1 - Send email confirmation when message registered from the web page
  - 2 - Send email confirmation when message registered from the mobile app
  - 3 - Send email confirmation when message registered from the web page or the mobile app

> Default value 0

- DEPARTMENTPATH : Controls how much of the path to the selected department is displayed on the New / Edit message page and on the Message form preview page.
  - 0 - The full path is displayed.
  - X - Only the last X number of departments in the organisation hierarchy are displayed.

> Default value 0

- GPS_ACTIVE : Option to enable location services in the Qm+ app and to display location for the registered messages on a map afterwards.
  - 0 - Off
  - 1 - On

> Default value 0

# MYPAGE

- SHOWBUTTONS : Determines if there will be a drop-down menu or a button for registering new messages
  - 0 - Drop-down menu
  - 1 - Button

> Default value 0

- SHOW_ID : Is the case number shown in the Inbox
  - 0 - No
  - 1 - Yes

> Default value 1

- MAXBUTTONS : Antall skjemaer som gjør at knapperaden for å registrere ny melding blir byttet ut med fellesknapp i Innboks og medarbeidersiden

Default value 4

- CATEGORY_GROUP_TABLE_DISPLAY: When this is set to 1, display one column per category group, ordered alphabetically.
  - 0 - No
  - 1 - Yes

Default value 0

# ACTION

- MESSAGESPRPAGE: number of messages per page

 Default value 20 

- COST: Show the cost in the message system
  - 0 - Hide
  - 1 - Show

> Default value 0

- TIME: Show the action time fields
  - 0 - Hide
  - 1 - Show

> Default value 0

- PREVENTION_FIELD
  - 0 Hide action prevention field ("How to prevent repetition (root cause analysis)")
  - 1 Show action prevention field.
  - 2 Hide action prevention field for all actions created after the date set in the SPAN field (date format: YYYYMMDD) - date specified included

> Default value 0

# INFO

- ORDER: (v3.96, May 2019: This may not be in use any more.)
  - 0 - Sort alphabetically
  - 1 - Sort by position

> Default value 0

- PRCOL:
  - 1 - 1 column with document groups
  - 2 - 2 columns with document groups

 Default value 2

- NOGOAL:
  - 0 - The Goal tab is shown
  - 1 - The Goal tab is not shown

Default value 0

- INLINEPAGE
  - 0 - Normal view with document names that opens the documents when clicked on.
  - 1 - Documents in a given tab are shown directly in the Qm+ page.

> Default value 0

- SHOWPDFICON
  - 0 - PDF icon for export to PDF document is not shown for documents written in Qm+
  - 1 - PDF icon for export to PDF document is shown for documents written in Qm+

> Default value 1

- SHOWPDFGROUPICON - PDF icon for export of all documents in a folder that may be exported to PDF. Only documents written in Qm+ may currently be exported to PDF. Folders without such documents do not show this icon.
  - 0 - PDF icon is not shown for folders
  - 1 - PDF icon is shown for folders

> Default value 1

- SHOWWORDICON
  - 0 - Word icon for export to docx document is not shown for documents written in Qm+
  - 1 - Word icon for export to docx document is shown for documents written in Qm+

> Default value 0

- TABLE_LAYOUT
  - 0 - Off. Normal flow layout. A group uses the amount of space it requires.
  - 1 - On. Table layout. 2 and 2 groups shown beside each other have the same length on the page.

> Default value 0.

- INFO_COMMON_LAWS_TAB : Activate the law overview "Lovgrunnlag for kommuner" from the common database.
  - 0 - Off
  - 1 - On

> Default value 0

- INFO_COMMON_PROCEDURES_TAB : Activate the procedure overview from the common database. ("Eksempel - Dokumentstruktur")
  - 0 - Off
  - 1 - On

> Default value 0

- INFO_COMMON_LAWS_CONSTRUCTION_TAB : Activate the law overview "Lovgrunnlag for byggebransjen" from the common database.
  - 0 - Off
  - 1 - On

> Default value 0

- INFO_COMMON_LAWS_REGION_TAB : Activate the law overview "Lovgrunnlag for fylkeskommuner" from the common database. (DEACTIVATED NOW!!)
  - 0 - Off
  - 1 - On

> Default value 0

- INFO_COMMON_LAWS_COMPANY_TAB : Activate the law overview "Lovgrunnlag for bedrifter" from the common database.
  - 0 - Off
  - 1 - On

> Default value 0

- INFO_COMMON_PROCEDURES_REGION_TAB :
  - 0 - Off
  - 1 - On

> Default value 0

- INFO_COMMON_PROCEDURES_COMPANY_TAB :
  - 0 - Off
  - 1 - On

> Default value 0

- INFO_COMMON_CUSTOM_TAB :
  - 0 - Off
  - 1 - On

> Default value 0

- INFO_COMMON_DOCUMENTS_AFK :
  - 0 - Off
  - 1 - On

> Default value 0

# RISK

- LEVEL1: The lowest risk number with a yellow warning

 Default value 5

- LEVEL2: The lowest risk number with a red warning

> Default value 15

# LIST

- ANONYMOUSPARTICIPATIONLIMIT : Number of answers that must be registered before a graph for an anonymous activity can be shown
  - 0 - The graph shows regardless of the number of answers
  - x > 0 - The graph shows only if the number of registered answers is< x for the selected range.

 Default value 6

- ANONYMOUSPARTICIPATIONMINIMUMLIMIT : Minimum value for the drop-down "Number of answers before the result is visible" in the Edit activity page.

> Default value 4

- HIDECOMMENTDIRECTLOGON : Hide the list of comments for those who have received the result via Send results
  - 0 - Deactivated
  - 1 - Activated

> Default value 0

- EDITAFTERDUEDATE : Fill out new answers and change the old for managers and case handlers after the deadline has expired
  - 0 - Deactivated
  - 1 - Activated

> Default value 1

- SHOWGROUPMEAN : Show the average value for the whole group depicted in the graph.
  - 0 - Deactivated
  - 1 - Activated
  - Span used to set number of decimals after ,

> Default value 0
 Default value span 2

- DEFAULTCOMMENTFORMID : Standard meldingsskjema å bruke for kommentarer til lister. Denne bør settes til id for Kommentarskjema for nye kunder.

> Default value 0

- DEFAULTCOMMENTCATEGORYNR : Standard kategori å bruke for kommentarer til lister. Denne bør settes til id for kategorien Kommentar i Kommentarskjema for nye kunder.

> Default value 0

- DOELEMENTOR : Om det skal gjøres AND eller OR sjekk for for alternativer i hvert spørsmpl ved svaralternativfiltrering i listegrafen
  - 0 - Bruk AND
  - 1 - Bruk OR

> Default value 1

- INDIVIDUALCOMMENTFIELDS : Om det for flervalgspørsmål skal vises eget kommentarfelt for hvert alternativ.
  - 0 - Deaktivert
  - 1 - Aktivert

Default value 1

# CALENDAR

- ADDCHILDACTIVITY : Have the possibility to create subactivities for the activities in the Activity plan. Subactivities works as usual activities, but they are sorted under the main activity.
  - 0 - Deactivated
  - 1 - Activated

> Default value 0

- SHOWREFERENCE : Show the name of the attached documents to an activity as a reference for the activity in the tables that provide an overview of the activities in the Activity plan.
  - 0 - Deactivated
  - 1 - Activated

> Default value 0

- SHOWFULLCOMMENTFORM : Always have the possibility to get a complete message form with the page Do you have any comments? even if the text field has been active right in the list.
  - 0 - Deactivated
  - 1 - Activated

> Default value 0

- CALENDAR_DEFAULT_READ_AND_UNDERSTOOD_LISTID : Used when SETUP_ACTIVITYDISTRIBUTION = 1.
  - The listId of the Read and Understood list.
  - Span can be used for the default activity group.


CALENDAR_EXCHANGE_INTEGRATION : Controls if the fields that indicate the possible Exchange integration is activated.

  - 0 - Deactivated
  - 1 - Activated

> Default value 0

# WARNING

- CASEPROCESSORWARNING: Send an email to users who have messages or actions that the deadline has expired. One email is sent for each user. The email contains links to all messages, actions and warnings for documents that need to be audited for which the user is responsible and their due date has passed.
  - 0 - Deactivated
  - 1 - Activated. New emails are sent each night, as long as the cases remain unhandled.
  - 2 - Every Sunday. For 2 - 8, messages are sent weekly on the selected day.
  - 3 - Every Monday
  - 4 - Every Tuesday
  - 5 - Every Wednesday
  - 6 - Every Thursday
  - 7 - Every Friday
  - 8 - Every Saturday

> Default value 0

- ESCALATION_DAYS : Determines whether cases are escalated after exceeding deadlines. The value of the option determines how many days over the period allowed before the case is escalated. The escalation is performed by the night job. When a message is escalated, the message's case handler changes to be the first user the routine meets in a search for users with the System Role Default message receiver in the parent department. If there is no match in the first parent department, its parent is tried until eventually the top of the organization is reached. So, in detail: Upon escalation, it is checked whether the current case handler has the role Default message receiver (the user type Manager is the only one that has it in the standard version). If the current case handler does not have this role, the message is sent to the first user the system finds in the same department (normally the user's manager) who has it. If the current case handler has this role, the message is sent to the first user the system finds in the department above which satisfies the requirement (the manager's manager).

  - 0 - Deactivated
  - 1 -> Number of days before the escalation happens. Span field can be used to define the days allowed to the new case handler, by moving the due date of the case this number of days ahead.

> Default value 0

- OVERDUEACTIONCREATOR: When an action has expired, send the warning email not only to its executors but also to its creator.
  - 0 - Off
  - 1 - On

> Default value 0

# MAIL

- INCLUDEAPPDATA : Turns the application data field in emails On or Off. Should be On only for customers with email servers that do not support the "In-Reply-to" email header.
  - 0 - Off
  - 1 - On

> Default value 0

- HIGHLIGHTLINKWARNING : Should the warning "Never forward emails from Qm+ containing links..." be at the top of the emails sent from the system and in red colour?
  - 0 - no, warning goes to the bottom of the email and text is black
  - 1 - yes, warning goes to the top of the email and text is red

> Default value 0

- INCLUDE_DESCRIPTION_IN_INFORM_EMAIL : Adds the 1st text field from the message (case description) to the Inform email (from the rule)
  - 0 - Off
  - 1 - On

> Default value 0

- PERSONALIZE_SENDER : In order to make emails from the system more user-friendly, we set the sender of the email to appear to be the email of the actual sender user, instead of msg-handler@qmplus.com, which is the actual sender address. But some email servers reject emails where the actual sender is not the same as the sender that appears to the recipient for security reasons. For those, this preference must be set to 0.
  - 0 - Off
  - 1 - On

> Default value 1


# DOCUMENTS

- CUSTOMHEADING : Turn on to use a customer defined document head.
  - 0 - Off
  - 1 - On

> Default value 0

- AUTO_PUBLISH : Controls if documents need to be published before they can appear under Info.
  - 0 - Off
  - 1 - On

> Default value 1

- PUBLISH_DEPARTMENT : Controls if is possible to store documents in departments other than your own.
  - 0 - Off
  - 1 - On

> Default value 0

- DOCUMENTS_EDITOR_MANUAL_STYLE_OPTIONS : Controls if the user has the options in the editor to adjust font and font size.
  - 0 - Off
  - 1 - On

> Default value 0

- CUSTOMHEADINGFIELDS : Controls the function for customer specific document heading fields. The fields must additionally be coded into the customer database for this function to work.
  - 0 - Off
  - 1 - On

> Default value 0

- DOCUMENTS_AUTO_INCREASE_REVISION_PUBLISHED_ONLY : Controls if the document is stored with a new revision number before it is published. If this option is active, the document will not have a change log in the version history before it is published.
  - 0 - Off
  - 1 - On

> Default value 0

- DOCUMENTS_STYLE_SHEET : Controls if the customer uses special stylesheet for html editor and document content.
  - 0 - Off
  - Number - id for .css file to be used

> Default value 0

- DOCUMENTS_PUBLISH_ONLY_APPROVED : Controls if a document must have an approved hearing before it can be published.
  - 0 - Off
  - 1 - On

> Default value 0

The Span value can be used to define a department number where the restriction starts.

- DOCUMENTS_COMMON_LAWS_TAB : Activate the law overview from the common database.
  - 0 - Off
  - 1 - On

> Default value 0

- DOCUMENTS_PROCEDURES_LAWS_TAB : Activate the procedure overview from the common database.
  - 0 - Off
  - 1 - On

> Default value 0

- DOCUMENTS_MAX_FILE_SIZE : The maximum allowed file size in MB for uploaded documents. Can be increased up to 50 MB.

> Default value 10 MB

- DOCUMENTS_SHOW_HEARING_IN_HEADER : Include the hearing information in the document header or not
  - 0 - Off
  - 1 - On

> Default value 1

- DOCUMENTS_SKIP_CONTROLLERS_IN_HEADER : If the hearing participants should be excluded from the document header. Has no effect if DOCUMENTS_SHOW_HEARING_IN_HEADER is 0
  - 0 - Off
  - 1 - On

> Default value 0

# FACILIT

- ACTIONMODE

- DEMANDROLE

# LDAP

- LDAPINTEGRATION_ACTIVE : Determines if the night job runs LDAP synchronisation for this customer
  - 0 - Off
  - 1 - On

> Default value 0

- LDAPINTEGRATION_SEND_DEACTIVATE_USER_NOTICE
  - 0 - Off
  - 1 - On

> Default value 0
