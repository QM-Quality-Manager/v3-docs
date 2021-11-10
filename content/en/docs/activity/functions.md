---
title: "Functions"
linkTitle: "Functions"
date: 2017-01-04
description: >
  All functions for activity.
---
# Edit date
Edit date is a function for changing single dates for periodic activities.

Accesible from Activities.

### Fields

- From: The time when the activity starts.
- To: The time when the activity ends.

### Buttons

- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes made in the fields.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.

# Periodic activity setup
Periodic activity setup is used for setting the individual dates when the periodic activity will be performed.

### Fields

- From: Start time for the entire period. Copied from Edit activity.
- To: Ending time for the entire period. Copied from Edit activity.
- How often will the activity be performed: The period is selected here. Press the Choose button to generate the various dates.

After the Choose button is pressed, the individual dates can also be adjusted freely. Check the box on the Delete column if any of the dates need to be deleted. Click Save after all the required changes have been made.

### Buttons

- Choose: Generates the various dates for the selected period.
- Save: All changes in the table are saved.
- Close: Sends you back to Activities.

# Send results
Function under Activity plan / Graphs for the list.

Used for sending the results from an activity to users who normally do not have access to them. Results are sent by an email containing a link that opens the graph for the activity.

### Fields

- Heading: The name of the activity.
- Subject: The subject field in the email that will be sent out.
- Text field: Here you can write the text to be included in the email. The text "http://www.qmplus.com/Resultat" can be placed anywhere in the email, and will be replaced with an individual link for each recipient. This link will then be used to display the graph for the activity.
- "From" address: This email address will appear in the sender field (From:). It is automatically set to the registered email address of the user who writes the email. This address will also receive any error messages about invalid email addresses. Email addresses can be changed in the Edit user information under Admin / Users.
- Former result messages sent for this activity: If any results emails had been sent earlier for this activity they will be listed here. If you want to use the same text as in a previous email, check the appropriate box in the Select column and then click on the Use selected former message button.

### Send results to

Used to create a list of possible recipients.

- Department: Since the result that is sent out is a graph for the department which is selected in the Navigator, one can choose here the department for the users who will receive the results.
- Send results to those who have answered: Displays all the users who have answered the activity.
- Send results to those who could answer: Displays all the users who could answer the activity.
- Send results to those who have certain roles: Opens a new panel where you can select a set of roles. All the users who have at least one of the selected roles will be displayed.
- Choose from all users: Provides the opportunity to choose among all the users from the selected department and from its subordinate departments.

Select one of the 4 options above and click on the "Select" button.

- At the top there is a summary of how many users are in the list and how many of them have a seemingly valid email address.
- Send to: Check boxes for those who will receive the email. All the users in the list that have a seemingly valid email address are preselected.

### Buttons

- Select all: Checks all the users in the list that have a seemingly valid email address.
- Select none: Removes all checks in the user list. May be useful if for example you want to send a test email to yourself or send it to a small sample before sending it out to everyone.
- Send result: Sends the results to all the users that are selected in the user list. If there are many (> 100) users in the list, it may take some time before all emails are sent out. It is possible to close the Send results window while emails are being sent. When all the emails have been sent, you will get a message if you have not closed the Send results window. That does not necessarily mean that everyone has received their email. Sometimes emails take longer time to be delivered than you expect. Also remember to look in your own email inbox for messages about invalid email addresses. These addresses must be corrected before you can send the email to them again.
- Use selected former message: Appears only for activities for which results emails have been sent earlier. Retrieves the subject and text of the selected former email so that it can be reused. You can make changes to the former text before sending the message. When you are finished, you have to click on the Send result button as usual.

# Edit activity
Edit activity is a function for managing activities.
Available from Activities.

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
  - Repeating: Repetitive activity. Can be filled out an unlimited number of times by each participant. Used when you do not know in advance how many times a list will be needed and filled out. Can also be used for anonymous external surveys.
  - Periodic: Used when you want to schedule a periodic execution of an activity forward in time. Set the From and To fields to include the entire period you want to schedule. After you make all the other selections in this page you need to press Save. Then you will go to the page Periodic activity setup. There you can set the period, e.g. daily, weekly, annually. This option is not recommended for the first time you create an activity. It is only appropriate to make periodic activities if you are certain that the attached list is not going to change within that period.

- Do you want an email reminder before the activity is due?: The system can send an email to the person who created the activity at the number of days before it ends that will be selected in the drop-down menu. The email will contain information such as how many people participated and how many should participate, as well as a link to Follow up where you can write and send a reminder email to those who have not yet answered.
- Send new reminder?:
- Should an email reminder be sent to the participants before the activity is due?:
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