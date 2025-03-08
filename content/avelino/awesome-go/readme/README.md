# Awesome Go Overview

A curated list of awesome Go frameworks, libraries and software

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/avelino/awesome-go/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 avelino/awesome-go](https://github.com/avelino/awesome-go) · ⭐ 139K · 🏷️ Programming Languages

[ [Daily](/content/avelino/awesome-go/README.md) / [Weekly](/content/avelino/awesome-go/week/README.md) / Overview ]

---

# Awesome Go

<a href="https://awesome-go.com/"><img align="right" src="https://github.com/avelino/awesome-go/raw/main/tmpl/assets/logo.png" alt="awesome-go" title="awesome-go" /></a>

[![Build Status](https://github.com/avelino/awesome-go/actions/workflows/tests.yaml/badge.svg?branch=main)](https://github.com/avelino/awesome-go/actions/workflows/tests.yaml?query=branch%3Amain)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true\&logo=slack\&colorB=red)](https://gophers.slack.com/messages/awesome)
[![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/avelino/awesome-go/)
[![Last Commit](https://img.shields.io/github/last-commit/avelino/awesome-go)](https://img.shields.io/github/last-commit/avelino/awesome-go)

We use the *[Golang Bridge (⭐402)](https://github.com/gobridge/about-us/blob/master/README.md)* community Slack for instant communication, follow the [form here to join](https://invite.slack.golangbridge.org/).

<a href="https://www.producthunt.com/posts/awesome-go?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-awesome-go" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=291535&theme=light" alt="awesome-go - Curated list awesome Go frameworks, libraries and software | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

**Sponsorships:**

*Special thanks to*

<div align="center">
<table cellpadding="5">
<tbody align="center">
<tr>
<td colspan="2">
<a href="https://bit.ly/awesome-go-workos">
<img src="https://avelino.run/sponsors/workos-logo-white-bg.svg" width="200" alt="WorkOS"><br/>
<b>Your app, enterprise-ready.</b><br/>
<sub>Start selling to enterprise customers with just a few lines of code.</sub><br/>
<sup>Add Single Sign-On (and more) in minutes instead of months.</sup>
</a>
</td>
</tr>
<tr>
<td colspan="2">
<a href="https://bit.ly/awesome-go-digitalocean">
<img src="https://avelino.run/sponsors/do_logo_horizontal_blue-210.png" width="200" alt="Digital Ocean">
</a>
</td>
</tr>
</tbody>
</table>
</div>

**Awesome Go has no monthly fee***, but we have employees who **work hard** to keep it running. With money raised, we can repay the effort of each person involved! You can see how we calculate our billing and distribution as it is open to the entire community. Want to be a supporter of the project click [here](https://github.com/avelino/awesome-go/blob/main/README.md/mailto:avelinorun+oss@gmail.com?subject=awesome-go%3A%20project%20support).*

> A curated list of awesome Go frameworks, libraries, and software. Inspired by [awesome-python (⭐236k)](https://github.com/vinta/awesome-python).

**Contributing:**

Please take a quick gander at the [contribution guidelines (⭐139k)](https://github.com/avelino/awesome-go/blob/main/CONTRIBUTING.md) first. Thanks to all [contributors (⭐139k)](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

> *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

## Contents

*   [Awesome Go](#awesome-go)
    *   [Contents](#contents)
    *   [Actor Model](#actor-model)
    *   [Artificial Intelligence](#artificial-intelligence)
    *   [Audio and Music](#audio-and-music)
    *   [Authentication and OAuth](#authentication-and-oauth)
    *   [Blockchain](#blockchain)
    *   [Bot Building](#bot-building)
    *   [Build Automation](#build-automation)
    *   [Command Line](#command-line)
        *   [Advanced Console UIs](#advanced-console-uis)
        *   [Standard CLI](#standard-cli)
    *   [Configuration](#configuration)
    *   [Continuous Integration](#continuous-integration)
    *   [CSS Preprocessors](#css-preprocessors)
    *   [Data Integration Frameworks](#data-integration-frameworks)
    *   [Data Structures and Algorithms](#data-structures-and-algorithms)
        *   [Bit-packing and Compression](#bit-packing-and-compression)
        *   [Bit Sets](#bit-sets)
        *   [Bloom and Cuckoo Filters](#bloom-and-cuckoo-filters)
        *   [Data Structure and Algorithm Collections](#data-structure-and-algorithm-collections)
        *   [Iterators](#iterators)
        *   [Maps](#maps)
        *   [Miscellaneous Data Structures and Algorithms](#miscellaneous-data-structures-and-algorithms)
        *   [Nullable Types](#nullable-types)
        *   [Queues](#queues)
        *   [Sets](#sets)
        *   [Text Analysis](#text-analysis)
        *   [Trees](#trees)
        *   [Pipes](#pipes)
    *   [Database](#database)
        *   [Caches](#caches)
        *   [Databases Implemented in Go](#databases-implemented-in-go)
        *   [Database Schema Migration](#database-schema-migration)
        *   [Database Tools](#database-tools)
        *   [SQL Query Builders](#sql-query-builders)
    *   [Database Drivers](#database-drivers)
        *   [Interfaces to Multiple Backends](#interfaces-to-multiple-backends)
        *   [Relational Database Drivers](#relational-database-drivers)
        *   [NoSQL Database Drivers](#nosql-database-drivers)
        *   [Search and Analytic Databases](#search-and-analytic-databases)
    *   [Date and Time](#date-and-time)
    *   [Distributed Systems](#distributed-systems)
    *   [Dynamic DNS](#dynamic-dns)
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
    *   [Goroutines](#goroutines)
    *   [GUI](#gui)
    *   [Hardware](#hardware)
    *   [Images](#images)
    *   [IoT (Internet of Things)](#iot-internet-of-things)
    *   [Job Scheduler](#job-scheduler)
    *   [JSON](#json)
    *   [Logging](#logging)
    *   [Machine Learning](#machine-learning)
    *   [Messaging](#messaging)
    *   [Microsoft Office](#microsoft-office)
        *   [Microsoft Excel](#microsoft-excel)
        *   [Microsoft Word](#microsoft-word)
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
    *   [Science and Data Analysis](#science-and-data-analysis)
    *   [Security](#security)
    *   [Serialization](#serialization)
    *   [Server Applications](#server-applications)
    *   [Stream Processing](#stream-processing)
    *   [Template Engines](#template-engines)
    *   [Testing](#testing)
        *   [Testing Frameworks](#testing-frameworks)
        *   [Mock](#mock)
        *   [Fuzzing and delta-debugging/reducing/shrinking](#fuzzing-and-delta-debuggingreducingshrinking)
        *   [Selenium and browser control tools](#selenium-and-browser-control-tools)
        *   [Fail injection](#fail-injection)
    *   [Text Processing](#text-processing)
        *   [Formatters](#formatters)
        *   [Markup Languages](#markup-languages)
        *   [Parsers/Encoders/Decoders](#parsersencodersdecoders)
        *   [Regular Expressions](#regular-expressions)
        *   [Sanitation](#sanitation)
        *   [Scrapers](#scrapers)
        *   [RSS](#rss)
        *   [Utility/Miscellaneous](#utilitymiscellaneous)
    *   [Third-party APIs](#third-party-apis)
    *   [Utilities](#utilities)
    *   [UUID](#uuid)
    *   [Validation](#validation)
    *   [Version Control](#version-control)
    *   [Video](#video)
    *   [Web Frameworks](#web-frameworks)
        *   [Middlewares](#middlewares)
            *   [Actual middlewares](#actual-middlewares)
            *   [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        *   [Routers](#routers)
    *   [WebAssembly](#webassembly)
    *   [Webhooks Server](#webhooks-server)
    *   [Windows](#windows)
    *   [Workflow Frameworks](#workflow-frameworks)
    *   [XML](#xml)
    *   [Zero Trust](#zero-trust)
    *   [Code Analysis](#code-analysis)
    *   [Editor Plugins](#editor-plugins)
    *   [Go Generate Tools](#go-generate-tools)
    *   [Go Tools](#go-tools)
    *   [Software Packages](#software-packages)
        *   [DevOps Tools](#devops-tools)
        *   [Other Software](#other-software)
*   [Resources](#resources)
    *   [Benchmarks](#benchmarks)
    *   [Conferences](#conferences)
    *   [E-Books](#e-books)
        *   [E-books for purchase](#e-books-for-purchase)
        *   [Free e-books](#free-e-books)
    *   [Gophers](#gophers)
    *   [Meetups](#meetups)
    *   [Style Guides](#style-guides)
    *   [Social Media](#social-media)
        *   [Twitter](#twitter)
        *   [Reddit](#reddit)
    *   [Websites](#websites)
        *   [Tutorials](#tutorials)
        *   [Guided Learning](#guided-learning)

**[⬆ back to top](#contents)**

## Actor Model

*Libraries for building actor-based programs.*

*   [Ergo (⭐3.8k)](https://github.com/ergo-services/ergo) - An actor-based Framework with network transparency for creating event-driven architecture in Golang. Inspired by Erlang.
*   [Goakt (⭐219)](https://github.com/Tochemey/goakt) - Fast and Distributed Actor framework using protocol buffers as message for Golang.
*   [Hollywood (⭐1.7k)](https://github.com/anthdm/hollywood) - Blazingly fast and light-weight Actor engine written in Golang.
*   [ProtoActor (⭐5.1k)](https://github.com/asynkron/protoactor-go) - Proto Actor - Ultra fast distributed actors for Go, C# and Java/Kotlin.

## Artificial Intelligence

*Libraries for building programs that leverage AI.*

*   [chromem-go (⭐425)](https://github.com/philippgille/chromem-go) - Embeddable vector database for Go with Chroma-like interface and zero third-party dependencies. In-memory with optional persistence.
*   [fun](https://gitlab.com/tozd/go/fun) - The simplest but powerful way to use large language models (LLMs) in Go.
*   [langchaingo (⭐5.8k)](https://github.com/tmc/langchaingo) - LangChainGo is a framework for developing applications powered by language models.
*   [LocalAI (⭐31k)](https://github.com/mudler/LocalAI) - Open Source OpenAI alternative, self-host AI models.
*   [Ollama (⭐129k)](https://github.com/jmorganca/ollama) - Run large language models locally.
*   [OllamaFarm (⭐64)](https://github.com/presbrey/ollamafarm) - Manage, load-balance, and failover packs of Ollamas

**[⬆ back to top](#contents)**

## Audio and Music

*Libraries for manipulating audio.*

*   [flac (⭐329)](https://github.com/mewkiz/flac) - Native Go FLAC encoder/decoder with support for FLAC streams.
*   [gaad (⭐126)](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser.
*   [GoAudio (⭐363)](https://github.com/DylanMeeus/GoAudio) - Native Go Audio Processing Library.
*   [gosamplerate (⭐33)](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go.
*   [id3v2 (⭐344)](https://github.com/bogem/id3v2) - ID3 decoding and encoding library for Go.
*   [malgo (⭐321)](https://github.com/gen2brain/malgo) - Mini audio library.
*   [minimp3 (⭐127)](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library.
*   [Oto (⭐1.7k)](https://github.com/hajimehoshi/oto) - A low-level library to play sound on multiple platforms.
*   [PortAudio (⭐736)](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library.

**[⬆ back to top](#contents)**

## Authentication and OAuth

*Libraries for implementing authentication schemes.*

*   [authboss (⭐3.9k)](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure it, and start building your app without having to build an authentication system each time.
*   [branca (⭐88)](https://github.com/essentialkaos/branca) - branca token [specification implementation (⭐228)](https://github.com/tuupola/branca-spec) for Golang 1.15+.
*   [casbin (⭐18k)](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, and ABAC.
*   [cookiestxt (⭐17)](https://github.com/mengzhuo/cookiestxt) - provides a parser of cookies.txt file format.
*   [go-guardian (⭐571)](https://github.com/shaj13/go-guardian) - Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token, and Certificate based authentication.
*   [go-jose (⭐356)](https://github.com/go-jose/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
*   [goiabada (⭐143)](https://github.com/leodip/goiabada) - An open-source authentication and authorization server supporting OAuth2 and OpenID Connect.
*   [gologin (⭐1.9k)](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
*   [gorbac (⭐1.6k)](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang.
*   [gosession (⭐261)](https://github.com/Kwynto/gosession) - This is quick session for net/http in GoLang. This package is perhaps the best implementation of the session mechanism, or at least it tries to become one.
*   [goth (⭐5.8k)](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.
*   [jeff (⭐267)](https://github.com/abraithwaite/jeff) - Simple, flexible, secure, and idiomatic web session management with pluggable backends.
*   [jwt (⭐358)](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library.
*   [jwt (⭐675)](https://github.com/cristalhq/jwt) - Safe, simple, and fast JSON Web Tokens for Go.
*   [jwt-auth (⭐234)](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options.
*   [jwt-go (⭐7.7k)](https://github.com/golang-jwt/jwt) - A full featured implementation of JSON Web Tokens (JWT). This library supports the parsing and verification as well as the generation and signing of JWTs.
*   [jwx (⭐2k)](https://github.com/lestrrat-go/jwx) - Go module implementing various JWx (JWA/JWE/JWK/JWS/JWT, otherwise known as JOSE) technologies
*   [keto (⭐4.9k)](https://github.com/ory/keto) - Open Source (Go) implementation of "Zanzibar: Google's Consistent, Global Authorization System". Ships gRPC, REST APIs, newSQL, and an easy and granular permission language. Supports ACL, RBAC, and other access models.
*   [loginsrv (⭐1.9k)](https://github.com/tarent/loginsrv) - JWT login microservice with pluggable backends such as OAuth2 (Github), htpasswd, osiam.
*   [oauth2 (⭐5.5k)](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine, and App Engine support.
*   [oidc (⭐1.5k)](https://github.com/zitadel/oidc) - Easy to use OpenID Connect client and server library written for Go and certified by the OpenID Foundation
*   [openfga (⭐3.3k)](https://github.com/openfga/openfga) - Implementation of fine-grained authorization based on the "Zanzibar: Google's Consistent, Global Authorization System" paper. Backed by [CNCF](https://www.cncf.io/).
*   [osin (⭐1.9k)](https://github.com/openshift/osin) - Golang OAuth2 server library.
*   [otpgen (⭐139)](https://github.com/grijul/otpgen) - Library to generate TOTP/HOTP codes.
*   [otpgo (⭐72)](https://github.com/jltorresm/otpgo) - Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go.
*   [paseto (⭐874)](https://github.com/o1egl/paseto) - Golang implementation of Platform-Agnostic Security Tokens (PASETO).
*   [permissions (⭐8)](https://github.com/xyproto/permissions) - Library for keeping track of users, login states, and permissions. Uses secure cookies and bcrypt.
*   [scope (⭐41)](https://github.com/SonicRoshan/scope) - Easily Manage OAuth2 Scopes In Go.
*   [scs (⭐2.3k)](https://github.com/alexedwards/scs) - Session Manager for HTTP servers.
*   [securecookie (⭐81)](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding.
*   [session (⭐119)](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE).
*   [sessions (⭐78)](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers.
*   [sessionup (⭐123)](https://github.com/swithek/sessionup) - Simple, yet effective HTTP session management and identification package.
*   [sjwt (⭐120)](https://github.com/brianvoe/sjwt) - Simple jwt generator and parser.

**[⬆ back to top](#contents)**

## Blockchain

*Tools for building blockchains.*

*   [cometbft (⭐707)](https://github.com/cometbft/cometbft) - A distributed, Byzantine fault-tolerant, deterministic state machine replication engine. It is a fork of Tendermint Core and implements the Tendermint consensus algorithm.
*   [cosmos-sdk (⭐6.5k)](https://github.com/cosmos/cosmos-sdk) - A Framework for Building Public Blockchains in the Cosmos Ecosystem.
*   [gno (⭐933)](https://github.com/gnolang/gno) - A comprehensive smart contract suite built with Golang and Gnolang, a deterministic, purpose-built Go variant for blockchains.
*   [go-ethereum (⭐48k)](https://github.com/ethereum/go-ethereum) - Official Go implementation of the Ethereum protocol.
*   [gosemble (⭐13)](https://github.com/LimeChain/gosemble) - A Go-based framework for building Polkadot/Substrate-compatible runtimes.
*   [gossamer (⭐441)](https://github.com/ChainSafe/gossamer) - A Go implementation of the Polkadot Host.
*   [kubo (⭐16k)](https://github.com/ipfs/kubo) - A blockchain framework implemented in Go. It provides content-addressable storage which can be used for decentralized storage in DApps. It is based on the IPFS protocol.
*   [lnd (⭐7.8k)](https://github.com/lightningnetwork/lnd) - A complete implementation of a Lightning Network node.
*   [solana-go (⭐1.2k)](https://github.com/gagliardetto/solana-go) - Go library to interface with Solana JSON RPC and WebSocket interfaces.
*   [tendermint (⭐5.8k)](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.

**[⬆ back to top](#contents)**

## Bot Building

*Libraries for building and working with bots.*

*   [arikawa (⭐497)](https://github.com/diamondburned/arikawa) - A library and framework for the Discord API.
*   [bot (⭐950)](https://github.com/go-telegram/bot) - Zero-dependencies Telegram Bot library with additional UI components
*   [echotron (⭐389)](https://github.com/NicoNex/echotron) - An elegant and concurrent library for Telegram Bots in Go.
*   [ephemeral-roles (⭐91)](https://github.com/ewohltman/ephemeral-roles) - A Discord bot for managing ephemeral roles based upon voice channel member presence.
*   [go-joe](https://joe-bot.net) - A general-purpose bot library inspired by Hubot but written in Go.
*   [go-sarah (⭐260)](https://github.com/oklahomer/go-sarah) - Framework to build a bot for desired chat services including LINE, Slack, Gitter, and more.
*   [go-tg (⭐111)](https://github.com/mr-linch/go-tg) - Generated from official docs Go client library for accessing Telegram Bot API, with batteries for building complex bots included.
*   [go-tgbot (⭐120)](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router, and middleware.
*   [go-twitch-irc (⭐371)](https://github.com/gempir/go-twitch-irc) - Library to write bots for twitch.tv chat
*   [Golang CryptoTrading Bot (⭐1.1k)](https://github.com/saniales/golang-crypto-trading-bot) - A golang implementation of a console-based trading bot for cryptocurrency exchanges.
*   [govkbot (⭐50)](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library.
*   [hanu (⭐156)](https://github.com/sbstjn/hanu) - Framework for writing Slack bots.
*   [larry (⭐161)](https://github.com/ezeoleaf/larry) - Larry 🐦 is a really simple Twitter bot generator that tweets random repositories from Github built in Go.
*   [margelet (⭐86)](https://github.com/zhulik/margelet) - Framework for building Telegram bots.
*   [micha (⭐30)](https://github.com/onrik/micha) - Go Library for Telegram bot api.
*   [slack-bot (⭐188)](https://github.com/innogames/slack-bot) - Ready to use Slack Bot for lazy developers: Custom commands, Jenkins, Jira, Bitbucket, Github...
*   [slacker (⭐48)](https://github.com/slack-io/slacker) - Easy to use framework to create Slack bots.
*   [slackscot (⭐55)](https://github.com/alexandre-normand/slackscot) - Another framework for building Slack bots.
*   [tbot (⭐354)](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http.
*   [telebot (⭐4.2k)](https://github.com/tucnak/telebot) - Telegram bot framework is written in Go.
*   [telego (⭐634)](https://github.com/mymmrac/telego) - Telegram Bot API library for Golang with full one-to-one API implementation.
*   [telegram-bot-api (⭐6k)](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client.
*   [teleterm (⭐38)](https://github.com/alfiankan/teleterm) - Telegram Bot Exec Terminal Command.
*   [Tenyks (⭐176)](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging.
*   [wayback (⭐1.9k)](https://github.com/wabarc/wayback) - A bot for Telegram, Mastodon, Slack, and other messaging platforms archives webpages.

**[⬆ back to top](#contents)**

## Build Automation

*Libraries and tools help with build automation.*

*   [1build (⭐231)](https://github.com/gopinath-langote/1build) - Command line tool to frictionlessly manage project-specific commands.
*   [air (⭐19k)](https://github.com/cosmtrek/air) - Air - Live reload for Go apps.
*   [anko (⭐40)](https://github.com/GuilhermeCaruso/anko) - Simple application watcher for multiple programming languages.
*   [gaper (⭐80)](https://github.com/maxclaus/gaper) - Builds and restarts a Go project when it crashes or some watched file changes.
*   [gilbert](https://go-gilbert.github.io) - Build system and task runner for Go projects.
*   [gob (⭐13)](https://github.com/kcmvp/gob) - [Gradle](https://docs.gradle.org/)/[Maven](https://maven.apache.org/) like build tool for Go projects.
*   [goyek (⭐591)](https://github.com/goyek/goyek) - Create build pipelines in Go.
*   [mage (⭐4.3k)](https://github.com/magefile/mage) - Mage is a make/rake-like build tool using Go.
*   [mmake (⭐1.7k)](https://github.com/tj/mmake) - Modern Make.
*   [realize (⭐4.5k)](https://github.com/tockins/realize) - Go build a system with file watchers and live to reload. Run, build and watch file changes with custom paths.
*   [Task (⭐12k)](https://github.com/go-task/task) - simple "Make" alternative.
*   [taskctl (⭐307)](https://github.com/taskctl/taskctl) - Concurrent task runner.
*   [xc (⭐1.3k)](https://github.com/joerdav/xc) - Task runner with README.md defined tasks, executable markdown.

**[⬆ back to top](#contents)**

## Command Line

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

*   [asciigraph (⭐2.7k)](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.
*   [aurora (⭐1.4k)](https://github.com/logrusorgru/aurora) - ANSI terminal colors that support fmt.Printf/Sprintf.
*   [box-cli-maker (⭐550)](https://github.com/Delta456/box-cli-maker) - Make Highly Customized Boxes for your CLI.
*   [bubble-table (⭐473)](https://github.com/Evertras/bubble-table) - An interactive table component for bubbletea.
*   [bubbles (⭐6k)](https://github.com/charmbracelet/bubbles) - TUI components for bubbletea.
*   [bubbletea (⭐30k)](https://github.com/charmbracelet/bubbletea) - Go framework to build terminal apps, based on The Elm Architecture.
*   [cfmt (⭐104)](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes.
*   [cfmt (⭐70)](https://github.com/i582/cfmt) - Simple and convenient formatted stylized output fully compatible with fmt library.
*   [chalk (⭐459)](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output.
*   [crab-config-files-templating (⭐8)](https://github.com/alfiankan/crab-config-files-templating) - Dynamic configuration file templating tool for kubernetes manifest or general configuration files.
*   [ctc (⭐47)](https://github.com/wzshiming/ctc) - The non-invasive cross-platform terminal color library does not need to modify the Print method.
*   [fx (⭐19k)](https://github.com/antonmedv/fx) - Terminal JSON viewer & processor.
*   [go-ataman (⭐19)](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals.
*   [go-colorable (⭐784)](https://github.com/mattn/go-colorable) - Colorable writer for windows.
*   [go-colortext (⭐217)](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals.
*   [go-isatty (⭐852)](https://github.com/mattn/go-isatty) - isatty for golang.
*   [go-palette (⭐18)](https://github.com/abusomani/go-palette) - Go library that provides elegant and convenient style definitions using ANSI colors. Fully compatible & wraps the [fmt library](https://pkg.go.dev/fmt) for nice terminal layouts.
*   [go-prompt (⭐5.3k)](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit (⭐9.6k)](https://github.com/jonathanslenders/python-prompt-toolkit).
*   [gocui (⭐10k)](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces.
*   [gommon/color (⭐546)](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
*   [gookit/color (⭐1.5k)](https://github.com/gookit/color) - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows.
*   [lipgloss (⭐8.6k)](https://github.com/charmbracelet/lipgloss) - Declaratively define styles for color, format and layout in the terminal.
*   [marker (⭐50)](https://github.com/cyucelen/marker) - Easiest way to match and mark strings for colorful terminal outputs.
*   [mpb (⭐2.4k)](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications.
*   [progressbar (⭐4.3k)](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS.
*   [pterm (⭐5k)](https://github.com/pterm/pterm) - A library to beautify console output on every platform with many combinable components.
*   [simpletable (⭐533)](https://github.com/alexeyco/simpletable) - Simple tables in a terminal with Go.
*   [spinner (⭐2.4k)](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.
*   [tabby (⭐358)](https://github.com/cheynewallace/tabby) - A tiny library for super simple Golang tables.
*   [table (⭐51)](https://github.com/tomlazar/table) - Small library for terminal color based tables.
*   [termbox-go (⭐4.7k)](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces.
*   [termdash (⭐2.8k)](https://github.com/mum4k/termdash) - Go terminal dashboard based on **termbox-go** and inspired by [termui (⭐13k)](https://github.com/gizak/termui).
*   [termenv (⭐1.8k)](https://github.com/muesli/termenv) - Advanced ANSI style & color support for your terminal applications.
*   [termui (⭐13k)](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib (⭐16k)](https://github.com/yaronn/blessed-contrib).
*   [uilive (⭐1.7k)](https://github.com/gosuri/uilive) - Library for updating terminal output in real time.
*   [uiprogress (⭐2.1k)](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications.
*   [uitable (⭐739)](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data.
*   [yacspin (⭐443)](https://github.com/theckman/yacspin) - Yet Another CLi Spinner package, for working with terminal spinners.

**[⬆ back to top](#contents)**

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

*   [acmd (⭐121)](https://github.com/cristalhq/acmd) - Simple, useful, and opinionated CLI package in Go.
*   [argparse (⭐622)](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module.
*   [argv (⭐41)](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax.
*   [carapace (⭐531)](https://github.com/rsteube/carapace) - Command argument completion generator for spf13/cobra.
*   [carapace-bin (⭐1.1k)](https://github.com/rsteube/carapace-bin) - Multi-shell multi-command argument completer.
*   [carapace-spec (⭐21)](https://github.com/rsteube/carapace-spec) - Define simple completions using a spec file.
*   [climax (⭐217)](https://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
*   [clîr (⭐188)](https://github.com/leaanthony/clir) - A Simple and Clear CLI library. Dependency free.
*   [cmd (⭐42)](https://github.com/posener/cmd) - Extends the standard `flag` package to support sub commands and more in idiomatic way.
*   [cmdr (⭐137)](https://github.com/hedzr/cmdr) - A POSIX/GNU style, getopt-like command-line UI Go library.
*   [cobra (⭐40k)](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions.
*   [command-chain (⭐65)](https://github.com/rainu/go-command-chain) - A go library for configure and run command chains - such as pipelining in unix shells.
*   [commandeer (⭐175)](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.
*   [complete (⭐933)](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion.
*   [console (⭐84)](https://github.com/reeflective/console) Closed-loop application library for Cobra commands, with oh-my-posh prompts, and more.
*   [Dnote (⭐2.8k)](https://github.com/dnote/dnote) - A simple command line notebook with multi-device sync.
*   [elvish (⭐5.9k)](https://github.com/elves/elvish) - An expressive programming language and a versatile interactive shell.
*   [env (⭐117)](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs.
*   [flaggy (⭐858)](https://github.com/integrii/flaggy) - A robust and idiomatic flags package with excellent subcommand support.
*   [flagvar (⭐45)](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package.
*   [getopt (⭐4)](https://github.com/jon-codes/getopt) - An accurate Go `getopt`, validated against the GNU libc implementation.
*   [go-arg (⭐2.1k)](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go.
*   [go-flags (⭐2.6k)](https://github.com/jessevdk/go-flags) - go command line option parser.
*   [go-getoptions (⭐57)](https://github.com/DavidGamba/go-getoptions) - Go option parser inspired by the flexibility of Perl’s GetOpt::Long.
*   [gocmd (⭐66)](https://github.com/devfacet/gocmd) - Go library for building command line applications.
*   [hashicorp/cli (⭐20)](https://github.com/hashicorp/cli) - Go library for implementing command-line interfaces.
*   [hiboot cli (⭐181)](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection.
*   [job (⭐147)](https://github.com/liujianping/job) - JOB, make your short-term command as a long-term job.
*   [kingpin (⭐3.5k)](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands (superseded by `kong`; see below).
*   [liner (⭐1.1k)](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces.
*   [mcli (⭐37)](https://github.com/jxskiss/mcli) - A minimal but very powerful cli library for Go.
*   [mkideal/cli (⭐732)](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags.
*   [mow.cli (⭐869)](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation.
*   [ops (⭐1.3k)](https://github.com/nanovms/ops) - Unikernel Builder/Orchestrator.
*   [pflag (⭐2.5k)](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.
*   [readline (⭐106)](https://github.com/reeflective/readline) - Shell library with modern and easy to use UI features.
*   [sand (⭐27)](https://github.com/Zaba505/sand) - Simple API for creating interpreters and so much more.
*   [sflags (⭐159)](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin, and other libraries.
*   [strumt (⭐62)](https://github.com/antham/strumt) - Library to create prompt chain.
*   [subcmd (⭐8)](https://github.com/bobg/subcmd) - Another approach to parsing and running subcommands. Works alongside the standard `flag` package.
*   [teris-io/cli (⭐131)](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go.
*   [ts (⭐20)](https://github.com/liujianping/ts) - Timestamp convert & compare tool.
*   [ukautz/clif (⭐129)](https://github.com/ukautz/clif) - Small command line interface framework.
*   [urfave/cli (⭐23k)](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
*   [version (⭐105)](https://github.com/mszostok/version) - Collects and displays CLI version information in multiple formats along with upgrade notice.
*   [wlog (⭐66)](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency.
*   [wmenu (⭐222)](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompt users to make choices.

**[⬆ back to top](#contents)**

## Configuration

*Libraries for configuration parsing.*

*   [aconfig (⭐563)](https://github.com/cristalhq/aconfig) - Simple, useful and opinionated config loader.
*   [bcl (⭐22)](https://github.com/wkhere/bcl) - BCL is a configuration language similar to HCL.
*   [cleanenv (⭐1.7k)](https://github.com/ilyakaznacheev/cleanenv) - Minimalistic configuration reader (from files, ENV, and wherever you want).
*   [config (⭐337)](https://github.com/JeremyLoy/config) - Cloud native application configuration. Bind ENV to structs in only two lines.
*   [config (⭐54)](https://github.com/num30/config) - configure your app using file, environment variables, or flags in two lines of code
*   [configuration (⭐108)](https://github.com/BoRuDar/configuration) - Library for initializing configuration structs from env variables, files, flags and 'default' tag.
*   [configure (⭐56)](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables.
*   [configuro (⭐96)](https://github.com/sherifabdlnaby/configuro) - opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications.
*   [confiq (⭐37)](https://github.com/greencoda/confiq) - Structured data format to config struct decoder library for Go - supporting multiple data formats
*   [confita (⭐493)](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct.
*   [conflate (⭐34)](https://github.com/the4thamigo-uk/conflate) - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema.
*   [env (⭐5.2k)](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults).
*   [env (⭐69)](https://github.com/junk1tm/env) - A lightweight package for loading environment variables into structs.
*   [env (⭐6)](https://github.com/syntaqx/env) - An environment utility package with support for unmarshaling into structs
*   [envconfig (⭐243)](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables.
*   [envh (⭐100)](https://github.com/antham/envh) - Helpers to manage environment variables.
*   [envyaml (⭐13)](https://github.com/yuseferi/envyaml) - Yaml with environment variables reader. it helps to have secrets as environment variable but load them configs as structured Yaml.
*   [fig (⭐380)](https://github.com/kkyr/fig) - Tiny library for reading configuration from a file and from environment variables (with validation & defaults).
*   [genv (⭐41)](https://github.com/sakirsensoy/genv) - Read environment variables easily with dotenv support.
*   [go-array (⭐19)](https://github.com/deatil/go-array) - A Go package that read or set data from map, slice or json.
*   [go-aws-ssm (⭐61)](https://github.com/PaddleHQ/go-aws-ssm) - Go package that fetches parameters from AWS System Manager - Parameter Store.
*   [go-cfg (⭐44)](https://github.com/dsbasko/go-cfg) - The library provides a unified way to read configuration data into a structure from various sources, such as env, flags, and configuration files (.json, .yaml, .toml, .env).
*   [go-conf (⭐11)](https://github.com/ThomasObenaus/go-conf) - Simple library for application configuration based on annotated structs. It supports reading the configuration from environment variables, config files and command line parameters.
*   [go-ini (⭐14)](https://github.com/subpop/go-ini) - A Go package that marshals and unmarshals INI-files.
*   [go-ssm-config (⭐22)](https://github.com/ianlopshire/go-ssm-config) - Go utility for loading configuration parameters from AWS SSM (Parameter Store).
*   [go-up (⭐43)](https://github.com/ufoscout/go-up) - A simple configuration library with recursive placeholders resolution and no magic.
*   [GoCfg (⭐6)](https://github.com/Jagerente/gocfg) - Config manager with Struct Tags based contracts, custom value providers, parsers, and documentation generation. Customizable yet simple.
*   [godotenv (⭐8.8k)](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`).
*   [gofigure (⭐68)](https://github.com/ian-kent/gofigure) - Go application configuration made easy.
*   [GoLobby/Config (⭐363)](https://github.com/golobby/config) - GoLobby Config is a lightweight yet powerful configuration manager for the Go programming language.
*   [gone/jconf (⭐50)](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep your config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
*   [gonfig (⭐9)](https://github.com/milad-abbasi/gonfig) - Tag-based configuration parser which loads values from different providers into typesafe struct.
*   [gookit/config (⭐548)](https://github.com/gookit/config) - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge.
*   [harvester (⭐132)](https://github.com/beatlabs/harvester) - Harvester, a easy to use static and dynamic configuration package supporting seeding, env vars and Consul integration.
*   [hedzr/store (⭐6)](https://github.com/hedzr/store) - Extensible, high-performance configuration management library, optimized for hierarchical data.
*   [hjson (⭐336)](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.
*   [hocon (⭐81)](https://github.com/gurkankaymak/hocon) - Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files.
*   [ingo (⭐38)](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file.
*   [ini (⭐3.5k)](https://github.com/go-ini/ini) - Go package to read and write INI files.
*   [ini (⭐15)](https://github.com/wlevene/ini) - INI Parser & Write Library, Unmarshal to Struct, Marshal to Json, Write File, watch file.
*   [joshbetz/config (⭐215)](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.
*   [kelseyhightower/envconfig (⭐5.1k)](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables.
*   [koanf (⭐3k)](https://github.com/knadh/koanf) - Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line.
*   [konf (⭐297)](https://github.com/nil-go/konf) - The simplest API for reading/watching config from file, env, flag and clouds (e.g. AWS, Azure, GCP).
*   [konfig (⭐644)](https://github.com/lalamove/konfig) - Composable, observable and performant config handling for Go for the distributed processing era.
*   [kong (⭐2.4k)](https://github.com/alecthomas/kong) - Command-line parser with support for arbitrarily complex command-line structures and additional sources of configuration such as YAML, JSON, TOML, etc (successor to `kingpin`).
*   [mini (⭐35)](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files.
*   [nasermirzaei89/env (⭐18)](https://github.com/nasermirzaei89/env) - Simple useful package for read environment variables.
*   [nfigure (⭐8)](https://github.com/muir/nfigure) - Per-library struct-tag based configuration from command lines (Posix & Go-style); environment, JSON, YAML
*   [onion (⭐117)](https://github.com/goraz/onion) - Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP.
*   [piper (⭐8)](https://github.com/Yiling-J/piper) - Viper wrapper with config inheritance and key generation.
*   [sonic (⭐7.6k)](https://github.com/bytedance/sonic) - A blazingly fast JSON serializing & deserializing library.
*   [store (⭐274)](https://github.com/tucnak/store) - Lightweight configuration manager for Go.
*   [swap (⭐8)](https://github.com/oblq/swap) - Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env).
*   [typenv (⭐9)](https://github.com/diegomarangoni/typenv) - Minimalistic, zero dependency, typed environment variables library.
*   [uConfig (⭐71)](https://github.com/omeid/uconfig) - Lightweight, zero-dependency, and extendable configuration management.
*   [viper (⭐28k)](https://github.com/spf13/viper) - Go configuration with fangs.
*   [xdg (⭐769)](https://github.com/adrg/xdg) - Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/latest/) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories).
*   [xdg (⭐80)](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://specifications.freedesktop.org/basedir-spec/latest/).
*   [yamagiconf (⭐18)](https://github.com/romshark/yamagiconf) - The "safe subset" of YAML for Go configs.

**[⬆ back to top](#contents)**

## Continuous Integration

*Tools for help with continuous integration.*

*   [abstruse (⭐943)](https://github.com/bleenco/abstruse) - Abstruse is a distributed CI platform.
*   [Bencher](https://bencher.dev/) - A suite of continuous benchmarking tools designed to catch performance regressions in CI.
*   [CDS (⭐4.7k)](https://github.com/ovh/cds) - Enterprise-Grade CI/CD and DevOps Automation Open Source Platform.
*   [dot (⭐23)](https://github.com/opnlabs/dot) - A minimal, local first continuous integration system that uses Docker to run jobs concurrently in stages.
*   [drone (⭐32k)](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go.
*   [go-beautiful-html-coverage (⭐14)](https://github.com/gha-common/go-beautiful-html-coverage) - A GitHub Action to track code coverage in your pull requests, with a beautiful HTML preview, for free.
*   [go-fuzz-action (⭐15)](https://github.com/jidicula/go-fuzz-action) - Use Go 1.18's built-in fuzz testing in GitHub Actions.
*   [go-semver-release (⭐10)](https://github.com/s0ders/go-semver-release) - Automate the semantic versioning of Git repositories.
*   [go-test-coverage (⭐136)](https://github.com/vladopajic/go-test-coverage) - Tool and GitHub action which reports issues when test coverage is below set threshold.
*   [gomason (⭐65)](https://github.com/nikogura/gomason) - Test, Build, Sign, and Publish your go binaries from a clean workspace.
*   [gotestfmt (⭐532)](https://github.com/GoTestTools/gotestfmt) - go test output for humans.
*   [goveralls (⭐789)](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system.
*   [muffet (⭐2.5k)](https://github.com/raviqqe/muffet) - Fast website link checker in Go, see [alternatives (⭐2.5k)](https://github.com/lycheeverse/lychee#features).
*   [overalls (⭐115)](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls.
*   [roveralls (⭐20)](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool.
*   [woodpecker (⭐4.7k)](https://github.com/woodpecker-ci/woodpecker) - Woodpecker is a community fork of the Drone CI system.

**[⬆ back to top](#contents)**

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

*   [gcss (⭐498)](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor.
*   [go-libsass (⭐206)](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project.

**[⬆ back to top](#contents)**

## Data Integration Frameworks

*Frameworks for performing ELT / ETL*

*   [Benthos (⭐8.3k)](https://github.com/benthosdev/benthos) - A message streaming bridge between a range of protocols.
*   [CloudQuery (⭐6k)](http://github.com/cloudquery/cloudquery) - A high-performance ELT data integration framework with pluggable architecture.
*   [omniparser (⭐1k)](https://github.com/jf-tech/omniparser) - A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema.

**[⬆ back to top](#contents)**

## Data Structures and Algorithms

### Bit-packing and Compression

*   [bingo (⭐41)](https://github.com/iancmcc/bingo) - Fast, zero-allocation, lexicographical-order-preserving packing of native types to bytes.
*   [binpacker (⭐224)](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream.
*   [bit (⭐161)](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions.
*   [crunch (⭐98)](https://github.com/superwhiskers/crunch) - Go package implementing buffers for handling various datatypes easily.
*   [go-ef (⭐34)](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding.
*   [roaring (⭐2.6k)](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets.

### Bit Sets

*   [bitmap (⭐321)](https://github.com/kelindar/bitmap) - Dense, zero-allocation, SIMD-enabled bitmap/bitset in Go.
*   [bitset (⭐1.4k)](https://github.com/bits-and-blooms/bitset) - Go package implementing bitsets.

### Bloom and Cuckoo Filters

*   [bloom (⭐2.5k)](https://github.com/bits-and-blooms/bloom) - Go package implementing Bloom filters.
*   [bloom (⭐146)](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go.
*   [bloom (⭐86)](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation.
*   [bloomfilter (⭐17)](https://github.com/OldPanda/bloomfilter) - Yet another Bloomfilter implementation in Go, compatible with Java's Guava library.
*   [boomfilters (⭐1.6k)](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams.
*   [cuckoo-filter (⭐298)](https://github.com/linvon/cuckoo-filter) - Cuckoo filter: a comprehensive cuckoo filter, which is configurable and space optimized compared with other implements, and all features mentioned in original paper are available.
*   [cuckoofilter (⭐1.2k)](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.
*   [ring (⭐138)](https://github.com/TheTannerRyan/ring) - Go implementation of a high performance, thread safe bloom filter.

### Data Structure and Algorithm Collections

*   [algorithms (⭐813)](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study.
*   [go-datastructures (⭐7.8k)](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures.
*   [gods (⭐17k)](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
*   [gostl (⭐1.1k)](https://github.com/liyue201/gostl) - Data structure and algorithm library for go, designed to provide functions similar to C++ STL.

### Iterators

*   [goterator (⭐16)](https://github.com/yaa110/goterator) - Iterator implementation to provide map and reduce functionalities.
*   [iter (⭐189)](https://github.com/disksing/iter) - Go implementation of C++ STL iterators and algorithms.

### Maps

See also [Database](#database) for more complex key-value stores, and [Trees](#trees) for
additional ordered map implementations.

*   [cmap (⭐93)](https://github.com/lrita/cmap) - a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards.
*   [dict (⭐47)](https://github.com/srfrog/dict) - Python-like dictionaries (dict) for Go.
*   [go-shelve (⭐9)](https://github.com/lucmq/go-shelve) - A persistent, map-like object for the Go programming language. Supports multiple embedded key-value stores.
*   [goradd/maps (⭐47)](https://github.com/goradd/maps) - Go 1.18+ generic map interface for maps; safe maps; ordered maps; ordered, safe maps; etc.

### Miscellaneous Data Structures and Algorithms

*   [concurrent-writer (⭐56)](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`.
*   [count-min-log (⭐66)](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).
*   [fsm (⭐69)](https://github.com/cocoonspace/fsm) - Finite-State Machine package.
*   [genfuncs (⭐51)](https://github.com/nwillc/genfuncs) - Go 1.18+ generics package inspired by Kotlin's Sequence and Map.
*   [go-generics (⭐80)](https://github.com/bobg/go-generics) - Generic slice, map, set, iterator, and goroutine utilities.
*   [go-geoindex (⭐357)](https://github.com/hailocab/go-geoindex) - In-memory geo index.
*   [go-rampart (⭐101)](https://github.com/francesconi/go-rampart) - Determine how intervals relate to each other.
*   [go-rquad (⭐134)](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding.
*   [go-tuple (⭐84)](https://github.com/barweiss/go-tuple) - Generic tuple implementation for Go 1.18+.
*   [go18ds (⭐46)](https://github.com/daichi-m/go18ds) - Go Data Structures using Go 1.18 generics.
*   [gofal (⭐19)](https://github.com/xxjwxc/gofal) - fractional api for Go.
*   [gogu (⭐102)](https://github.com/esimov/gogu) - A comprehensive, reusable and efficient concurrent-safe generics utility functions and data structures library.
*   [gota (⭐3.1k)](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go.
*   [hide (⭐69)](https://github.com/emvi/hide) - ID type with marshalling to/from hash to prevent sending IDs to clients.
*   [hyperloglog (⭐959)](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
*   [quadtree (⭐37)](https://github.com/s0rg/quadtree) - Generic, zero-alloc, 100%-test covered quadtree.
*   [slices (⭐20)](https://github.com/twharmon/slices) - Pure, generic functions for slices.

### Nullable Types

*   [nan (⭐85)](https://github.com/kak-tus/nan) - Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers.
*   [null (⭐36)](https://github.com/emvi/null) - Nullable Go types that can be marshalled/unmarshalled to/from JSON.
*   [typ (⭐46)](https://github.com/gurukami/typ) - Null Types, Safe primitive type conversion and fetching value from complex structures.

### Queues

*   [deque (⭐189)](https://github.com/edwingeng/deque) - A highly optimized double-ended queue.
*   [deque (⭐650)](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue).
*   [goconcurrentqueue (⭐414)](https://github.com/enriquebris/goconcurrentqueue) - Concurrent FIFO queue.
*   [hatchet (⭐4.6k)](https://github.com/hatchet-dev/hatchet) - Distributed, Fault-tolerant task queue.
*   [memlog (⭐129)](https://github.com/embano1/memlog) - An easy to use, lightweight, thread-safe and append-only in-memory data structure inspired by Apache Kafka.
*   [queue (⭐283)](https://github.com/adrianbrad/queue) - Multiple thread-safe, generic queue implementations for Go.

### Sets

*   [dsu (⭐15)](https://github.com/ihebu/dsu) - Disjoint Set data structure implementation in Go.
*   [golang-set (⭐4.4k)](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go.
*   [goset (⭐52)](https://github.com/zoumo/goset) - A useful Set collection implementation for Go.
*   [set (⭐27)](https://github.com/StudioSol/set) - Simple set data structure implementation in Go using LinkedHashMap.

### Text Analysis

*   [bleve (⭐10k)](https://github.com/blevesearch/bleve) - Modern text indexing library for go.
*   [go-adaptive-radix-tree (⭐383)](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree.
*   [go-edlib (⭐501)](https://github.com/hbollon/go-edlib) - Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode.
*   [levenshtein (⭐86)](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
*   [levenshtein (⭐380)](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go.
*   [mspm (⭐26)](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm for information retrieval.
*   [parsefields (⭐7)](https://github.com/MonaxGT/parsefields) - Tools for parse JSON-like logs for collecting unique fields and events.
*   [ptrie (⭐41)](https://github.com/viant/ptrie) - An implementation of prefix tree.
*   [trie (⭐767)](https://github.com/derekparker/trie) - Trie implementation in Go.

### Trees

*   [hashsplit (⭐31)](http://github.com/bobg/hashsplit) - Split byte streams into chunks, and arrange chunks into trees, with boundaries determined by content, not position.
*   [merkle (⭐19)](https://github.com/bobg/merkle) - Space-efficient computation of Merkle root hashes and inclusion proofs.
*   [skiplist (⭐282)](https://github.com/MauriceGit/skiplist) - Very fast Go Skiplist implementation.
*   [skiplist (⭐84)](https://github.com/gansidui/skiplist) - Skiplist implementation in Go.
*   [treap (⭐27)](https://github.com/perdata/treap) - Persistent, fast ordered map using tree heaps.
*   [treemap (⭐61)](https://github.com/igrmk/treemap) - Generic key-sorted map using a red-black tree under the hood.

### Pipes

*   [ordered-concurrently (⭐40)](https://github.com/tejzpr/ordered-concurrently) - Go module that processes work concurrently and returns output in a channel in the order of input.
*   [parapipe (⭐36)](https://github.com/nazar256/parapipe) - FIFO Pipeline which parallels execution on each stage while maintaining the order of messages and results.
*   [pipeline (⭐57)](https://github.com/hyfather/pipeline) - An implementation of pipelines with fan-in and fan-out.

**[⬆ back to top](#contents)**

## Database

### Caches

*Data stores with expiring records, in-memory distributed data stores, or in-memory subsets of file-based databases.*

*   [2q (⭐42)](https://github.com/floatdrop/2q) - 2Q in-memory cache implementation.
*   [bcache (⭐157)](https://github.com/iwanbk/bcache) - Eventually consistent distributed in-memory cache Go library.
*   [BigCache (⭐7.7k)](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data.
*   [cache (⭐188)](https://github.com/akyoto/cache) - In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage.
*   [cache2go (⭐2.1k)](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts.
*   [cachego (⭐371)](https://github.com/faabiosr/cachego) - Golang Cache component for multiple drivers.
*   [clusteredBigCache (⭐45)](https://github.com/oaStuff/clusteredBigCache) - BigCache with clustering support and individual item expiration.
*   [coherence-go-client (⭐11)](https://github.com/oracle/coherence-go-client) - Full implementation of Oracle Coherence cache API for Go applications using gRPC as network transport.
*   [couchcache (⭐65)](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server.
*   [EchoVault (⭐453)](https://github.com/EchoVault/EchoVault) - Embeddable Distributed in-memory data store compatible with Redis clients.
*   [fastcache (⭐2.2k)](https://github.com/VictoriaMetrics/fastcache) - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead.
*   [GCache (⭐2.6k)](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC.
*   [gdcache (⭐13)](https://github.com/ulovecode/gdcache) - A pure non-intrusive cache library implemented by golang, you can use it to implement your own distributed cache.
*   [go-cache (⭐146)](https://github.com/viney-shih/go-cache) - A flexible multi-layer Go caching library to deal with in-memory and shared cache by adopting Cache-Aside pattern.
*   [go-freelru (⭐220)](https://github.com/elastic/go-freelru) A GC-less, fast and generic LRU hashmap library with optional locking, sharding, eviction and expiration.
*   [go-mcache (⭐98)](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library. Pointer caches.
*   [gocache (⭐2.6k)](https://github.com/eko/gocache) - A complete Go cache library with multiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more.
*   [gocache (⭐10)](https://github.com/yuseferi/gocache) - A data race free Go ache library with high performance and auto pruge functionality
*   [groupcache (⭐13k)](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
*   [icache (⭐20)](https://github.com/mdaliyan/icache) - A High Performance, Generic, thread-safe, zero-dependency cache package.
*   [imcache (⭐123)](https://github.com/erni27/imcache) - A generic in-memory cache Go library. It supports expiration, sliding expiration, max entries limit, eviction callbacks and sharding.
*   [nscache (⭐11)](https://github.com/no-src/nscache) - A Go caching framework that supports multiple data source drivers.
*   [otter (⭐1.8k)](https://github.com/maypok86/otter) - A high performance lockless cache for Go. Many times faster than Ristretto and friends.
*   [pocache (⭐219)](https://github.com/naughtygopher/pocache) - Pocache is a minimal cache package which focuses on a preemptive optimistic caching strategy.
*   [ristretto (⭐5.9k)](https://github.com/dgraph-io/ristretto) -  A high performance memory-bound Go cache.
*   [sturdyc (⭐1.1k)](https://github.com/viccon/sturdyc) - A caching library with advanced concurrency features designed to make I/O heavy applications robust and highly performant.
*   [theine (⭐287)](https://github.com/Yiling-J/theine-go) - High performance, near optimal in-memory cache with proactive TTL expiration and generics.
*   [timedmap (⭐72)](https://github.com/zekroTJA/timedmap) - Map with expiring key-value pairs.
*   [ttlcache (⭐1k)](https://github.com/jellydator/ttlcache) - An in-memory cache with item expiration and generics.
*   [ttlcache (⭐10)](https://github.com/cheshir/ttlcache) - In-memory key value storage with TTL for each record.

### Databases Implemented in Go

*   [badger (⭐14k)](https://github.com/dgraph-io/badger) - Fast key-value store in Go.
*   [bbolt (⭐8.5k)](https://github.com/etcd-io/bbolt) - An embedded key/value database for Go.
*   [Bitcask](https://git.mills.io/prologic/bitcask) - Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL).
*   [buntdb (⭐4.6k)](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
*   [clover (⭐725)](https://github.com/ostafen/clover) - A lightweight document-oriented NoSQL database written in pure Golang.
*   [cockroach (⭐31k)](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.
*   [Coffer (⭐40)](https://github.com/claygod/coffer) - Simple ACID key-value database that supports transactions.
*   [column (⭐1.5k)](https://github.com/kelindar/column) - High-performance, columnar, embeddable in-memory store with bitmap indexing and transactions.
*   [CovenantSQL (⭐1.5k)](https://github.com/CovenantSQL/CovenantSQL) - CovenantSQL is a SQL database on blockchain.
*   [Databunker (⭐1.3k)](https://github.com/paranoidguy/databunker) - Personally identifiable information (PII) storage service built to comply with GDPR and CCPA.
*   [dgraph (⭐21k)](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.
*   [diskv (⭐1.4k)](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store.
*   [dolt (⭐18k)](https://github.com/dolthub/dolt) - Dolt – It's Git for Data.
*   [eliasdb (⭐1k)](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
*   [godis (⭐3.6k)](https://github.com/hdt3213/godis) - A Golang implemented high-performance Redis server and cluster.
*   [goleveldb (⭐6.2k)](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB (⭐37k)](https://github.com/google/leveldb) key/value database in Go.
*   [hare (⭐96)](https://github.com/jameycribbs/hare) - A simple database management system that stores each table as a text file of line-delimited JSON.
*   [immudb (⭐8.7k)](https://github.com/codenotary/immudb) - immudb is a lightweight, high-speed immutable database for systems and applications written in Go.
*   [influxdb (⭐30k)](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
*   [ledisdb (⭐4.1k)](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
*   [levigo (⭐415)](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB.
*   [libradb (⭐176)](https://github.com/amit-davidson/LibraDB) - LibraDB is a simple database with less than 1000 lines of code for learning.
*   [LinDB (⭐3k)](https://github.com/lindb/lindb) - LinDB is a scalable, high performance, high availability distributed time series database.
*   [lotusdb (⭐2.1k)](https://github.com/flower-corp/lotusdb) - Fast k/v database compatible with lsm and b+tree.
*   [Milvus (⭐33k)](https://github.com/milvus-io/milvus) - Milvus is a vector database for embedding management, analytics and search.
*   [moss (⭐999)](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go.
*   [nutsdb (⭐3.4k)](https://github.com/xujiajun/nutsdb) - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set.
*   [objectbox-go (⭐1.1k)](https://github.com/objectbox/objectbox-go) - High-performance embedded Object Database (NoSQL) with Go API.
*   [pebble (⭐5.2k)](https://github.com/cockroachdb/pebble) - RocksDB/LevelDB inspired key-value database in Go.
*   [piladb (⭐206)](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures.
*   [pogreb (⭐1.3k)](https://github.com/akrylysov/pogreb) - Embedded key-value store for read-heavy workloads.
*   [prometheus (⭐57k)](https://github.com/prometheus/prometheus) - Monitoring system and time series database.
*   [pudge (⭐368)](https://github.com/recoilme/pudge) - Fast and simple key/value store written using Go's standard library.
*   [redka (⭐3.6k)](https://github.com/nalgeon/redka) - Redis re-implemented with SQLite.
*   [rosedb (⭐4.7k)](https://github.com/roseduan/rosedb) - An embedded k-v database based on LSM+WAL, supports string, list, hash, set, zset.
*   [rotom (⭐41)](https://github.com/xgzlucario/rotom) - A tiny Redis server built with Golang, compatible with RESP protocols.
*   [rqlite (⭐16k)](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite.
*   [tempdb (⭐19)](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items.
*   [tidb (⭐38k)](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1.
*   [tiedot (⭐2.7k)](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang.
*   [unitdb (⭐120)](https://github.com/unit-io/unitdb) - Fast timeseries database for IoT, realtime messaging applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application.
*   [Vasto (⭐263)](https://github.com/chrislusf/vasto) - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption.
*   [VictoriaMetrics (⭐13k)](https://github.com/VictoriaMetrics/VictoriaMetrics) - fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL.

### Database Schema Migration

*   [atlas (⭐6.5k)](https://github.com/ariga/atlas) - A Database Toolkit. A CLI designed to help companies better work with their data.
*   [avro (⭐47)](https://github.com/khezen/avro) - Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes.
*   [bytebase (⭐12k)](https://github.com/bytebase/bytebase) - Safe database schema change and version control for DevOps teams.
*   [darwin (⭐145)](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go.
*   [dbmate (⭐5.7k)](https://github.com/amacneil/dbmate) - A lightweight, framework-agnostic database migration tool.
*   [go-fixtures (⭐29)](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library.
*   [go-pg-migrate (⭐11)](https://github.com/lawzava/go-pg-migrate) - CLI-friendly package for go-pg migrations management.
*   [go-pg-migrations (⭐85)](https://github.com/robinjoseph08/go-pg-migrations) - A Go package to help write migrations with go-pg/pg.
*   [goavro (⭐1k)](https://github.com/linkedin/goavro) - A Go package that encodes and decodes Avro data.
*   [godfish (⭐8)](https://github.com/rafaelespinoza/godfish) - Database migration manager, works with native query language. Support for cassandra, mysql, postgres, sqlite3.
*   [goose (⭐7.8k)](https://github.com/pressly/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
*   [gorm-seeder (⭐14)](https://github.com/Kachit/gorm-seeder) - Simple database seeder for Gorm ORM.
*   [gormigrate (⭐1.1k)](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM.
*   [libschema (⭐15)](https://github.com/muir/libschema) - Define your migrations separately in each library. Migrations for open source libraries. MySQL & PostgreSQL.
*   [migrate (⭐16k)](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library.
*   [migrator (⭐172)](https://github.com/lopezator/migrator) - Dead simple Go database migration library.
*   [migrator (⭐25)](https://github.com/larapulse/migrator) - MySQL database migrator designed to run migrations to your features and manage database schema update with intuitive go code.
*   [schema (⭐38)](https://github.com/adlio/schema) - Library to embed schema migrations for database/sql-compatible databases inside your Go binaries.
*   [skeema (⭐1.3k)](https://github.com/skeema/skeema) - Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools.
*   [soda (⭐1.5k)](https://github.com/gobuffalo/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
*   [sql-migrate (⭐3.3k)](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata.
*   [sqlize (⭐118)](https://github.com/sunary/sqlize) - Database migration generator. Allows generate sql migration from model and existing sql by differ them.

### Database Tools

*   [chproxy (⭐1.3k)](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database.
*   [clickhouse-bulk (⭐480)](https://github.com/nikepan/clickhouse-bulk) - Collects small inserts and sends big requests to ClickHouse servers.
*   [dbbench (⭐104)](https://github.com/sj14/dbbench) - Database benchmarking tool with support for several databases and scripts.
*   [dg (⭐31)](https://github.com/codingconcepts/dg) - A fast data generator that produces CSV files from generated relational data.
*   [gatewayd (⭐235)](https://github.com/gatewayd-io/gatewayd) - Cloud-native database gateway and framework for building data-driven applications. Like API gateways, for databases.
*   [go-mysql (⭐4.7k)](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication.
*   [gorm-multitenancy (⭐50)](https://github.com/bartventer/gorm-multitenancy) - Multi-tenancy support for GORM managed databases.
*   [hasql](https://golang.yandex/hasql) - Library for accessing multi-host SQL database installations.
*   [octillery (⭐193)](https://github.com/knocknote/octillery) - Go package for sharding databases ( Supports every ORM or raw SQL ).
*   [onedump (⭐147)](https://github.com/liweiyi88/onedump) - Database backup from different drivers to different destinations with one command and configuration.
*   [pg\_timetable (⭐1.1k)](https://github.com/cybertec-postgresql/pg_timetable) - Advanced scheduling for PostgreSQL.
*   [pgweb (⭐8.8k)](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser.
*   [prep (⭐33)](https://github.com/hexdigest/prep) - Use prepared SQL statements without changing your code.
*   [pREST (⭐4.3k)](https://github.com/prest/prest) - Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new.
*   [rdb (⭐474)](https://github.com/HDT3213/rdb) - Redis RDB file parser for secondary development and memory analysis.
*   [rwdb (⭐20)](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup.
*   [vitess (⭐19k)](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.
*   [wescale (⭐287)](https://github.com/wesql/wescale) - WeScale is a database proxy designed to enhance the scalability, performance, security, and resilience of your applications.

### SQL Query Builders

*Libraries for building and using SQL.*

*   [bqb (⭐161)](https://github.com/nullism/bqb) - Lightweight and easy to learn query builder.
*   [buildsqlx (⭐175)](https://github.com/arthurkushman/buildsqlx) - Go database query builder library for PostgreSQL.
*   [builq (⭐93)](https://github.com/cristalhq/builq) - Easily build SQL queries in Go.
*   [dbq (⭐407)](https://github.com/rocketlaunchr/dbq) - Zero boilerplate database operations for Go.
*   [Dotsql (⭐745)](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease.
*   [gendry (⭐1.6k)](https://github.com/didi/gendry) - Non-invasive SQL builder and powerful data binder.
*   [godbal (⭐59)](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily.
*   [goqu (⭐2.5k)](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library.
*   [gosql (⭐35)](https://github.com/twharmon/gosql) - SQL Query builder with better null values support.
*   [Hotcoal (⭐23)](https://github.com/motrboat/hotcoal) - Secure your handcrafted SQL against injection.
*   [igor (⭐126)](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
*   [jet (⭐2.9k)](https://github.com/go-jet/jet) - Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure.
*   [ormlite (⭐16)](https://github.com/pupizoid/ormlite) - Lightweight package containing some ORM-like features and helpers for sqlite databases.
*   [ozzo-dbx (⭐641)](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
*   [patcher (⭐4)](https://github.com/Jacobbrewer1/patcher) - Powerful SQL Query builder that automatically generates SQL queries from structs.
*   [qry (⭐35)](https://github.com/HnH/qry) - Tool that generates constants from files with raw SQL queries.
*   [sg (⭐6)](https://github.com/go-the-way/sg) - A SQL Gen for generating standard SQLs(supports: CRUD) written in Go.
*   [sq (⭐198)](https://github.com/bokwoon95/go-structured-query) - Type-safe SQL builder and struct mapper for Go.
*   [sqlc (⭐14k)](https://github.com/kyleconroy/sqlc) - Generate type-safe code from SQL.
*   [sqlf (⭐158)](https://github.com/leporo/sqlf) - Fast SQL query builder.
*   [sqlingo (⭐421)](https://github.com/lqs/sqlingo) - A lightweight DSL to build SQL in Go.
*   [sqrl (⭐280)](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance.
*   [Squalus](https://gitlab.com/qosenergy/squalus) - Thin layer over the Go SQL package that makes it easier to perform queries.
*   [Squirrel (⭐7.2k)](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries.
*   [xo (⭐3.8k)](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.

**[⬆ back to top](#contents)**

## Database Drivers

### Interfaces to Multiple Backends

*   [cayley (⭐15k)](https://github.com/google/cayley) - Graph database with support for multiple backends.
*   [dsc (⭐32)](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files.
*   [dynamo (⭐20)](https://github.com/fogfish/dynamo) - A simple key-value abstraction to store algebraic and linked-data data types at AWS storage services: AWS DynamoDB and AWS S3.
*   [go-transaction-manager (⭐266)](https://github.com/avito-tech/go-transaction-manager) - Transaction manager with multiple adapters (sql, sqlx, gorm, mongo, ...) controls transaction boundaries.
*   [gokv (⭐770)](https://github.com/philippgille/gokv) - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more).

### Relational Database Drivers

*   [avatica (⭐121)](https://github.com/apache/calcite-avatica-go) - Apache Avatica/Phoenix SQL driver for database/sql.
*   [bgc (⭐21)](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go.
*   [firebirdsql (⭐231)](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go.
*   [go-adodb (⭐147)](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql.
*   [go-mssqldb (⭐1.8k)](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go.
*   [go-oci8 (⭐634)](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql.
*   [go-sql-driver/mysql (⭐15k)](https://github.com/go-sql-driver/mysql) - MySQL driver for Go.
*   [go-sqlite3 (⭐8.3k)](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql.
*   [go-sqlite3 (⭐606)](https://github.com/ncruces/go-sqlite3) - This Go module is compatible with the database/sql driver. It allows embedding SQLite into your application, provides direct access to its C API, supports SQLite VFS, and also includes a GORM driver.
*   [godror (⭐542)](https://github.com/godror/godror) - Oracle driver for Go, using the ODPI-C driver.
*   [gofreetds (⭐113)](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](https://www.freetds.org).
*   [KSQL (⭐327)](https://github.com/VinGarcia/ksql) - A Simple and Powerful Golang SQL Library
*   [pgx (⭐11k)](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql.
*   [pig (⭐17)](https://github.com/alexeyco/pig) - Simple [pgx (⭐11k)](https://github.com/jackc/pgx) wrapper to execute and [scan (⭐1.4k)](https://github.com/georgysavva/scany) query results easily.
*   [pq (⭐9.3k)](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql.
*   [Sqinn-Go (⭐441)](https://github.com/cvilsmeier/sqinn-go) - SQLite with pure Go.
*   [sqlhooks (⭐654)](https://github.com/qustavo/sqlhooks) - Attach hooks to any database/sql driver.
*   [sqlite](https://pkg.go.dev/modernc.org/sqlite) - Package sqlite is a sql/database driver using a CGo-free port of the C SQLite3 library.
*   [surrealdb.go (⭐269)](https://github.com/surrealdb/surrealdb.go) - SurrealDB Driver for Go.
*   [ydb-go-sdk (⭐147)](https://github.com/ydb-platform/ydb-go-sdk) - native and database/sql driver YDB (Yandex Database)

### NoSQL Database Drivers

*   [aerospike-client-go (⭐443)](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language.
*   [arangolite (⭐72)](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB.
*   [asc (⭐11)](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go.
*   [forestdb (⭐37)](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB.
*   [go-couchbase (⭐323)](https://github.com/couchbase/go-couchbase) - Couchbase client in Go.
*   [go-mongox (⭐176)](https://github.com/chenmingyong0423/go-mongox) - A Go Mongo library based on the official driver, featuring streamlined document operations, generic binding of structs to collections, built-in CRUD, aggregation, automated field updates, struct validation, hooks, and plugin-based programming.
*   [go-pilosa (⭐57)](https://github.com/pilosa/go-pilosa) - Go client library for Pilosa.
*   [go-rejson (⭐344)](https://github.com/nitishm/go-rejson) - Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease.
*   [gocb (⭐372)](https://github.com/couchbase/gocb) - Official Couchbase Go SDK.
*   [gocosmos (⭐22)](https://github.com/btnguyen2k/gocosmos) - REST client and standard `database/sql` driver for Azure Cosmos DB.
*   [gocql](https://gocql.github.io) - Go language driver for Apache Cassandra.
*   [godis (⭐114)](https://github.com/piaohao/godis) - redis client implement by golang, inspired by jedis.
*   [godscache (⭐11)](https://github.com/defcronyke/godscache) - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached.
*   [gomemcache (⭐1.8k)](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language.
*   [gomemcached (⭐20)](https://github.com/aliexpressru/gomemcached) - A binary Memcached client for Go with support for sharding using consistent hashing, along with SASL.
*   [gorethink (⭐1.7k)](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB.
*   [goriak (⭐30)](https://github.com/zegl/goriak) - Go language driver for Riak KV.
*   [Kivik (⭐317)](https://github.com/go-kivik/kivik) - Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases.
*   [mgm (⭐757)](https://github.com/kamva/mgm) - MongoDB model-based ODM for Go (based on official MongoDB driver).
*   [mgo (⭐2k)](https://github.com/globalsign/mgo) - (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
*   [mongo-go-driver (⭐8.3k)](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language.
*   [neo4j (⭐29)](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang.
*   [neoism (⭐389)](https://github.com/jmcvetta/neoism) - Neo4j client for Golang.
*   [qmgo (⭐1.3k)](https://github.com/qiniu/qmgo) - The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo.
*   [redeo (⭐443)](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services.
*   [redigo (⭐9.8k)](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database.
*   [redis (⭐21k)](https://github.com/redis/go-redis) - Redis client for Golang.
*   [rueidis (⭐2.6k)](http://github.com/rueian/rueidis) - Fast Redis RESP3 client with auto pipelining and server-assisted client side caching.
*   [xredis (⭐19)](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client.

### Search and Analytic Databases

*   [clickhouse-go (⭐3k)](https://github.com/ClickHouse/clickhouse-go/) - ClickHouse SQL client for Go with a `database/sql` compatibility.
*   [effdsl (⭐27)](https://github.com/sdqri/effdsl) - Elasticsearch query builder for Go.
*   [elastic (⭐7.5k)](https://github.com/olivere/elastic) - Elasticsearch client for Go.
*   [elasticsql (⭐1.2k)](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go.
*   [elastigo (⭐942)](https://github.com/mattbaird/elastigo) - Elasticsearch client library.
*   [go-elasticsearch (⭐5.8k)](https://github.com/elastic/go-elasticsearch) - Official Elasticsearch client for Go.
*   [goes (⭐31)](https://github.com/OwnLocal/goes) - Library to interact with Elasticsearch.
*   [skizze (⭐91)](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage.
*   [zoekt (⭐846)](https://github.com/sourcegraph/zoekt) - Fast trigram based code search.

**[⬆ back to top](#contents)**

## Date and Time

*Libraries for working with dates and times.*

*   [approx (⭐13)](https://github.com/goschtalt/approx) - A Duration extension supporting parsing/printing durations in days, weeks and years.
*   [carbon (⭐0)](https://github.com/golang-module/carbon) - A simple, semantic and developer-friendly golang package for datetime.
*   [carbon (⭐781)](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library.
*   [cronrange (⭐17)](https://github.com/1set/cronrange) - Parses Cron-style time range expressions, checks if the given time is within any ranges.
*   [date (⭐136)](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day.
*   [dateparse (⭐2.1k)](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance.
*   [durafmt (⭐499)](https://github.com/hako/durafmt) - Time duration formatting library for Go.
*   [feiertage (⭐49)](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving...
*   [go-anytime (⭐27)](https://github.com/ijt/go-anytime) - Parse dates/times like "next dec 22nd at 3pm" and ranges like "from today until next thursday" without knowing the format in advance.
*   [go-datebin (⭐4)](https://github.com/deatil/go-datebin) - A simple datetime parse pkg.
*   [go-persian-calendar (⭐212)](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).
*   [go-str2duration (⭐109)](https://github.com/xhit/go-str2duration) - Convert string to duration. Support time.Duration returned string and more.
*   [go-sunrise (⭐156)](https://github.com/nathan-osman/go-sunrise) - Calculate the sunrise and sunset times for a given location.
*   [go-week (⭐9)](https://github.com/stoewer/go-week) - An efficient package to work with ISO8601 week dates.
*   [gostradamus (⭐205)](https://github.com/bykof/gostradamus) - A Go package for working with dates.
*   [iso8601 (⭐149)](https://github.com/relvacode/iso8601) - Efficiently parse ISO8601 date-times without regex.
*   [kair (⭐24)](https://github.com/GuilhermeCaruso/kair) - Date and Time - Golang Formatting Library.
*   [now (⭐4.5k)](https://github.com/jinzhu/now) - Now is a time toolkit for golang.
*   [strftime (⭐13)](https://github.com/awoodbeck/strftime) - C99-compatible strftime formatter.
*   [timespan (⭐83)](https://github.com/SaidinWoT/timespan) - For interacting with intervals of time, defined as a start time and a duration.
*   [timeutil (⭐192)](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package.
*   [tuesday (⭐12)](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function.

**[⬆ back to top](#contents)**

## Distributed Systems

*Packages that help with building Distributed Systems.*

*   [arpc (⭐1k)](https://github.com/lesismal/arpc) - More effective network communication, support two-way-calling, notify, broadcast.
*   [bedrock (⭐10)](https://github.com/z5labs/bedrock) - Provides a minimal, modular and composable foundation for quickly developing services and more use case specific frameworks in Go.
*   [capillaries (⭐64)](https://github.com/capillariesio/capillaries) - distributed batch data processing framework.
*   [celeriac (⭐72)](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.
*   [committer (⭐34)](https://github.com/vadiminshakov/committer) - A distributed transactions management system (2PC/3PC implementation).
*   [consistent (⭐718)](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads.
*   [consistenthash (⭐27)](https://github.com/mbrostami/consistenthash) - Consistent hashing with configurable replicas.
*   [dht (⭐321)](https://github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
*   [digota (⭐512)](https://github.com/digota/digota) - grpc ecommerce microservice.
*   [dot (⭐87)](https://github.com/dotchain/dot/) - distributed sync using operational transformation/OT.
*   [doublejump (⭐104)](https://github.com/edwingeng/doublejump) - A revamped Google's jump consistent hash.
*   [dragonboat (⭐5.1k)](https://github.com/lni/dragonboat) - A feature complete and high performance multi-group Raft library in Go.
*   [Dragonfly (⭐2.4k)](https://github.com/dragonflyoss/Dragonfly2) - Provide efficient, stable and secure file distribution and image acceleration based on p2p technology to be the best practice and standard solution in cloud native architectures.
*   [drmaa (⭐48)](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard.
*   [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed distributed locking implementation.
*   [dynatomic (⭐17)](https://github.com/tylfin/dynatomic) - A library for using DynamoDB as an atomic counter.
*   [emitter-io (⭐3.9k)](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love.
*   [evans (⭐4.3k)](https://github.com/ktr0731/evans) - Evans: more expressive universal gRPC client.
*   [failured (⭐13)](https://github.com/andy2046/failured) - adaptive accrual failure detector for distributed systems.
*   [flowgraph (⭐60)](https://github.com/vectaport/flowgraph) - flow-based programming package.
*   [gleam (⭐3.5k)](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.
*   [glow (⭐3.2k)](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.
*   [gmsec (⭐25)](https://github.com/gmsec/micro) - A Go distributed systems development framework.
*   [go-doudou (⭐1.2k)](https://github.com/unionj-cloud/go-doudou) - A gossip protocol and OpenAPI 3.0 spec based decentralized microservice framework. Built-in go-doudou cli focusing on low-code and rapid dev can power up your productivity.
*   [go-eagle (⭐2.3k)](https://github.com/go-eagle/eagle) - A Go framework for the API or Microservice with handy scaffolding tools.
*   [go-health (⭐751)](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous dependency health checks in your service.
*   [go-jump (⭐384)](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function.
*   [go-kit (⭐27k)](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
*   [go-micro (⭐22k)](https://github.com/micro/go-micro) - A distributed systems development framework.
*   [go-mysql-lock (⭐62)](https://github.com/sanketplus/go-mysql-lock) - MySQL based distributed lock.
*   [go-pdu (⭐48)](https://github.com/pdupub/go-pdu) - A decentralized identity-based social network.
*   [go-sundheit (⭐553)](https://github.com/AppsFlyer/go-sundheit) - A library built to provide support for defining async service health checks for golang services.
*   [go-zero (⭐30k)](https://github.com/tal-tech/go-zero) - A web and rpc framework. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity.
*   [gorpc (⭐708)](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load.
*   [grpc-go (⭐21k)](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC.
*   [hprose (⭐1.3k)](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now.
*   [jsonrpc (⭐188)](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0.
*   [jsonrpc (⭐342)](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation.
*   [K8gb (⭐942)](https://github.com/k8gb-io/k8gb) - A cloud native Kubernetes Global Balancer.
*   [Kitex (⭐7.3k)](https://github.com/cloudwego/kitex) - A high-performance and strong-extensibility Golang RPC framework that helps developers build microservices. If the performance and extensibility are the main concerns when you develop microservices, Kitex can be a good choice.
*   [Kratos (⭐24k)](https://github.com/go-kratos/kratos) - A modular-designed and easy-to-use microservices framework in Go.
*   [liftbridge (⭐2.6k)](https://github.com/liftbridge-io/liftbridge) - Lightweight, fault-tolerant message streams for NATS.
*   [lura (⭐6.5k)](https://github.com/luraproject/lura) - Ultra performant API Gateway framework with middlewares.
*   [micro (⭐12k)](https://github.com/micro/micro) - A distributed systems runtime for the cloud and beyond.
*   [mochi mqtt (⭐1.4k)](https://github.com/mochi-co/mqtt) - Fully spec compliant, embeddable high-performance MQTT v5/v3 broker for IoT, smarthome, and pubsub.
*   [NATS (⭐17k)](https://github.com/nats-io/nats-server) - NATS is a simple, secure, and
    performant communications system for digital systems, services, and devices.
*   [outboxer (⭐160)](https://github.com/italolelis/outboxer) - Outboxer is a go library that implements the outbox pattern.
*   [pglock](https://cirello.io/pglock) - PostgreSQL-backed distributed locking implementation.
*   [pjrpc](https://gitlab.com/pjrpc/pjrpc) - Golang JSON-RPC Server-Client with Protobuf spec.
*   [raft (⭐8.4k)](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp.
*   [raft (⭐739)](https://github.com/etcd-io/raft) - Go implementation of the Raft consensus protocol, by CoreOS.
*   [rain (⭐1k)](https://github.com/cenkalti/rain) - BitTorrent client and library.
*   [redis-lock (⭐1.5k)](https://github.com/bsm/redislock) - Simplified distributed locking implementation using Redis.
*   [resgate](https://resgate.io/) - Realtime API Gateway for building REST, real time, and RPC APIs, where all clients are synchronized seamlessly.
*   [ringpop-go (⭐845)](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications.
*   [rpcx (⭐8.2k)](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo.
*   [Semaphore (⭐94)](https://github.com/jexia/semaphore) - A straightforward (micro) service orchestrator.
*   [sleuth (⭐378)](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ (⭐10k)](https://github.com/zeromq/libzmq)).
*   [sponge (⭐1.7k)](https://github.com/zhufuyi/sponge) - A distributed development framework that integrates automatic code generation, gin and grpc frameworks, base development frameworks.
*   [Tarmac (⭐329)](https://github.com/tarmac-project/tarmac) - Framework for writing functions, microservices, or monoliths with WebAssembly
*   [Temporal (⭐577)](https://github.com/temporalio/sdk-go) - Durable execution system for making code fault-tolerant and simple.
*   [torrent (⭐5.7k)](https://github.com/anacrolix/torrent) - BitTorrent client package.
*   [trpc-go (⭐884)](https://github.com/trpc-group/trpc-go) - The Go language implementation of tRPC, which is a pluggable, high-performance RPC framework.

**[⬆ back to top](#contents)**

## Dynamic DNS

*Tools for updating dynamic DNS records.*

*   [DDNS (⭐258)](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend.
*   [dyndns](https://gitlab.com/alcastle/dyndns) - Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes.
*   [GoDNS (⭐1.5k)](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.

**[⬆ back to top](#contents)**

## Email

*Libraries and tools that implement email creation and sending.*

*   [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.
*   [douceur (⭐249)](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails.
*   [email (⭐2.7k)](https://github.com/jordan-wright/email) - A robust and flexible email library for Go.
*   [email-verifier (⭐1.3k)](https://github.com/AfterShip/email-verifier) - A Go library for email verification without sending any emails.
*   [go-dkim (⭐98)](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email.
*   [go-email-normalizer (⭐66)](https://github.com/dimuska139/go-email-normalizer) - Golang library for providing a canonical representation of email address.
*   [go-email-validator (⭐51)](https://github.com/go-email-validator/go-email-validator) - Modular email validator for syntax, disposable, smtp, etc... checking.
*   [go-imap (⭐2.1k)](https://github.com/emersion/go-imap) - IMAP library for clients and servers.
*   [go-mail (⭐879)](https://github.com/wneessen/go-mail) - A simple Go library for sending mails in Go.
*   [go-message (⭐397)](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages.
*   [go-premailer (⭐154)](https://github.com/vanng822/go-premailer) - Inline styling for HTML mail in Go.
*   [go-simple-mail (⭐658)](https://github.com/xhit/go-simple-mail) - Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send.
*   [Hectane (⭐222)](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API.
*   [hermes (⭐2.9k)](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails.
*   [Maddy (⭐5.4k)](https://github.com/foxcpp/maddy) - All-in-one (SMTP, IMAP, DKIM, DMARC, MTA-STS, DANE) email server
*   [mailchain (⭐142)](https://github.com/mailchain/mailchain) - Send encrypted emails to blockchain addresses written in Go.
*   [mailgun-go (⭐710)](https://github.com/mailgun/mailgun-go) - Go library for sending mail with the Mailgun API.
*   [MailHog (⭐15k)](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface.
*   [Mailpit (⭐6.7k)](https://github.com/axllent/mailpit) - Email and SMTP testing tool for developers.
*   [mailx (⭐19)](https://github.com/valord577/mailx) - Mailx is a library that makes it easier to send email via SMTP. It is an enhancement of the golang standard library `net/smtp`.
*   [mox (⭐3.9k)](https://github.com/mjl-/mox) - Modern full-featured secure mail server for low-maintenance, self-hosted email.
*   [SendGrid (⭐993)](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email.
*   [smtp (⭐75)](https://github.com/mailhog/smtp) - SMTP server protocol state machine.
*   [smtpmock (⭐141)](https://github.com/mocktools/go-smtp-mock) - Lightweight configurable multithreaded fake SMTP server. Mimic any SMTP behaviour for your test environment.
*   [truemail-go (⭐110)](https://github.com/truemail-rb/truemail-go) - Configurable Golang email validator/verifier. Verify email via Regex, DNS, SMTP and even more.

**[⬆ back to top](#contents)**

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

*   [anko (⭐1.5k)](https://github.com/mattn/anko) - Scriptable interpreter written in Go.
*   [binder (⭐77)](https://github.com/alexeyco/binder) - Go to Lua binding library, based on [gopher-lua (⭐6.5k)](https://github.com/yuin/gopher-lua).
*   [cel-go (⭐2.4k)](https://github.com/google/cel-go) - Fast, portable, non-Turing complete expression evaluation with gradual typing.
*   [ecal (⭐44)](https://github.com/krotik/ecal) - A simple embeddable scripting language which supports concurrent event processing.
*   [expr (⭐6.6k)](https://github.com/antonmedv/expr) - Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing.
*   [gentee (⭐139)](https://github.com/gentee/gentee) - Embeddable scripting programming language.
*   [gisp (⭐517)](https://github.com/jcla1/gisp) - Simple LISP in Go.
*   [go-duktape (⭐779)](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go.
*   [go-lua (⭐3.2k)](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go.
*   [go-php (⭐937)](https://github.com/deuill/go-php) - PHP bindings for Go.
*   [go-python (⭐1.5k)](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API.
*   [goal](https://codeberg.org/anaseto/goal) - An embeddable scripting array language.
*   [goja (⭐5.9k)](https://github.com/dop251/goja) - ECMAScript 5.1(+) implementation in Go.
*   [golua (⭐663)](https://github.com/aarzilli/golua) - Go bindings for Lua C API.
*   [gopher-lua (⭐6.5k)](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go.
*   [gval (⭐774)](https://github.com/PaesslerAG/gval) - A highly customizable expression language written in Go.
*   [metacall (⭐1.6k)](https://github.com/metacall/core) - Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, WebAssembly, Java, Cobol and more.
*   [ngaro (⭐30)](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro.
*   [prolog (⭐646)](https://github.com/ichiban/prolog) - Embeddable Prolog.
*   [purl (⭐41)](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go.
*   [starlark-go (⭐2.4k)](https://github.com/google/starlark-go) - Go implementation of Starlark: Python-like language with deterministic evaluation and hermetic execution.
*   [starlet (⭐28)](https://github.com/1set/starlet) - Go wrapper for [starlark-go (⭐2.4k)](https://github.com/google/starlark-go) that simplifies script execution, offers data conversion, and useful Starlark libraries and extensions.
*   [tengo (⭐3.6k)](https://github.com/d5/tengo) - Bytecode compiled script language for Go.
*   [Wa/凹语言 (⭐1.4k)](https://github.com/wa-lang/wa) - The Wa Programming Language embedded in Go.

**[⬆ back to top](#contents)**

## Error Handling

*Libraries for handling errors.*

*   [emperror (⭐352)](https://github.com/emperror/emperror) - Error handling tools and best practices for Go libraries and applications.
*   [eris (⭐1.5k)](https://github.com/rotisserie/eris) - A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors.
*   [errlog (⭐460)](https://github.com/snwfdhmp/errlog) - Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place.
*   [errors (⭐198)](https://github.com/emperror/errors) - Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives.
*   [errors (⭐6)](https://github.com/neuronlabs/errors) - Simple golang error handling with classification primitives.
*   [errors (⭐7)](https://github.com/PumpkinSeed/errors) - The most simple error wrapper with awesome performance and minimal memory overhead.
*   [errors](https://gitlab.com/tozd/go/errors) - Providing errors with a stack trace and optional structured details. Compatible with github.com/pkg/errors API but does not use it internally.
*   [errors (⭐68)](https://github.com/naughtygopher/errors) - Drop-in replacement for builtin Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions.
*   [errors (⭐2.2k)](https://github.com/cockroachdb/errors) - Go error library with error portability over the network.
*   [errorx (⭐1.2k)](https://github.com/joomcode/errorx) - A feature rich error package with stack traces, composition of errors and more.
*   [exception (⭐35)](https://github.com/rbrahul/exception) - A simple utility package for exception handling with try-catch in Golang.
*   [Falcon (⭐11)](https://github.com/SonicRoshan/falcon) - A Simple Yet Highly Powerful Package For Error Handling.
*   [Fault (⭐173)](https://github.com/Southclaws/fault) - An ergonomic mechanism for wrapping errors in order to facilitate structured metadata and context for error values.
*   [go-multierror (⭐2.4k)](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error.
*   [multierr (⭐1.1k)](https://github.com/uber-go/multierr) - Package for representing a list of errors as a single error.
*   [oops (⭐585)](https://github.com/samber/oops) - Error handling with context, stack trace and source fragments.
*   [tracerr (⭐1.1k)](https://github.com/ztrue/tracerr) - Golang errors with stack trace and source fragments.

**[⬆ back to top](#contents)**

## File Handling

*Libraries for handling files and file systems.*

*   [afero (⭐6.1k)](https://github.com/spf13/afero) - FileSystem Abstraction System for Go.
*   [afs (⭐313)](https://github.com/viant/afs) - Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go.
*   [baraka (⭐60)](https://github.com/xis/baraka) - A library to process http file uploads easily.
*   [checksum (⭐107)](https://github.com/codingsince1985/checksum) - Compute message digest, like MD5, SHA256, SHA1, CRC or BLAKE2s, for large files.
*   [copy (⭐743)](https://github.com/otiai10/copy) - Copy directory recursively.
*   [flop (⭐33)](https://github.com/homedepot/flop) - File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html).
*   [gdu (⭐4.2k)](https://github.com/dundee/gdu) - Disk usage analyzer with console interface.
*   [go-csv-tag (⭐122)](https://github.com/artonge/go-csv-tag) - Load csv file using tag.
*   [go-decent-copy (⭐22)](https://github.com/hugocarreira/go-decent-copy) - Copy files for humans.
*   [go-exiftool (⭐260)](https://github.com/barasher/go-exiftool) - Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...).
*   [go-gtfs (⭐47)](https://github.com/artonge/go-gtfs) - Load gtfs files in go.
*   [go-wkhtmltopdf (⭐1.1k)](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) - A package to convert an HTML template to a PDF file.
*   [gofs (⭐498)](https://github.com/no-src/gofs) - A cross-platform real-time file synchronization tool out of the box.
*   [gulter (⭐62)](https://github.com/adelowo/gulter) - A simple HTTP middleware to automatically handle all your file upload needs
*   [gut/yos (⭐26)](https://github.com/1set/gut) - Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links.
*   [higgs (⭐24)](https://github.com/dastoori/higgs) - A tiny cross-platform Go library to hide/unhide files and directories.
*   [iso9660 (⭐273)](https://github.com/kdomanski/iso9660) - A package for reading and creating ISO9660 disk images
*   [notify (⭐916)](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal.
*   [opc (⭐75)](https://github.com/qmuntal/opc) - Load Open Packaging Conventions (OPC) files for Go.
*   [parquet (⭐114)](https://github.com/parsyl/parquet) - Read and write [parquet](https://parquet.apache.org) files.
*   [pathtype (⭐12)](https://github.com/jonchun/pathtype) - Treat paths as their own type instead of using strings.
*   [pdfcpu (⭐7.3k)](https://github.com/pdfcpu/pdfcpu) - PDF processor.
*   [skywalker (⭐102)](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease.
*   [todotxt (⭐25)](https://github.com/1set/todotxt) - Go library for Gina Trapani's [*todo.txt*](http://todotxt.org/) files, supports parsing and manipulating of task lists in the [*todo.txt* format](https://github.com/todotxt/todo.txt).
*   [vfs (⭐325)](https://github.com/C2FO/vfs) - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS.

**[⬆ back to top](#contents)**

## Financial

*Packages for accounting and finance.*

*   [accounting (⭐886)](https://github.com/leekchan/accounting) - money and currency formatting for golang.
*   [ach (⭐474)](https://github.com/moov-io/ach) - A reader, writer, and validator for Automated Clearing House (ACH) files.
*   [bbgo (⭐1.3k)](https://github.com/c9s/bbgo) - A crypto trading bot framework written in Go. Including common crypto exchange API, standard indicators, back-testing and many built-in strategies.
*   [currency (⭐577)](https://github.com/bojanz/currency) - Handles currency amounts, provides currency information and formatting.
*   [currency (⭐61)](https://github.com/naughtygopher/currency) - High performant & accurate currency computation package.
*   [decimal (⭐6.6k)](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers.
*   [decimal (⭐134)](https://github.com/govalues/decimal) - Immutable decimal numbers with panic-free arithmetic.
*   [fpdecimal (⭐31)](https://github.com/nikolaydubina/fpdecimal) - Fast and precise serialization and arithmetic for small fixed-point decimals
*   [fpmoney (⭐32)](https://github.com/nikolaydubina/fpmoney) - Fast and simple ISO4217 fixed-point decimal money.
*   [go-finance (⭐177)](https://github.com/alpeb/go-finance) - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations.
*   [go-finance (⭐28)](https://github.com/pieterclaerhout/go-finance) - Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers.
*   [go-finnhub (⭐93)](https://github.com/m1/go-finnhub) - Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges.
*   [go-money (⭐1.7k)](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern.
*   [go-nowpayments (⭐3)](https://github.com/matm/go-nowpayments) - Library for the crypto NOWPayments API.
*   [ledger (⭐922)](https://github.com/formancehq/ledger) - A programmable financial ledger that provides a foundation for money-moving applications.
*   [money (⭐31)](https://github.com/govalues/money) - Immutable monetary amounts and exchange rates with panic-free arithmetic.
*   [ofxgo (⭐140)](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client).
*   [orderbook (⭐462)](https://github.com/i25959341/orderbook) - Matching Engine for Limit Order Book in Golang.
*   [payme (⭐86)](https://github.com/jovandeginste/payme) - QR code generator (ASCII & PNG) for SEPA payments.
*   [sleet (⭐140)](https://github.com/BoltApp/sleet) - One unified interface for multiple Payment Service Providers (PsP) to process online payment.
*   [swift](https://code.pfad.fr/swift/) - Offline validity check of IBAN (International Bank Account Number) and retrieval of BIC (for some countries).
*   [techan (⭐851)](https://github.com/sdcoffey/techan) - Technical analysis library with advanced market analysis and trading strategies.
*   [ticker (⭐5.1k)](https://github.com/achannarasappa/ticker) - Terminal stock watcher and stock position tracker.
*   [transaction (⭐134)](https://github.com/claygod/transaction) - Embedded transactional database of accounts, running in multithreaded mode.
*   [udecimal (⭐129)](https://github.com/quagmt/udecimal) - High performance, high precision, zero allocation fixed-point decimal library for financial applications.
*   [vat (⭐112)](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates.

**[⬆ back to top](#contents)**

## Forms

*Libraries for working with forms.*

*   [bind (⭐32)](https://github.com/robfig/bind) - Bind form data to any Go values.
*   [checker (⭐37)](https://github.com/cinar/checker) - Checker helps validating user input through rules defined in struct tags or directly through functions.
*   [conform (⭐324)](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.
*   [form (⭐796)](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.
*   [formam (⭐192)](https://github.com/monoculum/formam) - decode form's values into a struct.
*   [forms (⭐140)](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.
*   [gbind (⭐10)](https://github.com/bdjimmy/gbind) - Bind data to any Go value. Can use built-in and custom expression binding capabilities; supports data validation
*   [gorilla/csrf (⭐1.1k)](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services.
*   [httpin (⭐336)](https://github.com/ggicci/httpin) - Decode an HTTP request into a custom struct, including querystring, forms, HTTP headers, etc.
*   [nosurf (⭐1.6k)](https://github.com/justinas/nosurf) - CSRF protection middleware for Go.
*   [qs (⭐77)](https://github.com/sonh/qs) - Go module for encoding structs into URL query parameters.
*   [queryparam (⭐19)](https://github.com/tomwright/queryparam) - Decode `url.Values` into usable struct values of standard or custom types.

**[⬆ back to top](#contents)**

## Functional

*Packages to support functional programming in Go.*

*   [fp-go (⭐309)](https://github.com/repeale/fp-go) - Collection of Functional Programming helpers powered by Golang 1.18+ generics.
*   [fpGo (⭐352)](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang.
*   [fuego (⭐143)](https://github.com/seborama/fuego) - Functional Experiment in Go.
*   [go-functional (⭐487)](https://github.com/BooleanCat/go-functional) - Functional programming in Go using generics
*   [go-underscore (⭐1.3k)](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.
*   [gofp (⭐148)](https://github.com/rbrahul/gofp) - A lodash like powerful utility library for Golang.
*   [mo (⭐2.8k)](https://github.com/samber/mo) - Monads and popular FP abstractions, based on Go 1.18+ Generics (Option, Result, Either...).
*   [underscore (⭐111)](https://github.com/rjNemo/underscore) - Functional programming helpers for Go 1.18 and beyond.
*   [valor (⭐17)](https://github.com/phelmkamp/valor) - Generic option and result types that optionally contain a value.

**[⬆ back to top](#contents)**

## Game Development

*Awesome game development libraries.*

*   [Arche (⭐171)](https://github.com/mlange-42/arche) - Archetype-based Entity Component System (ECS) for Go.
*   [Ebitengine (⭐12k)](https://github.com/hajimehoshi/ebiten) - dead simple 2D game engine in Go.
*   [ecs (⭐136)](https://github.com/andygeiss/ecs) - Build your own Game-Engine based on the Entity Component System concept in Golang.
*   [engo (⭐1.8k)](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.
*   [fantasyname (⭐34)](https://github.com/s0rg/fantasyname) - Fantasy names generator.
*   [g3n (⭐2.9k)](https://github.com/g3n/engine) - Go 3D Game Engine.
*   [go-astar (⭐603)](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm.
*   [go-sdl2 (⭐2.3k)](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).
*   [go3d (⭐318)](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go.
*   [gonet (⭐1.3k)](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang.
*   [goworld (⭐2.6k)](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping.
*   [grid (⭐19)](https://github.com/s0rg/grid) - Generic 2D grid with ray-casting, shadow-casting and path finding.
*   [Harfang3D (⭐595)](https://github.com/harfang3d/harfang3d) - 3D engine for the Go language, works on Windows and Linux ([Harfang on Go.dev (⭐38)](https://github.com/harfang3d/harfang-go)).
*   [Leaf (⭐5.4k)](https://github.com/name5566/leaf) - Lightweight game server framework.
*   [nano (⭐3k)](https://github.com/lonng/nano) - Lightweight, facility, high performance golang based game server framework.
*   [Oak (⭐1.6k)](https://github.com/oakmound/oak) - Pure Go game engine.
*   [Pitaya (⭐2.5k)](https://github.com/topfreegames/pitaya) - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK.
*   [Pixel (⭐288)](https://github.com/gopxl/pixel) - Hand-crafted 2D game library in Go.
*   [prototype (⭐88)](https://github.com/gonutz/prototype) - Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API.
*   [raylib-go (⭐1.9k)](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](https://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.
*   [termloop (⭐1.4k)](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox.
*   [tile (⭐180)](https://github.com/kelindar/tile) - Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export.

**[⬆ back to top](#contents)**

## Generators

*Tools that generate Go code.*

*   [convergen (⭐44)](https://github.com/reedom/convergen) - Feature rich type-to-type copy code generator.
*   [copygen (⭐365)](https://github.com/switchupcb/copygen) - Generate any code based on Go types, including type-to-type converters (copy code) without reflection by default.
*   [generis (⭐45)](https://github.com/senselogic/GENERIS) - Code generation tool providing generics, free-form macros, conditional compilation and HTML templating.
*   [go-enum (⭐796)](https://github.com/abice/go-enum) - Code generation for enums from code comments.
*   [go-enum-encoding (⭐14)](https://github.com/nikolaydubina/go-enum-encoding) - Code generation for enum encoding from code comments.
*   [go-linq (⭐3.6k)](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go.
*   [goderive (⭐1.2k)](https://github.com/awalterschulze/goderive) - Derives functions from input types
*   [goverter (⭐628)](https://github.com/jmattheis/goverter) - Generate converters by defining an interface.
*   [GoWrap (⭐1.2k)](https://github.com/hexdigest/gowrap) - Generate decorators for Go interfaces using simple templates.
*   [interfaces (⭐427)](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions.
*   [jennifer (⭐3.4k)](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates.
*   [oapi-codegen (⭐6.7k)](https://github.com/deepmap/oapi-codegen) - This package contains a set of utilities for generating Go boilerplate code for services based on OpenAPI 3.0 API definitions.
*   [typeregistry (⭐23)](https://github.com/xiaoxin01/typeregistry) - A library to create type dynamically.

**[⬆ back to top](#contents)**

## Geographic

*Geographic tools and servers*

*   [geoos (⭐509)](https://github.com/spatial-go/geoos) - A library provides spatial data and geometric algorithms.
*   [geoserver (⭐91)](https://github.com/hishamkaram/geoserver) - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API.
*   [gismanager (⭐54)](https://github.com/hishamkaram/gismanager) - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver.
*   [godal (⭐149)](https://github.com/airbusgeo/godal) - Go wrapper for GDAL.
*   [H3 (⭐332)](https://github.com/uber/h3-go) - Go bindings for H3, a hierarchical hexagonal geospatial indexing system.
*   [H3 GeoJSON (⭐4)](https://github.com/mmadfox/go-geojson2h3) - Conversion utilities between H3 indexes and GeoJSON.
*   [H3GeoDist (⭐2)](https://github.com/mmadfox/go-h3geo-dist) - Distribution of Uber H3geo cells by virtual nodes.
*   [mbtileserver (⭐687)](https://github.com/consbio/mbtileserver) - A simple Go-based server for map tiles stored in mbtiles format.
*   [osm (⭐389)](https://github.com/paulmach/osm) - Library for reading, writing and working with OpenStreetMap data and APIs.
*   [pbf (⭐49)](https://github.com/maguro/pbf) - OpenStreetMap PBF golang encoder/decoder.
*   [S2 geojson (⭐34)](https://github.com/pantrif/s2-geojson) - Convert geojson to s2 cells & demonstrating some S2 geometry features on map.
*   [S2 geometry (⭐1.7k)](https://github.com/golang/geo) - S2 geometry library in Go.
*   [simplefeatures (⭐138)](https://github.com/peterstace/simplefeatures) - simplesfeatures is a 2D geometry library that provides Go types that model geometries, as well as algorithms that operate on them.
*   [Tile38 (⭐9.3k)](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing.
*   [Web-Mercator-Projection (⭐9)](https://github.com/jorelosorio/web-mercator-projection) A project to easily use and convert LonLat, Point and Tile to display info, markers, etc, in a map using the Web Mercator Projection.
*   [WGS84 (⭐133)](https://github.com/wroge/wgs84) - Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM).

**[⬆ back to top](#contents)**

## Go Compilers

*Tools for compiling Go to other languages.*

*   [c4go (⭐368)](https://github.com/Konstantin8105/c4go) - Transpile C code to Go code.
*   [esp32 (⭐89)](https://github.com/andygeiss/esp32-transpiler) - Transpile Go into Arduino code.
*   [f4go (⭐48)](https://github.com/Konstantin8105/f4go) - Transpile FORTRAN 77 code to Go code.
*   [go2hx (⭐107)](https://github.com/go2hx/go2hx) - Compiler from Go to Haxe to Javascript/C++/Java/C#.
*   [gopherjs (⭐13k)](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript.

**[⬆ back to top](#contents)**

## Goroutines

*Tools for managing and working with Goroutines.*

*   [ants (⭐13k)](https://github.com/panjf2000/ants) - A high-performance and low-cost goroutine pool in Go.
*   [artifex (⭐211)](https://github.com/borderstech/artifex) - Simple in-memory job queue for Golang using worker-based dispatching.
*   [async (⭐10)](https://github.com/yaitoo/async) - An asynchronous task package with async/await style for Go.
*   [async (⭐235)](https://github.com/reugn/async) - An alternative sync library for Go (Future, Promise, Locks).
*   [async (⭐137)](https://github.com/studiosol/async) - A safe way to execute functions asynchronously, recovering them in case of panic.
*   [async-job (⭐11)](https://github.com/lab210-dev/async-job) - AsyncJob is an asynchronous queue job manager with light code, clear and speed.
*   [breaker (⭐18)](https://github.com/kamilsk/breaker) - Flexible mechanism to make execution flow interruptible.
*   [channelify (⭐32)](https://github.com/ddelizia/channelify) - Transform your function to return channels for easy and powerful parallel processing.
*   [conc (⭐9.7k)](https://github.com/sourcegraph/conc) - `conc` is your toolbelt for structured concurrency in go, making common tasks easier and safer.
*   [concurrency-limiter (⭐17)](https://github.com/vivek-ng/concurrency-limiter) - Concurrency limiter with support for timeouts, dynamic priority and context cancellation of goroutines.
*   [conexec (⭐16)](https://github.com/ITcathyh/conexec) - A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency.
*   [cyclicbarrier (⭐152)](https://github.com/marusama/cyclicbarrier) - CyclicBarrier for golang.
*   [execpool (⭐29)](https://github.com/hexdigest/execpool) - A pool built around exec.Cmd that spins up a given number of processes in advance and attaches stdin and stdout to them when needed. Very similar to FastCGI or Apache Prefork MPM but works for any command.
*   [flowmatic (⭐374)](https://github.com/carlmjohnson/flowmatic) - Structured concurrency made easy.
*   [go-accumulator (⭐8)](https://github.com/nar10z/go-accumulator) - Solution for accumulation of events and their subsequent processing.
*   [go-actor (⭐193)](https://github.com/vladopajic/go-actor) - A tiny library for writing concurrent programs using actor model.
*   [go-floc (⭐269)](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease.
*   [go-flow (⭐221)](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order.
*   [go-tools/multithreading (⭐16)](https://github.com/nikhilsaraf/go-tools) - Manage a pool of goroutines using this lightweight library with a simple API.
*   [go-trylock (⭐36)](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang.
*   [go-waitgroup (⭐48)](https://github.com/pieterclaerhout/go-waitgroup) - Like `sync.WaitGroup` with error handling and concurrency control.
*   [go-workerpool (⭐11)](https://github.com/zenthangplus/go-workerpool) - Inspired from Java Thread Pool, Go WorkerPool aims to control heavy Go Routines.
*   [go-workers (⭐165)](https://github.com/catmullet/go-workers) - Easily and safely run workers for large data processing pipelines.
*   [goccm (⭐73)](https://github.com/zenthangplus/goccm) - Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently.
*   [gohive (⭐53)](https://github.com/loveleshsharma/gohive) - A highly performant and easy to use Goroutine pool for Go.
*   [gollback (⭐125)](https://github.com/vardius/gollback) - asynchronous simple function utilities, for managing execution of closures and callbacks.
*   [gowl (⭐69)](https://github.com/hamed-yousefi/gowl) - Gowl is a process management and process monitoring tool at once. An infinite worker pool gives you the ability to control the pool and processes and monitor their status.
*   [goworker (⭐2.8k)](https://github.com/benmanns/goworker) - goworker is a Go-based background worker.
*   [gowp (⭐520)](https://github.com/xxjwxc/gowp) - gowp is concurrency limiting goroutine pool.
*   [gpool (⭐90)](https://github.com/Sherifabdlnaby/gpool) - manages a resizeable pool of context-aware goroutines to bound concurrency.
*   [grpool (⭐744)](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool.
*   [hands (⭐10)](https://github.com/duanckham/hands) - A process controller used to control the execution and return strategies of multiple goroutines.
*   [Hunch (⭐105)](https://github.com/AaronJan/Hunch) - Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive.
*   [kyoo (⭐49)](https://github.com/dirkaholic/kyoo) - Provides an unlimited job queue and concurrent worker pools.
*   [neilotoole/errgroup (⭐162)](https://github.com/neilotoole/errgroup) - Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines.
*   [nursery (⭐67)](https://github.com/arunsworld/nursery) - Structured concurrency in Go.
*   [oversight](https://pkg.go.dev/cirello.io/oversight) - Oversight is a complete implementation of the Erlang supervision trees.
*   [parallel-fn (⭐36)](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel.
*   [pond (⭐1.6k)](https://github.com/alitto/pond) - Minimalistic and High-performance goroutine worker pool written in Go.
*   [pool (⭐729)](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.
*   [rill (⭐1.6k)](https://github.com/destel/rill) - Go toolkit for clean, composable, channel-based concurrency.
*   [routine (⭐248)](https://github.com/timandy/routine) - `routine` is a `ThreadLocal` for go library. It encapsulates and provides some easy-to-use, non-competitive, high-performance `goroutine` context access interfaces, which can help you access coroutine context information more gracefully.
*   [routine (⭐61)](https://github.com/x-mod/routine) - go routine control with context, support: Main, Go, Pool and some useful Executors.
*   [semaphore (⭐103)](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.
*   [semaphore (⭐176)](https://github.com/marusama/semaphore) - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations).
*   [stl (⭐30)](https://github.com/ssgreg/stl) - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism.
*   [threadpool (⭐102)](https://github.com/shettyh/threadpool) - Golang threadpool implementation.
*   [tunny (⭐4k)](https://github.com/Jeffail/tunny) - Goroutine pool for golang.
*   [worker-pool (⭐92)](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool.
*   [workerpool (⭐1.4k)](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.

**[⬆ back to top](#contents)**

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

*   [app (⭐8.5k)](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.
*   [cimgui-go (⭐385)](https://github.com/AllenDang/cimgui-go) - Auto generated Go wrapper for [Dear ImGui (⭐63k)](https://github.com/ocornut/imgui) via [cimgui (⭐1.6k)](https://github.com/cimgui/cimgui).
*   [Cogent Core (⭐1.9k)](https://github.com/cogentcore/core) - A framework for building 2D and 3D apps that run on macOS, Windows, Linux, iOS, Android, and the web.
*   [DarwinKit (⭐5.1k)](https://github.com/progrium/darwinkit) - Build native macOS applications using Go.
*   [energy (⭐430)](https://github.com/energye/energy) - Cross-platform based on LCL(Native System UI Control Library) and CEF(Chromium Embedded Framework) (Windows/ macOS / Linux)
*   [fyne (⭐26k)](https://github.com/fyne-io/fyne) - Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android.
*   [gio](https://gioui.org) - Gio is a library for writing cross-platform immediate mode GUI-s in Go. Gio supports all the major platforms: Linux, macOS, Windows, Android, iOS, FreeBSD, OpenBSD and WebAssembly.
*   [go-gtk](https://mattn.github.io/go-gtk/) - Go bindings for GTK.
*   [go-sciter (⭐2.6k)](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.
*   [Goey](https://bitbucket.org/rj/goey/src/master/) - Cross platform UI toolkit aggregator for Windows / Linux / Mac. GTK, Cocoa, Windows API
*   [goradd/html5tag (⭐11)](https://github.com/goradd/html5tag) - Library for outputting HTML5 tags.
*   [gotk3 (⭐2.1k)](https://github.com/gotk3/gotk3) - Go bindings for GTK3.
*   [gowd (⭐433)](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW\.js. Cross platform.
*   [qt (⭐11k)](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).
*   [Spot (⭐1.2k)](https://github.com/roblillack/spot) - Reactive, cross-platform desktop GUI toolkit.
*   [ui (⭐8.3k)](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform.
*   [unison (⭐231)](https://github.com/richardwilkes/unison) - A unified graphical user experience toolkit for Go desktop applications. macOS, Windows, and Linux are supported.
*   [Wails](https://wails.io) - Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer.
*   [walk (⭐6.9k)](https://github.com/lxn/walk) - Windows application library kit for Go.
*   [webview (⭐13k)](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).

*Interaction*

*   [AppIndicator Go (⭐6)](https://github.com/gopherlibs/appindicator) - Go bindings for libappindicator3 C library.
*   [gosx-notifier (⭐589)](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go.
*   [mac-activity-tracker (⭐29)](https://github.com/prashantgupta24/activity-tracker) - OSX library to notify about any (pluggable) activity on your machine.
*   [mac-sleep-notifier (⭐36)](https://github.com/prashantgupta24/mac-sleep-notifier) - OSX Sleep/Wake notifications in golang.
*   [robotgo (⭐9.9k)](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.
*   [systray (⭐3.4k)](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area.
*   [trayhost (⭐254)](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar.
*   [zenity (⭐781)](https://github.com/ncruces/zenity) - Cross-platform Go library and CLI to create simple dialogs that interact graphically with the user.

**[⬆ back to top](#contents)**

## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

*   [arduino-cli (⭐4.5k)](https://github.com/arduino/arduino-cli) - Official Arduino CLI and library. Can run standalone, or be incorporated into larger Go projects.
*   [emgo (⭐1.1k)](https://github.com/ziutek/emgo) - Go-like language for programming embedded systems (e.g. STM32 MCU).
*   [ghw (⭐1.7k)](https://github.com/jaypipes/ghw) - Golang hardware discovery/inspection library.
*   [go-osc (⭐208)](https://github.com/hypebeast/go-osc) - Open Sound Control (OSC) bindings for Go.
*   [go-rpio (⭐2.2k)](https://github.com/stianeikeland/go-rpio) - GPIO for Go, doesn't require cgo.
*   [goroslib (⭐349)](https://github.com/aler9/goroslib) - Robot Operating System (ROS) library for Go.
*   [joystick (⭐65)](https://github.com/0xcafed00d/joystick) - a polled API to read the state of an attached joystick.
*   [sysinfo (⭐541)](https://github.com/zcalusic/sysinfo) - A pure Go library providing Linux OS / kernel / hardware system information.

**[⬆ back to top](#contents)**

## Images

*Libraries for manipulating images.*

*   [bild (⭐4.1k)](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go.
*   [bimg (⭐2.8k)](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips.
*   [cameron (⭐124)](https://github.com/aofei/cameron) - An avatar generator for Go.
*   [canvas (⭐1.5k)](https://github.com/tdewolff/canvas) - Vector graphics to PDF, SVG or rasterized image.
*   [color-extractor (⭐94)](https://github.com/marekm4/color-extractor) - Dominant color extractor with no external dependencies.
*   [darkroom (⭐230)](https://github.com/gojek/darkroom) - An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency.
*   [draft (⭐581)](https://github.com/lucasepe/draft) - Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax.
*   [geopattern (⭐1.3k)](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string.
*   [gg (⭐4.5k)](https://github.com/fogleman/gg) - 2D rendering in pure Go.
*   [gift (⭐1.8k)](https://github.com/disintegration/gift) - Package of image processing filters.
*   [gltf (⭐252)](https://github.com/qmuntal/gltf) - Efficient and robust glTF 2.0 reader, writer and validator.
*   [go-cairo (⭐147)](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library.
*   [go-gd (⭐59)](https://github.com/bolknote/go-gd) - Go binding for GD library.
*   [go-nude (⭐419)](https://github.com/koyachi/go-nude) - Nudity detection with Go.
*   [go-qrcode (⭐625)](https://github.com/yeqown/go-qrcode) - Generate QR codes with personalized styles, allowing adjustments to color, block size, shape, and icons.
*   [go-webcolors (⭐28)](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go.
*   [go-webp (⭐242)](https://github.com/kolesa-team/go-webp) - Library for encode and decode webp pictures, using libwebp.
*   [gocv (⭐6.9k)](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+.
*   [goimagehash (⭐774)](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package.
*   [goimghdr (⭐40)](https://github.com/corona10/goimghdr) - The imghdr module determines the type of image contained in a file for Go.
*   [govatar (⭐590)](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars.
*   [govips (⭐1.4k)](https://github.com/davidbyttow/govips) - A lightning fast image processing and resizing library for Go.
*   [gowitness (⭐3.6k)](https://github.com/sensepost/gowitness) - Screenshoting webpages using go and headless chrome on command line.
*   [gridder (⭐78)](https://github.com/shomali11/gridder) - A Grid based 2D Graphics library.
*   [image2ascii (⭐904)](https://github.com/qeesung/image2ascii) - Convert image to ASCII.
*   [imagick (⭐1.8k)](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API.
*   [imaginary (⭐5.8k)](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing.
*   [imaging (⭐5.4k)](https://github.com/disintegration/imaging) - Simple Go image processing package.
*   [imagor (⭐3.6k)](https://github.com/cshum/imagor) - Fast, secure image processing server and Go library, using libvips.
*   [img (⭐155)](https://github.com/hawx/img) - Selection of image manipulation tools.
*   [ln (⭐3.3k)](https://github.com/fogleman/ln) - 3D line art rendering in Go.
*   [mergi (⭐237)](https://github.com/noelyahan/mergi) - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate).
*   [mort (⭐512)](https://github.com/aldor007/mort) - Storage and image processing server written in Go.
*   [mpo (⭐18)](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos.
*   [picfit (⭐2.2k)](https://github.com/thoas/picfit) - An image resizing server written in Go.
*   [pt (⭐2.1k)](https://github.com/fogleman/pt) - Path tracing engine written in Go.
*   [rez (⭐213)](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD.
*   [scout (⭐16)](https://github.com/jonoton/scout) - Scout is a standalone open source software solution for DIY video security.
*   [smartcrop (⭐1.8k)](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes.
*   [steganography (⭐327)](https://github.com/auyer/steganography) - Pure Go Library for LSB steganography.
*   [stegify (⭐1.2k)](https://github.com/DimitarPetrov/stegify) - Go tool for LSB steganography, capable of hiding any file within an image.
*   [svgo (⭐2.2k)](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation.
*   [transformimgs (⭐249)](https://github.com/Pixboost/transformimgs) - Transformimgs resizes and optimises images for Web using next-generation formats.
*   [webp-server (⭐74)](https://github.com/mehdipourfar/webp-server) - Simple and minimal image server capable of storing, resizing, converting and caching images.

**[⬆ back to top](#contents)**

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

*   [connectordb (⭐411)](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT.
*   [devices (⭐264)](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io.
*   [ekuiper (⭐1.5k)](https://github.com/lf-edge/ekuiper) - Lightweight data stream processing engine for IoT edge.
*   [eywa (⭐64)](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices.
*   [flogo (⭐2.4k)](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
*   [gatt (⭐1.1k)](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals.
*   [gobot (⭐9.1k)](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things.
*   [huego (⭐252)](https://github.com/amimof/huego) - An extensive Philips Hue client library for Go.
*   [iot (⭐65)](https://github.com/vaelen/iot/) - IoT is a simple framework for implementing a Google IoT Core device.
*   [mainflux (⭐45)](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server.
*   [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.
*   [rulego (⭐979)](https://github.com/rulego/rulego) - RuleGo is a lightweight, high-performance, embedded, orchestrable component-based rule engine for IoT edge.
*   [sensorbee (⭐231)](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT.
*   [shifu (⭐1.3k)](https://github.com/Edgenesis/shifu) - Kubernetes native IoT development framework.
*   [smart-home (⭐86)](https://github.com/e154/smart-home) - Software package for IoT automation.

**[⬆ back to top](#contents)**

## Job Scheduler

*Libraries for scheduling jobs.*

*   [cdule (⭐55)](https://github.com/deepaksinghvi/cdule) - Job scheduler library with database support
*   [cheek (⭐176)](https://github.com/datarootsio/cheek) - A simple crontab like scheduler that aims to offer a KISS approach to job scheduling.
*   [clockwerk (⭐168)](https://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
*   [cronticker (⭐16)](https://github.com/krayzpipes/cronticker) - A ticker implementation to support cron schedules.
*   [go-cron (⭐236)](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
*   [go-quartz (⭐1.8k)](https://github.com/reugn/go-quartz) - Simple, zero-dependency scheduling library for Go.
*   [gocron (⭐6k)](https://github.com/go-co-op/gocron) - Easy and fluent Go job scheduling. This is an actively maintained fork of [jasonlvhit/gocron (⭐3.5k)](https://github.com/jasonlvhit/gocron).
*   [goflow (⭐428)](https://github.com/fieldryand/goflow) - A simple but powerful DAG scheduler and dashboard.
*   [gron (⭐1k)](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
*   [gronx (⭐438)](https://github.com/adhocore/gronx) - Cron expression parser, task runner and daemon consuming crontab like task list.
*   [JobRunner (⭐1.1k)](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
*   [leprechaun (⭐106)](https://github.com/kilgaloon/leprechaun) - Job scheduler that supports webhooks, crons and classic scheduling.
*   [sched (⭐28)](https://github.com/romshark/sched) - A job scheduler with the ability to fast-forward time.
*   [scheduler (⭐454)](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy.
*   [tasks (⭐309)](https://github.com/madflojo/tasks) - An easy to use in-process scheduler for recurring tasks in Go.

**[⬆ back to top](#contents)**

## JSON

*Libraries for working with JSON.*

*   [ajson (⭐256)](https://github.com/spyzhov/ajson) - Abstract JSON for golang with JSONPath support.
*   [ask (⭐50)](https://github.com/simonnilsson/ask) - Easy access to nested values in maps and slices. Works in combination with encoding/json and other packages that "Unmarshal" arbitrary data into Go data-types.
*   [dynjson (⭐16)](https://github.com/cocoonspace/dynjson) - Client-customizable JSON formats for dynamic APIs.
*   [ej (⭐10)](https://github.com/lucassscaravelli/ej) - Write and read JSON from different sources succinctly.
*   [epoch (⭐15)](https://github.com/vtopc/epoch) - Contains primitives for marshaling/unmarshalling Unix timestamp/epoch to/from build-in time.Time type in JSON.
*   [fastjson (⭐2.3k)](https://github.com/valyala/fastjson) - Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection.
*   [gabs (⭐3.5k)](https://github.com/Jeffail/gabs) - For parsing, creating and editing unknown or dynamic JSON in Go.
*   [gjo (⭐130)](https://github.com/skanehira/gjo) - Small utility to create JSON objects.
*   [GJSON (⭐15k)](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.
*   [go-jsonerror (⭐16)](https://github.com/ddymko/go-jsonerror) - Go-JsonError is meant to allow us to easily create json response errors that follow the JsonApi spec.
*   [go-respond (⭐54)](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses.
*   [gojmapr (⭐22)](https://github.com/limiu82214/gojmapr) - Get simple struct from complex json by json path.
*   [gojq (⭐190)](https://github.com/elgs/gojq) - JSON query in Golang.
*   [gojson (⭐2.7k)](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.
*   [htmljson (⭐7)](https://github.com/nikolaydubina/htmljson) - Rich rendering of JSON as HTML in Go.
*   [JayDiff (⭐105)](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go.
*   [jettison (⭐177)](https://github.com/wI2L/jettison) - Fast and flexible JSON encoder for Go.
*   [jscan (⭐93)](https://github.com/romshark/jscan) - High performance zero-allocation JSON iterator.
*   [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.
*   [JSON-to-Proto](https://json-to-proto.github.io/) - Convert JSON to Protobuf online.
*   [json2go (⭐135)](https://github.com/m-zajac/json2go) - Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all.
*   [jsonapi-errors (⭐13)](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference.
*   [jsoncolor (⭐47)](https://github.com/neilotoole/jsoncolor) - Drop-in replacement for `encoding/json` that outputs colorized JSON.
*   [jsondiff (⭐550)](https://github.com/wI2L/jsondiff) - JSON diff library for Go based on RFC6902 (JSON Patch).
*   [jsonf (⭐65)](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON.
*   [jsongo (⭐108)](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects.
*   [jsonhal (⭐14)](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
*   [jsonhandlers (⭐2)](https://github.com/abusomani/jsonhandlers) - JSON library to expose simple handlers that lets you easily read and write json from various sources.
*   [jsonic (⭐11)](https://github.com/sinhashubham95/jsonic) - Utilities to handle and query JSON without defining structs in a type safe manner.
*   [jsonvalue (⭐194)](https://github.com/Andrew-M-C/go.jsonvalue) - A fast and convenient library for unstructured JSON data, replacing `encoding/json`.
*   [jzon (⭐11)](https://github.com/zerosnake0/jzon) - JSON library with standard compatible API/behavior.
*   [kazaam (⭐284)](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.
*   [mapslice-json (⭐20)](https://github.com/mickep76/mapslice-json) - Go MapSlice for ordered marshal/ unmarshal of maps in JSON.
*   [marshmallow (⭐378)](https://github.com/PerimeterX/marshmallow) - Performant JSON unmarshalling for flexible use cases.
*   [mp (⭐47)](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON.
*   [OjG (⭐871)](https://github.com/ohler55/ojg) - Optimized JSON for Go is a high performance parser with a variety of additional JSON tools including JSONPath.
*   [omg.jsonparser (⭐6)](https://github.com/dedalqq/omg.jsonparser) - Simple JSON parser with validation by condition via golang struct fields tags.
*   [ujson (⭐82)](https://github.com/olvrng/ujson) - Fast and minimal JSON parser and transformer that works on unstructured JSON.
*   [vjson (⭐40)](https://github.com/miladibra10/vjson) - Go package for validating JSON objects with declaring a JSON schema with fluent API.

**[⬆ back to top](#contents)**

## Logging

*Libraries for generating and working with log files.*

*   [distillog (⭐31)](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels).
*   [glg (⭐189)](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go.
*   [glo (⭐16)](https://github.com/lajosbencz/glo) - PHP Monolog inspired logging facility with identical severity levels.
*   [glog (⭐3.6k)](https://github.com/golang/glog) - Leveled execution logs for Go.
*   [go-cronowriter (⭐56)](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog.
*   [go-log (⭐10)](https://github.com/pieterclaerhout/go-log) - A logging library with stack traces, object dumping and optional timestamps.
*   [go-log (⭐14)](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers.
*   [go-log (⭐35)](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.
*   [go-log (⭐43)](https://github.com/ian-kent/go-log) - Log4j implementation in Go.
*   [go-logger (⭐289)](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers.
*   [gomol (⭐19)](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs.
*   [gone/log (⭐50)](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
*   [httpretty (⭐406)](https://github.com/henvic/httpretty) - Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest).
*   [journald (⭐41)](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging.
*   [kemba (⭐14)](https://github.com/clok/kemba) - A tiny debug logging tool inspired by [debug (⭐11k)](https://github.com/visionmedia/debug), great for CLI tools and applications.
*   [lazyjournal (⭐381)](https://github.com/Lifailon/lazyjournal) - A TUI for reading and filtering logs from journalctl, file system, Docker and Podman containers, as well Kubernetes pods.
*   [log (⭐10)](https://github.com/aerogo/log) - An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection).
*   [log (⭐1.4k)](https://github.com/apex/log) - Structured logging package for Go.
*   [log (⭐293)](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go.
*   [log (⭐26)](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation.
*   [log (⭐16)](https://github.com/heartwilltell/log) - Simple leveled logging wrapper around standard log package.
*   [log (⭐3)](https://github.com/no-src/log) - A simple logging framework out of the box.
*   [log15 (⭐1.1k)](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go.
*   [logdump (⭐11)](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging.
*   [logex (⭐43)](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib.
*   [logger (⭐156)](https://github.com/azer/logger) - Minimalistic logging library for Go.
*   [logo (⭐12)](https://github.com/mbndr/logo) - Golang logger to different configurable writers.
*   [logrus (⭐25k)](https://github.com/Sirupsen/logrus) - Structured logger for Go.
*   [logrusiowriter (⭐16)](https://github.com/cabify/logrusiowriter) - `io.Writer` implementation using [logrus (⭐25k)](https://github.com/sirupsen/logrus) logger.
*   [logrusly (⭐28)](https://github.com/sebest/logrusly) - [logrus (⭐25k)](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).
*   [logur (⭐205)](https://github.com/logur/logur) - An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries ([logrus (⭐25k)](https://github.com/sirupsen/logrus), [go-kit log (⭐27k)](https://github.com/go-kit/kit/tree/master/log), [zap (⭐23k)](https://github.com/uber-go/zap), [zerolog (⭐11k)](https://github.com/rs/zerolog), etc).
*   [logutils (⭐368)](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger.
*   [logxi (⭐358)](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy.
*   [lumberjack (⭐5k)](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser.
*   [mlog (⭐33)](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
*   [noodlog (⭐44)](https://github.com/gyozatech/noodlog) - Parametrized JSON logging library which lets you obfuscate sensitive data and marshal any kind of content. No more printed pointers instead of values, nor escape chars for the JSON strings.
*   [onelog (⭐414)](https://github.com/francoispqt/onelog) - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation.
*   [ozzo-log (⭐122)](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
*   [phuslu/log (⭐727)](https://github.com/phuslu/log) - High performance structured logging.
*   [pp (⭐1.9k)](https://github.com/k0kubun/pp) - Colored pretty printer for Go language.
*   [rollingwriter (⭐298)](https://github.com/arthurkiller/rollingWriter) - RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation.
*   [seelog (⭐1.6k)](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting.
*   [slf4g (⭐3)](https://github.com/echocat/slf4g) - Simple Logging Facade for Golang: Simple structured logging; but powerful, extendable and customizable, with huge amount of learnings from decades of past logging frameworks.
*   [slog (⭐423)](https://github.com/gookit/slog) - Lightweight, configurable, extensible logger for Go.
*   [slog-formatter (⭐159)](https://github.com/samber/slog-formatter) - Common formatters for slog and helpers to build your own.
*   [slog-multi (⭐443)](https://github.com/samber/slog-multi) - Chain of slog.Handler (pipeline, fanout...).
*   [slogor](https://gitlab.com/greyxor/slogor) - A colorful slog handler.
*   [spew (⭐6.2k)](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.
*   [sqldb-logger (⭐364)](https://github.com/simukti/sqldb-logger) - A logger for Go SQL database driver without modify existing \*sql.DB stdlib usage.
*   [stdlog (⭐48)](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
*   [structy/log (⭐5)](https://github.com/structy/log) - A simple to use log system, minimalist but with features for debugging and differentiation of messages.
*   [tail (⭐2.7k)](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program.
*   [tint (⭐895)](https://github.com/lmittmann/tint) - A slog.Handler that writes tinted logs.
*   [xlog (⭐8)](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.
*   [xlog (⭐137)](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.
*   [xylog (⭐17)](https://github.com/xybor-x/xylog) - Leveled and structured logging, dynamic fields, high performance, zone management, simple configuration, and readable syntax.
*   [yell (⭐1)](https://github.com/jfcg/yell) - Yet another minimalistic logging library.
*   [zap (⭐23k)](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go.
*   [zax (⭐26)](https://github.com/yuseferi/zax) - Integrate Context with Zap logger, which leads to more flexibility in Go logging.
*   [zerolog (⭐11k)](https://github.com/rs/zerolog) - Zero-allocation JSON logger.
*   [zkits-logger (⭐28)](https://github.com/edoger/zkits-logger) - A powerful zero-dependency JSON logger.
*   [zl (⭐6)](https://github.com/nkmr-jp/zl) - High Developer Experience, zap based logger. It offers rich functionality but is easy to configure.

**[⬆ back to top](#contents)**

## Machine Learning

*Libraries for Machine Learning.*

*   [bayesian (⭐804)](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang.
*   [catboost-cgo (⭐13)](https://github.com/mirecl/catboost-cgo) - Fast, scalable, high performance Gradient Boosting on Decision Trees library. Golang using Cgo for blazing fast inference CatBoost Model.
*   [CloudForest (⭐741)](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.
*   [ddt (⭐38)](https://github.com/sgrodriguez/ddt) - Dynamic decision tree, create trees defining customizable rules.
*   [eaopt (⭐892)](https://github.com/MaxHalford/eaopt) - An evolutionary optimization library.
*   [evoli (⭐33)](https://github.com/khezen/evoli) - Genetic Algorithm and Particle Swarm Optimization library.
*   [fonet (⭐84)](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go.
*   [go-cluster (⭐43)](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms.
*   [go-deep (⭐539)](https://github.com/patrikeh/go-deep) - A feature-rich neural network library in Go.
*   [go-fann (⭐116)](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library.
*   [go-featureprocessing (⭐119)](https://github.com/nikolaydubina/go-featureprocessing) - Fast and convenient feature processing for low latency machine learning in Go.
*   [go-galib (⭐200)](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang.
*   [go-pr (⭐67)](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang.
*   [gobrain (⭐565)](https://github.com/goml/gobrain) - Neural Networks written in go.
*   [godist (⭐42)](https://github.com/e-dard/godist) - Various probability distributions, and associated methods.
*   [goga (⭐222)](https://github.com/tomcraven/goga) - Genetic algorithm library for Go.
*   [GoLearn (⭐9.3k)](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go.
*   [golinear (⭐45)](https://github.com/danieldk/golinear) - liblinear bindings for Go.
*   [GoMind (⭐86)](https://github.com/surenderthakran/gomind) - A simplistic Neural Network Library in Go.
*   [goml (⭐1.6k)](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go.
*   [GoMLX (⭐682)](https://github.com/gomlx/gomlx) - An accelerated Machine Learning framework for Go.
*   [gonet (⭐82)](https://github.com/dathoangnd/gonet) - Neural Network for Go.
*   [Goptuna (⭐264)](https://github.com/c-bata/goptuna) - Bayesian optimization framework for black-box functions written in Go. Everything will be optimized.
*   [goRecommend (⭐206)](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go.
*   [gorgonia (⭐5.6k)](https://github.com/gorgonia/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.
*   [gorse (⭐8.8k)](https://github.com/zhenghaoz/gorse) - An offline recommender system backend based on collaborative filtering written in Go.
*   [goscore (⭐100)](https://github.com/asafschers/goscore) - Go Scoring API for PMML.
*   [gosseract (⭐2.8k)](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.
*   [hugot (⭐359)](https://github.com/knights-analytics/hugot) - Huggingface transformer pipelines for golang with onnxruntime.
*   [libsvm (⭐73)](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.
*   [m2cgen (⭐2.8k)](https://github.com/BayesWitnesses/m2cgen) - A CLI tool to transpile trained classic ML models into a native Go code with zero dependencies, written in Python with Go language support.
*   [neural-go (⭐70)](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation.
*   [ocrserver (⭐721)](https://github.com/otiai10/ocrserver) - A simple OCR API server, seriously easy to be deployed by Docker and Heroku.
*   [onnx-go (⭐749)](https://github.com/owulveryck/onnx-go) - Go Interface to Open Neural Network Exchange (ONNX).
*   [probab (⭐20)](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go.
*   [randomforest (⭐50)](https://github.com/malaschitz/randomForest) - Easy to use Random Forest library for Go.
*   [regommend (⭐314)](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine.
*   [shield (⭐158)](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go.
*   [tfgo (⭐2.4k)](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.
*   [Varis (⭐54)](https://github.com/Xamber/Varis) - Golang Neural Network.

**[⬆ back to top](#contents)**

## Messaging

*Libraries that implement messaging systems.*

*   [ami (⭐30)](https://github.com/kak-tus/ami) - Go client to reliable queues based on Redis Cluster Streams.
*   [amqp (⭐1.7k)](https://github.com/rabbitmq/amqp091-go) - Go RabbitMQ Client Library.
*   [APNs2 (⭐3.1k)](https://github.com/sideshow/apns2) - HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps.
*   [Asynq (⭐11k)](https://github.com/hibiken/asynq) - A simple, reliable, and efficient distributed task queue for Go built on top of Redis.
*   [Beaver (⭐1.6k)](https://github.com/Clivern/Beaver) - A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps.
*   [Bus (⭐343)](https://github.com/mustafaturan/bus) - Minimalist message bus implementation for internal communication.
*   [Centrifugo (⭐8.8k)](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go.
*   [Chanify (⭐1.3k)](https://github.com/chanify/chanify) - A push notification server send message to your iOS devices.
*   [Commander (⭐67)](https://github.com/jeroenrinzema/commander) - A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka.
*   [Confluent Kafka Golang Client (⭐4.8k)](https://github.com/confluentinc/confluent-kafka-go) - confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform.
*   [dbus (⭐1k)](https://github.com/godbus/dbus) - Native Go bindings for D-Bus.
*   [drone-line (⭐80)](https://github.com/appleboy/drone-line) - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI.
*   [emitter (⭐513)](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.
*   [event (⭐58)](https://github.com/agoalofalife/event) - Implementation of the pattern observer.
*   [EventBus (⭐1.8k)](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility.
*   [gaurun-client (⭐11)](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go.
*   [Glue (⭐418)](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io).
*   [go-eventbus (⭐7)](https://github.com/stanipetrosyan/go-eventbus) - Simple Event Bus package for Go.
*   [Go-MediatR (⭐222)](https://github.com/mehdihadeli/Go-MediatR) - A library for handling mediator patterns and simplified CQRS patterns within an event-driven architecture, inspired by csharp MediatR library.
*   [go-mq (⭐90)](https://github.com/cheshir/go-mq) - RabbitMQ client with declarative configuration.
*   [go-notify (⭐71)](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec.
*   [go-nsq (⭐2.6k)](https://github.com/nsqio/go-nsq) - the official Go package for NSQ.
*   [go-res (⭐65)](https://github.com/jirenius/go-res) - Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate.
*   [go-socket.io (⭐5.8k)](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.
*   [go-vitotrol (⭐23)](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service.
*   [Gollum (⭐941)](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.
*   [golongpoll (⭐661)](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple.
*   [gopush-cluster (⭐2.1k)](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster.
*   [gorush (⭐8.2k)](https://github.com/appleboy/gorush) - Push notification server using [APNs2 (⭐3.1k)](https://github.com/sideshow/apns2) and google [GCM (⭐105)](https://github.com/google/go-gcm).
*   [gosd (⭐26)](https://github.com/alexsniffin/gosd) - A library for scheduling when to dispatch a message to a channel.
*   [guble (⭐160)](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.
*   [hare (⭐53)](https://github.com/leozz37/hare) - A user friendly library for sending messages and listening to TCP sockets.
*   [hub (⭐146)](https://github.com/leandro-lugaresi/hub) - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges.
*   [hypermatch (⭐23)](https://github.com/SchwarzIT/hypermatch) - A very fast and efficient Go library for matching events to a large set of rules
*   [jazz (⭐18)](https://github.com/socifi/jazz) - A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages.
*   [machinery (⭐7.6k)](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing.
*   [mangos (⭐696)](https://github.com/nanomsg/mangos) - Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability.
*   [melody (⭐3.9k)](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.
*   [Mercure (⭐4.8k)](https://github.com/dunglas/mercure) - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events).
*   [messagebus (⭐273)](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.
*   [NATS Go Client (⭐5.7k)](https://github.com/nats-io/nats.go) - Go client for the NATS
    messaging system.
*   [nsq-event-bus (⭐79)](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel.
*   [oplog (⭐111)](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs.
*   [pubsub (⭐432)](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go.
*   [Quamina (⭐423)](https://github.com/timbray/quamina) - Fast pattern-matching for filtering messages and events.
*   [rabbitroutine (⭐111)](https://github.com/furdarius/rabbitroutine) - Lightweight library that handles RabbitMQ auto-reconnect and publishing retries. The library takes into account the need to re-declare entities in RabbitMQ after reconnection.
*   [rabbus (⭐97)](https://github.com/rafaeljesus/rabbus) - A tiny wrapper over amqp exchanges and queues.
*   [rabtap (⭐265)](https://github.com/jandelgado/rabtap) - RabbitMQ swiss army knife cli app.
*   [RapidMQ (⭐68)](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue.
*   [Ratus (⭐114)](https://github.com/hyperonym/ratus) - Ratus is a RESTful asynchronous task queue server.
*   [redisqueue (⭐131)](https://github.com/robinjoseph08/redisqueue) - redisqueue provides a producer and consumer of a queue that uses Redis streams.
*   [rmqconn (⭐23)](https://github.com/sbabiv/rmqconn) - RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed.
*   [sarama (⭐12k)](https://github.com/Shopify/sarama) - Go library for Apache Kafka.
*   [Uniqush-Push (⭐1.5k)](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices.
*   [Watermill (⭐8.1k)](https://github.com/ThreeDotsLabs/watermill) - Working efficiently with message streams. Building event driven applications, enabling event sourcing, RPC over messages, sagas. Can use conventional pub/sub implementations like Kafka or RabbitMQ, but also HTTP or MySQL binlog.
*   [zmq4 (⭐1.2k)](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [version 3 (⭐133)](https://github.com/pebbe/zmq3) and [version 2 (⭐19)](https://github.com/pebbe/zmq2).

**[⬆ back to top](#contents)**

## Microsoft Office

*   [unioffice (⭐4.5k)](https://github.com/unidoc/unioffice) - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents.

### Microsoft Excel

*Libraries for working with Microsoft Excel.*

*   [excelize (⭐19k)](https://github.com/xuri/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files.
*   [exl (⭐31)](https://github.com/go-the-way/exl) - Excel binding to struct written in Go.(Only supports Go1.18+)
*   [go-excel (⭐194)](https://github.com/szyhf/go-excel) - A simple and light reader to read a relate-db-like excel as a table.
*   [goxlsxwriter (⭐21)](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.
*   [xlsx (⭐5.9k)](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.
*   [xlsx (⭐174)](https://github.com/plandem/xlsx) - Fast and safe way to read/update your existing Microsoft Excel files in Go programs.

### Microsoft Word

*Libraries for working with Microsoft Word.*

*   [godocx (⭐145)](https://github.com/gomutex/godocx) - Library for reading and writing Microsoft Word (Docx) files.

**[⬆ back to top](#contents)**

## Miscellaneous

### Dependency Injection

*Libraries for working with dependency injection.*

*   [alice (⭐50)](https://github.com/magic003/alice) - Additive dependency injection container for Golang.
*   [autowire (⭐10)](https://github.com/tiendc/autowire) - Dependency injection using Generics and reflection.
*   [boot-go (⭐34)](http://github.com/boot-go/boot) - Component-based development with dependency injection using reflections for Go developers.
*   [componego (⭐26)](https://github.com/componego/componego) - A dependency injection framework based on components, allowing dynamic dependency replacement without duplicating code in tests.
*   [cosban/di](https://gitlab.com/cosban/di) - A code generation based dependency injection wiring tool.
*   [di (⭐235)](https://github.com/goava/di) - A dependency injection container for go programming language.
*   [dig (⭐4k)](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go.
*   [dingo (⭐181)](https://github.com/i-love-flamingo/dingo) - A dependency injection toolkit for Go, based on Guice.
*   [do (⭐2k)](https://github.com/samber/do) - A dependency injection framework based on Generics.
*   [fx (⭐6.2k)](https://github.com/uber-go/fx) - A dependency injection based application framework for Go (built on top of dig).
*   [gocontainer (⭐21)](https://github.com/vardius/gocontainer) - Simple Dependency Injection Container.
*   [goioc/di (⭐363)](https://github.com/goioc/di) - Spring-inspired Dependency Injection Container.
*   [GoLobby/Container (⭐574)](https://github.com/golobby/container) - GoLobby Container is a lightweight yet powerful IoC dependency injection container for the Go programming language.
*   [gontainer (⭐42)](https://github.com/NVIDIA/gontainer) - A dependency injection service container for Go projects.
*   [gontainer/gontainer (⭐15)](https://github.com/gontainer/gontainer) - A YAML-based Dependency Injection container for GO. It supports dependencies' scopes, and auto-detection of circular dependencies. Gontainer is concurrent-safe.
*   [google/wire (⭐13k)](https://github.com/google/wire) - Automated Initialization in Go.
*   [HnH/di (⭐8)](https://github.com/HnH/di) - DI container library that is focused on clean API and flexibility.
*   [kinit (⭐10)](https://github.com/go-kata/kinit) - Customizable dependency injection container with the global mode, cascade initialization and panic-safe finalization.
*   [kod (⭐177)](https://github.com/go-kod/kod) - A generics based dependency injection framework for Go.
*   [linker (⭐35)](https://github.com/logrange/linker) - A reflection based dependency injection and inversion of control library with components lifecycle support.
*   [nject (⭐30)](https://github.com/muir/nject) - A type safe, reflective framework for libraries, tests, http endpoints, and service startup.
*   [ore (⭐16)](https://github.com/firasdarwish/ore) - Lightweight, generic & simple dependency injection (DI) container.
*   [wire (⭐38)](https://github.com/Fs02/wire) - Strict Runtime Dependency Injection for Golang.

**[⬆ back to top](#contents)**

### Project Layout

***Unofficial** set of patterns for structuring projects.*

*   [ardanlabs/service (⭐3.7k)](https://github.com/ardanlabs/service) - A [starter kit (⭐3.7k)](https://github.com/ardanlabs/service/wiki) for building production grade scalable web service applications.
*   [cookiecutter-golang (⭐701)](https://github.com/lacion/cookiecutter-golang) - A Go application boilerplate template for quick starting projects following production best practices.
*   [go-blueprint (⭐6.9k)](https://github.com/Melkeydev/go-blueprint) - Allows users to spin up a quick Go project using a popular framework.
*   [go-module (⭐32)](https://github.com/octomation/go-module) - Template for a typical module written on Go.
*   [go-sample (⭐133)](https://github.com/zitryss/go-sample) - A sample layout for Go application projects with the real code.
*   [go-starter (⭐518)](https://github.com/allaboutapps/go-starter) - An opinionated production-ready RESTful JSON backend template, highly integrated with VSCode DevContainers.
*   [go-todo-backend (⭐323)](https://github.com/Fs02/go-todo-backend) - Go Todo Backend example using modular project layout for product microservice.
*   [gobase (⭐62)](https://github.com/wajox/gobase) - A simple skeleton for golang application with basic setup for real golang application.
*   [golang-standards/project-layout (⭐51k)](https://github.com/golang-standards/project-layout) - Set of common historical and emerging project layout patterns in the Go ecosystem. Note: despite the org-name they do not represent official golang standards, see [this issue (⭐51k)](https://github.com/golang-standards/project-layout/issues/117) for more information. Nonetheless, some may find the layout useful.
*   [golang-templates/seed (⭐499)](https://github.com/golang-templates/seed) - Go application GitHub repository template.
*   [goxygen (⭐3.6k)](https://github.com/shpota/goxygen) - Generate a modern Web project with Go and Angular, React, or Vue in seconds.
*   [insidieux/inizio (⭐18)](https://github.com/insidieux/inizio) - Golang project layout generator with plugins.
*   [kickstart.go (⭐81)](https://github.com/raeperd/kickstart.go) - Minimalistic single-file Go HTTP server template without third-party dependencies.
*   [modern-go-application (⭐1.9k)](https://github.com/sagikazarmark/modern-go-application) - Go application boilerplate and example applying modern practices.
*   [nunu (⭐2.1k)](https://github.com/go-nunu/nunu) - Nunu is a scaffolding tool for building Go applications.
*   [pagoda (⭐2.3k)](https://github.com/mikestefanello/pagoda) - Rapid, easy full-stack web development starter kit built in Go.
*   [scaffold (⭐149)](https://github.com/catchplay/scaffold) - Scaffold generates a starter Go project layout. Lets you focus on business logic implemented.
*   [wangyoucao577/go-project-layout (⭐26)](https://github.com/wangyoucao577/go-project-layout) - Set of practices and discussions on how to structure Go project layout.

**[⬆ back to top](#contents)**

### Strings

*Libraries for working with strings.*

*   [bexp (⭐21)](https://github.com/happy-sdk/happy/tree/main/pkg/strings/bexp) - Go implementation of Brace Expansion mechanism to generate arbitrary strings.
*   [caps (⭐58)](https://github.com/chanced/caps) - A case conversion library.
*   [go-formatter](https://gitlab.com/tymonx/go-formatter) - Implements **replacement fields** surrounded by curly braces `{}` format strings.
*   [gobeam/Stringy (⭐241)](https://github.com/gobeam/Stringy) - String manipulation library to convert string to camel case, snake case, kebab case / slugify etc.
*   [strcase (⭐7)](https://github.com/charlievieth/strcase) - Case-insensitive implementation of the standard library's strings/bytes packages.
*   [strutil (⭐207)](https://github.com/ozgio/strutil) - String utilities.
*   [sttr (⭐991)](https://github.com/abhimanyu003/sttr) - cross-platform, cli app to perform various operations on string.
*   [xstrings (⭐1.4k)](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages.

**[⬆ back to top](#contents)**

### Uncategorized

*These libraries were placed here because none of the other categories seemed to fit.*

*   [anagent (⭐15)](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection.
*   [antch (⭐262)](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework.
*   [archives (⭐174)](https://github.com/mholt/archives) - a cross-platform, multi-format Go library for working with archives and compression formats with a unified API and as virtual file systems compatible with io/fs.
*   [autoflags (⭐44)](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields.
*   [avgRating (⭐18)](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation.
*   [banner (⭐456)](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications.
*   [base64Captcha (⭐2.2k)](https://github.com/mojocn/base64Captcha) - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha.
*   [basexx (⭐5)](https://github.com/bobg/basexx) - Convert to, from, and between digit strings in various number bases.
*   [battery (⭐254)](https://github.com/distatus/battery) - Cross-platform, normalized battery information library.
*   [bitio (⭐248)](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go.
*   [browscap\_go (⭐49)](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](https://browscap.org/).
*   [captcha (⭐157)](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation.
*   [common (⭐4)](https://github.com/kubeservice-stack/common) - A library for server framework.
*   [conv (⭐382)](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types.
*   [datacounter (⭐49)](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter.
*   [faker (⭐97)](https://github.com/pioz/faker) - Random fake data and struct generator for Go.
*   [ffmt (⭐310)](https://github.com/go-ffmt/ffmt) - Beautify data display for Humans.
*   [gatus (⭐7.1k)](https://github.com/TwinProduction/gatus) - Automated service health dashboard.
*   [go-commandbus (⭐13)](https://github.com/lana/go-commandbus) - A slight and pluggable command-bus for Go.
*   [go-commons-pool (⭐1.2k)](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang.
*   [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
*   [go-resiliency (⭐2.3k)](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang.
*   [go-unarr (⭐288)](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives.
*   [gofakeit (⭐4.8k)](https://github.com/brianvoe/gofakeit) - Random data generator written in go.
*   [gommit (⭐114)](https://github.com/antham/gommit) - Analyze git commit messages to ensure they follow defined patterns.
*   [gopsutil (⭐11k)](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
*   [gosh (⭐36)](https://github.com/osamingo/gosh) - Provide Go Statistics Handler, Struct, Measure Method.
*   [gosms (⭐1.5k)](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS.
*   [gotoprom (⭐107)](https://github.com/cabify/gotoprom) - Type-safe metrics builder wrapper library for the official Prometheus client.
*   [gountries (⭐411)](https://github.com/pariz/gountries) - Package that exposes country and subdivision data.
*   [gtree (⭐262)](https://github.com/ddddddO/gtree) - Provide CLI, Package and Web for tree output and directories creation from Markdown or programmatically.
*   [health (⭐796)](https://github.com/alexliesenfeld/health) - A simple and flexible health check library for Go.
*   [health (⭐450)](https://github.com/dimiro1/health) - Easy to use, extensible health check library.
*   [healthcheck (⭐271)](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services.
*   [hostutils (⭐13)](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list.
*   [indigo (⭐109)](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58.
*   [lk (⭐377)](https://github.com/hyperboloide/lk) - A simple licensing library for golang.
*   [llvm (⭐1.2k)](https://github.com/llir/llvm) - Library for interacting with LLVM IR in pure Go.
*   [metrics (⭐27)](https://github.com/pascaldekloe/metrics) - Library for metrics instrumentation and Prometheus exposition.
*   [morse (⭐83)](https://github.com/alwindoss/morse) - Library to convert to and from morse code.
*   [numa (⭐32)](https://github.com/lrita/numa) - NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code.
*   [openapi (⭐11)](https://github.com/neotoolkit/openapi) - OpenAPI 3.x parser.
*   [pdfgen (⭐72)](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests.
*   [persian (⭐87)](https://github.com/mavihq/persian) - Some utilities for Persian language in go.
*   [sandid (⭐47)](https://github.com/aofei/sandid) - Every grain of sand on earth has its own ID.
*   [shellwords (⭐25)](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.
*   [shortid (⭐943)](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
*   [shoutrrr (⭐1.1k)](https://github.com/containrrr/shoutrrr) - Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others.
*   [sitemap-format (⭐5)](https://github.com/mingard/sitemap-format) - A simple sitemap generator, with a little syntactic sugar.
*   [stateless (⭐1k)](https://github.com/qmuntal/stateless) - A fluent library for creating state machines.
*   [stats (⭐170)](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
*   [turtle (⭐163)](https://github.com/hackebrot/turtle) - Emojis for Go.
*   [url-shortener (⭐49)](https://github.com/pantrif/url-shortener) - A modern, powerful, and robust URL shortener microservice with mysql support.
*   [VarHandler (⭐6)](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and output handling.
*   [varint (⭐15)](https://github.com/chmike/varint) - A faster varying length integer encoder/decoder than the one provided in the standard library.
*   [xdg (⭐47)](https://github.com/rkoesters/xdg) - FreeDesktop.org (xdg) Specs implemented in Go.
*   [xkg (⭐59)](https://github.com/go-xkg/xkg) - X Keyboard Grabber.
*   [xz (⭐491)](https://github.com/ulikunitz/xz) - Pure golang package for reading and writing xz-compressed files.

**[⬆ back to top](#contents)**

## Natural Language Processing

*Libraries for working with human languages.*

See also [Text Processing](#text-processing) and [Text Analysis](#text-analysis).

### Language Detection

*   [detectlanguage (⭐25)](https://github.com/detectlanguage/detectlanguage-go) - Language Detection API Go Client. Supports batch requests, short phrase or single word language detection.
*   [getlang (⭐172)](https://github.com/rylans/getlang) - Fast natural language detection package.
*   [guesslanguage (⭐58)](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text.
*   [lingua-go (⭐1.2k)](https://github.com/pemistahl/lingua-go) - An accurate natural language detection library, suitable for long and short text alike. Supports detecting multiple languages in mixed-language text.
*   [whatlanggo (⭐649)](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).

### Morphological Analyzers

*   [go-stem (⭐81)](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm.
*   [go2vec (⭐55)](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings.
*   [golibstemmer (⭐21)](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2.
*   [gosentiwordnet (⭐10)](https://github.com/dinopuguh/gosentiwordnet) - Sentiment analyzer using sentiwordnet lexicon in Go.
*   [govader (⭐46)](https://github.com/jonreiter/govader) - Go implementation of [VADER Sentiment Analysis (⭐4.6k)](https://github.com/cjhutto/vaderSentiment).
*   [govader-backend (⭐6)](https://github.com/PIMPfiction/govader_backend) - Microservice implementation of [GoVader (⭐46)](https://github.com/jonreiter/govader).
*   [kagome (⭐849)](https://github.com/ikawaha/kagome) - JP morphological analyzer written in pure Go.
*   [libtextcat (⭐13)](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
*   [nlp (⭐386)](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp.
*   [nlp (⭐454)](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).
*   [paicehusk (⭐29)](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm.
*   [porter (⭐12)](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
*   [porter2 (⭐45)](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer.
*   [RAKE.go (⭐118)](https://github.com/afjoseph/RAKE.Go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
*   [snowball (⭐37)](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).
*   [spaGO (⭐1.8k)](https://github.com/nlpodyssey/spago) - Self-contained Machine Learning and Natural Language Processing library in Go.
*   [spelling-corrector (⭐2)](https://github.com/jorelosorio/spellingcorrector) - A spelling corrector for the Spanish language or create your own.

### Slugifiers

*   [go-slugify (⭐94)](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support.
*   [slug (⭐1.2k)](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support.
*   [Slugify (⭐33)](https://github.com/avelino/slugify) - Go slugify application that handles string.

### Tokenizers

*   [gojieba (⭐2.5k)](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [jieba (⭐34k)](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm.
*   [gotokenizer (⭐22)](https://github.com/xujiajun/gotokenizer) - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation)
*   [gse (⭐2.6k)](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other.
*   [MMSEGO (⭐62)](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm.
*   [prose (⭐3.1k)](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only.
*   [segment (⭐89)](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](https://www.unicode.org/reports/tr29/)
*   [sentences (⭐443)](https://github.com/neurosnap/sentences) - Sentence tokenizer: converts text into a list of sentences.
*   [shamoji (⭐13)](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go.
*   [stemmer (⭐53)](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers.
*   [textcat (⭐72)](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text.

### Translation

*   [ctxi18n (⭐61)](https://github.com/invopop/ctxi18n/) - Context aware i18n with a short and consise API, pluralization, interpolation, and `fs.FS` support. YAML locale definitions are based on [Rails i18n](https://guides.rubyonrails.org/i18n.html).
*   [go-i18n (⭐3.1k)](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text.
*   [go-mystem (⭐34)](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer.
*   [go-pinyin (⭐1.7k)](https://github.com/mozillazg/go-pinyin) - CN Hanzi to Hanyu Pinyin converter.
*   [go-words (⭐6)](https://github.com/saleh-rahimzadeh/go-words) - A words table and text resource library for Golang projects.
*   [gotext (⭐447)](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go.
*   [iuliia-go (⭐50)](https://github.com/mehanizm/iuliia-go) - Transliterate Cyrillic → Latin in every possible way.
*   [spreak (⭐59)](https://github.com/vorlif/spreak) - Flexible translation and humanization library for Go, based on the concepts behind gettext.
*   [t (⭐20)](https://github.com/youthlin/t) - Another i18n pkg for golang, which follows GNU gettext style and supports .po/.mo files: `t.T (gettext)`, `t.N (ngettext)`, etc. And it contains a cmd tool [xtemplate (⭐20)](https://github.com/youthlin/t/blob/main/cmd/xtemplate), which can extract messages as a pot file from text/html template.

### Transliteration

*   [enca (⭐17)](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](https://cihar.com/software/enca/), which detects character encodings.
*   [go-unidecode (⭐135)](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text.
*   [gounidecode (⭐80)](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go.
*   [transliterator (⭐43)](https://github.com/alexsergivan/transliterator) - Provides one-way string transliteration with supporting of language-specific transliteration rules.

**[⬆ back to top](#contents)**

## Networking

*Libraries for working with various layers of the network.*

*   [arp (⭐370)](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826.
*   [bart (⭐56)](https://github.com/gaissmai/bart) - Package bart provides a fast routing table algorithm.
*   [buffstreams (⭐254)](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy.
*   [canopus (⭐156)](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252).
*   [cidranger (⭐918)](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go.
*   [cloudflared (⭐9.9k)](https://github.com/cloudflare/cloudflared) - Cloudflare Tunnel client (formerly Argo Tunnel).
*   [dhcp6 (⭐77)](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
*   [dns (⭐8.2k)](https://github.com/miekg/dns) - Go library for working with DNS.
*   [dnsmonster (⭐322)](https://github.com/mosajjal/dnsmonster) - Passive DNS Capture/Monitoring Framework.
*   [easytcp (⭐817)](https://github.com/DarthPestilane/easytcp) - A light-weight TCP framework written in Go (Golang), built with message router. EasyTCP helps you build a TCP server easily fast and less painful.
*   [ether (⭐80)](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames.
*   [ethernet (⭐280)](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshalling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
*   [event (⭐120)](https://github.com/cheng-zhongliang/event) - Simple I/O event notification library written in Golang.
*   [fasthttp (⭐22k)](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
*   [fortio (⭐3.4k)](https://github.com/fortio/fortio) - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC.
*   [ftp (⭐1.3k)](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](https://tools.ietf.org/html/rfc959).
*   [ftpserverlib (⭐444)](https://github.com/fclairamb/ftpserverlib) - Fully featured FTP server library.
*   [fullproxy (⭐81)](https://github.com/shoriwe/fullproxy) - A fully featured scriptable and daemon configurable proxy and pivoting toolkit with SOCKS5, HTTP, raw ports and reverse proxy protocols.
*   [fwdctl (⭐61)](https://github.com/alegrey91/fwdctl) - A simple and intuitive CLI to manage IPTables forwards in your Linux server.
*   [gaio (⭐777)](https://github.com/xtaci/gaio) - High performance async-io networking for Golang in proactor mode.
*   [gev (⭐1.7k)](https://github.com/Allenxuxu/gev) - gev is a lightweight, fast non-blocking TCP network library based on Reactor mode.
*   [gldap (⭐114)](https://github.com/jimlambrt/gldap) - gldap provides an ldap server implementation and you provide handlers for its ldap operations.
*   [gmqtt (⭐991)](https://github.com/DrmagicE/gmqtt) - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1.
*   [gnet (⭐10k)](https://github.com/panjf2000/gnet) - `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go.
*   [gnet (⭐20)](https://github.com/fish-tennis/gnet) - `gnet` is a high-performance networking framework,especially for game servers.
*   [gNxI (⭐265)](https://github.com/google/gnxi) - A collection of tools for Network Management that use the gNMI and gNOI protocols.
*   [go-getter (⭐1.7k)](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL.
*   [go-multiproxy (⭐9)](https://github.com/presbrey/go-multiproxy) - Library for making HTTP requests through a pool of proxies offering fault tolerance, load balancing, automatic retries, cookie management, and more, via http.Get/Post replacement or http.Client RoundTripper drop-in
*   [go-powerdns (⭐92)](https://github.com/joeig/go-powerdns) - PowerDNS API bindings for Golang.
*   [go-sse (⭐12)](https://github.com/lampctl/go-sse) - Go client and server implementation of HTML server-sent events.
*   [go-stun (⭐689)](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389).
*   [gobgp (⭐3.7k)](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.
*   [gopacket (⭐6.5k)](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings.
*   [gopcap (⭐491)](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap.
*   [GoProxy (⭐6.2k)](https://github.com/elazarl/goproxy) - A library to create a customized HTTP/HTTPS proxy server using Go.
*   [goshark (⭐19)](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
*   [gosnmp (⭐1.2k)](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions.
*   [gotcp (⭐513)](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications.
*   [grab (⭐1.4k)](https://github.com/cavaliercoder/grab) - Go package for managing file downloads.
*   [graval (⭐28)](https://github.com/koofr/graval) - Experimental FTP server framework.
*   [gws (⭐1.5k)](https://github.com/lxzan/gws) - High-Performance WebSocket Server & Client With AsyncIO Supporting .
*   [HTTPLab (⭐4.1k)](https://github.com/gchaincl/httplab) - HTTPLabs let you inspect HTTP requests and forge responses.
*   [httpproxy (⭐27)](https://github.com/wzshiming/httpproxy) - HTTP proxy handler and dialer.
*   [iplib (⭐146)](https://github.com/c-robinson/iplib) - Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)
*   [jazigo (⭐219)](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.
*   [kcp-go (⭐4.2k)](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol.
*   [kcptun (⭐14k)](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.
*   [lhttp (⭐690)](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily.
*   [linkio (⭐53)](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces.
*   [llb (⭐16)](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
*   [mdns (⭐1.2k)](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang.
*   [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
*   [natiu-mqtt (⭐89)](https://github.com/soypat/natiu-mqtt) - A dead-simple, non-allocating, low level implementation of MQTT well suited for embedded systems.
*   [nbio (⭐2.4k)](https://github.com/lesismal/nbio) - Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use.
*   [net](https://golang.org/x/net) - This repository holds supplementary Go networking libraries.
*   [netpoll (⭐4.2k)](https://github.com/cloudwego/netpoll) - A high-performance non-blocking I/O networking framework, which focused on RPC scenarios, developed by ByteDance.
*   [NFF-Go (⭐1.4k)](https://github.com/intel-go/nff-go) - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF).
*   [peerdiscovery (⭐653)](https://github.com/schollz/peerdiscovery) - Pure Go library for cross-platform local peer discovery using UDP multicast.
*   [portproxy (⭐57)](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it.
*   [psql-wire (⭐126)](https://github.com/jeroenrinzema/psql-wire) - PostgreSQL server wire protocol. Build your own server and start serving connections..
*   [publicip (⭐29)](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress).
*   [quic-go (⭐10k)](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go.
*   [raw (⭐424)](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface.
*   [sdns (⭐976)](https://github.com/semihalev/sdns) - A high-performance, recursive DNS resolver server with DNSSEC support, focused on preserving privacy.
*   [sftp (⭐1.5k)](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in <https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt>.
*   [ssh (⭐3.8k)](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh).
*   [sslb (⭐150)](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
*   [stun (⭐494)](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol.
*   [tcpack (⭐171)](https://github.com/lim-yoona/tcpack) - tcpack is an application protocol based on TCP to Pack and Unpack bytes stream in go program.
*   [tspool (⭐14)](https://github.com/two/tspool) - A TCP Library use worker pool to improve performance and protect your server.
*   [tun2socks (⭐3.7k)](https://github.com/xjasonlyu/tun2socks) - A pure go implementation of tun2socks powered by [gVisor](https://gvisor.dev/) TCP/IP stack.
*   [utp (⭐177)](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation.
*   [vssh (⭐965)](https://github.com/yahoo/vssh) - Go library for building network and server automation over SSH protocol.
*   [water (⭐2k)](https://github.com/songgao/water) - Simple TUN/TAP library.
*   [webrtc (⭐14k)](https://github.com/pions/webrtc) - A pure Go implementation of the WebRTC API.
*   [winrm (⭐429)](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines.
*   [xtcp (⭐155)](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol.

**[⬆ back to top](#contents)**

### HTTP Clients

*Libraries for making HTTP requests.*

*   [axios4go (⭐15)](https://github.com/rezmoss/axios4go) - A Go HTTP client library inspired by Axios, providing a simple and intuitive API for making HTTP requests.
*   [azuretls-client (⭐211)](https://github.com/Noooste/azuretls-client) -  An easy-to-use HTTP client 100% in Go to spoof TLS/JA3 and HTTP2 fingerprint
*   [fast-shot (⭐81)](https://github.com/opus-domini/fast-shot) - Hit your API targets with rapid-fire precision using Go's fastest and simple HTTP Client.
*   [gentleman (⭐1.1k)](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library.
*   [go-cleanhttp (⭐387)](https://github.com/hashicorp/go-cleanhttp) - Get easily stdlib HTTP client, which does not share any state with other clients.
*   [go-http-client (⭐81)](https://github.com/bozd4g/go-http-client) - Make http calls simply and easily.
*   [go-otelroundtripper (⭐83)](https://github.com/NdoleStudio/go-otelroundtripper) - Go http.RoundTripper that emits open telemetry metrics for HTTP requests.
*   [go-req (⭐22)](https://github.com/wenerme/go-req) - Declarative golang HTTP client.
*   [go-retryablehttp (⭐2.1k)](https://github.com/hashicorp/go-retryablehttp) - Retryable HTTP client in Go.
*   [go-zoox/fetch (⭐74)](https://github.com/go-zoox/fetch) - A Powerful, Lightweight, Easy Http Client, inspired by Web Fetch API.
*   [grequests (⭐2.1k)](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library.
*   [heimdall (⭐2.7k)](https://github.com/gojektech/heimdall) - An enhanced http client with retry and hystrix capabilities.
*   [httpretry (⭐51)](https://github.com/ybbus/httpretry) - Enriches the default go HTTP client with retry functionality.
*   [pester (⭐650)](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency.
*   [req (⭐4.4k)](https://github.com/imroc/req) - Simple Go HTTP client with Black Magic (Less code and More efficiency).
*   [request (⭐290)](https://github.com/monaco-io/request) - HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency.
*   [requests (⭐1.6k)](https://github.com/carlmjohnson/requests) - HTTP requests for Gophers. Uses context.Context and doesn't hide the underlying net/http.Client, making it compatible with standard Go APIs. Also includes testing tools.
*   [resty (⭐11k)](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.
*   [rq (⭐52)](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client.
*   [sling (⭐1.7k)](https://github.com/dghubble/sling) - Sling is a Go HTTP client library for creating and sending API requests.
*   [tls-client (⭐981)](https://github.com/bogdanfinn/tls-client) - net/http.Client like HTTP Client with options to select specific client TLS Fingerprints to use for requests.

**[⬆ back to top](#contents)**

## OpenGL

*Libraries for using OpenGL in Go.*

*   [gl (⭐1.1k)](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).
*   [glfw (⭐1.6k)](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.
*   [go-glmatrix (⭐11)](https://github.com/technohippy/go-glmatrix) - Go port of [glMatrix](https://glmatrix.net/) library.
*   [goxjs/gl (⭐177)](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
*   [goxjs/glfw (⭐83)](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events.
*   [mathgl (⭐573)](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.

**[⬆ back to top](#contents)**

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

*   [bob (⭐914)](https://github.com/stephenafamo/bob) - SQL query builder and ORM/Factory generator for Go. Successor of SQLBoiler.
*   [bun (⭐4k)](https://github.com/uptrace/bun) - SQL-first Golang ORM. Successor of go-pg.
*   [cacheme (⭐24)](https://github.com/Yiling-J/cacheme-go) - Schema based, typed Redis caching/memoize framework for Go.
*   [CQL (⭐17)](https://github.com/FrancoLiberali/cql) - Built on top of GORM, adds compile-time verified queries based on auto-generated code.
*   [ent (⭐16k)](https://github.com/facebook/ent) - An entity framework for Go. Simple, yet powerful ORM for modeling and querying data.
*   [go-dbw (⭐16)](https://github.com/hashicorp/go-dbw) - A simple package that encapsulates database operations.
*   [go-firestorm (⭐52)](https://github.com/jschoedt/go-firestorm) - A simple ORM for Google/Firebase Cloud Firestore.
*   [go-sql (⭐180)](https://github.com/rushteam/gosql) - A easy ORM for mysql.
*   [go-sqlbuilder (⭐1.5k)](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM.
*   [go-store (⭐113)](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go.
*   [golobby/orm (⭐159)](https://github.com/golobby/orm) - Simple, fast, type-safe, generic orm for developer happiness.
*   [GORM (⭐38k)](https://github.com/go-gorm/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.
*   [gormt (⭐2.4k)](https://github.com/xxjwxc/gormt) - Mysql database to golang gorm struct.
*   [gorp (⭐3.7k)](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go.
*   [grimoire (⭐165)](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).
*   [lore (⭐14)](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.
*   [marlow (⭐12)](https://github.com/marlow/marlow) - Generated ORM from project structs for compile time safety assurances.
*   [pop/soda (⭐1.5k)](https://github.com/gobuffalo/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
*   [Prisma (⭐2.3k)](https://github.com/prisma/prisma-client-go) - Prisma Client Go, Typesafe database access for Go.
*   [reform (⭐1.4k)](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation.
*   [rel (⭐778)](https://github.com/go-rel/rel) - Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API.
*   [SQLBoiler (⭐6.8k)](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.
*   [upper.io/db (⭐3.6k)](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
*   [XORM](https://gitea.com/xorm/xorm) - Simple and powerful ORM for Go. (Support: MySQL, MyMysql, PostgreSQL, Tidb, SQLite3, MsSql and Oracle).
*   [Zoom (⭐309)](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis.

**[⬆ back to top](#contents)**

## Package Management

*Official tooling for dependency and package management*

*   [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules.

*Unofficial libraries for package and dependency management.*

*   [glide (⭐8.1k)](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.
*   [godep (⭐5.5k)](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
*   [goop (⭐777)](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler.
*   [gop (⭐49)](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH.
*   [gopm (⭐2.5k)](https://github.com/gpmgo/gopm) - Go Package Manager.
*   [govendor (⭐4.9k)](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file.
*   [gpm (⭐1.2k)](https://github.com/pote/gpm) - Barebones dependency manager for Go.
*   [gup (⭐387)](https://github.com/nao1215/gup) - Update binaries installed by "go install".
*   [johnny-deps (⭐213)](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git.
*   [modgv (⭐491)](https://github.com/lucasepe/modgv) - Converts 'go mod graph' output into Graphviz's DOT language.
*   [mvn-golang (⭐164)](https://github.com/raydac/mvn-golang) - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure.
*   [syft (⭐6.6k)](https://github.com/anchore/syft) - A CLI tool and Go library for generating a Software Bill of Materials (SBOM) from container images and filesystems.
*   [VenGO (⭐126)](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments.

**[⬆ back to top](#contents)**

## Performance

*   [go-instrument (⭐250)](https://github.com/nikolaydubina/go-instrument) - Automatically add spans to all methods and functions.
*   [jaeger (⭐21k)](https://github.com/jaegertracing/jaeger) - A distributed tracing system.
*   [mm-go (⭐158)](https://github.com/joetifa2003/mm-go) - Generic manual memory management for golang.
*   [pixie (⭐5.8k)](https://github.com/pixie-labs/pixie) - No instrumentation tracing for Golang applications via eBPF.
*   [profile (⭐2k)](https://github.com/pkg/profile) - Simple profiling support package for Go.
*   [statsviz (⭐3.3k)](https://github.com/arl/statsviz) - Live visualization of your Go application runtime statistics.
*   [tracer (⭐86)](https://github.com/kamilsk/tracer) - Simple, lightweight tracing.

**[⬆ back to top](#contents)**

## Query Language

*   [api-fu (⭐56)](https://github.com/ccbrown/api-fu) - Comprehensive GraphQL implementation.
*   [dasel (⭐7.3k)](https://github.com/tomwright/dasel) - Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies.
*   [gojsonq (⭐2.2k)](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON Data.
*   [goven (⭐60)](https://github.com/SeldonIO/goven) - A drop-in query language for any database schema.
*   [gqlgen (⭐10k)](https://github.com/99designs/gqlgen) - go generate based graphql server library.
*   [grapher (⭐4)](https://github.com/reaganiwadha/grapher) - A GraphQL field builder utilizing Go generics with extra utilities and features.
*   [graphql (⭐57)](https://github.com/tmc/graphql) - graphql parser + utilities.
*   [graphql (⭐4.7k)](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use.
*   [graphql-go (⭐10k)](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go.
*   [gws (⭐6)](https://github.com/Zaba505/gws) - Apollos' "GraphQL over Websocket" client and server implementation.
*   [jsonpath (⭐25)](https://github.com/AsaiYusuke/jsonpath) - A query library for retrieving part of JSON based on JSONPath syntax.
*   [jsonql (⭐276)](https://github.com/elgs/jsonql) - JSON query expression library in Golang.
*   [jsonslice (⭐90)](https://github.com/bhmj/jsonslice) - Jsonpath queries with advanced filters.
*   [mql (⭐54)](https://github.com/hashicorp/mql) - Model Query Language (mql) is a query language for your database models.
*   [rql (⭐351)](https://github.com/a8m/rql) - Resource Query Language for REST API.
*   [rqp (⭐80)](https://github.com/timsolov/rest-query-parser) - Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query.
*   [straf (⭐40)](https://github.com/SonicRoshan/straf) - Easily Convert Golang structs to GraphQL objects.

**[⬆ back to top](#contents)**

## Reflection

*   [copy (⭐49)](https://github.com/gotidy/copy) - Package for fast copying structs of different types.
*   [Deepcopier (⭐455)](https://github.com/ulule/deepcopier) - Simple struct copying for Go.
*   [go-deepcopy (⭐44)](https://github.com/tiendc/go-deepcopy) - Fast deep copy library.
*   [goenum (⭐12)](https://github.com/lvyahui8/goenum) - A common enumeration struct based on generics and reflection that allows you to quickly define enumerations and use a set of useful default methods.
*   [gotype (⭐62)](https://github.com/wzshiming/gotype) - Golang source code parsing, usage like reflect package.
*   [gpath (⭐40)](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection.
*   [objwalker (⭐3)](https://github.com/rekby/objwalker) - Walk by go objects with reflection.
*   [reflectutils (⭐8)](https://github.com/muir/reflectutils) - Helpers for working with reflection: struct tag parsing; recursive walking; fill value from string.

**[⬆ back to top](#contents)**

## Resource Embedding

*   [debme (⭐33)](https://github.com/leaanthony/debme) - Create an `embed.FS` from an existing `embed.FS` subdirectory.
*   [embed](https://pkg.go.dev/embed) - Package embed provides access to files embedded in the running Go program.
*   [rebed (⭐30)](https://github.com/soypat/rebed) - Recreate folder structures and files from Go 1.16's `embed.FS` type
*   [vfsgen (⭐983)](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem.

**[⬆ back to top](#contents)**

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

*   [assocentity (⭐15)](https://github.com/ndabAP/assocentity) - Package assocentity returns the average distance from words to a given entity.
*   [bradleyterry (⭐11)](https://github.com/seanhagen/bradleyterry) - Provides a Bradley-Terry Model for pairwise comparisons.
*   [calendarheatmap (⭐408)](https://github.com/nikolaydubina/calendarheatmap) - Calendar heatmap in plain Go inspired by Github contribution activity.
*   [chart (⭐774)](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types.
*   [dataframe-go (⭐1.2k)](https://github.com/rocketlaunchr/dataframe-go) - Dataframes for machine-learning and statistics (similar to pandas).
*   [decimal (⭐42)](https://github.com/db47h/decimal) - Package decimal implements arbitrary-precision decimal floating-point arithmetic.
*   [evaler (⭐51)](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator.
*   [ewma (⭐441)](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages.
*   [geom (⭐55)](https://github.com/skelterjohn/geom) - 2D geometry for golang.
*   [go-dsp (⭐867)](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go.
*   [go-estimate (⭐115)](https://github.com/milosgajdos/go-estimate) - State estimation and filtering algorithms in Go.
*   [go-gt (⭐11)](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language.
*   [go-hep (⭐233)](https://github.com/go-hep/hep) - A set of libraries and tools for performing High Energy Physics analyses with ease.
*   [godesim (⭐23)](https://github.com/soypat/godesim) - Extended/multivariable ODE solver framework for event-based simulations with simple API.
*   [goent (⭐35)](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures.
*   [gograph (⭐75)](https://github.com/hmdsefi/gograph) - A golang generic graph library that provides mathematical graph-theory and algorithms.
*   [gonum (⭐7.8k)](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more.
*   [gonum/plot (⭐2.8k)](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go.
*   [goraph (⭐739)](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorithm visualization).
*   [gosl (⭐1.8k)](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
*   [GoStats (⭐22)](https://github.com/OGFris/GoStats) - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions.
*   [graph (⭐716)](https://github.com/yourbasic/graph) - Library of basic graph algorithms.
*   [jsonl-graph (⭐74)](https://github.com/nikolaydubina/jsonl-graph) - Tool to manipulate JSONL graphs with graphviz support.
*   [ode (⭐22)](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.
*   [orb (⭐949)](https://github.com/paulmach/orb) - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support.
*   [pagerank (⭐85)](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go.
*   [piecewiselinear (⭐28)](https://github.com/sgreben/piecewiselinear) - Tiny linear interpolation library.
*   [PiHex (⭐20)](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.
*   [Poly (⭐690)](https://github.com/bebop/poly) - A Go package for engineering organisms.
*   [rootfinding (⭐11)](https://github.com/khezen/rootfinding) - root-finding algorithms library for finding roots of quadratic functions.
*   [sparse (⭐161)](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.
*   [stats (⭐2.9k)](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library.
*   [streamtools (⭐1.3k)](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.
*   [TextRank (⭐209)](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support.
*   [topk (⭐9)](https://github.com/keilerkonzept/topk) - Sliding-window and regular top-K sketches, based on the HeavyKeeper algorithm.
*   [triangolatte (⭐36)](https://github.com/tchayen/triangolatte) - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs.

**[⬆ back to top](#contents)**

## Security

*Libraries that are used to help make your application more secure.*

*   [acmetool (⭐2.1k)](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal.
*   [acopw-go](https://sr.ht/~jamesponddotco/acopw-go/) - Small cryptographically secure password generator package for Go.
*   [acra (⭐1.4k)](https://github.com/cossacklabs/acra) - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system.
*   [age (⭐18k)](https://github.com/FiloSottile/age) - A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability.
*   [argon2-hashing (⭐21)](https://github.com/andskur/argon2-hashing) - light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package.
*   [argon2pw (⭐91)](https://github.com/raja/argon2pw) - Argon2 password hash generation with constant-time password comparison.
*   [autocert](https://pkg.go.dev/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.
*   [BadActor (⭐322)](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban.
*   [beelzebub (⭐839)](https://github.com/mariocandela/beelzebub) - A secure low code honeypot framework, leveraging AI for System Virtualization.
*   [booster (⭐559)](https://github.com/anatol/booster) - Fast initramfs generator with full-disk encryption support.
*   [Cameradar (⭐4.2k)](https://github.com/Ullaakut/cameradar) - Tool and library to remotely hack RTSP streams from surveillance cameras.
*   [certificates (⭐39)](https://github.com/mvmaasakkers/certificates) - An opinionated tool for generating tls certificates.
*   [CertMagic (⭐5.2k)](https://github.com/caddyserver/certmagic) - Mature, robust, and powerful ACME client integration for fully-managed TLS certificate issuance and renewal.
*   [Coraza (⭐2.4k)](https://github.com/corazawaf/coraza) - Enterprise-ready, modsecurity and OWASP CRS compatible WAF library.
*   [dongle (⭐968)](https://github.com/golang-module/dongle) - A simple, semantic and developer-friendly golang package for encoding\&decoding and encryption\&decryption.
*   [encid (⭐3)](https://github.com/bobg/encid) - Encode and decode encrypted integer IDs.
*   [entpassgen (⭐4)](https://github.com/andreimerlescu/entpassgen) - Entropy Password Generator with extensive command line arguments to generate random strings securely including digits, passwords, and passwords built using obscure dictionary words mixed with symbols and digits.
*   [firewalld-rest (⭐339)](https://github.com/prashantgupta24/firewalld-rest) - A rest application to dynamically update firewalld rules on a linux server.
*   [go-generate-password (⭐56)](https://github.com/m1/go-generate-password) - Password generator that can be used on the cli or as a library.
*   [go-htpasswd (⭐41)](https://github.com/tg123/go-htpasswd) - Apache htpasswd Parser for Go.
*   [go-password-validator (⭐515)](https://github.com/lane-c-wagner/go-password-validator) - Password validator based on raw cryptographic entropy values.
*   [go-peer (⭐283)](https://github.com/number571/go-peer) - A software library for creating secure and anonymous decentralized systems.
*   [go-yara (⭐364)](https://github.com/hillu/go-yara) - Go Bindings for [YARA (⭐138)](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)".
*   [goArgonPass (⭐20)](https://github.com/dwin/goArgonPass) - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations.
*   [goSecretBoxPassword (⭐60)](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords.
*   [Interpol (⭐5)](https://github.com/avahidi/interpol) - Rule-based data generator for fuzzing and penetration testing.
*   [lego (⭐8.3k)](https://github.com/go-acme/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).
*   [luks.go (⭐89)](https://github.com/anatol/luks.go) - Pure Golang library to manage LUKS partitions.
*   [memguard (⭐2.6k)](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory.
*   [multikey (⭐6)](https://github.com/adrianosela/multikey) - An n-out-of-N keys encryption/decryption framework based on Shamir's Secret Sharing algorithm.
*   [nacl (⭐545)](https://github.com/kevinburke/nacl) - Go implementation of the NaCL set of API's.
*   [optimus-go (⭐360)](https://github.com/pjebs/optimus-go) - ID hashing and Obfuscation using Knuth's Algorithm.
*   [passlib (⭐290)](https://github.com/hlandau/passlib) - Futureproof password hashing library.
*   [passwap (⭐62)](https://github.com/zitadel/passwap) - Provides a unified implementation between different password hashing algorithms
*   [qrand (⭐16)](https://github.com/bitfield/qrand) - Client for the ANU Quantum Numbers (AQN) API, providing quantum-mechanically secure random data.
*   [secret (⭐30)](https://github.com/rsjethani/secret) - Prevent your secrets from leaking into logs, std\* etc.
*   [secure (⭐2.3k)](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.
*   [secureio (⭐34)](https://github.com/xaionaro-go/secureio) - An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519.
*   [simple-scrypt (⭐197)](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in.
*   [ssh-vault (⭐466)](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys.
*   [sslmgr (⭐30)](https://github.com/adrianosela/sslmgr) - SSL certificates made easy with a high level wrapper around acme/autocert.
*   [teler-waf (⭐365)](https://github.com/kitabisa/teler-waf) - teler-waf is a Go HTTP middleware that provide teler IDS functionality to protect against web-based attacks and improve the security of Go-based web applications. It is highly configurable and easy to integrate into existing Go applications.
*   [themis (⭐1.9k)](https://github.com/cossacklabs/themis) - high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps.

**[⬆ back to top](#contents)**

## Serialization

*Libraries and tools for binary serialization.*

*   [bambam (⭐65)](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go.
*   [bel (⭐44)](https://github.com/32leaves/bel) - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC.
*   [binstruct (⭐100)](https://github.com/ghostiam/binstruct) - Golang binary decoder for mapping data into the structure.
*   [cbor (⭐805)](https://github.com/fxamacker/cbor) - Small, safe, and easy CBOR encoding and decoding library.
*   [colfer (⭐750)](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format.
*   [csvutil (⭐955)](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures.
*   [elastic (⭐24)](https://github.com/epiclabs-io/elastic) - Convert slices, maps or any other unknown value across different types at run-time, no matter what.
*   [fixedwidth (⭐9)](https://github.com/huydang284/fixedwidth) - Fixed-width text formatting (UTF-8 supported).
*   [fwencoder (⭐27)](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoding and decoding library) for Go.
*   [go-capnproto (⭐288)](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go.
*   [go-codec (⭐1.9k)](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.
*   [go-csvlib (⭐18)](https://github.com/tiendc/go-csvlib) - High level and rich functionalities CSV serialization/deserialization library.
*   [gogoprotobuf (⭐5.7k)](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.
*   [goprotobuf (⭐9.9k)](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
*   [gotiny (⭐21)](https://github.com/raszia/gotiny) - Efficient Go serialization library, gotiny is almost as fast as serialization libraries that generate code.
*   [jsoniter (⭐14k)](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json".
*   [mapstructure (⭐8k)](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures.
*   [php\_session\_decoder (⭐166)](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.
*   [pletter (⭐19)](https://github.com/vimeda/pletter) - A standard way to wrap a proto message for message brokers.
*   [structomap (⭐144)](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures.
*   [unitpacking (⭐7)](https://github.com/recolude/unitpacking) - Library to pack unit vectors into as fewest bytes as possible.

**[⬆ back to top](#contents)**

## Server Applications

*   [algernon (⭐2.9k)](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
*   [Caddy (⭐62k)](https://github.com/caddyserver/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
*   [Clace (⭐570)](https://github.com/claceio/clace) - Clace makes internal tool deployment and management easy by implementing an app server for containerized webapps.
*   [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
*   [cortex-tenant (⭐116)](https://github.com/blind-oracle/cortex-tenant) - Prometheus remote write proxy that adds add Cortex tenant ID header based on metric labels.
*   [devd (⭐3.4k)](https://github.com/cortesi/devd) - Local webserver for developers.
*   [discovery (⭐1.8k)](https://github.com/Bilibili/discovery) - A registry for resilient mid-tier load balancing and failover.
*   [dudeldu (⭐143)](https://github.com/krotik/dudeldu) - A simple SHOUTcast server.
*   [Easegress (⭐5.8k)](https://github.com/megaease/easegress) - A cloud native high availability/performance traffic orchestration system with observability and extensibility.
*   [Engity's Bifröst](https://bifroest.engity.org/) - Highly customizable SSH server with several ways to authorize a user how to execute its session (local or in containers).
*   [etcd (⭐49k)](https://github.com/etcd-io/etcd) - Highly-available key value store for shared configuration and service discovery.
*   [Euterpe (⭐548)](https://github.com/ironsmile/euterpe) - Self-hosted music streaming server with built-in web UI and REST API.
*   [Fider (⭐3.3k)](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback.
*   [Flagr (⭐2.5k)](https://github.com/checkr/flagr) - Flagr is an open-source feature flagging and A/B testing service.
*   [flipt (⭐4.1k)](https://github.com/markphelps/flipt) - A self contained feature flag solution written in Go and Vue.js
*   [go-feature-flag (⭐1.6k)](https://github.com/thomaspoignant/go-feature-flag) - A simple, complete and lightweight self-hosted feature flag solution 100% Open Source.
*   [go-proxy-cache (⭐136)](https://github.com/fabiocicerchia/go-proxy-cache) - Simple Reverse Proxy with Caching, written in Go, using Redis.
*   [gondola (⭐8)](https://github.com/bmf-san/gondola) - A YAML based golang reverse proxy.
*   [lets-proxy2 (⭐97)](https://github.com/rekby/lets-proxy2) - Reverse proxy for handle https with issue certificates in fly from lets-encrypt.
*   [minio (⭐50k)](https://github.com/minio/minio) - Minio is a distributed object storage server.
*   [Moxy (⭐15)](https://github.com/sinhashubham95/moxy) - Moxy is a simple mocker and proxy application server, you can create mock endpoints as well as proxy requests in case no mock exists for the endpoint.
*   [nginx-prometheus (⭐41)](https://github.com/blind-oracle/nginx-prometheus) - Nginx log parser and exporter to Prometheus.
*   [nsq](https://nsq.io/) - A realtime distributed messaging platform.
*   [pocketbase (⭐44k)](https://github.com/pocketbase/pocketbase) - PocketBase is a realtime backend in 1 file consisting of embedded database (SQLite) with realtime subscriptions, built-in auth management and much more.
*   [protoxy (⭐35)](https://github.com/camgraff/protoxy) - A proxy server that converts JSON request bodies to Protocol Buffers.
*   [psql-streamer (⭐59)](https://github.com/blind-oracle/psql-streamer) - Stream database events from PostgreSQL to Kafka.
*   [riemann-relay (⭐2)](https://github.com/blind-oracle/riemann-relay) - Relay to load-balance Riemann events and/or convert them to Carbon.
*   [RoadRunner (⭐8k)](https://github.com/spiral/roadrunner) - High-performance PHP application server, load-balancer and process manager.
*   [SFTPGo (⭐10k)](https://github.com/drakkan/sftpgo) - Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage.
*   [Trickster (⭐2k)](https://github.com/tricksterproxy/trickster) - HTTP reverse proxy cache and time series accelerator.
*   [wd-41 (⭐147)](https://github.com/baalimago/wd-41) - A (w)eb (d)evelopment server with automatic live-reload on file changes.
*   [Wish (⭐3.9k)](https://github.com/charmbracelet/wish) - Make SSH apps, just like that!

**[⬆ back to top](#contents)**

## Stream Processing

*Libraries and tools for stream processing and reactive programming.*

*   [go-etl (⭐132)](https://github.com/Breeze0806/go-etl) - A lightweight toolkit for data source extraction, transformation, and loading (ETL).
*   [go-streams (⭐2k)](https://github.com/reugn/go-streams) - Go stream processing library.
*   [goio (⭐84)](https://github.com/primetalk/goio) - An implementation of IO, Stream, Fiber for Golang, inspired by awesome Scala libraries cats and fs2.
*   [machine (⭐159)](https://github.com/whitaker-io/machine) - Go library for writing and generating stream workers with built in metrics and traceability.
*   [stream (⭐92)](https://github.com/youthlin/stream) - Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce...

**[⬆ back to top](#contents)**

## Template Engines

*Libraries and tools for templating and lexing.*

*   [ego (⭐583)](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
*   [extemplate](https://git.sr.ht/~dvko/extemplate) - Tiny wrapper around html/template to allow for easy file-based template inheritance.
*   [fasttemplate (⭐853)](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](https://golang.org/pkg/text/template/).
*   [gomponents](https://www.gomponents.com) - HTML 5 components in pure Go, that look something like this: `func(name string) g.Node { return Div(Class("headline"), g.Textf("Hi %v!", name)) }`.
*   [got (⭐34)](https://github.com/goradd/got) - A Go code generator inspired by Hero and Fasttemplate. Has include files, custom tag definitions, injected Go code, language translation, and more.
*   [goview (⭐432)](https://github.com/foolin/goview) - Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application.
*   [htmgo](https://htmgo.dev) - build simple and scalable systems with go + htmx
*   [jet (⭐1.3k)](https://github.com/CloudyKit/jet) - Jet template engine.
*   [liquid (⭐297)](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates.
*   [maroto (⭐2.3k)](https://github.com/johnfercher/maroto) - A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple.
*   [pongo2 (⭐2.9k)](https://github.com/flosch/pongo2) - Django-like template-engine for Go.
*   [quicktemplate (⭐3.2k)](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
*   [raymond (⭐617)](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go.
*   [Razor (⭐864)](https://github.com/sipin/gorazor) - Razor view engine for Golang.
*   [Soy (⭐173)](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).
*   [sprout (⭐144)](https://github.com/go-sprout/sprout) - Useful template functions for Go templates.
*   [tbd (⭐25)](https://github.com/lucasepe/tbd) - A really simple way to create text templates with placeholders - exposes extra builtin Git repo metadata.
*   [templ (⭐8.9k)](https://github.com/a-h/templ) - A HTML templating language that has great developer tooling.

**[⬆ back to top](#contents)**

## Testing

*Libraries for testing codebases and generating test data.*

### Testing Frameworks

*   [apitest](https://apitest.dev) - Simple and extensible behavioural testing library for REST based services or HTTP handlers that supports mocking external http calls and rendering of sequence diagrams.
*   [arch-go (⭐1)](https://github.com/fdaines/arch-go) - Architecture testing tool for Go projects.
*   [assert (⭐64)](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.
*   [baloo (⭐778)](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy.
*   [be (⭐104)](https://github.com/carlmjohnson/be) - The minimalist generic test assertion library.
*   [biff (⭐14)](https://github.com/fulldump/biff) - Bifurcation testing framework, BDD compatible.
*   [charlatan (⭐204)](https://github.com/percolate/charlatan) - Tool to generate fake interface implementations for tests.
*   [commander (⭐228)](https://github.com/SimonBaeumer/commander) - Tool for testing cli applications on windows, linux and osx.
*   [cupaloy (⭐312)](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework.
*   [dbcleaner (⭐162)](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.
*   [dft (⭐15)](https://github.com/abecodes/dft) - Lightweight, zero dependency docker containers for testing (or more).
*   [dsunit (⭐45)](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files.
*   [embedded-postgres (⭐909)](https://github.com/fergusstrange/embedded-postgres) - Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test.
*   [endly (⭐264)](https://github.com/viant/endly) - Declarative end to end functional testing.
*   [envite (⭐5)](https://github.com/PerimeterX/envite) - Dev and testing environment management framework.
*   [fixenv (⭐31)](https://github.com/rekby/fixenv) - Fixture manage engine, inspired by pytest fixtures.
*   [flute (⭐21)](https://github.com/suzuki-shunsuke/flute) - HTTP client testing framework.
*   [frisby (⭐276)](https://github.com/verdverm/frisby) - REST API testing framework.
*   [gherkingen (⭐81)](https://github.com/hedhyw/gherkingen) - BDD boilerplate generator and framework.
*   [ginkgo](https://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
*   [gnomock (⭐1.4k)](https://github.com/orlangure/gnomock) - integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks.
*   [go-carpet (⭐248)](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal.
*   [go-cmp (⭐4.3k)](https://github.com/google/go-cmp) - Package for comparing Go values in tests.
*   [go-hit (⭐258)](https://github.com/Eun/go-hit) - Hit is an http integration test framework written in golang.
*   [go-mutesting (⭐654)](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code.
*   [go-mysql-test-container (⭐3)](https://github.com/arikama/go-mysql-test-container) - Golang MySQL testcontainer to help with MySQL integration testing.
*   [go-snaps (⭐190)](http://github.com/gkampitakis/go-snaps) - Jest-like snapshot testing in Golang.
*   [go-testdeep (⭐441)](https://github.com/maxatome/go-testdeep) - Extremely flexible golang deep comparison, extends the go testing package.
*   [go-testpredicate (⭐5)](https://github.com/maargenton/go-testpredicate) - Test predicate style assertions library with extensive diagnostics output.
*   [go-vcr (⭐1.3k)](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
*   [goblin (⭐889)](https://github.com/franela/goblin) - Mocha like testing framework of Go.
*   [goc (⭐839)](https://github.com/qiniu/goc) - Goc is a comprehensive coverage testing system for The Go Programming Language.
*   [gocheck](https://labix.org/gocheck) - More advanced testing framework alternative to gotest.
*   [GoConvey (⭐8.3k)](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload.
*   [gocrest (⭐106)](https://github.com/corbym/gocrest) - Composable hamcrest-like matchers for Go assertions.
*   [godog (⭐2.4k)](https://github.com/cucumber/godog) - Cucumber BDD framework for Go.
*   [gofight (⭐441)](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework.
*   [gogiven (⭐15)](https://github.com/corbym/gogiven) - YATSPEC-like BDD testing framework for Go.
*   [gomatch (⭐48)](https://github.com/jfilipczyk/gomatch) - library created for testing JSON against patterns.
*   [gomega](https://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
*   [Gont (⭐79)](https://github.com/stv0g/gont) - Go network testing toolkit for testing building complex network topologies using Linux namespaces.
*   [gospecify (⭐52)](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
*   [gosuite (⭐12)](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.
*   [got (⭐265)](https://github.com/ysmood/got) - An enjoyable golang test framework.
*   [gotest.tools (⭐532)](https://github.com/gotestyourself/gotest.tools) - A collection of packages to augment the go testing package and support common patterns.
*   [Hamcrest (⭐30)](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
*   [httpexpect (⭐2.6k)](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
*   [is (⭐1.8k)](https://github.com/matryer/is) - Professional lightweight testing mini-framework for Go.
*   [jsonassert (⭐129)](https://github.com/kinbiko/jsonassert) - Package for verifying that your JSON payloads are serialized correctly.
*   [keploy (⭐6k)](https://github.com/keploy/keploy) - Generate Testcase and Data Mocks from API calls automatically.
*   [omg.testingtools (⭐1)](https://github.com/dedalqq/omg.testingtools) - The simple library for change a values of private fields for testing.
*   [restit (⭐55)](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
*   [schema (⭐20)](https://github.com/jgroeneveld/schema) - Quick and easy expression matching for JSON schemas used in requests and responses.
*   [stop-and-go (⭐11)](https://github.com/elgohr/stop-and-go) - Testing helper for concurrency.
*   [testcase (⭐122)](https://github.com/adamluzsi/testcase) - Idiomatic testing framework for Behavior Driven Development.
*   [testcerts (⭐71)](https://github.com/madflojo/testcerts) - Dynamically generate self-signed certificates and certificate authorities within your test functions.
*   [testcontainers-go (⭐3.9k)](https://github.com/testcontainers/testcontainers-go) - A Go package that makes it simple to create and clean up container-based dependencies for automated integration/smoke tests. The clean, easy-to-use API enables developers to programmatically define containers that should be run as part of a test and clean up those resources when the test is done.
*   [testfixtures (⭐1.1k)](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications.
*   [Testify (⭐24k)](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package.
*   [testsql (⭐17)](https://github.com/zhulongcheng/testsql) - Generate test data from SQL files before testing and clear it after finished.
*   [testza (⭐419)](https://github.com/MarvinJWendt/testza) - Full-featured test framework with nice colorized output.
*   [trial (⭐6)](https://github.com/jgroeneveld/trial) - Quick and easy extendable assertions without introducing much boilerplate.
*   [Tt (⭐8)](https://github.com/vcaesar/tt) - Simple and colorful test tools.
*   [wstest (⭐102)](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler.

### Mock

*   [counterfeiter (⭐1k)](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects.
*   [genmock](https://gitlab.com/so_literate/genmock) - Go mocking system with code generator for building calls of the interface methods.
*   [go-localstack (⭐80)](https://github.com/elgohr/go-localstack) - Tool for using localstack in AWS testing.
*   [go-sqlmock (⭐6.3k)](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions.
*   [go-txdb (⭐696)](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes.
*   [gock (⭐2.1k)](https://github.com/h2non/gock) - Versatile HTTP mocking made easy.
*   [gomock (⭐2.6k)](https://github.com/uber-go/mock) - Mocking framework for the Go programming language.
*   [govcr (⭐184)](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing.
*   [hoverfly (⭐2.4k)](https://github.com/SpectoLabs/hoverfly) - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI.
*   [httpmock (⭐2k)](https://github.com/jarcoal/httpmock) - Easy mocking of HTTP responses from external resources.
*   [minimock (⭐664)](https://github.com/gojuno/minimock) - Mock generator for Go interfaces.
*   [mockery (⭐6.4k)](https://github.com/vektra/mockery) - Tool to generate Go interfaces.
*   [mockhttp (⭐23)](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter.
*   [mooncake (⭐18)](https://github.com/GuilhermeCaruso/mooncake) - A simple way to generate mocks for multiple purposes.
*   [moq (⭐2k)](https://github.com/matryer/moq) - Utility that generates a struct from any interface. The struct can be used in test code as a mock of the interface.
*   [pgxmock (⭐436)](https://github.com/pashagolub/pgxmock) - A mock library implementing [pgx - PostgreSQL Driver and Toolkit (⭐11k)](https://github.com/jackc/pgx/).
*   [timex (⭐71)](https://github.com/cabify/timex) - A test-friendly replacement for the native `time` package.
*   [xgo (⭐382)](https://github.com/xhd2015/xgo) - A general pureposed function mocking library.

### Fuzzing and delta-debugging/reducing/shrinking

*   [go-fuzz (⭐4.8k)](https://github.com/dvyukov/go-fuzz) - Randomized testing system.
*   [gofuzz (⭐1.5k)](https://github.com/google/gofuzz) - Library for populating go objects with random values.
*   [Tavor (⭐245)](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework.

### Selenium and browser control tools

*   [cdp (⭐743)](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.
*   [chromedp (⭐11k)](https://github.com/knq/chromedp) - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
*   [ggr (⭐314)](https://github.com/aerokube/ggr) - a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs.
*   [playwright-go (⭐2.4k)](https://github.com/mxschmitt/playwright-go) - browser automation library to control Chromium, Firefox and WebKit with a single API.
*   [rod (⭐5.7k)](https://github.com/go-rod/rod) - A Devtools driver to make web automation and scraping easy.
*   [selenoid (⭐2.6k)](https://github.com/aerokube/selenoid) - alternative Selenium hub server that launches browsers within containers.

### Fail injection

*   [failpoint (⭐840)](https://github.com/pingcap/failpoint) - An implementation of [failpoints](https://www.freebsd.org/cgi/man.cgi?query=fail) for Golang.

**[⬆ back to top](#contents)**

## Text Processing

*Libraries for parsing and manipulating texts.*

See also [Natural Language Processing](#natural-language-processing) and [Text Analysis](#text-analysis).

### Formatters

*   [address (⭐77)](https://github.com/bojanz/address) - Handles address representation, validation and formatting.
*   [align (⭐84)](https://github.com/Guitarbum722/align) - A general purpose application that aligns text.
*   [bytes (⭐546)](https://github.com/labstack/gommon/tree/master/bytes) - Formats and parses numeric byte values (10K, 2M, 3G, etc.).
*   [go-fixedwidth (⭐82)](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection).
*   [go-humanize (⭐4.4k)](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.
*   [gotabulate (⭐337)](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.
*   [sq (⭐2.2k)](https://github.com/neilotoole/sq) - Convert data from SQL databases or document formats like CSV or Excel into formats such as JSON, Excel, CSV, HTML, Markdown, XML, and YAML.
*   [textwrap (⭐5)](https://github.com/isbm/textwrap) - Wraps text at end of lines. Implementation of `textwrap` module from Python.

### Markup Languages

*   [bafi (⭐108)](https://github.com/mmalcek/bafi) - Universal JSON, BSON, YAML, XML translator to ANY format using templates.
*   [bbConvert (⭐12)](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
*   [blackfriday (⭐5.5k)](https://github.com/russross/blackfriday) - Markdown processor in Go.
*   [go-output-format (⭐17)](https://github.com/drewstinnett/go-output-format) - Output go structures into multiple formats (YAML/JSON/etc) in your command line app.
*   [go-toml (⭐1.8k)](https://github.com/pelletier/go-toml) - Go library for the TOML format with query support and handy cli tools.
*   [goldmark (⭐3.9k)](https://github.com/yuin/goldmark) - A Markdown parser written in Go. Easy to extend, standard (CommonMark) compliant, well structured.
*   [goq (⭐265)](https://github.com/andrewstuart/goq) - Declarative unmarshalling of HTML using struct tags with jQuery syntax (uses GoQuery).
*   [html-to-markdown (⭐2.7k)](https://github.com/JohannesKaufmann/html-to-markdown) - Convert HTML to Markdown. Even works with entire websites and can be extended through rules.
*   [htmlquery (⭐761)](https://github.com/antchfx/htmlquery) - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression.
*   [htmlyaml (⭐5)](https://github.com/nikolaydubina/htmlyaml) -  Rich rendering of YAML as HTML in Go
*   [htree (⭐4)](https://github.com/bobg/htree) - Traverse, navigate, filter, and otherwise process trees of [html.Node](https://pkg.go.dev/golang.org/x/net/html#Node) objects.
*   [mxj (⭐624)](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map\[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
*   [toml (⭐4.7k)](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).

### Parsers/Encoders/Decoders

*   [allot (⭐59)](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots.
*   [codetree (⭐24)](https://github.com/aerogo/codetree) - Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure.
*   [commonregex (⭐894)](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go.
*   [did (⭐91)](https://github.com/ockam-network/did) - DID (Decentralized Identifiers) Parser and Stringer in Go.
*   [doi (⭐11)](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go.
*   [editorconfig-core-go (⭐145)](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.
*   [encdec (⭐9)](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decoders.
*   [go-fasttld (⭐35)](https://github.com/elliotwutingfeng/go-fasttld) - High performance effective top level domains (eTLD) extraction module.
*   [go-nmea (⭐233)](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language.
*   [go-querystring (⭐2k)](https://github.com/google/go-querystring) - Go library for encoding structs into URL query parameters.
*   [go-vcard (⭐113)](https://github.com/emersion/go-vcard) - Parse and format vCard.
*   [godump (⭐190)](https://github.com/yassinebenaid/godump) - Pretty print any GO variable with ease, an alternative to Go's `fmt.Printf("%#v")`.
*   [gofeed (⭐2.6k)](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go.
*   [gographviz (⭐559)](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language.
*   [gonameparts (⭐43)](https://github.com/polera/gonameparts) - Parses human names into individual name parts.
*   [ltsv (⭐9)](https://github.com/Wing924/ltsv) - High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go.
*   [normalize (⭐47)](https://github.com/avito-tech/normalize) - Sanitize, normalize and compare fuzzy text.
*   [parseargs-go (⭐10)](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes.
*   [parth (⭐0)](https://github.com/codemodus/parth) - URL path segmentation parsing.
*   [prattle (⭐7)](https://github.com/askeladdk/prattle) - Scan and parse LL(1) grammars simply and efficiently.
*   [sdp (⭐113)](https://github.com/gortc/sdp) - SDP: Session Description Protocol \[[RFC 4566](https://tools.ietf.org/html/rfc4566)].
*   [sh (⭐7.5k)](https://github.com/mvdan/sh) - Shell parser and formatter.
*   [tokenizer (⭐119)](https://github.com/bzick/tokenizer) - Parse any string, slice or infinite buffer to any tokens.
*   [vdf (⭐47)](https://github.com/andygrunwald/vdf) - A Lexer and Parser for Valves Data Format (known as vdf) written in Go.
*   [when (⭐1.4k)](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules.
*   [xj2go (⭐36)](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct.

### Regular Expressions

*   [genex (⭐76)](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings.
*   [go-wildcard (⭐84)](https://github.com/IGLOU-EU/go-wildcard) - Simple and lightweight wildcard pattern matching.
*   [goregen (⭐91)](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions.
*   [regroup (⭐148)](https://github.com/oriser/regroup) - Match regex expression named groups into go struct using struct tags and automatic parsing.
*   [rex (⭐201)](https://github.com/hedhyw/rex) - Regular expressions builder.

### Sanitation

*   [bluemonday (⭐3.3k)](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer.
*   [gofuckyourself (⭐69)](https://github.com/JoshuaDoes/gofuckyourself) - A sanitization-based swear filter for Go.

### Scrapers

*   [colly (⭐24k)](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers.
*   [dataflowkit (⭐678)](https://github.com/slotix/dataflowkit) - Web scraping Framework to turn websites into structured data.
*   [go-recipe (⭐28)](https://github.com/kkyr/go-recipe) - A package for scraping recipes from websites.
*   [GoQuery (⭐14k)](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
*   [pagser (⭐106)](https://github.com/foolin/pagser) - Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler.
*   [Tagify (⭐38)](https://github.com/zoomio/tagify) - Produces a set of tags from given source.
*   [walker (⭐11)](https://github.com/cyucelen/walker) - Seamlessly fetch paginated data from any source. Simple and high performance API scraping included.
*   [xurls (⭐1.2k)](https://github.com/mvdan/xurls) - Extract urls from text.

### RSS

*   [podcast (⭐135)](https://github.com/eduncan911/podcast) - iTunes Compliant and RSS 2.0 Podcast Generator in Golang

### Utility/Miscellaneous

*   [go-runewidth (⭐627)](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string.
*   [go-zero-width (⭐109)](https://github.com/trubitsyn/go-zero-width) - Zero-width character detection and removal for Go.
*   [kace (⭐20)](https://github.com/codemodus/kace) - Common case conversions covering common initialisms.
*   [petrovich (⭐50)](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case.
*   [radix (⭐192)](https://github.com/yourbasic/radix) - Fast string sorting algorithm.
*   [TySug (⭐19)](https://github.com/Dynom/TySug) - Alternative suggestions with respect to keyboard layouts.
*   [w2vgrep (⭐1.1k)](https://github.com/arunsupe/semantic-grep) - A semantic grep tool using word embeddings to find semantically similar matches. For example, searching for "death" will find "dead", "killing", "murder".

**[⬆ back to top](#contents)**

## Third-party APIs

*Libraries for accessing third party APIs.*

*   [airtable (⭐77)](https://github.com/mehanizm/airtable) - Go client library for the [Airtable API](https://airtable.com/api).
*   [anaconda (⭐1.1k)](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API.
*   [appstore-sdk-go (⭐5)](https://github.com/Kachit/appstore-sdk-go) - Unofficial Golang SDK for AppStore Connect API.
*   [aws-encryption-sdk-go (⭐21)](https://github.com/chainifynet/aws-encryption-sdk-go) - Unofficial Go SDK implementation of the [AWS Encryption SDK](https://docs.aws.amazon.com/encryption-sdk/latest/developer-guide/index.html).
*   [aws-sdk-go (⭐2.9k)](https://github.com/aws/aws-sdk-go-v2) - The official AWS SDK for the Go programming language.
*   [bqwriter (⭐16)](https://github.com/OTA-Insight/bqwriter) - High Level Go Library to write data into [Google BigQuery](https://cloud.google.com/bigquery) at a high throughout.
*   [brewerydb (⭐19)](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API.
*   [cachet (⭐90)](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
*   [circleci (⭐65)](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API.
*   [clarifai (⭐55)](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.
*   [codeship-go (⭐18)](https://github.com/codeship/codeship-go) - Go client library for interacting with Codeship's API v2.
*   [coinpaprika-go (⭐25)](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika's API.
*   [device-check-go (⭐24)](https://github.com/rinchsan/device-check-go) - Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1.
*   [discordgo (⭐5.3k)](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API.
*   [disgo (⭐91)](https://github.com/switchupcb/disgo) - Go API Wrapper for the Discord API.
*   [dusupay-sdk-go (⭐3)](https://github.com/Kachit/dusupay-sdk-go) - Unofficial Dusupay payment gateway API Client for Go
*   [ethrpc (⭐270)](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API.
*   [facebook (⭐1.4k)](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API.
*   [fasapay-sdk-go (⭐2)](https://github.com/Kachit/fasapay-sdk-go) - Unofficial Fasapay payment gateway XML API Client for Golang.
*   [fcm (⭐51)](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging.
*   [gads (⭐51)](https://github.com/emiddleton/gads) - Google Adwords Unofficial API.
*   [gcm (⭐31)](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging.
*   [geo-golang (⭐520)](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](https://developer.mapquest.com/documentation/api/geocoding/), [Nominatim](https://nominatim.org/release-docs/latest/api/Overview/), [OpenCage](https://opencagedata.com/api), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
*   [github (⭐11k)](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.
*   [githubql (⭐1.1k)](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4.
*   [go-atlassian (⭐142)](https://github.com/ctreminiom/go-atlassian) - Go library for accessing the [Atlassian Cloud](https://www.atlassian.com/enterprise/cloud) services (Jira, Jira Service Management, Jira Agile, Confluence, Admin Cloud)
*   [go-aws-news (⭐17)](https://github.com/circa10a/go-aws-news) - Go application and library to fetch what's new from AWS.
*   [go-chronos (⭐8)](https://github.com/axelspringer/go-chronos) - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler
*   [go-gerrit (⭐98)](https://github.com/andygrunwald/go-gerrit) - Go client library for [Gerrit Code Review](https://www.gerritcodereview.com/).
*   [go-hacknews (⭐17)](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API.
*   [go-here (⭐13)](https://github.com/abdullahselek/go-here) - Go client library around the HERE location based APIs.
*   [go-hibp (⭐8)](https://github.com/wneessen/go-hibp) - Simple Go binding to the "Have I Been Pwned" APIs.
*   [go-imgur (⭐24)](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)
*   [go-jira (⭐1.5k)](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
*   [go-lark (⭐214)](https://github.com/go-lark/lark) - An easy-to-use unofficial SDK for [Feishu](https://open.feishu.cn/) and [Lark](https://open.larksuite.com/) Open Platform.
*   [go-marathon (⭐198)](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS.
*   [go-myanimelist (⭐39)](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](https://myanimelist.net/apiconfig/references/api/v2).
*   [go-openai (⭐9.7k)](https://github.com/sashabaranov/go-openai) - OpenAI ChatGPT, DALL·E, Whisper API library for Go.
*   [go-openproject (⭐17)](https://github.com/manuelbcd/go-openproject) - Go client library for interacting with [OpenProject](https://docs.openproject.org/api/) API.
*   [go-postman-collection (⭐83)](https://github.com/rbretecher/go-postman-collection) - Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia).
*   [go-redoc (⭐83)](https://github.com/mvrilo/go-redoc) - Embedded OpenAPI/Swagger documentation ui for Go using [ReDoc](https://redocly.com/).
*   [go-restcountries (⭐3)](https://github.com/chriscross0/go-restcountries) - Go library for the [REST Countries API](https://countrylayer.com/).
*   [go-salesforce (⭐35)](https://github.com/k-capehart/go-salesforce) - Go client library for interacting with the [Salesforce REST API](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_list.htm).
*   [go-sophos (⭐12)](https://github.com/esurdam/go-sophos) - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies.
*   [go-swagger-ui (⭐11)](https://github.com/esurdam/go-swagger-ui) - Go library containing precompiled [Swagger UI](https://swagger.io/tools/swagger-ui/) for serving swagger json.
*   [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.
*   [go-trending (⭐144)](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github.
*   [go-unsplash (⭐76)](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.
*   [go-xkcd (⭐51)](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API.
*   [go-yapla](https://gitlab.com/adrienK/go-yapla) - Go client library for the Yapla v2.0 API.
*   [goagi (⭐10)](https://github.com/staskobzar/goagi) - Go library to build Asterisk PBX agi/fastagi applications.
*   [goami2 (⭐16)](https://github.com/staskobzar/goami2) - AMI v2 library for Asterisk PBX.
*   [GoFreeDB (⭐79)](https://github.com/FreeLeh/GoFreeDB) - Golang library providing common and simple database abstractions on top of Google Sheets.
*   [gogtrends (⭐82)](https://github.com/groovili/gogtrends) - Google Trends Unofficial API.
*   [golang-tmdb (⭐132)](https://github.com/cyruzin/golang-tmdb) - Golang wrapper for The Movie Database API v3.
*   [golyrics (⭐41)](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
*   [gomalshare (⭐12)](https://github.com/MonaxGT/gomalshare) - Go library MalShare API [malshare.com](https://www.malshare.com/)
*   [GoMusicBrainz (⭐59)](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library.
*   [google (⭐4.1k)](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.
*   [google-analytics (⭐15)](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting.
*   [google-cloud (⭐3.9k)](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library.
*   [gopaapi5 (⭐16)](https://github.com/utekaravinash/gopaapi5) - Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/).
*   [gopensky (⭐2)](https://github.com/navidys/gopensky) - Go client implementation for [OpenSKY Network](https://opensky-network.org/) live's API (airspace ADS-B and Mode S data).
*   [gosip (⭐152)](https://github.com/koltyakov/gosip) - Client library for SharePoint.
*   [gostorm (⭐129)](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
*   [hipchat (⭐104)](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API.
*   [hipchat (xmpp) (⭐111)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP.
*   [igdb (⭐84)](https://github.com/Henry-Sarabia/igdb) - Go client for the [Internet Game Database API](https://api.igdb.com/).
*   [ip2location-io-go (⭐11)](https://github.com/ip2location/ip2location-io-go) - Go wrapper for the IP2Location.io API [IP2Location.io](https://www.ip2location.io/).
*   [jokeapi-go (⭐25)](https://github.com/icelain/jokeapi) - Go client for [JokeAPI](https://sv443.net/jokeapi/v2/).
*   [lark (⭐431)](https://github.com/chyroc/lark) - [Feishu](https://open.feishu.cn/)/[Lark](https://open.larksuite.com/) Open API Go SDK, Support ALL Open API and Event Callback.
*   [lastpass-go (⭐35)](https://github.com/ansd/lastpass-go) - Go client library for the [LastPass](https://www.lastpass.com/) API.
*   [libgoffi (⭐9)](https://github.com/clevabit/libgoffi) - Library adapter toolbox for native [libffi](https://sourceware.org/libffi/) integration
*   [Medium (⭐141)](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API.
*   [megos (⭐54)](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](https://mesos.apache.org/) cluster.
*   [minio-go (⭐2.6k)](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage.
*   [mixpanel (⭐60)](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
*   [newsapi-go (⭐7)](https://github.com/jellydator/newsapi-go) - Go client for [NewsAPI](https://newsapi.org/).
*   [openaigo (⭐292)](https://github.com/otiai10/openaigo) - OpenAI GPT3/GPT3.5 ChatGPT API client library for Go.
*   [patreon-go (⭐43)](https://github.com/mxpv/patreon-go) - Go library for Patreon API.
*   [paypal (⭐709)](https://github.com/logpacker/PayPal-Go-SDK) - Wrapper for PayPal payment API.
*   [playlyfe (⭐2)](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK.
*   [pushover (⭐148)](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API.
*   [rawg-sdk-go (⭐13)](https://github.com/dimuska139/rawg-sdk-go) - Go library for the [RAWG Video Games Database](https://rawg.io/) API
*   [shopify (⭐24)](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.
*   [simples3 (⭐159)](https://github.com/rhnvrm/simples3) - Simple no frills AWS S3 Library using REST with V4 Signing written in Go.
*   [slack (⭐4.7k)](https://github.com/slack-go/slack) - Slack API in Go.
*   [smite (⭐11)](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API.
*   [spotify (⭐51)](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.
*   [steam (⭐32)](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers.
*   [stripe (⭐2.2k)](https://github.com/stripe/stripe-go) - Go client for the Stripe API.
*   [swag (⭐47)](https://github.com/zc2638/swag) - No comments, simple go wrapper to create swagger 2.0 compatible APIs. Support most routing frameworks, such as built-in, gin, chi, mux, echo, httprouter, fasthttp and more.
*   [textbelt (⭐20)](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API.
*   [Trello (⭐220)](https://github.com/adlio/trello) - Go wrapper for the Trello API.
*   [TripAdvisor (⭐2)](https://github.com/mrbenosborne/tripadvisor-golang) - Go wrapper for the TripAdvisor API.
*   [tumblr (⭐8)](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API.
*   [uptimerobot (⭐57)](https://github.com/bitfield/uptimerobot) - Go wrapper and command-line client for the Uptime Robot v2 API.
*   [vl-go (⭐2)](https://github.com/verifid/vl-go) - Go client library around the VerifID identity verification layer API.
*   [webhooks (⭐972)](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket.
*   [wit-go (⭐162)](https://github.com/wit-ai/wit-go) - Go client for wit.ai HTTP API.
*   [ynab (⭐72)](https://github.com/brunomvsouza/ynab.go) - Go wrapper for the YNAB API.
*   [zooz (⭐7)](https://github.com/gojuno/go-zooz) - Go client for the Zooz API.

**[⬆ back to top](#contents)**

## Utilities

*General utilities and tools to make your life easier.*

*   [apm (⭐168)](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API.
*   [backscanner (⭐65)](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward.
*   [bed (⭐1.3k)](https://github.com/itchyny/bed) - A Vim-like binary editor written in Go.
*   [blank (⭐12)](https://github.com/Henry-Sarabia/blank) - Verify or remove blanks and whitespace from strings.
*   [bleep (⭐11)](https://github.com/sinhashubham95/bleep) - Perform any number of actions on any set of OS signals in Go.
*   [boilr (⭐1.7k)](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.
*   [changie (⭐729)](https://github.com/miniscruff/changie) - Automated changelog tool for preparing releases with lots of customization options.
*   [chyle (⭐158)](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities.
*   [circuit (⭐777)](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern.
*   [circuitbreaker (⭐1.1k)](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go.
*   [clipboard (⭐654)](https://github.com/golang-design/clipboard) - 📋 cross-platform clipboard package in Go.
*   [clockwork (⭐683)](https://github.com/jonboulle/clockwork) - A simple fake clock for golang.
*   [cmd (⭐155)](https://github.com/SimonBaeumer/cmd) - Library for executing shell commands on osx, windows and linux.
*   [command (⭐13)](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher.
*   [config-file-validator (⭐365)](https://github.com/Boeing/config-file-validator) - Cross Platform tool to validate configuration files.
*   [cookie (⭐111)](https://github.com/syntaqx/cookie) - Cookie struct parsing and helper package.
*   [copy-pasta (⭐52)](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage.
*   [countries (⭐427)](https://github.com/biter777/countries) - Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standards.
*   [countries (⭐88)](https://github.com/pioz/countries) - All you need when you are working with countries in Go.
*   [create-go-app (⭐2.7k)](https://github.com/create-go-app/cli) - A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command.
*   [cryptgo (⭐155)](https://github.com/Gituser143/cryptgo) - Crytpgo is a TUI based application written purely in Go to monitor and observe cryptocurrency prices in real time!
*   [ctop (⭐16k)](https://github.com/bcicen/ctop) - [Top-like](https://ctop.sh) interface (e.g. htop) for container metrics.
*   [ctxutil (⭐25)](https://github.com/posener/ctxutil) - A collection of utility functions for contexts.
*   [cvt (⭐51)](https://github.com/shockerli/cvt) - Easy and safe convert any value to another type.
*   [dbt (⭐65)](https://github.com/nikogura/dbt) - A framework for running self-updating signed binaries from a central, trusted repository.
*   [Death (⭐195)](https://github.com/vrecan/death) - Managing go application shutdown with signals.
*   [delve (⭐650)](https://github.com/derekparker/delve) - Go debugger.
*   [dive (⭐50k)](https://github.com/wagoodman/dive) - A tool for exploring each layer in a Docker image.
*   [dlog (⭐17)](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls.
*   [EaseProbe (⭐2.2k)](https://github.com/megaease/easeprobe) - A simple, standalone, and lightWeight tool that can do health/status checking daemon, support HTTP/TCP/SSH/Shell/Client/... probes, and Slack/Discord/Telegram/SMS... notification.
*   [equalizer (⭐90)](https://github.com/reugn/equalizer) - Quota manager and rate limiter collection for Go.
*   [ergo (⭐633)](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy.
*   [evaluator (⭐41)](https://github.com/nullne/evaluator) - Evaluate an expression dynamically based on s-expression. It's simple and easy to extend.
*   [Failsafe-go (⭐1.7k)](https://github.com/failsafe-go/failsafe-go) - Fault tolerance and resilience patterns for Go.
*   [filetype (⭐2.2k)](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.
*   [filler (⭐18)](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag.
*   [filter (⭐150)](https://github.com/gookit/filter) - provide filtering, sanitizing, and conversion of Go data.
*   [fzf (⭐68k)](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.
*   [generate (⭐30)](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex.
*   [ghokin (⭐46)](https://github.com/antham/ghokin) - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...).
*   [git-time-metric (⭐989)](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git.
*   [gitbatch (⭐1.6k)](https://github.com/isacikgoz/gitbatch) - manage your git repositories in one place.
*   [gitcs (⭐121)](https://github.com/knbr13/gitcs/) - Git Commits Visualizer, CLI tool to visualize your Git commits on your local machine.
*   [go-actuator (⭐16)](https://github.com/sinhashubham95/go-actuator) - Production ready features for Go based web frameworks.
*   [go-astitodo (⭐66)](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code.
*   [go-bind-plugin (⭐182)](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
*   [go-bsdiff (⭐162)](https://github.com/gabstv/go-bsdiff) - Pure Go bsdiff and bspatch libraries and CLI tools.
*   [go-clip (⭐14)](https://github.com/prashantgupta24/go-clip) - A minimalistic clipboard manager for Mac.
*   [go-convert (⭐22)](https://github.com/Eun/go-convert) - Package go-convert enables you to convert a value into another type.
*   [go-countries (⭐16)](https://github.com/mikekonan/go-countries) - Lightweight lookup over ISO-3166 codes.
*   [go-dry (⭐487)](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go.
*   [go-events (⭐5)](https://github.com/deatil/go-events) - A go event and event'subscribe package, like wordpress hook functions.
*   [go-funk (⭐4.9k)](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
*   [go-health (⭐96)](https://github.com/Talento90/go-health) - Health package simplifies the way you add health check to your services.
*   [go-httpheader (⭐47)](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields.
*   [go-lambda-cleanup (⭐92)](https://github.com/karl-cardenas-coding/go-lambda-cleanup) - A CLI for removing unused or previous versions of AWS Lambdas.
*   [go-lock (⭐118)](https://github.com/viney-shih/go-lock) - go-lock is a lock library implementing read-write mutex and read-write trylock without starvation.
*   [go-pattern-match (⭐92)](https://github.com/PhakornKiong/go-pattern-match) - A Pattern matching library inspired by ts-pattern.
*   [go-pkg (⭐7)](https://github.com/chenquan/go-pkg) - A go toolkit.
*   [go-problemdetails (⭐17)](https://github.com/mvmaasakkers/go-problemdetails) - Go package for working with Problem Details.
*   [go-qr (⭐36)](https://github.com/piglig/go-qr) - A native, high-quality and minimalistic QR code generator.
*   [go-rate (⭐399)](https://github.com/beefsack/go-rate) - Timed rate limiter for Go.
*   [go-sitemap-generator (⭐225)](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.
*   [go-trigger (⭐248)](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
*   [go-tripper (⭐14)](https://github.com/rajnandan1/go-tripper) - Tripper is a circuit breaker package for Go that allows you to circuit and control the status of circuits.
*   [go-type (⭐19)](https://github.com/mikekonan/go-types) - Library providing Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types.
*   [goback (⭐49)](https://github.com/carlescere/goback) - Go simple exponential backoff package.
*   [goctx (⭐10)](https://github.com/zerosnake0/goctx) - Get your context value with high performance.
*   [godaemon (⭐493)](https://github.com/VividCortex/godaemon) - Utility to write daemons.
*   [godropbox (⭐4.2k)](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.
*   [gofn (⭐52)](https://github.com/tiendc/gofn) - High performance utility functions written using Generics for Go 1.18+.
*   [golarm (⭐53)](https://github.com/msempere/golarm) - Fire alarms with system events.
*   [golog (⭐63)](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks.
*   [gopencils (⭐453)](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
*   [goplaceholder (⭐29)](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images.
*   [goreadability (⭐69)](https://github.com/philipjkim/goreadability) - Webpage summary extractor using Facebook Open Graph and arc90's readability.
*   [goreleaser (⭐14k)](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.
*   [goreporter (⭐3.1k)](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.
*   [goseaweedfs (⭐113)](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features.
*   [gostrutils (⭐46)](https://github.com/ik5/gostrutils) - Collections of string manipulation and conversion functions.
*   [gotenv (⭐301)](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go.
*   [goval (⭐162)](https://github.com/maja42/goval) - Evaluate arbitrary expressions in Go.
*   [graterm (⭐27)](https://github.com/skovtunenko/graterm) - Provides primitives to perform ordered (sequential/concurrent) GRAceful TERMination (aka shutdown) in Go application.
*   [grofer (⭐367)](https://github.com/pesos/grofer) - A system and resource monitoring tool written in Golang!
*   [gubrak (⭐491)](https://github.com/novalagung/gubrak) - Golang utility library with syntactic sugar. It's like lodash, but for golang.
*   [handy (⭐82)](https://github.com/miguelpragier/handy) - Many utilities and helpers like string handlers/formatters and validators.
*   [hostctl (⭐1.1k)](https://github.com/guumaster/hostctl) - A CLI tool to manage /etc/hosts with easy commands.
*   [htcat (⭐555)](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility.
*   [hub (⭐23k)](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.
*   [immortal (⭐811)](https://github.com/immortal/immortal) - \*nix cross-platform (OS agnostic) supervisor.
*   [jet (⭐11)](https://github.com/NicoNex/jet) - Just Edit Text: a fast and powerful tool for finding and replacing file content and names using regular expressions.
*   [jsend (⭐22)](https://github.com/clevergo/jsend) - JSend's implementation written in Go.
*   [json-log-viewer (⭐140)](https://github.com/hedhyw/json-log-viewer) - Interactive viewer for JSON logs.
*   [jump (⭐1.8k)](https://github.com/gsamokovarov/jump) - Jump helps you navigate faster by learning your habits.
*   [just (⭐32)](https://github.com/kazhuravlev/just) - Just a collection of useful functions for working with generic data structures.
*   [koazee (⭐530)](https://github.com/wesovilabs/koazee) - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays.
*   [lancet (⭐4.9k)](https://github.com/duke-git/lancet) - A comprehensive, efficient, and reusable util function library of go.
*   [lets-go (⭐7)](https://github.com/aplescia-chwy/lets-go) - Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities.
*   [limiters (⭐521)](https://github.com/mennanov/limiters) - Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks.
*   [lo (⭐19k)](https://github.com/samber/lo) - A Lodash like Go library based on Go 1.18+ Generics (map, filter, contains, find...)
*   [loncha (⭐11)](https://github.com/kazu/loncha) - A high-performance slice Utilities.
*   [lrserver (⭐128)](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go.
*   [mani (⭐464)](https://github.com/alajmo/mani) - CLI tool to help you manage multiple repositories.
*   [mc (⭐3k)](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
*   [mergo (⭐2.9k)](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
*   [mimemagic (⭐100)](https://github.com/zRedShift/mimemagic) - Pure Go ultra performant MIME sniffing library/utility.
*   [mimesniffer (⭐33)](https://github.com/aofei/mimesniffer) - A MIME type sniffer for Go.
*   [mimetype (⭐1.7k)](https://github.com/gabriel-vasile/mimetype) - Package for MIME type detection based on magic numbers.
*   [minify (⭐3.8k)](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
*   [minquery (⭐62)](https://github.com/icza/minquery) - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off).
*   [moldova (⭐169)](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template.
*   [mole (⭐1.7k)](https://github.com/davrodpin/mole) - cli app to easily create ssh tunnels.
*   [mongo-go-pagination (⭐131)](https://github.com/gobeam/mongo-go-pagination) - Mongodb Pagination for official mongodb/mongo-go-driver package which supports both normal queries and Aggregation pipelines.
*   [mssqlx (⭐102)](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.
*   [multitick (⭐70)](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers.
*   [netbug (⭐72)](https://github.com/e-dard/netbug) - Easy remote profiling of your services.
*   [nfdump (⭐11)](https://github.com/chrispassas/nfdump) - Read nfdump netflow files.
*   [nostromo (⭐144)](https://github.com/pokanop/nostromo) - CLI for building powerful aliases.
*   [okrun (⭐16)](https://github.com/xta/okrun) - go run error steamroller.
*   [olaf (⭐5)](https://github.com/btnguyen2k/olaf) - Twitter Snowflake implemented in Go.
*   [onecache (⭐136)](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
*   [panicparse (⭐3.6k)](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
*   [pattern-match (⭐245)](https://github.com/alexpantyukhin/go-pattern-match) - Pattern matching library.
*   [peco (⭐7.7k)](https://github.com/peco/peco) - Simplistic interactive filtering tool.
*   [pgo (⭐86)](https://github.com/arthurkushman/pgo) - Convenient functions for PHP community.
*   [pm (⭐79)](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API.
*   [pointer (⭐42)](https://github.com/xorcare/pointer) - Package pointer contains helper routines for simplifying the creation of optional fields of basic type.
*   [ptr (⭐27)](https://github.com/gotidy/ptr) - Package that provide functions for simplified creation of pointers from constants of basic types.
*   [rclient (⭐35)](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs.
*   [remote-touchpad (⭐578)](https://github.com/Unrud/remote-touchpad) - Control mouse and keyboard from a smartphone.
*   [repeat (⭐85)](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating.
*   [request (⭐426)](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™.
*   [rerun (⭐166)](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes.
*   [rest-go (⭐16)](https://github.com/edermanoel94/rest-go) - A package that provide many helpful methods for working with rest api.
*   [retry (⭐342)](https://github.com/kamilsk/retry) - The most advanced functional mechanism to perform actions repetitively until successful.
*   [retry (⭐10)](https://github.com/percolate/retry) - A simple but highly configurable retry package for Go.
*   [retry (⭐66)](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go.
*   [retry (⭐12)](https://github.com/shafreeck/retry) - A pretty simple library to ensure your work to be done.
*   [retry-go (⭐2.6k)](https://github.com/avast/retry-go) - Simple library for retry mechanism.
*   [retry-go (⭐50)](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang.
*   [robustly (⭐159)](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics.
*   [rospo (⭐322)](https://github.com/ferama/rospo) - Simple and reliable ssh tunnels with embedded ssh server in Golang.
*   [scan (⭐581)](https://github.com/blockloop/scan) - Scan golang `sql.Rows` directly to structs, slices, or primitive types.
*   [scan (⭐65)](https://github.com/wroge/scan) - Scan sql rows into any type powered by generics.
*   [scany (⭐1.4k)](https://github.com/georgysavva/scany) - Library for scanning data from a database into Go structs and more.
*   [serve (⭐335)](https://github.com/syntaqx/serve) - A static http server anywhere you need.
*   [sesh (⭐859)](https://github.com/joshmedeski/sesh) - Sesh is a CLI that helps you create and manage tmux sessions quickly and easily using zoxide.
*   [set (⭐47)](https://github.com/nofeaturesonlybugs/set) - Performant and flexible struct mapping and loose type conversion.
*   [shutdown (⭐59)](https://github.com/ztrue/shutdown) - App shutdown hooks for `os.Signal` handling.
*   [silk (⭐13)](https://github.com/chrispassas/silk) - Read silk netflow files.
*   [slice (⭐51)](https://github.com/psampaz/slice) - Type-safe functions for common Go slice operations.
*   [sliceconv (⭐10)](https://github.com/Henry-Sarabia/sliceconv) - Slice conversion between primitive types.
*   [slicer (⭐46)](https://github.com/leaanthony/slicer) - Makes working with slices easier.
*   [sorty (⭐134)](https://github.com/jfcg/sorty) - Fast Concurrent / Parallel Sorting.
*   [sqlx (⭐17k)](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.
*   [sshman (⭐50)](https://github.com/shoobyban/sshman) - SSH Manager for authorized\_keys files on multiple remote servers.
*   [statiks (⭐11)](https://github.com/janiltonmaciel/statiks) - Fast, zero-configuration, static HTTP filer server.
*   [Storm (⭐2.1k)](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.
*   [structs (⭐24)](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs.
*   [throttle (⭐40)](https://github.com/yudppp/throttle) - Throttle is an object that will perform exactly one action per duration.
*   [tik (⭐5)](https://github.com/andy2046/tik) - Simple and easy timing wheel package for Go.
*   [tome (⭐34)](https://github.com/cyruzin/tome) - Tome was designed to paginate simple RESTful APIs.
*   [toolbox (⭐199)](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
*   [UNIS (⭐70)](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go.
*   [upterm (⭐904)](https://github.com/owenthereal/upterm) - A tool for developers to share terminal/tmux sessions securely over the web. It’s perfect for remote pair programming, accessing computers behind NATs/firewalls, remote debugging, and more.
*   [usql (⭐9.2k)](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.
*   [util (⭐296)](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
*   [watchhttp (⭐33)](https://github.com/nikolaydubina/watchhttp) - Run command periodically and expose latest STDOUT or its rich delta as HTTP endpoint.
*   [wifiqr (⭐266)](https://github.com/reugn/wifiqr) - Wi-Fi QR Code Generator.
*   [wuzz (⭐11k)](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.
*   [xferspdy (⭐101)](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang.
*   [xpool (⭐3)](https://github.com/peczenyj/xpool) - Yet another golang type safe object pool using generics.
*   [yogo (⭐43)](https://github.com/antham/yogo) - Check yopmail mails from command line.

**[⬆ back to top](#contents)**

## UUID

*Libraries for working with UUIDs.*

*   [fastuuid (⭐0)](https://github.com/rekby/fastuuid) - Fast generate UUIDv4 as string or bytes.
*   [goid (⭐41)](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs.
*   [gouid (⭐25)](https://github.com/twharmon/gouid) - Generate cryptographically secure random string IDs with just one allocation.
*   [nanoid (⭐62)](https://github.com/aidarkhanov/nanoid) - A tiny and efficient Go unique string ID generator.
*   [sno (⭐91)](https://github.com/muyo/sno) - Compact, sortable and fast unique IDs with embedded metadata.
*   [ulid (⭐4.6k)](https://github.com/oklog/ulid) - Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier).
*   [uniq](https://gitlab.com/skilstak/code/go/uniq) - No hassle safe, fast unique identifiers with commands.
*   [uuid (⭐18)](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.
*   [uuid (⭐1.6k)](https://github.com/gofrs/uuid) - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid.
*   [uuid (⭐5.5k)](https://github.com/google/uuid) - Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services.
*   [uuidcheck (⭐5)](https://github.com/ashwingopalsamy/uuidcheck) - A tiny, dependency-free Go library that validates UUIDs against standard RFC 4122 formatting, converts UUIDv7() into UTC timestamps.
*   [wuid (⭐536)](https://github.com/edwingeng/wuid) - An extremely fast globally unique number generator.
*   [xid (⭐4k)](https://github.com/rs/xid) - Xid is a globally unique id generator library, ready to be safely used directly in your server code.

**[⬆ back to top](#contents)**

## Validation

*Libraries for validation.*

*   [checkdigit (⭐111)](https://github.com/osamingo/checkdigit) - Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.).
*   [go-validator (⭐28)](https://github.com/tiendc/go-validator) - Validation library using Generics.
*   [gody (⭐117)](https://github.com/guiferpa/gody) - :balloon: A lightweight struct validator for Go.
*   [govalid (⭐81)](https://github.com/twharmon/govalid) - Fast, tag-based validation for structs.
*   [govalidator (⭐6.1k)](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs.
*   [govalidator (⭐1.3k)](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.
*   [hvalid (⭐11)](https://github.com/lyonnee/hvalid) hvalid is a lightweight validation library written in Go language. It provides a custom validator interface and a series of common validation functions to help developers quickly implement data validation.
*   [jio (⭐114)](https://github.com/faceair/jio) - jio is a json schema validator similar to [joi (⭐21k)](https://github.com/hapijs/joi).
*   [ozzo-validation (⭐3.9k)](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
*   [validate (⭐1.1k)](https://github.com/gookit/validate) - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features.
*   [validate (⭐94)](https://github.com/gobuffalo/validate) - This package provides a framework for writing validations for Go applications.
*   [validator (⭐18k)](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.
*   [Validator (⭐7)](https://github.com/go-the-way/validator) - A lightweight model validator written in Go.Contains VFs:Min, Max, MinLength, MaxLength, Length, Enum, Regex.
*   [valix (⭐29)](https://github.com/marrow16/valix) Go package for validating requests
*   [Zog (⭐514)](https://github.com/Oudwins/zog) - A [Zod (⭐36k)](https://github.com/colinhacks/zod) inspired schema builder for runtime value parsing and validation.
    **[⬆ back to top](#contents)**

## Version Control

*Libraries for version control.*

*   [cli](https://gitlab.com/gitlab-org/cli) - An open-source GitLab command line tool bringing GitLab's cool features to your command line.
*   [froggit-go (⭐46)](https://github.com/jfrog/froggit-go) - Froggit-Go is a Go library, allowing to perform actions on VCS providers.
*   [git2go (⭐2k)](https://github.com/libgit2/git2go) - Go bindings for libgit2.
*   [githooks (⭐107)](https://github.com/gabyx/githooks) - Per-repo and shared Git hooks with version control and auto update.
*   [go-git (⭐6.2k)](https://github.com/go-git/go-git) - highly extensible Git implementation in pure Go.
*   [go-vcs (⭐80)](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go.
*   [hercules (⭐2.7k)](https://github.com/src-d/hercules) - gaining advanced insights from Git repository history.
*   [hgo (⭐16)](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.

**[⬆ back to top](#contents)**

## Video

*Libraries for manipulating video.*

*   [gmf (⭐903)](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries.
*   [go-astiav (⭐448)](https://github.com/asticode/go-astiav) - Better C bindings for ffmpeg in GO.
*   [go-astisub (⭐617)](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
*   [go-astits (⭐554)](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO.
*   [go-m3u8 (⭐32)](https://github.com/etherlabsio/go-m3u8) - Parser and generator library for Apple m3u8 playlists. Actively maintained version of quangngotan95/go-m3u8 with improvements and latest HLS playlist parsing compatibility.
*   [go-mpd (⭐24)](https://github.com/unki2aut/go-mpd) - Parser and generator library for MPEG-DASH manifest files.
*   [goav (⭐2.1k)](https://github.com/giorgisio/goav) - Comprehensive Go bindings for FFmpeg.
*   [gortsplib (⭐737)](https://github.com/aler9/gortsplib) - Pure Go RTSP server and client library.
*   [libvlc-go (⭐456)](https://github.com/adrg/libvlc-go) - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player).
*   [m3u8 (⭐1.3k)](https://github.com/grafov/m3u8) - Parser and generator library of M3U8 playlists for Apple HLS.
*   [mp4ff (⭐504)](https://github.com/Eyevinn/mp4ff) - Library and tools for working with MP4 files containing video, audio, subtitles, or metadata.
*   [v4l (⭐81)](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go.

**[⬆ back to top](#contents)**

## Web Frameworks

*Full stack web frameworks.*

*   [Atreugo (⭐1.3k)](https://github.com/savsgio/atreugo) - High performance and extensible micro web framework with zero memory allocations in hot paths.
*   [Beego (⭐32k)](https://github.com/beego/beego) - beego is an open-source, high-performance web framework for the Go programming language.
*   [Confetti Framework](https://confetti-framework.github.io/docs/) - Confetti is a Go web application framework with an expressive, elegant syntax. Confetti combines the elegance of Laravel and the simplicity of Go.
*   [Don (⭐56)](https://github.com/abemedia/go-don) - A highly performant and simple to use API framework.
*   [Echo (⭐31k)](https://github.com/labstack/echo) - High performance, minimalist Go web framework.
*   [Fastschema (⭐395)](https://github.com/fastschema/fastschema) - A flexible Go web framework and Headless CMS.
*   [Fiber (⭐35k)](https://github.com/gofiber/fiber) - An Express.js inspired web framework build on Fasthttp.
*   [Flamingo (⭐500)](https://github.com/i-love-flamingo/flamingo) - Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc.
*   [Flamingo Commerce (⭐542)](https://github.com/i-love-flamingo/flamingo-commerce) - Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications.
*   [Fuego (⭐1.2k)](https://github.com/go-fuego/fuego) - The framework for busy Go developers! Web framework generating OpenAPI 3 spec from source code.
*   [Gin (⭐81k)](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
*   [Ginrpc (⭐292)](https://github.com/xxjwxc/ginrpc) - Gin parameter automatic binding tool,gin rpc tools.
*   [Goa (⭐5.8k)](https://github.com/goadesign/goa) - Goa provides a holistic approach for developing remote APIs and microservices in Go.
*   [GoFr (⭐4.2k)](https://github.com/gofr-dev/gofr) - Gofr is an opinionated microservice development framework.
*   [GoFrame (⭐12k)](https://github.com/gogf/gf) - GoFrame is a modular, powerful, high-performance and enterprise-class application development framework of Golang.
*   [golamb (⭐7)](https://github.com/twharmon/golamb) - Golamb makes it easier to write API endpoints for use with AWS Lambda and API Gateway.
*   [Gone (⭐120)](https://github.com/gone-io/gone) - A lightweight dependency injection and web framework inspired by Spring.
*   [goravel (⭐3.2k)](https://github.com/goravel/goravel) - A Laravel-inspired web framework with ORM, authentication, queue, task scheduling, and more built-in features.
*   [Goyave (⭐1.7k)](https://github.com/go-goyave/goyave) - Feature-complete REST API framework aimed at clean code and fast development, with powerful built-in functionalities.
*   [Hertz (⭐5.9k)](https://github.com/cloudwego/hertz) - A high-performance and strong-extensibility Go HTTP framework that helps developers build microservices.
*   [hiboot (⭐181)](https://github.com/hidevopsio/hiboot) - hiboot is a high performance web application framework with auto configuration and dependency injection support.
*   [Huma (⭐2.7k)](https://github.com/danielgtaylor/huma/) - Framework for modern REST/GraphQL APIs with built-in OpenAPI 3, generated documentation, and a CLI.
*   [iWF (⭐538)](https://github.com/indeedeng/iwf) - iWF is an all-in-one platform for developing long-running business processes. It offers a convenient abstraction for utilizing databases, ElasticSearch, message queues, durable timers, and more, with a clean, simple, and user-friendly interface.
*   [Lit (⭐26)](https://github.com/jvcoutinho/lit) - Highly performant declarative web framework for Golang, aiming for simplicity and quality of life.
*   [Microservice (⭐118)](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang.
*   [patron (⭐123)](https://github.com/beatlabs/patron) - Patron is a microservice framework following best cloud practices with a focus on productivity.
*   [Pnutmux](https://gitlab.com/fruitygo/pnutmux) - Pnutmux is a powerful Go web framework that uses regex for matching and handling HTTP requests. It offers features such as CORS handling, structured logging, URL parameters extraction, middlewares, and concurrency limiting.
*   [Revel (⭐13k)](https://github.com/revel/revel) - High-productivity web framework for the Go language.
*   [rk-boot (⭐526)](https://github.com/rookie-ninja/rk-boot) - A bootstrapper library for building enterprise go microservice with Gin and gRPC quickly and easily.
*   [rux (⭐97)](https://github.com/gookit/rux) - Simple and fast web framework for build golang HTTP applications.
*   [templui (⭐319)](https://github.com/axzilla/templui) - Modern UI Components for Go & Templ.
*   [uAdmin (⭐351)](https://github.com/uadmin/uadmin) - Fully featured web framework for Golang, inspired by Django.
*   [WebGo (⭐303)](https://github.com/naughtygopher/webgo) - A micro-framework to build web apps with handler chaining, middleware, and context injection. With standard library-compliant HTTP handlers (i.e., `http.HandlerFunc`)..
*   [Yokai (⭐659)](https://github.com/ankorstore/yokai) - Simple, modular, and observable Go framework for backend applications.

**[⬆ back to top](#contents)**

### Middlewares

#### Actual middlewares

*   [client-timing (⭐24)](https://github.com/posener/client-timing) - An HTTP client for Server-Timing header.
*   [CORS (⭐2.7k)](https://github.com/rs/cors) - Easily add CORS capabilities to your API.
*   [echo-middleware (⭐15)](https://github.com/faabiosr/echo-middleware) - Middleware for Echo framework with logging and metrics.
*   [formjson (⭐39)](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST.
*   [go-fault (⭐509)](https://github.com/github/go-fault) - Fault injection middleware for Go.
*   [go-server-timing (⭐859)](https://github.com/mitchellh/go-server-timing) - Add/parse Server-Timing header.
*   [Limiter (⭐2.2k)](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.
*   [ln-paywall (⭐153)](https://github.com/philippgille/ln-paywall) - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin).
*   [mid (⭐10)](https://github.com/bobg/mid) - Miscellaneous HTTP middleware features: idiomatic error return from handlers; receive/respond with JSON data; request tracing; and more.
*   [rk-gin (⭐49)](https://github.com/rookie-ninja/rk-gin) - Middleware for Gin framework with logging, metrics, auth, tracing etc.
*   [rk-grpc (⭐75)](https://github.com/rookie-ninja/rk-grpc) - Middleware for gRPC with logging, metrics, auth, tracing etc.
*   [Tollbooth (⭐2.8k)](https://github.com/didip/tollbooth) - Rate limit HTTP request handler.
*   [XFF (⭐98)](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends.

#### Libraries for creating HTTP middlewares

*   [alice (⭐3.2k)](https://github.com/justinas/alice) - Painless middleware chaining for Go.
*   [catena (⭐9)](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain").
*   [chain (⭐62)](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").
*   [gores (⭐104)](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
*   [interpose (⭐293)](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang.
*   [mediary (⭐88)](https://github.com/HereMobilityDevelopers/mediary) - add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses.
*   [muxchain (⭐206)](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http.
*   [negroni (⭐7.5k)](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang.
*   [render (⭐2k)](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses.
*   [renderer (⭐262)](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.
*   [rye (⭐101)](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.
*   [stats (⭐594)](https://github.com/thoas/stats) - Go middleware that stores various information about your web application.

**[⬆ back to top](#contents)**

### Routers

*   [alien (⭐134)](https://github.com/gernest/alien) - Lightweight and fast http router from outer space.
*   [bellt (⭐54)](https://github.com/GuilhermeCaruso/bellt) - A simple Go HTTP router.
*   [Bone (⭐1.3k)](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer.
*   [Bxog (⭐101)](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
*   [chi (⭐19k)](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context.
*   [fasthttprouter (⭐870)](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
*   [FastRouter (⭐23)](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go.
*   [goblin (⭐79)](https://github.com/bmf-san/goblin) - A golang http router based on trie tree.
*   [gocraft/web (⭐1.5k)](https://github.com/gocraft/web) - Mux and middleware package in Go.
*   [Goji (⭐969)](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.
*   [GoLobby/Router (⭐22)](https://github.com/golobby/router) - GoLobby Router is a lightweight yet powerful HTTP router for the Go programming language.
*   [goroute (⭐9)](https://github.com/goroute/route) - Simple yet powerful HTTP request multiplexer.
*   [GoRouter (⭐154)](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.
*   [gowww/router (⭐185)](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface.
*   [httprouter (⭐17k)](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework.
*   [httptreemux (⭐617)](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
*   [lars (⭐384)](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
*   [mux (⭐21k)](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang.
*   [nchi (⭐16)](https://github.com/muir/nchi) - chi-like router built on httprouter with dependency injection based middleware wrappers
*   [ngamux (⭐70)](https://github.com/ngamux/ngamux) - Simple HTTP router for Go.
*   [ozzo-routing (⭐454)](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
*   [pure (⭐150)](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation.
*   [Siesta (⭐349)](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers.
*   [vestigo (⭐267)](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications.
*   [violetear (⭐107)](https://github.com/nbari/violetear) - Go HTTP router.
*   [xmux (⭐99)](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support.
*   [xujiajun/gorouter (⭐531)](https://github.com/xujiajun/gorouter) - A simple and fast HTTP router for Go.

**[⬆ back to top](#contents)**

## WebAssembly

*   [dom (⭐492)](https://github.com/dennwc/dom) - DOM library.
*   [Extism Go SDK (⭐105)](https://github.com/extism/go-sdk) - Universal, cross-language WebAssembly framework for building plug-in systems and polyglot apps.
*   [go-canvas (⭐255)](https://github.com/markfarnan/go-canvas) - Library to use HTML5 Canvas, with all drawing within go code.
*   [tinygo (⭐16k)](https://github.com/tinygo-org/tinygo) - Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM.
*   [vert (⭐102)](https://github.com/norunners/vert) - Interop between Go and JS values.
*   [wasmbrowsertest (⭐196)](https://github.com/agnivade/wasmbrowsertest) - Run Go WASM tests in your browser.
*   [webapi (⭐175)](https://github.com/gowebapi/webapi) - Bindings for DOM and HTML generated from WebIDL.

**[⬆ back to top](#contents)**

## Webhooks Server

*   [webhook (⭐11k)](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
*   [webhooked (⭐37)](https://github.com/42Atomys/webhooked) - A webhook receiver on steroids: handle, secure, format and store a Webhook payload has never been easier.
*   [WebhookX (⭐135)](https://github.com/webhookx-io/webhookx) - A webhooks gateway for message receiving, processing, and reliable delivering.

**[⬆ back to top](#contents)**

## Windows

*   [d3d9 (⭐160)](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9.
*   [go-ole (⭐1.2k)](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang.
*   [gosddl (⭐11)](https://github.com/MonaxGT/gosddl) - Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL.

**[⬆ back to top](#contents)**

## Workflow Frameworks

*Libraries for creating Workflows.*

*   [Cadence-client (⭐355)](https://github.com/uber-go/cadence-client) - A framework for authoring workflows and activities running on top of the Cadence orchestration engine made by Uber.
*   [Dagu (⭐1.9k)](https://github.com/dagu-go/dagu) - No-code workflow executor. it executes DAGs defined in a simple YAML format.
*   [go-dag (⭐25)](https://github.com/rhosocial/go-dag) - A framework developed in Go that manages the execution of workflows described by directed acyclic graphs.
*   [go-taskflow (⭐443)](https://github.com/noneback/go-taskflow) - A taskflow-like General-purpose Task-parallel Programming Framework with integrated visualizer and profiler.
*   [workflow (⭐137)](https://github.com/luno/workflow) - A tech stack agnostic Event Driven Workflow framework.

**[⬆ back to top](#contents)**

## XML

*Libraries and tools for manipulating XML.*

*   [XML-Comp (⭐21)](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags.
*   [xml2map (⭐62)](https://github.com/sbabiv/xml2map) - XML to MAP converter written Golang.
*   [xmlquery (⭐457)](https://github.com/antchfx/xmlquery) - xmlquery is Golang XPath package for XML query.
*   [xmlwriter (⭐28)](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module.
*   [xpath (⭐699)](https://github.com/antchfx/xpath) - XPath package for Go.
*   [zek (⭐762)](https://github.com/miku/zek) - Generate a Go struct from XML.

## Zero Trust

*Libraries and tools to implement Zero Trust architectures.*

*   [Cosign (⭐4.7k)](https://github.com/sigstore/cosign) - Container Signing, Verification and Storage in an OCI registry.
*   [in-toto (⭐135)](https://github.com/in-toto/in-toto-golang) - Go implementation of the in-toto (provides a framework to protect the integrity of the software supply chain) python reference implementation.
*   [OpenZiti (⭐3.1k)](https://github.com/openziti/ziti) - A full, open source zero trust overlay network. Including numerous SDKs for numerous languages such as [golang (⭐102)](https://github.com/openziti/sdk-golang) allowing you to embed zero trust principles directly into your applications. The [OpenZiti Test Kitchen](https://github.com/openziti-test-kitchen) has numerous examples to draw inspiration from including a [zero trust ssh client - zssh (⭐38)](https://github.com/openziti-test-kitchen/zssh)
*   [Spiffe-Vault (⭐87)](https://github.com/philips-labs/spiffe-vault) - Utilizes Spiffe JWT authentication with Hashicorp Vault for secretless authentication.
*   [Spire (⭐1.9k)](https://github.com/spiffe/spire) - SPIRE (the SPIFFE Runtime Environment) is a toolchain of APIs for establishing trust between software systems across a wide variety of hosting platforms.

## Code Analysis

*Source code analysis tools, also known as Static Application Security Testing (SAST) Tools.*

*   [apicompat (⭐179)](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes.
*   [asty (⭐83)](https://github.com/asty-org/asty) - Converts golang AST to JSON and JSON to AST.
*   [blanket](https://gitlab.com/verygoodsoftwarenotvirus/blanket) - blanket is a tool that helps you catch functions which don't have direct unit tests in your Go packages.
*   [ChainJacking (⭐58)](https://github.com/Checkmarx/chainjacking) - Find which of your Go lang direct GitHub dependencies is susceptible to ChainJacking attack.
*   [Chronos (⭐432)](https://github.com/amit-davidson/Chronos) - Detects race conditions statically
*   [dupl (⭐348)](https://github.com/mibk/dupl) - Tool for code clone detection.
*   [errcheck (⭐2.4k)](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.
*   [fatcontext (⭐26)](https://github.com/Crocmagnon/fatcontext) - Fatcontext detects nested contexts in loops or function literals.
*   [go-checkstyle (⭐130)](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments.
*   [go-cleanarch (⭐913)](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.
*   [go-critic (⭐1.9k)](https://github.com/go-critic/go-critic) - source code linter that brings checks that are currently not implemented in other linters.
*   [go-mod-outdated (⭐653)](https://github.com/psampaz/go-mod-outdated) - An easy way to find outdated dependencies of your Go projects.
*   [goast-viewer (⭐776)](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer.
*   [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
*   [golang-ifood-sdk (⭐12)](https://github.com/arxdsilva/golang-ifood-sdk) - iFood API SDK.
*   [golangci-lint (⭐16k)](https://github.com/golangci/golangci-lint) – A fast Go linters runner. It runs linters in parallel, uses caching, supports `yaml` config, has integrations with all major IDE and has dozens of linters included.
*   [golines (⭐993)](https://github.com/segmentio/golines) - Formatter that automatically shortens long lines in Go code.
*   [GoPlantUML (⭐1.9k)](https://github.com/jfeliu007/goplantuml) - Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them.
*   [goreturns (⭐531)](https://github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
*   [gostatus (⭐242)](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages.
*   [lint (⭐66)](https://github.com/surullabs/lint) - Run linters as part of go test.
*   [php-parser (⭐943)](https://github.com/z7zmey/php-parser) - A Parser for PHP written in Go.
*   [revive (⭐4.9k)](https://github.com/mgechev/revive) – \~6x faster, stricter, configurable, extensible, and beautiful drop-in replacement for `golint`.
*   [staticcheck (⭐6.3k)](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
*   [testifylint (⭐123)](https://github.com/Antonboom/testifylint) – A linter that checks usage of [github.com/stretchr/testify (⭐24k)](https://github.com/stretchr/testify).
*   [tickgit (⭐323)](https://github.com/augmentable-dev/tickgit) - CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author.
*   [todocheck (⭐429)](https://github.com/preslavmihaylov/todocheck) - Static code analyser which links TODO comments in code with issues in your issue tracker.
*   [unconvert (⭐383)](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source.
*   [usestdlibvars (⭐44)](https://github.com/sashamelentyev/usestdlibvars) - A linter that detect the possibility to use variables/constants from the Go standard library.
*   [vacuum (⭐721)](https://github.com/daveshanley/vacuum) - An ultra-super-fast, lightweight OpenAPI linter and quality checking tool.
*   [validate (⭐61)](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.
*   [wrapcheck (⭐321)](https://github.com/tomarrell/wrapcheck) - A linter to check that errors from external packages are wrapped.

**[⬆ back to top](#contents)**

## Editor Plugins

*Plugin for text editors and IDEs.*

*   [coc-go language server extension for Vim/Neovim (⭐569)](https://github.com/josa42/coc-go) - This plugin adds [gopls (⭐7.5k)](https://github.com/golang/tools/blob/master/gopls/README.md) features to Vim/Neovim.
*   [Go Doc (⭐8)](https://github.com/msyrus/vscode-go-doc) - A Visual Studio Code extension for showing definition in output and generating go doc.
*   [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
*   [go-mode (⭐1.4k)](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
*   [gocode (⭐5k)](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language.
*   [goimports-reviser (⭐637)](https://github.com/incu6us/goimports-reviser) - Formatting tool for imports.
*   [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - This extension adds benchmark profiling support for the Go language to VS Code.
*   [GoSublime (⭐3.4k)](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features.
*   [gounit-vim (⭐24)](https://github.com/hexdigest/gounit-vim) - Vim plugin for generating Go tests based on the function's or method's signature.
*   [vim-compiler-go (⭐90)](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.
*   [vim-go (⭐16k)](https://github.com/fatih/vim-go) - Go development plugin for Vim.
*   [vscode-go (⭐4k)](https://github.com/golang/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
*   [Watch (⭐202)](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes.

**[⬆ back to top](#contents)**

## Go Generate Tools

*   [envdoc (⭐75)](https://github.com/g4s8/envdoc) -  generate documentation for environment variables from Go source files.
*   [generic (⭐49)](https://github.com/usk81/generic) - flexible data type for Go.
*   [gocontracts (⭐113)](https://github.com/Parquery/gocontracts) - brings design-by-contract to Go by synchronizing the code with the documentation.
*   [godal (⭐18)](https://github.com/mafulong/godal) - Generate orm models corresponding to golang by specifying sql ddl file, which can be used by gorm.
*   [gonerics (⭐114)](https://github.com/bouk/gonerics) - Idiomatic Generics in Go.
*   [gotests (⭐5k)](https://github.com/cweill/gotests) - Generate Go tests from your source code.
*   [gounit (⭐83)](https://github.com/hexdigest/gounit) - Generate Go tests using your own templates.
*   [hasgo (⭐142)](https://github.com/DylanMeeus/hasgo) - Generate Haskell inspired functions for your slices.
*   [options-gen (⭐84)](https://github.com/kazhuravlev/options-gen) - Functional options described by Dave Cheney's post "Functional options for friendly APIs".
*   [re2dfa](https://gitlab.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.
*   [sqlgen (⭐84)](https://github.com/anqiansong/sqlgen) - Generate gorm, xorm, sqlx, bun, sql code from SQL file or DSN.
*   [TOML-to-Go](https://xuri.me/toml-to-go) - Translates TOML into a Go type in the browser instantly.
*   [xgen (⭐352)](https://github.com/xuri/xgen) - XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator.

**[⬆ back to top](#contents)**

## Go Tools

*   [colorgo (⭐113)](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output.
*   [decouple (⭐26)](https://github.com/bobg/decouple) - Find “overspecified” function parameters that could be generalized with interface types.
*   [depth (⭐961)](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports.
*   [docs (⭐43)](https://github.com/go-oas/docs) - Automatically generate RESTful API documentation for GO projects - aligned with Open API Specification standard.
*   [go-callvis (⭐6.1k)](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format.
*   [go-size-analyzer (⭐1.5k)](https://github.com/Zxilly/go-size-analyzer) - Analyze and visualize the size of dependencies in compiled Golang binaries, providing insight into their impact on the final build.
*   [go-swagger (⭐9.7k)](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
*   [godbg (⭐205)](https://github.com/tylerwince/godbg) - Implementation of Rusts `dbg!` macro for quick and easy debugging during development.
*   [gomodrun (⭐36)](https://github.com/dustinblackman/gomodrun/) - Go tool that executes and caches binaries included in go.mod files.
*   [gotemplate.io](https://gotemplate.io/) - Online tool to preview `text/template` templates live.
*   [gotestdox (⭐135)](https://github.com/bitfield/gotestdox) - Show Go test results as readable sentences.
*   [gothanks (⭐125)](https://github.com/psampaz/gothanks) - GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers.
*   [igo (⭐67)](https://github.com/rocketlaunchr/igo) - An igo to go transpiler (new language features for Go language!)
*   [modver (⭐19)](https://github.com/bobg/modver) - Compare two versions of a Go module to check the version-number change required (major, minor, or patchlevel), according to [semver](https://semver.org/) rules.
*   [MoniGO (⭐259)](https://github.com/iyashjayesh/monigo) - A performance monitoring library for Go applications. It provides real-time insights into application performance! 🚀
*   [OctoLinker (⭐5.3k)](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
*   [richgo (⭐857)](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations.
*   [roumon (⭐193)](https://github.com/becheran/roumon) - Monitor current state of all active goroutines via a command line interface.
*   [rts (⭐249)](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses.
*   [textra (⭐6)](https://github.com/ravsii/textra) - Extract Go struct field names, types and tags for filtering and exporting.
*   [typex (⭐205)](https://github.com/dtgorski/typex) - Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration.

**[⬆ back to top](#contents)**

## Software Packages

*Software written in Go.*

**[⬆ back to top](#contents)**

### DevOps Tools

*   [abbreviate (⭐221)](https://github.com/dnnrly/abbreviate) - abbreviate is a tool turning long strings in to shorter ones with configurable separators, for example to embed branch names in to deployment stack IDs.
*   [alaz (⭐673)](https://github.com/ddosify/alaz) - Effortless, Low-Overhead, eBPF-based Kubernetes Monitoring.
*   [aptly (⭐2.6k)](https://github.com/aptly-dev/aptly) - aptly is a Debian repository management tool.
*   [aurora (⭐599)](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console.
*   [awsenv (⭐35)](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile.
*   [Balerter (⭐303)](https://github.com/balerter/balerter) - A self-hosted script-based alerting manager.
*   [Blast (⭐218)](https://github.com/dave/blast) - A simple tool for API load testing and batch jobs.
*   [bombardier (⭐6.2k)](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool.
*   [bosun (⭐3.4k)](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.
*   [cassowary (⭐780)](https://github.com/rogerwelin/cassowary) - Modern cross-platform HTTP load-testing tool written in Go.
*   [Ddosify (⭐8.4k)](https://github.com/ddosify/ddosify) - High-performance load testing tool, written in Golang.
*   [decompose (⭐89)](https://github.com/s0rg/decompose) - tool to generate and process Docker containers connections graphs.
*   [DepCharge (⭐23)](https://github.com/centerorbit/depcharge) - Helps orchestrating the execution of commands across the many dependencies in larger projects.
*   [Docker](https://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
*   [docker-go-mingw (⭐49)](https://github.com/x1unix/docker-go-mingw) - Docker image for building Go binaries for Windows with MinGW toolchain.
*   [Dockerfile-Generator (⭐174)](https://github.com/ozankasikci/dockerfile-generator) - A go library and an executable that produces valid Dockerfiles using various input channels.
*   [dogo (⭐272)](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart).
*   [drone-jenkins (⭐39)](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.
*   [drone-scp (⭐146)](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI.
*   [Dropship (⭐66)](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn.
*   [easyssh-proxy (⭐330)](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
*   [fac (⭐1.8k)](https://github.com/mkchoi212/fac) - Command-line user interface to fix git merge conflicts.
*   [Flannel (⭐9k)](https://github.com/flannel-io/flannel) - Flannel is a network fabric for containers, designed for Kubernetes.
*   [Fleet device management (⭐3.6k)](https://github.com/fleetdm/fleet) - Lightweight, programmable telemetry for servers and workstations.
*   [gaia (⭐5.2k)](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language.
*   [ghorg (⭐1.6k)](https://github.com/gabrie30/ghorg) - Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, Gitea, and Bitbucket.
*   [Gitea (⭐47k)](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven.
*   [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.
*   [go-furnace (⭐99)](https://github.com/go-furnace/go-furnace) - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean.
*   [go-rocket-update (⭐105)](https://github.com/mouuff/go-rocket-update) - A simple way to make self updating Go applications - Supports Github and Gitlab.
*   [go-selfupdate (⭐1.6k)](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update.
*   [gobrew (⭐192)](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.
*   [gobrew (⭐389)](https://github.com/kevincobain2000/gobrew) - Go version manager. Super simple tool to install and manage Go versions. Install go without root. Gobrew doesn't require shell rehash.
*   [godbg (⭐228)](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application.
*   [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
*   [gonative (⭐337)](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
*   [govvv (⭐537)](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries.
*   [grapes (⭐170)](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease.
*   [GVM (⭐11k)](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.
*   [Hey (⭐19k)](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application.
*   [httpref (⭐39)](https://github.com/dnnrly/httpref) - httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports.
*   [jcli (⭐399)](https://github.com/jenkins-zh/jenkins-cli) - Jenkins CLI allows you manage your Jenkins as an easy way.
*   [k3d (⭐5.6k)](https://github.com/k3d-io/k3d) - Little helper to run CNCF's k3s in Docker.
*   [k3s (⭐29k)](https://github.com/k3s-io/k3s) - Lightweight Kubernetes.
*   [k6 (⭐27k)](https://github.com/grafana/k6) - A modern load testing tool, using Go and JavaScript.
*   [kala (⭐2.1k)](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler.
*   [kcli (⭐218)](https://github.com/cswank/kcli) - Command line tool for inspecting kafka topics/partitions/messages.
*   [kind (⭐14k)](https://github.com/kubernetes-sigs/kind) - Kubernetes IN Docker - local clusters for testing Kubernetes.
*   [ko (⭐7.8k)](https://github.com/google/ko) - Command line tool for building and deploying Go applications on Kubernetes
*   [kool (⭐674)](https://github.com/kool-dev/kool) - Command line tool for managing Docker environments as an easy way.
*   [kubeblocks (⭐2.5k)](https://github.com/apecloud/kubeblocks) - KubeBlocks is an open-source control plane that runs and manages databases, message queues and other data infrastructure on K8s.
*   [kubernetes (⭐113k)](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
*   [kubeshark (⭐11k)](https://github.com/kubeshark/kubeshark) - API traffic analyzer for Kubernetes, inspired by Wireshark, purposely built for Kubernetes.
*   [KubeVela (⭐6.6k)](https://github.com/kubevela/kubevela) - Cloud native application delivery.
*   [KubeVPN (⭐1k)](https://github.com/kubenetworks/kubevpn) - KubeVPN offers a Cloud-Native Dev Environment that seamlessly connects to your Kubernetes cluster network.
*   [KusionStack (⭐1.1k)](https://github.com/KusionStack/kusion) - A unified programmable configuration techstack to deliver modern app in 'platform as code' and 'infra as code' approach.
*   [kwatch (⭐973)](https://github.com/abahmed/kwatch) - Monitor & detect crashes in your Kubernetes(K8s) cluster instantly.
*   [lstags (⭐337)](https://github.com/ivanilves/lstags) - Tool and API to sync Docker images across different registries.
*   [lwc (⭐32)](https://github.com/timdp/lwc) - A live-updating version of the UNIX wc command.
*   [manssh (⭐299)](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily.
*   [Mantil (⭐110)](https://github.com/mantil-io/mantil) - Go specific framework for building serverless applications on AWS that enables you to focus on pure Go code while Mantil takes care of the infrastructure.
*   [minikube (⭐30k)](https://github.com/kubernetes/minikube) - Run Kubernetes locally.
*   [Moby (⭐69k)](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.
*   [Mora (⭐314)](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data.
*   [ostent (⭐180)](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
*   [Packer (⭐15k)](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
*   [Pewpew (⭐424)](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester.
*   [PipeCD (⭐1.1k)](https://github.com/pipe-cd/pipecd) - A GitOps-style continuous delivery platform that provides consistent deployment and operations experience for any applications.
*   [podinfo (⭐5.5k)](https://github.com/stefanprodan/podinfo) - Podinfo is a tiny web application made with Go that showcases best practices of running microservices in Kubernetes. Podinfo is used by CNCF projects like Flux and Flagger for end-to-end testing and workshops.
*   [Pomerium (⭐4.2k)](https://github.com/pomerium/pomerium) - Pomerium is an identity-aware access proxy.
*   [Rodent (⭐33)](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.
*   [s3-proxy (⭐322)](https://github.com/oxyno-zeta/s3-proxy) - S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth).
*   [s3gof3r (⭐1.1k)](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
*   [s5cmd (⭐2.9k)](https://github.com/peak/s5cmd) - Blazing fast S3 and local filesystem execution tool.
*   [Scaleway-cli (⭐895)](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker).
*   [script (⭐6.4k)](https://github.com/bitfield/script) - Making it easy to write shell-like scripts in Go for DevOps and system administration tasks.
*   [sg (⭐8)](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response.
*   [skm (⭐962)](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!
*   [StatusOK (⭐1.6k)](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
*   [tau (⭐3.7k)](https://github.com/taubyte/tau) - Easily build Cloud Computing Platforms with features like Serverless WebAssembly Functions, Frontend Hosting, CI/CD, Object Storage, K/V Database, and Pub-Sub Messaging.
*   [terraform-provider-openapi (⭐275)](https://github.com/dikhan/terraform-provider-openapi) - Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed.
*   [tf-profile (⭐156)](https://github.com/datarootsio/tf-profile) - Profiler for Terraform runs. Generate global stats, resource-level stats or visualizations.
*   [tlm (⭐1.4k)](https://github.com/yusufcanb/tlm) - Local cli copilot, powered by CodeLLaMa
*   [traefik (⭐53k)](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends.
*   [trubka (⭐331)](https://github.com/xitonix/trubka) - A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka.
*   [uTask (⭐1.2k)](https://github.com/ovh/utask) - Automation engine that models and executes business processes declared in yaml.
*   [Vegeta (⭐24k)](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
*   [wait-for (⭐17)](https://github.com/dnnrly/wait-for) - Wait for something to happen (from the command line) before continuing. Easy orchestration of Docker services and other things.
*   [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
*   [winrm-cli (⭐167)](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines.

**[⬆ back to top](#contents)**

### Other Software

*   [Better Go Playground](https://goplay.tools) - Go playground with syntax highlight, code completion and other features.
*   [blocky (⭐5k)](https://github.com/0xERR0R/blocky) - Fast and lightweight DNS proxy as ad-blocker for local network with many features.
*   [borg (⭐1.6k)](https://github.com/crufter/borg) - Terminal based search engine for bash snippets.
*   [boxed (⭐78)](https://github.com/tejo/boxed) - Dropbox based blog engine.
*   [Chapar (⭐539)](https://github.com/chapar-rest/chapar) - Chapar is a a cross-platform Postman alternative built with go, aims to help developers to test their api endpoints. it support http and grpc protocols.
*   [Cherry (⭐301)](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go.
*   [Circuit (⭐2k)](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
*   [Comcast (⭐10k)](https://github.com/tylertreat/Comcast) - Simulate bad network connections.
*   [confd (⭐8.4k)](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
*   [crawley (⭐277)](https://github.com/s0rg/crawley) - Web scraper/crawler for cli.
*   [croc (⭐29k)](https://github.com/schollz/croc) - Easily and securely send files or folders from one computer to another.
*   [Documize (⭐2.2k)](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools.
*   [dp (⭐81)](https://github.com/scryinfo/dp) - Through SDK for data exchange with blockchain, developers can get easy access to DAPP development.
*   [drive (⭐6.7k)](https://github.com/odeke-em/drive) - Google Drive client for the commandline.
*   [Duplicacy (⭐5.3k)](https://github.com/gilbertchen/duplicacy) - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication.
*   [fjira (⭐167)](https://github.com/mk-5/fjira) - A fuzzy-search based terminal UI application for Attlasian Jira
*   [Gebug (⭐636)](https://github.com/moshebe/gebug) - A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly.
*   [gfile (⭐748)](https://github.com/Antonito/gfile) - Securely transfer files between two computers, without any third party, over WebRTC.
*   [Go Package Store (⭐897)](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH.
*   [go-peerflix (⭐473)](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client.
*   [goblin](https://goblin.run) - Cloud builder for CLI's written in go lang
*   [GoBoy (⭐2.6k)](https://github.com/Humpheh/goboy) - Nintendo Game Boy Color emulator written in Go.
*   [gocc (⭐625)](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go.
*   [GoDocTooltip (⭐13)](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at function list.
*   [Gokapi (⭐1.8k)](https://github.com/Forceu/gokapi) - Lightweight server to share files, which expire after a set amount of downloads or days. Similar to Firefox Send, but without public upload.
*   [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
*   [GoNB (⭐783)](https://github.com/janpfeifer/gonb) - Interactive Go programming with Jupyter Notebooks (also works in VSCode, Binder and Google's Colab).
*   [Gor (⭐19k)](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
*   [Guora (⭐676)](https://github.com/meloalright/guora) - A self-hosted Quora like web application written in Go.
*   [hoofli (⭐9)](https://github.com/dnnrly/hoofli) - Generate PlantUML diagrams from Chrome or Firefox network inspections.
*   [hotswap (⭐378)](https://github.com/edwingeng/hotswap) - A complete solution to reload your go code without restarting your server, interrupting or blocking any ongoing procedure.
*   [hugo](https://gohugo.io/) - Fast and Modern Static Website Engine.
*   [ide (⭐360)](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go.
*   [joincap (⭐214)](https://github.com/assafmo/joincap) - Command-line utility for merging multiple pcap files together.
*   [JuiceFS (⭐11k)](https://github.com/juicedata/juicefs) - Distributed POSIX file system built on top of Redis and AWS S3.
*   [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
*   [Layli](https://layli.app) - Draw pretty layout diagrams as code.
*   [Leaps (⭐752)](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms.
*   [lgo (⭐2.4k)](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility.
*   [limetext](https://limetext.github.io) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
*   [LiteIDE (⭐7.6k)](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
*   [mockingjay (⭐562)](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
*   [myLG (⭐2.7k)](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.
*   [naclpipe (⭐23)](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go.
*   [Neo-cowsay (⭐321)](https://github.com/Code-Hex/Neo-cowsay) - 🐮 cowsay is reborn. for a New Era.
*   [nes (⭐5.5k)](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go.
*   [Orbit (⭐184)](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates.
*   [peg (⭐1k)](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
*   [Plik (⭐1.5k)](https://github.com/root-gg/plik) - Plik is a temporary file upload system (Wetransfer like) in Go.
*   [portal (⭐1.6k)](https://github.com/SpatiumPortae/portal) - Portal is a quick and easy command-line file transfer utility from any computer to another.
*   [restic (⭐28k)](https://github.com/restic/restic) - De-duplicating backup program.
*   [sake (⭐654)](https://github.com/alajmo/sake) - sake is a command runner for local and remote hosts.
*   [scc (⭐7.1k)](https://github.com/boyter/scc) - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates.
*   [Seaweed File System (⭐24k)](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
*   [shell2http (⭐1.4k)](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control).
*   [Snitch (⭐16)](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru.
*   [sonic (⭐2.1k)](https://github.com/go-sonic/sonic) - Sonic is a Go Blogging Platform. Simple and Powerful.
*   [Stack Up (⭐2.5k)](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
*   [stew (⭐215)](https://github.com/marwanhawari/stew) - An independent package manager for compiled binaries.
*   [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
*   [tcpdog (⭐255)](https://github.com/mehrdadrad/tcpdog) - eBPF based TCP observability.
*   [tinycare-tui (⭐12)](https://github.com/DMcP89/tinycare-tui) - Small terminal app that shows git commits from the last 24 hours and week, current weather, some self care advice, a joke, and you current todo list tasks.
*   [toxiproxy (⭐11k)](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.
*   [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
*   [vaku (⭐154)](https://github.com/lingrino/vaku) - CLI & API for folder-based functions in Vault like copy, move, and search.
*   [vFlow (⭐1.1k)](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
*   [Wave Terminal](https://waveterm.dev) - Wave is an open-source, AI-native terminal built for seamless developer workflows with inline rendering, a modern UI, and persistent sessions.
*   [wellington (⭐301)](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass).
*   [woke (⭐470)](https://github.com/get-woke/woke) - Detect non-inclusive language in your source code.
*   [yai (⭐750)](https://github.com/ekkinox/yai) - AI powered terminal assistant.
*   [zs](https://git.mills.io/prologic/zs) - an extremely minimal static site generator.

**[⬆ back to top](#contents)**

# Resources

*Where to discover new Go libraries.*

**[⬆ back to top](#contents)**

## Benchmarks

*   [autobench (⭐99)](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.
*   [go-benchmark-app (⭐27)](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
*   [go-benchmarks (⭐147)](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
*   [go-http-routing-benchmark (⭐1.7k)](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison.
*   [go-json-benchmark (⭐10)](https://github.com/zerosnake0/go-json-benchmark) - Go JSON benchmark.
*   [go-ml-benchmarks (⭐30)](https://github.com/nikolaydubina/go-ml-benchmarks) - benchmarks for machine learning inference in Go.
*   [go-web-framework-benchmark (⭐2.1k)](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark.
*   [go\_serialization\_benchmarks (⭐1.6k)](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods.
*   [gocostmodel (⭐61)](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language.
*   [golang-benchmarks (⭐134)](https://github.com/SimonWaldherr/golang-benchmarks) - a collection of golang benchmarks.
*   [golang-sql-benchmark (⭐65)](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
*   [gospeed (⭐123)](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.
*   [kvbench (⭐26)](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark.
*   [skynet (⭐1.1k)](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.
*   [speedtest-resize (⭐242)](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language.

**[⬆ back to top](#contents)**

## Conferences

*   [GoCon](https://gocon.connpass.com/) - Tokyo, Japan.
*   [GoDays](https://www.godays.io/) - Berlin, Germany.
*   [GoLab](https://golab.io/) - Florence, Italy.
*   [GopherChina](https://gopherchina.org) - Shanghai, China.
*   [GopherCon](https://www.gophercon.com/) - Varied Locations Each Year, USA.
*   [GopherCon Australia](https://gophercon.com.au/) - Sydney, Australia.
*   [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, Brazil.
*   [GopherCon Europe](https://gophercon.eu/) - Berlin, Germany.
*   [GopherCon India](https://gopherconindia.org/) - Pune, India.
*   [GopherCon Israel](https://www.gophercon.org.il/) - Tel Aviv, Israel.
*   [GopherCon Russia](https://www.gophercon-russia.ru) - Moscow, Russia.
*   [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore.
*   [GopherCon UK](https://www.gophercon.co.uk/) - London, UK.
*   [GopherCon Vietnam](https://gophercon.vn/) - Ho Chi Minh City, Vietnam.
*   [GoWest Conference](https://www.gowestconf.com/) - Lehi, USA.

**[⬆ back to top](#contents)**

## E-Books

### E-books for purchase

*   [100 Go Mistakes: How to Avoid Them](https://www.manning.com/books/100-go-mistakes-how-to-avoid-them)
*   [Black Hat Go](https://nostarch.com/blackhatgo) - Go programming for hackers and pentesters.
*   [Build an Orchestrator in Go](https://www.manning.com/books/build-an-orchestrator-in-go)
*   [Continuous Delivery in Go](https://www.manning.com/books/continuous-delivery-in-go) - This practical guide to continuous delivery shows you how to rapidly establish an automated pipeline that will improve your testing, code quality, and final product.
*   [Creative DIY Microcontroller Project With TinyGo and WebAssembly](https://www.packtpub.com/product/creative-diy-microcontroller-projects-with-tinygo-and-webassembly/9781800560208) - An introduction into the TinyGo compiler with projects involving Arduino and WebAssembly.
*   [Effective Go: Elegant, efficient, and testable code](https://www.manning.com/books/effective-go) - Unlock Go’s unique perspective on program design, and start writing simple, maintainable, and testable Go code.
*   [For the Love of Go](https://bitfieldconsulting.com/books/love) - An introductory book for Go beginners.
*   [Go in Practice, Second Edition](https://www.manning.com/books/go-in-practice-second-edition)  - Your practical guide on the ins-and-outs of Go development, covering the standard library and the most important tools from Go’s powerful ecosystem.
*   [Know Go: Generics](https://bitfieldconsulting.com/books/generics) - A guide to understanding and using generics in Go.
*   [Lets-Go](https://lets-go.alexedwards.net) - A step-by-step guide to creating fast, secure and maintanable web applications with Go.
*   [Lets-Go-Further](https://lets-go-further.alexedwards.net) - Advanced patterns for building APIs and web applications in Go.
*   [The Power of Go: Tests](https://bitfieldconsulting.com/books/tests) - A guide to testing in Go.
*   [The Power of Go: Tools](https://bitfieldconsulting.com/books/tools) - A guide to writing command-line tools in Go.
*   [Writing A Compiler In Go](https://compilerbook.com)
*   [Writing An Interpreter In Go](https://interpreterbook.com) - Book that introduces dozens of techniques for writing idiomatic, expressive, and efficient Go code that avoids common pitfalls.

### Free e-books

*   [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
*   [An Introduction to Programming in Go](http://www.golang-book.com/)
*   [Build a blockchain from scratch in Go with gRPC (⭐347)](https://github.com/volodymyrprokopyuk/go-blockchain) - The foundational and practical guide for effectively learning and progressively building a blockchain from scratch in Go with gRPC.
*   [Build Web Application with Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/content/en/)
*   [Building Web Apps With Go](https://codegangsta.gitbooks.io/building-web-apps-with-go/content/)
*   [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
*   [Go AST Book (Chinese) (⭐5.4k)](https://github.com/chai2010/go-ast-book) - A book focusing on Go `go/*` packages.
*   [Go Faster](https://leanpub.com/gofaster) - This book seeks to shorten your learning curve and help you become a proficient Go programmer, faster.
*   [Go Succinctly (⭐22)](https://github.com/thedevsir/gosuccinctly) - in Persian.
*   [Go with the domain](https://threedots.tech/go-with-the-domain/) - A book showing how to apply DDD, Clean Architecture, and CQRS by practical refactoring.
*   [GoBooks (⭐18k)](https://github.com/dariubs/GoBooks) - A curated list of Go books.
*   [How To Code in Go eBook](https://www.digitalocean.com/community/books/how-to-code-in-go-ebook) - A 600 page introduction to Go aimed at first time developers.
*   [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
*   [Network Programming With Go](https://jan.newmarch.name/golang/)
*   [Practical Go Lessons](https://www.practical-go-lessons.com/)
*   [Spaceship Go A Journey to the Standard Library](https://blasrodri.github.io/spaceship-go-gh-pages/)
*   [The Go Programming Language](https://www.gopl.io/)
*   [The Golang Standard Library by Example (Chinese) (⭐9.5k)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example)
*   [Web Application with Go the Anti-Textbook (⭐3.2k)](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)

**[⬆ back to top](#contents)**

## Gophers

*   [Free Gophers Pack (⭐3.7k)](https://github.com/MariaLetta/free-gophers-pack) - Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster.
*   [Go-gopher-Vector (⭐69)](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data \[.ai, .svg].
*   [gopher-logos (⭐126)](https://github.com/GolangUA/gopher-logos) - adorable gopher logos.
*   [gopher-stickers (⭐592)](https://github.com/tenntenn/gopher-stickers)
*   [gophericons (⭐620)](https://github.com/shalakhin/gophericons)
*   [gopherize.me (⭐720)](https://github.com/matryer/gopherize.me) - Gopherize yourself.
*   [gophers (⭐3k)](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara.
*   [gophers (⭐3.6k)](https://github.com/egonelbre/gophers) - Free gophers.
*   [gophers (⭐58)](https://github.com/rogeralsing/gophers) - random gopher graphics.
*   [gophers (⭐149)](https://github.com/sillecelik/go-gopher) - Gopher amigurumi toy pattern.
*   [gophers (⭐34)](https://github.com/scraly/gophers) - Gophers by Aurélie Vache.

**[⬆ back to top](#contents)**

## Meetups

*   [Basel Go Meetup](https://www.meetup.com/Basel-Go-Meetup/)
*   [Belfast Gophers](https://www.meetup.com/Belfast-Gophers/)
*   [Belgrade Golang Meetup](https://www.meetup.com/golang-serbia/)
*   [Berlin Golang](https://www.meetup.com/golang-users-berlin/)
*   [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
*   [Bärner Go Meetup - Berne, Switzerland](https://www.meetup.com/berner-go-meetup/)
*   [Go Ireland - Dublin](https://www.meetup.com/goireland/)
*   [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
*   [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
*   [Go Remote Meetup](https://www.meetup.com/Go-Remote-Meetup/)
*   [Go Toronto](https://www.meetup.com/go-toronto/)
*   [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
*   [GoBandung](https://www.meetup.com/GoBandung/)
*   [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
*   [GoCracow - Krakow, Poland](https://www.meetup.com/GoCracow/)
*   [GoJakarta](https://www.meetup.com/GoJakarta/)
*   [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
*   [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
*   [Golang Athens](https://www.meetup.com/Athens-Gophers/)
*   [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
*   [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
*   [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
*   [Golang Boston](https://www.meetup.com/bostongo/)
*   [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
*   [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
*   [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
*   [Golang Curitiba - Brazil](https://www.meetup.com/GolangCWB/)
*   [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
*   [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
*   [Golang Estonia](https://www.meetup.com/Golang-Estonia/)
*   [Golang Gurgaon, India](https://www.meetup.com/Gurgaon-Go-Meetup/)
*   [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
*   [Golang Israel](https://www.meetup.com/Go-Israel/)
*   [Golang Kathmandu](https://www.meetup.com/Golang-Kathmandu/)
*   [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
*   [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
*   [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
*   [Golang Melbourne](https://www.meetup.com/golang-mel/)
*   [Golang Milano](https://www.meetup.com/golang-milano/)
*   [Golang North East](https://www.meetup.com/en-AU/Golang-North-East/)
*   [Golang Paris](https://www.meetup.com/Golang-Paris/)
*   [Golang Poland](https://www.meetup.com/Golang-Poland/)
*   [Golang Pune](https://www.meetup.com/Golang-Pune/)
*   [Golang Roma](https://www.meetup.com/golangroma/)
*   [Golang Rotterdam](https://www.meetup.com/golang-rotterdam/)
*   [Golang Singapore](https://www.meetup.com/golangsg/)
*   [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
*   [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
*   [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
*   [Golang Taipei](https://www.meetup.com/golang-taipei-meetup/)
*   [Golang Thessaloniki](https://www.meetup.com/thessaloniki-golang-meetup/)
*   [Golang Torino](https://www.meetup.com/golang-torino/)
*   [Golang Turkey](https://kommunity.com/goturkiye)
*   [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
*   [Golang Vienna, Austria](https://www.meetup.com/viennago/)
*   [Golang Москва](https://www.meetup.com/Golang-Moscow/)
*   [GoSF - San Francisco, CA](https://www.meetup.com/golangsf)
*   [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
*   [Lagos Gophers](https://www.meetup.com/GolangNigeria/)
*   [Nairobi Gophers](https://www.meetup.com/nairobi-gophers/)
*   [Seattle Go Programmers](https://www.meetup.com/golang/)
*   [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
*   [Utah Go User Group](https://www.meetup.com/utahgophers/)
*   [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)
*   [Zürich Gophers - Zurich, Switzerland](https://www.meetup.com/zurich-gophers/)

*Add the group of your city/country here (send **PR**)*

**[⬆ back to top](#contents)**

## Style Guides

*   [bahlo/go-styleguide (⭐1.5k)](https://github.com/bahlo/go-styleguide)
*   [CockroachDB (⭐31k)](https://github.com/cockroachdb/cockroach/blob/master/docs/style.md)
*   [GitLab](https://docs.gitlab.com/ee/development/go_guide/)
*   [Google](https://google.github.io/styleguide/go/)
*   [Hyperledger (⭐16k)](https://github.com/hyperledger/fabric/blob/release-1.4/docs/source/style-guides/go-style.rst)
*   [Magnetico (⭐3.1k)](https://github.com/boramalper/magnetico/wiki/magnetico-Design-Specification)
*   [Thanos](https://thanos.io/tip/contributing/coding-style-guide.md/)
*   [Trybe (⭐310)](https://github.com/betrybe/playbook-go/blob/main/README_EN.md)
*   [Uber (⭐16k)](https://github.com/uber-go/guide/blob/master/style.md)

**[⬆ back to top](#contents)**

## Social Media

### Twitter

*   [@GoDiscussions](https://twitter.com/GoDiscussions)
*   [@golang](https://twitter.com/golang)
*   [@golang\_news](https://twitter.com/golang_news)
*   [@golangch](https://twitter.com/golangch)
*   [@golangweekly](https://twitter.com/golangweekly)

**[⬆ back to top](#contents)**

### Reddit

*   [r/golang](https://www.reddit.com/r/golang/)

**[⬆ back to top](#contents)**

## Websites

*   [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
*   [Awesome Golang Workshops (⭐516)](https://github.com/amit-davidson/awesome-golang-workshops) - A curated list of awesome golang workshops.
*   [Awesome Remote Job (⭐37k)](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.
*   [awesome-awesomeness (⭐32k)](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists.
*   [awesome-go-extra (⭐24)](https://github.com/xwjdsh/awesome-go-extra) - Parse awesome-go README file and generate a new README file with repo info.
*   [Code with Mukesh](https://codewithmukesh.com/categories/golang) - Software Engineer and Blogs @ codewithmukesh.com.
*   [Coding Mystery](https://codingmystery.com) - Solve exciting escape-room-inspired programming challenges using Go.
*   [CodinGame](https://www.codingame.com/) - Learn Go by solving interactive tasks using small games as practical examples.
*   [Go Blog](https://blog.golang.org) - The official Go blog.
*   [Go Code Club](https://www.youtube.com/watch?v=nvoIPQYdx9g\&list=PLEcwzBXTPUE_YQR7R0BRtHBYJ0LN3Y0i3) - A group of Gophers read and discuss a different Go project every week.
*   [Go Community on Hashnode](https://hashnode.com/n/go) - Community of Gophers on Hashnode.
*   [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
*   [Go Projects (⭐126k)](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
*   [Go Proverbs](https://go-proverbs.github.io/) - Go Proverbs by Rob Pike.
*   [Go Report Card](https://goreportcard.com) - A report card for your Go package.
*   [go.dev](https://go.dev/) - A hub for Go developers.
*   [gocryforhelp (⭐41)](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go.
*   [Golang Developer Jobs](https://golangjob.xyz) - Developer Jobs exclusively for Golang related Roles.
*   [Golang News](https://golangnews.com) - Links and news about Go programming.
*   [Golang Nugget](https://golangnugget.com) - A weekly roundup of the best Go content, delivered to your inbox every Monday.
*   [Golang Weekly](https://discu.eu/weekly/golang/) - Each monday projects, tutorials and articles about Go.
*   [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
*   [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
*   [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
*   [Gophercises](https://gophercises.com/) - Free coding exercises for budding gophers.
*   [json2go](https://m-zajac.github.io/json2go) - Advanced JSON to Go struct conversion - online tool.
*   [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by Francesc Campoy [@francesc](https://twitter.com/francesc).
*   [Learn Go Programming](https://blog.learngoprogramming.com) - Learn Go concepts with illustrations.
*   [Made with Golang](https://madewithgolang.com/?ref=awesome-go)
*   [pkg.go.dev](https://pkg.go.dev/) - Documentation for open source Go packages.
*   [studygolang](https://studygolang.com) - The community of studygolang in China.
*   [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.
*   [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

**[⬆ back to top](#contents)**

### Tutorials

*   [50 Shades of Go](https://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
*   [A Comprehensive Guide to Structured Logging in Go](https://betterstack.com/community/guides/logging/logging-in-go/) - Delve deep into the world of structured logging in Go with a specific focus on recently accepted slog proposal which aims to bring high performance structured logging with levels to the standard library.
*   [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - Building a Golang site for e-commerce (demo included).
*   [A Tour of Go](https://tour.golang.org/) - Interactive tour of Go.
*   [Build a Database in 1000 lines of code](https://link.medium.com/O9YQlx89Htb) - Build a NoSQL Database From Zero in 1000 Lines of Code.
*   [Build web application with Golang (⭐43k)](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.
*   [Building and Testing a REST API in Go with Gorilla Mux and PostgreSQL](https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql) - We’ll write an API with the help of the powerful Gorilla Mux.
*   [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
*   [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - How to cache slow database queries.
*   [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
*   [CodeCrafters Golang Track](https://app.codecrafters.io/tracks/go) - Achieve mastery in advanced Go by building your own Redis, Docker, Git, and SQLite. Featuring goroutines, systems programming, file I/O, and more.
*   [Design Patterns in Go (⭐122)](https://github.com/shubhamzanwar/design-patterns) - Collection of programming design patterns implemented in Go.
*   [Games With Go](https://www.youtube.com/watch?v=9D4yH7e_ea8\&list=PLDZujg-VgQlZUy1iCqBbe5faZLMkA3g2x) - A video series teaching programming and game development.
*   [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
*   [Go Cheat Sheet (⭐8.5k)](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.
*   [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
*   [Go in 7 days (⭐144)](https://github.com/harrytran103/7_days_of_go) - Learn everything about Go in 7 days (from a Nodejs developer).
*   [Go Language Tutorial](https://www.javatpoint.com/go-tutorial) - Learn Go language Tutorial.
*   [Go Tutorial](https://www.tutorialspoint.com/go/index.htm) - Learn Go programming.
*   [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
*   [go-clean-template (⭐6.4k)](https://github.com/evrone/go-clean-template) - Clean Architecture template for Golang services.
*   [go-patterns (⭐26k)](https://github.com/tmrts/go-patterns) - Curated list of Go design patterns, recipes and idioms.
*   [goapp (⭐940)](https://github.com/naughtygopher/goapp) - An opinionated guideline to structure & develop a Go web application/service.
*   [Golang for Node.js Developers (⭐4.7k)](https://github.com/miguelmota/golang-for-nodejs-developers) - Examples of Golang compared to Node.js for learning.
*   [Golang Tutorial Guide](https://www.freecodecamp.org/news/golang-tutorial-list-free-courses-learn-go-programming-language/) - A List of Free Courses to Learn the Go Programming Language.
*   [golang-examples (⭐1.6k)](https://github.com/SimonWaldherr/golang-examples) - Many examples to learn Golang.
*   [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
*   [GopherCoding](https://gophercoding.com/) - Collection of code snippets and tutorials to help tackle every day issues.
*   [GopherSnippets](https://gophersnippets.com/) - Code snippets with tests and testable examples for the Go programming language.
*   [Gosamples](https://gosamples.dev/) - Collection of code snippets that let you solve everyday code problems.
*   [GraphQL with Go](https://hasura.io/learn/graphql/backend-stack/languages/go/) - Learn how to create a Go GraphQL server and client with code generation. Also includes creating REST endpoints.
*   [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
*   [Hex Monscape (⭐75)](https://github.com/Haraj-backend/hex-monscape) - Getting started guidelines in writing maintainable code using Hexagonal Architecture.
*   [How to Benchmark: dbq vs sqlx vs GORM](https://medium.com/@rocketlaunchr.cloud/how-to-benchmark-dbq-vs-sqlx-vs-gorm-e814caacecb5) - Learn how to benchmark in Go. As a case-study, we will benchmark dbq, sqlx and GORM.
*   [How To Deploy a Go Web Application with Docker](https://semaphoreci.com/community/tutorials/how-to-deploy-a-go-web-application-with-docker) - Learn how to use Docker for Go development and how to build production Docker images.
*   [How to Implement Role-Based Access Control (RBAC) Authorization in Golang](https://www.permit.io/blog/role-based-access-control-rbac-authorization-in-golang) - A guide to implementing Role-Based Access Control (RBAC) in Golang, including code examples, covering various methods to secure app endpoints with role-based authorization.
*   [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
*   [Learn Go with 1000+ Exercises (⭐19k)](https://github.com/inancgumus/learngo) - Learn Go with thousands of examples, exercises, and quizzes.
*   [Learn Go with TDD (⭐23k)](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development.
*   [Learning Go by examples](https://dev.to/aurelievache/learning-go-by-examples-introduction-448n) - Series of articles in order to learn Golang language by concrete applications as example.
*   [Microservices with Go](https://www.youtube.com/playlist?list=PLmD8u-IFdreyh6EUfevBcbiuCKzFk0EW_) - Dive deep into building microservices using Go, including gRPC.
*   [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
*   [Programming with Google Go](https://www.coursera.org/specializations/google-golang) - Coursera Specialization to learn about Go from scratch.
*   [Scaling Go Applications](https://betterstack.com/community/guides/scaling-go/) - Everything about building, deploying and scaling Go applications in production.
*   [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
*   [Understanding Go in a visual way](https://dev.to/aurelievache/series/26234) - Learn Go visually
*   [W3basic Go Tutorials](https://www.w3basic.com/golang/) - W3Basic provides an in-depth tutorial and well-organized content to learn Golang programming.
*   [Your basic Go](https://yourbasic.org/golang) - Huge collection of tutorials and how to's.

**[⬆ back to top](#contents)**

### Guided Learning

*   [The Go Developer Roadmap](https://roadmap.sh/golang) - A visual roadmap that new Go developers can follow through to help them learn Go.
*   [The Go Learning Path](https://tutorialedge.net/paths/golang/) - A guided learning path containing a mix of free and premium resources.
*   [The Go Skill Tree](https://labex.io/skilltrees/go) - A structured learning path that combines both free and premium resources.

**[⬆ back to top](#contents)**

