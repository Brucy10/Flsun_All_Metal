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
