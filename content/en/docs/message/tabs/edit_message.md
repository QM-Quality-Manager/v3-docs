---
title: "Edit message"
linkTitle: "Edit message"
date: 2017-01-04
description: >
  Tab under Inbox and Archive.
---
A message form has checkboxes or drop-down menus and text fields specified by the company's super user. At least one field will have an orange-like background colour. Orange fields are mandatory and must be filled out so that the message can be saved.

When a message is saved, it is registered on the department that is written in the top of the middle column in the message form. The message will appear immediately in the Inbox of the person(s) that is defined as the manager of the selected department, unless the early case process is enabled, see below. The message will also appear immediately under Reports and in the reports created from the same or a subordinate department.

### Filling out the form

- Remember to check something in all the fields with an orange-like background colour. There will usually be one such field in the upper left part of the screen. You will get an error message if you try to save a message and there are mandatory fields that have not been filled out. Please note that if there are more than one fields marked with {{< onlystaticimg src="/images/Tag_blue.png" >}}, you will only be able to select one category from all of them.
- Checkboxes:
  - Single choice: Fields that have a round box in front of each option. That means that you can select one option in this group. Once you have selected one option in a single choice field, then you can not take it away again.
  - Multiple choice: Fields that have a square box in front of each option. Here you can check any number alternatives or none at all.
- Check boxes and enter text in the fields you feel that apply to you. It may be that some message forms are general and that only some fields are relevant in your situation.
- Remember that the person who handles your message can make changes, typically write down additional information and change the cost field and priority.
- If there is a suggestion field, type your suggestion there. It is important for the improving process of the business. Some companies reward the month's or half the year's best suggestions for improvement.
- Priority: This field gets a value based on the selections you make in the message form. This value can be overridden.
- Cost: This field is meant to represent the actual cost of the registered message. This field gets a value based on the selections you make in the message form. This value can be overwritten. Super users can remove the cost field from a message form.
- Risk assessment: Some message forms may have a built-in risk assessment. In some cases, you should then evaluate the probability and the consequence that the registered event will happen again, in other cases you should evaluate the probability and the consequence for a hypothetical event. The risk value is then automatically calculated and displayed with a colour at the corresponding location in the risk matrix.
- Numeric fields: Categories can be displayed as numeric fields instead of checkboxes. Such numeric fields can be used to report for example the number of liters of water consumption or other number or quantity statements.
- Upload file: Use this if you want to add external files to the message, like images etc. Maximum file size allowed is 10 MB. Not enabled in the standard version.

### Buttons

- {{< onlystaticimg src="/images/Tick.png" >}} Save / Send: Saves the changes you have done.
- {{< onlystaticimg src="/images/Folder_table.png" >}} Process: Only for users having the process message system role. Saves the changes you have done and takes you to the Message process page.
- {{< onlystaticimg src="/images/Page_copy.png" >}} Copy: Copies this message and opens the copy. Appears only for risk messages.
- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} Show as pdf: Opens the Option page for reports from which you can export the current message to a .pdf file. This is intended for paper printing.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Sends you back to the page you came from.
- Change message form: Only for users having the system role Content Administrator. Gives the possibility to change the message form of a message. It only shows how the current message would look if another form was used. The message form is not actually changed until the user presses the Save button. Anonymity, department, priority, text fields, cost fields and any selected categories that are common in both message forms (the one used for the original message and the new one) are preserved.
- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the current window.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.

### Drop-down menus

- Version overview: Only for saved messages. The latest version is always selected when the message opens. Any other previous version can be selected. Then the message will be shown as it appeared at that time. You can only make changes to the latest version. All changes to a message lead to the creation of a new version. New versions are marked with who made the change and when.
- Registered on department: Only for users with the system role Content administrator. Used for moving registered messages.

### Early case process

This field appears only for messages that are not saved and only if it is enabled for the message form you are looking at. Activation of Early case process is not recommended for new customers unless they have special requirements.
Early case process means that the message can be assigned to a responsible person already when it is being registered. Normally this is not done by the person who registers the message but only when a manager or case handler is processing the case on the department where the message was registered. The Early case process can be activated by users with user type Manager on the top department or by users who have the system role Content administrator. This can be done under Admin / Rules, Rule type "Early case handlers" if you create such a rule for a message form. It is also possible to activate an option that shows a menu in the New message page similar to the "Send to case handler" drop-down in the Message process page. With this option you do not need "Early case handler" rules, but they can be used even if this option is on and the drop-down menu in the New message page will only show those.

- Send to case handler / line manager: Drop-down menu where you can choose to whom this message will be sent. This does not change the department on which the message is registered, even if the selected user is in another department.
- Send email: If this is checked here, an email will be sent to the selected user when you press the Save button.
- Deadline: Date / Time. This date and time will appear as the deadline for those who will receive the message.

### Tabs

The tabs here are only active for saved messages. Changes made in the page will not be saved if you click on a tab.
- Edit message: Reloads the message. Use this if you want to remove the changes you have made and have not saved yet.
- Dialog: For simplified interface. Takes you to the Dialog screen.
- Message process: For user types having the complete interface. Takes you to the Message process page.
