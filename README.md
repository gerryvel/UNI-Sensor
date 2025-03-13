# UNI-Sensor

![ESP32](https://img.shields.io/badge/ESP32-grey?logo=Espressif)
![KiCad](https://img.shields.io/badge/KiCad-darkblue?logo=KiCad)
![Relaise](https://img.shields.io/github/release-date/gerryvel/NMEA2000_TPW?)
![lastcommit](https://img.shields.io/github/last-commit/gerryvel/NMEA2000_TPW)
[![OBP](https://img.shields.io/badge/Sailing_with-OpenBoatsProjects-blue)](https://open-boat-projects.org/de/)

## Description
Universal housing / sensorcase for the boat sensors. 
Works with the software for the
- TPW sensor [Link](https://github.com/gerryvel/NMEA2000_TPW)
- MD sensor [Link](https://github.com/gerryvel/Motordaten)
- BD sensor [Link](https://github.com/gerryvel/Bootsdaten)
  
An additional board is available for the MD sensor, which is used to connect the sensors in the motor.
Depending on what is desired, the PCB board is assembled.
The PCB Board is complete with cover for the case.

## Circuit Diagram

![grafik](https://github.com/user-attachments/assets/197839f6-88d9-449e-bad3-d18180a2e885)
![grafik](https://github.com/user-attachments/assets/645a043e-5bcb-4a8e-890a-a823505a91c1)

## PCB

PCB by Aisler: [Link](https://aisler.net/p/CPIILIWO)

![grafik](https://github.com/user-attachments/assets/9237702e-ea9d-4694-a76b-8f9c9d8d6c1d)
![grafik](https://github.com/user-attachments/assets/ddced970-ff48-4024-8d60-0360f3428a74)

## Partlist

- C1	10µ	~	Capacitor_Tantalum_SMD
- C2	22µ	~	Capacitor_Tantalum_SMD
- D1	B360	[Link](http://www.jameco.com/Jameco/Products/ProdDS/1538777.pdf)	
- D2	LED_RBKG	[Link](https://cdn-reichelt.de/documents/datenblatt/A500/L-154A4SURKQBDZGW_ENG_TDS.pdf)	
- D3	PESD1CAN	[Link](https://www.tme.eu/Document/67dd2a1e5cb9d65d3ec5e3eca686ae13/PESD1CAN.pdf)	
- D4	ZPD3.3	[Link](http://diotec.com/tl_files/diotec/files/pdf/datasheets/zpd1)	
- D5	1N4148	[Link](https://assets.nexperia.com/documents/data-sheet/1N4148_1N4448.pdf)
- D6	P4SMAJ26CA	[Link](https://www.tme.eu/Document/1eef058bc29c4135e52f8ab997b46c91/p4smaj65.pdf)
- FL1	EPCO B82789C0513	
- J1,J2,J3,J4	Wago 2091-1174	[Link](https://www.wago.com/de/steckverbinder/1-leiter-tht-federleiste-gerade/p/2091-1174)
- J5	236-402	[Link](https://www.wago.com/236-402)
- J6,J7	236-403	[Link](https://www.wago.com/236-403)
- J8	M12 Cable 5x0,34mm²	
- R1	100k	~	Resistor_THT
- R2	27k	~	Resistor_THT
- R3	300R	~	Resistor_THT
- R4	10k	~	Resistor_THT
- R5	1k	~	Resistor_THT
- R6	4k7	~	Resistor_THT
- R7	2k	~	Resistor_THT
- U1	TSR_1-2450	[Link](http://www.tracopower.com/products/tsr1.pdf)	
- U2	ESP32-Huzzah	[Link](https://learn.adafruit.com/huzzah32-esp32-breakout-board/downloads)	
- U3	SN65HVD230	[Link](http://www.ti.com/lit/ds/symlink/sn65hvd230.pdf)	
- U4	H11L1	[Link](https://www.onsemi.com/pub/Collateral/H11L3M-D.PDF)
- U5,U6	DS18B20	[Link](http://datasheets.maximintegrated.com/en/ds/DS18B20.pdf)
- Case Phoenix UM-ALU 4-72 PROFILE 42,5 [Link](https://www.phoenixcontact.com/de-de/produkte/aufbaugehaeuseunterteil-um-alu-4-72-profile-425-2200917)
- Side elements (left and right) incl. snap-on foot Phoenix UM-ALU 4-72 COVER PA BK [Link](https://www.phoenixcontact.com/de-de/produkte/aufbaugehaeuse-seitenteil-um-alu-4-72-cover-pa-bk-2200934) 

## Foto

![image](https://github.com/user-attachments/assets/acca51ec-5697-454b-a93a-6d111932ee75)

![image](https://github.com/user-attachments/assets/b70798c0-e3a4-4893-b07d-f2c90de33de3)

![image](https://github.com/user-attachments/assets/4decf622-997f-4fb9-91bb-c0869aa0ace2)


