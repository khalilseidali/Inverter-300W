# Inverter-300W
As always, schematic design is divided into four sections:

•	Analogue

•	Digital

•	Controller (driver)

•	Power circuit

Analog Unite is Formed of a voltage level comparator circuit for reading and comparing the input voltage level (battery) and accordingly warning if the voltage level is less than the specified value.
5V (LM1117) linear regulator for power supply.
The digital part of this circuit consists of a NE555 to generate a clock pulse for a JK flip-flop. Specifications and equations are available in the schematic file. The controller part, which is the same as the power MOSFET driver part, consists of an optocoupler isolation circuit to separate the digital part and the power circuit, as well as to drive the power MOSFETs. This section commands JK flip-flops to turn on the MOSFETs.
Finally, the last part, which includes MOSFETs and double transformers 50hz 220v (input: 12v 0 -12v). Talking about the details of this circuit will last until the Day of Judgment. If you are interested, Send me Massage.

In This File :
1)BOM
2)SCHs
3)2Layer PCB ( PCB StackManager)
4)Datasheets
