# Awesome Crystal Overview

:gem: A collection of awesome Crystal libraries, tools, frameworks and software

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/veelenga/awesome-crystal/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 veelenga/awesome-crystal](https://github.com/veelenga/awesome-crystal) · ⭐ 3.2K · 🏷️ Programming Languages

[ [Daily](/content/veelenga/awesome-crystal/README.md) / [Weekly](/content/veelenga/awesome-crystal/week/README.md) / Overview ]

---

[![SWUbanner](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner-direct.svg)](https://github.com/vshymanskyy/StandWithUkraine/blob/main/docs/README.md)

<p align="center"><img src="https://github.com/veelenga/awesome-crystal/raw/master/logo/logotype_horizontal.jpg" alt="awesome-crystal"></p>

# Awesome Crystal

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Crystal code and resources. Inspired by [awesome (⭐266k)](https://github.com/sindresorhus/awesome) and [awesome-awesomeness (⭐30k)](https://github.com/bayandin/awesome-awesomeness).
The goal is to have projects mostly stable and useful for the community.

Search [Crystal Shards](https://crystalshards.org) or follow announcements [Crystal \[ANN\]](https://crystal-ann.com) for more.

Contributions are welcome. Please take a quick look at the [contribution guidelines (⭐3.2k)](https://github.com/veelenga/awesome-crystal/blob/master/.github/CONTRIBUTING.md) first.

*   [Awesome Crystal](#awesome-crystal)
    *   [Algorithms and Data structures](#algorithms-and-data-structures)
    *   [Blockchain](#blockchain)
    *   [C Bindings](#c-bindings)
    *   [Caching](#caching)
    *   [CLI Builders](#cli-builders)
    *   [CLI Utils](#cli-utils)
    *   [Code Analysis and Metrics](#code-analysis-and-metrics)
    *   [Compression](#compression)
    *   [Configuration](#configuration)
    *   [Converters](#converters)
    *   [Cryptography](#cryptography)
    *   [Data Formats](#data-formats)
    *   [Data Generators](#data-generators)
    *   [Database Drivers/Clients](#database-driversclients)
    *   [Database Tools](#database-tools)
    *   [Debugging](#debugging)
    *   [Dependency Injection](#dependency-injection)
    *   [Email](#email)
    *   [Environment Management](#environment-management)
    *   [Examples and funny stuff](#examples-and-funny-stuff)
    *   [Framework Components](#framework-components)
    *   [Game Development](#game-development)
    *   [GUI Development](#gui-development)
    *   [HTML Builders](#html-builders)
    *   [HTML/XML parsing](#htmlxml-parsing)
    *   [HTTP](#http)
    *   [Image Processing](#image-processing)
    *   [Implementations/Compilers](#implementationscompilers)
    *   [Internationalization](#internationalization)
    *   [Logging and monitoring](#logging-and-monitoring)
    *   [Machine Learning](#machine-learning)
    *   [Markdown/Text Processors](#markdowntext-processors)
    *   [Misc](#misc)
    *   [Network Protocols](#network-protocols)
    *   [Networking](#networking)
    *   [ORM/ODM Extensions](#ormodm-extensions)
    *   [Package Management](#package-management)
    *   [Processes and Threads](#processes-and-threads)
    *   [Project Generators](#project-generators)
    *   [Queues and Messaging](#queues-and-messaging)
    *   [Routing](#routing)
    *   [Scheduling](#scheduling)
    *   [Science and Data analysis](#science-and-data-analysis)
    *   [Search](#search)
    *   [Serverless Computing](#serverless-computing)
    *   [System](#system)
    *   [Task management](#task-management)
    *   [Template Engine](#template-engine)
    *   [Testing](#testing)
    *   [Third-party APIs](#third-party-apis)
    *   [Validation](#validation)
    *   [Web Frameworks](#web-frameworks)
*   [Community](#community)
    *   [Unofficial](#unofficial)
*   [Resources](#resources)
    *   [Official Documentation Translations](#official-documentation-translations)
*   [Services and Apps](#services-and-apps)
*   [Tools](#tools)
    *   [DevOps](#devops)
    *   [Editor Plugins](#editor-plugins)
    *   [LSP Language Server Protocol Implementations](#lsp-language-server-protocol-implementations)
    *   [Shell Plugins](#shell-plugins)

## Algorithms and Data structures

*   [bisect (⭐11)](https://github.com/spider-gazelle/bisect) - Inserting values into a sorted array
*   [blurhash.cr (⭐21)](https://github.com/Sija/blurhash.cr) - [BlurHash (⭐14k)](https://github.com/woltapp/blurhash) implementation
*   [crie (⭐12)](https://github.com/c910335/crie) - Compile-time Trie
*   [CrOTP (⭐62)](https://github.com/philnash/crotp) - HOTP and TOTP implementation for two factor authentication
*   [crystal-linked-list (⭐12)](https://github.com/abvdasker/crystal-linked-list) - Implementation of Linked List
*   [crystaledge (⭐27)](https://github.com/unn4m3d/crystaledge) - A pure Vector Math library
*   [crystalg (⭐35)](https://github.com/tobyapi/crystalg) - A Generic Algorithm Library
*   [crystalline (⭐127)](https://github.com/jtomschroeder/crystalline) - A collection of containers and algorithms
*   [csuuid (⭐15)](https://github.com/wyhaines/csuuid.cr) - A Chronologically Sortable UUID
*   [edits.cr (⭐17)](https://github.com/tcrouch/edits.cr) - Collection of edit distance algorithms
*   [fzy (⭐42)](https://github.com/hugopl/fzy) - A Crystal port of awesome Fzy project fuzzy finder algorithm
*   [Goban (⭐19)](https://github.com/soya-daizu/goban) - A fast and efficient QR Code implementation
*   [graphlb (⭐19)](https://github.com/mettuaditya/graphlb) - Collection of graph datastructure and algorithms
*   [haversine (⭐15)](https://github.com/geocrystal/haversine) - An Implementation of the Haversine formula
*   [kd\_tree (⭐16)](https://github.com/geocrystal/kd_tree) - An implementation of "K-Dimensional Tree" and "N-Nearest Neighbors"
*   [ksuid.cr (⭐15)](https://github.com/Sija/ksuid.cr) - K-Sortable Globally Unique IDs
*   [markov (⭐21)](https://github.com/mccallofthewild/markov) - Build Markov Chains and run Markov Processes
*   [multiset.cr (⭐4)](https://github.com/tcrouch/multiset.cr) - Implementation of a multiset
*   [qr-code (⭐17)](https://github.com/spider-gazelle/qr-code) - QR Code generator
*   [radix (⭐101)](https://github.com/luislavena/radix) - Radix Tree implementation
*   [s2\_cells (⭐0)](https://github.com/spider-gazelle/s2_cells) - [S2 Geometry](https://s2geometry.io/devguide/s2cell_hierarchy.html) for spatial indexing
*   [secure-remote-password (⭐4)](https://github.com/spider-gazelle/secure-remote-password) - SRP-6a protocol for authentication over an insecure network
*   [splay\_tree\_map (⭐14)](https://github.com/wyhaines/splay_tree_map.cr) - Splay Tree implementation that conforms to the Hash ducktype

## Blockchain

*   [Axentro (⭐196)](https://github.com/Axentro/Axentro) - A custom blockchain platform
*   [Cocol (⭐19)](https://github.com/cocol-project/cocol) - A minimal blockchain testbed
*   [secp256k1.cr (⭐47)](https://github.com/q9f/secp256k1.cr) - Elliptic curve used in the public-private-key cryptography

## C bindings

*   [augeas.cr (⭐7)](https://github.com/fernandes/augeas.cr) - Bindings for [Augeas](https://augeas.net/)
*   [clang.cr (⭐44)](https://github.com/crystal-lang/clang.cr) - Libclang bindings
*   [crt.cr (⭐28)](https://github.com/maiha/crt.cr) - Bindings for libncursesw and crt
*   [crystal-gsl (⭐2)](https://github.com/konovod/crystal-gsl) - Bindings for [GNU Scientific Library](https://www.gnu.org/software/gsl/)
*   [crystal-hunspell (⭐6)](https://github.com/mamantoha/crystal-hunspell) - Bindings for [Hunspell](https://hunspell.github.io/)
*   [duktape.cr (⭐136)](https://github.com/jessedoyle/duktape.cr) - Bindings for the [Duktape (⭐5.6k)](https://github.com/svaarala/duktape) javascript engine
*   [fftw.cr (⭐11)](https://github.com/firejox/fftw.cr) - Bindings for [FFTW](https://fftw.org/) library
*   [gphoto2.cr (⭐15)](https://github.com/Sija/gphoto2.cr) - Bindings for the [libgphoto2](http://www.gphoto.org/) library
*   [icu.cr (⭐11)](https://github.com/olbat/icu.cr) - Bindings for the [ICU](http://site.icu-project.org/) library
*   [libnotify.cr (⭐25)](https://github.com/splattael/libnotify.cr) - Bindings for Libnotify
*   [nlopt.cr (⭐3)](https://github.com/konovod/nlopt.cr) - Bindings for [NLOpt](https://nlopt.readthedocs.io/en/latest/)
*   [pcap.cr (⭐24)](https://github.com/maiha/pcap.cr) - Bindings for libpcap
*   [pledge.cr (⭐8)](https://github.com/chris-huxtable/pledge.cr) - Bindings for OpenBSD's `pledge(2)`
*   [ssh2.cr (⭐37)](https://github.com/spider-gazelle/ssh2.cr) - Bindings for libssh2 library
*   [syslog.cr (⭐10)](https://github.com/chris-huxtable/syslog.cr) - Bindings for `syslog`
*   [wasmer-crystal (⭐87)](https://github.com/naqvis/wasmer-crystal) - Bindings for the `wasmer` WebAssembly runtime
*   [win32cr (⭐6)](https://github.com/mjblack/win32cr) - Bindings for Win32 API
*   [x\_do.cr (⭐19)](https://github.com/woodruffw/x_do.cr) - Bindings for libxdo ([`xdotool`](https://github.com/jordansissel/xdotool))

## Caching

*   [crystal-memcached (⭐34)](https://github.com/comandeo/crystal-memcached) - Implementation of a memcached client

## CLI Builders

*   [admiral (⭐132)](https://github.com/jwaldrip/admiral.cr) - A robust DSL for writing command line interfaces
*   [Athena Console (⭐11)](https://github.com/athena-framework/console) - Allows for the creation of CLI based commands
*   [clicr (⭐29)](https://github.com/j8r/clicr) -  A simple declarative command line interface builder
*   [clim (⭐119)](https://github.com/at-grandpa/clim) - Slim command line interface builder
*   [Cling (⭐13)](https://github.com/devnote-dev/cling) - A modular, non-macro-based command line interface library
*   [commander (⭐125)](https://github.com/mrrooijen/commander) - Command-line interface builder
*   [Keimeno (⭐15)](https://github.com/robacarp/keimeno) -  A lightweight text user interface library in Crystal
*   [OptionParser](https://crystal-lang.org/api/OptionParser.html) - command-line options processing (Crystal stdlib)
*   [Phreak (⭐33)](https://github.com/shinzlet/phreak) - A highly flexible Crystal CLI builder in the style of OptionParser

## CLI Utils

*   [climate (⭐14)](https://github.com/Sija/climate.cr) - Tiny tool to make your CLI output 🌈  coloured
*   [coin (⭐7)](https://github.com/caian-org/coin) - Command-line application that performs currency conversion via the [Fixer API](https://fixer.io)
*   [cride (⭐47)](https://github.com/j8r/cride) - A light CLI text editor/IDE
*   [git-repository (⭐1)](https://github.com/place-labs/git-repository) - A git cli wrapper querying and cloning remote repositories with minimal data transfer
*   [hetzner-k3s (⭐1k)](https://github.com/vitobotta/hetzner-k3s) - A CLI tool to quickly create and manage Kubernetes clusters in Hetzner Cloud
*   [lff (⭐16)](https://github.com/mkdika/lff-cr) - Simple and straightforward large files finder utility in command line
*   [meet (⭐36)](https://github.com/ryanprior/meet) - Start a jitsi meeting quickly from the comfort of your command line
*   [oq (⭐184)](https://github.com/Blacksmoke16/oq) - A performant, and portable jq wrapper to facilitate the consumption and output of formats other than JSON; using [jq (⭐26k)](https://github.com/stedolan/jq) filters to transform the data
*   [progress\_bar.cr (⭐15)](https://github.com/TPei/progress_bar.cr) - A simple and customizable progress bar
*   [tablo (⭐26)](https://github.com/hutou/tablo) - A flexible terminal table generator
*   [tallboy (⭐52)](https://github.com/epoch/tallboy) - Generate ASCII character tables with support for spanning cells over multiple columns

## Code Analysis and Metrics

*   [ameba (⭐475)](https://github.com/crystal-ameba/ameba) - A static code analysis tool
*   [linguist.cr (⭐7)](https://github.com/microgit-com/linguist.cr) - Using multiple ways to find programming language used in files, based on Github's Linguist

## Compression

*   [Crystar (⭐38)](https://github.com/naqvis/crystar) - Readers and writers of Tar archive format
*   [Gzip](https://crystal-lang.org/api/Compress/Gzip.html) - readers and writers of gzip format (Crystal stdlib)
*   [polylines.cr (⭐9)](https://github.com/BuonOmo/polylines.cr) — compression of series of coordinates
*   [snappy (⭐17)](https://github.com/naqvis/snappy) -  Snappy compression format reader/writer for Crystal
*   [Zip](https://crystal-lang.org/api/Compress/Zip.html) - readers and writers of zip format (Crystal stdlib)
*   [Zlib](https://crystal-lang.org/api/Compress/Zlib.html) - readers and writers of zlib format (Crystal stdlib)
*   [zstd.cr (⭐38)](https://github.com/didactic-drunk/zstd.cr) - Bindings for [Zstandard (⭐21k)](https://github.com/facebook/zstd) compression library

## Configuration

*   [cr-dotenv (⭐94)](https://github.com/gdotdesign/cr-dotenv) - Loads .env file
*   [Envy (⭐6)](https://github.com/grottopress/envy) - Load environment variables from YAML
*   [envyable (⭐5)](https://github.com/philnash/envyable.cr) -  A simple YAML to ENV config loader
*   [habitat (⭐80)](https://github.com/luckyframework/habitat) - Type safe configuration for your classes and modules
*   [totem (⭐63)](https://github.com/icyleaf/totem) - Load and parse a configuration in JSON, YAML, dotenv formats

## Converters

*   [base62.cr (⭐9)](https://github.com/Sija/base62.cr) - Base62 encoder/decoder, well suited for url-shortening
*   [crunits (⭐6)](https://github.com/spider-gazelle/crunits) - Tool for converting units of measure (miles to kilometers, celsius to fahrenheit etc)
*   [money (⭐30)](https://github.com/crystal-money/money) - Handling money and currency conversion with ease (almost complete port of [RubyMoney (⭐2.6k)](https://github.com/RubyMoney/money))
*   [sass.cr (⭐34)](https://github.com/straight-shoota/sass.cr) - Compile SASS/SCSS to CSS ([libsass (⭐4.3k)](https://github.com/sass/libsass/) binding)

## Cryptography

*   [cmac (⭐2)](https://github.com/spider-gazelle/cmac) - Crystal implementation of Cipher-based Message Authentication Code (CMAC)
*   [ed25519 (⭐7)](https://github.com/spider-gazelle/ed25519) - the Ed25519 elliptic curve public-key signature system
    described in \[RFC 8032]
*   [monocypher.cr (⭐17)](https://github.com/konovod/monocypher.cr) - Crystal wrapper for the Monocypher crypto library
*   [sodium.cr (⭐46)](https://github.com/didactic-drunk/sodium.cr) - Crystal wrapper for the libsodium crypto API

## Data Formats

*   [BinData (⭐42)](https://github.com/spider-gazelle/bindata) - Binary data parser helper with an [ASN.1](https://en.wikipedia.org/wiki/Abstract_Syntax_Notation_One) parser
*   [config.cr (⭐14)](https://github.com/chris-huxtable/config.cr) - Easy to use configuration format parser
*   [crinder (⭐28)](https://github.com/c910335/crinder) - Class based json renderer
*   [Crystalizer (⭐39)](https://github.com/j8r/crystalizer) - (De)serialize any Crystal object; supporting JSON, YAML, and Byte formats out of the box
*   [CSV](https://crystal-lang.org/api/CSV.html) - parsing and generating for comma-separated values (Crystal stdlib)
*   [front\_matter.cr (⭐11)](https://github.com/chris-huxtable/front_matter.cr) - Separates a files front matter from its content
*   [geoip2.cr (⭐15)](https://github.com/delef/geoip2.cr) - GeoIP2 reader
*   [HAR (⭐22)](https://github.com/NeuraLegion/har) - HAR (HTTP Archive) parser
*   [INI](https://crystal-lang.org/api/INI.html) - INI file parser (Crystal stdlib)
*   [JSON](https://crystal-lang.org/api/JSON.html) - parsing and generating JSON documents (Crystal stdlib)
*   [json-schema (⭐8)](https://github.com/spider-gazelle/json-schema) - convert JSON serializable classes into a [JSON Schema](https://json-schema.org/) representation
*   [JSON::OnSteroids (⭐23)](https://github.com/anykeyh/json_on_steroids) - handle and mutate JSON document easily
*   [maxminddb.cr (⭐23)](https://github.com/delef/maxminddb.cr) - MaxMindDB reader
*   [toml.cr (⭐56)](https://github.com/crystal-community/toml.cr) - TOML parser
*   [XML](https://crystal-lang.org/api/XML.html) - parsing and generating XML documents (Crystal stdlib)
*   [YAML](https://crystal-lang.org/api/YAML.html) - parsing and generating YAML documents (Crystal stdlib)

## Data Generators

*   [faker (⭐141)](https://github.com/askn/faker) - A library for generating fake data
*   [hashids.cr (⭐52)](https://github.com/splattael/hashids.cr) - A library to generate YouTube-like ids from one or many numbers
*   [prime (⭐1)](https://github.com/wontruefree/prime) - A prime number generator

## Database Drivers/Clients

*   [couchdb.cr (⭐12)](https://github.com/TechMagister/couchdb.cr) - CouchDB client
*   [cryomongo (⭐62)](https://github.com/elbywan/cryomongo) - MongoDB driver
*   [crystal-db (⭐282)](https://github.com/crystal-lang/crystal-db) - Common db api
*   [crystal-ldap (⭐14)](https://github.com/spider-gazelle/crystal-ldap) - LDAP client
*   [crystal-mysql (⭐105)](https://github.com/crystal-lang/crystal-mysql) - MySQL connector for Crystal
*   [crystal-pg (⭐445)](https://github.com/will/crystal-pg) - A Postgres driver
*   [crystal-redis (⭐380)](https://github.com/stefanwille/crystal-redis) - Full featured Redis client
*   [crystal-rethinkdb (⭐21)](https://github.com/kingsleyh/crystal-rethinkdb) - Driver for RethinkDB / RebirthDB
*   [crystal-sqlite3 (⭐124)](https://github.com/crystal-lang/crystal-sqlite3) - SQLite3 bindings
*   [leveldb (⭐39)](https://github.com/crystal-community/leveldb) - Crystal bindings for LevelDB
*   [rocksdb.cr (⭐34)](https://github.com/maiha/rocksdb.cr) - RocksDB client
*   [surrealdb.cr (⭐5)](https://github.com/yorci/surrealdb.cr) - Unoffical SurrealDB HTTP & Websocket Client

## Database Tools

*   [migrate (⭐31)](https://github.com/vladfaust/migrate.cr) - A simpler database migration tool with transactions
*   [queryit (⭐23)](https://github.com/hugopl/queryit) - A setupless terminal based SQL query runner

## Debugging

*   [backtracer.cr (⭐15)](https://github.com/Sija/backtracer.cr) - Shard aiming to assist with parsing backtraces into a structured form
*   [debug.cr (⭐92)](https://github.com/Sija/debug.cr) - `debug!(…)` macro for `pp`-style debugging

## Dependency Injection

*   [Athena Dependency Injection (⭐8)](https://github.com/athena-framework/dependency-injection) - Robust dependency injection service container framework
*   [Crystal-DI (⭐31)](https://github.com/funk-yourself/crystal-di) - Lightweight DI Container
*   [HardWire (⭐19)](https://github.com/jerometwell/hardwire) - A compile-time non-intrusive dependency injection system
*   [syringe (⭐6)](https://github.com/Bonemind/syringe) - A simple and basic dependency injection shard for crystal

## Email

*   [carbon (⭐82)](https://github.com/luckyframework/carbon) - Fun, testable, and adapter-based email library
*   [crystal-email (⭐109)](https://github.com/arcage/crystal-email) - Simple e-mail sending library
*   [CrystalEmail](https://git.sceptique.eu/Sceptique/CrystalEmail) - A RFC compliant Email validator
*   [sendgrid.cr (⭐15)](https://github.com/dlanileonardo/sendgrid.cr) - Simple Sendgrid Client

## Environment Management

*   [asdf-crystal (⭐71)](https://github.com/marciogm/asdf-crystal) - Plugin for asdf version manager
*   [crenv (⭐235)](https://github.com/crenv/crenv) - Crystal version manager
*   [rcm.cr (⭐45)](https://github.com/maiha/rcm.cr) - Redis Cluster Manager

## Examples and funny stuff

*   [blackjack-cr (⭐7)](https://github.com/gdonald/blackjack-cr) - Console Blackjack
*   [crystal-patterns (⭐289)](https://github.com/crystal-community/crystal-patterns) - Examples of GOF patters
*   [crystalworld (⭐43)](https://github.com/vladfaust/crystalworld) - [realworld.io](https://realworld.io) back-end API implementation
*   [exercism-crystal (⭐70)](https://github.com/exercism/crystal) - Exercism exercises
*   [try.cr (⭐26)](https://github.com/maiha/try.cr) - Try monad

## Framework Components

*   [Athena Event Dispatcher (⭐13)](https://github.com/athena-framework/event-dispatcher) - A Mediator and Observer pattern event library
*   [Athena Negotiation (⭐3)](https://github.com/athena-framework/negotiation) - Framework agnostic content negotiation library
*   [device\_detector (⭐21)](https://github.com/creadone/device_detector) - Shard for detect device by user agent string
*   [Exception Page (⭐64)](https://github.com/crystal-loot/exception_page) - An exceptional exception page for Crystal web libraries and frameworks
*   [graphql (⭐132)](https://github.com/graphql-crystal/graphql) - Type-safe [GraphQL](http://graphql.org) server implementation
*   [graphql-crystal (⭐217)](https://github.com/ziprandom/graphql-crystal) - [GraphQL](http://graphql.org) implementation
*   [kemal-session (⭐49)](https://github.com/kemalcr/kemal-session) - Session handler for Kemal
*   [mochi (⭐22)](https://github.com/awcrotwell/mochi) - Authentication shard inspired by Devise supporting: Authenticable, Confirmable, Invitable & more
*   [motion.cr (⭐53)](https://github.com/awcrotwell/motion.cr) - Object oriented frontend library for Amber
*   [multi-auth (⭐111)](https://github.com/msa7/multi_auth) - Standardized multi-provider OAuth2 authentication (inspired by omniauth)
*   [praetorian (⭐57)](https://github.com/ilanusse/praetorian) - Minimalist authorization library inspired by Pundit
*   [Shield (⭐52)](https://github.com/grottopress/shield) - Comprehensive security for *Lucky* framework
*   [shrine.cr (⭐74)](https://github.com/jetrockets/shrine.cr) - File Attachment toolkit for Crystal applications. Heavily inspired by Shrine for Ruby
*   [tourmaline (⭐145)](https://github.com/protoncr/tourmaline) - Telegram bot framework with an API loosely based on [telegraf.js](https://telegraf.js.org/)

## Game Development

*   [CrSFML (⭐333)](https://github.com/oprypin/crsfml) - Bindings to [SFML](https://www.sfml-dev.org/) multimedia/game library
*   [crystal-chipmunk (⭐40)](https://github.com/oprypin/crystal-chipmunk) - Bindings to [Chipmunk](http://chipmunk-physics.net/), a fast and lightweight 2D game physics library
*   [crystal-imgui-sfml (⭐15)](https://github.com/oprypin/crystal-imgui-sfml) - Bindings to integrate [Dear ImGui (⭐50k)](https://github.com/ocornut/imgui) into an [SFML](https://www.sfml-dev.org/) project
*   [entitas.cr (⭐36)](https://github.com/spoved/entitas.cr) - A Entity Component System Framework for Crystal
*   [MyECS (⭐14)](https://github.com/konovod/myecs) - A Sparse Entity Component System Framework for Crystal
*   [SDL-Crystal-Bindings (⭐3)](https://github.com/Hadeweka/SDL-Crystal-Bindings) - Direct (unsafe) bindings to [SDL2](https://www.libsdl.org/), intended for writing own game libraries

## GUI Development

*   [crystal-imgui (⭐60)](https://github.com/oprypin/crystal-imgui) - Bindings to [Dear ImGui (⭐50k)](https://github.com/ocornut/imgui), an immediate-mode graphical UI library
*   [GTK4.cr (⭐87)](https://github.com/hugopl/gtk4.cr) - Bindings for [GTK4](https://docs.gtk.org/gtk4/overview.html) with Crystalized API
*   [Iu (⭐63)](https://github.com/grkek/iu) - UI framework based on the [Fusion/libui.cr (⭐176)](https://github.com/Fusion/libui.cr) library, with custom elements and modified bindings from [hedron-crystal/hedron (⭐83)](https://github.com/hedron-crystal/hedron)
*   [Ultimate GTK4 Crystal Guide](https://ultimate-gtk4-crystal-guide.geopjr.dev/) - Learn how to create premium GTK4 apps in Crystal

## HTML Builders

*   [blueprint (⭐33)](https://github.com/gunbolt/blueprint) - Write reusable and testable HTML templates in plain Crystal
*   [form\_builder.cr (⭐32)](https://github.com/westonganger/form_builder.cr) - Dead simple HTML form builder for Crystal with built-in support for many popular UI libraries such as Bootstrap
*   [Water (⭐26)](https://github.com/shootingfly/water) - A library for writing HTML in plain Crystal

## HTML/XML Parsing

*   [docx\_cr\_converter (⭐5)](https://github.com/aristotelesbr/docx_cr_converter) - parse DOCX Word
*   [myhtml (⭐151)](https://github.com/kostya/myhtml) - Fast HTML5 Parser that includes CSS selectors

## HTTP

*   [Cable (⭐113)](https://github.com/cable-cr/cable) - An ActionCable "port" to Crystal, framework agnostic, 100% compatible with the ActionCable JS Client
*   [cossack (⭐104)](https://github.com/crystal-community/cossack) - Simple flexible HTTP client
*   [crest (⭐222)](https://github.com/mamantoha/crest) - Simple HTTP and REST client, inspired by the Ruby's RestClient gem
*   [crul (⭐112)](https://github.com/porras/crul) - Command line HTTP client
*   [digest-auth (⭐4)](https://github.com/spider-gazelle/digest-auth) - Digest authentication
*   [halite (⭐172)](https://github.com/icyleaf/halite) - Crystal HTTP Requests with a chainable REST API, built-in sessions and loggers
*   [http-multiserver.cr (⭐23)](https://github.com/vladfaust/http-multiserver.cr) - Mounting multiple servers via routes (a.k.a. URL mapping)
*   [http-params-serializable (⭐19)](https://github.com/vladfaust/http-params-serializable) - HTTP params (de)serialization, applicable to URL queries and URL-encoded forms
*   [http-protection (⭐72)](https://github.com/rogeriozambon/http-protection) - Protection against typical web attacks
*   [http2 (⭐92)](https://github.com/ysbaddaden/http2) - HTTP/2 Protocol Implementation
*   [HTTP::Client](https://crystal-lang.org/api/HTTP/Client.html) - HTTP client (Crystal stdlib)
*   [HTTP::Server](https://crystal-lang.org/api/HTTP/Server.html) - HTTP server (Crystal stdlib)
*   [HTTP::WebSocket](https://crystal-lang.org/api/HTTP/WebSocket.html) - HTTP WebSocket client (Crystal stdlib)
*   [link-header (⭐1)](https://github.com/spider-gazelle/link-header) - HTTP Link Header Parser
*   [ntlm (⭐4)](https://github.com/spider-gazelle/ntlm) - NTLM authentication
*   [proxy-fetcher.cr (⭐10)](https://github.com/nbulaj/proxy-fetcher.cr) - Proxy lists fetching & validating library
*   [sse.cr (⭐20)](https://github.com/y2k2mt/sse.cr) - [Server-Sent Events](https://www.w3.org/TR/2009/WD-eventsource-20090421) client

## Image processing

*   [celestine (⭐86)](https://github.com/celestinecr/celestine) - Create SVG images using a DSL
*   [ffmpeg (⭐16)](https://github.com/spider-gazelle/ffmpeg) - FFmpeg bindings that works with StumpyPNG to extract frames
*   [Pluto (⭐59)](https://github.com/phenopolis/pluto) - A fast and convenient image processing library
*   [stumpy\_png (⭐102)](https://github.com/stumpycr/stumpy_png) - Read and write PNG images

## Implementations/Compilers

*   [charly](https://github.com/charly-lang) - Charly Programming Language
*   [cltk (⭐73)](https://github.com/ziprandom/cltk) - A crystal port of the Ruby Language Toolkit
*   [crisp (⭐43)](https://github.com/rhysd/Crisp) - Lisp dialect implemented with Crystal
*   [LinCAS-lang](https://github.com/LinCAS-lang) - A programming language for scientific computation
*   [mint-lang (⭐3.9k)](https://github.com/mint-lang/mint) - A refreshing programming language for the front-end web
*   [myst-lang](https://github.com/myst-lang/) - A practical, dynamic language designed to be written and understood as easily and efficiently as possible
*   [novika (⭐12)](https://github.com/novika-lang/novika) - A free-form, moldable, interpreted programming language
*   [runic-lang](https://github.com/runic-lang) - In-design toy language

## Internationalization

*   [crystal-i18n (⭐18)](https://github.com/crystal-i18n/i18n) - An internationalization library inspired by Ruby-I18n
*   [i18n.cr (⭐24)](https://github.com/vladfaust/i18n.cr) - Internationalization shard
*   [Lens (⭐16)](https://github.com/syeopite/lens) - A multiformat internationalization (i18n) shard for Crystal. Supports Gettext, Ruby YAML, etc.
*   [Rosetta (⭐35)](https://github.com/wout/rosetta) - A blazing fast internationalization (i18n) library with compile-time key lookup supporting YAML and JSON formats

## Logging and monitoring

*   [crafana (⭐21)](https://github.com/spoved/crafana.cr) - A [Grafana](https://grafana.com/) library to help autogenerate dashboards
*   [fiber\_metrics.cr (⭐7)](https://github.com/didactic-drunk/fiber_metrics.cr) - Track run time, wait time, or memory allocations per `Fiber`, method or block
*   [Log](https://crystal-lang.org/api/Log.html) - logging utility (Crystal stdlib)
*   [statsd.cr (⭐32)](https://github.com/miketheman/statsd.cr) - [Statsd (⭐17k)](https://github.com/etsy/statsd) client library

## Machine Learning

*   [ai4cr (⭐27)](https://github.com/drhuffman12/ai4cr) - Artificial Intelligence (based on [https://github.com/SergioFierens/ai4r (⭐712)](https://github.com/SergioFierens/ai4r))
*   [Cadmium (⭐197)](https://github.com/cadmiumcr/cadmium) - NLP library based heavily on [natural (⭐10k)](https://github.com/NaturalNode/natural)
*   [crystal-fann (⭐79)](https://github.com/NeuraLegion/crystal-fann) - FANN (Fast Artifical Neural Network) binding
*   [mxnet.cr (⭐22)](https://github.com/toddsundsted/mxnet.cr) - Bindings for [MXNet](https://mxnet.incubator.apache.org/)
*   [shainet (⭐176)](https://github.com/NeuraLegion/shainet) - SHAInet (Neural Network in pure crystal)

## Markdown/Text Processors

*   [markd (⭐105)](https://github.com/icyleaf/markd) - Yet another markdown parser built for speed, Compliant to CommonMark specification

## Misc

*   [aasm.cr (⭐50)](https://github.com/veelenga/aasm.cr) - Easy to use finite state machine for Crystal classes
*   [any\_hash.cr (⭐32)](https://github.com/Sija/any_hash.cr) - Recursive Hash with better JSON::Any included
*   [anyolite (⭐144)](https://github.com/Anyolite/anyolite) - Full mruby interpreter with simple bindings, allowing for easy scripting support in projects
*   [burocracia.cr (⭐21)](https://github.com/vinibrsl/burocracia.cr) - burocracia.cr the dependecyless shard to validate, generate and format Brazilian burocracias such as CPF, CNPJ and CEP
*   [callbacks (⭐12)](https://github.com/vladfaust/callbacks.cr) - Expressive callbacks module
*   [circuit\_breaker (⭐26)](https://github.com/TPei/circuit_breaker) - Implementation of the circuit breaker pattern
*   [CrSignals (⭐10)](https://github.com/firejox/CrSignals) - Signals/slots notification library
*   [crystal-binary\_parser (⭐18)](https://github.com/DanSnow/crystal-binary_parser) - Binary parser
*   [crystal-web-framework-stars (⭐66)](https://github.com/isaced/crystal-web-framework-stars) - Web frameworks for Crystal, most starred on Github
*   [crz (⭐90)](https://github.com/dhruvrajvanshi/crz) - Functional programming library
*   [defined (⭐16)](https://github.com/wyhaines/defined.cr) - macros for conditional compilation based on constant definitions, version requirements, or environment variable settings
*   [emoji.cr (⭐46)](https://github.com/veelenga/emoji.cr) - Emoji library
*   [gphoto2-web.cr (⭐6)](https://github.com/Sija/gphoto2-web.cr) - Web API for libgphoto2
*   [immutable (⭐200)](https://github.com/lucaong/immutable) - Implementation of thread-safe, persistent, immutable collections
*   [iterm2 (⭐5)](https://github.com/toddsundsted/iterm2) - Display images within the terminal using the ITerm2 Inline Images Protocol
*   [monads (⭐46)](https://github.com/alex-lairan/monads) - Monad implementation
*   [observable (⭐8)](https://github.com/TPei/observable) - Implementation of the observer pattern
*   [pinger (⭐10)](https://github.com/spider-gazelle/pinger) - Ping IP addresses and DNS entries without requiring sudo
*   [port\_midi (⭐5)](https://github.com/jimm/crystal_port_midi) - Crystal C bindings for the PortMIDI cross-platform MIDI I/O library
*   [retriable.cr (⭐37)](https://github.com/Sija/retriable.cr) - Simple DSL to retry failed code blocks
*   [serf-handler.cr (⭐1)](https://github.com/wyhaines/serf-handler.cr) - Framework for building Serf handlers, with a suite of useful builtin capabilities
*   [simple\_retry (⭐5)](https://github.com/spider-gazelle/simple_retry) - Simple tool for retrying failed code blocks
*   [sslscan.cr (⭐10)](https://github.com/NeuraLegion/sslscan.cr) - Crystal shard wrapping the rbsec/sslscan utility
*   [version\_tools (⭐8)](https://github.com/anicholson/crystal-version-tools) - Version-dependent behaviour, specified at compile-time
*   [wafalyzer (⭐33)](https://github.com/NeuraLegion/wafalyzer) - Web Application Firewall (WAF) Detector - shard + cli
*   [zaru\_crystal (⭐9)](https://github.com/szTheory/zaru_crystal) - Filename sanitization

## Network Protocols

*   [amqp-client.cr (⭐63)](https://github.com/cloudamqp/amqp-client.cr) - AMQP 0-9.1, a messaging protocol, implemented by eg. RabbitMQ
*   [connect-proxy (⭐5)](https://github.com/spider-gazelle/connect-proxy) - Connect method style of HTTP tunnelling / HTTP proxy
*   [cr-xmpp (⭐16)](https://github.com/naqvis/cr-xmpp) - XMPP/Jabber Library
*   [Crirc (⭐22)](https://github.com/Meoowww/Crirc) - IRC protocol implementation (Client, Server, Bots)
*   [crystal-bacnet (⭐0)](https://github.com/spider-gazelle/crystal-bacnet) - BACnet protocol implementation with BACnet/IP client
*   [crystal-dns](https://gitlab.com/jgillich/crystal-dns) - DNS protocol implementation and resolver
*   [crystal-json-socket (⭐13)](https://github.com/foi/crystal-json-socket) - JSON-socket client & server implementation. Inspired by and compatible with [node-json-socket (⭐154)](https://github.com/sebastianseilund/node-json-socket/) and [ruby-json-socket (⭐4)](https://github.com/foi/ruby-json-socket)
*   [crystal-mqtt (⭐17)](https://github.com/spider-gazelle/crystal-mqtt) - A MQTT client
*   [crystal-snmp (⭐16)](https://github.com/spider-gazelle/crystal-snmp) - An SNMP implementation with version 1, 2c and 3 support
*   [fast\_irc.cr (⭐19)](https://github.com/RX14/fast_irc.cr) - Fast IRC parser/generator
*   [jwt (⭐201)](https://github.com/crystal-community/jwt) - Implementation of JWT (JSON Web Token)
*   [mDNS (⭐7)](https://github.com/spider-gazelle/mdns) - DNS Service Discovery and multicast DNS
*   [mqtt-client.cr (⭐3)](https://github.com/84codes/mqtt-client.cr) - A fast and lightweight MQTT client
*   [msgpack-crystal (⭐129)](https://github.com/crystal-community/msgpack-crystal) - MessagePack library
*   [OAuth](https://crystal-lang.org/api/OAuth.html) - OAuth consumer (Crystal stdlib)
*   [OAuth2](https://crystal-lang.org/api/OAuth2.html) - OAuth2 client (Crystal stdlib)
*   [OpenSSL](https://crystal-lang.org/api/OpenSSL.html) - bindings to libssl (Crystal stdlib)
*   [simple\_rpc (⭐61)](https://github.com/kostya/simple_rpc) - RPC Server and Client for Crystal. Implements msgpack-rpc protocol
*   [stomp (⭐1)](https://github.com/spider-gazelle/stomp) - STOMP protocol
*   [telnet.cr (⭐10)](https://github.com/spider-gazelle/telnet.cr) - Telnet protocol
*   [transfer\_more](https://git.sceptique.eu/Sceptique/transfer_more) - Clone of transfer.sh to uploads files

## Networking

*   [ipaddress.cr (⭐42)](https://github.com/Sija/ipaddress.cr) - Library to handle IPv4 and IPv6 addresses
*   [mac-address (⭐2)](https://github.com/automatico/mac-address) - Library for working with MAC addresses

## ORM/ODM Extensions

*   [avram (⭐153)](https://github.com/luckyframework/avram) - A database wrapper for reading, writing, and migrating Postgres databases
*   [clear (⭐268)](https://github.com/anykeyh/clear) - ORM specialized to PostgreSQL only but with advanced features
*   [crecto (⭐341)](https://github.com/Crecto/crecto) - Database wrapper, based on Ecto
*   [granite (⭐283)](https://github.com/amberframework/granite) - ORM for Postgres, Mysql, Sqlite
*   [jennifer.cr (⭐403)](https://github.com/imdrasil/jennifer.cr) - Active Record pattern implementation with flexible query chainable builder and migration system
*   [rethinkdb-orm (⭐24)](https://github.com/spider-gazelle/rethinkdb-orm) - ORM for RethinkDB / RebirthDB

## Package Management

*   [shards (⭐743)](https://github.com/crystal-lang/shards) - Dependency manager for the Crystal

## Processes and Threads

*   [await\_async (⭐78)](https://github.com/anykeyh/await_async) - Add keywords await & async in Crystal Lang
*   [concurrent.cr (⭐45)](https://github.com/didactic-drunk/concurrent.cr) - Simplified concurrency using streams/pipelines, waitgroups, semaphores, smores and more
*   [neph (⭐199)](https://github.com/tbrand/neph) - A modern command line job processor that can execute jobs concurrently
*   [promise (⭐38)](https://github.com/spider-gazelle/promise) - A Promise implementation with type inference
*   [werk (⭐21)](https://github.com/marghidanu/werk) - Dead simple task runner with concurrent support, ideal for local CI

## Project Generators

*   [crystal\_lib (⭐138)](https://github.com/crystal-lang/crystal_lib) - Automatic binding generator for native libraries
*   [fez (⭐51)](https://github.com/jwoertink/fez) - A Kemal application generator
*   [libgen (⭐73)](https://github.com/olbat/libgen) - Automatic bindings generator configured using JSON/YAML files

## Queues and Messaging

*   [mosquito (⭐200)](https://github.com/mosquito-cr/mosquito/) - Redis backed periodic and ad hoc job processing
*   [NATS.io (⭐43)](https://github.com/nats-io/nats.cr) - NATS client
*   [sidekiq.cr (⭐759)](https://github.com/mperham/sidekiq.cr) - Simple, efficient job processing

## Routing

*   [orion (⭐122)](https://github.com/obsidian/orion) - A minimal, rails-esque routing library
*   [router.cr (⭐255)](https://github.com/tbrand/router.cr) - Minimum but powerful http router for HTTP::Server

## Scheduling

*   [crystime](https://gitlab.com/crystallabs/crystime) - Advanced time, calendar, schedule, and remind library
*   [schedule.cr (⭐71)](https://github.com/hugoabonizio/schedule.cr) - Run periodic tasks
*   [tasker (⭐45)](https://github.com/spider-gazelle/tasker) - A high precision scheduler including timezone aware cron jobs

## Science and Data analysis

*   [alea (⭐12)](https://github.com/nin93/alea) - Repeatable sampling, CDF and other utilities to work with probability distributions
*   [ishi (⭐46)](https://github.com/toddsundsted/ishi) - Graph plotting package with a small API and sensible defaults powered by gnuplot
*   [linalg (⭐45)](https://github.com/konovod/linalg) - Linear algebra library inspired by MATLAB and SciPy.linalg
*   [num.cr (⭐139)](https://github.com/crystal-data/num.cr) - Numerical computing library supporting N-Dimensional data
*   [predict.cr (⭐17)](https://github.com/RX14/predict.cr) - Satellite prediction library using the sgp4 model
*   [quartz (⭐15)](https://github.com/RomainFranceschini/quartz) - Modeling and simulation framework

## Search

*   [hermes (⭐37)](https://github.com/imdrasil/hermes.cr) - Data Mapper pattern implementation for ElastiSearch
*   [soegen (⭐20)](https://github.com/Ragmaanir/soegen) - Elasticsearch client for Crystal similar to the stretcher gem for ruby

## Serverless Computing

*   [crystal\_openfaas (⭐23)](https://github.com/TPei/crystal_openfaas/) - Template to enable crystal as first class citizens in OpenFaaS
*   [FaaStRuby](https://faastruby.io) - Serverless Software Development Platform for Ruby and Crystal
*   [secrets-env (⭐6)](https://github.com/spider-gazelle/secrets-env) - Extends ENV module to read values injected by docker / kubernetes secrets and other orchestration tools

## System

*   [baked\_file\_system (⭐170)](https://github.com/schovi/baked_file_system) - Virtual file system implementation
*   [hardware (⭐70)](https://github.com/crystal-community/hardware) - Get CPU, Memory and Network informations of the running OS and its processes

## Task management

*   [cake (⭐68)](https://github.com/axvm/cake) - Production-ready Make-like utility tool
*   [sam (⭐89)](https://github.com/imdrasil/sam.cr) - Another one Rake-like task manager with namespacing and arguments system

## Template Engine

*   [crinja (⭐113)](https://github.com/straight-shoota/crinja) - An implementation of the [Jinja2 template engine](http://jinja.pocoo.org/)
*   [crustache (⭐79)](https://github.com/MakeNowJust/crustache) - [{{Mustache}}](https://mustache.github.io) for Crystal
*   [ECR (Embedded Crystal)](https://crystal-lang.org/api/ECR.html) - compile time template language which uses plain crystal expressions (Crystal stdlib)
*   [Jbuilder (⭐45)](https://github.com/shootingfly/jbuilder) - Generate JSON objects with a Builder-style DSL, inspired by jbuilder
*   [Kilt (⭐148)](https://github.com/jeromegn/kilt) - Abstraction layer for template engines
*   [Slang (⭐232)](https://github.com/jeromegn/slang) - Lightweight, terse, templating language inspired by Ruby's Slim
*   [teeplate (⭐15)](https://github.com/mosop/teeplate) - A library for rendering multiple template files

## Testing

*   [Athena Spec (⭐2)](https://github.com/athena-framework/spec) - Common/helpful [Spec](https://crystal-lang.org/api/Spec.html) compliant testing utilities
*   [crotest (⭐26)](https://github.com/emancu/crotest) - A tiny and simple test framework
*   [crytic (⭐61)](https://github.com/hanneskaeufler/crytic) - Mutation testing framework
*   [hashr (⭐0)](https://github.com/crystal-china/hashr) - A tiny class makes test on JSON response easier
*   [LuckyFlow (⭐49)](https://github.com/luckyframework/lucky_flow) - Automated browser tests similar to Capybara
*   [mass-spec (⭐8)](https://github.com/c910335/mass-spec) - Web API testing library
*   [microtest (⭐30)](https://github.com/Ragmaanir/microtest) - Small opinionated testing library focusing on power asserts
*   [minitest.cr (⭐145)](https://github.com/ysbaddaden/minitest.cr) - Library for unit tests and assertions
*   [mocks.cr (⭐51)](https://github.com/waterlink/mocks.cr) - Mocking library for Crystal
*   [Spec](https://crystal-lang.org/api/Spec.html) - spec framework (Crystal stdlib)
*   [spectator](https://gitlab.com/arctic-fox/spectator) - Feature rich spec framework that uses the modern expect syntax
*   [timecop.cr (⭐19)](https://github.com/crystal-community/timecop.cr) - Library for mocking with `Time.now`. Inspired by the [timecop ruby gem (⭐3.3k)](https://github.com/travisjeffery/timecop)
*   [vcr (⭐56)](https://github.com/spoved/vcr.cr) - A HTTP capture and replay implementation for crystal
*   [webdriver\_pump (⭐4)](https://github.com/bwilczek/webdriver_pump) - Page Object library. Inspired by Ruby's [WatirPump (⭐16)](https://github.com/bwilczek/watir_pump)
*   [webmock.cr (⭐103)](https://github.com/manastech/webmock.cr) - Library for stubbing `HTTP::Client` requests

## Third-party APIs

*   [amazonite (⭐0)](https://github.com/rjnienaber/amazonite) - An unofficial SDK supporting popular AWS APIs
*   [aws-signer.cr (⭐12)](https://github.com/beanieboi/aws-signer.cr) - This library signs your HTTP requests using AWS v4
*   [awscr-s3 (⭐81)](https://github.com/taylorfinnell/awscr-s3) - AWS S3 interface
*   [awscr-signer (⭐21)](https://github.com/taylorfinnell/awscr-signer) - Sign HTTP::Request objects and generate presigned post forms
*   [crystal-consul (⭐18)](https://github.com/rogerwelin/crystal-consul) - Consul API client
*   [crystal-darksky (⭐8)](https://github.com/sb89/crystal-darksky) - Wrapper for the [Dark Sky](https://darksky.net) API
*   [crystal-swapi (⭐4)](https://github.com/sb89/crystal-swapi) - Star Wars API (SWAPI) wrapper
*   [crystal\_slack (⭐20)](https://github.com/manastech/crystal_slack) - A tool that parses Slack slash commands or send incoming web hooks
*   [GDAX (⭐7)](https://github.com/mccallofthewild/gdax) - GDAX REST and WebSocket API Wrapper with request signing
*   [gitlab.cr (⭐29)](https://github.com/icyleaf/gitlab.cr) - GitLab API wrapper
*   [google (⭐21)](https://github.com/PlaceOS/google) - Google API wrapper
*   [host\_meta (⭐3)](https://github.com/toddsundsted/host_meta) - A Web Host Metadata (<https://tools.ietf.org/html/rfc6415>) client
*   [kube-client.cr (⭐22)](https://github.com/spoved/kube-client.cr) - Kubernetes API Client
*   [mixpanel-crystal (⭐0)](https://github.com/petoem/mixpanel-crystal) - A library for sending events to Mixpanel
*   [mollie.cr (⭐16)](https://github.com/wout/mollie.cr) - [Mollie](https://www.mollie.com/en/) Payments API wrapper (Creditcard, PayPal, Apple Pay, Sofort, Klarna, ...)
*   [office365 (⭐9)](https://github.com/PlaceOS/office365) - Microsoft Graph API wrapper
*   [pinboard.cr (⭐6)](https://github.com/oz/pinboard.cr) - [Pinboard](https://pinboard.in) API
*   [raven.cr (⭐120)](https://github.com/sija/raven.cr) - Raven is a client for [Sentry (⭐35k)](https://github.com/getsentry/sentry)
*   [stripe.cr (⭐47)](https://github.com/confact/stripe.cr) - Stripe api wrapper
*   [tmdb.cr (⭐3)](https://github.com/mmacia/tmdb.cr) - The Movie DB (TMDb) api wrapper
*   [twitter-crystal (⭐83)](https://github.com/sferik/twitter-crystal) - A library to access the Twitter API
*   [web\_finger (⭐9)](https://github.com/toddsundsted/web_finger) - A WebFinger (<https://tools.ietf.org/html/rfc7033>) client
*   [ynab.cr (⭐4)](https://github.com/jaredsmithse/ynab.cr) - A library to interact with your YNAB data

## Validation

*   [accord (⭐24)](https://github.com/neovintage/accord) - Shareable validation library for Crystal Objects
*   [Athena Validator (⭐5)](https://github.com/athena-framework/validator) - Robust & flexible validation framework
*   [validations (⭐13)](https://github.com/vladfaust/validations.cr) - Validations mixin
*   [validator (⭐28)](https://github.com/Nicolab/crystal-validator) - Data check and validation

## Web Frameworks

*   [amber (⭐2.5k)](https://github.com/amberframework/amber) - Open source efficient and cohesive web application framework
*   [Athena (⭐186)](https://github.com/athena-framework/athena) - A web framework comprised of reusable, independent components
*   [grip (⭐259)](https://github.com/grip-framework/grip) - The microframework for writing powerful web applications
*   [kemal (⭐3.5k)](https://github.com/kemalcr/kemal) - Lightning Fast, Super Simple web framework. Inspired by Sinatra
*   [lucky (⭐2.5k)](https://github.com/luckyframework/lucky) - Catch bugs early, forget about most performance issues, and spend more time on code instead of debugging and writing tests
*   [marten (⭐328)](https://github.com/martenframework/marten) - A web framework that makes building web applications easy, productive, and fun
*   [runcobo (⭐46)](https://github.com/runcobo/runcobo) - An api framework with simple, intuitive and consistent DSL, using jbuilder to render json
*   [Shivneri (⭐22)](https://github.com/ujjwalguptaofficial/shivneri) - Component based MVC web framework for crystal targeting good code structures, modularity & performance
*   [spider-gazelle (⭐170)](https://github.com/spider-gazelle/spider-gazelle) - A Rails esque web framework with a focus on speed and extensibility

# Community

*   [Chicago Crystal Podcast](https://podcast.chicagocrystal.org)
*   [Chicago Crystal YouTube](https://www.youtube.com/channel/UCI1RvHPG6S9mw4eRoJfH2kA)
*   [Crystal Forum](https://forum.crystal-lang.org/)
*   [Crystal weekly newsletters](http://crystalweekly.com/)
*   [Gitter](https://gitter.im/crystal-lang/crystal)
*   [Google Group](https://groups.google.com/forum/?fromgroups#!forum/crystal-lang)
*   [IRC](http://irc.lc/freenode/crystal-lang) - #crystal-lang on Freenode
*   [Reddit](https://www.reddit.com/r/crystal_programming/)
*   [Stackoverflow](https://stackoverflow.com/tags/crystal-lang/info)

## Unofficial

*   [Chinese-speaking Telegram Group](https://t.me/crystal_cn) - 来吧！TG 中文圈的朋友们！
*   [Crystal Programming Discord Server](https://discord.gg/YS7YvQy) - Unofficial Discord server dedicated to the Crystal Programming Language
*   [Portuguese-speaking Telegram Group](https://t.me/crystalbrasil) - Bem vindos ao Crystal Brasil!
*   [Russian-speaking Telegram Group](https://t.me/crystal_ru) - Добро пожаловать, товарищ!

# Resources

*   [Crystal for Rubyists](http://www.crystalforrubyists.com/) - Free book to bootstrap your Crystal journey
*   [Crystal Shards for Ruby Gems (⭐19k)](https://github.com/crystal-lang/crystal/wiki/Crystal-Shards-for-Ruby-Gems) - A list of Ruby Gems and their Crystal Shards equivalents
*   [crystal-koans (⭐38)](https://github.com/ilmanzo/crystal-koans) - Learn Crystal by writing unit tests
*   [crystal-lang.org](https://crystal-lang.org) - Official language site
*   [devdocs.io](https://devdocs.io/crystal/) - API Documentation Browser with Crystal support
*   [Programming Crystal](https://pragprog.com/book/crystal/programming-crystal) - PragProg book to start your Crystal journey

## Official Documentation Translations

*   [br.crystal-lang.org](http://br.crystal-lang.org/) - Brazilian
*   [ja.crystal-lang.org](http://ja.crystal-lang.org/) - Japanese
*   [kr.crystal-lang.org](https://kr.crystal-lang.org/) - Korean
*   [ru.crystal-lang.org](http://ru.crystal-lang.org/) - Russian
*   [tw.crystal-lang.org](http://tw.crystal-lang.org/) - Chinese Traditional

# Services and Apps

*   [carc.in](https://carc.in/) - A web service that runs your code and displays the result
*   [Crank (⭐50)](https://github.com/arktisklada/crank) - A Procfile-based application manager (like Foreman)
*   [cry (⭐34)](https://github.com/elorest/cry) - Ability to execute crystal code in a fashion similar to Ruby's pry edit
*   [Crystal \[ANN\]](https://crystal-ann.com) - Announce new project, blog post, version update or any other Crystal work
*   [crystalshards.herokuapp.com](https://crystalshards.herokuapp.com/), [crystalshards.xyz](http://crystalshards.xyz/) - Web services that list all available Crystal shards
*   [Crystular](http://www.crystular.org) - Regular expression tester
*   [DeBot (⭐36)](https://github.com/jhass/DeBot) - IRC bot written in Crystal
*   [icr (⭐495)](https://github.com/crystal-community/icr) - Interactive console for Crystal (like IRB for Ruby)
*   [Invidious (⭐12k)](https://github.com/iv-org/invidious) - Invidious is an alternative front-end to YouTube
*   [mpngin (⭐31)](https://github.com/thewalkingtoast/mpngin) - A URL shortener with simple stats
*   [procodile (⭐5)](https://github.com/crystal-china/procodile_cr) - Run processes in the background (and foreground) on Mac & Linux from a Procfile (for production and/or development environments)
*   [quicktype](https://quicktype.io/) - Generate models and serializers from JSON, JSON Schema, GraphQL, and TypeScript
*   [shards.info](http://shards.info/) - Web service that lists all repositories on GitHub that have Crystal code in them. The sources are available on [GitHub (⭐35)](https://github.com/mamantoha/shards-info)

# Tools

*   [ast\_helper (⭐27)](https://github.com/bcardiff/crystal-ast-helper) - Helper tool to debug parser and formatter
*   [crystal-base (⭐2)](https://github.com/ruivieira/crystal-base) - CentOS base docker image for Crystal development
*   [crystal-dash-docset (⭐15)](https://github.com/Sija/crystal-dash-docset) - [Dash](https://kapeli.com/dash) docset generator
*   [port\_ruby\_to\_crystal (⭐8)](https://github.com/crystal-china/port_ruby_to_crystal) - A regex replace ruby script for port ruby code to crystal easier, reduce friction
*   [public\_suffix (⭐2)](https://github.com/toddsundsted/public_suffix) - A small library designed to make the Public Suffix List (<https://publicsuffix.org/>) easier to use

## DevOps

*   [ansible-crystal (⭐8)](https://github.com/CorbanR/ansible-crystal) - Ansible playbook for installing crystal
*   [DPPM (⭐110)](https://github.com/DFabric/dppm) - An easy, universal way to install and manage applications as packages (mostly Linux)

## Editor Plugins

*   Acme:
    *   [acmecrystal (⭐5)](https://github.com/ilanpillemer/acmecrystal) - Reformats crystal code in acme
*   Atom
    *   [crystal-tools](https://atom.io/packages/crystal-tools) - Enables built in tools in Crystal compiler
    *   [language-crystal-actual](https://atom.io/packages/language-crystal-actual) - Crystal language support in Atom
*   Emacs
    *   [crystal-mode](https://melpa.org/#/crystal-mode) - Crystal language support for Emacs ([crystal-lang-tools/emacs-crystal-mode (⭐45)](https://github.com/crystal-lang-tools/emacs-crystal-mode))
*   Geany
    *   [geany-crystal (⭐8)](https://github.com/crystal-lang-tools/geany-crystal) - Crystal support for the [Geany editor](https://www.geany.org/)
*   IntelliJ IDEA
    *   [intellij-crystal-lang (⭐30)](https://github.com/asedunov/intellij-crystal-lang) - Crystal support for the JetBrains IDEs
*   Lite-XL
    *   [lite-plugin-crystal (⭐5)](https://github.com/Tamnac/lite-plugin-crystal) - Crystal support for the [Lite-XL](https://lite-xl.com/en/) editor
*   Spacemacs
    *   [crystal-spacemacs-layer (⭐12)](https://github.com/juanedi/crystal-spacemacs-layer) - Spacemacs contribution layer for Crystal
*   Sublime
    *   [sublime-crystal (⭐82)](https://github.com/crystal-lang-tools/sublime-crystal) - Crystal syntax highlighting for sublime Text
*   TextMate
    *   [Crystal.tmbundle (⭐18)](https://github.com/crystal-lang-tools/Crystal.tmbundle) - Crystal syntax highlighting, compile, format command, snippets
*   Vim
    *   [vim-crystal (⭐403)](https://github.com/vim-crystal/vim-crystal) - Vim filetype support for Crystal
    *   [vim-slang (⭐12)](https://github.com/elorest/vim-slang) - Vim filetype support for Slang Templating Engine
*   Visual Studio Code
    *   [vscode-crystal-lang (⭐256)](https://github.com/crystal-lang-tools/vscode-crystal-lang) - Formatter, linter and syntax highlighting for `cr` and `ecr` files

## LSP Language Server Protocol Implementations

*   [crystalline (⭐374)](https://github.com/elbywan/crystalline) - Crystalline is an implementation of the Language Server Protocol written in and for the Crystal Language
*   [scry (⭐334)](https://github.com/crystal-lang-tools/scry) - Code analysis server for Crystal implementing the [Language Server Protocol](https://microsoft.github.io/language-server-protocol/)

## Shell plugins

*   [crun (⭐39)](https://github.com/Val/crun) - Crystal Run : shebang wrapper for Crystal
*   [crystal-zsh (⭐27)](https://github.com/veelenga/crystal-zsh) - .oh-my-zsh plugin

