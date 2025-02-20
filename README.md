## MechaTrellis RGB Driver PCB for 4x4 Keypad PCB

PCB files for the MechaTrellis 4x4 keypad PCB. Format is Kicad 8.0 schematic and board layout


### Description

MechaTellis is an Adaptation/Remix of the Adafruit NeoTrellis RGB Driver PCB.  

MechaTellis was designed by Steven Noreyko/denki-oto. Original NeoTrellis design by Limor Fried/Ladyada for Adafruit Industries. 

These run the same NeoTrellis seesaw I2C chip and are fully software compatible with the NeoTrellis boards and projects.

A JST-SH 4-pin connector is included that will give you power+data access. Note JST-SH is smaller than the NeoTrellis JST-PH connector.

From the original NeoTrellis 4x4 boards:  

These 4x4 button pad boards are fully tile-able and communicate over I2C. With 5 address pins, you've got the ability to connect up to 32 together in any arrangement you like. [With our trusty seesaw I2C-to-anything chip](https://learn.adafruit.com/adafruit-seesaw-atsamd09-breakout), you don't even need to manage the NeoPixel driving. That's right! Both the button management and LED driving is completely handled for you all over plain I2C. With both Arduino/C++ and CircuitPython/Python library support, you can use these pads with any and all microcontroller or computer boards.

**You can tile up to 32 boards together by soldering them edge-to-edge and soldering closed the I2C address jumpers, then use one I2C connection for all tiled boards!**

### License

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
