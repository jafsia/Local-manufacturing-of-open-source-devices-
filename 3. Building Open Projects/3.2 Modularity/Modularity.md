# The following questions can guide your way towards modular design:

Which are the main functions required for your hardware to operate?
The function is to pick up the sound coming from the beating of the heart
## Based on that, how many would modules you need to create and how would they group the components of your project? E.g., power module, microcontroller, communication, temperature sensor
The modules to create are, sound sensor, microcontroller, Terminal.
## How would you interconnect those modules? 
The sound sensor is connected to the arduino via a sound comparator; the parameters are broadcast via Bluetooth to a telephone for reading the test results
## How much space will your modules take once interconnected? (Think of enclosures!)
the device fits in a space where a bluetooth broadcast can be made.
