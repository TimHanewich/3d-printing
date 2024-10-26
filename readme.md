# 3D Printing Notes
This repo is meant to be a notepad for me as I jot down tips/tricks I learned while 3D printing.

## My Cura Profiles
My Cura profiles can be found in [the cura_profiles folder](./cura_profiles/).

## Ensuring Quality Prints
- Routine - should be done often (before every print or every 2/3 prints)
    - Remove bed plate, rub down with rubbing alcohol on towel.
    - Bed level
- Non-routine - only as needed
    - Unclog nozzle with needle
    - Replace nozzle if damaged
    - Extruder driver gear may be full of PLA flakes if PLA was removed and added repeatedly. Need to take this apart and clean with tooth brush to ensure the driver gear can "grip" the PLA filament and push it through the nozzle.
- Other tips
    - When removing PLA filament to do something like change colors, be sure to disable stepper motors.

## Noteable Models
- Metric nuts and screws: https://www.thingiverse.com/thing:3259952
    - The `Cylinderhead_screw_M6` model from [this](https://www.thingiverse.com/thing:3259952) post is **10x10mm**. If you would like to build a thread *into* another object that you can then screw this screw into, enlarge the screw to **12x12mm**. This provides enough room for the screw to fit into. Not enlarging the screw means the hole is not large enough to fit in.