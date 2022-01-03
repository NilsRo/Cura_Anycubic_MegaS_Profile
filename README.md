# Cura Anycubic MegaS Profile
Printer Profile for Mega Printers (Standard, S, Pro) and now also X
 
## Installation
Download the files and move the files to the Cura installation folders like C:\Program Files\Ultimaker Cura 4.8.0\resources. Under windows you can also use the AppData folder within your profile like C:\Users\<Username>\AppData\Roaming\cura\4.8
Profiles are integrated in Cura 4.10 and newer by default.

## What this printer profile does?
I created this printer profile because the one contained in Cura 4.8 does not support central settings. The standard dependency in Cura is Printer Settings -> Material Settings -> Quality Settings. So I moved every configuration to the printer.

To enable every setting in the materials you can install this plugin: https://marketplace.ultimaker.com/app/cura/plugins/fieldofview/MaterialSettingsPlugin

## Notes
 * Enhanced Top/Bottom Layer calculation based on the thickness of the "Layer height" and "Initial Layer Height"
 * Set Tree support as standard
 * If tree support is enabled it has to touch build plate automatically
 * "Printing Temperature Initial Layer" is set 10 C° higher that "Printing Temperature" if not set from materials
 * "Speed" settings are derived from "Print Speed"
 * If "Travel Speed" is higher than 150mm/s a warning occurs
 * Combining is initially off
 * If support is enabled "Build Plate Adhesion Type" will be set to none so no Skirt will be printed
 * GCode Start script is changed to support initial print and bed temperatures (parallel heatup)
 * Set retraction speed to 25 as this is the max. firmware setting. Maximum value constraint to 40, but has to be enabled in firmware.
 * Support for additional metadata for OctoPrint-Slicer Print Time Estimator https://github.com/NilsRo/OctoPrint-SlicerEstimator