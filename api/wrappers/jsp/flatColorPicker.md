---
title: flatColorPicker
slug: jsp-flatColorPicker
tags: api, java
publish: true
---

# \<kendo:flatColorPicker\>
A JSP tag representing Kendo FlatColorPicker.

## Configuration Attributes

### buttons `boolean`

Specifies whether we should display the Apply / Cancel buttons.

#### Example
    <kendo:flatColorPicker buttons="buttons">
    </kendo:flatColorPicker>

### messages `Object`

Allows customization of "Apply" / "Cancel" labels.

#### Example
    <kendo:flatColorPicker messages="messages">
    </kendo:flatColorPicker>

### opacity `boolean`

Specifies whether we should display the opacity slider to allow
selection of transparency.

#### Example
    <kendo:flatColorPicker opacity="opacity">
    </kendo:flatColorPicker>

### preview `boolean`

Specifies whether we should display the preview bar which displays the
current color and the input field.

#### Example
    <kendo:flatColorPicker preview="preview">
    </kendo:flatColorPicker>

### value `String`

Specifies the initially selected color.

#### Example
    <kendo:flatColorPicker value="value">
    </kendo:flatColorPicker>


## Event Attributes

### change `String`

Triggers when a new color has been selected.

#### Example
    <kendo:flatColorPicker change="handle_change">
    </kendo:flatColorPicker>
    <script>
        function handle_change(e) {
            // Code to handle the change event.
        }
    </script>

## Event Tags

### kendo:flatColorPicker-change

Triggers when a new color has been selected.

#### Example
    <kendo:flatColorPicker>
        <kendo:flatColorPicker-change>
            <script>
                function(e) {
                    // Code to handle the change event.
                }
            </script>
        </kendo:flatColorPicker-change>
    </kendo:flatColorPicker>

