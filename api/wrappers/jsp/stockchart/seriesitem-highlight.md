---
title: stockChart-seriesItem-highlight
slug: jsp-stockChart-seriesItem-highlight
tags: api, java
publish: true
---

# \<kendo:stockChart-seriesItem-highlight\>

Configures the appearance of highlighted points.** Applicable to candlestick and ohlc series. **

#### Example
    <kendo:stockChart-seriesItem>
        <kendo:stockChart-seriesItem-highlight></kendo:stockChart-seriesItem-highlight>
    </kendo:stockChart-seriesItem>

## Configuration Attributes

### color `String`

The highlight color.** Available only for pie series **

#### Example
    <kendo:stockChart-seriesItem-highlight color="color">
    </kendo:stockChart-seriesItem-highlight>

### opacity `float`

The opacity of the highlighted points.

#### Example
    <kendo:stockChart-seriesItem-highlight opacity="opacity">
    </kendo:stockChart-seriesItem-highlight>


##  Configuration JSP Tags

### kendo:stockChart-seriesItem-highlight-border

The border of highlighted points. The color is computed automatically from the base point color.

More documentation is available at [kendo:stockChart-seriesItem-highlight-border](stockchart/seriesitem-highlight-border).

#### Example

    <kendo:stockChart-seriesItem-highlight>
        <kendo:stockChart-seriesItem-highlight-border></kendo:stockChart-seriesItem-highlight-border>
    </kendo:stockChart-seriesItem-highlight>

### kendo:stockChart-seriesItem-highlight-line

Line options for highlighted points. The color is computed automatically from the base point color.** Available only for candlestick series **

More documentation is available at [kendo:stockChart-seriesItem-highlight-line](stockchart/seriesitem-highlight-line).

#### Example

    <kendo:stockChart-seriesItem-highlight>
        <kendo:stockChart-seriesItem-highlight-line></kendo:stockChart-seriesItem-highlight-line>
    </kendo:stockChart-seriesItem-highlight>

