# Eurorack Balanced Out
Stereo balanced output board with attenuation for in eurorack cases.

This will be a Kicad project for a balanced output board to build into Eurorack cases. This will not be used as a eurorack
module, but instead can be built into a eurorack case to provide two balanced outputs on TRS jacks on the back of the case.
The circuit can be powered from a normal +12v/-12v eurorack power supply and can be connected to a module built into the case
with mini-jack connectors so other modules can use the output. The current assumption is that we can use the Doepfer A-139-2 
Headphone Amplifier module for this. It provides mini jack inputs, volume control and has two un-populated headers on the board
that look like they provide outputs.

Features
- Two balanced 6,3 mm TRS jack outputs
- 10 pin eurorack compatible power connector for +12v/-12v
- two selectable attenuation levels (levels tbd. 1/4 and 1/10 for now)
- two DRV135 output drivers
- inputs on two 2-pin headers for internal connection to front panel module
