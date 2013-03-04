---
title: tooltip
slug: jsp-tooltip
tags: api, java
publish: true
---

# \<kendo:tooltip\>
A JSP tag representing Kendo Tooltip.

## Configuration Attributes

### autoHide `boolean`

Specifies if the tooltip will be hidden when mouse leaves the target element. If set to false a close button will be shown within tooltip.

#### Example
    <kendo:tooltip autoHide="autoHide">
    </kendo:tooltip>

### callout `boolean`

Specifies if the tooltip callout will be displayed.

#### Example
    <kendo:tooltip callout="callout">
    </kendo:tooltip>

### filter `String`

Specifies a selector for elements, within the container, for which the tooltip will be displayed.

#### Example
    <kendo:tooltip filter="filter">
    </kendo:tooltip>

### height `float`

The height (in pixels) of the tooltip.

#### Example
    <kendo:tooltip height="height">
    </kendo:tooltip>

### iframe `boolean`

Explicitly states whether content iframe should be created.

#### Example
    <kendo:tooltip iframe="iframe">
    </kendo:tooltip>

### position `String`

The position relative to the target element, at which the tooltip will be shown. Predefined values are "bottom", "top", "left", "right", "center".

#### Example
    <kendo:tooltip position="position">
    </kendo:tooltip>

### showAfter `float`

Specify the delay in milliseconds before the tooltip is shown. This option is ignored if showOn is set to "click" or "focus".

#### Example
    <kendo:tooltip showAfter="showAfter">
    </kendo:tooltip>

### showOn `String`

The event on which the tooltip will be shown. Predefined values are "mouseenter", "click" and "focus".

#### Example
    <kendo:tooltip showOn="showOn">
    </kendo:tooltip>

### width `float`

The width (in pixels) of the tooltip.

#### Example
    <kendo:tooltip width="width">
    </kendo:tooltip>


##  Configuration JSP Tags

### kendo:tooltip-animation

A collection of {Animation} objects, used to change default animations. A value of false
will disable all animations in the widget.

More documentation is available at [kendo:tooltip-animation](tooltip/animation).

#### Example

    <kendo:tooltip>
        <kendo:tooltip-animation></kendo:tooltip-animation>
    </kendo:tooltip>


## Event Attributes

### contentLoad `String`

Triggered when an AJAX request for content completes.

#### Example
    <kendo:tooltip contentLoad="handle_contentLoad">
    </kendo:tooltip>
    <script>
        function handle_contentLoad(e) {
            // Code to handle the contentLoad event.
        }
    </script>

### show `String`

Triggered when a Tooltip is shown.

#### Example
    <kendo:tooltip show="handle_show">
    </kendo:tooltip>
    <script>
        function handle_show(e) {
            // Code to handle the show event.
        }
    </script>

### hide `String`

Triggered when a Tooltip is hidden

#### Example
    <kendo:tooltip hide="handle_hide">
    </kendo:tooltip>
    <script>
        function handle_hide(e) {
            // Code to handle the hide event.
        }
    </script>

### requestStart `String`

Triggered before an AJAX request started.

#### Example
    <kendo:tooltip requestStart="handle_requestStart">
    </kendo:tooltip>
    <script>
        function handle_requestStart(e) {
            // Code to handle the requestStart event.
        }
    </script>

### error `String`

Triggered when an AJAX request for content fails.

#### Example
    <kendo:tooltip error="handle_error">
    </kendo:tooltip>
    <script>
        function handle_error(e) {
            // Code to handle the error event.
        }
    </script>

## Event Tags

### kendo:tooltip-contentLoad

Triggered when an AJAX request for content completes.

#### Example
    <kendo:tooltip>
        <kendo:tooltip-contentLoad>
            <script>
                function(e) {
                    // Code to handle the contentLoad event.
                }
            </script>
        </kendo:tooltip-contentLoad>
    </kendo:tooltip>

### kendo:tooltip-show

Triggered when a Tooltip is shown.

#### Example
    <kendo:tooltip>
        <kendo:tooltip-show>
            <script>
                function(e) {
                    // Code to handle the show event.
                }
            </script>
        </kendo:tooltip-show>
    </kendo:tooltip>

### kendo:tooltip-hide

Triggered when a Tooltip is hidden

#### Example
    <kendo:tooltip>
        <kendo:tooltip-hide>
            <script>
                function(e) {
                    // Code to handle the hide event.
                }
            </script>
        </kendo:tooltip-hide>
    </kendo:tooltip>

### kendo:tooltip-requestStart

Triggered before an AJAX request started.

#### Example
    <kendo:tooltip>
        <kendo:tooltip-requestStart>
            <script>
                function(e) {
                    // Code to handle the requestStart event.
                }
            </script>
        </kendo:tooltip-requestStart>
    </kendo:tooltip>

### kendo:tooltip-error

Triggered when an AJAX request for content fails.

#### Example
    <kendo:tooltip>
        <kendo:tooltip-error>
            <script>
                function(e) {
                    // Code to handle the error event.
                }
            </script>
        </kendo:tooltip-error>
    </kendo:tooltip>

