---
title: "Process chart setup"
linkTitle: "Process chart setup"
date: 2017-01-04
description: >
  Process chart setup: Used for editing the contents of a document of the type "Process chart". 
---
Opens from the page Edit document data and shows only when the document type "Process chart" is selected and the document has been saved at least once.

This page is separated in two parts. The left part is the Tree structure of the process while the right one depends on what is selected in the left part. Please note that you can right click on the tree for more options.

### General

- A new process initially has the same name as the document it contains it, but you can change it.

- You can make a process chart in all the languages available in the system.

- In general, a process can contain steps (which have to be implemented in a certain order) or tasks (which do not have to be implemented in an order, they could also be done in parallel), but not both at the same level. By default, a new process contains 4 main steps. In the process chart Preview page, steps are depicted in yellow while tasks are depicted in light blue. We will use the general term phase for both steps and tasks.

- Each step or task can have one or more responsible parties, which can be of type Object (User, Role, User type, Department) or Text (free text field with a limited size).

- Each step or task can have attributes (even if it is also a process with subprocesses). Attributes can be of type Object (User, Role, User type, Message form, Document, Department), Text (free text field with a limited size), Note (the Note field gives the possibility to write a longer text).

### How to set up a process chart

After you have created a new document of type Process chart and filled in the related data in the Document data tab, you should click Save. That makes the Process chart setup tab appear. When you first click on the Process chart setup tab, the system automatically creates a process with the same name as the newly created document and 4 main steps. You can see that in the left part of the page in a Tree structure. Every time you click on a phase in the Tree, the page on the right is updated with the options related to the phase you selected in the Tree. You can also right click on a phase in the tree to get the same or (sometimes) additional options.

### Editing the main process
#### {{< onlystaticimg src="/images/Keyboard.png" >}} Language settings
Here you can see a list with the available languages for your company. You should select in which of those the process chart will be available, and give the process name in all of them. The languages you select here will apply to the whole process chart. By default, the default language of the company and the current user's language will be preselected.

#### {{< onlystaticimg src="/images/Group_gear.png" >}} Configure responsibilities
Here you can select which of the available responsibilities will be used for this process chart. Select those you want from the list on the left and then click the Add button. The responsibilities you select here will appear in the Responsibility overview table on the right side of the page and will apply to the whole process chart. If you need to make a new responsibility for this chart that has not yet been defined in the system, you can click on the {{< onlystaticimg src="/images/Group_add.png" >}} New responsibility button. That will take you to the Responsibilities tab where you can define the new responsibility. After you do that and click Save and Close, you will be redirected back to this page.

#### Set default attribute type
Here you can see a list with the available attribute types. The type you select here will come up as the first suggested option every time you try to add a new attribute to a sub phase.

#### Responsibility overview
This table shows all the responsibilities that are available to the whole process and were selected via the Configure responsibilities button. You can remove a reponsibility by clicking on the {{< onlystaticimg src="/images/Group_delete.png" >}} icon.

#### Phases with linked prosess charts
This table appears if the process contains any phases with links to other processes. You can edit or remove a linked process chart by clicking on the {{< onlystaticimg src="/images/Group_edit.png" >}} or the {{< onlystaticimg src="/images/Group_delete.png" >}} icon respectively.

### Editing a phase

#### {{< onlystaticimg src="/images/Stepimage.png" >}} Add step
Here you are required to write the name of the step in all the languages you selected in the Language settings window earlier. You can also select the position, which is the order in which this step needs to be done within its parent phase. This button appears when the selected phase has no children of type task.

Please note: By default, the main process has 4 main steps to which you can add more if you wish by clicking on this button. If your process is to be comprised of tasks instead of steps, you will need to delete the default steps one by one by right clicking on their names on the tree and selecting Delete from the available options. Then the Add task button will also appear.

#### {{< onlystaticimg src="/images/Taskimage.png" >}} Add task
This button appears when the selected phase has no children of type step. Here you are required to write the name of the task in all the languages you selected in the Language settings window earlier. You can also select the position, which will only affect where this task will be shown in the tree structure underneath its parent phase.

#### {{< onlystaticimg src="/images/Stepimage.png" >}} Convert to step
This button appears only for tasks. It gives you the possibility to change this task and all other tasks in the same level to steps.

#### {{< onlystaticimg src="/images/Taskimage.png" >}} Convert to task
This button appears only for steps. It gives you the possibility to change this step and all other steps in the same level to tasks.

#### {{< onlystaticimg src="/images/Shape_align_center.png" >}} Import process chart
This button appears when the selected phase has no children. Here you have the option to select another process chart from the system and import it under the selected phase. This will copy that process inside the current document, which you will be able to see immediately in the tree structure on the left. Any changes done to the original chart after the import will not affect the current process chart. You will also get the option to "Replace name with imported process name". If you select this, the name of the selected phase will be replaced by the name of the top level process in the imported chart.

#### {{< onlystaticimg src="/images/Shape_align_center.png" >}} Link to process chart
This button appears when the selected phase has no children. Here you have the option to select another process chart from the system and link it under the selected phase. This will NOT copy that process inside the current document, it will only make a direct link to it. You will not be able to see the structure of the linked process chart in the tree structure on the left, you will only see a link symbol on the selected step {{< onlystaticimg src="/images/Icon_step_linked.png" >}} or task {{< onlystaticimg src="/images/Icon_task_linked.png" >}}. The linked process will appear normally in the Process chart view page. Any changes done to the original chart after the linking will have an immediate effect on the current process chart. After you link the selected phase to another process chart, you will be able to edit or remove that link if needed using the icons {{< onlystaticimg src="/images/Group_edit.png" >}} and {{< onlystaticimg src="/images/Group_delete.png" >}} respectively inside the linked process table that will appear at the bottom of the page for the selected phase or from the same table that will appear at the bottom of the page of the top level phase of this process.

#### Edit
This option comes up when you right click on a phase in the Tree, and gives the same options that appear on the right side of the page when you left click on the name of a phase.

#### Delete
This option comes up only when you right click on a phase in the Tree. If the phase that you are trying to delete has children, you will be informed of how many child nodes it has and you will be asked if you want to delete them all together with the selected phase or if you want to move them under a new parent node and which one. Otherwise, you will only get a confirmation message before actually deleting the selected phase.

#### Change parent
This option comes up when you right click on a phase in the Tree. It gives you the possibility to move the selected phase by selecting a new parent node for it. You can move it under any other phase that has no other children or that has children of the same type as the one you are trying to move (steps or tasks).

#### Add responsible
Here you can select who will be responsible for the selected phase with what kind of responsibility. You can set multiple responsible parties for a phase. First you select the responsibility (from the responsibilities configured on the main process level). You can write the responsible in a free text field (in all the languages set up on the main process level) or select from one of the available qm+ objects, User, Role, User type and Department. After you select the Object type you can also select its value from the list below. All responsible parties that you will set here will appear in a table below the button. You can later edit or delete a responsible using the respective icons {{< onlystaticimg src="/images/Group_edit.png" >}} and {{< onlystaticimg src="/images/Group_delete.png" >}}.

#### Add attribute
Here you can add more attributes to the phase. First you select the type of the attribute (first option is the Default attribute type configured on the main process level). The available types are:
- Object: User, Role, User type, Message form, Document, Department (dependent on the department which is selected in the Navigator). If there is a selected Department here, we will use this node as the starting point when displaying the chart display page.
- Text: free text field with a limited size (50 characters).
- Note: The Note field gives the possibility to write a longer text (255 characters). In the diagram, only a note mark is shown in the attribute list, while the note itself is displayed outside the figure at the bottom of the page in a separate Notes table.

You can also select the position, which is the order in which this attribute will show within its phase (compared to the other attributes, if any).

All attributes that you will set here will appear in the Attributes table below the button. You can later edit or delete an attribute using the respective icons {{< onlystaticimg src="/images/Group_edit.png" >}} and {{< onlystaticimg src="/images/Group_delete.png" >}}.

### Display modes

A document of type Process chart can be displayed in two modes, {{< onlystaticimg src="/images/Shape_align_center.png" >}} Process chart (the graphical representation of the process) and {{< onlystaticimg src="/images/Application_side_tree.png" >}} Responsibility matrix (if any responsible parties have been defined). Both of these buttons are at the bottom of the page and open a new window. You can only have one of these views open at a time.

When the document is opened, it will automatically get a meta-table that contains data about the document, identical to the one added to documents of type Written document.

Both views of the document can be exported to a .pdf file. Clicking on the Show as pdf button takes you to the page Option page for process reports.

#### Process chart view
The name of the process is shown above the chart at the center. Steps are represented by yellow boxes and are connected to their parent phase with black arrows, while tasks are represented by light blue boxes and are connected to their parent phase with blue lines. The phase (step or task) name is shown in bold inside the box, at the top.

On the upper right part of the page, you can see the Display settings for the whole chart, all of which start preselected. Please note that if you click on the Show as pdf button, the report will contain the same chart that is shown in this window, based on the selected display settings.

- Show responsibles: The responsible parties for each phase are shown in a red font below the phase name.
- Show attributes:
  - Attributes of type Message form are shown in a blue font, and have the icon {{< onlystaticimg src="/images/Application_form_edit.png" >}} in front. By clicking on the form name this window closes and you are taken to the page where you can register a message using that message form. When you save and / or close that page you will be taken back to the Process chart set up page.
  - Attributes of type Document are shown in a blue font, and have the icon {{< onlystaticimg src="/images/Link.png" >}} in front. If you click on the document name, the document will open in a separate window.
  - Attributes of type Note are shown in a black font, and they only appear as "Note1", "Note 2" etc inside a phase. These are clickable and take you to the aggregated Notes table which appears below the chart and contains the various phases that contain Notes attributes and the text written inside each Note.
  - All other types of attributes are shown in a black font.
- Display full chart: Displays the full chart. If this is not selected, then only the phases of the first level are shown in the chart. When you move the mouse cursor over the various phase names, it changes to the hand cursor if the phase is clickable, which means that it has children. Clicking on the phase name or in the empty space inside the phase expands the tree below it by one level.

#### Responsibility matrix view
If at least one responsible has been defined for a phase of the process, then the process chart can also be displayed in a matrix format that lists all the phases of the process in the first column in a hierarchical structure and the responsible parties in the first row. Inside the matrix, the responsibility codes are shown. If a phase has a Document attribute, the icon {{< onlystaticimg src="/images/Link.png" >}} will appear next to the phase name. You can click on it to see the name of that document which is also a a hyperlink, and clicking on it opens the document in a separate window. Below the responsibility matrix is the Responsibility overview table, which explains the Responsibilities (codes, names, additional information) that are available for this process.