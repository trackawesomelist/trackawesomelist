# Awesome D Overview

  A curated list of awesome D documents, frameworks, libraries and software. Inspired by awesome-python.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/dlang-community/awesome-d/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 dlang-community/awesome-d](https://github.com/dlang-community/awesome-d) · ⭐ 658 · 🏷️ Programming Languages

[ [Daily](/content/dlang-community/awesome-d/README.md) / [Weekly](/content/dlang-community/awesome-d/week/README.md) / Overview ]

---

# Awesome D [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

***

A curated list of awesome D frameworks, libraries and software. Inspired by [awesome-python (⭐219k)](https://github.com/vinta/awesome-python).

I created this list so that when I needed something in the future, it would be easy to find. Most of the documents and links are collected from the [D forum](https://forum.dlang.org), the [D wiki](https://wiki.dlang.org), and the [D package repository](https://code.dlang.org). Exploring GitHub also helps as many of the libs are hosted there.

If you know an interesting lib/app in D, please tell us through [GitHub issues (⭐657)](https://github.com/dlang-community/awesome-d/issues) or [edit this file (⭐657)](https://github.com/dlang-community/awesome-d/edit/master/README.md).

# Contents

*   [Awesome D](#awesome-d)
    *   Basic Information
        *   [Official Website](#official-website)
        *   [Getting Help](#getting-help)
        *   [People](#people)
        *   [Events](#events)
        *   [Organizations](#organizations)
    *   Documents
        *   [Books](#books)
        *   [Tutorials](#tutorials)
        *   [Blogs](#blogs)
        *   [Articles](#articles)
    *   Language Related
        *   [Package Management](#package-management)
        *   [Compilers](#compilers)
        *   [WIP Compilers](#wip-compilers)
        *   [Dev Tools](#dev-tools)
        *   [Build Tools](#build-tools)
        *   [IDEs & Editors](#ides--editors)
        *   [Lexers, Parsers, Generators](#lexers-parsers-parser-generators)
        *   [Preprocessors](#preprocessors)
    *   Compiler for other languages
        *   [Javascript](#javascript)
    *   Common/Utilities
        *   [Basic](#basic)
        *   [Containers](#containers)
    *   Continuous Integration
        *   [GitHub Actions](#github-actions)
        *   [Testing Frameworks](#testing-frameworks)
    *   Networking/Web Related
        *   [Networking](#networking-library)
        *   [Web Frameworks](#web-frameworks)
        *   [Data\&Serialization](#data-serialization)
    *   Database
        *   [Database clients](#database-clients)
    *   GUI
        *   [GUI Libs](#gui-libs)
    *   OS
        *   [Operating Systems](#os)
    *   Gaming
        *   [Bindings](#game-bindings)
        *   [Game Engine Bindings](#game-engine-bindings)
        *   [Frameworks](#game-frameworks)
        *   [Games](#games)
    *   Internationalization (i18n) / Globalization
        *   [Internationalization](#internationalization)
    *   Video
        *   [Applications](#video-applications)
    *   Image Processing
        *   [Applications](#image-processing)
    *   End-user applications (AppImages, Flatpaks, Snaps...)
        *   [Applications](#end-user-applications)
    *   Scientific
        *   [Scientific](#scientific)
        *   [Language Processing](#language-processing)
    *   Machine Learning
        *   [Machine Learning](#machine-learning)
    *   [Parallel computing](#parallel-computing)
    *   Others
        *   [Text Processing](#text-processing)
        *   [Command Line](#command-line)
        *   [Logging](#logging)
        *   [Configuration](#configuration)
        *   [BlogEngine](#blog-engine)
        *   [Dependency Injection](#dependency-injection)
*   [Other Awesome Lists](#other-awesome-lists)

## Official Website

*Official Website URLs.*

*   [dlang.org](https://dlang.org) - Official website for D.
*   [wiki.dlang.org](https://wiki.dlang.org) - Official Wiki for D.
*   [code.dlang.org](https://code.dlang.org) - Offical Library/Module Registry for D.
*   [Github Organization](https://github.com/dlang) - Official GitHub organization for D. Repo for all official D tools & code.
*   [forum.dlang.org](https://forum.dlang.org/) - Official forum. Many interesting discussions occurring on a daily basis.
*   [blog.dlang.org](https://dlang.org/blog/) - Official blog.
*   [Language Specification](https://dlang.org/spec/spec.html) - D programming language specification.
*   [Issue tracking](https://issues.dlang.org/) - Official issue tracking/reporting system for D. If you find bugs in the D compiler and/or libraries, please come and report them!

## Getting Help

*For when you're stuck.*

*   [Official D Forum Learn Group](https://forum.dlang.org/group/learn) - Highest traffic site for answering D questions.
*   [D on Stack Overflow](https://stackoverflow.com/questions/tagged/d) - Less traffic than forums but possibly easier to search.
*   [D on Rosetta Code](https://rosettacode.org/wiki/Category:D) - Examples of how to do many basic things in D.
*   [D on Discord](https://discord.gg/invite/bMZk9Q4) - Another very active community for D conversations and question.

## People

*The people that made D the language it is.*

*   [Walter Bright](https://www.walterbright.com/) - Father of D. Walter Bright is the creator and first implementer of the D programming language and has implemented compilers for several other languages.
*   [Andrei Alexandrescu, PhD](http://erdani.com/) - C++ guru. Author of *The D Programming Language* and *Modern C++ Design*. With Walter Bright, Andrei co-designed many important features of D and authored a large part of D's standard library. Andrei works as a trainer in advanced C++ programming and algorithms and is now actively evangelizing D in the organization.
*   [Átila Neves](https://atilaoncode.blog/) - [Deputy Leader of D](https://dlang.org/blog/2019/10/15/my-vision-of-ds-future/).
*   **YOU** - Please add your information if you've done something interesting in D. It is you, the awesome people that made D awesome.

## Events

*   [DConf](https://dconf.org/) - the premier event where D luminaries exchange knowledge, insight, and inspiration on everything related to the D language and its ecosystem.

## Organizations

*Organizations that contribute to D projects.*

*   [D Programming Language](https://github.com/dlang) - Official Organization, hosts DMD, Phobos and other official tools and libs.
*   [LDC Developers](https://github.com/ldc-developers) - LDC releated projects.
*   [DerelictOrg](https://github.com/DerelictOrg) - A GitHub organization hosting all Derelict bindings including OpenGL and other multimedia/game related library bindings. (OpenGL 3, Bgfx, ENet,  SDL 2, GLFW 3，OpenGLES, Free Image, Assimp3, libtheora, libogg, libvorbis, SFML 2, libpq, PhysicsFS, Open Dynamics Engine, Lua, DevIL, OpenAL, ALURE).
*   [DlangScience](https://github.com/DlangScience) -A focal point and first port of call for scientific libraries and tooling for D.
*   [Circular Studios](https://github.com/Circular-Studios) - We are a group of game developers at Rochester Institute of Technology building games and game tech. Hosts [Dash (⭐422)](https://github.com/Circular-Studios/Dash), a 3D game engine written in D, and other related libs.
*   [EMSI](https://github.com/economicmodeling) - A Career building company that uses D as their main language. Hosts their opensource projects.
*   [infognition](http://www.infognition.com/company.html) - Infognition is a self-funded and self-sustained company specializing in video processing and compression technologies for end-users and developers. They provide several opensource video related applications & tools written in D, hosted on [bitbucket](https://bitbucket.org/infognition/). They are also porting their main product--[Video Enchanser](http://www.infognition.com/VideoEnhancer/) from C/C++ to D.
*   [libmir](https://github.com/libmir) - D's numeric library development team
*   [sociomantic labs](https://www.sociomantic.com) - Berlin based company specializing in real-time bidding for online advertising. Main sponsor of the [annual D language conference](http://dconf.org). Has open-sourced large parts of their codebase as part of the [tsunami](https://github.com/sociomantic-tsunami) organization.
*   [Symmetry Investments](https://symmetryinvestments.com/) - Symmetry Investments LP is an investment management company with approximately US$4.7 billion in assets under management as of 31 December 2018. Main sponsor of the [Symmetry Autumn of Code](https://dlang.org/blog/symmetry-autumn-of-code/). Have sponsored the development of [excel-d](https://dlang.org/blog/2017/05/31/project-highlight-excel-d/), [dpp (⭐230)](https://github.com/atilaneves/dpp), [autowrap (⭐80)](https://github.com/symmetryinvestments/autowrap), [mir-algorithm (⭐173)](https://github.com/libmir/mir-algorithm), and various other projects.
*   [HuntLabs](https://www.huntlabs.net) - A technology group using DLang. Have pure D language implementation of quickly develop server-side applications and build distributed system services.

## Books

*D related books.* You can find another list of books on the [Books](https://wiki.dlang.org/Books) D wiki page.

*   [TDPL](https://www.amazon.com/The-Programming-Language-Andrei-Alexandrescu/dp/0321635361/) - *The D Programming Language* by Andrei Alexandrescu.
*   [Programming in D](https://ddili.org/ders/d.en/index.html) - A very detailed book about programming in D by Ali Çehreli  covering many areas of the language. Has a free online version and is suitable for beginners.
*   [D Cookbook](https://www.packtpub.com/product/d-cookbook/9781783287215) - A recipe-packed reference guide filled with practical tasks that are concisely explained to develop and broaden the user's abilities with the D programming language. by Adam D. Ruppe. Here is an interesting [review of the book](https://www.cppstories.com/2014/08/review-of-d-cookbook/).
*   [Learning D](https://www.packtpub.com/product/learning-d/9781783552481) - This book is intended for those with some background in a C-family language who want to learn how to apply their knowledge and experience to D. (...) This book will help you get up to speed with the language and avoid common pitfalls that arise when translating C-family experience to D.
*   [D Web Development](https://www.packtpub.com/product/d-web-development/9781785288890) - Whether you are new to the world of D, or already have developed applications in D, or if you want to leverage the power of D for web development, then this book is ideal for you.

## Tutorials

*D related tutorials.*

*   [The Dlang Tour](https://tour.dlang.org/) - An interactive tutorial for D, inspired by Golang Tour.
*   [Programming in Dlang](https://www.youtube.com/watch?v=HS7X9ERdjM4\&list=PLvv0ScY6vfd9Fso-3cB4CGnSlW0E4btJV\&ab_channel=MikeShah) - An introductory video series about programming in D.
*   [Pragmatic D tutorial](https://qznc.github.io/d-tut/index.html) - This is a pragmatic introduction to the D Programming Language. by Andreas Zwinkau.
*   [D Template Tutorial (⭐229)](https://github.com/PhilippeSigaud/D-templates-tutorial) - A tutorial dedicated to D Templates. Very good explanation about templates. Has pdf version. by Philippe Sigaud.
*   [Component programming in D](https://www.drdobbs.com/architecture-and-design/component-programming-in-d/240008321) - An article written by Walter Bright that details how D's functional support leads to a flexible and beautiful component programming style.
*   [Component programming with ranges](https://wiki.dlang.org/Component_programming_with_ranges) - A detailed blog post about how to do component programming in a idiomatic D way with ranges, with a full working example.
*   [Functional image processing in D](https://blog.cy.md/2014/03/21/functional-image-processing-in-d/) - A very interesting tutorial about writing an image processing lib in D. Shows the power of D's templates/CTFE/Ranges/UFCS for functional style programming.
*   [OpenGL tutorials](https://github.com/d-gamedev-team/opengl-tutorials) - OpenGL tutorials in D.
*   [Creating a simple JSON serialiser in D](https://bradley.chatha.dev/BlogPost/JsonSerialiser/0) - D metaprogramming tutorial series
*   [Let's learn D programming Game Dev!](https://www.youtube.com/watch?v=j-Zm1zgSxMQ\&list=PLgM-lc_kSqFQPF0UXgmFZpZalqcrSofe-\&ab_channel=KiRill) - A video series on learning game development with D from Ki Rill. [His channel](https://www.youtube.com/@rillki-dev/) also posts other videos related to D programming.
*   [DLang YouTube Tutorials from Mike Shah](https://www.youtube.com/playlist?list=PLvv0ScY6vfd9Fso-3cB4CGnSlW0E4btJV) - Series of tutorials covering basic to advanced features of the D programming language and standard library.

### Bare metal / kernel development

*   [D Bare bones](https://wiki.osdev.org/D_Bare_Bones) - kernel hello world in D (using GDC compiler)
*   [D barebone with ldc2](https://wiki.osdev.org/D_barebone_with_ldc2) - another kernel hello world in D (using LDC compiler)
*   [XOmB bare bones](https://web.archive.org/web/20161214232759/http://wiki.xomb.org/index.php?title=XOmB_Bare_Bones) - an exokernel operating system written in D. [Main page](https://web.archive.org/web/20161201061242/http://wiki.xomb.org/index.php?title=Main_Page), [github (⭐340)](https://github.com/xomboverlord/xomb/tree/unborn).
*   [Bare Metal ARM Cortex-M GDC Cross Compiler](https://wiki.dlang.org/Bare_Metal_ARM_Cortex-M_GDC_Cross_Compiler) - building a bare metal ARM Cortex-M (arm-none-eabi) GDC cross compiler for a Linux host.

## Blogs

*D related blogs.*

*   [blog.dlang.org](https://dlang.org/blog/) - Official blog.
*   [/r/d\_language on Reddit](https://www.reddit.com/r/d_language/) - A feed of news and blog posts about D.
*   [This week in D](https://dpldocs.info/this-week-in-d/Blog.html) - A weekly overview of activity in the D community and brief advice columns to help you get the most out of the D Programming Language.
*   [Planet D](http://planet.dsource.org) - A repository of co-authored D-specific blogs maintained by Vladimir Panteleev.
*   [D Idioms](https://p0nce.github.io/d-idioms/) - A great blog for many useful idioms with D programming.
*   [GTK-D coding](https://gtkdcoding.com/) - Simple examples of how to use GtkD to build GUI applications.
*   [Tasty D](https://tastyminerals.github.io/tasty-blog/) - A blog about learning the D programming language and various D language trivia.

## Articles

*D related Articles.*

*   [Origins of the D programming language](https://dl.acm.org/doi/pdf/10.1145/3386323) - By Walter Bright, Andrei Alexandrescu, Michael Parker. The history and development of D language.
*   [Purity in D](https://klickverbot.at/blog/2012/05/purity-in-d/) - An article that explains the design principles behind D's purity feature.
*   [Hidden treasures in the D standard library](https://web.archive.org/web/20171119072212/http://nomad.so/2014/08/hidden-treasure-in-the-d-standard-library/) - An article talking about several useful functions and templates in Phobos.
*   [Porting D Runtime to ARM](https://github.com/JinShil/D_Runtime_ARM_Cortex-M_study) - A study about porting a minimal D runtime to ARM Cortex-M preprocessors.
*   [D is for Data Science](https://tech.nextroll.com/blog/data/2014/11/17/d-is-for-data-science.html) - A great post about how D is suitable for data science, particularly, replacing the role of python scripts for fast prototyping.
*   [D Functional Garden](https://garden.dlang.io/)

## Package Management

*Libraries for package and dependency management.*

*   [code.dlang.org](https://code.dlang.org/) - Official D library repository. Backed by dub.

*   [dub (⭐672)](https://github.com/dlang/dub) - Official package and build management system for D.

## Compilers

*Compile software from source code.*

*   [dmd (⭐3k)](https://github.com/dlang/dmd) - The reference compiler for the D programming language. Stable, builds insanely fast, very good for learning and rapid prototyping/development. Currently the frontend is implemented in D, and shared between dmd, ldc and gdc, the backend is implemented in C++.
*   [ldc (⭐1.2k)](https://github.com/ldc-developers/ldc) - The LLVM-based D compiler. Uses the DMD frontend and LLVM backend. Builds slower than dmd, but generates more optimized code than DMD. It supports all the target platforms of LLVM.
*   [gdc (⭐359)](https://github.com/D-Programming-GDC/GDC) - GNU D Compiler. Use DMD frontend and GCC backend. Currently targets the most platforms due to the use of GCC. Generated code runs faster than DMD in most cases, on par with LDC. In the process of integration with the official GCC toolchain.

## WIP Compilers

*   [sdc (⭐246)](https://github.com/snazzy-d/SDC) - The Snazzy D Compiler. Written in D. Grows Smarter every day.

## Dev Tools

*Tools for more productive D development.*

*   [D-Scanner (⭐241)](https://github.com/dlang-community/D-Scanner) - Swiss-army knife for D source code (linting, static analysis, D code parsing, etc.)
*   [dfmt (⭐204)](https://github.com/dlang-community/dfmt) - formatter for D source code

## Build Tools

*Manage projects and compile software from source code.*

*   [dub (⭐672)](https://github.com/dlang/dub) - De facto official package and build management system for D. Will be included officially soon.
*   [scons-d](https://scons.org/) - Scons has built-in support for building D projects, thanks to Russel Winder.
*   [premake (⭐2)](https://github.com/premake/premake-dlang) - Premake has built-in support for D projects
*   [reggae (⭐183)](https://github.com/atilaneves/reggae) - meta build system in D
*   [Makefile (⭐20)](https://github.com/bioinfornatics/MakefileForD) - Makefile template for D projects
*   [cmake-d (⭐65)](https://github.com/dcarp/cmake-d) - CMake D Projects
*   [cook2 (⭐25)](https://github.com/gecko0307/Cook2) - Fast incremental build tool intended for projects in D
*   [button](https://jasonwhite.io/button/) - A universal build system to build your software at the push of a button.
*   [wild (⭐6)](https://github.com/Vild/Wild) - Wild build system, used to build the [PowerNex (⭐491)](https://github.com/PowerNex/PowerNex) kernel
*   [XMake](https://xmake.io) - XMake is a crossplatform build system, that incorporated the D language and also has support for DUB repositories.
*   [wox (⭐0)](https://github.com/redthing1/wox) - A highly flexible recipe build system inspired by Make

<a name="ide"></a>

## IDEs & Editors

*Integrated Development Environment.*

*   [Visual D (⭐288)](https://github.com/dlang/visuald) - Visual Studio extension for the D programming language.
*   [IntelliJ D Language](https://intellij-dlanguage.github.io/) - Support for the D programming language within IntelliJ IDEA.
*   [Dexed](https://gitlab.com/basile.b/dexed) - IDE for the D programming language, its compilers, tools and libraries.
*   [Dutyl (⭐79)](https://github.com/idanarye/vim-dutyl) - Vim plugin that integrates various D development tools
*   [code-d](https://marketplace.visualstudio.com/items?itemName=webfreak.code-d) <sup>\[[open-vsx](https://open-vsx.org/extension/webfreak/code-d)]</sup> - Visual Studio Code extension using serve-d
*   [ide-d](https://atom.io/packages/ide-d) - Atom extension for D using serve-d

<br/>

*   [DCD (⭐349)](https://github.com/dlang-community/DCD) - Independent auto-complete program for the D programming language. Could be used with editors like vim, emacs, sublime text, textadept, and zeus. See [editors support (⭐349)](https://github.com/dlang-community/DCD/wiki/IDEs-and-Editors-with-DCD-support).
*   [serve-d (⭐200)](https://github.com/Pure-D/serve-d) - Language Server Protocol (LSP) implementation for D.  Adds modern IDE features to any editor with LSP support (VSCode, Atom, Vim/Neovim and others)

## Lexers, Parsers, Parser Generators

*   [libdparse (⭐115)](https://github.com/dlang-community/libdparse) - A D language lexer and parser, (possibly) future standard D parser/lexer.
*   [Martin Nowak's Lexer (⭐13)](https://github.com/MartinNowak/lexer) - A lexer generator.
*   [Mono-D's DParser (⭐30)](https://github.com/aBothe/D_Parser) - A D parser written in C# and used in Mono-D.
*   [Pegged (⭐534)](https://github.com/PhilippeSigaud/Pegged) - A Parsing Expression Grammar (PEG) module written in D.
*   [Goldie](https://bitbucket.org/Abscissa/goldie/wiki/Home) - Goldie Parsing System.
*   [ctpg (⭐45)](https://github.com/youxkei/ctpg) - Compile-Time Parser (with converter) Generator written in D.
*   [dunnart (⭐14)](https://github.com/pwil3058/dunnart) - LALR(1) Parser Generator written in D.

## Preprocesors

*   [warp (⭐526)](https://github.com/facebookarchive/warp) - A fast preprocessor for C and C++ used in Facebook infrastructure. Written by Walter Bright.

## Javascript

*   [higgs (⭐875)](https://github.com/higgsjs/Higgs) -  Higgs JavaScript Virtual Machine, implemented in D.

## Basic

*   [hunt (⭐95)](https://github.com/huntlabs/hunt) - A refined core library for D programming language. The module has concurrency / collection / event / io / logging / text / serialize and more.
*   [hunt-time (⭐2)](https://github.com/huntlabs/hunt-time) - A time library and similar to Joda-time and Java.time api.
*   [hunt-validation (⭐3)](https://github.com/huntlabs/hunt-validation) - A data validation library for DLang based on hunt library.

## Containers

*   [EMSI containers (⭐110)](https://github.com/dlang-community/containers) -  Containers that do not use the GC

<!---->

*   [memutils (⭐42)](https://github.com/etcimon/memutils) - Overhead allocators, allocator-aware containers and lifetime management for D objects
*   [dlib.container (⭐217)](https://github.com/gecko0307/dlib) - generic data structures (GC-free dynamic and associative arrays and more)
*   [std.rcstring (⭐9)](https://github.com/burner/std.rcstring) - A reference counted string implementation for D's build in string construct

## GitHub Actions

*   [setup-dlang (⭐46)](https://github.com/dlang-community/setup-dlang) - Install D compilers & DUB inside GitHub Actions
*   [dub-upgrade (⭐1)](https://github.com/WebFreak001/dub-upgrade) - Run `dub upgrade` trying to repeat on network failure and using package cache on GitHub Actions

<a name="testing"></a>

## Testing Frameworks

*   [silly](https://gitlab.com/AntonMeep/silly) - Better test runner for the D programming language. No nonsense.
*   [dunit (⭐62)](https://github.com/nomad-software/dunit) - Advanced unit testing & mocking toolkit
*   [unit-threaded (⭐121)](https://github.com/atilaneves/unit-threaded) - Multi-threaded unit test framework

## Web Frameworks

*Networking library*

*   [hunt-net (⭐21)](https://github.com/huntlabs/hunt-net) - High-performance network library for D programming language, event-driven asynchonous implemention(IOCP / kqueue / epoll).
*   [hunt-http (⭐32)](https://github.com/huntlabs/hunt-http) - HTTP/1 and HTTP/2 protocol library for D.
*   [hunt-stomp (⭐0)](https://github.com/huntlabs/hunt-stomp) - STOMP for websocket protocol library implement in D.
*   [libasync (⭐144)](https://github.com/etcimon/libasync) -  Cross-platform event loop library of asynchronous objects
*   [libhttp2 (⭐35)](https://github.com/etcimon/libhttp2) -  HTTP/2 library in D, translated from nghttp2
*   [collie (⭐61)](https://github.com/huntlabs/collie) -  An asynchronous event-driven network framework written in dlang, like netty framework in D.
*   [dlang-requests (⭐154)](https://github.com/ikod/dlang-requests) - HTTP client library inspired by python-requests
*   [Handy-Httpd (⭐33)](https://github.com/andrewlalis/handy-httpd) - A simple, lightweight, and well-documented HTTP server that lets you bootstrap ideas and have something up and running in minutes.
*   [serverino (⭐52)](https://github.com/trikko/serverino) - Small and ready-to-go http server, in D

*Full stack web frameworks.*

*   [Hunt Framework (⭐300)](https://github.com/huntlabs/hunt-framework/) - Hunt is a high-level D Programming Language Web framework that encourages rapid development and clean, pragmatic design. It lets you build high-performance Web applications quickly and easily.
*   [vibe.d](https://vibed.org/) - Asynchronous I/O Web Framework that doesn’t get in your way, written in D.
*   [arsd (⭐531)](https://github.com/adamdruppe/arsd) - Adam D. Ruppe's web framework.
*   [cmsed (⭐18)](https://github.com/rikkimax/Cmsed) - A component library for Vibe that functions as a CMS.

*RPC library*

*   [grpc (⭐44)](https://github.com/huntlabs/grpc-dlang) - Grpc for D programming language, hunt-http library based.
*   [kissrpc (⭐40)](https://github.com/huntlabs/kissrpc) - Fast and light, flatbuffers based rpc framework.
*   [Hprose (⭐26)](https://github.com/hprose/hprose-d) - A very newbility RPC Library for D, and it support 25+ languages now.
*   [Apache Thrift](https://thrift.apache.org/) - A lightweight, language-independent, featureful RPC framework.  Thrift provides clean abstractions for data transport, data serialization, code generation, and application level processing.  [Dub package](https://code.dlang.org/packages/apache-thrift)

*Gossip*

*   [hunt-gossip (⭐0)](https://github.com/huntlabs/hunt-gossip) - A Apache V2 gossip protocol implementation for D programming language.

*Cache*

*   [hunt-cache (⭐6)](https://github.com/huntlabs/hunt-cache) - D language universal cache library, using radix, redis and memcached.

*Static Site Generator*

*   [DSSG (⭐20)](https://github.com/kambrium/dssg) - A static site generator with a different approach.

## Data serialization

*Json, XML, protobuf and other data serialization libs.*

### Binary Serilization

*   [flatbuffers (⭐11)](https://github.com/huntlabs/flatbuffers) - D Programming Language implementation of the google flatbuffers library.
*   [cerealed (⭐92)](https://github.com/atilaneves/cerealed)  - Serialisation library for D
*   [dproto (⭐37)](https://github.com/msoucy/dproto) - Google Protocol Buffer support in D.

### JSON

*   [vibe.data.json](https://vibed.org/api/vibe.data.json/) - JSON functions in Vibe.d. Currently the best implementation I used.
*   [fast.json (⭐112)](https://github.com/etcimon/fast) -  A library for D that aims to provide the fastest possible implementation of some every day routines.
*   [std.json](https://dlang.org/phobos/std_json.html) - D's standard library JSON module. Needs refinement.
*   [painlessjson (⭐23)](https://github.com/BlackEdder/painlessjson) - Convert between D types and std.json.
*   [std.data.json (⭐25)](https://github.com/dlang-community/std_data_json) - Phobos candidate for JSON serialization (based on Vibed)
*   [asdf (⭐20)](https://github.com/libmir/asdf) - Cache oriented string based JSON representation for fast read & writes and serialisation.

### XML

*   [orange (⭐72)](https://github.com/jacob-carlborg/orange) - General purpose serializer (currently only supports XML)
*   [std.experimental.xml (⭐20)](https://github.com/lodo1995/experimental.xml) - Phobos candidate for a XML serialization
*   arsd [dom.d (⭐531)](https://github.com/adamdruppe/arsd/blob/master/dom.d) - an xml/html DOM based on what Javascript provides in browsers

## Database clients

*Clients and bindings to C bliencts for relational and nosql databases.*

*   [hunt-entity (⭐57)](https://github.com/huntlabs/hunt-entity) - Hunt entity is an object-relational mapping tool for the D programming language. Referring to the design idea of JPA, support PostgreSQL / MySQL / SQLite.
*   [hunt-database (⭐48)](https://github.com/huntlabs/hunt-database) - Hunt database abstraction layer for D programing language, support PostgreSQL / MySQL / SQLite.
*   [vibe.d (⭐1.1k)](https://github.com/vibe-d/vibe.d) - Vibe.d has internal support for Redis and MongoDB, which are very stable. Soon, the database drivers will be separated into independent projects.
*   [mysql-native (⭐80)](https://github.com/mysql-d/mysql-native) - A MySQL client implemented in native D.
*   [ddb (⭐39)](https://github.com/pszturmaj/ddb) - Database access for D2. Currently only supports PostgreSQL.
*   [arsd (⭐531)](https://github.com/adamdruppe/arsd) - Adam D. Ruppe's library; in addition to a Web backend, it also has support for database access with database.d, sqlite.d, mysql.d and postgres.d.
*   [ddbc (⭐78)](https://github.com/buggins/ddbc) - DDBC is a DB Connector for D language (similar to JDBC). HibernateD (see below) uses ddbc for database abstraction.
*   [hibernated (⭐82)](https://github.com/buggins/hibernated) - HibernateD is an ORM for D (similar to [Hibernate](https://hibernate.org/)).
*   [dvorm (⭐17)](https://github.com/rikkimax/Dvorm) - An ORM for D with Vibe support. Works with vibe.d and mysql-d, giving it the ability to access MongoDB and MySQL.
*   [Tiny Redis](http://adilbaig.github.io/Tiny-Redis/) - Redis driver for D. Fast, Simple, Stable. Has no dependencies.
*   [libpb (⭐5)](https://github.com/Hax-io/libpb) - INteract with a PocketBase database

## Command Line

*   [hunt-console (⭐4)](https://github.com/huntlabs/hunt-console) - Hunt console creation easier to create powerful command-line applications.
*   [tilix (⭐5.4k)](https://github.com/gnunn1/tilix) -  A tiling terminal emulator for Linux using GTK+ 3.
*   [scriptlike (⭐93)](https://github.com/Abscissa/scriptlike) - Utility library to aid writing script-like programs in D.
*   [todod (⭐15)](https://github.com/BlackEdder/todod) - Todod is a command line based todo list manager. It also has support for shell interaction based on [linenoise (⭐3.7k)](https://github.com/antirez/linenoise).
*   [d-colorize](https://code.dlang.org/packages/colorize) - A port of the ruby library [colorize (⭐1.2k)](https://github.com/fazibear/colorize). It add some methods to set color, background color and text effect on console easier using ANSI escape sequences.
*   [terminal.d (⭐531)](https://github.com/adamdruppe/arsd/blob/master/terminal.d) - Part of Adam Ruppe's [arsd (⭐531)](https://github.com/adamdruppe/arsd) library supporting cursor and color manipulation on the console.
*   [dexpect (⭐12)](https://github.com/grogancolin/dexpect/) -  A D implementation of the expect framework. Handy for bash emulation.
*   [Argon (⭐17)](https://github.com/markuslaker/Argon) -  A processor for command-line arguments, an alternative to Getopt, written in D.
*   [argsd (⭐16)](https://github.com/burner/argsd) - A command line and config file parser for DLang
*   [darg (⭐38)](https://github.com/jasonwhite/darg) - Robust command line argument parsing for D.
*   [commandr (⭐41)](https://github.com/robik/commandr) - A modern, powerful commmand line argument parser.
*   [luneta (⭐62)](https://github.com/fbeline/luneta) - A command-line fuzzy finder.
*   [argparse](https://code.dlang.org/packages/argparse) - Flexible parser of command line arguments.
*   [dlog (⭐1)](https://github.com/deavmi/dlog) - extensible logging framework with message transformation support and custom loggers and contexts
*   [gogga (⭐2)](https://github.com/deavmi/gogga) - simple easy-to-use colorful logger for command-line applications

## GUI Libs

*Libraries for working with graphical user interface applications.*

*   [DLangUI (⭐804)](https://github.com/buggins/dlangui) - Cross Platform GUI for D programming language. My personal favorate, because it is written in D(not a binding), and is cross platform. DLangUI also has a good showcase in the IDE [DLangIDE (⭐447)](https://github.com/buggins/dlangide).
*   [GtkD (⭐320)](https://github.com/gtkd-developers/GtkD) - GtkD is a D binding and OO wrapper of GTK+. GtkD is actively maintained and is currently the most stable GUI lib for D.
*   [DWT (⭐141)](https://github.com/d-widget-toolkit/dwt) - A library for creating cross-platform GUI applications. GWT is a port of the Java SWT library to D. DWT was promoted as a semi-standard GUI library for D, but unfortunately didn't catch up popularity yet.
*   [tkD (⭐117)](https://github.com/nomad-software/tkd) - GUI toolkit for the D programming language based on Tcl/Tk.
*   [dqml (⭐42)](https://github.com/filcuc/dqml) -  Qt Qml bindings for the D programming language.
*   [Sciter-Dport (⭐33)](https://github.com/sciter-sdk/Sciter-Dport) - D bindings for the [Sciter](https://sciter.com) - crossplatform HTML/CSS/script desktop UI toolkit.
*   [LibUI (⭐33)](https://github.com/Extrawurst/DerelictLibui) - Dynamic Binding for [libui (⭐11k)](https://github.com/andlabs/libui)

*Note*: You can also find a list of GUI libs on [wiki.dlang.org](https://wiki.dlang.org/Libraries_and_Frameworks#GUI_Libraries), but not all of the libraries are actively maintained now.

## OS

*Operating Systems written in D*

*   [PowerNex (⭐491)](https://github.com/PowerNex/PowerNex) -  A kernel written in D
*   [SerpentOS](https://serpentos.com/) - Snek factory ([source code](https://gitlab.com/serpent-os))
*   [Trinix (⭐107)](https://github.com/Rikarin/Trinix) -  Hybrid operating system for x64 PC written in D
*   [XOmB (⭐340)](https://github.com/xomboverlord/xomb) - An exokernel operating system written in D

## Game Bindings

*Bindings to game development related C libraries.*

*   BindBC libraries - `-betterC` compatible, `@nogc` bindings using [bindbc-loader (⭐25)](https://github.com/BindBC/bindbc-loader):
    *   OpenGL - [bindbc-opengl (⭐35)](https://github.com/BindBC/bindbc-opengl)
    *   GLFW 3 - [bindbc-glfw (⭐38)](https://github.com/BindBC/bindbc-glfw)
    *   SDL 2 - [bindbc-sdl (⭐86)](https://github.com/BindBC/bindbc-sdl)
    *   SDL2\_gfx - [bindbc-sdlgfx (⭐1)](https://github.com/aferust/bindbc-sdlgfx)
    *   SFML 2 - [bindbc-sfml (⭐11)](https://github.com/BindBC/bindbc-sfml)
    *   Imgui - immediate UI - [bindbc-imgui (⭐15)](https://github.com/Inochi2D/bindbc-imgui)
    *   Nuklear - immediate UI - [bindbc-nuklear (⭐42)](https://github.com/Timu5/bindbc-nuklear)
    *   raylib3 - [bindbc-raylib3 (⭐14)](https://github.com/o3o/bindbc-raylib3)
    *   bgfx - [bindbc-bgfx (⭐21)](https://github.com/GoaLitiuM/bindbc-bgfx)
    *   WebGPU - [bindbc-wgpu (⭐25)](https://github.com/gecko0307/bindbc-wgpu)
    *   Zstandard - compression - [bindbc-zstandard (⭐2)](https://github.com/ZILtoid1991/bindbc-zstandard)
    *   nanomsg-next-gen - [bindbc-nng (⭐1)](https://github.com/darkridder/bindbc-nng)
    *   OpenAL - audio engine - [bindbc-openal (⭐7)](https://github.com/BindBC/bindbc-openal)
    *   SoLoud - audio engine - [bindbc-soloud (⭐7)](https://github.com/gecko0307/bindbc-soloud)
    *   KiWi - widget library - [bindbc-kiwi (⭐4)](https://github.com/aferust/bindbc-kiwi)
    *   NanoVG - vector drawing engine - [bindbc-nanovg (⭐3)](https://github.com/aferust/bindbc-nanovg)
    *   Blend2D - 2D Vector Graphics Powered by a JIT Compiler - [bindbc-blend2d (⭐4)](https://github.com/kdmult/bindbc-blend2d)
    *   Lua - [bindbc-lua (⭐17)](https://github.com/BindBC/bindbc-lua)
    *   JoyShockLibrary - [bindbc-jsl (⭐2)](https://github.com/ZILtoid1991/bindbc-JSL)
    *   Newton Dynamics - physics engine - [bindbc-newton (⭐8)](https://github.com/gecko0307/bindbc-newton)
    *   FreeImage - [bindbc-freeimage (⭐7)](https://github.com/BindBC/bindbc-freeimage)
    *   Assimp5 - [bindbc-assimp](https://github.com/Sobaya007/bindbc-assimp)
    *   Freetype - [bindbc-freetype (⭐15)](https://github.com/BindBC/bindbc-freetype)
    *   Harfbuzz - text shaping engine - [bindbc-harfbuzz (⭐1)](https://github.com/DlangGraphicsWG/bindbc-harfbuzz)
*   [DerelictOrg](https://github.com/DerelictOrg) - A GitHub organization hosting all Derelict bindings including:
    *   OpenGL 3 (DerelictGL3),
    *   Bgfx (DerelictBgfx),
    *   ENet (DerelictENet),
    *   SDL 2 (DerelictSDL2),
    *   GLFW 3 (DerelictGLFW3),
    *   OpenGLES (DerelictGLES),
    *   Free Image (DerelictFI),
    *   Assimp3 (DerelictASSIMP3),
    *   libtheora (DerelictTheora),
    *   libogg (DerelictOgg),
    *   libvorbis (DerelictVorbis),
    *   SFML 2 (DerelictSFML2),
    *   libpq (DerelictPQ),
    *   PhysicsFS (DerelictPHYSFS),
    *   Open Dynamics Engine (DerelictODE),
    *   Lua (DerelictLua),
    *   DevIL (DerelictIL),
    *   OpenAL (DerelictAL),
    *   ALURE (DerelictALURE).

## Game Engine Bindings

*   [Godot-D (⭐207)](https://github.com/godot-d/godot-d) - D language bindings for the Godot Engine's GDNative API

## Game Frameworks

*   [DGame (⭐85)](https://github.com/Dgame/Dgame) - A 2D framework for the D programming Language. see <http://dgame-dev.de/>.
*   [gfm (⭐3)](https://github.com/drug007/gfm7) - D gamedev toolkit.
*   [Dagon (⭐331)](https://github.com/gecko0307/dagon) - 3D game engine for D. see <https://gecko0307.github.io/dagon/>
*   [Dash (⭐422)](https://github.com/Circular-Studios/Dash) - A free and open 3D game engine written in D. see <https://circularstudios.com/dash/>.
*   [DSFML (⭐95)](https://github.com/Jebbs/DSFML) - A static binding of SFML in a way that makes sense for D. see <http://dsfml.com/>.
*   [DAllegro5 (⭐42)](https://github.com/SiegeLord/DAllegro5/tree/master/allegro5) - D binding/wrapper to Allegro 5, a modern game programming library.
*   [Voxelman (⭐126)](https://github.com/MrSmith33/voxelman) -  Plugin-based client-server voxel game engine written in D language
*   [PolyplexEngine (⭐38)](https://github.com/PolyplexEngine/libpp) - libpp is an XNA like framework written in D.
*   [rengfx (⭐82)](https://github.com/bmchtech/rengfx) - lightweight, expressive, extensible 2D/3D game engine.

## Games

*   [Spacecraft (⭐17)](https://github.com/Ingrater/Spacecraft) - A 3d multiplayer deathmatch space game written in D 2.0.
*   [Dtanks (⭐11)](https://github.com/kingsleyh/dtanks) - Robot Tank Battle Game.
*   [Electronvolt (formerly Atrium) (⭐112)](https://github.com/gecko0307/electronvolt) - FPS game with physics based puzzles using OpenGL.
*   [Backgammony (⭐41)](https://github.com/jonathanballs/backgammony) - A Backgammon GUI for Linux built with Gtk.

## Internationalization

*   [bindbc-icu (⭐2)](https://github.com/shoo/bindbc-icu) - bindbc bindings for the unicode ICU library.

## Video applications

*   [DerelictGL3 (⭐80)](https://github.com/DerelictOrg/DerelictGL3) - A dynamic binding to OpenGL for the D Programming Language.

## Image Processing

*   [ArmageddonEngine (⭐172)](https://github.com/CyberShadow/ae/tree/master/utils/graphics) - Vladimir Panteleev's ae library has a package for image processing in functional style, which is described in the article [Functional Image Processing in D](http://blog.thecybershadow.net/2014/03/21/functional-image-processing-in-d/).
*   [Blogsort](https://bitbucket.org/infognition/bsort/) -  A simple Windows app for viewing photos and preparing them for a blog.
*   [dlib.image (⭐217)](https://github.com/gecko0307/dlib) - image processing (8 and 16 bits per channel, floating point operations, filtering, FFT, HDRI, graphics formats support including JPEG and PNG)
*   [color.d (⭐531)](https://github.com/adamdruppe/arsd/blob/master/color.d) + [bmp.d (⭐531)](https://github.com/adamdruppe/arsd/blob/master/bmp.d), [jpg.d (⭐531)](https://github.com/adamdruppe/arsd/blob/master/jpg.d), [png.d (⭐531)](https://github.com/adamdruppe/arsd/blob/master/png.d) - basic color struct, HSL functions and reading and writing image files
*   [opencvd (⭐23)](https://github.com/aferust/opencvd) - Unofficial OpenCV binding for D

## End-user applications

*   [Cryptic-Resolver](https://github.com/cryptic-resolver/cr_D) -  Manage cryptic commands' names, acronyms and your own knowledge base (a command line utility)
*   [Inochi Creator (⭐796)](https://github.com/Inochi2D/inochi-creator) - Tool to create and edit Inochi2D puppets
*   [Literate (⭐662)](https://github.com/zyedidia/Literate) - A literate programming tool for any language
*   [onedrive (⭐9.9k)](https://github.com/abraunegg/onedrive) - #1 Free OneDrive Client for Linux
*   [tshare (⭐121)](https://github.com/trikko/tshare) - fast file sharing from cli, using transfer.sh

## Machine Learning

*   [vectorflow (⭐1.3k)](https://github.com/Netflix/vectorflow) - Nexflix's opensource deep learning framework.
*   [bindbc-onnxruntime (⭐10)](https://github.com/lempiji/bindbc-onnxruntime) - bindbc bindings to Microsoft's cross-platform, high performance ML inferencing and training accelerator
*   [grain2 (⭐7)](https://github.com/ShigekiKarita/grain2) - Autograd and GPGPU library for dynamic neural networks in D
*   [tfd (⭐31)](https://github.com/ShigekiKarita/tfd) -  Tensorflow wrapper for D

## Parallel computing

*   [DCompute (⭐134)](https://github.com/libmir/dcompute) - [GPGPU with Native D for OpenCL and CUDA](https://dlang.org/blog/2017/07/17/dcompute-gpgpu-with-native-d-for-opencl-and-cuda/)
*   [DerelictCUDA (⭐17)](https://github.com/DerelictOrg/DerelictCUDA) - Dynamic bindings to the CUDA library for the D Programming Language.
*   [DerelictCL (⭐7)](https://github.com/DerelictOrg/DerelictCL) - Dynamic bindings to the OpenCL library for the D Programming Language.

## Scientific

*Scientific programming*

*   [scid (⭐90)](https://github.com/DlangScience/scid) -  Scientific library for the D programming language
*   [dstats (⭐25)](https://github.com/DlangScience/dstats) -  A statistics library for D.
*   [mir (⭐210)](https://github.com/libmir/mir) -  Sandbox for some mir packages: sparse tensors, Hoffman and others.
*   [mir-algorithm (⭐210)](https://github.com/libmir/mir) - N-dimensional arrays (matrixes, tensors), algorithms, general purpose library.
*   [mir-random (⭐32)](https://github.com/libmir/mir-random) -  Advanced Random Number Generators.
*   [decimals](https://github.com/rumbu13/decimal) - Decimal library for D.

### Language Processing

*   [bindbc-mecab (⭐1)](https://github.com/lempiji/bindbc-mecab) - bindbc MeCab binding (Part-of-Speech and Morphological Analyzer for Japanese)

## Text Processing

*   [hunt-markdown (⭐12)](https://github.com/huntlabs/hunt-markdown) - A markdown parsing and rendering library for D programming language. Support commonMark.
*   [eBay's TSV utilities (⭐1.4k)](https://github.com/eBay/tsv-utils/) - Filtering, statistics, sampling, joins and other operations on TSV files. Very fast, especially good for large datasets.

## Logging

*Print with care.*

*   [std.experimenatal.logger](https://dlang.org/phobos/std_experimental_logger.html) - Phobos's upcoming standard logging facility
*   [dlogg (⭐14)](https://github.com/NCrashed/dlogg) - Logging for concurrent applications and daemons with lazy and delayed logging, [logrotate](https://linux.die.net/man/8/logrotate) support.

## Configuration

*Parsing configuration files*

*   [sdlang (⭐120)](https://github.com/Abscissa/SDLang-D) - An SDL (Simple Declarative Language) library for D.
*   [D:YAML (⭐118)](https://github.com/dlang-community/D-YAML) - YAML parser and emitter for the D programming language.
*   [inifile-D (⭐22)](https://github.com/burner/inifiled) - A compile time ini file parser and writter generator for D

## Blog Engine

*Hosting blogs yourself*

*   [mood (⭐43)](https://github.com/mihails-strasuns/mood) - simple vibe.d based blog engine

## Dependency Injection

*Apply inversion of control*

*   [Poodinis (⭐70)](https://github.com/mbierlee/poodinis) - A dependency injection framework for D with support for autowiring.

## Other Awesome Lists

Other amazingly awesome lists can be found in the [awesome-awesome (⭐2.8k)](https://github.com/emijrp/awesome-awesome) and  [awesome-awesomeness (⭐32k)](https://github.com/bayandin/awesome-awesomeness) projects.

