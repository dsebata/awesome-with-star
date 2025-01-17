# Information comes from [hobbyquaker/awesome-mqtt](https://github.com/hobbyquaker/awesome-mqtt)
# Awesome MQTT

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of MQTT related stuff.

MQTT is a lightweight client-server publish/subscribe messaging protocol, optimized for high-latency or unreliable networks. This protocol is a good choice for Internet of Things applications, Telemetry, Sensor Networks, Smart Metering, Home Automation, Messaging and Notification Services.

## Contents

- [Community Resources](#community-resources)
- [Broker](#broker)
- [Tools](#tools)
- [Clients](#clients)
- [Scripting](#scripting)
- [Interfaces](#interfaces)
    - [Makers](#makers)
    - [Industry](#industry)
    - [Telephony, PBX](#telephony-pbx)
    - [Operating System](#operating-system)
    - [Monitoring](#monitoring)
    - [Location Tracking](#location-tracking)
    - [Logging](#logging)
    - [Smart Home Hardware Interfaces](#smart-home-hardware-interfaces)
    - [Smart Home Integration Software](#smart-home-integration-software)
    - [Lighting](#lighting)
    - [Home Entertainment](#home-entertainment)
    - [Smart Metering](#smart-metering)
    - [Messaging](#messaging)
    - [Misc](#misc)
- [Visualization, Dashboards](#visualization-dashboards)
- [Architecture, Convention](#architecture-convention)
- [Security, Encryption](#security-encryption)


### Community Resources

* [mqtt.org](http://mqtt.org/).
* [MQTT community wiki](https://github.com/mqtt/mqtt.github.io/wiki).
* [Google Groups: MQTT](https://groups.google.com/forum/#!forum/mqtt).
* [IRC channel #mqtt on the freenode network](irc://irc.freenode.net/mqtt).
* [A list of public brokers](http://moxd.io/2015/10/17/public-mqtt-brokers/).

#### Blogs

* [Ben Hardill](https://www.hardill.me.uk/wordpress/tag/mqtt/)
* [Dominik Obermaier](http://forkbomb-blog.de/category/mqtt)
* [Jan-Piet Mens](https://jpmens.net/)
* [Nick O'Leary](https://knolleary.net/)

#### Talks

* [An Introduction to MQTT: Why HTTP isn't the King of the Internet of Things](https://www.youtube.com/watch?v=LKz1jYngpcU) - Shinji Kim, Robert Bird - Akamai, Samsung Developer Conference 2017.
* [Einführung in MQTT](https://www.youtube.com/watch?v=INYG4-xsa9c) - Dominik Obermaier & Jens Deters, [Building IoT](https://www.buildingiot.de/) conference 2016 (German).

### Broker

* [ActiveMQ](http://activemq.apache.org/) - A fast Java multiprotocol messaging and Integration Patterns server.
* [Aedes](https://github.com/mcollina/aedes) - Barebone MQTT broker that can run on any stream server, the node way. :star:440
* [Emitter](https://github.com/emitter-io/emitter) - A distributed, scalable and fault-tolerant publish-subscribe messaging platform based on MQTT protocol and featuring message storage. :star:1936
* [eMQTT](http://emqtt.io/) - The Massively Scalable MQTT Broker written in Erlang/OTP.
* [esp_uMQTT_broker](https://github.com/martin-ger/esp_mqtt) - A basic MQTT Broker on the ESP8266. :star:140
* [flespi](https://flespi.com/mqtt-broker) - Free cloud MQTT broker with private namespaces, MQTT 5.0 support and gorgeous limits.
* [hbmqtt](https://github.com/beerfactory/hbmqtt) - Python MQTT broker using asyncio. :star:507
* [HiveMQ](https://www.hivemq.com/) - Java based commercial MQTT Broker.
* [hrotti](https://github.com/alsm/hrotti) - A MQTT broker written in Go. :star:107
* [Moquette](https://github.com/moquette-io/moquette) - Java MQTT lightweight broker. :star:1330
* [Mosca](http://www.mosca.io/) - Mosca is a node.js MQTT broker, which can be used Standalone or Embedded in another Node.js application.
* [Mosquitto](http://mosquitto.org/) - "The" Open Source MQTT Broker.
* [MyQttHub](https://myqtthub.com) - Cloud MQTT broker.
* [Mystique](https://github.com/TheThingsIndustries/mystique) - An extendable MQTT broker written in Go, with HTTP capabilities for observability. Implements MQTT v3.1.1. :star:9
* [RabbitMQ](https://www.rabbitmq.com/mqtt.html) - RabbitMQ offers a MQTT Adapter.
* [SurgeMQ](https://zhen.org/categories/surgemq/) - High Performance MQTT Server and Client Libraries in Go.
* [VerneMQ](https://vernemq.com/) - an Apache2 licensed distributed MQTT broker, developed in Erlang.
* [Vert.x MQTT](https://github.com/vert-x3/vertx-mqtt) - Vert.x component to handle connections, communication and messages exchange with remote MQTT clients. :star:81

### Platforms

* [mainflux](https://www.mainflux.com/) - device management, data aggregation, data management, data analytics,connectivity and message routing and event management. Supported by Linux Software Foundation.
Core analytics
* [thingsboard](https://thingsboard.io/) - Device management, data collection, processing, event management, and visualization for your IoT projects.


### Tools

* [imqtt](https://github.com/shafreeck/imqtt) - Interactive MQTT packet manipulation shell based on IPython. :star:19
* [IoT-Testware](https://projects.eclipse.org/projects/technology.iottestware) - The Eclipse IoT-Testware is a collection of conformance test suites for IoT protocols enriched with additional tools for fuzzing and performance testing.
* [moxy](https://github.com/jvermillard/moxy) - A Golang MQTT proxy providing useful output traces to monitor and troubleshoot your MQTT communications. :star:16
* [MQTT Board](https://github.com/flespi-software/MQTT-Board) - Open-source diagnostic-oriented MQTT client tool. :star:16
* [mqtt-admin](https://github.com/hobbyquaker/mqtt-admin/) - Web based MQTT frontend. [Direct Link](https://hobbyquaker.github.io/mqtt-admin/). :star:87
* [mqtt-benchmark](https://github.com/chirino/mqtt-benchmark) - A benchmarking tool for MQTT Servers. :star:120
* [mqtt-client](https://github.com/sdeancos/mqtt-client) - A Simple MQTT Client command line (Python) (use paho lib) :star:6
* [mqtt-forget](https://github.com/hobbyquaker/mqtt-forget) - Command line tool to remove retained MQTT topics by wildcard. :star:5
* [mqtt-fuzz](https://github.com/F-Secure/mqtt_fuzz) - A simple fuzzer for the MQTT protocol. :star:43
* [mqtt-malaria](https://github.com/etactica/mqtt-malaria) - scalability and load testing utilities for MQTT environments. :star:220
* [MQTT-PWN](https://github.com/akamai-threat-research/mqtt-pwn) - MQTT-PWN intends to be a one-stop-shop for IoT Broker penetration-testing and security assessment operations. :star:48
* [mqtt-shell](https://github.com/pidster-dot-org/mqtt-shell) - A simple interactive shell for MQTT. :star:17
* [mqtt-spy](http://kamilfb.github.io/mqtt-spy/) - Java based MQTT frontend. Supports scripting.
* [mqtt_tree](https://github.com/poggenpower/mqtt_tree) - Displays all Topics in an expandable tree, helps to get an overview if you have a lot of clients publishing. (python, tkinter) :star:1
* [mqtt-utils](https://github.com/dsell/mqtt-utils) - A collection of MQTT utilities. :star:9
* [mqtt-wall](https://github.com/bastlirna/mqtt-wall) - Subscription only web-based client – like Twitter wall for MQTT. :star:29
* [mqtt-wildcard](https://github.com/hobbyquaker/mqtt-wildcard) - Node.js Module to match a MQTT Topic against wildcards. :star:12
* [MQTT.fx](http://mqttfx.jfx4ee.org/) - MQTT.fx is a MQTT Client written in Java based on Eclipse Paho. Supports scripting.
* [mqttcli](https://github.com/shirou/mqttcli) - MQTT Client for shell scripting. :star:74
* [MQTTInspector](https://github.com/ckrey/MQTTInspector) - A general MQTT testing app for iOS (iPhone and iPad). :star:64
* [MQTTLens](https://chrome.google.com/webstore/detail/mqttlens/hemojaaeigabkbcookmlgmdigohjobjm) - A Google Chrome application, which connects to a MQTT broker and is able to subscribe and publish to MQTT topics.
* [MQTT Explorer](https://mqtt-explorer.com/) - Tool to visualize your MQTT topics in a topic hierarchy, a MQTT swiss-army knife.
* [Python MQTT Client Shell](https://github.com/bapowell/python-mqtt-client-shell) - a text console-based, interactive shell for exercising various tasks associated with MQTT client communications. :star:19
* [Wireshark-MQTT](https://github.com/menudoproblema/Wireshark-MQTT) - MQTT dissector for Wireshark. :star:70

### Clients

* [CocoaMQTT](https://github.com/emqtt/CocoaMQTT) - MQTT for iOS and OS X written with Swift. :star:861
* [emqttc](https://github.com/emqtt/emqttc) - Asynchronous Erlang MQTT Client. :star:170
* [gmqtt](https://github.com/wialon/gmqtt) - Python MQTT v5.0 client (asyncio-based). :star:64
* [hbmqtt](https://github.com/beerfactory/hbmqtt) - Python MQTT client using asyncio. :star:507
* [aiomqtt](https://github.com/mossblaser/aiomqtt) - Async Python MQTT client based on paho-mqtt. :star:30
* [Hulaaki](https://github.com/suvash/hulaaki) - An Elixir library for clients communicating with MQTT brokers. :star:113
* [luamqtt](https://github.com/xHasKx/luamqtt/) - Pure-lua MQTT v3.1.1 and v5.0 client. :star:28
* [M2Mqtt](https://m2mqtt.wordpress.com/) - A MQTT client available for all .Net platforms (.Net Framework, .Net Compact Framework and .Net Micro Framework) and WinRT platforms (Windows 8.1, Windows Phone 8.1 and Windows 10).
* [Machine Head](https://github.com/clojurewerkz/machine_head) - A Clojure MQTT Client. :star:53
* [MIMIC MQTT Simulator](https://www.gambitcomm.com/site/mqttsimulator.php) - Simulate up to 100,000 MQTT clients per server for development/testing/deployment of IoT applications.
* [Moscapsule](https://github.com/flightonary/Moscapsule) - MQTT Client for iOS written in Swift. :star:210
* [Mosquitto-PHP](https://github.com/mgdm/Mosquitto-PHP) - A wrapper for the Mosquitto MQTT client library for PHP. :star:366
* [mqtt_cpp](https://github.com/redboltz/mqtt_cpp) - MQTT client for C++14 based on Boost.Asio. :star:88
* [mqtt_lua](http://geekscape.github.io/mqtt_lua/) - MQTT Client library for the Lua language.
* [MQTT-C](https://github.com/LiamBindle/MQTT-C) - A portable MQTT C client for embedded systems and PCs alike. :star:104
* [MQTT-Client-Framework](https://github.com/novastone-media/MQTT-Client-Framework) - iOS, OSX, tvOS native ObjectiveC MQTT Client Framework. :star:1405
* [mqtt-client](https://github.com/centamiv/mqtt-client) - A Polymer Web Component that implements a MQTT client (uses Paho mqttws31.js). :star:13
* [mqtt-elements](https://github.com/mqttjs/mqtt-elements) - Polymer elements for MQTT. :star:23
* [mqtt-rs](https://github.com/zonyitoo/mqtt-rs) - MQTT protocol library for Rust. :star:73
* [mqtt-stats](https://github.com/gambitcomminc/mqtt-stats) - Subscriber client to monitor MQTT Topic Statistics
* [mqtt-wrapper](https://www.webcomponents.org/element/hobbyquaker/mqtt-wrapper/elements/mqtt-wrapper) - Polymer Element that wraps other Elements and links them to MQTT topics.
* [mqtt.dart](https://github.com/jnguillerme/mqtt.dart) - Dart mqtt client. :star:35
* [MQTT.js](https://github.com/mqttjs) - MQTT client for Node.js.
* [mqtt](https://github.com/jeffallen/mqtt) - MQTT Clients, Servers and Load Testers in Go. :star:612
* [mqttex](https://github.com/alfert/mqttex) - MQTT implementation in Elixir. :star:44
* [MQTTKit](https://github.com/mobile-web-messaging/MQTTKit) - MQTT Objective-C client for iOS. :star:435
* [Paho](http://www.eclipse.org/paho/) - Open source client implementations (C/C++, Java, Python, Javascript, Go, C#).
* [pubsubclient](https://github.com/knolleary/pubsubclient) - A client library for the Arduino Ethernet Shield that provides support for MQTT. :star:2223
* [ruby-mqtt](https://github.com/njh/ruby-mqtt) - Pure Ruby gem that implements the MQTT protocol. :star:371
* [rumqtt](https://github.com/AtherEnergy/rumqtt) - A fast, lock free pure rust MQTT client. :star:148
* [tcl-mqtt](https://github.com/Tingenek/tcl-mqtt) - Small library to connect to a MQTT broker. Very, very basic. :star:3
* [TMQTTClient](http://jamiei.com/blog/code/mqtt-client-library-for-delphi/) - MQTT Client Library for Delphi.
* [Vert.x MQTT](https://github.com/vert-x3/vertx-mqtt) - Vert.x component that provides methods for connecting/disconnecting to a broker, publishing messages and subscribing to topics. :star:81
* [wolfMQTT](https://www.wolfssl.com/products/wolfmqtt/) - A client implementation of the MQTT written in C for embedded use. It supports SSL/TLS via the wolfSSL library.
* [MQTTnet](https://github.com/chkr1011/MQTTnet) - MQTT client and broker implementations in .NET. :star:986

### Scripting

* [logic4mqtt](https://github.com/owagner/logic4mqtt) - Java based Logic and scripting engine for use with MQTT. Uses Java's general scripting interface, so scripts can be written in a multitude of languages like Javascript, Groovy etc. :star:13
* [mqtt-scripts](https://github.com/hobbyquaker/mqtt-scripts/) - Node.js based script runner. :star:28
* [Node-RED](https://nodered.org/) - A visual tool for wiring the Internet of Things.


### Interfaces

#### Makers

* [arduinoTemps2mqtt](https://github.com/matbor/arduinoTemps2mqtt) - Arduino sketch, grab One-wire Temperature's and publish to a MQTT broker. :star:10
* [Basecamp](https://github.com/merlinschumacher/Basecamp) - An Arduino library to ease the use of the ESP32 in IoT projects. See [c't Magazin 2'2018 (German)](https://www.heise.de/select/ct/2018/02/1515452111258448). :star:247
* [esp_mqtt](https://github.com/tuanpmt/esp_mqtt) - MQTT client library for ESP8266. :star:966
* [mqtt-ir-transceiver](https://github.com/enc-X/mqtt-ir-transceiver) - ESP8266 based bidirectional gateway between MQTT and IR. Use with PlatformIO. :star:109
* [mqtt-with-micropython](https://docs.pycom.io/chapter/tutorials/all/mqtt.html) - Connect to MQTT with micropython and wipy/others (ESP32 inside)
* [MySensors](https://www.mysensors.org/) - Arduino NRF24L01 based sensor network with support for an MQTT gateway
* [nodemcu-gpiomqtt](https://github.com/hobbyquaker/nodemcu-gpiomqtt) - Lua script to connect ESP8266 GPIOs to MQTT. :star:6
* [pubsubclient](https://github.com/knolleary/pubsubclient) - A client library for the Arduino Ethernet Shield that provides support for MQTT. :star:2223
* [RFM69-MQTT-client](https://github.com/computourist/RFM69-MQTT-client) - Arduino RFM69 based sensors and MQTT gateway. :star:83
* [rpi2mqtt](https://github.com/hobbyquaker/rpi2mqtt) - Connect a RaspberryPis GPIOs and 1-Wire Temperature Sensors to MQTT. :star:14
* [xbee2mqtt](https://github.com/xoseperez/xbee2mqtt) - XBee to MQTT gateway. :star:19


#### Industry

* [CODESYS-MQTT](https://github.com/stefandreyer/CODESYS-MQTT) - A MQTT client for CODESYS PLC :star:20
* [spicierModbus2mqtt](https://github.com/mbs38/spicierModbus2mqtt) - Modbus master which publishes register values via MQTT. :star:5
* [mqtt2opcua](https://github.com/nzfarmer1/mqtt2opcua) - Bi Directional MQTT to OPCUA Bridge. :star:45
* [OPC Router](https://www.opc-router.com/4_1-mqtt-client-opc-router-plug-in-en/) - MQTT Gateway (publisher/subscriber) with various plug-ins (OPC UA Bridge, SQL Bridge, REST Bridge, SAP Bridge)

#### Telephony, PBX

* [agi-mqtt](https://github.com/zeha/agi-mqtt) - Interface between Asterisk and MQTT. :star:26
* [fritz2mqtt](https://github.com/akentner/fritz2mqtt) - Connect FRITZ!Box to MQTT. :star:5
* [sip2mqtt](https://github.com/MartyTremblay/sip2mqtt) - A SIP monitoring script that publishes incoming calls with CallerID to MQTT. :star:8


#### Operating System

* [mqtt-os-status](https://github.com/oskarhagberg/mqtt-os-status) - Operating-system related data, published to an MQTT broker at fixed intervals. :star:10
* [mqttlauncher](https://github.com/jpmens/mqtt-launcher) - Execute shell commands triggered by published MQTT messages. :star:102
* [mqttpc](https://github.com/hobbyquaker/mqttpc) - Control processes via MQTT. Ability to send signals via MQTT and to publish stdout/stderr or pipe MQTT payloads into stdin. :star:7
* [mqttwatchdir](https://github.com/jpmens/mqtt-watchdir) - Recursively watch a directory for modifications and publish file content to an MQTT broker. :star:24
* [psmqtt](https://github.com/eschava/psmqtt) - Utility reporting system health and status via MQTT. :star:41
* [WinThing](https://github.com/msiedlarek/winthing) - Remotely control Windows through MQTT. :star:59


#### Monitoring

* [check-mqtt](https://github.com/jpmens/check-mqtt) - A Nagios/Icinga plugin for checking connectivity to an MQTT broker. :star:44
* [nag2mqtt](https://github.com/DE-IBH/nag2mqtt) - Nagios event broker to MQTT gateway. :star:3
* [notify-by-mqtt](https://github.com/jpmens/notify-by-mqtt) - A Nagios/Icinga notification module which wraps data into JSON and fires it off to an MQTT broker. :star:12
* [mqtt2notifysend](https://github.com/David-Lor/MQTT2NotifySend) - Subscribe to a topic and show notifications from MQTT messages on Ubuntu & other notify-send compatible Linux distros. :star:3


#### Location tracking

* [OwnTracks](https://owntracks.org/) - Location tracking and geofencing for MQTT.


#### Logging

* [graylog-plugin-mqtt](https://github.com/graylog-labs/graylog-plugin-mqtt) - MQTT Input Plugin for Graylog. :star:11
* [influx4mqtt](https://github.com/hobbyquaker/influx4mqtt) - Subscribe to MQTT topics and insert into InfluxDB. :star:18
* [mqtt2elasticsearch](https://github.com/hobbyquaker/mqtt2elasticsearch) - Send MQTT messages to Elasticsearch. :star:2
* [mqtt2graphite](https://github.com/jpmens/mqtt2graphite) - Subscribe to MQTT topics and push to Graphite's Carbon server. :star:65
* [mqttcollect](https://github.com/jpmens/mqttcollect) - A collectd "Exec" plugin for MQTT. :star:17
* [mqtthandler](https://github.com/changyuheng/MQTTHandler) - A Python logging handler module for MQTT. :star:15
* [mqtt2mongodb](https://github.com/David-Lor/MQTT2MongoDB) - Subscribe to MQTT topics and insert into MongoDB. :star:2


#### Smart Home Hardware Interfaces

* [aqara-mqtt](https://github.com/monster1025/aqara-mqtt) - Aqara (Xiaomi) Gateway to MQTT bridge. :star:78
* [aqara2mqtt](https://github.com/hobbyquaker/aqara2mqtt) - Attach [Aqara](https://www.aqara.com/en/products.html) Smart Hubs to MQTT. :star:2
* [cul2mqtt](https://github.com/hobbyquaker/cul2mqtt) - Interface between [Busware CUL](http://shop.busware.de/product_info.php/cPath/1/products_id/29) (868MHz RF-Devices like ELV FS20, HMS, EM, ...) and MQTT. :star:8
* [domiqtt](https://github.com/etobi/domiqtt) - Connects to a Domiq Base (LCN) and translate from and to MQTT. :star:1
* [eno2mqtt](https://github.com/owagner/eno2mqtt) - Interface between an Enocean USB300 (TCM310) adapter and MQTT. :star:7
* [Evohome2mqtt](https://github.com/svrooij/evohome2mqtt) - MQTT Interface for the Honeywell Evohome system.
* [helios2mqtt](https://github.com/mreschka/helios2mqtt) - A daemon for syncing a helios easy controls system like my KWL EC 220D to MQTT. :star:1
* [hm2mqtt.js](https://github.com/hobbyquaker/hm2mqtt.js) - Interface between EQ-3's Homematic line of smarthome devices and MQTT. Supports Homematic IP. :star:20
* [homeeToMqtt](https://github.com/odig/homeeToMqtt) - Bidirectional Interface between homee and MQTT. :star:4
* [HS100toMQTT](https://github.com/dersimn/HS100toMQTT) - Gateway between TPLink HS100/HS110 and MQTT. :star:5
* [ipcam2mqtt](https://github.com/svrooij/ipcam2mqtt) - A small ftp server to receive movement images from ipcameras and turn them into mqtt alerts. :star:7
* [knx-mqtt-bridge](https://github.com/pakerfeldt/knx-mqtt-bridge) - ridges KNX and MQTT using the knx.js library. :star:9
* [knx2mqtt](https://github.com/owagner/knx2mqtt) - Interface between the KNX home automation standard and MQTT. :star:25
* [mcsMQTT](https://shop.homeseer.com/products/mcsmqtt-software-plug-in-for-hs3) - Plug-in for HS3 (HomeSeer).
* [mqtt-dss-bridge](https://github.com/cgHome/mqtt-dss-bridge) - MQTT digitalSTROM-Server Bridge. :star:3
* [mqtt2homekit](https://github.com/forty2/mqtt2homekit) - Roughly the opposite of [homekit2mqtt](https://github.com/hobbyquaker/homekit2mqtt): Control your HomeKit-enabled devices with MQTT and without Siri or iPhone. :star:15
* [node-lox-mqtt-gateway](https://github.com/alladdin/node-lox-mqtt-gateway) - Gateway for Loxone™ mini server to communicate with MQTT broker. :star:20
* [smartthings-mqtt-bridge](https://github.com/stjohnjohnson/smartthings-mqtt-bridge) - Bridge between [SmartThings](https://www.smartthings.com/) and MQTT. :star:300
* [Sonoff-Tasmota](https://github.com/arendst/Sonoff-Tasmota) - Firmware for Sonoff devices with native MQTT Support. :star:7452
* [xiaomi2mqtt](https://github.com/svrooij/node-xiaomi2mqtt) - bridge between the Xiaomi Smart Home Gateway Aquara and a MQTT server. :star:17
* [zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) - Allows you to use your Zigbee devices without the vendors (Xiaomi/TRADFRI/Hue) bridge/gateway. :star:2711


#### Smart Home Integration Software

* [control-freak](https://github.com/tx4x/control-freak) - IDE for IoT & friends. Built in MQTT support. :star:15
* [Domoticz](http://www.domoticz.com/) - Domoticz beta supports MQTT.
* [FHEM](http://fhem.de/fhem.html) has a [MQTT module](http://fhem.de/commandref.html#MQTT) since V5.6.
* [Home Assistant](https://www.home-assistant.io/) has a MQTT component.
* [Home.Pi](https://github.com/denschu/home.pi) is based on MQTT.
* [Homegear](https://homegear.eu/index.php/Main_Page) has build in MQTT support.
* [homekit2mqtt](https://github.com/hobbyquaker/homekit2mqtt) - Interface between [HAP-NodeJS](https://github.com/KhaosT/HAP-NodeJS) and MQTT. Control MQTT connected devices with Siri or HomeKit Apps. :star:212
* [ioBroker](https://github.com/ioBroker) has a [MQTT adapter](https://github.com/ioBroker/ioBroker.mqtt).
* [Lelylan](http://www.lelylan.com/) - IOT Cloud Platform. Microservices Architecture. For Developers.
* [Node-RED](https://nodered.org/) - A visual tool for wiring the Internet of Things, has native MQTT Support.
* [openHAB](https://github.com/openhab) has a [MQTT binding](https://github.com/openhab/openhab1-addons/wiki/MQTT-Binding).
* [pimatic](https://pimatic.org/) has a MQTT plugin.


#### Lighting

* [Arilux_AL-LC0X](https://github.com/mertenats/Arilux_AL-LC0X) - This is an alternative firmware for Arilux LED controllers which uses MQTT. :star:182
* [chromoflex2mqtt](https://github.com/owagner/chromoflex2mqtt) - Control Chromoflex USP3 RGB LED modules via MQTT. :star:2
* [h801/mqtt](https://github.com/open-homeautomation/h801/tree/master/mqtt) - Alternative firmware for the H801 LED dimmer that uses MQTT as a control channel. :star:32
* [hue2mqtt.js](https://github.com/hobbyquaker/hue2mqtt.js) - Interface between the Philips Hue bridge and MQTT. :star:16
* [MQTT DMX Controller](https://github.com/hobbyquaker/mqtt-dmx-controller) - DMX Controller with MQTT support. :star:26
* [mqtt-dmx-sequencer](https://github.com/hobbyquaker/mqtt-dmx-sequencer) - Headless counterpart to [MQTT DMX Controller](https://github.com/hobbyquaker/mqtt-dmx-sequencer) - use scenes and sequences exported from the MQTT DMX Controller and control them via MQTT. :star:9
* [sunricher-wifi-mqtt](https://github.com/magcode/sunricher-wifi-mqtt) - control Sunricher LED devices using MQTT. :star:9
* [TRADFRI2MQTT](https://github.com/hardillb/TRADFRI2MQTT) - MQTT Bridge for IKEA TRÅDFRI Light Gateway. :star:61


#### Home Entertainment

* [airtunes2mqtt](https://github.com/hobbyquaker/airtunes2mqtt) - MQTT controlled Multi-Room Audio with Airplay/Airtunes Devices. :star:31
* [bravia2mqtt](https://github.com/forty2/bravia2mqtt) - Control your Sony Bravia TV with MQTT. :star:8
* [broadlink-mqtt](https://github.com/eschava/broadlink-mqtt) - MQTT client to control BroadLink RM devices. :star:122
* [chromecast-mqtt-connector](https://github.com/nohum/chromecast-mqtt-connector) - Control your Google Chromecast devices using MQTT. :star:22
* [harmony-api](https://github.com/maddox/harmony-api) - A simple server allowing you to query/control multiple local Harmony Home Hubs over HTTP or MQTT. :star:314
* [htd2mqtt](https://github.com/TheOriginalAndrobot/htd2mqtt) - Bridge between an HTD Lync audio system and MQTT.
* [kodi2mqtt](https://github.com/owagner/kodi2mqtt) - Interface between a Kodi media center instance and MQTT. :star:58
* [lgtv2mqtt](https://github.com/hobbyquaker/lgtv2mqtt) - Interface between LG WebOS Smart TVs and MQTT. :star:48
* [lirc2mqtt](https://github.com/hobbyquaker/lirc2mqtt) - Send and receive infrared via [LIRC](www.lirc.org). :star:13
* [mopidy-mqtt](https://github.com/magcode/mopidy-mqtt) - MQTT features for Mopidy. :star:10
* [MQTT-DashCast-Docker](https://github.com/mukowman/MQTT-DashCast-Docker) - MQTT Docker to launch DashCast session on Chromecast. :star:1
* [mqtt2atlonamatrix](https://github.com/forty2/mqtt2atlonamatrix) - Control Atlona HDMI matrix switches with MQTT.
* [mqtt2tivoremote](https://github.com/forty2/mqtt2tivoremote) - Make TiVo DVR remote control available through an MQTT smarthome style interface. :star:3
* [onkyo2mqtt](https://github.com/owagner/onkyo2mqtt) - Interface between Onkyo AVR's EISCP network remote protocol and MQTT. Uses the onkyo-eiscp library. :star:9
* [sonos2mqtt](https://github.com/svrooij/sonos2mqtt) - A bridge between Sonos and MQTT. :star:18
* [VLC MQTT Module](https://wiki.videolan.org/Documentation:Modules/mqtt/) - Control VLC via MQTT.
* [xbmc2mqtt](https://github.com/gordonjcp/xbmc-mqtt) - A simple plugin for XBMC to listen for a particular topic on an MQTT broker, and display a popup message. :star:5
* [yamaha-avr2mqtt](https://github.com/akentner/yamaha-avr2mqtt) - A simple adapter for connection Yamaha AVR to MQTT. :star:3


#### Smart Metering

* [bcontrol2mqtt](https://github.com/hobbyquaker/bcontrol2mqtt) - Publish measurements from [TQ Energy Manager](https://www.tq-group.com/produkte/produktdetail/prod/energy-manager/extb/Main) to MQTT. :star:3


#### Messaging

* [mqtt-irc-bot](https://github.com/dobermai/mqtt-irc-bot) - A MQTT to IRC / IRC to MQTT bridge or bot. :star:17
* [mqttwarn](https://github.com/jpmens/mqttwarn) - Subscribe to MQTT topics (with wildcards) and notify pluggable services. :star:762
* [twitter-to-mqtt](https://github.com/knolleary/twitter-to-mqtt) - A python daemon that uses the Twitter Streaming API to access tweets and republishes them to an MQTT topic. :star:14


#### Misc

* [AlexaMqttBridge](https://github.com/mhdawson/AlexaMqttBridge) - Bridge between Amazon Alexa and Mqtt. :star:53
* [bt-mqtt-gateway](https://github.com/zewelor/bt-mqtt-gateway) - Easily extensible Bluetooth to MQTT gateway, currently supports: EQ3 smart thermostat, Xiaomi Mi Scale, Linak Desk, MySensors and Xiaomi Mi Flora plant sensor. :star:108
* [buderus2mqtt](https://github.com/krambox/buderus2mqtt) - Bridge between Buderus KM200 internet gateway and Mqtt. :star:10
* [dashbutton2mqtt](https://github.com/hobbyquaker/dashbutton2mqtt) - Publish Amazon Dash Button presses to MQTT. :star:12
* [flowerpower2mqtt](https://github.com/hobbyquaker/flowerpower2mqtt) - Publish measurements from Parrot Flower Power plant sensors to MQTT. :star:6
* [gBridge](https://github.com/kservices/gBridge) - gBridge allows you to control (almost) any smart home device, any smart home software, with Google Assistant. Therefore, it transforms actions received from Google by voice commands to MQTT messages. :star:88
* [haiku2mqtt](https://github.com/forty2/haiku2mqtt) - A bridge between Haiku smart fans and MQTT. :star:8
* [homely](https://github.com/baol/homely) - Collection of Go daemons for connecting Domoticz and other stuff. :star:11
* [kobold2mqtt](https://github.com/krambox/kobold2mqtt) - Bridge between Vorwerk Kobold Vr200 internet gateway and Mqtt.
* [leaf-python-mqtt](https://github.com/glynhudson/leaf-python-mqtt) - Extract data from Nissan Leaf API and post to mqtt. :star:18
* [miflora-mqtt-daemon](https://github.com/ThomDietrich/miflora-mqtt-daemon) - Linux service to send Xiaomi Mi Flora plant sensor data to an MQTT broker. :star:251
* [mqtt2ble](https://github.com/hardillb/mqtt2ble) - A way to bridge MQTT topics to BLE Gatt characteristics. :star:19
* [mqttclpro](https://github.com/dc297/mqttclpro) - MQTT Client with tasker integration Android app. :star:64
* [mqttDB](https://github.com/hobbyquaker/mqttDB) - A JSON store with MQTT interface. :star:19
* [node-mqtt-for-anki-overdrive](https://github.com/IBM-Cloud/node-mqtt-for-anki-overdrive) - Node.js Controller and MQTT API for Anki Overdrive. :star:48
* [parrot-sample](https://github.com/IBM-Cloud/parrot-sample) - Sample code which uses MQTT to control a Parrot AR Drone. :star:18
* [snowboy2mqtt](https://github.com/hobbyquaker/snowboy2mqtt) - Publish MQTT Messages on Snowboy Hotword Detection. :star:5
* [speedtest2mqtt](https://github.com/hobbyquaker/speedtest2mqtt) - Run speedtest-cli and publish results via MQTT. :star:4
* [unifi2mqtt](https://github.com/hobbyquaker/unifi2mqtt) - Publish connected clients from Ubiquiti Unifi to MQTT. :star:30
* [Valetudo](https://github.com/Hypfer/Valetudo) - Xiaomi (Roborock) Vacuum Robots Firmware with MQTT and Webinterface. :star:604
* [wlan-thermo-mqtt-addon](https://bitbucket.org/IOcastor/wlan-thermo-mqtt-addon/) - Addon for a popular DIY barbecue thermometer.
* Tasker (Automation for Android) [MQTT Publisher Plugin](https://play.google.com/store/apps/details?id=net.nosybore.mqttpublishplugin).

### Visualization, Dashboards

* [Crouton](http://crouton.mybluemix.net/crouton/gettingStarted) - A dashboard that taps into your IOT network, using only MQTT and JSON.
* [d3-MQTT-Topic-Tree](https://github.com/hardillb/d3-MQTT-Topic-Tree) - A MQTT Topic Tree viewer using the d3 collapsible tree and MQTT over websockets. :star:79
* [HelloIoT](https://github.com/adrianromero/helloiot) - HelloIoT is a MQTT client and dashboard application. :star:31
* [HOMR-REACT](https://github.com/klauserber/homr-react) - A configurable MQTT Visualization. :star:9
* [IoT OnOff](https://www.iot-onoff.com/) - Configurable iOS/Android app.
* [Linear MQTT Dashboard](https://github.com/ravendmaster/linear-mqtt-dashboard) - Easy, customizable control panel - MQTT-client. :star:41
* [MMM-mqtt](https://github.com/javiergayala/MMM-mqtt) - This is an extension for the MagicMirror². It provides the ability to subscribe to MQTT topics and display them. :star:12
* [MQTT Dash](https://play.google.com/store/apps/details?id=net.routix.mqttdash&hl=de) - Android App: With the app you can create dashboards for your MQTT enabled IoT Smart Home devices and applications.
* [mqtt-panel](https://github.com/fabaff/mqtt-panel) - A web interface for MQTT. :star:248
* [mqtt-svg-dash](https://github.com/jpmens/mqtt-svg-dash) - Subscribe to MQTT, extract JSON from a message and make lights blink on an SVG page. :star:48
* [mqtt2highcharts](https://github.com/matbor/mqtt2highcharts) - Plotting live numbered data from a subscribed mqtt topic using Highcharts. :star:53
* [node-red-dashboard](https://github.com/node-red/node-red-dashboard) - A dashboard UI for Node-RED. :star:648

Other tools that can be used to create Visualization/Dashboards can be found under [Platforms](#platforms) and [Smart Home Integration Software](#smart-home-integration-software).


### Architecture, Convention

* [mqtt-smarthome](https://github.com/mqtt-smarthome/mqtt-smarthome) - Smart home automation with MQTT as the central message bus - Architectural proposal. :star:264
* [The Homie Convention](https://github.com/homieiot/convention) - A lightweight MQTT convention for the IoT. :star:465

### Security, Encryption

* [Teserakt E4](https://teserakt.io/) - End-to-end encryption for MQTT and other M2M protocols - Commercial solution.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

