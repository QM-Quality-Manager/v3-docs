---
title: "Edit user"
linkTitle: "Edit user"
date: 2017-01-04
description: >
  Function under Users for changing the data of users.
---
### Fields

- User name: Used by the user for logging into the system. Distinguishes between uppercase and lowercase letters. Must be unique for each customer.
- Department / Type. This field defines the users access to the system.
  - Department: The department to which the user belongs.
    - If the department association is marked with {{< onlystaticimg src="/images/Server_connect.png" >}}, the entry may not be deleted. But it is allowed to alter the department and user type. Only relevant for customers with AD / LDAP integration.
  - Type: The user's user type.
  - Substitute: The substitute function gives the option for a defined user to log into the system with the same access rights as the access one is substituting for. One substitute may be defined for each access a user has. For each access a user has:
    - If a substitute is defined, the name of the substitute is shown. Click on the name to edit or remove the substitute.
    - If no substitute is defined, a button to set the substitute is shown.
- Password: Used by the user for logging into the system. Distinguishes between uppercase and lowercase letters.
- Repeat password: Must be identical with the password field in order for the user's data to be saved.
- First name: The user's first name.
- Middle name: The user's middle name.
- Surname: The user's last name.
- Email address: The user's email address. Some functionality of the system is linked to the user's email address. It is therefore preferred that each user has a unique email address.
- Language: Selection of the display language for the user. Available languages in the system are: Norwegian (bokmål), Norwegian (nynorsk), English, Swedish and Danish (not translated framework for Danish). The available languages for each customer will vary.
- Mobile number: Can be used for receiving SMS from the system, if this functionality is activated.
- Comment: Free text field for additional information about the user.

### Buttons

- {{< onlystaticimg src="/images/Add.png" >}} Add department: Adds a department to the user. It is possible to assign multiple departments to each user. For each department the user belongs to, (s)he can have only one corresponding user type. Users who belong to multiple departments select the department they wish to log into on the login page.
- {{< onlystaticimg src="/images/Delete.png" >}} Remove department: Deletes the selected department from the user. Appears for users who belong to multiple departments.
- {{< onlystaticimg src="/images/User_go.png" >}} Set substitute:
- {{< onlystaticimg src="/images/Accept.png" >}} Save: Saves the selected substitute user.
- {{< onlystaticimg src="/images/Cancel.png" >}} Cancel
- {{< onlystaticimg src="/images/Delete.png" >}} Delete
- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes made in the fields.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.
- {{< onlystaticimg src="/images/Cog_add.png" >}} Show / {{< onlystaticimg src="/images/Cog_delete.png" >}} Hide advanced options: Shows or hides the advanced options (see below).

### Advanced options

These are things that come up when the Show advanced options button is used. The advanced options are hidden by using the button Hide advanced options.

### Fields

- Granted roles: The roles assigned to this user.
- Role storage: The roles not assigned to this user.

### Buttons

- << Add: Adds the selected roles in the Role storage to the Granted roles.
- Remove >>: Removes the selected roles from the Granted roles. They will then be visible again in the Role storage.
- {{< onlystaticimg src="/images/Cog_add.png" >}} Show / {{< onlystaticimg src="/images/Cog_delete.png" >}} Hide system roles: Determines if the system roles will be included in the list of roles. This button appears only if the user has the role System roles.
