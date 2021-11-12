---
title: "Info"
linkTitle: "Info"
date: 2017-01-04
description: >
  Info is a tab on the Main Page.
---
Used to display the document overview in the system. The documents are organised in different areas of the screen. They can also be distributed under multiple tabs. The document structure is determined by the company's local super user. {{< onlystaticimg src="/images/Collapse.png" >}} and {{< onlystaticimg src="/images/Expand.png" >}} are used to expand and collapse the subdocuments of documents. There is also a search function here that performs free text searches in all the documents that appear in this page.

The document names function as links. Click on a document name to open the document. Especially for documents created in Qm+: You can either open the HTML version by clicking on the document name, or you can get a PDF version of the document by clicking on the {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} icon on the right of the document name.

When clicking on the {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} icon on the right of documents written in Qm+ that have subdocuments (they have the {{< onlystaticimg src="/images/Expand.png" >}} icon in front of them), you get a popup window where you can select if you want the exported .pdf to include only the current document or also its subdocuments.

Folders that contain documents written in Qm+ also have a pdf icon, which prints all such documents in the selected folder in one .pdf file. The pdf report from a folder includes also all sub-documents of internal documents in the printed file (not just the sub-documents of folders). This is intended to correct the problem that arises when one has written each chapter of a big document in a separate Qm+ document and wants to print the entire document as a whole.

You can also get the document in .docx format by clicking on the {{< onlystaticimg src="/images/Page_white_word.png" >}} icon. The option for exporting to .docx is not included in the standard version. If you want this option enabled, contact drift@qmplus.com. Please note that the .pdf version is the most suitable for printing. At this point, we cannot guarantee that the .docx produced file will look the same in all editors or that it will open correctly in all versions of Microsoft Office or OpenOffice. This export format should only be used when there is a need for manually updating the report. This functionality is still in test mode.

Documents can appear directly in this page under separate tabs instead of having the name of the document appear as a link. This functionality has to be ordered separately. Contact drift@qmplus.com if you want such a solution.

### Info.png What can I do here?

- I can search for documents: Click the "Search"-button at the bottom of the page.
- I can select between Tabs and Document groups to search in specific document collections.
- All the documents under INFO may be attached to different forms and categories such as message forms.

### Functions

- {{< onlystaticimg src="/images/Printer.png" >}} Print: Prints the current screen.

- {{< onlystaticimg src="/images/Help.png" >}} Help: Opens this page.

- {{< onlystaticimg src="/images/Find.png" >}} Search: Searches for the text that is written in the text field in front of the button. The search results depend on the department which is selected in the navigator, but not on the selected document tab. The search function uses the search engine Lucene.
  - Beneath the title of each document found in the search, the location of the document is displayed. It is shown as Document tab / Document group / Any parent document(s) / Document title.
  - When a free text search has been done, a set of search filters is displayed above the search results. The values in the filter are not affected by changing the department in the navigator and will remain until you click Close search results.
    - Document tab: Include documents from all or just the selected document tab.
    - Document group: Include documents from all or just the selected document group.
    - Department choice: Include documents from all documents available at the selected department or just the documents registered at the selected department.
  - Tip: Include only interesting words. For example, if you wish to search for procedures related to fire, use the keywords "procedures fire".
  - Advanced: See Lucene Query Syntax for detailed information about the syntax for the search field.
    - Searchable fields: Text, URL, DocumentId, Name, Information.
    - If no fields are specified, all fields are searched. In that case, extra weight is given to the name field.

- {{< onlystaticimg src="/images/Heart_add.png" >}} Add to favourites: This function is available for users who have the system role Info_Favourite documents, and for all documents except those of type Folder. The icon appears when the user moves the cursor over a document. Clicking on it marks the document as a Favourite document. These documents can later be found in the Favourite documents tab.

- {{< onlystaticimg src="/images/Heart_delete.png" >}} Remove from favourites: This function is available for users who have the system role Info_Favourite documents, and for all documents except those of type Folder. The icon appears when the user moves the cursor over a document that has been marked as a Favourite before. Clicking on it unmarks the specific document as a Favourite and removes it from the Favourite documents tab.

### Icons

Icons are used to symbolize different types of documents:

- {{< onlystaticimg src="/images/Page_white_world.png" >}} Link to the online version of the document
- {{< onlystaticimg src="/images/Lovdata_icon.png" >}} Link to a page from Lovdata
- {{< onlystaticimg src="/images/Page_white_word.png" >}} Word document
- {{< onlystaticimg src="/images/Page_white_acrobat.png" >}} PDF document
- {{< onlystaticimg src="/images/Page_white_excel.png" >}} Excel document
- {{< onlystaticimg src="/images/Page_white_powerpoint.png" >}} Powerpoint document
- {{< onlystaticimg src="/images/Page_white_text.png" >}} Document created in Qm+
- {{< onlystaticimg src="/images/Shape_align_center.png" >}} Document of type Process chart, created in Qm+
- {{< onlystaticimg src="/images/Image.png" >}} Image
- {{< onlystaticimg src="/images/Page_white.png" >}} Unknown or Blank document
- {{< onlystaticimg src="/images/Folder_page_white.png" >}} Folder. Can not be opened, used only to create a document structure

### Tabs

Used for sorting the documents. Determined by the super user. The tabs included in the standard version are:

- Managing documents
- Goals
- Favourite documents  
