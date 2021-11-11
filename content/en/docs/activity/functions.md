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

# Users that have answered the element
Function under the Activity plan. Used for seeing all the users and actions of a question. Opens from Graphs for the list.

### Headings

- The main heading shows for which activities the data are shown in the table below.
- The second heading Users that have answered the element shows for which question in the list are the data shown in the table below.

### Buttons

- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the current screen.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.
- {{< onlystaticimg src="/images/Application_form.png" >}} Show actions / {{< onlystaticimg src="/images/User.png" >}} Show users: Toggles between displaying the actions done for this question and the users who have checked / answered this question.
- {{< onlystaticimg src="/images/Application_form_edit.png" >}} Plan new action: Creates a new action for the point in the list that is described at the heading.
- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Show as pdf: Prints the current page to .pdf.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Sends you back to the page where you came from.

### Table

- Name: The name of the user.
- Type: The user type.
- Department: The department on which the answer is registered.
- Registered date: The date when the answer was first registered.
- Edit {{< onlystaticimg src="/images/Folder.png" >}}: Opens the answered list of the user.

# Graphs for the list
Function under the Activity plan for displaying the result of activities. By using the List results, the result from several activities that use the same list can be displayed and compared in the same screen.

### Fields

- Headline: Shows which list is used in the activity. Click on it to display the Comments to the activity for all the activities shown in this page.
- Activities shown in these graphs: List of all the activities included in the graphs below. There will only be one graph unless you have used the List results. Click on it to display the Comments to the activity for the selected activity.

### Drop-down menus

- Department selection:
  - Distributed on this and subdepartments: A blue graph will be shown for the results from the department which is selected in the Navigator and an orange graph for the sum of the results from the departments under the selected department in the hierarchy.
  - Total for this and subdepartments: A blue graph will be shown that is the sum of the results from the selected department and its subordinate departments.
- Graph type:
  - Shown as sum: The graph shows the results as the number of answers.
  - Shown as percentage: The graph shows the result as a percentage of the total number of answers for each question. If "Distributed on this and subdepartments" is selected, there is a percentage for the selected department and a percentage for the subordinate departments.
    - For survey forms, the percentage is calculated for each alternative answer based on how many people have answered every single question.
    - For checklists the percentage is calculated based on all who have answered the list. Blank answers are also included here.
  - Shown as mean value: Shows the average values for the answers. If the alternative answers begin with a number, then this number will be used as a weight, if the first alternative does not have the value 1, the next 2 etc. Alternatives that begin with the number 0 are not counted in the average value, either in the sum or in the number of answers that it is divided into. For alternatives that begin with a number, the average value will be the calculated number. For other alternatives, it will be the text of the alternative the index of which is closest to the calculated number.

### Graph

The appearance of the graph depends on the list type.

- Checklists have one graph per question.
- Risk analysis lists have a total risk matrix over the list of questions. An additional drop-down menu "Show graph" controls if the page displays the Count or the Average view.
  - Count: The total risk matrix at the top displays the number of answers to the questions in the list that fall within each risk area. Additionally, each question in the list gets its own risk matrix that shows the distribution of the answers to that question. To the right of each risk matrix is a table that shows the distribution of answers to that question within each risk group (red, yellow, green). The Count view is shown by default when you first open this page.
  - Average: The total risk matrix at the top displays the number of questions where the average value of the answers gives the specific risk value. For each question you get two charts displaying the average risk value of all answers to the question in the selected department in the Navigator (blue) and the average risk value of all answers to the question in the departments subordinate to the selected department in the Navigator (orange).
- Survey forms have one graph per alternative answer.

#### Click functionality

- You can click on all the questions in the list. Then you will go to Comments to the activity for the selected question. This can also be done by clicking on the {{< onlystaticimg src="/images/Folder.png" >}} icon.
- If you click on the activity name or its {{< onlystaticimg src="/images/Folder.png" >}} icon you will go to the page Comments to the activity for the selected activity.
- If you click on the list name you will go to the page Comments to the activity for all activities in the chart. Usually there is just one activity in the chart, but by using the list results page you can create charts that contain the results for more than one activities at the same time.
- You can click on all the charts in the table. This opens the page Users that have answered the element for the selected question.

### Buttons

- {{< onlystaticimg src="/images/Key_add.png" >}} Show / {{< onlystaticimg src="/images/Key_delete.png" >}} Hide selection filter: Hide or show the selection filter.
  - When the selection filter is activated, you can select the questions or the alternative answers you want to filter on.
  - Only answers that satisfy all selections will be included in the graph after the button Show selected results is pressed.
  - The selection filter also affects what is displayed under Comments to the activity and Users that have answered the element.
  - It also allows for filtering the result on a role connected to the user who has answered.
  - If a role is selected in the drop-down, only the users who have the selected role attached to their user, user type or the department the answer is registered on are included in the result.
- {{< onlystaticimg src="/images/Email_edit.png" >}} Send result: Opens the Send results page to publish the depicted graph to others.
- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Show as pdf: Prints the current page to .pdf.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.
- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the current page. Make sure that the option Print background colours and images is selected in Internet Options / Advanced / Print if you are using Internet Explorer, File / Page Setup / Print Background (colours and images) in Mozilla Firefox. Otherwise, the graphs will not be printed correctly. Mozilla Firefox has in some cases problems with printing screens that span multiple pages. This may depend on the setup, but seems to be a widespread problem.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.

### Actions

You have many possibilities to create actions for an activity from this page.

- Open the Comments to the activity by clicking on a question, the title of the activity or the title of the list. This will attach the action to the comment messages that appear in this page. If there aren't any comment messages, the action will still be attached to the question or the list depending on where you clicked.
- Open the Users that have answered the element by clicking on a graph. You can do this if you want to create a action for those who have given a specific answer to a question.

Which page you will go to, affects what the action will be attached to. So what is right depends on whether you want it to be common to the whole list, attached to a single question or to an alternative answer. 

# Send reminder
{{< onlystaticimg src="/images/Email_edit.png" >}} Send reminder is a function under the {{< onlystaticimg src="/images/Calendar.png" >}} Activity plan. Opens from Follow up and Activities.

Used for notifying those who will perform an activity. The reminder is sent by an email containing a link that opens the list which is attached to the activity. The list of possible recipients includes all participants in the activity who have not yet answered it.

### Fields

- Heading: The name of the activity.
- Subject: The subject field in the email that will be sent out.
- Text field: Here you can write the text to be included in the email. The text "http://www.qmplus.net/Link" can be placed anywhere in the email, and will be replaced with an individual link for each recipient. This link will then be used to answer the activity for each user. If several users answer the same activity by using the same link only the last reply will be registered, unless the activity is registered as a repetitive activity. It is therefore important that such emails are not forwarded.
- "From" address: This email address will show in the sender field (From:) of the email. It is automatically set to the registered email address of the user who writes the reminder. This address will also receive any error messages about invalid email addresses. Email addresses can be changed from the Edit user information under Admin / Users.
- Former reminders sent for this activity: If any reminders had been sent earlier for this activity they will be listed here. If you want to use the same text as in a previous reminder, check the appropriate box in the Select column and then click on the Use selected former message button.

### User list

- The list includes all the users who will participate in the activity and have not already answered it. The list is sorted by name.
- At the top there is a summary of how many users are in the list and how many of them have a seemingly valid email address.
- Send to: Check boxes for those who will receive the reminder. All the users in the list who have a seemingly valid email address are preselected.

### Buttons

- Select all: Checks all the users in the list that have a seemingly valid email address.
- Select none: Removes all checks in the user list. May be useful if you want to send a test reminder to yourself or send the email to a small sample before sending it out to everyone.
- Send reminder: Sends the reminder to all the users that are selected in the user list. If there are many (> 100) users in the list, it may take some time before all emails are sent out. It is possible to close the Send reminder window while emails are being sent. When all the emails have been sent, you will get a message if you have not closed the Send reminder window. That does not necessarily mean that everyone has received their email. Sometimes emails take longer time to be delivered than you expect. Also remember to look in your own email inbox for messages about invalid email addresses. These addresses must be corrected before you can send the reminder to them again.
- Use the text from the selected former reminder: Appears only for activities for which email reminders have been sent earlier. Retrieves the subject and text of the selected former reminder so that it can be reused. You can make changes to the former text before sending the message. When you are finished, you have to click on the Send reminder button as usual.



