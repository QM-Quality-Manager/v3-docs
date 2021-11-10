---
title: "Definitions"
linkTitle: "Definitions"
date: 2017-01-04
description: >
  All definitions specified.
---

# Alternative group
A collection of alternative answers that can be connected to questions in a survey form. Managed in the alternative groups.

An alternative group belongs to a specific alternative groups overview. This is used only to distinguish between alternative groups under Edit alternative answers and under Alternative groups. 

# Category group
A category group is used for grouping categories within the same topic and for setting properties for categories. In a message form, a category group is displayed as a headline over its corresponding categories. How it is displayed and how it works depends on the category group type. Each category group that is created, creates automatically a new report under Reports.

Category groups can also be used to identify groups of specific messages and actions via the search page for messages and the search page for actions.

Managed under Edit category group.

### Data

- Show for the language: The name of a category group can be set once for every language that is activated in the system. Appears only for customers who have multiple active languages.
- Category group type: The type of the category group.
- Category group name: The name used to represent the category group. A category group can have one name for each active language in the system.
- From department: From which level in the hierarchy the category group will be available.
- Information: Text that appears when you hold the cursor over the category group name in a message form.

### Advanced options

- Class: Default or Tasks. Categories of groups that are classified as Tasks represent a department's main tasks and are shown in the Edit department page. This will later be expanded with positions and competence.
- Subgroup of: If the category group is a subgroup of another category group.
- Shown for subdepartments?: Yes / No. If the category group will be visible also to all the subordinate departments of the selected department or only for the selected department.

# Defining category
A defining category is the category that describes what a message is about. It is mandatory to select a defining category for a message form to be saved. A defining category is defined by the fact that it belongs to a category group with a defined category group type. On a message form, defining categories are marked with the icon {{< onlystaticimg src="/images/Tag_blue.png" >}} and you can only select one of them. 

# Display type
Controls how the list is displayed.

Possible display types: Printer friendly, List version (or List form), Single question view. 

# Document group
A document group is a grouping of documents used to control which group of documents will appear under Info. Each document group is shown in a coloured box with the document group's name as the heading. A document group must contain at least one document belonging to the selected document tab for it to appear under the relative tab under Info. If a document group has documents that belong to various document tabs, then the document group will appear in each of these document tabs.

Managed under Edit document group.

Documents can be assigned to document groups under Edit document data.

### Fields

- Show for the language: The name of a document group can be registered once for every language that is activated in the system.
- Name: Used to identify the document group in tables and overviews. A document group can have one name for each language that is activated in the system.
- Position: The position of the document group under Info. In the standard version two document groups are displayed side by side. The next two will appear below these again until all the document groups are displayed.
- From department: The document group will appear under Info from the selected department and from its subordinate departments.
- Shown for subdepartments: If no, the document group will only appear under Info when the department selected under "From department" is selected in the Navigator.
- Background colour: If you want a special background colour for the document group, you can select it here.

# Hearing
A hearing is used when a group of users should be able to comment on the contents of a document. The hearing is connected to a version of a document, so that there can be several hearing rounds on the same document.

A hearing goes through the following phases:

- On hearing
- For approval
- Approved

A hearing is created under Edit document data, under the tab Hearing / Approval. It can be answered under Reply to a hearing that appears under Info, when opening the received hearing notification. A user receives a notification that (s)he has to participate in a hearing or that (s)he has to approve it under Cases I am responsible for and possibly by e-mail. 

# Log reports
Log is a tab under Reports.

The graphs for the log messages are shown here.

This tab appears only if the log messages are enabled. 

# Manager
One of the preconfigured user types in the system delivered with the standard version. Name and roles for all user types may be altered by the System administrator. The capabilities of the user type are defined by the system roles assigned to it. 

# Message status
Messages in Qm+ have a status that represents where they are in the handling process. The status of a message changes under Message process, the status of an action changes under Action process.

- New: The message is only registered.
- Sent to case handler: The message has been assigned to a responsible person with a deadline.
- Action in progress: Only under Archive. The message is connected to an action that has not yet been approved.
- Closed:
  - Under Reports: The message has been connected to an action.
  - Under Archive: The action that the message is connected to has been approved.
- Rejected: The message has been rejected.

When a message is connected to an action or rejected, it will be locked and it will no longer be possible to edit or process it, except from users with the system role content administrator.

Messages that are handled immediately, will be closed directly. 

# Print
Opens the print dialog of your browser in order to print the current page.

If you do not want to print the entire image or the print command does not print the part of the screen you want, try clicking the right button of the mouse in the field you want printed. Then choose Print from the menu that appears.

For users with high screen resolution the print out can be larger than the printer paper size. Trick to fix it:

- Choose reduced size for the printing. How this is done varies between different browsers and printers. Look for Scale, Reduce / Enlarge or a percentage (%) field. These can usually be found under the advanced options.
- Reduce the size of your browser window so that it looks more like the paper in the printer.
- Lower the resolution of your screen.
- Copy the part of the page you want to print out and paste it into an external program such as Word or a photo program, and print it from there. You can do this by pressing Prt Scr (Print Screen) on your keyboard and then pasting it by Ctrl + v at the desired application (for Windows PCs).

If you want to save the page as a PDF file instead of printing it on a printer, you can download and install the program PDFCreator. Next time you select Print or press Ctrl + P in your browser, you will be able to select PDFCreator as the printer. 

# Question
A list consists of topics and questions. A question may have an extra information field to provide additional information on the question. For survey forms, each question is also associated with an alternative group.

Questions are managed from Edit list content. 

# Reference
A reference is a document that is associated with an activity or a list and has also been marked as a reference. References are shown in tables and overviews along with the name of the corresponding activity. Activities inherit the reference affiliation from the list to which they are associated.

Reference functionality is an option that is not included in the standard version. 

# Reviewer
Reviewer is a user type in the standard version of Qm+ that has the same access rights as the user type manager. That means full access to read all cases within their remit, as well as reports via Reports and Activity plan. Reviewers have no access to Admin. Reviewers can register new messages on their own department and can edit only their own cases. 

# Role group
Role groups are used to sort roles. They are intended to be used by those customers who need to assign many different roles to multiple users. Instead of picking out roles one by one, one can instead simply assign all those roles in a role group for the various users.

All roles belong to one or more role groups. The roles that have not been assigned to a role group belong to no role group.

Role groups are managed under Edit role group. 

# Search criteria
Search criteria are the selected options when performing a search. They define what we search for.

They are shown in a table above the search results whenever a search is performed. A search may be started from Reports, from Search message, from Search action or by clicking on the risk matrix under Risk. All search results are shown in table form under Archive or as charts under Reports, under their respective tab.

- All criteria shown in drop-down menus can be changed. Such changes update the search results.
- Criteria followed by the {{< onlystaticimg src="/images/Delete.png" >}} icon can be removed from the search criteria. This also updates the search results.

# Single question view
Display type for lists. Used primarily for survey forms. Shows one question at a time with its own comment field if it should be possible to comment on the question. The answer is saved only when the Save button at the last question is pressed. 

# Subgroup
Subgroups are used to create grouped drop-down menus of categories in a message form.

The name of the category group to which the other groups are subgroups will be the title above the drop-down menu. Any categories in this group will then be listed at the top of the drop-down menu. Under these, there will be a heading in the drop-down menu for each subgroup. All the categories in the subgroup will be listed under this heading.

It is possible to select only one of the categories in such a drop-down menu.

This is a special functionality that one can usually discuss with QmPlus AS before using it. 

# Topic
A topic in a list is a headline over a set of questions. A topic can have an extra information field that appears under the heading when the list is answered. All questions in a list must belong to a topic.

Maintained under Edit list content. 

# Answer type
Every question in a list can have an answer type.

### Answer types:

- Single choice: One answer to each question. Even if one answer for a question is already selected, you should still answer the question. This is the default answer which will be used unless a change is made.
- Multiple choice: You can select as many alternative answers to each question as you wish, from none to all.
- Text: There will not be any check boxes for this question, only a comment field. Does not apply to the list version.
- Free text number: A number can be entered in response to this question. The graph will show the sum of all the numbers written as a reply to such a question.

Tip: Use the answer type Multi choice for questions with only one alternative answer, as in a checklist. Otherwise it will not be possible for users to remove the check mark if they change their mind. 

# Case
A case in Qm+ is either a message, an action, a hearing or an audit. 









