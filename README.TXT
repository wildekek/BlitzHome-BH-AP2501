# BlitzHome BH-AP2501 

Convert your [BlitzHome BH-AP2501](https://nl.banggood.com/BlitzHome-BH-AP2501-Air-Purifier-Smart-WiFi-and-PM2_5-Monitor-H13-True-HEPA-Filter-Filtration-System-Cleaner-Odor-Eliminators-Ozone-Free-Remove-99_97-pencent-Pet-Allergies-Smoke-Dust-Auto-Mode-Alexa-and-Google-Home-Control-p-1964173.html?cur_warehouse=CZ&ID=47184) Air Purifier with ESPHome and integrate it with Home Assistant.

## Why?
Blitzhome chose to work with Tuya for connectivity, which means using their cloud.
I don't like:
* Sending my data to China
* Slow response because of a roundtrip to a server
* Asking me for a subscription to their service to integrate with Home Assistant
* Not working when there is a connectivity issue

## How?
* Open the device by popping open the top panel and removing all the top screws
* Remove the WiFi carrier board
* [Replace the Tuya WBR3 MCU with an ESP8266](https://blakadder.com/replace-tuya-esp12/)
* Flash it with [ESPHome](https://web.esphome.io/)
* Use the yaml file in this repo for configuration

## What works?
All the things!