# Basic-Klicky-for-Enderwire
This is my approach to a Klicky for the Enderwire conversion that doesn't require a servo.

The idea comes from running into issues with my probe on an Ender 3 Pro to Switchwire conversion, and wanting to swap it for a Klicky probe. The problem is that all Klicky probes for the Enderwire require a servo (because the X-gantry extrusion has been shortened and the toolhead cannot travel until it's outside of the bed), which complicates the build and makes it substantially more expensive.

Hence, the "Basic Klicky for Enderwire" idea, which would be a standard Klicky probe for the Stealthburner, that has to be placed manually before any print, stays attached after homing the Z axis to be ready for creating a bed mesh or homing again after heat-soaking, and then gets released from the toolhead by the print bed before it starts a new print (after meshing, of course) by attaching to a dock that is fixed to the back of the bed. The Klicky probe then has to be picked up from the dock and placed manually onto the toolhead before the next print.

Disclaimer:

* This solution isn't fully automated. The Klicky probe has to be attached manually before any print (this is an opportunity for improvement, if we can come up with an idea to home X and Y, and then have a Z height pin to make the height of the dock known to the printer, then picking up the Klicky probe, and continuing with the described functionality).
