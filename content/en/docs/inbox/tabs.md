---
title: "Tabs"
linkTitle: "Tabs"
date: 2017-01-04
description: >
  All tabs for inbox.
---
# Cases I am responsible for
{{< onlystaticimg src="/images/User.png" >}} Cases I am responsible for is a tab under {{< onlystaticimg src="/images/Table_edit.png" >}} Inbox.

Cases I am responsible for shows cases that the logged in user has to work with, regardless of the department which is selected in the Navigator. This tab is not shown if the user can not process messages, perform actions, participate in hearings or perform document audits.

Pink cases are messages, yellow cases are actions, blue-gray cases are hearings. Audit warnings have no colour.

### Options

- {{< onlystaticimg src="/images/Application_form_edit.png" >}} Register new message: Select a message form to register a new message. Opens the Edit message page. The message forms are displayed as individual buttons if there are up to 4 different forms. If there are more, the button {{< onlystaticimg src="/images/Application_form_add.png" >}} Register new message must be pressed first. This opens a list of all active message forms.
- All cases drop-down menu: If you select a message form, only cases originating from such a form are shown.
- Cases I am responsible for / All cases I have been involved in: When "Cases I am responsible for" is selected, only cases that the logged in user should do something about are shown. When "All cases I have been involved in" is selected, the list shown below includes also the cases that the logged in user has done something about but they are not closed yet.

### Icons

- {{< onlystaticimg src="/images/LeftArrow.gif" >}} and {{< onlystaticimg src="/images/RightArrow.gif" >}} Change page: The arrows are used to change the page when there are more than 20 cases that can be displayed in the table.
- {{< onlystaticimg src="/images/Sort_down.png" >}} and {{< onlystaticimg src="/images/No_sort.png" >}} Sorting: The table is sorted by the column with the {{< onlystaticimg src="/images/Sort_down.png" >}}. Click on {{< onlystaticimg src="/images/No_sort.png" >}} to sort on another column.
- {{< onlystaticimg src="/images/Flag_green.png" >}},{{< onlystaticimg src="/images/Flag_yellow.png" >}},{{< onlystaticimg src="/images/Flag_red.png" >}} Priority: Symbolize low, medium and high priority respectively.

### Main table

When you click on a line of the main table, the selected case will open in its handling page. Messages open in the Message process page, actions open in the Action process page and hearings open in the Reply to a hearing page.

- \+ Extra Information and History: Hold the cursor over the + symbol to get more information about the case. Currently, only for messages and actions.
- Message form: Which message form was used to create the case.
- Registered: The date when the case was registered. For messages when they were registered, for actions when they were created.
- Due: For messages this is the handling deadline, for actions this is the execution and approval deadline.
- Description: For messages this is the text in the first text field of the message, for actions this is their name.
- Priority: {{< onlystaticimg src="/images/Flag_green.png" >}},{{< onlystaticimg src="/images/Flag_yellow.png" >}},{{< onlystaticimg src="/images/Flag_red.png" >}} symbolize low, medium and high priority respectively. For actions, this is the priority of the attached message to them with the highest priority.
- Status: The status of the case.
- Registered on department: The department where the case was originally registered.
- Current case handler: The name of the user who is responsible for handling the case. Depends on the type and status of the case. Shows only when the option "All cases I have been involved in" is selected above the table.
  - Messages:
    - <The name of a user>: This user is the assigned responsible person for the case.
  - Actions:
    - With status <<Under planning>>: The name of the user who has created the action and is responsible for it.
    - With status <<Under execution>>: The names of the users who will execute the action.
    - With status <<Under approval>>: The name of the user who has created the action and is responsible for approving it.
  - Hearing:
    - With status <<On hearing>>: The names of the users who will participate in the hearing.
    - With status <<For approval>>: The name of the user who will approve the hearing.

### Which cases are shown in the table?

- Messages sent to the logged in user via Send to case handler under Message process or via the Early case process under Edit message.
- For managers (users with the system role default message receiver):
  - Messages registered on the department where the manager is registered on and have not been assigned to another responsible person.
  - Messages registered on a subordinate department where there isn't a manager, and have not been assigned to another responsible person. Messages registered on departments without a manager will be moved upwards in the organisation hierarchy and will appears in the Inbox on the first department above that has a manager.
- Actions that the user has created and are being planned.
- Actions that the user has to execute and are under execution.
- Actions that the user is assigned as action approver for. This assignment is done either by creating the action or by a rule of type action approver.
- Hearings that the user has to participate in and are on hearing.
- Hearings that the user has to approve and are under approval.
- Audit warning for documents that have passed their audit warning date and the user is set as audit responsible.
- Audits the user has to do.

Please note that messages other users have registered which were made with message forms that have a role with the "See messages" limitation, will not be shown here unless the logged in user has the same role or the system role See all messages attached to him / her or to the user type the user is logged in with. Messages which the user himself / herself has registered will be shown. 

# Message process
Tab under Inbox and Archive.

Used for processing messages. Notice the message status. It can be seen both in the header and in the message field below. Also note whether the case currently has a responsible person before you start doing something about it. If it does, it is written in the field "Current case handler: <user name>" just below the header.

### {{< onlystaticimg src="/images/Info.png" >}} What can I do here?

- Here I can handle a case. Click: Choose action in the yellow / orange panel, or.....
- I can simply "Send a note about the case". Click on the white checkbox and write in the textfield that appears. This is sent by e-mail!
- I can also edit the message contents: Click on the tab "Edit message".

### Message details

This table provides a brief description of the content and status of the message that will be processed in this page. Click on Arrowclosed.gif to see the rest of the checked categories.

### Choose action

Drop-down menu with a coloured background that means that this is where you need to do something if you come to this page. Whatever choice you make in this drop-down menu, you will be able to check off the "Send a note about the case" that makes the dialog boxes appear and gives you the possibility to send an email to those involved in the case.

Possible actions: Click Save / Send after you have selected an action in order for it to happen.

- Choose case handler: Used when you want to transfer the responsibility for the message to someone else, or set a deadline for the message. Note that it is up to the receiver of the message whether (s)he will create an action or (s)he will reject it. Those you can send the message to are those who have the user type manager or case handler on your own department, the department above it in the hierarchy or one of the departments under your own. You can also send the message to those who are set up under the tab Rules with the rule type "Additional case handlers" with a remit that includes your department. Please note that for messages that are created with message forms which have a role with the "See messages" limitation, those who do not satisfy that limitation will be taken off this list. You can set a deadline for when the person you send it to should have done something about it.
- Return to former case handler: Used when you want to transfer the responsibility for the message back to someone who had it before. This option is only shown when a message has changed case handler at least once.
- Reject: Used when a message will not be followed up further. This may be a test message, or duplicate or similar. This option should not be used for real messages.
- Register done action
- Close the case. Used when a small action that does not require further action is about to be executed or has already been executed. You get the opportunity to register who has executed the action and write a name and a description of the work that was done.
- Plan an action: Opens all the fields for the planning phase of the action.
  - Give the action a name.
  - Write a description of the work that will be performed. This must contain enough information, so that the person who will be assigned to the job will know what to do. You can also give an extended description of what can be done to prevent the incident from happening again.
  - Choose who will perform the action in the field "Choose the persons that will do the job". If you need people from other departments, use the department selection drop-down menu above the two fields that show the users. To add users, select them in the right panel and press the << button.
  - Update the deadline ("Must be finished before") if necessary.
  - Send email to those who are responsible for the execution if necessary.
  - Click Save / Send. This will create the action. A link to the new action appears in a table at the top of the page. Click on it or on the tab Action process if you wish to see the complete action details.
- Upload file: Used to upload external files that will be attached to this message. Maximum file size is 10 MB. Not enabled in the standard version.
- Send to Facilit. Appears only for those who have integration with Facilit. Select a property and a building and press Save. This creates an action in Qm+ that is attached to an action in Facilit. The text and the categories from the original deviation are also sent to the action in Facilit. When the action in Facilit changes status, the status of the action in Qm+ is updated also. No other information from Facilit appears in the action in Qm+ other than the status change.
- There is an option there, where, on a customer basis, one can choose if an action that is reported to be completed in Facilit should get the status Under approval (default) or Approved. An action that gets the status Under approval in Qm+ must be approved manually in Qm+ by the person who sent the case to Facilit in order to close it.
- Each customer has the option to remove all options from this drop-down menu except from "Close the case" and "Reject".

### Send a note about the case

This field is used to send text messages to users who are involved in the case. Anyone who has access to a message can use these fields, regardless of the message's status. All notes sent here will be saved in this case and shown in the "Case history" table at the bottom of the page. They are also sent as an email if the selected recipients have registered a valid email address. If the SMS-module is activated, the option to send the notification as an SMS also appears.

- Message originator ("Registered on behalf of"): Check this box to send a text message to the person who originally created the message. The name of this user is in the field "Registered on behalf of".
- Has the case now: Field for the current case handler.
- Former case handlers: Field for all the users who have been responsible for the message previously. Select the person(s) you want to send a message to.
- Inform more: Here you can select users who are not directly involved in the case but should nevertheless be informed about it. The users in the left panel will receive the message you wrote when you press Save.
  - Choose from: Drop-down menu that determines which users will appear in the list of potential recipients to the right below this menu. The options are:
    - Case handler list: All users with a user type containing the system role inform shortlist on the selected department in the Navigator, the department above it and in all departments below it in the hierarchy. In addition, all the users with the a user type containing the system role Process message that are set up under the tab Rules with a remit that includes the selected department in the Navigator.
    - All: All users, regardless of user type, from the department which is selected in the Navigator and its subordinate departments.
    - <Role name>: All users, regardless of user type, the department which is selected in the Navigator and its subordinate departments who have the selected role.
      - There is an option there, where, on a customer basis, one can choose if the options All and <Role name> will show all users regardless of department.

### Buttons

- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes you have made. If the send email option was checked, this action sends the emails.
- {{< onlystaticimg src="/images/Email_go.png" >}} Send: Sends the message you wrote, but does not save any other changes. This button is shown in place of the Save button if you do not have edit rights to the message.
- {{< onlystaticimg src="/images/User_add.png" >}} <<: Moves the selected users from the right panel to the recipient list on the left.
- {{< onlystaticimg src="/images/User_add.png" >}} << All: Moves all the users from the right panel to the recipient list on the left.
- {{< onlystaticimg src="/images/User_delete.png" >}} >> All: Removes all users from the recipient list. Those who belong to the selected list (list type set in the drop-down menu "Choose from:") appear in the list on the right.
- {{< onlystaticimg src="/images/User_delete.png" >}} >>: Removes the selected users from the recipient list. Those who belong to the selected list (list type set in the drop-down menu "Choose from:") appear in the list on the right.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Sends you back to the page you came from.
- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Show as pdf: Opens the Option page for reports from which you can export the current message to a .pdf file. This is intended for paper printing.
- {{< onlystaticimg src="/images/Delete.png" >}} Delete (icon): Appears next to the attachment hyperlink. Used to delete attachments. Available only for the user who uploaded the attachment and for Content administrators.
- {{< onlystaticimg src="/images/Delete.png" >}} Delete (button): Appears at the bottom of the screen for messages with status Rejected and only for Content administrators. Marks a message as Deleted. Such messages can only be found again by searching for the message number and require the system role Content administrator to be opened.
- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the active window.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.

### Case history

Shows the history of all changes for the message, both for content and status. Shows also all correspondence about the case. All messages sent from the dialog panel above and all replies sent to them are shown here.
Tabs

- Edit message: Opens the Edit message page.
- Message process: Reloads this page. All changes you have made but not saved will be lost.






