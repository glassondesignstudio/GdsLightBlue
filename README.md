# GdsLightBlue Preference Pack

This repository contains the source code for a FreeCAD Preference Pack called GdsLightBlue. The GdsLightBlue stylesheet is an adaptive stylesheet that is based upon the standard FreeCAD stylsheet Light-blue.

See the [Release Notes](./ReleaseNotes.md) for more details on the changes and new features for each release.

## Why is special about this stylesheet?

This stylesheet was developed because videos published on the GlassonDesignStudio YouTube channel were recorded at 4K resolution but the existing FreeCAD stylesheets did not support this resolution very well. The standard stylesheets are typically pixel based which does not allow them to scale up to make ensure visibility when the screen resolution increases. The standard stylesheet Light-blue has been modified so that it adapts more easily to higher resolution displays.

## Known Issues and Notes
1. This preference pack is a work in progress. There are numerous stylesheet errors that require fixing and they will get fixed in time.
1. This preference pack uses a hardcoded font size of 25px as the basis of it's styling. This is due to having to work with two monitors of different resolutions in my use case. My intention is to remove this limitation as soon as possible while still being able to perform my work.

## Installation into Flatpak version of FreeCAD on Linux

At this time there is no automatic installation process for the Preference Pack and stylesheet so it must be performed manually using the following steps:

1. Open a command sheel
1. Change into the FreeCAD module directory
   ```cd $HOME/.var/app/.org.freecadweb.FreeCAD/data/FreeCAD/Mod```
1. Clone the repository using git
   ```git clone https://github.com/glassondesignstudio/FreeCAD-stylesheet.git```

## Setting as default stylesheet

1. Start FreeCAD
1. Edit preferences
1. Set stylesheet to GdsLightBlue
1. Apply the GdsLightBlue preference pack
1. Click the OK button

