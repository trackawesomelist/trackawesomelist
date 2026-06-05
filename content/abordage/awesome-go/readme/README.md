# Awesome Go Overview

Structured collection of Go frameworks, libraries, tools, and resources. Automatically maintained and up-to-date with metadata, filtering, and comprehensive categorization.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/abordage/awesome-go/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 abordage/awesome-go](https://github.com/abordage/awesome-go) · ⭐ 4 · 🏷️ Programming Languages

[ [Daily](/content/abordage/awesome-go/README.md) / [Weekly](/content/abordage/awesome-go/week/README.md) / Overview ]

---

# Awesome Go

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-go?label=last%20update)](https://github.com/abordage/awesome-go/blob/main/README.md/README.md)
![Repositories](https://img.shields.io/badge/repositories-1,171-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-5,007,208-gold)
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

*   [sashabaranov/go-openai (⭐11k)](https://github.com/sashabaranov/go-openai) — OpenAI API client for Go ☆`10,686`
*   [wit-ai/wit-go (⭐170)](https://github.com/wit-ai/wit-go) — Go client for wit.ai HTTP API ☆`170`

### Artificial Intelligence

*   [ollama/ollama (⭐172k)](https://github.com/ollama/ollama) — Run LLMs locally ☆`173,218`
*   [mudler/LocalAI (⭐46k)](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`46,678`
*   [tmc/langchaingo (⭐9.3k)](https://github.com/tmc/langchaingo) — LangChain for Go, the easiest way to write LLM-based programs in Go ☆`9,370`
*   [maximhq/bifrost (⭐5.2k)](https://github.com/maximhq/bifrost) — Fastest LLM gateway for Go ☆`5,495`
*   [philippgille/chromem-go (⭐959)](https://github.com/philippgille/chromem-go) — Embeddable vector database for Go ☆`965`
*   [universal-tool-calling-protocol/go-utcp (⭐106)](https://github.com/universal-tool-calling-protocol/go-utcp) — Official Go implementation of the UTCP ☆`108`
*   [presbrey/ollamafarm (⭐98)](https://github.com/presbrey/ollamafarm) — Manage multiple Ollama instances ☆`98`

### Machine Learning

*   [gorgonia/gorgonia (⭐5.9k)](https://github.com/gorgonia/gorgonia) — Machine learning library for Go ☆`5,915`
*   [otiai10/gosseract (⭐3.1k)](https://github.com/otiai10/gosseract) — OCR using Tesseract in Go ☆`3,111`
*   [gomlx/gomlx (⭐1.4k)](https://github.com/gomlx/gomlx) — GoMLX: An Accelerated Machine Learning Framework For Go ☆`1,442`
*   [jbrukh/bayesian (⭐813)](https://github.com/jbrukh/bayesian) — Naive Bayesian Classification for Golang. ☆`813`
*   [knights-analytics/hugot (⭐606)](https://github.com/knights-analytics/hugot) — Onnx transformer pipelines in Golang ☆`608`
*   [patrikeh/go-deep (⭐556)](https://github.com/patrikeh/go-deep) — Artificial Neural Network ☆`557`
*   [c-bata/goptuna (⭐277)](https://github.com/c-bata/goptuna) — A hyperparameter optimization framework, inspired by Optuna. ☆`277`

## Audio & Video

### Audio

*   [ebitengine/oto (⭐1.9k)](https://github.com/ebitengine/oto) — A low-level library to play sound on multiple platforms ☆`1,924`
*   [gordonklaus/portaudio (⭐836)](https://github.com/gordonklaus/portaudio) — Go bindings for the PortAudio audio I/O library ☆`836`
*   [gen2brain/malgo (⭐409)](https://github.com/gen2brain/malgo) — Mini audio library ☆`411`
*   [mewkiz/flac (⭐357)](https://github.com/mewkiz/flac) — Package flac provides access to FLAC (Free Lossless Audio Codec) streams. ☆`357`
*   [tosone/minimp3 (⭐132)](https://github.com/tosone/minimp3) — Decode mp3 ☆`132`

### Images

*   [hybridgroup/gocv (⭐7.5k)](https://github.com/hybridgroup/gocv) — Computer vision with OpenCV 4 ☆`7,453`
*   [anthonynsimon/bild (⭐4.2k)](https://github.com/anthonynsimon/bild) — Image processing algorithms in pure Go ☆`4,190`
*   [cshum/imagor (⭐3.9k)](https://github.com/cshum/imagor) — Fast, secure image processing server and Go library, using libvips ☆`3,960`
*   [thoas/picfit (⭐2.3k)](https://github.com/thoas/picfit) — An image resizing server written in Go ☆`2,335`
*   [gographics/imagick (⭐1.9k)](https://github.com/gographics/imagick) — Go binding to ImageMagick's MagickWand C API ☆`1,869`
*   [tdewolff/canvas (⭐1.8k)](https://github.com/tdewolff/canvas) — Vector graphics in Go ☆`1,814`
*   [davidbyttow/govips (⭐1.6k)](https://github.com/davidbyttow/govips) — A lightning fast image processing and resizing library for Go ☆`1,614`
*   [yeqown/go-qrcode (⭐847)](https://github.com/yeqown/go-qrcode) — Customizable QR code generator ☆`851`
*   [HugoSmits86/nativewebp (⭐439)](https://github.com/HugoSmits86/nativewebp) — Native webp encoder for Go ☆`439`
*   [auyer/steganography (⭐354)](https://github.com/auyer/steganography) — LSB steganography in pure Go ☆`354`
*   [kolesa-team/go-webp (⭐310)](https://github.com/kolesa-team/go-webp) — Simple and fast webp library for golang ☆`311`
*   [qmuntal/gltf (⭐282)](https://github.com/qmuntal/gltf) — Go library for encoding glTF 2.0 files ☆`282`
*   [Pixboost/transformimgs (⭐290)](https://github.com/Pixboost/transformimgs) — Open source image CDN. ☆`290`
*   [gojek/darkroom (⭐235)](https://github.com/gojek/darkroom) — Image processing engine and proxy service ☆`235`
*   [ungerik/go-cairo (⭐152)](https://github.com/ungerik/go-cairo) — Go binding for the cairo graphics library ☆`152`
*   [aofei/cameron (⭐131)](https://github.com/aofei/cameron) — An avatar generator for Go. ☆`131`
*   [piglig/go-qr (⭐50)](https://github.com/piglig/go-qr) — A native, high-quality and minimalistic QR code generator and decoder ☆`51`

### Video

*   [asticode/go-astiav (⭐717)](https://github.com/asticode/go-astiav) — Golang ffmpeg and libav C bindings ☆`719`
*   [asticode/go-astisub (⭐696)](https://github.com/asticode/go-astisub) — Manipulate subtitles in Go ☆`697`
*   [Eyevinn/mp4ff (⭐636)](https://github.com/Eyevinn/mp4ff) — MP4/ISOBMFF tools and library ☆`636`
*   [asticode/go-astits (⭐615)](https://github.com/asticode/go-astits) — Demux and mux MPEG Transport Streams (.ts) natively in GO ☆`616`
*   [adrg/libvlc-go (⭐509)](https://github.com/adrg/libvlc-go) — Go bindings for libVLC ☆`509`
*   [Eyevinn/hls-m3u8 (⭐61)](https://github.com/Eyevinn/hls-m3u8) — HLS m3u8 library in Go ☆`62`
*   [jonoton/scout (⭐28)](https://github.com/jonoton/scout) — Video surveillance with motion detection ☆`28`
*   [unki2aut/go-mpd (⭐32)](https://github.com/unki2aut/go-mpd) — MPEG-DASH manifest library ☆`32`

## Auth

### Authentication

*   [golang-jwt/jwt (⭐9.1k)](https://github.com/golang-jwt/jwt) — Go implementation of JSON Web Tokens (JWT). ☆`9,108`
*   [markbates/goth (⭐6.5k)](https://github.com/markbates/goth) — Multi-provider authentication ☆`6,548`
*   [golang/oauth2 (⭐5.9k)](https://github.com/golang/oauth2) — Go OAuth2 ☆`5,866`
*   [aarondl/authboss (⭐4.2k)](https://github.com/aarondl/authboss) — The boss of http auth. ☆`4,184`
*   [alexedwards/scs (⭐2.6k)](https://github.com/alexedwards/scs) — HTTP Session Management for Go ☆`2,572`
*   [lestrrat-go/jwx (⭐2.4k)](https://github.com/lestrrat-go/jwx) — Complete JWx implementation ☆`2,385`
*   [openshift/osin (⭐1.9k)](https://github.com/openshift/osin) — Golang OAuth2 server library ☆`1,933`
*   [dghubble/gologin (⭐2k)](https://github.com/dghubble/gologin) — Go login handlers for authentication providers (OAuth1, OAuth2) ☆`1,956`
*   [zitadel/oidc (⭐1.8k)](https://github.com/zitadel/oidc) — OpenID Connect client and server ☆`1,826`
*   [cristalhq/jwt (⭐686)](https://github.com/cristalhq/jwt) — Safe, simple and fast JSON Web Tokens for Go ☆`686`
*   [shaj13/go-guardian (⭐610)](https://github.com/shaj13/go-guardian) — Authentication library for Go ☆`610`
*   [go-jose/go-jose (⭐505)](https://github.com/go-jose/go-jose) — An implementation of JOSE standards (JWE, JWS, JWT) in Go ☆`509`
*   [abraithwaite/jeff (⭐272)](https://github.com/abraithwaite/jeff) — Jeff provides the simplest way to manage web sessions in Go. ☆`272`
*   [Kwynto/gosession (⭐258)](https://github.com/Kwynto/gosession) — Quick session for net/http ☆`258`
*   [leodip/goiabada (⭐189)](https://github.com/leodip/goiabada) — Goiabada is an OAuth2 / OpenID Connect server written in Go. ☆`189`
*   [jellydator/sessionup (⭐131)](https://github.com/jellydator/sessionup) — Straightforward HTTP session management ☆`131`
*   [brianvoe/sjwt (⭐122)](https://github.com/brianvoe/sjwt) — Simple JWT Golang ☆`122`
*   [essentialkaos/branca (⭐98)](https://github.com/essentialkaos/branca) — Encrypted API tokens ☆`98`
*   [icza/session (⭐118)](https://github.com/icza/session) — Session management for web servers ☆`118`
*   [mengzhuo/cookiestxt (⭐23)](https://github.com/mengzhuo/cookiestxt) — cookiestxt implement parser of cookies txt format ☆`23`

### Authorization

*   [apache/casbin (⭐20k)](https://github.com/apache/casbin) — Authorization library for Go ☆`20,170`
*   [ory/keto (⭐5.3k)](https://github.com/ory/keto) — Customizable permission server ☆`5,350`
*   [openfga/openfga (⭐5.2k)](https://github.com/openfga/openfga) — Fine-grained authorization server ☆`5,237`
*   [cerbos/cerbos (⭐4.4k)](https://github.com/cerbos/cerbos) — Open core authorization layer ☆`4,442`

## Bots & Chat

### Bot Frameworks

*   [tucnak/telebot (⭐4.6k)](https://github.com/tucnak/telebot) — Telebot is a Telegram bot framework in Go. ☆`4,618`
*   [go-telegram/bot (⭐1.7k)](https://github.com/go-telegram/bot) — Telegram Bot API Go framework ☆`1,733`
*   [mymmrac/telego (⭐1k)](https://github.com/mymmrac/telego) — Telegram Bot API library for Go ☆`1,033`
*   [diamondburned/arikawa (⭐591)](https://github.com/diamondburned/arikawa) — A Golang library and framework for the Discord API. ☆`591`
*   [NicoNex/echotron (⭐438)](https://github.com/NicoNex/echotron) — An elegant and concurrent library for the Telegram bot API in Go. ☆`439`
*   [gempir/go-twitch-irc (⭐397)](https://github.com/gempir/go-twitch-irc) — go irc client for twitch.tv ☆`397`
*   [innogames/slack-bot (⭐208)](https://github.com/innogames/slack-bot) — Slack bot for Jenkins, Jira, PRs ☆`208`
*   [mr-linch/go-tg (⭐131)](https://github.com/mr-linch/go-tg) — Telegram Bot API client ☆`135`
*   [slack-io/slacker (⭐60)](https://github.com/slack-io/slacker) — Slack Bot Framework ☆`60`
*   [onrik/micha (⭐33)](https://github.com/onrik/micha) — Client lib for Telegram bot api ☆`33`

### Chat APIs

*   [bwmarrin/discordgo (⭐5.9k)](https://github.com/bwmarrin/discordgo) — (Golang) Go bindings for Discord ☆`5,925`
*   [slack-go/slack (⭐4.9k)](https://github.com/slack-go/slack) — Slack API in Go ☆`4,944`
*   [huandu/facebook (⭐1.5k)](https://github.com/huandu/facebook) — A Facebook Graph API SDK For Go. ☆`1,467`
*   [chyroc/lark (⭐471)](https://github.com/chyroc/lark) — Lark/Feishu Open API SDK ☆`472`
*   [go-lark/lark (⭐244)](https://github.com/go-lark/lark) — Feishu/Lark SDK for Go ☆`244`
*   [switchupcb/disgo (⭐114)](https://github.com/switchupcb/disgo) — Next-gen Discord API library ☆`114`

## CLI & Terminal

### Advanced Console UIs

*   [charmbracelet/bubbletea (⭐43k)](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`42,888`
*   [antonmedv/fx](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,617`
*   [gizak/termui (⭐14k)](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,568`
*   [charmbracelet/lipgloss (⭐11k)](https://github.com/charmbracelet/lipgloss) — Style definitions for nice terminal layouts ☆`11,374`
*   [jroimartin/gocui (⭐11k)](https://github.com/jroimartin/gocui) — Minimalist Go package aimed at creating Console User Interfaces. ☆`10,566`
*   [charmbracelet/bubbles (⭐8.4k)](https://github.com/charmbracelet/bubbles) — TUI components for Bubble Tea ☆`8,497`
*   [c-bata/go-prompt (⭐5.5k)](https://github.com/c-bata/go-prompt) — Interactive prompts for Go ☆`5,480`
*   [pterm/pterm (⭐5.5k)](https://github.com/pterm/pterm) — Modern terminal output library ☆`5,463`
*   [schollz/progressbar (⭐4.7k)](https://github.com/schollz/progressbar) — Thread-safe progress bar ☆`4,678`
*   [guptarohit/asciigraph (⭐3k)](https://github.com/guptarohit/asciigraph) — ASCII line graphs in terminal ☆`3,036`
*   [mum4k/termdash (⭐3k)](https://github.com/mum4k/termdash) — Terminal-based dashboard ☆`3,007`
*   [briandowns/spinner (⭐2.5k)](https://github.com/briandowns/spinner) — Terminal spinner indicators ☆`2,524`
*   [vbauerster/mpb (⭐2.5k)](https://github.com/vbauerster/mpb) — Multi progress bar ☆`2,496`
*   [muesli/termenv (⭐2k)](https://github.com/muesli/termenv) — Terminal color support ☆`2,004`
*   [gookit/color (⭐1.6k)](https://github.com/gookit/color) — Terminal color rendering ☆`1,602`
*   [logrusorgru/aurora (⭐1.5k)](https://github.com/logrusorgru/aurora) — ANSI colors for Printf ☆`1,489`
*   [mattn/go-isatty (⭐909)](https://github.com/mattn/go-isatty) — Check if terminal is TTY ☆`909`
*   [mattn/go-colorable (⭐808)](https://github.com/mattn/go-colorable) — Colorable writer for Windows ☆`808`
*   [box-cli-maker/box-cli-maker (⭐636)](https://github.com/box-cli-maker/box-cli-maker) — Render highly customizable boxes in the terminal ☆`637`
*   [Evertras/bubble-table (⭐570)](https://github.com/Evertras/bubble-table) — Table component for Bubble Tea ☆`573`
*   [DMcP89/tinycare-tui (⭐19)](https://github.com/DMcP89/tinycare-tui) — TUI application written in GO inspired by tiny-care-terminal ☆`20`

### Standard CLI

*   [spf13/cobra (⭐44k)](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`44,056`
*   [urfave/cli (⭐24k)](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`24,107`
*   [elves/elvish (⭐6.3k)](https://github.com/elves/elvish) — Scripting shell for Go ☆`6,321`
*   [alecthomas/kingpin (⭐3.6k)](https://github.com/alecthomas/kingpin) — Command-line parser ☆`3,564`
*   [dnote/dnote (⭐3k)](https://github.com/dnote/dnote) — Command-line notebook ☆`3,040`
*   [spf13/pflag (⭐2.7k)](https://github.com/spf13/pflag) — POSIX/GNU-style flags ☆`2,741`
*   [jessevdk/go-flags (⭐2.7k)](https://github.com/jessevdk/go-flags) — Command-line option parser ☆`2,699`
*   [alexflint/go-arg (⭐2.3k)](https://github.com/alexflint/go-arg) — Struct-based argument parsing ☆`2,261`
*   [carapace-sh/carapace-bin (⭐1.8k)](https://github.com/carapace-sh/carapace-bin) — Multi-shell completion binary ☆`1,848`
*   [nanovms/ops (⭐1.5k)](https://github.com/nanovms/ops) — Build and run unikernels ☆`1,500`
*   [carapace-sh/carapace (⭐1.3k)](https://github.com/carapace-sh/carapace) — Multi-shell completion library ☆`1,336`
*   [posener/complete (⭐955)](https://github.com/posener/complete) — Bash completion in Go ☆`955`
*   [ddddddO/gtree (⭐331)](https://github.com/ddddddO/gtree) — Generate ASCII tree from Markdown ☆`331`
*   [leaanthony/clir (⭐202)](https://github.com/leaanthony/clir) — Simple CLI library ☆`202`
*   [urfave/sflags (⭐165)](https://github.com/urfave/sflags) — Generate flags from structs ☆`165`
*   [reeflective/readline (⭐140)](https://github.com/reeflective/readline) — Shell library with inputrc ☆`142`
*   [hedzr/cmdr (⭐141)](https://github.com/hedzr/cmdr) — POSIX-compliant CLI parser ☆`140`
*   [reeflective/console (⭐108)](https://github.com/reeflective/console) — Console library for Cobra ☆`108`
*   [codingconcepts/env (⭐126)](https://github.com/codingconcepts/env) — Tag-based environment configuration for structs ☆`125`
*   [dixonwille/wlog (⭐67)](https://github.com/dixonwille/wlog) — Cross-platform logging ☆`67`
*   [hashicorp/cli (⭐39)](https://github.com/hashicorp/cli) — CLI library for Go ☆`39`
*   [DavidGamba/go-getoptions (⭐60)](https://github.com/DavidGamba/go-getoptions) — Command line option parser with completion ☆`60`
*   [nyaosorg/go-readline-ny (⭐34)](https://github.com/nyaosorg/go-readline-ny) — Readline for Go ☆`35`
*   [carapace-sh/carapace-spec (⭐32)](https://github.com/carapace-sh/carapace-spec) — Multi-shell completion library ☆`32`
*   [jxskiss/mcli (⭐46)](https://github.com/jxskiss/mcli) — Minimal but powerful CLI ☆`46`
*   [sgreben/flagvar (⭐48)](https://github.com/sgreben/flagvar) — CLI argument types for flag ☆`48`

## Concurrency

### Actor Model

*   [asynkron/protoactor-go (⭐5.5k)](https://github.com/asynkron/protoactor-go) — Ultra fast distributed actors for Go ☆`5,464`
*   [ergo-services/ergo (⭐4.6k)](https://github.com/ergo-services/ergo) — Actor framework with network transparency ☆`4,577`
*   [anthdm/hollywood (⭐2.2k)](https://github.com/anthdm/hollywood) — Blazingly fast and light-weight Actor engine written in Golang ☆`2,237`
*   [Tochemey/goakt (⭐352)](https://github.com/Tochemey/goakt) — Distributed actor framework ☆`354`

### Goroutines

*   [panjf2000/ants (⭐14k)](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,426`
*   [benmanns/goworker (⭐2.9k)](https://github.com/benmanns/goworker) — Resque-compatible background worker ☆`2,848`
*   [alitto/pond (⭐2.2k)](https://github.com/alitto/pond) — High-performance worker pool ☆`2,151`
*   [destel/rill (⭐1.8k)](https://github.com/destel/rill) — Channel-based concurrency toolkit ☆`1,812`
*   [xxjwxc/gowp (⭐518)](https://github.com/xxjwxc/gowp) — Goroutine worker pool ☆`517`
*   [earthboundkid/flowmatic (⭐402)](https://github.com/earthboundkid/flowmatic) — Structured concurrency ☆`402`
*   [vladopajic/go-actor (⭐294)](https://github.com/vladopajic/go-actor) — Actor model library ☆`296`
*   [timandy/routine (⭐290)](https://github.com/timandy/routine) — ThreadLocal for Go ☆`290`
*   [reugn/async (⭐306)](https://github.com/reugn/async) — Async computation package ☆`306`
*   [mborders/artifex (⭐213)](https://github.com/mborders/artifex) — In-memory job queue ☆`213`

### Stream Processing

*   [reugn/go-streams (⭐2.2k)](https://github.com/reugn/go-streams) — Stream processing library ☆`2,171`
*   [Breeze0806/go-etl (⭐189)](https://github.com/Breeze0806/go-etl) — ETL toolset for Go ☆`190`
*   [fulminate-io/machine (⭐168)](https://github.com/fulminate-io/machine) — Machine is a workflow/pipeline library for processing data ☆`168`
*   [mariomac/gostream (⭐172)](https://github.com/mariomac/gostream) — Java Streams port for Go ☆`171`
*   [rulego/streamsql (⭐58)](https://github.com/rulego/streamsql) — SQL-based stream processing for IoT ☆`58`

## Configuration

*   [spf13/viper (⭐30k)](https://github.com/spf13/viper) — Go configuration with fangs ☆`30,282`
*   [caarlos0/env (⭐6.2k)](https://github.com/caarlos0/env) — Parse environment variables to structs ☆`6,204`
*   [knadh/koanf (⭐4k)](https://github.com/knadh/koanf) — Lightweight config management ☆`4,059`
*   [alecthomas/kong (⭐3.1k)](https://github.com/alecthomas/kong) — Command-line parser for Go ☆`3,091`
*   [ilyakaznacheev/cleanenv (⭐2.1k)](https://github.com/ilyakaznacheev/cleanenv) — Minimalistic environment config reader ☆`2,123`
*   [adrg/xdg (⭐995)](https://github.com/adrg/xdg) — XDG Base Directory implementation ☆`997`
*   [cristalhq/aconfig (⭐633)](https://github.com/cristalhq/aconfig) — Simple config loader ☆`634`
*   [gookit/config (⭐583)](https://github.com/gookit/config) — Config management with formats ☆`583`
*   [nil-go/konf (⭐382)](https://github.com/nil-go/konf) — Simplest config loader for Go ☆`384`
*   [kkyr/fig (⭐383)](https://github.com/kkyr/fig) — Minimalist config library ☆`383`
*   [hjson/hjson-go (⭐353)](https://github.com/hjson/hjson-go) — Hjson for Go ☆`353`
*   [vrischmann/envconfig (⭐250)](https://github.com/vrischmann/envconfig) — Env config library ☆`250`
*   [chaindead/zerocfg (⭐200)](https://github.com/chaindead/zerocfg) — Zero-effort config management ☆`200`
*   [beatlabs/harvester (⭐134)](https://github.com/beatlabs/harvester) — Watch and notify config changes ☆`134`
*   [BoRuDar/configuration (⭐108)](https://github.com/BoRuDar/configuration) — Set struct fields from env, flags, files ☆`108`
*   [omeid/uconfig (⭐74)](https://github.com/omeid/uconfig) — Lightweight config management ☆`74`
*   [gurkankaymak/hocon (⭐91)](https://github.com/gurkankaymak/hocon) — HOCON config library for Go ☆`92`
*   [PaddleHQ/go-aws-ssm (⭐64)](https://github.com/PaddleHQ/go-aws-ssm) — AWS System Manager interface ☆`65`
*   [go-simpler/env (⭐80)](https://github.com/go-simpler/env) — Load env vars to struct ☆`80`
*   [greencoda/confiq (⭐40)](https://github.com/greencoda/confiq) — Config struct decoder ☆`40`
*   [num30/config (⭐61)](https://github.com/num30/config) — Declarative configuration ☆`61`
*   [wkhere/bcl (⭐32)](https://github.com/wkhere/bcl) — Basic Configuration Language ☆`31`
*   [sakirsensoy/genv (⭐44)](https://github.com/sakirsensoy/genv) — Easy env variable handling ☆`44`
*   [dsbasko/go-cfg (⭐50)](https://github.com/dsbasko/go-cfg) — Unified config reading ☆`50`
*   [nasermirzaei89/env (⭐22)](https://github.com/nasermirzaei89/env) — Zero-dep env package ☆`22`
*   [atelpis/enflag (⭐38)](https://github.com/atelpis/enflag) — Unify env and flag parsing ☆`38`
*   [romshark/yamagiconf (⭐19)](https://github.com/romshark/yamagiconf) — YAML config framework ☆`19`

## Data Formats

### JSON

*   [tidwall/gjson (⭐16k)](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,511`
*   [bytedance/sonic (⭐9.5k)](https://github.com/bytedance/sonic) — A blazingly fast JSON serializing & deserializing library ☆`9,481`
*   [Jeffail/gabs (⭐3.5k)](https://github.com/Jeffail/gabs) — Dynamic JSON parsing ☆`3,530`
*   [valyala/fastjson (⭐2.5k)](https://github.com/valyala/fastjson) — Fast JSON parser for Go ☆`2,452`
*   [ohler55/ojg (⭐944)](https://github.com/ohler55/ojg) — Optimized JSON for Go ☆`946`
*   [wI2L/jsondiff (⭐626)](https://github.com/wI2L/jsondiff) — JSON Patch diff computation ☆`627`
*   [spyzhov/ajson (⭐290)](https://github.com/spyzhov/ajson) — Abstract JSON with JSONPath ☆`289`
*   [Andrew-M-C/go.jsonvalue (⭐202)](https://github.com/Andrew-M-C/go.jsonvalue) — Unstructured JSON solution ☆`202`
*   [iOliverNguyen/ujson (⭐85)](https://github.com/iOliverNguyen/ujson) — Minimal JSON parser ☆`85`
*   [neilotoole/jsoncolor (⭐52)](https://github.com/neilotoole/jsoncolor) — Colorized JSON output ☆`53`

### Serialization

*   [golang/protobuf (⭐10k)](https://github.com/golang/protobuf) — Protocol buffers for Go ☆`10,075`
*   [ugorji/go (⭐1.9k)](https://github.com/ugorji/go) — Codec for msgpack, cbor, json ☆`1,952`
*   [linkedin/goavro (⭐1.1k)](https://github.com/linkedin/goavro) — Goavro is a library that encodes and decodes Avro data. ☆`1,063`
*   [fxamacker/cbor (⭐1k)](https://github.com/fxamacker/cbor) — CBOR codec with extensions ☆`1,050`
*   [jszwec/csvutil (⭐1k)](https://github.com/jszwec/csvutil) — CSV to struct mapping ☆`1,035`
*   [ghostiam/binstruct (⭐114)](https://github.com/ghostiam/binstruct) — Binary to struct decoder ☆`114`
*   [csweichel/bel (⭐46)](https://github.com/csweichel/bel) — Generate TypeScript from Go ☆`46`
*   [o1egl/fwencoder (⭐27)](https://github.com/o1egl/fwencoder) — Fixed width file parser ☆`27`
*   [tiendc/go-csvlib (⭐18)](https://github.com/tiendc/go-csvlib) — High-level CSV library ☆`18`

### XML

*   [miku/zek (⭐819)](https://github.com/miku/zek) — Generate Go struct from XML ☆`818`
*   [antchfx/xpath (⭐740)](https://github.com/antchfx/xpath) — XPath for Go ☆`740`
*   [antchfx/xmlquery (⭐488)](https://github.com/antchfx/xmlquery) — XPath XML query ☆`488`

## Data Structures

### Bit-packing and Compression

*   [RoaringBitmap/roaring (⭐2.9k)](https://github.com/RoaringBitmap/roaring) — Compressed bitmaps for Go ☆`2,887`
*   [iancmcc/bingo (⭐52)](https://github.com/iancmcc/bingo) — Zero-allocation binary encoding ☆`52`
*   [amallia/go-ef (⭐41)](https://github.com/amallia/go-ef) — A Go implementation of the Elias-Fano encoding ☆`41`

### Bloom and Cuckoo Filters

*   [bits-and-blooms/bloom (⭐2.8k)](https://github.com/bits-and-blooms/bloom) — Bloom filter implementation ☆`2,787`
*   [tylertreat/BoomFilters (⭐1.6k)](https://github.com/tylertreat/BoomFilters) — Probabilistic data structures for streams ☆`1,646`
*   [seiflotfy/cuckoofilter (⭐1.2k)](https://github.com/seiflotfy/cuckoofilter) — Cuckoo Filter: Practically Better Than Bloom ☆`1,229`
*   [OldPanda/bloomfilter (⭐21)](https://github.com/OldPanda/bloomfilter) — Bloom filter compatible with pybloom ☆`21`

### Maps

*   [mhmtszr/concurrent-swiss-map (⭐261)](https://github.com/mhmtszr/concurrent-swiss-map) — Thread-safe concurrent hash map ☆`261`
*   [lrita/cmap (⭐103)](https://github.com/lrita/cmap) — a thread-safe concurrent map for go ☆`103`
*   [goradd/maps (⭐53)](https://github.com/goradd/maps) — Generic map library for Go ☆`53`
*   [srfrog/dict (⭐46)](https://github.com/srfrog/dict) — Python-like dictionaries for Go ☆`46`

### Miscellaneous

*   [Workiva/go-datastructures (⭐7.9k)](https://github.com/Workiva/go-datastructures) — Performant, threadsafe data structures ☆`7,927`
*   [deckarep/golang-set (⭐4.7k)](https://github.com/deckarep/golang-set) — Generic set type for Go ☆`4,684`
*   [bits-and-blooms/bitset (⭐1.5k)](https://github.com/bits-and-blooms/bitset) — Go package implementing bitsets ☆`1,496`
*   [liyue201/gostl (⭐1.1k)](https://github.com/liyue201/gostl) — Data structures modeled on C++ STL ☆`1,140`
*   [axiomhq/hyperloglog (⭐1k)](https://github.com/axiomhq/hyperloglog) — HyperLogLog with optimizations ☆`1,038`
*   [kelindar/bitmap (⭐377)](https://github.com/kelindar/bitmap) — Simple dense bitmap index in Go with binary operators ☆`378`
*   [barweiss/go-tuple (⭐100)](https://github.com/barweiss/go-tuple) — Go 1.18+ generic tuple ☆`100`
*   [seiflotfy/count-min-log (⭐70)](https://github.com/seiflotfy/count-min-log) — Go implementation of Count-Min-Log ☆`70`
*   [s0rg/quadtree (⭐41)](https://github.com/s0rg/quadtree) — Generic, zero-alloc, 100%-test covered Quadtree for golang ☆`41`
*   [nazar256/parapipe (⭐38)](https://github.com/nazar256/parapipe) — Paralleling pipeline ☆`38`
*   [StudioSol/set (⭐30)](https://github.com/StudioSol/set) — Simple set data structure ☆`30`
*   [bobg/merkle (⭐22)](https://github.com/bobg/merkle) — Merkle hash trees ☆`22`

### Queues

*   [gammazero/deque (⭐775)](https://github.com/gammazero/deque) — Fast ring-buffer deque (double-ended queue) ☆`775`
*   [adrianbrad/queue (⭐352)](https://github.com/adrianbrad/queue) — Multiple queue implementations ☆`356`
*   [embano1/memlog (⭐139)](https://github.com/embano1/memlog) — A Kafka log inspired in-memory and append-only data structure ☆`139`
*   [mikestefanello/backlite (⭐147)](https://github.com/mikestefanello/backlite) — SQLite-backed task queues ☆`147`

## Databases

### Caches

*   [golang/groupcache (⭐13k)](https://github.com/golang/groupcache) — Distributed cache library ☆`13,334`
*   [dgraph-io/ristretto (⭐6.9k)](https://github.com/dgraph-io/ristretto) — A high performance memory-bound Go cache ☆`6,914`
*   [eko/gocache (⭐2.9k)](https://github.com/eko/gocache) — Multi-store caching library ☆`2,864`
*   [maypok86/otter (⭐2.6k)](https://github.com/maypok86/otter) — A high performance caching library for Go ☆`2,618`
*   [VictoriaMetrics/fastcache (⭐2.4k)](https://github.com/VictoriaMetrics/fastcache) — Fast in-memory cache for Go ☆`2,363`
*   [jellydator/ttlcache (⭐1.3k)](https://github.com/jellydator/ttlcache) — An in-memory cache with item expiration and generics ☆`1,252`
*   [viccon/sturdyc (⭐1.2k)](https://github.com/viccon/sturdyc) — Caching with advanced concurrency ☆`1,248`
*   [EchoVault/SugarDB (⭐534)](https://github.com/EchoVault/SugarDB) — Embeddable and distributed in-memory alternative to Redis. ☆`535`
*   [Yiling-J/theine-go (⭐371)](https://github.com/Yiling-J/theine-go) — high performance in-memory cache ☆`372`
*   [elastic/go-freelru (⭐265)](https://github.com/elastic/go-freelru) — GC-less, fast and generic LRU cache for Go ☆`267`
*   [samber/hot (⭐257)](https://github.com/samber/hot) — In-memory caching library for read-intensive Go applications ☆`258`
*   [naughtygopher/pocache (⭐236)](https://github.com/naughtygopher/pocache) — Preemptive optimistic caching ☆`236`
*   [OrlovEvgeny/go-mcache (⭐106)](https://github.com/OrlovEvgeny/go-mcache) — Sharded in-memory KV cache ☆`106`
*   [erni27/imcache (⭐123)](https://github.com/erni27/imcache) — A zero-dependency generic in-memory cache Go library ☆`123`
*   [codingsince1985/couchcache (⭐66)](https://github.com/codingsince1985/couchcache) — A RESTful caching micro-service in Go backed by Couchbase ☆`66`
*   [mdaliyan/icache (⭐23)](https://github.com/mdaliyan/icache) — High-performance generic cache ☆`23`

### Database Schema Migration

*   [golang-migrate/migrate (⭐19k)](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,568`
*   [bytebase/bytebase (⭐14k)](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`14,107`
*   [pressly/goose (⭐11k)](https://github.com/pressly/goose) — A database migration tool. Supports SQL migrations and Go functions. ☆`10,825`
*   [ariga/atlas (⭐8.4k)](https://github.com/ariga/atlas) — Declarative schema migrations with schema-as-code workflows ☆`8,454`
*   [amacneil/dbmate (⭐6.9k)](https://github.com/amacneil/dbmate) — A lightweight, framework-agnostic database migration tool. ☆`6,935`
*   [rubenv/sql-migrate (⭐3.4k)](https://github.com/rubenv/sql-migrate) — SQL schema migration tool for Go. ☆`3,408`
*   [skeema/skeema (⭐1.4k)](https://github.com/skeema/skeema) — Declarative pure-SQL schema management for MySQL and MariaDB ☆`1,369`
*   [go-gormigrate/gormigrate (⭐1.2k)](https://github.com/go-gormigrate/gormigrate) — Minimalistic database migration helper for Gorm ORM ☆`1,163`
*   [sunary/sqlize (⭐124)](https://github.com/sunary/sqlize) — SQL parsing and migration toolkit ☆`124`
*   [robinjoseph08/go-pg-migrations (⭐86)](https://github.com/robinjoseph08/go-pg-migrations) — A Go package to help write migrations with go-pg/pg. ☆`86`
*   [adlio/schema (⭐43)](https://github.com/adlio/schema) — Embedded schema migration package for Go ☆`43`
*   [khezen/avro (⭐48)](https://github.com/khezen/avro) — Apache AVRO for go ☆`48`
*   [muir/libschema (⭐18)](https://github.com/muir/libschema) — database schema migrations on a per-library basis \[Go] ☆`18`

### Database Tools

*   [vitessio/vitess (⭐21k)](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`20,996`
*   [sosedoff/pgweb (⭐9.4k)](https://github.com/sosedoff/pgweb) — Cross-platform client for PostgreSQL databases ☆`9,369`
*   [go-mysql-org/go-mysql (⭐4.9k)](https://github.com/go-mysql-org/go-mysql) — a powerful mysql toolset with Go ☆`4,951`
*   [prest/prest (⭐4.5k)](https://github.com/prest/prest) — PostgreSQL REST API server ☆`4,550`
*   [ContentSquare/chproxy (⭐1.5k)](https://github.com/ContentSquare/chproxy) — Open-Source ClickHouse http proxy and load balancer ☆`1,463`
*   [cybertec-postgresql/pg\_timetable (⭐1.4k)](https://github.com/cybertec-postgresql/pg_timetable) — Advanced PostgreSQL scheduler ☆`1,364`
*   [liweiyi88/onedump (⭐966)](https://github.com/liweiyi88/onedump) — Effortless database administration tool ☆`966`
*   [HDT3213/rdb (⭐611)](https://github.com/HDT3213/rdb) — Redis RDB parser for Go ☆`611`
*   [nikepan/clickhouse-bulk (⭐507)](https://github.com/nikepan/clickhouse-bulk) — Batch inserts for ClickHouse ☆`507`
*   [wesql/wescale (⭐315)](https://github.com/wesql/wescale) — MySQL proxy with read/write split ☆`315`
*   [gatewayd-io/gatewayd (⭐285)](https://github.com/gatewayd-io/gatewayd) — database gateway for building data-driven applications ☆`285`
*   [sj14/dbbench (⭐117)](https://github.com/sj14/dbbench) — Database benchmarking tool ☆`117`
*   [bartventer/gorm-multitenancy (⭐82)](https://github.com/bartventer/gorm-multitenancy) — Multi-tenancy for GORM ☆`82`
*   [kazhuravlev/database-gateway (⭐36)](https://github.com/kazhuravlev/database-gateway) — Safe access to production databases ☆`36`
*   [codingconcepts/dg (⭐44)](https://github.com/codingconcepts/dg) — Generate CSV from data models ☆`45`

### Databases Implemented in Go

*   [prometheus/prometheus (⭐64k)](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`64,262`
*   [milvus-io/milvus (⭐45k)](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`44,636`
*   [pingcap/tidb (⭐40k)](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`40,129`
*   [cockroachdb/cockroach (⭐32k)](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`32,182`
*   [influxdata/influxdb (⭐32k)](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,527`
*   [dolthub/dolt (⭐23k)](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`23,085`
*   [dgraph-io/dgraph (⭐22k)](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,678`
*   [rqlite/rqlite (⭐18k)](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,562`
*   [VictoriaMetrics/VictoriaMetrics (⭐17k)](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`17,107`
*   [dgraph-io/badger (⭐16k)](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,644`
*   [dicedb/dicedb (⭐11k)](https://github.com/dicedb/dicedb) — Low-latency key/value engine on Valkey with storage tiers ☆`10,758`
*   [etcd-io/bbolt (⭐9.5k)](https://github.com/etcd-io/bbolt) — An embedded key/value database for Go. ☆`9,543`
*   [codenotary/immudb (⭐9k)](https://github.com/codenotary/immudb) — Immutable database with SQL ☆`8,977`
*   [cockroachdb/pebble (⭐5.9k)](https://github.com/cockroachdb/pebble) — RocksDB/LevelDB inspired key-value database in Go ☆`5,909`
*   [rosedblabs/rosedb (⭐4.9k)](https://github.com/rosedblabs/rosedb) — Fast key/value storage engine ☆`4,884`
*   [tidwall/buntdb (⭐4.9k)](https://github.com/tidwall/buntdb) — Embeddable in-memory key/value DB ☆`4,856`
*   [nalgeon/redka (⭐4.6k)](https://github.com/nalgeon/redka) — Redis re-implemented with SQL ☆`4,556`
*   [nutsdb/nutsdb (⭐3.6k)](https://github.com/nutsdb/nutsdb) — Simple embeddable key/value store ☆`3,568`
*   [lindb/lindb (⭐3.1k)](https://github.com/lindb/lindb) — Scalable time-series database ☆`3,060`
*   [lotusdblabs/lotusdb (⭐2.3k)](https://github.com/lotusdblabs/lotusdb) — Key-value database with LSM and B+ tree ☆`2,253`
*   [kelindar/column (⭐1.5k)](https://github.com/kelindar/column) — Columnar in-memory store ☆`1,510`
*   [akrylysov/pogreb (⭐1.4k)](https://github.com/akrylysov/pogreb) — Embedded key-value store for read-heavy workloads written in Go ☆`1,351`
*   [objectbox/objectbox-go (⭐1.3k)](https://github.com/objectbox/objectbox-go) — Embedded database for Go ☆`1,268`
*   [couchbase/moss (⭐1k)](https://github.com/couchbase/moss) — Simple, fast key-val storage ☆`1,016`
*   [claygod/transaction (⭐139)](https://github.com/claygod/transaction) — Embedded database for accounts transactions. ☆`139`
*   [xgzlucario/rotom (⭐41)](https://github.com/xgzlucario/rotom) — Tiny Redis server in Go ☆`41`

### Distributed Storage

*   [seaweedfs/seaweedfs (⭐33k)](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`32,720`
*   [juicedata/juicefs (⭐14k)](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`13,664`

### Interfaces to Multiple Backends

*   [philippgille/gokv (⭐828)](https://github.com/philippgille/gokv) — Key-value store abstraction ☆`828`
*   [avito-tech/go-transaction-manager (⭐405)](https://github.com/avito-tech/go-transaction-manager) — Transaction manager for Go ☆`405`
*   [fogfish/dynamo (⭐23)](https://github.com/fogfish/dynamo) — Generic Golang Key/Value trait for AWS storage services ☆`23`
*   [viant/dsc (⭐36)](https://github.com/viant/dsc) — Datastore Connectivity in go ☆`36`

### NoSQL Database Drivers

*   [redis/go-redis (⭐22k)](https://github.com/redis/go-redis) — Redis Go client ☆`22,126`
*   [gomodule/redigo (⭐9.9k)](https://github.com/gomodule/redigo) — Go client for Redis ☆`9,862`
*   [mongodb/mongo-go-driver (⭐8.5k)](https://github.com/mongodb/mongo-go-driver) — The Official Golang driver for MongoDB ☆`8,521`
*   [bradfitz/gomemcache (⭐1.9k)](https://github.com/bradfitz/gomemcache) — Go Memcached client library #golang ☆`1,873`
*   [qiniu/qmgo (⭐1.4k)](https://github.com/qiniu/qmgo) — Go driver for MongoDB ☆`1,353`
*   [Kamva/mgm (⭐764)](https://github.com/Kamva/mgm) — MongoDB ODM for Go based on official driver ☆`764`
*   [aerospike/aerospike-client-go (⭐460)](https://github.com/aerospike/aerospike-client-go) — Aerospike Client Go ☆`459`
*   [couchbase/gocb (⭐375)](https://github.com/couchbase/gocb) — The Couchbase Go SDK ☆`375`
*   [go-kivik/kivik (⭐343)](https://github.com/go-kivik/kivik) — CouchDB client interface ☆`343`
*   [couchbase/go-couchbase (⭐323)](https://github.com/couchbase/go-couchbase) — Couchbase client in Go ☆`323`
*   [chenmingyong0423/go-mongox (⭐219)](https://github.com/chenmingyong0423/go-mongox) — MongoDB driver wrapper with generics ☆`219`
*   [aliexpressru/gomemcached (⭐22)](https://github.com/aliexpressru/gomemcached) — Binary Memcached client with sharding ☆`22`
*   [btnguyen2k/gocosmos (⭐22)](https://github.com/btnguyen2k/gocosmos) — Go database/sql driver for Azure Cosmos DB SQL API ☆`22`

### ORM

*   [go-gorm/gorm (⭐40k)](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,770`
*   [ent/ent (⭐17k)](https://github.com/ent/ent) — An entity framework for Go ☆`17,097`
*   [aarondl/sqlboiler (⭐7k)](https://github.com/aarondl/sqlboiler) — Generate a Go ORM tailored to your database schema. ☆`6,990`
*   [uptrace/bun (⭐4.8k)](https://github.com/uptrace/bun) — SQL-first Golang ORM ☆`4,846`
*   [upper/db (⭐3.7k)](https://github.com/upper/db) — Data access layer for databases ☆`3,659`
*   [stephenafamo/bob (⭐1.7k)](https://github.com/stephenafamo/bob) — SQL builder with ORM generator ☆`1,735`
*   [huandu/go-sqlbuilder (⭐1.7k)](https://github.com/huandu/go-sqlbuilder) — SQL builder with zero-config ORM ☆`1,709`
*   [go-rel/rel (⭐781)](https://github.com/go-rel/rel) — Modern ORM for Golang ☆`781`
*   [hashicorp/go-dbw (⭐17)](https://github.com/hashicorp/go-dbw) — A simple package that encapsulates database operations. ☆`17`
*   [FrancoLiberali/cql (⭐17)](https://github.com/FrancoLiberali/cql) — CQL: Compiled Query Language ☆`17`

### Query Language

*   [99designs/gqlgen (⭐11k)](https://github.com/99designs/gqlgen) — go generate based graphql server library ☆`10,722`
*   [TomWright/dasel (⭐8k)](https://github.com/TomWright/dasel) — Query and modify data formats ☆`7,964`
*   [graph-gophers/graphql-go (⭐4.8k)](https://github.com/graph-gophers/graphql-go) — GraphQL server with a focus on ease of use ☆`4,754`
*   [bhmj/jsonslice (⭐92)](https://github.com/bhmj/jsonslice) — json slicer ☆`92`
*   [hashicorp/mql (⭐65)](https://github.com/hashicorp/mql) — Model Query Language (mql) is a query language for your database models. ☆`65`
*   [ccbrown/api-fu (⭐57)](https://github.com/ccbrown/api-fu) — A collection of Go packages for creating robust GraphQL APIs ☆`57`
*   [AsaiYusuke/jsonpath (⭐30)](https://github.com/AsaiYusuke/jsonpath) — JSONPath query library ☆`30`

### Relational Database Drivers

*   [go-sql-driver/mysql (⭐15k)](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,245`
*   [jackc/pgx (⭐14k)](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`13,888`
*   [denisenkom/go-mssqldb (⭐1.9k)](https://github.com/denisenkom/go-mssqldb) — Microsoft SQL server driver written in go language ☆`1,883`
*   [ncruces/go-sqlite3 (⭐1k)](https://github.com/ncruces/go-sqlite3) — Go bindings to SQLite using wasm2go ☆`1,026`
*   [godror/godror (⭐594)](https://github.com/godror/godror) — GO DRiver for ORacle DB ☆`595`
*   [cvilsmeier/sqinn-go (⭐532)](https://github.com/cvilsmeier/sqinn-go) — Golang SQLite without cgo ☆`531`
*   [VinGarcia/ksql (⭐356)](https://github.com/VinGarcia/ksql) — A Simple and Powerful Golang SQL Library ☆`354`
*   [surrealdb/surrealdb.go (⭐309)](https://github.com/surrealdb/surrealdb.go) — SurrealDB SDK for Golang ☆`310`
*   [nakagami/firebirdsql (⭐262)](https://github.com/nakagami/firebirdsql) — Firebird RDBMS sql driver for Go (golang) ☆`262`
*   [ydb-platform/ydb-go-sdk (⭐180)](https://github.com/ydb-platform/ydb-go-sdk) — Pure Go native and database/sql driver for YDB ☆`180`
*   [rqlite/gorqlite (⭐185)](https://github.com/rqlite/gorqlite) — A Go client for rqlite, the distributed database built on SQLite ☆`186`
*   [apache/calcite-avatica-go (⭐124)](https://github.com/apache/calcite-avatica-go) — Apache Calcite Go ☆`124`

### SQL Query Builders

*   [sqlc-dev/sqlc (⭐18k)](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`17,834`
*   [xo/dbtpl (⭐3.9k)](https://github.com/xo/dbtpl) — Generate Go code for databases ☆`3,892`
*   [go-jet/jet (⭐3.7k)](https://github.com/go-jet/jet) — Type-safe SQL builder with codegen ☆`3,710`
*   [lqs/sqlingo (⭐453)](https://github.com/lqs/sqlingo) — A lightweight DSL & ORM which helps you to write SQL in Go. ☆`453`
*   [nullism/bqb (⭐194)](https://github.com/nullism/bqb) — Lightweight query builder ☆`194`
*   [JiveGroup/FluentSQL (⭐18)](https://github.com/JiveGroup/FluentSQL) — Fluent SQL - flexible and powerful SQL string builder ☆`18`

### Search and Analytic Databases

*   [elastic/go-elasticsearch (⭐6k)](https://github.com/elastic/go-elasticsearch) — The official Go client for Elasticsearch ☆`6,051`
*   [ClickHouse/clickhouse-go (⭐3.3k)](https://github.com/ClickHouse/clickhouse-go) — Golang driver for ClickHouse ☆`3,299`
*   [sourcegraph/zoekt (⭐1.7k)](https://github.com/sourcegraph/zoekt) — Fast trigram-based code search ☆`1,678`
*   [sdqri/effdsl (⭐34)](https://github.com/sdqri/effdsl) — Elasticsearch query builder for golang ☆`34`

## DevOps & Build

### Backup

*   [restic/restic (⭐34k)](https://github.com/restic/restic) — Fast, secure backup program ☆`33,869`
*   [gilbertchen/duplicacy (⭐5.7k)](https://github.com/gilbertchen/duplicacy) — Cloud backup tool ☆`5,652`

### Build Automation

*   [air-verse/air (⭐24k)](https://github.com/air-verse/air) — Live reload for Go apps ☆`23,637`
*   [go-task/task (⭐16k)](https://github.com/go-task/task) — Fast cross-platform build tool inspired by Make ☆`15,668`
*   [joerdav/xc (⭐1.4k)](https://github.com/joerdav/xc) — Markdown defined task runner. ☆`1,385`
*   [goyek/goyek (⭐688)](https://github.com/goyek/goyek) — Task automation Go library ☆`690`
*   [flowexec/flow (⭐136)](https://github.com/flowexec/flow) — Local-first developer automation platform — workflows, secrets, templates, and more. ☆`137`

### CI/CD

*   [harness/harness (⭐36k)](https://github.com/harness/harness) — End-to-end developer platform ☆`36,386`
*   [woodpecker-ci/woodpecker (⭐7.1k)](https://github.com/woodpecker-ci/woodpecker) — Simple, powerful CI/CD engine ☆`7,208`
*   [ovh/cds (⭐4.8k)](https://github.com/ovh/cds) — Enterprise CI/CD platform ☆`4,821`
*   [raviqqe/muffet (⭐2.6k)](https://github.com/raviqqe/muffet) — Fast website link checker ☆`2,607`
*   [pipe-cd/pipecd (⭐1.3k)](https://github.com/pipe-cd/pipecd) — The One CD for All {applications, platforms, operations} ☆`1,284`
*   [jenkins-zh/jenkins-cli (⭐421)](https://github.com/jenkins-zh/jenkins-cli) — Jenkins CLI allows you to manage your Jenkins in an easy way ☆`421`
*   [vladopajic/go-test-coverage (⭐233)](https://github.com/vladopajic/go-test-coverage) — Report test coverage threshold issues ☆`235`
*   [appleboy/drone-scp (⭐171)](https://github.com/appleboy/drone-scp) — Copy files via SSH for Drone ☆`172`
*   [nikogura/gomason (⭐67)](https://github.com/nikogura/gomason) — A tool for testing, building, signing, and publishing binaries. ☆`67`
*   [appleboy/drone-jenkins (⭐41)](https://github.com/appleboy/drone-jenkins) — Drone plugin for trigger Jenkins jobs. ☆`41`
*   [opnlabs/dot (⭐37)](https://github.com/opnlabs/dot) — Minimal CI using Docker ☆`37`

### Containers

*   [moby/moby (⭐72k)](https://github.com/moby/moby) — Container ecosystem components ☆`71,623`
*   [traefik/traefik (⭐63k)](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`63,564`
*   [ko-build/ko (⭐8.4k)](https://github.com/ko-build/ko) — Build and deploy Go applications ☆`8,443`
*   [s0rg/decompose (⭐133)](https://github.com/s0rg/decompose) — Reverse-engineering tool for docker environments ☆`133`
*   [x1unix/docker-go-mingw (⭐54)](https://github.com/x1unix/docker-go-mingw) — Docker for Go with MinGW toolchain ☆`54`

### DevOps Utilities

*   [go-gitea/gitea (⭐56k)](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`56,122`
*   [moovweb/gvm (⭐12k)](https://github.com/moovweb/gvm) — Go Version Manager ☆`11,637`
*   [TwiN/gatus (⭐11k)](https://github.com/TwiN/gatus) — Developer-oriented status page with alerting ☆`11,135`
*   [bitfield/script (⭐7k)](https://github.com/bitfield/script) — Making it easy to write shell-like scripts in Go ☆`6,977`
*   [fleetdm/fleet (⭐6.4k)](https://github.com/fleetdm/fleet) — Open device management ☆`6,435`
*   [taubyte/tau (⭐5k)](https://github.com/taubyte/tau) — Fullstack Workspace for Humans & Machines ☆`5,047`
*   [megaease/easeprobe (⭐2.3k)](https://github.com/megaease/easeprobe) — Service health monitoring tool ☆`2,297`
*   [ajvb/kala (⭐2.2k)](https://github.com/ajvb/kala) — Modern Job Scheduler ☆`2,156`
*   [gabrie30/ghorg (⭐2k)](https://github.com/gabrie30/ghorg) — Clone entire GitHub orgs ☆`2,053`
*   [sanbornm/go-selfupdate (⭐1.7k)](https://github.com/sanbornm/go-selfupdate) — Enable your Go applications to self update ☆`1,691`
*   [yusufcanb/tlm (⭐1.5k)](https://github.com/yusufcanb/tlm) — Local CLI Copilot, powered by Ollama. ☆`1,483`
*   [ovh/utask (⭐1.4k)](https://github.com/ovh/utask) — Automation engine with YAML config ☆`1,380`
*   [TimothyYe/skm (⭐1.1k)](https://github.com/TimothyYe/skm) — A simple and powerful SSH keys manager ☆`1,062`
*   [scaleway/scaleway-cli (⭐972)](https://github.com/scaleway/scaleway-cli) — Command Line Interface for Scaleway ☆`974`
*   [alexliesenfeld/health (⭐833)](https://github.com/alexliesenfeld/health) — A simple and flexible health check library for Go. ☆`833`
*   [kool-dev/kool (⭐720)](https://github.com/kool-dev/kool) — Dev to cloud web apps made easy ☆`721`
*   [kevincobain2000/gobrew (⭐421)](https://github.com/kevincobain2000/gobrew) — Go version manager without root ☆`422`
*   [appleboy/easyssh-proxy (⭐346)](https://github.com/appleboy/easyssh-proxy) — Simple SSH protocol implementation ☆`346`
*   [xitonix/trubka (⭐337)](https://github.com/xitonix/trubka) — A CLI tool for Kafka ☆`337`
*   [thevxn/dish (⭐276)](https://github.com/thevxn/dish) — A simple, remotely configurable monitoring service. ☆`276`
*   [jkaninda/goma-gateway (⭐180)](https://github.com/jkaninda/goma-gateway) — Lightweight API gateway and proxy ☆`180`
*   [datarootsio/tf-profile (⭐163)](https://github.com/datarootsio/tf-profile) — Profile Terraform runs ☆`163`
*   [kazhuravlev/healthcheck (⭐23)](https://github.com/kazhuravlev/healthcheck) — Readiness probes for Kubernetes application ☆`23`

### Infrastructure

*   [hashicorp/packer (⭐16k)](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,697`
*   [pomerium/pomerium (⭐4.8k)](https://github.com/pomerium/pomerium) — Pomerium is an identity and context-aware access proxy. ☆`4,828`
*   [peak/s5cmd (⭐4.1k)](https://github.com/peak/s5cmd) — Parallel S3 and local filesystem execution tool. ☆`4,076`
*   [aptly-dev/aptly (⭐2.8k)](https://github.com/aptly-dev/aptly) — aptly - Debian repository management tool ☆`2,838`
*   [KusionStack/kusion (⭐1.3k)](https://github.com/KusionStack/kusion) — Declarative platform orchestrator ☆`1,311`
*   [oxyno-zeta/s3-proxy (⭐461)](https://github.com/oxyno-zeta/s3-proxy) — S3 reverse proxy with auth ☆`465`

### Kubernetes

*   [kubernetes/kubernetes (⭐122k)](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`122,694`
*   [k3s-io/k3s (⭐33k)](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`33,170`
*   [kubernetes/minikube (⭐32k)](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,840`
*   [kubernetes-sigs/kind (⭐15k)](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,277`
*   [kubeshark/kubeshark (⭐12k)](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`11,922`
*   [flannel-io/flannel (⭐9.5k)](https://github.com/flannel-io/flannel) — Network fabric for containers ☆`9,463`
*   [getanteon/anteon (⭐8.5k)](https://github.com/getanteon/anteon) — eBPF Kubernetes monitoring tool ☆`8,531`
*   [kubevela/kubevela (⭐7.8k)](https://github.com/kubevela/kubevela) — The Modern Application Platform. ☆`7,769`
*   [k3d-io/k3d (⭐6.4k)](https://github.com/k3d-io/k3d) — Little helper to run CNCF's k3s in Docker ☆`6,444`
*   [stefanprodan/podinfo (⭐5.9k)](https://github.com/stefanprodan/podinfo) — Go microservice template for Kubernetes ☆`5,911`
*   [apecloud/kubeblocks (⭐3k)](https://github.com/apecloud/kubeblocks) — Kubernetes operator for databases ☆`3,050`
*   [kubenetworks/kubevpn (⭐1.3k)](https://github.com/kubenetworks/kubevpn) — Connect to Kubernetes cluster network ☆`1,330`
*   [abahmed/kwatch (⭐1k)](https://github.com/abahmed/kwatch) — monitor & detect crashes in your Kubernetes(K8s) cluster instantly ☆`1,008`
*   [getanteon/alaz (⭐719)](https://github.com/getanteon/alaz) — eBPF agent for K8s observability ☆`716`

### Load Testing

*   [grafana/k6 (⭐31k)](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`30,729`
*   [tsenart/vegeta (⭐25k)](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`25,059`
*   [codesenberg/bombardier (⭐6.8k)](https://github.com/codesenberg/bombardier) — Fast cross-platform HTTP benchmarking tool written in Go ☆`6,790`
*   [rogerwelin/cassowary (⭐810)](https://github.com/rogerwelin/cassowary) — Modern cross-platform HTTP load-testing tool written in Go ☆`810`

## Email

*   [axllent/mailpit (⭐9.5k)](https://github.com/axllent/mailpit) — An email and SMTP testing tool with API for developers ☆`9,591`
*   [foxcpp/maddy (⭐6k)](https://github.com/foxcpp/maddy) — Composable all-in-one mail server. ☆`5,993`
*   [mjl-/mox (⭐5.7k)](https://github.com/mjl-/mox) — Modern secure mail server ☆`5,708`
*   [matcornic/hermes (⭐3k)](https://github.com/matcornic/hermes) — Clean HTML email generator ☆`3,005`
*   [AfterShip/email-verifier (⭐1.6k)](https://github.com/AfterShip/email-verifier) — Email verification without sending emails ☆`1,574`
*   [wneessen/go-mail (⭐1.4k)](https://github.com/wneessen/go-mail) — Easy to use, yet comprehensive library for sending mails with Go ☆`1,382`
*   [sendgrid/sendgrid-go (⭐1.1k)](https://github.com/sendgrid/sendgrid-go) — The Official Twilio SendGrid Golang API Library ☆`1,057`
*   [mailgun/mailgun-go (⭐745)](https://github.com/mailgun/mailgun-go) — Go library for the Mailgun API. ☆`745`
*   [xhit/go-simple-mail (⭐694)](https://github.com/xhit/go-simple-mail) — Simple mail sending with TLS/SSL ☆`695`
*   [emersion/go-message (⭐450)](https://github.com/emersion/go-message) — Internet Message Format library ☆`451`
*   [vanng822/go-premailer (⭐200)](https://github.com/vanng822/go-premailer) — Inline CSS for HTML mail ☆`201`
*   [truemail-rb/truemail-go (⭐135)](https://github.com/truemail-rb/truemail-go) — Email validator via Regex, DNS, SMTP ☆`135`
*   [toorop/go-dkim (⭐99)](https://github.com/toorop/go-dkim) — DKIM package for golang ☆`99`
*   [dimuska139/go-email-normalizer (⭐78)](https://github.com/dimuska139/go-email-normalizer) — Normalize email addresses ☆`78`
*   [valord577/mailx (⭐22)](https://github.com/valord577/mailx) — A library that makes it easier to send email via SMTP. ☆`22`

## Finance & Blockchain

### Blockchain

*   [ethereum/go-ethereum (⭐51k)](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`51,072`
*   [ipfs/kubo (⭐17k)](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`17,035`
*   [lightningnetwork/lnd (⭐8.2k)](https://github.com/lightningnetwork/lnd) — Lightning Network Daemon ☆`8,149`
*   [cosmos/cosmos-sdk (⭐7k)](https://github.com/cosmos/cosmos-sdk) — Framework for building performant, customizable blockchains with native interoperability ☆`7,004`
*   [solana-foundation/solana-go (⭐1.6k)](https://github.com/solana-foundation/solana-go) — Go SDK library and RPC client for the Solana Blockchain ☆`1,556`
*   [gnolang/gno (⭐1.1k)](https://github.com/gnolang/gno) — Interpreted Go virtual machine ☆`1,071`
*   [cometbft/cometbft (⭐893)](https://github.com/cometbft/cometbft) — Byzantine fault-tolerant consensus ☆`895`
*   [ChainSafe/gossamer (⭐452)](https://github.com/ChainSafe/gossamer) — Go Implementation of the Polkadot Host ☆`452`

### Financial

*   [shopspring/decimal (⭐7.4k)](https://github.com/shopspring/decimal) — Arbitrary-precision fixed-point decimal numbers in Go ☆`7,388`
*   [achannarasappa/ticker (⭐6.1k)](https://github.com/achannarasappa/ticker) — Terminal stock and crypto tracker ☆`6,096`
*   [Rhymond/go-money (⭐1.9k)](https://github.com/Rhymond/go-money) — Go implementation of Fowler's Money pattern ☆`1,889`
*   [c9s/bbgo (⭐1.6k)](https://github.com/c9s/bbgo) — The modern cryptocurrency trading bot framework written in Go. ☆`1,652`
*   [formancehq/ledger (⭐1.2k)](https://github.com/formancehq/ledger) — The programmable open source core ledger for fintech ☆`1,247`
*   [bojanz/currency (⭐639)](https://github.com/bojanz/currency) — Currency handling for Go. ☆`640`
*   [moov-io/ach (⭐544)](https://github.com/moov-io/ach) — ACH file reader, writer, validator ☆`546`
*   [invopop/gobl (⭐277)](https://github.com/invopop/gobl) — Go Business Language ☆`282`
*   [govalues/decimal (⭐238)](https://github.com/govalues/decimal) — Correctly rounded decimals for Go ☆`240`
*   [quagmt/udecimal (⭐182)](https://github.com/quagmt/udecimal) — High-precision decimal library ☆`182`
*   [jovandeginste/payme (⭐90)](https://github.com/jovandeginste/payme) — QR code generator (ASCII & PNG) for SEPA payments ☆`90`
*   [jokruger/dec128 (⭐44)](https://github.com/jokruger/dec128) — High performance 128-bit fixed-point decimal numbers in go. ☆`44`
*   [nikolaydubina/fpmoney (⭐35)](https://github.com/nikolaydubina/fpmoney) — Fixed-Point Decimal Money ☆`35`
*   [nikolaydubina/fpdecimal (⭐34)](https://github.com/nikolaydubina/fpdecimal) — Fixed-Point Decimals ☆`34`
*   [govalues/money (⭐53)](https://github.com/govalues/money) — Correctly rounded monetary amounts and exchange rates for Go ☆`54`

### Payment APIs

*   [stripe/stripe-go (⭐2.6k)](https://github.com/stripe/stripe-go) — Stripe API library for Go ☆`2,588`
*   [plutov/paypal (⭐774)](https://github.com/plutov/paypal) — Golang client for PayPal REST API ☆`774`
*   [brunomvsouza/ynab.go (⭐78)](https://github.com/brunomvsouza/ynab.go) — Client for YNAB API ☆`78`

## GUI & Desktop

### GUI

*   [fyne-io/fyne (⭐28k)](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`28,332`
*   [webview/webview (⭐14k)](https://github.com/webview/webview) — Tiny webview library for Go ☆`14,090`
*   [go-vgo/robotgo (⭐11k)](https://github.com/go-vgo/robotgo) — Cross-platform RPA and GUI automation ☆`10,717`
*   [maxence-charriere/go-app (⭐8.9k)](https://github.com/maxence-charriere/go-app) — Build progressive web apps with Go and WASM ☆`8,923`
*   [progrium/darwinkit (⭐5.4k)](https://github.com/progrium/darwinkit) — Native Mac APIs for Go. Previously known as MacDriver ☆`5,432`
*   [getlantern/systray (⭐3.7k)](https://github.com/getlantern/systray) — Cross-platform systray library ☆`3,704`
*   [cogentcore/core (⭐2.3k)](https://github.com/cogentcore/core) — Powerful GUI framework for Go ☆`2,327`
*   [gotk3/gotk3 (⭐2.2k)](https://github.com/gotk3/gotk3) — Go bindings for GTK3 ☆`2,206`
*   [roblillack/spot (⭐1.3k)](https://github.com/roblillack/spot) — React-like desktop GUI toolkit for Go ☆`1,258`
*   [ncruces/zenity (⭐909)](https://github.com/ncruces/zenity) — Zenity dialogs for Golang, Windows, macOS ☆`911`
*   [energye/energy (⭐594)](https://github.com/energye/energy) — CEF-based GUI framework ☆`595`
*   [AllenDang/cimgui-go (⭐518)](https://github.com/AllenDang/cimgui-go) — Auto generated Go wrapper for Dear ImGui via cimgui ☆`518`
*   [richardwilkes/unison (⭐323)](https://github.com/richardwilkes/unison) — Unified GUI toolkit for Go ☆`325`

### Windows

*   [go-ole/go-ole (⭐1.3k)](https://github.com/go-ole/go-ole) — win32 ole implementation for golang ☆`1,310`
*   [gonutz/d3d9 (⭐164)](https://github.com/gonutz/d3d9) — Direct3D9 wrapper for Go. ☆`164`

## Game Development

### Game Engines

*   [hajimehoshi/ebiten (⭐13k)](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`13,207`
*   [fogleman/nes (⭐5.6k)](https://github.com/fogleman/nes) — NES emulator written in Go. ☆`5,646`
*   [topfreegames/pitaya (⭐2.8k)](https://github.com/topfreegames/pitaya) — Game server with clustering support ☆`2,785`
*   [xiaonanln/goworld (⭐2.7k)](https://github.com/xiaonanln/goworld) — Distributed game server engine ☆`2,716`
*   [gen2brain/raylib-go (⭐2.4k)](https://github.com/gen2brain/raylib-go) — Go bindings for raylib ☆`2,446`
*   [oakmound/oak (⭐1.7k)](https://github.com/oakmound/oak) — A pure Go game engine ☆`1,657`
*   [JoelOtter/termloop (⭐1.5k)](https://github.com/JoelOtter/termloop) — Terminal-based game engine for Go, built on top of Termbox ☆`1,476`
*   [gopxl/pixel (⭐387)](https://github.com/gopxl/pixel) — A hand-crafted 2D game library in Go. ☆`391`
*   [ungerik/go3d (⭐339)](https://github.com/ungerik/go3d) — A performance oriented 2D/3D math package for Go ☆`339`
*   [mlange-42/ark (⭐273)](https://github.com/mlange-42/ark) — Ark -- Archetype-based Entity Component System (ECS) for Go. ☆`280`
*   [kelindar/tile (⭐222)](https://github.com/kelindar/tile) — 2D grid engine for games ☆`222`
*   [andygeiss/ecs (⭐176)](https://github.com/andygeiss/ecs) — Entity Component System for games ☆`175`
*   [gonutz/prototype (⭐108)](https://github.com/gonutz/prototype) — 2D game prototyping framework ☆`108`
*   [s0rg/fantasyname (⭐43)](https://github.com/s0rg/fantasyname) — RinkWorks fantasy name generator for golang ☆`43`
*   [s0rg/grid (⭐26)](https://github.com/s0rg/grid) — Generic 2D grid ☆`26`

### OpenGL

*   [go-gl/glfw (⭐1.7k)](https://github.com/go-gl/glfw) — Go bindings for GLFW 3 ☆`1,685`
*   [go-gl/gl (⭐1.2k)](https://github.com/go-gl/gl) — Go bindings for OpenGL (generated via glow) ☆`1,198`
*   [go-gl/mathgl (⭐606)](https://github.com/go-gl/mathgl) — A pure Go 3D math library. ☆`606`

## Geospatial

*   [tidwall/tile38 (⭐9.7k)](https://github.com/tidwall/tile38) — Real-time Geospatial and Geofencing ☆`9,664`
*   [golang/geo (⭐1.8k)](https://github.com/golang/geo) — S2 geometry library in Go ☆`1,838`
*   [consbio/mbtileserver (⭐783)](https://github.com/consbio/mbtileserver) — MBTiles server in Go ☆`783`
*   [paulmach/osm (⭐457)](https://github.com/paulmach/osm) — OpenStreetMap data library ☆`458`
*   [uber/h3-go (⭐427)](https://github.com/uber/h3-go) — H3 hexagonal geospatial indexing ☆`432`
*   [airbusgeo/godal (⭐176)](https://github.com/airbusgeo/godal) — GDAL wrapper for Go ☆`176`
*   [peterstace/simplefeatures (⭐172)](https://github.com/peterstace/simplefeatures) — OpenGIS Simple Feature implementation ☆`172`
*   [wroge/wgs84 (⭐141)](https://github.com/wroge/wgs84) — Zero-dep coordinate transformations ☆`141`
*   [pantrif/s2-geojson (⭐37)](https://github.com/pantrif/s2-geojson) — Visualize S2 cells on a map ☆`37`

## Go Tooling

### Compilers

*   [gopherjs/gopherjs (⭐13k)](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,152`
*   [yassinebenaid/bunster (⭐2.7k)](https://github.com/yassinebenaid/bunster) — Compile shell scripts to static binaries. ☆`2,672`
*   [Konstantin8105/c4go (⭐376)](https://github.com/Konstantin8105/c4go) — Transpiling C code to Go code ☆`376`
*   [go2hx/go2hx (⭐150)](https://github.com/go2hx/go2hx) — Import Go libraries in Haxe ☆`150`

### Editor Plugins

*   [fatih/vim-go (⭐16k)](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,235`
*   [visualfc/liteide (⭐7.8k)](https://github.com/visualfc/liteide) — LiteIDE is a simple, open source, cross-platform Go IDE. ☆`7,755`
*   [nsf/gocode (⭐5k)](https://github.com/nsf/gocode) — An autocompletion daemon for the Go programming language ☆`4,996`
*   [golang/vscode-go (⭐4.2k)](https://github.com/golang/vscode-go) — Go extension for Visual Studio Code ☆`4,249`
*   [dominikh/go-mode.el (⭐1.4k)](https://github.com/dominikh/go-mode.el) — Emacs mode for the Go programming language ☆`1,450`
*   [incu6us/goimports-reviser (⭐714)](https://github.com/incu6us/goimports-reviser) — Imports sorting and code formatting tool ☆`714`

### Generate Tools

*   [xuri/xgen (⭐412)](https://github.com/xuri/xgen) — XSD parser and code generator ☆`414`
*   [kazhuravlev/options-gen (⭐106)](https://github.com/kazhuravlev/options-gen) — Codegen for functional options in go projects ☆`106`
*   [g4s8/envdoc (⭐95)](https://github.com/g4s8/envdoc) — Go tool to generate documentation for environment variables ☆`95`

### Go Tools

*   [go-swagger/go-swagger (⭐10k)](https://github.com/go-swagger/go-swagger) — Swagger 2.0 implementation for go ☆`9,985`
*   [ondrajz/go-callvis (⭐6.5k)](https://github.com/ondrajz/go-callvis) — Visualize call graph of a Go program using Graphviz ☆`6,484`
*   [Zxilly/go-size-analyzer (⭐2.1k)](https://github.com/Zxilly/go-size-analyzer) — Analyze compiled Go binary size ☆`2,145`
*   [pointlander/peg (⭐1.1k)](https://github.com/pointlander/peg) — PEG parser generator for Go ☆`1,112`
*   [safedep/vet (⭐1.1k)](https://github.com/safedep/vet) — Protect against malicious open source packages ☆`1,066`
*   [janpfeifer/gonb (⭐1k)](https://github.com/janpfeifer/gonb) — Go notebook kernel for Jupyter ☆`1,027`
*   [alajmo/sake (⭐745)](https://github.com/alajmo/sake) — Task runner for local and remote hosts ☆`745`
*   [goccmack/gocc (⭐660)](https://github.com/goccmack/gocc) — Parser and scanner generator ☆`660`
*   [iyashjayesh/monigo (⭐411)](https://github.com/iyashjayesh/monigo) — Performance monitoring library ☆`408`
*   [becheran/roumon (⭐235)](https://github.com/becheran/roumon) — Universal goroutine monitor using pprof and termui ☆`235`
*   [bitfield/gotestdox (⭐196)](https://github.com/bitfield/gotestdox) — A tool for formatting Go test results as readable documentation ☆`196`
*   [ahmedakef/gotutor (⭐82)](https://github.com/ahmedakef/gotutor) — Online Go Debugger & Visualizer ☆`82`
*   [bobg/modver (⭐21)](https://github.com/bobg/modver) — a tool that helps you obey semantic versioning rules in your Go module ☆`21`
*   [bobg/decouple (⭐36)](https://github.com/bobg/decouple) — find overspecified function parameters in Go code ☆`36`

## Hardware & IoT

### Hardware

*   [shirou/gopsutil (⭐12k)](https://github.com/shirou/gopsutil) — psutil for golang ☆`11,851`
*   [arduino/arduino-cli (⭐4.9k)](https://github.com/arduino/arduino-cli) — Arduino command line tool ☆`4,920`
*   [jaypipes/ghw (⭐1.9k)](https://github.com/jaypipes/ghw) — Go HardWare discovery/inspection library ☆`1,865`
*   [zcalusic/sysinfo (⭐576)](https://github.com/zcalusic/sysinfo) — Linux system information library ☆`575`

### IoT

*   [hybridgroup/gobot (⭐9.4k)](https://github.com/hybridgroup/gobot) — Robotics and IoT framework ☆`9,421`
*   [lf-edge/ekuiper (⭐1.7k)](https://github.com/lf-edge/ekuiper) — Lightweight data stream processing engine for IoT edge ☆`1,708`
*   [rulego/rulego (⭐1.5k)](https://github.com/rulego/rulego) — Lightweight rule engine framework ☆`1,528`
*   [Edgenesis/shifu (⭐1.4k)](https://github.com/Edgenesis/shifu) — Kubernetes-native IoT gateway ☆`1,418`
*   [e154/smart-home (⭐98)](https://github.com/e154/smart-home) — software package for automation ☆`98`
*   [maxatome/go-vitotrol (⭐23)](https://github.com/maxatome/go-vitotrol) — golang client library to Viessmann Vitotrol web service ☆`23`

## Networking

### Consensus

*   [hashicorp/raft (⭐9k)](https://github.com/hashicorp/raft) — Golang implementation of the Raft consensus protocol ☆`9,026`
*   [lni/dragonboat (⭐5.3k)](https://github.com/lni/dragonboat) — Multi-group Raft consensus library ☆`5,310`
*   [etcd-io/raft (⭐1k)](https://github.com/etcd-io/raft) — Raft library for maintaining a replicated state machine ☆`1,044`
*   [vadiminshakov/committer (⭐43)](https://github.com/vadiminshakov/committer) — 2PC and 3PC protocols for Go ☆`43`

### DNS

*   [miekg/dns (⭐8.7k)](https://github.com/miekg/dns) — DNS library in Go ☆`8,694`
*   [0xERR0R/blocky (⭐6.6k)](https://github.com/0xERR0R/blocky) — DNS ad-blocker for local networks ☆`6,672`
*   [hashicorp/mdns (⭐1.4k)](https://github.com/hashicorp/mdns) — Simple mDNS client/server library in Golang ☆`1,360`
*   [semihalev/sdns (⭐1k)](https://github.com/semihalev/sdns) — High-performance recursive DNS ☆`1,042`
*   [FenkoHQ/dnsmonster (⭐355)](https://github.com/FenkoHQ/dnsmonster) — Passive DNS Capture and Monitoring Toolkit ☆`355`
*   [joeig/go-powerdns (⭐103)](https://github.com/joeig/go-powerdns) — PowerDNS API client for Go (community project) ☆`103`

### Distributed Utilities

*   [luraproject/lura (⭐6.8k)](https://github.com/luraproject/lura) — Ultra-performant API gateway ☆`6,778`
*   [chrislusf/gleam (⭐3.6k)](https://github.com/chrislusf/gleam) — Distributed map/reduce in Go ☆`3,562`
*   [bsm/redislock (⭐1.8k)](https://github.com/bsm/redislock) — Simplified distributed locking implementation using Redis ☆`1,756`
*   [k8gb-io/k8gb (⭐1.2k)](https://github.com/k8gb-io/k8gb) — A cloud native Kubernetes Global Balancer ☆`1,175`
*   [temporalio/sdk-go (⭐898)](https://github.com/temporalio/sdk-go) — Temporal Go SDK ☆`904`
*   [AppsFlyer/go-sundheit (⭐561)](https://github.com/AppsFlyer/go-sundheit) — Health checks library for Go ☆`561`
*   [tarmac-project/tarmac (⭐343)](https://github.com/tarmac-project/tarmac) — Functions as Monolith or Microservices ☆`343`
*   [italolelis/outboxer (⭐167)](https://github.com/italolelis/outboxer) — A library that implements the outboxer pattern in go ☆`167`
*   [capillariesio/capillaries (⭐72)](https://github.com/capillariesio/capillaries) — Distributed batch data processing framework ☆`72`
*   [svcavallar/celeriac.v1 (⭐76)](https://github.com/svcavallar/celeriac.v1) — Celery client for Go ☆`76`
*   [pdupub/go-pdu (⭐49)](https://github.com/pdupub/go-pdu) — An PDU implementation in Go ☆`49`
*   [mbrostami/consistenthash (⭐32)](https://github.com/mbrostami/consistenthash) — Consistent hashing implementation ☆`32`

### HTTP & Proxy

*   [valyala/fasthttp (⭐23k)](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,366`
*   [elazarl/goproxy (⭐6.7k)](https://github.com/elazarl/goproxy) — An HTTP proxy library for Go ☆`6,686`
*   [wzshiming/httpproxy (⭐32)](https://github.com/wzshiming/httpproxy) — HTTP proxy handler and dialer ☆`32`

### HTTP Clients

*   [go-resty/resty (⭐12k)](https://github.com/go-resty/resty) — Simple HTTP, REST, and SSE client library for Go ☆`11,688`
*   [imroc/req (⭐4.8k)](https://github.com/imroc/req) — Simple Go HTTP client with Black Magic ☆`4,799`
*   [gojek/heimdall (⭐2.7k)](https://github.com/gojek/heimdall) — An enhanced HTTP client for Go ☆`2,710`
*   [hashicorp/go-retryablehttp (⭐2.3k)](https://github.com/hashicorp/go-retryablehttp) — Retryable HTTP client in Go ☆`2,326`
*   [levigross/grequests (⭐2.2k)](https://github.com/levigross/grequests) — A Go "clone" of the great and famous Requests library ☆`2,188`
*   [dghubble/sling (⭐1.7k)](https://github.com/dghubble/sling) — A Go HTTP client library for creating and sending API requests ☆`1,717`
*   [bogdanfinn/tls-client (⭐1.6k)](https://github.com/bogdanfinn/tls-client) — HTTP client with TLS fingerprint spoofing ☆`1,649`
*   [earthboundkid/requests (⭐1.7k)](https://github.com/earthboundkid/requests) — HTTP requests for Gophers ☆`1,670`
*   [Noooste/azuretls-client (⭐450)](https://github.com/Noooste/azuretls-client) — HTTP client to spoof TLS/JA3 fingerprint ☆`452`
*   [monaco-io/request (⭐296)](https://github.com/monaco-io/request) — go request, go http client ☆`296`
*   [opus-domini/fast-shot (⭐123)](https://github.com/opus-domini/fast-shot) — Fluent HTTP client for Go ☆`124`
*   [NdoleStudio/go-otelroundtripper (⭐87)](https://github.com/NdoleStudio/go-otelroundtripper) — OpenTelemetry metrics for HTTP clients ☆`87`
*   [go-zoox/fetch (⭐88)](https://github.com/go-zoox/fetch) — Powerful HTTP client for Go ☆`88`
*   [rezmoss/axios4go (⭐36)](https://github.com/rezmoss/axios4go) — Axios-inspired HTTP client ☆`36`
*   [lib4u/fake-useragent (⭐16)](https://github.com/lib4u/fake-useragent) — Up-to-date simple useragent faker with real world database in Golang ☆`16`

### Servers

*   [caddyserver/caddy (⭐73k)](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`73,149`
*   [pocketbase/pocketbase (⭐59k)](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`58,886`
*   [etcd-io/etcd (⭐52k)](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`51,769`
*   [drakkan/sftpgo (⭐12k)](https://github.com/drakkan/sftpgo) — Full-featured SFTP/FTP/HTTP server ☆`12,127`
*   [adnanh/webhook (⭐12k)](https://github.com/adnanh/webhook) — Lightweight webhook server ☆`11,865`
*   [roadrunner-server/roadrunner (⭐8.5k)](https://github.com/roadrunner-server/roadrunner) — High-performance PHP application server ☆`8,469`
*   [easegress-io/easegress (⭐5.9k)](https://github.com/easegress-io/easegress) — A Cloud Native traffic orchestration system ☆`5,870`
*   [charmbracelet/wish (⭐5.2k)](https://github.com/charmbracelet/wish) — Make SSH apps, just like that! ☆`5,252`
*   [flipt-io/flipt (⭐4.8k)](https://github.com/flipt-io/flipt) — Enterprise-ready, Git native feature management solution ☆`4,819`
*   [getfider/fider (⭐4.3k)](https://github.com/getfider/fider) — Open platform to collect and prioritize feedback ☆`4,343`
*   [xyproto/algernon (⭐3k)](https://github.com/xyproto/algernon) — Web server with Lua and Markdown ☆`3,011`
*   [openflagr/flagr (⭐2.6k)](https://github.com/openflagr/flagr) — Feature flagging and A/B testing ☆`2,593`
*   [thomaspoignant/go-feature-flag (⭐2k)](https://github.com/thomaspoignant/go-feature-flag) — Open source feature flag solution ☆`2,029`
*   [msoap/shell2http (⭐1.5k)](https://github.com/msoap/shell2http) — Executing shell commands via HTTP server ☆`1,491`
*   [openrundev/openrun (⭐838)](https://github.com/openrundev/openrun) — Open source Cloud Run alternative ☆`842`
*   [webhookx-io/webhookx (⭐294)](https://github.com/webhookx-io/webhookx) — The Next-Generation Webhooks Gateway. ☆`296`
*   [blind-oracle/cortex-tenant (⭐138)](https://github.com/blind-oracle/cortex-tenant) — Prometheus proxy with tenant ID injection ☆`138`
*   [baalimago/wd-41 (⭐151)](https://github.com/baalimago/wd-41) — Web-Development 41, a static web server with live-reload ☆`151`
*   [42atomys/webhooked (⭐43)](https://github.com/42atomys/webhooked) — A webhook receiver on steroids. ☆`43`

### Network Utilities

*   [fortio/fortio (⭐3.7k)](https://github.com/fortio/fortio) — Load testing and echo server ☆`3,698`
*   [hashicorp/go-getter (⭐1.8k)](https://github.com/hashicorp/go-getter) — Download files from URLs ☆`1,820`
*   [TimothyYe/godns (⭐1.7k)](https://github.com/TimothyYe/godns) — Dynamic DNS client for multiple providers ☆`1,744`
*   [schollz/peerdiscovery (⭐669)](https://github.com/schollz/peerdiscovery) — Cross-platform local peer discovery ☆`669`
*   [fclairamb/ftpserverlib (⭐469)](https://github.com/fclairamb/ftpserverlib) — FTP server library for Go ☆`469`
*   [skibish/ddns (⭐266)](https://github.com/skibish/ddns) — Personal DDNS client with Digital Ocean Networking DNS as backend. ☆`266`
*   [assafmo/joincap (⭐220)](https://github.com/assafmo/joincap) — Merge pcap files ☆`220`
*   [gaissmai/bart (⭐139)](https://github.com/gaissmai/bart) — Balanced routing table ☆`141`
*   [alegrey91/fwdctl (⭐72)](https://github.com/alegrey91/fwdctl) — Manage IPTables forwards via CLI ☆`72`

### P2P & Torrent

*   [anacrolix/torrent (⭐6k)](https://github.com/anacrolix/torrent) — Full-featured BitTorrent client package and utilities ☆`6,033`
*   [dragonflyoss/dragonfly (⭐3.2k)](https://github.com/dragonflyoss/dragonfly) — P2P-based container image distribution ☆`3,186`
*   [cenkalti/rain (⭐1.1k)](https://github.com/cenkalti/rain) — BitTorrent client and library in Go ☆`1,134`
*   [anacrolix/dht (⭐355)](https://github.com/anacrolix/dht) — DHT for BitTorrent ☆`355`

### Protocols

*   [pion/webrtc (⭐16k)](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,519`
*   [quic-go/quic-go (⭐12k)](https://github.com/quic-go/quic-go) — A production-ready QUIC implementation in pure Go ☆`11,624`
*   [google/gopacket (⭐6.8k)](https://github.com/google/gopacket) — Provides packet processing capabilities for Go ☆`6,776`
*   [osrg/gobgp (⭐4.1k)](https://github.com/osrg/gobgp) — BGP implemented in the Go Programming Language ☆`4,061`
*   [lxzan/gws (⭐1.8k)](https://github.com/lxzan/gws) — Fast websocket server and client ☆`1,778`
*   [gosnmp/gosnmp (⭐1.2k)](https://github.com/gosnmp/gosnmp) — An SNMP library written in Go ☆`1,244`
*   [bluenviron/gortsplib (⭐917)](https://github.com/bluenviron/gortsplib) — RTSP client and server library for the Go programming language ☆`918`
*   [ccding/go-stun (⭐719)](https://github.com/ccding/go-stun) — A go implementation of the STUN client (RFC 3489 and RFC 5389) ☆`719`
*   [google/gnxi (⭐286)](https://github.com/google/gnxi) — gNXI Tools - gRPC Network Management/Operations Interface Tools ☆`285`
*   [jeroenrinzema/psql-wire (⭐235)](https://github.com/jeroenrinzema/psql-wire) — PostgreSQL wire protocol for Go ☆`235`
*   [jimlambrt/gldap (⭐120)](https://github.com/jimlambrt/gldap) — Build LDAP services w/ Go ☆`120`
*   [soypat/natiu-mqtt (⭐105)](https://github.com/soypat/natiu-mqtt) — Extensible MQTT for embedded systems ☆`105`

### RPC

*   [grpc/grpc-go (⭐23k)](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,947`
*   [lesismal/arpc (⭐1.1k)](https://github.com/lesismal/arpc) — Two-way RPC with broadcast support ☆`1,087`
*   [ybbus/jsonrpc (⭐370)](https://github.com/ybbus/jsonrpc) — A simple go implementation of json rpc 2.0 client over http ☆`370`
*   [osamingo/jsonrpc (⭐193)](https://github.com/osamingo/jsonrpc) — The jsonrpc package helps implement of JSON-RPC 2.0 ☆`193`

### SSH & SFTP

*   [gliderlabs/ssh (⭐4.1k)](https://github.com/gliderlabs/ssh) — Easy SSH servers in Golang ☆`4,141`
*   [pkg/sftp (⭐1.6k)](https://github.com/pkg/sftp) — SFTP support for the go.crypto/ssh package ☆`1,649`
*   [masterzen/winrm (⭐467)](https://github.com/masterzen/winrm) — Windows remote command library ☆`467`

### TCP/UDP Frameworks

*   [panjf2000/gnet (⭐11k)](https://github.com/panjf2000/gnet) — High-performance event-loop network ☆`11,164`
*   [cloudwego/netpoll (⭐4.6k)](https://github.com/cloudwego/netpoll) — High-performance I/O framework ☆`4,573`
*   [xtaci/kcp-go (⭐4.5k)](https://github.com/xtaci/kcp-go) — A crypto-secure Reliable-UDP library for Golang with FEC support. ☆`4,502`
*   [lesismal/nbio (⭐2.7k)](https://github.com/lesismal/nbio) — High-performance network library ☆`2,738`
*   [xtaci/gaio (⭐928)](https://github.com/xtaci/gaio) — High-performance, minimalist async-io (proactor) networking for Golang. ☆`928`
*   [cheng-zhongliang/event (⭐119)](https://github.com/cheng-zhongliang/event) — Simple I/O event notification library wirtten in Golang ☆`119`
*   [fish-tennis/gnet (⭐26)](https://github.com/fish-tennis/gnet) — high performance net library for game server ☆`26`

### VPN & Tunneling

*   [cloudflare/cloudflared (⭐14k)](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`14,420`
*   [xjasonlyu/tun2socks (⭐5.2k)](https://github.com/xjasonlyu/tun2socks) — TUN to SOCKS proxy ☆`5,244`
*   [songgao/water (⭐2.2k)](https://github.com/songgao/water) — A simple TUN/TAP library written in native Go. ☆`2,160`
*   [NodePassProject/nodepass (⭐2.1k)](https://github.com/NodePassProject/nodepass) — Secure TCP/UDP tunneling with TLS ☆`2,121`

## Queues & Pub/Sub

### Brokers

*   [nats-io/nats-server (⭐20k)](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`19,953`
*   [emitter-io/emitter (⭐4k)](https://github.com/emitter-io/emitter) — High-performance pub/sub broker ☆`4,003`
*   [mochi-mqtt/server (⭐1.9k)](https://github.com/mochi-mqtt/server) — Embeddable MQTT v5 broker ☆`1,872`

### Clients & Libraries

*   [hibiken/asynq (⭐13k)](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`13,338`
*   [IBM/sarama (⭐12k)](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,487`
*   [centrifugal/centrifugo (⭐10k)](https://github.com/centrifugal/centrifugo) — Scalable real-time messaging server ☆`10,338`
*   [ThreeDotsLabs/watermill (⭐9.7k)](https://github.com/ThreeDotsLabs/watermill) — Building event-driven applications the easy way in Go. ☆`9,745`
*   [appleboy/gorush (⭐8.7k)](https://github.com/appleboy/gorush) — A push notification server written in Go (Golang). ☆`8,736`
*   [RichardKnop/machinery (⭐8k)](https://github.com/RichardKnop/machinery) — Async task queue with message passing ☆`7,956`
*   [nats-io/nats.go (⭐6.6k)](https://github.com/nats-io/nats.go) — Golang client for NATS, the cloud native messaging system. ☆`6,630`
*   [dunglas/mercure (⭐5.2k)](https://github.com/dunglas/mercure) — Server-Sent Events hub ☆`5,253`
*   [confluentinc/confluent-kafka-go (⭐5.1k)](https://github.com/confluentinc/confluent-kafka-go) — Confluent's Apache Kafka Golang client ☆`5,141`
*   [olahol/melody (⭐4.1k)](https://github.com/olahol/melody) — Minimalist websocket framework for Go ☆`4,078`
*   [sideshow/apns2 (⭐3.2k)](https://github.com/sideshow/apns2) — Apple Push Notification Service ☆`3,176`
*   [lovoo/goka (⭐2.5k)](https://github.com/lovoo/goka) — Kafka stream processing library ☆`2,531`
*   [rabbitmq/amqp091-go (⭐2k)](https://github.com/rabbitmq/amqp091-go) — An AMQP 0-9-1 Go client maintained by the RabbitMQ team ☆`2,004`
*   [asaskevich/EventBus (⭐2k)](https://github.com/asaskevich/EventBus) — \[Go] Lightweight eventbus with async compatibility for Go ☆`1,975`
*   [containrrr/shoutrrr (⭐1.6k)](https://github.com/containrrr/shoutrrr) — Notification library for gophers and their furry friends. ☆`1,591`
*   [pebbe/zmq4 (⭐1.3k)](https://github.com/pebbe/zmq4) — A Go interface to ZeroMQ version 4 ☆`1,256`
*   [timbray/quamina (⭐491)](https://github.com/timbray/quamina) — Fast pattern-matching library ☆`493`
*   [jandelgado/rabtap (⭐281)](https://github.com/jandelgado/rabtap) — RabbitMQ wire tap and swiss army knife ☆`281`
*   [mehdihadeli/Go-MediatR (⭐276)](https://github.com/mehdihadeli/Go-MediatR) — Mediator pattern for CQRS ☆`277`
*   [goptics/varmq (⭐185)](https://github.com/goptics/varmq) — Zero-dep message queue library ☆`186`
*   [oagudo/outbox (⭐128)](https://github.com/oagudo/outbox) — Transactional outbox pattern ☆`128`
*   [hyperonym/ratus (⭐123)](https://github.com/hyperonym/ratus) — RESTful async task queue server ☆`123`
*   [dailymotion/oplog (⭐111)](https://github.com/dailymotion/oplog) — A generic oplog/replication system for microservices ☆`111`
*   [jirenius/go-res (⭐68)](https://github.com/jirenius/go-res) — RES Service protocol library for Go ☆`68`
*   [Protocol-Lattice/GoEventBus (⭐65)](https://github.com/Protocol-Lattice/GoEventBus) — A lock-free, ultra-fast event bus for Go ☆`65`
*   [SchwarzDigits/hypermatch (⭐34)](https://github.com/SchwarzDigits/hypermatch) — High-performance rule matching ☆`34`

## Science

*   [gonum/gonum (⭐8.4k)](https://github.com/gonum/gonum) — Numeric libraries for Go ☆`8,381`
*   [gonum/plot (⭐3k)](https://github.com/gonum/plot) — Plotting and visualization ☆`2,956`
*   [paulmach/orb (⭐1.1k)](https://github.com/paulmach/orb) — 2D geometry types and utilities ☆`1,115`
*   [madelynnblue/go-dsp (⭐912)](https://github.com/madelynnblue/go-dsp) — Digital Signal Processing for Go ☆`912`
*   [bebop/poly (⭐727)](https://github.com/bebop/poly) — Synthetic biology library for Go ☆`729`
*   [hmdsefi/gograph (⭐115)](https://github.com/hmdsefi/gograph) — Generic graph algorithms library ☆`115`
*   [nikolaydubina/jsonl-graph (⭐78)](https://github.com/nikolaydubina/jsonl-graph) — JSONL Graph Tools ☆`78`
*   [claygod/PiHex (⭐20)](https://github.com/claygod/PiHex) — Generate hexadecimal Pi digits ☆`20`

## Scripting

### Embeddable Languages

*   [php/frankenphp (⭐11k)](https://github.com/php/frankenphp) — The modern PHP app server ☆`11,122`
*   [expr-lang/expr (⭐7.9k)](https://github.com/expr-lang/expr) — Expression evaluation for Go ☆`7,884`
*   [yuin/gopher-lua (⭐6.9k)](https://github.com/yuin/gopher-lua) — Lua VM and compiler in Go ☆`6,927`
*   [dop251/goja (⭐6.9k)](https://github.com/dop251/goja) — ECMAScript engine in pure Go ☆`6,894`
*   [d5/tengo (⭐3.8k)](https://github.com/d5/tengo) — Fast script language for Go ☆`3,817`
*   [Shopify/go-lua (⭐3.4k)](https://github.com/Shopify/go-lua) — Lua VM in Go ☆`3,442`
*   [google/cel-go (⭐3k)](https://github.com/google/cel-go) — Common Expression Language for Go ☆`2,988`
*   [google/starlark-go (⭐2.7k)](https://github.com/google/starlark-go) — Starlark config language in Go ☆`2,707`
*   [metacall/core (⭐1.8k)](https://github.com/metacall/core) — Polyglot programming runtime ☆`1,803`
*   [wa-lang/wa (⭐1.8k)](https://github.com/wa-lang/wa) — The Wa Programming Language ☆`1,768`
*   [mattn/anko (⭐1.6k)](https://github.com/mattn/anko) — Scriptable interpreter in Go ☆`1,569`
*   [PaesslerAG/gval (⭐811)](https://github.com/PaesslerAG/gval) — Expression evaluation in Go ☆`811`
*   [ichiban/prolog (⭐724)](https://github.com/ichiban/prolog) — Prolog scripting engine for Go ☆`724`
*   [aarzilli/golua (⭐697)](https://github.com/aarzilli/golua) — Lua C API bindings for Go ☆`699`
*   [1set/starlet (⭐43)](https://github.com/1set/starlet) — Starlark wrapper with batteries ☆`43`

### Code Generators

*   [oapi-codegen/oapi-codegen (⭐8.4k)](https://github.com/oapi-codegen/oapi-codegen) — Generate Go code from OpenAPI 3 specs ☆`8,370`
*   [dave/jennifer (⭐3.6k)](https://github.com/dave/jennifer) — Code generator for Go ☆`3,618`
*   [hexdigest/gowrap (⭐1.3k)](https://github.com/hexdigest/gowrap) — Generate interface decorators ☆`1,326`
*   [awalterschulze/goderive (⭐1.3k)](https://github.com/awalterschulze/goderive) — Generate mundane Go functions ☆`1,263`
*   [abice/go-enum (⭐945)](https://github.com/abice/go-enum) — Enum generator for Go ☆`947`
*   [jmattheis/goverter (⭐852)](https://github.com/jmattheis/goverter) — Generate type-safe converters ☆`853`
*   [rjeczalik/interfaces (⭐431)](https://github.com/rjeczalik/interfaces) — Code generation tools for Go ☆`431`
*   [switchupcb/copygen (⭐403)](https://github.com/switchupcb/copygen) — Copy values between types ☆`403`
*   [reedom/convergen (⭐50)](https://github.com/reedom/convergen) — Type-to-type copy code generator ☆`50`

## Security

### Certificates

*   [go-acme/lego (⭐9.6k)](https://github.com/go-acme/lego) — Let's Encrypt/ACME client and library written in Go ☆`9,646`
*   [caddyserver/certmagic (⭐5.6k)](https://github.com/caddyserver/certmagic) — Automatic HTTPS certificate management ☆`5,562`
*   [tg123/go-htpasswd (⭐47)](https://github.com/tg123/go-htpasswd) — Apache htpasswd Parser for Go. ☆`47`
*   [adrianosela/sslmgr (⭐32)](https://github.com/adrianosela/sslmgr) — SSL certificate abstraction ☆`32`

### Cryptography

*   [FiloSottile/age (⭐22k)](https://github.com/FiloSottile/age) — Simple encryption tool ☆`22,482`
*   [authzed/spicedb (⭐6.7k)](https://github.com/authzed/spicedb) — Zanzibar-inspired permissions DB ☆`6,757`
*   [awnumar/memguard (⭐2.7k)](https://github.com/awnumar/memguard) — Software sandbox for storage of sensitive information in memory. ☆`2,746`
*   [cossacklabs/themis (⭐2k)](https://github.com/cossacklabs/themis) — Cryptographic framework for data protection ☆`1,966`
*   [dromara/dongle (⭐1.1k)](https://github.com/dromara/dongle) — A simple, semantic and developer-friendly crypto package for golang ☆`1,106`
*   [anatol/booster (⭐634)](https://github.com/anatol/booster) — Fast and secure initramfs generator ☆`641`
*   [kevinburke/nacl (⭐552)](https://github.com/kevinburke/nacl) — Pure Go implementation of the NaCL set of API's ☆`552`
*   [ssh-vault/ssh-vault (⭐505)](https://github.com/ssh-vault/ssh-vault) — encrypt/decrypt using ssh keys ☆`505`
*   [number571/go-peer (⭐325)](https://github.com/number571/go-peer) — Secure decentralized networking ☆`325`
*   [lingrino/vaku (⭐159)](https://github.com/lingrino/vaku) — Extended Vault API and CLI ☆`159`
*   [anatol/luks.go (⭐97)](https://github.com/anatol/luks.go) — Pure Golang library to manage LUKS partitions ☆`97`
*   [zitadel/passwap (⭐75)](https://github.com/zitadel/passwap) — Unified password hashing ☆`75`
*   [rsjethani/secret (⭐33)](https://github.com/rsjethani/secret) — Prevent your secrets from leaking into logs, std\* etc. ☆`33`
*   [andskur/argon2-hashing (⭐25)](https://github.com/andskur/argon2-hashing) — Argon2 password hashing ☆`25`

### WAF & Protection

*   [Ullaakut/cameradar (⭐5k)](https://github.com/Ullaakut/cameradar) — Cameradar hacks its way into RTSP videosurveillance cameras ☆`5,059`
*   [corazawaf/coraza (⭐3.5k)](https://github.com/corazawaf/coraza) — ModSecurity-compatible WAF in Go ☆`3,532`
*   [mojocn/base64Captcha (⭐2.4k)](https://github.com/mojocn/base64Captcha) — captcha of base64 image string ☆`2,362`
*   [unrolled/secure (⭐2.3k)](https://github.com/unrolled/secure) — HTTP middleware for Go that facilitates some quick security wins. ☆`2,344`
*   [beelzebub-labs/beelzebub (⭐2k)](https://github.com/beelzebub-labs/beelzebub) — AI-powered honeypot framework ☆`2,031`
*   [cossacklabs/acra (⭐1.5k)](https://github.com/cossacklabs/acra) — Database security proxy ☆`1,481`
*   [securitybunker/databunker (⭐1.4k)](https://github.com/securitybunker/databunker) — Secure vault for PII/PHI/KYC records ☆`1,422`
*   [hillu/go-yara (⭐388)](https://github.com/hillu/go-yara) — Go bindings for YARA ☆`388`
*   [teler-sh/teler-waf (⭐402)](https://github.com/teler-sh/teler-waf) — HTTP middleware for WAF ☆`401`
*   [steambap/captcha (⭐163)](https://github.com/steambap/captcha) — Easy captcha library ☆`164`

### Zero Trust

*   [sigstore/cosign (⭐6k)](https://github.com/sigstore/cosign) — Code signing and transparency for containers and binaries ☆`5,999`
*   [openziti/ziti (⭐4.2k)](https://github.com/openziti/ziti) — Zero trust networking platform ☆`4,199`
*   [spiffe/spire (⭐2.4k)](https://github.com/spiffe/spire) — The SPIFFE Runtime Environment ☆`2,381`
*   [philips-labs/spiffe-vault (⭐99)](https://github.com/philips-labs/spiffe-vault) — Integrates Spiffe and Vault to have secretless authentication ☆`99`

## Testing & Quality

### Benchmarks

*   [smallnest/go-web-framework-benchmark (⭐2.1k)](https://github.com/smallnest/go-web-framework-benchmark) — Web framework benchmarks ☆`2,139`
*   [alecthomas/go\_serialization\_benchmarks (⭐1.6k)](https://github.com/alecthomas/go_serialization_benchmarks) — Serialization benchmarks for Go ☆`1,627`
*   [SimonWaldherr/golang-benchmarks (⭐145)](https://github.com/SimonWaldherr/golang-benchmarks) — Go(lang) benchmarks - (measure the speed of golang) ☆`144`
*   [nikolaydubina/go-ml-benchmarks (⭐33)](https://github.com/nikolaydubina/go-ml-benchmarks) — Benchmarks of machine learning inference for Go ☆`33`

### Code Analysis

*   [golangci/golangci-lint (⭐19k)](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`19,039`
*   [boyter/scc (⭐8.4k)](https://github.com/boyter/scc) — Fast code counter and stats ☆`8,440`
*   [mgechev/revive (⭐5.5k)](https://github.com/mgechev/revive) — Fast, extensible Go linter ☆`5,515`
*   [kisielk/errcheck (⭐2.5k)](https://github.com/kisielk/errcheck) — errcheck checks that you checked errors. ☆`2,514`
*   [go-critic/go-critic (⭐2k)](https://github.com/go-critic/go-critic) — The most opinionated Go source code linter for code audit. ☆`2,052`
*   [daveshanley/vacuum (⭐1.1k)](https://github.com/daveshanley/vacuum) — Fast OpenAPI linter ☆`1,073`
*   [presmihaylov/todocheck (⭐437)](https://github.com/presmihaylov/todocheck) — Analyser for TODO comments ☆`436`
*   [mdempsky/unconvert (⭐387)](https://github.com/mdempsky/unconvert) — Remove unnecessary type conversions ☆`388`
*   [tomarrell/wrapcheck (⭐374)](https://github.com/tomarrell/wrapcheck) — Check errors are wrapped ☆`373`
*   [mibk/dupl (⭐368)](https://github.com/mibk/dupl) — Code clone detection tool ☆`369`
*   [shurcooL/gostatus (⭐245)](https://github.com/shurcooL/gostatus) — Show status of Go repositories ☆`245`
*   [Antonboom/testifylint (⭐169)](https://github.com/Antonboom/testifylint) — Linter for testify usage ☆`169`
*   [Crocmagnon/fatcontext (⭐76)](https://github.com/Crocmagnon/fatcontext) — Detect nested contexts in loops ☆`76`
*   [antham/ghokin (⭐53)](https://github.com/antham/ghokin) — Parallelized Gherkin formatter ☆`53`
*   [sashamelentyev/usestdlibvars (⭐48)](https://github.com/sashamelentyev/usestdlibvars) — Linter for stdlib variables usage ☆`48`
*   [borovikovd/gomsort (⭐26)](https://github.com/borovikovd/gomsort) — Go msort - linter that sorts methods ☆`25`

### Mock

*   [vektra/mockery (⭐7.1k)](https://github.com/vektra/mockery) — Mock code autogenerator for Go ☆`7,123`
*   [DATA-DOG/go-sqlmock (⭐6.6k)](https://github.com/DATA-DOG/go-sqlmock) — SQL mock driver for testing ☆`6,553`
*   [brianvoe/gofakeit (⭐5.4k)](https://github.com/brianvoe/gofakeit) — Random fake data generator written in go ☆`5,359`
*   [uber-go/mock (⭐3.4k)](https://github.com/uber-go/mock) — GoMock is a mocking framework for the Go programming language. ☆`3,358`
*   [SpectoLabs/hoverfly (⭐2.5k)](https://github.com/SpectoLabs/hoverfly) — API simulation and virtualization ☆`2,496`
*   [matryer/moq (⭐2.2k)](https://github.com/matryer/moq) — Interface mocking via go generate ☆`2,200`
*   [jarcoal/httpmock (⭐2.1k)](https://github.com/jarcoal/httpmock) — HTTP mocking for Go ☆`2,078`
*   [maxbrunsfeld/counterfeiter (⭐1.1k)](https://github.com/maxbrunsfeld/counterfeiter) — Generate type-safe test doubles ☆`1,133`
*   [gojuno/minimock (⭐750)](https://github.com/gojuno/minimock) — Powerful mock generator ☆`751`
*   [DATA-DOG/go-txdb (⭐751)](https://github.com/DATA-DOG/go-txdb) — Transaction-isolated SQL driver ☆`751`
*   [pashagolub/pgxmock (⭐584)](https://github.com/pashagolub/pgxmock) — pgx mock driver for testing ☆`586`
*   [xhd2015/xgo (⭐433)](https://github.com/xhd2015/xgo) — All-in-one Go testing library ☆`431`
*   [seborama/govcr (⭐199)](https://github.com/seborama/govcr) — Record and replay HTTP interactions ☆`199`
*   [mocktools/go-smtp-mock (⭐164)](https://github.com/mocktools/go-smtp-mock) — SMTP mock server for testing ☆`164`
*   [elgohr/go-localstack (⭐87)](https://github.com/elgohr/go-localstack) — Go wrapper for LocalStack ☆`87`

### Performance

*   [jaegertracing/jaeger (⭐23k)](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`22,858`
*   [pixie-io/pixie (⭐6.5k)](https://github.com/pixie-io/pixie) — Kubernetes-native observability ☆`6,460`
*   [arl/statsviz (⭐3.6k)](https://github.com/arl/statsviz) — Visualize Go runtime metrics ☆`3,636`
*   [nikolaydubina/go-instrument (⭐295)](https://github.com/nikolaydubina/go-instrument) — Add trace spans to Go functions ☆`295`
*   [joetifa2003/mm-go (⭐194)](https://github.com/joetifa2003/mm-go) — Manual memory management for Go ☆`194`

### Browser Automation

*   [chromedp/chromedp (⭐13k)](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`13,095`
*   [go-rod/rod (⭐6.9k)](https://github.com/go-rod/rod) — Chrome DevTools driver for scraping ☆`6,964`
*   [sensepost/gowitness (⭐4.3k)](https://github.com/sensepost/gowitness) — Web screenshot utility with Chrome ☆`4,317`
*   [playwright-community/playwright-go (⭐3.4k)](https://github.com/playwright-community/playwright-go) — Browser automation for Chromium, Firefox, WebKit ☆`3,366`
*   [mafredri/cdp (⭐790)](https://github.com/mafredri/cdp) — Chrome DevTools Protocol bindings ☆`791`

### Testing Frameworks

*   [stretchr/testify (⭐26k)](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`26,008`
*   [keploy/keploy (⭐17k)](https://github.com/keploy/keploy) — API testing with auto mocks ☆`17,594`
*   [Shopify/toxiproxy (⭐12k)](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`12,065`
*   [testcontainers/testcontainers-go (⭐4.9k)](https://github.com/testcontainers/testcontainers-go) — Docker containers for integration tests ☆`4,865`
*   [google/go-cmp (⭐4.6k)](https://github.com/google/go-cmp) — Package for comparing Go values in tests ☆`4,639`
*   [gavv/httpexpect (⭐2.7k)](https://github.com/gavv/httpexpect) — End-to-end HTTP and REST API testing for Go. ☆`2,720`
*   [cucumber/godog (⭐2.6k)](https://github.com/cucumber/godog) — Cucumber for golang ☆`2,628`
*   [orlangure/gnomock (⭐1.5k)](https://github.com/orlangure/gnomock) — Test with ephemeral Docker containers ☆`1,488`
*   [dnaeon/go-vcr (⭐1.4k)](https://github.com/dnaeon/go-vcr) — Record and replay HTTP for tests ☆`1,385`
*   [go-testfixtures/testfixtures (⭐1.2k)](https://github.com/go-testfixtures/testfixtures) — Rails-like test fixtures for Go ☆`1,232`
*   [fergusstrange/embedded-postgres (⭐1.2k)](https://github.com/fergusstrange/embedded-postgres) — Embedded PostgreSQL for testing ☆`1,186`
*   [chapar-rest/chapar (⭐702)](https://github.com/chapar-rest/chapar) — API testing for HTTP and gRPC ☆`702`
*   [gotestyourself/gotest.tools (⭐577)](https://github.com/gotestyourself/gotest.tools) — Testing utilities for Go ☆`577`
*   [maxatome/go-testdeep (⭐462)](https://github.com/maxatome/go-testdeep) — Flexible deep comparison in tests ☆`463`
*   [appleboy/gofight (⭐444)](https://github.com/appleboy/gofight) — Testing API Handler written in Golang. ☆`445`
*   [viant/endly (⭐267)](https://github.com/viant/endly) — End to end functional test and automation framework ☆`267`
*   [ysmood/got (⭐266)](https://github.com/ysmood/got) — An enjoyable golang test framework. ☆`266`
*   [adamluzsi/testcase (⭐130)](https://github.com/adamluzsi/testcase) — Opinionated testing framework ☆`130`
*   [kinbiko/jsonassert (⭐141)](https://github.com/kinbiko/jsonassert) — JSON assertion library for tests ☆`141`
*   [earthboundkid/be (⭐133)](https://github.com/earthboundkid/be) — The Go test helper for minimalists ☆`133`
*   [corbym/gocrest (⭐107)](https://github.com/corbym/gocrest) — GoCrest - Hamcrest-like matchers for Go ☆`107`
*   [madflojo/testcerts (⭐84)](https://github.com/madflojo/testcerts) — Generate test certificates on the fly ☆`85`
*   [hedhyw/gherkingen (⭐96)](https://github.com/hedhyw/gherkingen) — Behaviour Driven Development tests generator for Golang ☆`96`
*   [viant/dsunit (⭐45)](https://github.com/viant/dsunit) — Datastore Testibility ☆`45`
*   [go-restit/restit (⭐55)](https://github.com/go-restit/restit) — A Go library help testing your RESTful API application ☆`55`
*   [rekby/fixenv (⭐33)](https://github.com/rekby/fixenv) — Pytest-inspired fixture caching for Go tests ☆`33`
*   [abecodes/dft (⭐19)](https://github.com/abecodes/dft) — Docker wrapper for testing ☆`19`

### Testing Utilities

*   [dvyukov/go-fuzz (⭐4.8k)](https://github.com/dvyukov/go-fuzz) — Randomized testing for Go ☆`4,852`
*   [pingcap/failpoint (⭐885)](https://github.com/pingcap/failpoint) — Failpoint implementation for Go ☆`886`

### Validation

*   [go-playground/validator (⭐20k)](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`19,994`
*   [Oudwins/zog (⭐1.2k)](https://github.com/Oudwins/zog) — Zod-inspired schema validation ☆`1,189`
*   [gookit/validate (⭐1.1k)](https://github.com/gookit/validate) — Struct and data validation ☆`1,127`
*   [twharmon/govalid (⭐115)](https://github.com/twharmon/govalid) — Struct validation using tags ☆`115`
*   [faceair/jio (⭐126)](https://github.com/faceair/jio) — JSON schema validator like Joi ☆`126`
*   [osamingo/checkdigit (⭐114)](https://github.com/osamingo/checkdigit) — Check digit algorithms ☆`114`
*   [marrow16/valix (⭐31)](https://github.com/marrow16/valix) — Request validation package ☆`31`
*   [tiendc/go-validator (⭐31)](https://github.com/tiendc/go-validator) — Intuitive validation library ☆`31`

## Text & NLP

### Formatters

*   [dustin/go-humanize (⭐4.8k)](https://github.com/dustin/go-humanize) — Human-friendly unit formatting ☆`4,796`
*   [neilotoole/sq (⭐2.5k)](https://github.com/neilotoole/sq) — SQL data wrangler ☆`2,518`
*   [bojanz/address (⭐82)](https://github.com/bojanz/address) — Address handling for Go ☆`82`

### Markup Languages

*   [BurntSushi/toml (⭐5k)](https://github.com/BurntSushi/toml) — TOML parser with reflection ☆`4,961`
*   [yuin/goldmark (⭐4.8k)](https://github.com/yuin/goldmark) — Markdown parser for Go ☆`4,827`
*   [JohannesKaufmann/html-to-markdown (⭐3.7k)](https://github.com/JohannesKaufmann/html-to-markdown) — Convert HTML to Markdown ☆`3,672`
*   [pelletier/go-toml (⭐1.9k)](https://github.com/pelletier/go-toml) — TOML library for Go ☆`1,942`
*   [antchfx/htmlquery (⭐783)](https://github.com/antchfx/htmlquery) — XPath for HTML queries ☆`784`
*   [clbanning/mxj (⭐630)](https://github.com/clbanning/mxj) — XML to/from map conversion ☆`630`
*   [mmalcek/bafi (⭐114)](https://github.com/mmalcek/bafi) — Universal format converter ☆`114`

### Miscellaneous

*   [microcosm-cc/bluemonday (⭐3.7k)](https://github.com/microcosm-cc/bluemonday) — Fast HTML sanitizer for Go ☆`3,682`
*   [pemistahl/lingua-go (⭐1.3k)](https://github.com/pemistahl/lingua-go) — Natural language detection ☆`1,344`
*   [gosimple/slug (⭐1.3k)](https://github.com/gosimple/slug) — URL-friendly slugify ☆`1,329`
*   [arunsupe/semantic-grep (⭐1.2k)](https://github.com/arunsupe/semantic-grep) — Grep for similar words ☆`1,225`
*   [mattn/go-runewidth (⭐699)](https://github.com/mattn/go-runewidth) — Rune width for terminals ☆`702`
*   [hedhyw/rex (⭐211)](https://github.com/hedhyw/rex) — Flexible regex constructor ☆`212`
*   [IGLOU-EU/go-wildcard (⭐101)](https://github.com/IGLOU-EU/go-wildcard) — Fast wildcard matching ☆`102`
*   [JoshuaDoes/gofuckyourself (⭐70)](https://github.com/JoshuaDoes/gofuckyourself) — Swear filter for Go ☆`70`
*   [alexsergivan/transliterator (⭐46)](https://github.com/alexsergivan/transliterator) — Text transliterator ☆`46`

### Morphological Analyzers

*   [nlpodyssey/spago (⭐1.9k)](https://github.com/nlpodyssey/spago) — ML and NLP library for Go ☆`1,851`
*   [ikawaha/kagome (⭐964)](https://github.com/ikawaha/kagome) — Japanese morphological analyzer ☆`965`
*   [afjoseph/RAKE.Go (⭐123)](https://github.com/afjoseph/RAKE.Go) — Rapid Keyword Extraction in Go ☆`123`
*   [jonreiter/govader (⭐54)](https://github.com/jonreiter/govader) — VADER sentiment analysis ☆`54`

### Parsers/Encoders/Decoders

*   [mvdan/sh (⭐8.8k)](https://github.com/mvdan/sh) — Shell parser and formatter ☆`8,795`
*   [mmcdole/gofeed (⭐2.8k)](https://github.com/mmcdole/gofeed) — Parse RSS, Atom, JSON feeds ☆`2,838`
*   [google/go-querystring (⭐2.1k)](https://github.com/google/go-querystring) — Encode structs to URL query strings ☆`2,138`
*   [olebedev/when (⭐1.5k)](https://github.com/olebedev/when) — Natural language date parser ☆`1,461`
*   [adrianmo/go-nmea (⭐262)](https://github.com/adrianmo/go-nmea) — NMEA sentence parser ☆`263`
*   [yassinebenaid/godump (⭐221)](https://github.com/yassinebenaid/godump) — Dump any Go variable ☆`222`
*   [editorconfig/editorconfig-core-go (⭐154)](https://github.com/editorconfig/editorconfig-core-go) — EditorConfig core in Go ☆`154`
*   [bzick/tokenizer (⭐139)](https://github.com/bzick/tokenizer) — Tokenizer/lexer for Go ☆`139`
*   [emersion/go-vcard (⭐126)](https://github.com/emersion/go-vcard) — vCard parser and formatter ☆`126`
*   [polera/gonameparts (⭐43)](https://github.com/polera/gonameparts) — Takes a full name and splits it into individual name parts ☆`43`

### Scrapers

*   [gocolly/colly (⭐25k)](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,311`
*   [PuerkitoBio/goquery (⭐15k)](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,947`
*   [mvdan/xurls (⭐1.3k)](https://github.com/mvdan/xurls) — Extract URLs from text ☆`1,262`
*   [s0rg/crawley (⭐340)](https://github.com/s0rg/crawley) — The unix-way web crawler ☆`340`
*   [zoomio/tagify (⭐39)](https://github.com/zoomio/tagify) — Extract tags from HTML/Markdown/text ☆`39`

### Text Analysis

*   [blevesearch/bleve (⭐11k)](https://github.com/blevesearch/bleve) — Text/numeric/geo/vector indexing library ☆`11,088`
*   [derekparker/trie (⭐789)](https://github.com/derekparker/trie) — Trie for extremely fast prefix search ☆`789`
*   [agnivade/levenshtein (⭐470)](https://github.com/agnivade/levenshtein) — Go implementation to calculate Levenshtein Distance. ☆`470`
*   [plar/go-adaptive-radix-tree (⭐413)](https://github.com/plar/go-adaptive-radix-tree) — Adaptive Radix Trees implemented in Go ☆`413`

### Tokenizers

*   [go-ego/gse (⭐2.8k)](https://github.com/go-ego/gse) — Multilingual text segmentation ☆`2,829`
*   [pebbe/textcat (⭐73)](https://github.com/pebbe/textcat) — N-gram text categorization ☆`73`

### Translation

*   [nicksnyder/go-i18n (⭐3.5k)](https://github.com/nicksnyder/go-i18n) — Translate Go programs ☆`3,529`
*   [leonelquinteros/gotext (⭐498)](https://github.com/leonelquinteros/gotext) — GNU gettext for Go ☆`499`
*   [vorlif/spreak (⭐93)](https://github.com/vorlif/spreak) — Gettext-based translation library ☆`94`
*   [invopop/ctxi18n (⭐94)](https://github.com/invopop/ctxi18n) — Context-based i18n for Go ☆`94`
*   [mehanizm/iuliia-go (⭐56)](https://github.com/mehanizm/iuliia-go) — Cyrillic to Latin transliteration ☆`56`
*   [youthlin/t (⭐21)](https://github.com/youthlin/t) — Translation util using gettext ☆`21`

## Third-party APIs

### Cloud Provider APIs

*   [googleapis/google-cloud-go (⭐4.5k)](https://github.com/googleapis/google-cloud-go) — Google Cloud Client Libraries for Go. ☆`4,458`
*   [googleapis/google-api-go-client (⭐4.4k)](https://github.com/googleapis/google-api-go-client) — Auto-generated Google APIs for Go. ☆`4,440`
*   [aws/aws-sdk-go-v2 (⭐3.6k)](https://github.com/aws/aws-sdk-go-v2) — AWS SDK for the Go programming language. ☆`3,575`
*   [minio/minio-go (⭐2.9k)](https://github.com/minio/minio-go) — High-performance object storage ☆`2,950`
*   [rhnvrm/simples3 (⭐200)](https://github.com/rhnvrm/simples3) — Simple AWS S3 library using REST ☆`202`
*   [circa10a/go-aws-news (⭐18)](https://github.com/circa10a/go-aws-news) — Go app + library to fetch what's new from AWS ☆`18`
*   [chainifynet/aws-encryption-sdk-go (⭐22)](https://github.com/chainifynet/aws-encryption-sdk-go) — AWS Encryption SDK for Go ☆`22`

### Other APIs

*   [codingsince1985/geo-golang (⭐544)](https://github.com/codingsince1985/geo-golang) — Go library to access geocoding and reverse geocoding APIs ☆`544`
*   [cyruzin/golang-tmdb (⭐162)](https://github.com/cyruzin/golang-tmdb) — Wrapper for TMDb API ☆`161`
*   [gregdel/pushover (⭐155)](https://github.com/gregdel/pushover) — Go wrapper for the Pushover API ☆`155`
*   [mvrilo/go-redoc (⭐94)](https://github.com/mvrilo/go-redoc) — Embedded OpenAPI documentation ☆`94`
*   [rapito/go-spotify (⭐53)](https://github.com/rapito/go-spotify) — Go library for the Spotify Web API ☆`53`
*   [rinchsan/device-check-go (⭐25)](https://github.com/rinchsan/device-check-go) — iOS DeviceCheck SDK for Go ☆`25`
*   [sostronk/go-steam (⭐33)](https://github.com/sostronk/go-steam) — Go library for querying Source servers ☆`33`
*   [staskobzar/goami2 (⭐21)](https://github.com/staskobzar/goami2) — Simple Asterisk Manager Interface (AMI) library fo golang ☆`21`
*   [Icelain/jokeapi (⭐27)](https://github.com/Icelain/jokeapi) — Official golang wrapper for Sv443's jokeapi. ☆`27`

### Productivity APIs

*   [mk-5/fjira (⭐267)](https://github.com/mk-5/fjira) — The golang fuzzy-find cli jira interface ☆`267`
*   [adlio/trello (⭐227)](https://github.com/adlio/trello) — Trello API wrapper for Go ☆`227`
*   [ctreminiom/go-atlassian (⭐211)](https://github.com/ctreminiom/go-atlassian) — Atlassian Cloud API client ☆`211`
*   [koltyakov/gosip (⭐168)](https://github.com/koltyakov/gosip) — SharePoint SDK for Go ☆`168`
*   [FreeLeh/GoFreeDB (⭐90)](https://github.com/FreeLeh/GoFreeDB) — Database on top of Google Sheets ☆`90`
*   [mehanizm/airtable (⭐86)](https://github.com/mehanizm/airtable) — Simple golang airtable API wrapper ☆`86`
*   [k-capehart/go-salesforce (⭐55)](https://github.com/k-capehart/go-salesforce) — Salesforce REST API client ☆`55`

## Utilities

### Build & Release

*   [goreleaser/goreleaser (⭐16k)](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,844`
*   [create-go-app/cli (⭐2.8k)](https://github.com/create-go-app/cli) — Create production-ready Go projects ☆`2,758`
*   [miniscruff/changie (⭐878)](https://github.com/miniscruff/changie) — Automated changelog tool ☆`879`
*   [karl-cardenas-coding/go-lambda-cleanup (⭐96)](https://github.com/karl-cardenas-coding/go-lambda-cleanup) — Remove old AWS Lambda versions ☆`96`

### CLI Tools

*   [junegunn/fzf (⭐81k)](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`80,869`
*   [wagoodman/dive (⭐54k)](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`54,207`
*   [xo/usql (⭐10k)](https://github.com/xo/usql) — Universal SQL CLI ☆`9,973`
*   [minio/mc (⭐3.5k)](https://github.com/minio/mc) — Unix utilities for object stores ☆`3,485`
*   [joshmedeski/sesh (⭐2.5k)](https://github.com/joshmedeski/sesh) — Terminal session manager ☆`2,565`
*   [itchyny/bed (⭐1.3k)](https://github.com/itchyny/bed) — Binary editor in Go ☆`1,346`
*   [owenthereal/upterm (⭐1.2k)](https://github.com/owenthereal/upterm) — Instant terminal sharing ☆`1,227`
*   [alajmo/mani (⭐700)](https://github.com/alajmo/mani) — CLI for managing repositories ☆`705`
*   [Unrud/remote-touchpad (⭐662)](https://github.com/Unrud/remote-touchpad) — Control mouse/keyboard remotely ☆`663`
*   [chenquan/diskusage (⭐307)](https://github.com/chenquan/diskusage) — Fast disk usage analyzer ☆`308`
*   [reugn/wifiqr (⭐284)](https://github.com/reugn/wifiqr) — Generate Wi-Fi QR codes ☆`284`
*   [hedhyw/json-log-viewer (⭐222)](https://github.com/hedhyw/json-log-viewer) — Interactive JSON log viewer ☆`223`
*   [hrtsegv/gitcs (⭐132)](https://github.com/hrtsegv/gitcs) — Git contributions graph generator ☆`132`
*   [antham/yogo (⭐46)](https://github.com/antham/yogo) — Check yopmail from CLI ☆`46`

### Data Conversion

*   [samber/lo (⭐21k)](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`21,312`
*   [duke-git/lancet (⭐5.3k)](https://github.com/duke-git/lancet) — Comprehensive util library ☆`5,295`
*   [darccio/mergo (⭐3.1k)](https://github.com/darccio/mergo) — Merge Go structs and maps ☆`3,101`
*   [goforj/godump (⭐1.7k)](https://github.com/goforj/godump) — Pretty-printer for Go structs ☆`1,739`
*   [gookit/filter (⭐150)](https://github.com/gookit/filter) — Data filtering and conversion ☆`150`
*   [tiendc/gofn (⭐52)](https://github.com/tiendc/gofn) — High-performance generic functions ☆`52`
*   [xorcare/pointer (⭐47)](https://github.com/xorcare/pointer) — Create optional field pointers ☆`47`
*   [shockerli/cvt (⭐54)](https://github.com/shockerli/cvt) — Safe type conversion ☆`54`

### Database Extensions

*   [jmoiron/sqlx (⭐18k)](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,636`
*   [georgysavva/scany (⭐1.5k)](https://github.com/georgysavva/scany) — Scan database rows to structs ☆`1,516`
*   [blockloop/scan (⭐613)](https://github.com/blockloop/scan) — Scan SQL rows to structs ☆`613`

### Date and Time

*   [dromara/carbon (⭐5.2k)](https://github.com/dromara/carbon) — Developer-friendly time package ☆`5,221`
*   [yaa110/go-persian-calendar (⭐237)](https://github.com/yaa110/go-persian-calendar) — Persian calendar for Go ☆`239`
*   [bykof/gostradamus (⭐208)](https://github.com/bykof/gostradamus) — Better DateTimes for Go ☆`208`
*   [rickb777/date (⭐142)](https://github.com/rickb777/date) — Date handling package ☆`142`
*   [relvacode/iso8601 (⭐158)](https://github.com/relvacode/iso8601) — Fast ISO8601 date parser ☆`158`

### Dependency Injection

*   [uber-go/fx (⭐7.5k)](https://github.com/uber-go/fx) — DI-based application framework ☆`7,544`
*   [uber-go/dig (⭐4.5k)](https://github.com/uber-go/dig) — Reflection-based DI toolkit ☆`4,464`
*   [goioc/di (⭐379)](https://github.com/goioc/di) — Simple DI for Go ☆`378`
*   [go-kod/kod (⭐197)](https://github.com/go-kod/kod) — DI with aspect-oriented support ☆`197`
*   [i-love-flamingo/dingo (⭐188)](https://github.com/i-love-flamingo/dingo) — DI framework for Go ☆`188`
*   [NVIDIA/gontainer (⭐150)](https://github.com/NVIDIA/gontainer) — Simple DI container ☆`150`
*   [junioryono/godi (⭐76)](https://github.com/junioryono/godi) — DI with service lifetimes ☆`76`
*   [matzefriedrich/parsley (⭐32)](https://github.com/matzefriedrich/parsley) — Reflection-based DI package ☆`32`
*   [muir/nject (⭐30)](https://github.com/muir/nject) — Type-safe DI for Go ☆`30`
*   [firasdarwish/ore (⭐26)](https://github.com/firasdarwish/ore) — Advanced DI solution ☆`26`
*   [logrange/linker (⭐35)](https://github.com/logrange/linker) — DI and IoC package ☆`35`
*   [componego/componego (⭐29)](https://github.com/componego/componego) — Component-oriented framework ☆`29`
*   [gontainer/gontainer (⭐16)](https://github.com/gontainer/gontainer) — YAML-based DI container ☆`16`

### Error Handling

*   [hashicorp/go-multierror (⭐2.6k)](https://github.com/hashicorp/go-multierror) — Represent multiple errors as one ☆`2,570`
*   [cockroachdb/errors (⭐2.4k)](https://github.com/cockroachdb/errors) — Error library with portability ☆`2,407`
*   [rotisserie/eris (⭐1.8k)](https://github.com/rotisserie/eris) — Errors with readable stack traces ☆`1,788`
*   [joomcode/errorx (⭐1.3k)](https://github.com/joomcode/errorx) — Comprehensive error handling ☆`1,273`
*   [ztrue/tracerr (⭐1.1k)](https://github.com/ztrue/tracerr) — Errors with stack trace ☆`1,116`
*   [samber/oops (⭐947)](https://github.com/samber/oops) — Structured error handling ☆`956`
*   [Southclaws/fault (⭐310)](https://github.com/Southclaws/fault) — Composable error wrapping ☆`310`

### File Handling

*   [schollz/croc (⭐35k)](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`35,214`
*   [qax-os/excelize (⭐21k)](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,639`
*   [pdfcpu/pdfcpu (⭐8.7k)](https://github.com/pdfcpu/pdfcpu) — PDF processor in Go ☆`8,670`
*   [spf13/afero (⭐6.7k)](https://github.com/spf13/afero) — Filesystem abstraction for Go ☆`6,659`
*   [dundee/gdu (⭐5.7k)](https://github.com/dundee/gdu) — Fast disk usage analyzer ☆`5,711`
*   [unidoc/unioffice (⭐4.9k)](https://github.com/unidoc/unioffice) — Office document library ☆`4,873`
*   [root-gg/plik (⭐1.8k)](https://github.com/root-gg/plik) — Temporary file upload system ☆`1,771`
*   [SebastiaanKlippert/go-wkhtmltopdf (⭐1.2k)](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) — HTML to PDF wrapper ☆`1,177`
*   [otiai10/copy (⭐770)](https://github.com/otiai10/copy) — Copy directories recursively ☆`771`
*   [ulikunitz/xz (⭐556)](https://github.com/ulikunitz/xz) — Pure golang package for reading and writing xz-compressed files ☆`557`
*   [no-src/gofs (⭐529)](https://github.com/no-src/gofs) — Cross-platform file sync ☆`529`
*   [mholt/archives (⭐415)](https://github.com/mholt/archives) — Create and extract archives ☆`415`
*   [viant/afs (⭐386)](https://github.com/viant/afs) — Abstract file storage ☆`388`
*   [C2FO/vfs (⭐360)](https://github.com/C2FO/vfs) — Virtual file system for Go ☆`363`
*   [gen2brain/go-unarr (⭐310)](https://github.com/gen2brain/go-unarr) — Decompression library bindings ☆`310`
*   [barasher/go-exiftool (⭐292)](https://github.com/barasher/go-exiftool) — Exiftool wrapper for metadata ☆`293`
*   [gomutex/godocx (⭐257)](https://github.com/gomutex/godocx) — Go library for reading and writing Microsoft Docx ☆`258`
*   [charlievieth/fastwalk (⭐140)](https://github.com/charlievieth/fastwalk) — Fast directory traversal ☆`140`
*   [artonge/go-csv-tag (⭐131)](https://github.com/artonge/go-csv-tag) — CSV reading with tags ☆`131`
*   [parsyl/parquet (⭐127)](https://github.com/parsyl/parquet) — Parquet file library ☆`127`
*   [adelowo/gulter (⭐71)](https://github.com/adelowo/gulter) — Multipart form handling ☆`72`
*   [go-the-way/exl (⭐32)](https://github.com/go-the-way/exl) — Excel binding to struct written in Go.(Only supports Go1.18+) ☆`32`

### Forms

*   [justinas/nosurf (⭐1.7k)](https://github.com/justinas/nosurf) — CSRF protection middleware ☆`1,736`
*   [gorilla/csrf (⭐1.2k)](https://github.com/gorilla/csrf) — CSRF prevention middleware ☆`1,195`
*   [go-playground/form (⭐912)](https://github.com/go-playground/form) — URL values to structs ☆`913`
*   [ggicci/httpin (⭐385)](https://github.com/ggicci/httpin) — HTTP request to struct binding ☆`385`
*   [sonh/qs (⭐81)](https://github.com/sonh/qs) — Encode structs to query params ☆`81`
*   [cinar/checker (⭐48)](https://github.com/cinar/checker) — Input validation with struct tags ☆`48`

### Functional

*   [samber/mo (⭐3.4k)](https://github.com/samber/mo) — Monads and FP for Go ☆`3,360`
*   [BooleanCat/go-functional (⭐533)](https://github.com/BooleanCat/go-functional) — Iterator library for Go ☆`534`
*   [rjNemo/underscore (⭐117)](https://github.com/rjNemo/underscore) — Functional helpers for Go ☆`117`

### General

*   [wabarc/wayback (⭐2.2k)](https://github.com/wabarc/wayback) — Web archiving tool with IM interface ☆`2,197`
*   [gabriel-vasile/mimetype (⭐2k)](https://github.com/gabriel-vasile/mimetype) — MIME type detection by magic numbers ☆`1,981`
*   [qmuntal/stateless (⭐1.3k)](https://github.com/qmuntal/stateless) — Go library for creating finite state machines ☆`1,350`
*   [jonboulle/clockwork (⭐725)](https://github.com/jonboulle/clockwork) — a fake clock for golang ☆`725`
*   [Boeing/config-file-validator (⭐506)](https://github.com/Boeing/config-file-validator) — Cross-platform CLI tool to validate configuration files across 17 formats. Syntax and schema validation with JSON Schema, XSD, and SchemaStore integration. Written in Go. ☆`506`
*   [ungerik/go-dry (⭐487)](https://github.com/ungerik/go-dry) — DRY (don't repeat yourself) package for Go ☆`487`
*   [subosito/gotenv (⭐308)](https://github.com/subosito/gotenv) — Load environment variables from `.env` or `io.Reader` in Go. ☆`308`
*   [viant/toolbox (⭐228)](https://github.com/viant/toolbox) — Toolbox - go utility library ☆`228`
*   [ikeikeikeike/go-sitemap-generator (⭐230)](https://github.com/ikeikeikeike/go-sitemap-generator) — Generate XML sitemaps ☆`230`
*   [maja42/goval (⭐174)](https://github.com/maja42/goval) — Expression evaluation in golang ☆`174`
*   [jfcg/sorty (⭐144)](https://github.com/jfcg/sorty) — Fast Concurrent / Parallel Sorting in Go ☆`144`
*   [commander-cli/cmd (⭐161)](https://github.com/commander-cli/cmd) — A simple package to execute shell commands on linux, windows and osx ☆`161`
*   [syntaqx/cookie (⭐114)](https://github.com/syntaqx/cookie) — Cookies, but with structs, for happiness. ☆`114`
*   [tiendc/go-deepcopy (⭐128)](https://github.com/tiendc/go-deepcopy) — Fast deep-copy library for Go ☆`128`
*   [arthurkushman/pgo (⭐88)](https://github.com/arthurkushman/pgo) — Go library for PHP community with convenient functions ☆`88`
*   [pioz/countries (⭐96)](https://github.com/pioz/countries) — All you need when you are working with countries in Go. ☆`96`
*   [icza/backscanner (⭐69)](https://github.com/icza/backscanner) — Scan file lines backward ☆`69`
*   [wzshiming/gotype (⭐64)](https://github.com/wzshiming/gotype) — Golang source code parsing, usage like reflect package ☆`64`
*   [rkoesters/xdg (⭐49)](https://github.com/rkoesters/xdg) — FreeDesktop.org (xdg) Specs implemented in Go ☆`49`
*   [nikolaydubina/watchhttp (⭐34)](https://github.com/nikolaydubina/watchhttp) — Expose command output via HTTP ☆`34`
*   [mikekonan/go-types (⭐23)](https://github.com/mikekonan/go-types) — OpenAPI3 types for Go ☆`23`
*   [ik5/gostrutils (⭐47)](https://github.com/ik5/gostrutils) — Collections of string utils I have created over the years ☆`47`
*   [kazhuravlev/just (⭐37)](https://github.com/kazhuravlev/just) — Collection of useful functions. Complete simple tasks faster! ☆`37`
*   [floatdrop/debounce (⭐37)](https://github.com/floatdrop/debounce) — A zero-allocation debouncer ☆`37`
*   [lrita/numa (⭐38)](https://github.com/lrita/numa) — NUMA utility library for Go ☆`39`
*   [osamingo/gosh (⭐37)](https://github.com/osamingo/gosh) — Provide Go Statistics Handler, Struct, Measure Method ☆`37`
*   [skovtunenko/graterm (⭐30)](https://github.com/skovtunenko/graterm) — Graceful termination primitives ☆`30`

### Logging

*   [sirupsen/logrus (⭐26k)](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,731`
*   [uber-go/zap (⭐24k)](https://github.com/uber-go/zap) — Fast structured logging ☆`24,502`
*   [rs/zerolog (⭐12k)](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,414`
*   [golang/glog (⭐3.6k)](https://github.com/golang/glog) — Leveled execution logs ☆`3,602`
*   [k0kubun/pp (⭐2k)](https://github.com/k0kubun/pp) — Colored pretty printer for Go ☆`2,045`
*   [lmittmann/tint (⭐1.3k)](https://github.com/lmittmann/tint) — Colorized slog handler ☆`1,306`
*   [Lifailon/lazyjournal (⭐1.3k)](https://github.com/Lifailon/lazyjournal) — TUI for journald, Docker, K8s logs ☆`1,290`
*   [getsentry/sentry-go (⭐1.1k)](https://github.com/getsentry/sentry-go) — Official Sentry SDK for Go ☆`1,088`
*   [phuslu/log (⭐857)](https://github.com/phuslu/log) — Fastest structured logging ☆`859`
*   [samber/slog-multi (⭐625)](https://github.com/samber/slog-multi) — Workflow design for slog handlers ☆`626`
*   [gookit/slog (⭐542)](https://github.com/gookit/slog) — Configurable logging library ☆`542`
*   [henvic/httpretty (⭐413)](https://github.com/henvic/httpretty) — Pretty-print HTTP requests ☆`413`
*   [hashicorp/logutils (⭐372)](https://github.com/hashicorp/logutils) — Logging utilities for Go ☆`372`
*   [simukti/sqldb-logger (⭐382)](https://github.com/simukti/sqldb-logger) — SQL database logger ☆`382`
*   [samber/slog-formatter (⭐218)](https://github.com/samber/slog-formatter) — Slog attribute formatting ☆`218`
*   [DeRuina/timberjack (⭐137)](https://github.com/DeRuina/timberjack) — Log rolling library ☆`139`
*   [rs/xlog (⭐141)](https://github.com/rs/xlog) — Context-aware HTTP logger ☆`141`
*   [yuseferi/zax (⭐36)](https://github.com/yuseferi/zax) — Zap logger with context ☆`36`
*   [clok/kemba (⭐17)](https://github.com/clok/kemba) — Tiny debug logging tool ☆`17`

### Networking Utils

*   [cristianoliveira/ergo (⭐648)](https://github.com/cristianoliveira/ergo) — Manage apps on different ports ☆`648`
*   [htcat/htcat (⭐558)](https://github.com/htcat/htcat) — Parallel HTTP download ☆`558`
*   [ferama/rospo (⭐367)](https://github.com/ferama/rospo) — Persistent SSH tunnels ☆`369`

### Project Layout

*   [golang-standards/project-layout (⭐56k)](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`56,072`
*   [Melkeydev/go-blueprint (⭐8.8k)](https://github.com/Melkeydev/go-blueprint) — Spin up Go projects with popular frameworks ☆`8,847`
*   [ardanlabs/service (⭐4k)](https://github.com/ardanlabs/service) — K8s service starter kit ☆`4,022`
*   [Shpota/goxygen (⭐3.6k)](https://github.com/Shpota/goxygen) — Generate full-stack web projects ☆`3,595`
*   [mikestefanello/pagoda (⭐2.9k)](https://github.com/mikestefanello/pagoda) — Full-stack web development starter kit ☆`2,937`
*   [go-nunu/nunu (⭐2.6k)](https://github.com/go-nunu/nunu) — CLI for building Go apps ☆`2,573`
*   [sagikazarmark/modern-go-application (⭐1.9k)](https://github.com/sagikazarmark/modern-go-application) — Modern Go app example ☆`1,946`
*   [naughtygopher/goapp (⭐1.1k)](https://github.com/naughtygopher/goapp) — Opinionated web app structure ☆`1,062`
*   [lacion/cookiecutter-golang (⭐737)](https://github.com/lacion/cookiecutter-golang) — Go project template ☆`738`
*   [allaboutapps/go-starter (⭐610)](https://github.com/allaboutapps/go-starter) — Production-ready RESTful API template ☆`610`
*   [golang-templates/seed (⭐558)](https://github.com/golang-templates/seed) — Go app GitHub template ☆`563`
*   [Fs02/go-todo-backend (⭐336)](https://github.com/Fs02/go-todo-backend) — Go Todo Backend example using modular project layout for product microservice. ☆`336`
*   [raeperd/kickstart.go (⭐110)](https://github.com/raeperd/kickstart.go) — Minimal HTTP server template ☆`110`
*   [wangyoucao577/go-project-layout (⭐26)](https://github.com/wangyoucao577/go-project-layout) — Go project structure guide ☆`26`

### Resilience & Retry

*   [avast/retry-go (⭐2.9k)](https://github.com/avast/retry-go) — Simple retry mechanism ☆`2,930`
*   [eapache/go-resiliency (⭐2.3k)](https://github.com/eapache/go-resiliency) — Resiliency patterns for golang ☆`2,345`
*   [failsafe-go/failsafe-go (⭐2.2k)](https://github.com/failsafe-go/failsafe-go) — Fault tolerance patterns ☆`2,218`
*   [cep21/circuit (⭐814)](https://github.com/cep21/circuit) — Hystrix-like circuit breaker ☆`814`
*   [mennanov/limiters (⭐636)](https://github.com/mennanov/limiters) — Distributed rate limiters ☆`640`
*   [kamilsk/retry (⭐343)](https://github.com/kamilsk/retry) — Advanced retry mechanism ☆`343`
*   [webriots/rate (⭐165)](https://github.com/webriots/rate) — High-performance rate limiter ☆`166`

### Strings

*   [huandu/xstrings (⭐1.4k)](https://github.com/huandu/xstrings) — String functions from other langs ☆`1,414`
*   [abhimanyu003/sttr (⭐1.3k)](https://github.com/abhimanyu003/sttr) — CLI string operations ☆`1,323`
*   [gobeam/stringy (⭐250)](https://github.com/gobeam/stringy) — String case conversions ☆`250`
*   [ozgio/strutil (⭐206)](https://github.com/ozgio/strutil) — String utilities for Go ☆`206`

### System & Process

*   [cilium/ebpf (⭐7.8k)](https://github.com/cilium/ebpf) — eBPF library for Go ☆`7,778`
*   [maruel/panicparse (⭐3.7k)](https://github.com/maruel/panicparse) — Crash your app in style ☆`3,713`
*   [immortal/immortal (⭐834)](https://github.com/immortal/immortal) — Cross-platform supervisor ☆`835`
*   [derekparker/delve (⭐662)](https://github.com/derekparker/delve) — Delve is a debugger for the Go programming language. ☆`662`
*   [gotranspile/cxgo (⭐391)](https://github.com/gotranspile/cxgo) — Transpile C to Go ☆`392`

### UUID

*   [google/uuid (⭐6.1k)](https://github.com/google/uuid) — UUID generation and parsing ☆`6,075`
*   [oklog/ulid (⭐5k)](https://github.com/oklog/ulid) — ULID implementation ☆`5,035`
*   [gofrs/uuid (⭐1.8k)](https://github.com/gofrs/uuid) — UUID library for Go ☆`1,808`
*   [osamingo/indigo (⭐112)](https://github.com/osamingo/indigo) — Sonyflake-based ID generator ☆`112`
*   [sdrapkin/guid (⭐74)](https://github.com/sdrapkin/guid) — Fast cryptographically safe Guid generator for Go ☆`75`
*   [twharmon/gouid (⭐26)](https://github.com/twharmon/gouid) — Fast, dependable universally unique ids ☆`26`

## Version Control & Packages

### Git APIs

*   [google/go-github (⭐11k)](https://github.com/google/go-github) — Go library for accessing the GitHub v3 API ☆`11,251`
*   [shurcooL/githubv4 (⭐1.2k)](https://github.com/shurcooL/githubv4) — GitHub GraphQL API v4 client ☆`1,189`
*   [go-playground/webhooks (⭐1k)](https://github.com/go-playground/webhooks) — Webhook receiver for GitHub, Bitbucket, GitLab, Gogs ☆`1,030`
*   [andygrunwald/go-trending (⭐146)](https://github.com/andygrunwald/go-trending) — Access GitHub trending repositories ☆`146`
*   [andygrunwald/go-gerrit (⭐105)](https://github.com/andygrunwald/go-gerrit) — Go client/library for Gerrit Code Review ☆`105`

### Package Management

*   [anchore/syft (⭐9k)](https://github.com/anchore/syft) — SBOM generator for containers ☆`9,067`
*   [nao1215/gup (⭐577)](https://github.com/nao1215/gup) — gup - Update binaries installed by "go install" with goroutines. ☆`579`
*   [marwanhawari/stew (⭐349)](https://github.com/marwanhawari/stew) — An independent package manager for compiled binaries. ☆`349`
*   [chaindead/modup (⭐65)](https://github.com/chaindead/modup) — TUI for Go dependency updates ☆`65`

### Version Control

*   [go-git/go-git (⭐7.5k)](https://github.com/go-git/go-git) — Pure Go Git implementation ☆`7,497`
*   [antham/chyle (⭐161)](https://github.com/antham/chyle) — Changelog generator from Git ☆`161`
*   [gabyx/Githooks (⭐123)](https://github.com/gabyx/Githooks) — Per-repo shared Git hooks ☆`123`
*   [antham/gommit (⭐116)](https://github.com/antham/gommit) — Enforce git message commit consistency ☆`116`
*   [jfrog/froggit-go (⭐53)](https://github.com/jfrog/froggit-go) — Universal VCS client library ☆`53`
*   [kazhuravlev/git-tools (⭐32)](https://github.com/kazhuravlev/git-tools) — Useful set of tools which helps to manage git tags ☆`32`

## Web Development

### Microservices

*   [zeromicro/go-zero (⭐33k)](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`33,074`
*   [go-kit/kit (⭐27k)](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,425`
*   [go-kratos/kratos (⭐26k)](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,717`
*   [micro/go-micro (⭐23k)](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,757`
*   [smallnest/rpcx (⭐8.3k)](https://github.com/smallnest/rpcx) — Feature-rich RPC framework ☆`8,285`
*   [cloudwego/kitex (⭐8k)](https://github.com/cloudwego/kitex) — High-performance Go RPC framework ☆`7,965`
*   [go-dev-frame/sponge (⭐2.8k)](https://github.com/go-dev-frame/sponge) — Code generation framework for Go ☆`2,847`
*   [go-eagle/eagle (⭐2.4k)](https://github.com/go-eagle/eagle) — A Go framework for the API or Microservice ☆`2,423`
*   [unionj-cloud/go-doudou (⭐1.2k)](https://github.com/unionj-cloud/go-doudou) — OpenAPI 3 and gRPC microservices framework ☆`1,172`
*   [trpc-group/trpc-go (⭐1.2k)](https://github.com/trpc-group/trpc-go) — A pluggable, high-performance RPC framework written in golang ☆`1,156`
*   [gmsec/micro (⭐26)](https://github.com/gmsec/micro) — A Go distributed systems development framework ☆`26`

### Middlewares

*   [urfave/negroni (⭐7.5k)](https://github.com/urfave/negroni) — Idiomatic HTTP Middleware for Golang ☆`7,528`
*   [tdewolff/minify (⭐4.1k)](https://github.com/tdewolff/minify) — Go minifiers for web formats ☆`4,108`
*   [justinas/alice (⭐3.4k)](https://github.com/justinas/alice) — Painless middleware chaining for Go ☆`3,358`
*   [rs/cors (⭐2.9k)](https://github.com/rs/cors) — Go net/http configurable handler to handle CORS requests ☆`2,883`
*   [didip/tollbooth (⭐2.9k)](https://github.com/didip/tollbooth) — Simple middleware to rate-limit HTTP requests. ☆`2,858`
*   [unrolled/render (⭐2k)](https://github.com/unrolled/render) — Render JSON, XML, HTML, binary ☆`1,991`
*   [lingrino/go-fault (⭐554)](https://github.com/lingrino/go-fault) — go fault injection library ☆`554`
*   [jub0bs/cors (⭐220)](https://github.com/jub0bs/cors) — perhaps the best CORS middleware library for Go ☆`223`
*   [faabiosr/echo-middleware (⭐16)](https://github.com/faabiosr/echo-middleware) — Middlewares for Echo framework ☆`16`

### Routers

*   [go-chi/chi (⭐22k)](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`22,293`
*   [gorilla/mux (⭐22k)](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,822`
*   [gowww/router (⭐184)](https://github.com/gowww/router) — A lightning fast HTTP router ☆`184`
*   [bmf-san/goblin (⭐82)](https://github.com/bmf-san/goblin) — A golang http router based on trie tree. ☆`82`
*   [ngamux/ngamux (⭐70)](https://github.com/ngamux/ngamux) — Simple HTTP router for Go ☆`70`
*   [muir/nchi (⭐18)](https://github.com/muir/nchi) — golang http router with elegance, speed, and flexibility ☆`18`

### Template Engines

*   [a-h/templ (⭐10k)](https://github.com/a-h/templ) — A language for writing HTML user interfaces in Go. ☆`10,331`
*   [valyala/quicktemplate (⭐3.3k)](https://github.com/valyala/quicktemplate) — Fast template engine for Go ☆`3,322`
*   [johnfercher/maroto (⭐2.7k)](https://github.com/johnfercher/maroto) — Create PDFs with Bootstrap grid ☆`2,714`
*   [CloudyKit/jet (⭐1.4k)](https://github.com/CloudyKit/jet) — Jet template engine ☆`1,398`
*   [osteele/liquid (⭐347)](https://github.com/osteele/liquid) — A Liquid template engine in Go ☆`349`
*   [go-sprout/sprout (⭐214)](https://github.com/go-sprout/sprout) — Template functions for Go ☆`215`
*   [goradd/got (⭐38)](https://github.com/goradd/got) — Template engine with Go code output ☆`38`

### Web Frameworks

*   [gin-gonic/gin (⭐89k)](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`88,607`
*   [gofiber/fiber (⭐40k)](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`39,807`
*   [beego/beego (⭐32k)](https://github.com/beego/beego) — High-performance web framework ☆`32,393`
*   [labstack/echo (⭐32k)](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,424`
*   [gofr-dev/gofr (⭐21k)](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`21,383`
*   [gogf/gf (⭐13k)](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,169`
*   [cloudwego/hertz (⭐7.2k)](https://github.com/cloudwego/hertz) — High-performance HTTP framework ☆`7,260`
*   [goadesign/goa (⭐6.1k)](https://github.com/goadesign/goa) — Design-first API framework ☆`6,083`
*   [apache/dubbo-go (⭐4.9k)](https://github.com/apache/dubbo-go) — Go Implementation For Apache Dubbo . ☆`4,932`
*   [goravel/goravel (⭐4.5k)](https://github.com/goravel/goravel) — The full-featured Golang Development Framework skeleton ☆`4,542`
*   [danielgtaylor/huma (⭐4.1k)](https://github.com/danielgtaylor/huma) — Huma REST/HTTP API Framework for Golang with OpenAPI 3.1 ☆`4,144`
*   [documize/community (⭐2.4k)](https://github.com/documize/community) — Modern Confluence alternative ☆`2,396`
*   [go-goyave/goyave (⭐1.8k)](https://github.com/go-goyave/goyave) — The enterprise REST API framework ☆`1,769`
*   [go-fuego/fuego (⭐1.7k)](https://github.com/go-fuego/fuego) — Web framework with OpenAPI 3 ☆`1,728`
*   [templui/templui (⭐1.6k)](https://github.com/templui/templui) — UI components for Templ ☆`1,595`
*   [savsgio/atreugo (⭐1.3k)](https://github.com/savsgio/atreugo) — Micro web framework on fasthttp ☆`1,304`
*   [ankorstore/yokai (⭐832)](https://github.com/ankorstore/yokai) — Modular framework for Go apps ☆`834`
*   [indeedeng/iwf (⭐641)](https://github.com/indeedeng/iwf) — Workflow-as-code orchestration ☆`639`
*   [i-love-flamingo/flamingo-commerce (⭐588)](https://github.com/i-love-flamingo/flamingo-commerce) — Flexible Go web framework ☆`588`
*   [i-love-flamingo/flamingo (⭐560)](https://github.com/i-love-flamingo/flamingo) — Flexible Go web framework ☆`558`
*   [rookie-ninja/rk-boot (⭐575)](https://github.com/rookie-ninja/rk-boot) — Enterprise microservice framework ☆`575`
*   [fastschema/fastschema (⭐552)](https://github.com/fastschema/fastschema) — All-in-One Backend as a Service with Headless CMS Power ☆`553`
*   [uadmin/uadmin (⭐354)](https://github.com/uadmin/uadmin) — The web framework for Golang ☆`354`
*   [xxjwxc/ginrpc (⭐304)](https://github.com/xxjwxc/ginrpc) — gin auto binding, grpc and annotated route ☆`304`
*   [hidevopsio/hiboot (⭐179)](https://github.com/hidevopsio/hiboot) — High-performance CLI and web apps ☆`179`
*   [beatlabs/patron (⭐127)](https://github.com/beatlabs/patron) — Cloud-native microservice framework ☆`125`
*   [claygod/microservice (⭐122)](https://github.com/claygod/microservice) — Simple microservice framework ☆`122`
*   [gone-io/gone (⭐129)](https://github.com/gone-io/gone) — Lightweight DI framework ☆`129`
*   [gookit/rux (⭐99)](https://github.com/gookit/rux) — Simple and fast web framework ☆`99`
*   [yaitoo/xun (⭐91)](https://github.com/yaitoo/xun) — Web framework on html/template ☆`91`
*   [go-spring/spring-core (⭐83)](https://github.com/go-spring/spring-core) — Spring-inspired framework for Go ☆`83`
*   [napsy/go-css (⭐94)](https://github.com/napsy/go-css) — A very simple CSS parser, written in Go ☆`94`
*   [abemedia/go-don (⭐59)](https://github.com/abemedia/go-don) — API framework written in Golang. ☆`59`
*   [JiveGroup/gFly (⭐48)](https://github.com/JiveGroup/gFly) — Laravel inspired web framework written in Go ☆`48`
*   [clubpay/ronykit (⭐36)](https://github.com/clubpay/ronykit) — API Framework supporting REST and RPC. ☆`36`
*   [SaiNageswarS/go-api-boot (⭐34)](https://github.com/SaiNageswarS/go-api-boot) — gRPC + HTTP/2 production framework ☆`34`

### WebAssembly

*   [tinygo-org/tinygo (⭐17k)](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,490`
*   [agnivade/wasmbrowsertest (⭐207)](https://github.com/agnivade/wasmbrowsertest) — Run WASM tests inside your browser ☆`208`
*   [extism/go-sdk (⭐174)](https://github.com/extism/go-sdk) — Extism Go SDK - easily run WebAssembly modules in your Go applications ☆`175`

## Workflow & Scheduling

### Job Scheduler

*   [hatchet-dev/hatchet (⭐7.2k)](https://github.com/hatchet-dev/hatchet) — An orchestration engine for background tasks, AI agents, and durable workflows ☆`7,294`
*   [go-co-op/gocron (⭐7.1k)](https://github.com/go-co-op/gocron) — Easy and fluent Go cron scheduling ☆`7,066`
*   [reugn/go-quartz (⭐2k)](https://github.com/reugn/go-quartz) — Minimalist and zero-dependency scheduling library for Go ☆`2,011`
*   [adhocore/gronx (⭐504)](https://github.com/adhocore/gronx) — Lightweight cron expression parser ☆`504`
*   [fieldryand/goflow (⭐478)](https://github.com/fieldryand/goflow) — Simple but powerful DAG scheduler and dashboard ☆`480`
*   [madflojo/tasks (⭐329)](https://github.com/madflojo/tasks) — In-process task scheduler ☆`330`
*   [bart6114/cheek (⭐196)](https://github.com/bart6114/cheek) — cheek: a pico-sized declarative job scheduler ☆`196`
*   [onatm/clockwerk (⭐182)](https://github.com/onatm/clockwerk) — Job Scheduling Library ☆`182`
*   [deepaksinghvi/cdule (⭐61)](https://github.com/deepaksinghvi/cdule) — Golang job scheduler ☆`61`
*   [pardnchiu/go-scheduler (⭐34)](https://github.com/pardnchiu/go-scheduler) — Scheduler with standard cron and task dependencies ☆`34`
*   [romshark/sched (⭐31)](https://github.com/romshark/sched) — A job scheduler for Go with the ability to fast-forward time. ☆`31`

### Workflow Frameworks

*   [redpanda-data/connect (⭐8.7k)](https://github.com/redpanda-data/connect) — Fancy stream processing made operationally mundane ☆`8,676`
*   [dagucloud/dagu (⭐3.4k)](https://github.com/dagucloud/dagu) — Workflow engine with Web UI ☆`3,454`
*   [jf-tech/omniparser (⭐1.1k)](https://github.com/jf-tech/omniparser) — ETL streaming parser for Go ☆`1,084`
*   [noneback/go-taskflow (⭐629)](https://github.com/noneback/go-taskflow) — Task-parallel programming library ☆`629`
*   [cadence-workflow/cadence-go-client (⭐376)](https://github.com/cadence-workflow/cadence-go-client) — Cadence workflow client for Go ☆`377`
*   [luno/workflow (⭐239)](https://github.com/luno/workflow) — Type-safe workflow orchestration ☆`239`
*   [rhosocial/go-dag (⭐40)](https://github.com/rhosocial/go-dag) — DAG-based workflow framework ☆`40`

***

## 🏆 Top 100 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1.  [ollama/ollama (⭐172k)](https://github.com/ollama/ollama) — Run LLMs locally ☆`173,218`
2.  [kubernetes/kubernetes (⭐122k)](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`122,694`
3.  [gin-gonic/gin (⭐89k)](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`88,607`
4.  [junegunn/fzf (⭐81k)](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`80,869`
5.  [caddyserver/caddy (⭐73k)](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`73,149`
6.  [moby/moby (⭐72k)](https://github.com/moby/moby) — Container ecosystem components ☆`71,623`
7.  [prometheus/prometheus (⭐64k)](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`64,262`
8.  [traefik/traefik (⭐63k)](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`63,564`
9.  [pocketbase/pocketbase (⭐59k)](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`58,886`
10. [go-gitea/gitea (⭐56k)](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`56,122`
11. [golang-standards/project-layout (⭐56k)](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`56,072`
12. [wagoodman/dive (⭐54k)](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`54,207`
13. [etcd-io/etcd (⭐52k)](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`51,769`
14. [ethereum/go-ethereum (⭐51k)](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`51,072`
15. [mudler/LocalAI (⭐46k)](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`46,678`
16. [milvus-io/milvus (⭐45k)](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`44,636`
17. [spf13/cobra (⭐44k)](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`44,056`
18. [charmbracelet/bubbletea (⭐43k)](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`42,888`
19. [pingcap/tidb (⭐40k)](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`40,129`
20. [gofiber/fiber (⭐40k)](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`39,807`
21. [go-gorm/gorm (⭐40k)](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,770`
22. [harness/harness (⭐36k)](https://github.com/harness/harness) — End-to-end developer platform ☆`36,386`
23. [schollz/croc (⭐35k)](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`35,214`
24. [restic/restic (⭐34k)](https://github.com/restic/restic) — Fast, secure backup program ☆`33,869`
25. [k3s-io/k3s (⭐33k)](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`33,170`
26. [zeromicro/go-zero (⭐33k)](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`33,074`
27. [seaweedfs/seaweedfs (⭐33k)](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`32,720`
28. [labstack/echo (⭐32k)](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,424`
29. [beego/beego (⭐32k)](https://github.com/beego/beego) — High-performance web framework ☆`32,393`
30. [cockroachdb/cockroach (⭐32k)](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`32,182`
31. [kubernetes/minikube (⭐32k)](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,840`
32. [influxdata/influxdb (⭐32k)](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,527`
33. [grafana/k6 (⭐31k)](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`30,729`
34. [spf13/viper (⭐30k)](https://github.com/spf13/viper) — Go configuration with fangs ☆`30,282`
35. [fyne-io/fyne (⭐28k)](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`28,332`
36. [go-kit/kit (⭐27k)](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,425`
37. [stretchr/testify (⭐26k)](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`26,008`
38. [sirupsen/logrus (⭐26k)](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,731`
39. [go-kratos/kratos (⭐26k)](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,717`
40. [gocolly/colly (⭐25k)](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,311`
41. [tsenart/vegeta (⭐25k)](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`25,059`
42. [uber-go/zap (⭐24k)](https://github.com/uber-go/zap) — Fast structured logging ☆`24,502`
43. [urfave/cli (⭐24k)](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`24,107`
44. [air-verse/air (⭐24k)](https://github.com/air-verse/air) — Live reload for Go apps ☆`23,637`
45. [valyala/fasthttp (⭐23k)](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,366`
46. [dolthub/dolt (⭐23k)](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`23,085`
47. [grpc/grpc-go (⭐23k)](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,947`
48. [jaegertracing/jaeger (⭐23k)](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`22,858`
49. [micro/go-micro (⭐23k)](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,757`
50. [FiloSottile/age (⭐22k)](https://github.com/FiloSottile/age) — Simple encryption tool ☆`22,482`
51. [go-chi/chi (⭐22k)](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`22,293`
52. [redis/go-redis (⭐22k)](https://github.com/redis/go-redis) — Redis Go client ☆`22,126`
53. [gorilla/mux (⭐22k)](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,822`
54. [dgraph-io/dgraph (⭐22k)](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,678`
55. [gofr-dev/gofr (⭐21k)](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`21,383`
56. [samber/lo (⭐21k)](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`21,312`
57. [vitessio/vitess (⭐21k)](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`20,996`
58. [qax-os/excelize (⭐21k)](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,639`
59. [antonmedv/fx](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,617`
60. [apache/casbin (⭐20k)](https://github.com/apache/casbin) — Authorization library for Go ☆`20,170`
61. [go-playground/validator (⭐20k)](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`19,994`
62. [nats-io/nats-server (⭐20k)](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`19,953`
63. [golangci/golangci-lint (⭐19k)](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`19,039`
64. [golang-migrate/migrate (⭐19k)](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,568`
65. [sqlc-dev/sqlc (⭐18k)](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`17,834`
66. [jmoiron/sqlx (⭐18k)](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,636`
67. [keploy/keploy (⭐17k)](https://github.com/keploy/keploy) — API testing with auto mocks ☆`17,594`
68. [rqlite/rqlite (⭐18k)](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,562`
69. [tinygo-org/tinygo (⭐17k)](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,490`
70. [VictoriaMetrics/VictoriaMetrics (⭐17k)](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`17,107`
71. [ent/ent (⭐17k)](https://github.com/ent/ent) — An entity framework for Go ☆`17,097`
72. [ipfs/kubo (⭐17k)](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`17,035`
73. [pion/webrtc (⭐16k)](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,519`
74. [fatih/vim-go (⭐16k)](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,235`
75. [goreleaser/goreleaser (⭐16k)](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,844`
76. [hashicorp/packer (⭐16k)](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,697`
77. [go-task/task (⭐16k)](https://github.com/go-task/task) — Fast cross-platform build tool inspired by Make ☆`15,668`
78. [dgraph-io/badger (⭐16k)](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,644`
79. [tidwall/gjson (⭐16k)](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,511`
80. [kubernetes-sigs/kind (⭐15k)](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,277`
81. [go-sql-driver/mysql (⭐15k)](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,245`
82. [PuerkitoBio/goquery (⭐15k)](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,947`
83. [panjf2000/ants (⭐14k)](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,426`
84. [cloudflare/cloudflared (⭐14k)](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`14,420`
85. [bytebase/bytebase (⭐14k)](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`14,107`
86. [webview/webview (⭐14k)](https://github.com/webview/webview) — Tiny webview library for Go ☆`14,090`
87. [jackc/pgx (⭐14k)](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`13,888`
88. [juicedata/juicefs (⭐14k)](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`13,664`
89. [gizak/termui (⭐14k)](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,568`
90. [hibiken/asynq (⭐13k)](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`13,338`
91. [golang/groupcache (⭐13k)](https://github.com/golang/groupcache) — Distributed cache library ☆`13,334`
92. [hajimehoshi/ebiten (⭐13k)](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`13,207`
93. [gogf/gf (⭐13k)](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,169`
94. [gopherjs/gopherjs (⭐13k)](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,152`
95. [chromedp/chromedp (⭐13k)](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`13,095`
96. [IBM/sarama (⭐12k)](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,487`
97. [rs/zerolog (⭐12k)](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,414`
98. [drakkan/sftpgo (⭐12k)](https://github.com/drakkan/sftpgo) — Full-featured SFTP/FTP/HTTP server ☆`12,127`
99. [Shopify/toxiproxy (⭐12k)](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`12,065`
100.    [kubeshark/kubeshark (⭐12k)](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`11,922`

## Gophers

*   [MariaLetta/free-gophers-pack (⭐3.9k)](https://github.com/MariaLetta/free-gophers-pack) — This pack of 100+ gopher pictures and elements
*   [keygx/Go-gopher-Vector (⭐75)](https://github.com/keygx/Go-gopher-Vector) — Go gopher Vector Data (.ai, .svg)
*   [ashleymcnamara/gophers (⭐3.1k)](https://github.com/ashleymcnamara/gophers) — Gopher Artwork by Ashley McNamara
*   [sillecelik/go-gopher (⭐162)](https://github.com/sillecelik/go-gopher) — The Go Gopher Amigurumi Pattern
*   [GolangUA/gopher-logos (⭐140)](https://github.com/GolangUA/gopher-logos) — adorable gopher logos
*   [egonelbre/gophers (⭐3.8k)](https://github.com/egonelbre/gophers) — gophers artwork
*   [scraly/gophers (⭐37)](https://github.com/scraly/gophers) — Gopher artwork (Golang mascot)

## Contributing

Please see [CONTRIBUTING](https://github.com/abordage/awesome-go/blob/main/README.md/.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request — contributions are welcome!

## Credits

*   [avelino/awesome-go (⭐174k)](https://github.com/avelino/awesome-go)
*   [All Contributors (⭐4)](https://github.com/abordage/awesome-go/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](https://github.com/abordage/awesome-go/blob/main/README.md/LICENSE) for more information.

