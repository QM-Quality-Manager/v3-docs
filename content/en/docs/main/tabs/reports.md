---
title: "Reports"
linkTitle: "Reports"
date: 2017-01-04
description: >
  Reports (previously Graphs) is a tab on the Main Page.
---
Used to get a graphical overview of the activity in the system. Drop-down menus and various search criteria control what kind of graph you will get. By clicking on any of the graphs, the underlying report opens.

### {{< onlystaticimg src="/images/Info.png" >}} What can I do here?

- I can see the results in all or in parts of the organisation with one keystroke: Select a department in the Navigator.
- I can choose what kind of graphs will be shown by clicking on the checkboxes above the graphs, for example "Distribution over time",
- or I can click on a colour in the graph and see the results in a table overview,
- or I can select "Per department overview table" to retrieve comparisons between time periods. This can be copied into an Excell spreadsheet.

### Buttons

- {{< onlystaticimg src="/images/Printer.png" >}}Printer.png Print: Prints the current screen.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.
- {{< onlystaticimg src="/images/Report_edit.png" >}} Write report: Opens the page New document page where you can write a document that contains all the graphs that were showing when you clicked on this button. Only users that have the access right to create documents get this button. Charts in .pdf printouts and in the html version of the report document now have by default a width of 600 pixels, which makes them more readable.

### Tabs

The tabs Messages/NC, Log, Risk and Comments give the same graph possibilities for the various types of messages. They can also be used to reset the search criteria if you have performed a search. If you are in search mode, the tab Search is selected and the selected search criteria are shown in a separate table.

- Messages/NC: Charts for messages.
- Orders: Charts for messages. Only shown if the option for order messages is activated.
- Log: Charts for messages. Only shown if the option for log messages is activated.
- Risk: Charts for messages. Only shown if the option for risk messages is activated.
- Comments: Charts for messages.
- Action reports: Action matrix and reports for time registration on actions.
- Users: Provides an overview of logins and document usage.
- Search: Search for messages and display the results through charts.

### Drop-down menus

#### Report types

Select the report type.

#### Message / NC reports

##### Standard report graph

- Shows an overview of the number of registrations, status, used message forms, priority, distribution over time and categories, depending on the sub-reports that are checked.
- Click on any chart to get a list of the messages that contributed to the selected part of the chart.

##### Standard report table

Periodic report that shows a table overview of the most important data for messages summed up for the department which is selected in the Navigator. The data is listed below each other distributed in time periods. The periods are created automatically based on the time frame you have selected for the report. This is the same as in the chart "Distribution over time". At the moment there is no possibility to directly export the data or click on them (drill down functionality) in this report. Such functionality is scheduled for a later version of Qm+.

- Use the drop-down menu for the Period type if you want a different periodisation from the automatic one. If the time frame you are searching for does not cover an entire period, the last period and the total period (first column in the table) will show a time frame that spans an entire period. However, there will be no data in the report outside the time frame you have chosen.

##### Risk report

Shows a risk matrix for all messages in the current selection that have any category in a category group of the type Risk with risk value > 0.

##### Calculation reports

#### Action reports

Time per action and Timesheet for actions appear only if the option for Time registration for actions is activated. In all three reports, you can click on the name or number of the action to open it.

##### Action matrix

- Report that shows the status for all open actions.
- The colour codes for the status are shown above the table.
- Click on the name of an action to open it.
- Used together with the option for start time for actions, this report can be used to give an overview of the planned actions.
- The overview starts 3 days before today's date and includes the next 26 days.
- The transition from today's date to the next day is marked with a vertical black line.
- The matrix is sorted by the action's start date, if this is set. If not, the date the action was registered is used instead.

##### Time per action

- Report that shows how much time has been registered on all actions in the selected period.
- Actions without any registered time are not included in the report.
- The report includes actions registered on or below the department currently selected in the navigator.
- Shows per user and total.
- The actions are ordered by action number.
- This report is only available when the option for time registration on actions is activated.

##### Action time sheet

- Report that shows how much time, in the selected period, has been registered per action per user per day.
- Sums per day per user and total for all users.
- This report is only available when the option for time registration on actions is activated.

#### Mixed reports

##### Process time report

Periodic report that displays information for the registered and processed messages and actions. This report takes into account only the selected time period and the selected message type. The figures for average time take into account only messages that have obtained the relevant status. The last periods in the report will therefore usually have lower processing time than the first ones, as the last ones will usually have several open cases that will not be included in the calculation.

- Messages registered on... Displays the number of messages registered on the department(s).
- Messages processed at... Displays the number of messages processed (rejected or action created) in the selected period, regardless of where and when the message was registered.
- Messages closed at... Displays the number of messages closed (rejected or action approved) at the department(s), regardless of where the message was registered.
- Messages rejected at... Displays the number of messages rejected at the department(s), regardless of where the message was registered.
- Actions created at... Displays the number of actions created at the department(s).
- Actions approved at... Displays the number of actions approved at the department(s).
- Processed messages registered on... Displays the number of messages registered on the department(s) that have been processed. Used to calculate the Average processing time.
- Closed messages registered on... Displays the number of messages registered on the department(s) that have been closed. Used to calculate the Average closing time.
- Rejected messages registered on... Displays the number of messages registered on the department(s) that have been rejected.
- Average processing time in days for messages registered on... Time spent from registration for all fully processed messages registered on the department(s) / Number of fully processed messages registered on the department(s).
- Average processing time in days for messages processed on... Time spent from registration for all fully processed messages processed on the department(s) / Number of fully processed messages processed on the department(s).
- Average closing time in days for messages registered on... Time spent from registration for all closed messages registered on the department(s) / Number of closed messages registered on the department(s).
- Average closing time in days for messages processed on... Time spent from registration for all closed messages processed on the department(s) / Number of closed messages processed on the department(s).

Use the drop-down menu for Period Type if you want a different periodisation than the automatic. If the time frame you are searching for does not cover an entire period, the last period and the total period (first column in the table) will show a time frame that spans an entire period. However, there will not be any data in the report from outside the time frame you have selected.

> Note:

- Messages that are not yet closed may be part of the overview for process time withouth being included in the report for close time. Therefore, it is possible to have longer processing time than close time.
- To calculate the processing time we use only the latest department the message was sent to - the current department.

#### Message form

If a particular message form is selected here, only messages registered with the selected message form will be included in the report.

#### Category groups

If a category group is selected here, only messages with check marks in the selected category group will be included in the report.

### Graph types

A series of checkboxes that activate or deactivate the given graph type. Overview by forms, status and priority are activated as standard. This can be changed on a per customer basis.

- Overview by departments: Displays an overview of the messages that are registered on the department which is selected in the Navigator and the messages that are registered on its subordinate departments.
- Overview by forms: Displays the message forms that have been in use. This graph is hidden if a message form is selected in the drop-down menu above.
- Overview by status: Displays the status of the messages.
- Overview by priority: Displays the priority of the messages.
- Distribution over time: Displays when the messages were registered. The time axis changes according to the length of the selected period. Possible scales: days, weeks, months and years.
- Overview by categories: Displays one graph for each category group with which a registration was done.
- Overview by users: Does not appear in the standard version. Shows how many messages the users of the selected department have registered. Users registered on another department who have done registrations on the selected department are also shown. Messages reported as anonymous are not included in these graphs.
- Dynamic graphs: Any graph defined in Admin / Rules / Configuration for dynamic graphs is shown here. These are graphs where the local system administrator can choose which values come on the Y-axis and the X-axis.

### The graphs

Each graph has a series of checkboxes that control what it contains and what kind of graph will show.

- Swap axis: Swaps the data shown on the x and y axes in the graph.
- Show total: Appears only for category graphs.
  - Checked: The first segment of the bar contains the summarized totals for the following segments of the same bar. The subsequent segments of the bar show the sum from the respective department (see graph legend) and from its subordinate departments. Used if, for example, you want to get all the messages in the whole company for which a given category is checked.
  - Not checked: The first segment of the bar shows only the registrations from the department which is selected in the Navigator. The subsequent segments of the bar show also here the sum from the respective department (see graph legend) and from its subordinate departments.
- Message count: The graph that shows the number of messages appears. This is by default preselected for all graphs, except for the category graphs for the category groups of the type Number.
- Sum: Appears only for category groups of the type Number. It is by default preselected for them. This type of category groups is answered with a number instead of a tick. This graph shows the sum of these numbers for all messages included in the report.
- Percent chart: Shows the percentage distribution.
  - For graphs other than the category graphs this means that the message count graph is scaled to 100.
  - For category graphs it displays the percentage distribution of messages for each department per category within each category group. Each department sums up to 100% in this graph, so some bars could exceed 100. In this case, the graphs might be more readable if swapped. Use the Swap axis for this.
- Cost chart: Displays the sum of the cost field in the messages that the graph contains. When you click on a cost chart you will only see cases with cost > 0.
