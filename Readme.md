<!-- default file list -->
*Files to look at*:

* [Index.razor](./CS/MultiSelectEditor/Pages/Index.razor)
* [MultiSelectEditor1.razor](./CS/MultiSelectEditor/Components/MultiSelectEditor1.razor)
* [MultiSelectEditor2.razor](./CS/MultiSelectEditor/Components/MultiSelectEditor2.razor)
<!-- default file list end -->

### Blazor Editors - How to implement the multiple selection editor 

This example illustrates two different ways to implement the multiple selection editor. In both case our DxListBox box is used.
 
- In the first way, our DxListBox component is placed inside our DxPopup component. 
- In the second way, the [Bootstrap Dropdown widget](https://getbootstrap.com/docs/4.0/components/dropdowns/) is used, and DxListBox is placed inside that. This approach requires including the following JS libraries: jQuery, Popper, Bootstrap. 