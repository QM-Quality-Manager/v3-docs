---
title: "Tabs"
linkTitle: "Tabs"
date: 2017-01-04
description: >
  All tabs for admin.
---
# Edit responsibility

Function under {{< onlystaticimg src="/images/User_suit.png" >}} Responsibilities.

Used for managing the data related to a responsibility.

### Fields

- Show for the language: A responsibility may have one name for each registered language in the system.
- Responsibility name: Name of the responsibility.
- Responsibility code: Code for the responsibility. Used in the responsibility matrix view of a process chart.
- Information: Information related to the responsibility.

### Buttons

- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes made in the fields. Appears only when the department which is selected in the Navigator is the department where the responsibility was created.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Returns you to the page you came from.

# Users

{{< onlystaticimg src="/images/User.png" >}} Users is a tab under {{< onlystaticimg src="/images/Admin.png" >}} Admin.

Here you can manage the company's users and user types. Active users can use the system normally. Deactivated users will not be able to log into the system, but the information they have submitted is available.

The page can also be used to send messages to all registered users.

### {{< onlystaticimg src="/images/Info.png" >}} What can I do here?
> The ADMIN-tab gives me the possibility to make changes to Users.
> Notice the "Send to"-column on the right. Email messages can be sent from here.
> If you want to see (send to) all employees in the whole organisation: Click on the drop-down menu on the left, above the table. Select "This and subordinate departments".
>If you want to see the roles the users have: Select Role overview in the second drop-down menu. That adds a new column to the table..

### Drop-down menus

- Department selection:
  - This department: Shows the users in the selected department.
  - This and subordinate departments: Shows the users in the selected department and all the users in subordinate departments. If you are on the top section in the hierarchy and select this option, all the users in the system will be displayed.
- Information type selection:
  - User information: Provides information about the users.
  - Role overview: Provides information on which roles the users have. Only roles attached to the users are shown in the table, not user types.
    - Role filter: Shown when role information is selected. Filters the list on the selected role.
      - Gives hits on both roles attached to users and roles attached to user types.
      - If a role group is selected, the same check as above is used for every role in the selected role group. Having one of the roles in the role group gives a hit.

### Buttons

- {{< onlystaticimg src="/images/Email_edit.png" >}} Create message: Opens a panel where you can create and send messages. The same panel opens if you click the Select all users checkbox at the header of the table, next to the "Send to" title, or if you click on the {{< onlystaticimg src="/images/Phone.png" >}} icon.
- {{< onlystaticimg src="/images/Email_delete.png" >}} Remove message: Closes the message panel described above.
- {{< onlystaticimg src="/images/User_add.png" >}} New user: Creates a new user and takes you to New user screen.
- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the active window.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.
- {{< onlystaticimg src="/images/Email_go.png" >}} Send message: Sends the written message to the selected users.
- {{< onlystaticimg src="/images/Icon-excel.png" >}} Export to .xlsx / {{< onlystaticimg src="/images/Page_excel.png" >}} Export to .xls : Exports the list of users to an .xlsx or an .xls file respectively. The file can be opened with Microsoft Excel (.xlsx, .xls) or OpenOffice (.xls). The first row of the file contains the column headings. This button appears only when "User information" is selected in the second drop-down menu.

### Icons

- {{< onlystaticimg src="/images/User_edit.png" >}} Takes you to the Edit user information screen to edit the selected user.
- Turnarrow.gif Activates / Deactivates the selected user, depending on whether you are under the tab Deactivated users or Active users respectively. When you deactivate a user, you get the option to transfer any open cases that are attached to the user. You also get the option to transfer or delete completely the rules that are attached to the user you just deactivated. The Undo button will reactivate the user if clicked, but it will not transfer the cases and / or rules back to the original user. It is possible to select different recipients for the various case types, with the limitation that they should all belong to the same department. Please note that you can transfer all the cases to users who can handle cases from the department which is selected in the Navigator, which usually is the department of the original user (or a department above it in the hierarchy, if the view This and subordinate departments is selected above the table). If you need to transfer the cases to users from another department, you can do that by first changing the department of the original user to the department of the users you want to transfer the cases to, and then go through the deactivation process.
- {{< onlystaticimg src="/images/User_delete.png" >}} Deletes the selected user. This icon only comes up if the tab Deactivated users is selected and this user has not answered any forms.
- {{< onlystaticimg src="/images/Arrowopen.gif" >}} Indicates that the table is sorted by this column.
- {{< onlystaticimg src="/images/Arrowclosed.gif" >}} Sort the table by this column.
- {{< onlystaticimg src="/images/Phone.png" >}}: Opens the field for creating and sending messages customized for sending a mobile login per SMS. This icon appears only if the mobile version is enabled for a customer and the user has a registered phone number. 

  When you move the cursor over the data of some of table columns, you may notice that it changes form. In some browsers it will look like this: {{< onlystaticimg src="/images/Pencil.png" >}}, while in others it will turn into the hand icon. That means that the table cell at that point is editable. If you click on it, you can edit the text directly from this page, without having to go to the Edit user information page first. Then you see the following icons:

- {{< onlystaticimg src="/images/Accept.png" >}}: Saves the new text. You can also save the new text by simply pressing Enter on your keyboard.
- {{< onlystaticimg src="/images/Cancel.png" >}}: Cancels the change. The field takes its previous value.
- {{< onlystaticimg src="/images/Arrow_refresh.png" >}}: Undo. Appears after you have made and saved a change. The field takes its previously stored value.
  - If the Undo button gets pressed after a user has been deactivated, that user will become active. Any cases or rules that were transferred or deleted when the user was deactivated will not be restored. They will remain transferred or deleted.

### Tabs

- Active users: Shows the active users of the department which is selected in the Navigator.
- Deactivated users: Shows the deactivated users of the department which is selected in the Navigator.

### Message fields

- Message type: Used to determine what kind of message will be sent out.
  - New password: The sent message contains a link to a page where the user is given his / her username and he / she can enter their own password. This is the same function as the "Forgotten password" on the login page. This is intended for distributing usernames and passwords when introducing the system.
  - Mobile login: The sent message contains a link that logs the user right into the mobile version. This option only appears when the mobile version is enabled.
  - Information: The sent message does not contain any particular link. This function is intended to be used for general notifications or messages.
- Send message as: Used to determine whether the message should be sent as email or SMS. SMS is only available if activated.
- Subject: The subject field in the email.
- Text field: Here you can write the message.
- {{< onlystaticimg src="/images/Email_go.png" >}} Send message: Sends the written message to the users that are selected in the Send to column of the table.

# Documents
{{< onlystaticimg src="/images/Link.png" >}} Documents is a tab under Admin.png Admin.
From here you can manage the company's documents, document groups and document tabs.

### {{< onlystaticimg src="/images/Info.png" >}} What can I do here?

- As a super user / manager I can add documents (laws, procedures, etc.): Click on the button New document at the bottom of the page.
- I can create new Document tabs and new Document groups.

### Tabs

- Documents: Displays documents. Submenus:
  - Published documents. These are shown under Info.
  - Unpublished documents. These are not shown under Info.
  - Deactivated published documents. These are not shown under Info.
  - Deactivated unpublished documents. These are not shown under Info.
- Document groups: Displays document groups. Submenus:
  - Document groups. These are shown under Info.
  - Deactivated document groups. These are not shown under Info.
- Document tabs: Displays document tabs. Submenus:
  - Document tabs. These are shown under Info.
  - Deactivated document tabs. These are not shown under Info.

# Forms
{{< onlystaticimg src="/images/Page.png" >}} Forms is a tab under {{< onlystaticimg src="/images/Admin.png" >}} Admin.
From here, one can manage the company's checklists, risk analysis lists, survey forms and message forms.

### Tabs

- Checklists: Displays an overview of all available checklists.
- Risk analysis lists: Displays an overview of all available risk analysis lists.
- Message forms: Displays an overview of all available message forms.
- Survey forms: Displays an overview of all available survey forms.  

# Organisation
{{< onlystaticimg src="/images/Chart_organisation.png" >}} Organisation is a tab under {{< onlystaticimg src="/images/Admin.png" >}} Admin.

Here you can manage the company's departments. Active departments appear in the Navigator and users of these may use the system normally. Deactivated departments do not appear in the Navigator, users of these will not be able to log into the system and no other information that is saved for these will be visible in reports and overviews. The exception are messages and actions that are forwarded to other departments. Answers to activities with lists that are created on a department above the deactivated department and their comment messages will also be available via reports in the Activity plan, but it will not be possible to modify or create new answers in a deactivated department.

### {{< onlystaticimg src="/images/Info.png" >}} What can I do here?

>ADMIN-tab / Organisation enables me to make changes in the organisation.
>My selection in the Navigator + one click on the "New department" button at the bottom of the page, give me the sub departments of the department which is selected in the navigator.
>The "Edit"-column on the right side of the table has two main functions: The black arrow deactivates, and the yellow icon gives editing capabilities.

### Buttons

- {{< onlystaticimg src="/images/Chart_organisation_add.png" >}} New department: Creates a new department and takes you to the New department screen.
- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the active window.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.

### Icons

- {{< onlystaticimg src="/images/Folder.png" >}} Takes you to the Edit department screen to edit the selected department.
- {{< onlystaticimg src="/images/Turnarrow.gif" >}} Activates / Deactivates the selected department, depending on whether you are under Deactivated departments or Active departments respectively.
- {{< onlystaticimg src="/images/Chart_organisation_delete.png" >}} Deletes the selected department. This icon only comes up if the tab Deactivated departments is selected and the selected department does not contain any users, answered forms or form definitions.

### Tabs

- Active departments: Shows the active subordinate departments to the department that is selected in the Navigator.
- Deactivated departments: Shows the deactivated subordinate departments to the department that is selected in the Navigator.

### LDAP / AD Module

Only active if the company has activated the module for LDAP / AD integration and the logged in user has the system role LDAP integration responsible.

In this page you can see the options for making the LDAP / AD associations to the subordinate departments.

- {{< onlystaticimg src="/images/Database_gear.png" >}} LDAP / AD: Opens the LDAP / AD interface for the associations for this department.
- {{< onlystaticimg src="/images/Add.png" >}} Add LDAP / AD association. Opens the option to enter data for a new association. Appears after the {{< onlystaticimg src="/images/Database_gear.png" >}} icon is pressed.
- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the new or modified LDAP association.
- {{< onlystaticimg src="/images/Delete.png" >}} Delete: Deletes the selected LDAP / AD association.

# Rules
{{< onlystaticimg src="/images/Wrench.png" >}} Rules is a tab under {{< onlystaticimg src="/images/Admin.png" >}} Admin.

Here you can manage various rules. Rules are used for setting up criteria, that when satisfied, a predefined "reaction" happens. Rule types ("reactions") can only be defined by QmPlus AS.

At the moment, such criteria can be specific users, forms, categories, departments and notification types.

- Example 1: User A is an additional case handler for the HES-form and the Information security form, from the departments Technical, Culture and Administration.
- Example 2: Users B and C will receive an email whenever a message is registered using the HES-form, has the category Fire safety selected and has been registered on the Technical department.

In the current version, rules can only be created or modified by users with a user type that has the system role content administrator or rule administrator.

### Rule types (Reactions)

In the current version, there are 8 different predefined Rule types:

#### Additional case handlers

Here you can manage who should appear as an additional case handler when the "Choose case handler" function is used in the Message process page.

{{< onlystaticimg src="/images/ChooseCaseHandler.png" >}}

Additional case handlers are added to the drop-down menu with the potential recipients when the option "Send to case handler" is selected as action on the Message process page (see image above).

The drop-down menu automatically contains all users with the system role Default possible message receiver. In the standard version user type manager and case handler from the following places:

- The department which is selected in the navigator.
- The department directly above the department which is selected in the navigator.
- All departments directly beneath the department which is selected in the navigator.

This is used when users should be able to send messages without following the traditional hierarchy structure, for example across the organisation or directly to the responsible person in an entirely different part of the organisation.

If the option for Automatic early case processing is activated, Additional case handlers will also be included in the drop-down menu for selecting the case handler in the Register new message page.

The list shows all users who have been registered as additional case handlers in the whole company. In the column "From department" of the table you can see from which department a case handler was set.

Do not set additional case handlers unless you are absolutely sure of what you are doing. If in doubt, please contact QmPlus AS for clarifications.

#### Early case handlers

Here you can set up users who should be the default case handlers for one or more message forms.

ATTENTION: The rules for Early case handlers are intended to handle exceptions. If you want all messages to be sent to the nearest manager as a general rule, order the option for Automatic early case processing.

{{< onlystaticimg src="/images/EarlyCaseHandlers.png" >}}

The field that shows that a message form is set up with "Early case handling" (and Irene Bauer as default case handler in the example above) is titled "Send to case handler".


In the "From department" drop-down menu, select from which department (inclusive) the default case handler function will apply. If several users are set as the default case handler on various departments for the same message form, the user whose department is the closest to the department which was selected in the navigator when the message was registered will be preselected in the "From department" drop-down menu in the message form. If priority or categories are added to this rule (based on the system setting EARLYCASEPROCESS) then the available case handlers will be updated after every change in the Edit message page during message registration.

A common way to use this is when you have a message form that for example should always go to a specified recipient, no matter where in the organisation the message is registered.

Please note that that when a message gets a case handler this way, when it is registered it will get the status "Sent to case handler" instead of "New message".

For forms that have Early case handler rules defined, the Additional case handlers will never be included in the related drop-down of the Register new message page. If the option for Automatic early case processing is turned on, the defined rules with the early case handlers will override the automatic ones. If you do not want to override them but add them, use the Additional case handler rules as described in the previous section.

#### Action approvers

In principle, all users with a user type that contains the system role Process message (Manager or Case handler in the standard version) can handle all messages within their area of responsibility. To restrict who can close certain messages, you can set up Rules for that. These rules affect the following actions in the Message process page:

- Reject
- Close the case.

In the Action process page, rules can restrict the action:

- Approve action.

#### Informed upon message registration

When a new message is registered, users who satisfy the criteria set up in one of these rules will receive a notification for the new message. The comment column can be used for personalising the notification text. The notification may be sent by email, SMS or both. The default type is Email. The other two options (Sms, Email and sms) will only be available for customers who have the SMS functionality enabled. The email notification will have the default subject "You have a new message in Qm+ from..." unless a special setting has been added from the Email settings page for the message form that is specified in this rule.

#### Informed upon message closure

When a message is closed, users who satisfy the criteria set up in one of these rules will receive a notification. The comment column can be used for personalising the notification text. The notification may be sent by email, SMS or both. The default type is Email. The other two options (Sms, Email and sms) will only be available for customers who have the SMS functionality enabled. The email notification will have the default subject "Message closed in Qm+..." unless a special setting has been added from the Email settings page for the message form that is specified in this rule. A message is defined as closed when it only relates to approved actions or it is rejected.

#### Informed upon threshold violation

- When a threshold value has been exceeded, a warning email is sent to the users specified in the rule.
- The warning emails are sent when running the night job, in the same way as warnings for passed due date.
- One can choose between Periodic warning and Daily warning for various time frames.
  - A Periodic warning sends an email once, after the threshold is breached.
    - If a rule is modified and more users get added as recipients of the warning, after the periodic warning has been sent or if the sending of the email to one of the specified users fails, then the warning will be sent again at the next opportunity.
  - Daily warnings are sent for as long as the threshold is exceeded for the selected time frame.
- The threshold value is referring only to the number of registered messages.

#### Configuration for dynamic graphs

Used for defining which values will be used on the Y-axis and X-axis for the dynamic graphs in the Reports page. The dynamic graphs are shown when you select the box Dynamic graphs, see image below.

{{< onlystaticimg src="/images/DynamicGraphs.png" >}}

If no rules have been defined here, there will be no Dynamic graphs on the Reports page. Rules of this type are made one row at a time. The save symbol becomes visible once you add a new rule or you change an existing one.

#### Configuration for calculation reports

This rule type can be used to define a calculation that can be displayed under the report type Calculation reports in the Reports page. Please contact us if there is a need for such calculations.

- Example: Calculation of the H-value = (number of personal injuries * 1000000) / Total number of hours spent.

In order to use the calculation above, messages with the category for personal injuries must be registered in Qm+. Periodically, the total number of hours must be registered. In order for the results to make sense, the periodic registration of hours must also match with the period used to display the calculation reports.

#### Filter rules

These are rules that can be used as part of a rule for calculation reports to create the restriction expressions.

- Example: You wish to include only one category from messages with a specific message form with a given priority and also the categories from another form with another priority. Then you can create two different filters here and then combine them in their respective categories in the calculation rule.

### Columns

- Name: The name of the user to whom this rule applies.
  - For some rule types, you can select between any of the users of the company, regardless of user type. For others, the user type must have certain access rights to appear in the user list. For example, in order to appear in the list of available "Early case handlers", a user needs to have the right to handle a message.
  - Without a user name the rule will have no effect anywhere in the system. Mandatory field for all Rule types.
  - You can have multiple user names in one rule, which would then apply to all the selected users.
  - The drop-down at the column heading is a filter for the table below, showing only the users that already have a rule for the selected Rule type.
- From department: The department from which this rule will apply.
  - If no department is set, the rule will apply to all messages regardless of the department on which they were registered.
  - You can have multiple departments in one rule, which would then apply from all of them.
  - The rule will apply from the department(s) you have selected and down. You can select between all the departments starting from the one you have logged in and down.
  - Mandatory field for the Early Case Handler rule type, optional field for the rest.
- Message forms: The message form for which this rule will apply.
  - You can have multiple forms in one rule, which would then apply to all of them.
  - If no message form is set, the rule will apply to all message forms. Otherwise, the rule will apply only to messages registered using the specified message form(s).
  - You can select between the forms which are available at the department which is selected in the Navigator.
- Categories: The category for which this rule will apply.
  - You can have multiple categories from various category groups in one rule, which would then apply to all of them.
  - If no category is set, the rule will apply to all messages. Otherwise, the rule will apply only to messages that have the specified category selected. Optional field for the Rule types it applies to.
  - When you click the {{< onlystaticimg src="/images/Add.png" >}} you will see two drop-downs, the first containing category groups and the second the categories of the group which is selected in the first one.
  - You can select between the category groups and categories which are available at the department which is selected in the Navigator.
  - Does not apply to the Rule type "Early case handlers".
- Priority: The message priority for which this rule will apply.
  - Does not apply to the Rule type "Early case handlers".
  - Optional field for the other Rule types. If no priority is selected, the rule will apply to all messages regardless of priority.
  - You can have multiple priority levels in one rule, which would then apply to all of them.
- Comment: A comment for this rule.
  - Does not appear for the Rule type "Informed upon message registration".
  - Optional field for the other Rule types.
- Send as: Determines how the automatic notification will be sent.
  - Applies only to the Rule type "Informed upon message registration".
  - Possible values are Email, SMS, Email and SMS.
  - Shows only when the SMS option is available for the customer, otherwise "Email" will be used.
- Text for SMS / Email warning: It is the personalised text that will be added to the notification sent to the user(s) defined in the Name column when a new message is registered that satisfies the criteria set in the rest of the columns.
  - Applies only to the Rule type "Informed upon message registration".
- Time frame: Set a time frame limit.
  - Applies only to the Rule "Informed upon threshold violation". Used only when the Threshold value is also set.
  - Periodic warning: Emails are sent out the first time the threshold value is exceeded.
  - Daily warning. Emails are sent out every day after the threshold value is exceeded.
- Threshold value: The number of messages which meet the requirements of the rule that need to be registered in order for the warning email to be sent.
  - Applies only to the Rule "Informed upon threshold violation". Used only when the Time frame is also set.
- Edit: If the user has the right to create and edit rules, the icon {{< onlystaticimg src="/images/Delete.png" >}} will be shown there. It can be used to delete the rule.

### Buttons

- {{< onlystaticimg src="/images/Wrench.png" >}} New rule: Creates a new rule without any criteria set. This shows as an empty highlighted yellow row in the table. Go to that row and click on the {{< onlystaticimg src="/images/Add.png" >}} of one or more table columns and add criteria of the type that you wish. The button shows only for users with user type Manager on the top department or users who have the system role Content administrator.

### Icons

When you move the cursor over the data of some of table columns, you may notice that it changes form. In some browsers it will look like this: {{< onlystaticimg src="/images/Pencil.png" >}}, while in others it will turn into the hand icon. That means that the table cell at that point is editable. If you click on it, you can edit the text directly in this page. Then you see the following icons (Note: The icons described below are only visible for users with user type Manager on the top department or users who have the system role Content administrator):

- {{< onlystaticimg src="/images/Accept.png" >}} Save: Saves the change.
- {{< onlystaticimg src="/images/Cancel.png" >}} Cancel: Cancels the change. The field takes its previous value.
- {{< onlystaticimg src="/images/Delete.png" >}} Delete: Deletes this criterion from the rule or deletes the whole rule (if the icon is in the Edit column).
- {{< onlystaticimg src="/images/Arrow_refresh.png" >}} Undo: Appears after you have made and saved a change. The field takes its previous saved value.
- {{< onlystaticimg src="/images/Add.png" >}} Add: Add a new criterion of this type (see column header) to this rule.

# Categories
{{< onlystaticimg src="/images/Note.png" >}} Categories is a tab under {{< onlystaticimg src="/images/Admin.png" >}} Admin.

Here you can manage the company's categories and category groups.

### {{< onlystaticimg src="/images/Info.png" >}} What can I do here?
>The ADMIN-tab gives me the possibility to make changes in Categories. (These can later be added to the message form: Click Forms.)
>Here you can create a new Category group. Click on the tab "Active category groups".
>
>The next page gives you the possibility to select if the group will be multi choice, single choice (radio button), number or defining category.
>If you select the tab "Active categories" you can select between the category groups in the drop-down menu on the left above the table. Then click on the "New category" button.

### Drop-down menus

- Category group selection: Lists all active category groups in the system. All categories in the selected group created from the selected department in the Navigator will be shown in the table.

### Buttons

- {{< onlystaticimg src="/images/Note_add.png" >}} New category: Creates a new category and takes you to the Edit category screen.

### Icons

- {{< onlystaticimg src="/images/Note_edit.png" >}} Takes you to the Edit category page to change the selected category.
- {{< onlystaticimg src="/images/Turnarrow.gif" >}} Activates / Deactivates the selected category, depending on whether you are under the tab Deactivated categories or Active categories respectively.
- {{< onlystaticimg src="/images/Note_delete.png" >}} Delete: Deletes the selected category. Visible only under the Deactivated categories for categories that are not in use.

### Tabs

- Active categories: Displays the active categories created in the department which is selected in the Navigator.
- Deactivated categories: Displays the deactivated categories created in the department which is selected in the Navigator.
- Active category groups: Displays the active category groups which are accessible from the department that is selected in the Navigator.
- Deactivated category groups: Displays the disabled category groups which are accessible from the department that is selected in the Navigator.

# Category groups
Active category groups and Deactivated category groups are tabs under {{< onlystaticimg src="/images/Note.png" >}} Categories.

Here you can manage the company's category groups.

### Buttons

- {{< onlystaticimg src="/images/Package_add.png" >}} New category group: Creates a new category group and takes you to the Edit category group page.

### Icons

- {{< onlystaticimg src="/images/Folder.png" >}} Takes you to the Edit category group page to change the category group.
- {{< onlystaticimg src="/images/Turnarrow.gif" >}} Activate / Deactivate the category group, depending on whether you are under Deactivated category groups or Active category groups respectively.

# Edit category group
Edit category group is a function under Category groups.

Here you can manage the data of category groups.

### Fields

- Show for the language: The name of a category group can be set once for every language that is activated in the system. Appears only for customers who have multiple active languages.
- Category group type: The category group type of the category group. Determines how the categories in this category group will look like in a message form. A text further below in this screen describes the selected category group type.
- Category name: The name used to represent the category group. A category group can have one name for every language that is activated in the system.
- From department: The category group is available from the selected department and from its subordinate departments.
- Information: Text that appears when you hold the cursor over the category group name in a message form.

### Advanced options

- Class: Default or Tasks. Categories of groups that are classified as Tasks represent a department's main tasks and are shown in the Edit department page. This will later be expanded with positions and competence.
- Subgroup of: If the category group is a subgroup of another category group.
- Shown for subdepartments?: Set to no if this category group will only be available from the department which is selected above.

### Buttons

- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes made in the fields.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.
- {{< onlystaticimg src="/images/Cog_add.png" >}} Show / {{< onlystaticimg src="/images/Cog_delete.png" >}} Hide advanced options: Displays or hides the advanced options.

# Responsibilities
{{< onlystaticimg src="/images/User_suit.png" >}} Responsibilities is a tab under {{< onlystaticimg src="/images/Admin.png" >}} Admin.

Here you can manage the company's responsibilities. Responsibilities may be used in documents of type Process chart. The use of responsibilities is a prerequisite in order for a process chart to be displayed as a responsibility matrix. Responsibilities are edited in the Edit responsibility page. By default, the following responsibilities are defined: Approver (A), Executor (E), Participant (P) and Informed (I).

### Buttons

- {{< onlystaticimg src="/images/Group_add.png" >}} New responsibility: Opens the Edit responsibility page to create a new responsibility.

### Icons

- {{< onlystaticimg src="/images/Group_edit.png" >}}: Opens the Edit responsibility page to change a responsibility.
- {{< onlystaticimg src="/images/Turnarrow.gif" >}}: Deactivates or activates the responsibility depending on whether you are under Active responsibilities or Deactivated responsibilities respectively. Appears only when the department which is selected in the Navigator is the department where the responsibility was created.
- {{< onlystaticimg src="/images/Group_delete.png" >}}: Deletes the responsibility. Only visible for deactivated responsibilities. Appears only when the department which is selected in the Navigator is the department where the responsibility was created.

### Tabs

- Active responsibilities: The active responsibilities are shown in the table.
- Deactivated responsibilities: The deactivated responsibilities are shown in the table.

# Roles
{{< onlystaticimg src="/images/Group.png" >}} Roles is a tab under {{< onlystaticimg src="/images/Admin.png" >}} Admin.

Here you can manage the company's roles and role groups.

### Buttons

- {{< onlystaticimg src="/images/Group_add.png" >}} New role / {{< onlystaticimg src="/images/Group_add.png" >}} New role group: Opens the Edit role / Edit role group page to create a new role / role group.

### Icons

- {{< onlystaticimg src="/images/Group_edit.png" >}}: Opens the Edit role / Edit role group page to change a role / role group.
- {{< onlystaticimg src="/images/Turnarrow.gif" >}}: Deactivates or activates the role / role group depending on whether you are under Active roles / role groups or Deactivated roles / role groups respectively.
- {{< onlystaticimg src="/images/Group_delete.png" >}}: Deletes the role / role group. Only visible for deactivated roles / role groups.

### Tabs

- Active roles: The active roles are shown in the table.
- Deactivated roles: The deactivated roles are shown in the table.
- Active role groups: The active role groups are shown in the table.
- Deactivated role groups: The deactivated role groups are shown in the table.


