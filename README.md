# Flash Forge Creator Max Profile

This repository is intended to allow collaboration on the creation of a [Cura](https://ultimaker.com/software/ultimaker-cura) profile for the Creator Max printer from [FlashForge](https://flashforge.com)

## Thank you!
This repository was inspired by the [Flash forge for cura](https://github.com/eugr/Flashforge-for-Cura) project and borrows their install script and their STL file for the print bed

## Current Status
This profile is working on both extruders, and has been setup so that extruder 1 is left and 2 is right. The biggest issue right now is that the Tool change codes (`T0` or `T1`) that cura puts in the file for multi tool printers causes an error on file read.

### 

## Some notes on reading files
The creator max appears to read files with either .gcode or .g extensions. However it is important to note that if the file name is too long, the file will not open properly and the print will not start.