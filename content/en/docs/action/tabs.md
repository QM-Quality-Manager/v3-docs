---
title: "Tabs"
linkTitle: "Tabs"
date: 2017-01-04
description: >
  All tabs for actions.
---
# Actions
Actions is a tab under {{< onlystaticimg src="/images/Book.png" >}} Archive.

Shows all the actions registered on the department which is selected in the Navigator with the status that is selected in one of the underlying tabs. If the underlying tabs have one action for every status, an additional tab for search appears. When performing a search from Action search, the selected search criteria are shown in a separate table above the results table.

### Table

- By clicking on a line in the main table, the action will open in the Action process page.
- Hold the cursor over the + symbol in the first column to get more information about an action, including its history.

### Buttons

- {{< onlystaticimg src="/images/Page.png" >}} Expanded view / {{< onlystaticimg src="/images/Table.png" >}} Table: Toggle between table and expanded view. The table gives a compact description of the actions intended for use when working with them. The expanded view gives a more complete description of the whole action, similar to the printer friendly (.pdf) version.
- {{< onlystaticimg src="/images/LeftArrow.gif" >}} and {{< onlystaticimg src="/images/RightArrow.gif" >}} Change page: The arrows are used to change the page when there are more than 20 cases that can be displayed in the table.
- {{< onlystaticimg src="/images/Arrowopen.gif" >}} and {{< onlystaticimg src="/images/Arrowclosed.gif" >}} Sorting: The table is sorted by the column with the {{< onlystaticimg src="/images/Arrowopen.gif" >}}. Click on the {{< onlystaticimg src="/images/Arrowclosed.gif" >}} to sort by another column.
- {{< onlystaticimg src="/images/Page_save.png" >}} Save as file: Allows you to download and save the page as an HTML file on your machine locally. The file can be edited in any application that can edit HTML, including Word.
- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Show as pdf: Opens the Option page for reports, from which you can create a report with the related actions. This is intended for paper printing.
- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the current screen.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.

### Tabs

The tabs here are used for choosing which status you wish to see.

- Under planning: Actions that have not been initiated.
- Under execution: Actions that have been assigned to a person responsible for executing them and have been initiated.
- Under approval: Executed actions that are pending approval.
- Approved actions: Approved actions.
- Search: Advanced search for actions.

# Activity groups
Tab under Activity plan

The Activity groups page is used for managing activity groups. It is important that there is at least one activity group, otherwise it will not be possible to create new activities.

### Fields

- Name of the activity group: The name of the activity group.
- Comment: A comment about the activity group. Appears only on this screen.

### Drop-down menus

- Show for the language: Appears only when you have pressed Layout add.png New activity group or Folder.png Edit activity group. The text fields of an activity group can be registered in any language that is activated in the system.

### Icons

- {{< onlystaticimg src="/images/Folder.png" >}} Edit this activity group: Opens the data fields for the activity group so that they can be changed.
- {{< onlystaticimg src="/images/Layout_delete.png" >}} Delete activity group: Appears only for activity groups without activities.

### Buttons

- {{< onlystaticimg src="/images/Layout_add.png" >}} New activity group: Opens the data fields to create a new activity group.
- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the data fields of the selected activity group.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Closes the data fields for the requested activity group.

# Activity report tab worker
Activity report is a tab under Questionnaires for users having the simplified interface, and a function under Activity plan / Fill out and results for users having the complete interface.

Displays an overview of all the activities the user has participated in.

### Drop-down menus

- Activity group: Restricts the activities in the Activity drop-down menu to the activities from the selected activity group.
- Activity: The answers that the user has provided for the selected activity will be shown in the table below.

### Buttons

- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the current screen.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page
- {{< onlystaticimg src="/images/Page.png" >}} Show list: Shows the list associated with the selected activity in list version, as it looks like with the user's answer.
- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Show as pdf: Prints the current page to .pdf.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Closes this screen.

### Overview

- Displays a table for each topic in the list that has been answered. The topic name appears above each table.

### Tables

#### Summing up of the answered list

- Question: The question from the list that has been answered.
- My answers (worker interface) / Answer (manager interface): The answer to the question. For survey forms the text of the selected alternative answer is displayed. For checklists, a checked checkbox is displayed. If the user has commented on his / hers response to a given question, the comment will show here.
- Actions I participate in (worker interface) / Actions this user participates in (manager interface): If an action for this question has been created and the user is one of those who will execute it, a link to that action will appear here.
- Other actions (worker interface) / Available actions (manager interface): If an action for this question has been created and the user is not one of those who will execute it, a link to that action will appear here.

#### All actions created for the selected activity

This table appears only in the manager interface.

- Question: The question from the list to which the action is connected.
- Action number: A unique identifier for the action.
- Action name: The name of the action.
- Department: The department on which the action is registered.
- Status: The status of the action.
