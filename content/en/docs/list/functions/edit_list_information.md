---
title: "Tabs"
linkTitle: "Tabs"
date: 2017-01-04
description: >
  All tabs for lists.
---
# Edit list information
Function used by all lists for changing the information about them.

Available from Checklists, Risk analysis lists and Survey forms.

### Fields

- Show for the language: The name of a list can be registered once for every language that is activated in the system.
- List name: Identifies the list in tables and overviews.
- List type: Grouping for the list. Appears only for checklists.
- Registered by department: The list is available from this department and from its subordinate departments. Changes can only be made in the list from this department.
- Attached message form: The message form which will be used as the comment form when this list is used. If "No comment" is selected (only for individual groups and questions of survey forms), it will not be possible to comment on the questions of this list.
- Attached category: This category will be preselected for the comment form. If "All categories" is selected, then no category will be preselected. This prevents the display type single question view from being used.
- Attached report form: The message form that will be used as the report form when this list is used. Not enabled in the standard version.
- Attached report category: This category will be preselected for the report form. Not enabled in the standard version.
- List comment: Free text field for additional information about the list. It will be shown at the top of the list when it is answered.
- Risk alternative: Appears only for Risk analysis lists.

### Buttons

- {{< onlystaticimg src="/images/Page_edit.png" >}} Edit list content. Takes you to the Edit list content screen to edit the questions of the selected checklist.
- {{< onlystaticimg src="/images/Page_key.png" >}} Edit alternative answers. Takes you to the Edit alternative answers screen to edit the content of the selected list. It is only possible to edit alternative answers in survey forms that were created on the department which is selected in the Navigator.
- {{< onlystaticimg src="/images/Page.png" >}} Preview. Opens the preview window to see how the list looks in the printer friendly version. In this window you can also choose to see the list in list form or as a series of single questions which is how it will look when it will be filled out.
- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes made in the fields.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.
- {{< onlystaticimg src="/images/Cog_add.png" >}} Show / {{< onlystaticimg src="/images/Cog_delete.png" >}} Hide advanced options. Shows and hides the advanced options.

### Advanced options

These are things that come up when the button Show advanced options is pressed. The advanced options are hidden when you press the button Hide advanced options.

#### Fields

- The list's documents: The documents that are attached to this list.

#### Buttons

- {{< onlystaticimg src="/images/Link_add.png" >}} Add: Adds the selected document to this list. Please note that if you add a document that has subdocuments, all its subdocuments will also be added to the list.
- {{< onlystaticimg src="/images/Page_white delete.png" >}} Delete: Removes the selected document from this list.

### Only for survey forms

The fields of the attached message form and the attached category are repeated in a table for all topics and questions in the list. This can be used to adjust the associations for the whole list so that some questions get different comment forms or checked category.

If you want to change all the associations for all the questions under a topic, make the change in the topic line and press Save. Then automatically all the questions under this topic will get the same association that was selected for the topic. Similarly, if the attachment is changed for the list and the Save button is pressed, all questions will also be changed. 
