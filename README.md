# ESP8266/32 (Home Assistant Switch) connected to PCF8574 controlling 8 relays

[![Build Status](https://travis-ci.com/debsahu/PCF8574_8Relay.svg?branch=master)](https://travis-ci.com/debsahu/PCF8574_8Relay) [![License: MIT](https://img.shields.io/github/license/debsahu/PCF8574_8Relay.svg)](https://opensource.org/licenses/MIT) [![version](https://img.shields.io/github/release/debsahu/PCF8574_8Relay.svg)](https://github.com/debsahu/PCF8574_8Relay/releases/tag/1.1.2) [![LastCommit](https://img.shields.io/github/last-commit/debsahu/PCF8574_8Relay.svg?style=social)](https://github.com/debsahu/PCF8574_8Relay/commits/master)

Home Assistant Switch for 8 Relays

- Code can compile on ESP8266/32
- PCF8574 can be used to extend the GPIO of ESP8266/32
- 8 ports of PCF8574 is connected to 8 Relay module

[![PCF8574_8Relay](https://img.youtube.com/vi/XXXXXXXX/0.jpg)](https://www.youtube.com/watch?v=XXXXXXXX)

## Libraries Needed

[platformio.ini](https://github.com/debsahu/PCF8574_8Relay/blob/master/platformio.ini) is included, use [PlatformIO](https://platformio.org/platformio-ide) and it will take care of installing the following libraries.

| Library                   | Link                                                                                              |
|---------------------------|---------------------------------------------------------------------------------------------------|
|MQTT                       |https://github.com/256dpi/arduino-mqtt                                                             |
|ArduinoJson v6.8.0         |https://github.com/bblanchon/ArduinoJson/releases/download/v6.8.0-beta/ArduinoJson-v6.8.0-beta.zip |
|WiFiManager Develop        |https://github.com/tzapu/WiFiManager/archive/development.zip                                       |
|PCF8574 Library            |https://github.com/xreef/PCF8574_library                                                           |

## Hardware

- todo