# How to colorize map contours loaded from Shapefiles using the Graph colorizer


<p>This example demonstrates how to paint map contours loaded from a Shapefile  (<strong>Countries.shp</strong>) using the graph colorizer. </p>


<h3>Description</h3>

<p>To accomplish this task, create a graph colorizer (the <a href="http://documentation.devexpress.com/#WPF/clsDevExpressXpfMapGraphColorizertopic"><u>GraphColorizer</u></a> object) and assign it to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapVectorLayer_Colorizertopic">VectorLayer.Colorizer</a><u> </u> property.</p>
<p>And finally, specify the desired set of colors in the <a href="http://documentation.devexpress.com/#WPF/clsDevExpressXpfChartsColorCollectiontopic"><u>ColorCollection</u></a> object that is accessed via the <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapMapColorizer_Colorstopic"><u>MapColorizer.Colors</u></a> property.</p>

<br/>


