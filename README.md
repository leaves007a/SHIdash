# SHIdash

![alt text](https://github.com/leaves007a/SHIdash/blob/main/PXL_20230907_021441539.jpg?raw=true)

The Smart Home Info Dashboard (SHIdash) uses an e-ink screen and an ESP32 driver board (both by Waveshare) to display information of smart home devices (e.g. air quality monitor, litterbox robot). It is based on Home Assistant OS and the ESPHome add-on.

The following hardware products are used in this project:

E-paper display  https://www.waveshare.com/product/7.5inch-e-paper-hat.htm

ESP32 driver board  https://www.waveshare.com/wiki/E-Paper_ESP32_Driver_Board

5x7 photoframe  https://www.target.com/p/rounded-rectangle-wood-table-frame-natural-threshold/-/A-86677088?preselect=86325304

Installation:
1. Install and configure the Home Assistant (HA) OS and the ESPhome addon (There are plenty of tutorials on the HA website)
   
2. Plug in the ESP32 board to a PC via USB. Flash the firmware via https://web.esphome.io/
  
3. Use the ESPhome webfront to flash SHIdash.yaml
