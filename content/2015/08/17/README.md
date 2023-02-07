# Awesome List Updates on Aug 17, 2015

7 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Security](/content/sbilly/awesome-security/README.md)

### Network / Scanning / Pentesting

*   [OpenVAS](http://www.openvas.org/) - OpenVAS is a framework of several services and tools offering a comprehensive and powerful vulnerability scanning and vulnerability management solution.
*   [Metasploit Framework (⭐29k)](https://github.com/rapid7/metasploit-framework) - A tool for developing and executing exploit code against a remote target machine. Other important sub-projects include the Opcode Database, shellcode archive and related research.

### Network / Monitoring / Logging

*   [justniffer](http://justniffer.sourceforge.net/) - Justniffer is a network protocol analyzer that captures network traffic and produces logs in a customized way, can emulate Apache web server log files, track response times and extract all "intercepted" files from the HTTP traffic.
*   [httpry](http://dumpsterventures.com/jason/httpry/) - httpry is a specialized packet sniffer designed for displaying and logging HTTP traffic. It is not intended to perform analysis itself, but to capture, parse, and log the traffic for later analysis. It can be run in real-time displaying the traffic as it is parsed, or as a daemon process that logs to an output file. It is written to be as lightweight and flexible as possible, so that it can be easily adaptable to different applications.
*   [ngrep](http://ngrep.sourceforge.net/) - ngrep strives to provide most of GNU grep's common features, applying them to the network layer. ngrep is a pcap-aware tool that will allow you to specify extended regular or hexadecimal expressions to match against data payloads of packets. It currently recognizes IPv4/6, TCP, UDP, ICMPv4/6, IGMP and Raw across Ethernet, PPP, SLIP, FDDI, Token Ring and null interfaces, and understands BPF filter logic in the same fashion as more common packet sniffing tools, such as tcpdump and snoop.
*   [sagan](http://sagan.quadrantsec.com/) - Sagan uses a 'Snort like' engine and rules to analyze logs (syslog/event log/snmptrap/netflow/etc).

### Network / IDS / IPS / Host IDS / Host IPS

*   [Snort](https://www.snort.org/) - Snort is a free and open source network intrusion prevention system (NIPS) and network intrusion detection system (NIDS)created by Martin Roesch in 1998. Snort is now developed by Sourcefire, of which Roesch is the founder and CTO. In 2009, Snort entered InfoWorld's Open Source Hall of Fame as one of the "greatest \[pieces of] open source software of all time".
*   [sshwatch (⭐34)](https://github.com/marshyski/sshwatch) - IPS for SSH similar to DenyHosts written in Python.  It also can gather information about attacker during the attack in a log.

### Network / Honey Pot / Honey Net

*   [Conpot](http://conpot.org/) - ICS/SCADA Honeypot. Conpot is a low interactive server side Industrial Control Systems honeypot designed to be easy to deploy, modify and extend. By providing a range of common industrial control protocols we created the basics to build your own system, capable to emulate complex infrastructures to convince an adversary that he just found a huge industrial complex. To improve the deceptive capabilities, we also provided the possibility to server a custom human machine interface to increase the honeypots attack surface. The response times of the services can be artificially delayed to mimic the behaviour of a system under constant load. Because we are providing complete stacks of the protocols, Conpot can be accessed with productive HMI's or extended with real hardware. Conpot is developed under the umbrella of the Honeynet Project and on the shoulders of a couple of very big giants.
*   [Amun (⭐49)](https://github.com/zeroq/amun) - Amun Python-based low-interaction Honeypot.
*   [Glastopf](http://glastopf.org/) - Glastopf is a Honeypot which emulates thousands of vulnerabilities to gather data from attacks targeting web applications. The principle behind it is very simple: Reply the correct response to the attacker exploiting the web application.
*   [Kippo (⭐1.4k)](https://github.com/desaster/kippo) - Kippo is a medium interaction SSH honeypot designed to log brute force attacks and, most importantly, the entire shell interaction performed by the attacker.
*   [Kojoney](http://kojoney.sourceforge.net/) - Kojoney is a low level interaction honeypot that emulates an SSH server. The daemon is written in Python using the Twisted Conch libraries.
*   [HoneyDrive](http://bruteforce.gr/honeydrive) - HoneyDrive is the premier honeypot Linux distro. It is a virtual appliance (OVA) with Xubuntu Desktop 12.04.4 LTS edition installed. It contains over 10 pre-installed and pre-configured honeypot software packages such as Kippo SSH honeypot, Dionaea and Amun malware honeypots, Honeyd low-interaction honeypot, Glastopf web honeypot and Wordpot, Conpot SCADA/ICS honeypot, Thug and PhoneyC honeyclients and more. Additionally it includes many useful pre-configured scripts and utilities to analyze, visualize and process the data it can capture, such as Kippo-Graph, Honeyd-Viz, DionaeaFR, an ELK stack and much more. Lastly, almost 90 well-known malware analysis, forensics and network monitoring related tools are also present in the distribution.
*   [Cuckoo Sandbox](http://www.cuckoosandbox.org/) - Cuckoo Sandbox is an Open Source software for automating analysis of suspicious files. To do so it makes use of custom components that monitor the behavior of the malicious processes while running in an isolated environment.

### Network / Full Packet Capture / Forensic

*   [tcpflow (⭐1.4k)](https://github.com/simsong/tcpflow) - tcpflow is a program that captures data transmitted as part of TCP connections (flows), and stores the data in a way that is convenient for protocol analysis and debugging. Each TCP flow is stored in its own file. Thus, the typical TCP flow will be stored in two files, one for each direction. tcpflow can also process stored 'tcpdump' packet flows.
*   [Xplico](http://www.xplico.org/) - The goal of Xplico is extract from an internet traffic capture the applications data contained. For example, from a pcap file Xplico extracts each email (POP, IMAP, and SMTP protocols), all HTTP contents, each VoIP call (SIP), FTP, TFTP, and so on. Xplico isn’t a network protocol analyzer. Xplico is an open source Network Forensic Analysis Tool (NFAT).
*   [OpenFPC](http://www.openfpc.org) - OpenFPC is a set of tools that combine to provide a lightweight full-packet network traffic recorder & buffering system. It's design goal is to allow non-expert users to deploy a distributed network traffic recorder on COTS hardware while integrating into existing alert and log management tools.
*   [Dshell (⭐5.4k)](https://github.com/USArmyResearchLab/Dshell) - Dshell is a network forensic analysis framework. Enables rapid development of plugins to support the dissection of network packet captures.
*   [stenographer (⭐1.7k)](https://github.com/google/stenographer) - Stenographer is a packet capture solution which aims to quickly spool all packets to disk, then provide simple, fast access to subsets of those packets.

### Network / Sniffer

*   [wireshark](https://www.wireshark.org) - Wireshark is a free and open-source packet analyzer. It is used for network troubleshooting, analysis, software and communications protocol development, and education. Wireshark is very similar to tcpdump, but has a graphical front-end, plus some integrated sorting and filtering options.
*   [netsniff-ng](http://netsniff-ng.org/) -  netsniff-ng is a free Linux networking toolkit, a Swiss army knife for your daily Linux network plumbing if you will. Its gain of performance is reached by zero-copy mechanisms, so that on packet reception and transmission the kernel does not need to copy packets from kernel space to user space and vice versa.

### Network / Security Information & Event Management

*   [OSSIM](https://www.alienvault.com/open-threat-exchange/projects) - OSSIM provides all of the features that a security professional needs from a SIEM offering – event collection, normalization, and correlation.

### Endpoint / Configuration Management

*   [Rudder](http://www.rudder-project.org/) - Rudder is an easy to use, web-driven, role-based solution for IT Infrastructure Automation & Compliance. Automate common system administration tasks (installation, configuration); Enforce configuration over time (configuring once is good, ensuring that configuration is valid and automatically fixing it is better); Inventory of all managed nodes; Web interface to configure and manage nodes and their configuration; Compliance reporting, by configuration and/or by node.

### Endpoint / Mobile / Android / iOS

*   [android-security-awesome (⭐6.4k)](https://github.com/ashishb/android-security-awesome) - A collection of android security related resources. A lot of work is happening in academia and industry on tools to perform dynamic analysis, static analysis and reverse engineering of android apps.

### Endpoint / Forensics

*   [grr (⭐4.2k)](https://github.com/google/grr) - GRR Rapid Response is an incident response framework focused on remote live forensics.

### Threat Intelligence / Forensics

*   [PhishTank](http://www.phishtank.com/) - PhishTank is a collaborative clearing house for data and information about phishing on the Internet. Also, PhishTank provides an open API for developers and researchers to integrate anti-phishing data into their applications at no charge.
*   [Internet Storm Center](https://www.dshield.org/reports.html) - The ISC was created in 2001 following the successful detection, analysis, and widespread warning of the Li0n worm. Today, the ISC provides a free analysis and warning service to thousands of Internet users and organizations, and is actively working with Internet Service Providers to fight back against the most malicious attackers.
*   [AutoShun](https://www.autoshun.org/) - AutoShun is a Snort plugin that allows you to send your Snort IDS logs to a centralized server that will correlate attacks from your sensor logs with other snort sensors, honeypots, and mail filters from around the world.
*   [DNS-BH](http://www.malwaredomains.com/) - The DNS-BH project creates and maintains a listing of domains that are known to be used to propagate malware and spyware. This project creates the Bind and Windows zone files required to serve fake replies to localhost for any requests to these, thus preventing many spyware installs and reporting.
*   [AlienVault Open Threat Exchange](http://www.alienvault.com/open-threat-exchange/dashboard) - AlienVault Open Threat Exchange (OTX), to help you secure your networks from data loss, service disruption and system compromise caused by malicious IP addresses.
*   [leakedin.com](http://www.leakedin.com/) - The primary purpose of leakedin.com is to make visitors aware about the risks of loosing data. This blog just compiles samples of data lost or disclosed on sites like pastebin.com.
*   [FireEye OpenIOCs (⭐441)](https://github.com/fireeye/iocs) - FireEye Publicly Shared Indicators of Compromise (IOCs)
*   [OpenVAS NVT Feed](http://www.openvas.org/openvas-nvt-feed.html) - The public feed of Network Vulnerability Tests (NVTs). It contains more than 35,000 NVTs (as of April 2014), growing on a daily basis. This feed is configured as the default for OpenVAS.
*   [Project Honey Pot](http://www.projecthoneypot.org/) - Project Honey Pot is the first and only distributed system for identifying spammers and the spambots they use to scrape addresses from your website. Using the Project Honey Pot system you can install addresses that are custom-tagged to the time and IP address of a visitor to your site. If one of these addresses begins receiving email we not only can tell that the messages are spam, but also the exact moment when the address was harvested and the IP address that gathered it.
*   [virustotal](https://www.virustotal.com/) - VirusTotal, a subsidiary of Google, is a free online service that analyzes files and URLs enabling the identification of viruses, worms, trojans and other kinds of malicious content detected by antivirus engines and website scanners. At the same time, it may be used as a means to detect false positives, i.e. innocuous resources detected as malicious by one or more scanners.

### Web / Organization

*   [OWASP](http://www.owasp.org) - The Open Web Application Security Project (OWASP) is a 501(c)(3) worldwide not-for-profit charitable organization focused on improving the security of software.

### Web / Scanning / Pentesting

*   [sqlmap](http://sqlmap.org/) - sqlmap is an open source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers. It comes with a powerful detection engine, many niche features for the ultimate penetration tester and a broad range of switches lasting from database fingerprinting, over data fetching from the database, to accessing the underlying file system and executing commands on the operating system via out-of-band connections.
*   [w3af](http://w3af.org/) - w3af is a Web Application Attack and Audit Framework. The project’s goal is to create a framework to help you secure your web applications by finding and exploiting all web application vulnerabilities.
*   [PTF (⭐4.4k)](https://github.com/trustedsec/ptf) - The Penetration Testers Framework (PTF) is a way for modular support for up-to-date tools.

### Big Data / Development

*   [data\_hacking (⭐738)](https://github.com/ClickSecurity/data_hacking) - Examples of using IPython, Pandas, and Scikit Learn to get the most out of your security data.
*   [hadoop-pcap (⭐202)](https://github.com/RIPE-NCC/hadoop-pcap) - Hadoop library to read packet capture (PCAP) files.
*   [OpenSOC (⭐564)](https://github.com/OpenSOC/opensoc) - OpenSOC integrates a variety of open source big data technologies in order to offer a centralized tool for security monitoring and analysis.
*   [binarypig (⭐140)](https://github.com/endgameinc/binarypig) - Scalable Binary Data Extraction in Hadoop. Malware Processing and Analytics over Pig, Exploration through Django, Twitter Bootstrap, and Elasticsearch.

### Other Awesome Lists / Other Common Awesome Lists

*   [lists (⭐8.5k)](https://github.com/jnv/lists) - The definitive list of (awesome) lists curated on GitHub.

## [2. Awesome Ocaml](/content/ocaml-community/awesome-ocaml/README.md)

### Questions

*   [oml (⭐115)](https://github.com/hammerlab/oml) - OCaml library for general numerical work.

### Testing

*   [iTeML (⭐66)](https://github.com/vincent-hugot/iTeML) (formerly known as [qtest](http://batteries.vhugot.com/qtest/))  — supports inline pragma's to generate tests.
*   [Pa\_test](https://ocaml.janestreet.com/ocaml-core/111.28.00/doc/pa_test) —  General inline testing macro's.

## [3. Awesome Deep Learning](/content/ChristosChristofidis/awesome-deep-learning/README.md)

### Researchers / Tutorials

*   [Aaron Courville](http://aaroncourville.wordpress.com)
*   [Abdel-rahman Mohamed](http://www.cs.toronto.edu/\~asamir/)
*   [Alex Acero](http://research.microsoft.com/en-us/people/alexac/)
*   [ Alex Krizhevsky ](http://www.cs.utoronto.ca/\~kriz/index.html)
*   [ Alexander Ilin ](http://users.ics.aalto.fi/alexilin/)
*   [ Amos Storkey ](http://homepages.inf.ed.ac.uk/amos/)
*   [ Andrew M. Saxe ](http://www.stanford.edu/\~asaxe/)
*   [ Andrew Ng ](http://www.cs.stanford.edu/people/ang/)
*   [ Andrew W. Senior ](http://research.google.com/pubs/author37792.html)
*   [ Andriy Mnih ](http://www.gatsby.ucl.ac.uk/\~amnih/)
*   [ Ayse Naz Erkan ](http://www.cs.nyu.edu/\~naz/)
*   [ Benjamin Schrauwen ](http://reslab.elis.ugent.be/benjamin)
*   [ Bernardete Ribeiro ](https://www.cisuc.uc.pt/people/show/2020)
*   [ Bo David Chen ](http://vision.caltech.edu/\~bchen3/Site/Bo_David_Chen.html)
*   [ Boureau Y-Lan ](http://cs.nyu.edu/\~ylan/)
*   [ Brian Kingsbury ](http://researcher.watson.ibm.com/researcher/view.php?person=us-bedk)
*   [ Christopher Manning ](http://nlp.stanford.edu/\~manning/)
*   [ Clement Farabet ](http://www.clement.farabet.net/)
*   [ Dan Claudiu Cireșan ](http://www.idsia.ch/\~ciresan/)
*   [ Dong Yu ](http://research.microsoft.com/en-us/people/dongyu/default.aspx)
*   [ Drausin Wulsin ](http://www.seas.upenn.edu/\~wulsin/)
*   [ Erik M. Schmidt ](http://music.ece.drexel.edu/people/eschmidt)
*   [ Eugenio Culurciello ](https://engineering.purdue.edu/BME/People/viewPersonById?resource_id=71333)
*   [ Frank Seide ](http://research.microsoft.com/en-us/people/fseide/)
*   [ Galen Andrew ](http://homes.cs.washington.edu/\~galen/)
*   [ Geoffrey Hinton ](http://www.cs.toronto.edu/\~hinton/)
*   [ George Dahl ](http://www.cs.toronto.edu/\~gdahl/)
*   [ Graham Taylor ](http://www.uoguelph.ca/\~gwtaylor/)
*   [ Grégoire Montavon ](http://gregoire.montavon.name/)
*   [ Guido Francisco Montúfar ](http://personal-homepages.mis.mpg.de/montufar/)
*   [ Guillaume Desjardins ](http://brainlogging.wordpress.com/)
*   [ Hannes Schulz ](http://www.ais.uni-bonn.de/\~schulz/)
*   [ Hélène Paugam-Moisy ](http://www.lri.fr/\~hpaugam/)
*   [ Honglak Lee ](http://web.eecs.umich.edu/\~honglak/)
*   [ Hugo Larochelle ](http://www.dmi.usherb.ca/\~larocheh/index_en.html)
*   [ Ilya Sutskever ](http://www.cs.toronto.edu/\~ilya/)
*   [ James Martens ](http://www.cs.toronto.edu/\~jmartens/)
*   [ Jason Morton ](http://www.jasonmorton.com/)
*   [ Jason Weston ](http://www.thespermwhale.com/jaseweston/)
*   [ Jeff Dean ](http://research.google.com/pubs/jeff.html)
*   [ Jiquan Mgiam ](http://cs.stanford.edu/\~jngiam/)
*   [ Joseph Turian ](http://www-etud.iro.umontreal.ca/\~turian/)
*   [ Joshua Matthew Susskind ](http://aclab.ca/users/josh/index.html)
*   [ Jürgen Schmidhuber ](http://www.idsia.ch/\~juergen/)
*   [ Koray Kavukcuoglu ](http://koray.kavukcuoglu.org/)
*   [ KyungHyun Cho ](http://users.ics.aalto.fi/kcho/)
*   [ Li Deng ](http://research.microsoft.com/en-us/people/deng/)
*   [ Lucas Theis ](http://www.kyb.tuebingen.mpg.de/nc/employee/details/lucas.html)
*   [ Marc'Aurelio Ranzato ](http://www.cs.nyu.edu/\~ranzato/)
*   [ Martin Längkvist ](http://aass.oru.se/\~mlt/)
*   [ Mohammad Norouzi ](http://www.cs.toronto.edu/\~norouzi/)
*   [ Nando de Freitas ](http://www.cs.ubc.ca/\~nando/)
*   [ Navdeep Jaitly ](http://www.cs.utoronto.ca/\~ndjaitly/)
*   [ Nicolas Le Roux ](http://nicolas.le-roux.name/)
*   [ Nitish Srivastava ](http://www.cs.toronto.edu/\~nitish/)
*   [ Noel Lopes ](https://www.cisuc.uc.pt/people/show/2028)
*   [ Oriol Vinyals ](http://www.cs.berkeley.edu/\~vinyals/)
*   [ Pascal Vincent ](http://www.iro.umontreal.ca/\~vincentp)
*   [ Pedro Domingos ](http://homes.cs.washington.edu/\~pedrod/)
*   [ Peggy Series ](http://homepages.inf.ed.ac.uk/pseries/)
*   [ Pierre Sermanet ](http://cs.nyu.edu/\~sermanet)
*   [ Piotr Mirowski ](http://www.cs.nyu.edu/\~mirowski/)
*   [ Quoc V. Le ](http://ai.stanford.edu/\~quocle/)
*   [ Reinhold Scherer ](http://bci.tugraz.at/scherer/)
*   [ Richard Socher ](http://www.socher.org/)
*   [ Robert Gens ](http://homes.cs.washington.edu/\~rcg/)
*   [ Roger Grosse ](http://people.csail.mit.edu/rgrosse/)
*   [ Ronan Collobert ](http://ronan.collobert.com/)
*   [ Ruslan Salakhutdinov ](http://www.utstat.toronto.edu/\~rsalakhu/)
*   [ Sebastian Gerwinn ](http://www.kyb.tuebingen.mpg.de/nc/employee/details/sgerwinn.html)
*   [ Stéphane Mallat ](http://www.cmap.polytechnique.fr/\~mallat/)
*   [ Sven Behnke ](http://www.ais.uni-bonn.de/behnke/)
*   [ Tapani Raiko ](http://users.ics.aalto.fi/praiko/)
*   [ Tara Sainath ](https://sites.google.com/site/tsainath/)
*   [ Tijmen Tieleman ](http://www.cs.toronto.edu/\~tijmen/)
*   [ Ueli Meier ](http://www.idsia.ch/\~meier/)
*   [ Vincent Vanhoucke ](http://vincent.vanhoucke.com)
*   [ Volodymyr Mnih ](http://www.cs.toronto.edu/\~vmnih/)
*   [ Yann LeCun ](http://yann.lecun.com/)
*   [ Yichuan Tang ](http://www.cs.toronto.edu/\~tang/)
*   [ Yoshua Bengio ](http://www.iro.umontreal.ca/\~bengioy/yoshua_en/index.html)

## [4. Awesome Cpp](/content/fffaraz/awesome-cpp/README.md)

### Database

*   [redis3m (⭐185)](https://github.com/luca3m/redis3m) - Wrapper of hiredis with clean C++ interface, supporting sentinel and ready to use patterns. \[Apache2]

## [5. Awesome Jvm](/content/deephacks/awesome-jvm/README.md)

### Profilers

*   [Overseer](http://www.peternier.com/projects/overseer/overseer.php) - Low-Level Hardware Monitoring and Management for Java.

## [6. Awesome Android Ui](/content/wasabeef/awesome-android-ui/README.md)

### Layout

- Name: [WaveSwipeRefreshLayout (⭐1.9k)](https://github.com/recruit-lifestyle/WaveSwipeRefreshLayout)

  License: [Apache License V2](https://www.apache.org/licenses/LICENSE-2.0)

  Demo: <img src="https://github.com/wasabeef/awesome-android-ui/raw/master/art/WaveSwipeRefreshLayout.gif" width="49%">


- Name: [FloatingView (⭐1.1k)](https://github.com/recruit-lifestyle/FloatingView)

  License: [Apache License V2](https://www.apache.org/licenses/LICENSE-2.0)

  Demo: <img src="https://github.com/wasabeef/awesome-android-ui/raw/master/art/FloatingView.gif" width="49%">



### Progress

- Name: [Loading (⭐1.2k)](https://github.com/yankai-victor/Loading)

  License: [Apache License V2](https://www.apache.org/licenses/LICENSE-2.0)

  Demo: <img src="https://github.com/wasabeef/awesome-android-ui/raw/master/art/Loading.gif" width="49%"> <img src="https://github.com/wasabeef/awesome-android-ui/raw/master/art/Loading2.gif" width="49%"> <img src="https://github.com/wasabeef/awesome-android-ui/raw/master/art/Loading3.gif" width="49%">


- Name: [Animated Circle Loading View (⭐1.2k)](https://github.com/jlmd/AnimatedCircleLoadingView)

  License: [Apache License V2](https://www.apache.org/licenses/LICENSE-2.0)

  Demo: <img src="https://github.com/wasabeef/awesome-android-ui/raw/master/art/AnimatedCircleLoadingView.gif" width="49%">


- Name: [AndroidFillableLoaders (⭐2k)](https://github.com/JorgeCastilloPrz/AndroidFillableLoaders)

  License: [Apache License V2](https://www.apache.org/licenses/LICENSE-2.0)

  Demo: <img src="https://github.com/wasabeef/awesome-android-ui/raw/master/art/AndroidFillableLoaders.gif" width="49%"> <img src="https://github.com/wasabeef/awesome-android-ui/raw/master/art/AndroidFillableLoaders2.gif" width="49%">



## [7. Awesome Javascript](/content/sorrycc/awesome-javascript/README.md)

### RegExp / Runner

*   [RegEx101](https://regex101.com/#javascript) - Online regex tester and debugger for JavaScript. Also supports Python, PHP and PCRE.

---

- Prev: [Aug 18, 2015](/content/2015/08/18/README.md)
- Next: [Aug 16, 2015](/content/2015/08/16/README.md)