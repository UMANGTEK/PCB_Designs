This folder consistes of the design files of flight computer for CANSAT competetion 2023. This is my first ever design of PCB which is completely designed by me me and was used on the actual cansat during launch.
Due to size restriction the computer was divided into two parts:

PART 1 - Consists of micro-controller, actuators and pins for power supply for the whole flight computer.

PART 2 - Consists of sensors operating through I2C and UART, some actuators which could fit in part 1 has also been added .

My objective while desiging this PCB was to keep microcontrollers, actuators and main power supply in same board as all actuators indivisually require independent signal from micro-controller, while I2C is a common
signal for I2C operable devices, this reduced the wires used to connect two parts. 

All the sensors used in the computer were pre fabricated, hence I did not consider the impedence while designing and worked with the default parameters. I had started working on this PCB by the end of 1-1 and wasn't 
aware with importance of trace width and kept an arbitary value of 0.5 mm for all connections. 
