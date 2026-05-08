# Awesome Home Assistant Overview

A curated list of amazingly awesome Home Assistant resources.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/frenck/awesome-home-assistant/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 frenck/awesome-home-assistant](https://github.com/frenck/awesome-home-assistant) · ⭐ 7.6K · 🏷️ Platforms

[ [Daily](/content/frenck/awesome-home-assistant/README.md) / [Weekly](/content/frenck/awesome-home-assistant/week/README.md) / Overview ]

---

# Awesome Home Assistant [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

<!--lint disable double-link-->

<div align="center">
  <a href="https://awesome-ha.com">
    <img width="400" src="https://www.awesome-ha.com/images/awesome-home-assistant.svg" alt="Awesome Home Assistant">
  </a>
  <br>
  <a href="https://awesome-ha.com"><strong>https://awesome-ha.com</strong></a>
</div>

Home Assistant is an open source home automation that puts local control and
privacy first. Powered by a worldwide community of tinkerers and DIY
enthusiasts. Perfect to run on a Raspberry Pi or a local server.

If you want to get an impression on the look and feel,
you should check out the [Home Assistant online demo](https://demo.home-assistant.io).

Awesome Home Assistant is a curated list of awesome
[Home Assistant](https://www.home-assistant.io) resources.
Additional software, tutorials, custom integrations, apps,
custom dashboard cards & plugins, cookbooks, example setups, and much more.

Most of the items below can be installed in one click through
[HACS](https://hacs.xyz), the Home Assistant Community Store, after you
install Home Assistant itself. Home Assistant is owned by the
[Open Home Foundation](https://www.openhomefoundation.org), which also
stewards ESPHome, Music Assistant, Z-Wave JS, and the open voice tools you
will see throughout the list. If you are buying smart-home devices, the
[Works with Home Assistant](https://works-with.home-assistant.io) program
tests for privacy, local control, and long-term support.

The list is divided into categories. The links in those categories do not have
pre-established order; the order is for contribution. If you want to contribute,
please read the [guide (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/blob/main/.github/CONTRIBUTING.md)
or raise an [issue (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose)
to suggest additions, updates or removals.

## Contents

*   [How to use](#how-to-use)
*   [Installing](#installing)
*   [In case you need help](#in-case-you-need-help)
    *   [🤝 Official Communities](#-official-communities)
    *   [🌐 Other Communities](#-other-communities)
*   [Public Configurations](#public-configurations)
*   [Custom Integrations](#custom-integrations)
    *   [🤖 AI & LLMs](#-ai--llms)
    *   [💡 Lighting](#-lighting)
    *   [🌡️ Climate](#-climate)
    *   [⚡ Energy & solar](#-energy--solar)
    *   [📹 Cameras & video](#-cameras--video)
    *   [🚨 Security & alarm](#-security--alarm)
    *   [🔊 Voice & media playback](#-voice--media-playback)
    *   [🚗 Cars & EV charging](#-cars--ev-charging)
    *   [📍 Presence & location](#-presence--location)
    *   [🧹 Vacuums](#-vacuums)
    *   [🔵 Bluetooth & BLE](#-bluetooth--ble)
    *   [🔋 Battery monitoring](#-battery-monitoring)
    *   [🏷️ Vendor & brand](#-vendor--brand)
    *   [🛠️ Automation tooling](#-automation-tooling)
    *   [🏘️ Civic & household](#-civic--household)
    *   [🔐 Network & authentication](#-network--authentication)
    *   [🔗 Federation & multi-instance](#-federation--multi-instance)
    *   [📊 Logging & analytics](#-logging--analytics)
*   [Dashboard Cards](#dashboard-cards)
    *   [🧱 Dashboard frameworks](#-dashboard-frameworks)
    *   [📐 Layout helpers](#-layout-helpers)
    *   [📈 Charts & graphs](#-charts--graphs)
    *   [📋 Status & info rows](#-status--info-rows)
    *   [☀️ Weather cards](#-weather-cards)
    *   [🎵 Media cards](#-media-cards)
    *   [🌡️ Climate cards](#-climate-cards)
    *   [⚡ Energy cards](#-energy-cards)
    *   [💡 Lighting cards](#-lighting-cards)
    *   [🗺️ Maps & location](#-maps--location)
    *   [📸 Camera cards](#-camera-cards)
    *   [🧹 Vacuum cards](#-vacuum-cards)
    *   [📅 Calendar & feed](#-calendar--feed)
    *   [📡 Remote control](#-remote-control)
    *   [🍃 Air quality](#-air-quality)
    *   [🖥️ Kiosk & wallpanel](#-kiosk--wallpanel)
*   [Dashboards](#dashboards)
*   [Themes](#themes)
*   [Icon packs](#icon-packs)
*   [Apps](#apps)
    *   [🛡️ Official Apps](#-official-apps)
    *   [📦 Third Party Apps](#-third-party-apps)
*   [DIY](#diy)
    *   [🧩 Standalone projects](#-standalone-projects)
    *   [🌉 DIY Gateways](#-diy-gateways)
    *   [🔨 DIY Projects](#-diy-projects)
*   [Tools & Utilities](#tools--utilities)
*   [Online Resources](#online-resources)
    *   [✍️ Blogs](#-blogs)
    *   [📺 YouTube Channels](#-youtube-channels)
    *   [🎙️ Podcasts](#-podcasts)
    *   [📱 Social](#-social)
*   [Alternative Home Automation Software](#alternative-home-automation-software)
*   [Other Awesome Lists](#other-awesome-lists)
*   [Trademark Legal Notice](#trademark-legal-notice)

## How to use

Awesome Home Assistant is a curated list of the best resources for Home
Assistant, the open-source home automation that runs on your own hardware
and keeps your data local. Use it to find the apps, custom cards, custom
integrations, and tutorials that experienced users actually rely on.

You can navigate through the list by:

*   Simply press <kbd>command/ctrl</kbd> + <kbd>F</kbd> to search for a keyword
*   Go through our [*Contents list*](#contents)
*   Alternatively, use the search on our website: <https://www.awesome-ha.com>

## Installing

New to Home Assistant and not sure where to start? The easiest path is to
grab a [Home Assistant Green](https://www.home-assistant.io/green/) and plug
it in. If you would rather use hardware you already own (a Raspberry Pi, a
Mini PC, an old laptop), the official guides below cover every option.
Whichever you pick, you end up running the same Home Assistant. Once it is
up, install [HACS](https://hacs.xyz) and most of the items in this list
become one click away.

*   [Home Assistant Installation](https://www.home-assistant.io/installation/) - The official installation guides.
*   [Compare Installation Methods](https://www.home-assistant.io/installation/#compare-installation-methods) - The available installation methods compared.

## In case you need help

Stuck on a configuration, wondering why a device will not pair, or just want
to see what other people are building? Home Assistant has one of the most
active home-automation communities on the internet, and most of it is free
to join.

### 🤝 Official Communities

*   [Home Assistant Discord](https://discordapp.com/invite/c5DvZ4e) - Join the chat, most of us are there.
*   [Home Assistant Community](https://community.home-assistant.io/?u=frenck) - The community discussion forum.
*   [Home Assistant Subreddit](https://www.reddit.com/r/homeassistant/) - If you are into Reddit, subscribe.
*   [Home Assistant Facebook Group](https://www.facebook.com/groups/HomeAssistant/) - Facebook group for enthusiasts.

### 🌐 Other Communities

*   [Dr. ZZs](https://www.facebook.com/groups/1969622823351838/) - Facebook group by Dr. Zzs.
*   [ESPHome Discord](https://discord.gg/KhAMKrd) - Get support for your DIY ESPHome project.
*   🇳🇱 [Dutch Domotics Discord](https://discord.gg/Ee5X7T7) - Dutch Discord server with home automation enthusiasts.

## Public Configurations

*Wondering how more experienced users have set up their thermostat schedules, presence detection, or automations? These are full Home Assistant configurations published on GitHub. Read them like recipe books, copy the bits that look useful, and skip the rest.*

*   [Carlo Costanzo (⭐5.1k)](https://github.com/CCOSTAN/Home-AssistantConfig#logo) - Probably the most documented configuration out there (5,147★).
*   [DubhAd (⭐686)](https://github.com/DubhAd/Home-AssistantConfig) - Also known as Tinkerer, shares his configuration files (686★).
*   [geekofweek (⭐1.5k)](https://github.com/geekofweek/homeassistant) - Has 300+ automations (1,472★).
*   [Alok Saboo (⭐2k)](https://github.com/arsaboo/homeassistant-config) - Also known as arsaboo. Regularly updated (1,953★).
*   [Franck Nijhof (⭐2k)](https://github.com/frenck/home-assistant-config) - Home Assistant OS based, very different configuration structure compared to others (1,999★).
*   [Klaas Schoute (⭐223)](https://github.com/klaasnicolaas/Student-homeassistant-config) - Home Assistant OS based, Intel NUC, Ubuntu Server, Docker and regularly updated (223★).
*   [Ryan Warner](https://github.com/rwarner/Home-Assistant-Config) - Docker on Ubuntu HA Config, maintained since early HA. Highly documented and regularly updated (5★).

## Custom Integrations

*Integrations Home Assistant does not ship with out of the box, written by the community. Install them through HACS in a couple of clicks.*

### 🤖 AI & LLMs

*Wire Home Assistant up to a large language model and let it read your devices, build dashboards, write automations, or describe what your cameras see.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### 💡 Lighting

*Effects, schedules, and behaviour layers that sit on top of your lights.*

*   [Circadian Lighting (⭐882)](https://github.com/claytonjn/hass-circadian_lighting) - Slowly synchronizes your color-changing lights with the naturally occurring color temperature of the sky throughout the day (882★).

### 🌡️ Climate

*Smarter thermostats, comfort sensors, and HVAC integrations that go beyond what comes built in.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### ⚡ Energy & solar

*Pull your solar inverter, smart meter, home battery, or utility tariff into Home Assistant and feed the energy dashboard.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### 📹 Cameras & video

*Pair specific camera brands and video sources that Home Assistant does not support out of the box.*

*   [HASS Aarlo (⭐466)](https://github.com/twrecked/hass-aarlo) - Asynchronous Arlo integration. Similar to the Arlo web site; monitors events and states for all base stations, cameras and doorbells (466★).
*   [WebRTC Camera (⭐2.1k)](https://github.com/AlexxIT/WebRTC) - View RTSP streams from IP Cameras in real-time through WebRTC or MSE with Pan/Zoom controls (2,104★).

### 🚨 Security & alarm

*Turn Home Assistant into a fully-featured alarm system with arm and disarm flows, user codes, zones, and panic.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### 🔊 Voice & media playback

*Send commands to voice speakers and media players, or relay what they hear and play back into Home Assistant.*

*   [Spotcast (⭐807)](https://github.com/fondberg/spotcast) - Start Spotify playback on an idle Chromecast device as well as control Spotify connect devices (807★).

### 🚗 Cars & EV charging

*Track your car's battery, location, and charging state, or control where and when it plugs in.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### 📍 Presence & location

*Figure out who is home and where they are, often more accurately than the built-in device tracker.*

*   [iCloud3 (⭐835)](https://github.com/gcobb321/icloud3) - Improved version of the iCloud device tracker component with a lot of capabilities (835★).

### 🧹 Vacuums

*Control specific robot vacuums and surface their map data, beyond what comes built in.*

*   [Xiaomi Cloud Map Extractor (⭐1.4k)](https://github.com/PiotrMachowski/Home-Assistant-custom-components-Xiaomi-Cloud-Map-Extractor) - Presents a live view of a map for Xiaomi (Roborock/Viomi/Roidmi/Dreame) vacuums without a need for rooting (1,392★).

### 🔵 Bluetooth & BLE

*Pull data from sensors that broadcast over Bluetooth, or use Bluetooth itself for room-level presence detection.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### 🔋 Battery monitoring

*Keep an eye on the batteries in all your devices and get warned before they run flat.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### 🏷️ Vendor & brand

*Pull a specific manufacturer's devices into Home Assistant, often with more features or better local control than what comes built in.*

*   [SmartIR (⭐2.7k)](https://github.com/smartHomeHub/SmartIR) - Integrates devices using Broadlink IR (2,698★).
*   [Sonoff LAN (⭐3.2k)](https://github.com/AlexxIT/SonoffLAN) - Control Sonoff devices with eWeLink (original) firmware over LAN and/or Cloud (3,230★).

### 🛠️ Automation tooling

*Helpers that make automations easier to write, debug, and maintain.*

*   [The Watchman (⭐643)](https://github.com/dummylabs/thewatchman) - Keep track of missing entities and services in your config files (643★).

### 🏘️ Civic & household

*Local services that turn into sensors and calendars: garbage collection schedules, school holidays, traffic, weather alerts, and similar.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### 🔐 Network & authentication

*Sign in to Home Assistant with single sign-on, route through a tunnel, or pull network hardware into your dashboard.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### 🔗 Federation & multi-instance

*Link multiple Home Assistant instances together, share entities across homes, or relay between them.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### 📊 Logging & analytics

*Send Home Assistant data to external systems for long-term storage, richer dashboards, or analysis.*

*   [Elasticsearch (⭐164)](https://github.com/legrego/homeassistant-elasticsearch) - Publishes events to Elasticsearch (164★).

## Dashboard Cards

*Lovelace plugins that drop into your dashboard. Grouped roughly by what they do.*

### 🧱 Dashboard frameworks

*Full card collections that change the look and feel of your dashboards. Mushroom, Bubble Card, Floorplan, and similar all-in-one toolkits.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### 📐 Layout helpers

*Cards that change where and how other cards appear: stack, fold, show conditionally, restyle, or template.*

*   [Auto-Entities Card (⭐1.7k)](https://github.com/thomasloven/lovelace-auto-entities) - Dynamically adds entities: 🔮 Magic (1,747★).
*   [Card Modder (⭐1.7k)](https://github.com/thomasloven/lovelace-card-mod) - Style your Lovelace cards (1,692★).
*   [Restriction Card (⭐316)](https://github.com/iantrich/restriction-card) - A card to provide restrictions on Lovelace cards defined within (316★).
*   [Config Template Card (⭐547)](https://github.com/iantrich/config-template-card) - Allow using templates in Lovelace (547★).
*   [Button card (⭐2.4k)](https://github.com/custom-cards/button-card) - Highly customizable button for your entities (2,432★).
*   [Expander Card (⭐412)](https://github.com/Alia5/lovelace-expander-card) - Expandable and collapsible card to group and hide other cards behind a header (412★).

### 📈 Charts & graphs

*Visualise sensor data over time. Gauges, line graphs, bars, and Sankey diagrams.*

*   [Mini Graph Card (⭐3.8k)](https://github.com/kalkih/mini-graph-card) - A minimalistic sensor graph card (3,810★).
*   [Canvas Gauge Card (⭐216)](https://github.com/custom-cards/canvas-gauge-card) - Use awesome gauges from canvas-gauges.com (216★).
*   [Dual Gauge Card (⭐220)](https://github.com/custom-cards/dual-gauge-card) - Shows two gauges in one (220★).

### 📋 Status & info rows

*Compact rows that pack more information into entity-card style listings.*

*   [Slider Entity Row (⭐906)](https://github.com/thomasloven/lovelace-slider-entity-row) - Add a slider to adjust, e.g., the brightness of lights in lovelace entity cards (906★).

### ☀️ Weather cards

*Weather widgets with the look you actually want.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### 🎵 Media cards

*Better ways to control media players, with album art, queues, and per-room presence.*

*   [Mini Media Player (⭐1.7k)](https://github.com/kalkih/mini-media-player) - A minimalistic media player card (1,698★).

### 🌡️ Climate cards

*Replacement thermostat cards with a different look or feel.*

*   [Thermostat Card (⭐744)](https://github.com/ciotlosm/lovelace-thermostat-dark-card) - Thermostat control card that looks like a Nest Thermostat (744★).
*   [Simple Thermostat (⭐807)](https://github.com/nervetattoo/simple-thermostat) - A simpler and more flexible thermostat card (807★).

### ⚡ Energy cards

*Visualise solar production, grid imports, battery state, and consumption flow.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### 💡 Lighting cards

*Specialised controls for lights, color temperature, and effects.*

*   [RGB Light Card (⭐558)](https://github.com/bokub/rgb-light-card) - Colorful buttons to control your RGB Lights (558★).

### 🗺️ Maps & location

*Show a map of where your devices and people are, with history trails and custom overlays.*

*   [ha-map-card (⭐110)](https://github.com/nathan-gs/ha-map-card) - Leaflet-based map card with history trails, custom tile layers, and tap actions (110★).

### 📸 Camera cards

*Display camera streams the way you want them, with overlays, controls, event timelines, and pop-out viewers.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

### 🧹 Vacuum cards

*Show vacuum status, room maps, and start/stop controls in your dashboard.*

*   [Vacuum Map Card (⭐1.9k)](https://github.com/PiotrMachowski/lovelace-xiaomi-vacuum-map-card) - This card provides a user-friendly way to fully control Xiaomi (Roborock/Viomi/Dreame/Roidmi) and Neato (+ possibly other) vacuums (1,863★).
*   [Vacuum Card (⭐1.2k)](https://github.com/denysdovhan/vacuum-card) - A card for controlling a robot vacuum (1,199★).

### 📅 Calendar & feed

*Calendar views and rolling feeds of upcoming events.*

*   [Atomic Calendar Revive (⭐611)](https://github.com/totaldebug/atomic-calendar-revive) - Calendar card with advanced settings (611★).

### 📡 Remote control

*Virtual remotes for TVs, streamers, and AV gear.*

*   [LG WebOS Remote Control (⭐547)](https://github.com/madmicio/LG-WebOS-Remote-Control) - Remote Control for LG TV WebOS (547★).

### 🍃 Air quality

*Display readings from purifiers and air-quality sensors.*

*   [Purifier Card (⭐339)](https://github.com/denysdovhan/purifier-card) - A card for controlling air purifiers (339★).

### 🖥️ Kiosk & wallpanel

*Hide the chrome, run full-screen, or turn an old tablet on the wall into a dedicated touch panel.*

*   [Suggest one (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/issues/new/choose) - Have a community resource that fits here? Open an issue to propose it.

## Dashboards

*Frameworks that replace or extend the default Home Assistant dashboard with a different look and feel.*

*   [Dwains Dashboard (⭐2k)](https://github.com/dwainscheeren/dwains-lovelace-dashboard) - A fully auto-generating dashboard for desktop, tablet and mobile (2,033★).
*   [Mushroom Strategy (⭐640)](https://github.com/DigiLive/mushroom-strategy) - A strategy that automatically generates a dashboard using Mushroom cards (640★).

## Themes

*It is all about the looks, apply some style.*

*   [Midnight](https://community.home-assistant.io/t/midnight-theme/28598?u=frenck) - A dark theme by Marcel Hoffs.
*   [Dark Cyan](https://community.home-assistant.io/t/dark-cyan-theme/28594?u=frenck) - A dark theme with cyan accents by Ryoen Deprouw.
*   [Grey Night](https://community.home-assistant.io/t/grey-night-theme/30848?u=frenck) - A dark theme with grey accents by ksya.
*   [Dark Red](https://community.home-assistant.io/t/dark-red-theme/28592?u=frenck) - A dark theme with red accents by Ryoen Deprouw.
*   [Halloween](https://community.home-assistant.io/t/halloween-theme/30872?u=frenck) - Pumpkins colored by Mahasri Kalavala.
*   [Black and Green](https://community.home-assistant.io/t/black-and-green-theme/28602?u=frenck) - A dark theme with pale green accents by GreenTurtwig.
*   [Vintage](https://community.home-assistant.io/t/vintage-theme/42806?u=frenck) - Give your frontend a vintage look with this theme by Anup Surendran.
*   [Carbon Green](https://community.home-assistant.io/t/share-your-themes/22018/95?u=frenck) - Light carbon theme with green accents by Reua.
*   [Slate (⭐136)](https://github.com/seangreen2/slate_theme) - A dark theme close to the vanilla look (136★).
*   [Synthwave (⭐199)](https://github.com/bbbenji/synthwave-hass) - A theme influenced by the cover artwork of modern Synthwave bands (199★).

## Icon packs

*Custom icon sets you install through HACS to replace or extend the default icons across your dashboards.*

*   [Font Awesome Icons (⭐338)](https://github.com/thomasloven/hass-fontawesome) - Use the free icons from Font Awesome in your frontend (338★).
*   [Hass Hue Icons (⭐376)](https://github.com/arallsopp/hass-hue-icons) - Additional Philips Hue bulbs and fixtures icons (376★).
*   [simpleicons (⭐166)](https://github.com/vigonotion/hass-simpleicons) - Use the free icons from the simpleicons set (166★).

## Apps

*Need a database, a reverse proxy, an MQTT broker (the messaging service many smart-home devices use), or another tool running alongside Home Assistant? Apps, formerly called Add-ons, let you install them straight into Home Assistant OS. No Docker, no separate server, no command line required.*

### 🛡️ Official Apps

*Created and maintained by the Home Assistant team.*

*   [DuckDNS (⭐2.2k)](https://github.com/home-assistant/hassio-addons/blob/master/duckdns/DOCS.md) - Updates your Duck DNS IP address and generates SSL using Let's Encrypt.
*   [File editor (⭐2.2k)](https://github.com/home-assistant/hassio-addons/blob/master/configurator/DOCS.md) - Browser-based configuration file editor.
*   [Mosquitto (⭐2.2k)](https://github.com/home-assistant/hassio-addons/blob/master/mosquitto/DOCS.md) - Fast and reliable MQTT broker.
*   [Terminal & SSH (⭐2.2k)](https://github.com/home-assistant/hassio-addons/blob/master/ssh/DOCS.md) - Allows logging in remotely using a web terminal or SSH client.
*   [Samba (⭐2.2k)](https://github.com/home-assistant/hassio-addons/blob/master/samba/DOCS.md) - Access your configuration files using Windows network shares.
*   [NGINX SSL proxy (⭐2.2k)](https://github.com/home-assistant/hassio-addons/blob/master/nginx_proxy/DOCS.md) - Reverse proxy with SSL termination.
*   [deCONZ (⭐2.2k)](https://github.com/home-assistant/hassio-addons/blob/master/deconz/DOCS.md) - Control a ZigBee network using ConBee or RaspBee hardware by Dresden Elektronik.
*   [Let's Encrypt (⭐2.2k)](https://github.com/home-assistant/hassio-addons/blob/master/letsencrypt/DOCS.md) - Get a free SSL certificate from Let's Encrypt; an open and automated certificate authority (CA).
*   [MariaDB (⭐2.2k)](https://github.com/home-assistant/hassio-addons/blob/master/mariadb/DOCS.md) - An open source relational database (fork of MySQL).

### 📦 Third Party Apps

*Anyone can create an app, the following are created by the community.*

*   [SSH & Web Terminal (⭐494)](https://github.com/hassio-addons/app-ssh) - SSH and Web-based terminal with tons of pre-loaded useful tools (494★).
*   [UniFi Controller (⭐367)](https://github.com/hassio-addons/app-unifi) - The UniFi Controller allows you to manage your UniFi network using a web browser (367★).
*   [Node-RED (⭐635)](https://github.com/hassio-addons/app-node-red) - Flow-based programming for the Internet of Things (635★).
*   [Plex Media Server (⭐187)](https://github.com/hassio-addons/app-plex) - Your recorded media beautifully organized and ready to stream (187★).
*   [InfluxDB (⭐194)](https://github.com/hassio-addons/addon-influxdb) - Scalable datastore for metrics, events, and real-time analytics (194★).
*   [Grafana (⭐275)](https://github.com/hassio-addons/addon-grafana) - Open platform for beautiful analytics and monitoring (275★).
*   [Tor (⭐62)](https://github.com/hassio-addons/app-tor) - Protect your privacy and access your instance via Tor (62★).
*   [Spotify Connect (⭐252)](https://github.com/hassio-addons/app-spotify-connect) - Stream music from Spotify directly to your Home Assistant device (252★).
*   [zigbee2mqtt (⭐15k)](https://github.com/Koenkk/zigbee2mqtt) - Zigbee to MQTT bridge, get rid of your proprietary Zigbee bridges (15,106★).
*   [AppDaemon (⭐955)](https://github.com/AppDaemon/appdaemon) - A loosely coupled, multi-threaded, sandboxed Python execution environment for writing automation apps (955★).
*   [TasmoAdmin (⭐253)](https://github.com/hassio-addons/addon-tasmoadmin) - Centrally manage all your Sonoff-Tasmota devices (253★).
*   [Aircast (⭐393)](https://github.com/hassio-addons/app-aircast) - AirPlay capabilities for your Chromecast players (394★).
*   [AirSonos (⭐120)](https://github.com/hassio-addons/app-airsonos) - AirPlay capabilities for your Sonos players (120★).
*   [Log Viewer (⭐94)](https://github.com/hassio-addons/addon-log-viewer) - Browser-based live log viewing utility (94★).
*   [Tautulli (⭐46)](https://github.com/hassio-addons/addon-tautulli) - Monitor and get statistics from your Plex server (46★).
*   [motionEye (⭐331)](https://github.com/hassio-addons/addon-motioneye) - Simple, elegant and feature-rich CCTV/NVR for your cameras (331★).
*   [JupyterLab (⭐68)](https://github.com/hassio-addons/addon-jupyterlab) - Create documents containing live code, equations, visualizations, and explanatory text (68★).
*   [Glances (⭐184)](https://github.com/hassio-addons/app-glances) - A cross-platform system monitoring tool written in Python (184★).
*   [AdGuard Home (⭐511)](https://github.com/hassio-addons/app-adguard-home) - A network-wide ad-and-tracker blocking DNS server with parental control (511★).
*   [Traccar](https://github.com/hassio-addons/addon-traccar) - Modern GPS tracking platform (158★).
*   [Hass.io Google Drive Backup (⭐3.5k)](https://github.com/sabeechen/hassio-google-drive-backup) - A complete and easy-to-configure solution for backing up to Google Drive (3,537★).
*   [Grocy (⭐429)](https://github.com/hassio-addons/app-grocy) - ERP beyond your fridge! A groceries & household management solution for your home (429★).
*   [CrowdSec (⭐94)](https://github.com/crowdsecurity/home-assistant-addons) - A next-gen collaborative IPS/IDS to protect you from intrusion (94★).

## DIY

*Some of the best smart-home gadgets do not exist as products you can buy, but other people have figured out how to build them. The projects below cover everything from soldering your own multi-sensor to repurposing a discontinued device. Most are weekend projects with parts that cost less than a coffee run.*

### 🧩 Standalone projects

*   [ESPHome](https://esphome.io/) - Program ESP8266 boards and ESP32 boards using YAML.
*   [Tasmota (⭐24k)](https://github.com/arendst/Tasmota) - Firmware for ESP8266 boards and devices (24,346★).
*   [Sonoff NSPanel (⭐986)](https://github.com/joBr99/nspanel-lovelace-ui) - Custom firmware for Sonoff NSPanel touchscreens with a Lovelace-style UI (986★).
*   [CODESYS V3 Home Automation (⭐142)](https://github.com/MichielVanwelsenaere/HomeAutomation.CoDeSys3) - PLC home-automation software that communicates over MQTT for wired automation setups (142★).

### 🌉 DIY Gateways

*   [OpenMQTTGateway (⭐4k)](https://github.com/1technophile/OpenMQTTGateway) - A flexible MQTT gateway for IR, RF, BLE, MiFlora, SMS, and many sensors (4,010★).
*   [esp8266 Milight Hub (⭐1k)](https://github.com/sidoh/esp8266_milight_hub) - Alternative hub for Milight/LimitlessLED devices that uses MQTT (1,027★).

### 🔨 DIY Projects

*   [HA SwitchPlate](https://community.home-assistant.io/t/ha-switchplate-diy-lcd-touchscreen-wall-switch-replacement/25464?u=frenck) - LCD Touchscreen wall switch replacement.
*   [$10 WiFi RGB Bulb](https://community.home-assistant.io/t/how-to-inexpensive-10-us-wifi-rgb-bulb-that-works-with-home-assistant/14735?u=frenck) - An inexpensive RGB bulb that works on WiFi.
*   [433mhz/IR Bidirectional Gateway](https://community.home-assistant.io/t/433mhz-infrared-ir-to-and-from-mqtt-on-esp8266/6779?u=frenck) - Bidirectional with IR and 433mhz using ESP8266 and MQTT.
*   [esp8266MQTTBlinds](https://community.home-assistant.io/t/esp8266-window-blinds-mqtt/14863?u=frenck) - Automate your window blinds using an ESP8266, a servo and MQTT.
*   [Home Assistant's Hackster.io](https://www.hackster.io/home-assistant?f=1#_=_) - A Hackster channel with multiple DIY projects.
*   [Bed Presence Detection](https://selfhostedhome.com/diy-bed-presence-detection-home-assistant/) - ESP8266 based Bed Presence Detection.
*   [QuinLED](https://quinled.info/) - DIY Wi-Fi LED dimmers and controllers using ESP32 boards.

## Tools & Utilities

*Helpers, daemons, and developer tools that sit alongside Home Assistant rather than inside it. Useful for editing your config, debugging your data, sending device data over MQTT, or wiring HA into a wider workflow.*

*   [HASS Configurator (⭐335)](https://github.com/danielperna84/hass-configurator) - Browser-based configuration file editor (335★).
*   [HA-Dockermon (⭐291)](https://github.com/philhawthorne/ha-dockermon) - A Node.js service for RESTful switches to control Docker containers (291★).
*   [Home Assistant Device Database](https://www.hadevices.com/) - Database of supported/confirmed working devices.
*   [Jinja Scripts for Curious Minds (⭐273)](https://github.com/skalavala/mysmarthome/tree/master/jinja_helpers) - Bunch of Jinja2 scripts helping you to understand it better.
*   [GitLab CI/CD](https://about.gitlab.com/2018/08/02/using-the-gitlab-ci-slash-cd-for-smart-home-configuration-management/) - How to simplify your smart home configuration with GitLab CI/CD.
*   [Monitor (⭐2.1k)](https://github.com/andrewjfreyer/monitor) - Distributed advertisement-based BTLE presence detection reported via MQTT (2,101★).
*   [HASS-data-detective (⭐204)](https://github.com/robmarkcole/HASS-data-detective) - Explore and analyse your database data (204★).
*   [ADB Intents](https://gist.github.com/mcfrojd/9e6875e1db5c089b1e3ddeb7dba0f304) - List of ADB intents to control Android Devices.
*   [Home Assistant Config Helper for VSCode](https://marketplace.visualstudio.com/items?itemName=keesschollaart.vscode-home-assistant) - Visual Studio Code Extension that provides auto-completion, config validation and snippets when editing your configuration.
*   [Mi Flora via MQTT daemon (⭐624)](https://github.com/ThomDietrich/miflora-mqtt-daemon) - Collect and transfer Xiaomi Mi Flora plant sensor data via MQTT (624★).
*   [Home Assistant Taskbar Menu (⭐342)](https://github.com/PiotrMachowski/Home-Assistant-Taskbar-Menu) - A client for Windows that can display Lovelace views, control entities and show persistent notifications (342★).

## Online Resources

*Home Assistant has a thriving community of bloggers, YouTubers, podcasters, and people who love sharing what they have built. The folks below are some of the regular voices worth following, especially when something new ships and you want a hands-on take before deciding whether to dig in yourself.*

### ✍️ Blogs

*   [DIY Futurism](https://diyfuturism.com/) - Brad posts articles with great instructions for new users.
*   [Smart Home Hobby](https://smarthomehobby.com/) - Features budget friendly guides and information.
*   [Self Hosted Home](https://selfhostedhome.com/) - Articles on DIY home automation projects and self hosted services.
*   [Tinkering with Home Automation](https://blog.ceard.tech/) - Tinkerer's blog and guides.
*   [HomeTechHacker](https://HomeTechHacker.com) - DIY Smarthome guides, reviews, and advice.
*   [Intermittent Technology](https://blog.quindorian.org) - Quindor's personal blog for pasting random (mostly technology related) things.
*   [SmartHomeScene](https://smarthomescene.com/) - Beginner-friendly tutorials, smart-home device reviews, and DIY automation projects.

### 📺 YouTube Channels

*Sit back, relax, watch, and learn.*

*   [Home Assistant](https://www.youtube.com/channel/UCbX3YkedQunLt7EQAdVxh7w) - Official YouTube Channel where new launches and live streams are held.
*   [BurnsHA](https://www.youtube.com/channel/UCSKQutOXuNLvFetrKuwudpg) - Great informational and tutorial videos.
*   [The Hook Up](https://www.youtube.com/channel/UC2gyzKcHbYfqoXA5xbyGXtQ) - Tutorials and more, also has videos on home automation in general.
*   [JuanMTech](https://www.youtube.com/juanmtech) - Easy to follow how-to videos, product reviews and more.
*   [vCloudInfo](https://www.youtube.com/vCloudInfo) - Publishes videos based on his home and GitHub repository.
*   [digiblurDIY](https://www.youtube.com/channel/UC5ZdPKE2ckcBhljTc2R_qNA) - Tutorials on hardware projects and Tasmota automations.
*   [Intermit.Tech](https://www.youtube.com/channel/UCv7UOhZ2XuPwm9SN5oJsCjA) - Tutorials & reviews: Camera's, Home Networking, ESP8266 boards, Node-RED.
*   [BeardedTinker](https://www.youtube.com/channel/UCuqokNoK8ZFNQdXxvlE129g) - Tutorials & 3D printing.
*   [Smart Home Junkie](https://www.youtube.com/@smarthomejunkie) - How-to videos and tutorials for starters and advanced users.
*   [Everything Smart Home](https://www.youtube.com/c/EverythingSmartHome) - Focuses on Smart Home, Home Automation, general tech reviews, guides, and step-by-step DIY projects.
*   [Warner Discovers](https://www.youtube.com/c/WarnerDiscovers) - Tech reviews, DIY installs, smart home gear, and solar DIY.

### 🎙️ Podcasts

*Get inspired, while commuting, doing your morning routine, or at the gym!*

*   [Home Assistant Podcast](https://hasspodcast.io) - Biweekly podcast with the latest news and interesting guests.

### 📱 Social

*Follow along on social media. The list still leans on X (formerly Twitter); Bluesky and Mastodon entries land in a follow-up.*

*   [@home\_assistant](https://twitter.com/home_assistant) - Open source home automation that puts local control and privacy first.
*   [@hass\_devs](https://twitter.com/hass_devs) - Latest news on the development of Home Assistant for contributors.
*   [@balloob](https://twitter.com/balloob) - Founder of the Home Assistant project.
*   [@pvizeli](https://twitter.com/pvizeli) - Core developer and creator of the Home Assistant Supervisor.
*   [@frenck](https://twitter.com/frenck) - Creator of this Awesome list and maintainer of the Home Assistant Community Apps project.
*   [@ccostan](https://twitter.com/ccostan) - Blogger of all things Tech. Smart Home, #IOT & other Geeky subjects.
*   [@HomeTechHacker](https://twitter.com/HomeTechHacker) - Guy friends call when #tech happens. Tweet 25-50x/week about #smarthome, #homenetwork, #cybersecurity, #Linux, #gadgets, and #life.
*   [@hassioaddons](https://twitter.com/hassioaddons) - For all community app news and updates.
*   [@Dr\_Zzs](https://twitter.com/Dr_Zzs) - Great how-to videos and also streams live.

## Alternative Home Automation Software

*Home Assistant is not the only home-automation platform out there. If you want to compare, or if you have specific needs HA does not cover, the projects below are the most active alternatives. Some are commercial, some are open source, and a few solve very different problems.*

*   [openHAB](https://github.com/openhab) - Java-based and aims at being a universal integration platform.
*   [Domoticz (⭐3.7k)](https://github.com/domoticz/domoticz) - A lightweight Home Automation System (3,751★).
*   [Gladys (⭐3.1k)](https://github.com/GladysAssistant/Gladys) - Open source program which runs on your Raspberry Pi (3,054★).
*   [SmartThings](https://www.smartthings.com/) - Commercial home automation hub by Samsung.

## Other Awesome Lists

*Like this list, but for adjacent topics? The lists below cover broader smart-home categories, specific protocols, and self-hosted software in general. They are good places to look when something does not fit Home Assistant directly but might solve part of your puzzle.*

*   [awesome-iot (⭐3.9k)](https://github.com/HQarroum/awesome-iot) - Curated list of awesome Internet of Things projects and resources (3,928★).
*   [awesome-mqtt (⭐2.3k)](https://github.com/awesome-mqtt/awesome-mqtt#readme) - Curated list of MQTT related stuff (2,332★).
*   [awesome-selfhosted (⭐289k)](https://github.com/awesome-selfhosted/awesome-selfhosted) - Curated list of awesome self hosted software (290,872★).

## Contributing

This awesome list is an active open-source project and is always open to
people who want to contribute to it. We have set up a separate document
containing our [Contribution Guidelines (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/blob/main/.github/CONTRIBUTING.md).

The original setup of this awesome list is by [Franck Nijhof](https://twitter.com/frenck).

For a full list of all authors and contributors, check the
[contributor's page (⭐7.6k)](https://github.com/frenck/awesome-home-assistant/graphs/contributors).

Thank you for being involved! 😍

## Trademark Legal Notice

Awesome Home Assistant is an independent, community-curated index. It is not
created, endorsed, sponsored by, or affiliated with
[Home Assistant](https://www.home-assistant.io) or the
[Open Home Foundation](https://www.openhomefoundation.org). "Home Assistant"
and the Home Assistant logo are trademarks of the Open Home Foundation.

All other product names, logos, brands, trademarks, and registered trademarks
referenced in this list are the property of their respective owners.
References to specific manufacturers, products, integrations, add-ons,
services, and community projects are for identification purposes only and do
not imply endorsement by their owners.

The contents of this list are licensed under [Creative Commons Attribution
4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC-BY-4.0).
See [LICENSE.md](https://github.com/frenck/awesome-home-assistant/blob/main/README.md/LICENSE.md) for the full text.

