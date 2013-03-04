---
title:TooltipBuilder
slug:aspnetmvc-kendo.mvc.ui.fluent.tooltipbuilder
publish:true
---

# Kendo.Mvc.UI.Fluent.TooltipBuilder
Defines the fluent interface for configuring the Tooltip component.



## Methods

### For(System.String)
The selector which to match the DOM element to which the Tooltip widget will be instantiated


#### Parameters

##### selector `System.String`
jQuery selector



#### Returns



### Filter(System.String)
The selector which to match target child elements for which the Tooltip will be shown


#### Parameters

##### selector `System.String`
jQuery selector



#### Returns



### Position(Kendo.Mvc.UI.TooltipPosition)
The position (relative to the target) at which the Tooltip will be shown


#### Parameters

##### position [Kendo.Mvc.UI.TooltipPosition](/api/wrappers/aspnet-mvc/Kendo.Mvc.UI/TooltipPosition)
The position



#### Returns



### ShowAfter(System.Int32)
The inverval in milliseconds, after which the Tooltip will be shown


#### Parameters

##### milliseconds `System.Int32`




#### Returns



### Callout(System.Boolean)
Determines if callout should be visible


#### Parameters

##### show `System.Boolean`




#### Returns



### AutoHide(System.Boolean)
Determines if tooltip should be automatically hidden, or a close button should be present


#### Parameters

##### value `System.Boolean`




#### Returns



### LoadContentFrom(System.Web.Routing.RouteValueDictionary)
Sets the Url, which will be requested to return the content.

#### Example

    <%= Html.Kendo().Tooltip()
        .For("#element")
        .LoadContentFrom(MVC.Home.Index().GetRouteValueDictionary());
    %>
        


#### Parameters

##### routeValues `System.Web.Routing.RouteValueDictionary`
The route values of the Action method.




### LoadContentFrom(System.String,System.String)
Sets the Url, which will be requested to return the content.

#### Example

    <%= Html.Kendo().Tooltip()
        .For("#element")
        .LoadContentFrom("AjaxView_OpenSource", "Tooltip")
    %>
        


#### Parameters

##### actionName `System.String`
The action name.

##### controllerName `System.String`
The controller name.




### LoadContentFrom(System.String,System.String,System.Object)
Sets the Url, which will be requested to return the content.

#### Example

    <%= Html.Kendo().Tooltip()
        .For("#element")
        .LoadContentFrom("AjaxView_OpenSource", "Tooltip", new { id = 10})
    %>
        


#### Parameters

##### actionName `System.String`
The action name.

##### controllerName `System.String`
The controller name.

##### routeValues `System.Object`
Route values.




### LoadContentFrom(System.String)
Sets the Url, which will be requested to return the content.

#### Example

    <%= Html.Kendo().Tooltip()
        .For("#element")
        .LoadContentFrom(Url.Action("AjaxView_OpenSource", "Tooltip"))
    %>
        


#### Parameters

##### value `System.String`
The url.




### Content(System.String)
Sets the HTML content which the tooltip should display as a string.


#### Parameters

##### value `System.String`
The action which renders the content.




### ContentTemplateId(System.String)
Sets the id of kendo template which will be used as tooltip content.


#### Parameters

##### value `System.String`
The id of the template




### ContentHandler(System.Func\<System.Object,System.Object\>)
Sets JavaScript function which to return the content for the tooltip.




### ContentHandler(System.String)
Sets JavaScript function which to return the content for the tooltip.


#### Parameters

##### handler `System.String`
JavaScript function name




### Animation(System.Boolean)
Configures the animation effects of the window.

#### Example

    <%= Html.Kendo().Tooltip()
        .For("#element")
        .Animation(false)
        


#### Parameters

##### enable `System.Boolean`
Whether the component animation is enabled.




### Animation(System.Action\<Kendo.Mvc.UI.Fluent.PopupAnimationBuilder\>)
Configures the animation effects of the panelbar.

#### Example

    <%= Html.Kendo().Tooltip()
        .For("#element")
        .Animation(animation => animation.Expand)
        


#### Parameters

##### animationAction System.Action<[Kendo.Mvc.UI.Fluent.PopupAnimationBuilder](/api/wrappers/aspnet-mvc/Kendo.Mvc.UI.Fluent/PopupAnimationBuilder)>
The action that configures the animation.




### Width(System.Int32)
Sets the width of the tooltip.




### Height(System.Int32)
Sets the height of the tooltip.




### Deferred
Suppress initialization script rendering. Note that this options should be used in conjunction with DeferredScripts



#### Returns



### ToComponent
Returns the internal view component.



#### Returns



### Render
Renders the component.





