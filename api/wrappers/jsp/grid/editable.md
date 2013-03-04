---
title: grid-editable
slug: jsp-grid-editable
tags: api, java
publish: true
---

# \<kendo:grid-editable\>

Indicates whether editing is enabled/disabled.

#### Example
    <kendo:grid>
        <kendo:grid-editable></kendo:grid-editable>
    </kendo:grid>

## Configuration Attributes

### confirmation `Object`

Defines the text that will be used in confirmation box when delete an item.

#### Example
    <kendo:grid-editable confirmation="confirmation">
    </kendo:grid-editable>

### createAt `String`

Indicates whether the created record should be inserted at the top or at the bottom of the current page. Available values are "top" and "bottom".

#### Example
    <kendo:grid-editable createAt="createAt">
    </kendo:grid-editable>

### destroy `boolean`

Indicates whether item should be deleted when click on delete button.

#### Example
    <kendo:grid-editable destroy="destroy">
    </kendo:grid-editable>

### mode `String`

Indicates which of the available edit modes(incell(default)/inline/popup) will be used

#### Example
    <kendo:grid-editable mode="mode">
    </kendo:grid-editable>

### template `String`

Template which will be use during popup editing

#### Example
    <kendo:grid-editable template="template">
    </kendo:grid-editable>

### update `boolean`

Indicates whether item should be switched to edit mode on click.

#### Example
    <kendo:grid-editable update="update">
    </kendo:grid-editable>

