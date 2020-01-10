This fantastic case has been contributed by '''Nicolai Demidenko'''.
It's designed for RBPi4 + Zynscreen, but include lot of customizations that improves the basic Kit v3.

![Front view of the 3D-printed RBPi4+Zynscreen customized case](https://raw.githubusercontent.com/zynthian/zynthian-case/master/3DPrint-RBPi4-Zynscreen-CustomCase/Images/DSCF0340.JPG)

![Back view of the 3D-printed RBPi4+Zynscreen customized case](https://raw.githubusercontent.com/zynthian/zynthian-case/master/3DPrint-RBPi4-Zynscreen-CustomCase/Images/DSCF0341.JPG)

This case for Zynthian involves quite a lot of additional work and is not a simple assembly. It requires lots of extra soldering and glueing parts.
Wires for MIDI sockets and LEDs have to be lenghtened. Additional parts required are 20W 5V 4A PSU available from aliexpress at less than 2 euros,
80mm 5V silent fan, 2 little On-Off switches for power and cooling fan, some screws, nuts (I used M3 and M2.5 where required) and 3mm high plastic supports 
for PCB's (12 altogether).

Inner and outer side panels have to be glued together, then three PCBs (RPi4, Audioinject Zero and MIDI controller) plus PSU and fan have to be mounted 
on the bottom panel, back and front panels have to be glued to the bottom one and altogether they have to be glued to the right side panel.
Left side panel uses 4 magnets (my magnets are 4.8mm diameter - but you can use other sizes, just modifying four holes). I provide .stl file as an example
of the case receptacles for magnets (I use the same size magnets, they hold well); I glued them to the front, bottom and back sides (not to the top panel).

I ordered matte black acrylic for the face panel, but the seller sent me a glossy one;  as my design stands, I plan to use matt black for the face and outer side 
panels, and will replace glossy one with matte when my acrylic sheet arrives. 
To prevent an electrical damage to the PSU when I use RPI power supply (when it is not connected to the mains - and connecting both at the same time is
strictly NO if you don't want to fry your zynsinth) I installed a diode between PSU output and the circuits; 3A diode is enough, and 0.4V fall is easily 
compensated by a trimmer on the PSU.
Acrylic panels are all 3mm thick.

That's all...

Nicolai Demidenko
