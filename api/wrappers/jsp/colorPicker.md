---
title: colorPicker
slug: jsp-colorPicker
tags: api, java
publish: true
---

# \<kendo:colorPicker\>
A JSP tag representing Kendo ColorPicker.

## Configuration Attributes

### buttons `boolean`

Applicable only for the HSV selector (that is, when pallete is
null).  This specifies whether the "Apply" / "Cancel" buttons are to
be displayed in the drop-down HSV picker.

#### Example
    <kendo:colorPicker buttons="buttons">
    </kendo:colorPicker>

### columns `float`

The number of columns to show in the simple color dropdown.  For the
"basic" and "websafe" palettes this is automatically initialized; if
you pass a custom palette then you can set this to some value that
makes sense for your colors.

#### Example
    <kendo:colorPicker columns="columns">
    </kendo:colorPicker>

### messages `Object`

Allows customization of "Apply" / "Cancel" labels.

#### Example
    <kendo:colorPicker messages="messages">
    </kendo:colorPicker>

### opacity `boolean`

Only for the HSV selector.  If true, the widget will display the
opacity slider.  Note that currently in HTML5 the <input
type="color"> does not support opacity.

#### Example
    <kendo:colorPicker opacity="opacity">
    </kendo:colorPicker>

### palette `String`

When a non-null palette argument is supplied, the drop-down will be
a simple color picker.  The following are supported:If palette is missing or null, the widget will display the HSV
selector.

#### Example
    <kendo:colorPicker palette="palette">
    </kendo:colorPicker>

### preview `boolean`

Only for the HSV selector.  Displays the color preview element, along
with an input field where the end user can paste a color in a
CSS-supported notation.

#### Example
    <kendo:colorPicker preview="preview">
    </kendo:colorPicker>

### tileSize `float`

The size of a color cell. Further configuration is available via [kendo:colorPicker-tileSize](#kendo-colorPicker-tileSize). 

#### Example
    <kendo:colorPicker tileSize="tileSize">
    </kendo:colorPicker>

### toolIcon `String`

A CSS class name to display an icon in the color picker button.  If
specified, the HTML for the element will look like this:

#### Example
    <kendo:colorPicker toolIcon="toolIcon">
    </kendo:colorPicker>

### value `String`

The initially selected color.  This can be a string supported by
parseColor or a Color object.  Note that when initializing the
widget from an <input> element, the initial color will be decided by the
field instead.

#### Example
    <kendo:colorPicker value="value">
    </kendo:colorPicker>


##  Configuration JSP Tags

### kendo:colorPicker-tileSize

The size of a color cell.

More documentation is available at [kendo:colorPicker-tileSize](colorpicker/tilesize).

#### Example

    <kendo:colorPicker>
        <kendo:colorPicker-tileSize></kendo:colorPicker-tileSize>
    </kendo:colorPicker>


## Event Attributes

### change `String`

Fires when a color was selected, either by clicking on it (in the
simple picker), by clicking ENTER or by pressing "Apply" in the HSV
picker.

#### Example
    <kendo:colorPicker change="handle_change">
    </kendo:colorPicker>
    <script>
        function handle_change(e) {
            // Code to handle the change event.
        }
    </script>

### select `String`

Fires as a new color is displayed in the drop-down picker.  This is
not necessarily the "final" value; for example this event triggers
when the sliders in the HSV selector are dragged, but then pressing
ESC would cancel the selection and the color will revert to the
original value.

#### Example
    <kendo:colorPicker select="handle_select">
    </kendo:colorPicker>
    <script>
        function handle_select(e) {
            // Code to handle the select event.
        }
    </script>

### open `String`

Fires when the picker popup is opening.

#### Example
    <kendo:colorPicker open="handle_open">
    </kendo:colorPicker>
    <script>
        function handle_open(e) {
            // Code to handle the open event.
        }
    </script>

### close `String`

Fires when the picker popup is closing.

#### Example
    <kendo:colorPicker close="handle_close">
    </kendo:colorPicker>
    <script>
        function handle_close(e) {
            // Code to handle the close event.
        }
    </script>

## Event Tags

### kendo:colorPicker-change

Fires when a color was selected, either by clicking on it (in the
simple picker), by clicking ENTER or by pressing "Apply" in the HSV
picker.

#### Example
    <kendo:colorPicker>
        <kendo:colorPicker-change>
            <script>
                function(e) {
                    // Code to handle the change event.
                }
            </script>
        </kendo:colorPicker-change>
    </kendo:colorPicker>

### kendo:colorPicker-select

Fires as a new color is displayed in the drop-down picker.  This is
not necessarily the "final" value; for example this event triggers
when the sliders in the HSV selector are dragged, but then pressing
ESC would cancel the selection and the color will revert to the
original value.

#### Example
    <kendo:colorPicker>
        <kendo:colorPicker-select>
            <script>
                function(e) {
                    // Code to handle the select event.
                }
            </script>
        </kendo:colorPicker-select>
    </kendo:colorPicker>

### kendo:colorPicker-open

Fires when the picker popup is opening.

#### Example
    <kendo:colorPicker>
        <kendo:colorPicker-open>
            <script>
                function(e) {
                    // Code to handle the open event.
                }
            </script>
        </kendo:colorPicker-open>
    </kendo:colorPicker>

### kendo:colorPicker-close

Fires when the picker popup is closing.

#### Example
    <kendo:colorPicker>
        <kendo:colorPicker-close>
            <script>
                function(e) {
                    // Code to handle the close event.
                }
            </script>
        </kendo:colorPicker-close>
    </kendo:colorPicker>

