Hello Morpheus Bottom board Repository
===
905-00005-B
Bottom board -
Why changed- in order to fix problems we found during initial production, minor board changes are being made to give additional clearance around the screw holes to ensure we don't have mechanical conflicts or shorts with the screw bosses. This includes making minor changes to component placement for a very small number of devices. ...
What changed- 
1. 4 vias around TP6 (3.3V) moved right-handed to avoid H2 clearance around the screw. This includes slightly expanding the 3.3V plane on the bottom side.
2. C3 rotated 45 degree to avoid H2 clearance around the screw. Added a ground via on top of the GND node of the switcher cap to enhance the noise guarding.
3. LED1 rotates 45 degree to avoid H3 clearance around the screw. This includes moving R5 footprint and H3 adjacent traces.
4. Move the position of both Test point DOUT and DIN to avoid flex connector clearance. 
5. Created a flex connector P3 footprint.
6. Slight move TP1.8v to the right to avoid H4 clearance around the screw.
7. Rout the gnd via of U3 by ground layer trace.