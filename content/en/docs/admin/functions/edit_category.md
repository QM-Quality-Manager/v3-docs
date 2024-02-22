---
title: "Edit category"
linkTitle: "Edit category"
date: 2017-01-04
description: >
  Edit category is a function under Categories.
---
Here you can manage the data of categories.

### {{< onlystaticimg src="/images/Info.png" >}} What can I do here?

- The Categories tab gives me the possibility to create new or edit existing Categories. (They will later be added to a message form).
  1. Select a category group. Then 
  2. enter the name of the new category. if applicable, 
  3. predefine the cost (which will be automatically added when you select this category in a message form). 
  4. You can decide from which department (in the navigator) the category will be visible in a message form.

Attention! The same message form can have different content depending on the location in the Navigator you have selected! If you want a pop-up for this category: Write this in the information text field.

### Fields

- Show for the language: The name of a category can be set once for every language that is activated in the system. Appears only for customers who have multiple active languages.
- Category group: The category's group. The category group type of the category group determines how this category will look like in a message form. A text at the bottom of this screen describes the type of the selected group.
- Category name: The name used to represent the category. A category can have one name for every language that is activated in the system.
- Priority: Low, Medium, High. The pre-defined priority of a category. Can be overridden by the person who fills out the message form. The priority of a message is the highest priority of the checked categories unless it is overridden by the user.
- Cost: The predefined cost of a category. Can be overridden by the person who fills out the message form. The cost of a message is the sum of the costs of the checked categories, unless it is overridden by the user. Cost functionality can be removed for those who wish it.
- From department: The category is available from the selected department and its subordinate departments.
- Attached document: The document that will be activated if you click on the category in the message form.
- Information: Text field that is visible when you hold the cursor over the category in the message form.
- Risk data: Appear only for the categories belonging to a category group with the category group type Risk. Used to set different acceptance criteria for various risk categories.
  - Start yellow risk area: Overviews of this category will give a yellow risk value from (and including) this risk value.
  - Start the red risk area: Overviews of this category will give a red risk value from (and including) this risk value.
- Add the category to the selected message forms (in the left column): In this panel you can manage the message forms to which the category will appear. The left panel shows the message forms where this category has already been added, the right panel shows the message forms where this category can be added. If a message form in the left panel is marked with yellow, the category will appear both when the message form is opened at the department where the category was added and at any subordinate department. Message forms in white will contain this category only when opening the form at the same department where the category was added. This is set by the state of the "Show for subdepartments" checkbox (checked or not) when adding the category to a message form.

### Buttons

- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes made in the fields.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page you came from.
- {{< onlystaticimg src="/images/Note_add.png" >}} << Add: Adds this category to the selected message form in the right panel.
- {{< onlystaticimg src="/images/Note_delete.png" >}} Remove >>: Removes this category from the selected message form in the left panel.
