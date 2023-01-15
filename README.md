# ESP-Solar_OpenDTU
PCB for OpenDTU in Cable Branchbox, LineSupply w. Fuses, RS485/RS232-Olimex, Relais, DS2485 OneWire, I2C-Header...

Mechanically fits into quite compact HNS 989861-H01 wiring box (form closure only).
If not all features are used, even edged Wieland-Socket should fit.
LEDs need LightGuides: no. position-drawing and not included in material list 

Tradeoff: Very limited space, copyrighted code for ds2485

image::ESP-SolarV1.jpg

* WESP32-WROOM-based (internal or external antenna)

* 5x20 Fuseholder (Supply)
* Varistor
* HiLink Supplymodule f.e. 230V->3.3V

* 5x20 Fuseholder (Relais)
* Relais SANYOU 10A

* modern 1Wire-Controler DS2485
* programming Header (Shelly-Pinout)
* I2C+VCC+GND header
* 2x5 Ribbon Connector for Olimex' RS485/RS232-Modules
* LEDs (green: power, red:active, or:DS2485 GPIO)

* TTL serial connector f.e. for IR-Energy reading 
* robust cage clamps for external connections

The board was done for differend scenarios including HoymilesDTU, using different RF-Modules,
reading the new IR-Energy counters with "Volkszähler", measure distributed temerature locations 
with OneWire-Sensors and control of pool pump or heating elements, maybe some IR motion detection 
in the garage, interfacing RS485/Modbus/RS232 for Solar-Inverters etc. - CAN- and metering bus 
are missing, though.

Would be great to hear how you used it or modified it for!
