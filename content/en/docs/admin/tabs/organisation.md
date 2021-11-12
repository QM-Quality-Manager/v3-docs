---
title: "Organisation"
linkTitle: "Organisation"
date: 2017-01-04
description: >
  Organisation is a tab under Admin.
---
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
