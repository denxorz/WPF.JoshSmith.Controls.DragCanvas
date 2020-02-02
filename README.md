# WPF.JoshSmith.Controls.DragCanvas

![Build status](https://github.com/denxorz/WPF.JoshSmith.Controls.DragCanvas/workflows/.NET%20Core/badge.svg) [![NuGet](https://buildstats.info/nuget/WPF.JoshSmith.Controls.DragCanvas)](https://www.nuget.org/packages/WPF.JoshSmith.Controls.DragCanvas/) [![License](http://img.shields.io/:license-mit-blue.svg)](https://github.com/denxorz/WPF.JoshSmith.Controls.DragCanvas/blob/master/LICENSE)

## What does it do?
A Canvas which manages dragging of the UIElements it contains. This Canvas is made by Josh Smith.

This package is based on the following articles: 

* https://www.codeproject.com/Articles/15354/Dragging-Elements-in-a-Canvas

## Examples

```C#
<jas:DragCanvas>
  <TextBlock Canvas.Left="20" Canvas.Bottom="50" Text="example"/>
  <Ellipse Canvas.Left="100" Canvas.Bottom="30" Width="65" Height="70" Fill="Blue" />
</jas:DragCanvas>
```

## Tools and Products Used

* [Microsoft Visual Studio Community](https://www.visualstudio.com)
* [Icons8](https://icons8.com/)
* [NuGet](https://www.nuget.org/)
* [GitHub](https://github.com/)


## Versions & Release Notes

version 1.1: Expose `IsDragInProgress`
version 1.0: First version
