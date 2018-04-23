# How to: Load vector data from a KML file


<p>This example demonstrates how to load vector data from a KML file.</p>


<h3>Description</h3>

To load vector data from a KML file, do the following.<br />1. Create a&nbsp;<a href="https://documentation.devexpress.com/#XAML/clsDevExpressUIXamlMapVectorFileLayertopic">VectorFileLayer</a> object and add it&nbsp;to the&nbsp;<a href="https://documentation.devexpress.com/#XAML/DevExpressUIXamlMapMapControl_Layerstopic">MapControl.Layers</a> collection.<br />2. Create an instance of the&nbsp;<a href="https://documentation.devexpress.com/#XAML/clsDevExpressUIXamlMapKmlReadertopic">KmlReader</a> class and assign&nbsp;the instance&nbsp;to the&nbsp;<a href="https://documentation.devexpress.com/#XAML/DevExpressUIXamlMapVectorFileLayer_FileReadertopic">VectorFileLayer.FileReader</a> property.<br />3. Create&nbsp;a&nbsp;<a href="https://documentation.devexpress.com/#XAML/clsDevExpressUIXamlMapMapFileSourceBasetopic">MapFileSourceBase</a> class descendant object, configure it&nbsp;and assign to the&nbsp;<a href="https://documentation.devexpress.com/#XAML/DevExpressUIXamlMapMapFileReaderBase_FileSourcetopic">FileSource</a> property of the instance.

<br/>


