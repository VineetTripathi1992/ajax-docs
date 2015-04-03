---
title: The Wizard Labels, Legend and Titles Tab
page_title: The Wizard Labels, Legend and Titles Tab | UI for ASP.NET AJAX Documentation
description: The Wizard Labels, Legend and Titles Tab
slug: chart/understanding-radchart-ui/the-wizard-labels,-legend-and-titles-tab
tags: the,wizard,labels,,legend,and,titles,tab
published: True
position: 6
---

# The Wizard Labels, Legend and Titles Tab



>caution  __RadChart__ has been replaced by[RadHtmlChart](http://www.telerik.com/products/aspnet-ajax/html-chart.aspx), Telerik's client-side charting component.	If you are considering __RadChart__ for new development, examine the[RadHtmlChart documentation](ffd58685-7423-4c50-9554-f92c70a75138)and[online demos](http://demos.telerik.com/aspnet-ajax/htmlchart/examples/overview/defaultcs.aspx)first to see if it will fit your development needs.	If you are already using __RadChart__ in your projects, you can migrate to __RadHtmlChart__ by following these articles:[Migrating Series](2f393f28-bc31-459c-92aa-c3599785f6cc),[Migrating Axes](3f1bea81-87b9-4324-b0d2-d13131031048),[Migrating Date Axes](93226130-bc3c-4c53-862a-f9e17b2eb7dd),[Migrating Databinding](d6c5e2f1-280c-4fb0-b5b0-2f507697511d),[Feature parity](010dc716-ce38-480b-9157-572e0f140169).	Support for __RadChart__ is discontinued as of __Q3 2014__ , but the control will remain in the assembly so it can still be used.	We encourage you to use __RadHtmlChart__ for new development.
>


## 

On the __Labels, Legend and Titles__ Tab:

* __Title:__From this portion of the tab set the __Text__ for the title, toggle visibility of the title using the checkbox provided and set text direction from the drop down list. Use the __Alignment__drop down to move the title position between None, Left, Top, Bottom, Center, TopRight, TopLeft, BottomRight and BottomLeft.

* __Legend:__Unselect the Visible checkbox to hide the legend. Use the __Marker__drop down to select from a predefined list of shapes.In the example below the Rectangle shape is selected. Use the __Alignment__drop down to move the legend position between None, Left, Top, Bottom, Center, TopRight, TopLeft, BottomRight and BottomLeft. In the example below the legend is moved to the upper right corner.

>tip If you hide the legend, the extra space at the right of the screen remains. Use the PlotArea.Appearance.Dimensions.Margins to add or remove buffer space around the[plot area]({%slug chart/understanding-radchart-elements/background-and-plot-areas%}).
>


* __Series Labels__: This section lets you set label properties for a series name selected in the Series drop down list.Uncheck the __Visible__box to hide the series labels.Enter a value between 0 and 360 to the __Rotation__entry to rotate all series labels at one time.In the example below the labels are rotated 330 degrees. Positive __Rotation__ values rotate the labels clockwise, negative values rotate the labels counter-clockwise. Positive __Distance__values move the labels away from the chart series items. The example below has a distance of 60.
>caption 

![Using the Wizard Labels, Legend and Titles Tab](images/radchart-ui004.png)