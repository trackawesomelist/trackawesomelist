# Awesome Go Overview

Structured collection of Go frameworks, libraries, tools, and resources. Automatically maintained and up-to-date with metadata, filtering, and comprehensive categorization.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/abordage/awesome-go/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 abordage/awesome-go](https://github.com/abordage/awesome-go) · ⭐ 2 · 🏷️ Programming Languages

[ [Daily](/content/abordage/awesome-go/README.md) / [Weekly](/content/abordage/awesome-go/week/README.md) / Overview ]

---

# Awesome Go

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-go?label=last%20update)](https://github.com/abordage/awesome-go/blob/main/README.md/README.md)
![Repositories](https://img.shields.io/badge/repositories-1,220-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-4,932,689-gold)
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

*   [sashabaranov/go-openai (⭐11k)](https://github.com/sashabaranov/go-openai) — OpenAI API client for Go ☆`10,552`
*   [otiai10/openaigo (⭐299)](https://github.com/otiai10/openaigo) — OpenAI GPT client library ☆`299`
*   [wit-ai/wit-go (⭐170)](https://github.com/wit-ai/wit-go) — Go client for wit.ai HTTP API ☆`170`

### Artificial Intelligence

*   [ollama/ollama (⭐162k)](https://github.com/ollama/ollama) — Run LLMs locally ☆`162,893`
*   [mudler/LocalAI (⭐43k)](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`42,891`
*   [tmc/langchaingo (⭐8.6k)](https://github.com/tmc/langchaingo) — LangChain for Go, the easiest way to write LLM-based programs in Go ☆`8,670`
*   [maximhq/bifrost (⭐2.1k)](https://github.com/maximhq/bifrost) — Fastest LLM gateway for Go ☆`2,443`
*   [philippgille/chromem-go (⭐850)](https://github.com/philippgille/chromem-go) — Embeddable vector database for Go ☆`864`
*   [universal-tool-calling-protocol/go-utcp (⭐97)](https://github.com/universal-tool-calling-protocol/go-utcp) — Official Go implementation of the UTCP ☆`99`
*   [presbrey/ollamafarm (⭐94)](https://github.com/presbrey/ollamafarm) — Manage multiple Ollama instances ☆`95`

### Machine Learning

*   [gorgonia/gorgonia (⭐5.9k)](https://github.com/gorgonia/gorgonia) — Machine learning library for Go ☆`5,907`
*   [otiai10/gosseract (⭐3.1k)](https://github.com/otiai10/gosseract) — OCR using Tesseract in Go ☆`3,069`
*   [galeone/tfgo (⭐2.5k)](https://github.com/galeone/tfgo) — Tensorflow + Go, the gopher way ☆`2,493`
*   [gomlx/gomlx (⭐1.3k)](https://github.com/gomlx/gomlx) — GoMLX: An Accelerated Machine Learning Framework For Go ☆`1,313`
*   [jbrukh/bayesian (⭐809)](https://github.com/jbrukh/bayesian) — Naive Bayesian Classification for Golang. ☆`810`
*   [knights-analytics/hugot (⭐560)](https://github.com/knights-analytics/hugot) — Onnx transformer pipelines in Golang ☆`565`
*   [patrikeh/go-deep (⭐559)](https://github.com/patrikeh/go-deep) — Artificial Neural Network ☆`559`
*   [c-bata/goptuna (⭐275)](https://github.com/c-bata/goptuna) — A hyperparameter optimization framework, inspired by Optuna. ☆`276`

## Audio & Video

### Audio

*   [ebitengine/oto (⭐1.9k)](https://github.com/ebitengine/oto) — A low-level library to play sound on multiple platforms ☆`1,863`
*   [gordonklaus/portaudio (⭐825)](https://github.com/gordonklaus/portaudio) — Go bindings for the PortAudio audio I/O library ☆`826`
*   [DylanMeeus/GoAudio (⭐404)](https://github.com/DylanMeeus/GoAudio) — Go tools for audio processing & creation ☆`405`
*   [gen2brain/malgo (⭐385)](https://github.com/gen2brain/malgo) — Mini audio library ☆`387`
*   [mewkiz/flac (⭐350)](https://github.com/mewkiz/flac) — Package flac provides access to FLAC (Free Lossless Audio Codec) streams. ☆`350`
*   [tosone/minimp3 (⭐133)](https://github.com/tosone/minimp3) — Decode mp3 ☆`133`

### Images

*   [hybridgroup/gocv (⭐7.4k)](https://github.com/hybridgroup/gocv) — Computer vision with OpenCV 4 ☆`7,382`
*   [anthonynsimon/bild (⭐4.2k)](https://github.com/anthonynsimon/bild) — Image processing algorithms in pure Go ☆`4,174`
*   [cshum/imagor (⭐3.9k)](https://github.com/cshum/imagor) — Fast, secure image processing server and Go library, using libvips ☆`3,897`
*   [thoas/picfit (⭐2.3k)](https://github.com/thoas/picfit) — An image resizing server written in Go ☆`2,326`
*   [gographics/imagick (⭐1.9k)](https://github.com/gographics/imagick) — Go binding to ImageMagick's MagickWand C API ☆`1,863`
*   [tdewolff/canvas (⭐1.8k)](https://github.com/tdewolff/canvas) — Vector graphics in Go ☆`1,780`
*   [davidbyttow/govips (⭐1.5k)](https://github.com/davidbyttow/govips) — A lightning fast image processing and resizing library for Go ☆`1,525`
*   [yeqown/go-qrcode (⭐809)](https://github.com/yeqown/go-qrcode) — Customizable QR code generator ☆`810`
*   [HugoSmits86/nativewebp (⭐388)](https://github.com/HugoSmits86/nativewebp) — Native webp encoder for Go ☆`388`
*   [auyer/steganography (⭐353)](https://github.com/auyer/steganography) — LSB steganography in pure Go ☆`353`
*   [kolesa-team/go-webp (⭐296)](https://github.com/kolesa-team/go-webp) — Simple and fast webp library for golang ☆`300`
*   [Pixboost/transformimgs (⭐286)](https://github.com/Pixboost/transformimgs) — Open source image CDN. ☆`288`
*   [qmuntal/gltf (⭐275)](https://github.com/qmuntal/gltf) — Go library for encoding glTF 2.0 files ☆`275`
*   [gojek/darkroom (⭐236)](https://github.com/gojek/darkroom) — Image processing engine and proxy service ☆`236`
*   [ungerik/go-cairo (⭐151)](https://github.com/ungerik/go-cairo) — Go binding for the cairo graphics library ☆`151`
*   [aofei/cameron (⭐130)](https://github.com/aofei/cameron) — An avatar generator for Go. ☆`130`
*   [piglig/go-qr (⭐47)](https://github.com/piglig/go-qr) — A native, high-quality and minimalistic QR code generator ☆`47`

### Video

*   [asticode/go-astisub (⭐682)](https://github.com/asticode/go-astisub) — Manipulate subtitles in Go ☆`684`
*   [asticode/go-astiav (⭐672)](https://github.com/asticode/go-astiav) — Golang ffmpeg and libav C bindings ☆`680`
*   [asticode/go-astits (⭐604)](https://github.com/asticode/go-astits) — Demux and mux MPEG Transport Streams (.ts) natively in GO ☆`609`
*   [Eyevinn/mp4ff (⭐593)](https://github.com/Eyevinn/mp4ff) — MP4/ISOBMFF tools and library ☆`596`
*   [adrg/libvlc-go (⭐505)](https://github.com/adrg/libvlc-go) — Go bindings for libVLC ☆`505`
*   [korandiz/v4l (⭐90)](https://github.com/korandiz/v4l) — Facade to the Video4Linux video capture interface. ☆`90`
*   [Eyevinn/hls-m3u8 (⭐48)](https://github.com/Eyevinn/hls-m3u8) — HLS m3u8 library in Go ☆`49`
*   [unki2aut/go-mpd (⭐33)](https://github.com/unki2aut/go-mpd) — MPEG-DASH manifest library ☆`32`
*   [jonoton/scout (⭐26)](https://github.com/jonoton/scout) — Video surveillance with motion detection ☆`26`

## Auth

### Authentication

*   [golang-jwt/jwt (⭐8.9k)](https://github.com/golang-jwt/jwt) — Go implementation of JSON Web Tokens (JWT). ☆`8,906`
*   [markbates/goth (⭐6.4k)](https://github.com/markbates/goth) — Multi-provider authentication ☆`6,452`
*   [golang/oauth2 (⭐5.8k)](https://github.com/golang/oauth2) — Go OAuth2 ☆`5,813`
*   [aarondl/authboss (⭐4.1k)](https://github.com/aarondl/authboss) — The boss of http auth. ☆`4,152`
*   [alexedwards/scs (⭐2.5k)](https://github.com/alexedwards/scs) — HTTP Session Management for Go ☆`2,521`
*   [lestrrat-go/jwx (⭐2.3k)](https://github.com/lestrrat-go/jwx) — Complete JWx implementation ☆`2,321`
*   [openshift/osin (⭐1.9k)](https://github.com/openshift/osin) — Golang OAuth2 server library ☆`1,934`
*   [dghubble/gologin (⭐1.9k)](https://github.com/dghubble/gologin) — Go login handlers for authentication providers (OAuth1, OAuth2) ☆`1,945`
*   [zitadel/oidc (⭐1.8k)](https://github.com/zitadel/oidc) — OpenID Connect client and server ☆`1,762`
*   [cristalhq/jwt (⭐687)](https://github.com/cristalhq/jwt) — Safe, simple and fast JSON Web Tokens for Go ☆`688`
*   [shaj13/go-guardian (⭐607)](https://github.com/shaj13/go-guardian) — Authentication library for Go ☆`608`
*   [go-jose/go-jose (⭐479)](https://github.com/go-jose/go-jose) — An implementation of JOSE standards (JWE, JWS, JWT) in Go ☆`481`
*   [abraithwaite/jeff (⭐270)](https://github.com/abraithwaite/jeff) — Jeff provides the simplest way to manage web sessions in Go. ☆`270`
*   [Kwynto/gosession (⭐258)](https://github.com/Kwynto/gosession) — Quick session for net/http ☆`258`
*   [leodip/goiabada (⭐183)](https://github.com/leodip/goiabada) — Goiabada is an OAuth2 / OpenID Connect server written in Go. ☆`184`
*   [jellydator/sessionup (⭐130)](https://github.com/jellydator/sessionup) — Straightforward HTTP session management ☆`130`
*   [brianvoe/sjwt (⭐122)](https://github.com/brianvoe/sjwt) — Simple JWT Golang ☆`122`
*   [essentialkaos/branca (⭐95)](https://github.com/essentialkaos/branca) — Encrypted API tokens ☆`95`
*   [icza/session (⭐118)](https://github.com/icza/session) — Session management for web servers ☆`118`
*   [mengzhuo/cookiestxt (⭐22)](https://github.com/mengzhuo/cookiestxt) — cookiestxt implement parser of cookies txt format ☆`22`

### Authorization

*   [casbin/casbin (⭐20k)](https://github.com/casbin/casbin) — Authorization library for Go ☆`19,846`
*   [ory/keto (⭐5.3k)](https://github.com/ory/keto) — Customizable permission server ☆`5,270`
*   [openfga/openfga (⭐4.7k)](https://github.com/openfga/openfga) — Fine-grained authorization server ☆`4,780`
*   [cerbos/cerbos (⭐4.2k)](https://github.com/cerbos/cerbos) — Open core authorization layer ☆`4,222`

## Bots & Chat

### Bot Frameworks

*   [tucnak/telebot (⭐4.6k)](https://github.com/tucnak/telebot) — Telebot is a Telegram bot framework in Go. ☆`4,564`
*   [go-telegram/bot (⭐1.6k)](https://github.com/go-telegram/bot) — Telegram Bot API Go framework ☆`1,592`
*   [mymmrac/telego (⭐926)](https://github.com/mymmrac/telego) — Telegram Bot API library for Go ☆`949`
*   [diamondburned/arikawa (⭐569)](https://github.com/diamondburned/arikawa) — A Golang library and framework for the Discord API. ☆`573`
*   [NicoNex/echotron (⭐416)](https://github.com/NicoNex/echotron) — An elegant and concurrent library for the Telegram bot API in Go. ☆`416`
*   [gempir/go-twitch-irc (⭐390)](https://github.com/gempir/go-twitch-irc) — go irc client for twitch.tv ☆`393`
*   [innogames/slack-bot (⭐206)](https://github.com/innogames/slack-bot) — Slack bot for Jenkins, Jira, PRs ☆`206`
*   [mr-linch/go-tg (⭐124)](https://github.com/mr-linch/go-tg) — Telegram Bot API client ☆`124`
*   [slack-io/slacker (⭐60)](https://github.com/slack-io/slacker) — Slack Bot Framework ☆`60`
*   [onrik/micha (⭐31)](https://github.com/onrik/micha) — Client lib for Telegram bot api ☆`31`

### Chat APIs

*   [bwmarrin/discordgo (⭐5.8k)](https://github.com/bwmarrin/discordgo) — (Golang) Go bindings for Discord ☆`5,785`
*   [slack-go/slack (⭐4.9k)](https://github.com/slack-go/slack) — Slack API in Go ☆`4,898`
*   [huandu/facebook (⭐1.4k)](https://github.com/huandu/facebook) — A Facebook Graph API SDK For Go. ☆`1,443`
*   [chyroc/lark (⭐461)](https://github.com/chyroc/lark) — Lark/Feishu Open API SDK ☆`462`
*   [go-lark/lark (⭐238)](https://github.com/go-lark/lark) — Feishu/Lark SDK for Go ☆`238`
*   [switchupcb/disgo (⭐109)](https://github.com/switchupcb/disgo) — Next-gen Discord API library ☆`110`

## CLI & Terminal

### Advanced Console UIs

*   [charmbracelet/bubbletea (⭐39k)](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`39,583`
*   [antonmedv/fx (⭐20k)](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,275`
*   [gizak/termui (⭐14k)](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,518`
*   [charmbracelet/lipgloss (⭐10k)](https://github.com/charmbracelet/lipgloss) — Style definitions for nice terminal layouts ☆`10,586`
*   [jroimartin/gocui (⭐11k)](https://github.com/jroimartin/gocui) — Minimalist Go package aimed at creating Console User Interfaces. ☆`10,514`
*   [charmbracelet/bubbles (⭐7.7k)](https://github.com/charmbracelet/bubbles) — TUI components for Bubble Tea ☆`7,787`
*   [c-bata/go-prompt (⭐5.5k)](https://github.com/c-bata/go-prompt) — Interactive prompts for Go ☆`5,465`
*   [pterm/pterm (⭐5.4k)](https://github.com/pterm/pterm) — Modern terminal output library ☆`5,364`
*   [schollz/progressbar (⭐4.6k)](https://github.com/schollz/progressbar) — Thread-safe progress bar ☆`4,641`
*   [mum4k/termdash (⭐3k)](https://github.com/mum4k/termdash) — Terminal-based dashboard ☆`2,977`
*   [guptarohit/asciigraph (⭐3k)](https://github.com/guptarohit/asciigraph) — ASCII line graphs in terminal ☆`2,954`
*   [briandowns/spinner (⭐2.5k)](https://github.com/briandowns/spinner) — Terminal spinner indicators ☆`2,510`
*   [vbauerster/mpb (⭐2.5k)](https://github.com/vbauerster/mpb) — Multi progress bar ☆`2,476`
*   [muesli/termenv (⭐2k)](https://github.com/muesli/termenv) — Terminal color support ☆`1,968`
*   [gookit/color (⭐1.6k)](https://github.com/gookit/color) — Terminal color rendering ☆`1,572`
*   [logrusorgru/aurora (⭐1.5k)](https://github.com/logrusorgru/aurora) — ANSI colors for Printf ☆`1,476`
*   [mattn/go-isatty (⭐887)](https://github.com/mattn/go-isatty) — Check if terminal is TTY ☆`889`
*   [mattn/go-colorable (⭐803)](https://github.com/mattn/go-colorable) — Colorable writer for Windows ☆`804`
*   [box-cli-maker/box-cli-maker (⭐601)](https://github.com/box-cli-maker/box-cli-maker) — Render highly customizable boxes in the terminal ☆`612`
*   [Evertras/bubble-table (⭐548)](https://github.com/Evertras/bubble-table) — Table component for Bubble Tea ☆`553`
*   [DMcP89/tinycare-tui (⭐16)](https://github.com/DMcP89/tinycare-tui) — TUI application written in GO inspired by tiny-care-terminal ☆`16`

### Standard CLI

*   [spf13/cobra (⭐43k)](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`43,212`
*   [urfave/cli (⭐24k)](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`23,893`
*   [elves/elvish (⭐6.2k)](https://github.com/elves/elvish) — Scripting shell for Go ☆`6,237`
*   [alecthomas/kingpin (⭐3.6k)](https://github.com/alecthomas/kingpin) — Command-line parser ☆`3,560`
*   [dnote/dnote (⭐3k)](https://github.com/dnote/dnote) — Command-line notebook ☆`3,007`
*   [spf13/pflag (⭐2.7k)](https://github.com/spf13/pflag) — POSIX/GNU-style flags ☆`2,707`
*   [jessevdk/go-flags (⭐2.7k)](https://github.com/jessevdk/go-flags) — Command-line option parser ☆`2,688`
*   [alexflint/go-arg (⭐2.2k)](https://github.com/alexflint/go-arg) — Struct-based argument parsing ☆`2,228`
*   [carapace-sh/carapace-bin (⭐1.7k)](https://github.com/carapace-sh/carapace-bin) — Multi-shell completion binary ☆`1,696`
*   [nanovms/ops (⭐1.5k)](https://github.com/nanovms/ops) — Build and run unikernels ☆`1,465`
*   [carapace-sh/carapace (⭐1.1k)](https://github.com/carapace-sh/carapace) — Multi-shell completion library ☆`1,160`
*   [posener/complete (⭐951)](https://github.com/posener/complete) — Bash completion in Go ☆`951`
*   [ddddddO/gtree (⭐326)](https://github.com/ddddddO/gtree) — Generate ASCII tree from Markdown ☆`326`
*   [leaanthony/clir (⭐197)](https://github.com/leaanthony/clir) — Simple CLI library ☆`197`
*   [urfave/sflags (⭐167)](https://github.com/urfave/sflags) — Generate flags from structs ☆`167`
*   [hedzr/cmdr (⭐142)](https://github.com/hedzr/cmdr) — POSIX-compliant CLI parser ☆`141`
*   [reeflective/readline (⭐132)](https://github.com/reeflective/readline) — Shell library with inputrc ☆`133`
*   [cristalhq/acmd (⭐137)](https://github.com/cristalhq/acmd) — Simple CLI package ☆`137`
*   [reeflective/console (⭐101)](https://github.com/reeflective/console) — Console library for Cobra ☆`104`
*   [codingconcepts/env (⭐126)](https://github.com/codingconcepts/env) — Tag-based environment configuration for structs ☆`126`
*   [dixonwille/wlog (⭐67)](https://github.com/dixonwille/wlog) — Cross-platform logging ☆`67`
*   [jxskiss/mcli (⭐42)](https://github.com/jxskiss/mcli) — Minimal but powerful CLI ☆`43`
*   [DavidGamba/go-getoptions (⭐61)](https://github.com/DavidGamba/go-getoptions) — Command line option parser with completion ☆`61`
*   [nyaosorg/go-readline-ny (⭐32)](https://github.com/nyaosorg/go-readline-ny) — Readline for Go ☆`32`
*   [carapace-sh/carapace-spec (⭐29)](https://github.com/carapace-sh/carapace-spec) — Multi-shell completion library ☆`29`
*   [sgreben/flagvar (⭐48)](https://github.com/sgreben/flagvar) — CLI argument types for flag ☆`48`
*   [hashicorp/cli (⭐35)](https://github.com/hashicorp/cli) — CLI library for Go ☆`35`

## Concurrency

### Actor Model

*   [asynkron/protoactor-go (⭐5.4k)](https://github.com/asynkron/protoactor-go) — Ultra fast distributed actors for Go ☆`5,419`
*   [ergo-services/ergo (⭐4.4k)](https://github.com/ergo-services/ergo) — Actor framework with network transparency ☆`4,432`
*   [anthdm/hollywood (⭐2.2k)](https://github.com/anthdm/hollywood) — Blazingly fast and light-weight Actor engine written in Golang ☆`2,177`
*   [Tochemey/goakt (⭐320)](https://github.com/Tochemey/goakt) — Distributed actor framework ☆`322`

### Goroutines

*   [panjf2000/ants (⭐14k)](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,332`
*   [benmanns/goworker (⭐2.8k)](https://github.com/benmanns/goworker) — Resque-compatible background worker ☆`2,847`
*   [alitto/pond (⭐2.1k)](https://github.com/alitto/pond) — High-performance worker pool ☆`2,079`
*   [destel/rill (⭐1.8k)](https://github.com/destel/rill) — Channel-based concurrency toolkit ☆`1,803`
*   [xxjwxc/gowp (⭐522)](https://github.com/xxjwxc/gowp) — Goroutine worker pool ☆`522`
*   [earthboundkid/flowmatic (⭐397)](https://github.com/earthboundkid/flowmatic) — Structured concurrency ☆`397`
*   [reugn/async (⭐295)](https://github.com/reugn/async) — Async computation package ☆`296`
*   [vladopajic/go-actor (⭐278)](https://github.com/vladopajic/go-actor) — Actor model library ☆`279`
*   [timandy/routine (⭐287)](https://github.com/timandy/routine) — ThreadLocal for Go ☆`287`
*   [mborders/artifex (⭐214)](https://github.com/mborders/artifex) — In-memory job queue ☆`214`

### Stream Processing

*   [reugn/go-streams (⭐2.2k)](https://github.com/reugn/go-streams) — Stream processing library ☆`2,157`
*   [Breeze0806/go-etl (⭐182)](https://github.com/Breeze0806/go-etl) — ETL toolset for Go ☆`184`
*   [fulminate-io/machine (⭐165)](https://github.com/fulminate-io/machine) — Machine is a workflow/pipeline library for processing data ☆`165`
*   [mariomac/gostream (⭐171)](https://github.com/mariomac/gostream) — Java Streams port for Go ☆`170`
*   [rulego/streamsql (⭐53)](https://github.com/rulego/streamsql) — SQL-based stream processing for IoT ☆`54`

## Configuration

*   [spf13/viper (⭐30k)](https://github.com/spf13/viper) — Go configuration with fangs ☆`30,063`
*   [caarlos0/env (⭐6k)](https://github.com/caarlos0/env) — Parse environment variables to structs ☆`5,998`
*   [knadh/koanf (⭐3.8k)](https://github.com/knadh/koanf) — Lightweight config management ☆`3,864`
*   [alecthomas/kong (⭐3k)](https://github.com/alecthomas/kong) — Command-line parser for Go ☆`2,974`
*   [ilyakaznacheev/cleanenv (⭐2k)](https://github.com/ilyakaznacheev/cleanenv) — Minimalistic environment config reader ☆`2,057`
*   [adrg/xdg (⭐950)](https://github.com/adrg/xdg) — XDG Base Directory implementation ☆`954`
*   [cristalhq/aconfig (⭐622)](https://github.com/cristalhq/aconfig) — Simple config loader ☆`623`
*   [gookit/config (⭐578)](https://github.com/gookit/config) — Config management with formats ☆`578`
*   [kkyr/fig (⭐385)](https://github.com/kkyr/fig) — Minimalist config library ☆`385`
*   [nil-go/konf (⭐362)](https://github.com/nil-go/konf) — Simplest config loader for Go ☆`362`
*   [hjson/hjson-go (⭐347)](https://github.com/hjson/hjson-go) — Hjson for Go ☆`347`
*   [vrischmann/envconfig (⭐250)](https://github.com/vrischmann/envconfig) — Env config library ☆`250`
*   [chaindead/zerocfg (⭐199)](https://github.com/chaindead/zerocfg) — Zero-effort config management ☆`199`
*   [beatlabs/harvester (⭐134)](https://github.com/beatlabs/harvester) — Watch and notify config changes ☆`134`
*   [BoRuDar/configuration (⭐108)](https://github.com/BoRuDar/configuration) — Set struct fields from env, flags, files ☆`108`
*   [gurkankaymak/hocon (⭐87)](https://github.com/gurkankaymak/hocon) — HOCON config library for Go ☆`88`
*   [PaddleHQ/go-aws-ssm (⭐62)](https://github.com/PaddleHQ/go-aws-ssm) — AWS System Manager interface ☆`62`
*   [go-simpler/env (⭐80)](https://github.com/go-simpler/env) — Load env vars to struct ☆`80`
*   [omeid/uconfig (⭐72)](https://github.com/omeid/uconfig) — Lightweight config management ☆`72`
*   [sakirsensoy/genv (⭐43)](https://github.com/sakirsensoy/genv) — Easy env variable handling ☆`43`
*   [num30/config (⭐60)](https://github.com/num30/config) — Declarative configuration ☆`60`
*   [wkhere/bcl (⭐29)](https://github.com/wkhere/bcl) — Basic Configuration Language ☆`29`
*   [dsbasko/go-cfg (⭐47)](https://github.com/dsbasko/go-cfg) — Unified config reading ☆`47`
*   [atelpis/enflag (⭐37)](https://github.com/atelpis/enflag) — Unify env and flag parsing ☆`37`
*   [greencoda/confiq (⭐39)](https://github.com/greencoda/confiq) — Config struct decoder ☆`39`
*   [nasermirzaei89/env (⭐22)](https://github.com/nasermirzaei89/env) — Zero-dep env package ☆`22`
*   [deatil/go-array (⭐22)](https://github.com/deatil/go-array) — Read/set map, slice, JSON data ☆`22`
*   [romshark/yamagiconf (⭐18)](https://github.com/romshark/yamagiconf) — YAML config framework ☆`18`

## Data Formats

### JSON

*   [tidwall/gjson (⭐15k)](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,438`
*   [bytedance/sonic (⭐9.2k)](https://github.com/bytedance/sonic) — A blazingly fast JSON serializing & deserializing library ☆`9,200`
*   [Jeffail/gabs (⭐3.5k)](https://github.com/Jeffail/gabs) — Dynamic JSON parsing ☆`3,528`
*   [valyala/fastjson (⭐2.4k)](https://github.com/valyala/fastjson) — Fast JSON parser for Go ☆`2,436`
*   [ohler55/ojg (⭐934)](https://github.com/ohler55/ojg) — Optimized JSON for Go ☆`935`
*   [wI2L/jsondiff (⭐622)](https://github.com/wI2L/jsondiff) — JSON Patch diff computation ☆`622`
*   [spyzhov/ajson (⭐291)](https://github.com/spyzhov/ajson) — Abstract JSON with JSONPath ☆`291`
*   [Andrew-M-C/go.jsonvalue (⭐202)](https://github.com/Andrew-M-C/go.jsonvalue) — Unstructured JSON solution ☆`202`
*   [iOliverNguyen/ujson (⭐85)](https://github.com/iOliverNguyen/ujson) — Minimal JSON parser ☆`85`
*   [neilotoole/jsoncolor (⭐49)](https://github.com/neilotoole/jsoncolor) — Colorized JSON output ☆`50`
*   [ake-persson/mapslice-json (⭐20)](https://github.com/ake-persson/mapslice-json) — Ordered JSON map slices ☆`20`
*   [vtopc/epoch (⭐17)](https://github.com/vtopc/epoch) — Unix timestamp marshaling ☆`17`

### Serialization

*   [golang/protobuf (⭐10k)](https://github.com/golang/protobuf) — Protocol buffers for Go ☆`10,061`
*   [ugorji/go (⭐1.9k)](https://github.com/ugorji/go) — Codec for msgpack, cbor, json ☆`1,937`
*   [linkedin/goavro (⭐1.1k)](https://github.com/linkedin/goavro) — Goavro is a library that encodes and decodes Avro data. ☆`1,055`
*   [fxamacker/cbor (⭐1k)](https://github.com/fxamacker/cbor) — CBOR codec with extensions ☆`1,022`
*   [jszwec/csvutil (⭐1k)](https://github.com/jszwec/csvutil) — CSV to struct mapping ☆`1,030`
*   [ghostiam/binstruct (⭐112)](https://github.com/ghostiam/binstruct) — Binary to struct decoder ☆`112`
*   [csweichel/bel (⭐45)](https://github.com/csweichel/bel) — Generate TypeScript from Go ☆`45`
*   [o1egl/fwencoder (⭐27)](https://github.com/o1egl/fwencoder) — Fixed width file parser ☆`27`
*   [tiendc/go-csvlib (⭐19)](https://github.com/tiendc/go-csvlib) — High-level CSV library ☆`18`

### XML

*   [miku/zek (⭐823)](https://github.com/miku/zek) — Generate Go struct from XML ☆`824`
*   [antchfx/xpath (⭐735)](https://github.com/antchfx/xpath) — XPath for Go ☆`735`
*   [antchfx/xmlquery (⭐485)](https://github.com/antchfx/xmlquery) — XPath XML query ☆`486`

## Data Structures

### Bit-packing and Compression

*   [RoaringBitmap/roaring (⭐2.8k)](https://github.com/RoaringBitmap/roaring) — Compressed bitmaps for Go ☆`2,836`
*   [iancmcc/bingo (⭐50)](https://github.com/iancmcc/bingo) — Zero-allocation binary encoding ☆`50`
*   [amallia/go-ef (⭐41)](https://github.com/amallia/go-ef) — A Go implementation of the Elias-Fano encoding ☆`41`

### Bloom and Cuckoo Filters

*   [bits-and-blooms/bloom (⭐2.7k)](https://github.com/bits-and-blooms/bloom) — Bloom filter implementation ☆`2,750`
*   [tylertreat/BoomFilters (⭐1.6k)](https://github.com/tylertreat/BoomFilters) — Probabilistic data structures for streams ☆`1,643`
*   [seiflotfy/cuckoofilter (⭐1.2k)](https://github.com/seiflotfy/cuckoofilter) — Cuckoo Filter: Practically Better Than Bloom ☆`1,218`
*   [OldPanda/bloomfilter (⭐20)](https://github.com/OldPanda/bloomfilter) — Bloom filter compatible with pybloom ☆`20`

### Maps

*   [mhmtszr/concurrent-swiss-map (⭐261)](https://github.com/mhmtszr/concurrent-swiss-map) — Thread-safe concurrent hash map ☆`261`
*   [goradd/maps (⭐51)](https://github.com/goradd/maps) — Generic map library for Go ☆`51`
*   [srfrog/dict (⭐46)](https://github.com/srfrog/dict) — Python-like dictionaries for Go ☆`46`

### Miscellaneous

*   [Workiva/go-datastructures (⭐7.9k)](https://github.com/Workiva/go-datastructures) — Performant, threadsafe data structures ☆`7,898`
*   [deckarep/golang-set (⭐4.6k)](https://github.com/deckarep/golang-set) — Generic set type for Go ☆`4,649`
*   [bits-and-blooms/bitset (⭐1.5k)](https://github.com/bits-and-blooms/bitset) — Go package implementing bitsets ☆`1,484`
*   [liyue201/gostl (⭐1.1k)](https://github.com/liyue201/gostl) — Data structures modeled on C++ STL ☆`1,135`
*   [axiomhq/hyperloglog (⭐1k)](https://github.com/axiomhq/hyperloglog) — HyperLogLog with optimizations ☆`1,029`
*   [kelindar/bitmap (⭐374)](https://github.com/kelindar/bitmap) — Simple dense bitmap index in Go with binary operators ☆`374`
*   [barweiss/go-tuple (⭐96)](https://github.com/barweiss/go-tuple) — Go 1.18+ generic tuple ☆`96`
*   [seiflotfy/count-min-log (⭐68)](https://github.com/seiflotfy/count-min-log) — Go implementation of Count-Min-Log ☆`68`
*   [s0rg/quadtree (⭐41)](https://github.com/s0rg/quadtree) — Generic, zero-alloc, 100%-test covered Quadtree for golang ☆`41`
*   [StudioSol/set (⭐29)](https://github.com/StudioSol/set) — Simple set data structure ☆`29`
*   [nazar256/parapipe (⭐37)](https://github.com/nazar256/parapipe) — Paralleling pipeline ☆`37`
*   [bobg/merkle (⭐21)](https://github.com/bobg/merkle) — Merkle hash trees ☆`21`

### Queues

*   [gammazero/deque (⭐755)](https://github.com/gammazero/deque) — Fast ring-buffer deque (double-ended queue) ☆`757`
*   [adrianbrad/queue (⭐330)](https://github.com/adrianbrad/queue) — Multiple queue implementations ☆`330`
*   [embano1/memlog (⭐135)](https://github.com/embano1/memlog) — A Kafka log inspired in-memory and append-only data structure ☆`135`
*   [mikestefanello/backlite (⭐137)](https://github.com/mikestefanello/backlite) — SQLite-backed task queues ☆`137`

## Databases

### Caches

*   [golang/groupcache (⭐13k)](https://github.com/golang/groupcache) — Distributed cache library ☆`13,323`
*   [dgraph-io/ristretto (⭐6.7k)](https://github.com/dgraph-io/ristretto) — A high performance memory-bound Go cache ☆`6,771`
*   [eko/gocache (⭐2.8k)](https://github.com/eko/gocache) — Multi-store caching library ☆`2,838`
*   [bluele/gcache (⭐2.7k)](https://github.com/bluele/gcache) — In-memory cache with eviction ☆`2,729`
*   [maypok86/otter (⭐2.5k)](https://github.com/maypok86/otter) — A high performance caching library for Go ☆`2,511`
*   [VictoriaMetrics/fastcache (⭐2.3k)](https://github.com/VictoriaMetrics/fastcache) — Fast in-memory cache for Go ☆`2,338`
*   [jellydator/ttlcache (⭐1.2k)](https://github.com/jellydator/ttlcache) — An in-memory cache with item expiration and generics ☆`1,214`
*   [viccon/sturdyc (⭐1.2k)](https://github.com/viccon/sturdyc) — Caching with advanced concurrency ☆`1,248`
*   [EchoVault/SugarDB (⭐519)](https://github.com/EchoVault/SugarDB) — Embeddable and distributed in-memory alternative to Redis. ☆`522`
*   [faabiosr/cachego (⭐372)](https://github.com/faabiosr/cachego) — Golang Cache component - Multiple drivers ☆`372`
*   [Yiling-J/theine-go (⭐362)](https://github.com/Yiling-J/theine-go) — high performance in-memory cache ☆`362`
*   [elastic/go-freelru (⭐260)](https://github.com/elastic/go-freelru) — GC-less, fast and generic LRU cache for Go ☆`261`
*   [samber/hot (⭐239)](https://github.com/samber/hot) — In-memory caching library for read-intensive Go applications ☆`242`
*   [naughtygopher/pocache (⭐231)](https://github.com/naughtygopher/pocache) — Preemptive optimistic caching ☆`231`
*   [OrlovEvgeny/go-mcache (⭐102)](https://github.com/OrlovEvgeny/go-mcache) — Sharded in-memory KV cache ☆`103`
*   [erni27/imcache (⭐123)](https://github.com/erni27/imcache) — A zero-dependency generic in-memory cache Go library ☆`123`
*   [zekroTJA/timedmap (⭐74)](https://github.com/zekroTJA/timedmap) — A thread safe map which has expiring key-value pairs. ☆`74`
*   [codingsince1985/couchcache (⭐66)](https://github.com/codingsince1985/couchcache) — A RESTful caching micro-service in Go backed by Couchbase ☆`66`
*   [mdaliyan/icache (⭐23)](https://github.com/mdaliyan/icache) — High-performance generic cache ☆`23`

### Database Schema Migration

*   [golang-migrate/migrate (⭐18k)](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,110`
*   [bytebase/bytebase (⭐14k)](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`13,738`
*   [pressly/goose (⭐10k)](https://github.com/pressly/goose) — A database migration tool. Supports SQL migrations and Go functions. ☆`10,187`
*   [ariga/atlas (⭐8.1k)](https://github.com/ariga/atlas) — Declarative schema migrations with schema-as-code workflows ☆`8,091`
*   [amacneil/dbmate (⭐6.7k)](https://github.com/amacneil/dbmate) — A lightweight, framework-agnostic database migration tool. ☆`6,724`
*   [rubenv/sql-migrate (⭐3.4k)](https://github.com/rubenv/sql-migrate) — SQL schema migration tool for Go. ☆`3,403`
*   [skeema/skeema (⭐1.4k)](https://github.com/skeema/skeema) — Declarative pure-SQL schema management for MySQL and MariaDB ☆`1,358`
*   [go-gormigrate/gormigrate (⭐1.1k)](https://github.com/go-gormigrate/gormigrate) — Minimalistic database migration helper for Gorm ORM ☆`1,150`
*   [sunary/sqlize (⭐124)](https://github.com/sunary/sqlize) — SQL parsing and migration toolkit ☆`124`
*   [robinjoseph08/go-pg-migrations (⭐86)](https://github.com/robinjoseph08/go-pg-migrations) — A Go package to help write migrations with go-pg/pg. ☆`86`
*   [adlio/schema (⭐42)](https://github.com/adlio/schema) — Embedded schema migration package for Go ☆`42`
*   [khezen/avro (⭐48)](https://github.com/khezen/avro) — Apache AVRO for go ☆`48`
*   [muir/libschema (⭐17)](https://github.com/muir/libschema) — database schema migrations on a per-library basis \[Go] ☆`17`

### Database Tools

*   [vitessio/vitess (⭐21k)](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`20,745`
*   [sosedoff/pgweb (⭐9.3k)](https://github.com/sosedoff/pgweb) — Cross-platform client for PostgreSQL databases ☆`9,257`
*   [go-mysql-org/go-mysql (⭐4.9k)](https://github.com/go-mysql-org/go-mysql) — a powerful mysql toolset with Go ☆`4,920`
*   [prest/prest (⭐4.5k)](https://github.com/prest/prest) — PostgreSQL REST API server ☆`4,519`
*   [ContentSquare/chproxy (⭐1.4k)](https://github.com/ContentSquare/chproxy) — Open-Source ClickHouse http proxy and load balancer ☆`1,437`
*   [cybertec-postgresql/pg\_timetable (⭐1.3k)](https://github.com/cybertec-postgresql/pg_timetable) — Advanced PostgreSQL scheduler ☆`1,319`
*   [liweiyi88/onedump (⭐891)](https://github.com/liweiyi88/onedump) — Effortless database administration tool ☆`924`
*   [HDT3213/rdb (⭐598)](https://github.com/HDT3213/rdb) — Redis RDB parser for Go ☆`597`
*   [nikepan/clickhouse-bulk (⭐505)](https://github.com/nikepan/clickhouse-bulk) — Batch inserts for ClickHouse ☆`505`
*   [wesql/wescale (⭐313)](https://github.com/wesql/wescale) — MySQL proxy with read/write split ☆`313`
*   [gatewayd-io/gatewayd (⭐275)](https://github.com/gatewayd-io/gatewayd) — database gateway for building data-driven applications ☆`275`
*   [sj14/dbbench (⭐115)](https://github.com/sj14/dbbench) — Database benchmarking tool ☆`115`
*   [bartventer/gorm-multitenancy (⭐78)](https://github.com/bartventer/gorm-multitenancy) — Multi-tenancy for GORM ☆`78`
*   [kazhuravlev/database-gateway (⭐30)](https://github.com/kazhuravlev/database-gateway) — Safe access to production databases ☆`29`
*   [codingconcepts/dg (⭐43)](https://github.com/codingconcepts/dg) — Generate CSV from data models ☆`43`

### Databases Implemented in Go

*   [prometheus/prometheus (⭐63k)](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`62,801`
*   [milvus-io/milvus (⭐43k)](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`42,827`
*   [pingcap/tidb (⭐40k)](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`39,798`
*   [cockroachdb/cockroach (⭐32k)](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`31,900`
*   [influxdata/influxdb (⭐31k)](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,257`
*   [dgraph-io/dgraph (⭐22k)](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,573`
*   [dolthub/dolt (⭐20k)](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`19,886`
*   [rqlite/rqlite (⭐17k)](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,314`
*   [VictoriaMetrics/VictoriaMetrics (⭐16k)](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`16,337`
*   [dgraph-io/badger (⭐15k)](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,477`
*   [dicedb/dicedb (⭐11k)](https://github.com/dicedb/dicedb) — Open-source, low-latency key/value engine built on Valkey with hierarchical storage tiers. ☆`10,686`
*   [etcd-io/bbolt (⭐9.3k)](https://github.com/etcd-io/bbolt) — An embedded key/value database for Go. ☆`9,371`
*   [codenotary/immudb (⭐8.9k)](https://github.com/codenotary/immudb) — Immutable database with SQL ☆`8,920`
*   [cockroachdb/pebble (⭐5.8k)](https://github.com/cockroachdb/pebble) — RocksDB/LevelDB inspired key-value database in Go ☆`5,773`
*   [rosedblabs/rosedb (⭐4.9k)](https://github.com/rosedblabs/rosedb) — Fast key/value storage engine ☆`4,876`
*   [tidwall/buntdb (⭐4.8k)](https://github.com/tidwall/buntdb) — Embeddable in-memory key/value DB ☆`4,833`
*   [nalgeon/redka (⭐4.5k)](https://github.com/nalgeon/redka) — Redis re-implemented with SQL ☆`4,525`
*   [HDT3213/godis (⭐3.8k)](https://github.com/HDT3213/godis) — A Golang implemented Redis Server and Cluster ☆`3,821`
*   [nutsdb/nutsdb (⭐3.6k)](https://github.com/nutsdb/nutsdb) — Simple embeddable key/value store ☆`3,551`
*   [lindb/lindb (⭐3.1k)](https://github.com/lindb/lindb) — Scalable time-series database ☆`3,060`
*   [lotusdblabs/lotusdb (⭐2.3k)](https://github.com/lotusdblabs/lotusdb) — Key-value database with LSM and B+ tree ☆`2,250`
*   [kelindar/column (⭐1.5k)](https://github.com/kelindar/column) — Columnar in-memory store ☆`1,506`
*   [akrylysov/pogreb (⭐1.4k)](https://github.com/akrylysov/pogreb) — Embedded key-value store for read-heavy workloads written in Go ☆`1,349`
*   [objectbox/objectbox-go (⭐1.3k)](https://github.com/objectbox/objectbox-go) — Embedded database for Go ☆`1,257`
*   [couchbase/moss (⭐1k)](https://github.com/couchbase/moss) — Simple, fast key-val storage ☆`1,017`
*   [amit-davidson/LibraDB (⭐199)](https://github.com/amit-davidson/LibraDB) — Simple persistent key/value store ☆`198`
*   [claygod/transaction (⭐139)](https://github.com/claygod/transaction) — Embedded database for accounts transactions. ☆`139`
*   [xgzlucario/rotom (⭐41)](https://github.com/xgzlucario/rotom) — Tiny Redis server in Go ☆`41`

### Distributed Storage

*   [seaweedfs/seaweedfs (⭐30k)](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`30,405`
*   [juicedata/juicefs (⭐13k)](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`13,233`

### Interfaces to Multiple Backends

*   [philippgille/gokv (⭐821)](https://github.com/philippgille/gokv) — Key-value store abstraction ☆`821`
*   [avito-tech/go-transaction-manager (⭐377)](https://github.com/avito-tech/go-transaction-manager) — Transaction manager for Go ☆`384`
*   [viant/dsc (⭐35)](https://github.com/viant/dsc) — Datastore Connectivity in go ☆`35`
*   [fogfish/dynamo (⭐22)](https://github.com/fogfish/dynamo) — Generic Golang Key/Value trait for AWS storage services ☆`22`

### NoSQL Database Drivers

*   [redis/go-redis (⭐22k)](https://github.com/redis/go-redis) — Redis Go client ☆`21,930`
*   [gomodule/redigo (⭐9.9k)](https://github.com/gomodule/redigo) — Go client for Redis ☆`9,883`
*   [mongodb/mongo-go-driver (⭐8.5k)](https://github.com/mongodb/mongo-go-driver) — The Official Golang driver for MongoDB ☆`8,504`
*   [bradfitz/gomemcache (⭐1.9k)](https://github.com/bradfitz/gomemcache) — Go Memcached client library #golang ☆`1,867`
*   [qiniu/qmgo (⭐1.3k)](https://github.com/qiniu/qmgo) — Go driver for MongoDB ☆`1,348`
*   [aerospike/aerospike-client-go (⭐457)](https://github.com/aerospike/aerospike-client-go) — Aerospike Client Go ☆`457`
*   [couchbase/gocb (⭐376)](https://github.com/couchbase/gocb) — The Couchbase Go SDK ☆`376`
*   [go-kivik/kivik (⭐335)](https://github.com/go-kivik/kivik) — CouchDB client interface ☆`336`
*   [couchbase/go-couchbase (⭐324)](https://github.com/couchbase/go-couchbase) — Couchbase client in Go ☆`324`
*   [chenmingyong0423/go-mongox (⭐217)](https://github.com/chenmingyong0423/go-mongox) — MongoDB driver wrapper with generics ☆`217`
*   [aliexpressru/gomemcached (⭐22)](https://github.com/aliexpressru/gomemcached) — Binary Memcached client with sharding ☆`22`
*   [btnguyen2k/gocosmos (⭐22)](https://github.com/btnguyen2k/gocosmos) — Go database/sql driver for Azure Cosmos DB SQL API ☆`22`

### ORM

*   [go-gorm/gorm (⭐39k)](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,602`
*   [ent/ent (⭐17k)](https://github.com/ent/ent) — An entity framework for Go ☆`16,925`
*   [aarondl/sqlboiler (⭐7k)](https://github.com/aarondl/sqlboiler) — Generate a Go ORM tailored to your database schema. ☆`6,976`
*   [uptrace/bun (⭐4.7k)](https://github.com/uptrace/bun) — SQL-first Golang ORM ☆`4,667`
*   [upper/db (⭐3.6k)](https://github.com/upper/db) — Data access layer for databases ☆`3,644`
*   [huandu/go-sqlbuilder (⭐1.7k)](https://github.com/huandu/go-sqlbuilder) — SQL builder with zero-config ORM ☆`1,669`
*   [stephenafamo/bob (⭐1.6k)](https://github.com/stephenafamo/bob) — SQL builder with ORM generator ☆`1,634`
*   [go-rel/rel (⭐781)](https://github.com/go-rel/rel) — Modern ORM for Golang ☆`781`
*   [FrancoLiberali/cql (⭐17)](https://github.com/FrancoLiberali/cql) — CQL: Compiled Query Language ☆`17`
*   [hashicorp/go-dbw (⭐16)](https://github.com/hashicorp/go-dbw) — A simple package that encapsulates database operations. ☆`16`

### Query Language

*   [99designs/gqlgen (⭐11k)](https://github.com/99designs/gqlgen) — go generate based graphql server library ☆`10,667`
*   [TomWright/dasel (⭐7.8k)](https://github.com/TomWright/dasel) — Query and modify data formats ☆`7,834`
*   [graph-gophers/graphql-go (⭐4.7k)](https://github.com/graph-gophers/graphql-go) — GraphQL server with a focus on ease of use ☆`4,739`
*   [bhmj/jsonslice (⭐92)](https://github.com/bhmj/jsonslice) — json slicer ☆`92`
*   [hashicorp/mql (⭐65)](https://github.com/hashicorp/mql) — Model Query Language (mql) is a query language for your database models. ☆`65`
*   [ccbrown/api-fu (⭐57)](https://github.com/ccbrown/api-fu) — A collection of Go packages for creating robust GraphQL APIs ☆`57`
*   [AsaiYusuke/jsonpath (⭐30)](https://github.com/AsaiYusuke/jsonpath) — JSONPath query library ☆`30`

### Relational Database Drivers

*   [go-sql-driver/mysql (⭐15k)](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,421`
*   [jackc/pgx (⭐13k)](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`13,378`
*   [denisenkom/go-mssqldb (⭐1.9k)](https://github.com/denisenkom/go-mssqldb) — Microsoft SQL server driver written in go language ☆`1,880`
*   [ncruces/go-sqlite3 (⭐908)](https://github.com/ncruces/go-sqlite3) — Go bindings to SQLite using wazero ☆`914`
*   [godror/godror (⭐585)](https://github.com/godror/godror) — GO DRiver for ORacle DB ☆`587`
*   [cvilsmeier/sqinn-go (⭐512)](https://github.com/cvilsmeier/sqinn-go) — Golang SQLite without cgo ☆`510`
*   [VinGarcia/ksql (⭐352)](https://github.com/VinGarcia/ksql) — A Simple and Powerful Golang SQL Library ☆`353`
*   [surrealdb/surrealdb.go (⭐299)](https://github.com/surrealdb/surrealdb.go) — SurrealDB SDK for Golang ☆`301`
*   [nakagami/firebirdsql (⭐254)](https://github.com/nakagami/firebirdsql) — Firebird RDBMS sql driver for Go (golang) ☆`255`
*   [ydb-platform/ydb-go-sdk (⭐173)](https://github.com/ydb-platform/ydb-go-sdk) — Pure Go native and database/sql driver for YDB ☆`174`
*   [rqlite/gorqlite (⭐178)](https://github.com/rqlite/gorqlite) — A Go client for rqlite, the distributed database built on SQLite ☆`179`
*   [apache/calcite-avatica-go (⭐124)](https://github.com/apache/calcite-avatica-go) — Apache Calcite Go ☆`124`
*   [viant/bgc (⭐21)](https://github.com/viant/bgc) — Datastore Connectivity for BigQuery in go ☆`21`

### SQL Query Builders

*   [sqlc-dev/sqlc (⭐17k)](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`16,975`
*   [Masterminds/squirrel (⭐7.9k)](https://github.com/Masterminds/squirrel) — Fluent SQL generation for golang ☆`7,866`
*   [xo/dbtpl (⭐3.9k)](https://github.com/xo/dbtpl) — Generate Go code for databases ☆`3,885`
*   [go-jet/jet (⭐3.6k)](https://github.com/go-jet/jet) — Type-safe SQL builder with codegen ☆`3,576`
*   [doug-martin/goqu (⭐2.6k)](https://github.com/doug-martin/goqu) — SQL builder and query library for golang ☆`2,635`
*   [didi/gendry (⭐1.6k)](https://github.com/didi/gendry) — a golang library for sql builder ☆`1,642`
*   [lqs/sqlingo (⭐447)](https://github.com/lqs/sqlingo) — A lightweight DSL & ORM which helps you to write SQL in Go. ☆`448`
*   [nullism/bqb (⭐187)](https://github.com/nullism/bqb) — Lightweight query builder ☆`186`
*   [arthurkushman/buildsqlx (⭐185)](https://github.com/arthurkushman/buildsqlx) — Go database query builder library for PostgreSQL ☆`185`
*   [galeone/igor (⭐126)](https://github.com/galeone/igor) — igor is an abstraction layer for PostgreSQL with a gorm like syntax. ☆`126`
*   [cristalhq/builq (⭐97)](https://github.com/cristalhq/builq) — Easily build SQL queries in Go. ☆`97`
*   [JiveGroup/FluentSQL (⭐18)](https://github.com/JiveGroup/FluentSQL) — Fluent SQL - flexible and powerful SQL string builder ☆`18`

### Search and Analytic Databases

*   [elastic/go-elasticsearch (⭐6k)](https://github.com/elastic/go-elasticsearch) — The official Go client for Elasticsearch ☆`6,026`
*   [ClickHouse/clickhouse-go (⭐3.2k)](https://github.com/ClickHouse/clickhouse-go) — Golang driver for ClickHouse ☆`3,247`
*   [sourcegraph/zoekt (⭐1.4k)](https://github.com/sourcegraph/zoekt) — Fast trigram-based code search ☆`1,395`
*   [sdqri/effdsl (⭐34)](https://github.com/sdqri/effdsl) — Elasticsearch query builder for golang ☆`34`

## DevOps & Build

### Backup

*   [restic/restic (⭐32k)](https://github.com/restic/restic) — Fast, secure backup program ☆`32,312`
*   [gilbertchen/duplicacy (⭐5.6k)](https://github.com/gilbertchen/duplicacy) — Cloud backup tool ☆`5,619`

### Build Automation

*   [air-verse/air (⭐23k)](https://github.com/air-verse/air) — Live reload for Go apps ☆`22,989`
*   [go-task/task (⭐15k)](https://github.com/go-task/task) — A fast, cross-platform build tool inspired by Make, designed for modern workflows. ☆`14,846`
*   [joerdav/xc (⭐1.4k)](https://github.com/joerdav/xc) — Markdown defined task runner. ☆`1,371`
*   [goyek/goyek (⭐677)](https://github.com/goyek/goyek) — Task automation Go library ☆`677`
*   [flowexec/flow (⭐130)](https://github.com/flowexec/flow) — Local developer automation platform that flows with you ☆`132`

### CI/CD

*   [harness/harness (⭐34k)](https://github.com/harness/harness) — End-to-end developer platform ☆`33,882`
*   [woodpecker-ci/woodpecker (⭐6.4k)](https://github.com/woodpecker-ci/woodpecker) — Simple, powerful CI/CD engine ☆`6,487`
*   [ovh/cds (⭐4.8k)](https://github.com/ovh/cds) — Enterprise CI/CD platform ☆`4,803`
*   [raviqqe/muffet (⭐2.6k)](https://github.com/raviqqe/muffet) — Fast website link checker ☆`2,590`
*   [pipe-cd/pipecd (⭐1.2k)](https://github.com/pipe-cd/pipecd) — The One CD for All {applications, platforms, operations} ☆`1,252`
*   [jenkins-zh/jenkins-cli (⭐410)](https://github.com/jenkins-zh/jenkins-cli) — Jenkins CLI allows you to manage your Jenkins in an easy way ☆`410`
*   [vladopajic/go-test-coverage (⭐216)](https://github.com/vladopajic/go-test-coverage) — Report test coverage threshold issues ☆`217`
*   [appleboy/drone-scp (⭐166)](https://github.com/appleboy/drone-scp) — Copy files via SSH for Drone ☆`166`
*   [nikogura/gomason (⭐66)](https://github.com/nikogura/gomason) — A tool for testing, building, signing, and publishing binaries. ☆`66`
*   [appleboy/drone-jenkins (⭐41)](https://github.com/appleboy/drone-jenkins) — Drone plugin for trigger Jenkins jobs. ☆`41`
*   [opnlabs/dot (⭐33)](https://github.com/opnlabs/dot) — Minimal CI using Docker ☆`33`
*   [gha-common/go-beautiful-html-coverage (⭐20)](https://github.com/gha-common/go-beautiful-html-coverage) — GitHub Action for code coverage reports ☆`21`

### Containers

*   [moby/moby (⭐71k)](https://github.com/moby/moby) — Container ecosystem components ☆`71,479`
*   [traefik/traefik (⭐62k)](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`61,816`
*   [ko-build/ko (⭐8.3k)](https://github.com/ko-build/ko) — Build and deploy Go applications ☆`8,342`
*   [s0rg/decompose (⭐123)](https://github.com/s0rg/decompose) — Reverse-engineering tool for docker environments ☆`123`
*   [x1unix/docker-go-mingw (⭐53)](https://github.com/x1unix/docker-go-mingw) — Docker for Go with MinGW toolchain ☆`53`

### DevOps Utilities

*   [go-gitea/gitea (⭐54k)](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`53,781`
*   [moovweb/gvm (⭐12k)](https://github.com/moovweb/gvm) — Go Version Manager ☆`11,536`
*   [TwiN/gatus (⭐10k)](https://github.com/TwiN/gatus) — Automated developer-oriented status page with alerting and incident support ☆`10,141`
*   [bitfield/script (⭐6.9k)](https://github.com/bitfield/script) — Making it easy to write shell-like scripts in Go ☆`6,933`
*   [fleetdm/fleet (⭐6k)](https://github.com/fleetdm/fleet) — Open device management ☆`6,051`
*   [taubyte/tau (⭐5k)](https://github.com/taubyte/tau) — Fullstack Workspace for Humans & Machines ☆`4,973`
*   [megaease/easeprobe (⭐2.3k)](https://github.com/megaease/easeprobe) — Service health monitoring tool ☆`2,295`
*   [ajvb/kala (⭐2.2k)](https://github.com/ajvb/kala) — Modern Job Scheduler ☆`2,162`
*   [gabrie30/ghorg (⭐2k)](https://github.com/gabrie30/ghorg) — Clone entire GitHub orgs ☆`1,974`
*   [sanbornm/go-selfupdate (⭐1.7k)](https://github.com/sanbornm/go-selfupdate) — Enable your Go applications to self update ☆`1,678`
*   [yusufcanb/tlm (⭐1.5k)](https://github.com/yusufcanb/tlm) — Local CLI Copilot, powered by Ollama. ☆`1,468`
*   [ovh/utask (⭐1.4k)](https://github.com/ovh/utask) — Automation engine with YAML config ☆`1,361`
*   [TimothyYe/skm (⭐1k)](https://github.com/TimothyYe/skm) — A simple and powerful SSH keys manager ☆`1,008`
*   [scaleway/scaleway-cli (⭐954)](https://github.com/scaleway/scaleway-cli) — Command Line Interface for Scaleway ☆`956`
*   [alexliesenfeld/health (⭐829)](https://github.com/alexliesenfeld/health) — A simple and flexible health check library for Go. ☆`829`
*   [kool-dev/kool (⭐714)](https://github.com/kool-dev/kool) — Dev to cloud web apps made easy ☆`712`
*   [kevincobain2000/gobrew (⭐411)](https://github.com/kevincobain2000/gobrew) — Go version manager without root ☆`411`
*   [appleboy/easyssh-proxy (⭐345)](https://github.com/appleboy/easyssh-proxy) — Simple SSH protocol implementation ☆`345`
*   [xitonix/trubka (⭐337)](https://github.com/xitonix/trubka) — A CLI tool for Kafka ☆`337`
*   [emicklei/mora (⭐316)](https://github.com/emicklei/mora) — MongoDB generic REST server in Go ☆`315`
*   [thevxn/dish (⭐274)](https://github.com/thevxn/dish) — A simple, remotely configurable monitoring service. ☆`274`
*   [jkaninda/goma-gateway (⭐175)](https://github.com/jkaninda/goma-gateway) — Lightweight API gateway and proxy ☆`175`
*   [datarootsio/tf-profile (⭐163)](https://github.com/datarootsio/tf-profile) — Profile Terraform runs ☆`163`
*   [kazhuravlev/healthcheck (⭐22)](https://github.com/kazhuravlev/healthcheck) — Readiness probes for Kubernetes application ☆`21`

### Infrastructure

*   [hashicorp/packer (⭐16k)](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,608`
*   [pomerium/pomerium (⭐4.7k)](https://github.com/pomerium/pomerium) — Pomerium is an identity and context-aware access proxy. ☆`4,676`
*   [peak/s5cmd (⭐3.9k)](https://github.com/peak/s5cmd) — Parallel S3 and local filesystem execution tool. ☆`3,921`
*   [aptly-dev/aptly (⭐2.8k)](https://github.com/aptly-dev/aptly) — aptly - Debian repository management tool ☆`2,771`
*   [KusionStack/kusion (⭐1.3k)](https://github.com/KusionStack/kusion) — Declarative platform orchestrator ☆`1,272`
*   [oxyno-zeta/s3-proxy (⭐432)](https://github.com/oxyno-zeta/s3-proxy) — S3 reverse proxy with auth ☆`435`

### Kubernetes

*   [kubernetes/kubernetes (⭐120k)](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`120,676`
*   [k3s-io/k3s (⭐32k)](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`32,223`
*   [kubernetes/minikube (⭐31k)](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,502`
*   [kubernetes-sigs/kind (⭐15k)](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,026`
*   [kubeshark/kubeshark (⭐12k)](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`11,794`
*   [flannel-io/flannel (⭐9.4k)](https://github.com/flannel-io/flannel) — Network fabric for containers ☆`9,406`
*   [getanteon/anteon (⭐8.5k)](https://github.com/getanteon/anteon) — eBPF Kubernetes monitoring tool ☆`8,543`
*   [kubevela/kubevela (⭐7.7k)](https://github.com/kubevela/kubevela) — The Modern Application Platform. ☆`7,688`
*   [k3d-io/k3d (⭐6.2k)](https://github.com/k3d-io/k3d) — Little helper to run CNCF's k3s in Docker ☆`6,260`
*   [stefanprodan/podinfo (⭐5.8k)](https://github.com/stefanprodan/podinfo) — Go microservice template for Kubernetes ☆`5,829`
*   [apecloud/kubeblocks (⭐3k)](https://github.com/apecloud/kubeblocks) — Kubernetes operator for databases ☆`2,980`
*   [kubenetworks/kubevpn (⭐1.3k)](https://github.com/kubenetworks/kubevpn) — Connect to Kubernetes cluster network ☆`1,295`
*   [abahmed/kwatch (⭐992)](https://github.com/abahmed/kwatch) — monitor & detect crashes in your Kubernetes(K8s) cluster instantly ☆`995`
*   [getanteon/alaz (⭐716)](https://github.com/getanteon/alaz) — eBPF agent for K8s observability ☆`718`

### Load Testing

*   [grafana/k6 (⭐30k)](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`29,931`
*   [tsenart/vegeta (⭐25k)](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`24,907`
*   [codesenberg/bombardier (⭐6.7k)](https://github.com/codesenberg/bombardier) — Fast cross-platform HTTP benchmarking tool written in Go ☆`6,733`
*   [rogerwelin/cassowary (⭐809)](https://github.com/rogerwelin/cassowary) — Modern cross-platform HTTP load-testing tool written in Go ☆`808`

## Email

*   [axllent/mailpit (⭐8.7k)](https://github.com/axllent/mailpit) — An email and SMTP testing tool with API for developers ☆`8,754`
*   [foxcpp/maddy (⭐5.8k)](https://github.com/foxcpp/maddy) — Composable all-in-one mail server. ☆`5,848`
*   [mjl-/mox (⭐5.5k)](https://github.com/mjl-/mox) — Modern secure mail server ☆`5,472`
*   [matcornic/hermes (⭐3k)](https://github.com/matcornic/hermes) — Clean HTML email generator ☆`3,046`
*   [AfterShip/email-verifier (⭐1.5k)](https://github.com/AfterShip/email-verifier) — Email verification without sending emails ☆`1,518`
*   [wneessen/go-mail (⭐1.3k)](https://github.com/wneessen/go-mail) — Easy to use, yet comprehensive library for sending mails with Go ☆`1,278`
*   [sendgrid/sendgrid-go (⭐1k)](https://github.com/sendgrid/sendgrid-go) — The Official Twilio SendGrid Golang API Library ☆`1,047`
*   [mailgun/mailgun-go (⭐743)](https://github.com/mailgun/mailgun-go) — Go library for the Mailgun API. ☆`743`
*   [xhit/go-simple-mail (⭐691)](https://github.com/xhit/go-simple-mail) — Simple mail sending with TLS/SSL ☆`693`
*   [emersion/go-message (⭐438)](https://github.com/emersion/go-message) — Internet Message Format library ☆`438`
*   [vanng822/go-premailer (⭐187)](https://github.com/vanng822/go-premailer) — Inline CSS for HTML mail ☆`187`
*   [truemail-rb/truemail-go (⭐129)](https://github.com/truemail-rb/truemail-go) — Email validator via Regex, DNS, SMTP ☆`129`
*   [toorop/go-dkim (⭐99)](https://github.com/toorop/go-dkim) — DKIM package for golang ☆`99`
*   [dimuska139/go-email-normalizer (⭐77)](https://github.com/dimuska139/go-email-normalizer) — Normalize email addresses ☆`77`
*   [valord577/mailx (⭐20)](https://github.com/valord577/mailx) — A library that makes it easier to send email via SMTP. ☆`20`

## Finance & Blockchain

### Blockchain

*   [ethereum/go-ethereum (⭐51k)](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`50,823`
*   [ipfs/kubo (⭐17k)](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`16,911`
*   [lightningnetwork/lnd (⭐8.1k)](https://github.com/lightningnetwork/lnd) — Lightning Network Daemon ☆`8,109`
*   [cosmos/cosmos-sdk (⭐6.9k)](https://github.com/cosmos/cosmos-sdk) — A Framework for Building High Value Public Blockchains ☆`6,932`
*   [gagliardetto/solana-go (⭐1.5k)](https://github.com/gagliardetto/solana-go) — Go SDK library and RPC client for the Solana Blockchain ☆`1,509`
*   [gnolang/gno (⭐1k)](https://github.com/gnolang/gno) — Interpreted Go virtual machine ☆`1,052`
*   [cometbft/cometbft (⭐854)](https://github.com/cometbft/cometbft) — Byzantine fault-tolerant consensus ☆`858`
*   [ChainSafe/gossamer (⭐456)](https://github.com/ChainSafe/gossamer) — Go Implementation of the Polkadot Host ☆`455`

### Financial

*   [shopspring/decimal (⭐7.2k)](https://github.com/shopspring/decimal) — Arbitrary-precision fixed-point decimal numbers in Go ☆`7,240`
*   [achannarasappa/ticker (⭐5.9k)](https://github.com/achannarasappa/ticker) — Terminal stock and crypto tracker ☆`5,941`
*   [Rhymond/go-money (⭐1.8k)](https://github.com/Rhymond/go-money) — Go implementation of Fowler's Money pattern ☆`1,880`
*   [c9s/bbgo (⭐1.6k)](https://github.com/c9s/bbgo) — The modern cryptocurrency trading bot framework written in Go. ☆`1,599`
*   [formancehq/ledger (⭐1.1k)](https://github.com/formancehq/ledger) — The programmable open source core ledger for fintech ☆`1,151`
*   [bojanz/currency (⭐623)](https://github.com/bojanz/currency) — Currency handling for Go. ☆`624`
*   [moov-io/ach (⭐526)](https://github.com/moov-io/ach) — ACH file reader, writer, validator ☆`529`
*   [invopop/gobl (⭐249)](https://github.com/invopop/gobl) — Go Business Language ☆`258`
*   [govalues/decimal (⭐222)](https://github.com/govalues/decimal) — Correctly rounded decimals for Go ☆`222`
*   [quagmt/udecimal (⭐170)](https://github.com/quagmt/udecimal) — High-precision decimal library ☆`171`
*   [jovandeginste/payme (⭐89)](https://github.com/jovandeginste/payme) — QR code generator (ASCII & PNG) for SEPA payments ☆`89`
*   [jokruger/dec128 (⭐41)](https://github.com/jokruger/dec128) — High performance 128-bit fixed-point decimal numbers in go. ☆`41`
*   [govalues/money (⭐48)](https://github.com/govalues/money) — Correctly rounded monetary amounts and exchange rates for Go ☆`48`
*   [nikolaydubina/fpmoney (⭐35)](https://github.com/nikolaydubina/fpmoney) — Fixed-Point Decimal Money ☆`35`
*   [nikolaydubina/fpdecimal (⭐34)](https://github.com/nikolaydubina/fpdecimal) — Fixed-Point Decimals ☆`34`

### Payment APIs

*   [stripe/stripe-go (⭐2.5k)](https://github.com/stripe/stripe-go) — Stripe API library for Go ☆`2,530`
*   [plutov/paypal (⭐771)](https://github.com/plutov/paypal) — Golang client for PayPal REST API ☆`772`
*   [brunomvsouza/ynab.go (⭐79)](https://github.com/brunomvsouza/ynab.go) — Client for YNAB API ☆`79`

## GUI & Desktop

### GUI

*   [fyne-io/fyne (⭐28k)](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`27,939`
*   [webview/webview (⭐14k)](https://github.com/webview/webview) — Tiny webview library for Go ☆`13,911`
*   [therecipe/qt (⭐11k)](https://github.com/therecipe/qt) — Qt bindings for Go ☆`10,786`
*   [go-vgo/robotgo (⭐11k)](https://github.com/go-vgo/robotgo) — Cross-platform RPA and GUI automation ☆`10,612`
*   [maxence-charriere/go-app (⭐8.9k)](https://github.com/maxence-charriere/go-app) — Build progressive web apps with Go and WASM ☆`8,856`
*   [progrium/darwinkit (⭐5.4k)](https://github.com/progrium/darwinkit) — Native Mac APIs for Go. Previously known as MacDriver ☆`5,398`
*   [getlantern/systray (⭐3.7k)](https://github.com/getlantern/systray) — Cross-platform systray library ☆`3,661`
*   [cogentcore/core (⭐2.3k)](https://github.com/cogentcore/core) — Powerful GUI framework for Go ☆`2,308`
*   [gotk3/gotk3 (⭐2.2k)](https://github.com/gotk3/gotk3) — Go bindings for GTK3 ☆`2,202`
*   [roblillack/spot (⭐1.3k)](https://github.com/roblillack/spot) — React-like desktop GUI toolkit for Go ☆`1,258`
*   [ncruces/zenity (⭐891)](https://github.com/ncruces/zenity) — Zenity dialogs for Golang, Windows, macOS ☆`893`
*   [energye/energy (⭐574)](https://github.com/energye/energy) — CEF-based GUI framework ☆`577`
*   [AllenDang/cimgui-go (⭐491)](https://github.com/AllenDang/cimgui-go) — Auto generated Go wrapper for Dear ImGui via cimgui ☆`495`
*   [richardwilkes/unison (⭐316)](https://github.com/richardwilkes/unison) — Unified GUI toolkit for Go ☆`318`

### Windows

*   [go-ole/go-ole (⭐1.3k)](https://github.com/go-ole/go-ole) — win32 ole implementation for golang ☆`1,292`
*   [gonutz/d3d9 (⭐163)](https://github.com/gonutz/d3d9) — Direct3D9 wrapper for Go. ☆`163`

## Game Development

### Game Engines

*   [hajimehoshi/ebiten (⭐13k)](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`12,965`
*   [fogleman/nes (⭐5.6k)](https://github.com/fogleman/nes) — NES emulator written in Go. ☆`5,639`
*   [topfreegames/pitaya (⭐2.7k)](https://github.com/topfreegames/pitaya) — Game server with clustering support ☆`2,736`
*   [xiaonanln/goworld (⭐2.7k)](https://github.com/xiaonanln/goworld) — Distributed game server engine ☆`2,704`
*   [gen2brain/raylib-go (⭐2.3k)](https://github.com/gen2brain/raylib-go) — Go bindings for raylib ☆`2,361`
*   [oakmound/oak (⭐1.7k)](https://github.com/oakmound/oak) — A pure Go game engine ☆`1,652`
*   [JoelOtter/termloop (⭐1.5k)](https://github.com/JoelOtter/termloop) — Terminal-based game engine for Go, built on top of Termbox ☆`1,470`
*   [gopxl/pixel (⭐376)](https://github.com/gopxl/pixel) — A hand-crafted 2D game library in Go. ☆`376`
*   [ungerik/go3d (⭐338)](https://github.com/ungerik/go3d) — A performance oriented 2D/3D math package for Go ☆`338`
*   [mlange-42/ark (⭐210)](https://github.com/mlange-42/ark) — Ark -- Archetype-based Entity Component System (ECS) for Go. ☆`215`
*   [kelindar/tile (⭐210)](https://github.com/kelindar/tile) — 2D grid engine for games ☆`211`
*   [andygeiss/ecs (⭐169)](https://github.com/andygeiss/ecs) — Entity Component System for games ☆`171`
*   [gonutz/prototype (⭐108)](https://github.com/gonutz/prototype) — 2D game prototyping framework ☆`107`
*   [s0rg/grid (⭐25)](https://github.com/s0rg/grid) — Generic 2D grid ☆`25`
*   [s0rg/fantasyname (⭐39)](https://github.com/s0rg/fantasyname) — RinkWorks fantasy name generator for golang ☆`39`

### OpenGL

*   [go-gl/glfw (⭐1.7k)](https://github.com/go-gl/glfw) — Go bindings for GLFW 3 ☆`1,660`
*   [go-gl/gl (⭐1.2k)](https://github.com/go-gl/gl) — Go bindings for OpenGL (generated via glow) ☆`1,188`
*   [go-gl/mathgl (⭐596)](https://github.com/go-gl/mathgl) — A pure Go 3D math library. ☆`596`

## Geospatial

*   [tidwall/tile38 (⭐9.6k)](https://github.com/tidwall/tile38) — Real-time Geospatial and Geofencing ☆`9,577`
*   [golang/geo (⭐1.8k)](https://github.com/golang/geo) — S2 geometry library in Go ☆`1,820`
*   [consbio/mbtileserver (⭐770)](https://github.com/consbio/mbtileserver) — MBTiles server in Go ☆`771`
*   [spatial-go/geoos (⭐532)](https://github.com/spatial-go/geoos) — Spatial data and geometric algorithms ☆`532`
*   [paulmach/osm (⭐443)](https://github.com/paulmach/osm) — OpenStreetMap data library ☆`443`
*   [uber/h3-go (⭐404)](https://github.com/uber/h3-go) — H3 hexagonal geospatial indexing ☆`406`
*   [airbusgeo/godal (⭐173)](https://github.com/airbusgeo/godal) — GDAL wrapper for Go ☆`174`
*   [peterstace/simplefeatures (⭐168)](https://github.com/peterstace/simplefeatures) — OpenGIS Simple Feature implementation ☆`168`
*   [wroge/wgs84 (⭐140)](https://github.com/wroge/wgs84) — Zero-dep coordinate transformations ☆`140`
*   [pantrif/s2-geojson (⭐36)](https://github.com/pantrif/s2-geojson) — Visualize S2 cells on a map ☆`36`

## Go Tooling

### Compilers

*   [gopherjs/gopherjs (⭐13k)](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,125`
*   [yassinebenaid/bunster (⭐2.6k)](https://github.com/yassinebenaid/bunster) — Compile shell scripts to static binaries. ☆`2,643`
*   [Konstantin8105/c4go (⭐377)](https://github.com/Konstantin8105/c4go) — Transpiling C code to Go code ☆`379`
*   [go2hx/go2hx (⭐149)](https://github.com/go2hx/go2hx) — Import Go libraries in Haxe ☆`149`

### Editor Plugins

*   [fatih/vim-go (⭐16k)](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,238`
*   [visualfc/liteide (⭐7.8k)](https://github.com/visualfc/liteide) — LiteIDE is a simple, open source, cross-platform Go IDE. ☆`7,757`
*   [nsf/gocode (⭐5k)](https://github.com/nsf/gocode) — An autocompletion daemon for the Go programming language ☆`4,999`
*   [golang/vscode-go (⭐4.2k)](https://github.com/golang/vscode-go) — Go extension for Visual Studio Code ☆`4,206`
*   [dominikh/go-mode.el (⭐1.4k)](https://github.com/dominikh/go-mode.el) — Emacs mode for the Go programming language ☆`1,446`
*   [incu6us/goimports-reviser (⭐712)](https://github.com/incu6us/goimports-reviser) — Imports sorting and code formatting tool ☆`711`

### Generate Tools

*   [xuri/xgen (⭐405)](https://github.com/xuri/xgen) — XSD parser and code generator ☆`406`
*   [kazhuravlev/options-gen (⭐107)](https://github.com/kazhuravlev/options-gen) — Codegen for functional options in go projects ☆`103`
*   [g4s8/envdoc (⭐94)](https://github.com/g4s8/envdoc) — Go tool to generate documentation for environment variables ☆`94`

### Go Tools

*   [go-swagger/go-swagger (⭐9.9k)](https://github.com/go-swagger/go-swagger) — Swagger 2.0 implementation for go ☆`9,940`
*   [ondrajz/go-callvis (⭐6.5k)](https://github.com/ondrajz/go-callvis) — Visualize call graph of a Go program using Graphviz ☆`6,452`
*   [Zxilly/go-size-analyzer (⭐2k)](https://github.com/Zxilly/go-size-analyzer) — Analyze compiled Go binary size ☆`1,970`
*   [pointlander/peg (⭐1.1k)](https://github.com/pointlander/peg) — PEG parser generator for Go ☆`1,100`
*   [janpfeifer/gonb (⭐977)](https://github.com/janpfeifer/gonb) — Go notebook kernel for Jupyter ☆`980`
*   [safedep/vet (⭐942)](https://github.com/safedep/vet) — Protect against malicious open source packages ☆`952`
*   [alajmo/sake (⭐743)](https://github.com/alajmo/sake) — Task runner for local and remote hosts ☆`743`
*   [goccmack/gocc (⭐657)](https://github.com/goccmack/gocc) — Parser and scanner generator ☆`657`
*   [moshebe/gebug (⭐634)](https://github.com/moshebe/gebug) — Debug Dockerized Go apps ☆`634`
*   [edwingeng/hotswap (⭐418)](https://github.com/edwingeng/hotswap) — Hot reload Go code without restart ☆`421`
*   [iyashjayesh/monigo (⭐396)](https://github.com/iyashjayesh/monigo) — Performance monitoring library ☆`397`
*   [becheran/roumon (⭐234)](https://github.com/becheran/roumon) — Universal goroutine monitor using pprof and termui ☆`234`
*   [bitfield/gotestdox (⭐191)](https://github.com/bitfield/gotestdox) — A tool for formatting Go test results as readable documentation ☆`193`
*   [ahmedakef/gotutor (⭐74)](https://github.com/ahmedakef/gotutor) — Online Go Debugger & Visualizer ☆`74`
*   [bobg/decouple (⭐35)](https://github.com/bobg/decouple) — find overspecified function parameters in Go code ☆`35`
*   [bobg/modver (⭐21)](https://github.com/bobg/modver) — a tool that helps you obey semantic versioning rules in your Go module ☆`21`
*   [dustinblackman/gomodrun (⭐38)](https://github.com/dustinblackman/gomodrun) — Run binaries from go.mod ☆`38`

## Hardware & IoT

### Hardware

*   [shirou/gopsutil (⭐12k)](https://github.com/shirou/gopsutil) — psutil for golang ☆`11,706`
*   [arduino/arduino-cli (⭐4.8k)](https://github.com/arduino/arduino-cli) — Arduino command line tool ☆`4,804`
*   [jaypipes/ghw (⭐1.8k)](https://github.com/jaypipes/ghw) — Go HardWare discovery/inspection library ☆`1,824`
*   [zcalusic/sysinfo (⭐575)](https://github.com/zcalusic/sysinfo) — Linux system information library ☆`575`

### IoT

*   [hybridgroup/gobot (⭐9.4k)](https://github.com/hybridgroup/gobot) — Robotics and IoT framework ☆`9,380`
*   [lf-edge/ekuiper (⭐1.7k)](https://github.com/lf-edge/ekuiper) — Lightweight data stream processing engine for IoT edge ☆`1,678`
*   [rulego/rulego (⭐1.4k)](https://github.com/rulego/rulego) — Lightweight rule engine framework ☆`1,430`
*   [Edgenesis/shifu (⭐1.4k)](https://github.com/Edgenesis/shifu) — Kubernetes-native IoT gateway ☆`1,401`
*   [e154/smart-home (⭐96)](https://github.com/e154/smart-home) — software package for automation ☆`96`
*   [maxatome/go-vitotrol (⭐23)](https://github.com/maxatome/go-vitotrol) — golang client library to Viessmann Vitotrol web service ☆`23`

## Networking

### Consensus

*   [hashicorp/raft (⭐8.9k)](https://github.com/hashicorp/raft) — Golang implementation of the Raft consensus protocol ☆`8,927`
*   [lni/dragonboat (⭐5.3k)](https://github.com/lni/dragonboat) — Multi-group Raft consensus library ☆`5,298`
*   [etcd-io/raft (⭐984)](https://github.com/etcd-io/raft) — Raft library for maintaining a replicated state machine ☆`985`
*   [vadiminshakov/committer (⭐40)](https://github.com/vadiminshakov/committer) — 2PC and 3PC protocols for Go ☆`40`

### DNS

*   [miekg/dns (⭐8.6k)](https://github.com/miekg/dns) — DNS library in Go ☆`8,633`
*   [0xERR0R/blocky (⭐6.1k)](https://github.com/0xERR0R/blocky) — DNS ad-blocker for local networks ☆`6,118`
*   [hashicorp/mdns (⭐1.3k)](https://github.com/hashicorp/mdns) — Simple mDNS client/server library in Golang ☆`1,334`
*   [semihalev/sdns (⭐1k)](https://github.com/semihalev/sdns) — High-performance recursive DNS ☆`1,028`
*   [mosajjal/dnsmonster (⭐350)](https://github.com/mosajjal/dnsmonster) — Passive DNS Capture and Monitoring Toolkit ☆`350`
*   [joeig/go-powerdns (⭐103)](https://github.com/joeig/go-powerdns) — PowerDNS API client for Go (community project) ☆`103`

### Distributed Utilities

*   [luraproject/lura (⭐6.7k)](https://github.com/luraproject/lura) — Ultra-performant API gateway ☆`6,736`
*   [chrislusf/gleam (⭐3.6k)](https://github.com/chrislusf/gleam) — Distributed map/reduce in Go ☆`3,554`
*   [bsm/redislock (⭐1.7k)](https://github.com/bsm/redislock) — Simplified distributed locking implementation using Redis ☆`1,737`
*   [k8gb-io/k8gb (⭐1.1k)](https://github.com/k8gb-io/k8gb) — A cloud native Kubernetes Global Balancer ☆`1,145`
*   [temporalio/sdk-go (⭐826)](https://github.com/temporalio/sdk-go) — Temporal Go SDK ☆`832`
*   [AppsFlyer/go-sundheit (⭐560)](https://github.com/AppsFlyer/go-sundheit) — Health checks library for Go ☆`560`
*   [tarmac-project/tarmac (⭐342)](https://github.com/tarmac-project/tarmac) — Functions as Monolith or Microservices ☆`342`
*   [italolelis/outboxer (⭐166)](https://github.com/italolelis/outboxer) — A library that implements the outboxer pattern in go ☆`166`
*   [capillariesio/capillaries (⭐69)](https://github.com/capillariesio/capillaries) — Distributed batch data processing framework ☆`69`
*   [svcavallar/celeriac.v1 (⭐76)](https://github.com/svcavallar/celeriac.v1) — Celery client for Go ☆`76`
*   [sanketplus/go-mysql-lock (⭐66)](https://github.com/sanketplus/go-mysql-lock) — MySQL Backed Locking Primitive ☆`66`
*   [pdupub/go-pdu (⭐49)](https://github.com/pdupub/go-pdu) — An PDU implementation in Go ☆`49`
*   [mbrostami/consistenthash (⭐31)](https://github.com/mbrostami/consistenthash) — Consistent hashing implementation ☆`31`

### HTTP & Proxy

*   [valyala/fasthttp (⭐23k)](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,261`
*   [elazarl/goproxy (⭐6.6k)](https://github.com/elazarl/goproxy) — An HTTP proxy library for Go ☆`6,610`
*   [wzshiming/httpproxy (⭐32)](https://github.com/wzshiming/httpproxy) — HTTP proxy handler and dialer ☆`31`

### HTTP Clients

*   [go-resty/resty (⭐12k)](https://github.com/go-resty/resty) — Simple HTTP, REST, and SSE client library for Go ☆`11,547`
*   [imroc/req (⭐4.8k)](https://github.com/imroc/req) — Simple Go HTTP client with Black Magic ☆`4,758`
*   [gojek/heimdall (⭐2.7k)](https://github.com/gojek/heimdall) — An enhanced HTTP client for Go ☆`2,699`
*   [hashicorp/go-retryablehttp (⭐2.3k)](https://github.com/hashicorp/go-retryablehttp) — Retryable HTTP client in Go ☆`2,275`
*   [levigross/grequests (⭐2.2k)](https://github.com/levigross/grequests) — A Go "clone" of the great and famous Requests library ☆`2,184`
*   [dghubble/sling (⭐1.7k)](https://github.com/dghubble/sling) — A Go HTTP client library for creating and sending API requests ☆`1,717`
*   [earthboundkid/requests (⭐1.7k)](https://github.com/earthboundkid/requests) — HTTP requests for Gophers ☆`1,665`
*   [bogdanfinn/tls-client (⭐1.4k)](https://github.com/bogdanfinn/tls-client) — HTTP client with TLS fingerprint spoofing ☆`1,466`
*   [Noooste/azuretls-client (⭐422)](https://github.com/Noooste/azuretls-client) — HTTP client to spoof TLS/JA3 fingerprint ☆`426`
*   [monaco-io/request (⭐295)](https://github.com/monaco-io/request) — go request, go http client ☆`295`
*   [opus-domini/fast-shot (⭐95)](https://github.com/opus-domini/fast-shot) — Fluent HTTP client for Go ☆`116`
*   [go-zoox/fetch (⭐89)](https://github.com/go-zoox/fetch) — Powerful HTTP client for Go ☆`89`
*   [NdoleStudio/go-otelroundtripper (⭐85)](https://github.com/NdoleStudio/go-otelroundtripper) — OpenTelemetry metrics for HTTP clients ☆`85`
*   [rezmoss/axios4go (⭐30)](https://github.com/rezmoss/axios4go) — Axios-inspired HTTP client ☆`32`

### Servers

*   [caddyserver/caddy (⭐70k)](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`70,194`
*   [pocketbase/pocketbase (⭐56k)](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`56,223`
*   [etcd-io/etcd (⭐51k)](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`51,621`
*   [drakkan/sftpgo (⭐12k)](https://github.com/drakkan/sftpgo) — Full-featured SFTP/FTP/HTTP server ☆`11,696`
*   [adnanh/webhook (⭐12k)](https://github.com/adnanh/webhook) — Lightweight webhook server ☆`11,596`
*   [roadrunner-server/roadrunner (⭐8.4k)](https://github.com/roadrunner-server/roadrunner) — High-performance PHP application server ☆`8,396`
*   [easegress-io/easegress (⭐5.9k)](https://github.com/easegress-io/easegress) — A Cloud Native traffic orchestration system ☆`5,866`
*   [charmbracelet/wish (⭐4.9k)](https://github.com/charmbracelet/wish) — Make SSH apps, just like that! ☆`4,915`
*   [flipt-io/flipt (⭐4.7k)](https://github.com/flipt-io/flipt) — Enterprise-ready, Git native feature management solution ☆`4,717`
*   [getfider/fider (⭐4.1k)](https://github.com/getfider/fider) — Open platform to collect and prioritize feedback ☆`4,099`
*   [xyproto/algernon (⭐3k)](https://github.com/xyproto/algernon) — Web server with Lua and Markdown ☆`2,988`
*   [openflagr/flagr (⭐2.6k)](https://github.com/openflagr/flagr) — Feature flagging and A/B testing ☆`2,573`
*   [thomaspoignant/go-feature-flag (⭐1.9k)](https://github.com/thomaspoignant/go-feature-flag) — Open source feature flag solution ☆`1,939`
*   [msoap/shell2http (⭐1.5k)](https://github.com/msoap/shell2http) — Executing shell commands via HTTP server ☆`1,471`
*   [openrundev/openrun (⭐736)](https://github.com/openrundev/openrun) — Open source Cloud Run alternative ☆`796`
*   [webhookx-io/webhookx (⭐270)](https://github.com/webhookx-io/webhookx) — The Next-Generation Webhooks Gateway. ☆`272`
*   [baalimago/wd-41 (⭐151)](https://github.com/baalimago/wd-41) — Web-Development 41, a static web server with live-reload ☆`151`
*   [blind-oracle/cortex-tenant (⭐132)](https://github.com/blind-oracle/cortex-tenant) — Prometheus proxy with tenant ID injection ☆`133`
*   [rekby/lets-proxy2 (⭐101)](https://github.com/rekby/lets-proxy2) — Reverse proxy with auto TLS ☆`101`
*   [42atomys/webhooked (⭐42)](https://github.com/42atomys/webhooked) — A webhook receiver on steroids. ☆`42`

### Network Utilities

*   [fortio/fortio (⭐3.7k)](https://github.com/fortio/fortio) — Load testing and echo server ☆`3,677`
*   [hashicorp/go-getter (⭐1.8k)](https://github.com/hashicorp/go-getter) — Download files from URLs ☆`1,806`
*   [TimothyYe/godns (⭐1.7k)](https://github.com/TimothyYe/godns) — Dynamic DNS client for multiple providers ☆`1,736`
*   [cavaliergopher/grab (⭐1.5k)](https://github.com/cavaliergopher/grab) — Download manager package ☆`1,472`
*   [schollz/peerdiscovery (⭐668)](https://github.com/schollz/peerdiscovery) — Cross-platform local peer discovery ☆`668`
*   [fclairamb/ftpserverlib (⭐462)](https://github.com/fclairamb/ftpserverlib) — FTP server library for Go ☆`463`
*   [skibish/ddns (⭐267)](https://github.com/skibish/ddns) — Personal DDNS client with Digital Ocean Networking DNS as backend. ☆`267`
*   [assafmo/joincap (⭐220)](https://github.com/assafmo/joincap) — Merge pcap files ☆`221`
*   [c-robinson/iplib (⭐152)](https://github.com/c-robinson/iplib) — A library for working with IP addresses and networks in Go ☆`151`
*   [gaissmai/bart (⭐117)](https://github.com/gaissmai/bart) — Balanced routing table ☆`117`
*   [alegrey91/fwdctl (⭐72)](https://github.com/alegrey91/fwdctl) — Manage IPTables forwards via CLI ☆`72`

### P2P & Torrent

*   [anacrolix/torrent (⭐6k)](https://github.com/anacrolix/torrent) — Full-featured BitTorrent client package and utilities ☆`5,970`
*   [dragonflyoss/dragonfly (⭐3k)](https://github.com/dragonflyoss/dragonfly) — P2P-based container image distribution ☆`3,033`
*   [cenkalti/rain (⭐1.1k)](https://github.com/cenkalti/rain) — BitTorrent client and library in Go ☆`1,111`
*   [anacrolix/dht (⭐348)](https://github.com/anacrolix/dht) — DHT for BitTorrent ☆`348`

### Protocols

*   [pion/webrtc (⭐16k)](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,051`
*   [quic-go/quic-go (⭐11k)](https://github.com/quic-go/quic-go) — A production-ready QUIC implementation in pure Go ☆`11,443`
*   [google/gopacket (⭐6.7k)](https://github.com/google/gopacket) — Provides packet processing capabilities for Go ☆`6,747`
*   [osrg/gobgp (⭐4k)](https://github.com/osrg/gobgp) — BGP implemented in the Go Programming Language ☆`3,985`
*   [lxzan/gws (⭐1.7k)](https://github.com/lxzan/gws) — Fast websocket server and client ☆`1,705`
*   [gosnmp/gosnmp (⭐1.2k)](https://github.com/gosnmp/gosnmp) — An SNMP library written in Go ☆`1,239`
*   [bluenviron/gortsplib (⭐889)](https://github.com/bluenviron/gortsplib) — RTSP client and server library for the Go programming language ☆`892`
*   [ccding/go-stun (⭐718)](https://github.com/ccding/go-stun) — A go implementation of the STUN client (RFC 3489 and RFC 5389) ☆`718`
*   [google/gnxi (⭐283)](https://github.com/google/gnxi) — gNXI Tools - gRPC Network Management/Operations Interface Tools ☆`282`
*   [jeroenrinzema/psql-wire (⭐216)](https://github.com/jeroenrinzema/psql-wire) — PostgreSQL wire protocol for Go ☆`217`
*   [jimlambrt/gldap (⭐118)](https://github.com/jimlambrt/gldap) — Build LDAP services w/ Go ☆`118`
*   [soypat/natiu-mqtt (⭐102)](https://github.com/soypat/natiu-mqtt) — Extensible MQTT for embedded systems ☆`104`

### RPC

*   [grpc/grpc-go (⭐23k)](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,787`
*   [lesismal/arpc (⭐1.1k)](https://github.com/lesismal/arpc) — Two-way RPC with broadcast support ☆`1,090`
*   [ybbus/jsonrpc (⭐369)](https://github.com/ybbus/jsonrpc) — A simple go implementation of json rpc 2.0 client over http ☆`369`
*   [osamingo/jsonrpc (⭐193)](https://github.com/osamingo/jsonrpc) — The jsonrpc package helps implement of JSON-RPC 2.0 ☆`192`

### SSH & SFTP

*   [gliderlabs/ssh (⭐4.1k)](https://github.com/gliderlabs/ssh) — Easy SSH servers in Golang ☆`4,087`
*   [pkg/sftp (⭐1.6k)](https://github.com/pkg/sftp) — SFTP support for the go.crypto/ssh package ☆`1,634`
*   [masterzen/winrm (⭐459)](https://github.com/masterzen/winrm) — Windows remote command library ☆`460`

### TCP/UDP Frameworks

*   [panjf2000/gnet (⭐11k)](https://github.com/panjf2000/gnet) — High-performance event-loop network ☆`11,089`
*   [xtaci/kcp-go (⭐4.5k)](https://github.com/xtaci/kcp-go) — A crypto-secure Reliable-UDP library for Golang with FEC support. ☆`4,493`
*   [cloudwego/netpoll (⭐4.5k)](https://github.com/cloudwego/netpoll) — High-performance I/O framework ☆`4,529`
*   [lesismal/nbio (⭐2.7k)](https://github.com/lesismal/nbio) — High-performance network library ☆`2,700`
*   [xtaci/gaio (⭐1k)](https://github.com/xtaci/gaio) — High-performance, minimalist async-io (proactor) networking for Golang. ☆`1,080`
*   [cheng-zhongliang/event (⭐119)](https://github.com/cheng-zhongliang/event) — Simple I/O event notification library wirtten in Golang ☆`119`
*   [fish-tennis/gnet (⭐26)](https://github.com/fish-tennis/gnet) — high performance net library for game server ☆`26`

### VPN & Tunneling

*   [cloudflare/cloudflared (⭐13k)](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`13,167`
*   [xjasonlyu/tun2socks (⭐4.9k)](https://github.com/xjasonlyu/tun2socks) — TUN to SOCKS proxy ☆`4,909`
*   [songgao/water (⭐2.1k)](https://github.com/songgao/water) — A simple TUN/TAP library written in native Go. ☆`2,138`
*   [NodePassProject/nodepass (⭐2.1k)](https://github.com/NodePassProject/nodepass) — Secure TCP/UDP tunneling with TLS ☆`2,068`

## Queues & Pub/Sub

### Brokers

*   [nats-io/nats-server (⭐19k)](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`19,169`
*   [emitter-io/emitter (⭐4k)](https://github.com/emitter-io/emitter) — High-performance pub/sub broker ☆`4,001`
*   [mochi-mqtt/server (⭐1.8k)](https://github.com/mochi-mqtt/server) — Embeddable MQTT v5 broker ☆`1,790`

### Clients & Libraries

*   [hibiken/asynq (⭐13k)](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`12,904`
*   [IBM/sarama (⭐12k)](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,429`
*   [centrifugal/centrifugo (⭐9.9k)](https://github.com/centrifugal/centrifugo) — Scalable real-time messaging server ☆`9,968`
*   [ThreeDotsLabs/watermill (⭐9.5k)](https://github.com/ThreeDotsLabs/watermill) — Building event-driven applications the easy way in Go. ☆`9,534`
*   [appleboy/gorush (⭐8.7k)](https://github.com/appleboy/gorush) — A push notification server written in Go (Golang). ☆`8,689`
*   [RichardKnop/machinery (⭐7.9k)](https://github.com/RichardKnop/machinery) — Async task queue with message passing ☆`7,949`
*   [nats-io/nats.go (⭐6.4k)](https://github.com/nats-io/nats.go) — Golang client for NATS, the cloud native messaging system. ☆`6,447`
*   [dunglas/mercure (⭐5.2k)](https://github.com/dunglas/mercure) — Server-Sent Events hub ☆`5,184`
*   [confluentinc/confluent-kafka-go (⭐5.1k)](https://github.com/confluentinc/confluent-kafka-go) — Confluent's Apache Kafka Golang client ☆`5,104`
*   [olahol/melody (⭐4.1k)](https://github.com/olahol/melody) — Minimalist websocket framework for Go ☆`4,066`
*   [sideshow/apns2 (⭐3.2k)](https://github.com/sideshow/apns2) — Apple Push Notification Service ☆`3,162`
*   [lovoo/goka (⭐2.5k)](https://github.com/lovoo/goka) — Kafka stream processing library ☆`2,507`
*   [rabbitmq/amqp091-go (⭐2k)](https://github.com/rabbitmq/amqp091-go) — An AMQP 0-9-1 Go client maintained by the RabbitMQ team ☆`1,970`
*   [asaskevich/EventBus (⭐2k)](https://github.com/asaskevich/EventBus) — \[Go] Lightweight eventbus with async compatibility for Go ☆`1,960`
*   [containrrr/shoutrrr (⭐1.5k)](https://github.com/containrrr/shoutrrr) — Notification library for gophers and their furry friends. ☆`1,506`
*   [pebbe/zmq4 (⭐1.2k)](https://github.com/pebbe/zmq4) — A Go interface to ZeroMQ version 4 ☆`1,246`
*   [timbray/quamina (⭐476)](https://github.com/timbray/quamina) — Fast pattern-matching library ☆`478`
*   [cskr/pubsub (⭐447)](https://github.com/cskr/pubsub) — A simple pubsub package for go. ☆`448`
*   [jandelgado/rabtap (⭐278)](https://github.com/jandelgado/rabtap) — RabbitMQ wire tap and swiss army knife ☆`278`
*   [mehdihadeli/Go-MediatR (⭐274)](https://github.com/mehdihadeli/Go-MediatR) — Mediator pattern for CQRS ☆`274`
*   [goptics/varmq (⭐176)](https://github.com/goptics/varmq) — Zero-dep message queue library ☆`178`
*   [robinjoseph08/redisqueue (⭐139)](https://github.com/robinjoseph08/redisqueue) — Redis streams producer and consumer ☆`139`
*   [oagudo/outbox (⭐116)](https://github.com/oagudo/outbox) — Transactional outbox pattern ☆`118`
*   [hyperonym/ratus (⭐124)](https://github.com/hyperonym/ratus) — RESTful async task queue server ☆`124`
*   [furdarius/rabbitroutine (⭐114)](https://github.com/furdarius/rabbitroutine) — RabbitMQ auto-reconnect library ☆`114`
*   [dailymotion/oplog (⭐110)](https://github.com/dailymotion/oplog) — A generic oplog/replication system for microservices ☆`110`
*   [jirenius/go-res (⭐67)](https://github.com/jirenius/go-res) — RES Service protocol library for Go ☆`67`
*   [Protocol-Lattice/GoEventBus (⭐53)](https://github.com/Protocol-Lattice/GoEventBus) — A lock-free, ultra-fast event bus for Go ☆`57`
*   [SchwarzDigits/hypermatch (⭐33)](https://github.com/SchwarzDigits/hypermatch) — High-performance rule matching ☆`33`

## Science

*   [gonum/gonum (⭐8.3k)](https://github.com/gonum/gonum) — Numeric libraries for Go ☆`8,311`
*   [gonum/plot (⭐2.9k)](https://github.com/gonum/plot) — Plotting and visualization ☆`2,940`
*   [paulmach/orb (⭐1.1k)](https://github.com/paulmach/orb) — 2D geometry types and utilities ☆`1,090`
*   [madelynnblue/go-dsp (⭐904)](https://github.com/madelynnblue/go-dsp) — Digital Signal Processing for Go ☆`907`
*   [bebop/poly (⭐721)](https://github.com/bebop/poly) — Synthetic biology library for Go ☆`720`
*   [hmdsefi/gograph (⭐105)](https://github.com/hmdsefi/gograph) — Generic graph algorithms library ☆`106`
*   [nikolaydubina/jsonl-graph (⭐77)](https://github.com/nikolaydubina/jsonl-graph) — JSONL Graph Tools ☆`77`
*   [claygod/PiHex (⭐20)](https://github.com/claygod/PiHex) — Generate hexadecimal Pi digits ☆`20`

## Scripting

### Embeddable Languages

*   [php/frankenphp (⭐11k)](https://github.com/php/frankenphp) — The modern PHP app server ☆`10,790`
*   [expr-lang/expr (⭐7.7k)](https://github.com/expr-lang/expr) — Expression evaluation for Go ☆`7,692`
*   [yuin/gopher-lua (⭐6.8k)](https://github.com/yuin/gopher-lua) — Lua VM and compiler in Go ☆`6,852`
*   [dop251/goja (⭐6.7k)](https://github.com/dop251/goja) — ECMAScript engine in pure Go ☆`6,743`
*   [d5/tengo (⭐3.8k)](https://github.com/d5/tengo) — Fast script language for Go ☆`3,774`
*   [Shopify/go-lua (⭐3.4k)](https://github.com/Shopify/go-lua) — Lua VM in Go ☆`3,414`
*   [google/cel-go (⭐2.9k)](https://github.com/google/cel-go) — Common Expression Language for Go ☆`2,875`
*   [google/starlark-go (⭐2.6k)](https://github.com/google/starlark-go) — Starlark config language in Go ☆`2,635`
*   [metacall/core (⭐1.8k)](https://github.com/metacall/core) — Polyglot programming runtime ☆`1,759`
*   [wa-lang/wa (⭐1.7k)](https://github.com/wa-lang/wa) — The Wa Programming Language ☆`1,754`
*   [mattn/anko (⭐1.6k)](https://github.com/mattn/anko) — Scriptable interpreter in Go ☆`1,558`
*   [PaesslerAG/gval (⭐810)](https://github.com/PaesslerAG/gval) — Expression evaluation in Go ☆`810`
*   [ichiban/prolog (⭐706)](https://github.com/ichiban/prolog) — Prolog scripting engine for Go ☆`706`
*   [aarzilli/golua (⭐689)](https://github.com/aarzilli/golua) — Lua C API bindings for Go ☆`689`
*   [1set/starlet (⭐40)](https://github.com/1set/starlet) — Starlark wrapper with batteries ☆`40`

### Code Generators

*   [oapi-codegen/oapi-codegen (⭐8k)](https://github.com/oapi-codegen/oapi-codegen) — Generate Go code from OpenAPI 3 specs ☆`8,075`
*   [dave/jennifer (⭐3.6k)](https://github.com/dave/jennifer) — Code generator for Go ☆`3,602`
*   [hexdigest/gowrap (⭐1.3k)](https://github.com/hexdigest/gowrap) — Generate interface decorators ☆`1,310`
*   [awalterschulze/goderive (⭐1.3k)](https://github.com/awalterschulze/goderive) — Generate mundane Go functions ☆`1,266`
*   [abice/go-enum (⭐917)](https://github.com/abice/go-enum) — Enum generator for Go ☆`923`
*   [jmattheis/goverter (⭐811)](https://github.com/jmattheis/goverter) — Generate type-safe converters ☆`815`
*   [rjeczalik/interfaces (⭐432)](https://github.com/rjeczalik/interfaces) — Code generation tools for Go ☆`432`
*   [switchupcb/copygen (⭐399)](https://github.com/switchupcb/copygen) — Copy values between types ☆`399`
*   [reedom/convergen (⭐48)](https://github.com/reedom/convergen) — Type-to-type copy code generator ☆`48`

## Security

### Certificates

*   [go-acme/lego (⭐9.2k)](https://github.com/go-acme/lego) — Let's Encrypt/ACME client and library written in Go ☆`9,264`
*   [caddyserver/certmagic (⭐5.4k)](https://github.com/caddyserver/certmagic) — Automatic HTTPS certificate management ☆`5,442`
*   [tg123/go-htpasswd (⭐46)](https://github.com/tg123/go-htpasswd) — Apache htpasswd Parser for Go. ☆`46`
*   [adrianosela/sslmgr (⭐30)](https://github.com/adrianosela/sslmgr) — SSL certificate abstraction ☆`31`

### Cryptography

*   [FiloSottile/age (⭐21k)](https://github.com/FiloSottile/age) — Simple encryption tool ☆`21,351`
*   [authzed/spicedb (⭐6.4k)](https://github.com/authzed/spicedb) — Zanzibar-inspired permissions DB ☆`6,439`
*   [awnumar/memguard (⭐2.7k)](https://github.com/awnumar/memguard) — Software sandbox for storage of sensitive information in memory. ☆`2,713`
*   [cossacklabs/themis (⭐1.9k)](https://github.com/cossacklabs/themis) — Cryptographic framework for data protection ☆`1,950`
*   [dromara/dongle (⭐1.1k)](https://github.com/dromara/dongle) — A simple, semantic and developer-friendly crypto package for golang ☆`1,098`
*   [anatol/booster (⭐620)](https://github.com/anatol/booster) — Fast and secure initramfs generator ☆`620`
*   [kevinburke/nacl (⭐552)](https://github.com/kevinburke/nacl) — Pure Go implementation of the NaCL set of API's ☆`552`
*   [ssh-vault/ssh-vault (⭐494)](https://github.com/ssh-vault/ssh-vault) — encrypt/decrypt using ssh keys ☆`493`
*   [number571/go-peer (⭐316)](https://github.com/number571/go-peer) — Secure decentralized networking ☆`316`
*   [lingrino/vaku (⭐158)](https://github.com/lingrino/vaku) — Extended Vault API and CLI ☆`158`
*   [anatol/luks.go (⭐95)](https://github.com/anatol/luks.go) — Pure Golang library to manage LUKS partitions ☆`95`
*   [zitadel/passwap (⭐72)](https://github.com/zitadel/passwap) — Unified password hashing ☆`72`
*   [rsjethani/secret (⭐32)](https://github.com/rsjethani/secret) — Prevent your secrets from leaking into logs, std\* etc. ☆`32`
*   [andskur/argon2-hashing (⭐25)](https://github.com/andskur/argon2-hashing) — Argon2 password hashing ☆`25`

### WAF & Protection

*   [Ullaakut/cameradar (⭐4.9k)](https://github.com/Ullaakut/cameradar) — Cameradar hacks its way into RTSP videosurveillance cameras ☆`4,868`
*   [corazawaf/coraza (⭐3.3k)](https://github.com/corazawaf/coraza) — ModSecurity-compatible WAF in Go ☆`3,294`
*   [mojocn/base64Captcha (⭐2.3k)](https://github.com/mojocn/base64Captcha) — captcha of base64 image string ☆`2,347`
*   [unrolled/secure (⭐2.3k)](https://github.com/unrolled/secure) — HTTP middleware for Go that facilitates some quick security wins. ☆`2,334`
*   [mariocandela/beelzebub (⭐1.8k)](https://github.com/mariocandela/beelzebub) — AI-powered honeypot framework ☆`1,844`
*   [cossacklabs/acra (⭐1.5k)](https://github.com/cossacklabs/acra) — Database security proxy ☆`1,453`
*   [securitybunker/databunker (⭐1.4k)](https://github.com/securitybunker/databunker) — Secure vault for PII/PHI/KYC records ☆`1,384`
*   [hillu/go-yara (⭐385)](https://github.com/hillu/go-yara) — Go bindings for YARA ☆`385`
*   [teler-sh/teler-waf (⭐399)](https://github.com/teler-sh/teler-waf) — HTTP middleware for WAF ☆`399`
*   [steambap/captcha (⭐161)](https://github.com/steambap/captcha) — Easy captcha library ☆`162`

### Zero Trust

*   [sigstore/cosign (⭐5.6k)](https://github.com/sigstore/cosign) — Code signing and transparency for containers and binaries ☆`5,667`
*   [openziti/ziti (⭐3.9k)](https://github.com/openziti/ziti) — Zero trust networking platform ☆`3,883`
*   [spiffe/spire (⭐2.2k)](https://github.com/spiffe/spire) — The SPIFFE Runtime Environment ☆`2,211`
*   [philips-labs/spiffe-vault (⭐97)](https://github.com/philips-labs/spiffe-vault) — Integrates Spiffe and Vault to have secretless authentication ☆`97`

## Testing & Quality

### Benchmarks

*   [smallnest/go-web-framework-benchmark (⭐2.1k)](https://github.com/smallnest/go-web-framework-benchmark) — Web framework benchmarks ☆`2,137`
*   [alecthomas/go\_serialization\_benchmarks (⭐1.6k)](https://github.com/alecthomas/go_serialization_benchmarks) — Serialization benchmarks for Go ☆`1,621`
*   [SimonWaldherr/golang-benchmarks (⭐142)](https://github.com/SimonWaldherr/golang-benchmarks) — Go(lang) benchmarks - (measure the speed of golang) ☆`142`
*   [feyeleanor/gospeed (⭐126)](https://github.com/feyeleanor/gospeed) — Go language construct benchmarks ☆`126`
*   [nikolaydubina/go-ml-benchmarks (⭐32)](https://github.com/nikolaydubina/go-ml-benchmarks) — Benchmarks of machine learning inference for Go ☆`32`

### Code Analysis

*   [golangci/golangci-lint (⭐18k)](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`18,530`
*   [boyter/scc (⭐8.1k)](https://github.com/boyter/scc) — Fast code counter and stats ☆`8,051`
*   [mgechev/revive (⭐5.4k)](https://github.com/mgechev/revive) — Fast, extensible Go linter ☆`5,396`
*   [kisielk/errcheck (⭐2.5k)](https://github.com/kisielk/errcheck) — errcheck checks that you checked errors. ☆`2,473`
*   [go-critic/go-critic (⭐2k)](https://github.com/go-critic/go-critic) — The most opinionated Go source code linter for code audit. ☆`2,035`
*   [daveshanley/vacuum (⭐1k)](https://github.com/daveshanley/vacuum) — Fast OpenAPI linter ☆`1,008`
*   [presmihaylov/todocheck (⭐437)](https://github.com/presmihaylov/todocheck) — Analyser for TODO comments ☆`436`
*   [mdempsky/unconvert (⭐388)](https://github.com/mdempsky/unconvert) — Remove unnecessary type conversions ☆`388`
*   [tomarrell/wrapcheck (⭐358)](https://github.com/tomarrell/wrapcheck) — Check errors are wrapped ☆`359`
*   [mibk/dupl (⭐362)](https://github.com/mibk/dupl) — Code clone detection tool ☆`363`
*   [shurcooL/gostatus (⭐245)](https://github.com/shurcooL/gostatus) — Show status of Go repositories ☆`245`
*   [Antonboom/testifylint (⭐164)](https://github.com/Antonboom/testifylint) — Linter for testify usage ☆`163`
*   [Crocmagnon/fatcontext (⭐65)](https://github.com/Crocmagnon/fatcontext) — Detect nested contexts in loops ☆`67`
*   [antham/ghokin (⭐51)](https://github.com/antham/ghokin) — Parallelized Gherkin formatter ☆`52`
*   [asticode/go-astitodo (⭐66)](https://github.com/asticode/go-astitodo) — Parse TODOs in your GO code ☆`66`
*   [sashamelentyev/usestdlibvars (⭐47)](https://github.com/sashamelentyev/usestdlibvars) — Linter for stdlib variables usage ☆`47`
*   [borovikovd/gomsort (⭐26)](https://github.com/borovikovd/gomsort) — Go msort - linter that sorts methods ☆`26`

### Mock

*   [vektra/mockery (⭐7k)](https://github.com/vektra/mockery) — Mock code autogenerator for Go ☆`6,997`
*   [DATA-DOG/go-sqlmock (⭐6.5k)](https://github.com/DATA-DOG/go-sqlmock) — SQL mock driver for testing ☆`6,524`
*   [brianvoe/gofakeit (⭐5.3k)](https://github.com/brianvoe/gofakeit) — Random fake data generator written in go ☆`5,304`
*   [uber-go/mock (⭐3.3k)](https://github.com/uber-go/mock) — GoMock is a mocking framework for the Go programming language. ☆`3,265`
*   [SpectoLabs/hoverfly (⭐2.5k)](https://github.com/SpectoLabs/hoverfly) — API simulation and virtualization ☆`2,466`
*   [matryer/moq (⭐2.2k)](https://github.com/matryer/moq) — Interface mocking via go generate ☆`2,179`
*   [jarcoal/httpmock (⭐2.1k)](https://github.com/jarcoal/httpmock) — HTTP mocking for Go ☆`2,075`
*   [maxbrunsfeld/counterfeiter (⭐1.1k)](https://github.com/maxbrunsfeld/counterfeiter) — Generate type-safe test doubles ☆`1,120`
*   [gojuno/minimock (⭐745)](https://github.com/gojuno/minimock) — Powerful mock generator ☆`746`
*   [DATA-DOG/go-txdb (⭐742)](https://github.com/DATA-DOG/go-txdb) — Transaction-isolated SQL driver ☆`746`
*   [pashagolub/pgxmock (⭐559)](https://github.com/pashagolub/pgxmock) — pgx mock driver for testing ☆`561`
*   [xhd2015/xgo (⭐429)](https://github.com/xhd2015/xgo) — All-in-one Go testing library ☆`430`
*   [seborama/govcr (⭐196)](https://github.com/seborama/govcr) — Record and replay HTTP interactions ☆`196`
*   [mocktools/go-smtp-mock (⭐160)](https://github.com/mocktools/go-smtp-mock) — SMTP mock server for testing ☆`160`
*   [elgohr/go-localstack (⭐86)](https://github.com/elgohr/go-localstack) — Go wrapper for LocalStack ☆`85`

### Performance

*   [jaegertracing/jaeger (⭐22k)](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`22,471`
*   [pixie-io/pixie (⭐6.4k)](https://github.com/pixie-io/pixie) — Kubernetes-native observability ☆`6,354`
*   [arl/statsviz (⭐3.6k)](https://github.com/arl/statsviz) — Visualize Go runtime metrics ☆`3,623`
*   [nikolaydubina/go-instrument (⭐288)](https://github.com/nikolaydubina/go-instrument) — Add trace spans to Go functions ☆`288`
*   [joetifa2003/mm-go (⭐193)](https://github.com/joetifa2003/mm-go) — Manual memory management for Go ☆`193`

### Browser Automation

*   [chromedp/chromedp (⭐13k)](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`12,742`
*   [go-rod/rod (⭐6.6k)](https://github.com/go-rod/rod) — Chrome DevTools driver for scraping ☆`6,713`
*   [sensepost/gowitness (⭐4.2k)](https://github.com/sensepost/gowitness) — Web screenshot utility with Chrome ☆`4,174`
*   [playwright-community/playwright-go (⭐3.2k)](https://github.com/playwright-community/playwright-go) — Browser automation for Chromium, Firefox, WebKit ☆`3,202`
*   [mafredri/cdp (⭐780)](https://github.com/mafredri/cdp) — Chrome DevTools Protocol bindings ☆`784`

### Testing Frameworks

*   [stretchr/testify (⭐26k)](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`25,862`
*   [keploy/keploy (⭐16k)](https://github.com/keploy/keploy) — API testing with auto mocks ☆`15,709`
*   [Shopify/toxiproxy (⭐12k)](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`11,848`
*   [testcontainers/testcontainers-go (⭐4.7k)](https://github.com/testcontainers/testcontainers-go) — Docker containers for integration tests ☆`4,686`
*   [google/go-cmp (⭐4.6k)](https://github.com/google/go-cmp) — Package for comparing Go values in tests ☆`4,596`
*   [gavv/httpexpect (⭐2.7k)](https://github.com/gavv/httpexpect) — End-to-end HTTP and REST API testing for Go. ☆`2,711`
*   [cucumber/godog (⭐2.6k)](https://github.com/cucumber/godog) — Cucumber for golang ☆`2,590`
*   [orlangure/gnomock (⭐1.5k)](https://github.com/orlangure/gnomock) — Test with ephemeral Docker containers ☆`1,481`
*   [dnaeon/go-vcr (⭐1.4k)](https://github.com/dnaeon/go-vcr) — Record and replay HTTP for tests ☆`1,359`
*   [go-testfixtures/testfixtures (⭐1.2k)](https://github.com/go-testfixtures/testfixtures) — Rails-like test fixtures for Go ☆`1,220`
*   [fergusstrange/embedded-postgres (⭐1.1k)](https://github.com/fergusstrange/embedded-postgres) — Embedded PostgreSQL for testing ☆`1,125`
*   [chapar-rest/chapar (⭐687)](https://github.com/chapar-rest/chapar) — API testing for HTTP and gRPC ☆`693`
*   [gotestyourself/gotest.tools (⭐577)](https://github.com/gotestyourself/gotest.tools) — Testing utilities for Go ☆`577`
*   [maxatome/go-testdeep (⭐457)](https://github.com/maxatome/go-testdeep) — Flexible deep comparison in tests ☆`462`
*   [appleboy/gofight (⭐445)](https://github.com/appleboy/gofight) — Testing API Handler written in Golang. ☆`445`
*   [viant/endly (⭐266)](https://github.com/viant/endly) — End to end functional test and automation framework ☆`266`
*   [ysmood/got (⭐269)](https://github.com/ysmood/got) — An enjoyable golang test framework. ☆`269`
*   [kinbiko/jsonassert (⭐140)](https://github.com/kinbiko/jsonassert) — JSON assertion library for tests ☆`140`
*   [adamluzsi/testcase (⭐127)](https://github.com/adamluzsi/testcase) — Opinionated testing framework ☆`127`
*   [earthboundkid/be (⭐131)](https://github.com/earthboundkid/be) — The Go test helper for minimalists ☆`131`
*   [corbym/gocrest (⭐106)](https://github.com/corbym/gocrest) — GoCrest - Hamcrest-like matchers for Go ☆`106`
*   [hedhyw/gherkingen (⭐92)](https://github.com/hedhyw/gherkingen) — Behaviour Driven Development tests generator for Golang ☆`94`
*   [madflojo/testcerts (⭐84)](https://github.com/madflojo/testcerts) — Generate test certificates on the fly ☆`84`
*   [viant/dsunit (⭐45)](https://github.com/viant/dsunit) — Datastore Testibility ☆`45`
*   [go-restit/restit (⭐55)](https://github.com/go-restit/restit) — A Go library help testing your RESTful API application ☆`55`
*   [rekby/fixenv (⭐33)](https://github.com/rekby/fixenv) — Pytest-inspired fixture caching for Go tests ☆`33`
*   [abecodes/dft (⭐19)](https://github.com/abecodes/dft) — Docker wrapper for testing ☆`19`

### Testing Utilities

*   [dvyukov/go-fuzz (⭐4.8k)](https://github.com/dvyukov/go-fuzz) — Randomized testing for Go ☆`4,846`
*   [pingcap/failpoint (⭐874)](https://github.com/pingcap/failpoint) — Failpoint implementation for Go ☆`872`

### Validation

*   [go-playground/validator (⭐20k)](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`19,716`
*   [gookit/validate (⭐1.1k)](https://github.com/gookit/validate) — Struct and data validation ☆`1,125`
*   [Oudwins/zog (⭐1.1k)](https://github.com/Oudwins/zog) — Zod-inspired schema validation ☆`1,141`
*   [faceair/jio (⭐125)](https://github.com/faceair/jio) — JSON schema validator like Joi ☆`125`
*   [twharmon/govalid (⭐112)](https://github.com/twharmon/govalid) — Struct validation using tags ☆`112`
*   [osamingo/checkdigit (⭐114)](https://github.com/osamingo/checkdigit) — Check digit algorithms ☆`114`
*   [marrow16/valix (⭐31)](https://github.com/marrow16/valix) — Request validation package ☆`31`
*   [tiendc/go-validator (⭐32)](https://github.com/tiendc/go-validator) — Intuitive validation library ☆`32`

## Text & NLP

### Formatters

*   [dustin/go-humanize (⭐4.8k)](https://github.com/dustin/go-humanize) — Human-friendly unit formatting ☆`4,806`
*   [neilotoole/sq (⭐2.4k)](https://github.com/neilotoole/sq) — SQL data wrangler ☆`2,433`
*   [bojanz/address (⭐82)](https://github.com/bojanz/address) — Address handling for Go ☆`82`

### Markup Languages

*   [BurntSushi/toml (⭐4.9k)](https://github.com/BurntSushi/toml) — TOML parser with reflection ☆`4,901`
*   [yuin/goldmark (⭐4.6k)](https://github.com/yuin/goldmark) — Markdown parser for Go ☆`4,605`
*   [JohannesKaufmann/html-to-markdown (⭐3.4k)](https://github.com/JohannesKaufmann/html-to-markdown) — Convert HTML to Markdown ☆`3,426`
*   [pelletier/go-toml (⭐1.9k)](https://github.com/pelletier/go-toml) — TOML library for Go ☆`1,905`
*   [antchfx/htmlquery (⭐781)](https://github.com/antchfx/htmlquery) — XPath for HTML queries ☆`781`
*   [clbanning/mxj (⭐633)](https://github.com/clbanning/mxj) — XML to/from map conversion ☆`632`
*   [mmalcek/bafi (⭐112)](https://github.com/mmalcek/bafi) — Universal format converter ☆`112`
*   [drewstinnett/gout (⭐18)](https://github.com/drewstinnett/gout) — Output Go objects in YAML, JSON ☆`18`

### Miscellaneous

*   [microcosm-cc/bluemonday (⭐3.6k)](https://github.com/microcosm-cc/bluemonday) — Fast HTML sanitizer for Go ☆`3,626`
*   [gosimple/slug (⭐1.3k)](https://github.com/gosimple/slug) — URL-friendly slugify ☆`1,320`
*   [pemistahl/lingua-go (⭐1.3k)](https://github.com/pemistahl/lingua-go) — Natural language detection ☆`1,319`
*   [arunsupe/semantic-grep (⭐1.2k)](https://github.com/arunsupe/semantic-grep) — Grep for similar words ☆`1,211`
*   [mattn/go-runewidth (⭐676)](https://github.com/mattn/go-runewidth) — Rune width for terminals ☆`679`
*   [hedhyw/rex (⭐210)](https://github.com/hedhyw/rex) — Flexible regex constructor ☆`210`
*   [IGLOU-EU/go-wildcard (⭐99)](https://github.com/IGLOU-EU/go-wildcard) — Fast wildcard matching ☆`99`
*   [JoshuaDoes/gofuckyourself (⭐68)](https://github.com/JoshuaDoes/gofuckyourself) — Swear filter for Go ☆`68`
*   [alexsergivan/transliterator (⭐46)](https://github.com/alexsergivan/transliterator) — Text transliterator ☆`46`
*   [Dynom/TySug (⭐19)](https://github.com/Dynom/TySug) — Typo suggestions with keyboard layout ☆`19`

### Morphological Analyzers

*   [nlpodyssey/spago (⭐1.8k)](https://github.com/nlpodyssey/spago) — ML and NLP library for Go ☆`1,849`
*   [ikawaha/kagome (⭐942)](https://github.com/ikawaha/kagome) — Japanese morphological analyzer ☆`943`
*   [afjoseph/RAKE.Go (⭐122)](https://github.com/afjoseph/RAKE.Go) — Rapid Keyword Extraction in Go ☆`123`
*   [jonreiter/govader (⭐52)](https://github.com/jonreiter/govader) — VADER sentiment analysis ☆`52`

### Parsers/Encoders/Decoders

*   [mvdan/sh (⭐8.5k)](https://github.com/mvdan/sh) — Shell parser and formatter ☆`8,470`
*   [mmcdole/gofeed (⭐2.8k)](https://github.com/mmcdole/gofeed) — Parse RSS, Atom, JSON feeds ☆`2,806`
*   [google/go-querystring (⭐2.1k)](https://github.com/google/go-querystring) — Encode structs to URL query strings ☆`2,132`
*   [olebedev/when (⭐1.5k)](https://github.com/olebedev/when) — Natural language date parser ☆`1,459`
*   [adrianmo/go-nmea (⭐257)](https://github.com/adrianmo/go-nmea) — NMEA sentence parser ☆`257`
*   [yassinebenaid/godump (⭐223)](https://github.com/yassinebenaid/godump) — Dump any Go variable ☆`224`
*   [editorconfig/editorconfig-core-go (⭐150)](https://github.com/editorconfig/editorconfig-core-go) — EditorConfig core in Go ☆`151`
*   [bzick/tokenizer (⭐138)](https://github.com/bzick/tokenizer) — Tokenizer/lexer for Go ☆`138`
*   [emersion/go-vcard (⭐123)](https://github.com/emersion/go-vcard) — vCard parser and formatter ☆`123`
*   [polera/gonameparts (⭐43)](https://github.com/polera/gonameparts) — Takes a full name and splits it into individual name parts ☆`43`

### Scrapers

*   [gocolly/colly (⭐25k)](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,095`
*   [PuerkitoBio/goquery (⭐15k)](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,905`
*   [mvdan/xurls (⭐1.2k)](https://github.com/mvdan/xurls) — Extract URLs from text ☆`1,247`
*   [s0rg/crawley (⭐330)](https://github.com/s0rg/crawley) — The unix-way web crawler ☆`330`
*   [zoomio/tagify (⭐39)](https://github.com/zoomio/tagify) — Extract tags from HTML/Markdown/text ☆`39`

### Text Analysis

*   [blevesearch/bleve (⭐11k)](https://github.com/blevesearch/bleve) — Text/numeric/geo/vector indexing library ☆`10,981`
*   [derekparker/trie (⭐787)](https://github.com/derekparker/trie) — Trie for extremely fast prefix search ☆`788`
*   [agnivade/levenshtein (⭐451)](https://github.com/agnivade/levenshtein) — Go implementation to calculate Levenshtein Distance. ☆`454`
*   [plar/go-adaptive-radix-tree (⭐411)](https://github.com/plar/go-adaptive-radix-tree) — Adaptive Radix Trees implemented in Go ☆`411`
*   [viant/ptrie (⭐45)](https://github.com/viant/ptrie) — A prefix tree implementation in go ☆`45`

### Tokenizers

*   [go-ego/gse (⭐2.8k)](https://github.com/go-ego/gse) — Multilingual text segmentation ☆`2,780`
*   [pebbe/textcat (⭐73)](https://github.com/pebbe/textcat) — N-gram text categorization ☆`73`

### Translation

*   [nicksnyder/go-i18n (⭐3.5k)](https://github.com/nicksnyder/go-i18n) — Translate Go programs ☆`3,469`
*   [leonelquinteros/gotext (⭐491)](https://github.com/leonelquinteros/gotext) — GNU gettext for Go ☆`490`
*   [vorlif/spreak (⭐92)](https://github.com/vorlif/spreak) — Gettext-based translation library ☆`93`
*   [invopop/ctxi18n (⭐92)](https://github.com/invopop/ctxi18n) — Context-based i18n for Go ☆`92`
*   [mehanizm/iuliia-go (⭐56)](https://github.com/mehanizm/iuliia-go) — Cyrillic to Latin transliteration ☆`56`
*   [youthlin/t (⭐21)](https://github.com/youthlin/t) — Translation util using gettext ☆`21`

## Third-party APIs

### Cloud Provider APIs

*   [googleapis/google-cloud-go (⭐4.4k)](https://github.com/googleapis/google-cloud-go) — Google Cloud Client Libraries for Go. ☆`4,416`
*   [googleapis/google-api-go-client (⭐4.4k)](https://github.com/googleapis/google-api-go-client) — Auto-generated Google APIs for Go. ☆`4,395`
*   [aws/aws-sdk-go-v2 (⭐3.4k)](https://github.com/aws/aws-sdk-go-v2) — AWS SDK for the Go programming language. ☆`3,468`
*   [minio/minio-go (⭐2.9k)](https://github.com/minio/minio-go) — High-performance object storage ☆`2,905`
*   [rhnvrm/simples3 (⭐194)](https://github.com/rhnvrm/simples3) — Simple AWS S3 library using REST ☆`195`
*   [chainifynet/aws-encryption-sdk-go (⭐22)](https://github.com/chainifynet/aws-encryption-sdk-go) — AWS Encryption SDK for Go ☆`22`
*   [circa10a/go-aws-news (⭐18)](https://github.com/circa10a/go-aws-news) — Go app + library to fetch what's new from AWS ☆`18`

### Other APIs

*   [codingsince1985/geo-golang (⭐539)](https://github.com/codingsince1985/geo-golang) — Go library to access geocoding and reverse geocoding APIs ☆`538`
*   [cyruzin/golang-tmdb (⭐155)](https://github.com/cyruzin/golang-tmdb) — Wrapper for TMDb API ☆`156`
*   [gregdel/pushover (⭐154)](https://github.com/gregdel/pushover) — Go wrapper for the Pushover API ☆`154`
*   [mvrilo/go-redoc (⭐94)](https://github.com/mvrilo/go-redoc) — Embedded OpenAPI documentation ☆`94`
*   [rapito/go-spotify (⭐50)](https://github.com/rapito/go-spotify) — Go library for the Spotify Web API ☆`50`
*   [rinchsan/device-check-go (⭐25)](https://github.com/rinchsan/device-check-go) — iOS DeviceCheck SDK for Go ☆`25`
*   [zc2638/swag (⭐50)](https://github.com/zc2638/swag) — Generate Swagger from code ☆`50`
*   [staskobzar/goami2 (⭐21)](https://github.com/staskobzar/goami2) — Simple Asterisk Manager Interface (AMI) library fo golang ☆`21`
*   [sostronk/go-steam (⭐33)](https://github.com/sostronk/go-steam) — Go library for querying Source servers ☆`33`
*   [Icelain/jokeapi (⭐27)](https://github.com/Icelain/jokeapi) — Official golang wrapper for Sv443's jokeapi. ☆`27`

### Productivity APIs

*   [mk-5/fjira (⭐255)](https://github.com/mk-5/fjira) — The golang fuzzy-find cli jira interface ☆`256`
*   [adlio/trello (⭐227)](https://github.com/adlio/trello) — Trello API wrapper for Go ☆`227`
*   [ctreminiom/go-atlassian (⭐194)](https://github.com/ctreminiom/go-atlassian) — Atlassian Cloud API client ☆`195`
*   [koltyakov/gosip (⭐167)](https://github.com/koltyakov/gosip) — SharePoint SDK for Go ☆`167`
*   [FreeLeh/GoFreeDB (⭐90)](https://github.com/FreeLeh/GoFreeDB) — Database on top of Google Sheets ☆`90`
*   [mehanizm/airtable (⭐82)](https://github.com/mehanizm/airtable) — Simple golang airtable API wrapper ☆`83`
*   [k-capehart/go-salesforce (⭐53)](https://github.com/k-capehart/go-salesforce) — Salesforce REST API client ☆`53`

## Utilities

### Build & Release

*   [goreleaser/goreleaser (⭐16k)](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,589`
*   [create-go-app/cli (⭐2.7k)](https://github.com/create-go-app/cli) — Create production-ready Go projects ☆`2,741`
*   [miniscruff/changie (⭐854)](https://github.com/miniscruff/changie) — Automated changelog tool ☆`859`
*   [jaschaephraim/lrserver (⭐129)](https://github.com/jaschaephraim/lrserver) — LiveReload server for Go \[golang] ☆`129`
*   [karl-cardenas-coding/go-lambda-cleanup (⭐96)](https://github.com/karl-cardenas-coding/go-lambda-cleanup) — Remove old AWS Lambda versions ☆`96`

### CLI Tools

*   [junegunn/fzf (⭐78k)](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`77,991`
*   [wagoodman/dive (⭐53k)](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`53,374`
*   [xo/usql (⭐9.8k)](https://github.com/xo/usql) — Universal SQL CLI ☆`9,817`
*   [minio/mc (⭐3.4k)](https://github.com/minio/mc) — Unix utilities for object stores ☆`3,385`
*   [joshmedeski/sesh (⭐1.6k)](https://github.com/joshmedeski/sesh) — Terminal session manager ☆`1,735`
*   [itchyny/bed (⭐1.3k)](https://github.com/itchyny/bed) — Binary editor in Go ☆`1,344`
*   [owenthereal/upterm (⭐1.1k)](https://github.com/owenthereal/upterm) — Instant terminal sharing ☆`1,124`
*   [alajmo/mani (⭐651)](https://github.com/alajmo/mani) — CLI for managing repositories ☆`658`
*   [Unrud/remote-touchpad (⭐640)](https://github.com/Unrud/remote-touchpad) — Control mouse/keyboard remotely ☆`644`
*   [chenquan/diskusage (⭐301)](https://github.com/chenquan/diskusage) — Fast disk usage analyzer ☆`301`
*   [reugn/wifiqr (⭐281)](https://github.com/reugn/wifiqr) — Generate Wi-Fi QR codes ☆`281`
*   [hedhyw/json-log-viewer (⭐211)](https://github.com/hedhyw/json-log-viewer) — Interactive JSON log viewer ☆`215`
*   [hrtsegv/gitcs (⭐130)](https://github.com/hrtsegv/gitcs) — Git contributions graph generator ☆`130`
*   [antham/yogo (⭐46)](https://github.com/antham/yogo) — Check yopmail from CLI ☆`46`

### Data Conversion

*   [samber/lo (⭐21k)](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`20,987`
*   [duke-git/lancet (⭐5.3k)](https://github.com/duke-git/lancet) — Comprehensive util library ☆`5,271`
*   [darccio/mergo (⭐3.1k)](https://github.com/darccio/mergo) — Merge Go structs and maps ☆`3,084`
*   [goforj/godump (⭐1.7k)](https://github.com/goforj/godump) — Pretty-printer for Go structs ☆`1,695`
*   [gookit/filter (⭐151)](https://github.com/gookit/filter) — Data filtering and conversion ☆`151`
*   [tiendc/gofn (⭐52)](https://github.com/tiendc/gofn) — High-performance generic functions ☆`51`
*   [xorcare/pointer (⭐48)](https://github.com/xorcare/pointer) — Create optional field pointers ☆`48`
*   [shockerli/cvt (⭐54)](https://github.com/shockerli/cvt) — Safe type conversion ☆`54`

### Database Extensions

*   [jmoiron/sqlx (⭐17k)](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,513`
*   [georgysavva/scany (⭐1.5k)](https://github.com/georgysavva/scany) — Scan database rows to structs ☆`1,498`
*   [blockloop/scan (⭐609)](https://github.com/blockloop/scan) — Scan SQL rows to structs ☆`610`
*   [wroge/scan (⭐68)](https://github.com/wroge/scan) — Generic SQL row scanner ☆`68`

### Date and Time

*   [dromara/carbon (⭐5.2k)](https://github.com/dromara/carbon) — Developer-friendly time package ☆`5,221`
*   [yaa110/go-persian-calendar (⭐237)](https://github.com/yaa110/go-persian-calendar) — Persian calendar for Go ☆`237`
*   [bykof/gostradamus (⭐210)](https://github.com/bykof/gostradamus) — Better DateTimes for Go ☆`210`
*   [nathan-osman/go-sunrise (⭐172)](https://github.com/nathan-osman/go-sunrise) — Calculate sunrise and sunset times ☆`172`
*   [rickb777/date (⭐142)](https://github.com/rickb777/date) — Date handling package ☆`142`
*   [relvacode/iso8601 (⭐157)](https://github.com/relvacode/iso8601) — Fast ISO8601 date parser ☆`157`

### Dependency Injection

*   [uber-go/fx (⭐7.3k)](https://github.com/uber-go/fx) — DI-based application framework ☆`7,352`
*   [uber-go/dig (⭐4.4k)](https://github.com/uber-go/dig) — Reflection-based DI toolkit ☆`4,439`
*   [goioc/di (⭐377)](https://github.com/goioc/di) — Simple DI for Go ☆`377`
*   [go-kod/kod (⭐196)](https://github.com/go-kod/kod) — DI with aspect-oriented support ☆`195`
*   [i-love-flamingo/dingo (⭐187)](https://github.com/i-love-flamingo/dingo) — DI framework for Go ☆`187`
*   [junioryono/godi (⭐68)](https://github.com/junioryono/godi) — DI with service lifetimes ☆`68`
*   [NVIDIA/gontainer (⭐63)](https://github.com/NVIDIA/gontainer) — Simple DI container ☆`64`
*   [matzefriedrich/parsley (⭐30)](https://github.com/matzefriedrich/parsley) — Reflection-based DI package ☆`30`
*   [muir/nject (⭐30)](https://github.com/muir/nject) — Type-safe DI for Go ☆`30`
*   [logrange/linker (⭐35)](https://github.com/logrange/linker) — DI and IoC package ☆`35`
*   [componego/componego (⭐28)](https://github.com/componego/componego) — Component-oriented framework ☆`28`
*   [firasdarwish/ore (⭐24)](https://github.com/firasdarwish/ore) — Advanced DI solution ☆`24`
*   [gontainer/gontainer (⭐16)](https://github.com/gontainer/gontainer) — YAML-based DI container ☆`16`

### Error Handling

*   [hashicorp/go-multierror (⭐2.5k)](https://github.com/hashicorp/go-multierror) — Represent multiple errors as one ☆`2,548`
*   [cockroachdb/errors (⭐2.3k)](https://github.com/cockroachdb/errors) — Error library with portability ☆`2,352`
*   [rotisserie/eris (⭐1.8k)](https://github.com/rotisserie/eris) — Errors with readable stack traces ☆`1,765`
*   [joomcode/errorx (⭐1.3k)](https://github.com/joomcode/errorx) — Comprehensive error handling ☆`1,270`
*   [ztrue/tracerr (⭐1.1k)](https://github.com/ztrue/tracerr) — Errors with stack trace ☆`1,104`
*   [samber/oops (⭐854)](https://github.com/samber/oops) — Structured error handling ☆`857`
*   [Southclaws/fault (⭐306)](https://github.com/Southclaws/fault) — Composable error wrapping ☆`308`

### File Handling

*   [schollz/croc (⭐34k)](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`34,185`
*   [qax-os/excelize (⭐20k)](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,302`
*   [pdfcpu/pdfcpu (⭐8.4k)](https://github.com/pdfcpu/pdfcpu) — PDF processor in Go ☆`8,470`
*   [spf13/afero (⭐6.6k)](https://github.com/spf13/afero) — Filesystem abstraction for Go ☆`6,559`
*   [dundee/gdu (⭐5.3k)](https://github.com/dundee/gdu) — Fast disk usage analyzer ☆`5,320`
*   [unidoc/unioffice (⭐4.8k)](https://github.com/unidoc/unioffice) — Office document library ☆`4,809`
*   [SpatiumPortae/portal (⭐1.7k)](https://github.com/SpatiumPortae/portal) — Command-line file transfer utility ☆`1,746`
*   [root-gg/plik (⭐1.7k)](https://github.com/root-gg/plik) — Temporary file upload system ☆`1,695`
*   [SebastiaanKlippert/go-wkhtmltopdf (⭐1.2k)](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) — HTML to PDF wrapper ☆`1,178`
*   [otiai10/copy (⭐769)](https://github.com/otiai10/copy) — Copy directories recursively ☆`769`
*   [ulikunitz/xz (⭐548)](https://github.com/ulikunitz/xz) — Pure golang package for reading and writing xz-compressed files ☆`550`
*   [no-src/gofs (⭐525)](https://github.com/no-src/gofs) — Cross-platform file sync ☆`526`
*   [viant/afs (⭐373)](https://github.com/viant/afs) — Abstract file storage ☆`374`
*   [mholt/archives (⭐369)](https://github.com/mholt/archives) — Create and extract archives ☆`372`
*   [C2FO/vfs (⭐356)](https://github.com/C2FO/vfs) — Virtual file system for Go ☆`356`
*   [gen2brain/go-unarr (⭐305)](https://github.com/gen2brain/go-unarr) — Decompression library bindings ☆`305`
*   [barasher/go-exiftool (⭐292)](https://github.com/barasher/go-exiftool) — Exiftool wrapper for metadata ☆`293`
*   [gomutex/godocx (⭐237)](https://github.com/gomutex/godocx) — Go library for reading and writing Microsoft Docx ☆`240`
*   [artonge/go-csv-tag (⭐127)](https://github.com/artonge/go-csv-tag) — CSV reading with tags ☆`129`
*   [parsyl/parquet (⭐127)](https://github.com/parsyl/parquet) — Parquet file library ☆`127`
*   [charlievieth/fastwalk (⭐117)](https://github.com/charlievieth/fastwalk) — Fast directory traversal ☆`120`
*   [adelowo/gulter (⭐68)](https://github.com/adelowo/gulter) — Multipart form handling ☆`68`
*   [go-the-way/exl (⭐32)](https://github.com/go-the-way/exl) — Excel binding to struct written in Go.(Only supports Go1.18+) ☆`32`

### Forms

*   [justinas/nosurf (⭐1.7k)](https://github.com/justinas/nosurf) — CSRF protection middleware ☆`1,727`
*   [gorilla/csrf (⭐1.2k)](https://github.com/gorilla/csrf) — CSRF prevention middleware ☆`1,178`
*   [go-playground/form (⭐901)](https://github.com/go-playground/form) — URL values to structs ☆`902`
*   [ggicci/httpin (⭐382)](https://github.com/ggicci/httpin) — HTTP request to struct binding ☆`382`
*   [sonh/qs (⭐80)](https://github.com/sonh/qs) — Encode structs to query params ☆`80`
*   [cinar/checker (⭐47)](https://github.com/cinar/checker) — Input validation with struct tags ☆`47`

### Functional

*   [samber/mo (⭐3.3k)](https://github.com/samber/mo) — Monads and FP for Go ☆`3,290`
*   [BooleanCat/go-functional (⭐525)](https://github.com/BooleanCat/go-functional) — Iterator library for Go ☆`527`
*   [seborama/fuego (⭐146)](https://github.com/seborama/fuego) — Functional programming in Go ☆`146`
*   [rjNemo/underscore (⭐118)](https://github.com/rjNemo/underscore) — Functional helpers for Go ☆`118`

### General

*   [wabarc/wayback (⭐2.1k)](https://github.com/wabarc/wayback) — Web archiving tool with IM interface ☆`2,143`
*   [gabriel-vasile/mimetype (⭐1.9k)](https://github.com/gabriel-vasile/mimetype) — MIME type detection by magic numbers ☆`1,951`
*   [qmuntal/stateless (⭐1.2k)](https://github.com/qmuntal/stateless) — Go library for creating finite state machines ☆`1,238`
*   [jonboulle/clockwork (⭐723)](https://github.com/jonboulle/clockwork) — a fake clock for golang ☆`723`
*   [Boeing/config-file-validator (⭐496)](https://github.com/Boeing/config-file-validator) — Cross Platform tool to validate configuration files ☆`497`
*   [biter777/countries (⭐501)](https://github.com/biter777/countries) — ISO country codes library ☆`501`
*   [ungerik/go-dry (⭐488)](https://github.com/ungerik/go-dry) — DRY (don't repeat yourself) package for Go ☆`488`
*   [subosito/gotenv (⭐306)](https://github.com/subosito/gotenv) — Load environment variables from `.env` or `io.Reader` in Go. ☆`306`
*   [viant/toolbox (⭐227)](https://github.com/viant/toolbox) — Toolbox - go utility library ☆`227`
*   [ikeikeikeike/go-sitemap-generator (⭐229)](https://github.com/ikeikeikeike/go-sitemap-generator) — Generate XML sitemaps ☆`229`
*   [maja42/goval (⭐173)](https://github.com/maja42/goval) — Expression evaluation in golang ☆`173`
*   [commander-cli/cmd (⭐160)](https://github.com/commander-cli/cmd) — A simple package to execute shell commands on linux, windows and osx ☆`160`
*   [tiendc/go-deepcopy (⭐125)](https://github.com/tiendc/go-deepcopy) — Fast deep-copy library for Go ☆`125`
*   [jfcg/sorty (⭐144)](https://github.com/jfcg/sorty) — Fast Concurrent / Parallel Sorting in Go ☆`144`
*   [syntaqx/cookie (⭐112)](https://github.com/syntaqx/cookie) — Cookies, but with structs, for happiness. ☆`112`
*   [pioz/countries (⭐94)](https://github.com/pioz/countries) — All you need when you are working with countries in Go. ☆`95`
*   [arthurkushman/pgo (⭐88)](https://github.com/arthurkushman/pgo) — Go library for PHP community with convenient functions ☆`88`
*   [wzshiming/gotype (⭐64)](https://github.com/wzshiming/gotype) — Golang source code parsing, usage like reflect package ☆`64`
*   [rkoesters/xdg (⭐48)](https://github.com/rkoesters/xdg) — FreeDesktop.org (xdg) Specs implemented in Go ☆`48`
*   [icza/backscanner (⭐69)](https://github.com/icza/backscanner) — Scan file lines backward ☆`69`
*   [kazhuravlev/just (⭐37)](https://github.com/kazhuravlev/just) — Collection of useful functions. Complete simple tasks faster! ☆`35`
*   [mikekonan/go-types (⭐23)](https://github.com/mikekonan/go-types) — OpenAPI3 types for Go ☆`23`
*   [ik5/gostrutils (⭐47)](https://github.com/ik5/gostrutils) — Collections of string utils I have created over the years ☆`47`
*   [osamingo/gosh (⭐36)](https://github.com/osamingo/gosh) — Provide Go Statistics Handler, Struct, Measure Method ☆`36`
*   [lrita/numa (⭐37)](https://github.com/lrita/numa) — NUMA utility library for Go ☆`38`
*   [floatdrop/debounce (⭐34)](https://github.com/floatdrop/debounce) — A zero-allocation debouncer ☆`34`
*   [skovtunenko/graterm (⭐30)](https://github.com/skovtunenko/graterm) — Graceful termination primitives ☆`30`
*   [nikolaydubina/watchhttp (⭐34)](https://github.com/nikolaydubina/watchhttp) — Expose command output via HTTP ☆`34`

### Logging

*   [sirupsen/logrus (⭐26k)](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,693`
*   [uber-go/zap (⭐24k)](https://github.com/uber-go/zap) — Fast structured logging ☆`24,329`
*   [rs/zerolog (⭐12k)](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,218`
*   [davecgh/go-spew (⭐6.4k)](https://github.com/davecgh/go-spew) — Deep pretty printer for debugging ☆`6,372`
*   [golang/glog (⭐3.6k)](https://github.com/golang/glog) — Leveled execution logs ☆`3,615`
*   [k0kubun/pp (⭐2k)](https://github.com/k0kubun/pp) — Colored pretty printer for Go ☆`2,032`
*   [lmittmann/tint (⭐1.2k)](https://github.com/lmittmann/tint) — Colorized slog handler ☆`1,234`
*   [Lifailon/lazyjournal (⭐1.1k)](https://github.com/Lifailon/lazyjournal) — TUI for journald, Docker, K8s logs ☆`1,119`
*   [getsentry/sentry-go (⭐1k)](https://github.com/getsentry/sentry-go) — Official Sentry SDK for Go ☆`1,041`
*   [phuslu/log (⭐834)](https://github.com/phuslu/log) — Fastest structured logging ☆`834`
*   [samber/slog-multi (⭐604)](https://github.com/samber/slog-multi) — Workflow design for slog handlers ☆`609`
*   [gookit/slog (⭐534)](https://github.com/gookit/slog) — Configurable logging library ☆`534`
*   [henvic/httpretty (⭐413)](https://github.com/henvic/httpretty) — Pretty-print HTTP requests ☆`413`
*   [simukti/sqldb-logger (⭐382)](https://github.com/simukti/sqldb-logger) — SQL database logger ☆`382`
*   [hashicorp/logutils (⭐369)](https://github.com/hashicorp/logutils) — Logging utilities for Go ☆`371`
*   [samber/slog-formatter (⭐210)](https://github.com/samber/slog-formatter) — Slog attribute formatting ☆`212`
*   [DeRuina/timberjack (⭐116)](https://github.com/DeRuina/timberjack) — Log rolling library ☆`118`
*   [rs/xlog (⭐141)](https://github.com/rs/xlog) — Context-aware HTTP logger ☆`141`
*   [yuseferi/zax (⭐32)](https://github.com/yuseferi/zax) — Zap logger with context ☆`33`
*   [clok/kemba (⭐17)](https://github.com/clok/kemba) — Tiny debug logging tool ☆`17`

### Networking Utils

*   [cristianoliveira/ergo (⭐649)](https://github.com/cristianoliveira/ergo) — Manage apps on different ports ☆`649`
*   [htcat/htcat (⭐559)](https://github.com/htcat/htcat) — Parallel HTTP download ☆`561`
*   [ferama/rospo (⭐358)](https://github.com/ferama/rospo) — Persistent SSH tunnels ☆`358`

### Project Layout

*   [golang-standards/project-layout (⭐55k)](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`55,386`
*   [Melkeydev/go-blueprint (⭐8.6k)](https://github.com/Melkeydev/go-blueprint) — Spin up Go projects with popular frameworks ☆`8,653`
*   [ardanlabs/service (⭐3.9k)](https://github.com/ardanlabs/service) — K8s service starter kit ☆`3,936`
*   [Shpota/goxygen (⭐3.6k)](https://github.com/Shpota/goxygen) — Generate full-stack web projects ☆`3,602`
*   [mikestefanello/pagoda (⭐2.9k)](https://github.com/mikestefanello/pagoda) — Full-stack web development starter kit ☆`2,908`
*   [go-nunu/nunu (⭐2.5k)](https://github.com/go-nunu/nunu) — CLI for building Go apps ☆`2,544`
*   [sagikazarmark/modern-go-application (⭐1.9k)](https://github.com/sagikazarmark/modern-go-application) — Modern Go app example ☆`1,937`
*   [naughtygopher/goapp (⭐1k)](https://github.com/naughtygopher/goapp) — Opinionated web app structure ☆`1,050`
*   [allaboutapps/go-starter (⭐594)](https://github.com/allaboutapps/go-starter) — Production-ready RESTful API template ☆`595`
*   [golang-templates/seed (⭐555)](https://github.com/golang-templates/seed) — Go app GitHub template ☆`554`
*   [raeperd/kickstart.go (⭐102)](https://github.com/raeperd/kickstart.go) — Minimal HTTP server template ☆`104`
*   [wangyoucao577/go-project-layout (⭐26)](https://github.com/wangyoucao577/go-project-layout) — Go project structure guide ☆`26`

### Resilience & Retry

*   [avast/retry-go (⭐2.9k)](https://github.com/avast/retry-go) — Simple retry mechanism ☆`2,885`
*   [eapache/go-resiliency (⭐2.3k)](https://github.com/eapache/go-resiliency) — Resiliency patterns for golang ☆`2,336`
*   [failsafe-go/failsafe-go (⭐2.1k)](https://github.com/failsafe-go/failsafe-go) — Fault tolerance patterns ☆`2,144`
*   [rubyist/circuitbreaker (⭐1.2k)](https://github.com/rubyist/circuitbreaker) — Circuit breakers in Go ☆`1,164`
*   [cep21/circuit (⭐798)](https://github.com/cep21/circuit) — Hystrix-like circuit breaker ☆`797`
*   [mennanov/limiters (⭐618)](https://github.com/mennanov/limiters) — Distributed rate limiters ☆`620`
*   [kamilsk/retry (⭐346)](https://github.com/kamilsk/retry) — Advanced retry mechanism ☆`346`
*   [webriots/rate (⭐166)](https://github.com/webriots/rate) — High-performance rate limiter ☆`166`
*   [reugn/equalizer (⭐90)](https://github.com/reugn/equalizer) — Performant rate limiters ☆`90`

### Strings

*   [huandu/xstrings (⭐1.4k)](https://github.com/huandu/xstrings) — String functions from other langs ☆`1,417`
*   [abhimanyu003/sttr (⭐1.3k)](https://github.com/abhimanyu003/sttr) — CLI string operations ☆`1,289`
*   [gobeam/stringy (⭐251)](https://github.com/gobeam/stringy) — String case conversions ☆`251`
*   [ozgio/strutil (⭐207)](https://github.com/ozgio/strutil) — String utilities for Go ☆`207`

### System & Process

*   [cilium/ebpf (⭐7.5k)](https://github.com/cilium/ebpf) — eBPF library for Go ☆`7,528`
*   [maruel/panicparse (⭐3.7k)](https://github.com/maruel/panicparse) — Crash your app in style ☆`3,713`
*   [immortal/immortal (⭐832)](https://github.com/immortal/immortal) — Cross-platform supervisor ☆`832`
*   [derekparker/delve (⭐663)](https://github.com/derekparker/delve) — Delve is a debugger for the Go programming language. ☆`662`
*   [gotranspile/cxgo (⭐386)](https://github.com/gotranspile/cxgo) — Transpile C to Go ☆`387`

### UUID

*   [google/uuid (⭐6k)](https://github.com/google/uuid) — UUID generation and parsing ☆`5,989`
*   [oklog/ulid (⭐5k)](https://github.com/oklog/ulid) — ULID implementation ☆`4,985`
*   [gofrs/uuid (⭐1.8k)](https://github.com/gofrs/uuid) — UUID library for Go ☆`1,766`
*   [osamingo/indigo (⭐112)](https://github.com/osamingo/indigo) — Sonyflake-based ID generator ☆`112`
*   [sdrapkin/guid (⭐73)](https://github.com/sdrapkin/guid) — Fast cryptographically safe Guid generator for Go ☆`73`
*   [twharmon/gouid (⭐26)](https://github.com/twharmon/gouid) — Fast, dependable universally unique ids ☆`26`

## Version Control & Packages

### Git APIs

*   [google/go-github (⭐11k)](https://github.com/google/go-github) — Go library for accessing the GitHub v3 API ☆`11,137`
*   [shurcooL/githubv4 (⭐1.2k)](https://github.com/shurcooL/githubv4) — GitHub GraphQL API v4 client ☆`1,184`
*   [go-playground/webhooks (⭐1k)](https://github.com/go-playground/webhooks) — Webhook receiver for GitHub, Bitbucket, GitLab, Gogs ☆`1,028`
*   [andygrunwald/go-trending (⭐146)](https://github.com/andygrunwald/go-trending) — Access GitHub trending repositories ☆`146`
*   [andygrunwald/go-gerrit (⭐104)](https://github.com/andygrunwald/go-gerrit) — Go client/library for Gerrit Code Review ☆`104`

### Package Management

*   [anchore/syft (⭐8.3k)](https://github.com/anchore/syft) — SBOM generator for containers ☆`8,393`
*   [nao1215/gup (⭐535)](https://github.com/nao1215/gup) — gup - Update binaries installed by "go install" with goroutines. ☆`540`
*   [marwanhawari/stew (⭐326)](https://github.com/marwanhawari/stew) — An independent package manager for compiled binaries. ☆`331`
*   [chaindead/modup (⭐62)](https://github.com/chaindead/modup) — TUI for Go dependency updates ☆`63`

### Version Control

*   [go-git/go-git (⭐7.2k)](https://github.com/go-git/go-git) — Pure Go Git implementation ☆`7,206`
*   [antham/chyle (⭐159)](https://github.com/antham/chyle) — Changelog generator from Git ☆`159`
*   [gabyx/Githooks (⭐120)](https://github.com/gabyx/Githooks) — Per-repo shared Git hooks ☆`120`
*   [antham/gommit (⭐115)](https://github.com/antham/gommit) — Enforce git message commit consistency ☆`115`
*   [jfrog/froggit-go (⭐52)](https://github.com/jfrog/froggit-go) — Universal VCS client library ☆`52`
*   [kazhuravlev/git-tools (⭐31)](https://github.com/kazhuravlev/git-tools) — Useful set of tools which helps to manage git tags ☆`29`

## Web Development

### Microservices

*   [zeromicro/go-zero (⭐33k)](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`32,666`
*   [go-kit/kit (⭐28k)](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,609`
*   [go-kratos/kratos (⭐25k)](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,449`
*   [micro/go-micro (⭐23k)](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,706`
*   [smallnest/rpcx (⭐8.3k)](https://github.com/smallnest/rpcx) — Feature-rich RPC framework ☆`8,276`
*   [cloudwego/kitex (⭐7.9k)](https://github.com/cloudwego/kitex) — High-performance Go RPC framework ☆`7,864`
*   [go-dev-frame/sponge (⭐2.8k)](https://github.com/go-dev-frame/sponge) — Code generation framework for Go ☆`2,794`
*   [go-eagle/eagle (⭐2.4k)](https://github.com/go-eagle/eagle) — A Go framework for the API or Microservice ☆`2,416`
*   [unionj-cloud/go-doudou (⭐1.2k)](https://github.com/unionj-cloud/go-doudou) — OpenAPI 3 and gRPC microservices framework ☆`1,206`
*   [trpc-group/trpc-go (⭐1.1k)](https://github.com/trpc-group/trpc-go) — A pluggable, high-performance RPC framework written in golang ☆`1,117`
*   [gmsec/micro (⭐25)](https://github.com/gmsec/micro) — A Go distributed systems development framework ☆`25`

### Middlewares

*   [urfave/negroni (⭐7.5k)](https://github.com/urfave/negroni) — Idiomatic HTTP Middleware for Golang ☆`7,543`
*   [tdewolff/minify (⭐4.1k)](https://github.com/tdewolff/minify) — Go minifiers for web formats ☆`4,065`
*   [justinas/alice (⭐3.4k)](https://github.com/justinas/alice) — Painless middleware chaining for Go ☆`3,352`
*   [rs/cors (⭐2.9k)](https://github.com/rs/cors) — Go net/http configurable handler to handle CORS requests ☆`2,862`
*   [didip/tollbooth (⭐2.9k)](https://github.com/didip/tollbooth) — Simple middleware to rate-limit HTTP requests. ☆`2,857`
*   [unrolled/render (⭐2k)](https://github.com/unrolled/render) — Render JSON, XML, HTML, binary ☆`1,992`
*   [lingrino/go-fault (⭐511)](https://github.com/lingrino/go-fault) — go fault injection library ☆`512`
*   [jub0bs/cors (⭐169)](https://github.com/jub0bs/cors) — perhaps the best CORS middleware library for Go ☆`178`
*   [rookie-ninja/rk-gin (⭐51)](https://github.com/rookie-ninja/rk-gin) — Start gin microservice from YAML, plugin of rk-boot ☆`51`
*   [faabiosr/echo-middleware (⭐16)](https://github.com/faabiosr/echo-middleware) — Middlewares for Echo framework ☆`16`

### Routers

*   [gorilla/mux (⭐22k)](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,886`
*   [go-chi/chi (⭐22k)](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`21,700`
*   [gowww/router (⭐186)](https://github.com/gowww/router) — A lightning fast HTTP router ☆`186`
*   [gernest/alien (⭐134)](https://github.com/gernest/alien) — A lightweight and fast http router from outer space ☆`134`
*   [ngamux/ngamux (⭐70)](https://github.com/ngamux/ngamux) — Simple HTTP router for Go ☆`70`
*   [bmf-san/goblin (⭐81)](https://github.com/bmf-san/goblin) — A golang http router based on trie tree. ☆`81`
*   [muir/nchi (⭐18)](https://github.com/muir/nchi) — golang http router with elegance, speed, and flexibility ☆`18`

### Template Engines

*   [a-h/templ (⭐10k)](https://github.com/a-h/templ) — A language for writing HTML user interfaces in Go. ☆`10,083`
*   [valyala/quicktemplate (⭐3.3k)](https://github.com/valyala/quicktemplate) — Fast template engine for Go ☆`3,296`
*   [johnfercher/maroto (⭐2.6k)](https://github.com/johnfercher/maroto) — Create PDFs with Bootstrap grid ☆`2,639`
*   [CloudyKit/jet (⭐1.4k)](https://github.com/CloudyKit/jet) — Jet template engine ☆`1,383`
*   [osteele/liquid (⭐339)](https://github.com/osteele/liquid) — A Liquid template engine in Go ☆`341`
*   [go-sprout/sprout (⭐209)](https://github.com/go-sprout/sprout) — Template functions for Go ☆`210`
*   [robfig/soy (⭐177)](https://github.com/robfig/soy) — Go implementation for Soy templates (Google Closure templates) ☆`177`
*   [goradd/got (⭐38)](https://github.com/goradd/got) — Template engine with Go code output ☆`38`

### Web Frameworks

*   [gin-gonic/gin (⭐88k)](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`88,132`
*   [gofiber/fiber (⭐39k)](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`39,236`
*   [beego/beego (⭐32k)](https://github.com/beego/beego) — High-performance web framework ☆`32,428`
*   [labstack/echo (⭐32k)](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,179`
*   [gofr-dev/gofr (⭐16k)](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`16,087`
*   [gogf/gf (⭐13k)](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,035`
*   [cloudwego/hertz (⭐7.1k)](https://github.com/cloudwego/hertz) — High-performance HTTP framework ☆`7,091`
*   [goadesign/goa (⭐6k)](https://github.com/goadesign/goa) — Design-first API framework ☆`6,055`
*   [apache/dubbo-go (⭐4.9k)](https://github.com/apache/dubbo-go) — Go Implementation For Apache Dubbo . ☆`4,884`
*   [goravel/goravel (⭐4.4k)](https://github.com/goravel/goravel) — The full-featured Golang Development Framework skeleton ☆`4,428`
*   [danielgtaylor/huma (⭐3.8k)](https://github.com/danielgtaylor/huma) — Huma REST/HTTP API Framework for Golang with OpenAPI 3.1 ☆`3,827`
*   [documize/community (⭐2.4k)](https://github.com/documize/community) — Modern Confluence alternative ☆`2,367`
*   [go-sonic/sonic (⭐2.1k)](https://github.com/go-sonic/sonic) — Blogging platform in Go ☆`2,119`
*   [go-goyave/goyave (⭐1.8k)](https://github.com/go-goyave/goyave) — The enterprise REST API framework ☆`1,761`
*   [go-fuego/fuego (⭐1.7k)](https://github.com/go-fuego/fuego) — Web framework with OpenAPI 3 ☆`1,665`
*   [templui/templui (⭐1.3k)](https://github.com/templui/templui) — UI components for Templ ☆`1,350`
*   [savsgio/atreugo (⭐1.3k)](https://github.com/savsgio/atreugo) — Micro web framework on fasthttp ☆`1,299`
*   [ankorstore/yokai (⭐819)](https://github.com/ankorstore/yokai) — Modular framework for Go apps ☆`820`
*   [indeedeng/iwf (⭐629)](https://github.com/indeedeng/iwf) — Workflow-as-code orchestration ☆`631`
*   [i-love-flamingo/flamingo-commerce (⭐587)](https://github.com/i-love-flamingo/flamingo-commerce) — Flexible Go web framework ☆`588`
*   [i-love-flamingo/flamingo (⭐554)](https://github.com/i-love-flamingo/flamingo) — Flexible Go web framework ☆`554`
*   [rookie-ninja/rk-boot (⭐575)](https://github.com/rookie-ninja/rk-boot) — Enterprise microservice framework ☆`575`
*   [fastschema/fastschema (⭐534)](https://github.com/fastschema/fastschema) — All-in-One Backend as a Service with Headless CMS Power ☆`536`
*   [uadmin/uadmin (⭐355)](https://github.com/uadmin/uadmin) — The web framework for Golang ☆`355`
*   [xxjwxc/ginrpc (⭐301)](https://github.com/xxjwxc/ginrpc) — gin auto binding, grpc and annotated route ☆`301`
*   [hidevopsio/hiboot (⭐182)](https://github.com/hidevopsio/hiboot) — High-performance CLI and web apps ☆`180`
*   [beatlabs/patron (⭐126)](https://github.com/beatlabs/patron) — Cloud-native microservice framework ☆`126`
*   [gone-io/gone (⭐132)](https://github.com/gone-io/gone) — Lightweight DI framework ☆`132`
*   [claygod/microservice (⭐122)](https://github.com/claygod/microservice) — Simple microservice framework ☆`122`
*   [gookit/rux (⭐99)](https://github.com/gookit/rux) — Simple and fast web framework ☆`99`
*   [yaitoo/xun (⭐91)](https://github.com/yaitoo/xun) — Web framework on html/template ☆`91`
*   [napsy/go-css (⭐90)](https://github.com/napsy/go-css) — A very simple CSS parser, written in Go ☆`91`
*   [go-spring/spring-core (⭐75)](https://github.com/go-spring/spring-core) — Spring-inspired framework for Go ☆`75`
*   [abemedia/go-don (⭐57)](https://github.com/abemedia/go-don) — API framework written in Golang. ☆`57`
*   [JiveGroup/gFly (⭐48)](https://github.com/JiveGroup/gFly) — Laravel inspired web framework written in Go ☆`48`
*   [clubpay/ronykit (⭐35)](https://github.com/clubpay/ronykit) — API Framework supporting REST and RPC. ☆`36`
*   [SaiNageswarS/go-api-boot (⭐35)](https://github.com/SaiNageswarS/go-api-boot) — gRPC + HTTP/2 production framework ☆`35`
*   [jvcoutinho/lit (⭐31)](https://github.com/jvcoutinho/lit) — A simple, fast and expressive HTTP framework for Go. ☆`31`

### WebAssembly

*   [tinygo-org/tinygo (⭐17k)](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,171`
*   [agnivade/wasmbrowsertest (⭐206)](https://github.com/agnivade/wasmbrowsertest) — Run WASM tests inside your browser ☆`206`
*   [extism/go-sdk (⭐166)](https://github.com/extism/go-sdk) — Extism Go SDK - easily run WebAssembly modules in your Go applications ☆`167`

## Workflow & Scheduling

### Job Scheduler

*   [go-co-op/gocron (⭐6.9k)](https://github.com/go-co-op/gocron) — Easy and fluent Go cron scheduling ☆`6,920`
*   [hatchet-dev/hatchet (⭐6.5k)](https://github.com/hatchet-dev/hatchet) — Run Background Tasks at Scale ☆`6,611`
*   [reugn/go-quartz (⭐2k)](https://github.com/reugn/go-quartz) — Minimalist and zero-dependency scheduling library for Go ☆`2,001`
*   [adhocore/gronx (⭐486)](https://github.com/adhocore/gronx) — Lightweight cron expression parser ☆`492`
*   [fieldryand/goflow (⭐472)](https://github.com/fieldryand/goflow) — Simple but powerful DAG scheduler and dashboard ☆`472`
*   [madflojo/tasks (⭐323)](https://github.com/madflojo/tasks) — In-process task scheduler ☆`323`
*   [bart6114/cheek (⭐194)](https://github.com/bart6114/cheek) — cheek: a pico-sized declarative job scheduler ☆`194`
*   [onatm/clockwerk (⭐182)](https://github.com/onatm/clockwerk) — Job Scheduling Library ☆`182`
*   [deepaksinghvi/cdule (⭐60)](https://github.com/deepaksinghvi/cdule) — Golang job scheduler ☆`60`
*   [pardnchiu/go-scheduler (⭐32)](https://github.com/pardnchiu/go-scheduler) — Scheduler with standard cron and task dependencies ☆`32`
*   [romshark/sched (⭐28)](https://github.com/romshark/sched) — A job scheduler for Go with the ability to fast-forward time. ☆`28`

### Workflow Frameworks

*   [redpanda-data/connect (⭐8.6k)](https://github.com/redpanda-data/connect) — Fancy stream processing made operationally mundane ☆`8,589`
*   [dagu-org/dagu (⭐3k)](https://github.com/dagu-org/dagu) — Workflow engine with Web UI ☆`3,076`
*   [jf-tech/omniparser (⭐1.1k)](https://github.com/jf-tech/omniparser) — ETL streaming parser for Go ☆`1,078`
*   [noneback/go-taskflow (⭐609)](https://github.com/noneback/go-taskflow) — Task-parallel programming library ☆`612`
*   [cadence-workflow/cadence-go-client (⭐374)](https://github.com/cadence-workflow/cadence-go-client) — Cadence workflow client for Go ☆`374`
*   [luno/workflow (⭐216)](https://github.com/luno/workflow) — Type-safe workflow orchestration ☆`217`
*   [rhosocial/go-dag (⭐35)](https://github.com/rhosocial/go-dag) — DAG-based workflow framework ☆`35`

***

## 🏆 Top 100 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1.  [ollama/ollama (⭐162k)](https://github.com/ollama/ollama) — Run LLMs locally ☆`162,893`
2.  [kubernetes/kubernetes (⭐120k)](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`120,676`
3.  [gin-gonic/gin (⭐88k)](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`88,132`
4.  [junegunn/fzf (⭐78k)](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`77,991`
5.  [moby/moby (⭐71k)](https://github.com/moby/moby) — Container ecosystem components ☆`71,479`
6.  [caddyserver/caddy (⭐70k)](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`70,194`
7.  [prometheus/prometheus (⭐63k)](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`62,801`
8.  [traefik/traefik (⭐62k)](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`61,816`
9.  [pocketbase/pocketbase (⭐56k)](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`56,223`
10. [golang-standards/project-layout (⭐55k)](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`55,386`
11. [go-gitea/gitea (⭐54k)](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`53,781`
12. [wagoodman/dive (⭐53k)](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`53,374`
13. [etcd-io/etcd (⭐51k)](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`51,621`
14. [ethereum/go-ethereum (⭐51k)](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`50,823`
15. [spf13/cobra (⭐43k)](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`43,212`
16. [mudler/LocalAI (⭐43k)](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`42,891`
17. [milvus-io/milvus (⭐43k)](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`42,827`
18. [pingcap/tidb (⭐40k)](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`39,798`
19. [go-gorm/gorm (⭐39k)](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,602`
20. [charmbracelet/bubbletea (⭐39k)](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`39,583`
21. [gofiber/fiber (⭐39k)](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`39,236`
22. [schollz/croc (⭐34k)](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`34,185`
23. [harness/harness (⭐34k)](https://github.com/harness/harness) — End-to-end developer platform ☆`33,882`
24. [zeromicro/go-zero (⭐33k)](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`32,666`
25. [beego/beego (⭐32k)](https://github.com/beego/beego) — High-performance web framework ☆`32,428`
26. [restic/restic (⭐32k)](https://github.com/restic/restic) — Fast, secure backup program ☆`32,312`
27. [k3s-io/k3s (⭐32k)](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`32,223`
28. [labstack/echo (⭐32k)](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,179`
29. [cockroachdb/cockroach (⭐32k)](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`31,900`
30. [kubernetes/minikube (⭐31k)](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,502`
31. [influxdata/influxdb (⭐31k)](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,257`
32. [seaweedfs/seaweedfs (⭐30k)](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`30,405`
33. [spf13/viper (⭐30k)](https://github.com/spf13/viper) — Go configuration with fangs ☆`30,063`
34. [grafana/k6 (⭐30k)](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`29,931`
35. [fyne-io/fyne (⭐28k)](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`27,939`
36. [go-kit/kit (⭐28k)](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,609`
37. [stretchr/testify (⭐26k)](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`25,862`
38. [sirupsen/logrus (⭐26k)](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,693`
39. [go-kratos/kratos (⭐25k)](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,449`
40. [gocolly/colly (⭐25k)](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,095`
41. [tsenart/vegeta (⭐25k)](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`24,907`
42. [uber-go/zap (⭐24k)](https://github.com/uber-go/zap) — Fast structured logging ☆`24,329`
43. [urfave/cli (⭐24k)](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`23,893`
44. [valyala/fasthttp (⭐23k)](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,261`
45. [air-verse/air (⭐23k)](https://github.com/air-verse/air) — Live reload for Go apps ☆`22,989`
46. [grpc/grpc-go (⭐23k)](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,787`
47. [micro/go-micro (⭐23k)](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,706`
48. [jaegertracing/jaeger (⭐22k)](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`22,471`
49. [redis/go-redis (⭐22k)](https://github.com/redis/go-redis) — Redis Go client ☆`21,930`
50. [gorilla/mux (⭐22k)](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,886`
51. [go-chi/chi (⭐22k)](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`21,700`
52. [dgraph-io/dgraph (⭐22k)](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,573`
53. [FiloSottile/age (⭐21k)](https://github.com/FiloSottile/age) — Simple encryption tool ☆`21,351`
54. [samber/lo (⭐21k)](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`20,987`
55. [vitessio/vitess (⭐21k)](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`20,745`
56. [qax-os/excelize (⭐20k)](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,302`
57. [antonmedv/fx (⭐20k)](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,275`
58. [dolthub/dolt (⭐20k)](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`19,886`
59. [casbin/casbin (⭐20k)](https://github.com/casbin/casbin) — Authorization library for Go ☆`19,846`
60. [go-playground/validator (⭐20k)](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`19,716`
61. [nats-io/nats-server (⭐19k)](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`19,169`
62. [golangci/golangci-lint (⭐18k)](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`18,530`
63. [golang-migrate/migrate (⭐18k)](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,110`
64. [jmoiron/sqlx (⭐17k)](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,513`
65. [rqlite/rqlite (⭐17k)](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,314`
66. [tinygo-org/tinygo (⭐17k)](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,171`
67. [sqlc-dev/sqlc (⭐17k)](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`16,975`
68. [ent/ent (⭐17k)](https://github.com/ent/ent) — An entity framework for Go ☆`16,925`
69. [ipfs/kubo (⭐17k)](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`16,911`
70. [VictoriaMetrics/VictoriaMetrics (⭐16k)](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`16,337`
71. [fatih/vim-go (⭐16k)](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,238`
72. [gofr-dev/gofr (⭐16k)](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`16,087`
73. [pion/webrtc (⭐16k)](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,051`
74. [keploy/keploy (⭐16k)](https://github.com/keploy/keploy) — API testing with auto mocks ☆`15,709`
75. [hashicorp/packer (⭐16k)](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,608`
76. [goreleaser/goreleaser (⭐16k)](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,589`
77. [dgraph-io/badger (⭐15k)](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,477`
78. [tidwall/gjson (⭐15k)](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,438`
79. [go-sql-driver/mysql (⭐15k)](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,421`
80. [kubernetes-sigs/kind (⭐15k)](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,026`
81. [PuerkitoBio/goquery (⭐15k)](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,905`
82. [go-task/task (⭐15k)](https://github.com/go-task/task) — A fast, cross-platform build tool inspired by Make, designed for modern workflows. ☆`14,846`
83. [panjf2000/ants (⭐14k)](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,332`
84. [webview/webview (⭐14k)](https://github.com/webview/webview) — Tiny webview library for Go ☆`13,911`
85. [bytebase/bytebase (⭐14k)](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`13,738`
86. [gizak/termui (⭐14k)](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,518`
87. [jackc/pgx (⭐13k)](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`13,378`
88. [golang/groupcache (⭐13k)](https://github.com/golang/groupcache) — Distributed cache library ☆`13,323`
89. [juicedata/juicefs (⭐13k)](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`13,233`
90. [cloudflare/cloudflared (⭐13k)](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`13,167`
91. [gopherjs/gopherjs (⭐13k)](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,125`
92. [gogf/gf (⭐13k)](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,035`
93. [hajimehoshi/ebiten (⭐13k)](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`12,965`
94. [hibiken/asynq (⭐13k)](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`12,904`
95. [chromedp/chromedp (⭐13k)](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`12,742`
96. [IBM/sarama (⭐12k)](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,429`
97. [rs/zerolog (⭐12k)](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,218`
98. [Shopify/toxiproxy (⭐12k)](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`11,848`
99. [kubeshark/kubeshark (⭐12k)](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`11,794`
100.    [shirou/gopsutil (⭐12k)](https://github.com/shirou/gopsutil) — psutil for golang ☆`11,706`

## Gophers

*   [MariaLetta/free-gophers-pack (⭐3.9k)](https://github.com/MariaLetta/free-gophers-pack) — This pack of 100+ gopher pictures and elements
*   [keygx/Go-gopher-Vector (⭐73)](https://github.com/keygx/Go-gopher-Vector) — Go gopher Vector Data (.ai, .svg)
*   [ashleymcnamara/gophers (⭐3.1k)](https://github.com/ashleymcnamara/gophers) — Gopher Artwork by Ashley McNamara
*   [sillecelik/go-gopher (⭐160)](https://github.com/sillecelik/go-gopher) — The Go Gopher Amigurumi Pattern
*   [GolangUA/gopher-logos (⭐140)](https://github.com/GolangUA/gopher-logos) — adorable gopher logos
*   [egonelbre/gophers (⭐3.8k)](https://github.com/egonelbre/gophers) — gophers artwork
*   [scraly/gophers (⭐36)](https://github.com/scraly/gophers) — Gopher artwork (Golang mascot)

## Contributing

Please see [CONTRIBUTING](https://github.com/abordage/awesome-go/blob/main/README.md/.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request — contributions are welcome!

## Credits

*   [avelino/awesome-go (⭐165k)](https://github.com/avelino/awesome-go)
*   [All Contributors (⭐2)](https://github.com/abordage/awesome-go/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](https://github.com/abordage/awesome-go/blob/main/README.md/LICENSE) for more information.

