# MIDI_polyphonic_synth_sine_wave
Turn Arduino Mega into an 8 bit polyphonic synthesizer using a MIDI input circuit and a R2R DAC.
# Arduino spec requirements
Arduino Mega - 26 KB Flash - 3KB SRAM
# Circuit Description
On the Arduino Mega wire pins 30-37 to the R2R DAC from the Most Signifigant Bit to the Least Signifigant Bit. Wire ground to the end of the last 2R resistor (LSB) and the output speaker to the front of the first 2R resisotr (MSB). You'll also want to make sure to connect your speaker ground to the ground of the arduino.
A better explanation can be found on Wikipedia https://en.wikipedia.org/wiki/Resistor_ladder
