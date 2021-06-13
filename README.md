This is ultrasonic pest repellent device for bugs based on ATTINY85, resistors and PAM4803 amplifier with set of transducers

Sinusoidal waveform taken from the program memory of ATTINY 85 chip is send to its PORT B output and then converted to analog signal using DAC with 2R RESISTOR LADDER ( see here : https://en.wikipedia.org/wiki/Resistor_ladder). 

The PAM4803 amplifies this 40kHZ sinusoidal wave from ATTINY  to 2 x 3 Watt audio power wich gives 100dB of audio power nearby the device. 

10 ultrasonic transducer convert 10V peak-to-peak sinusoidal pulses to strong audio signal and that repels bugs nearby..

Components needed :
- 1 x ATTINY 85 chip
- 6 x 1K Ohm resistor
- 4 x 470 Ohm resistor
- 1 x 10K Ohm potentiometer for adjusting amplification
- 1 x PAM4803 stereo audio amplifier module 2 x 3Watt
- 1 x 100uF electrolytic capacitor
- 1 x 470nF capacitor
- (At least) 10 x 40kHZ ultrasonic transducer

Compilation script compileattiny85 can be used under Linux environmet with AVR-GCC and AVRDUDE installed to program ATTINY85 chip. 



