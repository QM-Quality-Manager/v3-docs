---
title: "Functions"
linkTitle: "Functions"
date: 2017-01-04
description: >
  All functions for forms.
---
# Edit alternative group
Function under Survey forms.

Used to edit alternative groups.

### Drop-down menus

- Language: The alternative answers in an alternative group can be set once for each language that is enabled in the system.
- Alternative groups overview: Every alternative group belongs to an alternative groups overview. Here you can choose which one.

### Buttons

- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the current screen.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.
- {{< onlystaticimg src="/images/Key_add.png" >}} New alternative answer: Opens a text field where you can write the name of a new alternative answer.
- {{< onlystaticimg src="/images/Key_delete.png" >}} Delete alternative answer: Appears only when you click on an alternative answer.
- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes you have made. Use this once you have entered a new or edited an existing alternative answer.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Closes this page and sends you back to Alternative groups or Edit alternative answers depending on where you came from.

### Table

- Click on the text of an alternative answer to select it. The row in the table will be highlighted in red. Now you can edit the text or use the button Delete alternative answer.
- {{< onlystaticimg src="/images/SmallArrowUpFilled.gif" >}}: Move this alternative answer up in the alternative group.
- {{< onlystaticimg src="/images/SmallArrowDownFilled.gif" >}}: Move this alternative answer down in the alternative group.

# Edit alternative groups overview
Function under Survey forms.
Used for editing the name of an alternative groups overview.

### Fields

Show for the language: Drop-down menu for the language. An alternative groups overview may have one name per language that is enabled in the system.
Alternative groups overview name: Write the name of the alternative groups overview.

### Buttons

- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the active window.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.
- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes that have been made.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Closes this screen and sends you back to the page you came from.

# Edit alternative answers
Function under Survey forms.

Edit alternative answers is used for setting alternative answers and display criteria for questions in survey forms.

### {{< onlystaticimg src="/images/Info.png" >}} What can I do here?

- I can add answer groups in the questionnaire. Click on the drop-down menu with the Alternative groups and select one.
- If the alternative group you are looking for is not in the drop-down menu: Click on "New alternative group" at the bottom of the page. You will find your new group at the bottom.
- I can select if the alternative answers will be Text, Multiple choice or Single choice. Click in Order / Answer type.

### Drop-down menu

- Default alternative group for this list: Drop-down menu that sets the alternative group which will be used in this list. The corresponding Choose button updates the list below according to the choice made here. Note that all changes of alternative answers you have already done in this list will be overwritten when you do this.

### List table

The table shows all the questions in the list and is used for assigning alternative groups to each question. Display criteria can also be set for all questions.

- {{< onlystaticimg src="/images/Accept.png" >}} / {{< onlystaticimg src="/images/Asterisk_orange.png" >}}: Opens the submenu to edit the display criteria for this question. {{< onlystaticimg src="/images/Accept.png" >}} means that the question does not have a display criterion and will always be shown. {{< onlystaticimg src="/images/Asterisk_orange.png" >}} means that the question has a display criterion and that it will only be shown for the user who answers the list when the display criterion is fulfilled.
- Group / Element name: Dark rows show groups, light rows show questions.
- Order / Answer type: Sorting applies to all questions in a group, answer type applies to each question.
- Alternative group: The alternative group that applies to the current question. If the alternative group is changed for a group and the Save button is used, all the questions in that group will be assigned to this alternative group.

### Alternative answers

This is the same table that can be found under Alternative groups.
Buttons

- {{< onlystaticimg src="/images/Page_gear.png" >}} Edit list information. Takes you to the Edit list information screen to edit the information on the selected checklist.
- {{< onlystaticimg src="/images/Page_edit.png" >}} Edit list content. Takes you to the Edit list content screen to edit the questions of the selected checklist.
- {{< onlystaticimg src="/images/Page.png" >}} Preview. Opens the preview window to see how the list looks in the printer friendly version. In this window you can also choose to see the list in list form or as a series of single questions which is how it will look when it will be filled out.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.

# Edit message form
Function for managing message forms.

Available from Message forms.

### Buttons

- {{< onlystaticimg src="/images/Page.png" >}} View form: Opens the printer friendly version of this message form so that you can easily see the effect of the changes you have made.
- {{< onlystaticimg src="/images/Cog.png" >}} Show / {{< onlystaticimg src="/images/Cog_delete.png" >}}: Hide advanced options. Shows only when the tab Categories is selected below.
- {{< onlystaticimg src="/images/Page_lightning.png" >}} Update messages: Updates all open messages to use the newest version of this message form. Warning: If categories or other fields have been removed from the form, this might lead to loss of registered data. This button is only shown for users having the system role content administrator.
- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes made in the fields.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page where you came from.

### Tabs

- {{< onlystaticimg src="/images/Page_edit.png" >}} Form data: Edit the general data of the message form.
- {{< onlystaticimg src="/images/Note.png" >}} Categories: Add or remove categories from the message form.
- {{< onlystaticimg src="/images/Page_white_edit.png" >}} Fields: Edit the fields in the message form.
- {{< onlystaticimg src="/images/Link.png" >}} Documents: Add or remove documents from the message form.
- {{< onlystaticimg src="/images/Group.png" >}} Roles: Add or remove roles from the message form.
- {{< onlystaticimg src="/images/Wrench.png" >}} Rules: Add or remove case handlers from the message form.
- {{< onlystaticimg src="/images/Map.png" >}} GPS coordinates: Add or remove the GPS coordinates feature from the message form.
- {{< onlystaticimg src="/images/Email.png" >}} Email settings: Change the subject of the information email for the message form.

# Email settings
{{< onlystaticimg src="/images/Email.png" >}} Email settings is a tab under Edit message form.

In this page you can change the subject of emails that are sent because of the Rules of the type Informed upon message registration. This means that in order to have any effect, this page must be used in combination with rules of this type. The email subject can be set to the name of a checked category in the message that belongs to a specified category group. If you do not set anything in this page, the default email subject will be used (e.g. "You have a new message in Qm+ from ...").

### Drop-down menus

- Category group: The defining or single-choice category group, the checked category of which will be set as the email subject.
- From department: The department from which this setting will apply.

Please note that if multiple category groups are set in this page, the category group with the From department which is closest to where the message was registered will be used.

### Buttons

- {{< onlystaticimg src="/images/Add.png" >}} Add: Sets the selected category group from the selected department.
- {{< onlystaticimg src="/images/Delete.png" >}} Delete: Deletes the specified category group / From department combination.





