# RayPad
RayPad is a 4-key macropad with 3 LEDs, and uses KMK firmware.

<img src="assets/assembled_raypad.JPG" width="50%" alt="assembled raypad"/>

## Features
* 4 keys
* 3 LEDs (diffuse through the case)
* Case: Main body and top cover

## CAD Model
The case has two pieces. The main body, where the PCB is placed, and the top cover which features an anime bird design. It is designed in Fusion 360.

<img src="assets/cad_open.png" width="50%" alt="RayPad CAD Main Body"/>
<img src="assets/cad_closed.png" width="50%" alt="RayPad CAD Main Body"/>
<img src="assets/cad_top.png" width="60%" alt="RayPad CAD Main Body"/>

## PCB
The PCB is designed in KiCad. It uses the Seeed Studio XIAO RP2040 microcontroller.

##### Schematic:
<img src="assets/sch.png" width="50%" alt="RayPad Schematic"/>

##### PCB:
<img src="assets/pcb.png" width="50%" alt="RayPad PCB"/>

## Firmware
The firmware is written in KMK. There are 2 layers: one for basic functions and one for changing the LED modes.

## BOM
* 4x Cherry MX Switches
* 4x DSA Keycaps
* 4x M3x16mm screws
* 4x M3x5x4 heatset inserts
* 3x SK6812MINI LED
* 1x XIAO RP2040
* 1x Case (2 printed parts)
