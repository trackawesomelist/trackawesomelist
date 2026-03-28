# Awesome Crystal Overview

:gem: A collection of awesome Crystal libraries, tools, frameworks and software

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/veelenga/awesome-crystal/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 veelenga/awesome-crystal](https://github.com/veelenga/awesome-crystal) · ⭐ 3.5K · 🏷️ Programming Languages

[ [Daily](/content/veelenga/awesome-crystal/README.md) / [Weekly](/content/veelenga/awesome-crystal/week/README.md) / Overview ]

---

[![SWUbanner](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner-direct.svg)](https://github.com/vshymanskyy/StandWithUkraine/blob/main/docs/README.md)

<p align="center"><img src="https://github.com/veelenga/awesome-crystal/raw/master/logo/logotype_horizontal.jpg" alt="awesome-crystal"></p>

# Awesome Crystal

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Crystal code and resources. Inspired by [awesome (⭐446k)](https://github.com/sindresorhus/awesome) and [awesome-awesomeness (⭐33k)](https://github.com/bayandin/awesome-awesomeness).
The goal is to have projects mostly stable and useful for the community.

Search shards at [shards.info](https://shards.info) for more.

Contributions are welcome. Please take a quick look at the [contribution guidelines (⭐3.5k)](https://github.com/veelenga/awesome-crystal/blob/master/.github/CONTRIBUTING.md) first.

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
    *   [Security](#security)
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

*   [bisect (⭐12)](https://github.com/spider-gazelle/bisect) - Inserting values into a sorted array
*   [blurhash.cr (⭐26)](https://github.com/Sija/blurhash.cr) - [BlurHash (⭐17k)](https://github.com/woltapp/blurhash) implementation
*   [crie (⭐12)](https://github.com/c910335/crie) - Compile-time Trie
*   [CrOTP (⭐66)](https://github.com/philnash/crotp) - HOTP and TOTP implementation for two factor authentication
*   [crystal-linked-list (⭐12)](https://github.com/abvdasker/crystal-linked-list) - Implementation of Linked List
*   [crystaledge (⭐27)](https://github.com/unn4m3d/crystaledge) - A pure Vector Math library
*   [crystalg (⭐38)](https://github.com/tobyapi/crystalg) - A Generic Algorithm Library
*   [crystalline (⭐128)](https://github.com/jtomschroeder/crystalline) - A collection of containers and algorithms
*   [csuuid (⭐16)](https://github.com/wyhaines/csuuid.cr) - A Chronologically Sortable UUID
*   [edits.cr (⭐17)](https://github.com/tcrouch/edits.cr) - Collection of edit distance algorithms
*   [fzy (⭐47)](https://github.com/hugopl/fzy) - A Crystal port of awesome Fzy project fuzzy finder algorithm
*   [Goban (⭐30)](https://github.com/soya-daizu/goban) - A fast and efficient QR Code implementation
*   [graphlb (⭐21)](https://github.com/mettuaditya/graphlb) - Collection of graph datastructure and algorithms
*   [haversine (⭐19)](https://github.com/geocrystal/haversine) - An Implementation of the Haversine formula
*   [HKDF (⭐1)](https://github.com/spider-gazelle/HKDF) - HMAC-based Extract-and-Expand Key Derivation Function [rfc5869](https://www.rfc-editor.org/rfc/rfc5869)
*   [kd\_tree (⭐19)](https://github.com/geocrystal/kd_tree) - An implementation of "K-Dimensional Tree" and "N-Nearest Neighbors"
*   [ksuid.cr (⭐17)](https://github.com/Sija/ksuid.cr) - K-Sortable Globally Unique IDs
*   [markov (⭐20)](https://github.com/mccallofthewild/markov) - Build Markov Chains and run Markov Processes
*   [multiset.cr (⭐4)](https://github.com/tcrouch/multiset.cr) - Implementation of a multiset
*   [named\_information (⭐0)](https://github.com/spider-gazelle/named_information) - Naming Things with Hashes [rfc6920](https://datatracker.ietf.org/doc/html/rfc6920)
*   [qr-code (⭐23)](https://github.com/spider-gazelle/qr-code) - QR Code generator
*   [radix (⭐106)](https://github.com/luislavena/radix) - Radix Tree implementation
*   [s2\_cells (⭐0)](https://github.com/spider-gazelle/s2_cells) - [S2 Geometry](https://s2geometry.io/devguide/s2cell_hierarchy.html) for spatial indexing
*   [secure-remote-password (⭐7)](https://github.com/spider-gazelle/secure-remote-password) - SRP-6a protocol for authentication over an insecure network
*   [SPAKE2+ (⭐2)](https://github.com/spider-gazelle/SPAKE2_plus) - Password Authenticated Key Exchange (PAKE) protocol, comparable to SRP-6a
*   [splay\_tree\_map (⭐16)](https://github.com/wyhaines/splay_tree_map.cr) - Splay Tree implementation that conforms to the Hash ducktype
*   [verhoeff (⭐0)](https://github.com/spider-gazelle/verhoeff) - Implementation of the Verhoeff checksum algorithm

## Blockchain

*   [Axentro (⭐194)](https://github.com/Axentro/Axentro) - A custom blockchain platform
*   [Cocol (⭐20)](https://github.com/cocol-project/cocol) - A minimal blockchain testbed
*   [secp256k1.cr (⭐51)](https://github.com/q9f/secp256k1.cr) - Elliptic curve used in the public-private-key cryptography

## C bindings

*   [augeas.cr (⭐8)](https://github.com/fernandes/augeas.cr) - Bindings for [Augeas](https://augeas.net/)
*   [clang.cr (⭐50)](https://github.com/crystal-lang/clang.cr) - Libclang bindings
*   [crt.cr (⭐27)](https://github.com/maiha/crt.cr) - Bindings for libncursesw and crt
*   [crystal-gsl (⭐5)](https://github.com/konovod/crystal-gsl) - Bindings for [GNU Scientific Library](https://www.gnu.org/software/gsl/)
*   [crystal-hunspell (⭐8)](https://github.com/mamantoha/crystal-hunspell) - Bindings for [Hunspell](https://hunspell.github.io/)
*   [duktape.cr (⭐141)](https://github.com/jessedoyle/duktape.cr) - Bindings for the [Duktape (⭐6.2k)](https://github.com/svaarala/duktape) javascript engine
*   [fftw.cr (⭐12)](https://github.com/firejox/fftw.cr) - Bindings for [FFTW](https://fftw.org/) library
*   [gphoto2.cr (⭐19)](https://github.com/Sija/gphoto2.cr) - Bindings for the [libgphoto2](http://www.gphoto.org/) library
*   [gpio.cr (⭐3)](https://github.com/spider-gazelle/gpio.cr) - Bindings for the gpiod library (general purpose IO control and feedback)
*   [icu.cr (⭐14)](https://github.com/olbat/icu.cr) - Bindings for the [ICU](http://site.icu-project.org/) library
*   [libnotify.cr (⭐26)](https://github.com/splattael/libnotify.cr) - Bindings for Libnotify
*   [nlopt.cr (⭐3)](https://github.com/konovod/nlopt.cr) - Bindings for [NLOpt](https://nlopt.readthedocs.io/en/latest/)
*   [pcap.cr (⭐26)](https://github.com/maiha/pcap.cr) - Bindings for libpcap
*   [pledge.cr (⭐10)](https://github.com/chris-huxtable/pledge.cr) - Bindings for OpenBSD's `pledge(2)`
*   [ssh2.cr (⭐49)](https://github.com/spider-gazelle/ssh2.cr) - Bindings for libssh2 library
*   [syslog.cr (⭐11)](https://github.com/chris-huxtable/syslog.cr) - Bindings for `syslog`
*   [v4l2.cr (⭐5)](https://github.com/spider-gazelle/v4l2.cr) - Bindings for [Video4Linux2](https://en.wikipedia.org/wiki/Video4Linux)
*   [wasmer-crystal (⭐97)](https://github.com/naqvis/wasmer-crystal) - Bindings for the `wasmer` WebAssembly runtime
*   [win32cr (⭐20)](https://github.com/mjblack/win32cr) - Bindings for Win32 API
*   [x\_do.cr (⭐16)](https://github.com/woodruffw/x_do.cr) - Bindings for libxdo ([`xdotool`](https://github.com/jordansissel/xdotool))

## Caching

*   [cache (⭐50)](https://github.com/crystal-cache/cache) - A key/value store where pairs can expire after a specified interval
*   [crystal-memcached (⭐36)](https://github.com/comandeo/crystal-memcached) - Implementation of a memcached client

## CLI Builders

*   [admiral (⭐140)](https://github.com/jwaldrip/admiral.cr) - A robust DSL for writing command line interfaces
*   [Athena Console (⭐22)](https://github.com/athena-framework/console) - Allows for the creation of CLI based commands
*   [clicr (⭐31)](https://github.com/j8r/clicr) -  A simple declarative command line interface builder
*   [clim (⭐125)](https://github.com/at-grandpa/clim) - Slim command line interface builder
*   [Cling (⭐32)](https://github.com/devnote-dev/cling) - A modular, non-macro-based command line interface library
*   [commander (⭐128)](https://github.com/mrrooijen/commander) - Command-line interface builder
*   [Keimeno (⭐16)](https://github.com/robacarp/keimeno) -  A lightweight text user interface library in Crystal
*   [OptionParser](https://crystal-lang.org/api/OptionParser.html) - command-line options processing (Crystal stdlib)
*   [Phreak (⭐34)](https://github.com/shinzlet/phreak) - A highly flexible Crystal CLI builder in the style of OptionParser

## CLI Utils

*   [climate (⭐17)](https://github.com/Sija/climate.cr) - Tiny tool to make your CLI output 🌈  coloured
*   [coin (⭐7)](https://github.com/caian-org/coin) - Command-line application that performs currency conversion via the [Fixer API](https://fixer.io)
*   [cride (⭐54)](https://github.com/j8r/cride) - A light CLI text editor/IDE
*   [git-repository (⭐5)](https://github.com/place-labs/git-repository) - A git cli wrapper querying and cloning remote repositories with minimal data transfer
*   [hetzner-k3s (⭐3.4k)](https://github.com/vitobotta/hetzner-k3s) - A CLI tool to quickly create and manage Kubernetes clusters in Hetzner Cloud
*   [lff (⭐19)](https://github.com/mkdika/lff-cr) - Simple and straightforward large files finder utility in command line
*   [meet (⭐42)](https://github.com/ryanprior/meet) - Start a jitsi meeting quickly from the comfort of your command line
*   [oq (⭐205)](https://github.com/Blacksmoke16/oq) - A performant, and portable jq wrapper to facilitate the consumption and output of formats other than JSON; using [jq (⭐34k)](https://github.com/stedolan/jq) filters to transform the data
*   [progress\_bar.cr (⭐17)](https://github.com/TPei/progress_bar.cr) - A simple and customizable progress bar
*   [tablo (⭐37)](https://github.com/hutou/tablo) - A flexible terminal table generator
*   [tallboy (⭐61)](https://github.com/epoch/tallboy) - Generate ASCII character tables with support for spanning cells over multiple columns

## Code Analysis and Metrics

*   [ameba (⭐556)](https://github.com/crystal-ameba/ameba) - A static code analysis tool
*   [cruml (⭐8)](https://github.com/tamdaz/cruml) - A tool that provides an UML class diagram generator for any Crystal projects
*   [linguist.cr (⭐12)](https://github.com/microgit-com/linguist.cr) - Using multiple ways to find programming language used in files, based on Github's Linguist

## Compression

*   [Crystar (⭐47)](https://github.com/naqvis/crystar) - Readers and writers of Tar archive format
*   [Gzip](https://crystal-lang.org/api/Compress/Gzip.html) - readers and writers of gzip format (Crystal stdlib)
*   [polylines.cr (⭐10)](https://github.com/BuonOmo/polylines.cr) — compression of series of coordinates
*   [snappy (⭐22)](https://github.com/naqvis/snappy) -  Snappy compression format reader/writer for Crystal
*   [Zip](https://crystal-lang.org/api/Compress/Zip.html) - readers and writers of zip format (Crystal stdlib)
*   [Zlib](https://crystal-lang.org/api/Compress/Zlib.html) - readers and writers of zlib format (Crystal stdlib)
*   [zstd.cr (⭐42)](https://github.com/didactic-drunk/zstd.cr) - Bindings for [Zstandard (⭐27k)](https://github.com/facebook/zstd) compression library

## Configuration

*   [cr-dotenv (⭐99)](https://github.com/gdotdesign/cr-dotenv) - Loads .env file
*   [Envy (⭐10)](https://github.com/grottopress/envy) - Load environment variables from YAML
*   [envyable (⭐7)](https://github.com/philnash/envyable.cr) -  A simple YAML to ENV config loader
*   [habitat (⭐83)](https://github.com/luckyframework/habitat) - Type safe configuration for your classes and modules
*   [totem (⭐71)](https://github.com/icyleaf/totem) - Load and parse a configuration in JSON, YAML, dotenv formats

## Converters

*   [base62.cr (⭐13)](https://github.com/Sija/base62.cr) - Base62 encoder/decoder, well suited for url-shortening
*   [crunits (⭐6)](https://github.com/spider-gazelle/crunits) - Tool for converting units of measure (miles to kilometers, celsius to fahrenheit etc)
*   [money (⭐43)](https://github.com/crystal-money/money) - Handling money and currency conversion with ease (almost complete port of [RubyMoney (⭐2.8k)](https://github.com/RubyMoney/money))
*   [sass.cr (⭐38)](https://github.com/straight-shoota/sass.cr) - Compile SASS/SCSS to CSS ([libsass (⭐4.3k)](https://github.com/sass/libsass/) binding)
*   [tssc.cr (⭐6)](https://github.com/Sija/tssc.cr) - `Time::Span` String Converter (incl. JSON & YAML support)

## Cryptography

*   [cmac (⭐5)](https://github.com/spider-gazelle/cmac) - Crystal implementation of Cipher-based Message Authentication Code (CMAC)
*   [ed25519 (⭐11)](https://github.com/spider-gazelle/ed25519) - the Ed25519 elliptic curve public-key signature system
    described in \[RFC 8032]
*   [monocypher.cr (⭐19)](https://github.com/konovod/monocypher.cr) - Crystal wrapper for the Monocypher crypto library
*   [sodium.cr (⭐51)](https://github.com/didactic-drunk/sodium.cr) - Crystal wrapper for the libsodium crypto API

## Data Formats

*   [BinData (⭐48)](https://github.com/spider-gazelle/bindata) - Binary data parser helper with an [ASN.1](https://en.wikipedia.org/wiki/Abstract_Syntax_Notation_One) parser
*   [config.cr (⭐14)](https://github.com/chris-huxtable/config.cr) - Easy to use configuration format parser
*   [crinder (⭐28)](https://github.com/c910335/crinder) - Class based json renderer
*   [Crystalizer (⭐41)](https://github.com/j8r/crystalizer) - (De)serialize any Crystal object; supporting JSON, YAML, and Byte formats out of the box
*   [CSV](https://crystal-lang.org/api/CSV.html) - parsing and generating for comma-separated values (Crystal stdlib)
*   [front\_matter.cr (⭐13)](https://github.com/chris-huxtable/front_matter.cr) - Separates a files front matter from its content
*   [geoip2.cr (⭐20)](https://github.com/delef/geoip2.cr) - GeoIP2 reader
*   [HAR (⭐22)](https://github.com/NeuraLegion/har) - HAR (HTTP Archive) parser
*   [INI](https://crystal-lang.org/api/INI.html) - INI file parser (Crystal stdlib)
*   [jmespath.cr (⭐12)](https://github.com/qequ/jmespath.cr) - Crystal implementation of JMESPath, a query language for JSON
*   [JSON](https://crystal-lang.org/api/JSON.html) - parsing and generating JSON documents (Crystal stdlib)
*   [json-schema (⭐15)](https://github.com/spider-gazelle/json-schema) - convert JSON serializable classes into a [JSON Schema](https://json-schema.org/) representation
*   [JSON::OnSteroids (⭐25)](https://github.com/anykeyh/json_on_steroids) - handle and mutate JSON document easily
*   [maxminddb.cr (⭐27)](https://github.com/delef/maxminddb.cr) - MaxMindDB reader
*   [toml.cr (⭐65)](https://github.com/crystal-community/toml.cr) - TOML parser
*   [toon-crystal (⭐9)](https://github.com/mamantoha/toon-crystal) - TOON (Token-Oriented Object Notation) parser
*   [XML](https://crystal-lang.org/api/XML.html) - parsing and generating XML documents (Crystal stdlib)
*   [YAML](https://crystal-lang.org/api/YAML.html) - parsing and generating YAML documents (Crystal stdlib)

## Data Generators

*   [faker (⭐156)](https://github.com/askn/faker) - A library for generating fake data
*   [hashids.cr (⭐53)](https://github.com/splattael/hashids.cr) - A library to generate YouTube-like ids from one or many numbers
*   [prime (⭐3)](https://github.com/wontruefree/prime) - A prime number generator

## Database Drivers/Clients

*   [couchdb.cr (⭐14)](https://github.com/TechMagister/couchdb.cr) - CouchDB client
*   [cryomongo (⭐78)](https://github.com/elbywan/cryomongo) - MongoDB driver
*   [crystal-db (⭐312)](https://github.com/crystal-lang/crystal-db) - Common db api
*   [crystal-ldap (⭐19)](https://github.com/spider-gazelle/crystal-ldap) - LDAP client
*   [crystal-mysql (⭐111)](https://github.com/crystal-lang/crystal-mysql) - MySQL connector for Crystal
*   [crystal-pg (⭐480)](https://github.com/will/crystal-pg) - A Postgres driver
*   [crystal-redis (⭐379)](https://github.com/stefanwille/crystal-redis) - Full featured Redis client
*   [crystal-rethinkdb (⭐22)](https://github.com/kingsleyh/crystal-rethinkdb) - Driver for RethinkDB / RebirthDB
*   [crystal-sqlite3 (⭐157)](https://github.com/crystal-lang/crystal-sqlite3) - SQLite3 bindings
*   [leveldb (⭐41)](https://github.com/crystal-community/leveldb) - Crystal bindings for LevelDB
*   [rocksdb.cr (⭐40)](https://github.com/maiha/rocksdb.cr) - RocksDB client
*   [surrealdb.cr (⭐7)](https://github.com/yorci/surrealdb.cr) - Unoffical SurrealDB HTTP & Websocket Client

## Database Tools

*   [migrate (⭐32)](https://github.com/vladfaust/migrate.cr) - A simpler database migration tool with transactions

## Debugging

*   [backtracer.cr (⭐18)](https://github.com/Sija/backtracer.cr) - Shard aiming to assist with parsing backtraces into a structured form
*   [debug.cr (⭐103)](https://github.com/Sija/debug.cr) - `debug!(…)` macro for `pp`-style debugging

## Dependency Injection

*   [Athena Dependency Injection (⭐11)](https://github.com/athena-framework/dependency-injection) - Robust dependency injection service container framework
*   [Crystal-DI (⭐33)](https://github.com/funk-yourself/crystal-di) - Lightweight DI Container
*   [HardWire (⭐23)](https://github.com/jerometwell/hardwire) - A compile-time non-intrusive dependency injection system
*   [syringe (⭐8)](https://github.com/Bonemind/syringe) - A simple and basic dependency injection shard for crystal

## Email

*   [carbon (⭐86)](https://github.com/luckyframework/carbon) - Fun, testable, and adapter-based email library
*   [crystal-email (⭐115)](https://github.com/arcage/crystal-email) - Simple e-mail sending library
*   [CrystalEmail](https://git.sceptique.eu/Sceptique/CrystalEmail) - A RFC compliant Email validator
*   [sendgrid.cr (⭐16)](https://github.com/dlanileonardo/sendgrid.cr) - Simple Sendgrid Client

## Environment Management

*   [asdf-crystal (⭐77)](https://github.com/marciogm/asdf-crystal) - Plugin for asdf version manager
*   [crenv (⭐237)](https://github.com/crenv/crenv) - Crystal version manager
*   [rcm.cr (⭐45)](https://github.com/maiha/rcm.cr) - Redis Cluster Manager
*   [vfox-crystal (⭐10)](https://github.com/yanecc/vfox-crystal) - Plugin for vfox version manager

## Examples and funny stuff

*   [blackjack-cr (⭐10)](https://github.com/gdonald/blackjack-cr) - Console Blackjack
*   [crystal-patterns (⭐304)](https://github.com/crystal-community/crystal-patterns) - Examples of GOF patters
*   [crystalworld (⭐43)](https://github.com/vladfaust/crystalworld) - [realworld.io](https://realworld.io) back-end API implementation
*   [exercism-crystal (⭐79)](https://github.com/exercism/crystal) - Exercism exercises
*   [try.cr (⭐26)](https://github.com/maiha/try.cr) - Try monad

## Framework Components

*   [Athena Event Dispatcher (⭐15)](https://github.com/athena-framework/event-dispatcher) - A Mediator and Observer pattern event library
*   [Athena Negotiation (⭐5)](https://github.com/athena-framework/negotiation) - Framework agnostic content negotiation library
*   [device\_detector (⭐24)](https://github.com/creadone/device_detector) - Shard for detect device by user agent string
*   [Exception Page (⭐72)](https://github.com/crystal-loot/exception_page) - An exceptional exception page for Crystal web libraries and frameworks
*   [graphql (⭐138)](https://github.com/graphql-crystal/graphql) - Type-safe [GraphQL](http://graphql.org) server implementation
*   [graphql-crystal (⭐213)](https://github.com/ziprandom/graphql-crystal) - [GraphQL](http://graphql.org) implementation
*   [kemal-session (⭐62)](https://github.com/kemalcr/kemal-session) - Session handler for Kemal
*   [mochi (⭐26)](https://github.com/awcrotwell/mochi) - Authentication shard inspired by Devise supporting: Authenticable, Confirmable, Invitable & more
*   [motion.cr (⭐53)](https://github.com/awcrotwell/motion.cr) - Object oriented frontend library for Amber
*   [multi-auth (⭐115)](https://github.com/msa7/multi_auth) - Standardized multi-provider OAuth2 authentication (inspired by omniauth)
*   [praetorian (⭐61)](https://github.com/ilanusse/praetorian) - Minimalist authorization library inspired by Pundit
*   [Shield (⭐56)](https://github.com/grottopress/shield) - Comprehensive security for *Lucky* framework
*   [shrine.cr (⭐82)](https://github.com/jetrockets/shrine.cr) - File Attachment toolkit for Crystal applications. Heavily inspired by Shrine for Ruby
*   [tourmaline (⭐167)](https://github.com/protoncr/tourmaline) - Telegram bot framework with an API loosely based on [telegraf.js](https://telegraf.js.org/)

## Game Development

*   [CrSFML (⭐355)](https://github.com/oprypin/crsfml) - Bindings to [SFML](https://www.sfml-dev.org/) multimedia/game library
*   [crystal-chipmunk (⭐45)](https://github.com/oprypin/crystal-chipmunk) - Bindings to [Chipmunk](http://chipmunk-physics.net/), a fast and lightweight 2D game physics library
*   [crystal-imgui-sfml (⭐18)](https://github.com/oprypin/crystal-imgui-sfml) - Bindings to integrate [Dear ImGui (⭐72k)](https://github.com/ocornut/imgui) into an [SFML](https://www.sfml-dev.org/) project
*   [entitas.cr (⭐38)](https://github.com/spoved/entitas.cr) - A Entity Component System Framework for Crystal
*   [MyECS (⭐21)](https://github.com/konovod/myecs) - A Sparse Entity Component System Framework for Crystal
*   [Raylib-cr (⭐107)](https://github.com/sol-vin/raylib-cr) - Direct bindings to [Raylib](https://raylib.com), which supports Linux, Windows, and Mac
*   [SDL-Crystal-Bindings (⭐16)](https://github.com/Hadeweka/SDL-Crystal-Bindings) - Direct (unsafe) bindings to [SDL2](https://www.libsdl.org/), intended for writing own game libraries

## GUI Development

*   [crystal-imgui (⭐76)](https://github.com/oprypin/crystal-imgui) - Bindings to [Dear ImGui (⭐72k)](https://github.com/ocornut/imgui), an immediate-mode graphical UI library
*   [GTK4.cr (⭐121)](https://github.com/hugopl/gtk4.cr) - Bindings for [GTK4](https://docs.gtk.org/gtk4/overview.html) with Crystalized API
*   [Iu (⭐76)](https://github.com/grkek/iu) - UI framework based on the [Fusion/libui.cr (⭐182)](https://github.com/Fusion/libui.cr) library, with custom elements and modified bindings from [hedron-crystal/hedron (⭐88)](https://github.com/hedron-crystal/hedron)
*   [Ultimate GTK4 Crystal Guide](https://ultimate-gtk4-crystal-guide.geopjr.dev/) - Learn how to create premium GTK4 apps in Crystal

## HTML Builders

*   [blueprint (⭐80)](https://github.com/gunbolt/blueprint) - Write reusable and testable HTML templates in plain Crystal
*   [form\_builder.cr (⭐33)](https://github.com/westonganger/form_builder.cr) - Dead simple HTML form builder for Crystal with built-in support for many popular UI libraries such as Bootstrap
*   [to\_html (⭐17)](https://github.com/sbsoftware/to_html.cr) - The fastest HTML builder engine for Crystal
*   [Water (⭐30)](https://github.com/shootingfly/water) - A library for writing HTML in plain Crystal

## HTML/XML Parsing

*   [docx\_cr\_converter (⭐11)](https://github.com/aristotelesbr/docx_cr_converter) - parse DOCX Word
*   [lexbor (⭐112)](https://github.com/kostya/lexbor) - Fast HTML5 Parser that includes CSS selectors

## HTTP

*   [Cable (⭐132)](https://github.com/cable-cr/cable) - An ActionCable "port" to Crystal, framework agnostic, 100% compatible with the ActionCable JS Client
*   [cossack (⭐110)](https://github.com/crystal-community/cossack) - Simple flexible HTTP client
*   [crest (⭐246)](https://github.com/mamantoha/crest) - Simple HTTP and REST client, inspired by the Ruby's RestClient gem
*   [crul (⭐113)](https://github.com/porras/crul) - Command line HTTP client
*   [digest-auth (⭐4)](https://github.com/spider-gazelle/digest-auth) - Digest authentication
*   [halite (⭐172)](https://github.com/icyleaf/halite) - Crystal HTTP Requests with a chainable REST API, built-in sessions and loggers
*   [http-multiserver.cr (⭐24)](https://github.com/vladfaust/http-multiserver.cr) - Mounting multiple servers via routes (a.k.a. URL mapping)
*   [http-params-serializable (⭐21)](https://github.com/vladfaust/http-params-serializable) - HTTP params (de)serialization, applicable to URL queries and URL-encoded forms
*   [http-protection (⭐75)](https://github.com/rogeriozambon/http-protection) - Protection against typical web attacks
*   [http2 (⭐106)](https://github.com/ysbaddaden/http2) - HTTP/2 Protocol Implementation
*   [HTTP::Client](https://crystal-lang.org/api/HTTP/Client.html) - HTTP client (Crystal stdlib)
*   [HTTP::Server](https://crystal-lang.org/api/HTTP/Server.html) - HTTP server (Crystal stdlib)
*   [HTTP::WebSocket](https://crystal-lang.org/api/HTTP/WebSocket.html) - HTTP WebSocket client (Crystal stdlib)
*   [link-header (⭐1)](https://github.com/spider-gazelle/link-header) - HTTP Link Header Parser
*   [ntlm (⭐4)](https://github.com/spider-gazelle/ntlm) - NTLM authentication
*   [proxy-fetcher.cr (⭐11)](https://github.com/nbulaj/proxy-fetcher.cr) - Proxy lists fetching & validating library
*   [sse.cr (⭐26)](https://github.com/y2k2mt/sse.cr) - [Server-Sent Events](https://html.spec.whatwg.org/multipage/server-sent-events.html) client

## Image processing

*   [celestine (⭐95)](https://github.com/celestinecr/celestine) - Create SVG images using a DSL
*   [ffmpeg (⭐22)](https://github.com/spider-gazelle/ffmpeg) - FFmpeg bindings that works with StumpyPNG to extract frames
*   [Pluto (⭐75)](https://github.com/phenopolis/pluto) - A fast and convenient image processing library
*   [stumpy\_png (⭐108)](https://github.com/stumpycr/stumpy_png) - Read and write PNG images

## Implementations/Compilers

*   [charly](https://github.com/charly-lang) - Charly Programming Language
*   [cltk (⭐72)](https://github.com/ziprandom/cltk) - A crystal port of the Ruby Language Toolkit
*   [crisp (⭐47)](https://github.com/rhysd/Crisp) - Lisp dialect implemented with Crystal
*   [LinCAS-lang](https://github.com/LinCAS-lang) - A programming language for scientific computation
*   [mint-lang (⭐4.2k)](https://github.com/mint-lang/mint) - A refreshing programming language for the front-end web
*   [myst-lang](https://github.com/myst-lang/) - A practical, dynamic language designed to be written and understood as easily and efficiently as possible
*   [novika (⭐19)](https://github.com/novika-lang/novika) - A free-form, moldable, interpreted programming language
*   [runic-lang](https://github.com/runic-lang) - In-design toy language

## Internationalization

*   [crystal-i18n (⭐32)](https://github.com/crystal-i18n/i18n) - An internationalization library inspired by Ruby-I18n
*   [i18n.cr (⭐22)](https://github.com/vladfaust/i18n.cr) - Internationalization shard
*   [Lens (⭐18)](https://github.com/syeopite/lens) - A multiformat internationalization (i18n) shard for Crystal. Supports Gettext, Ruby YAML, etc.
*   [Rosetta (⭐59)](https://github.com/wout/rosetta) - A blazing fast internationalization (i18n) library with compile-time key lookup supporting YAML and JSON formats

## Logging and monitoring

*   [crafana (⭐21)](https://github.com/spoved/crafana.cr) - A [Grafana](https://grafana.com/) library to help autogenerate dashboards
*   [fiber\_metrics.cr (⭐9)](https://github.com/didactic-drunk/fiber_metrics.cr) - Track run time, wait time, or memory allocations per `Fiber`, method or block
*   [Log](https://crystal-lang.org/api/Log.html) - logging utility (Crystal stdlib)
*   [statsd.cr (⭐36)](https://github.com/miketheman/statsd.cr) - [Statsd (⭐18k)](https://github.com/etsy/statsd) client library

## Machine Learning

*   [ai4cr (⭐28)](https://github.com/drhuffman12/ai4cr) - Artificial Intelligence (based on [https://github.com/SergioFierens/ai4r (⭐721)](https://github.com/SergioFierens/ai4r))
*   [Cadmium (⭐210)](https://github.com/cadmiumcr/cadmium) - NLP library based heavily on [natural (⭐11k)](https://github.com/NaturalNode/natural)
*   [crystal-fann (⭐87)](https://github.com/NeuraLegion/crystal-fann) - FANN (Fast Artifical Neural Network) binding
*   [mxnet.cr (⭐22)](https://github.com/toddsundsted/mxnet.cr) - Bindings for [MXNet](https://mxnet.incubator.apache.org/)
*   [shainet (⭐194)](https://github.com/NeuraLegion/shainet) - SHAInet (Neural Network in pure crystal)

## Markdown/Text Processors

*   [cr-cmark-gfm (⭐21)](https://github.com/amauryt/cr-cmark-gfm) -  Crystal C bindings for cmark-gfm to work with Commonmark and Github Flavored Markdown
*   [markd (⭐123)](https://github.com/icyleaf/markd) - Yet another markdown parser built for speed, Compliant to CommonMark specification

## Misc

*   [aasm.cr (⭐55)](https://github.com/veelenga/aasm.cr) - Easy to use finite state machine for Crystal classes
*   [any\_hash.cr (⭐38)](https://github.com/Sija/any_hash.cr) - Recursive Hash with better JSON::Any included
*   [anyolite (⭐180)](https://github.com/Anyolite/anyolite) - Full mruby interpreter with simple bindings, allowing for easy scripting support in projects
*   [burocracia.cr (⭐23)](https://github.com/vinibrsl/burocracia.cr) - burocracia.cr the dependecyless shard to validate, generate and format Brazilian burocracias such as CPF, CNPJ and CEP
*   [callbacks (⭐12)](https://github.com/vladfaust/callbacks.cr) - Expressive callbacks module
*   [circuit\_breaker (⭐27)](https://github.com/TPei/circuit_breaker) - Implementation of the circuit breaker pattern
*   [cpf\_cnpj](https://codeberg.org/gunbolt/cpf_cnpj) - Provide utilities for validating and formatting CPF and CNPJ identifiers
*   [CrSignals (⭐10)](https://github.com/firejox/CrSignals) - Signals/slots notification library
*   [crystal-binary\_parser (⭐20)](https://github.com/DanSnow/crystal-binary_parser) - Binary parser
*   [crystal-web-framework-stars (⭐74)](https://github.com/isaced/crystal-web-framework-stars) - Web frameworks for Crystal, most starred on Github
*   [crz (⭐94)](https://github.com/dhruvrajvanshi/crz) - Functional programming library
*   [defined (⭐18)](https://github.com/wyhaines/defined.cr) - macros for conditional compilation based on constant definitions, version requirements, or environment variable settings
*   [emoji.cr (⭐53)](https://github.com/veelenga/emoji.cr) - Emoji library
*   [gphoto2-web.cr (⭐13)](https://github.com/Sija/gphoto2-web.cr) - Web API for libgphoto2
*   [immutable (⭐204)](https://github.com/lucaong/immutable) - Implementation of thread-safe, persistent, immutable collections
*   [iterm2 (⭐6)](https://github.com/toddsundsted/iterm2) - Display images within the terminal using the ITerm2 Inline Images Protocol
*   [lua.cr (⭐65)](https://github.com/veelenga/lua.cr) - Bindings to liblua and a wrapper around it
*   [luajit.cr (⭐7)](https://github.com/mdwagner/luajit.cr) - LuaJIT bindings for Crystal
*   [monads (⭐47)](https://github.com/alex-lairan/monads) - Monad implementation
*   [observable (⭐9)](https://github.com/TPei/observable) - Implementation of the observer pattern
*   [pinger (⭐11)](https://github.com/spider-gazelle/pinger) - Ping IP addresses and DNS entries without requiring sudo
*   [port\_midi (⭐7)](https://github.com/jimm/crystal_port_midi) - Crystal C bindings for the PortMIDI cross-platform MIDI I/O library
*   [retriable.cr (⭐45)](https://github.com/Sija/retriable.cr) - Simple DSL to retry failed code blocks
*   [sentry (⭐6)](https://github.com/crystal-china/sentry) - Build/Runs your crystal application, watches files, and rebuilds/restarts app on file changes.
*   [serf-handler.cr (⭐1)](https://github.com/wyhaines/serf-handler.cr) - Framework for building Serf handlers, with a suite of useful builtin capabilities
*   [simple\_retry (⭐7)](https://github.com/spider-gazelle/simple_retry) - Simple tool for retrying failed code blocks
*   [sslscan.cr (⭐10)](https://github.com/NeuraLegion/sslscan.cr) - Crystal shard wrapping the rbsec/sslscan utility
*   [version\_tools (⭐9)](https://github.com/anicholson/crystal-version-tools) - Version-dependent behaviour, specified at compile-time
*   [wafalyzer (⭐35)](https://github.com/NeuraLegion/wafalyzer) - Web Application Firewall (WAF) Detector - shard + cli
*   [zaru\_crystal (⭐13)](https://github.com/szTheory/zaru_crystal) - Filename sanitization

## Network Protocols

*   [amqp-client.cr (⭐72)](https://github.com/cloudamqp/amqp-client.cr) - AMQP 0-9.1, a messaging protocol, implemented by eg. RabbitMQ
*   [connect-proxy (⭐7)](https://github.com/spider-gazelle/connect-proxy) - Connect method style of HTTP tunnelling / HTTP proxy
*   [cr-xmpp (⭐17)](https://github.com/naqvis/cr-xmpp) - XMPP/Jabber Library
*   [Crirc (⭐21)](https://github.com/Meoowww/Crirc) - IRC protocol implementation (Client, Server, Bots)
*   [crystal-bacnet (⭐0)](https://github.com/spider-gazelle/crystal-bacnet) - BACnet protocol implementation with BACnet/IP client
*   [crystal-json-socket (⭐14)](https://github.com/foi/crystal-json-socket) - JSON-socket client & server implementation. Inspired by and compatible with [node-json-socket (⭐155)](https://github.com/sebastianseilund/node-json-socket/) and [ruby-json-socket (⭐4)](https://github.com/foi/ruby-json-socket)
*   [crystal-mqtt (⭐21)](https://github.com/spider-gazelle/crystal-mqtt) - A MQTT client
*   [crystal-snmp (⭐17)](https://github.com/spider-gazelle/crystal-snmp) - An SNMP implementation with version 1, 2c and 3 support
*   [dns (⭐14)](https://github.com/spider-gazelle/dns) - DNS protocol implementation and resolver
*   [fast\_irc.cr (⭐24)](https://github.com/RX14/fast_irc.cr) - Fast IRC parser/generator
*   [jwt (⭐212)](https://github.com/crystal-community/jwt) - Implementation of JWT (JSON Web Token)
*   [knx (⭐3)](https://github.com/spider-gazelle/knx) - KNX protocol implementation supporting multicast, unicast and TCP/IP tunnelling
*   [Matter (⭐10)](https://github.com/Crystal-Matter/matter) - Matter protocol for smart home and Internet of things (IoT) devices
*   [mDNS (⭐8)](https://github.com/spider-gazelle/mdns) - DNS Service Discovery and multicast DNS
*   [mqtt-client.cr (⭐5)](https://github.com/84codes/mqtt-client.cr) - A fast and lightweight MQTT client
*   [msgpack-crystal (⭐146)](https://github.com/crystal-community/msgpack-crystal) - MessagePack library
*   [OAuth](https://crystal-lang.org/api/OAuth.html) - OAuth consumer (Crystal stdlib)
*   [OAuth2](https://crystal-lang.org/api/OAuth2.html) - OAuth2 client (Crystal stdlib)
*   [OpenSSL](https://crystal-lang.org/api/OpenSSL.html) - bindings to libssl (Crystal stdlib)
*   [simple\_rpc (⭐70)](https://github.com/kostya/simple_rpc) - RPC Server and Client for Crystal. Implements msgpack-rpc protocol
*   [stomp (⭐1)](https://github.com/spider-gazelle/stomp) - STOMP protocol
*   [telnet.cr (⭐11)](https://github.com/spider-gazelle/telnet.cr) - Telnet protocol
*   [transfer\_more](https://git.sceptique.eu/Sceptique/transfer_more) - Clone of transfer.sh to uploads files

## Networking

*   [ipaddress.cr (⭐45)](https://github.com/Sija/ipaddress.cr) - Library to handle IPv4 and IPv6 addresses
*   [mac-address (⭐2)](https://github.com/automatico/mac-address) - Library for working with MAC addresses

## ORM/ODM Extensions

*   [avram (⭐177)](https://github.com/luckyframework/avram) - A database wrapper for reading, writing, and migrating Postgres databases
*   [clear (⭐283)](https://github.com/anykeyh/clear) - ORM specialized to PostgreSQL only but with advanced features
*   [crecto (⭐351)](https://github.com/Crecto/crecto) - Database wrapper, based on Ecto
*   [granite (⭐308)](https://github.com/amberframework/granite) - ORM for Postgres, Mysql, Sqlite
*   [jennifer.cr (⭐424)](https://github.com/imdrasil/jennifer.cr) - Active Record pattern implementation with flexible query chainable builder and migration system
*   [lustra (⭐22)](https://github.com/crystal-garage/lustra) - Advanced PostgreSQL ORM with ActiveRecord pattern, full-text search, geometry types, and more
*   [rethinkdb-orm (⭐24)](https://github.com/spider-gazelle/rethinkdb-orm) - ORM for RethinkDB / RebirthDB

## Package Management

*   [shards (⭐791)](https://github.com/crystal-lang/shards) - Dependency manager for the Crystal

## Processes and Threads

*   [await\_async (⭐88)](https://github.com/anykeyh/await_async) - Add keywords await & async in Crystal Lang
*   [concurrent.cr (⭐48)](https://github.com/didactic-drunk/concurrent.cr) - Simplified concurrency using streams/pipelines, waitgroups, semaphores, smores and more
*   [neph (⭐205)](https://github.com/tbrand/neph) - A modern command line job processor that can execute jobs concurrently
*   [promise (⭐44)](https://github.com/spider-gazelle/promise) - A Promise implementation with type inference
*   [werk (⭐30)](https://github.com/marghidanu/werk) - Dead simple task runner with concurrent support, ideal for local CI

## Project Generators

*   [crygen (⭐13)](https://github.com/tamdaz/crygen) - A library that allows to generate the Crystal code
*   [crystal\_lib (⭐141)](https://github.com/crystal-lang/crystal_lib) - Automatic binding generator for native libraries
*   [fez (⭐52)](https://github.com/jwoertink/fez) - A Kemal application generator
*   [libgen (⭐84)](https://github.com/olbat/libgen) - Automatic bindings generator configured using JSON/YAML files

## Queues and Messaging

*   [crafka (⭐20)](https://github.com/BT-OpenSource/crafka) - Apache Kafka library utilizing `librdkafka`
*   [mosquito (⭐242)](https://github.com/mosquito-cr/mosquito/) - Redis backed periodic and ad hoc job processing
*   [NATS.io (⭐44)](https://github.com/nats-io/nats.cr) - NATS client
*   [sidekiq.cr (⭐775)](https://github.com/mperham/sidekiq.cr) - Simple, efficient job processing

## Routing

*   [orion (⭐128)](https://github.com/obsidian/orion) - A minimal, rails-esque routing library
*   [router.cr (⭐272)](https://github.com/tbrand/router.cr) - Minimum but powerful http router for HTTP::Server

## Scheduling

*   [crystime](https://gitlab.com/crystallabs/crystime) - Advanced time, calendar, schedule, and remind library
*   [schedule.cr (⭐76)](https://github.com/hugoabonizio/schedule.cr) - Run periodic tasks
*   [tasker (⭐56)](https://github.com/spider-gazelle/tasker) - A high precision scheduler including timezone aware cron jobs

## Science and Data analysis

*   [alea (⭐12)](https://github.com/nin93/alea) - Repeatable sampling, CDF and other utilities to work with probability distributions
*   [ishi (⭐48)](https://github.com/toddsundsted/ishi) - Graph plotting package with a small API and sensible defaults powered by gnuplot
*   [linalg (⭐53)](https://github.com/konovod/linalg) - Linear algebra library inspired by MATLAB and SciPy.linalg
*   [num.cr (⭐160)](https://github.com/crystal-data/num.cr) - Numerical computing library supporting N-Dimensional data
*   [predict.cr (⭐19)](https://github.com/RX14/predict.cr) - Satellite prediction library using the sgp4 model
*   [quartz (⭐16)](https://github.com/RomainFranceschini/quartz) - Modeling and simulation framework

## Search

*   [hermes (⭐38)](https://github.com/imdrasil/hermes.cr) - Data Mapper pattern implementation for ElastiSearch

## Security

*   [cyclonedx-cr (⭐4)](https://github.com/hahwul/cyclonedx-cr) - CycloneDX SBOM(Software Bill of Materials) generator for Crystal projects
*   [OWASP Noir (⭐1.1k)](https://github.com/owasp-noir/noir) - Attack surface detector that identifies endpoints by static analysis
*   [XSSMaze (⭐31)](https://github.com/hahwul/xssmaze) - XSSMaze is a web service that tests security tools using diverse XSS cases

## Serverless Computing

*   [crystal\_openfaas (⭐23)](https://github.com/TPei/crystal_openfaas/) - Template to enable crystal as first class citizens in OpenFaaS
*   [secrets-env (⭐6)](https://github.com/spider-gazelle/secrets-env) - Extends ENV module to read values injected by docker / kubernetes secrets and other orchestration tools

## System

*   [baked\_file\_system (⭐187)](https://github.com/schovi/baked_file_system) - Virtual file system implementation
*   [hardware (⭐76)](https://github.com/crystal-community/hardware) - Get CPU, Memory and Network informations of the running OS and its processes

## Task management

*   [cake (⭐73)](https://github.com/axvm/cake) - Production-ready Make-like utility tool
*   [sam (⭐98)](https://github.com/imdrasil/sam.cr) - Another one Rake-like task manager with namespacing and arguments system

## Template Engine

*   [crinja (⭐142)](https://github.com/straight-shoota/crinja) - An implementation of the [Jinja2 template engine](http://jinja.pocoo.org/)
*   [crustache (⭐87)](https://github.com/MakeNowJust/crustache) - [{{Mustache}}](https://mustache.github.io) for Crystal
*   [ECR (Embedded Crystal)](https://crystal-lang.org/api/ECR.html) - compile time template language which uses plain crystal expressions (Crystal stdlib)
*   [Jbuilder (⭐44)](https://github.com/shootingfly/jbuilder) - Generate JSON objects with a Builder-style DSL, inspired by jbuilder
*   [Kilt (⭐152)](https://github.com/jeromegn/kilt) - Abstraction layer for template engines
*   [Slang (⭐237)](https://github.com/jeromegn/slang) - Lightweight, terse, templating language inspired by Ruby's Slim
*   [teeplate (⭐17)](https://github.com/mosop/teeplate) - A library for rendering multiple template files

## Testing

*   [Athena Spec (⭐3)](https://github.com/athena-framework/spec) - Common/helpful [Spec](https://crystal-lang.org/api/Spec.html) compliant testing utilities
*   [crotest (⭐28)](https://github.com/emancu/crotest) - A tiny and simple test framework
*   [crytic (⭐68)](https://github.com/hanneskaeufler/crytic) - Mutation testing framework
*   [hashr (⭐2)](https://github.com/crystal-china/hashr) - A tiny class makes test on JSON response easier
*   [LuckyFlow (⭐55)](https://github.com/luckyframework/lucky_flow) - Automated browser tests similar to Capybara
*   [mass-spec (⭐9)](https://github.com/c910335/mass-spec) - Web API testing library
*   [microtest (⭐32)](https://github.com/Ragmaanir/microtest) - Small opinionated testing library focusing on power asserts
*   [minitest.cr (⭐151)](https://github.com/ysbaddaden/minitest.cr) - Library for unit tests and assertions
*   [mocks.cr (⭐55)](https://github.com/waterlink/mocks.cr) - Mocking library for Crystal
*   [selenium.cr (⭐26)](https://github.com/crystal-loot/selenium.cr) - Selenium client for interacting with web pages for browser automation
*   [Spec](https://crystal-lang.org/api/Spec.html) - spec framework (Crystal stdlib)
*   [spectator](https://gitlab.com/arctic-fox/spectator) - Feature rich spec framework that uses the modern expect syntax
*   [timecop.cr (⭐21)](https://github.com/crystal-community/timecop.cr) - Library for mocking with `Time.now`. Inspired by the [timecop ruby gem (⭐3.4k)](https://github.com/travisjeffery/timecop)
*   [vcr (⭐59)](https://github.com/spoved/vcr.cr) - A HTTP capture and replay implementation for crystal
*   [webdriver\_pump (⭐5)](https://github.com/bwilczek/webdriver_pump) - Page Object library. Inspired by Ruby's [WatirPump (⭐16)](https://github.com/bwilczek/watir_pump)
*   [webmock.cr (⭐109)](https://github.com/manastech/webmock.cr) - Library for stubbing `HTTP::Client` requests

## Third-party APIs

*   [amazonite (⭐1)](https://github.com/rjnienaber/amazonite) - An unofficial SDK supporting popular AWS APIs
*   [aws-signer.cr (⭐13)](https://github.com/beanieboi/aws-signer.cr) - This library signs your HTTP requests using AWS v4
*   [awscr-s3 (⭐89)](https://github.com/taylorfinnell/awscr-s3) - AWS S3 interface
*   [awscr-signer (⭐23)](https://github.com/taylorfinnell/awscr-signer) - Sign HTTP::Request objects and generate presigned post forms
*   [crystal-consul (⭐19)](https://github.com/rogerwelin/crystal-consul) - Consul API client
*   [crystal-darksky (⭐8)](https://github.com/sb89/crystal-darksky) - Wrapper for the [Dark Sky](https://darksky.net) API
*   [crystal-swapi (⭐5)](https://github.com/sb89/crystal-swapi) - Star Wars API (SWAPI) wrapper
*   [crystal\_slack (⭐19)](https://github.com/manastech/crystal_slack) - A tool that parses Slack slash commands or send incoming web hooks
*   [GDAX (⭐7)](https://github.com/mccallofthewild/gdax) - GDAX REST and WebSocket API Wrapper with request signing
*   [gitlab.cr (⭐30)](https://github.com/icyleaf/gitlab.cr) - GitLab API wrapper
*   [google (⭐25)](https://github.com/PlaceOS/google) - Google API wrapper
*   [host\_meta (⭐3)](https://github.com/toddsundsted/host_meta) - A Web Host Metadata (<https://tools.ietf.org/html/rfc6415>) client
*   [kube-client.cr (⭐22)](https://github.com/spoved/kube-client.cr) - Kubernetes API Client
*   [mixpanel-crystal (⭐0)](https://github.com/petoem/mixpanel-crystal) - A library for sending events to Mixpanel
*   [mollie.cr (⭐22)](https://github.com/wout/mollie.cr) - [Mollie](https://www.mollie.com/en/) Payments API wrapper (Creditcard, PayPal, Apple Pay, Sofort, Klarna, ...)
*   [office365 (⭐11)](https://github.com/PlaceOS/office365) - Microsoft Graph API wrapper
*   [pinboard.cr (⭐7)](https://github.com/oz/pinboard.cr) - [Pinboard](https://pinboard.in) API
*   [raven.cr (⭐130)](https://github.com/sija/raven.cr) - Raven is a client for [Sentry (⭐43k)](https://github.com/getsentry/sentry)
*   [stripe.cr (⭐52)](https://github.com/confact/stripe.cr) - Stripe api wrapper
*   [tmdb.cr (⭐4)](https://github.com/mmacia/tmdb.cr) - The Movie DB (TMDb) api wrapper
*   [twitter-crystal (⭐82)](https://github.com/sferik/twitter-crystal) - A library to access the Twitter API
*   [web\_finger (⭐9)](https://github.com/toddsundsted/web_finger) - A WebFinger (<https://tools.ietf.org/html/rfc7033>) client
*   [ynab.cr (⭐4)](https://github.com/jaredsmithse/ynab.cr) - A library to interact with your YNAB data

## Validation

*   [accord (⭐26)](https://github.com/neovintage/accord) - Shareable validation library for Crystal Objects
*   [Athena Validator (⭐7)](https://github.com/athena-framework/validator) - Robust & flexible validation framework
*   [validations (⭐13)](https://github.com/vladfaust/validations.cr) - Validations mixin
*   [validator (⭐30)](https://github.com/Nicolab/crystal-validator) - Data check and validation

## Web Frameworks

*   [amber (⭐2.6k)](https://github.com/amberframework/amber) - Open source efficient and cohesive web application framework
*   [Athena (⭐230)](https://github.com/athena-framework/athena) - A web framework comprised of reusable, independent components
*   [grip (⭐292)](https://github.com/grip-framework/grip) - The microframework for writing powerful web applications
*   [kemal (⭐3.8k)](https://github.com/kemalcr/kemal) - Lightning Fast, Super Simple web framework. Inspired by Sinatra
*   [lucky (⭐2.7k)](https://github.com/luckyframework/lucky) - Catch bugs early, forget about most performance issues, and spend more time on code instead of debugging and writing tests
*   [marten (⭐467)](https://github.com/martenframework/marten) - A web framework that makes building web applications easy, productive, and fun
*   [runcobo (⭐51)](https://github.com/runcobo/runcobo) - An api framework with simple, intuitive and consistent DSL, using jbuilder to render json
*   [Shivneri (⭐23)](https://github.com/ujjwalguptaofficial/shivneri) - Component based MVC web framework for crystal targeting good code structures, modularity & performance
*   [spider-gazelle (⭐190)](https://github.com/spider-gazelle/spider-gazelle) - A Rails esque web framework with a focus on speed and extensibility

# Community

*   [Crystal Forum](https://forum.crystal-lang.org/)
*   [Crystal newsletter](https://crystal-lang.org/#newsletter)
*   [Gitter](https://gitter.im/crystal-lang/crystal)
*   [IRC](ircs://irc.libera.chat:6697#crystal-lang) - #crystal-lang on Libera
*   [Reddit](https://www.reddit.com/r/crystal_programming/)
*   [Stackoverflow](https://stackoverflow.com/tags/crystal-lang/info)

## Unofficial

*   [Crystal Programming Discord Server](https://discord.gg/YS7YvQy) - Unofficial Discord server dedicated to the Crystal Programming Language
*   [Portuguese-speaking Telegram Group](https://t.me/crystalbrasil) - Bem vindos ao Crystal Brasil!
*   [Russian-speaking Telegram Group](https://t.me/crystal_ru) - Добро пожаловать, товарищ!

# Resources

*   [Crystal for Rubyists](http://www.crystalforrubyists.com/) - Free book to bootstrap your Crystal journey
*   [Crystal Shards for Ruby Gems (⭐20k)](https://github.com/crystal-lang/crystal/wiki/Crystal-Shards-for-Ruby-Gems) - A list of Ruby Gems and their Crystal Shards equivalents
*   [crystal-koans (⭐53)](https://github.com/ilmanzo/crystal-koans) - Learn Crystal by writing unit tests
*   [crystal-lang.org](https://crystal-lang.org) - Official language site
*   [devdocs.io](https://devdocs.io/crystal/) - API Documentation Browser with Crystal support
*   [Learn X in Y minutes](https://learnxinyminutes.com/docs/crystal/) - Quick tutorial on Crystal
*   [Programming Crystal](https://pragprog.com/book/crystal/programming-crystal) - PragProg book to start your Crystal journey
*   [Usability of Programming Languages](https://gergelyk.github.io/prog-lang-usability/) - Comparison of Python, Rust, Crystal

## Official Documentation Translations

*   [br.crystal-lang.org](http://br.crystal-lang.org/) - Brazilian
*   [ja.crystal-lang.org](http://ja.crystal-lang.org/) - Japanese
*   [kr.crystal-lang.org](https://kr.crystal-lang.org/) - Korean
*   [ru.crystal-lang.org](http://ru.crystal-lang.org/) - Russian
*   [tw.crystal-lang.org](http://tw.crystal-lang.org/) - Chinese Traditional

# Services and Apps

*   [carc.in](https://carc.in/) - A web service that runs your code and displays the result
*   [Crank (⭐52)](https://github.com/arktisklada/crank) - A Procfile-based application manager (like Foreman)
*   [cry (⭐34)](https://github.com/elorest/cry) - Ability to execute crystal code in a fashion similar to Ruby's pry edit
*   [DeBot (⭐36)](https://github.com/jhass/DeBot) - IRC bot written in Crystal
*   [icr (⭐506)](https://github.com/crystal-community/icr) - Interactive console for Crystal (like IRB for Ruby)
*   [Invidious (⭐19k)](https://github.com/iv-org/invidious) - Invidious is an alternative front-end to YouTube
*   [mpngin (⭐35)](https://github.com/thewalkingtoast/mpngin) - A URL shortener with simple stats
*   [procodile (⭐11)](https://github.com/crystal-china/procodile) - Run processes in the background (and foreground) on Mac & Linux from a Procfile (for production and/or development environments)
*   [quicktype](https://quicktype.io/) - Generate models and serializers from JSON, JSON Schema, GraphQL, and TypeScript
*   [shards.info](http://shards.info/) - Web service that lists all repositories on GitHub that have Crystal code in them. The sources are available on [GitHub (⭐45)](https://github.com/mamantoha/shards-info)

# Tools

*   [ast\_helper (⭐25)](https://github.com/bcardiff/crystal-ast-helper) - Helper tool to debug parser and formatter
*   [crystal-base (⭐2)](https://github.com/ruivieira/crystal-base) - CentOS base docker image for Crystal development
*   [crystal-dash-docset (⭐19)](https://github.com/Sija/crystal-dash-docset) - [Dash](https://kapeli.com/dash) docset generator
*   [port\_ruby\_to\_crystal (⭐10)](https://github.com/crystal-china/port_ruby_to_crystal) - A regex replace ruby script for port ruby code to crystal easier, reduce friction
*   [public\_suffix (⭐2)](https://github.com/toddsundsted/public_suffix) - A small library designed to make the Public Suffix List (<https://publicsuffix.org/>) easier to use

## DevOps

*   [ansible-crystal (⭐9)](https://github.com/CorbanR/ansible-crystal) - Ansible playbook for installing crystal
*   [DPPM (⭐119)](https://github.com/DFabric/dppm) - An easy, universal way to install and manage applications as packages (mostly Linux)

## Editor Plugins

*   Acme:
    *   [acmecrystal (⭐6)](https://github.com/ilanpillemer/acmecrystal) - Reformats crystal code in acme
*   Atom
    *   [crystal-tools](https://atom.io/packages/crystal-tools) - Enables built in tools in Crystal compiler
    *   [language-crystal-actual](https://atom.io/packages/language-crystal-actual) - Crystal language support in Atom
*   Emacs
    *   [crystal-mode](https://melpa.org/#/crystal-mode) - Crystal language support for Emacs ([crystal-lang-tools/emacs-crystal-mode (⭐53)](https://github.com/crystal-lang-tools/emacs-crystal-mode))
*   Geany
    *   [geany-crystal (⭐9)](https://github.com/crystal-lang-tools/geany-crystal) - Crystal support for the [Geany editor](https://www.geany.org/)
*   IntelliJ IDEA
    *   [intellij-crystal-lang (⭐40)](https://github.com/asedunov/intellij-crystal-lang) - Crystal support for the JetBrains IDEs
*   Lite-XL
    *   [lite-plugin-crystal (⭐6)](https://github.com/Tamnac/lite-plugin-crystal) - Crystal support for the [Lite-XL](https://lite-xl.com/en/) editor
*   Spacemacs
    *   [crystal-spacemacs-layer (⭐12)](https://github.com/juanedi/crystal-spacemacs-layer) - Spacemacs contribution layer for Crystal
*   Sublime
    *   [sublime-crystal (⭐89)](https://github.com/crystal-lang-tools/sublime-crystal) - Crystal syntax highlighting for sublime Text
*   TextMate
    *   [Crystal.tmbundle (⭐19)](https://github.com/crystal-lang-tools/Crystal.tmbundle) - Crystal syntax highlighting, compile, format command, snippets
*   Vim
    *   [vim-crystal (⭐425)](https://github.com/vim-crystal/vim-crystal) - Vim filetype support for Crystal
    *   [vim-slang (⭐13)](https://github.com/elorest/vim-slang) - Vim filetype support for Slang Templating Engine
*   Visual Studio Code
    *   [vscode-crystal-lang (⭐300)](https://github.com/crystal-lang-tools/vscode-crystal-lang) - Formatter, linter and syntax highlighting for `cr` and `ecr` files

## LSP Language Server Protocol Implementations

*   [crystalline (⭐509)](https://github.com/elbywan/crystalline) - Crystalline is an implementation of the Language Server Protocol written in and for the Crystal Language
*   [scry (⭐331)](https://github.com/crystal-lang-tools/scry) - Code analysis server for Crystal implementing the [Language Server Protocol](https://microsoft.github.io/language-server-protocol/)

## Shell plugins

*   [crun (⭐47)](https://github.com/Val/crun) - Crystal Run : shebang wrapper for Crystal
*   [crystal-zsh (⭐27)](https://github.com/veelenga/crystal-zsh) - .oh-my-zsh plugin

