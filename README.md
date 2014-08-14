io-arduino
==========

Some applications require to generate (or read) digital channels on the host-PC running the GUI.
Most commonly, this is needed when closed-loop experiments make use of event detection on the host PC, for example with the phase-detector plugin.

The arduino i/o module for the GUI can interface with an aruino via the firmate firmware ( http://playground.arduino.cc/Interfacing/Firmata ) and assigns pins on the rduino to event channels in the software.
The module can generate up to 8 channels of digital I/O, where each channel can be assigned as input or output and assigned to an event channel in the GUI.

This shield plugs into any standard arduino board and provides convenient BNC connectors to the 8 input or output pins, as well as a connector to the standardized HDMI connector that is also used on the acquisition board.

See the wiki for more info: https://open-ephys.atlassian.net/wiki/pages/viewpage.action?pageId=16384044

For a similar, but much more powerful signal output device, check out the PulsePal (https://sites.google.com/site/pulsepalwiki/home) which also works seamlessly with the Open Ephys GUI.


