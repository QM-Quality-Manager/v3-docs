---
title: "Archive"
linkTitle: "Archive"
date: 2017-01-04
description: >
  Archive is a tab on the Main Page.
---
{{< onlystaticimg src="/images/Book.png" >}} The Archive contains all cases in the system. Used for retrieving reports over which cases are being processed, on which department, what is their status. The Search functionality here is used to provide detailed reports over cases selected based on certain criteria and produces the same results as if you were under Reports and clicked on the part of the chart that represents the same criteria.

### Drop-down menus

- All messages: If you select a message form, only cases originating from such a message form will be displayed.

### Table

- When you click on a line of the main table, the selected case will open in its process page. Messages open the Message process page, while actions open the Action process page. Log messages open in the Edit message page, since these are not normally processed.
- Hold the cursor over the + symbol in the first column to get more information about a case, including its history.

### Buttons

- Configure category columns: Does not show for Actions. Used to select which category group columns will be shown in the table.
  - The page is reloaded after each change.
  - The column selection affects all tabs in Archive for messages: Messages/NC, Log, Comments.
  - The column selection lasts until you log out.
  - The column selection also affects export to .pdf in Overview table format ("Show summary report" option in Option page for reports). Only the first 10 category groups will be included in the .pdf.
- Configure columns: Does not show for Actions. Used to select which columns will be shown in the table.
  - The page is reloaded after each change.
  - The column selection affects all tabs in Archive for messages: Messages/NC, Log, Comments.
  - The column selection lasts until you log out.
  - The column selection also affects export to .pdf in Overview table format ("Show summary report" option in Option page for reports).
- Select messages for export / Cancel selection: Does not show for Actions and is visible only when in Table view. Adds a selection column on the right side of the table, where the user can select which messages will be included in the pdf report. Pagination is lost temporarily and all messages appear in the page. When the Cancel selection is pressed, the Table view and the pagination get restored to their default state.
- {{< onlystaticimg src="/images/Page.png" >}} Expanded view / {{< onlystaticimg src="/images/Table.png" >}} Table: Switch between the expanded and the table view. The table gives a compact description of cases intended for use when working with them. The expanded view gives a more complete description of the whole case, similar to the printer friendly (.pdf) version.
- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Show as pdf: Opens the Option page for reports, from which you can create a report with the related cases.
- {{< onlystaticimg src="/images/Page_save.png" >}} Save as file: Allows you to download and save the page as an HTML file on your machine locally. The file can be edited in any application that can edit HTML, including Word. Shows only for Actions.
- {{< onlystaticimg src="/images/LeftArrow.gif" >}} and {{< onlystaticimg src="/images/RightArrow.gif" >}} Change page: The arrows are used to change pages when there are more than 20 cases that can be shown in the table.
- {{< onlystaticimg src="/images/Arrowopen.gif" >}} and {{< onlystaticimg src="/images/Arrowclosed.gif" >}} Sorting: The table is sorted by the column with the {{< onlystaticimg src="/images/Arrowopen.gif" >}}. Click on the {{< onlystaticimg src="/images/Arrowclosed.gif" >}} to sort by another column.
- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the current page.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.

### Tabs

- Messages/NC: Registration and overview of messages that follow the usual handling process.
- Log: Registration and overview of log messages. Not included in the standard version.
- Comments: Overview of comment messages.
- Actions: Overview of actions.
