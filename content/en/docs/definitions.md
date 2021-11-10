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

# Category
A category is in most cases a checkbox in a message form. All categories belong to a category group. The category group type of the category group determines how the category will appear in the message form. All information that is entered in relation to a category in a message form can be extracted as a report via Reports. The categories can also be used to identify groups of specific messages via the search page for messages and the search page for actions.

Managed under Edit category.

### Data

- Show for the language: The name of a category can be set once for every language that is activated in the system. Appears only for customers who have multiple active languages.
- Category group: The category's group. The category group type of the category group determines how this category will look like in a message form. A text at the bottom of this screen describes the type of the selected group.
- Category name: The name used to represent the category. A category can have one name for every language that is activated in the system.
- Priority: Low, Medium, High. The predefined priority of a category. Can be overridden by the person who fills out the message form. The priority of a message is the highest priority of the checked categories unless it is overridden by the user.
- Cost: The predefined cost of a category. Can be overridden by the person who fills out the message form. The cost of a message is the sum of the costs of the checked categories, unless it is overridden by the user. Cost functionality can be removed for those who wish it.
- From department: The category is available from the selected department and its subordinate departments.
- Attached document: The document that will be activated if you click on the category in the message form.
- Information: Text field that is visible when you hold the cursor over the category in the message form.
- Risk data: Appear only for the categories belonging to a category group with the category group type Risk. Used to set different acceptance criteria for various risk categories.
  - Start yellow risk area: Overviews of this category will give a yellow risk value from (and including) this risk value.
  - Start red risk area: Overviews of this category will give a red risk value from (and including) this risk value.

# Category group type
The category group type of a category group determines how the categories in the group will be displayed and answered in a message form.

### Types
#### Defining category

Intended to describe what is the topic of a message. Single choice for the whole message form. If there are several defining groups in a message form, it will only be possible to check one category in one of the groups. A message form can only be saved if a category which belongs to a defining category group is checked. Defining categories are obligatory to fill out in a a message form. Defining categories usually appear at the upper part of the screen to the left with an orange background colour and are marked with the icon Tag blue.png.

#### Single choice

Used to provide additional information in a message form. One choice per group. Shown to the left under the defining categories.

#### Multi Choice

Used to provide additional information in a message form. Any number can be checked. Shown on the right.

#### Action

Used to provide detailed information on what kind of action should be used to deal with the conditions that the message is about. Any number can be checked. The categories in this group are taken further in the action, if one is created for a message. Shown in the center below the text fields in the message form.

#### Number

Provides a text field where any number can be entered. Selecting a group of this type in the Reports would cause the cost graph to be replaced with a graph showing the sum of the values in these fields. Shown to the right in the message form.

#### Risk

Each category of this type has two drop-down menus, where a value from 1 to 5 can be selected. The first symbolizes the probability that the event will happen, the second symbolizes the consequence. These values are automatically multiplied to produce a risk value. The risk value gets a colour based on limits set for the category. Messages with values > 0 for a risk category will appear in the risk report under Reports. Shown in the center of the message form under the Action categories. 

# Comment form
A message form that is associated with a question in a list is called a comment form. This message form is used for registering the comments given when replying to a list. If the display type single question view is used, the text above the comment field will be the name of the first text field in the comment form.

This link between the list and the message form means that all comments on an activity can be handled and given feedback to as if they were ordinary messages.

The comment form for a list can be selected under Edit list information. 

# Filling out
The function of filling out a list. Its appearance is determined by the list type and the selected display type for the activity.

See "Filling out a list form" and "Filling out a list in single question view".

# Graph report types
Graph report types can be selected under Reports, Message search and Action search to determine which kind of reports will be displayed.

### Graph report types

- Per department: Shows one graph per department for the department which is selected in the Navigator and one for each directly subordinate department to that one.

- Per department / Per category: If all the category groups are selected in the category group drop-down menu, then one graph per category group will be shown. If a particular category group is selected in the category group drop-down menu, then one graph per department for the department which is selected in the Navigator and one for each directly subordinate department to that one will be shown . This graph is colour coded so that each category in the selected category group will be marked with a different colour. This report has one graph for numbers and one for percentages.

- Per category / category group: If all the category groups are selected in the category group drop-down menu, then one graph per category group is displayed. If a particular category group is selected in the category group drop-down menu, then one graph per each category that belongs to the selected category group is displayed. When there are many reported messages in a category group, then this is the report that provides the best overview.

- Status: Provides a graph bar per message status.

- Priority: Provides a graph bar per priority.

- Distribution over time: Provides a graph bar per unit of time. Which unit is chosen depends on the selected time period.

- Risk report: Provides a risk matrix.

- List: Lists all the categories in the report grouped by category group.

# List type
The List type controls how a list will be displayed to the user. The different list types are: Checklists, Risk analysis lists and Survey forms.

# Log message
Log messages are messages that normally do not need to be handled, just registered and saved in the archive. Examples of such use can be minutes and documentation of legal execution. Log messages do not therefore appear under the Inbox unless you use Message process to activate them. The message type log message is not enabled in the standard version.

Log messages are in all other ways identical to the regular messages.

# Message type
All messages have a message type. A message gets the same message type as the message form it was registered with.

### The different message types

- Message: Common messages.
- Log message: Registered in the Log under Archive. Not included in the standard version.
- Risk message: Registered in the Risk under Archive. Not included in the standard version.

If neither log messages or risk messages are enabled in your system, the term message type will not be used.

# Mobile version
The mobile version of Qm+ is a separate interface adapted for display on mobile devices. The customization is done by sending over only the most important information and displays everything as short texts. It is possible to register messages, checklists and survey forms in this version. All information registered is visible in the normal Qm+ version in the same way as everything else.

The homepage for the mobile version is wap.qmplus.net. Logging in is done using the same company, username and password as for the normal login.

The mobile version is an additional module that must be ordered separately.

# Printer friendly
A printer friendly version is a message form or an action that is adapted in order to print well on paper.