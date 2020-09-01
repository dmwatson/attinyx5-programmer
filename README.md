# ATTinyX5 Programmer 1.0

![Enlarged PCB view](https://github.com/dmwatson/attinyx5-programmer/blob/master/V1/ATTinyX5_PCB.png)

A programmer for the ATTiny 25/45/85/13 series of microcontrollers in DIP-8 package. This was an exercise to try and make the least expensive, standalone, and relatively small programmer for that series of microcontrollers. The programmer uses an Arduino Nano v3 board as the ISP interface and has a test LED for the ATTiny located on pin PB3. The PCB size currently is 48.26mm&#xb2;.

Currently, this version of the hardware will work with the DIP-8 package of those particular microcontrollers.

## ICSP Version

In the ICSP directory is an even more simplified version of the board that uses the ICSP (In-Circuit System Programmer) pins located at the rear of an Arduino Nano.

The ICSP version of the board is only 20.45mm x 17.02mm.

![Enlarged PCB view](https://github.com/dmwatson/attinyx5-programmer/blob/master/ICSP/PCB_V1.png)

## License

All board designs, Gerber files, schematics, etc., are licensed under the [Open Source Hardware (OSHW) 1.0](https://www.oshwa.org/definition/) license.

## About the Hardware

In order to make the programmer compact, SMD components were used in its design. See the BOM for complete listings of materials. The total cost for components, minus the Nano and ATTiny, comes to about $3.50 USD total as of this writing.

## Solder Stencil DXF

A DXF of the PCB is included to create 3D printable solder stencils. The holes in the PCB design are included to allow for proper board alignment like fiducials.

## Improvements

There's always room for improvement. Being able to work with different microcontrollers like the 24/44/84 series, or different packages using a switch might be nice to have.
