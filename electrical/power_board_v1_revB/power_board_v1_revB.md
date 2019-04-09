#Description

This board will bring the power from an ATX power supply (ATX PSU) to the busbar of the discovery through cables

Cables of the ATX PSU will be connected to the board as follow :

	*2 CPU power connectors
	*4 PCIe power connectors
  
Connectors are 9A per pins which allow us to bring to the busbar:

	*2x4 + 4x3 = 20 pins => 20x9 = 180A 
  
With the cable version we will put cable in crimps using a crimper and then screw the crimp to the board at one side. 
At the other side, we will screw the crimp to the busbar (two crimps per hole so four for 12V and four for GND).

Cables will be 4 AWG which will allow us to have 135A max per cable for chassis wiring and 60A max per cable for power transmission

A +12V zone will cover top, with a bigger isolation around the GND vias. Same goes for the GND zone on bottom and +12V vias
