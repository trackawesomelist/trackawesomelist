# Awesome Honeypots Overview

an awesome list of honeypot resources

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/paralax/awesome-honeypots/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 paralax/awesome-honeypots](https://github.com/paralax/awesome-honeypots) · ⭐ 7.6K · 🏷️ Security

[ [Daily](/content/paralax/awesome-honeypots/README.md) / [Weekly](/content/paralax/awesome-honeypots/week/README.md) / Overview ]

---

# Awesome Honeypots [![Awesome Honeypots](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome honeypots, plus related components and much more, divided into categories such as Web, services, and others, with a focus on free and open source projects.

There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](https://github.com/paralax/awesome-honeypots/blob/master/README.md/CONTRIBUTING.md).

Discover more awesome lists at [sindresorhus/awesome (⭐283k)](https://github.com/sindresorhus/awesome).

# Contents

*   [Awesome Honeypots ![Awesome Honeypots](https://github.com/sindresorhus/awesome)](#awesome-honeypots-)
*   [Contents](#contents)
    *   [Related Lists](#related-lists)
    *   [Honeypots](#honeypots)
    *   [Honeyd Tools](#honeyd-tools)
    *   [Network and Artifact Analysis](#network-and-artifact-analysis)
    *   [Data Tools](#data-tools)
    *   [Guides](#guides)

## Related Lists

*   [awesome-pcaptools (⭐2.9k)](https://github.com/caesar0301/awesome-pcaptools) - Useful in network traffic analysis.
*   [awesome-malware-analysis (⭐11k)](https://github.com/rshipp/awesome-malware-analysis) - Some overlap here for artifact analysis.

## Honeypots

*   Database Honeypots

    *   [Delilah (⭐18)](https://github.com/SecurityTW/delilah) - Elasticsearch Honeypot written in Python (originally from Novetta).
    *   [ESPot (⭐25)](https://github.com/mycert/ESPot) - Elasticsearch honeypot written in NodeJS, to capture every attempts to exploit CVE-2014-3120.
    *   [ElasticPot](https://gitlab.com/bontchev/elasticpot) - An Elasticsearch Honeypot.
    *   [Elastic honey (⭐177)](https://github.com/jordan-wright/elastichoney) - Simple Elasticsearch Honeypot.
    *   [MongoDB-HoneyProxy (⭐86)](https://github.com/Plazmaz/MongoDB-HoneyProxy) - MongoDB honeypot proxy.
    *   [NoSQLpot (⭐101)](https://github.com/torque59/nosqlpot) - Honeypot framework built on a NoSQL-style database.
    *   [mysql-honeypotd (⭐27)](https://github.com/sjinks/mysql-honeypotd) - Low interaction MySQL honeypot written in C.
    *   [MysqlPot (⭐20)](https://github.com/schmalle/MysqlPot) - MySQL honeypot, still very early stage.
    *   [pghoney (⭐16)](https://github.com/betheroot/pghoney) - Low-interaction Postgres Honeypot.
    *   [sticky\_elephant (⭐7)](https://github.com/betheroot/sticky_elephant) - Medium interaction postgresql honeypot.
    *   [RedisHoneyPot (⭐13)](https://github.com/cypwnpwnsocute/RedisHoneyPot) - High Interaction Honeypot Solution for Redis protocol.

*   Web honeypots

    *   [Express honeypot (⭐11)](https://github.com/christophe77/express-honeypot) - RFI & LFI honeypot using nodeJS and express.
    *   [EoHoneypotBundle (⭐32)](https://github.com/eymengunay/EoHoneypotBundle) - Honeypot type for Symfony2 forms.
    *   [Glastopf (⭐516)](https://github.com/mushorg/glastopf) - Web Application Honeypot.
    *   [Google Hack Honeypot](http://ghh.sourceforge.net) - Designed to provide reconnaissance against attackers that use search engines as a hacking tool against your resources.
    *   [HellPot (⭐229)](https://github.com/yunginnanet/HellPot) - Honeypot that tries to crash the bots and clients that visit it's location.
    *   [Laravel Application Honeypot (⭐429)](https://github.com/msurguy/Honeypot) - Simple spam prevention package for Laravel applications.
    *   [Nodepot (⭐41)](https://github.com/schmalle/Nodepot) - NodeJS web application honeypot.
    *   [PasitheaHoneypot (⭐1)](https://github.com/Marist-Innovation-Lab/PasitheaHoneypot) - RestAPI honeypot.
    *   [Servletpot (⭐12)](https://github.com/schmalle/servletpot) - Web application Honeypot.
    *   [Shadow Daemon](https://shadowd.zecure.org/overview/introduction/) - Modular Web Application Firewall / High-Interaction Honeypot for PHP, Perl, and Python apps.
    *   [StrutsHoneypot (⭐71)](https://github.com/Cymmetria/StrutsHoneypot) - Struts Apache 2 based honeypot as well as a detection module for Apache 2 servers.
    *   [WebTrap (⭐55)](https://github.com/IllusiveNetworks-Labs/WebTrap) - Designed to create deceptive webpages to deceive and redirect attackers away from real websites.
    *   [basic-auth-pot (bap) (⭐43)](https://github.com/bjeborn/basic-auth-pot) - HTTP Basic Authentication honeypot.
    *   [bwpot (⭐25)](https://github.com/graneed/bwpot) - Breakable Web applications honeyPot.
    *   [django-admin-honeypot (⭐977)](https://github.com/dmpayton/django-admin-honeypot) - Fake Django admin login screen to notify admins of attempted unauthorized access.
    *   [drupo (⭐57)](https://github.com/d1str0/drupot) - Drupal Honeypot.
    *   [galah (⭐21)](https://github.com/0x4D31/galah) - an LLM-powered web honeypot using the OpenAI API.
    *   [honeyhttpd (⭐34)](https://github.com/bocajspear1/honeyhttpd) - Python-based web server honeypot builder.
    *   [honeyup (⭐24)](https://github.com/LogoiLab/honeyup) - An uploader honeypot designed to look like poor website security.
    *   [owa-honeypot (⭐21)](https://github.com/joda32/owa-honeypot) - A basic flask based Outlook Web Honey pot.
    *   [phpmyadmin\_honeypot (⭐64)](https://github.com/gfoss/phpmyadmin_honeypot) - Simple and effective phpMyAdmin honeypot.
    *   [shockpot](https://github.com/threatstream/shockpot) - WebApp Honeypot for detecting Shell Shock exploit attempts.
    *   [smart-honeypot (⭐16)](https://github.com/freak3dot/smart-honeypot) - PHP Script demonstrating a smart honey pot.
    *   Snare/Tanner - successors to Glastopf
        *   [Snare (⭐416)](https://github.com/mushorg/snare) - Super Next generation Advanced Reactive honeypot.
        *   [Tanner (⭐198)](https://github.com/mushorg/tanner) - Evaluating SNARE events.
    *   [stack-honeypot (⭐22)](https://github.com/CHH/stack-honeypot) - Inserts a trap for spam bots into responses.
    *   [tomcat-manager-honeypot (⭐10)](https://github.com/helospark/tomcat-manager-honeypot) - Honeypot that mimics Tomcat manager endpoints. Logs requests and saves attacker's WAR file for later study
    *   WordPress honeypots
        *   [HonnyPotter (⭐27)](https://github.com/MartinIngesen/HonnyPotter) - WordPress login honeypot for collection and analysis of failed login attempts.
        *   [HoneyPress (⭐2)](https://github.com/kungfuguapo/HoneyPress) - Python based WordPress honeypot in a Docker container.
        *   [wp-smart-honeypot (⭐26)](https://github.com/freak3dot/wp-smart-honeypot) - WordPress plugin to reduce comment spam with a smarter honeypot.
        *   [wordpot (⭐171)](https://github.com/gbrindisi/wordpot) - WordPress Honeypot.
    *   [Python-Honeypot (⭐389)](https://github.com/OWASP/Python-Honeypot) - OWASP Honeypot, Automated Deception Framework.

*   Service Honeypots
    *   [ADBHoney (⭐158)](https://github.com/huuck/ADBHoney) - Low interaction honeypot that simulates an Android device running Android Debug Bridge (ADB) server process.
    *   [AMTHoneypot (⭐16)](https://github.com/packetflare/amthoneypot) - Honeypot for Intel's AMT Firmware Vulnerability CVE-2017-5689.
    *   [ddospot (⭐34)](https://github.com/aelth/ddospot) - NTP, DNS, SSDP, Chargen and generic UDP-based amplification DDoS honeypot.
    *   [dionaea (⭐663)](https://github.com/DinoTools/dionaea) - Home of the dionaea honeypot.
    *   [dhp (⭐23)](https://github.com/ciscocsirt/dhp) - Simple Docker Honeypot server emulating small snippets of the Docker HTTP API.
    *   [DolosHoneypot (⭐1)](https://github.com/Marist-Innovation-Lab/DolosHoneypot) - SDN (software defined networking) honeypot.
    *   [Ensnare (⭐66)](https://github.com/ahoernecke/ensnare) - Easy to deploy Ruby honeypot.
    *   [Helix (⭐26)](https://github.com/Zeerg/helix-honeypot) - K8s API Honeypot with Active Defense Capabilities.
    *   [honeycomb\_plugins (⭐26)](https://github.com/Cymmetria/honeycomb_plugins) - Plugin repository for Honeycomb, the honeypot framework by Cymmetria.
    *   [honeyntp (⭐52)](https://github.com/fygrave/honeyntp) - NTP logger/honeypot.
    *   [honeypot-camera (⭐50)](https://github.com/alexbredo/honeypot-camera) - Observation camera honeypot.
    *   [honeypot-ftp (⭐26)](https://github.com/alexbredo/honeypot-ftp) - FTP Honeypot.
    *   [honeypots (⭐509)](https://github.com/qeeqbox/honeypots) - 25 different honeypots in a single pypi package! (dns, ftp, httpproxy, http, https, imap, mysql, pop3, postgres, redis, smb, smtp, socks5, ssh, telnet, vnc, mssql, elastic, ldap, ntp, memcache, snmp, oracle, sip and irc).
    *   [honeytrap (⭐1.2k)](https://github.com/honeytrap/honeytrap) - Advanced Honeypot framework written in Go that can be connected with other honeypot software.
    *   [HoneyPy (⭐445)](https://github.com/foospidy/HoneyPy) - Low interaction honeypot.
    *   [Honeygrove (⭐19)](https://github.com/UHH-ISS/honeygrove) - Multi-purpose modular honeypot based on Twisted.
    *   [Honeyport (⭐40)](https://github.com/securitygeneration/Honeyport) - Simple honeyport written in Bash and Python.
    *   [Honeyprint (⭐18)](https://github.com/glaslos/honeyprint) - Printer honeypot.
    *   [Lyrebird](https://hub.docker.com/r/lyrebird/honeypot-base/) - Modern high-interaction honeypot framework.
    *   [MICROS honeypot (⭐13)](https://github.com/Cymmetria/micros_honeypot) - Low interaction honeypot to detect CVE-2018-2636 in the Oracle Hospitality Simphony component of Oracle Hospitality Applications (MICROS).
    *   [node-ftp-honeypot (⭐2)](https://github.com/christophe77/node-ftp-honeypot) - FTP server honeypot in JS.
    *   [pyrdp (⭐1.4k)](https://github.com/gosecure/pyrdp) - RDP man-in-the-middle and library for Python 3 with the ability to watch connections live or after the fact.
    *   [rdppot (⭐59)](https://github.com/kryptoslogic/rdppot) - RDP honeypot
    *   [RDPy (⭐1.6k)](https://github.com/citronneur/rdpy) - Microsoft Remote Desktop Protocol (RDP) honeypot implemented in Python.
    *   [SMB Honeypot (⭐43)](https://github.com/r0hi7/HoneySMB) - High interaction SMB service honeypot capable of capturing wannacry-like Malware.
    *   [Tom's Honeypot (⭐25)](https://github.com/inguardians/toms_honeypot) - Low interaction Python honeypot.
    *   [troje (⭐45)](https://github.com/dutchcoders/troje/) - Honeypot that runs each connection with the service within a separate LXC container.
    *   [WebLogic honeypot (⭐31)](https://github.com/Cymmetria/weblogic_honeypot) - Low interaction honeypot to detect CVE-2017-10271 in the Oracle WebLogic Server component of Oracle Fusion Middleware.
    *   [WhiteFace Honeypot (⭐4)](https://github.com/csirtgadgets/csirtg-honeypot) - Twisted based honeypot for WhiteFace.

*   Distributed Honeypots

    *   [DemonHunter (⭐55)](https://github.com/RevengeComing/DemonHunter) - Low interaction honeypot server.

*   Anti-honeypot stuff

    *   [canarytokendetector (⭐7)](https://github.com/referefref/canarytokendetector) - Tool for detection and nullification of Thinkst CanaryTokens
    *   [honeydet (⭐14)](https://github.com/referefref/honeydet) - Signature based honeypot detector tool written in Golang
    *   [kippo\_detect (⭐54)](https://github.com/andrew-morris/kippo_detect) - Offensive component that detects the presence of the kippo honeypot.

*   ICS/SCADA honeypots

    *   [Conpot (⭐1.1k)](https://github.com/mushorg/conpot) - ICS/SCADA honeypot.
    *   [GasPot (⭐121)](https://github.com/sjhilt/GasPot) - Veeder Root Gaurdian AST, common in the oil and gas industry.
    *   [SCADA honeynet](http://scadahoneynet.sourceforge.net) - Building Honeypots for Industrial Networks.
    *   [gridpot (⭐50)](https://github.com/sk4ld/gridpot) - Open source tools for realistic-behaving electric grid honeynets.
    *   [scada-honeynet](http://www.digitalbond.com/blog/2007/07/24/scada-honeynet-article-in-infragard-publication/) - Mimics many of the services from a popular PLC and better helps SCADA researchers understand potential risks of exposed control system devices.

*   Other/random

    *   [CitrixHoneypot (⭐115)](https://github.com/MalwareTech/CitrixHoneypot) - Detect and log CVE-2019-19781 scan and exploitation attempts.
    *   [Damn Simple Honeypot (DSHP) (⭐14)](https://github.com/naorlivne/dshp) - Honeypot framework with pluggable handlers.
    *   [dicompot (⭐19)](https://github.com/nsmfoo/dicompot) - DICOM Honeypot.
    *   [IPP Honey](https://gitlab.com/bontchev/ipphoney) - A honeypot for the Internet Printing Protocol.
    *   [Log4Pot (⭐89)](https://github.com/thomaspatzke/Log4Pot) - A honeypot for the Log4Shell vulnerability (CVE-2021-44228).
    *   [Masscanned (⭐88)](https://github.com/ivre/masscanned) - Let's be scanned. A low-interaction honeypot focused on network scanners and bots. It integrates very well with IVRE to build a self-hosted alternative to GreyNoise.
    *   [medpot (⭐20)](https://github.com/schmalle/medpot) -  HL7 / FHIR honeypot.
    *   [NOVA (⭐72)](https://github.com/DataSoft/Nova) - Uses honeypots as detectors, looks like a complete system.
    *   [OpenFlow Honeypot (OFPot) (⭐22)](https://github.com/upa/ofpot) - Redirects traffic for unused IPs to a honeypot, built on POX.
    *   [OpenCanary (⭐1.9k)](https://github.com/thinkst/opencanary) - Modular and decentralised honeypot daemon that runs several canary versions of services that alerts when a service is (ab)used.
    *   [ciscoasa\_honeypot (⭐50)](https://github.com/cymmetria/ciscoasa_honeypot) A low interaction honeypot for the Cisco ASA component capable of detecting CVE-2018-0101, a DoS and remote code execution vulnerability.
    *   [miniprint (⭐197)](https://github.com/sa7mon/miniprint) - A medium interaction printer honeypot.

*   Botnet C2 tools

    *   [Hale (⭐182)](https://github.com/pjlantz/Hale) - Botnet command and control monitor.
    *   [dnsMole](https://code.google.com/archive/p/dns-mole/) - Analyses DNS traffic and potentionaly detect botnet command and control server activity, along with infected hosts.

*   IPv6 attack detection tool

    *   [ipv6-attack-detector (⭐36)](https://github.com/mzweilin/ipv6-attack-detector/) - Google Summer of Code 2012 project, supported by The Honeynet Project organization.

*   Dynamic code instrumentation toolkit

    *   [Frida](https://www.frida.re) - Inject JavaScript to explore native apps on Windows, Mac, Linux, iOS and Android.

*   Tool to convert website to server honeypots

    *   [HIHAT](http://hihat.sourceforge.net/) - Transform arbitrary PHP applications into web-based high-interaction Honeypots.

*   Malware collector

    *   [Kippo-Malware](https://bruteforcelab.com/kippo-malware) - Python script that will download all malicious files stored as URLs in a Kippo SSH honeypot database.

*   Distributed sensor deployment

    *   [Community Honey Network](https://communityhoneynetwork.readthedocs.io/en/stable/) - CHN aims to make deployments honeypots and honeypot management tools easy and flexible. The default deployment method uses Docker Compose and Docker to deploy with a few simple commands.
    *   [Modern Honey Network](https://github.com/threatstream/mhn) - Multi-snort and honeypot sensor management, uses a network of VMs, small footprint SNORT installations, stealthy dionaeas, and a centralized server for management.

*   Network Analysis Tool

    *   [Tracexploit](https://code.google.com/archive/p/tracexploit/) - Replay network packets.

*   Log anonymizer

    *   [LogAnon](http://code.google.com/archive/p/loganon/) - Log anonymization library that helps having anonymous logs consistent between logs and network captures.

*   Low interaction honeypot (router back door)

    *   [Honeypot-32764 (⭐15)](https://github.com/knalli/honeypot-for-tcp-32764) - Honeypot for router backdoor (TCP 32764).
    *   [WAPot (⭐16)](https://github.com/lcashdol/WAPot) - Honeypot that can be used to observe traffic directed at home routers.

*   honeynet farm traffic redirector

    *   [Honeymole](https://web.archive.org/web/20100326040550/http://www.honeynet.org.pt:80/index.php/HoneyMole) - Deploy multiple sensors that redirect traffic to a centralized collection of honeypots.

*   HTTPS Proxy

    *   [mitmproxy](https://mitmproxy.org/) - Allows traffic flows to be intercepted, inspected, modified, and replayed.

*   System instrumentation

    *   [Sysdig](https://sysdig.com/opensource/) - Open source, system-level exploration allows one to capture system state and activity from a running GNU/Linux instance, then save, filter, and analyze the results.
    *   [Fibratus (⭐2k)](https://github.com/rabbitstack/fibratus) - Tool for exploration and tracing of the Windows kernel.

*   Honeypot for USB-spreading malware

    *   [Ghost-usb (⭐88)](https://github.com/honeynet/ghost-usb-honeypot) - Honeypot for malware that propagates via USB storage devices.

*   Data Collection

    *   [Kippo2MySQL](https://bruteforcelab.com/kippo2mysql) - Extracts some very basic stats from Kippo’s text-based log files and inserts them in a MySQL database.
    *   [Kippo2ElasticSearch](https://bruteforcelab.com/kippo2elasticsearch) - Python script to transfer data from a Kippo SSH honeypot MySQL database to an ElasticSearch instance (server or cluster).

*   Passive network audit framework parser

    *   [Passive Network Audit Framework (pnaf) (⭐31)](https://github.com/jusafing/pnaf) - Framework that combines multiple passive and automated analysis techniques in order to provide a security assessment of network platforms.

*   VM monitoring and tools

    *   [Antivmdetect (⭐681)](https://github.com/nsmfoo/antivmdetection) - Script to create templates to use with VirtualBox to make VM detection harder.
    *   [VMCloak (⭐466)](https://github.com/hatching/vmcloak) - Automated Virtual Machine Generation and Cloaking for Cuckoo Sandbox.
    *   [vmitools](http://libvmi.com/) - C library with Python bindings that makes it easy to monitor the low-level details of a running virtual machine.

*   Binary debugger

    *   [Hexgolems - Pint Debugger Backend (⭐31)](https://github.com/hexgolems/pint) - Debugger backend and LUA wrapper for PIN.
    *   [Hexgolems - Schem Debugger Frontend (⭐143)](https://github.com/hexgolems/schem) - Debugger frontend.

*   Mobile Analysis Tool

    *   [Androguard (⭐4.8k)](https://github.com/androguard/androguard) - Reverse engineering, Malware and goodware analysis of Android applications and more.
    *   [APKinspector (⭐814)](https://github.com/honeynet/apkinspector/) - Powerful GUI tool for analysts to analyze the Android applications.

*   Low interaction honeypot

    *   [Honeyperl](https://sourceforge.net/projects/honeyperl/) - Honeypot software based in Perl with plugins developed for many functions like : wingates, telnet, squid, smtp, etc.
    *   [T-Pot (⭐5.5k)](https://github.com/dtag-dev-sec/tpotce) - All in one honeypot appliance from telecom provider T-Mobile
    *   [beelzebub (⭐485)](https://github.com/mariocandela/beelzebub) - A secure honeypot framework, extremely easy to configure by yaml 🚀

*   Honeynet data fusion

    *   [HFlow2](https://projects.honeynet.org/hflow) - Data coalesing tool for honeynet/network analysis.

*   Server

    *   [Amun](http://amunhoney.sourceforge.net) - Vulnerability emulation honeypot.
    *   [Artillery (⭐323)](https://github.com/trustedsec/artillery/) - Open-source blue team tool designed to protect Linux and Windows operating systems through multiple methods.
    *   [Bait and Switch](http://baitnswitch.sourceforge.net) - Redirects all hostile traffic to a honeypot that is partially mirroring your production system.
    *   [Bifrozt (⭐4)](https://github.com/Ziemeck/bifrozt-ansible) - Automatic deploy bifrozt with ansible.
    *   [Conpot](http://conpot.org/) - Low interactive server side Industrial Control Systems honeypot.
    *   [Heralding (⭐359)](https://github.com/johnnykv/heralding) - Credentials catching honeypot.
    *   [HoneyWRT (⭐19)](https://github.com/CanadianJeff/honeywrt) - Low interaction Python honeypot designed to mimic services or ports that might get targeted by attackers.
    *   [Honeyd (⭐8)](https://github.com/provos/honeyd) - See [honeyd tools](#honeyd-tools).
    *   [Honeysink](http://www.honeynet.org/node/773) - Open source network sinkhole that provides a mechanism for detection and prevention of malicious traffic on a given network.
    *   [Hontel (⭐157)](https://github.com/stamparm/hontel) - Telnet Honeypot.
    *   [KFSensor](http://www.keyfocus.net/kfsensor/) - Windows based honeypot Intrusion Detection System (IDS).
    *   [LaBrea](http://labrea.sourceforge.net/labrea-info.html) - Takes over unused IP addresses, and creates virtual servers that are attractive to worms, hackers, and other denizens of the Internet.
    *   [MTPot (⭐101)](https://github.com/Cymmetria/MTPot) - Open Source Telnet Honeypot, focused on Mirai malware.
    *   [SIREN (⭐11)](https://github.com/blaverick62/SIREN) - Semi-Intelligent HoneyPot Network - HoneyNet Intelligent Virtual Environment.
    *   [TelnetHoney (⭐0)](https://github.com/balte/TelnetHoney) - Simple telnet honeypot.
    *   [UDPot Honeypot (⭐43)](https://github.com/jekil/UDPot) - Simple UDP/DNS honeypot scripts.
    *   [Yet Another Fake Honeypot (YAFH) (⭐8)](https://github.com/fnzv/YAFH) - Simple honeypot written in Go.
    *   [arctic-swallow (⭐1)](https://github.com/ajackal/arctic-swallow) - Low interaction honeypot.
    *   [fapro (⭐1.5k)](https://github.com/fofapro/fapro) - Fake Protocol Server.
    *   [glutton (⭐218)](https://github.com/mushorg/glutton) - All eating honeypot.
    *   [go-HoneyPot (⭐42)](https://github.com/Mojachieee/go-HoneyPot) - Honeypot server written in Go.
    *   [go-emulators (⭐8)](https://github.com/kingtuna/go-emulators) - Honeypot Golang emulators.
    *   [honeymail (⭐26)](https://github.com/sec51/honeymail) - SMTP honeypot written in Golang.
    *   [honeytrap (⭐91)](https://github.com/tillmannw/honeytrap) - Low-interaction honeypot and network security tool written to catch attacks against TCP and UDP services.
    *   [imap-honey (⭐23)](https://github.com/yvesago/imap-honey) - IMAP honeypot written in Golang.
    *   [mwcollectd](https://www.openhub.net/p/mwcollectd) - Versatile malware collection daemon, uniting the best features of nepenthes and honeytrap.
    *   [potd (⭐28)](https://github.com/lnslbrty/potd) - Highly scalable low- to medium-interaction SSH/TCP honeypot designed for OpenWrt/IoT devices leveraging several Linux kernel features, such as namespaces, seccomp and thread capabilities.
    *   [portlurker (⭐20)](https://github.com/bartnv/portlurker) - Port listener in Rust with protocol guessing and safe string display.
    *   [slipm-honeypot (⭐14)](https://github.com/rshipp/slipm-honeypot) - Simple low-interaction port monitoring honeypot.
    *   [telnet-iot-honeypot (⭐297)](https://github.com/Phype/telnet-iot-honeypot) - Python telnet honeypot for catching botnet binaries.
    *   [telnetlogger (⭐236)](https://github.com/robertdavidgraham/telnetlogger) - Telnet honeypot designed to track the Mirai botnet.
    *   [vnclowpot (⭐20)](https://github.com/magisterquis/vnclowpot) - Low interaction VNC honeypot.

*   IDS signature generation

    *   [Honeycomb](http://www.icir.org/christian/honeycomb/) - Automated signature creation using honeypots.

*   Lookup service for AS-numbers and prefixes

    *   [CC2ASN](http://www.cc2asn.com/) - Simple lookup service for AS-numbers and prefixes belonging to any given country in the world.

*   Data Collection / Data Sharing

    *   [HPfriends](http://hpfriends.honeycloud.net/#/home) - Honeypot data-sharing platform.
        *   [hpfriends - real-time social data-sharing](https://heipei.io/sigint-hpfriends/) - Presentation about HPFriends feed system
    *   [HPFeeds (⭐207)](https://github.com/rep/hpfeeds/) - Lightweight authenticated publish-subscribe protocol.

*   Central management tool

    *   [PHARM](http://www.nepenthespharm.com/) - Manage, report, and analyze your distributed Nepenthes instances.

*   Network connection analyzer

    *   [Impost](http://impost.sourceforge.net/) - Network security auditing tool designed to analyze the forensics behind compromised and/or vulnerable daemons.

*   Honeypot deployment

    *   [honeyfs (⭐0)](https://github.com/referefref/honeyfs) - Tool to create artificial file systems for medium/high interaction honeypots.
    *   [Modern Honeynet Network](http://threatstream.github.io/mhn/) - Streamlines deployment and management of secure honeypots.

*   Honeypot extensions to Wireshark

    *   [Wireshark Extensions](https://www.honeynet.org/project/WiresharkExtensions) - Apply Snort IDS rules and signatures against packet capture files using Wireshark.

*   Client

    *   [CWSandbox / GFI Sandbox](https://www.gfi.com/products-and-solutions/all-products)
    *   [Capture-HPC-Linux](https://redmine.honeynet.org/projects/linux-capture-hpc/wiki)
    *   [Capture-HPC-NG (⭐10)](https://github.com/CERT-Polska/HSN-Capture-HPC-NG)
    *   [Capture-HPC](https://projects.honeynet.org/capture-hpc) - High interaction client honeypot (also called honeyclient).
    *   [HoneyBOT](http://www.atomicsoftwaresolutions.com/)
    *   [HoneyC](https://projects.honeynet.org/honeyc)
    *   [HoneySpider Network (⭐28)](https://github.com/CERT-Polska/hsn2-bundle) - Highly-scalable system integrating multiple client honeypots to detect malicious websites.
    *   [HoneyWeb](https://code.google.com/archive/p/gsoc-honeyweb/) - Web interface created to manage and remotely share Honeyclients resources.
    *   [Jsunpack-n (⭐159)](https://github.com/urule99/jsunpack-n)
    *   [MonkeySpider](http://monkeyspider.sourceforge.net)
    *   [PhoneyC (⭐24)](https://github.com/honeynet/phoneyc) - Python honeyclient (later replaced by Thug).
    *   [Pwnypot](https://github.com/shjalayeri/pwnypot) - High Interaction Client Honeypot.
    *   [Rumal](https://github.com/thugs-rumal/) - Thug's Rumāl: a Thug's dress and weapon.
    *   [Shelia](https://www.cs.vu.nl/~herbertb/misc/shelia/) - Client-side honeypot for attack detection.
    *   [Thug](https://buffer.github.io/thug/) - Python-based low-interaction honeyclient.
    *   [Thug Distributed Task Queuing](https://thug-distributed.readthedocs.io/en/latest/index.html)
    *   [Trigona](https://www.honeynet.org/project/Trigona)
    *   [URLQuery](https://urlquery.net/)
    *   [YALIH (Yet Another Low Interaction Honeyclient) (⭐65)](https://github.com/Masood-M/yalih) - Low-interaction client honeypot designed to detect malicious websites through signature, anomaly, and pattern matching techniques.

*   Honeypot

    *   [Deception Toolkit](http://www.all.net/dtk/dtk.html)
    *   [IMHoneypot (⭐14)](https://github.com/mushorg/imhoneypot)

*   PDF document inspector

    *   [peepdf (⭐1.2k)](https://github.com/jesparza/peepdf) - Powerful Python tool to analyze PDF documents.

*   Hybrid low/high interaction honeypot

    *   [HoneyBrid](http://honeybrid.sourceforge.net)

*   SSH Honeypots

    *   [Blacknet (⭐18)](https://github.com/morian/blacknet) - Multi-head SSH honeypot system.
    *   [Cowrie (⭐4.7k)](https://github.com/cowrie/cowrie) - Cowrie SSH Honeypot (based on kippo).
    *   [DShield docker (⭐14)](https://github.com/xme/dshield-docker) - Docker container running cowrie with DShield output enabled.
    *   [endlessh (⭐6.5k)](https://github.com/skeeto/endlessh) - SSH tarpit that slowly sends an endless banner. ([docker image](https://hub.docker.com/r/linuxserver/endlessh))
    *   [HonSSH (⭐366)](https://github.com/tnich/honssh) - Logs all SSH communications between a client and server.
    *   [HUDINX (⭐3)](https://github.com/Cryptix720/HUDINX) - Tiny interaction SSH honeypot engineered in Python to log brute force attacks and, most importantly, the entire shell interaction performed by the attacker.
    *   [Kippo (⭐1.6k)](https://github.com/desaster/kippo) - Medium interaction SSH honeypot.
    *   [Kippo\_JunOS (⭐9)](https://github.com/gregcmartin/Kippo_JunOS) - Kippo configured to be a backdoored netscreen.
    *   [Kojoney2 (⭐36)](https://github.com/madirish/kojoney2) - Low interaction SSH honeypot written in Python and based on Kojoney by Jose Antonio Coret.
    *   [Kojoney](http://kojoney.sourceforge.net/) - Python-based Low interaction honeypot that emulates an SSH server implemented with Twisted Conch.
    *   [Longitudinal Analysis of SSH Cowrie Honeypot Logs (⭐14)](https://github.com/deroux/longitudinal-analysis-cowrie) - Python based command line tool to analyze cowrie logs over time.
    *   [LongTail Log Analysis @ Marist College](http://longtail.it.marist.edu/honey/) - Analyzed SSH honeypot logs.
    *   [Malbait (⭐6)](https://github.com/batchmcnulty/Malbait) - Simple TCP/UDP honeypot implemented in Perl.
    *   [MockSSH (⭐123)](https://github.com/ncouture/MockSSH) - Mock an SSH server and define all commands it supports (Python, Twisted).
    *   [cowrie2neo (⭐4)](https://github.com/xlfe/cowrie2neo) - Parse cowrie honeypot logs into a neo4j database.
    *   [go-sshoney (⭐28)](https://github.com/ashmckenzie/go-sshoney) - SSH Honeypot.
    *   [go0r (⭐34)](https://github.com/fzerorubigd/go0r) - Simple ssh honeypot in Golang.
    *   [gohoney (⭐9)](https://github.com/PaulMaddox/gohoney) - SSH honeypot written in Go.
    *   [hived (⭐2)](https://github.com/sahilm/hived) - Golang-based honeypot.
    *   [hnypots-agent) (⭐37)](https://github.com/joshrendek/hnypots-agent) - SSH Server in Go that logs username and password combinations.
    *   [honeypot.go (⭐25)](https://github.com/mdp/honeypot.go) - SSH Honeypot written in Go.
    *   [honeyssh (⭐11)](https://github.com/ppacher/honeyssh) - Credential dumping SSH honeypot with statistics.
    *   [hornet (⭐21)](https://github.com/czardoz/hornet) - Medium interaction SSH honeypot that supports multiple virtual hosts.
    *   [ssh-auth-logger (⭐18)](https://github.com/JustinAzoff/ssh-auth-logger) - Low/zero interaction SSH authentication logging honeypot.
    *   [ssh-honeypot (⭐574)](https://github.com/droberson/ssh-honeypot) - Fake sshd that logs IP addresses, usernames, and passwords.
    *   [ssh-honeypot (⭐24)](https://github.com/amv42/sshd-honeypot) - Modified version of the OpenSSH deamon that forwards commands to Cowrie where all commands are interpreted and returned.
    *   [ssh-honeypotd (⭐11)](https://github.com/sjinks/ssh-honeypotd) - Low-interaction SSH honeypot written in C.
    *   [sshForShits (⭐38)](https://github.com/traetox/sshForShits) - Framework for a high interaction SSH honeypot.
    *   [sshesame (⭐1.4k)](https://github.com/jaksi/sshesame) - Fake SSH server that lets everyone in and logs their activity.
    *   [sshhipot (⭐168)](https://github.com/magisterquis/sshhipot) - High-interaction MitM SSH honeypot.
    *   [sshlowpot (⭐12)](https://github.com/magisterquis/sshlowpot) - Yet another no-frills low-interaction SSH honeypot in Go.
    *   [sshsyrup (⭐94)](https://github.com/mkishere/sshsyrup) - Simple SSH Honeypot with features to capture terminal activity and upload to asciinema.org.
    *   [twisted-honeypots (⭐84)](https://github.com/lanjelot/twisted-honeypots) - SSH, FTP and Telnet honeypots based on Twisted.

*   Distributed sensor project

    *   [DShield Web Honeypot Project](https://sites.google.com/site/webhoneypotsite/)

*   A pcap analyzer

    *   [Honeysnap](https://projects.honeynet.org/honeysnap/)

*   Network traffic redirector

    *   [Honeywall](https://projects.honeynet.org/honeywall/)

*   Honeypot Distribution with mixed content

    *   [HoneyDrive](https://bruteforcelab.com/honeydrive)

*   Honeypot sensor

    *   [Honeeepi](https://redmine.honeynet.org/projects/honeeepi/wiki) - Honeypot sensor on a Raspberry Pi based on a customized Raspbian OS.

*   File carving

    *   [TestDisk & PhotoRec](https://www.cgsecurity.org/)

*   Behavioral analysis tool for win32

    *   [Capture BAT](https://www.honeynet.org/node/315)

*   Live CD

    *   [DAVIX](https://www.secviz.org/node/89) - The DAVIX Live CD.

*   Spamtrap

    *   [Mail::SMTP::Honeypot](https://metacpan.org/pod/release/MIKER/Mail-SMTP-Honeypot-0.11/Honeypot.pm) - Perl module that appears to provide the functionality of a standard SMTP server.
    *   [Mailoney (⭐246)](https://github.com/awhitehatter/mailoney) - SMTP honeypot, Open Relay, Cred Harvester written in python.
    *   [SendMeSpamIDS.py (⭐11)](https://github.com/johestephan/VerySimpleHoneypot) - Simple SMTP fetch all IDS and analyzer.
    *   [Shiva (⭐128)](https://github.com/shiva-spampot/shiva) - Spam Honeypot with Intelligent Virtual Analyzer.
        *   [Shiva The Spam Honeypot Tips And Tricks For Getting It Up And Running](https://www.pentestpartners.com/security-blog/shiva-the-spam-honeypot-tips-and-tricks-for-getting-it-up-and-running/)
    *   [SMTPLLMPot (⭐1)](https://github.com/referefref/SMTPLLMPot) - A super simple SMTP Honeypot built using GPT3.5
    *   [SpamHAT (⭐24)](https://github.com/miguelraulb/spamhat) - Spam Honeypot Tool.
    *   [Spamhole](http://www.spamhole.net/)
    *   [honeypot (⭐2)](https://github.com/jadb/honeypot) - The Project Honey Pot un-official PHP SDK.
    *   [spamd](http://man.openbsd.org/cgi-bin/man.cgi?query=spamd%26apropos=0%26sektion=0%26manpath=OpenBSD+Current%26arch=i386%26format=html)

*   Commercial honeynet

    *   [Cymmetria Mazerunner](ttps://cymmetria.com/products/mazerunner/) - Leads attackers away from real targets and creates a footprint of the attack.

*   Server (Bluetooth)

    *   [Bluepot (⭐217)](https://github.com/andrewmichaelsmith/bluepot)

*   Dynamic analysis of Android apps

    *   [Droidbox](https://code.google.com/archive/p/droidbox/)

*   Dockerized Low Interaction packaging

    *   [Docker honeynet (⭐21)](https://github.com/sreinhardt/Docker-Honeynet) - Several Honeynet tools set up for Docker containers.
    *   [Dockerized Thug](https://hub.docker.com/r/honeynet/thug/) - Dockerized [Thug (⭐938)](https://github.com/buffer/thug) to analyze malicious web content.
    *   [Dockerpot (⭐146)](https://github.com/mrschyte/dockerpot) - Docker based honeypot.
    *   [Manuka (⭐22)](https://github.com/andrewmichaelsmith/manuka) - Docker based honeypot (Dionaea and Kippo).
    *   [honey\_ports (⭐4)](https://github.com/run41/honey_ports) - Very simple but effective docker deployed honeypot to detect port scanning in your environment.
    *   [mhn-core-docker (⭐31)](https://github.com/MattCarothers/mhn-core-docker) - Core elements of the Modern Honey Network implemented in Docker.

*   Network analysis

    *   [Quechua](https://bitbucket.org/zaccone/quechua)

*   SIP Server

    *   [Artemnesia VoIP](http://artemisa.sourceforge.net)

*   SIP

    *   [SentryPeer (⭐140)](https://github.com/SentryPeer/SentryPeer) - Protect your SIP Servers from bad actors.

*   IOT Honeypot

    *   [HoneyThing (⭐113)](https://github.com/omererdem/honeything) - TR-069 Honeypot.
    *   [Kako (⭐24)](https://github.com/darkarnium/kako) - Honeypots for a number of well known and deployed embedded device vulnerabilities.

*   Honeytokens
    *   [CanaryTokens (⭐1.6k)](https://github.com/thinkst/canarytokens) - Self-hostable honeytoken generator and reporting dashboard; demo version available at [CanaryTokens.org](https://canarytokens.org/generate).
    *   [Honeybits (⭐267)](https://github.com/0x4D31/honeybits) - Simple tool designed to enhance the effectiveness of your traps by spreading breadcrumbs and honeytokens across your production servers and workstations to lure the attacker toward your honeypots.
    *   [Honeyλ (HoneyLambda) (⭐500)](https://github.com/0x4D31/honeylambda) - Simple, serverless application designed to create and monitor URL honeytokens, on top of AWS Lambda and Amazon API Gateway.
    *   [dcept (⭐496)](https://github.com/secureworks/dcept) - Tool for deploying and detecting use of Active Directory honeytokens.
    *   [honeyku (⭐58)](https://github.com/0x4D31/honeyku) - Heroku-based web honeypot that can be used to create and monitor fake HTTP endpoints (i.e. honeytokens).

## Honeyd Tools

*   Honeyd plugin

    *   [Honeycomb](http://www.honeyd.org/tools.php)

*   Honeyd viewer

    *   [Honeyview](http://honeyview.sourceforge.net/)

*   Honeyd to MySQL connector

    *   [Honeyd2MySQL](https://bruteforcelab.com/honeyd2mysql)

*   A script to visualize statistics from honeyd

    *   [Honeyd-Viz](https://bruteforcelab.com/honeyd-viz)

*   Honeyd stats
    *   [Honeydsum.pl (⭐324)](https://github.com/DataSoft/Honeyd/blob/master/scripts/misc/honeydsum-v0.3/honeydsum.pl)

## Network and Artifact Analysis

*   Sandbox

    *   [Argos](http://www.few.vu.nl/argos/) - Emulator for capturing zero-day attacks.
    *   [COMODO automated sandbox](https://help.comodo.com/topic-72-1-451-4768-.html)
    *   [Cuckoo](https://cuckoosandbox.org/) - Leading open source automated malware analysis system.
    *   [Pylibemu (⭐122)](https://github.com/buffer/pylibemu) - Libemu Cython wrapper.
    *   [RFISandbox](https://monkey.org/~jose/software/rfi-sandbox/) - PHP 5.x script sandbox built on top of [funcall](https://pecl.php.net/package/funcall).
    *   [dorothy2 (⭐197)](https://github.com/m4rco-/dorothy2) - Malware/botnet analysis framework written in Ruby.
    *   [imalse (⭐11)](https://github.com/hbhzwj/imalse) - Integrated MALware Simulator and Emulator.
    *   [libemu (⭐131)](https://github.com/buffer/libemu) - Shellcode emulation library, useful for shellcode detection.

*   Sandbox-as-a-Service

    *   [Hybrid Analysis](https://www.hybrid-analysis.com) - Free malware analysis service powered by Payload Security that detects and analyzes unknown threats using a unique Hybrid Analysis technology.
    *   [Joebox Cloud](https://jbxcloud.joesecurity.org/login) - Analyzes the behavior of malicious files including PEs, PDFs, DOCs, PPTs, XLSs, APKs, URLs and MachOs on Windows, Android and Mac OS X for suspicious activities.
    *   [VirusTotal](https://www.virustotal.com/) - Analyze suspicious files and URLs to detect types of malware, and automatically share them with the security community.
    *   [malwr.com](https://malwr.com/) - Free malware analysis service and community.

## Data Tools

*   Front Ends

    *   [DionaeaFR (⭐65)](https://github.com/rubenespadas/DionaeaFR) - Front Web to Dionaea low-interaction honeypot.
    *   [Django-kippo (⭐11)](https://github.com/jedie/django-kippo) - Django App for kippo SSH Honeypot.
    *   [Shockpot-Frontend (⭐2)](https://github.com/GovCERT-CZ/Shockpot-Frontend) - Full featured script to visualize statistics from a Shockpot honeypot.
    *   [Tango (⭐251)](https://github.com/aplura/Tango) - Honeypot Intelligence with Splunk.
    *   [Wordpot-Frontend (⭐3)](https://github.com/GovCERT-CZ/Wordpot-Frontend) - Full featured script to visualize statistics from a Wordpot honeypot.
    *   [honeyalarmg2 (⭐3)](https://github.com/schmalle/honeyalarmg2) - Simplified UI for showing honeypot alarms.
    *   [honeypotDisplay (⭐2)](https://github.com/Joss-Steward/honeypotDisplay) - Flask website which displays data gathered from an SSH Honeypot.

*   Visualization

    *   [Acapulco (⭐9)](https://github.com/hgascon/acapulco) - Automated Attack Community Graph Construction.
    *   [Afterglow Cloud (⭐14)](https://github.com/ayrus/afterglow-cloud)
    *   [Afterglow](http://afterglow.sourceforge.net/)
    *   [Glastopf Analytics (⭐1)](https://github.com/katkad/Glastopf-Analytics) - Easy honeypot statistics.
    *   [HoneyMalt (⭐13)](https://github.com/SneakersInc/HoneyMalt) - Maltego tranforms for mapping Honeypot systems.
    *   [HoneyMap (⭐216)](https://github.com/fw42/honeymap) - Real-time websocket stream of GPS events on a fancy SVG world map.
    *   [HoneyStats](https://sourceforge.net/projects/honeystats/) - Statistical view of the recorded activity on a Honeynet.
    *   [HpfeedsHoneyGraph (⭐14)](https://github.com/yuchincheng/HpfeedsHoneyGraph) - Visualization app to visualize hpfeeds logs.
    *   [IVRE (⭐3.2k)](https://github.com/ivre/ivre) - Network recon framework, published by @cea-sec & @ANSSI-FR. Build your own, self-hosted and fully-controlled alternatives to Criminalip / Shodan / ZoomEye / Censys and GreyNoise, run your Passive DNS service, collect and analyse network intelligence from your sensors, and much more!
    *   [Kippo stats (⭐17)](https://github.com/mfontani/kippo-stats) - Mojolicious app to display statistics for your kippo SSH honeypot.
    *   [Kippo-Graph](https://bruteforcelab.com/kippo-graph) - Full featured script to visualize statistics from a Kippo SSH honeypot.
    *   [The Intelligent HoneyNet (⭐60)](https://github.com/jpyorre/IntelligentHoneyNet) - Create actionable information from honeypots.
    *   [ovizart (⭐46)](https://github.com/oguzy/ovizart) - Visual analysis for network traffic.

## Guides

*   [T-Pot: A Multi-Honeypot Platform](https://dtag-dev-sec.github.io/mediator/feature/2015/03/17/concept.html)

*   [Honeypot (Dionaea and kippo) setup script (⭐81)](https://github.com/andrewmichaelsmith/honeypot-setup-script/)

*   Deployment

    *   [Dionaea and EC2 in 20 Minutes](http://andrewmichaelsmith.com/2012/03/dionaea-honeypot-on-ec2-in-20-minutes/) - Tutorial on setting up Dionaea on an EC2 instance.
    *   [Using a Raspberry Pi honeypot to contribute data to DShield/ISC](https://isc.sans.edu/diary/22680) - The Raspberry Pi based system will allow us to maintain one code base that will make it easier to collect rich logs beyond firewall logs.
    *   [honeypotpi (⭐31)](https://github.com/free5ty1e/honeypotpi) - Script for turning a Raspberry Pi into a HoneyPot Pi.

*   Research Papers

    *   [Honeypot research papers (⭐21)](https://github.com/shbhmsingh72/Honeypot-Research-Papers) - PDFs of research papers on honeypots.
    *   [vEYE](https://link.springer.com/article/10.1007%2Fs10115-008-0137-3) - Behavioral footprinting for self-propagating worm detection and profiling.

