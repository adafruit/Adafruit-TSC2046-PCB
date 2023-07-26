## Adafruit TSC2046 SPI Resistive Touch Screen Controller PCB

<a href="http://www.adafruit.com/products/5767"><img src="assets/5767.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit TSC2046 SPI Resistive Touch Screen Controller. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5767

### Description

Getting touchy performance with your screen's touch screen? Resistive touch screens are incredibly popular as overlays to TFT and LCD displays. Only problem is they require a bunch of analog pins and you have to keep polling them since the overlays themselves are basically just big potentiometers. If your microcontroller doesn't have analog inputs, or maybe you want just a way more elegant controller, the TSC2046 is a nice way to solve that problem.

This breakout board features the TSC2046, which has an easy-to-use SPI interface available. There is also an interrupt pin that you can use to indicate when a touch has been detected to your microcontroller or microcomputer. It can be powered from 3-5V, so it's safe to use with 3V or 5V logic. It's a nicely designed chip and has very stable precise readings. We found it's also a lot faster than trying to do all the readings on an Arduino.

For the screens that have 1mm pitch FPC cables, you can plug the cable right into the connector. The majority of medium/large touchscreens have that kind of connector. If you have another kind of touch screen, the four X/Y contacts are available on 0.1" pitch breakouts so you can hand-solder or wire them.

Getting started is super easy with our simple TSC2046 Arduino library. Plug any 1mm-pitch 4-wire resistive touchscreen to the on-board FPC connector, then use the library example to read touch points with X, Y and Z (pressure) results returned instantaneously. There's an IRQ pin that will drop low when a touch is detected, you can use that to reduce the SPI polling.

We also break out the Busy pin, that lets you know when the chip is still reading, and the Vref pin if you want to read or change the default 2.5V reference voltage. There's also two extra ADC pins you can read, Aux (0V - VRef) and VBat (0V - 2*VRef).

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
