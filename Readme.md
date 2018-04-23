# How to implement a CheckedComboBox control (multi-selection)


<p>This example is based on example: <a href="https://www.devexpress.com/Support/Center/p/E76">Implementing a Multi-Column ComboBox using the ASPxGridView, ASPxButtonEdit and ASPxPopupControl</a>.<br />
To add a multi selection to this control, create the GridViewCommandColumn in the grid, and set the ShowSelectCheckbox property to True. Handle the grid's SelectionChanged client-side event, and use the GetSelectedFieldValues function to obtain the list of selected values.</p>

<br/>

