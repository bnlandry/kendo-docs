---
title: chart-legend
slug: jsp-chart-legend
tags: api, java
publish: true
---

# \<kendo:chart-legend\>

The chart legend configuration options.

#### Example
    <kendo:chart>
        <kendo:chart-legend></kendo:chart-legend>
    </kendo:chart>

## Configuration Attributes

### background `String`

The background color of the legend. Any valid CSS color string will work here, including hex and rgb.

#### Example
    <kendo:chart-legend background="background">
    </kendo:chart-legend>

### margin `Object`

The margin of the legend.

#### Example
    <kendo:chart-legend margin="margin">
    </kendo:chart-legend>

### offsetX `float`

The X offset from its position.  The offset is relative to the current position of the legend.
For instance, a value of 20 will move the legend 20 pixels to the right of it's initial position.  A negative value will move the legend
to the left of the current position.

#### Example
    <kendo:chart-legend offsetX="offsetX">
    </kendo:chart-legend>

### offsetY `float`

The Y offset from its position.  The offset is relative to the current position of the legend.
For instance, a value of 20 will move the legend 20 pixels down from it's initial position.  A negative value will move the legend
upwards from the current position.

#### Example
    <kendo:chart-legend offsetY="offsetY">
    </kendo:chart-legend>

### padding `Object`

The padding of the legend.

#### Example
    <kendo:chart-legend padding="padding">
    </kendo:chart-legend>

### position `String`

The positions of the legend.

#### Example
    <kendo:chart-legend position="position">
    </kendo:chart-legend>

### visible `boolean`

The visibility of the legend.

#### Example
    <kendo:chart-legend visible="visible">
    </kendo:chart-legend>


##  Configuration JSP Tags

### kendo:chart-legend-border

The border of the legend.

More documentation is available at [kendo:chart-legend-border](chart/legend-border).

#### Example

    <kendo:chart-legend>
        <kendo:chart-legend-border></kendo:chart-legend-border>
    </kendo:chart-legend>

### kendo:chart-legend-labels

Configures the legend labels.

More documentation is available at [kendo:chart-legend-labels](chart/legend-labels).

#### Example

    <kendo:chart-legend>
        <kendo:chart-legend-labels></kendo:chart-legend-labels>
    </kendo:chart-legend>

