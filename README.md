# OpenStreetMap Sample for WinForms
OpenStreetMap (OSM) is a collaborative project to create free geographic data for the entire world. It can be thought of the “Free Wiki World Map”. Now, the latest version of MapSuite Desktop can support that. In order to run this project, you will need the development build 10.0.0.0 or later.

![Screenshot](https://raw.githubusercontent.com/howardchn/Sample-OpenStreetMap-WLM/master/OpenStreetMap/Resources/Screenshot.jpg)

## Using code
The first thing is to set the `winformsMap.MapUnit` to `GeographyUnit.Meter`. Then you can add OpenStreetMap with the following code. 
```csharp
OpenStreetMapOverlay osmOvelerlay = new OpenStreetMapOverlay();
winformsMap.Overlays.Add(osmOvelerlay);
```

After the Open Street Map is added to winformsMap, call `winformsMap.Refresh()` method to make it paint on the component.

