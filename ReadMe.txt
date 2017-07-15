All the files obtained here are included in the SD Card I received from the mananufacturer. Do note that there may be several different models of this printer. The specfic printer that I have has a excruter that does not have any fan (Marlin_fanless.zip). Then I upgraded with printer with E3D V6 extruder (Marlin_E3DV6.zip) after requesting from the manufacturer. The Arduino program and Repetier-Host programs are removed from the folder, but the versions are included in the text file.

Default 3D Printer Program
- Repetier-Host V1.0.6

Default Arduino Program
- Arduino 1.6.1

Marlin_fanless.zip contains the original source code for fanless design from the manufacturer
Marlin_E3DV6.zip contains the original source code for E3D V6 design with 3 fans from the manufacturer

Marlin_fanless_fixed_bed folder contains modified source code modified by the manufacturer to fix my scratching on print bed issue while auto leveling
Marlin_E3DV6_mod folder contains modified source code by me to fix the invert Z-Stopper issue.

I found out that the 3 fan design is redundant and replaced it with this fan design: https://www.thingiverse.com/thing:839620

Steps to replace the fanless fan extruder with E3D V6.
1. If your filament is loaded, heat up your extruder and remove the filament.
2. Power off your 3D priter completely and remove USB cable.
3. While waiting for the extruder to cool down, tighten all the screws and nuts for E3D V6. Make sure the thermostat is in place!
4. Unplug extruder stepper motor wires and the extension wires that conenct the main board with extruder.
5. Remove the semi-transparent tube that goes into extruder.
6. Remove the extruder by removing 6 screws of that hold the entire extruder structure.
7. Remove all the screws that hold the fanless extruder.
8. Remove the extruder from the metal plate.
