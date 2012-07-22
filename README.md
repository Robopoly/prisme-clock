# Clock for PRisme
This program makes a clock out of the [PRisme](http://robopoly.epfl.ch/kit-prisme). It can use the internal 8MHz RC oscillator (very inaccurate, but adjustable) or an external watch oscillator (32.768kHz) connected to the PC6 and PC7 pins, which is very accurate.

It can be used to call a function regularly over the day such as a watering system or a weather station...

The clock can be easily set by sending the time in _HHMMSS_ format by UART at 9600 baud (ex: 170531 sets time to 17 hours 5 minutes and 31 seconds).
