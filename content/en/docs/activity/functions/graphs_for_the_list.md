---
title: "Graphs for the list"
linkTitle: "Graphs for the list"
date: 2017-01-04
description: >
  Function under the Activity plan for displaying the result of activities.
---
By using the List results, the result from several activities that use the same list can be displayed and compared in the same screen.

### Fields

- Headline: Shows which list is used in the activity. Click on it to display the Comments to the activity for all the activities shown in this page.
- Activities shown in these graphs: List of all the activities included in the graphs below. There will only be one graph unless you have used the List results. Click on it to display the Comments to the activity for the selected activity.

### Drop-down menus

- Department selection:
  - Distributed on this and subdepartments: A blue graph will be shown for the results from the department which is selected in the Navigator and an orange graph for the sum of the results from the departments under the selected department in the hierarchy.
  - Total for this and subdepartments: A blue graph will be shown that is the sum of the results from the selected department and its subordinate departments.
- Graph type:
  - Shown as sum: The graph shows the results as the number of answers.
  - Shown as percentage: The graph shows the result as a percentage of the total number of answers for each question. If "Distributed on this and subdepartments" is selected, there is a percentage for the selected department and a percentage for the subordinate departments.
    - For survey forms, the percentage is calculated for each alternative answer based on how many people have answered every single question.
    - For checklists the percentage is calculated based on all who have answered the list. Blank answers are also included here.
  - Shown as mean value: Shows the average values for the answers. If the alternative answers begin with a number, then this number will be used as a weight, if the first alternative does not have the value 1, the next 2 etc. Alternatives that begin with the number 0 are not counted in the average value, either in the sum or in the number of answers that it is divided into. For alternatives that begin with a number, the average value will be the calculated number. For other alternatives, it will be the text of the alternative the index of which is closest to the calculated number.

### Graph

The appearance of the graph depends on the list type.

- Checklists have one graph per question.
- Risk analysis lists have a total risk matrix over the list of questions. An additional drop-down menu "Show graph" controls if the page displays the Count or the Average view.
  - Count: The total risk matrix at the top displays the number of answers to the questions in the list that fall within each risk area. Additionally, each question in the list gets its own risk matrix that shows the distribution of the answers to that question. To the right of each risk matrix is a table that shows the distribution of answers to that question within each risk group (red, yellow, green). The Count view is shown by default when you first open this page.
  - Average: The total risk matrix at the top displays the number of questions where the average value of the answers gives the specific risk value. For each question you get two charts displaying the average risk value of all answers to the question in the selected department in the Navigator (blue) and the average risk value of all answers to the question in the departments subordinate to the selected department in the Navigator (orange).
- Survey forms have one graph per alternative answer.

#### Click functionality

- You can click on all the questions in the list. Then you will go to Comments to the activity for the selected question. This can also be done by clicking on the {{< onlystaticimg src="/images/Folder.png" >}} icon.
- If you click on the activity name or its {{< onlystaticimg src="/images/Folder.png" >}} icon you will go to the page Comments to the activity for the selected activity.
- If you click on the list name you will go to the page Comments to the activity for all activities in the chart. Usually there is just one activity in the chart, but by using the list results page you can create charts that contain the results for more than one activities at the same time.
- You can click on all the charts in the table. This opens the page Users that have answered the element for the selected question.

### Buttons

- {{< onlystaticimg src="/images/Key_add.png" >}} Show / {{< onlystaticimg src="/images/Key_delete.png" >}} Hide selection filter: Hide or show the selection filter.
  - When the selection filter is activated, you can select the questions or the alternative answers you want to filter on.
  - Only answers that satisfy all selections will be included in the graph after the button Show selected results is pressed.
  - The selection filter also affects what is displayed under Comments to the activity and Users that have answered the element.
  - It also allows for filtering the result on a role connected to the user who has answered.
  - If a role is selected in the drop-down, only the users who have the selected role attached to their user, user type or the department the answer is registered on are included in the result.
- {{< onlystaticimg src="/images/Email_edit.png" >}} Send result: Opens the Send results page to publish the depicted graph to others.
- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Show as pdf: Prints the current page to .pdf.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.
- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the current page. Make sure that the option Print background colours and images is selected in Internet Options / Advanced / Print if you are using Internet Explorer, File / Page Setup / Print Background (colours and images) in Mozilla Firefox. Otherwise, the graphs will not be printed correctly. Mozilla Firefox has in some cases problems with printing screens that span multiple pages. This may depend on the setup, but seems to be a widespread problem.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.

### Actions

You have many possibilities to create actions for an activity from this page.

- Open the Comments to the activity by clicking on a question, the title of the activity or the title of the list. This will attach the action to the comment messages that appear in this page. If there aren't any comment messages, the action will still be attached to the question or the list depending on where you clicked.
- Open the Users that have answered the element by clicking on a graph. You can do this if you want to create a action for those who have given a specific answer to a question.

Which page you will go to, affects what the action will be attached to. So what is right depends on whether you want it to be common to the whole list, attached to a single question or to an alternative answer. 
