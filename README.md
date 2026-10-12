It's true...
This repository is just barely set up...

I'll get to that some time.

But for now...
This is a little USB-PD board that'll give you the selected output voltage if plugged into a PD capable source that supports the chosen voltage.

# Notes:
FreeCAD's STEP export seems to have some sort of bug that occasionally causes random boolean cuts in CSG objects to act like boolean unions.  This is very weird and annoying.

My current solution (seems to work rather well...) is to go back into the project and add 0.001mm to a positional offset of the item that's being borked.
