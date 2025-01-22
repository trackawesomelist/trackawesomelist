# Track Awesome Vehicle Security Updates Weekly

🚗  A curated list of resources for learning about vehicle security and car hacking.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/jaredthecoder/awesome-vehicle-security/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 jaredthecoder/awesome-vehicle-security](https://github.com/jaredthecoder/awesome-vehicle-security) · ⭐ 3.3K · 🏷️ Security

[ [Daily](/content/jaredthecoder/awesome-vehicle-security/README.md) / Weekly / [Overview](/content/jaredthecoder/awesome-vehicle-security/readme/README.md) ]

## [Jan 27 - Feb 02, 2025](/content/2025/4/README.md)

### Presentations

*   [TR23: V2GEvil: Ghost in the wires](https://www.youtube.com/watch?v=JVWFfSmIlRY) - This research is dedicated to enhancing the cybersecurity of electric vehicles, with a specific focus on identifying vulnerabilities in the Electric Vehicle Communication Controller (EVCC), and an introduction to the tool V2GEvil. Accessible through the On-Board Charging (OBC) port, makes this attack vector really important for the security of future vehicles.
*   [DEF CON CHV - V2GEvil: Ghost in the wires](https://www.youtube.com/watch?v=Ui2etjRyrUE) - Shortened and summarized version of the talk V2GEvil: Ghost in the wires, from the DEF CON 32 Car Hacking Village, by Pavel Khunt and Thomas Sermpinis.
*   [The hack, the crash and two smoking barrels. (And all the times I (almost) killed an engineer.)](https://www.youtube.com/watch?v=MDndWJxfP-U) - Thomas Sermpinis goes through the process of responsibly disclosing findings affecting the Blind Spot Detection Sensor of a current MY vehicle from one of the biggest OEMs in the world, leading to accusations that he was collaborating with hostile nations by the OEM. A story about how automotive manufacturers are treating the security industry, where are we heading, and how to be better, on the stage of DEF CON 32.

### Research Papers

*   [On the Insecurity of Vehicles Against Protocol-Level Bluetooth Threats](https://hexhive.epfl.ch/publications/files/22WOOT.pdf)
*   [Pavel, K. Vehicle On-Board Charging Security Scanner, 2024](https://dspace.cvut.cz/bitstream/handle/10467/113764/F8-DP-2024-Khunt-Pavel-thesis.pdf)

### Libraries and Tools / C++

*   [UnlockECU (⭐277)](https://github.com/jglim/UnlockECU) - Free, open-source ECU seed-key unlocking tool.

## [Feb 05 - Feb 11, 2024](/content/2024/6/README.md)

### Presentations

*   [FREE-FALL: HACKING TESLA FROM WIRELESS TO CAN BUS](https://www.blackhat.com/docs/us-17/thursday/us-17-Nie-Free-Fall-Hacking-Tesla-From-Wireless-To-CAN-Bus-wp.pdf) - Zeronights 2016 and later BlackHat talk by Sen Nie, Ling Liu, and Yuefeng Du from Tencent and KEEN Security lab
*   [TR22: UDS Fuzzing and the Path to Game Over](https://www.youtube.com/watch?v=c_DqxHmH7kc) - UDS diagnostics protocol fuzzing methodology, presented as a result of numerous penetration testing projects in the automotive industry, with real world exploitation PoCs, presented during Troopers Conference 2022.
*   [CCC - Horror Stories From the Automotive Industry](https://www.youtube.com/watch?v=rAA-agcNeeg) - Horrifying examples of common vulnerabilities in the automotive industry, result of more than 100 penetration tests targeting Tier 1 suppliers and OEMs, with ultimate goal to raise awareness on the current state of automotive security. Additionally, PoC of automated week seed randomness exploitation in automotive components, by using a battery isolator in heavy-duty vehicles and the UDS protocol, for complete compromise of a target. Presented in Chaos Communication Camp, DeepSec 2023 and Troopers Conference 23.
*   [Car Hacking Scene in the PH: How Far We've Come](https://www.youtube.com/watch?v=JaF-_KYQ46A) - Car Hacking Village PH presents their first attempt on the main tracks for ROOTCON. This is a rundown of CHVPH's past security research to current research - from hacking infotainment systems to CAN Bus protocols and a summary of cars available in the Philippines which are susceptible to car thefts.
*   [Analysis of an In-vehicular network: From CAN bus to infotainment](https://www.youtube.com/watch?v=4d-uhs2VLCQ) - This talk will feature Div0 CSQ’s 3 test benches as they explore more features on Connected vehicles. This was presented in ROOTCON 17 Car Hacking Village.
*   [An overview of Automotive Defensive Engineering](https://www.youtube.com/watch?v=MfTNv9SXd-o) - This talk is for car hackers to learn about modern defense measures being added to ECUs and Vehicle Architectures. This was presented in ROOTCON 17 Car Hacking Village.
*   [Hacking Back Your Car](https://www.youtube.com/watch?v=akMok3Hb-pE) - Kamel Ghali's talk on ROOTCON 17 about how an attacker's perspective on hacking a car and origins of such attacks, how they've been used in different countries over the years, and explore the technical details of what makes such an attack possible.

### Books

*   [2014 Car Hacker's Handbook](https://www.amazon.com/Car-Hackers-Manual-Craig-Smith/dp/0990490106) - Free guide to hacking vehicles from 2014.
*   [Inside Radio: An Attack and Defense Guide](https://www.amazon.com/Inside-Radio-Attack-Defense-Guide/dp/9811084467)This book discusses the security issues in a wide range of wireless devices and systems,Chapter 4 433/315MHz Communication (4.3　4.4 4.5 is about car keys Security)

### Research Papers

*   [Intrusion detection system based on the analysis of time intervals of CAN messages for in-vehicle network, 2016](https://ieeexplore.ieee.org/document/7427089)

### Websites

*   [OpenGarages](https://github.com/opengarages) - Provides public access, documentation and tools necessary to understand today's modern vehicle systems.

### Podcasts and Episodes / Podcasts

*   [TrustedSec Podcast](https://podcasts.apple.com/us/podcast/security-noise/id1428851782) - From the people at TrustedSec, leaders in Social Engineering, their episodes often go into recent vehicle vulnerabilities and exploits.

### Miscellaneous / Episodes

*   [CANtact](https://cantact.io/cantact/users-guide.html) - "The Open Source Car Tool" designed to help you hack your car. You can buy one or make your own following the guide here.
*   [Macchina M2](https://www.macchina.cc/m2-introduction) - Macchina 2.0 is a complete overhaul of our 1.X generation of Macchina. The goals are still the same: Create an easy-to-use, fully-open, and super-compatible automotive interface.

### Libraries and Tools / Python

*   [Caring Caribou Next (⭐9)](https://github.com/Cr0wTom/caringcaribounext) - Upgraded and optimized version of the original Caring Caribou project.

### Libraries and Tools / JavaScript

*   [UberATC](https://www.uber.com/us/en/autonomous/) - Uber Advanced Technologies Center, now Uber AV - [info@uberatc.com](https://github.com/jaredthecoder/awesome-vehicle-security/blob/master/README.md/mailto:info@uberatc.com).
*   [VicOne](https://www.vicone.com/) - A subsidiary of Trend Micro which focuses on automotive security

### Coordinated disclosure / JavaScript

*   [Stellantis](https://bugcrowd.com/stellantis) on Bugcrowd - Coordinated disclosure submissions accepted, paid bounties offered
*   [ASRG](https://asrg.io/disclosure/) - The ASRG Disclosure Process is to support responsible disclosure when direct communication with the responsible company is unavailable or not responsive.
*   [Zeekr](https://security.zeekrlife.com/vulnerability) - Zeekr and Geely Responsible disclosure program

## [Jul 24 - Jul 30, 2023](/content/2023/30/README.md)

### Websites

*   [NIST Automotive Cybersecurity Community of Interest](https://csrc.nist.gov/Projects/auto-cybersecurity-coi) - NIST, the organization behind the NVD CVE database and modern cryptographic standards, runs a Community of Interest group for Automotive Cybersecurity that seeks to "provide a way for NIST to facilitate the discussions and receive comments and feedback from the automotive industry, academia, and government.".

### Applications / Episodes

*   [O2OO](http://web.archive.org/web/20201108091723/https://www.vanheusden.com/O2OO/) - Works with the ELM327 to record data to a SQLite database for graphing purposes. It also supports reading GPS data. You can connect this to your car and have it map out using Google Maps KML data where you drive.

### Libraries and Tools / Python

*   [SocketCAN](https://python-can.readthedocs.io/en/master/interfaces/socketcan.html) Python interface to SocketCAN
*   [canmatrix (⭐948)](https://github.com/ebroecker/canmatrix) Python module to work with CAN matrix files
*   [canopen](https://canopen.readthedocs.io/en/latest/) Python module to communicate with CANopen devices
*   [cantools (⭐1.9k)](https://github.com/eerimoq/cantools) Python module to decode and encode CAN messages using a DBC file

## [Feb 13 - Feb 19, 2023](/content/2023/7/README.md)

### Libraries and Tools / Python

*   [Python-CAN (⭐1.3k)](https://github.com/hardbyte/python-can) - Python interface to various CAN implementations, including SocketCAN. Allows you to use Python 2.7.x or 3.3.x+ to communicate over CAN networks.

## [Dec 12 - Dec 18, 2022](/content/2022/50/README.md)

### Presentations

*   [Remote Exploitation of Honda Cars](https://www.youtube.com/watch?v=y4Uzm-CTa0I\&ab_channel=CarHackingVillage) - The Honda Connect app used by Honda City 5th generation used weak security mechanisms in its APIs for access control which would allow a malicious user to perform actions like starting the car, locking/unlocking car etc. remotely by interacting with it's Telematics Control Unit (TCU)

### Websites

*   [Automotive Security Research Group](https://asrg.io/knowledge/) - The Automotive Security Research Group (ASRG) is a non-profit initiative to promote the development of security solutions for automotive products.

### Libraries and Tools / Python

*   [canTot (⭐132)](https://github.com/shipcod3/canTot) - A python-based cli framework based on sploitkit and is easy to use because it similar to working with Metasploit. This similar to an exploit framework but focused on known CAN Bus vulnerabilities or fun CAN Bus hacks.

## [Jun 13 - Jun 19, 2022](/content/2022/24/README.md)

### Research Papers

*   [Modeling Inter-Signal Arrival Times for Accurate Detection of CAN Bus Signal Injection Attacks](https://dl.acm.org/citation.cfm?id=3064816)

## [Feb 14 - Feb 20, 2022](/content/2022/7/README.md)

### Presentations

*   [Analysis and Defense of Automotive Networks](https://www.youtube.com/watch?v=a1huGwMjjd4) - Overview of CAN, security, and potential intrusion detection approaches at BSides Knoxville 2020

### Research Papers

*   [CAN-D: A Modular Four-Step Pipeline for Comprehensively Decoding Controller Area Network Data](https://arxiv.org/pdf/2006.05993.pdf)
*   [Time-Based CAN Intrusion Detection Benchmark](https://arxiv.org/pdf/2101.05781.pdf)
*   [Addressing the Lack of Comparability & Testing in CAN Intrusion Detection Research: A Comprehensive Guide to CAN IDS Data & Introduction of the ROAD Dataset](https://arxiv.org/pdf/2012.14600.pdf)

### Conferences

*   [Cyber Truck Challenge](https://www.cybertruckchallenge.org/) - Conference that focuses on heavy vehicle cybersecurity issues. Includes hands-on assessments of heavy vehicles and subsystems.

### Miscellaneous / Episodes

*   [Real ORNL Automotive Dynamometer (ROAD) CAN Intrusion Dataset](https://0xsam.com/road/)
*   [CAN DoS Fuzzing Attack Video](https://www.youtube.com/shorts/80A5IhvwsJU)
*   [ECU Reflashing Detector Demo](https://www.youtube.com/watch?v=HPpGzwWQY5Y)

### Libraries and Tools / C++

*   [CANdevStudio (⭐969)](https://github.com/GENIVI/CANdevStudio) - Development tool for CAN bus simulation. CANdevStudio enables to simulate CAN signals such as ignition status, doors status or reverse gear by every automotive developer.

### Libraries and Tools / Java

*   [ITS Geonetworking (⭐102)](https://github.com/alexvoronov/geonetworking) - ETSI ITS G5 GeoNetworking stack, in Java: CAM-DENM / ASN.1 PER / BTP / GeoNetworking

## [Oct 04 - Oct 10, 2021](/content/2021/40/README.md)

### Miscellaneous / Episodes

*   [Uptane](https://uptane.github.io/overview.html) - Uptane is an open and secure software update system design protecting software delivered over-the-air to the computerized units of automobiles and is designed to be resilient even to the best efforts of nation state attackers.

## [Aug 30 - Sep 05, 2021](/content/2021/35/README.md)

### Research Papers

*   [The Connected Car - Ways to get unauthorized access and potential implications, 2018](https://www.computest.nl/documents/9/The_Connected_Car._Research_Rapport_Computest_april_2018.pdf)

## [Jul 05 - Jul 11, 2021](/content/2021/27/README.md)

### Libraries and Tools / Python

*   [CanoPy (⭐240)](https://github.com/tbruno25/canopy) - A python gui used to visualize and plot message payloads in real time.

## [Nov 23 - Nov 29, 2020](/content/2020/47/README.md)

### Presentations

*   [TR19: Automotive Penetration Testing with Scapy](https://www.youtube.com/watch?v=7D7uNqPWrXw) - Overview on how Scapy can be used for automotive penetration testing at Troopers Conference 2019.

## [Oct 19 - Oct 25, 2020](/content/2020/42/README.md)

### Presentations

*   [Pentesting vehicles with YACHT (Yet Another Car Hacking Tool)](https://www.blackhat.com/docs/eu-16/materials/eu-16-Sintsov-Pen-Testing-Vehicles-With-Cantoolz.pdf) -A presentation that discusses different attack surfaces of a vehicle, then continues to describe an approach to car hacking along with tools needed to analyse and gather useful information.

## [Sep 28 - Oct 04, 2020](/content/2020/39/README.md)

### Libraries and Tools / JavaScript

*   [Cohda Wireless](https://cohdawireless.com/) - V2X DSRC Radio and Software

## [Sep 21 - Sep 27, 2020](/content/2020/38/README.md)

### Who to Follow

*   Daniel Öster: Dala's EV Repair, electric vehicle CAN hacking/upgrading
    *   [Youtube](https://www.youtube.com/channel/UCc3g-KhOBoicgOrB4KkMeew)
    *   [Website](https://dalasevrepair.fi/)

## [Aug 10 - Aug 16, 2020](/content/2020/32/README.md)

### Miscellaneous / Episodes

*   [CAN MITM Bridge by MUXSCAN](https://www.tindie.com/products/muxsan/can-mitm-bridge-3-port-rev-25/) - a tool to MITM CAN messages, allowing easy interaction with your car.

## [Jun 15 - Jun 21, 2020](/content/2020/24/README.md)

### Libraries and Tools / Python

*   [Scapy (⭐11k)](https://github.com/secdev/scapy) - A python library to send, receive, edit raw packets. Supports CAN and automotive protocols: see the [automotive doc](https://scapy.readthedocs.io/en/latest/layers/automotive.html)

## [Nov 04 - Nov 10, 2019](/content/2019/44/README.md)

### Articles

*   [Car Hacking in 30 Minutes or Less](https://brysonpayne.com/2018/10/20/start-car-hacking-in-30-minutes-or-less/) - Using VirtualBox and Kali Linux, you can start car hacking using completely free open-source software and tools, including can-utils, ICSim, ScanTool, Wireshark, and tcpdump

## [Jun 10 - Jun 16, 2019](/content/2019/23/README.md)

### Presentations

*   [Car Infotainment Hacking Methodology and Attack Surface Scenario](https://www.youtube.com/watch?v=F0mYkI2FJ_4) - A guide on how to attack, hunt bugs or hack your IVI by Jay Turla which was presented at the Packet Hacking Village / Wall of Sheep during DEF CON 26.

### Who to Follow

*   carfucar: Founder of Car Hacking Village and Speaker or Trainer
    *   [Twitter](https://twitter.com/CarHackVillage)
*   Ian Tabor / mintynet: Car Hacker, Car Hacking Village staff
    *   [Twitter](https://twitter.com/mintynet)
    *   [Website](https://www.mintynet.com/)

## [Jan 07 - Jan 13, 2019](/content/2019/1/README.md)

### Articles

*   [Analysis of an old Subaru Impreza - Subaru Select Monitor v1 (SSM1)](https://p1kachu.pluggi.fr/project/automotive/2018/12/28/subaru-ssm1/) - Digging into an old ECU through an old protocol and disabling a 1997 Subaru Impreza's speed limiter.

### Books

*   [智能汽车安全攻防大揭秘](https://www.amazon.cn/dp/B075QZXY7W)This book first introduced some basic knowledge of security for automotive R\&D personnel, such as encryption and decryption, security authentication, digital signatures, common attack types, and methods. Then it introduced the working principles of some smart cars for security researchers, such as the automotive intranet. Protocol, network architecture, principle of X-By-Wire remote control system, common potential attack surface, etc. Finally, a detailed analysis of some actual automotive attack or security test cases, and defense analysis of the loopholes involved in the case during the analysis process.

## [Oct 01 - Oct 07, 2018](/content/2018/40/README.md)

### Miscellaneous / Episodes

*   [Reverse Engineering Resources (⭐89)](https://github.com/ps1337/automotive-security-research)

## [Sep 17 - Sep 23, 2018](/content/2018/38/README.md)

### Applications / Episodes

*   [CANalyzat0r (⭐763)](https://github.com/schutzwerk/CANalyzat0r) - A security analysis toolkit for proprietary car protocols.

## [Sep 03 - Sep 09, 2018](/content/2018/36/README.md)

### Libraries and Tools / C

*   [dbcc (⭐383)](https://github.com/howerj/dbcc) - "dbcc is a program for converting a DBC file primarily into into C code that can serialize and deserialize CAN messages." With existing DBC files from a vehicle, this file allows you to convert them to C code that extracts the CAN messages and properties of the CAN environment.

### Libraries and Tools / Python

*   [CanCat (⭐199)](https://github.com/atlas0fd00m/CanCat) - A "swiss-army knife" for interacting with live CAN data. Primary API interface in Python, but written in C++.

## [Aug 20 - Aug 26, 2018](/content/2018/34/README.md)

### Articles

*   [Car Hacking on the Cheap](http://www.ioactive.com/pdfs/IOActive_Car_Hacking_Poories.pdf) -  A whitepaper from Chris Valasek and IOActive on hacking your car when you don't have a lot of resources at your disposal.
*   [Researchers tackle autonomous vehicle security](https://phys.org/news/2017-05-tackle-autonomous-vehicle.html) - Texas A\&M researchers develop intelligence system prototype.
*   [Reverse engineering of the Nitro OBD2](https://blog.quarkslab.com/reverse-engineering-of-the-nitro-obd2.html) - Reverse engineering of CAN diagnostic tools.

### Presentations

*   [How to drift with any car](https://www.youtube.com/watch?v=KU7gl1n1tIs) - Introduction to CAN hacking, and using a real car as an Xbox controller.

### Miscellaneous / Episodes

*   [OpenXC](http://openxcplatform.com/hardware.html) - OpenXC is a combination of open source hardware and software that lets you extend your vehicle with custom applications and pluggable modules. It uses standard, well-known tools to open up a wealth of data from the vehicle to developers. Started by researchers at Ford, it works for all 2002 and newer MY vehicles (standard OBD-II interface). Researchers at Ford Motor Company joined up to create a standard way of creating aftermarket software and hardware for vehicles.

### Applications / Episodes

*   [talking-with-cars (⭐115)](https://github.com/P1kachu/talking-with-cars) - CAN related scripts, and scripts to use a car as a gamepad

## [Feb 12 - Feb 18, 2018](/content/2018/7/README.md)

### Miscellaneous / Episodes

*   [PandwaRF](https://pandwarf.com/) - PandwaRF is a pocket-sized, portable RF analysis tool operating the sub-1 GHz range. It allows the capture, analysis and re-transmission of RF via an Android device or a Linux PC. Capture any data in ASK/OOK/MSK/2-FSK/GFSK modulation from the 300-928 MHz band.

## [Nov 27 - Dec 03, 2017](/content/2017/48/README.md)

### Miscellaneous / Episodes

*   [Arduino](https://www.arduino.cc/) - Arduino boards have a number of shields you can attach to connect to CAN-enabled devices.
    *   [CANdiy-Shield (⭐24)](https://github.com/watterott/CANdiy-Shield)
    *   [DFRobot CAN-BUS Shield For Arduino](http://www.dfrobot.com/index.php?route=product/product\&product_id=1444)
    *   [SparkFun CAN-BUS Shield](https://www.sparkfun.com/products/13262)
    *   [arduino-canbus-monitor (⭐309)](https://github.com/latonita/arduino-canbus-monitor) - No matter which shield is selected you will need your own sniffer. This is implementation of standard Lawicel/SLCAN protocol for Arduino + any MCP CAN Shield to use with many standard CAN bus analysis software packages or SocketCAN

## [Oct 30 - Nov 05, 2017](/content/2017/44/README.md)

### Books

*   [2016 Car Hacker's Handbook](https://www.amazon.com/Car-Hackers-Handbook-Penetration-Tester/dp/1593277032) - Latest version of the Car Hacker's handbook with updated information to hack your own vehicle and learning vehicle security. For a physical copy as well unlimited PDF, MOBI, and EPUB copies of the book, buy it at [No Starch Press](https://www.nostarch.com/carhacking). Sections are available online [here](https://books.google.com/books?id=Ao_QCwAAQBAJ\&lpg=PP1\&dq=car%20hacking\&pg=PP1#v=onepage\&q\&f=false).

### Blogs

*   [Keen Security Lab Blog](http://keenlab.tencent.com/en/) - Blog created by Keen Security Lab of Tencent that posts research on car security.

## [Oct 23 - Oct 29, 2017](/content/2017/43/README.md)

### Articles

*   [How to hack a car — a quick crash-course](https://medium.freecodecamp.org/hacking-cars-a-guide-tutorial-on-how-to-hack-a-car-5eafcfbbb7ec) - Car enthusiast Kenny Kuchera illustrates just enough information to get you up and running. An excellent resource for first timers!

### Research Papers

*   [Automobile Driver Fingerprinting, 2016](http://www.autosec.org/pubs/fingerprint.pdf)

## [Oct 16 - Oct 22, 2017](/content/2017/42/README.md)

### Websites

*   [Python Security](http://www.pythoncarsecurity.com/) - A website for browsing and buying python-integrated cars having certain vehicular security features.

### Libraries and Tools / C++

*   [High Level ViWi Service (⭐14)](https://github.com/iotbzh/high-level-viwi-service) - High level Volkswagen CAN signaling protocol implementation.

## [Oct 09 - Oct 15, 2017](/content/2017/41/README.md)

### Presentations

*   [Self-Driving and Connected Cars: Fooling Sensors and Tracking Drivers](https://www.youtube.com/watch?v=C29UGFsIWVI) - Black Hat talk by Jonathan Petit. Automated and connected vehicles are the next evolution in transportation and will improve safety, traffic efficiency and driving experience. This talk will be divided in two parts: 1) security of autonomous automated vehicles and 2) privacy of connected vehicles. 2015
*   [A Survey of Remote Automotive Attack Surfaces](https://www.youtube.com/watch?v=MAGacjNw0Sw) - Black Hat talk By Charlie Miller and Chris Valasek. Automotive security concerns have gone from the fringe to the mainstream with security researchers showing the susceptibility of the modern vehicle to local and remote attacks. Discussion of vehicle attack surfaces. 2014.

## [Oct 02 - Oct 08, 2017](/content/2017/40/README.md)

### Articles

*   [Stopping a Jeep Cherokee on the Highway Remotely](https://www.wired.com/2015/07/hackers-remotely-kill-jeep-highway/) - Chris Valasek's and Charlie Miller's pivotal research on hacking into Jeep's presented at DEFCON in 2015.
*   [Car Hacking: The definitive source](http://illmatics.com/carhacking.html) - Charlie Miller and Chris Valasek publish all tools, data, research notes, and papers for everyone for free
*   [Car Hacking on the cheap](https://community.rapid7.com/community/transpo-security/blog/2017/02/08/car-hacking-on-the-cheap) - Craig Smith wrote a brief article on working with Metasploit’s HWBrige using ELM327 Bluetooth dongle

### Presentations

*   ["Hopping on the CAN Bus" from BlackHat Asia 2015](https://www.blackhat.com/asia-15/briefings.html#hopping-on-the-can-bus) - A talk from BlackHat Asia 2015 that aims to enable the audience to "gain an understanding of automotive systems, but will also have the tools to attack them".
*   [Remote Exploitation of an Unaltered Passenger Vehicle](https://www.youtube.com/watch?v=OobLb1McxnI) - DEFCON 23 talk Chris Valasek and Charlie Miller give their now famous talk on hacking into a Jeep remotely and stopping it dead in its tracks.

### Books

*   [A Comprehensible Guide to Controller Area Network](https://www.amazon.com/Comprehensible-Guide-Controller-Area-Network/dp/0976511606/ref=pd_sim_14_1?ie=UTF8\&dpID=41-D9UhlE9L\&dpSrc=sims\&preST=_AC_UL160_SR124%2C160_\&psc=1\&refRID=3FH8N10610H0RX8SMB6K) - An older book from 2005, but still a comprehensive guide on CAN buses and networking in vehicles.
*   [Controller Area Network Prototyping with Arduino](https://www.amazon.com/Controller-Area-Network-Prototyping-Arduino/dp/1938581164/ref=pd_sim_14_2?ie=UTF8\&dpID=51J27ZEcl9L\&dpSrc=sims\&preST=_AC_UL160_SR123%2C160_\&psc=1\&refRID=V42FKNW09QGVGHW7ZFRR) - This book guides you through prototyping CAN applications on Arduinos, which can help when working with CAN on your own car.
*   [Embedded Networking with CAN and CANopen](https://www.amazon.com/Embedded-Networking-CANopen-Olaf-Pfeiffer/dp/0929392787/ref=pd_sim_14_37?ie=UTF8\&dpID=41UnLKYFpmL\&dpSrc=sims\&preST=_AC_UL160_SR122%2C160_\&psc=1\&refRID=V42FKNW09QGVGHW7ZFRR) - From 2003, this book fills in gaps in CAN literature and will educate you further on CAN networks and working with embedded systems.

### Research Papers

*   [A Car Hacking Experiment: When Connectivity Meets Vulnerability](http://ieeexplore.ieee.org/abstract/document/7413993/)
*   [Security issues and vulnerabilities in connected car systems](http://ieeexplore.ieee.org/abstract/document/7223297/)

### Podcasts and Episodes / Podcasts

*   [Security Weekly](http://securityweekly.com/) - Excellent podcast covering all ranges of security, with some episodes focusing portions on vehicle security from cars to drones.

### Podcasts and Episodes / Episodes

*   [Car Hacking with Craig Smith](http://softwareengineeringdaily.com/2015/09/02/car-hacking-with-craig-smith/) - Software Engineering Daily did an amazing episode with Craig Smith, author of the Car Hacking Handbook (above), on hacking into vehicles.

### Miscellaneous / Episodes

*   [ELM327](https://www.elmelectronics.com/obdic.html) - The de facto chipset that's very cheap and can be used to connect to CAN devices.

### Applications / Episodes

*   [Intrepid Tools](http://store.intrepidcs.com/) - Expensive, but extremely versatile tools specifically designed for reversing CAN and other vehicle communication protocols.
*   [Wireshark](https://www.wireshark.org/) - WireShark can be used for reversing CAN communications.
*   [OpenXC](http://openxcplatform.com/getting-started/index.html) - Currently, OpenXC works with `Python` and `Android`, with libraries provided to get started.
*   [openpilot (⭐52k)](https://github.com/commaai/openpilot) - openpilot is an open source driving agent that performs the functions of Adaptive Cruise Control (ACC) and Lane Keeping Assist System (LKAS) for Hondas and Acuras.

### Libraries and Tools / Python

*   [CANard (⭐508)](https://github.com/ericevenchick/canard) - A Python framework for Controller Area Network applications.
*   [Python-OBD (⭐1.1k)](https://github.com/brendan-w/python-OBD) - A Python module for handling realtime sensor data from OBD-II vehicle ports. Works with ELM327 OBD-II adapters, and is fit for the Raspberry Pi.

## [Aug 21 - Aug 27, 2017](/content/2017/34/README.md)

### Presentations

*   [Car Hacking Videos](http://tekeye.uk/automotive/cyber-security/car-hacking-videos) -  A web page with a long list of videos (40+) that are available online related to the topic of car hacking. From a 2007 DEF CON talk on modding engine ECUS and onwards (e.g. the 2017 Keen Security Tesla hack).

## [Aug 14 - Aug 20, 2017](/content/2017/33/README.md)

### Research Papers

*   [A Vulnerability in Modern Automotive Standards and How We Exploited It](https://documents.trendmicro.com/assets/A-Vulnerability-in-Modern-Automotive-Standards-and-How-We-Exploited-It.pdf)

## [Jul 31 - Aug 06, 2017](/content/2017/31/README.md)

### Presentations

*   [State of Automotive Cyber Safety, 2015](https://www.youtube.com/watch?v=g-a20ORka-A) - State of automotive hacking, policy, industry changes, etc. from I Am The Cavalry track at BSides Las Vegas, 2015.
*   [State of Automotive Cyber Safety, 2016](https://www.youtube.com/watch?v=WcObDVy2-1I) - State of automotive hacking, policy, industry changes, etc. from I Am The Cavalry track at BSides Las Vegas, 2016.
*   [How to Hack a Tesla Model S](https://www.youtube.com/watch?v=KX_0c9R4Fng) - DEF CON 23 talk by Marc Rogers and Kevin Mahaffey on hacking a Tesla. Tesla Co-Founder and CTO, JB Straubel, joins them to thank them and present a challenge coin.

### Research Papers

*   [5-Star Automotive Cyber Safety Framework, 2015](https://iamthecavalry.org/5star)

### Websites

*   [I Am The Cavalry](https://www.iamthecavalry.org/) - Global grassroots (eg. volunteer) initiative focused on the intersection of security and human life/public safety issues, such as cars. Participation from security researchers, OEMs, Tier 1s, and many others. Published [Automotive 5-Star Cyber Safety Framework](https://iamthecavalry.org/5star).

### Conferences

*   [U.S. Automotve Cyber Security Summit](http://www.automotivecybersecurity.com/) [European Automotive Cyber Security Summit](https://automotive-cyber-security.iqpc.de/) - Conference series dedicated to automotive cyber security involving many OEMs, Tier 1s, academics, consultants, etc.
*   [escar conference](https://www.escar.info/) - Embedded security in cars. European event has run for over 10 years, and they now have US and Asia events.
*   [IT Security for Vehicles](https://www.vdi-wissensforum.de/en/event/it-security-for-vehicles/) - Conference run by the Association of German Engineers (VDI), with participation from US and European OEMs, Tier 1s, and others.

### Who to Follow

*   Samy Kamkar: Created MySpace Worm, RollJam, OwnStar.
    *   [Twitter](https://twitter.com/samykamkar)
    *   [Website](https://samy.pl)
*   I Am The Cavalry: Global grassroots (eg. volunteer) initiative focused on the intersection of security and human life/public safety issues, such as cars.
    *   [Twitter](https://twitter.com/iamthecavalry)
    *   [Website](https://iamthecavalry.org)
    *   [Discussion Group](https://groups.google.com/forum/#!forum/iamthecavalry)

### Coordinated disclosure / JavaScript

*   [General Motors](https://hackerone.com/gm) on HackerOne - Coordinated disclosure submissions accepted
*   [Tesla Motors](https://bugcrowd.com/tesla) on Bugcrowd - Coordinated disclosure submissions accepted, paid bounties offered

## [Jul 17 - Jul 23, 2017](/content/2017/29/README.md)

### Presentations

*   [Car Hacking 101](https://www.youtube.com/watch?v=P-mzo2X47sg) - Bugcrowd LevelUp 2017 by Alan Mond

### Applications / Episodes

*   [Mazda AIO Tweaks](https://mazdatweaks.com/) - All-in-one installer/uninstaller for many available Mazda MZD Infotainment System tweaks.
*   [mazda\_getInfo (⭐157)](https://github.com/shipcod3/mazda_getInfo) - A PoC that the USB port is an attack surface for a Mazda car's infotainment system and how Mazda hacks are made (known bug in the CMU).

## [Feb 13 - Feb 19, 2017](/content/2017/7/README.md)

### Research Papers

*   [Koscher et al. Experimental Security Analysis of a Modern Automobile, 2010](http://www.autosec.org/pubs/cars-oakland2010.pdf)
*   [Comprehensive Experimental Analyses of Automotive Attack Surfaces, 2011](http://static.usenix.org/events/sec11/tech/full_papers/Checkoway.pdf)
*   [Miller and Valasek](http://illmatics.com/carhacking.html) - Self proclaimed "car hacking the definitive source".
    *   [Adventures in Automotive Networks and Control Units (aka car hacking)](http://illmatics.com/car_hacking.pdf)
    *   [Car Hacking for Poories](http://illmatics.com/car_hacking_poories.pdf)
    *   [A Survey of Remote Automotive Attack Surfaces, 2014](http://illmatics.com/remote%20attack%20surfaces.pdf)
    *   [Remote Compromise of an Unaltered Passenger Vehicle (aka The Jeep Hack), 2015](http://illmatics.com/Remote%20Car%20Hacking.pdf)
    *   [Advanced CAN Message Injection, 2016](http://illmatics.com/can%20message%20injection.pdf)

## [Feb 06 - Feb 12, 2017](/content/2017/6/README.md)

### Applications / Episodes

*   [metasploit](https://community.rapid7.com/community/transpo-security/blog/2017/02/02/exiting-the-matrix) - The popular metasploit framework now supports Hardware Bridge sessions, that extend the framework's capabilites onto hardware devices such as socketcan and SDR radios.

## [Jan 30 - Feb 05, 2017](/content/2017/5/README.md)

### Courses

*   [Udacity's Self Driving Car Engineer Course (⭐6.2k)](https://github.com/udacity/self-driving-car) - The content for Udacity's self driving car software engineer course. The actual course on Udacity's website is [here](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013).

### Miscellaneous / Episodes

*   [Open Vehicle Monitoring System (⭐312)](https://github.com/openvehicles/Open-Vehicle-Monitoring-System) - A community project building a hardware module for your car, a server to talk to it, and a mobile app to talk to the server, in order to allow developers and enthusiasts to add more functionality to their car and control it remotely.
*   [Open Source Car Control Project (⭐979)](https://github.com/PolySync/OSCC) - The Open Source Car Control Project is a hardware and software project detailing the conversion of a late model vehicle into an autonomous driving research and development vehicle.

### Applications / Episodes

*   [openalpr (⭐11k)](https://github.com/openalpr/openalpr) - An open source Automatic License Plate Recognition library written in C++ with bindings in C#, Java, Node.js, Go, and Python.

## [Oct 24 - Oct 30, 2016](/content/2016/43/README.md)

### Articles

*   [Developments in Car Hacking](https://www.sans.org/reading-room/whitepapers/ICS/developments-car-hacking-36607) - via the SANS Reading Room, Currie's paper analyses the risks and perils of smart vehicle technology.

### Presentations

*   [Ken Munro & Dave Lodge - Hacking the Mitsubishi Outlander & IOT](https://www.youtube.com/watch?v=YLBQdO6a5IQ) - talk from BSides Manchester 2016 by Ken and Dave of [Pen Test Partners](#who-to-follow)

### Websites

*   [canbushack: Hack Your Car](http://www.canbushack.com/blog/index.php) - course on Vehicle Hacking methodology.
*   [Carloop Community](https://community.carloop.io/) - Community of people interested in car hacking and connecting vehicles to the cloud.

### Who to Follow

*   Ken Munro: British researcher, works at Pen Test Partners; major interest in vehicle security
    *   [Twitter](https://twitter.com/TheKenMunroShow)
*   Pen Test Partners: British penetration testing firm; several posts concern their disclosed car security vulns
    *   [Twitter](https://twitter.com/pentestpartners)
    *   [Website](https://www.pentestpartners.com/blog)

### Podcasts and Episodes / Podcasts

*   [SANS Internet Storm Center](https://isc.sans.edu/) - the ISC run a regular podcast going into the latest vulnerabilities and security news.

## [Oct 03 - Oct 09, 2016](/content/2016/40/README.md)

### Presentations

*   [Can You Trust Autonomous Vehicles?](https://www.youtube.com/watch?v=orWqKWvIW_0) - DEFCON 24 talk by Jianhao Liu, Chen Yan, Wenyuan Xu

## [Sep 19 - Sep 25, 2016](/content/2016/38/README.md)

### Miscellaneous / Episodes

*   [CANBadger](https://gutenshit.github.io/CANBadger/) - A tool for reverse-engineering and testing automotive systems. The CANBadger consists of both hardware and software. The main interface is a LPC1768/LPC1769 processor mounted on a custom PCB, which offers two CAN interfaces, SD Card, a blinky LED, some GPIO pins, power supply for peripherals and the ethernet port.
*   [CANSPY](https://bitbucket.org/jcdemay/canspy) - A platform giving security auditors to audit CAN devices. It can be used to block, forward or modify CAN frames on the fly autonomously as well as interactively.
*   [CANBus Triple](https://canb.us/) - General purpose Controller Area Network swiss army knife and development platform.
*   [USBtin](http://www.fischl.de/usbtin/) - USBtin is a simple USB to CAN interface. It can monitor CAN busses and transmit CAN messages. USBtin implements the USB CDC class and creates a virtual comport on the host computer.

### Applications / Episodes

*   [CANToolz (⭐307)](https://github.com/eik00d/CANToolz) - CANToolz is a framework for analysing CAN networks and devices. It is based on several modules which can be assembled in a pipeline.
*   [BUSMASTER](https://rbei-etas.github.io/busmaster/) -An Open Source tool to simulate, analyze and test data bus systems such as CAN, LIN, FlexRay.

## [Sep 05 - Sep 11, 2016](/content/2016/36/README.md)

### Miscellaneous / Episodes

*   [Carloop](https://www.carloop.io/) - Open source development kit that makes it easy to connect your car to the Internet. Lowest cost car hacking tool that is compatible with SocketCAN and can-utils.  No OBD-II to serial cable required.

### Libraries and Tools / C

*   [vircar (⭐148)](https://github.com/dn5/vircar) - a Virtual car userspace that sends CAN messages based on SocketCAN

### Libraries and Tools / Go

*   [CAN Simulator (⭐65)](https://github.com/carloop/simulator-program) - A Go based CAN simulator for the Raspberry Pi to be used with PiCAN2 or the open source [CAN Simulator board (⭐176)](https://github.com/carloop/simulator)

## [Jul 25 - Jul 31, 2016](/content/2016/30/README.md)

### Articles

*   [Troy Hunt on Controlling Nissans](https://www.troyhunt.com/controlling-vehicle-features-of-nissan/) - Troy Hunt goes into controlling Nissan vehicles.
*   [Tesla hackers explain how they did it at Defcon](http://www.cnet.com/roadshow/news/tesla-hackers-explain-how-they-did-it-at-def-con-23/) - Overview of DEFCON 23 presentation on hacking into Tesla cars.
*   [Anatomy of the Rolljam Wireless Car Hack](http://makezine.com/2015/08/11/anatomy-of-the-rolljam-wireless-car-hack/) - Overview of the RollJam rolling code exploitation device.
*   [IOActive's Tools and Data](http://blog.ioactive.com/2013/08/car-hacking-content.html) - Chris Valasek and Charlie Miller release some of their tools and data for hacking into vehicles in an effort to get more people into vehicle security research.

### Presentations

*   ["Drive It Like You Hacked It" from DEFCON 23](https://samy.pl/defcon2015/) - A talk and slides from Samy Kamkar's DEFCON 23/2015 talk that includes hacking garages, exploiting automotive mobile apps, and breaking rolling codes to unlock any vehicle with low cost tools.
*   [Samy Kamkar on Hacking Vehicles with OnStar](https://www.youtube.com/watch?v=3olXUbS-prU\&feature=youtu.be) - Samy Kamkar, the prolific hacker behind the Samy worm on MySpace, explores hacking into vehicles with OnStar systems.
*   [Adventures in Automotive Networks and Control Units](https://www.youtube.com/watch?v=n70hIu9lcYo) - DEFCON 21 talk by Chris Valasek and Charlie Miller on automotive networks.

### Websites

*   [DEFCON Car Hacking Village](http://www.carhackingvillage.com/) - Car Hacking exercises from DEFCON 24.
*   [OWASP Internet of Things Project](https://www.owasp.org/index.php/OWASP_Internet_of_Things_Project#tab=Community) - OWASP's project to secure IoT, from cars to medical devices and beyond.

### Who to Follow

*   Chris Valasek: Security Lead at [UberATC](#companies-and-jobs)
    *   [Twitter](https://twitter.com/nudehaberdasher)
    *   [Website](http://chris.illmatics.com/about.html)
*   Charlie Miller: Hacked the first Apple iPhone, now does car security.
    *   [Twitter](https://twitter.com/0xcharlie)
*   Justin Seitz: Author of Black Hat Python (No Starch Press).
    *   [Twitter](https://twitter.com/jms_dot_py)
*   Troy Hunt: Pluralsight author. Microsoft Regional Director and MVP for Developer Security. Creator of [haveibeenpwned](https://haveibeenpwned.com/).
    *   [Twitter](https://twitter.com/troyhunt)
    *   [Website](https://www.troyhunt.com/)
*   OpenGarages: Initiative to created Vehicle Research Labs around the world.
    *   [Twitter](https://twitter.com/opengarages)
    *   [Website](http://opengarages.org/index.php/Main_Page)
*   Hackaday: Collaborative project hosting for hackers - there are frequently car projects on here.
    *   [Twitter](https://twitter.com/hackaday)

### Podcasts and Episodes / Podcasts

*   [Security Ledger](https://soundcloud.com/securityledger) - A podcast focusing on interviewing security experts about topics related to security.

### Podcasts and Episodes / Episodes

*   [Big Bugs Podcast Episode 1: Auto Bugs - Critical Vulns found in Cars with Jason Haddix](https://blog.bugcrowd.com/big-bugs-podcast-episode-1) - Jason Haddix explores major vulnerabilities found in cars.
*   [Hacking Under the Hood and Into Your Car](http://www.npr.org/2013/08/02/208270026/hacking-under-the-hood-and-into-your-car) - Chris Valasek and Charlie Miller discuss with NPR how they were able to hack into vehicles.
*   [Hacking Connected Vehicles with Chris Valasek of IOActive](https://soundcloud.com/securityledger/chris-valasek-of-ioactive) - Chris Valasek talks about hacking into connected vehicles.

### Miscellaneous / Episodes

*   [Freematics OBD-II Telematics Kit](http://freematics.com/pages/products/arduino-telematics-kit-3/) - Arduino-based OBD-II Bluetooth adapter kit has both an OBD-II device and a data logger, and it comes with GPS, an accelerometer and gyro, and temperature sensors.
*   [GoodThopter12](http://goodfet.sourceforge.net/hardware/goodthopter12/) - Crafted by a well-known hardware hacker, this board is a general board that can be used for exploration of automotive networks.
*   [USB2CAN](http://www.8devices.com/products/usb2can/) - Cheap USB to CAN connector that will register a device on linux that you can use to get data from a CAN network.
*   [Red Pitaya](http://redpitaya.com/) - Replaces expensive measurement tools such as oscilloscopes, signal generators, and spectrum analyzers. Red Pitaya has LabView and Matlab interfaces, and you can write your own tools and applications for it. It even supports extensions for things like Arduino shields.
*   [ChipWhisperer](http://newae.com/tools/chipwhisperer/) - A system for side-channel attacks, such as power analysis and clock glitching.
*   [HackerSDR](https://greatscottgadgets.com/hackrf/) - A Software Defined Radio peripheral capable of transmission or reception of radio signals from 1 MHz to 6 GHz. Designed to enable test and development of modern and next generation radio technologies.

### Applications / Episodes

*   [Kayak](http://kayak.2codeornot2code.org/) - Java application for CAN bus diagnosis and monitoring.
*   [UDSim (⭐296)](https://github.com/zombieCraig/UDSim/) - GUI tool that can monitor a CAN bus and automatically learn the devices attached to it by watching communications.
*   [RomRaider](http://www.romraider.com/) - An open source tuning suite for the Subaru engine control unit that lets you view and log data and tune the ECU.

### Libraries and Tools / C

*   [SocketCAN Utils (⭐2.5k)](https://github.com/linux-can/can-utils) - Userspace utilites for SocketCAN on Linux.

### Libraries and Tools / Python

*   [Caring Caribou (⭐769)](https://github.com/CaringCaribou/caringcaribou/) - Intended to be the *nmap of vehicle security*.
*   [c0f (⭐87)](https://github.com/zombieCraig/c0f/) - A fingerprinting tool for CAN communications that can be used to find a specific signal on a CAN network when testing interactions with a vehicle.

### Libraries and Tools / Go

*   [CANNiBUS (⭐112)](https://github.com/Hive13/CANiBUS/) - A Go server that allows a room full of researchers to simultaneously work on the same vehicle, whether for instructional purposes or team reversing sessions.

### Libraries and Tools / JavaScript

*   [NodeJS extension to SocketCAN (⭐226)](https://github.com/sebi2k1/node-can) - Allows you to communicate over CAN networks with simple JavaScript functions.
*   [Tesla](https://www.tesla.com/careers/search#/filter/?keyword=security\&department=1) - Tesla hires security professionals for a variety of roles, particularly securing their vehicles.
*   [Intrepid Control Systems](https://www.intrepidcs.com/jobs/) - Embedded security company building tools for reversing vehicles.
*   [Rapid7](https://www.rapid7.com/company/careers.jsp) - Rapid7 does work in information, computer, and embedded security.
*   [IOActive](http://www.ioactive.com/) - Security consulting firm that does work on pentesting hardware and embedded systems.

### Coordinated disclosure / JavaScript

*   Security
    *   [Application Security (⭐6.4k)](https://github.com/paragonie/awesome-appsec)
    *   [Security (⭐13k)](https://github.com/sbilly/awesome-security)
    *   [Capture the Flag (⭐10k)](https://github.com/apsdehal/awesome-ctf)
    *   [Malware Analysis (⭐12k)](https://github.com/rshipp/awesome-malware-analysis)
    *   [Android Security (⭐8.3k)](https://github.com/ashishb/android-security-awesome)
    *   [Hacking (⭐14k)](https://github.com/carpedm20/awesome-hacking)
    *   [Honeypots (⭐8.8k)](https://github.com/paralax/awesome-honeypots)
    *   [Incident Response (⭐7.8k)](https://github.com/meirwah/awesome-incident-response)
*   Meta
    *   [awesome (⭐342k)](https://github.com/sindresorhus/awesome)
    *   [lists (⭐10k)](https://github.com/jnv/lists)