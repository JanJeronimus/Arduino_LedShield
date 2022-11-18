# Arduino_LedShield
## D2-D9 Led tester

 Shield for Arduino Uno with 8 Leds and some buttons
 intended for testing and experimenting with programs on the Arduino.
* The Leds can be configured to be connected to the different Arduino pins 
 and to GND or +5V
* As LEDs and resistors through hole or SMD versions can be used.
* On the PCB also 4 pushbuttons can be placed ( Reset and SW0 SW1 and SW2
* This Arduino shield includes an "Ardaptor" concept to mount a cheap standard PY 5cmx7cm prototype board.

![PCB finished](/assets/images/PCBfinished.jpg)

### Leds
SMD and through hole components are drawn in paralell in the schematic, Solder only one. 

Easy connect or disconnect leds with jumpers to pins D2 - D9 (and VCC or GND)
Using Dupont wires other Arduino pins can be used

![PCB Front and Back](/assets/images/PCBfrontback.jpg)

Circuit of each Led with a resistor in series goes to Pin 2 an 4 of the Dupont connector

5 pin connector:
GND Resistor Dx Led VCC

A Led can be configured different ways:
1) Placing jumpers between
 GND and Resistor and between Led and VCC => LED testing (connected to VCC and GND)
In the middle (3) is Pin Dx connected to D2 up to D9 of the Arduino.
2) Placing jumpers between
 GND and Resistor and between Dx Led   => LED connected to Arduino pin and GND
3) Placing jumpers between
 GND and Dx and between Led and VCC    => LED connected to Arduino pin and VCC

4) Using a Dupont wire the LED can be connected also to any other Arduino pin.

### Switches
Using jumpers SW0 SW1 and SW2 can be wired to A0 A1 A2
The PCB also has space for a Reset switch

### Ardaptor
The PCB can also be used as "Ardaptor"  (Arduino Adaptor) to mount a cheap standard PY 5cmx7cm prototype board.
It can convert the Arduino pin spacing to standard pin spacing. However in this case the LEDs area wil be covered.
The yellow line on top indicated the size of the PY 7cm * 7 cm prototype board pin area. 


### PCB
![PCB](/assets/images/PCB.png)

### Schematic
![Schematic](/schematic/ArduinoD2-D9_tester.png)


