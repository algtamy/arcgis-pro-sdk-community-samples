## Styling-with-ArcGIS-Pro

<!-- TODO: Write a brief abstract explaining this sample -->
This sample demonstrates how to create UI elements in your Add-in that have the ArcGIS Pro "look and feel".      
Xaml code for buttons, check boxes, DataGrids, TextBlock styles can be obtained from this sample.   
  


<a href="http://pro.arcgis.com/en/pro-app/sdk/" target="_blank">View it live</a>

<!-- TODO: Fill this section below with metadata about this sample-->
```
Language:              C#
Subject:               Framework
Contributor:           ArcGIS Pro SDK Team <arcgisprosdk@esri.com>
Organization:          Esri, http://www.esri.com
Date:                  6/27/2019
ArcGIS Pro:            2.4
Visual Studio:         2015, 2017
.NET Target Framework: 4.6.1
```

## Resources

* [API Reference online](https://pro.arcgis.com/en/pro-app/sdk/api-reference)
* <a href="https://pro.arcgis.com/en/pro-app/sdk/" target="_blank">ArcGIS Pro SDK for .NET (pro.arcgis.com)</a>
* [arcgis-pro-sdk-community-samples](https://github.com/Esri/arcgis-pro-sdk-community-samples)
* [ArcGIS Pro DAML ID Reference](https://github.com/Esri/arcgis-pro-sdk/wiki/ArcGIS-Pro-DAML-ID-Reference)
* [FAQ](https://github.com/Esri/arcgis-pro-sdk/wiki/FAQ)
* [ArcGIS Pro SDK icons](https://github.com/Esri/arcgis-pro-sdk/releases/tag/2.4.0.19948)

![ArcGIS Pro SDK for .NET Icons](https://Esri.github.io/arcgis-pro-sdk/images/Home/Image-of-icons.png  "ArcGIS Pro SDK Icons")

### Samples Data

* Sample data for ArcGIS Pro SDK Community Samples can be downloaded from the [repo releases](https://github.com/Esri/arcgis-pro-sdk-community-samples/releases) page.  

## How to use the sample
<!-- TODO: Explain how this sample can be used. To use images in this section, create the image file in your sample project's screenshots folder. Use relative url to link to this image using this syntax: ![My sample Image](FacePage/SampleImage.png) -->
1. In Visual Studio click the Build menu. Then select Build Solution.  
1. This solution is using the AvalonEdit and Extended.Wpf.Toolkit Nugets. If needed, you can install the Nugets from the "Nuget Package Manager Console" by using this script: "Install-Package AvalonEdit" and "Install-Package Extended.Wpf.Toolkit".  
1. Click Start button to open ArcGIS Pro.  
1. ArcGIS Pro will open. Click on the new UI Design tab created by this add-in. Four buttons are created on the ribbon in an ArcGIS Pro UI Design group - Control Styles, TextBlock Styles, Backstage Styles and ProWindow Styles.   
![UI](screenshots/UIDesign.png)  
  
1. Control Styles button: Clicking this button launches the ArcGIS Pro Control Styles dockpane. Select the control you are interested in to view its available styles. You can then click on the Copy button next to the Xaml code for that style to paste into your add-in.  
![Controls](screenshots/controls.png)  
  
1. TextBlock Styles button: Clicking this button launches the ArcGIS Pro TextBlock Styles dockpane. You can see the various TextBlock styles available with Pro.  
![TextBlock](screenshots/TextBlock.png)  
  
1. Backstage Styles button: Clicking this button will launch a Backstage page that lists the backstage TextBlock styles provided in Pro.  
![Backstage](screenshots/Backstage.png)  
  
1. ProWindow Styles button: Clicking this button will launch a ProWindow that lists the dialog TextBlock styles provided in Pro.  
![ProWindow](screenshots/ProWindow.png)  
  
1. Make sure when working with styles that your look and feel supports the ArcGIS Pro Dark Theme as well as the Default Theme.  
  


<!-- End -->

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://esri.github.io/arcgis-pro-sdk/images/ArcGISPro.png"  alt="ArcGIS Pro SDK for Microsoft .NET Framework" height = "20" width = "20" align="top"  >
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[Home](https://github.com/Esri/arcgis-pro-sdk/wiki) | <a href="https://pro.arcgis.com/en/pro-app/sdk/api-reference" target="_blank">API Reference</a> | [Requirements](https://github.com/Esri/arcgis-pro-sdk/wiki#requirements) | [Download](https://github.com/Esri/arcgis-pro-sdk/wiki#installing-arcgis-pro-sdk-for-net) | <a href="https://github.com/esri/arcgis-pro-sdk-community-samples" target="_blank">Samples</a>
