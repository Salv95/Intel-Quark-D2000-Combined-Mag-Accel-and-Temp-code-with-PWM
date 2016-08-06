This folder contains the main.cpp file for the Temperature Sensor with PWM.

There is no template in ISSM for the temperaute sensor. This code displays the data received by the temperature sensor in celcius. The code provides pause with modulation(PWM) for the LED. The closer a temperature value is to zero, the faster the modulation will be. This also means that the modulation will be slower the further the temperature value is from zero.


Since the temperatue code cannot be found as a template in ISSM, in order to make the main.c file run, the bmc_150.c and bmc_150.h in the active project may need to be replaced with the ones provided by us in this directory https://github.com/Salv95/Intel-Quark-D2000-Combined-Mag-Accel-and-Temp-code-with-PWM/tree/master/bmc150