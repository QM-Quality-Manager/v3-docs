---
title: "Rules"
linkTitle: "Rules"
date: 2017-01-04
description: >
  Rules is a tab under Admin.
---
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
