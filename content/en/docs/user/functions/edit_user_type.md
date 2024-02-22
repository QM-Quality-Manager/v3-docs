---
title: "Edit user type"
linkTitle: "Edit user type"
date: 2017-01-04
description: >
  Function under User types for changing the data for user types.
---
One must have the system role "System role administrator" to be able to make changes to the page.

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
