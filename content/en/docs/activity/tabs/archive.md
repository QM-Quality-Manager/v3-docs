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

# Comments to the activity
Function under the Activity plan. Used for viewing all the comment messages, actions and reports for an activity or a question.

### Headings

- The headline says for which activity or activities are the data shown in the table below.
- The smaller heading "Concerning question" below says for which question in the list are the data shown in the table below. If this heading is not here, the data for the whole list is displayed.

### Drop-down menus

- Show comments / actions: Document type selection.
  - Show comments: Comment messages are shown in the table.
  - Show actions: Actions are shown in the table.
  - Show reports: Activity reports are shown in the table. Not included in the standard version.
- Action location selection: Appears only when "Show actions" is selected in the first drop-down menu.
  - Actions registered on: Takes into account only the department on which the action is registered. This is the department that the user had selected in the Navigator when "Create new action" was pressed.
  - Actions with executors from: Takes into account only the department on which those that are set up to perform the action are registered.
- Department selection: Appears only when "Show actions" is selected in the first drop-down menu.
  - This department: Only cases that belong to the department which is selected in the Navigator appear in the table.
  - This and subordinate departments: Cases that belong to the department which is selected in the Navigator or to its subordinate departments appear in the table.

### Buttons

- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Show as pdf: Opens the Option page for reports, from which you can create a report with the related comment messages. This is intended for paper printing.
- {{< onlystaticimg src="/images/Page.png" >}} Expanded view / {{< onlystaticimg src="/images/Table.png" >}} Table: Switch between the expanded and the table view. The table gives a compact description of the comment messages intended for use when working with them. The expanded view gives a more complete description of the comment messages, similar to the printer friendly (.pdf) version.
- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the active window.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.
- {{< onlystaticimg src="/images/Report.png" >}} Report: Create a new report for this activity. Not included in the standard version.
- {{< onlystaticimg src="/images/Application_form_edit.png" >}} Create new action: Creates a new action for the element in the list that is described by the headlines.
  - If "Show comments" is selected in the first drop-down menu, all selected comments in the table below will be attached to the new action. All comments are preselected. Click on the checkbox on the column header (next to "Select") to select or deselect all comments at the same time or click on specific comments to (de)select them one at a time.
  - If "Show actions" is selected in the first drop-down menu, the new action will be blank and will be attached to a "dummy" message which will not be editable and will not be used otherwise. You can use this when you need to create an action for a question to which no comments were added.
  - The button does not appear when "Show reports" is selected in the first drop-down menu.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Sends you back to the page you came from.

### Icons

- {{< onlystaticimg src="/images/Arrowclosed.gif" >}}: Sort on this column.
- {{< onlystaticimg src="/images/Arrowopen.gif" >}}: The table is sorted on this column.
- {{< onlystaticimg src="/images/LeftArrow.gif" >}}: If there are several pages, scroll forward.
- {{< onlystaticimg src="/images/RightArrow.gif" >}}: If there are several pages, scroll backward.

### Table

- \+: Hold the cursor over this field to get extended information about the case, including its history.
- Registered: When was the case registered.
- Due: The deadline for the case. Does not appear when "Show actions" is selected in the first drop-down menu.
- Question: The question for which the comment was written. Does not appear when "Show actions" is selected in the first drop-down menu.
- Comment: Text written from the user as a comment to this question. Does not appear when "Show actions" is selected in the first drop-down menu.
- Priority: Does not appear when "Show actions" is selected in the first drop-down menu.
- Status: The status of the action or comment message.
- Operative department: The department by which the comment is being processed. Does not appear when "Show actions" is selected in the first drop-down menu. Does not show for anonymous activities.
- Select: When you press the "Create new action" button, the state of the checkbox determines if the new action will be attached to the current comment (selected) or not (not selected). Appears only when "Show comments" is selected in the first drop-down menu.
- Action name: Appears only when "Show actions" is selected in the first drop-down menu.
- Executor: Who will execute the action. Appears only when "Show actions" is selected in the first drop-down menu.
