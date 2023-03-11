# Awesome List Updates on Feb 14, 2022

12 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Vehicle Security](/content/jaredthecoder/awesome-vehicle-security/README.md)

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

*   [CANdevStudio (⭐651)](https://github.com/GENIVI/CANdevStudio) - Development tool for CAN bus simulation. CANdevStudio enables to simulate CAN signals such as ignition status, doors status or reverse gear by every automotive developer.

### Libraries and Tools / Java

*   [ITS Geonetworking (⭐91)](https://github.com/alexvoronov/geonetworking) - ETSI ITS G5 GeoNetworking stack, in Java: CAM-DENM / ASN.1 PER / BTP / GeoNetworking

## [2. Awesome Tmux](/content/rothgar/awesome-tmux/README.md)

### Plugins

*   [tmux-browser (⭐39)](https://github.com/ofirgall/tmux-browser) Web browser sessions attached to tmux sessions.

## [3. Awesome Ruby](/content/markets/awesome-ruby/README.md)

### Date and Time Processing

*   [montrose (⭐738)](https://github.com/rossta/montrose) - a simple library for expressing, serializing, and enumerating recurring events in Ruby.
*   [stamp (⭐967)](https://github.com/jeremyw/stamp) - Format dates and times based on human-friendly examples, not arcane strftime directives.

## [4. Awesome Malware Persistence](/content/Karneades/awesome-malware-persistence/README.md)

### Techniques / Generic

*   [MITRE ATT\&CK tactic "TA0003 - Persistence"](https://attack.mitre.org/tactics/TA0003/) - MITRE ATT\&CK tactic "TA0003 - Persistence".
*   [Sigma rules (⭐6.1k)](https://github.com/Neo23x0/sigma/tree/master/rules) - Sigma rules which covers persistence techniques. You can even use filters such as `--filter tag=attack.persistence` or specifically for one technique `tag=attack.t1084`.

### Techniques / Linux

*   [Linux Malware Persistence with Cron](https://www.sandflysecurity.com/blog/linux-malware-persistence-with-cron/) - Blog post about linux persistence using cron jobs.

### Techniques / Windows

*   [Windows Persistence using WinLogon](https://www.hackingarticles.in/windows-persistence-using-winlogon/) - Blog post about abusing WinLogon.
*   [Persistence using GlobalFlags in Image File Execution Options – Hidden from Autoruns.exe](https://oddvar.moe/2018/04/10/persistence-using-globalflags-in-image-file-execution-options-hidden-from-autoruns-exe/) - Blog post about abusing GlobalFlag for process execution.
*   [Uncovering a MyKings Variant With Bootloader Persistence via Managed Detection and Response](https://blog.trendmicro.com/trendlabs-security-intelligence/uncovering-a-mykings-variant-with-bootloader-persistence-via-managed-detection-and-response/) - Blog post about bootloader persistence.
*   Various blog posts about COM/CLSID hijacking
    *   [COM Object hijacking: the discreet way of persistence, 2014](https://www.gdatasoftware.com/blog/2014/10/23941-com-object-hijacking-the-discreet-way-of-persistence)
    *   [Persistence – COM Hijacking, 2020](https://pentestlab.blog/2020/05/20/persistence-com-hijacking/)
    *   [Abusing COM hijacking in combination with scheduled tasks, 2016](https://enigma0x3.net/2016/05/25/userland-persistence-with-scheduled-tasks-and-com-handler-hijacking/)
*   [Hunting for persistence via Microsoft Exchange Server or Outlook](https://speakerdeck.com/heirhabarov/hunting-for-persistence-via-microsoft-exchange-server-or-outlook) - Blog post about Microsoft Exchange server persistence.

### Persistence Removal / Generic

*   [Awesome Incident Response (⭐6k)](https://github.com/meirwah/awesome-incident-response) - Use the tools and resources for security incident response, aimed to help security analysts and DFIR teams.

### Persistence Removal / Windows

*   [PowerSponse (⭐35)](https://github.com/swisscom/PowerSponse) - PowerSponse includes various commands for cleanup of persistence mechanisms.
*   [Removing Backdoors – Powershell Empire Edition](https://www.n00py.io/2017/01/removing-backdoors-powershell-empire-edition/) - Various blog posts handle the removal of WMI implants.
*   [RegDelNull](https://docs.microsoft.com/en-us/sysinternals/downloads/regdelnull) - Removal of registry keys with null bytes - used e.g. in run keys for evasion.

### Detection Testing / Windows

*   [Atomic Red Team (⭐7.2k)](https://github.com/redcanaryco/atomic-red-team) - Atomic Red Team supports also the MITRE ATT\&CK persistence techniques, see e.g. [T1044 "File System Permissions Weakness" (⭐7.2k)](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1044/T1044.yaml).

### Collection / Generic

*   [Awesome Forensics (⭐2.7k)](https://github.com/Cugu/awesome-forensics) - Use the tools from this list which includes awesome free (mostly open source) forensic analysis tools and resources. They help collecting the persistence mechanisms at scale, e.g. by using remote forensics tools.
*   [osquery](https://osquery.readthedocs.io) - Query persistence mechanisms on clients.
*   [OSSEC (⭐3.9k)](https://github.com/ossec/ossec-hids) - Use rules and logs from the HIDS to detection configuration changes.

### Collection / Windows

*   [PowerShell Autoruns (⭐187)](https://github.com/p0w3rsh3ll/AutoRuns) - A PowerShell version of Autoruns.
*   [KAPE](https://www.kroll.com/en/insights/publications/cyber/kroll-artifact-parser-extractor-kape) - The tool allows collecting various predefined artifactgs using targets and modules, see [KapeFiles (⭐442)](https://github.com/EricZimmerman/KapeFiles) which include persistence mechanisms, among others there's a collection of [LNK files (⭐442)](https://github.com/EricZimmerman/KapeFiles/blob/master/Targets/Windows/LNKFilesAndJumpLists.tkape), [scheduled task files (⭐442)](https://github.com/EricZimmerman/KapeFiles/blob/master/Targets/Windows/ScheduledTasks.tkape) and [scheduled task listing (⭐442)](https://github.com/EricZimmerman/KapeFiles/blob/master/Modules/LiveResponse/schtasks.mkape) or a [WMI repository auditing (⭐442)](https://github.com/EricZimmerman/KapeFiles/blob/master/Modules/LiveResponse/WMI-Repository-Auditing.mkape) module.

## [5. Awesome List](/content/sindresorhus/awesome/README.md)

### Front-End Development

*   [lit (⭐1.1k)](https://github.com/web-padawan/awesome-lit#readme) - Library for building web components with a declarative template system.

### Back-End Development

*   [Laravel (⭐12k)](https://github.com/chiraggude/awesome-laravel#readme) - PHP framework.
    *   [Education (⭐368)](https://github.com/fukuball/Awesome-Laravel-Education#readme)
    *   [TALL Stack (⭐794)](https://github.com/livewire/awesome-tall-stack#readme) - Full-stack development solution featuring libraries built by the Laravel community.
*   [Vapor (⭐1k)](https://github.com/vapor-community/awesome-vapor#readme) - Server-side development in Swift.

### Computer Science

*   [Speech and Natural Language Processing (⭐2.1k)](https://github.com/edobashira/speech-language-processing#readme)
    *   [Spanish (⭐313)](https://github.com/dav009/awesome-spanish-nlp#readme)
    *   [NLP with Ruby (⭐986)](https://github.com/arbox/nlp-with-ruby#readme)
    *   [Question Answering (⭐718)](https://github.com/seriousran/awesome-qa#readme) - The science of asking and answering in natural language with a machine.
    *   [Natural Language Generation (⭐401)](https://github.com/accelerated-text/awesome-nlg#readme) - Generation of text used in data to text, conversational agents, and narrative generation applications.

### Big Data

*   [Big Data (⭐12k)](https://github.com/0xnr/awesome-bigdata#readme)

### Gaming

*   [Construct 2 (⭐53)](https://github.com/ConstructCommunity/awesome-construct#readme) - Game engine.

### Testing

*   [k6 (⭐355)](https://github.com/grafana/awesome-k6#readme) - Open-source, developer-centric performance monitoring and load testing solution.

### Miscellaneous

*   [Analytics (⭐3.6k)](https://github.com/0xnr/awesome-analytics#readme)
*   [Data Visualization (⭐3.2k)](https://github.com/javierluraschi/awesome-dataviz#readme)
*   [Product Design (⭐2k)](https://github.com/ttt30ga/awesome-product-design#readme) - Design a product from the initial concept to production.
*   [QR Code (⭐53)](https://github.com/make-github-pseudonymous-again/awesome-qr-code#readme) - A type of matrix barcode that can be used to store and share a small amount of information.

### Related

*   [Awesome Viewer](https://awesome.digitalbunker.dev) - A visualizer for all of the above Awesome lists.

## [6. Awesome Agi Cocosci](/content/YuzheSHI/awesome-agi-cocosci/README.md)

### NYU / Commonsense Knowledgebase

*   [Ernest Davis](https://cs.nyu.edu/~davise/) - ***Department of Computer Science, Courant Institute of Mathematical Sciences, NYU***.

## [7. Awesome React Components](/content/brillout/awesome-react-components/README.md)

### Boilerplate / Mouse Events

*   [nx](https://nx.dev) - Next generation build system with first class monorepo support and powerful integrations.

## [8. Awesome Cpp](/content/fffaraz/awesome-cpp/README.md)

### Graphics

*   [Skia (⭐7.3k)](https://github.com/google/skia) - A complete 2D graphic library for drawing Text, Geometries, and Images. \[BSD] [website](https://skia.org/)

## [9. Awesome Ebpf](/content/zoidbergwill/awesome-ebpf/README.md)

### Articles and Presentations / Generic eBPF Presentations and Articles

*   [Cloudflare's blog posts on eBPF](https://blog.cloudflare.com/tag/ebpf/) - Different blog posts about networking use cases and low-level aspects of eBPF.
*   [Linux Extended BPF (eBPF) Tracing Tools](https://www.brendangregg.com/ebpf.html) - An in-depth collection of information around examples of performance analysis tools using eBPF. Contains also a section at the end of the page about other resources.

### eBPF Workflow: Tools and Utilities / eBPF on Other Platforms

*   [eBPF for Windows (⭐1.7k)](https://github.com/microsoft/ebpf-for-windows) - This project is a work-in-progress that allows using existing eBPF toolchains and APIs familiar in the Linux ecosystem to be used on top of Windows.

### Projects Related to eBPF / Security

*   [Falco](https://falco.org/) - A cloud-native runtime security project used as a Kubernetes threat detection engine.
*   [Sysmon for Linux (⭐1.2k)](https://github.com/Sysinternals/SysmonForLinux) - A security monitoring tool. It depends on [SysinternalsEBPF (⭐173)](https://github.com/Sysinternals/SysinternalsEBPF).
*   [Red Canary Linux Agent](https://redcanary.com/blog/ebpf-for-security) - Red Canary has started to incorporate eBPF to their Linux security sensor.
*   [Tracee (⭐2.5k)](https://github.com/aquasecurity/tracee) - A runtime security and forensics tool for Linux which uses eBPF technology to trace the system and applications at runtime, and analyze collected events to detect suspicious behavioral patterns.
*   [redcanary-ebpf-sensor (⭐61)](https://github.com/redcanaryco/redcanary-ebpf-sensor) - A set of BPF programs that gather security relevant event data from the Linux kernel. The BPF programs are combined into a single ELF file from which individual probes can be selectively loaded, depending on the running operating system and kernel version.
*   [bpflock - Lock Linux machines (⭐117)](https://github.com/linux-lock/bpflock) - An eBPF driven security tool for locking and auditing Linux machines.

### Projects Related to eBPF / Tools

*   [bpftrace](https://bpftrace.org/) - A tool for tracing with its own high-level tracing language. It is flexible enough to be envisioned as a Linux replacement for DTrace and SystemTap.
    *   [bpftrace Cheat Sheet](https://www.brendangregg.com/BPF/bpftrace-cheat-sheet.html) - Summary and cheat sheet for programming in bpftrace. Contains information about syntax, probe types, variables and functions.
*   [Embrace The Red: Offensive BPF!](https://embracethered.com/blog/tags/ebpf) - A series of posts around the introduction into BPF with a focus to an offensive setting, and also how its misuse can be detected. Posts include discussions on the rootkit capabilities of eBPF, or on which tracing type is needed for different use cases.
*   [eBPF: Block Linux Fileless Payload "Malware" Execution with BPF LSM](https://djalal.opendz.org/post/ebpf-block-linux-fileless-payload-execution-with-bpf-lsm/) - Blog post about how BPF can help detection and blocking fileless malware.
*   [Blackhat 2021: With Friends Like eBPF, Who Needs Enemies?](https://www.blackhat.com/us-21/briefings/schedule/#with-friends-like-ebpf-who-needs-enemies-23619) - Talk about an eBPF rootkit and how the capabilities of eBPF could be abused. The rootkit was also the object of a talk at Defcon, [eBPF, I thought we were friends !](https://defcon.org/html/defcon-29/dc-29-speakers.html#fournier).
*   [ebpfkit (⭐481)](https://github.com/Gui774ume/ebpfkit) - A rootkit that leverages multiple eBPF features to implement offensive security techniques.
*   [ebpfkit-monitor (⭐84)](https://github.com/Gui774ume/ebpfkit-monitor) - An utility to statically analyze eBPF bytecode or monitor suspicious eBPF activity at runtime. It was specifically designed to detect ebpfkit.
*   [Bad BPF (⭐298)](https://github.com/pathtofile/bad-bpf) - A collection of malicious eBPF programs that make use of eBPF's ability to read and write user data in between the usermode program and the kernel.

## [10. Awesome Snmp](/content/eozer/awesome-snmp/README.md)

### Publications / Books

*   [The Networknomicon, or SNMP Mastery by Abdul Alhazred and Michael W. Lucas](https://mwl.io/nonfiction/networking#networknomicon) - The Simple Network Management Protocol, SNMP, empowers you to invoke ancient standards from the void. SNMP exposes the secrets of your network and servers, and--if you're careless--reconfigures them into unspeakable nightmares. It exposes your inadequate brain to the vast alien dimensions underlying modern computing.
*   [SNMP Mastery by Michael W. Lucas](https://mwl.io/nonfiction/networking#snmp) - SNMP, Simple Network Management Protocol, Four lies in one acronym?

## [11. Public Apis](/content/public-apis/public-apis/README.md)

### Books

- API: [Wizard World](https://wizard-world-api.herokuapp.com/swagger/index.html)

  Description: Get information from the Harry Potter universe

  Auth: No

  HTTPS: Yes

  CORS: Yes



## [12. Awesome Purescript](/content/passy/awesome-purescript/README.md)

### Binary Serialization

*   [purescript-arraybuffer-builder (⭐4)](https://github.com/jamesdbrock/purescript-arraybuffer-builder) - Builder for serializing ArrayBuffer
*   [purescript-parsing-dataview (⭐3)](https://github.com/jamesdbrock/purescript-parsing-dataview) - Parser for deserializing ArrayBuffer
*   [purescript-protobuf (⭐47)](https://github.com/xc-jp/purescript-protobuf) - Google Protocol Buffers

---

- Prev: [Feb 15, 2022](/content/2022/02/15/README.md)
- Next: [Feb 13, 2022](/content/2022/02/13/README.md)