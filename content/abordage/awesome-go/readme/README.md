# Awesome Go Overview

Structured collection of Go frameworks, libraries, tools, and resources. Automatically maintained and up-to-date with metadata, filtering, and comprehensive categorization.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/abordage/awesome-go/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 abordage/awesome-go](https://github.com/abordage/awesome-go) · ⭐ 2 · 🏷️ Programming Languages

[ [Daily](/content/abordage/awesome-go/README.md) / [Weekly](/content/abordage/awesome-go/week/README.md) / Overview ]

---

# Awesome Go

[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-go?label=last%20update)](https://github.com/abordage/awesome-go/blob/main/README.md/README.md)
[![License](https://img.shields.io/github/license/abordage/awesome-go)](https://github.com/abordage/awesome-go/blob/main/README.md/LICENSE)

**Automated. Curated. Ranked.**

Go libraries, tools, and applications from the community. This awesome list is automatically maintained with daily GitHub API updates. Projects are re-ranked daily based on current activity metrics.

**Daily process:** Merge community PRs → Scan repos → Filter stale projects → Recalculate scores → Rebuild list

*   [Actor Model](#actor-model)
*   [Artificial Intelligence](#artificial-intelligence)
*   [Audio and Music](#audio-and-music)
*   [Authentication and OAuth](#authentication-and-oauth)
*   [Benchmarks](#benchmarks)
*   [Blockchain](#blockchain)
*   [Bot Building](#bot-building)
*   [Build Automation](#build-automation)
*   [Code Analysis](#code-analysis)
*   [Command Line](#command-line)
    *   [Advanced Console UIs](#advanced-console-uis)
    *   [Standard CLI](#standard-cli)
*   [Configuration](#configuration)
*   [Continuous Integration](#continuous-integration)
*   [CSS Preprocessors](#css-preprocessors)
*   [Data Integration Frameworks](#data-integration-frameworks)
*   [Data Structures and Algorithms](#data-structures-and-algorithms)
    *   [Bit Sets](#bit-sets)
    *   [Bit-packing and Compression](#bit-packing-and-compression)
    *   [Bloom and Cuckoo Filters](#bloom-and-cuckoo-filters)
    *   [Data Structure and Algorithm Collections](#data-structure-and-algorithm-collections)
    *   [Maps](#maps)
    *   [Miscellaneous Data Structures and Algorithms](#miscellaneous-data-structures-and-algorithms)
    *   [Pipes](#pipes)
    *   [Queues](#queues)
    *   [Sets](#sets)
    *   [Text Analysis](#text-analysis)
    *   [Trees](#trees)
*   [Database](#database)
    *   [Caches](#caches)
    *   [Database Schema Migration](#database-schema-migration)
    *   [Database Tools](#database-tools)
    *   [Databases Implemented in Go](#databases-implemented-in-go)
    *   [SQL Query Builders](#sql-query-builders)
*   [Database Drivers](#database-drivers)
    *   [Interfaces to Multiple Backends](#interfaces-to-multiple-backends)
    *   [NoSQL Database Drivers](#nosql-database-drivers)
    *   [Relational Database Drivers](#relational-database-drivers)
    *   [Search and Analytic Databases](#search-and-analytic-databases)
*   [Date and Time](#date-and-time)
*   [Distributed Systems](#distributed-systems)
*   [Dynamic DNS](#dynamic-dns)
*   [Editor Plugins](#editor-plugins)
*   [Email](#email)
*   [Embeddable Scripting Languages](#embeddable-scripting-languages)
*   [Error Handling](#error-handling)
*   [File Handling](#file-handling)
*   [Financial](#financial)
*   [Forms](#forms)
*   [Functional](#functional)
*   [Game Development](#game-development)
*   [Generators](#generators)
*   [Geographic](#geographic)
*   [Go Compilers](#go-compilers)
*   [Go Generate Tools](#go-generate-tools)
*   [Go Tools](#go-tools)
*   [Goroutines](#goroutines)
*   [GUI](#gui)
*   [Hardware](#hardware)
*   [Images](#images)
*   [IoT (Internet of Things)](#iot-\(internet-of-things\))
*   [Job Scheduler](#job-scheduler)
*   [JSON](#json)
*   [Logging](#logging)
*   [Machine Learning](#machine-learning)
*   [Messaging](#messaging)
*   [Microsoft Office](#microsoft-office)
    *   [Microsoft Excel](#microsoft-excel)
    *   [Microsoft Word](#microsoft-word)
*   [Middlewares](#middlewares)
*   [Miscellaneous](#miscellaneous)
    *   [Dependency Injection](#dependency-injection)
    *   [Project Layout](#project-layout)
    *   [Strings](#strings)
    *   [Uncategorized](#uncategorized)
*   [Natural Language Processing](#natural-language-processing)
    *   [Language Detection](#language-detection)
    *   [Morphological Analyzers](#morphological-analyzers)
    *   [Slugifiers](#slugifiers)
    *   [Tokenizers](#tokenizers)
    *   [Translation](#translation)
    *   [Transliteration](#transliteration)
*   [Networking](#networking)
    *   [HTTP Clients](#http-clients)
*   [OpenGL](#opengl)
*   [ORM](#orm)
*   [Package Management](#package-management)
*   [Performance](#performance)
*   [Query Language](#query-language)
*   [Reflection](#reflection)
*   [Resource Embedding](#resource-embedding)
*   [Routers](#routers)
*   [Science and Data Analysis](#science-and-data-analysis)
*   [Security](#security)
*   [Serialization](#serialization)
*   [Server Applications](#server-applications)
*   [Software Packages](#software-packages)
    *   [DevOps Tools](#devops-tools)
    *   [Other Software](#other-software)
*   [Stream Processing](#stream-processing)
*   [Style Guides](#style-guides)
*   [Template Engines](#template-engines)
*   [Testing](#testing)
    *   [Fail injection](#fail-injection)
    *   [Fuzzing](#fuzzing)
    *   [Mock](#mock)
    *   [Selenium and browser control tools](#selenium-and-browser-control-tools)
    *   [Testing Frameworks](#testing-frameworks)
*   [Text Processing](#text-processing)
    *   [Formatters](#formatters)
    *   [Markup Languages](#markup-languages)
    *   [Parsers/Encoders/Decoders](#parsers/encoders/decoders)
    *   [Regular Expressions](#regular-expressions)
    *   [Sanitation](#sanitation)
    *   [Scrapers](#scrapers)
    *   [Utility/Miscellaneous](#utility/miscellaneous)
*   [Third-party APIs](#third-party-apis)
*   [Utilities](#utilities)
*   [UUID](#uuid)
*   [Validation](#validation)
*   [Version Control](#version-control)
*   [Video](#video)
*   [Web Frameworks](#web-frameworks)
*   [WebAssembly](#webassembly)
*   [Webhooks Server](#webhooks-server)
*   [Windows](#windows)
*   [Workflow Frameworks](#workflow-frameworks)
*   [XML](#xml)
*   [Zero Trust](#zero-trust)

## Actor Model

*   [asynkron/protoactor-go](https://github.com/asynkron/protoactor-go) — Proto Actor - Ultra fast distributed actors for Go, C# and Java/Kotlin ☆`5,379`
*   [ergo-services/ergo](https://github.com/ergo-services/ergo) — An actor-based Framework with network transparency for creating event-driven architecture in Golang. Inspired by Erlang. Zero dependencies. ☆`4,268`
*   [anthdm/hollywood](https://github.com/anthdm/hollywood) — Blazingly fast and light-weight Actor engine written in Golang ☆`2,105`
*   [Tochemey/goakt](https://github.com/Tochemey/goakt) — \[Go] Distributed Actor/Grain framework using protocol buffers as message for Golang ☆`300`

## Artificial Intelligence

*   [ollama/ollama](https://github.com/ollama/ollama) — Get up and running with OpenAI gpt-oss, DeepSeek-R1, Gemma 3 and other models. ☆`156,461`
*   [mudler/LocalAI](https://github.com/mudler/LocalAI) — The free, Open Source alternative to OpenAI, Claude and others. Self-hosted and local-first. Drop-in replacement for OpenAI, running on consumer-grade hardware. No GPU required. Runs gguf, transformers, diffusers and many more. Features: Generate Text, Audio, Video, Images, Voice Cloning, Distributed, P2P and decentralized inference ☆`39,068`
*   [tmc/langchaingo](https://github.com/tmc/langchaingo) — LangChain for Go, the easiest way to write LLM-based programs in Go ☆`8,064`
*   [maximhq/bifrost](https://github.com/maximhq/bifrost) — Fastest LLM gateway (50x faster than LiteLLM) with adaptive load balancer, cluster mode, guardrails, 1000+ models support & <100 µs overhead at 5k RPS. ☆`1,152`
*   [philippgille/chromem-go](https://github.com/philippgille/chromem-go) — Embeddable vector database for Go with Chroma-like interface and zero third-party dependencies. In-memory with optional persistence. ☆`782`
*   [universal-tool-calling-protocol/go-utcp](https://github.com/universal-tool-calling-protocol/go-utcp) — Official Go implementation of the UTCP ☆`86`
*   [presbrey/ollamafarm](https://github.com/presbrey/ollamafarm) — Manage and use multiple Ollama instances with automatic offline detection/failover and model availability tracking ☆`92`

## Audio and Music

*   [ebitengine/oto](https://github.com/ebitengine/oto) — A low-level library to play sound on multiple platforms ☆`1,822`
*   [gordonklaus/portaudio](https://github.com/gordonklaus/portaudio) — Go bindings for the PortAudio audio I/O library ☆`808`
*   [DylanMeeus/GoAudio](https://github.com/DylanMeeus/GoAudio) — Go tools for audio processing & creation ☆`394`
*   [gen2brain/malgo](https://github.com/gen2brain/malgo) — Mini audio library ☆`359`
*   [mewkiz/flac](https://github.com/mewkiz/flac) — Package flac provides access to FLAC (Free Lossless Audio Codec) streams. ☆`346`
*   [tosone/minimp3](https://github.com/tosone/minimp3) — Decode mp3 ☆`132`
*   [dh1tw/gosamplerate](https://github.com/dh1tw/gosamplerate) — Go Bindings for libsamplerate ☆`37`

## Authentication and OAuth

*   [casbin/casbin](https://github.com/casbin/casbin) — An authorization library that supports access control models like ACL, RBAC, ABAC in Golang ☆`19,443`
*   [golang-jwt/jwt](https://github.com/golang-jwt/jwt) — Go implementation of JSON Web Tokens (JWT). ☆`8,700`
*   [markbates/goth](https://github.com/markbates/goth) — Package goth provides a simple, clean, and idiomatic way to write authentication packages for Go web applications. ☆`6,342`
*   [golang/oauth2](https://github.com/golang/oauth2) — Go OAuth2 ☆`5,757`
*   [ory/keto](https://github.com/ory/keto) — The most scalable and customizable permission server on the market. Fix your slow or broken permission system with Google's proven "Zanzibar" approach. Supports ACL, RBAC, and more. Written in Go, cloud native, headless, API-first. Available as a service on Ory Network and for self-hosters. ☆`5,193`
*   [openfga/openfga](https://github.com/openfga/openfga) — A high performance and flexible authorization/permission engine built for developers and inspired by Google Zanzibar ☆`4,439`
*   [cerbos/cerbos](https://github.com/cerbos/cerbos) — Cerbos is the open core, language-agnostic, scalable authorization solution that makes user permissions and authorization simple to implement and manage by writing context-aware access control policies for your application resources. ☆`4,142`
*   [aarondl/authboss](https://github.com/aarondl/authboss) — The boss of http auth. ☆`4,111`
*   [alexedwards/scs](https://github.com/alexedwards/scs) — HTTP Session Management for Go ☆`2,472`
*   [lestrrat-go/jwx](https://github.com/lestrrat-go/jwx) — Complete implementation of JWx (Javascript Object Signing and Encryption/JOSE) technologies for Go ☆`2,262`
*   [openshift/osin](https://github.com/openshift/osin) — Golang OAuth2 server library ☆`1,933`
*   [dghubble/gologin](https://github.com/dghubble/gologin) — Go login handlers for authentication providers (OAuth1, OAuth2) ☆`1,934`
*   [zitadel/oidc](https://github.com/zitadel/oidc) — Easy to use OpenID Connect client and server library written for Go and certified by the OpenID Foundation ☆`1,714`
*   [cristalhq/jwt](https://github.com/cristalhq/jwt) — Safe, simple and fast JSON Web Tokens for Go ☆`688`
*   [shaj13/go-guardian](https://github.com/shaj13/go-guardian) — Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication. ☆`600`
*   [go-jose/go-jose](https://github.com/go-jose/go-jose) — An implementation of JOSE standards (JWE, JWS, JWT) in Go ☆`460`
*   [abraithwaite/jeff](https://github.com/abraithwaite/jeff) — Jeff provides the simplest way to manage web sessions in Go. ☆`270`
*   [Kwynto/gosession](https://github.com/Kwynto/gosession) — This is quick session for net/http in golang. This package is perhaps the best implementation of the session mechanism, at least it tries to become one. ☆`255`
*   [leodip/goiabada](https://github.com/leodip/goiabada) — Goiabada is an OAuth2 / OpenID Connect server written in Go. ☆`159`
*   [brianvoe/sjwt](https://github.com/brianvoe/sjwt) — Simple JWT Golang ☆`121`
*   [RijulGulati/otpgen](https://github.com/RijulGulati/otpgen) — Library to generate TOTP/HOTP codes ☆`142`
*   [jellydator/sessionup](https://github.com/jellydator/sessionup) — Straightforward HTTP session management ☆`128`
*   [icza/session](https://github.com/icza/session) — Go session management for web servers (including support for Google App Engine - GAE). ☆`118`
*   [essentialkaos/branca](https://github.com/essentialkaos/branca) — Authenticated encrypted API tokens (IETF XChaCha20-Poly1305 AEAD) for Golang ☆`93`
*   [mengzhuo/cookiestxt](https://github.com/mengzhuo/cookiestxt) — cookiestxt implement parser of cookies txt format ☆`21`

## Benchmarks

*   [smallnest/go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) — Go web framework benchmark ☆`2,131`
*   [alecthomas/go\_serialization\_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) — Benchmarks of Go serialization methods ☆`1,616`
*   [SimonWaldherr/golang-benchmarks](https://github.com/SimonWaldherr/golang-benchmarks) — Go(lang) benchmarks - (measure the speed of golang) ☆`141`
*   [feyeleanor/gospeed](https://github.com/feyeleanor/gospeed) — Go micro-benchmarks for calculating the speed of language constructs ☆`126`
*   [nikolaydubina/go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) — Benchmarks of machine learning inference for Go ☆`32`

## Blockchain

*   [ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`50,351`
*   [ipfs/kubo](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`16,812`
*   [lightningnetwork/lnd](https://github.com/lightningnetwork/lnd) — Lightning Network Daemon ☆`8,057`
*   [cosmos/cosmos-sdk](https://github.com/cosmos/cosmos-sdk) — A Framework for Building High Value Public Blockchains ☆`6,851`
*   [gagliardetto/solana-go](https://github.com/gagliardetto/solana-go) — Go SDK library and RPC client for the Solana Blockchain ☆`1,479`
*   [gnolang/gno](https://github.com/gnolang/gno) — Gno: An interpreted, stack-based Go virtual machine to build succinct and composable apps + gno.land: a blockchain for timeless code and fair open-source. ☆`1,015`
*   [cometbft/cometbft](https://github.com/cometbft/cometbft) — CometBFT: A distributed, Byzantine fault-tolerant, deterministic state machine replication engine. A fork and successor to Tendermint Core. ☆`823`
*   [ChainSafe/gossamer](https://github.com/ChainSafe/gossamer) — Go Implementation of the Polkadot Host ☆`457`

## Bot Building

*   [tucnak/telebot](https://github.com/tucnak/telebot) — Telebot is a Telegram bot framework in Go. ☆`4,488`
*   [wabarc/wayback](https://github.com/wabarc/wayback) — An archiving tool with an IM-style interface that prioritizes privacy and accessibility, integrated with various archival services including Internet Archive, archive.today, Ghostarchive, IPFS, Telegraph, and file systems. ☆`2,098`
*   [go-telegram/bot](https://github.com/go-telegram/bot) — Telegram Bot API Go framework ☆`1,452`
*   [mymmrac/telego](https://github.com/mymmrac/telego) — Telegram Bot API library for Go ☆`821`
*   [diamondburned/arikawa](https://github.com/diamondburned/arikawa) — A Golang library and framework for the Discord API. ☆`556`
*   [NicoNex/echotron](https://github.com/NicoNex/echotron) — An elegant and concurrent library for the Telegram bot API in Go. ☆`413`
*   [gempir/go-twitch-irc](https://github.com/gempir/go-twitch-irc) — go irc client for twitch.tv ☆`386`
*   [innogames/slack-bot](https://github.com/innogames/slack-bot) — Ready to use Slack bot for lazy developers: start Jenkins jobs, watch Jira tickets, watch pull requests with AI support... ☆`203`
*   [mr-linch/go-tg](https://github.com/mr-linch/go-tg) — Go client library for accessing Telegram Bot API, with batteries for building complex bots included. ☆`122`
*   [slack-io/slacker](https://github.com/slack-io/slacker) — Slack Bot Framework ☆`59`
*   [onrik/micha](https://github.com/onrik/micha) — Client lib for Telegram bot api ☆`31`

## Build Automation

*   [air-verse/air](https://github.com/air-verse/air) — Live reload for Go apps ☆`22,285`
*   [go-task/task](https://github.com/go-task/task) — A task runner / simpler Make alternative written in Go ☆`14,241`
*   [joerdav/xc](https://github.com/joerdav/xc) — Markdown defined task runner. ☆`1,352`
*   [goyek/goyek](https://github.com/goyek/goyek) — Task automation Go library ☆`638`
*   [flowexec/flow](https://github.com/flowexec/flow) — Local developer automation platform that flows with you ☆`121`

## Code Analysis

*   [golangci/golangci-lint](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`18,027`
*   [mgechev/revive](https://github.com/mgechev/revive) — \~6x faster, stricter, configurable, extensible, and beautiful drop-in replacement for golint ☆`5,349`
*   [kisielk/errcheck](https://github.com/kisielk/errcheck) — errcheck checks that you checked errors. ☆`2,452`
*   [go-critic/go-critic](https://github.com/go-critic/go-critic) — The most opinionated Go source code linter for code audit. ☆`2,020`
*   [segmentio/golines](https://github.com/segmentio/golines) — A golang formatter that fixes long lines ☆`1,131`
*   [daveshanley/vacuum](https://github.com/daveshanley/vacuum) — vacuum is the worlds fastest OpenAPI 3, OpenAPI 2 / Swagger linter and quality analysis tool. Built in go, it tears through API specs faster than you can think. vacuum is compatible with Spectral rulesets and generates compatible reports. ☆`922`
*   [yuroyoro/goast-viewer](https://github.com/yuroyoro/goast-viewer) — Golang AST visualizer ☆`789`
*   [presmihaylov/todocheck](https://github.com/presmihaylov/todocheck) — A static code analyser for annotated TODO comments ☆`437`
*   [mdempsky/unconvert](https://github.com/mdempsky/unconvert) — Remove unnecessary type conversions from Go source ☆`385`
*   [tomarrell/wrapcheck](https://github.com/tomarrell/wrapcheck) — A Go linter to check that errors from external packages are wrapped ☆`353`
*   [mibk/dupl](https://github.com/mibk/dupl) — a tool for code clone detection ☆`357`
*   [shurcooL/gostatus](https://github.com/shurcooL/gostatus) — A command line tool that shows the status of Go repositories. ☆`245`
*   [Antonboom/testifylint](https://github.com/Antonboom/testifylint) — The Golang linter that checks usage of github.com/stretchr/testify. ☆`159`
*   [Crocmagnon/fatcontext](https://github.com/Crocmagnon/fatcontext) — detects nested contexts in loops or function literals ☆`59`
*   [sashamelentyev/usestdlibvars](https://github.com/sashamelentyev/usestdlibvars) — A linter that detect the possibility to use variables/constants from the Go standard library. ☆`46`

## Command Line

### Advanced Console UIs

*   [charmbracelet/bubbletea](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`36,770`
*   [antonmedv/fx](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`19,988`
*   [gizak/termui](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,471`
*   [jroimartin/gocui](https://github.com/jroimartin/gocui) — Minimalist Go package aimed at creating Console User Interfaces. ☆`10,449`
*   [charmbracelet/lipgloss](https://github.com/charmbracelet/lipgloss) — Style definitions for nice terminal layouts ☆`10,036`
*   [charmbracelet/bubbles](https://github.com/charmbracelet/bubbles) — TUI components for Bubble Tea ☆`7,266`
*   [c-bata/go-prompt](https://github.com/c-bata/go-prompt) — Building powerful interactive prompts in Go, inspired by python-prompt-toolkit. ☆`5,429`
*   [pterm/pterm](https://github.com/pterm/pterm) — #PTerm is a modern Go module to easily beautify console output. Featuring charts, progressbars, tables, trees, text input, select menus and much more It's completely configurable and 100% cross-platform compatible. ☆`5,298`
*   [schollz/progressbar](https://github.com/schollz/progressbar) — A really basic thread-safe progress bar for Golang applications ☆`4,584`
*   [mum4k/termdash](https://github.com/mum4k/termdash) — Terminal based dashboard. ☆`2,913`
*   [guptarohit/asciigraph](https://github.com/guptarohit/asciigraph) — make lightweight ASCII line graph in command line apps with no other dependencies ☆`2,922`
*   [briandowns/spinner](https://github.com/briandowns/spinner) — Go (golang) package with 90 configurable terminal spinner/progress indicators. ☆`2,482`
*   [vbauerster/mpb](https://github.com/vbauerster/mpb) — multi progress bar for Go cli applications ☆`2,454`
*   [muesli/termenv](https://github.com/muesli/termenv) — Advanced ANSI style & color support for your terminal applications ☆`1,943`
*   [gookit/color](https://github.com/gookit/color) — Terminal color rendering library, support 8/16 colors, 256 colors, RGB color rendering output ☆`1,567`
*   [logrusorgru/aurora](https://github.com/logrusorgru/aurora) — Golang ultimate ANSI-colors that supports Printf/Sprintf methods ☆`1,476`
*   [mattn/go-isatty](https://github.com/mattn/go-isatty) —  ☆`877`
*   [mattn/go-colorable](https://github.com/mattn/go-colorable) —  ☆`803`
*   [Evertras/bubble-table](https://github.com/Evertras/bubble-table) — A customizable, interactive table component for the Bubble Tea framework ☆`542`

### Standard CLI

*   [spf13/cobra](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`42,472`
*   [urfave/cli](https://github.com/urfave/cli) — A declarative, simple, fast, and fun package for building command line tools in Go ☆`23,721`
*   [elves/elvish](https://github.com/elves/elvish) — Powerful scripting language & versatile interactive shell ☆`6,170`
*   [alecthomas/kingpin](https://github.com/alecthomas/kingpin) — A Go command line and flag parser ☆`3,556`
*   [dnote/dnote](https://github.com/dnote/dnote) — A simple command line notebook ☆`2,983`
*   [spf13/pflag](https://github.com/spf13/pflag) — Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. ☆`2,663`
*   [jessevdk/go-flags](https://github.com/jessevdk/go-flags) — go command line option parser ☆`2,685`
*   [alexflint/go-arg](https://github.com/alexflint/go-arg) — Struct-based argument parsing in Go ☆`2,203`
*   [carapace-sh/carapace-bin](https://github.com/carapace-sh/carapace-bin) — A multi-shell completion binary. ☆`1,595`
*   [nanovms/ops](https://github.com/nanovms/ops) — ops - build and run nanos unikernels ☆`1,432`
*   [carapace-sh/carapace](https://github.com/carapace-sh/carapace) — A multi-shell completion library. ☆`988`
*   [posener/complete](https://github.com/posener/complete) — bash completion written in go + bash completion for go command ☆`947`
*   [leaanthony/clir](https://github.com/leaanthony/clir) — A Simple and Clear CLI library. Dependency free. ☆`195`
*   [urfave/sflags](https://github.com/urfave/sflags) — Generate flags by parsing structures ☆`164`
*   [hedzr/cmdr](https://github.com/hedzr/cmdr) — POSIX-compliant command-line UI (CLI) parser and Hierarchical-configuration operations ☆`141`
*   [reeflective/readline](https://github.com/reeflective/readline) — Shell library with powerful and modern UI, large feature set, and `.inputrc` support ☆`129`
*   [cristalhq/acmd](https://github.com/cristalhq/acmd) — Simple, useful and opinionated CLI package in Go. ☆`134`
*   [codingconcepts/env](https://github.com/codingconcepts/env) — Tag-based environment configuration for structs ☆`126`
*   [reeflective/console](https://github.com/reeflective/console) — Closed-loop application library for Cobra commands (powerful, ready-to-run and easy to use) ☆`100`
*   [dixonwille/wlog](https://github.com/dixonwille/wlog) — A simple logging interface that supports cross-platform color and concurrency. ☆`67`
*   [DavidGamba/go-getoptions](https://github.com/DavidGamba/go-getoptions) — Fully featured Go (golang) command line option parser with built-in auto-completion support. ☆`61`
*   [hashicorp/cli](https://github.com/hashicorp/cli) — A Go library for implementing command-line interfaces. ☆`32`
*   [nyaosorg/go-readline-ny](https://github.com/nyaosorg/go-readline-ny) — The New Yet another Readline for Go ☆`32`
*   [carapace-sh/carapace-spec](https://github.com/carapace-sh/carapace-spec) — A multi-shell completion spec. ☆`24`
*   [sgreben/flagvar](https://github.com/sgreben/flagvar) — A collection of CLI argument types for the Go `flag` package. ☆`47`
*   [jxskiss/mcli](https://github.com/jxskiss/mcli) — A minimal but powerful cli library for Go ☆`42`

## Configuration

*   [spf13/viper](https://github.com/spf13/viper) — Go configuration with fangs ☆`29,597`
*   [bytedance/sonic](https://github.com/bytedance/sonic) — A blazingly fast JSON serializing & deserializing library ☆`8,861`
*   [caarlos0/env](https://github.com/caarlos0/env) — A simple, zero-dependencies library to parse environment variables into structs ☆`5,854`
*   [knadh/koanf](https://github.com/knadh/koanf) — Simple, extremely lightweight, extensible, configuration management library for Go. Supports JSON, TOML, YAML, env, command line, file, S3 etc. Alternative to viper. ☆`3,626`
*   [alecthomas/kong](https://github.com/alecthomas/kong) — Kong is a command-line parser for Go ☆`2,859`
*   [ilyakaznacheev/cleanenv](https://github.com/ilyakaznacheev/cleanenv) — Clean and minimalistic environment configuration reader for Golang ☆`1,992`
*   [adrg/xdg](https://github.com/adrg/xdg) — Go implementation of the XDG Base Directory Specification and XDG user directories ☆`923`
*   [cristalhq/aconfig](https://github.com/cristalhq/aconfig) — Simple, useful and opinionated config loader. ☆`608`
*   [gookit/config](https://github.com/gookit/config) — Go configuration manage (load, get, set, export). support JSON, YAML, TOML, Properties, INI, HCL, ENV and Flags. ☆`572`
*   [kkyr/fig](https://github.com/kkyr/fig) — A minimalist Go configuration library ☆`385`
*   [nil-go/konf](https://github.com/nil-go/konf) — The simplest config loader for Go that reads/watches from file, env, flag and clouds (AWS, Azure, GCP). ☆`357`
*   [hjson/hjson-go](https://github.com/hjson/hjson-go) — Hjson for Go ☆`346`
*   [vrischmann/envconfig](https://github.com/vrischmann/envconfig) — Small library to read your configuration from environment variables ☆`248`
*   [chaindead/zerocfg](https://github.com/chaindead/zerocfg) — Zero-effort, concise configuration management that avoids boilerplate and repetitive actions. ☆`199`
*   [beatlabs/harvester](https://github.com/beatlabs/harvester) — Harvest configuration, watch and notify subscriber ☆`134`
*   [BoRuDar/configuration](https://github.com/BoRuDar/configuration) — Library for setting values to structs' fields from env, flags, files or default tag ☆`108`
*   [gurkankaymak/hocon](https://github.com/gurkankaymak/hocon) — go implementation of lightbend's HOCON configuration library <https://github.com/lightbend/config> ☆`86`
*   [PaddleHQ/go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) — Go package that interfaces with AWS System Manager ☆`62`
*   [omeid/uconfig](https://github.com/omeid/uconfig) — Lightweight, zero-dependency, and extendable configuration management library for Go ☆`72`
*   [go-simpler/env](https://github.com/go-simpler/env) — Load environment variables into a config struct ☆`80`
*   [num30/config](https://github.com/num30/config) — Declarative configuration for Go ☆`60`
*   [atelpis/enflag](https://github.com/atelpis/enflag) — Container-focused Golang config: unify Env & Flag parsing in one call with minimal code and zero dependencies. ☆`34`
*   [wkhere/bcl](https://github.com/wkhere/bcl) — Basic Configuration Language ☆`27`
*   [sakirsensoy/genv](https://github.com/sakirsensoy/genv) — Genv is a library for Go (golang) that makes it easy to read and use environment variables in your projects. It also allows environment variables to be loaded from the .env file. ☆`43`
*   [greencoda/confiq](https://github.com/greencoda/confiq) — Structured data format to config struct decoder library for Go ☆`39`
*   [dsbasko/go-cfg](https://github.com/dsbasko/go-cfg) — The library provides a unified way to read configuration data from different sources, such as environment variables, command line flags, and configuration files. ☆`47`
*   [nasermirzaei89/env](https://github.com/nasermirzaei89/env) — Golang Get Environment Variables Package with Zero Dependencies ☆`22`
*   [romshark/yamagiconf](https://github.com/romshark/yamagiconf) — YAML configuration framework for Go. ☆`18`
*   [deatil/go-array](https://github.com/deatil/go-array) — A Go package that read or set data from map, slice or json ☆`22`

## Continuous Integration

*   [harness/harness](https://github.com/harness/harness) — Harness Open Source is an end-to-end developer platform with Source Control Management, CI/CD Pipelines, Hosted Developer Environments, and Artifact Registries. ☆`33,632`
*   [woodpecker-ci/woodpecker](https://github.com/woodpecker-ci/woodpecker) — Woodpecker is a simple, yet powerful CI/CD engine with great extensibility. ☆`5,732`
*   [ovh/cds](https://github.com/ovh/cds) — Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform ☆`4,782`
*   [raviqqe/muffet](https://github.com/raviqqe/muffet) — Fast website link checker in Go ☆`2,580`
*   [vladopajic/go-test-coverage](https://github.com/vladopajic/go-test-coverage) — go-test-coverage is a tool designed to report issues when test coverage falls below a specified threshold ☆`197`
*   [nikogura/gomason](https://github.com/nikogura/gomason) — A tool for testing, building, signing, and publishing binaries. ☆`66`
*   [opnlabs/dot](https://github.com/opnlabs/dot) — A minimal continuous integration system. Uses docker to run jobs concurrently in stages. ☆`31`
*   [gha-common/go-beautiful-html-coverage](https://github.com/gha-common/go-beautiful-html-coverage) — A GitHub Action to track code coverage in your pull requests, with a beautiful HTML preview, for free. ☆`18`

## CSS Preprocessors

*   [wellington/go-libsass](https://github.com/wellington/go-libsass) — Go wrapper for libsass, the only Sass 3.5 compiler for Go ☆`213`
*   [napsy/go-css](https://github.com/napsy/go-css) — A very simple CSS parser, written in Go ☆`86`

## Data Integration Frameworks

*   [redpanda-data/connect](https://github.com/redpanda-data/connect) — Fancy stream processing made operationally mundane ☆`8,511`
*   [jf-tech/omniparser](https://github.com/jf-tech/omniparser) — omniparser: a native Golang ETL streaming parser and transform library for CSV, JSON, XML, EDI, text, etc. ☆`1,071`

## Data Structures and Algorithms

### Bit Sets

*   [bits-and-blooms/bitset](https://github.com/bits-and-blooms/bitset) — Go package implementing bitsets ☆`1,462`
*   [kelindar/bitmap](https://github.com/kelindar/bitmap) — Simple dense bitmap index in Go with binary operators ☆`367`

### Bit-packing and Compression

*   [RoaringBitmap/roaring](https://github.com/RoaringBitmap/roaring) — Roaring bitmaps in Go (golang), used by InfluxDB, Bleve, DataDog ☆`2,797`
*   [iancmcc/bingo](https://github.com/iancmcc/bingo) — Fast, zero-allocation, lexicographic-order-preserving packing/unpacking of native Go types to bytes. ☆`47`
*   [amallia/go-ef](https://github.com/amallia/go-ef) — A Go implementation of the Elias-Fano encoding ☆`40`

### Bloom and Cuckoo Filters

*   [bits-and-blooms/bloom](https://github.com/bits-and-blooms/bloom) — Go package implementing Bloom filters, used by Milvus and Beego. ☆`2,698`
*   [tylertreat/BoomFilters](https://github.com/tylertreat/BoomFilters) — Probabilistic data structures for processing continuous, unbounded streams. ☆`1,627`
*   [seiflotfy/cuckoofilter](https://github.com/seiflotfy/cuckoofilter) — Cuckoo Filter: Practically Better Than Bloom ☆`1,200`
*   [OldPanda/bloomfilter](https://github.com/OldPanda/bloomfilter) — Yet another Bloomfilter implementation in Go, compatible with Java's Guava library ☆`19`

### Data Structure and Algorithm Collections

*   [Workiva/go-datastructures](https://github.com/Workiva/go-datastructures) — A collection of useful, performant, and threadsafe Go datastructures. ☆`7,864`
*   [liyue201/gostl](https://github.com/liyue201/gostl) — Data structure and algorithm library for go, designed to provide functions similar to C++ STL ☆`1,119`

### Maps

*   [mhmtszr/concurrent-swiss-map](https://github.com/mhmtszr/concurrent-swiss-map) — A high-performance, thread-safe generic concurrent hash map implementation with Swiss Map. ☆`258`
*   [srfrog/dict](https://github.com/srfrog/dict) — Python-like dictionaries for Go ☆`46`
*   [goradd/maps](https://github.com/goradd/maps) — map library using Go generics that offers a standard interface, go routine synchronization, and sorting ☆`51`

### Miscellaneous Data Structures and Algorithms

*   [axiomhq/hyperloglog](https://github.com/axiomhq/hyperloglog) — HyperLogLog with lots of sugar (Sparse, LogLog-Beta bias correction and TailCut space reduction) brought to you by Axiom ☆`1,015`
*   [barweiss/go-tuple](https://github.com/barweiss/go-tuple) — Go 1.18+ generic tuple ☆`95`
*   [seiflotfy/count-min-log](https://github.com/seiflotfy/count-min-log) — Go implementation of Count-Min-Log ☆`69`
*   [s0rg/quadtree](https://github.com/s0rg/quadtree) — Generic, zero-alloc, 100%-test covered Quadtree for golang ☆`41`

### Pipes

*   [nazar256/parapipe](https://github.com/nazar256/parapipe) — Paralleling pipeline ☆`37`

### Queues

*   [hatchet-dev/hatchet](https://github.com/hatchet-dev/hatchet) — Run Background Tasks at Scale ☆`6,234`
*   [gammazero/deque](https://github.com/gammazero/deque) — Fast ring-buffer deque (double-ended queue) ☆`741`
*   [adrianbrad/queue](https://github.com/adrianbrad/queue) — Go package providing multiple queue implementations. Developed in a thread-safe generic way. ☆`322`
*   [embano1/memlog](https://github.com/embano1/memlog) — A Kafka log inspired in-memory and append-only data structure ☆`135`
*   [mikestefanello/backlite](https://github.com/mikestefanello/backlite) — Type-safe, persistent, embedded task queues and background job runner w/ SQLite. Web monitoring UI included. ☆`128`

### Sets

*   [deckarep/golang-set](https://github.com/deckarep/golang-set) — A simple, battle-tested and generic set type for the Go language. Trusted by GoogleCloudPlatform, Docker, 1Password, Ethereum and Hashicorp. ☆`4,618`
*   [StudioSol/set](https://github.com/StudioSol/set) — A simple Set data structure implementation in Go (Golang) using LinkedHashMap. ☆`29`

### Text Analysis

*   [blevesearch/bleve](https://github.com/blevesearch/bleve) — A modern text/numeric/geo-spatial/vector indexing library for go ☆`10,777`
*   [derekparker/trie](https://github.com/derekparker/trie) — Data structure and relevant algorithms for extremely fast prefix/fuzzy string searching. ☆`784`
*   [agnivade/levenshtein](https://github.com/agnivade/levenshtein) — Go implementation to calculate Levenshtein Distance. ☆`441`
*   [plar/go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) — Adaptive Radix Trees implemented in Go ☆`406`
*   [viant/ptrie](https://github.com/viant/ptrie) — A prefix tree implementation in go ☆`44`

### Trees

*   [bobg/merkle](https://github.com/bobg/merkle) — Merkle hash trees ☆`20`

## Database

### Caches

*   [golang/groupcache](https://github.com/golang/groupcache) — groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. ☆`13,281`
*   [dgraph-io/ristretto](https://github.com/dgraph-io/ristretto) — A high performance memory-bound Go cache ☆`6,587`
*   [eko/gocache](https://github.com/eko/gocache) — A complete Go cache library that brings you multiple ways of managing your caches ☆`2,800`
*   [bluele/gcache](https://github.com/bluele/gcache) — An in-memory cache library for golang. It supports multiple eviction policies: LRU, LFU, ARC ☆`2,722`
*   [maypok86/otter](https://github.com/maypok86/otter) — A high performance caching library for Go ☆`2,410`
*   [VictoriaMetrics/fastcache](https://github.com/VictoriaMetrics/fastcache) — Fast thread-safe inmemory cache for big number of entries in Go. Minimizes GC overhead ☆`2,299`
*   [viccon/sturdyc](https://github.com/viccon/sturdyc) — A caching library with advanced concurrency features designed to make I/O heavy applications robust and highly performant ☆`1,238`
*   [jellydator/ttlcache](https://github.com/jellydator/ttlcache) — An in-memory cache with item expiration and generics ☆`1,183`
*   [EchoVault/SugarDB](https://github.com/EchoVault/SugarDB) — Embeddable and distributed in-memory alternative to Redis. ☆`514`
*   [faabiosr/cachego](https://github.com/faabiosr/cachego) — Golang Cache component - Multiple drivers ☆`373`
*   [Yiling-J/theine-go](https://github.com/Yiling-J/theine-go) — high performance in-memory cache ☆`352`
*   [elastic/go-freelru](https://github.com/elastic/go-freelru) —  ☆`254`
*   [naughtygopher/pocache](https://github.com/naughtygopher/pocache) — Pocache is a minimal cache package which focuses on a preemptive optimistic caching strategy ☆`229`
*   [samber/hot](https://github.com/samber/hot) — In-memory caching library for read-intensive Go applications ☆`217`
*   [erni27/imcache](https://github.com/erni27/imcache) — A zero-dependency generic in-memory cache Go library ☆`123`
*   [OrlovEvgeny/go-mcache](https://github.com/OrlovEvgeny/go-mcache) — High-throughput, sharded in-memory KV cache for Go with minimal allocations ☆`100`
*   [zekroTJA/timedmap](https://github.com/zekroTJA/timedmap) — A thread safe map which has expiring key-value pairs. ☆`74`
*   [codingsince1985/couchcache](https://github.com/codingsince1985/couchcache) — A RESTful caching micro-service in Go backed by Couchbase ☆`66`
*   [mdaliyan/icache](https://github.com/mdaliyan/icache) — A High Performance, Generic, thread-safe, zero-dependency, key-value, in-memory cache ☆`23`

### Database Schema Migration

*   [golang-migrate/migrate](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`17,710`
*   [bytebase/bytebase](https://github.com/bytebase/bytebase) — World's most advanced database DevSecOps solution for Developer, Security, DBA and Platform Engineering teams. The GitHub/GitLab for database DevSecOps. ☆`13,348`
*   [pressly/goose](https://github.com/pressly/goose) — A database migration tool. Supports SQL migrations and Go functions. ☆`9,511`
*   [ariga/atlas](https://github.com/ariga/atlas) — Manage your database schema as code ☆`7,604`
*   [amacneil/dbmate](https://github.com/amacneil/dbmate) — A lightweight, framework-agnostic database migration tool. ☆`6,503`
*   [rubenv/sql-migrate](https://github.com/rubenv/sql-migrate) — SQL schema migration tool for Go. ☆`3,391`
*   [skeema/skeema](https://github.com/skeema/skeema) — Declarative pure-SQL schema management for MySQL and MariaDB ☆`1,340`
*   [go-gormigrate/gormigrate](https://github.com/go-gormigrate/gormigrate) — Minimalistic database migration helper for Gorm ORM ☆`1,138`
*   [linkedin/goavro](https://github.com/linkedin/goavro) — Goavro is a library that encodes and decodes Avro data. ☆`1,048`
*   [sunary/sqlize](https://github.com/sunary/sqlize) — powerful SQL toolkit; offering parsing, building, and migration capabilities. ☆`122`
*   [robinjoseph08/go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) — A Go package to help write migrations with go-pg/pg. ☆`86`
*   [adlio/schema](https://github.com/adlio/schema) — Embedded schema migration package for Go ☆`42`
*   [khezen/avro](https://github.com/khezen/avro) — Apache AVRO for go ☆`47`
*   [muir/libschema](https://github.com/muir/libschema) — database schema migrations on a per-library basis \[Go] ☆`17`

### Database Tools

*   [vitessio/vitess](https://github.com/vitessio/vitess) — Vitess is a database clustering system for horizontal scaling of MySQL. ☆`20,489`
*   [sosedoff/pgweb](https://github.com/sosedoff/pgweb) — Cross-platform client for PostgreSQL databases ☆`9,085`
*   [go-mysql-org/go-mysql](https://github.com/go-mysql-org/go-mysql) — a powerful mysql toolset with Go ☆`4,878`
*   [prest/prest](https://github.com/prest/prest) — PostgreSQL REST, low-code, simplify and accelerate development, instant, realtime, high-performance on any Postgres application, existing or new ☆`4,459`
*   [ContentSquare/chproxy](https://github.com/ContentSquare/chproxy) — Open-Source ClickHouse http proxy and load balancer ☆`1,415`
*   [cybertec-postgresql/pg\_timetable](https://github.com/cybertec-postgresql/pg_timetable) — pg\_timetable: Advanced scheduling for PostgreSQL ☆`1,237`
*   [liweiyi88/onedump](https://github.com/liweiyi88/onedump) — Effortless database administration tool ☆`765`
*   [HDT3213/rdb](https://github.com/HDT3213/rdb) — Golang implemented Redis RDB parser for secondary development and memory analysis ☆`581`
*   [nikepan/clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) — Collects many small inserts to ClickHouse and send in big inserts ☆`504`
*   [wesql/wescale](https://github.com/wesql/wescale) — WeScale is a Modern MySQL proxy that supports read-write-split, read-after-write-consistency, load balancing and OnlineDDL. ☆`311`
*   [gatewayd-io/gatewayd](https://github.com/gatewayd-io/gatewayd) — database gateway for building data-driven applications ☆`270`
*   [sj14/dbbench](https://github.com/sj14/dbbench) — dbbench is a simple database benchmarking tool which supports several databases and own scripts ☆`114`
*   [bartventer/gorm-multitenancy](https://github.com/bartventer/gorm-multitenancy) — Multi-tenancy support for GORM managed databases ☆`72`
*   [kazhuravlev/database-gateway](https://github.com/kazhuravlev/database-gateway) — Safe access to production databases ☆`29`
*   [codingconcepts/dg](https://github.com/codingconcepts/dg) — A fast data generator that produces CSV files from generated relational data ☆`43`

### Databases Implemented in Go

*   [prometheus/prometheus](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`61,436`
*   [milvus-io/milvus](https://github.com/milvus-io/milvus) — Milvus is a high-performance, cloud-native vector database built for scalable vector ANN search ☆`40,084`
*   [pingcap/tidb](https://github.com/pingcap/tidb) — TiDB - the open-source, cloud-native, distributed SQL database designed for modern applications. ☆`39,349`
*   [cockroachdb/cockroach](https://github.com/cockroachdb/cockroach) — CockroachDB — the cloud native, distributed SQL database designed for high availability, effortless scale, and control over data placement. ☆`31,500`
*   [influxdata/influxdb](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`30,865`
*   [dgraph-io/dgraph](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,360`
*   [dolthub/dolt](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`19,304`
*   [rqlite/rqlite](https://github.com/rqlite/rqlite) — The lightweight, user-friendly, fault-tolerant database built on SQLite. ☆`17,110`
*   [VictoriaMetrics/VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) — VictoriaMetrics: fast, cost-effective monitoring solution and time series database ☆`15,446`
*   [dgraph-io/badger](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,194`
*   [etcd-io/bbolt](https://github.com/etcd-io/bbolt) — An embedded key/value database for Go. ☆`9,221`
*   [codenotary/immudb](https://github.com/codenotary/immudb) — immudb - immutable database based on zero trust, SQL/Key-Value/Document model, tamperproof, data change history ☆`8,858`
*   [authzed/spicedb](https://github.com/authzed/spicedb) — Open Source, Google Zanzibar-inspired database for scalably storing and querying fine-grained authorization data ☆`6,212`
*   [cockroachdb/pebble](https://github.com/cockroachdb/pebble) — RocksDB/LevelDB inspired key-value database in Go ☆`5,621`
*   [rosedblabs/rosedb](https://github.com/rosedblabs/rosedb) — Lightweight, fast and reliable key/value storage engine based on Bitcask. ☆`4,870`
*   [tidwall/buntdb](https://github.com/tidwall/buntdb) — BuntDB is an embeddable, in-memory key/value database for Go with custom indexing and geospatial support ☆`4,803`
*   [nalgeon/redka](https://github.com/nalgeon/redka) — Redis re-implemented with SQL ☆`4,388`
*   [HDT3213/godis](https://github.com/HDT3213/godis) — A Golang implemented Redis Server and Cluster ☆`3,795`
*   [nutsdb/nutsdb](https://github.com/nutsdb/nutsdb) — A simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set. ☆`3,529`
*   [lindb/lindb](https://github.com/lindb/lindb) — LinDB is a scalable, high performance, high availability distributed time series database. ☆`3,043`
*   [lotusdblabs/lotusdb](https://github.com/lotusdblabs/lotusdb) — Most advanced key-value database written in Go, extremely fast, compatible with LSM tree and B+ tree. ☆`2,241`
*   [kelindar/column](https://github.com/kelindar/column) — High-performance, columnar, in-memory store with bitmap indexing in Go ☆`1,502`
*   [akrylysov/pogreb](https://github.com/akrylysov/pogreb) — Embedded key-value store for read-heavy workloads written in Go ☆`1,348`
*   [securitybunker/databunker](https://github.com/securitybunker/databunker) — Secure Vault for Customer PII/PHI/PCI/KYC Records ☆`1,347`
*   [objectbox/objectbox-go](https://github.com/objectbox/objectbox-go) — Embedded Go Database, the fast alternative to SQLite, gorm, etc. ☆`1,253`
*   [couchbase/moss](https://github.com/couchbase/moss) — moss - a simple, fast, ordered, persistable, key-val storage library for golang ☆`1,014`
*   [amit-davidson/LibraDB](https://github.com/amit-davidson/LibraDB) — LibraDB is a simple, persistent key/value store written in pure Go in less than 1000 lines for learning purposes. ☆`198`
*   [xgzlucario/rotom](https://github.com/xgzlucario/rotom) — A tiny Redis server built with Golang, compatible with RESP protocols. ☆`41`

### SQL Query Builders

*   [sqlc-dev/sqlc](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`16,366`
*   [Masterminds/squirrel](https://github.com/Masterminds/squirrel) — Fluent SQL generation for golang ☆`7,768`
*   [xo/dbtpl](https://github.com/xo/dbtpl) — Command line tool to generate idiomatic Go code for SQL databases supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server ☆`3,881`
*   [go-jet/jet](https://github.com/go-jet/jet) — Type safe SQL builder with code generation and automatic query result data mapping ☆`3,468`
*   [doug-martin/goqu](https://github.com/doug-martin/goqu) — SQL builder and query library for golang ☆`2,605`
*   [didi/gendry](https://github.com/didi/gendry) — a golang library for sql builder ☆`1,639`
*   [lqs/sqlingo](https://github.com/lqs/sqlingo) — A lightweight DSL & ORM which helps you to write SQL in Go. ☆`443`
*   [nullism/bqb](https://github.com/nullism/bqb) — BQB is a lightweight and easy to use query builder that works with sqlite, mysql, mariadb, postgres, and others. ☆`180`
*   [arthurkushman/buildsqlx](https://github.com/arthurkushman/buildsqlx) — Go database query builder library for PostgreSQL ☆`183`
*   [galeone/igor](https://github.com/galeone/igor) — igor is an abstraction layer for PostgreSQL with a gorm like syntax. ☆`126`
*   [cristalhq/builq](https://github.com/cristalhq/builq) — Easily build SQL queries in Go. ☆`95`
*   [HnH/qry](https://github.com/HnH/qry) — Write your SQL queries in raw files with all benefits of modern IDEs, use them in an easy way inside your application with all the profit of compile time constants ☆`35`
*   [JiveGroup/FluentSQL](https://github.com/JiveGroup/FluentSQL) — Fluent SQL - flexible and powerful SQL string builder ☆`18`
*   [motrboat/hotcoal](https://github.com/motrboat/hotcoal) — Hotcoal - Secure your handcrafted SQL against injection ☆`23`

## Database Drivers

### Interfaces to Multiple Backends

*   [philippgille/gokv](https://github.com/philippgille/gokv) — Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more) ☆`817`
*   [avito-tech/go-transaction-manager](https://github.com/avito-tech/go-transaction-manager) — Transaction manager for GoLang ☆`361`
*   [viant/dsc](https://github.com/viant/dsc) — Datastore Connectivity in go ☆`35`
*   [fogfish/dynamo](https://github.com/fogfish/dynamo) — Generic Golang Key/Value trait for AWS storage services ☆`22`

### NoSQL Database Drivers

*   [redis/go-redis](https://github.com/redis/go-redis) — Redis Go client ☆`21,692`
*   [gomodule/redigo](https://github.com/gomodule/redigo) — Go client for Redis ☆`9,877`
*   [mongodb/mongo-go-driver](https://github.com/mongodb/mongo-go-driver) — The Official Golang driver for MongoDB ☆`8,477`
*   [bradfitz/gomemcache](https://github.com/bradfitz/gomemcache) — Go Memcached client library #golang ☆`1,856`
*   [qiniu/qmgo](https://github.com/qiniu/qmgo) — Qmgo - The Go driver for MongoDB. It‘s based on official mongo-go-driver but easier to use like Mgo. ☆`1,340`
*   [Kamva/mgm](https://github.com/Kamva/mgm) — Mongo Go Models (mgm) is a fast and simple MongoDB ODM for Go (based on official Mongo Go Driver) ☆`765`
*   [aerospike/aerospike-client-go](https://github.com/aerospike/aerospike-client-go) — Aerospike Client Go ☆`454`
*   [couchbase/gocb](https://github.com/couchbase/gocb) — The Couchbase Go SDK ☆`373`
*   [couchbase/go-couchbase](https://github.com/couchbase/go-couchbase) — Couchbase client in Go ☆`324`
*   [go-kivik/kivik](https://github.com/go-kivik/kivik) — Common interface to CouchDB or CouchDB-like databases for Go and GopherJS ☆`331`
*   [nitishm/go-rejson](https://github.com/nitishm/go-rejson) — Golang client for redislabs' ReJSON module with support for multilple redis clients (redigo, go-redis) ☆`345`
*   [chenmingyong0423/go-mongox](https://github.com/chenmingyong0423/go-mongox) — A Go Mongo library based on the official MongoDB driver, featuring streamlined document operations, generic binding of structs to collections, built-in BSON doc builder, automated field updates, struct validation, hooks, and plugin-based programming. ☆`215`
*   [aliexpressru/gomemcached](https://github.com/aliexpressru/gomemcached) — A Binary Memcached client for Go with support for sharding using consistent hashing, along with SASL. ☆`21`
*   [btnguyen2k/gocosmos](https://github.com/btnguyen2k/gocosmos) — Go database/sql driver for Azure Cosmos DB SQL API ☆`22`

### Relational Database Drivers

*   [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) — Go MySQL Driver is a MySQL driver for Go's (golang) database/sql package ☆`15,294`
*   [jackc/pgx](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`12,885`
*   [denisenkom/go-mssqldb](https://github.com/denisenkom/go-mssqldb) — Microsoft SQL server driver written in go language ☆`1,867`
*   [ncruces/go-sqlite3](https://github.com/ncruces/go-sqlite3) — Go bindings to SQLite using wazero ☆`861`
*   [godror/godror](https://github.com/godror/godror) — GO DRiver for ORacle DB ☆`574`
*   [cvilsmeier/sqinn-go](https://github.com/cvilsmeier/sqinn-go) — Golang SQLite without cgo ☆`505`
*   [VinGarcia/ksql](https://github.com/VinGarcia/ksql) — A Simple and Powerful Golang SQL Library ☆`348`
*   [surrealdb/surrealdb.go](https://github.com/surrealdb/surrealdb.go) — SurrealDB SDK for Golang ☆`295`
*   [nakagami/firebirdsql](https://github.com/nakagami/firebirdsql) — Firebird RDBMS sql driver for Go (golang) ☆`252`
*   [ydb-platform/ydb-go-sdk](https://github.com/ydb-platform/ydb-go-sdk) — Pure Go native and database/sql driver for YDB ☆`174`
*   [rqlite/gorqlite](https://github.com/rqlite/gorqlite) — A Go client for rqlite, the distributed database built on SQLite ☆`174`
*   [apache/calcite-avatica-go](https://github.com/apache/calcite-avatica-go) — Apache Calcite Go ☆`123`
*   [viant/bgc](https://github.com/viant/bgc) — Datastore Connectivity for BigQuery in go ☆`21`

### Search and Analytic Databases

*   [elastic/go-elasticsearch](https://github.com/elastic/go-elasticsearch) — The official Go client for Elasticsearch ☆`5,989`
*   [ClickHouse/clickhouse-go](https://github.com/ClickHouse/clickhouse-go) — Golang driver for ClickHouse ☆`3,200`
*   [sourcegraph/zoekt](https://github.com/sourcegraph/zoekt) — Fast trigram based code search ☆`1,164`
*   [sdqri/effdsl](https://github.com/sdqri/effdsl) — Elasticsearch query builder for golang ☆`34`

## Date and Time

*   [dromara/carbon](https://github.com/dromara/carbon) — A simple, semantic and developer-friendly time package for golang ☆`5,179`
*   [araddon/dateparse](https://github.com/araddon/dateparse) — GoLang Parse many date strings without knowing format in advance. ☆`2,124`
*   [yaa110/go-persian-calendar](https://github.com/yaa110/go-persian-calendar) — The implementation of Persian (Solar Hijri) Calendar in Go ☆`235`
*   [bykof/gostradamus](https://github.com/bykof/gostradamus) — Gostradamus: Better DateTimes for Go ☆`211`
*   [relvacode/iso8601](https://github.com/relvacode/iso8601) — A fast ISO8601 date parser for Go ☆`156`
*   [nathan-osman/go-sunrise](https://github.com/nathan-osman/go-sunrise) — Go package for calculating the sunrise and sunset times for a given location ☆`171`
*   [rickb777/date](https://github.com/rickb777/date) — A Go package for working with dates ☆`138`

## Distributed Systems

*   [zeromicro/go-zero](https://github.com/zeromicro/go-zero) — A cloud-native Go microservices framework with cli tool for productivity. ☆`32,159`
*   [go-kit/kit](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,526`
*   [go-kratos/kratos](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,111`
*   [grpc/grpc-go](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,547`
*   [micro/go-micro](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,615`
*   [nats-io/nats-server](https://github.com/nats-io/nats-server) — High-Performance server for NATS.io, the cloud and edge native messaging system. ☆`18,631`
*   [hashicorp/raft](https://github.com/hashicorp/raft) — Golang implementation of the Raft consensus protocol ☆`8,836`
*   [smallnest/rpcx](https://github.com/smallnest/rpcx) — Best microservices framework in Go, like alibaba Dubbo, but with more features, Scale easily ☆`8,264`
*   [cloudwego/kitex](https://github.com/cloudwego/kitex) — Go RPC framework with high-performance and strong-extensibility for building micro-services. ☆`7,742`
*   [luraproject/lura](https://github.com/luraproject/lura) — Ultra performant API Gateway with middlewares. A project hosted at The Linux Foundation ☆`6,692`
*   [anacrolix/torrent](https://github.com/anacrolix/torrent) — Full-featured BitTorrent client package and utilities ☆`5,901`
*   [lni/dragonboat](https://github.com/lni/dragonboat) — A feature complete and high performance multi-group Raft library in Go. ☆`5,265`
*   [emitter-io/emitter](https://github.com/emitter-io/emitter) — High performance, distributed and low latency publish-subscribe platform. ☆`3,986`
*   [chrislusf/gleam](https://github.com/chrislusf/gleam) — Fast, efficient, and scalable distributed map/reduce system, DAG execution, in memory or on disk, written in pure Go, runs standalone or distributedly. ☆`3,547`
*   [dragonflyoss/dragonfly](https://github.com/dragonflyoss/dragonfly) — Delivers efficient, stable, and secure data distribution and acceleration powered by P2P technology, with an optional content‑addressable filesystem that accelerates OCI container launch. ☆`2,907`
*   [go-dev-frame/sponge](https://github.com/go-dev-frame/sponge) — A powerful and easy-to-use Go development framework that enables you to effortlessly build stable, reliable, and high-performance backend services with a "low-code" approach. ☆`2,662`
*   [go-eagle/eagle](https://github.com/go-eagle/eagle) — A Go framework for the API or Microservice ☆`2,397`
*   [mochi-mqtt/server](https://github.com/mochi-mqtt/server) — The fully compliant, embeddable high-performance Go MQTT v5 server for IoT, smarthome, and pubsub ☆`1,703`
*   [bsm/redislock](https://github.com/bsm/redislock) — Simplified distributed locking implementation using Redis ☆`1,709`
*   [hprose/hprose-golang](https://github.com/hprose/hprose-golang) — Hprose is a cross-language RPC. This project is Hprose for Golang. ☆`1,261`
*   [unionj-cloud/go-doudou](https://github.com/unionj-cloud/go-doudou) — go-doudou（doudou pronounce /dəudəu/）is OpenAPI 3.0 (for REST) spec and Protobuf v3 (for grpc) based lightweight microservice framework. It supports monolith service application as well. ☆`1,208`
*   [k8gb-io/k8gb](https://github.com/k8gb-io/k8gb) — A cloud native Kubernetes Global Balancer ☆`1,118`
*   [cenkalti/rain](https://github.com/cenkalti/rain) — BitTorrent client and library in Go ☆`1,089`
*   [lesismal/arpc](https://github.com/lesismal/arpc) — More effective network communication, two-way calling, notify and broadcast supported. ☆`1,080`
*   [trpc-group/trpc-go](https://github.com/trpc-group/trpc-go) — A pluggable, high-performance RPC framework written in golang ☆`1,070`
*   [etcd-io/raft](https://github.com/etcd-io/raft) — Raft library for maintaining a replicated state machine ☆`949`
*   [temporalio/sdk-go](https://github.com/temporalio/sdk-go) — Temporal Go SDK ☆`765`
*   [AppsFlyer/go-sundheit](https://github.com/AppsFlyer/go-sundheit) — A library built to provide support for defining service health for golang services. It allows you to register async health checks for your dependencies and the service itself, provides a health endpoint that exposes their status, and health metrics. ☆`559`
*   [ybbus/jsonrpc](https://github.com/ybbus/jsonrpc) — A simple go implementation of json rpc 2.0 client over http ☆`362`
*   [anacrolix/dht](https://github.com/anacrolix/dht) — dht is used by anacrolix/torrent, and is intended for use as a library in other projects both torrent related and otherwise ☆`345`
*   [tarmac-project/tarmac](https://github.com/tarmac-project/tarmac) — Write as Functions, Deploy as a Monolith or Microservice with WebAssembly ☆`339`
*   [osamingo/jsonrpc](https://github.com/osamingo/jsonrpc) — The jsonrpc package helps implement of JSON-RPC 2.0 ☆`191`
*   [italolelis/outboxer](https://github.com/italolelis/outboxer) — A library that implements the outboxer pattern in go ☆`164`
*   [capillariesio/capillaries](https://github.com/capillariesio/capillaries) — Distributed batch data processing framework ☆`69`
*   [svcavallar/celeriac.v1](https://github.com/svcavallar/celeriac.v1) — Golang client library for adding support for interacting and monitoring Celery workers, tasks and events. ☆`76`
*   [sanketplus/go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) — MySQL Backed Locking Primitive ☆`65`
*   [vadiminshakov/committer](https://github.com/vadiminshakov/committer) — Two-phase (2PC) and three-phase (3PC) protocols implementaion in Golang ☆`40`
*   [pdupub/go-pdu](https://github.com/pdupub/go-pdu) — An PDU implementation in Go ☆`49`
*   [mbrostami/consistenthash](https://github.com/mbrostami/consistenthash) — A Go library that implements Consistent Hashing (+Block Partitioning) ☆`30`
*   [gmsec/micro](https://github.com/gmsec/micro) — A Go distributed systems development framework ☆`25`

## Dynamic DNS

*   [TimothyYe/godns](https://github.com/TimothyYe/godns) — A dynamic DNS client tool that supports AliDNS, Cloudflare, Google Domains, DNSPod, HE.net & DuckDNS & DreamHost, etc, written in Go. ☆`1,705`
*   [skibish/ddns](https://github.com/skibish/ddns) — Personal DDNS client with Digital Ocean Networking DNS as backend. ☆`266`

## Editor Plugins

*   [fatih/vim-go](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,211`
*   [nsf/gocode](https://github.com/nsf/gocode) — An autocompletion daemon for the Go programming language ☆`5,000`
*   [golang/vscode-go](https://github.com/golang/vscode-go) — Go extension for Visual Studio Code ☆`4,150`
*   [dominikh/go-mode.el](https://github.com/dominikh/go-mode.el) — Emacs mode for the Go programming language ☆`1,443`
*   [incu6us/goimports-reviser](https://github.com/incu6us/goimports-reviser) — Right imports sorting & code formatting tool (goimports alternative) ☆`702`

## Email

*   [axllent/mailpit](https://github.com/axllent/mailpit) — An email and SMTP testing tool with API for developers ☆`8,154`
*   [foxcpp/maddy](https://github.com/foxcpp/maddy) — Composable all-in-one mail server. ☆`5,742`
*   [mjl-/mox](https://github.com/mjl-/mox) — modern full-featured open source secure mail server for low-maintenance self-hosted email ☆`5,277`
*   [matcornic/hermes](https://github.com/matcornic/hermes) — Golang package that generates clean, responsive HTML e-mails for sending transactional mail ☆`2,988`
*   [AfterShip/email-verifier](https://github.com/AfterShip/email-verifier) — A Go library for email verification without sending any emails. ☆`1,467`
*   [wneessen/go-mail](https://github.com/wneessen/go-mail) — Easy to use, yet comprehensive library for sending mails with Go ☆`1,188`
*   [sendgrid/sendgrid-go](https://github.com/sendgrid/sendgrid-go) — The Official Twilio SendGrid Golang API Library ☆`1,040`
*   [mailgun/mailgun-go](https://github.com/mailgun/mailgun-go) — Go library for sending mail with the Mailgun API. ☆`741`
*   [xhit/go-simple-mail](https://github.com/xhit/go-simple-mail) — Golang package for send email. Support keep alive connection, TLS and SSL. Easy for bulk SMTP. ☆`686`
*   [emersion/go-message](https://github.com/emersion/go-message) — A streaming Go library for the Internet Message Format and mail messages ☆`429`
*   [vanng822/go-premailer](https://github.com/vanng822/go-premailer) — Inline styling for html mail in golang ☆`177`
*   [mocktools/go-smtp-mock](https://github.com/mocktools/go-smtp-mock) — SMTP mock server written on Golang. Mimic any SMTP server behavior for your test environment with fake SMTP server. ☆`157`
*   [truemail-rb/truemail-go](https://github.com/truemail-rb/truemail-go) — Configurable Golang email validator/verifier. Verify email via Regex, DNS, SMTP and even more. Be sure that email address valid and exists. ☆`129`
*   [toorop/go-dkim](https://github.com/toorop/go-dkim) — DKIM package for golang ☆`99`
*   [dimuska139/go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) — Golang library for providing a canonical representation of email address. ☆`76`
*   [valord577/mailx](https://github.com/valord577/mailx) — A library that makes it easier to send email via SMTP. ☆`20`

## Embeddable Scripting Languages

*   [php/frankenphp](https://github.com/php/frankenphp) — The modern PHP app server ☆`10,458`
*   [expr-lang/expr](https://github.com/expr-lang/expr) — Expression language and expression evaluation for Go ☆`7,441`
*   [yuin/gopher-lua](https://github.com/yuin/gopher-lua) — GopherLua: VM and compiler for Lua in Go ☆`6,789`
*   [dop251/goja](https://github.com/dop251/goja) — ECMAScript/JavaScript engine in pure Go ☆`6,585`
*   [d5/tengo](https://github.com/d5/tengo) — A fast script language for Go ☆`3,740`
*   [Shopify/go-lua](https://github.com/Shopify/go-lua) — A Lua VM in Go ☆`3,363`
*   [google/cel-go](https://github.com/google/cel-go) — Fast, portable, non-Turing complete expression evaluation with gradual typing (Go) ☆`2,779`
*   [google/starlark-go](https://github.com/google/starlark-go) — Starlark in Go: the Starlark configuration language, implemented in Go ☆`2,568`
*   [metacall/core](https://github.com/metacall/core) — MetaCall: The ultimate polyglot programming experience. ☆`1,736`
*   [wa-lang/wa](https://github.com/wa-lang/wa) — The Wa Programming Language ☆`1,740`
*   [mattn/anko](https://github.com/mattn/anko) — Scriptable interpreter written in golang ☆`1,545`
*   [PaesslerAG/gval](https://github.com/PaesslerAG/gval) — Expression evaluation in golang ☆`808`
*   [ichiban/prolog](https://github.com/ichiban/prolog) — The only reasonable scripting engine for Go. ☆`694`
*   [aarzilli/golua](https://github.com/aarzilli/golua) — Go bindings for Lua C API - in progress ☆`685`
*   [1set/starlet](https://github.com/1set/starlet) — Yet another Go wrapper for Starlark that simplifies usage, offers data conversion and useful Starlark libraries ☆`40`

## Error Handling

*   [hashicorp/go-multierror](https://github.com/hashicorp/go-multierror) — A Go (golang) package for representing a list of errors as a single error. ☆`2,536`
*   [cockroachdb/errors](https://github.com/cockroachdb/errors) — Go error library with error portability over the network ☆`2,321`
*   [rotisserie/eris](https://github.com/rotisserie/eris) — Error handling library with readable stack traces and flexible formatting support ☆`1,733`
*   [joomcode/errorx](https://github.com/joomcode/errorx) — A comprehensive error handling library for Go ☆`1,266`
*   [ztrue/tracerr](https://github.com/ztrue/tracerr) — Golang errors with stack trace and source fragments. ☆`1,101`
*   [samber/oops](https://github.com/samber/oops) — Error handling library with context, assertion, stack trace and source fragments ☆`805`
*   [Southclaws/fault](https://github.com/Southclaws/fault) — Go errors but structured and composable. Fault provides an extensible yet ergonomic mechanism for wrapping errors. ☆`302`

## File Handling

*   [pdfcpu/pdfcpu](https://github.com/pdfcpu/pdfcpu) — A PDF processor written in Go. ☆`8,261`
*   [spf13/afero](https://github.com/spf13/afero) — The Universal Filesystem Abstraction for Go ☆`6,459`
*   [dundee/gdu](https://github.com/dundee/gdu) — Fast disk usage analyzer with console interface written in Go ☆`5,001`
*   [SebastiaanKlippert/go-wkhtmltopdf](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) — Golang commandline wrapper for wkhtmltopdf ☆`1,160`
*   [otiai10/copy](https://github.com/otiai10/copy) — Go copy directory recursively ☆`769`
*   [no-src/gofs](https://github.com/no-src/gofs) — A cross-platform real-time file synchronization tool out of the box based on Golang ☆`519`
*   [viant/afs](https://github.com/viant/afs) — Abstract File Storage ☆`357`
*   [C2FO/vfs](https://github.com/C2FO/vfs) — Pluggable, extensible virtual file system for Go ☆`354`
*   [barasher/go-exiftool](https://github.com/barasher/go-exiftool) — Golang wrapper for Exiftool : extract as much metadata as possible (EXIF, ...) from files (pictures, pdf, office documents, ...) ☆`285`
*   [kdomanski/iso9660](https://github.com/kdomanski/iso9660) — A go library for reading and creating ISO9660 images ☆`282`
*   [artonge/go-csv-tag](https://github.com/artonge/go-csv-tag) — Read csv file from go using tags ☆`128`
*   [charlievieth/fastwalk](https://github.com/charlievieth/fastwalk) — Fast directory traversal for Golang ☆`110`
*   [parsyl/parquet](https://github.com/parsyl/parquet) — A library for reading and writing parquet files. ☆`126`
*   [codingsince1985/checksum](https://github.com/codingsince1985/checksum) — Compute message digest for large files in Go ☆`113`
*   [qmuntal/opc](https://github.com/qmuntal/opc) — Go implementation of the Open Packaging Conventions (OPC) ☆`77`
*   [adelowo/gulter](https://github.com/adelowo/gulter) — Golang middleware for handling multipart/form-data and uploading files ☆`66`

## Financial

*   [shopspring/decimal](https://github.com/shopspring/decimal) — Arbitrary-precision fixed-point decimal numbers in Go ☆`7,053`
*   [achannarasappa/ticker](https://github.com/achannarasappa/ticker) — Track stocks, crypto, and derivatives prices and positions in real time from your terminal ☆`5,817`
*   [Rhymond/go-money](https://github.com/Rhymond/go-money) — Go implementation of Fowler's Money pattern ☆`1,825`
*   [c9s/bbgo](https://github.com/c9s/bbgo) — The modern cryptocurrency trading bot framework written in Go. ☆`1,569`
*   [formancehq/ledger](https://github.com/formancehq/ledger) — The programmable open source core ledger for fintech ☆`1,077`
*   [bojanz/currency](https://github.com/bojanz/currency) — Currency handling for Go. ☆`607`
*   [moov-io/ach](https://github.com/moov-io/ach) — ACH implements a reader, writer, and validator for Automated Clearing House (ACH) files. The HTTP server is available in a Docker image and the Go package is available. ☆`516`
*   [invopop/gobl](https://github.com/invopop/gobl) — Go Business Language ☆`227`
*   [govalues/decimal](https://github.com/govalues/decimal) — Correctly rounded decimals for Go ☆`203`
*   [quagmt/udecimal](https://github.com/quagmt/udecimal) — A high-performance, high precision, zero allocation fixed-point decimal library for financial applications ☆`161`
*   [claygod/transaction](https://github.com/claygod/transaction) — Embedded database for accounts transactions. ☆`138`
*   [jovandeginste/payme](https://github.com/jovandeginste/payme) — QR code generator (ASCII & PNG) for SEPA payments ☆`88`
*   [jokruger/dec128](https://github.com/jokruger/dec128) — High performance 128-bit fixed-point decimal numbers in go. ☆`35`
*   [govalues/money](https://github.com/govalues/money) — Correctly rounded monetary amounts and exchange rates for Go ☆`44`
*   [nikolaydubina/fpmoney](https://github.com/nikolaydubina/fpmoney) — Fixed-Point Decimal Money ☆`34`
*   [nikolaydubina/fpdecimal](https://github.com/nikolaydubina/fpdecimal) — Fixed-Point Decimals ☆`33`

## Forms

*   [justinas/nosurf](https://github.com/justinas/nosurf) — CSRF protection middleware for Go. ☆`1,710`
*   [gorilla/csrf](https://github.com/gorilla/csrf) — Package gorilla/csrf provides Cross Site Request Forgery (CSRF) prevention middleware for Go web applications & services ☆`1,163`
*   [go-playground/form](https://github.com/go-playground/form) — Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. ☆`883`
*   [ggicci/httpin](https://github.com/ggicci/httpin) — HTTP Input for Go - HTTP Request from/to Go Struct (Bi-directional Data Binding between Go Struct and http.Request) ☆`378`
*   [sonh/qs](https://github.com/sonh/qs) — Go module for encoding structs into URL query parameters ☆`79`
*   [cinar/checker](https://github.com/cinar/checker) — Effortless input validation in Go with the power of struct tags. No dependencies, just pure simplicity. See how! ☆`47`

## Functional

*   [samber/mo](https://github.com/samber/mo) — Monads and popular FP abstractions, powered by Go 1.18+ Generics (Option, Result, Either...) ☆`3,216`
*   [BooleanCat/go-functional](https://github.com/BooleanCat/go-functional) — go-functional is a library of iterators to augment the standard library ☆`519`
*   [seborama/fuego](https://github.com/seborama/fuego) — Functional Experiment in Golang ☆`146`
*   [rjNemo/underscore](https://github.com/rjNemo/underscore) — Useful functional programming helpers for Go ☆`118`

## Game Development

*   [hajimehoshi/ebiten](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`12,682`
*   [topfreegames/pitaya](https://github.com/topfreegames/pitaya) — Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. ☆`2,684`
*   [xiaonanln/goworld](https://github.com/xiaonanln/goworld) — Scalable Distributed Game Server Engine with Hot Swapping in Golang ☆`2,689`
*   [gen2brain/raylib-go](https://github.com/gen2brain/raylib-go) — Go bindings for raylib, a simple and easy-to-use library to enjoy videogames programming. ☆`2,244`
*   [oakmound/oak](https://github.com/oakmound/oak) — A pure Go game engine ☆`1,645`
*   [JoelOtter/termloop](https://github.com/JoelOtter/termloop) — Terminal-based game engine for Go, built on top of Termbox ☆`1,467`
*   [xtaci/gonet](https://github.com/xtaci/gonet) — A Game Server Skeleton in golang. ☆`1,285`
*   [gopxl/pixel](https://github.com/gopxl/pixel) — A hand-crafted 2D game library in Go. ☆`362`
*   [ungerik/go3d](https://github.com/ungerik/go3d) — A performance oriented 2D/3D math package for Go ☆`330`
*   [kelindar/tile](https://github.com/kelindar/tile) — Tile is a 2D grid engine, built with data and cache friendly ways, includes pathfinding and observers. ☆`208`
*   [mlange-42/ark](https://github.com/mlange-42/ark) — Ark -- Archetype-based Entity Component System (ECS) for Go. ☆`183`
*   [andygeiss/ecs](https://github.com/andygeiss/ecs) — Build your own Game-Engine based on the Entity Component System concept in Golang. ☆`167`
*   [gonutz/prototype](https://github.com/gonutz/prototype) — Simple 2D game prototyping framework targetting Windows, Mac, Linux, WASM. ☆`108`
*   [s0rg/fantasyname](https://github.com/s0rg/fantasyname) — RinkWorks fantasy name generator for golang ☆`39`
*   [s0rg/grid](https://github.com/s0rg/grid) — Generic 2D grid ☆`25`

## Generators

*   [oapi-codegen/oapi-codegen](https://github.com/oapi-codegen/oapi-codegen) — Generate Go client and server boilerplate from OpenAPI 3 specifications ☆`7,817`
*   [dave/jennifer](https://github.com/dave/jennifer) — Jennifer is a code generator for Go ☆`3,578`
*   [hexdigest/gowrap](https://github.com/hexdigest/gowrap) — GoWrap is a command line tool for generating decorators for Go interfaces ☆`1,288`
*   [awalterschulze/goderive](https://github.com/awalterschulze/goderive) — Derives and generates mundane golang functions that you do not want to maintain yourself ☆`1,272`
*   [abice/go-enum](https://github.com/abice/go-enum) — An enum generator for go ☆`894`
*   [jmattheis/goverter](https://github.com/jmattheis/goverter) — Generate type-safe Go converters by defining function signatures. ☆`786`
*   [rjeczalik/interfaces](https://github.com/rjeczalik/interfaces) — Code generation tools for Go. ☆`431`
*   [switchupcb/copygen](https://github.com/switchupcb/copygen) — Copygen generates code based on Go types. Generate type-based code to copy values from type to type and fields from struct to struct by default (copier without reflection). ☆`398`
*   [reedom/convergen](https://github.com/reedom/convergen) — A type-to-type copy function code generator. ☆`48`

## Geographic

*   [tidwall/tile38](https://github.com/tidwall/tile38) — Real-time Geospatial and Geofencing ☆`9,528`
*   [golang/geo](https://github.com/golang/geo) — S2 geometry library in Go ☆`1,803`
*   [consbio/mbtileserver](https://github.com/consbio/mbtileserver) — Basic Go server for mbtiles ☆`759`
*   [spatial-go/geoos](https://github.com/spatial-go/geoos) — A library provides spatial data and geometric algorithms ☆`526`
*   [paulmach/osm](https://github.com/paulmach/osm) — General purpose library for reading, writing and working with OpenStreetMap data ☆`432`
*   [uber/h3-go](https://github.com/uber/h3-go) — Go bindings for H3, a hierarchical hexagonal geospatial indexing system ☆`381`
*   [peterstace/simplefeatures](https://github.com/peterstace/simplefeatures) — Simple Features is a pure Go Implementation of the OpenGIS Simple Feature Access Specification ☆`161`
*   [airbusgeo/godal](https://github.com/airbusgeo/godal) — golang wrapper for github.com/OSGEO/gdal ☆`173`
*   [wroge/wgs84](https://github.com/wroge/wgs84) — A zero-dependency Go package for coordinate transformations. ☆`140`
*   [pantrif/s2-geojson](https://github.com/pantrif/s2-geojson) — Draw a polygon on the map or paste a geoJSON and explore how the s2.RegionCoverer covers it with S2 cells depending on the min and max levels ☆`36`

## Go Compilers

*   [gopherjs/gopherjs](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,071`
*   [yassinebenaid/bunster](https://github.com/yassinebenaid/bunster) — Compile shell scripts to static binaries. ☆`2,610`
*   [Konstantin8105/c4go](https://github.com/Konstantin8105/c4go) — Transpiling C code to Go code ☆`376`
*   [go2hx/go2hx](https://github.com/go2hx/go2hx) — Import Go libraries in your Haxe projects Go -> Haxe source-to-source compiler ☆`143`

## Go Generate Tools

*   [xuri/xgen](https://github.com/xuri/xgen) — XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator ☆`399`
*   [kazhuravlev/options-gen](https://github.com/kazhuravlev/options-gen) — Codegen for functional options in go projects ☆`103`
*   [g4s8/envdoc](https://github.com/g4s8/envdoc) — Go tool to generate documentation for environment variables ☆`93`

## Go Tools

*   [go-swagger/go-swagger](https://github.com/go-swagger/go-swagger) — Swagger 2.0 implementation for go ☆`9,881`
*   [ondrajz/go-callvis](https://github.com/ondrajz/go-callvis) — Visualize call graph of a Go program using Graphviz ☆`6,418`
*   [Zxilly/go-size-analyzer](https://github.com/Zxilly/go-size-analyzer) — A tool for analyzing the size of compiled Go binaries, offering cross-platform support, detailed breakdowns, and multiple output formats. ☆`1,696`
*   [safedep/vet](https://github.com/safedep/vet) — Protect against malicious open source packages ☆`846`
*   [iyashjayesh/monigo](https://github.com/iyashjayesh/monigo) — MoniGo is a performance monitoring library for Go apps, offering real-time insights into service-level and function-level metrics. With an intuitive UI, it enables developers to track and optimize performance. Get your Go app's dashboard up in just 10 seconds! ☆`380`
*   [becheran/roumon](https://github.com/becheran/roumon) — Universal goroutine monitor using pprof and termui ☆`221`
*   [bitfield/gotestdox](https://github.com/bitfield/gotestdox) — A tool for formatting Go test results as readable documentation ☆`172`
*   [ahmedakef/gotutor](https://github.com/ahmedakef/gotutor) — Online Go Debugger & Visualizer ☆`72`
*   [bobg/decouple](https://github.com/bobg/decouple) — find overspecified function parameters in Go code ☆`31`
*   [bobg/modver](https://github.com/bobg/modver) — a tool that helps you obey semantic versioning rules in your Go module ☆`21`
*   [dustinblackman/gomodrun](https://github.com/dustinblackman/gomodrun) — The forgotten go tool that executes and caches binaries included in go.mod files. ☆`38`

## Goroutines

*   [panjf2000/ants](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,152`
*   [benmanns/goworker](https://github.com/benmanns/goworker) — goworker is a Go-based background worker that runs 10 to 100,000\* times faster than Ruby-based workers. ☆`2,844`
*   [alitto/pond](https://github.com/alitto/pond) — Minimalistic and High-performance goroutine worker pool written in Go ☆`2,024`
*   [destel/rill](https://github.com/destel/rill) — Go toolkit for clean, composable, channel-based concurrency ☆`1,793`
*   [xxjwxc/gowp](https://github.com/xxjwxc/gowp) — golang worker pool , Concurrency limiting goroutine pool ☆`524`
*   [earthboundkid/flowmatic](https://github.com/earthboundkid/flowmatic) — Structured concurrency made easy ☆`394`
*   [timandy/routine](https://github.com/timandy/routine) — ThreadLocal for Golang. ☆`277`
*   [vladopajic/go-actor](https://github.com/vladopajic/go-actor) — A lightweight library for writing concurrent programs in Go using the Actor model. ☆`265`
*   [reugn/async](https://github.com/reugn/async) — Synchronization and asynchronous computation package for Go ☆`280`
*   [mborders/artifex](https://github.com/mborders/artifex) — Simple in-memory job queue for Golang using worker-based dispatching ☆`213`

## GUI

*   [fyne-io/fyne](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`27,511`
*   [webview/webview](https://github.com/webview/webview) — Tiny cross-platform webview library for C/C++. Uses WebKit (GTK/Cocoa) and Edge WebView2 (Windows). ☆`13,616`
*   [therecipe/qt](https://github.com/therecipe/qt) — Qt binding for Go (Golang) with support for Windows / macOS / Linux / FreeBSD / Android / iOS / Sailfish OS / Raspberry Pi / AsteroidOS / Ubuntu Touch / JavaScript / WebAssembly ☆`10,761`
*   [go-vgo/robotgo](https://github.com/go-vgo/robotgo) — RobotGo, Go Native cross-platform RPA and GUI automation @vcaesar ☆`10,446`
*   [maxence-charriere/go-app](https://github.com/maxence-charriere/go-app) — A package to build progressive web apps with Go programming language and WebAssembly. ☆`8,822`
*   [lxn/walk](https://github.com/lxn/walk) — A Windows GUI toolkit for the Go Programming Language ☆`7,038`
*   [progrium/darwinkit](https://github.com/progrium/darwinkit) — Native Mac APIs for Go. Previously known as MacDriver ☆`5,357`
*   [getlantern/systray](https://github.com/getlantern/systray) — a cross platfrom Go library to place an icon and menu in the notification area ☆`3,618`
*   [cogentcore/core](https://github.com/cogentcore/core) — A free and open source framework for building powerful, fast, elegant 2D and 3D apps that run on macOS, Windows, Linux, iOS, Android, and web with a single Go codebase, allowing you to Code Once, Run Everywhere. ☆`2,271`
*   [gotk3/gotk3](https://github.com/gotk3/gotk3) — Go bindings for GTK3 ☆`2,203`
*   [roblillack/spot](https://github.com/roblillack/spot) — React-like desktop GUI toolkit for Go ☆`1,249`
*   [ncruces/zenity](https://github.com/ncruces/zenity) — Zenity dialogs for Golang, Windows, macOS ☆`872`
*   [energye/energy](https://github.com/energye/energy) — Energy is a framework developed by Go language based on CEF (Chromium Embedded Framework) for developing cross-platform desktop applications for Windows, Mac OS X, and Linux ☆`551`
*   [AllenDang/cimgui-go](https://github.com/AllenDang/cimgui-go) — Auto generated Go wrapper for Dear ImGui via cimgui ☆`472`
*   [richardwilkes/unison](https://github.com/richardwilkes/unison) — A unified graphical user experience toolkit for Go desktop applications ☆`304`
*   [shurcooL/trayhost](https://github.com/shurcooL/trayhost) — Cross-platform Go library to place an icon in the host operating system's taskbar. ☆`258`

## Hardware

*   [arduino/arduino-cli](https://github.com/arduino/arduino-cli) — Arduino command line tool ☆`4,723`
*   [jaypipes/ghw](https://github.com/jaypipes/ghw) — Go HardWare discovery/inspection library ☆`1,793`
*   [zcalusic/sysinfo](https://github.com/zcalusic/sysinfo) — Sysinfo is a Go library providing Linux OS / kernel / hardware system information. ☆`564`

## Images

*   [hybridgroup/gocv](https://github.com/hybridgroup/gocv) — Go package for computer vision using OpenCV 4 and beyond. Includes support for DNN, CUDA, OpenCV Contrib, and OpenVINO. ☆`7,297`
*   [anthonynsimon/bild](https://github.com/anthonynsimon/bild) — Image processing algorithms in pure Go ☆`4,152`
*   [sensepost/gowitness](https://github.com/sensepost/gowitness) — gowitness - a golang, web screenshot utility using Chrome Headless ☆`4,054`
*   [cshum/imagor](https://github.com/cshum/imagor) — Fast, secure image processing server and Go library, using libvips ☆`3,836`
*   [thoas/picfit](https://github.com/thoas/picfit) — An image resizing server written in Go ☆`2,311`
*   [gographics/imagick](https://github.com/gographics/imagick) — Go binding to ImageMagick's MagickWand C API ☆`1,851`
*   [tdewolff/canvas](https://github.com/tdewolff/canvas) — Vector graphics in Go ☆`1,723`
*   [davidbyttow/govips](https://github.com/davidbyttow/govips) — A lightning fast image processing and resizing library for Go ☆`1,502`
*   [yeqown/go-qrcode](https://github.com/yeqown/go-qrcode) — To help gophers generate QR Codes with customized styles, such as color, block size, block shape, and icon. ☆`792`
*   [HugoSmits86/nativewebp](https://github.com/HugoSmits86/nativewebp) — Native webp encoder for Go ☆`366`
*   [auyer/steganography](https://github.com/auyer/steganography) — Pure Golang Library that allows LSB steganography on images using ZERO dependencies ☆`351`
*   [Pixboost/transformimgs](https://github.com/Pixboost/transformimgs) — Open source image CDN. ☆`282`
*   [kolesa-team/go-webp](https://github.com/kolesa-team/go-webp) — Simple and fast webp library for golang ☆`290`
*   [qmuntal/gltf](https://github.com/qmuntal/gltf) — Go library for encoding glTF 2.0 files ☆`264`
*   [gojek/darkroom](https://github.com/gojek/darkroom) —  ☆`235`
*   [aofei/cameron](https://github.com/aofei/cameron) — An avatar generator for Go. ☆`130`
*   [ungerik/go-cairo](https://github.com/ungerik/go-cairo) — Go binding for the cairo graphics library ☆`149`
*   [jonoton/scout](https://github.com/jonoton/scout) — Scout is a standalone open source software solution for DIY video security. ☆`26`

## IoT (Internet of Things)

*   [hybridgroup/gobot](https://github.com/hybridgroup/gobot) — Golang framework for robotics, drones, and the Internet of Things (IoT) ☆`9,338`
*   [lf-edge/ekuiper](https://github.com/lf-edge/ekuiper) — Lightweight data stream processing engine for IoT edge ☆`1,654`
*   [Edgenesis/shifu](https://github.com/Edgenesis/shifu) — Kubernetes-native IoT gateway ☆`1,383`
*   [rulego/rulego](https://github.com/rulego/rulego) — RuleGo is a lightweight, high-performance, embedded, next-generation component orchestration rule engine framework for Go. ☆`1,336`
*   [e154/smart-home](https://github.com/e154/smart-home) — software package for automation ☆`96`

## Job Scheduler

*   [go-co-op/gocron](https://github.com/go-co-op/gocron) — Easy and fluent Go cron scheduling ☆`6,741`
*   [reugn/go-quartz](https://github.com/reugn/go-quartz) — Minimalist and zero-dependency scheduling library for Go ☆`1,983`
*   [adhocore/gronx](https://github.com/adhocore/gronx) — Lightweight, fast and dependency-free Cron expression parser (due checker, next/prev due date finder), task runner, job scheduler and/or daemon for Golang (tested on v1.13+) and standalone usage. If you are bold, use it to replace crontab entirely. ☆`480`
*   [fieldryand/goflow](https://github.com/fieldryand/goflow) — Simple but powerful DAG scheduler and dashboard ☆`462`
*   [madflojo/tasks](https://github.com/madflojo/tasks) — Package tasks is an easy to use in-process scheduler for recurring tasks in Go ☆`321`
*   [bart6114/cheek](https://github.com/bart6114/cheek) — cheek: a pico-sized declarative job scheduler ☆`198`
*   [onatm/clockwerk](https://github.com/onatm/clockwerk) — Job Scheduling Library ☆`182`
*   [deepaksinghvi/cdule](https://github.com/deepaksinghvi/cdule) — cdule (pronounce as Schedule) Golang based scheduler library with database support. ☆`58`
*   [pardnchiu/go-scheduler](https://github.com/pardnchiu/go-scheduler) — Task scheduler with standard cron expressions ☆`31`
*   [romshark/sched](https://github.com/romshark/sched) — A job scheduler for Go with the ability to fast-forward time. ☆`28`

## JSON

*   [tidwall/gjson](https://github.com/tidwall/gjson) — Get JSON values quickly - JSON parser for Go ☆`15,336`
*   [Jeffail/gabs](https://github.com/Jeffail/gabs) — For parsing, creating and editing unknown or dynamic JSON in Go ☆`3,520`
*   [valyala/fastjson](https://github.com/valyala/fastjson) — Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection ☆`2,413`
*   [ohler55/ojg](https://github.com/ohler55/ojg) — Optimized JSON for Go ☆`926`
*   [wI2L/jsondiff](https://github.com/wI2L/jsondiff) — Compute the diff between two JSON documents as a series of JSON Patch (RFC6902) operations ☆`611`
*   [spyzhov/ajson](https://github.com/spyzhov/ajson) — Abstract JSON for Golang with JSONPath support ☆`287`
*   [Andrew-M-C/go.jsonvalue](https://github.com/Andrew-M-C/go.jsonvalue) — Quick Solution with Unstructured JSON data ☆`202`
*   [romshark/jscan](https://github.com/romshark/jscan) — High performance JSON iterator & validator for Go ☆`97`
*   [iOliverNguyen/ujson](https://github.com/iOliverNguyen/ujson) — µjson - A fast and minimal JSON parser and transformer that works on unstructured JSON ☆`85`
*   [neilotoole/jsoncolor](https://github.com/neilotoole/jsoncolor) — Colorized JSON output for Go ☆`49`
*   [ake-persson/mapslice-json](https://github.com/ake-persson/mapslice-json) — Go MapSlice for ordered marshal/ unmarshal of maps in JSON ☆`20`
*   [vtopc/epoch](https://github.com/vtopc/epoch) — Contains primitives for marshaling/unmarshaling Unix timestamp/epoch to/from built-in time.Time type in JSON ☆`17`

## Logging

*   [sirupsen/logrus](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,586`
*   [uber-go/zap](https://github.com/uber-go/zap) — Blazing fast, structured, leveled logging in Go. ☆`23,934`
*   [rs/zerolog](https://github.com/rs/zerolog) — Zero Allocation JSON Logger ☆`11,981`
*   [davecgh/go-spew](https://github.com/davecgh/go-spew) — Implements a deep pretty printer for Go data structures to aid in debugging ☆`6,350`
*   [golang/glog](https://github.com/golang/glog) — Leveled execution logs for Go ☆`3,617`
*   [k0kubun/pp](https://github.com/k0kubun/pp) — Colored pretty printer for Go language ☆`2,009`
*   [lmittmann/tint](https://github.com/lmittmann/tint) — slog.Handler that writes tinted (colorized) logs ☆`1,171`
*   [getsentry/sentry-go](https://github.com/getsentry/sentry-go) — The official Go SDK for Sentry (sentry.io) ☆`1,019`
*   [Lifailon/lazyjournal](https://github.com/Lifailon/lazyjournal) — A TUI for reading logs from journald, auditd, file system, Docker containers, Compose stacks, Podman and Kubernetes pods with support for output coloring and multiple filtering modes. ☆`930`
*   [phuslu/log](https://github.com/phuslu/log) — Fastest structured logging ☆`824`
*   [samber/slog-multi](https://github.com/samber/slog-multi) — Design workflows of slog handlers: pipeline, middleware, fanout, routing, failover, load balancing... ☆`576`
*   [gookit/slog](https://github.com/gookit/slog) — Lightweight, configurable, extensible logging library written in Go ☆`516`
*   [henvic/httpretty](https://github.com/henvic/httpretty) — Package httpretty prints the HTTP requests you make with Go pretty on your terminal. ☆`414`
*   [hashicorp/logutils](https://github.com/hashicorp/logutils) — Utilities for slightly better logging in Go (Golang). ☆`371`
*   [simukti/sqldb-logger](https://github.com/simukti/sqldb-logger) — A logger for Go SQL database driver without modifying existing \*sql.DB stdlib usage. ☆`383`
*   [samber/slog-formatter](https://github.com/samber/slog-formatter) — slog: Attribute formatting ☆`200`
*   [rs/xlog](https://github.com/rs/xlog) — xlog is a logger for net/context aware HTTP applications ☆`140`
*   [DeRuina/timberjack](https://github.com/DeRuina/timberjack) — Timberjack is a Go log rolling library with support for size-based, time-based, and manual rotation. ☆`97`
*   [yuseferi/zax](https://github.com/yuseferi/zax) — Golang Zap logger with context ☆`28`
*   [clok/kemba](https://github.com/clok/kemba) — A tiny debug logging tool. Ideal for CLI tools and command applications ☆`17`

## Machine Learning

*   [sjwhitworth/golearn](https://github.com/sjwhitworth/golearn) — Machine Learning for Go ☆`9,449`
*   [gorgonia/gorgonia](https://github.com/gorgonia/gorgonia) — Gorgonia is a library that helps facilitate machine learning in Go. ☆`5,882`
*   [otiai10/gosseract](https://github.com/otiai10/gosseract) — Go package for OCR (Optical Character Recognition), by using Tesseract C++ library ☆`3,021`
*   [galeone/tfgo](https://github.com/galeone/tfgo) — Tensorflow + Go, the gopher way ☆`2,487`
*   [gomlx/gomlx](https://github.com/gomlx/gomlx) — GoMLX: An Accelerated Machine Learning Framework For Go ☆`1,178`
*   [patrikeh/go-deep](https://github.com/patrikeh/go-deep) — Artificial Neural Network ☆`558`
*   [knights-analytics/hugot](https://github.com/knights-analytics/hugot) — Onnx transformer pipelines in Golang ☆`497`
*   [c-bata/goptuna](https://github.com/c-bata/goptuna) — A hyperparameter optimization framework, inspired by Optuna. ☆`272`

## Messaging

*   [IBM/sarama](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,314`
*   [hibiken/asynq](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`12,457`
*   [centrifugal/centrifugo](https://github.com/centrifugal/centrifugo) — Scalable real-time messaging server in a language-agnostic way. Self-hosted alternative to Pubnub, Pusher, Ably, socket.io, Phoenix.PubSub, SignalR. Set up once and forever. ☆`9,571`
*   [ThreeDotsLabs/watermill](https://github.com/ThreeDotsLabs/watermill) — Building event-driven applications the easy way in Go. ☆`9,261`
*   [appleboy/gorush](https://github.com/appleboy/gorush) — A push notification server written in Go (Golang). ☆`8,593`
*   [RichardKnop/machinery](https://github.com/RichardKnop/machinery) — Machinery is an asynchronous task queue/job queue based on distributed message passing. ☆`7,889`
*   [nats-io/nats.go](https://github.com/nats-io/nats.go) — Golang client for NATS, the cloud native messaging system. ☆`6,263`
*   [confluentinc/confluent-kafka-go](https://github.com/confluentinc/confluent-kafka-go) — Confluent's Apache Kafka Golang client ☆`5,044`
*   [dunglas/mercure](https://github.com/dunglas/mercure) — An open, easy, fast, reliable and battery-efficient solution for real-time communications ☆`5,114`
*   [olahol/melody](https://github.com/olahol/melody) — Minimalist websocket framework for Go ☆`4,029`
*   [sideshow/apns2](https://github.com/sideshow/apns2) — HTTP/2 Apple Push Notification Service (APNs) push provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps, using the APNs HTTP/2 protocol. ☆`3,145`
*   [lovoo/goka](https://github.com/lovoo/goka) — Goka is a compact yet powerful distributed stream processing library for Apache Kafka written in Go. ☆`2,490`
*   [asaskevich/EventBus](https://github.com/asaskevich/EventBus) — \[Go] Lightweight eventbus with async compatibility for Go ☆`1,943`
*   [rabbitmq/amqp091-go](https://github.com/rabbitmq/amqp091-go) — An AMQP 0-9-1 Go client maintained by the RabbitMQ team ☆`1,918`
*   [pebbe/zmq4](https://github.com/pebbe/zmq4) — A Go interface to ZeroMQ version 4 ☆`1,236`
*   [timbray/quamina](https://github.com/timbray/quamina) — Home of Quamina, a fast pattern-matching library in Go ☆`436`
*   [cskr/pubsub](https://github.com/cskr/pubsub) — A simple pubsub package for go. ☆`446`
*   [jandelgado/rabtap](https://github.com/jandelgado/rabtap) — RabbitMQ wire tap and swiss army knife ☆`277`
*   [mehdihadeli/Go-MediatR](https://github.com/mehdihadeli/Go-MediatR) — A library for handling mediator patterns and simplified CQRS patterns within an event-driven architecture, inspired by csharp MediatR library. ☆`265`
*   [goptics/varmq](https://github.com/goptics/varmq) — A Simplest Storage-Agnostic and Zero-dep Message Queue for Your Concurrent Go Program ☆`171`
*   [hyperonym/ratus](https://github.com/hyperonym/ratus) — Ratus is a RESTful asynchronous task queue server. It translated concepts of distributed task queues into a set of resources that conform to REST principles and provides a consistent HTTP API for various backends. ☆`124`
*   [robinjoseph08/redisqueue](https://github.com/robinjoseph08/redisqueue) — redisqueue provides a producer and consumer of a queue that uses Redis streams ☆`137`
*   [oagudo/outbox](https://github.com/oagudo/outbox) — Lightweight library for the transactional outbox pattern in Go, not tied to any specific relational database or broker. ☆`108`
*   [furdarius/rabbitroutine](https://github.com/furdarius/rabbitroutine) — Lightweight library that handles RabbitMQ auto-reconnect and publishing retry routine for you. ☆`113`
*   [dailymotion/oplog](https://github.com/dailymotion/oplog) — A generic oplog/replication system for microservices ☆`110`
*   [Protocol-Lattice/GoEventBus](https://github.com/Protocol-Lattice/GoEventBus) — A lock-free, ultra-fast event bus for Go ☆`46`
*   [jirenius/go-res](https://github.com/jirenius/go-res) — RES Service protocol library for Go ☆`68`
*   [SchwarzIT/hypermatch](https://github.com/SchwarzIT/hypermatch) — hypermatch is a high-performance Go library designed for rapid matching of a large number of rules to events. It processes thousands of events per second against extensive rule sets in-memory with minimal latency . ☆`32`
*   [maxatome/go-vitotrol](https://github.com/maxatome/go-vitotrol) — golang client library to Viessmann Vitotrol web service ☆`23`

## Microsoft Office

*   [unidoc/unioffice](https://github.com/unidoc/unioffice) — Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents ☆`4,705`

### Microsoft Excel

*   [qax-os/excelize](https://github.com/qax-os/excelize) — Go language library for reading and writing Microsoft Excel (XLAM / XLSM / XLSX / XLTM / XLTX) spreadsheets ☆`19,969`
*   [go-the-way/exl](https://github.com/go-the-way/exl) — Excel binding to struct written in Go.(Only supports Go1.18+) ☆`32`

### Microsoft Word

*   [gomutex/godocx](https://github.com/gomutex/godocx) — Go library for reading and writing Microsoft Docx ☆`224`

## Middlewares

*   [urfave/negroni](https://github.com/urfave/negroni) — Idiomatic HTTP Middleware for Golang ☆`7,543`
*   [justinas/alice](https://github.com/justinas/alice) — Painless middleware chaining for Go ☆`3,335`
*   [rs/cors](https://github.com/rs/cors) — Go net/http configurable handler to handle CORS requests ☆`2,838`
*   [didip/tollbooth](https://github.com/didip/tollbooth) — Simple middleware to rate-limit HTTP requests. ☆`2,840`
*   [unrolled/render](https://github.com/unrolled/render) — Go package for easily rendering JSON, XML, binary data, and HTML templates responses. ☆`1,986`
*   [lingrino/go-fault](https://github.com/lingrino/go-fault) — fault injection library in go using standard http middleware ☆`510`
*   [jub0bs/cors](https://github.com/jub0bs/cors) — perhaps the best CORS middleware library for Go ☆`163`
*   [rookie-ninja/rk-gin](https://github.com/rookie-ninja/rk-gin) — Start gin microservice from YAML, plugin of rk-boot ☆`51`
*   [faabiosr/echo-middleware](https://github.com/faabiosr/echo-middleware) — Go package that provides multiple middlewares for Echo Framework. ☆`16`

## Miscellaneous

### Dependency Injection

*   [uber-go/fx](https://github.com/uber-go/fx) — A dependency injection based application framework for Go. ☆`7,075`
*   [uber-go/dig](https://github.com/uber-go/dig) — A reflection based dependency injection toolkit for Go. ☆`4,383`
*   [goioc/di](https://github.com/goioc/di) — Simple and yet powerful Dependency Injection for Go ☆`374`
*   [d3fvxl/di](https://github.com/d3fvxl/di) — A full-featured dependency injection container for go programming language. ☆`239`
*   [go-kod/kod](https://github.com/go-kod/kod) — A generics based dependency injection application framework for Go, supporting aspect oriented programming based on interceptors ☆`197`
*   [i-love-flamingo/dingo](https://github.com/i-love-flamingo/dingo) — Go Dependency Injection Framework ☆`185`
*   [NVIDIA/gontainer](https://github.com/NVIDIA/gontainer) — Simple but powerful dependency injection container for Go projects! ☆`61`
*   [junioryono/godi](https://github.com/junioryono/godi) — Dependency Injection with Service Lifetimes for Go ☆`62`
*   [matzefriedrich/parsley](https://github.com/matzefriedrich/parsley) — An easy-to-use reflection-based dependency injection package that fits into any Go application. ☆`31`
*   [muir/nject](https://github.com/muir/nject) — Golang type-safe dependency injection ☆`30`
*   [logrange/linker](https://github.com/logrange/linker) — Dependency Injection and Inversion of Control package ☆`35`
*   [firasdarwish/ore](https://github.com/firasdarwish/ore) — Advanced Dependency Injection Solution for Go ☆`24`
*   [componego/componego](https://github.com/componego/componego) — The most flexible component-oriented framework for GoLang applications ☆`28`
*   [gontainer/gontainer](https://github.com/gontainer/gontainer) — YAML-based Dependency Injection container for GO ☆`16`

### Project Layout

*   [golang-standards/project-layout](https://github.com/golang-standards/project-layout) — Standard Go Project Layout ☆`54,497`
*   [Melkeydev/go-blueprint](https://github.com/Melkeydev/go-blueprint) — Go-blueprint allows users to spin up a quick Go project using a popular framework ☆`8,438`
*   [ardanlabs/service](https://github.com/ardanlabs/service) — Starter-kit for writing services in Go using Kubernetes. ☆`3,904`
*   [Shpota/goxygen](https://github.com/Shpota/goxygen) — Generate a modern Web project with Go and Angular, React, or Vue in seconds ☆`3,602`
*   [mikestefanello/pagoda](https://github.com/mikestefanello/pagoda) — Rapid, easy full-stack web development starter kit and admin panel in Go ☆`2,873`
*   [go-nunu/nunu](https://github.com/go-nunu/nunu) — A CLI tool for building Go applications. ☆`2,490`
*   [sagikazarmark/modern-go-application](https://github.com/sagikazarmark/modern-go-application) — Modern Go Application example ☆`1,935`
*   [naughtygopher/goapp](https://github.com/naughtygopher/goapp) — An opinionated guideline to structure & develop a Go web application/service ☆`1,031`
*   [lacion/cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) — A Go project template ☆`730`
*   [allaboutapps/go-starter](https://github.com/allaboutapps/go-starter) — An opinionated production-ready SQL-/Swagger-first RESTful JSON API written in Go, highly integrated with VSCode DevContainers by allaboutapps. ☆`586`
*   [golang-templates/seed](https://github.com/golang-templates/seed) — Go application GitHub repository template. ☆`546`
*   [raeperd/kickstart.go](https://github.com/raeperd/kickstart.go) — Minimalistic HTTP server template in Go ☆`100`
*   [wangyoucao577/go-project-layout](https://github.com/wangyoucao577/go-project-layout) — My understanding of how to structure a golang project. ☆`26`

### Strings

*   [huandu/xstrings](https://github.com/huandu/xstrings) — Implements string functions widely used in other languages but absent in Go. ☆`1,415`
*   [abhimanyu003/sttr](https://github.com/abhimanyu003/sttr) — cross-platform, cli app to perform various operations on string ☆`1,229`
*   [gobeam/stringy](https://github.com/gobeam/stringy) — Convert string to camel case, snake case, kebab case / slugify, custom delimiter, pad string, tease string and many other functionalities with help of by Stringy package. ☆`253`
*   [ozgio/strutil](https://github.com/ozgio/strutil) — String utilities for Go ☆`207`

### Uncategorized

*   [shirou/gopsutil](https://github.com/shirou/gopsutil) — psutil for golang ☆`11,561`
*   [TwiN/gatus](https://github.com/TwiN/gatus) — Automated developer-oriented status page ☆`9,132`
*   [brianvoe/gofakeit](https://github.com/brianvoe/gofakeit) — Random fake data generator written in go ☆`5,255`
*   [mojocn/base64Captcha](https://github.com/mojocn/base64Captcha) — captcha of base64 image string ☆`2,317`
*   [eapache/go-resiliency](https://github.com/eapache/go-resiliency) — Resiliency patterns for golang ☆`2,337`
*   [containrrr/shoutrrr](https://github.com/containrrr/shoutrrr) — Notification library for gophers and their furry friends. ☆`1,409`
*   [qmuntal/stateless](https://github.com/qmuntal/stateless) — Go library for creating finite state machines ☆`1,131`
*   [alexliesenfeld/health](https://github.com/alexliesenfeld/health) — A simple and flexible health check library for Go. ☆`825`
*   [ulikunitz/xz](https://github.com/ulikunitz/xz) — Pure golang package for reading and writing xz-compressed files ☆`536`
*   [mholt/archives](https://github.com/mholt/archives) — Cross-platform library to create & extract archives, compress & decompress files, and walk virtual file systems across various formats ☆`341`
*   [ddddddO/gtree](https://github.com/ddddddO/gtree) — Easily output ASCII tree from Go program or Markdown unordered list (and it does more than just output tree!) ☆`320`
*   [gen2brain/go-unarr](https://github.com/gen2brain/go-unarr) — Go bindings for unarr (decompression library for RAR, TAR, ZIP and 7z archives) ☆`299`
*   [steambap/captcha](https://github.com/steambap/captcha) — Package captcha provides an easy to use, unopinionated API for captcha generation ☆`162`
*   [antham/gommit](https://github.com/antham/gommit) — Enforce git message commit consistency ☆`115`
*   [osamingo/indigo](https://github.com/osamingo/indigo) — A distributed unique ID generator of using Sonyflake and encoded by Base58 ☆`111`
*   [rkoesters/xdg](https://github.com/rkoesters/xdg) — FreeDesktop.org (xdg) Specs implemented in Go ☆`48`
*   [osamingo/gosh](https://github.com/osamingo/gosh) — Provide Go Statistics Handler, Struct, Measure Method ☆`35`
*   [lrita/numa](https://github.com/lrita/numa) — NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code. ☆`37`

## Natural Language Processing

### Language Detection

*   [pemistahl/lingua-go](https://github.com/pemistahl/lingua-go) — The most accurate natural language detection library for Go, suitable for short text and mixed-language text ☆`1,299`

### Morphological Analyzers

*   [nlpodyssey/spago](https://github.com/nlpodyssey/spago) — Self-contained Machine Learning and Natural Language Processing library in Go ☆`1,835`
*   [ikawaha/kagome](https://github.com/ikawaha/kagome) — Self-contained Japanese Morphological Analyzer written in pure Go ☆`913`
*   [afjoseph/RAKE.Go](https://github.com/afjoseph/RAKE.Go) — A Go port of the Rapid Automatic Keyword Extraction algorithm (RAKE) ☆`122`
*   [jonreiter/govader](https://github.com/jonreiter/govader) — vader sentiment analysis in go ☆`52`

### Slugifiers

*   [gosimple/slug](https://github.com/gosimple/slug) — URL-friendly slugify with multiple languages support. ☆`1,297`

### Tokenizers

*   [go-ego/gse](https://github.com/go-ego/gse) — Go efficient multilingual NLP and text segmentation; support English, Chinese, Japanese and others. ☆`2,755`
*   [pebbe/textcat](https://github.com/pebbe/textcat) — A Go package for n-gram based text categorization, with support for utf-8 and raw text ☆`72`

### Translation

*   [nicksnyder/go-i18n](https://github.com/nicksnyder/go-i18n) — Translate your Go program into multiple languages. ☆`3,406`
*   [leonelquinteros/gotext](https://github.com/leonelquinteros/gotext) — Go (Golang) GNU gettext utilities package ☆`487`
*   [vorlif/spreak](https://github.com/vorlif/spreak) — Flexible translation and humanization library for Go, based on the concepts behind gettext. ☆`69`
*   [invopop/ctxi18n](https://github.com/invopop/ctxi18n) — Go Context Internationalization - translating apps easily ☆`81`
*   [mehanizm/iuliia-go](https://github.com/mehanizm/iuliia-go) — Transliterate Cyrillic → Latin in every possible way ☆`55`
*   [youthlin/t](https://github.com/youthlin/t) — t: translation util for go, using GNU gettext ☆`20`

### Transliteration

*   [alexsergivan/transliterator](https://github.com/alexsergivan/transliterator) — Golang text Transliterator (i.e München -> Muenchen) ☆`46`

## Networking

*   [valyala/fasthttp](https://github.com/valyala/fasthttp) — Fast HTTP package for Go. Tuned for high performance. Zero memory allocations in hot paths. Up to 10x faster than net/http ☆`23,097`
*   [pion/webrtc](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`15,665`
*   [xtaci/kcptun](https://github.com/xtaci/kcptun) — A Quantum-Safe Secure Tunnel based on QPP, KCP, FEC, and N:M multiplexing. ☆`14,288`
*   [cloudflare/cloudflared](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`12,061`
*   [quic-go/quic-go](https://github.com/quic-go/quic-go) — A production-ready QUIC implementation in pure Go ☆`11,192`
*   [panjf2000/gnet](https://github.com/panjf2000/gnet) — gnet is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go. ☆`10,913`
*   [miekg/dns](https://github.com/miekg/dns) — DNS library in Go ☆`8,558`
*   [google/gopacket](https://github.com/google/gopacket) — Provides packet processing capabilities for Go ☆`6,682`
*   [elazarl/goproxy](https://github.com/elazarl/goproxy) — An HTTP proxy library for Go ☆`6,532`
*   [cloudwego/netpoll](https://github.com/cloudwego/netpoll) — A high-performance non-blocking I/O networking framework focusing on RPC scenarios. ☆`4,464`
*   [xtaci/kcp-go](https://github.com/xtaci/kcp-go) — A Crypto-Secure Reliable-UDP Library for golang with FEC ☆`4,348`
*   [xjasonlyu/tun2socks](https://github.com/xjasonlyu/tun2socks) — tun2socks - powered by gVisor TCP/IP stack ☆`4,377`
*   [gliderlabs/ssh](https://github.com/gliderlabs/ssh) — Easy SSH servers in Golang ☆`4,029`
*   [osrg/gobgp](https://github.com/osrg/gobgp) — BGP implemented in the Go Programming Language ☆`3,925`
*   [fortio/fortio](https://github.com/fortio/fortio) — Fortio load testing library, command line tool, advanced echo server and web UI in go (golang). Allows to specify a set query-per-second load and record latency histograms and other useful stats. ☆`3,644`
*   [lesismal/nbio](https://github.com/lesismal/nbio) — Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use. ☆`2,607`
*   [songgao/water](https://github.com/songgao/water) — A simple TUN/TAP library written in native Go. ☆`2,099`
*   [hashicorp/go-getter](https://github.com/hashicorp/go-getter) — Package for downloading things from a string URL using a variety of protocols. ☆`1,777`
*   [Allenxuxu/gev](https://github.com/Allenxuxu/gev) — Gev is a lightweight, fast non-blocking TCP network library / websocket server based on Reactor mode. Support custom protocols to quickly and easily build high-performance servers. ☆`1,769`
*   [pkg/sftp](https://github.com/pkg/sftp) — SFTP support for the go.crypto/ssh package ☆`1,623`
*   [lxzan/gws](https://github.com/lxzan/gws) — simple, fast, reliable websocket server & client, supports running over tcp/kcp/unix domain socket. keywords: ws, proxy, chat, go, golang... ☆`1,657`
*   [yosebyte/nodepass](https://github.com/yosebyte/nodepass) — A secure, efficient TCP/UDP tunneling solution that delivers fast, reliable access across network restrictions using pre-established TLS/TCP connections ☆`1,483`
*   [cavaliergopher/grab](https://github.com/cavaliergopher/grab) — A download manager package for Go ☆`1,461`
*   [hashicorp/mdns](https://github.com/hashicorp/mdns) — Simple mDNS client/server library in Golang ☆`1,311`
*   [gosnmp/gosnmp](https://github.com/gosnmp/gosnmp) — An SNMP library written in Go ☆`1,225`
*   [DrmagicE/gmqtt](https://github.com/DrmagicE/gmqtt) — Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.x and V5 in golang ☆`1,022`
*   [semihalev/sdns](https://github.com/semihalev/sdns) — A high-performance, recursive DNS resolver server with DNSSEC support, focused on preserving privacy. ☆`1,017`
*   [yahoo/vssh](https://github.com/yahoo/vssh) — Go Library to Execute Commands Over SSH at Scale ☆`982`
*   [xtaci/gaio](https://github.com/xtaci/gaio) — High performance minimalism async-io(proactor) networking for Golang. ☆`798`
*   [ccding/go-stun](https://github.com/ccding/go-stun) — A go implementation of the STUN client (RFC 3489 and RFC 5389) ☆`711`
*   [schollz/peerdiscovery](https://github.com/schollz/peerdiscovery) — Pure-Go library for cross-platform local peer discovery using UDP multicast ☆`665`
*   [masterzen/winrm](https://github.com/masterzen/winrm) — Command-line tool and library for Windows remote command execution in Go ☆`455`
*   [fclairamb/ftpserverlib](https://github.com/fclairamb/ftpserverlib) — golang ftp server library ☆`455`
*   [mosajjal/dnsmonster](https://github.com/mosajjal/dnsmonster) — Passive DNS Capture and Monitoring Toolkit ☆`346`
*   [google/gnxi](https://github.com/google/gnxi) — gNXI Tools - gRPC Network Management/Operations Interface Tools ☆`282`
*   [jeroenrinzema/psql-wire](https://github.com/jeroenrinzema/psql-wire) — PostgreSQL server wire protocol. Build your own server and start serving connections. ☆`203`
*   [eduardonunesp/sslb](https://github.com/eduardonunesp/sslb) — Golang Super Simple Load Balance ☆`151`
*   [c-robinson/iplib](https://github.com/c-robinson/iplib) — A library for working with IP addresses and networks in Go ☆`151`
*   [gaissmai/bart](https://github.com/gaissmai/bart) — The Balanced Routing Table is an adaptation of D. Knuth's ART algorithm and requires significantly less memory and has an even better lookup speed. ☆`108`
*   [joeig/go-powerdns](https://github.com/joeig/go-powerdns) — PowerDNS API client for Go (community project) ☆`103`
*   [cheng-zhongliang/event](https://github.com/cheng-zhongliang/event) — Simple I/O event notification library wirtten in Golang ☆`119`
*   [jimlambrt/gldap](https://github.com/jimlambrt/gldap) — Build LDAP services w/ Go ☆`117`
*   [soypat/natiu-mqtt](https://github.com/soypat/natiu-mqtt) — A dead-simple, extensible MQTT implementation well suited for embedded systems. ☆`100`
*   [alegrey91/fwdctl](https://github.com/alegrey91/fwdctl) — CLI tool to easily manage IPTables forwards ☆`72`
*   [fish-tennis/gnet](https://github.com/fish-tennis/gnet) — high performance net library for game server ☆`25`
*   [wzshiming/httpproxy](https://github.com/wzshiming/httpproxy) — HTTP proxy handler and dialer ☆`31`

### HTTP Clients

*   [go-resty/resty](https://github.com/go-resty/resty) — Simple HTTP, REST, and SSE client library for Go ☆`11,372`
*   [imroc/req](https://github.com/imroc/req) — Simple Go HTTP client with Black Magic ☆`4,679`
*   [gojek/heimdall](https://github.com/gojek/heimdall) — An enhanced HTTP client for Go ☆`2,701`
*   [hashicorp/go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) — Retryable HTTP client in Go ☆`2,232`
*   [levigross/grequests](https://github.com/levigross/grequests) — A Go "clone" of the great and famous Requests library ☆`2,182`
*   [dghubble/sling](https://github.com/dghubble/sling) — A Go HTTP client library for creating and sending API requests ☆`1,717`
*   [earthboundkid/requests](https://github.com/earthboundkid/requests) — HTTP requests for Gophers ☆`1,654`
*   [bogdanfinn/tls-client](https://github.com/bogdanfinn/tls-client) — net/http.Client like HTTP Client with options to select specific client TLS Fingerprints to use for requests. ☆`1,339`
*   [Noooste/azuretls-client](https://github.com/Noooste/azuretls-client) — An easy-to-use HTTP client to spoof TLS/JA3, HTTP2 and HTTP3 fingerprint ☆`384`
*   [monaco-io/request](https://github.com/monaco-io/request) — go request, go http client ☆`293`
*   [opus-domini/fast-shot](https://github.com/opus-domini/fast-shot) — Hit your API targets with rapid-fire precision using Go's fastest and simple HTTP Client. ☆`94`
*   [NdoleStudio/go-otelroundtripper](https://github.com/NdoleStudio/go-otelroundtripper) — Go http.RoundTripper that emits open telemetry metrics. This helps you easily get metrics for all external APIs you interact with. ☆`84`
*   [go-zoox/fetch](https://github.com/go-zoox/fetch) — Go Fetch - A Powerful, Lightweight, Easy Http Client, inspired by Web Fetch API ☆`88`
*   [rezmoss/axios4go](https://github.com/rezmoss/axios4go) — A Go HTTP client library inspired by Axios, providing a simple and intuitive API for making HTTP requests with features like interceptors, JSON handling, configurable instances, and automatic retries ☆`30`

## OpenGL

*   [go-gl/glfw](https://github.com/go-gl/glfw) — Go bindings for GLFW 3 ☆`1,651`
*   [go-gl/gl](https://github.com/go-gl/gl) — Go bindings for OpenGL (generated via glow) ☆`1,174`
*   [go-gl/mathgl](https://github.com/go-gl/mathgl) — A pure Go 3D math library. ☆`590`

## ORM

*   [go-gorm/gorm](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,172`
*   [ent/ent](https://github.com/ent/ent) — An entity framework for Go ☆`16,711`
*   [aarondl/sqlboiler](https://github.com/aarondl/sqlboiler) — Generate a Go ORM tailored to your database schema. ☆`6,967`
*   [uptrace/bun](https://github.com/uptrace/bun) — SQL-first Golang ORM ☆`4,483`
*   [upper/db](https://github.com/upper/db) — Data Access Layer (DAL) for PostgreSQL, CockroachDB, MySQL, SQLite and MongoDB with ORM-like features. ☆`3,627`
*   [huandu/go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) — A flexible and powerful SQL string builder library plus a zero-config ORM. ☆`1,631`
*   [stephenafamo/bob](https://github.com/stephenafamo/bob) — SQL query builder and ORM/Factory generator for Go with support for PostgreSQL, MySQL and SQLite ☆`1,548`
*   [go-rel/rel](https://github.com/go-rel/rel) — Modern ORM for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API ☆`782`
*   [hashicorp/go-dbw](https://github.com/hashicorp/go-dbw) — A simple package that encapsulates database operations. ☆`16`

## Package Management

*   [anchore/syft](https://github.com/anchore/syft) — CLI tool and library for generating a Software Bill of Materials from container images and filesystems ☆`7,983`
*   [nao1215/gup](https://github.com/nao1215/gup) — gup - Update binaries installed by "go install" with goroutines. ☆`476`
*   [chaindead/modup](https://github.com/chaindead/modup) — Terminal UI for Go dependency updates with outdated module detection and selective upgrading. ☆`59`

## Performance

*   [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger) — CNCF Jaeger, a Distributed Tracing Platform ☆`22,130`
*   [pixie-io/pixie](https://github.com/pixie-io/pixie) — Instant Kubernetes-Native Application Observability ☆`6,246`
*   [arl/statsviz](https://github.com/arl/statsviz) — Visualise Go runtime metrics in real time ☆`3,590`
*   [nikolaydubina/go-instrument](https://github.com/nikolaydubina/go-instrument) — Automatically add Trace Spans to Go functions ☆`284`
*   [joetifa2003/mm-go](https://github.com/joetifa2003/mm-go) — Generic manual memory management for golang ☆`186`

## Query Language

*   [99designs/gqlgen](https://github.com/99designs/gqlgen) — go generate based graphql server library ☆`10,590`
*   [TomWright/dasel](https://github.com/TomWright/dasel) — Select, put and delete data from JSON, TOML, YAML, XML and CSV files with a single tool. Supports conversion between formats and can be used as a Go package. ☆`7,688`
*   [graph-gophers/graphql-go](https://github.com/graph-gophers/graphql-go) — GraphQL server with a focus on ease of use ☆`4,741`
*   [bhmj/jsonslice](https://github.com/bhmj/jsonslice) — json slicer ☆`92`
*   [hashicorp/mql](https://github.com/hashicorp/mql) — Model Query Language (mql) is a query language for your database models. ☆`66`
*   [timsolov/rest-query-parser](https://github.com/timsolov/rest-query-parser) — Query Parser for REST ☆`89`
*   [ccbrown/api-fu](https://github.com/ccbrown/api-fu) — A collection of Go packages for creating robust GraphQL APIs ☆`57`
*   [AsaiYusuke/jsonpath](https://github.com/AsaiYusuke/jsonpath) — A query library for retrieving part of JSON based on JSONPath syntax. ☆`28`

## Reflection

*   [tiendc/go-deepcopy](https://github.com/tiendc/go-deepcopy) — Fast deep-copy library for Go ☆`115`
*   [wzshiming/gotype](https://github.com/wzshiming/gotype) — Golang source code parsing, usage like reflect package ☆`64`

## Resource Embedding

*   [shurcooL/vfsgen](https://github.com/shurcooL/vfsgen) — Takes an input http.FileSystem (likely at go generate time) and generates Go code that statically implements it. ☆`984`

## Routers

*   [gorilla/mux](https://github.com/gorilla/mux) — Package gorilla/mux is a powerful HTTP router and URL matcher for building Go web servers with ☆`21,712`
*   [go-chi/chi](https://github.com/go-chi/chi) — lightweight, idiomatic and composable router for building Go HTTP services ☆`20,954`
*   [gernest/alien](https://github.com/gernest/alien) — A lightweight and fast http router from outer space ☆`134`
*   [ngamux/ngamux](https://github.com/ngamux/ngamux) — Simple HTTP router for Go ☆`70`
*   [bmf-san/goblin](https://github.com/bmf-san/goblin) — A golang http router based on trie tree. ☆`81`
*   [muir/nchi](https://github.com/muir/nchi) — golang http router with elegance, speed, and flexibility ☆`18`

## Science and Data Analysis

*   [gonum/gonum](https://github.com/gonum/gonum) — Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more ☆`8,225`
*   [gonum/plot](https://github.com/gonum/plot) — A repository for plotting and visualizing data ☆`2,923`
*   [paulmach/orb](https://github.com/paulmach/orb) — Types and utilities for working with 2d geometry in Golang ☆`1,059`
*   [bebop/poly](https://github.com/bebop/poly) — A Go package for engineering organisms. ☆`712`
*   [hmdsefi/gograph](https://github.com/hmdsefi/gograph) — A golang generic graph library that provides mathematical graph-theory and algorithms. ☆`101`
*   [nikolaydubina/jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) — JSONL Graph Tools ☆`77`
*   [claygod/PiHex](https://github.com/claygod/PiHex) — PiHex Library, written in Go, generates a hexadecimal number sequence in the number Pi in the range from 0 to 10,000,000. ☆`20`
*   [sgreben/piecewiselinear](https://github.com/sgreben/piecewiselinear) — tiny linear interpolation library for go ☆`28`

## Security

*   [FiloSottile/age](https://github.com/FiloSottile/age) — A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability. ☆`20,187`
*   [go-acme/lego](https://github.com/go-acme/lego) — Let's Encrypt/ACME client and library written in Go ☆`9,007`
*   [caddyserver/certmagic](https://github.com/caddyserver/certmagic) — Automatic HTTPS for any Go program: fully-managed TLS certificate issuance and renewal ☆`5,379`
*   [Ullaakut/cameradar](https://github.com/Ullaakut/cameradar) — Cameradar hacks its way into RTSP videosurveillance cameras ☆`4,768`
*   [corazawaf/coraza](https://github.com/corazawaf/coraza) — OWASP Coraza WAF is a golang modsecurity compatible web application firewall library ☆`3,072`
*   [awnumar/memguard](https://github.com/awnumar/memguard) — Software sandbox for storage of sensitive information in memory. ☆`2,678`
*   [unrolled/secure](https://github.com/unrolled/secure) — HTTP middleware for Go that facilitates some quick security wins. ☆`2,332`
*   [cossacklabs/themis](https://github.com/cossacklabs/themis) — Easy to use cryptographic framework for data protection: secure messaging with forward secrecy and secure data storage. Has unified APIs across 14 platforms. ☆`1,945`
*   [mariocandela/beelzebub](https://github.com/mariocandela/beelzebub) — A secure low code honeypot framework, leveraging AI for System Virtualization. ☆`1,696`
*   [cossacklabs/acra](https://github.com/cossacklabs/acra) — Database security suite. Database proxy with field-level encryption, search through encrypted data, SQL injections prevention, intrusion detection, honeypots. Supports client-side and proxy-side ("transparent") encryption. SQL, NoSQL. ☆`1,442`
*   [dromara/dongle](https://github.com/dromara/dongle) — A simple, semantic and developer-friendly crypto package for golang ☆`1,090`
*   [anatol/booster](https://github.com/anatol/booster) — Fast and secure initramfs generator ☆`606`
*   [kevinburke/nacl](https://github.com/kevinburke/nacl) — Pure Go implementation of the NaCL set of API's ☆`551`
*   [ssh-vault/ssh-vault](https://github.com/ssh-vault/ssh-vault) — encrypt/decrypt using ssh keys ☆`481`
*   [hillu/go-yara](https://github.com/hillu/go-yara) — Go bindings for YARA ☆`380`
*   [teler-sh/teler-waf](https://github.com/teler-sh/teler-waf) — teler-waf is a Go HTTP middleware that protects local web services from OWASP Top 10 threats, known vulnerabilities, malicious actors, botnets, unwanted crawlers, and brute force attacks. ☆`392`
*   [number571/go-peer](https://github.com/number571/go-peer) — Library for developing secure, decentralized, anonymous and quantum-resistant networks in Go language ☆`312`
*   [anatol/luks.go](https://github.com/anatol/luks.go) — Pure Golang library to manage LUKS partitions ☆`93`
*   [zitadel/passwap](https://github.com/zitadel/passwap) — Package passwap provides a unified implementation between different password hashing algorithms. It allows for easy swapping between algorithms, using the same API for all of them. ☆`70`
*   [tg123/go-htpasswd](https://github.com/tg123/go-htpasswd) — Apache htpasswd Parser for Go. ☆`46`
*   [adrianosela/sslmgr](https://github.com/adrianosela/sslmgr) — A layer of abstraction the around acme/autocert certificate manager (Golang) ☆`30`
*   [rsjethani/secret](https://github.com/rsjethani/secret) — Prevent your secrets from leaking into logs, std\* etc. ☆`32`
*   [andskur/argon2-hashing](https://github.com/andskur/argon2-hashing) — A light package for generating and comparing password hashing with argon2 in Go ☆`25`
*   [bitfield/qrand](https://github.com/bitfield/qrand) — Quantum randomness source using the ANU hardware QRNG ☆`17`

## Serialization

*   [golang/protobuf](https://github.com/golang/protobuf) — Go support for Google's protocol buffers ☆`10,041`
*   [ugorji/go](https://github.com/ugorji/go) — idiomatic codec and rpc lib for msgpack, cbor, json, etc. msgpack.org\[Go] ☆`1,917`
*   [jszwec/csvutil](https://github.com/jszwec/csvutil) — csvutil provides fast and idiomatic mapping between CSV and Go (golang) values. ☆`1,021`
*   [fxamacker/cbor](https://github.com/fxamacker/cbor) — CBOR codec (RFC 8949, RFC 8742) with CBOR tags, Go struct tag options (toarray, keyasint, omitempty, omitzero), float64/32/16, big.Int, and fuzz tested. ☆`967`
*   [ghostiam/binstruct](https://github.com/ghostiam/binstruct) — Golang binary decoder for mapping data into the structure ☆`110`
*   [csweichel/bel](https://github.com/csweichel/bel) — Generate TypeScript interfaces from Go structs/interfaces - useful for JSON RPC ☆`45`
*   [o1egl/fwencoder](https://github.com/o1egl/fwencoder) — Fixed width file parser (encoder/decoder) in GO (golang) ☆`27`
*   [tiendc/go-csvlib](https://github.com/tiendc/go-csvlib) — High-level performant CSV encoding and decoding library ☆`19`

## Server Applications

*   [caddyserver/caddy](https://github.com/caddyserver/caddy) — Fast and extensible multi-platform HTTP/1-2-3 web server with automatic HTTPS ☆`68,072`
*   [minio/minio](https://github.com/minio/minio) — MinIO is a high-performance, S3 compatible object store, open sourced under GNU AGPLv3 license. ☆`58,477`
*   [pocketbase/pocketbase](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`52,940`
*   [etcd-io/etcd](https://github.com/etcd-io/etcd) — Distributed reliable key-value store for the most critical data of a distributed system ☆`50,830`
*   [drakkan/sftpgo](https://github.com/drakkan/sftpgo) — Full-featured and highly configurable SFTP, HTTP/S, FTP/S and WebDAV server - S3, Google Cloud Storage, Azure Blob ☆`11,369`
*   [roadrunner-server/roadrunner](https://github.com/roadrunner-server/roadrunner) — High-performance PHP application server, process manager written in Go and powered with plugins ☆`8,332`
*   [easegress-io/easegress](https://github.com/easegress-io/easegress) — A Cloud Native traffic orchestration system ☆`5,865`
*   [flipt-io/flipt](https://github.com/flipt-io/flipt) — Enterprise-ready, Git native feature management solution ☆`4,637`
*   [charmbracelet/wish](https://github.com/charmbracelet/wish) — Make SSH apps, just like that! ☆`4,585`
*   [getfider/fider](https://github.com/getfider/fider) — Open platform to collect and prioritize feedback ☆`3,886`
*   [xyproto/algernon](https://github.com/xyproto/algernon) — Small self-contained pure-Go web server with Lua, Teal, Markdown, Ollama, HTTP/2, QUIC, Redis, SQLite and PostgreSQL support ++ ☆`2,958`
*   [openflagr/flagr](https://github.com/openflagr/flagr) — Flagr is a feature flagging, A/B testing and dynamic configuration microservice ☆`2,559`
*   [thomaspoignant/go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) — GO Feature Flag is a simple, complete and lightweight self-hosted feature flag solution 100% Open Source. ☆`1,855`
*   [openrundev/openrun](https://github.com/openrundev/openrun) — Open source alternative to Google Cloud Run and AWS App Runner. Easily deploy web apps declaratively. ☆`700`
*   [blind-oracle/cortex-tenant](https://github.com/blind-oracle/cortex-tenant) — Prometheus remote write proxy that adds Cortex/Mimir tenant ID based on metric labels ☆`127`
*   [baalimago/wd-41](https://github.com/baalimago/wd-41) — Web-Development 41, a static web server with live-reload ☆`149`
*   [rekby/lets-proxy2](https://github.com/rekby/lets-proxy2) — Reverse proxy with automatically obtains TLS certificates from Let's Encrypt ☆`100`

## Software Packages

### DevOps Tools

*   [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`118,767`
*   [moby/moby](https://github.com/moby/moby) — The Moby Project - a collaborative project for the container ecosystem to assemble container-based systems ☆`71,131`
*   [traefik/traefik](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`59,144`
*   [go-gitea/gitea](https://github.com/go-gitea/gitea) — Git with a cup of tea! Painless self-hosted all-in-one software development service, including Git hosting, code review, team collaboration, package registry and CI/CD ☆`52,131`
*   [kubernetes/minikube](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,163`
*   [k3s-io/k3s](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`31,385`
*   [grafana/k6](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`29,273`
*   [tsenart/vegeta](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`24,722`
*   [hashicorp/packer](https://github.com/hashicorp/packer) — Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. ☆`15,525`
*   [kubernetes-sigs/kind](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`14,774`
*   [kubeshark/kubeshark](https://github.com/kubeshark/kubeshark) — The API traffic analyzer for Kubernetes providing real-time K8s protocol-level visibility, capturing and monitoring all traffic and payloads going in, out and across containers, pods, nodes and clusters. Inspired by Wireshark, purposely built for Kubernetes ☆`11,566`
*   [moovweb/gvm](https://github.com/moovweb/gvm) — Go Version Manager ☆`11,407`
*   [flannel-io/flannel](https://github.com/flannel-io/flannel) — flannel is a network fabric for containers, designed for Kubernetes ☆`9,326`
*   [getanteon/anteon](https://github.com/getanteon/anteon) — Anteon (formerly Ddosify): eBPF-based Kubernetes Monitoring and Performance Testing ☆`8,537`
*   [ko-build/ko](https://github.com/ko-build/ko) — Build and deploy Go applications ☆`8,201`
*   [kubevela/kubevela](https://github.com/kubevela/kubevela) — The Modern Application Platform. ☆`7,606`
*   [bitfield/script](https://github.com/bitfield/script) — Making it easy to write shell-like scripts in Go ☆`6,882`
*   [codesenberg/bombardier](https://github.com/codesenberg/bombardier) — Fast cross-platform HTTP benchmarking tool written in Go ☆`6,636`
*   [k3d-io/k3d](https://github.com/k3d-io/k3d) — Little helper to run CNCF's k3s in Docker ☆`6,119`
*   [stefanprodan/podinfo](https://github.com/stefanprodan/podinfo) — Go microservice template for Kubernetes ☆`5,768`
*   [fleetdm/fleet](https://github.com/fleetdm/fleet) — Open device management ☆`5,761`
*   [taubyte/tau](https://github.com/taubyte/tau) — Fullstack Workspace for Humans & Machines ☆`4,799`
*   [pomerium/pomerium](https://github.com/pomerium/pomerium) — Pomerium is an identity and context-aware access proxy. ☆`4,532`
*   [peak/s5cmd](https://github.com/peak/s5cmd) — Parallel S3 and local filesystem execution tool. ☆`3,747`
*   [apecloud/kubeblocks](https://github.com/apecloud/kubeblocks) — KubeBlocks is a Kubernetes Operator designed to manage a variety of databases and streaming systems, including MySQL, PostgreSQL, MongoDB, Redis, RabbitMQ, RocketMQ, and more, within Kubernetes environments. ☆`2,903`
*   [aptly-dev/aptly](https://github.com/aptly-dev/aptly) — aptly - Debian repository management tool ☆`2,731`
*   [ajvb/kala](https://github.com/ajvb/kala) — Modern Job Scheduler ☆`2,160`
*   [gabrie30/ghorg](https://github.com/gabrie30/ghorg) — Quickly clone or backup an entire org/users repositories into one directory - Supports GitHub, GitLab, Bitbucket, and more ☆`1,888`
*   [sanbornm/go-selfupdate](https://github.com/sanbornm/go-selfupdate) — Enable your Go applications to self update ☆`1,651`
*   [yusufcanb/tlm](https://github.com/yusufcanb/tlm) — Local CLI Copilot, powered by Ollama. ☆`1,461`
*   [ovh/utask](https://github.com/ovh/utask) — µTask is an automation engine that models and executes business processes declared in yaml. ☆`1,336`
*   [pipe-cd/pipecd](https://github.com/pipe-cd/pipecd) — The One CD for All {applications, platforms, operations} ☆`1,229`
*   [kubenetworks/kubevpn](https://github.com/kubenetworks/kubevpn) — KubeVPN offers a Cloud Native Dev Environment that connects to kubernetes cluster network. ☆`1,255`
*   [KusionStack/kusion](https://github.com/KusionStack/kusion) — Declarative Intent Driven Platform Orchestrator for Internal Developer Platform (IDP). ☆`1,191`
*   [abahmed/kwatch](https://github.com/abahmed/kwatch) — monitor & detect crashes in your Kubernetes(K8s) cluster instantly ☆`990`
*   [TimothyYe/skm](https://github.com/TimothyYe/skm) — A simple and powerful SSH keys manager ☆`997`
*   [scaleway/scaleway-cli](https://github.com/scaleway/scaleway-cli) — Command Line Interface for Scaleway ☆`942`
*   [rogerwelin/cassowary](https://github.com/rogerwelin/cassowary) — Modern cross-platform HTTP load-testing tool written in Go ☆`810`
*   [kool-dev/kool](https://github.com/kool-dev/kool) — From local development to the cloud: web apps development with containers made easy. ☆`706`
*   [getanteon/alaz](https://github.com/getanteon/alaz) — Alaz: Advanced eBPF Agent for Kubernetes Observability – Effortlessly monitor K8s service interactions and performance metrics in your K8s environment. Gain in-depth insights with service maps, metrics, and more, while staying alert to crucial system anomalies ☆`709`
*   [oxyno-zeta/s3-proxy](https://github.com/oxyno-zeta/s3-proxy) — S3 Reverse Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth) ☆`417`
*   [kevincobain2000/gobrew](https://github.com/kevincobain2000/gobrew) — Go version manager, written in Go. Super simple tool to install and manage Go versions. Install go without root. Gobrew doesn't require shell rehash. ☆`407`
*   [jenkins-zh/jenkins-cli](https://github.com/jenkins-zh/jenkins-cli) — Jenkins CLI allows you to manage your Jenkins in an easy way ☆`405`
*   [appleboy/easyssh-proxy](https://github.com/appleboy/easyssh-proxy) — easyssh-proxy provides a simple implementation of some SSH protocol features in Go ☆`341`
*   [xitonix/trubka](https://github.com/xitonix/trubka) — A CLI tool for Kafka ☆`337`
*   [emicklei/mora](https://github.com/emicklei/mora) — MongoDB generic REST server in Go ☆`316`
*   [thevxn/dish](https://github.com/thevxn/dish) — A lightweight, remotely configurable monitoring service. ☆`260`
*   [appleboy/drone-scp](https://github.com/appleboy/drone-scp) — Copy files and artifacts via SSH using a binary, docker or Drone CI. ☆`162`
*   [datarootsio/tf-profile](https://github.com/datarootsio/tf-profile) — CLI tool to profile Terraform runs, written in Go ☆`162`
*   [jkaninda/goma-gateway](https://github.com/jkaninda/goma-gateway) — Goma Gateway – Lightweight, High-Performance API Gateway and Reverse Proxy with declarative config, robust middleware, and support for REST, GraphQL, TCP, UDP, and gRPC. ☆`136`
*   [s0rg/decompose](https://github.com/s0rg/decompose) — Reverse-engineering tool for docker environments ☆`116`
*   [x1unix/docker-go-mingw](https://github.com/x1unix/docker-go-mingw) — Docker image for building Go binaries with MinGW toolchain. Supports Windows on ARM! ☆`53`
*   [appleboy/drone-jenkins](https://github.com/appleboy/drone-jenkins) — Drone plugin for trigger Jenkins jobs. ☆`38`

### Other Software

*   [schollz/croc](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`32,069`
*   [restic/restic](https://github.com/restic/restic) — Fast, secure, efficient backup program ☆`30,910`
*   [seaweedfs/seaweedfs](https://github.com/seaweedfs/seaweedfs) — SeaweedFS is a fast distributed storage system for blobs, objects, files, and data lake, for billions of files! Blob store has O(1) disk seek, cloud tiering. Filer supports Cloud Drive, xDC replication, Kubernetes, POSIX FUSE mount, S3 API, S3 Gateway, Hadoop, WebDAV, encryption, Erasure Coding. Enterprise version is at seaweedfs.com. ☆`27,505`
*   [juicedata/juicefs](https://github.com/juicedata/juicefs) — JuiceFS is a distributed POSIX file system built on top of Redis and S3. ☆`12,441`
*   [Shopify/toxiproxy](https://github.com/Shopify/toxiproxy) — A TCP proxy to simulate network and system conditions for chaos and resiliency testing ☆`11,683`
*   [visualfc/liteide](https://github.com/visualfc/liteide) — LiteIDE is a simple, open source, cross-platform Go IDE. ☆`7,723`
*   [boyter/scc](https://github.com/boyter/scc) — Sloc, Cloc and Code: scc is a very fast accurate code counter with complexity calculations and COCOMO estimates written in pure Go ☆`7,805`
*   [0xERR0R/blocky](https://github.com/0xERR0R/blocky) — Fast and lightweight DNS proxy as ad-blocker for local network with many features ☆`5,755`
*   [fogleman/nes](https://github.com/fogleman/nes) — NES emulator written in Go. ☆`5,623`
*   [gilbertchen/duplicacy](https://github.com/gilbertchen/duplicacy) — A new generation cloud backup tool ☆`5,562`
*   [Forceu/Gokapi](https://github.com/Forceu/Gokapi) — Lightweight selfhosted Firefox Send alternative without public upload. AWS S3 supported. ☆`2,432`
*   [documize/community](https://github.com/documize/community) — Modern Confluence alternative designed for internal & external docs, built with Go + EmberJS ☆`2,338`
*   [go-sonic/sonic](https://github.com/go-sonic/sonic) — Sonic is a blogging platform developed by Go. Simple and powerful ☆`2,113`
*   [root-gg/plik](https://github.com/root-gg/plik) — Plik is a temporary file upload system (Wetransfer like) in Go. ☆`1,669`
*   [SpatiumPortae/portal](https://github.com/SpatiumPortae/portal) — Portal is a quick and easy command-line file transfer utility from any computer to another ☆`1,707`
*   [msoap/shell2http](https://github.com/msoap/shell2http) — Executing shell commands via HTTP server ☆`1,453`
*   [pointlander/peg](https://github.com/pointlander/peg) — Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. ☆`1,089`
*   [janpfeifer/gonb](https://github.com/janpfeifer/gonb) — GoNB, a Go Notebook Kernel for Jupyter ☆`955`
*   [shurcooL/Go-Package-Store](https://github.com/shurcooL/Go-Package-Store) — An app that displays updates for the Go packages in your GOPATH. ☆`897`
*   [alajmo/sake](https://github.com/alajmo/sake) — task runner for local and remote hosts ☆`736`
*   [chapar-rest/chapar](https://github.com/chapar-rest/chapar) — Chapar is a simple and easy to use api testing tools aims to help developers to test their api endpoints. it support http and grpc protocols. ☆`657`
*   [goccmack/gocc](https://github.com/goccmack/gocc) — Parser / Scanner Generator ☆`651`
*   [moshebe/gebug](https://github.com/moshebe/gebug) — Debug Dockerized Go applications better ☆`635`
*   [edwingeng/hotswap](https://github.com/edwingeng/hotswap) — A complete solution to reload your go code without restarting your server, interrupting or blocking any ongoing procedure. ☆`413`
*   [s0rg/crawley](https://github.com/s0rg/crawley) — The unix-way web crawler ☆`319`
*   [marwanhawari/stew](https://github.com/marwanhawari/stew) — An independent package manager for compiled binaries. ☆`311`
*   [mk-5/fjira](https://github.com/mk-5/fjira) — The golang fuzzy-find cli jira interface ☆`244`
*   [assafmo/joincap](https://github.com/assafmo/joincap) — Merge multiple pcap files together, gracefully. ☆`220`
*   [lingrino/vaku](https://github.com/lingrino/vaku) — vaku extends the vault api & cli ☆`158`
*   [DMcP89/tinycare-tui](https://github.com/DMcP89/tinycare-tui) — TUI application written in GO inspired by tiny-care-terminal ☆`16`

## Stream Processing

*   [reugn/go-streams](https://github.com/reugn/go-streams) — A lightweight stream processing library for Go ☆`2,130`
*   [Breeze0806/go-etl](https://github.com/Breeze0806/go-etl) — go-etl is a toolset for data extraction, transformation and loading. ☆`178`
*   [mariomac/gostream](https://github.com/mariomac/gostream) — A Go port of the Java Streams API. Type-safe and functional Go Streams processing ☆`170`
*   [whitaker-io/machine](https://github.com/whitaker-io/machine) — Machine is a workflow/pipeline library for processing data ☆`163`
*   [rulego/streamsql](https://github.com/rulego/streamsql) — Lightweight SQL-based stream processing engine for IoT edge. ☆`50`

## Style Guides

*   [bahlo/go-styleguide](https://github.com/bahlo/go-styleguide) — Opinionated Styleguide for the Go language ☆`1,629`

## Template Engines

*   [a-h/templ](https://github.com/a-h/templ) — A language for writing HTML user interfaces in Go. ☆`9,831`
*   [valyala/quicktemplate](https://github.com/valyala/quicktemplate) — Fast, powerful, yet easy to use template engine for Go. Optimized for speed, zero memory allocations in hot paths. Up to 20x faster than html/template ☆`3,282`
*   [johnfercher/maroto](https://github.com/johnfercher/maroto) — A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple. ☆`2,575`
*   [CloudyKit/jet](https://github.com/CloudyKit/jet) — Jet template engine ☆`1,368`
*   [osteele/liquid](https://github.com/osteele/liquid) — A Liquid template engine in Go ☆`327`
*   [go-sprout/sprout](https://github.com/go-sprout/sprout) — From sprig to sprout - Useful template functions for Go templates with steroids ☆`189`
*   [robfig/soy](https://github.com/robfig/soy) — Go implementation for Soy templates (Google Closure templates) ☆`177`
*   [goradd/got](https://github.com/goradd/got) — GoT is a template engine that turns templates into Go code to compile into your app. ☆`38`

## Testing

### Fail injection

*   [pingcap/failpoint](https://github.com/pingcap/failpoint) — An implementation of failpoints for Golang. ☆`868`

### Fuzzing

*   [dvyukov/go-fuzz](https://github.com/dvyukov/go-fuzz) — Randomized testing for Go ☆`4,836`

### Mock

*   [vektra/mockery](https://github.com/vektra/mockery) — A mock code autogenerator for Go ☆`6,880`
*   [DATA-DOG/go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) — Sql mock driver for golang to test database interactions ☆`6,485`
*   [uber-go/mock](https://github.com/uber-go/mock) — GoMock is a mocking framework for the Go programming language. ☆`3,175`
*   [SpectoLabs/hoverfly](https://github.com/SpectoLabs/hoverfly) — Lightweight service virtualization/ API simulation / API mocking tool for developers and testers ☆`2,453`
*   [matryer/moq](https://github.com/matryer/moq) — Interface mocking tool for go generate ☆`2,159`
*   [jarcoal/httpmock](https://github.com/jarcoal/httpmock) — HTTP mocking for Golang ☆`2,066`
*   [maxbrunsfeld/counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) — A tool for generating self-contained, type-safe test doubles in go ☆`1,104`
*   [gojuno/minimock](https://github.com/gojuno/minimock) — Powerful mock generation tool for Go programming language ☆`741`
*   [DATA-DOG/go-txdb](https://github.com/DATA-DOG/go-txdb) — Immutable transaction isolated sql driver for golang ☆`738`
*   [pashagolub/pgxmock](https://github.com/pashagolub/pgxmock) — pgx mock driver for golang to test database interactions ☆`537`
*   [xhd2015/xgo](https://github.com/xhd2015/xgo) — All-in-one go testing library ☆`428`
*   [seborama/govcr](https://github.com/seborama/govcr) — HTTP mock for Golang: record and replay HTTP/HTTPS interactions for offline testing ☆`196`
*   [elgohr/go-localstack](https://github.com/elgohr/go-localstack) — Go Wrapper for using localstack ☆`84`

### Selenium and browser control tools

*   [chromedp/chromedp](https://github.com/chromedp/chromedp) — A faster, simpler way to drive browsers supporting the Chrome DevTools Protocol. ☆`12,483`
*   [go-rod/rod](https://github.com/go-rod/rod) — A Chrome DevTools Protocol driver for web automation and scraping. ☆`6,427`
*   [playwright-community/playwright-go](https://github.com/playwright-community/playwright-go) — Playwright for Go a browser automation library to control Chromium, Firefox and WebKit with a single API. ☆`3,030`
*   [mafredri/cdp](https://github.com/mafredri/cdp) — Package cdp provides type-safe bindings for the Chrome DevTools Protocol (CDP), written in the Go programming language. ☆`768`

### Testing Frameworks

*   [stretchr/testify](https://github.com/stretchr/testify) — A toolkit with common assertions and mocks that plays nicely with the standard library ☆`25,458`
*   [keploy/keploy](https://github.com/keploy/keploy) — API, Integration, E2E Testing Agent for Developers that actually work. Generate tests, mocks/stubs for your APIs! ☆`12,939`
*   [testcontainers/testcontainers-go](https://github.com/testcontainers/testcontainers-go) — Testcontainers for Go is a Go package that makes it simple to create and clean up container-based dependencies for automated integration/smoke tests. The clean, easy-to-use API enables developers to programmatically define containers that should be run as part of a test and clean up those resources when the test is done. ☆`4,498`
*   [google/go-cmp](https://github.com/google/go-cmp) — Package for comparing Go values in tests ☆`4,549`
*   [gavv/httpexpect](https://github.com/gavv/httpexpect) — End-to-end HTTP and REST API testing for Go. ☆`2,689`
*   [cucumber/godog](https://github.com/cucumber/godog) — Cucumber for golang ☆`2,547`
*   [orlangure/gnomock](https://github.com/orlangure/gnomock) — Test your code without writing mocks with ephemeral Docker containers Setup popular services with just a couple lines of code No bash, no yaml, only code ☆`1,469`
*   [dnaeon/go-vcr](https://github.com/dnaeon/go-vcr) — Record and replay your HTTP interactions for fast, deterministic and accurate tests ☆`1,343`
*   [go-testfixtures/testfixtures](https://github.com/go-testfixtures/testfixtures) — Ruby on Rails like test fixtures for Go. Write tests against a real database ☆`1,201`
*   [fergusstrange/embedded-postgres](https://github.com/fergusstrange/embedded-postgres) — Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test ☆`1,078`
*   [gotestyourself/gotest.tools](https://github.com/gotestyourself/gotest.tools) — A collection of packages to augment the go testing package and support common patterns. ☆`573`
*   [maxatome/go-testdeep](https://github.com/maxatome/go-testdeep) — Extremely flexible golang deep comparison, extends the go testing package, tests HTTP APIs and provides tests suite ☆`455`
*   [appleboy/gofight](https://github.com/appleboy/gofight) — Testing API Handler written in Golang. ☆`445`
*   [viant/endly](https://github.com/viant/endly) — End to end functional test and automation framework ☆`268`
*   [ysmood/got](https://github.com/ysmood/got) — An enjoyable golang test framework. ☆`269`
*   [adamluzsi/testcase](https://github.com/adamluzsi/testcase) — testcase is an opinionated testing framework to support test driven design. ☆`126`
*   [earthboundkid/be](https://github.com/earthboundkid/be) — The Go test helper for minimalists ☆`124`
*   [kinbiko/jsonassert](https://github.com/kinbiko/jsonassert) — A Go test assertion library for verifying that two representations of JSON are semantically equal ☆`140`
*   [corbym/gocrest](https://github.com/corbym/gocrest) — GoCrest - Hamcrest-like matchers for Go ☆`106`
*   [hedhyw/gherkingen](https://github.com/hedhyw/gherkingen) — Behaviour Driven Development tests generator for Golang ☆`89`
*   [madflojo/testcerts](https://github.com/madflojo/testcerts) — Dynamically generate self-signed certificates and certificate authorities for Go tests ☆`82`
*   [go-restit/restit](https://github.com/go-restit/restit) — A Go library help testing your RESTful API application ☆`55`
*   [rekby/fixenv](https://github.com/rekby/fixenv) —  ☆`33`
*   [viant/dsunit](https://github.com/viant/dsunit) — Datastore Testibility ☆`45`
*   [abecodes/dft](https://github.com/abecodes/dft) — Docker For Testing is a zero dependency wrapper around the `docker` command. ☆`18`

## Text Processing

### Formatters

*   [dustin/go-humanize](https://github.com/dustin/go-humanize) — Go Humans! (formatters for units to human friendly sizes) ☆`4,715`
*   [neilotoole/sq](https://github.com/neilotoole/sq) — sq data wrangler ☆`2,362`
*   [ianlopshire/go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) — Encoding and decoding for fixed-width formatted data ☆`87`
*   [bojanz/address](https://github.com/bojanz/address) — Address handling for Go. ☆`82`

### Markup Languages

*   [BurntSushi/toml](https://github.com/BurntSushi/toml) — TOML parser for Golang with reflection. ☆`4,843`
*   [yuin/goldmark](https://github.com/yuin/goldmark) — A markdown parser written in Go. Easy to extend, standard(CommonMark) compliant, well structured. ☆`4,421`
*   [JohannesKaufmann/html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) — Convert HTML to Markdown. Even works with entire websites and can be extended through rules. ☆`3,206`
*   [pelletier/go-toml](https://github.com/pelletier/go-toml) — Go library for the TOML file format ☆`1,880`
*   [antchfx/htmlquery](https://github.com/antchfx/htmlquery) — htmlquery is golang XPath package for HTML query. ☆`773`
*   [clbanning/mxj](https://github.com/clbanning/mxj) — Decode / encode XML to/from map\[string]interface{} (or JSON); extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. ☆`630`
*   [mmalcek/bafi](https://github.com/mmalcek/bafi) — Universal JSON, BSON, YAML, CSV, XML, mt940 converter with templates ☆`110`
*   [drewstinnett/gout](https://github.com/drewstinnett/gout) — Output go objects in standard formats, such as YAML, JSON, etc ☆`18`

### Parsers/Encoders/Decoders

*   [mvdan/sh](https://github.com/mvdan/sh) — A shell parser, formatter, and interpreter with bash support; includes shfmt ☆`8,246`
*   [mmcdole/gofeed](https://github.com/mmcdole/gofeed) — Parse RSS, Atom and JSON feeds in Go ☆`2,777`
*   [google/go-querystring](https://github.com/google/go-querystring) — go-querystring is Go library for encoding structs into URL query strings. ☆`2,110`
*   [olebedev/when](https://github.com/olebedev/when) — A natural language date/time parser with pluggable rules ☆`1,453`
*   [adrianmo/go-nmea](https://github.com/adrianmo/go-nmea) — A NMEA parser library in pure Go ☆`251`
*   [yassinebenaid/godump](https://github.com/yassinebenaid/godump) — Dump any GO variable with ease ☆`222`
*   [editorconfig/editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) — EditorConfig Core written in Go ☆`149`
*   [bzick/tokenizer](https://github.com/bzick/tokenizer) — Tokenizer (lexer) for golang ☆`136`
*   [emersion/go-vcard](https://github.com/emersion/go-vcard) — A Go library to parse and format vCard ☆`122`
*   [polera/gonameparts](https://github.com/polera/gonameparts) — Takes a full name and splits it into individual name parts ☆`43`

### Regular Expressions

*   [hedhyw/rex](https://github.com/hedhyw/rex) — Flexible regular expressions constructor for Golang. ☆`210`
*   [IGLOU-EU/go-wildcard](https://github.com/IGLOU-EU/go-wildcard) — Fast and light wildcard pattern matching. ☆`96`

### Sanitation

*   [microcosm-cc/bluemonday](https://github.com/microcosm-cc/bluemonday) — bluemonday: a fast golang HTML sanitizer (inspired by the OWASP Java HTML Sanitizer) to scrub user generated content of XSS ☆`3,566`
*   [JoshuaDoes/gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) — A sanitization-based swear filter for Go. ☆`68`

### Scrapers

*   [gocolly/colly](https://github.com/gocolly/colly) — Elegant Scraper and Crawler Framework for Golang ☆`24,834`
*   [PuerkitoBio/goquery](https://github.com/PuerkitoBio/goquery) — A little like that j-thing, only in Go. ☆`14,803`
*   [mvdan/xurls](https://github.com/mvdan/xurls) — Extract urls from text ☆`1,237`
*   [zoomio/tagify](https://github.com/zoomio/tagify) — Tagify produces a set of tags from a given source. Source can be either an HTML page, a Markdown document or a plain text. Supports English, Russian, Chinese, Hindi, Spanish, Arabic, Japanese, German, Hebrew, French and Korean languages. ☆`41`

### Utility/Miscellaneous

*   [arunsupe/semantic-grep](https://github.com/arunsupe/semantic-grep) — grep for words with similar meaning to the query ☆`1,188`
*   [mattn/go-runewidth](https://github.com/mattn/go-runewidth) — wcwidth for golang ☆`668`
*   [striker2000/petrovich](https://github.com/striker2000/petrovich) — Golang port of Petrovich - an inflector for Russian anthroponyms. ☆`51`

## Third-party APIs

*   [google/go-github](https://github.com/google/go-github) — Go library for accessing the GitHub v3 API ☆`11,024`
*   [sashabaranov/go-openai](https://github.com/sashabaranov/go-openai) — OpenAI ChatGPT, GPT-5, GPT-Image-1, Whisper API clients for Go ☆`10,413`
*   [bwmarrin/discordgo](https://github.com/bwmarrin/discordgo) — (Golang) Go bindings for Discord ☆`5,667`
*   [slack-go/slack](https://github.com/slack-go/slack) — Slack API in Go ☆`4,867`
*   [googleapis/google-cloud-go](https://github.com/googleapis/google-cloud-go) — Google Cloud Client Libraries for Go. ☆`4,371`
*   [googleapis/google-api-go-client](https://github.com/googleapis/google-api-go-client) — Auto-generated Google APIs for Go. ☆`4,355`
*   [aws/aws-sdk-go-v2](https://github.com/aws/aws-sdk-go-v2) — AWS SDK for the Go programming language. ☆`3,364`
*   [minio/minio-go](https://github.com/minio/minio-go) — MinIO Go client SDK for S3 compatible object storage ☆`2,859`
*   [stripe/stripe-go](https://github.com/stripe/stripe-go) — Go library for the Stripe API. ☆`2,455`
*   [huandu/facebook](https://github.com/huandu/facebook) — A Facebook Graph API SDK For Go. ☆`1,420`
*   [shurcooL/githubv4](https://github.com/shurcooL/githubv4) — client library for accessing GitHub GraphQL API v4 ☆`1,175`
*   [ChimeraCoder/anaconda](https://github.com/ChimeraCoder/anaconda) — A Go client library for the Twitter 1.1 API ☆`1,143`
*   [go-playground/webhooks](https://github.com/go-playground/webhooks) — Webhook receiver for GitHub, Bitbucket, GitLab, Gogs ☆`1,013`
*   [plutov/paypal](https://github.com/plutov/paypal) — Golang client for PayPal REST API ☆`764`
*   [codingsince1985/geo-golang](https://github.com/codingsince1985/geo-golang) — Go library to access geocoding and reverse geocoding APIs ☆`538`
*   [chyroc/lark](https://github.com/chyroc/lark) — Lark Open API Go SDK, Support ALL Open API and Event Callback ☆`457`
*   [otiai10/openaigo](https://github.com/otiai10/openaigo) — OpenAI GPT3/3.5 and GPT4 ChatGPT API Client Library for Go, simple, less dependencies, and well-tested ☆`301`
*   [onrik/ethrpc](https://github.com/onrik/ethrpc) — Golang client for ethereum json rpc api ☆`277`
*   [go-lark/lark](https://github.com/go-lark/lark) — An easy-to-use SDK for Feishu and Lark Open Platform (Instant Messaging API only) ☆`231`
*   [adlio/trello](https://github.com/adlio/trello) — Trello API wrapper for Go ☆`226`
*   [ctreminiom/go-atlassian](https://github.com/ctreminiom/go-atlassian) — Golang Client Library for Atlassian Cloud. ☆`188`
*   [rhnvrm/simples3](https://github.com/rhnvrm/simples3) — Simple no frills AWS S3 Golang Library using REST with V4 Signing (without AWS Go SDK) ☆`178`
*   [wit-ai/wit-go](https://github.com/wit-ai/wit-go) — Go client for wit.ai HTTP API ☆`170`
*   [koltyakov/gosip](https://github.com/koltyakov/gosip) — SharePoint SDK for Go ☆`165`
*   [gregdel/pushover](https://github.com/gregdel/pushover) — Go wrapper for the Pushover API ☆`152`
*   [cyruzin/golang-tmdb](https://github.com/cyruzin/golang-tmdb) — This is a Golang wrapper for working with TMDb API. It aims to support version 3. ☆`145`
*   [andygrunwald/go-trending](https://github.com/andygrunwald/go-trending) — Go library for accessing trending repositories and developers at Github. ☆`146`
*   [andygrunwald/go-gerrit](https://github.com/andygrunwald/go-gerrit) — Go client/library for Gerrit Code Review ☆`102`
*   [switchupcb/disgo](https://github.com/switchupcb/disgo) — Disgo is the next generation of Discord API Consumption. Create a Discord Bot with Go using this Discord API Wrapper (SDK Client). ☆`107`
*   [mvrilo/go-redoc](https://github.com/mvrilo/go-redoc) — go-redoc is an embedded OpenAPI/Swagger documentation ui for Go using ReDoc ☆`94`
*   [FreeLeh/GoFreeDB](https://github.com/FreeLeh/GoFreeDB) — GoFreeDB is a Golang library that provides common and simple database abstractions on top of Google Sheets. ☆`88`
*   [mehanizm/airtable](https://github.com/mehanizm/airtable) — Simple golang airtable API wrapper ☆`82`
*   [brunomvsouza/ynab.go](https://github.com/brunomvsouza/ynab.go) — Go client for the YNAB API. Unofficial. It covers 100% of the resources made available by the YNAB API. ☆`77`
*   [k-capehart/go-salesforce](https://github.com/k-capehart/go-salesforce) — Salesforce REST API client written in Go ☆`51`
*   [rapito/go-spotify](https://github.com/rapito/go-spotify) — Go library for the Spotify Web API ☆`50`
*   [rinchsan/device-check-go](https://github.com/rinchsan/device-check-go) — iOS DeviceCheck SDK for Go - query and modify the per-device bits ☆`25`
*   [zc2638/swag](https://github.com/zc2638/swag) — No comments, simple go wrapper to create swagger 2.0 compatible APIs. Support most routing frameworks, such as built-in, gin, chi, mux, echo, httprouter, fasthttp and more. ☆`50`
*   [chainifynet/aws-encryption-sdk-go](https://github.com/chainifynet/aws-encryption-sdk-go) — AWS Encryption SDK for Go ☆`21`
*   [sostronk/go-steam](https://github.com/sostronk/go-steam) — Go library for querying Source servers ☆`33`
*   [Icelain/jokeapi](https://github.com/Icelain/jokeapi) — Official golang wrapper for Sv443's jokeapi. ☆`26`
*   [circa10a/go-aws-news](https://github.com/circa10a/go-aws-news) — Go app + library to fetch what's new from AWS ☆`17`
*   [staskobzar/goami2](https://github.com/staskobzar/goami2) — Simple Asterisk Manager Interface (AMI) library fo golang ☆`20`

## Utilities

*   [junegunn/fzf](https://github.com/junegunn/fzf) — A command-line fuzzy finder ☆`75,287`
*   [wagoodman/dive](https://github.com/wagoodman/dive) — A tool for exploring each layer in a docker image ☆`52,663`
*   [samber/lo](https://github.com/samber/lo) — A Lodash-style Go library based on Go 1.18+ Generics (map, filter, contains, find...) ☆`20,647`
*   [jmoiron/sqlx](https://github.com/jmoiron/sqlx) — general purpose extensions to golang's database/sql ☆`17,353`
*   [goreleaser/goreleaser](https://github.com/goreleaser/goreleaser) — Release engineering, simplified ☆`15,286`
*   [xo/usql](https://github.com/xo/usql) — Universal command-line interface for SQL databases ☆`9,602`
*   [cilium/ebpf](https://github.com/cilium/ebpf) — ebpf-go is a pure-Go library to read, modify and load eBPF programs and attach them to various hooks in the Linux kernel. ☆`7,285`
*   [duke-git/lancet](https://github.com/duke-git/lancet) — A comprehensive, efficient, and reusable util function library of Go. ☆`5,226`
*   [dropbox/godropbox](https://github.com/dropbox/godropbox) — Common libraries for writing Go services/applications. ☆`4,200`
*   [tdewolff/minify](https://github.com/tdewolff/minify) — Go minifiers for web formats ☆`4,022`
*   [maruel/panicparse](https://github.com/maruel/panicparse) — Crash your app in style (Golang) ☆`3,709`
*   [minio/mc](https://github.com/minio/mc) — Unix like utilities for object store ☆`3,268`
*   [darccio/mergo](https://github.com/darccio/mergo) — Mergo: merging Go structs and maps since 2013 ☆`3,066`
*   [avast/retry-go](https://github.com/avast/retry-go) — Simple golang library for retry mechanism ☆`2,834`
*   [create-go-app/cli](https://github.com/create-go-app/cli) — A complete and self-contained solution for developers of any qualification to create a production-ready project with backend (Go), frontend (JavaScript, TypeScript) and deploy automation (Ansible, Docker) by running only one CLI command. ☆`2,730`
*   [megaease/easeprobe](https://github.com/megaease/easeprobe) — A simple, standalone, and lightweight tool that can do health/status checking, written in Go. ☆`2,279`
*   [failsafe-go/failsafe-go](https://github.com/failsafe-go/failsafe-go) — Fault tolerance and resilience patterns for Go ☆`2,019`
*   [gabriel-vasile/mimetype](https://github.com/gabriel-vasile/mimetype) — A fast Golang library for media type and file extension detection, based on magic numbers ☆`1,896`
*   [georgysavva/scany](https://github.com/georgysavva/scany) — Library for scanning data from a database into Go structs and more ☆`1,481`
*   [joshmedeski/sesh](https://github.com/joshmedeski/sesh) — Smart session manager for the terminal ☆`1,449`
*   [goforj/godump](https://github.com/goforj/godump) — A minimal, developer-friendly pretty-printer and debug dumper for Go structs, inspired by Laravel’s dump() and Symfony’s VarDumper. ☆`1,356`
*   [itchyny/bed](https://github.com/itchyny/bed) — Binary editor written in Go ☆`1,340`
*   [rubyist/circuitbreaker](https://github.com/rubyist/circuitbreaker) — Circuit Breakers in Go ☆`1,163`
*   [owenthereal/upterm](https://github.com/owenthereal/upterm) — Instant Terminal Sharing ☆`1,052`
*   [miniscruff/changie](https://github.com/miniscruff/changie) — Automated changelog tool for preparing releases with lots of customization options ☆`815`
*   [immortal/immortal](https://github.com/immortal/immortal) — A \*nix cross-platform (OS agnostic) supervisor ☆`827`
*   [cep21/circuit](https://github.com/cep21/circuit) — An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. ☆`791`
*   [jonboulle/clockwork](https://github.com/jonboulle/clockwork) — a fake clock for golang ☆`718`
*   [derekparker/delve](https://github.com/derekparker/delve) — Delve is a debugger for the Go programming language. ☆`660`
*   [Unrud/remote-touchpad](https://github.com/Unrud/remote-touchpad) — Control mouse and keyboard from a smartphone ☆`634`
*   [alajmo/mani](https://github.com/alajmo/mani) — CLI tool to help you manage repositories ☆`627`
*   [cristianoliveira/ergo](https://github.com/cristianoliveira/ergo) — The management of multiple apps running over different ports made easy ☆`641`
*   [blockloop/scan](https://github.com/blockloop/scan) — Tiny lib to scan SQL rows directly to structs, slices, and primitive types ☆`606`
*   [mennanov/limiters](https://github.com/mennanov/limiters) — Golang rate limiters for distributed applications ☆`600`
*   [htcat/htcat](https://github.com/htcat/htcat) — Parallel and Pipelined HTTP GET Utility ☆`556`
*   [ungerik/go-dry](https://github.com/ungerik/go-dry) — DRY (don't repeat yourself) package for Go ☆`487`
*   [biter777/countries](https://github.com/biter777/countries) — Countries - ISO-639, ISO-3166 countries codes with subdivisions and names, ISO-4217 currency designators, ITU-T E.164 IDD phone codes, countries capitals, UN M.49 codes, IANA ccTLD countries domains, FIPS, IOC/NOC and FIFA codes, VERY VERY FAST, compatible with Databases/JSON/BSON/GOB/XML/CSV, Emoji countries flags and currencies, Unicode CLDR. ☆`490`
*   [Boeing/config-file-validator](https://github.com/Boeing/config-file-validator) — Cross Platform tool to validate configuration files ☆`439`
*   [gotranspile/cxgo](https://github.com/gotranspile/cxgo) — Tool for transpiling C to Go. ☆`375`
*   [ferama/rospo](https://github.com/ferama/rospo) — Effortless persistent SSH tunnels with embedded server for seamless connectivity ☆`351`
*   [kamilsk/retry](https://github.com/kamilsk/retry) — The most advanced interruptible mechanism to perform actions repetitively until successful. ☆`345`
*   [subosito/gotenv](https://github.com/subosito/gotenv) — Load environment variables from `.env` or `io.Reader` in Go. ☆`307`
*   [chenquan/diskusage](https://github.com/chenquan/diskusage) — A tool for showing disk usage(Linux, MacOS and Windows), it is a very fast utility to find largest directories or files. ☆`297`
*   [reugn/wifiqr](https://github.com/reugn/wifiqr) — Create a QR code with your Wi-Fi login details ☆`280`
*   [ikeikeikeike/go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) — go-sitemap-generator is the easiest way to generate Sitemaps in Go ☆`226`
*   [viant/toolbox](https://github.com/viant/toolbox) — Toolbox - go utility library ☆`227`
*   [hedhyw/json-log-viewer](https://github.com/hedhyw/json-log-viewer) — Interactive viewer for JSON logs. ☆`184`
*   [webriots/rate](https://github.com/webriots/rate) — A high-performance rate limiter library for Go applications ☆`162`
*   [antham/chyle](https://github.com/antham/chyle) — Changelog generator : use a git repository and various data sources and publish the result on external services ☆`159`
*   [maja42/goval](https://github.com/maja42/goval) — Expression evaluation in golang ☆`172`
*   [gookit/filter](https://github.com/gookit/filter) — Provide filtering, sanitizing, and conversion of Golang data ☆`149`
*   [commander-cli/cmd](https://github.com/commander-cli/cmd) — A simple package to execute shell commands on linux, windows and osx ☆`160`
*   [jfcg/sorty](https://github.com/jfcg/sorty) — Fast Concurrent / Parallel Sorting in Go ☆`142`
*   [knbr13/gitcs](https://github.com/knbr13/gitcs) — Command line tool written in Go. It allows developers to scan their local Git repositories and generate a visual contributions graph. ☆`126`
*   [syntaqx/cookie](https://github.com/syntaqx/cookie) — Cookies, but with structs, for happiness. ☆`110`
*   [jaschaephraim/lrserver](https://github.com/jaschaephraim/lrserver) — LiveReload server for Go \[golang] ☆`129`
*   [karl-cardenas-coding/go-lambda-cleanup](https://github.com/karl-cardenas-coding/go-lambda-cleanup) — go-lambda-cleanup - A solution for removing previous versions of AWS Lambdas ☆`96`
*   [reugn/equalizer](https://github.com/reugn/equalizer) — A set of performant rate limiters for Go ☆`91`
*   [arthurkushman/pgo](https://github.com/arthurkushman/pgo) — Go library for PHP community with convenient functions ☆`88`
*   [VividCortex/pm](https://github.com/VividCortex/pm) — Processlist manager with TCP listener ☆`79`
*   [tiendc/gofn](https://github.com/tiendc/gofn) — High performance utility functions using Generics ☆`52`
*   [icza/backscanner](https://github.com/icza/backscanner) — A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. ☆`69`
*   [antham/ghokin](https://github.com/antham/ghokin) — Parallelized formatter with no external dependencies for gherkin (cucumber, behat...) ☆`49`
*   [xorcare/pointer](https://github.com/xorcare/pointer) — Helper routines for simplifying the creation of optional fields of basic type. ☆`47`
*   [antham/yogo](https://github.com/antham/yogo) — Check yopmail mails from command line. ☆`46`
*   [asticode/go-astitodo](https://github.com/asticode/go-astitodo) — Parse TODOs in your GO code ☆`66`
*   [wroge/scan](https://github.com/wroge/scan) — scan sql rows into any type powered by generics ☆`67`
*   [shockerli/cvt](https://github.com/shockerli/cvt) — Easy and safe convert any value to another type in Go ☆`53`
*   [kazhuravlev/git-tools](https://github.com/kazhuravlev/git-tools) — Useful set of tools which helps to manage git tags ☆`33`
*   [piglig/go-qr](https://github.com/piglig/go-qr) — A native, high-quality and minimalistic QR code generator ☆`45`
*   [borovikovd/gomsort](https://github.com/borovikovd/gomsort) — Go msort - linter that sorts methods ☆`26`
*   [ik5/gostrutils](https://github.com/ik5/gostrutils) — Collections of string utils I have created over the years ☆`48`
*   [mikekonan/go-types](https://github.com/mikekonan/go-types) — Library providing opanapi3 and Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types. ☆`22`
*   [floatdrop/debounce](https://github.com/floatdrop/debounce) — A zero-allocation debouncer ☆`34`
*   [kazhuravlev/just](https://github.com/kazhuravlev/just) — Collection of useful functions. Complete simple tasks faster! ☆`37`
*   [nikolaydubina/watchhttp](https://github.com/nikolaydubina/watchhttp) — Run command periodically and expose latest STDOUT as HTTP endpoint ☆`35`
*   [skovtunenko/graterm](https://github.com/skovtunenko/graterm) — Provides primitives to perform ordered GRAceful TERmination for Golang applications ☆`29`
*   [kazhuravlev/healthcheck](https://github.com/kazhuravlev/healthcheck) — Readiness probes for Kubernetes application ☆`22`

## UUID

*   [google/uuid](https://github.com/google/uuid) — Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services. ☆`5,892`
*   [oklog/ulid](https://github.com/oklog/ulid) — Universally Unique Lexicographically Sortable Identifier (ULID) in Go ☆`4,903`
*   [gofrs/uuid](https://github.com/gofrs/uuid) — A UUID package for Go ☆`1,746`
*   [edwingeng/wuid](https://github.com/edwingeng/wuid) — An extremely fast globally unique number generator. ☆`544`
*   [sdrapkin/guid](https://github.com/sdrapkin/guid) — Fast cryptographically safe Guid generator for Go ☆`73`
*   [twharmon/gouid](https://github.com/twharmon/gouid) — Fast, dependable universally unique ids ☆`26`

## Validation

*   [go-playground/validator](https://github.com/go-playground/validator) — Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving ☆`19,357`
*   [gookit/validate](https://github.com/gookit/validate) — Go package for data validation and filtering. support Map, Struct, Form data ☆`1,115`
*   [Oudwins/zog](https://github.com/Oudwins/zog) — Go with Zod inspired simple schema validation ☆`1,013`
*   [twharmon/govalid](https://github.com/twharmon/govalid) — Struct validation using tags ☆`109`
*   [faceair/jio](https://github.com/faceair/jio) — jio is a json schema validator similar to joi ☆`124`
*   [osamingo/checkdigit](https://github.com/osamingo/checkdigit) — Provide check digit algorithms and calculators written in Go ☆`114`
*   [tiendc/go-validator](https://github.com/tiendc/go-validator) — Intuitive validation library for Golang ☆`32`
*   [marrow16/valix](https://github.com/marrow16/valix) — Go package for validating requests ☆`31`

## Version Control

*   [go-git/go-git](https://github.com/go-git/go-git) — A highly extensible Git implementation in pure Go. ☆`7,007`
*   [gabyx/Githooks](https://github.com/gabyx/Githooks) — Githooks: per-repo and shared Git hooks with version control and auto update. \[✩Star] if you're using it! ☆`114`
*   [jfrog/froggit-go](https://github.com/jfrog/froggit-go) — Froggit-Go is a universal Go library, allowing to perform actions on VCS providers. ☆`48`

## Video

*   [bluenviron/gortsplib](https://github.com/bluenviron/gortsplib) — RTSP client and server library for the Go programming language ☆`865`
*   [asticode/go-astisub](https://github.com/asticode/go-astisub) — Manipulate subtitles in GO (.srt, .ssa/.ass, .stl, .ttml, .vtt (webvtt), teletext, etc.) ☆`672`
*   [asticode/go-astiav](https://github.com/asticode/go-astiav) — Golang ffmpeg and libav C bindings ☆`597`
*   [asticode/go-astits](https://github.com/asticode/go-astits) — Demux and mux MPEG Transport Streams (.ts) natively in GO ☆`595`
*   [Eyevinn/mp4ff](https://github.com/Eyevinn/mp4ff) — Library and tools for working with MP4 files containing video, audio, subtitles, or metadata. The focus is on fragmented files. Includes mp4ff-info, mp4ff-encrypt, mp4ff-decrypt and other tools. ☆`576`
*   [adrg/libvlc-go](https://github.com/adrg/libvlc-go) — Handcrafted Go bindings for libVLC and high-level media player interface ☆`493`
*   [korandiz/v4l](https://github.com/korandiz/v4l) — Facade to the Video4Linux video capture interface. ☆`88`
*   [Eyevinn/hls-m3u8](https://github.com/Eyevinn/hls-m3u8) — HLS m3u8 library in Go ☆`28`
*   [unki2aut/go-mpd](https://github.com/unki2aut/go-mpd) — Go library for parsing and generating MPEG-DASH Media Presentation Description (MPD) files ☆`32`

## Web Frameworks

*   [gin-gonic/gin](https://github.com/gin-gonic/gin) — Gin is a high-performance HTTP web framework written in Go. It provides a Martini-like API but with significantly better performance—up to 40 times faster—thanks to httprouter. Gin is designed for building REST APIs, web applications, and microservices. ☆`87,109`
*   [gofiber/fiber](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`38,519`
*   [beego/beego](https://github.com/beego/beego) — beego is an open-source, high-performance web framework for the Go programming language. ☆`32,349`
*   [labstack/echo](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`31,844`
*   [gofr-dev/gofr](https://github.com/gofr-dev/gofr) — An opinionated GoLang framework for accelerated microservice development. Built in support for databases and observability. ☆`14,926`
*   [gogf/gf](https://github.com/gogf/gf) — A powerful framework for faster, easier, and more efficient project development. ☆`12,891`
*   [cloudwego/hertz](https://github.com/cloudwego/hertz) — Go HTTP framework with high-performance and strong-extensibility for building micro-services. ☆`6,899`
*   [goadesign/goa](https://github.com/goadesign/goa) — Design-first Go framework that generates API code, documentation, and clients. Define once in an elegant DSL, deploy as HTTP and gRPC services with zero drift between code and docs. ☆`5,991`
*   [apache/dubbo-go](https://github.com/apache/dubbo-go) — Go Implementation For Apache Dubbo . ☆`4,854`
*   [goravel/goravel](https://github.com/goravel/goravel) — A full-featured Golang Development Framework. ☆`4,281`
*   [danielgtaylor/huma](https://github.com/danielgtaylor/huma) — Huma REST/HTTP API Framework for Golang with OpenAPI 3.1 ☆`3,581`
*   [go-goyave/goyave](https://github.com/go-goyave/goyave) — The enterprise REST API framework ☆`1,749`
*   [go-fuego/fuego](https://github.com/go-fuego/fuego) — Golang Fuego - Web framework generating OpenAPI 3 spec from source code - Pluggable to existing Gin & Echo APIs ☆`1,591`
*   [savsgio/atreugo](https://github.com/savsgio/atreugo) — High performance and extensible micro web framework. Zero memory allocations in hot paths. ☆`1,297`
*   [templui/templui](https://github.com/templui/templui) — A growing collection of beautifully designed UI components for Go and templ. Install via CLI. Customize everything. Own your code. ☆`1,027`
*   [ankorstore/yokai](https://github.com/ankorstore/yokai) — Simple, modular, and observable Go framework for backend applications. ☆`789`
*   [indeedeng/iwf](https://github.com/indeedeng/iwf) — iWF is a Workflow-As-Code microservice orchestration platform offering an orchestration coding framework and service for building resilient, fault-tolerant, scalable long-running processes ☆`622`
*   [i-love-flamingo/flamingo-commerce](https://github.com/i-love-flamingo/flamingo-commerce) — Flexible E-Commerce Framework on top of Flamingo. Used to build E-Commerce "Portals" and connect it with the help of individual Adapters to other services. ☆`583`
*   [i-love-flamingo/flamingo](https://github.com/i-love-flamingo/flamingo) — Flamingo Framework and Core Library. Flamingo is a go based framework to build pluggable applications. Focus is on clean architecture, maintainability and operation readiness. ☆`551`
*   [rookie-ninja/rk-boot](https://github.com/rookie-ninja/rk-boot) — Build microservice with rk-boot and let the team take over clean and tidy code. ☆`574`
*   [fastschema/fastschema](https://github.com/fastschema/fastschema) — All-in-One Backend as a Service with Headless CMS Power ☆`522`
*   [uadmin/uadmin](https://github.com/uadmin/uadmin) — The web framework for Golang ☆`355`
*   [xxjwxc/ginrpc](https://github.com/xxjwxc/ginrpc) — gin auto binding, grpc and annotated route ☆`299`
*   [hidevopsio/hiboot](https://github.com/hidevopsio/hiboot) — hiboot is a high performance web and cli application framework with dependency injection support ☆`182`
*   [beatlabs/patron](https://github.com/beatlabs/patron) — Microservice framework following best cloud practices with a focus on productivity. ☆`126`
*   [gone-io/gone](https://github.com/gone-io/gone) — Gone - A Lightweight Dependency Injection Framework for Go | Tag-based Auto Injection | Supports Config Center/Lifecycle Management | Provides Rich Ecosystem Components and Scaffolding Tool ☆`132`
*   [claygod/microservice](https://github.com/claygod/microservice) — This library provides a simple microservice framework based on clean architecture principles with a working example implemented. ☆`121`
*   [gookit/rux](https://github.com/gookit/rux) — Rux is an simple and fast web framework. Support route group, param route binding, middleware, compatible http.Handler interface ☆`98`
*   [yaitoo/xun](https://github.com/yaitoo/xun) — Xun is a web framework built on Go's built-in html/template and net/http package’s router (1.22). ☆`91`
*   [go-spring/spring-core](https://github.com/go-spring/spring-core) — \[released] Go-Spring is a high-performance Go framework inspired by Spring Boot, offering DI, auto-configuration, and lifecycle management while maintaining Go's simplicity and efficiency. ☆`73`
*   [abemedia/go-don](https://github.com/abemedia/go-don) — API framework written in Golang. ☆`57`
*   [JiveGroup/gFly](https://github.com/JiveGroup/gFly) — Laravel inspired web framework written in Go ☆`49`
*   [SaiNageswarS/go-api-boot](https://github.com/SaiNageswarS/go-api-boot) — Production-ready Go framework for gRPC + HTTP APIs with MongoDB ODM, zero-config SSL, Temporal workflows, cloud utilities, and bootstrap CLI. ☆`35`
*   [clubpay/ronykit](https://github.com/clubpay/ronykit) — API Framework supporting REST and RPC. ☆`34`
*   [jvcoutinho/lit](https://github.com/jvcoutinho/lit) — A simple, fast and expressive HTTP framework for Go. ☆`30`

## WebAssembly

*   [tinygo-org/tinygo](https://github.com/tinygo-org/tinygo) — Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM. ☆`16,867`
*   [agnivade/wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) — Run WASM tests inside your browser ☆`206`
*   [extism/go-sdk](https://github.com/extism/go-sdk) — Extism Go SDK - easily run WebAssembly modules in your Go applications ☆`154`

## Webhooks Server

*   [adnanh/webhook](https://github.com/adnanh/webhook) — webhook is a lightweight incoming webhook server to run shell commands ☆`11,386`
*   [webhookx-io/webhookx](https://github.com/webhookx-io/webhookx) — The Next-Generation Webhooks Gateway. ☆`246`
*   [42atomys/webhooked](https://github.com/42atomys/webhooked) — A webhook receiver on steroids. ☆`41`

## Windows

*   [go-ole/go-ole](https://github.com/go-ole/go-ole) — win32 ole implementation for golang ☆`1,283`
*   [gonutz/d3d9](https://github.com/gonutz/d3d9) — Direct3D9 wrapper for Go. ☆`163`

## Workflow Frameworks

*   [dagu-org/dagu](https://github.com/dagu-org/dagu) — A dead simple, local-first workflow engine for managing complex jobs without pain. Single binary with Web UI. 100% open source. No vendor lock-in. It natively supports running containers and executing commands over SSH. Offline or air-gapped environment ready. ☆`2,858`
*   [noneback/go-taskflow](https://github.com/noneback/go-taskflow) — A pure go General-purpose Task-parallel Programming Framework with integrated visualizer and profiler ☆`597`
*   [cadence-workflow/cadence-go-client](https://github.com/cadence-workflow/cadence-go-client) — Framework for authoring workflows and activities running on top of the Cadence orchestration engine. ☆`373`
*   [luno/workflow](https://github.com/luno/workflow) — The type-safe, event-driven workflow orchestration library that scales with your business. Build robust, distributed workflows in Go with compile-time safety, automatic retries, and horizontal scaling out of the box. Integrate with your existing tech stack using adapters ☆`202`
*   [rhosocial/go-dag](https://github.com/rhosocial/go-dag) — A Go-based framework has been developed to oversee the execution of workflows delineated by directed acyclic graphs (DAGs). ☆`34`

## XML

*   [miku/zek](https://github.com/miku/zek) — Generate a Go struct from XML. ☆`821`
*   [antchfx/xpath](https://github.com/antchfx/xpath) — XPath package for golang, supports HTML, XML, JSON document query and more ☆`730`
*   [antchfx/xmlquery](https://github.com/antchfx/xmlquery) — xmlquery is Golang XPath package for XML query. ☆`480`

## Zero Trust

*   [sigstore/cosign](https://github.com/sigstore/cosign) — Code signing and transparency for containers and binaries ☆`5,436`
*   [openziti/ziti](https://github.com/openziti/ziti) — The parent project for OpenZiti. Here you will find the executables for a fully zero trust, application embedded, programmable network @OpenZiti ☆`3,714`
*   [spiffe/spire](https://github.com/spiffe/spire) — The SPIFFE Runtime Environment ☆`2,123`
*   [philips-labs/spiffe-vault](https://github.com/philips-labs/spiffe-vault) — Integrates Spiffe and Vault to have secretless authentication ☆`94`

## Gophers

*   [MariaLetta/free-gophers-pack](https://github.com/MariaLetta/free-gophers-pack) — This pack of 100+ gopher pictures and elements
*   [keygx/Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) — Go gopher Vector Data (.ai, .svg)
*   [ashleymcnamara/gophers](https://github.com/ashleymcnamara/gophers) — Gopher Artwork by Ashley McNamara
*   [sillecelik/go-gopher](https://github.com/sillecelik/go-gopher) — The Go Gopher Amigurumi Pattern
*   [GolangUA/gopher-logos](https://github.com/GolangUA/gopher-logos) — adorable gopher logos
*   [egonelbre/gophers](https://github.com/egonelbre/gophers) — gophers artwork
*   [scraly/gophers](https://github.com/scraly/gophers) — Gopher artwork (Golang mascot)

## Contributing

Please see [CONTRIBUTING](https://github.com/abordage/awesome-go/blob/main/README.md/.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request — contributions are welcome!

## Credits

*   [avelino/awesome-go](https://github.com/avelino/awesome-go)
*   [All Contributors](https://github.com/abordage/awesome-go/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](https://github.com/abordage/awesome-go/blob/main/README.md/LICENSE) for more information.

