# PathTorture
This is a collection of test files for the FreeCAD Path workbench.  The repository has the following structure

####  root directory contains the FreeCAD project source files

#### rustlers:  Basic test shapes.  Simple files that should always generate a
shape.  

#### cutthroats:  Test shapes with difficult geometry. Bsplines, ellipses, etc.

#### murderers: Test shapes with unusual characteristics other than geometry.
Position, Arrays, Panels, etc.

#### methodists:  Test shapes or projects that we can't currently handle
correctly.

Rustlers and cuthroats can be either FreeCAD project files (.fcstd) or shapes
(.brep, .stp, .iges)

Murderers and methodists should be only FreeCAD project files.

