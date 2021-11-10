---
title: "Tabs"
linkTitle: "Tabs"
date: 2017-01-04
description: >
  All tabs for messages.
---
# Categories submenu message form
{{< onlystaticimg src="/images/Note.png" >}}Categories submenu message form is a tab under Edit message form.

Here you can manage the categories of the message form.

### Add categories to the message form

In this panel you can manage the categories of the message form.

The left panel shows the categories that are already in the message form, the right panel shows the categories that can be added. The panels are filtered by the category group which is selected in the category group drop-down menu above the left panel.

If a category in the left panel is marked with yellow, it will appear both when the message form is opened at the department where the category was added and at any subordinate department. Categories in white are only shown when opening the form at the same department where the category was added. This is set by the state of the "Show for subdepartments" checkbox (checked or not) when adding a category to the message form.

### Drop-down menus

The entries marked with "Advanced option" are only shown when the Show advanced options button in the Edit message form page has been clicked.

- Choose category group: The fields below this drop-down menu will only contain categories belonging to the selected category group. The category groups in this drop-down menu are grouped by category group type.
- Order type (Advanced option): Shown above the category group drop-down menu at the panel Add categories to the message form.
  - Ordering by Type is the default and means that the category groups will be sorted by their category group type.
  - Ordering by Index means that you can assign a column (left, center or right) and an index to each category group in the message form. If the sorting is to be done by index, one should go through all the category groups and set the column and index. The Save button must be pressed after each change so that it will be put into effect.
- Show as: Determines how the selected category group will appear in the message form (Checkbox / Drop-down menu).

Note that a category group needs to have either some of its own categories or some categories of a sub group attached to the message form for the following options to have any effect.

- Display in the message form (Advanced option): Determines if and how the given category group should appear in the message form.
- Display in the message process page (Advanced option): Determines if and how the given category group should appear in the message process page.
- Display in the action process page (Advanced option): Determines if and how the given category group should appear in the action process page.
- Display in Inbox (Advanced option): If set to Yes, then an extra column will appear under Inbox, where the checked categories that belong to this category group will be listed for messages.
- Display in the mobile app (Advanced option): If set to No, this category group will not appear in the message form when displayed in the mobile application. This field is visible only if the mobile application is activated.
- Mandatory: If set to Yes, the user will have to select a category in this group in order for a message created with this message form to be saved. Defining category groups are a special case and will always have Yes here. Note that if a message form has more than one defining category groups, the mandatory requirement will work so that only one of the categories in all the defining category groups will have to be checked before a message can be saved.

### Buttons

- {{< onlystaticimg src="/images/Note_add.png" >}}New category: Opens the New category screen with the Category group set to the same category group as the one selected in the drop-down menu.
- {{< onlystaticimg src="/images/Note_add.png" >}}<< Add: Adds the selected categories in the right panel to this message form.
- {{< onlystaticimg src="/images/Note_delete.png" >}}Remove >>: Removes the selected categories in the left panel from this message form.
- {{< onlystaticimg src="/images/Note_go.png" >}}: Edit category dependency for the selected category. Opens the page Edit category dependency.

### Categories in this message form

Displays a table for each category group with the categories associated with the message form. The table shows the name of the category and the department it was attached from. To delete a category from a message form, one must have selected the same department in the Navigator as the department where the category was attached from. 

# Department cases
{{< onlystaticimg src="/images/Chart_organisation.png" >}}Department cases is a tab under {{< onlystaticimg src="/images/Table_edit.png" >}}Inbox.

Department cases shows cases that the department that is selected in the Navigator has to work with.

Pink cases are messages, yellow cases are actions and blue-gray cases are hearings.

### Options

- {{< onlystaticimg src="/images/Application_form_edit.png" >}}Register new message: Select a message form to register a new message. Opens the Edit message page. The message forms are displayed as individual buttons if there are up to 4 different forms. If there are more, the button {{< onlystaticimg src="/images/Application_form_add.png" >}}Register new message must be pressed first. This opens a list of all active message forms.
- All messages drop-down menu: If you select a message form, only cases originating from such a form are shown.

### Icons

- LeftArrow.gif and RightArrow.gif Change page: The arrows are used to change the page when there are more than 20 cases that can be displayed in the table.
- {{< onlystaticimg src="/images/Sort_down.png" >}} and {{< onlystaticimg src="/images/No_sort.png" >}} Sorting: The table is sorted by the column with the {{< onlystaticimg src="/images/Sort_down.png" >}}. Click on {{< onlystaticimg src="/images/No_sort.png" >}} to sort on another column.
- {{< onlystaticimg src="/images/Flag_green.png" >}}, {{< onlystaticimg src="/images/Flag_yellow.png" >}}, {{< onlystaticimg src="/images/Flag_red.png" >}} Priority: Symbolize low, medium and high priority respectively.

### Main table

When you click on a line of the main table, the selected case will open in its handling page. Messages open in the Message process page, actions open in the Action process page and hearings open in the Reply to a hearing page.

- + Extra Information and History: Hold the cursor over the + symbol to get more information about the case. Currently, only for messages and actions.
- Message form: Which message form was used to create the case.
- Registered: The date when the case was registered. For messages when they were registered, for actions when they were created.
- Due: For messages this is the handling deadline, for actions this is the execution and approval deadline.
- Description: For messages this is the text in the first text field of the message, for actions this is their name.
- Priority: {{< onlystaticimg src="/images/Flag_green.png" >}}, {{< onlystaticimg src="/images/Flag_yellow.png" >}}, {{< onlystaticimg src="/images/Flag_red.png" >}} symbolize low, medium and high priority respectively. For actions, this is the priority of the attached message to them with the highest priority.
- Status: The status of the case.
- Registered on department: The department where the case was originally registered.
- Current case handler: Depends on the type and status of the case.
  - Messages:
    - Blank: The case is registered on this department and no responsible person has been assigned to it.
    - <The name of a user>: This user is the assigned responsible person for the case.
  - Actions:
    - With status <<Under planning>>: The name of the user who has created the action and has the main responsibility for it.
    - With status <<Under execution>>: The names of the users who will execute the action.
    - With status <<Under approval>>: The name of the user who has created the action and is responsible for approving it.
  - Hearing:
    - With status <<On hearing>>: The names of the users who will participate in the hearing.
    - With status <<For approval>>: The name of the user who will approve the hearing.

### Which cases are shown in the table?

- Messages sent to a user in the department which is selected in the Navigator via Send to case handler under Message process or via the Early case process under Edit message.
- For managers:
  - Messages registered on the selected department if that has a manager, that have not been assigned to another responsible person.
  - Messages registered on a subordinate department, where there isn't a manager and have not been assigned to another responsible person. Messages registered on departments without a manager will be moved upwards in the organisation hierarchy and will appear in the Inbox on the first department above that has a manager.
- Actions under planning created by a user of the department.
- Actions under execution that will be executed by a user of the department.
- Actions for approval that will be approved by a user of the department.
- Hearings that are on hearing in which a user of the department will participate.
- Hearings that are for approval which a user of the department will approve.

Please note that messages other users have registered which were made with message forms that have a role with the "See messages" limitation, will not be shown here unless the logged in user has the same role or the system role See all messages attached to him / her or to the user type the user is logged in with. Messages which the user himself / herself has registered will be shown. 