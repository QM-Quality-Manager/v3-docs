---
title: "Message search"
linkTitle: "Message search"
date: 2017-01-04
description: >
  Tab under Messages/NC, Log and Risk.
---
This page is used for searching among registered messages. The initial value of the Form type field depends on which tab you opened this page from. In many cases it is more appropriate to use Reports to identify specific messages than to use this page, but this page gives more options. This page can also be used together with Reports via the Expand search button in the search results.

### General search criteria

- Time frame: Search for cases from a certain time period. From and To date fields (inclusive).
- Status: Include messages with the selected status.
- Priority: Include messages with the selected priority.
- Form type: Appears only if the Log messages or the Risk messages are activated. Include messages with the selected form type. The result will appear in the tab corresponding to the selected form type.
- Form: Only messages created with the selected message form will be included. If you select something other than "All" here, the category groups and the categories in the section "Type of category to search by" below will only show those that are in use in the selected message form.
- Message number: Search for messages with the selected message number. When this field is used, none of the other search criteria is used.
- Registered on behalf of: Search for messages reported by the selected user.
- Content search: Search for messages containing a given text. The text can be in any of the text fields in the message. Characters are not case sensitive. Lucene is the search engine used for this function. See Lucene Query Syntax for detailed information about the syntax for the search field.
- Show messages from:
  - This department: Only messages registered on the department which is selected in the Navigator are shown.
  - This and subordinate departments: All messages registered on the department which is selected in the Navigator and on its subordinate departments are shown.
  - Subordinate departments: Only messages registered on the subordinate departments of the one which is selected in the Navigator are shown.
- Risk: Show the messages with categories of the category group type Risk. Choose the P and C value for the messages that will be included in the search.
  - P: Probability. Value from 0 - 5. 0 means that this parameter will not be used.
  - C: Consequence. Value from 0 - 5. 0 means that this parameter will not be used.

### Type of category to search by

This section is used to search for category groups and categories. Check one or more category groups and / or select categories from the menus. The defining category groups appear at the top. Among them you can only search for one category group and / or category. If a message type or a message form is selected, only the category groups and the categories used in these message forms will appear in this section.

### Order by

Select the column by which the result table will be sorted.

### Show results in

- Table: Show the results in the table of the Search results page for messages.
- Expanded view: Show the results in the expanded view that contains all the message details (previously "Printer friendly" version) of the Search results page for messages.
- Graph: Show the result as a chart under Reports.
