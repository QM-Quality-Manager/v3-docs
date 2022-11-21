---
title: "Document data"
linkTitle: "Document data"
date: 2017-01-04
description: >
  Document data: Used to edit the general information relating to a document. Opens from Edit document data.
---
### Fields
#### Document name and type

- Name: The name of the document. Can be up to 100 characters long.
- Information: Short text (up to 500 characters) with information about the document. This text appears as a tooltip when you hover over the document name in Info, in message forms and lists.
- Document type: Τhe type of this document.
  - Write a document: Used if you wish to create (write) a document directly in Qm+. The document is saved as an HTML document and has some formatting options. The text edit field uses TinyMCE.
  - Link: Used if you wish to link to a resource on the internet or to a document on a local file server. Documents that are not accessible from the internet will not be indexed in our search engine and will appear as a Link Error under Documents. Make sure that the address entered is a valid http or https address.
  - File: Used if you want to upload a file from your local computer to the Qm+ server. This creates a copy of the file on the server. To make changes in the file, it must be edited locally and then uploaded again.
  - Folder: Used to create a folder structure under Info. Can not be opened as a document.
  - Process chart: Used when you want to create a process chart in Qm+. When you save a document with this type, the tab Process chart setup becomes available and you are no longer able to change the document type of this document.

#### Choose where the document will be shown under INFO

- Document departments. Table that shows the departments where the document will be shown.
  - From department. The document will be visible under Info and under Admin / Documents on the departments that will be set here. Use the "{{< onlystaticimg src="/images/Add.png" >}} Add department" button to get a new drop-down menu in the table.
  - Shown for subdepartments. If this is checked, the document will also be visible under Info from the subdepartments of the department which is selected in the "From department".
  - Delete. Only active if the document is associated with more than one department. Click on the Delete department icon {{< onlystaticimg src="/images/Delete.png" >}} to delete the association with the specific department.
- Document tab: Determines under which tab the document will appear under Info. Mandatory field.
- Document group: The document's group. Determines in which box the document will appear under Info. Mandatory field.
- Subdocument of: A subdocument will not be shown under Info, until the document above it is expanded by holding the cursor over the {{< onlystaticimg src="/images/Arrowclosed.gif" >}} icon.
- Public document: If this is checked, the document will be available to everyone and no authentication will be required to open it. Applies only to documents of type "Write a document", "Link" and "File".
- Position: Used only if the alphabetical sorting is turned off. Normally you can ignore this.

#### Customer specific document heading fields

These fields must be ordered separately. Used to add extra fields that will be displayed in the document heading. Only applicable for documents written in Qm+. Possible field types:

    Free text.
    Date.
    Department. Displays a drop-down menu that contains all departments. This may be role filtered, which means that only departments with a predefined role will be shown.
    User. Displays a drop-down menu that contains all users. This may be role filtered, which means that only users with a predefined role will be shown.

#### Status

This section appears only for documents that have been saved at least once.

- Version: The version of the document. Displayed as x.y, where x is the main version number and y is the edit number.
  - The main version number is increased by 1 each time the button "{{< onlystaticimg src="/images/Disc_multiple.png" >}} Create new version" is pressed.
  - The edit number is increased by 1 each time this page is saved and either the name, the document content if this is a document written in Qm+, or the document address has changed or a new document has been uploaded.
  - The edit number starts at 1 for each new version that is created. The edit number in previous versions of Qm+ was referred to as the revision number.
  - The version number is displayed as a link that you can click on. It opens the document in that version.
  - If the version shown on the page is newer than the published version of the document or the document has never been published, the button {{< onlystaticimg src="/images/Page_lightning.png" >}} Publish will appear. This button stores any changes made in the document and sets the current version as the published one.
  - If you are in a version of a document which has a newer version, you will be notified by the icon {{< onlystaticimg src="/images/Exclamation.png" >}} and the text "This document has a newer version". This text is a link that opens the newer version.
  - Documents that have a newer version can be changed, but you cannot create new versions of them.
- Published version. If the version of the document which is shown on the page is the actual published version, i.e. the one that appears under Info, the text "This is the published version" shows. If not, the version number of the actual published version of the document is displayed.
- Created by: The name of the user who has created this document.
- Latest edit by: The name of the user who changed the document last.
- Hearing status for this version: Appears only if the selected version is associated with a hearing. Displays the status of the hearing and links to Reply to a hearing.
- Document address: Only shown for saved documents. If you want another document in Qm+ to refer to this document, you may use this address as a link. This address can now also be used outside Qm+ and, for documents written in Qm+ (Document type: Write a document) or for uploaded files (Document type: File), it will always take you to the latest published version. If you are not already logged into Qm+, you will be prompted for your username and password in order to see the document.

#### Audit

- Activate regular audit. You should check this when you want a user to be warned on a regular basis that the document should be audited. The following fields described in this section are shown when this box is checked.
- Warning date for audit. The date when the user will be notified of the audit.
- Audit interval. The period between each warning. When a document, for which the audit due date has passed, is audited, the warning date is increased by the value in this field. If the document gets audited before the audit due date, the warning date will not be automatically updated. If you wish to update the warning date in this case, you will have to do so manually.
- Audit responsible. The user who receives the document audit warning in his / her Inbox.

#### Extra attributes

- Document is a template. Yes / No. Standard No. Only applicable for documents of the type "Write a document". A template document is an outline or start of a document, such as a set of standard headlines. Template documents that are saved and published can be inserted into, preferably new, documents from the Document content tab by all users. Template documents do not show under Info.
- Document heading type. Appears only for those who have the option for selectable document heading type set. Applies only to documents of the type "Write a document." Determines which of the available document heading types will be used for this document.




