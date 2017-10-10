# Home-Assistant Config by [@thejeffreystone](http://www.twitter.com/thejeffreystone)
[Home Assistant](https://home-assistant.io/) configuration files (YAMLs)

This is version 2 of my Home Assistant Configuration and it is a work in progress. Most of the changes

Currently I am running HA on a Raspberry Pi 3.

**Devices I have :**
* Apple Devices (Macbooks, Mac Mini, iPhones, iPads)
* [Honeywell Wifi Thermostat](http://a.co/cqvrljP)
* [Amazon Echo Dot](http://a.co/7VYHqvw)
* [Smartthings](http://a.co/2xWyXF5)
* [GE Z-Wave Switches](http://a.co/3OUpcMf)
* [Aeon Energy Switchs](http://a.co/7aKBkst)
* [First Alert Z-Wave Smoke/CO2](http://a.co/iTuEjU8)
* [GoControl Z-Wave Bulbs](http://a.co/ajfXdIS)
* [Cree Connect Bulbs](http://a.co/91ddysL)
* [Foscam FI8918W](http://a.co/cExSWZ7)
* [GoControl Z-Wave Garage Door Opener](http://a.co/iw3H4zQ)
* [ZWave Door Sensor]( http://a.co/4Uj8d5r)
* [Sonoff WiFi Wireless Smart Switch ]( http://a.co/9v8KnBT) 
* AppleTv
* ChromeCast
* Roku Streaming Stick

**App Integrations**
* Amazon Echo Skill
* IFTTT
* Owntracks
* MQTT (For Smartthings and Owntracks)
* Google Maps (For Traffic/Travel Times)
* [Smartthings-MQTT-Bridge](https://github.com/stjohnjohnson/smartthings-mqtt-bridge)
* [Homebridge](https://github.com/nfarina/homebridge)

**Automations:**
```
LOCATION AWARENESS:
    Send notifications based on arrival and departure of zones as well as integration with Echo so Alexa can provide location when asked.

SUNSET:
    Turn on Outside lights and Living Room Lamp (100%)

SUNRISE:
    Turn off all lights

SECURITY
    When smoke is detected all lights turn on

```

**Todo List**

* Add LED Strips to stairs, kitchen cabinets.
* Put Door Sensor in Mailbox
* Add RGB LED Bulbs to the lamps in the bedrooms and living areas
* Add Motion detectors
* Add door sensors
* ~~Integrate with Google Maps to provide traffic and ETA for daily driving routes~~
* Add Smart locks to ensure all doors are locked.
* Replace other Smoke Detectors with Z-Wave Detectors.
