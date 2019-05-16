# Long-Distance-Lamps
This code is designed to run on a Particle Photon. It's function is to create a set of twin 'lamps' that are linked together via WiFi. Both lamps are capable of independently changing to any desired color, and also sharing that color with the partner lamp. WiFi Setup is handled by the Particle Photon setup, but this can be pre-set if desired.

Each lamp has a number of devices for input. This includes three knobs, one button, and one touch sensor.

  -Each of the three knobs modifies one of the color values of the lamp (red, green, or blue).

  -The button's current function is to put the lamp into a color cycle mode, where the lamp shifts through all the colors. The lamp may        recieve colors from the partner lamp when in this color shifting mode, but it does not send colors.

  -The touch sensor is used for sending the lamp's current color to the partner lamp
  
Each lamp has two decices for output, and LED strip and a single LED

  -Each lamp is given one individually addressable LED strip containing 60 LEDS, but this can be modified if desired.
  
  -The single LED serves as an indicator if the partner lamp is turned on or not.
