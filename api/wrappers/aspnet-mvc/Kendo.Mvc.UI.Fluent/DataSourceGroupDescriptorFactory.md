---
title:DataSourceGroupDescriptorFactory
slug:aspnetmvc-kendo.mvc.ui.fluent.datasourcegroupdescriptorfactory
publish:true
---

# Kendo.Mvc.UI.Fluent.DataSourceGroupDescriptorFactory
Defines the fluent interface for configuring group.



## Methods

### AddT1(System.Linq.Expressions.Expression\<System.Func\<T,T1\>\>)
Specifies the member by which the data should be grouped.


#### Parameters

##### expression `System.Linq.Expressions.Expression<System.Func<T,T1>>`
Member access expression which describes the member




### AddT1(System.String)
Specifies the member by which the data should be grouped.


#### Parameters

##### memberName `System.String`
Member name




### Add(System.String,System.Type)
Specifies the member by which the data should be grouped.


#### Parameters

##### memberName `System.String`
Member name

##### memberType `System.Type`
Member type




### Add(System.String,System.Type,System.ComponentModel.ListSortDirection)
Specifies the member by which the data should be grouped.


#### Parameters

##### memberName `System.String`
Member name

##### memberType `System.Type`
Member type

##### sortDirection `System.ComponentModel.ListSortDirection`
Sort order




### AddT1(System.String,System.ComponentModel.ListSortDirection)
Specifies the member by which the data should be grouped.


#### Parameters

##### memberName `System.String`
Member type

##### sortDirection `System.ComponentModel.ListSortDirection`
Sort order



#### Returns



### AddDescendingT1(System.Linq.Expressions.Expression\<System.Func\<T,T1\>\>)
Specifies the member by which the data should be sorted in descending order and grouped.


#### Parameters

##### expression `System.Linq.Expressions.Expression<System.Func<T,T1>>`
Member access expression which describes the member




### AddDescendingT1(System.String)
Specifies the member by which the data should be sorted in descending order and grouped.


#### Parameters

##### memberName `System.String`
Member name




### AddDescending(System.String,System.Type)
Specifies the member by which the data should be sorted in descending order and grouped.


#### Parameters

##### memberName `System.String`
Member name

##### memberType `System.Type`
Member type





