# 3DStar PGM
Este un programator universal pentru placile Arduino, ESP8266 si ESP32.

# Functii
- punte cositorita pe verso pentru a alege tensiunea de lucru: 5V sau 3.3V, alimenteaza cu pana la 1A placa ce urmeaza a fi programata
- TX/RX la 3.3V (functioneaza atat pentru sisteme 5V cat si 3.3V)
- 6 pini standard Arduino pentru programare
- punte cositorita pentru alegerea intre sistemul Arduino (cu DTR si CTS) si sistemul 3DStar pentru ESP cu RESET (pe pinul DTR) si GP0 (pe pinul CTS)
- pentru programarea ESP alegeti metoda NodeMCU de resetare/programare

# Adaptoare
Pentru programarea placilor ESP sunt disponibile mai multe adaptoare:
- ESP-01 / ESP-01S
- ESP-07x / ESP-12x
- adaptor conexiune rapida 3DStar (ESPContact, ESPbutton, etc.)

# Info
Adaptoarele permit programarea atat direct cu 3DStar PGM cat si cu un programator stil Arduino de 3,3V. Puntile se cositoresc corespunzator in functie de programator - catre GP0 si RST pentru 3DStar PGM sau DTR si CTS pentru cele de tip Arduino.