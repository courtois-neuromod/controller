# PCB assembly instructions
Get PCB 3D model [here](../CAD/stp/neuromod_game_controller_v1.zip)

## Ordering PCBs

Get Gerber files [here](GerberFiles.zip) and send to fab house

## Assembly
<img src="img/PXL_20220401_211853837.jpg" alt="" width="600"/><br>
Raw PCB view

<img src="img/PCB_1.png" alt="" width="600"/><br>
PCB isometric view

<img src="img/PCB_2.png" alt="" width="600"/><br>
PCB Top view

<img src="img/PCB_3.png" alt="" width="600"/><br>
PCB Side view

<img src="img/PCB_4.png" alt="" width="600"/><br>
PCB Side view

Teensy with headers | Teensy on PCB
---|---
<img src="img/PCB_5.png" alt="" width="400"/> |<img src="img/PCB_6.png" alt="" width="400"/>

The Teensy board can be mounted either on headers (left) or directly on PCB (right). The first option is recommended as is allows easy replacement in case of damage.

<img src="img/PCB_7.png" alt="" width="600"/><br>
Adjust potentiometer to be 330 Ω between the two illustrated pins or solder directly a 330 Ω resistor between those pins.

<img src="img/PCB_Layout.png" alt="" width="600"/><br>
Board layout

Schematics | Component| Value
-----------|----------|---|
IC1 - IC5, IC7|Gate driver|SN75451BP
IC6|Voltage regulator|LM340
R1 - R10|Resistor| 65 Ω
R11 - R29|Resistor|330 Ω between pin 1 & 3
R21|Resistor| 5 kΩ
C1 - C8|Capacitor|0.1 µF
C11,C12|Capacitor|10 µF
TX1 - TX10|Fiber optic transmitter|SFH756V
RX1 - RX10|Fiber optic receiver|SFH551V
Teensy 3.5 | Use version 3.5 **NOT 3.6**

TX9,TX10,RX9,RX10 and associated components are optional. They were meant for additional controls not implemented on this version of the controller. They can also be used for troubleshooting purpose or to fix a damaged channel.
