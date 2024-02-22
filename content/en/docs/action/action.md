---
title: "Action"
linkTitle: "Action"
date: 2017-01-04
description: >
  An action is a way to follow up and close a message. A message can have multiple actions and an action can have multiple messages. 
---
Managed under Action process.

Usually created from the Message process page.

Can be deleted and get attached to or detached from messages under Attached messages. 

### Data

- Action name: Used to identify the action in tables and overviews. Mandatory field.
- Budget: How much money is set aside for this action.
- Actual cost: Describes what the actual cost was. This field is used as the cost field in the report for actions.
- Status: Under planning, under execution, under approval, approved. See Action status.
- Action categories: The categories of the type Action in the message this action was made for, can be used in the action to categorize it. This is a multiple choice field.

### Text fields

- Original deviation: Description of the original deviation. Copied from the first text field in the message this action was created from.
- Corrective action: Description of the corrective action. Option: May be copied from the second text field in the message this action was created from. The text copied here should often be interpreted as a suggestion and should be changed by the creator of the action to become a task description.
- How to prevent repetition: Description of how to prevent the incident from happening again. You have to do something more than simply correct the error. Option: May be copied from any third text field in the message.
- Comment: Additional comments to the action.

### Persons responsible

- Message originator: The users who have created messages attached to this action.
- The action was created by: The user who created and owns the action and thus is responsible for it. Must also approve the action before it is closed.
- The action will be executed by: Those who will execute the action. Can be selected among all the users in the system.
- The action will be approved by: The person who will approve the action. It is always the same user who created the action. Can also be done by a super user with the system role Content administrator.

### Access control

All actions are registered on a department and get the status Under planning or Under execution if the selection of the executor is made in the Message process page. What kind of access a user has to an action is determined by the status and department of the action, and the user type, the department and the roles of the user.

#### The different access types give the following rights

- Read access
  - Can read the action.
  - Can send email comments to it.
- Write access
  - Can edit the action.
  - Some fields require also Process access to be able to edit them.
  - Activates the Save button.
- Execute for yourself
  - Can mark an action as Executed for their own users.
- Execute for others
  - Can mark an action as Executed for users within their own hierarchy.
  - With Process access, can mark the action as Executed for users outside their own hierarchy.
- Process access
  - Can process the action.
  - Can change its status.
  - Can assign or remove the person responsible for execution.
  - Can attach the action to several messages or detach it from messages.
  - Can edit the field Original deviation.
- Delete access
  - Can delete the action. All attached messages will be detached and get the status New or Sent to case handler depending on their previous status.
- Administration access
  - Can edit an action even if it is closed and locked.
  - Can re-open closed actions.
  - Can also do whatever the other access types can do.

#### Requirements for obtaining the various access types

- Read access
  -The message originator of a message which is attached to the action.
  -The executor of the action.
  -Users with the user type manager, case handler or reviewer who have the same department as the one on which the action is registered or a department which is directly above this in the hierarchy.
  -Users with the user type manager, case handler or reviewer who have the same department as the one on which a message attached to the action is registered or a department which is directly above this in the hierarchy.
  -Users who have been set as case handlers for a message which is attached to this action.
  -Users with the user type manager, case handler or reviewer who have the same department as a user who has been the case handler for a message attached to the action or a department which is directly above this in the hierarchy.
  -Users who have been informed of a message through an email from the Message process page and this message is attached to the action.

- Write access is granted only when the action's status is not Approved.
  -Users with the user type manager or case handler who have the same department as the one on which the action is registered or a department which is directly above this in the hierarchy.
  -Users who will execute the action and the action's status is Under execution.
  -Users with the user type manager or case handler who have the same department as the action's executors or a department which is directly above this in the hierarchy.

- Execute for yourself
  -Users who will execute the action and the action's status is Under execution.

- Execute for others
  -Users with the user type manager or case handler who have the same department as the action's executors or a department which is directly above this in the hierarchy, and the action's status is Under execution.

- Process access
  -Users with the user type manager or case handler who have the same department as the one on which the action is registered or a department which is directly above this in the hierarchy.

- Delete access
  -The owner of the action, the user who will approve the action, can delete it if it has the status Under planning.

- Administration access
  -Given to the users with the system role Content Administrator.
