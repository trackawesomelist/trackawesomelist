# Track Awesome Lua Updates Weekly

A curated list of quality Lua packages and resources.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/LewisJEllis/awesome-lua/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 LewisJEllis/awesome-lua](https://github.com/LewisJEllis/awesome-lua) · ⭐ 3.2K · 🏷️ Programming Languages

[ [Daily](/content/LewisJEllis/awesome-lua/README.md) / Weekly / [Overview](/content/LewisJEllis/awesome-lua/readme/README.md) ]

## [Apr 02 - Apr 08, 2018](/content/2018/14/README.md)

### Resources / Implementations, Interpreters, and Bindings

*   [Lua](http://www.lua.org/download.html) - Lua's original ANSI C interpreter.
    *   [Lua Repo (⭐6.2k)](https://github.com/lua/lua) - The official Lua repo, as seen by the Lua team, mirrored to GitHub.
*   [Fengari](https://fengari.io/) - The Lua VM rewritten in Javascript with seamless JS and DOM interoperability.
*   [LuaBridge (⭐1.4k)](https://github.com/vinniefalco/LuaBridge) - A lightweight library for mapping data, functions, and classes back and forth between C++ and Lua.

### Resources / Build Tools and Standalone Makers

*   [Lake (⭐123)](https://github.com/stevedonovan/Lake) - A build engine written in Lua, similar to Ruby's rake.
*   [Luabuild (⭐79)](https://github.com/stevedonovan/luabuild) - Highly customizable Lua 5.2 build system.
*   [luastatic (⭐663)](https://github.com/ers35/luastatic) - Simple tool for turning Lua programs into standalone executables.
*   [omnia (⭐45)](https://github.com/tongson/omnia) - A batteries-included creator of standalone executables, built on top of luastatic.

### Resources / IDEs and Plugins

*   [BabeLua](https://archive.codeplex.com/?p=babelua) - Lua editor/debugger extension for VS2012-13 with highlighting, auto-completion, linting, and formatting capabilities.
*   [lua-mode (⭐292)](https://github.com/immerrr/lua-mode) - Emacs major mode for editing Lua.
*   [vscode-lua (⭐109)](https://github.com/trixnz/vscode-lua) - VSCode intellisense and linting.

### Resources / Utility Belts

*   [compat53](https://luarocks.org/modules/siffiejoe/compat53) - Compatibility module providing Lua-5.3-style APIs for Lua 5.2 and 5.1.
*   [RxLua (⭐467)](https://github.com/bjornbytes/RxLua) - Reactive Extensions, Observables, etc.

### Resources / Game Engines

*   [LÖVR](https://lovr.org) - 3D framework for creating virtual reality experiences, inspired by LÖVE 2D.

### Resources / Game Development

*   Corona
    *   [Coronium](https://develephant.github.io/coronium-core-docs/) - Simple cloud platform supporting analytics, data objects, user management, and more.

### Resources / Logging

*   [lua-log (⭐96)](https://github.com/moteus/lua-log) - Asynchronous logging library with pluggable writers for file system, network, ZeroMQ, and more.
*   [LuaLogging (⭐145)](https://github.com/Neopallium/lualogging) - Log4j-inspired logging library supporting various appenders.
*   [luasyslog](https://luarocks.org/modules/luarocks/luasyslog) - Log to syslog, based on LuaLogging.

### Resources / OpenResty

*   Frameworks & tools
    *   [Lapis](http://leafo.net/lapis/) - Full-stack framework for Lua and OpenResty. Like the Django or Rails of Lua. Supports Moonscript.
    *   [ledge (⭐436)](https://github.com/pintsized/ledge) - Lua module providing scriptable, RFC-compliant HTTP cache functionality.
    *   [Sailor (⭐881)](https://github.com/sailorproject/sailor) — An MVC web framework compatible with OpenResty, Apache and other webservers.
    *   [Kong (⭐33k)](https://github.com/Kong/kong) - Microservice & API Management Layer.

### Resources / Concurrency and Multithreading

*   Coroutine-based multitasking:
    *   [Lumen (⭐139)](https://github.com/xopxe/Lumen) - Simple concurrent task scheduling.
    *   [ConcurrentLua (⭐158)](https://github.com/lefcha/concurrentlua) - Implements an Erlang-style message-passing concurrency model.
    *   [cqueues](http://25thandclement.com/\~william/projects/cqueues.html) - Library for managing sockets, signals, and threads based on an event loop with coroutines.

### Resources / File system and OS

*   [LuaFileSystem](http://keplerproject.github.io/luafilesystem/) - Extends and complements Lua's built-in set of file system functions.
*   [lunix](http://25thandclement.com/\~william/projects/lunix.html) - Bindings to common Unix system APIs, striving for thread-safety.
*   [lua-path (⭐58)](https://github.com/moteus/lua-path) - File system path manipulation library.

### Resources / Time and Date

*   [luatx (⭐106)](https://github.com/daurnimator/luatz) - Time, date, and timezone library.

### Resources / Parsing and Serialization

*   JSON
    *   [lua-cjson (⭐821)](https://github.com/mpx/lua-cjson/) - Blazing fast JSON encoding/decoding implemented in C and exposed to Lua.
    *   [luajson (⭐240)](https://github.com/harningt/luajson) - JSON encoder/decoder implemented in Lua on top of LPeg.
    *   [dkjson](http://dkolf.de/src/dkjson-lua.fsl/home) - JSON encoder/decoder implemented in pure Lua.
    *   [json.lua (⭐1.4k)](https://github.com/rxi/json.lua) - A fast and tiny JSON library in pure Lua.
*   MessagePack
    *   [lua-MessagePack](https://github.com/fperrad/lua-MessagePack) - Pure Lua implementation of MessagePack.
    *   [lua-cmsgpack (⭐330)](https://github.com/antirez/lua-cmsgpack) - A MessagePack C implementation with Lua bindings, as used by Redis.=
*   LPeg
    *   [LPeg](http://www.inf.puc-rio.br/\~roberto/lpeg/) - A pattern-matching library for Lua, based on Parsing Expression Grammars.
    *   [lpeg\_patterns (⭐111)](https://github.com/daurnimator/lpeg_patterns) - A collection of LPeg patterns.
    *   [LuLPeg (⭐226)](https://github.com/pygy/LuLPeg) - A pure Lua implementation of LPeg v0.12.
    *   [LPegLJ (⭐104)](https://github.com/sacek/LPegLJ) - A pure LuaJIT implementation of LPeg v1.0.
    *   [LPegLabel (⭐115)](https://github.com/sqmedeiros/lpeglabel) - An extension of LPeg adding support for labeled failures.
*   [LXSH (⭐71)](https://github.com/xolox/lua-lxsh) - A collection of lexers and syntax highlighters written with LPeg.
*   [lua-pb (⭐278)](https://github.com/Neopallium/lua-pb) - Protocol Buffers implementation.

### Resources / Humanize

*   [say (⭐29)](https://github.com/Olivine-Labs/say) - Simple string key-value store for i18n.

### Resources / Cryptography

*   [luaossl (⭐123)](https://github.com/wahern/luaossl) - "Most comprehensive OpenSSL module in the Lua universe" - used by lapis, kong, and lua-http.

### Resources / Network

*   [lua-cURLv3 (⭐243)](https://github.com/Lua-cURL/Lua-cURLv3) - Lua binding to libcurl.
*   [lua-http (⭐669)](https://github.com/daurnimator/lua-http) - Asynchronous HTTP and WebSocket library with client and server APIs, TLS, and HTTP/2; based on cqueues.

### Resources / Data Stores

*   [pgmoon (⭐322)](https://github.com/leafo/pgmoon) - Lua PostgreSQL driver for OpenResty, LuaSocket, and cqueues.
*   Redis
    *   [redis-lua (⭐704)](https://github.com/nrk/redis-lua) - Pure Lua client library for Redis.
    *   [lua-resty-redis (⭐1.8k)](https://github.com/openresty/lua-resty-redis) - Lua Redis client driver for OpenResty.
    *   [lredis (⭐43)](https://github.com/daurnimator/lredis) - Asynchronous Redis client with pipelining and Pub/Sub support; based on cqueues.

### Resources / Message Brokers

*   [lua-zmq (⭐149)](https://github.com/Neopallium/lua-zmq) - Lua bindings to ZeroMQ.
*   [lzmq (⭐128)](https://github.com/zeromq/lzmq) - A newer Lua binding to ZeroMQ.
*   [lua-resty-kafka (⭐738)](https://github.com/doujiang24/lua-resty-kafka) - Kafka client driver based on OpenResty cosockets.
*   [lua-resty-rabbitmqstomp (⭐186)](https://github.com/wingify/lua-resty-rabbitmqstomp) - RabbitMQ client library based on OpenResty cosockets.

### Resources / Analysis Tools and ASTs

*   [luacov](http://keplerproject.github.io/luacov/) - Simple coverage analyzer, used by busted and telescope for checking test coverage.
    *   [luacov-coveralls (⭐45)](https://github.com/moteus/luacov-coveralls) - LuaCov reporter for coveralls.io.
*   [lua-parser (⭐163)](https://github.com/andremm/lua-parser) - A Lua 5.3 parser written using LPegLabel, with improved error messages.

### Resources / Community

*   [lua-l](http://www.lua.org/lua-l.html) - The official Lua mailing list, and one of the focal points of the Lua community.
*   [Lua.Space](http://lua.space/) - The Lua community blog.
*   [Lua Users Foundation](https://github.com/lua-users-foundation) - An association of individuals with the mission of supporting and promoting Lua and its community and ecosystems.
*   [lua-users.org](http://lua-users.org/) - A site for and by users of Lua, featuring an IRC channel, a web archive of lua-l, and a large wiki.
*   Conferences/Meetups
    *   [Lua Workshop](https://www.lua.org/community.html#workshop) - Annual 2-day meeting of the Lua community, in rotating locations.
    *   [Lua Conf](http://luaconf.com/) - Annual 1-day Lua conference in Brazil.
    *   [FOSDEM](https://fosdem.org/) - Annual 2-day gathering of F/OSS developers in Brussels which sometimes has a "Lua devroom".

## [Jul 24 - Jul 30, 2017](/content/2017/30/README.md)

### Resources / Implementations, Interpreters, and Bindings

*   [lua.vm.js (⭐829)](https://github.com/daurnimator/lua.vm.js) - Lua VM on the web; a direct port of the C interpreter via LLVM, emscripten, and asm.js.

### Resources / Package Managers

*   [LuaRocks](https://luarocks.org/) - De-facto tool for installing Lua modules as packages called "rocks", plus public rock repository and website.  Much like npm or pip.

### Resources / IDEs and Plugins

*   [Lua Development Tools](https://eclipse.org/ldt/) - Eclipse plugin which provides code completion, debugging, and more. Built on Metalua.
*   [ZeroBraneStudio](https://studio.zerobrane.com/) - Lightweight, customizable, cross-platform Lua-dedicated IDE with code completion and analysis, written in Lua. Has broad debugging support for numerous Lua engines.

### Resources / Utility Belts

*   [Lua Fun (⭐1.8k)](https://github.com/luafun/luafun) - High-performance functional programming library designed for LuaJIT.

### Resources / Game Engines

*   [Corona SDK](https://coronalabs.com/) - Development platform for iOS and Android. Proprietary, but used by numerous top games and apps, totaling over 150 million downloads.

### Resources / Other Lists

*   [awesome-love2d (⭐2.5k)](https://github.com/love2d-community/awesome-love2d) - A list like this one, but focused on game dev and the LÖVE platform.

### Resources / Game Development

*   MOAI
    *   [moaifiddle](https://moaifiddle.com) - Edit and share short scripts for the MOAI game engine and run them in the browser using WebGL.

### Resources / Web/Networking Platforms

*   [OpenResty](http://openresty.org/en/) - A fast and scalable web application platform created by extending Nginx with Lua. Today's de-facto Lua web platform, used heavily by Cloudflare, Taobao, Tencent, and others.
*   [turbo](https://turbo.readthedocs.io/en/latest/) - Event-driven, non-blocking, LuaJIT-based networking suite and framework, inspired by Tornado.
*   [Kepler Project](https://github.com/keplerproject) - A collection of web-oriented projects using a common set of standards and components.
*   [Pegasus.lua (⭐309)](https://github.com/EvandroLG/pegasus.lua) - Pegasus.lua is a http server to work with web applications written in Lua language.

### Resources / Documentation

*   [Locco](http://rgieseke.github.io/locco/) - Lua port of [Docco](http://ashkenas.com/docco/), the "quick-and-dirty, hundred-line-long, literate-programming-style documentation generator".

### Resources / Digital Signal Processing

*   [LuaFFT (⭐37)](https://github.com/h4rm/luafft) - An easy to use Fast Fourier Transformation package in pure Lua.

### Resources / Math and Scientific Computing

*   [lhf's Lua Tools](http://webserver2.tecgraf.puc-rio.br/\~lhf/ftp/lua/) - Assorted libraries and tools, many math- or data-related.

### Resources / Data Stores

*   [LuaSQL](http://keplerproject.github.io/luasql/) - Simple interface for connecting to ODBC, ADO, Oracle, MySQL, SQLite and PostgreSQL.

### Resources / Scriptable by Lua

*   [AwesomeWM](https://awesomewm.org/) - A highly configurable and extensible window manager for X, scripted and configured by Lua.
*   [Textadept](https://foicica.com/textadept/) - Extremely lightweight, customizable, cross-platform editor, written (mostly) in (and scripted by) Lua.

### Resources / Articles

*   [Embedding Lua in C](https://debian-administration.org/article/264/Embedding_a_scripting_language_inside_your_C/C_code) - An introductory walkthrough of embedding Lua in a C program. A bit dated, but still a great walkthrough.

### Resources / Books

*   [Lua Quick Reference](https://foicica.com/lua/) - A quick reference on how to program in and embed Lua 5.1 through 5.3, by the creator of Textadept.

## [May 08 - May 14, 2017](/content/2017/19/README.md)

### Resources / Glossaries

*   [Lua 5.3 Glossary](https://rawgit.com/dlaurie/lua-notes/master/glossary.html) - A glossary of some essential Lua terms.

## [Jan 30 - Feb 05, 2017](/content/2017/5/README.md)

### Resources / Scriptable by Lua

*   [luakit](https://luakit.github.io/luakit/) - Fast, small, webkit based browser framework extensible by Lua.

## [Dec 12 - Dec 18, 2016](/content/2016/50/README.md)

### Resources / Cryptography

*   [luatweetnacl (⭐13)](https://github.com/philanc/luatweetnacl) - Bindings to tweetnacl, modern high-security cryptographic library.

## [Feb 08 - Feb 14, 2016](/content/2016/6/README.md)

### Resources / Game Engines

*   [Drystal](https://drystal.github.io/) - Open source, games can run on Linux or on any platform with a recent web browser.
*   [Amulet](http://www.amulet.xyz/) - Open source, audio/visual toolkit suitable for small games and experimentation. It runs on Windows, Mac, Linux, HTML5 and iOS.

## [Jan 18 - Jan 24, 2016](/content/2016/3/README.md)

### Resources / Implementations, Interpreters, and Bindings

*   [LLVM-Lua (⭐121)](https://github.com/neopallium/llvm-lua) - Compiles Lua to LLVM.

### Resources / Game Development

*   Examples
    *   [termtris (⭐432)](https://github.com/tylerneylon/termtris) - A tetris clone, written in literate style with "an emphasis on learn-from-ability".
    *   [PacPac (⭐334)](https://github.com/tylerneylon/pacpac) - A Pac-man clone, made with LÖVE.
    *   [Mari0 (⭐513)](https://github.com/Stabyourself/mari0) - Fusion of Mario and Portal, made with LÖVE. See also its [wikipedia entry](https://en.wikipedia.org/wiki/Mari0).
    *   [Journey to the Center of Hawkthorne (⭐1k)](https://github.com/hawkthorne/hawkthorne-journey) - 2D platformer based on Community's [Digital Estate Planning](https://en.wikipedia.org/wiki/Digital_Estate_Planning) episode, made with LÖVE.

### Resources / Documentation

*   [docroc (⭐11)](https://github.com/bjornbytes/docroc) - Parse comments into a Lua table to generate documentation.

### Resources / Math and Scientific Computing

*   [SciLua](http://scilua.org/) - Numerical/scientific computing framework built on LuaJIT, with an interface to R.

### Resources / Testing

*   [lust (⭐78)](https://github.com/bjornbytes/lust) - Minimal test framework.

### Resources / Experimental, etc

*   [graphql-lua (⭐171)](https://github.com/bjornbytes/graphql-lua) - Lua implementation of [GraphQL](http://graphql.org/).

### Resources / Scriptable by Lua

*   [Hammerspoon](http://www.hammerspoon.org) - A powerful, extensible OS X automation tool. A community-maintained fork of [Mjolnir](http://www.mjolnir.io/).
*   [lumail](https://lumail.org/) - A console-based mail client, with extensive scripting capabilities.

### Resources / Books

*   [Lua Programming](https://en.wikibooks.org/wiki/Lua_Programming) - A shorter overview of the language, up to date for Lua 5.2, and available online.

## [Oct 05 - Oct 11, 2015](/content/2015/40/README.md)

### Resources / Other Lists

*   [awesome-resty (⭐2.2k)](https://github.com/bungle/awesome-resty) - A list like this one, but focused on OpenResty.

## [Apr 13 - Apr 19, 2015](/content/2015/15/README.md)

### Resources / Scriptable by Lua

*   [KoReader (⭐12k)](https://github.com/koreader/koreader) - An ebook reader application supports PDF, DJVU, EPUB, FB2 and much more, running on Kindle, Kobo, PocketBook and Android devices.

## [Mar 16 - Mar 22, 2015](/content/2015/11/README.md)

### Resources / Implementations, Interpreters, and Bindings

*   [MoonSharp (⭐1.2k)](https://github.com/xanathar/moonsharp) - A Lua interpreter written entirely in C# for the .NET, Mono and Unity platforms.

### Resources / Analysis Tools and ASTs

*   [luadec51 (⭐288)](https://github.com/sztupy/luadec51) - Lua Decompiler for Lua version 5.1.

## [Mar 02 - Mar 08, 2015](/content/2015/9/README.md)

### Resources / Implementations, Interpreters, and Bindings

*   [GopherLua (⭐5.1k)](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler implemented in Go with Go APIs.

## [Feb 09 - Feb 15, 2015](/content/2015/6/README.md)

### Resources / References

*   [Reference Manual](http://www.lua.org/manual/5.3/) - The official definition of the Lua language.

## [Jan 26 - Feb 01, 2015](/content/2015/4/README.md)

### Resources / Command-line Utilities

*   [argparse (⭐205)](https://github.com/mpeterv/argparse) - A feature-rich command line parser inspired by argparse for Python.

### Resources / Cryptography

*   [LuaCrypto (⭐86)](https://github.com/mkottman/luacrypto) - Lua bindings to OpenSSL.
*   [lua-lockbox (⭐325)](https://github.com/somesocks/lua-lockbox) - A collection of cryptographic primitives written in pure Lua.

## [Jan 19 - Jan 25, 2015](/content/2015/3/README.md)

### Resources / Hardware and Embedded Systems

*   [eLua](http://www.eluaproject.net/) - Lua, extended with optimizations and specific features for efficient and portable embedded software development.

## [Jan 12 - Jan 18, 2015](/content/2015/2/README.md)

### Resources / Implementations, Interpreters, and Bindings

*   [lupa (⭐841)](https://github.com/scoder/lupa) - Python bindings to LuaJIT2.
*   [golua (⭐598)](https://github.com/aarzilli/golua) - Golang bindings to the Lua C API.

## [Jan 05 - Jan 11, 2015](/content/2015/1/README.md)

### Resources / Parsing and Serialization

*   [lyaml (⭐163)](https://github.com/gvvaughan/lyaml) - YAML encoding/decoding via binding to LibYAML.

### Resources / Network

*   [lua-websockets (⭐365)](https://github.com/lipp/lua-websockets) - WebSocket client and server modules. Webserver-agnostic, implemented in Lua on top of LuaSocket.

## [Dec 15 - Dec 21, 2014](/content/2014/50/README.md)

### Resources / OpenResty

*   Third-party modules
    *   [lua-resty-http (⭐1.8k)](https://github.com/pintsized/lua-resty-http) - Lua HTTP client driver, built on the cosocket API.

### Resources / Analysis Tools and ASTs

*   [Typed Lua (⭐528)](https://github.com/andremm/typedlua) - A typed superset of Lua that compiles to plain Lua.

### Resources / Other Lists

*   [Where Lua is Used](https://sites.google.com/site/marbux/home/where-lua-is-used) - A comprehensive list of stand-alone programs written in or extensible using Lua.

## [Sep 01 - Sep 07, 2014](/content/2014/35/README.md)

### Resources / Implementations, Interpreters, and Bindings

*   [UniLua (⭐1.1k)](https://github.com/xebecnan/UniLua) - A pure C# implementation of Lua 5.2, focused on compatibility with the Unity game engine.

## [Aug 25 - Aug 31, 2014](/content/2014/34/README.md)

### Resources / Debugging and Profiling

*   [lovebird (⭐257)](https://github.com/rxi/lovebird) - Browser-based debug console. Originally made for LÖVE, but works in any project with LuaSocket support.

### Resources / Game Engines

*   [MOAI](http://getmoai.com/) - Open source, cross-platform, mobile game development framework. Minimalist C++ engine powered by Lua scripting.

### Resources / Game Development

*   Tweening
    *   [flux (⭐301)](https://github.com/rxi/flux) - A fast, lightweight tweening library for Lua with easing functions and the ability to group tweens together.
    *   [tween.lua (⭐485)](https://github.com/kikito/tween.lua) - Small library for tweening, with several easing functions.

### Resources / Digital Signal Processing

*   [Worp](http://worp.zevv.nl/about.html) - Sound/music/DSP engine written for LuaJIT.

### Resources / Network

*   [LuaSocket (⭐1.5k)](https://github.com/diegonehab/luasocket) - Networking extension which provides a socket API for TCP and UDP, and implements HTTP, FTP, and SMTP.

### Resources / Data Stores

*   [lua-resty-cassandra (⭐67)](https://github.com/jbochi/lua-resty-cassandra) - Lua Cassandra client driver for OpenResty and others.

### Resources / References

*   [Lua Unofficial FAQ](http://www.luafaq.org/) - Answers all sorts of Lua-related questions, including many of the form 'How to \_\_\_?'.

### Resources / Articles

*   [Lua states, libraries, coroutines and memory](http://www.thijsschreijer.nl/blog/?p=693) - Diagrams and explains some more advanced concepts of the Lua VM, particularly when interfacing with C.

## [Aug 18 - Aug 24, 2014](/content/2014/33/README.md)

### Resources / Implementations, Interpreters, and Bindings

*   [LuaJIT](http://luajit.org/luajit.html) - High-performance Just-In-Time compiler for Lua.
*   [Moonshine (⭐493)](https://github.com/gamesys/moonshine) - A Lua VM implemented in JavaScript. Slower than lua.vm.js, but with better docs, examples, and JS interfacing.

### Resources / Debugging and Profiling

*   [ProFi](https://gist.github.com/perky/2838755) - Simple profiler that works with LuaJIT and produces a report file.
*   [luatrace (⭐157)](https://github.com/geoffleyland/luatrace) - Toolset for tracing/analyzing/profiling script execution and generating detailed reports.
*   [StackTracePlus (⭐180)](https://github.com/ignacio/StackTracePlus) - Drop-in upgrade to Lua's stack traces which adds local context and improves readability.
*   [MobDebug (⭐778)](https://github.com/pkulchenko/MobDebug) - Powerful remote debugger with breakpoints and stack inspection. Used by ZeroBraneStudio.

### Resources / IDEs and Plugins

*   [Lua for IDEA](https://bitbucket.org/sylvanaar2/lua-for-idea/wiki/Home) - IntelliJ IDEA plugin which, among other things, provides code completion, smart highlighting, and experimental debugging.

### Resources / Utility Belts

*   [Moses (⭐590)](https://github.com/Yonaba/Moses) - Functional programming utility belt, inspired by Underscore.js.
*   [Penlight (⭐1.6k)](https://github.com/stevedonovan/Penlight) - Broad, heavyweight utility library, inspired by Python's standard libs. Provides the batteries that Lua doesn't.
*   [lua-stdlib (⭐259)](https://github.com/lua-stdlib/lua-stdlib) - Middle-weight standard library extension; adds some useful data structures, utility functions, and basic functional stuff.
*   [Microlight (⭐156)](https://github.com/stevedonovan/Microlight) - A little library of useful Lua functions; the 'extra light' version of Penlight.

### Resources / Game Engines

*   [LÖVE 2D](http://love2d.org/) - Desktop game development platform. Cross-platform, feature-complete, well-adopted.

### Resources / Game Development

*   [Jumper (⭐575)](https://github.com/Yonaba/Jumper) - Fast, lightweight, and easy-to-use pathfinding library for grid-based games.
*   [lume (⭐761)](https://github.com/rxi/lume/) - Utility belt library geared toward game development.
*   [NoobHub (⭐273)](https://github.com/Overtorment/NoobHub) - Network multiplayer for Corona, LÖVE, and more, following a simple pub-sub model.
*   Collision detection
    *   [bump.lua (⭐769)](https://github.com/kikito/bump.lua) - Minimal rectangle-based collision detection which handles tunnelling and basic collision resolution.
    *   [HardonCollider](http://vrld.github.io/HardonCollider/) - Detect collisions between arbitrarily positioned and rotated shapes of any type.

### Resources / OpenResty

*   Core platform
    *   [ngx\_lua](https://www.nginx.com/resources/wiki/modules/lua/) - The core piece of OpenResty. Embeds Lua in Nginx and exposes, among other things, the cosocket API for non-blocking sockets (compatible with LuaSocket's API).
    *   [OpenResty GitHub Organization](https://github.com/openresty) - Home of the repositories for ngx\_lua, ngx\_openresty, and many related modules.

### Resources / Command-line Utilities

*   [ansicolors (⭐107)](https://github.com/kikito/ansicolors.lua) - Simple function for printing to the console in color.
*   [cliargs (⭐96)](https://github.com/amireh/lua_cliargs) - A simple command-line argument parsing module.
*   [lua-term (⭐114)](https://github.com/hoelzro/lua-term) - Terminal operations and manipulations.

### Resources / Concurrency and Multithreading

*   Multithreading:
    *   [llthreads (⭐141)](https://github.com/Neopallium/lua-llthreads) - A simple wrapper for low-level pthreads & WIN32 threads.
    *   [llthreads2 (⭐69)](https://github.com/moteus/lua-llthreads2) - Newer rewrite of llthreads.
    *   [lanes (⭐381)](https://github.com/LuaLanes/lanes) - Library implementing a message passing model with one OS thread per Lua thread.
    *   [luaproc (⭐105)](https://github.com/askyrme/luaproc) - Message-passing model which allows multiple threads per OS thread and easily generalizes across a network. See also [the paper](http://www.inf.puc-rio.br/\~roberto/docs/ry08-05.pdf) where it originated.

### Resources / Templating

*   [lustache](http://olivinelabs.com/lustache/) - Mustache template implementation.
*   [etlua (⭐187)](https://github.com/leafo/etlua) - Embedded Lua templates, ERB-style.
*   [lua-resty-template (⭐852)](https://github.com/bungle/lua-resty-template) - Lua-oriented template engine for OpenResty, somewhat Jinja-like.

### Resources / Documentation

*   [LDoc](http://stevedonovan.github.io/ldoc/) - Documentation generator which modernizes and extends [LuaDoc](http://keplerproject.github.io/luadoc/).

### Resources / Object-oriented Programming

*   [30log (⭐381)](https://github.com/Yonaba/30log) - Minimalist OOP library with basic classes, inheritance, and mixins in 30 lines.
*   [middleclass (⭐1.5k)](https://github.com/kikito/middleclass) - Simple but robust OOP library with inheritance, methods, metamethods, class variables and mixins.

### Resources / File system and OS

*   [luaposix (⭐441)](https://github.com/luaposix/luaposix) - Bindings for POSIX APIs, including curses.

### Resources / Time and Date

*   [LuaDate (⭐225)](https://github.com/Tieske/date) - Date and time module with parsing, formatting, addition/subtraction, localization, and ISO 8601 support.
*   [cron.lua (⭐149)](https://github.com/kikito/cron.lua) - Time-related functions for Lua, inspired by JavaScript's setTimeout and setInterval.

### Resources / Image Manipulation

*   [magick (⭐362)](https://github.com/leafo/magick) - Lua bindings to ImageMagick for LuaJIT using FFI.

### Resources / Math and Scientific Computing

*   [Torch7](http://torch.ch/) - Scientific computing framework with wide support for machine learning algorithms, used by Facebook, Google, and more.

### Resources / Parsing and Serialization

*   XML
    *   [LuaExpat](https://matthewwild.co.uk/projects/luaexpat/) - SAX XML parser via binding to the Expat library.
    *   [SLAXML (⭐141)](https://github.com/Phrogz/SLAXML) - Pure Lua SAX-like streaming XML parser.
*   [lunamark (⭐166)](https://github.com/jgm/lunamark) - Converts Markdown to other textual formats including HTML and LaTeX. Uses LPeg for fast parsing.

### Resources / Humanize

*   [i18n.lua (⭐218)](https://github.com/kikito/i18n.lua) - Internationalization library with locales, formatting, and pluralization.
*   [inspect.lua (⭐1.1k)](https://github.com/kikito/inspect.lua) - Human-readable representation of Lua tables.
*   [serpent (⭐464)](https://github.com/pkulchenko/serpent) - Serializer and pretty printer.
*   [Ser (⭐72)](https://github.com/gvx/Ser) - Dead simple serializer with good performance.

### Resources / Compression

*   [lua-zlib (⭐246)](https://github.com/brimworks/lua-zlib) - Simple streaming interface to zlib for gzip/gunzip.
*   [lua-zip (⭐69)](https://github.com/brimworks/lua-zip) - Lua binding to libzip. Reads and writes zip files.

### Resources / Data Stores

*   [lua-resty-mysql (⭐666)](https://github.com/openresty/lua-resty-mysql) - Lua MySQL driver for OpenResty.

### Resources / Testing

*   [busted](http://olivinelabs.com/busted/) - BDD-style unit testing framework with great docs and Moonscript support.
*   [telescope (⭐153)](https://github.com/norman/telescope) - Flexible and highly customizable testing library.
*   [luassert (⭐137)](https://github.com/Olivine-Labs/luassert) - Assertion library extending Lua's built-in assertions.

### Resources / Foreign Function Interfaces

*   [LuaJIT FFI](http://luajit.org/ext_ffi.html) - LuaJIT's mechanism for calling external C functions and using C data structures from pure Lua code.
*   [luaffi (⭐441)](https://github.com/jmckaskill/luaffi) - Standalone FFI library, compatible with the LuaJIT FFI interface.

### Resources / Analysis Tools and ASTs

*   [luacheck (⭐1.7k)](https://github.com/mpeterv/luacheck) - Simple static analyzer which detects accidental globals and undefined or shadowed locals.
*   [Metalua (⭐324)](https://github.com/fab13n/metalua) - Pure Lua parser and compiler, used for generating ASTs. A number of other tools make use of the Metalua parser in this way.
*   [LuaInspect (⭐160)](https://github.com/davidm/lua-inspect) - Lua's most powerful code analysis and linting tool, built on Metalua. Used by ZeroBraneStudio, among others.
*   [LuaMinify (⭐231)](https://github.com/stravant/LuaMinify) - Minifier which also brings its own static analysis tools, lexer, and parser.

### Resources / Experimental, etc

*   [punchdrunk.js (⭐79)](https://github.com/TannerRogalsky/punchdrunk) - Moonshine + LÖVE API reimplementation = run LÖVE games in the browser.
*   [luvit (⭐3.6k)](https://github.com/luvit/luvit) - Node.js's underlying architecture (libUV) with Lua on top instead of JavaScript.

### Resources / Scriptable by Lua

*   [kpie (⭐76)](https://github.com/skx/kpie) - A scripting utility to juggle windows.

### Resources / Miscellaneous

*   [MoonScript](http://moonscript.org/) - Moonscript is a dynamic scripting language that compiles to Lua. It reduces verbosity and provides a rich set of features like comprehensions and classes. Its author calls it 'CoffeeScript for Lua'.
*   [sitegen](http://leafo.net/sitegen/) - A static site generator which uses MoonScript and supports HTML and Markdown, page grouping, and plugins.

### Resources / References

*   [lua-users wiki](http://lua-users.org/wiki/) - A large community-maintained collection of Lua information and resources, supplementing the official website.

### Resources / Style Guides

*   [Lua-users style guide](http://lua-users.org/wiki/LuaStyleGuide) - A general, high-level style guide; unopinionated, easily agreed on.
*   [Olivine style guide (⭐445)](https://github.com/Olivine-Labs/lua-style-guide) - A more opinionated and specific, and therefore more rigorous, guide.

### Resources / Tutorials

*   [Lua Crash Course](http://www.coppeliarobotics.com/helpFiles/en/luaCrashCourse.htm) - Short crash course readover, or reference for when you forget the basics.
*   [Learn Lua in 15 Minutes](http://tylerneylon.com/a/learn-lua/) - A well-commented example file which covers the basics.
*   [Learning Lua from JS](http://phrogz.net/lua/LearningLua_FromJS.html) - An overview of the similarities and differences between Lua and JS; a great start for JavaScript folks looking to pick up Lua.
*   [lua-users tutorial](http://lua-users.org/wiki/LuaTutorial) - In-depth collection of tutorials aimed at newcomers.
*   [Lua Missions (⭐318)](https://github.com/kikito/lua_missions) - A series of 'Missions' to work through which are designed to teach aspects of Lua along the way.
*   [Creating an Image Server](http://leafo.net/posts/creating_an_image_server.html) - Walks through setting up and using OpenResty to build a simple image processing server; a great starting point for playing with OpenResty.

### Resources / Articles

*   [Lua: Good, bad, and ugly parts](http://notebook.kulchenko.com/programming/lua-good-different-bad-and-ugly-parts) - A thorough summary of the good, different, bad, and ugly aspects of Lua, including many subtle quirks, by the author of ZeroBraneStudio.

### Resources / Talks & Slides

*   [Roberto's Talks](http://www.inf.puc-rio.br/\~roberto/talks/index.html) - History of talks given by Lua's chief architect, with slides for each.
*   [Lua Workshop Talks](http://www.lua.org/wshop14.html#abstracts) - High-quality talks are given at each \~annual Lua Workshop, and a history of them is online, slides included.

### Resources / Books

*   [Programming in Lua](http://www.lua.org/pil/) - The authoritative intro to all aspects of Lua programming, written by Lua's chief architect. Three editions released; first edition available online.
*   [Programming Gems](http://www.lua.org/gems/) - A collection of articles covering existing wisdom and practices on programming well in Lua, in a broad variety of use cases.