---
title: Overview
slug: jsp-multiselect-overview
publish: true
---

# MultiSelect

The MultiSelect JSP tag is a server-side wrapper for the [Kendo UI MultiSelect](http://docs.kendoui.com/api/web/multiSelect) widget.

## Getting Started

There are two ways to bind a Kendo MultiSelect:

*   **server** - the data will be serialized to the client. No Ajax requests will be made.
*   **ajax** - the multiSelect will make ajax requests to get the data. [Here](http://docs.kendoui.com/getting-started/using-kendo-with/jsp/tags/multiSelect/ajax-binding) you can find more information about this binding.

Here is how to configure the Kendo MultiSelect for binding to a data passed as model attribute in Spring MVC:

1.  Make sure you have followed all the steps from the [Introduction](http://docs.kendoui.com/getting-started/using-kendo-with/jsp/introduction) help topic.

2.  Create a new action method and pass the Products table to the View:

        @RequestMapping(value = {"index"}, method = RequestMethod.GET)
        public String index(Model model) {
            model.addAttribute("products", product.getList());

            return "web/multiselect/index";
        }

3. Add kendo taglib mapping to the page

        <%@taglib prefix="kendo" uri="http://www.kendoui.com/jsp/tags"%>

4.  Add a server bound multiSelect:

        <kendo:multiSelect name="productMultiSelect" taTextField="productName" dataValueField="productId" filter="startswith">
            <kendo:dataSource data="${products}"></kendo:dataSource>
        </kendo:multiSelect>

## Accessing an Existing MultiSelect

You can reference an existing MultiSelect instance via [jQuery.data()](http://api.jquery.com/jQuery.data/).
Once a reference has been established, you can use the [API](http://docs.kendoui.com/api/web/multiselect#methods) to control its behavior.

### Accessing an existing MultiSelect instance

    //Put this after your Kendo MultiSelect tag declaration
    <script>
    $(function() {
        // Notice that the Name() of the multiselect is used to get its client-side instance
        var multiSelect = $("#productMultiSelect").data("kendoMultiSelect");
    });
    </script>

## Handling Kendo UI MultiSelect events

You can subscribe to all [events](http://docs.kendoui.com/api/web/multiselect#events) exposed by Kendo UI multiselect:

### Subscribe by handler name

    <kendo:multiSelect name="productMultiSelect" dataTextField="productName" dataValueField="productId" change="multiselect_change">
        <kendo:dataSource data="${products}">
        </kendo:dataSource>
    </kendo:multiSelect>

    <script>
        function multiselect_change() {
            //Handle the change event
        }
    </script>
