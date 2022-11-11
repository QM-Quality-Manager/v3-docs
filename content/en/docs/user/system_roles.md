---
title: "System roles"
linkTitle: "System roles"
date: 2017-01-04
description: >
  System roles are roles that provide specific additional rights defined in the system. New system roles can only be defined by QmPlus AS.
---
The roles are marked with (M, C, R, E) if in the standard version, the one set up from QmPlus AS, they are attached to the user types Manager, Case handler, Reviewer and Employee respectively. Note that from version 3.60 a user having the "System role administrator" role can change the name and the rights of user types.

### Roles that control the access to tabs

All these roles give to the user access to the tab with the same name.

#### Roles that control the access to the tabs of the complete interface

- Home:
- Info: (M, C, R)
- Reports: (M, C, R)
- Admin: (M)
- Preferences: (C, R)
- Activity plan: (M, C, R)
- Inbox:
- Risk: (M)
- Archive: (M, C, R)
- Help: (M, C, R)

#### Roles that control the access to the tabs under Admin

- Admin_Organisation: (M)
- Admin_Users: (M)
- Admin_Categories: (M)
- Admin_Forms: (M)
- Admin_Documents: (M)
- Admin_Roles: (M)
- Admin_Rules: (M)
- Admin_Responsibilities:

#### Roles that control the access to the tabs under Inbox

- Inbox_Department cases: (M, C, R)

#### Roles that control the access to the tabs under Archive and Reports

- Archive_Non conformance: (M, C, R)
- Archive_Actions: (M), Only under Archive
- Archive_Comments:
- Archive_Log: (M, C, R)
- Archive_Closed cases only: Users with this role will only be able to see the Closed cases under Archive/Messages, Archive/Comments, Archive/Order and Archive/Logs. The other status tabs will be visible but the user will not be able to select them.
- Reports_User reports:

#### Roles that control the access to the tabs under Info

- Info_Favourite documents:

#### Roles that control the access to the tabs of the simplified interface

- Info: (E)
- My cases: (E)
- Preferences: (E)
- Help: (E)

#### Roles that control the access to the tabs under My cases

- My cases_Messages: (E)
- My cases_Actions: (E)
- My cases_Questionnaires: (E)
- My cases_Log: (E)

### Roles that define access rights and how a user behaves

#### Documents

- Hearing participator: (M, C) Can participate in hearings. Users with the simplified interface can also have this role even if this is not the standard.
- Approve document: (M, C) Can approve documents in hearings. Users with the simplified interface can also have this role even if this is not the standard.
- Audit document: (M) Can be set up as the recipient of document audit warnings, can create a new audit and perform audits.
- Publish document: (). Disabled as default. When activated, this role is required to publish a document.

#### Messages / Actions

- Message originator (M, C, R, E): The name of the user will appear in the "Registered on behalf of:" drop-down menu when you register a new message.
- Create / Edit message (M, C, R, E): The user can create and edit his / her own messages.
- Create / Edit message, other department (M, C): The user can create / edit messages on all departments that are available in the Navigator.
- Action executor (M, C, R, E): The user can get the task to execute an action.
- Access to hidden text fields (M): The user can see the contents of the hidden text fields. If this role is attached to the user's user type, then the user will have access to the hidden text fields of the messages that (s)he is set to be the case handler for. If the role is attached to the user directly, then the user will be able to see the hidden text fields in the Edit message page of all the messages that (s)he has access to.
- See all messages: The user can see all messages in his / her organisation, as well as messages from message forms which have a role limitation of the type "See messages", even if the user does not have that role.
- Process message (M, C): The user can process messages.
- Default message receiver (M):
  - New messages that have not been assigned to a specific case handler, will appear under Inbox / Cases I am responsible for at the department which is closest to the department where the message was registered on, where there is a user with this role. The role can be associated with the user or the user's User type. This corresponds to the previous feature "Shows for the nearest line manager".
  - If the option "Early case handling" is turned on, the selection of the case handler will be done in the "Register new message" page without having set an "Early case handling" rule. Then the user with this role will be included in the list of users from which you can choose the case handler.
- Default possible information receiver (M, C, R, E): The user will appear under "All" and "All in own organisation" when someone selects the "Inform more" option in the Message process page.
- Default possible message receiver (M, C): The user will appear as a possible option when someone selects "Choose case handler" in the "Choose action" drop-down menu in the Message process page.
- Inform shortlist (M, C, R): The user will be a possible recipient when someone selects "Case handler list" after choosing "Inform more" in the Message process page.
- Limited to forms in case handler rules: Users with this role can only get their own messages / actions under Inbox and Archive unless the user is defined as either an "Additional case handler" or an "Early case handler" for specific message forms under Admin / Rules.
- User graph: Can see the graph of how many messages have been registered per user on a selected department under Reports (Overview by users checkbox).
- Facilit: Can transfer cases to Facilit if the integration module with Facilit is turned on.
- SMS responsible: Can send SMS from the page Admin / Users.
- Move message: May change department for messages the user has write access to. This role is not required if the user already has Content administrator.

#### Graphs

- Cannot click on graphs: Users with this role will not be able to click on graphs under Reports or Home (dashboard). This is to allow users to see charts without direct further access to the actual cases. To prevent such access in general, other tab roles will also have to be unselected for that user or user type.

#### Activity plan

- Activity participator (M, C, R, E): Will participate in activities. Users without this role will not be counted when the number of remaining answers is calculated. If a user has different user types on various departments and should only participate in the activity plan on some of them, be sure to select this role only for the user types who should participate.
- Fill out activity, other department (M, C): Can fill out activities for all departments that the user has in the Navigator.
- Environmental beacon:

#### Administration roles

- Organisation administrator (M): Can create / edit departments.
- User administrator (M): Can create / edit users.
- Form administrator (M): Can create / edit lists, message forms and categories.
- Activity administrator (M): Can create / edit activities.
- Document administrator (M): Can create / edit documents.
- Role administrator (M) Can create / edit roles.
- Rule administrator: Can create / edit rules.
- Responsibility administrator: Can create / edit responsibilities.

### Roles that provide extended super user rights

- System role administrator: The user can manage System roles. Not given to anyone in the standard version. Only the super user should have this role.
- Content administrator: The user can edit locked forms, move filled out messages and open closed cases. Not given to anyone in the standard version. Only the super user should have this role.

### Roles that give access to special functionality in the manager interface

- Competence module: Changes the functionality of the system to match with the competence module. Shows only if the Competence module is activated. (work in progress, not available at this time)
