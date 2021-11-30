---
title: "Message"
linkTitle: "Message"
date: 2017-01-04
description: >
  A message is a filled out message form used for storing a registration in the system.
---
A message can be attached to one or more actions. An action can also be attached to one or more messages. A message can be attached to several actions regardless of what status the message has.

Messages are registered and modified under Edit message and processed in the Message process page.

Messages is the general name for normal messages, risk messages, log messages and comment messages. Risk messages and log messages are not activated in the standard version. They are identical to the regular messages except that they are intended to be used in a different way.

### Data

- Categories: A message can have an unlimited number of selected categories.
- Text fields: A message can have an unlimited number of text fields. In the standard version, messages usually have two text fields.
- Priority: Shows the priority of the message. Can have the values Low (green), Medium (yellow), High (red). It is set automatically based on pre-coded values for the selected categories. Can be overridden by the message originator and the case handler.
- Cost: A message can have 0 - 2 cost fields. In the standard version there is 1 cost field per message form.
- Registration date: When the registered incident occurred.
- Registered by user: The user who did the registration.
- Registered on behalf of user: The user reporting the message. It is this user who will be the message originator.
- Registered on department: The department where the message was registered. It is on this department that the message will be shown in reports and graphs.
- Operative department: The department where the actual case handler of the message is registered.
- Status: Possible status values for a message:
  - New: A message gets the status "new" when it is registered.
  - Sent to case handler: A message that has been assigned a case handler and has been given a deadline.
  - Rejected: A message that has been rejected. This is closed and can not be processed further.
  - Action in progress: A message that is attached to at least one action that is not approved.
  - Closed: A message that is attached only to actions that have been approved.
- GPS coordinates: Messages registered through the mobile application send the GPS coordinates of the location of the mobile device at the time of registration. Displayed in the Message process page only if this is set in the Edit message form page and if the user of the app had location services enabled on his / her device at the time of registration. If you click on the coordinates, a new page opens with the map of the specified location.
- Documents: The uploaded files, either via the mobile app or the Upload file function. File name, date and time of upload are displayed.

### Access control

All messages are registered on a department and get the status New or Sent to case handler if the selection of the case handler is made in the registration page. What kind of access a user has to a message is determined by the status and department of the message, and the user type, the department and the roles of the user.

#### The different access types give the following rights

- Read access: Can read the message and send email comments to it.
- Write access: Can edit the message.
- Process access: Can process the message and attach it to actions.
- Administration access: Can edit a message even if it is closed and locked. Can re-open closed messages, change the registration date, change the department and change the user on whom the message is registered. Can also do whatever the other access types can do.

To reject or send a message to the case handler, you need both write access and process access.

#### Requirements for obtaining the various access types

- Read access
  - The user on whom the message is registered (message originator).
  - Users with the user type manager, case handler and reviewer who have the same department as the one on which the message is registered or a department which is directly above this in the hierarchy.
  - Users with the user type manager, case handler and reviewer who have the same department as the message's operative department or a department which is directly above this in the hierarchy.
  - Users who have been informed of a message through an email from the Message process page.
  - Users who have been set as case handlers for the message but have forwarded it.

- Write access is granted only when the message's status is New, or Sent to case handler.
  - The user on whom the message is registered (message originator).
  - Users with the user type manager and case handler who have the same department as the one on which the message is registered or a department which is directly above this in the hierarchy.
  - Users with the user type manager and case handler who have the same department as the message's operative department or a department which is directly above this in the hierarchy.
  - Users who have been set as case handlers for the message but have forwarded it.

- Process access
  - Users with the user type manager and case handler who have the same department as the one on which the message is registered or a department which is directly above this in the hierarchy.
  - Users with the user type manager and case handler who have the same department as the message's operative department or a department which is directly above this in the hierarchy.
  - Users who have been set as case handlers for the message but have forwarded it.

- Administration access
  - Given to the users with the system role Content Administrator.
