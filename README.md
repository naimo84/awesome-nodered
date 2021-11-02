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

- [node-red-nodes](https://github.com/node-red/node-red-nodes) - Preinstalled nodes.
    ### Analysis

    - [node-red-node-badwords](https://github.com/node-red/node-red-nodes/tree/master/analysis/swearfilter) - Analyses the payload and tries to filter out any messages containing bad swear words. This only operates on payloads of type string. Everything else is blocked.

    - [node-red-node-wordpos](https://github.com/node-red/node-red-nodes/tree/master/analysis/wordpos) - Analyses the payload and classifies the part-of-speech of each word. The resulting message has msg.pos added with the results. A word may appear in multiple categories (eg, 'great' is both a noun and an adjective).

    ### Function

    - [node-red-node-datagenerater](https://github.com/node-red/node-red-nodes/tree/master/function/datagenerator) - A node that can generate dummy data in various formats, names, addresses, emails, numbers, words, etc.

    - [node-red-node-pidcontrol](https://github.com/node-red/node-red-nodes/tree/master/function/PID) - A PID control node for numeric inputs - provides simple contoll loop feedback capability.

    - [node-red-node-random](https://github.com/node-red/node-red-nodes/tree/master/function/random) - A simple random number generator - can generate integers for x to y - or floats between x and y.

    - [node-red-node-rbe](https://github.com/node-red/node-red-nodes/tree/master/function/rbe) - A simple node to provide report by exception and deadband / bandgap capability for simple inputs.

    - [node-red-node-smooth](https://github.com/node-red/node-red-nodes/tree/master/function/smooth) - A simple node to provide various functions across several previous values, including max, min, mean, high and low pass filters.


    ### Hardware

    - [node-red-node-arduino](https://github.com/node-red/node-red-nodes/tree/master/hardware/Arduino) - A collection of analogue & digital input & output nodes for the Arduino board - uses firmata protocol to talk to the board.

    - [node-red-node-beaglebone](https://github.com/node-red/node-red-nodes/tree/master/hardware/BBB) - A collection of analogue & digital input & output nodes for the [Beaglebone Black](http://beagleboard.org/black).

    - [node-red-node-blink1](https://github.com/node-red/node-red-nodes/tree/master/hardware/blink1) - Provides support for the [Blink1](http://blink1.thingm.com/) USB LED from ThingM.

    - [node-red-node-blinkstick](https://github.com/node-red/node-red-nodes/tree/master/hardware/blinkstick) - Provides support for the [BlinkStick](http://www.blinkstick.com/) USB LED device.

    - [node-red-node-digirgb](https://github.com/node-red/node-red-nodes/tree/master/hardware/digiRGB) - Provides support for the DigiSpark RGB USB LED.

    - [node-red-node-heatmiser](https://github.com/node-red/node-red-nodes/tree/master/hardware/heatmiser) - Read and writes settings for temperature and frost protection to Heatmiser thermostats.

    - [node-red-node-intel-galileo](https://github.com/node-red/node-red-nodes/tree/master/hardware/intel) - A collection of analogue & digital input & output nodes for the Intel Galileo and Edison.

    - [node-red-node-ledborg](https://github.com/node-red/node-red-nodes/tree/master/hardware/LEDborg) - A simple driver for the [LEDborg](https://www.piborg.org/ledborg) plug on module for Raspberry Pi.

    - [node-red-node-makeymakey](https://github.com/node-red/node-red-nodes/tree/master/hardware/makey) - A Node-RED node to read from a [MakeyMakey](http://www.makeymakey.com/) input device.

    - [node-red-node-pi-gpiod](https://github.com/node-red/node-red-nodes/tree/master/hardware/pigpiod) - An alternative to the default PI GPIO nodes that allows remote access - so a host machine can access a remote Pi (via network) and is better for driving multiple servos.

    - [node-red-node-pi-mcp3008](https://github.com/node-red/node-red-nodes/tree/master/hardware/mcp3008) - Allows A Raspberry Pi to node to read from MCP300x series Analogue to Digital Converter chips via the SPI bus.

    - [node-red-node-pi-neopixel](https://github.com/node-red/node-red-nodes/tree/master/hardware/neopixel) - Allows A Raspberry Pi to drive a strip of NeoPixels directly.

    - [node-red-node-pi-unicorn-hat](https://github.com/node-red/node-red-nodes/tree/master/hardware/unicorn) - Lets a Raspbeery Pi control a Pimorini Unicorn HAT 8x8 LED display.

    - [node-red-node-pibrella](https://github.com/node-red/node-red-nodes/tree/master/hardware/Pibrella) - Controls a [Pibrella](http://pibrella.com/) add-on board for a Raspberry-Pi.

    - [node-red-node-piface](https://github.com/node-red/node-red-nodes/tree/master/hardware/PiFace) - Adds support for the [PiFace](http://www.piface.org.uk/) interface module for Raspberry Pi.

    - [node-red-node-piliter](https://github.com/node-red/node-red-nodes/tree/master/hardware/PiLiter) - Controls a Pimorini Pi-LITEr 8 LED add-on board for a Raspberry-Pi.

    - [node-red-node-sensortag](https://github.com/node-red/node-red-nodes/tree/master/hardware/sensorTag) - Reads data from the Ti Bluetooh Low Energy (BLE) SensorTag device.

    - [node-red-node-wemo](https://github.com/node-red/node-red-nodes/tree/master/hardware/wemo) - Basic node to drive a [WeMo](http://www.belkin.com/us/Products/home-automation/c/wemo-home-automation/) socket and switch. Does not use discovery.

    - [n/A](https://github.com/node-red/node-red-nodes/tree/master/hardware/scanBLE) - Scans for a particular Bluetooth Low Energy (BLE) device.

    ### I/O

    - [node-red-node-discovery](https://github.com/node-red/node-red-nodes/tree/master/io/mdns) - Discovers other Avahi/Bonjour services on the network.

    - [node-red-node-emoncms](https://github.com/node-red/node-red-nodes/tree/master/io/emoncms) - Adds node to post to an [Emoncms](http://emoncms.org/) server.

    - [node-red-node-mqlight](https://github.com/node-red/node-red-nodes/tree/master/io/mqlight) - Adds nodes to send and receive using MQlight.

    - [node-red-node-ping](https://github.com/node-red/node-red-nodes/tree/master/io/ping) - Pings a machine and returns the trip time in mS. Returns false if no response received within 3 seconds, or if the host is unresolveable. Default ping is every 20 seconds but can be configured.

    - [node-red-node-serialport](https://github.com/node-red/node-red-nodes/tree/master/io/serialport) - Node to send messages to and receive messages from a physical serial port.

    - [node-red-node-snmp](https://github.com/node-red/node-red-nodes/tree/master/io/snmp) - Adds simple snmp receivers for single OIDs or OID tables.

    - [node-red-node-stomp](https://github.com/node-red/node-red-nodes/tree/master/io/stomp) - A Node-RED node to publish and subscribe to and from a [STOMP server](https://stomp.github.io/implementations.html#STOMP_Servers).

    - [node-red-node-wol](https://github.com/node-red/node-red-nodes/tree/master/io/wol) - Sends a Wake-On-LAN magic packet to the mac address specified. You may instead set msg.mac to dynamically set the target device mac to wake up.


    ### Parsers

    - [node-red-node-base64](https://github.com/node-red/node-red-nodes/tree/master/parsers/base64) - Converts a payload to/from base64 encoded format.

    - [node-red-node-geohash](https://github.com/node-red/node-red-nodes/tree/master/parsers/geohash) - Converts a lat, lon payload to/from geohash format.

    - [node-red-node-msgpack](https://github.com/node-red/node-red-nodes/tree/master/parsers/msgpack) - Converts a payload to/from msgpack binary packed format.

    - [node-red-node-what3words](https://github.com/node-red/node-red-nodes/tree/master/parsers/what3words) - Encodes or Decodes a lat, lon position into what3words text format.

    ### Social

    - [node-red-node-dweetio](https://github.com/node-red/node-red-nodes/tree/master/social/dweetio) - Uses [dweetio](https://dweet.io/) to send/receive messages.

    - [node-red-node-email](https://github.com/node-red/node-red-nodes/tree/master/social/email) - Sends and receives simple emails from services like gmail or smtp or imap servers.

    - [node-red-node-feedparser](https://github.com/node-red/node-red-nodes/tree/master/social/feedparser) - Reads messages from an atom or rss feed.

    - [node-red-node-irc](https://github.com/node-red/node-red-nodes/tree/master/social/irc) - Connects to an IRC server to send and receive messages.

    - [node-red-node-nma](https://github.com/node-red/node-red-nodes/tree/master/social/nma) - DEPRECATED as NMA closed down operations.

    - [node-red-node-notify](https://github.com/node-red/node-red-nodes/tree/master/social/notify) - Uses [Growl](http://growl.info/) to provide a desktop popup containing the payload. Only useful on the local Apple machine.

    - [node-red-node-prowl](https://github.com/node-red/node-red-nodes/tree/master/social/prowl) - Uses [Prowl](http://www.prowlapp.com/) to push the payload to an Apple device that has the Prowl app installed.

    - [node-red-node-pushbullet](https://github.com/node-red/node-red-nodes/tree/master/social/pushbullet) - Uses [PushBullet](https://www.pushbullet.com/) to push the payload to an Android device that has the app installed.

    - [node-red-node-pusher](https://github.com/node-red/node-red-nodes/tree/master/social/pusher) - Publish-Subscribe to a [Pusher](http://pusher.com/) channel/event.

    - [node-red-node-pushover](https://github.com/node-red/node-red-nodes/tree/master/social/pushover) - Sends alerts via [Pushover](https://pushover.net/).

    - [node-red-node-twilio](https://github.com/node-red/node-red-nodes/tree/master/social/twilio) - Uses [Twilio](https://www.twilio.com/) service to send/receive text messages.

    - [node-red-node-twitter](https://github.com/node-red/node-red-nodes/tree/master/social/twitter) - Listens to Twitter feeds and can also send tweets. ([nOTE**: this will break soon when Twitter remove their streaming API)

    - [node-red-node-xmpp](https://github.com/node-red/node-red-nodes/tree/master/social/xmpp) - Connects to an XMPP server to send and receive messages.


    ### Storage

    - [node-red-node-leveldb](https://github.com/node-red/node-red-nodes/tree/master/storage/leveldb) - Uses LevelDB for a simple key value pair database.

    - [node-red-node-mysql](https://github.com/node-red/node-red-nodes/tree/master/storage/mysql) - Allows basic access to a MySQL database. This node uses the **query** operation against the configured database. This does allow both INSERTS and DELETES. By it's very nature it allows SQL injection. *so be careful out there*

    - [node-red-node-sqlite](https://github.com/node-red/node-red-nodes/tree/master/storage/sqlite) - Supports read and write to a local sqlite database.

    ### Time

    - [node-red-node-suncalc](https://github.com/node-red/node-red-nodes/tree/master/time/suncalc) - Uses the suncalc module to generate an output at sunrise and sunset based on a specified location. Several choices of definition of sunrise and sunset are available.

    - [node-red-node-timeswitch](https://github.com/node-red/node-red-nodes/tree/master/time/timeswitch) - Lets the user set simple repeating timers for example for simple heating control, etc.

    ### Utility

    - [node-red-node-daemon](https://github.com/node-red/node-red-nodes/tree/master/utility/daemon) - Starts up (calls) a long running system program and pipes STDIN, STDOUT and STDERR to and from that process. Good for monitoring long running command line applications.

    - [node-red-node-exif](https://github.com/node-red/node-red-nodes/tree/master/utility/exif) - Extracts GPS and other EXIF information from a passed in jpeg image.

- [node-red-contrib-aedes](https://github.com/martin-doyle/node-red-contrib-aedes) - MQTT Broker based on Aedes.
- [node-red-contrib-actionflows](https://github.com/Steveorevo/node-red-contrib-actionflows) - Brings easy to use loops and OOP (object oriented programming) features.
- [node-red-contrib-alarm](https://github.com/Anamico/node-red-contrib-alarm) - Build your own home alarm system with any number of panels, zones, sensors, triggers and automations.
- [node-red-contrib-alexa-home](https://github.com/mabunixda/node-red-contrib-alexa-home) - The node just works wihtin your local network - no extra cloud stuff is required.
- [node-red-alexa-home-skill-v3-web](https://github.com/coldfire84/node-red-alexa-home-skill-v3-web) - Web Service/ API for Alexa and Google Home Node-RED Smart Home Control.
- [node-red-alexa-home-skill-v3-lambda](https://github.com/coldfire84/node-red-alexa-home-skill-v3-lambda) - Lambda function for node-red-alexa-home-skill-v3-web.
- [node-red-contrib-alexa-home-skill-v3](https://github.com/coldfire84/node-red-contrib-alexa-home-skill-v3) - Control things via Amazon Alexa *and* Google Home.
- [node-red-contrib-alexa-remote-cakebaked](https://github.com/cakebake/node-red-contrib-alexa-remote-cakebaked) - Interacting with the Alexa API. You can emulate routine behaviour, control and query your devices.
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
- [node-red-contrib-homee](https://github.com/stfnhmplr/node-red-contrib-homee) - Access the homee api and create virtual devices for homee.
- [node-red-contrib-homekit-bridged](https://github.com/NRCHKB/node-red-contrib-homekit-bridged) - Collection of nodes which can be used to imitate HomeKit devices.
- [node-red-contrib-huemagic](https://github.com/Foddy/node-red-contrib-huemagic) - Provides several nodes and is the most in-depth and easy to use solution to control Philips Hue bridges, lights, groups, scenes, rules, taps, switches, buttons, motion sensors, temperature sensors and Lux sensors.
- [node-red-contrib-ical-events](https://github.com/naimo84/node-red-contrib-ical-events) - Get events from an ical-URL, a caldav-server or from iCloud.
- [node-red-contrib-image-output](https://github.com/rikukissa/node-red-contrib-image-output) - Simple image output node. Useful for previewing images (of face detecting, object recognition etc.) inside the flow editor.
- [node-red-contrib-influxdb](https://github.com/mblackstock/node-red-contrib-influxdb) - Save and query data from an influxdb time series database.
- [node-red-contrib-stackhero-influxdb-v2](https://github.com/stackhero-io/node-red-contrib-stackhero-influxdb-v2) - Save and query data from an InfluxDB v2 time series database.
- [node-red-contrib-interval-length](https://github.com/bartbutenaers/node-red-contrib-interval-length) - Measure the (time) interval length between successive messages.
- [node-red-contrib-knx-ultimate](https://github.com/Supergiovane/node-red-contrib-knx-ultimate) - Control your KNX intallation. Single Node KNX IN/OUT with optional ETS group address importer and gateway simulation. 
- [node-red-contrib-lgtv](https://github.com/hobbyquaker/node-red-contrib-lgtv) - Control LG webOS Smart TVs.
- [node-red-contrib-loxone](https://github.com/codmpm/node-red-contrib-loxone) - Connect to the Loxone Miniserver.
- [node-red-contrib-mindconnect](https://github.com/mindsphere/node-red-contrib-mindconnect) - Upload timeseries, files and events to MindSphere.
- [node-red-contrib-modbus](https://github.com/biancoroyal/node-red-contrib-modbus) - All in one Modbus TCP and Serial package.
- [node-red-contrib-moment](https://github.com/totallyinformation/node-red-contrib-moment) - Produces a nicely formatted Date/Time string using the Moment.JS library. It's fully time zone/DST/locale aware.
- [node-red-contrib-noble-bluetooth](https://github.com/clausbroch/node-red-contrib-noble-bluetooth) - Based on noble for interaction with Bluetooth Low Energy (BLE) devices.
- [node-red-contrib-owntracks](https://github.com/hardillb/node-red-contrib-owntracks) - Converts Owntrack Messages into standard geo message and deals with encrypted locations.
- [node-red-contrib-os](https://github.com/Argonne-National-Laboratory/node-red-contrib-os) - Obtain system information.
- [node-red-contrib-s7](https://github.com/st-one-io/node-red-contrib-s7) - Interact with Siemens S7 PLCs.
- [node-red-contrib-self-healing](https://github.com/jpdias/node-red-contrib-self-healing) - A collection of nodes for making Node-RED more resilient by adding self-healing capabilities.
- [node-red-contrib-simpletime](https://github.com/Paul-Reed/node-red-contrib-simpletime) - Adds time and date payloads with various formatting options, which can be retreived and used later in the flow.
- [node-red-contrib-slack](https://github.com/yayadrian/node-red-slack) - Interact with the Slack API.
- [node-red-contrib-smartnora](https://github.com/andrei-tatar/node-red-contrib-smartnora) - Google smart home Action integration via Smart NORA.
- [node-red-contrib-sonos-plus](https://github.com/hklages/node-red-contrib-sonos-plus) - Control SONOS player in your local network.
- [node-red-contrib-stackhero-mysql](https://github.com/stackhero-io/node-red-contrib-stackhero-mysql) - Connect to a MySQL or a MariaDB database, using TLS (SSL) and compatible with "Caching SHA2 password" authentication method (MySQL >= 8).
- [node-red-contrib-string](https://github.com/steveorevo/node-red-contrib-string) - Provides native and extended chainable JavaScript string parsing and manipulation methods.
- [node-red-contrib-sun-position](https://github.com/rdmtc/node-red-contrib-sun-position) - Timer based flow control with dusk, dawn (and variations) and much more. Additional you can get sun and moon position or to control a flow by sun or moon position.
- [node-red-contrib-tado-client](https://github.com/mattdavis90/node-red-contrib-tado-client) - Connect to the Tado Web API.
- [node-red-contrib-telegrambot](https://github.com/windkh/node-red-contrib-telegrambot) - Contains a receiver and a sender node which act as a Telegram Bot.
- [node-red-contrib-tuya-smart](https://github.com/hgross/node-red-contrib-tuya-smart) - Input nodes to interface with smart plugs, bulbs, etc. from tuya.
- [node-red-contrib-twc-weather](https://github.com/johnwalicki/node-red-contrib-twc-weather) - The Weather Company and Weather Underground Personal Weather Station APIs.
- [node-red-contrib-uibuilder](https://github.com/TotallyInformation/node-red-contrib-uibuilder) - Provide an easy to use way to create dynamic web interfaces using any (or no) front end libraries for convenience.
- [node-red-contrib-whatsappbot](https://github.com/robertsLando/node-red-contrib-whatsappbot) - Whatsapp Bot.
- [node-red-node-watson](https://github.com/watson-developer-cloud/node-red-node-watson) - Interact with the IBM Watson services in IBM Cloud.
- [node-red-contrib-web-worldmap](https://github.com/dceejay/RedMap) - Provide a world map web page for plotting "things" on.
- [node-red-contrib-zigbee](https://github.com/hobbyquaker/node-red-contrib-zigbee) - Control Zigbee Devices via a CC253x Module.
- [node-red-contrib-zigbee2mqtt](https://github.com/andreypopov/node-red-contrib-zigbee2mqtt) - Zigbee2mqtt connectivity.
- [node-red-contrib-zwave-js](https://github.com/zwave-js/node-red-contrib-zwave-js) - Integrates Z-Wave node based on Z-Wave JS.
- [node-red-node-typescript-starter](https://github.com/alexk111/node-red-node-typescript-starter) - Quick-start template repository for creating new node sets in TypeScript.

## Community

- [Node-RED Forum](https://discourse.nodered.org/)
- [Node-RED Blog](https://nodered.org/blog/)
- [Twitter](https://twitter.com/NodeRED)
- [reddit r/nodered](https://www.reddit.com/r/nodered/)
- [Redmatic Forum](https://homematic-forum.de/forum/viewforum.php?f=77)
- [HomeAssistant Forum](https://community.home-assistant.io/c/third-party/node-red/31)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
