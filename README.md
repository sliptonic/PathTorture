# PathTorture
This is a collection of test files for the FreeCAD Path workbench. It came from a discussion on a [Forum thread](https://forum.freecadweb.org/viewtopic.php?f=15&t=20378)  The repository has the following structure


#### rustlers
Basic test shapes.  Simple files that should always generate a shape.  

#### cutthroats
Test shapes with difficult geometry. Bsplines, ellipses, etc.

#### murderers
Test shapes with unusual characteristics other than geometry.
Position, Arrays, Clones, Panels, etc.

#### methodists
The ones that keep us up at night.  Test shapes or projects that we can't currently handle correctly.

Rustlers and cuthroats can be either FreeCAD project files (.fcstd) or shapes
(.brep, .stp, .iges)

Murderers and methodists should be only FreeCAD project files.

