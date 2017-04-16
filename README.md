# ESPWebServer

## Introduction
This is a fork of ESP8266WebServer from https://github.com/esp8266/Arduino 
that is ported to work on ESP32 and ESP8266.

There were not a lot of changes.

## Reasoning

I needed a single web server that worked on both the ESP32 and ESP8266.  There
don't seem to be any out there, so I ported the ESP8266WebServer to work on both.

## Staging
If building with platformio this might need espressif32_staging, rather than
espressif32.

## License

This is licensed under the LGPL, as it is a derivative of https://github.com/esp8266/Arduino.
  Which is also licensed under the LGPL.


