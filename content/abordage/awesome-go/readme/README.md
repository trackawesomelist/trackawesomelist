# Awesome Go Overview

Structured collection of Go frameworks, libraries, tools, and resources. Automatically maintained and up-to-date with metadata, filtering, and comprehensive categorization.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/abordage/awesome-go/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 abordage/awesome-go](https://github.com/abordage/awesome-go) · ⭐ 3 · 🏷️ Programming Languages

[ [Daily](/content/abordage/awesome-go/README.md) / [Weekly](/content/abordage/awesome-go/week/README.md) / Overview ]

---

# Awesome Go

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-go?label=last%20update)](https://github.com/abordage/awesome-go/blob/main/README.md/README.md)
![Repositories](https://img.shields.io/badge/repositories-1,194-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-4,967,252-gold)
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

*   [sashabaranov/go-openai (⭐11k)](https://github.com/sashabaranov/go-openai) — OpenAI API client for Go ☆`10,615`
*   [wit-ai/wit-go (⭐170)](https://github.com/wit-ai/wit-go) — Go client for wit.ai HTTP API ☆`170`

### Artificial Intelligence

*   [ollama/ollama (⭐169k)](https://github.com/ollama/ollama) — Run LLMs locally ☆`168,767`
*   [mudler/LocalAI (⭐45k)](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`45,332`
*   [tmc/langchaingo (⭐9k)](https://github.com/tmc/langchaingo) — LangChain for Go, the easiest way to write LLM-based programs in Go ☆`9,047`
*   [maximhq/bifrost (⭐3.7k)](https://github.com/maximhq/bifrost) — Fastest LLM gateway for Go ☆`3,722`
*   [philippgille/chromem-go (⭐914)](https://github.com/philippgille/chromem-go) — Embeddable vector database for Go ☆`917`
*   [universal-tool-calling-protocol/go-utcp (⭐103)](https://github.com/universal-tool-calling-protocol/go-utcp) — Official Go implementation of the UTCP ☆`103`
*   [presbrey/ollamafarm (⭐98)](https://github.com/presbrey/ollamafarm) — Manage multiple Ollama instances ☆`98`

### Machine Learning

*   [gorgonia/gorgonia (⭐5.9k)](https://github.com/gorgonia/gorgonia) — Machine learning library for Go ☆`5,911`
*   [otiai10/gosseract (⭐3.1k)](https://github.com/otiai10/gosseract) — OCR using Tesseract in Go ☆`3,091`
*   [gomlx/gomlx (⭐1.4k)](https://github.com/gomlx/gomlx) — GoMLX: An Accelerated Machine Learning Framework For Go ☆`1,361`
*   [jbrukh/bayesian (⭐812)](https://github.com/jbrukh/bayesian) — Naive Bayesian Classification for Golang. ☆`812`
*   [knights-analytics/hugot (⭐590)](https://github.com/knights-analytics/hugot) — Onnx transformer pipelines in Golang ☆`592`
*   [patrikeh/go-deep (⭐555)](https://github.com/patrikeh/go-deep) — Artificial Neural Network ☆`555`
*   [c-bata/goptuna (⭐279)](https://github.com/c-bata/goptuna) — A hyperparameter optimization framework, inspired by Optuna. ☆`279`

## Audio & Video

### Audio

*   [ebitengine/oto (⭐1.9k)](https://github.com/ebitengine/oto) — A low-level library to play sound on multiple platforms ☆`1,898`
*   [gordonklaus/portaudio (⭐834)](https://github.com/gordonklaus/portaudio) — Go bindings for the PortAudio audio I/O library ☆`834`
*   [DylanMeeus/GoAudio (⭐413)](https://github.com/DylanMeeus/GoAudio) — Go tools for audio processing & creation ☆`414`
*   [gen2brain/malgo (⭐398)](https://github.com/gen2brain/malgo) — Mini audio library ☆`398`
*   [mewkiz/flac (⭐353)](https://github.com/mewkiz/flac) — Package flac provides access to FLAC (Free Lossless Audio Codec) streams. ☆`353`
*   [tosone/minimp3 (⭐133)](https://github.com/tosone/minimp3) — Decode mp3 ☆`133`

### Images

*   [hybridgroup/gocv (⭐7.4k)](https://github.com/hybridgroup/gocv) — Computer vision with OpenCV 4 ☆`7,421`
*   [anthonynsimon/bild (⭐4.2k)](https://github.com/anthonynsimon/bild) — Image processing algorithms in pure Go ☆`4,188`
*   [cshum/imagor (⭐3.9k)](https://github.com/cshum/imagor) — Fast, secure image processing server and Go library, using libvips ☆`3,932`
*   [thoas/picfit (⭐2.3k)](https://github.com/thoas/picfit) — An image resizing server written in Go ☆`2,335`
*   [gographics/imagick (⭐1.9k)](https://github.com/gographics/imagick) — Go binding to ImageMagick's MagickWand C API ☆`1,865`
*   [tdewolff/canvas (⭐1.8k)](https://github.com/tdewolff/canvas) — Vector graphics in Go ☆`1,801`
*   [davidbyttow/govips (⭐1.6k)](https://github.com/davidbyttow/govips) — A lightning fast image processing and resizing library for Go ☆`1,576`
*   [yeqown/go-qrcode (⭐827)](https://github.com/yeqown/go-qrcode) — Customizable QR code generator ☆`828`
*   [HugoSmits86/nativewebp (⭐406)](https://github.com/HugoSmits86/nativewebp) — Native webp encoder for Go ☆`407`
*   [auyer/steganography (⭐352)](https://github.com/auyer/steganography) — LSB steganography in pure Go ☆`353`
*   [kolesa-team/go-webp (⭐304)](https://github.com/kolesa-team/go-webp) — Simple and fast webp library for golang ☆`304`
*   [Pixboost/transformimgs (⭐289)](https://github.com/Pixboost/transformimgs) — Open source image CDN. ☆`287`
*   [qmuntal/gltf (⭐279)](https://github.com/qmuntal/gltf) — Go library for encoding glTF 2.0 files ☆`280`
*   [gojek/darkroom (⭐235)](https://github.com/gojek/darkroom) — Image processing engine and proxy service ☆`235`
*   [aofei/cameron (⭐131)](https://github.com/aofei/cameron) — An avatar generator for Go. ☆`131`
*   [piglig/go-qr (⭐49)](https://github.com/piglig/go-qr) — A native, high-quality and minimalistic QR code generator ☆`49`

### Video

*   [asticode/go-astisub (⭐691)](https://github.com/asticode/go-astisub) — Manipulate subtitles in Go ☆`691`
*   [asticode/go-astiav (⭐695)](https://github.com/asticode/go-astiav) — Golang ffmpeg and libav C bindings ☆`697`
*   [Eyevinn/mp4ff (⭐625)](https://github.com/Eyevinn/mp4ff) — MP4/ISOBMFF tools and library ☆`626`
*   [asticode/go-astits (⭐610)](https://github.com/asticode/go-astits) — Demux and mux MPEG Transport Streams (.ts) natively in GO ☆`611`
*   [adrg/libvlc-go (⭐507)](https://github.com/adrg/libvlc-go) — Go bindings for libVLC ☆`507`
*   [Eyevinn/hls-m3u8 (⭐59)](https://github.com/Eyevinn/hls-m3u8) — HLS m3u8 library in Go ☆`59`
*   [jonoton/scout (⭐26)](https://github.com/jonoton/scout) — Video surveillance with motion detection ☆`26`
*   [unki2aut/go-mpd (⭐32)](https://github.com/unki2aut/go-mpd) — MPEG-DASH manifest library ☆`32`

## Auth

### Authentication

*   [golang-jwt/jwt (⭐9k)](https://github.com/golang-jwt/jwt) — Go implementation of JSON Web Tokens (JWT). ☆`9,012`
*   [markbates/goth (⭐6.5k)](https://github.com/markbates/goth) — Multi-provider authentication ☆`6,510`
*   [golang/oauth2 (⭐5.8k)](https://github.com/golang/oauth2) — Go OAuth2 ☆`5,834`
*   [aarondl/authboss (⭐4.2k)](https://github.com/aarondl/authboss) — The boss of http auth. ☆`4,170`
*   [alexedwards/scs (⭐2.5k)](https://github.com/alexedwards/scs) — HTTP Session Management for Go ☆`2,540`
*   [lestrrat-go/jwx (⭐2.4k)](https://github.com/lestrrat-go/jwx) — Complete JWx implementation ☆`2,350`
*   [openshift/osin (⭐1.9k)](https://github.com/openshift/osin) — Golang OAuth2 server library ☆`1,936`
*   [dghubble/gologin (⭐1.9k)](https://github.com/dghubble/gologin) — Go login handlers for authentication providers (OAuth1, OAuth2) ☆`1,950`
*   [zitadel/oidc (⭐1.8k)](https://github.com/zitadel/oidc) — OpenID Connect client and server ☆`1,802`
*   [cristalhq/jwt (⭐688)](https://github.com/cristalhq/jwt) — Safe, simple and fast JSON Web Tokens for Go ☆`688`
*   [shaj13/go-guardian (⭐609)](https://github.com/shaj13/go-guardian) — Authentication library for Go ☆`609`
*   [go-jose/go-jose (⭐497)](https://github.com/go-jose/go-jose) — An implementation of JOSE standards (JWE, JWS, JWT) in Go ☆`496`
*   [abraithwaite/jeff (⭐271)](https://github.com/abraithwaite/jeff) — Jeff provides the simplest way to manage web sessions in Go. ☆`271`
*   [Kwynto/gosession (⭐257)](https://github.com/Kwynto/gosession) — Quick session for net/http ☆`257`
*   [leodip/goiabada (⭐188)](https://github.com/leodip/goiabada) — Goiabada is an OAuth2 / OpenID Connect server written in Go. ☆`188`
*   [brianvoe/sjwt (⭐122)](https://github.com/brianvoe/sjwt) — Simple JWT Golang ☆`122`
*   [jellydator/sessionup (⭐131)](https://github.com/jellydator/sessionup) — Straightforward HTTP session management ☆`131`
*   [essentialkaos/branca (⭐96)](https://github.com/essentialkaos/branca) — Encrypted API tokens ☆`96`
*   [icza/session (⭐118)](https://github.com/icza/session) — Session management for web servers ☆`118`
*   [mengzhuo/cookiestxt (⭐22)](https://github.com/mengzhuo/cookiestxt) — cookiestxt implement parser of cookies txt format ☆`22`

### Authorization

*   [apache/casbin (⭐20k)](https://github.com/apache/casbin) — Authorization library for Go ☆`19,992`
*   [ory/keto (⭐5.3k)](https://github.com/ory/keto) — Customizable permission server ☆`5,309`
*   [openfga/openfga (⭐5k)](https://github.com/openfga/openfga) — Fine-grained authorization server ☆`5,009`
*   [cerbos/cerbos (⭐4.3k)](https://github.com/cerbos/cerbos) — Open core authorization layer ☆`4,319`

## Bots & Chat

### Bot Frameworks

*   [tucnak/telebot (⭐4.6k)](https://github.com/tucnak/telebot) — Telebot is a Telegram bot framework in Go. ☆`4,583`
*   [go-telegram/bot (⭐1.7k)](https://github.com/go-telegram/bot) — Telegram Bot API Go framework ☆`1,676`
*   [mymmrac/telego (⭐981)](https://github.com/mymmrac/telego) — Telegram Bot API library for Go ☆`989`
*   [diamondburned/arikawa (⭐586)](https://github.com/diamondburned/arikawa) — A Golang library and framework for the Discord API. ☆`587`
*   [NicoNex/echotron (⭐434)](https://github.com/NicoNex/echotron) — An elegant and concurrent library for the Telegram bot API in Go. ☆`434`
*   [gempir/go-twitch-irc (⭐396)](https://github.com/gempir/go-twitch-irc) — go irc client for twitch.tv ☆`396`
*   [innogames/slack-bot (⭐208)](https://github.com/innogames/slack-bot) — Slack bot for Jenkins, Jira, PRs ☆`208`
*   [mr-linch/go-tg (⭐130)](https://github.com/mr-linch/go-tg) — Telegram Bot API client ☆`130`
*   [slack-io/slacker (⭐59)](https://github.com/slack-io/slacker) — Slack Bot Framework ☆`59`
*   [onrik/micha (⭐33)](https://github.com/onrik/micha) — Client lib for Telegram bot api ☆`33`

### Chat APIs

*   [bwmarrin/discordgo (⭐5.9k)](https://github.com/bwmarrin/discordgo) — (Golang) Go bindings for Discord ☆`5,877`
*   [slack-go/slack (⭐4.9k)](https://github.com/slack-go/slack) — Slack API in Go ☆`4,925`
*   [huandu/facebook (⭐1.5k)](https://github.com/huandu/facebook) — A Facebook Graph API SDK For Go. ☆`1,459`
*   [chyroc/lark (⭐470)](https://github.com/chyroc/lark) — Lark/Feishu Open API SDK ☆`470`
*   [go-lark/lark (⭐242)](https://github.com/go-lark/lark) — Feishu/Lark SDK for Go ☆`242`
*   [switchupcb/disgo (⭐111)](https://github.com/switchupcb/disgo) — Next-gen Discord API library ☆`111`

## CLI & Terminal

### Advanced Console UIs

*   [charmbracelet/bubbletea (⭐41k)](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`41,516`
*   [antonmedv/fx (⭐20k)](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,397`
*   [gizak/termui (⭐14k)](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,540`
*   [charmbracelet/lipgloss (⭐11k)](https://github.com/charmbracelet/lipgloss) — Style definitions for nice terminal layouts ☆`11,041`
*   [jroimartin/gocui (⭐11k)](https://github.com/jroimartin/gocui) — Minimalist Go package aimed at creating Console User Interfaces. ☆`10,546`
*   [charmbracelet/bubbles (⭐8.2k)](https://github.com/charmbracelet/bubbles) — TUI components for Bubble Tea ☆`8,189`
*   [c-bata/go-prompt (⭐5.5k)](https://github.com/c-bata/go-prompt) — Interactive prompts for Go ☆`5,472`
*   [pterm/pterm (⭐5.4k)](https://github.com/pterm/pterm) — Modern terminal output library ☆`5,416`
*   [schollz/progressbar (⭐4.7k)](https://github.com/schollz/progressbar) — Thread-safe progress bar ☆`4,660`
*   [guptarohit/asciigraph (⭐3k)](https://github.com/guptarohit/asciigraph) — ASCII line graphs in terminal ☆`2,996`
*   [mum4k/termdash (⭐3k)](https://github.com/mum4k/termdash) — Terminal-based dashboard ☆`2,989`
*   [briandowns/spinner (⭐2.5k)](https://github.com/briandowns/spinner) — Terminal spinner indicators ☆`2,525`
*   [vbauerster/mpb (⭐2.5k)](https://github.com/vbauerster/mpb) — Multi progress bar ☆`2,488`
*   [muesli/termenv (⭐2k)](https://github.com/muesli/termenv) — Terminal color support ☆`1,977`
*   [gookit/color (⭐1.6k)](https://github.com/gookit/color) — Terminal color rendering ☆`1,579`
*   [logrusorgru/aurora (⭐1.5k)](https://github.com/logrusorgru/aurora) — ANSI colors for Printf ☆`1,485`
*   [mattn/go-isatty (⭐899)](https://github.com/mattn/go-isatty) — Check if terminal is TTY ☆`899`
*   [mattn/go-colorable (⭐805)](https://github.com/mattn/go-colorable) — Colorable writer for Windows ☆`805`
*   [box-cli-maker/box-cli-maker (⭐626)](https://github.com/box-cli-maker/box-cli-maker) — Render highly customizable boxes in the terminal ☆`627`
*   [Evertras/bubble-table (⭐567)](https://github.com/Evertras/bubble-table) — Table component for Bubble Tea ☆`567`
*   [DMcP89/tinycare-tui (⭐19)](https://github.com/DMcP89/tinycare-tui) — TUI application written in GO inspired by tiny-care-terminal ☆`19`

### Standard CLI

*   [spf13/cobra (⭐44k)](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`43,657`
*   [urfave/cli (⭐24k)](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`23,961`
*   [elves/elvish (⭐6.3k)](https://github.com/elves/elvish) — Scripting shell for Go ☆`6,274`
*   [alecthomas/kingpin (⭐3.6k)](https://github.com/alecthomas/kingpin) — Command-line parser ☆`3,561`
*   [dnote/dnote (⭐3k)](https://github.com/dnote/dnote) — Command-line notebook ☆`3,022`
*   [spf13/pflag (⭐2.7k)](https://github.com/spf13/pflag) — POSIX/GNU-style flags ☆`2,726`
*   [jessevdk/go-flags (⭐2.7k)](https://github.com/jessevdk/go-flags) — Command-line option parser ☆`2,697`
*   [alexflint/go-arg (⭐2.3k)](https://github.com/alexflint/go-arg) — Struct-based argument parsing ☆`2,252`
*   [carapace-sh/carapace-bin (⭐1.8k)](https://github.com/carapace-sh/carapace-bin) — Multi-shell completion binary ☆`1,775`
*   [nanovms/ops (⭐1.5k)](https://github.com/nanovms/ops) — Build and run unikernels ☆`1,485`
*   [carapace-sh/carapace (⭐1.2k)](https://github.com/carapace-sh/carapace) — Multi-shell completion library ☆`1,246`
*   [posener/complete (⭐953)](https://github.com/posener/complete) — Bash completion in Go ☆`953`
*   [ddddddO/gtree (⭐330)](https://github.com/ddddddO/gtree) — Generate ASCII tree from Markdown ☆`331`
*   [leaanthony/clir (⭐198)](https://github.com/leaanthony/clir) — Simple CLI library ☆`198`
*   [urfave/sflags (⭐166)](https://github.com/urfave/sflags) — Generate flags from structs ☆`166`
*   [hedzr/cmdr (⭐142)](https://github.com/hedzr/cmdr) — POSIX-compliant CLI parser ☆`142`
*   [reeflective/readline (⭐136)](https://github.com/reeflective/readline) — Shell library with inputrc ☆`136`
*   [cristalhq/acmd (⭐139)](https://github.com/cristalhq/acmd) — Simple CLI package ☆`139`
*   [reeflective/console (⭐106)](https://github.com/reeflective/console) — Console library for Cobra ☆`106`
*   [codingconcepts/env (⭐126)](https://github.com/codingconcepts/env) — Tag-based environment configuration for structs ☆`126`
*   [jxskiss/mcli (⭐46)](https://github.com/jxskiss/mcli) — Minimal but powerful CLI ☆`46`
*   [dixonwille/wlog (⭐67)](https://github.com/dixonwille/wlog) — Cross-platform logging ☆`67`
*   [DavidGamba/go-getoptions (⭐61)](https://github.com/DavidGamba/go-getoptions) — Command line option parser with completion ☆`61`
*   [nyaosorg/go-readline-ny (⭐34)](https://github.com/nyaosorg/go-readline-ny) — Readline for Go ☆`34`
*   [carapace-sh/carapace-spec (⭐29)](https://github.com/carapace-sh/carapace-spec) — Multi-shell completion library ☆`29`
*   [hashicorp/cli (⭐37)](https://github.com/hashicorp/cli) — CLI library for Go ☆`37`
*   [sgreben/flagvar (⭐48)](https://github.com/sgreben/flagvar) — CLI argument types for flag ☆`48`

## Concurrency

### Actor Model

*   [asynkron/protoactor-go (⭐5.4k)](https://github.com/asynkron/protoactor-go) — Ultra fast distributed actors for Go ☆`5,451`
*   [ergo-services/ergo (⭐4.5k)](https://github.com/ergo-services/ergo) — Actor framework with network transparency ☆`4,489`
*   [anthdm/hollywood (⭐2.2k)](https://github.com/anthdm/hollywood) — Blazingly fast and light-weight Actor engine written in Golang ☆`2,212`
*   [Tochemey/goakt (⭐336)](https://github.com/Tochemey/goakt) — Distributed actor framework ☆`337`

### Goroutines

*   [panjf2000/ants (⭐14k)](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,387`
*   [benmanns/goworker (⭐2.9k)](https://github.com/benmanns/goworker) — Resque-compatible background worker ☆`2,853`
*   [alitto/pond (⭐2.1k)](https://github.com/alitto/pond) — High-performance worker pool ☆`2,139`
*   [destel/rill (⭐1.8k)](https://github.com/destel/rill) — Channel-based concurrency toolkit ☆`1,806`
*   [xxjwxc/gowp (⭐521)](https://github.com/xxjwxc/gowp) — Goroutine worker pool ☆`521`
*   [earthboundkid/flowmatic (⭐398)](https://github.com/earthboundkid/flowmatic) — Structured concurrency ☆`398`
*   [reugn/async (⭐302)](https://github.com/reugn/async) — Async computation package ☆`302`
*   [vladopajic/go-actor (⭐286)](https://github.com/vladopajic/go-actor) — Actor model library ☆`287`
*   [timandy/routine (⭐289)](https://github.com/timandy/routine) — ThreadLocal for Go ☆`289`
*   [mborders/artifex (⭐214)](https://github.com/mborders/artifex) — In-memory job queue ☆`214`

### Stream Processing

*   [reugn/go-streams (⭐2.2k)](https://github.com/reugn/go-streams) — Stream processing library ☆`2,163`
*   [Breeze0806/go-etl (⭐185)](https://github.com/Breeze0806/go-etl) — ETL toolset for Go ☆`185`
*   [fulminate-io/machine (⭐167)](https://github.com/fulminate-io/machine) — Machine is a workflow/pipeline library for processing data ☆`167`
*   [mariomac/gostream (⭐171)](https://github.com/mariomac/gostream) — Java Streams port for Go ☆`171`
*   [rulego/streamsql (⭐55)](https://github.com/rulego/streamsql) — SQL-based stream processing for IoT ☆`55`

## Configuration

*   [spf13/viper (⭐30k)](https://github.com/spf13/viper) — Go configuration with fangs ☆`30,183`
*   [caarlos0/env (⭐6.1k)](https://github.com/caarlos0/env) — Parse environment variables to structs ☆`6,095`
*   [knadh/koanf (⭐4k)](https://github.com/knadh/koanf) — Lightweight config management ☆`3,964`
*   [alecthomas/kong (⭐3k)](https://github.com/alecthomas/kong) — Command-line parser for Go ☆`3,025`
*   [ilyakaznacheev/cleanenv (⭐2.1k)](https://github.com/ilyakaznacheev/cleanenv) — Minimalistic environment config reader ☆`2,086`
*   [adrg/xdg (⭐975)](https://github.com/adrg/xdg) — XDG Base Directory implementation ☆`975`
*   [cristalhq/aconfig (⭐627)](https://github.com/cristalhq/aconfig) — Simple config loader ☆`627`
*   [gookit/config (⭐584)](https://github.com/gookit/config) — Config management with formats ☆`584`
*   [nil-go/konf (⭐376)](https://github.com/nil-go/konf) — Simplest config loader for Go ☆`377`
*   [kkyr/fig (⭐384)](https://github.com/kkyr/fig) — Minimalist config library ☆`384`
*   [hjson/hjson-go (⭐348)](https://github.com/hjson/hjson-go) — Hjson for Go ☆`348`
*   [vrischmann/envconfig (⭐250)](https://github.com/vrischmann/envconfig) — Env config library ☆`250`
*   [chaindead/zerocfg (⭐200)](https://github.com/chaindead/zerocfg) — Zero-effort config management ☆`200`
*   [beatlabs/harvester (⭐134)](https://github.com/beatlabs/harvester) — Watch and notify config changes ☆`134`
*   [BoRuDar/configuration (⭐108)](https://github.com/BoRuDar/configuration) — Set struct fields from env, flags, files ☆`108`
*   [gurkankaymak/hocon (⭐90)](https://github.com/gurkankaymak/hocon) — HOCON config library for Go ☆`90`
*   [omeid/uconfig (⭐73)](https://github.com/omeid/uconfig) — Lightweight config management ☆`73`
*   [PaddleHQ/go-aws-ssm (⭐62)](https://github.com/PaddleHQ/go-aws-ssm) — AWS System Manager interface ☆`62`
*   [go-simpler/env (⭐80)](https://github.com/go-simpler/env) — Load env vars to struct ☆`80`
*   [sakirsensoy/genv (⭐43)](https://github.com/sakirsensoy/genv) — Easy env variable handling ☆`43`
*   [num30/config (⭐60)](https://github.com/num30/config) — Declarative configuration ☆`60`
*   [wkhere/bcl (⭐30)](https://github.com/wkhere/bcl) — Basic Configuration Language ☆`30`
*   [dsbasko/go-cfg (⭐48)](https://github.com/dsbasko/go-cfg) — Unified config reading ☆`48`
*   [greencoda/confiq (⭐39)](https://github.com/greencoda/confiq) — Config struct decoder ☆`39`
*   [romshark/yamagiconf (⭐18)](https://github.com/romshark/yamagiconf) — YAML config framework ☆`18`
*   [atelpis/enflag (⭐38)](https://github.com/atelpis/enflag) — Unify env and flag parsing ☆`38`
*   [nasermirzaei89/env (⭐22)](https://github.com/nasermirzaei89/env) — Zero-dep env package ☆`22`
*   [deatil/go-array (⭐22)](https://github.com/deatil/go-array) — Read/set map, slice, JSON data ☆`22`

## Data Formats

### JSON

*   [tidwall/gjson (⭐15k)](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,482`
*   [bytedance/sonic (⭐9.3k)](https://github.com/bytedance/sonic) — A blazingly fast JSON serializing & deserializing library ☆`9,326`
*   [Jeffail/gabs (⭐3.5k)](https://github.com/Jeffail/gabs) — Dynamic JSON parsing ☆`3,531`
*   [valyala/fastjson (⭐2.4k)](https://github.com/valyala/fastjson) — Fast JSON parser for Go ☆`2,449`
*   [ohler55/ojg (⭐942)](https://github.com/ohler55/ojg) — Optimized JSON for Go ☆`942`
*   [wI2L/jsondiff (⭐625)](https://github.com/wI2L/jsondiff) — JSON Patch diff computation ☆`622`
*   [spyzhov/ajson (⭐290)](https://github.com/spyzhov/ajson) — Abstract JSON with JSONPath ☆`290`
*   [Andrew-M-C/go.jsonvalue (⭐202)](https://github.com/Andrew-M-C/go.jsonvalue) — Unstructured JSON solution ☆`202`
*   [iOliverNguyen/ujson (⭐85)](https://github.com/iOliverNguyen/ujson) — Minimal JSON parser ☆`85`
*   [neilotoole/jsoncolor (⭐52)](https://github.com/neilotoole/jsoncolor) — Colorized JSON output ☆`52`

### Serialization

*   [golang/protobuf (⭐10k)](https://github.com/golang/protobuf) — Protocol buffers for Go ☆`10,066`
*   [ugorji/go (⭐1.9k)](https://github.com/ugorji/go) — Codec for msgpack, cbor, json ☆`1,944`
*   [linkedin/goavro (⭐1.1k)](https://github.com/linkedin/goavro) — Goavro is a library that encodes and decodes Avro data. ☆`1,059`
*   [fxamacker/cbor (⭐1k)](https://github.com/fxamacker/cbor) — CBOR codec with extensions ☆`1,037`
*   [jszwec/csvutil (⭐1k)](https://github.com/jszwec/csvutil) — CSV to struct mapping ☆`1,033`
*   [ghostiam/binstruct (⭐114)](https://github.com/ghostiam/binstruct) — Binary to struct decoder ☆`114`
*   [csweichel/bel (⭐46)](https://github.com/csweichel/bel) — Generate TypeScript from Go ☆`46`
*   [o1egl/fwencoder (⭐27)](https://github.com/o1egl/fwencoder) — Fixed width file parser ☆`27`
*   [tiendc/go-csvlib (⭐18)](https://github.com/tiendc/go-csvlib) — High-level CSV library ☆`18`

### XML

*   [miku/zek (⭐825)](https://github.com/miku/zek) — Generate Go struct from XML ☆`825`
*   [antchfx/xpath (⭐739)](https://github.com/antchfx/xpath) — XPath for Go ☆`739`
*   [antchfx/xmlquery (⭐485)](https://github.com/antchfx/xmlquery) — XPath XML query ☆`485`

## Data Structures

### Bit-packing and Compression

*   [RoaringBitmap/roaring (⭐2.9k)](https://github.com/RoaringBitmap/roaring) — Compressed bitmaps for Go ☆`2,866`
*   [iancmcc/bingo (⭐52)](https://github.com/iancmcc/bingo) — Zero-allocation binary encoding ☆`52`
*   [amallia/go-ef (⭐41)](https://github.com/amallia/go-ef) — A Go implementation of the Elias-Fano encoding ☆`41`

### Bloom and Cuckoo Filters

*   [bits-and-blooms/bloom (⭐2.8k)](https://github.com/bits-and-blooms/bloom) — Bloom filter implementation ☆`2,767`
*   [tylertreat/BoomFilters (⭐1.6k)](https://github.com/tylertreat/BoomFilters) — Probabilistic data structures for streams ☆`1,647`
*   [seiflotfy/cuckoofilter (⭐1.2k)](https://github.com/seiflotfy/cuckoofilter) — Cuckoo Filter: Practically Better Than Bloom ☆`1,222`
*   [OldPanda/bloomfilter (⭐20)](https://github.com/OldPanda/bloomfilter) — Bloom filter compatible with pybloom ☆`20`

### Maps

*   [mhmtszr/concurrent-swiss-map (⭐262)](https://github.com/mhmtszr/concurrent-swiss-map) — Thread-safe concurrent hash map ☆`262`
*   [lrita/cmap (⭐101)](https://github.com/lrita/cmap) — a thread-safe concurrent map for go ☆`102`
*   [srfrog/dict (⭐46)](https://github.com/srfrog/dict) — Python-like dictionaries for Go ☆`46`
*   [goradd/maps (⭐52)](https://github.com/goradd/maps) — Generic map library for Go ☆`52`

### Miscellaneous

*   [Workiva/go-datastructures (⭐7.9k)](https://github.com/Workiva/go-datastructures) — Performant, threadsafe data structures ☆`7,914`
*   [deckarep/golang-set (⭐4.7k)](https://github.com/deckarep/golang-set) — Generic set type for Go ☆`4,661`
*   [bits-and-blooms/bitset (⭐1.5k)](https://github.com/bits-and-blooms/bitset) — Go package implementing bitsets ☆`1,490`
*   [liyue201/gostl (⭐1.1k)](https://github.com/liyue201/gostl) — Data structures modeled on C++ STL ☆`1,137`
*   [axiomhq/hyperloglog (⭐1k)](https://github.com/axiomhq/hyperloglog) — HyperLogLog with optimizations ☆`1,035`
*   [kelindar/bitmap (⭐372)](https://github.com/kelindar/bitmap) — Simple dense bitmap index in Go with binary operators ☆`372`
*   [barweiss/go-tuple (⭐100)](https://github.com/barweiss/go-tuple) — Go 1.18+ generic tuple ☆`100`
*   [seiflotfy/count-min-log (⭐69)](https://github.com/seiflotfy/count-min-log) — Go implementation of Count-Min-Log ☆`69`
*   [s0rg/quadtree (⭐41)](https://github.com/s0rg/quadtree) — Generic, zero-alloc, 100%-test covered Quadtree for golang ☆`41`
*   [nazar256/parapipe (⭐37)](https://github.com/nazar256/parapipe) — Paralleling pipeline ☆`37`
*   [StudioSol/set (⭐30)](https://github.com/StudioSol/set) — Simple set data structure ☆`30`
*   [bobg/merkle (⭐22)](https://github.com/bobg/merkle) — Merkle hash trees ☆`22`

### Queues

*   [gammazero/deque (⭐770)](https://github.com/gammazero/deque) — Fast ring-buffer deque (double-ended queue) ☆`771`
*   [adrianbrad/queue (⭐332)](https://github.com/adrianbrad/queue) — Multiple queue implementations ☆`332`
*   [embano1/memlog (⭐138)](https://github.com/embano1/memlog) — A Kafka log inspired in-memory and append-only data structure ☆`138`
*   [mikestefanello/backlite (⭐142)](https://github.com/mikestefanello/backlite) — SQLite-backed task queues ☆`143`

## Databases

### Caches

*   [golang/groupcache (⭐13k)](https://github.com/golang/groupcache) — Distributed cache library ☆`13,337`
*   [dgraph-io/ristretto (⭐6.9k)](https://github.com/dgraph-io/ristretto) — A high performance memory-bound Go cache ☆`6,855`
*   [eko/gocache (⭐2.8k)](https://github.com/eko/gocache) — Multi-store caching library ☆`2,847`
*   [maypok86/otter (⭐2.6k)](https://github.com/maypok86/otter) — A high performance caching library for Go ☆`2,583`
*   [VictoriaMetrics/fastcache (⭐2.3k)](https://github.com/VictoriaMetrics/fastcache) — Fast in-memory cache for Go ☆`2,346`
*   [jellydator/ttlcache (⭐1.2k)](https://github.com/jellydator/ttlcache) — An in-memory cache with item expiration and generics ☆`1,239`
*   [viccon/sturdyc (⭐1.2k)](https://github.com/viccon/sturdyc) — Caching with advanced concurrency ☆`1,247`
*   [EchoVault/SugarDB (⭐530)](https://github.com/EchoVault/SugarDB) — Embeddable and distributed in-memory alternative to Redis. ☆`530`
*   [Yiling-J/theine-go (⭐366)](https://github.com/Yiling-J/theine-go) — high performance in-memory cache ☆`367`
*   [faabiosr/cachego (⭐371)](https://github.com/faabiosr/cachego) — Golang Cache component - Multiple drivers ☆`371`
*   [elastic/go-freelru (⭐263)](https://github.com/elastic/go-freelru) — GC-less, fast and generic LRU cache for Go ☆`264`
*   [samber/hot (⭐248)](https://github.com/samber/hot) — In-memory caching library for read-intensive Go applications ☆`248`
*   [naughtygopher/pocache (⭐235)](https://github.com/naughtygopher/pocache) — Preemptive optimistic caching ☆`235`
*   [OrlovEvgeny/go-mcache (⭐104)](https://github.com/OrlovEvgeny/go-mcache) — Sharded in-memory KV cache ☆`104`
*   [erni27/imcache (⭐123)](https://github.com/erni27/imcache) — A zero-dependency generic in-memory cache Go library ☆`123`
*   [zekroTJA/timedmap (⭐74)](https://github.com/zekroTJA/timedmap) — A thread safe map which has expiring key-value pairs. ☆`74`
*   [codingsince1985/couchcache (⭐66)](https://github.com/codingsince1985/couchcache) — A RESTful caching micro-service in Go backed by Couchbase ☆`66`
*   [mdaliyan/icache (⭐23)](https://github.com/mdaliyan/icache) — High-performance generic cache ☆`23`

### Database Schema Migration

*   [golang-migrate/migrate (⭐18k)](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,348`
*   [bytebase/bytebase (⭐14k)](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`13,903`
*   [pressly/goose (⭐10k)](https://github.com/pressly/goose) — A database migration tool. Supports SQL migrations and Go functions. ☆`10,457`
*   [ariga/atlas (⭐8.2k)](https://github.com/ariga/atlas) — Declarative schema migrations with schema-as-code workflows ☆`8,267`
*   [amacneil/dbmate (⭐6.8k)](https://github.com/amacneil/dbmate) — A lightweight, framework-agnostic database migration tool. ☆`6,831`
*   [rubenv/sql-migrate (⭐3.4k)](https://github.com/rubenv/sql-migrate) — SQL schema migration tool for Go. ☆`3,410`
*   [skeema/skeema (⭐1.4k)](https://github.com/skeema/skeema) — Declarative pure-SQL schema management for MySQL and MariaDB ☆`1,362`
*   [go-gormigrate/gormigrate (⭐1.2k)](https://github.com/go-gormigrate/gormigrate) — Minimalistic database migration helper for Gorm ORM ☆`1,154`
*   [sunary/sqlize (⭐124)](https://github.com/sunary/sqlize) — SQL parsing and migration toolkit ☆`124`
*   [robinjoseph08/go-pg-migrations (⭐86)](https://github.com/robinjoseph08/go-pg-migrations) — A Go package to help write migrations with go-pg/pg. ☆`86`
*   [adlio/schema (⭐42)](https://github.com/adlio/schema) — Embedded schema migration package for Go ☆`42`
*   [khezen/avro (⭐48)](https://github.com/khezen/avro) — Apache AVRO for go ☆`48`
*   [muir/libschema (⭐17)](https://github.com/muir/libschema) — database schema migrations on a per-library basis \[Go] ☆`17`

### Database Tools

*   [vitessio/vitess (⭐21k)](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`20,906`
*   [sosedoff/pgweb (⭐9.3k)](https://github.com/sosedoff/pgweb) — Cross-platform client for PostgreSQL databases ☆`9,294`
*   [go-mysql-org/go-mysql (⭐4.9k)](https://github.com/go-mysql-org/go-mysql) — a powerful mysql toolset with Go ☆`4,931`
*   [prest/prest (⭐4.5k)](https://github.com/prest/prest) — PostgreSQL REST API server ☆`4,540`
*   [ContentSquare/chproxy (⭐1.4k)](https://github.com/ContentSquare/chproxy) — Open-Source ClickHouse http proxy and load balancer ☆`1,447`
*   [cybertec-postgresql/pg\_timetable (⭐1.3k)](https://github.com/cybertec-postgresql/pg_timetable) — Advanced PostgreSQL scheduler ☆`1,346`
*   [liweiyi88/onedump (⭐957)](https://github.com/liweiyi88/onedump) — Effortless database administration tool ☆`961`
*   [HDT3213/rdb (⭐604)](https://github.com/HDT3213/rdb) — Redis RDB parser for Go ☆`605`
*   [nikepan/clickhouse-bulk (⭐507)](https://github.com/nikepan/clickhouse-bulk) — Batch inserts for ClickHouse ☆`506`
*   [wesql/wescale (⭐315)](https://github.com/wesql/wescale) — MySQL proxy with read/write split ☆`315`
*   [gatewayd-io/gatewayd (⭐280)](https://github.com/gatewayd-io/gatewayd) — database gateway for building data-driven applications ☆`280`
*   [sj14/dbbench (⭐115)](https://github.com/sj14/dbbench) — Database benchmarking tool ☆`115`
*   [bartventer/gorm-multitenancy (⭐80)](https://github.com/bartventer/gorm-multitenancy) — Multi-tenancy for GORM ☆`80`
*   [kazhuravlev/database-gateway (⭐33)](https://github.com/kazhuravlev/database-gateway) — Safe access to production databases ☆`34`
*   [codingconcepts/dg (⭐43)](https://github.com/codingconcepts/dg) — Generate CSV from data models ☆`43`

### Databases Implemented in Go

*   [prometheus/prometheus (⭐63k)](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`63,557`
*   [milvus-io/milvus (⭐44k)](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`43,763`
*   [pingcap/tidb (⭐40k)](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`39,962`
*   [cockroachdb/cockroach (⭐32k)](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`32,044`
*   [influxdata/influxdb (⭐31k)](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,434`
*   [dolthub/dolt (⭐22k)](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`22,116`
*   [dgraph-io/dgraph (⭐22k)](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,658`
*   [rqlite/rqlite (⭐17k)](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,416`
*   [VictoriaMetrics/VictoriaMetrics (⭐17k)](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`16,741`
*   [dgraph-io/badger (⭐16k)](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,560`
*   [dicedb/dicedb (⭐11k)](https://github.com/dicedb/dicedb) — Low-latency key/value engine on Valkey with storage tiers ☆`10,727`
*   [etcd-io/bbolt (⭐9.5k)](https://github.com/etcd-io/bbolt) — An embedded key/value database for Go. ☆`9,460`
*   [codenotary/immudb (⭐9k)](https://github.com/codenotary/immudb) — Immutable database with SQL ☆`8,952`
*   [cockroachdb/pebble (⭐5.8k)](https://github.com/cockroachdb/pebble) — RocksDB/LevelDB inspired key-value database in Go ☆`5,843`
*   [rosedblabs/rosedb (⭐4.9k)](https://github.com/rosedblabs/rosedb) — Fast key/value storage engine ☆`4,883`
*   [tidwall/buntdb (⭐4.8k)](https://github.com/tidwall/buntdb) — Embeddable in-memory key/value DB ☆`4,841`
*   [nalgeon/redka (⭐4.5k)](https://github.com/nalgeon/redka) — Redis re-implemented with SQL ☆`4,539`
*   [HDT3213/godis (⭐3.8k)](https://github.com/HDT3213/godis) — A Golang implemented Redis Server and Cluster ☆`3,828`
*   [nutsdb/nutsdb (⭐3.6k)](https://github.com/nutsdb/nutsdb) — Simple embeddable key/value store ☆`3,562`
*   [lindb/lindb (⭐3.1k)](https://github.com/lindb/lindb) — Scalable time-series database ☆`3,060`
*   [lotusdblabs/lotusdb (⭐2.3k)](https://github.com/lotusdblabs/lotusdb) — Key-value database with LSM and B+ tree ☆`2,253`
*   [kelindar/column (⭐1.5k)](https://github.com/kelindar/column) — Columnar in-memory store ☆`1,511`
*   [akrylysov/pogreb (⭐1.4k)](https://github.com/akrylysov/pogreb) — Embedded key-value store for read-heavy workloads written in Go ☆`1,351`
*   [objectbox/objectbox-go (⭐1.3k)](https://github.com/objectbox/objectbox-go) — Embedded database for Go ☆`1,260`
*   [couchbase/moss (⭐1k)](https://github.com/couchbase/moss) — Simple, fast key-val storage ☆`1,017`
*   [claygod/transaction (⭐139)](https://github.com/claygod/transaction) — Embedded database for accounts transactions. ☆`139`
*   [xgzlucario/rotom (⭐40)](https://github.com/xgzlucario/rotom) — Tiny Redis server in Go ☆`40`

### Distributed Storage

*   [seaweedfs/seaweedfs (⭐31k)](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`31,490`
*   [juicedata/juicefs (⭐13k)](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`13,429`

### Interfaces to Multiple Backends

*   [philippgille/gokv (⭐824)](https://github.com/philippgille/gokv) — Key-value store abstraction ☆`825`
*   [avito-tech/go-transaction-manager (⭐395)](https://github.com/avito-tech/go-transaction-manager) — Transaction manager for Go ☆`395`
*   [fogfish/dynamo (⭐23)](https://github.com/fogfish/dynamo) — Generic Golang Key/Value trait for AWS storage services ☆`23`
*   [viant/dsc (⭐36)](https://github.com/viant/dsc) — Datastore Connectivity in go ☆`36`

### NoSQL Database Drivers

*   [redis/go-redis (⭐22k)](https://github.com/redis/go-redis) — Redis Go client ☆`22,035`
*   [gomodule/redigo (⭐9.9k)](https://github.com/gomodule/redigo) — Go client for Redis ☆`9,875`
*   [mongodb/mongo-go-driver (⭐8.5k)](https://github.com/mongodb/mongo-go-driver) — The Official Golang driver for MongoDB ☆`8,520`
*   [bradfitz/gomemcache (⭐1.9k)](https://github.com/bradfitz/gomemcache) — Go Memcached client library #golang ☆`1,868`
*   [qiniu/qmgo (⭐1.4k)](https://github.com/qiniu/qmgo) — Go driver for MongoDB ☆`1,351`
*   [Kamva/mgm (⭐763)](https://github.com/Kamva/mgm) — MongoDB ODM for Go based on official driver ☆`764`
*   [aerospike/aerospike-client-go (⭐459)](https://github.com/aerospike/aerospike-client-go) — Aerospike Client Go ☆`459`
*   [couchbase/gocb (⭐375)](https://github.com/couchbase/gocb) — The Couchbase Go SDK ☆`375`
*   [go-kivik/kivik (⭐341)](https://github.com/go-kivik/kivik) — CouchDB client interface ☆`341`
*   [couchbase/go-couchbase (⭐323)](https://github.com/couchbase/go-couchbase) — Couchbase client in Go ☆`323`
*   [chenmingyong0423/go-mongox (⭐217)](https://github.com/chenmingyong0423/go-mongox) — MongoDB driver wrapper with generics ☆`217`
*   [aliexpressru/gomemcached (⭐22)](https://github.com/aliexpressru/gomemcached) — Binary Memcached client with sharding ☆`22`
*   [btnguyen2k/gocosmos (⭐22)](https://github.com/btnguyen2k/gocosmos) — Go database/sql driver for Azure Cosmos DB SQL API ☆`22`

### ORM

*   [go-gorm/gorm (⭐40k)](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,672`
*   [ent/ent (⭐17k)](https://github.com/ent/ent) — An entity framework for Go ☆`17,020`
*   [aarondl/sqlboiler (⭐7k)](https://github.com/aarondl/sqlboiler) — Generate a Go ORM tailored to your database schema. ☆`6,984`
*   [uptrace/bun (⭐4.7k)](https://github.com/uptrace/bun) — SQL-first Golang ORM ☆`4,749`
*   [upper/db (⭐3.7k)](https://github.com/upper/db) — Data access layer for databases ☆`3,652`
*   [stephenafamo/bob (⭐1.7k)](https://github.com/stephenafamo/bob) — SQL builder with ORM generator ☆`1,702`
*   [huandu/go-sqlbuilder (⭐1.7k)](https://github.com/huandu/go-sqlbuilder) — SQL builder with zero-config ORM ☆`1,691`
*   [go-rel/rel (⭐782)](https://github.com/go-rel/rel) — Modern ORM for Golang ☆`782`
*   [hashicorp/go-dbw (⭐17)](https://github.com/hashicorp/go-dbw) — A simple package that encapsulates database operations. ☆`17`
*   [FrancoLiberali/cql (⭐17)](https://github.com/FrancoLiberali/cql) — CQL: Compiled Query Language ☆`17`

### Query Language

*   [99designs/gqlgen (⭐11k)](https://github.com/99designs/gqlgen) — go generate based graphql server library ☆`10,708`
*   [TomWright/dasel (⭐7.9k)](https://github.com/TomWright/dasel) — Query and modify data formats ☆`7,905`
*   [graph-gophers/graphql-go (⭐4.7k)](https://github.com/graph-gophers/graphql-go) — GraphQL server with a focus on ease of use ☆`4,747`
*   [bhmj/jsonslice (⭐92)](https://github.com/bhmj/jsonslice) — json slicer ☆`92`
*   [hashicorp/mql (⭐65)](https://github.com/hashicorp/mql) — Model Query Language (mql) is a query language for your database models. ☆`65`
*   [ccbrown/api-fu (⭐57)](https://github.com/ccbrown/api-fu) — A collection of Go packages for creating robust GraphQL APIs ☆`57`
*   [AsaiYusuke/jsonpath (⭐30)](https://github.com/AsaiYusuke/jsonpath) — JSONPath query library ☆`30`

### Relational Database Drivers

*   [go-sql-driver/mysql (⭐15k)](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,287`
*   [jackc/pgx (⭐14k)](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`13,625`
*   [denisenkom/go-mssqldb (⭐1.9k)](https://github.com/denisenkom/go-mssqldb) — Microsoft SQL server driver written in go language ☆`1,883`
*   [ncruces/go-sqlite3 (⭐963)](https://github.com/ncruces/go-sqlite3) — Go bindings to SQLite using wasm2go ☆`966`
*   [godror/godror (⭐591)](https://github.com/godror/godror) — GO DRiver for ORacle DB ☆`591`
*   [cvilsmeier/sqinn-go (⭐526)](https://github.com/cvilsmeier/sqinn-go) — Golang SQLite without cgo ☆`526`
*   [VinGarcia/ksql (⭐355)](https://github.com/VinGarcia/ksql) — A Simple and Powerful Golang SQL Library ☆`355`
*   [surrealdb/surrealdb.go (⭐309)](https://github.com/surrealdb/surrealdb.go) — SurrealDB SDK for Golang ☆`309`
*   [nakagami/firebirdsql (⭐256)](https://github.com/nakagami/firebirdsql) — Firebird RDBMS sql driver for Go (golang) ☆`256`
*   [ydb-platform/ydb-go-sdk (⭐178)](https://github.com/ydb-platform/ydb-go-sdk) — Pure Go native and database/sql driver for YDB ☆`178`
*   [rqlite/gorqlite (⭐181)](https://github.com/rqlite/gorqlite) — A Go client for rqlite, the distributed database built on SQLite ☆`181`
*   [apache/calcite-avatica-go (⭐124)](https://github.com/apache/calcite-avatica-go) — Apache Calcite Go ☆`124`

### SQL Query Builders

*   [sqlc-dev/sqlc (⭐17k)](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`17,330`
*   [xo/dbtpl (⭐3.9k)](https://github.com/xo/dbtpl) — Generate Go code for databases ☆`3,892`
*   [go-jet/jet (⭐3.6k)](https://github.com/go-jet/jet) — Type-safe SQL builder with codegen ☆`3,640`
*   [doug-martin/goqu (⭐2.6k)](https://github.com/doug-martin/goqu) — SQL builder and query library for golang ☆`2,647`
*   [didi/gendry (⭐1.6k)](https://github.com/didi/gendry) — a golang library for sql builder ☆`1,638`
*   [lqs/sqlingo (⭐450)](https://github.com/lqs/sqlingo) — A lightweight DSL & ORM which helps you to write SQL in Go. ☆`450`
*   [nullism/bqb (⭐189)](https://github.com/nullism/bqb) — Lightweight query builder ☆`190`
*   [arthurkushman/buildsqlx (⭐185)](https://github.com/arthurkushman/buildsqlx) — Go database query builder library for PostgreSQL ☆`185`
*   [galeone/igor (⭐126)](https://github.com/galeone/igor) — igor is an abstraction layer for PostgreSQL with a gorm like syntax. ☆`126`
*   [cristalhq/builq (⭐97)](https://github.com/cristalhq/builq) — Easily build SQL queries in Go. ☆`97`
*   [JiveGroup/FluentSQL (⭐18)](https://github.com/JiveGroup/FluentSQL) — Fluent SQL - flexible and powerful SQL string builder ☆`18`

### Search and Analytic Databases

*   [elastic/go-elasticsearch (⭐6k)](https://github.com/elastic/go-elasticsearch) — The official Go client for Elasticsearch ☆`6,040`
*   [ClickHouse/clickhouse-go (⭐3.3k)](https://github.com/ClickHouse/clickhouse-go) — Golang driver for ClickHouse ☆`3,268`
*   [sourcegraph/zoekt (⭐1.5k)](https://github.com/sourcegraph/zoekt) — Fast trigram-based code search ☆`1,543`
*   [sdqri/effdsl (⭐34)](https://github.com/sdqri/effdsl) — Elasticsearch query builder for golang ☆`34`

## DevOps & Build

### Backup

*   [restic/restic (⭐33k)](https://github.com/restic/restic) — Fast, secure backup program ☆`33,082`
*   [gilbertchen/duplicacy (⭐5.6k)](https://github.com/gilbertchen/duplicacy) — Cloud backup tool ☆`5,640`

### Build Automation

*   [air-verse/air (⭐23k)](https://github.com/air-verse/air) — Live reload for Go apps ☆`23,328`
*   [go-task/task (⭐15k)](https://github.com/go-task/task) — Fast cross-platform build tool inspired by Make ☆`15,291`
*   [joerdav/xc (⭐1.4k)](https://github.com/joerdav/xc) — Markdown defined task runner. ☆`1,377`
*   [goyek/goyek (⭐683)](https://github.com/goyek/goyek) — Task automation Go library ☆`684`
*   [flowexec/flow (⭐133)](https://github.com/flowexec/flow) — Local developer automation platform that flows with you ☆`133`

### CI/CD

*   [harness/harness (⭐35k)](https://github.com/harness/harness) — End-to-end developer platform ☆`34,631`
*   [woodpecker-ci/woodpecker (⭐6.8k)](https://github.com/woodpecker-ci/woodpecker) — Simple, powerful CI/CD engine ☆`6,804`
*   [ovh/cds (⭐4.8k)](https://github.com/ovh/cds) — Enterprise CI/CD platform ☆`4,806`
*   [raviqqe/muffet (⭐2.6k)](https://github.com/raviqqe/muffet) — Fast website link checker ☆`2,593`
*   [pipe-cd/pipecd (⭐1.3k)](https://github.com/pipe-cd/pipecd) — The One CD for All {applications, platforms, operations} ☆`1,268`
*   [jenkins-zh/jenkins-cli (⭐414)](https://github.com/jenkins-zh/jenkins-cli) — Jenkins CLI allows you to manage your Jenkins in an easy way ☆`414`
*   [vladopajic/go-test-coverage (⭐225)](https://github.com/vladopajic/go-test-coverage) — Report test coverage threshold issues ☆`225`
*   [appleboy/drone-scp (⭐166)](https://github.com/appleboy/drone-scp) — Copy files via SSH for Drone ☆`166`
*   [nikogura/gomason (⭐66)](https://github.com/nikogura/gomason) — A tool for testing, building, signing, and publishing binaries. ☆`66`
*   [appleboy/drone-jenkins (⭐41)](https://github.com/appleboy/drone-jenkins) — Drone plugin for trigger Jenkins jobs. ☆`41`
*   [opnlabs/dot (⭐35)](https://github.com/opnlabs/dot) — Minimal CI using Docker ☆`35`
*   [gha-common/go-beautiful-html-coverage (⭐23)](https://github.com/gha-common/go-beautiful-html-coverage) — GitHub Action for code coverage reports ☆`23`

### Containers

*   [moby/moby (⭐72k)](https://github.com/moby/moby) — Container ecosystem components ☆`71,485`
*   [traefik/traefik (⭐63k)](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`62,666`
*   [ko-build/ko (⭐8.4k)](https://github.com/ko-build/ko) — Build and deploy Go applications ☆`8,403`
*   [s0rg/decompose (⭐129)](https://github.com/s0rg/decompose) — Reverse-engineering tool for docker environments ☆`129`
*   [x1unix/docker-go-mingw (⭐53)](https://github.com/x1unix/docker-go-mingw) — Docker for Go with MinGW toolchain ☆`53`

### DevOps Utilities

*   [go-gitea/gitea (⭐55k)](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`54,858`
*   [moovweb/gvm (⭐12k)](https://github.com/moovweb/gvm) — Go Version Manager ☆`11,591`
*   [TwiN/gatus (⭐11k)](https://github.com/TwiN/gatus) — Developer-oriented status page with alerting ☆`10,643`
*   [bitfield/script (⭐7k)](https://github.com/bitfield/script) — Making it easy to write shell-like scripts in Go ☆`6,958`
*   [fleetdm/fleet (⭐6.2k)](https://github.com/fleetdm/fleet) — Open device management ☆`6,241`
*   [taubyte/tau (⭐5k)](https://github.com/taubyte/tau) — Fullstack Workspace for Humans & Machines ☆`5,003`
*   [megaease/easeprobe (⭐2.3k)](https://github.com/megaease/easeprobe) — Service health monitoring tool ☆`2,301`
*   [ajvb/kala (⭐2.2k)](https://github.com/ajvb/kala) — Modern Job Scheduler ☆`2,159`
*   [gabrie30/ghorg (⭐2k)](https://github.com/gabrie30/ghorg) — Clone entire GitHub orgs ☆`2,012`
*   [sanbornm/go-selfupdate (⭐1.7k)](https://github.com/sanbornm/go-selfupdate) — Enable your Go applications to self update ☆`1,685`
*   [yusufcanb/tlm (⭐1.5k)](https://github.com/yusufcanb/tlm) — Local CLI Copilot, powered by Ollama. ☆`1,478`
*   [ovh/utask (⭐1.4k)](https://github.com/ovh/utask) — Automation engine with YAML config ☆`1,374`
*   [TimothyYe/skm (⭐1k)](https://github.com/TimothyYe/skm) — A simple and powerful SSH keys manager ☆`1,009`
*   [scaleway/scaleway-cli (⭐964)](https://github.com/scaleway/scaleway-cli) — Command Line Interface for Scaleway ☆`964`
*   [alexliesenfeld/health (⭐829)](https://github.com/alexliesenfeld/health) — A simple and flexible health check library for Go. ☆`829`
*   [kool-dev/kool (⭐716)](https://github.com/kool-dev/kool) — Dev to cloud web apps made easy ☆`716`
*   [kevincobain2000/gobrew (⭐416)](https://github.com/kevincobain2000/gobrew) — Go version manager without root ☆`416`
*   [appleboy/easyssh-proxy (⭐346)](https://github.com/appleboy/easyssh-proxy) — Simple SSH protocol implementation ☆`346`
*   [xitonix/trubka (⭐337)](https://github.com/xitonix/trubka) — A CLI tool for Kafka ☆`337`
*   [emicklei/mora (⭐315)](https://github.com/emicklei/mora) — MongoDB generic REST server in Go ☆`315`
*   [thevxn/dish (⭐276)](https://github.com/thevxn/dish) — A simple, remotely configurable monitoring service. ☆`276`
*   [jkaninda/goma-gateway (⭐176)](https://github.com/jkaninda/goma-gateway) — Lightweight API gateway and proxy ☆`176`
*   [datarootsio/tf-profile (⭐165)](https://github.com/datarootsio/tf-profile) — Profile Terraform runs ☆`165`
*   [kazhuravlev/healthcheck (⭐22)](https://github.com/kazhuravlev/healthcheck) — Readiness probes for Kubernetes application ☆`23`

### Infrastructure

*   [hashicorp/packer (⭐16k)](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,640`
*   [pomerium/pomerium (⭐4.7k)](https://github.com/pomerium/pomerium) — Pomerium is an identity and context-aware access proxy. ☆`4,738`
*   [peak/s5cmd (⭐4k)](https://github.com/peak/s5cmd) — Parallel S3 and local filesystem execution tool. ☆`3,997`
*   [aptly-dev/aptly (⭐2.8k)](https://github.com/aptly-dev/aptly) — aptly - Debian repository management tool ☆`2,802`
*   [KusionStack/kusion (⭐1.3k)](https://github.com/KusionStack/kusion) — Declarative platform orchestrator ☆`1,288`
*   [oxyno-zeta/s3-proxy (⭐448)](https://github.com/oxyno-zeta/s3-proxy) — S3 reverse proxy with auth ☆`449`

### Kubernetes

*   [kubernetes/kubernetes (⭐122k)](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`121,679`
*   [k3s-io/k3s (⭐33k)](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`32,728`
*   [kubernetes/minikube (⭐32k)](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,688`
*   [kubernetes-sigs/kind (⭐15k)](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,159`
*   [kubeshark/kubeshark (⭐12k)](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`11,868`
*   [flannel-io/flannel (⭐9.4k)](https://github.com/flannel-io/flannel) — Network fabric for containers ☆`9,435`
*   [getanteon/anteon (⭐8.5k)](https://github.com/getanteon/anteon) — eBPF Kubernetes monitoring tool ☆`8,538`
*   [kubevela/kubevela (⭐7.7k)](https://github.com/kubevela/kubevela) — The Modern Application Platform. ☆`7,731`
*   [k3d-io/k3d (⭐6.4k)](https://github.com/k3d-io/k3d) — Little helper to run CNCF's k3s in Docker ☆`6,373`
*   [stefanprodan/podinfo (⭐5.9k)](https://github.com/stefanprodan/podinfo) — Go microservice template for Kubernetes ☆`5,881`
*   [apecloud/kubeblocks (⭐3k)](https://github.com/apecloud/kubeblocks) — Kubernetes operator for databases ☆`3,007`
*   [kubenetworks/kubevpn (⭐1.3k)](https://github.com/kubenetworks/kubevpn) — Connect to Kubernetes cluster network ☆`1,307`
*   [abahmed/kwatch (⭐1k)](https://github.com/abahmed/kwatch) — monitor & detect crashes in your Kubernetes(K8s) cluster instantly ☆`1,001`
*   [getanteon/alaz (⭐718)](https://github.com/getanteon/alaz) — eBPF agent for K8s observability ☆`718`

### Load Testing

*   [grafana/k6 (⭐30k)](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`30,337`
*   [tsenart/vegeta (⭐25k)](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`24,996`
*   [codesenberg/bombardier (⭐6.8k)](https://github.com/codesenberg/bombardier) — Fast cross-platform HTTP benchmarking tool written in Go ☆`6,761`
*   [rogerwelin/cassowary (⭐808)](https://github.com/rogerwelin/cassowary) — Modern cross-platform HTTP load-testing tool written in Go ☆`809`

## Email

*   [axllent/mailpit (⭐9.1k)](https://github.com/axllent/mailpit) — An email and SMTP testing tool with API for developers ☆`9,140`
*   [foxcpp/maddy (⭐5.9k)](https://github.com/foxcpp/maddy) — Composable all-in-one mail server. ☆`5,920`
*   [mjl-/mox (⭐5.6k)](https://github.com/mjl-/mox) — Modern secure mail server ☆`5,631`
*   [matcornic/hermes (⭐3k)](https://github.com/matcornic/hermes) — Clean HTML email generator ☆`3,003`
*   [AfterShip/email-verifier (⭐1.5k)](https://github.com/AfterShip/email-verifier) — Email verification without sending emails ☆`1,551`
*   [wneessen/go-mail (⭐1.3k)](https://github.com/wneessen/go-mail) — Easy to use, yet comprehensive library for sending mails with Go ☆`1,335`
*   [sendgrid/sendgrid-go (⭐1.1k)](https://github.com/sendgrid/sendgrid-go) — The Official Twilio SendGrid Golang API Library ☆`1,053`
*   [mailgun/mailgun-go (⭐745)](https://github.com/mailgun/mailgun-go) — Go library for the Mailgun API. ☆`745`
*   [xhit/go-simple-mail (⭐694)](https://github.com/xhit/go-simple-mail) — Simple mail sending with TLS/SSL ☆`694`
*   [emersion/go-message (⭐443)](https://github.com/emersion/go-message) — Internet Message Format library ☆`443`
*   [vanng822/go-premailer (⭐196)](https://github.com/vanng822/go-premailer) — Inline CSS for HTML mail ☆`196`
*   [truemail-rb/truemail-go (⭐131)](https://github.com/truemail-rb/truemail-go) — Email validator via Regex, DNS, SMTP ☆`131`
*   [toorop/go-dkim (⭐99)](https://github.com/toorop/go-dkim) — DKIM package for golang ☆`99`
*   [dimuska139/go-email-normalizer (⭐78)](https://github.com/dimuska139/go-email-normalizer) — Normalize email addresses ☆`78`
*   [valord577/mailx (⭐21)](https://github.com/valord577/mailx) — A library that makes it easier to send email via SMTP. ☆`21`

## Finance & Blockchain

### Blockchain

*   [ethereum/go-ethereum (⭐51k)](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`50,977`
*   [ipfs/kubo (⭐17k)](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`16,985`
*   [lightningnetwork/lnd (⭐8.1k)](https://github.com/lightningnetwork/lnd) — Lightning Network Daemon ☆`8,128`
*   [cosmos/cosmos-sdk (⭐7k)](https://github.com/cosmos/cosmos-sdk) — A Framework for Building High Value Public Blockchains ☆`6,978`
*   [solana-foundation/solana-go (⭐1.5k)](https://github.com/solana-foundation/solana-go) — Go SDK library and RPC client for the Solana Blockchain ☆`1,539`
*   [gnolang/gno (⭐1.1k)](https://github.com/gnolang/gno) — Interpreted Go virtual machine ☆`1,065`
*   [cometbft/cometbft (⭐878)](https://github.com/cometbft/cometbft) — Byzantine fault-tolerant consensus ☆`878`
*   [ChainSafe/gossamer (⭐454)](https://github.com/ChainSafe/gossamer) — Go Implementation of the Polkadot Host ☆`454`

### Financial

*   [shopspring/decimal (⭐7.3k)](https://github.com/shopspring/decimal) — Arbitrary-precision fixed-point decimal numbers in Go ☆`7,303`
*   [achannarasappa/ticker (⭐6k)](https://github.com/achannarasappa/ticker) — Terminal stock and crypto tracker ☆`6,031`
*   [Rhymond/go-money (⭐1.9k)](https://github.com/Rhymond/go-money) — Go implementation of Fowler's Money pattern ☆`1,884`
*   [c9s/bbgo (⭐1.6k)](https://github.com/c9s/bbgo) — The modern cryptocurrency trading bot framework written in Go. ☆`1,624`
*   [formancehq/ledger (⭐1.2k)](https://github.com/formancehq/ledger) — The programmable open source core ledger for fintech ☆`1,194`
*   [bojanz/currency (⭐632)](https://github.com/bojanz/currency) — Currency handling for Go. ☆`635`
*   [moov-io/ach (⭐536)](https://github.com/moov-io/ach) — ACH file reader, writer, validator ☆`537`
*   [invopop/gobl (⭐271)](https://github.com/invopop/gobl) — Go Business Language ☆`273`
*   [govalues/decimal (⭐234)](https://github.com/govalues/decimal) — Correctly rounded decimals for Go ☆`234`
*   [quagmt/udecimal (⭐178)](https://github.com/quagmt/udecimal) — High-precision decimal library ☆`180`
*   [jovandeginste/payme (⭐91)](https://github.com/jovandeginste/payme) — QR code generator (ASCII & PNG) for SEPA payments ☆`91`
*   [jokruger/dec128 (⭐43)](https://github.com/jokruger/dec128) — High performance 128-bit fixed-point decimal numbers in go. ☆`43`
*   [nikolaydubina/fpmoney (⭐35)](https://github.com/nikolaydubina/fpmoney) — Fixed-Point Decimal Money ☆`35`
*   [nikolaydubina/fpdecimal (⭐34)](https://github.com/nikolaydubina/fpdecimal) — Fixed-Point Decimals ☆`34`
*   [govalues/money (⭐51)](https://github.com/govalues/money) — Correctly rounded monetary amounts and exchange rates for Go ☆`51`

### Payment APIs

*   [stripe/stripe-go (⭐2.6k)](https://github.com/stripe/stripe-go) — Stripe API library for Go ☆`2,562`
*   [plutov/paypal (⭐775)](https://github.com/plutov/paypal) — Golang client for PayPal REST API ☆`775`
*   [brunomvsouza/ynab.go (⭐78)](https://github.com/brunomvsouza/ynab.go) — Client for YNAB API ☆`78`

## GUI & Desktop

### GUI

*   [fyne-io/fyne (⭐28k)](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`28,110`
*   [webview/webview (⭐14k)](https://github.com/webview/webview) — Tiny webview library for Go ☆`14,010`
*   [go-vgo/robotgo (⭐11k)](https://github.com/go-vgo/robotgo) — Cross-platform RPA and GUI automation ☆`10,681`
*   [maxence-charriere/go-app (⭐8.9k)](https://github.com/maxence-charriere/go-app) — Build progressive web apps with Go and WASM ☆`8,879`
*   [progrium/darwinkit (⭐5.4k)](https://github.com/progrium/darwinkit) — Native Mac APIs for Go. Previously known as MacDriver ☆`5,413`
*   [getlantern/systray (⭐3.7k)](https://github.com/getlantern/systray) — Cross-platform systray library ☆`3,684`
*   [cogentcore/core (⭐2.3k)](https://github.com/cogentcore/core) — Powerful GUI framework for Go ☆`2,315`
*   [gotk3/gotk3 (⭐2.2k)](https://github.com/gotk3/gotk3) — Go bindings for GTK3 ☆`2,206`
*   [roblillack/spot (⭐1.3k)](https://github.com/roblillack/spot) — React-like desktop GUI toolkit for Go ☆`1,258`
*   [ncruces/zenity (⭐901)](https://github.com/ncruces/zenity) — Zenity dialogs for Golang, Windows, macOS ☆`903`
*   [energye/energy (⭐585)](https://github.com/energye/energy) — CEF-based GUI framework ☆`586`
*   [AllenDang/cimgui-go (⭐507)](https://github.com/AllenDang/cimgui-go) — Auto generated Go wrapper for Dear ImGui via cimgui ☆`507`
*   [richardwilkes/unison (⭐320)](https://github.com/richardwilkes/unison) — Unified GUI toolkit for Go ☆`320`

### Windows

*   [go-ole/go-ole (⭐1.3k)](https://github.com/go-ole/go-ole) — win32 ole implementation for golang ☆`1,301`
*   [gonutz/d3d9 (⭐163)](https://github.com/gonutz/d3d9) — Direct3D9 wrapper for Go. ☆`163`

## Game Development

### Game Engines

*   [hajimehoshi/ebiten (⭐13k)](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`13,087`
*   [fogleman/nes (⭐5.6k)](https://github.com/fogleman/nes) — NES emulator written in Go. ☆`5,641`
*   [topfreegames/pitaya (⭐2.8k)](https://github.com/topfreegames/pitaya) — Game server with clustering support ☆`2,764`
*   [xiaonanln/goworld (⭐2.7k)](https://github.com/xiaonanln/goworld) — Distributed game server engine ☆`2,708`
*   [gen2brain/raylib-go (⭐2.4k)](https://github.com/gen2brain/raylib-go) — Go bindings for raylib ☆`2,400`
*   [oakmound/oak (⭐1.7k)](https://github.com/oakmound/oak) — A pure Go game engine ☆`1,655`
*   [JoelOtter/termloop (⭐1.5k)](https://github.com/JoelOtter/termloop) — Terminal-based game engine for Go, built on top of Termbox ☆`1,473`
*   [gopxl/pixel (⭐387)](https://github.com/gopxl/pixel) — A hand-crafted 2D game library in Go. ☆`387`
*   [ungerik/go3d (⭐336)](https://github.com/ungerik/go3d) — A performance oriented 2D/3D math package for Go ☆`336`
*   [mlange-42/ark (⭐237)](https://github.com/mlange-42/ark) — Ark -- Archetype-based Entity Component System (ECS) for Go. ☆`240`
*   [kelindar/tile (⭐218)](https://github.com/kelindar/tile) — 2D grid engine for games ☆`218`
*   [andygeiss/ecs (⭐172)](https://github.com/andygeiss/ecs) — Entity Component System for games ☆`172`
*   [gonutz/prototype (⭐107)](https://github.com/gonutz/prototype) — 2D game prototyping framework ☆`107`
*   [s0rg/fantasyname (⭐41)](https://github.com/s0rg/fantasyname) — RinkWorks fantasy name generator for golang ☆`41`
*   [s0rg/grid (⭐25)](https://github.com/s0rg/grid) — Generic 2D grid ☆`25`

### OpenGL

*   [go-gl/glfw (⭐1.7k)](https://github.com/go-gl/glfw) — Go bindings for GLFW 3 ☆`1,666`
*   [go-gl/gl (⭐1.2k)](https://github.com/go-gl/gl) — Go bindings for OpenGL (generated via glow) ☆`1,191`
*   [go-gl/mathgl (⭐602)](https://github.com/go-gl/mathgl) — A pure Go 3D math library. ☆`602`

## Geospatial

*   [tidwall/tile38 (⭐9.6k)](https://github.com/tidwall/tile38) — Real-time Geospatial and Geofencing ☆`9,615`
*   [golang/geo (⭐1.8k)](https://github.com/golang/geo) — S2 geometry library in Go ☆`1,830`
*   [consbio/mbtileserver (⭐780)](https://github.com/consbio/mbtileserver) — MBTiles server in Go ☆`780`
*   [spatial-go/geoos (⭐531)](https://github.com/spatial-go/geoos) — Spatial data and geometric algorithms ☆`530`
*   [paulmach/osm (⭐451)](https://github.com/paulmach/osm) — OpenStreetMap data library ☆`451`
*   [uber/h3-go (⭐418)](https://github.com/uber/h3-go) — H3 hexagonal geospatial indexing ☆`419`
*   [peterstace/simplefeatures (⭐172)](https://github.com/peterstace/simplefeatures) — OpenGIS Simple Feature implementation ☆`172`
*   [airbusgeo/godal (⭐174)](https://github.com/airbusgeo/godal) — GDAL wrapper for Go ☆`174`
*   [wroge/wgs84 (⭐141)](https://github.com/wroge/wgs84) — Zero-dep coordinate transformations ☆`141`
*   [pantrif/s2-geojson (⭐37)](https://github.com/pantrif/s2-geojson) — Visualize S2 cells on a map ☆`37`

## Go Tooling

### Compilers

*   [gopherjs/gopherjs (⭐13k)](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,139`
*   [yassinebenaid/bunster (⭐2.7k)](https://github.com/yassinebenaid/bunster) — Compile shell scripts to static binaries. ☆`2,658`
*   [Konstantin8105/c4go (⭐378)](https://github.com/Konstantin8105/c4go) — Transpiling C code to Go code ☆`378`
*   [go2hx/go2hx (⭐150)](https://github.com/go2hx/go2hx) — Import Go libraries in Haxe ☆`150`

### Editor Plugins

*   [fatih/vim-go (⭐16k)](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,230`
*   [visualfc/liteide (⭐7.7k)](https://github.com/visualfc/liteide) — LiteIDE is a simple, open source, cross-platform Go IDE. ☆`7,747`
*   [nsf/gocode (⭐5k)](https://github.com/nsf/gocode) — An autocompletion daemon for the Go programming language ☆`4,998`
*   [golang/vscode-go (⭐4.2k)](https://github.com/golang/vscode-go) — Go extension for Visual Studio Code ☆`4,233`
*   [dominikh/go-mode.el (⭐1.5k)](https://github.com/dominikh/go-mode.el) — Emacs mode for the Go programming language ☆`1,452`
*   [incu6us/goimports-reviser (⭐716)](https://github.com/incu6us/goimports-reviser) — Imports sorting and code formatting tool ☆`716`

### Generate Tools

*   [xuri/xgen (⭐408)](https://github.com/xuri/xgen) — XSD parser and code generator ☆`408`
*   [kazhuravlev/options-gen (⭐104)](https://github.com/kazhuravlev/options-gen) — Codegen for functional options in go projects ☆`105`
*   [g4s8/envdoc (⭐95)](https://github.com/g4s8/envdoc) — Go tool to generate documentation for environment variables ☆`95`

### Go Tools

*   [go-swagger/go-swagger (⭐10k)](https://github.com/go-swagger/go-swagger) — Swagger 2.0 implementation for go ☆`9,968`
*   [ondrajz/go-callvis (⭐6.5k)](https://github.com/ondrajz/go-callvis) — Visualize call graph of a Go program using Graphviz ☆`6,468`
*   [Zxilly/go-size-analyzer (⭐2.1k)](https://github.com/Zxilly/go-size-analyzer) — Analyze compiled Go binary size ☆`2,122`
*   [pointlander/peg (⭐1.1k)](https://github.com/pointlander/peg) — PEG parser generator for Go ☆`1,108`
*   [safedep/vet (⭐1k)](https://github.com/safedep/vet) — Protect against malicious open source packages ☆`1,009`
*   [janpfeifer/gonb (⭐1k)](https://github.com/janpfeifer/gonb) — Go notebook kernel for Jupyter ☆`1,009`
*   [alajmo/sake (⭐742)](https://github.com/alajmo/sake) — Task runner for local and remote hosts ☆`742`
*   [goccmack/gocc (⭐658)](https://github.com/goccmack/gocc) — Parser and scanner generator ☆`658`
*   [moshebe/gebug (⭐634)](https://github.com/moshebe/gebug) — Debug Dockerized Go apps ☆`634`
*   [iyashjayesh/monigo (⭐407)](https://github.com/iyashjayesh/monigo) — Performance monitoring library ☆`407`
*   [edwingeng/hotswap (⭐423)](https://github.com/edwingeng/hotswap) — Hot reload Go code without restart ☆`424`
*   [becheran/roumon (⭐234)](https://github.com/becheran/roumon) — Universal goroutine monitor using pprof and termui ☆`234`
*   [bitfield/gotestdox (⭐193)](https://github.com/bitfield/gotestdox) — A tool for formatting Go test results as readable documentation ☆`193`
*   [ahmedakef/gotutor (⭐75)](https://github.com/ahmedakef/gotutor) — Online Go Debugger & Visualizer ☆`75`
*   [bobg/decouple (⭐36)](https://github.com/bobg/decouple) — find overspecified function parameters in Go code ☆`36`
*   [bobg/modver (⭐21)](https://github.com/bobg/modver) — a tool that helps you obey semantic versioning rules in your Go module ☆`21`
*   [dustinblackman/gomodrun (⭐38)](https://github.com/dustinblackman/gomodrun) — Run binaries from go.mod ☆`38`

## Hardware & IoT

### Hardware

*   [shirou/gopsutil (⭐12k)](https://github.com/shirou/gopsutil) — psutil for golang ☆`11,782`
*   [arduino/arduino-cli (⭐4.9k)](https://github.com/arduino/arduino-cli) — Arduino command line tool ☆`4,863`
*   [jaypipes/ghw (⭐1.8k)](https://github.com/jaypipes/ghw) — Go HardWare discovery/inspection library ☆`1,844`
*   [zcalusic/sysinfo (⭐575)](https://github.com/zcalusic/sysinfo) — Linux system information library ☆`575`

### IoT

*   [hybridgroup/gobot (⭐9.4k)](https://github.com/hybridgroup/gobot) — Robotics and IoT framework ☆`9,392`
*   [lf-edge/ekuiper (⭐1.7k)](https://github.com/lf-edge/ekuiper) — Lightweight data stream processing engine for IoT edge ☆`1,695`
*   [rulego/rulego (⭐1.5k)](https://github.com/rulego/rulego) — Lightweight rule engine framework ☆`1,479`
*   [Edgenesis/shifu (⭐1.4k)](https://github.com/Edgenesis/shifu) — Kubernetes-native IoT gateway ☆`1,412`
*   [e154/smart-home (⭐97)](https://github.com/e154/smart-home) — software package for automation ☆`97`
*   [maxatome/go-vitotrol (⭐23)](https://github.com/maxatome/go-vitotrol) — golang client library to Viessmann Vitotrol web service ☆`23`

## Networking

### Consensus

*   [hashicorp/raft (⭐9k)](https://github.com/hashicorp/raft) — Golang implementation of the Raft consensus protocol ☆`8,988`
*   [lni/dragonboat (⭐5.3k)](https://github.com/lni/dragonboat) — Multi-group Raft consensus library ☆`5,301`
*   [etcd-io/raft (⭐1k)](https://github.com/etcd-io/raft) — Raft library for maintaining a replicated state machine ☆`1,012`
*   [vadiminshakov/committer (⭐41)](https://github.com/vadiminshakov/committer) — 2PC and 3PC protocols for Go ☆`41`

### DNS

*   [miekg/dns (⭐8.7k)](https://github.com/miekg/dns) — DNS library in Go ☆`8,671`
*   [0xERR0R/blocky (⭐6.5k)](https://github.com/0xERR0R/blocky) — DNS ad-blocker for local networks ☆`6,530`
*   [hashicorp/mdns (⭐1.4k)](https://github.com/hashicorp/mdns) — Simple mDNS client/server library in Golang ☆`1,358`
*   [semihalev/sdns (⭐1k)](https://github.com/semihalev/sdns) — High-performance recursive DNS ☆`1,034`
*   [FenkoHQ/dnsmonster (⭐353)](https://github.com/FenkoHQ/dnsmonster) — Passive DNS Capture and Monitoring Toolkit ☆`354`
*   [joeig/go-powerdns (⭐103)](https://github.com/joeig/go-powerdns) — PowerDNS API client for Go (community project) ☆`103`

### Distributed Utilities

*   [luraproject/lura (⭐6.8k)](https://github.com/luraproject/lura) — Ultra-performant API gateway ☆`6,758`
*   [chrislusf/gleam (⭐3.6k)](https://github.com/chrislusf/gleam) — Distributed map/reduce in Go ☆`3,559`
*   [bsm/redislock (⭐1.7k)](https://github.com/bsm/redislock) — Simplified distributed locking implementation using Redis ☆`1,746`
*   [k8gb-io/k8gb (⭐1.2k)](https://github.com/k8gb-io/k8gb) — A cloud native Kubernetes Global Balancer ☆`1,162`
*   [temporalio/sdk-go (⭐861)](https://github.com/temporalio/sdk-go) — Temporal Go SDK ☆`864`
*   [AppsFlyer/go-sundheit (⭐560)](https://github.com/AppsFlyer/go-sundheit) — Health checks library for Go ☆`560`
*   [tarmac-project/tarmac (⭐343)](https://github.com/tarmac-project/tarmac) — Functions as Monolith or Microservices ☆`343`
*   [italolelis/outboxer (⭐166)](https://github.com/italolelis/outboxer) — A library that implements the outboxer pattern in go ☆`166`
*   [capillariesio/capillaries (⭐69)](https://github.com/capillariesio/capillaries) — Distributed batch data processing framework ☆`69`
*   [svcavallar/celeriac.v1 (⭐76)](https://github.com/svcavallar/celeriac.v1) — Celery client for Go ☆`76`
*   [pdupub/go-pdu (⭐49)](https://github.com/pdupub/go-pdu) — An PDU implementation in Go ☆`49`
*   [sanketplus/go-mysql-lock (⭐66)](https://github.com/sanketplus/go-mysql-lock) — MySQL Backed Locking Primitive ☆`66`

### HTTP & Proxy

*   [valyala/fasthttp (⭐23k)](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,327`
*   [elazarl/goproxy (⭐6.7k)](https://github.com/elazarl/goproxy) — An HTTP proxy library for Go ☆`6,656`
*   [wzshiming/httpproxy (⭐31)](https://github.com/wzshiming/httpproxy) — HTTP proxy handler and dialer ☆`31`

### HTTP Clients

*   [go-resty/resty (⭐12k)](https://github.com/go-resty/resty) — Simple HTTP, REST, and SSE client library for Go ☆`11,633`
*   [imroc/req (⭐4.8k)](https://github.com/imroc/req) — Simple Go HTTP client with Black Magic ☆`4,781`
*   [gojek/heimdall (⭐2.7k)](https://github.com/gojek/heimdall) — An enhanced HTTP client for Go ☆`2,706`
*   [hashicorp/go-retryablehttp (⭐2.3k)](https://github.com/hashicorp/go-retryablehttp) — Retryable HTTP client in Go ☆`2,298`
*   [levigross/grequests (⭐2.2k)](https://github.com/levigross/grequests) — A Go "clone" of the great and famous Requests library ☆`2,186`
*   [dghubble/sling (⭐1.7k)](https://github.com/dghubble/sling) — A Go HTTP client library for creating and sending API requests ☆`1,720`
*   [earthboundkid/requests (⭐1.7k)](https://github.com/earthboundkid/requests) — HTTP requests for Gophers ☆`1,669`
*   [bogdanfinn/tls-client (⭐1.6k)](https://github.com/bogdanfinn/tls-client) — HTTP client with TLS fingerprint spoofing ☆`1,562`
*   [Noooste/azuretls-client (⭐444)](https://github.com/Noooste/azuretls-client) — HTTP client to spoof TLS/JA3 fingerprint ☆`444`
*   [monaco-io/request (⭐295)](https://github.com/monaco-io/request) — go request, go http client ☆`295`
*   [opus-domini/fast-shot (⭐120)](https://github.com/opus-domini/fast-shot) — Fluent HTTP client for Go ☆`121`
*   [go-zoox/fetch (⭐89)](https://github.com/go-zoox/fetch) — Powerful HTTP client for Go ☆`89`
*   [NdoleStudio/go-otelroundtripper (⭐87)](https://github.com/NdoleStudio/go-otelroundtripper) — OpenTelemetry metrics for HTTP clients ☆`87`
*   [rezmoss/axios4go (⭐33)](https://github.com/rezmoss/axios4go) — Axios-inspired HTTP client ☆`33`
*   [lib4u/fake-useragent (⭐16)](https://github.com/lib4u/fake-useragent) — Up-to-date simple useragent faker with real world database in Golang ☆`16`

### Servers

*   [caddyserver/caddy (⭐71k)](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`71,488`
*   [pocketbase/pocketbase (⭐58k)](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`57,573`
*   [etcd-io/etcd (⭐52k)](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`51,617`
*   [drakkan/sftpgo (⭐12k)](https://github.com/drakkan/sftpgo) — Full-featured SFTP/FTP/HTTP server ☆`11,919`
*   [adnanh/webhook (⭐12k)](https://github.com/adnanh/webhook) — Lightweight webhook server ☆`11,731`
*   [roadrunner-server/roadrunner (⭐8.4k)](https://github.com/roadrunner-server/roadrunner) — High-performance PHP application server ☆`8,435`
*   [easegress-io/easegress (⭐5.9k)](https://github.com/easegress-io/easegress) — A Cloud Native traffic orchestration system ☆`5,870`
*   [charmbracelet/wish (⭐5.1k)](https://github.com/charmbracelet/wish) — Make SSH apps, just like that! ☆`5,122`
*   [flipt-io/flipt (⭐4.8k)](https://github.com/flipt-io/flipt) — Enterprise-ready, Git native feature management solution ☆`4,766`
*   [getfider/fider (⭐4.2k)](https://github.com/getfider/fider) — Open platform to collect and prioritize feedback ☆`4,208`
*   [xyproto/algernon (⭐3k)](https://github.com/xyproto/algernon) — Web server with Lua and Markdown ☆`2,999`
*   [openflagr/flagr (⭐2.6k)](https://github.com/openflagr/flagr) — Feature flagging and A/B testing ☆`2,585`
*   [thomaspoignant/go-feature-flag (⭐2k)](https://github.com/thomaspoignant/go-feature-flag) — Open source feature flag solution ☆`1,987`
*   [msoap/shell2http (⭐1.5k)](https://github.com/msoap/shell2http) — Executing shell commands via HTTP server ☆`1,485`
*   [openrundev/openrun (⭐821)](https://github.com/openrundev/openrun) — Open source Cloud Run alternative ☆`822`
*   [webhookx-io/webhookx (⭐294)](https://github.com/webhookx-io/webhookx) — The Next-Generation Webhooks Gateway. ☆`294`
*   [blind-oracle/cortex-tenant (⭐136)](https://github.com/blind-oracle/cortex-tenant) — Prometheus proxy with tenant ID injection ☆`136`
*   [baalimago/wd-41 (⭐151)](https://github.com/baalimago/wd-41) — Web-Development 41, a static web server with live-reload ☆`151`
*   [42atomys/webhooked (⭐42)](https://github.com/42atomys/webhooked) — A webhook receiver on steroids. ☆`42`

### Network Utilities

*   [fortio/fortio (⭐3.7k)](https://github.com/fortio/fortio) — Load testing and echo server ☆`3,689`
*   [hashicorp/go-getter (⭐1.8k)](https://github.com/hashicorp/go-getter) — Download files from URLs ☆`1,814`
*   [TimothyYe/godns (⭐1.7k)](https://github.com/TimothyYe/godns) — Dynamic DNS client for multiple providers ☆`1,745`
*   [cavaliergopher/grab (⭐1.5k)](https://github.com/cavaliergopher/grab) — Download manager package ☆`1,475`
*   [schollz/peerdiscovery (⭐669)](https://github.com/schollz/peerdiscovery) — Cross-platform local peer discovery ☆`669`
*   [fclairamb/ftpserverlib (⭐467)](https://github.com/fclairamb/ftpserverlib) — FTP server library for Go ☆`467`
*   [skibish/ddns (⭐267)](https://github.com/skibish/ddns) — Personal DDNS client with Digital Ocean Networking DNS as backend. ☆`267`
*   [assafmo/joincap (⭐221)](https://github.com/assafmo/joincap) — Merge pcap files ☆`221`
*   [gaissmai/bart (⭐135)](https://github.com/gaissmai/bart) — Balanced routing table ☆`135`
*   [alegrey91/fwdctl (⭐72)](https://github.com/alegrey91/fwdctl) — Manage IPTables forwards via CLI ☆`72`

### P2P & Torrent

*   [anacrolix/torrent (⭐6k)](https://github.com/anacrolix/torrent) — Full-featured BitTorrent client package and utilities ☆`6,010`
*   [dragonflyoss/dragonfly (⭐3.1k)](https://github.com/dragonflyoss/dragonfly) — P2P-based container image distribution ☆`3,129`
*   [cenkalti/rain (⭐1.1k)](https://github.com/cenkalti/rain) — BitTorrent client and library in Go ☆`1,118`
*   [anacrolix/dht (⭐354)](https://github.com/anacrolix/dht) — DHT for BitTorrent ☆`354`

### Protocols

*   [pion/webrtc (⭐16k)](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,208`
*   [quic-go/quic-go (⭐12k)](https://github.com/quic-go/quic-go) — A production-ready QUIC implementation in pure Go ☆`11,531`
*   [google/gopacket (⭐6.8k)](https://github.com/google/gopacket) — Provides packet processing capabilities for Go ☆`6,765`
*   [osrg/gobgp (⭐4k)](https://github.com/osrg/gobgp) — BGP implemented in the Go Programming Language ☆`4,028`
*   [lxzan/gws (⭐1.8k)](https://github.com/lxzan/gws) — Fast websocket server and client ☆`1,752`
*   [gosnmp/gosnmp (⭐1.2k)](https://github.com/gosnmp/gosnmp) — An SNMP library written in Go ☆`1,247`
*   [bluenviron/gortsplib (⭐906)](https://github.com/bluenviron/gortsplib) — RTSP client and server library for the Go programming language ☆`906`
*   [ccding/go-stun (⭐721)](https://github.com/ccding/go-stun) — A go implementation of the STUN client (RFC 3489 and RFC 5389) ☆`720`
*   [google/gnxi (⭐282)](https://github.com/google/gnxi) — gNXI Tools - gRPC Network Management/Operations Interface Tools ☆`282`
*   [jeroenrinzema/psql-wire (⭐230)](https://github.com/jeroenrinzema/psql-wire) — PostgreSQL wire protocol for Go ☆`230`
*   [jimlambrt/gldap (⭐120)](https://github.com/jimlambrt/gldap) — Build LDAP services w/ Go ☆`120`
*   [soypat/natiu-mqtt (⭐104)](https://github.com/soypat/natiu-mqtt) — Extensible MQTT for embedded systems ☆`104`

### RPC

*   [grpc/grpc-go (⭐23k)](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,900`
*   [lesismal/arpc (⭐1.1k)](https://github.com/lesismal/arpc) — Two-way RPC with broadcast support ☆`1,088`
*   [ybbus/jsonrpc (⭐370)](https://github.com/ybbus/jsonrpc) — A simple go implementation of json rpc 2.0 client over http ☆`370`
*   [osamingo/jsonrpc (⭐193)](https://github.com/osamingo/jsonrpc) — The jsonrpc package helps implement of JSON-RPC 2.0 ☆`193`

### SSH & SFTP

*   [gliderlabs/ssh (⭐4.1k)](https://github.com/gliderlabs/ssh) — Easy SSH servers in Golang ☆`4,124`
*   [pkg/sftp (⭐1.6k)](https://github.com/pkg/sftp) — SFTP support for the go.crypto/ssh package ☆`1,637`
*   [masterzen/winrm (⭐465)](https://github.com/masterzen/winrm) — Windows remote command library ☆`465`

### TCP/UDP Frameworks

*   [panjf2000/gnet (⭐11k)](https://github.com/panjf2000/gnet) — High-performance event-loop network ☆`11,127`
*   [cloudwego/netpoll (⭐4.5k)](https://github.com/cloudwego/netpoll) — High-performance I/O framework ☆`4,551`
*   [xtaci/kcp-go (⭐4.5k)](https://github.com/xtaci/kcp-go) — A crypto-secure Reliable-UDP library for Golang with FEC support. ☆`4,477`
*   [lesismal/nbio (⭐2.7k)](https://github.com/lesismal/nbio) — High-performance network library ☆`2,717`
*   [xtaci/gaio (⭐1k)](https://github.com/xtaci/gaio) — High-performance, minimalist async-io (proactor) networking for Golang. ☆`990`
*   [cheng-zhongliang/event (⭐119)](https://github.com/cheng-zhongliang/event) — Simple I/O event notification library wirtten in Golang ☆`119`
*   [fish-tennis/gnet (⭐27)](https://github.com/fish-tennis/gnet) — high performance net library for game server ☆`27`

### VPN & Tunneling

*   [cloudflare/cloudflared (⭐14k)](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`13,811`
*   [xjasonlyu/tun2socks (⭐5k)](https://github.com/xjasonlyu/tun2socks) — TUN to SOCKS proxy ☆`5,038`
*   [songgao/water (⭐2.2k)](https://github.com/songgao/water) — A simple TUN/TAP library written in native Go. ☆`2,150`
*   [NodePassProject/nodepass (⭐2.1k)](https://github.com/NodePassProject/nodepass) — Secure TCP/UDP tunneling with TLS ☆`2,097`

## Queues & Pub/Sub

### Brokers

*   [nats-io/nats-server (⭐20k)](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`19,571`
*   [emitter-io/emitter (⭐4k)](https://github.com/emitter-io/emitter) — High-performance pub/sub broker ☆`4,000`
*   [mochi-mqtt/server (⭐1.8k)](https://github.com/mochi-mqtt/server) — Embeddable MQTT v5 broker ☆`1,831`

### Clients & Libraries

*   [hibiken/asynq (⭐13k)](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`13,133`
*   [IBM/sarama (⭐12k)](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,460`
*   [centrifugal/centrifugo (⭐10k)](https://github.com/centrifugal/centrifugo) — Scalable real-time messaging server ☆`10,162`
*   [ThreeDotsLabs/watermill (⭐9.6k)](https://github.com/ThreeDotsLabs/watermill) — Building event-driven applications the easy way in Go. ☆`9,651`
*   [appleboy/gorush (⭐8.7k)](https://github.com/appleboy/gorush) — A push notification server written in Go (Golang). ☆`8,713`
*   [RichardKnop/machinery (⭐8k)](https://github.com/RichardKnop/machinery) — Async task queue with message passing ☆`7,953`
*   [nats-io/nats.go (⭐6.5k)](https://github.com/nats-io/nats.go) — Golang client for NATS, the cloud native messaging system. ☆`6,542`
*   [dunglas/mercure (⭐5.2k)](https://github.com/dunglas/mercure) — Server-Sent Events hub ☆`5,222`
*   [confluentinc/confluent-kafka-go (⭐5.1k)](https://github.com/confluentinc/confluent-kafka-go) — Confluent's Apache Kafka Golang client ☆`5,122`
*   [olahol/melody (⭐4.1k)](https://github.com/olahol/melody) — Minimalist websocket framework for Go ☆`4,069`
*   [sideshow/apns2 (⭐3.2k)](https://github.com/sideshow/apns2) — Apple Push Notification Service ☆`3,167`
*   [lovoo/goka (⭐2.5k)](https://github.com/lovoo/goka) — Kafka stream processing library ☆`2,515`
*   [rabbitmq/amqp091-go (⭐2k)](https://github.com/rabbitmq/amqp091-go) — An AMQP 0-9-1 Go client maintained by the RabbitMQ team ☆`1,996`
*   [asaskevich/EventBus (⭐2k)](https://github.com/asaskevich/EventBus) — \[Go] Lightweight eventbus with async compatibility for Go ☆`1,968`
*   [containrrr/shoutrrr (⭐1.6k)](https://github.com/containrrr/shoutrrr) — Notification library for gophers and their furry friends. ☆`1,551`
*   [pebbe/zmq4 (⭐1.2k)](https://github.com/pebbe/zmq4) — A Go interface to ZeroMQ version 4 ☆`1,248`
*   [timbray/quamina (⭐491)](https://github.com/timbray/quamina) — Fast pattern-matching library ☆`491`
*   [cskr/pubsub (⭐451)](https://github.com/cskr/pubsub) — A simple pubsub package for go. ☆`451`
*   [jandelgado/rabtap (⭐282)](https://github.com/jandelgado/rabtap) — RabbitMQ wire tap and swiss army knife ☆`282`
*   [mehdihadeli/Go-MediatR (⭐278)](https://github.com/mehdihadeli/Go-MediatR) — Mediator pattern for CQRS ☆`278`
*   [goptics/varmq (⭐184)](https://github.com/goptics/varmq) — Zero-dep message queue library ☆`184`
*   [oagudo/outbox (⭐123)](https://github.com/oagudo/outbox) — Transactional outbox pattern ☆`123`
*   [hyperonym/ratus (⭐122)](https://github.com/hyperonym/ratus) — RESTful async task queue server ☆`123`
*   [dailymotion/oplog (⭐111)](https://github.com/dailymotion/oplog) — A generic oplog/replication system for microservices ☆`111`
*   [jirenius/go-res (⭐68)](https://github.com/jirenius/go-res) — RES Service protocol library for Go ☆`68`
*   [Protocol-Lattice/GoEventBus (⭐60)](https://github.com/Protocol-Lattice/GoEventBus) — A lock-free, ultra-fast event bus for Go ☆`60`
*   [SchwarzDigits/hypermatch (⭐33)](https://github.com/SchwarzDigits/hypermatch) — High-performance rule matching ☆`33`

## Science

*   [gonum/gonum (⭐8.3k)](https://github.com/gonum/gonum) — Numeric libraries for Go ☆`8,347`
*   [gonum/plot (⭐2.9k)](https://github.com/gonum/plot) — Plotting and visualization ☆`2,948`
*   [paulmach/orb (⭐1.1k)](https://github.com/paulmach/orb) — 2D geometry types and utilities ☆`1,109`
*   [madelynnblue/go-dsp (⭐911)](https://github.com/madelynnblue/go-dsp) — Digital Signal Processing for Go ☆`911`
*   [bebop/poly (⭐721)](https://github.com/bebop/poly) — Synthetic biology library for Go ☆`722`
*   [hmdsefi/gograph (⭐110)](https://github.com/hmdsefi/gograph) — Generic graph algorithms library ☆`110`
*   [nikolaydubina/jsonl-graph (⭐77)](https://github.com/nikolaydubina/jsonl-graph) — JSONL Graph Tools ☆`77`
*   [claygod/PiHex (⭐20)](https://github.com/claygod/PiHex) — Generate hexadecimal Pi digits ☆`20`

## Scripting

### Embeddable Languages

*   [php/frankenphp (⭐11k)](https://github.com/php/frankenphp) — The modern PHP app server ☆`10,982`
*   [expr-lang/expr (⭐7.8k)](https://github.com/expr-lang/expr) — Expression evaluation for Go ☆`7,797`
*   [yuin/gopher-lua (⭐6.9k)](https://github.com/yuin/gopher-lua) — Lua VM and compiler in Go ☆`6,873`
*   [dop251/goja (⭐6.8k)](https://github.com/dop251/goja) — ECMAScript engine in pure Go ☆`6,823`
*   [d5/tengo (⭐3.8k)](https://github.com/d5/tengo) — Fast script language for Go ☆`3,796`
*   [Shopify/go-lua (⭐3.4k)](https://github.com/Shopify/go-lua) — Lua VM in Go ☆`3,429`
*   [google/cel-go (⭐2.9k)](https://github.com/google/cel-go) — Common Expression Language for Go ☆`2,931`
*   [google/starlark-go (⭐2.7k)](https://github.com/google/starlark-go) — Starlark config language in Go ☆`2,664`
*   [metacall/core (⭐1.8k)](https://github.com/metacall/core) — Polyglot programming runtime ☆`1,793`
*   [wa-lang/wa (⭐1.8k)](https://github.com/wa-lang/wa) — The Wa Programming Language ☆`1,758`
*   [mattn/anko (⭐1.6k)](https://github.com/mattn/anko) — Scriptable interpreter in Go ☆`1,562`
*   [PaesslerAG/gval (⭐813)](https://github.com/PaesslerAG/gval) — Expression evaluation in Go ☆`813`
*   [ichiban/prolog (⭐717)](https://github.com/ichiban/prolog) — Prolog scripting engine for Go ☆`717`
*   [aarzilli/golua (⭐693)](https://github.com/aarzilli/golua) — Lua C API bindings for Go ☆`693`
*   [1set/starlet (⭐42)](https://github.com/1set/starlet) — Starlark wrapper with batteries ☆`42`

### Code Generators

*   [oapi-codegen/oapi-codegen (⭐8.2k)](https://github.com/oapi-codegen/oapi-codegen) — Generate Go code from OpenAPI 3 specs ☆`8,226`
*   [dave/jennifer (⭐3.6k)](https://github.com/dave/jennifer) — Code generator for Go ☆`3,610`
*   [hexdigest/gowrap (⭐1.3k)](https://github.com/hexdigest/gowrap) — Generate interface decorators ☆`1,320`
*   [awalterschulze/goderive (⭐1.3k)](https://github.com/awalterschulze/goderive) — Generate mundane Go functions ☆`1,265`
*   [abice/go-enum (⭐939)](https://github.com/abice/go-enum) — Enum generator for Go ☆`939`
*   [jmattheis/goverter (⭐840)](https://github.com/jmattheis/goverter) — Generate type-safe converters ☆`840`
*   [rjeczalik/interfaces (⭐432)](https://github.com/rjeczalik/interfaces) — Code generation tools for Go ☆`432`
*   [switchupcb/copygen (⭐404)](https://github.com/switchupcb/copygen) — Copy values between types ☆`404`
*   [reedom/convergen (⭐50)](https://github.com/reedom/convergen) — Type-to-type copy code generator ☆`50`

## Security

### Certificates

*   [go-acme/lego (⭐9.5k)](https://github.com/go-acme/lego) — Let's Encrypt/ACME client and library written in Go ☆`9,468`
*   [caddyserver/certmagic (⭐5.5k)](https://github.com/caddyserver/certmagic) — Automatic HTTPS certificate management ☆`5,527`
*   [tg123/go-htpasswd (⭐47)](https://github.com/tg123/go-htpasswd) — Apache htpasswd Parser for Go. ☆`47`
*   [adrianosela/sslmgr (⭐31)](https://github.com/adrianosela/sslmgr) — SSL certificate abstraction ☆`31`

### Cryptography

*   [FiloSottile/age (⭐22k)](https://github.com/FiloSottile/age) — Simple encryption tool ☆`21,953`
*   [authzed/spicedb (⭐6.6k)](https://github.com/authzed/spicedb) — Zanzibar-inspired permissions DB ☆`6,588`
*   [awnumar/memguard (⭐2.7k)](https://github.com/awnumar/memguard) — Software sandbox for storage of sensitive information in memory. ☆`2,724`
*   [cossacklabs/themis (⭐2k)](https://github.com/cossacklabs/themis) — Cryptographic framework for data protection ☆`1,958`
*   [dromara/dongle (⭐1.1k)](https://github.com/dromara/dongle) — A simple, semantic and developer-friendly crypto package for golang ☆`1,100`
*   [anatol/booster (⭐624)](https://github.com/anatol/booster) — Fast and secure initramfs generator ☆`624`
*   [kevinburke/nacl (⭐552)](https://github.com/kevinburke/nacl) — Pure Go implementation of the NaCL set of API's ☆`552`
*   [ssh-vault/ssh-vault (⭐502)](https://github.com/ssh-vault/ssh-vault) — encrypt/decrypt using ssh keys ☆`502`
*   [number571/go-peer (⭐320)](https://github.com/number571/go-peer) — Secure decentralized networking ☆`320`
*   [lingrino/vaku (⭐159)](https://github.com/lingrino/vaku) — Extended Vault API and CLI ☆`159`
*   [anatol/luks.go (⭐96)](https://github.com/anatol/luks.go) — Pure Golang library to manage LUKS partitions ☆`96`
*   [zitadel/passwap (⭐74)](https://github.com/zitadel/passwap) — Unified password hashing ☆`74`
*   [rsjethani/secret (⭐33)](https://github.com/rsjethani/secret) — Prevent your secrets from leaking into logs, std\* etc. ☆`33`
*   [andskur/argon2-hashing (⭐25)](https://github.com/andskur/argon2-hashing) — Argon2 password hashing ☆`25`

### WAF & Protection

*   [Ullaakut/cameradar (⭐5k)](https://github.com/Ullaakut/cameradar) — Cameradar hacks its way into RTSP videosurveillance cameras ☆`4,985`
*   [corazawaf/coraza (⭐3.4k)](https://github.com/corazawaf/coraza) — ModSecurity-compatible WAF in Go ☆`3,407`
*   [mojocn/base64Captcha (⭐2.4k)](https://github.com/mojocn/base64Captcha) — captcha of base64 image string ☆`2,355`
*   [unrolled/secure (⭐2.3k)](https://github.com/unrolled/secure) — HTTP middleware for Go that facilitates some quick security wins. ☆`2,338`
*   [beelzebub-labs/beelzebub (⭐1.9k)](https://github.com/beelzebub-labs/beelzebub) — AI-powered honeypot framework ☆`1,947`
*   [cossacklabs/acra (⭐1.5k)](https://github.com/cossacklabs/acra) — Database security proxy ☆`1,467`
*   [securitybunker/databunker (⭐1.4k)](https://github.com/securitybunker/databunker) — Secure vault for PII/PHI/KYC records ☆`1,407`
*   [hillu/go-yara (⭐387)](https://github.com/hillu/go-yara) — Go bindings for YARA ☆`387`
*   [teler-sh/teler-waf (⭐400)](https://github.com/teler-sh/teler-waf) — HTTP middleware for WAF ☆`400`
*   [steambap/captcha (⭐162)](https://github.com/steambap/captcha) — Easy captcha library ☆`162`

### Zero Trust

*   [sigstore/cosign (⭐5.8k)](https://github.com/sigstore/cosign) — Code signing and transparency for containers and binaries ☆`5,807`
*   [openziti/ziti (⭐4.1k)](https://github.com/openziti/ziti) — Zero trust networking platform ☆`4,081`
*   [spiffe/spire (⭐2.3k)](https://github.com/spiffe/spire) — The SPIFFE Runtime Environment ☆`2,308`
*   [philips-labs/spiffe-vault (⭐99)](https://github.com/philips-labs/spiffe-vault) — Integrates Spiffe and Vault to have secretless authentication ☆`99`

## Testing & Quality

### Benchmarks

*   [smallnest/go-web-framework-benchmark (⭐2.1k)](https://github.com/smallnest/go-web-framework-benchmark) — Web framework benchmarks ☆`2,138`
*   [alecthomas/go\_serialization\_benchmarks (⭐1.6k)](https://github.com/alecthomas/go_serialization_benchmarks) — Serialization benchmarks for Go ☆`1,626`
*   [SimonWaldherr/golang-benchmarks (⭐143)](https://github.com/SimonWaldherr/golang-benchmarks) — Go(lang) benchmarks - (measure the speed of golang) ☆`143`
*   [nikolaydubina/go-ml-benchmarks (⭐32)](https://github.com/nikolaydubina/go-ml-benchmarks) — Benchmarks of machine learning inference for Go ☆`32`

### Code Analysis

*   [golangci/golangci-lint (⭐19k)](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`18,806`
*   [boyter/scc (⭐8.3k)](https://github.com/boyter/scc) — Fast code counter and stats ☆`8,279`
*   [mgechev/revive (⭐5.5k)](https://github.com/mgechev/revive) — Fast, extensible Go linter ☆`5,480`
*   [kisielk/errcheck (⭐2.5k)](https://github.com/kisielk/errcheck) — errcheck checks that you checked errors. ☆`2,480`
*   [go-critic/go-critic (⭐2k)](https://github.com/go-critic/go-critic) — The most opinionated Go source code linter for code audit. ☆`2,039`
*   [daveshanley/vacuum (⭐1k)](https://github.com/daveshanley/vacuum) — Fast OpenAPI linter ☆`1,036`
*   [presmihaylov/todocheck (⭐435)](https://github.com/presmihaylov/todocheck) — Analyser for TODO comments ☆`435`
*   [mibk/dupl (⭐366)](https://github.com/mibk/dupl) — Code clone detection tool ☆`366`
*   [mdempsky/unconvert (⭐388)](https://github.com/mdempsky/unconvert) — Remove unnecessary type conversions ☆`388`
*   [tomarrell/wrapcheck (⭐374)](https://github.com/tomarrell/wrapcheck) — Check errors are wrapped ☆`374`
*   [shurcooL/gostatus (⭐245)](https://github.com/shurcooL/gostatus) — Show status of Go repositories ☆`245`
*   [Antonboom/testifylint (⭐165)](https://github.com/Antonboom/testifylint) — Linter for testify usage ☆`165`
*   [Crocmagnon/fatcontext (⭐74)](https://github.com/Crocmagnon/fatcontext) — Detect nested contexts in loops ☆`74`
*   [antham/ghokin (⭐52)](https://github.com/antham/ghokin) — Parallelized Gherkin formatter ☆`52`
*   [asticode/go-astitodo (⭐66)](https://github.com/asticode/go-astitodo) — Parse TODOs in your GO code ☆`66`
*   [sashamelentyev/usestdlibvars (⭐47)](https://github.com/sashamelentyev/usestdlibvars) — Linter for stdlib variables usage ☆`47`
*   [borovikovd/gomsort (⭐26)](https://github.com/borovikovd/gomsort) — Go msort - linter that sorts methods ☆`26`

### Mock

*   [vektra/mockery (⭐7.1k)](https://github.com/vektra/mockery) — Mock code autogenerator for Go ☆`7,059`
*   [DATA-DOG/go-sqlmock (⭐6.5k)](https://github.com/DATA-DOG/go-sqlmock) — SQL mock driver for testing ☆`6,543`
*   [brianvoe/gofakeit (⭐5.3k)](https://github.com/brianvoe/gofakeit) — Random fake data generator written in go ☆`5,331`
*   [uber-go/mock (⭐3.3k)](https://github.com/uber-go/mock) — GoMock is a mocking framework for the Go programming language. ☆`3,304`
*   [SpectoLabs/hoverfly (⭐2.5k)](https://github.com/SpectoLabs/hoverfly) — API simulation and virtualization ☆`2,480`
*   [matryer/moq (⭐2.2k)](https://github.com/matryer/moq) — Interface mocking via go generate ☆`2,198`
*   [jarcoal/httpmock (⭐2.1k)](https://github.com/jarcoal/httpmock) — HTTP mocking for Go ☆`2,074`
*   [maxbrunsfeld/counterfeiter (⭐1.1k)](https://github.com/maxbrunsfeld/counterfeiter) — Generate type-safe test doubles ☆`1,127`
*   [gojuno/minimock (⭐748)](https://github.com/gojuno/minimock) — Powerful mock generator ☆`749`
*   [DATA-DOG/go-txdb (⭐748)](https://github.com/DATA-DOG/go-txdb) — Transaction-isolated SQL driver ☆`748`
*   [pashagolub/pgxmock (⭐577)](https://github.com/pashagolub/pgxmock) — pgx mock driver for testing ☆`577`
*   [xhd2015/xgo (⭐432)](https://github.com/xhd2015/xgo) — All-in-one Go testing library ☆`432`
*   [seborama/govcr (⭐196)](https://github.com/seborama/govcr) — Record and replay HTTP interactions ☆`196`
*   [mocktools/go-smtp-mock (⭐164)](https://github.com/mocktools/go-smtp-mock) — SMTP mock server for testing ☆`164`
*   [elgohr/go-localstack (⭐87)](https://github.com/elgohr/go-localstack) — Go wrapper for LocalStack ☆`87`

### Performance

*   [jaegertracing/jaeger (⭐23k)](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`22,677`
*   [pixie-io/pixie (⭐6.4k)](https://github.com/pixie-io/pixie) — Kubernetes-native observability ☆`6,416`
*   [arl/statsviz (⭐3.6k)](https://github.com/arl/statsviz) — Visualize Go runtime metrics ☆`3,635`
*   [nikolaydubina/go-instrument (⭐293)](https://github.com/nikolaydubina/go-instrument) — Add trace spans to Go functions ☆`293`
*   [joetifa2003/mm-go (⭐194)](https://github.com/joetifa2003/mm-go) — Manual memory management for Go ☆`194`

### Browser Automation

*   [chromedp/chromedp (⭐13k)](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`12,941`
*   [go-rod/rod (⭐6.8k)](https://github.com/go-rod/rod) — Chrome DevTools driver for scraping ☆`6,856`
*   [sensepost/gowitness (⭐4.2k)](https://github.com/sensepost/gowitness) — Web screenshot utility with Chrome ☆`4,229`
*   [playwright-community/playwright-go (⭐3.3k)](https://github.com/playwright-community/playwright-go) — Browser automation for Chromium, Firefox, WebKit ☆`3,301`
*   [mafredri/cdp (⭐788)](https://github.com/mafredri/cdp) — Chrome DevTools Protocol bindings ☆`788`

### Testing Frameworks

*   [stretchr/testify (⭐26k)](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`25,926`
*   [keploy/keploy (⭐17k)](https://github.com/keploy/keploy) — API testing with auto mocks ☆`17,091`
*   [Shopify/toxiproxy (⭐12k)](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`11,937`
*   [testcontainers/testcontainers-go (⭐4.8k)](https://github.com/testcontainers/testcontainers-go) — Docker containers for integration tests ☆`4,782`
*   [google/go-cmp (⭐4.6k)](https://github.com/google/go-cmp) — Package for comparing Go values in tests ☆`4,612`
*   [gavv/httpexpect (⭐2.7k)](https://github.com/gavv/httpexpect) — End-to-end HTTP and REST API testing for Go. ☆`2,715`
*   [cucumber/godog (⭐2.6k)](https://github.com/cucumber/godog) — Cucumber for golang ☆`2,612`
*   [orlangure/gnomock (⭐1.5k)](https://github.com/orlangure/gnomock) — Test with ephemeral Docker containers ☆`1,484`
*   [dnaeon/go-vcr (⭐1.4k)](https://github.com/dnaeon/go-vcr) — Record and replay HTTP for tests ☆`1,369`
*   [go-testfixtures/testfixtures (⭐1.2k)](https://github.com/go-testfixtures/testfixtures) — Rails-like test fixtures for Go ☆`1,226`
*   [fergusstrange/embedded-postgres (⭐1.2k)](https://github.com/fergusstrange/embedded-postgres) — Embedded PostgreSQL for testing ☆`1,161`
*   [chapar-rest/chapar (⭐697)](https://github.com/chapar-rest/chapar) — API testing for HTTP and gRPC ☆`697`
*   [gotestyourself/gotest.tools (⭐578)](https://github.com/gotestyourself/gotest.tools) — Testing utilities for Go ☆`578`
*   [maxatome/go-testdeep (⭐462)](https://github.com/maxatome/go-testdeep) — Flexible deep comparison in tests ☆`462`
*   [appleboy/gofight (⭐444)](https://github.com/appleboy/gofight) — Testing API Handler written in Golang. ☆`444`
*   [viant/endly (⭐267)](https://github.com/viant/endly) — End to end functional test and automation framework ☆`267`
*   [ysmood/got (⭐268)](https://github.com/ysmood/got) — An enjoyable golang test framework. ☆`268`
*   [kinbiko/jsonassert (⭐141)](https://github.com/kinbiko/jsonassert) — JSON assertion library for tests ☆`141`
*   [adamluzsi/testcase (⭐127)](https://github.com/adamluzsi/testcase) — Opinionated testing framework ☆`127`
*   [earthboundkid/be (⭐132)](https://github.com/earthboundkid/be) — The Go test helper for minimalists ☆`132`
*   [corbym/gocrest (⭐106)](https://github.com/corbym/gocrest) — GoCrest - Hamcrest-like matchers for Go ☆`106`
*   [hedhyw/gherkingen (⭐96)](https://github.com/hedhyw/gherkingen) — Behaviour Driven Development tests generator for Golang ☆`96`
*   [madflojo/testcerts (⭐84)](https://github.com/madflojo/testcerts) — Generate test certificates on the fly ☆`84`
*   [go-restit/restit (⭐55)](https://github.com/go-restit/restit) — A Go library help testing your RESTful API application ☆`55`
*   [viant/dsunit (⭐45)](https://github.com/viant/dsunit) — Datastore Testibility ☆`45`
*   [rekby/fixenv (⭐33)](https://github.com/rekby/fixenv) — Pytest-inspired fixture caching for Go tests ☆`33`
*   [abecodes/dft (⭐19)](https://github.com/abecodes/dft) — Docker wrapper for testing ☆`19`

### Testing Utilities

*   [dvyukov/go-fuzz (⭐4.8k)](https://github.com/dvyukov/go-fuzz) — Randomized testing for Go ☆`4,850`
*   [pingcap/failpoint (⭐878)](https://github.com/pingcap/failpoint) — Failpoint implementation for Go ☆`879`

### Validation

*   [go-playground/validator (⭐20k)](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`19,865`
*   [Oudwins/zog (⭐1.2k)](https://github.com/Oudwins/zog) — Zod-inspired schema validation ☆`1,168`
*   [gookit/validate (⭐1.1k)](https://github.com/gookit/validate) — Struct and data validation ☆`1,126`
*   [twharmon/govalid (⭐114)](https://github.com/twharmon/govalid) — Struct validation using tags ☆`114`
*   [faceair/jio (⭐126)](https://github.com/faceair/jio) — JSON schema validator like Joi ☆`126`
*   [osamingo/checkdigit (⭐114)](https://github.com/osamingo/checkdigit) — Check digit algorithms ☆`114`
*   [tiendc/go-validator (⭐32)](https://github.com/tiendc/go-validator) — Intuitive validation library ☆`32`
*   [marrow16/valix (⭐31)](https://github.com/marrow16/valix) — Request validation package ☆`31`

## Text & NLP

### Formatters

*   [dustin/go-humanize (⭐4.8k)](https://github.com/dustin/go-humanize) — Human-friendly unit formatting ☆`4,787`
*   [neilotoole/sq (⭐2.5k)](https://github.com/neilotoole/sq) — SQL data wrangler ☆`2,463`
*   [bojanz/address (⭐82)](https://github.com/bojanz/address) — Address handling for Go ☆`82`

### Markup Languages

*   [BurntSushi/toml (⭐4.9k)](https://github.com/BurntSushi/toml) — TOML parser with reflection ☆`4,931`
*   [yuin/goldmark (⭐4.7k)](https://github.com/yuin/goldmark) — Markdown parser for Go ☆`4,712`
*   [JohannesKaufmann/html-to-markdown (⭐3.5k)](https://github.com/JohannesKaufmann/html-to-markdown) — Convert HTML to Markdown ☆`3,552`
*   [pelletier/go-toml (⭐1.9k)](https://github.com/pelletier/go-toml) — TOML library for Go ☆`1,924`
*   [antchfx/htmlquery (⭐781)](https://github.com/antchfx/htmlquery) — XPath for HTML queries ☆`781`
*   [clbanning/mxj (⭐633)](https://github.com/clbanning/mxj) — XML to/from map conversion ☆`633`
*   [mmalcek/bafi (⭐114)](https://github.com/mmalcek/bafi) — Universal format converter ☆`114`

### Miscellaneous

*   [microcosm-cc/bluemonday (⭐3.7k)](https://github.com/microcosm-cc/bluemonday) — Fast HTML sanitizer for Go ☆`3,655`
*   [pemistahl/lingua-go (⭐1.3k)](https://github.com/pemistahl/lingua-go) — Natural language detection ☆`1,336`
*   [gosimple/slug (⭐1.3k)](https://github.com/gosimple/slug) — URL-friendly slugify ☆`1,326`
*   [arunsupe/semantic-grep (⭐1.2k)](https://github.com/arunsupe/semantic-grep) — Grep for similar words ☆`1,218`
*   [mattn/go-runewidth (⭐690)](https://github.com/mattn/go-runewidth) — Rune width for terminals ☆`691`
*   [hedhyw/rex (⭐211)](https://github.com/hedhyw/rex) — Flexible regex constructor ☆`211`
*   [IGLOU-EU/go-wildcard (⭐100)](https://github.com/IGLOU-EU/go-wildcard) — Fast wildcard matching ☆`100`
*   [JoshuaDoes/gofuckyourself (⭐69)](https://github.com/JoshuaDoes/gofuckyourself) — Swear filter for Go ☆`70`
*   [alexsergivan/transliterator (⭐46)](https://github.com/alexsergivan/transliterator) — Text transliterator ☆`46`

### Morphological Analyzers

*   [nlpodyssey/spago (⭐1.8k)](https://github.com/nlpodyssey/spago) — ML and NLP library for Go ☆`1,849`
*   [ikawaha/kagome (⭐959)](https://github.com/ikawaha/kagome) — Japanese morphological analyzer ☆`960`
*   [afjoseph/RAKE.Go (⭐122)](https://github.com/afjoseph/RAKE.Go) — Rapid Keyword Extraction in Go ☆`123`
*   [jonreiter/govader (⭐54)](https://github.com/jonreiter/govader) — VADER sentiment analysis ☆`54`

### Parsers/Encoders/Decoders

*   [mvdan/sh (⭐8.6k)](https://github.com/mvdan/sh) — Shell parser and formatter ☆`8,661`
*   [mmcdole/gofeed (⭐2.8k)](https://github.com/mmcdole/gofeed) — Parse RSS, Atom, JSON feeds ☆`2,824`
*   [google/go-querystring (⭐2.1k)](https://github.com/google/go-querystring) — Encode structs to URL query strings ☆`2,135`
*   [olebedev/when (⭐1.5k)](https://github.com/olebedev/when) — Natural language date parser ☆`1,461`
*   [adrianmo/go-nmea (⭐260)](https://github.com/adrianmo/go-nmea) — NMEA sentence parser ☆`260`
*   [yassinebenaid/godump (⭐224)](https://github.com/yassinebenaid/godump) — Dump any Go variable ☆`224`
*   [editorconfig/editorconfig-core-go (⭐151)](https://github.com/editorconfig/editorconfig-core-go) — EditorConfig core in Go ☆`151`
*   [bzick/tokenizer (⭐139)](https://github.com/bzick/tokenizer) — Tokenizer/lexer for Go ☆`139`
*   [emersion/go-vcard (⭐125)](https://github.com/emersion/go-vcard) — vCard parser and formatter ☆`125`
*   [polera/gonameparts (⭐43)](https://github.com/polera/gonameparts) — Takes a full name and splits it into individual name parts ☆`43`

### Scrapers

*   [gocolly/colly (⭐25k)](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,228`
*   [PuerkitoBio/goquery (⭐15k)](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,926`
*   [mvdan/xurls (⭐1.3k)](https://github.com/mvdan/xurls) — Extract URLs from text ☆`1,255`
*   [s0rg/crawley (⭐335)](https://github.com/s0rg/crawley) — The unix-way web crawler ☆`337`
*   [zoomio/tagify (⭐39)](https://github.com/zoomio/tagify) — Extract tags from HTML/Markdown/text ☆`39`

### Text Analysis

*   [blevesearch/bleve (⭐11k)](https://github.com/blevesearch/bleve) — Text/numeric/geo/vector indexing library ☆`11,009`
*   [derekparker/trie (⭐789)](https://github.com/derekparker/trie) — Trie for extremely fast prefix search ☆`789`
*   [agnivade/levenshtein (⭐463)](https://github.com/agnivade/levenshtein) — Go implementation to calculate Levenshtein Distance. ☆`463`
*   [plar/go-adaptive-radix-tree (⭐414)](https://github.com/plar/go-adaptive-radix-tree) — Adaptive Radix Trees implemented in Go ☆`413`

### Tokenizers

*   [go-ego/gse (⭐2.8k)](https://github.com/go-ego/gse) — Multilingual text segmentation ☆`2,806`
*   [pebbe/textcat (⭐73)](https://github.com/pebbe/textcat) — N-gram text categorization ☆`73`

### Translation

*   [nicksnyder/go-i18n (⭐3.5k)](https://github.com/nicksnyder/go-i18n) — Translate Go programs ☆`3,498`
*   [leonelquinteros/gotext (⭐492)](https://github.com/leonelquinteros/gotext) — GNU gettext for Go ☆`492`
*   [vorlif/spreak (⭐93)](https://github.com/vorlif/spreak) — Gettext-based translation library ☆`93`
*   [invopop/ctxi18n (⭐91)](https://github.com/invopop/ctxi18n) — Context-based i18n for Go ☆`91`
*   [mehanizm/iuliia-go (⭐56)](https://github.com/mehanizm/iuliia-go) — Cyrillic to Latin transliteration ☆`56`
*   [youthlin/t (⭐21)](https://github.com/youthlin/t) — Translation util using gettext ☆`21`

## Third-party APIs

### Cloud Provider APIs

*   [googleapis/google-cloud-go (⭐4.4k)](https://github.com/googleapis/google-cloud-go) — Google Cloud Client Libraries for Go. ☆`4,439`
*   [googleapis/google-api-go-client (⭐4.4k)](https://github.com/googleapis/google-api-go-client) — Auto-generated Google APIs for Go. ☆`4,419`
*   [aws/aws-sdk-go-v2 (⭐3.5k)](https://github.com/aws/aws-sdk-go-v2) — AWS SDK for the Go programming language. ☆`3,521`
*   [minio/minio-go (⭐2.9k)](https://github.com/minio/minio-go) — High-performance object storage ☆`2,927`
*   [rhnvrm/simples3 (⭐197)](https://github.com/rhnvrm/simples3) — Simple AWS S3 library using REST ☆`197`
*   [circa10a/go-aws-news (⭐18)](https://github.com/circa10a/go-aws-news) — Go app + library to fetch what's new from AWS ☆`18`
*   [chainifynet/aws-encryption-sdk-go (⭐22)](https://github.com/chainifynet/aws-encryption-sdk-go) — AWS Encryption SDK for Go ☆`22`

### Other APIs

*   [codingsince1985/geo-golang (⭐542)](https://github.com/codingsince1985/geo-golang) — Go library to access geocoding and reverse geocoding APIs ☆`542`
*   [cyruzin/golang-tmdb (⭐160)](https://github.com/cyruzin/golang-tmdb) — Wrapper for TMDb API ☆`160`
*   [gregdel/pushover (⭐156)](https://github.com/gregdel/pushover) — Go wrapper for the Pushover API ☆`156`
*   [mvrilo/go-redoc (⭐94)](https://github.com/mvrilo/go-redoc) — Embedded OpenAPI documentation ☆`94`
*   [rapito/go-spotify (⭐52)](https://github.com/rapito/go-spotify) — Go library for the Spotify Web API ☆`52`
*   [rinchsan/device-check-go (⭐25)](https://github.com/rinchsan/device-check-go) — iOS DeviceCheck SDK for Go ☆`25`
*   [zc2638/swag (⭐50)](https://github.com/zc2638/swag) — Generate Swagger from code ☆`50`
*   [staskobzar/goami2 (⭐21)](https://github.com/staskobzar/goami2) — Simple Asterisk Manager Interface (AMI) library fo golang ☆`21`
*   [sostronk/go-steam (⭐33)](https://github.com/sostronk/go-steam) — Go library for querying Source servers ☆`33`
*   [Icelain/jokeapi (⭐27)](https://github.com/Icelain/jokeapi) — Official golang wrapper for Sv443's jokeapi. ☆`27`

### Productivity APIs

*   [mk-5/fjira (⭐262)](https://github.com/mk-5/fjira) — The golang fuzzy-find cli jira interface ☆`265`
*   [adlio/trello (⭐227)](https://github.com/adlio/trello) — Trello API wrapper for Go ☆`227`
*   [ctreminiom/go-atlassian (⭐199)](https://github.com/ctreminiom/go-atlassian) — Atlassian Cloud API client ☆`199`
*   [koltyakov/gosip (⭐168)](https://github.com/koltyakov/gosip) — SharePoint SDK for Go ☆`168`
*   [FreeLeh/GoFreeDB (⭐90)](https://github.com/FreeLeh/GoFreeDB) — Database on top of Google Sheets ☆`90`
*   [mehanizm/airtable (⭐86)](https://github.com/mehanizm/airtable) — Simple golang airtable API wrapper ☆`86`
*   [k-capehart/go-salesforce (⭐55)](https://github.com/k-capehart/go-salesforce) — Salesforce REST API client ☆`55`

## Utilities

### Build & Release

*   [goreleaser/goreleaser (⭐16k)](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,702`
*   [create-go-app/cli (⭐2.8k)](https://github.com/create-go-app/cli) — Create production-ready Go projects ☆`2,755`
*   [miniscruff/changie (⭐869)](https://github.com/miniscruff/changie) — Automated changelog tool ☆`870`
*   [karl-cardenas-coding/go-lambda-cleanup (⭐96)](https://github.com/karl-cardenas-coding/go-lambda-cleanup) — Remove old AWS Lambda versions ☆`96`

### CLI Tools

*   [junegunn/fzf (⭐79k)](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`79,420`
*   [wagoodman/dive (⭐54k)](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`53,759`
*   [xo/usql (⭐9.9k)](https://github.com/xo/usql) — Universal SQL CLI ☆`9,907`
*   [minio/mc (⭐3.4k)](https://github.com/minio/mc) — Unix utilities for object stores ☆`3,447`
*   [joshmedeski/sesh (⭐2.3k)](https://github.com/joshmedeski/sesh) — Terminal session manager ☆`2,274`
*   [itchyny/bed (⭐1.3k)](https://github.com/itchyny/bed) — Binary editor in Go ☆`1,346`
*   [owenthereal/upterm (⭐1.2k)](https://github.com/owenthereal/upterm) — Instant terminal sharing ☆`1,200`
*   [alajmo/mani (⭐682)](https://github.com/alajmo/mani) — CLI for managing repositories ☆`682`
*   [Unrud/remote-touchpad (⭐658)](https://github.com/Unrud/remote-touchpad) — Control mouse/keyboard remotely ☆`660`
*   [chenquan/diskusage (⭐304)](https://github.com/chenquan/diskusage) — Fast disk usage analyzer ☆`304`
*   [reugn/wifiqr (⭐280)](https://github.com/reugn/wifiqr) — Generate Wi-Fi QR codes ☆`280`
*   [hedhyw/json-log-viewer (⭐218)](https://github.com/hedhyw/json-log-viewer) — Interactive JSON log viewer ☆`218`
*   [hrtsegv/gitcs (⭐131)](https://github.com/hrtsegv/gitcs) — Git contributions graph generator ☆`131`
*   [antham/yogo (⭐45)](https://github.com/antham/yogo) — Check yopmail from CLI ☆`45`

### Data Conversion

*   [samber/lo (⭐21k)](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`21,190`
*   [duke-git/lancet (⭐5.3k)](https://github.com/duke-git/lancet) — Comprehensive util library ☆`5,279`
*   [darccio/mergo (⭐3.1k)](https://github.com/darccio/mergo) — Merge Go structs and maps ☆`3,095`
*   [goforj/godump (⭐1.7k)](https://github.com/goforj/godump) — Pretty-printer for Go structs ☆`1,735`
*   [gookit/filter (⭐150)](https://github.com/gookit/filter) — Data filtering and conversion ☆`150`
*   [xorcare/pointer (⭐47)](https://github.com/xorcare/pointer) — Create optional field pointers ☆`47`
*   [tiendc/gofn (⭐51)](https://github.com/tiendc/gofn) — High-performance generic functions ☆`51`
*   [shockerli/cvt (⭐54)](https://github.com/shockerli/cvt) — Safe type conversion ☆`54`

### Database Extensions

*   [jmoiron/sqlx (⭐18k)](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,573`
*   [georgysavva/scany (⭐1.5k)](https://github.com/georgysavva/scany) — Scan database rows to structs ☆`1,509`
*   [blockloop/scan (⭐611)](https://github.com/blockloop/scan) — Scan SQL rows to structs ☆`611`

### Date and Time

*   [dromara/carbon (⭐5.2k)](https://github.com/dromara/carbon) — Developer-friendly time package ☆`5,226`
*   [yaa110/go-persian-calendar (⭐237)](https://github.com/yaa110/go-persian-calendar) — Persian calendar for Go ☆`237`
*   [bykof/gostradamus (⭐208)](https://github.com/bykof/gostradamus) — Better DateTimes for Go ☆`208`
*   [nathan-osman/go-sunrise (⭐174)](https://github.com/nathan-osman/go-sunrise) — Calculate sunrise and sunset times ☆`174`
*   [rickb777/date (⭐142)](https://github.com/rickb777/date) — Date handling package ☆`142`
*   [relvacode/iso8601 (⭐158)](https://github.com/relvacode/iso8601) — Fast ISO8601 date parser ☆`158`

### Dependency Injection

*   [uber-go/fx (⭐7.4k)](https://github.com/uber-go/fx) — DI-based application framework ☆`7,443`
*   [uber-go/dig (⭐4.5k)](https://github.com/uber-go/dig) — Reflection-based DI toolkit ☆`4,457`
*   [goioc/di (⭐379)](https://github.com/goioc/di) — Simple DI for Go ☆`379`
*   [go-kod/kod (⭐197)](https://github.com/go-kod/kod) — DI with aspect-oriented support ☆`197`
*   [i-love-flamingo/dingo (⭐188)](https://github.com/i-love-flamingo/dingo) — DI framework for Go ☆`188`
*   [junioryono/godi (⭐73)](https://github.com/junioryono/godi) — DI with service lifetimes ☆`73`
*   [NVIDIA/gontainer (⭐66)](https://github.com/NVIDIA/gontainer) — Simple DI container ☆`66`
*   [matzefriedrich/parsley (⭐31)](https://github.com/matzefriedrich/parsley) — Reflection-based DI package ☆`31`
*   [muir/nject (⭐30)](https://github.com/muir/nject) — Type-safe DI for Go ☆`30`
*   [firasdarwish/ore (⭐26)](https://github.com/firasdarwish/ore) — Advanced DI solution ☆`26`
*   [logrange/linker (⭐35)](https://github.com/logrange/linker) — DI and IoC package ☆`35`
*   [componego/componego (⭐29)](https://github.com/componego/componego) — Component-oriented framework ☆`29`
*   [gontainer/gontainer (⭐16)](https://github.com/gontainer/gontainer) — YAML-based DI container ☆`16`

### Error Handling

*   [hashicorp/go-multierror (⭐2.6k)](https://github.com/hashicorp/go-multierror) — Represent multiple errors as one ☆`2,567`
*   [cockroachdb/errors (⭐2.4k)](https://github.com/cockroachdb/errors) — Error library with portability ☆`2,387`
*   [rotisserie/eris (⭐1.8k)](https://github.com/rotisserie/eris) — Errors with readable stack traces ☆`1,785`
*   [joomcode/errorx (⭐1.3k)](https://github.com/joomcode/errorx) — Comprehensive error handling ☆`1,271`
*   [ztrue/tracerr (⭐1.1k)](https://github.com/ztrue/tracerr) — Errors with stack trace ☆`1,106`
*   [samber/oops (⭐911)](https://github.com/samber/oops) — Structured error handling ☆`916`
*   [Southclaws/fault (⭐309)](https://github.com/Southclaws/fault) — Composable error wrapping ☆`309`

### File Handling

*   [schollz/croc (⭐35k)](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`34,628`
*   [qax-os/excelize (⭐20k)](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,472`
*   [pdfcpu/pdfcpu (⭐8.6k)](https://github.com/pdfcpu/pdfcpu) — PDF processor in Go ☆`8,559`
*   [spf13/afero (⭐6.6k)](https://github.com/spf13/afero) — Filesystem abstraction for Go ☆`6,626`
*   [dundee/gdu (⭐5.5k)](https://github.com/dundee/gdu) — Fast disk usage analyzer ☆`5,552`
*   [unidoc/unioffice (⭐4.8k)](https://github.com/unidoc/unioffice) — Office document library ☆`4,832`
*   [root-gg/plik (⭐1.7k)](https://github.com/root-gg/plik) — Temporary file upload system ☆`1,743`
*   [SebastiaanKlippert/go-wkhtmltopdf (⭐1.2k)](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) — HTML to PDF wrapper ☆`1,176`
*   [otiai10/copy (⭐771)](https://github.com/otiai10/copy) — Copy directories recursively ☆`771`
*   [ulikunitz/xz (⭐553)](https://github.com/ulikunitz/xz) — Pure golang package for reading and writing xz-compressed files ☆`554`
*   [no-src/gofs (⭐526)](https://github.com/no-src/gofs) — Cross-platform file sync ☆`526`
*   [mholt/archives (⭐394)](https://github.com/mholt/archives) — Create and extract archives ☆`395`
*   [viant/afs (⭐383)](https://github.com/viant/afs) — Abstract file storage ☆`383`
*   [C2FO/vfs (⭐358)](https://github.com/C2FO/vfs) — Virtual file system for Go ☆`358`
*   [gen2brain/go-unarr (⭐310)](https://github.com/gen2brain/go-unarr) — Decompression library bindings ☆`310`
*   [barasher/go-exiftool (⭐295)](https://github.com/barasher/go-exiftool) — Exiftool wrapper for metadata ☆`295`
*   [gomutex/godocx (⭐251)](https://github.com/gomutex/godocx) — Go library for reading and writing Microsoft Docx ☆`251`
*   [charlievieth/fastwalk (⭐128)](https://github.com/charlievieth/fastwalk) — Fast directory traversal ☆`128`
*   [artonge/go-csv-tag (⭐131)](https://github.com/artonge/go-csv-tag) — CSV reading with tags ☆`131`
*   [parsyl/parquet (⭐127)](https://github.com/parsyl/parquet) — Parquet file library ☆`127`
*   [adelowo/gulter (⭐70)](https://github.com/adelowo/gulter) — Multipart form handling ☆`70`
*   [go-the-way/exl (⭐32)](https://github.com/go-the-way/exl) — Excel binding to struct written in Go.(Only supports Go1.18+) ☆`32`

### Forms

*   [justinas/nosurf (⭐1.7k)](https://github.com/justinas/nosurf) — CSRF protection middleware ☆`1,734`
*   [gorilla/csrf (⭐1.2k)](https://github.com/gorilla/csrf) — CSRF prevention middleware ☆`1,190`
*   [go-playground/form (⭐906)](https://github.com/go-playground/form) — URL values to structs ☆`905`
*   [ggicci/httpin (⭐385)](https://github.com/ggicci/httpin) — HTTP request to struct binding ☆`385`
*   [sonh/qs (⭐80)](https://github.com/sonh/qs) — Encode structs to query params ☆`80`
*   [cinar/checker (⭐48)](https://github.com/cinar/checker) — Input validation with struct tags ☆`48`

### Functional

*   [samber/mo (⭐3.3k)](https://github.com/samber/mo) — Monads and FP for Go ☆`3,337`
*   [BooleanCat/go-functional (⭐529)](https://github.com/BooleanCat/go-functional) — Iterator library for Go ☆`529`
*   [seborama/fuego (⭐145)](https://github.com/seborama/fuego) — Functional programming in Go ☆`145`
*   [rjNemo/underscore (⭐116)](https://github.com/rjNemo/underscore) — Functional helpers for Go ☆`117`

### General

*   [wabarc/wayback (⭐2.2k)](https://github.com/wabarc/wayback) — Web archiving tool with IM interface ☆`2,174`
*   [gabriel-vasile/mimetype (⭐2k)](https://github.com/gabriel-vasile/mimetype) — MIME type detection by magic numbers ☆`1,966`
*   [qmuntal/stateless (⭐1.3k)](https://github.com/qmuntal/stateless) — Go library for creating finite state machines ☆`1,285`
*   [jonboulle/clockwork (⭐725)](https://github.com/jonboulle/clockwork) — a fake clock for golang ☆`725`
*   [Boeing/config-file-validator (⭐501)](https://github.com/Boeing/config-file-validator) — Cross-platform CLI tool to validate configuration files (JSON, YAML, TOML, XML, INI, HCL, ENV, Properties, CSV, and more). Catch errors in syntax and schema before deployment. Written in Go. ☆`502`
*   [biter777/countries (⭐509)](https://github.com/biter777/countries) — ISO country codes library ☆`510`
*   [ungerik/go-dry (⭐487)](https://github.com/ungerik/go-dry) — DRY (don't repeat yourself) package for Go ☆`487`
*   [subosito/gotenv (⭐307)](https://github.com/subosito/gotenv) — Load environment variables from `.env` or `io.Reader` in Go. ☆`307`
*   [viant/toolbox (⭐228)](https://github.com/viant/toolbox) — Toolbox - go utility library ☆`228`
*   [ikeikeikeike/go-sitemap-generator (⭐231)](https://github.com/ikeikeikeike/go-sitemap-generator) — Generate XML sitemaps ☆`231`
*   [maja42/goval (⭐174)](https://github.com/maja42/goval) — Expression evaluation in golang ☆`174`
*   [commander-cli/cmd (⭐161)](https://github.com/commander-cli/cmd) — A simple package to execute shell commands on linux, windows and osx ☆`161`
*   [jfcg/sorty (⭐144)](https://github.com/jfcg/sorty) — Fast Concurrent / Parallel Sorting in Go ☆`144`
*   [tiendc/go-deepcopy (⭐127)](https://github.com/tiendc/go-deepcopy) — Fast deep-copy library for Go ☆`127`
*   [syntaqx/cookie (⭐113)](https://github.com/syntaqx/cookie) — Cookies, but with structs, for happiness. ☆`113`
*   [pioz/countries (⭐95)](https://github.com/pioz/countries) — All you need when you are working with countries in Go. ☆`95`
*   [icza/backscanner (⭐69)](https://github.com/icza/backscanner) — Scan file lines backward ☆`69`
*   [wzshiming/gotype (⭐64)](https://github.com/wzshiming/gotype) — Golang source code parsing, usage like reflect package ☆`64`
*   [kazhuravlev/just (⭐36)](https://github.com/kazhuravlev/just) — Collection of useful functions. Complete simple tasks faster! ☆`37`
*   [rkoesters/xdg (⭐48)](https://github.com/rkoesters/xdg) — FreeDesktop.org (xdg) Specs implemented in Go ☆`48`
*   [nikolaydubina/watchhttp (⭐34)](https://github.com/nikolaydubina/watchhttp) — Expose command output via HTTP ☆`34`
*   [mikekonan/go-types (⭐23)](https://github.com/mikekonan/go-types) — OpenAPI3 types for Go ☆`23`
*   [ik5/gostrutils (⭐47)](https://github.com/ik5/gostrutils) — Collections of string utils I have created over the years ☆`47`
*   [floatdrop/debounce (⭐37)](https://github.com/floatdrop/debounce) — A zero-allocation debouncer ☆`37`
*   [lrita/numa (⭐38)](https://github.com/lrita/numa) — NUMA utility library for Go ☆`38`
*   [osamingo/gosh (⭐37)](https://github.com/osamingo/gosh) — Provide Go Statistics Handler, Struct, Measure Method ☆`37`
*   [skovtunenko/graterm (⭐30)](https://github.com/skovtunenko/graterm) — Graceful termination primitives ☆`30`

### Logging

*   [sirupsen/logrus (⭐26k)](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,706`
*   [uber-go/zap (⭐24k)](https://github.com/uber-go/zap) — Fast structured logging ☆`24,410`
*   [rs/zerolog (⭐12k)](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,320`
*   [golang/glog (⭐3.6k)](https://github.com/golang/glog) — Leveled execution logs ☆`3,606`
*   [k0kubun/pp (⭐2k)](https://github.com/k0kubun/pp) — Colored pretty printer for Go ☆`2,038`
*   [lmittmann/tint (⭐1.3k)](https://github.com/lmittmann/tint) — Colorized slog handler ☆`1,272`
*   [Lifailon/lazyjournal (⭐1.2k)](https://github.com/Lifailon/lazyjournal) — TUI for journald, Docker, K8s logs ☆`1,219`
*   [getsentry/sentry-go (⭐1.1k)](https://github.com/getsentry/sentry-go) — Official Sentry SDK for Go ☆`1,080`
*   [phuslu/log (⭐840)](https://github.com/phuslu/log) — Fastest structured logging ☆`840`
*   [samber/slog-multi (⭐616)](https://github.com/samber/slog-multi) — Workflow design for slog handlers ☆`617`
*   [gookit/slog (⭐538)](https://github.com/gookit/slog) — Configurable logging library ☆`539`
*   [henvic/httpretty (⭐412)](https://github.com/henvic/httpretty) — Pretty-print HTTP requests ☆`413`
*   [hashicorp/logutils (⭐372)](https://github.com/hashicorp/logutils) — Logging utilities for Go ☆`372`
*   [simukti/sqldb-logger (⭐382)](https://github.com/simukti/sqldb-logger) — SQL database logger ☆`382`
*   [samber/slog-formatter (⭐216)](https://github.com/samber/slog-formatter) — Slog attribute formatting ☆`216`
*   [DeRuina/timberjack (⭐130)](https://github.com/DeRuina/timberjack) — Log rolling library ☆`130`
*   [rs/xlog (⭐141)](https://github.com/rs/xlog) — Context-aware HTTP logger ☆`141`
*   [yuseferi/zax (⭐34)](https://github.com/yuseferi/zax) — Zap logger with context ☆`34`
*   [clok/kemba (⭐17)](https://github.com/clok/kemba) — Tiny debug logging tool ☆`17`

### Networking Utils

*   [cristianoliveira/ergo (⭐650)](https://github.com/cristianoliveira/ergo) — Manage apps on different ports ☆`650`
*   [htcat/htcat (⭐560)](https://github.com/htcat/htcat) — Parallel HTTP download ☆`558`
*   [ferama/rospo (⭐363)](https://github.com/ferama/rospo) — Persistent SSH tunnels ☆`363`

### Project Layout

*   [golang-standards/project-layout (⭐56k)](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`55,753`
*   [Melkeydev/go-blueprint (⭐8.8k)](https://github.com/Melkeydev/go-blueprint) — Spin up Go projects with popular frameworks ☆`8,783`
*   [ardanlabs/service (⭐3.9k)](https://github.com/ardanlabs/service) — K8s service starter kit ☆`3,951`
*   [Shpota/goxygen (⭐3.6k)](https://github.com/Shpota/goxygen) — Generate full-stack web projects ☆`3,595`
*   [mikestefanello/pagoda (⭐2.9k)](https://github.com/mikestefanello/pagoda) — Full-stack web development starter kit ☆`2,920`
*   [go-nunu/nunu (⭐2.6k)](https://github.com/go-nunu/nunu) — CLI for building Go apps ☆`2,553`
*   [sagikazarmark/modern-go-application (⭐1.9k)](https://github.com/sagikazarmark/modern-go-application) — Modern Go app example ☆`1,938`
*   [naughtygopher/goapp (⭐1.1k)](https://github.com/naughtygopher/goapp) — Opinionated web app structure ☆`1,060`
*   [allaboutapps/go-starter (⭐605)](https://github.com/allaboutapps/go-starter) — Production-ready RESTful API template ☆`605`
*   [golang-templates/seed (⭐555)](https://github.com/golang-templates/seed) — Go app GitHub template ☆`556`
*   [Fs02/go-todo-backend (⭐335)](https://github.com/Fs02/go-todo-backend) — Go Todo Backend example using modular project layout for product microservice. ☆`335`
*   [raeperd/kickstart.go (⭐108)](https://github.com/raeperd/kickstart.go) — Minimal HTTP server template ☆`109`
*   [wangyoucao577/go-project-layout (⭐26)](https://github.com/wangyoucao577/go-project-layout) — Go project structure guide ☆`26`

### Resilience & Retry

*   [avast/retry-go (⭐2.9k)](https://github.com/avast/retry-go) — Simple retry mechanism ☆`2,912`
*   [eapache/go-resiliency (⭐2.3k)](https://github.com/eapache/go-resiliency) — Resiliency patterns for golang ☆`2,344`
*   [failsafe-go/failsafe-go (⭐2.2k)](https://github.com/failsafe-go/failsafe-go) — Fault tolerance patterns ☆`2,194`
*   [rubyist/circuitbreaker (⭐1.2k)](https://github.com/rubyist/circuitbreaker) — Circuit breakers in Go ☆`1,166`
*   [cep21/circuit (⭐813)](https://github.com/cep21/circuit) — Hystrix-like circuit breaker ☆`815`
*   [mennanov/limiters (⭐631)](https://github.com/mennanov/limiters) — Distributed rate limiters ☆`632`
*   [kamilsk/retry (⭐345)](https://github.com/kamilsk/retry) — Advanced retry mechanism ☆`345`
*   [webriots/rate (⭐165)](https://github.com/webriots/rate) — High-performance rate limiter ☆`165`

### Strings

*   [huandu/xstrings (⭐1.4k)](https://github.com/huandu/xstrings) — String functions from other langs ☆`1,418`
*   [abhimanyu003/sttr (⭐1.3k)](https://github.com/abhimanyu003/sttr) — CLI string operations ☆`1,306`
*   [gobeam/stringy (⭐251)](https://github.com/gobeam/stringy) — String case conversions ☆`251`
*   [ozgio/strutil (⭐206)](https://github.com/ozgio/strutil) — String utilities for Go ☆`206`

### System & Process

*   [cilium/ebpf (⭐7.7k)](https://github.com/cilium/ebpf) — eBPF library for Go ☆`7,659`
*   [maruel/panicparse (⭐3.7k)](https://github.com/maruel/panicparse) — Crash your app in style ☆`3,717`
*   [immortal/immortal (⭐834)](https://github.com/immortal/immortal) — Cross-platform supervisor ☆`834`
*   [derekparker/delve (⭐662)](https://github.com/derekparker/delve) — Delve is a debugger for the Go programming language. ☆`662`
*   [gotranspile/cxgo (⭐388)](https://github.com/gotranspile/cxgo) — Transpile C to Go ☆`388`

### UUID

*   [google/uuid (⭐6k)](https://github.com/google/uuid) — UUID generation and parsing ☆`6,032`
*   [oklog/ulid (⭐5k)](https://github.com/oklog/ulid) — ULID implementation ☆`5,023`
*   [gofrs/uuid (⭐1.8k)](https://github.com/gofrs/uuid) — UUID library for Go ☆`1,794`
*   [osamingo/indigo (⭐112)](https://github.com/osamingo/indigo) — Sonyflake-based ID generator ☆`112`
*   [sdrapkin/guid (⭐73)](https://github.com/sdrapkin/guid) — Fast cryptographically safe Guid generator for Go ☆`73`
*   [twharmon/gouid (⭐26)](https://github.com/twharmon/gouid) — Fast, dependable universally unique ids ☆`26`

## Version Control & Packages

### Git APIs

*   [google/go-github (⭐11k)](https://github.com/google/go-github) — Go library for accessing the GitHub v3 API ☆`11,188`
*   [shurcooL/githubv4 (⭐1.2k)](https://github.com/shurcooL/githubv4) — GitHub GraphQL API v4 client ☆`1,185`
*   [go-playground/webhooks (⭐1k)](https://github.com/go-playground/webhooks) — Webhook receiver for GitHub, Bitbucket, GitLab, Gogs ☆`1,028`
*   [andygrunwald/go-trending (⭐145)](https://github.com/andygrunwald/go-trending) — Access GitHub trending repositories ☆`145`
*   [andygrunwald/go-gerrit (⭐104)](https://github.com/andygrunwald/go-gerrit) — Go client/library for Gerrit Code Review ☆`104`

### Package Management

*   [anchore/syft (⭐8.7k)](https://github.com/anchore/syft) — SBOM generator for containers ☆`8,687`
*   [nao1215/gup (⭐564)](https://github.com/nao1215/gup) — gup - Update binaries installed by "go install" with goroutines. ☆`564`
*   [marwanhawari/stew (⭐340)](https://github.com/marwanhawari/stew) — An independent package manager for compiled binaries. ☆`340`
*   [chaindead/modup (⭐63)](https://github.com/chaindead/modup) — TUI for Go dependency updates ☆`63`

### Version Control

*   [go-git/go-git (⭐7.3k)](https://github.com/go-git/go-git) — Pure Go Git implementation ☆`7,345`
*   [antham/chyle (⭐159)](https://github.com/antham/chyle) — Changelog generator from Git ☆`159`
*   [gabyx/Githooks (⭐122)](https://github.com/gabyx/Githooks) — Per-repo shared Git hooks ☆`122`
*   [antham/gommit (⭐115)](https://github.com/antham/gommit) — Enforce git message commit consistency ☆`115`
*   [jfrog/froggit-go (⭐53)](https://github.com/jfrog/froggit-go) — Universal VCS client library ☆`53`
*   [kazhuravlev/git-tools (⭐31)](https://github.com/kazhuravlev/git-tools) — Useful set of tools which helps to manage git tags ☆`32`

## Web Development

### Microservices

*   [zeromicro/go-zero (⭐33k)](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`32,905`
*   [go-kit/kit (⭐28k)](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,473`
*   [go-kratos/kratos (⭐26k)](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,600`
*   [micro/go-micro (⭐23k)](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,727`
*   [smallnest/rpcx (⭐8.3k)](https://github.com/smallnest/rpcx) — Feature-rich RPC framework ☆`8,277`
*   [cloudwego/kitex (⭐7.9k)](https://github.com/cloudwego/kitex) — High-performance Go RPC framework ☆`7,918`
*   [go-dev-frame/sponge (⭐2.8k)](https://github.com/go-dev-frame/sponge) — Code generation framework for Go ☆`2,812`
*   [go-eagle/eagle (⭐2.4k)](https://github.com/go-eagle/eagle) — A Go framework for the API or Microservice ☆`2,424`
*   [unionj-cloud/go-doudou (⭐1.2k)](https://github.com/unionj-cloud/go-doudou) — OpenAPI 3 and gRPC microservices framework ☆`1,172`
*   [trpc-group/trpc-go (⭐1.1k)](https://github.com/trpc-group/trpc-go) — A pluggable, high-performance RPC framework written in golang ☆`1,137`
*   [gmsec/micro (⭐25)](https://github.com/gmsec/micro) — A Go distributed systems development framework ☆`25`

### Middlewares

*   [urfave/negroni (⭐7.5k)](https://github.com/urfave/negroni) — Idiomatic HTTP Middleware for Golang ☆`7,532`
*   [tdewolff/minify (⭐4.1k)](https://github.com/tdewolff/minify) — Go minifiers for web formats ☆`4,089`
*   [justinas/alice (⭐3.3k)](https://github.com/justinas/alice) — Painless middleware chaining for Go ☆`3,348`
*   [rs/cors (⭐2.9k)](https://github.com/rs/cors) — Go net/http configurable handler to handle CORS requests ☆`2,874`
*   [didip/tollbooth (⭐2.9k)](https://github.com/didip/tollbooth) — Simple middleware to rate-limit HTTP requests. ☆`2,859`
*   [unrolled/render (⭐2k)](https://github.com/unrolled/render) — Render JSON, XML, HTML, binary ☆`1,992`
*   [lingrino/go-fault (⭐553)](https://github.com/lingrino/go-fault) — go fault injection library ☆`553`
*   [jub0bs/cors (⭐202)](https://github.com/jub0bs/cors) — perhaps the best CORS middleware library for Go ☆`207`
*   [faabiosr/echo-middleware (⭐16)](https://github.com/faabiosr/echo-middleware) — Middlewares for Echo framework ☆`16`

### Routers

*   [gorilla/mux (⭐22k)](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,842`
*   [go-chi/chi (⭐22k)](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`21,968`
*   [gowww/router (⭐184)](https://github.com/gowww/router) — A lightning fast HTTP router ☆`184`
*   [ngamux/ngamux (⭐70)](https://github.com/ngamux/ngamux) — Simple HTTP router for Go ☆`70`
*   [bmf-san/goblin (⭐82)](https://github.com/bmf-san/goblin) — A golang http router based on trie tree. ☆`82`
*   [muir/nchi (⭐18)](https://github.com/muir/nchi) — golang http router with elegance, speed, and flexibility ☆`18`

### Template Engines

*   [a-h/templ (⭐10k)](https://github.com/a-h/templ) — A language for writing HTML user interfaces in Go. ☆`10,219`
*   [valyala/quicktemplate (⭐3.3k)](https://github.com/valyala/quicktemplate) — Fast template engine for Go ☆`3,314`
*   [johnfercher/maroto (⭐2.7k)](https://github.com/johnfercher/maroto) — Create PDFs with Bootstrap grid ☆`2,673`
*   [CloudyKit/jet (⭐1.4k)](https://github.com/CloudyKit/jet) — Jet template engine ☆`1,394`
*   [osteele/liquid (⭐346)](https://github.com/osteele/liquid) — A Liquid template engine in Go ☆`346`
*   [go-sprout/sprout (⭐212)](https://github.com/go-sprout/sprout) — Template functions for Go ☆`213`
*   [goradd/got (⭐38)](https://github.com/goradd/got) — Template engine with Go code output ☆`38`

### Web Frameworks

*   [gin-gonic/gin (⭐88k)](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`88,295`
*   [gofiber/fiber (⭐40k)](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`39,567`
*   [beego/beego (⭐32k)](https://github.com/beego/beego) — High-performance web framework ☆`32,407`
*   [labstack/echo (⭐32k)](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,303`
*   [gofr-dev/gofr (⭐22k)](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`21,680`
*   [gogf/gf (⭐13k)](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,106`
*   [cloudwego/hertz (⭐7.2k)](https://github.com/cloudwego/hertz) — High-performance HTTP framework ☆`7,160`
*   [goadesign/goa (⭐6.1k)](https://github.com/goadesign/goa) — Design-first API framework ☆`6,072`
*   [apache/dubbo-go (⭐4.9k)](https://github.com/apache/dubbo-go) — Go Implementation For Apache Dubbo . ☆`4,912`
*   [goravel/goravel (⭐4.5k)](https://github.com/goravel/goravel) — The full-featured Golang Development Framework skeleton ☆`4,484`
*   [danielgtaylor/huma (⭐4k)](https://github.com/danielgtaylor/huma) — Huma REST/HTTP API Framework for Golang with OpenAPI 3.1 ☆`3,973`
*   [documize/community (⭐2.4k)](https://github.com/documize/community) — Modern Confluence alternative ☆`2,382`
*   [go-sonic/sonic (⭐2.1k)](https://github.com/go-sonic/sonic) — Blogging platform in Go ☆`2,117`
*   [go-goyave/goyave (⭐1.8k)](https://github.com/go-goyave/goyave) — The enterprise REST API framework ☆`1,769`
*   [go-fuego/fuego (⭐1.7k)](https://github.com/go-fuego/fuego) — Web framework with OpenAPI 3 ☆`1,698`
*   [templui/templui (⭐1.5k)](https://github.com/templui/templui) — UI components for Templ ☆`1,534`
*   [savsgio/atreugo (⭐1.3k)](https://github.com/savsgio/atreugo) — Micro web framework on fasthttp ☆`1,303`
*   [ankorstore/yokai (⭐826)](https://github.com/ankorstore/yokai) — Modular framework for Go apps ☆`826`
*   [indeedeng/iwf (⭐637)](https://github.com/indeedeng/iwf) — Workflow-as-code orchestration ☆`637`
*   [i-love-flamingo/flamingo-commerce (⭐588)](https://github.com/i-love-flamingo/flamingo-commerce) — Flexible Go web framework ☆`588`
*   [i-love-flamingo/flamingo (⭐559)](https://github.com/i-love-flamingo/flamingo) — Flexible Go web framework ☆`559`
*   [rookie-ninja/rk-boot (⭐574)](https://github.com/rookie-ninja/rk-boot) — Enterprise microservice framework ☆`574`
*   [fastschema/fastschema (⭐547)](https://github.com/fastschema/fastschema) — All-in-One Backend as a Service with Headless CMS Power ☆`548`
*   [uadmin/uadmin (⭐355)](https://github.com/uadmin/uadmin) — The web framework for Golang ☆`355`
*   [xxjwxc/ginrpc (⭐302)](https://github.com/xxjwxc/ginrpc) — gin auto binding, grpc and annotated route ☆`302`
*   [hidevopsio/hiboot (⭐179)](https://github.com/hidevopsio/hiboot) — High-performance CLI and web apps ☆`179`
*   [beatlabs/patron (⭐127)](https://github.com/beatlabs/patron) — Cloud-native microservice framework ☆`127`
*   [gone-io/gone (⭐131)](https://github.com/gone-io/gone) — Lightweight DI framework ☆`130`
*   [claygod/microservice (⭐122)](https://github.com/claygod/microservice) — Simple microservice framework ☆`122`
*   [gookit/rux (⭐99)](https://github.com/gookit/rux) — Simple and fast web framework ☆`99`
*   [yaitoo/xun (⭐91)](https://github.com/yaitoo/xun) — Web framework on html/template ☆`91`
*   [go-spring/spring-core (⭐80)](https://github.com/go-spring/spring-core) — Spring-inspired framework for Go ☆`80`
*   [napsy/go-css (⭐93)](https://github.com/napsy/go-css) — A very simple CSS parser, written in Go ☆`93`
*   [abemedia/go-don (⭐58)](https://github.com/abemedia/go-don) — API framework written in Golang. ☆`58`
*   [JiveGroup/gFly (⭐48)](https://github.com/JiveGroup/gFly) — Laravel inspired web framework written in Go ☆`48`
*   [clubpay/ronykit (⭐36)](https://github.com/clubpay/ronykit) — API Framework supporting REST and RPC. ☆`36`
*   [SaiNageswarS/go-api-boot (⭐35)](https://github.com/SaiNageswarS/go-api-boot) — gRPC + HTTP/2 production framework ☆`35`

### WebAssembly

*   [tinygo-org/tinygo (⭐17k)](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,338`
*   [agnivade/wasmbrowsertest (⭐206)](https://github.com/agnivade/wasmbrowsertest) — Run WASM tests inside your browser ☆`206`
*   [extism/go-sdk (⭐169)](https://github.com/extism/go-sdk) — Extism Go SDK - easily run WebAssembly modules in your Go applications ☆`169`

## Workflow & Scheduling

### Job Scheduler

*   [go-co-op/gocron (⭐7k)](https://github.com/go-co-op/gocron) — Easy and fluent Go cron scheduling ☆`7,000`
*   [hatchet-dev/hatchet (⭐6.8k)](https://github.com/hatchet-dev/hatchet) — Run Background Tasks at Scale ☆`6,821`
*   [reugn/go-quartz (⭐2k)](https://github.com/reugn/go-quartz) — Minimalist and zero-dependency scheduling library for Go ☆`2,010`
*   [adhocore/gronx (⭐501)](https://github.com/adhocore/gronx) — Lightweight cron expression parser ☆`501`
*   [fieldryand/goflow (⭐476)](https://github.com/fieldryand/goflow) — Simple but powerful DAG scheduler and dashboard ☆`476`
*   [madflojo/tasks (⭐324)](https://github.com/madflojo/tasks) — In-process task scheduler ☆`325`
*   [bart6114/cheek (⭐195)](https://github.com/bart6114/cheek) — cheek: a pico-sized declarative job scheduler ☆`195`
*   [onatm/clockwerk (⭐182)](https://github.com/onatm/clockwerk) — Job Scheduling Library ☆`182`
*   [deepaksinghvi/cdule (⭐61)](https://github.com/deepaksinghvi/cdule) — Golang job scheduler ☆`61`
*   [pardnchiu/go-scheduler (⭐33)](https://github.com/pardnchiu/go-scheduler) — Scheduler with standard cron and task dependencies ☆`33`
*   [romshark/sched (⭐30)](https://github.com/romshark/sched) — A job scheduler for Go with the ability to fast-forward time. ☆`30`

### Workflow Frameworks

*   [redpanda-data/connect (⭐8.6k)](https://github.com/redpanda-data/connect) — Fancy stream processing made operationally mundane ☆`8,629`
*   [dagucloud/dagu (⭐3.2k)](https://github.com/dagucloud/dagu) — Workflow engine with Web UI ☆`3,271`
*   [jf-tech/omniparser (⭐1.1k)](https://github.com/jf-tech/omniparser) — ETL streaming parser for Go ☆`1,081`
*   [noneback/go-taskflow (⭐622)](https://github.com/noneback/go-taskflow) — Task-parallel programming library ☆`622`
*   [cadence-workflow/cadence-go-client (⭐375)](https://github.com/cadence-workflow/cadence-go-client) — Cadence workflow client for Go ☆`375`
*   [luno/workflow (⭐229)](https://github.com/luno/workflow) — Type-safe workflow orchestration ☆`230`
*   [rhosocial/go-dag (⭐37)](https://github.com/rhosocial/go-dag) — DAG-based workflow framework ☆`37`

***

## 🏆 Top 100 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1.  [ollama/ollama (⭐169k)](https://github.com/ollama/ollama) — Run LLMs locally ☆`168,767`
2.  [kubernetes/kubernetes (⭐122k)](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`121,679`
3.  [gin-gonic/gin (⭐88k)](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`88,295`
4.  [junegunn/fzf (⭐79k)](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`79,420`
5.  [caddyserver/caddy (⭐71k)](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`71,488`
6.  [moby/moby (⭐72k)](https://github.com/moby/moby) — Container ecosystem components ☆`71,485`
7.  [prometheus/prometheus (⭐63k)](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`63,557`
8.  [traefik/traefik (⭐63k)](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`62,666`
9.  [pocketbase/pocketbase (⭐58k)](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`57,573`
10. [golang-standards/project-layout (⭐56k)](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`55,753`
11. [go-gitea/gitea (⭐55k)](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`54,858`
12. [wagoodman/dive (⭐54k)](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`53,759`
13. [etcd-io/etcd (⭐52k)](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`51,617`
14. [ethereum/go-ethereum (⭐51k)](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`50,977`
15. [mudler/LocalAI (⭐45k)](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`45,332`
16. [milvus-io/milvus (⭐44k)](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`43,763`
17. [spf13/cobra (⭐44k)](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`43,657`
18. [charmbracelet/bubbletea (⭐41k)](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`41,516`
19. [pingcap/tidb (⭐40k)](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`39,962`
20. [go-gorm/gorm (⭐40k)](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,672`
21. [gofiber/fiber (⭐40k)](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`39,567`
22. [harness/harness (⭐35k)](https://github.com/harness/harness) — End-to-end developer platform ☆`34,631`
23. [schollz/croc (⭐35k)](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`34,628`
24. [restic/restic (⭐33k)](https://github.com/restic/restic) — Fast, secure backup program ☆`33,082`
25. [zeromicro/go-zero (⭐33k)](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`32,905`
26. [k3s-io/k3s (⭐33k)](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`32,728`
27. [beego/beego (⭐32k)](https://github.com/beego/beego) — High-performance web framework ☆`32,407`
28. [labstack/echo (⭐32k)](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,303`
29. [cockroachdb/cockroach (⭐32k)](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`32,044`
30. [kubernetes/minikube (⭐32k)](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,688`
31. [seaweedfs/seaweedfs (⭐31k)](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`31,490`
32. [influxdata/influxdb (⭐31k)](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,434`
33. [grafana/k6 (⭐30k)](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`30,337`
34. [spf13/viper (⭐30k)](https://github.com/spf13/viper) — Go configuration with fangs ☆`30,183`
35. [fyne-io/fyne (⭐28k)](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`28,110`
36. [go-kit/kit (⭐28k)](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,473`
37. [stretchr/testify (⭐26k)](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`25,926`
38. [sirupsen/logrus (⭐26k)](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,706`
39. [go-kratos/kratos (⭐26k)](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,600`
40. [gocolly/colly (⭐25k)](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,228`
41. [tsenart/vegeta (⭐25k)](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`24,996`
42. [uber-go/zap (⭐24k)](https://github.com/uber-go/zap) — Fast structured logging ☆`24,410`
43. [urfave/cli (⭐24k)](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`23,961`
44. [air-verse/air (⭐23k)](https://github.com/air-verse/air) — Live reload for Go apps ☆`23,328`
45. [valyala/fasthttp (⭐23k)](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,327`
46. [grpc/grpc-go (⭐23k)](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,900`
47. [micro/go-micro (⭐23k)](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,727`
48. [jaegertracing/jaeger (⭐23k)](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`22,677`
49. [dolthub/dolt (⭐22k)](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`22,116`
50. [redis/go-redis (⭐22k)](https://github.com/redis/go-redis) — Redis Go client ☆`22,035`
51. [go-chi/chi (⭐22k)](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`21,968`
52. [FiloSottile/age (⭐22k)](https://github.com/FiloSottile/age) — Simple encryption tool ☆`21,953`
53. [gorilla/mux (⭐22k)](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,842`
54. [gofr-dev/gofr (⭐22k)](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`21,680`
55. [dgraph-io/dgraph (⭐22k)](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,658`
56. [samber/lo (⭐21k)](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`21,190`
57. [vitessio/vitess (⭐21k)](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`20,906`
58. [qax-os/excelize (⭐20k)](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,472`
59. [antonmedv/fx (⭐20k)](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,397`
60. [apache/casbin (⭐20k)](https://github.com/apache/casbin) — Authorization library for Go ☆`19,992`
61. [go-playground/validator (⭐20k)](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`19,865`
62. [nats-io/nats-server (⭐20k)](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`19,571`
63. [golangci/golangci-lint (⭐19k)](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`18,806`
64. [golang-migrate/migrate (⭐18k)](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,348`
65. [jmoiron/sqlx (⭐18k)](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,573`
66. [rqlite/rqlite (⭐17k)](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,416`
67. [tinygo-org/tinygo (⭐17k)](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,338`
68. [sqlc-dev/sqlc (⭐17k)](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`17,330`
69. [keploy/keploy (⭐17k)](https://github.com/keploy/keploy) — API testing with auto mocks ☆`17,091`
70. [ent/ent (⭐17k)](https://github.com/ent/ent) — An entity framework for Go ☆`17,020`
71. [ipfs/kubo (⭐17k)](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`16,985`
72. [VictoriaMetrics/VictoriaMetrics (⭐17k)](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`16,741`
73. [fatih/vim-go (⭐16k)](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,230`
74. [pion/webrtc (⭐16k)](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,208`
75. [goreleaser/goreleaser (⭐16k)](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,702`
76. [hashicorp/packer (⭐16k)](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,640`
77. [dgraph-io/badger (⭐16k)](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,560`
78. [tidwall/gjson (⭐15k)](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,482`
79. [go-task/task (⭐15k)](https://github.com/go-task/task) — Fast cross-platform build tool inspired by Make ☆`15,291`
80. [go-sql-driver/mysql (⭐15k)](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,287`
81. [kubernetes-sigs/kind (⭐15k)](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,159`
82. [PuerkitoBio/goquery (⭐15k)](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,926`
83. [panjf2000/ants (⭐14k)](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,387`
84. [webview/webview (⭐14k)](https://github.com/webview/webview) — Tiny webview library for Go ☆`14,010`
85. [bytebase/bytebase (⭐14k)](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`13,903`
86. [cloudflare/cloudflared (⭐14k)](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`13,811`
87. [jackc/pgx (⭐14k)](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`13,625`
88. [gizak/termui (⭐14k)](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,540`
89. [juicedata/juicefs (⭐13k)](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`13,429`
90. [golang/groupcache (⭐13k)](https://github.com/golang/groupcache) — Distributed cache library ☆`13,337`
91. [gopherjs/gopherjs (⭐13k)](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,139`
92. [hibiken/asynq (⭐13k)](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`13,133`
93. [gogf/gf (⭐13k)](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,106`
94. [hajimehoshi/ebiten (⭐13k)](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`13,087`
95. [chromedp/chromedp (⭐13k)](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`12,941`
96. [IBM/sarama (⭐12k)](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,460`
97. [rs/zerolog (⭐12k)](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,320`
98. [Shopify/toxiproxy (⭐12k)](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`11,937`
99. [drakkan/sftpgo (⭐12k)](https://github.com/drakkan/sftpgo) — Full-featured SFTP/FTP/HTTP server ☆`11,919`
100.    [kubeshark/kubeshark (⭐12k)](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`11,868`

## Gophers

*   [MariaLetta/free-gophers-pack (⭐3.9k)](https://github.com/MariaLetta/free-gophers-pack) — This pack of 100+ gopher pictures and elements
*   [keygx/Go-gopher-Vector (⭐75)](https://github.com/keygx/Go-gopher-Vector) — Go gopher Vector Data (.ai, .svg)
*   [ashleymcnamara/gophers (⭐3.1k)](https://github.com/ashleymcnamara/gophers) — Gopher Artwork by Ashley McNamara
*   [sillecelik/go-gopher (⭐162)](https://github.com/sillecelik/go-gopher) — The Go Gopher Amigurumi Pattern
*   [GolangUA/gopher-logos (⭐140)](https://github.com/GolangUA/gopher-logos) — adorable gopher logos
*   [egonelbre/gophers (⭐3.8k)](https://github.com/egonelbre/gophers) — gophers artwork
*   [scraly/gophers (⭐36)](https://github.com/scraly/gophers) — Gopher artwork (Golang mascot)

## Contributing

Please see [CONTRIBUTING](https://github.com/abordage/awesome-go/blob/main/README.md/.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request — contributions are welcome!

## Credits

*   [avelino/awesome-go (⭐170k)](https://github.com/avelino/awesome-go)
*   [All Contributors (⭐3)](https://github.com/abordage/awesome-go/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](https://github.com/abordage/awesome-go/blob/main/README.md/LICENSE) for more information.

