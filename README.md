# AVR Gree IR remote control
Simple AVR library for Gree Air conditioner remote IR control
## Idea
This is a bare C code for avr microcontrollers, especially Atmega328P/Arduino to control Gree air conditioner using dedicated IR protocol.
## Assumption 
- Atmega 328P set to use 8 MHz internal oscillator.
- Infrared LED connected to PB3 pin via about 100 Ohm (depending on power voltage) resistor.
- Timer 2 is used to generate 38 kHz IR carrier signal.
- IR controlling codes are first recorder using separate tool and saved as an array in memory (this is done to avoid complex check cum calculations).
