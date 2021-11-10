---
title: "Functions"
linkTitle: "Functions"
date: 2017-01-04
description: >
  All functions for documents.
---
# Edit document group
Function under Documents for managing data about document groups.

### Fields

- Show for the language: The name of a document group can be registered once for every language that is activated in the system.
- Name: The name of the document group.
- Column: Not specified (default), Left column, Right column. If the left or the right column is selected, the group will always appear at that position under Info.
- Position: The position of the document group under Info. In the standard version two document groups are displayed side by side. The next two will appear below these again until all the document groups are displayed.
- From department: The document group will appear under Info from the selected department and from its subordinate departments.
- Shown for subdepartments: If no, the document group will only appear under Info when the department selected under "From department" is selected in the Navigator.
- Starts closed under Info: No (default), Yes. If a group starts as closed, the user will have to click on it with the mouse in order to see the documents that are in it.
- Background colour: If you want a special background colour for the document group, you can select it here.

### Buttons

- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes made in the fields.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.
- {{< onlystaticimg src="/images/Color_wheel.png" >}} Choose colour: Opens a list of colors you can choose from.

# Edit document tab
Function under Documents for managing data about document tabs.

### Fields

- Show for the language: The name of a document tab can be registered once for every language that is activated in the system.
- Name: Used to identify the document tab in tables and overviews. A document tab can have one name for each language that is activated.
- Position: The position of the document tab under Info.
- From department: The document tab will appear under Info from the selected department and from its subordinate departments.
- Shown for subdepartments: If no, the document tab will only appear under Info when the department selected under "From department" is selected in the Navigator.
- Subtab of: Used, if this tab should be a subtab. Then it will appear as a new level of tabs, under the tab that is selected here. Tabs with underlying tabs are not allowed to have their own documents.
- Information: Text that appears when you hold the cursor over the tab.
- Role overview: A document tab with roles is only shown under Info if the user opening Info or the selected department in the navigator has at least one of the roles the document tab has.

### Buttons

- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes made in the fields.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.
- << Add: Adds the selected role to this document tab.
- Remove >>: Removes the selected role from this document tab.