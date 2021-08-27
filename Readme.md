<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128571226/13.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4719)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/GraphColorizer/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/GraphColorizer/MainWindow.xaml))
<!-- default file list end -->
# How to colorize map contours loaded from Shapefiles using the Graph colorizer


<p>This example demonstrates how to paint map contours loaded from a Shapefile  (<strong>Countries.shp</strong>) using the graph colorizer. </p>


<h3>Description</h3>

<p>To accomplish this task, create a graph colorizer (the <a href="http://documentation.devexpress.com/#WPF/clsDevExpressXpfMapGraphColorizertopic"><u>GraphColorizer</u></a> object) and assign it to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapVectorLayer_Colorizertopic">VectorLayer.Colorizer</a><u> </u> property.</p>
<p>And finally, specify the desired set of colors in the <a href="http://documentation.devexpress.com/#WPF/clsDevExpressXpfChartsColorCollectiontopic"><u>ColorCollection</u></a> object that is accessed via the <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapMapColorizer_Colorstopic"><u>MapColorizer.Colors</u></a> property.</p>

<br/>


