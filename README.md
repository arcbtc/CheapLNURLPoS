

# CheapLNURLPoS
## $8 version of the <a href="https://github.com/arcbtc/LNURLPoS">LNURLPoS</a>

> <i>Join our <a href="https://t.me/makerbits">telegram support/chat</a>.</i>

<img style="width:500px" src="https://user-images.githubusercontent.com/33088785/145500962-7e2bb6c2-ee64-446f-adad-d6fbd780e259.JPG">

1.8 128/160 TFT PIN MAP: 
[VCC - 5V, GND - GND, CS - GPIO5, Reset - GPIO16, AO (DC) - GPI17, SDA (MOSI) - GPIO23, SCK - GPIO18, LED - 3.3V]

Uses the same hardware as my other PoS <a href="https://github.com/arcbtc/Quickening">TheQuickening</a>

 ## Hardware: 
 (USE THE TFT_eSPI LIBRARY IN THIS FOLDER FOR THE CORRECT DRIVERS!!!)
* ESP32 NODE32S
* 1.8 TFT 160/128
* 4x4 adhesive matrix keypad
* x8 female-female jumper cables

![ESP32 GPIO Map](https://i.imgur.com/PLP3YBG.jpg)

* ESP32 DevKit V1

![ESP32s GPIO Map](https://i.imgur.com/iK3pCjt.jpg)


## Installing arduino + libraries

Install the Arduino IDE,<br>
https://www.arduino.cc/en/Main/Software

Install the ESP32 hardware,<br>
https://github.com/espressif/arduino-esp32#installation-instructions

From "Manage Libraries" install,<br>
- Keypad
- ArduinoJson
- TFT_eSPI
- QRCode

![a](https://i.imgur.com/mCfnhZN.png)


