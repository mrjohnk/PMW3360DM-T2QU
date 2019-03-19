# PMW3360DM

This library will get you up and running with the PMW3360DM module available from [this Tindie page](https://www.tindie.com/products/jkicklighter/pmw3360-motion-sensor/). It handles all the behind the scenes communication with the module over SPI.  


## Wiring
Teensy wiring:  
VI = 3.3V  
MI = MISO0 -or- DIN  
MO = MOSI0 -or- DOUT  
SC = SCK0 -or- SCK  
SS = CS0 -or- CS  
MT = Must match [Motion_Interrupt_Pin on line 56](https://github.com/mrjohnk/PMW3360DM-T2QU/blob/master/PMW3360DM.ino#L56) (Pin 3 by default)  
GD = GND  
  
*Note: The MT pin must be attached to an interrupt compatible pin. Check to make sure the pin is labelled INT on the [Teensy pinout page](https://www.pjrc.com/teensy/pinout.html)*  



