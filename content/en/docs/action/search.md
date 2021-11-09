---
title: "Action search"
linkTitle: "Action search"
date: 2017-01-04
description: >
  Tab under Actions.
---
This page is used for searching among registered actions. In many cases it is more appropriate to use Reports to identify specific actions than to use this page, but this page gives more options. This page can also be used together with Reports via the Expand search button in the search results. 

### General search criteria

#### Fields that use data from the actions

- Time frame: From and To date fields (inclusive).
- Status: Include actions with the selected status.
- Action number: Search for the action with this number.

#### Fields that use data from the attached messages

- Priority: Include actions with the selected priority.
- Form type: Appears only if the Log messages or the Risk messages are activated. Include actions attached to messages with the selected form type.
- Form: If you select something other than "All" here, the category groups and the categories in the section "Type of category to search by" below will only show those that are in use in the selected message form.
- Message number: Search for actions attached to the message with the selected message number. When this field is used, none of the other search criteria is used.
- Content search: Search for messages containing a given text. The text can be in any of the text fields in the message. Characters are not case sensitive. Lucene is the search engine used for this function. See Lucene Query Syntax for detailed information about the syntax for the search field.
- Show messages from:
  - This department: Only messages registered on the department which is selected in the Navigator are shown.
  - This and subordinate departments: All messages registered on the department which is selected in the Navigator and on its subordinate departments are shown.
  - Subordinate departments: Only messages registered on the subordinate departments of the one which is selected in the Navigator are shown.
- Show actions that are: Both options include actions from the selected department in the Navigator and from its subordinate departments.
  - Created on selected departments: The department where the action was created.
  - Processed by persons in the selected departments: The department where the action will be executed.
- Risk: Show the actions attached to messages with categories of the category group type Risk. Choose the P and C value for the messages that will be used.
  - P: Probability. Value from 0 - 5. 0 means that this parameter will not be used.
  - C: Consequence. Value from 0 - 5. 0 means that this parameter will not be used.

### Type of category to search by

All the parameters in this section are used for the messages attached to the actions.

This section is used to search for category groups and categories. Check one or more category groups and / or select categories from the menus. The defining category groups appear at the top. Among them you can only search for one category group and / or category. If a message type or a message form is selected, only the category groups and the categories used in these message forms will appear in this section.

### Order by

Select the column by which the result table will be sorted.
Show results in

- Table: Show the results in the table of the Search results page for actions.
- Expanded view: Show the results in the expanded view that contains all the action details (previously "Printer friendly" version) of the Search results page for actions.
- Graph: Show the result as a chart under Reports.
