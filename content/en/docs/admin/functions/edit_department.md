---
title: "Edit department"
linkTitle: "Edit department"
date: 2017-01-04
description: >
  Function under Chart organisation.png Organisation for changing the data of departments.
---
### Fields

Department name: The name used for the department in the system. Will appear in the Navigator.
Subdepartment of: The department under which this department will be shown in the Navigator. This department will inherit forms, documents, and activities from the departments above it.

### Buttons

- {{< onlystaticimg src="/images/Cog_add.png" >}} Show / {{< onlystaticimg src="/images/Cog_delete.png" >}} Hide advanced options: Use to display or hide the most advanced capabilities for this page.
  - {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes made in the fields.
  - {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.
- Advanced options

These are things that come up when the Show advanced options is used. The advanced options are hidden using the button Hide advanced options.

### Roles

- Granted roles: The roles assigned to this department.
  - Roles associated with a department apply to all users of the active department. That means all employees of that department and all other users who have selected that department in the navigator.
  - Roles associated with a department are used to control the accessibility of documents, forms and activities.
- Role storage: The roles that are not assigned to this department.

### Buttons

- {{< onlystaticimg src="/images/User_add.png" >}} << Add: Adds the selected roles in the Role storage to the Granted roles.
- {{< onlystaticimg src="/images/User_delete.png" >}} Remove >>: Removes the selected roles from the Granted roles. They will then be visible again in the Role storage.
- {{< onlystaticimg src="/images/Cog_add.png" >}} Show / {{< onlystaticimg src="/images/Cog_delete.png" >}} Hide system roles: Determines if the System roles will be included in the list of roles. This button appears only if the user has the role System roles.

### Main tasks

Departments may be related to categories in a category group classified as Tasks. This is meant to visualize the department's main tasks, and has currently no system effect beyond that.

#### Buttons

- {{< onlystaticimg src="/images/Note_edit.png" >}} Configure tasks. Shows the Department main tasks and the Task storage, so that the user can add to or remove tasks from the department.
- {{< onlystaticimg src="/images/Note.png" >}} Show as list. Shows the tasks in a table view, with the Task name and Information.
- {{< onlystaticimg src="/images/Note_add.png" >}} << Add: Adds the selected tasks in the Task storage to the Department main tasks.
- {{< onlystaticimg src="/images/Note_delete.png" >}} Remove >>: Removes the selected tasks from the Department main tasks. They will then be visible again in the Task storage.
