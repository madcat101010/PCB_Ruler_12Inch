PROJECT:		PCB_Ruler_12Inch

REV:			1.0

AUTHOR:			Robin S. Yang

DATE:			26 JAN 2018

PCB SOFTWARE:	KiCAD 4.0.4-stable

DIMENSIONS:		12.060 mil x 1.500 mil

LAYERS:			2

===============================


This is a foot long PCB-ruler. There are many standard SMD parts with more use-case specific IC footprints. The AWG 0 hole may be used as a hanging point. There are also some useful data tables and formulas. All pads and through holes should be shorted together through a complete copper plane on either top/bottom layers. Prefer using some sort of gold plating on exposed copper for better readability and aesthetics. Designed for use with matte black soldermask. May need decent PCB fab accuracy for fine silk screen.

There is a blank .sch schematic. No schematic provided as there are zero working circuits on the PCB. The netlist is not useful either. I am too lazy to make a full schematic that grounds everything. A -0.001 mil clearance was used to ensure all pads/throughholes are shorted to the copper planes.

The .kicad_pcb layout file has many reference footprints and rulers for mm/cm, 1/16 inch, and 1/10 inch. Most footprints sources from KiCAD's v4 and v5 open source footprint libraries. Footprints in the ruler_specific.pretty library were created by me for this PCB. Footprints include ones that belong to standards (i.e. JEDEC).

Feel free to modify it with your own formulas or footprints. This PCB design is an open source hardware project. I am not responsible for any inaccuracies in values or formulas. Use this design at your own risk!

I came up with the star and gear logo on the top soldermask. Feel free to replace it with your own solder mask art!
