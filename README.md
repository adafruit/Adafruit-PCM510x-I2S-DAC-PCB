## Adafruit PCM510x I2S DAC with Line Level Output PCB

<a href="http://www.adafruit.com/products/6250"><img src="assets/6250.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>
<br>
<a href="http://www.adafruit.com/products/6251"><img src="assets/6251.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit PCM510x I2S DAC with Line Level Output. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6250
* https://www.adafruit.com/product/6251

### Description

We stock a lot of chips and development boards that are able to do high quality digital I2S out, which makes for great quality audio playback. That's great when you have enough processing power to decode WAVs or MP3s in real time. However, we don't have a good selection of I2S DAC boards...until now! We really love the sounds coming out of the Adafruit PCM5102 I2S DAC with Line Level Output - it's got clean, excellent-quality, stereo audio and does not need any MCLK or I2C configuration. Literally just pipe some I2S audio in and it ill just work.

The PCM510x comes in a few different varieties: we've got the the good-quality PCM5100 with 100dB signa-to-noise/dynamic range, and the excellent-quality PCM5102 with 112dB. The '02 is a little more expensive but they are both quite good for any use and are pin-compatible so can swap between the two.

This breakout makes I2S digital audio easy: all you need to do is power it with 3~5VDC, and provide BCLK (bit clock), WSEL (left/right word select), and DIN (data in). The data lines are 3.3V logic only. By default it's configured for I2S but you can also do Left-Justified by toggling the Format pin. Audio can be 16, 24 or 32-bit wide, the chip will automagically determine the right format from the WSEL / BCLK ratio. No MCLK pin is needed, the chip will auto-generate it internally from the bit clock - or you can provide it on the MCLK input if you want.

Other breakout pads provide: filtering (change from normal to low-latency by pulling high), mute (pull low to quickly set the outputs to ground), and de-emphasis for 44.1khz audio (default is off). The audio outputs are also available on breakout pads if you want to wire directly without using the 3.5mm jack.

Audio output is not AC-coupled because it is centered on ground: you can plug it into anything that is either AC coupled or has the same ground reference. Note that this is a line-level output, it cannot drive headphones - the output is for no less than 1K ohm loads!

Each order comes with one I2S Stereo DAC breakout and some header you can solder on for breadboard usage.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
