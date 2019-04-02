# monomefighterjd

## Required: 
* A Mac
* Cycling 74 Max
* A 40h / 64 monome interface
* A thurst for controlling AV software which can be configured to respond to MIDI

## monomefighter
'monomefighterjd' is an update to James Drake's 'monomefighter' Max patch. The original 'monomefighter' allowed a 40h / 64 monome grid to be used as four MIDI Fighter interfaces. This is useful when interfacing a monome interface with a program like 'Traktor', for which MIDI Fighter mappings exist which use two or more MIDI Fighter interfaces.

## monomefighterjd
'monomefighterjd' adds SerialOSC support so that connecting to a device is a similar process to other modern monome patches.

## Setup
* Open Audio Midi Setup, enable the IAC Driver, and ensure there are eight buses.
* Configure your application to send / receive MIDI to the four virtual MIDI Fighters using the info below.

| Device | Position | Receives | Sends |
| --- | --- | --- | --- |
| MIDI Fighter 1 | Top left | IAC Bus 1 | IAC Bus 2 |
| MIDI Fighter 2 | Top right | IAC Bus 3  | IAC Bus 4 |
| MIDI Fighter 3 | Bottom left | IAC Bus 5  | IAC Bus 6 |
| MIDI Fighter 4 | Bottom right | IAC Bus 7  | IAC Bus 8 |

## Acknowledgements
The original 'monomefighter' was made by James Drake, who is tragically no longer with us.