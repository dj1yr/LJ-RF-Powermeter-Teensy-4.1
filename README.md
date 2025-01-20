Here is a collection of files for the RF Powermeter with Teensy 4.1 (a Teensy 4.0 can also be used with restrictions).
Since I could not find any board files, I designed two boards based on Robert Entwistle's version, WA2T.
The REV2.7 is an all in one version, the Rev3n is based on a mainboard on which different RF boards can be plugged to find the best solution for each application.
The firmware is being further developed by Johan G. Holstein and is really impressive.

I am trying to create a complete folder with all files here, my board files are welcome to be used and improved.

The board was designed with Kicad and the housing parts are designed with Inventor.


73' René


**Revisions:**

REV3n:
-add extender card
-many changes

REV4n:
**BETA**
last changes from Johan (PD0LEW) - Beta!
-add LAN on ESP32 with W5500
-add USB-C connector, connected on Teensy
-add extra display header (J4)*
-add USER IO to ESP32
-removed USER IO from teensy*
