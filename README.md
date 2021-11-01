# Awesome Node-RED [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <img src="https://nodered.org/about/resources/media/node-red-hexagon.png" width="200" align="right" alt="Node-RED">

> Curated list of useful resources for Node-RED.

[Node-RED](https://nodered.org/) is a programming tool for wiring together hardware devices, APIs and online services in new and interesting ways.

It provides a browser-based editor that makes it easy to wire together flows using the wide range of nodes in the palette that can be deployed to its runtime in a single-click.

## Contents

- [Installation](#installation)
- [Nodes](#nodes)
- [Community](#community)
- [Contribute](#contribute)

## Installation

- [Running locally](https://nodered.org/docs/getting-started/local)
- [Running under Docker](https://github.com/node-red/node-red-docker)
- [c't-Smart-Home](https://github.com/ct-Open-Source/ct-Smart-Home) - A ready-to-use setup for home automation maintained by [german computer magazine c't](https://www.ct.de/smarthome).
- [RedMatic](https://github.com/rdmtc/RedMatic/wiki/Installation) - Install Node-RED on a CCU3, smart home automation hardware from the manufacturer eQ-3, popular especially in Germany.
- [ioBroker node-red Adapter](https://github.com/ioBroker/ioBroker.node-red) - Starts Node-RED instance within ioBroker and communicates with it.
## Nodes

- [node-red-contrib-aedes](https://github.com/martin-doyle/node-red-contrib-aedes) - MQTT Broker based on Aedes.
- [node-red-contrib-alarm](https://github.com/Anamico/node-red-contrib-alarm) - Build your own home alarm system with any number of panels, zones, sensors, triggers and automations.
- [node-red-contrib-bool-gate](https://flows.nodered.org/node/node-red-contrib-bool-gate) - Boolean logic gates.
- [node-red-contrib-browser-utils](https://github.com/ibm-early-programs/node-red-contrib-browser-utils) - Add browser functionality such as file upload, camera & microphone.
- [node-red-contrib-ccu](https://github.com/rdmtc/node-red-contrib-ccu) - Connect with Homematic, a series of smart home automation hardware from the manufacturer eQ-3, popular especially in Germany.
- [node-red-contrib-deconz](https://github.com/deconz-community/node-red-contrib-deconz) - The deCONZ REST plugin provides a REST-API to access Zigbee 3.0 (Z30), Zigbee Home Automation (ZHA) and Zigbee Light Link (ZLL) lights.
- [node-red-contrib-dockerode](https://github.com/naimo84/node-red-contrib-dockerode) -  Connects to Docker daemon.
- [node-red-contrib-flow-manager](https://flows.nodered.org/node/node-red-contrib-flow-manager) - Separates your flow json to multiple files.
- [node-red-contrib-fritz](https://github.com/bashgroup/node-red-contrib-fritz) - Provides easy access to your avm fritzbox. You can read and write the configuration of your fritzbox including the VoIP and Dect configuration.
- [node-red-contrib-german-holidays](https://github.com/rdmtc/node-red-contrib-german-holidays) - Getting german holidays or information if today/tomorrow is a holiday.
- [node-red-contrib-home-assistant](https://github.com/AYapejian/node-red-contrib-home-assistant) - Various nodes to assist in setting up communication with Home Assistant.
- [node-red-contrib-home-assistant-websocket](https://github.com/zachowj/node-red-contrib-home-assistant-websocket) - Various nodes using websockets to assist in setting up communication with Home Assistant.
- [node-red-contrib-homebridge-automation](https://github.com/NorthernMan54/node-red-contrib-homebridge-automation) - Integrate Homebridge Accessories into flows.
- [node-red-contrib-homekit-bridged](https://github.com/NRCHKB/node-red-contrib-homekit-bridged) - Collection of nodes which can be used to imitate HomeKit devices.
- [node-red-contrib-huemagic](https://github.com/Foddy/node-red-contrib-huemagic) - HueMagic provides several nodes and is the most in-depth and easy to use solution to control Philips Hue bridges, lights, groups, scenes, rules, taps, switches, buttons, motion sensors, temperature sensors and Lux sensors.
- [node-red-contrib-ical-events](https://github.com/naimo84/node-red-contrib-ical-events) - Get events from an ical-URL, a caldav-server or from iCloud.
- [node-red-contrib-image-output](https://github.com/rikukissa/node-red-contrib-image-output) - Simple image output node. Useful for previewing images (of face detecting, object recognition etc.) inside the flow editor.
- [node-red-contrib-influxdb](https://github.com/mblackstock/node-red-contrib-influxdb) - Save and query data from an influxdb time series database.
- [node-red-contrib-interval-length](https://github.com/bartbutenaers/node-red-contrib-interval-length) - Measure the (time) interval length between successive messages.
- [node-red-contrib-knx-ultimate](https://github.com/Supergiovane/node-red-contrib-knx-ultimate) - Control your KNX intallation. Single Node KNX IN/OUT with optional ETS group address importer and gateway simulation. 
- [node-red-contrib-modbus](https://github.com/biancoroyal/node-red-contrib-modbus) - All in one Modbus TCP and Serial package.
- [node-red-contrib-moment](https://github.com/totallyinformation/node-red-contrib-moment) - Produces a nicely formatted Date/Time string using the Moment.JS library. It's fully time zone/DST/locale aware.
- [node-red-contrib-noble-bluetooth](https://github.com/clausbroch/node-red-contrib-noble-bluetooth) - Based on noble for interaction with Bluetooth Low Energy (BLE) devices.
- [node-red-contrib-owntracks](https://github.com/hardillb/node-red-contrib-owntracks) - Converts Owntrack Messages into standard geo message and deals with encrypted locations.
- [node-red-contrib-os](https://github.com/Argonne-National-Laboratory/node-red-contrib-os) - Obtain system information.
- [node-red-contrib-simpletime](https://github.com/Paul-Reed/node-red-contrib-simpletime) - Adds time and date payloads with various formatting options, which can be retreived and used later in the flow.
- [node-red-contrib-slack](https://github.com/yayadrian/node-red-slack) - Interact with the Slack API.
- [node-red-contrib-stackhero-mysql](https://github.com/stackhero-io/node-red-contrib-stackhero-mysql) - Connect to a MySQL or a MariaDB database, using TLS (SSL) and compatible with "Caching SHA2 password" authentication method (MySQL >= 8).
- [node-red-contrib-string](https://github.com/steveorevo/node-red-contrib-string) - Provides native and extended chainable JavaScript string parsing and manipulation methods.
- [node-red-contrib-sun-position](https://github.com/rdmtc/node-red-contrib-sun-position) - Timer based flow control with dusk, dawn (and variations) and much more. Additional you can get sun and moon position or to control a flow by sun or moon position.
- [node-red-contrib-tado-client](https://github.com/mattdavis90/node-red-contrib-tado-client) - Connect to the Tado Web API.
- [node-red-contrib-telegrambot](https://github.com/windkh/node-red-contrib-telegrambot) - Contains a receiver and a sender node which act as a Telegram Bot.
- [node-red-contrib-twc-weather](https://github.com/johnwalicki/node-red-contrib-twc-weather) - The Weather Company and Weather Underground Personal Weather Station APIs.
- [node-red-contrib-uibuilder](https://github.com/TotallyInformation/node-red-contrib-uibuilder) - Provide an easy to use way to create dynamic web interfaces using any (or no) front end libraries for convenience.
- [node-red-node-watson](https://github.com/watson-developer-cloud/node-red-node-watson) - Interact with the IBM Watson services in IBM Cloud.
- [node-red-contrib-web-worldmap](https://github.com/dceejay/RedMap) - Provide a world map web page for plotting "things" on.
- [node-red-node-wol](https://github.com/node-red/node-red-nodes) - Send Wake-On-LAN (WOL) magic packets.
- [node-red-contrib-zigbee](https://github.com/hobbyquaker/node-red-contrib-zigbee) - Control Zigbee Devices via a CC253x Module.
- [node-red-contrib-zigbee2mqtt](https://github.com/andreypopov/node-red-contrib-zigbee2mqtt) - Zigbee2mqtt connectivity.
## Community

- [Node-RED Forum](https://discourse.nodered.org/)
- [Node-RED Blog](https://nodered.org/blog/)
- [Twitter](https://twitter.com/NodeRED)
- [reddit r/nodered](https://www.reddit.com/r/nodered/)
- [Redmatic Forum](https://homematic-forum.de/forum/viewforum.php?f=77)
- [HomeAssistant Forum](https://community.home-assistant.io/c/third-party/node-red/31)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
