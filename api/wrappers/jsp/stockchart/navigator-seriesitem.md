---
title: stockChart-navigator-seriesItem
slug: jsp-stockChart-navigator-seriesItem
tags: api, java
publish: true
---

# \<kendo:stockChart-navigator-seriesItem\>

Array of series definitions.Accepts the same options as the root series collection.Omitting the array and specifying a single series is also acceptable.

#### Example
    <kendo:stockChart-navigator-series>
        <kendo:stockChart-navigator-seriesItem></kendo:stockChart-navigator-seriesItem>
    </kendo:stockChart-navigator-series>

## Configuration Attributes

### aggregate `String`

Aggregate function for date series.This function is used when a category (an year, month, etc.) contains two or more points.
The function return value is displayed instead of the individual points.

#### Example
    <kendo:stockChart-navigator-seriesItem aggregate="aggregate">
    </kendo:stockChart-navigator-seriesItem>

### axis `String`

The name of the value axis to use.** Applicable to area, column, line, ohlc and candlestick series **

#### Example
    <kendo:stockChart-navigator-seriesItem axis="axis">
    </kendo:stockChart-navigator-seriesItem>

### closeField `String`

The data field containing the close value.** Available for candlestick and ohlc series only **

#### Example
    <kendo:stockChart-navigator-seriesItem closeField="closeField">
    </kendo:stockChart-navigator-seriesItem>

### color `String`

The series base color.

#### Example
    <kendo:stockChart-navigator-seriesItem color="color">
    </kendo:stockChart-navigator-seriesItem>

### colorField `String`

The data field containing the point color.** Applicable for column, candlestick and ohlc series. **

#### Example
    <kendo:stockChart-navigator-seriesItem colorField="colorField">
    </kendo:stockChart-navigator-seriesItem>

### dashType `String`

The series line dash type.** Applicable only to line series **

#### Example
    <kendo:stockChart-navigator-seriesItem dashType="dashType">
    </kendo:stockChart-navigator-seriesItem>

### data `Object`

Array of data items. The data item type can be either a:

#### Example
    <kendo:stockChart-navigator-seriesItem data="data">
    </kendo:stockChart-navigator-seriesItem>

### downColor `String`

The series color when open value is smoller then close value.** Available for candlestick series only **

#### Example
    <kendo:stockChart-navigator-seriesItem downColor="downColor">
    </kendo:stockChart-navigator-seriesItem>

### downColorField `String`

The data field containing the body color.** Available for candlestick series only **

#### Example
    <kendo:stockChart-navigator-seriesItem downColorField="downColorField">
    </kendo:stockChart-navigator-seriesItem>

### field `String`

The data field containing the series value.

#### Example
    <kendo:stockChart-navigator-seriesItem field="field">
    </kendo:stockChart-navigator-seriesItem>

### gap `float`

The distance between category clusters.** Applicable for column, candlestick and ohlc series. **

#### Example
    <kendo:stockChart-navigator-seriesItem gap="gap">
    </kendo:stockChart-navigator-seriesItem>

### groupNameTemplate `String`

Name template for auto-generated series when binding to grouped data.Template variables:

#### Example
    <kendo:stockChart-navigator-seriesItem groupNameTemplate="groupNameTemplate">
    </kendo:stockChart-navigator-seriesItem>

### highField `String`

The data field containing the high value.** Available for candlestick and ohlc series only **

#### Example
    <kendo:stockChart-navigator-seriesItem highField="highField">
    </kendo:stockChart-navigator-seriesItem>

### line `String`

Line options.** Applicable to area, candlestick and ohlc series. ** Further configuration is available via [kendo:stockChart-navigator-seriesItem-line](#kendo-stockChart-navigator-seriesItem-line). 

#### Example
    <kendo:stockChart-navigator-seriesItem line="line">
    </kendo:stockChart-navigator-seriesItem>

### lowField `String`

The data field containing the low value.** Available for candlestick and ohlc series **

#### Example
    <kendo:stockChart-navigator-seriesItem lowField="lowField">
    </kendo:stockChart-navigator-seriesItem>

### missingValues `String`

Configures the behavior for handling missing values.** Applicable for area and line series. **

#### Example
    <kendo:stockChart-navigator-seriesItem missingValues="missingValues">
    </kendo:stockChart-navigator-seriesItem>

### name `String`

The series name visible in the legend.

#### Example
    <kendo:stockChart-navigator-seriesItem name="name">
    </kendo:stockChart-navigator-seriesItem>

### opacity `float`

The series opacity.

#### Example
    <kendo:stockChart-navigator-seriesItem opacity="opacity">
    </kendo:stockChart-navigator-seriesItem>

### openField `String`

The data field containing the open value.** Available for candlestick and ohlc series **

#### Example
    <kendo:stockChart-navigator-seriesItem openField="openField">
    </kendo:stockChart-navigator-seriesItem>

### spacing `float`

Space between points as proportion of the point width.Available for column, candlestick and ohlc series.

#### Example
    <kendo:stockChart-navigator-seriesItem spacing="spacing">
    </kendo:stockChart-navigator-seriesItem>

### stack `Object`

A value indicating if the series should be stacked.  String value indicates that the series should be stacked in a group with the specified name.
Available for column series.

#### Example
    <kendo:stockChart-navigator-seriesItem stack="stack">
    </kendo:stockChart-navigator-seriesItem>

### type `String`

The type of the series. Available types:

#### Example
    <kendo:stockChart-navigator-seriesItem type="type">
    </kendo:stockChart-navigator-seriesItem>

### width `float`

The line width.** Applicable for area and line series. **

#### Example
    <kendo:stockChart-navigator-seriesItem width="width">
    </kendo:stockChart-navigator-seriesItem>


##  Configuration JSP Tags

### kendo:stockChart-navigator-seriesItem-border

The border of the points.** Applicable to column, ohlc and candlestick series **

More documentation is available at [kendo:stockChart-navigator-seriesItem-border](stockchart/navigator-seriesitem-border).

#### Example

    <kendo:stockChart-navigator-seriesItem>
        <kendo:stockChart-navigator-seriesItem-border></kendo:stockChart-navigator-seriesItem-border>
    </kendo:stockChart-navigator-seriesItem>

### kendo:stockChart-navigator-seriesItem-highlight

Configures the appearance of highlighted points.** Applicable to candlestick and ohlc series. **

More documentation is available at [kendo:stockChart-navigator-seriesItem-highlight](stockchart/navigator-seriesitem-highlight).

#### Example

    <kendo:stockChart-navigator-seriesItem>
        <kendo:stockChart-navigator-seriesItem-highlight></kendo:stockChart-navigator-seriesItem-highlight>
    </kendo:stockChart-navigator-seriesItem>

### kendo:stockChart-navigator-seriesItem-labels

Configures the series data labels.

More documentation is available at [kendo:stockChart-navigator-seriesItem-labels](stockchart/navigator-seriesitem-labels).

#### Example

    <kendo:stockChart-navigator-seriesItem>
        <kendo:stockChart-navigator-seriesItem-labels></kendo:stockChart-navigator-seriesItem-labels>
    </kendo:stockChart-navigator-seriesItem>

### kendo:stockChart-navigator-seriesItem-line

Line options.** Applicable to area, candlestick and ohlc series. **

More documentation is available at [kendo:stockChart-navigator-seriesItem-line](stockchart/navigator-seriesitem-line).

#### Example

    <kendo:stockChart-navigator-seriesItem>
        <kendo:stockChart-navigator-seriesItem-line></kendo:stockChart-navigator-seriesItem-line>
    </kendo:stockChart-navigator-seriesItem>

### kendo:stockChart-navigator-seriesItem-markers

Marker options.** Applicable for area and line series. **

More documentation is available at [kendo:stockChart-navigator-seriesItem-markers](stockchart/navigator-seriesitem-markers).

#### Example

    <kendo:stockChart-navigator-seriesItem>
        <kendo:stockChart-navigator-seriesItem-markers></kendo:stockChart-navigator-seriesItem-markers>
    </kendo:stockChart-navigator-seriesItem>

### kendo:stockChart-navigator-seriesItem-overlay

The effects overlay.

More documentation is available at [kendo:stockChart-navigator-seriesItem-overlay](stockchart/navigator-seriesitem-overlay).

#### Example

    <kendo:stockChart-navigator-seriesItem>
        <kendo:stockChart-navigator-seriesItem-overlay></kendo:stockChart-navigator-seriesItem-overlay>
    </kendo:stockChart-navigator-seriesItem>

### kendo:stockChart-navigator-seriesItem-tooltip

The data point tooltip configuration options.

More documentation is available at [kendo:stockChart-navigator-seriesItem-tooltip](stockchart/navigator-seriesitem-tooltip).

#### Example

    <kendo:stockChart-navigator-seriesItem>
        <kendo:stockChart-navigator-seriesItem-tooltip></kendo:stockChart-navigator-seriesItem-tooltip>
    </kendo:stockChart-navigator-seriesItem>

