## Adafruit Adafruit 1.9" 320x170 Color IPS TFT Display - ST7789 PCB

<a href="http://www.adafruit.com/products/5394"><img src="assets/5394.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Adafruit 1.9" 320x170 Color IPS TFT Display - ST7789. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5394

### Description

This lovely little display breakout is the best way to add a small, colorful, and very bright display to any project. Since the display uses 4-wire SPI to communicate and has its own pixel-addressable frame buffer, it can be used with every kind of microcontroller. Even a very small one with low memory and few pins available! The 1.9" display has 320x170 16-bit full-color pixels and is an **IPS** display, so the color looks great up to 80 degrees off-axis in any direction. The TFT driver (ST7789) is very similar to the popular ST7735, and our Arduino library supports it well.

The breakout has the TFT display soldered on (it uses a delicate flex-circuit connector) as well as an ultra-low-dropout 3.3V regulator, auto-reset circuitry, and a 3/5V level shifter so you can use it with 3.3V or 5V power and logic. We also had a little extra space, so we placed a microSD card holder so you can easily load full color bitmaps from a FAT16/FAT32 formatted microSD card. The microSD card is not included, [but you can pick one up here](https://www.adafruit.com/product/5251).

Of course, we wouldn't just leave you with a datasheet and a "good luck!" - [we've written a full open-source graphics Arduino library that can draw pixels, lines, rectangles, circles, text, and bitmaps as well as example code](https://github.com/adafruit/Adafruit-ST7735-Library). The code is written for Arduino but can be easily ported to your favorite microcontroller! Wiring is easy, we strongly encourage using the hardware SPI pins of your Arduino as software SPI is noticeably slower when dealing with this size display. [For Raspberry Pi or other Single Board Computer Python users, we have a user-space Pillow-compatible library](https://github.com/adafruit/Adafruit_CircuitPython_RGB_Display). For [CircuitPython there's a displayio driver for native support](https://github.com/adafruit/Adafruit_CircuitPython_ST7789).

This display breakout also features an 18-pin "EYE SPI" standard FPC connector with flip-top connector. You can use an 18-pin 0.5mm pitch FPC cable to connect to all the GPIO pins, for when you want to skip the soldering.

**Please note!** This display is designed original for smartwatches and similar, where there's a glass over the screen. Without something gently holding the screen down, the backlight can eventually peel away from the TFT. (It's not destructive but it's unattractive) You can prevent this by, ideally, adding a plastic or glass cover/overlay. If using bare, try dabbing a touch of E6000 or similar craft glue on the thin side edges, or using a thin piece of tape to keep the front TFT attached to the backlight.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
