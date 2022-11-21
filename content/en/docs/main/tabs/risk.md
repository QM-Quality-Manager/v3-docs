---
title: "Risk"
linkTitle: "Risk"
date: 2017-01-04
description: >
  Risk is a tab on the main page.
---
Appears only for the companies that have activated the Risk message module for the users who have the system role Risk. The purpose of this page is to show the current risk status for the organisation.

The tab Risk contains all the risk messages in the system from the active departments. Risk messages are messages that are used to create a risk overview for the company. It is up to the company if the risk messages will be handled or if they will only be registered and stored in the archive. Our recommendation is that they are not handled, only updated annually. Messages registered here do not appear in the Inbox unless you use the Message process page to handle them. The message type risk message is not enabled in the standard version. When performing a search either from Reports, from the Message search or by clicking on the risk matrix, the selected search criteria are shown in a separate table above the results table.

### Risk matrix

The risk matrix provides a risk profile for the selected part of the company. The numbers in the matrix show how many messages in the table below have risk categories with values corresponding to a field in the risk matrix.

- The numbers in the risk matrix show only categories from messages in the table below.
- The Navigator is used to set the starting department for the risk overview.
- Click on a field in the matrix to look only at the messages that have categories in this field. This is performed as a search and changes the selected tab. The risk field in the search criteria shows which field you clicked on.
- Messages with only the value 0 for all of their risk categories do not appear in the matrix.

### Drop-down menus

Not included in the simplified interface.

- Selection of departments:
  - This department: Only messages registered on the department which is selected in the Navigator are shown.
  - This and subordinate departments: All messages registered on the department which is selected in the Navigator and on its subordinate departments are shown.
  - Subordinate departments: Only messages registered on the subordinate departments of the one which is selected in the Navigator are shown.
- Display type:
  - Total: It shows a risk matrix for the overall result of all risk categories for the messages in the table.
  - Per category: It shows a risk matrix for each risk category that is used in the messages in the table.
  - Individual: It shows a risk matrix for the risk category that is selected in the risk category drop-down menu.
- Risk category: Appears only when the display type "Individual" is selected. Determines which risk category is shown in the risk matrix. Only messages with a registered risk value > 0 for the selected risk category will be displayed. Please note that only categories from active category groups are shown here.

### Selections

Not included in the simplified interface.

- All messages drop-down menu: Select a message form and only messages originating from that message form will be shown. Only message forms of the type Risk are shown here.
- {{< onlystaticimg src="/images/Calendar.png" >}} Date search: From date, To date. Only messages registered in the period displayed here are shown in the table.

### Table

- When you click on a line of the main table, the selected message will open in the Edit message page.
- Hold the cursor over the + symbol in the first column to get more information about a message, including its history.

### Buttons

- Configure columns: Used to select which columns will be shown in the table.
  - The page is reloaded after each change.
  - The column selection lasts until you log out.
  - The column selection also affects export to .pdf in Overview table format ("Show summary report" option in Option page for reports).
- {{< onlystaticimg src="/images/Application_form_edit.png" >}} Register new message: Select a button with the name of a message form to register a new message. Only message forms of the type Risk are shown here.
- {{< onlystaticimg src="/images/Find.png" >}} Search: Update the table of messages based on the selected dates.
- {{< onlystaticimg src="/images/Page.png" >}} Expanded view / {{< onlystaticimg src="/images/Table.png" >}} Table: Switch between the expanded and the table view. The table gives a compact description of messages intended for use when working with them. The expanded view gives a more complete description of the whole message, similar to the printer friendly (.pdf) version.
- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Show as pdf: Opens the Option page for reports, from which you can create a report with the related risk messages. This is intended for paper printing.
- {{< onlystaticimg src="/images/LeftArrow.gif" >}} and {{< onlystaticimg src="/images/RightArrow.gif" >}} Change page: The arrows are used to change pages when there are more than 20 cases that can be shown in the table.
- {{< onlystaticimg src="/images/Arrowopen.gif" >}} and {{< onlystaticimg src="/images/Arrowclosed.gif" >}} Sorting: The table is sorted by the column with the {{< onlystaticimg src="/images/Arrowopen.gif" >}}. Click on the {{< onlystaticimg src="/images/Arrowclosed.gif" >}} to sort by another column.
- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the current page.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.

### Tabs

- Risk overview: All the risk messages that are registered on the department which is selected in the Navigator.
- Search: Opens the Message search with the form type Risk preselected.
