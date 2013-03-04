---
title:ChartPlotBandsBuilder
slug:aspnetmvc-kendo.mvc.ui.fluent.chartplotbandsbuilder
publish:true
---

# Kendo.Mvc.UI.Fluent.ChartPlotBandsBuilder
Defines the fluent interface for configuring plot band.



## Methods

### From(T)
Sets the plot band start position.

#### Example

    <% Html.Kendo().Chart()
        .Name("Chart")
        .CategoryAxis(axis => axis
        .PlotBands(plotBands => plotBands
        .Add().From(1).Color("Red");
        )
        )
        .Render();
    %>
        


#### Parameters

##### from `T`
The plot band start position.




### To(T)
Sets the plot band end position.

#### Example

    <% Html.Kendo().Chart()
        .Name("Chart")
        .CategoryAxis(axis => axis
        .PlotBands(plotBands => plotBands
        .Add().To(2).Color("Red");
        )
        )
        .Render();
    %>
        


#### Parameters

##### to `T`
The plot band end position.




### Color(System.String)
Sets the plot band background color

#### Example

    <% Html.Kendo().Chart()
        .Name("Chart")
        .CategoryAxis(axis => axis
        .PlotBands(plotBands => plotBands
        .Add().Color("Red");
        )
        )
        .Render();
    %>
        


#### Parameters

##### color `System.String`
The plot band background color.




### Opacity(System.Double)
Sets the plot band opacity

#### Example

    <% Html.Kendo().Chart()
        .Name("Chart")
        .CategoryAxis(axis => axis
        .PlotBands(plotBands => plotBands
        .Add().Opacity(0.5);
        )
        )
        .Render();
    %>
        


#### Parameters

##### opacity `System.Double`
The plot band opacity.





