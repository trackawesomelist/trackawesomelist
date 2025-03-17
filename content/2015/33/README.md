# Awesome List Updates on Aug 17 - Aug 23, 2015

30 awesome lists updated this week.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Linux Containers](/content/Friz-zy/awesome-linux-containers/week/README.md)

### Foundations

*   [OPEN CONTAINER INITIATIVE](https://www.opencontainers.org/)\
    The Open Container Initiative is a lightweight, open governance structure, to be formed under the auspices of the Linux Foundation, for the express purpose of creating open industry standards around container formats and runtime.
*   [Cloud Native Computing Foundation](https://cncf.io/)\
    The Cloud Native Computing Foundation will create and drive the adoption of a new set of common container technologies informed by technical merit and end user value, and inspired by Internet-scale computing.

### Specifications

*   [Open Container Specifications (⭐2.9k)](https://github.com/opencontainers/specs)\
    This project is where the Open Container Initiative Specifications are written. This is a work in progress.
*   [App Container basics (⭐8.8k)](https://github.com/coreos/rkt/blob/master/Documentation/app-container.md)\
    App Container (appc) is an open specification that defines several aspects of how to run applications in containers: an image format, runtime environment, and discovery protocol.

### Clouds

*   [Google Cloud Platform](https://cloud.google.com/container-engine/)\
    Run Docker containers on Google Cloud Platform, powered by Kubernetes. Google Container Engine actively schedules your containers, based on declared needs, on a managed cluster of virtual machines.

### Hypervisors

*   [LXD (⭐4k)](https://github.com/lxc/lxd)\
    Daemon based on liblxc offering a REST API to manage LXC containers.
*   [OpenVZ](https://openvz.org/)\
    OpenVZ is container-based virtualization for Linux. OpenVZ creates multiple secure, isolated Linux containers (otherwise known as VEs or VPSs) on a single physical server enabling better server utilization and ensuring that applications do not conflict.

### Containers

*   [runc (⭐11k)](https://github.com/opencontainers/runc)\
    runc is a CLI tool for spawning and running containers according to the OCS specification.
*   [Rocket (⭐8.8k)](https://github.com/coreos/rkt)\
    rkt (pronounced "rock-it") is a CLI for running app containers on Linux. rkt is designed to be composable, secure, and fast. Based on AppC specification.
*   [LXC (⭐4.1k)](https://github.com/lxc/lxc)\
    LXC is the well known set of tools, templates, library and language bindings. It's pretty low level, very flexible and covers just about every containment feature supported by the upstream kernel.
*   [Vagga (⭐1.8k)](https://github.com/tailhook/vagga)\
    Vagga is a fully-userspace container engine inspired by Vagrant and Docker, specialized for development environments.
*   [libct (⭐101)](https://github.com/xemul/libct)\
    Libct is a containers management library which provides convenient API for frontend programs to rule a container during its whole lifetime.
*   [libvirt](https://libvirt.org/drvlxc.html)\
    A big toolkit to interact with the virtualization capabilities of recent versions of Linux (and other OSes).

### Sandboxes

*   [Firejail](https://l3net.wordpress.com/projects/firejail/)\
    Firejail is a SUID sandbox program that reduces the risk of security breaches by restricting the running environment of untrusted applications using Linux namespaces, seccomp-bpf and Linux capabilities.
*   [Subuser (⭐881)](https://github.com/subuser-security/subuser)\
    Securing the Linux desktop with Docker.
*   [Snappy](https://wiki.ubuntu.com/SecurityTeam/Specifications/SnappyConfinement)\
    Snappy Ubuntu Core is a new rendition of Ubuntu with transactional updates - a minimal server image with the same libraries as today’s Ubuntu, but applications are provided through a simpler mechanism.
*   [xdg-app](https://wiki.gnome.org/Projects/SandboxedApps)\
    xdg-app is a system for building, distributing and running sandboxed desktop applications on Linux.

### Partial Access

*   [nsenter](http://man7.org/linux/man-pages/man1/nsenter.1.html)\
    Run program with namespaces of other processes. Part of the util-linux.
*   [ip-netns](http://man7.org/linux/man-pages/man8/ip-netns.8.html)\
    Process network namespace management. Part of the iproute2.
*   [unshare](http://man7.org/linux/man-pages/man1/unshare.1.html)\
    Run program with some namespaces unshared from parent. Part of the util-linux.
*   [python-nsenter (⭐136)](https://github.com/zalando/python-nsenter)\
    This Python package allows entering Linux kernel namespaces (mount, IPC, net, PID, user and UTS) by doing the "setns" syscall.
*   [butter](https://pypi.python.org/pypi/butter)\
    Python library to interface to low level linux features (inotify, fanotify, timerfd, signalfd, eventfd, containers) with asyncio support.
*   [pyspaces (⭐87)](https://github.com/Friz-zy/pyspaces)\
    Works with Linux namespaces through glibc with pure python.

### Security / Links

*   [Are Docker containers really secure?](https://opensource.com/business/14/7/docker-security-selinux)
*   [Bringing new security features to Docker](https://opensource.com/business/14/9/security-for-docker)
*   [Docker, Linux Containers (LXC), and security](http://www.slideshare.net/jpetazzo/docker-linux-containers-lxc-and-security)
*   [For containers, security is problem #1](http://www.itworld.com/article/2920349/security/for-containers-security-is-problem-1.html)
*   [Linux Container Security](https://mjg59.dreamwidth.org/33170.html)
*   [Ask HN: Best Linux sandbox?](https://news.ycombinator.com/item?id=10030868)

### Security / Levels of security problems

*   regular application
*   always untrusted -> know it
*   suid bit -> mount with nosuid
*   limit available syscall -> seccomp-bpf, grsec
*   system services like cron, ssh
*   run as root -> isolate via bastion host or vm
*   using /dev -> "devices" control group\
    The following device nodes are created in the container by default.\
    The Docker images are also mounted with nodev, which means that even if a device node was pre-created in the image, it could not be used by processes within the container to talk to the kernel.\
    /dev/console,/dev/null,/dev/zero,/dev/full,/dev/tty\*,/dev/urandom,/dev/random,/dev/fuse
*   root calls -> capabilities (cap\_sys\_admin warning!)\
    Here is the current list of capabilities that Docker uses: chown, dac\_override, fowner, kill, setgid, setuid, setpcap, net\_bind\_service, net\_raw, sys\_chroot, mknod, setfcap, and audit\_write.\
    Docker removes several of these capabilities including the following:\
    CAP\_SETPCAP 	Modify process capabilities\
    CAP\_SYS\_MODULE 	Insert/Remove kernel modules\
    CAP\_SYS\_RAWIO 	Modify Kernel Memory\
    CAP\_SYS\_PACCT 	Configure process accounting\
    CAP\_SYS\_NICE 	Modify Priority of processes\
    CAP\_SYS\_RESOURCE 	Override Resource Limits\
    CAP\_SYS\_TIME 	Modify the system clock\
    CAP\_SYS\_TTY\_CONFIG 	Configure tty devices\
    CAP\_AUDIT\_WRITE 	Write the audit log\
    CAP\_AUDIT\_CONTROL 	Configure Audit Subsystem\
    CAP\_MAC\_OVERRIDE 	Ignore Kernel MAC Policy\
    CAP\_MAC\_ADMIN 	Configure MAC Configuration\
    CAP\_SYSLOG 	Modify Kernel printk behavior\
    CAP\_NET\_ADMIN 	Configure the network\
    CAP\_SYS\_ADMIN 	Catch all\
    uses /proc, /sys -> remount ro, drop cap\_sys\_admin; security modules like selinux or apparmor; some part of this fs are "namespace-aware"\
    Docker mounts these file systems into the container as "read-only" mount points.\
    . /sys\
    . /proc/sys\
    . /proc/sysrq-trigger\
    . /proc/irq\
    . /proc/bus\
    Copy-on-write file systems\
    Docker uses copy-on-write file systems. This means containers can use the same file system image as the base for the container. When a container writes content to the image, it gets written to a container specific file system. This prevents one container from seeing the changes of another container even if they wrote to the same file system image. Just as important, one container can not change the image content to effect the processes in another container.
*   uid 0 -> user namespaces, uid 0 mappet to random uid outside
*   system services like devices, network, filesystems
*   kernel drivers, network stack, security policies
*   general like immutable infrastructure
*   container is ro
*   write to small separate rw nosuid part

### Security / Technologies for security

*   SELinux
*   Cgroups
*   file systems under /sys
*   /proc/sys, /proc/sysrq-trigger, /proc/irq, /proc/bus
*   /dev/mem
*   /dev/sd\* file system devices
*   kernel modules

## [2. Awesome Erlang](/content/drobakowski/awesome-erlang/week/README.md)

### Miscellaneous

*   [erld (⭐194)](https://github.com/ShoreTel-Inc/erld) - erld is a small program designed to solve the problem of running Erlang programs as a UNIX daemon.

## [3. Awesome Typescript](/content/dzharii/awesome-typescript/week/README.md)

### Offline / Other (Plugins || Cross-platform || OSS || Free)

*   :octocat: [Typescript addin for (⭐30)](https://github.com/mrward/typescript-addin) MonoDevelop, SharpDevelop and Xamarin Studio;  a short [review article](http://lastexitcode.com/blog/2015/04/01/TypeScriptSupportInXamarinStudio/)

### :dollar: Paid Courses / Chrome Extensions

*   [Angular with TypeScript](http://www.pluralsight.com/courses/angular-typescript) (Pluralsight)

## [4. Engineering Blogs](/content/kilimchoi/engineering-blogs/week/README.md)

### Companies / L companies

*   LinkedIn <https://engineering.linkedin.com/blog>

## [5. Awesome Influxdb](/content/mark-rushakoff/awesome-influxdb/week/README.md)

### Projects / Dedicated

*   [Charmander (⭐63)](https://github.com/att-innovate/charmander) - Charmander is a lab environment for measuring and analyzing resource-scheduling algorithms
*   [sysinfo\_influxdb](https://github.com/novaquark/sysinfo_influxdb) - Collect and send system (linux) info to InfluxDB

### Libraries / Non-dedicated

*   [metrics (⭐313)](https://github.com/beberlei/metrics) - (PHP) Simple library that abstracts different metrics collectors. "I find this necessary to have a consistent and simple metrics (functional) API that doesn't cause vendor lock-in"

## [6. Awesome Salesforce](/content/mailtoharshit/awesome-salesforce/week/README.md)

### Mobile Development with Salesforce / Mobile SDK

*   [Salesfoce MobileSDK for Windows (⭐11)](https://github.com/forcedotcom/SalesforceMobileSDK-Windows)-Build the project normally in Visual Studio; everything should build fine. If you wish to create a new project and not use the NuGet versions of the core libraries, simply create a new project with the template, remove the NuGet reference and add references to Salesforce.SDK.Core, Salesforce.SDK.Store (for windows projects) or Salesforce.SDK.Phone for phone projects.

### Troubleshooting and queries / Official Salesforce Twitter Accounts

*   [Salesforce Developers](https://twitter.com/SalesforceDevs)
*   [Salesforce Docs](https://twitter.com/salesforcedocs)
*   [Salesforce Stack Exchange](https://twitter.com/StackSalesforce)
*   [Salesforce Service Cloud](https://twitter.com/ServiceCloud)
*   [Salesforce ForceDotComLabs](https://twitter.com/ForceDotComLabs)
*   [Salesforce SalesforceLive](https://twitter.com/SalesforceLive)
*   [Salesforce Engineering](https://twitter.com/SalesforceEng)
*   [Salesforce UX](https://twitter.com/SalesforceUX)

### Troubleshooting and queries / Technical Blogs

*   [Salesforce Engineering Blog](https://developer.salesforce.com/blogs/engineering/) - Covers latest update from engineering team, you will find updates about core engineering and product releated post and some awesome people to follow

## [7. Awesome Elixir](/content/h4cc/awesome-elixir/week/README.md)

### Framework Components

*   [phoenix\_html\_sanitizer (⭐28)](https://github.com/elixirstatus/phoenix_html_sanitizer) - HTML Sanitizer integration for Phoenix.

### Text and Numbers

*   [haikunator (⭐27)](https://github.com/knrz/Haikunator) - Generate Heroku-like memorable random names to use in your apps or anywhere else.

## [8. Awesome Sketch](/content/diessica/awesome-sketch/week/README.md)

### Videos / Tutorial-only

*   [Exploring Sketch plugins](https://www.youtube.com/playlist?list=PLLnpHn493BHHUZe9bihv37Z6CyXBTyb-9)

### Videos / Process of designing dashboards, mobile apps

*   [Sketch 3 Workflow playlist](https://www.youtube.com/playlist?list=PLdOb4Jg-Lxg-g4NyfQZkgkfwXJpMFwo5E)
*   [SketchApp TV playlists](https://www.youtube.com/channel/UCSdp5logiFTM3SyLJrHabOQ/playlists)

### Videos / General screencasts

*   [SketchCasts](http://www.sketchcasts.net/) *(paid mostly)*

### Community / Tutorials

*   [Sketch Hunt](http://sketchhunt.com/)
*   [Designer News](https://www.designernews.co/) *(people talk a lot about Sketch there!)*

### Plugins / Must-have :heart:

*   [Content Generator (⭐4.4k)](https://github.com/timuric/Content-generator-sketch-plugin)
*   [RenameIt (⭐1.4k)](https://github.com/rodi01/RenameIt)
*   [Sketch Measure (⭐7k)](https://github.com/utom/sketch-measure)
*   [Style Inventory (⭐1.8k)](https://github.com/getflourish/Sketch-Style-Inventory/)
*   [Dynamic Button (⭐1.1k)](https://github.com/ddwht/sketch-dynamic-button)
*   [Page Switch (⭐67)](https://github.com/mauehara/sketch-page-switch)
*   [Sketch Flex Layout (⭐1.7k)](https://github.com/hrescak/Sketch-Flex-Layout)

### Plugins / Nice-to-have :thumbsup:

*   [Handy Tools (⭐127)](https://github.com/webpatch/Handy-Tools/)
*   [Easier.cc](http://easier.cc/) (Files up to 5 MB)

### Other / Nice-to-have :thumbsup:

*   (Newsletter) [Sketch official newsletter](https://bohemian.curated.co/)
*   (Newsletter) [Sketch tricks](http://sketchtricks.com/)
*   (Resources) [SketchApp Resources](http://www.sketchappsources.com/)
*   (Resources) [SketchLand](http://sketch.land)
*   (Resources) [SketchResources](http://sketchresources.com/)
*   (Resources) [Sketchapp TV](http://sketchapp.tv/)
*   [SketchTips](http://www.sketchtips.info/), a blog about Sketch
*   [sketch-tricks on Medium](https://medium.com/sketch-tricks)

## [9. Awesome Python](/content/vinta/awesome-python/week/README.md)

### HTML Manipulation

*   [html5lib (⭐1.1k)](https://github.com/html5lib/html5lib-python) - A standards-compliant library for parsing and serializing HTML documents and fragments.
*   [lxml](http://lxml.de/) - A very fast, easy-to-use and versatile library for handling HTML and XML.
*   [pyquery (⭐2.3k)](https://github.com/gawel/pyquery) - A jQuery-like library for parsing HTML.
*   [xmltodict (⭐5.4k)](https://github.com/martinblech/xmltodict) - Working with XML feel like you are working with JSON.

### Processes

*   [sh (⭐6.9k)](https://github.com/amoffat/sh) - A full-fledged subprocess replacement for Python.

### Science

*   [astropy](http://www.astropy.org/) - A community Python library for Astronomy.
*   [bccb (⭐598)](https://github.com/chapmanb/bcbb) - Collection of useful code related to biological analysis.
*   [Biopython](http://biopython.org/wiki/Main_Page) - Biopython is a set of freely available tools for biological computation.
*   [cclib](http://cclib.github.io/) - A library for parsing and interpreting the results of computational chemistry packages.
*   [NumPy](http://www.numpy.org/) - A fundamental package for scientific computing with Python.
*   [PyMC (⭐8.5k)](https://github.com/pymc-devs/pymc3) - Markov Chain Monte Carlo sampling toolkit.
*   [statsmodels (⭐9.7k)](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python.
*   [SymPy (⭐13k)](https://github.com/sympy/sympy) - A Python library for symbolic mathematics.

### Third-party APIs

*   [google-api-python-client (⭐7.6k)](https://github.com/google/google-api-python-client) - Google APIs Client Library for Python.
*   [gspread (⭐7k)](https://github.com/burnash/gspread) - Google Spreadsheets Python API.
*   [twython (⭐1.9k)](https://github.com/ryanmcgrath/twython) - A Python wrapper for the Twitter API.

## [10. Awesome Answers](/content/cyberglot/awesome-answers/week/README.md)

### Programming Languages / JavaScript

*   [What are the actual uses of ES6 WeakMap?](http://stackoverflow.com/a/29416340)

### Programming Languages / Python

*   [Why are banks like JP Morgan and Bank of America Merrill Lynch using Python to replace historic legacy systems built in Java/C++?](http://qr.ae/RCkmhJ)
*   [What are killer Python tips which could make our coder lives more productive, easier and happier?](http://qr.ae/RCkmKa)
*   [What are some of the best time-saving tips for Python?](http://qr.ae/RCkmoh)

## [11. Awesome Polymer](/content/Granze/awesome-polymer/week/README.md)

### Tutorials/Guides

*   [Unit Testing](https://medium.com/@granze/polymer-unit-testing-d6a69910dc31)

### Directories

*   [open-elements](http://open-elements.org) Open for all elements working with polymer ^1.1

## [12. Awesome Dotnet](/content/quozd/awesome-dotnet/week/README.md)

### Machine Learning and Data Science

*   [numl (⭐430)](https://github.com/sethjuarez/numl) - Designed to include the most popular supervised and unsupervised learning algorithms while minimizing the friction involved with creating the predictive models.

### SDK and API Clients

*   [Azure PowerShell (⭐4.3k)](https://github.com/Azure/azure-powershell) - A set of PowerShell cmdlets for developers and administrators to develop, deploy and manage Microsoft Azure applications

## [13. Awesome Jvm](/content/deephacks/awesome-jvm/week/README.md)

### Garbage collectors

*   [G1](http://www.oracle.com/technetwork/java/javase/tech/g1-intro-jsp-135488.html) - The Garbage-First Garbage Collector.

### Languages

*   [Ceylon](http://ceylon-lang.org/) - Object-oriented, strong and static programming language with an emphasis on immutability, created by Red Hat.
*   [Clojure](http://clojure.org/) - Dialect of Lisp created by Rich Hickey. Dynamically typed with emphasis on functional programming.
*   [Erjang](http://www.erjang.org) - A JVM-based Erlang VM.
*   [Frege (⭐3.6k)](https://github.com/Frege/frege) - Pure functional programming language in the spirit of Haskell.
*   [Groovy](http://www.groovy-lang.org/) - Optionally typed and dynamic language, with static-typing and static compilation capabilities.
*   [Java](http://www.oracle.com/technetwork/java/javase/overview/index.html) - General-purpose, concurrent, strongly typed, class-based object-oriented language.
*   [JRuby](http://jruby.org) - Implementation of the Ruby language on the JVM.
*   [Jython](http://www.jython.org) - Python for the Java Platform.
*   [Kawa](http://www.gnu.org/software/kawa/) - Extension of the Scheme language, which is in the Lisp family of programming languages.
*   [Kotlin](http://kotlinlang.org/) - Statically typed programming language for the JVM, Android and the browser.
*   [Nashorn](http://openjdk.java.net/projects/nashorn/) - Lightweight high-performance JavaScript runtime in Java with a native JVM.
*   [Renjin](http://www.renjin.org/) - JVM-based interpreter for the R language for the statistical analysis
*   [Scala](http://www.scala-lang.org/) - Strong and static programming language that combine object-oriented and functional programming ideas.

### Nix tools

*   [atoptool](http://www.atoptool.nl/) - Logging of system and process activity for long-term analysis, highlighting overloaded system.
*   [javap](http://docs.oracle.com/javase/8/docs/technotes/tools/unix/javap.html) - Disassembles class files into code that reflects the java bytecode.
*   [jhat](http://docs.oracle.com/javase/8/docs/technotes/tools/unix/jhat.html) - Java Heap Analysis Tool
*   [jinfo](http://docs.oracle.com/javase/8/docs/technotes/tools/unix/jinfo.html) - Prints configuration information for a given process.
*   [jstack](http://docs.oracle.com/javase/8/docs/technotes/tools/unix/jstack.html) - Prints stack traces of threads for a given Java process.
*   [perf](https://perf.wiki.kernel.org/index.php/Main_Page) - Linux profiling with performance counters.
*   [sysstat](http://sebastien.godard.pagesperso-orange.fr) - Performance monitoring tools for Linux.

### Profilers

*   [BTrace (⭐5.2k)](https://github.com/jbachorik/btrace) - a safe, dynamic tracing tool for the Java platform.
*   [Chronon](http://chrononsystems.com) - Record your entire java program. Replay on any machine.
*   [GCViewer (⭐4.1k)](https://github.com/chewiebug/GCViewer) - GCViewer is a tool that visualizes verbose GC output.
*   [JProfiler](https://www.ej-technologies.com/products/jprofiler/overview.html) - Helps resolve performance bottlenecks, pin down memory leaks and understand threading issues.
*   [JVMTI](https://docs.oracle.com/javase/8/docs/technotes/guides/jvmti/) - Provide a native API to inspect the state and to control the execution of applications running in the JVM.
*   [Riemann JVM Profiler (⭐288)](https://github.com/riemann/riemann-jvm-profiler) - JVM agent which sends function-level profiler telemetry to a Riemann server for analysis, visualization, and storage.
*   [Swiss Java Knife (⭐3.1k)](https://github.com/aragozin/jvm-tools) - Small set of tools for JVM troublshooting, monitoring and profiling.
*   [Takipi](https://www.takipi.com/) - Tells you when and why code breaks in production.
*   [Zipkin (⭐16k)](https://github.com/openzipkin/zipkin) - A distributed tracing system gather timing data for disparate services developed by Twitter.

### Runtimes

*   [CRaSH](http://www.crashub.org/) - The shell for the Java Platform.
*   [Drip (⭐1.5k)](https://github.com/ninjudd/drip) - Fast JVM launching without the hassle of persistent JVMs.

### Virtual Machines

*   [Dalvik](https://source.android.com/devices/tech/dalvik/) - Android runtime (ART) is the managed runtime used by applications and some system services on Android.
*   [HotSpot](http://openjdk.java.net/groups/hotspot/) - HotSpot virtual machine maintained and distributed by Oracle Corporation.
*   [IBM J9](http://www.ibm.com/developerworks/java/jdk/) - JVM developed by IBM.

### Documentation

*   [The JVM specification](https://docs.oracle.com/javase/specs/jvms/se8/jvms8.pdf) - The Java Virtual
    Machine Specification Java SE 8 Edition.
*   [The Java Memory Model](http://www.cs.umd.edu/\~pugh/java/memoryModel/) - Starting point for discussions of and information concerning the Java Memory Model.
*   [The JSR-133 Cookbook for Compiler Writers](http://gee.cs.oswego.edu/dl/jmm/cookbook.html) - Unofficial guide to implementing the new Java Memory Model (JMM) specified by JSR-133.
*   [Garbage Collection Tuning Guide](http://docs.oracle.com/javase/8/docs/technotes/guides/vm/gctuning/) - HotSpot Virtual Machine Garbage Collection Tuning Guide.

### Communities

*   [concurrency-interest](http://altair.cs.oswego.edu/mailman/listinfo/concurrency-interest) - Discussion list for JSR-166.
*   [hotspot-compiler-dev](http://mail.openjdk.java.net/mailman/listinfo/hotspot-compiler-dev) - Technical discussion about the development of the HotSpot bytecode compilers.
*   [hotspot-dev](http://mail.openjdk.java.net/mailman/listinfo/hotspot-dev) - HotSpot development mailing list.
*   [hotspot-gc-dev](http://mail.openjdk.java.net/mailman/listinfo/hotspot-gc-dev) - Technical discussion about the development of the HotSpot garbage collectors.
*   [mechanical-sympathy](https://groups.google.com/forum/#!forum/mechanical-sympathy) - Discussing how to code sympathetically to and measure the underlying stack/platform so good performance can be extracted.

### Media

*   [JVM Language Summit 2015](http://openjdk.java.net/projects/mlvm/jvmlangsummit/) - JVM Language Summit 2015.
*   [Bits of advice for VM writers](https://www.youtube.com/watch?v=vzzABBxo44g) - Cliff Click.
*   [Understanding Java garbage collection ...](https://www.youtube.com/watch?v=_e5hujoTkgY) - Gil Tene.
*   [Faster Object Arrays](https://www.youtube.com/watch?v=bZuPTCaciLU) - Gil Tene at GOTO Conferences.
*   [Java Memory Model Pragmatics](https://www.youtube.com/watch?v=TxqsKzxyySo) - Aleksey Shipilev.

### People

*   [Aleksey Shipilëv](http://shipilev.net/) - Developing Oracle/Open JDK/Hotspot and other Java-related technologies.
*   [Brian Goetz](https://twitter.com/BrianGoetz) - Java Language Architect at Oracle.
*   [Cliff Click](http://www.cliffc.org/blog/) - Creator of the HotSpot Server Compiler.
*   [Dave Dice](https://blogs.oracle.com/dave/) - Senior research scientist in the Scalable Synchronization Research Group within Oracle.
*   [Doug Lea](http://g.oswego.edu/) - Author of the Java memory model.
*   [Gil Tene](https://twitter.com/giltene) - Azul Systems.
*   [John Rose](https://blogs.oracle.com/jrose/) - HotSpot developer.
*   [Martin Thompson](http://mechanical-sympathy.blogspot.se/) - Pasty faced performance gangster.
*   [Nitsan Wakart](http://psy-lob-saw.blogspot.se/2014/03/where-is-my-safepoint.html) - Azul Systems.

## [14. Awesome Html5](/content/diegocard/awesome-html5/week/README.md)

### Development APIs / Permissions

*   [Permissions API for the Web by Google](https://developers.google.com/web/updates/2015/04/permissions-api-for-the-web)

### Web Workers / WebRTC

*   [How fast are web workers?](https://hacks.mozilla.org/2015/07/how-fast-are-web-workers/)
*   [Web Workers in MDN](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers)

## [15. Awesome Transit](/content/CUTR-at-USF/awesome-transit/week/README.md)

### GTFS Libraries / Java

*   [OneBusAway GTFS Modules (⭐131)](https://github.com/OneBusAway/onebusaway-gtfs-modules/wiki) - A Java-based library for reading, writing, and transforming public transit data in the GTFS format, including database support.

### GTFS Realtime Libraries & Demo Apps / Rust

*   [GTFS-realtime Exporter (⭐17)](https://github.com/OneBusAway/onebusaway-gtfs-realtime-exporter/wiki) - A Java-based tool that assists in producing and sharing a GTFS-relatime feed.
*   [GTFS-realtime Alerts Producer Demo (⭐8)](https://github.com/OneBusAway/onebusaway-gtfs-realtime-alerts-producer-demo/wiki) - A Java-based demo project for producing GTFS-realtime Service Alerts.
*   [GTFS-realtime TripUpdates & VehiclePositions Producer Demo (⭐11)](https://github.com/OneBusAway/onebusaway-gtfs-realtime-trip-updates-producer-demo/wiki) - A Java-based demo project for producing GTFS-realtime TripUpdates (estimated arrivals) and Vehicle Positions.

### Web Apps (open source) / Rust

*   [GTFS-realtime Alerts Producer Web Application (⭐1)](https://github.com/OneBusAway/onebusaway-service-alerts) - A Java-based web application for producing GTFS-realtime Service Alerts.
*   [Instabus](http://instabus.org) - Realtime map of Austin's (CapMetro) public transit. Has no server/backend dependency at all and runs completely on GitHub pages.
*   [OpenTripPlanner Client GWT (⭐11)](https://github.com/mecatran/OpenTripPlanner-client-gwt) - A Google Web Toolkit-based web interface for OpenTripPlanner
*   [HRT BUS Web app (⭐17)](https://github.com/Code4HR/hrt-bus-api) - HRT Bus API publishes real time bus data from Hampton Roads Transit through an application programming interface for developers to make apps from it.
*   [Transit-Map (⭐361)](https://github.com/vasile/transit-map) - Web app that animates vehicles (markers) on a map using the public transport timetables to interpolate their positions along the routes (polylines).

### GTFS Realtime Convertors / Rust

*   [Syncromatics API to GTFS-realtime (⭐2)](https://github.com/CUTR-at-USF/bullrunner-gtfs-realtime-generator) - A Java-based command-line utility to convert from the [Syncromatics API](http://www.syncromatics.com/) format to GTFS-realtime TripUpdates and VehiclePositons.
*   [KV6,15,17, and ARNU to GTFS-realtime (⭐1)](https://github.com/bliksemlabs/bliksemintegration-realtime) - Java-based tool to process incoming KV6,15,17 and ARNU and match them to static transit data present in a RID integration database. It then proceeds to export this data as ARNU RITinfo, GTFS(realtime) and KV78turbo
*   [WMATA BusPositions API to GTFS-realtime (⭐12)](https://github.com/kurtraschke/wmata-gtfsrealtime) - Java-based tool to convert from WMATA's [BusPositions API](https://developer.wmata.com/docs/services/54763629281d83086473f231/operations/5476362a281d830c946a3d68) and Alert RSS feeds from [MetroAlerts](http://www.wmata.com/rider_tools/metro_service_status/rail_bus.cfm?) to GTFS-realtime TripUpdates, VehiclePositions, and Alerts feeds.
*   [SEPTA API to GTFS-realtime (⭐2)](https://github.com/kurtraschke/septa-gtfsrealtime) - Java-based tool to convert [SEPTA's](http://www.septa.org/) [real-time bus and rail data](http://www3.septa.org/hackathon/) to GTFS-realtime
*   [CTA API to GTFS-realtime (⭐4)](https://github.com/kurtraschke/ctatt-gtfsrealtime) - Java-based tool to convert [CTA's](http://www.transitchicago.com/) [Train Tracker data](http://www.transitchicago.com/developers/traintracker.aspx) to GTFS-realtime.
*   [Detroit DOT to GTFS-realtime (⭐2)](https://github.com/prashtx/ddot-avl) - Extract real-time info from [DDOT's](http://www.detroitmi.gov/How-Do-I/Locate-Transportation/Bus-Schedules) TransitMaster installation (database) and convert to GTFS-realtime
*   [Live Transit Event Trigger (⭐4)](https://github.com/ipublic/live_transit_event_trigger) - Extracts data from [Ride On's](http://www.montgomerycountymd.gov/dot-transit/) OrbCAD database and export as GTFS-realtime.
*   [SoundTransit to GTFS-realtime (⭐3)](https://github.com/bdferris/onebusaway-sound-transit-realtime) - Convert text file feed from [Sound Transit](http://www.soundtransit.org/) to GTFS-realtime
*   [Civic Transit (⭐4)](https://github.com/jestin/CivicTransit) - Screen-scrapes [KCATA’s](http://www.kcata.org/) TransitMaster WebWatch installation to produce a GTFS-realtime feed.

### GTFS Realtime Utilities / Rust

*   [GTFS-realtime Munin Plugin (⭐1)](https://github.com/OneBusAway/onebusaway-gtfs-realtime-munin-plugin) - Provides a [Munin](http://munin-monitoring.org/) plugin for logging information about a GTFS-realtime feed.

### Software for Creating APIs / Rust

*   [OneBusAway](http://onebusaway.org/) - A Java app that consumes GTFS and GTFS-Realtime (along with [other formats (⭐217)](https://github.com/OneBusAway/onebusaway-application-modules/wiki/Real-Time-Data-Configuration-Guide)) and turns them into an easy to use REST API.

## [16. Awesome Android](/content/JStumpp/awesome-android/week/README.md)

### GUI / Animations

*   [Android-View-Actions (⭐138)](https://github.com/dtx12/AndroidAnimationsActions) - Makes creating complex animations for views easy.

## [17. Awesome Microservices](/content/mfornos/awesome-microservices/week/README.md)

### REST / Scala

*   [API Blueprint](https://apiblueprint.org/) - Tools for your whole API lifecycle. Use it to discuss your API with others. Generate documentation automatically. Or a test suite. Or even some code.
*   [RAML](http://raml.org/) - RESTful API Modeling Language, a simple and succinct way of describing practically-RESTful APIs.

### World Wide Web / Scala

*   [W3C.REC-Webarch](http://www.w3.org/TR/webarch/) - Architecture of the World Wide Web, Volume One.
*   [RFC3986](https://tools.ietf.org/html/rfc3986) - Uniform Resource Identifier (URI): Generic Syntax.
*   [RFC6570](https://tools.ietf.org/html/rfc6570) - URI Template.
*   [RFC7320](https://tools.ietf.org/html/rfc7320) - URI Design and Ownership.

### HTTP/1.1 / Scala

*   [RFC7230](https://tools.ietf.org/html/rfc7230) - Message Syntax and Routing.
*   [RFC7231](https://tools.ietf.org/html/rfc7231) - Semantics and Content.
*   [RFC7232](https://tools.ietf.org/html/rfc7232) - Conditional Requests.
*   [RFC7233](https://tools.ietf.org/html/rfc7233) - Range Requests.
*   [RFC7234](https://tools.ietf.org/html/rfc7234) - Caching.
*   [RFC7235](https://tools.ietf.org/html/rfc7235) - Authentication.

### HTTP/2 / Scala

*   [RFC7540](https://tools.ietf.org/html/rfc7540) - Hypertext Transfer Protocol Version 2.

### Unicode / Scala

*   [UNIV8](http://www.unicode.org/versions/Unicode8.0.0/) - The Unicode Consortium. The Unicode Standard, Version 8.0.0, (Mountain View, CA: The Unicode Consortium, 2015. ISBN 978-1-936213-10-8).
*   [RFC3629](https://tools.ietf.org/html/rfc3629) - UTF-8, a transformation format of ISO 10646.

## [18. BEM Resources](/content/sturobson/BEM-resources/week/README.md)

### Articles

*   [BEM official naming convention](https://en.bem.info/method/naming-convention/)

## [19. Toolsforactivism](/content/drewrwilson/toolsforactivism/week/README.md)

### Open-source host-it-yourself:

*   [Twilio.org's Rapid Response Kit (⭐304)](https://github.com/Twilio-org/rapid-response-kit) - Collection phone-related tools using Twilio's service. Kit includes: Auto-Respond (inbound voice/sms responder), Broadcast (simple way to broadcast texts/calls to a list), Conference Line, Forwarder, Ringdown (call down a list of people, if 1st person doesn't answer go on to the next), Help Line (Press 1 for..., Press 2 for...)
*   [Crowdring (⭐16)](https://github.com/therules/CrowdRing) - web app where people around the world can place a free missed call to sign a petition
*   [Self Starter (⭐3.2k)](https://github.com/lockitron/selfstarter) - roll your own crowdfunding site

### Software as a service:

*   [Contact Congress (FFTF)](http://congress.fightforthefuture.org/) - Used to send emails to members of the US Congress. This is Fight for the Future's hosted-version of the open sources Contact Congress. Ideal for organizations that send a lot of emails to congress, but who don't have tech staff who can install and maintain their own version of the open source software.

### How do I contribute to this list

*   **Familiar with github?** Send a pull request with your suggestions. If you're not sure how to do that don't sweat it. See below.
*   **Not familiar with github?** You can leave a comment on this page by clicking on the `Issues` tab on the right and adding a New Issue (that's just like a comment). FYI you'll need to create a github account.

## [20. Awesome Cpp](/content/fffaraz/awesome-cpp/week/README.md)

### CLI

*   [gflags](https://gflags.github.io/gflags/) - Commandline flags module for C++. \[BSD]

### Containers

*   [LSHBOX (⭐287)](https://github.com/RSIA-LIESMARS-WHU/LSHBOX) - A c++ toolbox of locality-sensitive hashing (LSH), provides several popular LSH algorithms, also support Python and MATLAB. \[GPL]

### Physics

*   [Box2D (⭐8.6k)](https://github.com/erincatto/Box2D) - A 2D physics engine for games. \[BSD-like]

## [21. Awesome Javascript](/content/sorrycc/awesome-javascript/week/README.md)

### MVC Frameworks and Libraries / Runner

*   [react-native (⭐121k)](https://github.com/facebook/react-native) - A framework for building native apps with React.

## [22. Awesome Canvas](/content/raphamorim/awesome-canvas/week/README.md)

### Canvas / Examples

*   [30.000 particles](http://codepen.io/soulwire/full/Ffvlo) \[[show me the code](http://codepen.io/soulwire/pen/Ffvlo)] • A result of a study creating performant particles with Canvas 2D.
*   [Canvas Colour Cycling](http://www.effectgames.com/demos/canvascycle/) \[[show me the code](http://www.effectgames.com/effect/article.psp.html/joe/Old_School_Color_Cycling_with_HTML5)] • This demo is an implementation of a full 8-bit color cycling engine, rendered into an HTML5 Canvas in real-time.
*   [Canvas Loader](http://cssdeck.com/labs/full/4do6cnjm) \[[show me the code](http://cssdeck.com/labs/4do6cnjm)] • Reference to make loaders using canvas.
*   [Circular Rings](http://cssdeck.com/labs/full/zeaklousedit) \[[show me the code](http://cssdeck.com/labs/zeaklousedit)] • A great example about how to create circular rings using canvas.
*   [Cloth 3D Effect](http://gyu.que.jp/jscloth/) (Google Chrome strongly recommended) • Thid demo renders a 3d model of Apple iPod with sphere environmental mapping technique.
*   [Distance Field Waves](http://www.kevs3d.co.uk/dev/shaders/distancefield3.html) \[[show me the code (⭐207)](https://github.com/kevinroast/webglshaders/blob/master/distancefield3.html)] • A example about GPU rendering shader experiments with procedural 3D scene generation using ray marching and distance field (also known as 'sphere tracing') rendering techniques.
*   [Fibrous Texture](http://cssdeck.com/labs/full/fibrous) \[[show me the code](http://cssdeck.com/labs/fibrous)] • Simple canvas based animation; draws random lines across the field. Makes an interesting papery pattern that becomes increasingly detailed with each iteration.
*   [Image Nodes](http://cssdeck.com/labs/full/image-nodes) \[[show me the code](http://cssdeck.com/labs/image-nodes)] • Interactive nodes built from image data. Use the mouse to play.
*   [JS Metaballs](http://cssdeck.com/labs/full/js-metaballs) \[[show me the code](http://cssdeck.com/labs/js-metaballs)] • Experiment for Chrome. Mix of webkit-filter and canvas for a metaballs effect.
*   [Linjer](http://lab.hakim.se/linjer/) • Amazing experiment about nodes effects in addition with cloth and animation effect.
*   [Liquid Particles](http://spielzeugz.de/html5/liquid-particles.html) • A good example about Liquid Particles.
*   [LucidChart](http://www.lucidchart.com/documents/demo) • A complete tool to draw diagrams and other geometric forms, made in canvas.
*   [L-System Turtle Fractal Renderer](http://www.kevs3d.co.uk/dev/lsystems/) • A example about fractal renderer using canvas.
*   [Motion Graphic Typeface](http://codepen.io/ara_node/full/nuJCG/) \[[show me the code](http://codepen.io/ara_node/pen/nuJCG)] • A example about typeface animation.
*   [Neatnait Canvas Rain](http://cssdeck.com/labs/full/neatnait-canvas-rain) \[[show me the code](http://cssdeck.com/labs/neatnait-canvas-rain)] • A reference to create rain particles.
*   [Particles](http://codepen.io/pixelgrid/full/ECrKd) \[[show me the code](http://codepen.io/pixelgrid/pen/ECrKd)] • Reference to create astonishing particles.
*   [Ping Pong Game](http://cssdeck.com/labs/full/ping-pong-game-tutorial-with-html5-canvas-and-sounds) \[[show me the code](http://cssdeck.com/labs/ping-pong-game-tutorial-with-html5-canvas-and-sounds)] • Besides being a good example, it also is a tutorial about game made with canvas.
*   [Pirates Love Daisies](http://www.pirateslovedaisies.com/) • A entire game created using canvas
*   [Tree in the Breeze](http://cssdeck.com/labs/full/fjqj6ifd) \[[show me the code](http://cssdeck.com/labs/fjqj6ifd)] • Demo about generating 2D trees in canvas.
*   [Video Destruction](http://www.craftymind.com/factory/html5video/CanvasVideo.html) • Block based destruction of HTML5 video, best viewed in webkit based browsers.
*   [Wipers](http://cssdeck.com/labs/full/oluh99m6) \[[show me the code](http://cssdeck.com/labs/oluh99m6)] • Wipers receiving life with canvas.
*   [3D Lorenz Atractor](http://cssdeck.com/labs/full/3d-lorenz-atractor) \[[show me the code](http://cssdeck.com/labs/3d-lorenz-atractor)] • A simple canvas example showing a Lorenz atractor
*   [3D Movement in HTML5 Canvas](http://cssdeck.com/labs/full/xtunjekt) \[[show me the code](http://cssdeck.com/labs/xtunjekt)] • Excelent example about vector postion and movement.
*   [3D Space Craft](http://07055944295.com/solvalou.php) • A Space Craft made and rotating with canvas.
*   [Wormz](https://www.chromeexperiments.com/experiment/wormz) • Particles experiment.

### Resources / Twitter

*   [@jeresig](https://twitter.com/jeresig) - Creator of [Processing.js (⭐1.7k)](https://github.com/jeresig/processing-js)
*   [@mrdoob](https://twitter.com/mrdoob) - Creator of [three.js (⭐97k)](https://github.com/mrdoob/three.js)
*   [@soulwire](https://twitter.com/soulwire) - Creator of [sketch.js (⭐4.1k)](https://github.com/soulwire/sketch.js) and actively creating and sharing canvas/WebGL experiments
*   [@spielzeugz](https://twitter.com/spielzeugz) - Actively creating and sharing canvas experiments
*   [@paul\_irish](https://twitter.com/paul_irish) - Active contributor and write a [reference post about requestAnimationFrame](http://www.paulirish.com/2011/requestanimationframe-for-smart-animating/)

## [23. Awesome Standard](/content/standard/awesome-standard/week/README.md)

### forks

*   **[jsw](https://www.npmjs.com/package/jsw)** - "the spec doesnt care about semicolons and neither should you"
*   **[obama](https://www.npmjs.com/package/obama)** - Move forward and standardize with Obama

## [24. Amas](/content/sindresorhus/amas/week/README.md)

### Ask these organizations anything!

*   [Edenspiekermann](https://github.com/edenspiekermann/ama) - Design agency based in Berlin and around the world.

## [25. Awesome Appsec](/content/paragonie/awesome-appsec/week/README.md)

### Articles

### [Why Invest in Application Security?](https://paragonie.com/white-paper/2015-why-invest-application-security) (2015)

**Released**: June 21, 2015

Running a business requires being cost-conscious and minimizing unnecessary spending. The benefits of ensuring in the security of your application are invisible to most companies, so often times they neglect to invest in secure software development as a cost-saving measure. What these companies don't realize is the potential cost (both financial and to brand reputation) a preventable data compromise can incur.

**The average data breach costs millions of dollars in damage.**

Investing more time and personnel to develop secure software is, for most companies, worth it to minimize this unnecessary risk to their bottom line.
### [A Guide to Secure Data Encryption in PHP Applications](https://paragonie.com/white-paper/2015-secure-php-data-encryption) (2015)

**Released**: August 2, 2015

Discusses the importance of end-to-end network-layer encryption (HTTPS) as well as secure encryption for data at rest, then introduces the specific cryptography tools that developers should use for specific use cases, whether they use [libsodium](https://pecl.php.net/package/libsodium), [Defuse Security's secure PHP encryption library (⭐3.8k)](https://github.com/defuse/php-encryption), or OpenSSL.

### Books and ebooks

### [SEI CERT Android Secure Coding Standard](https://www.securecoding.cert.org/confluence/display/android/Android+Secure+Coding+Standard) (2015)

**Released**: February 24, 2015

A community-maintained Wiki detailing secure coding standards for Android development.
### [SEI CERT C Coding Standard](https://www.securecoding.cert.org/confluence/display/c/SEI+CERT+C+Coding+Standard) (2006)

**Released**: May 24, 2006

A community-maintained Wiki detailing secure coding standards for C programming.
### [SEI CERT Java Coding Standard](https://www.securecoding.cert.org/confluence/display/java/SEI+CERT+Oracle+Coding+Standard+for+Java) (2007)

**Released**: January 12, 2007

A community-maintained Wiki detailing secure coding standards for Java programming.

### Useful libraries

### [paragonie/random\_compat (⭐8.2k)](https://github.com/paragonie/random_compat)

PHP 7 offers a new set of CSPRNG functions: `random_bytes()` and `random_int()`. This is a community effort to expose the same API in PHP 5 projects (forward compatibility layer). Permissively MIT licensed.
### [psecio/gatekeeper (⭐365)](https://github.com/psecio/gatekeeper)

A secure authentication and authorization library that implements Role-Based Access Controls and Paragon Initiative Enterprises' recommendaitons for [secure "remember me" checkboxes](https://paragonie.com/blog/2015/04/secure-authentication-php-with-long-term-persistence#title.2).

## [26. Tips](/content/git-tips/tips/week/README.md)

## Before deleting untracked files/directory, do a dry run to get the list of these files/directories

```sh
git clean -n
```
## Forcefully remove untracked files

```sh
git clean -f
```
## Forcefully remove untracked directory

```sh
git clean -f -d
```
## Show all commits in the current branch yet to be merged to master

```sh
git cherry -v master
```

**Alternatives:**

```sh
git cherry -v master <branch-to-be-merged>
```

## [27. Awesome Json Datasets](/content/jdorfman/awesome-json-datasets/week/README.md)

### GitHub API

*   [Emojis](https://api.github.com/emojis)
*   [Events](https://api.github.com/events)
*   [Gists](https://api.github.com/gists)

### Reddit

*   [/r/AskReddit](https://www.reddit.com/r/AskReddit.json)
*   [/r/funny](https://www.reddit.com/r/funny.json)
*   [/r/pics](https://www.reddit.com/r/pics.json)
*   [/r/todayilearned](https://www.reddit.com/r/todayilearned.json)
*   [/r/announcements](https://www.reddit.com/r/announcements.json)
*   [/r/worldnews](https://www.reddit.com/r/worldnews.json)
*   [/r/science](https://www.reddit.com/r/science.json)
*   [/r/IAmA](https://www.reddit.com/r/IAmA.json)
*   [/r/videos](https://www.reddit.com/r/videos.json)
*   [/r/gaming](https://www.reddit.com/r/gaming.json)

### More Awesome Lists

*   [Awesome (⭐337k)](https://github.com/sindresorhus/awesome) *(The OG List)*
*   [WPO (⭐8.4k)](https://github.com/davidsonfellipe/awesome-wpo) *(Web Performance Optimization)*
*   [Shell (⭐33k)](https://github.com/alebcay/awesome-shell) *(CLI Frameworks, Toolkits and Guides)*

## [28. Awesome Ruby](/content/markets/awesome-ruby/week/README.md)

### Code Analysis and Metrics

*   [Fasterer (⭐1.8k)](https://github.com/DamirSvrtan/fasterer) - Make your Rubies go faster with this command line tool highly inspired by fast-ruby and Sferik's talk at Baruco Conf.

## [29. Awesome Electron](/content/sindresorhus/awesome-electron/week/README.md)

### Articles / Other

*   [Building a desktop application with Electron](https://medium.com/@bojzi/building-a-desktop-application-with-electron-204203eeb658)

## [30. Awesome Bigdata](/content/newTendermint/awesome-bigdata/week/README.md)

### Distributed Filesystem

*   [Seaweed-FS (⭐24k)](https://github.com/chrislusf/seaweedfs) - simple and highly scalable distributed file system.

---

- Prev: [Aug 24 - Aug 30, 2015](/content/2015/34/README.md)
- Next: [Aug 10 - Aug 16, 2015](/content/2015/32/README.md)