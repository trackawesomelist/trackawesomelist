# Awesome V Overview

A curated list of awesome V frameworks, libraries, software and resources.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/vlang/awesome-v/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 vlang/awesome-v](https://github.com/vlang/awesome-v) · ⭐ 2K · 🏷️ Programming Languages

[ [Daily](/content/vlang/awesome-v/README.md) / [Weekly](/content/vlang/awesome-v/week/README.md) / Overview ]

---

<!--lint disable no-dead-urls-->

<p align="center"><img src="https://github.com/vlang/awesome-v/raw/master/media/awesome-v-logo.svg" width="400"/></p>

# Awesome V [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome V frameworks, libraries, software and resources.

[V](https://vlang.io/) is a simple, fast, safe, compiled language for developing maintainable software.

## Contents

*   [Applications](#applications)
    *   [Build Systems](#build-systems)
    *   [Command-line](#command-line)
    *   [Editors](#editors)
    *   [Games](#games)
    *   [Graphics](#graphics)
    *   [Interpreters/Compilers](#interpreterscompilers)
    *   [Operating systems/Kernels](#operating-systemskernels)
    *   [Package managers](#package-managers)
    *   [Project management](#project-management)
    *   [Serialization](#serialization)
    *   [Utilities](#utilities)
    *   [Web](#web)
*   [Libraries](#libraries)
    *   [Audio](#audio)
    *   [Automation](#automation)
    *   [Command line interface (CLI) / Terminal / Shell](#command-line-interface-cli--terminal--shell)
    *   [Database clients](#database-clients)
    *   [Discord](#discord)
    *   [Eventing](#eventing)
    *   [File handling](#file-handling)
    *   [Game development](#game-development)
    *   [Graphics](#graphics-1)
    *   [Interoperability](#interoperability)
    *   [IRC](#irc)
    *   [Networking](#networking)
    *   [Operating system](#operating-system)
    *   [Scientific computing](#scientific-computing)
    *   [Serial Communications](#serial-communications)
    *   [Telecommunications](#telecommunications)
    *   [Telegram](#telegram)
    *   [Text processing](#text-processing)
    *   [User Interface toolkits](#user-interface-toolkits)
    *   [Utility](#utility)
    *   [Web](#web-1)
*   [Other](#other)
    *   [Articles](#articles)
    *   [Books](#books)
    *   [Communities](#communities)
    *   [Editor plugins](#editor-plugins)
    *   [Forums](#forums)
    *   [GitHub actions](#github-actions)
    *   [GitHub templates](#github-templates)
    *   [IDEs with V](#ides-with-v)
    *   [Online IDEs with V](#online-ides-with-v)
    *   [Operating Systems & OS Development Examples](#operating-systems--os-development-examples)
    *   [Patterns](#patterns)
    *   [Programming contests](#programming-contests)
    *   [Syntax highlighting](#syntax-highlighting)
    *   [Tutorials](#tutorials)
    *   [Videos](#videos)

## Applications

### Build Systems

*   [clockwork (⭐19)](https://github.com/emmathemartian/clockwork) - A language-agnostic build tool wrote in V.
*   [vab (⭐327)](https://github.com/vlang/vab) - The official V tool to build and package applications for Android.
*   [vab-sdl (⭐3)](https://github.com/larpon/vab-sdl) - Standalone and extra command for `vab` to build and package
    SDL2 and SDL3 based applications importing `vlang/sdl`.

### Command-line

*   [crepl (⭐32)](https://github.com/l1mey112/crepl) - Compile and execute C code on the fly as you type it.
*   [fdup (⭐7)](https://github.com/gechandesu/fdup) - Find and remove duplicate files.
*   [github-releases (⭐6)](https://github.com/Dracks/repo-download-asset) - Cli tool to keep track of applications released as GitHub Release (or assets in workflow) and download them.
*   [HN-top (⭐22)](https://github.com/BafS/hn-top) - A simple command to list most recent news from hacker-news.
*   [klonol (⭐20)](https://github.com/hungrybluedev/klonol) - CLI tool to help you "clone all" git repositories belonging to you. Works with GitHub and Gitea.
*   [lsv (⭐52)](https://github.com/mike-ward/lsv) - `ls` file lister in the spirit of exa, eza, lsd, pls, natls, ls-go and others.
*   [portctl (⭐9)](https://github.com/apoprotsky/portctl) - CLI tool to manage Docker Swarm resources using Portainer API.
*   [runner (⭐26)](https://github.com/Naheel-Azawy/runner) - A tool that automates running/compiling code written in various programming languages.
*   [symlinker (⭐8)](https://github.com/serkonda7/symlinker) - A small Linux tool to manage symlinks.
*   [vast (⭐27)](https://github.com/lydiandy/vast) - A simple tool for vlang, generate v source file to AST json file.
*   [vcli (⭐3)](https://github.com/changhz/vcli) - A CLI tool to generate folder structure according to the [guideline](https://blog.vlang.io/the-complete-beginners-guide-to-cli-apps-in-v/)
*   [verve (⭐6)](https://github.com/MohammadMD1383/verve) - Simple and fast static file server.
*   [vfetch (⭐10)](https://github.com/carlosqsilva/vfetch) - A macOS system information fetch written in V.
*   [vgoogle (⭐9)](https://github.com/changhz/vgoogle) - Make google search on the terminal.
*   [vindex (⭐5)](https://github.com/wenxuanjun/vindex) - A simple file list server generating json strings, compatible with nginx's autoindex module.
*   [vinit (⭐16)](https://github.com/pranavbaburaj/vinit) - A tool to generate v projects.
*   [vLogQL (⭐17)](https://github.com/lmangani/vLogQL) - A tiny command-line utility to query LogQL APIs.
*   [vqrcode (⭐26)](https://github.com/carlosqsilva/vqrcode) - CLI for creating QR Codes.
*   [vspect (⭐2)](https://github.com/zakuro9715/vspect) - A tool to inspect vlang source file. ( Archived )
*   [vzcc (⭐27)](https://github.com/malisipi/vzcc) - A CLI cross-compiling tool based on Zig CC for V.
*   [vin (⭐5)](https://github.com/DeoDorqnt387/vin) - A Basic Command Line Interface for V.

### Editors

*   [polygon-editor (⭐7)](https://github.com/ArtemkaKun/polygon-editor) - A tool to create and edit 2D polygons with sprite lookup, created in V.
*   [text\_editor (⭐36k)](https://github.com/vlang/v/blob/master/examples/term.ui/text_editor.v) - Small text editor from the official V examples.
*   [ved (⭐1.4k)](https://github.com/vlang/ved) - 1 MB text editor written in V with hardware accelerated text rendering. Compiles in <1s.
*   [vee (⭐49)](https://github.com/Larpon/vee) - V Editor Engine. A V module providing the guts of a text editor. Comes with a [TUI editor example (⭐49)](https://github.com/Larpon/vee/blob/master/examples/tuieditor/).
*   [vPDF (⭐85)](https://github.com/vlang/pdf) - A module to simplify PDF file creation using the V programming language.

### Games

*   [2048 (⭐4)](https://github.com/wenxuanjun/2048) - A 2048 game with several types of traditional AI integrated.
*   [Boundstone (⭐61)](https://github.com/organization/boundstone) - High Performance / Fast Compilation / Lightweight Minecraft: Bedrock Edition Server.
*   [flappylearning-v (⭐36k)](https://github.com/vlang/v/tree/master/examples/flappylearning) - A simple flappy learning demo in v.
*   [Kurarin (⭐53)](https://github.com/FireRedz/kurarin) - osu! beatmap visualizer made in V. [Example video](https://p153.p0.n0.cdn.getcloudapp.com/items/6quvQjb5/ce3ea737-eb29-4b8c-a5f3-65a804a2f56f.mp4).
*   [minesweeper (⭐39)](https://github.com/ali-furkan/minesweeper-v) - A simple Minesweeper game written in vlang.
*   [Puzzle Vibes (⭐16)](https://github.com/Larpon/puzzle_vibes) - A jigsaw-like puzzle game written in V using `shy`.
*   [v-pong (⭐13)](https://github.com/thebigsmileXD/v-pong) - A classic paddle game brought back to life through the power of V.

### Graphics

*   [mpv-v (⭐30)](https://github.com/xjunko/mpv-v) - World's Simplest Video Player.
*   [vRayTracer (⭐49)](https://github.com/ali-raheem/vraytracer) - A simple ray tracer written in V.

### Interpreters/Compilers

*   [Aixt (⭐71)](https://github.com/fermarsan/aixt) - Programming framework for microcontrollers based on a V-based language and written in V.
*   [cotowali (⭐613)](https://github.com/cotowali/cotowali) - A statically typed scripting language that transpiles into POSIX sh.
*   [monkey\_v (⭐38)](https://github.com/Delta456/monkey_v) - Implementation of [Thorsten Ball's Monkey Language](https://interpreterbook.com/) in V.
*   [stas (⭐57)](https://github.com/l1mey112/stas/tree/0.1.0-v-compiler) - A stack based compiled programming language. The bootstrap compiler is written in V.
*   [v (⭐36k)](https://github.com/vlang/v) - V itself. Simple, fast, safe, compiled language for developing maintainable software.
*   [vas (⭐98)](https://github.com/v420v/vas) - A simple x86-64 assembler written in V.
*   [vbf (⭐19)](https://github.com/vpervenditti/vbf) - A brainfuck interpreter/compiler.
*   [vfuck](https://github.com/ShayokhShorfuddin/VFuck) - A brainfuck interpreter written in V.
*   [vcc (⭐102)](https://github.com/lemoncmd/vcc) - A C compiler written in V.
*   [Vork (⭐28)](https://github.com/Itay2805/Vork) - Alternative V compiler/interpreter written in Python.

### Operating systems/Kernels

*   [Vinix (⭐2k)](https://github.com/vlang/vinix) - Small and simple OS in V. Runs bash.
*   [V-Unikernel (⭐20)](https://github.com/vlang/unikernel) - A unikernel is a computer program statically linked with the operating system code on which it depends.

### Package managers

*   [vpm (⭐125)](https://github.com/vlang/vpm) - The V language package management tool written in V.

### Project management

*   [Lenra template (⭐3)](https://github.com/lenra-io/template-v) - The Lenra template to write V app for Lenra platform.
*   [vset (⭐20)](https://github.com/mulh8377/vset) - A project setup and configuration tool for V projects.

### Serialization

*   [ini-v (⭐5)](https://github.com/ldedev/ini-v) - Simple and practical module for manipulating ini/cfg file.
*   [maple (⭐8)](https://github.com/emmathemartian/maple) - A very simple key-value config format wrote in V.
*   [v-toxml (⭐9)](https://github.com/radare/v-toxml) - XML Serialization library for V.
*   [vgura (⭐21)](https://github.com/gura-conf/vgura) - Official Gura parser for V.
*   [vlang-yaml (⭐25)](https://github.com/jdonnerstag/vlang-yaml) - A V-native YAML reader, incl. YAML-to-JSON converter.
*   [vproto (⭐55)](https://github.com/emily33901/vproto) - Protobuf compiler and runtime in V.

### Utilities

*   [emoji-mart-desktop (⭐21)](https://github.com/ttytm/emoji-mart-desktop) - An emoji picker created with V, webview and SvelteKit.
*   [v-nodejs-addon (⭐6)](https://github.com/fanlia/v-nodejs-addon) - An demo of how to create a Node.js addon with V.

### Web

*   [Gitly (⭐1.4k)](https://github.com/vlang/gitly) - A light and fast SCM alternative to GitHub/GitLab written in V.
*   [Heroku Buildpack for V (⭐2)](https://github.com/zztkm/heroku-buildpack-v) - Deploy V apps on Heroku.
*   [Mantis (⭐22)](https://github.com/khalyomede/mantis) - A web framework written in V.
*   [Tiniest Veb Server (⭐16)](https://github.com/davlgd/tVeb) - A < 1MB static hosting web server written in V, based on `veb`. 🍃
*   [v-admin-skeleton (⭐14)](https://github.com/xiusin/v-system-skeleton) - Backend skeleton written in V.
*   [v-vite starter (⭐2)](https://github.com/v-vite/starter) - A starter kit for Veb applications, preconfigured with Vite.js.
*   [vblog (⭐29)](https://github.com/scurty-labs/vblog) - A simple, fast and responsive blogging system.
*   [Vebview.JS (⭐78)](https://github.com/malisipi/Vebview.JS) - Electron/Neutralino.JS alternative written in V.
*   [Vieter (⭐11)](https://github.com/ChewingBever/vieter) - Archlinux repository server & package build system, written in V.
*   [Vlang Benchmarks Visualization (⭐9)](https://github.com/ArtemkaKun/VlangBenchmarksVisualization) - Fancy statistics and plots for *[Is V still fast?](https://fast.vlang.io/)*.
*   [vorum (⭐220)](https://github.com/vlang/vorum) - Open-source blogging/forum software written in V.
*   [vss (⭐37)](https://github.com/vssio/vss) - Easy-to-use static site generator.
*   [VTik (⭐18)](https://github.com/Sharqo78/VTik) - TikTok and Twitter video downloader app (CLI / Telegram Bot).
*   [rr-dl (⭐1)](https://github.com/dy-tea/rr-dl) - Royal-Road Novel downloader.

## Libraries

### Audio

*   [miniaudio (⭐51)](https://github.com/larpon/miniaudio) - Bindings for the excellent miniaudio C audio library.
*   [vave (⭐41)](https://github.com/thecodrr/vave) - A crazy simple library for reading/writing WAV files in V. 🌊
*   [vspeech (⭐50)](https://github.com/thecodrr/vspeech) - Complete V bindings for Mozilla's DeepSpeech TensorFlow based Speech-to-Text library. 📢📜

### Automation

*   [vrobot (⭐52)](https://github.com/eioo/vrobot) - Desktop automation for V. Only supports Windows.

### Command line interface (CLI) / Terminal / Shell

*   [bartender (⭐55)](https://github.com/tobealive/bartender) - Customizable progress indicators for V terminal applications.
*   [boxx (⭐99)](https://github.com/thecodrr/boxx) - Create highly customizable terminal boxes that also look great! 📦
*   [lol (⭐16)](https://github.com/0xLeif/lol) - V version of lolcat (text/character rainbowizer).
*   [progressbar (⭐29)](https://github.com/Waqar144/progressbar) - An easy to use V library for creating progress bars in cli.
*   [spinners (⭐21)](https://github.com/rhygg/spinners) - Create spinners in your terminal!
*   [termtable (⭐44)](https://github.com/serkonda7/termtable) - V Terminal Tables: Simple and highly customizable library to display tables in the terminal.
*   [vargs (⭐38)](https://github.com/nedpals/vargs) - V library for parsing arguments from argv-like arrays. ( Archived )
*   [vesseract (⭐17)](https://github.com/barrack-obama/vesseract) - V wrapper for Tesseract-OCR (optical character recognition).

### Database clients

*   [firebird (⭐1)](https://github.com/einar-hjortdal/firebird) - Client for Firebird SQL.
*   [mongodb (⭐50)](https://github.com/vlang/mongo) - MongoDB driver for V.
*   [redict (⭐3)](https://github.com/einar-hjortdal/redict) - Client for Redict, a LGPL-3.0-only fork of Redis (compatible with Redis <=7.2.4).
*   [redis (⭐69)](https://github.com/patrickpissurno/vredis) - Redis client for V, written in V.
*   [vduckdb (⭐36)](https://github.com/rodabt/vduckdb) - A DuckDB client wrapper for V.
*   [vmemcached (⭐11)](https://github.com/blacktrub/vmemcached) - Memcached client for V, written in V.
*   [vredis (⭐7)](https://github.com/xiusin/vredis) - A simple, user-friendly, and comprehensive Redis client.
*   [vsql (⭐46)](https://github.com/lydiandy/vsql) - A sql query builder for V.

### Discord

*   [discord.v (⭐119)](https://github.com/Terisback/discord.v) - User-friendly Discord bot library.
*   [discordwebhook (⭐1)](https://github.com/ysdragon/discordwebhook) - Super simple interface to send discord messages through webhooks.
*   [kitten (⭐14)](https://github.com/geniushq/kitten) - Simple Discord API library for writing bots.
*   [viscord (⭐22)](https://github.com/vlang/viscord) - Pretty basic library for connecting to the Discord gateway.
*   [vord (⭐5)](https://github.com/9xN/vord) - Library for interacting with user account endpoints and gateway (Self-bots, custom clients, etc).

### Eventing

*   [eventbus (⭐36k)](https://github.com/vlang/v/tree/master/vlib/eventbus) - A simple event bus system for V.

### File handling

*   [v-mime (⭐24)](https://github.com/nedpals/v-mime) - MIME detection library for V.
*   [vmon (⭐36)](https://github.com/Larpon/vmon) - Asynchronously watch for file changes in a directory. The module is essentially a V wrapper for `septag/dmon`. It works for Windows, macOS and Linux.

### Game development

*   [chipmunk2d (⭐1)](https://github.com/larpon/chipmunk2d) - V wrapper of the Chipmunk2D physics library.
*   [engine (⭐44)](https://github.com/LouisSchmieder/engine) - WIP Vulkan in V.
*   [raylib.v (⭐72)](https://github.com/irishgreencitrus/raylib.v) - Updated V bindings for [raylib](https://www.raylib.com) with plans for complete cross-platform support.
*   [shy (⭐58)](https://github.com/Larpon/shy) - A foundation that helps you being creative in V.
*   [V\_ecs (⭐17)](https://github.com/mohamedLT/V_ecs) - ECS library made in V inspired by Bevy ECS.
*   [vraylib (⭐6)](https://github.com/mohamedLT/vraylib) - A V wrapper for the awesome raylib library.
*   [vraylib (⭐49)](https://github.com/MajorHard/vraylib) - V wrapper (bindings) for raylib, the C game development framework.
*   [wren (⭐6)](https://github.com/larpon/wren) - V wrapper around the excellent Wren scripting language.

### Graphics

*   [sdl (⭐91)](https://github.com/vlang/sdl) - Official SDL2 & SDL3 bindings for V.
*   [sgldraw (⭐10)](https://github.com/larpon/sgldraw) - An experimental real-time vector render V module based on `sokol.sgl`.
*   [V Earcut (⭐14)](https://github.com/Larpon/earcut) - fast (real-time) polygon triangulation library based on [mapbox/Earcut (⭐2.3k)](https://github.com/mapbox/earcut) to handle holes, twisted polygons, degeneracies and self-intersections.
*   [V\_sokol\_gp (⭐4)](https://github.com/mohamedLT/V_sokol_gp) - A V wrapper for the sokol\_gp library for easy and fast 2d graphics.
*   [viup (⭐46)](https://github.com/kjlaw89/viup) - V wrapper for the C-based cross-platform UI library, IUP.
*   [vsdl (⭐12)](https://github.com/kjlaw89/vsdl) - V wrapper for the C-based SDL library.
*   [vsdl2 (⭐46)](https://github.com/nsauzede/vsdl2) - A libSDL2 wrapper.
*   [vsl.vcl (⭐369)](https://github.com/vlang/vsl/tree/master/vcl#readme) - VCL is a high level way of writing programs with OpenCL using V. These are highly opinionated OpenCL bindings for V. It tries to make GPU computing easy, with some sugar abstraction, V's concurrency and channels.
*   [vbmp (⭐1)](https://github.com/dy-tea/vbmp) - Read and write bitmap files.
*   [voronoi (⭐1)](https://github.com/larpon/voronoi) - V wrapper of [JCash/voronoi (⭐670)](https://github.com/JCash/voronoi).
*   [vqoi (⭐12)](https://github.com/Le0Developer/vqoi) - V: QOI - The "Quite OK Image" format for fast, lossless image compression.

### Interoperability

*   [jni (⭐24)](https://github.com/larpon/jni) - V wrapper around the C Java Native Interface (Desktop + Android).

### IRC

*   [vitric (⭐4)](https://github.com/m-242/vitric) - A transparent IRC library.

### Networking

*   [netaddr (⭐1)](https://github.com/gechandesu/netaddr) - IPv4, IPv6 and MAC (EUI-48, EUI-64) addresses manipulation library.
*   [vibe (⭐34)](https://github.com/tobealive/vibe) - Request library that wraps libcurl to enable fast and reliable requests while providing a higher-level API.
*   [vmq (⭐19)](https://github.com/jordan-bonecutter/vmq) -  V wrapper For [ZMQ](https://zeromq.org/) (aka ZeroMQ, ØMQ, 0MQ: a high-performance asynchronous messaging library).

### Operating system

*   [clipboard (⭐36k)](https://github.com/vlang/v/tree/master/vlib/clipboard) - V module for interacting with the OS clipboard. Fully cross-platform.
*   [mmap (⭐5)](https://github.com/jdonnerstag/vlang-mmap) - Provide native V-lang support for memory-mapping on Linux and Windows.
*   [vlipboard (⭐12)](https://github.com/asvvvad/vlipboard) - An easy to use wrapper of clipboard with Wayland and Termux support.
*   [winreg (⭐5)](https://github.com/ldedev/WindowsRegistry) - MS Windows Registry API. (WIP)

### Scientific computing

*   [vplot (⭐16)](https://github.com/erdetn/vplot) - V wrapper for GNU Plot (`gnuplot_i`).
*   [vsl (⭐369)](https://github.com/vlang/vsl) - VSL is a Scientific Library with a great variety of different modules. Although most modules offer pure-V definitions, VSL also provides modules that wrap known C libraries among other backends that allow high performance computing as an alternative. Also provides opinionated wrappers for OpenBLAS, LAPACKE, MPI, OpenCL among other libraries.
*   [vtl (⭐155)](https://github.com/vlang/vtl) - The V Tensor Library is a numerical computing library supporting n-dimensional data structure, backed by VSL.
*   [NeuralNetworks-V-Module (⭐28)](https://github.com/Eliyaan/NeuralNetworks-V-Module) - This is a V module to create neural networks.

### Serial Communications

*   [vi2c (⭐14)](https://github.com/erdetn/vi2c) - A tiny (wrapper) library for I2C serial communication for Linux written in V.
*   [vserialport (⭐11)](https://github.com/erdetn/vserialport) - V wrapper for [libserialport](https://sigrok.org/wiki/Libserialport).
*   [vserialx (⭐12)](https://github.com/erdetn/vserialx) - A tiny (wrapper) serial communication library for Linux written in V.

### Telecommunications

*   [vagi (⭐7)](https://github.com/Ouri028/vagi) - Asterisk FastAGI library in V.

### Telegram

*   [vgram (⭐148)](https://github.com/dariotarantini/vgram) - Telegram bot library.

### Text processing

*   [ascii\_robot (⭐13)](https://github.com/Delta456/ascii_robot) - ASCII Robot generator written in V.
*   [chalk (⭐22)](https://github.com/etienne-napoleone/chalk) - Colorize strings in the terminal.
*   [cjson (⭐12)](https://github.com/lydiandy/cjson) - Wrap cJSON for vlang.
*   [crayon (⭐58)](https://github.com/thecodrr/crayon) - Paint your terminal output like Picasso. 🖍️🎨
*   [iconv (⭐6)](https://github.com/fanlia/iconv) - Wrap iconv for vlang.
*   [pcre2 (⭐6)](https://github.com/srackham/pcre2) - Library for processing PCRE regular expressions.
*   [read\_xlsx\_v (⭐0)](https://github.com/fanlia/read_xlsx_v) - Read xlsx using vlang.
*   [Rosie-RPL (⭐6)](https://github.com/jdonnerstag/vlang-rosie) - A Rosie Pattern Language (RPL) implementation.
*   [slugify (⭐3)](https://github.com/einar-hjortdal/slugify) - Transform Unicode strings to url-friendly human-readable ASCII slugs.
*   [text-processing (⭐6)](https://github.com/ArtemkaKun/text-processing) - V text processing library, that contains common tools to manipulate text data.
*   [v-regex (⭐14)](https://github.com/spytheman/v-regex) - A simple regex library for V.
*   [vxml (⭐1)](https://github.com/i582/vxml) - Pure V library for parsing XML to a DOM.
*   [whisker (⭐39)](https://github.com/hungrybluedev/whisker) - Fast, robust template engine for V inspired by mustache.
*   [lexical\_uuid (⭐4)](https://github.com/einar-hjortdal/lexical_uuid) - Lexicographically-sortable universally unique identifiers.

### User Interface toolkits

*   [iUI (⭐115)](https://github.com/isaiahpatton/ui) - Isaiah's cross-platform GUI library for V. Inspired by the syntax of Java's Swing.
*   [mui (⭐108)](https://github.com/malisipi/mui) - A Cross-Platform UI library for Windows, Linux, Android and Web.
*   [V UI (⭐2.4k)](https://github.com/vlang/ui) - Integrated cross platform UI toolkit for Windows, macOS, Linux, Android, iOS and the web.
*   [vgtk3 (⭐62)](https://github.com/vgtk/vgtk3) - A wrapper for GTK3 in V.
*   [vig (⭐55)](https://github.com/nsauzede/vig) - Bindings for [Dear ImGui (⭐64k)](https://github.com/ocornut/imgui) GUI toolkit.
*   [vnk (⭐53)](https://github.com/nsauzede/vnk) - Bindings for [Nuklear (⭐14k)](https://github.com/vurtun/nuklear) GUI toolkit.
*   [V-WebUI (⭐126)](https://github.com/webui-dev/v-webui) - A wrapper for WebUI. A lightweight library that allows you to use any web browser as a GUI, with V in the backend and HTML5 in the frontend.
*   [webview (⭐71)](https://github.com/ttytm/webview) - Bindings for webview. A tiny library to build modern cross-platform GUI applications. It allows to combine V with modern web technologies to design a graphical user interface.

### Utility

*   [dialog (⭐29)](https://github.com/ttytm/dialog) - A cross-platform utility library to open system dialogs - open files, message boxes, color-pickers etc.
*   [dotenv (⭐2)](https://github.com/einar-hjortdal/dotenv) - Loads environment variables from a .env file for development purposes.
*   [json2v (⭐29)](https://github.com/ldedev/Json2V) - Convert a json to a struct in Vlang.
*   [objc (⭐8)](https://github.com/magic003/objc) - V bindings to Objective-C runtime.
*   [range (⭐33)](https://github.com/Delta456/range) - Functionality of Python's range() in V.
*   [ssh-config](https://github.com/walkingdevel/ssh-config) - A V library for parsing SSH config files.
*   [vaker (⭐17)](https://github.com/ChAoSUnItY/vaker) - A light-weight compile-time-generated data faker written in V.
*   [vdotenv (⭐40)](https://github.com/zztkm/vdotenv) - Support for .env files which loads environment variables.
*   [vhs (⭐4)](https://github.com/KevinDaSilvaS/vhs) - Haskell prelude list functions(zip, zipwith, head, etc) implemented in V.
*   [VInstall (⭐38)](https://github.com/malisipi/VInstall) - A cross-platform installer creator.
*   [votp (⭐19)](https://github.com/OdaiGH/votp) - TOTP and HOTP implementation in v.

### Web

*   [pico.v (⭐113)](https://github.com/S-YOU/pico.v) - A web server in V based on picoev and picohttpparser.
*   [v-jsonrpc (⭐34)](https://github.com/nedpals/v-jsonrpc) - Basic JSON-RPC 2.0-compliant server written on V.
*   [v-tiktok](https://github.com/walkingdevel/v-tiktok) - A V library for downloading TikTok videos.
*   [validate (⭐21)](https://github.com/endeveit/v-validate) - A simple library to validate strings in V.
*   [valval (⭐153)](https://github.com/taojy123/valval) - Web framework written in V, improved by vweb.
*   [vcurrency (⭐7)](https://github.com/mehtaarn000/vcurrency) - API wrapper (written in V) for <https://api.exchangeratesapi.io>.
*   [veb (⭐36k)](https://github.com/vlang/v/tree/master/vlib/veb) - V's built-in web framework.
*   [vest (⭐5)](https://github.com/alexferl/vest) - A REST client in V.
*   [vex (⭐343)](https://github.com/nedpals/vex) - Web framework written on V inspired by Express and Sinatra.
*   [vigest (⭐4)](https://github.com/withs/vigest) - Simple client for digest authentication (written in V).
*   [vistas (⭐1)](https://github.com/einar-hjortdal/vistas) - Central file server API.
*   [vite.v (⭐4)](https://github.com/siguici/vite.v) - Seamless [Vite.js](https://vite.dev) integration for Veb applications.
*   [vxbloauth (⭐8)](https://github.com/WolvesFortress/vxbl-oauth) - A minimalistic Xbox Live authenticator for vweb.
*   [west (⭐10)](https://github.com/Dracks/West) - A wrapper of vweb to work in a similar way as nestjs works with modules and dependency injection.

## Other

### Articles

*   [An introduction to V](https://simonknott.de/articles/VLang.html)

### Books

*   [Getting Started with V Programming - Navule Pavan Kumar Rao - Packt 2021 Dec](https://www.amazon.com/Getting-Started-Programming-end-end-ebook/dp/B09FKK3JL7/ref=sr_1_1?keywords=Getting+started+with+V+programming\&qid=1639480830\&sr=8-1) - Introductory book on V.

### Communities

*   [V Community](https://github.com/v-community)

### Editor plugins

#### Atom

*   [language-v (⭐7)](https://github.com/Cutlery-Drawer/language-v) - V language support for Atom (port of vscode-vlang).

#### Emacs

*   [v-mode (⭐62)](https://github.com/damon-kwok/v-mode) - Emacs major mode for the V programming language.
*   [vlang-mode.el (⭐13)](https://github.com/Naheel-Azawy/vlang-mode.el) - Emacs major mode for the V programming language.

#### Sublime Text 3

*   [sublime-v (⭐15)](https://github.com/onerbs/sublime-v) - Fully-featured Sublime Text 3 package for the V Programming Language.
*   [vlang-sublime (⭐18)](https://github.com/oversoul/vlang-sublime) - Sublime text 3 Support for the Vlang Programming Language.

#### VS Code

*   [vscode-vlang (⭐392)](https://github.com/vlang/vscode-vlang) - V Language extension for Visual Studio Code.
*   [v-analyzer (⭐144)](https://github.com/vlang/v-analyzer) - Bring IDE features for the V programming language to VS Code.

#### Vim

*   [v-vim (⭐177)](https://github.com/ollykel/v-vim) - Support for V syntax highlighting in Vim.
*   [vim-v (⭐25)](https://github.com/cheap-glitch/vim-v) - Quality syntax highlighting for the V programming language.
*   [vim-vtools (⭐17)](https://github.com/zakuro9715/vim-vtools) - V tools for Vim, including auto formatting.

### Forums

*   [r/vlang](https://www.reddit.com/r/vlang)
*   [Stack Overflow](https://stackoverflow.com/questions/tagged/vlang)

### GitHub actions

*   [action-create-v-docs](https://github.com/marketplace/actions/create-documentation-for-v-modules) - GitHub action to create documentation for V modules.
*   [setup-v](https://github.com/marketplace/actions/setup-vlang) - GitHub action to install and use V in your workflow.

### GitHub templates

*   [v-project-basement (⭐13)](https://github.com/ArtemkaKun/v-project-basement) - A basement for every V project, that contains universal minimum GitHub CI scripts and issue templates for a V project.

### IDEs with V

*   [Vide (⭐125)](https://github.com/IsaiahPatton/Vide)

### Online IDEs with V

*   [V Playground](https://play.vlang.io)
*   [V Playground (old)](https://v-wasm.now.sh/)
*   [VOSCA V Playground](https://play.vosca.dev)

### Operating Systems & OS Development Examples

*   [limine-v-template (⭐0)](https://github.com/plos-clan/limine-v-template) - A simple template for building a Limine-compliant kernel in V.
*   [Simple Linux kernel module example (⭐27)](https://github.com/spytheman/simple_kernel_module_in_v) - Demonstration & test of writing a very simple Linux kernel module, using V.
*   [v-limine (⭐0)](https://github.com/wenxuanjun/v-limine) - A V library for handling Limine boot protocol structures.

### Patterns

*   [MVU.v (⭐5)](https://github.com/ArtemkaKun/MVU.v) - MVU pattern (The Elm Architecture) implemented in V programming language.

### Programming contests

*   [Advent of Code 2019 (⭐12)](https://github.com/mvlootman/aoc2019) - Solution of Advent of Code 2019 in V.
*   [Advent of Code 2022 (⭐43)](https://github.com/vlang/adventofcode) - Solution of Advent of Code 2022 in V.
*   [Rosetta Code in V](https://rosettacode.org/wiki/Category:V_\(Vlang\)) - Solutions for Rosetta Code in V.
*   [SoloLearn Coding Challenges (⭐16)](https://github.com/Serkonda/v-sololearn-coding-challenges) - Implementation of the SoloLearn coding challenges in V.

### Syntax highlighting

*   [kate-syntax-highlight-v (⭐21)](https://github.com/Larpon/kate-syntax-highlight-v) - V syntax highlighting for [Kate](https://kate-editor.org/).
*   [scite-v-support (⭐2)](https://github.com/sunnylcw/scite-v-support) - V syntax highlighting for [SciTE](https://www.scintilla.org/SciTE.html).

### Tutorials

*   [Learn V in Y Minutes (⭐62)](https://github.com/v-community/learn_v_in_y_minutes)
*   [V by Example (⭐170)](https://github.com/v-community/v_by_example) - V book as [GitBook](https://v-community.gitbook.io/v-by-example/).
*   [V for Node Devs (⭐28)](https://github.com/Thigidu/vlang-for-nodejs-developers) - Vlang for node js developers.
*   [V learning notes (⭐172)](https://github.com/lydiandy/vlang_note) - Personal learning notes in Chinese.
*   [VOSCA Blog Tutorials](https://blog.vosca.dev/categories/tutorials/) - Tutorial category on VOSCA blog.

### Videos

*   [The V Programming Language](https://www.youtube.com/channel/UCLZIElNyubHOvbfudT7KS1A)
*   [V Programming Tutorials](https://www.youtube.com/watch?v=BVCuZ7z7GMY\&list=PLEPMhdsq-gNpFr40A-ZnX-Hu9l-Sp5Oc_)

