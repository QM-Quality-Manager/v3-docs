---
title: "Functions"
linkTitle: "Functions"
date: 2017-01-04
description: >
  All functions for admin.
---
# Edit category
Edit category is a function under {{< onlystaticimg src="/images/Note.png" >}} Categories.

Here you can manage the data of categories.

### {{< onlystaticimg src="/images/Info.png" >}} What can I do here?

- The Categories tab gives me the possibility to create new or edit existing Categories. (They will later be added to a message form).
  1. Select a category group. Then 
  2. enter the name of the new category. if applicable, 
  3. predefine the cost (which will be automatically added when you select this category in a message form). 
  4. You can decide from which department (in the navigator) the category will be visible in a message form.

Attention! The same message form can have different content depending on the location in the Navigator you have selected! If you want a pop-up for this category: Write this in the information text field.

### Fields

- Show for the language: The name of a category can be set once for every language that is activated in the system. Appears only for customers who have multiple active languages.
- Category group: The category's group. The category group type of the category group determines how this category will look like in a message form. A text at the bottom of this screen describes the type of the selected group.
- Category name: The name used to represent the category. A category can have one name for every language that is activated in the system.
- Priority: Low, Medium, High. The pre-defined priority of a category. Can be overridden by the person who fills out the message form. The priority of a message is the highest priority of the checked categories unless it is overridden by the user.
- Cost: The predefined cost of a category. Can be overridden by the person who fills out the message form. The cost of a message is the sum of the costs of the checked categories, unless it is overridden by the user. Cost functionality can be removed for those who wish it.
- From department: The category is available from the selected department and its subordinate departments.
- Attached document: The document that will be activated if you click on the category in the message form.
- Information: Text field that is visible when you hold the cursor over the category in the message form.
- Risk data: Appear only for the categories belonging to a category group with the category group type Risk. Used to set different acceptance criteria for various risk categories.
  - Start yellow risk area: Overviews of this category will give a yellow risk value from (and including) this risk value.
  - Start the red risk area: Overviews of this category will give a red risk value from (and including) this risk value.
- Add the category to the selected message forms (in the left column): In this panel you can manage the message forms to which the category will appear. The left panel shows the message forms where this category has already been added, the right panel shows the message forms where this category can be added. If a message form in the left panel is marked with yellow, the category will appear both when the message form is opened at the department where the category was added and at any subordinate department. Message forms in white will contain this category only when opening the form at the same department where the category was added. This is set by the state of the "Show for subdepartments" checkbox (checked or not) when adding the category to a message form.

### Buttons

- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes made in the fields.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.
- {{< onlystaticimg src="/images/Note_add.png" >}} << Add: Adds this category to the selected message form in the right panel.
- {{< onlystaticimg src="/images/Note_delete.png" >}} Remove >>: Removes this category from the selected message form in the left panel.

# Edit department
Function under Chart organisation.png Organisation for changing the data of departments.

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

# Edit role
Function under {{< onlystaticimg src="/images/Group.png" >}} Roles.
Used for managing the name of a role and the users to whom the selected role is assigned. To manage all the roles of a specific user, it is easier to use Edit user information.

### Fields

- Show for the language: A role may have one name for each registered language in the system.
- Role name: Name of the role.
- Assigning the role to users: The left panel shows the users who have this role, the right panel shows those who do not. This component appears only after a new role has been saved at least once.

### Drop-down menu

Department selection: Determines which users will appear in the role assignment panels.

### Buttons

- {{< onlystaticimg src="/images/User_add.png" >}} << Add: Assigns this role to the selected users in the right panel.
- {{< onlystaticimg src="/images/User_delete.png" >}} Remove >>: Removes this role from the selected users in the left panel.
- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the change of the name.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Returns you to the page you came from.

# Edit user type
Function under User types for changing the data for user types. One must have the system role "System role administrator" to be able to make changes to the page.

Note 1: Be very careful when you make changes to the user type you are logged in with. It may be impossible to reverse your changes if you change the wrong access, for example if you take away your own user type's access to the Admin tab.

Note 2. All changes done to user types will take effect immediately for all users who are logged in with that user type, with the exception of tabs of the top level. The page needs to be reloaded to see changes there. This can be done for example by pressing the F5 key on your keyboard.

### Fields
- Show for language: Used to select the language of the name field. Displayed only if more than one languages are enabled.
- Name: The name of the user type. Used wherever the user type is displayed.
- Position: Used to sort lists where the user type is displayed. Position 1 shows first.
- Information: Additional information about the user type.
- Interface: Determines whether the user type should have the Complete interface (previously called Manager interface) or the Simplified interface (previously called Worker interface). The choice here determines the system roles that can be given to the user type.

### Role overview
Overview of all the roles associated with this user type. System roles appear first, followed by the user-defined roles. A logged in user has all the rights from the roles that are attached to the user type (s)he is logged in with, in addition to the rights from the roles which are directly attached to that user. System roles for tabs can only be attached to user types.

- The selected system roles give access to specific parts of the system.
- The selected user-defined roles give no direct rights to the user unless the actual roles are also attached to elements like message forms, activities or documents.
- {{< onlystaticimg src="/images/Help.png" >}}: Opens the help page for System roles where you can find a short description for - the related system role.
- Checking the box next to the Select column heading of each table title selects all roles in that table. Unchecking it when checked, deselects all roles in that table.

### Buttons
- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes done in the page.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.

# Edit role group
Function under Roles.

Used to manage the name of the role group and the roles that belong to the role group.

### Fields

- Show for the language: A role group can have a name for each registered language in the system.
- Role group name: The name of the role group.
- Assigning roles to the role group: The left panel shows the roles in this role group. The right panel shows the roles that are not in this role group.

### Functions

#### Buttons

- << Add: Adds the selected roles in the right panel into this role group.
- Remove >>: Removes the selected roles in the left panel from this role group.
- Save: Saves the name change.
- Close: Returns you to the screen where you came from.



