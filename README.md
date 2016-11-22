# Three-Channel Thermocouple Input Module (K Type)
This repository includes the schematic and PCB design of a three-channel thermocouple input module (K-type). This module is similar to the [Adafruit thermocouple amplifier breakout board](https://www.adafruit.com/product/269), but allowing for three channels of input. This module (or breakout board) also uses MAX6675 chip and can only be connected to [K-type thermocouples](https://www.adafruit.com/products/270). MAX6675 can sense temperatures ranging from 0 to 1024 Degrees Celcius.

## Dimensions:
Length: 45mm/1.77in
Width: 28mm/1.1in

## Data Interface
The MAX6675 chip uses an SPI-compatible serial interface (only SCK and MISO). 

## Arduino Library
The [MAX6675 library from Adafruit](https://github.com/adafruit/MAX6675-library) can be readily used.

*Note that there are no 3.3V voltage regulators on this board. The MAX6675 chip itself accepts both 3.3V and 5V power input, but make sure the voltage level of the I/O pins are compatible with the devices connected.
