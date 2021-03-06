# Tiny Dice

## Introduction
The Tiny Dice is a PCB with 14 LEDs which represent 2 dice faces. The LEDS are controlled by an ATTINY 13 using charlieplexing. Code is uploaded to the device with AVR dude using a Bus Pirate, a AVRisp mk II or similar. It is not arduino compatable.

## Theory
<iframe id="ytplayer" type="text/html" width="640" height="360"
  src="https://www.youtube.com/embed/Bx5GLyJSWPk?autoplay=0&origin=http://hammeshacks.com"
  frameborder="0" allowfullscreen></iframe>
  
## Soldering The Dice
  
### Materials
  * 7 110 Ohm resistors
  * 2 capacitors 
  * 14 LEDs
  * 1 ATtiny13A
  * 1 button
  * 1 battery holder
  * 1 coin cell battery
  
### To solder the shield follow these steps:
<img alt="schmatic" src="picture.jpg" width="100%" />

1. Solder on all 14 LEDS paying attention to the LED orientation on the silkscreen.
2. Solder the ATtiny13A onto the PCB.
3. Solder the capacitors onto the PCB.
4. Solder the resistors onto the PCB. 
5. Solder the button onto the PCB.
6. Solder the battery holder onto the PCB.
7. (optional) Solder the pin headers onto the PCB.
  
### Uploading Code 
* Code comes pre-uploaded to the ATtiny. [The source can be found on github](https://github.com/emilyhammes/snowflake-firmware).

