# Turntable VU meters

This is a schematic and PCB I've designed for stereo LED VU meter bars to be mounted in my turntable. It is based around the logarithmic variant of the LM3914, the LM3915, which thus works well for audio.

The LEDs are in a common anode configuration, which is connected to the rightmost pin of each wide connector.

The cathodes are connected to all the other pins of the connectors. The leftmost pin is the LED corresponding to the lowest volume, and the rightmost - 1 for peak volume.

The peak LED also has a small circuit to make it act as an actual peak indicator. This is accomplished with a capacitor.

The circuit is designed for ~12V input voltage, connected on the left connector. GND on top, +12V on bottom.

The bottom connector is for audio input, Left and right. It assumes the audio source shares the GND with the power source.

See the [blog post]() for more details on the build process and a bunch of photos.

