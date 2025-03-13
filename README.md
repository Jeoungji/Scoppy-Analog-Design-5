# Scoppy
### Raspberry Pi Pico Osilloscope
### Analog-Design-5
https://github.com/fhdm-dev/scoppy/discussions/63
https://youtu.be/VVi2ylpizq4

#### Logic analysis GPIO pins must be modified
- The logic analysis GPIO pins must be set from GP2 to GP9.
- Any overlapping pins should be reassigned to other unused pins.
- The TRIG pin is not an input.


![Case](Image/Case.PNG)


|![PCB_2d](Image/PCB_2D.PNG)|![PCB_2d_2](Image/PCB_2D_2.PNG)|
|---|---|
|![PCB_3D](Image/PCB_3D.PNG)|![PCB_CAD](Image/PCB_CAD.PNG)|


## BOM
|Component Type|Specification|Footprint/Package|Quantity|
|---|---|---|---|
|Ceramic Capacitor|100nF|CAP-TH_BD5.0-P2.00-D0.5-FD|1EA|
|Electrolytic Capacitor|10uF|CAP-TH_L5.0-W3.2-P5.00-D0.5|2EA|
|Pin Header Socket|2.54_1X2|HDR-F-2.54_1X2|2EA|
|Pin Header Socket|2.54_1X2|HDR-F-2.54_1X20|2EA|
|Pin Header Socket|2.54_1X2|HDR-F-2.54_2X10|1EA|
|Diode|1N4148| |4EA
|resistance|470k| |4EA|
|resistance|220| |2EA|
|resistance|100| |2EA|
|OP-Amp|MCP6002|PDIP-8|1EA|
|Hex Socket Bolt|M3-8mm| |4EA|
|Hex Socket Bolt|M2-10mm| |4EA|

