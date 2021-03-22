# Cura_Anycubic_MegaS_Profile
 Printer Profile for Mega Printers with Knutwurst
 
## Installation
Download the files and move the files to the Cura installation folders like C:\Program Files\Ultimaker Cura 4.8.0\resources. Under windows you can also use the AppData folder within your profile like C:\Users\<Username>\AppData\Roaming\cura\4.8

## What this printer profile does?
I created this printer profile because the one contained in Cura 4.8 does not support central settings. The standard dependency in Cura is Printer Settings -> Material Settings -> Quality Settings. So I moved every configuration to the printer.

To enable every setting in the materials you can install this plugin: https://marketplace.ultimaker.com/app/cura/plugins/fieldofview/MaterialSettingsPlugin

## Notes
 * enhanced Top/Bottom Layer calculation based on the thickness of the "Layer height" and "Initial Layer Height"
 * set Tree support as standard
 * if tree support is enabled it has to touch build plate automatically
 * "Printing Temperature Initial Layer" is set 10 C° higher that "Printing Temperature" of not set from materials
 * "Speed" settings are calculated automatically from "Print Speed"
 * If "Travel Speed" is higher than 150mm/s a warning occurs
 * Combining is initially off
 * If support is enabled "Build Plate Adhesion Type" will be set to none as no Skirt will be printed