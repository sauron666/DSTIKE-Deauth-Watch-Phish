## ESP8266 DSTIKE Watch EvilTwin
This software allows you to easily perform a variety of actions to test 802.11 wireless networks by using an inexpensive ESP8266 WiFi SoC (System On A Chip).
## Main feature
- The deauthentication attack, is used to disconnect devices from their WiFi network.	
- It is capable of performing a social engineering attack to get a secret WPA / WPA2 password


## Compiling using Arduino IDE
First you have to install and open the Arduino IDE.
- In Arduino go to File -> Preferences add both URLs in Additional Boards Manager URLs https://raw.githubusercontent.com/SpacehuhnTech/arduino/main/package_spacehuhn_index.json
- Go to Tools -> Board -> Boards Manager, search "deauther" and install Deauther ESP8266 Boards
- Select your board at Tools -> Board and be sure it is at Deauther ESP8266 Boards (and not at ESP8266 Modules)!
- Extract the whole .zip file, and open WifiPhisher.ino with Arduino.
- Check your upload settings and press upload!

## Disclaimer
Usage of Wifiphisher for attacking infrastructures without prior mutual consistency can be considered as an illegal activity. It is the final user's responsibility to obey all applicable local, state and federal laws. Authors assume no liability and are not responsible for any misuse or damage caused by this program.
## This source code is built on [Deauther](https://github.com/SpacehuhnTech/esp8266_deauther)
