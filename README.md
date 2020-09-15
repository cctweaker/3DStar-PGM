# 3DStar PGM
Is intended to be used as a universal programmer for Arduino, ESP8266 and ESP32 boards.

# Features
- solder jumper to select 5V or 3.3V up to 1A to power your board
- 3.3V data lines (works for both 5V and 3.3V devices)
- standard Arduino pinout for programming
- solder jumpers to switch from Arduino DTR and CTS pins to ESP RESET and GPIO 0 pins
- for ESP it uses NodeMCU style reset/program

# Adapters
- designed to use adapters for different ESP boards
- ESP-01 / ESP-01S
- ESP-07x / ESP-12x
- 3DStar connection (ESPContact, ESPbutton, etc.)

# Info
Adapter boards are thought to be used mainly with this programmer, without needing any extra components but they can also be used with any Arduino serial programmer by adding a few components and changing 2 jumpers.