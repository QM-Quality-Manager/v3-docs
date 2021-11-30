---
title: "Cases I am responsible for"
linkTitle: "Cases I am responsible for"
date: 2017-01-04
description: >
  Cases I am responsible for is a tab under Inbox.
---
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
