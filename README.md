# Neumann N149A/V Tube Power Supply Reverse Engineering
This project aims to reverse engineer and document the design of the PCB inside Neumann N194A and N194V type power supplys 
as well as offer a replacement linear design for the discrete SMPS inside of each stock unit.

# Operation
These power supplys offer a small variety of voltage rails to be used with a connected Neumann M147, M149, or M150 type tube
large diaphragm condensor microphone. 

The power supplys operate largely with two blocks. First, being the discrete switch mode power supply often found to be 
a Globtek "TR9KE1250LCP-Y" or similar. These are typically a 12V 1.25A 15W black brick type SMPS used to step the incoming
120V from the wall down to 12V to be used by other circuitry. Second, the remainder of the power supply is comprised by a PCB 
manufactured likely by Neumann that take the 12V from the SMPS and makes the necessary rails for the microphone with it. 
On this board the DIN-8 connector for linking to the microphone and XLR-3 connector for output are found.
