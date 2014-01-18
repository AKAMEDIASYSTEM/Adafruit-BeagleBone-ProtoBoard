Hi, I'm hoping to do a number of Beaglebone Black projects that use a lot of I2C and analog sensing devices. I modified Adafruit's excellent Proto Capes to include a dedicated I2C bus area that allows you to connect up to 11 I2C devices to the same bus; also, in the place where the SMD pads were, I made an area where you can easily connect voltage-divider type analog sensors to a0 through a5.

I also added some BBB-specific pin labels to the boead because I found I kept having to look those up...

- AKA

PS, super-thanks to Adafruit for sharing their design!

== Adafruit's original text ==

Adafruit Proto Cape Kit for Beagle Bone 

These are the Eagle CAD files for the Adafruit Proto Cape Kit for Beagle Bone:
  ----> http://www.adafruit.com/products/572

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Add some circuitry to your Beagle Bone with our lovely Proto Cape. If you have a 'Bone you need one of these! This PCB fits neatly on top of a Beagle Bone, without getting in the way of the Ethernet jack, and provides a breakout to both 46 pin headers - with individual numbering to keep them straight. We also threw down some strips to access the 5V and 3V power supplies as well as two SMT breakouts, one for SOIC-8's and one for SOT-23's. 

Kit comes with a double-sided FR4 PCB and 3 sticks of header. You'll need to place the header into the Beagle Bone and then solder the Proto Cape PCB in place, but its very easy and should take only 10 minutes max even for beginners

All text above must be included in any redistribution

Designed by Limor Fried/Ladyada and Kevin Townsend for Adafruit Industries.
Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution