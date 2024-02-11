Quickly hacked together Arduino shield to program other Arduino's. Can also be used to program the old AT90S1200 microcontroller using avrdude. I used [AVRDUDESS 2.14](https://github.com/ZakKemble/AVRDUDESS/releases/tag/v2.14
) with avrdude 7.0.

![](arduino%20as%20isp%20shield.jpg)

Use the [ArduinoISP.ino](https://github.com/rsbohn/ArduinoISP/blob/master/ArduinoISP/ArduinoISP.ino) sketch to program your Arduino.

Use this define:
```#define USE_OLD_STYLE_WIRING```

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)