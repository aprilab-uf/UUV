UUV Testbed README
Fall 2022
Altium Schematic and PCB Files:
There are three separate PCB files: the Power, Main, and IMU Sensor board. The Power PCB file includes the Thruster schematic and Battery Management Schematic. The Main board PCB includes the Main board schematic and the IMU sensor board PCB includes the IMU sensor board schematic.

	For these designs, the system is powered by a 22.2V Lithium ion battery, and only powers the IMU with the battery management IC disconnected. The IMU communicates with a Raspberry Pi 4+ (code is included for USB camera and IMU). With the current design, the Raspberry Pi 4+ only works when powered by a wall outlet. 
	
	What works with current hardware design:
●	Power to IMU
	What will be updated:
●	Providing safe power to thruster(s) and Raspberry Pi 4+ with battery management IC (instead of just IMU)
●	Add CANBUS communication between thruster(s) and IMU
●	Hole sizes for the battery and thruster PCB connections
●	Fuse selection
●	Surface mount connections for the mezzanine connectors on the IMU board and Main board
●	Method of attaching the Power board and Raspberry Pi 4+ onto the Main board 
