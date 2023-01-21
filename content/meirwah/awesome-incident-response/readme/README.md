# Awesome Incident Response Overview

A curated list of tools for incident response

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/meirwah/awesome-incident-response/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 meirwah/awesome-incident-response](https://github.com/meirwah/awesome-incident-response) · ⭐ 5.9K · 🏷️ Security

[ [Daily](/content/meirwah/awesome-incident-response/README.md) / [Weekly](/content/meirwah/awesome-incident-response/week/README.md) / Overview ]

---

# Awesome Incident Response [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of tools and resources for security incident response, aimed to help security analysts and [DFIR](http://www.acronymfinder.com/Digital-Forensics%2c-Incident-Response-%28DFIR%29.html) teams.

Digital Forensics and Incident Response (DFIR) teams are groups of people in an organization responsible for managing the response to a security incident, including gathering evidence of the incident, remediating its effects, and implementing controls to prevent the incident from recurring in the future.

## Contents

*   [Adversary Emulation](#adversary-emulation)
*   [All-In-One Tools](#all-in-one-tools)
*   [Books](#books)
*   [Communities](#communities)
*   [Disk Image Creation Tools](#disk-image-creation-tools)
*   [Evidence Collection](#evidence-collection)
*   [Incident Management](#incident-management)
*   [Knowledge Bases](#knowledge-bases)
*   [Linux Distributions](#linux-distributions)
*   [Linux Evidence Collection](#linux-evidence-collection)
*   [Log Analysis Tools](#log-analysis-tools)
*   [Memory Analysis Tools](#memory-analysis-tools)
*   [Memory Imaging Tools](#memory-imaging-tools)
*   [OSX Evidence Collection](#osx-evidence-collection)
*   [Other Lists](#other-lists)
*   [Other Tools](#other-tools)
*   [Playbooks](#playbooks)
*   [Process Dump Tools](#process-dump-tools)
*   [Sandboxing/Reversing Tools](#sandboxingreversing-tools)
*   [Scanner Tools](#scanner-tools)
*   [Timeline Tools](#timeline-tools)
*   [Videos](#videos)
*   [Windows Evidence Collection](#windows-evidence-collection)

## IR Tools Collection

### Adversary Emulation

*   [APTSimulator (⭐2.1k)](https://github.com/NextronSystems/APTSimulator) - Windows Batch script that uses a set of tools and output files to make a system look as if it was compromised.
*   [Atomic Red Team (ART) (⭐7k)](https://github.com/redcanaryco/atomic-red-team) - Small and highly portable detection tests mapped to the MITRE ATT\&CK Framework.
*   [AutoTTP (⭐231)](https://github.com/jymcheong/AutoTTP) - Automated Tactics Techniques & Procedures. Re-running complex sequences manually for regression tests, product evaluations, generate data for researchers.
*   [Blue Team Training Toolkit (BT3)](https://www.bt3.no/) - Software for defensive security training, which will bring your network analysis training sessions, incident response drills and red team engagements to a new level.
*   [Caldera (⭐4k)](https://github.com/mitre/caldera) - Automated adversary emulation system that performs post-compromise adversarial behavior within Windows Enterprise networks. It generates plans during operation using a planning system and a pre-configured adversary model based on the Adversarial Tactics, Techniques & Common Knowledge (ATT\&CK™) project.
*   [DumpsterFire (⭐894)](https://github.com/TryCatchHCF/DumpsterFire) - Modular, menu-driven, cross-platform tool for building repeatable, time-delayed, distributed security events. Easily create custom event chains for Blue Team drills and sensor /   alert mapping. Red Teams can create decoy incidents, distractions, and lures to support and scale their operations.
*   [Metta (⭐983)](https://github.com/uber-common/metta) - Information security preparedness tool to do adversarial simulation.
*   [Network Flight Simulator (⭐822)](https://github.com/alphasoc/flightsim) - Lightweight utility used to generate malicious network traffic and help security teams to evaluate security controls and network visibility.
*   [Red Team Automation (RTA) (⭐934)](https://github.com/endgameinc/RTA) - RTA provides a framework of scripts designed to allow blue teams to test their detection capabilities against malicious tradecraft, modeled after MITRE ATT\&CK.
*   [RedHunt-OS (⭐1.1k)](https://github.com/redhuntlabs/RedHunt-OS) - Virtual machine for adversary emulation and threat hunting.

### All-In-One Tools

*   [Belkasoft Evidence Center](https://belkasoft.com/ec) -  The toolkit will quickly extract digital evidence from multiple sources by analyzing hard drives, drive images, memory dumps, iOS, Blackberry and Android backups, UFED, JTAG and chip-off dumps.
*   [CimSweep (⭐614)](https://github.com/PowerShellMafia/CimSweep) - Suite of CIM/WMI-based tools that enable the ability to perform incident response and hunting operations remotely across all versions of Windows.
*   [CIRTkit (⭐130)](https://github.com/byt3smith/CIRTKit) - CIRTKit is not just a collection of tools, but also a framework to aid in the ongoing unification of Incident Response and Forensics investigation processes.
*   [Cyber Triage](http://www.cybertriage.com) - Cyber Triage remotely collects and analyzes endpoint data to help determine if it is compromised.  It’s agentless approach and focus on ease of use and automation allows companies to respond without major infrastructure changes and without a team of forensics experts.  Its results are used to decide if the system should be erased or investigated further.
*   [Doorman (⭐592)](https://github.com/mwielgoszewski/doorman) - osquery fleet manager that allows remote management of osquery configurations retrieved by nodes. It takes advantage of osquery's TLS configuration, logger, and distributed read/write endpoints, to give administrators visibility across a fleet of devices with minimal overhead and intrusiveness.
*   [Falcon Orchestrator (⭐179)](https://github.com/CrowdStrike/falcon-orchestrator) - Extendable Windows-based application that provides workflow automation, case management and security response functionality.
*   [Flare (⭐4.4k)](https://github.com/fireeye/flare-vm) - A fully customizable, Windows-based security distribution for malware analysis, incident response, penetration testing.
*   [Fleetdm (⭐1k)](https://github.com/fleetdm/fleet) - State of the art host monitoring platform tailored for security experts. Leveraging Facebook's battle-tested osquery project, Fleetdm delivers continuous updates, features and fast answers to big questions.
*   [GRR Rapid Response (⭐4.3k)](https://github.com/google/grr) - Incident response framework focused on remote live forensics. It consists of a python agent (client) that is installed on target systems, and a python server infrastructure that can manage and talk to the agent. Besides the included Python API client, [PowerGRR (⭐54)](https://github.com/swisscom/PowerGRR) provides an API client library in PowerShell working on Windows, Linux and macOS for GRR automation and scripting.
*   [IRIS (⭐586)](https://github.com/dfir-iris/iris-web) - IRIS is a web collaborative platform for incident response analysts allowing to share investigations at a technical level.
*   [Kuiper (⭐569)](https://github.com/DFIRKuiper/Kuiper) - Digital Forensics Investigation Platform
*   [Limacharlie](https://www.limacharlie.io/) - Endpoint security platform composed of a collection of small projects all working together that gives you a cross-platform (Windows, OSX, Linux, Android and iOS) low-level environment for managing and pushing additional modules into memory to extend its functionality.
*   [Matano (⭐630)](https://github.com/matanolabs/matano): Open source serverless security lake platform on AWS that lets you ingest, store, and analyze petabytes of security data into an Apache Iceberg data lake and run realtime Python detections as code.
*   [MozDef (⭐2.2k)](https://github.com/mozilla/MozDef) - Automates the security incident handling process and facilitate the real-time activities of incident handlers.
*   [MutableSecurity (⭐37)](https://github.com/MutableSecurity/mutablesecurity) - CLI program for automating the setup, configuration, and use of cybersecurity solutions.
*   [nightHawk (⭐595)](https://github.com/biggiesmallsAG/nightHawkResponse) - Application built for asynchronous forensic data presentation using ElasticSearch as the backend. It's designed to ingest Redline collections.
*   [Open Computer Forensics Architecture](http://sourceforge.net/projects/ocfa/) - Another popular distributed open-source computer forensics framework. This framework was built on Linux platform and uses postgreSQL database for storing data.
*   [osquery](https://osquery.io/) - Easily ask questions about your Linux and macOS infrastructure using a SQL-like query language; the provided *incident-response pack* helps you detect and respond to breaches.
*   [Redline](https://www.fireeye.com/services/freeware/redline.html) - Provides host investigative capabilities to users to find signs of malicious activity through memory and file analysis, and the development of a threat assessment profile.
*   [SOC Multi-tool (⭐99)](https://github.com/zdhenard42/SOC-Multitool) - A powerful and user-friendly browser extension that streamlines investigations for security professionals.
*   [The Sleuth Kit & Autopsy](http://www.sleuthkit.org) - Unix and Windows based tool which helps in forensic analysis of computers. It comes with various tools which helps in digital forensics. These tools help in analyzing disk images, performing in-depth analysis of file systems, and various other things.
*   [TheHive](https://thehive-project.org/) - Scalable 3-in-1 open source and free solution designed to make life easier for SOCs, CSIRTs, CERTs and any information security practitioner dealing with security incidents that need to be investigated and acted upon swiftly.
*   [Velociraptor (⭐1.6k)](https://github.com/Velocidex/velociraptor) - Endpoint visibility and collection tool
*   [X-Ways Forensics](http://www.x-ways.net/forensics/) - Forensics tool for Disk cloning and imaging. It can be used to find deleted files and disk analysis.
*   [Zentral (⭐661)](https://github.com/zentralopensource/zentral) - Combines osquery's powerful endpoint inventory features with a flexible notification and action framework. This enables one to identify and react to changes on OS X and Linux clients.

### Books

*   [Applied Incident Response](https://www.amazon.com/Applied-Incident-Response-Steve-Anson/dp/1119560268/) - Steve Anson's book on Incident Response.
*   [Art of Memory Forensics](https://www.amazon.com/Art-Memory-Forensics-Detecting-Malware/dp/1118825098/) - Detecting Malware and Threats in Windows, Linux, and Mac Memory.
*   [Crafting the InfoSec Playbook: Security Monitoring and Incident Response Master Plan](https://www.amazon.com/Crafting-InfoSec-Playbook-Security-Monitoring/dp/1491949406) - by Jeff Bollinger, Brandon Enright and Matthew Valites.
*   [Digital Forensics and Incident Response: Incident response techniques and procedures to respond to modern cyber threats](https://www.amazon.com/Digital-Forensics-Incident-Response-techniques/dp/183864900X) - by Gerard Johansen.
*   [Introduction to DFIR](https://medium.com/@sroberts/introduction-to-dfir-d35d5de4c180/) - By Scott J. Roberts.
*   [Incident Response & Computer Forensics, Third Edition](https://www.amazon.com/Incident-Response-Computer-Forensics-Third/dp/0071798684/) - The definitive guide to incident response.
*   [Incident Response Techniques for Ransomware Attacks](https://www.amazon.com/Incident-Response-Techniques-Ransomware-Attacks/dp/180324044X) - A great guide to build an incident response strategy for ransomware attacks. By Oleg Skulkin.
*   [Incident Response with Threat Intelligence](https://www.amazon.com/Incident-response-Threat-Intelligence-intelligence-based/dp/1801072957) - Great reference to build an incident response plan based also on Threat Intelligence. By Roberto Martinez.
*   [Intelligence-Driven Incident Response](https://www.amazon.com/Intelligence-Driven-Incident-Response-Outwitting-Adversary-ebook-dp-B074ZRN5T7/dp/B074ZRN5T7) - By Scott J. Roberts, Rebekah Brown.
*   [Operator Handbook: Red Team + OSINT + Blue Team Reference](https://www.amazon.com/Operator-Handbook-Team-OSINT-Reference/dp/B085RR67H5/) - Great reference for incident responders.
*   [Practical Memory Forensics](https://www.amazon.com/Practical-Memory-Forensics-Jumpstart-effective/dp/1801070334) - The definitive guide to practice memory forensics. By Svetlana Ostrovskaya and Oleg Skulkin.
*   [The Practice of Network Security Monitoring: Understanding Incident Detection and Response](http://www.amazon.com/gp/product/1593275099) - Richard Bejtlich's book on IR.

### Communities

*   [Digital Forensics Discord Server](https://discordapp.com/invite/JUqe9Ek) - Community of 8,000+ working professionals from Law Enforcement, Private Sector, and Forensic Vendors. Additionally, plenty of students and hobbyists! Guide [here](https://aboutdfir.com/a-beginners-guide-to-the-digital-forensics-discord-server/).
*   [SANS DFIR mailing list](https://lists.sans.org/mailman/listinfo/dfir) - Mailing list by SANS for DFIR.
*   [Slack DFIR channel](https://dfircommunity.slack.com) - Slack DFIR Communitiy channel - [Signup here](https://start.paloaltonetworks.com/join-our-slack-community).

### Disk Image Creation Tools

*   [AccessData FTK Imager](http://accessdata.com/product-download/?/support/adownloads#FTKImager) - Forensics tool whose main purpose is to preview recoverable data from a disk of any kind. FTK Imager can also acquire live memory and paging file on 32bit and 64bit systems.
*   [Bitscout (⭐413)](https://github.com/vitaly-kamluk/bitscout) - Bitscout by Vitaly Kamluk helps you build your fully-trusted customizable LiveCD/LiveUSB image to be used for remote digital forensics (or perhaps any other task of your choice). It is meant to be transparent and monitorable by the owner of the system, forensically sound, customizable and compact.
*   [GetData Forensic Imager](http://www.forensicimager.com/) - Windows based program that will acquire, convert, or verify a forensic image in one of the following common forensic file formats.
*   [Guymager](http://guymager.sourceforge.net) - Free forensic imager for media acquisition on Linux.
*   [Magnet ACQUIRE](https://www.magnetforensics.com/magnet-acquire/) - ACQUIRE by Magnet Forensics allows various types of disk acquisitions to be performed on Windows, Linux, and OS X as well as mobile operating systems.

### Evidence Collection

*   [artifactcollector (⭐179)](https://github.com/forensicanalysis/artifactcollector) - The artifactcollector project provides a software that collects forensic artifacts on systems.
*   [bulk\_extractor (⭐758)](https://github.com/simsong/bulk_extractor) - Computer forensics tool that scans a disk image, a file, or a directory of files and extracts useful information without parsing the file system or file system structures. Because of ignoring the file system structure, the program distinguishes itself in terms of speed and thoroughness.
*   [Cold Disk Quick Response (⭐315)](https://github.com/rough007/CDQR) - Streamlined list of parsers to quickly analyze a forensic image file (`dd`, E01, `.vmdk`, etc) and output nine reports.
*   [CyLR (⭐521)](https://github.com/orlikoski/CyLR) - The CyLR tool collects forensic artifacts from hosts with NTFS file systems quickly, securely and minimizes impact to the host.
*   [Forensic Artifacts (⭐813)](https://github.com/ForensicArtifacts/artifacts) - Digital Forensics Artifact Repository
*   [ir-rescue (⭐406)](https://github.com/diogo-fernan/ir-rescue) - Windows Batch script and a Unix Bash script to comprehensively collect host forensic data during incident response.
*   [Live Response Collection](https://www.brimorlabs.com/tools/) - Automated tool that collects volatile data from Windows, OSX, and \*nix based operating systems.
*   [Margarita Shotgun (⭐217)](https://github.com/ThreatResponse/margaritashotgun) - Command line utility (that works with or without Amazon EC2 instances) to parallelize remote memory acquisition.
*   [UAC (⭐312)](https://github.com/tclahr/uac) - UAC (Unix-like Artifacts Collector) is a Live Response collection script for Incident Response that makes use of native binaries and tools to automate the collection of AIX, Android, ESXi, FreeBSD, Linux, macOS, NetBSD, NetScaler, OpenBSD and Solaris systems artifacts.

### Incident Management

*   [Catalyst (⭐144)](https://github.com/SecurityBrewery/catalyst) - A free SOAR system that helps to automate alert handling and incident response processes.
*   [CyberCPR](https://www.cybercpr.com) - Community and commercial incident management tool with Need-to-Know built in to support GDPR compliance while handling sensitive incidents.
*   [Cyphon](https://medevel.com/cyphon/) - Cyphon eliminates the headaches of incident management by streamlining a multitude of related tasks through a single platform. It receives, processes and triages events to provide an all-encompassing solution for your analytic workflow — aggregating data, bundling and prioritizing alerts, and empowering analysts to investigate and document incidents.
*   [CORTEX XSOAR](https://www.paloaltonetworks.com/cortex/xsoar) - Paloalto security orchestration, automation and response platform with full Incident lifecycle management and many integrations to enhance automations.
*   [DFTimewolf (⭐225)](https://github.com/log2timeline/dftimewolf) - A framework for orchestrating forensic collection, processing and data export.
*   [DFIRTrack (⭐409)](https://github.com/dfirtrack/dfirtrack) - Incident Response tracking application handling one or more incidents via cases and tasks with a lot of affected systems and artifacts.
*   [Fast Incident Response (FIR) (⭐1.5k)](https://github.com/certsocietegenerale/FIR/) - Cybersecurity incident management platform designed with agility and speed in mind. It allows for easy creation, tracking, and reporting of cybersecurity incidents and is useful for CSIRTs, CERTs and SOCs alike.
*   [RTIR](https://www.bestpractical.com/rtir/) - Request Tracker for Incident Response (RTIR) is the premier open source incident handling system targeted for computer security teams. We worked with over a dozen CERT and CSIRT teams around the world to help you handle the ever-increasing volume of incident reports. RTIR builds on all the features of Request Tracker.
*   [Sandia Cyber Omni Tracker (SCOT) (⭐233)](https://github.com/sandialabs/scot) - Incident Response collaboration and knowledge capture tool focused on flexibility and ease of use. Our goal is to add value to the incident response process without burdening the user.
*   [Shuffle (⭐861)](https://github.com/frikky/Shuffle) - A general purpose security automation platform focused on accessibility.
*   [threat\_note (⭐409)](https://github.com/defpoint/threat_note) - Lightweight investigation notebook that allows security researchers the ability to register and retrieve indicators related to their research.
*   [Zenduty](https://www.zenduty.com) - Zenduty is a novel incident management platform providing end-to-end incident alerting, on-call management and response orchestration, giving teams greater control and automation over the incident management lifecycle.

### Knowledge Bases

*   [Digital Forensics Artifact Knowledge Base (⭐46)](https://github.com/ForensicArtifacts/artifacts-kb) - Digital Forensics Artifact Knowledge Base
*   [Windows Events Attack Samples (⭐1.8k)](https://github.com/sbousseaden/EVTX-ATTACK-SAMPLES) - Windows Events Attack Samples
*   [Windows Registry Knowledge Base (⭐114)](https://github.com/libyal/winreg-kb) - Windows Registry Knowledge Base

### Linux Distributions

*   [The Appliance for Digital Investigation and Analysis (ADIA)](https://forensics.cert.org/#ADIA) - VMware-based appliance used for digital investigation and acquisition and is built entirely from public domain software. Among the tools contained in ADIA are Autopsy, the Sleuth Kit, the Digital Forensics Framework, log2timeline, Xplico, and Wireshark. Most of the system maintenance uses Webmin. It is designed for small-to-medium sized digital investigations and acquisitions. The appliance runs under Linux, Windows, and Mac OS. Both i386 (32-bit) and x86\_64 (64-bit) versions are available.
*   [Computer Aided Investigative Environment (CAINE)](http://www.caine-live.net/index.html) - Contains numerous tools that help investigators during their analysis, including forensic evidence collection.
*   [CCF-VM (⭐448)](https://github.com/rough007/CCF-VM) - CyLR CDQR Forensics Virtual Machine (CCF-VM): An all-in-one solution to parsing collected data, making it easily searchable with built-in common searches, enable searching of single and multiple hosts simultaneously.
*   [Digital Evidence & Forensics Toolkit (DEFT)](http://www.deftlinux.net/) - Linux distribution made for computer forensic evidence collection. It comes bundled with the Digital Advanced Response Toolkit (DART) for Windows. A light version of DEFT, called DEFT Zero, is also available, which is focused primarily on forensically sound evidence collection.
*   [NST - Network Security Toolkit](https://sourceforge.net/projects/nst/files/latest/download?source=files) - Linux distribution that includes a vast collection of best-of-breed open source network security applications useful to the network security professional.
*   [PALADIN](https://sumuri.com/software/paladin/) - Modified Linux distribution to perform various forensics task in a forensically sound manner. It comes with many open source forensics tools included.
*   [Security Onion (⭐3k)](https://github.com/Security-Onion-Solutions/security-onion) - Special Linux distro aimed at network security monitoring featuring advanced analysis tools.
*   [SANS Investigative Forensic Toolkit (SIFT) Workstation](http://digital-forensics.sans.org/community/downloads) - Demonstrates that advanced incident response capabilities and deep dive digital forensic techniques to intrusions can be accomplished using cutting-edge open-source tools that are freely available and frequently updated.

### Linux Evidence Collection

*   [FastIR Collector Linux (⭐153)](https://github.com/SekoiaLab/Fastir_Collector_Linux) - FastIR for Linux collects different artifacts on live Linux and records the results in CSV files.

### Log Analysis Tools

*   [AppCompatProcessor (⭐163)](https://github.com/mbevilacqua/appcompatprocessor) - AppCompatProcessor has been designed to extract additional value from enterprise-wide AppCompat / AmCache data beyond the classic stacking and grepping techniques.
*   [APT Hunter (⭐827)](https://github.com/ahmedkhlief/APT-Hunter) - APT-Hunter is Threat Hunting tool for windows event logs.
*   [Chainsaw (⭐1.8k)](https://github.com/countercept/chainsaw) - Chainsaw provides a powerful ‘first-response’ capability to quickly identify threats within Windows event logs.
*   [Event Log Explorer](https://eventlogxp.com/) - Tool developed to quickly analyze log files and other data.
*   [Event Log Observer](https://lizard-labs.com/event_log_observer.aspx) - View, analyze and monitor events recorded in Microsoft Windows event logs with this GUI tool.
*   [Hayabusa (⭐960)](https://github.com/Yamato-Security/hayabusa) - Hayabusa is a Windows event log fast forensics timeline generator and threat hunting tool created by the Yamato Security group in Japan.
*   [Kaspersky CyberTrace](https://support.kaspersky.com/13850) - Threat intelligence fusion and analysis tool that integrates threat data feeds with SIEM solutions. Users can immediately leverage threat intelligence for security monitoring and incident report (IR) activities in the workflow of their existing security operations.
*   [Log Parser Lizard](https://lizard-labs.com/log_parser_lizard.aspx) - Execute SQL queries against structured log data: server logs, Windows Events, file system, Active Directory, log4net logs, comma/tab separated text, XML or JSON files. Also provides a GUI to Microsoft LogParser 2.2 with powerful UI elements: syntax editor, data grid, chart, pivot table, dashboard, query manager and more.
*   [Lorg (⭐203)](https://github.com/jensvoid/lorg) - Tool for advanced HTTPD logfile security analysis and forensics.
*   [Logdissect (⭐125)](https://github.com/dogoncouch/logdissect) - CLI utility and Python API for analyzing log files and other data.
*   [LogonTracer (⭐2.2k)](https://github.com/JPCERTCC/LogonTracer) - Tool to investigate malicious Windows logon by visualizing and analyzing Windows event log.
*   [Sigma (⭐6k)](https://github.com/SigmaHQ/sigma) - Generic signature format for SIEM systems already containing an extensive ruleset.
*   [StreamAlert (⭐2.7k)](https://github.com/airbnb/streamalert) - Serverless, real-time log data analysis framework, capable of ingesting custom data sources and triggering alerts using user-defined logic.
*   [SysmonSearch (⭐378)](https://github.com/JPCERTCC/SysmonSearch) - SysmonSearch makes Windows event log analysis more effective and less time consuming by aggregation of event logs.
*   [WELA (⭐492)](https://github.com/Yamato-Security/WELA) - Windows Event Log Analyzer aims to be the Swiss Army knife for Windows event logs.
*   [Zircolite (⭐432)](https://github.com/wagga40/Zircolite) - A standalone and fast SIGMA-based detection tool for EVTX or JSON.

### Memory Analysis Tools

*   [AVML (⭐604)](https://github.com/microsoft/avml) - A portable volatile memory acquisition tool for Linux.
*   [Evolve (⭐252)](https://github.com/JamesHabben/evolve) - Web interface for the Volatility Memory Forensics Framework.
*   [inVtero.net (⭐265)](https://github.com/ShaneK2/inVtero.net) - Advanced memory analysis for Windows x64 with nested hypervisor support.
*   [LiME (⭐1.4k)](https://github.com/504ensicsLabs/LiME) - Loadable Kernel Module (LKM), which allows the acquisition of volatile memory from Linux and Linux-based devices, formerly called DMD.
*   [MalConfScan (⭐441)](https://github.com/JPCERTCC/MalConfScan) - MalConfScan is a Volatility plugin extracts configuration data of known malware. Volatility is an open-source memory forensics framework for incident response and malware analysis. This tool searches for malware in memory images and dumps configuration data. In addition, this tool has a function to list strings to which malicious code refers.
*   [Memoryze](https://www.fireeye.com/services/freeware/memoryze.html) - Free memory forensic software that helps incident responders find evil in live memory. Memoryze can acquire and/or analyze memory images, and on live systems, can include the paging file in its analysis.
*   [Memoryze for Mac](https://www.fireeye.com/services/freeware/memoryze.html) - Memoryze for Mac is Memoryze but then for Macs. A lower number of features, however.
*   [Orochi (⭐143)](https://github.com/LDO-CERT/orochi) - Orochi is an open source framework for collaborative forensic memory dump analysis.
*   [Rekall](http://www.rekall-forensic.com/) - Open source tool (and library) for the extraction of digital artifacts from volatile memory (RAM) samples.
*   [Responder PRO](http://www.countertack.com/responder-pro) - Responder PRO is the industry standard physical memory and automated malware analysis solution.
*   [Volatility (⭐5.9k)](https://github.com/volatilityfoundation/volatility) - Advanced memory forensics framework.
*   [Volatility 3 (⭐1.2k)](https://github.com/volatilityfoundation/volatility3) - The volatile memory extraction framework (successor of Volatility)
*   [VolatilityBot (⭐251)](https://github.com/mkorman90/VolatilityBot) - Automation tool for researchers cuts all the guesswork and manual tasks out of the binary extraction phase, or to help the investigator in the first steps of performing a memory analysis investigation.
*   [VolDiff (⭐187)](https://github.com/aim4r/VolDiff) - Malware Memory Footprint Analysis based on Volatility.
*   [WindowsSCOPE](http://www.windowsscope.com/windowsscope-cyber-forensics/) - Memory forensics and reverse engineering tool used for analyzing volatile memory offering the capability of analyzing the Windows kernel, drivers, DLLs, and virtual and physical memory.

### Memory Imaging Tools

*   [Belkasoft Live RAM Capturer](http://belkasoft.com/ram-capturer) - Tiny free forensic tool to reliably extract the entire content of the computer’s volatile memory – even if protected by an active anti-debugging or anti-dumping system.
*   [Linux Memory Grabber (⭐244)](https://github.com/halpomeranz/lmg/) - Script for dumping Linux memory and creating Volatility profiles.
*   [Magnet RAM Capture](https://www.magnetforensics.com/free-tool-magnet-ram-capture/) - Free imaging tool designed to capture the physical memory of a suspect’s computer. Supports recent versions of Windows.
*   [OSForensics](http://www.osforensics.com/) - Tool to acquire live memory on 32-bit and 64-bit systems. A dump of an individual process’s memory space or physical memory dump can be done.

### OSX Evidence Collection

*   [Knockknock](https://objective-see.com/products/knockknock.html) - Displays persistent items(scripts, commands, binaries, etc.) that are set to execute automatically on OSX.
*   [macOS Artifact Parsing Tool (mac\_apt) (⭐556)](https://github.com/ydkhatri/mac_apt) - Plugin based forensics framework for quick mac triage that works on live machines, disk images or individual artifact files.
*   [OSX Auditor (⭐3.1k)](https://github.com/jipegit/OSXAuditor) - Free Mac OS X computer forensics tool.
*   [OSX Collector (⭐1.8k)](https://github.com/yelp/osxcollector) - OSX Auditor offshoot for live response.
*   [The ESF Playground](https://themittenmac.com/the-esf-playground/) - A tool to view the events in Apple Endpoint Security Framework (ESF) in real time.

### Other Lists

*   [Awesome Event IDs (⭐434)](https://github.com/stuhli/awesome-event-ids) - Collection of Event ID resources useful for Digital Forensics and Incident Response.
*   [Awesome Forensics (⭐2.6k)](https://github.com/cugu/awesome-forensics) - A curated list of awesome forensic analysis tools and resources.
*   [Didier Stevens Suite (⭐1.5k)](https://github.com/DidierStevens/DidierStevensSuite) - Tool collection
*   [Eric Zimmerman Tools](https://ericzimmerman.github.io/) - An updated list of forensic tools created by Eric Zimmerman, an instructor for SANS institute.
*   [List of various Security APIs (⭐735)](https://github.com/deralexxx/security-apis) - Collective list of public JSON APIs for use in security.

### Other Tools

*   [Cortex](https://thehive-project.org) - Cortex allows you to analyze observables such as IP and email addresses, URLs, domain names, files or hashes one by one or in bulk mode using a Web interface. Analysts can also automate these operations using its REST API.
*   [Crits](https://crits.github.io/) - Web-based tool which combines an analytic engine with a cyber threat database.
*   [Diffy (⭐623)](https://github.com/Netflix-Skunkworks/diffy) - DFIR tool developed by Netflix's SIRT that allows an investigator to quickly scope a compromise across cloud instances (Linux instances on AWS, currently) during an incident and efficiently triaging those instances for followup actions by showing differences against a baseline.
*   [domfind (⭐20)](https://github.com/diogo-fernan/domfind) - Python DNS crawler for finding identical domain names under different TLDs.
*   [Fileintel (⭐105)](https://github.com/keithjjones/fileintel) - Pull intelligence per file hash.
*   [HELK (⭐3.4k)](https://github.com/Cyb3rWard0g/HELK) - Threat Hunting platform.
*   [Hindsight (⭐828)](https://github.com/obsidianforensics/hindsight) - Internet history forensics for Google Chrome/Chromium.
*   [Hostintel (⭐242)](https://github.com/keithjjones/hostintel) - Pull intelligence per host.
*   [imagemounter (⭐99)](https://github.com/ralphje/imagemounter) - Command line utility and Python package to ease the (un)mounting of forensic disk images.
*   [Kansa (⭐1.4k)](https://github.com/davehull/Kansa/) - Modular incident response framework in PowerShell.
*   [MFT Browser (⭐239)](https://github.com/kacos2000/MFT_Browser) - MFT directory tree reconstruction & record info.
*   [Munin (⭐722)](https://github.com/Neo23x0/munin) - Online hash checker for VirusTotal and other services.
*   [PowerSponse (⭐34)](https://github.com/swisscom/PowerSponse) - PowerSponse is a PowerShell module focused on targeted containment and remediation during security incident response.
*   [PyaraScanner (⭐22)](https://github.com/nogoodconfig/pyarascanner) - Very simple multi-threaded many-rules to many-files YARA scanning Python script for malware zoos and IR.
*   [rastrea2r (⭐209)](https://github.com/rastrea2r/rastrea2r) - Allows one to scan disks and memory for IOCs using YARA on Windows, Linux and OS X.
*   [RaQet](https://raqet.github.io/) - Unconventional remote acquisition and triaging tool that allows triage a disk of a remote computer (client) that is restarted with a purposely built forensic operating system.
*   [Raccine (⭐850)](https://github.com/Neo23x0/Raccine) - A Simple Ransomware Protection
*   [Stalk](https://www.percona.com/doc/percona-toolkit/2.2/pt-stalk.html) - Collect forensic data about MySQL when problems occur.
*   [Scout2](https://nccgroup.github.io/Scout2/) - Security tool that lets Amazon Web Services administrators assess their environment's security posture.
*   [Stenographer (⭐1.8k)](https://github.com/google/stenographer) - Packet capture solution which aims to quickly spool all packets to disk, then provide simple, fast access to subsets of those packets. It stores as much history as it possible, managing disk usage, and deleting when disk limits are hit. It's ideal for capturing the traffic just before and during an incident, without the need explicit need to store all of the network traffic.
*   [sqhunter (⭐65)](https://github.com/0x4d31/sqhunter) - Threat hunter based on osquery and Salt Open (SaltStack) that can issue ad-hoc or distributed queries without the need for osquery's tls plugin. sqhunter allows you to query open network sockets and check them against threat intelligence sources.
*   [sysmon-config (⭐3.9k)](https://github.com/SwiftOnSecurity/sysmon-config) - Sysmon configuration file template with default high-quality event tracing
*   [sysmon-modular (⭐2.1k)](https://github.com/olafhartong/sysmon-modular) - A repository of sysmon configuration modules
*   [traceroute-circl (⭐36)](https://github.com/CIRCL/traceroute-circl) - Extended traceroute to support the activities of CSIRT (or CERT) operators. Usually CSIRT team have to handle incidents based on IP addresses received. Created by Computer Emergency Response Center Luxembourg.
*   [X-Ray 2.0](https://www.raymond.cc/blog/xray/) - Windows utility (poorly maintained or no longer maintained) to submit virus samples to AV vendors.

### Playbooks

*   [AWS Incident Response Runbook Samples (⭐695)](https://github.com/aws-samples/aws-incident-response-runbooks/tree/0d9a1c0f7ad68fb2c1b2d86be8914f2069492e21) - AWS IR Runbook Samples meant to be customized per each entity using them. The three samples are: "DoS or DDoS attack", "credential leakage", and "unintended access to an Amazon S3 bucket".
*   [Counteractive Playbooks (⭐380)](https://github.com/counteractive/incident-response-plan-template/tree/master/playbooks) - Counteractive PLaybooks collection.
*   [GuardSIght Playbook Battle Cards (⭐177)](https://github.com/guardsight/gsvsoc_cirt-playbook-battle-cards) - A collection of Cyber Incident Response Playbook Battle Cards
*   [IRM (⭐519)](https://github.com/certsocietegenerale/IRM) - Incident Response Methodologies by CERT Societe Generale.
*   [IR Workflow Gallery](https://www.incidentresponse.org/playbooks/) - Different generic incident response workflows, e.g. for malware outbreak, data theft, unauthorized access,... Every workflow consists of seven steps: prepare, detect, analyze, contain, eradicate, recover, post-incident handling. The workflows are online available or for download.
*   [PagerDuty Incident Response Documentation](https://response.pagerduty.com/) - Documents that describe parts of the PagerDuty Incident Response process. It provides information not only on preparing for an incident, but also what to do during and after. Source is available on [GitHub (⭐955)](https://github.com/PagerDuty/incident-response-docs).
*   [Phantom Community Playbooks (⭐373)](https://github.com/phantomcyber/playbooks) - Phantom Community Playbooks for Splunk but also customizable for other use.
*   [ThreatHunter-Playbook (⭐3.3k)](https://github.com/OTRF/ThreatHunter-Playbook) - Playbook to aid the development of techniques and hypothesis for hunting campaigns.

### Process Dump Tools

*   [Microsoft ProcDump](https://docs.microsoft.com/en-us/sysinternals/downloads/procdump) - Dumps any running Win32 processes memory image on the fly.
*   [PMDump](http://www.ntsecurity.nu/toolbox/pmdump/) - Tool that lets you dump the memory contents of a process to a file without stopping the process.

### Sandboxing/Reversing Tools

*   [AMAaaS](https://amaaas.com/index.php/AMAaaS/dashboard) - Android Malware Analysis as a Service, executed in a native Android environment.
*   [Any Run](https://app.any.run/) - Interactive online malware analysis service for dynamic and static research of most types of threats using any environment.
*   [CAPEv2 (⭐1k)](https://github.com/kevoreilly/CAPEv2) - Malware Configuration And Payload Extraction.
*   [Cuckoo (⭐5.1k)](https://github.com/cuckoosandbox/cuckoo) - Open Source Highly configurable sandboxing tool.
*   [Cuckoo-modified (⭐381)](https://github.com/spender-sandbox/cuckoo-modified) - Heavily modified Cuckoo fork developed by community.
*   [Cuckoo-modified-api (⭐16)](https://github.com/keithjjones/cuckoo-modified-api) - Python library to control a cuckoo-modified sandbox.
*   [Cutter](https://github.com/radareorg/cutter) - Reverse engineering platform powered by Radare2.
*   [Ghidra (⭐37k)](https://github.com/NationalSecurityAgency/ghidra) - Software Reverse Engineering Framework.
*   [Hybrid-Analysis](https://www.hybrid-analysis.com/) - Free powerful online sandbox by CrowdStrike.
*   [Intezer](https://analyze.intezer.com/#/) - Intezer Analyze dives into Windows binaries to detect micro-code similarities to known threats, in order to provide accurate yet easy-to-understand results.
*   [Joe Sandbox (Community)](https://www.joesandbox.com/) - Joe Sandbox detects and analyzes potential malicious files and URLs on Windows, Android, Mac OS, Linux, and iOS for suspicious activities; providing comprehensive and detailed analysis reports.
*   [Mastiff (⭐160)](https://github.com/KoreLogicSecurity/mastiff) - Static analysis framework that automates the process of extracting key characteristics from a number of different file formats.
*   [Metadefender Cloud](https://www.metadefender.com) - Free threat intelligence platform providing multiscanning, data sanitization and vulnerability assessment of files.
*   [Radare2 (⭐17k)](https://github.com/radareorg/radare2) - Reverse engineering framework and command-line toolset.
*   [Reverse.IT](https://www.reverse.it/) - Alternative domain for the Hybrid-Analysis tool provided by CrowdStrike.
*   [Rizin (⭐1.7k)](https://github.com/rizinorg/rizin) - UNIX-like reverse engineering framework and command-line toolset
*   [StringSifter (⭐594)](https://github.com/fireeye/stringsifter) - A machine learning tool that ranks strings based on their relevance for malware analysis.
*   [Threat.Zone](https://app.threat.zone) - Cloud based threat analysis platform which include sandbox, CDR and interactive analysis for researchers.
*   [Valkyrie Comodo](https://valkyrie.comodo.com) - Valkyrie uses run-time behavior and hundreds of features from a file to perform analysis.
*   [Viper (⭐1.5k)](https://github.com/viper-framework/viper) - Python based binary analysis and management framework, that works well with Cuckoo and YARA.
*   [Virustotal](https://www.virustotal.com) - Free online service that analyzes files and URLs enabling the identification of viruses, worms, trojans and other kinds of malicious content detected by antivirus engines and website scanners.
*   [Visualize\_Logs (⭐132)](https://github.com/keithjjones/visualize_logs) - Open source visualization library and command line tools for logs (Cuckoo, Procmon, more to come).
*   [Yomi](https://yomi.yoroi.company) - Free MultiSandbox managed and hosted by Yoroi.

### Scanner Tools

*   [Fenrir (⭐541)](https://github.com/Neo23x0/Fenrir) - Simple IOC scanner. It allows scanning any Linux/Unix/OSX system for IOCs in plain bash. Created by the creators of THOR and LOKI.
*   [LOKI (⭐2.7k)](https://github.com/Neo23x0/Loki) - Free IR scanner for scanning endpoint with yara rules and other indicators(IOCs).
*   [Spyre (⭐138)](https://github.com/spyre-project/spyre) - Simple YARA-based IOC scanner written in Go

### Timeline Tools

*   [Aurora Incident Response (⭐581)](https://github.com/cyb3rfox/Aurora-Incident-Response) - Platform developed to build easily a detailed timeline of an incident.
*   [Highlighter](https://www.fireeye.com/services/freeware/highlighter.html) - Free Tool available from Fire/Mandiant that will depict log/text file that can highlight areas on the graphic, that corresponded to a key word or phrase. Good for time lining an infection and what was done post compromise.
*   [Morgue (⭐1k)](https://github.com/etsy/morgue) - PHP Web app by Etsy for managing postmortems.
*   [Plaso (⭐1.4k)](https://github.com/log2timeline/plaso) -  a Python-based backend engine for the tool log2timeline.
*   [Timesketch (⭐2.1k)](https://github.com/google/timesketch) - Open source tool for collaborative forensic timeline analysis.

### Videos

*   [The Future of Incident Response](https://www.youtube.com/watch?v=bDcx4UNpKNc) - Presented by Bruce Schneier at OWASP AppSecUSA 2015.

### Windows Evidence Collection

*   [AChoir (⭐164)](https://github.com/OMENScan/AChoir) - Framework/scripting tool to standardize and simplify the process of scripting live acquisition utilities for Windows.
*   [Crowd Response](http://www.crowdstrike.com/community-tools/) - Lightweight Windows console application designed to aid in the gathering of system information for incident response and security engagements. It features numerous modules and output formats.
*   [DFIR ORC](https://dfir-orc.github.io/) - DFIR ORC is a collection of specialized tools dedicated to reliably parse and collect critical artifacts such as the MFT, registry hives or event logs. DFIR ORC collects data, but does not analyze it: it is not meant to triage machines. It provides a forensically relevant snapshot of machines running Microsoft Windows. The code can be found on [GitHub (⭐310)](https://github.com/DFIR-ORC/dfir-orc).
*   [FastIR Collector (⭐480)](https://github.com/SekoiaLab/Fastir_Collector) - Tool that collects different artifacts on live Windows systems and records the results in csv files. With the analyses of these artifacts, an early compromise can be detected.
*   [Fibratus (⭐1.8k)](https://github.com/rabbitstack/fibratus) - Tool for exploration and tracing of the Windows kernel.
*   [Hoarder (⭐146)](https://github.com/muteb/Hoarder) - Collecting the most valuable artifacts for forensics or incident response investigations.
*   [IREC](https://binalyze.com/products/irec-free/) - All-in-one IR Evidence Collector which captures RAM Image, $MFT, EventLogs, WMI Scripts, Registry Hives, System Restore Points and much more. It is FREE, lightning fast and easy to use.
*   [Invoke-LiveResponse (⭐133)](https://github.com/mgreen27/Invoke-LiveResponse) -  Invoke-LiveResponse is a live response tool for targeted collection.
*   [IOC Finder](https://www.fireeye.com/services/freeware/ioc-finder.html) - Free tool from Mandiant for collecting host system data and reporting the presence of Indicators of Compromise (IOCs). Support for Windows only. No longer maintained. Only fully supported up to Windows 7 / Windows Server 2008 R2.
*   [IRTriage (⭐115)](https://github.com/AJMartel/IRTriage) - Incident Response Triage - Windows Evidence Collection for Forensic Analysis.
*   [KAPE](https://www.kroll.com/en/services/cyber-risk/incident-response-litigation-support/kroll-artifact-parser-extractor-kape) - Kroll Artifact Parser and Extractor (KAPE) by Eric Zimmerman. A triage tool that finds the most prevalent digital artifacts and then parses them quickly. Great and thorough when time is of the essence.
*   [LOKI (⭐2.7k)](https://github.com/Neo23x0/Loki) - Free IR scanner for scanning endpoint with yara rules and other indicators(IOCs).
*   [MEERKAT (⭐368)](https://github.com/TonyPhipps/Meerkat) - PowerShell-based triage and threat hunting for Windows.
*   [Panorama (⭐38)](https://github.com/AlmCo/Panorama) - Fast incident overview on live Windows systems.
*   [PowerForensics (⭐1.3k)](https://github.com/Invoke-IR/PowerForensics) - Live disk forensics platform, using PowerShell.
*   [PSRecon (⭐459)](https://github.com/gfoss/PSRecon/) - PSRecon gathers data from a remote Windows host using PowerShell (v2 or later), organizes the data into folders, hashes all extracted data, hashes PowerShell and various system properties, and sends the data off to the security team. The data can be pushed to a share, sent over email, or retained locally.
*   [RegRipper (⭐325)](https://github.com/keydet89/RegRipper3.0) - Open source tool, written in Perl, for extracting/parsing information (keys, values, data) from the Registry and presenting it for analysis.

