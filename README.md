An adaptation of the crkbd keyboard. It contains a 4x6 matrix and three thumb keys. It's also MX and Choc hotswappable.

All of the KiCad files needed to print the pcb are included. I know that the gerber files included are enough to print through JLCPCB.

I have dxf files to get plates made for the pcb's, but I won't have access to that computer for at least a week or two. Same with QMK.

If you want to do QMK yourself before I add it, I'll try to give the steps as best as I remember them.
There's a file which specifies rows and columns. Here, change it from 8 to 10. There's also a file which specifies input and output pins. There should be a list for rows which has D4, C6, D7, and E6. Add B4 to this. Now, you can add an extra row in the key layout and compile.
