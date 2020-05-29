# Eurorack Balanced Out
Stereo balanced output board with attenuation for in eurorack cases.

This is a Kicad project for a balanced output board to build in the back of an Eurorack case. This is not a eurorack
module, but instead can be built into a eurorack case to provide two balanced outputs on TRS jacks on the back of the case.
The circuit is powered from a normal +12v/-12v eurorack power supply and can be connected to a module that provides
mini-jack connectors so signals can be patched into the output. The current assumption is that we can use the Doepfer A-139-2 
Headphone Amplifier module for this. It provides mini jack inputs, volume control and has two un-populated headers on the board
that look like they provide outputs.

Features
- Two balanced 6,3 mm TRS jack outputs
- 10 pin eurorack compatible power connector for +12v/-12v
- 1/4 attenuation, use different resistors to change attenuation level
- two THAT1646 output drivers
- inputs on two 2-pin headers for internal connection to front panel module
