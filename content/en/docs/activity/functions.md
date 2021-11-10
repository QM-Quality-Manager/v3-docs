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
