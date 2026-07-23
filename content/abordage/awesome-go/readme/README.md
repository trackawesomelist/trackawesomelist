# Awesome Go Overview

Structured collection of Go frameworks, libraries, tools, and resources. Automatically maintained and up-to-date with metadata, filtering, and comprehensive categorization.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/abordage/awesome-go/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 abordage/awesome-go](https://github.com/abordage/awesome-go) · ⭐ 4 · 🏷️ Programming Languages

[ [Daily](/content/abordage/awesome-go/README.md) / [Weekly](/content/abordage/awesome-go/week/README.md) / Overview ]

---

# Awesome Go

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-go?label=last%20update)](https://github.com/abordage/awesome-go/blob/main/README.md/README.md)
![Repositories](https://img.shields.io/badge/repositories-1,145-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-4,998,185-gold)
[![License](https://img.shields.io/github/license/abordage/awesome-go)](https://github.com/abordage/awesome-go/blob/main/README.md/LICENSE)

**Automated. Curated. Ranked.**

Go libraries, tools, and applications from the community. This awesome list is automatically maintained with daily GitHub API updates. Projects are re-ranked daily based on current activity metrics.

**Daily process:** Merge community PRs → Scan repos → Filter stale projects → Recalculate scores → Rebuild list

*   [AI & Machine Learning](#ai--machine-learning)
    *   [AI APIs](#ai-apis)
    *   [Artificial Intelligence](#artificial-intelligence)
    *   [Machine Learning](#machine-learning)
*   [Audio & Video](#audio--video)
    *   [Audio](#audio)
    *   [Images](#images)
    *   [Video](#video)
*   [Auth](#auth)
    *   [Authentication](#authentication)
    *   [Authorization](#authorization)
*   [Bots & Chat](#bots--chat)
    *   [Bot Frameworks](#bot-frameworks)
    *   [Chat APIs](#chat-apis)
*   [CLI & Terminal](#cli--terminal)
    *   [Advanced Console UIs](#advanced-console-uis)
    *   [Standard CLI](#standard-cli)
*   [Concurrency](#concurrency)
    *   [Actor Model](#actor-model)
    *   [Goroutines](#goroutines)
    *   [Stream Processing](#stream-processing)
*   [Configuration](#configuration)
*   [Data Formats](#data-formats)
    *   [JSON](#json)
    *   [Serialization](#serialization)
    *   [XML](#xml)
*   [Data Structures](#data-structures)
    *   [Bit-packing and Compression](#bit-packing-and-compression)
    *   [Bloom and Cuckoo Filters](#bloom-and-cuckoo-filters)
    *   [Maps](#maps)
    *   [Miscellaneous](#miscellaneous)
    *   [Queues](#queues)
*   [Databases](#databases)
    *   [Caches](#caches)
    *   [Database Schema Migration](#database-schema-migration)
    *   [Database Tools](#database-tools)
    *   [Databases Implemented in Go](#databases-implemented-in-go)
    *   [Distributed Storage](#distributed-storage)
    *   [Interfaces to Multiple Backends](#interfaces-to-multiple-backends)
    *   [NoSQL Database Drivers](#nosql-database-drivers)
    *   [ORM](#orm)
    *   [Query Language](#query-language)
    *   [Relational Database Drivers](#relational-database-drivers)
    *   [SQL Query Builders](#sql-query-builders)
    *   [Search and Analytic Databases](#search-and-analytic-databases)
*   [DevOps & Build](#devops--build)
    *   [Backup](#backup)
    *   [Build Automation](#build-automation)
    *   [CI/CD](#cicd)
    *   [Containers](#containers)
    *   [DevOps Utilities](#devops-utilities)
    *   [Infrastructure](#infrastructure)
    *   [Kubernetes](#kubernetes)
    *   [Load Testing](#load-testing)
*   [Email](#email)
*   [Finance & Blockchain](#finance--blockchain)
    *   [Blockchain](#blockchain)
    *   [Financial](#financial)
    *   [Payment APIs](#payment-apis)
*   [GUI & Desktop](#gui--desktop)
    *   [GUI](#gui)
    *   [Windows](#windows)
*   [Game Development](#game-development)
    *   [Game Engines](#game-engines)
    *   [OpenGL](#opengl)
*   [Geospatial](#geospatial)
*   [Go Tooling](#go-tooling)
    *   [Compilers](#compilers)
    *   [Editor Plugins](#editor-plugins)
    *   [Generate Tools](#generate-tools)
    *   [Go Tools](#go-tools)
*   [Hardware & IoT](#hardware--iot)
    *   [Hardware](#hardware)
    *   [IoT](#iot)
*   [Networking](#networking)
    *   [Consensus](#consensus)
    *   [DNS](#dns)
    *   [Distributed Utilities](#distributed-utilities)
    *   [HTTP & Proxy](#http--proxy)
    *   [HTTP Clients](#http-clients)
    *   [Servers](#servers)
    *   [Network Utilities](#network-utilities)
    *   [P2P & Torrent](#p2p--torrent)
    *   [Protocols](#protocols)
    *   [RPC](#rpc)
    *   [SSH & SFTP](#ssh--sftp)
    *   [TCP/UDP Frameworks](#tcpudp-frameworks)
    *   [VPN & Tunneling](#vpn--tunneling)
*   [Queues & Pub/Sub](#queues--pubsub)
    *   [Brokers](#brokers)
    *   [Clients & Libraries](#clients--libraries)
*   [Science](#science)
*   [Scripting](#scripting)
    *   [Embeddable Languages](#embeddable-languages)
    *   [Code Generators](#code-generators)
*   [Security](#security)
    *   [Certificates](#certificates)
    *   [Cryptography](#cryptography)
    *   [WAF & Protection](#waf--protection)
    *   [Zero Trust](#zero-trust)
*   [Testing & Quality](#testing--quality)
    *   [Benchmarks](#benchmarks)
    *   [Code Analysis](#code-analysis)
    *   [Mock](#mock)
    *   [Performance](#performance)
    *   [Browser Automation](#browser-automation)
    *   [Testing Frameworks](#testing-frameworks)
    *   [Testing Utilities](#testing-utilities)
    *   [Validation](#validation)
*   [Text & NLP](#text--nlp)
    *   [Formatters](#formatters)
    *   [Markup Languages](#markup-languages)
    *   [Miscellaneous](#miscellaneous)
    *   [Morphological Analyzers](#morphological-analyzers)
    *   [Parsers/Encoders/Decoders](#parsersencodersdecoders)
    *   [Scrapers](#scrapers)
    *   [Text Analysis](#text-analysis)
    *   [Tokenizers](#tokenizers)
    *   [Translation](#translation)
*   [Third-party APIs](#third-party-apis)
    *   [Cloud Provider APIs](#cloud-provider-apis)
    *   [Other APIs](#other-apis)
    *   [Productivity APIs](#productivity-apis)
*   [Utilities](#utilities)
    *   [Build & Release](#build--release)
    *   [CLI Tools](#cli-tools)
    *   [Data Conversion](#data-conversion)
    *   [Database Extensions](#database-extensions)
    *   [Date and Time](#date-and-time)
    *   [Dependency Injection](#dependency-injection)
    *   [Error Handling](#error-handling)
    *   [File Handling](#file-handling)
    *   [Forms](#forms)
    *   [Functional](#functional)
    *   [General](#general)
    *   [Logging](#logging)
    *   [Networking Utils](#networking-utils)
    *   [Project Layout](#project-layout)
    *   [Resilience & Retry](#resilience--retry)
    *   [Strings](#strings)
    *   [System & Process](#system--process)
    *   [UUID](#uuid)
*   [Version Control & Packages](#version-control--packages)
    *   [Git APIs](#git-apis)
    *   [Package Management](#package-management)
    *   [Version Control](#version-control)
*   [Web Development](#web-development)
    *   [Microservices](#microservices)
    *   [Middlewares](#middlewares)
    *   [Routers](#routers)
    *   [Template Engines](#template-engines)
    *   [Web Frameworks](#web-frameworks)
    *   [WebAssembly](#webassembly)
*   [Workflow & Scheduling](#workflow--scheduling)
    *   [Job Scheduler](#job-scheduler)
    *   [Workflow Frameworks](#workflow-frameworks)

## AI & Machine Learning

### AI APIs

*   [sashabaranov/go-openai (⭐11k)](https://github.com/sashabaranov/go-openai) — OpenAI API client for Go ☆`10,722`
*   [wit-ai/wit-go (⭐170)](https://github.com/wit-ai/wit-go) — Go client for wit.ai HTTP API ☆`171`

### Artificial Intelligence

*   [ollama/ollama (⭐176k)](https://github.com/ollama/ollama) — Run LLMs locally ☆`176,669`
*   [mudler/LocalAI (⭐47k)](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`47,737`
*   [tmc/langchaingo (⭐9.5k)](https://github.com/tmc/langchaingo) — LangChain for Go, the easiest way to write LLM-based programs in Go ☆`9,552`
*   [maximhq/bifrost (⭐6.5k)](https://github.com/maximhq/bifrost) — Fastest LLM gateway for Go ☆`6,708`
*   [philippgille/chromem-go (⭐1k)](https://github.com/philippgille/chromem-go) — Embeddable vector database for Go ☆`1,035`
*   [universal-tool-calling-protocol/go-utcp (⭐119)](https://github.com/universal-tool-calling-protocol/go-utcp) — Official Go implementation of the UTCP ☆`121`
*   [presbrey/ollamafarm (⭐100)](https://github.com/presbrey/ollamafarm) — Manage multiple Ollama instances ☆`100`

### Machine Learning

*   [gorgonia/gorgonia (⭐5.9k)](https://github.com/gorgonia/gorgonia) — Machine learning library for Go ☆`5,923`
*   [otiai10/gosseract (⭐3.1k)](https://github.com/otiai10/gosseract) — OCR using Tesseract in Go ☆`3,123`
*   [gomlx/gomlx (⭐1.5k)](https://github.com/gomlx/gomlx) — GoMLX: An Accelerated Machine Learning Framework For Go ☆`1,485`
*   [jbrukh/bayesian (⭐814)](https://github.com/jbrukh/bayesian) — Naive Bayesian Classification for Golang. ☆`814`
*   [knights-analytics/hugot (⭐622)](https://github.com/knights-analytics/hugot) — Onnx transformer pipelines in Golang ☆`625`
*   [c-bata/goptuna (⭐279)](https://github.com/c-bata/goptuna) — A hyperparameter optimization framework, inspired by Optuna. ☆`279`

## Audio & Video

### Audio

*   [ebitengine/oto (⭐1.9k)](https://github.com/ebitengine/oto) — A low-level library to play sound on multiple platforms ☆`1,941`
*   [gordonklaus/portaudio (⭐840)](https://github.com/gordonklaus/portaudio) — Go bindings for the PortAudio audio I/O library ☆`840`
*   [gen2brain/malgo (⭐416)](https://github.com/gen2brain/malgo) — Mini audio library ☆`417`
*   [mewkiz/flac (⭐357)](https://github.com/mewkiz/flac) — Package flac provides access to FLAC (Free Lossless Audio Codec) streams. ☆`357`
*   [tosone/minimp3 (⭐133)](https://github.com/tosone/minimp3) — Decode mp3 ☆`133`

### Images

*   [hybridgroup/gocv (⭐7.5k)](https://github.com/hybridgroup/gocv) — Computer vision with OpenCV 4 ☆`7,474`
*   [anthonynsimon/bild (⭐4.2k)](https://github.com/anthonynsimon/bild) — Image processing algorithms in pure Go ☆`4,201`
*   [cshum/imagor (⭐4k)](https://github.com/cshum/imagor) — Fast, secure image processing server and Go library, using libvips ☆`3,988`
*   [thoas/picfit (⭐2.3k)](https://github.com/thoas/picfit) — An image resizing server written in Go ☆`2,338`
*   [gographics/imagick (⭐1.9k)](https://github.com/gographics/imagick) — Go binding to ImageMagick's MagickWand C API ☆`1,872`
*   [tdewolff/canvas (⭐1.8k)](https://github.com/tdewolff/canvas) — Vector graphics in Go ☆`1,825`
*   [davidbyttow/govips (⭐1.6k)](https://github.com/davidbyttow/govips) — A lightning fast image processing and resizing library for Go ☆`1,635`
*   [yeqown/go-qrcode (⭐855)](https://github.com/yeqown/go-qrcode) — Customizable QR code generator ☆`856`
*   [HugoSmits86/nativewebp (⭐450)](https://github.com/HugoSmits86/nativewebp) — Native webp encoder for Go ☆`449`
*   [auyer/steganography (⭐356)](https://github.com/auyer/steganography) — LSB steganography in pure Go ☆`355`
*   [kolesa-team/go-webp (⭐315)](https://github.com/kolesa-team/go-webp) — Simple and fast webp library for golang ☆`315`
*   [qmuntal/gltf (⭐286)](https://github.com/qmuntal/gltf) — Go library for encoding glTF 2.0 files ☆`284`
*   [Pixboost/transformimgs (⭐292)](https://github.com/Pixboost/transformimgs) — Open source image CDN. ☆`291`
*   [gojek/darkroom (⭐235)](https://github.com/gojek/darkroom) — Image processing engine and proxy service ☆`235`
*   [ungerik/go-cairo (⭐153)](https://github.com/ungerik/go-cairo) — Go binding for the cairo graphics library ☆`153`
*   [aofei/cameron (⭐132)](https://github.com/aofei/cameron) — An avatar generator for Go. ☆`132`
*   [piglig/go-qr (⭐57)](https://github.com/piglig/go-qr) — A native, high-quality and minimalistic QR code generator and decoder ☆`57`

### Video

*   [asticode/go-astiav (⭐722)](https://github.com/asticode/go-astiav) — Golang ffmpeg and libav C bindings ☆`727`
*   [asticode/go-astisub (⭐701)](https://github.com/asticode/go-astisub) — Manipulate subtitles in Go ☆`701`
*   [Eyevinn/mp4ff (⭐643)](https://github.com/Eyevinn/mp4ff) — MP4/ISOBMFF tools and library ☆`645`
*   [asticode/go-astits (⭐614)](https://github.com/asticode/go-astits) — Demux and mux MPEG Transport Streams (.ts) natively in GO ☆`614`
*   [adrg/libvlc-go (⭐509)](https://github.com/adrg/libvlc-go) — Go bindings for libVLC ☆`509`
*   [Eyevinn/hls-m3u8 (⭐67)](https://github.com/Eyevinn/hls-m3u8) — HLS m3u8 library in Go ☆`67`
*   [jonoton/scout (⭐30)](https://github.com/jonoton/scout) — Video surveillance with motion detection ☆`30`
*   [unki2aut/go-mpd (⭐32)](https://github.com/unki2aut/go-mpd) — MPEG-DASH manifest library ☆`32`

## Auth

### Authentication

*   [golang-jwt/jwt (⭐9.2k)](https://github.com/golang-jwt/jwt) — Go implementation of JSON Web Tokens (JWT). ☆`9,174`
*   [markbates/goth (⭐6.6k)](https://github.com/markbates/goth) — Multi-provider authentication ☆`6,574`
*   [golang/oauth2 (⭐5.9k)](https://github.com/golang/oauth2) — Go OAuth2 ☆`5,876`
*   [aarondl/authboss (⭐4.2k)](https://github.com/aarondl/authboss) — The boss of http auth. ☆`4,197`
*   [alexedwards/scs (⭐2.6k)](https://github.com/alexedwards/scs) — HTTP Session Management for Go ☆`2,600`
*   [lestrrat-go/jwx (⭐2.4k)](https://github.com/lestrrat-go/jwx) — Complete JWx implementation ☆`2,405`
*   [openshift/osin (⭐1.9k)](https://github.com/openshift/osin) — Golang OAuth2 server library ☆`1,934`
*   [dghubble/gologin (⭐2k)](https://github.com/dghubble/gologin) — Go login handlers for authentication providers (OAuth1, OAuth2) ☆`1,959`
*   [zitadel/oidc (⭐1.9k)](https://github.com/zitadel/oidc) — OpenID Connect client and server ☆`1,850`
*   [cristalhq/jwt (⭐690)](https://github.com/cristalhq/jwt) — Safe, simple and fast JSON Web Tokens for Go ☆`690`
*   [shaj13/go-guardian (⭐613)](https://github.com/shaj13/go-guardian) — Authentication library for Go ☆`613`
*   [go-jose/go-jose (⭐520)](https://github.com/go-jose/go-jose) — An implementation of JOSE standards (JWE, JWS, JWT) in Go ☆`523`
*   [abraithwaite/jeff (⭐272)](https://github.com/abraithwaite/jeff) — Jeff provides the simplest way to manage web sessions in Go. ☆`272`
*   [Kwynto/gosession (⭐258)](https://github.com/Kwynto/gosession) — Quick session for net/http ☆`257`
*   [leodip/goiabada (⭐192)](https://github.com/leodip/goiabada) — Goiabada is an OAuth2 / OpenID Connect server written in Go. ☆`192`
*   [jellydator/sessionup (⭐131)](https://github.com/jellydator/sessionup) — Straightforward HTTP session management ☆`132`
*   [brianvoe/sjwt (⭐123)](https://github.com/brianvoe/sjwt) — Simple JWT Golang ☆`123`
*   [icza/session (⭐119)](https://github.com/icza/session) — Session management for web servers ☆`119`
*   [essentialkaos/branca (⭐100)](https://github.com/essentialkaos/branca) — Encrypted API tokens ☆`100`
*   [mengzhuo/cookiestxt (⭐24)](https://github.com/mengzhuo/cookiestxt) — cookiestxt implement parser of cookies txt format ☆`24`

### Authorization

*   [apache/casbin (⭐20k)](https://github.com/apache/casbin) — Authorization library for Go ☆`20,277`
*   [openfga/openfga (⭐5.4k)](https://github.com/openfga/openfga) — Fine-grained authorization server ☆`5,482`
*   [ory/keto (⭐5.4k)](https://github.com/ory/keto) — Customizable permission server ☆`5,375`
*   [cerbos/cerbos (⭐4.5k)](https://github.com/cerbos/cerbos) — Open core authorization layer ☆`4,499`

## Bots & Chat

### Bot Frameworks

*   [tucnak/telebot (⭐4.6k)](https://github.com/tucnak/telebot) — Telebot is a Telegram bot framework in Go. ☆`4,634`
*   [go-telegram/bot (⭐1.8k)](https://github.com/go-telegram/bot) — Telegram Bot API Go framework ☆`1,782`
*   [mymmrac/telego (⭐1k)](https://github.com/mymmrac/telego) — Telegram Bot API library for Go ☆`1,052`
*   [diamondburned/arikawa (⭐596)](https://github.com/diamondburned/arikawa) — A Golang library and framework for the Discord API. ☆`596`
*   [NicoNex/echotron (⭐442)](https://github.com/NicoNex/echotron) — An elegant and concurrent library for the Telegram bot API in Go. ☆`443`
*   [gempir/go-twitch-irc (⭐398)](https://github.com/gempir/go-twitch-irc) — go irc client for twitch.tv ☆`398`
*   [innogames/slack-bot (⭐209)](https://github.com/innogames/slack-bot) — Slack bot for Jenkins, Jira, PRs ☆`209`
*   [mr-linch/go-tg (⭐136)](https://github.com/mr-linch/go-tg) — Telegram Bot API client ☆`136`
*   [slack-io/slacker (⭐60)](https://github.com/slack-io/slacker) — Slack Bot Framework ☆`60`
*   [onrik/micha (⭐34)](https://github.com/onrik/micha) — Client lib for Telegram bot api ☆`34`

### Chat APIs

*   [bwmarrin/discordgo (⭐6k)](https://github.com/bwmarrin/discordgo) — (Golang) Go bindings for Discord ☆`5,966`
*   [slack-go/slack (⭐5k)](https://github.com/slack-go/slack) — Slack API in Go ☆`4,953`
*   [huandu/facebook (⭐1.5k)](https://github.com/huandu/facebook) — A Facebook Graph API SDK For Go. ☆`1,474`
*   [chyroc/lark (⭐474)](https://github.com/chyroc/lark) — Lark/Feishu Open API SDK ☆`475`
*   [go-lark/lark (⭐247)](https://github.com/go-lark/lark) — Feishu/Lark SDK for Go ☆`246`
*   [switchupcb/disgo (⭐114)](https://github.com/switchupcb/disgo) — Next-gen Discord API library ☆`115`

## CLI & Terminal

### Advanced Console UIs

*   [charmbracelet/bubbletea (⭐44k)](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`43,880`
*   [antonmedv/fx (⭐21k)](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,544`
*   [gizak/termui (⭐14k)](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,577`
*   [charmbracelet/lipgloss (⭐12k)](https://github.com/charmbracelet/lipgloss) — Style definitions for nice terminal layouts ☆`11,598`
*   [jroimartin/gocui (⭐11k)](https://github.com/jroimartin/gocui) — Minimalist Go package aimed at creating Console User Interfaces. ☆`10,593`
*   [charmbracelet/bubbles (⭐8.7k)](https://github.com/charmbracelet/bubbles) — TUI components for Bubble Tea ☆`8,704`
*   [pterm/pterm (⭐5.5k)](https://github.com/pterm/pterm) — Modern terminal output library ☆`5,505`
*   [c-bata/go-prompt (⭐5.5k)](https://github.com/c-bata/go-prompt) — Interactive prompts for Go ☆`5,488`
*   [schollz/progressbar (⭐4.7k)](https://github.com/schollz/progressbar) — Thread-safe progress bar ☆`4,691`
*   [guptarohit/asciigraph (⭐3.1k)](https://github.com/guptarohit/asciigraph) — ASCII line graphs in terminal ☆`3,079`
*   [mum4k/termdash (⭐3k)](https://github.com/mum4k/termdash) — Terminal-based dashboard ☆`3,023`
*   [vbauerster/mpb (⭐2.5k)](https://github.com/vbauerster/mpb) — Multi progress bar ☆`2,504`
*   [briandowns/spinner (⭐2.5k)](https://github.com/briandowns/spinner) — Terminal spinner indicators ☆`2,527`
*   [muesli/termenv (⭐2k)](https://github.com/muesli/termenv) — Terminal color support ☆`2,014`
*   [gookit/color (⭐1.6k)](https://github.com/gookit/color) — Terminal color rendering ☆`1,601`
*   [logrusorgru/aurora (⭐1.5k)](https://github.com/logrusorgru/aurora) — ANSI colors for Printf ☆`1,493`
*   [mattn/go-isatty (⭐919)](https://github.com/mattn/go-isatty) — Check if terminal is TTY ☆`920`
*   [mattn/go-colorable (⭐814)](https://github.com/mattn/go-colorable) — Colorable writer for Windows ☆`812`
*   [box-cli-maker/box-cli-maker (⭐645)](https://github.com/box-cli-maker/box-cli-maker) — Render highly customizable boxes in the terminal ☆`646`
*   [Evertras/bubble-table (⭐576)](https://github.com/Evertras/bubble-table) — Table component for Bubble Tea ☆`576`
*   [DMcP89/tinycare-tui (⭐21)](https://github.com/DMcP89/tinycare-tui) — TUI application written in GO inspired by tiny-care-terminal ☆`21`

### Standard CLI

*   [spf13/cobra (⭐44k)](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`44,305`
*   [urfave/cli (⭐24k)](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`24,174`
*   [elves/elvish (⭐6.3k)](https://github.com/elves/elvish) — Scripting shell for Go ☆`6,337`
*   [alecthomas/kingpin (⭐3.6k)](https://github.com/alecthomas/kingpin) — Command-line parser ☆`3,566`
*   [dnote/dnote (⭐3k)](https://github.com/dnote/dnote) — Command-line notebook ☆`3,047`
*   [spf13/pflag (⭐2.8k)](https://github.com/spf13/pflag) — POSIX/GNU-style flags ☆`2,753`
*   [jessevdk/go-flags (⭐2.7k)](https://github.com/jessevdk/go-flags) — Command-line option parser ☆`2,698`
*   [alexflint/go-arg (⭐2.3k)](https://github.com/alexflint/go-arg) — Struct-based argument parsing ☆`2,269`
*   [carapace-sh/carapace-bin (⭐1.9k)](https://github.com/carapace-sh/carapace-bin) — Multi-shell completion binary ☆`1,896`
*   [nanovms/ops (⭐1.5k)](https://github.com/nanovms/ops) — Build and run unikernels ☆`1,502`
*   [carapace-sh/carapace (⭐1.4k)](https://github.com/carapace-sh/carapace) — Multi-shell completion library ☆`1,376`
*   [ddddddO/gtree (⭐356)](https://github.com/ddddddO/gtree) — Generate ASCII tree from Markdown ☆`356`
*   [urfave/sflags (⭐168)](https://github.com/urfave/sflags) — Generate flags from structs ☆`168`
*   [reeflective/readline (⭐144)](https://github.com/reeflective/readline) — Shell library with inputrc ☆`146`
*   [hedzr/cmdr (⭐141)](https://github.com/hedzr/cmdr) — POSIX-compliant CLI parser ☆`141`
*   [reeflective/console (⭐113)](https://github.com/reeflective/console) — Console library for Cobra ☆`114`
*   [hashicorp/cli (⭐42)](https://github.com/hashicorp/cli) — CLI library for Go ☆`42`
*   [dixonwille/wlog (⭐67)](https://github.com/dixonwille/wlog) — Cross-platform logging ☆`67`
*   [DavidGamba/go-getoptions (⭐60)](https://github.com/DavidGamba/go-getoptions) — Command line option parser with completion ☆`60`
*   [nyaosorg/go-readline-ny (⭐36)](https://github.com/nyaosorg/go-readline-ny) — Readline for Go ☆`36`
*   [carapace-sh/carapace-spec (⭐34)](https://github.com/carapace-sh/carapace-spec) — Multi-shell completion library ☆`34`
*   [jxskiss/mcli (⭐47)](https://github.com/jxskiss/mcli) — Minimal but powerful CLI ☆`47`
*   [sgreben/flagvar (⭐48)](https://github.com/sgreben/flagvar) — CLI argument types for flag ☆`48`

## Concurrency

### Actor Model

*   [asynkron/protoactor-go (⭐5.5k)](https://github.com/asynkron/protoactor-go) — Ultra fast distributed actors for Go ☆`5,480`
*   [ergo-services/ergo (⭐4.6k)](https://github.com/ergo-services/ergo) — Actor framework with network transparency ☆`4,618`
*   [anthdm/hollywood (⭐2.3k)](https://github.com/anthdm/hollywood) — Blazingly fast and light-weight Actor engine written in Golang ☆`2,316`
*   [Tochemey/goakt (⭐361)](https://github.com/Tochemey/goakt) — Distributed actor framework ☆`364`

### Goroutines

*   [panjf2000/ants (⭐14k)](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,468`
*   [benmanns/goworker (⭐2.8k)](https://github.com/benmanns/goworker) — Resque-compatible background worker ☆`2,847`
*   [alitto/pond (⭐2.2k)](https://github.com/alitto/pond) — High-performance worker pool ☆`2,173`
*   [destel/rill (⭐1.8k)](https://github.com/destel/rill) — Channel-based concurrency toolkit ☆`1,845`
*   [xxjwxc/gowp (⭐516)](https://github.com/xxjwxc/gowp) — Goroutine worker pool ☆`516`
*   [earthboundkid/flowmatic (⭐402)](https://github.com/earthboundkid/flowmatic) — Structured concurrency ☆`402`
*   [vladopajic/go-actor (⭐301)](https://github.com/vladopajic/go-actor) — Actor model library ☆`303`
*   [timandy/routine (⭐292)](https://github.com/timandy/routine) — ThreadLocal for Go ☆`292`
*   [reugn/async (⭐309)](https://github.com/reugn/async) — Async computation package ☆`309`
*   [mborders/artifex (⭐214)](https://github.com/mborders/artifex) — In-memory job queue ☆`214`

### Stream Processing

*   [reugn/go-streams (⭐2.2k)](https://github.com/reugn/go-streams) — Stream processing library ☆`2,173`
*   [Breeze0806/go-etl (⭐190)](https://github.com/Breeze0806/go-etl) — ETL toolset for Go ☆`191`
*   [mariomac/gostream (⭐172)](https://github.com/mariomac/gostream) — Java Streams port for Go ☆`172`
*   [fulminate-io/machine (⭐169)](https://github.com/fulminate-io/machine) — Machine is a workflow/pipeline library for processing data ☆`169`
*   [rulego/streamsql (⭐61)](https://github.com/rulego/streamsql) — SQL-based stream processing for IoT ☆`61`

## Configuration

*   [spf13/viper (⭐30k)](https://github.com/spf13/viper) — Go configuration with fangs ☆`30,374`
*   [caarlos0/env (⭐6.3k)](https://github.com/caarlos0/env) — Parse environment variables to structs ☆`6,269`
*   [knadh/koanf (⭐4.1k)](https://github.com/knadh/koanf) — Lightweight config management ☆`4,125`
*   [alecthomas/kong (⭐3.1k)](https://github.com/alecthomas/kong) — Command-line parser for Go ☆`3,141`
*   [adrg/xdg (⭐1k)](https://github.com/adrg/xdg) — XDG Base Directory implementation ☆`1,009`
*   [cristalhq/aconfig (⭐635)](https://github.com/cristalhq/aconfig) — Simple config loader ☆`637`
*   [gookit/config (⭐585)](https://github.com/gookit/config) — Config management with formats ☆`585`
*   [nil-go/konf (⭐391)](https://github.com/nil-go/konf) — Simplest config loader for Go ☆`391`
*   [kkyr/fig (⭐383)](https://github.com/kkyr/fig) — Minimalist config library ☆`382`
*   [hjson/hjson-go (⭐357)](https://github.com/hjson/hjson-go) — Hjson for Go ☆`356`
*   [vrischmann/envconfig (⭐250)](https://github.com/vrischmann/envconfig) — Env config library ☆`250`
*   [chaindead/zerocfg (⭐200)](https://github.com/chaindead/zerocfg) — Zero-effort config management ☆`200`
*   [beatlabs/harvester (⭐135)](https://github.com/beatlabs/harvester) — Watch and notify config changes ☆`135`
*   [BoRuDar/configuration (⭐107)](https://github.com/BoRuDar/configuration) — Set struct fields from env, flags, files ☆`107`
*   [omeid/uconfig (⭐75)](https://github.com/omeid/uconfig) — Lightweight config management ☆`75`
*   [gurkankaymak/hocon (⭐93)](https://github.com/gurkankaymak/hocon) — HOCON config library for Go ☆`93`
*   [PaddleHQ/go-aws-ssm (⭐66)](https://github.com/PaddleHQ/go-aws-ssm) — AWS System Manager interface ☆`66`
*   [go-simpler/env (⭐80)](https://github.com/go-simpler/env) — Load env vars to struct ☆`80`
*   [num30/config (⭐61)](https://github.com/num30/config) — Declarative configuration ☆`61`
*   [wkhere/bcl (⭐34)](https://github.com/wkhere/bcl) — Basic Configuration Language ☆`34`
*   [sakirsensoy/genv (⭐45)](https://github.com/sakirsensoy/genv) — Easy env variable handling ☆`45`
*   [greencoda/confiq (⭐41)](https://github.com/greencoda/confiq) — Config struct decoder ☆`40`
*   [dsbasko/go-cfg (⭐49)](https://github.com/dsbasko/go-cfg) — Unified config reading ☆`48`
*   [nasermirzaei89/env (⭐23)](https://github.com/nasermirzaei89/env) — Zero-dep env package ☆`23`
*   [deatil/go-array (⭐23)](https://github.com/deatil/go-array) — Read/set map, slice, JSON data ☆`23`
*   [romshark/yamagiconf (⭐20)](https://github.com/romshark/yamagiconf) — YAML config framework ☆`19`
*   [atelpis/enflag (⭐38)](https://github.com/atelpis/enflag) — Unify env and flag parsing ☆`39`

## Data Formats

### JSON

*   [tidwall/gjson (⭐16k)](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,545`
*   [bytedance/sonic (⭐9.5k)](https://github.com/bytedance/sonic) — A blazingly fast JSON serializing & deserializing library ☆`9,551`
*   [valyala/fastjson (⭐2.5k)](https://github.com/valyala/fastjson) — Fast JSON parser for Go ☆`2,463`
*   [ohler55/ojg (⭐952)](https://github.com/ohler55/ojg) — Optimized JSON for Go ☆`951`
*   [wI2L/jsondiff (⭐629)](https://github.com/wI2L/jsondiff) — JSON Patch diff computation ☆`630`
*   [spyzhov/ajson (⭐290)](https://github.com/spyzhov/ajson) — Abstract JSON with JSONPath ☆`289`
*   [Andrew-M-C/go.jsonvalue (⭐203)](https://github.com/Andrew-M-C/go.jsonvalue) — Unstructured JSON solution ☆`203`
*   [iOliverNguyen/ujson (⭐85)](https://github.com/iOliverNguyen/ujson) — Minimal JSON parser ☆`85`
*   [simonnilsson/ask (⭐58)](https://github.com/simonnilsson/ask) — A Go package that provides a simple way of accessing nested properties in maps and slices. ☆`58`
*   [neilotoole/jsoncolor (⭐54)](https://github.com/neilotoole/jsoncolor) — Colorized JSON output ☆`54`

### Serialization

*   [golang/protobuf (⭐10k)](https://github.com/golang/protobuf) — Protocol buffers for Go ☆`10,082`
*   [ugorji/go (⭐2k)](https://github.com/ugorji/go) — Codec for msgpack, cbor, json ☆`1,956`
*   [linkedin/goavro (⭐1.1k)](https://github.com/linkedin/goavro) — Goavro is a library that encodes and decodes Avro data. ☆`1,065`
*   [fxamacker/cbor (⭐1.1k)](https://github.com/fxamacker/cbor) — CBOR codec with extensions ☆`1,070`
*   [jszwec/csvutil (⭐1k)](https://github.com/jszwec/csvutil) — CSV to struct mapping ☆`1,033`
*   [ghostiam/binstruct (⭐114)](https://github.com/ghostiam/binstruct) — Binary to struct decoder ☆`114`
*   [csweichel/bel (⭐46)](https://github.com/csweichel/bel) — Generate TypeScript from Go ☆`46`
*   [o1egl/fwencoder (⭐27)](https://github.com/o1egl/fwencoder) — Fixed width file parser ☆`27`
*   [tiendc/go-csvlib (⭐18)](https://github.com/tiendc/go-csvlib) — High-level CSV library ☆`18`

### XML

*   [miku/zek (⭐821)](https://github.com/miku/zek) — Generate Go struct from XML ☆`820`
*   [antchfx/xpath (⭐742)](https://github.com/antchfx/xpath) — XPath for Go ☆`743`
*   [antchfx/xmlquery (⭐490)](https://github.com/antchfx/xmlquery) — XPath XML query ☆`490`

## Data Structures

### Bit-packing and Compression

*   [RoaringBitmap/roaring (⭐2.9k)](https://github.com/RoaringBitmap/roaring) — Compressed bitmaps for Go ☆`2,918`
*   [iancmcc/bingo (⭐52)](https://github.com/iancmcc/bingo) — Zero-allocation binary encoding ☆`52`

### Bloom and Cuckoo Filters

*   [bits-and-blooms/bloom (⭐2.8k)](https://github.com/bits-and-blooms/bloom) — Bloom filter implementation ☆`2,799`
*   [tylertreat/BoomFilters (⭐1.6k)](https://github.com/tylertreat/BoomFilters) — Probabilistic data structures for streams ☆`1,646`
*   [OldPanda/bloomfilter (⭐21)](https://github.com/OldPanda/bloomfilter) — Bloom filter compatible with pybloom ☆`21`

### Maps

*   [mhmtszr/concurrent-swiss-map (⭐262)](https://github.com/mhmtszr/concurrent-swiss-map) — Thread-safe concurrent hash map ☆`260`
*   [lrita/cmap (⭐105)](https://github.com/lrita/cmap) — a thread-safe concurrent map for go ☆`104`
*   [goradd/maps (⭐55)](https://github.com/goradd/maps) — Generic map library for Go ☆`55`
*   [srfrog/dict (⭐48)](https://github.com/srfrog/dict) — Python-like dictionaries for Go ☆`48`

### Miscellaneous

*   [Workiva/go-datastructures (⭐7.9k)](https://github.com/Workiva/go-datastructures) — Performant, threadsafe data structures ☆`7,945`
*   [deckarep/golang-set (⭐4.7k)](https://github.com/deckarep/golang-set) — Generic set type for Go ☆`4,703`
*   [bits-and-blooms/bitset (⭐1.5k)](https://github.com/bits-and-blooms/bitset) — Go package implementing bitsets ☆`1,511`
*   [liyue201/gostl (⭐1.1k)](https://github.com/liyue201/gostl) — Data structures modeled on C++ STL ☆`1,140`
*   [axiomhq/hyperloglog (⭐1k)](https://github.com/axiomhq/hyperloglog) — HyperLogLog with optimizations ☆`1,045`
*   [kelindar/bitmap (⭐381)](https://github.com/kelindar/bitmap) — Simple dense bitmap index in Go with binary operators ☆`381`
*   [barweiss/go-tuple (⭐100)](https://github.com/barweiss/go-tuple) — Go 1.18+ generic tuple ☆`100`
*   [seiflotfy/count-min-log (⭐70)](https://github.com/seiflotfy/count-min-log) — Go implementation of Count-Min-Log ☆`70`
*   [s0rg/quadtree (⭐41)](https://github.com/s0rg/quadtree) — Generic, zero-alloc, 100%-test covered Quadtree for golang ☆`41`
*   [nazar256/parapipe (⭐38)](https://github.com/nazar256/parapipe) — Paralleling pipeline ☆`38`
*   [StudioSol/set (⭐30)](https://github.com/StudioSol/set) — Simple set data structure ☆`30`
*   [bobg/merkle (⭐23)](https://github.com/bobg/merkle) — Merkle hash trees ☆`23`

### Queues

*   [gammazero/deque (⭐783)](https://github.com/gammazero/deque) — Fast ring-buffer deque (double-ended queue) ☆`783`
*   [adrianbrad/queue (⭐360)](https://github.com/adrianbrad/queue) — Multiple queue implementations ☆`360`
*   [mikestefanello/backlite (⭐150)](https://github.com/mikestefanello/backlite) — SQLite-backed task queues ☆`150`
*   [embano1/memlog (⭐141)](https://github.com/embano1/memlog) — A Kafka log inspired in-memory and append-only data structure ☆`141`

## Databases

### Caches

*   [golang/groupcache (⭐13k)](https://github.com/golang/groupcache) — Distributed cache library ☆`13,340`
*   [dgraph-io/ristretto (⭐7k)](https://github.com/dgraph-io/ristretto) — A high performance memory-bound Go cache ☆`6,967`
*   [eko/gocache (⭐2.9k)](https://github.com/eko/gocache) — Multi-store caching library ☆`2,876`
*   [maypok86/otter (⭐2.6k)](https://github.com/maypok86/otter) — A high performance caching library for Go ☆`2,646`
*   [VictoriaMetrics/fastcache (⭐2.4k)](https://github.com/VictoriaMetrics/fastcache) — Fast in-memory cache for Go ☆`2,372`
*   [jellydator/ttlcache (⭐1.3k)](https://github.com/jellydator/ttlcache) — An in-memory cache with item expiration and generics ☆`1,267`
*   [viccon/sturdyc (⭐1.3k)](https://github.com/viccon/sturdyc) — Caching with advanced concurrency ☆`1,268`
*   [EchoVault/SugarDB (⭐540)](https://github.com/EchoVault/SugarDB) — Embeddable and distributed in-memory alternative to Redis. ☆`537`
*   [Yiling-J/theine-go (⭐375)](https://github.com/Yiling-J/theine-go) — high performance in-memory cache ☆`375`
*   [elastic/go-freelru (⭐269)](https://github.com/elastic/go-freelru) — GC-less, fast and generic LRU cache for Go ☆`269`
*   [samber/hot (⭐263)](https://github.com/samber/hot) — In-memory caching library for read-intensive Go applications ☆`262`
*   [naughtygopher/pocache (⭐236)](https://github.com/naughtygopher/pocache) — Preemptive optimistic caching ☆`236`
*   [OrlovEvgeny/go-mcache (⭐107)](https://github.com/OrlovEvgeny/go-mcache) — Sharded in-memory KV cache ☆`107`
*   [erni27/imcache (⭐123)](https://github.com/erni27/imcache) — A zero-dependency generic in-memory cache Go library ☆`123`
*   [mdaliyan/icache (⭐23)](https://github.com/mdaliyan/icache) — High-performance generic cache ☆`23`

### Database Schema Migration

*   [golang-migrate/migrate (⭐19k)](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,739`
*   [bytebase/bytebase (⭐14k)](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`14,282`
*   [pressly/goose (⭐11k)](https://github.com/pressly/goose) — A database migration tool. Supports SQL migrations and Go functions. ☆`11,211`
*   [ariga/atlas (⭐8.6k)](https://github.com/ariga/atlas) — Declarative schema migrations with schema-as-code workflows ☆`8,599`
*   [amacneil/dbmate (⭐7k)](https://github.com/amacneil/dbmate) — A lightweight, framework-agnostic database migration tool. ☆`7,008`
*   [rubenv/sql-migrate (⭐3.4k)](https://github.com/rubenv/sql-migrate) — SQL schema migration tool for Go. ☆`3,415`
*   [skeema/skeema (⭐1.4k)](https://github.com/skeema/skeema) — Declarative pure-SQL schema management for MySQL and MariaDB ☆`1,372`
*   [go-gormigrate/gormigrate (⭐1.2k)](https://github.com/go-gormigrate/gormigrate) — Minimalistic database migration helper for Gorm ORM ☆`1,171`
*   [sunary/sqlize (⭐125)](https://github.com/sunary/sqlize) — SQL parsing and migration toolkit ☆`125`
*   [robinjoseph08/go-pg-migrations (⭐87)](https://github.com/robinjoseph08/go-pg-migrations) — A Go package to help write migrations with go-pg/pg. ☆`87`
*   [adlio/schema (⭐44)](https://github.com/adlio/schema) — Embedded schema migration package for Go ☆`44`
*   [khezen/avro (⭐49)](https://github.com/khezen/avro) — Apache AVRO for go ☆`49`
*   [muir/libschema (⭐19)](https://github.com/muir/libschema) — database schema migrations on a per-library basis \[Go] ☆`19`

### Database Tools

*   [vitessio/vitess (⭐21k)](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`21,158`
*   [sosedoff/pgweb (⭐9.4k)](https://github.com/sosedoff/pgweb) — Cross-platform client for PostgreSQL databases ☆`9,449`
*   [go-mysql-org/go-mysql (⭐5k)](https://github.com/go-mysql-org/go-mysql) — a powerful mysql toolset with Go ☆`4,962`
*   [prest/prest (⭐4.6k)](https://github.com/prest/prest) — PostgreSQL REST API server ☆`4,597`
*   [ContentSquare/chproxy (⭐1.5k)](https://github.com/ContentSquare/chproxy) — Open-Source ClickHouse http proxy and load balancer ☆`1,468`
*   [cybertec-postgresql/pg\_timetable (⭐1.4k)](https://github.com/cybertec-postgresql/pg_timetable) — Advanced PostgreSQL scheduler ☆`1,385`
*   [liweiyi88/onedump (⭐974)](https://github.com/liweiyi88/onedump) — Effortless database administration tool ☆`979`
*   [HDT3213/rdb (⭐618)](https://github.com/HDT3213/rdb) — Redis RDB parser for Go ☆`619`
*   [nikepan/clickhouse-bulk (⭐510)](https://github.com/nikepan/clickhouse-bulk) — Batch inserts for ClickHouse ☆`511`
*   [wesql/wescale (⭐316)](https://github.com/wesql/wescale) — MySQL proxy with read/write split ☆`316`
*   [gatewayd-io/gatewayd (⭐286)](https://github.com/gatewayd-io/gatewayd) — database gateway for building data-driven applications ☆`286`
*   [sj14/dbbench (⭐118)](https://github.com/sj14/dbbench) — Database benchmarking tool ☆`118`
*   [bartventer/gorm-multitenancy (⭐83)](https://github.com/bartventer/gorm-multitenancy) — Multi-tenancy for GORM ☆`83`
*   [kazhuravlev/database-gateway (⭐39)](https://github.com/kazhuravlev/database-gateway) — Safe access to production databases ☆`39`
*   [codingconcepts/dg (⭐45)](https://github.com/codingconcepts/dg) — Generate CSV from data models ☆`45`

### Databases Implemented in Go

*   [prometheus/prometheus (⭐65k)](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`65,264`
*   [milvus-io/milvus (⭐45k)](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`45,335`
*   [pingcap/tidb (⭐40k)](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`40,326`
*   [cockroachdb/cockroach (⭐32k)](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`32,310`
*   [influxdata/influxdb (⭐32k)](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,648`
*   [dolthub/dolt (⭐24k)](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`23,932`
*   [dgraph-io/dgraph (⭐22k)](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,745`
*   [rqlite/rqlite (⭐18k)](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,642`
*   [VictoriaMetrics/VictoriaMetrics (⭐17k)](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`17,379`
*   [dgraph-io/badger (⭐16k)](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,727`
*   [dicedb/dicedb (⭐11k)](https://github.com/dicedb/dicedb) — Low-latency key/value engine on Valkey with storage tiers ☆`10,769`
*   [etcd-io/bbolt (⭐9.6k)](https://github.com/etcd-io/bbolt) — An embedded key/value database for Go. ☆`9,645`
*   [codenotary/immudb (⭐9k)](https://github.com/codenotary/immudb) — Immutable database with SQL ☆`9,002`
*   [cockroachdb/pebble (⭐6k)](https://github.com/cockroachdb/pebble) — RocksDB/LevelDB inspired key-value database in Go ☆`5,967`
*   [rosedblabs/rosedb (⭐4.9k)](https://github.com/rosedblabs/rosedb) — Fast key/value storage engine ☆`4,880`
*   [tidwall/buntdb (⭐4.9k)](https://github.com/tidwall/buntdb) — Embeddable in-memory key/value DB ☆`4,863`
*   [nalgeon/redka (⭐4.6k)](https://github.com/nalgeon/redka) — Redis re-implemented with SQL ☆`4,565`
*   [nutsdb/nutsdb (⭐3.6k)](https://github.com/nutsdb/nutsdb) — Simple embeddable key/value store ☆`3,577`
*   [lindb/lindb (⭐3.1k)](https://github.com/lindb/lindb) — Scalable time-series database ☆`3,069`
*   [lotusdblabs/lotusdb (⭐2.3k)](https://github.com/lotusdblabs/lotusdb) — Key-value database with LSM and B+ tree ☆`2,254`
*   [kelindar/column (⭐1.5k)](https://github.com/kelindar/column) — Columnar in-memory store ☆`1,512`
*   [akrylysov/pogreb (⭐1.3k)](https://github.com/akrylysov/pogreb) — Embedded key-value store for read-heavy workloads written in Go ☆`1,352`
*   [objectbox/objectbox-go (⭐1.3k)](https://github.com/objectbox/objectbox-go) — Embedded database for Go ☆`1,272`
*   [couchbase/moss (⭐1k)](https://github.com/couchbase/moss) — Simple, fast key-val storage ☆`1,016`
*   [claygod/transaction (⭐139)](https://github.com/claygod/transaction) — Embedded database for accounts transactions. ☆`139`
*   [xgzlucario/rotom (⭐42)](https://github.com/xgzlucario/rotom) — Tiny Redis server in Go ☆`42`

### Distributed Storage

*   [seaweedfs/seaweedfs (⭐33k)](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`33,652`
*   [juicedata/juicefs (⭐14k)](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`14,221`

### Interfaces to Multiple Backends

*   [philippgille/gokv (⭐829)](https://github.com/philippgille/gokv) — Key-value store abstraction ☆`829`
*   [avito-tech/go-transaction-manager (⭐412)](https://github.com/avito-tech/go-transaction-manager) — Transaction manager for Go ☆`411`
*   [viant/dsc (⭐37)](https://github.com/viant/dsc) — Datastore Connectivity in go ☆`37`
*   [fogfish/dynamo (⭐24)](https://github.com/fogfish/dynamo) — Generic Golang Key/Value trait for AWS storage services ☆`24`

### NoSQL Database Drivers

*   [redis/go-redis (⭐22k)](https://github.com/redis/go-redis) — Redis Go client ☆`22,196`
*   [gomodule/redigo (⭐9.9k)](https://github.com/gomodule/redigo) — Go client for Redis ☆`9,855`
*   [mongodb/mongo-go-driver (⭐8.5k)](https://github.com/mongodb/mongo-go-driver) — The Official Golang driver for MongoDB ☆`8,538`
*   [bradfitz/gomemcache (⭐1.9k)](https://github.com/bradfitz/gomemcache) — Go Memcached client library #golang ☆`1,879`
*   [qiniu/qmgo (⭐1.4k)](https://github.com/qiniu/qmgo) — Go driver for MongoDB ☆`1,356`
*   [Kamva/mgm (⭐763)](https://github.com/Kamva/mgm) — MongoDB ODM for Go based on official driver ☆`763`
*   [aerospike/aerospike-client-go (⭐458)](https://github.com/aerospike/aerospike-client-go) — Aerospike Client Go ☆`459`
*   [couchbase/gocb (⭐377)](https://github.com/couchbase/gocb) — The Couchbase Go SDK ☆`377`
*   [go-kivik/kivik (⭐344)](https://github.com/go-kivik/kivik) — CouchDB client interface ☆`344`
*   [couchbase/go-couchbase (⭐323)](https://github.com/couchbase/go-couchbase) — Couchbase client in Go ☆`323`
*   [chenmingyong0423/go-mongox (⭐220)](https://github.com/chenmingyong0423/go-mongox) — MongoDB driver wrapper with generics ☆`221`
*   [aliexpressru/gomemcached (⭐23)](https://github.com/aliexpressru/gomemcached) — Binary Memcached client with sharding ☆`23`
*   [btnguyen2k/gocosmos (⭐22)](https://github.com/btnguyen2k/gocosmos) — Go database/sql driver for Azure Cosmos DB SQL API ☆`22`

### ORM

*   [go-gorm/gorm (⭐40k)](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,880`
*   [ent/ent (⭐17k)](https://github.com/ent/ent) — An entity framework for Go ☆`17,143`
*   [aarondl/sqlboiler (⭐7k)](https://github.com/aarondl/sqlboiler) — Generate a Go ORM tailored to your database schema. ☆`6,988`
*   [uptrace/bun (⭐4.9k)](https://github.com/uptrace/bun) — SQL-first Golang ORM ☆`4,894`
*   [upper/db (⭐3.7k)](https://github.com/upper/db) — Data access layer for databases ☆`3,661`
*   [stephenafamo/bob (⭐1.7k)](https://github.com/stephenafamo/bob) — SQL builder with ORM generator ☆`1,747`
*   [huandu/go-sqlbuilder (⭐1.7k)](https://github.com/huandu/go-sqlbuilder) — SQL builder with zero-config ORM ☆`1,718`
*   [go-rel/rel (⭐785)](https://github.com/go-rel/rel) — Modern ORM for Golang ☆`786`
*   [hashicorp/go-dbw (⭐18)](https://github.com/hashicorp/go-dbw) — A simple package that encapsulates database operations. ☆`18`
*   [FrancoLiberali/cql (⭐18)](https://github.com/FrancoLiberali/cql) — CQL: Compiled Query Language ☆`18`

### Query Language

*   [99designs/gqlgen (⭐11k)](https://github.com/99designs/gqlgen) — go generate based graphql server library ☆`10,739`
*   [TomWright/dasel (⭐8k)](https://github.com/TomWright/dasel) — Query and modify data formats ☆`8,004`
*   [graph-gophers/graphql-go (⭐4.8k)](https://github.com/graph-gophers/graphql-go) — GraphQL server with a focus on ease of use ☆`4,757`
*   [bhmj/jsonslice (⭐92)](https://github.com/bhmj/jsonslice) — json slicer ☆`92`
*   [hashicorp/mql (⭐66)](https://github.com/hashicorp/mql) — Model Query Language (mql) is a query language for your database models. ☆`66`
*   [AsaiYusuke/jsonpath (⭐32)](https://github.com/AsaiYusuke/jsonpath) — JSONPath query library ☆`32`
*   [ccbrown/api-fu (⭐57)](https://github.com/ccbrown/api-fu) — A collection of Go packages for creating robust GraphQL APIs ☆`57`

### Relational Database Drivers

*   [go-sql-driver/mysql (⭐15k)](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,277`
*   [jackc/pgx (⭐14k)](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`14,057`
*   [denisenkom/go-mssqldb (⭐1.9k)](https://github.com/denisenkom/go-mssqldb) — Microsoft SQL server driver written in go language ☆`1,883`
*   [ncruces/go-sqlite3 (⭐1.1k)](https://github.com/ncruces/go-sqlite3) — Go bindings to SQLite using wasm2go ☆`1,070`
*   [godror/godror (⭐597)](https://github.com/godror/godror) — GO DRiver for ORacle DB ☆`596`
*   [cvilsmeier/sqinn-go (⭐532)](https://github.com/cvilsmeier/sqinn-go) — Golang SQLite without cgo ☆`535`
*   [VinGarcia/ksql (⭐357)](https://github.com/VinGarcia/ksql) — A Simple and Powerful Golang SQL Library ☆`359`
*   [surrealdb/surrealdb.go (⭐314)](https://github.com/surrealdb/surrealdb.go) — SurrealDB SDK for Golang ☆`314`
*   [nakagami/firebirdsql (⭐265)](https://github.com/nakagami/firebirdsql) — Firebird RDBMS sql driver for Go (golang) ☆`266`
*   [ydb-platform/ydb-go-sdk (⭐181)](https://github.com/ydb-platform/ydb-go-sdk) — Pure Go native and database/sql driver for YDB ☆`182`
*   [rqlite/gorqlite (⭐188)](https://github.com/rqlite/gorqlite) — A Go client for rqlite, the distributed database built on SQLite ☆`187`
*   [apache/calcite-avatica-go (⭐126)](https://github.com/apache/calcite-avatica-go) — Apache Calcite Go ☆`126`

### SQL Query Builders

*   [sqlc-dev/sqlc (⭐18k)](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`18,054`
*   [xo/dbtpl (⭐3.9k)](https://github.com/xo/dbtpl) — Generate Go code for databases ☆`3,894`
*   [go-jet/jet (⭐3.7k)](https://github.com/go-jet/jet) — Type-safe SQL builder with codegen ☆`3,769`
*   [lqs/sqlingo (⭐456)](https://github.com/lqs/sqlingo) — A lightweight DSL & ORM which helps you to write SQL in Go. ☆`456`
*   [arthurkushman/buildsqlx (⭐187)](https://github.com/arthurkushman/buildsqlx) — Go database query builder library for PostgreSQL ☆`187`
*   [nullism/bqb (⭐194)](https://github.com/nullism/bqb) — Lightweight query builder ☆`194`
*   [JiveGroup/FluentSQL (⭐18)](https://github.com/JiveGroup/FluentSQL) — Fluent SQL - flexible and powerful SQL string builder ☆`18`

### Search and Analytic Databases

*   [elastic/go-elasticsearch (⭐6.1k)](https://github.com/elastic/go-elasticsearch) — The official Go client for Elasticsearch ☆`6,058`
*   [ClickHouse/clickhouse-go (⭐3.3k)](https://github.com/ClickHouse/clickhouse-go) — Golang driver for ClickHouse ☆`3,323`
*   [sourcegraph/zoekt (⭐1.8k)](https://github.com/sourcegraph/zoekt) — Fast trigram-based code search ☆`1,784`
*   [sdqri/effdsl (⭐35)](https://github.com/sdqri/effdsl) — Elasticsearch query builder for golang ☆`35`

## DevOps & Build

### Backup

*   [restic/restic (⭐35k)](https://github.com/restic/restic) — Fast, secure backup program ☆`35,119`
*   [gilbertchen/duplicacy (⭐5.7k)](https://github.com/gilbertchen/duplicacy) — Cloud backup tool ☆`5,665`

### Build Automation

*   [air-verse/air (⭐24k)](https://github.com/air-verse/air) — Live reload for Go apps ☆`23,799`
*   [go-task/task (⭐16k)](https://github.com/go-task/task) — Fast cross-platform build tool inspired by Make ☆`15,868`
*   [joerdav/xc (⭐1.4k)](https://github.com/joerdav/xc) — Markdown defined task runner. ☆`1,394`
*   [goyek/goyek (⭐693)](https://github.com/goyek/goyek) — Task automation Go library ☆`695`
*   [flowexec/flow (⭐136)](https://github.com/flowexec/flow) — Local-first developer automation platform — workflows, secrets, templates, and more. ☆`136`

### CI/CD

*   [harness/harness (⭐37k)](https://github.com/harness/harness) — End-to-end developer platform ☆`37,451`
*   [woodpecker-ci/woodpecker (⭐7.4k)](https://github.com/woodpecker-ci/woodpecker) — Simple, powerful CI/CD engine ☆`7,489`
*   [ovh/cds (⭐4.8k)](https://github.com/ovh/cds) — Enterprise CI/CD platform ☆`4,832`
*   [raviqqe/muffet (⭐2.6k)](https://github.com/raviqqe/muffet) — Fast website link checker ☆`2,612`
*   [pipe-cd/pipecd (⭐1.3k)](https://github.com/pipe-cd/pipecd) — The One CD for All {applications, platforms, operations} ☆`1,330`
*   [jenkins-zh/jenkins-cli (⭐424)](https://github.com/jenkins-zh/jenkins-cli) — Jenkins CLI allows you to manage your Jenkins in an easy way ☆`425`
*   [vladopajic/go-test-coverage (⭐237)](https://github.com/vladopajic/go-test-coverage) — Report test coverage threshold issues ☆`237`
*   [appleboy/drone-scp (⭐173)](https://github.com/appleboy/drone-scp) — Copy files via SSH for Drone ☆`173`
*   [nikogura/gomason (⭐69)](https://github.com/nikogura/gomason) — A tool for testing, building, signing, and publishing binaries. ☆`69`
*   [appleboy/drone-jenkins (⭐43)](https://github.com/appleboy/drone-jenkins) — Drone plugin for trigger Jenkins jobs. ☆`43`
*   [opnlabs/dot (⭐36)](https://github.com/opnlabs/dot) — Minimal CI using Docker ☆`36`

### Containers

*   [moby/moby (⭐72k)](https://github.com/moby/moby) — Container ecosystem components ☆`71,890`
*   [traefik/traefik (⭐64k)](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`64,078`
*   [ko-build/ko (⭐8.5k)](https://github.com/ko-build/ko) — Build and deploy Go applications ☆`8,481`
*   [s0rg/decompose (⭐138)](https://github.com/s0rg/decompose) — Reverse-engineering tool for docker environments ☆`138`
*   [x1unix/docker-go-mingw (⭐55)](https://github.com/x1unix/docker-go-mingw) — Docker for Go with MinGW toolchain ☆`55`

### DevOps Utilities

*   [go-gitea/gitea (⭐57k)](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`56,971`
*   [moovweb/gvm (⭐12k)](https://github.com/moovweb/gvm) — Go Version Manager ☆`11,676`
*   [TwiN/gatus (⭐11k)](https://github.com/TwiN/gatus) — Developer-oriented status page with alerting ☆`11,582`
*   [bitfield/script (⭐7k)](https://github.com/bitfield/script) — Making it easy to write shell-like scripts in Go ☆`7,013`
*   [fleetdm/fleet (⭐6.6k)](https://github.com/fleetdm/fleet) — Open device management ☆`6,623`
*   [taubyte/tau (⭐5.1k)](https://github.com/taubyte/tau) — Fullstack Workspace for Humans & Machines ☆`5,091`
*   [megaease/easeprobe (⭐2.3k)](https://github.com/megaease/easeprobe) — Service health monitoring tool ☆`2,297`
*   [ajvb/kala (⭐2.2k)](https://github.com/ajvb/kala) — Modern Job Scheduler ☆`2,157`
*   [gabrie30/ghorg (⭐2.1k)](https://github.com/gabrie30/ghorg) — Clone entire GitHub orgs ☆`2,100`
*   [sanbornm/go-selfupdate (⭐1.7k)](https://github.com/sanbornm/go-selfupdate) — Enable your Go applications to self update ☆`1,695`
*   [yusufcanb/tlm (⭐1.5k)](https://github.com/yusufcanb/tlm) — Local CLI Copilot, powered by Ollama. ☆`1,488`
*   [ovh/utask (⭐1.4k)](https://github.com/ovh/utask) — Automation engine with YAML config ☆`1,392`
*   [TimothyYe/skm (⭐1.1k)](https://github.com/TimothyYe/skm) — A simple and powerful SSH keys manager ☆`1,071`
*   [scaleway/scaleway-cli (⭐986)](https://github.com/scaleway/scaleway-cli) — Command Line Interface for Scaleway ☆`986`
*   [alexliesenfeld/health (⭐833)](https://github.com/alexliesenfeld/health) — A simple and flexible health check library for Go. ☆`833`
*   [kool-dev/kool (⭐722)](https://github.com/kool-dev/kool) — Dev to cloud web apps made easy ☆`723`
*   [kevincobain2000/gobrew (⭐426)](https://github.com/kevincobain2000/gobrew) — Go version manager without root ☆`426`
*   [appleboy/easyssh-proxy (⭐348)](https://github.com/appleboy/easyssh-proxy) — Simple SSH protocol implementation ☆`348`
*   [xitonix/trubka (⭐336)](https://github.com/xitonix/trubka) — A CLI tool for Kafka ☆`337`
*   [thevxn/dish (⭐280)](https://github.com/thevxn/dish) — A simple, remotely configurable monitoring service. ☆`280`
*   [jkaninda/goma-gateway (⭐181)](https://github.com/jkaninda/goma-gateway) — Lightweight API gateway and proxy ☆`183`
*   [datarootsio/tf-profile (⭐163)](https://github.com/datarootsio/tf-profile) — Profile Terraform runs ☆`163`
*   [kazhuravlev/healthcheck (⭐24)](https://github.com/kazhuravlev/healthcheck) — Readiness probes for Kubernetes application ☆`24`

### Infrastructure

*   [hashicorp/packer (⭐16k)](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,736`
*   [pomerium/pomerium (⭐4.9k)](https://github.com/pomerium/pomerium) — Pomerium is an identity and context-aware access proxy. ☆`4,917`
*   [peak/s5cmd (⭐4.1k)](https://github.com/peak/s5cmd) — Parallel S3 and local filesystem execution tool. ☆`4,128`
*   [aptly-dev/aptly (⭐2.9k)](https://github.com/aptly-dev/aptly) — aptly - Debian repository management tool ☆`2,854`
*   [KusionStack/kusion (⭐1.3k)](https://github.com/KusionStack/kusion) — Declarative platform orchestrator ☆`1,315`
*   [oxyno-zeta/s3-proxy (⭐478)](https://github.com/oxyno-zeta/s3-proxy) — S3 reverse proxy with auth ☆`479`

### Kubernetes

*   [kubernetes/kubernetes (⭐124k)](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`123,883`
*   [k3s-io/k3s (⭐33k)](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`33,542`
*   [kubernetes/minikube (⭐32k)](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,978`
*   [kubernetes-sigs/kind (⭐15k)](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,367`
*   [kubeshark/kubeshark (⭐12k)](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`12,009`
*   [flannel-io/flannel (⭐9.5k)](https://github.com/flannel-io/flannel) — Network fabric for containers ☆`9,510`
*   [getanteon/anteon (⭐8.5k)](https://github.com/getanteon/anteon) — eBPF Kubernetes monitoring tool ☆`8,523`
*   [kubevela/kubevela (⭐7.9k)](https://github.com/kubevela/kubevela) — The Modern Application Platform. ☆`7,864`
*   [k3d-io/k3d (⭐6.5k)](https://github.com/k3d-io/k3d) — Little helper to run CNCF's k3s in Docker ☆`6,497`
*   [stefanprodan/podinfo (⭐5.9k)](https://github.com/stefanprodan/podinfo) — Go microservice template for Kubernetes ☆`5,955`
*   [apecloud/kubeblocks (⭐3.1k)](https://github.com/apecloud/kubeblocks) — Kubernetes operator for databases ☆`3,085`
*   [kubenetworks/kubevpn (⭐1.3k)](https://github.com/kubenetworks/kubevpn) — Connect to Kubernetes cluster network ☆`1,356`
*   [abahmed/kwatch (⭐1k)](https://github.com/abahmed/kwatch) — monitor & detect crashes in your Kubernetes(K8s) cluster instantly ☆`1,011`
*   [getanteon/alaz (⭐717)](https://github.com/getanteon/alaz) — eBPF agent for K8s observability ☆`717`

### Load Testing

*   [grafana/k6 (⭐31k)](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`31,093`
*   [tsenart/vegeta (⭐25k)](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`25,124`
*   [codesenberg/bombardier (⭐6.8k)](https://github.com/codesenberg/bombardier) — Fast cross-platform HTTP benchmarking tool written in Go ☆`6,809`
*   [rogerwelin/cassowary (⭐810)](https://github.com/rogerwelin/cassowary) — Modern cross-platform HTTP load-testing tool written in Go ☆`811`

## Email

*   [axllent/mailpit (⭐9.9k)](https://github.com/axllent/mailpit) — An email and SMTP testing tool with API for developers ☆`9,923`
*   [foxcpp/maddy (⭐6k)](https://github.com/foxcpp/maddy) — Composable all-in-one mail server. ☆`6,042`
*   [mjl-/mox (⭐5.7k)](https://github.com/mjl-/mox) — Modern secure mail server ☆`5,761`
*   [matcornic/hermes (⭐3k)](https://github.com/matcornic/hermes) — Clean HTML email generator ☆`3,021`
*   [AfterShip/email-verifier (⭐1.6k)](https://github.com/AfterShip/email-verifier) — Email verification without sending emails ☆`1,592`
*   [wneessen/go-mail (⭐1.4k)](https://github.com/wneessen/go-mail) — Easy to use, yet comprehensive library for sending mails with Go ☆`1,453`
*   [sendgrid/sendgrid-go (⭐1.1k)](https://github.com/sendgrid/sendgrid-go) — The Official Twilio SendGrid Golang API Library ☆`1,059`
*   [mailgun/mailgun-go (⭐745)](https://github.com/mailgun/mailgun-go) — Go library for the Mailgun API. ☆`745`
*   [emersion/go-message (⭐457)](https://github.com/emersion/go-message) — Internet Message Format library ☆`456`
*   [vanng822/go-premailer (⭐203)](https://github.com/vanng822/go-premailer) — Inline CSS for HTML mail ☆`203`
*   [truemail-rb/truemail-go (⭐135)](https://github.com/truemail-rb/truemail-go) — Email validator via Regex, DNS, SMTP ☆`135`
*   [toorop/go-dkim (⭐99)](https://github.com/toorop/go-dkim) — DKIM package for golang ☆`99`
*   [dimuska139/go-email-normalizer (⭐79)](https://github.com/dimuska139/go-email-normalizer) — Normalize email addresses ☆`79`
*   [valord577/mailx (⭐23)](https://github.com/valord577/mailx) — A library that makes it easier to send email via SMTP. ☆`23`

## Finance & Blockchain

### Blockchain

*   [ethereum/go-ethereum (⭐51k)](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`51,194`
*   [ipfs/kubo (⭐17k)](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`17,082`
*   [lightningnetwork/lnd (⭐8.2k)](https://github.com/lightningnetwork/lnd) — Lightning Network Daemon ☆`8,163`
*   [cosmos/cosmos-sdk (⭐7k)](https://github.com/cosmos/cosmos-sdk) — Framework for building performant, customizable blockchains with native interoperability ☆`7,029`
*   [solana-foundation/solana-go (⭐1.6k)](https://github.com/solana-foundation/solana-go) — Go SDK library and RPC client for the Solana Blockchain ☆`1,569`
*   [gnolang/gno (⭐1.1k)](https://github.com/gnolang/gno) — Interpreted Go virtual machine ☆`1,078`
*   [cometbft/cometbft (⭐907)](https://github.com/cometbft/cometbft) — Byzantine fault-tolerant consensus ☆`910`
*   [ChainSafe/gossamer (⭐453)](https://github.com/ChainSafe/gossamer) — Go Implementation of the Polkadot Host ☆`454`

### Financial

*   [shopspring/decimal (⭐7.4k)](https://github.com/shopspring/decimal) — Arbitrary-precision fixed-point decimal numbers in Go ☆`7,453`
*   [achannarasappa/ticker (⭐6.2k)](https://github.com/achannarasappa/ticker) — Terminal stock and crypto tracker ☆`6,156`
*   [Rhymond/go-money (⭐1.9k)](https://github.com/Rhymond/go-money) — Go implementation of Fowler's Money pattern ☆`1,903`
*   [c9s/bbgo (⭐1.7k)](https://github.com/c9s/bbgo) — The modern cryptocurrency trading bot framework written in Go. ☆`1,662`
*   [formancehq/ledger (⭐1.3k)](https://github.com/formancehq/ledger) — The programmable open source core ledger for fintech ☆`1,307`
*   [bojanz/currency (⭐640)](https://github.com/bojanz/currency) — Currency handling for Go. ☆`641`
*   [moov-io/ach (⭐555)](https://github.com/moov-io/ach) — ACH file reader, writer, validator ☆`554`
*   [invopop/gobl (⭐293)](https://github.com/invopop/gobl) — Go Business Language ☆`294`
*   [govalues/decimal (⭐245)](https://github.com/govalues/decimal) — Correctly rounded decimals for Go ☆`247`
*   [quagmt/udecimal (⭐188)](https://github.com/quagmt/udecimal) — High-precision decimal library ☆`192`
*   [jovandeginste/payme (⭐91)](https://github.com/jovandeginste/payme) — QR code generator (ASCII & PNG) for SEPA payments ☆`91`
*   [nikolaydubina/fpmoney (⭐36)](https://github.com/nikolaydubina/fpmoney) — Fixed-Point Decimal Money ☆`36`
*   [nikolaydubina/fpdecimal (⭐35)](https://github.com/nikolaydubina/fpdecimal) — Fixed-Point Decimals ☆`35`
*   [jokruger/dec128 (⭐47)](https://github.com/jokruger/dec128) — High performance 128-bit fixed-point decimal numbers in go. ☆`48`
*   [govalues/money (⭐54)](https://github.com/govalues/money) — Correctly rounded monetary amounts and exchange rates for Go ☆`54`

### Payment APIs

*   [stripe/stripe-go (⭐2.6k)](https://github.com/stripe/stripe-go) — Stripe API library for Go ☆`2,611`
*   [plutov/paypal (⭐777)](https://github.com/plutov/paypal) — Golang client for PayPal REST API ☆`778`
*   [brunovenceslau/ynab.go (⭐78)](https://github.com/brunovenceslau/ynab.go) — Client for YNAB API ☆`78`

## GUI & Desktop

### GUI

*   [fyne-io/fyne (⭐28k)](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`28,515`
*   [webview/webview (⭐14k)](https://github.com/webview/webview) — Tiny webview library for Go ☆`14,165`
*   [go-vgo/robotgo (⭐11k)](https://github.com/go-vgo/robotgo) — Cross-platform RPA and GUI automation ☆`10,750`
*   [maxence-charriere/go-app (⭐8.9k)](https://github.com/maxence-charriere/go-app) — Build progressive web apps with Go and WASM ☆`8,932`
*   [progrium/darwinkit (⭐5.4k)](https://github.com/progrium/darwinkit) — Native Mac APIs for Go. Previously known as MacDriver ☆`5,433`
*   [cogentcore/core (⭐2.3k)](https://github.com/cogentcore/core) — Powerful GUI framework for Go ☆`2,344`
*   [gotk3/gotk3 (⭐2.2k)](https://github.com/gotk3/gotk3) — Go bindings for GTK3 ☆`2,212`
*   [roblillack/spot (⭐1.3k)](https://github.com/roblillack/spot) — React-like desktop GUI toolkit for Go ☆`1,257`
*   [ncruces/zenity (⭐915)](https://github.com/ncruces/zenity) — Zenity dialogs for Golang, Windows, macOS ☆`916`
*   [energye/energy (⭐606)](https://github.com/energye/energy) — CEF-based GUI framework ☆`605`
*   [AllenDang/cimgui-go (⭐528)](https://github.com/AllenDang/cimgui-go) — Auto generated Go wrapper for Dear ImGui via cimgui ☆`527`
*   [richardwilkes/unison (⭐329)](https://github.com/richardwilkes/unison) — Unified GUI toolkit for Go ☆`329`

### Windows

*   [go-ole/go-ole (⭐1.3k)](https://github.com/go-ole/go-ole) — win32 ole implementation for golang ☆`1,318`
*   [gonutz/d3d9 (⭐164)](https://github.com/gonutz/d3d9) — Direct3D9 wrapper for Go. ☆`164`

## Game Development

### Game Engines

*   [hajimehoshi/ebiten (⭐13k)](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`13,357`
*   [fogleman/nes (⭐5.7k)](https://github.com/fogleman/nes) — NES emulator written in Go. ☆`5,653`
*   [topfreegames/pitaya (⭐2.8k)](https://github.com/topfreegames/pitaya) — Game server with clustering support ☆`2,810`
*   [xiaonanln/goworld (⭐2.7k)](https://github.com/xiaonanln/goworld) — Distributed game server engine ☆`2,719`
*   [gen2brain/raylib-go (⭐2.5k)](https://github.com/gen2brain/raylib-go) — Go bindings for raylib ☆`2,490`
*   [oakmound/oak (⭐1.7k)](https://github.com/oakmound/oak) — A pure Go game engine ☆`1,661`
*   [JoelOtter/termloop (⭐1.5k)](https://github.com/JoelOtter/termloop) — Terminal-based game engine for Go, built on top of Termbox ☆`1,475`
*   [gopxl/pixel (⭐390)](https://github.com/gopxl/pixel) — A hand-crafted 2D game library in Go. ☆`387`
*   [ungerik/go3d (⭐341)](https://github.com/ungerik/go3d) — A performance oriented 2D/3D math package for Go ☆`341`
*   [mlange-42/ark (⭐285)](https://github.com/mlange-42/ark) — Ark -- Archetype-based Entity Component System (ECS) for Go. ☆`288`
*   [kelindar/tile (⭐225)](https://github.com/kelindar/tile) — 2D grid engine for games ☆`225`
*   [andygeiss/ecs (⭐176)](https://github.com/andygeiss/ecs) — Entity Component System for games ☆`176`
*   [gonutz/prototype (⭐108)](https://github.com/gonutz/prototype) — 2D game prototyping framework ☆`108`
*   [s0rg/fantasyname (⭐44)](https://github.com/s0rg/fantasyname) — RinkWorks fantasy name generator for golang ☆`44`
*   [s0rg/grid (⭐27)](https://github.com/s0rg/grid) — Generic 2D grid ☆`27`

### OpenGL

*   [go-gl/glfw (⭐1.7k)](https://github.com/go-gl/glfw) — Go bindings for GLFW 3 ☆`1,689`
*   [go-gl/gl (⭐1.2k)](https://github.com/go-gl/gl) — Go bindings for OpenGL (generated via glow) ☆`1,200`
*   [go-gl/mathgl (⭐607)](https://github.com/go-gl/mathgl) — A pure Go 3D math library. ☆`607`

## Geospatial

*   [tidwall/tile38 (⭐9.7k)](https://github.com/tidwall/tile38) — Real-time Geospatial and Geofencing ☆`9,701`
*   [golang/geo (⭐1.8k)](https://github.com/golang/geo) — S2 geometry library in Go ☆`1,845`
*   [consbio/mbtileserver (⭐787)](https://github.com/consbio/mbtileserver) — MBTiles server in Go ☆`787`
*   [paulmach/osm (⭐465)](https://github.com/paulmach/osm) — OpenStreetMap data library ☆`466`
*   [uber/h3-go (⭐440)](https://github.com/uber/h3-go) — H3 hexagonal geospatial indexing ☆`442`
*   [airbusgeo/godal (⭐179)](https://github.com/airbusgeo/godal) — GDAL wrapper for Go ☆`179`
*   [peterstace/simplefeatures (⭐172)](https://github.com/peterstace/simplefeatures) — OpenGIS Simple Feature implementation ☆`172`
*   [wroge/wgs84 (⭐142)](https://github.com/wroge/wgs84) — Zero-dep coordinate transformations ☆`142`
*   [pantrif/s2-geojson (⭐37)](https://github.com/pantrif/s2-geojson) — Visualize S2 cells on a map ☆`37`

## Go Tooling

### Compilers

*   [gopherjs/gopherjs (⭐13k)](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,169`
*   [yassinebenaid/bunster (⭐2.7k)](https://github.com/yassinebenaid/bunster) — Compile shell scripts to static binaries. ☆`2,673`
*   [Konstantin8105/c4go (⭐376)](https://github.com/Konstantin8105/c4go) — Transpiling C code to Go code ☆`376`
*   [go2hx/go2hx (⭐152)](https://github.com/go2hx/go2hx) — Import Go libraries in Haxe ☆`152`

### Editor Plugins

*   [fatih/vim-go (⭐16k)](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,223`
*   [visualfc/liteide (⭐7.8k)](https://github.com/visualfc/liteide) — LiteIDE is a simple, open source, cross-platform Go IDE. ☆`7,760`
*   [nsf/gocode (⭐5k)](https://github.com/nsf/gocode) — An autocompletion daemon for the Go programming language ☆`4,993`
*   [golang/vscode-go (⭐4.3k)](https://github.com/golang/vscode-go) — Go extension for Visual Studio Code ☆`4,260`
*   [dominikh/go-mode.el (⭐1.5k)](https://github.com/dominikh/go-mode.el) — Emacs mode for the Go programming language ☆`1,455`
*   [incu6us/goimports-reviser (⭐717)](https://github.com/incu6us/goimports-reviser) — Imports sorting and code formatting tool ☆`716`

### Generate Tools

*   [xuri/xgen (⭐417)](https://github.com/xuri/xgen) — XSD parser and code generator ☆`418`
*   [kazhuravlev/options-gen (⭐109)](https://github.com/kazhuravlev/options-gen) — Codegen for functional options in go projects ☆`109`
*   [g4s8/envdoc (⭐98)](https://github.com/g4s8/envdoc) — Go tool to generate documentation for environment variables ☆`98`

### Go Tools

*   [go-swagger/go-swagger (⭐10k)](https://github.com/go-swagger/go-swagger) — Swagger 2.0 implementation for go ☆`9,994`
*   [ondrajz/go-callvis (⭐6.5k)](https://github.com/ondrajz/go-callvis) — Visualize call graph of a Go program using Graphviz ☆`6,500`
*   [Zxilly/go-size-analyzer (⭐2.2k)](https://github.com/Zxilly/go-size-analyzer) — Analyze compiled Go binary size ☆`2,154`
*   [pointlander/peg (⭐1.1k)](https://github.com/pointlander/peg) — PEG parser generator for Go ☆`1,112`
*   [safedep/vet (⭐1.1k)](https://github.com/safedep/vet) — Protect against malicious open source packages ☆`1,093`
*   [janpfeifer/gonb (⭐1k)](https://github.com/janpfeifer/gonb) — Go notebook kernel for Jupyter ☆`1,031`
*   [alajmo/sake (⭐748)](https://github.com/alajmo/sake) — Task runner for local and remote hosts ☆`748`
*   [goccmack/gocc (⭐663)](https://github.com/goccmack/gocc) — Parser and scanner generator ☆`663`
*   [iyashjayesh/monigo (⭐409)](https://github.com/iyashjayesh/monigo) — Performance monitoring library ☆`409`
*   [becheran/roumon (⭐236)](https://github.com/becheran/roumon) — Universal goroutine monitor using pprof and termui ☆`236`
*   [bitfield/gotestdox (⭐200)](https://github.com/bitfield/gotestdox) — A tool for formatting Go test results as readable documentation ☆`200`
*   [ahmedakef/gotutor (⭐83)](https://github.com/ahmedakef/gotutor) — Online Go Debugger & Visualizer ☆`83`
*   [bobg/modver (⭐22)](https://github.com/bobg/modver) — a tool that helps you obey semantic versioning rules in your Go module ☆`22`
*   [bobg/decouple (⭐37)](https://github.com/bobg/decouple) — find overspecified function parameters in Go code ☆`37`

## Hardware & IoT

### Hardware

*   [shirou/gopsutil (⭐12k)](https://github.com/shirou/gopsutil) — psutil for golang ☆`11,882`
*   [arduino/arduino-cli (⭐5k)](https://github.com/arduino/arduino-cli) — Arduino command line tool ☆`4,972`
*   [jaypipes/ghw (⭐1.9k)](https://github.com/jaypipes/ghw) — Go HardWare discovery/inspection library ☆`1,875`
*   [zcalusic/sysinfo (⭐576)](https://github.com/zcalusic/sysinfo) — Linux system information library ☆`577`

### IoT

*   [hybridgroup/gobot (⭐9.4k)](https://github.com/hybridgroup/gobot) — Robotics and IoT framework ☆`9,438`
*   [lf-edge/ekuiper (⭐1.7k)](https://github.com/lf-edge/ekuiper) — Lightweight data stream processing engine for IoT edge ☆`1,725`
*   [rulego/rulego (⭐1.6k)](https://github.com/rulego/rulego) — Lightweight rule engine framework ☆`1,566`
*   [Edgenesis/shifu (⭐1.4k)](https://github.com/Edgenesis/shifu) — Kubernetes-native IoT gateway ☆`1,426`
*   [e154/smart-home (⭐101)](https://github.com/e154/smart-home) — software package for automation ☆`102`
*   [maxatome/go-vitotrol (⭐24)](https://github.com/maxatome/go-vitotrol) — golang client library to Viessmann Vitotrol web service ☆`24`

## Networking

### Consensus

*   [hashicorp/raft (⭐9.1k)](https://github.com/hashicorp/raft) — Golang implementation of the Raft consensus protocol ☆`9,060`
*   [lni/dragonboat (⭐5.3k)](https://github.com/lni/dragonboat) — Multi-group Raft consensus library ☆`5,322`
*   [etcd-io/raft (⭐1.1k)](https://github.com/etcd-io/raft) — Raft library for maintaining a replicated state machine ☆`1,075`
*   [vadiminshakov/committer (⭐44)](https://github.com/vadiminshakov/committer) — 2PC and 3PC protocols for Go ☆`44`

### DNS

*   [miekg/dns (⭐8.7k)](https://github.com/miekg/dns) — DNS library in Go ☆`8,732`
*   [0xERR0R/blocky (⭐6.8k)](https://github.com/0xERR0R/blocky) — DNS ad-blocker for local networks ☆`6,804`
*   [hashicorp/mdns (⭐1.4k)](https://github.com/hashicorp/mdns) — Simple mDNS client/server library in Golang ☆`1,369`
*   [semihalev/sdns (⭐1.1k)](https://github.com/semihalev/sdns) — High-performance recursive DNS ☆`1,067`
*   [FenkoHQ/dnsmonster (⭐357)](https://github.com/FenkoHQ/dnsmonster) — Passive DNS Capture and Monitoring Toolkit ☆`358`
*   [joeig/go-powerdns (⭐104)](https://github.com/joeig/go-powerdns) — PowerDNS API client for Go (community project) ☆`105`

### Distributed Utilities

*   [luraproject/lura (⭐6.8k)](https://github.com/luraproject/lura) — Ultra-performant API gateway ☆`6,790`
*   [chrislusf/gleam (⭐3.6k)](https://github.com/chrislusf/gleam) — Distributed map/reduce in Go ☆`3,564`
*   [bsm/redislock (⭐1.8k)](https://github.com/bsm/redislock) — Simplified distributed locking implementation using Redis ☆`1,765`
*   [k8gb-io/k8gb (⭐1.2k)](https://github.com/k8gb-io/k8gb) — A cloud native Kubernetes Global Balancer ☆`1,194`
*   [temporalio/sdk-go (⭐925)](https://github.com/temporalio/sdk-go) — Temporal Go SDK ☆`935`
*   [AppsFlyer/go-sundheit (⭐561)](https://github.com/AppsFlyer/go-sundheit) — Health checks library for Go ☆`560`
*   [tarmac-project/tarmac (⭐344)](https://github.com/tarmac-project/tarmac) — Functions as Monolith or Microservices ☆`346`
*   [italolelis/outboxer (⭐168)](https://github.com/italolelis/outboxer) — A library that implements the outboxer pattern in go ☆`168`
*   [capillariesio/capillaries (⭐73)](https://github.com/capillariesio/capillaries) — Distributed batch data processing framework ☆`73`
*   [pdupub/go-pdu (⭐50)](https://github.com/pdupub/go-pdu) — An PDU implementation in Go ☆`50`
*   [mbrostami/consistenthash (⭐35)](https://github.com/mbrostami/consistenthash) — Consistent hashing implementation ☆`35`

### HTTP & Proxy

*   [valyala/fasthttp (⭐23k)](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,416`
*   [elazarl/goproxy (⭐6.7k)](https://github.com/elazarl/goproxy) — An HTTP proxy library for Go ☆`6,710`
*   [wzshiming/httpproxy (⭐33)](https://github.com/wzshiming/httpproxy) — HTTP proxy handler and dialer ☆`33`

### HTTP Clients

*   [go-resty/resty (⭐12k)](https://github.com/go-resty/resty) — Simple HTTP, REST, and SSE client library for Go ☆`11,728`
*   [imroc/req (⭐4.8k)](https://github.com/imroc/req) — Simple Go HTTP client with Black Magic ☆`4,824`
*   [gojek/heimdall (⭐2.8k)](https://github.com/gojek/heimdall) — An enhanced HTTP client for Go ☆`2,773`
*   [hashicorp/go-retryablehttp (⭐2.3k)](https://github.com/hashicorp/go-retryablehttp) — Retryable HTTP client in Go ☆`2,340`
*   [levigross/grequests (⭐2.2k)](https://github.com/levigross/grequests) — A Go "clone" of the great and famous Requests library ☆`2,188`
*   [bogdanfinn/tls-client (⭐1.7k)](https://github.com/bogdanfinn/tls-client) — HTTP client with TLS fingerprint spoofing ☆`1,744`
*   [dghubble/sling (⭐1.7k)](https://github.com/dghubble/sling) — A Go HTTP client library for creating and sending API requests ☆`1,719`
*   [earthboundkid/requests (⭐1.7k)](https://github.com/earthboundkid/requests) — HTTP requests for Gophers ☆`1,671`
*   [Noooste/azuretls-client (⭐462)](https://github.com/Noooste/azuretls-client) — HTTP client to spoof TLS/JA3 fingerprint ☆`464`
*   [opus-domini/fast-shot (⭐125)](https://github.com/opus-domini/fast-shot) — Fluent HTTP client for Go ☆`125`
*   [go-zoox/fetch (⭐91)](https://github.com/go-zoox/fetch) — Powerful HTTP client for Go ☆`91`
*   [NdoleStudio/go-otelroundtripper (⭐88)](https://github.com/NdoleStudio/go-otelroundtripper) — OpenTelemetry metrics for HTTP clients ☆`88`
*   [rezmoss/axios4go (⭐38)](https://github.com/rezmoss/axios4go) — Axios-inspired HTTP client ☆`38`
*   [lib4u/fake-useragent (⭐19)](https://github.com/lib4u/fake-useragent) — Up-to-date simple useragent faker with real world database in Golang ☆`19`

### Servers

*   [caddyserver/caddy (⭐74k)](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`74,276`
*   [pocketbase/pocketbase (⭐60k)](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`60,149`
*   [etcd-io/etcd (⭐52k)](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`52,018`
*   [drakkan/sftpgo (⭐12k)](https://github.com/drakkan/sftpgo) — Full-featured SFTP/FTP/HTTP server ☆`12,300`
*   [adnanh/webhook (⭐12k)](https://github.com/adnanh/webhook) — Lightweight webhook server ☆`11,991`
*   [roadrunner-server/roadrunner (⭐8.5k)](https://github.com/roadrunner-server/roadrunner) — High-performance PHP application server ☆`8,492`
*   [easegress-io/easegress (⭐5.9k)](https://github.com/easegress-io/easegress) — A Cloud Native traffic orchestration system ☆`5,869`
*   [charmbracelet/wish (⭐5.3k)](https://github.com/charmbracelet/wish) — Make SSH apps, just like that! ☆`5,342`
*   [flipt-io/flipt (⭐4.8k)](https://github.com/flipt-io/flipt) — Enterprise-ready, Git native feature management solution ☆`4,853`
*   [getfider/fider (⭐4.4k)](https://github.com/getfider/fider) — Open platform to collect and prioritize feedback ☆`4,429`
*   [xyproto/algernon (⭐3k)](https://github.com/xyproto/algernon) — Web server with Lua and Markdown ☆`3,022`
*   [openflagr/flagr (⭐2.6k)](https://github.com/openflagr/flagr) — Feature flagging and A/B testing ☆`2,602`
*   [thomaspoignant/go-feature-flag (⭐2.1k)](https://github.com/thomaspoignant/go-feature-flag) — Open source feature flag solution ☆`2,067`
*   [msoap/shell2http (⭐1.5k)](https://github.com/msoap/shell2http) — Executing shell commands via HTTP server ☆`1,496`
*   [openrundev/openrun (⭐898)](https://github.com/openrundev/openrun) — Open source Cloud Run alternative ☆`899`
*   [webhookx-io/webhookx (⭐294)](https://github.com/webhookx-io/webhookx) — The Next-Generation Webhooks Gateway. ☆`293`
*   [blind-oracle/cortex-tenant (⭐139)](https://github.com/blind-oracle/cortex-tenant) — Prometheus proxy with tenant ID injection ☆`139`
*   [baalimago/wd-41 (⭐153)](https://github.com/baalimago/wd-41) — Web-Development 41, a static web server with live-reload ☆`153`
*   [42atomys/webhooked (⭐43)](https://github.com/42atomys/webhooked) — A webhook receiver on steroids. ☆`43`

### Network Utilities

*   [fortio/fortio (⭐3.7k)](https://github.com/fortio/fortio) — Load testing and echo server ☆`3,711`
*   [hashicorp/go-getter (⭐1.8k)](https://github.com/hashicorp/go-getter) — Download files from URLs ☆`1,822`
*   [TimothyYe/godns (⭐1.7k)](https://github.com/TimothyYe/godns) — Dynamic DNS client for multiple providers ☆`1,751`
*   [schollz/peerdiscovery (⭐671)](https://github.com/schollz/peerdiscovery) — Cross-platform local peer discovery ☆`673`
*   [fclairamb/ftpserverlib (⭐471)](https://github.com/fclairamb/ftpserverlib) — FTP server library for Go ☆`472`
*   [skibish/ddns (⭐266)](https://github.com/skibish/ddns) — Personal DDNS client with Digital Ocean Networking DNS as backend. ☆`266`
*   [assafmo/joincap (⭐220)](https://github.com/assafmo/joincap) — Merge pcap files ☆`220`
*   [gaissmai/bart (⭐147)](https://github.com/gaissmai/bart) — Balanced routing table ☆`151`
*   [alegrey91/fwdctl (⭐72)](https://github.com/alegrey91/fwdctl) — Manage IPTables forwards via CLI ☆`72`

### P2P & Torrent

*   [anacrolix/torrent (⭐6.1k)](https://github.com/anacrolix/torrent) — Full-featured BitTorrent client package and utilities ☆`6,074`
*   [dragonflyoss/dragonfly (⭐3.3k)](https://github.com/dragonflyoss/dragonfly) — P2P-based container image distribution ☆`3,265`
*   [cenkalti/rain (⭐1.1k)](https://github.com/cenkalti/rain) — BitTorrent client and library in Go ☆`1,140`
*   [anacrolix/dht (⭐357)](https://github.com/anacrolix/dht) — DHT for BitTorrent ☆`359`

### Protocols

*   [pion/webrtc (⭐17k)](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,657`
*   [quic-go/quic-go (⭐12k)](https://github.com/quic-go/quic-go) — A production-ready QUIC implementation in pure Go ☆`11,712`
*   [google/gopacket (⭐6.8k)](https://github.com/google/gopacket) — Provides packet processing capabilities for Go ☆`6,788`
*   [osrg/gobgp (⭐4.1k)](https://github.com/osrg/gobgp) — BGP implemented in the Go Programming Language ☆`4,090`
*   [lxzan/gws (⭐1.8k)](https://github.com/lxzan/gws) — Fast websocket server and client ☆`1,794`
*   [gosnmp/gosnmp (⭐1.3k)](https://github.com/gosnmp/gosnmp) — An SNMP library written in Go ☆`1,252`
*   [bluenviron/gortsplib (⭐929)](https://github.com/bluenviron/gortsplib) — RTSP client and server library for the Go programming language ☆`930`
*   [ccding/go-stun (⭐720)](https://github.com/ccding/go-stun) — A go implementation of the STUN client (RFC 3489 and RFC 5389) ☆`720`
*   [google/gnxi (⭐287)](https://github.com/google/gnxi) — gNXI Tools - gRPC Network Management/Operations Interface Tools ☆`288`
*   [jeroenrinzema/psql-wire (⭐238)](https://github.com/jeroenrinzema/psql-wire) — PostgreSQL wire protocol for Go ☆`238`
*   [jimlambrt/gldap (⭐122)](https://github.com/jimlambrt/gldap) — Build LDAP services w/ Go ☆`122`
*   [soypat/natiu-mqtt (⭐106)](https://github.com/soypat/natiu-mqtt) — Extensible MQTT for embedded systems ☆`106`

### RPC

*   [grpc/grpc-go (⭐23k)](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`23,011`
*   [lesismal/arpc (⭐1.1k)](https://github.com/lesismal/arpc) — Two-way RPC with broadcast support ☆`1,091`
*   [ybbus/jsonrpc (⭐370)](https://github.com/ybbus/jsonrpc) — A simple go implementation of json rpc 2.0 client over http ☆`370`
*   [osamingo/jsonrpc (⭐193)](https://github.com/osamingo/jsonrpc) — The jsonrpc package helps implement of JSON-RPC 2.0 ☆`193`

### SSH & SFTP

*   [gliderlabs/ssh (⭐4.2k)](https://github.com/gliderlabs/ssh) — Easy SSH servers in Golang ☆`4,159`
*   [pkg/sftp (⭐1.7k)](https://github.com/pkg/sftp) — SFTP support for the go.crypto/ssh package ☆`1,661`
*   [masterzen/winrm (⭐473)](https://github.com/masterzen/winrm) — Windows remote command library ☆`476`

### TCP/UDP Frameworks

*   [panjf2000/gnet (⭐11k)](https://github.com/panjf2000/gnet) — High-performance event-loop network ☆`11,216`
*   [xtaci/kcp-go (⭐4.5k)](https://github.com/xtaci/kcp-go) — A crypto-secure Reliable-UDP library for Golang with FEC support. ☆`4,535`
*   [cloudwego/netpoll (⭐4.6k)](https://github.com/cloudwego/netpoll) — High-performance I/O framework ☆`4,594`
*   [lesismal/nbio (⭐2.8k)](https://github.com/lesismal/nbio) — High-performance network library ☆`2,753`
*   [xtaci/gaio (⭐930)](https://github.com/xtaci/gaio) — High-performance, minimalist async-io (proactor) networking for Golang. ☆`930`
*   [cheng-zhongliang/event (⭐119)](https://github.com/cheng-zhongliang/event) — Simple I/O event notification library wirtten in Golang ☆`119`
*   [fish-tennis/gnet (⭐27)](https://github.com/fish-tennis/gnet) — high performance net library for game server ☆`27`

### VPN & Tunneling

*   [cloudflare/cloudflared (⭐15k)](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`14,931`
*   [xjasonlyu/tun2socks (⭐5.4k)](https://github.com/xjasonlyu/tun2socks) — TUN to SOCKS proxy ☆`5,409`
*   [songgao/water (⭐2.2k)](https://github.com/songgao/water) — A simple TUN/TAP library written in native Go. ☆`2,165`
*   [NodePassProject/nodepass (⭐267)](https://github.com/NodePassProject/nodepass) — Secure TCP/UDP tunneling with TLS ☆`268`

## Queues & Pub/Sub

### Brokers

*   [nats-io/nats-server (⭐20k)](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`20,294`
*   [emitter-io/emitter (⭐4k)](https://github.com/emitter-io/emitter) — High-performance pub/sub broker ☆`4,003`
*   [mochi-mqtt/server (⭐1.9k)](https://github.com/mochi-mqtt/server) — Embeddable MQTT v5 broker ☆`1,902`

### Clients & Libraries

*   [hibiken/asynq (⭐14k)](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`13,540`
*   [IBM/sarama (⭐13k)](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,501`
*   [centrifugal/centrifugo (⭐10k)](https://github.com/centrifugal/centrifugo) — Scalable real-time messaging server ☆`10,541`
*   [ThreeDotsLabs/watermill (⭐9.8k)](https://github.com/ThreeDotsLabs/watermill) — Building event-driven applications the easy way in Go. ☆`9,808`
*   [appleboy/gorush (⭐8.7k)](https://github.com/appleboy/gorush) — A push notification server written in Go (Golang). ☆`8,750`
*   [RichardKnop/machinery (⭐8k)](https://github.com/RichardKnop/machinery) — Async task queue with message passing ☆`7,962`
*   [nats-io/nats.go (⭐6.7k)](https://github.com/nats-io/nats.go) — Golang client for NATS, the cloud native messaging system. ☆`6,695`
*   [dunglas/mercure (⭐5.3k)](https://github.com/dunglas/mercure) — Server-Sent Events hub ☆`5,285`
*   [confluentinc/confluent-kafka-go (⭐5.1k)](https://github.com/confluentinc/confluent-kafka-go) — Confluent's Apache Kafka Golang client ☆`5,151`
*   [olahol/melody (⭐4.1k)](https://github.com/olahol/melody) — Minimalist websocket framework for Go ☆`4,079`
*   [sideshow/apns2 (⭐3.2k)](https://github.com/sideshow/apns2) — Apple Push Notification Service ☆`3,185`
*   [lovoo/goka (⭐2.5k)](https://github.com/lovoo/goka) — Kafka stream processing library ☆`2,536`
*   [rabbitmq/amqp091-go (⭐2k)](https://github.com/rabbitmq/amqp091-go) — An AMQP 0-9-1 Go client maintained by the RabbitMQ team ☆`2,022`
*   [containrrr/shoutrrr (⭐1.6k)](https://github.com/containrrr/shoutrrr) — Notification library for gophers and their furry friends. ☆`1,632`
*   [pebbe/zmq4 (⭐1.3k)](https://github.com/pebbe/zmq4) — A Go interface to ZeroMQ version 4 ☆`1,258`
*   [timbray/quamina (⭐496)](https://github.com/timbray/quamina) — Fast pattern-matching library ☆`497`
*   [jandelgado/rabtap (⭐286)](https://github.com/jandelgado/rabtap) — RabbitMQ wire tap and swiss army knife ☆`288`
*   [mehdihadeli/Go-MediatR (⭐278)](https://github.com/mehdihadeli/Go-MediatR) — Mediator pattern for CQRS ☆`278`
*   [goptics/varmq (⭐191)](https://github.com/goptics/varmq) — Zero-dep message queue library ☆`191`
*   [oagudo/outbox (⭐130)](https://github.com/oagudo/outbox) — Transactional outbox pattern ☆`131`
*   [hyperonym/ratus (⭐124)](https://github.com/hyperonym/ratus) — RESTful async task queue server ☆`124`
*   [dailymotion/oplog (⭐111)](https://github.com/dailymotion/oplog) — A generic oplog/replication system for microservices ☆`111`
*   [jirenius/go-res (⭐69)](https://github.com/jirenius/go-res) — RES Service protocol library for Go ☆`69`
*   [Protocol-Lattice/GoEventBus (⭐68)](https://github.com/Protocol-Lattice/GoEventBus) — A lock-free, ultra-fast event bus for Go ☆`68`
*   [SchwarzDigits/hypermatch (⭐36)](https://github.com/SchwarzDigits/hypermatch) — High-performance rule matching ☆`36`

## Science

*   [gonum/gonum (⭐8.4k)](https://github.com/gonum/gonum) — Numeric libraries for Go ☆`8,415`
*   [gonum/plot (⭐3k)](https://github.com/gonum/plot) — Plotting and visualization ☆`2,962`
*   [paulmach/orb (⭐1.1k)](https://github.com/paulmach/orb) — 2D geometry types and utilities ☆`1,122`
*   [madelynnblue/go-dsp (⭐915)](https://github.com/madelynnblue/go-dsp) — Digital Signal Processing for Go ☆`915`
*   [bebop/poly (⭐731)](https://github.com/bebop/poly) — Synthetic biology library for Go ☆`732`
*   [hmdsefi/gograph (⭐123)](https://github.com/hmdsefi/gograph) — Generic graph algorithms library ☆`123`
*   [nikolaydubina/jsonl-graph (⭐79)](https://github.com/nikolaydubina/jsonl-graph) — JSONL Graph Tools ☆`79`
*   [claygod/PiHex (⭐21)](https://github.com/claygod/PiHex) — Generate hexadecimal Pi digits ☆`21`

## Scripting

### Embeddable Languages

*   [php/frankenphp (⭐11k)](https://github.com/php/frankenphp) — The modern PHP app server ☆`11,239`
*   [expr-lang/expr (⭐7.9k)](https://github.com/expr-lang/expr) — Expression evaluation for Go ☆`7,950`
*   [dop251/goja (⭐7k)](https://github.com/dop251/goja) — ECMAScript engine in pure Go ☆`7,017`
*   [yuin/gopher-lua (⭐6.9k)](https://github.com/yuin/gopher-lua) — Lua VM and compiler in Go ☆`6,955`
*   [d5/tengo (⭐3.8k)](https://github.com/d5/tengo) — Fast script language for Go ☆`3,830`
*   [Shopify/go-lua (⭐3.4k)](https://github.com/Shopify/go-lua) — Lua VM in Go ☆`3,446`
*   [cel-expr/cel-go (⭐3k)](https://github.com/cel-expr/cel-go) — Common Expression Language for Go ☆`3,037`
*   [google/starlark-go (⭐2.7k)](https://github.com/google/starlark-go) — Starlark config language in Go ☆`2,735`
*   [metacall/core (⭐1.8k)](https://github.com/metacall/core) — Polyglot programming runtime ☆`1,810`
*   [wa-lang/wa (⭐1.8k)](https://github.com/wa-lang/wa) — The Wa Programming Language ☆`1,770`
*   [mattn/anko (⭐1.6k)](https://github.com/mattn/anko) — Scriptable interpreter in Go ☆`1,578`
*   [PaesslerAG/gval (⭐812)](https://github.com/PaesslerAG/gval) — Expression evaluation in Go ☆`813`
*   [ichiban/prolog (⭐727)](https://github.com/ichiban/prolog) — Prolog scripting engine for Go ☆`726`
*   [aarzilli/golua (⭐700)](https://github.com/aarzilli/golua) — Lua C API bindings for Go ☆`700`
*   [1set/starlet (⭐47)](https://github.com/1set/starlet) — Starlark wrapper with batteries ☆`48`

### Code Generators

*   [oapi-codegen/oapi-codegen (⭐8.4k)](https://github.com/oapi-codegen/oapi-codegen) — Generate Go code from OpenAPI 3 specs ☆`8,473`
*   [dave/jennifer (⭐3.6k)](https://github.com/dave/jennifer) — Code generator for Go ☆`3,626`
*   [hexdigest/gowrap (⭐1.3k)](https://github.com/hexdigest/gowrap) — Generate interface decorators ☆`1,332`
*   [awalterschulze/goderive (⭐1.3k)](https://github.com/awalterschulze/goderive) — Generate mundane Go functions ☆`1,265`
*   [abice/go-enum (⭐953)](https://github.com/abice/go-enum) — Enum generator for Go ☆`953`
*   [jmattheis/goverter (⭐859)](https://github.com/jmattheis/goverter) — Generate type-safe converters ☆`861`
*   [rjeczalik/interfaces (⭐431)](https://github.com/rjeczalik/interfaces) — Code generation tools for Go ☆`430`
*   [switchupcb/copygen (⭐404)](https://github.com/switchupcb/copygen) — Copy values between types ☆`404`
*   [reedom/convergen (⭐50)](https://github.com/reedom/convergen) — Type-to-type copy code generator ☆`51`

## Security

### Certificates

*   [go-acme/lego (⭐9.7k)](https://github.com/go-acme/lego) — Let's Encrypt/ACME client and library written in Go ☆`9,757`
*   [caddyserver/certmagic (⭐5.6k)](https://github.com/caddyserver/certmagic) — Automatic HTTPS certificate management ☆`5,587`
*   [tg123/go-htpasswd (⭐49)](https://github.com/tg123/go-htpasswd) — Apache htpasswd Parser for Go. ☆`49`
*   [adrianosela/sslmgr (⭐32)](https://github.com/adrianosela/sslmgr) — SSL certificate abstraction ☆`32`

### Cryptography

*   [FiloSottile/age (⭐23k)](https://github.com/FiloSottile/age) — Simple encryption tool ☆`22,971`
*   [authzed/spicedb (⭐6.9k)](https://github.com/authzed/spicedb) — Zanzibar-inspired permissions DB ☆`6,879`
*   [awnumar/memguard (⭐2.7k)](https://github.com/awnumar/memguard) — Software sandbox for storage of sensitive information in memory. ☆`2,751`
*   [cossacklabs/themis (⭐2k)](https://github.com/cossacklabs/themis) — Cryptographic framework for data protection ☆`1,968`
*   [dromara/dongle (⭐1.1k)](https://github.com/dromara/dongle) — A simple, semantic and developer-friendly crypto package for golang ☆`1,108`
*   [anatol/booster (⭐656)](https://github.com/anatol/booster) — Fast and secure initramfs generator ☆`658`
*   [kevinburke/nacl (⭐553)](https://github.com/kevinburke/nacl) — Pure Go implementation of the NaCL set of API's ☆`554`
*   [ssh-vault/ssh-vault (⭐508)](https://github.com/ssh-vault/ssh-vault) — encrypt/decrypt using ssh keys ☆`508`
*   [number571/go-peer (⭐328)](https://github.com/number571/go-peer) — Secure decentralized networking ☆`327`
*   [lingrino/vaku (⭐160)](https://github.com/lingrino/vaku) — Extended Vault API and CLI ☆`160`
*   [anatol/luks.go (⭐98)](https://github.com/anatol/luks.go) — Pure Golang library to manage LUKS partitions ☆`98`
*   [zitadel/passwap (⭐77)](https://github.com/zitadel/passwap) — Unified password hashing ☆`77`
*   [rsjethani/secret (⭐33)](https://github.com/rsjethani/secret) — Prevent your secrets from leaking into logs, std\* etc. ☆`33`
*   [andskur/argon2-hashing (⭐25)](https://github.com/andskur/argon2-hashing) — Argon2 password hashing ☆`25`

### WAF & Protection

*   [Ullaakut/cameradar (⭐5.1k)](https://github.com/Ullaakut/cameradar) — Cameradar hacks its way into RTSP videosurveillance cameras ☆`5,130`
*   [corazawaf/coraza (⭐3.7k)](https://github.com/corazawaf/coraza) — ModSecurity-compatible WAF in Go ☆`3,672`
*   [mojocn/base64Captcha (⭐2.4k)](https://github.com/mojocn/base64Captcha) — captcha of base64 image string ☆`2,370`
*   [unrolled/secure (⭐2.3k)](https://github.com/unrolled/secure) — HTTP middleware for Go that facilitates some quick security wins. ☆`2,349`
*   [beelzebub-labs/beelzebub (⭐2.1k)](https://github.com/beelzebub-labs/beelzebub) — AI-powered honeypot framework ☆`2,093`
*   [cossacklabs/acra (⭐1.5k)](https://github.com/cossacklabs/acra) — Database security proxy ☆`1,485`
*   [securitybunker/databunker (⭐1.5k)](https://github.com/securitybunker/databunker) — Secure vault for PII/PHI/KYC records ☆`1,474`
*   [hillu/go-yara (⭐389)](https://github.com/hillu/go-yara) — Go bindings for YARA ☆`389`
*   [steambap/captcha (⭐163)](https://github.com/steambap/captcha) — Easy captcha library ☆`163`

### Zero Trust

*   [sigstore/cosign (⭐6.1k)](https://github.com/sigstore/cosign) — Code signing and transparency for containers and binaries ☆`6,148`
*   [openziti/ziti (⭐4.3k)](https://github.com/openziti/ziti) — Zero trust networking platform ☆`4,309`
*   [spiffe/spire (⭐2.4k)](https://github.com/spiffe/spire) — The SPIFFE Runtime Environment ☆`2,445`
*   [philips-labs/spiffe-vault (⭐101)](https://github.com/philips-labs/spiffe-vault) — Integrates Spiffe and Vault to have secretless authentication ☆`101`

## Testing & Quality

### Benchmarks

*   [smallnest/go-web-framework-benchmark (⭐2.1k)](https://github.com/smallnest/go-web-framework-benchmark) — Web framework benchmarks ☆`2,138`
*   [alecthomas/go\_serialization\_benchmarks (⭐1.6k)](https://github.com/alecthomas/go_serialization_benchmarks) — Serialization benchmarks for Go ☆`1,626`
*   [SimonWaldherr/golang-benchmarks (⭐145)](https://github.com/SimonWaldherr/golang-benchmarks) — Go(lang) benchmarks - (measure the speed of golang) ☆`145`
*   [nikolaydubina/go-ml-benchmarks (⭐34)](https://github.com/nikolaydubina/go-ml-benchmarks) — Benchmarks of machine learning inference for Go ☆`34`

### Code Analysis

*   [golangci/golangci-lint (⭐19k)](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`19,202`
*   [boyter/scc (⭐8.6k)](https://github.com/boyter/scc) — Fast code counter and stats ☆`8,554`
*   [mgechev/revive (⭐5.5k)](https://github.com/mgechev/revive) — Fast, extensible Go linter ☆`5,536`
*   [kisielk/errcheck (⭐2.5k)](https://github.com/kisielk/errcheck) — errcheck checks that you checked errors. ☆`2,525`
*   [go-critic/go-critic (⭐2.1k)](https://github.com/go-critic/go-critic) — The most opinionated Go source code linter for code audit. ☆`2,057`
*   [daveshanley/vacuum (⭐1.1k)](https://github.com/daveshanley/vacuum) — Fast OpenAPI linter ☆`1,105`
*   [presmihaylov/todocheck (⭐439)](https://github.com/presmihaylov/todocheck) — Analyser for TODO comments ☆`439`
*   [mdempsky/unconvert (⭐388)](https://github.com/mdempsky/unconvert) — Remove unnecessary type conversions ☆`387`
*   [tomarrell/wrapcheck (⭐375)](https://github.com/tomarrell/wrapcheck) — Check errors are wrapped ☆`374`
*   [mibk/dupl (⭐368)](https://github.com/mibk/dupl) — Code clone detection tool ☆`368`
*   [shurcooL/gostatus (⭐245)](https://github.com/shurcooL/gostatus) — Show status of Go repositories ☆`245`
*   [Antonboom/testifylint (⭐173)](https://github.com/Antonboom/testifylint) — Linter for testify usage ☆`172`
*   [Crocmagnon/fatcontext (⭐80)](https://github.com/Crocmagnon/fatcontext) — Detect nested contexts in loops ☆`80`
*   [antham/ghokin (⭐56)](https://github.com/antham/ghokin) — Parallelized Gherkin formatter ☆`56`
*   [sashamelentyev/usestdlibvars (⭐48)](https://github.com/sashamelentyev/usestdlibvars) — Linter for stdlib variables usage ☆`47`
*   [borovikovd/gomsort (⭐25)](https://github.com/borovikovd/gomsort) — Go msort - linter that sorts methods ☆`25`

### Mock

*   [vektra/mockery (⭐7.2k)](https://github.com/vektra/mockery) — Mock code autogenerator for Go ☆`7,153`
*   [DATA-DOG/go-sqlmock (⭐6.6k)](https://github.com/DATA-DOG/go-sqlmock) — SQL mock driver for testing ☆`6,565`
*   [brianvoe/gofakeit (⭐5.4k)](https://github.com/brianvoe/gofakeit) — Random fake data generator written in go ☆`5,373`
*   [uber-go/mock (⭐3.4k)](https://github.com/uber-go/mock) — GoMock is a mocking framework for the Go programming language. ☆`3,385`
*   [SpectoLabs/hoverfly (⭐2.5k)](https://github.com/SpectoLabs/hoverfly) — API simulation and virtualization ☆`2,505`
*   [matryer/moq (⭐2.2k)](https://github.com/matryer/moq) — Interface mocking via go generate ☆`2,201`
*   [jarcoal/httpmock (⭐2.1k)](https://github.com/jarcoal/httpmock) — HTTP mocking for Go ☆`2,079`
*   [maxbrunsfeld/counterfeiter (⭐1.1k)](https://github.com/maxbrunsfeld/counterfeiter) — Generate type-safe test doubles ☆`1,135`
*   [gojuno/minimock (⭐753)](https://github.com/gojuno/minimock) — Powerful mock generator ☆`752`
*   [DATA-DOG/go-txdb (⭐751)](https://github.com/DATA-DOG/go-txdb) — Transaction-isolated SQL driver ☆`751`
*   [pashagolub/pgxmock (⭐592)](https://github.com/pashagolub/pgxmock) — pgx mock driver for testing ☆`592`
*   [xhd2015/xgo (⭐432)](https://github.com/xhd2015/xgo) — All-in-one Go testing library ☆`431`
*   [seborama/govcr (⭐200)](https://github.com/seborama/govcr) — Record and replay HTTP interactions ☆`200`
*   [mocktools/go-smtp-mock (⭐166)](https://github.com/mocktools/go-smtp-mock) — SMTP mock server for testing ☆`166`
*   [elgohr/go-localstack (⭐88)](https://github.com/elgohr/go-localstack) — Go wrapper for LocalStack ☆`88`

### Performance

*   [jaegertracing/jaeger (⭐23k)](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`23,026`
*   [pixie-io/pixie (⭐6.5k)](https://github.com/pixie-io/pixie) — Kubernetes-native observability ☆`6,498`
*   [arl/statsviz (⭐3.6k)](https://github.com/arl/statsviz) — Visualize Go runtime metrics ☆`3,645`
*   [nikolaydubina/go-instrument (⭐298)](https://github.com/nikolaydubina/go-instrument) — Add trace spans to Go functions ☆`299`
*   [joetifa2003/mm-go (⭐194)](https://github.com/joetifa2003/mm-go) — Manual memory management for Go ☆`194`

### Browser Automation

*   [chromedp/chromedp (⭐13k)](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`13,200`
*   [go-rod/rod (⭐7k)](https://github.com/go-rod/rod) — Chrome DevTools driver for scraping ☆`7,034`
*   [sensepost/gowitness (⭐4.4k)](https://github.com/sensepost/gowitness) — Web screenshot utility with Chrome ☆`4,413`
*   [mxschmitt/playwright-go (⭐3.4k)](https://github.com/mxschmitt/playwright-go) — Browser automation for Chromium, Firefox, WebKit ☆`3,439`
*   [mafredri/cdp (⭐793)](https://github.com/mafredri/cdp) — Chrome DevTools Protocol bindings ☆`794`

### Testing Frameworks

*   [stretchr/testify (⭐26k)](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`26,095`
*   [keploy/keploy (⭐18k)](https://github.com/keploy/keploy) — API testing with auto mocks ☆`18,337`
*   [Shopify/toxiproxy (⭐12k)](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`12,183`
*   [testcontainers/testcontainers-go (⭐4.9k)](https://github.com/testcontainers/testcontainers-go) — Docker containers for integration tests ☆`4,926`
*   [google/go-cmp (⭐4.7k)](https://github.com/google/go-cmp) — Package for comparing Go values in tests ☆`4,666`
*   [gavv/httpexpect (⭐2.7k)](https://github.com/gavv/httpexpect) — End-to-end HTTP and REST API testing for Go. ☆`2,723`
*   [cucumber/godog (⭐2.6k)](https://github.com/cucumber/godog) — Cucumber for golang ☆`2,640`
*   [orlangure/gnomock (⭐1.5k)](https://github.com/orlangure/gnomock) — Test with ephemeral Docker containers ☆`1,490`
*   [dnaeon/go-vcr (⭐1.4k)](https://github.com/dnaeon/go-vcr) — Record and replay HTTP for tests ☆`1,394`
*   [go-testfixtures/testfixtures (⭐1.2k)](https://github.com/go-testfixtures/testfixtures) — Rails-like test fixtures for Go ☆`1,233`
*   [fergusstrange/embedded-postgres (⭐1.2k)](https://github.com/fergusstrange/embedded-postgres) — Embedded PostgreSQL for testing ☆`1,211`
*   [chapar-rest/chapar (⭐703)](https://github.com/chapar-rest/chapar) — API testing for HTTP and gRPC ☆`705`
*   [gotestyourself/gotest.tools (⭐579)](https://github.com/gotestyourself/gotest.tools) — Testing utilities for Go ☆`578`
*   [maxatome/go-testdeep (⭐464)](https://github.com/maxatome/go-testdeep) — Flexible deep comparison in tests ☆`463`
*   [appleboy/gofight (⭐447)](https://github.com/appleboy/gofight) — Testing API Handler written in Golang. ☆`447`
*   [ysmood/got (⭐266)](https://github.com/ysmood/got) — An enjoyable golang test framework. ☆`267`
*   [viant/endly (⭐268)](https://github.com/viant/endly) — End to end functional test and automation framework ☆`268`
*   [adamluzsi/testcase (⭐132)](https://github.com/adamluzsi/testcase) — Opinionated testing framework ☆`133`
*   [kinbiko/jsonassert (⭐142)](https://github.com/kinbiko/jsonassert) — JSON assertion library for tests ☆`142`
*   [earthboundkid/be (⭐133)](https://github.com/earthboundkid/be) — The Go test helper for minimalists ☆`133`
*   [corbym/gocrest (⭐108)](https://github.com/corbym/gocrest) — GoCrest - Hamcrest-like matchers for Go ☆`108`
*   [madflojo/testcerts (⭐86)](https://github.com/madflojo/testcerts) — Generate test certificates on the fly ☆`85`
*   [hedhyw/gherkingen (⭐97)](https://github.com/hedhyw/gherkingen) — Behaviour Driven Development tests generator for Golang ☆`97`
*   [go-restit/restit (⭐56)](https://github.com/go-restit/restit) — A Go library help testing your RESTful API application ☆`56`
*   [viant/dsunit (⭐46)](https://github.com/viant/dsunit) — Datastore Testibility ☆`46`
*   [rekby/fixenv (⭐34)](https://github.com/rekby/fixenv) — Pytest-inspired fixture caching for Go tests ☆`34`
*   [abecodes/dft (⭐19)](https://github.com/abecodes/dft) — Docker wrapper for testing ☆`19`

### Testing Utilities

*   [dvyukov/go-fuzz (⭐4.9k)](https://github.com/dvyukov/go-fuzz) — Randomized testing for Go ☆`4,851`
*   [pingcap/failpoint (⭐891)](https://github.com/pingcap/failpoint) — Failpoint implementation for Go ☆`893`

### Validation

*   [go-playground/validator (⭐20k)](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`20,088`
*   [Oudwins/zog (⭐1.2k)](https://github.com/Oudwins/zog) — Zod-inspired schema validation ☆`1,200`
*   [gookit/validate (⭐1.2k)](https://github.com/gookit/validate) — Struct and data validation ☆`1,161`
*   [twharmon/govalid (⭐119)](https://github.com/twharmon/govalid) — Struct validation using tags ☆`119`
*   [osamingo/checkdigit (⭐114)](https://github.com/osamingo/checkdigit) — Check digit algorithms ☆`114`
*   [marrow16/valix (⭐31)](https://github.com/marrow16/valix) — Request validation package ☆`31`
*   [tiendc/go-validator (⭐31)](https://github.com/tiendc/go-validator) — Intuitive validation library ☆`31`

## Text & NLP

### Formatters

*   [dustin/go-humanize (⭐4.8k)](https://github.com/dustin/go-humanize) — Human-friendly unit formatting ☆`4,808`
*   [neilotoole/sq (⭐2.5k)](https://github.com/neilotoole/sq) — SQL data wrangler ☆`2,539`
*   [bojanz/address (⭐83)](https://github.com/bojanz/address) — Address handling for Go ☆`83`

### Markup Languages

*   [BurntSushi/toml (⭐5k)](https://github.com/BurntSushi/toml) — TOML parser with reflection ☆`4,984`
*   [yuin/goldmark (⭐4.9k)](https://github.com/yuin/goldmark) — Markdown parser for Go ☆`4,909`
*   [JohannesKaufmann/html-to-markdown (⭐3.7k)](https://github.com/JohannesKaufmann/html-to-markdown) — Convert HTML to Markdown ☆`3,748`
*   [pelletier/go-toml (⭐2k)](https://github.com/pelletier/go-toml) — TOML library for Go ☆`1,961`
*   [antchfx/htmlquery (⭐784)](https://github.com/antchfx/htmlquery) — XPath for HTML queries ☆`784`
*   [clbanning/mxj (⭐629)](https://github.com/clbanning/mxj) — XML to/from map conversion ☆`629`
*   [mmalcek/bafi (⭐116)](https://github.com/mmalcek/bafi) — Universal format converter ☆`116`

### Miscellaneous

*   [microcosm-cc/bluemonday (⭐3.7k)](https://github.com/microcosm-cc/bluemonday) — Fast HTML sanitizer for Go ☆`3,699`
*   [pemistahl/lingua-go (⭐1.4k)](https://github.com/pemistahl/lingua-go) — Natural language detection ☆`1,359`
*   [gosimple/slug (⭐1.3k)](https://github.com/gosimple/slug) — URL-friendly slugify ☆`1,328`
*   [arunsupe/semantic-grep (⭐1.2k)](https://github.com/arunsupe/semantic-grep) — Grep for similar words ☆`1,242`
*   [mattn/go-runewidth (⭐713)](https://github.com/mattn/go-runewidth) — Rune width for terminals ☆`714`
*   [hedhyw/rex (⭐214)](https://github.com/hedhyw/rex) — Flexible regex constructor ☆`214`
*   [IGLOU-EU/go-wildcard (⭐103)](https://github.com/IGLOU-EU/go-wildcard) — Fast wildcard matching ☆`103`
*   [JoshuaDoes/gofuckyourself (⭐71)](https://github.com/JoshuaDoes/gofuckyourself) — Swear filter for Go ☆`71`

### Morphological Analyzers

*   [nlpodyssey/spago (⭐1.9k)](https://github.com/nlpodyssey/spago) — ML and NLP library for Go ☆`1,851`
*   [ikawaha/kagome (⭐973)](https://github.com/ikawaha/kagome) — Japanese morphological analyzer ☆`974`
*   [afjoseph/RAKE.Go (⭐124)](https://github.com/afjoseph/RAKE.Go) — Rapid Keyword Extraction in Go ☆`124`
*   [jonreiter/govader (⭐55)](https://github.com/jonreiter/govader) — VADER sentiment analysis ☆`55`

### Parsers/Encoders/Decoders

*   [mvdan/sh (⭐8.9k)](https://github.com/mvdan/sh) — Shell parser and formatter ☆`8,914`
*   [mmcdole/gofeed (⭐2.8k)](https://github.com/mmcdole/gofeed) — Parse RSS, Atom, JSON feeds ☆`2,857`
*   [google/go-querystring (⭐2.1k)](https://github.com/google/go-querystring) — Encode structs to URL query strings ☆`2,144`
*   [olebedev/when (⭐1.5k)](https://github.com/olebedev/when) — Natural language date parser ☆`1,462`
*   [adrianmo/go-nmea (⭐264)](https://github.com/adrianmo/go-nmea) — NMEA sentence parser ☆`264`
*   [yassinebenaid/godump (⭐223)](https://github.com/yassinebenaid/godump) — Dump any Go variable ☆`223`
*   [editorconfig/editorconfig-core-go (⭐155)](https://github.com/editorconfig/editorconfig-core-go) — EditorConfig core in Go ☆`155`
*   [bzick/tokenizer (⭐141)](https://github.com/bzick/tokenizer) — Tokenizer/lexer for Go ☆`141`
*   [emersion/go-vcard (⭐128)](https://github.com/emersion/go-vcard) — vCard parser and formatter ☆`128`
*   [polera/gonameparts (⭐43)](https://github.com/polera/gonameparts) — Takes a full name and splits it into individual name parts ☆`43`

### Scrapers

*   [gocolly/colly (⭐25k)](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,383`
*   [PuerkitoBio/goquery (⭐15k)](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,975`
*   [mvdan/xurls (⭐1.3k)](https://github.com/mvdan/xurls) — Extract URLs from text ☆`1,266`
*   [s0rg/crawley (⭐340)](https://github.com/s0rg/crawley) — The unix-way web crawler ☆`340`

### Text Analysis

*   [blevesearch/bleve (⭐11k)](https://github.com/blevesearch/bleve) — Text/numeric/geo/vector indexing library ☆`11,158`
*   [derekparker/trie (⭐791)](https://github.com/derekparker/trie) — Trie for extremely fast prefix search ☆`791`
*   [agnivade/levenshtein (⭐471)](https://github.com/agnivade/levenshtein) — Go implementation to calculate Levenshtein Distance. ☆`471`
*   [plar/go-adaptive-radix-tree (⭐414)](https://github.com/plar/go-adaptive-radix-tree) — Adaptive Radix Trees implemented in Go ☆`413`

### Tokenizers

*   [go-ego/gse (⭐2.8k)](https://github.com/go-ego/gse) — Multilingual text segmentation ☆`2,839`
*   [pebbe/textcat (⭐73)](https://github.com/pebbe/textcat) — N-gram text categorization ☆`73`

### Translation

*   [nicksnyder/go-i18n (⭐3.5k)](https://github.com/nicksnyder/go-i18n) — Translate Go programs ☆`3,534`
*   [leonelquinteros/gotext (⭐506)](https://github.com/leonelquinteros/gotext) — GNU gettext for Go ☆`505`
*   [vorlif/spreak (⭐94)](https://github.com/vorlif/spreak) — Gettext-based translation library ☆`94`
*   [invopop/ctxi18n (⭐94)](https://github.com/invopop/ctxi18n) — Context-based i18n for Go ☆`94`
*   [mehanizm/iuliia-go (⭐57)](https://github.com/mehanizm/iuliia-go) — Cyrillic to Latin transliteration ☆`57`

## Third-party APIs

### Cloud Provider APIs

*   [googleapis/google-cloud-go (⭐4.5k)](https://github.com/googleapis/google-cloud-go) — Google Cloud Client Libraries for Go. ☆`4,481`
*   [googleapis/google-api-go-client (⭐4.5k)](https://github.com/googleapis/google-api-go-client) — Auto-generated Google APIs for Go. ☆`4,459`
*   [aws/aws-sdk-go-v2 (⭐3.6k)](https://github.com/aws/aws-sdk-go-v2) — AWS SDK for the Go programming language. ☆`3,616`
*   [minio/minio-go (⭐3k)](https://github.com/minio/minio-go) — High-performance object storage ☆`2,976`
*   [rhnvrm/simples3 (⭐205)](https://github.com/rhnvrm/simples3) — Simple AWS S3 library using REST ☆`205`
*   [circa10a/go-aws-news (⭐19)](https://github.com/circa10a/go-aws-news) — Go app + library to fetch what's new from AWS ☆`19`
*   [chainifynet/aws-encryption-sdk-go (⭐23)](https://github.com/chainifynet/aws-encryption-sdk-go) — AWS Encryption SDK for Go ☆`23`

### Other APIs

*   [codingsince1985/geo-golang (⭐546)](https://github.com/codingsince1985/geo-golang) — Go library to access geocoding and reverse geocoding APIs ☆`546`
*   [cyruzin/golang-tmdb (⭐163)](https://github.com/cyruzin/golang-tmdb) — Wrapper for TMDb API ☆`164`
*   [gregdel/pushover (⭐157)](https://github.com/gregdel/pushover) — Go wrapper for the Pushover API ☆`157`
*   [mvrilo/go-redoc (⭐95)](https://github.com/mvrilo/go-redoc) — Embedded OpenAPI documentation ☆`95`
*   [rapito/go-spotify (⭐53)](https://github.com/rapito/go-spotify) — Go library for the Spotify Web API ☆`53`
*   [rinchsan/device-check-go (⭐26)](https://github.com/rinchsan/device-check-go) — iOS DeviceCheck SDK for Go ☆`26`
*   [staskobzar/goami2 (⭐22)](https://github.com/staskobzar/goami2) — Simple Asterisk Manager Interface (AMI) library fo golang ☆`22`
*   [Icelain/jokeapi (⭐27)](https://github.com/Icelain/jokeapi) — Official golang wrapper for Sv443's jokeapi. ☆`27`

### Productivity APIs

*   [mk-5/fjira (⭐272)](https://github.com/mk-5/fjira) — The golang fuzzy-find cli jira interface ☆`272`
*   [adlio/trello (⭐228)](https://github.com/adlio/trello) — Trello API wrapper for Go ☆`228`
*   [ctreminiom/go-atlassian (⭐215)](https://github.com/ctreminiom/go-atlassian) — Atlassian Cloud API client ☆`215`
*   [koltyakov/gosip (⭐169)](https://github.com/koltyakov/gosip) — SharePoint SDK for Go ☆`169`
*   [FreeLeh/GoFreeDB (⭐90)](https://github.com/FreeLeh/GoFreeDB) — Database on top of Google Sheets ☆`90`
*   [mehanizm/airtable (⭐86)](https://github.com/mehanizm/airtable) — Simple golang airtable API wrapper ☆`86`
*   [k-capehart/go-salesforce (⭐56)](https://github.com/k-capehart/go-salesforce) — Salesforce REST API client ☆`56`

## Utilities

### Build & Release

*   [goreleaser/goreleaser (⭐16k)](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,952`
*   [create-go-app/cli (⭐2.8k)](https://github.com/create-go-app/cli) — Create production-ready Go projects ☆`2,766`
*   [miniscruff/changie (⭐891)](https://github.com/miniscruff/changie) — Automated changelog tool ☆`891`
*   [karl-cardenas-coding/go-lambda-cleanup (⭐97)](https://github.com/karl-cardenas-coding/go-lambda-cleanup) — Remove old AWS Lambda versions ☆`98`

### CLI Tools

*   [junegunn/fzf (⭐82k)](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`81,915`
*   [wagoodman/dive (⭐54k)](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`54,348`
*   [xo/usql (⭐10k)](https://github.com/xo/usql) — Universal SQL CLI ☆`10,040`
*   [joshmedeski/sesh (⭐2.7k)](https://github.com/joshmedeski/sesh) — Terminal session manager ☆`2,703`
*   [itchyny/bed (⭐1.3k)](https://github.com/itchyny/bed) — Binary editor in Go ☆`1,347`
*   [owenthereal/upterm (⭐1.3k)](https://github.com/owenthereal/upterm) — Instant terminal sharing ☆`1,263`
*   [alajmo/mani (⭐733)](https://github.com/alajmo/mani) — CLI for managing repositories ☆`738`
*   [Unrud/remote-touchpad (⭐668)](https://github.com/Unrud/remote-touchpad) — Control mouse/keyboard remotely ☆`668`
*   [chenquan/diskusage (⭐309)](https://github.com/chenquan/diskusage) — Fast disk usage analyzer ☆`310`
*   [reugn/wifiqr (⭐287)](https://github.com/reugn/wifiqr) — Generate Wi-Fi QR codes ☆`287`
*   [hedhyw/json-log-viewer (⭐229)](https://github.com/hedhyw/json-log-viewer) — Interactive JSON log viewer ☆`230`
*   [hrtsegv/gitcs (⭐133)](https://github.com/hrtsegv/gitcs) — Git contributions graph generator ☆`133`
*   [antham/yogo (⭐47)](https://github.com/antham/yogo) — Check yopmail from CLI ☆`48`

### Data Conversion

*   [samber/lo (⭐21k)](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`21,391`
*   [duke-git/lancet (⭐5.3k)](https://github.com/duke-git/lancet) — Comprehensive util library ☆`5,296`
*   [darccio/mergo (⭐3.1k)](https://github.com/darccio/mergo) — Merge Go structs and maps ☆`3,103`
*   [goforj/godump (⭐1.7k)](https://github.com/goforj/godump) — Pretty-printer for Go structs ☆`1,748`
*   [gookit/filter (⭐151)](https://github.com/gookit/filter) — Data filtering and conversion ☆`151`
*   [xorcare/pointer (⭐48)](https://github.com/xorcare/pointer) — Create optional field pointers ☆`48`
*   [tiendc/gofn (⭐53)](https://github.com/tiendc/gofn) — High-performance generic functions ☆`53`
*   [shockerli/cvt (⭐54)](https://github.com/shockerli/cvt) — Safe type conversion ☆`54`

### Database Extensions

*   [jmoiron/sqlx (⭐18k)](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,701`
*   [georgysavva/scany (⭐1.5k)](https://github.com/georgysavva/scany) — Scan database rows to structs ☆`1,522`
*   [blockloop/scan (⭐614)](https://github.com/blockloop/scan) — Scan SQL rows to structs ☆`613`

### Date and Time

*   [dromara/carbon (⭐5.2k)](https://github.com/dromara/carbon) — Developer-friendly time package ☆`5,224`
*   [yaa110/go-persian-calendar (⭐240)](https://github.com/yaa110/go-persian-calendar) — Persian calendar for Go ☆`242`
*   [bykof/gostradamus (⭐208)](https://github.com/bykof/gostradamus) — Better DateTimes for Go ☆`208`
*   [rickb777/date (⭐143)](https://github.com/rickb777/date) — Date handling package ☆`143`
*   [relvacode/iso8601 (⭐158)](https://github.com/relvacode/iso8601) — Fast ISO8601 date parser ☆`158`

### Dependency Injection

*   [uber-go/fx (⭐7.6k)](https://github.com/uber-go/fx) — DI-based application framework ☆`7,610`
*   [uber-go/dig (⭐4.5k)](https://github.com/uber-go/dig) — Reflection-based DI toolkit ☆`4,486`
*   [goioc/di (⭐379)](https://github.com/goioc/di) — Simple DI for Go ☆`378`
*   [go-kod/kod (⭐198)](https://github.com/go-kod/kod) — DI with aspect-oriented support ☆`198`
*   [i-love-flamingo/dingo (⭐188)](https://github.com/i-love-flamingo/dingo) — DI framework for Go ☆`188`
*   [NVIDIA/gontainer (⭐153)](https://github.com/NVIDIA/gontainer) — Simple DI container ☆`153`
*   [junioryono/godi (⭐75)](https://github.com/junioryono/godi) — DI with service lifetimes ☆`75`
*   [matzefriedrich/parsley (⭐34)](https://github.com/matzefriedrich/parsley) — Reflection-based DI package ☆`34`
*   [muir/nject (⭐32)](https://github.com/muir/nject) — Type-safe DI for Go ☆`32`
*   [firasdarwish/ore (⭐27)](https://github.com/firasdarwish/ore) — Advanced DI solution ☆`27`
*   [logrange/linker (⭐35)](https://github.com/logrange/linker) — DI and IoC package ☆`35`
*   [componego/componego (⭐29)](https://github.com/componego/componego) — Component-oriented framework ☆`29`
*   [gontainer/gontainer (⭐17)](https://github.com/gontainer/gontainer) — YAML-based DI container ☆`17`

### Error Handling

*   [hashicorp/go-multierror (⭐2.6k)](https://github.com/hashicorp/go-multierror) — Represent multiple errors as one ☆`2,576`
*   [cockroachdb/errors (⭐2.4k)](https://github.com/cockroachdb/errors) — Error library with portability ☆`2,449`
*   [rotisserie/eris (⭐1.8k)](https://github.com/rotisserie/eris) — Errors with readable stack traces ☆`1,790`
*   [joomcode/errorx (⭐1.3k)](https://github.com/joomcode/errorx) — Comprehensive error handling ☆`1,270`
*   [ztrue/tracerr (⭐1.1k)](https://github.com/ztrue/tracerr) — Errors with stack trace ☆`1,120`
*   [samber/oops (⭐970)](https://github.com/samber/oops) — Structured error handling ☆`973`
*   [Southclaws/fault (⭐311)](https://github.com/Southclaws/fault) — Composable error wrapping ☆`310`

### File Handling

*   [schollz/croc (⭐36k)](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`37,700`
*   [qax-os/excelize (⭐21k)](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,795`
*   [pdfcpu/pdfcpu (⭐8.7k)](https://github.com/pdfcpu/pdfcpu) — PDF processor in Go ☆`8,723`
*   [spf13/afero (⭐6.7k)](https://github.com/spf13/afero) — Filesystem abstraction for Go ☆`6,679`
*   [dundee/gdu (⭐5.8k)](https://github.com/dundee/gdu) — Fast disk usage analyzer ☆`5,839`
*   [unidoc/unioffice (⭐4.9k)](https://github.com/unidoc/unioffice) — Office document library ☆`4,896`
*   [root-gg/plik (⭐1.8k)](https://github.com/root-gg/plik) — Temporary file upload system ☆`1,800`
*   [SebastiaanKlippert/go-wkhtmltopdf (⭐1.2k)](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) — HTML to PDF wrapper ☆`1,181`
*   [otiai10/copy (⭐772)](https://github.com/otiai10/copy) — Copy directories recursively ☆`771`
*   [ulikunitz/xz (⭐559)](https://github.com/ulikunitz/xz) — Pure golang package for reading and writing xz-compressed files ☆`559`
*   [mholt/archives (⭐430)](https://github.com/mholt/archives) — Create and extract archives ☆`432`
*   [viant/afs (⭐390)](https://github.com/viant/afs) — Abstract file storage ☆`390`
*   [C2FO/vfs (⭐367)](https://github.com/C2FO/vfs) — Virtual file system for Go ☆`367`
*   [gen2brain/go-unarr (⭐310)](https://github.com/gen2brain/go-unarr) — Decompression library bindings ☆`310`
*   [gomutex/godocx (⭐265)](https://github.com/gomutex/godocx) — Go library for reading and writing Microsoft Docx ☆`263`
*   [charlievieth/fastwalk (⭐144)](https://github.com/charlievieth/fastwalk) — Fast directory traversal ☆`144`
*   [artonge/go-csv-tag (⭐131)](https://github.com/artonge/go-csv-tag) — CSV reading with tags ☆`131`
*   [parsyl/parquet (⭐127)](https://github.com/parsyl/parquet) — Parquet file library ☆`127`
*   [adelowo/gulter (⭐72)](https://github.com/adelowo/gulter) — Multipart form handling ☆`72`
*   [go-the-way/exl (⭐33)](https://github.com/go-the-way/exl) — Excel binding to struct written in Go.(Only supports Go1.18+) ☆`33`

### Forms

*   [justinas/nosurf (⭐1.7k)](https://github.com/justinas/nosurf) — CSRF protection middleware ☆`1,742`
*   [gorilla/csrf (⭐1.2k)](https://github.com/gorilla/csrf) — CSRF prevention middleware ☆`1,200`
*   [go-playground/form (⭐920)](https://github.com/go-playground/form) — URL values to structs ☆`920`
*   [ggicci/httpin (⭐387)](https://github.com/ggicci/httpin) — HTTP request to struct binding ☆`388`
*   [sonh/qs (⭐82)](https://github.com/sonh/qs) — Encode structs to query params ☆`82`
*   [cinar/checker (⭐48)](https://github.com/cinar/checker) — Input validation with struct tags ☆`48`

### Functional

*   [samber/mo (⭐3.4k)](https://github.com/samber/mo) — Monads and FP for Go ☆`3,384`
*   [BooleanCat/go-functional (⭐537)](https://github.com/BooleanCat/go-functional) — Iterator library for Go ☆`537`
*   [rjNemo/underscore (⭐118)](https://github.com/rjNemo/underscore) — Functional helpers for Go ☆`118`

### General

*   [wabarc/wayback (⭐2.2k)](https://github.com/wabarc/wayback) — Web archiving tool with IM interface ☆`2,219`
*   [gabriel-vasile/mimetype (⭐2k)](https://github.com/gabriel-vasile/mimetype) — MIME type detection by magic numbers ☆`1,996`
*   [qmuntal/stateless (⭐1.4k)](https://github.com/qmuntal/stateless) — Go library for creating finite state machines ☆`1,370`
*   [jonboulle/clockwork (⭐727)](https://github.com/jonboulle/clockwork) — a fake clock for golang ☆`726`
*   [Boeing/config-file-validator (⭐509)](https://github.com/Boeing/config-file-validator) — Cross-platform CLI tool to validate configuration files across 18 formats. Syntax and schema validation with JSON Schema, XSD, and SchemaStore integration. Written in Go. ☆`509`
*   [ungerik/go-dry (⭐488)](https://github.com/ungerik/go-dry) — DRY (don't repeat yourself) package for Go ☆`488`
*   [subosito/gotenv (⭐309)](https://github.com/subosito/gotenv) — Load environment variables from `.env` or `io.Reader` in Go. ☆`309`
*   [viant/toolbox (⭐230)](https://github.com/viant/toolbox) — Toolbox - go utility library ☆`230`
*   [maja42/goval (⭐174)](https://github.com/maja42/goval) — Expression evaluation in golang ☆`174`
*   [jfcg/sorty (⭐145)](https://github.com/jfcg/sorty) — Fast Concurrent / Parallel Sorting in Go ☆`145`
*   [commander-cli/cmd (⭐161)](https://github.com/commander-cli/cmd) — A simple package to execute shell commands on linux, windows and osx ☆`161`
*   [syntaqx/cookie (⭐115)](https://github.com/syntaqx/cookie) — Cookies, but with structs, for happiness. ☆`114`
*   [tiendc/go-deepcopy (⭐130)](https://github.com/tiendc/go-deepcopy) — Fast deep-copy library for Go ☆`130`
*   [arthurkushman/pgo (⭐89)](https://github.com/arthurkushman/pgo) — Go library for PHP community with convenient functions ☆`89`
*   [pioz/countries (⭐98)](https://github.com/pioz/countries) — All you need when you are working with countries in Go. ☆`98`
*   [wzshiming/gotype (⭐66)](https://github.com/wzshiming/gotype) — Golang source code parsing, usage like reflect package ☆`66`
*   [rkoesters/xdg (⭐50)](https://github.com/rkoesters/xdg) — FreeDesktop.org (xdg) Specs implemented in Go ☆`50`
*   [icza/backscanner (⭐69)](https://github.com/icza/backscanner) — Scan file lines backward ☆`69`
*   [nikolaydubina/watchhttp (⭐35)](https://github.com/nikolaydubina/watchhttp) — Expose command output via HTTP ☆`35`
*   [mikekonan/go-types (⭐24)](https://github.com/mikekonan/go-types) — OpenAPI3 types for Go ☆`24`
*   [kazhuravlev/just (⭐38)](https://github.com/kazhuravlev/just) — Collection of useful functions. Complete simple tasks faster! ☆`38`
*   [lrita/numa (⭐40)](https://github.com/lrita/numa) — NUMA utility library for Go ☆`40`
*   [osamingo/gosh (⭐37)](https://github.com/osamingo/gosh) — Provide Go Statistics Handler, Struct, Measure Method ☆`37`
*   [floatdrop/debounce (⭐37)](https://github.com/floatdrop/debounce) — A zero-allocation debouncer ☆`37`
*   [skovtunenko/graterm (⭐30)](https://github.com/skovtunenko/graterm) — Graceful termination primitives ☆`30`

### Logging

*   [sirupsen/logrus (⭐26k)](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,749`
*   [uber-go/zap (⭐25k)](https://github.com/uber-go/zap) — Fast structured logging ☆`24,580`
*   [rs/zerolog (⭐12k)](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,479`
*   [golang/glog (⭐3.6k)](https://github.com/golang/glog) — Leveled execution logs ☆`3,600`
*   [k0kubun/pp (⭐2k)](https://github.com/k0kubun/pp) — Colored pretty printer for Go ☆`2,048`
*   [lmittmann/tint (⭐1.3k)](https://github.com/lmittmann/tint) — Colorized slog handler ☆`1,323`
*   [Lifailon/lazyjournal (⭐1.3k)](https://github.com/Lifailon/lazyjournal) — TUI for journald, Docker, K8s logs ☆`1,326`
*   [getsentry/sentry-go (⭐1.1k)](https://github.com/getsentry/sentry-go) — Official Sentry SDK for Go ☆`1,098`
*   [phuslu/log (⭐870)](https://github.com/phuslu/log) — Fastest structured logging ☆`870`
*   [samber/slog-multi (⭐629)](https://github.com/samber/slog-multi) — Workflow design for slog handlers ☆`631`
*   [gookit/slog (⭐547)](https://github.com/gookit/slog) — Configurable logging library ☆`549`
*   [henvic/httpretty (⭐414)](https://github.com/henvic/httpretty) — Pretty-print HTTP requests ☆`414`
*   [hashicorp/logutils (⭐372)](https://github.com/hashicorp/logutils) — Logging utilities for Go ☆`372`
*   [simukti/sqldb-logger (⭐382)](https://github.com/simukti/sqldb-logger) — SQL database logger ☆`382`
*   [samber/slog-formatter (⭐220)](https://github.com/samber/slog-formatter) — Slog attribute formatting ☆`221`
*   [DeRuina/timberjack (⭐150)](https://github.com/DeRuina/timberjack) — Log rolling library ☆`153`
*   [yuseferi/zax (⭐37)](https://github.com/yuseferi/zax) — Zap logger with context ☆`37`
*   [clok/kemba (⭐18)](https://github.com/clok/kemba) — Tiny debug logging tool ☆`18`

### Networking Utils

*   [cristianoliveira/ergo (⭐648)](https://github.com/cristianoliveira/ergo) — Manage apps on different ports ☆`649`
*   [htcat/htcat (⭐557)](https://github.com/htcat/htcat) — Parallel HTTP download ☆`557`
*   [ferama/rospo (⭐371)](https://github.com/ferama/rospo) — Persistent SSH tunnels ☆`371`

### Project Layout

*   [golang-standards/project-layout (⭐56k)](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`56,344`
*   [Melkeydev/go-blueprint (⭐8.9k)](https://github.com/Melkeydev/go-blueprint) — Spin up Go projects with popular frameworks ☆`8,895`
*   [ardanlabs/service (⭐4.1k)](https://github.com/ardanlabs/service) — K8s service starter kit ☆`4,096`
*   [Shpota/goxygen (⭐3.6k)](https://github.com/Shpota/goxygen) — Generate full-stack web projects ☆`3,594`
*   [mikestefanello/pagoda (⭐2.9k)](https://github.com/mikestefanello/pagoda) — Full-stack web development starter kit ☆`2,945`
*   [go-nunu/nunu (⭐2.6k)](https://github.com/go-nunu/nunu) — CLI for building Go apps ☆`2,592`
*   [sagikazarmark/modern-go-application (⭐1.9k)](https://github.com/sagikazarmark/modern-go-application) — Modern Go app example ☆`1,943`
*   [naughtygopher/goapp (⭐1.1k)](https://github.com/naughtygopher/goapp) — Opinionated web app structure ☆`1,068`
*   [lacion/cookiecutter-golang (⭐737)](https://github.com/lacion/cookiecutter-golang) — Go project template ☆`737`
*   [allaboutapps/go-starter (⭐617)](https://github.com/allaboutapps/go-starter) — Production-ready RESTful API template ☆`620`
*   [golang-templates/seed (⭐564)](https://github.com/golang-templates/seed) — Go app GitHub template ☆`565`
*   [Fs02/go-todo-backend (⭐338)](https://github.com/Fs02/go-todo-backend) — Go Todo Backend example using modular project layout for product microservice. ☆`338`
*   [raeperd/kickstart.go (⭐111)](https://github.com/raeperd/kickstart.go) — Minimal HTTP server template ☆`111`
*   [wangyoucao577/go-project-layout (⭐26)](https://github.com/wangyoucao577/go-project-layout) — Go project structure guide ☆`26`

### Resilience & Retry

*   [avast/retry-go (⭐2.9k)](https://github.com/avast/retry-go) — Simple retry mechanism ☆`2,939`
*   [eapache/go-resiliency (⭐2.3k)](https://github.com/eapache/go-resiliency) — Resiliency patterns for golang ☆`2,343`
*   [failsafe-go/failsafe-go (⭐2.2k)](https://github.com/failsafe-go/failsafe-go) — Fault tolerance patterns ☆`2,232`
*   [cep21/circuit (⭐816)](https://github.com/cep21/circuit) — Hystrix-like circuit breaker ☆`815`
*   [mennanov/limiters (⭐648)](https://github.com/mennanov/limiters) — Distributed rate limiters ☆`650`
*   [kamilsk/retry (⭐344)](https://github.com/kamilsk/retry) — Advanced retry mechanism ☆`344`
*   [webriots/rate (⭐170)](https://github.com/webriots/rate) — High-performance rate limiter ☆`170`

### Strings

*   [abhimanyu003/sttr (⭐1.3k)](https://github.com/abhimanyu003/sttr) — CLI string operations ☆`1,337`
*   [gobeam/stringy (⭐248)](https://github.com/gobeam/stringy) — String case conversions ☆`249`
*   [ozgio/strutil (⭐206)](https://github.com/ozgio/strutil) — String utilities for Go ☆`206`

### System & Process

*   [cilium/ebpf (⭐7.9k)](https://github.com/cilium/ebpf) — eBPF library for Go ☆`7,874`
*   [maruel/panicparse (⭐3.7k)](https://github.com/maruel/panicparse) — Crash your app in style ☆`3,711`
*   [immortal/immortal (⭐837)](https://github.com/immortal/immortal) — Cross-platform supervisor ☆`837`
*   [derekparker/delve (⭐662)](https://github.com/derekparker/delve) — Delve is a debugger for the Go programming language. ☆`661`
*   [gotranspile/cxgo (⭐394)](https://github.com/gotranspile/cxgo) — Transpile C to Go ☆`394`

### UUID

*   [google/uuid (⭐6.1k)](https://github.com/google/uuid) — UUID generation and parsing ☆`6,117`
*   [oklog/ulid (⭐5k)](https://github.com/oklog/ulid) — ULID implementation ☆`5,043`
*   [gofrs/uuid (⭐1.8k)](https://github.com/gofrs/uuid) — UUID library for Go ☆`1,814`
*   [osamingo/indigo (⭐112)](https://github.com/osamingo/indigo) — Sonyflake-based ID generator ☆`112`
*   [sdrapkin/guid (⭐74)](https://github.com/sdrapkin/guid) — Fast cryptographically safe Guid generator for Go ☆`75`
*   [twharmon/gouid (⭐27)](https://github.com/twharmon/gouid) — Fast, dependable universally unique ids ☆`27`

## Version Control & Packages

### Git APIs

*   [google/go-github (⭐11k)](https://github.com/google/go-github) — Go library for accessing the GitHub v3 API ☆`11,275`
*   [shurcooL/githubv4 (⭐1.2k)](https://github.com/shurcooL/githubv4) — GitHub GraphQL API v4 client ☆`1,194`
*   [go-playground/webhooks (⭐1k)](https://github.com/go-playground/webhooks) — Webhook receiver for GitHub, Bitbucket, GitLab, Gogs ☆`1,027`
*   [andygrunwald/go-trending (⭐147)](https://github.com/andygrunwald/go-trending) — Access GitHub trending repositories ☆`147`
*   [andygrunwald/go-gerrit (⭐106)](https://github.com/andygrunwald/go-gerrit) — Go client/library for Gerrit Code Review ☆`106`

### Package Management

*   [anchore/syft (⭐9.2k)](https://github.com/anchore/syft) — SBOM generator for containers ☆`9,273`
*   [nao1215/gup (⭐589)](https://github.com/nao1215/gup) — Fast manager for Go-installed binaries in $GOBIN: update, export/import, and migrate toolsets across machines ☆`590`
*   [marwanhawari/stew (⭐352)](https://github.com/marwanhawari/stew) — An independent package manager for compiled binaries. ☆`352`
*   [chaindead/modup (⭐65)](https://github.com/chaindead/modup) — TUI for Go dependency updates ☆`65`

### Version Control

*   [go-git/go-git (⭐7.6k)](https://github.com/go-git/go-git) — Pure Go Git implementation ☆`7,627`
*   [antham/chyle (⭐162)](https://github.com/antham/chyle) — Changelog generator from Git ☆`162`
*   [gabyx/Githooks (⭐125)](https://github.com/gabyx/Githooks) — Per-repo shared Git hooks ☆`126`
*   [antham/gommit (⭐117)](https://github.com/antham/gommit) — Enforce git message commit consistency ☆`117`
*   [sourcegraph/go-vcs (⭐81)](https://github.com/sourcegraph/go-vcs) — manipulate and inspect VCS repositories in Go ☆`81`
*   [jfrog/froggit-go (⭐54)](https://github.com/jfrog/froggit-go) — Universal VCS client library ☆`54`
*   [kazhuravlev/git-tools (⭐33)](https://github.com/kazhuravlev/git-tools) — Useful set of tools which helps to manage git tags ☆`33`

## Web Development

### Microservices

*   [zeromicro/go-zero (⭐33k)](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`33,210`
*   [go-kratos/kratos (⭐26k)](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,802`
*   [micro/go-micro (⭐23k)](https://github.com/micro/go-micro) — A Go agent harness and service framework ☆`22,965`
*   [smallnest/rpcx (⭐8.3k)](https://github.com/smallnest/rpcx) — Feature-rich RPC framework ☆`8,307`
*   [cloudwego/kitex (⭐8k)](https://github.com/cloudwego/kitex) — High-performance Go RPC framework ☆`8,001`
*   [go-dev-frame/sponge (⭐2.9k)](https://github.com/go-dev-frame/sponge) — Code generation framework for Go ☆`2,855`
*   [go-eagle/eagle (⭐2.4k)](https://github.com/go-eagle/eagle) — A Go framework for the API or Microservice ☆`2,428`
*   [unionj-cloud/go-doudou (⭐1.2k)](https://github.com/unionj-cloud/go-doudou) — OpenAPI 3 and gRPC microservices framework ☆`1,172`
*   [trpc-group/trpc-go (⭐1.2k)](https://github.com/trpc-group/trpc-go) — A pluggable, high-performance RPC framework written in golang ☆`1,182`
*   [gmsec/micro (⭐27)](https://github.com/gmsec/micro) — A Go distributed systems development framework ☆`27`

### Middlewares

*   [urfave/negroni (⭐7.5k)](https://github.com/urfave/negroni) — Idiomatic HTTP Middleware for Golang ☆`7,526`
*   [tdewolff/minify (⭐4.1k)](https://github.com/tdewolff/minify) — Go minifiers for web formats ☆`4,126`
*   [rs/cors (⭐2.9k)](https://github.com/rs/cors) — Go net/http configurable handler to handle CORS requests ☆`2,893`
*   [didip/tollbooth (⭐2.9k)](https://github.com/didip/tollbooth) — Simple middleware to rate-limit HTTP requests. ☆`2,859`
*   [unrolled/render (⭐2k)](https://github.com/unrolled/render) — Render JSON, XML, HTML, binary ☆`1,997`
*   [lingrino/go-fault (⭐555)](https://github.com/lingrino/go-fault) — go fault injection library ☆`554`
*   [jub0bs/cors (⭐224)](https://github.com/jub0bs/cors) — perhaps the best CORS middleware library for Go ☆`223`
*   [faabiosr/echo-middleware (⭐16)](https://github.com/faabiosr/echo-middleware) — Middlewares for Echo framework ☆`16`

### Routers

*   [go-chi/chi (⭐23k)](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`22,568`
*   [gorilla/mux (⭐22k)](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,832`
*   [gowww/router (⭐185)](https://github.com/gowww/router) — A lightning fast HTTP router ☆`185`
*   [claygod/Bxog (⭐104)](https://github.com/claygod/Bxog) — Bxog is a simple and fast HTTP router for Go (HTTP request multiplexer). ☆`104`
*   [ngamux/ngamux (⭐71)](https://github.com/ngamux/ngamux) — Simple HTTP router for Go ☆`71`
*   [bmf-san/goblin (⭐82)](https://github.com/bmf-san/goblin) — A golang http router based on trie tree. ☆`81`
*   [muir/nchi (⭐19)](https://github.com/muir/nchi) — golang http router with elegance, speed, and flexibility ☆`19`

### Template Engines

*   [a-h/templ (⭐10k)](https://github.com/a-h/templ) — A language for writing HTML user interfaces in Go. ☆`10,418`
*   [johnfercher/maroto (⭐2.7k)](https://github.com/johnfercher/maroto) — Create PDFs with Bootstrap grid ☆`2,742`
*   [CloudyKit/jet (⭐1.4k)](https://github.com/CloudyKit/jet) — Jet template engine ☆`1,404`
*   [osteele/liquid (⭐353)](https://github.com/osteele/liquid) — A Liquid template engine in Go ☆`355`
*   [go-sprout/sprout (⭐224)](https://github.com/go-sprout/sprout) — Template functions for Go ☆`225`
*   [goradd/got (⭐38)](https://github.com/goradd/got) — Template engine with Go code output ☆`38`

### Web Frameworks

*   [gin-gonic/gin (⭐89k)](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`88,939`
*   [gofiber/fiber (⭐40k)](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`40,002`
*   [beego/beego (⭐32k)](https://github.com/beego/beego) — High-performance web framework ☆`32,409`
*   [labstack/echo (⭐33k)](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,546`
*   [gofr-dev/gofr (⭐21k)](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`21,117`
*   [gogf/gf (⭐13k)](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,228`
*   [cloudwego/hertz (⭐7.3k)](https://github.com/cloudwego/hertz) — High-performance HTTP framework ☆`7,308`
*   [goadesign/goa (⭐6.1k)](https://github.com/goadesign/goa) — Design-first API framework ☆`6,090`
*   [apache/dubbo-go (⭐4.9k)](https://github.com/apache/dubbo-go) — Go Implementation For Apache Dubbo . ☆`4,938`
*   [goravel/goravel (⭐4.8k)](https://github.com/goravel/goravel) — The full-featured Golang Development Framework skeleton ☆`4,788`
*   [danielgtaylor/huma (⭐4.2k)](https://github.com/danielgtaylor/huma) — Huma REST/HTTP API Framework for Golang with OpenAPI 3.1 ☆`4,259`
*   [documize/community (⭐2.4k)](https://github.com/documize/community) — Modern Confluence alternative ☆`2,413`
*   [go-goyave/goyave (⭐1.8k)](https://github.com/go-goyave/goyave) — The enterprise REST API framework ☆`1,774`
*   [go-fuego/fuego (⭐1.7k)](https://github.com/go-fuego/fuego) — Web framework with OpenAPI 3 ☆`1,757`
*   [templui/templui (⭐1.6k)](https://github.com/templui/templui) — UI components for Templ ☆`1,626`
*   [savsgio/atreugo (⭐1.3k)](https://github.com/savsgio/atreugo) — Micro web framework on fasthttp ☆`1,304`
*   [ankorstore/yokai (⭐836)](https://github.com/ankorstore/yokai) — Modular framework for Go apps ☆`837`
*   [indeedeng/iwf (⭐649)](https://github.com/indeedeng/iwf) — Workflow-as-code orchestration ☆`653`
*   [i-love-flamingo/flamingo-commerce (⭐590)](https://github.com/i-love-flamingo/flamingo-commerce) — Flexible Go web framework ☆`590`
*   [fastschema/fastschema (⭐560)](https://github.com/fastschema/fastschema) — All-in-One Backend as a Service with Headless CMS Power ☆`566`
*   [i-love-flamingo/flamingo (⭐559)](https://github.com/i-love-flamingo/flamingo) — Flexible Go web framework ☆`559`
*   [rookie-ninja/rk-boot (⭐572)](https://github.com/rookie-ninja/rk-boot) — Enterprise microservice framework ☆`572`
*   [uadmin/uadmin (⭐354)](https://github.com/uadmin/uadmin) — The web framework for Golang ☆`354`
*   [xxjwxc/ginrpc (⭐304)](https://github.com/xxjwxc/ginrpc) — gin auto binding, grpc and annotated route ☆`304`
*   [hidevopsio/hiboot (⭐180)](https://github.com/hidevopsio/hiboot) — High-performance CLI and web apps ☆`179`
*   [beatlabs/patron (⭐127)](https://github.com/beatlabs/patron) — Cloud-native microservice framework ☆`127`
*   [claygod/microservice (⭐123)](https://github.com/claygod/microservice) — Simple microservice framework ☆`123`
*   [gone-io/gone (⭐131)](https://github.com/gone-io/gone) — Lightweight DI framework ☆`131`
*   [gookit/rux (⭐99)](https://github.com/gookit/rux) — Simple and fast web framework ☆`100`
*   [yaitoo/xun (⭐92)](https://github.com/yaitoo/xun) — Web framework on html/template ☆`92`
*   [napsy/go-css (⭐94)](https://github.com/napsy/go-css) — A very simple CSS parser, written in Go ☆`94`
*   [abemedia/go-don (⭐60)](https://github.com/abemedia/go-don) — API framework written in Golang. ☆`60`
*   [JiveGroup/gFly (⭐49)](https://github.com/JiveGroup/gFly) — Laravel inspired web framework written in Go ☆`49`
*   [clubpay/ronykit (⭐37)](https://github.com/clubpay/ronykit) — API Framework supporting REST and RPC. ☆`37`
*   [SaiNageswarS/go-api-boot (⭐35)](https://github.com/SaiNageswarS/go-api-boot) — gRPC + HTTP/2 production framework ☆`35`

### WebAssembly

*   [tinygo-org/tinygo (⭐18k)](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,591`
*   [agnivade/wasmbrowsertest (⭐211)](https://github.com/agnivade/wasmbrowsertest) — Run WASM tests inside your browser ☆`211`
*   [extism/go-sdk (⭐180)](https://github.com/extism/go-sdk) — Extism Go SDK - easily run WebAssembly modules in your Go applications ☆`182`

## Workflow & Scheduling

### Job Scheduler

*   [hatchet-dev/hatchet (⭐7.5k)](https://github.com/hatchet-dev/hatchet) — An orchestration engine for background tasks, AI agents, and durable workflows ☆`7,556`
*   [go-co-op/gocron (⭐7.1k)](https://github.com/go-co-op/gocron) — Easy and fluent Go cron scheduling ☆`7,109`
*   [reugn/go-quartz (⭐2k)](https://github.com/reugn/go-quartz) — Minimalist and zero-dependency scheduling library for Go ☆`2,013`
*   [adhocore/gronx (⭐511)](https://github.com/adhocore/gronx) — Lightweight cron expression parser ☆`512`
*   [fieldryand/goflow (⭐481)](https://github.com/fieldryand/goflow) — Simple but powerful DAG scheduler and dashboard ☆`481`
*   [madflojo/tasks (⭐330)](https://github.com/madflojo/tasks) — In-process task scheduler ☆`332`
*   [bart6114/cheek (⭐200)](https://github.com/bart6114/cheek) — cheek: a pico-sized declarative job scheduler ☆`199`
*   [onatm/clockwerk (⭐182)](https://github.com/onatm/clockwerk) — Job Scheduling Library ☆`183`
*   [deepaksinghvi/cdule (⭐61)](https://github.com/deepaksinghvi/cdule) — Golang job scheduler ☆`61`
*   [pardnchiu/go-scheduler (⭐35)](https://github.com/pardnchiu/go-scheduler) — (module) A Go scheduling library with task dependencies, timeout control, and cron expressions ☆`36`
*   [romshark/sched (⭐31)](https://github.com/romshark/sched) — A job scheduler for Go with the ability to fast-forward time. ☆`31`

### Workflow Frameworks

*   [redpanda-data/connect (⭐8.7k)](https://github.com/redpanda-data/connect) — Fancy stream processing made operationally mundane ☆`8,711`
*   [dagucloud/dagu (⭐3.7k)](https://github.com/dagucloud/dagu) — Workflow engine with Web UI ☆`3,660`
*   [jf-tech/omniparser (⭐1.1k)](https://github.com/jf-tech/omniparser) — ETL streaming parser for Go ☆`1,085`
*   [noneback/go-taskflow (⭐635)](https://github.com/noneback/go-taskflow) — Task-parallel programming library ☆`636`
*   [cadence-workflow/cadence-go-client (⭐378)](https://github.com/cadence-workflow/cadence-go-client) — Cadence workflow client for Go ☆`378`
*   [luno/workflow (⭐249)](https://github.com/luno/workflow) — Type-safe workflow orchestration ☆`250`
*   [rhosocial/go-dag (⭐41)](https://github.com/rhosocial/go-dag) — DAG-based workflow framework ☆`41`

***

## 🏆 Top 100 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1.  [ollama/ollama (⭐176k)](https://github.com/ollama/ollama) — Run LLMs locally ☆`176,669`
2.  [kubernetes/kubernetes (⭐124k)](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`123,883`
3.  [gin-gonic/gin (⭐89k)](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`88,939`
4.  [junegunn/fzf (⭐82k)](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`81,915`
5.  [caddyserver/caddy (⭐74k)](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`74,276`
6.  [moby/moby (⭐72k)](https://github.com/moby/moby) — Container ecosystem components ☆`71,890`
7.  [prometheus/prometheus (⭐65k)](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`65,264`
8.  [traefik/traefik (⭐64k)](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`64,078`
9.  [pocketbase/pocketbase (⭐60k)](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`60,149`
10. [go-gitea/gitea (⭐57k)](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`56,971`
11. [golang-standards/project-layout (⭐56k)](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`56,344`
12. [wagoodman/dive (⭐54k)](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`54,348`
13. [etcd-io/etcd (⭐52k)](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`52,018`
14. [ethereum/go-ethereum (⭐51k)](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`51,194`
15. [mudler/LocalAI (⭐47k)](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`47,737`
16. [milvus-io/milvus (⭐45k)](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`45,335`
17. [spf13/cobra (⭐44k)](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`44,305`
18. [charmbracelet/bubbletea (⭐44k)](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`43,880`
19. [pingcap/tidb (⭐40k)](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`40,326`
20. [gofiber/fiber (⭐40k)](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`40,002`
21. [go-gorm/gorm (⭐40k)](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,880`
22. [schollz/croc (⭐36k)](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`37,700`
23. [harness/harness (⭐37k)](https://github.com/harness/harness) — End-to-end developer platform ☆`37,451`
24. [restic/restic (⭐35k)](https://github.com/restic/restic) — Fast, secure backup program ☆`35,119`
25. [seaweedfs/seaweedfs (⭐33k)](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`33,652`
26. [k3s-io/k3s (⭐33k)](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`33,542`
27. [zeromicro/go-zero (⭐33k)](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`33,210`
28. [labstack/echo (⭐33k)](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,546`
29. [beego/beego (⭐32k)](https://github.com/beego/beego) — High-performance web framework ☆`32,409`
30. [cockroachdb/cockroach (⭐32k)](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`32,310`
31. [kubernetes/minikube (⭐32k)](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,978`
32. [influxdata/influxdb (⭐32k)](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,648`
33. [grafana/k6 (⭐31k)](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`31,093`
34. [spf13/viper (⭐30k)](https://github.com/spf13/viper) — Go configuration with fangs ☆`30,374`
35. [fyne-io/fyne (⭐28k)](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`28,515`
36. [stretchr/testify (⭐26k)](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`26,095`
37. [go-kratos/kratos (⭐26k)](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,802`
38. [sirupsen/logrus (⭐26k)](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,749`
39. [gocolly/colly (⭐25k)](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,383`
40. [tsenart/vegeta (⭐25k)](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`25,124`
41. [uber-go/zap (⭐25k)](https://github.com/uber-go/zap) — Fast structured logging ☆`24,580`
42. [urfave/cli (⭐24k)](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`24,174`
43. [dolthub/dolt (⭐24k)](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`23,932`
44. [air-verse/air (⭐24k)](https://github.com/air-verse/air) — Live reload for Go apps ☆`23,799`
45. [valyala/fasthttp (⭐23k)](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,416`
46. [jaegertracing/jaeger (⭐23k)](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`23,026`
47. [grpc/grpc-go (⭐23k)](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`23,011`
48. [FiloSottile/age (⭐23k)](https://github.com/FiloSottile/age) — Simple encryption tool ☆`22,971`
49. [micro/go-micro (⭐23k)](https://github.com/micro/go-micro) — A Go agent harness and service framework ☆`22,965`
50. [go-chi/chi (⭐23k)](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`22,568`
51. [redis/go-redis (⭐22k)](https://github.com/redis/go-redis) — Redis Go client ☆`22,196`
52. [gorilla/mux (⭐22k)](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,832`
53. [dgraph-io/dgraph (⭐22k)](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,745`
54. [samber/lo (⭐21k)](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`21,391`
55. [vitessio/vitess (⭐21k)](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`21,158`
56. [gofr-dev/gofr (⭐21k)](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`21,117`
57. [qax-os/excelize (⭐21k)](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,795`
58. [antonmedv/fx (⭐21k)](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,544`
59. [nats-io/nats-server (⭐20k)](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`20,294`
60. [apache/casbin (⭐20k)](https://github.com/apache/casbin) — Authorization library for Go ☆`20,277`
61. [go-playground/validator (⭐20k)](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`20,088`
62. [golangci/golangci-lint (⭐19k)](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`19,202`
63. [golang-migrate/migrate (⭐19k)](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,739`
64. [keploy/keploy (⭐18k)](https://github.com/keploy/keploy) — API testing with auto mocks ☆`18,337`
65. [sqlc-dev/sqlc (⭐18k)](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`18,054`
66. [jmoiron/sqlx (⭐18k)](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,701`
67. [rqlite/rqlite (⭐18k)](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,642`
68. [tinygo-org/tinygo (⭐18k)](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,591`
69. [VictoriaMetrics/VictoriaMetrics (⭐17k)](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`17,379`
70. [ent/ent (⭐17k)](https://github.com/ent/ent) — An entity framework for Go ☆`17,143`
71. [ipfs/kubo (⭐17k)](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`17,082`
72. [pion/webrtc (⭐17k)](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,657`
73. [fatih/vim-go (⭐16k)](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,223`
74. [goreleaser/goreleaser (⭐16k)](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,952`
75. [go-task/task (⭐16k)](https://github.com/go-task/task) — Fast cross-platform build tool inspired by Make ☆`15,868`
76. [hashicorp/packer (⭐16k)](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,736`
77. [dgraph-io/badger (⭐16k)](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,727`
78. [tidwall/gjson (⭐16k)](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,545`
79. [kubernetes-sigs/kind (⭐15k)](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,367`
80. [go-sql-driver/mysql (⭐15k)](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,277`
81. [PuerkitoBio/goquery (⭐15k)](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,975`
82. [cloudflare/cloudflared (⭐15k)](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`14,931`
83. [panjf2000/ants (⭐14k)](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,468`
84. [bytebase/bytebase (⭐14k)](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`14,282`
85. [juicedata/juicefs (⭐14k)](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`14,221`
86. [webview/webview (⭐14k)](https://github.com/webview/webview) — Tiny webview library for Go ☆`14,165`
87. [jackc/pgx (⭐14k)](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`14,057`
88. [gizak/termui (⭐14k)](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,577`
89. [hibiken/asynq (⭐14k)](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`13,540`
90. [hajimehoshi/ebiten (⭐13k)](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`13,357`
91. [golang/groupcache (⭐13k)](https://github.com/golang/groupcache) — Distributed cache library ☆`13,340`
92. [gogf/gf (⭐13k)](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,228`
93. [chromedp/chromedp (⭐13k)](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`13,200`
94. [gopherjs/gopherjs (⭐13k)](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,169`
95. [IBM/sarama (⭐13k)](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,501`
96. [rs/zerolog (⭐12k)](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,479`
97. [drakkan/sftpgo (⭐12k)](https://github.com/drakkan/sftpgo) — Full-featured SFTP/FTP/HTTP server ☆`12,300`
98. [Shopify/toxiproxy (⭐12k)](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`12,183`
99. [kubeshark/kubeshark (⭐12k)](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`12,009`
100.    [adnanh/webhook (⭐12k)](https://github.com/adnanh/webhook) — Lightweight webhook server ☆`11,991`

## Gophers

*   [MariaLetta/free-gophers-pack (⭐4k)](https://github.com/MariaLetta/free-gophers-pack) — This pack of 100+ gopher pictures and elements
*   [keygx/Go-gopher-Vector (⭐75)](https://github.com/keygx/Go-gopher-Vector) — Go gopher Vector Data (.ai, .svg)
*   [ashleymcnamara/gophers (⭐3.1k)](https://github.com/ashleymcnamara/gophers) — Gopher Artwork by Ashley McNamara
*   [sillecelik/go-gopher (⭐163)](https://github.com/sillecelik/go-gopher) — The Go Gopher Amigurumi Pattern
*   [GolangUA/gopher-logos (⭐140)](https://github.com/GolangUA/gopher-logos) — adorable gopher logos
*   [egonelbre/gophers (⭐3.8k)](https://github.com/egonelbre/gophers) — gophers artwork
*   [scraly/gophers (⭐37)](https://github.com/scraly/gophers) — Gopher artwork (Golang mascot)

## Contributing

Please see [CONTRIBUTING](https://github.com/abordage/awesome-go/blob/main/README.md/.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request — contributions are welcome!

## Credits

*   [avelino/awesome-go (⭐178k)](https://github.com/avelino/awesome-go)
*   [All Contributors (⭐4)](https://github.com/abordage/awesome-go/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](https://github.com/abordage/awesome-go/blob/main/README.md/LICENSE) for more information.

