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
Daily:
These are daily automations like turning on lights at sunset, and turning them off at sunrise.

Events:
These are based on reoccuring events like Trash notifications.

Garage:
These are based on the garage door opening and closing and include things like turning on the driveway lights 
if the sun is below the horizon or notifying us if the garage door is open and the sun has set or notifying us
that the garage door failed to close

Media:
These are around the media player and will fire scenes based on when the Apple Tv starts playing or pauses.

Notifications:
Notifications are sent out when people come or go. Most of them are audible in the house, but some are text based

Presence:
The automations fire when we leave or arrive or around individuals travel. These are typically not notifications, but may 
set statuses that fire other automations.

Security:
These are all security related and mostly relate to sounding alarms when doors open while the security system is armed. 

Transit:
These are all based on when someone leaves work and simply provides an ETA home.

Weather:
Weather based automations that include sounding a tornado alarm. 

Zones:
These are all based on sensors that are connected to an old security system and monitor doors and windows. 

```

**Todo List**

* Add LED Strips to stairs, kitchen cabinets.
* Put Door Sensor in Mailbox
* Add RGB LED Bulbs to the lamps in the bedrooms and living areas
* Add Motion detectors
* Add more door sensors
* Add Smart locks to ensure all doors are locked.
* Replace other Smoke Detectors with Z-Wave Detectors.
