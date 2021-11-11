---
title: "Tabs"
linkTitle: "Tabs"
date: 2017-01-04
description: >
  All tabs for info.
---
# Goals
Goals is a tab under {{< onlystaticimg src="/images/Info_16px.png" >}} Info.

Used in the standard version to display a textual description of the company's goals. There is a field for "Goals for quality management" and one for "Goals for HES". Users with the user type Manager who are registered on the highest department in the hierarchy have a Save button that allows them to change the content of these fields.

Goals are not multilingual and are the same for all departments. If such functionality is desired, use the normal mechanisms for documents (see Info). The tab Goals may be removed in the future. 

# Favourite documents

Favourite documents is a tab under {{< onlystaticimg src="/images/Info_16px.png" >}} Info.

To be able to see this tab, a user must have the system tab role "Info_Favourite documents".
This page contains in an alphabetical order all the documents that the user has marked as Favourites in Info. When the cursor passes over a document, the "remove from favourites" icon {{< onlystaticimg src="/images/Heart_delete.png" >}} appears. By clicking on it, the specific document is removed from this page.

# Managing documents
Managing documents is a tab under Info 16px.png Info.

Used in the standard version to show the documents. Can be changed / removed by the company's super user.

# Document tab
Each document tab appears as a tab under Info.

Managed under Edit document tab.

Documents are assigned to document tabs under Edit document data.

### Data

- Show for the language: The name of a document tab can be registered once for every language that is activated in the system.
- Name: Used to identify the document tab in tables and overviews. A document tab can have one name for each language that is activated.
- Position: The position of the document tab under Info.
- From department: The document tab will appear under Info from the selected department and from its subordinate departments.
- Shown for subdepartments: If no, the document tab will only appear under Info when the department selected under "From department" is selected in the Navigator.
- Subtab of: Used, if this tab should be a subtab. Then it will appear at a new level of tabs, under the tab that is selected here. Tabs with underlying tabs are not allowed to have their own documents.
- Information: Text that appears when you hold the cursor over the tab.
- Roles: A document tab with roles is only shown under Info if the user opening Info or the selected department in the navigator has at least one of the roles the document tab has.



