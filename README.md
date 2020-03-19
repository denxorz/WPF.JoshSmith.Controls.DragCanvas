# WPF.JoshSmith.Controls.DragCanvas

[![Build status](https://github.com/denxorz/WPF.JoshSmith.Controls.DragCanvas/workflows/.NET%20Core/badge.svg)](https://github.com/denxorz/WPF.JoshSmith.Controls.DragCanvas/actions) [![NuGet](https://buildstats.info/nuget/WPF.JoshSmith.Controls.DragCanvas)](https://www.nuget.org/packages/WPF.JoshSmith.Controls.DragCanvas/) [![License](https://img.shields.io/badge/license-CPOL--1.02-blue)](https://github.com/denxorz/WPF.JoshSmith.Controls.DragCanvas/blob/master/LICENSE.md)


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

![DragCanvas sample gif](https://github.com/denxorz/WPF.JoshSmith.Controls.DragCanvas/raw/master/sample.gif "DragCanvas sample gif")


## Tools and Products Used

* [Microsoft Visual Studio Community](https://www.visualstudio.com)
* [Icons8](https://icons8.com/)
* [NuGet](https://www.nuget.org/)
* [GitHub](https://github.com/)


## Versions & Release Notes

version 2.0: 
 * Replace 'preview mouse down' event by a normal one, so that buttons/comboboxes/scrollbars work when put on draggable controls. Downside, these controls can no longer be dragged on themselves.
 * Replace target `net462` and `net48` by `net472`

version 1.1: 
 * Expose `IsDragInProgress`

version 1.0: 
 * First version
