## Adafruit HX711 24-bit ADC for Load Cells / Strain Gauges PCB

<a href="http://www.adafruit.com/products/5974"><img src="assets/5974.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit HX711 24-bit ADC for Load Cells / Strain Gauges. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5974

### Description

If you are feeling the stress and strain of modern life a Wheatstone bridge and you want to quantify it, this handy breakout will do the job, no sweat! The Adafruit HX711 Breakout contains a super-high-resolution 24-Bit differential ADC with extra gain circuitry that makes it perfect for measuring strain gauges / load cells or other sensors that have four wires that are connected in a Wheatstone bridge arrangement.

Each breakout comes with a HX711 ADC chip, plus some support circuitry, and 6 port terminal block that can be used to connect one or two 4-wire sensors. The E- pad connects to ground (often a black wire), the E+ pad connects to the power voltage supplied to the HX711 (often a red wire).

Then A- and A+ pads connect to the differential outputs from the bridge. For example, connecting to a strain gauge these tend to be the white and green wires. If you have a second gauge or voltage you want to measure, you can use the B- and B+ pads. On the A channel, you can select 64x or 128x gain. On the B channel, you have a fixed 32x gain.

As the sensor is twisted and bent, the slight changes in resistance are converted to minuscule voltage changes that can be read by the HX711 ADC for converting into force or mass measurements. You can use our Arduino library or CedarGrove's CircuitPython/Python library to configure and read the ADC for fast interfacing. Note that this sensor has a fixed I2C address, if multiple sensors are desired on one I2C bus, a multiplexer can be used.

This sensor uses a two-wire protocol, similar to SPI. If you want a similar sensor but I2C, check out the NAU7802 breakout we make. We based this design on the excellent Sparkfun HX711 breakout: incorporating their split analog/digital supply and digital supply filtering. We then made a few tweaks: pre-soldered terminal blocks, the second bridge exposed, and a slide switch to change between 10 SPS and 80 SPS rates.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
