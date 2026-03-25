# Awesome Go Overview

Structured collection of Go frameworks, libraries, tools, and resources. Automatically maintained and up-to-date with metadata, filtering, and comprehensive categorization.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/abordage/awesome-go/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 abordage/awesome-go](https://github.com/abordage/awesome-go) · ⭐ 3 · 🏷️ Programming Languages

[ [Daily](/content/abordage/awesome-go/README.md) / [Weekly](/content/abordage/awesome-go/week/README.md) / Overview ]

---

# Awesome Go

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-go?label=last%20update)](https://github.com/abordage/awesome-go/blob/main/README.md/README.md)
![Repositories](https://img.shields.io/badge/repositories-1,201-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-4,950,801-gold)
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

*   [sashabaranov/go-openai (⭐11k)](https://github.com/sashabaranov/go-openai) — OpenAI API client for Go ☆`10,602`
*   [wit-ai/wit-go (⭐170)](https://github.com/wit-ai/wit-go) — Go client for wit.ai HTTP API ☆`170`

### Artificial Intelligence

*   [ollama/ollama (⭐165k)](https://github.com/ollama/ollama) — Run LLMs locally ☆`166,077`
*   [mudler/LocalAI (⭐43k)](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`44,336`
*   [tmc/langchaingo (⭐8.8k)](https://github.com/tmc/langchaingo) — LangChain for Go, the easiest way to write LLM-based programs in Go ☆`8,936`
*   [maximhq/bifrost (⭐2.8k)](https://github.com/maximhq/bifrost) — Fastest LLM gateway for Go ☆`3,162`
*   [philippgille/chromem-go (⭐891)](https://github.com/philippgille/chromem-go) — Embeddable vector database for Go ☆`900`
*   [universal-tool-calling-protocol/go-utcp (⭐101)](https://github.com/universal-tool-calling-protocol/go-utcp) — Official Go implementation of the UTCP ☆`101`
*   [presbrey/ollamafarm (⭐95)](https://github.com/presbrey/ollamafarm) — Manage multiple Ollama instances ☆`95`

### Machine Learning

*   [gorgonia/gorgonia (⭐5.9k)](https://github.com/gorgonia/gorgonia) — Machine learning library for Go ☆`5,914`
*   [otiai10/gosseract (⭐3.1k)](https://github.com/otiai10/gosseract) — OCR using Tesseract in Go ☆`3,079`
*   [gomlx/gomlx (⭐1.3k)](https://github.com/gomlx/gomlx) — GoMLX: An Accelerated Machine Learning Framework For Go ☆`1,346`
*   [jbrukh/bayesian (⭐811)](https://github.com/jbrukh/bayesian) — Naive Bayesian Classification for Golang. ☆`811`
*   [knights-analytics/hugot (⭐574)](https://github.com/knights-analytics/hugot) — Onnx transformer pipelines in Golang ☆`580`
*   [patrikeh/go-deep (⭐555)](https://github.com/patrikeh/go-deep) — Artificial Neural Network ☆`555`
*   [c-bata/goptuna (⭐277)](https://github.com/c-bata/goptuna) — A hyperparameter optimization framework, inspired by Optuna. ☆`277`

## Audio & Video

### Audio

*   [ebitengine/oto (⭐1.9k)](https://github.com/ebitengine/oto) — A low-level library to play sound on multiple platforms ☆`1,888`
*   [gordonklaus/portaudio (⭐834)](https://github.com/gordonklaus/portaudio) — Go bindings for the PortAudio audio I/O library ☆`835`
*   [gen2brain/malgo (⭐391)](https://github.com/gen2brain/malgo) — Mini audio library ☆`396`
*   [DylanMeeus/GoAudio (⭐409)](https://github.com/DylanMeeus/GoAudio) — Go tools for audio processing & creation ☆`410`
*   [mewkiz/flac (⭐351)](https://github.com/mewkiz/flac) — Package flac provides access to FLAC (Free Lossless Audio Codec) streams. ☆`351`
*   [tosone/minimp3 (⭐133)](https://github.com/tosone/minimp3) — Decode mp3 ☆`133`

### Images

*   [hybridgroup/gocv (⭐7.4k)](https://github.com/hybridgroup/gocv) — Computer vision with OpenCV 4 ☆`7,405`
*   [anthonynsimon/bild (⭐4.2k)](https://github.com/anthonynsimon/bild) — Image processing algorithms in pure Go ☆`4,186`
*   [cshum/imagor (⭐3.9k)](https://github.com/cshum/imagor) — Fast, secure image processing server and Go library, using libvips ☆`3,920`
*   [thoas/picfit (⭐2.3k)](https://github.com/thoas/picfit) — An image resizing server written in Go ☆`2,329`
*   [gographics/imagick (⭐1.9k)](https://github.com/gographics/imagick) — Go binding to ImageMagick's MagickWand C API ☆`1,867`
*   [tdewolff/canvas (⭐1.8k)](https://github.com/tdewolff/canvas) — Vector graphics in Go ☆`1,794`
*   [davidbyttow/govips (⭐1.5k)](https://github.com/davidbyttow/govips) — A lightning fast image processing and resizing library for Go ☆`1,548`
*   [yeqown/go-qrcode (⭐819)](https://github.com/yeqown/go-qrcode) — Customizable QR code generator ☆`820`
*   [HugoSmits86/nativewebp (⭐399)](https://github.com/HugoSmits86/nativewebp) — Native webp encoder for Go ☆`403`
*   [auyer/steganography (⭐353)](https://github.com/auyer/steganography) — LSB steganography in pure Go ☆`353`
*   [kolesa-team/go-webp (⭐303)](https://github.com/kolesa-team/go-webp) — Simple and fast webp library for golang ☆`303`
*   [Pixboost/transformimgs (⭐289)](https://github.com/Pixboost/transformimgs) — Open source image CDN. ☆`289`
*   [qmuntal/gltf (⭐276)](https://github.com/qmuntal/gltf) — Go library for encoding glTF 2.0 files ☆`278`
*   [gojek/darkroom (⭐236)](https://github.com/gojek/darkroom) — Image processing engine and proxy service ☆`236`
*   [aofei/cameron (⭐131)](https://github.com/aofei/cameron) — An avatar generator for Go. ☆`131`
*   [piglig/go-qr (⭐47)](https://github.com/piglig/go-qr) — A native, high-quality and minimalistic QR code generator ☆`47`

### Video

*   [asticode/go-astisub (⭐689)](https://github.com/asticode/go-astisub) — Manipulate subtitles in Go ☆`690`
*   [asticode/go-astiav (⭐682)](https://github.com/asticode/go-astiav) — Golang ffmpeg and libav C bindings ☆`687`
*   [Eyevinn/mp4ff (⭐622)](https://github.com/Eyevinn/mp4ff) — MP4/ISOBMFF tools and library ☆`625`
*   [asticode/go-astits (⭐614)](https://github.com/asticode/go-astits) — Demux and mux MPEG Transport Streams (.ts) natively in GO ☆`616`
*   [adrg/libvlc-go (⭐505)](https://github.com/adrg/libvlc-go) — Go bindings for libVLC ☆`506`
*   [Eyevinn/hls-m3u8 (⭐54)](https://github.com/Eyevinn/hls-m3u8) — HLS m3u8 library in Go ☆`56`
*   [jonoton/scout (⭐26)](https://github.com/jonoton/scout) — Video surveillance with motion detection ☆`26`
*   [unki2aut/go-mpd (⭐32)](https://github.com/unki2aut/go-mpd) — MPEG-DASH manifest library ☆`32`

## Auth

### Authentication

*   [golang-jwt/jwt (⭐8.9k)](https://github.com/golang-jwt/jwt) — Go implementation of JSON Web Tokens (JWT). ☆`8,967`
*   [markbates/goth (⭐6.5k)](https://github.com/markbates/goth) — Multi-provider authentication ☆`6,489`
*   [golang/oauth2 (⭐5.8k)](https://github.com/golang/oauth2) — Go OAuth2 ☆`5,826`
*   [aarondl/authboss (⭐4.2k)](https://github.com/aarondl/authboss) — The boss of http auth. ☆`4,168`
*   [alexedwards/scs (⭐2.5k)](https://github.com/alexedwards/scs) — HTTP Session Management for Go ☆`2,535`
*   [lestrrat-go/jwx (⭐2.3k)](https://github.com/lestrrat-go/jwx) — Complete JWx implementation ☆`2,340`
*   [openshift/osin (⭐1.9k)](https://github.com/openshift/osin) — Golang OAuth2 server library ☆`1,935`
*   [dghubble/gologin (⭐1.9k)](https://github.com/dghubble/gologin) — Go login handlers for authentication providers (OAuth1, OAuth2) ☆`1,947`
*   [zitadel/oidc (⭐1.8k)](https://github.com/zitadel/oidc) — OpenID Connect client and server ☆`1,783`
*   [cristalhq/jwt (⭐688)](https://github.com/cristalhq/jwt) — Safe, simple and fast JSON Web Tokens for Go ☆`688`
*   [shaj13/go-guardian (⭐610)](https://github.com/shaj13/go-guardian) — Authentication library for Go ☆`610`
*   [go-jose/go-jose (⭐487)](https://github.com/go-jose/go-jose) — An implementation of JOSE standards (JWE, JWS, JWT) in Go ☆`490`
*   [abraithwaite/jeff (⭐271)](https://github.com/abraithwaite/jeff) — Jeff provides the simplest way to manage web sessions in Go. ☆`271`
*   [Kwynto/gosession (⭐258)](https://github.com/Kwynto/gosession) — Quick session for net/http ☆`259`
*   [leodip/goiabada (⭐185)](https://github.com/leodip/goiabada) — Goiabada is an OAuth2 / OpenID Connect server written in Go. ☆`187`
*   [brianvoe/sjwt (⭐122)](https://github.com/brianvoe/sjwt) — Simple JWT Golang ☆`122`
*   [jellydator/sessionup (⭐131)](https://github.com/jellydator/sessionup) — Straightforward HTTP session management ☆`131`
*   [essentialkaos/branca (⭐96)](https://github.com/essentialkaos/branca) — Encrypted API tokens ☆`96`
*   [icza/session (⭐118)](https://github.com/icza/session) — Session management for web servers ☆`118`
*   [mengzhuo/cookiestxt (⭐22)](https://github.com/mengzhuo/cookiestxt) — cookiestxt implement parser of cookies txt format ☆`22`

### Authorization

*   [apache/casbin (⭐20k)](https://github.com/apache/casbin) — Authorization library for Go ☆`19,950`
*   [ory/keto (⭐5.3k)](https://github.com/ory/keto) — Customizable permission server ☆`5,289`
*   [openfga/openfga (⭐4.9k)](https://github.com/openfga/openfga) — Fine-grained authorization server ☆`4,925`
*   [cerbos/cerbos (⭐4.3k)](https://github.com/cerbos/cerbos) — Open core authorization layer ☆`4,290`

## Bots & Chat

### Bot Frameworks

*   [tucnak/telebot (⭐4.6k)](https://github.com/tucnak/telebot) — Telebot is a Telegram bot framework in Go. ☆`4,578`
*   [go-telegram/bot (⭐1.6k)](https://github.com/go-telegram/bot) — Telegram Bot API Go framework ☆`1,645`
*   [mymmrac/telego (⭐965)](https://github.com/mymmrac/telego) — Telegram Bot API library for Go ☆`972`
*   [diamondburned/arikawa (⭐579)](https://github.com/diamondburned/arikawa) — A Golang library and framework for the Discord API. ☆`583`
*   [NicoNex/echotron (⭐424)](https://github.com/NicoNex/echotron) — An elegant and concurrent library for the Telegram bot API in Go. ☆`428`
*   [gempir/go-twitch-irc (⭐394)](https://github.com/gempir/go-twitch-irc) — go irc client for twitch.tv ☆`394`
*   [innogames/slack-bot (⭐206)](https://github.com/innogames/slack-bot) — Slack bot for Jenkins, Jira, PRs ☆`206`
*   [mr-linch/go-tg (⭐129)](https://github.com/mr-linch/go-tg) — Telegram Bot API client ☆`130`
*   [slack-io/slacker (⭐59)](https://github.com/slack-io/slacker) — Slack Bot Framework ☆`59`
*   [onrik/micha (⭐32)](https://github.com/onrik/micha) — Client lib for Telegram bot api ☆`33`

### Chat APIs

*   [bwmarrin/discordgo (⭐5.8k)](https://github.com/bwmarrin/discordgo) — (Golang) Go bindings for Discord ☆`5,852`
*   [slack-go/slack (⭐4.9k)](https://github.com/slack-go/slack) — Slack API in Go ☆`4,922`
*   [huandu/facebook (⭐1.4k)](https://github.com/huandu/facebook) — A Facebook Graph API SDK For Go. ☆`1,450`
*   [chyroc/lark (⭐465)](https://github.com/chyroc/lark) — Lark/Feishu Open API SDK ☆`468`
*   [go-lark/lark (⭐240)](https://github.com/go-lark/lark) — Feishu/Lark SDK for Go ☆`242`
*   [switchupcb/disgo (⭐110)](https://github.com/switchupcb/disgo) — Next-gen Discord API library ☆`110`

## CLI & Terminal

### Advanced Console UIs

*   [charmbracelet/bubbletea (⭐41k)](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`40,936`
*   [antonmedv/fx (⭐20k)](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,356`
*   [gizak/termui (⭐14k)](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,522`
*   [charmbracelet/lipgloss (⭐11k)](https://github.com/charmbracelet/lipgloss) — Style definitions for nice terminal layouts ☆`10,904`
*   [jroimartin/gocui (⭐11k)](https://github.com/jroimartin/gocui) — Minimalist Go package aimed at creating Console User Interfaces. ☆`10,536`
*   [charmbracelet/bubbles (⭐8k)](https://github.com/charmbracelet/bubbles) — TUI components for Bubble Tea ☆`8,059`
*   [c-bata/go-prompt (⭐5.5k)](https://github.com/c-bata/go-prompt) — Interactive prompts for Go ☆`5,470`
*   [pterm/pterm (⭐5.4k)](https://github.com/pterm/pterm) — Modern terminal output library ☆`5,393`
*   [schollz/progressbar (⭐4.6k)](https://github.com/schollz/progressbar) — Thread-safe progress bar ☆`4,654`
*   [guptarohit/asciigraph (⭐3k)](https://github.com/guptarohit/asciigraph) — ASCII line graphs in terminal ☆`2,987`
*   [mum4k/termdash (⭐3k)](https://github.com/mum4k/termdash) — Terminal-based dashboard ☆`2,982`
*   [briandowns/spinner (⭐2.5k)](https://github.com/briandowns/spinner) — Terminal spinner indicators ☆`2,519`
*   [vbauerster/mpb (⭐2.5k)](https://github.com/vbauerster/mpb) — Multi progress bar ☆`2,487`
*   [muesli/termenv (⭐2k)](https://github.com/muesli/termenv) — Terminal color support ☆`1,976`
*   [gookit/color (⭐1.6k)](https://github.com/gookit/color) — Terminal color rendering ☆`1,578`
*   [logrusorgru/aurora (⭐1.5k)](https://github.com/logrusorgru/aurora) — ANSI colors for Printf ☆`1,480`
*   [mattn/go-isatty (⭐892)](https://github.com/mattn/go-isatty) — Check if terminal is TTY ☆`895`
*   [mattn/go-colorable (⭐805)](https://github.com/mattn/go-colorable) — Colorable writer for Windows ☆`805`
*   [box-cli-maker/box-cli-maker (⭐618)](https://github.com/box-cli-maker/box-cli-maker) — Render highly customizable boxes in the terminal ☆`620`
*   [Evertras/bubble-table (⭐561)](https://github.com/Evertras/bubble-table) — Table component for Bubble Tea ☆`564`
*   [DMcP89/tinycare-tui (⭐17)](https://github.com/DMcP89/tinycare-tui) — TUI application written in GO inspired by tiny-care-terminal ☆`19`

### Standard CLI

*   [spf13/cobra (⭐43k)](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`43,518`
*   [urfave/cli (⭐24k)](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`23,948`
*   [elves/elvish (⭐6.2k)](https://github.com/elves/elvish) — Scripting shell for Go ☆`6,266`
*   [alecthomas/kingpin (⭐3.6k)](https://github.com/alecthomas/kingpin) — Command-line parser ☆`3,559`
*   [dnote/dnote (⭐3k)](https://github.com/dnote/dnote) — Command-line notebook ☆`3,018`
*   [spf13/pflag (⭐2.7k)](https://github.com/spf13/pflag) — POSIX/GNU-style flags ☆`2,718`
*   [jessevdk/go-flags (⭐2.7k)](https://github.com/jessevdk/go-flags) — Command-line option parser ☆`2,695`
*   [alexflint/go-arg (⭐2.2k)](https://github.com/alexflint/go-arg) — Struct-based argument parsing ☆`2,242`
*   [carapace-sh/carapace-bin (⭐1.7k)](https://github.com/carapace-sh/carapace-bin) — Multi-shell completion binary ☆`1,754`
*   [nanovms/ops (⭐1.5k)](https://github.com/nanovms/ops) — Build and run unikernels ☆`1,477`
*   [carapace-sh/carapace (⭐1.2k)](https://github.com/carapace-sh/carapace) — Multi-shell completion library ☆`1,216`
*   [posener/complete (⭐952)](https://github.com/posener/complete) — Bash completion in Go ☆`952`
*   [ddddddO/gtree (⭐328)](https://github.com/ddddddO/gtree) — Generate ASCII tree from Markdown ☆`330`
*   [leaanthony/clir (⭐197)](https://github.com/leaanthony/clir) — Simple CLI library ☆`198`
*   [urfave/sflags (⭐167)](https://github.com/urfave/sflags) — Generate flags from structs ☆`167`
*   [hedzr/cmdr (⭐141)](https://github.com/hedzr/cmdr) — POSIX-compliant CLI parser ☆`141`
*   [reeflective/readline (⭐135)](https://github.com/reeflective/readline) — Shell library with inputrc ☆`136`
*   [cristalhq/acmd (⭐137)](https://github.com/cristalhq/acmd) — Simple CLI package ☆`138`
*   [reeflective/console (⭐105)](https://github.com/reeflective/console) — Console library for Cobra ☆`107`
*   [codingconcepts/env (⭐126)](https://github.com/codingconcepts/env) — Tag-based environment configuration for structs ☆`126`
*   [jxskiss/mcli (⭐44)](https://github.com/jxskiss/mcli) — Minimal but powerful CLI ☆`45`
*   [dixonwille/wlog (⭐67)](https://github.com/dixonwille/wlog) — Cross-platform logging ☆`67`
*   [DavidGamba/go-getoptions (⭐61)](https://github.com/DavidGamba/go-getoptions) — Command line option parser with completion ☆`61`
*   [nyaosorg/go-readline-ny (⭐33)](https://github.com/nyaosorg/go-readline-ny) — Readline for Go ☆`34`
*   [carapace-sh/carapace-spec (⭐29)](https://github.com/carapace-sh/carapace-spec) — Multi-shell completion library ☆`29`
*   [sgreben/flagvar (⭐48)](https://github.com/sgreben/flagvar) — CLI argument types for flag ☆`48`
*   [hashicorp/cli (⭐36)](https://github.com/hashicorp/cli) — CLI library for Go ☆`36`

## Concurrency

### Actor Model

*   [asynkron/protoactor-go (⭐5.4k)](https://github.com/asynkron/protoactor-go) — Ultra fast distributed actors for Go ☆`5,434`
*   [ergo-services/ergo (⭐4.5k)](https://github.com/ergo-services/ergo) — Actor framework with network transparency ☆`4,475`
*   [anthdm/hollywood (⭐2.2k)](https://github.com/anthdm/hollywood) — Blazingly fast and light-weight Actor engine written in Golang ☆`2,203`
*   [Tochemey/goakt (⭐326)](https://github.com/Tochemey/goakt) — Distributed actor framework ☆`332`

### Goroutines

*   [panjf2000/ants (⭐14k)](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,370`
*   [benmanns/goworker (⭐2.8k)](https://github.com/benmanns/goworker) — Resque-compatible background worker ☆`2,852`
*   [alitto/pond (⭐2.1k)](https://github.com/alitto/pond) — High-performance worker pool ☆`2,129`
*   [destel/rill (⭐1.8k)](https://github.com/destel/rill) — Channel-based concurrency toolkit ☆`1,804`
*   [xxjwxc/gowp (⭐522)](https://github.com/xxjwxc/gowp) — Goroutine worker pool ☆`520`
*   [earthboundkid/flowmatic (⭐397)](https://github.com/earthboundkid/flowmatic) — Structured concurrency ☆`398`
*   [reugn/async (⭐299)](https://github.com/reugn/async) — Async computation package ☆`301`
*   [vladopajic/go-actor (⭐284)](https://github.com/vladopajic/go-actor) — Actor model library ☆`283`
*   [timandy/routine (⭐287)](https://github.com/timandy/routine) — ThreadLocal for Go ☆`288`
*   [mborders/artifex (⭐214)](https://github.com/mborders/artifex) — In-memory job queue ☆`214`

### Stream Processing

*   [reugn/go-streams (⭐2.2k)](https://github.com/reugn/go-streams) — Stream processing library ☆`2,163`
*   [Breeze0806/go-etl (⭐184)](https://github.com/Breeze0806/go-etl) — ETL toolset for Go ☆`184`
*   [fulminate-io/machine (⭐166)](https://github.com/fulminate-io/machine) — Machine is a workflow/pipeline library for processing data ☆`166`
*   [mariomac/gostream (⭐170)](https://github.com/mariomac/gostream) — Java Streams port for Go ☆`170`
*   [rulego/streamsql (⭐54)](https://github.com/rulego/streamsql) — SQL-based stream processing for IoT ☆`55`

## Configuration

*   [spf13/viper (⭐30k)](https://github.com/spf13/viper) — Go configuration with fangs ☆`30,174`
*   [caarlos0/env (⭐6k)](https://github.com/caarlos0/env) — Parse environment variables to structs ☆`6,060`
*   [knadh/koanf (⭐3.9k)](https://github.com/knadh/koanf) — Lightweight config management ☆`3,938`
*   [alecthomas/kong (⭐3k)](https://github.com/alecthomas/kong) — Command-line parser for Go ☆`3,009`
*   [ilyakaznacheev/cleanenv (⭐2.1k)](https://github.com/ilyakaznacheev/cleanenv) — Minimalistic environment config reader ☆`2,079`
*   [adrg/xdg (⭐964)](https://github.com/adrg/xdg) — XDG Base Directory implementation ☆`970`
*   [cristalhq/aconfig (⭐624)](https://github.com/cristalhq/aconfig) — Simple config loader ☆`626`
*   [gookit/config (⭐581)](https://github.com/gookit/config) — Config management with formats ☆`581`
*   [nil-go/konf (⭐372)](https://github.com/nil-go/konf) — Simplest config loader for Go ☆`373`
*   [kkyr/fig (⭐384)](https://github.com/kkyr/fig) — Minimalist config library ☆`384`
*   [hjson/hjson-go (⭐346)](https://github.com/hjson/hjson-go) — Hjson for Go ☆`346`
*   [vrischmann/envconfig (⭐250)](https://github.com/vrischmann/envconfig) — Env config library ☆`250`
*   [chaindead/zerocfg (⭐199)](https://github.com/chaindead/zerocfg) — Zero-effort config management ☆`200`
*   [beatlabs/harvester (⭐134)](https://github.com/beatlabs/harvester) — Watch and notify config changes ☆`133`
*   [BoRuDar/configuration (⭐108)](https://github.com/BoRuDar/configuration) — Set struct fields from env, flags, files ☆`108`
*   [gurkankaymak/hocon (⭐89)](https://github.com/gurkankaymak/hocon) — HOCON config library for Go ☆`89`
*   [PaddleHQ/go-aws-ssm (⭐62)](https://github.com/PaddleHQ/go-aws-ssm) — AWS System Manager interface ☆`62`
*   [go-simpler/env (⭐80)](https://github.com/go-simpler/env) — Load env vars to struct ☆`80`
*   [omeid/uconfig (⭐72)](https://github.com/omeid/uconfig) — Lightweight config management ☆`73`
*   [sakirsensoy/genv (⭐43)](https://github.com/sakirsensoy/genv) — Easy env variable handling ☆`43`
*   [num30/config (⭐60)](https://github.com/num30/config) — Declarative configuration ☆`60`
*   [wkhere/bcl (⭐29)](https://github.com/wkhere/bcl) — Basic Configuration Language ☆`29`
*   [dsbasko/go-cfg (⭐47)](https://github.com/dsbasko/go-cfg) — Unified config reading ☆`48`
*   [atelpis/enflag (⭐38)](https://github.com/atelpis/enflag) — Unify env and flag parsing ☆`38`
*   [greencoda/confiq (⭐39)](https://github.com/greencoda/confiq) — Config struct decoder ☆`39`
*   [romshark/yamagiconf (⭐18)](https://github.com/romshark/yamagiconf) — YAML config framework ☆`18`
*   [nasermirzaei89/env (⭐22)](https://github.com/nasermirzaei89/env) — Zero-dep env package ☆`22`
*   [deatil/go-array (⭐22)](https://github.com/deatil/go-array) — Read/set map, slice, JSON data ☆`22`

## Data Formats

### JSON

*   [tidwall/gjson (⭐15k)](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,470`
*   [bytedance/sonic (⭐9.3k)](https://github.com/bytedance/sonic) — A blazingly fast JSON serializing & deserializing library ☆`9,294`
*   [Jeffail/gabs (⭐3.5k)](https://github.com/Jeffail/gabs) — Dynamic JSON parsing ☆`3,530`
*   [valyala/fastjson (⭐2.4k)](https://github.com/valyala/fastjson) — Fast JSON parser for Go ☆`2,441`
*   [ohler55/ojg (⭐940)](https://github.com/ohler55/ojg) — Optimized JSON for Go ☆`942`
*   [wI2L/jsondiff (⭐624)](https://github.com/wI2L/jsondiff) — JSON Patch diff computation ☆`625`
*   [spyzhov/ajson (⭐291)](https://github.com/spyzhov/ajson) — Abstract JSON with JSONPath ☆`291`
*   [Andrew-M-C/go.jsonvalue (⭐202)](https://github.com/Andrew-M-C/go.jsonvalue) — Unstructured JSON solution ☆`202`
*   [iOliverNguyen/ujson (⭐85)](https://github.com/iOliverNguyen/ujson) — Minimal JSON parser ☆`85`
*   [neilotoole/jsoncolor (⭐51)](https://github.com/neilotoole/jsoncolor) — Colorized JSON output ☆`51`

### Serialization

*   [golang/protobuf (⭐10k)](https://github.com/golang/protobuf) — Protocol buffers for Go ☆`10,059`
*   [ugorji/go (⭐1.9k)](https://github.com/ugorji/go) — Codec for msgpack, cbor, json ☆`1,942`
*   [linkedin/goavro (⭐1.1k)](https://github.com/linkedin/goavro) — Goavro is a library that encodes and decodes Avro data. ☆`1,057`
*   [fxamacker/cbor (⭐1k)](https://github.com/fxamacker/cbor) — CBOR codec with extensions ☆`1,030`
*   [jszwec/csvutil (⭐1k)](https://github.com/jszwec/csvutil) — CSV to struct mapping ☆`1,031`
*   [ghostiam/binstruct (⭐112)](https://github.com/ghostiam/binstruct) — Binary to struct decoder ☆`112`
*   [csweichel/bel (⭐46)](https://github.com/csweichel/bel) — Generate TypeScript from Go ☆`46`
*   [o1egl/fwencoder (⭐27)](https://github.com/o1egl/fwencoder) — Fixed width file parser ☆`27`
*   [tiendc/go-csvlib (⭐18)](https://github.com/tiendc/go-csvlib) — High-level CSV library ☆`18`

### XML

*   [miku/zek (⭐825)](https://github.com/miku/zek) — Generate Go struct from XML ☆`827`
*   [antchfx/xpath (⭐735)](https://github.com/antchfx/xpath) — XPath for Go ☆`735`
*   [antchfx/xmlquery (⭐486)](https://github.com/antchfx/xmlquery) — XPath XML query ☆`485`

## Data Structures

### Bit-packing and Compression

*   [RoaringBitmap/roaring (⭐2.8k)](https://github.com/RoaringBitmap/roaring) — Compressed bitmaps for Go ☆`2,853`
*   [iancmcc/bingo (⭐51)](https://github.com/iancmcc/bingo) — Zero-allocation binary encoding ☆`51`
*   [amallia/go-ef (⭐41)](https://github.com/amallia/go-ef) — A Go implementation of the Elias-Fano encoding ☆`41`

### Bloom and Cuckoo Filters

*   [bits-and-blooms/bloom (⭐2.8k)](https://github.com/bits-and-blooms/bloom) — Bloom filter implementation ☆`2,762`
*   [tylertreat/BoomFilters (⭐1.6k)](https://github.com/tylertreat/BoomFilters) — Probabilistic data structures for streams ☆`1,646`
*   [seiflotfy/cuckoofilter (⭐1.2k)](https://github.com/seiflotfy/cuckoofilter) — Cuckoo Filter: Practically Better Than Bloom ☆`1,222`
*   [OldPanda/bloomfilter (⭐20)](https://github.com/OldPanda/bloomfilter) — Bloom filter compatible with pybloom ☆`20`

### Maps

*   [mhmtszr/concurrent-swiss-map (⭐262)](https://github.com/mhmtszr/concurrent-swiss-map) — Thread-safe concurrent hash map ☆`262`
*   [goradd/maps (⭐52)](https://github.com/goradd/maps) — Generic map library for Go ☆`52`
*   [srfrog/dict (⭐46)](https://github.com/srfrog/dict) — Python-like dictionaries for Go ☆`46`

### Miscellaneous

*   [Workiva/go-datastructures (⭐7.9k)](https://github.com/Workiva/go-datastructures) — Performant, threadsafe data structures ☆`7,911`
*   [deckarep/golang-set (⭐4.7k)](https://github.com/deckarep/golang-set) — Generic set type for Go ☆`4,655`
*   [bits-and-blooms/bitset (⭐1.5k)](https://github.com/bits-and-blooms/bitset) — Go package implementing bitsets ☆`1,489`
*   [liyue201/gostl (⭐1.1k)](https://github.com/liyue201/gostl) — Data structures modeled on C++ STL ☆`1,138`
*   [axiomhq/hyperloglog (⭐1k)](https://github.com/axiomhq/hyperloglog) — HyperLogLog with optimizations ☆`1,032`
*   [kelindar/bitmap (⭐370)](https://github.com/kelindar/bitmap) — Simple dense bitmap index in Go with binary operators ☆`371`
*   [barweiss/go-tuple (⭐96)](https://github.com/barweiss/go-tuple) — Go 1.18+ generic tuple ☆`97`
*   [seiflotfy/count-min-log (⭐69)](https://github.com/seiflotfy/count-min-log) — Go implementation of Count-Min-Log ☆`69`
*   [s0rg/quadtree (⭐41)](https://github.com/s0rg/quadtree) — Generic, zero-alloc, 100%-test covered Quadtree for golang ☆`41`
*   [StudioSol/set (⭐29)](https://github.com/StudioSol/set) — Simple set data structure ☆`29`
*   [nazar256/parapipe (⭐37)](https://github.com/nazar256/parapipe) — Paralleling pipeline ☆`37`
*   [bobg/merkle (⭐21)](https://github.com/bobg/merkle) — Merkle hash trees ☆`21`

### Queues

*   [gammazero/deque (⭐765)](https://github.com/gammazero/deque) — Fast ring-buffer deque (double-ended queue) ☆`769`
*   [adrianbrad/queue (⭐331)](https://github.com/adrianbrad/queue) — Multiple queue implementations ☆`332`
*   [embano1/memlog (⭐136)](https://github.com/embano1/memlog) — A Kafka log inspired in-memory and append-only data structure ☆`138`
*   [mikestefanello/backlite (⭐138)](https://github.com/mikestefanello/backlite) — SQLite-backed task queues ☆`141`

## Databases

### Caches

*   [golang/groupcache (⭐13k)](https://github.com/golang/groupcache) — Distributed cache library ☆`13,340`
*   [dgraph-io/ristretto (⭐6.8k)](https://github.com/dgraph-io/ristretto) — A high performance memory-bound Go cache ☆`6,830`
*   [eko/gocache (⭐2.8k)](https://github.com/eko/gocache) — Multi-store caching library ☆`2,845`
*   [maypok86/otter (⭐2.5k)](https://github.com/maypok86/otter) — A high performance caching library for Go ☆`2,558`
*   [VictoriaMetrics/fastcache (⭐2.3k)](https://github.com/VictoriaMetrics/fastcache) — Fast in-memory cache for Go ☆`2,342`
*   [jellydator/ttlcache (⭐1.2k)](https://github.com/jellydator/ttlcache) — An in-memory cache with item expiration and generics ☆`1,234`
*   [viccon/sturdyc (⭐1.2k)](https://github.com/viccon/sturdyc) — Caching with advanced concurrency ☆`1,247`
*   [EchoVault/SugarDB (⭐529)](https://github.com/EchoVault/SugarDB) — Embeddable and distributed in-memory alternative to Redis. ☆`530`
*   [faabiosr/cachego (⭐372)](https://github.com/faabiosr/cachego) — Golang Cache component - Multiple drivers ☆`371`
*   [Yiling-J/theine-go (⭐362)](https://github.com/Yiling-J/theine-go) — high performance in-memory cache ☆`365`
*   [elastic/go-freelru (⭐262)](https://github.com/elastic/go-freelru) — GC-less, fast and generic LRU cache for Go ☆`263`
*   [samber/hot (⭐244)](https://github.com/samber/hot) — In-memory caching library for read-intensive Go applications ☆`247`
*   [naughtygopher/pocache (⭐231)](https://github.com/naughtygopher/pocache) — Preemptive optimistic caching ☆`232`
*   [OrlovEvgeny/go-mcache (⭐103)](https://github.com/OrlovEvgeny/go-mcache) — Sharded in-memory KV cache ☆`103`
*   [erni27/imcache (⭐123)](https://github.com/erni27/imcache) — A zero-dependency generic in-memory cache Go library ☆`123`
*   [zekroTJA/timedmap (⭐74)](https://github.com/zekroTJA/timedmap) — A thread safe map which has expiring key-value pairs. ☆`74`
*   [codingsince1985/couchcache (⭐66)](https://github.com/codingsince1985/couchcache) — A RESTful caching micro-service in Go backed by Couchbase ☆`66`
*   [mdaliyan/icache (⭐23)](https://github.com/mdaliyan/icache) — High-performance generic cache ☆`23`

### Database Schema Migration

*   [golang-migrate/migrate (⭐18k)](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,272`
*   [bytebase/bytebase (⭐14k)](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`13,850`
*   [pressly/goose (⭐10k)](https://github.com/pressly/goose) — A database migration tool. Supports SQL migrations and Go functions. ☆`10,364`
*   [ariga/atlas (⭐8.2k)](https://github.com/ariga/atlas) — Declarative schema migrations with schema-as-code workflows ☆`8,204`
*   [amacneil/dbmate (⭐6.8k)](https://github.com/amacneil/dbmate) — A lightweight, framework-agnostic database migration tool. ☆`6,789`
*   [rubenv/sql-migrate (⭐3.4k)](https://github.com/rubenv/sql-migrate) — SQL schema migration tool for Go. ☆`3,407`
*   [skeema/skeema (⭐1.4k)](https://github.com/skeema/skeema) — Declarative pure-SQL schema management for MySQL and MariaDB ☆`1,361`
*   [go-gormigrate/gormigrate (⭐1.2k)](https://github.com/go-gormigrate/gormigrate) — Minimalistic database migration helper for Gorm ORM ☆`1,152`
*   [sunary/sqlize (⭐124)](https://github.com/sunary/sqlize) — SQL parsing and migration toolkit ☆`124`
*   [robinjoseph08/go-pg-migrations (⭐86)](https://github.com/robinjoseph08/go-pg-migrations) — A Go package to help write migrations with go-pg/pg. ☆`86`
*   [adlio/schema (⭐42)](https://github.com/adlio/schema) — Embedded schema migration package for Go ☆`42`
*   [khezen/avro (⭐48)](https://github.com/khezen/avro) — Apache AVRO for go ☆`48`
*   [muir/libschema (⭐17)](https://github.com/muir/libschema) — database schema migrations on a per-library basis \[Go] ☆`17`

### Database Tools

*   [vitessio/vitess (⭐21k)](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`20,862`
*   [sosedoff/pgweb (⭐9.3k)](https://github.com/sosedoff/pgweb) — Cross-platform client for PostgreSQL databases ☆`9,276`
*   [go-mysql-org/go-mysql (⭐4.9k)](https://github.com/go-mysql-org/go-mysql) — a powerful mysql toolset with Go ☆`4,922`
*   [prest/prest (⭐4.5k)](https://github.com/prest/prest) — PostgreSQL REST API server ☆`4,534`
*   [ContentSquare/chproxy (⭐1.4k)](https://github.com/ContentSquare/chproxy) — Open-Source ClickHouse http proxy and load balancer ☆`1,440`
*   [cybertec-postgresql/pg\_timetable (⭐1.3k)](https://github.com/cybertec-postgresql/pg_timetable) — Advanced PostgreSQL scheduler ☆`1,337`
*   [liweiyi88/onedump (⭐940)](https://github.com/liweiyi88/onedump) — Effortless database administration tool ☆`952`
*   [HDT3213/rdb (⭐600)](https://github.com/HDT3213/rdb) — Redis RDB parser for Go ☆`601`
*   [nikepan/clickhouse-bulk (⭐505)](https://github.com/nikepan/clickhouse-bulk) — Batch inserts for ClickHouse ☆`507`
*   [wesql/wescale (⭐314)](https://github.com/wesql/wescale) — MySQL proxy with read/write split ☆`314`
*   [gatewayd-io/gatewayd (⭐278)](https://github.com/gatewayd-io/gatewayd) — database gateway for building data-driven applications ☆`279`
*   [sj14/dbbench (⭐115)](https://github.com/sj14/dbbench) — Database benchmarking tool ☆`115`
*   [bartventer/gorm-multitenancy (⭐78)](https://github.com/bartventer/gorm-multitenancy) — Multi-tenancy for GORM ☆`79`
*   [kazhuravlev/database-gateway (⭐30)](https://github.com/kazhuravlev/database-gateway) — Safe access to production databases ☆`33`
*   [codingconcepts/dg (⭐43)](https://github.com/codingconcepts/dg) — Generate CSV from data models ☆`43`

### Databases Implemented in Go

*   [prometheus/prometheus (⭐63k)](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`63,287`
*   [milvus-io/milvus (⭐43k)](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`43,458`
*   [pingcap/tidb (⭐40k)](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`39,924`
*   [cockroachdb/cockroach (⭐32k)](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`31,995`
*   [influxdata/influxdb (⭐31k)](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,376`
*   [dgraph-io/dgraph (⭐22k)](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,647`
*   [dolthub/dolt (⭐21k)](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`21,673`
*   [rqlite/rqlite (⭐17k)](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,372`
*   [VictoriaMetrics/VictoriaMetrics (⭐17k)](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`16,596`
*   [dgraph-io/badger (⭐16k)](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,528`
*   [dicedb/dicedb (⭐11k)](https://github.com/dicedb/dicedb) — Low-latency key/value engine on Valkey with storage tiers ☆`10,711`
*   [etcd-io/bbolt (⭐9.4k)](https://github.com/etcd-io/bbolt) — An embedded key/value database for Go. ☆`9,421`
*   [codenotary/immudb (⭐8.9k)](https://github.com/codenotary/immudb) — Immutable database with SQL ☆`8,948`
*   [cockroachdb/pebble (⭐5.8k)](https://github.com/cockroachdb/pebble) — RocksDB/LevelDB inspired key-value database in Go ☆`5,816`
*   [rosedblabs/rosedb (⭐4.9k)](https://github.com/rosedblabs/rosedb) — Fast key/value storage engine ☆`4,878`
*   [tidwall/buntdb (⭐4.8k)](https://github.com/tidwall/buntdb) — Embeddable in-memory key/value DB ☆`4,842`
*   [nalgeon/redka (⭐4.5k)](https://github.com/nalgeon/redka) — Redis re-implemented with SQL ☆`4,537`
*   [HDT3213/godis (⭐3.8k)](https://github.com/HDT3213/godis) — A Golang implemented Redis Server and Cluster ☆`3,829`
*   [nutsdb/nutsdb (⭐3.6k)](https://github.com/nutsdb/nutsdb) — Simple embeddable key/value store ☆`3,561`
*   [lindb/lindb (⭐3.1k)](https://github.com/lindb/lindb) — Scalable time-series database ☆`3,057`
*   [lotusdblabs/lotusdb (⭐2.3k)](https://github.com/lotusdblabs/lotusdb) — Key-value database with LSM and B+ tree ☆`2,254`
*   [kelindar/column (⭐1.5k)](https://github.com/kelindar/column) — Columnar in-memory store ☆`1,509`
*   [akrylysov/pogreb (⭐1.3k)](https://github.com/akrylysov/pogreb) — Embedded key-value store for read-heavy workloads written in Go ☆`1,348`
*   [objectbox/objectbox-go (⭐1.3k)](https://github.com/objectbox/objectbox-go) — Embedded database for Go ☆`1,258`
*   [couchbase/moss (⭐1k)](https://github.com/couchbase/moss) — Simple, fast key-val storage ☆`1,017`
*   [amit-davidson/LibraDB (⭐198)](https://github.com/amit-davidson/LibraDB) — Simple persistent key/value store ☆`199`
*   [claygod/transaction (⭐139)](https://github.com/claygod/transaction) — Embedded database for accounts transactions. ☆`139`
*   [xgzlucario/rotom (⭐41)](https://github.com/xgzlucario/rotom) — Tiny Redis server in Go ☆`40`

### Distributed Storage

*   [seaweedfs/seaweedfs (⭐31k)](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`31,140`
*   [juicedata/juicefs (⭐13k)](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`13,356`

### Interfaces to Multiple Backends

*   [philippgille/gokv (⭐822)](https://github.com/philippgille/gokv) — Key-value store abstraction ☆`824`
*   [avito-tech/go-transaction-manager (⭐386)](https://github.com/avito-tech/go-transaction-manager) — Transaction manager for Go ☆`389`
*   [viant/dsc (⭐35)](https://github.com/viant/dsc) — Datastore Connectivity in go ☆`35`
*   [fogfish/dynamo (⭐22)](https://github.com/fogfish/dynamo) — Generic Golang Key/Value trait for AWS storage services ☆`22`

### NoSQL Database Drivers

*   [redis/go-redis (⭐22k)](https://github.com/redis/go-redis) — Redis Go client ☆`22,000`
*   [gomodule/redigo (⭐9.9k)](https://github.com/gomodule/redigo) — Go client for Redis ☆`9,876`
*   [mongodb/mongo-go-driver (⭐8.5k)](https://github.com/mongodb/mongo-go-driver) — The Official Golang driver for MongoDB ☆`8,515`
*   [bradfitz/gomemcache (⭐1.9k)](https://github.com/bradfitz/gomemcache) — Go Memcached client library #golang ☆`1,868`
*   [qiniu/qmgo (⭐1.3k)](https://github.com/qiniu/qmgo) — Go driver for MongoDB ☆`1,350`
*   [Kamva/mgm (⭐764)](https://github.com/Kamva/mgm) — MongoDB ODM for Go based on official driver ☆`763`
*   [aerospike/aerospike-client-go (⭐458)](https://github.com/aerospike/aerospike-client-go) — Aerospike Client Go ☆`458`
*   [couchbase/gocb (⭐376)](https://github.com/couchbase/gocb) — The Couchbase Go SDK ☆`376`
*   [go-kivik/kivik (⭐340)](https://github.com/go-kivik/kivik) — CouchDB client interface ☆`340`
*   [couchbase/go-couchbase (⭐324)](https://github.com/couchbase/go-couchbase) — Couchbase client in Go ☆`324`
*   [chenmingyong0423/go-mongox (⭐217)](https://github.com/chenmingyong0423/go-mongox) — MongoDB driver wrapper with generics ☆`217`
*   [aliexpressru/gomemcached (⭐22)](https://github.com/aliexpressru/gomemcached) — Binary Memcached client with sharding ☆`22`
*   [btnguyen2k/gocosmos (⭐22)](https://github.com/btnguyen2k/gocosmos) — Go database/sql driver for Azure Cosmos DB SQL API ☆`22`

### ORM

*   [go-gorm/gorm (⭐40k)](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,647`
*   [ent/ent (⭐17k)](https://github.com/ent/ent) — An entity framework for Go ☆`16,989`
*   [aarondl/sqlboiler (⭐7k)](https://github.com/aarondl/sqlboiler) — Generate a Go ORM tailored to your database schema. ☆`6,977`
*   [uptrace/bun (⭐4.7k)](https://github.com/uptrace/bun) — SQL-first Golang ORM ☆`4,721`
*   [upper/db (⭐3.6k)](https://github.com/upper/db) — Data access layer for databases ☆`3,648`
*   [huandu/go-sqlbuilder (⭐1.7k)](https://github.com/huandu/go-sqlbuilder) — SQL builder with zero-config ORM ☆`1,680`
*   [stephenafamo/bob (⭐1.7k)](https://github.com/stephenafamo/bob) — SQL builder with ORM generator ☆`1,684`
*   [go-rel/rel (⭐781)](https://github.com/go-rel/rel) — Modern ORM for Golang ☆`781`
*   [FrancoLiberali/cql (⭐17)](https://github.com/FrancoLiberali/cql) — CQL: Compiled Query Language ☆`17`
*   [hashicorp/go-dbw (⭐16)](https://github.com/hashicorp/go-dbw) — A simple package that encapsulates database operations. ☆`16`

### Query Language

*   [99designs/gqlgen (⭐11k)](https://github.com/99designs/gqlgen) — go generate based graphql server library ☆`10,696`
*   [TomWright/dasel (⭐7.9k)](https://github.com/TomWright/dasel) — Query and modify data formats ☆`7,887`
*   [graph-gophers/graphql-go (⭐4.7k)](https://github.com/graph-gophers/graphql-go) — GraphQL server with a focus on ease of use ☆`4,747`
*   [bhmj/jsonslice (⭐92)](https://github.com/bhmj/jsonslice) — json slicer ☆`92`
*   [hashicorp/mql (⭐65)](https://github.com/hashicorp/mql) — Model Query Language (mql) is a query language for your database models. ☆`65`
*   [ccbrown/api-fu (⭐57)](https://github.com/ccbrown/api-fu) — A collection of Go packages for creating robust GraphQL APIs ☆`57`
*   [AsaiYusuke/jsonpath (⭐30)](https://github.com/AsaiYusuke/jsonpath) — JSONPath query library ☆`30`

### Relational Database Drivers

*   [go-sql-driver/mysql (⭐15k)](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,388`
*   [jackc/pgx (⭐14k)](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`13,553`
*   [denisenkom/go-mssqldb (⭐1.9k)](https://github.com/denisenkom/go-mssqldb) — Microsoft SQL server driver written in go language ☆`1,881`
*   [ncruces/go-sqlite3 (⭐926)](https://github.com/ncruces/go-sqlite3) — Go bindings to SQLite using wasm2go ☆`940`
*   [godror/godror (⭐588)](https://github.com/godror/godror) — GO DRiver for ORacle DB ☆`589`
*   [cvilsmeier/sqinn-go (⭐513)](https://github.com/cvilsmeier/sqinn-go) — Golang SQLite without cgo ☆`515`
*   [VinGarcia/ksql (⭐355)](https://github.com/VinGarcia/ksql) — A Simple and Powerful Golang SQL Library ☆`355`
*   [surrealdb/surrealdb.go (⭐307)](https://github.com/surrealdb/surrealdb.go) — SurrealDB SDK for Golang ☆`308`
*   [nakagami/firebirdsql (⭐256)](https://github.com/nakagami/firebirdsql) — Firebird RDBMS sql driver for Go (golang) ☆`256`
*   [ydb-platform/ydb-go-sdk (⭐176)](https://github.com/ydb-platform/ydb-go-sdk) — Pure Go native and database/sql driver for YDB ☆`177`
*   [rqlite/gorqlite (⭐179)](https://github.com/rqlite/gorqlite) — A Go client for rqlite, the distributed database built on SQLite ☆`180`
*   [apache/calcite-avatica-go (⭐124)](https://github.com/apache/calcite-avatica-go) — Apache Calcite Go ☆`124`

### SQL Query Builders

*   [sqlc-dev/sqlc (⭐17k)](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`17,208`
*   [xo/dbtpl (⭐3.9k)](https://github.com/xo/dbtpl) — Generate Go code for databases ☆`3,889`
*   [go-jet/jet (⭐3.6k)](https://github.com/go-jet/jet) — Type-safe SQL builder with codegen ☆`3,615`
*   [doug-martin/goqu (⭐2.6k)](https://github.com/doug-martin/goqu) — SQL builder and query library for golang ☆`2,643`
*   [didi/gendry (⭐1.6k)](https://github.com/didi/gendry) — a golang library for sql builder ☆`1,639`
*   [lqs/sqlingo (⭐449)](https://github.com/lqs/sqlingo) — A lightweight DSL & ORM which helps you to write SQL in Go. ☆`450`
*   [nullism/bqb (⭐187)](https://github.com/nullism/bqb) — Lightweight query builder ☆`189`
*   [arthurkushman/buildsqlx (⭐185)](https://github.com/arthurkushman/buildsqlx) — Go database query builder library for PostgreSQL ☆`185`
*   [galeone/igor (⭐126)](https://github.com/galeone/igor) — igor is an abstraction layer for PostgreSQL with a gorm like syntax. ☆`126`
*   [cristalhq/builq (⭐97)](https://github.com/cristalhq/builq) — Easily build SQL queries in Go. ☆`97`
*   [JiveGroup/FluentSQL (⭐18)](https://github.com/JiveGroup/FluentSQL) — Fluent SQL - flexible and powerful SQL string builder ☆`18`

### Search and Analytic Databases

*   [elastic/go-elasticsearch (⭐6k)](https://github.com/elastic/go-elasticsearch) — The official Go client for Elasticsearch ☆`6,036`
*   [ClickHouse/clickhouse-go (⭐3.3k)](https://github.com/ClickHouse/clickhouse-go) — Golang driver for ClickHouse ☆`3,257`
*   [sourcegraph/zoekt (⭐1.4k)](https://github.com/sourcegraph/zoekt) — Fast trigram-based code search ☆`1,491`
*   [sdqri/effdsl (⭐34)](https://github.com/sdqri/effdsl) — Elasticsearch query builder for golang ☆`34`

## DevOps & Build

### Backup

*   [restic/restic (⭐33k)](https://github.com/restic/restic) — Fast, secure backup program ☆`32,817`
*   [gilbertchen/duplicacy (⭐5.6k)](https://github.com/gilbertchen/duplicacy) — Cloud backup tool ☆`5,633`

### Build Automation

*   [air-verse/air (⭐23k)](https://github.com/air-verse/air) — Live reload for Go apps ☆`23,207`
*   [go-task/task (⭐15k)](https://github.com/go-task/task) — Fast cross-platform build tool inspired by Make ☆`15,182`
*   [joerdav/xc (⭐1.4k)](https://github.com/joerdav/xc) — Markdown defined task runner. ☆`1,375`
*   [goyek/goyek (⭐680)](https://github.com/goyek/goyek) — Task automation Go library ☆`681`
*   [flowexec/flow (⭐132)](https://github.com/flowexec/flow) — Local developer automation platform that flows with you ☆`132`

### CI/CD

*   [harness/harness (⭐34k)](https://github.com/harness/harness) — End-to-end developer platform ☆`34,023`
*   [woodpecker-ci/woodpecker (⭐6.6k)](https://github.com/woodpecker-ci/woodpecker) — Simple, powerful CI/CD engine ☆`6,706`
*   [ovh/cds (⭐4.8k)](https://github.com/ovh/cds) — Enterprise CI/CD platform ☆`4,804`
*   [raviqqe/muffet (⭐2.6k)](https://github.com/raviqqe/muffet) — Fast website link checker ☆`2,593`
*   [pipe-cd/pipecd (⭐1.3k)](https://github.com/pipe-cd/pipecd) — The One CD for All {applications, platforms, operations} ☆`1,263`
*   [jenkins-zh/jenkins-cli (⭐410)](https://github.com/jenkins-zh/jenkins-cli) — Jenkins CLI allows you to manage your Jenkins in an easy way ☆`413`
*   [vladopajic/go-test-coverage (⭐224)](https://github.com/vladopajic/go-test-coverage) — Report test coverage threshold issues ☆`223`
*   [appleboy/drone-scp (⭐167)](https://github.com/appleboy/drone-scp) — Copy files via SSH for Drone ☆`167`
*   [nikogura/gomason (⭐66)](https://github.com/nikogura/gomason) — A tool for testing, building, signing, and publishing binaries. ☆`66`
*   [appleboy/drone-jenkins (⭐41)](https://github.com/appleboy/drone-jenkins) — Drone plugin for trigger Jenkins jobs. ☆`41`
*   [opnlabs/dot (⭐34)](https://github.com/opnlabs/dot) — Minimal CI using Docker ☆`35`
*   [gha-common/go-beautiful-html-coverage (⭐21)](https://github.com/gha-common/go-beautiful-html-coverage) — GitHub Action for code coverage reports ☆`21`

### Containers

*   [moby/moby (⭐72k)](https://github.com/moby/moby) — Container ecosystem components ☆`71,561`
*   [traefik/traefik (⭐62k)](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`62,349`
*   [ko-build/ko (⭐8.4k)](https://github.com/ko-build/ko) — Build and deploy Go applications ☆`8,378`
*   [s0rg/decompose (⭐126)](https://github.com/s0rg/decompose) — Reverse-engineering tool for docker environments ☆`128`
*   [x1unix/docker-go-mingw (⭐53)](https://github.com/x1unix/docker-go-mingw) — Docker for Go with MinGW toolchain ☆`53`

### DevOps Utilities

*   [go-gitea/gitea (⭐54k)](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`54,466`
*   [moovweb/gvm (⭐12k)](https://github.com/moovweb/gvm) — Go Version Manager ☆`11,572`
*   [TwiN/gatus (⭐10k)](https://github.com/TwiN/gatus) — Developer-oriented status page with alerting ☆`10,495`
*   [bitfield/script (⭐6.9k)](https://github.com/bitfield/script) — Making it easy to write shell-like scripts in Go ☆`6,950`
*   [fleetdm/fleet (⭐6.1k)](https://github.com/fleetdm/fleet) — Open device management ☆`6,173`
*   [taubyte/tau (⭐5k)](https://github.com/taubyte/tau) — Fullstack Workspace for Humans & Machines ☆`4,992`
*   [megaease/easeprobe (⭐2.3k)](https://github.com/megaease/easeprobe) — Service health monitoring tool ☆`2,304`
*   [ajvb/kala (⭐2.2k)](https://github.com/ajvb/kala) — Modern Job Scheduler ☆`2,159`
*   [gabrie30/ghorg (⭐2k)](https://github.com/gabrie30/ghorg) — Clone entire GitHub orgs ☆`1,999`
*   [sanbornm/go-selfupdate (⭐1.7k)](https://github.com/sanbornm/go-selfupdate) — Enable your Go applications to self update ☆`1,684`
*   [yusufcanb/tlm (⭐1.5k)](https://github.com/yusufcanb/tlm) — Local CLI Copilot, powered by Ollama. ☆`1,477`
*   [ovh/utask (⭐1.4k)](https://github.com/ovh/utask) — Automation engine with YAML config ☆`1,367`
*   [TimothyYe/skm (⭐1k)](https://github.com/TimothyYe/skm) — A simple and powerful SSH keys manager ☆`1,009`
*   [scaleway/scaleway-cli (⭐959)](https://github.com/scaleway/scaleway-cli) — Command Line Interface for Scaleway ☆`963`
*   [alexliesenfeld/health (⭐830)](https://github.com/alexliesenfeld/health) — A simple and flexible health check library for Go. ☆`830`
*   [kool-dev/kool (⭐713)](https://github.com/kool-dev/kool) — Dev to cloud web apps made easy ☆`716`
*   [kevincobain2000/gobrew (⭐412)](https://github.com/kevincobain2000/gobrew) — Go version manager without root ☆`413`
*   [appleboy/easyssh-proxy (⭐347)](https://github.com/appleboy/easyssh-proxy) — Simple SSH protocol implementation ☆`347`
*   [xitonix/trubka (⭐337)](https://github.com/xitonix/trubka) — A CLI tool for Kafka ☆`336`
*   [emicklei/mora (⭐315)](https://github.com/emicklei/mora) — MongoDB generic REST server in Go ☆`315`
*   [thevxn/dish (⭐275)](https://github.com/thevxn/dish) — A simple, remotely configurable monitoring service. ☆`275`
*   [jkaninda/goma-gateway (⭐175)](https://github.com/jkaninda/goma-gateway) — Lightweight API gateway and proxy ☆`176`
*   [datarootsio/tf-profile (⭐164)](https://github.com/datarootsio/tf-profile) — Profile Terraform runs ☆`164`
*   [kazhuravlev/healthcheck (⭐21)](https://github.com/kazhuravlev/healthcheck) — Readiness probes for Kubernetes application ☆`21`

### Infrastructure

*   [hashicorp/packer (⭐16k)](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,635`
*   [pomerium/pomerium (⭐4.7k)](https://github.com/pomerium/pomerium) — Pomerium is an identity and context-aware access proxy. ☆`4,722`
*   [peak/s5cmd (⭐4k)](https://github.com/peak/s5cmd) — Parallel S3 and local filesystem execution tool. ☆`3,970`
*   [aptly-dev/aptly (⭐2.8k)](https://github.com/aptly-dev/aptly) — aptly - Debian repository management tool ☆`2,788`
*   [KusionStack/kusion (⭐1.3k)](https://github.com/KusionStack/kusion) — Declarative platform orchestrator ☆`1,286`
*   [oxyno-zeta/s3-proxy (⭐442)](https://github.com/oxyno-zeta/s3-proxy) — S3 reverse proxy with auth ☆`445`

### Kubernetes

*   [kubernetes/kubernetes (⭐121k)](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`121,331`
*   [k3s-io/k3s (⭐32k)](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`32,557`
*   [kubernetes/minikube (⭐32k)](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,623`
*   [kubernetes-sigs/kind (⭐15k)](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,114`
*   [kubeshark/kubeshark (⭐12k)](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`11,834`
*   [flannel-io/flannel (⭐9.4k)](https://github.com/flannel-io/flannel) — Network fabric for containers ☆`9,420`
*   [getanteon/anteon (⭐8.5k)](https://github.com/getanteon/anteon) — eBPF Kubernetes monitoring tool ☆`8,538`
*   [kubevela/kubevela (⭐7.7k)](https://github.com/kubevela/kubevela) — The Modern Application Platform. ☆`7,714`
*   [k3d-io/k3d (⭐6.3k)](https://github.com/k3d-io/k3d) — Little helper to run CNCF's k3s in Docker ☆`6,327`
*   [stefanprodan/podinfo (⭐5.8k)](https://github.com/stefanprodan/podinfo) — Go microservice template for Kubernetes ☆`5,866`
*   [apecloud/kubeblocks (⭐3k)](https://github.com/apecloud/kubeblocks) — Kubernetes operator for databases ☆`2,997`
*   [kubenetworks/kubevpn (⭐1.3k)](https://github.com/kubenetworks/kubevpn) — Connect to Kubernetes cluster network ☆`1,307`
*   [abahmed/kwatch (⭐1k)](https://github.com/abahmed/kwatch) — monitor & detect crashes in your Kubernetes(K8s) cluster instantly ☆`1,000`
*   [getanteon/alaz (⭐718)](https://github.com/getanteon/alaz) — eBPF agent for K8s observability ☆`718`

### Load Testing

*   [grafana/k6 (⭐30k)](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`30,202`
*   [tsenart/vegeta (⭐25k)](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`24,961`
*   [codesenberg/bombardier (⭐6.7k)](https://github.com/codesenberg/bombardier) — Fast cross-platform HTTP benchmarking tool written in Go ☆`6,753`
*   [rogerwelin/cassowary (⭐808)](https://github.com/rogerwelin/cassowary) — Modern cross-platform HTTP load-testing tool written in Go ☆`808`

## Email

*   [axllent/mailpit (⭐8.9k)](https://github.com/axllent/mailpit) — An email and SMTP testing tool with API for developers ☆`9,006`
*   [foxcpp/maddy (⭐5.9k)](https://github.com/foxcpp/maddy) — Composable all-in-one mail server. ☆`5,898`
*   [mjl-/mox (⭐5.6k)](https://github.com/mjl-/mox) — Modern secure mail server ☆`5,591`
*   [matcornic/hermes (⭐3k)](https://github.com/matcornic/hermes) — Clean HTML email generator ☆`3,032`
*   [AfterShip/email-verifier (⭐1.5k)](https://github.com/AfterShip/email-verifier) — Email verification without sending emails ☆`1,538`
*   [wneessen/go-mail (⭐1.3k)](https://github.com/wneessen/go-mail) — Easy to use, yet comprehensive library for sending mails with Go ☆`1,309`
*   [sendgrid/sendgrid-go (⭐1.1k)](https://github.com/sendgrid/sendgrid-go) — The Official Twilio SendGrid Golang API Library ☆`1,053`
*   [mailgun/mailgun-go (⭐744)](https://github.com/mailgun/mailgun-go) — Go library for the Mailgun API. ☆`745`
*   [xhit/go-simple-mail (⭐693)](https://github.com/xhit/go-simple-mail) — Simple mail sending with TLS/SSL ☆`693`
*   [emersion/go-message (⭐441)](https://github.com/emersion/go-message) — Internet Message Format library ☆`443`
*   [vanng822/go-premailer (⭐193)](https://github.com/vanng822/go-premailer) — Inline CSS for HTML mail ☆`196`
*   [truemail-rb/truemail-go (⭐130)](https://github.com/truemail-rb/truemail-go) — Email validator via Regex, DNS, SMTP ☆`130`
*   [toorop/go-dkim (⭐99)](https://github.com/toorop/go-dkim) — DKIM package for golang ☆`99`
*   [dimuska139/go-email-normalizer (⭐77)](https://github.com/dimuska139/go-email-normalizer) — Normalize email addresses ☆`78`
*   [valord577/mailx (⭐20)](https://github.com/valord577/mailx) — A library that makes it easier to send email via SMTP. ☆`21`

## Finance & Blockchain

### Blockchain

*   [ethereum/go-ethereum (⭐51k)](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`50,951`
*   [ipfs/kubo (⭐17k)](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`16,972`
*   [lightningnetwork/lnd (⭐8.1k)](https://github.com/lightningnetwork/lnd) — Lightning Network Daemon ☆`8,118`
*   [cosmos/cosmos-sdk (⭐6.9k)](https://github.com/cosmos/cosmos-sdk) — A Framework for Building High Value Public Blockchains ☆`6,961`
*   [gagliardetto/solana-go (⭐1.5k)](https://github.com/gagliardetto/solana-go) — Go SDK library and RPC client for the Solana Blockchain ☆`1,527`
*   [gnolang/gno (⭐1.1k)](https://github.com/gnolang/gno) — Interpreted Go virtual machine ☆`1,059`
*   [cometbft/cometbft (⭐868)](https://github.com/cometbft/cometbft) — Byzantine fault-tolerant consensus ☆`873`
*   [ChainSafe/gossamer (⭐455)](https://github.com/ChainSafe/gossamer) — Go Implementation of the Polkadot Host ☆`455`

### Financial

*   [shopspring/decimal (⭐7.3k)](https://github.com/shopspring/decimal) — Arbitrary-precision fixed-point decimal numbers in Go ☆`7,285`
*   [achannarasappa/ticker (⭐6k)](https://github.com/achannarasappa/ticker) — Terminal stock and crypto tracker ☆`5,994`
*   [Rhymond/go-money (⭐1.9k)](https://github.com/Rhymond/go-money) — Go implementation of Fowler's Money pattern ☆`1,881`
*   [c9s/bbgo (⭐1.6k)](https://github.com/c9s/bbgo) — The modern cryptocurrency trading bot framework written in Go. ☆`1,613`
*   [formancehq/ledger (⭐1.2k)](https://github.com/formancehq/ledger) — The programmable open source core ledger for fintech ☆`1,176`
*   [bojanz/currency (⭐627)](https://github.com/bojanz/currency) — Currency handling for Go. ☆`628`
*   [moov-io/ach (⭐533)](https://github.com/moov-io/ach) — ACH file reader, writer, validator ☆`535`
*   [invopop/gobl (⭐259)](https://github.com/invopop/gobl) — Go Business Language ☆`268`
*   [govalues/decimal (⭐224)](https://github.com/govalues/decimal) — Correctly rounded decimals for Go ☆`230`
*   [quagmt/udecimal (⭐176)](https://github.com/quagmt/udecimal) — High-precision decimal library ☆`177`
*   [jovandeginste/payme (⭐90)](https://github.com/jovandeginste/payme) — QR code generator (ASCII & PNG) for SEPA payments ☆`91`
*   [jokruger/dec128 (⭐42)](https://github.com/jokruger/dec128) — High performance 128-bit fixed-point decimal numbers in go. ☆`42`
*   [govalues/money (⭐49)](https://github.com/govalues/money) — Correctly rounded monetary amounts and exchange rates for Go ☆`50`
*   [nikolaydubina/fpmoney (⭐35)](https://github.com/nikolaydubina/fpmoney) — Fixed-Point Decimal Money ☆`35`
*   [nikolaydubina/fpdecimal (⭐34)](https://github.com/nikolaydubina/fpdecimal) — Fixed-Point Decimals ☆`34`

### Payment APIs

*   [stripe/stripe-go (⭐2.5k)](https://github.com/stripe/stripe-go) — Stripe API library for Go ☆`2,547`
*   [plutov/paypal (⭐775)](https://github.com/plutov/paypal) — Golang client for PayPal REST API ☆`776`
*   [brunomvsouza/ynab.go (⭐79)](https://github.com/brunomvsouza/ynab.go) — Client for YNAB API ☆`79`

## GUI & Desktop

### GUI

*   [fyne-io/fyne (⭐28k)](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`28,045`
*   [webview/webview (⭐14k)](https://github.com/webview/webview) — Tiny webview library for Go ☆`13,971`
*   [go-vgo/robotgo (⭐11k)](https://github.com/go-vgo/robotgo) — Cross-platform RPA and GUI automation ☆`10,660`
*   [maxence-charriere/go-app (⭐8.9k)](https://github.com/maxence-charriere/go-app) — Build progressive web apps with Go and WASM ☆`8,865`
*   [progrium/darwinkit (⭐5.4k)](https://github.com/progrium/darwinkit) — Native Mac APIs for Go. Previously known as MacDriver ☆`5,410`
*   [getlantern/systray (⭐3.7k)](https://github.com/getlantern/systray) — Cross-platform systray library ☆`3,678`
*   [cogentcore/core (⭐2.3k)](https://github.com/cogentcore/core) — Powerful GUI framework for Go ☆`2,313`
*   [gotk3/gotk3 (⭐2.2k)](https://github.com/gotk3/gotk3) — Go bindings for GTK3 ☆`2,204`
*   [roblillack/spot (⭐1.3k)](https://github.com/roblillack/spot) — React-like desktop GUI toolkit for Go ☆`1,260`
*   [ncruces/zenity (⭐894)](https://github.com/ncruces/zenity) — Zenity dialogs for Golang, Windows, macOS ☆`898`
*   [energye/energy (⭐578)](https://github.com/energye/energy) — CEF-based GUI framework ☆`581`
*   [AllenDang/cimgui-go (⭐505)](https://github.com/AllenDang/cimgui-go) — Auto generated Go wrapper for Dear ImGui via cimgui ☆`506`
*   [richardwilkes/unison (⭐319)](https://github.com/richardwilkes/unison) — Unified GUI toolkit for Go ☆`320`

### Windows

*   [go-ole/go-ole (⭐1.3k)](https://github.com/go-ole/go-ole) — win32 ole implementation for golang ☆`1,300`
*   [gonutz/d3d9 (⭐163)](https://github.com/gonutz/d3d9) — Direct3D9 wrapper for Go. ☆`163`

## Game Development

### Game Engines

*   [hajimehoshi/ebiten (⭐13k)](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`13,061`
*   [fogleman/nes (⭐5.6k)](https://github.com/fogleman/nes) — NES emulator written in Go. ☆`5,641`
*   [topfreegames/pitaya (⭐2.7k)](https://github.com/topfreegames/pitaya) — Game server with clustering support ☆`2,754`
*   [xiaonanln/goworld (⭐2.7k)](https://github.com/xiaonanln/goworld) — Distributed game server engine ☆`2,708`
*   [gen2brain/raylib-go (⭐2.4k)](https://github.com/gen2brain/raylib-go) — Go bindings for raylib ☆`2,391`
*   [oakmound/oak (⭐1.7k)](https://github.com/oakmound/oak) — A pure Go game engine ☆`1,656`
*   [JoelOtter/termloop (⭐1.5k)](https://github.com/JoelOtter/termloop) — Terminal-based game engine for Go, built on top of Termbox ☆`1,472`
*   [gopxl/pixel (⭐383)](https://github.com/gopxl/pixel) — A hand-crafted 2D game library in Go. ☆`386`
*   [ungerik/go3d (⭐338)](https://github.com/ungerik/go3d) — A performance oriented 2D/3D math package for Go ☆`338`
*   [mlange-42/ark (⭐225)](https://github.com/mlange-42/ark) — Ark -- Archetype-based Entity Component System (ECS) for Go. ☆`230`
*   [kelindar/tile (⭐212)](https://github.com/kelindar/tile) — 2D grid engine for games ☆`213`
*   [andygeiss/ecs (⭐171)](https://github.com/andygeiss/ecs) — Entity Component System for games ☆`171`
*   [gonutz/prototype (⭐107)](https://github.com/gonutz/prototype) — 2D game prototyping framework ☆`107`
*   [s0rg/fantasyname (⭐40)](https://github.com/s0rg/fantasyname) — RinkWorks fantasy name generator for golang ☆`41`
*   [s0rg/grid (⭐25)](https://github.com/s0rg/grid) — Generic 2D grid ☆`25`

### OpenGL

*   [go-gl/glfw (⭐1.7k)](https://github.com/go-gl/glfw) — Go bindings for GLFW 3 ☆`1,670`
*   [go-gl/gl (⭐1.2k)](https://github.com/go-gl/gl) — Go bindings for OpenGL (generated via glow) ☆`1,192`
*   [go-gl/mathgl (⭐599)](https://github.com/go-gl/mathgl) — A pure Go 3D math library. ☆`602`

## Geospatial

*   [tidwall/tile38 (⭐9.6k)](https://github.com/tidwall/tile38) — Real-time Geospatial and Geofencing ☆`9,602`
*   [golang/geo (⭐1.8k)](https://github.com/golang/geo) — S2 geometry library in Go ☆`1,827`
*   [consbio/mbtileserver (⭐775)](https://github.com/consbio/mbtileserver) — MBTiles server in Go ☆`778`
*   [spatial-go/geoos (⭐532)](https://github.com/spatial-go/geoos) — Spatial data and geometric algorithms ☆`532`
*   [paulmach/osm (⭐446)](https://github.com/paulmach/osm) — OpenStreetMap data library ☆`448`
*   [uber/h3-go (⭐410)](https://github.com/uber/h3-go) — H3 hexagonal geospatial indexing ☆`414`
*   [airbusgeo/godal (⭐174)](https://github.com/airbusgeo/godal) — GDAL wrapper for Go ☆`174`
*   [peterstace/simplefeatures (⭐169)](https://github.com/peterstace/simplefeatures) — OpenGIS Simple Feature implementation ☆`172`
*   [wroge/wgs84 (⭐140)](https://github.com/wroge/wgs84) — Zero-dep coordinate transformations ☆`141`
*   [pantrif/s2-geojson (⭐37)](https://github.com/pantrif/s2-geojson) — Visualize S2 cells on a map ☆`37`

## Go Tooling

### Compilers

*   [gopherjs/gopherjs (⭐13k)](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,132`
*   [yassinebenaid/bunster (⭐2.6k)](https://github.com/yassinebenaid/bunster) — Compile shell scripts to static binaries. ☆`2,653`
*   [Konstantin8105/c4go (⭐379)](https://github.com/Konstantin8105/c4go) — Transpiling C code to Go code ☆`379`
*   [go2hx/go2hx (⭐150)](https://github.com/go2hx/go2hx) — Import Go libraries in Haxe ☆`150`

### Editor Plugins

*   [fatih/vim-go (⭐16k)](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,235`
*   [visualfc/liteide (⭐7.8k)](https://github.com/visualfc/liteide) — LiteIDE is a simple, open source, cross-platform Go IDE. ☆`7,759`
*   [nsf/gocode (⭐5k)](https://github.com/nsf/gocode) — An autocompletion daemon for the Go programming language ☆`4,999`
*   [golang/vscode-go (⭐4.2k)](https://github.com/golang/vscode-go) — Go extension for Visual Studio Code ☆`4,220`
*   [dominikh/go-mode.el (⭐1.4k)](https://github.com/dominikh/go-mode.el) — Emacs mode for the Go programming language ☆`1,450`
*   [incu6us/goimports-reviser (⭐715)](https://github.com/incu6us/goimports-reviser) — Imports sorting and code formatting tool ☆`716`

### Generate Tools

*   [xuri/xgen (⭐406)](https://github.com/xuri/xgen) — XSD parser and code generator ☆`406`
*   [kazhuravlev/options-gen (⭐103)](https://github.com/kazhuravlev/options-gen) — Codegen for functional options in go projects ☆`103`
*   [g4s8/envdoc (⭐94)](https://github.com/g4s8/envdoc) — Go tool to generate documentation for environment variables ☆`94`

### Go Tools

*   [go-swagger/go-swagger (⭐10k)](https://github.com/go-swagger/go-swagger) — Swagger 2.0 implementation for go ☆`9,961`
*   [ondrajz/go-callvis (⭐6.5k)](https://github.com/ondrajz/go-callvis) — Visualize call graph of a Go program using Graphviz ☆`6,461`
*   [Zxilly/go-size-analyzer (⭐2.1k)](https://github.com/Zxilly/go-size-analyzer) — Analyze compiled Go binary size ☆`2,102`
*   [pointlander/peg (⭐1.1k)](https://github.com/pointlander/peg) — PEG parser generator for Go ☆`1,103`
*   [safedep/vet (⭐968)](https://github.com/safedep/vet) — Protect against malicious open source packages ☆`982`
*   [janpfeifer/gonb (⭐995)](https://github.com/janpfeifer/gonb) — Go notebook kernel for Jupyter ☆`1,003`
*   [alajmo/sake (⭐743)](https://github.com/alajmo/sake) — Task runner for local and remote hosts ☆`744`
*   [goccmack/gocc (⭐658)](https://github.com/goccmack/gocc) — Parser and scanner generator ☆`658`
*   [moshebe/gebug (⭐634)](https://github.com/moshebe/gebug) — Debug Dockerized Go apps ☆`634`
*   [iyashjayesh/monigo (⭐404)](https://github.com/iyashjayesh/monigo) — Performance monitoring library ☆`406`
*   [edwingeng/hotswap (⭐422)](https://github.com/edwingeng/hotswap) — Hot reload Go code without restart ☆`423`
*   [becheran/roumon (⭐234)](https://github.com/becheran/roumon) — Universal goroutine monitor using pprof and termui ☆`234`
*   [bitfield/gotestdox (⭐194)](https://github.com/bitfield/gotestdox) — A tool for formatting Go test results as readable documentation ☆`193`
*   [ahmedakef/gotutor (⭐75)](https://github.com/ahmedakef/gotutor) — Online Go Debugger & Visualizer ☆`75`
*   [bobg/decouple (⭐35)](https://github.com/bobg/decouple) — find overspecified function parameters in Go code ☆`36`
*   [bobg/modver (⭐21)](https://github.com/bobg/modver) — a tool that helps you obey semantic versioning rules in your Go module ☆`21`
*   [dustinblackman/gomodrun (⭐38)](https://github.com/dustinblackman/gomodrun) — Run binaries from go.mod ☆`38`

## Hardware & IoT

### Hardware

*   [shirou/gopsutil (⭐12k)](https://github.com/shirou/gopsutil) — psutil for golang ☆`11,751`
*   [arduino/arduino-cli (⭐4.8k)](https://github.com/arduino/arduino-cli) — Arduino command line tool ☆`4,843`
*   [jaypipes/ghw (⭐1.8k)](https://github.com/jaypipes/ghw) — Go HardWare discovery/inspection library ☆`1,827`
*   [zcalusic/sysinfo (⭐575)](https://github.com/zcalusic/sysinfo) — Linux system information library ☆`576`

### IoT

*   [hybridgroup/gobot (⭐9.4k)](https://github.com/hybridgroup/gobot) — Robotics and IoT framework ☆`9,387`
*   [lf-edge/ekuiper (⭐1.7k)](https://github.com/lf-edge/ekuiper) — Lightweight data stream processing engine for IoT edge ☆`1,686`
*   [rulego/rulego (⭐1.4k)](https://github.com/rulego/rulego) — Lightweight rule engine framework ☆`1,458`
*   [Edgenesis/shifu (⭐1.4k)](https://github.com/Edgenesis/shifu) — Kubernetes-native IoT gateway ☆`1,407`
*   [e154/smart-home (⭐96)](https://github.com/e154/smart-home) — software package for automation ☆`95`
*   [maxatome/go-vitotrol (⭐23)](https://github.com/maxatome/go-vitotrol) — golang client library to Viessmann Vitotrol web service ☆`23`

## Networking

### Consensus

*   [hashicorp/raft (⭐8.9k)](https://github.com/hashicorp/raft) — Golang implementation of the Raft consensus protocol ☆`8,966`
*   [lni/dragonboat (⭐5.3k)](https://github.com/lni/dragonboat) — Multi-group Raft consensus library ☆`5,298`
*   [etcd-io/raft (⭐993)](https://github.com/etcd-io/raft) — Raft library for maintaining a replicated state machine ☆`1,001`
*   [vadiminshakov/committer (⭐40)](https://github.com/vadiminshakov/committer) — 2PC and 3PC protocols for Go ☆`41`

### DNS

*   [miekg/dns (⭐8.6k)](https://github.com/miekg/dns) — DNS library in Go ☆`8,652`
*   [0xERR0R/blocky (⭐6.2k)](https://github.com/0xERR0R/blocky) — DNS ad-blocker for local networks ☆`6,211`
*   [hashicorp/mdns (⭐1.3k)](https://github.com/hashicorp/mdns) — Simple mDNS client/server library in Golang ☆`1,351`
*   [semihalev/sdns (⭐1k)](https://github.com/semihalev/sdns) — High-performance recursive DNS ☆`1,033`
*   [FenkoHQ/dnsmonster (⭐352)](https://github.com/FenkoHQ/dnsmonster) — Passive DNS Capture and Monitoring Toolkit ☆`353`
*   [joeig/go-powerdns (⭐103)](https://github.com/joeig/go-powerdns) — PowerDNS API client for Go (community project) ☆`103`

### Distributed Utilities

*   [luraproject/lura (⭐6.7k)](https://github.com/luraproject/lura) — Ultra-performant API gateway ☆`6,748`
*   [chrislusf/gleam (⭐3.6k)](https://github.com/chrislusf/gleam) — Distributed map/reduce in Go ☆`3,555`
*   [bsm/redislock (⭐1.7k)](https://github.com/bsm/redislock) — Simplified distributed locking implementation using Redis ☆`1,743`
*   [k8gb-io/k8gb (⭐1.2k)](https://github.com/k8gb-io/k8gb) — A cloud native Kubernetes Global Balancer ☆`1,160`
*   [temporalio/sdk-go (⭐841)](https://github.com/temporalio/sdk-go) — Temporal Go SDK ☆`852`
*   [AppsFlyer/go-sundheit (⭐560)](https://github.com/AppsFlyer/go-sundheit) — Health checks library for Go ☆`560`
*   [tarmac-project/tarmac (⭐342)](https://github.com/tarmac-project/tarmac) — Functions as Monolith or Microservices ☆`343`
*   [italolelis/outboxer (⭐166)](https://github.com/italolelis/outboxer) — A library that implements the outboxer pattern in go ☆`166`
*   [capillariesio/capillaries (⭐68)](https://github.com/capillariesio/capillaries) — Distributed batch data processing framework ☆`68`
*   [svcavallar/celeriac.v1 (⭐76)](https://github.com/svcavallar/celeriac.v1) — Celery client for Go ☆`76`
*   [sanketplus/go-mysql-lock (⭐66)](https://github.com/sanketplus/go-mysql-lock) — MySQL Backed Locking Primitive ☆`66`
*   [pdupub/go-pdu (⭐49)](https://github.com/pdupub/go-pdu) — An PDU implementation in Go ☆`49`
*   [mbrostami/consistenthash (⭐32)](https://github.com/mbrostami/consistenthash) — Consistent hashing implementation ☆`32`

### HTTP & Proxy

*   [valyala/fasthttp (⭐23k)](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,305`
*   [elazarl/goproxy (⭐6.6k)](https://github.com/elazarl/goproxy) — An HTTP proxy library for Go ☆`6,638`
*   [wzshiming/httpproxy (⭐31)](https://github.com/wzshiming/httpproxy) — HTTP proxy handler and dialer ☆`31`

### HTTP Clients

*   [go-resty/resty (⭐12k)](https://github.com/go-resty/resty) — Simple HTTP, REST, and SSE client library for Go ☆`11,600`
*   [imroc/req (⭐4.8k)](https://github.com/imroc/req) — Simple Go HTTP client with Black Magic ☆`4,772`
*   [gojek/heimdall (⭐2.7k)](https://github.com/gojek/heimdall) — An enhanced HTTP client for Go ☆`2,702`
*   [hashicorp/go-retryablehttp (⭐2.3k)](https://github.com/hashicorp/go-retryablehttp) — Retryable HTTP client in Go ☆`2,287`
*   [levigross/grequests (⭐2.2k)](https://github.com/levigross/grequests) — A Go "clone" of the great and famous Requests library ☆`2,182`
*   [dghubble/sling (⭐1.7k)](https://github.com/dghubble/sling) — A Go HTTP client library for creating and sending API requests ☆`1,719`
*   [earthboundkid/requests (⭐1.7k)](https://github.com/earthboundkid/requests) — HTTP requests for Gophers ☆`1,669`
*   [bogdanfinn/tls-client (⭐1.5k)](https://github.com/bogdanfinn/tls-client) — HTTP client with TLS fingerprint spoofing ☆`1,526`
*   [Noooste/azuretls-client (⭐434)](https://github.com/Noooste/azuretls-client) — HTTP client to spoof TLS/JA3 fingerprint ☆`438`
*   [monaco-io/request (⭐295)](https://github.com/monaco-io/request) — go request, go http client ☆`295`
*   [opus-domini/fast-shot (⭐117)](https://github.com/opus-domini/fast-shot) — Fluent HTTP client for Go ☆`119`
*   [go-zoox/fetch (⭐89)](https://github.com/go-zoox/fetch) — Powerful HTTP client for Go ☆`89`
*   [NdoleStudio/go-otelroundtripper (⭐86)](https://github.com/NdoleStudio/go-otelroundtripper) — OpenTelemetry metrics for HTTP clients ☆`86`
*   [rezmoss/axios4go (⭐32)](https://github.com/rezmoss/axios4go) — Axios-inspired HTTP client ☆`33`
*   [lib4u/fake-useragent (⭐15)](https://github.com/lib4u/fake-useragent) — Up-to-date simple useragent faker with real world database in Golang ☆`16`

### Servers

*   [caddyserver/caddy (⭐71k)](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`71,072`
*   [pocketbase/pocketbase (⭐57k)](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`57,070`
*   [etcd-io/etcd (⭐52k)](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`51,698`
*   [drakkan/sftpgo (⭐12k)](https://github.com/drakkan/sftpgo) — Full-featured SFTP/FTP/HTTP server ☆`11,815`
*   [adnanh/webhook (⭐12k)](https://github.com/adnanh/webhook) — Lightweight webhook server ☆`11,695`
*   [roadrunner-server/roadrunner (⭐8.4k)](https://github.com/roadrunner-server/roadrunner) — High-performance PHP application server ☆`8,427`
*   [easegress-io/easegress (⭐5.9k)](https://github.com/easegress-io/easegress) — A Cloud Native traffic orchestration system ☆`5,873`
*   [charmbracelet/wish (⭐5k)](https://github.com/charmbracelet/wish) — Make SSH apps, just like that! ☆`5,059`
*   [flipt-io/flipt (⭐4.7k)](https://github.com/flipt-io/flipt) — Enterprise-ready, Git native feature management solution ☆`4,754`
*   [getfider/fider (⭐4.1k)](https://github.com/getfider/fider) — Open platform to collect and prioritize feedback ☆`4,178`
*   [xyproto/algernon (⭐3k)](https://github.com/xyproto/algernon) — Web server with Lua and Markdown ☆`2,995`
*   [openflagr/flagr (⭐2.6k)](https://github.com/openflagr/flagr) — Feature flagging and A/B testing ☆`2,580`
*   [thomaspoignant/go-feature-flag (⭐2k)](https://github.com/thomaspoignant/go-feature-flag) — Open source feature flag solution ☆`1,972`
*   [msoap/shell2http (⭐1.5k)](https://github.com/msoap/shell2http) — Executing shell commands via HTTP server ☆`1,477`
*   [openrundev/openrun (⭐811)](https://github.com/openrundev/openrun) — Open source Cloud Run alternative ☆`814`
*   [webhookx-io/webhookx (⭐273)](https://github.com/webhookx-io/webhookx) — The Next-Generation Webhooks Gateway. ☆`290`
*   [baalimago/wd-41 (⭐151)](https://github.com/baalimago/wd-41) — Web-Development 41, a static web server with live-reload ☆`151`
*   [blind-oracle/cortex-tenant (⭐133)](https://github.com/blind-oracle/cortex-tenant) — Prometheus proxy with tenant ID injection ☆`133`
*   [rekby/lets-proxy2 (⭐101)](https://github.com/rekby/lets-proxy2) — Reverse proxy with auto TLS ☆`102`
*   [42atomys/webhooked (⭐42)](https://github.com/42atomys/webhooked) — A webhook receiver on steroids. ☆`42`

### Network Utilities

*   [fortio/fortio (⭐3.7k)](https://github.com/fortio/fortio) — Load testing and echo server ☆`3,684`
*   [hashicorp/go-getter (⭐1.8k)](https://github.com/hashicorp/go-getter) — Download files from URLs ☆`1,814`
*   [TimothyYe/godns (⭐1.7k)](https://github.com/TimothyYe/godns) — Dynamic DNS client for multiple providers ☆`1,744`
*   [cavaliergopher/grab (⭐1.5k)](https://github.com/cavaliergopher/grab) — Download manager package ☆`1,474`
*   [schollz/peerdiscovery (⭐668)](https://github.com/schollz/peerdiscovery) — Cross-platform local peer discovery ☆`668`
*   [fclairamb/ftpserverlib (⭐464)](https://github.com/fclairamb/ftpserverlib) — FTP server library for Go ☆`465`
*   [skibish/ddns (⭐267)](https://github.com/skibish/ddns) — Personal DDNS client with Digital Ocean Networking DNS as backend. ☆`268`
*   [assafmo/joincap (⭐221)](https://github.com/assafmo/joincap) — Merge pcap files ☆`221`
*   [c-robinson/iplib (⭐151)](https://github.com/c-robinson/iplib) — A library for working with IP addresses and networks in Go ☆`151`
*   [gaissmai/bart (⭐121)](https://github.com/gaissmai/bart) — Balanced routing table ☆`123`
*   [alegrey91/fwdctl (⭐72)](https://github.com/alegrey91/fwdctl) — Manage IPTables forwards via CLI ☆`72`

### P2P & Torrent

*   [anacrolix/torrent (⭐6k)](https://github.com/anacrolix/torrent) — Full-featured BitTorrent client package and utilities ☆`5,992`
*   [dragonflyoss/dragonfly (⭐3.1k)](https://github.com/dragonflyoss/dragonfly) — P2P-based container image distribution ☆`3,097`
*   [cenkalti/rain (⭐1.1k)](https://github.com/cenkalti/rain) — BitTorrent client and library in Go ☆`1,114`
*   [anacrolix/dht (⭐349)](https://github.com/anacrolix/dht) — DHT for BitTorrent ☆`351`

### Protocols

*   [pion/webrtc (⭐16k)](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,152`
*   [quic-go/quic-go (⭐11k)](https://github.com/quic-go/quic-go) — A production-ready QUIC implementation in pure Go ☆`11,492`
*   [google/gopacket (⭐6.8k)](https://github.com/google/gopacket) — Provides packet processing capabilities for Go ☆`6,760`
*   [osrg/gobgp (⭐4k)](https://github.com/osrg/gobgp) — BGP implemented in the Go Programming Language ☆`4,004`
*   [lxzan/gws (⭐1.7k)](https://github.com/lxzan/gws) — Fast websocket server and client ☆`1,737`
*   [gosnmp/gosnmp (⭐1.2k)](https://github.com/gosnmp/gosnmp) — An SNMP library written in Go ☆`1,246`
*   [bluenviron/gortsplib (⭐897)](https://github.com/bluenviron/gortsplib) — RTSP client and server library for the Go programming language ☆`897`
*   [ccding/go-stun (⭐719)](https://github.com/ccding/go-stun) — A go implementation of the STUN client (RFC 3489 and RFC 5389) ☆`719`
*   [google/gnxi (⭐282)](https://github.com/google/gnxi) — gNXI Tools - gRPC Network Management/Operations Interface Tools ☆`282`
*   [jeroenrinzema/psql-wire (⭐219)](https://github.com/jeroenrinzema/psql-wire) — PostgreSQL wire protocol for Go ☆`226`
*   [jimlambrt/gldap (⭐120)](https://github.com/jimlambrt/gldap) — Build LDAP services w/ Go ☆`120`
*   [soypat/natiu-mqtt (⭐104)](https://github.com/soypat/natiu-mqtt) — Extensible MQTT for embedded systems ☆`104`

### RPC

*   [grpc/grpc-go (⭐23k)](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,853`
*   [lesismal/arpc (⭐1.1k)](https://github.com/lesismal/arpc) — Two-way RPC with broadcast support ☆`1,090`
*   [ybbus/jsonrpc (⭐369)](https://github.com/ybbus/jsonrpc) — A simple go implementation of json rpc 2.0 client over http ☆`370`
*   [osamingo/jsonrpc (⭐193)](https://github.com/osamingo/jsonrpc) — The jsonrpc package helps implement of JSON-RPC 2.0 ☆`193`

### SSH & SFTP

*   [gliderlabs/ssh (⭐4.1k)](https://github.com/gliderlabs/ssh) — Easy SSH servers in Golang ☆`4,111`
*   [pkg/sftp (⭐1.6k)](https://github.com/pkg/sftp) — SFTP support for the go.crypto/ssh package ☆`1,633`
*   [masterzen/winrm (⭐462)](https://github.com/masterzen/winrm) — Windows remote command library ☆`462`

### TCP/UDP Frameworks

*   [panjf2000/gnet (⭐11k)](https://github.com/panjf2000/gnet) — High-performance event-loop network ☆`11,113`
*   [xtaci/kcp-go (⭐4.5k)](https://github.com/xtaci/kcp-go) — A crypto-secure Reliable-UDP library for Golang with FEC support. ☆`4,502`
*   [cloudwego/netpoll (⭐4.5k)](https://github.com/cloudwego/netpoll) — High-performance I/O framework ☆`4,545`
*   [lesismal/nbio (⭐2.7k)](https://github.com/lesismal/nbio) — High-performance network library ☆`2,714`
*   [xtaci/gaio (⭐1.1k)](https://github.com/xtaci/gaio) — High-performance, minimalist async-io (proactor) networking for Golang. ☆`1,109`
*   [cheng-zhongliang/event (⭐119)](https://github.com/cheng-zhongliang/event) — Simple I/O event notification library wirtten in Golang ☆`119`
*   [fish-tennis/gnet (⭐27)](https://github.com/fish-tennis/gnet) — high performance net library for game server ☆`27`

### VPN & Tunneling

*   [cloudflare/cloudflared (⭐14k)](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`13,576`
*   [xjasonlyu/tun2socks (⭐5k)](https://github.com/xjasonlyu/tun2socks) — TUN to SOCKS proxy ☆`4,996`
*   [songgao/water (⭐2.1k)](https://github.com/songgao/water) — A simple TUN/TAP library written in native Go. ☆`2,147`
*   [NodePassProject/nodepass (⭐2.1k)](https://github.com/NodePassProject/nodepass) — Secure TCP/UDP tunneling with TLS ☆`2,089`

## Queues & Pub/Sub

### Brokers

*   [nats-io/nats-server (⭐19k)](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`19,407`
*   [emitter-io/emitter (⭐4k)](https://github.com/emitter-io/emitter) — High-performance pub/sub broker ☆`3,999`
*   [mochi-mqtt/server (⭐1.8k)](https://github.com/mochi-mqtt/server) — Embeddable MQTT v5 broker ☆`1,822`

### Clients & Libraries

*   [hibiken/asynq (⭐13k)](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`13,051`
*   [IBM/sarama (⭐12k)](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,454`
*   [centrifugal/centrifugo (⭐10k)](https://github.com/centrifugal/centrifugo) — Scalable real-time messaging server ☆`10,097`
*   [ThreeDotsLabs/watermill (⭐9.6k)](https://github.com/ThreeDotsLabs/watermill) — Building event-driven applications the easy way in Go. ☆`9,614`
*   [appleboy/gorush (⭐8.7k)](https://github.com/appleboy/gorush) — A push notification server written in Go (Golang). ☆`8,702`
*   [RichardKnop/machinery (⭐8k)](https://github.com/RichardKnop/machinery) — Async task queue with message passing ☆`7,947`
*   [nats-io/nats.go (⭐6.5k)](https://github.com/nats-io/nats.go) — Golang client for NATS, the cloud native messaging system. ☆`6,510`
*   [dunglas/mercure (⭐5.2k)](https://github.com/dunglas/mercure) — Server-Sent Events hub ☆`5,213`
*   [confluentinc/confluent-kafka-go (⭐5.1k)](https://github.com/confluentinc/confluent-kafka-go) — Confluent's Apache Kafka Golang client ☆`5,113`
*   [olahol/melody (⭐4.1k)](https://github.com/olahol/melody) — Minimalist websocket framework for Go ☆`4,069`
*   [sideshow/apns2 (⭐3.2k)](https://github.com/sideshow/apns2) — Apple Push Notification Service ☆`3,163`
*   [lovoo/goka (⭐2.5k)](https://github.com/lovoo/goka) — Kafka stream processing library ☆`2,511`
*   [rabbitmq/amqp091-go (⭐2k)](https://github.com/rabbitmq/amqp091-go) — An AMQP 0-9-1 Go client maintained by the RabbitMQ team ☆`1,981`
*   [asaskevich/EventBus (⭐2k)](https://github.com/asaskevich/EventBus) — \[Go] Lightweight eventbus with async compatibility for Go ☆`1,966`
*   [containrrr/shoutrrr (⭐1.5k)](https://github.com/containrrr/shoutrrr) — Notification library for gophers and their furry friends. ☆`1,543`
*   [pebbe/zmq4 (⭐1.2k)](https://github.com/pebbe/zmq4) — A Go interface to ZeroMQ version 4 ☆`1,248`
*   [timbray/quamina (⭐481)](https://github.com/timbray/quamina) — Fast pattern-matching library ☆`486`
*   [cskr/pubsub (⭐448)](https://github.com/cskr/pubsub) — A simple pubsub package for go. ☆`449`
*   [jandelgado/rabtap (⭐279)](https://github.com/jandelgado/rabtap) — RabbitMQ wire tap and swiss army knife ☆`280`
*   [mehdihadeli/Go-MediatR (⭐276)](https://github.com/mehdihadeli/Go-MediatR) — Mediator pattern for CQRS ☆`278`
*   [goptics/varmq (⭐181)](https://github.com/goptics/varmq) — Zero-dep message queue library ☆`182`
*   [oagudo/outbox (⭐119)](https://github.com/oagudo/outbox) — Transactional outbox pattern ☆`121`
*   [hyperonym/ratus (⭐124)](https://github.com/hyperonym/ratus) — RESTful async task queue server ☆`124`
*   [dailymotion/oplog (⭐110)](https://github.com/dailymotion/oplog) — A generic oplog/replication system for microservices ☆`110`
*   [jirenius/go-res (⭐67)](https://github.com/jirenius/go-res) — RES Service protocol library for Go ☆`68`
*   [Protocol-Lattice/GoEventBus (⭐58)](https://github.com/Protocol-Lattice/GoEventBus) — A lock-free, ultra-fast event bus for Go ☆`58`
*   [SchwarzDigits/hypermatch (⭐33)](https://github.com/SchwarzDigits/hypermatch) — High-performance rule matching ☆`33`

## Science

*   [gonum/gonum (⭐8.3k)](https://github.com/gonum/gonum) — Numeric libraries for Go ☆`8,334`
*   [gonum/plot (⭐2.9k)](https://github.com/gonum/plot) — Plotting and visualization ☆`2,947`
*   [paulmach/orb (⭐1.1k)](https://github.com/paulmach/orb) — 2D geometry types and utilities ☆`1,102`
*   [madelynnblue/go-dsp (⭐909)](https://github.com/madelynnblue/go-dsp) — Digital Signal Processing for Go ☆`909`
*   [bebop/poly (⭐720)](https://github.com/bebop/poly) — Synthetic biology library for Go ☆`720`
*   [hmdsefi/gograph (⭐107)](https://github.com/hmdsefi/gograph) — Generic graph algorithms library ☆`109`
*   [nikolaydubina/jsonl-graph (⭐77)](https://github.com/nikolaydubina/jsonl-graph) — JSONL Graph Tools ☆`77`
*   [claygod/PiHex (⭐20)](https://github.com/claygod/PiHex) — Generate hexadecimal Pi digits ☆`20`

## Scripting

### Embeddable Languages

*   [php/frankenphp (⭐11k)](https://github.com/php/frankenphp) — The modern PHP app server ☆`10,938`
*   [expr-lang/expr (⭐7.7k)](https://github.com/expr-lang/expr) — Expression evaluation for Go ☆`7,752`
*   [yuin/gopher-lua (⭐6.9k)](https://github.com/yuin/gopher-lua) — Lua VM and compiler in Go ☆`6,862`
*   [dop251/goja (⭐6.8k)](https://github.com/dop251/goja) — ECMAScript engine in pure Go ☆`6,780`
*   [d5/tengo (⭐3.8k)](https://github.com/d5/tengo) — Fast script language for Go ☆`3,792`
*   [Shopify/go-lua (⭐3.4k)](https://github.com/Shopify/go-lua) — Lua VM in Go ☆`3,424`
*   [google/cel-go (⭐2.9k)](https://github.com/google/cel-go) — Common Expression Language for Go ☆`2,910`
*   [google/starlark-go (⭐2.6k)](https://github.com/google/starlark-go) — Starlark config language in Go ☆`2,653`
*   [metacall/core (⭐1.8k)](https://github.com/metacall/core) — Polyglot programming runtime ☆`1,793`
*   [wa-lang/wa (⭐1.8k)](https://github.com/wa-lang/wa) — The Wa Programming Language ☆`1,759`
*   [mattn/anko (⭐1.6k)](https://github.com/mattn/anko) — Scriptable interpreter in Go ☆`1,560`
*   [PaesslerAG/gval (⭐810)](https://github.com/PaesslerAG/gval) — Expression evaluation in Go ☆`811`
*   [ichiban/prolog (⭐708)](https://github.com/ichiban/prolog) — Prolog scripting engine for Go ☆`715`
*   [aarzilli/golua (⭐691)](https://github.com/aarzilli/golua) — Lua C API bindings for Go ☆`691`
*   [1set/starlet (⭐41)](https://github.com/1set/starlet) — Starlark wrapper with batteries ☆`42`

### Code Generators

*   [oapi-codegen/oapi-codegen (⭐8.2k)](https://github.com/oapi-codegen/oapi-codegen) — Generate Go code from OpenAPI 3 specs ☆`8,184`
*   [dave/jennifer (⭐3.6k)](https://github.com/dave/jennifer) — Code generator for Go ☆`3,605`
*   [hexdigest/gowrap (⭐1.3k)](https://github.com/hexdigest/gowrap) — Generate interface decorators ☆`1,314`
*   [awalterschulze/goderive (⭐1.3k)](https://github.com/awalterschulze/goderive) — Generate mundane Go functions ☆`1,264`
*   [abice/go-enum (⭐931)](https://github.com/abice/go-enum) — Enum generator for Go ☆`934`
*   [jmattheis/goverter (⭐826)](https://github.com/jmattheis/goverter) — Generate type-safe converters ☆`836`
*   [rjeczalik/interfaces (⭐432)](https://github.com/rjeczalik/interfaces) — Code generation tools for Go ☆`432`
*   [switchupcb/copygen (⭐400)](https://github.com/switchupcb/copygen) — Copy values between types ☆`402`
*   [reedom/convergen (⭐48)](https://github.com/reedom/convergen) — Type-to-type copy code generator ☆`50`

## Security

### Certificates

*   [go-acme/lego (⭐9.3k)](https://github.com/go-acme/lego) — Let's Encrypt/ACME client and library written in Go ☆`9,341`
*   [caddyserver/certmagic (⭐5.5k)](https://github.com/caddyserver/certmagic) — Automatic HTTPS certificate management ☆`5,490`
*   [tg123/go-htpasswd (⭐47)](https://github.com/tg123/go-htpasswd) — Apache htpasswd Parser for Go. ☆`47`
*   [adrianosela/sslmgr (⭐31)](https://github.com/adrianosela/sslmgr) — SSL certificate abstraction ☆`31`

### Cryptography

*   [FiloSottile/age (⭐22k)](https://github.com/FiloSottile/age) — Simple encryption tool ☆`21,747`
*   [authzed/spicedb (⭐6.5k)](https://github.com/authzed/spicedb) — Zanzibar-inspired permissions DB ☆`6,542`
*   [awnumar/memguard (⭐2.7k)](https://github.com/awnumar/memguard) — Software sandbox for storage of sensitive information in memory. ☆`2,720`
*   [cossacklabs/themis (⭐2k)](https://github.com/cossacklabs/themis) — Cryptographic framework for data protection ☆`1,955`
*   [dromara/dongle (⭐1.1k)](https://github.com/dromara/dongle) — A simple, semantic and developer-friendly crypto package for golang ☆`1,100`
*   [anatol/booster (⭐623)](https://github.com/anatol/booster) — Fast and secure initramfs generator ☆`623`
*   [kevinburke/nacl (⭐552)](https://github.com/kevinburke/nacl) — Pure Go implementation of the NaCL set of API's ☆`552`
*   [ssh-vault/ssh-vault (⭐497)](https://github.com/ssh-vault/ssh-vault) — encrypt/decrypt using ssh keys ☆`500`
*   [number571/go-peer (⭐319)](https://github.com/number571/go-peer) — Secure decentralized networking ☆`319`
*   [lingrino/vaku (⭐159)](https://github.com/lingrino/vaku) — Extended Vault API and CLI ☆`159`
*   [anatol/luks.go (⭐95)](https://github.com/anatol/luks.go) — Pure Golang library to manage LUKS partitions ☆`95`
*   [zitadel/passwap (⭐73)](https://github.com/zitadel/passwap) — Unified password hashing ☆`73`
*   [rsjethani/secret (⭐32)](https://github.com/rsjethani/secret) — Prevent your secrets from leaking into logs, std\* etc. ☆`32`
*   [andskur/argon2-hashing (⭐25)](https://github.com/andskur/argon2-hashing) — Argon2 password hashing ☆`25`

### WAF & Protection

*   [Ullaakut/cameradar (⭐4.9k)](https://github.com/Ullaakut/cameradar) — Cameradar hacks its way into RTSP videosurveillance cameras ☆`4,940`
*   [corazawaf/coraza (⭐3.3k)](https://github.com/corazawaf/coraza) — ModSecurity-compatible WAF in Go ☆`3,372`
*   [mojocn/base64Captcha (⭐2.4k)](https://github.com/mojocn/base64Captcha) — captcha of base64 image string ☆`2,354`
*   [unrolled/secure (⭐2.3k)](https://github.com/unrolled/secure) — HTTP middleware for Go that facilitates some quick security wins. ☆`2,334`
*   [beelzebub-labs/beelzebub (⭐1.9k)](https://github.com/beelzebub-labs/beelzebub) — AI-powered honeypot framework ☆`1,911`
*   [cossacklabs/acra (⭐1.5k)](https://github.com/cossacklabs/acra) — Database security proxy ☆`1,462`
*   [securitybunker/databunker (⭐1.4k)](https://github.com/securitybunker/databunker) — Secure vault for PII/PHI/KYC records ☆`1,395`
*   [hillu/go-yara (⭐387)](https://github.com/hillu/go-yara) — Go bindings for YARA ☆`388`
*   [teler-sh/teler-waf (⭐399)](https://github.com/teler-sh/teler-waf) — HTTP middleware for WAF ☆`399`
*   [steambap/captcha (⭐162)](https://github.com/steambap/captcha) — Easy captcha library ☆`162`

### Zero Trust

*   [sigstore/cosign (⭐5.7k)](https://github.com/sigstore/cosign) — Code signing and transparency for containers and binaries ☆`5,752`
*   [openziti/ziti (⭐3.9k)](https://github.com/openziti/ziti) — Zero trust networking platform ☆`3,991`
*   [spiffe/spire (⭐2.2k)](https://github.com/spiffe/spire) — The SPIFFE Runtime Environment ☆`2,264`
*   [philips-labs/spiffe-vault (⭐99)](https://github.com/philips-labs/spiffe-vault) — Integrates Spiffe and Vault to have secretless authentication ☆`99`

## Testing & Quality

### Benchmarks

*   [smallnest/go-web-framework-benchmark (⭐2.1k)](https://github.com/smallnest/go-web-framework-benchmark) — Web framework benchmarks ☆`2,138`
*   [alecthomas/go\_serialization\_benchmarks (⭐1.6k)](https://github.com/alecthomas/go_serialization_benchmarks) — Serialization benchmarks for Go ☆`1,627`
*   [SimonWaldherr/golang-benchmarks (⭐142)](https://github.com/SimonWaldherr/golang-benchmarks) — Go(lang) benchmarks - (measure the speed of golang) ☆`142`
*   [feyeleanor/gospeed (⭐127)](https://github.com/feyeleanor/gospeed) — Go language construct benchmarks ☆`128`
*   [nikolaydubina/go-ml-benchmarks (⭐32)](https://github.com/nikolaydubina/go-ml-benchmarks) — Benchmarks of machine learning inference for Go ☆`32`

### Code Analysis

*   [golangci/golangci-lint (⭐19k)](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`18,710`
*   [boyter/scc (⭐8.2k)](https://github.com/boyter/scc) — Fast code counter and stats ☆`8,230`
*   [mgechev/revive (⭐5.4k)](https://github.com/mgechev/revive) — Fast, extensible Go linter ☆`5,453`
*   [kisielk/errcheck (⭐2.5k)](https://github.com/kisielk/errcheck) — errcheck checks that you checked errors. ☆`2,474`
*   [go-critic/go-critic (⭐2k)](https://github.com/go-critic/go-critic) — The most opinionated Go source code linter for code audit. ☆`2,036`
*   [daveshanley/vacuum (⭐1k)](https://github.com/daveshanley/vacuum) — Fast OpenAPI linter ☆`1,026`
*   [presmihaylov/todocheck (⭐435)](https://github.com/presmihaylov/todocheck) — Analyser for TODO comments ☆`435`
*   [mibk/dupl (⭐365)](https://github.com/mibk/dupl) — Code clone detection tool ☆`366`
*   [mdempsky/unconvert (⭐388)](https://github.com/mdempsky/unconvert) — Remove unnecessary type conversions ☆`388`
*   [tomarrell/wrapcheck (⭐360)](https://github.com/tomarrell/wrapcheck) — Check errors are wrapped ☆`373`
*   [shurcooL/gostatus (⭐245)](https://github.com/shurcooL/gostatus) — Show status of Go repositories ☆`245`
*   [Antonboom/testifylint (⭐163)](https://github.com/Antonboom/testifylint) — Linter for testify usage ☆`165`
*   [Crocmagnon/fatcontext (⭐72)](https://github.com/Crocmagnon/fatcontext) — Detect nested contexts in loops ☆`74`
*   [antham/ghokin (⭐52)](https://github.com/antham/ghokin) — Parallelized Gherkin formatter ☆`52`
*   [asticode/go-astitodo (⭐66)](https://github.com/asticode/go-astitodo) — Parse TODOs in your GO code ☆`66`
*   [sashamelentyev/usestdlibvars (⭐47)](https://github.com/sashamelentyev/usestdlibvars) — Linter for stdlib variables usage ☆`47`
*   [borovikovd/gomsort (⭐26)](https://github.com/borovikovd/gomsort) — Go msort - linter that sorts methods ☆`26`

### Mock

*   [vektra/mockery (⭐7k)](https://github.com/vektra/mockery) — Mock code autogenerator for Go ☆`7,031`
*   [DATA-DOG/go-sqlmock (⭐6.5k)](https://github.com/DATA-DOG/go-sqlmock) — SQL mock driver for testing ☆`6,534`
*   [brianvoe/gofakeit (⭐5.3k)](https://github.com/brianvoe/gofakeit) — Random fake data generator written in go ☆`5,327`
*   [uber-go/mock (⭐3.3k)](https://github.com/uber-go/mock) — GoMock is a mocking framework for the Go programming language. ☆`3,293`
*   [SpectoLabs/hoverfly (⭐2.5k)](https://github.com/SpectoLabs/hoverfly) — API simulation and virtualization ☆`2,472`
*   [matryer/moq (⭐2.2k)](https://github.com/matryer/moq) — Interface mocking via go generate ☆`2,192`
*   [jarcoal/httpmock (⭐2.1k)](https://github.com/jarcoal/httpmock) — HTTP mocking for Go ☆`2,076`
*   [maxbrunsfeld/counterfeiter (⭐1.1k)](https://github.com/maxbrunsfeld/counterfeiter) — Generate type-safe test doubles ☆`1,125`
*   [gojuno/minimock (⭐747)](https://github.com/gojuno/minimock) — Powerful mock generator ☆`747`
*   [DATA-DOG/go-txdb (⭐748)](https://github.com/DATA-DOG/go-txdb) — Transaction-isolated SQL driver ☆`748`
*   [pashagolub/pgxmock (⭐568)](https://github.com/pashagolub/pgxmock) — pgx mock driver for testing ☆`571`
*   [xhd2015/xgo (⭐431)](https://github.com/xhd2015/xgo) — All-in-one Go testing library ☆`431`
*   [seborama/govcr (⭐196)](https://github.com/seborama/govcr) — Record and replay HTTP interactions ☆`196`
*   [mocktools/go-smtp-mock (⭐160)](https://github.com/mocktools/go-smtp-mock) — SMTP mock server for testing ☆`162`
*   [elgohr/go-localstack (⭐85)](https://github.com/elgohr/go-localstack) — Go wrapper for LocalStack ☆`87`

### Performance

*   [jaegertracing/jaeger (⭐23k)](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`22,612`
*   [pixie-io/pixie (⭐6.4k)](https://github.com/pixie-io/pixie) — Kubernetes-native observability ☆`6,389`
*   [arl/statsviz (⭐3.6k)](https://github.com/arl/statsviz) — Visualize Go runtime metrics ☆`3,625`
*   [nikolaydubina/go-instrument (⭐291)](https://github.com/nikolaydubina/go-instrument) — Add trace spans to Go functions ☆`293`
*   [joetifa2003/mm-go (⭐193)](https://github.com/joetifa2003/mm-go) — Manual memory management for Go ☆`193`

### Browser Automation

*   [chromedp/chromedp (⭐13k)](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`12,868`
*   [go-rod/rod (⭐6.8k)](https://github.com/go-rod/rod) — Chrome DevTools driver for scraping ☆`6,814`
*   [sensepost/gowitness (⭐4.2k)](https://github.com/sensepost/gowitness) — Web screenshot utility with Chrome ☆`4,201`
*   [playwright-community/playwright-go (⭐3.2k)](https://github.com/playwright-community/playwright-go) — Browser automation for Chromium, Firefox, WebKit ☆`3,270`
*   [mafredri/cdp (⭐784)](https://github.com/mafredri/cdp) — Chrome DevTools Protocol bindings ☆`789`

### Testing Frameworks

*   [stretchr/testify (⭐26k)](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`25,903`
*   [keploy/keploy (⭐16k)](https://github.com/keploy/keploy) — API testing with auto mocks ☆`16,571`
*   [Shopify/toxiproxy (⭐12k)](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`11,922`
*   [testcontainers/testcontainers-go (⭐4.7k)](https://github.com/testcontainers/testcontainers-go) — Docker containers for integration tests ☆`4,737`
*   [google/go-cmp (⭐4.6k)](https://github.com/google/go-cmp) — Package for comparing Go values in tests ☆`4,612`
*   [gavv/httpexpect (⭐2.7k)](https://github.com/gavv/httpexpect) — End-to-end HTTP and REST API testing for Go. ☆`2,713`
*   [cucumber/godog (⭐2.6k)](https://github.com/cucumber/godog) — Cucumber for golang ☆`2,602`
*   [orlangure/gnomock (⭐1.5k)](https://github.com/orlangure/gnomock) — Test with ephemeral Docker containers ☆`1,483`
*   [dnaeon/go-vcr (⭐1.4k)](https://github.com/dnaeon/go-vcr) — Record and replay HTTP for tests ☆`1,365`
*   [go-testfixtures/testfixtures (⭐1.2k)](https://github.com/go-testfixtures/testfixtures) — Rails-like test fixtures for Go ☆`1,222`
*   [fergusstrange/embedded-postgres (⭐1.1k)](https://github.com/fergusstrange/embedded-postgres) — Embedded PostgreSQL for testing ☆`1,154`
*   [chapar-rest/chapar (⭐693)](https://github.com/chapar-rest/chapar) — API testing for HTTP and gRPC ☆`693`
*   [gotestyourself/gotest.tools (⭐577)](https://github.com/gotestyourself/gotest.tools) — Testing utilities for Go ☆`578`
*   [maxatome/go-testdeep (⭐463)](https://github.com/maxatome/go-testdeep) — Flexible deep comparison in tests ☆`463`
*   [appleboy/gofight (⭐445)](https://github.com/appleboy/gofight) — Testing API Handler written in Golang. ☆`444`
*   [viant/endly (⭐266)](https://github.com/viant/endly) — End to end functional test and automation framework ☆`266`
*   [ysmood/got (⭐269)](https://github.com/ysmood/got) — An enjoyable golang test framework. ☆`269`
*   [kinbiko/jsonassert (⭐141)](https://github.com/kinbiko/jsonassert) — JSON assertion library for tests ☆`141`
*   [adamluzsi/testcase (⭐127)](https://github.com/adamluzsi/testcase) — Opinionated testing framework ☆`127`
*   [earthboundkid/be (⭐131)](https://github.com/earthboundkid/be) — The Go test helper for minimalists ☆`132`
*   [corbym/gocrest (⭐106)](https://github.com/corbym/gocrest) — GoCrest - Hamcrest-like matchers for Go ☆`106`
*   [hedhyw/gherkingen (⭐94)](https://github.com/hedhyw/gherkingen) — Behaviour Driven Development tests generator for Golang ☆`95`
*   [madflojo/testcerts (⭐84)](https://github.com/madflojo/testcerts) — Generate test certificates on the fly ☆`84`
*   [viant/dsunit (⭐45)](https://github.com/viant/dsunit) — Datastore Testibility ☆`45`
*   [go-restit/restit (⭐55)](https://github.com/go-restit/restit) — A Go library help testing your RESTful API application ☆`55`
*   [rekby/fixenv (⭐33)](https://github.com/rekby/fixenv) — Pytest-inspired fixture caching for Go tests ☆`33`
*   [abecodes/dft (⭐19)](https://github.com/abecodes/dft) — Docker wrapper for testing ☆`19`

### Testing Utilities

*   [dvyukov/go-fuzz (⭐4.8k)](https://github.com/dvyukov/go-fuzz) — Randomized testing for Go ☆`4,845`
*   [pingcap/failpoint (⭐874)](https://github.com/pingcap/failpoint) — Failpoint implementation for Go ☆`875`

### Validation

*   [go-playground/validator (⭐20k)](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`19,829`
*   [Oudwins/zog (⭐1.2k)](https://github.com/Oudwins/zog) — Zod-inspired schema validation ☆`1,160`
*   [gookit/validate (⭐1.1k)](https://github.com/gookit/validate) — Struct and data validation ☆`1,127`
*   [twharmon/govalid (⭐113)](https://github.com/twharmon/govalid) — Struct validation using tags ☆`114`
*   [faceair/jio (⭐124)](https://github.com/faceair/jio) — JSON schema validator like Joi ☆`125`
*   [osamingo/checkdigit (⭐114)](https://github.com/osamingo/checkdigit) — Check digit algorithms ☆`114`
*   [marrow16/valix (⭐31)](https://github.com/marrow16/valix) — Request validation package ☆`31`
*   [tiendc/go-validator (⭐32)](https://github.com/tiendc/go-validator) — Intuitive validation library ☆`32`

## Text & NLP

### Formatters

*   [dustin/go-humanize (⭐4.8k)](https://github.com/dustin/go-humanize) — Human-friendly unit formatting ☆`4,814`
*   [neilotoole/sq (⭐2.5k)](https://github.com/neilotoole/sq) — SQL data wrangler ☆`2,455`
*   [bojanz/address (⭐82)](https://github.com/bojanz/address) — Address handling for Go ☆`82`

### Markup Languages

*   [BurntSushi/toml (⭐4.9k)](https://github.com/BurntSushi/toml) — TOML parser with reflection ☆`4,919`
*   [yuin/goldmark (⭐4.6k)](https://github.com/yuin/goldmark) — Markdown parser for Go ☆`4,662`
*   [JohannesKaufmann/html-to-markdown (⭐3.5k)](https://github.com/JohannesKaufmann/html-to-markdown) — Convert HTML to Markdown ☆`3,503`
*   [pelletier/go-toml (⭐1.9k)](https://github.com/pelletier/go-toml) — TOML library for Go ☆`1,915`
*   [antchfx/htmlquery (⭐781)](https://github.com/antchfx/htmlquery) — XPath for HTML queries ☆`781`
*   [clbanning/mxj (⭐633)](https://github.com/clbanning/mxj) — XML to/from map conversion ☆`633`
*   [mmalcek/bafi (⭐113)](https://github.com/mmalcek/bafi) — Universal format converter ☆`113`

### Miscellaneous

*   [microcosm-cc/bluemonday (⭐3.6k)](https://github.com/microcosm-cc/bluemonday) — Fast HTML sanitizer for Go ☆`3,648`
*   [gosimple/slug (⭐1.3k)](https://github.com/gosimple/slug) — URL-friendly slugify ☆`1,325`
*   [pemistahl/lingua-go (⭐1.3k)](https://github.com/pemistahl/lingua-go) — Natural language detection ☆`1,329`
*   [arunsupe/semantic-grep (⭐1.2k)](https://github.com/arunsupe/semantic-grep) — Grep for similar words ☆`1,215`
*   [mattn/go-runewidth (⭐682)](https://github.com/mattn/go-runewidth) — Rune width for terminals ☆`685`
*   [hedhyw/rex (⭐210)](https://github.com/hedhyw/rex) — Flexible regex constructor ☆`210`
*   [IGLOU-EU/go-wildcard (⭐100)](https://github.com/IGLOU-EU/go-wildcard) — Fast wildcard matching ☆`100`
*   [JoshuaDoes/gofuckyourself (⭐68)](https://github.com/JoshuaDoes/gofuckyourself) — Swear filter for Go ☆`69`
*   [alexsergivan/transliterator (⭐46)](https://github.com/alexsergivan/transliterator) — Text transliterator ☆`46`

### Morphological Analyzers

*   [nlpodyssey/spago (⭐1.9k)](https://github.com/nlpodyssey/spago) — ML and NLP library for Go ☆`1,849`
*   [ikawaha/kagome (⭐954)](https://github.com/ikawaha/kagome) — Japanese morphological analyzer ☆`956`
*   [afjoseph/RAKE.Go (⭐123)](https://github.com/afjoseph/RAKE.Go) — Rapid Keyword Extraction in Go ☆`122`
*   [jonreiter/govader (⭐53)](https://github.com/jonreiter/govader) — VADER sentiment analysis ☆`54`

### Parsers/Encoders/Decoders

*   [mvdan/sh (⭐8.6k)](https://github.com/mvdan/sh) — Shell parser and formatter ☆`8,587`
*   [mmcdole/gofeed (⭐2.8k)](https://github.com/mmcdole/gofeed) — Parse RSS, Atom, JSON feeds ☆`2,822`
*   [google/go-querystring (⭐2.1k)](https://github.com/google/go-querystring) — Encode structs to URL query strings ☆`2,134`
*   [olebedev/when (⭐1.5k)](https://github.com/olebedev/when) — Natural language date parser ☆`1,462`
*   [adrianmo/go-nmea (⭐257)](https://github.com/adrianmo/go-nmea) — NMEA sentence parser ☆`258`
*   [yassinebenaid/godump (⭐224)](https://github.com/yassinebenaid/godump) — Dump any Go variable ☆`224`
*   [editorconfig/editorconfig-core-go (⭐151)](https://github.com/editorconfig/editorconfig-core-go) — EditorConfig core in Go ☆`151`
*   [bzick/tokenizer (⭐139)](https://github.com/bzick/tokenizer) — Tokenizer/lexer for Go ☆`139`
*   [emersion/go-vcard (⭐124)](https://github.com/emersion/go-vcard) — vCard parser and formatter ☆`124`
*   [polera/gonameparts (⭐43)](https://github.com/polera/gonameparts) — Takes a full name and splits it into individual name parts ☆`43`

### Scrapers

*   [gocolly/colly (⭐25k)](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,179`
*   [PuerkitoBio/goquery (⭐15k)](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,923`
*   [mvdan/xurls (⭐1.3k)](https://github.com/mvdan/xurls) — Extract URLs from text ☆`1,252`
*   [s0rg/crawley (⭐334)](https://github.com/s0rg/crawley) — The unix-way web crawler ☆`334`
*   [zoomio/tagify (⭐39)](https://github.com/zoomio/tagify) — Extract tags from HTML/Markdown/text ☆`39`

### Text Analysis

*   [blevesearch/bleve (⭐11k)](https://github.com/blevesearch/bleve) — Text/numeric/geo/vector indexing library ☆`11,009`
*   [derekparker/trie (⭐787)](https://github.com/derekparker/trie) — Trie for extremely fast prefix search ☆`787`
*   [agnivade/levenshtein (⭐458)](https://github.com/agnivade/levenshtein) — Go implementation to calculate Levenshtein Distance. ☆`461`
*   [plar/go-adaptive-radix-tree (⭐411)](https://github.com/plar/go-adaptive-radix-tree) — Adaptive Radix Trees implemented in Go ☆`412`
*   [viant/ptrie (⭐45)](https://github.com/viant/ptrie) — A prefix tree implementation in go ☆`45`

### Tokenizers

*   [go-ego/gse (⭐2.8k)](https://github.com/go-ego/gse) — Multilingual text segmentation ☆`2,792`
*   [pebbe/textcat (⭐73)](https://github.com/pebbe/textcat) — N-gram text categorization ☆`73`

### Translation

*   [nicksnyder/go-i18n (⭐3.5k)](https://github.com/nicksnyder/go-i18n) — Translate Go programs ☆`3,492`
*   [leonelquinteros/gotext (⭐492)](https://github.com/leonelquinteros/gotext) — GNU gettext for Go ☆`491`
*   [vorlif/spreak (⭐93)](https://github.com/vorlif/spreak) — Gettext-based translation library ☆`93`
*   [invopop/ctxi18n (⭐92)](https://github.com/invopop/ctxi18n) — Context-based i18n for Go ☆`91`
*   [mehanizm/iuliia-go (⭐56)](https://github.com/mehanizm/iuliia-go) — Cyrillic to Latin transliteration ☆`56`
*   [youthlin/t (⭐21)](https://github.com/youthlin/t) — Translation util using gettext ☆`21`

## Third-party APIs

### Cloud Provider APIs

*   [googleapis/google-cloud-go (⭐4.4k)](https://github.com/googleapis/google-cloud-go) — Google Cloud Client Libraries for Go. ☆`4,428`
*   [googleapis/google-api-go-client (⭐4.4k)](https://github.com/googleapis/google-api-go-client) — Auto-generated Google APIs for Go. ☆`4,415`
*   [aws/aws-sdk-go-v2 (⭐3.5k)](https://github.com/aws/aws-sdk-go-v2) — AWS SDK for the Go programming language. ☆`3,493`
*   [minio/minio-go (⭐2.9k)](https://github.com/minio/minio-go) — High-performance object storage ☆`2,916`
*   [rhnvrm/simples3 (⭐197)](https://github.com/rhnvrm/simples3) — Simple AWS S3 library using REST ☆`198`
*   [circa10a/go-aws-news (⭐18)](https://github.com/circa10a/go-aws-news) — Go app + library to fetch what's new from AWS ☆`18`
*   [chainifynet/aws-encryption-sdk-go (⭐22)](https://github.com/chainifynet/aws-encryption-sdk-go) — AWS Encryption SDK for Go ☆`22`

### Other APIs

*   [codingsince1985/geo-golang (⭐539)](https://github.com/codingsince1985/geo-golang) — Go library to access geocoding and reverse geocoding APIs ☆`540`
*   [cyruzin/golang-tmdb (⭐157)](https://github.com/cyruzin/golang-tmdb) — Wrapper for TMDb API ☆`159`
*   [gregdel/pushover (⭐155)](https://github.com/gregdel/pushover) — Go wrapper for the Pushover API ☆`155`
*   [mvrilo/go-redoc (⭐94)](https://github.com/mvrilo/go-redoc) — Embedded OpenAPI documentation ☆`94`
*   [rapito/go-spotify (⭐51)](https://github.com/rapito/go-spotify) — Go library for the Spotify Web API ☆`52`
*   [rinchsan/device-check-go (⭐25)](https://github.com/rinchsan/device-check-go) — iOS DeviceCheck SDK for Go ☆`25`
*   [zc2638/swag (⭐50)](https://github.com/zc2638/swag) — Generate Swagger from code ☆`50`
*   [staskobzar/goami2 (⭐21)](https://github.com/staskobzar/goami2) — Simple Asterisk Manager Interface (AMI) library fo golang ☆`21`
*   [sostronk/go-steam (⭐33)](https://github.com/sostronk/go-steam) — Go library for querying Source servers ☆`33`
*   [Icelain/jokeapi (⭐27)](https://github.com/Icelain/jokeapi) — Official golang wrapper for Sv443's jokeapi. ☆`27`

### Productivity APIs

*   [mk-5/fjira (⭐262)](https://github.com/mk-5/fjira) — The golang fuzzy-find cli jira interface ☆`262`
*   [adlio/trello (⭐227)](https://github.com/adlio/trello) — Trello API wrapper for Go ☆`227`
*   [ctreminiom/go-atlassian (⭐198)](https://github.com/ctreminiom/go-atlassian) — Atlassian Cloud API client ☆`199`
*   [koltyakov/gosip (⭐168)](https://github.com/koltyakov/gosip) — SharePoint SDK for Go ☆`169`
*   [FreeLeh/GoFreeDB (⭐90)](https://github.com/FreeLeh/GoFreeDB) — Database on top of Google Sheets ☆`90`
*   [mehanizm/airtable (⭐85)](https://github.com/mehanizm/airtable) — Simple golang airtable API wrapper ☆`85`
*   [k-capehart/go-salesforce (⭐54)](https://github.com/k-capehart/go-salesforce) — Salesforce REST API client ☆`54`

## Utilities

### Build & Release

*   [goreleaser/goreleaser (⭐16k)](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,673`
*   [create-go-app/cli (⭐2.7k)](https://github.com/create-go-app/cli) — Create production-ready Go projects ☆`2,754`
*   [miniscruff/changie (⭐864)](https://github.com/miniscruff/changie) — Automated changelog tool ☆`868`
*   [karl-cardenas-coding/go-lambda-cleanup (⭐96)](https://github.com/karl-cardenas-coding/go-lambda-cleanup) — Remove old AWS Lambda versions ☆`96`

### CLI Tools

*   [junegunn/fzf (⭐79k)](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`78,900`
*   [wagoodman/dive (⭐54k)](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`53,634`
*   [xo/usql (⭐9.9k)](https://github.com/xo/usql) — Universal SQL CLI ☆`9,883`
*   [minio/mc (⭐3.4k)](https://github.com/minio/mc) — Unix utilities for object stores ☆`3,432`
*   [joshmedeski/sesh (⭐1.8k)](https://github.com/joshmedeski/sesh) — Terminal session manager ☆`1,840`
*   [itchyny/bed (⭐1.3k)](https://github.com/itchyny/bed) — Binary editor in Go ☆`1,346`
*   [owenthereal/upterm (⭐1.2k)](https://github.com/owenthereal/upterm) — Instant terminal sharing ☆`1,188`
*   [alajmo/mani (⭐669)](https://github.com/alajmo/mani) — CLI for managing repositories ☆`671`
*   [Unrud/remote-touchpad (⭐652)](https://github.com/Unrud/remote-touchpad) — Control mouse/keyboard remotely ☆`654`
*   [chenquan/diskusage (⭐303)](https://github.com/chenquan/diskusage) — Fast disk usage analyzer ☆`304`
*   [reugn/wifiqr (⭐280)](https://github.com/reugn/wifiqr) — Generate Wi-Fi QR codes ☆`280`
*   [hedhyw/json-log-viewer (⭐217)](https://github.com/hedhyw/json-log-viewer) — Interactive JSON log viewer ☆`217`
*   [hrtsegv/gitcs (⭐130)](https://github.com/hrtsegv/gitcs) — Git contributions graph generator ☆`131`
*   [antham/yogo (⭐45)](https://github.com/antham/yogo) — Check yopmail from CLI ☆`45`

### Data Conversion

*   [samber/lo (⭐21k)](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`21,147`
*   [duke-git/lancet (⭐5.3k)](https://github.com/duke-git/lancet) — Comprehensive util library ☆`5,280`
*   [darccio/mergo (⭐3.1k)](https://github.com/darccio/mergo) — Merge Go structs and maps ☆`3,091`
*   [goforj/godump (⭐1.7k)](https://github.com/goforj/godump) — Pretty-printer for Go structs ☆`1,727`
*   [gookit/filter (⭐151)](https://github.com/gookit/filter) — Data filtering and conversion ☆`150`
*   [tiendc/gofn (⭐51)](https://github.com/tiendc/gofn) — High-performance generic functions ☆`51`
*   [xorcare/pointer (⭐47)](https://github.com/xorcare/pointer) — Create optional field pointers ☆`47`
*   [shockerli/cvt (⭐54)](https://github.com/shockerli/cvt) — Safe type conversion ☆`54`

### Database Extensions

*   [jmoiron/sqlx (⭐18k)](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,542`
*   [georgysavva/scany (⭐1.5k)](https://github.com/georgysavva/scany) — Scan database rows to structs ☆`1,507`
*   [blockloop/scan (⭐610)](https://github.com/blockloop/scan) — Scan SQL rows to structs ☆`610`

### Date and Time

*   [dromara/carbon (⭐5.2k)](https://github.com/dromara/carbon) — Developer-friendly time package ☆`5,224`
*   [yaa110/go-persian-calendar (⭐237)](https://github.com/yaa110/go-persian-calendar) — Persian calendar for Go ☆`237`
*   [bykof/gostradamus (⭐210)](https://github.com/bykof/gostradamus) — Better DateTimes for Go ☆`208`
*   [nathan-osman/go-sunrise (⭐173)](https://github.com/nathan-osman/go-sunrise) — Calculate sunrise and sunset times ☆`173`
*   [rickb777/date (⭐142)](https://github.com/rickb777/date) — Date handling package ☆`142`
*   [relvacode/iso8601 (⭐157)](https://github.com/relvacode/iso8601) — Fast ISO8601 date parser ☆`158`

### Dependency Injection

*   [uber-go/fx (⭐7.4k)](https://github.com/uber-go/fx) — DI-based application framework ☆`7,415`
*   [uber-go/dig (⭐4.5k)](https://github.com/uber-go/dig) — Reflection-based DI toolkit ☆`4,455`
*   [goioc/di (⭐377)](https://github.com/goioc/di) — Simple DI for Go ☆`378`
*   [go-kod/kod (⭐197)](https://github.com/go-kod/kod) — DI with aspect-oriented support ☆`197`
*   [i-love-flamingo/dingo (⭐187)](https://github.com/i-love-flamingo/dingo) — DI framework for Go ☆`188`
*   [junioryono/godi (⭐70)](https://github.com/junioryono/godi) — DI with service lifetimes ☆`71`
*   [NVIDIA/gontainer (⭐65)](https://github.com/NVIDIA/gontainer) — Simple DI container ☆`65`
*   [muir/nject (⭐30)](https://github.com/muir/nject) — Type-safe DI for Go ☆`31`
*   [matzefriedrich/parsley (⭐30)](https://github.com/matzefriedrich/parsley) — Reflection-based DI package ☆`31`
*   [firasdarwish/ore (⭐25)](https://github.com/firasdarwish/ore) — Advanced DI solution ☆`26`
*   [logrange/linker (⭐35)](https://github.com/logrange/linker) — DI and IoC package ☆`35`
*   [componego/componego (⭐28)](https://github.com/componego/componego) — Component-oriented framework ☆`29`
*   [gontainer/gontainer (⭐16)](https://github.com/gontainer/gontainer) — YAML-based DI container ☆`16`

### Error Handling

*   [hashicorp/go-multierror (⭐2.6k)](https://github.com/hashicorp/go-multierror) — Represent multiple errors as one ☆`2,561`
*   [cockroachdb/errors (⭐2.4k)](https://github.com/cockroachdb/errors) — Error library with portability ☆`2,378`
*   [rotisserie/eris (⭐1.8k)](https://github.com/rotisserie/eris) — Errors with readable stack traces ☆`1,779`
*   [joomcode/errorx (⭐1.3k)](https://github.com/joomcode/errorx) — Comprehensive error handling ☆`1,271`
*   [ztrue/tracerr (⭐1.1k)](https://github.com/ztrue/tracerr) — Errors with stack trace ☆`1,106`
*   [samber/oops (⭐872)](https://github.com/samber/oops) — Structured error handling ☆`891`
*   [Southclaws/fault (⭐308)](https://github.com/Southclaws/fault) — Composable error wrapping ☆`308`

### File Handling

*   [schollz/croc (⭐34k)](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`34,462`
*   [qax-os/excelize (⭐20k)](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,423`
*   [pdfcpu/pdfcpu (⭐8.5k)](https://github.com/pdfcpu/pdfcpu) — PDF processor in Go ☆`8,535`
*   [spf13/afero (⭐6.6k)](https://github.com/spf13/afero) — Filesystem abstraction for Go ☆`6,603`
*   [dundee/gdu (⭐5.4k)](https://github.com/dundee/gdu) — Fast disk usage analyzer ☆`5,473`
*   [unidoc/unioffice (⭐4.8k)](https://github.com/unidoc/unioffice) — Office document library ☆`4,824`
*   [root-gg/plik (⭐1.7k)](https://github.com/root-gg/plik) — Temporary file upload system ☆`1,719`
*   [SebastiaanKlippert/go-wkhtmltopdf (⭐1.2k)](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) — HTML to PDF wrapper ☆`1,177`
*   [otiai10/copy (⭐770)](https://github.com/otiai10/copy) — Copy directories recursively ☆`771`
*   [ulikunitz/xz (⭐551)](https://github.com/ulikunitz/xz) — Pure golang package for reading and writing xz-compressed files ☆`552`
*   [no-src/gofs (⭐526)](https://github.com/no-src/gofs) — Cross-platform file sync ☆`526`
*   [mholt/archives (⭐383)](https://github.com/mholt/archives) — Create and extract archives ☆`388`
*   [viant/afs (⭐377)](https://github.com/viant/afs) — Abstract file storage ☆`381`
*   [C2FO/vfs (⭐357)](https://github.com/C2FO/vfs) — Virtual file system for Go ☆`358`
*   [gen2brain/go-unarr (⭐309)](https://github.com/gen2brain/go-unarr) — Decompression library bindings ☆`309`
*   [barasher/go-exiftool (⭐293)](https://github.com/barasher/go-exiftool) — Exiftool wrapper for metadata ☆`294`
*   [gomutex/godocx (⭐244)](https://github.com/gomutex/godocx) — Go library for reading and writing Microsoft Docx ☆`245`
*   [artonge/go-csv-tag (⭐129)](https://github.com/artonge/go-csv-tag) — CSV reading with tags ☆`130`
*   [charlievieth/fastwalk (⭐124)](https://github.com/charlievieth/fastwalk) — Fast directory traversal ☆`127`
*   [parsyl/parquet (⭐127)](https://github.com/parsyl/parquet) — Parquet file library ☆`127`
*   [adelowo/gulter (⭐70)](https://github.com/adelowo/gulter) — Multipart form handling ☆`70`
*   [go-the-way/exl (⭐32)](https://github.com/go-the-way/exl) — Excel binding to struct written in Go.(Only supports Go1.18+) ☆`32`

### Forms

*   [justinas/nosurf (⭐1.7k)](https://github.com/justinas/nosurf) — CSRF protection middleware ☆`1,730`
*   [gorilla/csrf (⭐1.2k)](https://github.com/gorilla/csrf) — CSRF prevention middleware ☆`1,186`
*   [go-playground/form (⭐903)](https://github.com/go-playground/form) — URL values to structs ☆`906`
*   [ggicci/httpin (⭐384)](https://github.com/ggicci/httpin) — HTTP request to struct binding ☆`385`
*   [sonh/qs (⭐80)](https://github.com/sonh/qs) — Encode structs to query params ☆`80`
*   [cinar/checker (⭐48)](https://github.com/cinar/checker) — Input validation with struct tags ☆`48`

### Functional

*   [samber/mo (⭐3.3k)](https://github.com/samber/mo) — Monads and FP for Go ☆`3,307`
*   [BooleanCat/go-functional (⭐527)](https://github.com/BooleanCat/go-functional) — Iterator library for Go ☆`527`
*   [seborama/fuego (⭐146)](https://github.com/seborama/fuego) — Functional programming in Go ☆`145`
*   [rjNemo/underscore (⭐118)](https://github.com/rjNemo/underscore) — Functional helpers for Go ☆`117`

### General

*   [wabarc/wayback (⭐2.2k)](https://github.com/wabarc/wayback) — Web archiving tool with IM interface ☆`2,167`
*   [gabriel-vasile/mimetype (⭐2k)](https://github.com/gabriel-vasile/mimetype) — MIME type detection by magic numbers ☆`1,958`
*   [qmuntal/stateless (⭐1.3k)](https://github.com/qmuntal/stateless) — Go library for creating finite state machines ☆`1,277`
*   [jonboulle/clockwork (⭐725)](https://github.com/jonboulle/clockwork) — a fake clock for golang ☆`725`
*   [Boeing/config-file-validator (⭐497)](https://github.com/Boeing/config-file-validator) — Cross Platform tool to validate configuration files ☆`498`
*   [biter777/countries (⭐502)](https://github.com/biter777/countries) — ISO country codes library ☆`505`
*   [ungerik/go-dry (⭐488)](https://github.com/ungerik/go-dry) — DRY (don't repeat yourself) package for Go ☆`488`
*   [subosito/gotenv (⭐306)](https://github.com/subosito/gotenv) — Load environment variables from `.env` or `io.Reader` in Go. ☆`306`
*   [viant/toolbox (⭐228)](https://github.com/viant/toolbox) — Toolbox - go utility library ☆`228`
*   [ikeikeikeike/go-sitemap-generator (⭐229)](https://github.com/ikeikeikeike/go-sitemap-generator) — Generate XML sitemaps ☆`229`
*   [maja42/goval (⭐174)](https://github.com/maja42/goval) — Expression evaluation in golang ☆`174`
*   [commander-cli/cmd (⭐160)](https://github.com/commander-cli/cmd) — A simple package to execute shell commands on linux, windows and osx ☆`160`
*   [jfcg/sorty (⭐144)](https://github.com/jfcg/sorty) — Fast Concurrent / Parallel Sorting in Go ☆`144`
*   [tiendc/go-deepcopy (⭐126)](https://github.com/tiendc/go-deepcopy) — Fast deep-copy library for Go ☆`126`
*   [syntaqx/cookie (⭐112)](https://github.com/syntaqx/cookie) — Cookies, but with structs, for happiness. ☆`112`
*   [pioz/countries (⭐95)](https://github.com/pioz/countries) — All you need when you are working with countries in Go. ☆`95`
*   [arthurkushman/pgo (⭐88)](https://github.com/arthurkushman/pgo) — Go library for PHP community with convenient functions ☆`88`
*   [wzshiming/gotype (⭐64)](https://github.com/wzshiming/gotype) — Golang source code parsing, usage like reflect package ☆`64`
*   [rkoesters/xdg (⭐48)](https://github.com/rkoesters/xdg) — FreeDesktop.org (xdg) Specs implemented in Go ☆`48`
*   [icza/backscanner (⭐69)](https://github.com/icza/backscanner) — Scan file lines backward ☆`69`
*   [kazhuravlev/just (⭐35)](https://github.com/kazhuravlev/just) — Collection of useful functions. Complete simple tasks faster! ☆`35`
*   [mikekonan/go-types (⭐23)](https://github.com/mikekonan/go-types) — OpenAPI3 types for Go ☆`23`
*   [ik5/gostrutils (⭐47)](https://github.com/ik5/gostrutils) — Collections of string utils I have created over the years ☆`47`
*   [floatdrop/debounce (⭐35)](https://github.com/floatdrop/debounce) — A zero-allocation debouncer ☆`35`
*   [lrita/numa (⭐38)](https://github.com/lrita/numa) — NUMA utility library for Go ☆`38`
*   [osamingo/gosh (⭐36)](https://github.com/osamingo/gosh) — Provide Go Statistics Handler, Struct, Measure Method ☆`36`
*   [nikolaydubina/watchhttp (⭐34)](https://github.com/nikolaydubina/watchhttp) — Expose command output via HTTP ☆`34`
*   [skovtunenko/graterm (⭐30)](https://github.com/skovtunenko/graterm) — Graceful termination primitives ☆`30`

### Logging

*   [sirupsen/logrus (⭐26k)](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,709`
*   [uber-go/zap (⭐24k)](https://github.com/uber-go/zap) — Fast structured logging ☆`24,388`
*   [rs/zerolog (⭐12k)](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,290`
*   [davecgh/go-spew (⭐6.4k)](https://github.com/davecgh/go-spew) — Deep pretty printer for debugging ☆`6,379`
*   [golang/glog (⭐3.6k)](https://github.com/golang/glog) — Leveled execution logs ☆`3,615`
*   [k0kubun/pp (⭐2k)](https://github.com/k0kubun/pp) — Colored pretty printer for Go ☆`2,035`
*   [lmittmann/tint (⭐1.2k)](https://github.com/lmittmann/tint) — Colorized slog handler ☆`1,256`
*   [Lifailon/lazyjournal (⭐1.2k)](https://github.com/Lifailon/lazyjournal) — TUI for journald, Docker, K8s logs ☆`1,201`
*   [getsentry/sentry-go (⭐1k)](https://github.com/getsentry/sentry-go) — Official Sentry SDK for Go ☆`1,058`
*   [phuslu/log (⭐834)](https://github.com/phuslu/log) — Fastest structured logging ☆`838`
*   [samber/slog-multi (⭐611)](https://github.com/samber/slog-multi) — Workflow design for slog handlers ☆`612`
*   [gookit/slog (⭐537)](https://github.com/gookit/slog) — Configurable logging library ☆`538`
*   [henvic/httpretty (⭐413)](https://github.com/henvic/httpretty) — Pretty-print HTTP requests ☆`413`
*   [hashicorp/logutils (⭐371)](https://github.com/hashicorp/logutils) — Logging utilities for Go ☆`371`
*   [simukti/sqldb-logger (⭐382)](https://github.com/simukti/sqldb-logger) — SQL database logger ☆`382`
*   [samber/slog-formatter (⭐212)](https://github.com/samber/slog-formatter) — Slog attribute formatting ☆`212`
*   [DeRuina/timberjack (⭐121)](https://github.com/DeRuina/timberjack) — Log rolling library ☆`124`
*   [rs/xlog (⭐141)](https://github.com/rs/xlog) — Context-aware HTTP logger ☆`140`
*   [yuseferi/zax (⭐34)](https://github.com/yuseferi/zax) — Zap logger with context ☆`34`
*   [clok/kemba (⭐17)](https://github.com/clok/kemba) — Tiny debug logging tool ☆`17`

### Networking Utils

*   [cristianoliveira/ergo (⭐650)](https://github.com/cristianoliveira/ergo) — Manage apps on different ports ☆`650`
*   [htcat/htcat (⭐561)](https://github.com/htcat/htcat) — Parallel HTTP download ☆`560`
*   [ferama/rospo (⭐358)](https://github.com/ferama/rospo) — Persistent SSH tunnels ☆`359`

### Project Layout

*   [golang-standards/project-layout (⭐56k)](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`55,624`
*   [Melkeydev/go-blueprint (⭐8.7k)](https://github.com/Melkeydev/go-blueprint) — Spin up Go projects with popular frameworks ☆`8,745`
*   [ardanlabs/service (⭐3.9k)](https://github.com/ardanlabs/service) — K8s service starter kit ☆`3,947`
*   [Shpota/goxygen (⭐3.6k)](https://github.com/Shpota/goxygen) — Generate full-stack web projects ☆`3,599`
*   [mikestefanello/pagoda (⭐2.9k)](https://github.com/mikestefanello/pagoda) — Full-stack web development starter kit ☆`2,921`
*   [go-nunu/nunu (⭐2.6k)](https://github.com/go-nunu/nunu) — CLI for building Go apps ☆`2,551`
*   [sagikazarmark/modern-go-application (⭐1.9k)](https://github.com/sagikazarmark/modern-go-application) — Modern Go app example ☆`1,938`
*   [naughtygopher/goapp (⭐1.1k)](https://github.com/naughtygopher/goapp) — Opinionated web app structure ☆`1,057`
*   [allaboutapps/go-starter (⭐599)](https://github.com/allaboutapps/go-starter) — Production-ready RESTful API template ☆`600`
*   [golang-templates/seed (⭐556)](https://github.com/golang-templates/seed) — Go app GitHub template ☆`556`
*   [raeperd/kickstart.go (⭐105)](https://github.com/raeperd/kickstart.go) — Minimal HTTP server template ☆`108`
*   [wangyoucao577/go-project-layout (⭐26)](https://github.com/wangyoucao577/go-project-layout) — Go project structure guide ☆`26`

### Resilience & Retry

*   [avast/retry-go (⭐2.9k)](https://github.com/avast/retry-go) — Simple retry mechanism ☆`2,902`
*   [eapache/go-resiliency (⭐2.3k)](https://github.com/eapache/go-resiliency) — Resiliency patterns for golang ☆`2,341`
*   [failsafe-go/failsafe-go (⭐2.2k)](https://github.com/failsafe-go/failsafe-go) — Fault tolerance patterns ☆`2,182`
*   [rubyist/circuitbreaker (⭐1.2k)](https://github.com/rubyist/circuitbreaker) — Circuit breakers in Go ☆`1,164`
*   [cep21/circuit (⭐806)](https://github.com/cep21/circuit) — Hystrix-like circuit breaker ☆`812`
*   [mennanov/limiters (⭐622)](https://github.com/mennanov/limiters) — Distributed rate limiters ☆`624`
*   [kamilsk/retry (⭐346)](https://github.com/kamilsk/retry) — Advanced retry mechanism ☆`346`
*   [webriots/rate (⭐165)](https://github.com/webriots/rate) — High-performance rate limiter ☆`165`

### Strings

*   [huandu/xstrings (⭐1.4k)](https://github.com/huandu/xstrings) — String functions from other langs ☆`1,418`
*   [abhimanyu003/sttr (⭐1.3k)](https://github.com/abhimanyu003/sttr) — CLI string operations ☆`1,302`
*   [gobeam/stringy (⭐251)](https://github.com/gobeam/stringy) — String case conversions ☆`251`
*   [ozgio/strutil (⭐207)](https://github.com/ozgio/strutil) — String utilities for Go ☆`207`

### System & Process

*   [cilium/ebpf (⭐7.6k)](https://github.com/cilium/ebpf) — eBPF library for Go ☆`7,609`
*   [maruel/panicparse (⭐3.7k)](https://github.com/maruel/panicparse) — Crash your app in style ☆`3,717`
*   [immortal/immortal (⭐833)](https://github.com/immortal/immortal) — Cross-platform supervisor ☆`832`
*   [derekparker/delve (⭐661)](https://github.com/derekparker/delve) — Delve is a debugger for the Go programming language. ☆`661`
*   [gotranspile/cxgo (⭐387)](https://github.com/gotranspile/cxgo) — Transpile C to Go ☆`388`

### UUID

*   [google/uuid (⭐6k)](https://github.com/google/uuid) — UUID generation and parsing ☆`6,017`
*   [oklog/ulid (⭐5k)](https://github.com/oklog/ulid) — ULID implementation ☆`5,012`
*   [gofrs/uuid (⭐1.8k)](https://github.com/gofrs/uuid) — UUID library for Go ☆`1,790`
*   [osamingo/indigo (⭐112)](https://github.com/osamingo/indigo) — Sonyflake-based ID generator ☆`112`
*   [sdrapkin/guid (⭐73)](https://github.com/sdrapkin/guid) — Fast cryptographically safe Guid generator for Go ☆`73`
*   [twharmon/gouid (⭐26)](https://github.com/twharmon/gouid) — Fast, dependable universally unique ids ☆`26`

## Version Control & Packages

### Git APIs

*   [google/go-github (⭐11k)](https://github.com/google/go-github) — Go library for accessing the GitHub v3 API ☆`11,168`
*   [shurcooL/githubv4 (⭐1.2k)](https://github.com/shurcooL/githubv4) — GitHub GraphQL API v4 client ☆`1,188`
*   [go-playground/webhooks (⭐1k)](https://github.com/go-playground/webhooks) — Webhook receiver for GitHub, Bitbucket, GitLab, Gogs ☆`1,029`
*   [andygrunwald/go-trending (⭐146)](https://github.com/andygrunwald/go-trending) — Access GitHub trending repositories ☆`146`
*   [andygrunwald/go-gerrit (⭐104)](https://github.com/andygrunwald/go-gerrit) — Go client/library for Gerrit Code Review ☆`104`

### Package Management

*   [anchore/syft (⭐8.5k)](https://github.com/anchore/syft) — SBOM generator for containers ☆`8,559`
*   [nao1215/gup (⭐552)](https://github.com/nao1215/gup) — gup - Update binaries installed by "go install" with goroutines. ☆`558`
*   [marwanhawari/stew (⭐335)](https://github.com/marwanhawari/stew) — An independent package manager for compiled binaries. ☆`338`
*   [chaindead/modup (⭐63)](https://github.com/chaindead/modup) — TUI for Go dependency updates ☆`62`

### Version Control

*   [go-git/go-git (⭐7.3k)](https://github.com/go-git/go-git) — Pure Go Git implementation ☆`7,276`
*   [antham/chyle (⭐159)](https://github.com/antham/chyle) — Changelog generator from Git ☆`159`
*   [gabyx/Githooks (⭐120)](https://github.com/gabyx/Githooks) — Per-repo shared Git hooks ☆`122`
*   [antham/gommit (⭐115)](https://github.com/antham/gommit) — Enforce git message commit consistency ☆`115`
*   [jfrog/froggit-go (⭐52)](https://github.com/jfrog/froggit-go) — Universal VCS client library ☆`52`
*   [kazhuravlev/git-tools (⭐30)](https://github.com/kazhuravlev/git-tools) — Useful set of tools which helps to manage git tags ☆`30`

## Web Development

### Microservices

*   [zeromicro/go-zero (⭐33k)](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`32,834`
*   [go-kit/kit (⭐28k)](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,581`
*   [go-kratos/kratos (⭐26k)](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,561`
*   [micro/go-micro (⭐23k)](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,723`
*   [smallnest/rpcx (⭐8.3k)](https://github.com/smallnest/rpcx) — Feature-rich RPC framework ☆`8,273`
*   [cloudwego/kitex (⭐7.9k)](https://github.com/cloudwego/kitex) — High-performance Go RPC framework ☆`7,897`
*   [go-dev-frame/sponge (⭐2.8k)](https://github.com/go-dev-frame/sponge) — Code generation framework for Go ☆`2,808`
*   [go-eagle/eagle (⭐2.4k)](https://github.com/go-eagle/eagle) — A Go framework for the API or Microservice ☆`2,423`
*   [unionj-cloud/go-doudou (⭐1.2k)](https://github.com/unionj-cloud/go-doudou) — OpenAPI 3 and gRPC microservices framework ☆`1,198`
*   [trpc-group/trpc-go (⭐1.1k)](https://github.com/trpc-group/trpc-go) — A pluggable, high-performance RPC framework written in golang ☆`1,131`
*   [gmsec/micro (⭐25)](https://github.com/gmsec/micro) — A Go distributed systems development framework ☆`25`

### Middlewares

*   [urfave/negroni (⭐7.5k)](https://github.com/urfave/negroni) — Idiomatic HTTP Middleware for Golang ☆`7,534`
*   [tdewolff/minify (⭐4.1k)](https://github.com/tdewolff/minify) — Go minifiers for web formats ☆`4,083`
*   [justinas/alice (⭐3.4k)](https://github.com/justinas/alice) — Painless middleware chaining for Go ☆`3,347`
*   [rs/cors (⭐2.9k)](https://github.com/rs/cors) — Go net/http configurable handler to handle CORS requests ☆`2,869`
*   [didip/tollbooth (⭐2.9k)](https://github.com/didip/tollbooth) — Simple middleware to rate-limit HTTP requests. ☆`2,855`
*   [unrolled/render (⭐2k)](https://github.com/unrolled/render) — Render JSON, XML, HTML, binary ☆`1,991`
*   [lingrino/go-fault (⭐549)](https://github.com/lingrino/go-fault) — go fault injection library ☆`550`
*   [jub0bs/cors (⭐179)](https://github.com/jub0bs/cors) — perhaps the best CORS middleware library for Go ☆`180`
*   [rookie-ninja/rk-gin (⭐51)](https://github.com/rookie-ninja/rk-gin) — Start gin microservice from YAML, plugin of rk-boot ☆`51`
*   [faabiosr/echo-middleware (⭐16)](https://github.com/faabiosr/echo-middleware) — Middlewares for Echo framework ☆`16`

### Routers

*   [gorilla/mux (⭐22k)](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,857`
*   [go-chi/chi (⭐22k)](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`21,865`
*   [gowww/router (⭐185)](https://github.com/gowww/router) — A lightning fast HTTP router ☆`185`
*   [ngamux/ngamux (⭐70)](https://github.com/ngamux/ngamux) — Simple HTTP router for Go ☆`70`
*   [bmf-san/goblin (⭐82)](https://github.com/bmf-san/goblin) — A golang http router based on trie tree. ☆`82`
*   [muir/nchi (⭐18)](https://github.com/muir/nchi) — golang http router with elegance, speed, and flexibility ☆`18`

### Template Engines

*   [a-h/templ (⭐10k)](https://github.com/a-h/templ) — A language for writing HTML user interfaces in Go. ☆`10,179`
*   [valyala/quicktemplate (⭐3.3k)](https://github.com/valyala/quicktemplate) — Fast template engine for Go ☆`3,310`
*   [johnfercher/maroto (⭐2.7k)](https://github.com/johnfercher/maroto) — Create PDFs with Bootstrap grid ☆`2,661`
*   [CloudyKit/jet (⭐1.4k)](https://github.com/CloudyKit/jet) — Jet template engine ☆`1,391`
*   [osteele/liquid (⭐343)](https://github.com/osteele/liquid) — A Liquid template engine in Go ☆`345`
*   [go-sprout/sprout (⭐209)](https://github.com/go-sprout/sprout) — Template functions for Go ☆`209`
*   [goradd/got (⭐38)](https://github.com/goradd/got) — Template engine with Go code output ☆`38`

### Web Frameworks

*   [gin-gonic/gin (⭐88k)](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`88,304`
*   [gofiber/fiber (⭐39k)](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`39,422`
*   [beego/beego (⭐32k)](https://github.com/beego/beego) — High-performance web framework ☆`32,415`
*   [labstack/echo (⭐32k)](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,245`
*   [gofr-dev/gofr (⭐16k)](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`20,509`
*   [gogf/gf (⭐13k)](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,089`
*   [cloudwego/hertz (⭐7.1k)](https://github.com/cloudwego/hertz) — High-performance HTTP framework ☆`7,136`
*   [goadesign/goa (⭐6.1k)](https://github.com/goadesign/goa) — Design-first API framework ☆`6,066`
*   [apache/dubbo-go (⭐4.9k)](https://github.com/apache/dubbo-go) — Go Implementation For Apache Dubbo . ☆`4,903`
*   [goravel/goravel (⭐4.5k)](https://github.com/goravel/goravel) — The full-featured Golang Development Framework skeleton ☆`4,473`
*   [danielgtaylor/huma (⭐3.9k)](https://github.com/danielgtaylor/huma) — Huma REST/HTTP API Framework for Golang with OpenAPI 3.1 ☆`3,906`
*   [documize/community (⭐2.4k)](https://github.com/documize/community) — Modern Confluence alternative ☆`2,379`
*   [go-sonic/sonic (⭐2.1k)](https://github.com/go-sonic/sonic) — Blogging platform in Go ☆`2,122`
*   [go-goyave/goyave (⭐1.8k)](https://github.com/go-goyave/goyave) — The enterprise REST API framework ☆`1,768`
*   [go-fuego/fuego (⭐1.7k)](https://github.com/go-fuego/fuego) — Web framework with OpenAPI 3 ☆`1,684`
*   [templui/templui (⭐1.4k)](https://github.com/templui/templui) — UI components for Templ ☆`1,493`
*   [savsgio/atreugo (⭐1.3k)](https://github.com/savsgio/atreugo) — Micro web framework on fasthttp ☆`1,301`
*   [ankorstore/yokai (⭐821)](https://github.com/ankorstore/yokai) — Modular framework for Go apps ☆`824`
*   [indeedeng/iwf (⭐631)](https://github.com/indeedeng/iwf) — Workflow-as-code orchestration ☆`634`
*   [i-love-flamingo/flamingo-commerce (⭐588)](https://github.com/i-love-flamingo/flamingo-commerce) — Flexible Go web framework ☆`590`
*   [i-love-flamingo/flamingo (⭐557)](https://github.com/i-love-flamingo/flamingo) — Flexible Go web framework ☆`558`
*   [rookie-ninja/rk-boot (⭐576)](https://github.com/rookie-ninja/rk-boot) — Enterprise microservice framework ☆`574`
*   [fastschema/fastschema (⭐540)](https://github.com/fastschema/fastschema) — All-in-One Backend as a Service with Headless CMS Power ☆`543`
*   [uadmin/uadmin (⭐355)](https://github.com/uadmin/uadmin) — The web framework for Golang ☆`355`
*   [xxjwxc/ginrpc (⭐302)](https://github.com/xxjwxc/ginrpc) — gin auto binding, grpc and annotated route ☆`301`
*   [hidevopsio/hiboot (⭐180)](https://github.com/hidevopsio/hiboot) — High-performance CLI and web apps ☆`179`
*   [beatlabs/patron (⭐126)](https://github.com/beatlabs/patron) — Cloud-native microservice framework ☆`126`
*   [gone-io/gone (⭐131)](https://github.com/gone-io/gone) — Lightweight DI framework ☆`131`
*   [claygod/microservice (⭐122)](https://github.com/claygod/microservice) — Simple microservice framework ☆`122`
*   [gookit/rux (⭐99)](https://github.com/gookit/rux) — Simple and fast web framework ☆`98`
*   [yaitoo/xun (⭐91)](https://github.com/yaitoo/xun) — Web framework on html/template ☆`91`
*   [go-spring/spring-core (⭐76)](https://github.com/go-spring/spring-core) — Spring-inspired framework for Go ☆`78`
*   [napsy/go-css (⭐91)](https://github.com/napsy/go-css) — A very simple CSS parser, written in Go ☆`92`
*   [abemedia/go-don (⭐58)](https://github.com/abemedia/go-don) — API framework written in Golang. ☆`58`
*   [JiveGroup/gFly (⭐48)](https://github.com/JiveGroup/gFly) — Laravel inspired web framework written in Go ☆`48`
*   [clubpay/ronykit (⭐36)](https://github.com/clubpay/ronykit) — API Framework supporting REST and RPC. ☆`36`
*   [SaiNageswarS/go-api-boot (⭐35)](https://github.com/SaiNageswarS/go-api-boot) — gRPC + HTTP/2 production framework ☆`35`

### WebAssembly

*   [tinygo-org/tinygo (⭐17k)](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,240`
*   [agnivade/wasmbrowsertest (⭐206)](https://github.com/agnivade/wasmbrowsertest) — Run WASM tests inside your browser ☆`206`
*   [extism/go-sdk (⭐168)](https://github.com/extism/go-sdk) — Extism Go SDK - easily run WebAssembly modules in your Go applications ☆`169`

## Workflow & Scheduling

### Job Scheduler

*   [go-co-op/gocron (⭐7k)](https://github.com/go-co-op/gocron) — Easy and fluent Go cron scheduling ☆`6,977`
*   [hatchet-dev/hatchet (⭐6.7k)](https://github.com/hatchet-dev/hatchet) — Run Background Tasks at Scale ☆`6,756`
*   [reugn/go-quartz (⭐2k)](https://github.com/reugn/go-quartz) — Minimalist and zero-dependency scheduling library for Go ☆`2,011`
*   [adhocore/gronx (⭐499)](https://github.com/adhocore/gronx) — Lightweight cron expression parser ☆`500`
*   [fieldryand/goflow (⭐473)](https://github.com/fieldryand/goflow) — Simple but powerful DAG scheduler and dashboard ☆`475`
*   [madflojo/tasks (⭐323)](https://github.com/madflojo/tasks) — In-process task scheduler ☆`324`
*   [bart6114/cheek (⭐194)](https://github.com/bart6114/cheek) — cheek: a pico-sized declarative job scheduler ☆`195`
*   [onatm/clockwerk (⭐182)](https://github.com/onatm/clockwerk) — Job Scheduling Library ☆`182`
*   [deepaksinghvi/cdule (⭐60)](https://github.com/deepaksinghvi/cdule) — Golang job scheduler ☆`60`
*   [pardnchiu/go-scheduler (⭐32)](https://github.com/pardnchiu/go-scheduler) — Scheduler with standard cron and task dependencies ☆`32`
*   [romshark/sched (⭐30)](https://github.com/romshark/sched) — A job scheduler for Go with the ability to fast-forward time. ☆`30`

### Workflow Frameworks

*   [redpanda-data/connect (⭐8.6k)](https://github.com/redpanda-data/connect) — Fancy stream processing made operationally mundane ☆`8,614`
*   [dagu-org/dagu (⭐3.2k)](https://github.com/dagu-org/dagu) — Workflow engine with Web UI ☆`3,205`
*   [jf-tech/omniparser (⭐1.1k)](https://github.com/jf-tech/omniparser) — ETL streaming parser for Go ☆`1,079`
*   [noneback/go-taskflow (⭐617)](https://github.com/noneback/go-taskflow) — Task-parallel programming library ☆`620`
*   [cadence-workflow/cadence-go-client (⭐374)](https://github.com/cadence-workflow/cadence-go-client) — Cadence workflow client for Go ☆`374`
*   [luno/workflow (⭐222)](https://github.com/luno/workflow) — Type-safe workflow orchestration ☆`224`
*   [rhosocial/go-dag (⭐37)](https://github.com/rhosocial/go-dag) — DAG-based workflow framework ☆`37`

***

## 🏆 Top 100 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1.  [ollama/ollama (⭐165k)](https://github.com/ollama/ollama) — Run LLMs locally ☆`166,077`
2.  [kubernetes/kubernetes (⭐121k)](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`121,331`
3.  [gin-gonic/gin (⭐88k)](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`88,304`
4.  [junegunn/fzf (⭐79k)](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`78,900`
5.  [moby/moby (⭐72k)](https://github.com/moby/moby) — Container ecosystem components ☆`71,561`
6.  [caddyserver/caddy (⭐71k)](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`71,072`
7.  [prometheus/prometheus (⭐63k)](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`63,287`
8.  [traefik/traefik (⭐62k)](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`62,349`
9.  [pocketbase/pocketbase (⭐57k)](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`57,070`
10. [golang-standards/project-layout (⭐56k)](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`55,624`
11. [go-gitea/gitea (⭐54k)](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`54,466`
12. [wagoodman/dive (⭐54k)](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`53,634`
13. [etcd-io/etcd (⭐52k)](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`51,698`
14. [ethereum/go-ethereum (⭐51k)](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`50,951`
15. [mudler/LocalAI (⭐43k)](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`44,336`
16. [spf13/cobra (⭐43k)](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`43,518`
17. [milvus-io/milvus (⭐43k)](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`43,458`
18. [charmbracelet/bubbletea (⭐41k)](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`40,936`
19. [pingcap/tidb (⭐40k)](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`39,924`
20. [go-gorm/gorm (⭐40k)](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,647`
21. [gofiber/fiber (⭐39k)](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`39,422`
22. [schollz/croc (⭐34k)](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`34,462`
23. [harness/harness (⭐34k)](https://github.com/harness/harness) — End-to-end developer platform ☆`34,023`
24. [zeromicro/go-zero (⭐33k)](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`32,834`
25. [restic/restic (⭐33k)](https://github.com/restic/restic) — Fast, secure backup program ☆`32,817`
26. [k3s-io/k3s (⭐32k)](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`32,557`
27. [beego/beego (⭐32k)](https://github.com/beego/beego) — High-performance web framework ☆`32,415`
28. [labstack/echo (⭐32k)](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,245`
29. [cockroachdb/cockroach (⭐32k)](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`31,995`
30. [kubernetes/minikube (⭐32k)](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,623`
31. [influxdata/influxdb (⭐31k)](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,376`
32. [seaweedfs/seaweedfs (⭐31k)](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`31,140`
33. [grafana/k6 (⭐30k)](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`30,202`
34. [spf13/viper (⭐30k)](https://github.com/spf13/viper) — Go configuration with fangs ☆`30,174`
35. [fyne-io/fyne (⭐28k)](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`28,045`
36. [go-kit/kit (⭐28k)](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,581`
37. [stretchr/testify (⭐26k)](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`25,903`
38. [sirupsen/logrus (⭐26k)](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,709`
39. [go-kratos/kratos (⭐26k)](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,561`
40. [gocolly/colly (⭐25k)](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,179`
41. [tsenart/vegeta (⭐25k)](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`24,961`
42. [uber-go/zap (⭐24k)](https://github.com/uber-go/zap) — Fast structured logging ☆`24,388`
43. [urfave/cli (⭐24k)](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`23,948`
44. [valyala/fasthttp (⭐23k)](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,305`
45. [air-verse/air (⭐23k)](https://github.com/air-verse/air) — Live reload for Go apps ☆`23,207`
46. [grpc/grpc-go (⭐23k)](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,853`
47. [micro/go-micro (⭐23k)](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,723`
48. [jaegertracing/jaeger (⭐23k)](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`22,612`
49. [redis/go-redis (⭐22k)](https://github.com/redis/go-redis) — Redis Go client ☆`22,000`
50. [go-chi/chi (⭐22k)](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`21,865`
51. [gorilla/mux (⭐22k)](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,857`
52. [FiloSottile/age (⭐22k)](https://github.com/FiloSottile/age) — Simple encryption tool ☆`21,747`
53. [dolthub/dolt (⭐21k)](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`21,673`
54. [dgraph-io/dgraph (⭐22k)](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,647`
55. [samber/lo (⭐21k)](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`21,147`
56. [vitessio/vitess (⭐21k)](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`20,862`
57. [gofr-dev/gofr (⭐16k)](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`20,509`
58. [qax-os/excelize (⭐20k)](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,423`
59. [antonmedv/fx (⭐20k)](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,356`
60. [apache/casbin (⭐20k)](https://github.com/apache/casbin) — Authorization library for Go ☆`19,950`
61. [go-playground/validator (⭐20k)](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`19,829`
62. [nats-io/nats-server (⭐19k)](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`19,407`
63. [golangci/golangci-lint (⭐19k)](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`18,710`
64. [golang-migrate/migrate (⭐18k)](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,272`
65. [jmoiron/sqlx (⭐18k)](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,542`
66. [rqlite/rqlite (⭐17k)](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,372`
67. [tinygo-org/tinygo (⭐17k)](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,240`
68. [sqlc-dev/sqlc (⭐17k)](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`17,208`
69. [ent/ent (⭐17k)](https://github.com/ent/ent) — An entity framework for Go ☆`16,989`
70. [ipfs/kubo (⭐17k)](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`16,972`
71. [VictoriaMetrics/VictoriaMetrics (⭐17k)](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`16,596`
72. [keploy/keploy (⭐16k)](https://github.com/keploy/keploy) — API testing with auto mocks ☆`16,571`
73. [fatih/vim-go (⭐16k)](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,235`
74. [pion/webrtc (⭐16k)](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,152`
75. [goreleaser/goreleaser (⭐16k)](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,673`
76. [hashicorp/packer (⭐16k)](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,635`
77. [dgraph-io/badger (⭐16k)](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,528`
78. [tidwall/gjson (⭐15k)](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,470`
79. [go-sql-driver/mysql (⭐15k)](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,388`
80. [go-task/task (⭐15k)](https://github.com/go-task/task) — Fast cross-platform build tool inspired by Make ☆`15,182`
81. [kubernetes-sigs/kind (⭐15k)](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,114`
82. [PuerkitoBio/goquery (⭐15k)](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,923`
83. [panjf2000/ants (⭐14k)](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,370`
84. [webview/webview (⭐14k)](https://github.com/webview/webview) — Tiny webview library for Go ☆`13,971`
85. [bytebase/bytebase (⭐14k)](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`13,850`
86. [cloudflare/cloudflared (⭐14k)](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`13,576`
87. [jackc/pgx (⭐14k)](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`13,553`
88. [gizak/termui (⭐14k)](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,522`
89. [juicedata/juicefs (⭐13k)](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`13,356`
90. [golang/groupcache (⭐13k)](https://github.com/golang/groupcache) — Distributed cache library ☆`13,340`
91. [gopherjs/gopherjs (⭐13k)](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,132`
92. [gogf/gf (⭐13k)](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,089`
93. [hajimehoshi/ebiten (⭐13k)](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`13,061`
94. [hibiken/asynq (⭐13k)](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`13,051`
95. [chromedp/chromedp (⭐13k)](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`12,868`
96. [IBM/sarama (⭐12k)](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,454`
97. [rs/zerolog (⭐12k)](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,290`
98. [Shopify/toxiproxy (⭐12k)](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`11,922`
99. [kubeshark/kubeshark (⭐12k)](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`11,834`
100.    [drakkan/sftpgo (⭐12k)](https://github.com/drakkan/sftpgo) — Full-featured SFTP/FTP/HTTP server ☆`11,815`

## Gophers

*   [MariaLetta/free-gophers-pack (⭐3.9k)](https://github.com/MariaLetta/free-gophers-pack) — This pack of 100+ gopher pictures and elements
*   [keygx/Go-gopher-Vector (⭐75)](https://github.com/keygx/Go-gopher-Vector) — Go gopher Vector Data (.ai, .svg)
*   [ashleymcnamara/gophers (⭐3.1k)](https://github.com/ashleymcnamara/gophers) — Gopher Artwork by Ashley McNamara
*   [sillecelik/go-gopher (⭐161)](https://github.com/sillecelik/go-gopher) — The Go Gopher Amigurumi Pattern
*   [GolangUA/gopher-logos (⭐140)](https://github.com/GolangUA/gopher-logos) — adorable gopher logos
*   [egonelbre/gophers (⭐3.8k)](https://github.com/egonelbre/gophers) — gophers artwork
*   [scraly/gophers (⭐36)](https://github.com/scraly/gophers) — Gopher artwork (Golang mascot)

## Contributing

Please see [CONTRIBUTING](https://github.com/abordage/awesome-go/blob/main/README.md/.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request — contributions are welcome!

## Credits

*   [avelino/awesome-go (⭐167k)](https://github.com/avelino/awesome-go)
*   [All Contributors (⭐3)](https://github.com/abordage/awesome-go/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](https://github.com/abordage/awesome-go/blob/main/README.md/LICENSE) for more information.

