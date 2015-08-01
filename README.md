# TSL45315-Breakout
Breakout with [TSL45315](http://www.ams.com/eng/Products/Sensor-Driven-Lighting/SDL-Ambient-Light-Sensors/TSL45315) digital ambient light sensor from AMS.

[![TSL45315-Breakout](https://raw.github.com/watterott/TSL45315-Breakout/master/pcb/TSL45315-Breakout_v10.jpg)](http://www.watterott.com/en/TSL45315-Breakout)


## Shop
* [TSL45315-Breakout](http://www.watterott.com/en/TSL45315-Breakout)


## Features
* Direct lux output with wide dynamic range (3 lux to 220k lux)
* Rejects 50Hz/60Hz lighting ripple
* Approximates human eye response in diverse lighting conditions
* TWI/I2C Interface (address 0x29)
* 3.3V - 5V Power Supply and Logic Level


## Hardware and Software
* [Schematics + Layout](https://github.com/watterott/TSL45315-Breakout/tree/master/pcb)
* [Arduino Example](https://github.com/watterott/TSL45315-Breakout/tree/master/src)

* Arduino Library and Examples: [Makerblog_TSL45315](https://github.com/adidax/Makerblog_TSL45315)

* Raspberry Pi Library and Examples: [WebIOPi TSL4531](http://code.google.com/p/webiopi/wiki/TSL4531)
    ```
    from webiopi.devices.sensor.tslXXXX import TSL45315
    tsl = TSL45315(0x29)
    lux = tsl.getLux()
    ```
