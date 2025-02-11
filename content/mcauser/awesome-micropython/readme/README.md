# Awesome Micropython Overview

A curated list of awesome MicroPython libraries, frameworks, software and resources.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/mcauser/awesome-micropython/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 mcauser/awesome-micropython](https://github.com/mcauser/awesome-micropython) · ⭐ 1.5K · 🏷️ Programming Languages

[ [Daily](/content/mcauser/awesome-micropython/README.md) / [Weekly](/content/mcauser/awesome-micropython/week/README.md) / Overview ]

---

<p align="center">
  <a href="https://awesome-micropython.com/" style="display:block"><img src="https://raw.githubusercontent.com/mcauser/awesome-micropython/master/docs/img/logo.svg"></a>
</p>
<p align="center">
  <a href="https://awesome.re">
    <img alt="Awesome" src="https://awesome.re/badge-flat.svg">
  </a>
</p>
<hr>

A curated list of awesome MicroPython libraries, frameworks, software and resources.

[MicroPython](https://micropython.org/) is a lean and efficient implementation of the Python 3 programming language that includes a small subset of the Python standard library and is optimised to run on microcontrollers and in constrained environments.

## Contents

*   [Libraries](#libraries)
    *   [AI](#ai)
    *   [Audio](#audio)
    *   [Communications](#communications)
    *   [Display](#display)
    *   [IO](#io)
    *   [Mathematics](#mathematics)
    *   [Motion](#motion)
    *   [Sensors](#sensors)
    *   [Scheduling](#scheduling)
    *   [Storage](#storage)
    *   [Threading](#threading)
    *   [User Interface](#user-interface)
    *   [Utilities](#utilities)
*   [Community](#community)
*   [Tutorials](#tutorials)
*   [Books](#books)
*   [Frameworks](#frameworks)
*   [Resources](#resources)
*   [Development](#development)
    *   [Code Generation](#code-generation)
    *   [Debugging](#debugging)
    *   [Firmware](#firmware)
    *   [IDEs](#ides)
    *   [Logging](#logging)
    *   [Shells](#shells)
*   [Miscellaneous](#miscellaneous)
*   [Contributing](#contributing)

## Libraries

Other places you can look for MicroPython Libraries:

*   [PyPi](https://pypi.org/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+Implementation+%3A%3A+MicroPython) - This filter shows just the MicroPython libraries on PyPi. Note: You cannot `pip install` MicroPython libraries. See the [MicroPython docs](https://docs.micropython.org/en/latest/reference/packages.html) for more information on managing packages with MicroPython.
*   [GitHub Search](https://github.com/search?q=micropython) - Search GitHub for repositories containing MicroPython.
*   [GitHub Topic - MicroPython](https://github.com/topics/micropython) - Browse GitHub Topics for projects tagged with MicroPython.
*   [Libraries.io](https://libraries.io/search?q=micropython) - Libraries.io query for MicroPython.
*   [GitLab Explore](https://gitlab.com/explore?sort=latest_activity_desc\&utf8=%E2%9C%93\&name=micropython\&sort=latest_activity_desc) - Explore repositories on GitLab.
*   [Codeberg Explore](https://codeberg.org/explore/repos?tab=\&sort=recentupdate\&q=micropython) - Explore repositories on Codeberg.

### AI

*   [MicroMLP (⭐182)](https://github.com/jczic/MicroMLP) - A micro neural network multilayer perceptron for MicroPython (used on ESP32 and Pycom modules).
*   [MicroPython-NeuralNetwork](https://gitlab.com/olivierlenoir/MicroPython-NeuralNetwork) - Neural Network for MicroPython.
*   [upython-chat-gpt (⭐30)](https://github.com/karlsoderby/upython-chat-gpt) - ChatGPT for MicroPython.
*   [emlearn-micropython (⭐109)](https://github.com/emlearn/emlearn-micropython) - Efficient Machine Learning engine for MicroPython.

### Audio

*   [micropython-jq6500 (⭐19)](https://github.com/rdagger/micropython-jq6500) - Driver for JQ6500 UART MP3 modules.
*   [KT403A-MP3 (⭐11)](https://github.com/jczic/KT403A-MP3) - Driver for KT403A, used by DFPlayer Mini and Grove MP3 v2.0.
*   [micropython-buzzer (⭐19)](https://github.com/fruch/micropython-buzzer) - Play Nokia compose and mid files on buzzers.
*   [micropython-dfplayer (⭐14)](https://github.com/redoxcode/micropython-dfplayer) - Library to control the DFPlayer mini MP3 player module.
*   [micropython-dfplayer (⭐43)](https://github.com/ShrimpingIt/micropython-dfplayer) - Driver for DFPlayer Mini using UART.
*   [micropython-longwave (⭐11)](https://github.com/MattMatic/micropython-longwave) - WAV player for MicroPython board.
*   [micropython-vs1053 (⭐27)](https://github.com/peterhinch/micropython-vs1053) - Asynchronous driver for VS1053b MP3 player.
*   [micropython-midi (⭐2)](https://github.com/EMATech/micropython-midi) - A MIDI implementation example for MicroPython.
*   [upy-rtttl (⭐39)](https://github.com/dhylands/upy-rtttl) - Python Parser for Ring Tone Text Transfer Language (RTTTL).
*   [micropython-i2s-examples (⭐247)](https://github.com/miketeachman/micropython-i2s-examples) - Examples for I2S support on microcontrollers that run MicroPython.
*   [micropython-osc (⭐66)](https://github.com/SpotlightKid/micropython-osc) - A minimal OSC client and server library for MicroPython.
*   [micropython-sgtl5000 (⭐3)](https://github.com/rdagger/micropython-sgtl5000) - Library for SGTL5000 Low Power Stereo Codec w/ Headphone Amp.
*   [umidiparser (⭐34)](https://github.com/bixb922/umidiparser) - MIDI file parser for MicroPython, CircuitPython and Python.
*   [micropython-tas2505 (⭐2)](https://github.com/miketeachman/micropython-tas2505) - MicroPython driver for the Texas Instruments TAS2505 Digital Input Class-D Speaker Amplifier.
*   [yx5300 (⭐6)](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/yx5300.py) - MP3 player that can be controlled via a serial interface.
*   [micropython\_nonblocking\_buzzer (⭐1)](https://github.com/jornamon/micropython_nonblocking_buzzer) - A nonblocking implementation of a buzzer class that allows you to play basic melodies or sound patterns without blocking the main loop while the sound is being played.

### Communications

#### APIs

*   [micropython-utelegram (⭐87)](https://github.com/jordiprats/micropython-utelegram) - Telegram API wrapper for MicroPython.
*   [uEagle (⭐4)](https://github.com/jcalbert/uEagle) - MicroPython Rainforest EAGLE client.
*   [micropython-youtube-api (⭐13)](https://github.com/UnexpectedMaker/micropython-youtube-api) - YouTube API in MicroPython.
*   [micropython\_esp8266\_tweetbot (⭐10)](https://github.com/ayoko/micropython_esp8266_tweetbot) - Tweet bot for MicroPython v1.8.4 (ESP8266).
*   [telegram-upy (⭐44)](https://github.com/gabrielebarola/telegram-upy) - Telegram API wrapper for MicroPython.
*   [micropython-thingspeak (⭐13)](https://github.com/radeklat/micropython-thingspeak) - Library for sending data to thingspeak.com from IoT devices running MicroPython (such as ESP8266).
*   [micropython\_pushbullet (⭐3)](https://github.com/gsampallo/micropython_pushbullet) - Simple example of how to use PushBullet with MicroPython on ESP8266.
*   [esp32-youtube-display (⭐17)](https://github.com/alvarowolfx/esp32-youtube-display) - Display YouTube metrics using Google API and MicroPython.
*   [micropython-spotify-web-api (⭐19)](https://github.com/tltx/micropython-spotify-web-api) - A library for using Spotify's web API from a IoT device with MicroPython.
*   [micropython\_demo\_bot (⭐13)](https://github.com/gsampallo/micropython_demo_bot) - Little example of how to create a bot for Telegram.
*   [micropython-basicdweet (⭐4)](https://github.com/jacklinquan/micropython-basicdweet) - A python module for very basic APIs of the free dweet service.
*   [micropython-dweeter (⭐3)](https://github.com/jacklinquan/micropython-dweeter) - A python module for messaging through the free dweet service.
*   [micropython-cryptodweet (⭐2)](https://github.com/jacklinquan/micropython-cryptodweet) - A python module for very basic APIs of the free dweet service with encryption.
*   [micropython-linenotify (⭐10)](https://github.com/PerfecXX/micropython-linenotify) - MicroPython library for sending notifications to Line Notify with ESP8266 and ESP32.
*   [micropython-telegram-bot (⭐33)](https://github.com/antirez/micropython-telegram-bot) - MicroPython telegram bot library: simple way to put your IoT projects on the cloud.
*   [MicroPython-GoogleSheet (⭐16)](https://github.com/PerfecXX/MicroPython-GoogleSheet) - Fetch, update or append data in Google Sheets using Google Apps Script API.

#### Authentication

*   [micropython-firebase-auth (⭐8)](https://github.com/WoolDoughnut310/micropython-firebase-auth) - Firebase Auth implementation for MicroPython.

#### Bluetooth

*   [PyBoard-HC05-Android (⭐11)](https://github.com/KipCrossing/PyBoard-HC05-Android) - Pyboard HC05 Bluetooth adapter example application.
*   [uble (⭐86)](https://github.com/dmazzella/uble) - Lightweight Bluetooth Low Energy driver written in pure Python for MicroPython.
*   [MicroPythonBLEHID (⭐258)](https://github.com/Heerkog/MicroPythonBLEHID) - Human Interface Device (HID) over Bluetooth Low Energy (BLE) GATT library for MicroPython.
*   [upyble (⭐20)](https://github.com/Carglglz/upyble) - Command line tool for Bluetooth Low Energy MicroPython devices.
*   [micropython-xiaomi-ble-adv-parse](https://codeberg.org/scy/micropython-xiaomi-ble-adv-parse) - Passively retrieve sensor data from some Xiaomi Bluetooth Low Energy (BLE) sensors.
*   [mijia-temphum-upy](https://codeberg.org/scy/mijia-temphum-upy) - MicroPython library to read certain Xiaomi Mijia BLE temperature & humidity sensors.
*   [micropython-aioble-itag (⭐1)](https://github.com/mcauser/micropython-aioble-itag) - Examples using aioble to interact with iTag BLE keychain tags.
*   [micropython\_aioble\_examples (⭐2)](https://github.com/ekspla/micropython_aioble_examples) - A few aioble (asyncio BLE) examples of MicroPython using ESP32.

#### CAN

*   [micropython-spacecan](https://gitlab.com/alphaaomega/micropython-spacecan) - Spacecan is a MicroPython implementation of the SpaceCAN protocol for embedded systems.
*   [Robomaster-Micropython (⭐28)](https://github.com/JohnieBraaf/Robomaster-Micropython) - Robomaster S1 - MicroPython CAN BUS controller.
*   [micropython-mcp2515 (⭐28)](https://github.com/jxltom/micropython-mcp2515) - MicroPython MCP2515 driver, porting from Arduino MCP2515 CAN interface library.
*   [microPython\_MCP2515 (⭐5)](https://github.com/capella-ben/microPython_MCP2515) - A MicroPython library for the MCP2515 CAN bus controller.

#### Compression

*   [ufastlz (⭐16)](https://github.com/dmazzella/ufastlz) - MicroPython wrapper for FastLZ, a lightning-fast lossless compression library.
*   [tamp (⭐33)](https://github.com/BrianPugh/tamp) - A low-memory, MicroPython-optimized, DEFLATE-inspired lossless compression library.
*   [micropython-zipfile (⭐7)](https://github.com/jonnor/micropython-zipfile) - Read/write ZIP archive files. Ported from CPython, supports DEFLATE compression.

#### Cryptography

*   [ucryptography (⭐8)](https://github.com/dmazzella/ucryptography) - Lightweight porting of pyca/cryptography to MicroPython based on ARM Mbed TLS.
*   [mpyaes (⭐27)](https://github.com/iyassou/mpyaes) - MicroPython module for AES encryption.
*   [micropython-aes (⭐19)](https://github.com/piaca/micropython-aes) - AES algorithm with pure python implementation.
*   [ucrypto (⭐36)](https://github.com/dmazzella/ucrypto) - MicroPython package for doing fast RSA and elliptic curve cryptography, specifically digital signatures. ECDSA API design inspired from fastecdsa and implementation based on tomsfastmath.
*   [ucryptoauthlib (⭐41)](https://github.com/dmazzella/ucryptoauthlib) - Lightweight driver for Microchip Crypto Authentication secure elements written in pure Python for MicroPython.
*   [embit (⭐91)](https://github.com/diybitcoinhardware/embit) - A minimal Bitcoin library for MicroPython and Python 3 with a focus on embedded systems.
*   [microotp (⭐27)](https://github.com/gdassori/microotp) - An ESP8266 MicroPython OTP Generator.
*   [micropython-rsa-signing (⭐18)](https://github.com/artem-smotrakov/micropython-rsa-signing) - RSA signing on MicroPython.
*   [micropython-cryptomsg (⭐5)](https://github.com/jacklinquan/micropython-cryptomsg) - A MicroPython module to encrypt and decrypt messages with AES CBC mode.
*   [mprsa (⭐4)](https://github.com/git-n-pissed/mprsa) - A MicroPython module for creating, importing, and exporting RSA keys in DER and PEM formats with PKCS#1, PKCS#8, and X.509/SPKI structures, and signing/verifying and encryption/decryption using blinding and SHA-1 and SHA-256 hashing algorithms.
*   [mpy-mbedtls (⭐3)](https://github.com/Carglglz/mpy-mbedtls) - MicroPython bindings for some MbedTLS EC and x509 cert/csr functions.
*   [micropython-cryptocfb (⭐5)](https://github.com/jacklinquan/micropython-cryptocfb) - A Python module to encrypt and decrypt data with AES-128 CFB mode.
*   [tscp (⭐3)](https://github.com/shariltumin/tscp) - An endpoint-to-endpoint encryption based on Diffie-Hellman-Merkle with TLS1.3 styled handshake using MicroPython.

#### DNS

*   [aiodns (⭐15)](https://github.com/vshymanskyy/aiodns) - A small, versatile DNS client that provides an async version of `getaddrinfo` and works with any connectivity.
*   [ICantBelieveItsNotDNS (⭐19)](https://github.com/yschaeff/ICantBelieveItsNotDNS) - "I Can't Believe It's Not DNS!" (ICBIND) is an authoritative DNS server for the ESP8266 written in MicroPython.
*   [MicroDNSSrv (⭐75)](https://github.com/jczic/MicroDNSSrv) - A micro DNS server for MicroPython to simply respond to A queries on multi-domains with or without wildcards (used on Pycom modules & ESP32).
*   [tinydns (⭐32)](https://github.com/belyalov/tinydns) - Very simple DNS async server for MicroPython.
*   [micropython-captiveportal (⭐24)](https://github.com/metachris/micropython-captiveportal) -  Minimal async captive portal for MicroPython (compatible with uasyncio v3/MicroPython 1.13+ as well as earlier versions).
*   [Micropython-DNSServer-Captive-Portal (⭐16)](https://github.com/p-doyle/Micropython-DNSServer-Captive-Portal) - MicroPython WiFi AP Captive Portal with DNS and Web Server.

#### ESP-NOW

*   [mesh-espnow-micropython (⭐10)](https://github.com/shariltumin/mesh-espnow-micropython) - Dynamic Secure Mesh for Collaborative Nodes of IoT devices.

#### Ethernet

*   [Official WIZnet5k (⭐2)](https://github.com/andrewleech/wiznet_ioLibrary_Driver) - Driver for the WIZnet5x00 series of Ethernet controllers.
*   [micropy-ENC28J60 (⭐22)](https://github.com/przemobe/micropy-ENC28J60) - ENC28J60 Ethernet chip driver for MicroPython (RP2).
*   [RP2040 Ethernet example (⭐11)](https://github.com/SteveSEK/Raspberry-Pi-Pico-MicroPython-Ethernet) - Ethernet driver, example Python code and YouTube.
*   [micropython-ch9121 (⭐10)](https://github.com/wybiral/micropython-ch9121) - MicroPython library for controlling CH9121 Ethernet modules.

#### FTP

*   [micropython-ftplib (⭐37)](https://github.com/SpotlightKid/micropython-ftplib) - An FTP client library for MicroPython.
*   [FTP-Server-for-ESP8266-ESP32-and-PYBD (⭐152)](https://github.com/robert-hh/FTP-Server-for-ESP8266-ESP32-and-PYBD) - Small FTP server for ESP8266/ESP32/Pyboard on the MicroPython platform.
*   [MicroFTPServer (⭐36)](https://github.com/cpopp/MicroFTPServer) - Minimal FTP Server that can run on an ESP8266 with MicroPython.
*   [micropython-uaioftp (⭐3)](https://github.com/cwyark/micropython-uaioftp) - Lightweight FTP library for MicroPython.
*   [FtpTiny-Micropython (⭐9)](https://github.com/MZachmann/FtpTiny-Micropython) - Really small FTP server that runs in a thread.

#### GPS

*   [micropyGPS (⭐364)](https://github.com/inmcm/micropyGPS) - Full featured GPS NMEA sentence parser.
*   [micropython-gnssl76l (⭐6)](https://github.com/tuupola/micropython-gnssl76l) - MicroPython I2C driver for Quectel GNSS L76-L (GPS).
*   [mpy-agps (⭐13)](https://github.com/pulkin/mpy-agps) - MicroPython implementation of assisted location services (AGPS).
*   [Asynchronous GPS driver (⭐766)](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/GPS.md) - Receive and parse GPS data as a uasyncio task.

#### GSM

*   [micropython-upyphone (⭐425)](https://github.com/jeffmer/micropython-upyphone) - A GSM phone using Pyboard and SIM800l.
*   [micropython-sim800 (⭐17)](https://github.com/olablt/micropython-sim800) - MicroPython driver for SIM800.
*   [sim800 (⭐25)](https://github.com/basanovase/sim800) - Library for interfacing with SIM800 module in MicroPython.
*   [MicroPython-AM7020 (⭐3)](https://github.com/JiekangHuang/MicroPython-AM7020) - MicroPython driver for AM7020 Narrowband Internet of Things (NBIoT) module.
*   [SIM800L-micropython (⭐0)](https://github.com/aleppax/SIM800L-micropython) - MicroPython wrapper for common SIM800L AT commands.
*   [sim7600 (⭐4)](https://github.com/basanovase/sim7600) - MicroPython library for SIM7600 module.
*   [sim900 (⭐1)](https://github.com/basanovase/sim900) - MicroPython library for SIM900 GSM/GPRS module.

#### HTTP

*   [mrequests (⭐55)](https://github.com/SpotlightKid/mrequests) - A HTTP client module (not only) for MicroPython with an API similar to requests.

#### IoT

*   [microhomie (⭐79)](https://github.com/microhomie/microhomie) - MicroPython implementation of the Homie MQTT convention for IoT.
*   [uPyEcho (⭐56)](https://github.com/lemariva/uPyEcho) - Emulated Belkin WeMo device that works with Amazon Echo (Alexa) using MicroPython on an ESP32.
*   [SonosRemote (⭐57)](https://github.com/foosel/SonosRemote) - A remote for Sonos installations running on an ESP8266 and using Sonos HTTP API.
*   [micropython-home-assistant](https://gitlab.com/aapjeisbaas/micropython-home-assistant) - MicroPython-based scripts to extend your Home Assistant-driven home automation projects.
*   [micropython-iot (⭐94)](https://github.com/peterhinch/micropython-iot) - An approach to designing IoT applications using ESP8266, ESP32 or Pyboard D endpoints.
*   [iot-core-micropython (⭐52)](https://github.com/GoogleCloudPlatform/iot-core-micropython) - Use MicroPython to connect to Google Cloud IoT Core.
*   [SmartUPy (⭐14)](https://github.com/lemariva/SmartUPy) - Controlling "Tuya-type" smart power outlets using MicroPython.
*   [aws-iot-GET-POST-loop (⭐17)](https://github.com/manningt/aws-iot-GET-POST-loop) - MicroPython code which uses the AWS IoT REST API to GET/POST device state info.
*   [sensor-mqtt-homeassistant (⭐15)](https://github.com/DougWilkinson/sensor-mqtt-homeassistant) - An ESP8266/ESP32 MicroPython-based sensor platform for GPIO, DHT, analog, LED and more. Includes remote updates for .py code from web server and MQTT/Home Assistant integration.
*   [micropython-ha-mqtt-device (⭐16)](https://github.com/agners/micropython-ha-mqtt-device) - MicroPython module which allows creating Entites for HomeAssistant using MQTT Discovery.
*   [ESP8266-Home-Assistant-Smart-Socket (⭐2)](https://github.com/AnthonyKNorman/ESP8266-Home-Assistant-Smart-Socket) - This MicroPython project is to hack a Hyleton313 cheap WiFi smart socket.
*   [ESP8266-Home-Assistant-RGB-Bulb (⭐3)](https://github.com/AnthonyKNorman/ESP8266-Home-Assistant-RGB-Bulb) - This MicroPython project is to hack a TYWE3S board in a cheap WiFi RGB Bulb.
*   [uPyIoT (⭐6)](https://github.com/lemariva/uPyIoT) - Connect an M5Stack ATOM running MicroPython to the Google Cloud Platform (GCP) to collect air-quality variables obtained from reading sensors.
*   [micropython-switchbot-thermometer-hygrometer (⭐3)](https://github.com/hilch/micropython-switchbot-thermometer-hygrometer) - Read SwitchBot Thermometer/Hygrometer via Bluetooth.

#### IR

*   [micropython-necir (⭐15)](https://github.com/MattMatic/micropython-necir) - NEC infrared capture for TL1838 IR receiver LEDs.
*   [Micropython-IR (⭐13)](https://github.com/designerPing/Micropython-IR) - Pyboard infrared remote sniff and replay.
*   [micropython\_ir (⭐264)](https://github.com/peterhinch/micropython_ir) - Nonblocking device drivers to receive from IR remotes and for IR "blaster" apps.
*   [micropython-amg88xx (⭐21)](https://github.com/peterhinch/micropython-amg88xx) - Driver for Grid-EYE thermal infrared array sensor (Adafruit 3538).
*   [micropython-ys-irtm (⭐28)](https://github.com/mcauser/micropython-ys-irtm) - MicroPython examples for YS-IRTM 5V NEC Infrared UART transceivers.
*   [esp8266\_ir (⭐49)](https://github.com/ruoyu0088/esp8266_ir) - Control IR signal by WebSocket.
*   [micropython\_espX\_IR\_Transceiver (⭐8)](https://github.com/gamefunc/micropython_espX_IR_Transceiver) - MicroPython ESP32 IR Transceiver.
*   [pico-ir (⭐27)](https://github.com/bartoszadamczyk/pico-ir) - IR library for Raspberry Pi Pico.
*   [esp32-ir-remote (⭐9)](https://github.com/cbrand/esp32-ir-remote) - A MicroPython project for running ESP32 IR remotes.

#### LoRa

*   [loraE22 (⭐10)](https://github.com/matthias-bs/loraE22) - A MicroPython class for the Ebyte E22 Series LoRa modules.
*   [micropython-lora (⭐42)](https://github.com/wybiral/micropython-lora) - MicroPython library for controlling a Semtech SX127x LoRa module over SPI.
*   [micropython-aiolora (⭐4)](https://github.com/wybiral/micropython-aiolora) - MicroPython library for controlling a Semtech SX127x LoRa module with asyncio API.
*   [micropython-rylr (⭐4)](https://github.com/wybiral/micropython-rylr) - MicroPython library for controlling Reyax LoRa modules (RYLR896, RYLR406).
*   [silvergeko\_rfm9x (⭐1)](https://github.com/scopelemanuele/silvergeko_rfm9x) - Porting to MicroPython of adafruit\_rfm9x.py library.

#### LoRaWAN

*   [uPyLoRaWAN (⭐231)](https://github.com/lemariva/uPyLoRaWAN) - ESP32 using MicroPython meets LoRa and LoRaWAN.
*   [SX127x\_driver\_for\_MicroPython\_on\_ESP8266 (⭐148)](https://github.com/Wei1234c/SX127x_driver_for_MicroPython_on_ESP8266) - SX127x (LoRa transceiver) driver for (Micro)Python on ESP8266/ESP32/Raspberry Pi.
*   [LightLora\_MicroPython (⭐21)](https://github.com/MZachmann/LightLora_MicroPython) - Lightweight Interrupt-driven Semtech SX127x Library for MicroPython.
*   [u-lora (⭐74)](https://github.com/martynwheeler/u-lora) - Raspi-lora for MicroPython.
*   [sx127x\_esp (⭐13)](https://github.com/azorg/sx127x_esp) - Connect Ra-01 module base on LoRaTM sx127x chip to ESP8266/ESP32 under MicroPython.
*   [nanoserver (⭐6)](https://github.com/gradoj/nanoserver) - MicroPython embedded LoRaWAN server.
*   [micropySX126X (⭐112)](https://github.com/ehong-tl/micropySX126X) - Semtech SX126X LoRa driver for MicroPython and CircuitPython.

#### MDNS

*   [micropython-mdns (⭐62)](https://github.com/cbrand/micropython-mdns) - A pure Python implementation of MDNS with support for Service Discovery.

#### Modbus

*   [micropython-modbus](https://gitlab.com/extel-open-source/micropython-modbus) - MicroPython port of modbus-tk.
*   [micropython-modbus (⭐74)](https://github.com/techbase123/micropython-modbus) - Modbus Master library for MicroPython ESP32 devices. Based on pycom-modbus from Pycom.
*   [mp\_modbus (⭐12)](https://github.com/eydam-prototyping/mp_modbus) - Modbus library for MicroPython.
*   [micropython-modbus (⭐119)](https://github.com/brainelectronics/micropython-modbus) - ModBus TCP and RTU library supporting client and host mode. Based on pycom-modbus from Pycom.

#### MQTT

*   [micropython-mqtt (⭐610)](https://github.com/peterhinch/micropython-mqtt) - A 'resilient' asynchronous MQTT client: recovers from WiFi and broker outages.
*   [MQBoard (⭐123)](https://github.com/tve/mqboard) - A micro-framework for using MQTT with asyncio on MicroPython boards, primarily on the ESP32.
*   [pysmartnode (⭐116)](https://github.com/kevinkk525/pysmartnode) -  MicroPython Smart Home framework.
*   [umqtt\_aws\_iot (⭐21)](https://github.com/juwul/umqtt_aws_iot) - Publish UMQTT messages with MicroPython to AWS IoT.
*   [sonoff-mqtt by davea (⭐59)](https://github.com/davea/sonoff-mqtt) - MicroPython scripts to control Sonoff/ESP8266 using MQTT.
*   [micropython-sonoff-switch (⭐10)](https://github.com/kfricke/micropython-sonoff-switch) - Implements an MQTT-controllable switch for the iTead Sonoff Switch using MicroPython.
*   [micropython-thingspeak-mqtt-esp8266 (⭐26)](https://github.com/miketeachman/micropython-thingspeak-mqtt-esp8266) - Publish and Subscribe to ThingSpeak using MQTT with MicroPython running on ESP8266/ESP32 platforms.
*   [uMQTT (⭐9)](https://github.com/andrewmk/uMQTT) - MQTT publish for MicroPython on the WiPy board.
*   [micropython-mqtt (⭐37)](https://github.com/chrismoorhouse/micropython-mqtt) - Async MQTT library with auto reconnect for MicroPython devices such as the ESP32 or Pycom devices.
*   [micropython-adafruit-mqtt-esp8266 (⭐54)](https://github.com/miketeachman/micropython-adafruit-mqtt-esp8266) - Using MQTT to Publish/Subscribe to Adafruit IO. MicroPython/CircuitPython implementation on ESP8266/ESP32.
*   [mqtt\_upython (⭐0)](https://github.com/matbgn/mqtt_upython) - MQTT Client using MicroPython on ESP8266.
*   [tinymqtt (⭐7)](https://github.com/belyalov/tinymqtt) - Async MQTT client for MicroPython.
*   [micropython-mqtt-thingspeak (⭐26)](https://github.com/miketeachman/micropython-mqtt-thingspeak) - Publish and Subscribe to ThingSpeak using MQTT with MicroPython.
*   [micropython-sparkplugb (⭐10)](https://github.com/sciotaio/micropython-sparkplugb) - MicroPython compatible implementation of the Eclipse Sparkplug B Specification.

#### NBD

*   [unbd (⭐4)](https://github.com/pulkin/unbd) - Micro implementation of network block device (NBD) for MicroPython.

#### NFC

*   [micropython-nfc (⭐12)](https://github.com/rolandvs/micropython-nfc) - Using NFC with MicroPython.
*   [micropython\_pn532 (⭐10)](https://github.com/luiz-brandao/micropython_pn532) - Driver for PN532 NFC/RFID breakout boards based on Adafruit CircuitPython (UART).
*   [NFC\_PN532\_SPI (⭐42)](https://github.com/Carglglz/NFC_PN532_SPI) - Partial port of Adafruit CircuitPython to MicroPython of PN532 NFC/RFID control library (SPI).

#### NTP

*   [esp8266\_ntp\_webserver (⭐3)](https://github.com/Roterfux/esp8266_ntp_webserver) - MicroPython + ESP8266 + NTP + web server.
*   [micropython-ntpd (⭐2)](https://github.com/dave2/micropython-ntpd) - An implementation of an NTP daemon in MicroPython.
*   [micropython\_ntpserver (⭐3)](https://github.com/GrantGMiller/micropython_ntpserver) - An NTP server written for MicroPython.
*   [micropython-ntpclient (⭐6)](https://github.com/wieck/micropython-ntpclient) - NTP client for MicroPython using uasyncio.
*   [micropython-ntp (⭐9)](https://github.com/ekondayan/micropython-ntp) - Robust NTP library for MicroPython.

#### OneWire

*   [Official OneWire (⭐2.5k)](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/bus/onewire) - For devices using the OneWire bus, eg Dallas DS18x20.
*   [Onewire\_DS18X20 (⭐13)](https://github.com/robert-hh/Onewire_DS18X20) - Classes for driving the DS18x20 sensor with the OneWire protocol for Pycom MicroPython.
*   [micropython\_arduino\_control (⭐0)](https://github.com/kevinkk525/micropython_arduino_control) - MicroPython library to control an Arduino remotely, with corresponding Arduino code.

#### Onkyo EISCP

*   [eiscp-micropython (⭐3)](https://github.com/cbrand/eiscp-micropython) - MicroPython port for the Onkyo-EISCP protocol used, among others, by Pioneer.

#### OTA

*   [micropython-ota-updater (⭐373)](https://github.com/rdehuyss/micropython-ota-updater) - OTA Updater for MicroPython.
*   [Micropython-ESP32-OTA (⭐15)](https://github.com/AkhileshThorat/Micropython-ESP32-OTA) - MicroPython updater based on rdehuyss/micropython-ota-updater.
*   [senko (⭐96)](https://github.com/RangerDigital/senko) - Simplest OTA update solution for your MicroPython projects.

#### Proxy

*   [uProxy (⭐6)](https://github.com/shawwwn/uProxy) - An asyncio-based, memory-efficient HTTP/HTTPS/SOCKS4/SOCKS5 forward proxy server for MicroPython, compatible with CPython.

#### Radio

*   [micropython-radio (⭐56)](https://github.com/peterhinch/micropython-radio) - Protocols for nRF24L01 2.4GHz radio modules.
*   [micropython-rfsocket (⭐34)](https://github.com/wuub/micropython-rfsocket) - MicroPython implementation of popular 433MHz-based RFSockets.
*   [Official nRF24L01 (⭐2.5k)](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/radio/nrf24l01) - Official driver for nRF24L01 2.4GHz radio modules.
*   [micropython\_remote (⭐74)](https://github.com/peterhinch/micropython_remote) - Capture and replay 433MHz remote control codes. Control remote switched power adaptors.
*   [micropython-ys-rf34t (⭐9)](https://github.com/mcauser/micropython-ys-rf34t) - MicroPython examples using YS-RF34T 433MHz ASK/OOK UART transceivers.
*   [FM\_Talkie (⭐7)](https://github.com/Wei1234c/FM_Talkie) - FM Walkie Talkie using RDA5820N.
*   [micropython-TEA5767 (⭐44)](https://github.com/alankrantas/micropython-TEA5767) - MicroPython ESP8266/ESP32 driver for TEA5767 FM radio module.
*   [micropython-ppm-decoder (⭐11)](https://github.com/dastultz/micropython-ppm-decoder) - Utility for decoding an R/C receiver PPM frame signal.
*   [ESP32-433Mhz-Receiver-and-Tools (⭐10)](https://github.com/Aschhoff/ESP32-433Mhz-Receiver-and-Tools) - ESP32 433MHz receiver written in MicroPython and tools for Windows.
*   [ESP32-433Mhz-Transmitter (⭐11)](https://github.com/Aschhoff/ESP32-433Mhz-Transmitter) - A pure MicroPython RF transmitter. You can create and add your own encoder.
*   [pico\_jjy\_tx (⭐6)](https://github.com/elehobica/pico_jjy_tx) - JJY transmitter for Raspberry Pi Pico W.
*   [pico\_dcf77\_tx (⭐11)](https://github.com/elehobica/pico_dcf77_tx) - DCF77 transmitter for Raspberry Pi Pico W.
*   [micropython\_dcf77 (⭐2)](https://github.com/dsiggi/micropython-dcf77) - DCF77 receiver and decoder.
*   [EByte\_LoRa\_E220\_micropython\_library (⭐22)](https://github.com/xreef/EByte_LoRa_E220_micropython_library) - MicroPython LoRa EBYTE E220 devices.
*   [EByte\_LoRa\_E22\_micropython\_library (⭐8)](https://github.com/xreef/EByte_LoRa_E22_micropython_library) - MicroPython LoRa EBYTE E22 devices.
*   [EByte\_LoRa\_E32\_micropython\_library (⭐6)](https://github.com/xreef/EByte_LoRa_E32_micropython_library) - MicroPython LoRa EBYTE E32 devices.

#### RC receiver

*   [micropython-ppm\_reader (⭐11)](https://github.com/redoxcode/micropython-ppm_reader) - Library to decode PPM signals coming from a RC receiver.

#### REPL

*   [webrepl](https://micropython.org/webrepl) - MicroPython WebREPL.
*   [zepl](https://gitlab.com/zepl1/zepl) - MicroPython WebREPL Console Application using ZeroMQ.
*   [jupyter\_micropython\_remote](https://gitlab.com/alelec/jupyter_micropython_remote) - Jupyter kernel to directly execute code on a MicroPython board over the serial/web REPL.
*   [FBConsole (⭐58)](https://github.com/boochow/FBConsole) - Framebuffer console class for MicroPython.

#### RFID

*   [micropython-mfrc522 (⭐170)](https://github.com/wendlers/micropython-mfrc522) - Driver for NXP MFRC522 RFID reader/writer.
*   [micropython-wiegand (⭐30)](https://github.com/pjz/micropython-wiegand) - Wiegand protocol reader.
*   [urdm6300 (⭐2)](https://github.com/membermatters/urdm6300) - A MicroPython driver for the popular RDM6300 RFID card reader.

#### RPC

*   [ujrpc (⭐5)](https://github.com/zcattacz/ujrpc) - JSON RPC for MicroPython.

#### RTC

*   [micropython-tinyrtc-i2c (⭐64)](https://github.com/mcauser/micropython-tinyrtc-i2c) - Driver for DS1307 RTC and AT24C32N EEPROM.
*   [Micropython\_TinyRTC (⭐4)](https://github.com/AnthonyKNorman/Micropython_TinyRTC) - Driver for DS1307 RTC.
*   [micropython-mcp7940 (⭐1)](https://github.com/mattytrentini/micropython-mcp7940) - Driver for the Microchip MCP7940 RTC.
*   [micropython-ds1302-rtc (⭐47)](https://github.com/omarbenhamid/micropython-ds1302-rtc) - DS1302 RTC Clock driver for MicroPython.
*   [DS3231micro (⭐16)](https://github.com/notUnique/DS3231micro) - MicroPython library for DS3231.
*   [micropython-ds1307 (⭐7)](https://github.com/brainelectronics/micropython-ds1307) - MicroPython driver for DS1307 RTC.
*   [esp-ds3231-micropython (⭐7)](https://github.com/HAIZAKURA/esp-ds3231-micropython) - A DS3231 library for ESP8266/ESP32 with MicroPython.
*   [PCF8563\_PythonLibrary (⭐9)](https://github.com/lewisxhe/PCF8563_PythonLibrary) - MicroPython library for NXP PCF8563 Real-time clock/calendar.
*   [DS3231 (⭐0)](https://github.com/octaprog7/DS3231) - MicroPython module for the DS3231 clock from Maxim Integrated.
*   [DS1307 (⭐1)](https://github.com/peter-l5/DS1307) - MicroPython driver for the DS1307 real time clock.
*   [micropython-DS3231-AT24C32 (⭐29)](https://github.com/pangopi/micropython-DS3231-AT24C32) - MicroPython driver for DS3231 RTC.
*   [micropython\_rx-8035 (⭐0)](https://github.com/ekspla/micropython_rx-8035) - A MicroPython Driver for Seiko Epson's RTC, RX-8035SA/LC.

#### Serial

*   [mpy-miniterm (⭐22)](https://github.com/jeffmakes/mpy-miniterm) - Tool for seamless serial debug and file synchronisation with MicroPython devices via the serial REPL.
*   [MicroPython-MorseCode](https://gitlab.com/olivierlenoir/MicroPython-MorseCode) - International Morse Code using a microcontroller with MicroPython.
*   [I2C Slave (⭐766)](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/I2C.md) - Uses the Pyboard's I2C slave mode to implement a full duplex asynchronous link. Principal use case is for ESP8266 which has only one UART.
*   [microSDI12 (⭐11)](https://github.com/insighio/microSDI12) - A mini SDI-12 implementation for getting sensor info over RS-485.

#### Serialization

*   [micropython-msgpack (⭐33)](https://github.com/peterhinch/micropython-msgpack) - MessagePack serialisation library optimised for MicroPython.
*   [micropython-uprotobuf (⭐21)](https://github.com/jazzycamel/micropython-uprotobuf) - A lightweight implementation of Google's Protocol Buffers (protobuf) for MicroPython.
*   [minipb (⭐55)](https://github.com/dogtopus/minipb) - Mini Protobuf {de}serializer in pure Python.
*   [ucbor (⭐2)](https://github.com/dmazzella/ucbor) - Lightweight implementation of cbor for MicroPython.
*   [upy-msgpack (⭐0)](https://github.com/SpotlightKid/upy-msgpack) - A lightweight MessagePack (de)serialization library (not only) for MicroPython.

#### SMTP

*   [uMail (⭐85)](https://github.com/shawwwn/uMail) - A lightweight, scalable SMTP client for sending email in MicroPython.

#### Sockets

*   [XAsyncSockets (⭐41)](https://github.com/jczic/XAsyncSockets) - XAsyncSockets is an efficient Python/MicroPython library of managed asynchronous sockets.

#### SOCKS

*   [micropython-socks (⭐5)](https://github.com/kost/micropython-socks) - MicroPython library implementing SOCKS server.

#### TCP

*   [us2n (⭐21)](https://github.com/tiagocoutinho/us2n) - MicroPython bridge between UART and TCP for the ESP32.

#### Telnet

*   [MicroTelnetServer (⭐77)](https://github.com/cpopp/MicroTelnetServer) - Simple telnet server for MicroPython and the ESP8266 allowing telnet clients access to the REPL.

#### Text-to-Speech

*   [micropython-SYN6988 (⭐11)](https://github.com/scruss/micropython-SYN6988) - MicroPython library for the VoiceTX SYN6988 text to speech module.

#### Time

*   [ustrftime (⭐2)](https://github.com/iyassou/ustrftime) - A MicroPython implementation of time.strftime.

#### VoIP

*   [uPyVoip (⭐24)](https://github.com/RetepRelleum/uPyVoip) - VoIP for MicroPython ESP32 with Interactive Voice Response.

#### Web

*   [MicroWebSrv (⭐653)](https://github.com/jczic/MicroWebSrv) - A micro HTTP web server that supports WebSockets, HTML/Python language templating and routing handlers, for MicroPython (used on Pycom modules & ESP32).
*   [MicroWebSrv2 (⭐675)](https://github.com/jczic/MicroWebSrv2) - The last micro web server for IoTs (MicroPython) or large servers (CPython), that supports WebSocket, routes, template engine and with really optimized architecture (mem allocations, async I/Os).
*   [tinyweb (⭐257)](https://github.com/belyalov/tinyweb) - Simple and lightweight HTTP async server for MicroPython.
*   [upy-websocket-server (⭐84)](https://github.com/BetaRavener/upy-websocket-server) - MicroPython (ESP8266) WebSocket server implementation.
*   [micropython-captive-portal (⭐51)](https://github.com/amora-labs/micropython-captive-portal) - A captive portal demo for MicroPython.
*   [uPyPortal (⭐40)](https://github.com/lemariva/uPyPortal) - A captive portal for MicroPython using ESP32 (Wemos).
*   [ESP8266WebServer (⭐51)](https://github.com/codemee/ESP8266WebServer) - ESP8266 web server for MicroPython.
*   [microCoAPy (⭐63)](https://github.com/insighio/microCoAPy) - A mini client/server implementation of CoAP (Constrained Application Protocol) into MicroPython.
*   [micropyserver (⭐135)](https://github.com/troublegum/micropyserver) - MicroPyServer is a simple HTTP server for MicroPython projects.
*   [MicroRESTCli (⭐29)](https://github.com/jczic/MicroRESTCli) - A micro JSON REST web client based on MicroWebCli for MicroPython (used on Pycom modules & ESP32).
*   [micropython-noggin (⭐18)](https://github.com/larsks/micropython-noggin) - A very simple web server for MicroPython.
*   [uwebsockets (⭐199)](https://github.com/danni/uwebsockets) - MicroPython WebSocket implementation for ESP8266.
*   [microdot (⭐1.6k)](https://github.com/miguelgrinberg/microdot) - The impossibly small web framework for MicroPython.
*   [micropython-nanoweb (⭐111)](https://github.com/hugokernel/micropython-nanoweb) - Full async MicroPython web server with small memory footprint.
*   [MicroWebCli (⭐56)](https://github.com/jczic/MicroWebCli) - A micro HTTP web client for MicroPython (used on Pycom modules & ESP32).
*   [micropython-configserver (⭐15)](https://github.com/carstenblt/micropython-configserver) - Captive portal for MicroPython including a dumb DNS server and a web server to configure WiFi networks.
*   [micropython-aioweb (⭐31)](https://github.com/wybiral/micropython-aioweb) - A minimalist asyncio web framework for MicroPython.
*   [thimble (⭐18)](https://github.com/DavesCodeMusings/thimble) - A tiny web framework for MicroPython.
*   [CaptiveWebServer (⭐1)](https://github.com/joewez/CaptiveWebServer) - Simple MicroPython web server for serving a website from a captive portal.
*   [micropython-urouter (⭐51)](https://github.com/majoson-chen/micropython-urouter) - A lightweight HTTP request routing processing support library based on MicroPython. The previous name was micro-route.
*   [wlan-relays (⭐0)](https://github.com/oliver-joos/wlan-relays) - Very simple HTTP server written in MicroPython for controlling the pins of an ESP32 board.

#### WiFi

*   [HueBridge (⭐16)](https://github.com/FRC4564/HueBridge) - Philips Hue Bridge.
*   [micropython-wifimanager (⭐61)](https://github.com/mitchins/micropython-wifimanager) - A simple network configuration utility for MicroPython on the ESP8266 board.
*   [WiFiManager (⭐366)](https://github.com/tayfunulu/WiFiManager) - WiFi manager for ESP8266 - ESP12 - ESP32 - MicroPython.
*   [Micropython-ESP-WiFi-Manager (⭐35)](https://github.com/brainelectronics/Micropython-ESP-WiFi-Manager) - WiFi Manager to configure and connect to networks.
*   [mpy-wpa\_supplicant (⭐1)](https://github.com/Carglglz/mpy-wpa_supplicant) - MicroPython module to connect to the nearest known Wifi AP.
*   [micropython-wifi\_manager (⭐61)](https://github.com/ferreira-igor/micropython-wifi_manager) - WiFi Manager for ESP8266 and ESP32 using MicroPython.

#### Zigbee

*   [ZbPy (⭐47)](https://github.com/osresearch/ZbPy) - MicroPython IEEE802.15.4 / Zigbee parser.

### Display

#### E-Paper

*   [micropython-ili9341 (⭐3)](https://github.com/mcauser/deshipu-micropython-ili9341) - SSD1606 active matrix ePaper display 128x180.
*   [micropython-waveshare-epaper (⭐347)](https://github.com/mcauser/micropython-waveshare-epaper) - Drivers for various Waveshare ePaper modules.
*   [micropython-waveshare-epd (⭐53)](https://github.com/ayoy/micropython-waveshare-epd) - Waveshare ePaper Display driver for devices running Pycom-flavored MicroPython.
*   [ssd1675a (⭐8)](https://github.com/mattytrentini/ssd1675a) - Driver for SSD1675-based e-paper displays.
*   [Inkplate-micropython (⭐78)](https://github.com/SolderedElectronics/Inkplate-micropython) - MicroPython driver for Inkplate boards.
*   [micropython-inkplate6 (⭐19)](https://github.com/tve/micropython-inkplate6) - MicroPython driver for the Inkplate 6.
*   [eInk-micropython (⭐24)](https://github.com/dhallgb/eInk-micropython) - eInk library for Waveshare 4.3inch device on MicroPython.
*   [eink (⭐17)](https://github.com/chevdor/eink) - An eInk, ePaper display driver for MicroPython and ESP32.
*   [micropython\_DEPG0213BN (⭐14)](https://github.com/Inqbus/micropython_DEPG0213BN) - Pure MicroPython driver for the DEPG0213BN eInk display found on the TTGO T5 V2.3 ESP32 boards.
*   [uPyEINK (⭐29)](https://github.com/lemariva/uPyEINK) - Control a Waveshare 7.5" E-INK display using an ESP32 running MicroPython.
*   [MicroPython-2.9-inch-ePaper-Library (⭐11)](https://github.com/rdagger/MicroPython-2.9-inch-ePaper-Library) - MicroPython Display Driver for WaveShare 2.9inch e-Paper Display (B).
*   [uc8151\_micropython (⭐144)](https://github.com/antirez/uc8151_micropython) - UC8151 / IL0373 MicroPython e-paper display driver with support for greyscales and fast updates.

#### Fonts

*   [micropython-font-to-py (⭐404)](https://github.com/peterhinch/micropython-font-to-py) - A Python 3 utility to convert fonts to Python source capable of being frozen as bytecode.
*   [writer (⭐404)](https://github.com/peterhinch/micropython-font-to-py/blob/master/writer/WRITER.md) - A simple way to render above Python fonts to displays whose driver is subclassed from `framebuf`.
*   [ssd1306big (⭐25)](https://github.com/nickpmulder/ssd1306big) - A font for MicroPython on 128x64 pixel SSD1306 OLED display.
*   [framebuf2 (⭐15)](https://github.com/peter-l5/framebuf2) - MicroPython FrameBuffer extension: larger and rotated font, triangles and circles.
*   [micropython\_GT30L24T3Y\_big5\_font (⭐2)](https://github.com/alankrantas/micropython_GT30L24T3Y_big5_font) - MicroPython driver for reading BIG-5 Chinese characters from GT30L24T3Y / ER3303-1 SPI module.
*   [ttgo-hershey-fonts (⭐27)](https://github.com/russhughes/ttgo-hershey-fonts) - MicroPython Hershey font demo for the TTGO-LCD board.
*   [packed-font (⭐22)](https://github.com/mark-gladding/packed-font) -  Memory efficient MicroPython fonts for the Pico Pi and SSD1306 OLED Display.
*   [microfont (⭐56)](https://github.com/antirez/microfont) - Text drawing library for MicroPython framebuffer.

#### Graphics

*   [micropython-stage (⭐39)](https://github.com/python-ugame/micropython-stage) - A MicroPython port of the Stage game library.
*   [micropython-png (⭐13)](https://github.com/Ratfink/micropython-png) - Derivative of PyPNG for use with MicroPython.
*   [mpy-img-decoder (⭐34)](https://github.com/remixer-dec/mpy-img-decoder) - PNG and JPEG decoder / parser / renderer in pure MicroPython.
*   [micropython-oled-progressbars (⭐13)](https://github.com/follower46/micropython-oled-progressbars) - A collection of progress bars for use with ESP8266 and ESP32 on OLED displays.
*   [microplot (⭐20)](https://github.com/romilly/microplot) - Simple MicroPython plotting package.
*   [micropython-microbmp (⭐10)](https://github.com/jacklinquan/micropython-microbmp) - A small Python module for BMP image processing.
*   [MicroPython\_UPLOT (⭐2)](https://github.com/jposada202020/MicroPython_UPLOT) - MicroPython Small Graphics Framework.
*   [Tempe (⭐9)](https://github.com/unital/tempe) - Efficient MicroPython graphics library built on top of `framebuf`.

#### GUI

*   [lvgl (⭐278)](https://github.com/lvgl/lv_binding_micropython) - An object-oriented, component-based high-level GUI library with MicroPython binding.
*   [micropython-lcd160cr-gui (⭐31)](https://github.com/peterhinch/micropython-lcd160cr-gui) - Simple touch-driven event based GUI for the Pyboard and LCD160CR colour display.
*   [micropython\_ra8875 (⭐11)](https://github.com/peterhinch/micropython_ra8875) - MicroPython device driver and nano-GUI for RA8875 based displays.
*   [micropython-nano-gui (⭐542)](https://github.com/peterhinch/micropython-nano-gui) - A tiny display-only GUI with a limited set of GUI objects (widgets) for displays whose display driver is subclassed from the `framebuf` class. With drivers for TFT, ePaper and OLED displays.
*   [micro-gui (⭐282)](https://github.com/peterhinch/micropython-micro-gui) - Derived from nano-gui and supporting the same displays and hosts, this provides for user input via push buttons or a navigation joystick and an optional rotary encoder.
*   [micropython-touch (⭐38)](https://github.com/peterhinch/micropython-touch) - Derived from nano-gui and supporting the same displays and hosts, this offers touch input. Supports various touch controllers.
*   [TFT-GUI (⭐92)](https://github.com/peterhinch/micropython-tft-gui) - A fast touch GUI for large displays based on SSD1963 controller with XPT2046 touch controller.
*   [micropython-nextion (⭐13)](https://github.com/brainelectronics/micropython-nextion) - Control Nextion displays using MicroPython.
*   [mp\_lvgl\_widgets (⭐2)](https://github.com/kdschlosser/mp_lvgl_widgets) - Widgets for the MicroPython Port of LVGL.
*   [micropython-core2 (⭐54)](https://github.com/lemariva/micropython-core2) - Extends LV-MicroPython for the M5Stack CORE2 with MPU6886, ILI9342C, BM8563 and AXP192 drivers.

#### LCD Character

*   [Grove\_RGB\_LCD (⭐3)](https://github.com/dda/MicroPython/blob/master/Grove_RGB_LCD.py) - Driver for SeeedStudio's Grove RGB LCD.
*   [lcdi2c (⭐4)](https://github.com/slothyrulez/lcdi2c) - Driver for HD44780-compatible dot matrix LCDs.
*   [micropython-charlcd (⭐13)](https://github.com/rdagger/micropython-charlcd) - Driver for HD44780-compatible LCDs.
*   [micropython-i2c-lcd (⭐33)](https://github.com/Bucknalla/micropython-i2c-lcd) - Driver for I2C 2x16 LCD Screens.
*   [pyboard-LCD-character-display (⭐1)](https://github.com/scitoast/pyboard-LCD-character-display) - Pyboar driver for HDD44780-compatible 1602 LCDs.
*   [python\_lcd (⭐316)](https://github.com/dhylands/python_lcd) - Driver for HD44780-compatible dot matrix LCDs.
*   [micropython-lcd (⭐20)](https://github.com/wjdp/micropython-lcd) - Class for controlling the HD44780 from a MicroPython Pyboard.
*   [HD44780-lcd-upy](https://gitlab.com/rafalosa/HD44780-lcd-upy) - MicroPython module for controlling a generic HD44780 LCD.
*   [LCM1602-14\_LCD\_Library (⭐14)](https://github.com/Bhavithiran97/LCM1602-14_LCD_Library) - driver for AIP31068L [3.3 V I2C and SPI 1602 Serial Character LCDs](https://www.cytron.io/p-3v3-i2c-and-spi-1602-serial-character-lcd).
*   [micropython-i2c-lcd (⭐17)](https://github.com/brainelectronics/micropython-i2c-lcd) - MicroPython package to control HD44780 LCD displays 1602 and 2004 via I2C.
*   [micropython\_i2c\_lcd (⭐3)](https://github.com/Thomascountz/micropython_i2c_lcd) - MicroPython library for interacting with HD44780-based LCD displays through a PCF8574 I/O expander. It offers a high-level API for LCD control, including text display, cursor manipulation, and backlight settings, while also providing lower-level access to the GPIO operations on the PCF8574.

#### LCD Graphic

*   [micropython-lcd-AQM1248A (⭐1)](https://github.com/forester3/micropython-lcd-AQM1248A) - ESP8266 driver for AQM1248A graphic LCD.
*   [micropython-pcd8544 (⭐67)](https://github.com/mcauser/micropython-pcd8544) - Driver for Nokia 5110 PCD8544 84x48 LCD modules.
*   [micropython-st7565 (⭐13)](https://github.com/nquest/micropython-st7565) - Driver for ST7565 128x64 LCDs.
*   [micropython-st7920 (⭐13)](https://github.com/ShrimpingIt/micropython-st7920) - Library for simple graphic primitives on ST7920 128x64 monochrome LCD panel using ESP8266 and SPI.
*   [MicroPython\_PCD8544 (⭐3)](https://github.com/AnthonyKNorman/MicroPython_PCD8544) - ESP8266 driver for Nokia 5110 PCD8544.
*   [Official LCD160CR (⭐2.5k)](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/display/lcd160cr) - Driver for official MicroPython LCD160CR display with resistive touch sensor.
*   [micropython-hx1230 (⭐5)](https://github.com/mcauser/micropython-hx1230) - MicroPython library for HX1230 96x68 LCD modules.
*   [micropython-SHARP\_Memory\_Display (⭐11)](https://github.com/pramasoul/micropython-SHARP_Memory_Display) - MicroPython driver for SHARP memory display.

#### LCD TFT

*   [micropython-ili9341 (⭐3)](https://github.com/mcauser/deshipu-micropython-ili9341) - Collection of drivers for TFT displays, ILI9341, SH1106, SSD1606, ST7735.
*   [micropython-ili934x (⭐19)](https://github.com/tuupola/micropython-ili934x) - SPI driver for ILI934X series based TFT / LCD displays.
*   [MicroPython-ST7735 (⭐218)](https://github.com/boochow/MicroPython-ST7735) - ESP32 version of GuyCarvers's ST7735 TFT LCD driver.
*   [micropython-st7735 (⭐26)](https://github.com/hosaka/micropython-st7735) - Driver for ST7735 TFT LCDs.
*   [MicroPython\_ST7735 (⭐27)](https://github.com/AnthonyKNorman/MicroPython_ST7735) - Driver for ST7735 128x128 TFT.
*   [SSD1963-TFT-Library-for-PyBoard-and-RP2040 (⭐29)](https://github.com/robert-hh/SSD1963-TFT-Library-for-PyBoard-and-RP2040) - SSD1963 TFT Library for Pyboard and Raspberry Pi Pico.
*   [ST7735 (⭐154)](https://github.com/GuyCarver/MicroPython/blob/master/lib/ST7735.py) - Driver for ST7735 TFT LCDs.
*   [micropython-ili9341 (⭐215)](https://github.com/rdagger/micropython-ili9341) - MicroPython ILI9341 display & XPT2046 touch screen driver.
*   [st7789\_mpy (⭐208)](https://github.com/devbis/st7789_mpy) - Fast pure-C driver for MicroPython that can handle display modules on ST7789 chip.
*   [st7789py\_mpy (⭐87)](https://github.com/devbis/st7789py_mpy) - Slow MicroPython driver for 240x240 ST7789 display without CS pin from AliExpress, written in MicroPython.
*   [micropython-ili9341 (⭐133)](https://github.com/jeffmer/micropython-ili9341) - MicroPython Driver for ILI9341 display.
*   [micropython-ili9341 (⭐14)](https://github.com/tkurbad/micropython-ili9341) - ILI9341 TFT driver for MicroPython on ESP32.
*   [st7789\_mpy (⭐590)](https://github.com/russhughes/st7789_mpy) - Fast MicroPython driver for ST7789 display module written in C.
*   [st7789py\_mpy (⭐178)](https://github.com/russhughes/st7789py_mpy) - Driver for 320x240, 240x240 and 135x240 ST7789 displays written in MicroPython.
*   [ili9342c\_mpy (⭐54)](https://github.com/russhughes/ili9342c_mpy) - ILI9342C Fast 'C' Driver for MicroPython (M5Stack Core).
*   [gc9a01py (⭐45)](https://github.com/russhughes/gc9a01py) - GC9A01 Display driver in MicroPython.
*   [gc9a01\_mpy (⭐160)](https://github.com/russhughes/gc9a01_mpy) - Fast MicroPython driver for GC9A01 display modules written in C.
*   [st7735-esp8266-micropython (⭐33)](https://github.com/cheungbx/st7735-esp8266-micropython) - An ESP8266 MicroPython library for ST7735 160x80, 128x128, 128x160 TFT LCD displays.
*   [TTGO-ST7789-MicroPython (⭐18)](https://github.com/schumixmd/TTGO-ST7789-MicroPython) - MicroPython ST7789 display driver for TTGO T-Display ESP32 CP2104 WiFi Bluetooth Module 1.14 Inch LCD.
*   [st7735\_micropython (⭐2)](https://github.com/cheungbx/st7735_micropython) - ST7735 MicroPython drivers for 80x160, 128x128, 128x160 for ESP8266.
*   [ili934x-micropython](https://gitlab.com/mhepp63/ili934x-micropython) - Library for using ILI9341 display drivers with MicroPython.
*   [micropython-st7735-esp8266](https://gitlab.com/mo_krauti/micropython-st7735-esp8266) - MicroPython driver for ST7735 TFT displays on the ESP8266.
*   [st7789s3\_esp\_lcd (⭐17)](https://github.com/russhughes/st7789s3_esp_lcd) - Fast ESP\_LCD based MicroPython driver for the TTGO T-Display-S3 st7789 display written in C.
*   [s3lcd (⭐79)](https://github.com/russhughes/s3lcd) - ESP\_LCD based MicroPython driver for ESP32-S3 Devices with ST7789 or compatible displays.
*   [thmi\_py (⭐5)](https://github.com/russhughes/thmi_py) - MicroPython display driver for the LILYGO T-HMI written in Python.
*   [wt32sc01py (⭐13)](https://github.com/russhughes/wt32sc01py) - WT32SC01 Plus MicroPython Display Driver.
*   [st7789s3\_mpy (⭐67)](https://github.com/russhughes/st7789s3_mpy) - MicroPython display driver for the TTGO T-Display-S3 ST7789 written in C.
*   [t-display-s3 (⭐13)](https://github.com/russhughes/t-display-s3) - MicroPython display driver for the TTGO T-Display-S3 ST7789 written in Python.
*   [mp-ili9341 (⭐1)](https://github.com/tkurbad/mp-ili9341) - MicroPython Driver for ILI9341 TFT Display.
*   [lvgl\_esp32\_gc9a01 (⭐10)](https://github.com/minyiky/lvgl_esp32_gc9a01) - Driver for displays using the GC901 driver for use with LVGL MicroPython.
*   [ST77xx-pure-MP (⭐30)](https://github.com/antirez/ST77xx-pure-MP) - Pure MicroPython driver for ST77xx displays. Low memory requirements.
*   [upy-st7789 (⭐2)](https://github.com/OneMadGypsy/upy-st7789) - A simple ST7789 driver written in MicroPython.

#### LED Matrix

*   [micropython-ht1632c (⭐7)](https://github.com/vrialland/micropython-ht1632c) - Driver for HT1632C 32x16 bicolor LED matrix.
*   [micropython-matrix8x8 (⭐15)](https://github.com/JanBednarik/micropython-matrix8x8) - Driver for Adafruit 8x8 LED Matrix display with HT16K33 backpack.
*   [micropython-max7219 (⭐188)](https://github.com/mcauser/micropython-max7219) - Driver for MAX7219 8x8 LED matrix modules.
*   [micropython-wemos-led-matrix-shield](https://github.com/mactijn/micropython-wemos-led-matrix-shield) - Driver for Wemos D1 Mini Matrix LED shield, using TM1640 chip.
*   [micropython-wemos-led-matrix (⭐1)](https://github.com/mattytrentini/micropython-wemos-led-matrix) - Driver for Wemos D1 Mini Matrix LED shield, using TM1640 chip.
*   [micropython-max7219 (⭐39)](https://github.com/vrialland/micropython-max7219) - MicroPython driver for MAX7219 8x8 LED matrix.
*   [MatrixDisplay (⭐0)](https://github.com/octaprog7/MatrixDisplay) - MicroPython module for work with MAX7219 LED matrix 8x8 display.
*   [LED\_panel\_upy (⭐1)](https://github.com/CatMeowByte/LED_panel_upy) - MicroPython driver module for Panel P10 32x16 Matrix display and its variants.

#### LED Segment

*   [LKM1638 (⭐1)](https://github.com/arikb/LKM1638) - Driver for JY-LKM1638 displays based on TM1638 controller.
*   [max7219\_8digit (⭐24)](https://github.com/pdwerryhouse/max7219_8digit) - Driver for MAX7219 8-digit 7-segment LED modules.
*   [micropython-max7219 (⭐4)](https://github.com/JulienBacquart/micropython-max7219) - Driver for MAX7219 8-digit 7-segment LED modules.
*   [micropython-my9221 (⭐7)](https://github.com/mcauser/micropython-my9221) - Driver for MY9221 10-segment LED bar graph modules.
*   [micropython-tm1637 (⭐197)](https://github.com/mcauser/micropython-tm1637) - Driver for TM1637 quad 7-segment LED modules.
*   [micropython-tm1638 (⭐28)](https://github.com/mcauser/micropython-tm1638) - Driver for TM1638 dual quad 7-segment LED modules with switches.
*   [micropython-tm1640 (⭐15)](https://github.com/mcauser/micropython-tm1640) - Driver for TM1740 8x8 LED matrix modules.
*   [micropython-tm1640](https://gitlab.com/robhamerling/micropython-tm1640) - MicroPython Library for 16 digits 7-segment displays controlled by a TM1640.
*   [TM74HC595 (⭐6)](https://github.com/Sakartu/TM74HC595) - Driver for shift register-controlled 5 pin display modules.
*   [micropython-tm1638spi](https://gitlab.com/robhamerling/micropython-tm1638spi) - MicroPython Library for a popular board with 8 7-segment digits, 8 separate LEDs and 8 push buttons controlled by a TM1638.
*   [micropython-hpdl1414 (⭐1)](https://github.com/rdagger/micropython-hpdl1414) - MicroPython HPDL-1414 Display Driver.

#### LEDs

*   [micropython-morsecode (⭐7)](https://github.com/mampersat/micropython-morsecode) - Blink an LED with Morse Coded message.
*   [micropython-p9813 (⭐7)](https://github.com/mcauser/micropython-p9813) - Driver for P9813 RGB LED used in SeeedStudio's Grove chainable RGB LED.
*   [micropython-ws2812-7seg (⭐1)](https://github.com/HubertD/micropython-ws2812-7seg) - 7-segment display using WS2812 RGB LEDs.
*   [micropython-ws2812 (⭐191)](https://github.com/JanBednarik/micropython-ws2812) - Driver for WS2812 RGB LEDs.
*   [Official APA102](https://docs.micropython.org/en/latest/esp8266/quickref.html#apa102-driver) - ESP8266 APA102/DotStar RGB LED driver.
*   [Official WS2811](https://docs.micropython.org/en/latest/esp8266/quickref.html#neopixel-driver) - ESP8266 WS2811/NeoPixel RGB LED driver.
*   [tlc5940-micropython (⭐5)](https://github.com/oysols/tlc5940-micropython) - Driver for TLC5940 16 channel LED driver.
*   [ws2812-SPI (⭐28)](https://github.com/nickovs/ws2812-SPI) - An efficient MicroPython WS2812 (NeoPixel) driver.
*   [micropython-ws2801 (⭐2)](https://github.com/HeMan/micropython-ws2801) - A MicroPython library to interface with strands of WS2801 RGB LEDs.
*   [tlc5947-rgb-micropython](https://gitlab.com/peterzuger/tlc5947-rgb-micropython) - Driver for the TLC5947 24 channel 12-bit PWM LED driver.
*   [micropython-ht16k33 (⭐44)](https://github.com/hybotix/micropython-ht16k33) - MicroPython driver for the HT16K33, a LED matrix, 7-Segment Numeric, and 14-Segment Alphanumeric display driver IC.
*   [micropython-rgbled (⭐15)](https://github.com/Warringer/micropython-rgbled) - This wrapper module aims to reduce the work needed to work with NeoPixel (WS2812) and DotStar (APA102) RGB LED strips and matrices.
*   [micropython\_fastled (⭐22)](https://github.com/kdschlosser/micropython_fastled) - Port of FastLED to MicroPython.
*   [micropython-rgb-led-driver](https://gitlab.com/Athanaze/micropython-rgb-led-driver) - Tiny driver to control an RGB LED with PWM.
*   [micropython-dotstar (⭐22)](https://github.com/mattytrentini/micropython-dotstar) - A MicroPython port of the Adafruit CircuitPython APA102/DotStar library.
*   [micropython-aw210xx (⭐0)](https://github.com/eosti/micropython-aw210xx) - Driver for Awinic's AW210xx line of 8-bit LED drivers.

#### OLED

*   [Grove\_OLED (⭐3)](https://github.com/dda/MicroPython/blob/master/Grove_OLED.py) - Driver for SSD1327 used by SeeedStudio's Grove OLED Display 1.12" v1.0.
*   [micropython-oled (⭐4)](https://github.com/mcauser/deshipu-micropython-oled) - Collection of drivers for monochrome OLED displays, PCD8544, SH1106, SSD1306, UC1701X.
*   [micropython-ssd1327 (⭐26)](https://github.com/mcauser/micropython-ssd1327) - Driver for SSD1327 128x128 4-bit greyscale OLED displays.
*   [micropython-ssd1351 (⭐58)](https://github.com/rdagger/micropython-ssd1351) - Driver for SSD1351 OLED displays.
*   [MicroPython\_SSD1306 (⭐10)](https://github.com/AnthonyKNorman/MicroPython_SSD1306) - ESP8266 driver for SSD1306 OLED 128x64 displays.
*   [Official SSD1306 (⭐2.5k)](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/display/ssd1306) - Driver for SSD1306 128x64 OLED displays.
*   [SH1106 (⭐176)](https://github.com/robert-hh/SH1106) - Driver for the SH1106 OLED display.
*   [micropython-ssd1309 (⭐36)](https://github.com/rdagger/micropython-ssd1309) - MicroPython SSD1309 Monochrome OLED Display Driver.
*   [sh1107-micropython (⭐9)](https://github.com/nemart69/sh1107-micropython) - MicroPython driver for SH1107-based OLED display (64x128).
*   [SH1107 (⭐26)](https://github.com/peter-l5/SH1107) - Driver for SH1107 OLED displays (128x128 and 128x64 pixels).
*   [micropython-ssd1322 (⭐12)](https://github.com/rdagger/micropython-ssd1322) - MicroPython display driver for SSD1322 grayscale OLED.
*   [micropython-ssd1306 (⭐0)](https://github.com/rdagger/micropython-ssd1306) - MicroPython SPI & I2C Display Driver for SSD1306 monochrome OLED.

#### Printer

*   [micropython-thermal-printer (⭐24)](https://github.com/ayoy/micropython-thermal-printer) - The MicroPython port of Python Thermal Printer by Adafruit.

### IO

#### ADC

*   [ads1x15 (⭐98)](https://github.com/robert-hh/ads1x15) - Driver for the ADS1015/ADS1115 ADC, I2C interface.
*   [micropython-ads1015 (⭐0)](https://github.com/mcauser/deshipu-micropython-ads1015) - ADS1015 12-Bit and ADS1115 16-bit ADC, 4 channels with programmable gain, I2C interface.
*   [Micropython\_ADS1115 (⭐4)](https://github.com/AnthonyKNorman/Micropython_ADS1115) - ADS1115 16-bit ADC, 4 channels with programmable gain, I2C interface.
*   [ADS7818 (⭐0)](https://github.com/robert-hh/ADS7818) - Python class interfacing the ADS7818 AD-converter.
*   [micropython-ads1219 (⭐4)](https://github.com/miketeachman/micropython-ads1219) - MicroPython module for the Texas Instruments ADS1219 ADC.
*   [MicroPython-ADC\_Cal (⭐18)](https://github.com/matthias-bs/MicroPython-ADC_Cal) - ESP32 ADC driver using reference voltage calibration value from efuse.
*   [micropython-pcf8591](https://gitlab.com/cediddi/micropython-pcf8591) - MicroPython driver for PCF8591 ADC/DAC, I2C interface.
*   [MCP342x\_LoPy (⭐3)](https://github.com/jajberni/MCP342x_LoPy) - MicroPython driver for the MCP342x ADC.
*   [micropython-ads1220 (⭐6)](https://github.com/rdagger/micropython-ads1220) - MicroPython library for ADS1220 24-bit analog-to-digital converter.
*   [PCF8591\_micropython\_library (⭐2)](https://github.com/xreef/PCF8591_micropython_library) - MicroPython library for PCF8591 8-bit ADC/DAC.
*   [CS1237 (⭐0)](https://github.com/robert-hh/CS1237) - MicroPython driver for the CS1237 ADC.
*   [ads1115 (⭐0)](https://github.com/octaprog7/ads1115) - MicroPython module for managing ADS1115, multichannel, differential I2C ADC from TI.
*   [mcp3421 (⭐0)](https://github.com/octaprog7/mcp3421) - MicroPython module for controlling MCP342X, 18-bit analog-to-digital converter with I2C interface.
*   [micropython-MCP3001 (⭐0)](https://github.com/scruss/micropython-MCP3001) - MicroPython driver for the MCP3001 1-channel 10-bit ADC with SPI interface.

#### DAC

*   [micropython-mcp4725 (⭐12)](https://github.com/wayoda/micropython-mcp4725) - Driver for the MCP4725 I2C DAC.
*   [mcp4728 (⭐4)](https://github.com/openfablab/mcp4728) - Helper library for the Microchip MCP4728 I2C 12-bit Quad DAC.
*   [mpyDAC (⭐0)](https://github.com/octaprog7/mpyDAC) - MicroPython module for controlling MCP4725, 12-bit digital analog converter (CAP) with EEPROM memory.

#### GPIO

*   [micropython-inputs (⭐34)](https://github.com/alanmitchell/micropython-inputs) - Classes to count pulses, debounce digital inputs, and calculate moving averages of analog inputs for a MicroPython board.
*   [ubutton](https://gitlab.com/WiLED-Project/ubutton) - A MicroPython library for controlling reading and debouncing pushbutton inputs, including "short" and "long" press callbacks.
*   [micropython-debounce-switch (⭐8)](https://github.com/selfhostedhome/micropython-debounce-switch) - MicroPython Class for Debouncing Switches.

#### IO-Expander

*   [micropython-mcp230xx (⭐30)](https://github.com/ShrimpingIt/micropython-mcp230xx) - Driver for MCP23017 and MCP23008 GPIO expanders.
*   [micropython-mcp230xx (⭐0)](https://github.com/dsiggi/micropython-mcp230xx) - Driver for MCP23017 and MCP23008 GPIO expanders, extended with interrupt handling.
*   [micropython-mcp23017 (⭐76)](https://github.com/mcauser/micropython-mcp23017) - MicroPython driver for MCP23017 16-bit I/O Expander.
*   [micropython-pcf8574 (⭐41)](https://github.com/mcauser/micropython-pcf8574) - MicroPython driver for PCF8574 8-Bit I2C I/O Expander with Interrupt.
*   [micropython-pcf8575 (⭐21)](https://github.com/mcauser/micropython-pcf8575) - MicroPython driver for PCF8575 16-Bit I2C I/O Expander with Interrupt.
*   [ESP8266\_MCP23S17 (⭐1)](https://github.com/AnthonyKNorman/ESP8266_MCP23S17) - MicroPython library for using the MCP23S17 16-bit I/O expander with the ESP8266.
*   [pcf8574 (⭐0)](https://github.com/octaprog7/pcf8574) - MicroPython module for working with the PCF8574(A) I2C 8-bit I/O expander from NXP.
*   [mcp23017 (⭐0)](https://github.com/octaprog7/mcp23017) - MicroPython module for MCP23017, 16-Bit I/O Expander with Serial Interface.
*   [micropython-sx1509 (⭐1)](https://github.com/rdagger/micropython-sx1509) - MicroPython SX1509 I/O Expander Library.

#### Joystick

*   [micropython-nunchuck (⭐12)](https://github.com/kfricke/micropython-nunchuck) - Driver for Nunchuk game controller, I2C interface.
*   [esp32-microgamepad-ble (⭐16)](https://github.com/insighio/esp32-microgamepad-ble) - Dual analog joystick on ESP32 over BLE (Nordic UART Service - NUS) using MicroPython.
*   [micropython-joystick-2-unit (⭐0)](https://github.com/HowManyOliversAreThere/micropython-joystick-2-unit) - Driver for the [M5Stack Joystick 2 Unit](https://docs.m5stack.com/en/unit/Unit-JoyStick2).

#### Keyboard

*   [micropython-keyboard (⭐31)](https://github.com/mcameron/micropython-keyboard) - 47 key keyboard running on a MicroPython Pyboard.
*   [pico-rgbkeypad (⭐66)](https://github.com/martinohanlon/pico-rgbkeypad) - A Python class for controlling the Pimoroni RGB Keypad for Raspberry Pi Pico.
*   [micropython-aiobutton (⭐4)](https://github.com/jacklinquan/micropython-aiobutton) - A MicroPython module for asyncio button.
*   [MicroPython-SimpleKeypad (⭐2)](https://github.com/PerfecXX/MicroPython-SimpleKeypad) - MicroPython library for interfacing with a keypad matrix.

#### Multiplexer

*   [micropython-tca9548a (⭐16)](https://github.com/mcauser/micropython-tca9548a) - MicroPython examples using TCA9548A I2C multiplexer.
*   [tca9548a (⭐6)](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/tca9548a.py) - MicroPython driver for the TCA9548A I2C multiplexer.

#### Potentiometers

*   [micropython-ad840x (⭐1)](https://github.com/dsiggi/micropython-ad840x) - MicroPython SPI-based manipulation of the AD series digital potentiometers AD8400, AD8402 and AD8403.
*   [mcp4131 (⭐3)](https://github.com/scruss/mcp4131) - MicroPython module to control MicroChip's MCP4131 SPI digital potentiometer.
*   [MicroPython\_DS1841 (⭐0)](https://github.com/jposada202020/MicroPython_DS1841) - MicroPython Driver for the DS1841 Potentiometer.
*   [MicroPython\_DS3502 (⭐0)](https://github.com/jposada202020/MicroPython_DS3502) - MicroPython Driver for the DS3502 Potentiometer.

#### Power Management

*   [AXP202\_PythonLibrary (⭐12)](https://github.com/lewisxhe/AXP202_PythonLibrary) - MicroPython AXP202 Library.
*   [micropython\_hourly\_sleeper\_library (⭐13)](https://github.com/costastf/micropython_hourly_sleeper_library) - A MicroPython library that enables an ESP8266 to sleep for hourly increments for a setup amount of hours.

#### PWM

*   [upwmcontroller](https://gitlab.com/WiLED-Project/upwmcontroller) - A MicroPython library for controlling PWM outputs in an asyncio loop, with features including fading and blinking.

#### Relay

*   [micropython-xl9535-kxv5-relay (⭐10)](https://github.com/mcauser/micropython-xl9535-kxv5-relay) - A MicroPython library for jxl XL9535-KxV5 I2C relay boards.

#### Rotary Encoder

*   [micropython-rotary (⭐297)](https://github.com/miketeachman/micropython-rotary) - MicroPython module to read a rotary encoder.
*   [uencoder](https://gitlab.com/WiLED-Project/uencoder) - A MicroPython library for reading from a rotary encoder.
*   [encodermenu (⭐113)](https://github.com/sgall17a/encodermenu) - Simple GUI menu for MicroPython using a rotary encoder and basic display.
*   [encoderLib (⭐8)](https://github.com/BramRausch/encoderLib) - MicroPython library to handle a rotary encoder.
*   [rotary-encoder (⭐31)](https://github.com/gurgleapps/rotary-encoder) - MicroPython code to drive a KY-040 rotary encoder.
*   [micropython-encoder-knob (⭐2)](https://github.com/infinite-tree/micropython-encoder-knob) - A very simple lightweight encoder knob library with button support.
*   [encoders (⭐484)](https://github.com/peterhinch/micropython-samples/blob/master/encoders/ENCODERS.md) - Short document explaining issues around encoder technology.
*   [asynchronous encoder driver (⭐766)](https://github.com/peterhinch/micropython-async/blob/master/v3/primitives/encoder.py) - Interface an encoder to uasyncio code.
*   [micropython-8encoder (⭐2)](https://github.com/HowManyOliversAreThere/micropython-8encoder) - Driver for the I2C [M5Stack 8-Encoder Unit](https://shop.m5stack.com/products/8-encoder-unit-stm32f030).
*   [micropython-quiic-twist (⭐3)](https://github.com/rdagger/micropython-quiic-twist) - MicroPython Driver for Quiic Twist RGB Rotary Encoder.
*   [AS5600 (⭐34)](https://github.com/sgall17a/AS5600) - AS5600 MicroPython library for reading this magnetic sensor.
*   [AS5600 (⭐1)](https://github.com/octaprog7/AS5600) - MicroPython module for controlling single-turn magnetic encoder AS5600.

#### Shift Registers

*   [micropython-74hc595 (⭐30)](https://github.com/mcauser/micropython-74hc595) - MicroPython driver for 74HC595 8-bit shift registers.
*   [MicroPython-SN74HCS264](https://gitlab.com/olivierlenoir/MicroPython-SN74HCS264) - MicroPython Driver for SN74HCS264 8-Bit Parallel-Out Serial Shift Registers With Schmitt-Trigger Inputs and Inverted Outputs.

#### Waveform Generator

*   [Micropython-AD9833 (⭐19)](https://github.com/KipCrossing/Micropython-AD9833) - Pyboard driver for AD9833, SPI interface.
*   [Clock\_Generators (⭐7)](https://github.com/Wei1234c/Clock_Generators) - Clock generators (Si5351 for now) toolbox.
*   [Signal\_Generators (⭐21)](https://github.com/Wei1234c/Signal_Generators) - Signal generators (AD9833, AD9834, AD9850, ADF4351) toolbox.
*   [pico-wave-vibration-generator (⭐3)](https://github.com/gurgleapps/pico-wave-vibration-generator) - A MicroPython-based frequency generator for Raspberry Pi Pico designed to create vibrations on solenoids or speakers, enabling wave experimentation and exploration at home.
*   [micropython-m5stack-dds (⭐1)](https://github.com/mattytrentini/micropython-m5stack-dds) - MicroPython driver for the M5Stack DDS frequency generator.
*   [AD9833-MicroPython-Module (⭐7)](https://github.com/owainm713/AD9833-MicroPython-Module) - MicroPython module to use the AD9833 programmable waveform generator.

### Mathematics

*   [uMath (⭐19)](https://github.com/albaEDA/uMath) - Computer Algebra for microcontrollers.
*   [micropython-ulab (⭐447)](https://github.com/v923z/micropython-ulab) - A NumPy-like fast vector module for MicroPython.
*   [micropython-fourier (⭐81)](https://github.com/peterhinch/micropython-fourier) - Fast Fourier transform in MicroPython's inline ARM assembler.
*   [Filters (⭐67)](https://github.com/peterhinch/micropython-filters) - FIR filters using ARM Thumb assembler. Using an online utility you can go from a graph of required frequency response to a filter implementation.
*   [ulinalg (⭐32)](https://github.com/jalawson/ulinalg) - Small size matrix handling module with a few linear algebra operations specifically for MicroPython (Python 3).
*   [micropython-mtx](https://gitlab.com/nickoala/micropython-mtx) - Fast Matrix Multiplication and Linear Solver on MicroPython.
*   [micropython-vec](https://gitlab.com/nickoala/micropython-vec) - Vector Operations on MicroPython.
*   [MicroPython\_Statistics (⭐15)](https://github.com/rcolistete/MicroPython_Statistics) - Statistics module for MicroPython.
*   [MicroPython-Matrix](https://gitlab.com/olivierlenoir/MicroPython-Matrix) - MicroPython basic matrix operations.
*   [uumpy (⭐2)](https://github.com/nickovs/uumpy) - A subset of NumPy for MicroPython.
*   [upyuncertainties (⭐0)](https://github.com/rcolistete/upyuncertainties) - Uncertainty calculations for MicroPython.
*   [umatrix (⭐15)](https://github.com/iyassou/umatrix) - A matrix library for the MicroPython language.
*   [micropython-fractions (⭐1)](https://github.com/mattytrentini/micropython-fractions) - A MicroPython port of the CPython standard Fractions library.
*   [Sun and Moon (⭐484)](https://github.com/peterhinch/micropython-samples/blob/master/astronomy/README.md) - Determine Sun and Moon rise and set times, Moon phases.
*   [micropython-npyfile (⭐3)](https://github.com/jonnor/micropython-npyfile/) - Numpy .npy file support for MicroPython, supports read/write/streaming.
*   [Micropython Perlin (⭐1)](https://github.com/sjaak31367/micropython_perlin) - A Perlin noise generator module.

### Motion

#### DC Motor

*   [L298N (⭐154)](https://github.com/GuyCarver/MicroPython/blob/master/lib/L298N.py) - Driver for the L298N dual H-bridge motor controller.
*   [MicroPython-L298](https://gitlab.com/olivierlenoir/MicroPython-L298) - Drive L298 dual H-bridge with MicroPython.
*   [pyl298 (⭐2)](https://github.com/marcio-pessoa/pyl298) - Driver for the L298 dual full-bridge motor controller.

#### Servo

*   [micropython-pca9685 (⭐3)](https://github.com/mcauser/deshipu-micropython-pca9685) - 16-channel 12-bit PWM/servo driver.
*   [micropython-servo (⭐15)](https://github.com/redoxcode/micropython-servo) - Library to control RC servos using direct PWM output in a tidy way.
*   [MicroPython\_PCA9685 (⭐6)](https://github.com/jposada202020/MicroPython_PCA9685) - MicroPython Driver for the PCA9685 PWM control IC, commonly used to control servos, LEDs and motors.
*   [MicroPython\_MOTOR (⭐1)](https://github.com/jposada202020/MicroPython_MOTOR) - MicroPython Helper for controlling PWM based motors.
*   [pca9685 (⭐0)](https://github.com/octaprog7/pca9685) - MicroPython module for managing a 16-channel SHIM controller, PCA9685

#### Stepper

*   [micropython-stepper (⭐12)](https://github.com/redoxcode/micropython-stepper) - Library to control common stepper drivers in a tidy way.
*   [micropython-upybbot (⭐91)](https://github.com/jeffmer/micropython-upybbot) - A4988 driver for bipolar stepper motors.
*   [uln2003 (⭐47)](https://github.com/IDWizard/uln2003) - Driver for 5V 28BYJ-48 stepper motors.
*   [micropython-multiaxis](https://gitlab.com/olivierlenoir/micropython-multiaxis) - Multiaxis with MicroPython ESP32 and DRV8825.
*   [ticlib (⭐19)](https://github.com/jphalip/ticlib) - Driver for Pololu Tic stepper motor controllers.
*   [AccelStepper-MicroPython (⭐39)](https://github.com/pedromneto97/AccelStepper-MicroPython) - AccelStepper Library for MicroPython - ESP32.
*   [pystepper (⭐3)](https://github.com/marcio-pessoa/pystepper) - MicroPython Stepper Motor Sequence Control.
*   [uPySteppers (⭐12)](https://github.com/lemariva/uPySteppers) - DIY rotating platform using an ESP32 connected to WiFi.
*   [microPython\_AMIS-30543 (⭐0)](https://github.com/capella-ben/microPython_AMIS-30543) - MicroPython library for Stepper Driver control using AMIS-30543 driver.
*   [micropython-drv8825](https://gitlab.com/robhamerling/micropython-drv8825) - Driver and example in MicroPython to control a stepper motor via a DRV8825 controller board.
*   [microPython\_TMC5160 (⭐3)](https://github.com/capella-ben/microPython_TMC5160) - A MicroPython library for the Trinamic TMC5160 Motion Controller.
*   [micropython-stepper-motor (⭐9)](https://github.com/larsks/micropython-stepper-motor) - Drive a 28BYJ-48 motor attached to a ULN2003 driver.

### Sensors

#### Accelerometer Digital

*   [ADXL345-with-Pyboard (⭐0)](https://github.com/AbhinayBandaru/ADXL345-with-Pyboard) - Driver for ADXL345 16g 3-axis accelerometer.
*   [adxl345\_micropython (⭐7)](https://github.com/fanday/adxl345_micropython) - Driver for ADXL345 16g 3-axis accelerometer.
*   [MicroPython-LIS3DH (⭐64)](https://github.com/tinypico/tinypico-micropython/tree/master/lis3dh%20library) - I2C driver for LIS3DH 3-axis accelerometer.
*   [micropython-lis2hh12 (⭐9)](https://github.com/tuupola/micropython-lis2hh12) - I2C driver for LIS2HH12 3-axis accelerometer.
*   [MMA7660 (⭐1)](https://github.com/Bucknalla/MicroPython-3-Axis-Accelerometer/blob/master/MMA7660.py) - Driver for MMA7660 1.5g 3-axis accelerometer.
*   [ADXL345\_spi\_micropython (⭐18)](https://github.com/AlekseyFedorovich/ADXL345_spi_micropython) - Library for interacting through the SPI protocol with an 'Analog Devices ADXL345' accelerometer from an MCU flashed with MicroPython.
*   [MicroPython\_ADXL343 (⭐0)](https://github.com/jposada202020/MicroPython_ADXL343) - MicroPython Driver for the Analog Devices ADXL343 Accelerometer.
*   [MicroPython\_BMA220 (⭐0)](https://github.com/jposada202020/MicroPython_BMA220) - MicroPython Driver for the Bosch BMA220 Accelerometer.
*   [MicroPython\_BMA400 (⭐0)](https://github.com/jposada202020/MicroPython_BMA400) - MicroPython Driver for the Bosch BMA400 Accelerometer.
*   [bma423-pure-mp (⭐9)](https://github.com/antirez/bma423-pure-mp) - MicroPython Driver for the Bosch 423 accelerometer. Includes FIFO support. ⏩
*   [MicroPython\_LIS3DH (⭐1)](https://github.com/jposada202020/MicroPython_LIS3DH) - MicroPython Driver for the LIS3DH 3-axis accelerometer.
*   [MicroPython\_KX132 (⭐1)](https://github.com/jposada202020/MicroPython_KX132) - MicroPython Driver for the Kionix KX132 Accelerometer.
*   [MicroPython\_H3LIS200DL (⭐0)](https://github.com/jposada202020/MicroPython_H3LIS200DL) - MicroPython Driver for the ST H3LIS200DL Accelerometer.
*   [MicroPython\_QMC5883L (⭐1)](https://github.com/jposada202020/MicroPython_QMC5883L) - MicroPython Driver for the QMC5883L Accelerometer.
*   [Micropython\_MC3479 (⭐0)](https://github.com/jposada202020/Micropython_MC3479) - MicroPython Driver for the MC3479 Accelerometer.
*   [MicroPython\_MMA8451 (⭐1)](https://github.com/jposada202020/MicroPython_MMA8451) - MicroPython module for the MMA8451 3-axis accelerometer.
*   [MicroPython\_MMA8452Q (⭐0)](https://github.com/jposada202020/MicroPython_MMA8452Q) - MicroPython Driver for the NXP MMA8452Q Accelerometer.
*   [msa301-micropython-driver (⭐3)](https://github.com/wojciech-szmyt/msa301-micropython-driver) - Homebrew MicroPython driver for MSA301 3-axis accelerometer. Tested on Raspberry Pico.

#### Air Quality

*   [CCS811 (⭐0)](https://github.com/Ledbelly2142/CCS811) - CCS811 Air Quality Sensor.
*   [upython-aq-monitor (⭐28)](https://github.com/ayoy/upython-aq-monitor) - Air Quality monitor using PMS5003 sensor and WiPy.
*   [micropython-pms7003 (⭐33)](https://github.com/pkucmus/micropython-pms7003) - MicroPython driver for the PMS7003 Air Quality Sensor.
*   [pms5003\_micropython (⭐23)](https://github.com/kevinkk525/pms5003_micropython) - Driver for PMS5003 air quality sensor for MicroPython.
*   [micropython-pms5003-minimal (⭐1)](https://github.com/miketeachman/micropython-pms5003-minimal) - Driver for P air quality sensor for MicroPython.
*   [polly (⭐12)](https://github.com/g-sam/polly) - SDS011 pollution sensor + Wemos D1 mini pro + MicroPython.
*   [micropython-SNGCJA5 (⭐0)](https://github.com/aleppax/micropython-SNGCJA5) - MicroPython driver for Panasonic SN-GCJA5 particulate matter (PM) sensor.

#### Barometer - Air and Water Pressure

*   [MicroPython-BMPxxx (⭐2)](https://github.com/bradcar/MicroPython_BMPxxx) - Driver for BMP585, BMP581, BMP390, BMP280 Bosch temperature/pressure sensors.
*   [mp-bmp3xx-full (⭐4)](https://github.com/jornamon/mp-bmp3xx-full) - MicroPython driver for the Bosch BMP3xx range of barometric pressure sensors. Includes FIFO support. ⏩
*   [micropython-bme280 (⭐3)](https://github.com/kevbu/micropython-bme280) - Driver for the Bosch BME280 temperature/pressure/humidity sensor.
*   [micropython-bmp180 (⭐86)](https://github.com/micropython-IMU/micropython-bmp180) - Driver for Bosch BMP180 temperature, pressure and altitude sensor.
*   [mpy\_bme280\_esp8266 (⭐73)](https://github.com/catdog2/mpy_bme280_esp8266) - Bosch BME280 temperature/pressure/humidity sensor.
*   [BME280 (⭐106)](https://github.com/robert-hh/BME280) - MicroPython driver for the BME280 sensor, target platform Pycom devices.
*   [ms5803-micropython (⭐2)](https://github.com/minyiky/ms5803-micropython) - A MicroPython implementation of the driver for an MS5803 air/water pressure & temperature sensor.
*   [MPL3115A2\_MicroPython (⭐4)](https://github.com/PinsonJonas/MPL3115A2_MicroPython) - MicroPython library for the MPL3115A2 altimeter.
*   [D6F-PH (⭐0)](https://github.com/ekspla/D6F-PH) - MicroPython module for differential pressure sensor, D6F-PH (OMRON).
*   [micropython-bmp280 (⭐95)](https://github.com/dafvid/micropython-bmp280) - Module for the BMP280 sensor.
*   [micropython\_bme280\_i2c (⭐10)](https://github.com/triplepoint/micropython_bme280_i2c) - A MicroPython module for communicating with the Bosch BME280 temperature, humidity, and pressure sensor.
*   [MicroPython-BME280 (⭐7)](https://github.com/neliogodoi/MicroPython-BME280) - Driver to digital sensor of Temperature, Pressure and Humidity.
*   [micropython-bmp180](https://gitlab.com/flowolf/micropython-bmp180) - A module for MicroPython which provides a class for the BMP180 pressure sensor.
*   [bmp581 (⭐0)](https://github.com/octaprog7/bmp581) - MicroPython module for BMP581, pressure and ambient temperature sensor from Bosch Sensortec.
*   [BMP390 (⭐3)](https://github.com/octaprog7/BMP390) - MicroPython module for BMP390 pressure & temperature sensor.
*   [BMP180 (⭐3)](https://github.com/octaprog7/BMP180) - MicroPython module for BMP180 pressure & temperature sensor.
*   [MicroPython\_DPS310 (⭐0)](https://github.com/jposada202020/MicroPython_DPS310) - MicroPython Driver for the DPS310 Sensor. (Archived)
*   [MicroPython\_ICP10111 (⭐0)](https://github.com/jposada202020/MicroPython_ICP10111) - MicroPython Driver for the TDK ICP-10111 Barometric Pressure and Temperature sensor. (Archived)
*   [MicroPython\_BMP581 (⭐0)](https://github.com/jposada202020/MicroPython_BMP581) - MicroPython driver for the Bosch BMP581 pressure & temperature sensor. (Archived)
*   [MicroPython\_MMR902 (⭐0)](https://github.com/jposada202020/MicroPython_MMR902) - MicroPython Driver for the Mitsumi MMR902 Micro Pressure Sensor. (Archived)
*   [MicroPython\_MPL3115A2 (⭐0)](https://github.com/jposada202020/MicroPython_MPL3115A2) - MicroPython driver for the NXP MPL3115A2 Pressure and Temperature sensor. (Archived)
*   [MicroPython\_MS5611 (⭐0)](https://github.com/jposada202020/MicroPython_MS5611) - MicroPython Driver for the TE MS5611 Pressure and Temperature Sensor. (Archived)

#### Battery

*   [Micropython-LC709203F (⭐2)](https://github.com/scopelemanuele/Micropython-LC709203F) - A simple MicroPython library for LC709293F Fuel Gauge.

#### Biometric

*   [micropython-fingerprint (⭐16)](https://github.com/chrisb2/micropython-fingerprint) - MicroPython library for reading Grow and ZhianTec fingerprint sensors.
*   [MAX30102-MicroPython-driver (⭐61)](https://github.com/n-elia/MAX30102-MicroPython-driver) - A MAX30102 driver ported to MicroPython. It should also work for MAX30105.
*   [max30102 (⭐6)](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/max30102.py) - MicroPython driver for the MAX30102, with heartbeat detection and BPM measurement.

#### Camera

*   [micropython-camera-API (⭐47)](https://github.com/cnadler86/micropython-camera-API) - Project with the aim of supporting cameras across various ports in MicroPython, starting with the ESP32 port and Omnivision cameras (OV2640 & OV5640).
*   [micropython-ov2640 (⭐112)](https://github.com/namato/micropython-ov2640) - MicroPython class for OV2640 camera.
*   [Nikon-Trigger-for-MicroPython (⭐3)](https://github.com/Thekegman/Nikon-Trigger-for-MicroPython) - Remote trigger for a Nikon camera using an IR LED. For Pyboard v1.1.
*   [micropython-camera-driver (⭐487)](https://github.com/lemariva/micropython-camera-driver) - OV2640 camera driver for MicroPython on ESP32.
*   [esp32-cam-micropython (⭐92)](https://github.com/shariltumin/esp32-cam-micropython) - MicroPython ESP32-CAM.
*   [uPyCam (⭐157)](https://github.com/lemariva/uPyCam) - Take a photo with an ESP32-CAM running MicroPython.
*   [OV2640\_uPy (⭐10)](https://github.com/FunPythonEC/OV2640_uPy) - OV2640 camera library for MicroPython.
*   [MQTT-Cam (⭐9)](https://github.com/jono-allen/MQTT-Cam) - ESP32-CAM MicroPython MQTT AWS S3 Uploader.
*   [huskylib (⭐6)](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/huskylib.py) - MicroPython driver for the DFRobot Husky Lens. An easy-to-use AI Camera / Vision Sensor, featuring face recognition, object tracking, object recognition, line tracking, color recognition, and QR code recognition.

#### Colour

*   [micropython-tcs34725](https://gitlab.com/robhamerling/micropython-tcs34725) - Driver class for TCS34725 and TCS34727 color sensors.
*   [micropython-as7341](https://gitlab.com/robhamerling/micropython-as7341) - MicroPython library for AS7341.
*   [MicroPython\_ISL29125 (⭐0)](https://github.com/jposada202020/MicroPython_ISL29125) - MicroPython Driver for the Intersil ISL29125 Color Sensor.
*   [TCS3200-MicroPython (⭐1)](https://github.com/uraich/TCS3200-MicroPython) - A MicroPython driver and test programs for the TCS3200 color sensor.
*   [MicroPython\_TCS3430 (⭐0)](https://github.com/jposada202020/MicroPython_TCS3430) - MicroPython driver for the AMS TCS3430 Color and ALS sensor.
*   [micropython-gy33 (⭐2)](https://github.com/QuirkyCort/micropython-gy33) - UART and I2C drivers for GY-33 module (TCS3472 color sensor).
*   [veml6040 (⭐0)](https://github.com/octaprog7/veml6040) - MicroPython module for managing a color sensor RGBW, VEML6040 from Vishay.

#### Compass

*   [micropython-esp8266-hmc5883l (⭐14)](https://github.com/gvalkov/micropython-esp8266-hmc5883l) - 3-axis digital compass on the ESP8266.
*   [QMC5883 (⭐15)](https://github.com/robert-hh/QMC5883) - Python class for the QMC5883 Three-Axis Digital Compass IC.
*   [microPython\_AS5600L (⭐2)](https://github.com/capella-ben/microPython_AS5600L) - MicroPython driver for AS5600L magnet rotary position sensor.
*   [QMC5883 (⭐0)](https://github.com/octaprog7/QMC5883) - MicroPython module for control QMC5883L geomagnetic sensor.

#### Current

*   [micropythonINA219 (⭐4)](https://github.com/kabel42/micropythonINA219) - Driver for INA219 current sensor.
*   [pyb\_ina219 (⭐57)](https://github.com/chrisb2/pyb_ina219) - Driver for INA219 current sensor.
*   [INA219 (⭐13)](https://github.com/robert-hh/INA219) - INA219 MicroPython driver.
*   [TI\_INA226\_micropython (⭐29)](https://github.com/elschopi/TI_INA226_micropython) - MicroPython driver for Texas Instruments INA226 power measuring IC.
*   [micropython-current-monitor](https://gitlab.com/n.rj.powers/micropython-current-monitor) - Current monitor using the INA219 and an SSD1306 OLED.
*   [INA\_TI (⭐0)](https://github.com/octaprog7/INA_TI) - MicroPython module for controlling INA219, INA226 - A two-directional current / power monitor with the I2C interface.

#### Distance IR

*   [micropython-gp2y0e03 (⭐1)](https://github.com/mcauser/deshipu-micropython-gp2y0e03) - IR-LED distance measuring sensor using Sharp GP2Y0E03.
*   [micropython-vl6180 (⭐0)](https://github.com/mcauser/deshipu-micropython-vl6180) - Time-of-Flight sensor, ambient light sensor & IR emitter.
*   [GP2Y0A21YK (⭐0)](https://github.com/basanovase/GP2Y0A21YK) - GP2Y0A21YK MicroPython library.

#### Distance Laser

*   [micropython-vl53l0x (⭐0)](https://github.com/mcauser/deshipu-micropython-vl53l0x) - Time-of-Flight laser-ranging sensor.
*   [Qwiic\_TOF\_Module\_RFD77402 (⭐2)](https://github.com/ZIOCC/Qwiic_TOF_Module_RFD77402) - Qwiic TOF Module (RFD77402) time-of-flight rangefinding module.
*   [VL53L0X (⭐42)](https://github.com/uceeatz/VL53L0X) - MicroPython Library for LiDAR Sensor VL53L0X.
*   [vl53l1x\_pico (⭐21)](https://github.com/drakxtwo/vl53l1x_pico) - MicroPython driver for the VL53L1X ToF sensor.
*   [tf-luna-micropython (⭐11)](https://github.com/davmoz/tf-luna-micropython) - A simple MicroPython I2C library for TF-Luna LiDAR Module.
*   [vl53l5cx (⭐14)](https://github.com/mp-extras/vl53l5cx) - MicroPython and CircuitPython Package for the [VL53L5CX](https://www.st.com/en/imaging-and-photonics-solutions/vl53l5cx.html) (4x4/8x8 ToF sensor array).
*   [VL6180X (⭐5)](https://github.com/Ledbelly2142/VL6180X) - MicroPython driver for the VL6180X sensor on the ESP32.
*   [LidarLight\_v3HP\_micropython (⭐0)](https://github.com/Dnapert/LidarLight_v3HP_micropython) - A MicroPython library for the Garmin Lidar Lite v3HP.
*   [vl53l1x (⭐6)](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/vl53l1x.py) - MicroPython driver for the VL53L1X ToF sensor.
*   [vl53l0x-nb (⭐5)](https://github.com/antirez/vl53l0x-nb) - Fork of MicroPython driver for vl53l0x TOF sensor to add non-blocking mode.

#### Distance Ultrasonic

*   [micropython-hcsr04 (⭐153)](https://github.com/rsc1975/micropython-hcsr04) - Driver for HC-SR04 ultrasonic distance sensors.
*   [micropython-us100 (⭐3)](https://github.com/kfricke/micropython-us100) - MicroPython driver for the US-100 sonar distance sensor.
*   [micropython-i2c-ultrasonic (⭐2)](https://github.com/HowManyOliversAreThere/micropython-i2c-ultrasonic) - MicroPython driver for the RCWL-9620-based M5 I2C Ultrasonic Distance Unit.
*   [micropython-grove-ultrasonic-ranger (⭐0)](https://github.com/mores/TheMissingLink/tree/main/Seeed_MicroPython_UltrasonicRanger) - Driver for SeeedStudio's Grove Ultrasonic Ranger.

#### Dust

*   [pyGP2Y (⭐4)](https://github.com/amigcamel/pyGP2Y) - MicroPython library for the Sharp GP2Y1014AU0F Dust Sensor.

#### Energy

*   [ATM90E26\_Micropython (⭐3)](https://github.com/whatnick/ATM90E26_Micropython) - Driver for ATM90E26 energy metering device.
*   [MCP39F521 (⭐6)](https://github.com/warpme/MCP39F521) - ESP8266 scripts for reading MCP39F521 power monitors.
*   [micropython-p1meter (⭐26)](https://github.com/Josverl/micropython-p1meter) - A ESP32 sensor to read a p1 electricity meter and publish this to MQTT and Home Assistant, written in MicroPython.
*   [esp32-solar2 (⭐0)](https://github.com/octopusengine/esp32-solar2) - Simple solar regulator - MicroPython project.
*   [cs5490\_micropython (⭐1)](https://github.com/whatnick/cs5490_micropython) - MicroPython Driver for CS5490 Energy Monitor IC.

#### Gaseous

*   [micropython-MQ (⭐25)](https://github.com/kartun83/micropython-MQ) - Drivers for MQ series gas sensors.
*   [MQ135 (⭐44)](https://github.com/rubfi/MQ135) - Driver for MQ135 gas sensor.
*   [CCS811 (⭐30)](https://github.com/Notthemarsian/CCS811) - Basic MicroPython driver for CCS811 on ESP8266 boards.
*   [micropython-scd30 (⭐26)](https://github.com/agners/micropython-scd30) - MicroPython I2C driver for Sensirion SCD30 CO2 sensor module.
*   [MicroPython\_SCD4X (⭐9)](https://github.com/peter-l5/MicroPython_SCD4X) - MicroPython I2C driver for Sensirion SCD40 and SCD41 CO2 sensors.
*   [micropython-sgp40 (⭐3)](https://github.com/agners/micropython-sgp40) - MicroPython I2C driver for SGP40 VOC sensor module.
*   [MICS6814-Micropython-driver](https://gitlab.com/DanNduati/MICS6814-Micropython-driver) - ESP32 MicroPython driver for the Pimoroni MICS6814 breakout board.
*   [MicroPython\_AGS02MA (⭐0)](https://github.com/jposada202020/MicroPython_AGS02MA) - MicroPython Driver for the AGS02MA TVOC sensor.
*   [SCD4x (⭐12)](https://github.com/octaprog7/SCD4x) - MicroPython module for work with SCD4x (SCD40, SCD41) low power CO2, temperature & humidity electroacoustic sensor from Sensirion.
*   [ens160 (⭐1)](https://github.com/octaprog7/ens160) - MicroPython module for work with ENS160 Digital Metal-Oxide Multi-Gas Sensor.

#### Humidity

*   [MicroPython\_HTS221 (⭐0)](https://github.com/jposada202020/MicroPython_HTS221) - MicroPython Driver for the HTS221 Humidity Sensor.

#### Human Presence

*   [ld2410 (⭐6)](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/ld2410.py) - 24GHz human presence sensing module, capable of detecting moving and stationary targets, and providing an approximate range.

#### Light

*   [MicroPython-SI1145 (⭐6)](https://github.com/neliogodoi/MicroPython-SI1145) - SI1145 UV index, IR, visible light and proximity sensor.
*   [micropython-tsl2561 (⭐3)](https://github.com/kfricke/micropython-tsl2561) - Driver for the TSL2561 illumination sensor from TAOS / ams.
*   [mpy\_bh1750fvi\_esp8266 (⭐18)](https://github.com/catdog2/mpy_bh1750fvi_esp8266) - ESP8266 driver for BH1750FVI sensor.
*   [bh1750 (⭐54)](https://github.com/PinkInk/upylib/tree/master/bh1750) - BH1750 I2C digital light sensor driver.
*   [micropython-max44009 (⭐1)](https://github.com/mcauser/micropython-max44009) - MicroPython driver for the MAX44009 ambient light sensor.
*   [veml7700 (⭐14)](https://github.com/palouf34/veml7700) - Library for MicroPython for VEML7700 light sensor.
*   [MicroPython\_MAX44009\_driver (⭐2)](https://github.com/rcolistete/MicroPython_MAX44009_driver) - MicroPython driver for MAX44009 light sensor.
*   [MicroPython-VEML6075 (⭐2)](https://github.com/neliogodoi/MicroPython-VEML6075) - Driver base for the VEML6075 UV light sensor.
*   [BH1750 (⭐1)](https://github.com/octaprog7/BH1750) - MicroPython module for the BH1750 ambient light sensor (ALS).
*   [veml7700 (⭐0)](https://github.com/octaprog7/veml7700) - MicroPython module for the VEML7700 ambient light sensor (ALS) from Vishay.
*   [opt3001 (⭐0)](https://github.com/octaprog7/opt3001) - MicroPython module for OPT3001, external lighting sensor from Texas Instruments.
*   [ltr390uv (⭐0)](https://github.com/octaprog7/ltr390uv) - MicroPython module for LTR390UV, ambient light sensor in the visible and ultraviolet ranges.

#### Load Cell

*   [micropython-hx711 (⭐79)](https://github.com/SergeyPiskunov/micropython-hx711) - MicroPython driver for HX711 24-Bit Analog-to-Digital Converter.
*   [hx711\_mpy-driver (⭐8)](https://github.com/HowManyOliversAreThere/hx711_mpy-driver) - MicroPython Driver for the HX711 weighing sensor.
*   [hx710 (⭐6)](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/hx710.py) - MicroPython driver for the HX710.
*   [hx711 (⭐53)](https://github.com/robert-hh/hx711) - MicroPython driver for the HX711 load cell interface.
*   [hx710 (⭐2)](https://github.com/robert-hh/hx710) - MicroPython driver for the HX710 load cell interface.

#### Magnetometer

*   [MicroPython\_LIS2MDL (⭐0)](https://github.com/jposada202020/MicroPython_LIS2MDL) - MicroPython Driver for the ST LIS2MDL Magnetometer sensor.
*   [MicroPython\_LIS3MDL (⭐1)](https://github.com/jposada202020/MicroPython_LIS3MDL) - MicroPython Driver for the ST LIS3MDL magnetometer.
*   [MicroPython\_MLX90393 (⭐3)](https://github.com/jposada202020/MicroPython_MLX90393) - MicroPython Driver for the MLX90393 Magnetometer.
*   [MicroPython\_MMC5603 (⭐0)](https://github.com/jposada202020/MicroPython_MMC5603) - MicroPython driver for the Memsic MMC5603 Magnetometer.
*   [MicroPython\_BMM150 (⭐1)](https://github.com/jposada202020/MicroPython_BMM150) - MicroPython Driver for the Bosch BMM150 Magnetometer.
*   [MicroPython\_MMC5983 (⭐0)](https://github.com/jposada202020/MicroPython_MMC5983) - MicroPython Library for the Memsic MMC5983 Magnetometer.
*   [MMC5603 (⭐0)](https://github.com/octaprog7/MMC5603) - MicroPython module for MMC5603 geomagnetic sensor.
*   [HSCDTD008A (⭐0)](https://github.com/octaprog7/HSCDTD008A) - MicroPython module for HSCDTD008A geomagnetic sensor.
*   [RM3100 (⭐1)](https://github.com/octaprog7/RM3100) - MicroPython module for RM3100 geomagnetic sensor.

#### Motion Inertial

*   [micropython-bmx055 (⭐5)](https://github.com/micropython-IMU/micropython-bmx055) - Driver for Bosch BMX055 IMU sensor.
*   [micropython-bno055 (⭐4)](https://github.com/deshipu/micropython-bno055) - Bosch Sensortec BNO055 9DOF IMU sensor, I2C interface.
*   [micropython-lsm9ds0 (⭐4)](https://github.com/micropython-IMU/micropython-lsm9ds0) - LSM9DS0 g-force linear acceleration, Gauss magnetic and DPS angular rate sensors.
*   [micropython-mpu9250 (⭐152)](https://github.com/tuupola/micropython-mpu9250) - I2C driver for MPU9250 9-axis motion tracking device.
*   [micropython-mpu9x50 (⭐263)](https://github.com/micropython-IMU/micropython-mpu9x50) - Driver for the InvenSense MPU9250 inertial measurement unit.
*   [MPU6050-ESP8266-MicroPython (⭐88)](https://github.com/adamjezek98/MPU6050-ESP8266-MicroPython) - ESP8266 driver for MPU6050 accelerometer/gyroscope.
*   [py-mpu6050 (⭐83)](https://github.com/larsks/py-mpu6050) - ESP8266 driver for MPU6050 accelerometer/gyroscope.
*   [micropython-mpu6886 (⭐20)](https://github.com/tuupola/micropython-mpu6886) - MicroPython I2C driver for MPU6886 6-axis motion tracking device.
*   [micropython-fusion (⭐332)](https://github.com/micropython-IMU/micropython-fusion) - Sensor fusion calculates heading, pitch and roll from the outputs of motion tracking devices.
*   [flight\_controller (⭐75)](https://github.com/wagnerc4/flight_controller) - MicroPython flight controller.
*   [micropython-bno055 (⭐53)](https://github.com/micropython-IMU/micropython-bno055) - Bosch BNO055 driver for MicroPython. IMU with hardware sensor fusion.
*   [micropython-mpu6050-mqtt-streamer (⭐10)](https://github.com/mozanunal/micropython-mpu6050-mqtt-streamer) - Stream data from MPU6050 to MQTT server using MicroPython on ESP8266.
*   [upy-motion (⭐18)](https://github.com/OneMadGypsy/upy-motion) - A simple MPU6050 driver written in MicroPython.
*   [micropython-bno08x-rvc (⭐5)](https://github.com/rdagger/micropython-bno08x-rvc) - MicroPython library for BNO08x.
*   [micropython-mpu9250](https://gitlab.com/nnayo/micropython-mpu9250) - MicroPython MPU-9250 (MPU-6500 + AK8963) I2C driver.
*   [MicroPython\_ICM20948 (⭐11)](https://github.com/jposada202020/MicroPython_ICM20948) - MicroPython Driver for the TDK ICM20948 Accelerometer/Gyro Sensor.
*   [MicroPython\_BMI160 (⭐1)](https://github.com/jposada202020/MicroPython_BMI160) - MicroPython Driver for the Bosch BMI160 Accelerometer/Gyro Sensor.
*   [micropython-mpu6050 (⭐1)](https://github.com/wybiral/micropython-mpu6050) - MicroPython library for reading from MPU-6050 accelerometer and gyroscope modules.
*   [MicroPython\_ICG20660 (⭐0)](https://github.com/jposada202020/MicroPython_ICG20660) - MicroPython Driver for the TDK ICG20660 Accelerometer/Gyro sensor.
*   [MicroPython\_BMI270 (⭐8)](https://github.com/jposada202020/MicroPython_BMI270) - MicroPython Driver for the Bosch BMI270 Accelerometer/Gyro Sensor.
*   [MicroPython\_LSM6DSOX (⭐2)](https://github.com/jposada202020/MicroPython_LSM6DSOX) - MicroPython Library for the ST LSM6DSOX accelerometer/gyro Sensor.

#### Proximity

*   [uPy\_APDS9960 (⭐9)](https://github.com/rlangoy/uPy_APDS9960) - MicroPython proximity library for ESP8266 using APDS9960.
*   [MicroPython\_VCNL4010 (⭐0)](https://github.com/jposada202020/MicroPython_VCNL4010) - MicroPython Driver for the Vishay VCNL4010 Proximity and Ambient Light Sensor.
*   [apds9960 (⭐6)](https://github.com/QuirkyCort/IoTy/blob/main/public/extensions/apds9960.py) - MicroPython Driver for the APDS9960, with simple gesture detection.

#### Radiation

*   [micropython-geiger](https://github.com/Josep/micropython-geiger) - Geiger counter with MicroPython card.
*   [ESPGeiger (⭐22)](https://github.com/biemster/ESPGeiger) - MicroPython library for the ESP8266 Geiger counter.

#### Soil Moisture

*   [micropython-chirp (⭐3)](https://github.com/robberwick/micropython-chirp) - Driver for the Chirp Soil Moisture Sensor.
*   [MicroPython-MiFlora (⭐6)](https://github.com/matthias-bs/MicroPython-MiFlora) - Xiaomi Mi Flora (aka flower care) BLE plant sensors (soil moisture/conductivity/light intensity/temperature).
*   [micropython-miflora (⭐2)](https://github.com/agners/micropython-miflora) - MicroPython library for Xiaomi Mi Flora BLE plant sensors.

#### Spectral

*   [AS726X\_LoPy (⭐8)](https://github.com/jajberni/AS726X_LoPy) - MicroPython driver for the AS726X spectral sensor.
*   [MicroPython\_AS7262X\_driver (⭐2)](https://github.com/rcolistete/MicroPython_AS7262X_driver) - MicroPython driver for AS7262/AS7263 nano spectrometer sensor.

#### Temperature Analog

*   [micropython-max31855 (⭐1)](https://github.com/mcauser/deshipu-micropython-max31855) - Thermocouple amplifier, SPI interface.
*   [max31856 (⭐1)](https://github.com/alinbaltaru/max31856) - Precision thermocouple to digital converter with linearization, SPI interface.
*   [max31865 (⭐1)](https://github.com/sufyanaslam198/max31865) - Precision resistance-to-digital converter optimized for platinum resistance temperature detectors, SPI interface.
*   [mcp9700](https://gitlab.com/CrispyCrafter/mcp9700) - Generic MicroPython driver for MCP9700.
*   [micropython-generic-thermistor (⭐2)](https://github.com/Trexation/micropython-generic-thermistor) - MicroPython Generic Thermistor Library for simplified temperature sensing using NTC thermistors with voltage dividers.
*   [micropython-simple-thermistor (⭐0)](https://github.com/scruss/micropython-simple-thermistor) - Read NTC thermistor temperature wired in a potential divider.

#### Temperature Digital

*   [bme680-mqtt-micropython (⭐15)](https://github.com/robmarkcole/bme680-mqtt-micropython) - Driver for BME680 gas, pressure, temperature and humidity sensor.
*   [LM75-MicroPython (⭐3)](https://github.com/OldhamMade/LM75-MicroPython) - Driver for LM75 digital temperature sensor, I2C interface.
*   [micropython-am2320 (⭐25)](https://github.com/mcauser/micropython-am2320) - Aosong AM2320 temperature and humidity sensor, I2C interface.
*   [micropython-dht12 (⭐16)](https://github.com/mcauser/micropython-dht12) - Aosong DHT12 temperature and humidity sensor, I2C interface.
*   [micropython-hdc1008 (⭐4)](https://github.com/kfricke/micropython-hdc1008) - Driver for the Texas Instruments HDC1008 humidity and temperature sensor.
*   [micropython-mcp9808 (⭐7)](https://github.com/kfricke/micropython-mcp9808) - Driver for the Microchip MCP9808 temperature sensor.
*   [micropython-mpl115a2 (⭐2)](https://github.com/khoulihan/micropython-mpl115a2) - Pyboard driver for the MPL115A2 barometric pressure sensor.
*   [micropython-sht30 (⭐47)](https://github.com/rsc1975/micropython-sht30) - Driver for SHT30 temperature and humidity sensor.
*   [micropython-sht31 (⭐22)](https://github.com/kfricke/micropython-sht31) - Driver for the SHT31 temperature and humidity sensor.
*   [micropython-Si7005 (⭐1)](https://github.com/Smrtokvitek/micropython-Si7005) - Driver for Si7005 relative humidity and temperature sensor.
*   [micropython-si7021 (⭐0)](https://github.com/mcauser/deshipu-micropython-si7021) - SI7021 Temperature and humidity sensor, I2C interface.
*   [micropython-si7021 (⭐14)](https://github.com/chrisbalmer/micropython-si7021) - SI7021 Temperature and humidity sensor, I2C interface.
*   [micropython-Si705x (⭐1)](https://github.com/billyrayvalentine/micropython-Si705x) - Silicon Labs Si705x series of temperature sensors, I2C interface.
*   [micropython-Si70xx (⭐2)](https://github.com/billyrayvalentine/micropython-Si70xx) - Silicon Labs Si70xx series of relative humidity and temperature sensors, I2C interface.
*   [micropython-tmp102 (⭐8)](https://github.com/khoulihan/micropython-tmp102) - Driver for TMP102 digital temperature sensor.
*   [Official DHT11+DHT12 (⭐2.5k)](https://github.com/micropython/micropython-lib/tree/master/micropython/drivers/sensor/dht) - ESP8266 driver for DHT11 and DHT12 temperature and humidity sensor.
*   [sht25-micropython (⭐4)](https://github.com/Miceuz/sht25-micropython) - Driver for SHT25 temperature and humidity sensor.
*   [micropython-tmp1075 (⭐0)](https://github.com/mattytrentini/micropython-tmp1075) - Driver for the TI TMP1075 temperature sensor.
*   [micropython-sht11 (⭐2)](https://github.com/2black0/micropython-sht11) - Driver for Sensirion SHT11 temperature and humidity sensor.
*   [micropython-lm75a (⭐5)](https://github.com/mcauser/micropython-lm75a) - Driver for the NXP LM75A digital temperature sensor.
*   [BME680-Micropython (⭐37)](https://github.com/robert-hh/BME680-Micropython) - MicroPython driver for the BME680 sensor.
*   [htu21d-esp8266 (⭐5)](https://github.com/julianhille/htu21d-esp8266) - This is a MicroPython module / class to measure data from the HTU21D.
*   [HTU21D (⭐766)](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/HTU21D.md) - Asynchronous driver for HTU21D temperature and humidity sensor.
*   [esp-sht3x-micropython (⭐7)](https://github.com/HAIZAKURA/esp-sht3x-micropython) - A SHT3x (SHT30/31/35) library for ESP8266/ESP32 with MicroPython.
*   [sht25-micropython](https://gitlab.com/miceuz/sht25-micropython) - MicroPython implementation of API of SHT25 humidity and temperature sensor.
*   [micropython-sht30 (⭐3)](https://github.com/schinckel/micropython-sht30) - SHT30 sensor driver in pure Python based on I2C bus.
*   [micropython\_ahtx0 (⭐37)](https://github.com/targetblank/micropython_ahtx0) - MicroPython driver for the AHT10 and AHT20 temperature and humidity sensors.
*   [sht85 (⭐0)](https://github.com/octaprog7/sht85) - MicroPython driver for the [Sensiron SHT85](https://sensirion.com/products/catalog/SHT85/) humidity and temperature sensor.
*   [micropython-zacwire (⭐0)](https://github.com/mdaeron/micropython-zacwire) - MicroPython driver for the ZACwire protocol used in TSic 506F temperature sensors.
*   [MicroPython\_HTU31D (⭐1)](https://github.com/jposada202020/MicroPython_HTU31D) - MicroPython library for TE HTU31D temperature and humidity sensors.
*   [MicroPython\_SHTC3 (⭐5)](https://github.com/jposada202020/MicroPython_SHTC3) - MicroPython Driver for the Sensirion SHTC3 Temperature and Humidity Sensor.
*   [MicroPython\_TMP117 (⭐2)](https://github.com/jposada202020/MicroPython_TMP117) - MicroPython Driver for the TMP117 Temperature Sensor.
*   [MicroPython\_SI7021 (⭐0)](https://github.com/jposada202020/MicroPython_SI7021) - MicroPython Library for the Temperature and Humidity SI7021 Sensor.
*   [MicroPython\_ADT7410 (⭐0)](https://github.com/jposada202020/MicroPython_ADT7410) - MicroPython Driver for the Analog Devices ADT7410 Temperature Sensor.
*   [MicroPython\_WSENTIDS (⭐0)](https://github.com/jposada202020/MicroPython_WSENTIDS) - MicroPython library for the WSEN WSEN-TIDS temperature Sensor.
*   [MicroPython\_HS3003 (⭐0)](https://github.com/jposada202020/MicroPython_HS3003) - MicroPython Driver for the Renesas HS3003 Temperature and Humidity Sensor.
*   [MicroPython\_STTS22H (⭐0)](https://github.com/jposada202020/MicroPython_STTS22H) - MicroPython Driver for the STTS22H Temperature Sensor.
*   [MicroPython\_HTU21DF (⭐0)](https://github.com/jposada202020/MicroPython_HTU21DF) - MicroPython HTU21D-F Temperature & Humidity driver.
*   [MicroPython\_SHT4X (⭐8)](https://github.com/jposada202020/MicroPython_SHT4X) - MicroPython Driver for the Sensirion Temperature and Humidity SHT40 and SHT45 Sensor.
*   [MicroPython\_SHT20 (⭐0)](https://github.com/jposada202020/MicroPython_SHT20) - MicroPython Driver for the Sensirion SHT20 Temperature Sensor.
*   [MicroPython\_MCP9808 (⭐1)](https://github.com/jposada202020/MicroPython_MCP9808) - MicroPython Driver for the Microchip MCP9808 Temperature Sensor.
*   [MicroPython\_HDC1080 (⭐1)](https://github.com/jposada202020/MicroPython_HDC1080) - MicroPython driver for the TI HDC1080 Temperature and Humidity sensor.
*   [TMP117 (⭐2)](https://github.com/octaprog7/TMP117) - MicroPython module for the TMP117 temperature sensor from Texas Instruments.
*   [BME680 (⭐1)](https://github.com/octaprog7/BME680) - MicroPython module for the BME680, Bosch low power gas, pressure, temperature & humidity sensor.
*   [SHT30 (⭐2)](https://github.com/robert-hh/SHT30) - MicroPython driver for the Sensirion SHT3x sensor.
*   [MicroPython\_AS6212 (⭐0)](https://github.com/jposada202020/MicroPython_AS6212) - MicroPython Library for the ASM AS6212 Temperature Sensor.
*   [MicroPython\_PCT2075 (⭐0)](https://github.com/jposada202020/MicroPython_PCT2075) - MicroPython Driver for the NXP Semiconductors PCT2075 Temperature Sensor.
*   [micropython-hdc1080 (⭐2)](https://github.com/mcauser/micropython-hdc1080) - MicroPython driver for the HDC1080 temperature and humidity sensor.
*   [bme680-pure-mp (⭐13)](https://github.com/antirez/bme680-pure-mp) - Pure MicroPython Bosch BME680 sensor driver.
*   [SHT4X (⭐0)](https://github.com/octaprog7/SHT4X) - MicroPython module for controlling the SHT4x - 4th generation relative humidity and temperature sensor.

#### Temperature IR

*   [micropython-mlx90614 (⭐35)](https://github.com/mcauser/micropython-mlx90614) - Driver for Melexis MLX90614 IR temperature sensor.
*   [MicroPython\_MLX90615\_driver (⭐2)](https://github.com/rcolistete/MicroPython_MLX90615_driver) - MicroPython driver for Melexis MLX90615 IR temperature sensor.

#### Touch Capacitive

*   [micropython-mpr121 (⭐17)](https://github.com/mcauser/micropython-mpr121) - Driver for MPR121 capacitive touch keypads and breakout boards.
*   [micropython-ttp223 (⭐8)](https://github.com/mcauser/micropython-ttp223) - Examples using TTP223 capacitive touch module.
*   [micropython-TTP229-BSF (⭐17)](https://github.com/alankrantas/micropython-TTP229-BSF) - MicroPython ESP8266/ESP32 driver for TTP229-BSF 16-key capacitive keypad in serial interface mode.
*   [uFT6336U (⭐7)](https://github.com/fantasticdonkey/uFT6336U) - MicroPython I2C driver for the Focus LCDs FT6336U capacitive touch panel controller IC.
*   [MicroPythonTrill (⭐5)](https://github.com/Heerkog/MicroPythonTrill) - Trill touch sensor library for MicroPython.
*   [L58Touch (⭐5)](https://github.com/russhughes/L58Touch) - L58 Multi-Touch MicroPython Module.
*   [micropython-ft6x06 (⭐9)](https://github.com/antirez/micropython-ft6x06) - Simple driver for FT6x06 capacitive touch sensor in pure Python.

#### Touch Resistive

*   [XPT2046-touch-pad-driver (⭐19)](https://github.com/robert-hh/XPT2046-touch-pad-driver) - Driver for XPT2046 touch pad controller used in many TFT modules.

### Scheduling

*   [micropython-mcron (⭐36)](https://github.com/fizista/micropython-mcron) - MicroCRON is a time-based task scheduling program for MicroPython.
*   [micropython-scron (⭐9)](https://github.com/fizista/micropython-scron) - SimpleCRON is a time-based task scheduling program inspired by the well-known cron program for Unix systems.
*   [Schedule (⭐766)](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/SCHEDULE.md) - A scheduler for asyncio based applications. Schedule events at specified times and dates or with reference to Sun and Moon rise and set.
*   [micropython-aioschedule (⭐9)](https://github.com/ThinkTransit/micropython-aioschedule) - A persistent uasyncio scheduler that supports deepsleep between task runs.

### Storage

#### Configuration file

*   [uPyftsConf (⭐5)](https://github.com/aleppax/upyftsconf) - MicroPython Far Too Simple Config File. Single file library that writes configurations to itself.

#### Databases

*   [uPyMySQL (⭐24)](https://github.com/dvrhax/uPyMySQL) - Pure MicroPython MySQL Client.
*   [micropython-redis (⭐21)](https://github.com/dwighthubbard/micropython-redis) - A Redis client implementation designed for use with MicroPython.
*   [picoredis (⭐9)](https://github.com/SpotlightKid/picoredis) - A very minimal Redis client (not only) for MicroPython.
*   [micropg (⭐26)](https://github.com/nakagami/micropg) - PostgreSQL database driver for MicroPython.
*   [micropg\_lite (⭐4)](https://github.com/TimonW-Dev/micropg_lite) - Lightweight version of micropg with some slight limitations (e.g. error handling), in order to run on low-RAM microcontrollers (works with ESP8266).
*   [micropg\_superlite (⭐0)](https://github.com/TimonW-Dev/micropg_superlite) - The lightest PostgreSQL database driver for micropython based on micropg\_lite/micropg, but has even stronger restrictions in functionality and focuses only on the absolutely necessary functions.
*   [micropython-cratedb (⭐6)](https://github.com/crate/micropython-cratedb/) - MicroPython driver for CrateDB databases.
*   [nmongo (⭐20)](https://github.com/nakagami/nmongo) - MongoDB client for CPython and MicroPython, with MongoDB shell-like APIs.
*   [MicroPyDatabase (⭐20)](https://github.com/sungkhum/MicroPyDatabase) - A low-memory JSON-based database for MicroPython.
*   [micropython-firebase-realtime-database (⭐24)](https://github.com/ckoever/micropython-firebase-realtime-database) - Firebase implementation for MicroPython optimized for ESP32.
*   [micropython-firebase-firestore (⭐8)](https://github.com/WoolDoughnut310/micropython-firebase-firestore) - Firebase Firestore implementation for MicroPython.
*   [uSQLite (⭐97)](https://github.com/spatialdude/usqlite) - SQLite library module for MicroPython.

#### EEPROM

*   [micropython\_eeprom (⭐79)](https://github.com/peterhinch/micropython_eeprom) - Cross-platform MicroPython device drivers for memory chips (EEPROM, FRAM, Flash, PSRAM).
*   [mb\_24x256\_512 (⭐1)](https://github.com/MarksBench/mb_24x256_512) - Very simple MicroPython module/driver for Microchip 24x256 and 24x512 I2C EEPROM devices.
*   [micropython-eeprom (⭐6)](https://github.com/brainelectronics/micropython-eeprom) - MicroPython driver for AT24Cxx EEPROM.

#### Flash

*   [micropython\_data\_to\_py (⭐29)](https://github.com/peterhinch/micropython_data_to_py) - A Python 3 utility to convert an arbitrary binary file to Python source for freezing as bytecode in Flash.
*   [micropython-winbond (⭐12)](https://github.com/brainelectronics/micropython-winbond) - Interact with Winbond W25Q Flash chips via SPI.
*   [freezeFS (⭐29)](https://github.com/bixb922/freezeFS) - Create self-extracting compressed or self-mounting archives for MicroPython.

#### FRAM

*   [micropython-fram (⭐1)](https://github.com/rolandvs/micropython-fram) - Pyboard driver for Ferroelectric RAM module.

#### PSRAM

*   [mb\_PSRAM\_64Mb\_SPI (⭐12)](https://github.com/MarksBench/mb_PSRAM_64Mb_SPI) - Very simple MicroPython module to use a generic 64Mbit PSRAM (ie Adafruit 4677) with a Raspberry Pi Pico (RP2040).

#### SD

*   [mp-sdcard-littleFS (⭐4)](https://github.com/jornamon/mp-sdcard-littleFS) - MicroPython SD card driver that works with LittleFS2 (implements extended interface).

#### SRAM

*   [mb\_23LC1024 (⭐1)](https://github.com/MarksBench/mb_23LC1024) - Very simple MicroPython module to use a Microchip 23LC1024 SPI SRAM with a Raspberry Pi Pico (RP2040).
*   [mb\_47x16 (⭐1)](https://github.com/MarksBench/mb_47x16) - Very simple MicroPython module/driver for Microchip 47x16 EERAM devices (47L/47C).

### Threading

*   [MicroWorkers (⭐45)](https://github.com/jczic/MicroWorkers) - A micro workers class that easily manages a pool of threads to optimise simultaneous jobs and jobs endings, for MicroPython (used on Pycom modules & ESP32).

### User Interface

*   [upymenu (⭐27)](https://github.com/jplattel/upymenu) - MicroPython Menu for LCD Displays.

### Utilities

*   [micropython-hexdump (⭐4)](https://github.com/mattytrentini/micropython-hexdump) - An implementation of Hexdump for MicroPython.

## Community

*   [MicroPython Discussions on GitHub](https://github.com/orgs/micropython/discussions) - GitHub discussions for all things related to MicroPython.
*   [MicroPython Forum (archive)](https://forum.micropython.org/) - Archived community conversations on all things related to MicroPython.
*   [Discord](https://discord.com/invite/qw7d8bv) - Get an invite to the MicroPython Discord server.
*   [MicroPython on Mastodon / Fediverse](https://fosstodon.org/@MicroPython) - Follow MicroPython in the Fediverse.
*   [MicroPython on Twitter](https://twitter.com/micropython) - Follow MicroPython on Twitter for latest news and updates.
*   [MicroPython on Facebook](https://www.facebook.com/micropython) - Like MicroPython on Facebook for competitions, news and updates.
*   [Melbourne MicroPython Meetup](https://www.meetup.com/en-AU/MicroPython-Meetup) - Regular meetup at CCHS in Melbourne, Australia.

## Tutorials

*   [asyncio (⭐766)](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/TUTORIAL.md) - Write asynchronous code which interfaces to hardware devices.
*   [Asynchronous drivers (⭐766)](https://github.com/peterhinch/micropython-async/blob/master/v3/docs/DRIVERS.md) - Tutorial and code for asynchronous interfaces to switches, pushbuttons, encoders and ADCs.
*   [Pyboard micropower (⭐45)](https://github.com/peterhinch/micropython-micropower) - Tutorial and code for low power applications on Pyboard 1.x and Pyboard D.
*   [3D rotation with quaternions (⭐484)](https://github.com/peterhinch/micropython-samples/blob/master/QUATERNIONS.md) - Tutorial and code for the easy way to do 3D rotation.
*   [Miguel Grinberg](https://blog.miguelgrinberg.com/category/MicroPython) - MicroPython and the Internet of Things.
*   [Bhavesh Kakwani](https://bhave.sh/) - MicroPython videos + written tutorials.
*   [CoderDojo Twin Cities MicroPython](https://www.coderdojotc.org/micropython/) - Full coding curriculum for teaching MicroPython to children.
*   [MicroPython Tutorials for ESP32 boards](https://www.upesy.com/blogs/tutorials/tutorials-for-esp32-with-micropython-code) - Tutorials with code examples to learn the basic of MicroPython with ESP32 boards.
*   [Learn MicroPython with a Pi Pico board](https://www.upesy.com/blogs/tutorials/tutorials-for-rpi-pi-pico-with-micropython-code) - Tutorials on MicroPython with the Raspberry Pi Pico / RP240 boards.

## Books

*   [Programming with MicroPython: Embedded Programming with Microcontrollers and Python](https://www.oreilly.com/library/view/programming-with-micropython/9781491972724/) - By Nicholas H. Tollervey. ISBN 9781491972731.
*   [MicroPython for the Internet of Things: A Beginner's Guide to Programming with Python on Microcontrollers](https://link.springer.com/book/10.1007/978-1-4842-3123-4) - By Charles Bell. ISBN 9781484231227.
*   [Beginning MicroPython with the Raspberry Pi Pico: Build Electronics and IoT Projects](https://link.springer.com/book/10.1007/978-1-4842-8135-2) - By Charles Bell. ISBN 9781484281345.
*   [MicroPython Cookbook](https://www.packtpub.com/en-us/product/micropython-cookbook-9781838641955) - By Marwan Alsabbagh. ISBN 9781838649951.
*   [Python for Microcontrollers: Getting Started with MicroPython](https://www.mheducation.com.au/python-for-microcontrollers-getting-started-with-micropython-9781259644535-aus) - By Donald Norris. ISBN 9781259644535.
*   [Advanced Programming in MicroPython By Example](https://www.amazon.com/Advanced-Programming-MicroPython-Example-Magda/dp/1090900937) - By Yury Magda. ISBN 9781090900937.
*   [MicroPython Projects](https://www.packtpub.com/en-us/product/micropython-projects-9781789952537) - By Jacob Beningo. ISBN 9781789958034.
*   [Get Started with MicroPython on Raspberry Pi Pico 2nd Edition](https://store.rpipress.cc/collections/books/products/get-started-with-micropython-on-raspberry-pi-pico-2nd-edition) - By Gareth Halfacree and Ben Everard. ISBN 9781912047291.
*   [MicroPython for Microcontrollers](https://www.elektor.com/micropython-for-microcontrollers-e-book) - By Günter Spanner. ISBN 9783895764370.
*   [MicroPython for the Raspberry Pi Pico W: A gentle introduction to programming digital circuits with Python](https://www.amazon.com/MicroPython-Raspberry-Pico-introduction-programming/dp/B0BKSCV18D) - By Miguel Grinberg. ISBN 9798361302710.
*   [Programming ESP32: Learn MicroPython Coding and Electronics](https://www.amazon.com/Programming-ESP32-MicroPython-Coding-Electronics/dp/1739487451/) - By Simon Monk. ISBN 9781739487454.

## Frameworks

*   [micrOS (⭐113)](https://github.com/BxNxM/micrOS) - MicroPython-based IoT Framework.
*   [terkin-datalogger (⭐61)](https://github.com/hiveeyes/terkin-datalogger) - Flexible data logger application for MicroPython and CPython.
*   [perthensis](https://codeberg.org/scy/perthensis) - Perthensis: an asynchronous framework for MicroPython.
*   [meerkat (⭐9)](https://github.com/crdietrich/meerkat) - I2C Data Acquisition for MicroPython and Raspberry Pi.

## Resources

*   [MicroPython](https://micropython.org) - Project website. Test drive the Pyboard. Try MicroPython online with Unicorn.
*   [MicroPython on GitHub (⭐20k)](https://github.com/micropython/micropython) - Submit bug reports, follow and join in development on GitHub.
*   [MicroPython Official Documentation](https://docs.micropython.org/) - For various ports, including quick reference, general information, examples and tutorials.
*   [MicroPython Wiki (⭐20k)](https://github.com/micropython/micropython/wiki) - Community generated documentation and examples of the features of MicroPython and the Pyboard.
*   [MicroPython Newsletter](https://micropython.org/newsletter) - Subscribe to the MicroPython newsletter for news and announcements including new features and new products.
*   [MicroPython Store](https://store.micropython.org/) - Where you can buy the Pyboard, housings, skins, books, connectors and peripherals.
*   [MicroPython on Wikipedia](https://en.wikipedia.org/wiki/MicroPython) - MicroPython on Wikipedia.
*   [awesome-micropythons (⭐46)](https://github.com/adafruit/awesome-micropythons) - The many forks & ports of MicroPython.

## Development

### Code Generation

*   [micropy-cli (⭐319)](https://github.com/BradenM/micropy-cli) - Micropy CLI is a project management/generation tool for writing MicroPython code in modern IDEs such as Visual Studio Code.
*   [micropython-stubber (⭐200)](https://github.com/Josverl/micropython-stubber) - Generate and use stubs for different MicroPython firmwares to use with Visual Studio Code or any IDE and linter.
*   [micropython-stubs (⭐187)](https://github.com/Josverl/micropython-stubs) - Stubs of most MicroPython ports, boards and versions to make writing code that much simpler.
*   [micropy-stubs (⭐30)](https://github.com/BradenM/micropy-stubs) - Automatically Generated Stub Packages for Micropy-Cli and whomever else.
*   [micropython-extmod-generator (⭐23)](https://github.com/prusnak/micropython-extmod-generator) - Generator for MicroPython external modules written in C.
*   [micropython-package-template (⭐7)](https://github.com/brainelectronics/micropython-package-template) - GitHub workflow supported MicroPython package template with deploys to the [Python Package Index](https://pypi.org/) on a push to the main branch and test deploys to the [Test Python Package Index](https://test.pypi.org/) on PRs.
*   [micropython-usermod](https://micropython-usermod.readthedocs.io) - Online book about MicroPython external modules writen in C.
*   [wasm2mpy (⭐127)](https://github.com/vshymanskyy/wasm2mpy) - Compile WebAssembly to native MicroPython `.mpy` files. Allows writing code in various statically compiled languages, and translating them to C for near-native performance.

### Debugging

*   [esp32-backtrace (⭐27)](https://github.com/tve/esp32-backtrace) - ESP32 Exception Stack Backtrace Analyzer.
*   [micropython-aiosentry (⭐11)](https://github.com/devbis/micropython-aiosentry) - Asynchronous Sentry.io micro client for MicroPython.
*   [micropython-usyslog (⭐17)](https://github.com/kfricke/micropython-usyslog) - Simple remote syslog client for MicroPython.
*   [Asynchronous monitor (⭐34)](https://github.com/peterhinch/micropython-monitor) - Use a Raspberry Pico and a logic analyser or scope to monitor asynchronous code.

### Firmware

*   [micropython-builder (⭐0)](https://github.com/jonahbron/micropython-builder) - Tool for building and flashing a custom MicroPython firmware.

### IDEs

*   [BIPES](https://bipes.net.br/ide/) - Web-based IDE for MicroPython with file manager, editor, code generation from blocks, IoT dashboard and Serial/USB/Bluetooth/WebREPL console on the web browser. Source: <https://github.com/BIPES>.
*   [ESP32-MPY-Jama (⭐447)](https://github.com/jczic/ESP32-MPY-Jama) - Tool for managing Espressif ESP32 microcontrollers with MicroPython.
*   [JetBrains IntelliJ/PyCharm MicroPython Plugin](https://plugins.jetbrains.com/plugin/9777-micropython) - Plugin for MicroPython devices in IntelliJ and PyCharm.
*   [MicroPython IDE for VSCode](https://marketplace.visualstudio.com/items?itemName=dphans.micropython-ide-vscode) - MicroPython IDE for Visual Studio Code.
*   [MicroPython-REPLink for VSCode](https://marketplace.visualstudio.com/items?itemName=SWC-Fablab.micropython-replink) - Handy shortcuts for interacting with a MicroPython REPL terminal.
*   [MPRemote for VSCode](https://marketplace.visualstudio.com/items?itemName=DavesCodeMusings.mpremote) - An extension to provide easy access to some of mpremote's functionality from within Visual Studio Code.
*   [Mu Editor](https://codewith.mu/) -  Code with Mu: a simple Python/MicroPython/CircuitPython editor for beginner programmers.
*   [Thonny IDE](https://thonny.org/) - Thonny: Python IDE for beginners.
*   [ViperIDE](https://viper-ide.org) - An innovative MicroPython / CircuitPython IDE for Web and Mobile. No installation required.
*   [Pyboard File Manager (⭐5)](https://github.com/joewez/PyboardFileManager) - Pyboard File Manager: Windows GUI for Pyboard.py compatible devices.
*   [uPIDE (⭐23)](https://github.com/harbaum/upide) - µPIDE is a simple IDE for MicroPython.

### Logging

*   [micropython-ulogger (⭐36)](https://github.com/majoson-chen/micropython-ulogger) - Lightweight log module customized for MicroPython.
*   [scd30logger (⭐0)](https://github.com/agners/scd30logger) - Sensirion SCD30 based CO2, Humidity and Temperature Logger for MicroPython.
*   [sht15logger (⭐0)](https://github.com/agners/sht15logger) - MicroPython Temperature and Humidity Logger using Sensirion SHT15.

### Shells

#### Jupyter

*   [micropython-magic (⭐24)](https://github.com/josverl/micropython-magic) - MicroPython integrated into Jupyter notebooks.
*   [jupyter\_upydevice\_kernel (⭐14)](https://github.com/Carglglz/jupyter_upydevice_kernel) - Jupyter kernel to interact with a MicroPython board over its REPL interface.

#### On Device

*   [upy-shell (⭐40)](https://github.com/dhylands/upy-shell) - A simple command line-based shell for MicroPython.
*   [Micropython-Editor (⭐231)](https://github.com/robert-hh/Micropython-Editor) - Small on-board editor for Pyboard, WiPy, ESP8266, ESP32, PyCom and Adafruit devices written in Python.

#### On Host

*   [rshell (⭐977)](https://github.com/dhylands/rshell) - Copy or sync files to boards, enter REPL from your terminal.
*   [ampy (⭐736)](https://github.com/scientifichackers/ampy) - Utility to interact with a MicroPython board over a serial connection.
*   [mpbridge (⭐53)](https://github.com/AmirHmZz/mpbridge) - A file system bridge to synchronize and manage files on a device running MicroPython.
*   [mpfshell (⭐407)](https://github.com/wendlers/mpfshell) - A simple shell-based file explorer for ESP8266 and WiPy.
*   [mpsync (⭐7)](https://github.com/thilomichael/mpsync) - A tool that automatically synchronizes code to a MicroPython board.
*   [mpremote (⭐20k)](https://github.com/micropython/micropython/blob/master/tools/mpremote/README.md) - Powerful official shell that supports mounting the host's current directory on the target. Run code without changing the target's filesystem.
*   [MPRemoteEditor (⭐3)](https://github.com/joewez/MPRemoteEditor) - A simple Windows IDE for developing with MicroPython MPRemote devices.
*   [uPyExplorer (⭐6)](https://github.com/RetepRelleum/uPyExplorer) - Explorer for MicroPython Device.
*   [mpr (⭐15)](https://github.com/bulletmark/mpr) - Wrapper for MicroPython mpremote tool.

## Miscellaneous

*   [MicroPython Kickstarter](https://www.kickstarter.com/projects/214379695/micro-python-python-for-microcontrollers) - 1,931 backers pledged £97,803 to help bring this project to life.
*   [MicroPython on the ESP8266 Kickstarter](https://www.kickstarter.com/projects/214379695/micropython-on-the-esp8266-beautifully-easy-iot) - 1,399 backers pledged £28,534 to help bring this project to life.

## Contributing

Contributions and suggestions are always welcome! Please take a look at the [contribution guidelines (⭐1.5k)](https://github.com/mcauser/awesome-micropython/blob/master/contributing.md) first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could vote for them by adding 👍 to them.

