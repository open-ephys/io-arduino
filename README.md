io-arduino
==========

Some applications require to generate (or read) digital channels on the host-PC running the GUI.
Most commonly, this is needed when closed-loop experiments make use of event detection on the host PC, for example with the phase-detector plugin.

The arduino shield for I/O from the host-pc can generate up to 8 channels of digital I/O.
Each channel can be assigned as in or out and assigned to an event channel in the GUI.

On the arduino, this is implemented via the firmate firmware ( http://playground.arduino.cc/Interfacing/Firmata )
ADD MORE DETAIL HERE

For a similar, but much more powerful signal output device, check out the PulsePal (https://sites.google.com/site/pulsepalwiki/home) which also works seamlessly with the Open Ephys GUI.


