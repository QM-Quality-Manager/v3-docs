---
title: "Edit activity"
linkTitle: "Edit activity"
date: 2017-01-04
description: >
  Edit activity is a function for managing activities.
---
### Fields

- Activity group: Select which activity group this activity will belong to.
- Activity name: Identifies the activity in tables and overviews. Also used as a heading when an attached list is filled out.
- Attached list: If a list should be filled out, it is selected here. The lists in the drop-down menu are sorted by list type. This field cannot be changed after someone has answered the activity.
  - {{< onlystaticimg src="/images/Page.png" >}} Show printer friendly version: Opens the printer friendly version of the selected list. Click on this icon when a list is selected to see how it looks.
- From: The date and time when the activity starts. Click on the {{< onlystaticimg src="/images/Calendar_icon.png" >}} to open a calendar for date selection.
- To: The date and time when the activity ends. Click on the {{< onlystaticimg src="/images/Calendar_icon.png" >}} to open a calendar for date selection.

### Buttons

- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes made in the fields.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.
- {{< onlystaticimg src="/images/Cog_add.png" >}} Show / {{< onlystaticimg src="/images/Cog_delete.png" >}} Hide advanced options: Displays or hides the advanced options.

### Advanced options

These are options that come up when the button {{< onlystaticimg src="/images/Cog_add.png" >}} Show advanced options is used. The advanced options are hidden by using the button {{< onlystaticimg src="/images/Cog_delete.png" >}} Hide advanced options.

#### Fields
- Show for the language: Drop-down menu with the languages that are activated in the system. - The name of the activity can be set once for every available language.
- Activity distribution (Optional):
  - Normal: The answers of the participants are registered on their own department.
  - Audit: Those who participate can answer the activity once for each department they have access to. If the activity is repetitive, they can answer it an unlimited number of times per department.
  - Read and understood: A Read and understood activity is used to distribute a document and get a confirmation that it has been read and understood. Read and understood activities behave exactly as usual activities, with the exception that they cannot be sent out periodically, repetitively or anonymously. These options are therefore hidden when the option Read and understood is selected as the Activity distribution. Those who want this feature turned on must contact QmPlus AS.

- The subordinate departments will do the activity: Check this box if the subdepartments of the selected department will also participate in the activity.
- How often will the activity be performed?: Drop-down menu to determine the type of the activity.
  - One time: Common activity that can be filled out once by all the users who can participate.
  - Repeating: Repetitive activity. Can be filled out an unlimited number of times by each participant. Used when you do not know in advance how many times a list should be filled out. Can also be used for anonymous external surveys.
  - Periodic: Used when you want to schedule a periodic execution of an activity forward in time. Set the From and To fields to include the entire period you want to schedule. After you make all the other selections in this page you need to press Save. Then you will go to the page Periodic activity setup. There you can set the period, e.g. daily, weekly, annually. This option is not recommended for the first time you create an activity. It is only appropriate to make periodic activities if you are certain that the attached list is not going to change within that period.

- Do you want an email reminder before the activity is due?: The system can send an email to the person who created the activity at the number of days before it ends that will be selected in the drop-down menu. The email will contain information such as how many people participated and how many should participate, as well as a link to Follow up where you can write and send a reminder email to those who have not yet answered.
- Send new reminder?:
- Should an email reminder be sent to the participants before the activity is due?: The system can send an email to the participants who have not yet answered the activity at the selected time (1, 2, 3, 5, 7, 14, 21 or 30 days before the end date).
- Send new reminder?:
- This activity is answered anonymously: Checkbox that makes the activity anonymous. Comments on anonymous activities will be anonymous.
- Number of answers before the result is visible: Appears only when the anonymity box is checked. The number selected here controls how many answers a single department must have before a graph is shown for this department under Graphs for the list. The starting value of this drop-down can be changed using the system setting ANONYMOUSPARTICIPATIONMINIMUMLIMIT.
- Display as list: The list will be answered in the list version view. Click on the {{< onlystaticimg src="/images/Page.png" >}} icon to see how the selected list looks like in this display type. Should be used for checklists and risk analysis lists. Can be used for survey forms.
- Display as series of single questions (reminder link only): Τhe list will be answered as a series of single questions. Click on the {{< onlystaticimg src="/images/Page.png" >}} icon to see how the selected list looks like in this display type. Used to give survey forms the more traditional questionnaire look. "Reminder link only" means that this display type will only be used when the person who will answer the list has come to it by clicking on the link in the email that is sent out as a reminder for the activity. Otherwise, if for example you are logged into Qm+ as usual, the list version will always be used when you try to fill out the list.
- Display as control list: In this view, there is one checkbox per day per question and the alternative answers do not appear at all.
- Roles that will perform the activity: When you associate roles to an activity, only users that have at least one of these roles can participate in it. If no roles are selected, all within the selected departments can participate.
- Document tab selection: Only documents which belong to the document tab that is selected here are shown below.
- Add documents to the activity: Documents attached to the activity will be shown at the top of the attached list as blue clickable links when it is answered. Used if those who will answer need to have reference material or additional information available when they answer the list. Please note that if you add a document that has subdocuments, all its subdocuments will also be added to the activity.

#### Buttons
- << Add: Adds one or more of the items which are selected in the right panel to the activity.
- Remove >>: Removes one or more of the items which are selected in the left panel to the activity.
