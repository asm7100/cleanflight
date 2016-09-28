# Board - STM32F103C8T6 AlienFlight (ALIENFLIGHTF1)
How to use a STM32103C8T6 for cleanflight, and whats pin's is used.

- STM32F103C8T6 MCU (ALIENFLIGHTF1)


## Pin connection
Mini USB connector up.
###Left side of PCB
- PA8 - Motor1
- PA9 - TX1 BT/TELEM Also to connect to your computer for flash and setup
- PA10 - RX1 BT/TELEM Also to connect to your computer for flash and setup
- PA11 - Motor2
- PA12 - BUZZER

- PB3 - LED 1
- PB4 - LED 0

- PB6 - Motor 3
- PB7 - Motor 4
- PB8 - Motor 5
- PB9 - Motor 6

###Right side of PCB
- PB11 - SDA Sensors
- PB10 - SCL Sensors
- PB1 - CH8 or Sonar ECHO
- PB0 - CH7 or Sonar TRIG
- PA7 - CH6 - Motor 8
- PA6 - CH5 - Motor 7

- PA4 - VBAT (Voltage divider 1/10)
- PA3 - CH4 or RX2 GPS 3V3
- PA2 - CH3 or TX2 GPS 3V3
- PA1 - CH2
- PA0 - CH1 PPM 3v3 RX
