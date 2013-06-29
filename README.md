i2c LCD controller with PCF8574
===============

This board works with the <a href="http://hmario.home.xs4all.nl/arduino/LiquidCrystal_I2C/">LiquidCrystal I2C</a> Arduino library to communicate with an HD44780 LCD. Most components are SMT to make things easier and cheaper.

BOM:

*  1 x PCF8574 16-SOIC package, for example digikey# 296-13105-1-ND
*  1 x 0.1 uF 1206 ceramic capacitor
*  2 x 10k 0805 resistor
*  1 x 100ohm 0805 resistor
*  1 x 10k trimmer potentiometer, through hole 6mm, for example digikey# 3319P-103-ND
*  optional 0.1" header for connections

The schematics and board files were made in Eagle.

For diy style etching use 1 sided copper clad (etch BOTTOM layer only), use a piece of wire for vias and top layer trace.

A0-A2 sets i2c address. Refer to the PCF8574 datasheet for info on the address settings.


