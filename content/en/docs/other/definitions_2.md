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

# Risk matrix
A risk matrix shows an overview of Probability and Consequence in a 5 x 5 matrix. The fields are coloured green, yellow and red to symbolise the different acceptance levels for the risk value.

Qm+ has a risk matrix under Reports for each message type. The matrix under Message Reports refers to real events, while the matrix under Risk Reports shows an overview of potential incidents. The matrix of potential incidents appears also under Archive / Risk. 

# Risk value
Risk value (R) is the result of the multiplication of probability (P) and consequence (C).

> P * C = R.

The risk value is often visualised in a risk matrix.

At a risk assessment, one wishes to reduce the risk value. This is done by showing the probability- and consequence-reducing measures. 

# Role overview
- {{< onlystaticimg src="/images/Group.png" >}} Role overview: Used for assigning roles to a document. Opens from Edit document data.

- A document without roles:
  - is available to all users from the department where the document was created and from its subordinate departments.

- A document with associated roles appears under Info only for:
  - users assigned to one or more of the same roles.
  - users who have chosen a department associated with one or more of the same roles of the document.

Roles do not limit the access to documents under Admin / Documents. 

# Standard version
The standard version of Qm+ is the one with the system settings that is given to new customers if they do not ask for any changes.

The customer's contact person with QmPlus AS may order changes from the standard version. Most changes to system settings are done free of charge. Contact drift@qmplus.com if you have questions or change requests.

See system roles for the set up of user types in the standard version. 

# Super user
The super user is a user who has taken the super user course of Qm+. The super user has the highest access to Qm+ within the company. The super user will assist the other users in the company and will act as local support for Qm+.

All super users are entitled to free telephone support from Qm+ and can take advantage of this if they receive a question from their company users that they need help to answer. As a rule, one or more of the company's super users also function as contact persons between the company and QmPlus AS.

All requests for changing some functionality in the system must be communicated via the customer's contact person, so that we know that this is a request of the entire company. 

# System role
System roles are roles that are preset in the system and provide specific rights for using Qm+. System roles are defined by QmPlus AS but can be given from certain super users to users or user types. This is advanced functionality and is usually not turned on for new customers at the beginning. Contact drift@qmplus.com if you need this right or if you have questions.

You can find a list of the available system roles here. 

# Tab
The navigation structure of Qm+ is made up of tabs. They have a name that describes the location of the system you can go to if you click on them. Most also have a descriptive text that appears when you hover the mouse pointer over them.

Tabs also describe where you are in the system. The tabs that are darker than the others are selected.

Example :

{{< onlystaticimg src="/images/Arkfanebeskrivelse.png" >}} 

# User
A user is a set of information that identifies a real person who will be using Qm+.

Managed under Admin / Users / Edit user information by users having access to that tab or under Preferences for others.

### Data

- User name: Used by the user for logging into the system. Distinguishes between uppercase and lowercase letters. Must be unique for each customer.
- Department: The department to which the user belongs.
- Type: The user's user type.
- Password: Used by the user for logging into the system. Distinguishes between uppercase and lowercase letters.
- Repeat password: Must be identical with the password field in order for the user's data to be saved.
- First name: The user's first name.
- Middle name: The user's middle name.
- Surname: The user's last name.
- Email address: The user's email address. Some functionality of the system is linked to the user's email address. It is therefore preferred that each user has a unique email address.
- Language: Selection of the display language for the user. Available languages in the system are: Norwegian (bokmål), Norwegian (nynorsk), English, Swedish and Danish (not translated framework for Danish). The available languages for each customer will vary.
- Mobile number: Can be used for receiving SMS from the system, if this functionality is activated.
- Comment: Free text field for additional information about the user.

# User type
Name and roles for all user types may be altered by the System administrator. User types may also be added and removed. The capabilities of a user type are defined by the system roles assigned to it. A user must have one user type for each department the user is attached to. For a logged in user with multiple user types, only the roles attached to the user type of the department the user is currently logged in at, will be active. In the Standard version four user types are preconfigured: Manager, Case handler and Reviewer have the complete interface, while Worker has the Simplified interface.

### Manager

They have full access to the system in the standard version. Can have limited or increased access with the help of system roles.

### Case handler

Same access rights as the Manager, but the access to Admin is replaced by Preferences.

Managers and Case handlers appear automatically as possible recipients (case handlers) for messages under Messages/NC / Message process within their department. If it must be possible to send messages across the organisation, for example from the Health Department to the Technical department, at least one user of the user type Manager or Case handler in that department must be set under the tab Admin / Rules, Rule type "Additional case handlers".

### Reviewer

They have the same read access as Managers. They can only edit their own information, but may comment on all cases they can read. They appear automatically as possible recipients of the messages under Inform in the Messages/NC / Message process on their department. Reviewers may only register new messages on the department they are registered on, even though they have the navigator. They have the tab Preferences instead of Admin.

### Worker

They have their own simple interface that only allows access to their own information. 

# Worker
User type that in the standard version gives the users a simple interface, from which they can access only their own cases. 

# Action status
An action in Qm+ has an status that shows where it is in the handling process. The status of an action changes under Action process.

- Under planning: The action is being planned. Text fields must be filled out, categorisation and cost must be set and one or more users must be made responsible for executing the action.
- Under execution: The action has been sent to the person(s) who will execute it. When all the persons responsible for executing the action have checked out the field "Executed"and have written their comments, it can be sent for approval.
- Under approval: The action is waiting for approval from the person who created it.
- Approved: The action has been approved and can no longer be changed. Super users with the system role content administrator can still make changes.

An action under execution or under approval may be sent backwards in the process by using the << buttons in the status field of the Action process. 

# Activity group
Activities are organised in activity groups. This organisation has no influence on the system beyond the fact that it makes it easier to identify activities when there are many of them. In the Calendar under the Activity plan, activities are shown per activity group. 

# Activity report
An activity report can be used to write a final report for an activity. The activity report can be written by pressing the Report button under Comments to the activity.

Which message form will be used in the activity report is determined under Edit list information.

Activity reports are not included in the standard version and must be ordered specifically. 

# Alternative answer
An alternative answer is an answer you can choose to a question in a survey form. All the alternative answers you can choose from for one question are called an alternative group. Managed under Edit alternative answers.

### Data

- Number: Determines the sorting of the alternative answers in the alternative group.
- Text: The displayed text for that alternative answer. Each alternative answer may have one text for each enabled language.

# Alternative groups overview
All the alternative groups belong to an alternative groups overview. This is used only to distinguish between alternative groups when editing alternative answers and under the tab Alternative groups. Managed from the tab Alternative groups. 

# Case handler
The Case handler is a user type in the standard version in Qm+ that has approximately the same rights as the user type manager. That means full access to read and modify all cases within his/her remit, as well as reports via Reports and the Activity plan. A case handler does not have access to Admin. 

# Category dependency
A category dependency is used for controlling when a category is shown in a message form. Only categories without dependencies and categories that have all their dependencies satisfied are shown in the message form.

A category dependency is only used for the actual message form it is set up for. A category may only have one dependency against each of the other categories in that message form.

A category satisfies its dependencies when it both:

- satisfies all "And" dependencies. If it has no "And" dependencies it is considered as satisfied.
- satisfies at least one "Or" dependency or it has no "Or" dependencies.

Managed under Edit category dependency. 

# Checklist
A checklist is a list that is displayed with checkboxes in front of the question. To be able to edit alternative answers, the list type survey form must be used. A checklist is intended to be used as a "find the error list". That lists a series of common errors within the area to be examined. The users then check the point in the list if they know of the error. See list for explanation of data fields. 

# Comment message
A comment message is an additional text response to a question in a list. Comment messages are registered in a normal message form. Only the first text field in the message form that is connected to the list will show as a comment field inside the list.

Comment messages can be handled in the same way as the other messages. In the standard version, comment messages do not appear under Inbox unless someone has transferred them to a case handler, set a deadline or created an action for them.

Show comment list in Activity plan is used to get an overview of the comment messages for an activity.

You can get an overview of all comment messages from the tab Comment reports under Reports or from the Comments tab under Archive. 

# Default case handler
If a message form has a default case handler, the messages registered with this message form will appear on the Cases I am responsible for page of the default case handler instead of the Manager of the department where the message was registered. The message will still be registered on the department it was registered and will appear under Reports and Search.

If the same message form is set up with multiple default case handlers with overlapping departments, the user registering the message will be able to choose between them from a drop-down menu during registration. In the registration screen, there is also a checkbox for whether to send an email to the selected case handler when the message is registered. 

# Department
A department is a set of information that identifies a physical location or an organisational unit that will be used as the reporting unit in Qm+. Active departments can be selected in the Navigator. Managed under Admin / Organisation / Edit department. If a department is moved within the organisational structure, all associated data and records will automatically follow.

Function under Organisation.

### Fields

- Department name: The name used for the department in the system. Will appear in the Navigator.
- Subdepartment of: The department under which this department appears in the Navigator. This department will inherit the lists, the message forms, the documents and the activities from the department above it.

#### Advanced options

- The department's roles: The roles associated with this department.
  - Roles associated with a department apply to all users of the active department. That means all employees of that department and all other users who have selected that department in the navigator.
  - Roles associated with a department are used to control the accessibility of documents, forms and activities.
- The department's main tasks: Departments may be related to categories in a category group classified as Tasks. This is meant to visualize the department's main tasks, and has currently no system effect beyond that.

# Display criterion
A display criterion is a criterion that can be set on a question or a group of questions in a survey form. The most common use is to set up a question to show only if a particular alternative answer is selected on a previous question.

Display criteria are set for each survey form under Edit alternative answers.

### Behaviour

- Specific group, Element = None, Alternative = None: A checkbox appears before the group name with the text "Show" when the list is filled out. This box must be checked, in order for the questions in this group to show.
- Specific group, specific Element, Alternative = None: The question shows only if the particular question is not answered.
- Specific group, specific Element, specific Alternative: The question shows only if the particular question is answered with the specific alternative answer.

Display criteria work for the list version and the single question view. 

# Document
A document is a text written in Qm+, a reference to a file, a reference to a web page or a folder. Shown in the table under info for all users who have access to them, according to the document's department and roles.

Managed under Edit document data. A simple version control also exists on that page.

### Data

- Name: Used to identify the document in tables and overviews.
- Document type:
  - Written document: The document is written and maintained in the internal text editor of Qm+. When the document is opened, it will automatically get a meta-table that contains data about the document. The table shows who has created the document, when it was changed, the customer's logo and possibly the hearing status it has. The table can be customized on a per customer level.
  - Link: The document is a link to a page on the Internet, a document written in Qm+ or a file uploaded to Qm+.
  - File: The document is a file that was uploaded to Qm+ and stored on the server of QmPlus AS.
  - Folder: The document is only a folder that contains other documents under Info.
  - Process chart: The document is written and maintained in the Process chart setup page of Qm+ and can be displayed in two modes, Process chart and Responsibility matrix. When the document is opened, it will automatically get a meta-table that contains data about the document, identical to the one added to documents of type Written document. After a process chart is saved, it is not possible to change the type of the document again.
- Document group: The document's group. Determines in which box the document will appear under Info.
- Document tab: Determines under which tab the document will appear under Info. Appears only if this functionality is turned on. In the standard version, all documents are shown under the tab Managing documents under Info.
- Subdocument of: A subdocument will be shown only when the document above it is extended by holding the cursor over the {{< onlystaticimg src="/images/Arrowclosed.gif" >}} icon. Make sure to choose something in this menu after you have selected the Document group and the Document tab.
- Address: Where is the document. If it is a file that was uploaded, the address field will be set automatically. Do not make changes to it afterwards.
- From department: The document will be available from the selected department and its subordinate departments.
- Shown for subdepartments?: If no, the document will only appear under Info when the selected department in the "From department" is selected in the Navigator.
- Created by: The name of the user who has created this document.
- Version: Version number. Shows how many times there were changes made on the document. It will not be updated if the change is done outside Qm+.
- Roles: An unlimited number of roles can be associated with the document. A user must have at least one of these in order to be able to see the document under the Info page. Does not affect the availability of the document in the message forms or lists to which the document is attached.
- Last modified: Date when the document was last modified.

# Filling out PDF forms

### Purpose

It has been requested that the details of a message which will be reported with the help of a PDF form, should be automatically filled in. If a form has been linked to a PDF, the user will have a new opportunity to select a message form for filling data into the PDF. After the PDF document is opened, the data are already copied in the correct fields and the user can fill in the rest of the form.

### Layout

In order for the data of a form to be able to be exported to a PDF form, the fields must be manually connected to the fields of the PDF. Unfortunately, for the moment, this can only be done directly in the database, ie, the users must ask Qm+ to do it for them.

In order to connect a form to a PDF, we need the PDF and the message it will be connected to. In addition we need an accurate description of which fields in the PDF will be connected to which fields in the message. 

# GPS coordinates
{{< onlystaticimg src="/images/Map.png" >}} GPS coordinates is a tab under Edit message form.

Messages registered through the mobile application send the GPS coordinates of the location of the mobile device at the time of registration. Use this page to decide if these coordinates will appear in the Message process page and in the pdf reports. More options will appear in this page soon. 

# List

A list is a form used to collect information. Lists are managed under Admin / Forms and are sent out from the Activity plan. The appearance of a list is determined by the selected list type.

### Data

- Show for the language: The name of a list can be set once for every language that is activated in the system. Appears only for customers who have multiple active languages.
- List name: Used to identify the list in tables and menus.
- List type: Used to organise the lists in various overviews under Admin. Has no practical significance.
- Registered by department: The department where the list was created. A list can be used from the department where it was created and from its subordinate departments.
- Attached message form: The message form that is used to store comments on the list.
- Attached category: The category which will be selected in the attached message form when the comment is written.
- Attached report form: The message form that will be used to save reports to an activity where the list has been used.
- Attached report category: The category which will be selected in the attached message form when the report is written.
  - The report form and the report categories are not included in the standard version but can be activated for all customers who want them. In this case, contact drift@qmplus.com.
- List comment: A textual comment that will appear at the top of list when it is filled out.
- Attached documents: A link above the list that opens the selected document.

# List version
Display type for lists. Used mainly for checklists and risk analysis lists. Shows all the questions in a list. Opportunity to comment comes up on page two after Save is pressed.

All lists that appear when you log in to Qm+ in the normal way (not when logging in via a link in an e-mail that takes you directly to the list), are using the list version. 

# Periodic activity
A periodic activity is used when you want to schedule a periodic execution of an activity forward in time. The period is how frequently the activity will be carried out, for example, daily, weekly, annually.

The period and the individual dates can be managed under Periodic activity setup, and the other activity data under Edit activity. Individual dates for a periodic activity can be deleted under Activities. 

# Priority
Messages in Qm+ may have different priorities.

- Low: Highlighted in green.
- Medium: Highlighted in yellow.
- High: highlighted in red.

An action gets the same priority as the message attached to it with the highest priority. 

# Repetitive activity
A repetitive activity is an activity that can be filled out an unlimited number of times by each participant. Can also be used for registration of anonymous external surveys where all responses are registered on the same user. 

# Risk analysis list
A risk analysis list is a list that is displayed with a drop-down menu for the probability and a drop-down menu for the consequence of each question. See list for explanation of data fields. 

# Risk message
Risk messages are messages used to create a risk overview for your company. It is up to the company whether the risk messages should be handled or if they should only be registered and stored in the archive. Our recommendation is that they are not handled, only updated annually. Risk messages can only be closed by QmPlus AS (as an exception), as they should not normally be handled. Messages registered here do not appear in the Inbox unless you use Message process to activate them. The message type risk message is not enabled in the standard version. 

# Role
A role can be assigned to users, user types, departments, activities, message forms and documents. They provide rights and restrictions. Generally one can say that a user or a user's department must have the same role as an activity, a message form or a document in order to have access to it. Common roles can be set by the customer's super user.

Roles are sorted in role groups and managed under Edit role.

A special type of roles called system roles give extended rights for use of Qm+. System roles are set by QmPlus AS and they can be assigned to some super users. This is an advanced functionality and is usually not given to new customers. Contact drift@qmplus.com if you need this right or if you have questions.

### Data

- Name: A role can have one name for each language that is activated in the system.

# Rules submenu message form
{{< onlystaticimg src="/images/Wrench.png" >}} Rules submenu message form is a tab under Edit message form.

Use this page to get an overview of the rules which are associated with the message form. See Rules for a more detailed description of the table contents and functionality.

Please note that a message registered with a message form without case handlers follows the normal procedure and appears in the Inbox / My current cases of the nearest manager. In most cases this is the best solution. 

# Sub-activity
An activity can have sub-activities. They have no effect other than the fact that they are visually grouped together under Activities and Calendar. 

# Survey form
A type of list. Provides full flexibility to change the answers and comments for all questions. When used as a traditional survey, it is often worth using the display type "single question view". 

# The action process
The action process is the process from when an action is created until it is approved and closed.

Followed up through the Action process page.

- Under planning: All actions start with this status. In this phase, the action is being planned. First give a name to the action so that it becomes easy to identify it later, and enter the budget if you use this field. The text fields Corrective action and How to prevent repetition must be filled out so that those who will execute the action will know what to do. The action categories may also be selected now. The last thing you have to do is to select those who should execute the action and give them a deadline. This is done in the mandatory panel Persons responsible. Click on Send to execution >> or the >> button in the Status panel to save the action and change its status to Under execution.
- Under execution: In this phase, the work described in the action will be executed. If the time registration fields are enabled, the executors can log the hours they have spent carrying out the action per day. Then those who carried out the action must tick the Executed box. They can also write a comment in the Comment field and fill in the Actual cost if they know it. When all the changes have been done, use the button Send to approval >> or the >> button in the Status panel. This saves the action and change its status to Under approval.
- Under approval: Here the person who created the action will make sure everything is in order before (s)he approves the action.
- Approved: An approved action is closed and locked and can not be changed except by users with the system role content administrator. Comments can still be sent out to all involved users.


