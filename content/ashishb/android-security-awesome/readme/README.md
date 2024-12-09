# Android Security Awesome Overview

A collection of android security related resources

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/ashishb/android-security-awesome/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 ashishb/android-security-awesome](https://github.com/ashishb/android-security-awesome) · ⭐ 8.3K · 🏷️ Security

[ [Daily](/content/ashishb/android-security-awesome/README.md) / [Weekly](/content/ashishb/android-security-awesome/week/README.md) / Overview ]

---

# android-security-awesome ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

[![Link Liveness Checker](https://github.com/ashishb/android-security-awesome/actions/workflows/validate-links.yml/badge.svg)](https://github.com/ashishb/android-security-awesome/actions/workflows/validate-links.yml) [![Lint Shell scripts](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-shell-script.yaml/badge.svg)](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-shell-script.yaml) [![Lint Markdown](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-markdown.yaml/badge.svg)](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-markdown.yaml)  [![Lint YAML](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-yaml.yaml/badge.svg)](https://github.com/ashishb/android-security-awesome/actions/workflows/lint-yaml.yaml)

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
6.  [App Detonator](https://appdetonator.run/) - Detonate APK binary to provide source code level details including app author, signature, build, and manifest information. 3 Analysis/day free quota.
7.  [Pithus](https://beta.pithus.org/) - Open-Source APK analyzer. Still in Beta for the moment and limited to static analysis for the moment. It is possible to hunt malware with Yara rules. More [here](https://beta.pithus.org/about/).
8.  [Oversecured](https://oversecured.com/) - Enterprise vulnerability scanner for Android and iOS apps, it offers app owners and developers the ability to secure each new version of a mobile app by integrating Oversecured into the development process. Not free.
9.  [AppSweep by Guardsquare](https://appsweep.guardsquare.com/) - Free, fast Android application security testing for developers
10. [Koodous](https://koodous.com) - Performs static/dynamic malware analysis over a vast repository of Android samples and checks them against public and private Yara rules.
11. [Immuniweb](https://www.immuniweb.com/mobile/). Does an "OWASP Mobile Top 10 Test", "Mobile App Privacy Check" and an application permissions test. The free tier is 4 tests per day incl. report after registration
12. ~~[BitBaan](https://malab.bitbaan.com/)~~
13. ~~[AVC UnDroid](http://undroid.av-comparatives.info/)~~
14. ~~[AMAaaS](https://amaaas.com) - Free Android Malware Analysis Service. A bare-metal service features static and dynamic analysis for Android applications. A product of [MalwarePot](https://malwarepot.com/index.php/AMAaaS)~~.
15. ~~[AppCritique](https://appcritique.boozallen.com) - Upload your Android APKs and receive comprehensive free security assessments~~
16. ~~[NVISO ApkScan](https://apkscan.nviso.be/) - sunsetting on Oct 31, 2019~~
17. ~~[Mobile Malware Sandbox](http://www.mobilemalware.com.br/analysis/index_en.php)~~
18. ~~[IBM Security AppScan Mobile Analyzer](https://appscan.bluemix.net/mobileAnalyzer) - not free~~
19. ~~[Visual Threat](https://www.visualthreat.com/) - no longer an Android app analyzer~~
20. ~~[Tracedroid](http://tracedroid.few.vu.nl/)~~
21. ~~[habo](https://habo.qq.com/) - 10/day~~
22. ~~[CopperDroid](http://copperdroid.isg.rhul.ac.uk/copperdroid/)~~
23. ~~[SandDroid](http://sanddroid.xjtu.edu.cn/)~~
24. ~~[Stowaway](http://www.android-permissions.org/)~~
25. ~~[Anubis](http://anubis.iseclab.org/)~~
26. ~~[Mobile app insight](http://www.mobile-app-insight.org)~~
27. ~~[Mobile-Sandbox](http://mobile-sandbox.com)~~
28. ~~[Ijiami](http://safe.ijiami.cn/)~~
29. ~~[Comdroid](http://www.comdroid.org/)~~
30. ~~[Android Sandbox](http://www.androidsandbox.net/)~~
31. ~~[Foresafe](http://www.foresafe.com/scan)~~
32. ~~[Dexter](https://dexter.dexlabs.org/)~~
33. ~~[MobiSec Eacus](http://www.mobiseclab.org/eacus.jsp)~~
34. ~~[Fireeye](https://fireeye.ijinshan.com/)- max 60MB 15/day~~
35. ~~[approver](https://approver.talos-sec.com/) - Approver  is a fully automated security analysis and risk assessment platform for Android and iOS apps. Not free.~~

### Static Analysis Tools

1.  [Androwarn (⭐485)](https://github.com/maaaaz/androwarn/) - detect and warn the user about potential malicious behaviors developed by an Android application.
2.  [ApkAnalyser (⭐1k)](https://github.com/sonyxperiadev/ApkAnalyser)
3.  [APKInspector (⭐833)](https://github.com/honeynet/apkinspector/)
4.  [Droid Intent Data Flow Analysis for Information Leakage](https://insights.sei.cmu.edu/library/didfail/)
5.  [DroidLegacy](https://bitbucket.org/srl/droidlegacy)
6.  [FlowDroid](https://blogs.uni-paderborn.de/sse/tools/flowdroid/)
7.  [Android Decompiler](https://www.pnfsoftware.com/) – not free
8.  [PSCout](https://security.csl.toronto.edu/pscout/) - A tool that extracts the permission specification from the Android OS source code using static analysis
9.  [Amandroid](http://amandroid.sireum.org/)
10. [SmaliSCA (⭐317)](https://github.com/dorneanu/smalisca) - Smali Static Code Analysis
11. [CFGScanDroid (⭐59)](https://github.com/douggard/CFGScanDroid) - Scans and compares CFG against CFG of malicious applications
12. [Madrolyzer (⭐102)](https://github.com/maldroid/maldrolyzer) - extracts actionable data like C\&C, phone number etc.
13. [SPARTA](https://www.cs.washington.edu/sparta) - verifies (proves) that an app satisfies an information-flow security policy; built on the [Checker Framework](https://types.cs.washington.edu/checker-framework/)
14. [ConDroid (⭐56)](https://github.com/JulianSchuette/ConDroid) - Performs a combination of symbolic + concrete execution of the app
15. [DroidRA (⭐50)](https://github.com/serval-snt-uni-lu/DroidRA)
16. [RiskInDroid (⭐141)](https://github.com/ClaudiuGeorgiu/RiskInDroid) - A tool for calculating the risk of Android apps based on their permissions, with an online demo available.
17. [SUPER (⭐422)](https://github.com/SUPERAndroidAnalyzer/super) - Secure, Unified, Powerful and Extensible Rust Android Analyzer
18. [ClassyShark (⭐7.5k)](https://github.com/google/android-classyshark) - Standalone binary inspection tool that can browse any Android executable and show important info.
19. [StaCoAn (⭐830)](https://github.com/vincentcox/StaCoAn) - Cross-platform tool that aids developers, bug-bounty hunters, and ethical hackers in performing static code analysis on mobile applications. This tool was created with a big focus on usability and graphical guidance in the user interface.
20. [JAADAS (⭐349)](https://github.com/flankerhqd/JAADAS) - Joint intraprocedural and interprocedural program analysis tool to find vulnerabilities in Android apps, built on Soot and Scala
21. [Quark-Engine (⭐1.3k)](https://github.com/quark-engine/quark-engine) - An Obfuscation-Neglect Android Malware Scoring System
22. [One Step Decompiler (⭐252)](https://github.com/b-mueller/apkx) - Android APK Decompilation for the Lazy
23. [APKLeaks (⭐5k)](https://github.com/dwisiswant0/apkleaks) - Scanning APK file for URIs, endpoints & secrets.
24. [Mobile Audit (⭐206)](https://github.com/mpast/mobileAudit) - Web application for performing Static Analysis and detecting malware in Android APKs.
25. ~~[Smali CFG generator](https://github.com/EugenioDelfa/Smali-CFGs)~~
26. ~~[Several tools from PSU](http://siis.cse.psu.edu/tools.html)~~

### App Vulnerability Scanners

1.  [QARK (⭐3.2k)](https://github.com/linkedin/qark/) - QARK by LinkedIn is for app developers to scan apps for security issues
2.  [AndroBugs (⭐1.1k)](https://github.com/AndroBugs/AndroBugs_Framework)
3.  [Nogotofail (⭐2.9k)](https://github.com/google/nogotofail)
4.  ~~[Devknox](https://devknox.io/) - IDE plugin to build secure Android apps. Not maintained anymore.~~

### Dynamic Analysis Tools

1.  [Android DBI frameowork](http://www.mulliner.org/blog/blosxom.cgi/security/androiddbiv02.html)
2.  [Androl4b (⭐1.1k)](https://github.com/sh4hin/Androl4b)- A Virtual Machine For Assessing Android applications, Reverse Engineering and Malware Analysis
3.  [House (⭐1.4k)](https://github.com/nccgroup/house)- House: A runtime mobile application analysis toolkit with a Web GUI, powered by Frida, written in Python.
4.  [Mobile-Security-Framework MobSF (⭐18k)](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - Mobile Security Framework is an intelligent, all-in-one open-source mobile application (Android/iOS) automated pen-testing framework capable of performing static, dynamic analysis and web API testing.
5.  [AppUse](https://appsec-labs.com/AppUse/) – custom build for penetration testing
6.  [Droidbox (⭐760)](https://github.com/pjlantz/droidbox)
7.  [Drozer (⭐4k)](https://github.com/mwrlabs/drozer)
8.  [Xposed](https://forum.xda-developers.com/xposed/xposed-installer-versions-changelog-t2714053) - equivalent of doing Stub-based code injection but without any modifications to the binary
9.  [Inspeckage (⭐2.8k)](https://github.com/ac-pm/Inspeckage) - Android Package Inspector - dynamic analysis with API hooks, start unexported activities, and more. (Xposed Module)
10. [Android Hooker (⭐408)](https://github.com/AndroidHooker/hooker) - Dynamic Java code instrumentation (requires the Substrate Framework)
11. [ProbeDroid (⭐197)](https://github.com/ZSShen/ProbeDroid) - Dynamic Java code instrumentation
12. [DECAF (⭐808)](https://github.com/sycurelab/DECAF) - Dynamic Executable Code Analysis Framework based on QEMU (DroidScope is now an extension to DECAF)
13. [CuckooDroid (⭐580)](https://github.com/idanr1986/cuckoo-droid) - Android extension for Cuckoo sandbox
14. [Mem (⭐66)](https://github.com/MobileForensicsResearch/mem) - Memory analysis of Android (root required)
15. [Crowdroid](http://www.ida.liu.se/labs/rtslab/publications/2011/spsm11-burguera.pdf) – unable to find the actual tool
16. [AuditdAndroid (⭐45)](https://github.com/nwhusted/AuditdAndroid) – android port of auditd, not under active development anymore
17. [Android Security Evaluation Framework](https://code.google.com/p/asef/) - not under active development anymore
18. [Aurasium (⭐37)](https://github.com/xurubin/aurasium) – Practical security policy enforcement for Android apps via bytecode rewriting and in-place reference monitor.
19. [Android Linux Kernel modules (⭐206)](https://github.com/strazzere/android-lkms)
20. [StaDynA (⭐23)](https://github.com/zyrikby/StaDynA) - a system supporting security app analysis in the presence of dynamic code update features (dynamic class loading and reflection). This tool combines static and dynamic analysis of Android applications in order to reveal the hidden/updated behavior and extend static analysis results with this information.
21. [DroidAnalytics (⭐29)](https://github.com/zhengmin1989/DroidAnalytics) - incomplete
22. [Vezir Project (⭐103)](https://github.com/oguzhantopgul/Vezir-Project) - Virtual Machine for Mobile Application Pentesting and Mobile Malware Analysis
23. [MARA (⭐630)](https://github.com/xtiankisutsa/MARA_Framework) - Mobile Application Reverse Engineering and Analysis Framework
24. [Taintdroid](http://appanalysis.org) - requires AOSP compilation
25. [ARTist](https://artist.cispa.saarland) - a flexible open-source instrumentation and hybrid analysis framework for Android apps and Android's Java middleware. It is based on the Android Runtime's (ART) compiler and modifies code during on-device compilation.
26. [Android Malware Sandbox (⭐281)](https://github.com/Areizen/Android-Malware-Sandbox)
27. [AndroPyTool (⭐356)](https://github.com/alexMyG/AndroPyTool) - a tool for extracting static and dynamic features from Android APKs. It combines different well-known Android app analysis tools such as DroidBox, FlowDroid, Strace, AndroGuard, or VirusTotal analysis.
28. [Runtime Mobile Security (RMS) (⭐2.6k)](https://github.com/m0bilesecurity/RMS-Runtime-Mobile-Security) - is a powerful web interface that helps you to manipulate Android and iOS Apps at Runtime
29. [PAPIMonitor (⭐51)](https://github.com/Dado1513/PAPIMonitor) – PAPIMonitor (Python API Monitor for Android apps) is a Python tool based on Frida for monitoring user-select APIs during the app execution.
30. [Android\_application\_analyzer (⭐153)](https://github.com/NotSoSecure/android_application_analyzer) - The tool is used to analyze the content of the Android application in local storage.
31. [Decompiler.com](https://www.decompiler.com/) - Online APK and Java decompiler
32. [friTap (⭐292)](https://github.com/fkie-cad/friTap)- - Intercept SSL/TLS connections with Frida; Allows TLS key extraction and decryption of TLS payload as PCAP on Android in real-time.
33. ~~[Appie](https://manifestsecurity.com/appie/) - Appie is a software package that has been pre-configured to function as an Android Pentesting Environment. It is completely portable and can be carried on a USB stick or smartphone. This is a one-stop answer for all the tools needed in Android Application Security Assessment and an awesome alternative to existing virtual machines.~~
34. ~~[Android Tamer](https://androidtamer.com/) - Virtual / Live Platform for Android Security Professionals~~
35. ~~[Android Malware Analysis Toolkit](http://www.mobilemalware.com.br/amat/download.html) - (Linux distro) Earlier it use to be an [online analyzer](http://dunkelheit.com.br/amat/analysis/index_en.php)~~
36. ~~[Android Reverse Engineering](https://redmine.honeynet.org/projects/are/wiki) – ARE (android reverse engineering) not under active development anymore~~
37. ~~[ViaLab Community Edition](https://www.nowsecure.com/blog/2014/09/09/introducing-vialab-community-edition/)~~
38. ~~[Mercury](https://labs.mwrinfosecurity.com/tools/2012/03/16/mercury/)~~
39. ~~[Cobradroid](https://thecobraden.com/projects/cobradroid/) – custom image for malware analysis~~

### Reverse Engineering

1.  [Smali/Baksmali (⭐6.4k)](https://github.com/JesusFreke/smali) – apk decompilation
2.  [emacs syntax coloring for smali files (⭐33)](https://github.com/strazzere/Emacs-Smali)
3.  [vim syntax coloring for smali files](http://codetastrophe.com/smali.vim)
4.  [AndBug (⭐595)](https://github.com/swdunlop/AndBug)
5.  [Androguard (⭐5.3k)](https://github.com/androguard/androguard) – powerful, integrates well with other tools
6.  [Apktool](https://ibotpeaches.github.io/Apktool/) – really useful for compilation/decompilation (uses smali)
7.  [Android Framework for Exploitation (⭐188)](https://github.com/appknox/AFE)
8.  [Bypass signature and permission checks for IPCs (⭐83)](https://github.com/iSECPartners/Android-KillPermAndSigChecks)
9.  [Android OpenDebug (⭐129)](https://github.com/iSECPartners/Android-OpenDebug) – make any application on the device debuggable (using cydia substrate).
10. [Dex2Jar (⭐12k)](https://github.com/pxb1988/dex2jar) - dex to jar converter
11. [Enjarify (⭐2.7k)](https://github.com/google/enjarify) - dex to jar converter from Google
12. [Dedexer](https://sourceforge.net/projects/dedexer/)
13. [Fino (⭐106)](https://github.com/sysdream/fino)
14. [Frida](https://www.frida.re/) - inject javascript to explore applications and a [GUI tool (⭐174)](https://github.com/antojoseph/diff-gui) for it
15. [Indroid](https://bitbucket.org/aseemjakhar/indroid) – thread injection kit
16. [IntentSniffer](https://www.nccgroup.com/us/our-research/intent-sniffer/)
17. [Introspy (⭐467)](https://github.com/iSECPartners/Introspy-Android)
18. [Jad](https://varaneckas.com/jad/) - Java decompiler
19. [JD-GUI (⭐14k)](https://github.com/java-decompiler/jd-gui) - Java decompiler
20. [CFR](http://www.benf.org/other/cfr/) - Java decompiler
21. [Krakatau (⭐2k)](https://github.com/Storyyeller/Krakatau) - Java decompiler
22. [FernFlower (⭐3.5k)](https://github.com/fesh0r/fernflower) - Java decompiler
23. [Redexer (⭐164)](https://github.com/plum-umd/redexer) – apk manipulation
24. [Simplify Android deobfuscator (⭐4.5k)](https://github.com/CalebFenton/simplify)
25. [Bytecode viewer (⭐15k)](https://github.com/Konloch/bytecode-viewer)
26. [Radare2 (⭐21k)](https://github.com/radare/radare2)
27. [Jadx (⭐42k)](https://github.com/skylot/jadx)
28. [Dwarf (⭐1.3k)](https://github.com/iGio90/Dwarf) - GUI for reverse engineering
29. [Andromeda (⭐702)](https://github.com/secrary/Andromeda) - Another basic command-line reverse engineering tool
30. [apk-mitm (⭐4k)](https://github.com/shroudedcode/apk-mitm) - A CLI application that prepares Android APK files for HTTPS inspection
31. [Noia (⭐113)](https://github.com/0x742/noia) - Simple Android application sandbox file browser tool
32. [Obfuscapk (⭐1.1k)](https://github.com/ClaudiuGeorgiu/Obfuscapk) - Obfuscapk is a modular Python tool for obfuscating Android apps without needing their source code.
33. [ARMANDroid (⭐12)](https://github.com/Mobile-IoT-Security-Lab/ARMANDroid) - ARMAND (Anti-Repackaging through Multi-patternAnti-tampering based on Native Detection) is a novel anti-tampering protection scheme that embeds logic bombs and AT detection nodes directly in the apk file without needing their source code.
34. [MVT (Mobile Verification Toolkit) (⭐10k)](https://github.com/mvt-project/mvt) - a collection of utilities to simplify and automate the process of gathering forensic traces helpful to identify a potential compromise of Android and iOS devices
35. [Dexmod (⭐52)](https://github.com/google/dexmod) - tool to exemplify patching Dalvik bytecode in a DEX (Dalvik Executable) file, and assist in the static analysis of Android applications.
36. ~~[Procyon](https://bitbucket.org/mstrobel/procyon/wiki/Java%20Decompiler) - Java decompiler~~
37. ~~[Smali viewer](http://blog.avlyun.com/wp-content/uploads/2014/04/SmaliViewer.zip)~~
38. ~~[ZjDroid](https://github.com/BaiduSecurityLabs/ZjDroid)~~, ~~[fork/mirror](https://github.com/yangbean9/ZjDroid)~~
39. ~~[Dare](http://siis.cse.psu.edu/dare/index.html) – .dex to .class converter~~

### Fuzz Testing

1.  [Radamsa Fuzzer (⭐65)](https://github.com/anestisb/radamsa-android)
2.  [Honggfuzz (⭐3.1k)](https://github.com/google/honggfuzz)
3.  [An Android port of the Melkor ELF fuzzer (⭐60)](https://github.com/anestisb/melkor-android)
4.  [Media Fuzzing Framework for Android (⭐332)](https://github.com/fuzzing/MFFA)
5.  [AndroFuzz (⭐39)](https://github.com/jonmetz/AndroFuzz)
6.  [QuarksLab's Android Fuzzing (⭐109)](https://github.com/quarkslab/android-fuzzing)
7.  ~~[IntentFuzzer](https://www.nccgroup.trust/us/about-us/resources/intent-fuzzer/)~~

### App Repackaging Detectors

1.  [FSquaDRA (⭐70)](https://github.com/zyrikby/FSquaDRA) - a tool for detecting repackaged Android applications based on app resources hash comparison.

### Market Crawlers

1.  [Google Play crawler (Java) (⭐569)](https://github.com/Akdeniz/google-play-crawler)
2.  [Google Play crawler (Python) (⭐880)](https://github.com/egirault/googleplay-api)
3.  [Google Play crawler (Node) (⭐270)](https://github.com/dweinstein/node-google-play) - get app details and download apps from the official Google Play Store.
4.  [Aptoide downloader (Node) (⭐25)](https://github.com/dweinstein/node-aptoide) - download apps from Aptoide third-party Android market
5.  [Appland downloader (Node) (⭐16)](https://github.com/dweinstein/node-appland) - download apps from Appland third-party Android market
6.  [PlaystoreDownloader (⭐1.1k)](https://github.com/ClaudiuGeorgiu/PlaystoreDownloader) - PlaystoreDownloader is a tool for downloading Android applications directly from the Google Play Store. After an initial (one-time) configuration, applications can be downloaded by specifying their package name.
7.  [APK Downloader](https://apkcombo.com/apk-downloader/) Online Service to download APK from Playstore for specific Android Device Configuration
8.  ~~[Apkpure](https://apkpure.com/) - Online apk downloader. Provides also its own app for downloading.~~

### Misc Tools

1.  [smalihook](http://androidcracking.blogspot.com/2011/03/original-smalihook-java-source.html)
2.  [AXMLPrinter2](http://code.google.com/p/android4me/downloads/detail?name=AXMLPrinter2.jar) - to convert binary XML files to human-readable XML files
3.  [adb autocomplete (⭐252)](https://github.com/mbrubeck/android-completion)
4.  [mitmproxy (⭐37k)](https://github.com/mitmproxy/mitmproxy)
5.  [dockerfile/androguard (⭐41)](https://github.com/dweinstein/dockerfile-androguard)
6.  [Android Vulnerability Test Suite (⭐1k)](https://github.com/AndroidVTS/android-vts) - android-vts scans a device for set of vulnerabilities
7.  [AppMon (⭐1.6k)](https://github.com/dpnishant/appmon)- AppMon is an automated framework for monitoring and tampering with system API calls of native macOS, iOS, and Android apps. It is based on Frida.
8.  [Internal Blue (⭐694)](https://github.com/seemoo-lab/internalblue) - Bluetooth experimentation framework based on Reverse Engineering of Broadcom Bluetooth Controllers
9.  [Android Mobile Device Hardening (⭐202)](https://github.com/SecTheTech/AMDH) - AMDH scans and hardens the device's settings and lists harmful installed Apps based on permissions.
10. ~~[Android Device Security Database](https://www.android-device-security.org/client/datatable) - Database of security features of Android devices~~
11. ~~[Opcodes table for quick reference](http://ww38.xchg.info/corkami/opcodes_tables.pdf)~~
12. ~~[APK-Downloader](http://codekiem.com/2012/02/24/apk-downloader/)~~ - seems dead now
13. ~~[Dalvik opcodes](http://pallergabor.uw.hu/androidblog/dalvik_opcodes.html)~~

### Vulnerable Applications for practice

1.  [Damn Insecure Vulnerable Application (DIVA) (⭐973)](https://github.com/payatu/diva-android)
2.  [Vuldroid (⭐62)](https://github.com/jaiswalakshansh/Vuldroid)
3.  [ExploitMe Android Labs](http://securitycompass.github.io/AndroidLabs/setup.html)
4.  [GoatDroid (⭐239)](https://github.com/jackMannino/OWASP-GoatDroid-Project)
5.  [Android InsecureBank (⭐1.3k)](https://github.com/dineshshetty/Android-InsecureBankv2)
6.  [Insecureshop (⭐234)](https://github.com/optiv/insecureshop)
7.  [Oversecured Vulnerable Android App (OVAA) (⭐657)](https://github.com/oversecured/ovaa)

## Academic/Research/Publications/Books

### Research Papers

1.  [Exploit Database](https://www.exploit-db.com/papers/)
2.  [Android security-related presentations (⭐167)](https://github.com/jacobsoo/AndroidSlides)
3.  [A good collection of static analysis papers](https://tthtlc.wordpress.com/2011/09/01/static-analysis-of-android-applications/)

### Books

1.  [SEI CERT Android Secure Coding Standard](https://wiki.sei.cmu.edu/confluence/display/android/Android+Secure+Coding+Standard)

### Others

1.  [OWASP Mobile Security Testing Guide Manual (⭐12k)](https://github.com/OWASP/owasp-mstg)
2.  [doridori/Android-Security-Reference (⭐922)](https://github.com/doridori/Android-Security-Reference)
3.  [android app security checklist (⭐855)](https://github.com/b-mueller/android_app_security_checklist)
4.  [Mobile App Pentest Cheat Sheet (⭐4.6k)](https://github.com/tanprathan/MobileApp-Pentest-Cheatsheet)
5.  [Android Reverse Engineering 101 by Daniele Altomare (Web Archive link)](https://web.archive.org/web/20180721134044/http://www.fasteque.com:80/android-reverse-engineering-101-part-1/)
6.  ~~[Mobile Security Reading Room](https://mobile-security.zeef.com) - A reading room that contains well-categorized technical reading material about mobile penetration testing, mobile malware, mobile forensics, and all kind of mobile security-related topics~~

## Exploits/Vulnerabilities/Bugs

### List

1.  [Android Security Bulletins](https://source.android.com/security/bulletin/)
2.  [Android's reported security vulnerabilities](https://www.cvedetails.com/vulnerability-list/vendor_id-1224/product_id-19997/Google-Android.html)
3.  [AOSP - Issue tracker](https://code.google.com/p/android/issues/list?can=2\&q=priority=Critical\&sort=-opened)
4.  [OWASP Mobile Top 10 2016](https://www.owasp.org/index.php/Mobile_Top_10_2016-Top_10)
5.  [Exploit Database](https://www.exploit-db.com/search/?action=search\&q=android) - click search
6.  [Vulnerability Google Doc](https://docs.google.com/spreadsheet/pub?key=0Am5hHW4ATym7dGhFU1A4X2lqbUJtRm1QSWNRc3E0UlE\&single=true\&gid=0\&output=html)
7.  [Google Android Security Team’s Classifications for Potentially Harmful Applications (Malware)](https://source.android.com/security/reports/Google_Android_Security_PHA_classifications.pdf)
8.  ~~[Android Devices Security Patch Status](https://kb.androidtamer.com/Device_Security_Patch_tracker/)~~

### Malware

1.  [androguard - Database Android Malware wiki](https://code.google.com/p/androguard/wiki/DatabaseAndroidMalwares)
2.  [Android Malware Github repo (⭐1.1k)](https://github.com/ashishb/android-malware)
3.  [Android Malware Genome Project](http://www.malgenomeproject.org/) - contains 1260 malware samples categorized into 49 different malware families, free for research purposes.
4.  [Contagio Mobile Malware Mini Dump](http://contagiominidump.blogspot.com)
5.  [Drebin](https://www.sec.tu-bs.de/~danarp/drebin/)
6.  [Hudson Rock](https://www.hudsonrock.com/threat-intelligence-cybercrime-tools) - Free cybercrime intelligence toolset that can indicate if a specific APK package was compromised in an Infostealer malware attack.
7.  [Kharon Malware Dataset](http://kharon.gforge.inria.fr/dataset/) - 7 malware which have been reverse-engineered and documented
8.  [Android Adware and General Malware Dataset](https://www.unb.ca/cic/datasets/android-adware.html)
9.  [AndroZoo](https://androzoo.uni.lu/) - AndroZoo is a growing Android application collection from several sources, including the official Google Play app market.
10. ~~[Android PRAGuard Dataset](http://pralab.diee.unica.it/en/AndroidPRAGuardDataset) - The dataset contains 10479 samples, obtained by obfuscating the MalGenome and the Contagio Minidump datasets with seven different obfuscation techniques.~~
11. ~~[Admire](http://admire.necst.it/)~~

### Bounty Programs

1.  [Android Security Reward Program](https://www.google.com/about/appsecurity/android-rewards/)

### How to report Security issues

1.  [Android - reporting security issues](https://source.android.com/security/overview/updates-resources.html#report-issues)
2.  [Android Reports and Resources (⭐1.5k)](https://github.com/B3nac/Android-Reports-and-Resources) - List of Android Hackerone disclosed reports and other resources

## Contributing

Your contributions are always welcome!

