# Awesome Dtrace Overview

A curated list of awesome DTrace books, articles, videos, tools and resources.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/xen0l/awesome-dtrace/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 xen0l/awesome-dtrace](https://github.com/xen0l/awesome-dtrace) · ⭐ 141 · 🏷️ Miscellaneous

[ [Daily](/content/xen0l/awesome-dtrace/README.md) / [Weekly](/content/xen0l/awesome-dtrace/week/README.md) / Overview ]

---

# Awesome DTrace [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome DTrace books, articles, videos, tools and resources.

## Contents

*   [Learn](#learn)
*   [Articles](#articles)
*   [Videos](#videos)
*   [Software](#software)
*   [Tools](#tools)
*   [Community](#community)
*   [Contributing](#contributing)

***

## Learn

Recommended reading for learning DTrace.

### Books

*   [Dynamic Tracing Guide](http://dtrace.org/guide/preface.html) - Illumos.org DTrace guide.
*   [DTrace: Dynamic Tracing in Oracle Solaris, Mac OS X, and FreeBSD](http://www.dtracebook.com/index.php/Main_Page) - Official DTrace book.
*   [Dynamic Tracing with DTrace & SystemTap](http://myaut.github.io/dtrace-stap-book/) - A book introduces both DTrace and SystemTap.

### Other

*   [dtrace(1m) man page](https://illumos.org/man/1m/dtrace) - DTrace manual page.
*   [DTrace cheatsheet](http://www.brendangregg.com/DTrace/DTrace-cheatsheet.pdf) - DTrace cheatsheet by Brendan Gregg.
*   [DTrace one-liners](http://www.brendangregg.com/DTrace/dtrace_oneliners.txt) - DTrace one liners. Handy commands.
*   [DTrace one-liners (FreeBSD)](https://wiki.freebsd.org/DTrace/One-Liners) - DTrace one liners from FreeBSD.
*   [DTrace QuickStart](http://www.tablespace.net/quicksheet/dtrace-quickstart.html) - DTrace quick starting guide.
*   [Using DTrace stories (⭐22)](https://github.com/NanXiao/using-dtrace-stories) - A collection of using DTrace to debug system stories.
*   [Advanced DTrace Tips, Tricks and Gotchas](http://dtrace.org/resources/bmc/dtrace_tips.pdf) - A collection of advanced tips for using DTrace.

## Articles

Interesting articles about DTrace and real-world use cases.

### PID Provider

*   [pid provider: entry probe](http://dtrace.org/blogs/brendan/2011/02/09/dtrace-pid-provider/) - DTrace PID Provider.
*   [pid provider: entry arguments](http://dtrace.org/blogs/brendan/2011/02/11/dtrace-pid-provider-arguments/) - DTrace PID Provider Arguments.
*   [pid provider: return](http://dtrace.org/blogs/brendan/2011/02/14/dtrace-pid-provider-return/) - DTrace PID Provider return.
*   [pid provider: instructions](http://dtrace.org/blogs/brendan/2011/02/16/dtrace-pid-provider-instructions/) - DTrace PID Provider Instructions.
*   [pid provider: overhead](http://dtrace.org/blogs/brendan/2011/02/18/dtrace-pid-provider-overhead/) - DTrace PID Provider Overhead.
*   [pid provider exposed](http://dtrace.org/blogs/ahl/2005/03/01/pid-provider-exposed/) - PID providers internals by Adam Leventhal.
*   [When magic collides](http://dtrace.org/blogs/bmc/2011/03/09/when-magic-collides/) - PID provider bug deep dive by Bryan Cantrill.

### USDT provider

*   [Understanding DTrace ustack helpers](http://dtrace.org/blogs/dap/2013/11/20/understanding-dtrace-ustack-helpers/) - DTrace ustack helpers.
*   [USDT Providers Redux](http://dtrace.org/blogs/dap/2011/12/13/usdt-providers-redux/) - Reference for building USDT providers in custom applications.

### Sysevent provider

*   [DTrace sysevent provider](https://blogs.oracle.com/eschrock/entry/dtrace_sysevent_provider) - Solaris/illumos sysevent provider for DTrace.

### Ruby and DTrace

*   [Using DTrace to measure mutex contention in Ruby](https://vaneyckt.io/posts/using_dtrace_to_measure_mutex_contention_in_ruby/) - Mutex contention measuring in Ruby.

### Visualization methods

*   [Flamegraphs](http://www.brendangregg.com/flamegraphs.html) - A visualization of profiled software, allowing the most frequent code-paths to be identified quickly and accurately.
*   [Heat Maps](http://brendangregg.com/heatmaps.html) - Heat maps allow three dimensions of data to be visualized, similar to weather radar maps where color is used as a dimension.

## Videos

Interesting videos about DTrace.

*   [DTrace review](https://www.youtube.com/watch?v=TgmA48fILq8) - Bryan Cantrill explains how to significantly improve debugging both for development and live systems with DTrace.

### dtrace.conf

*   [dtrace.conf 2008](https://youtu.be/RvyP61WeFdM?list=PL8516982CBF9FADCC)
    *   [NFSv3 and iSCSI providers](https://www.youtube.com/watch?v=sgBCz7bXkSo\&index=4\&list=PL8516982CBF9FADCC)
    *   [DTrace for hardware](https://www.youtube.com/watch?v=1Bc2Dz8aS6s\&list=PL8516982CBF9FADCC\&index=5)
    *   [Zones & DTrace](https://www.youtube.com/watch?v=D8_onK0pSvA\&index=8\&list=PL8516982CBF9FADCC)
    *   [DTracing a Solaris build](https://www.youtube.com/watch?v=e55iXXYj-74\&index=10\&list=PL8516982CBF9FADCC)
    *   [War Stories](https://www.youtube.com/watch?v=yR39YqVXQOM\&index=11\&list=PL8516982CBF9FADCC)
    *   [Sun Benchmarks](https://www.youtube.com/watch?v=uK0DjEXo99w\&list=PL8516982CBF9FADCC\&index=12)
    *   [Erlang](https://www.youtube.com/watch?v=PXIGE5GFAkE\&index=13\&list=PL8516982CBF9FADCC)
    *   [Erlang (continued)](https://www.youtube.com/watch?v=YTNiCv9Za2Y\&index=14\&list=PL8516982CBF9FADCC)
    *   [Instrumenting Adobe AIR](https://www.youtube.com/watch?v=4astU1_X5xM\&index=15\&list=PL8516982CBF9FADCC)
    *   [HotSpot Runtime & Java](https://www.youtube.com/watch?v=8kdJDHqiByI\&list=PL8516982CBF9FADCC\&index=16)
    *   [PostgreSQL: Looking Under the Hood with Solaris](https://www.youtube.com/watch?v=p5NKcxDny_4\&list=PL8516982CBF9FADCC\&index=17)
    *   [PostgreSQL Provider](https://www.youtube.com/watch?v=SJykRURWgeU\&list=PL8516982CBF9FADCC\&index=18)
    *   [Distributed DTrace](https://www.youtube.com/watch?v=oYK1kgFwxk4\&index=19\&list=PL8516982CBF9FADCC)
    *   [Apple Port of DTrace](https://www.youtube.com/watch?v=OKSuox4eFrk\&list=PL8516982CBF9FADCC\&index=21)

*   [dtrace.conf 2012](https://www.youtube.com/watch?v=l_7v7Fn7uMQ\&list=PL973D48F273EB0360)
    *   [DTrace State of the Union](https://www.youtube.com/watch?v=l_7v7Fn7uMQ\&list=PL973D48F273EB0360)
    *   [User-Level CTF](https://www.youtube.com/watch?v=0QF04ivO_WE\&list=PL973D48F273EB0360\&index=3)
    *   [Dynamic Translators](https://www.youtube.com/watch?v=CqLcj0lVnp4\&index=4\&list=PL973D48F273EB0360)
    *   [Clang Parser for DTrace](https://www.youtube.com/watch?v=6NqV_Uj8Ba4\&index=7\&list=PL973D48F273EB0360)
    *   [Visualizations](https://www.youtube.com/watch?v=XD5hdaWnQM4\&index=8\&list=PL973D48F273EB0360)
    *   [Visualizations, Enabling Toolchain for Seamless USDT](https://www.youtube.com/watch?v=3Sqa8mmtnMM\&index=9\&list=PL973D48F273EB0360)
    *   [More Visualizations](https://www.youtube.com/watch?v=-B6u6wY3Iro\&index=10\&list=PL973D48F273EB0360)
    *   [DTrace in Node.js](https://www.youtube.com/watch?v=0ZMvSh7lUdM\&list=PL973D48F273EB0360\&index=11)
    *   [DTrace and Erlang](https://www.youtube.com/watch?v=4Si-7nAic2c\&list=PL973D48F273EB0360\&index=12)
    *   [DTrace on Linux](https://www.youtube.com/watch?v=NElog3MvUC8\&list=PL973D48F273EB0360\&index=13)
    *   [ZFS Provider](https://www.youtube.com/watch?v=m_V7yrrn49Y\&index=14\&list=PL973D48F273EB0360)
    *   [DTrace on FreeBSD](https://www.youtube.com/watch?v=s5PpSiPfSNI\&index=15\&list=PL973D48F273EB0360)
    *   [Barriers to DTrace Adoption](https://www.youtube.com/watch?v=P95LHZ-WOWw\&index=16\&list=PL973D48F273EB0360)

*   [dtrace.conf 2016](https://www.joyent.com/about/events/2016/dtrace-conf)
    *   [Introduction](https://player.vimeo.com/video/173346406)
    *   [(Useful!) DTrace intro](https://player.vimeo.com/video/173346405)
    *   [CTF Everywhere!](https://player.vimeo.com/video/173346404)
    *   [Distributed DTrace](https://player.vimeo.com/video/173346403)
    *   [DTracign Apps](https://player.vimeo.com/video/173346402)
    *   [DTrace and JSON: Together at last!](https://player.vimeo.com/video/173346401)
    *   [ASSERT() as a DTrace probe (and why I need some help)](https://player.vimeo.com/video/173346400)
    *   [Implementing (or not) fds\[\] in FreeBSD](https://player.vimeo.com/video/173346399)
    *   [OpenDTrace](https://player.vimeo.com/video/173346398)
    *   [DTrace Performance Improvements with Always-on Instrumentation](https://player.vimeo.com/video/173300658)
    *   [D language improvements](https://player.vimeo.com/video/173300657)
    *   [D Syntactic Sugar](https://player.vimeo.com/video/173300656)
    *   [DTrace and Go](https://player.vimeo.com/video/173300655)
    *   [DTrace and Postgres](https://player.vimeo.com/video/173300654)
    *   [DTrace in the Zone](https://player.vimeo.com/video/173300653)
    *   [DTrace ustack() performance improvements](https://player.vimeo.com/video/173300651)
    *   [DTrace Exploitation](https://player.vimeo.com/video/173300650)

## Software

List of software with DTrace support.

### Programming languages

#### Erlang

*   [Erlang](http://erlang.org/doc/apps/runtime_tools/DTRACE.html) - DTrace and Erlang/OTP.

#### Lua

*   [lua-usdt (⭐6)](https://github.com/chrisa/lua-usdt) - Libusdt bindings for Lua.

#### Node.js

*   [node-dtrace-provider (⭐314)](https://github.com/chrisa/node-dtrace-provider) - Native DTrace probes for Node.js apps.

#### Perl

*   [perl-Devel-DTrace-Provider (⭐2)](https://github.com/chrisa/perl-Devel-DTrace-Provider) - Perl wrapper for libusdt.

#### PHP

*   [PHP](https://secure.php.net/manual/en/features.dtrace.dtrace.php) - Using PHP and DTrace.

#### Python

*   [Python](https://www.jcea.es/artic/python_dtrace.htm) - DTrace patch for Python 2.7.x and 3.x.
*   [python-usdt (⭐7)](https://github.com/nshalman/python-usdt) - Libusdt bindings for Python.

#### Ruby

*   [Ruby](http://ruby-doc.org/core-2.3.1/doc/dtrace_probes_rdoc.html) - Ruby DTrace probes.
*   [ruby-usdt (⭐25)](https://github.com/kevinykchan/ruby-usdt) - Native DTrace probes for ruby apps.

### Databases

*   [MySQL](https://dev.mysql.com/doc/refman/5.7/en/dba-dtrace-mysqld-ref.html) - MySQL DTrace probes.
*   [PostgreSQL](https://www.postgresql.org/docs/current/static/dynamic-trace.html) - PostgreSQL DTrace probes.

### Webservers

*   [mod\_usdt (⭐18)](https://github.com/davepacheco/mod_usdt) - "httpd" DTrace provider.

### Visualization

*   [FlameGraph (⭐14k)](https://github.com/brendangregg/FlameGraph) - Stack trace visualizer.
*   [node-stackvis (⭐341)](https://github.com/joyent/node-stackvis) - Stack trace visualizer.

## Tools

*   [DTraceToolkit](http://www.brendangregg.com/dtracetoolkit.html) - A collection of useful documented DTrace scripts.
*   [dtrace-cloud-tools (⭐197)](https://github.com/brendangregg/dtrace-cloud-tools) - DTrace tools written for the SmartOS/SmartDataCenter cloud (illumos-based).
*   [pgsql tools (⭐129)](https://github.com/joyent/pgsqlstat) - Report top-level PostgreSQL stats.
*   [portsnoop (⭐3)](https://github.com/davepacheco/portsnoop) - Trace event port activity.
*   [storage tools (⭐31)](https://github.com/richardelling/tools) - Report NFS, CIFS and iSCSI stats.

## Community

*   [Community site](http://dtrace.org) - DTrace community site.
*   [Mailing list](http://dtrace.org/blogs/mailing-list/) - DTrace community mailing list.
*   [FreeBSD DTrace mailing list](https://lists.freebsd.org/mailman/listinfo/freebsd-dtrace) - FreeBSD DTrace community mailing list.
*   [China DTrace](http://chinadtrace.org/) - A Chinese DTrace site.

## Contributing

Contributions are more than welcome! Please see [contribution guidelines (⭐140)](https://github.com/xen0l/awesome-dtrace/blob/master/CONTRIBUTING.md) first.

