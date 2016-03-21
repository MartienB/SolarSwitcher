#SolarSwitcher

##Goal
The goal of the SolarSwitcher project is to develop a device which can reliably power a USB powered device (in this case a Raspberry PI) from a small solar panel. The uptime of the USB powered device will be garanteed by switching to a secondary power supply in case the battery voltage of the solar panel will drop below a certain level.


##Requirements
- The device should consist mainly of parts I've lying around.
- The device should be durable, so no loose wires and breadboards
- The device should be able to relay its status (show statistics on connected RPI)
- The device should be power efficient
- The device should work if either power supply is disconnected 
- The power to the connected (USB powered) device shouldn't be interuppted while switching power supplies


##Prototype

Build a prototype with breadboards, loose wires and salvaged parts. Capacitor bank is way to big to use in final design.

##Version 1:

Design based around a simple relay board and using micro USB connectors for connecting the input power sources.

##Version 2:

Replaced relay board for a relay, diode and two leds (with resistors). Micro USB connectors were to fragile in the first version so we're now using USB B connectors



