# FreeCAD-stylesheet

This repository contains the source code for a FreeCAD stylesheet Preference Pack called SkyBlue. The SkyBlue stylesheet is an adaptive stylesheet that is based upon the standard FreeCAD stylsheet Light-blue.

## Why is special about this stylesheet?

This stylesheet was developed because videos published on the GlassonDesignStudio YouTube channel were recorded at 4K resolution but the existing FreeCAD stylesheets did not support this resolution very well.

The standard stylesheets are typically pixel based which does not allow them to scale up to make ensure visibility when the screen resolution increases. The standard stylesheet Light-blue has been modified so that it adapts more easily to higher resolution displays.

## Installation into Flatpak version of FreeCAD on Linux

1. Close the repository using git
2. Copy GDS-Light-blue.qss to $HOME/.var/app/org.freecadweb.FreeCAD/data/FreeCAD/Gui/Stylesheets/

## Setting as default stylesheet

1. Start FreeCAD
2. Edit preferences
3. Set stylesheet to GDS-Light-blue
4. Apply changes

