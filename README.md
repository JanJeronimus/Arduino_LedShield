# Arduino_LedShield
## D2-D9 Led tester

 Shield for Arduino Uno with 8 Leds and some buttons
 intended for testing and experimenting.
* The Leds can be configured to be connected to the different Arduino pins 
 and to GND or +5V
* As LEDs and resistors through hole and SMD versions can be used. 
* On the PCB also 4 pushbuttons can be placed ( Reset and SW0 SW1 and SW2
* This arduino shield includes an "Ardaptor" concept to mount a cheap standard PY 5cmx7cm prototype board. (Not using the Arduino spacing but the standard pin spacing.
 However this will cover the LEDs area)

![PCB finished](/assets/images/PCBfinished.jpg)

Easy connect or disconnect with jumpers to pins D2 - D9 (or power)
With some dupont wires also other Arduino pins can be selected

![PCB Front and Back](/assets/images/PCBfrontback.jpg)


Each LED with a resistor in series goes to Pin 2 an 4 of a Dupont connector

GND Resistor Dx Led VCC


With 2 jumpers eah led can be confiured different ways:
1) Placing jumpers between
 GND and Resistor and between Led and VCC => LED testing (connected to VCC and GND)
In the middle (3) is Pin Dx connected to D2 up to D9 of the Arduino.
2) Placing jumpers between
 GND and Resistor and between Dx Led   => LED connected to Arduino pin and GND
3) Placing jumpers between
 GND and Dx and between Led and VCC    => LED connected to Arduino pin and VCC

Using one jumper and a dupont wire the LED can also be connected to any other Arduino pin.

![Schematic](/schematic/ArduinoD2-D9_tester.png)
