---
title: "Tabs"
linkTitle: "Tabs"
date: 2017-01-04
description: >
  All tabs for documents.
---
# Document tabs
Tab under Documents.

Here one can manage the company's document tabs.

Deactivated document tabs do not appear under Info and no documents can be assigned to them. Documents that belong to a deactivated document tab do not appear under Info either.

### Buttons

- New document tab: Opens the Edit document tab screen to create a new document tab.

### Icons

- {{< onlystaticimg src="/images/Folder.png" >}}: Opens the Edit document tab screen to edit an existing document tab.
- {{< onlystaticimg src="/images/Turnarrow.gif" >}}: Deactivates or activates the document tab depending on whether you are under Document tabs or Deactivated document tabs respectively.
- {{< onlystaticimg src="/images/View.gif" >}}: Used to open a document tab which you do not have the right to change. One has the right to change the document tabs created from the selected department in the Navigator and the underlying departments of that 

# Reply to a hearing
Reply to a hearing is a tab that shows under {{< onlystaticimg src="/images/Table_multiple.png" >}} Info when a hearing needs to be answered. This page can be accessed from the Inbox of those who should reply to it, and from Edit document data under Admin / Documents for users with access to it.

This page is used for replying to a hearing. The users who have been given the responsibility to participate in the hearing can reply to it and give their comments. The hearing's status can be changed by the person who has been assigned the responsibility to approve it.

### Fields

- Document: Link to open the document itself. Document number X in version Y: Number (X) and version (Y) of the document to which the hearing is attached. {{< onlystaticimg src="/images/Link_edit.png" >}} takes you to the Edit document data page for that document.
- Responsible for approval of the document: The person who will approve the hearing and who can change its status.
- Hearing / approval status: Can have the values On hearing, For approval and Approved.
- Hearing number: Serial number for all hearings in the system.
- Created: The creation date of the hearing.
- Responsible for the hearing: The person who has created the hearing.
- Hearing due date: The deadline (date and time) to reply to the hearing.
- My answer to the hearing: Unanswered / Ok / Not ok. Used by those who will participate in the hearing to provide feedback on the document.
- Hearing / approval status drop-down: Used by the person responsible for approving the hearing to change its status.
- Comment: Text field that can be used by anyone with access to the hearing.
- My comment: Menu for selecting who will receive the message written in the Comment field.

### Buttons

- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes you have made in this screen. If you wrote a comment it will be sent in the manner you have chosen in My answer.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Closes this page and takes you back to the page you came from.
- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the current screen.
- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.

### Tables

- Participants in the hearing: Overview over those who will reply to the hearing, their answers and when they last changed their answer.
- Comments to the hearing: All comments added to the hearing.

# Version overview
- {{< onlystaticimg src="/images/Folder_link.png" >}} Version overview: Tab under Edit document data. Used to provide an overview of all the versions of the document.

### Table

The table contains one row per version (Major version) that the document has been through.

- Name: Name of the document for this version.
- Version: "Version number.Edit number". Create a new version when you have made ​​major changes to the document. Must be done manually. The edit number changes whenever you save a change in the document.
  - Click RightArrow.gif to show the minor versions.
  - The version that is published and displayed under Info is marked with a {{< onlystaticimg src="/images/Tick.png" >}}.
  - {{< onlystaticimg src="/images/Page_white_put.png" >}} Copy and set as latest version. Click on this to copy the version of this row as a new version. Copies all content and document data, including the name. Shows only for documents of type Written document ("Write a file").
- Address: The address of the document. Click on it to open the selected version of the document.
- Created by: Who created this version.
- Created: When this version was first created.
- Latest edit by: The last user to change the document.
- Latest edit: When the last change was made.
- Compare: You can select any 2 versions from the table. Then when you click the Compare versions button, you will be able to see the text or the HTML differences between the two versions. Use the Compare as HTML / Compare as text button to switch the comparison view mode. Added elements are highlighted with green, while removed elements are highlighted with red and a strikethrough line. The function works only for documents written in the Qm+ editor.
