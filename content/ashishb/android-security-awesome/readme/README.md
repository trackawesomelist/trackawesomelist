# Android Security Awesome Overview

A collection of android security related resources

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/ashishb/android-security-awesome/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 ashishb/android-security-awesome](https://github.com/ashishb/android-security-awesome) · ⭐ 9K · 🏷️ Security

[ [Daily](/content/ashishb/android-security-awesome/README.md) / [Weekly](/content/ashishb/android-security-awesome/week/README.md) / Overview ]

---

# android-security-awesome ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

[![Link Liveness Checker](https://github.com/ashishb/android-security-awesome/actions/workflows/validate-links.yml/badge.svg)](https://github.com/ashishb/android-security-awesome/actions/workflows/validate-links.yml)

[![Lint Shell scripts](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-shell-script.yaml/badge.svg)](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-shell-script.yaml)
[![Lint Markdown](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-markdown.yaml/badge.svg)](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-markdown.yaml)
[![Lint YAML](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-yaml.yaml/badge.svg)](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-yaml.yaml)
[![Lint GitHub Actions](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-github-actions.yaml/badge.svg)](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-github-actions.yaml)
![GitHub contributors](https://img.shields.io/github/contributors/ashishb/android-security-awesome)

A collection of Android security-related resources.

1.  [Tools](#tools)
2.  [Academic/Research/Publications/Books](#academic)
3.  [Exploits/Vulnerabilities/Bugs](#exploits)

## Tools

### Online Analyzers

1.  [AndroTotal](http://andrototal.org/)
2.  [Appknox](https://www.appknox.com/) - not free
3.  [Virustotal](https://www.virustotal.com/) - max 128MB
4.  [Fraunhofer App-ray](http://app-ray.co/) - not free
5.  [NowSecure Lab Automated](https://www.nowsecure.com/blog/2016/09/19/announcing-nowsecure-lab-automated/) - Enterprise tool for mobile app security testing both Android and iOS mobile apps. Lab Automated features dynamic and static analysis on real devices in the cloud to return results in minutes. Not free
6.  [App Detonator](https://appdetonator.run/) - Detonate APK binary to provide source code level details, including app author, signature, build, and manifest information. 3 Analysis/day free quota.
7.  [Pithus](https://beta.pithus.org/) - Open-Source APK analyzer. Still in Beta and limited to static analysis for the moment. It is possible to hunt malware with Yara rules. More [here](https://beta.pithus.org/about/).
8.  [Oversecured](https://oversecured.com/) - Enterprise vulnerability scanner for Android and iOS apps; it offers app owners and developers the ability to secure each new version of a mobile app by integrating Oversecured into the development process. Not free.
9.  [AppSweep by Guardsquare](https://appsweep.guardsquare.com/) - Free, fast Android application security testing for developers
10. [Koodous](https://koodous.com) - Performs static/dynamic malware analysis over a vast repository of Android samples and checks them against public and private Yara rules.
11. [Immuniweb](https://www.immuniweb.com/mobile/). Does an "OWASP Mobile Top 10 Test", "Mobile App Privacy Check", and an application permissions test. The free tier is 4 tests per day, including report after registration
12. [ANY.RUN](https://app.any.run/) - An interactive cloud-based malware analysis platform with support for Android application analysis. Limited free plan available.
13. ~~[BitBaan](https://malab.bitbaan.com/)~~
14. ~~[AVC UnDroid](http://undroid.av-comparatives.info/)~~
15. ~~[AMAaaS](https://amaaas.com) - Free Android Malware Analysis Service. A bare-metal service features static and dynamic analysis for Android applications. A product of [MalwarePot](https://malwarepot.com/index.php/AMAaaS)~~.
16. ~~[AppCritique](https://appcritique.boozallen.com) - Upload your Android APKs and receive comprehensive free security assessments~~
17. ~~[NVISO ApkScan](https://apkscan.nviso.be/) - sunsetting on Oct 31, 2019~~
18. ~~[Mobile Malware Sandbox](http://www.mobilemalware.com.br/analysis/index_en.php)~~
19. ~~[IBM Security AppScan Mobile Analyzer](https://appscan.bluemix.net/mobileAnalyzer) - not free~~
20. ~~[Visual Threat](https://www.visualthreat.com/) - no longer an Android app analyzer~~
21. ~~[Tracedroid](http://tracedroid.few.vu.nl/)~~
22. ~~[habo](https://habo.qq.com/) - 10/day~~
23. ~~[CopperDroid](http://copperdroid.isg.rhul.ac.uk/copperdroid/)~~
24. ~~[SandDroid](http://sanddroid.xjtu.edu.cn/)~~
25. ~~[Stowaway](http://www.android-permissions.org/)~~
26. ~~[Anubis](http://anubis.iseclab.org/)~~
27. ~~[Mobile app insight](http://www.mobile-app-insight.org)~~
28. ~~[Mobile-Sandbox](http://mobile-sandbox.com)~~
29. ~~[Ijiami](http://safe.ijiami.cn/)~~
30. ~~[Comdroid](http://www.comdroid.org/)~~
31. ~~[Android Sandbox](http://www.androidsandbox.net/)~~
32. ~~[Foresafe](http://www.foresafe.com/scan)~~
33. ~~[Dexter](https://dexter.dexlabs.org/)~~
34. ~~[MobiSec Eacus](http://www.mobiseclab.org/eacus.jsp)~~
35. ~~[Fireeye](https://fireeye.ijinshan.com/)- max 60MB 15/day~~
36. ~~[approver](https://approver.talos-sec.com/) - Approver  is a fully automated security analysis and risk assessment platform for Android and iOS apps. Not free.~~

### Static Analysis Tools

1.  [Androwarn (⭐515)](https://github.com/maaaaz/androwarn/) - detect and warn the user about potential malicious behaviors developed by an Android application.
2.  [ApkAnalyser (⭐1k)](https://github.com/sonyxperiadev/ApkAnalyser)
3.  [APKInspector (⭐848)](https://github.com/honeynet/apkinspector/)
4.  [Droid Intent Data Flow Analysis for Information Leakage](https://insights.sei.cmu.edu/library/didfail/)
5.  [DroidLegacy](https://bitbucket.org/srl/droidlegacy)
6.  [FlowDroid](https://blogs.uni-paderborn.de/sse/tools/flowdroid/)
7.  [Android Decompiler](https://www.pnfsoftware.com/) – not free
8.  [PSCout](https://security.csl.toronto.edu/pscout/) - A tool that extracts the permission specification from the Android OS source code using static analysis
9.  [Amandroid](http://amandroid.sireum.org/)
10. [SmaliSCA (⭐324)](https://github.com/dorneanu/smalisca) - Smali Static Code Analysis
11. [CFGScanDroid (⭐60)](https://github.com/douggard/CFGScanDroid) - Scans and compares the CFG against the CFG of malicious applications
12. [Madrolyzer (⭐109)](https://github.com/maldroid/maldrolyzer) - extracts actionable data like C\&C, phone number etc.
13. [ConDroid (⭐56)](https://github.com/JulianSchuette/ConDroid) - Performs a combination of symbolic + concrete execution of the app
14. [DroidRA (⭐51)](https://github.com/serval-snt-uni-lu/DroidRA)
15. [RiskInDroid (⭐156)](https://github.com/ClaudiuGeorgiu/RiskInDroid) - A tool for calculating the risk of Android apps based on their permissions, with an online demo available.
16. [SUPER (⭐424)](https://github.com/SUPERAndroidAnalyzer/super) - Secure, Unified, Powerful, and Extensible Rust Android Analyzer
17. [ClassyShark (⭐7.6k)](https://github.com/google/android-classyshark) - A Standalone binary inspection tool that can browse any Android executable and show important info.
18. [StaCoAn (⭐855)](https://github.com/vincentcox/StaCoAn) - Cross-platform tool that aids developers, bug-bounty hunters, and ethical hackers in performing static code analysis on mobile applications. This tool was created with a big focus on usability and graphical guidance in the user interface.
19. [JAADAS (⭐349)](https://github.com/flankerhqd/JAADAS) - Joint intraprocedural and interprocedural program analysis tool to find vulnerabilities in Android apps, built on Soot and Scala
20. [Quark-Engine (⭐1.6k)](https://github.com/quark-engine/quark-engine) - An Obfuscation-Neglect Android Malware Scoring System
21. [One Step Decompiler (⭐285)](https://github.com/b-mueller/apkx) - Android APK Decompilation for the Lazy
22. [APKLeaks (⭐5.7k)](https://github.com/dwisiswant0/apkleaks) - Scanning APK file for URIs, endpoints & secrets.
23. [Mobile Audit (⭐222)](https://github.com/mpast/mobileAudit) - Web application for performing Static Analysis and detecting malware in Android APKs.
24. [Detekt (⭐6.8k)](https://github.com/detekt/detekt) - Static code analysis for Kotlin
25. [APKdevastate (⭐8)](https://github.com/rafigk2v9c/APKdevastate/) - Advanced analysis software for APK payloads created by RATs.
26. ~~[Smali CFG generator](https://github.com/EugenioDelfa/Smali-CFGs)~~
27. ~~[Several tools from PSU](http://siis.cse.psu.edu/tools.html)~~
28. ~~[SPARTA](https://www.cs.washington.edu/sparta) - verifies (proves) that an app satisfies an information-flow security policy; built on the [Checker Framework](https://types.cs.washington.edu/checker-framework/)~~

### App Vulnerability Scanners

1.  [QARK (⭐3.3k)](https://github.com/linkedin/qark/) - QARK by LinkedIn is for app developers to scan apps for security issues
2.  [AndroBugs (⭐1.2k)](https://github.com/AndroBugs/AndroBugs_Framework)
3.  [Nogotofail (⭐2.9k)](https://github.com/google/nogotofail)
4.  ~~[Devknox](https://devknox.io/) - IDE plugin to build secure Android apps. Not maintained anymore.~~

### Dynamic Analysis Tools

1.  [Android DBI frameowork](http://www.mulliner.org/blog/blosxom.cgi/security/androiddbiv02.html)
2.  [Androl4b (⭐1.2k)](https://github.com/sh4hin/Androl4b)- A Virtual Machine For Assessing Android applications, Reverse Engineering and Malware Analysis
3.  [House (⭐1.5k)](https://github.com/nccgroup/house)- House: A runtime mobile application analysis toolkit with a Web GUI, powered by Frida, written in Python.
4.  [Mobile-Security-Framework MobSF (⭐20k)](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - Mobile Security Framework is an intelligent, all-in-one open-source mobile application (Android/iOS) automated pen-testing framework capable of performing static, dynamic analysis, and web API testing.
5.  [Droidbox (⭐786)](https://github.com/pjlantz/droidbox)
6.  [Drozer (⭐4.4k)](https://github.com/mwrlabs/drozer)
7.  [Xposed](https://forum.xda-developers.com/xposed/xposed-installer-versions-changelog-t2714053) - equivalent of doing Stub-based code injection but without any modifications to the binary
8.  [Inspeckage (⭐2.9k)](https://github.com/ac-pm/Inspeckage) - Android Package Inspector - dynamic analysis with API hooks, start unexported activities, and more. (Xposed Module)
9.  [Android Hooker (⭐413)](https://github.com/AndroidHooker/hooker) - Dynamic Java code instrumentation (requires the Substrate Framework)
10. [ProbeDroid (⭐199)](https://github.com/ZSShen/ProbeDroid) - Dynamic Java code instrumentation
11. [DECAF (⭐832)](https://github.com/sycurelab/DECAF) - Dynamic Executable Code Analysis Framework based on QEMU (DroidScope is now an extension to DECAF)
12. [CuckooDroid (⭐596)](https://github.com/idanr1986/cuckoo-droid) - Android extension for Cuckoo sandbox
13. [Mem (⭐68)](https://github.com/MobileForensicsResearch/mem) - Memory analysis of Android (root required)
14. [Crowdroid](http://www.ida.liu.se/labs/rtslab/publications/2011/spsm11-burguera.pdf) – unable to find the actual tool
15. [AuditdAndroid (⭐45)](https://github.com/nwhusted/AuditdAndroid) – Android port of auditd, not under active development anymore
16. [Android Security Evaluation Framework](https://code.google.com/p/asef/) - not under active development anymore
17. [Aurasium (⭐38)](https://github.com/xurubin/aurasium) – Practical security policy enforcement for Android apps via bytecode rewriting and in-place reference monitoring.
18. [Android Linux Kernel modules (⭐216)](https://github.com/strazzere/android-lkms)
19. [StaDynA (⭐24)](https://github.com/zyrikby/StaDynA) - a system supporting security app analysis in the presence of dynamic code update features (dynamic class loading and reflection). This tool combines static and dynamic analysis of Android applications in order to reveal the hidden/updated behavior and extend static analysis results with this information.
20. [DroidAnalytics (⭐29)](https://github.com/zhengmin1989/DroidAnalytics) - incomplete
21. [Vezir Project (⭐111)](https://github.com/oguzhantopgul/Vezir-Project) - Virtual Machine for Mobile Application Pentesting and Mobile Malware Analysis
22. [MARA (⭐655)](https://github.com/xtiankisutsa/MARA_Framework) - Mobile Application Reverse Engineering and Analysis Framework
23. [Taintdroid](http://appanalysis.org) - requires AOSP compilation
24. [ARTist](https://artist.cispa.saarland) - a flexible open-source instrumentation and hybrid analysis framework for Android apps and Android's Java middleware. It is based on the Android Runtime's (ART) compiler and modifies code during on-device compilation.
25. [Android Malware Sandbox (⭐293)](https://github.com/Areizen/Android-Malware-Sandbox)
26. [AndroPyTool (⭐374)](https://github.com/alexMyG/AndroPyTool) - a tool for extracting static and dynamic features from Android APKs. It combines different well-known Android app analysis tools such as DroidBox, FlowDroid, Strace, AndroGuard, and VirusTotal analysis.
27. [Runtime Mobile Security (RMS) (⭐2.9k)](https://github.com/m0bilesecurity/RMS-Runtime-Mobile-Security) - is a powerful web interface that helps you to manipulate Android and iOS Apps at Runtime
28. [PAPIMonitor (⭐79)](https://github.com/Dado1513/PAPIMonitor) – PAPIMonitor (Python API Monitor for Android apps) is a Python tool based on Frida for monitoring user-select APIs during the app execution.
29. [Android\_application\_analyzer (⭐167)](https://github.com/NotSoSecure/android_application_analyzer) - The tool is used to analyze the content of the Android application in local storage.
30. [Decompiler.com](https://www.decompiler.com/) - Online APK and Java decompiler
31. [friTap (⭐433)](https://github.com/fkie-cad/friTap)- Intercept SSL/TLS connections with Frida; Allows TLS key extraction and decryption of TLS payload as PCAP on Android in real-time.
32. [HacknDroid (⭐109)](https://github.com/RaffaDNDM/HacknDroid) - A tool designed to automate various Mobile Application Penetration Testing (MAPT) tasks and facilitate interaction with Android devices.
33. [adbsploit (⭐854)](https://github.com/mesquidar/adbsploit) - tools for exploiting device via ADB
34. [Brida (⭐1.8k)](https://github.com/federicodotta/Brida) - Burp Suite extension that, working as a bridge between Burp and Frida, lets you use and manipulate the applications' own methods while tampering with the traffic exchanged between the applications and their back-end services/servers.
35. [MPT (⭐35)](https://github.com/ByteSnipers/mobile-pentest-toolkit) - MPT (Mobile Pentest Toolkit) is a must-have solution for your Android penetration testing workflows. This tool allows you to automate security tasks.
36. [Andriller (⭐1.5k)](https://github.com/den4uk/andriller) - software utility with a collection of forensic tools for smartphones. It performs read-only, forensically sound, non-destructive acquisition from Android devices.
37. ~~[AppUse](https://appsec-labs.com/AppUse/) – custom build for penetration testing~~
38. ~~[Appie](https://manifestsecurity.com/appie/) - Appie is a software package that has been pre-configured to function as an Android Pentesting Environment. It is completely portable and can be carried on a USB stick or smartphone. This is a one-stop answer for all the tools needed in Android Application Security Assessment and an awesome alternative to existing virtual machines.~~
39. ~~[Android Tamer](https://androidtamer.com/) - Virtual / Live Platform for Android Security Professionals~~
40. ~~[Android Malware Analysis Toolkit](http://www.mobilemalware.com.br/amat/download.html) - (Linux distro) Earlier, it used to be an [online analyzer](http://dunkelheit.com.br/amat/analysis/index_en.php)~~
41. ~~[Android Reverse Engineering](https://redmine.honeynet.org/projects/are/wiki) – ARE (android reverse engineering) is not under active development anymore~~
42. ~~[ViaLab Community Edition](https://www.nowsecure.com/blog/2014/09/09/introducing-vialab-community-edition/)~~
43. ~~[Mercury](https://labs.mwrinfosecurity.com/tools/2012/03/16/mercury/)~~
44. ~~[Cobradroid](https://thecobraden.com/projects/cobradroid/) – custom image for malware analysis~~

### Reverse Engineering

1.  [Smali/Baksmali (⭐6.6k)](https://github.com/JesusFreke/smali) – apk decompilation
2.  [emacs syntax coloring for smali files (⭐34)](https://github.com/strazzere/Emacs-Smali)
3.  [vim syntax coloring for smali files](http://codetastrophe.com/smali.vim)
4.  [AndBug (⭐601)](https://github.com/swdunlop/AndBug)
5.  [Androguard (⭐5.9k)](https://github.com/androguard/androguard) – powerful, integrates well with other tools
6.  [Apktool](https://ibotpeaches.github.io/Apktool/) – really useful for compilation/decompilation (uses smali)
7.  [Android Framework for Exploitation (⭐196)](https://github.com/appknox/AFE)
8.  [Bypass signature and permission checks for IPCs (⭐84)](https://github.com/iSECPartners/Android-KillPermAndSigChecks)
9.  [Android OpenDebug (⭐134)](https://github.com/iSECPartners/Android-OpenDebug) – make any application on the device debuggable (using Cydia Substrate).
10. [Dex2Jar (⭐13k)](https://github.com/pxb1988/dex2jar) - dex to jar converter
11. [Enjarify (⭐2.7k)](https://github.com/google/enjarify) - dex to jar converter from Google
12. [Dedexer](https://sourceforge.net/projects/dedexer/)
13. [Fino (⭐108)](https://github.com/sysdream/fino)
14. [Frida](https://www.frida.re/) - inject JavaScript to explore applications and a [GUI tool (⭐181)](https://github.com/antojoseph/diff-gui) for it
15. [Indroid](https://bitbucket.org/aseemjakhar/indroid) – thread injection kit
16. [Introspy (⭐481)](https://github.com/iSECPartners/Introspy-Android)
17. [Jad](https://varaneckas.com/jad/) - Java decompiler
18. [JD-GUI (⭐15k)](https://github.com/java-decompiler/jd-gui) - Java decompiler
19. [CFR](http://www.benf.org/other/cfr/) - Java decompiler
20. [Krakatau (⭐2.2k)](https://github.com/Storyyeller/Krakatau) - Java decompiler
21. [FernFlower (⭐4.1k)](https://github.com/fesh0r/fernflower) - Java decompiler
22. [Redexer (⭐169)](https://github.com/plum-umd/redexer) – apk manipulation
23. [Simplify Android deobfuscator (⭐4.6k)](https://github.com/CalebFenton/simplify)
24. [Bytecode viewer (⭐15k)](https://github.com/Konloch/bytecode-viewer)
25. [Radare2 (⭐23k)](https://github.com/radare/radare2)
26. [Jadx (⭐46k)](https://github.com/skylot/jadx)
27. [Dwarf (⭐1.3k)](https://github.com/iGio90/Dwarf) - GUI for reverse engineering
28. [Andromeda (⭐709)](https://github.com/secrary/Andromeda) - Another basic command-line reverse engineering tool
29. [apk-mitm (⭐4.8k)](https://github.com/shroudedcode/apk-mitm) - A CLI application that prepares Android APK files for HTTPS inspection
30. [Noia (⭐123)](https://github.com/0x742/noia) - Simple Android application sandbox file browser tool
31. [Obfuscapk (⭐1.2k)](https://github.com/ClaudiuGeorgiu/Obfuscapk) — Obfuscapk is a modular Python tool for obfuscating Android apps without requiring their source code.
32. [ARMANDroid (⭐14)](https://github.com/Mobile-IoT-Security-Lab/ARMANDroid) - ARMAND (Anti-Repackaging through Multi-pattern, Anti-tampering based on Native Detection) is a novel anti-tampering protection scheme that embeds logic bombs and AT detection nodes directly in the apk file without needing their source code.
33. [MVT (Mobile Verification Toolkit) (⭐12k)](https://github.com/mvt-project/mvt) - a collection of utilities to simplify and automate the process of gathering forensic traces helpful to identify a potential compromise of Android and iOS devices
34. [Dexmod (⭐63)](https://github.com/google/dexmod) - a tool to exemplify patching Dalvik bytecode in a DEX (Dalvik Executable) file and assist in the static analysis of Android applications.
35. [odex-patcher (⭐95)](https://github.com/giacomoferretti/odex-patcher) - Run arbitrary code by patching OAT files
36. [PhoneSpolit-Pro (⭐5.4k)](https://github.com/AzeemIdrisi/PhoneSploit-Pro) - An all-in-one hacking tool to remotely exploit Android devices using ADB and Metasploit Framework to get a Meterpreter session.
37. [APKLab (⭐3.6k)](https://github.com/APKLab/APKLab) - plugin for VS code to analyze APKs
38. ~~[IntentSniffer](https://www.nccgroup.com/us/our-research/intent-sniffer/)~~
39. ~~[Procyon](https://bitbucket.org/mstrobel/procyon/wiki/Java%20Decompiler) - Java decompiler~~
40. ~~[Smali viewer](http://blog.avlyun.com/wp-content/uploads/2014/04/SmaliViewer.zip)~~
41. ~~[ZjDroid](https://github.com/BaiduSecurityLabs/ZjDroid)~~, ~~[fork/mirror](https://github.com/yangbean9/ZjDroid)~~
42. ~~[Dare](http://siis.cse.psu.edu/dare/index.html) – .dex to .class converter~~

### Fuzz Testing

1.  [Radamsa Fuzzer (⭐66)](https://github.com/anestisb/radamsa-android)
2.  [Honggfuzz (⭐3.3k)](https://github.com/google/honggfuzz)
3.  [An Android port of the Melkor ELF fuzzer (⭐61)](https://github.com/anestisb/melkor-android)
4.  [Media Fuzzing Framework for Android (⭐332)](https://github.com/fuzzing/MFFA)
5.  [AndroFuzz (⭐38)](https://github.com/jonmetz/AndroFuzz)
6.  [QuarksLab's Android Fuzzing (⭐124)](https://github.com/quarkslab/android-fuzzing)
7.  ~~[IntentFuzzer](https://www.nccgroup.trust/us/about-us/resources/intent-fuzzer/)~~

### App Repackaging Detectors

1.  [FSquaDRA (⭐73)](https://github.com/zyrikby/FSquaDRA) - a tool for detecting repackaged Android applications based on app resources hash comparison.

### Market Crawlers

1.  [Google Play crawler (Java) (⭐588)](https://github.com/Akdeniz/google-play-crawler)
2.  [Google Play crawler (Python) (⭐895)](https://github.com/egirault/googleplay-api)
3.  [Google Play crawler (Node) (⭐278)](https://github.com/dweinstein/node-google-play) - get app details and download apps from the official Google Play Store.
4.  [Aptoide downloader (Node) (⭐25)](https://github.com/dweinstein/node-aptoide) - download apps from Aptoide third-party Android market
5.  [Appland downloader (Node) (⭐18)](https://github.com/dweinstein/node-appland) - download apps from Appland third-party Android market
6.  [PlaystoreDownloader (⭐1.2k)](https://github.com/ClaudiuGeorgiu/PlaystoreDownloader) - PlaystoreDownloader is a tool for downloading Android applications directly from the Google Play Store. After an initial (one-time) configuration, applications can be downloaded by specifying their package name.
7.  [APK Downloader](https://apkcombo.com/apk-downloader/) Online Service to download APK from the Play Store for a specific Android Device Configuration
8.  ~~[Apkpure](https://apkpure.com/) - Online apk downloader. Also, it provides its own app for downloading.~~

### Misc Tools

1.  [smalihook](http://androidcracking.blogspot.com/2011/03/original-smalihook-java-source.html)
2.  [AXMLPrinter2](http://code.google.com/p/android4me/downloads/detail?name=AXMLPrinter2.jar) - to convert binary XML files to human-readable XML files
3.  [adb autocomplete (⭐258)](https://github.com/mbrubeck/android-completion)
4.  [mitmproxy (⭐41k)](https://github.com/mitmproxy/mitmproxy)
5.  [dockerfile/androguard (⭐44)](https://github.com/dweinstein/dockerfile-androguard)
6.  [Android Vulnerability Test Suite (⭐1k)](https://github.com/AndroidVTS/android-vts) - android-vts scans a device for set of vulnerabilities
7.  [AppMon (⭐1.6k)](https://github.com/dpnishant/appmon)- AppMon is an automated framework for monitoring and tampering with system API calls of native macOS, iOS, and Android apps. It is based on Frida.
8.  [Internal Blue (⭐746)](https://github.com/seemoo-lab/internalblue) - Bluetooth experimentation framework based on the Reverse Engineering of Broadcom Bluetooth Controllers
9.  [Android Mobile Device Hardening (⭐214)](https://github.com/SecTheTech/AMDH) - AMDH scans and hardens the device's settings and lists harmful installed Apps based on permissions.
10. [Firmware Extractor (⭐339)](https://github.com/AndroidDumps/Firmware_extractor) - Extract given archive to images
11. [ARMv7 payload that provides arbitrary code execution on MediaTek bootloaders (⭐132)](https://github.com/R0rt1z2/kaeru)
12. ~~[Android Device Security Database](https://www.android-device-security.org/client/datatable) - Database of security features of Android devices~~
13. ~~[Opcodes table for quick reference](http://ww38.xchg.info/corkami/opcodes_tables.pdf)~~
14. ~~[APK-Downloader](http://codekiem.com/2012/02/24/apk-downloader/)~~ - seems dead now
15. ~~[Dalvik opcodes](http://pallergabor.uw.hu/androidblog/dalvik_opcodes.html)~~

### Vulnerable Applications for practice

1.  [Damn Insecure Vulnerable Application (DIVA) (⭐1.1k)](https://github.com/payatu/diva-android)
2.  [Vuldroid (⭐65)](https://github.com/jaiswalakshansh/Vuldroid)
3.  [ExploitMe Android Labs](http://securitycompass.github.io/AndroidLabs/setup.html)
4.  [GoatDroid (⭐247)](https://github.com/jackMannino/OWASP-GoatDroid-Project)
5.  [Android InsecureBank (⭐1.4k)](https://github.com/dineshshetty/Android-InsecureBankv2)
6.  [Insecureshop (⭐249)](https://github.com/optiv/insecureshop)
7.  [Oversecured Vulnerable Android App (OVAA) (⭐723)](https://github.com/oversecured/ovaa)

## Academic/Research/Publications/Books

### Research Papers

1.  [Exploit Database](https://www.exploit-db.com/papers/)
2.  [Android security-related presentations (⭐174)](https://github.com/jacobsoo/AndroidSlides)
3.  [A good collection of static analysis papers](https://tthtlc.wordpress.com/2011/09/01/static-analysis-of-android-applications/)

### Books

1.  [SEI CERT Android Secure Coding Standard](https://wiki.sei.cmu.edu/confluence/display/android/Android+Secure+Coding+Standard)

### Others

1.  [OWASP Mobile Security Testing Guide Manual (⭐13k)](https://github.com/OWASP/owasp-mstg)
2.  [doridori/Android-Security-Reference (⭐973)](https://github.com/doridori/Android-Security-Reference)
3.  [android app security checklist (⭐886)](https://github.com/b-mueller/android_app_security_checklist)
4.  [Mobile App Pentest Cheat Sheet (⭐5.1k)](https://github.com/tanprathan/MobileApp-Pentest-Cheatsheet)
5.  [Android Reverse Engineering 101 by Daniele Altomare (Web Archive link)](https://web.archive.org/web/20180721134044/http://www.fasteque.com:80/android-reverse-engineering-101-part-1/)
6.  ~~[Mobile Security Reading Room](https://mobile-security.zeef.com) - A reading room that contains well-categorized technical reading material about mobile penetration testing, mobile malware, mobile forensics, and all kinds of mobile security-related topics~~

## Exploits/Vulnerabilities/Bugs

### List

1.  [Android Security Bulletins](https://source.android.com/security/bulletin/)
2.  [Android's reported security vulnerabilities](https://www.cvedetails.com/vulnerability-list/vendor_id-1224/product_id-19997/Google-Android.html)
3.  [OWASP Mobile Top 10 2016](https://www.owasp.org/index.php/Mobile_Top_10_2016-Top_10)
4.  [Exploit Database](https://www.exploit-db.com/search/?action=search\&q=android) - click search
5.  [Vulnerability Google Doc](https://docs.google.com/spreadsheet/pub?key=0Am5hHW4ATym7dGhFU1A4X2lqbUJtRm1QSWNRc3E0UlE\&single=true\&gid=0\&output=html)
6.  [Google Android Security Team’s Classifications for Potentially Harmful Applications (Malware)](https://source.android.com/security/reports/Google_Android_Security_PHA_classifications.pdf)
7.  ~~[Android Devices Security Patch Status](https://kb.androidtamer.com/Device_Security_Patch_tracker/)~~

### Malware

1.  [androguard - Database Android Malware wiki](https://code.google.com/p/androguard/wiki/DatabaseAndroidMalwares)
2.  [Android Malware Github repo (⭐1.2k)](https://github.com/ashishb/android-malware)
3.  [Android Malware Genome Project](http://www.malgenomeproject.org/) - contains 1260 malware samples categorized into 49 different malware families, free for research purposes.
4.  [Contagio Mobile Malware Mini Dump](http://contagiominidump.blogspot.com)
5.  [Drebin](https://www.sec.tu-bs.de/~danarp/drebin/)
6.  [Hudson Rock](https://www.hudsonrock.com/threat-intelligence-cybercrime-tools) - A Free cybercrime intelligence toolset that can indicate if a specific APK package was compromised in an Infostealer malware attack.
7.  [Kharon Malware Dataset](http://kharon.gforge.inria.fr/dataset/) - 7 malware which have been reverse-engineered and documented
8.  [Android Adware and General Malware Dataset](https://www.unb.ca/cic/datasets/android-adware.html)
9.  [AndroZoo](https://androzoo.uni.lu/) - AndroZoo is a growing Android application collection from several sources, including the official Google Play app market.
10. ~~[Android PRAGuard Dataset](http://pralab.diee.unica.it/en/AndroidPRAGuardDataset) - The dataset contains 10479 samples, obtained by obfuscating the MalGenome and the Contagio Minidump datasets with seven different obfuscation techniques.~~
11. ~~[Admire](http://admire.necst.it/)~~

### Bounty Programs

1.  [Android Security Reward Program](https://www.google.com/about/appsecurity/android-rewards/)

### How to report Security issues

1.  [Android - reporting security issues](https://source.android.com/security/overview/updates-resources.html#report-issues)
2.  [Android Reports and Resources (⭐1.6k)](https://github.com/B3nac/Android-Reports-and-Resources) - List of Android Hackerone disclosed reports and other resources

## Contributing

Your contributions are always welcome!

## 📖 Citation

```bibtex
@misc{
  author = {Ashish Bhatia - ashishb.net},
  title = {The most comprehensive collection of Android Security related resources},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/ashishb/android-security-awesome}}
}
```

This repository has been cited in [10+ papers](https://scholar.google.com/scholar?q=github.com%2Fashishb%2Fandroid-security-awesome)

