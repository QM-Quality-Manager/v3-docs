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