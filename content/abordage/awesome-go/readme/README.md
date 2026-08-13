# Awesome Go Overview

Structured collection of Go frameworks, libraries, tools, and resources. Automatically maintained and up-to-date with metadata, filtering, and comprehensive categorization.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/abordage/awesome-go/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 abordage/awesome-go](https://github.com/abordage/awesome-go) · ⭐ 5 · 🏷️ Programming Languages

[ [Daily](/content/abordage/awesome-go/README.md) / [Weekly](/content/abordage/awesome-go/week/README.md) / Overview ]

---

# Awesome Go

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-go?label=last%20update)](https://github.com/abordage/awesome-go/blob/main/README.md/README.md)
![Repositories](https://img.shields.io/badge/repositories-1,133-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-4,985,141-gold)
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

*   [sashabaranov/go-openai (⭐11k)](https://github.com/sashabaranov/go-openai) — OpenAI API client for Go ☆`10,734`
*   [wit-ai/wit-go (⭐171)](https://github.com/wit-ai/wit-go) — Go client for wit.ai HTTP API ☆`171`

### Artificial Intelligence

*   [ollama/ollama (⭐178k)](https://github.com/ollama/ollama) — Run LLMs locally ☆`178,403`
*   [mudler/LocalAI (⭐48k)](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`48,418`
*   [tmc/langchaingo (⭐9.6k)](https://github.com/tmc/langchaingo) — LangChain for Go, the easiest way to write LLM-based programs in Go ☆`9,607`
*   [maximhq/bifrost (⭐6.9k)](https://github.com/maximhq/bifrost) — Fastest LLM gateway for Go ☆`7,275`
*   [philippgille/chromem-go (⭐1k)](https://github.com/philippgille/chromem-go) — Embeddable vector database for Go ☆`1,044`
*   [universal-tool-calling-protocol/go-utcp (⭐120)](https://github.com/universal-tool-calling-protocol/go-utcp) — Official Go implementation of the UTCP ☆`121`
*   [presbrey/ollamafarm (⭐101)](https://github.com/presbrey/ollamafarm) — Manage multiple Ollama instances ☆`101`

### Machine Learning

*   [otiai10/gosseract (⭐3.1k)](https://github.com/otiai10/gosseract) — OCR using Tesseract in Go ☆`3,127`
*   [gomlx/gomlx (⭐1.6k)](https://github.com/gomlx/gomlx) — GoMLX: An Accelerated Machine Learning Framework For Go ☆`1,602`
*   [jbrukh/bayesian (⭐814)](https://github.com/jbrukh/bayesian) — Naive Bayesian Classification for Golang. ☆`814`
*   [knights-analytics/hugot (⭐634)](https://github.com/knights-analytics/hugot) — Onnx transformer pipelines in Golang ☆`634`
*   [c-bata/goptuna (⭐279)](https://github.com/c-bata/goptuna) — A hyperparameter optimization framework, inspired by Optuna. ☆`279`

## Audio & Video

### Audio

*   [ebitengine/oto (⭐1.9k)](https://github.com/ebitengine/oto) — A low-level library to play sound on multiple platforms ☆`1,948`
*   [gordonklaus/portaudio (⭐841)](https://github.com/gordonklaus/portaudio) — Go bindings for the PortAudio audio I/O library ☆`841`
*   [gen2brain/malgo (⭐422)](https://github.com/gen2brain/malgo) — Mini audio library ☆`423`
*   [mewkiz/flac (⭐360)](https://github.com/mewkiz/flac) — Package flac provides access to FLAC (Free Lossless Audio Codec) streams. ☆`360`
*   [tosone/minimp3 (⭐133)](https://github.com/tosone/minimp3) — Decode mp3 ☆`133`

### Images

*   [hybridgroup/gocv (⭐7.5k)](https://github.com/hybridgroup/gocv) — Computer vision with OpenCV 4 ☆`7,486`
*   [anthonynsimon/bild (⭐4.2k)](https://github.com/anthonynsimon/bild) — Image processing algorithms in pure Go ☆`4,203`
*   [cshum/imagor (⭐4k)](https://github.com/cshum/imagor) — Fast, secure image processing server and Go library, using libvips ☆`4,002`
*   [thoas/picfit (⭐2.3k)](https://github.com/thoas/picfit) — An image resizing server written in Go ☆`2,340`
*   [gographics/imagick (⭐1.9k)](https://github.com/gographics/imagick) — Go binding to ImageMagick's MagickWand C API ☆`1,873`
*   [tdewolff/canvas (⭐1.8k)](https://github.com/tdewolff/canvas) — Vector graphics in Go ☆`1,827`
*   [davidbyttow/govips (⭐1.6k)](https://github.com/davidbyttow/govips) — A lightning fast image processing and resizing library for Go ☆`1,646`
*   [yeqown/go-qrcode (⭐857)](https://github.com/yeqown/go-qrcode) — Customizable QR code generator ☆`858`
*   [HugoSmits86/nativewebp (⭐454)](https://github.com/HugoSmits86/nativewebp) — Native webp encoder for Go ☆`454`
*   [auyer/steganography (⭐353)](https://github.com/auyer/steganography) — LSB steganography in pure Go ☆`353`
*   [kolesa-team/go-webp (⭐316)](https://github.com/kolesa-team/go-webp) — Simple and fast webp library for golang ☆`316`
*   [qmuntal/gltf (⭐285)](https://github.com/qmuntal/gltf) — Go library for encoding glTF 2.0 files ☆`285`
*   [Pixboost/transformimgs (⭐292)](https://github.com/Pixboost/transformimgs) — Open source image CDN. ☆`292`
*   [gojek/darkroom (⭐235)](https://github.com/gojek/darkroom) — Image processing engine and proxy service ☆`235`
*   [ungerik/go-cairo (⭐153)](https://github.com/ungerik/go-cairo) — Go binding for the cairo graphics library ☆`153`
*   [aofei/cameron (⭐132)](https://github.com/aofei/cameron) — An avatar generator for Go. ☆`132`
*   [piglig/go-qr (⭐60)](https://github.com/piglig/go-qr) — A native, high-quality and minimalistic QR code generator and decoder ☆`60`

### Video

*   [asticode/go-astiav (⭐728)](https://github.com/asticode/go-astiav) — Golang ffmpeg and libav C bindings ☆`728`
*   [asticode/go-astisub (⭐703)](https://github.com/asticode/go-astisub) — Manipulate subtitles in Go ☆`703`
*   [Eyevinn/mp4ff (⭐650)](https://github.com/Eyevinn/mp4ff) — MP4/ISOBMFF tools and library ☆`651`
*   [asticode/go-astits (⭐616)](https://github.com/asticode/go-astits) — Demux and mux MPEG Transport Streams (.ts) natively in GO ☆`616`
*   [adrg/libvlc-go (⭐509)](https://github.com/adrg/libvlc-go) — Go bindings for libVLC ☆`509`
*   [Eyevinn/hls-m3u8 (⭐67)](https://github.com/Eyevinn/hls-m3u8) — HLS m3u8 library in Go ☆`68`
*   [jonoton/scout (⭐30)](https://github.com/jonoton/scout) — Video surveillance with motion detection ☆`30`
*   [unki2aut/go-mpd (⭐32)](https://github.com/unki2aut/go-mpd) — MPEG-DASH manifest library ☆`32`

## Auth

### Authentication

*   [golang-jwt/jwt (⭐9.2k)](https://github.com/golang-jwt/jwt) — Go implementation of JSON Web Tokens (JWT). ☆`9,194`
*   [markbates/goth (⭐6.6k)](https://github.com/markbates/goth) — Multi-provider authentication ☆`6,591`
*   [golang/oauth2 (⭐5.9k)](https://github.com/golang/oauth2) — Go OAuth2 ☆`5,890`
*   [aarondl/authboss (⭐4.2k)](https://github.com/aarondl/authboss) — The boss of http auth. ☆`4,197`
*   [alexedwards/scs (⭐2.6k)](https://github.com/alexedwards/scs) — HTTP Session Management for Go ☆`2,613`
*   [lestrrat-go/jwx (⭐2.4k)](https://github.com/lestrrat-go/jwx) — Complete JWx implementation ☆`2,412`
*   [openshift/osin (⭐1.9k)](https://github.com/openshift/osin) — Golang OAuth2 server library ☆`1,934`
*   [dghubble/gologin (⭐2k)](https://github.com/dghubble/gologin) — Go login handlers for authentication providers (OAuth1, OAuth2) ☆`1,958`
*   [zitadel/oidc (⭐1.9k)](https://github.com/zitadel/oidc) — OpenID Connect client and server ☆`1,864`
*   [cristalhq/jwt (⭐690)](https://github.com/cristalhq/jwt) — Safe, simple and fast JSON Web Tokens for Go ☆`690`
*   [go-jose/go-jose (⭐528)](https://github.com/go-jose/go-jose) — An implementation of JOSE standards (JWE, JWS, JWT) in Go ☆`528`
*   [abraithwaite/jeff (⭐272)](https://github.com/abraithwaite/jeff) — Jeff provides the simplest way to manage web sessions in Go. ☆`272`
*   [leodip/goiabada (⭐200)](https://github.com/leodip/goiabada) — Goiabada is an OAuth2 / OpenID Connect server written in Go. ☆`200`
*   [jellydator/sessionup (⭐132)](https://github.com/jellydator/sessionup) — Straightforward HTTP session management ☆`132`
*   [brianvoe/sjwt (⭐123)](https://github.com/brianvoe/sjwt) — Simple JWT Golang ☆`123`
*   [icza/session (⭐119)](https://github.com/icza/session) — Session management for web servers ☆`119`
*   [essentialkaos/branca (⭐100)](https://github.com/essentialkaos/branca) — Encrypted API tokens ☆`100`
*   [mengzhuo/cookiestxt (⭐24)](https://github.com/mengzhuo/cookiestxt) — cookiestxt implement parser of cookies txt format ☆`24`

### Authorization

*   [apache/casbin (⭐20k)](https://github.com/apache/casbin) — Authorization library for Go ☆`20,322`
*   [openfga/openfga (⭐5.6k)](https://github.com/openfga/openfga) — Fine-grained authorization server ☆`5,589`
*   [ory/keto (⭐5.4k)](https://github.com/ory/keto) — Customizable permission server ☆`5,388`
*   [cerbos/cerbos (⭐4.5k)](https://github.com/cerbos/cerbos) — Open core authorization layer ☆`4,533`

## Bots & Chat

### Bot Frameworks

*   [tucnak/telebot (⭐4.6k)](https://github.com/tucnak/telebot) — Telebot is a Telegram bot framework in Go. ☆`4,634`
*   [go-telegram/bot (⭐1.8k)](https://github.com/go-telegram/bot) — Telegram Bot API Go framework ☆`1,803`
*   [mymmrac/telego (⭐1.1k)](https://github.com/mymmrac/telego) — Telegram Bot API library for Go ☆`1,063`
*   [diamondburned/arikawa (⭐598)](https://github.com/diamondburned/arikawa) — A Golang library and framework for the Discord API. ☆`598`
*   [NicoNex/echotron (⭐444)](https://github.com/NicoNex/echotron) — An elegant and concurrent library for the Telegram bot API in Go. ☆`445`
*   [gempir/go-twitch-irc (⭐402)](https://github.com/gempir/go-twitch-irc) — go irc client for twitch.tv ☆`402`
*   [innogames/slack-bot (⭐210)](https://github.com/innogames/slack-bot) — Slack bot for Jenkins, Jira, PRs ☆`210`
*   [mr-linch/go-tg (⭐136)](https://github.com/mr-linch/go-tg) — Telegram Bot API client ☆`136`
*   [slack-io/slacker (⭐61)](https://github.com/slack-io/slacker) — Slack Bot Framework ☆`62`
*   [onrik/micha (⭐34)](https://github.com/onrik/micha) — Client lib for Telegram bot api ☆`34`

### Chat APIs

*   [bwmarrin/discordgo (⭐6k)](https://github.com/bwmarrin/discordgo) — (Golang) Go bindings for Discord ☆`5,971`
*   [slack-go/slack (⭐5k)](https://github.com/slack-go/slack) — Slack API in Go ☆`4,955`
*   [huandu/facebook (⭐1.5k)](https://github.com/huandu/facebook) — A Facebook Graph API SDK For Go. ☆`1,480`
*   [chyroc/lark (⭐476)](https://github.com/chyroc/lark) — Lark/Feishu Open API SDK ☆`476`
*   [go-lark/lark (⭐246)](https://github.com/go-lark/lark) — Feishu/Lark SDK for Go ☆`246`
*   [switchupcb/disgo (⭐115)](https://github.com/switchupcb/disgo) — Next-gen Discord API library ☆`115`

## CLI & Terminal

### Advanced Console UIs

*   [charmbracelet/bubbletea (⭐44k)](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`44,334`
*   [antonmedv/fx (⭐21k)](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,578`
*   [gizak/termui (⭐14k)](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,583`
*   [charmbracelet/lipgloss (⭐12k)](https://github.com/charmbracelet/lipgloss) — Style definitions for nice terminal layouts ☆`11,695`
*   [jroimartin/gocui (⭐11k)](https://github.com/jroimartin/gocui) — Minimalist Go package aimed at creating Console User Interfaces. ☆`10,598`
*   [charmbracelet/bubbles (⭐8.8k)](https://github.com/charmbracelet/bubbles) — TUI components for Bubble Tea ☆`8,798`
*   [pterm/pterm (⭐5.5k)](https://github.com/pterm/pterm) — Modern terminal output library ☆`5,514`
*   [c-bata/go-prompt (⭐5.5k)](https://github.com/c-bata/go-prompt) — Interactive prompts for Go ☆`5,489`
*   [schollz/progressbar (⭐4.7k)](https://github.com/schollz/progressbar) — Thread-safe progress bar ☆`4,691`
*   [guptarohit/asciigraph (⭐3.1k)](https://github.com/guptarohit/asciigraph) — ASCII line graphs in terminal ☆`3,085`
*   [mum4k/termdash (⭐3k)](https://github.com/mum4k/termdash) — Terminal-based dashboard ☆`3,027`
*   [vbauerster/mpb (⭐2.5k)](https://github.com/vbauerster/mpb) — Multi progress bar ☆`2,507`
*   [briandowns/spinner (⭐2.5k)](https://github.com/briandowns/spinner) — Terminal spinner indicators ☆`2,531`
*   [muesli/termenv (⭐2k)](https://github.com/muesli/termenv) — Terminal color support ☆`2,018`
*   [gookit/color (⭐1.6k)](https://github.com/gookit/color) — Terminal color rendering ☆`1,601`
*   [logrusorgru/aurora (⭐1.5k)](https://github.com/logrusorgru/aurora) — ANSI colors for Printf ☆`1,494`
*   [mattn/go-isatty (⭐923)](https://github.com/mattn/go-isatty) — Check if terminal is TTY ☆`923`
*   [mattn/go-colorable (⭐812)](https://github.com/mattn/go-colorable) — Colorable writer for Windows ☆`812`
*   [box-cli-maker/box-cli-maker (⭐647)](https://github.com/box-cli-maker/box-cli-maker) — Render highly customizable boxes in the terminal ☆`647`
*   [Evertras/bubble-table (⭐576)](https://github.com/Evertras/bubble-table) — Table component for Bubble Tea ☆`576`
*   [DMcP89/tinycare-tui (⭐21)](https://github.com/DMcP89/tinycare-tui) — TUI application written in GO inspired by tiny-care-terminal ☆`21`

### Standard CLI

*   [spf13/cobra (⭐44k)](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`44,454`
*   [urfave/cli (⭐24k)](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`24,193`
*   [elves/elvish (⭐6.4k)](https://github.com/elves/elvish) — Scripting shell for Go ☆`6,353`
*   [alecthomas/kingpin (⭐3.6k)](https://github.com/alecthomas/kingpin) — Command-line parser ☆`3,568`
*   [dnote/dnote (⭐3k)](https://github.com/dnote/dnote) — Command-line notebook ☆`3,054`
*   [spf13/pflag (⭐2.8k)](https://github.com/spf13/pflag) — POSIX/GNU-style flags ☆`2,760`
*   [alexflint/go-arg (⭐2.3k)](https://github.com/alexflint/go-arg) — Struct-based argument parsing ☆`2,269`
*   [carapace-sh/carapace-bin (⭐1.9k)](https://github.com/carapace-sh/carapace-bin) — Multi-shell completion binary ☆`1,920`
*   [nanovms/ops (⭐1.5k)](https://github.com/nanovms/ops) — Build and run unikernels ☆`1,509`
*   [carapace-sh/carapace (⭐1.4k)](https://github.com/carapace-sh/carapace) — Multi-shell completion library ☆`1,406`
*   [ddddddO/gtree (⭐357)](https://github.com/ddddddO/gtree) — Generate ASCII tree from Markdown ☆`358`
*   [urfave/sflags (⭐168)](https://github.com/urfave/sflags) — Generate flags from structs ☆`169`
*   [reeflective/readline (⭐146)](https://github.com/reeflective/readline) — Shell library with inputrc ☆`147`
*   [hedzr/cmdr (⭐141)](https://github.com/hedzr/cmdr) — POSIX-compliant CLI parser ☆`141`
*   [reeflective/console (⭐115)](https://github.com/reeflective/console) — Console library for Cobra ☆`116`
*   [hashicorp/cli (⭐42)](https://github.com/hashicorp/cli) — CLI library for Go ☆`43`
*   [dixonwille/wlog (⭐67)](https://github.com/dixonwille/wlog) — Cross-platform logging ☆`67`
*   [DavidGamba/go-getoptions (⭐59)](https://github.com/DavidGamba/go-getoptions) — Command line option parser with completion ☆`59`
*   [carapace-sh/carapace-spec (⭐34)](https://github.com/carapace-sh/carapace-spec) — Multi-shell completion library ☆`34`
*   [jxskiss/mcli (⭐47)](https://github.com/jxskiss/mcli) — Minimal but powerful CLI ☆`47`
*   [sgreben/flagvar (⭐48)](https://github.com/sgreben/flagvar) — CLI argument types for flag ☆`48`
*   [nyaosorg/go-readline-ny (⭐36)](https://github.com/nyaosorg/go-readline-ny) — Readline for Go ☆`36`

## Concurrency

### Actor Model

*   [asynkron/protoactor-go (⭐5.5k)](https://github.com/asynkron/protoactor-go) — Ultra fast distributed actors for Go ☆`5,491`
*   [ergo-services/ergo (⭐4.6k)](https://github.com/ergo-services/ergo) — Actor framework with network transparency ☆`4,623`
*   [anthdm/hollywood (⭐2.3k)](https://github.com/anthdm/hollywood) — Blazingly fast and light-weight Actor engine written in Golang ☆`2,325`
*   [Tochemey/goakt (⭐369)](https://github.com/Tochemey/goakt) — Distributed actor framework ☆`369`

### Goroutines

*   [panjf2000/ants (⭐14k)](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,488`
*   [benmanns/goworker (⭐2.8k)](https://github.com/benmanns/goworker) — Resque-compatible background worker ☆`2,846`
*   [alitto/pond (⭐2.2k)](https://github.com/alitto/pond) — High-performance worker pool ☆`2,185`
*   [destel/rill (⭐1.8k)](https://github.com/destel/rill) — Channel-based concurrency toolkit ☆`1,848`
*   [xxjwxc/gowp (⭐515)](https://github.com/xxjwxc/gowp) — Goroutine worker pool ☆`515`
*   [vladopajic/go-actor (⭐307)](https://github.com/vladopajic/go-actor) — Actor model library ☆`307`
*   [timandy/routine (⭐291)](https://github.com/timandy/routine) — ThreadLocal for Go ☆`291`
*   [reugn/async (⭐312)](https://github.com/reugn/async) — Async computation package ☆`312`
*   [mborders/artifex (⭐214)](https://github.com/mborders/artifex) — In-memory job queue ☆`214`

### Stream Processing

*   [reugn/go-streams (⭐2.2k)](https://github.com/reugn/go-streams) — Stream processing library ☆`2,172`
*   [Breeze0806/go-etl (⭐191)](https://github.com/Breeze0806/go-etl) — ETL toolset for Go ☆`191`
*   [mariomac/gostream (⭐172)](https://github.com/mariomac/gostream) — Java Streams port for Go ☆`172`
*   [fulminate-io/machine (⭐169)](https://github.com/fulminate-io/machine) — Machine is a workflow/pipeline library for processing data ☆`169`
*   [rulego/streamsql (⭐61)](https://github.com/rulego/streamsql) — SQL-based stream processing for IoT ☆`61`

## Configuration

*   [spf13/viper (⭐30k)](https://github.com/spf13/viper) — Go configuration with fangs ☆`30,430`
*   [caarlos0/env (⭐6.3k)](https://github.com/caarlos0/env) — Parse environment variables to structs ☆`6,285`
*   [knadh/koanf (⭐4.2k)](https://github.com/knadh/koanf) — Lightweight config management ☆`4,156`
*   [alecthomas/kong (⭐3.2k)](https://github.com/alecthomas/kong) — Command-line parser for Go ☆`3,156`
*   [adrg/xdg (⭐1k)](https://github.com/adrg/xdg) — XDG Base Directory implementation ☆`1,012`
*   [cristalhq/aconfig (⭐639)](https://github.com/cristalhq/aconfig) — Simple config loader ☆`639`
*   [gookit/config (⭐586)](https://github.com/gookit/config) — Config management with formats ☆`586`
*   [nil-go/konf (⭐391)](https://github.com/nil-go/konf) — Simplest config loader for Go ☆`391`
*   [kkyr/fig (⭐381)](https://github.com/kkyr/fig) — Minimalist config library ☆`381`
*   [hjson/hjson-go (⭐356)](https://github.com/hjson/hjson-go) — Hjson for Go ☆`356`
*   [vrischmann/envconfig (⭐250)](https://github.com/vrischmann/envconfig) — Env config library ☆`250`
*   [chaindead/zerocfg (⭐200)](https://github.com/chaindead/zerocfg) — Zero-effort config management ☆`200`
*   [beatlabs/harvester (⭐135)](https://github.com/beatlabs/harvester) — Watch and notify config changes ☆`135`
*   [gurkankaymak/hocon (⭐92)](https://github.com/gurkankaymak/hocon) — HOCON config library for Go ☆`92`
*   [BoRuDar/configuration (⭐108)](https://github.com/BoRuDar/configuration) — Set struct fields from env, flags, files ☆`108`
*   [omeid/uconfig (⭐75)](https://github.com/omeid/uconfig) — Lightweight config management ☆`75`
*   [PaddleHQ/go-aws-ssm (⭐66)](https://github.com/PaddleHQ/go-aws-ssm) — AWS System Manager interface ☆`66`
*   [go-simpler/env (⭐80)](https://github.com/go-simpler/env) — Load env vars to struct ☆`80`
*   [num30/config (⭐61)](https://github.com/num30/config) — Declarative configuration ☆`61`
*   [wkhere/bcl (⭐34)](https://github.com/wkhere/bcl) — Basic Configuration Language ☆`34`
*   [sakirsensoy/genv (⭐45)](https://github.com/sakirsensoy/genv) — Easy env variable handling ☆`45`
*   [greencoda/confiq (⭐39)](https://github.com/greencoda/confiq) — Config struct decoder ☆`39`
*   [nasermirzaei89/env (⭐23)](https://github.com/nasermirzaei89/env) — Zero-dep env package ☆`23`
*   [deatil/go-array (⭐23)](https://github.com/deatil/go-array) — Read/set map, slice, JSON data ☆`23`
*   [romshark/yamagiconf (⭐19)](https://github.com/romshark/yamagiconf) — YAML config framework ☆`19`
*   [atelpis/enflag (⭐39)](https://github.com/atelpis/enflag) — Unify env and flag parsing ☆`39`

## Data Formats

### JSON

*   [tidwall/gjson (⭐16k)](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,551`
*   [bytedance/sonic (⭐9.6k)](https://github.com/bytedance/sonic) — A blazingly fast JSON serializing & deserializing library ☆`9,572`
*   [valyala/fastjson (⭐2.5k)](https://github.com/valyala/fastjson) — Fast JSON parser for Go ☆`2,465`
*   [ohler55/ojg (⭐953)](https://github.com/ohler55/ojg) — Optimized JSON for Go ☆`953`
*   [wI2L/jsondiff (⭐632)](https://github.com/wI2L/jsondiff) — JSON Patch diff computation ☆`632`
*   [spyzhov/ajson (⭐291)](https://github.com/spyzhov/ajson) — Abstract JSON with JSONPath ☆`291`
*   [Andrew-M-C/go.jsonvalue (⭐203)](https://github.com/Andrew-M-C/go.jsonvalue) — Unstructured JSON solution ☆`203`
*   [romshark/jscan (⭐101)](https://github.com/romshark/jscan) — High-performance JSON iterator ☆`101`
*   [iOliverNguyen/ujson (⭐85)](https://github.com/iOliverNguyen/ujson) — Minimal JSON parser ☆`85`
*   [simonnilsson/ask (⭐58)](https://github.com/simonnilsson/ask) — A Go package that provides a simple way of accessing nested properties in maps and slices. ☆`58`
*   [neilotoole/jsoncolor (⭐54)](https://github.com/neilotoole/jsoncolor) — Colorized JSON output ☆`54`

### Serialization

*   [ugorji/go (⭐2k)](https://github.com/ugorji/go) — Codec for msgpack, cbor, json ☆`1,957`
*   [linkedin/goavro (⭐1.1k)](https://github.com/linkedin/goavro) — Goavro is a library that encodes and decodes Avro data. ☆`1,069`
*   [fxamacker/cbor (⭐1.1k)](https://github.com/fxamacker/cbor) — CBOR codec with extensions ☆`1,077`
*   [jszwec/csvutil (⭐1k)](https://github.com/jszwec/csvutil) — CSV to struct mapping ☆`1,033`
*   [ghostiam/binstruct (⭐114)](https://github.com/ghostiam/binstruct) — Binary to struct decoder ☆`114`
*   [o1egl/fwencoder (⭐27)](https://github.com/o1egl/fwencoder) — Fixed width file parser ☆`27`
*   [tiendc/go-csvlib (⭐18)](https://github.com/tiendc/go-csvlib) — High-level CSV library ☆`18`

### XML

*   [miku/zek (⭐821)](https://github.com/miku/zek) — Generate Go struct from XML ☆`821`
*   [antchfx/xpath (⭐742)](https://github.com/antchfx/xpath) — XPath for Go ☆`742`
*   [antchfx/xmlquery (⭐490)](https://github.com/antchfx/xmlquery) — XPath XML query ☆`490`

## Data Structures

### Bit-packing and Compression

*   [RoaringBitmap/roaring (⭐2.9k)](https://github.com/RoaringBitmap/roaring) — Compressed bitmaps for Go ☆`2,918`
*   [iancmcc/bingo (⭐52)](https://github.com/iancmcc/bingo) — Zero-allocation binary encoding ☆`52`

### Bloom and Cuckoo Filters

*   [bits-and-blooms/bloom (⭐2.8k)](https://github.com/bits-and-blooms/bloom) — Bloom filter implementation ☆`2,804`
*   [tylertreat/BoomFilters (⭐1.6k)](https://github.com/tylertreat/BoomFilters) — Probabilistic data structures for streams ☆`1,646`
*   [OldPanda/bloomfilter (⭐21)](https://github.com/OldPanda/bloomfilter) — Bloom filter compatible with pybloom ☆`21`

### Maps

*   [mhmtszr/concurrent-swiss-map (⭐259)](https://github.com/mhmtszr/concurrent-swiss-map) — Thread-safe concurrent hash map ☆`259`
*   [lrita/cmap (⭐104)](https://github.com/lrita/cmap) — a thread-safe concurrent map for go ☆`104`
*   [goradd/maps (⭐55)](https://github.com/goradd/maps) — Generic map library for Go ☆`55`
*   [srfrog/dict (⭐48)](https://github.com/srfrog/dict) — Python-like dictionaries for Go ☆`48`

### Miscellaneous

*   [Workiva/go-datastructures (⭐7.9k)](https://github.com/Workiva/go-datastructures) — Performant, threadsafe data structures ☆`7,947`
*   [deckarep/golang-set (⭐4.7k)](https://github.com/deckarep/golang-set) — Generic set type for Go ☆`4,701`
*   [bits-and-blooms/bitset (⭐1.5k)](https://github.com/bits-and-blooms/bitset) — Go package implementing bitsets ☆`1,511`
*   [liyue201/gostl (⭐1.1k)](https://github.com/liyue201/gostl) — Data structures modeled on C++ STL ☆`1,139`
*   [axiomhq/hyperloglog (⭐1k)](https://github.com/axiomhq/hyperloglog) — HyperLogLog with optimizations ☆`1,045`
*   [kelindar/bitmap (⭐381)](https://github.com/kelindar/bitmap) — Simple dense bitmap index in Go with binary operators ☆`381`
*   [barweiss/go-tuple (⭐100)](https://github.com/barweiss/go-tuple) — Go 1.18+ generic tuple ☆`100`
*   [seiflotfy/count-min-log (⭐70)](https://github.com/seiflotfy/count-min-log) — Go implementation of Count-Min-Log ☆`70`
*   [s0rg/quadtree (⭐41)](https://github.com/s0rg/quadtree) — Generic, zero-alloc, 100%-test covered Quadtree for golang ☆`41`
*   [nazar256/parapipe (⭐38)](https://github.com/nazar256/parapipe) — Paralleling pipeline ☆`38`
*   [StudioSol/set (⭐30)](https://github.com/StudioSol/set) — Simple set data structure ☆`30`
*   [bobg/merkle (⭐23)](https://github.com/bobg/merkle) — Merkle hash trees ☆`23`

### Queues

*   [gammazero/deque (⭐787)](https://github.com/gammazero/deque) — Fast ring-buffer deque (double-ended queue) ☆`787`
*   [adrianbrad/queue (⭐362)](https://github.com/adrianbrad/queue) — Multiple queue implementations ☆`362`
*   [mikestefanello/backlite (⭐151)](https://github.com/mikestefanello/backlite) — SQLite-backed task queues ☆`151`
*   [embano1/memlog (⭐142)](https://github.com/embano1/memlog) — A Kafka log inspired in-memory and append-only data structure ☆`142`

## Databases

### Caches

*   [golang/groupcache (⭐13k)](https://github.com/golang/groupcache) — Distributed cache library ☆`13,337`
*   [dgraph-io/ristretto (⭐7k)](https://github.com/dgraph-io/ristretto) — A high performance memory-bound Go cache ☆`6,976`
*   [eko/gocache (⭐2.9k)](https://github.com/eko/gocache) — Multi-store caching library ☆`2,882`
*   [maypok86/otter (⭐2.7k)](https://github.com/maypok86/otter) — A high performance caching library for Go ☆`2,663`
*   [VictoriaMetrics/fastcache (⭐2.4k)](https://github.com/VictoriaMetrics/fastcache) — Fast in-memory cache for Go ☆`2,373`
*   [jellydator/ttlcache (⭐1.3k)](https://github.com/jellydator/ttlcache) — An in-memory cache with item expiration and generics ☆`1,273`
*   [viccon/sturdyc (⭐1.3k)](https://github.com/viccon/sturdyc) — Caching with advanced concurrency ☆`1,282`
*   [EchoVault/SugarDB (⭐537)](https://github.com/EchoVault/SugarDB) — Embeddable and distributed in-memory alternative to Redis. ☆`536`
*   [Yiling-J/theine-go (⭐379)](https://github.com/Yiling-J/theine-go) — high performance in-memory cache ☆`379`
*   [elastic/go-freelru (⭐272)](https://github.com/elastic/go-freelru) — GC-less, fast and generic LRU cache for Go ☆`272`
*   [samber/hot (⭐265)](https://github.com/samber/hot) — In-memory caching library for read-intensive Go applications ☆`269`
*   [naughtygopher/pocache (⭐236)](https://github.com/naughtygopher/pocache) — Preemptive optimistic caching ☆`236`
*   [OrlovEvgeny/go-mcache (⭐107)](https://github.com/OrlovEvgeny/go-mcache) — Sharded in-memory KV cache ☆`107`
*   [erni27/imcache (⭐123)](https://github.com/erni27/imcache) — A zero-dependency generic in-memory cache Go library ☆`123`
*   [mdaliyan/icache (⭐23)](https://github.com/mdaliyan/icache) — High-performance generic cache ☆`23`

### Database Schema Migration

*   [golang-migrate/migrate (⭐19k)](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,813`
*   [bytebase/bytebase (⭐14k)](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`14,375`
*   [pressly/goose (⭐11k)](https://github.com/pressly/goose) — A database migration tool. Supports SQL migrations and Go functions. ☆`11,320`
*   [ariga/atlas (⭐8.6k)](https://github.com/ariga/atlas) — Declarative schema migrations with schema-as-code workflows ☆`8,634`
*   [amacneil/dbmate (⭐7k)](https://github.com/amacneil/dbmate) — A lightweight, framework-agnostic database migration tool. ☆`7,043`
*   [rubenv/sql-migrate (⭐3.4k)](https://github.com/rubenv/sql-migrate) — SQL schema migration tool for Go. ☆`3,416`
*   [skeema/skeema (⭐1.4k)](https://github.com/skeema/skeema) — Declarative pure-SQL schema management for MySQL and MariaDB ☆`1,375`
*   [go-gormigrate/gormigrate (⭐1.2k)](https://github.com/go-gormigrate/gormigrate) — Minimalistic database migration helper for Gorm ORM ☆`1,173`
*   [sunary/sqlize (⭐125)](https://github.com/sunary/sqlize) — SQL parsing and migration toolkit ☆`125`
*   [robinjoseph08/go-pg-migrations (⭐87)](https://github.com/robinjoseph08/go-pg-migrations) — A Go package to help write migrations with go-pg/pg. ☆`87`
*   [adlio/schema (⭐44)](https://github.com/adlio/schema) — Embedded schema migration package for Go ☆`44`
*   [khezen/avro (⭐49)](https://github.com/khezen/avro) — Apache AVRO for go ☆`49`
*   [muir/libschema (⭐19)](https://github.com/muir/libschema) — database schema migrations on a per-library basis \[Go] ☆`19`

### Database Tools

*   [vitessio/vitess (⭐21k)](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`21,220`
*   [sosedoff/pgweb (⭐9.5k)](https://github.com/sosedoff/pgweb) — Cross-platform client for PostgreSQL databases ☆`9,476`
*   [go-mysql-org/go-mysql (⭐5k)](https://github.com/go-mysql-org/go-mysql) — a powerful mysql toolset with Go ☆`4,966`
*   [prest/prest (⭐4.6k)](https://github.com/prest/prest) — PostgreSQL REST API server ☆`4,609`
*   [ContentSquare/chproxy (⭐1.5k)](https://github.com/ContentSquare/chproxy) — Open-Source ClickHouse http proxy and load balancer ☆`1,477`
*   [cybertec-postgresql/pg\_timetable (⭐1.4k)](https://github.com/cybertec-postgresql/pg_timetable) — Advanced PostgreSQL scheduler ☆`1,395`
*   [liweiyi88/onedump (⭐987)](https://github.com/liweiyi88/onedump) — Effortless database administration tool ☆`986`
*   [HDT3213/rdb (⭐621)](https://github.com/HDT3213/rdb) — Redis RDB parser for Go ☆`622`
*   [nikepan/clickhouse-bulk (⭐512)](https://github.com/nikepan/clickhouse-bulk) — Batch inserts for ClickHouse ☆`512`
*   [wesql/wescale (⭐316)](https://github.com/wesql/wescale) — MySQL proxy with read/write split ☆`316`
*   [gatewayd-io/gatewayd (⭐288)](https://github.com/gatewayd-io/gatewayd) — database gateway for building data-driven applications ☆`288`
*   [sj14/dbbench (⭐118)](https://github.com/sj14/dbbench) — Database benchmarking tool ☆`118`
*   [bartventer/gorm-multitenancy (⭐83)](https://github.com/bartventer/gorm-multitenancy) — Multi-tenancy for GORM ☆`83`
*   [kazhuravlev/database-gateway (⭐39)](https://github.com/kazhuravlev/database-gateway) — Safe access to production databases ☆`39`
*   [codingconcepts/dg (⭐46)](https://github.com/codingconcepts/dg) — Generate CSV from data models ☆`46`

### Databases Implemented in Go

*   [prometheus/prometheus (⭐66k)](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`65,724`
*   [milvus-io/milvus (⭐45k)](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`45,620`
*   [pingcap/tidb (⭐40k)](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`40,426`
*   [cockroachdb/cockroach (⭐32k)](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`32,384`
*   [influxdata/influxdb (⭐32k)](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,689`
*   [dolthub/dolt (⭐24k)](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`24,167`
*   [dgraph-io/dgraph (⭐22k)](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,772`
*   [VictoriaMetrics/VictoriaMetrics (⭐18k)](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`17,521`
*   [rqlite/rqlite (⭐18k)](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,675`
*   [dgraph-io/badger (⭐16k)](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,750`
*   [dicedb/dicedb (⭐11k)](https://github.com/dicedb/dicedb) — Low-latency key/value engine on Valkey with storage tiers ☆`10,773`
*   [etcd-io/bbolt (⭐9.7k)](https://github.com/etcd-io/bbolt) — An embedded key/value database for Go. ☆`9,681`
*   [codenotary/immudb (⭐9k)](https://github.com/codenotary/immudb) — Immutable database with SQL ☆`9,019`
*   [cockroachdb/pebble (⭐6k)](https://github.com/cockroachdb/pebble) — RocksDB/LevelDB inspired key-value database in Go ☆`5,993`
*   [rosedblabs/rosedb (⭐4.9k)](https://github.com/rosedblabs/rosedb) — Fast key/value storage engine ☆`4,884`
*   [tidwall/buntdb (⭐4.9k)](https://github.com/tidwall/buntdb) — Embeddable in-memory key/value DB ☆`4,863`
*   [nalgeon/redka (⭐4.6k)](https://github.com/nalgeon/redka) — Redis re-implemented with SQL ☆`4,569`
*   [nutsdb/nutsdb (⭐3.6k)](https://github.com/nutsdb/nutsdb) — Simple embeddable key/value store ☆`3,578`
*   [lindb/lindb (⭐3.1k)](https://github.com/lindb/lindb) — Scalable time-series database ☆`3,067`
*   [lotusdblabs/lotusdb (⭐2.3k)](https://github.com/lotusdblabs/lotusdb) — Key-value database with LSM and B+ tree ☆`2,256`
*   [kelindar/column (⭐1.5k)](https://github.com/kelindar/column) — Columnar in-memory store ☆`1,512`
*   [akrylysov/pogreb (⭐1.4k)](https://github.com/akrylysov/pogreb) — Embedded key-value store for read-heavy workloads written in Go ☆`1,352`
*   [objectbox/objectbox-go (⭐1.3k)](https://github.com/objectbox/objectbox-go) — Embedded database for Go ☆`1,273`
*   [couchbase/moss (⭐1k)](https://github.com/couchbase/moss) — Simple, fast key-val storage ☆`1,015`
*   [claygod/transaction (⭐139)](https://github.com/claygod/transaction) — Embedded database for accounts transactions. ☆`139`
*   [xgzlucario/rotom (⭐42)](https://github.com/xgzlucario/rotom) — Tiny Redis server in Go ☆`42`

### Distributed Storage

*   [seaweedfs/seaweedfs (⭐34k)](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`34,038`
*   [juicedata/juicefs (⭐14k)](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`14,312`

### Interfaces to Multiple Backends

*   [philippgille/gokv (⭐828)](https://github.com/philippgille/gokv) — Key-value store abstraction ☆`828`
*   [avito-tech/go-transaction-manager (⭐414)](https://github.com/avito-tech/go-transaction-manager) — Transaction manager for Go ☆`414`
*   [viant/dsc (⭐37)](https://github.com/viant/dsc) — Datastore Connectivity in go ☆`37`
*   [fogfish/dynamo (⭐24)](https://github.com/fogfish/dynamo) — Generic Golang Key/Value trait for AWS storage services ☆`24`

### NoSQL Database Drivers

*   [redis/go-redis (⭐22k)](https://github.com/redis/go-redis) — Redis Go client ☆`22,222`
*   [gomodule/redigo (⭐9.9k)](https://github.com/gomodule/redigo) — Go client for Redis ☆`9,857`
*   [mongodb/mongo-go-driver (⭐8.5k)](https://github.com/mongodb/mongo-go-driver) — The Official Golang driver for MongoDB ☆`8,538`
*   [bradfitz/gomemcache (⭐1.9k)](https://github.com/bradfitz/gomemcache) — Go Memcached client library #golang ☆`1,881`
*   [qiniu/qmgo (⭐1.4k)](https://github.com/qiniu/qmgo) — Go driver for MongoDB ☆`1,357`
*   [Kamva/mgm (⭐763)](https://github.com/Kamva/mgm) — MongoDB ODM for Go based on official driver ☆`763`
*   [aerospike/aerospike-client-go (⭐459)](https://github.com/aerospike/aerospike-client-go) — Aerospike Client Go ☆`459`
*   [couchbase/gocb (⭐377)](https://github.com/couchbase/gocb) — The Couchbase Go SDK ☆`377`
*   [go-kivik/kivik (⭐344)](https://github.com/go-kivik/kivik) — CouchDB client interface ☆`344`
*   [couchbase/go-couchbase (⭐323)](https://github.com/couchbase/go-couchbase) — Couchbase client in Go ☆`323`
*   [chenmingyong0423/go-mongox (⭐221)](https://github.com/chenmingyong0423/go-mongox) — MongoDB driver wrapper with generics ☆`221`
*   [aliexpressru/gomemcached (⭐23)](https://github.com/aliexpressru/gomemcached) — Binary Memcached client with sharding ☆`23`
*   [btnguyen2k/gocosmos (⭐22)](https://github.com/btnguyen2k/gocosmos) — Go database/sql driver for Azure Cosmos DB SQL API ☆`22`

### ORM

*   [go-gorm/gorm (⭐40k)](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,915`
*   [ent/ent (⭐17k)](https://github.com/ent/ent) — An entity framework for Go ☆`17,170`
*   [aarondl/sqlboiler (⭐7k)](https://github.com/aarondl/sqlboiler) — Generate a Go ORM tailored to your database schema. ☆`6,990`
*   [uptrace/bun (⭐4.9k)](https://github.com/uptrace/bun) — SQL-first Golang ORM ☆`4,929`
*   [upper/db (⭐3.7k)](https://github.com/upper/db) — Data access layer for databases ☆`3,661`
*   [stephenafamo/bob (⭐1.8k)](https://github.com/stephenafamo/bob) — SQL builder with ORM generator ☆`1,769`
*   [huandu/go-sqlbuilder (⭐1.7k)](https://github.com/huandu/go-sqlbuilder) — SQL builder with zero-config ORM ☆`1,724`
*   [go-rel/rel (⭐786)](https://github.com/go-rel/rel) — Modern ORM for Golang ☆`787`
*   [hashicorp/go-dbw (⭐18)](https://github.com/hashicorp/go-dbw) — A simple package that encapsulates database operations. ☆`18`
*   [FrancoLiberali/cql (⭐18)](https://github.com/FrancoLiberali/cql) — CQL: Compiled Query Language ☆`18`

### Query Language

*   [99designs/gqlgen (⭐11k)](https://github.com/99designs/gqlgen) — go generate based graphql server library ☆`10,749`
*   [TomWright/dasel (⭐8k)](https://github.com/TomWright/dasel) — Query and modify data formats ☆`8,016`
*   [graph-gophers/graphql-go (⭐4.8k)](https://github.com/graph-gophers/graphql-go) — GraphQL server with a focus on ease of use ☆`4,759`
*   [hashicorp/mql (⭐67)](https://github.com/hashicorp/mql) — Model Query Language (mql) is a query language for your database models. ☆`67`
*   [bhmj/jsonslice (⭐92)](https://github.com/bhmj/jsonslice) — json slicer ☆`92`
*   [ccbrown/api-fu (⭐58)](https://github.com/ccbrown/api-fu) — A collection of Go packages for creating robust GraphQL APIs ☆`58`
*   [AsaiYusuke/jsonpath (⭐32)](https://github.com/AsaiYusuke/jsonpath) — JSONPath query library ☆`32`

### Relational Database Drivers

*   [go-sql-driver/mysql (⭐15k)](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,278`
*   [jackc/pgx (⭐14k)](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`14,130`
*   [denisenkom/go-mssqldb (⭐1.9k)](https://github.com/denisenkom/go-mssqldb) — Microsoft SQL server driver written in go language ☆`1,883`
*   [ncruces/go-sqlite3 (⭐1.1k)](https://github.com/ncruces/go-sqlite3) — Go bindings to SQLite using wasm2go ☆`1,086`
*   [godror/godror (⭐596)](https://github.com/godror/godror) — GO DRiver for ORacle DB ☆`596`
*   [cvilsmeier/sqinn-go (⭐537)](https://github.com/cvilsmeier/sqinn-go) — Golang SQLite without cgo ☆`538`
*   [VinGarcia/ksql (⭐360)](https://github.com/VinGarcia/ksql) — A Simple and Powerful Golang SQL Library ☆`360`
*   [surrealdb/surrealdb.go (⭐316)](https://github.com/surrealdb/surrealdb.go) — SurrealDB SDK for Golang ☆`316`
*   [nakagami/firebirdsql (⭐266)](https://github.com/nakagami/firebirdsql) — Firebird RDBMS sql driver for Go (golang) ☆`266`
*   [ydb-platform/ydb-go-sdk (⭐181)](https://github.com/ydb-platform/ydb-go-sdk) — Pure Go native and database/sql driver for YDB ☆`181`
*   [rqlite/gorqlite (⭐187)](https://github.com/rqlite/gorqlite) — A Go client for rqlite, the distributed database built on SQLite ☆`187`
*   [apache/calcite-avatica-go (⭐126)](https://github.com/apache/calcite-avatica-go) — Apache Calcite Go ☆`126`

### SQL Query Builders

*   [sqlc-dev/sqlc (⭐18k)](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`18,161`
*   [xo/dbtpl (⭐3.9k)](https://github.com/xo/dbtpl) — Generate Go code for databases ☆`3,895`
*   [go-jet/jet (⭐3.8k)](https://github.com/go-jet/jet) — Type-safe SQL builder with codegen ☆`3,776`
*   [lqs/sqlingo (⭐455)](https://github.com/lqs/sqlingo) — A lightweight DSL & ORM which helps you to write SQL in Go. ☆`455`
*   [arthurkushman/buildsqlx (⭐188)](https://github.com/arthurkushman/buildsqlx) — Go database query builder library for PostgreSQL ☆`188`
*   [nullism/bqb (⭐194)](https://github.com/nullism/bqb) — Lightweight query builder ☆`194`
*   [JiveGroup/FluentSQL (⭐18)](https://github.com/JiveGroup/FluentSQL) — Fluent SQL - flexible and powerful SQL string builder ☆`18`

### Search and Analytic Databases

*   [elastic/go-elasticsearch (⭐6.1k)](https://github.com/elastic/go-elasticsearch) — The official Go client for Elasticsearch ☆`6,061`
*   [ClickHouse/clickhouse-go (⭐3.3k)](https://github.com/ClickHouse/clickhouse-go) — Golang driver for ClickHouse ☆`3,326`
*   [sourcegraph/zoekt (⭐1.8k)](https://github.com/sourcegraph/zoekt) — Fast trigram-based code search ☆`1,819`
*   [sdqri/effdsl (⭐34)](https://github.com/sdqri/effdsl) — Elasticsearch query builder for golang ☆`34`

## DevOps & Build

### Backup

*   [restic/restic (⭐35k)](https://github.com/restic/restic) — Fast, secure backup program ☆`35,486`
*   [gilbertchen/duplicacy (⭐5.7k)](https://github.com/gilbertchen/duplicacy) — Cloud backup tool ☆`5,668`

### Build Automation

*   [air-verse/air (⭐24k)](https://github.com/air-verse/air) — Live reload for Go apps ☆`23,874`
*   [go-task/task (⭐16k)](https://github.com/go-task/task) — Fast cross-platform build tool inspired by Make ☆`15,959`
*   [joerdav/xc (⭐1.4k)](https://github.com/joerdav/xc) — Markdown defined task runner. ☆`1,401`
*   [goyek/goyek (⭐696)](https://github.com/goyek/goyek) — Task automation Go library ☆`696`
*   [flowexec/flow (⭐136)](https://github.com/flowexec/flow) — Local-first developer automation platform — workflows, secrets, templates, and more. ☆`136`

### CI/CD

*   [harness/harness (⭐38k)](https://github.com/harness/harness) — End-to-end developer platform ☆`37,799`
*   [woodpecker-ci/woodpecker (⭐7.7k)](https://github.com/woodpecker-ci/woodpecker) — Simple, powerful CI/CD engine ☆`7,673`
*   [ovh/cds (⭐4.8k)](https://github.com/ovh/cds) — Enterprise CI/CD platform ☆`4,832`
*   [raviqqe/muffet (⭐2.6k)](https://github.com/raviqqe/muffet) — Fast website link checker ☆`2,611`
*   [pipe-cd/pipecd (⭐1.3k)](https://github.com/pipe-cd/pipecd) — The One CD for All {applications, platforms, operations} ☆`1,340`
*   [jenkins-zh/jenkins-cli (⭐428)](https://github.com/jenkins-zh/jenkins-cli) — Jenkins CLI allows you to manage your Jenkins in an easy way ☆`428`
*   [vladopajic/go-test-coverage (⭐236)](https://github.com/vladopajic/go-test-coverage) — Report test coverage threshold issues ☆`236`
*   [appleboy/drone-scp (⭐174)](https://github.com/appleboy/drone-scp) — Copy files via SSH for Drone ☆`174`
*   [nikogura/gomason (⭐69)](https://github.com/nikogura/gomason) — A tool for testing, building, signing, and publishing binaries. ☆`69`
*   [appleboy/drone-jenkins (⭐43)](https://github.com/appleboy/drone-jenkins) — Drone plugin for trigger Jenkins jobs. ☆`43`

### Containers

*   [moby/moby (⭐72k)](https://github.com/moby/moby) — Container ecosystem components ☆`72,013`
*   [traefik/traefik (⭐64k)](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`64,443`
*   [ko-build/ko (⭐8.5k)](https://github.com/ko-build/ko) — Build and deploy Go applications ☆`8,492`
*   [s0rg/decompose (⭐139)](https://github.com/s0rg/decompose) — Reverse-engineering tool for docker environments ☆`139`
*   [x1unix/docker-go-mingw (⭐55)](https://github.com/x1unix/docker-go-mingw) — Docker for Go with MinGW toolchain ☆`55`

### DevOps Utilities

*   [go-gitea/gitea (⭐57k)](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`57,351`
*   [TwiN/gatus (⭐12k)](https://github.com/TwiN/gatus) — Developer-oriented status page with alerting ☆`11,799`
*   [bitfield/script (⭐7k)](https://github.com/bitfield/script) — Making it easy to write shell-like scripts in Go ☆`7,019`
*   [fleetdm/fleet (⭐6.7k)](https://github.com/fleetdm/fleet) — Open device management ☆`6,703`
*   [taubyte/tau (⭐5.1k)](https://github.com/taubyte/tau) — Fullstack Workspace for Humans & Machines ☆`5,110`
*   [megaease/easeprobe (⭐2.3k)](https://github.com/megaease/easeprobe) — Service health monitoring tool ☆`2,295`
*   [ajvb/kala (⭐2.2k)](https://github.com/ajvb/kala) — Modern Job Scheduler ☆`2,155`
*   [gabrie30/ghorg (⭐2.1k)](https://github.com/gabrie30/ghorg) — Clone entire GitHub orgs ☆`2,115`
*   [sanbornm/go-selfupdate (⭐1.7k)](https://github.com/sanbornm/go-selfupdate) — Enable your Go applications to self update ☆`1,698`
*   [yusufcanb/tlm (⭐1.5k)](https://github.com/yusufcanb/tlm) — Local CLI Copilot, powered by Ollama. ☆`1,488`
*   [ovh/utask (⭐1.4k)](https://github.com/ovh/utask) — Automation engine with YAML config ☆`1,394`
*   [TimothyYe/skm (⭐1.1k)](https://github.com/TimothyYe/skm) — A simple and powerful SSH keys manager ☆`1,077`
*   [scaleway/scaleway-cli (⭐990)](https://github.com/scaleway/scaleway-cli) — Command Line Interface for Scaleway ☆`991`
*   [alexliesenfeld/health (⭐836)](https://github.com/alexliesenfeld/health) — A simple and flexible health check library for Go. ☆`836`
*   [kool-dev/kool (⭐724)](https://github.com/kool-dev/kool) — Dev to cloud web apps made easy ☆`724`
*   [kevincobain2000/gobrew (⭐428)](https://github.com/kevincobain2000/gobrew) — Go version manager without root ☆`428`
*   [appleboy/easyssh-proxy (⭐348)](https://github.com/appleboy/easyssh-proxy) — Simple SSH protocol implementation ☆`348`
*   [xitonix/trubka (⭐337)](https://github.com/xitonix/trubka) — A CLI tool for Kafka ☆`337`
*   [thevxn/dish (⭐280)](https://github.com/thevxn/dish) — A simple, remotely configurable monitoring service. ☆`280`
*   [jkaninda/goma-gateway (⭐185)](https://github.com/jkaninda/goma-gateway) — Lightweight API gateway and proxy ☆`185`
*   [datarootsio/tf-profile (⭐163)](https://github.com/datarootsio/tf-profile) — Profile Terraform runs ☆`163`
*   [kazhuravlev/healthcheck (⭐24)](https://github.com/kazhuravlev/healthcheck) — Readiness probes for Kubernetes application ☆`24`

### Infrastructure

*   [hashicorp/packer (⭐16k)](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,754`
*   [pomerium/pomerium (⭐4.9k)](https://github.com/pomerium/pomerium) — Pomerium is an identity and context-aware access proxy. ☆`4,950`
*   [peak/s5cmd (⭐4.2k)](https://github.com/peak/s5cmd) — Parallel S3 and local filesystem execution tool. ☆`4,161`
*   [aptly-dev/aptly (⭐2.9k)](https://github.com/aptly-dev/aptly) — aptly - Debian repository management tool ☆`2,862`
*   [KusionStack/kusion (⭐1.3k)](https://github.com/KusionStack/kusion) — Declarative platform orchestrator ☆`1,316`
*   [oxyno-zeta/s3-proxy (⭐482)](https://github.com/oxyno-zeta/s3-proxy) — S3 reverse proxy with auth ☆`482`

### Kubernetes

*   [kubernetes/kubernetes (⭐124k)](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`124,477`
*   [k3s-io/k3s (⭐34k)](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`33,728`
*   [kubernetes/minikube (⭐32k)](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`32,027`
*   [kubernetes-sigs/kind (⭐15k)](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,414`
*   [kubeshark/kubeshark (⭐12k)](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`12,037`
*   [flannel-io/flannel (⭐9.5k)](https://github.com/flannel-io/flannel) — Network fabric for containers ☆`9,522`
*   [getanteon/anteon (⭐8.5k)](https://github.com/getanteon/anteon) — eBPF Kubernetes monitoring tool ☆`8,522`
*   [kubevela/kubevela (⭐7.9k)](https://github.com/kubevela/kubevela) — The Modern Application Platform. ☆`7,879`
*   [k3d-io/k3d (⭐6.5k)](https://github.com/k3d-io/k3d) — Little helper to run CNCF's k3s in Docker ☆`6,516`
*   [stefanprodan/podinfo (⭐6k)](https://github.com/stefanprodan/podinfo) — Go microservice template for Kubernetes ☆`5,976`
*   [apecloud/kubeblocks (⭐3.1k)](https://github.com/apecloud/kubeblocks) — Kubernetes operator for databases ☆`3,102`
*   [kubenetworks/kubevpn (⭐1.4k)](https://github.com/kubenetworks/kubevpn) — Connect to Kubernetes cluster network ☆`1,364`
*   [abahmed/kwatch (⭐1k)](https://github.com/abahmed/kwatch) — monitor & detect crashes in your Kubernetes(K8s) cluster instantly ☆`1,014`
*   [getanteon/alaz (⭐717)](https://github.com/getanteon/alaz) — eBPF agent for K8s observability ☆`716`

### Load Testing

*   [grafana/k6 (⭐31k)](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`31,248`
*   [tsenart/vegeta (⭐25k)](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`25,144`
*   [codesenberg/bombardier (⭐6.8k)](https://github.com/codesenberg/bombardier) — Fast cross-platform HTTP benchmarking tool written in Go ☆`6,821`
*   [rogerwelin/cassowary (⭐812)](https://github.com/rogerwelin/cassowary) — Modern cross-platform HTTP load-testing tool written in Go ☆`812`

## Email

*   [axllent/mailpit (⭐10k)](https://github.com/axllent/mailpit) — An email and SMTP testing tool with API for developers ☆`10,098`
*   [foxcpp/maddy (⭐6.1k)](https://github.com/foxcpp/maddy) — Composable all-in-one mail server. ☆`6,063`
*   [mjl-/mox (⭐5.8k)](https://github.com/mjl-/mox) — Modern secure mail server ☆`5,780`
*   [matcornic/hermes (⭐3k)](https://github.com/matcornic/hermes) — Clean HTML email generator ☆`3,024`
*   [AfterShip/email-verifier (⭐1.6k)](https://github.com/AfterShip/email-verifier) — Email verification without sending emails ☆`1,594`
*   [wneessen/go-mail (⭐1.5k)](https://github.com/wneessen/go-mail) — Easy to use, yet comprehensive library for sending mails with Go ☆`1,465`
*   [sendgrid/sendgrid-go (⭐1.1k)](https://github.com/sendgrid/sendgrid-go) — The Official Twilio SendGrid Golang API Library ☆`1,061`
*   [mailgun/mailgun-go (⭐745)](https://github.com/mailgun/mailgun-go) — Go library for the Mailgun API. ☆`745`
*   [emersion/go-message (⭐456)](https://github.com/emersion/go-message) — Internet Message Format library ☆`456`
*   [vanng822/go-premailer (⭐204)](https://github.com/vanng822/go-premailer) — Inline CSS for HTML mail ☆`204`
*   [truemail-rb/truemail-go (⭐135)](https://github.com/truemail-rb/truemail-go) — Email validator via Regex, DNS, SMTP ☆`135`
*   [toorop/go-dkim (⭐99)](https://github.com/toorop/go-dkim) — DKIM package for golang ☆`99`
*   [dimuska139/go-email-normalizer (⭐79)](https://github.com/dimuska139/go-email-normalizer) — Normalize email addresses ☆`79`
*   [valord577/mailx (⭐23)](https://github.com/valord577/mailx) — A library that makes it easier to send email via SMTP. ☆`23`

## Finance & Blockchain

### Blockchain

*   [ethereum/go-ethereum (⭐51k)](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`51,284`
*   [ipfs/kubo (⭐17k)](https://github.com/ipfs/kubo) — IPFS implementation in Go: a daemon that stores and serves content-addressed data, with a CLI, HTTP Gateway, and RPC API ☆`17,100`
*   [lightningnetwork/lnd (⭐8.2k)](https://github.com/lightningnetwork/lnd) — Lightning Network Daemon ☆`8,182`
*   [cosmos/cosmos-sdk (⭐7k)](https://github.com/cosmos/cosmos-sdk) — Framework for building performant, customizable blockchains with native interoperability ☆`7,045`
*   [solana-foundation/solana-go (⭐1.6k)](https://github.com/solana-foundation/solana-go) — Go SDK library and RPC client for the Solana Blockchain ☆`1,574`
*   [gnolang/gno (⭐1.1k)](https://github.com/gnolang/gno) — Interpreted Go virtual machine ☆`1,082`
*   [cometbft/cometbft (⭐915)](https://github.com/cometbft/cometbft) — Byzantine fault-tolerant consensus ☆`915`
*   [ChainSafe/gossamer (⭐455)](https://github.com/ChainSafe/gossamer) — Go Implementation of the Polkadot Host ☆`455`

### Financial

*   [shopspring/decimal (⭐7.5k)](https://github.com/shopspring/decimal) — Arbitrary-precision fixed-point decimal numbers in Go ☆`7,467`
*   [achannarasappa/ticker (⭐6.2k)](https://github.com/achannarasappa/ticker) — Terminal stock and crypto tracker ☆`6,189`
*   [Rhymond/go-money (⭐1.9k)](https://github.com/Rhymond/go-money) — Go implementation of Fowler's Money pattern ☆`1,910`
*   [c9s/bbgo (⭐1.7k)](https://github.com/c9s/bbgo) — The modern cryptocurrency trading bot framework written in Go. ☆`1,661`
*   [formancehq/ledger (⭐1.3k)](https://github.com/formancehq/ledger) — The programmable open source core ledger for fintech ☆`1,341`
*   [bojanz/currency (⭐643)](https://github.com/bojanz/currency) — Currency handling for Go. ☆`643`
*   [moov-io/ach (⭐558)](https://github.com/moov-io/ach) — ACH file reader, writer, validator ☆`558`
*   [invopop/gobl (⭐296)](https://github.com/invopop/gobl) — Go Business Language ☆`296`
*   [govalues/decimal (⭐246)](https://github.com/govalues/decimal) — Correctly rounded decimals for Go ☆`246`
*   [quagmt/udecimal (⭐193)](https://github.com/quagmt/udecimal) — High-precision decimal library ☆`193`
*   [jovandeginste/payme (⭐91)](https://github.com/jovandeginste/payme) — QR code generator (ASCII & PNG) for SEPA payments ☆`91`
*   [nikolaydubina/fpmoney (⭐36)](https://github.com/nikolaydubina/fpmoney) — Fixed-Point Decimal Money ☆`36`
*   [nikolaydubina/fpdecimal (⭐35)](https://github.com/nikolaydubina/fpdecimal) — Fixed-Point Decimals ☆`35`
*   [jokruger/dec128 (⭐50)](https://github.com/jokruger/dec128) — High performance 128-bit fixed-point decimal numbers in go. ☆`50`
*   [govalues/money (⭐56)](https://github.com/govalues/money) — Correctly rounded monetary amounts and exchange rates for Go ☆`56`

### Payment APIs

*   [stripe/stripe-go (⭐2.6k)](https://github.com/stripe/stripe-go) — Stripe API library for Go ☆`2,624`
*   [plutov/paypal (⭐778)](https://github.com/plutov/paypal) — Golang client for PayPal REST API ☆`778`
*   [brunovenceslau/ynab.go (⭐78)](https://github.com/brunovenceslau/ynab.go) — Client for YNAB API ☆`78`

## GUI & Desktop

### GUI

*   [fyne-io/fyne (⭐29k)](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`28,590`
*   [webview/webview (⭐14k)](https://github.com/webview/webview) — Tiny webview library for Go ☆`14,199`
*   [go-vgo/robotgo (⭐11k)](https://github.com/go-vgo/robotgo) — Cross-platform RPA and GUI automation ☆`10,767`
*   [maxence-charriere/go-app (⭐8.9k)](https://github.com/maxence-charriere/go-app) — Build progressive web apps with Go and WASM ☆`8,954`
*   [progrium/darwinkit (⭐5.4k)](https://github.com/progrium/darwinkit) — Native Mac APIs for Go. Previously known as MacDriver ☆`5,431`
*   [cogentcore/core (⭐2.3k)](https://github.com/cogentcore/core) — Powerful GUI framework for Go ☆`2,347`
*   [gotk3/gotk3 (⭐2.2k)](https://github.com/gotk3/gotk3) — Go bindings for GTK3 ☆`2,212`
*   [roblillack/spot (⭐1.3k)](https://github.com/roblillack/spot) — React-like desktop GUI toolkit for Go ☆`1,256`
*   [ncruces/zenity (⭐919)](https://github.com/ncruces/zenity) — Zenity dialogs for Golang, Windows, macOS ☆`919`
*   [energye/energy (⭐610)](https://github.com/energye/energy) — CEF-based GUI framework ☆`610`
*   [AllenDang/cimgui-go (⭐536)](https://github.com/AllenDang/cimgui-go) — Auto generated Go wrapper for Dear ImGui via cimgui ☆`536`
*   [richardwilkes/unison (⭐331)](https://github.com/richardwilkes/unison) — Unified GUI toolkit for Go ☆`331`

### Windows

*   [go-ole/go-ole (⭐1.3k)](https://github.com/go-ole/go-ole) — win32 ole implementation for golang ☆`1,318`
*   [gonutz/d3d9 (⭐164)](https://github.com/gonutz/d3d9) — Direct3D9 wrapper for Go. ☆`164`

## Game Development

### Game Engines

*   [hajimehoshi/ebiten (⭐13k)](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`13,399`
*   [fogleman/nes (⭐5.7k)](https://github.com/fogleman/nes) — NES emulator written in Go. ☆`5,653`
*   [topfreegames/pitaya (⭐2.8k)](https://github.com/topfreegames/pitaya) — Game server with clustering support ☆`2,820`
*   [xiaonanln/goworld (⭐2.7k)](https://github.com/xiaonanln/goworld) — Distributed game server engine ☆`2,720`
*   [gen2brain/raylib-go (⭐2.5k)](https://github.com/gen2brain/raylib-go) — Go bindings for raylib ☆`2,505`
*   [oakmound/oak (⭐1.7k)](https://github.com/oakmound/oak) — A pure Go game engine ☆`1,666`
*   [gopxl/pixel (⭐386)](https://github.com/gopxl/pixel) — A hand-crafted 2D game library in Go. ☆`386`
*   [ungerik/go3d (⭐341)](https://github.com/ungerik/go3d) — A performance oriented 2D/3D math package for Go ☆`341`
*   [mlange-42/ark (⭐295)](https://github.com/mlange-42/ark) — Ark -- Archetype-based Entity Component System (ECS) for Go. ☆`295`
*   [kelindar/tile (⭐225)](https://github.com/kelindar/tile) — 2D grid engine for games ☆`225`
*   [andygeiss/ecs (⭐176)](https://github.com/andygeiss/ecs) — Entity Component System for games ☆`176`
*   [gonutz/prototype (⭐108)](https://github.com/gonutz/prototype) — 2D game prototyping framework ☆`108`
*   [s0rg/fantasyname (⭐44)](https://github.com/s0rg/fantasyname) — RinkWorks fantasy name generator for golang ☆`44`
*   [s0rg/grid (⭐27)](https://github.com/s0rg/grid) — Generic 2D grid ☆`27`

### OpenGL

*   [go-gl/glfw (⭐1.7k)](https://github.com/go-gl/glfw) — Go bindings for GLFW 3 ☆`1,689`
*   [go-gl/gl (⭐1.2k)](https://github.com/go-gl/gl) — Go bindings for OpenGL (generated via glow) ☆`1,203`
*   [go-gl/mathgl (⭐608)](https://github.com/go-gl/mathgl) — A pure Go 3D math library. ☆`608`

## Geospatial

*   [tidwall/tile38 (⭐9.7k)](https://github.com/tidwall/tile38) — Real-time Geospatial and Geofencing ☆`9,714`
*   [golang/geo (⭐1.8k)](https://github.com/golang/geo) — S2 geometry library in Go ☆`1,847`
*   [consbio/mbtileserver (⭐788)](https://github.com/consbio/mbtileserver) — MBTiles server in Go ☆`788`
*   [paulmach/osm (⭐466)](https://github.com/paulmach/osm) — OpenStreetMap data library ☆`466`
*   [uber/h3-go (⭐447)](https://github.com/uber/h3-go) — H3 hexagonal geospatial indexing ☆`447`
*   [airbusgeo/godal (⭐180)](https://github.com/airbusgeo/godal) — GDAL wrapper for Go ☆`181`
*   [peterstace/simplefeatures (⭐172)](https://github.com/peterstace/simplefeatures) — OpenGIS Simple Feature implementation ☆`172`
*   [wroge/wgs84 (⭐142)](https://github.com/wroge/wgs84) — Zero-dep coordinate transformations ☆`142`
*   [pantrif/s2-geojson (⭐37)](https://github.com/pantrif/s2-geojson) — Visualize S2 cells on a map ☆`37`

## Go Tooling

### Compilers

*   [gopherjs/gopherjs (⭐13k)](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,173`
*   [yassinebenaid/bunster (⭐2.7k)](https://github.com/yassinebenaid/bunster) — Compile shell scripts to static binaries. ☆`2,679`
*   [Konstantin8105/c4go (⭐375)](https://github.com/Konstantin8105/c4go) — Transpiling C code to Go code ☆`375`
*   [go2hx/go2hx (⭐153)](https://github.com/go2hx/go2hx) — Import Go libraries in Haxe ☆`153`

### Editor Plugins

*   [fatih/vim-go (⭐16k)](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,219`
*   [visualfc/liteide (⭐7.8k)](https://github.com/visualfc/liteide) — LiteIDE is a simple, open source, cross-platform Go IDE. ☆`7,765`
*   [nsf/gocode (⭐5k)](https://github.com/nsf/gocode) — An autocompletion daemon for the Go programming language ☆`4,991`
*   [golang/vscode-go (⭐4.3k)](https://github.com/golang/vscode-go) — Go extension for Visual Studio Code ☆`4,259`
*   [dominikh/go-mode.el (⭐1.5k)](https://github.com/dominikh/go-mode.el) — Emacs mode for the Go programming language ☆`1,455`
*   [incu6us/goimports-reviser (⭐716)](https://github.com/incu6us/goimports-reviser) — Imports sorting and code formatting tool ☆`716`

### Generate Tools

*   [xuri/xgen (⭐420)](https://github.com/xuri/xgen) — XSD parser and code generator ☆`420`
*   [kazhuravlev/options-gen (⭐110)](https://github.com/kazhuravlev/options-gen) — Codegen for functional options in go projects ☆`110`
*   [g4s8/envdoc (⭐100)](https://github.com/g4s8/envdoc) — Go tool to generate documentation for environment variables ☆`100`

### Go Tools

*   [go-swagger/go-swagger (⭐10k)](https://github.com/go-swagger/go-swagger) — Swagger 2.0 implementation for go ☆`9,990`
*   [ondrajz/go-callvis (⭐6.5k)](https://github.com/ondrajz/go-callvis) — Visualize call graph of a Go program using Graphviz ☆`6,505`
*   [Zxilly/go-size-analyzer (⭐2.2k)](https://github.com/Zxilly/go-size-analyzer) — Analyze compiled Go binary size ☆`2,161`
*   [pointlander/peg (⭐1.1k)](https://github.com/pointlander/peg) — PEG parser generator for Go ☆`1,115`
*   [safedep/vet (⭐1.1k)](https://github.com/safedep/vet) — Protect against malicious open source packages ☆`1,096`
*   [janpfeifer/gonb (⭐1k)](https://github.com/janpfeifer/gonb) — Go notebook kernel for Jupyter ☆`1,037`
*   [alajmo/sake (⭐749)](https://github.com/alajmo/sake) — Task runner for local and remote hosts ☆`749`
*   [goccmack/gocc (⭐663)](https://github.com/goccmack/gocc) — Parser and scanner generator ☆`663`
*   [iyashjayesh/monigo (⭐410)](https://github.com/iyashjayesh/monigo) — Performance monitoring library ☆`410`
*   [becheran/roumon (⭐236)](https://github.com/becheran/roumon) — Universal goroutine monitor using pprof and termui ☆`236`
*   [bitfield/gotestdox (⭐201)](https://github.com/bitfield/gotestdox) — A tool for formatting Go test results as readable documentation ☆`201`
*   [ahmedakef/gotutor (⭐85)](https://github.com/ahmedakef/gotutor) — Online Go Debugger & Visualizer ☆`85`
*   [bobg/modver (⭐22)](https://github.com/bobg/modver) — a tool that helps you obey semantic versioning rules in your Go module ☆`22`
*   [bobg/decouple (⭐37)](https://github.com/bobg/decouple) — find overspecified function parameters in Go code ☆`37`

## Hardware & IoT

### Hardware

*   [shirou/gopsutil (⭐12k)](https://github.com/shirou/gopsutil) — psutil for golang ☆`11,896`
*   [arduino/arduino-cli (⭐5k)](https://github.com/arduino/arduino-cli) — Arduino command line tool ☆`4,986`
*   [jaypipes/ghw (⭐1.9k)](https://github.com/jaypipes/ghw) — Go HardWare discovery/inspection library ☆`1,873`
*   [zcalusic/sysinfo (⭐576)](https://github.com/zcalusic/sysinfo) — Linux system information library ☆`576`

### IoT

*   [hybridgroup/gobot (⭐9.4k)](https://github.com/hybridgroup/gobot) — Robotics and IoT framework ☆`9,446`
*   [lf-edge/ekuiper (⭐1.7k)](https://github.com/lf-edge/ekuiper) — Lightweight data stream processing engine for IoT edge ☆`1,728`
*   [rulego/rulego (⭐1.6k)](https://github.com/rulego/rulego) — Lightweight rule engine framework ☆`1,579`
*   [Edgenesis/shifu (⭐1.4k)](https://github.com/Edgenesis/shifu) — Kubernetes-native IoT gateway ☆`1,431`
*   [e154/smart-home (⭐102)](https://github.com/e154/smart-home) — software package for automation ☆`102`
*   [maxatome/go-vitotrol (⭐24)](https://github.com/maxatome/go-vitotrol) — golang client library to Viessmann Vitotrol web service ☆`24`

## Networking

### Consensus

*   [hashicorp/raft (⭐9.1k)](https://github.com/hashicorp/raft) — Golang implementation of the Raft consensus protocol ☆`9,083`
*   [lni/dragonboat (⭐5.3k)](https://github.com/lni/dragonboat) — Multi-group Raft consensus library ☆`5,324`
*   [etcd-io/raft (⭐1.1k)](https://github.com/etcd-io/raft) — Raft library for maintaining a replicated state machine ☆`1,089`
*   [vadiminshakov/committer (⭐44)](https://github.com/vadiminshakov/committer) — 2PC and 3PC protocols for Go ☆`44`

### DNS

*   [miekg/dns (⭐8.7k)](https://github.com/miekg/dns) — DNS library in Go ☆`8,752`
*   [0xERR0R/blocky (⭐6.8k)](https://github.com/0xERR0R/blocky) — DNS ad-blocker for local networks ☆`6,854`
*   [hashicorp/mdns (⭐1.4k)](https://github.com/hashicorp/mdns) — Simple mDNS client/server library in Golang ☆`1,372`
*   [semihalev/sdns (⭐1.1k)](https://github.com/semihalev/sdns) — High-performance recursive DNS ☆`1,073`
*   [FenkoHQ/dnsmonster (⭐359)](https://github.com/FenkoHQ/dnsmonster) — Passive DNS Capture and Monitoring Toolkit ☆`360`
*   [joeig/go-powerdns (⭐105)](https://github.com/joeig/go-powerdns) — PowerDNS API client for Go (community project) ☆`105`

### Distributed Utilities

*   [luraproject/lura (⭐6.8k)](https://github.com/luraproject/lura) — Ultra-performant API gateway ☆`6,786`
*   [chrislusf/gleam (⭐3.6k)](https://github.com/chrislusf/gleam) — Distributed map/reduce in Go ☆`3,564`
*   [bsm/redislock (⭐1.8k)](https://github.com/bsm/redislock) — Simplified distributed locking implementation using Redis ☆`1,767`
*   [k8gb-io/k8gb (⭐1.3k)](https://github.com/k8gb-io/k8gb) — A cloud native Kubernetes Global Balancer ☆`1,293`
*   [temporalio/sdk-go (⭐944)](https://github.com/temporalio/sdk-go) — Temporal Go SDK ☆`945`
*   [AppsFlyer/go-sundheit (⭐561)](https://github.com/AppsFlyer/go-sundheit) — Health checks library for Go ☆`561`
*   [tarmac-project/tarmac (⭐346)](https://github.com/tarmac-project/tarmac) — Functions as Monolith or Microservices ☆`346`
*   [italolelis/outboxer (⭐168)](https://github.com/italolelis/outboxer) — A library that implements the outboxer pattern in go ☆`168`
*   [capillariesio/capillaries (⭐73)](https://github.com/capillariesio/capillaries) — Distributed batch data processing framework ☆`73`
*   [pdupub/go-pdu (⭐50)](https://github.com/pdupub/go-pdu) — An PDU implementation in Go ☆`50`
*   [mbrostami/consistenthash (⭐35)](https://github.com/mbrostami/consistenthash) — Consistent hashing implementation ☆`35`

### HTTP & Proxy

*   [valyala/fasthttp (⭐23k)](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,429`
*   [elazarl/goproxy (⭐6.7k)](https://github.com/elazarl/goproxy) — An HTTP proxy library for Go ☆`6,743`
*   [wzshiming/httpproxy (⭐33)](https://github.com/wzshiming/httpproxy) — HTTP proxy handler and dialer ☆`33`

### HTTP Clients

*   [go-resty/resty (⭐12k)](https://github.com/go-resty/resty) — Simple HTTP, REST, and SSE client library for Go ☆`11,750`
*   [imroc/req (⭐4.9k)](https://github.com/imroc/req) — Simple Go HTTP client with Black Magic ☆`4,854`
*   [gojek/heimdall (⭐2.8k)](https://github.com/gojek/heimdall) — An enhanced HTTP client for Go ☆`2,775`
*   [hashicorp/go-retryablehttp (⭐2.3k)](https://github.com/hashicorp/go-retryablehttp) — Retryable HTTP client in Go ☆`2,343`
*   [levigross/grequests (⭐2.2k)](https://github.com/levigross/grequests) — A Go "clone" of the great and famous Requests library ☆`2,186`
*   [bogdanfinn/tls-client (⭐1.8k)](https://github.com/bogdanfinn/tls-client) — HTTP client with TLS fingerprint spoofing ☆`1,777`
*   [dghubble/sling (⭐1.7k)](https://github.com/dghubble/sling) — A Go HTTP client library for creating and sending API requests ☆`1,720`
*   [earthboundkid/requests (⭐1.7k)](https://github.com/earthboundkid/requests) — HTTP requests for Gophers ☆`1,672`
*   [Noooste/azuretls-client (⭐468)](https://github.com/Noooste/azuretls-client) — HTTP client to spoof TLS/JA3 fingerprint ☆`469`
*   [opus-domini/fast-shot (⭐127)](https://github.com/opus-domini/fast-shot) — Fluent HTTP client for Go ☆`127`
*   [go-zoox/fetch (⭐90)](https://github.com/go-zoox/fetch) — Powerful HTTP client for Go ☆`90`
*   [NdoleStudio/go-otelroundtripper (⭐88)](https://github.com/NdoleStudio/go-otelroundtripper) — OpenTelemetry metrics for HTTP clients ☆`88`
*   [rezmoss/axios4go (⭐39)](https://github.com/rezmoss/axios4go) — Axios-inspired HTTP client ☆`39`
*   [lib4u/fake-useragent (⭐19)](https://github.com/lib4u/fake-useragent) — Up-to-date simple useragent faker with real world database in Golang ☆`19`

### Servers

*   [caddyserver/caddy (⭐75k)](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`74,899`
*   [pocketbase/pocketbase (⭐61k)](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`60,640`
*   [etcd-io/etcd (⭐52k)](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`52,120`
*   [drakkan/sftpgo (⭐12k)](https://github.com/drakkan/sftpgo) — Full-featured SFTP/FTP/HTTP server ☆`12,396`
*   [adnanh/webhook (⭐12k)](https://github.com/adnanh/webhook) — Lightweight webhook server ☆`12,035`
*   [roadrunner-server/roadrunner (⭐8.5k)](https://github.com/roadrunner-server/roadrunner) — High-performance PHP application server ☆`8,501`
*   [easegress-io/easegress (⭐5.9k)](https://github.com/easegress-io/easegress) — A Cloud Native traffic orchestration system. (CNCF Project) ☆`5,869`
*   [charmbracelet/wish (⭐5.4k)](https://github.com/charmbracelet/wish) — Make SSH apps, just like that! ☆`5,437`
*   [flipt-io/flipt (⭐4.9k)](https://github.com/flipt-io/flipt) — Enterprise-ready, Git native feature management solution ☆`4,870`
*   [getfider/fider (⭐4.5k)](https://github.com/getfider/fider) — Open platform to collect and prioritize feedback ☆`4,464`
*   [xyproto/algernon (⭐3k)](https://github.com/xyproto/algernon) — Web server with Lua and Markdown ☆`3,024`
*   [openflagr/flagr (⭐2.6k)](https://github.com/openflagr/flagr) — Feature flagging and A/B testing ☆`2,606`
*   [thomaspoignant/go-feature-flag (⭐2.1k)](https://github.com/thomaspoignant/go-feature-flag) — Open source feature flag solution ☆`2,078`
*   [msoap/shell2http (⭐1.5k)](https://github.com/msoap/shell2http) — Executing shell commands via HTTP server ☆`1,499`
*   [openrundev/openrun (⭐918)](https://github.com/openrundev/openrun) — Open source Cloud Run alternative ☆`929`
*   [webhookx-io/webhookx (⭐296)](https://github.com/webhookx-io/webhookx) — The Next-Generation Webhooks Gateway. ☆`296`
*   [blind-oracle/cortex-tenant (⭐140)](https://github.com/blind-oracle/cortex-tenant) — Prometheus proxy with tenant ID injection ☆`140`
*   [baalimago/wd-41 (⭐154)](https://github.com/baalimago/wd-41) — Web-Development 41, a static web server with live-reload ☆`154`
*   [42atomys/webhooked (⭐43)](https://github.com/42atomys/webhooked) — A webhook receiver on steroids. ☆`43`

### Network Utilities

*   [fortio/fortio (⭐3.7k)](https://github.com/fortio/fortio) — Load testing and echo server ☆`3,718`
*   [hashicorp/go-getter (⭐1.8k)](https://github.com/hashicorp/go-getter) — Download files from URLs ☆`1,823`
*   [TimothyYe/godns (⭐1.8k)](https://github.com/TimothyYe/godns) — Dynamic DNS client for multiple providers ☆`1,772`
*   [cavaliergopher/grab (⭐1.5k)](https://github.com/cavaliergopher/grab) — Download manager package ☆`1,483`
*   [schollz/peerdiscovery (⭐673)](https://github.com/schollz/peerdiscovery) — Cross-platform local peer discovery ☆`673`
*   [fclairamb/ftpserverlib (⭐473)](https://github.com/fclairamb/ftpserverlib) — FTP server library for Go ☆`473`
*   [skibish/ddns (⭐266)](https://github.com/skibish/ddns) — Personal DDNS client with Digital Ocean Networking DNS as backend. ☆`266`
*   [assafmo/joincap (⭐219)](https://github.com/assafmo/joincap) — Merge pcap files ☆`219`
*   [gaissmai/bart (⭐154)](https://github.com/gaissmai/bart) — Balanced routing table ☆`154`
*   [alegrey91/fwdctl (⭐72)](https://github.com/alegrey91/fwdctl) — Manage IPTables forwards via CLI ☆`72`

### P2P & Torrent

*   [anacrolix/torrent (⭐6.1k)](https://github.com/anacrolix/torrent) — Full-featured BitTorrent client package and utilities ☆`6,092`
*   [dragonflyoss/dragonfly (⭐3.3k)](https://github.com/dragonflyoss/dragonfly) — P2P-based container image distribution ☆`3,295`
*   [cenkalti/rain (⭐1.1k)](https://github.com/cenkalti/rain) — BitTorrent client and library in Go ☆`1,143`
*   [anacrolix/dht (⭐362)](https://github.com/anacrolix/dht) — DHT for BitTorrent ☆`362`

### Protocols

*   [pion/webrtc (⭐17k)](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,713`
*   [quic-go/quic-go (⭐12k)](https://github.com/quic-go/quic-go) — A production-ready QUIC implementation in pure Go ☆`11,741`
*   [google/gopacket (⭐6.8k)](https://github.com/google/gopacket) — Provides packet processing capabilities for Go ☆`6,793`
*   [osrg/gobgp (⭐4.1k)](https://github.com/osrg/gobgp) — BGP implemented in the Go Programming Language ☆`4,097`
*   [lxzan/gws (⭐1.8k)](https://github.com/lxzan/gws) — Fast websocket server and client ☆`1,797`
*   [gosnmp/gosnmp (⭐1.3k)](https://github.com/gosnmp/gosnmp) — An SNMP library written in Go ☆`1,254`
*   [bluenviron/gortsplib (⭐931)](https://github.com/bluenviron/gortsplib) — RTSP client and server library for the Go programming language ☆`934`
*   [ccding/go-stun (⭐721)](https://github.com/ccding/go-stun) — A go implementation of the STUN client (RFC 3489 and RFC 5389) ☆`721`
*   [google/gnxi (⭐289)](https://github.com/google/gnxi) — gNXI Tools - gRPC Network Management/Operations Interface Tools ☆`289`
*   [jeroenrinzema/psql-wire (⭐238)](https://github.com/jeroenrinzema/psql-wire) — PostgreSQL wire protocol for Go ☆`238`
*   [jimlambrt/gldap (⭐122)](https://github.com/jimlambrt/gldap) — Build LDAP services w/ Go ☆`122`
*   [soypat/natiu-mqtt (⭐105)](https://github.com/soypat/natiu-mqtt) — Extensible MQTT for embedded systems ☆`105`

### RPC

*   [grpc/grpc-go (⭐23k)](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`23,038`
*   [lesismal/arpc (⭐1.1k)](https://github.com/lesismal/arpc) — Two-way RPC with broadcast support ☆`1,090`
*   [ybbus/jsonrpc (⭐371)](https://github.com/ybbus/jsonrpc) — A simple go implementation of json rpc 2.0 client over http ☆`371`
*   [osamingo/jsonrpc (⭐193)](https://github.com/osamingo/jsonrpc) — The jsonrpc package helps implement of JSON-RPC 2.0 ☆`193`

### SSH & SFTP

*   [gliderlabs/ssh (⭐4.2k)](https://github.com/gliderlabs/ssh) — Easy SSH servers in Golang ☆`4,165`
*   [pkg/sftp (⭐1.7k)](https://github.com/pkg/sftp) — SFTP support for the go.crypto/ssh package ☆`1,662`
*   [masterzen/winrm (⭐479)](https://github.com/masterzen/winrm) — Windows remote command library ☆`479`

### TCP/UDP Frameworks

*   [panjf2000/gnet (⭐11k)](https://github.com/panjf2000/gnet) — High-performance event-loop network ☆`11,230`
*   [xtaci/kcp-go (⭐4.5k)](https://github.com/xtaci/kcp-go) — A crypto-secure Reliable-UDP library for Golang with FEC support. ☆`4,545`
*   [cloudwego/netpoll (⭐4.6k)](https://github.com/cloudwego/netpoll) — High-performance I/O framework ☆`4,599`
*   [lesismal/nbio (⭐2.8k)](https://github.com/lesismal/nbio) — High-performance network library ☆`2,753`
*   [xtaci/gaio (⭐933)](https://github.com/xtaci/gaio) — High-performance, minimalist async-io (proactor) networking for Golang. ☆`933`
*   [cheng-zhongliang/event (⭐119)](https://github.com/cheng-zhongliang/event) — Simple I/O event notification library wirtten in Golang ☆`119`
*   [fish-tennis/gnet (⭐27)](https://github.com/fish-tennis/gnet) — high performance net library for game server ☆`27`

### VPN & Tunneling

*   [cloudflare/cloudflared (⭐15k)](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`15,200`
*   [xjasonlyu/tun2socks (⭐5.4k)](https://github.com/xjasonlyu/tun2socks) — TUN to SOCKS proxy ☆`5,439`
*   [NodePassProject/nodepass (⭐274)](https://github.com/NodePassProject/nodepass) — Secure TCP/UDP tunneling with TLS ☆`274`

## Queues & Pub/Sub

### Brokers

*   [nats-io/nats-server (⭐20k)](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`20,486`
*   [emitter-io/emitter (⭐4k)](https://github.com/emitter-io/emitter) — High-performance pub/sub broker ☆`4,003`
*   [mochi-mqtt/server (⭐1.9k)](https://github.com/mochi-mqtt/server) — Embeddable MQTT v5 broker ☆`1,916`

### Clients & Libraries

*   [hibiken/asynq (⭐14k)](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`13,625`
*   [IBM/sarama (⭐12k)](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,505`
*   [centrifugal/centrifugo (⭐11k)](https://github.com/centrifugal/centrifugo) — Scalable real-time messaging server ☆`10,617`
*   [ThreeDotsLabs/watermill (⭐9.8k)](https://github.com/ThreeDotsLabs/watermill) — Building event-driven applications the easy way in Go. ☆`9,841`
*   [appleboy/gorush (⭐8.8k)](https://github.com/appleboy/gorush) — A push notification server written in Go (Golang). ☆`8,756`
*   [RichardKnop/machinery (⭐8k)](https://github.com/RichardKnop/machinery) — Async task queue with message passing ☆`7,971`
*   [nats-io/nats.go (⭐6.7k)](https://github.com/nats-io/nats.go) — Golang client for NATS, the cloud native messaging system. ☆`6,723`
*   [dunglas/mercure (⭐5.3k)](https://github.com/dunglas/mercure) — Server-Sent Events hub ☆`5,299`
*   [confluentinc/confluent-kafka-go (⭐5.2k)](https://github.com/confluentinc/confluent-kafka-go) — Confluent's Apache Kafka Golang client ☆`5,160`
*   [olahol/melody (⭐4.1k)](https://github.com/olahol/melody) — Minimalist websocket framework for Go ☆`4,082`
*   [sideshow/apns2 (⭐3.2k)](https://github.com/sideshow/apns2) — Apple Push Notification Service ☆`3,187`
*   [lovoo/goka (⭐2.5k)](https://github.com/lovoo/goka) — Kafka stream processing library ☆`2,538`
*   [rabbitmq/amqp091-go (⭐2k)](https://github.com/rabbitmq/amqp091-go) — An AMQP 0-9-1 Go client maintained by the RabbitMQ team ☆`2,026`
*   [containrrr/shoutrrr (⭐1.6k)](https://github.com/containrrr/shoutrrr) — Notification library for gophers and their furry friends. ☆`1,650`
*   [pebbe/zmq4 (⭐1.3k)](https://github.com/pebbe/zmq4) — A Go interface to ZeroMQ version 4 ☆`1,260`
*   [timbray/quamina (⭐501)](https://github.com/timbray/quamina) — Fast pattern-matching library ☆`501`
*   [jandelgado/rabtap (⭐288)](https://github.com/jandelgado/rabtap) — RabbitMQ wire tap and swiss army knife ☆`288`
*   [mehdihadeli/Go-MediatR (⭐278)](https://github.com/mehdihadeli/Go-MediatR) — Mediator pattern for CQRS ☆`278`
*   [goptics/varmq (⭐193)](https://github.com/goptics/varmq) — Zero-dep message queue library ☆`194`
*   [oagudo/outbox (⭐131)](https://github.com/oagudo/outbox) — Transactional outbox pattern ☆`131`
*   [hyperonym/ratus (⭐124)](https://github.com/hyperonym/ratus) — RESTful async task queue server ☆`124`
*   [dailymotion/oplog (⭐111)](https://github.com/dailymotion/oplog) — A generic oplog/replication system for microservices ☆`111`
*   [Protocol-Lattice/GoEventBus (⭐68)](https://github.com/Protocol-Lattice/GoEventBus) — A lock-free, ultra-fast event bus for Go ☆`69`
*   [jirenius/go-res (⭐69)](https://github.com/jirenius/go-res) — RES Service protocol library for Go ☆`69`
*   [SchwarzDigits/hypermatch (⭐37)](https://github.com/SchwarzDigits/hypermatch) — High-performance rule matching ☆`37`

## Science

*   [gonum/gonum (⭐8.4k)](https://github.com/gonum/gonum) — Numeric libraries for Go ☆`8,421`
*   [gonum/plot (⭐3k)](https://github.com/gonum/plot) — Plotting and visualization ☆`2,964`
*   [paulmach/orb (⭐1.1k)](https://github.com/paulmach/orb) — 2D geometry types and utilities ☆`1,123`
*   [madelynnblue/go-dsp (⭐915)](https://github.com/madelynnblue/go-dsp) — Digital Signal Processing for Go ☆`915`
*   [bebop/poly (⭐735)](https://github.com/bebop/poly) — Synthetic biology library for Go ☆`735`
*   [DavidBelicza/TextRank (⭐224)](https://github.com/DavidBelicza/TextRank) — TextRank implementation in Golang with extendable features (summarization, phrase extraction) and multithreading (goroutine). ☆`224`
*   [hmdsefi/gograph (⭐123)](https://github.com/hmdsefi/gograph) — Generic graph algorithms library ☆`123`
*   [nikolaydubina/jsonl-graph (⭐79)](https://github.com/nikolaydubina/jsonl-graph) — JSONL Graph Tools ☆`79`
*   [claygod/PiHex (⭐21)](https://github.com/claygod/PiHex) — Generate hexadecimal Pi digits ☆`21`

## Scripting

### Embeddable Languages

*   [php/frankenphp (⭐11k)](https://github.com/php/frankenphp) — The modern PHP app server ☆`11,279`
*   [expr-lang/expr (⭐8k)](https://github.com/expr-lang/expr) — Expression evaluation for Go ☆`7,974`
*   [dop251/goja (⭐7k)](https://github.com/dop251/goja) — ECMAScript engine in pure Go ☆`7,045`
*   [yuin/gopher-lua (⭐7k)](https://github.com/yuin/gopher-lua) — Lua VM and compiler in Go ☆`6,966`
*   [d5/tengo (⭐3.8k)](https://github.com/d5/tengo) — Fast script language for Go ☆`3,831`
*   [Shopify/go-lua (⭐3.4k)](https://github.com/Shopify/go-lua) — Lua VM in Go ☆`3,448`
*   [cel-expr/cel-go (⭐3.1k)](https://github.com/cel-expr/cel-go) — Common Expression Language for Go ☆`3,064`
*   [google/starlark-go (⭐2.7k)](https://github.com/google/starlark-go) — Starlark config language in Go ☆`2,746`
*   [metacall/core (⭐1.8k)](https://github.com/metacall/core) — Polyglot programming runtime ☆`1,809`
*   [wa-lang/wa (⭐1.8k)](https://github.com/wa-lang/wa) — The Wa Programming Language ☆`1,768`
*   [mattn/anko (⭐1.6k)](https://github.com/mattn/anko) — Scriptable interpreter in Go ☆`1,580`
*   [PaesslerAG/gval (⭐814)](https://github.com/PaesslerAG/gval) — Expression evaluation in Go ☆`814`
*   [ichiban/prolog (⭐728)](https://github.com/ichiban/prolog) — Prolog scripting engine for Go ☆`728`
*   [aarzilli/golua (⭐700)](https://github.com/aarzilli/golua) — Lua C API bindings for Go ☆`700`
*   [1set/starlet (⭐48)](https://github.com/1set/starlet) — Starlark wrapper with batteries ☆`48`

### Code Generators

*   [oapi-codegen/oapi-codegen (⭐8.5k)](https://github.com/oapi-codegen/oapi-codegen) — Generate Go code from OpenAPI 3 specs ☆`8,512`
*   [dave/jennifer (⭐3.6k)](https://github.com/dave/jennifer) — Code generator for Go ☆`3,628`
*   [hexdigest/gowrap (⭐1.3k)](https://github.com/hexdigest/gowrap) — Generate interface decorators ☆`1,334`
*   [awalterschulze/goderive (⭐1.3k)](https://github.com/awalterschulze/goderive) — Generate mundane Go functions ☆`1,261`
*   [abice/go-enum (⭐954)](https://github.com/abice/go-enum) — Enum generator for Go ☆`954`
*   [jmattheis/goverter (⭐866)](https://github.com/jmattheis/goverter) — Generate type-safe converters ☆`868`
*   [rjeczalik/interfaces (⭐431)](https://github.com/rjeczalik/interfaces) — Code generation tools for Go ☆`431`
*   [switchupcb/copygen (⭐406)](https://github.com/switchupcb/copygen) — Copy values between types ☆`406`
*   [reedom/convergen (⭐51)](https://github.com/reedom/convergen) — Type-to-type copy code generator ☆`51`

## Security

### Certificates

*   [go-acme/lego (⭐9.8k)](https://github.com/go-acme/lego) — Let's Encrypt/ACME client and library written in Go ☆`9,806`
*   [caddyserver/certmagic (⭐5.6k)](https://github.com/caddyserver/certmagic) — Automatic HTTPS certificate management ☆`5,590`
*   [tg123/go-htpasswd (⭐49)](https://github.com/tg123/go-htpasswd) — Apache htpasswd Parser for Go. ☆`49`
*   [adrianosela/sslmgr (⭐32)](https://github.com/adrianosela/sslmgr) — SSL certificate abstraction ☆`32`

### Cryptography

*   [FiloSottile/age (⭐23k)](https://github.com/FiloSottile/age) — Simple encryption tool ☆`23,198`
*   [authzed/spicedb (⭐7k)](https://github.com/authzed/spicedb) — Zanzibar-inspired permissions DB ☆`6,956`
*   [awnumar/memguard (⭐2.8k)](https://github.com/awnumar/memguard) — Software sandbox for storage of sensitive information in memory. ☆`2,754`
*   [cossacklabs/themis (⭐2k)](https://github.com/cossacklabs/themis) — Cryptographic framework for data protection ☆`1,971`
*   [dromara/dongle (⭐1.1k)](https://github.com/dromara/dongle) — A simple, semantic and developer-friendly crypto package for golang ☆`1,107`
*   [anatol/booster (⭐660)](https://github.com/anatol/booster) — Fast and secure initramfs generator ☆`661`
*   [kevinburke/nacl (⭐550)](https://github.com/kevinburke/nacl) — Pure Go implementation of the NaCL set of API's ☆`550`
*   [ssh-vault/ssh-vault (⭐508)](https://github.com/ssh-vault/ssh-vault) — encrypt/decrypt using ssh keys ☆`508`
*   [number571/go-peer (⭐327)](https://github.com/number571/go-peer) — Secure decentralized networking ☆`328`
*   [lingrino/vaku (⭐160)](https://github.com/lingrino/vaku) — Extended Vault API and CLI ☆`160`
*   [anatol/luks.go (⭐98)](https://github.com/anatol/luks.go) — Pure Golang library to manage LUKS partitions ☆`98`
*   [zitadel/passwap (⭐78)](https://github.com/zitadel/passwap) — Unified password hashing ☆`78`
*   [rsjethani/secret (⭐33)](https://github.com/rsjethani/secret) — Prevent your secrets from leaking into logs, std\* etc. ☆`33`
*   [andskur/argon2-hashing (⭐25)](https://github.com/andskur/argon2-hashing) — Argon2 password hashing ☆`25`

### WAF & Protection

*   [Ullaakut/cameradar (⭐5.2k)](https://github.com/Ullaakut/cameradar) — Cameradar hacks its way into RTSP videosurveillance cameras ☆`5,162`
*   [corazawaf/coraza (⭐3.7k)](https://github.com/corazawaf/coraza) — ModSecurity-compatible WAF in Go ☆`3,734`
*   [mojocn/base64Captcha (⭐2.4k)](https://github.com/mojocn/base64Captcha) — captcha of base64 image string ☆`2,369`
*   [unrolled/secure (⭐2.4k)](https://github.com/unrolled/secure) — HTTP middleware for Go that facilitates some quick security wins. ☆`2,353`
*   [beelzebub-labs/beelzebub (⭐2.1k)](https://github.com/beelzebub-labs/beelzebub) — AI-powered honeypot framework ☆`2,144`
*   [cossacklabs/acra (⭐1.5k)](https://github.com/cossacklabs/acra) — Database security proxy ☆`1,491`
*   [securitybunker/databunker (⭐1.5k)](https://github.com/securitybunker/databunker) — Secure vault for PII/PHI/KYC records ☆`1,481`
*   [hillu/go-yara (⭐389)](https://github.com/hillu/go-yara) — Go bindings for YARA ☆`389`
*   [steambap/captcha (⭐163)](https://github.com/steambap/captcha) — Easy captcha library ☆`163`

### Zero Trust

*   [sigstore/cosign (⭐6.2k)](https://github.com/sigstore/cosign) — Code signing and transparency for containers and binaries ☆`6,202`
*   [openziti/ziti (⭐4.3k)](https://github.com/openziti/ziti) — Zero trust networking platform ☆`4,348`
*   [spiffe/spire (⭐2.5k)](https://github.com/spiffe/spire) — The SPIFFE Runtime Environment ☆`2,485`
*   [philips-labs/spiffe-vault (⭐101)](https://github.com/philips-labs/spiffe-vault) — Integrates Spiffe and Vault to have secretless authentication ☆`101`

## Testing & Quality

### Benchmarks

*   [smallnest/go-web-framework-benchmark (⭐2.1k)](https://github.com/smallnest/go-web-framework-benchmark) — Web framework benchmarks ☆`2,135`
*   [alecthomas/go\_serialization\_benchmarks (⭐1.6k)](https://github.com/alecthomas/go_serialization_benchmarks) — Serialization benchmarks for Go ☆`1,625`
*   [SimonWaldherr/golang-benchmarks (⭐145)](https://github.com/SimonWaldherr/golang-benchmarks) — Go(lang) benchmarks - (measure the speed of golang) ☆`145`
*   [nikolaydubina/go-ml-benchmarks (⭐34)](https://github.com/nikolaydubina/go-ml-benchmarks) — Benchmarks of machine learning inference for Go ☆`34`

### Code Analysis

*   [golangci/golangci-lint (⭐19k)](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`19,247`
*   [boyter/scc (⭐8.6k)](https://github.com/boyter/scc) — Fast code counter and stats ☆`8,620`
*   [mgechev/revive (⭐5.5k)](https://github.com/mgechev/revive) — Fast, extensible Go linter ☆`5,543`
*   [kisielk/errcheck (⭐2.5k)](https://github.com/kisielk/errcheck) — errcheck checks that you checked errors. ☆`2,527`
*   [go-critic/go-critic (⭐2.1k)](https://github.com/go-critic/go-critic) — The most opinionated Go source code linter for code audit. ☆`2,066`
*   [daveshanley/vacuum (⭐1.1k)](https://github.com/daveshanley/vacuum) — Fast OpenAPI linter ☆`1,114`
*   [presmihaylov/todocheck (⭐439)](https://github.com/presmihaylov/todocheck) — Analyser for TODO comments ☆`439`
*   [mdempsky/unconvert (⭐387)](https://github.com/mdempsky/unconvert) — Remove unnecessary type conversions ☆`387`
*   [tomarrell/wrapcheck (⭐373)](https://github.com/tomarrell/wrapcheck) — Check errors are wrapped ☆`373`
*   [mibk/dupl (⭐368)](https://github.com/mibk/dupl) — Code clone detection tool ☆`368`
*   [shurcooL/gostatus (⭐245)](https://github.com/shurcooL/gostatus) — Show status of Go repositories ☆`245`
*   [Antonboom/testifylint (⭐172)](https://github.com/Antonboom/testifylint) — Linter for testify usage ☆`172`
*   [Crocmagnon/fatcontext (⭐81)](https://github.com/Crocmagnon/fatcontext) — Detect nested contexts in loops ☆`81`
*   [antham/ghokin (⭐56)](https://github.com/antham/ghokin) — Parallelized Gherkin formatter ☆`56`
*   [sashamelentyev/usestdlibvars (⭐47)](https://github.com/sashamelentyev/usestdlibvars) — Linter for stdlib variables usage ☆`47`
*   [borovikovd/gomsort (⭐26)](https://github.com/borovikovd/gomsort) — Go msort - linter that sorts methods ☆`26`

### Mock

*   [vektra/mockery (⭐7.2k)](https://github.com/vektra/mockery) — Mock code autogenerator for Go ☆`7,153`
*   [DATA-DOG/go-sqlmock (⭐6.6k)](https://github.com/DATA-DOG/go-sqlmock) — SQL mock driver for testing ☆`6,567`
*   [brianvoe/gofakeit (⭐5.4k)](https://github.com/brianvoe/gofakeit) — Random fake data generator written in go ☆`5,379`
*   [uber-go/mock (⭐3.4k)](https://github.com/uber-go/mock) — GoMock is a mocking framework for the Go programming language. ☆`3,395`
*   [SpectoLabs/hoverfly (⭐2.5k)](https://github.com/SpectoLabs/hoverfly) — API simulation and virtualization ☆`2,509`
*   [matryer/moq (⭐2.2k)](https://github.com/matryer/moq) — Interface mocking via go generate ☆`2,205`
*   [jarcoal/httpmock (⭐2.1k)](https://github.com/jarcoal/httpmock) — HTTP mocking for Go ☆`2,078`
*   [maxbrunsfeld/counterfeiter (⭐1.1k)](https://github.com/maxbrunsfeld/counterfeiter) — Generate type-safe test doubles ☆`1,139`
*   [gojuno/minimock (⭐752)](https://github.com/gojuno/minimock) — Powerful mock generator ☆`752`
*   [DATA-DOG/go-txdb (⭐751)](https://github.com/DATA-DOG/go-txdb) — Transaction-isolated SQL driver ☆`751`
*   [pashagolub/pgxmock (⭐594)](https://github.com/pashagolub/pgxmock) — pgx mock driver for testing ☆`594`
*   [xhd2015/xgo (⭐431)](https://github.com/xhd2015/xgo) — All-in-one Go testing library ☆`431`
*   [seborama/govcr (⭐200)](https://github.com/seborama/govcr) — Record and replay HTTP interactions ☆`200`
*   [mocktools/go-smtp-mock (⭐168)](https://github.com/mocktools/go-smtp-mock) — SMTP mock server for testing ☆`168`
*   [elgohr/go-localstack (⭐88)](https://github.com/elgohr/go-localstack) — Go wrapper for LocalStack ☆`88`

### Performance

*   [jaegertracing/jaeger (⭐23k)](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`23,097`
*   [pixie-io/pixie (⭐6.5k)](https://github.com/pixie-io/pixie) — Kubernetes-native observability ☆`6,513`
*   [arl/statsviz (⭐3.6k)](https://github.com/arl/statsviz) — Visualize Go runtime metrics ☆`3,646`
*   [nikolaydubina/go-instrument (⭐299)](https://github.com/nikolaydubina/go-instrument) — Add trace spans to Go functions ☆`299`
*   [joetifa2003/mm-go (⭐194)](https://github.com/joetifa2003/mm-go) — Manual memory management for Go ☆`194`

### Browser Automation

*   [chromedp/chromedp (⭐13k)](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`13,251`
*   [go-rod/rod (⭐7.1k)](https://github.com/go-rod/rod) — Chrome DevTools driver for scraping ☆`7,058`
*   [sensepost/gowitness (⭐4.5k)](https://github.com/sensepost/gowitness) — Web screenshot utility with Chrome ☆`4,477`
*   [mxschmitt/playwright-go (⭐3.5k)](https://github.com/mxschmitt/playwright-go) — Browser automation for Chromium, Firefox, WebKit ☆`3,468`
*   [mafredri/cdp (⭐796)](https://github.com/mafredri/cdp) — Chrome DevTools Protocol bindings ☆`796`

### Testing Frameworks

*   [stretchr/testify (⭐26k)](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`26,154`
*   [keploy/keploy (⭐18k)](https://github.com/keploy/keploy) — API testing with auto mocks ☆`18,398`
*   [Shopify/toxiproxy (⭐12k)](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`12,238`
*   [testcontainers/testcontainers-go (⭐4.9k)](https://github.com/testcontainers/testcontainers-go) — Docker containers for integration tests ☆`4,948`
*   [google/go-cmp (⭐4.7k)](https://github.com/google/go-cmp) — Package for comparing Go values in tests ☆`4,672`
*   [gavv/httpexpect (⭐2.7k)](https://github.com/gavv/httpexpect) — End-to-end HTTP and REST API testing for Go. ☆`2,725`
*   [cucumber/godog (⭐2.7k)](https://github.com/cucumber/godog) — Cucumber for golang ☆`2,659`
*   [orlangure/gnomock (⭐1.5k)](https://github.com/orlangure/gnomock) — Test with ephemeral Docker containers ☆`1,489`
*   [dnaeon/go-vcr (⭐1.4k)](https://github.com/dnaeon/go-vcr) — Record and replay HTTP for tests ☆`1,394`
*   [go-testfixtures/testfixtures (⭐1.2k)](https://github.com/go-testfixtures/testfixtures) — Rails-like test fixtures for Go ☆`1,235`
*   [fergusstrange/embedded-postgres (⭐1.2k)](https://github.com/fergusstrange/embedded-postgres) — Embedded PostgreSQL for testing ☆`1,218`
*   [chapar-rest/chapar (⭐706)](https://github.com/chapar-rest/chapar) — API testing for HTTP and gRPC ☆`706`
*   [gotestyourself/gotest.tools (⭐577)](https://github.com/gotestyourself/gotest.tools) — Testing utilities for Go ☆`577`
*   [maxatome/go-testdeep (⭐463)](https://github.com/maxatome/go-testdeep) — Flexible deep comparison in tests ☆`463`
*   [appleboy/gofight (⭐445)](https://github.com/appleboy/gofight) — Testing API Handler written in Golang. ☆`445`
*   [ysmood/got (⭐267)](https://github.com/ysmood/got) — An enjoyable golang test framework. ☆`267`
*   [viant/endly (⭐269)](https://github.com/viant/endly) — End to end functional test and automation framework ☆`269`
*   [adamluzsi/testcase (⭐133)](https://github.com/adamluzsi/testcase) — Opinionated testing framework ☆`133`
*   [kinbiko/jsonassert (⭐143)](https://github.com/kinbiko/jsonassert) — JSON assertion library for tests ☆`143`
*   [earthboundkid/be (⭐133)](https://github.com/earthboundkid/be) — The Go test helper for minimalists ☆`133`
*   [hedhyw/gherkingen (⭐97)](https://github.com/hedhyw/gherkingen) — Behaviour Driven Development tests generator for Golang ☆`97`
*   [corbym/gocrest (⭐108)](https://github.com/corbym/gocrest) — GoCrest - Hamcrest-like matchers for Go ☆`108`
*   [madflojo/testcerts (⭐84)](https://github.com/madflojo/testcerts) — Generate test certificates on the fly ☆`84`
*   [go-restit/restit (⭐56)](https://github.com/go-restit/restit) — A Go library help testing your RESTful API application ☆`56`
*   [viant/dsunit (⭐47)](https://github.com/viant/dsunit) — Datastore Testibility ☆`47`
*   [rekby/fixenv (⭐34)](https://github.com/rekby/fixenv) — Pytest-inspired fixture caching for Go tests ☆`34`
*   [abecodes/dft (⭐19)](https://github.com/abecodes/dft) — Docker wrapper for testing ☆`19`

### Testing Utilities

*   [dvyukov/go-fuzz (⭐4.8k)](https://github.com/dvyukov/go-fuzz) — Randomized testing for Go ☆`4,850`
*   [pingcap/failpoint (⭐892)](https://github.com/pingcap/failpoint) — Failpoint implementation for Go ☆`892`

### Validation

*   [go-playground/validator (⭐20k)](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`20,109`
*   [Oudwins/zog (⭐1.2k)](https://github.com/Oudwins/zog) — Zod-inspired schema validation ☆`1,208`
*   [gookit/validate (⭐1.2k)](https://github.com/gookit/validate) — Struct and data validation ☆`1,163`
*   [twharmon/govalid (⭐118)](https://github.com/twharmon/govalid) — Struct validation using tags ☆`118`
*   [osamingo/checkdigit (⭐114)](https://github.com/osamingo/checkdigit) — Check digit algorithms ☆`114`
*   [tiendc/go-validator (⭐32)](https://github.com/tiendc/go-validator) — Intuitive validation library ☆`32`
*   [marrow16/valix (⭐31)](https://github.com/marrow16/valix) — Request validation package ☆`31`

## Text & NLP

### Formatters

*   [dustin/go-humanize (⭐4.8k)](https://github.com/dustin/go-humanize) — Human-friendly unit formatting ☆`4,814`
*   [neilotoole/sq (⭐2.5k)](https://github.com/neilotoole/sq) — SQL data wrangler ☆`2,549`
*   [bojanz/address (⭐83)](https://github.com/bojanz/address) — Address handling for Go ☆`83`

### Markup Languages

*   [BurntSushi/toml (⭐5k)](https://github.com/BurntSushi/toml) — TOML parser with reflection ☆`4,993`
*   [yuin/goldmark (⭐4.9k)](https://github.com/yuin/goldmark) — Markdown parser for Go ☆`4,941`
*   [JohannesKaufmann/html-to-markdown (⭐3.8k)](https://github.com/JohannesKaufmann/html-to-markdown) — Convert HTML to Markdown ☆`3,780`
*   [pelletier/go-toml (⭐2k)](https://github.com/pelletier/go-toml) — TOML library for Go ☆`1,975`
*   [antchfx/htmlquery (⭐783)](https://github.com/antchfx/htmlquery) — XPath for HTML queries ☆`783`
*   [mmalcek/bafi (⭐116)](https://github.com/mmalcek/bafi) — Universal format converter ☆`116`

### Miscellaneous

*   [microcosm-cc/bluemonday (⭐3.7k)](https://github.com/microcosm-cc/bluemonday) — Fast HTML sanitizer for Go ☆`3,709`
*   [pemistahl/lingua-go (⭐1.4k)](https://github.com/pemistahl/lingua-go) — Natural language detection ☆`1,361`
*   [gosimple/slug (⭐1.3k)](https://github.com/gosimple/slug) — URL-friendly slugify ☆`1,331`
*   [arunsupe/semantic-grep (⭐1.2k)](https://github.com/arunsupe/semantic-grep) — Grep for similar words ☆`1,246`
*   [mattn/go-runewidth (⭐717)](https://github.com/mattn/go-runewidth) — Rune width for terminals ☆`717`
*   [hedhyw/rex (⭐213)](https://github.com/hedhyw/rex) — Flexible regex constructor ☆`213`
*   [IGLOU-EU/go-wildcard (⭐103)](https://github.com/IGLOU-EU/go-wildcard) — Fast wildcard matching ☆`103`
*   [JoshuaDoes/gofuckyourself (⭐71)](https://github.com/JoshuaDoes/gofuckyourself) — Swear filter for Go ☆`71`

### Morphological Analyzers

*   [nlpodyssey/spago (⭐1.9k)](https://github.com/nlpodyssey/spago) — ML and NLP library for Go ☆`1,850`
*   [ikawaha/kagome (⭐977)](https://github.com/ikawaha/kagome) — Japanese morphological analyzer ☆`977`
*   [afjoseph/RAKE.Go (⭐124)](https://github.com/afjoseph/RAKE.Go) — Rapid Keyword Extraction in Go ☆`124`
*   [jonreiter/govader (⭐55)](https://github.com/jonreiter/govader) — VADER sentiment analysis ☆`55`

### Parsers/Encoders/Decoders

*   [mvdan/sh (⭐8.9k)](https://github.com/mvdan/sh) — Shell parser and formatter ☆`8,973`
*   [mmcdole/gofeed (⭐2.9k)](https://github.com/mmcdole/gofeed) — Parse RSS, Atom, JSON feeds ☆`2,865`
*   [google/go-querystring (⭐2.1k)](https://github.com/google/go-querystring) — Encode structs to URL query strings ☆`2,146`
*   [olebedev/when (⭐1.5k)](https://github.com/olebedev/when) — Natural language date parser ☆`1,464`
*   [adrianmo/go-nmea (⭐264)](https://github.com/adrianmo/go-nmea) — NMEA sentence parser ☆`264`
*   [yassinebenaid/godump (⭐223)](https://github.com/yassinebenaid/godump) — Dump any Go variable ☆`223`
*   [editorconfig/editorconfig-core-go (⭐156)](https://github.com/editorconfig/editorconfig-core-go) — EditorConfig core in Go ☆`156`
*   [bzick/tokenizer (⭐142)](https://github.com/bzick/tokenizer) — Tokenizer/lexer for Go ☆`142`
*   [emersion/go-vcard (⭐129)](https://github.com/emersion/go-vcard) — vCard parser and formatter ☆`129`
*   [polera/gonameparts (⭐43)](https://github.com/polera/gonameparts) — Takes a full name and splits it into individual name parts ☆`43`

### Scrapers

*   [gocolly/colly (⭐25k)](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,417`
*   [PuerkitoBio/goquery (⭐15k)](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,975`
*   [mvdan/xurls (⭐1.3k)](https://github.com/mvdan/xurls) — Extract URLs from text ☆`1,266`
*   [s0rg/crawley (⭐340)](https://github.com/s0rg/crawley) — The unix-way web crawler ☆`341`

### Text Analysis

*   [blevesearch/bleve (⭐11k)](https://github.com/blevesearch/bleve) — Text/numeric/geo/vector indexing library ☆`11,179`
*   [derekparker/trie (⭐791)](https://github.com/derekparker/trie) — Trie for extremely fast prefix search ☆`791`
*   [agnivade/levenshtein (⭐472)](https://github.com/agnivade/levenshtein) — Go implementation to calculate Levenshtein Distance. ☆`473`
*   [plar/go-adaptive-radix-tree (⭐412)](https://github.com/plar/go-adaptive-radix-tree) — Adaptive Radix Trees implemented in Go ☆`412`

### Tokenizers

*   [go-ego/gse (⭐2.8k)](https://github.com/go-ego/gse) — Multilingual text segmentation ☆`2,842`
*   [pebbe/textcat (⭐73)](https://github.com/pebbe/textcat) — N-gram text categorization ☆`73`

### Translation

*   [nicksnyder/go-i18n (⭐3.5k)](https://github.com/nicksnyder/go-i18n) — Translate Go programs ☆`3,538`
*   [leonelquinteros/gotext (⭐507)](https://github.com/leonelquinteros/gotext) — GNU gettext for Go ☆`507`
*   [vorlif/spreak (⭐94)](https://github.com/vorlif/spreak) — Gettext-based translation library ☆`94`
*   [invopop/ctxi18n (⭐95)](https://github.com/invopop/ctxi18n) — Context-based i18n for Go ☆`95`
*   [mehanizm/iuliia-go (⭐57)](https://github.com/mehanizm/iuliia-go) — Cyrillic to Latin transliteration ☆`57`

## Third-party APIs

### Cloud Provider APIs

*   [googleapis/google-cloud-go (⭐4.5k)](https://github.com/googleapis/google-cloud-go) — Google Cloud Client Libraries for Go. ☆`4,493`
*   [googleapis/google-api-go-client (⭐4.5k)](https://github.com/googleapis/google-api-go-client) — Auto-generated Google APIs for Go. ☆`4,461`
*   [aws/aws-sdk-go-v2 (⭐3.6k)](https://github.com/aws/aws-sdk-go-v2) — AWS SDK for the Go programming language. ☆`3,633`
*   [minio/minio-go (⭐3k)](https://github.com/minio/minio-go) — High-performance object storage ☆`2,992`
*   [rhnvrm/simples3 (⭐206)](https://github.com/rhnvrm/simples3) — Simple AWS S3 library using REST ☆`206`
*   [circa10a/go-aws-news (⭐19)](https://github.com/circa10a/go-aws-news) — Go app + library to fetch what's new from AWS ☆`19`
*   [chainifynet/aws-encryption-sdk-go (⭐23)](https://github.com/chainifynet/aws-encryption-sdk-go) — AWS Encryption SDK for Go ☆`23`

### Other APIs

*   [codingsince1985/geo-golang (⭐548)](https://github.com/codingsince1985/geo-golang) — Go library to access geocoding and reverse geocoding APIs ☆`548`
*   [cyruzin/golang-tmdb (⭐164)](https://github.com/cyruzin/golang-tmdb) — Wrapper for TMDb API ☆`164`
*   [gregdel/pushover (⭐157)](https://github.com/gregdel/pushover) — Go wrapper for the Pushover API ☆`157`
*   [mvrilo/go-redoc (⭐95)](https://github.com/mvrilo/go-redoc) — Embedded OpenAPI documentation ☆`95`
*   [rapito/go-spotify (⭐53)](https://github.com/rapito/go-spotify) — Go library for the Spotify Web API ☆`53`
*   [rinchsan/device-check-go (⭐26)](https://github.com/rinchsan/device-check-go) — iOS DeviceCheck SDK for Go ☆`26`
*   [staskobzar/goami2 (⭐22)](https://github.com/staskobzar/goami2) — Simple Asterisk Manager Interface (AMI) library fo golang ☆`22`
*   [Icelain/jokeapi (⭐27)](https://github.com/Icelain/jokeapi) — Official golang wrapper for Sv443's jokeapi. ☆`27`

### Productivity APIs

*   [mk-5/fjira (⭐274)](https://github.com/mk-5/fjira) — The golang fuzzy-find cli jira interface ☆`274`
*   [adlio/trello (⭐228)](https://github.com/adlio/trello) — Trello API wrapper for Go ☆`228`
*   [ctreminiom/go-atlassian (⭐215)](https://github.com/ctreminiom/go-atlassian) — Atlassian Cloud API client ☆`215`
*   [koltyakov/gosip (⭐170)](https://github.com/koltyakov/gosip) — SharePoint SDK for Go ☆`170`
*   [FreeLeh/GoFreeDB (⭐90)](https://github.com/FreeLeh/GoFreeDB) — Database on top of Google Sheets ☆`90`
*   [mehanizm/airtable (⭐86)](https://github.com/mehanizm/airtable) — Simple golang airtable API wrapper ☆`86`
*   [k-capehart/go-salesforce (⭐56)](https://github.com/k-capehart/go-salesforce) — Salesforce REST API client ☆`56`

## Utilities

### Build & Release

*   [goreleaser/goreleaser (⭐16k)](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,981`
*   [create-go-app/cli (⭐2.8k)](https://github.com/create-go-app/cli) — Create production-ready Go projects ☆`2,766`
*   [miniscruff/changie (⭐897)](https://github.com/miniscruff/changie) — Automated changelog tool ☆`898`
*   [karl-cardenas-coding/go-lambda-cleanup (⭐98)](https://github.com/karl-cardenas-coding/go-lambda-cleanup) — Remove old AWS Lambda versions ☆`98`

### CLI Tools

*   [junegunn/fzf (⭐83k)](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`82,542`
*   [wagoodman/dive (⭐54k)](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`54,451`
*   [xo/usql (⭐10k)](https://github.com/xo/usql) — Universal SQL CLI ☆`10,068`
*   [joshmedeski/sesh (⭐2.8k)](https://github.com/joshmedeski/sesh) — Terminal session manager ☆`2,755`
*   [itchyny/bed (⭐1.3k)](https://github.com/itchyny/bed) — Binary editor in Go ☆`1,345`
*   [owenthereal/upterm (⭐1.3k)](https://github.com/owenthereal/upterm) — Instant terminal sharing ☆`1,274`
*   [alajmo/mani (⭐753)](https://github.com/alajmo/mani) — CLI for managing repositories ☆`753`
*   [Unrud/remote-touchpad (⭐674)](https://github.com/Unrud/remote-touchpad) — Control mouse/keyboard remotely ☆`674`
*   [chenquan/diskusage (⭐311)](https://github.com/chenquan/diskusage) — Fast disk usage analyzer ☆`311`
*   [reugn/wifiqr (⭐287)](https://github.com/reugn/wifiqr) — Generate Wi-Fi QR codes ☆`287`
*   [hedhyw/json-log-viewer (⭐232)](https://github.com/hedhyw/json-log-viewer) — Interactive JSON log viewer ☆`232`
*   [hrtsegv/gitcs (⭐133)](https://github.com/hrtsegv/gitcs) — Git contributions graph generator ☆`133`
*   [antham/yogo (⭐48)](https://github.com/antham/yogo) — Check yopmail from CLI ☆`48`

### Data Conversion

*   [samber/lo (⭐21k)](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`21,402`
*   [duke-git/lancet (⭐5.3k)](https://github.com/duke-git/lancet) — Comprehensive util library ☆`5,299`
*   [darccio/mergo (⭐3.1k)](https://github.com/darccio/mergo) — Merge Go structs and maps ☆`3,106`
*   [goforj/godump (⭐1.8k)](https://github.com/goforj/godump) — Pretty-printer for Go structs ☆`1,754`
*   [gookit/filter (⭐151)](https://github.com/gookit/filter) — Data filtering and conversion ☆`151`
*   [xorcare/pointer (⭐48)](https://github.com/xorcare/pointer) — Create optional field pointers ☆`48`
*   [tiendc/gofn (⭐54)](https://github.com/tiendc/gofn) — High-performance generic functions ☆`54`
*   [shockerli/cvt (⭐53)](https://github.com/shockerli/cvt) — Safe type conversion ☆`53`

### Database Extensions

*   [jmoiron/sqlx (⭐18k)](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,726`
*   [georgysavva/scany (⭐1.5k)](https://github.com/georgysavva/scany) — Scan database rows to structs ☆`1,522`
*   [blockloop/scan (⭐614)](https://github.com/blockloop/scan) — Scan SQL rows to structs ☆`614`

### Date and Time

*   [dromara/carbon (⭐5.2k)](https://github.com/dromara/carbon) — Developer-friendly time package ☆`5,224`
*   [yaa110/go-persian-calendar (⭐243)](https://github.com/yaa110/go-persian-calendar) — Persian calendar for Go ☆`243`
*   [bykof/gostradamus (⭐208)](https://github.com/bykof/gostradamus) — Better DateTimes for Go ☆`208`
*   [relvacode/iso8601 (⭐166)](https://github.com/relvacode/iso8601) — Fast ISO8601 date parser ☆`166`
*   [rickb777/date (⭐143)](https://github.com/rickb777/date) — Date handling package ☆`143`

### Dependency Injection

*   [uber-go/fx (⭐7.6k)](https://github.com/uber-go/fx) — DI-based application framework ☆`7,634`
*   [uber-go/dig (⭐4.5k)](https://github.com/uber-go/dig) — Reflection-based DI toolkit ☆`4,494`
*   [goioc/di (⭐378)](https://github.com/goioc/di) — Simple DI for Go ☆`378`
*   [go-kod/kod (⭐199)](https://github.com/go-kod/kod) — DI with aspect-oriented support ☆`199`
*   [i-love-flamingo/dingo (⭐189)](https://github.com/i-love-flamingo/dingo) — DI framework for Go ☆`189`
*   [NVIDIA/gontainer (⭐154)](https://github.com/NVIDIA/gontainer) — Simple DI container ☆`154`
*   [junioryono/godi (⭐75)](https://github.com/junioryono/godi) — DI with service lifetimes ☆`75`
*   [matzefriedrich/parsley (⭐36)](https://github.com/matzefriedrich/parsley) — Reflection-based DI package ☆`36`
*   [muir/nject (⭐33)](https://github.com/muir/nject) — Type-safe DI for Go ☆`33`
*   [firasdarwish/ore (⭐28)](https://github.com/firasdarwish/ore) — Advanced DI solution ☆`28`
*   [logrange/linker (⭐35)](https://github.com/logrange/linker) — DI and IoC package ☆`35`
*   [componego/componego (⭐29)](https://github.com/componego/componego) — Component-oriented framework ☆`29`

### Error Handling

*   [hashicorp/go-multierror (⭐2.6k)](https://github.com/hashicorp/go-multierror) — Represent multiple errors as one ☆`2,577`
*   [cockroachdb/errors (⭐2.5k)](https://github.com/cockroachdb/errors) — Error library with portability ☆`2,453`
*   [rotisserie/eris (⭐1.8k)](https://github.com/rotisserie/eris) — Errors with readable stack traces ☆`1,794`
*   [joomcode/errorx (⭐1.3k)](https://github.com/joomcode/errorx) — Comprehensive error handling ☆`1,270`
*   [ztrue/tracerr (⭐1.1k)](https://github.com/ztrue/tracerr) — Errors with stack trace ☆`1,120`
*   [samber/oops (⭐980)](https://github.com/samber/oops) — Structured error handling ☆`980`
*   [Southclaws/fault (⭐309)](https://github.com/Southclaws/fault) — Composable error wrapping ☆`309`

### File Handling

*   [schollz/croc (⭐39k)](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`39,707`
*   [qax-os/excelize (⭐21k)](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,852`
*   [pdfcpu/pdfcpu (⭐8.8k)](https://github.com/pdfcpu/pdfcpu) — PDF processor in Go ☆`8,775`
*   [spf13/afero (⭐6.7k)](https://github.com/spf13/afero) — Filesystem abstraction for Go ☆`6,688`
*   [dundee/gdu (⭐5.9k)](https://github.com/dundee/gdu) — Fast disk usage analyzer ☆`5,892`
*   [unidoc/unioffice (⭐4.9k)](https://github.com/unidoc/unioffice) — Office document library ☆`4,921`
*   [root-gg/plik (⭐1.8k)](https://github.com/root-gg/plik) — Temporary file upload system ☆`1,810`
*   [SebastiaanKlippert/go-wkhtmltopdf (⭐1.2k)](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) — HTML to PDF wrapper ☆`1,181`
*   [otiai10/copy (⭐771)](https://github.com/otiai10/copy) — Copy directories recursively ☆`771`
*   [ulikunitz/xz (⭐560)](https://github.com/ulikunitz/xz) — Pure golang package for reading and writing xz-compressed files ☆`560`
*   [mholt/archives (⭐438)](https://github.com/mholt/archives) — Create and extract archives ☆`438`
*   [viant/afs (⭐393)](https://github.com/viant/afs) — Abstract file storage ☆`393`
*   [C2FO/vfs (⭐369)](https://github.com/C2FO/vfs) — Virtual file system for Go ☆`369`
*   [gen2brain/go-unarr (⭐309)](https://github.com/gen2brain/go-unarr) — Decompression library bindings ☆`309`
*   [gomutex/godocx (⭐267)](https://github.com/gomutex/godocx) — Go library for reading and writing Microsoft Docx ☆`267`
*   [charlievieth/fastwalk (⭐143)](https://github.com/charlievieth/fastwalk) — Fast directory traversal ☆`143`
*   [artonge/go-csv-tag (⭐131)](https://github.com/artonge/go-csv-tag) — CSV reading with tags ☆`131`
*   [parsyl/parquet (⭐127)](https://github.com/parsyl/parquet) — Parquet file library ☆`127`
*   [adelowo/gulter (⭐72)](https://github.com/adelowo/gulter) — Multipart form handling ☆`72`
*   [go-the-way/exl (⭐33)](https://github.com/go-the-way/exl) — Excel binding to struct written in Go.(Only supports Go1.18+) ☆`33`

### Forms

*   [justinas/nosurf (⭐1.7k)](https://github.com/justinas/nosurf) — CSRF protection middleware ☆`1,747`
*   [gorilla/csrf (⭐1.2k)](https://github.com/gorilla/csrf) — CSRF prevention middleware ☆`1,205`
*   [go-playground/form (⭐923)](https://github.com/go-playground/form) — URL values to structs ☆`923`
*   [ggicci/httpin (⭐390)](https://github.com/ggicci/httpin) — HTTP request to struct binding ☆`390`
*   [sonh/qs (⭐83)](https://github.com/sonh/qs) — Encode structs to query params ☆`83`
*   [cinar/checker (⭐48)](https://github.com/cinar/checker) — Input validation with struct tags ☆`48`

### Functional

*   [samber/mo (⭐3.4k)](https://github.com/samber/mo) — Monads and FP for Go ☆`3,398`
*   [BooleanCat/go-functional (⭐537)](https://github.com/BooleanCat/go-functional) — Iterator library for Go ☆`537`
*   [rjNemo/underscore (⭐118)](https://github.com/rjNemo/underscore) — Functional helpers for Go ☆`118`

### General

*   [wabarc/wayback (⭐2.2k)](https://github.com/wabarc/wayback) — Web archiving tool with IM interface ☆`2,223`
*   [gabriel-vasile/mimetype (⭐2k)](https://github.com/gabriel-vasile/mimetype) — MIME type detection by magic numbers ☆`2,006`
*   [qmuntal/stateless (⭐1.4k)](https://github.com/qmuntal/stateless) — Go library for creating finite state machines ☆`1,379`
*   [jonboulle/clockwork (⭐727)](https://github.com/jonboulle/clockwork) — a fake clock for golang ☆`727`
*   [Boeing/config-file-validator (⭐512)](https://github.com/Boeing/config-file-validator) — Cross-platform CLI tool to validate configuration files across 18 formats. Syntax and schema validation with JSON Schema, XSD, and SchemaStore integration. Written in Go. ☆`512`
*   [ungerik/go-dry (⭐488)](https://github.com/ungerik/go-dry) — DRY (don't repeat yourself) package for Go ☆`488`
*   [subosito/gotenv (⭐310)](https://github.com/subosito/gotenv) — Load environment variables from `.env` or `io.Reader` in Go. ☆`310`
*   [viant/toolbox (⭐231)](https://github.com/viant/toolbox) — Toolbox - go utility library ☆`231`
*   [maja42/goval (⭐174)](https://github.com/maja42/goval) — Expression evaluation in golang ☆`174`
*   [jfcg/sorty (⭐145)](https://github.com/jfcg/sorty) — Fast Concurrent / Parallel Sorting in Go ☆`145`
*   [commander-cli/cmd (⭐161)](https://github.com/commander-cli/cmd) — A simple package to execute shell commands on linux, windows and osx ☆`161`
*   [syntaqx/cookie (⭐114)](https://github.com/syntaqx/cookie) — Cookies, but with structs, for happiness. ☆`114`
*   [tiendc/go-deepcopy (⭐130)](https://github.com/tiendc/go-deepcopy) — Fast deep-copy library for Go ☆`130`
*   [pioz/countries (⭐98)](https://github.com/pioz/countries) — All you need when you are working with countries in Go. ☆`98`
*   [arthurkushman/pgo (⭐89)](https://github.com/arthurkushman/pgo) — Go library for PHP community with convenient functions ☆`89`
*   [wzshiming/gotype (⭐66)](https://github.com/wzshiming/gotype) — Golang source code parsing, usage like reflect package ☆`66`
*   [rkoesters/xdg (⭐50)](https://github.com/rkoesters/xdg) — FreeDesktop.org (xdg) Specs implemented in Go ☆`50`
*   [icza/backscanner (⭐70)](https://github.com/icza/backscanner) — Scan file lines backward ☆`70`
*   [nikolaydubina/watchhttp (⭐35)](https://github.com/nikolaydubina/watchhttp) — Expose command output via HTTP ☆`35`
*   [mikekonan/go-types (⭐24)](https://github.com/mikekonan/go-types) — OpenAPI3 types for Go ☆`24`
*   [kazhuravlev/just (⭐38)](https://github.com/kazhuravlev/just) — Collection of useful functions. Complete simple tasks faster! ☆`38`
*   [lrita/numa (⭐40)](https://github.com/lrita/numa) — NUMA utility library for Go ☆`40`
*   [osamingo/gosh (⭐37)](https://github.com/osamingo/gosh) — Provide Go Statistics Handler, Struct, Measure Method ☆`37`
*   [floatdrop/debounce (⭐36)](https://github.com/floatdrop/debounce) — A zero-allocation debouncer ☆`36`
*   [skovtunenko/graterm (⭐30)](https://github.com/skovtunenko/graterm) — Graceful termination primitives ☆`30`

### Logging

*   [sirupsen/logrus (⭐26k)](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,752`
*   [uber-go/zap (⭐25k)](https://github.com/uber-go/zap) — Fast structured logging ☆`24,654`
*   [rs/zerolog (⭐12k)](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,490`
*   [golang/glog (⭐3.6k)](https://github.com/golang/glog) — Leveled execution logs ☆`3,599`
*   [k0kubun/pp (⭐2.1k)](https://github.com/k0kubun/pp) — Colored pretty printer for Go ☆`2,051`
*   [Lifailon/lazyjournal (⭐1.4k)](https://github.com/Lifailon/lazyjournal) — TUI for journald, Docker, K8s logs ☆`1,376`
*   [lmittmann/tint (⭐1.3k)](https://github.com/lmittmann/tint) — Colorized slog handler ☆`1,334`
*   [getsentry/sentry-go (⭐1.1k)](https://github.com/getsentry/sentry-go) — Official Sentry SDK for Go ☆`1,102`
*   [phuslu/log (⭐869)](https://github.com/phuslu/log) — Fastest structured logging ☆`869`
*   [samber/slog-multi (⭐632)](https://github.com/samber/slog-multi) — Workflow design for slog handlers ☆`632`
*   [gookit/slog (⭐553)](https://github.com/gookit/slog) — Configurable logging library ☆`553`
*   [henvic/httpretty (⭐451)](https://github.com/henvic/httpretty) — Pretty-print HTTP requests ☆`452`
*   [simukti/sqldb-logger (⭐379)](https://github.com/simukti/sqldb-logger) — SQL database logger ☆`379`
*   [hashicorp/logutils (⭐371)](https://github.com/hashicorp/logutils) — Logging utilities for Go ☆`371`
*   [samber/slog-formatter (⭐225)](https://github.com/samber/slog-formatter) — Slog attribute formatting ☆`225`
*   [DeRuina/timberjack (⭐155)](https://github.com/DeRuina/timberjack) — Log rolling library ☆`156`
*   [yuseferi/zax (⭐38)](https://github.com/yuseferi/zax) — Zap logger with context ☆`38`
*   [clok/kemba (⭐18)](https://github.com/clok/kemba) — Tiny debug logging tool ☆`18`

### Networking Utils

*   [cristianoliveira/ergo (⭐651)](https://github.com/cristianoliveira/ergo) — Manage apps on different ports ☆`651`
*   [htcat/htcat (⭐557)](https://github.com/htcat/htcat) — Parallel HTTP download ☆`557`
*   [ferama/rospo (⭐372)](https://github.com/ferama/rospo) — Persistent SSH tunnels ☆`372`

### Project Layout

*   [golang-standards/project-layout (⭐56k)](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`56,451`
*   [Melkeydev/go-blueprint (⭐8.9k)](https://github.com/Melkeydev/go-blueprint) — Spin up Go projects with popular frameworks ☆`8,910`
*   [ardanlabs/service (⭐4.1k)](https://github.com/ardanlabs/service) — K8s service starter kit ☆`4,103`
*   [Shpota/goxygen (⭐3.6k)](https://github.com/Shpota/goxygen) — Generate full-stack web projects ☆`3,594`
*   [mikestefanello/pagoda (⭐3k)](https://github.com/mikestefanello/pagoda) — Full-stack web development starter kit ☆`2,952`
*   [go-nunu/nunu (⭐2.6k)](https://github.com/go-nunu/nunu) — CLI for building Go apps ☆`2,593`
*   [sagikazarmark/modern-go-application (⭐1.9k)](https://github.com/sagikazarmark/modern-go-application) — Modern Go app example ☆`1,943`
*   [naughtygopher/goapp (⭐1.1k)](https://github.com/naughtygopher/goapp) — Opinionated web app structure ☆`1,070`
*   [lacion/cookiecutter-golang (⭐736)](https://github.com/lacion/cookiecutter-golang) — Go project template ☆`736`
*   [allaboutapps/go-starter (⭐621)](https://github.com/allaboutapps/go-starter) — Production-ready RESTful API template ☆`621`
*   [golang-templates/seed (⭐565)](https://github.com/golang-templates/seed) — Go app GitHub template ☆`565`
*   [Fs02/go-todo-backend (⭐337)](https://github.com/Fs02/go-todo-backend) — Go Todo Backend example using modular project layout for product microservice. ☆`335`
*   [raeperd/kickstart.go (⭐111)](https://github.com/raeperd/kickstart.go) — Minimal HTTP server template ☆`111`
*   [wangyoucao577/go-project-layout (⭐26)](https://github.com/wangyoucao577/go-project-layout) — Go project structure guide ☆`26`

### Resilience & Retry

*   [avast/retry-go (⭐2.9k)](https://github.com/avast/retry-go) — Simple retry mechanism ☆`2,949`
*   [eapache/go-resiliency (⭐2.3k)](https://github.com/eapache/go-resiliency) — Resiliency patterns for golang ☆`2,345`
*   [failsafe-go/failsafe-go (⭐2.2k)](https://github.com/failsafe-go/failsafe-go) — Fault tolerance patterns ☆`2,241`
*   [cep21/circuit (⭐815)](https://github.com/cep21/circuit) — Hystrix-like circuit breaker ☆`815`
*   [mennanov/limiters (⭐651)](https://github.com/mennanov/limiters) — Distributed rate limiters ☆`651`
*   [kamilsk/retry (⭐344)](https://github.com/kamilsk/retry) — Advanced retry mechanism ☆`344`
*   [webriots/rate (⭐170)](https://github.com/webriots/rate) — High-performance rate limiter ☆`170`

### Strings

*   [abhimanyu003/sttr (⭐1.3k)](https://github.com/abhimanyu003/sttr) — CLI string operations ☆`1,339`
*   [gobeam/stringy (⭐250)](https://github.com/gobeam/stringy) — String case conversions ☆`250`
*   [ozgio/strutil (⭐206)](https://github.com/ozgio/strutil) — String utilities for Go ☆`206`

### System & Process

*   [cilium/ebpf (⭐7.9k)](https://github.com/cilium/ebpf) — eBPF library for Go ☆`7,912`
*   [maruel/panicparse (⭐3.7k)](https://github.com/maruel/panicparse) — Crash your app in style ☆`3,710`
*   [immortal/immortal (⭐838)](https://github.com/immortal/immortal) — Cross-platform supervisor ☆`838`
*   [derekparker/delve (⭐661)](https://github.com/derekparker/delve) — Delve is a debugger for the Go programming language. ☆`661`
*   [gotranspile/cxgo (⭐395)](https://github.com/gotranspile/cxgo) — Transpile C to Go ☆`395`

### UUID

*   [google/uuid (⭐6.1k)](https://github.com/google/uuid) — UUID generation and parsing ☆`6,134`
*   [oklog/ulid (⭐5k)](https://github.com/oklog/ulid) — ULID implementation ☆`5,048`
*   [gofrs/uuid (⭐1.8k)](https://github.com/gofrs/uuid) — UUID library for Go ☆`1,811`
*   [osamingo/indigo (⭐111)](https://github.com/osamingo/indigo) — Sonyflake-based ID generator ☆`111`
*   [sdrapkin/guid (⭐75)](https://github.com/sdrapkin/guid) — Fast cryptographically safe Guid generator for Go ☆`75`
*   [twharmon/gouid (⭐27)](https://github.com/twharmon/gouid) — Fast, dependable universally unique ids ☆`27`

## Version Control & Packages

### Git APIs

*   [google/go-github (⭐11k)](https://github.com/google/go-github) — Go library for accessing the GitHub v3 API ☆`11,281`
*   [shurcooL/githubv4 (⭐1.2k)](https://github.com/shurcooL/githubv4) — GitHub GraphQL API v4 client ☆`1,197`
*   [andygrunwald/go-trending (⭐147)](https://github.com/andygrunwald/go-trending) — Access GitHub trending repositories ☆`147`
*   [andygrunwald/go-gerrit (⭐106)](https://github.com/andygrunwald/go-gerrit) — Go client/library for Gerrit Code Review ☆`106`

### Package Management

*   [anchore/syft (⭐9.4k)](https://github.com/anchore/syft) — SBOM generator for containers ☆`9,394`
*   [nao1215/gup (⭐596)](https://github.com/nao1215/gup) — Fast manager for Go-installed binaries in $GOBIN: update, export/import, and migrate toolsets across machines ☆`596`
*   [marwanhawari/stew (⭐353)](https://github.com/marwanhawari/stew) — An independent package manager for compiled binaries. ☆`353`
*   [chaindead/modup (⭐65)](https://github.com/chaindead/modup) — TUI for Go dependency updates ☆`65`

### Version Control

*   [go-git/go-git (⭐7.7k)](https://github.com/go-git/go-git) — Pure Go Git implementation ☆`7,665`
*   [antham/chyle (⭐163)](https://github.com/antham/chyle) — Changelog generator from Git ☆`163`
*   [antham/gommit (⭐117)](https://github.com/antham/gommit) — Enforce git message commit consistency ☆`117`
*   [gabyx/Githooks (⭐127)](https://github.com/gabyx/Githooks) — Per-repo shared Git hooks ☆`127`
*   [sourcegraph/go-vcs (⭐82)](https://github.com/sourcegraph/go-vcs) — manipulate and inspect VCS repositories in Go ☆`82`
*   [jfrog/froggit-go (⭐54)](https://github.com/jfrog/froggit-go) — Universal VCS client library ☆`54`
*   [kazhuravlev/git-tools (⭐33)](https://github.com/kazhuravlev/git-tools) — Useful set of tools which helps to manage git tags ☆`33`

## Web Development

### Microservices

*   [zeromicro/go-zero (⭐33k)](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`33,262`
*   [go-kratos/kratos (⭐26k)](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,866`
*   [micro/go-micro (⭐23k)](https://github.com/micro/go-micro) — A Go agent harness and service framework ☆`23,009`
*   [smallnest/rpcx (⭐8.3k)](https://github.com/smallnest/rpcx) — Feature-rich RPC framework ☆`8,311`
*   [cloudwego/kitex (⭐8k)](https://github.com/cloudwego/kitex) — High-performance Go RPC framework ☆`8,016`
*   [go-dev-frame/sponge (⭐2.9k)](https://github.com/go-dev-frame/sponge) — Code generation framework for Go ☆`2,855`
*   [go-eagle/eagle (⭐2.4k)](https://github.com/go-eagle/eagle) — A Go framework for the API or Microservice ☆`2,428`
*   [trpc-group/trpc-go (⭐1.2k)](https://github.com/trpc-group/trpc-go) — A pluggable, high-performance RPC framework written in golang ☆`1,189`
*   [unionj-cloud/go-doudou (⭐1.2k)](https://github.com/unionj-cloud/go-doudou) — OpenAPI 3 and gRPC microservices framework ☆`1,172`
*   [gmsec/micro (⭐27)](https://github.com/gmsec/micro) — A Go distributed systems development framework ☆`27`

### Middlewares

*   [urfave/negroni (⭐7.5k)](https://github.com/urfave/negroni) — Idiomatic HTTP Middleware for Golang ☆`7,526`
*   [tdewolff/minify (⭐4.1k)](https://github.com/tdewolff/minify) — Go minifiers for web formats ☆`4,132`
*   [rs/cors (⭐2.9k)](https://github.com/rs/cors) — Go net/http configurable handler to handle CORS requests ☆`2,895`
*   [didip/tollbooth (⭐2.9k)](https://github.com/didip/tollbooth) — Simple middleware to rate-limit HTTP requests. ☆`2,858`
*   [unrolled/render (⭐2k)](https://github.com/unrolled/render) — Render JSON, XML, HTML, binary ☆`1,997`
*   [lingrino/go-fault (⭐554)](https://github.com/lingrino/go-fault) — go fault injection library ☆`555`
*   [jub0bs/cors (⭐224)](https://github.com/jub0bs/cors) — perhaps the best CORS middleware library for Go ☆`224`
*   [faabiosr/echo-middleware (⭐16)](https://github.com/faabiosr/echo-middleware) — Middlewares for Echo framework ☆`16`

### Routers

*   [go-chi/chi (⭐23k)](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`22,664`
*   [gorilla/mux (⭐22k)](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,843`
*   [gowww/router (⭐185)](https://github.com/gowww/router) — A lightning fast HTTP router ☆`185`
*   [claygod/Bxog (⭐104)](https://github.com/claygod/Bxog) — Bxog is a simple and fast HTTP router for Go (HTTP request multiplexer). ☆`104`
*   [ngamux/ngamux (⭐71)](https://github.com/ngamux/ngamux) — Simple HTTP router for Go ☆`71`
*   [bmf-san/goblin (⭐81)](https://github.com/bmf-san/goblin) — A golang http router based on trie tree. ☆`81`
*   [muir/nchi (⭐19)](https://github.com/muir/nchi) — golang http router with elegance, speed, and flexibility ☆`19`

### Template Engines

*   [a-h/templ (⭐10k)](https://github.com/a-h/templ) — A language for writing HTML user interfaces in Go. ☆`10,479`
*   [johnfercher/maroto (⭐2.7k)](https://github.com/johnfercher/maroto) — Create PDFs with Bootstrap grid ☆`2,747`
*   [CloudyKit/jet (⭐1.4k)](https://github.com/CloudyKit/jet) — Jet template engine ☆`1,403`
*   [osteele/liquid (⭐354)](https://github.com/osteele/liquid) — A Liquid template engine in Go ☆`354`
*   [go-sprout/sprout (⭐224)](https://github.com/go-sprout/sprout) — Template functions for Go ☆`224`
*   [goradd/got (⭐38)](https://github.com/goradd/got) — Template engine with Go code output ☆`38`

### Web Frameworks

*   [gin-gonic/gin (⭐89k)](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`89,111`
*   [gofiber/fiber (⭐40k)](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`40,062`
*   [beego/beego (⭐32k)](https://github.com/beego/beego) — High-performance web framework ☆`32,416`
*   [labstack/echo (⭐33k)](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,645`
*   [gofr-dev/gofr (⭐21k)](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`21,026`
*   [gogf/gf (⭐13k)](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,244`
*   [cloudwego/hertz (⭐7.3k)](https://github.com/cloudwego/hertz) — High-performance HTTP framework ☆`7,332`
*   [goadesign/goa (⭐6.1k)](https://github.com/goadesign/goa) — Design-first API framework ☆`6,089`
*   [apache/dubbo-go (⭐4.9k)](https://github.com/apache/dubbo-go) — Go Implementation For Apache Dubbo . ☆`4,947`
*   [goravel/goravel (⭐4.8k)](https://github.com/goravel/goravel) — The full-featured Golang Development Framework skeleton ☆`4,801`
*   [danielgtaylor/huma (⭐4.3k)](https://github.com/danielgtaylor/huma) — Huma REST/HTTP API Framework for Golang with OpenAPI 3.1 ☆`4,316`
*   [documize/community (⭐2.4k)](https://github.com/documize/community) — Modern Confluence alternative ☆`2,414`
*   [go-goyave/goyave (⭐1.8k)](https://github.com/go-goyave/goyave) — The enterprise REST API framework ☆`1,774`
*   [go-fuego/fuego (⭐1.8k)](https://github.com/go-fuego/fuego) — Web framework with OpenAPI 3 ☆`1,759`
*   [axadrn/shadcn-templ (⭐1.7k)](https://github.com/axadrn/shadcn-templ) — UI components for Templ ☆`1,699`
*   [savsgio/atreugo (⭐1.3k)](https://github.com/savsgio/atreugo) — Micro web framework on fasthttp ☆`1,302`
*   [ankorstore/yokai (⭐839)](https://github.com/ankorstore/yokai) — Modular framework for Go apps ☆`839`
*   [indeedeng/iwf (⭐655)](https://github.com/indeedeng/iwf) — Workflow-as-code orchestration ☆`655`
*   [i-love-flamingo/flamingo-commerce (⭐591)](https://github.com/i-love-flamingo/flamingo-commerce) — Flexible Go web framework ☆`591`
*   [fastschema/fastschema (⭐569)](https://github.com/fastschema/fastschema) — All-in-One Backend as a Service with Headless CMS Power ☆`570`
*   [i-love-flamingo/flamingo (⭐559)](https://github.com/i-love-flamingo/flamingo) — Flexible Go web framework ☆`559`
*   [rookie-ninja/rk-boot (⭐571)](https://github.com/rookie-ninja/rk-boot) — Enterprise microservice framework ☆`571`
*   [uadmin/uadmin (⭐354)](https://github.com/uadmin/uadmin) — The web framework for Golang ☆`354`
*   [xxjwxc/ginrpc (⭐303)](https://github.com/xxjwxc/ginrpc) — gin auto binding, grpc and annotated route ☆`303`
*   [hidevopsio/hiboot (⭐179)](https://github.com/hidevopsio/hiboot) — High-performance CLI and web apps ☆`179`
*   [beatlabs/patron (⭐127)](https://github.com/beatlabs/patron) — Cloud-native microservice framework ☆`127`
*   [claygod/microservice (⭐123)](https://github.com/claygod/microservice) — Simple microservice framework ☆`123`
*   [gone-io/gone (⭐131)](https://github.com/gone-io/gone) — Lightweight DI framework ☆`131`
*   [gookit/rux (⭐100)](https://github.com/gookit/rux) — Simple and fast web framework ☆`100`
*   [yaitoo/xun (⭐92)](https://github.com/yaitoo/xun) — Web framework on html/template ☆`92`
*   [napsy/go-css (⭐94)](https://github.com/napsy/go-css) — A very simple CSS parser, written in Go ☆`94`
*   [abemedia/go-don (⭐60)](https://github.com/abemedia/go-don) — API framework written in Golang. ☆`60`
*   [JiveGroup/gFly (⭐49)](https://github.com/JiveGroup/gFly) — Laravel inspired web framework written in Go ☆`50`
*   [clubpay/ronykit (⭐38)](https://github.com/clubpay/ronykit) — API Framework supporting REST and RPC. ☆`38`
*   [SaiNageswarS/go-api-boot (⭐35)](https://github.com/SaiNageswarS/go-api-boot) — gRPC + HTTP/2 production framework ☆`35`

### WebAssembly

*   [tinygo-org/tinygo (⭐18k)](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,643`
*   [agnivade/wasmbrowsertest (⭐211)](https://github.com/agnivade/wasmbrowsertest) — Run WASM tests inside your browser ☆`211`
*   [extism/go-sdk (⭐182)](https://github.com/extism/go-sdk) — Extism Go SDK - easily run WebAssembly modules in your Go applications ☆`182`

## Workflow & Scheduling

### Job Scheduler

*   [hatchet-dev/hatchet (⭐7.7k)](https://github.com/hatchet-dev/hatchet) — An orchestration engine for background tasks, AI agents, and durable workflows ☆`7,713`
*   [go-co-op/gocron (⭐7.1k)](https://github.com/go-co-op/gocron) — Easy and fluent Go cron scheduling ☆`7,133`
*   [reugn/go-quartz (⭐2k)](https://github.com/reugn/go-quartz) — Minimalist and zero-dependency scheduling library for Go ☆`2,014`
*   [adhocore/gronx (⭐513)](https://github.com/adhocore/gronx) — Lightweight cron expression parser ☆`513`
*   [fieldryand/goflow (⭐481)](https://github.com/fieldryand/goflow) — Simple but powerful DAG scheduler and dashboard ☆`481`
*   [madflojo/tasks (⭐333)](https://github.com/madflojo/tasks) — In-process task scheduler ☆`333`
*   [bart6114/cheek (⭐201)](https://github.com/bart6114/cheek) — cheek: a pico-sized declarative job scheduler ☆`201`
*   [onatm/clockwerk (⭐183)](https://github.com/onatm/clockwerk) — Job Scheduling Library ☆`183`
*   [deepaksinghvi/cdule (⭐61)](https://github.com/deepaksinghvi/cdule) — Golang job scheduler ☆`61`
*   [pardnchiu/go-scheduler (⭐36)](https://github.com/pardnchiu/go-scheduler) — (module) A Go scheduling library with task dependencies, timeout control, and cron expressions ☆`36`
*   [romshark/sched (⭐31)](https://github.com/romshark/sched) — A job scheduler for Go with the ability to fast-forward time. ☆`31`

### Workflow Frameworks

*   [redpanda-data/connect (⭐8.7k)](https://github.com/redpanda-data/connect) — Fancy stream processing made operationally mundane ☆`8,731`
*   [dagucloud/dagu (⭐3.7k)](https://github.com/dagucloud/dagu) — Workflow engine with Web UI ☆`3,741`
*   [jf-tech/omniparser (⭐1.1k)](https://github.com/jf-tech/omniparser) — ETL streaming parser for Go ☆`1,084`
*   [noneback/go-taskflow (⭐637)](https://github.com/noneback/go-taskflow) — Task-parallel programming library ☆`637`
*   [cadence-workflow/cadence-go-client (⭐380)](https://github.com/cadence-workflow/cadence-go-client) — Cadence workflow client for Go ☆`382`
*   [luno/workflow (⭐252)](https://github.com/luno/workflow) — Type-safe workflow orchestration ☆`253`
*   [rhosocial/go-dag (⭐41)](https://github.com/rhosocial/go-dag) — DAG-based workflow framework ☆`41`

***

## 🏆 Top 100 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1.  [ollama/ollama (⭐178k)](https://github.com/ollama/ollama) — Run LLMs locally ☆`178,403`
2.  [kubernetes/kubernetes (⭐124k)](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`124,477`
3.  [gin-gonic/gin (⭐89k)](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`89,111`
4.  [junegunn/fzf (⭐83k)](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`82,542`
5.  [caddyserver/caddy (⭐75k)](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`74,899`
6.  [moby/moby (⭐72k)](https://github.com/moby/moby) — Container ecosystem components ☆`72,013`
7.  [prometheus/prometheus (⭐66k)](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`65,724`
8.  [traefik/traefik (⭐64k)](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`64,443`
9.  [pocketbase/pocketbase (⭐61k)](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`60,640`
10. [go-gitea/gitea (⭐57k)](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`57,351`
11. [golang-standards/project-layout (⭐56k)](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`56,451`
12. [wagoodman/dive (⭐54k)](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`54,451`
13. [etcd-io/etcd (⭐52k)](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`52,120`
14. [ethereum/go-ethereum (⭐51k)](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`51,284`
15. [mudler/LocalAI (⭐48k)](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`48,418`
16. [milvus-io/milvus (⭐45k)](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`45,620`
17. [spf13/cobra (⭐44k)](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`44,454`
18. [charmbracelet/bubbletea (⭐44k)](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`44,334`
19. [pingcap/tidb (⭐40k)](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`40,426`
20. [gofiber/fiber (⭐40k)](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`40,062`
21. [go-gorm/gorm (⭐40k)](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,915`
22. [schollz/croc (⭐39k)](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`39,707`
23. [harness/harness (⭐38k)](https://github.com/harness/harness) — End-to-end developer platform ☆`37,799`
24. [restic/restic (⭐35k)](https://github.com/restic/restic) — Fast, secure backup program ☆`35,486`
25. [seaweedfs/seaweedfs (⭐34k)](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`34,038`
26. [k3s-io/k3s (⭐34k)](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`33,728`
27. [zeromicro/go-zero (⭐33k)](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`33,262`
28. [labstack/echo (⭐33k)](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,645`
29. [beego/beego (⭐32k)](https://github.com/beego/beego) — High-performance web framework ☆`32,416`
30. [cockroachdb/cockroach (⭐32k)](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`32,384`
31. [kubernetes/minikube (⭐32k)](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`32,027`
32. [influxdata/influxdb (⭐32k)](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,689`
33. [grafana/k6 (⭐31k)](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`31,248`
34. [spf13/viper (⭐30k)](https://github.com/spf13/viper) — Go configuration with fangs ☆`30,430`
35. [fyne-io/fyne (⭐29k)](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`28,590`
36. [stretchr/testify (⭐26k)](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`26,154`
37. [go-kratos/kratos (⭐26k)](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,866`
38. [sirupsen/logrus (⭐26k)](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,752`
39. [gocolly/colly (⭐25k)](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,417`
40. [tsenart/vegeta (⭐25k)](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`25,144`
41. [uber-go/zap (⭐25k)](https://github.com/uber-go/zap) — Fast structured logging ☆`24,654`
42. [urfave/cli (⭐24k)](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`24,193`
43. [dolthub/dolt (⭐24k)](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`24,167`
44. [air-verse/air (⭐24k)](https://github.com/air-verse/air) — Live reload for Go apps ☆`23,874`
45. [valyala/fasthttp (⭐23k)](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,429`
46. [FiloSottile/age (⭐23k)](https://github.com/FiloSottile/age) — Simple encryption tool ☆`23,198`
47. [jaegertracing/jaeger (⭐23k)](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`23,097`
48. [grpc/grpc-go (⭐23k)](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`23,038`
49. [micro/go-micro (⭐23k)](https://github.com/micro/go-micro) — A Go agent harness and service framework ☆`23,009`
50. [go-chi/chi (⭐23k)](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`22,664`
51. [redis/go-redis (⭐22k)](https://github.com/redis/go-redis) — Redis Go client ☆`22,222`
52. [gorilla/mux (⭐22k)](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,843`
53. [dgraph-io/dgraph (⭐22k)](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,772`
54. [samber/lo (⭐21k)](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`21,402`
55. [vitessio/vitess (⭐21k)](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`21,220`
56. [gofr-dev/gofr (⭐21k)](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`21,026`
57. [qax-os/excelize (⭐21k)](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,852`
58. [antonmedv/fx (⭐21k)](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,578`
59. [nats-io/nats-server (⭐20k)](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`20,486`
60. [apache/casbin (⭐20k)](https://github.com/apache/casbin) — Authorization library for Go ☆`20,322`
61. [go-playground/validator (⭐20k)](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`20,109`
62. [golangci/golangci-lint (⭐19k)](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`19,247`
63. [golang-migrate/migrate (⭐19k)](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,813`
64. [keploy/keploy (⭐18k)](https://github.com/keploy/keploy) — API testing with auto mocks ☆`18,398`
65. [sqlc-dev/sqlc (⭐18k)](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`18,161`
66. [jmoiron/sqlx (⭐18k)](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,726`
67. [rqlite/rqlite (⭐18k)](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,675`
68. [tinygo-org/tinygo (⭐18k)](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,643`
69. [VictoriaMetrics/VictoriaMetrics (⭐18k)](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`17,521`
70. [ent/ent (⭐17k)](https://github.com/ent/ent) — An entity framework for Go ☆`17,170`
71. [ipfs/kubo (⭐17k)](https://github.com/ipfs/kubo) — IPFS implementation in Go: a daemon that stores and serves content-addressed data, with a CLI, HTTP Gateway, and RPC API ☆`17,100`
72. [pion/webrtc (⭐17k)](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,713`
73. [fatih/vim-go (⭐16k)](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,219`
74. [goreleaser/goreleaser (⭐16k)](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,981`
75. [go-task/task (⭐16k)](https://github.com/go-task/task) — Fast cross-platform build tool inspired by Make ☆`15,959`
76. [hashicorp/packer (⭐16k)](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,754`
77. [dgraph-io/badger (⭐16k)](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,750`
78. [tidwall/gjson (⭐16k)](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,551`
79. [kubernetes-sigs/kind (⭐15k)](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,414`
80. [go-sql-driver/mysql (⭐15k)](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,278`
81. [cloudflare/cloudflared (⭐15k)](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`15,200`
82. [PuerkitoBio/goquery (⭐15k)](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,975`
83. [panjf2000/ants (⭐14k)](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,488`
84. [bytebase/bytebase (⭐14k)](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`14,375`
85. [juicedata/juicefs (⭐14k)](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`14,312`
86. [webview/webview (⭐14k)](https://github.com/webview/webview) — Tiny webview library for Go ☆`14,199`
87. [jackc/pgx (⭐14k)](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`14,130`
88. [hibiken/asynq (⭐14k)](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`13,625`
89. [gizak/termui (⭐14k)](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,583`
90. [hajimehoshi/ebiten (⭐13k)](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`13,399`
91. [golang/groupcache (⭐13k)](https://github.com/golang/groupcache) — Distributed cache library ☆`13,337`
92. [chromedp/chromedp (⭐13k)](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`13,251`
93. [gogf/gf (⭐13k)](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,244`
94. [gopherjs/gopherjs (⭐13k)](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,173`
95. [IBM/sarama (⭐12k)](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,505`
96. [rs/zerolog (⭐12k)](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,490`
97. [drakkan/sftpgo (⭐12k)](https://github.com/drakkan/sftpgo) — Full-featured SFTP/FTP/HTTP server ☆`12,396`
98. [Shopify/toxiproxy (⭐12k)](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`12,238`
99. [kubeshark/kubeshark (⭐12k)](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`12,037`
100.    [adnanh/webhook (⭐12k)](https://github.com/adnanh/webhook) — Lightweight webhook server ☆`12,035`

## Gophers

*   [MariaLetta/free-gophers-pack (⭐4k)](https://github.com/MariaLetta/free-gophers-pack) — This pack of 100+ gopher pictures and elements
*   [keygx/Go-gopher-Vector (⭐76)](https://github.com/keygx/Go-gopher-Vector) — Go gopher Vector Data (.ai, .svg)
*   [ashleymcnamara/gophers (⭐3.1k)](https://github.com/ashleymcnamara/gophers) — Gopher Artwork by Ashley McNamara
*   [sillecelik/go-gopher (⭐163)](https://github.com/sillecelik/go-gopher) — The Go Gopher Amigurumi Pattern
*   [GolangUA/gopher-logos (⭐141)](https://github.com/GolangUA/gopher-logos) — adorable gopher logos
*   [egonelbre/gophers (⭐3.8k)](https://github.com/egonelbre/gophers) — gophers artwork
*   [scraly/gophers (⭐37)](https://github.com/scraly/gophers) — Gopher artwork (Golang mascot)

## Contributing

Please see [CONTRIBUTING](https://github.com/abordage/awesome-go/blob/main/README.md/.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request — contributions are welcome!

## Credits

*   [avelino/awesome-go (⭐181k)](https://github.com/avelino/awesome-go)
*   [All Contributors (⭐5)](https://github.com/abordage/awesome-go/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](https://github.com/abordage/awesome-go/blob/main/README.md/LICENSE) for more information.

