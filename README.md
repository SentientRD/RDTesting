ProjectTestRD1
==============

First test of the Node-Red projects

### About

Flow 1 is some random testings I had done just pushing outputs to the GPIO pins on the Pi. 
This was just to familiarize myself with making flows in Node-Red. Some parts include trying to get an Analog input from a DHT_11 sensor but I could not figure it out.

Flow 2 was a cleaner version of testing and output pin. 
This Flow outputs a Digital output to GPIO 23. 

The "RELAY On:0" injection string just inputs a 0 on the GPIO 23 to turn the Relay Module to Normally Closed allowing the 5v line to supply power to the Red_LED.

The "RELAY Off:1" injection string simply does the opposite and it inputs a 1 on GPIO 23 to turn the Relay Module to Normally Open, opening the cicuit and cutting Power to the Red_LED

The "Pi Mouse Middle" takes the middle scroll wheel input from the Raspberry Pi and allows control over the Digital Output from GPIO 23. Holding down the middle button inputs a 1 and no input on the middle button inputs a 0.


This is your project's README.md file. It helps users understand what your
project does, how to use it and anything else they may need to know.