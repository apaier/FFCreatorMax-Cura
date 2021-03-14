# Flash Forge Creator Max Profile

This repository is intended to allow collaboration on the creation of a [Cura](https://ultimaker.com/software/ultimaker-cura) profile for the Creator Max printer from [FlashForge](https://flashforge.com)

## Current Status
The profile will work if you install it, however the generated code will have a tool entry of `T0` or `T1` right after the intial comments that will cause an error if not removed. It is unclear why this is happenig at this time.

You do not have to disable extruders to use this profile. 

## Some notes on reading files
The creator max appears to read files with either .gcode or .g extensions. However it is important to note that if the file name is too long, the file will not open properly and the print will not start.