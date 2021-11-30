---
title: "Messages/NC"
linkTitle: "Messages/NC"
date: 2017-01-04
description: >
  Messages/NC (Non Conformance) is a tab under Archive.
---
Contains all the usual messages in the system. Used for easily retrieving reports over which messages are being processed, on which department, with which status. The Search functionality here is used to provide detailed reports over messages selected based on certain criteria and produces the same results as if you were under Reports and clicked on the part of the chart that represents the same criteria. When performing a search either from Reports or from the Message search, the selected search criteria are shown in a separate table above the results table.

### Drop-down menus

- All messages: If you select a message form, only messages originating from such a message form will be displayed.

### Table

- When you click on a line of the main table, the selected message will open in the handling page.
- Hold the cursor over the + symbol in the first column to get more information about a message, including its history.

### Buttons

- Configure category columns: Used to select which category group columns will be shown in the table.
  - The page is reloaded after each change.
  - The column selection affects all tabs in Archive for messages: Messages/NC, Log, Comments.
  - The column selection lasts until you log out.
  - The column selection also affects export to .pdf in Overview table format ("Show summary report" option in Option page for reports). Only the first 10 category groups will be included in the .pdf.
- Configure columns: Used to select which columns will be shown in the table.
  - The page is reloaded after each change.
  - The column selection affects all tabs in Archive for messages: Messages/NC, Log, Comments.
  - The column selection lasts until you log out.
  - The column selection also affects export to .pdf in Overview table format ("Show summary report" option in Option page for reports).
- Select messages for export / Cancel selection: Visible only when in Table view. Adds a selection column on the right side of the table, where the user can select which messages will be included in the pdf report. Pagination is lost temporarily and all messages appear in the page. When the Cancel selection is pressed, the Table view and the pagination get restored to their default state.
- {{< onlystaticimg src="/images/Page.png" >}} Expanded view / {{< onlystaticimg src="/images/Table.png" >}} Table: Switch between the expanded and the table view. The table gives a compact description of cases intended for use when working with them. The expanded view gives a more complete description of the whole case, similar to the printer friendly (.pdf) version.
- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Show as pdf: Opens the Option page for reports, from which you can create a report with the related messages.
- {{< onlystaticimg src="/images/LeftArrow.gif" >}} and {{< onlystaticimg src="/images/RightArrow.gif" >}} Change page: The arrows are used to change pages when there are more than 20 messages that can be shown in the table.
- {{< onlystaticimg src="/images/Arrowopen.gif" >}} and {{< onlystaticimg src="/images/Arrowclosed.gif" >}} Sorting: The table is sorted by the column with the {{< onlystaticimg src="/images/Arrowopen.gif" >}}. Click on the {{< onlystaticimg src="/images/Arrowclosed.gif" >}} to sort by another column.
- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the current page.
- {{< onlystaticimg src="/images/Help.png" >}} Page help: Opens this page.

### Tabs

The tabs here are used for choosing the status you wish to see.

- New messages: Messages that have not been processed.
- Sent to case handler: Messages that have been assigned to a responsible person.
- Action in progress: Messages which are attached to an action that has not been completed and approved.
- Closed cases: Messages which are attached to an action that has been completed and approved.
- Rejected: Messages that have been rejected. Rejected messages can be deleted by users with the system role content administrator.
- Search: Opens the Message search page.
