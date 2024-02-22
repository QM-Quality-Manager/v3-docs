---
title: "Action process"
linkTitle: "Action process"
date: 2017-01-04
description: >
  Tab under Inbox and Archive.
---
The possibility to make changes in this page depends on the user's access to the relevant action. See Access control for actions.

### Action data

- Action number: A unique number for each action.
- Action name: Used to identify the action in tables and overviews. Mandatory field.
- Registered on department: The department on which the action is registered.
- Start time: Does not show in the standard version.
- Must be finished before: Due date for the action.
- Budget: How much is allocated to the implementation of the action.
- Actual cost: How much was spent on the execution of the action. This field is used for calculating the cost graph for the action under Reports.
- Planned time:
- Actual time:

### Action description

- Original deviation: Copied from the first text field in the original message.
- Work description: Copied from the second text field in the original message. Should often be changed to a concrete task for those who will execute the action.
- How to prevent repetition: Copied from a possible third text field in the original message. Here you can write a little about other changes than the one that must be executed in this action, so that the original deviation will not happen again.
- Comment: Additional comments to the action.

### Action categories

Used for categorizing the action.

### Status

This panel indicates where the action is in the action process. It partly controls the appearance of the rest of this screen.

- Under planning: All actions start with this status. In this phase, the action is being planned. First give a name to the action so that it becomes easy to identify it later, and enter the budget if you use this field. The text fields Corrective action and How to prevent repetition must be filled out so that those who will execute the action will know what to do. The action categories may also be selected now. The last thing is to select those who should execute the action and give them a deadline. This is done in the mandatory panel Persons responsible. Click on Send to execution >> or the >> button in the Status panel to save the action and change its status to Under execution.
- Under execution: In this phase, the work described in the action will be executed. Then those who carried out the action must tick the Executed box. They can also write a comment in the Comment field and fill in the Actual cost if they know it. When all the changes have been done, use the button Send to approval >> or the >> button in the Status panel. This saves the action and changes its status to Under approval.
- Under approval: Here the person who created the action will make sure everything is in order before (s)he approves the action.
- Approved: An approved action is closed and locked and can not be changed except by users with the system role content administrator. Comments can still be sent out to all involved users .

### Persons responsible

Shows an overview of all who have been involved in the case. They all have a checkbox next to their name that is used if you wish to send a message by email to some of these people with regard to this case. All sent messages will also appear at the bottom of this screen.

- Message originator: The users who have created messages attached to this action.
- The action was created by: The user who created the action and thus is responsible for it. Must approve the action before it is closed.
- The action will be executed by: Those who will execute the action.
  - Executed: This must be checked when the action has been performed (finished).
  - Executed on / Hours spent: If time registration is enabled, the action executor can log his / her work here, by setting a date and filling in the hours field (decimal values accepted), and then clicking Save.
  - Work log: If time registration is enabled, each time the Save button is clicked above, the logged hours appear here. You cannot add multiple entries for the same day, but you can always edit the existing entry for a specific date by clicking on it (the fields are editable).
- The action will be approved by: The person who will approve the action. In the standard version it is always the same user who created the action.

### Case history

Displays an overview of events for this action.

- All edits of the content or status.
- Attachment or detachment of messages.
- All sent out email comments attached to this action.

### Buttons

- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Show as pdf: Opens the Option page for reports from which you can export the current action to a .pdf file. This is intended for paper printing.
- {{< onlystaticimg src="/images/Application_form_delete.png" >}} Delete action: Deletes the action. Appears only for the user who has created the action as long as it still has status Under planning, and for Content administrators. Deleted actions cannot be restored or found again.
- {{< onlystaticimg src="/images/Tick.png" >}} Save action: Saves the changes you have made. Remember that this button never changes the Status.
- {{< onlystaticimg src="/images/Tick.png" >}} Send: Appears when you do not have permission to make changes in the action. Used to send email comments related to the action.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Returns you to the page you came from, unless you were in a message and created an action. Then you will go to where you opened this message from.
- {{< onlystaticimg src="/images/Calendar_icon.png" >}} Calendar: Opens the calendar to select the date.
- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the current page.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.
- {{< onlystaticimg src="/images/Application_form.png" >}} Attached messages: Displays the messages attached to this action. Possibility to attach and detach more messages and to delete the action, for users who have the right to do it.

### Tabs

- Action process: Reloads this page. All changes you have made without pressing the Save button afterwards will be lost.
