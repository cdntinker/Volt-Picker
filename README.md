This is a little USB-PD board that'll give you the selected output voltage if plugged into a PD capable source that supports the chosen voltage.

![rev: 3.0.0](/pix/Volt-Picker.png)

# Theory:
One of the main design criteria is that it does NOT require an MCU to manage it.

Voltage & Current are chosen by soldering a jumper for each.  (The basic circuit can easily be embeded into a board with just a single resistor for each...)

# Rant/Snark:
* Volt-Picker 1.tar.gz:
  * My original design idea
  * Based on the CH224 from Nanjing Qinheng Microelectronics Co., Ltd. (WCH)
  * chip seems to have been disontinued...
* Volt-Picker 2.tar.gz
  * New design based on the AP33771 from Diodes Incorporated
  * Apparently, this has been replaced by the AP33771C
  * But nobody has stock yet...
* This is now rev 3.0.0
  * Based on the AP33771C
  * Will it be the penultimate verion?
  * Only time will tell if there's a need for a rev 4...

# Notes:
FreeCAD's STEP export seems to have some sort of bug that occasionally causes random boolean cuts in CSG objects to act like boolean unions.  This is very weird and annoying.

My current solution (seems to work rather well...) is to go back into the project and add 0.001mm to a positional offset of the item that's being borked.
