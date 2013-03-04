---
title:PageableBuilder
slug:aspnetmvc-kendo.mvc.ui.fluent.pageablebuilder
publish:true
---

# Kendo.Mvc.UI.Fluent.PageableBuilder
Defines the fluent interface for configuring Pageable



## Methods

### PageSizes(System.Int32[])
Sets the page sizes of the grid.


#### Parameters

##### pageSizes `System.Int32[]`
The values shown in the pageSize dropdown




### PageSizes(System.Boolean)
Sets the page sizes of the grid.


#### Parameters

##### enabled `System.Boolean`
A value indicating whether to enable the page sizes dropdown




### ButtonCount(System.Int32)
Sets the number of buttons displayed in the numeric pager. Default is 10.


#### Parameters

##### pageSizes `System.Int32`
The value




### Enabled(System.Boolean)
Enables or disables paging.

#### Example

    <%= Html.Kendo().Grid(Model)
        .Name("Grid")
        .Pageable(paging => paging.Enabled((bool)ViewData["enablePaging"]))
    %>
        





