# Linear Regulated - Adjustable Power Supply for a Workbench setup  

The Workbench requires a general all purpose variable power supply. A dual power supply with independent adjustable positive and negative output voltages enables a separate adjustment for each of the supplies, providing the user unlimited applications for IC circuit voltage requirements. A Jameco {JE215) Adjustable Dual Power Supply Kit BOM is provided below.

A containment enclosure will be constructed using the previously constructed [CNC Milling machine]() to edge the contours and pockets required.  

|ITEM 		|QTY.	  |PART NO. 	 |DESCRIPTION 							|
|-----------|:-------:|:------------:|:------------------------------------:|
|IC1		|1		  |23579	     |Regulator, Adj. Pos., LM317T			|
|IC2		|1		  |23819		 |Regulator, Adj. Neg., LM337T			|
|C1, C2		|2		  |609705		 |Capacitor, Electrolytic, 2200uF 35V	|
|C3, C4		|2		  |33662		 |Capacitor, Tantalum, 1uF 35V			|
|CR1, CR4	|4		  |35975		 |Diode, 1N4001							|
|LED1		|1		  |94511		 |Red T1 ¾ LED, Diffused Lens			|
|R1			|1		  |690865		 |¼ Watt, 1k ohm (brown-black-red)		|
|R2, R5		|2		  |690689		 |¼ Watt, 180 ohms (brown-gray-brown)	|
|R3, R4		|2		  |35503		 |¼ Watt Potentiometer, 2.5k ohms		|
|P1			|1		  |42042		 |6 foot power cord, AWG 18/2			|
|T1			|1		  |29226		 |Power Transformer, 12.6VCT @ 2A		|
|			|2		  |42622		 |Heatsink, THM6030 or Equivalent		|
|			|1		  |20642		 |Printed Circuit Board, JE215-1		|
|			|2		  |40970		 |Screw, PH 4-40 x 3/8"					|
|			|6		  |42446		 |Screw, PH 6-32 x 3/8"					|
|			|2		  |42463		 |Washer, split lock, #6				|
|			|2		  |40943		 |Hex Nut, 4-40							|
|			|10		  |42420		 |Hex Nut, 6-32							|
|			|4		  |32011		 |Rubber bumper feet SJ5012 or equivalent|
|			|		  |20634		 |Kit instructions for JE215  			|

## Electrical  
Schematics included:

![schematics](/Electrical/Schematic_Diagram.png) 

## Structural  
Reference the [FreeCAD files](/Structural) - derive GCODE to use CNC or 3D Printer  

![Power Supply](/Electrical/Power_Supply.png)  

5.1"L - 129.54 mm  
3.5"W - 88.9 mm  
2.0"H - 50.8 mm   

Bounding boxes around outside for slats, + 5 mm  

2x - 135 mm x 94 mm - 6 slots 			- Base  
	4x slots aligned to length - 25.32mm from edge 4mm inside edge 1.1 mm for slots width, 25.32mm from edges 20 mm slot length (both sides)  
	2x slots aligned to width - 37.22mm from edge 20 mm slot length, 4 mm from top/bottom  
	
2x - 135 mm x 56 mm - 2 slots 4 slats	- Sides  
	4x slats aligned to length - 25mm from edges - edges milled 1.1 mm except for slats  
	2x slots aligned to width - 18mm from edges - 20 mm slot length - 4 mm from top/bottom  

2x - 56 mm x 94 mm  - 4 slats			- Ends  
	2x slats - 37 mm from edge - edges milled 1.1mm except for slats 20mm in length (top / bottom)  
	2x slats - 18 mm from edge - edges milled 1.1mm except for slats 20mm in length (sides)  

