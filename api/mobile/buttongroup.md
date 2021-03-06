---
title: kendo.mobile.ui.ButtonGroup
meta_title: Kendo UI Mobile ButtonGroup API reference
meta_description: Learn how to define the initially selected button, select a button and get the currently selected button.
slug: mobile-kendo.mobile.ui.buttongroup
tags: api,mobile
publish: true
---

# kendo.mobile.ui.ButtonGroup

Represents the Kendo UI Mobile ButtonGroup widget. Inherits from [kendo.mobile.ui.Widget](/api/framework/mobilewidget).

## Configuration

### index `Number`

Defines the initially selected Button.

### selectOn `String` *(default "down")*

Sets the DOM event used to select the button. Accepts `"up"` as an alias for `touchend`, `mouseup` and `MSPointerUp` vendor specific events.

By default, buttons are selected immediately after the user presses the button (on `touchstart` or `mousedown` or `MSPointerDown`, depending on the mobile device).
However, if the widget is placed in a scrollable view, the user may accidentally press the button when scrolling. In such cases, it is recommended to set this option to `"up"`.

## Methods

### current

Get the currently selected Button.

### destroy
Prepares the **ButtonGroup** for safe removal from DOM. Detaches all event handlers and removes jQuery.data attributes to avoid memory leaks. Calls destroy method of any child Kendo widgets.

> **Important:** This method does not remove the ButtonGroup element from DOM.

#### Example

    var buttonGroup = $("#buttonGroup").data("kendoMobileButtonGroup");

    // detach events
    buttonGroup.destroy();

#### Returns

`jQuery` the currently selected Button.

### select

Select a Button.

#### Example

    var buttongroup = $("#buttongroup").data("kendoMobileButtonGroup");

    // selects by jQuery object
    buttongroup.select(buttongroup.element.children().eq(0));

    // selects by index
    buttongroup.select(1);

#### Parameters

##### li `jQuery | Number`

LI element or index of the Button.

## Events

### select

Fires when a Button is selected.

#### Handle select event

    <ul id="buttongroup" data-role="buttongroup">
      <li>Option 1</li>
      <li>Option 2</li>
    </ul>

    <script>
     $("#buttongroup").data("kendoMobileButtonGroup").bind("select", function(e) {
         //handle select event
     }
    </script>
