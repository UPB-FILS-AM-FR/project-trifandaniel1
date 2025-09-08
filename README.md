# Your Project Name
Telecomanda wireless pentru controlul pozitiei cursorului
| | |
|-|-|
|`Author` | Trifan Iulian Daniel

## Description
Telecomanda pentru controlul pozitiei cursorului prin touchpad/joystick si butoane pentru clicks
## Motivation
Am nevoie de o metoda sa ma uit la serial mai comfortabil.
## Architecture

### Block diagram

<!-- Make sure the path to the picture is correct -->
![Block Diagram](schematics/block_diagram.png)

### Schematic

![Schematic](schematics/kicad_schematic.png)

### Components


<!-- This is just an example, fill in with your actual components -->

| Device | Usage | Price |
|--------|--------|-------|
| Arduino Uno | Placa | [34.99 RON](https://www.optimusdigital.ro/en/avr-boards/4561-development-board-compatible-with-arduino-uno-r3-atmega328p-atmega16u2-50-cm-cable.html) |

| Joystick shield | Joystick Shield | [32,99 RON](https://ardushop.ro/ro/electronica/999-shield-joystick-6427854013514.html?gad_source=1&gad_campaignid=22058879462&gbraid=0AAAAADlKU-4LI9_Rh9WI-VlfmfVgGHi1d&gclid=CjwKCAjwruXBBhArEiwACBRtHX1qwJBiXnskHcLCrIZoMd5jZhwQ6WCPg6KxH3oL0nNBLwp8b-a_2BoCuLcQAvD_BwE) |

### Libraries

<!-- This is just an example, fill in the table with your actual components -->

| Library | Description | Usage |
|---------|-------------|-------|
| [lib-name1](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |
| [lib-name2](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |

## Log

<!-- write every week your progress here -->

### Week 6 - 12 May
Gasirea ideei , alegerea pieselor.
### Week 7 - 19 May
Realegerea pieselor in urma unor probleme provocate de ESP32 si bateria LiPo (era ars adaptorul de la baterie si am renuntat la ideea de wireless), in urma faptului ca a trebuit sa lucrez cu cablu pentru alimentare in lipsa bateriei, am decis si sa nu mai implementez wireless. (conexiunea fiind facuta prin cablu)
### Week 20 - 26 May
Scrierea codului si finalizarea functionalitatilor. In urma faptului ca arduino uno r3 are doar functionalitate slave , a trebuit sa recurd la un HDI si am ales python pentru translatarea semnalelor din Arduino IDE in semnale de miscare a mouse-ului si click-urile lui.

## Reference links
https://projecthub.arduino.cc/sraykov08/joystick-shield-94386a
<!-- Fill in with appropriate links and link titles -->

[Tutorial 1](https://www.youtube.com/watch?v=wdgULBpRoXk&t=1s&ab_channel=BenEater)

[Article 1](https://www.explainthatstuff.com/induction-motors.html)

[Link title](https://projecthub.arduino.cc/)
