# ESP32 Dual H Bridge Breakout Board

This project is for an ESP32 Breakout board that was designed to be the brains of your next robot. The features of this board are;

Can accommodate any ESP32 dev kit that has two rows of up to twenty pins on one inch centers.
A place to mount a TB6612FNG dual H bridge DC motor controller daughter board.
A two screw terminal block for each motor connection.
A two screw terminal block and a set of five header pins for Vin & Gnd
Two rows of twenty GPIO breakout pins.
Headers for two HC-SR04 Sonar sensors, with voltage dividers on the Echo output.
A header for connecting to a tri-color, common anode, LED with limiting resistors.
On board 5V, 1A voltage regulator with five header pins for 5V & Gnd.
Four sets of headers for I2C connections with 3.3V & Gnd for each connection.
All components mount on one side of the circuit board.
The physical size of the board is 90mm x 56mm, two sided. This puts it well within the 100mm x 100mm size limits for most board makers low cost prototypes.

The board was designed around the DOIT ESP32 DEVKIT V1 which has two rows of eighteen pins each. Easily cut traces on the backside of the board allow you to separate the dedicated 5V, Gnd and 3.3V pins from their respective buses. Then you can use the pins in these locations as GPIO and using jumpers, connect the 5V, Gnd and 3.3V buses to the appropriate pins on the ESP32 dev kit that you are using.

The board was created using Kicad Ver 4.0.7.

## The files
ESP32_Robot_Bd.zip - This is all of the files needed to have the board fabricated. Send this file to your board manufacturer.
ESP32_Robot_Bd.kicad.pcb   - This is the kicad pcb file.
ESP32_Robot_Bd.net         - This is the kicad generated net file for the pcb.
ESP32_Robot_Bd.pdf         - This is a pdf version of the schematic.
ESP32_Robot_Bd.pro         - This is the kicad project.
ESP32_Robot_Bd.sch         - This is the kicad schematic.
ESP32_Robot_Bd-cache.lib   - This is the cached library. It has any custom library parts.

