---
title: listView
slug: jsp-listView
tags: api, java
publish: true
---

# \<kendo:listView\>
A JSP tag representing Kendo ListView.

## Configuration Attributes

### altTemplate `String`

Template to be used for rendering the alternate items in the listview.

#### Example
    <kendo:listView altTemplate="altTemplate">
    </kendo:listView>

### autoBind `boolean`

Indicates whether the list view will call read on the DataSource initially.

#### Example
    <kendo:listView autoBind="autoBind">
    </kendo:listView>

### editTemplate `String`

Specifies ListView item template in edit mode.

#### Example
    <kendo:listView editTemplate="editTemplate">
    </kendo:listView>

### navigatable `boolean`

Indicates whether keyboard navigation is enabled/disabled.

#### Example
    <kendo:listView navigatable="navigatable">
    </kendo:listView>

### pageable `boolean`

Indicates whether paging is enabled/disabled. Further configuration is available via [kendo:listView-pageable](#kendo-listView-pageable). 

#### Example
    <kendo:listView pageable="pageable">
    </kendo:listView>

### selectable `String`

Indicates whether selection is enabled/disabled. Possible values:

#### Example
    <kendo:listView selectable="selectable">
    </kendo:listView>

### tagName `String`

Specifies ListView wrapper element tag name.

#### Example
    <kendo:listView tagName="tagName">
    </kendo:listView>

### template `String`

The id of the template used for rendering the items in the listview.

#### Example
    <kendo:listView template="template">
    </kendo:listView>


##  Configuration JSP Tags

### kendo:listView-pageable

Indicates whether paging is enabled/disabled.

More documentation is available at [kendo:listView-pageable](listview/pageable).

#### Example

    <kendo:listView>
        <kendo:listView-pageable></kendo:listView-pageable>
    </kendo:listView>


## Event Attributes

### cancel `String`

Raised when the user clicks the "cancel" button.

#### Example
    <kendo:listView cancel="handle_cancel">
    </kendo:listView>
    <script>
        function handle_cancel(e) {
            // Code to handle the cancel event.
        }
    </script>

### change `String`

Fires when the list view selection has changed.

#### Example
    <kendo:listView change="handle_change">
    </kendo:listView>
    <script>
        function handle_change(e) {
            // Code to handle the change event.
        }
    </script>

### dataBound `String`

Fires when the list view has received data from the data source.
and is about to render it.

#### Example
    <kendo:listView dataBound="handle_dataBound">
    </kendo:listView>
    <script>
        function handle_dataBound(e) {
            // Code to handle the dataBound event.
        }
    </script>

### dataBinding `String`

Fires when the grid is about to be rendered.

#### Example
    <kendo:listView dataBinding="handle_dataBinding">
    </kendo:listView>
    <script>
        function handle_dataBinding(e) {
            // Code to handle the dataBinding event.
        }
    </script>

### edit `String`

Fires when the list view enters edit mode.

#### Example
    <kendo:listView edit="handle_edit">
    </kendo:listView>
    <script>
        function handle_edit(e) {
            // Code to handle the edit event.
        }
    </script>

### remove `String`

Fires before the list view item is removed.

#### Example
    <kendo:listView remove="handle_remove">
    </kendo:listView>
    <script>
        function handle_remove(e) {
            // Code to handle the remove event.
        }
    </script>

## Event Tags

### kendo:listView-cancel

Raised when the user clicks the "cancel" button.

#### Example
    <kendo:listView>
        <kendo:listView-cancel>
            <script>
                function(e) {
                    // Code to handle the cancel event.
                }
            </script>
        </kendo:listView-cancel>
    </kendo:listView>

### kendo:listView-change

Fires when the list view selection has changed.

#### Example
    <kendo:listView>
        <kendo:listView-change>
            <script>
                function(e) {
                    // Code to handle the change event.
                }
            </script>
        </kendo:listView-change>
    </kendo:listView>

### kendo:listView-dataBound

Fires when the list view has received data from the data source.
and is about to render it.

#### Example
    <kendo:listView>
        <kendo:listView-dataBound>
            <script>
                function(e) {
                    // Code to handle the dataBound event.
                }
            </script>
        </kendo:listView-dataBound>
    </kendo:listView>

### kendo:listView-dataBinding

Fires when the grid is about to be rendered.

#### Example
    <kendo:listView>
        <kendo:listView-dataBinding>
            <script>
                function(e) {
                    // Code to handle the dataBinding event.
                }
            </script>
        </kendo:listView-dataBinding>
    </kendo:listView>

### kendo:listView-edit

Fires when the list view enters edit mode.

#### Example
    <kendo:listView>
        <kendo:listView-edit>
            <script>
                function(e) {
                    // Code to handle the edit event.
                }
            </script>
        </kendo:listView-edit>
    </kendo:listView>

### kendo:listView-remove

Fires before the list view item is removed.

#### Example
    <kendo:listView>
        <kendo:listView-remove>
            <script>
                function(e) {
                    // Code to handle the remove event.
                }
            </script>
        </kendo:listView-remove>
    </kendo:listView>

