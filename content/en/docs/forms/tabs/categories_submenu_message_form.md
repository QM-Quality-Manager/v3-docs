---
title: "Categories submenu message form"
linkTitle: "Categories submenu message form"
date: 2017-01-04
description: >
  Categories submenu message form is a tab under Edit message form.
---
Here you can manage the categories of the message form.

### Add categories to the message form

In this panel you can manage the categories of the message form.

The left panel shows the categories that are already in the message form, the right panel shows the categories that can be added. The panels are filtered by the category group which is selected in the category group drop-down menu above the left panel.

If a category in the left panel is marked with yellow, it will appear both when the message form is opened at the department where the category was added and at any subordinate department. Categories in white are only shown when opening the form at the same department where the category was added. This is set by the state of the "Show for subdepartments" checkbox (checked or not) when adding a category to the message form.

### Drop-down menus

The entries marked with "Advanced option" are only shown when the Show advanced options button in the Edit message form page has been clicked.

- Choose category group: The fields below this drop-down menu will only contain categories belonging to the selected category group. The category groups in this drop-down menu are grouped by category group type.
- Order type (Advanced option): Shown above the category group drop-down menu at the panel Add categories to the message form.
  - Ordering by Type is the default and means that the category groups will be sorted by their category group type.
  - Ordering by Index means that you can assign a column (left, center or right) and an index to each category group in the message form. If the sorting is to be done by index, one should go through all the category groups and set the column and index. The Save button must be pressed after each change so that it will be put into effect.
- Show as: Determines how the selected category group will appear in the message form (Checkbox / Drop-down menu).

Note that a category group needs to have either some of its own categories or some categories of a sub group attached to the message form for the following options to have any effect.

- Display in the message form (Advanced option): Determines if and how the given category group should appear in the message form.
- Display in the message process page (Advanced option): Determines if and how the given category group should appear in the message process page.
- Display in the action process page (Advanced option): Determines if and how the given category group should appear in the action process page.
- Display in Inbox (Advanced option): If set to Yes, then an extra column will appear under Inbox, where the checked categories that belong to this category group will be listed for messages.
- Display in the mobile app (Advanced option): If set to No, this category group will not appear in the message form when displayed in the mobile application. This field is visible only if the mobile application is activated.
- Mandatory: If set to Yes, the user will have to select a category in this group in order for a message created with this message form to be saved. Defining category groups are a special case and will always have Yes here. Note that if a message form has more than one defining category groups, the mandatory requirement will work so that only one of the categories in all the defining category groups will have to be checked before a message can be saved.

### Buttons

- {{< onlystaticimg src="/images/Note_add.png" >}}New category: Opens the New category screen with the Category group set to the same category group as the one selected in the drop-down menu.
- {{< onlystaticimg src="/images/Note_add.png" >}}<< Add: Adds the selected categories in the right panel to this message form.
- {{< onlystaticimg src="/images/Note_delete.png" >}}Remove >>: Removes the selected categories in the left panel from this message form.
- {{< onlystaticimg src="/images/Note_go.png" >}}: Edit category dependency for the selected category. Opens the page Edit category dependency.

### Categories in this message form

Displays a table for each category group with the categories associated with the message form. The table shows the name of the category and the department it was attached from. To delete a category from a message form, one must have selected the same department in the Navigator as the department where the category was attached from. 
