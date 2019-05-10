# MIDI_polyphonic_synth_sine_wave
Turn Arduino Mega into an 8 bit polyphonic synthesizer using a MIDI input circuit and a R2R DAC.
# Arduino spec requirements
Arduino Mega - 26 KB Flash - 3KB SRAM
# R2R ladder Description
On the Arduino Mega wire pins 30-37 to the R2R DAC from the Most Signifigant Bit to the Least Signifigant Bit. Wire ground to the end of the last 2R resistor (LSB) and the output speaker to the front of the first 2R resisotr (MSB). You'll also want to make sure to connect your speaker ground to the ground of the arduino.
A better explanation can be found on Wikipedia https://en.wikipedia.org/wiki/Resistor_ladder
# MIDI input description
It is possible to wire the data pin directly to your Rxn port on your Arduino, but it is suggested that you use an optocoupler as described on the MIDI.org website https://www.midi.org/specifications-old/item/midi-din-electrical-specification
I found this youtube video do be helpful https://www.youtube.com/watch?v=GxfHijjn0ZM
