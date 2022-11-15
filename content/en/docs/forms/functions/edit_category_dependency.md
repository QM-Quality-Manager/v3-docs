---
title: "Edit category dependency"
linkTitle: "Edit category dependency"
date: 2017-01-04
description: >
  Edit category dependency is a page for maintaining the category dependencies. It opens from Edit message form / Categories.
---
The headline of the page describes which category you edit the category dependencies for and which category group it belongs to. A category dependency is only used for the actual message form it was set up for. A category may only have one dependency against each of the other categories in that message form.

A category satisfies its dependencies when it both:

- satisfies all "And" dependencies. If it has no "And" dependencies it is considered satisfied.
- satisfies at least one "Or" dependency or it has no "Or" dependencies.

Note that when you close this page you have to reload the page {{< onlystaticimg src="/images/Note.png" >}} Categories or Edit message form for the changes to be visible in the category table. The easiest way to do that is by clicking on the tab {{< onlystaticimg src="/images/Note.png" >}} Categories above the category table.

### Fields

- The table Existing category dependencies shows the dependencies that the selected category already has (appears only if it has any). Here you can:
  - Change the dependency type between "And" or "Or".
  - Delete a dependency.
- New category dependency. Here you can add a new dependency.
  - First, select in the first drop-down menu the category group to which the category you want to set up a dependency on belongs.
  - Then, select the category from the second drop-down menu. Note that the content of this menu depends on what you selected in the first drop-down menu.
  - Finally, choose the dependency type. "And" is the default value.

### Buttons

- {{< onlystaticimg src="/images/Delete.png" >}}: Deletes the selected dependency.
- {{< onlystaticimg src="/images/Tick.png" >}} Save: Saves the changes done in the page. If the fields in the New category dependency part have been set, a new dependency is created.
- {{< onlystaticimg src="/images/Tick.png" >}} Save for the group: Saves the changes done in the page. If the fields in the New category dependency part have been set, a new dependency is created and it is is added to all categories in the category group that appears in the headline of the page.
- {{< onlystaticimg src="/images/Cross.png" >}} Close: Takes you back to the page where you came from.