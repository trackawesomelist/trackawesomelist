# Awesome Rust Overview

A curated list of Rust code and resources.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/rust-unofficial/awesome-rust/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 rust-unofficial/awesome-rust](https://github.com/rust-unofficial/awesome-rust) · ⭐ 32K · 🏷️ Programming Languages

[ [Daily](/content/rust-unofficial/awesome-rust/README.md) / [Weekly](/content/rust-unofficial/awesome-rust/week/README.md) / Overview ]

---

# Awesome Rust [![build badge](https://github.com/rust-unofficial/awesome-rust/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/rust-unofficial/awesome-rust/actions/workflows/rust.yml) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/rust-unofficial/awesome-rust/)

A curated list of Rust code and resources.

If you want to contribute, please read [this](https://github.com/rust-unofficial/awesome-rust/blob/main/README.md/CONTRIBUTING.md).

## Table of contents

<!-- toc -->

*   [Applications](#applications)
    *   [Audio and Music](#audio-and-music)
    *   [Cryptocurrencies](#cryptocurrencies)
    *   [Database](#database)
    *   [Emulators](#emulators)
    *   [Games](#games)
    *   [Graphics](#graphics)
    *   [Image processing](#image-processing)
    *   [Industrial automation](#industrial-automation)
    *   [Observability](#observability)
    *   [Operating systems](#operating-systems)
    *   [Productivity](#productivity)
    *   [Security tools](#security-tools)
    *   [Simulation](#simulation)
    *   [Social networks](#social-networks)
    *   [System tools](#system-tools)
    *   [Task scheduling](#task-scheduling)
    *   [Text editors](#text-editors)
    *   [Text processing](#text-processing)
    *   [Utilities](#utilities)
    *   [Video](#video)
    *   [Virtualization](#virtualization)
    *   [Web](#web)
    *   [Web Servers](#web-servers)
*   [Development tools](#development-tools)
    *   [Build system](#build-system)
    *   [Debugging](#debugging)
    *   [Deployment](#deployment)
    *   [Embedded](#embedded)
    *   [FFI](#ffi)
    *   [Formatters](#formatters)
    *   [IDEs](#ides)
    *   [Profiling](#profiling)
    *   [Services](#services)
    *   [Static analysis](#static-analysis)
    *   [Testing](#testing)
    *   [Transpiling](#transpiling)
*   [Libraries](#libraries)
    *   [Artificial Intelligence](#artificial-intelligence)
        *   [Genetic algorithms](#genetic-algorithms)
        *   [Machine learning](#machine-learning)
    *   [Astronomy](#astronomy)
    *   [Asynchronous](#asynchronous)
    *   [Audio and Music](#audio-and-music-1)
    *   [Authentication](#authentication)
    *   [Automotive](#automotive)
    *   [Bioinformatics](#bioinformatics)
    *   [Caching](#caching)
    *   [Cloud](#cloud)
    *   [Command-line](#command-line)
    *   [Compression](#compression)
    *   [Computation](#computation)
    *   [Concurrency](#concurrency)
    *   [Configuration](#configuration)
    *   [Cryptography](#cryptography)
    *   [Data processing](#data-processing)
    *   [Data streaming](#data-streaming)
    *   [Data structures](#data-structures)
    *   [Data visualization](#data-visualization)
    *   [Database](#database-1)
    *   [Date and time](#date-and-time)
    *   [Distributed systems](#distributed-systems)
    *   [Domain driven design](#domain-driven-design)
    *   [Email](#email)
    *   [Encoding](#encoding)
    *   [Filesystem](#filesystem)
    *   [Functional Programming](#functional-programming)
    *   [Game development](#game-development)
    *   [Geospatial](#geospatial)
    *   [Graph algorithms](#graph-algorithms)
    *   [Graphics](#graphics-1)
    *   [GUI](#gui)
    *   [Image processing](#image-processing-1)
    *   [Language specification](#language-specification)
    *   [Logging](#logging)
    *   [Macro](#macro)
    *   [Markup language](#markup-language)
    *   [Mobile](#mobile)
    *   [Network programming](#network-programming)
    *   [Parsing](#parsing)
    *   [Peripherals](#peripherals)
    *   [Platform specific](#platform-specific)
    *   [Scripting](#scripting)
    *   [Simulation](#simulation-1)
    *   [System](#system)
    *   [Task scheduling](#task-scheduling-1)
    *   [Template engine](#template-engine)
    *   [Text processing](#text-processing-1)
    *   [Text search](#text-search)
    *   [Unsafe](#unsafe)
    *   [Virtualization](#virtualization-1)
    *   [Web programming](#web-programming)
*   [Registries](#registries)
*   [Resources](#resources)
*   [License](#license)

<!-- tocstop -->

## Applications

See also [Rust — Production](https://www.rust-lang.org/production) organizations running Rust in production.

*   [alacritty (⭐44k)](https://github.com/alacritty/alacritty) — A cross-platform, GPU enhanced terminal emulator
*   [Arti](https://gitlab.torproject.org/tpo/core/arti) — An implementation of Tor, in Rust. (So far, it's a not-very-complete client. But watch this space!) [![Crates.io](https://img.shields.io/crates/v/arti.svg)](https://crates.io/crates/arti)
*   [asm-cli-rust (⭐243)](https://github.com/cch123/asm-cli-rust) — An interactive assembly shell written in rust.
*   [cloudflare/boringtun (⭐4.8k)](https://github.com/cloudflare/boringtun) — A Userspace WireGuard VPN Implementation [![build badge](https://img.shields.io/badge/crates.io-v0.2.0-orange.svg)](https://crates.io/crates/boringtun)
*   [datafusion (⭐3.1k)](https://github.com/apache/arrow-datafusion) — Apache Arrow DataFusion and Ballista query engines
*   [denoland/deno (⭐88k)](https://github.com/denoland/deno) — A secure JavaScript/TypeScript runtime built with V8, Rust, and Tokio [![Build Status](https://github.com/denoland/deno/workflows/ci/badge.svg?branch=master\&event=push)](https://github.com/denoland/deno/actions)
*   [Factotum (⭐197)](https://github.com/snowplow/factotum) — [A system to programmatically run data pipelines](https://snowplow.io/blog/introducing-factotum-data-pipeline-runner/) [![build badge](https://api.travis-ci.org/snowplow/factotum.svg?branch=master)](https://travis-ci.org/snowplow/factotum)
*   [fcsonline/drill (⭐1.5k)](https://github.com/fcsonline/drill) — A HTTP load testing application inspired by Ansible syntax [![build badge](https://api.travis-ci.org/fcsonline/drill.svg?branch=master)](https://travis-ci.org/fcsonline/drill)
*   [fend (⭐152)](https://github.com/printfn/fend) - Arbitrary-precision unit-aware calculator [![build](https://github.com/printfn/fend/workflows/build/badge.svg)](https://github.com/printfn/fend)
*   [Fractalide (⭐793)](https://github.com/fractalide/fractalide) — Simple Rust Microservices
*   [habitat (⭐2.4k)](https://github.com/habitat-sh/habitat) — A tool created by Chef to build, deploy, and manage applications.
*   [Herd (⭐100)](https://github.com/imjacobclark/Herd) — an experimental HTTP load testing application
*   [jedisct1/flowgger (⭐742)](https://github.com/awslabs/flowgger) — A fast, simple and lightweight data collector
*   [kalker (⭐1.2k)](https://github.com/PaddiM8/kalker) - A scientific calculator that supports math-like syntax with user-defined variables, functions, derivation, integration, and complex numbers. Cross platform + WASM support [![Build Status](https://github.com/PaddiM8/kalker/workflows/Release/badge.svg)](https://github.com/PaddiM8/kalker/actions)
*   [kytan (⭐371)](https://github.com/changlan/kytan) — High Performance Peer-to-Peer VPN
*   [linkerd/linkerd2-proxy (⭐1.7k)](https://github.com/linkerd/linkerd2-proxy) — Ultralight service mesh for Kubernetes.
*   [MaidSafe](https://github.com/maidsafe) — A decentralized platform.
*   [mdBook](https://crates.io/crates/mdbook) — A command line utility to create books from markdown files [![Build Status](https://github.com/rust-lang/mdBook/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/mdBook/actions)
*   [nicohman/eidolon (⭐114)](https://github.com/nicohman/eidolon) — A steam and drm-free game registry and launcher for linux and macosx [![build badge](https://api.travis-ci.org/nicohman/eidolon.svg?branch=master)](https://travis-ci.org/nicohman/eidolon)
*   [notty (⭐2.2k)](https://github.com/withoutboats/notty) — A new kind of terminal
*   [Pijul](https://pijul.org) — A patch-based distributed version control system
*   [rx (⭐2.6k)](https://github.com/cloudhead/rx) — Vi inspired Modern Pixel Art Editor
*   [Servo (⭐22k)](https://github.com/servo/servo) — A prototype web browser engine
*   [shuttle (⭐1.7k)](https://github.com/shuttle-hq/shuttle) — A serverless platform built for Rust
*   [Sniffnet (⭐2.8k)](https://github.com/GyulyVGC/sniffnet) — Cross-platform application to monitor your network traffic with ease [![build badge](https://img.shields.io/github/actions/workflow/status/gyulyvgc/sniffnet/rust.yml?logo=github)](https://github.com/GyulyVGC/sniffnet/blob/main/.github/workflows/rust.yml) [![crate](https://img.shields.io/crates/v/sniffnet?logo=rust)](https://crates.io/crates/sniffnet)
*   [SWC (⭐26k)](https://github.com/swc-project/swc) — super-fast TypeScript / JavaScript compiler
*   [tiny (⭐819)](https://github.com/osa1/tiny) — A terminal IRC client
*   [trust-dns](https://crates.io/crates/trust-dns) — A DNS-server [![Build Status](https://github.com/bluejekyll/trust-dns/workflows/test/badge.svg?branch=main)](https://github.com/bluejekyll/trust-dns/actions?query=workflow%3Atest)
*   [wasmer (⭐14k)](https://github.com/wasmerio/wasmer) — A safe and fast WebAssembly runtime supporting WASI and Emscripten [![Build Status](https://github.com/wasmerio/wasmer/workflows/build/badge.svg?style=flat-square)](https://github.com/wasmerio/wasmer/actions)
*   [Weld (⭐246)](https://github.com/serayuzgur/weld) — Full fake REST API generator [![build badge](https://api.travis-ci.org/serayuzgur/weld.svg?branch=master)](https://travis-ci.org/serayuzgur/weld)
*   [wezterm (⭐7k)](https://github.com/wez/wezterm) — A GPU-accelerated cross-platform terminal emulator and multiplexer
*   [zellij (⭐9.7k)](https://github.com/zellij-org/zellij) — A terminal multiplexer (workspace) with batteries included

### Audio and Music

*   [enginesound (⭐203)](https://github.com/DasEtwas/enginesound) — A GUI and command line application used to procedurally generate semi-realistic engine sounds. Featuring in-depth configuration, variable sample rate and a frequency analysis window.
*   [Glicol (⭐1.2k)](https://github.com/chaosprint/glicol) — Graph-oriented live coding language written in Rust for collaborative musicking in browsers.
*   [ncspot (⭐3.5k)](https://github.com/hrkfdn/ncspot) - Cross-platform ncurses Spotify client, inspired by ncmpc and the likes. [![build badge](https://github.com/hrkfdn/ncspot/workflows/Build/badge.svg)](https://github.com/hrkfdn/ncspot/actions?query=workflow%3ABuild)
*   [Polaris (⭐1k)](https://github.com/agersant/polaris) — A music streaming application.  [![build badge](https://api.travis-ci.org/agersant/polaris.svg?branch=master)](https://travis-ci.org/agersant/polaris)
*   [Spotify TUI (⭐14k)](https://github.com/Rigellute/spotify-tui) — A Spotify client for the terminal written in Rust. ![Continuous Integration](https://github.com/Rigellute/spotify-tui/workflows/Continuous%20Integration/badge.svg?branch=master)
*   [Spotifyd (⭐8.6k)](https://github.com/Spotifyd/spotifyd) — An open source Spotify client running as a UNIX daemon. ![Continuous Integration](https://github.com/Spotifyd/spotifyd/workflows/Continuous%20Integration/badge.svg?branch=master)
*   [WhatBPM (⭐74)](https://github.com/sergree/whatbpm) — A daily statically generated information resource for electronic dance music producers. Provides daily analytics on the most frequently used values for each EDM genre: tempos, keys, root notes, and so on, using publicly available data such as Beatport and Spotify. ![Continuous Integration](https://github.com/sergree/whatbpm/actions/workflows/website_build_deploy.yml/badge.svg?branch=main)

### Cryptocurrencies

*   [Akula (⭐794)](https://github.com/akula-bft/akula) - Rust Ethereum Execution Layer (EL) Client (WIP)
*   [beerus (⭐75)](https://github.com/keep-starknet-strange/beerus) - Beerus is a trustless StarkNet Light Client, ⚡blazing fast ⚡ and powered by Rust 🦀 [![GitHub Workflow Status](https://github.com/keep-starknet-strange/beerus/actions/workflows/test.yml/badge.svg)](https://github.com/keep-starknet-strange/beerus/actions/workflows/test.yml)
*   [Bitcoin Satoshi's Vision (⭐54)](https://github.com/brentongunning/rust-sv) \[[sv](https://crates.io/crates/sv)] — A Rust library for working with Bitcoin SV .
*   [cairo (⭐562)](https://github.com/starkware-libs/cairo) - Cairo is the first Turing-complete language for creating provable programs for general computation. This is also the native language of [StarkNet](https://starknet.io), a ZK-Rollup using STARK proofs ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/starkware-libs/cairo/CI?style=flat-square\&logo=github)
*   [cairo-rs (⭐271)](https://github.com/lambdaclass/cairo-rs) — Rust implementation of the Cairo VM [![rust](https://github.com/lambdaclass/cairo-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/lambdaclass/cairo-rs/actions/workflows/rust.yml)
*   [ChainX (⭐262)](https://github.com/chainx-org/ChainX) — Fully Decentralized Interchain Crypto Asset Management on Polkadot.
*   [CITA (⭐1.3k)](https://github.com/citahub/cita) — A high performance blockchain kernel for enterprise users.
*   [coinbase-pro-rs (⭐126)](https://github.com/inv2004/coinbase-pro-rs) — Coinbase pro client in Rust, supports sync/async/websocket [![build badge](https://api.travis-ci.org/inv2004/coinbase-pro-rs.svg?branch=master)](https://travis-ci.org/inv2004/coinbase-pro-rs)
*   [Diem (⭐17k)](https://github.com/diem/diem) — Diem’s mission is to enable a simple global currency and financial infrastructure that empowers billions of people.
*   [electrumrs (⭐712)](https://github.com/romanz/electrs) — An efficient re-implementation of Electrum Server in Rust.
*   [ethabi (⭐386)](https://github.com/rust-ethereum/ethabi) - Encode and decode smart contract invocations.
*   [ethaddrgen (⭐154)](https://github.com/Limeth/ethaddrgen) — Custom Ethereum vanity address generator made in Rust [![build badge](https://api.travis-ci.org/Limeth/ethaddrgen.svg?branch=master)](https://travis-ci.org/Limeth/ethaddrgen)
*   [ethers-rs (⭐1.5k)](https://github.com/gakonst/ethers-rs) - Complete Ethereum & Celo library and wallet implementation in Rust. ![Build Status](https://github.com/gakonst/ethers-rs/workflows/Tests/badge.svg)
*   [etk (⭐257)](https://github.com/quilt/etk) - etk is a collection of tools for writing, reading, and analyzing EVM bytecode.
*   [Forest (⭐515)](https://github.com/ChainSafe/forest) - Rust Filecoin implementation [![Build Status](https://img.shields.io/circleci/build/gh/ChainSafe/forest/main?branch=master)](https://app.circleci.com/pipelines/github/ChainSafe/forest?branch=main)
*   [Foundry (⭐5.3k)](https://github.com/foundry-rs/foundry) - Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust. ![Build Status](https://img.shields.io/github/workflow/status/foundry-rs/foundry/test?style=flat-square)
*   [Grin (⭐5k)](https://github.com/mimblewimble/grin/) — Evolution of the MimbleWimble protocol
*   [hdwallet (⭐23)](https://github.com/jjyr/hdwallet) \[[hdwallet](https://crates.io/crates/hdwallet)] — BIP-32 HD wallet related key derivation utilities.
*   [Holochain (⭐748)](https://github.com/holochain/holochain) — Scalable P2P alternative to blockchain for all those distributed apps you always wanted to build. [![detect critical check failures](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml/badge.svg)](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml)
*   [ibc-rs (⭐311)](https://github.com/informalsystems/hermes) - Rust implementation of the [Interblockchain Communication](https://ibc.cosmos.network/) protocol
*   [infincia/bip39-rs (⭐49)](https://github.com/infincia/bip39-rs) \[[bip39](https://crates.io/crates/bip39)] — Rust implementation of BIP39.
*   [interBTC (⭐195)](https://github.com/interlay/interbtc) — Trustless and fully decentralized Bitcoin bridge to Polkadot and Kusama.
*   [Joystream (⭐165)](https://github.com/Joystream/joystream) — A user governed video platform [![Build Status](https://api.travis-ci.org/Joystream/joystream.svg?branch=master)](https://travis-ci.org/Joystream/joystream)
*   [Lighthouse (⭐2.2k)](https://github.com/sigp/lighthouse) — Rust Ethereum Consensus Layer (CL) Client [![Build Status](https://github.com/sigp/lighthouse/workflows/test-suite/badge.svg?branch=master)](https://github.com/sigp/lighthouse/actions)
*   [mev-inspect-rs (⭐436)](https://github.com/flashbots/mev-inspect-rs) - Ethereum MEV Inspector in Rust
*   [near/nearcore (⭐2k)](https://github.com/near/nearcore) — decentralized smart-contract platform for low-end mobile devices.
*   [Nervos CKB (⭐1k)](https://github.com/nervosnetwork/ckb) — Nervos CKB is a public permissionless blockchain, the common knowledge layer of Nervos network.
*   [Nimiq (⭐72)](https://github.com/nimiq/core-rs) — Rust implementation of Nimiq node
*   [opensea-rs (⭐227)](https://github.com/gakonst/opensea-rs) - Rust bindings & CLI to the Opensea API and Contracts.
*   [Parity-Bitcoin (⭐714)](https://github.com/paritytech/parity-bitcoin) — The Parity Bitcoin client [![build badge](https://api.travis-ci.org/paritytech/parity-bitcoin.svg?branch=master)](https://app.travis-ci.com/github/paritytech/parity-bitcoin)
*   [Phala-Network/phala-blockchain (⭐315)](https://github.com/Phala-Network/phala-blockchain) — Confidential smart contract blockchain based on Intel SGX and Substrate
*   [Polkadot (⭐6.5k)](https://github.com/paritytech/polkadot) — Heterogeneous multi‑chain technology with pooled security
*   [revm (⭐544)](https://github.com/bluealloy/revm) - Revolutionary Machine (revm) is a fast Ethereum virtual machine written in rust.
*   [rust-bitcoin (⭐1.3k)](https://github.com/rust-bitcoin/rust-bitcoin) — Library with support for de/serialization, parsing and executing on data structures and network messages related to Bitcoin.
*   [rust-lightning (⭐874)](https://github.com/lightningdevkit/rust-lightning) [![Crate](https://img.shields.io/crates/v/lightning.svg?logo=rust)](https://crates.io/crates/lightning) — Bitcoin Lightning library written in Rust. The main crate,`lightning`, does not handle networking, persistence, or any other I/O. Thus,it is runtime-agnostic, but users must implement basic networking logic, chain interactions, and disk storage.po on linking crate.
*   [sigma-rust (⭐54)](https://github.com/ergoplatform/sigma-rust) — Rust implementation of ErgoTree interpreter and wallet-related features.
*   [Solana (⭐10k)](https://github.com/solana-labs/solana) — Incredibly fast, highly scalable blockchain using Proof-of-History.
*   [Substrate (⭐7.9k)](https://github.com/paritytech/substrate) — Generic modular blockchain template written in Rust
*   [svm-rs (⭐117)](https://github.com/roynalnaruto/svm-rs) - Solidity-Compiler Version Manager.
*   [tendermint-rs (⭐456)](https://github.com/informalsystems/tendermint-rs) - Rust implementation of Tendermint blockchain data structures and clients
*   [wagyu (⭐554)](https://github.com/AleoHQ/wagyu) \[[wagyu](https://crates.io/crates/wagyu)] — Rust library for generating cryptocurrency wallets [![build badge](https://api.travis-ci.com/AleoHQ/wagyu.svg?branch=master)](https://api.travis-ci.com/AleoHQ/wagyu.svg?branch=master)
*   [zcash (⭐4.7k)](https://github.com/zcash/zcash) — Zcash is an implementation of the "Zerocash" protocol.

### Database

*   [Atomic-Server (⭐246)](https://github.com/atomicdata-dev/atomic-data-rust/) \[[atomic-server](https://crates.io/crates/atomic_server)] - NoSQL graph database with realtime updates, dynamic indexing and easy-to-use GUI for CMS purposes. [![Release](https://github.com/atomicdata-dev/atomic-data-rust/actions/workflows/docker.yml/badge.svg)](https://github.com/atomicdata-dev/atomic-data-rust/actions/workflows/docker.yml)
*   [CozoDB (⭐2k)](https://github.com/cozodb/cozo) - A transactional, relational database that uses Datalog and focuses on graph data and algorithms. Time-travel-capable, and fast! [![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/cozodb/cozo/build.yml?branch=main)](https://github.com/cozodb/cozo/actions/workflows/build.yml)
*   [Databend (⭐5.2k)](https://github.com/datafuselabs/databend) - A Modern Real-Time Data Processing & Analytics DBMS with Cloud-Native Architecture [![Release](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml/badge.svg)](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml)
*   [DB3 Network (⭐111)](https://github.com/dbpunk-labs/db3) — DB3 is a community-driven blockchain layer2 decentralized database network ![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/dbpunk-labs/db3/ci.yml?branch=main\&style=flat-square)
*   [indradb](https://crates.io/crates/indradb) — Rust based graph database [![build badge](https://api.travis-ci.org/indradb/indradb.svg?branch=master)](https://travis-ci.org/indradb/indradb)
*   [Lucid (⭐310)](https://github.com/lucid-kv/lucid) — High performance and distributed KV store accessible through a HTTP API. [![Build Status](https://github.com/lucid-kv/lucid/workflows/Lucid/badge.svg?branch=master)](https://github.com/lucid-kv/lucid/actions?workflow=Lucid)
*   [Materialize (⭐4.8k)](https://github.com/MaterializeInc/materialize) - Streaming SQL database powered by Timely Dataflow :heavy\_dollar\_sign: [![Build status](https://badge.buildkite.com/97d6604e015bf633d1c2a12d166bb46f3b43a927d3952c999a.svg?branch=main)](https://buildkite.com/materialize/tests)
*   [noria (⭐4.6k)](https://github.com/mit-pdos/noria) \[[noria](https://crates.io/crates/noria)] — Dynamically changing, partially-stateful data-flow for web application backends [![build badge](https://api.travis-ci.org/mit-pdos/noria.svg?branch=master)](https://travis-ci.org/mit-pdos/noria)
*   [ParityDB (⭐174)](https://github.com/paritytech/parity-db) — Fast and reliable database, optimised for read operation
*   [PumpkinDB (⭐1.3k)](https://github.com/PumpkinDB/PumpkinDB) — an event sourcing database engine
*   [Qdrant (⭐3.7k)](https://github.com/qdrant/qdrant) - An open source vector similarity search engine with extended filtering support [![Tests](https://github.com/qdrant/qdrant/workflows/Tests/badge.svg)](https://github.com/qdrant/qdrant/actions)
*   [RisingWaveLabs/RisingWave (⭐3.8k)](https://github.com/RisingWaveLabs/risingwave) - the next-generation streaming database in the cloud [![CI](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg)](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg?branch=main)
*   [seppo0010/rsedis (⭐1.6k)](https://github.com/seppo0010/rsedis) — A Redis reimplementation in Rust [![build badge](https://api.travis-ci.org/seppo0010/rsedis.svg?branch=master)](https://travis-ci.org/seppo0010/rsedis)
*   [Skytable (⭐1.4k)](https://github.com/skytable/skytable) — A multi-model NoSQL database ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/skytable/skytable/Tests?style=flat-square)
*   [sled](https://crates.io/crates/sled) — A (beta) modern embedded database [![Build Status](https://github.com/spacejam/sled/workflows/Rust/badge.svg?branch=master)](https://github.com/spacejam/sled/actions?workflow=Rust)
*   [SurrealDB (⭐17k)](https://github.com/surrealdb/surrealdb) — A scalable, distributed, document-graph database [![Build Status](https://img.shields.io/github/workflow/status/surrealdb/surrealdb/Continuous%20integration/main)](https://github.com/surrealdb/surrealdb/actions)
*   [TerminusDB (⭐310)](https://github.com/terminusdb/terminusdb-store) - open source graph database and document store [![Build Status](https://github.com/terminusdb/terminusdb-store/workflows/Build/badge.svg?branch=master)](https://github.com/terminusdb/terminusdb-store/actions)
*   [tikv (⭐13k)](https://github.com/tikv/tikv) — A distributed KV database in Rust [![Build Status](https://ci.pingcap.net/job/tikv_ghpr_test/badge/icon)](https://ci.pingcap.net/job/tikv_ghpr_test/)
*   [vorot93/libmdbx-rs (⭐47)](https://github.com/vorot93/libmdbx-rs) \[[mdbx-sys](https://crates.io/crates/mdbx-sys)] — Rust bindings for MDBX, a "fast, compact, powerful, embedded, transactional key-value database, with permissive license". This is a fork of mozilla/lmdb-rs with patches to make it work with libmdbx.
*   [WooriDB (⭐115)](https://github.com/naomijub/wooridb) - General purpose time serial database inspired by Crux and Datomic.

### Emulators

See also [crates matching keyword 'emulator'](https://crates.io/keywords/emulator).

*   CHIP-8
    *   [ColinEberhardt/wasm-rust-chip8 (⭐240)](https://github.com/ColinEberhardt/wasm-rust-chip8) — A WebAssembly CHIP-8 emulator written with Rust
    *   [starrhorne/chip8-rust (⭐104)](https://github.com/starrhorne/chip8-rust) — Yet another rust chip8 emulator
*   Commodore 64
    *   [kondrak/rust64 (⭐221)](https://github.com/kondrak/rust64) — [![build badge](https://api.travis-ci.org/kondrak/rust64.svg?branch=master)](https://travis-ci.org/kondrak/rust64)
*   Flash Player
    *   [Ruffle (⭐11k)](https://github.com/ruffle-rs/ruffle) — Ruffle is an Adobe Flash Player emulator written in the Rust programming language. Ruffle targets both the desktop and the web using WebAssembly. [![CI](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml)[![CI](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml)
*   Gameboy
    *   [Gekkio/mooneye-gb (⭐807)](https://github.com/Gekkio/mooneye-gb) — [![build badge](https://api.travis-ci.org/Gekkio/mooneye-gb.svg?branch=master)](https://travis-ci.org/Gekkio/mooneye-gb)
    *   [mohanson/gameboy (⭐1.2k)](https://github.com/mohanson/gameboy) — Full featured Cross-platform GameBoy emulator. Forever boys!.
    *   [mvdnes/rboy (⭐514)](https://github.com/mvdnes/rboy) — [![build badge](https://api.travis-ci.org/mvdnes/rboy.svg?branch=master)](https://travis-ci.org/mvdnes/rboy)
*   Gameboy Advance
    *   [michelhe/rustboyadvance-ng (⭐513)](https://github.com/michelhe/rustboyadvance-ng) - RustboyAdvance-ng is a Gameboy Advance emulator with desktop, android and [WebAssembly](https://michelhe.github.io/rustboyadvance-ng/) support. [![build badge](https://github.com/michelhe/rustboyadvance-ng/workflows/Deploy/badge.svg?branch=master)](https://github.com/michelhe/rustboyadvance-ng/actions?query=workflow%3ADeploy)
*   GameMaker
    *   [OpenGMK (⭐151)](https://github.com/OpenGMK/OpenGMK) — OpenGMK is a modern rewrite of the proprietary GameMaker Classic engines, providing a full sourceport of the runner, a decompiler, a TASing framework, and libraries for working with gamedata yourself.
*   Intel 8080 CPU
    *   [mohanson/i8080 (⭐85)](https://github.com/mohanson/i8080) — Intel 8080 cpu emulator by Rust
*   iOS
    *   [touchHLE (⭐173)](https://github.com/hikari-no-yume/touchHLE) — High-level emulator for iPhone OS apps
*   iPod
    *   [clicky (⭐102)](https://github.com/daniel5151/clicky) — A clickwheel iPod emulator (WIP)
*   NES
    *   [koute/pinky (⭐710)](https://github.com/koute/pinky) — [![build badge](https://api.travis-ci.org/koute/pinky.svg?branch=master)](https://travis-ci.org/koute/pinky)
    *   [pcwalton/sprocketnes (⭐725)](https://github.com/pcwalton/sprocketnes)
*   PlayStation 4
    *   [Obliteration (⭐155)](https://github.com/obhq/obliteration) — Experimental PS4 emulator written in Rust for Windows, macOS and Linux [![CI](https://github.com/obhq/obliteration/actions/workflows/main.yml/badge.svg)](https://github.com/obhq/obliteration/actions/workflows/main.yml)
*   ZX Spectrum
    *   [rustzx/rustzx (⭐162)](https://github.com/rustzx/rustzx) — [![RustZX CI](https://github.com/rustzx/rustzx/actions/workflows/ci.yml/badge.svg)](https://github.com/rustzx/rustzx/actions/workflows/ci.yml)

### Games

See also [Games Made With Piston (⭐4.3k)](https://github.com/PistonDevelopers/piston/wiki/Games-Made-With-Piston).

*   [citybound (⭐7.3k)](https://github.com/citybound/citybound) — The city sim you deserve
*   [cristicbz/rust-doom (⭐2.2k)](https://github.com/cristicbz/rust-doom) — A renderer for Doom, may progress to being a playable game [![build badge](https://api.travis-ci.org/cristicbz/rust-doom.svg?branch=master)](https://travis-ci.org/cristicbz/rust-doom)
*   [doukutsu-rs (⭐579)](https://github.com/doukutsu-rs/doukutsu-rs) — A Rust reimplementation of Cave Story engine with some enhancements.
*   [garkimasera/rusted-ruins (⭐429)](https://github.com/garkimasera/rusted-ruins) — Extensible open world rogue like game with pixel art [![build badge](https://api.travis-ci.org/garkimasera/rusted-ruins.svg?branch=master)](https://travis-ci.org/garkimasera/rusted-ruins)
*   [gorilla-devs/ferium (⭐663)](https://github.com/gorilla-devs/ferium) — Ferium is a fast and feature rich CLI program for downloading and updating Minecraft mods from Modrinth, CurseForge, and GitHub Releases, and modpacks from Modrinth and CurseForge ![ferium build](https://github.com/gorilla-devs/ferium/actions/workflows/build.yml/badge.svg?branch=main)
*   [lifthrasiir/angolmois-rust (⭐96)](https://github.com/lifthrasiir/angolmois-rust) — A minimalistic music video game which supports the BMS format [![build badge](https://api.travis-ci.org/lifthrasiir/angolmois-rust.svg?branch=master)](https://travis-ci.org/lifthrasiir/angolmois-rust)
*   [mara214/rsnake (⭐85)](https://github.com/mara214/rsnake) — Snake written in Rust.
*   [ozkriff/zemeroth (⭐1.3k)](https://github.com/ozkriff/zemeroth) — A small 2D turn-based hexagonal strategy game [![build badge](https://api.travis-ci.org/ozkriff/zemeroth.svg?branch=master)](https://travis-ci.org/ozkriff/zemeroth)
*   [rhex (⭐138)](https://github.com/dpc/rhex) — hexagonal ascii roguelike
*   [rsaarelm/magog (⭐345)](https://github.com/rsaarelm/magog) — A roguelike game in Rust
*   [SoftbearStudios/mk48 (⭐169)](https://github.com/SoftbearStudios/mk48) — Mk48.io is an online multiplayer naval combat game
*   [swatteau/sokoban-rs (⭐137)](https://github.com/swatteau/sokoban-rs) — A Sokoban implementation
*   [thetawavegame/thetawave-legacy (⭐190)](https://github.com/thetawavegame/thetawave-legacy) - A space shooter game that strives to be an entry point for new game developers to make their first contributions. ![build badge](https://github.com/thetawavegame/thetawave-legacy/actions/workflows/ci.yml/badge.svg?branch=master)
*   [Thinkofname/rust-quake (⭐56)](https://github.com/Thinkofname/rust-quake) — Quake map renderer in Rust
*   [ttyperacer/terminal-typeracer](https://gitlab.com/ttyperacer/terminal-typeracer) - Single player typing test game written for the terminal
*   [Veloren](https://gitlab.com/veloren/veloren) — An open world, open source multiplayer voxel RPG game currently in alpha development [![build badge](https://gitlab.com/veloren/veloren/badges/master/pipeline.svg)](https://gitlab.com/veloren/veloren/-/pipelines)
*   [Zone of Control (⭐358)](https://github.com/ozkriff/zoc) — A turn-based hexagonal strategy game [![build badge](https://api.travis-ci.org/ozkriff/zoc.svg?branch=master)](https://travis-ci.org/ozkriff/zoc)

### Graphics

*   [ivanceras/svgbob (⭐3.4k)](https://github.com/ivanceras/svgbob) — converts ASCII diagrams into SVG graphics [![build badge](https://api.travis-ci.org/ivanceras/svgbob.svg?branch=master)](https://travis-ci.org/ivanceras/svgbob)
*   [Limeth/euclider (⭐193)](https://github.com/Limeth/euclider) — A real-time 4D CPU ray tracer [![build badge](https://api.travis-ci.org/Limeth/euclider.svg?branch=master)](https://travis-ci.org/Limeth/euclider)
*   [RazrFalcon/resvg (⭐1.8k)](https://github.com/RazrFalcon/resvg) — An SVG rendering library. [![build badge](https://api.travis-ci.org/RazrFalcon/resvg.svg?branch=master)](https://travis-ci.org/RazrFalcon/resvg)
*   [turnage/valora](https://crates.io/crates/valora) — A library for generative fine art ![Rust](https://github.com/turnage/valora/workflows/Rust/badge.svg?branch=master)
*   [Twinklebear/tray\_rust (⭐496)](https://github.com/Twinklebear/tray_rust) — A ray tracer [![build badge](https://api.travis-ci.org/Twinklebear/tray_rust.svg?branch=master)](https://travis-ci.org/Twinklebear/tray_rust)

### Image processing

*   [Imager (⭐493)](https://github.com/imager-io/imager) — Automated image optimization.
*   [shssoichiro/oxipng (⭐1.9k)](https://github.com/shssoichiro/oxipng) \[[oxipng](https://crates.io/crates/oxipng)] — Multithreaded PNG optimizer written in Rust. [![Build Status](https://github.com/shssoichiro/oxipng/workflows/oxipng/badge.svg)](https://github.com/shssoichiro/oxipng/actions?query=branch%3Amaster) [![Version](https://img.shields.io/crates/v/oxipng.svg)](https://crates.io/crates/oxipng)

### Industrial automation

*   [locka99/opcua (⭐369)](https://github.com/locka99/opcua) — A pure rust [OPC UA](https://opcfoundation.org/about/opc-technologies/opc-ua/) library.
*   [slowtec/tokio-modbus (⭐230)](https://github.com/slowtec/tokio-modbus) — A [tokio](https://tokio.rs)-based [modbus](https://modbus.org) library. [![Build Status](https://api.travis-ci.org/slowtec/tokio-modbus.svg?branch=master)](https://travis-ci.org/slowtec/tokio-modbus)

### Observability

*   [avito-tech/bioyino (⭐206)](https://github.com/avito-tech/bioyino) — A high-performance scalable StatsD compatible server.
*   [OpenTelemetry](https://crates.io/crates/opentelemetry) — OpenTelemetry provides a single set of APIs, libraries, agents, and collector services to capture distributed traces and metrics from your application. You can analyze them using Prometheus, Jaeger, and other observability tools. [![GitHub Actions CI](https://github.com/open-telemetry/opentelemetry-rust/workflows/CI/badge.svg?branch=master)](https://github.com/open-telemetry/opentelemetry-rust/actions?query=workflow%3ACI+branch%3Amaster)
*   [Quickwit-oss/quickwit (⭐3k)](https://github.com/quickwit-oss/quickwit) - Cloud-native and highly cost-efficient search engine for log management. [![CI](https://github.com/quickwit-oss/quickwit/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/quickwit-oss/quickwit/actions?query=workflow%3ACI)
*   [Scaphandre (⭐903)](https://github.com/hubblo-org/scaphandre) - A power consumption monitoring agent, to track host and each service power consumption and enable designing systems and applications for more sustainability. Designed to fit any monitoring toolchain (already supports prometheus, warp10, riemann...).
*   [vectordotdev/vector (⭐13k)](https://github.com/vectordotdev/vector) — A High-Performance, Logs, Metrics, & Events Router.

### Operating systems

See also [A comparison of operating systems written in Rust (⭐494)](https://github.com/flosse/rust-os-comparison).

*   [0x59616e/SteinsOS (⭐87)](https://github.com/0x59616e/SteinsOS)  — An OS for armv8-a architecture.
*   [redox-os/redox](https://gitlab.redox-os.org/redox-os/redox) — [![build badge](https://api.travis-ci.org/redox-os/redox.svg?branch=master)](https://travis-ci.org/redox-os/redox)
*   [thepowersgang/rust\_os (⭐618)](https://github.com/thepowersgang/rust_os) — [![build badge](https://api.travis-ci.org/thepowersgang/rust_os.svg?branch=master)](https://travis-ci.org/thepowersgang/rust_os)
*   [theseus-os/Theseus (⭐2.3k)](https://github.com/theseus-os/Theseus) — A safe-language, single address space and single privilege level OS written from scratch in pure Rust - [![build badge](https://img.shields.io/github/workflow/status/theseus-os/Theseus/Documentation?label=docs%20build)](https://www.theseus-os.com/Theseus/book/index.html)
*   [tock/tock (⭐4.1k)](https://github.com/tock/tock) — A secure embedded operating system for Cortex-M based microcontrollers

### Productivity

*   [Bartib (⭐355)](https://github.com/nikolassv/bartib) \[[Bartib](https://crates.io/crates/bartib)] - A simple timetracker for the command line [![Tests](https://github.com/nikolassv/bartib/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/nikolassv/bartib/actions/workflows/test.yml)
*   [espanso (⭐6.8k)](https://github.com/espanso/espanso) — A cross-platform Text Expander written in Rust[![CI](https://github.com/espanso/espanso/actions/workflows/ci.yml/badge.svg?branch=dev\&event=push)](https://github.com/espanso/espanso/actions/workflows/ci.yml)
*   [eureka](https://crates.io/crates/eureka) — A CLI tool to input and store your ideas without leaving the terminal
*   [pier-cli/pier (⭐410)](https://github.com/pier-cli/pier) — A central repository to manage (add, search metadata, etc.) all your one-liners, scripts, tools, and CLIs

### Security tools

*   [AFLplusplus/LibAFL (⭐1.2k)](https://github.com/AFLplusplus/LibAFL) - Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no\_std, etc. [![build and test](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml)
*   [cargo-audit](https://crates.io/crates/cargo-audit) - Audit Cargo.lock for crates with security vulnerabilities
*   [cargo-auditable](https://crates.io/crates/cargo-auditable) - Make production Rust binaries auditable
*   [cargo-crev](https://crates.io/crates/cargo-crev) - A cryptographically verifiable code review system for the cargo (Rust) package manager.
*   [cargo-deny](https://crates.io/crates/cargo-deny) - Cargo plugin to help you manage large dependency graphs
*   [Cherrybomb (⭐717)](https://github.com/blst-security/cherrybomb) - Stop half-done API specifications with a CLI tool that helps you avoid undefined user behaviour by validating your API specifications.
*   [epi052/feroxbuster (⭐3.6k)](https://github.com/epi052/feroxbuster) - A simple, fast, recursive content discovery tool written in Rust (
*   [Inspektor (⭐259)](https://github.com/inspektor-dev/inspektor) - A database protocol-aware proxy that is used to enforce access policies 👮
*   [kpcyrd/authoscope (⭐345)](https://github.com/kpcyrd/authoscope) — A scriptable network authentication cracker [![build badge](https://api.travis-ci.org/kpcyrd/authoscope.svg?branch=master)](https://travis-ci.org/kpcyrd/authoscope)
*   [kpcyrd/rshijack (⭐378)](https://github.com/kpcyrd/rshijack) — A TCP connection hijacker, rust rewrite of shijack [![build badge](https://api.travis-ci.org/kpcyrd/rshijack.svg?branch=master)](https://travis-ci.org/kpcyrd/rshijack)
*   [kpcyrd/sn0int (⭐1.4k)](https://github.com/kpcyrd/sn0int) — A semi-automatic OSINT framework and package manager [![build badge](https://api.travis-ci.org/kpcyrd/sn0int.svg?branch=master)](https://travis-ci.org/kpcyrd/sn0int)
*   [kpcyrd/sniffglue (⭐921)](https://github.com/kpcyrd/sniffglue) — A secure multithreaded packet sniffer [![build badge](https://api.travis-ci.org/kpcyrd/sniffglue.svg?branch=master)](https://travis-ci.org/kpcyrd/sniffglue)
*   [ObserverWard (⭐550)](https://github.com/0x727/ObserverWard) — Community based web technologies analysis tool.
*   [phra/rustbuster (⭐472)](https://github.com/phra/rustbuster) — A Comprehensive Web Fuzzer and Content Discovery Tool
*   [ripasso (⭐557)](https://github.com/cortex/ripasso/) — A password manager, filesystem compatible with pass
*   [rustscan/rustscan (⭐9k)](https://github.com/RustScan/RustScan) — Make Nmap faster with this port scanning tool [![build badge](https://github.com/RustScan/RustScan/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/RustScan/RustScan/actions?query=workflow%3A%22Continuous+integration%22)

### Simulation

*   [hEngine (⭐705)](https://github.com/hashintel/hash/tree/main/packages/engine) - A Rust-implemented computational simulation engine, supporting large-scale agent-based modelling, with simulation logic written in JavaScript and Python.

### Social networks

*   Mastodon
    *   [Rustodon (⭐756)](https://github.com/rustodon/rustodon) - A Mastodon-compatible, ActivityPub-speaking server in Rust

### System tools

*   [ajeetdsouza/zoxide (⭐9.1k)](https://github.com/ajeetdsouza/zoxide/) — A fast alternative to `cd` that learns your habits [![release](https://github.com/ajeetdsouza/zoxide/workflows/.github/workflows/release.yml/badge.svg)](https://github.com/ajeetdsouza/zoxide/actions)
*   [Alonely0/Voila (⭐88)](https://github.com/Alonely0/Voila) — Voila is a domain-specific language launched through CLI tool for operating with files and directories in massive amounts in a fast & reliable way. [![Linux build](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml) [![macOS build](https://github.com/Alonely0/Voila/actions/workflows/mac-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/mac-ci.yml) [![Windows build](https://github.com/Alonely0/Voila/actions/workflows/windows-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/windows-ci.yml)
*   [bandwhich (⭐7.6k)](https://github.com/imsnif/bandwhich) — Terminal bandwidth utilization tool [![build badge](https://api.travis-ci.com/imsnif/bandwhich.svg?branch=master)](https://app.travis-ci.com/github/imsnif/bandwhich)
*   [bottom (⭐6k)](https://github.com/ClementTsang/bottom) - Yet another cross-platform graphical process/system monitor. [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ClementTsang/bottom/ci/master)](https://github.com/ClementTsang/bottom/actions?query=branch%3Amaster)
*   [brocode/fblog (⭐261)](https://github.com/brocode/fblog) — Small command-line JSON Log viewer [![build badge](https://api.travis-ci.org/brocode/fblog.svg?branch=master)](https://travis-ci.org/brocode/fblog)
*   [bustd (⭐188)](https://github.com/vrmiguel/bustd) - Lightweight process killer daemon to handle out-of-memory scenarios on Linux. [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/vrmiguel/bustd/build-and-test)](https://github.com/vrmiguel/bustd/actions?query=branch%3Amaster)
*   [buster/rrun (⭐105)](https://github.com/buster/rrun) — A command launcher for Linux, similar to gmrun [![build badge](https://api.travis-ci.org/buster/rrun.svg?branch=master)](https://travis-ci.org/buster/rrun)
*   [cantino/mcfly (⭐4.8k)](https://github.com/cantino/mcfly) - Fly through your shell history. Great Scott! [![build badge](https://api.travis-ci.org/cantino/mcfly.svg?branch=master)](https://travis-ci.org/cantino/mcfly)
*   [crabz (⭐237)](https://github.com/sstadick/crabz) - Multi-threaded compression and decompression CLI tool [![Build Status](https://github.com/sstadick/crabz/workflows/Check/badge.svg)](https://github.com/sstadick/crabz/actions?query=workflow%3ACheck)
*   [cristianoliveira/funzzy (⭐189)](https://github.com/cristianoliveira/funzzy) — A configurable filesystem watcher inspired by [entr](http://eradman.com/entrproject/) [![build badge](https://api.travis-ci.org/cristianoliveira/funzzy.svg?branch=master)](https://travis-ci.org/cristianoliveira/funzzy)
*   [dalance/procs (⭐3.7k)](https://github.com/dalance/procs) — A modern replacement for 'ps' written by Rust [![Regression](https://github.com/dalance/procs/actions/workflows/regression.yml/badge.svg)](https://github.com/dalance/procs/actions/workflows/regression.yml)
*   [ddh (⭐390)](https://github.com/darakian/ddh) — Fast duplicate file finder [![build badge](https://api.travis-ci.org/darakian/ddh.svg?branch=master)](https://travis-ci.org/darakian/ddh)
*   [diskonaut (⭐1.6k)](https://github.com/imsnif/diskonaut) — Terminal visual disk space navigator [![build badge](https://api.travis-ci.com/imsnif/diskonaut.svg?branch=main)](https://app.travis-ci.com/github/imsnif/diskonaut)
*   [dust (⭐5.5k)](https://github.com/bootandy/dust) — A more intuitive version of du
*   [fselect](https://crates.io/crates/fselect) — Find files with SQL-like queries [![build badge](https://api.travis-ci.org/jhspetersson/fselect.svg?branch=master)](https://travis-ci.org/jhspetersson/fselect)
*   [gitui (⭐12k)](https://github.com/extrawurst/gitui) - Blazing fast terminal client for git written in Rust. [![build](https://github.com/extrawurst/gitui/workflows/CI/badge.svg?branch=master)](https://github.com/extrawurst/gitui/actions)
*   [j0ru/kickoff (⭐167)](https://github.com/j0ru/kickoff) - Fast and snappy wayland program launcher [![build](https://github.com/j0ru/kickoff/actions/workflows/ci.yml/badge.svg)](https://github.com/j0ru/kickoff/actions)
*   [Kondo (⭐941)](https://github.com/tbillington/kondo) - CLI & GUI tool for deleting software project artifacts and reclaiming disk space
*   [lotabout/rargs (⭐382)](https://github.com/lotabout/rargs) \[[rargs](https://crates.io/crates/rargs)] — xargs + awk with pattern matching support [![build badge](https://api.travis-ci.org/lotabout/rargs.svg?branch=master)](https://travis-ci.org/lotabout/rargs)
*   [lotabout/skim (⭐3.8k)](https://github.com/lotabout/skim) — A fuzzy finder in pure rust [![build badge](https://api.travis-ci.org/lotabout/skim.svg?branch=master)](https://travis-ci.org/lotabout/skim)
*   [Luminarys/synapse (⭐813)](https://github.com/Luminarys/synapse) — Flexible and fast BitTorrent daemon. [![Build Status](https://api.travis-ci.org/Luminarys/synapse.svg?branch=master)](https://travis-ci.org/Luminarys/synapse)
*   [m4b/bingrep (⭐1.6k)](https://github.com/m4b/bingrep) — Greps through binaries from various OSs and architectures, and colors them. [![build badge](https://api.travis-ci.org/m4b/bingrep.svg?branch=master)](https://travis-ci.org/m4b/bingrep)
*   [mitnk/cicada (⭐926)](https://github.com/mitnk/cicada) — A bash-like Unix shell [![build badge](https://api.travis-ci.org/mitnk/cicada.svg?branch=master)](https://travis-ci.org/mitnk/cicada)
*   [mmstick/concurr (⭐92)](https://github.com/mmstick/concurr) — Alternative to GNU Parallel w/ a client-server architecture
*   [mmstick/fontfinder (⭐253)](https://github.com/mmstick/fontfinder) — GTK3 application for previewing and installing Google's fonts
*   [mmstick/tv-renamer (⭐144)](https://github.com/mmstick/tv-renamer) — A tv series renaming application with an optional GTK3 frontend. [![build badge](https://api.travis-ci.org/mmstick/tv-renamer.svg?branch=master)](https://travis-ci.org/mmstick/tv-renamer)
*   [mxseev/logram (⭐86)](https://github.com/mxseev/logram) — Push log files' updates to Telegram
*   [nickgerace/gfold (⭐219)](https://github.com/nickgerace/gfold) \[[gfold](https://crates.io/crates/gfold)] - CLI tool to help keep track of multiple Git repositories [![build](https://img.shields.io/github/workflow/status/nickgerace/gfold/merge/main)](https://github.com/nickgerace/gfold/actions?query=workflow%3Amerge+branch%3Amain)
*   [nivekuil/rip (⭐844)](https://github.com/nivekuil/rip) - A safe and ergonomic alternative to `rm` [![build badge](https://api.travis-ci.org/nivekuil/rip.svg?branch=master)](https://travis-ci.org/nivekuil/rip)
*   [ogham/exa (⭐21k)](https://github.com/ogham/exa) — A replacement for 'ls' [![build badge](https://api.travis-ci.org/ogham/exa.svg?branch=master)](https://travis-ci.org/ogham/exa)
*   [orhun/kmon (⭐1.7k)](https://github.com/orhun/kmon) — Linux Kernel Manager and Activity Monitor ![https://github.com/orhun/kmon/actions](https://img.shields.io/github/workflow/status/orhun/kmon/Continuous%20Integration/master?label=build)
*   [orhun/systeroid (⭐793)](https://github.com/orhun/systeroid) — A more powerful alternative to sysctl(8) with a terminal user interface ![https://github.com/orhun/systeroid/actions](https://img.shields.io/github/workflow/status/orhun/systeroid/Continuous%20Integration/main?label=build)
*   [ouch (⭐882)](https://github.com/ouch-org/ouch) - Painless compression and decompression on the command-line [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ouch-org/ouch/build-and-test)](https://github.com/ouch-org/ouch/actions?query=branch%3Amaster)
*   [Peltoche/lsd (⭐9.1k)](https://github.com/Peltoche/lsd) — An ls with a lot of pretty colors and awesome icons [![build](https://github.com/Peltoche/lsd/workflows/CICD/badge.svg?branch=master)](https://github.com/Peltoche/lsd/actions)
*   [pop-os/popsicle (⭐479)](https://github.com/pop-os/popsicle) — GTK3 & CLI utility for flashing multiple USB devices in parallel
*   [pop-os/system76-power (⭐470)](https://github.com/pop-os/system76-power/) — Linux power management daemon (DBus-interface) with CLI tool.
*   [pueue (⭐3.3k)](https://github.com/nukesor/pueue) — Manage your long running shell commands. [![GitHub Actions Workflow](https://github.com/nukesor/pueue/workflows/Test%20build/badge.svg?branch=master)](https://github.com/nukesor/pueue/actions)
*   [qarmin/cakawka (⭐9.4k)](https://github.com/qarmin/czkawka) - Multi-functional app to find duplicates, empty folders, similar images, etc. [![GitHub Actions Workflow](https://github.com/qarmin/czkawka/actions/workflows/pages/pages-build-deployment/badge.svg?branch=master)](https://github.com/qarmin/czkawka/actions)
*   [redox-os/ion (⭐1.3k)](https://github.com/redox-os/ion) — Next-generation system shell [![build badge](https://api.travis-ci.org/redox-os/ion.svg?branch=master)](https://travis-ci.org/redox-os/ion)
*   [sharkdp/bat (⭐39k)](https://github.com/sharkdp/bat) — A cat(1) clone with wings. [![CICD](https://github.com/sharkdp/bat/actions/workflows/CICD.yml/badge.svg?branch=master)](https://github.com/sharkdp/bat/actions/workflows/CICD.yml)
*   [sharkdp/fd (⭐26k)](https://github.com/sharkdp/fd) — A simple, fast and user-friendly alternative to find. [![CICD](https://github.com/sharkdp/fd/actions/workflows/CICD.yml/badge.svg)](https://github.com/sharkdp/fd/actions/workflows/CICD.yml)
*   [sitkevij/hex (⭐392)](https://github.com/sitkevij/hex) — A colorized hexdump terminal utility. [![build badge](https://api.travis-ci.org/sitkevij/hex.svg?branch=master)](https://travis-ci.org/sitkevij/hex)
*   [trippy (⭐168)](https://github.com/fujiapple852/trippy) - A network diagnostic tool [![build badge](https://github.com/fujiapple852/trippy/workflows/CI/badge.svg)](https://github.com/fujiapple852/trippy/actions/workflows/ci.yml)
*   [uutils/coreutils (⭐13k)](https://github.com/uutils/coreutils) — A cross-platform Rust rewrite of the GNU coreutils \[[![CICD](https://github.com/uutils/coreutils/actions/workflows/CICD.yml/badge.svg)](https://github.com/uutils/coreutils/actions/workflows/CICD.yml)
*   [watchexec (⭐3.7k)](https://github.com/watchexec/watchexec) — Executes commands in response to file modifications [![build badge](https://api.travis-ci.org/watchexec/watchexec.svg?branch=master)](https://travis-ci.org/watchexec/watchexec)
*   [XAMPPRocky/tokei (⭐7.6k)](https://github.com/XAMPPRocky/tokei) — counts the lines of code [![build badge](https://api.travis-ci.org/XAMPPRocky/tokei.svg?branch=master)](https://travis-ci.org/XAMPPRocky/tokei)

### Task scheduling

*   [delicate (⭐540)](https://github.com/BinChengZhao/delicate) — A lightweight and distributed task scheduling platform written in rust. [![Build Status](https://github.com/BinChengZhao/delicate/workflows/CI/badge.svg)](https://github.com/BinChengZhao/delicate/actions)

### Text editors

*   [amp](https://amp.rs) — Inspired by Vi/Vim. [![build badge](https://api.travis-ci.org/jmacdonald/amp.svg?branch=master)](https://travis-ci.org/jmacdonald/amp)
*   [emacs-ng (⭐1.4k)](https://github.com/emacs-ng/emacs-ng) — Complementing the C codebase with rust code to introduce new features.
*   [gchp/iota (⭐1.6k)](https://github.com/gchp/iota) — A simple text editor [![build badge](https://api.travis-ci.org/gchp/iota.svg?branch=master)](https://travis-ci.org/gchp/iota)
*   [helix (⭐19k)](https://github.com/helix-editor/helix) — A post-modern modal text editor inspired by Neovim/Kakoune. [![build badge](https://github.com/helix-editor/helix/actions/workflows/build.yml/badge.svg)](https://github.com/helix-editor/helix/actions)
*   [ilai-deutel/kibi (⭐902)](https://github.com/ilai-deutel/kibi) — A tiny (≤1024 LOC) text editor with syntax highlighting, incremental search and more. [![build badge](https://github.com/ilai-deutel/kibi/workflows/CI/badge.svg?branch=master)](https://github.com/ilai-deutel/kibi/actions?query=branch%3Amaster)
*   [Lapce (⭐23k)](https://github.com/lapce/lapce) — A modern editor with a backend written in Rust. Taking inspiration from the discontinued [xi-editory (⭐20k)](https://github.com/xi-editor/xi-editor).
*   [mathall/rim (⭐559)](https://github.com/mathall/rim) — Vim-like text editor written in Rust
*   [ox (⭐2.9k)](https://github.com/curlpipe/ox) — An independent Rust text editor that runs in your terminal!
*   [vamolessa/pepper (⭐289)](https://github.com/vamolessa/pepper) \[[pepper](https://crates.io/crates/pepper)] — An opinionated modal editor to simplify code editing from the terminal [![build badge](https://github.com/vamolessa/pepper/workflows/rust/badge.svg?branch=master)](https://github.com/vamolessa/pepper)

### Text processing

*   [dominikwilkowski/cfonts (⭐1.3k)](https://github.com/dominikwilkowski/cfonts) \[[cfonts](https://crates.io/crates/cfonts)] — Sexy ANSI fonts for the console ![build badge](https://github.com/dominikwilkowski/cfonts/actions/workflows/testing.yml/badge.svg)
*   [grex (⭐5.8k)](https://github.com/pemistahl/grex) — A command-line tool and library for generating regular expressions from user-provided test cases [![build badge](https://api.travis-ci.org/pemistahl/grex.svg?branch=master)](https://travis-ci.org/pemistahl/grex)
*   [Lisprez/so\_stupid\_search (⭐138)](https://github.com/Lisprez/so_stupid_search) — A simple and fast string search tool for human beings
*   [Melody (⭐4k)](https://github.com/yoav-lavi/melody) - A language that compiles to regular expressions and aims to be more easily readable and maintainable [![build badge](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml/badge.svg)](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml) [![crates.io](https://img.shields.io/crates/v/melody_compiler?label=compiler)](https://crates.io/crates/melody_compiler)
*   [phiresky/ripgrep-all (⭐5.3k)](https://github.com/phiresky/ripgrep-all) — ripgrep, but also search in PDFs, E-Books, Office documents, zip, tar.gz, etc. [![Build Status](https://api.travis-ci.org/phiresky/ripgrep-all.svg?branch=master)](https://travis-ci.org/phiresky/ripgrep-all)
*   [replicadse/complate (⭐20)](https://github.com/replicadse/complate) — An in-terminal text templating tool designed for standardizing messages (like for GIT commits). [![crates.io](https://img.shields.io/crates/v/complate.svg)](https://crates.io/crates/complate) [![crates.io](https://img.shields.io/crates/d/complate?label=crates.io%20downloads)](https://crates.io/crates/complate) [![build badge](https://github.com/replicadse/complate/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/complate/actions)
*   [ripgrep](https://crates.io/crates/ripgrep) — combines the usability of The Silver Searcher with the raw speed of grep [![build badge](https://api.travis-ci.org/BurntSushi/ripgrep.svg?branch=master)](https://travis-ci.org/BurntSushi/ripgrep)
*   [ruplacer (⭐335)](https://github.com/your-tools/ruplacer) — Find and replace text in source files [![Run tests](https://github.com/your-tools/ruplacer/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/your-tools/ruplacer/actions/workflows/test.yml)
*   [sd](https://crates.io/crates/sd) — Intuitive find & replace CLI
*   [sstadick/hck (⭐608)](https://github.com/sstadick/hck) - A faster and more featureful drop in replacement for `cut`  [![build badge](https://github.com/sstadick/hck/workflows/Check/badge.svg?branch=master)](https://github.com/sstadick/hck)
*   [vishaltelangre/ff (⭐310)](https://github.com/vishaltelangre/ff) — Find files (ff) by name! [![build badge](https://api.travis-ci.org/vishaltelangre/ff.svg?branch=master)](https://travis-ci.org/vishaltelangre/ff)
*   [whitfin/bytelines (⭐54)](https://github.com/whitfin/bytelines) \[[bytelines](https://crates.io/crates/bytelines)] — Read input lines as byte slices for high efficiency.
*   [whitfin/runiq (⭐170)](https://github.com/whitfin/runiq) — an efficient way to filter duplicate lines from unsorted input.
*   [xsv](https://crates.io/crates/xsv) — A fast CSV command line tool (slicing, indexing, selecting, searching, sampling, etc.) [![build badge](https://api.travis-ci.org/BurntSushi/xsv.svg?branch=master)](https://travis-ci.org/BurntSushi/xsv)

### Utilities

*   [1History (⭐345)](https://github.com/1History/1History) — Command line interface to backup Firefox/Chrome/Safari history to one SQLite file [![Build Status](https://github.com/1History/1History/actions/workflows/CI.yml/badge.svg)](https://github.com/1History/1History/actions/workflows/CI.yml)
*   [brycx/checkpwn (⭐97)](https://github.com/brycx/checkpwn) — A Have I Been Pwned (HIBP) command-line utility tool that lets you easily check for compromised accounts and passwords.
*   [evansmurithi/cloak (⭐207)](https://github.com/evansmurithi/cloak) — A Command Line OTP (One Time Password) Authenticator application.
    ![CI](https://github.com/evansmurithi/cloak/workflows/CI/badge.svg) [![build badge](https://ci.appveyor.com/api/projects/status/9mlfpfru3ng4c689/branch/master?svg=true)](https://ci.appveyor.com/project/evansmurithi/cloak)
*   [fcsonline/tmux-thumbs (⭐612)](https://github.com/fcsonline/tmux-thumbs) — A lightning fast version of tmux-fingers written in Rust, copy/pasting tmux like vimium/vimperator.
*   [guoxbin/dtool (⭐315)](https://github.com/guoxbin/dtool) — A useful command-line tool collection to assist development including conversion, codec, hashing, encryption, etc. [![Build Status](https://api.travis-ci.org/guoxbin/dtool.svg?branch=master)](https://travis-ci.org/guoxbin/dtool)
*   [mprocs (⭐603)](https://github.com/pvolok/mprocs) — TUI for running multiple processes
*   [nix-community/nix-init (⭐106)](https://github.com/nix-community/nix-init) — Generate Nix packages from URLs with hash prefetching, dependency inference, license detection, and more [![build-badge](https://github.com/nix-community/nix-init/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nix-init/actions/workflows/ci.yml)
*   [nix-community/nurl (⭐106)](https://github.com/nix-community/nurl) \[[nurl](https://crates.io/crates/nurl)] — Generate Nix fetcher calls from repository URLs [![build-badge](https://github.com/nix-community/nurl/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nurl/actions/workflows/ci.yml)
*   [nomino (⭐475)](https://github.com/yaa110/nomino) — Batch rename utility for developers [![Build Status](https://api.travis-ci.org/yaa110/nomino.svg?branch=master)](https://travis-ci.org/yaa110/nomino)
*   [raftario/licensor (⭐163)](https://github.com/raftario/licensor) — write licenses to stdout [![GitHub Actions](https://github.com/raftario/licensor/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/raftario/licensor/actions/workflows/build.yml)
*   [rustdesk/rustdesk (⭐36k)](https://github.com/rustdesk/rustdesk) — A remote desktop software, great alternative to TeamViewer and AnyDesk.
*   [tversteeg/emplace (⭐205)](https://github.com/tversteeg/emplace) — Synchronize installed packages on multiple machines
*   [vamolessa/verco (⭐215)](https://github.com/vamolessa/verco) \[[verco](https://crates.io/crates/verco)] — A simple Git/Hg tui client focused on keyboard shortcuts
*   [vaultwarden (⭐22k)](https://github.com/dani-garcia/vaultwarden#readme) [![Build](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml/badge.svg)](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml) — Alternative implementation of the Bitwarden server API written in Rust
*   [yaa110/cb (⭐76)](https://github.com/yaa110/cb) — Command line interface to manage clipboard [![Build Status](https://api.travis-ci.org/yaa110/cb.svg?branch=master)](https://travis-ci.org/yaa110/cb)

### Video

*   [dertuxmalwieder/yaydl (⭐210)](https://github.com/dertuxmalwieder/yaydl) \[[yaydl](https://crates.io/crates/yaydl)] - A simple video downloader
*   [harlanc/xiu (⭐620)](https://github.com/harlanc/xiu) — A powerful and secure live server by pure rust (rtmp/httpflv/hls/relay). [![Build Status](https://api.travis-ci.com/harlanc/xiu.svg?branch=master)](https://app.travis-ci.com/github/harlanc/xiu) [![crates.io](https://img.shields.io/crates/v/xiu.svg)](https://crates.io/crates/xiu)
*   [vidmerger (⭐54)](https://github.com/TGotwig/vidmerger) — 📼 Merge video & audio files via CLI
*   [xiph/rav1e (⭐3.1k)](https://github.com/xiph/rav1e) — The fastest and safest AV1 encoder. [![build badge](https://api.travis-ci.org/xiph/rav1e.svg?branch=master)](https://travis-ci.org/xiph/rav1e)

### Virtualization

*   [containers/youki (⭐4.3k)](https://github.com/containers/youki) — A container runtime in Rust [![build badge](https://github.com/containers/youki/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/containers/youki/actions)
*   [firecracker-microvm/firecracker (⭐21k)](https://github.com/firecracker-microvm/firecracker) — A lightweight virtual machine for container workload  [Firecracker Microvm](https://firecracker-microvm.github.io/)
*   [tailhook/vagga (⭐1.8k)](https://github.com/tailhook/vagga) — A containerization tool without daemons [![build badge](https://api.travis-ci.org/tailhook/vagga.svg?branch=master)](https://travis-ci.org/tailhook/vagga)

### Web

*   [cfal/tobaru (⭐107)](https://github.com/cfal/tobaru) - Port forwarder with allowlists, IP and TLS SNI/ALPN rule-based routing, iptables support, round-robin forwarding (load balancing), and hot reloading.
*   [LemmyNet/lemmy (⭐7.2k)](https://github.com/LemmyNet/lemmy) — A link aggregator / reddit clone for the fediverse [![Build Status](https://cloud.drone.io/api/badges/LemmyNet/lemmy/status.svg)](https://cloud.drone.io/LemmyNet/lemmy)
*   [libreddit (⭐4k)](https://github.com/libreddit/libreddit) - An alternative private front-end to Reddit
*   [MASQ-Project/Node (⭐123)](https://github.com/MASQ-Project/Node) — MASQ Node software provides a decentralized mesh-network of nodes for global users to access normal internet content - next evolution of tech beyond Tor & VPN [![build badge](https://github.com/MASQ-Project/Node/actions/workflows/ci-matrix.yml/badge.svg)](https://github.com/MASQ-Project/Node/actions)
*   [Plume-org/Plume (⭐1.9k)](https://github.com/Plume-org/Plume) — ActivityPub federating blogging application [![build badge](https://api.travis-ci.org/Plume-org/Plume.svg?branch=master)](https://travis-ci.org/Plume-org/Plume)
*   [Revolt/backend (⭐756)](https://github.com/revoltchat/backend) - User-first chat platform built with modern web technologies.

### Web Servers

*   [mufeedvh/binserve (⭐731)](https://github.com/mufeedvh/binserve) — A blazingly fast static web server with routing, templating, and security in a single binary you can set up with zero code [![build badge](https://github.com/mufeedvh/binserve/workflows/CICD/badge.svg?branch=master)](https://github.com/mufeedvh/binserve/actions)
*   [orhun/rustypaste (⭐176)](https://github.com/orhun/rustypaste) — A minimal file upload/pastebin service ![https://github.com/orhun/rustypaste/actions](https://img.shields.io/github/workflow/status/orhun/rustypaste/Continuous%20Integration/master?label=build)
*   [ronanyeah/rust-hasura (⭐132)](https://github.com/ronanyeah/rust-hasura) — A demonstration of how a Rust GraphQL server can be used as a remote schema with [Hasura](https://hasura.io/) ![Rust](https://github.com/ronanyeah/rust-hasura/workflows/Rust/badge.svg?branch=master)
*   [static-web-server (⭐524)](https://github.com/static-web-server/static-web-server) — A blazing fast and asynchronous web server for static files-serving. ⚡ [![CI](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml/badge.svg)](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml?query=branch%3Amaster)
*   [svenstaro/miniserve (⭐4.2k)](https://github.com/svenstaro/miniserve) — A small, self-contained cross-platform CLI tool that allows you to just grab the binary and serve some file(s) via HTTP [![build badge](https://github.com/svenstaro/miniserve/workflows/CI/badge.svg?branch=master)](https://github.com/svenstaro/miniserve/actions)
*   [thecoshman/http (⭐375)](https://github.com/thecoshman/http) — Host These Things Please — A basic http server for hosting a folder fast and simply [![build badge](https://api.travis-ci.org/thecoshman/http.svg?branch=master)](https://travis-ci.org/thecoshman/http)
*   [TheWaWaR/simple-http-server (⭐809)](https://github.com/TheWaWaR/simple-http-server) — simple static http server
*   [wyhaya/see (⭐175)](https://github.com/wyhaya/see) — Static HTTP file server [![Build Status](https://api.travis-ci.org/wyhaya/see.svg?branch=master)](https://travis-ci.org/wyhaya/see)

## Development tools

*   [bacon (⭐677)](https://github.com/Canop/bacon) — background rust code checker, similar to cargo-watch
*   [clippy](https://crates.io/crates/clippy) — Rust lints [![build badge](https://api.travis-ci.com/rust-lang/rust-clippy.svg?branch=master)](https://travis-ci.org/rust-lang/rust-clippy)
*   [clog-tool/clog-cli (⭐783)](https://github.com/clog-tool/clog-cli) — generates a changelog from git metadata ([conventional changelog](https://blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html)) [![build badge](https://api.travis-ci.org/clog-tool/clog-cli.svg?branch=master)](https://travis-ci.org/clog-tool/clog-cli)
*   [comtrya (⭐282)](https://github.com/comtrya/comtrya) — A configuration management tool for localhost / dotfiles [![build badge](https://github.com/comtrya/comtrya/actions/workflows/main.yaml/badge.svg)](https://github.com/comtrya/comtrya/actions)
*   [create-rust-app (⭐1.1k)](https://github.com/Wulf/create-rust-app) — Set up a modern rust+react web app by running one command. [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/create-rust-app)
*   [dan-t/rusty-tags (⭐371)](https://github.com/dan-t/rusty-tags) — create ctags/etags for a cargo project and all of its dependencies [![build badge](https://api.travis-ci.org/dan-t/rusty-tags.svg?branch=master)](https://travis-ci.org/dan-t/rusty-tags)
*   [datanymizer/datanymizer (⭐388)](https://github.com/datanymizer/datanymizer) - Powerful database anonymizer with flexible rules [![build badge](https://github.com/datanymizer/datanymizer/workflows/CI/badge.svg?branch=main)](https://github.com/datanymizer/datanymizer/actions?query=workflow%3ACI+branch%3Amain)
*   [delta](https://crates.io/crates/git-delta) — A syntax-highlighter for git and diff output[![build badge](https://github.com/dandavison/delta/workflows/Continuous%20Integration/badge.svg)](https://github.com/dandavison/delta//actions)
*   [dotenv-linter (⭐1.5k)](https://github.com/dotenv-linter/dotenv-linter) — Linter for `.env` files [![build badge](https://github.com/dotenv-linter/dotenv-linter/workflows/CI/badge.svg?branch=master)](https://github.com/dotenv-linter/dotenv-linter/actions?query=workflow%3ACI+branch%3Amaster)
*   [fw (⭐426)](https://github.com/brocode/fw) — workspace productivity booster [![Rust](https://github.com/brocode/fw/actions/workflows/rust.yml/badge.svg)](https://github.com/brocode/fw/actions/workflows/rust.yml)
*   [geiger (⭐1.1k)](https://github.com/rust-secure-code/cargo-geiger) — A program that list statistics related to usage of unsafe Rust code in a Rust crate and all its dependencies [![Build Status](https://dev.azure.com/cargo-geiger/cargo-geiger/_apis/build/status/rust-secure-code.cargo-geiger?branchName=master)](https://dev.azure.com/cargo-geiger/cargo-geiger/_build/latest?definitionId=1\&branchName=master)
*   [git-cliff (⭐5.2k)](https://github.com/orhun/git-cliff) — A highly customizable Changelog Generator that follows Conventional Commit specifications ![https://github.com/orhun/git-cliff/actions](https://img.shields.io/github/workflow/status/orhun/git-cliff/Continuous%20Integration/main?label=build)
*   [git-journal (⭐551)](https://github.com/saschagrunert/git-journal/) — The Git Commit Message and Changelog Generation Framework [![build badge](https://api.travis-ci.org/saschagrunert/git-journal.svg?branch=master)](https://travis-ci.org/saschagrunert/git-journal)
*   [hot-lib-reloader (⭐288)](https://github.com/rksm/hot-lib-reloader-rs) — Hot reload Rust code [![build badge](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml)
*   [just (⭐10k)](https://github.com/casey/just) — A handy command runner for project-specific tasks [![build badge](https://api.travis-ci.org/casey/just.svg?branch=master)](https://travis-ci.org/casey/just)
*   [mask (⭐769)](https://github.com/jacobdeichert/mask) — A CLI task runner defined by a simple markdown file [![build badge](https://github.com/jacobdeichert/mask/workflows/CI/badge.svg?branch=master)](https://github.com/jacobdeichert/mask/actions?query=workflow%3ACI)
*   [Module Linker (⭐247)](https://github.com/fiatjaf/module-linker) — Extension that adds `<a>` links to references in `mod`, `use` and `extern crate` statements at GitHub.
*   [ptags (⭐108)](https://github.com/dalance/ptags) — A parallel universal-ctags wrapper for git repository [![Build Status](https://api.travis-ci.org/dalance/ptags.svg?branch=master)](https://travis-ci.org/dalance/ptags)
*   [Racer (⭐3.4k)](https://github.com/racer-rust/racer) — code completion for Rust [![build badge](https://api.travis-ci.org/racer-rust/racer.svg?branch=master)](https://travis-ci.org/racer-rust/racer)
*   [Rust Search Extension (⭐977)](https://github.com/huhu/rust-search-extension) — A handy browser extension to search crates and docs in address bar (omnibox). [![Build Status](https://github.com/huhu/rust-search-extension/workflows/build/badge.svg?branch=master)](https://github.com/huhu/rust-search-extension/actions)
*   [rust-lang/rustfix (⭐808)](https://github.com/rust-lang/rustfix)  — automatically applies the suggestions made by rustc
*   [Rustup (⭐5.1k)](https://github.com/rust-lang/rustup) — the Rust toolchain installer [![build badge](https://github.com/rust-lang/rustup/workflows/Linux%20\(master\)/badge.svg?branch=master)](https://github.com/rust-lang/rustup/actions)
*   [scriptisto (⭐253)](https://github.com/igor-petruk/scriptisto) A language-agnostic "shebang interpreter" that enables you to write one file scripts in compiled languages. [![Build Status](https://cloud.drone.io/api/badges/igor-petruk/scriptisto/status.svg)](https://cloud.drone.io/igor-petruk/scriptisto)

### Build system

*   [Cargo](https://crates.io/) — the Rust package manager
    *   [cargo-all-features (⭐88)](https://github.com/frewsxcv/cargo-all-features) - A configurable subcommand to simplify testing, building and much more for all combinations of features [![CI](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml/badge.svg)](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml)
    *   [cargo-benchcmp](https://crates.io/crates/cargo-benchcmp) — A utility to compare Rust micro-benchmarks [![build badge](https://api.travis-ci.org/BurntSushi/cargo-benchcmp.svg?branch=master)](https://travis-ci.org/BurntSushi/cargo-benchcmp)
    *   [cargo-bitbake](https://crates.io/crates/cargo-bitbake) — A cargo extension that can generate BitBake recipes utilizing the classes from meta-rust [![build badge](https://api.travis-ci.org/cardoe/cargo-bitbake.svg?branch=master)](https://travis-ci.org/cardoe/cargo-bitbake)
    *   [cargo-cache](https://crates.io/crates/cargo-cache) — inspect/manage/clean your cargo cache (`~/.cargo/`/`${CARGO_HOME}`), print sizes etc [![Build Status](https://github.com/matthiaskrgr/cargo-cache/workflows/ci/badge.svg?branch=master)](https://github.com/matthiaskrgr/cargo-cache/actions)
    *   [cargo-check](https://crates.io/crates/cargo-check) — A wrapper around `cargo rustc -- -Zno-trans` which can be helpful for running a faster compile if you only need correctness checks [![build badge](https://api.travis-ci.org/rsolomo/cargo-check.svg?branch=master)](https://travis-ci.org/rsolomo/cargo-check)
    *   [cargo-count](https://crates.io/crates/cargo-count) — lists source code counts and details about cargo projects, including unsafe statistics [![build badge](https://api.travis-ci.org/kbknapp/cargo-count.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-count)
    *   [cargo-deb](https://crates.io/crates/cargo-deb) — Generates binary Debian packages [![build badge](https://api.travis-ci.org/mmstick/cargo-deb.svg?branch=master)](https://travis-ci.org/mmstick/cargo-deb)
    *   [cargo-deps](https://crates.io/crates/cargo-deps) — build dependency graphs of Rust projects [![build badge](https://api.travis-ci.com/m-cat/cargo-deps.svg?branch=master)](https://travis-ci.org/m-cat/cargo-deps)
    *   [cargo-do](https://crates.io/crates/cargo-do) — run multiple cargo commands in a row [![build badge](https://api.travis-ci.org/pwoolcoc/cargo-do.svg?branch=master)](https://travis-ci.org/pwoolcoc/cargo-do)
    *   [cargo-ebuild](https://crates.io/crates/cargo-ebuild) — cargo extension that can generate ebuilds using the in-tree eclasses [![build badge](https://api.travis-ci.org/cardoe/cargo-ebuild.svg?branch=master)](https://travis-ci.org/cardoe/cargo-ebuild)
    *   [cargo-edit](https://crates.io/crates/cargo-edit) — allows you to add and list dependencies by reading/writing to your Cargo.toml file from the command line [![build badge](https://api.travis-ci.org/killercup/cargo-edit.svg?branch=master)](https://travis-ci.org/killercup/cargo-edit)
    *   [cargo-generate (⭐1.3k)](https://github.com/cargo-generate/cargo-generate) A generator of a rust project by leveraging a pre-existing git repository as a template.
    *   [cargo-graph](https://crates.io/crates/cargo-graph) — updated fork of `cargo-dot` with additional features. Unmaintained, see `cargo-deps` [![build badge](https://api.travis-ci.org/kbknapp/cargo-graph.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-graph)
    *   [cargo-info](https://crates.io/crates/cargo-info) — queries crates.io for crates details from command line [![build badge](https://api.travis-ci.org/imp/cargo-info.svg?branch=master)](https://travis-ci.org/imp/cargo-info)
    *   [cargo-license](https://crates.io/crates/cargo-license) — A cargo subcommand to quickly view the licenses of all dependencies. [![build badge](https://api.travis-ci.org/onur/cargo-license.svg?branch=master)](https://travis-ci.org/onur/cargo-license)
    *   [cargo-limit](https://crates.io/crates/cargo-limit) — Cargo with less noise: warnings are skipped until errors are fixed, Neovim integration, etc. [![build badge](https://github.com/alopatindev/cargo-limit/actions/workflows/rust.yml/badge.svg)](https://github.com/alopatindev/cargo-limit/actions)
    *   [cargo-make](https://crates.io/crates/cargo-make) — Rust task runner and build tool. [![build badge](https://github.com/sagiegurari/cargo-make/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cargo-make/actions)
    *   [cargo-modules](https://crates.io/crates/cargo-modules) — A cargo plugin for showing a tree-like overview of a crate's modules. [![build badge](https://api.travis-ci.org/regexident/cargo-modules.svg?branch=master)](https://travis-ci.org/regexident/cargo-modules)
    *   [cargo-multi](https://crates.io/crates/cargo-multi) — runs specified cargo command on multiple crates [![build badge](https://api.travis-ci.org/imp/cargo-multi.svg?branch=master)](https://travis-ci.org/imp/cargo-multi)
    *   [cargo-outdated](https://crates.io/crates/cargo-outdated) — displays when newer versions of Rust dependencies are available, or out of date [![build badge](https://api.travis-ci.org/kbknapp/cargo-outdated.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-outdated)
    *   [cargo-rdme (⭐47)](https://github.com/orium/cargo-rdme) \[[cargo-rdme](https://crates.io/crates/cargo-rdme)] — Cargo subcommand to create your README from your crate’s documentation. [![build badge](https://github.com/orium/cargo-rdme/workflows/CI/badge.svg)](https://github.com/orium/cargo-rdme/actions?query=workflow%3ACI)
    *   [cargo-release](https://crates.io/crates/cargo-release) — tool for releasing git-managed cargo project, build, tag, publish, doc and push [![Rust](https://github.com/crate-ci/cargo-release/actions/workflows/ci.yml/badge.svg)](https://github.com/crate-ci/cargo-release/actions/workflows/rust.yml)
    *   [cargo-script](https://crates.io/crates/cargo-script) — lets people quickly and easily run Rust "scripts" which can make use of Cargo's package ecosystem [![build badge](https://api.travis-ci.org/DanielKeep/cargo-script.svg?branch=master)](https://travis-ci.org/DanielKeep/cargo-script)
    *   [cargo-update](https://crates.io/crates/cargo-update) — cargo subcommand for checking and applying updates to installed executables [![build badge](https://api.travis-ci.org/nabijaczleweli/cargo-update.svg?branch=master)](https://travis-ci.org/nabijaczleweli/cargo-update)
    *   [cargo-watch](https://crates.io/crates/cargo-watch) — utility for cargo to compile projects when sources change [![build badge](https://api.travis-ci.org/passcod/cargo-watch.svg?branch=master)](https://travis-ci.org/passcod/cargo-watch)
    *   [dtolnay/cargo-expand (⭐1.8k)](https://github.com/dtolnay/cargo-expand) — Expand macros in your source code
*   CMake
    *   [Devolutions/CMakeRust (⭐141)](https://github.com/Devolutions/CMakeRust) — useful for integrating a Rust library into a CMake project
    *   [SiegeLord/RustCMake (⭐104)](https://github.com/SiegeLord/RustCMake) — an example project showing usage of CMake with Rust [![build badge](https://api.travis-ci.org/SiegeLord/RustCMake.svg?branch=master)](https://travis-ci.org/SiegeLord/RustCMake)
*   [Fleet (⭐2.3k)](https://github.com/dimensionhq/fleet) \[[fleet-rs](https://crates.io/crates/fleet-rs)] - The blazing fast build tool for Rust.
*   Github actions
    *   [icepuma/rust-action (⭐77)](https://github.com/icepuma/rust-action) — rust github action
    *   [peaceiris/actions-mdbook (⭐233)](https://github.com/peaceiris/actions-mdbook) — GitHub Actions for mdBook
*   [Nix](https://nixos.org/)
    *   [nix-community/fenix (⭐226)](https://github.com/nix-community/fenix) — Rust toolchains and rust analyzer nightly for nix [![build-badge](https://github.com/nix-community/fenix/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/fenix/actions/workflows/ci.yml)

### Debugging

*   GDB
    *   [gdbgui (⭐9k)](https://github.com/cs01/gdbgui) — Browser based frontend for gdb to debug C, C++, Rust, and go. [![build badge](https://api.travis-ci.org/cs01/gdbgui.svg?branch=master)](https://travis-ci.org/cs01/gdbgui)
*   LLDB
    *   [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) — A LLDB extension for [Visual Studio Code](https://code.visualstudio.com/).

### Deployment

*   Docker
    *   [emk/rust-musl-builder (⭐1.3k)](https://github.com/emk/rust-musl-builder) — Docker images for compiling static Rust binaries using musl-libc and musl-gcc, with static versions of useful C libraries
    *   [kpcyrd/mini-docker-rust (⭐155)](https://github.com/kpcyrd/mini-docker-rust) — An example project for very small rust docker images [![build badge](https://api.travis-ci.org/kpcyrd/mini-docker-rust.svg?branch=master)](https://travis-ci.org/kpcyrd/mini-docker-rust)
    *   [liuchong/docker-rustup (⭐84)](https://github.com/liuchong/docker-rustup) — A multiple version (with musl tools) Rust Docker image
    *   [LukeMathWalker/cargo-chef (⭐893)](https://github.com/LukeMathWalker/cargo-chef) - A tool and pre-built images for caching compiling remote dependencies between Docker builds.
    *   [rust-cross/rust-musl-cross (⭐378)](https://github.com/rust-cross/rust-musl-cross) — Docker images for compiling static Rust binaries using musl-cross [![Build](https://github.com/rust-cross/rust-musl-cross/workflows/Build/badge.svg)](https://github.com/rust-cross/rust-musl-cross/actions?query=workflow%3ABuild)
    *   [rust-lang-nursery/docker-rust (⭐327)](https://github.com/rust-lang/docker-rust) — the official Rust Docker image
*   Github Pages
    *   [wasm-template-rust (⭐103)](https://github.com/sn99/wasm-template-rust) — A wasm template for Rust to publish to gh-pages without npm-deploy
*   Heroku
    *   [emk/heroku-buildpack-rust (⭐505)](https://github.com/emk/heroku-buildpack-rust) — A buildpack for Rust applications on Heroku

### Embedded

[Rust Embedded](https://rust-embedded.org/) focuses on improving the end-to-end experience of using Rust in resource-constrained environments and non-traditional platforms. See [awesome-embedded-rust (⭐4.1k)](https://github.com/rust-embedded/awesome-embedded-rust) for a curated, and more extended list of embedded Rust resources.

*   Arduino
    *   [avr-rust/ruduino (⭐614)](https://github.com/avr-rust/ruduino) Reusable components for the Arduino Uno.
*   Cross compiling
    *   [japaric/rust-cross (⭐2.3k)](https://github.com/japaric/rust-cross) — everything you need to know about cross compiling Rust programs [![build badge](https://api.travis-ci.org/japaric/rust-cross.svg?branch=master)](https://travis-ci.org/japaric/rust-cross)
    *   [japaric/xargo (⭐998)](https://github.com/japaric/xargo) — effortless cross compilation of Rust programs to custom bare-metal targets like ARM Cortex-M [![build badge](https://api.travis-ci.org/japaric/xargo.svg?branch=master)](https://travis-ci.org/japaric/xargo)
*   Espressif
    *   [esp-rs](https://github.com/esp-rs) home to a number of community projects enabling the use of the Rust programming language on various SoCs and modules produced by Espressif Systems.
*   nRF
    *   [nrf-rs/nrf-hal (⭐358)](https://github.com/nrf-rs/nrf-hal) — A Rust HAL for the nRF family of devices
        [![build badge](https://api.travis-ci.org/nrf-rs/nrf-hal.svg?branch=master)](https://travis-ci.org/nrf-rs/nrf-hal)

### FFI

See also [Foreign Function Interface](https://doc.rust-lang.org/book/first-edition/ffi.html),  [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/) (a collection of examples of using code written in Rust from other languages) and [FFI examples written in Rust (⭐1.1k)](https://github.com/alexcrichton/rust-ffi-examples).

*   C
    *   [rlhunt/cbindgen (⭐1.7k)](https://github.com/eqrion/cbindgen) — generates C header files from Rust source files. Used in Gecko for WebRender [![build badge](https://api.travis-ci.org/eqrion/cbindgen.svg?branch=master)](https://travis-ci.org/eqrion/cbindgen)
    *   [Sean1708/rusty-cheddar (⭐190)](https://github.com/Sean1708/rusty-cheddar) — generates C header files from Rust source files [![build badge](https://api.travis-ci.org/Sean1708/rusty-cheddar.svg?branch=master)](https://travis-ci.org/Sean1708/rusty-cheddar)
*   C++
    *   [dtolnay/cxx (⭐4.5k)](https://github.com/dtolnay/cxx) — Safe interop between Rust and C++ [![build badge](https://img.shields.io/badge/github-dtolnay/cxx-8da0cb?style=for-the-badge\&labelColor=555555\&logo=github)](https://github.com/dtolnay/cxx)
    *   [rust-cpp](https://crates.io/crates/cpp) - Embed C++ code directly in Rust. [![Build Status](https://api.travis-ci.org/mystor/rust-cpp.svg?branch=master)](https://travis-ci.org/mystor/rust-cpp) [![Build status](https://ci.appveyor.com/api/projects/status/uu76vmcrwnjqra0u/branch/master?svg=true)](https://ci.appveyor.com/project/mystor/rust-cpp/branch/master)
    *   [rust-lang/rust-bindgen (⭐3.2k)](https://github.com/rust-lang/rust-bindgen) — A Rust bindings generator
*   Erlang
    *   [rusterlium/rustler (⭐3.6k)](https://github.com/rusterlium/rustler) — safe Rust bridge for creating Erlang NIF functions [![build badge](https://api.travis-ci.org/rusterlium/rustler.svg?branch=master)](https://travis-ci.org/rusterlium/rustler)
*   Java
    *   [bennettanderson/rjni (⭐67)](https://github.com/benanders/rjni) — use Java from Rust
    *   [drrb/java-rust-example (⭐320)](https://github.com/drrb/java-rust-example) — use Rust from Java [![build badge](https://api.travis-ci.org/drrb/java-rust-example.svg?branch=master)](https://travis-ci.org/drrb/java-rust-example)
    *   [j4rs](https://crates.io/crates/j4rs) — use Java from Rust [![build badge](https://api.travis-ci.org/astonbitecode/j4rs.svg?branch=master)](https://travis-ci.org/astonbitecode/j4rs)
    *   [jni](https://crates.io/crates/jni) — use Rust from Java [![build badge](https://api.travis-ci.org/jni-rs/jni-rs.svg?branch=master)](https://travis-ci.org/jni-rs/jni-rs)
    *   [jni-sys](https://crates.io/crates/jni-sys) — Rust definitions corresponding to jni.h [![build badge](https://api.travis-ci.org/sfackler/rust-jni-sys.svg?branch=master)](https://travis-ci.org/sfackler/rust-jni-sys)
    *   [rucaja](https://crates.io/crates/rucaja) — use Java from Rust [![build badge](https://api.travis-ci.org/kud1ing/rucaja.svg?branch=master)](https://travis-ci.org/kud1ing/rucaja)
*   Lua
    *   [jcmoyer/rust-lua53 (⭐151)](https://github.com/jcmoyer/rust-lua53) — Lua 5.3 bindings for Rust [![build badge](https://api.travis-ci.org/jcmoyer/rust-lua53.svg?branch=master)](https://travis-ci.org/jcmoyer/rust-lua53)
    *   [lilyball/rust-lua (⭐124)](https://github.com/lilyball/rust-lua) — Safe Rust bindings to Lua 5.1 [![build badge](https://api.travis-ci.org/lilyball/rust-lua.svg?branch=master)](https://travis-ci.org/lilyball/rust-lua)
    *   [tickbh/td\_rlua (⭐48)](https://github.com/tickbh/td_rlua) \[[td\_rlua](https://crates.io/crates/td_rlua)] — Zero-cost high-level lua 5.3 wrapper for Rust [![build badge](https://api.travis-ci.org/tickbh/td_rlua.svg?branch=master)](https://travis-ci.org/tickbh/td_rlua)
    *   [tomaka/hlua (⭐488)](https://github.com/tomaka/hlua) — Rust library to interface with Lua [![build badge](https://api.travis-ci.org/tomaka/hlua.svg?branch=master)](https://travis-ci.org/tomaka/hlua)
*   mruby
    *   [anima-engine/mrusty (⭐200)](https://github.com/anima-engine/mrusty) — mruby safe bindings for Rust [![build badge](https://api.travis-ci.org/anima-engine/mrusty.svg?branch=master)](https://travis-ci.org/anima-engine/mrusty)
*   Node.js
    *   [infinyon/node-bindgen (⭐350)](https://github.com/infinyon/node-bindgen) - Easy way to generate nodejs module using Rust
    *   [neon-bindings/neon (⭐7k)](https://github.com/neon-bindings/neon) — Rust bindings for writing safe and fast native Node.js modules [![build badge](https://api.travis-ci.org/neon-bindings/neon.svg?branch=master)](https://travis-ci.org/neon-bindings/neon)
*   Objective-C
    *   [SSheldon/rust-objc (⭐337)](https://github.com/SSheldon/rust-objc) — Objective-C Runtime bindings and wrapper for Rust
*   Python
    *   [dgrunwald/rust-cpython (⭐1.7k)](https://github.com/dgrunwald/rust-cpython) — Python bindings [![build badge](https://api.travis-ci.org/dgrunwald/rust-cpython.svg?branch=master)](https://travis-ci.org/dgrunwald/rust-cpython)
    *   [getsentry/milksnake (⭐751)](https://github.com/getsentry/milksnake) — extension for python setuptools that allows you to distribute dynamic linked libraries in Python wheels in the most portable way imaginable.
    *   [PyO3/PyO3 (⭐7.4k)](https://github.com/PyO3/PyO3) — Rust bindings for the Python interpreter [![build badge](https://api.travis-ci.org/PyO3/pyo3.svg?branch=master)](https://travis-ci.org/PyO3/pyo3)
    *   [RustPython (⭐13k)](https://github.com/RustPython/RustPython) — A Python Interpreter written in Rust [![Build Status](https://github.com/RustPython/RustPython/workflows/CI/badge.svg)](https://github.com/RustPython/RustPython/actions?query=workflow%3ACI)
*   Ruby
    *   [d-unseductable/ruru (⭐813)](https://github.com/d-unseductable/ruru) — native Ruby extensions written in Rust [![build badge](https://api.travis-ci.org/d-unseductable/ruru.svg?branch=master)](https://travis-ci.org/d-unseductable/ruru)
    *   [danielpclark/rutie (⭐736)](https://github.com/danielpclark/rutie) — native Ruby extensions written in Rust and vice versa [![Build Status](https://api.travis-ci.org/danielpclark/rutie.svg?branch=master)](https://travis-ci.org/danielpclark/rutie)
    *   [tildeio/helix (⭐2k)](https://github.com/tildeio/helix) — write Ruby classes in Rust [![build badge](https://api.travis-ci.org/tildeio/helix.svg?branch=master)](https://travis-ci.org/tildeio/helix)
*   Web Assembly
    *   [rhysd/wain (⭐330)](https://github.com/rhysd/wain) - wain: WebAssembly INterpreter from scratch in Safe Rust with zero dependency [![build badge](https://github.com/rhysd/wain/workflows/CI/badge.svg?branch=master\&event=push)](https://github.com/rhysd/wain/actions?query=workflow%3ACI+branch%3Amaster+event%3Apush)
    *   [rustwasm/wasm-bindgen (⭐6k)](https://github.com/rustwasm/wasm-bindgen) — A project for facilitating high-level interactions between wasm modules and JS. [![build badge](https://api.travis-ci.com/rustwasm/wasm-bindgen.svg?branch=master)](https://travis-ci.org/rustwasm/wasm-bindgen)
    *   [rustwasm/wasm-pack (⭐4.9k)](https://github.com/rustwasm/wasm-pack) — :package: :sparkles: pack up the wasm and publish it to npm! [![build badge](https://api.travis-ci.com/rustwasm/wasm-pack.svg?branch=master)](https://travis-ci.org/rustwasm/wasm-pack)

### Formatters

*   [dprint (⭐1.7k)](https://github.com/dprint/dprint) — A pluggable and configurable code formatting platform [![build badge](https://github.com/dprint/dprint/workflows/CI/badge.svg)](https://github.com/dprint/dprint/actions?query=workflow%3ACI)
*   [Prettier Rust (⭐89)](https://github.com/jinxdash/prettier-plugin-rust) — An opinionated Rust code formatter that autofixes bad syntax ([Prettier](https://prettier.io/) community plugin)
*   [rustfmt (⭐4.9k)](https://github.com/rust-lang/rustfmt) — Rust code formatter maintained by the Rust team and included in cargo [![build badge](https://api.travis-ci.com/rust-lang/rustfmt.svg?branch=master)](https://app.travis-ci.com/github/rust-lang/rustfmt)

### IDEs

See also [Are we (I)DE yet?](https://areweideyet.com/) and [Rust Tools](https://www.rust-lang.org/tools).

*   [Atom](https://github.blog/2022-06-08-sunsetting-atom/)
    *   [rust-lang/atom-ide-rust (⭐239)](https://github.com/rust-lang/atom-ide-rust) — Rust IDE support for Atom, powered by the Rust Language Server (RLS) [![Build Status](https://api.travis-ci.com/rust-lang/atom-ide-rust.svg?branch=master)](https://app.travis-ci.com/grust-lang/atom-ide-rust)
*   [Eclipse](https://www.eclipse.org/)
    *   [Eclipse Corrosion (⭐196)](https://github.com/eclipse/corrosion)
*   [Emacs](https://www.gnu.org/software/emacs/)
    *   [emacs-racer (⭐398)](https://github.com/racer-rust/emacs-racer) — Autocompletion (see also [company](https://company-mode.github.io) and [auto-complete (⭐1.7k)](https://github.com/auto-complete/auto-complete))
    *   [flycheck-rust (⭐112)](https://github.com/flycheck/flycheck-rust) — Rust support for [Flycheck (⭐2.3k)](https://github.com/flycheck/flycheck)
    *   [rust-mode (⭐933)](https://github.com/rust-lang/rust-mode) — Rust Major Mode
    *   [rustic (⭐617)](https://github.com/brotzeit/rustic) - Rust development environment for Emacs [![build badge](https://github.com/brotzeit/rustic/workflows/CI/badge.svg)](https://github.com/brotzeit/rustic/actions?query=workflow%3ACI)
*   [gitpod.io](https://gitpod.io) — Online IDE with full Rust support based on Rust Language Server
*   [gnome-builder](https://wiki.gnome.org/Apps/Builder) native support for rust and cargo since Version 3.22.2
*   [IntelliJ](https://www.jetbrains.com/idea/)
    *   [intellij-rust/intellij-rust (⭐4.2k)](https://github.com/intellij-rust/intellij-rust) — [![build badge](https://api.travis-ci.org/intellij-rust/intellij-rust.svg?branch=master)](https://travis-ci.org/intellij-rust/intellij-rust)
*   [Kakoune](http://kakoune.org/)
    *   [kak-lsp/kak-lsp (⭐503)](https://github.com/kak-lsp/kak-lsp/) — [LSP](https://microsoft.github.io/language-server-protocol/) client. Implemented in Rust and supports rls out of the box.
*   [lapce (⭐23k)](https://github.com/lapce/lapce) — Lightning-fast and Powerful Code Editor written in Rust. [![build badge](https://github.com/lapce/lapce/actions/workflows/release.yml/badge.svg)](https://github.com/lapce/lapce/actions/workflows/release.yml)
*   [Ride (⭐171)](https://github.com/madeso/ride) — [![build badge](https://api.travis-ci.org/madeso/ride.svg?branch=master)](https://travis-ci.org/madeso/ride)
*   [Sublime Text](https://www.sublimetext.com/)
    *   [rust-lang/rust-enhanced (⭐708)](https://github.com/rust-lang/rust-enhanced) — official Rust package
*   [Vim](https://vim.sourceforge.io/) — the ubiquitous text editor
    *   [autozimu/LanguageClient-neovim (⭐3.5k)](https://github.com/autozimu/LanguageClient-neovim) — [LSP](https://microsoft.github.io/language-server-protocol/) client. Implemented in Rust and supports rls out of the box.
    *   [crates.nvim (⭐370)](https://github.com/Saecki/crates.nvim) - plugin that helps to managing crates.io dependencies.
    *   [rust.vim (⭐3.4k)](https://github.com/rust-lang/rust.vim) — provides file detection, syntax highlighting, formatting, Syntastic integration, and more.
    *   [vim-racer (⭐624)](https://github.com/racer-rust/vim-racer) — allows vim to use [Racer (⭐3.4k)](https://github.com/racer-rust/racer) for Rust code completion and navigation.
*   Visual Studio
    *   [dgriffen/rls-vs2017 (⭐110)](https://github.com/ZoeyR/rls-vs2017) — Rust support for Visual Studio 2017 Preview [![build badge](https://ci.appveyor.com/api/projects/status/d2lxlincwninhsng?svg=true)](https://ci.appveyor.com/project/dgriffen/rls-vs2017)
    *   [PistonDevelopers/VisualRust (⭐699)](https://github.com/PistonDevelopers/VisualRust) — A Visual Studio extension for Rust [![Build status](https://ci.appveyor.com/api/projects/status/5nw5no10jj0y4p3f?svg=true)](https://ci.appveyor.com/project/vosen/visualrust)
*   [Visual Studio Code](https://code.visualstudio.com/)
    *   [Better TOML](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml) - TOML support in vscode
    *   [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) — A LLDB extension
    *   [crates (⭐167)](https://github.com/serayuzgur/crates) — crates is an extension for crates.io dependencies. [![build badge](https://img.shields.io/vscode-marketplace/v/serayuzgur.crates.svg)](https://github.com/serayuzgur/crates) [![build badge](https://api.travis-ci.org/serayuzgur/crates.svg?branch=master)](https://travis-ci.org/serayuzgur/crates)
    *   [Prettier - Code formatter (Rust)](https://marketplace.visualstudio.com/items?itemName=jinxdash.prettier-rust) — Opinionated Rust code formatter that autofixes bad syntax ([Prettier](https://prettier.io/) community plugin)
    *   [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer) — An alternative rust language server to the RLS
    *   [rust-lang/rls-vscode](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust) — Rust support for Visual Studio Code (supports both RLS and rust-analyzer)

### Profiling

*   [bheisler/criterion.rs (⭐3.1k)](https://github.com/bheisler/criterion.rs) — Statistics-driven benchmarking library for Rust [![Build Status](https://api.travis-ci.org/bheisler/criterion.rs.svg?branch=master)](https://travis-ci.org/bheisler/criterion.rs)
*   [Bytehound (⭐3.3k)](https://github.com/koute/bytehound) — A memory profiler for Linux
*   [ellisonch/rust-stopwatch (⭐77)](https://github.com/ellisonch/rust-stopwatch) — A stopwatch library [![build badge](https://api.travis-ci.org/ellisonch/rust-stopwatch.svg?branch=master)](https://travis-ci.org/ellisonch/rust-stopwatch)
*   FlameGraphs
    *   [llogiq/flame (⭐639)](https://github.com/llogiq/flame) — [![build badge](https://api.travis-ci.org/llogiq/flame.svg?branch=master)](https://travis-ci.org/llogiq/flame)
    *   [mrhooray/torch (⭐125)](https://github.com/mrhooray/torch) — generates FlameGraphs based on DWARF Debug Info
*   [sharkdp/hyperfine (⭐14k)](https://github.com/sharkdp/hyperfine) — A command-line benchmarking tool [![Version info](https://img.shields.io/crates/v/hyperfine.svg)](https://crates.io/crates/hyperfine) [![Build Status](https://api.travis-ci.org/sharkdp/hyperfine.svg?branch=master)](https://travis-ci.org/sharkdp/hyperfine)

### Services

*   [deps.rs (⭐371)](https://github.com/deps-rs/deps.rs) — Detect outdated or insecure dependencies
*   [docs.rs](https://docs.rs) — Automatic documentation generation of crates

### Static analysis

\[[assert](https://crates.io/keywords/assert), [static](https://crates.io/keywords/static)]

*   [facebookexperimental/MIRAI (⭐801)](https://github.com/facebookexperimental/mirai) — an abstract interpreter operating on Rust's mid-level intermediate representation (MIR) [![Continuous Integration](https://github.com/facebookexperimental/MIRAI/actions/workflows/rust.yml/badge.svg)](https://github.com/facebookexperimental/MIRAI/actions/workflows/rust.yml)
*   [static\_assertions](https://crates.io/crates/static_assertions) — Compile-time assertions to ensure that invariants are met [![Build Status](https://api.travis-ci.org/nvzqz/static-assertions-rs.svg?branch=master)](https://travis-ci.org/nvzqz/static-assertions-rs/)

### Testing

\[[test](https://crates.io/keywords/test), [testing](https://crates.io/keywords/testing)]

*   Code Coverage
    *   [tarpaulin](https://crates.io/crates/cargo-tarpaulin) — A code coverage tool designed for Rust [![build badge](https://api.travis-ci.org/repositories/xd009642/tarpaulin.svg?branch=master)](https://travis-ci.org/xd009642/tarpaulin)
*   Continuous Integration
    *   [trust (⭐1.2k)](https://github.com/japaric/trust) — A Travis CI and AppVeyor template to test your Rust crate on 5 architectures and publish binary releases of it for Linux, macOS and Windows
*   Frameworks and Runners
    *   [AlKass/polish (⭐49)](https://github.com/AlKass/polish) — Mini Testing/Test-Driven Framework [![Build Status](https://api.travis-ci.org/AlKass/polish.svg?branch=master)](https://travis-ci.org/AlKass/polish) [![Crates Package Status](https://img.shields.io/crates/v/polish.svg)](https://crates.io/crates/polish)
    *   [cargo-dinghy](https://crates.io/crates/cargo-dinghy/) - A cargo extension to simplify running library tests and benches on smartphones and other small processor devices.
    *   [cucumber](https://crates.io/crates/cucumber) [![Latest Version](https://img.shields.io/crates/v/cucumber.svg)](https://crates.io/crates/cucumber) — An implementation of the Cucumber testing framework for Rust. Fully native, no external test runners or dependencies. [![Build Status](https://github.com/cucumber-rs/cucumber/workflows/CI/badge.svg?branch=master)](https://github.com/cucumber-rs/cucumber)
    *   [demonstrate](https://crates.io/crates/demonstrate) — Declarative Testing Framework [![Build Status](https://github.com/aubaugh/demonstrate/workflows/Continuous%20Integration/badge.svg?branch=master)](https://github.com/aubaugh/demonstrate)
    *   [rstest](https://crates.io/crates/rstest) — Fixture-based test framework for Rust [![Build Status](https://github.com/la10736/rstest/workflows/Test/badge.svg?branch=master)](https://github.com/la10736/rstest/actions)
    *   [speculate](https://crates.io/crates/speculate) — An RSpec inspired minimal testing framework for Rust
*   Mocking and Test Data
    *   [asomers/mockall (⭐960)](https://github.com/asomers/mockall) \[[mockall](https://crates.io/crates/mockall)] — A powerful mock object library for Rust. [![Cirrus Build Status](https://api.cirrus-ci.com/github/asomers/mockall.svg)](https://cirrus-ci.com/github/asomers/mockall)
    *   [fake-rs (⭐566)](https://github.com/cksac/fake-rs) —  A library for generating fake data [![build badge](https://api.travis-ci.org/repositories/cksac/fake-rs.svg?branch=master)](https://travis-ci.org/cksac/fake-rs)
    *   [goldenfile (⭐25)](https://github.com/calder/rust-goldenfile) \[[goldenfile](https://crates.io/crates/goldenfile)] - A library providing a simple API for goldenfile testing. [![build badge](https://api.travis-ci.org/calder/rust-goldenfile.svg?branch=master)](https://travis-ci.org/calder/rust-goldenfile)
    *   [httpmock (⭐325)](https://github.com/alexliesenfeld/httpmock) — HTTP mocking [![build badge](https://dev.azure.com/alexliesenfeld/httpmock/_apis/build/status/alexliesenfeld.httpmock?branchName=master)](https://dev.azure.com/alexliesenfeld/httpmock/_build/latest?definitionId=2\&branchName=master)
    *   [mockiato](https://crates.io/crates/mockiato) — A strict, yet friendly mocking library for Rust 2018 [![build badge](https://api.travis-ci.com/mockiato/mockiato.svg?branch=master)](https://app.travis-ci.com/github/mockiato/mockiato)
    *   [mockito](https://crates.io/crates/mockito) — HTTP mocking [![build badge](https://api.travis-ci.org/lipanski/mockito.svg?branch=master)](https://travis-ci.org/lipanski/mockito)
    *   [nrxus/faux (⭐329)](https://github.com/nrxus/faux/) [![Latest Version](https://img.shields.io/crates/v/faux.svg)](https://crates.io/crates/faux) — A library to create mocks out of structs. ![build](https://github.com/nrxus/faux/workflows/test/badge.svg?branch=master)
    *   [synth (⭐1k)](https://github.com/shuttle-hq/synth/) — Generate database data declaratively. [![build](https://github.com/shuttle-hq/synth/actions/workflows/synth-test.yml/badge.svg)](https://github.com/shuttle-hq/synth)
*   Mutation Testing
    *   [cargo-mutants (⭐190)](https://github.com/sourcefrog/cargo-mutants) \[[cargo-mutants](https://crates.io/crates/cargo-mutants)] - Finds inadequately tested code by injecting mutations, no source changes required. [![build badge](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml/badge.svg?branch=main\&event=push)](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml?query=branch%3Amain)
    *   [mutagen (⭐545)](https://github.com/llogiq/mutagen) \[[mutagen](https://crates.io/crates/mutagen)] — A source-level mutation testing framework (nightly only) [![build badge](https://api.travis-ci.org/llogiq/mutagen.svg?branch=master)](https://travis-ci.org/llogiq/mutagen)
*   Property Testing and Fuzzing
    *   [proptest](https://crates.io/crates/proptest) — property testing framework inspired by the [Hypothesis](https://hypothesis.works/) framework for Python [![build badge](https://api.travis-ci.org/altsysrq/proptest.svg?branch=master)](https://travis-ci.org/altsysrq/proptest)
    *   [quickcheck](https://crates.io/crates/quickcheck) — A Rust implementation of [QuickCheck](https://wiki.haskell.org/Introduction_to_QuickCheck1) [![build badge](https://api.travis-ci.org/BurntSushi/quickcheck.svg?branch=master)](https://travis-ci.org/BurntSushi/quickcheck)
    *   [rust-fuzz/afl.rs (⭐1.3k)](https://github.com/rust-fuzz/afl.rs) — A Rust fuzzer, using [AFL](https://lcamtuf.coredump.cx/afl/) [![build badge](https://api.travis-ci.org/rust-fuzz/afl.rs.svg?branch=master)](https://travis-ci.org/rust-fuzz/afl.rs)

### Transpiling

*   [BayesWitnesses/m2cgen (⭐2.3k)](https://github.com/BayesWitnesses/m2cgen) — A CLI tool to transpile trained classic machine learning models into a native Rust code with zero dependencies. [![GitHub Actions Status](https://github.com/BayesWitnesses/m2cgen/workflows/GitHub%20Actions/badge.svg?branch=master)](https://github.com/BayesWitnesses/m2cgen/actions)
*   [immunant/c2rust (⭐3k)](https://github.com/immunant/c2rust) — C to Rust translator and cross checker built atop Clang/LLVM. [![Build Status](https://api.travis-ci.org/immunant/c2rust.svg?branch=master)](https://travis-ci.org/immunant/c2rust)
*   [jameysharp/corrode (⭐2.1k)](https://github.com/jameysharp/corrode) — A C to Rust translator written in Haskell.

## Libraries

*   [perf-monitor-rs (⭐157)](https://github.com/larksuite/perf-monitor-rs) — A toolkit designed to be a foundation for applications to monitor their performance. [![crates.io](https://img.shields.io/crates/v/perf_monitor.svg)](https://crates.io/crates/perf_monitor)

### Artificial Intelligence

#### Genetic algorithms

*   [innoave/genevo (⭐112)](https://github.com/innoave/genevo) — Execute genetic algorithm (GA) simulations in a customizable and extensible way.
*   [m-decoster/RsGenetic (⭐75)](https://github.com/m-decoster/RsGenetic) — Genetic Algorithm library in Rust. In maintenance mode.
*   [Martin1887/oxigen (⭐147)](https://github.com/Martin1887/oxigen) — Fast, parallel, extensible and adaptable genetic algorithm library. A example using this library solves the N Queens problem for N = 255 in only few seconds and using less than 1 MB of RAM.
*   [pkalivas/radiate (⭐111)](https://github.com/pkalivas/radiate) — A customizable parallel genetic programming engine capable of evolving solutions for supervised, unsupervised, and reinforcement learning problems. Comes with complete and customizable implementation of NEAT and Evtree. [![Build Status](https://api.travis-ci.com/pkalivas/radiate.svg?branch=master)](https://app.travis-ci.com/github/pkalivas/radiate)![Crates.io](https://img.shields.io/crates/v/radiate)
*   [willi-kappler/darwin-rs (⭐99)](https://github.com/willi-kappler/darwin-rs) — Evolutionary algorithms with Rust [![Build Status](https://api.travis-ci.org/willi-kappler/darwin-rs.svg?branch=master)](https://travis-ci.org/willi-kappler/darwin-rs)

#### Machine learning

See \[[Machine learning](https://crates.io/keywords/machine-learning)]

See also [About Rust’s Machine Learning Community](https://medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790#.hvkp56j3f) and [Are we learning yet?](https://www.arewelearningyet.com).

*   [autumnai/leaf (⭐5.5k)](https://github.com/autumnai/leaf) — Open Machine Intelligence framework. [![Build Status](https://api.travis-ci.org/autumnai/leaf.svg?branch=master)](https://travis-ci.org/autumnai/leaf). Abandoned project. The most updated fork is [spearow/juice (⭐993)](https://github.com/spearow/juice).
*   [huggingface/tokenizers (⭐6.3k)](https://github.com/huggingface/tokenizers) - Hugging Face's tokenizers for modern NLP pipelines written in Rust (original implementation) with bindings for Python. [![Build Status](https://github.com/huggingface/tokenizers/workflows/Rust/badge.svg?branch=master)](https://github.com/huggingface/tokenizers/actions)
*   [LaurentMazare/tch-rs (⭐2.4k)](https://github.com/LaurentMazare/tch-rs) — Rust language bindings for PyTorch. [![Build Status](https://api.travis-ci.org/LaurentMazare/tch-rs.svg?branch=master)](https://travis-ci.org/LaurentMazare/tch-rs)
*   [maciejkula/rustlearn (⭐553)](https://github.com/maciejkula/rustlearn) — Machine learning crate for Rust. [![Circle CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://app.circleci.com/pipelines/github/maciejkula/rustlearn)
*   [rust-ml/linfa (⭐2.3k)](https://github.com/rust-ml/linfa) — Machine learning framework.
*   [smartcorelib/smartcore (⭐447)](https://github.com/smartcorelib/smartcore) — Machine Learning Library In Rust [![Build Status](https://img.shields.io/circleci/build/github/smartcorelib/smartcore)](https://smartcorelib.org/)
*   [tensorflow/rust (⭐4.2k)](https://github.com/tensorflow/rust) — Rust language bindings for TensorFlow. [![Build Status](https://api.travis-ci.org/tensorflow/rust.svg?branch=master)](https://travis-ci.org/tensorflow/rust)

### Astronomy

\[[astronomy](https://crates.io/keywords/astronomy)]

*   [fitsio](https://crates.io/crates/fitsio) — fits interface library wrapping cfitsio [![build badge](https://api.travis-ci.org/mindriot101/rust-fitsio.svg?branch=master)](https://travis-ci.org/mindriot101/rust-fitsio)
*   [flosse/rust-sun (⭐37)](https://github.com/flosse/rust-sun) \[[sun](https://crates.io/crates/sun)] — A rust port of the JS library suncalc [![build badge](https://api.travis-ci.org/flosse/rust-sun.svg?branch=master)](https://travis-ci.org/flosse/rust-sun)
*   [saurvs/astro-rust (⭐214)](https://github.com/saurvs/astro-rust) — astronomy for Rust [![build badge](https://api.travis-ci.org/saurvs/astro-rust.svg?branch=master)](https://travis-ci.org/saurvs/astro-rust)

### Asynchronous

*   [async-std](https://async.rs/) [\[async-std\]](https://crates.io/crates/async-std) - Async version of the Rust standard library [![CI](https://github.com/async-rs/async-std/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/async-rs/async-std/actions/workflows/ci.yml)
*   [dpc/mioco (⭐137)](https://github.com/dpc/mioco) — Scalable, coroutine-based, asynchronous IO handling library [![build badge](https://api.travis-ci.org/dpc/mioco.svg?branch=master)](https://travis-ci.org/dpc/mioco)
*   [mio (⭐5.3k)](https://github.com/tokio-rs/mio) — MIO is a lightweight IO library for Rust with a focus on adding as little overhead as possible over the OS abstractions [![build badge](https://api.travis-ci.org/tokio-rs/mio.svg?branch=master)](https://travis-ci.org/tokio-rs/mio)
*   [rust-lang/futures-rs (⭐4.7k)](https://github.com/rust-lang/futures-rs) — Zero-cost futures in Rust [![build badge](https://api.travis-ci.com/rust-lang/futures-rs.svg?branch=master)](https://travis-ci.org/rust-lang/futures-rs)
*   [TeaEntityLab/fpRust (⭐102)](https://github.com/TeaEntityLab/fpRust) — Monad/MonadIO, Handler, Coroutine/doNotation, Functional Programming features for Rust [![build badge](https://api.travis-ci.org/TeaEntityLab/fpRust.svg?branch=master)](https://travis-ci.org/TeaEntityLab/fpRust)
*   [Xudong-Huang/may (⭐1.3k)](https://github.com/Xudong-Huang/may) — rust stackful coroutine library [![build badge](https://api.travis-ci.org/Xudong-Huang/may.svg?branch=master)](https://travis-ci.org/Xudong-Huang/may)
*   [zonyitoo/coio-rs (⭐455)](https://github.com/zonyitoo/coio-rs) — A coroutine I/O library with a working-stealing scheduler [![build badge](https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master)](https://travis-ci.org/zonyitoo/coio-rs)

### Audio and Music

\[[audio](https://crates.io/keywords/audio)]

*   [hound](https://crates.io/crates/hound) — A WAV encoding and decoding library [![build badge](https://api.travis-ci.org/ruuda/hound.svg?branch=master)](https://travis-ci.org/ruuda/hound)
*   [insomnimus/nodi (⭐6)](https://github.com/insomnimus/nodi) \[[nodi](https://crates.io/crates/nodi)] — A library for playback and abstraction of MIDI files. [![build badge](https://github.com/insomnimus/nodi/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/insomnimus/nodi/actions)
*   [jhasse/ears (⭐82)](https://github.com/jhasse/ears) — A simple library to play Sounds and Musics, on top of OpenAL and libsndfile [![build badge](https://api.travis-ci.org/jhasse/ears.svg?branch=master)](https://travis-ci.org/jhasse/ears)
*   [musitdev/portmidi-rs (⭐69)](https://github.com/musitdev/portmidi-rs) — [PortMidi](https://portmedia.sourceforge.net/portmidi/) bindings [![build badge](https://api.travis-ci.org/musitdev/portmidi-rs.svg?branch=master)](https://travis-ci.org/musitdev/portmidi-rs)
*   [ozankasikci/rust-music-theory (⭐562)](https://github.com/ozankasikci/rust-music-theory) — A Rust music theory library [![Build Status](https://api.travis-ci.com/ozankasikci/rust-music-theory.svg?branch=master)](https://travis-ci.org/ozankasikci/rust-music-theory)
*   [pdeljanov/Symphonia (⭐1.3k)](https://github.com/pdeljanov/Symphonia) — A pure Rust audio decoding and media demuxing library supporting AAC, FLAC, MP3, MP4, OGG, Vorbis, and WAV.
*   [RustAudio](https://github.com/RustAudio)
    *   [RustAudio/cpal (⭐1.8k)](https://github.com/RustAudio/cpal) - Low-level cross-platform audio I/O library in pure Rust. [![Actions Status](https://github.com/RustAudio/cpal/workflows/cpal/badge.svg?branch=master)](https://github.com/RustAudio/cpal/actions)
    *   [RustAudio/rodio (⭐1.2k)](https://github.com/RustAudio/rodio) — A Rust audio playback library [![Build Status](https://api.travis-ci.org/RustAudio/rodio.svg?branch=master)](https://travis-ci.org/RustAudio/rodio)
    *   [RustAudio/rust-portaudio (⭐334)](https://github.com/RustAudio/rust-portaudio) — PortAudio bindings [![build badge](https://api.travis-ci.org/RustAudio/rust-portaudio.svg?branch=master)](https://travis-ci.org/RustAudio/rust-portaudio)
*   [Serial-ATA/lofty-rs (⭐72)](https://github.com/Serial-ATA/lofty-rs) \[[lofty](https://crates.io/crates/lofty)] — A library for reading and editing the metadata of various audio formats [![build badge](https://github.com/Serial-ATA/lofty-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Serial-ATA/lofty-rs/actions)

### Authentication

*   [constantoine/totp-rs (⭐59)](https://github.com/constantoine/totp-rs) \[[totp-rs](https://crates.io/crates/totp-rs)] — 2fa library to generate and verify TOTP-based tokens ![Build Status](https://github.com/constantoine/totp-rs/workflows/Rust/badge.svg)
*   [Keats/jsonwebtoken (⭐1.1k)](https://github.com/Keats/jsonwebtoken) — [JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) lib in rust  [![Build Status](https://api.travis-ci.org/Keats/jsonwebtoken.svg?branch=master)](https://travis-ci.org/Keats/jsonwebtoken)
*   [oauth2 (⭐619)](https://github.com/ramosbugs/oauth2-rs) — Extensible, strongly-typed Rust OAuth2 client library [![Build Status](https://api.travis-ci.org/ramosbugs/oauth2-rs.svg?branch=main)](https://travis-ci.org/ramosbugs/oauth2-rs)
*   [oxide-auth (⭐475)](https://github.com/HeroicKatora/oxide-auth) — A OAuth2 server library, for use in combination with actix or other frontends, featuring a set of configurable and pluggable backends [![Build Status](https://api.cirrus-ci.com/github/HeroicKatora/oxide-auth.svg?branch=master)](https://cirrus-ci.com/github/HeroicKatora/oxide-auth)
*   [sgrust01/jwtvault (⭐65)](https://github.com/sgrust01/jwtvault) — Async library to manage and orchestrate JWT workflow  [![Build Status](https://api.travis-ci.org/sgrust01/jwtvault.svg?branch=master)](https://travis-ci.org/sgrust01/jwtvault)
*   [yup-oauth2 (⭐174)](https://github.com/dermesser/yup-oauth2) — An oauth2 client implementation providing the Device, Installed and Service Account flows [![Build Status](https://api.travis-ci.org/dermesser/yup-oauth2.svg?branch=master)](https://travis-ci.org/dermesser/yup-oauth2)

### Automotive

*   [marcelbuesing/can-dbc (⭐39)](https://github.com/marcelbuesing/can-dbc) \[[can-dbc](https://crates.io/crates/can-dbc)] — A parser for the DBC format [![build badge](https://api.travis-ci.org/marcelbuesing/can-dbc.svg?branch=dev)](https://travis-ci.org/marcelbuesing/can-dbc)
*   [marcelbuesing/tokio-socketcan-bcm (⭐4)](https://github.com/marcelbuesing/tokio-socketcan-bcm) \[[tokio-socketcan-bcm](https://crates.io/crates/tokio-socketcan-bcm)] — Linux SocketCAN BCM support for tokio [![build badge](https://api.travis-ci.org/marcelbuesing/tokio-socketcan-bcm.svg?branch=master)](https://travis-ci.org/marcelbuesing/tokio-socketcan-bcm)
*   [mbr/socketcan (⭐62)](https://github.com/socketcan-rs/socketcan-rs) \[[socketcan](https://crates.io/crates/socketcan)] — Linux SocketCAN library
*   [oefd/tokio-socketcan (⭐30)](https://github.com/oefd/tokio-socketcan) [\[tokio-socketcan\]](https://crates.io/crates/tokio-socketcan)] — Linux SocketCAN support for tokio based on the socketcan crate
*   [Sensirion/lin-bus (⭐13)](https://github.com/Sensirion/lin-bus-rs) \[[lin-bus](https://crates.io/crates/lin-bus)] — LIN bus driver traits and protocol implementation [![build badge](https://circleci.com/gh/Sensirion/lin-bus-rs.svg?style=svg)](https://app.circleci.com/pipelines/github/Sensirion/lin-bus-rs)

### Bioinformatics

*   [Rust-Bio](https://github.com/rust-bio) — bioinformatics libraries in Rust.

### Caching

*   [aisk/rust-memcache (⭐106)](https://github.com/aisk/rust-memcache) — Memcached client library [![build badge](https://api.travis-ci.org/aisk/rust-memcache.svg?branch=master)](https://travis-ci.org/aisk/rust-memcache)
*   [al8n/stretto (⭐320)](https://github.com/al8n/stretto) - A high performance thread-safe memory-bound Rust cache [![build badge](https://github.com/al8n/stretto/actions/workflows/ci.yml/badge.svg)](https://github.com/al8n/stretto/actions/workflows/ci.yml)
*   [jaemk/cached (⭐1k)](https://github.com/jaemk/cached) — Simple function caching/memoization
*   [mozilla/sccache (⭐3.7k)](https://github.com/mozilla/sccache/) - Shared Compilation Cache, great for Rust compilation [![build badge](https://api.travis-ci.org/mozilla/sccache.svg?branch=master)](https://travis-ci.org/mozilla/sccache)

### Cloud

*   AWS \[[aws](https://crates.io/keywords/aws)]
    *   [awslabs/aws-lambda-rust-runtime (⭐2.5k)](https://github.com/awslabs/aws-lambda-rust-runtime) \[[lambda\_runtime](https://crates.io/crates/lambda_runtime)] — A Rust runtime for AWS Lambda  [![build badge](https://github.com/awslabs/aws-lambda-rust-runtime/workflows/Rust/badge.svg)](https://github.com/awslabs/aws-lambda-rust-runtime/actions)
    *   [awslabs/aws-sdk-rust (⭐2.1k)](https://github.com/awslabs/aws-sdk-rust) - The new AWS SDK for Rust
    *   [rusoto/rusoto (⭐2.6k)](https://github.com/rusoto/rusoto) — [![build badge](https://api.travis-ci.org/rusoto/rusoto.svg?branch=master)](https://travis-ci.org/rusoto/rusoto)
*   Load Balancer
    *   [Convey (⭐291)](https://github.com/bparli/convey) - Layer 4 Load Balancer with dynamic configuration loading.
*   Multi Cloud
    *   [Qovery/engine (⭐1.9k)](https://github.com/Qovery/engine) - Abstraction layer library that turns easy application deployment on Cloud providers in just a few minutes

### Command-line

*   Argument parsing
    *   [clap-rs (⭐11k)](https://github.com/clap-rs/clap) \[[clap](https://crates.io/crates/clap)] — A simple to use, full featured command-line argument parser [![build badge](https://api.travis-ci.org/clap-rs/clap.svg?branch=master)](https://travis-ci.org/clap-rs/clap)
    *   [cliparser](https://crates.io/crates/cliparser) — Simple command line parser. [![build badge](https://github.com/sagiegurari/cliparser/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cliparser/actions)
    *   [docopt/docopt.rs (⭐747)](https://github.com/docopt/docopt.rs) \[[docopt](https://crates.io/crates/docopt)] — A Rust implementation of [DocOpt](http://docopt.org) [![build badge](https://api.travis-ci.org/docopt/docopt.rs.svg?branch=master)](https://travis-ci.org/docopt/docopt.rs)
    *   [google/argh (⭐1.3k)](https://github.com/google/argh) \[[argh](https://crates.io/crates/argh)] — An opinionated Derive-based argument parser optimized for code size [![build badge](https://github.com/google/argh/workflows/Argh/badge.svg?branch=master)](https://github.com/google/argh/actions)
    *   [killercup/quicli (⭐538)](https://github.com/killercup/quicli) \[[quicli](https://crates.io/crates/quicli)] — quickly build cool CLI apps in Rust [![build badge](https://api.travis-ci.org/killercup/quicli.svg?branch=master)](https://travis-ci.org/killercup/quicli)
    *   [ksk001100/seahorse (⭐230)](https://github.com/ksk001100/seahorse) \[[seahorse](https://crates.io/crates/seahorse)] — A minimal CLI framework written in Rust [![Build status](https://github.com/ksk001100/seahorse/workflows/CI/badge.svg?branch=master)](https://github.com/ksk001100/seahorse/actions)
    *   [TeXitoi/structopt (⭐2.6k)](https://github.com/TeXitoi/structopt) \[[structopt](https://crates.io/crates/structopt)] — parse command line argument by defining a struct [![build badge](https://api.travis-ci.org/TeXitoi/structopt.svg?branch=master)](https://travis-ci.org/TeXitoi/structopt)
*   Data visualization
    *   [nukesor/comfy-table (⭐543)](https://github.com/nukesor/comfy-table) \[[comfy-table](https://crates.io/crates/comfy-table)] — Beautiful dynamic tables for your cli tools. [![Build status](https://github.com/Nukesor/comfy-table/workflows/Tests/badge.svg?branch=master)](https://github.com/nukesor/comfy-table/actions)
    *   [zhiburt/tabled (⭐1.3k)](https://github.com/zhiburt/tabled) \[[tabled](https://crates.io/crates/tabled)] — An easy to use library for pretty print tables of Rust structs and enums.  [![Build Status](https://github.com/zhiburt/tabled/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/tabled/actions)
*   Human-centered design
    *   [rust-cli/human-panic (⭐1k)](https://github.com/rust-cli/human-panic) \[[human-panic](https://crates.io/crates/human-panic)] — panic messages for humans [![build badge](https://api.travis-ci.org/rust-cli/human-panic.svg?branch=master)](https://travis-ci.org/rust-cli/human-panic)
*   Line editor
    *   [kkawakam/rustyline (⭐1.2k)](https://github.com/kkawakam/rustyline) \[[rustyline](https://crates.io/crates/rustyline)] — readline implementation in Rust [![build badge](https://api.travis-ci.org/kkawakam/rustyline.svg?branch=master)](https://travis-ci.org/kkawakam/rustyline)
    *   [MovingtoMars/liner (⭐72)](https://github.com/MovingtoMars/liner) \[[liner](https://crates.io/crates/liner)] — A library offering readline-like functionality [![build badge](https://api.travis-ci.org/MovingtoMars/liner.svg?branch=master)](https://travis-ci.org/MovingtoMars/liner)
    *   [murarth/linefeed (⭐176)](https://github.com/murarth/linefeed) \[[linefeed](https://crates.io/crates/linefeed)] — Configurable, extensible, interactive line reader [![build badge](https://api.travis-ci.org/murarth/linefeed.svg?branch=master)](https://travis-ci.org/murarth/linefeed)
    *   [srijs/rust-copperline (⭐25)](https://github.com/srijs/rust-copperline) \[[copperline](https://crates.io/crates/copperline)] — pure-Rust command line editing library
*   Other
    *   [mgrachev/update-informer (⭐166)](https://github.com/mgrachev/update-informer) \[[update-informer](https://crates.io/crates/update-informer)] — Update informer for CLI applications. It checks for a new version on Crates.io and GitHub [![build badge](https://github.com/mgrachev/update-informer/workflows/CI/badge.svg)](https://github.com/mgrachev/update-informer/actions)
*   Pipeline
    *   [hniksic/rust-subprocess (⭐379)](https://github.com/hniksic/rust-subprocess) \[[subprocess](https://crates.io/crates/subprocess)] — facilities for interaction with external pipelines [![build badge](https://api.travis-ci.org/hniksic/rust-subprocess.svg?branch=master)](https://travis-ci.org/hniksic/rust-subprocess)
    *   [imp/pager-rs](https://gitlab.com/imp/pager-rs) \[[pager](https://crates.io/crates/pager)] — pipe your output through an external pager
    *   [oconnor663/duct.rs (⭐643)](https://github.com/oconnor663/duct.rs) \[[duct](https://crates.io/crates/duct)] — A builder for subprocess pipelines and IO redirection [![build badge](https://api.travis-ci.org/oconnor663/duct.rs.svg?branch=master)](https://travis-ci.org/oconnor663/duct.rs)
    *   [rust-cli/rexpect (⭐182)](https://github.com/rust-cli/rexpect) \[[rexpect](https://crates.io/crates/rexpect)] — automate interactive applications such as ssh, ftp, passwd, etc [![CI](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml/badge.svg)](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml)
    *   [zhiburt/expectrl (⭐133)](https://github.com/zhiburt/expectrl) \[[expectrl](https://crates.io/crates/expectrl)] — A library for controlling interactive programs in a pseudo-terminal [![build badge](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml)
*   Progress
    *   [a8m/pb (⭐510)](https://github.com/a8m/pb) \[[pbr](https://crates.io/crates/pbr)] — console progress bar for Rust
    *   [console-rs/indicatif (⭐3.3k)](https://github.com/console-rs/indicatif) \[[indicatif](https://crates.io/crates/indicatif)] — indicate progress to users
    *   [etienne-napoleone/spinach (⭐64)](https://github.com/etienne-napoleone/spinach) \[[spinach](https://crates.io/crates/spinach)] — Practical spinner for Rust. [![CI](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml/badge.svg)](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml)
    *   [FGRibreau/spinners (⭐437)](https://github.com/FGRibreau/spinners) \[[spinners](https://crates.io/crates/spinners)] — 60+ elegant terminal spinners
*   Prompt
    *   [hashmismatch/terminal\_cli.rs (⭐47)](https://github.com/hashmismatch/terminal_cli.rs) \[[terminal\_cli](https://crates.io/crates/terminal_cli)]  — build an interactive command prompt [![build badge](https://api.travis-ci.org/hashmismatch/terminal_cli.rs.svg?branch=master)](https://travis-ci.org/hashmismatch/terminal_cli.rs)
    *   [starship/starship](https://starship.rs/) \[[starship](https://crates.io/crates/starship)]  — A minimal, blazing fast, and extremely customizable prompt for any shell [![Build status](https://github.com/starship/starship/workflows/Main%20workflow/badge.svg?branch=master)](https://github.com/starship/starship/actions)
    *   [ynqa/promkit (⭐73)](https://github.com/ynqa/promkit) \[[promkit](https://crates.io/crates/promkit)]  — A toolkit for building interactive command-line tools [![Build status](https://github.com/ynqa/promkit/workflows/promkit/badge.svg?branch=master)](https://github.com/ynqa/promkit/actions)
*   Style
    *   [LukasKalbertodt/bunt (⭐204)](https://github.com/LukasKalbertodt/bunt) \[[bunt](https://crates.io/crates/bunt)] — cross-platform terminal colors and styling with macros [![Build status](https://github.com/LukasKalbertodt/bunt/actions/workflows/ci.yml/badge.svg)](https://github.com/LukasKalbertodt/bunt/actions?query=workflow%3ACI+branch%3Amaster)
    *   [LukasKalbertodt/term-painter (⭐75)](https://github.com/LukasKalbertodt/term-painter) \[[term-painter](https://crates.io/crates/term-painter)] — cross-platform styled terminal output [![build badge](https://api.travis-ci.org/LukasKalbertodt/term-painter.svg?branch=master)](https://travis-ci.org/LukasKalbertodt/term-painter)
    *   [mackwic/colored (⭐1.2k)](https://github.com/mackwic/colored) \[[colored](https://crates.io/crates/colored)] — Coloring terminal so simple, you already know how to do it!
    *   [ogham/rust-ansi-term (⭐413)](https://github.com/ogham/rust-ansi-term) \[[ansi\_term](https://crates.io/crates/ansi_term)] — control colours and formatting on ANSI terminals [![build badge](https://api.travis-ci.org/ogham/rust-ansi-term.svg?branch=master)](https://travis-ci.org/ogham/rust-ansi-term)
    *   [SergioBenitez/yansi (⭐171)](https://github.com/SergioBenitez/yansi) \[[yansi](https://crates.io/crates/yansi)] — A dead simple ANSI terminal color painting library
*   TUI
    *   BearLibTerminal
        *   [cfyzium/bearlibterminal (⭐30)](https://github.com/nabijaczleweli/BearLibTerminal.rs) \[[bear-lib-terminal](https://crates.io/crates/bear-lib-terminal)] — [BearLibTerminal (⭐43)](https://github.com/tommyettinger/BearLibTerminal) bindings [![build badge](https://api.travis-ci.org/nabijaczleweli/BearLibTerminal.rs.svg?branch=master)](https://travis-ci.org/nabijaczleweli/BearLibTerminal.rs)
    *   [fdehau/tui-rs (⭐9.6k)](https://github.com/fdehau/tui-rs) \[[tui](https://crates.io/crates/tui)] — A TUI library inspired by [blessed-contrib (⭐15k)](https://github.com/yaronn/blessed-contrib) and [termui (⭐12k)](https://github.com/gizak/termui) [![build badge](https://api.travis-ci.org/fdehau/tui-rs.svg?branch=master)](https://travis-ci.org/fdehau/tui-rs)
    *   [gyscos/Cursive (⭐3.3k)](https://github.com/gyscos/Cursive) \[[cursive](https://crates.io/crates/cursive)] — build rich TUI applications [![build badge](https://api.travis-ci.org/gyscos/Cursive.svg?branch=master)](https://travis-ci.org/gyscos/Cursive)
    *   [ivanceras/titik (⭐113)](https://github.com/ivanceras/titik) - a crossplatform TUI widget library with the goal of providing interactive widgets [![Build Status](https://api.travis-ci.com/ivanceras/titik.svg?branch=master)](https://app.travis-ci.com/github/ivanceras/titik)
    *   ncurses
        *   [ihalila/pancurses (⭐362)](https://github.com/ihalila/pancurses) \[[pancurses](https://crates.io/crates/pancurses)] — curses library, supports linux and windows [![build badge](https://api.travis-ci.org/ihalila/pancurses.svg?branch=master)](https://travis-ci.org/ihalila/pancurses)
        *   [jeaye/ncurses-rs (⭐631)](https://github.com/jeaye/ncurses-rs) \[[ncurses](https://crates.io/crates/ncurses)] — [ncurses](https://www.gnu.org/software/ncurses/) bindings [![build badge](https://api.travis-ci.org/jeaye/ncurses-rs.svg?branch=master)](https://travis-ci.org/jeaye/ncurses-rs)
    *   [ogham/rust-term-grid (⭐61)](https://github.com/ogham/rust-term-grid) \[[term\_grid](https://crates.io/crates/term_grid)] — Rust library for putting things in a grid [![build badge](https://api.travis-ci.org/ogham/rust-term-grid.svg?branch=master)](https://travis-ci.org/ogham/rust-term-grid)
    *   [redox-os/termion (⭐1.9k)](https://github.com/redox-os/termion) \[[termion](https://crates.io/crates/termion)] — bindless library for controlling terminals/TTY [![build badge](https://api.travis-ci.org/redox-os/termion.svg?branch=master)](https://travis-ci.org/redox-os/termion)
    *   Termbox
        *   [gchp/rustbox (⭐462)](https://github.com/gchp/rustbox) \[[rustbox](https://crates.io/crates/rustbox)] — bindings to [Termbox (⭐1.9k)](https://github.com/nsf/termbox) [![build badge](https://api.travis-ci.org/gchp/rustbox.svg?branch=master)](https://travis-ci.org/gchp/rustbox)
    *   [TimonPost/crossterm (⭐2.1k)](https://github.com/crossterm-rs/crossterm) \[[crossterm](https://crates.io/crates/crossterm)] — crossplatform terminal library

### Compression

*   [Brotli](https://opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html)
    *   [dropbox/rust-brotli (⭐666)](https://github.com/dropbox/rust-brotli) — Brotli decompressor in Rust that optionally avoids the stdlib
    *   [ende76/brotli-rs (⭐59)](https://github.com/ende76/brotli-rs) — implementation of Brotli compression
*   bzip2
    *   [alexcrichton/bzip2-rs (⭐68)](https://github.com/alexcrichton/bzip2-rs) — [libbz2](https://www.sourceware.org/bzip2/) bindings [![build badge](https://api.travis-ci.com/alexcrichton/bzip2-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/bzip2-rs)
*   gzip
    *   [zopfli (⭐10)](https://github.com/zopfli-rs/zopfli) \[[zopfli](https://crates.io/crates/zopfli)] — implementation of the Zopfli compression algorithm for higher quality deflate or zlib compression
*   gzp
    *   [sstadick/gzp (⭐125)](https://github.com/sstadick/gzp/) - multi-threaded encoding and decoding of deflate formats and snappy
*   miniz
    *   [rust-lang/flate2-rs (⭐628)](https://github.com/rust-lang/flate2-rs) — [miniz](https://code.google.com/archive/p/miniz) bindings [![build badge](https://github.com/rust-lang/flate2-rs/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/flate2-rs/actions)
*   snappy
    *   [JeffBelgum/rust-snappy (⭐14)](https://github.com/JeffBelgum/rust-snappy) — [snappy (⭐5.5k)](https://github.com/google/snappy) bindings [![build badge](https://api.travis-ci.org/JeffBelgum/rust-snappy.svg?branch=master)](https://travis-ci.org/JeffBelgum/rust-snappy)
*   tar
    *   [alexcrichton/tar-rs (⭐493)](https://github.com/alexcrichton/tar-rs) — tar archive reading/writing in Rust [![build badge](https://api.travis-ci.com/alexcrichton/tar-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/tar-rs)
*   zip
    *   [zip-rs/zip (⭐552)](https://github.com/zip-rs/zip) — read and write ZIP archives [![Build Status](https://api.travis-ci.org/mvdnes/zip-rs.svg?branch=master)](https://travis-ci.org/mvdnes/zip-rs)

### Computation

*   [argmin-rs/argmin (⭐565)](https://github.com/argmin-rs/argmin) \[[argmin](https://crates.io/crates/argmin)] — A pure Rust optimization library [![build badge](https://api.travis-ci.org/argmin-rs/argmin.svg?branch=master)](https://travis-ci.org/argmin-rs/argmin)
*   [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) \[[blas](https://crates.io/keywords/blas)]
    *   [mikkyang/rust-blas (⭐77)](https://github.com/mikkyang/rust-blas) — BLAS bindings
*   [calebwin/emu (⭐1.5k)](https://github.com/calebwin/emu) — A language for GPGPU numerical computing from a Rust macro
*   [dimforge/nalgebra (⭐3k)](https://github.com/dimforge/nalgebra) — low-dimensional linear algebra library [![build badge](https://api.travis-ci.org/dimforge/nalgebra.svg?branch=dev)](https://travis-ci.org/dimforge/nalgebra)
*   [GSL](http://www.gnu.org/software/gsl/)
    *   [GuillaumeGomez/rust-GSL (⭐158)](https://github.com/GuillaumeGomez/rust-GSL) — GSL bindings [![build badge](https://api.travis-ci.org/GuillaumeGomez/rust-GSL.svg?branch=master)](https://travis-ci.org/GuillaumeGomez/rust-GSL)
*   [LAPACK](https://en.wikipedia.org/wiki/LAPACK)
    *   [stainless-steel/lapack (⭐69)](https://github.com/blas-lapack-rs/lapack) — LAPACK bindings [![build badge](https://api.travis-ci.org/blas-lapack-rs/lapack.svg?branch=master)](https://travis-ci.org/blas-lapack-rs/lapack)
*   Parallel
    *   [arrayfire/arrayfire-rust (⭐703)](https://github.com/arrayfire/arrayfire-rust) — [Arrayfire](https://github.com/arrayfire) bindings
    *   [autumnai/collenchyma (⭐460)](https://github.com/autumnai/collenchyma) — An extensible, pluggable, backend-agnostic framework for parallel, high-performance computations on CUDA, OpenCL and common host CPU. [![build badge](https://api.travis-ci.org/autumnai/collenchyma.svg?branch=master)](https://travis-ci.org/autumnai/collenchyma)
    *   [luqmana/rust-opencl (⭐170)](https://github.com/luqmana/rust-opencl) — [OpenCL](https://www.khronos.org/opencl/) bindings
*   Scirust
    *   [indigits/scirust (⭐242)](https://github.com/indigits/scirust) — scientific computing library in Rust [![Build Status](https://api.travis-ci.org/indigits/scirust.svg?branch=master)](https://travis-ci.org/indigits/scirust)
*   Statrs
    *   [statrs-dev/statrs (⭐387)](https://github.com/statrs-dev/statrs) — Robust statistical computation library in Rust [![Build Status](https://api.travis-ci.org/boxtown/statrs.svg?branch=master)](https://travis-ci.org/boxtown/statrs)

### Concurrency

*   [crossbeam-rs/crossbeam (⭐5.8k)](https://github.com/crossbeam-rs/crossbeam) – Support for parallelism and low-level concurrency in Rust [![build badge](https://api.travis-ci.org/crossbeam-rs/crossbeam.svg?branch=master)](https://travis-ci.org/crossbeam-rs/crossbeam)
*   [orium/archery (⭐107)](https://github.com/orium/archery) \[[archery](https://crates.io/crates/archery)] — Library to abstract from `Rc`/`Arc` pointer types. [![build badge](https://github.com/orium/archery/workflows/CI/badge.svg)](https://github.com/orium/archery/actions?query=workflow%3ACI)
*   [Rayon (⭐7.9k)](https://github.com/rayon-rs/rayon) – A data parallelism library for Rust [![build badge](https://api.travis-ci.org/rayon-rs/rayon.svg?branch=master)](https://travis-ci.org/rayon-rs/rayon)
*   [rustcc/coroutine-rs (⭐405)](https://github.com/rustcc/coroutine-rs) – Coroutine Library in Rust [![build badge](https://api.travis-ci.org/rustcc/coroutine-rs.svg?branch=master)](https://travis-ci.org/rustcc/coroutine-rs)
*   [zonyitoo/coio-rs (⭐455)](https://github.com/zonyitoo/coio-rs) – Coroutine I/O for Rust [![build badge](https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master)](https://travis-ci.org/zonyitoo/coio-rs)

### Configuration

*   [andoriyu/uclicious (⭐14)](https://github.com/andoriyu/uclicious) \[[uclicious](https://crates.io/crates/uclicious)] — [libUCL (⭐1.5k)](https://github.com/vstakhov/libucl) based feature-rich configuration library. [![CircleCI](https://circleci.com/gh/vstakhov/libucl.svg?style=svg)](https://app.circleci.com/pipelines/github/vstakhov/libucl)
*   [Kixunil/configure\_me (⭐50)](https://github.com/Kixunil/configure_me) \[[configure\_me](https://crates.io/crates/configure_me)] — library for processing application configuration easily
*   [mehcode/config-rs (⭐1.8k)](https://github.com/mehcode/config-rs) \[[config](https://crates.io/crates/config)] — Layered configuration system for Rust applications (with strong support for 12-factor applications). [![build badge](https://api.travis-ci.org/mehcode/config-rs.svg?branch=master)](https://travis-ci.org/mehcode/config-rs)
*   [softprops/envy (⭐651)](https://github.com/softprops/envy) - deserialize env vars into typesafe structs [![Main](https://github.com/softprops/envy/actions/workflows/main.yml/badge.svg)](https://github.com/softprops/envy/actions/workflows/main.yml)

### Cryptography

\[[crypto](https://crates.io/keywords/crypto), [cryptography](https://crates.io/keywords/cryptography)]

*   [briansmith/ring (⭐3k)](https://github.com/briansmith/ring) — Safe, fast, small crypto using Rust and BoringSSL's cryptography primitives. [![build badge](https://api.travis-ci.org/briansmith/ring.svg?branch=master)](https://travis-ci.org/briansmith/ring)
*   [briansmith/webpki (⭐411)](https://github.com/briansmith/webpki) — Web PKI TLS X.509 certificate validation in Rust. [![build badge](https://api.travis-ci.org/briansmith/webpki.svg?branch=master)](https://travis-ci.org/briansmith/webpki)
*   [conradkleinespel/rooster (⭐133)](https://github.com/conradkleinespel/rooster) \[[rooster](https://crates.io/crates/rooster)] — Simple password manager to use in your terminal
*   [cossacklabs/themis (⭐1.7k)](https://github.com/cossacklabs/themis) \[[themis](https://crates.io/crates/themis)] — a high-level cryptographic library for solving typical data security tasks, best fit for multi-platform apps. [![build badge](https://circleci.com/gh/cossacklabs/themis/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/cossacklabs/themis)
*   [DaGenix/rust-crypto (⭐1.3k)](https://github.com/DaGenix/rust-crypto) — cryptographic algorithms in Rust [![build badge](https://api.travis-ci.org/DaGenix/rust-crypto.svg?branch=master)](https://travis-ci.org/DaGenix/rust-crypto)
*   [dalek-cryptography/curve25519-dalek (⭐623)](https://github.com/dalek-cryptography/curve25519-dalek) — Pure Rust implementation of Curve25519 operations
*   [dalek-cryptography/ed25519-dalek (⭐574)](https://github.com/dalek-cryptography/ed25519-dalek) — Pure Rust implementation of Ed25519 digital signatures
*   [dalek-cryptography/x25519-dalek (⭐258)](https://github.com/dalek-cryptography/x25519-dalek) — Pure Rust implementation of X25519 key exchange
*   [debris/tiny-keccak (⭐169)](https://github.com/debris/tiny-keccak) — Pure Rust implementation of the Keccak family (SHA3)
*   [exonum/exonum (⭐1.2k)](https://github.com/exonum/exonum) \[[exonum](https://crates.io/crates/exonum)] — extensible framework for blockchain projects [![build badge](https://api.travis-ci.com/exonum/exonum.svg?branch=master)](https://travis-ci.org/exonum/exonum)
*   [facebook/opaque-ke (⭐197)](https://github.com/facebook/opaque-ke) — Pure Rust implementation of the recent [OPAQUE](https://datatracker.ietf.org/doc/draft-krawczyk-cfrg-opaque/) password-authenticated key exchange. [![build badge](https://github.com/facebook/opaque-ke/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/facebook/opaque-ke)
*   [gakonst/ark-circom (⭐146)](https://github.com/gakonst/ark-circom) - Arkworks bindings to Circom's R1CS, for Groth16 Proof and Witness generation in Rust.
*   [klutzy/suruga (⭐123)](https://github.com/klutzy/suruga) — A Rust implementation of [TLS 1.2](https://datatracker.ietf.org/doc/html/rfc5246)
*   [kornelski/rust-security-framework (⭐173)](https://github.com/kornelski/rust-security-framework) — Bindings for Security Framework (OSX native)
*   [libOctavo/octavo (⭐139)](https://github.com/libOctavo/octavo) — Modular hash and crypto library in Rust [![build badge](https://api.travis-ci.org/libOctavo/octavo.svg?branch=master)](https://travis-ci.org/libOctavo/octavo)
*   [orion-rs/orion (⭐480)](https://github.com/orion-rs/orion) — This library aims to provide easy and usable crypto. 'Usable' meaning exposing high-level API's that are easy to use and hard to misuse. [![Tests](https://github.com/orion-rs/orion/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/orion-rs/orion/actions/workflows/test.yml)
*   [racum/rust-djangohashers (⭐52)](https://github.com/racum/rust-djangohashers) \[[djangohashers](https://crates.io/crates/djangohashers)] — A Rust port of the password primitives used in the Django Project. It doesn't require Django, only hashes and validates passwords according to its style. [![build badge](https://api.travis-ci.org/Racum/rust-djangohashers.svg?branch=master)](https://travis-ci.org/Racum/rust-djangohashers)
*   [RustCrypto/hashes (⭐1.2k)](https://github.com/RustCrypto/hashes) — Collection of cryptographic hash functions written in pure Rust [![build badge](https://api.travis-ci.org/RustCrypto/hashes.svg?branch=master)](https://travis-ci.org/RustCrypto/hashes)
*   [rustls/rustls (⭐4.1k)](https://github.com/rustls/rustls) — A Rust implementation of TLS
*   [sfackler/rust-native-tls (⭐373)](https://github.com/sfackler/rust-native-tls) — Bindings for native TLS libraries
*   [sfackler/rust-openssl (⭐1.1k)](https://github.com/sfackler/rust-openssl) — [OpenSSL](https://www.openssl.org/) bindings [![build badge](https://api.travis-ci.org/sfackler/rust-openssl.svg?branch=master)](https://travis-ci.org/sfackler/rust-openssl)
*   [sodiumoxide/sodiumoxide (⭐642)](https://github.com/sodiumoxide/sodiumoxide) — [libsodium (⭐11k)](https://github.com/jedisct1/libsodium) bindings [![build badge](https://api.travis-ci.org/sodiumoxide/sodiumoxide.svg?branch=master)](https://travis-ci.org/sodiumoxide/sodiumoxide)
*   [vityafx/randomorg (⭐7)](https://github.com/vityafx/randomorg) - A random.org client library. [![Crates badge](https://img.shields.io/crates/v/randomorg.svg)](https://crates.io/crates/randomorg)
*   [w3f/schnorrkel (⭐256)](https://github.com/w3f/schnorrkel) - Schnorr VRFs and signatures on the Ristretto group

### Data processing

*   [amv-dev/yata (⭐198)](https://github.com/amv-dev/yata) — high perfomance technical analysis library [![Build Status](https://img.shields.io/github/workflow/status/amv-dev/yata/Rust?branch=master)](https://github.com/amv-dev/yata/actions?query=workflow%3ARust)
*   [bluss/ndarray (⭐2.6k)](https://github.com/rust-ndarray/ndarray) — N-dimensional array with array views, multidimensional slicing, and efficient operations
*   [kernelmachine/utah (⭐139)](https://github.com/kernelmachine/utah) — Dataframe structure and operations in Rust
*   [pola-rs/polars (⭐13k)](https://github.com/pola-rs/polars) - Fast feature complete DataFrame library ![Build and test](https://github.com/pola-rs/polars/workflows/Build%20and%20test/badge.svg?branch=master)
*   [weld-project/weld (⭐2.9k)](https://github.com/weld-project/weld) — High-performance runtime for data analytics applications

### Data streaming

*   [infinyon/fluvio (⭐1.6k)](https://github.com/infinyon/fluvio) - Programmable data streaming platform [![CI](https://github.com/infinyon/fluvio/workflows/CI/badge.svg?branch=stable)](https://github.com/infinyon/fluvio/actions)

### Data structures

*   [becheran/grid (⭐47)](https://github.com/becheran/grid) \[[grid](https://crates.io/crates/grid)] —  Provide a two dimensional data structure for rust that is easy to use and fast. [![build status](https://github.com/becheran/grid/actions/workflows/rust.yml/badge.svg)](https://github.com/becheran/grid/actions)
*   [billyevans/tst (⭐20)](https://github.com/billyevans/tst) \[[tst](https://crates.io/crates/tst)] — Ternary search tree collection [![build badge](https://api.travis-ci.org/billyevans/tst.svg?branch=master)](https://travis-ci.org/billyevans/tst)
*   [contain-rs](https://github.com/contain-rs) — Extension of Rust's std::collections
*   [danielpclark/array\_tool (⭐71)](https://github.com/danielpclark/array_tool) — Array helpers for Rust. Some of the most common methods you would use on Arrays made available on Vectors. Polymorphic implementations for handling most of your use cases. [![build badge](https://api.travis-ci.org/danielpclark/array_tool.svg?branch=master)](https://travis-ci.org/danielpclark/array_tool)
*   [fizyk20/generic-array (⭐329)](https://github.com/fizyk20/generic-array) – a hack to allow for arrays sized by typenums [![build badge](https://api.travis-ci.org/fizyk20/generic-array.svg?branch=master)](https://travis-ci.org/fizyk20/generic-array)
*   [garro95/priority-queue (⭐140)](https://github.com/garro95/priority-queue)\[[priority-queue](https://crates.io/crates/priority-queue)] — A priority queue that implements priority changes. [![build badge](https://api.travis-ci.org/garro95/priority-queue.svg?branch=master)](https://travis-ci.org/garro95/priority-queue)
*   [mrhooray/kdtree-rs (⭐161)](https://github.com/mrhooray/kdtree-rs) — K-dimensional tree in Rust for fast geospatial indexing and nearest neighbors lookup
*   [orium/rpds (⭐897)](https://github.com/orium/rpds) \[[rpds](https://crates.io/crates/rpds)] — Persistent data structures in Rust. [![build badge](https://github.com/orium/rpds/workflows/CI/badge.svg)](https://github.com/orium/rpds/actions?query=workflow%3ACI)
*   [RoaringBitmap/roaring-rs (⭐558)](https://github.com/RoaringBitmap/roaring-rs) – Roaring Bitmaps in Rust
*   [rust-itertools/itertools (⭐2k)](https://github.com/rust-itertools/itertools) — [![build badge](https://api.travis-ci.org/rust-itertools/itertools.svg?branch=master)](https://travis-ci.org/rust-itertools/itertools)
*   [tnballo/scapegoat (⭐220)](https://github.com/tnballo/scapegoat) \[[scapegoat](https://crates.io/crates/scapegoat)] — Safe, fallible, stack-only alternative to `BTreeSet` and `BTreeMap`. [![GitHub Actions](https://github.com/tnballo/scapegoat/workflows/test/badge.svg?branch=master)](https://github.com/tnballo/scapegoat/actions)
*   [xfix/enum-map (⭐62)](https://github.com/xfix/enum-map) \[[enum-map](https://crates.io/crates/enum-map)] — An optimized map implementation for enums using an array to store values. [![build badge](https://api.travis-ci.org/xfix/enum-map.svg?branch=master)](https://travis-ci.org/xfix/enum-map)
*   [yamafaktory/hypergraph (⭐228)](https://github.com/yamafaktory/hypergraph) \[[hypergraph](https://crates.io/crates/hypergraph)] — Hypergraph is a data structure library to generate directed hypergraphs. [![ci](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml)

### Data visualization

*   [djduque/pgfplots (⭐81)](https://github.com/djduque/pgfplots) \[[pgfplots](https://crates.io/crates/pgfplots)] — A Rust library to generate publication-quality figures. [![build](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml/badge.svg)](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml)
*   [igiagkiozis/plotly (⭐684)](https://github.com/igiagkiozis/plotly) — Plotly for Rust.
*   [milliams/plotlib (⭐420)](https://github.com/milliams/plotlib) — [![build badge](https://api.travis-ci.org/milliams/plotlib.svg?branch=master)](https://travis-ci.org/milliams/plotlib)
*   [plotters (⭐2.7k)](https://github.com/plotters-rs/plotters) — [![build badge](https://github.com/plotters-rs/plotters/workflows/CI/badge.svg)](https://github.com/plotters-rs/plotters/actions)
*   [saresend/gust (⭐128)](https://github.com/saresend/Gust) — [![build badge](https://api.travis-ci.org/saresend/Gust.svg?branch=master)](https://travis-ci.org/saresend/Gust)

### Database

\[[database](https://crates.io/keywords/database)]

*   NoSQL \[[nosql](https://crates.io/keywords/nosql)]

    *   [ArangoDB](https://www.arangodb.com)
        *   [Aragog](https://gitlab.com/qonfucius/aragog) \[[aragog](https://crates.io/crates/aragog)] - A Lightweight ArangoDB Object document, relational and graph mapper [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
        *   [Arangors (⭐116)](https://github.com/fMeow/arangors) \[[arangors](https://crates.io/crates/arangors)] - An ArangoDB driver for Rust
    *   [Cassandra](https://cassandra.apache.org/_/index.html) \[[cassandra](https://crates.io/keywords/cassandra), [cql](https://crates.io/keywords/cql)]
        *   [AlexPikalov/cdrs (⭐338)](https://github.com/AlexPikalov/cdrs) \[[cdrs](https://crates.io/crates/cdrs)] — native client written in Rust [![build badge](https://api.travis-ci.org/AlexPikalov/cdrs.svg?branch=master)](https://travis-ci.org/AlexPikalov/cdrs)
        *   [krojew/cdrs-tokio (⭐73)](https://github.com/krojew/cdrs-tokio) \[[cdrs-tokio](https://crates.io/crates/cdrs-tokio)] - production-ready async Apache Cassandra driver written in pure Rust [![build badge](https://github.com/krojew/cdrs-tokio/actions/workflows/rust.yml/badge.svg)](https://github.com/krojew/cdrs-tokio/actions)
        *   [Metaswitch/cassandra-rs (⭐94)](https://github.com/Metaswitch/cassandra-rs) —  bindings to the DataStax C/C++ client [![build badge](https://api.travis-ci.org/Metaswitch/cassandra-rs.svg?branch=master)](https://travis-ci.org/Metaswitch/cassandra-rs)
    *   CouchDB \[[couchdb](https://crates.io/keywords/couchdb)]
        *   [chill-rs/chill (⭐35)](https://github.com/chill-rs/chill) \[[couchdb](https://crates.io/crates/chill)] — A Rust client for the CouchDB REST API [![build badge](https://api.travis-ci.org/chill-rs/chill.svg?branch=master)](https://travis-ci.org/chill-rs/chill)
    *   [DynamoDB](https://aws.amazon.com/dynamodb/) \[[dynamodb](https://crates.io/keywords/dynamodb)]
        *   [softprops/dynomite (⭐199)](https://github.com/softprops/dynomite) - A library for strongly-typed and convenient interaction with `rusoto_dynamodb` [![build badge](https://github.com/softprops/dynomite/workflows/Main/badge.svg?branch=master)](https://github.com/softprops/dynomite/actions)
    *   Elasticsearch \[[elasticsearch](https://crates.io/keywords/elasticsearch)]
        *   [benashford/rs-es (⭐218)](https://github.com/benashford/rs-es) \[[rs-es](https://crates.io/crates/rs-es)] — A Rust client for the [Elastic](https://www.elastic.co/) REST API [![build badge](https://api.travis-ci.org/benashford/rs-es.svg?branch=master)](https://travis-ci.org/benashford/rs-es)
        *   [elastic-rs/elastic (⭐249)](https://github.com/elastic-rs/elastic) \[[elastic](https://crates.io/crates/elastic)] — elastic is an efficient, modular API client for Elasticsearch written in Rust [![build badge](https://ci.appveyor.com/api/projects/status/csa78tcumdpnbur2?svg=true)](https://ci.appveyor.com/project/KodrAus/elastic)
    *   etcd
        *   [jimmycuadra/rust-etcd (⭐139)](https://github.com/jimmycuadra/rust-etcd) \[[etcd](https://crates.io/crates/etcd)] — A client library for CoreOS's etcd. [![build badge](https://api.travis-ci.org/jimmycuadra/rust-etcd.svg?branch=master)](https://travis-ci.org/jimmycuadra/rust-etcd)
        *   [lodrem/etcd-rs (⭐162)](https://github.com/lodrem/etcd-rs) — An asynchronous etcd client for rust [![CI](https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml)
    *   ForestDB
        *   [vhbit/sherwood (⭐8)](https://github.com/vhbit/sherwood) — [ForestDB (⭐1.2k)](https://github.com/couchbase/forestdb) bindings [![build badge](https://api.travis-ci.org/vhbit/sherwood.svg?branch=master)](https://travis-ci.org/vhbit/sherwood)
    *   [InfluxDB](https://www.influxdata.com/)
        *   [driftluo/InfluxDBClient-rs (⭐74)](https://github.com/driftluo/InfluxDBClient-rs) — Synchronization interface [![build badge](https://api.travis-ci.org/driftluo/InfluxDBClient-rs.svg?branch=master)](https://travis-ci.org/driftluo/InfluxDBClient-rs)
    *   LevelDB
        *   [skade/leveldb (⭐164)](https://github.com/skade/leveldb) — [LevelDB (⭐32k)](https://github.com/google/leveldb) bindings [![build badge](https://api.travis-ci.org/skade/leveldb.svg?branch=master)](https://travis-ci.org/skade/leveldb)
    *   LMDB \[[lmdb](https://crates.io/keywords/lmdb)]
        *   [vhbit/lmdb-rs (⭐105)](https://github.com/vhbit/lmdb-rs) \[[lmdb-rs](https://crates.io/crates/lmdb-rs)] — [LMDB](https://www.symas.com/symas-embedded-database-lmdb) bindings [![build badge](https://api.travis-ci.org/vhbit/lmdb-rs.svg?branch=master)](https://travis-ci.org/vhbit/lmdb-rs)
    *   MongoDB \[[mongodb](https://crates.io/keywords/mongodb)]
        *   [mongodb/mongo-rust-driver (⭐1.2k)](https://github.com/mongodb/mongo-rust-driver) \[[mongodb](https://crates.io/crates/mongodb)] — [MongoDB](https://www.mongodb.com/) bindings
    *   [PickleDB](https://pythonhosted.org/pickleDB/)
        *   [seladb/pickledb-rs (⭐158)](https://github.com/seladb/pickledb-rs) — a lightweight and simple key-value store, heavily inspired by Python's PickleDB. [![build badge](https://api.travis-ci.org/seladb/pickledb-rs.svg?branch=master)](https://travis-ci.org/seladb/pickledb-rs)
    *   [PoloDB](https://www.polodb.org/)
        *   [PoloDB (⭐435)](https://github.com/PoloDB/PoloDB) - An embedded JSON-based database has API similar to MongoDB. ![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/PoloDB/PoloDB/rust.yml)
    *   Redis \[[redis](https://crates.io/keywords/redis)]
        *   [aembke/fred (⭐118)](https://github.com/aembke/fred.rs) \[[fred](https://crates.io/crates/fred)] - A high level async [Redis](https://redis.io/) client for Rust with Tokio. [![CircleCI](https://circleci.com/gh/aembke/fred.rs/tree/main.svg?style=svg)](\[https://circleci.com/gh/aembke/fred.rs/tree/main]\(https://app.circleci.com/pipelines/github/aembke/fred.rs?branch=main\))
        *   [redis-rs (⭐2.8k)](https://github.com/redis-rs/redis-rs) — [Redis](https://redis.io/) library in Rust [![Rust](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml)
    *   [RocksDB](https://rocksdb.org/)
        *   [rust-rocksdb/rust-rocksdb (⭐1.4k)](https://github.com/rust-rocksdb/rust-rocksdb) — RocksDB bindings [![RocksDB CI](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml)
    *   [SurrealDB](https://surrealdb.com/)
        *   [surrealdb/surrealdb (⭐17k)](https://github.com/surrealdb/surrealdb) — SurrealDB embedded document-graph database
    *   [UnQLite](https://unqlite.org/)
        *   [zitsen/unqlite.rs (⭐101)](https://github.com/zitsen/unqlite.rs) — UnQLite bindings [![build badge](https://api.travis-ci.org/zitsen/unqlite.rs.svg?branch=master)](https://travis-ci.org/zitsen/unqlite.rs)
    *   [ZooKeeper](https://zookeeper.apache.org/)
        *   [bonifaido/rust-zookeeper (⭐171)](https://github.com/bonifaido/rust-zookeeper) \[[zookeeper](https://crates.io/crates/zookeeper)] — A client library for Apache ZooKeeper. [![build badge](https://api.travis-ci.org/bonifaido/rust-zookeeper.svg?branch=master)](https://travis-ci.org/bonifaido/rust-zookeeper)
        *   [krojew/rust-zookeeper (⭐16)](https://github.com/krojew/rust-zookeeper) \[[zookeeper-async](https://crates.io/crates/zookeeper-async)] - Async Zookeeper client written 100% in Rust, based on tokio.  ![build status](https://github.com/krojew/rust-zookeeper/actions/workflows/rust.yml/badge.svg)
*   OGM \[[ogm](https://crates.io/keywords/ogm)]
    *   [Aragog](https://gitlab.com/qonfucius/aragog) \[[aragog](https://crates.io/crates/aragog)] - A Lightweight ArangoDB Object document, relational and graph mapper [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
*   ORM \[[orm](https://crates.io/keywords/orm)]
    *   [Brendonovich/prisma-client-rust (⭐897)](https://github.com/Brendonovich/prisma-client-rust) — An autogenerated query builder that provides simple and fully type-safe database access using the Prisma ecosystem. [![Test Status](https://img.shields.io/github/workflow/status/Brendonovich/prisma-client-rust/CI?label=tests\&style=flat-square)](https://github.com/Brendonovich/prisma-client-rust/actions)
    *   [diesel-rs/diesel (⭐9.8k)](https://github.com/diesel-rs/diesel) — an ORM and Query builder for Rust [![Build Status](https://api.travis-ci.org/diesel-rs/diesel.svg?branch=master)](https://travis-ci.org/diesel-rs/diesel)
    *   [ivanceras/rustorm (⭐236)](https://github.com/ivanceras/rustorm) — an ORM for Rust [![Build Status](https://api.travis-ci.org/ivanceras/rustorm.svg?branch=master)](https://travis-ci.org/ivanceras/rustorm)
    *   [rbatis/rbatis (⭐1.7k)](https://github.com/rbatis/rbatis) — Rust ORM Framework High Performance(JSON based) [![Build Status](https://api.travis-ci.org/zhuxiujia/rbatis.svg?branch=master)](https://travis-ci.org/zhuxiujia/rbatis)
    *   [SeaQL/sea-orm (⭐3.6k)](https://github.com/SeaQL/sea-orm) — 🐚 An async & dynamic ORM for Rust [![Build Status](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml)
*   [sfackler/r2d2 (⭐1.2k)](https://github.com/sfackler/r2d2) — generic connection pool [![build badge](https://api.travis-ci.org/sfackler/r2d2.svg?branch=master)](https://travis-ci.org/sfackler/r2d2)
*   SQL \[[sql](https://crates.io/keywords/sql)]
    *   Generic
        *   [launchbadge/sqlx (⭐7.8k)](https://github.com/launchbadge/sqlx) - async PostgreSQL/MySQL/SQLite connection pool with strong typing support [![build badge](https://img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master?style=flat-square)](https://github.com/launchbadge/sqlx)
        *   [SeaQL/sea-query (⭐674)](https://github.com/SeaQL/sea-query) - 🔱 A dynamic SQL query builder for MySQL, Postgres and SQLite [![build status](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml)
        *   [SeaQL/sea-schema (⭐100)](https://github.com/SeaQL/sea-schema) - 🌿 SQL schema management suite [![build status](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml)
    *   Microsoft SQL
        *   [prisma/tiberius (⭐199)](https://github.com/prisma/tiberius) — [![Cargo tests](https://github.com/prisma/tiberius/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/prisma/tiberius/actions/workflows/test.yml)
    *   MySql \[[mysql](https://crates.io/keywords/mysql)]
        *   [AgilData/mysql-proxy-rs (⭐175)](https://github.com/AgilData/mysql-proxy-rs) — A MySQL Proxy [![CircleCI](https://circleci.com/gh/AgilData/mysql-proxy-rs/tree/master.svg?style=svg)](https://app.circleci.com/pipelines/github/AgilData/mysql-proxy-rs?branch=master)
        *   [blackbeam/mysql\_async (⭐294)](https://github.com/blackbeam/mysql_async) \[[mysql\_async](https://crates.io/crates/mysql_async)] — asyncronous Rust Mysql driver based on Tokio. [![CircleCI](https://circleci.com/gh/blackbeam/mysql_async/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/blackbeam/mysql_async?branch=master)
        *   [blackbeam/rust-mysql-simple (⭐552)](https://github.com/blackbeam/rust-mysql-simple) \[[mysql](https://crates.io/crates/mysql)] — A native MySql client [![build badge](https://api.travis-ci.org/blackbeam/rust-mysql-simple.svg?branch=master)](https://travis-ci.org/blackbeam/rust-mysql-simple)
    *   PostgreSql \[[postgres](https://crates.io/keywords/postgres), [postgresql](https://crates.io/keywords/postgresql)]
        *   [sfackler/rust-postgres (⭐2.8k)](https://github.com/sfackler/rust-postgres) \[[postgres](https://crates.io/crates/postgres)] — A native [PostgreSQL](https://www.postgresql.org/) client [![build badge](https://api.travis-ci.org/sfackler/rust-postgres.svg?branch=master)](https://travis-ci.org/sfackler/rust-postgres)
    *   Sqlite \[[sqlite](https://crates.io/keywords/sqlite)]
        *   [rusqlite (⭐1.9k)](https://github.com/rusqlite/rusqlite) — [Sqlite3](https://www.sqlite.org/index.html) bindings [![build badge](https://api.travis-ci.org/rusqlite/rusqlite.svg?branch=master)](https://travis-ci.org/rusqlite/rusqlite)

### Date and time

\[[date](https://crates.io/keywords/date), [time](https://crates.io/keywords/time)]

*   [chronotope/chrono (⭐2.5k)](https://github.com/chronotope/chrono) — [![build badge](https://api.travis-ci.org/chronotope/chrono.svg?branch=master)](https://travis-ci.org/chronotope/chrono)
*   [Mnwa/ms (⭐31)](https://github.com/Mnwa/ms) \[[ms-converter](https://crates.io/crates/ms-converter)] — it's a library for converting human-like times to milliseconds [![build badge](https://github.com/Mnwa/ms/workflows/build/badge.svg?branch=master)](https://github.com/Mnwa/ms/actions?query=workflow%3Abuild)
*   [time-rs/time (⭐697)](https://github.com/time-rs/time) — [![build badge](https://github.com/time-rs/time/workflows/Build/badge.svg)](https://github.com/time-rs/time/actions)

### Distributed systems

*   Antimony
    *   [antimonyproject/antimony (⭐62)](https://github.com/antimonyproject/antimony) \[[antimony](https://crates.io/crates/antimony)] — stream processing / distributed computation platform [![build badge](https://api.travis-ci.org/antimonyproject/antimony.svg?branch=master)](https://travis-ci.org/antimonyproject/antimony)
*   Apache Kafka
    *   [fede1024/rust-rdkafka (⭐1.1k)](https://github.com/fede1024/rust-rdkafka) \[[rdkafka](https://crates.io/crates/rdkafka)] — [librdkafka (⭐6.5k)](https://github.com/confluentinc/librdkafka) bindings [![build badge](https://api.travis-ci.org/fede1024/rust-rdkafka.svg?branch=master)](https://travis-ci.org/fede1024/rust-rdkafka)
    *   [gklijs/schema\_registry\_converter (⭐70)](https://github.com/gklijs/schema_registry_converter) \[[schema\_registry\_converter](https://crates.io/crates/schema_registry_converter)] — to integrate with [confluent schema registry](https://www.confluent.io/product/confluent-platform/data-compatibility/) [![build badge](https://api.travis-ci.org/gklijs/schema_registry_converter.svg?branch=master)](https://travis-ci.org/gklijs/schema_registry_converter)
    *   [kafka-rust/kafka-rust (⭐915)](https://github.com/kafka-rust/kafka-rust) — [![build badge](https://api.travis-ci.org/kafka-rust/kafka-rust.svg?branch=master)](https://travis-ci.org/kafka-rust/kafka-rust)
*   Beanstalkd
    *   [schickling/rust-beanstalkd (⭐44)](https://github.com/schickling/rust-beanstalkd) — [Beanstalkd (⭐6.3k)](https://github.com/beanstalkd/beanstalkd) bindings [![build badge](https://api.travis-ci.org/schickling/rust-beanstalkd.svg?branch=master)](https://travis-ci.org/schickling/rust-beanstalkd)
*   HDFS
    *   [hyunsik/hdfs-rs (⭐32)](https://github.com/hyunsik/hdfs-rs) \[[hdfs](https://crates.io/crates/hdfs)] — libhdfs bindings

### Domain driven design

*   [serverlesstechnology/cqrs (⭐167)](https://github.com/serverlesstechnology/cqrs) \[[cqrs-es](https://crates.io/crates/cqrs-es)] — A framework for CQRS and event sourcing with [user guide](https://doc.rust-cqrs.org/)

### Email

\[[email](https://crates.io/keywords/email), [imap](https://crates.io/keywords/imap), [smtp](https://crates.io/keywords/smtp)]

*   [gsquire/sendgrid-rs (⭐88)](https://github.com/gsquire/sendgrid-rs) — unofficial Rust library for SendGrid API [![build badge](https://api.travis-ci.org/gsquire/sendgrid-rs.svg?branch=master)](https://travis-ci.org/gsquire/sendgrid-rs)
*   [jdrouet/catapulte (⭐108)](https://github.com/jdrouet/catapulte) [![build badge](https://api.travis-ci.com/jdrouet/catapulte.svg?branch=main)](https://travis-ci.org/jdrouet/catapulte) - A microservice to send emails using [MRML (⭐231)](https://github.com/jdrouet/mrml) templates.
*   [jdrouet/jolimail (⭐106)](https://github.com/jdrouet/jolimail) [![pipeline status](https://gitlab.com/jeremie.drouet/jolimail/badges/main/pipeline.svg)](https://gitlab.com/jeremie.drouet/jolimail/-/commits/main) - A web application to build [MRML (⭐231)](https://github.com/jdrouet/mrml) templates.
*   [jdrouet/mrml (⭐231)](https://github.com/jdrouet/mrml) [![build badge](https://api.travis-ci.com/jdrouet/mrml.svg?branch=master)](https://travis-ci.org/jdrouet/mrml) - A library to generate nice email templates working on any mail client.
*   [lettre/lettre (⭐1.3k)](https://github.com/lettre/lettre) — an SMTP-library for Rust [![CI](https://github.com/lettre/lettre/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/lettre/lettre/actions/workflows/test.yml)
*   [staktrace/mailparse (⭐151)](https://github.com/staktrace/mailparse) \[[mailparse](https://crates.io/crates/mailparse)] — A library for parsing real-world email files [![build badge](https://api.travis-ci.org/staktrace/mailparse.svg?branch=master)](https://travis-ci.org/staktrace/mailparse)
*   [stalwartlabs/mail-parser (⭐158)](https://github.com/stalwartlabs/mail-parser) \[[mail-parser](https://crates.io/crates/mail-parser)] - A fast and robust e-mail parsing library with full MIME support [![build badge](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml)
*   [stalwartlabs/mail-send (⭐128)](https://github.com/stalwartlabs/mail-send) \[[mail-send](https://crates.io/crates/mail-send)] - E-mail builder and SMTP client library with DKIM support [![build badge](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml)

### Encoding

\[[encoding](https://crates.io/keywords/encoding)]

*   ASN.1
    *   [alex/rust-asn1 (⭐85)](https://github.com/alex/rust-asn1) — A Rust ASN.1 (DER) serializer [![build badge](https://api.travis-ci.org/alex/rust-asn1.svg?branch=master)](https://travis-ci.org/alex/rust-asn1)
*   Binary
    *   [bincode-org/bincode (⭐1.9k)](https://github.com/bincode-org/bincode) — A binary encoder/decoder in Rust [![CI](https://github.com/bincode-org/bincode/actions/workflows/rust.yml/badge.svg?branch=trunk)](https://github.com/bincode-org/bincode/actions/workflows/rust.yml)
    *   [m4b/goblin (⭐903)](https://github.com/m4b/goblin) \[[goblin](https://crates.io/crates/goblin)] —  cross-platform, zero-copy, and endian-aware binary parsing [![build badge](https://api.travis-ci.org/m4b/goblin.svg?branch=master)](https://travis-ci.org/m4b/goblin)
*   BSON
    *   [mongodb/bson-rust (⭐316)](https://github.com/mongodb/bson-rust) — Encoding and decoding support for BSON in Rust
*   Byte swapping
    *   [BurntSushi/byteorder (⭐821)](https://github.com/BurntSushi/byteorder) — Supports big-endian, little-endian and native byte orders [![build badge](https://api.travis-ci.org/BurntSushi/byteorder.svg?branch=master)](https://travis-ci.org/BurntSushi/byteorder)
*   Cap'n Proto
    *   [capnproto/capnproto-rust (⭐1.5k)](https://github.com/capnproto/capnproto-rust) — [![build badge](https://api.travis-ci.org/capnproto/capnproto-rust.svg?branch=master)](https://travis-ci.org/capnproto/capnproto-rust)
*   CBOR
    *   [serde\_cbor](https://crates.io/crates/serde_cbor) — CBOR support for serde [![build badge](https://api.travis-ci.org/pyfisch/cbor.svg?branch=master)](https://travis-ci.org/pyfisch/cbor)
*   Character Encoding
    *   [hsivonen/encoding\_rs (⭐287)](https://github.com/hsivonen/encoding_rs) \[[encoding\_rs](https://crates.io/crates/encoding_rs)] — A Gecko-oriented implementation of the Encoding Standard in Rust [![build badge](https://api.travis-ci.org/hsivonen/encoding_rs.svg?branch=master)](https://travis-ci.org/hsivonen/encoding_rs)
    *   [lifthrasiir/rust-encoding (⭐268)](https://github.com/lifthrasiir/rust-encoding) — [![build badge](https://api.travis-ci.org/lifthrasiir/rust-encoding.svg?branch=master)](https://travis-ci.org/lifthrasiir/rust-encoding)
*   CRC
    *   [mrhooray/crc-rs (⭐131)](https://github.com/mrhooray/crc-rs) — [![build badge](https://api.travis-ci.org/mrhooray/crc-rs.svg?branch=master)](https://travis-ci.org/mrhooray/crc-rs)
*   CSV
    *   [BurntSushi/rust-csv (⭐1.3k)](https://github.com/BurntSushi/rust-csv) — A fast and flexible CSV reader and writer, with support for Serde [![build badge](https://api.travis-ci.org/BurntSushi/rust-csv.svg?branch=master)](https://travis-ci.org/BurntSushi/rust-csv)
*   EDN
    *   [naomijub/edn-rs (⭐63)](https://github.com/naomijub/edn-rs) \[[edn-rs](https://crates.io/crates/edn-rs)] — crate to parse and emit EDN format into Rust types. [![Build Status](https://api.travis-ci.org/naomijub/edn-rs.svg?branch=master)](https://travis-ci.org/naomijub/edn-rs)
*   [FlatBuffers](https://google.github.io/flatbuffers/)
    *   [frol/flatc-rust (⭐88)](https://github.com/frol/flatc-rust) — FlatBuffers compiler (flatc) integration for Cargo build scripts [![build badge](https://api.travis-ci.org/frol/flatc-rust.svg?branch=master)](https://travis-ci.org/frol/flatc-rust)
*   HAR
    *   [mandrean/har-rs (⭐25)](https://github.com/mandrean/har-rs) \[[har](https://crates.io/crates/har)] — A HTTP Archive Format (HAR) serialization & deserialization library [![Build Status](https://api.travis-ci.org/mandrean/har-rs.svg?branch=master)](https://travis-ci.org/mandrean/har-rs)
*   HTML
    *   [servo/html5ever (⭐1.7k)](https://github.com/servo/html5ever) — High-performance browser-grade HTML5 parser [![build badge](https://api.travis-ci.com/servo/html5ever.svg?branch=master)](https://travis-ci.org/servo/html5ever)
*   JSON
    *   [importcjj/rust-ajson (⭐91)](https://github.com/importcjj/rust-ajson) [\[ajson\]](https://crates.io/crates/ajson) —  Get JSON values quickly [![build badge](https://api.travis-ci.com/importcjj/rust-ajson.svg?branch=master)](https://app.travis-ci.com/github/importcjj/rust-ajson)
    *   [maciejhirsz/json-rust (⭐506)](https://github.com/maciejhirsz/json-rust) \[[json](https://crates.io/crates/json)] — JSON implementation in Rust [![build badge](https://api.travis-ci.org/maciejhirsz/json-rust.svg?branch=master)](https://travis-ci.org/maciejhirsz/json-rust)
    *   [pikkr/pikkr (⭐616)](https://github.com/pikkr/pikkr) \[[pikkr](https://crates.io/crates/pikkr)] — JSON parser which picks up values directly without performing tokenization in Rust
    *   [serde-rs/json (⭐3.6k)](https://github.com/serde-rs/json) \[[serde\_json](https://crates.io/crates/serde_json)] — JSON support for [Serde (⭐6.6k)](https://github.com/serde-rs/serde) framework [![build badge](https://api.travis-ci.org/serde-rs/json.svg?branch=master)](https://travis-ci.org/serde-rs/json)
    *   [simd-lite/simd-json (⭐759)](https://github.com/simd-lite/simd-json) \[[simd-json](https://crates.io/crates/simd-json)] — High performance JSON parser based on a port of simdjson
*   MsgPack
    *   [3Hren/msgpack-rust (⭐847)](https://github.com/3Hren/msgpack-rust) — A pure Rust low/high level MessagePack implementation [![build badge](https://api.travis-ci.org/3Hren/msgpack-rust.svg?branch=master)](https://travis-ci.org/3Hren/msgpack-rust)
*   PEM
    *   [jcreekmore/pem-rs (⭐30)](https://github.com/jcreekmore/pem-rs) \[[pem](https://crates.io/crates/pem)] — A Rust based way to parse and encode PEM-encoded data [![build badge](https://api.travis-ci.org/jcreekmore/pem-rs.svg?branch=master)](https://travis-ci.org/jcreekmore/pem-rs)
*   ProtocolBuffers
    *   [stepancheg/rust-protobuf (⭐2.3k)](https://github.com/stepancheg/rust-protobuf) — [![build badge](https://api.travis-ci.org/stepancheg/rust-protobuf.svg?branch=master)](https://travis-ci.org/stepancheg/rust-protobuf)
    *   [tokio-rs/prost (⭐2.6k)](https://github.com/tokio-rs/prost) — [![continuous integration](https://github.com/tokio-rs/prost/workflows/continuous%20integration/badge.svg?branch=master)](https://github.com/tokio-rs/prost/actions)
*   rkyv
    *   [rkyv/rkyv (⭐1.7k)](https://github.com/rkyv/rkyv) \[[rkyv](https://crates.io/crates/rkyv)] — rkyv (archive) is a zero-copy deserialization framework for Rust
*   RON (Rusty Object Notation)
    *   [https://github.com/ron-rs/ron (⭐2.4k)](https://github.com/ron-rs/ron) — [![build badge](https://api.travis-ci.org/ron-rs/ron.svg?branch=master)](https://travis-ci.org/https://github.com/ron-rs/ron)
*   Serde
    *   [vityafx/serde-aux (⭐98)](https://github.com/vityafx/serde-aux/) - additional tools for using with the serde library. [![CI](https://github.com/vityafx/serde-aux/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/serde-aux/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/serde-aux.svg)](https://crates.io/crates/serde-aux)
*   TOML
    *   [tamasfe/taplo (⭐604)](https://github.com/tamasfe/taplo) \[[taplo](https://crates.io/crates/taplo)] — A TOML toolkit written in Rust [![CI](https://github.com/tamasfe/taplo/workflows/Continuous%20integration/badge.svg)](https://github.com/tamasfe/taplo/actions?query=workflow%3A%22Continuous+integration%22)
    *   [toml-rs/toml (⭐306)](https://github.com/toml-rs/toml) — [![CI](https://github.com/toml-rs/toml/actions/workflows/ci.yml/badge.svg)](https://github.com/toml-rs/toml/actions/workflows/ci.yml)
*   XML
    *   [Florob/RustyXML (⭐97)](https://github.com/Florob/RustyXML) — an XML parser written in Rust [![build badge](https://api.travis-ci.org/Florob/RustyXML.svg?branch=master)](https://travis-ci.org/Florob/RustyXML)
    *   [media-io/yaserde (⭐139)](https://github.com/media-io/yaserde) — Yet Another Serializer/Deserializer specialized for XML [![build badge](https://api.travis-ci.org/media-io/yaserde.svg?branch=master)](https://travis-ci.org/media-io/yaserde)
    *   [netvl/xml-rs (⭐421)](https://github.com/netvl/xml-rs) — A streaming XML library [![build badge](https://api.travis-ci.org/netvl/xml-rs.svg?branch=master)](https://travis-ci.org/netvl/xml-rs)
    *   [shepmaster/sxd-document (⭐147)](https://github.com/shepmaster/sxd-document) — An XML library in Rust [![build badge](https://api.travis-ci.org/shepmaster/sxd-document.svg?branch=master)](https://travis-ci.org/shepmaster/sxd-document)
    *   [shepmaster/sxd-xpath (⭐109)](https://github.com/shepmaster/sxd-xpath) — An XPath library in Rust [![build badge](https://api.travis-ci.org/shepmaster/sxd-xpath.svg?branch=master)](https://travis-ci.org/shepmaster/sxd-xpath)
    *   [tafia/quick-xml (⭐818)](https://github.com/tafia/quick-xml) — High performance XML pull reader/writer [![build badge](https://api.travis-ci.org/tafia/quick-xml.svg?branch=master)](https://travis-ci.org/tafia/quick-xml)
*   YAML
    *   [chyh1990/yaml-rust (⭐550)](https://github.com/chyh1990/yaml-rust) — The missing YAML 1.2 implementation for Rust. [![build badge](https://api.travis-ci.org/chyh1990/yaml-rust.svg?branch=master)](https://travis-ci.org/chyh1990/yaml-rust)
    *   [dtolnay/serde-yaml (⭐681)](https://github.com/dtolnay/serde-yaml) \[[serde\_yaml](https://crates.io/crates/serde_yaml)] — YAML support for [Serde (⭐6.6k)](https://github.com/serde-rs/serde) framework [![build](https://img.shields.io/github/workflow/status/dtolnay/serde-yaml/CI/master)](https://github.com/dtolnay/serde-yaml/actions?query=branch%3Amaster)
    *   [vitiral/stfu8 (⭐19)](https://github.com/vitiral/stfu8) \[[stfu8](https://crates.io/crates/stfu8)] — Sorta Text Format in UTF-8 [![build badge](https://api.travis-ci.org/vitiral/stfu8.svg?branch=master)](https://travis-ci.org/vitiral/stfu8)

### Filesystem

\[[filesystem](https://crates.io/keywords/filesystem)]

*   Operations
    *   [pop-os/dbus-udisks2 (⭐14)](https://github.com/pop-os/dbus-udisks2) \[[dbus-udisks2](https://crates.io/crates/dbus-udisks2)] - UDisks2 DBus API
    *   [pop-os/sys-mount (⭐32)](https://github.com/pop-os/sys-mount) \[[sys-mount](https://crates.io/crates/sys-mount)] — High level abstraction for the `mount` / `umount2` system calls.
    *   [vitiral/path\_abs (⭐45)](https://github.com/vitiral/path_abs) \[[path\_abs](https://crates.io/crates/path_abs)] — Absolute serializable path types and associated methods. [![build badge](https://api.travis-ci.org/vitiral/path_abs.svg?branch=master)](https://travis-ci.org/webdesus/fs_extr://travis-ci.org/vitiral/path_abs)
    *   [webdesus/fs\_extra (⭐165)](https://github.com/webdesus/fs_extra) — expanding opportunities standard library std::fs and std::io [![build badge](https://api.travis-ci.org/webdesus/fs_extra.svg?branch=master)](https://travis-ci.org/webdesus/fs_extra)
*   Temporary Files
    *   [Stebalien/tempfile (⭐794)](https://github.com/Stebalien/tempfile) — temporary file library [![build badge](https://api.travis-ci.org/Stebalien/tempfile.svg?branch=master)](https://travis-ci.org/Stebalien/tempfile)
    *   [Stebalien/xattr (⭐33)](https://github.com/Stebalien/xattr) \[[xattr](https://crates.io/crates/xattr)] — list and manipulate unix extended file attributes [![build badge](https://api.travis-ci.org/Stebalien/xattr.svg?branch=master)](https://travis-ci.org/Stebalien/xattr)
    *   [zboxfs/zbox (⭐1.4k)](https://github.com/zboxfs/zbox) \[[zbox](https://crates.io/crates/zbox)] — Zero-details, privacy-focused embeddable file system. [![build badge](https://api.travis-ci.org/zboxfs/zbox.svg?branch=master)](https://travis-ci.org/zboxfs/zbox)

### Functional Programming

\[[functional programming](https://crates.io/keywords/fp)]

*   Prelude
    *   [JasonShin/fp-core.rs (⭐1.1k)](https://github.com/JasonShin/fp-core.rs) — A library for functional programming in Rust
    *   [myrrlyn/tap (⭐221)](https://github.com/myrrlyn/tap) - Suffix-Position Pipeline Behavior

### Game development

See also [Are we game yet?](https://arewegameyet.rs)

*   Allegro
    *   [SiegeLord/RustAllegro (⭐80)](https://github.com/SiegeLord/RustAllegro) — [Allegro 5](https://liballeg.org/) bindings [![build badge](https://api.travis-ci.org/SiegeLord/RustAllegro.svg?branch=master)](https://travis-ci.org/SiegeLord/RustAllegro)
*   [Awesome Quads (⭐111)](https://github.com/ozkriff/awesome-quads) — A curated list of links to miniquad/macroquad-related code & resources
*   [Awesome wgpu (⭐292)](https://github.com/rofrol/awesome-wgpu) — A curated list of wgpu code and resources
*   bracket-lib (previously RLTK)
    *   [bracket-lib (⭐1.2k)](https://github.com/amethyst/bracket-lib) \[[bracket-lib](https://crates.io/crates/bracket-lib)] - The Roguelike Toolkit (RLTK), implemented for Rust. [![Rust](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml/badge.svg)](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml)
*   Challonge
    *   [vityafx/challonge-rs (⭐2)](https://github.com/vityafx/challonge-rs) \[[challonge](https://crates.io/crates/challonge)] — Client library for the Challonge REST API. Helps to organize tournaments. [![CI](https://github.com/vityafx/challonge-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/challonge-rs/actions/workflows/ci.yml)
*   Corange
    *   [lucidscape/corange-rs (⭐43)](https://github.com/lucidscape/corange-rs) — [Corange (⭐1.6k)](https://github.com/orangeduck/Corange) bindings
*   Entity-Component Systems (ECS)
    *   [amethyst/specs (⭐2.2k)](https://github.com/amethyst/specs) — Specs Parallel ECS [![build badge](https://api.travis-ci.org/amethyst/specs.svg?branch=master)](https://travis-ci.org/amethyst/specs)
    *   [legion (⭐1.4k)](https://github.com/amethyst/legion) — A feature rich high performance ECS library with minimal boilerplate [![build badge](https://github.com/amethyst/legion/workflows/CI/badge.svg?branch=master)](https://github.com/amethyst/legion/actions)
*   Game Engines
    *   [Bevy (⭐22k)](https://github.com/bevyengine/bevy) is a refreshingly simple data-driven game engine built in Rust. - [![Crates.io](https://img.shields.io/crates/v/bevy.svg)](https://crates.io/crates/bevy)
        [![Crates.io](https://img.shields.io/crates/d/bevy.svg)](https://crates.io/crates/bevy)
    *   [Fyrox](https://fyrox.rs/) — Rust Game engine 3D [![Crates.io](https://img.shields.io/crates/v/fyrox.svg)](https://crates.io/crates/fyrox) [![license](https://img.shields.io/crates/l/fyrox.svg)](https://github.com/FyroxEngine/Fyrox/blob/master/LICENSE.md) [![Crates.io](https://img.shields.io/crates/d/fyrox.svg)](https://crates.io/crates/fyrox)
    *   [ggez (⭐3.6k)](https://github.com/ggez/ggez) — A lightweight game framework for making 2D games with minimum friction - [![Crates.io](https://img.shields.io/crates/v/ggez.svg)](https://crates.io/crates/ggez) [![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ggez/ggez/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/ggez.svg)](https://crates.io/crates/ggez)
    *   [Kiss3d](http://kiss3d.org) — A Keep It Simple, Stupid 3d graphics engine written with Rust [![Crates.io](https://img.shields.io/crates/d/kiss3d.svg)](https://crates.io/crates/kiss3d)
    *   [oxidator (⭐262)](https://github.com/Ruddle/oxidator) — A real time strategy game/engine written with Rust and WebGPU
    *   [Piston](https://www.piston.rs/) — [![Crates.io](https://img.shields.io/crates/v/piston.svg?style=flat-square)](https://crates.io/crates/piston) [![Crates.io](https://img.shields.io/crates/l/piston.svg)](https://github.com/PistonDevelopers/piston/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/piston.svg)](https://crates.io/crates/piston)
    *   [Unrust (⭐369)](https://github.com/unrust/unrust) — unrust — A pure rust based (webgl 2.0 / native) game engine
*   [Godot](https://godotengine.org/)
    *   [godot-rust/gdnative (⭐3.2k)](https://github.com/godot-rust/gdnative) \[[gdnative](https://crates.io/crates/gdnative)] - Rust bindings to the Godot game engine [![CI](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml/badge.svg)](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml)
*   [Raylib](https://www.raylib.com/)
    *   [deltaphc/raylib-rs (⭐487)](https://github.com/deltaphc/raylib-rs) \[[raylib](https://crates.io/crates/raylib)] — Rust bindings for raylib
*   [SDL](http://www.libsdl.org/) \[[sdl](https://crates.io/keywords/sdl)]
    *   [brson/rust-sdl (⭐174)](https://github.com/brson/rust-sdl) — SDL1 bindings [![build badge](https://api.travis-ci.org/brson/rust-sdl.svg?branch=master)](https://travis-ci.org/brson/rust-sdl)
    *   [Rust-SDL2/rust-sdl2 (⭐2.2k)](https://github.com/Rust-SDL2/rust-sdl2) — SDL2 bindings [![build badge](https://api.travis-ci.org/Rust-SDL2/rust-sdl2.svg?branch=master)](https://travis-ci.org/Rust-SDL2/rust-sdl2)
*   SFML
    *   [jeremyletang/rust-sfml (⭐568)](https://github.com/jeremyletang/rust-sfml) — [SFML](https://www.sfml-dev.org/) bindings
*   Tcod-rs
    *   [tomassedovic/tcod-rs (⭐227)](https://github.com/tomassedovic/tcod-rs) — Libtcod bindings for Rust.
    *   Warning: Not maintained anymore
*   Toornament-rs
    *   [vityafx/toornament-rs (⭐3)](https://github.com/vityafx/toornament-rs) - Toornament.com API bindings for Rust. [![CI](https://github.com/vityafx/toornament-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/toornament-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/toornament.svg)](https://crates.io/crates/toornament)
*   Victorem
    *   [VictoremWinbringer/Victorem (⭐27)](https://github.com/VictoremWinbringer/Victorem) \[[Victorem](https://crates.io/crates/Victorem)] — Easy UDP Game Server and UDP Client framework for creating simple 2D and 3D online game prototype [![build badge](https://api.travis-ci.org/VictoremWinbringer/Victorem.svg?branch=master)](https://travis-ci.org/VictoremWinbringer/Victorem)

### Geospatial

\[[geo](https://crates.io/keywords/geo), [gis](https://crates.io/keywords/gis)]

*   [DaveKram/coord\_transforms (⭐25)](https://github.com/DaveKram/coord_transforms) \[[coord\_transforms](https://crates.io/crates/coord_transforms)] — coordinate transformations (2-d, 3-d, and geospatial) [![build badge](https://api.travis-ci.org/DaveKram/coord_transforms.svg?branch=master)](https://travis-ci.org/DaveKram/coord_transforms)
*   [Georust](https://github.com/georust) — geospatial tools and libraries written in Rust
*   [rust-reverse-geocoder (⭐96)](https://github.com/gx0r/rrgeo) — A fast, offline reverse geocoder in Rust, inspired by [thampiman/reverse-geocoder (⭐1.8k)](https://github.com/thampiman/reverse-geocoder)
*   [vlopes11/geomorph (⭐11)](https://github.com/vlopes11/geomorph) \[[geomorph](https://crates.io/crates/geomorph)] — conversion between UTM, LatLon and MGRS coordinates [![build badge](https://api.travis-ci.org/vlopes11/geomorph.svg?branch=master)](https://travis-ci.org/vlopes11/geomorph)

### Graph algorithms

*   [s1ck/graph (⭐231)](https://github.com/s1ck/graph) - A library for high-performant graph algorithms [![graph CI status](https://img.shields.io/github/workflow/status/s1ck/graph/CI/main?label=CI)](https://github.com/s1ck/graph/actions/workflows/rust.yml)

### Graphics

\[[graphics](https://crates.io/keywords/graphics)]

*   Font
    *   [RazrFalcon/rustybuzz (⭐323)](https://github.com/RazrFalcon/rustybuzz) - An incremental harfbuzz port to Rust [![build badge](https://api.travis-ci.org/RazrFalcon/rustybuzz.svg?branch=master)](https://travis-ci.org/RazrFalcon/rustybuzz)
    *   [redox-os/rusttype (⭐573)](https://github.com/redox-os/rusttype) — A pure Rust alternative to libraries like FreeType [![build badge](https://api.travis-ci.org/redox-os/rusttype.svg?branch=master)](https://travis-ci.org/redox-os/rusttype)
*   [gfx-rs/gfx (⭐5.2k)](https://github.com/gfx-rs/gfx) — A high-performance, bindless graphics API for Rust. [![build badge](https://api.travis-ci.org/gfx-rs/gfx.svg?branch=master)](https://travis-ci.org/gfx-rs/gfx)
*   [gfx-rs/wgpu (⭐6.6k)](https://github.com/gfx-rs/wgpu) - Native WebGPU implementation based on gfx-hal. [![build badge](https://github.com/gfx-rs/wgpu/workflows/CI/badge.svg?branch=master)](https://github.com/gfx-rs/wgpu/actions)
*   OpenGL \[[opengl](https://crates.io/keywords/opengl)]
    *   [brendanzab/gl-rs (⭐623)](https://github.com/brendanzab/gl-rs) — [![build badge](https://api.travis-ci.org/brendanzab/gl-rs.svg?branch=master)](https://travis-ci.org/brendanzab/gl-rs)
    *   [glium/glium (⭐3.1k)](https://github.com/glium/glium) — safe OpenGL wrapper for the Rust language. [![build badge](https://api.travis-ci.org/glium/glium.svg?branch=master)](https://travis-ci.org/glium/glium)
    *   [glutin](https://crates.io/crates/glutin) — Rust alternative to [GLFW](https://www.glfw.org/) [![build badge](https://api.travis-ci.org/rust-windowing/glutin.svg?branch=master)](https://travis-ci.org/rust-windowing/glutin)
    *   [Kiss3d](http://kiss3d.org) — draw simple geometric figures and play with them with one-liners [![build badge](https://api.travis-ci.org/sebcrozet/kiss3d.svg?branch=master)](https://api.travis-ci.org/repositories/sebcrozet/kiss3d)
    *   [PistonDevelopers/glfw-rs (⭐550)](https://github.com/PistonDevelopers/glfw-rs) — [![build badge](https://api.travis-ci.org/PistonDevelopers/glfw-rs.svg?branch=master)](https://travis-ci.org/PistonDevelopers/glfw-rs)
*   PDF
    *   [fschutt/printpdf (⭐598)](https://github.com/fschutt/printpdf) — PDF writing library [![build badge](https://api.travis-ci.org/fschutt/printpdf.svg?branch=master)](https://travis-ci.org/fschutt/printpdf)
    *   [J-F-Liu/lopdf (⭐1.1k)](https://github.com/J-F-Liu/lopdf) — PDF document manipulation [![build badge](https://api.travis-ci.org/J-F-Liu/lopdf.svg?branch=master)](https://travis-ci.org/J-F-Liu/lopdf)
    *   [kaj/rust-pdf (⭐129)](https://github.com/kaj/rust-pdf) — [![build badge](https://api.travis-ci.org/kaj/rust-pdf.svg?branch=master)](https://travis-ci.org/kaj/rust-pdf)
    *   [WASM-PDF (⭐383)](https://github.com/jussiniinikoski/wasm-pdf) – Generates PDF files with JavaScript and WASM (WebAssembly) [![build badge](https://api.travis-ci.org/jussiniinikoski/wasm-pdf.svg?branch=master)](https://travis-ci.org/jussiniinikoski/wasm-pdf)
*   [Vulkan](https://www.vulkan.org/) \[[vulkan](https://crates.io/keywords/vulkan)]
    *   [erupt](https://gitlab.com/Friz64/erupt) \[[erupt](https://crates.io/crates/erupt)] — [![build badge](https://gitlab.com/Friz64/erupt/badges/main/pipeline.svg)](https://gitlab.com/Friz64/erupt/-/pipelines)
    *   [vulkano (⭐3.6k)](https://github.com/vulkano-rs/vulkano) \[[vulkano](https://crates.io/crates/vulkano)] — [![build badge](https://api.travis-ci.org/vulkano-rs/vulkano.svg?branch=master)](https://travis-ci.org/vulkano-rs/vulkano)

### GUI

\[[gui](https://crates.io/keywords/gui)]

*   [autopilot-rs/autopilot-rs (⭐279)](https://github.com/autopilot-rs/autopilot-rs) — A simple, cross-platform GUI automation library for Rust.
*   Cocoa
    *   [servo/core-foundation-rs (⭐689)](https://github.com/servo/core-foundation-rs) — [![build badge](https://api.travis-ci.com/servo/core-foundation-rs.svg?branch=master)](https://travis-ci.org/servo/core-foundation-rs)
*   [DioxusLabs/dioxus (⭐6.9k)](https://github.com/dioxuslabs/dioxus) - a portable, performant, and ergonomic framework for building cross-platform user interfaces in Rust. ![rust ci](https://github.com/dioxuslabs/dioxus/actions/workflows/main.yml/badge.svg)
*   [emilk/egui (⭐13k)](https://github.com/emilk/egui) - Simple, fast, and highly portable immediate mode GUI library for Rust. egui runs on the web, natively, and in your favorite game engine. [![Build Status](https://github.com/emilk/egui/workflows/CI/badge.svg)](https://github.com/emilk/egui/actions?workflow=CI)
*   [emoon/rust\_minifb (⭐785)](https://github.com/emoon/rust_minifb) — minifb is a cross-platform window setup with optional bitmap rendering. It also comes with easy mouse and keyboard input. Primarily designed for prototyping
*   [FLTK](https://www.fltk.org/)
    *   [fltk-rs (⭐1.1k)](https://github.com/fltk-rs/fltk-rs) — FLTK Rust bindings [![Build](https://github.com/fltk-rs/fltk-rs/workflows/Build/badge.svg?branch=master)](https://github.com/fltk-rs/fltk-rs/actions)
*   [Flutter](https://flutter.dev/)
    *   [flutter-rs (⭐2k)](https://github.com/flutter-rs/flutter-rs) — Build flutter desktop app in dart & rust.
    *   [fzyzcjy/flutter\_rust\_bridge (⭐2.2k)](https://github.com/fzyzcjy/flutter_rust_bridge) — High-level memory-safe binding generator for Flutter/Dart <-> Rust
*   [fschutt/azul (⭐5.4k)](https://github.com/fschutt/azul) — A free, functional, IMGUI-oriented GUI framework for rapid development of desktop applications written in Rust, supported by the Mozilla WebRender rendering engine. [![build badge](https://api.travis-ci.org/fschutt/azul.svg?branch=master)](https://travis-ci.org/fschutt/azul)
*   [GTK+](https://www.gtk.org/) \[[gtk](https://crates.io/keywords/gtk)]
    *   [gtk-rs/gtk3-rs (⭐443)](https://github.com/gtk-rs/gtk3-rs) - GTK3 binding for rust ![CI](https://github.com/gtk-rs/gtk3-rs/workflows/CI/badge.svg)
    *   [relm (⭐2.3k)](https://github.com/antoyo/relm) — Asynchronous, GTK+-based, GUI library, inspired by Elm [![build badge](https://api.travis-ci.org/antoyo/relm.svg?branch=master)](https://travis-ci.org/antoyo/relm)
*   [iced-rs/iced (⭐18k)](https://github.com/iced-rs/iced) \[[iced](https://crates.io/crates/iced)] — A cross-platform GUI library for Rust focused on simplicity and type-safety. Inspired by Elm.
*   [ImGui (⭐45k)](https://github.com/ocornut/imgui)
    *   [imgui-rs (⭐2k)](https://github.com/imgui-rs/imgui-rs) — Rust bindings for ImGui [![Build Status](https://github.com/imgui-rs/imgui-rs/workflows/ci/badge.svg?branch=master)](https://github.com/imgui-rs/imgui-rs/actions)
*   [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
    *   [Kiss-ui (⭐342)](https://github.com/KISS-UI/kiss-ui) — A simple UI framework built on IUP [![Build Status](https://api.travis-ci.org/cybergeek94/kiss-ui.svg?branch=master)](https://travis-ci.org/cybergeek94/kiss-ui)
*   [ivanceras/sauron-native (⭐627)](https://github.com/ivanceras/sauron-native) - A truly native and cross platform GUI library. One unified code can be run as native GUI, Html Web and TUI. [![Build Status](https://api.travis-ci.com/ivanceras/sauron-native.svg?branch=master)](https://app.travis-ci.com/github/ivanceras/sauron-native)
*   [libui (⭐10k)](https://github.com/andlabs/libui)
    *   [rust-native-ui/libui-rs (⭐868)](https://github.com/rust-native-ui/libui-rs) — libui bindings [![build badge](https://api.travis-ci.org/rust-native-ui/libui-rs.svg?branch=master)](https://travis-ci.org/rust-native-ui/libui-rs).
*   [Nuklear (⭐6.9k)](https://github.com/Immediate-Mode-UI/Nuklear)
    *   [nuklear-rust (⭐335)](https://github.com/snuk182/nuklear-rust) — Rust bindings for Nuklear
*   [OrbTk (⭐3.7k)](https://github.com/redox-os/orbtk) — The Orbital Widget Toolkit is a multi platform (G)UI toolkit using SDL2 [![Build and test](https://github.com/redox-os/orbtk/workflows/build/badge.svg?branch=develop)](https://github.com/redox-os/orbtk/actions)
*   [PistonDevelopers/conrod (⭐3.3k)](https://github.com/PistonDevelopers/conrod/) — An easy-to-use, immediate-mode, 2D GUI library written entirely in Rust [![build badge](https://api.travis-ci.org/PistonDevelopers/conrod.svg?branch=master)](https://travis-ci.org/PistonDevelopers/conrod)
*   [Qt](https://doc.qt.io)
    *   [cyndis/qmlrs (⭐432)](https://github.com/cyndis/qmlrs) — QtQuick bindings [![build badge](https://api.travis-ci.org/cyndis/qmlrs.svg?branch=master)](https://travis-ci.org/cyndis/qmlrs)
    *   [rust-qt](https://github.com/rust-qt)
    *   [woboq/qmetaobject-rs (⭐499)](https://github.com/woboq/qmetaobject-rs) — Integrate Qml and Rust by building the QMetaObject at compile time. [![build badge](https://api.travis-ci.org/woboq/qmetaobject-rs.svg?branch=master)](https://travis-ci.org/woboq/qmetaobject-rs)
*   [rise-ui (⭐71)](https://github.com/rise-ui/rise) — Simple component-based cross-Platform GUI Toolkit for developing beautiful and user-friendly interfaces.
*   [saurvs/nfd-rs (⭐153)](https://github.com/saurvs/nfd-rs) — [nativefiledialog (⭐1.5k)](https://github.com/mlabbe/nativefiledialog) bindings
*   [Sciter](https://sciter.com/)
    *   [sciter-sdk/rust-sciter (⭐762)](https://github.com/sciter-sdk/rust-sciter) — Sciter bindings [![build badge](https://ci.appveyor.com/api/projects/status/github/sciter-sdk/rust-sciter?svg=true)](https://ci.appveyor.com/project/sciter-sdk/rust-sciter)
*   [slint-ui/slint (⭐5.6k)](https://github.com/slint-ui/slint) \[[slint](https://crates.io/crates/slint)] — [Slint](https://slint-ui.com) is a toolkit to efficiently develop fluid graphical user interfaces for embedded devices and desktop applications. [![Build Status](https://github.com/slint-ui/slint/workflows/CI/badge.svg?branch=master)](https://github.com/slint-ui/slint/actions?query=workflow%3ACI)
*   [tauri-apps/tauri (⭐58k)](https://github.com/tauri-apps/tauri) — Build smaller, faster, and more secure desktop applications with a web frontend, powered by [WRY (⭐2.2k)](https://github.com/tauri-apps/wry). [![test library](https://img.shields.io/github/workflow/status/tauri-apps/tauri/test%20library?label=test%20library)](https://github.com/tauri-apps/tauri/actions?query=workflow%3A%22test+library%22)
*   [tauri-apps/wry (⭐2.2k)](https://github.com/tauri-apps/wry) - Webview Rendering librarY.
*   [xilem (⭐816)](https://github.com/linebender/xilem) — Successor of the data-first Rust-native UI design toolkit [druid (⭐8.4k)](https://github.com/linebender/druid).

### Image processing

*   [abonander/img\_hash (⭐265)](https://github.com/abonander/img_hash) — Perceptual image hashing and comparison for equality and similarity. [![Build Status](https://api.travis-ci.org/abonander/img_hash.svg?branch=master)](https://travis-ci.org/abonander/img_hash)
*   [image-rs/image (⭐3.5k)](https://github.com/image-rs/image) — Basic imaging processing functions and methods for converting to and from image formats [![build badge](https://api.travis-ci.org/image-rs/image.svg?branch=master)](https://travis-ci.org/image-rs/image)
*   [image-rs/imageproc (⭐522)](https://github.com/image-rs/imageproc) — An image processing library, based on the `image` library. [![Build Status](https://api.travis-ci.org/image-rs/imageproc.svg?branch=master)](https://travis-ci.org/image-rs/imageproc)
*   [rust-cv/cv (⭐443)](https://github.com/rust-cv/cv) — Rust CV is a project to implement computer vision algorithms, abstractions, and systems in Rust. #\[no\_std] is supported where possible. ![build badge](https://github.com/rust-cv/cv/workflows/tests/badge.svg)
*   [teovoinea/steganography (⭐80)](https://github.com/teovoinea/steganography) \[[steganography](https://crates.io/crates/steganography)] — A simple steganography library [![build badge](https://api.travis-ci.org/teovoinea/steganography.svg?branch=master)](https://travis-ci.org/teovoinea/steganography)
*   [twistedfall/opencv-rust (⭐1.2k)](https://github.com/twistedfall/opencv-rust) — Rust bindings for OpenCV [![build badge](https://api.travis-ci.org/twistedfall/opencv-rust.svg?branch=cv2)](https://travis-ci.org/twistedfall/opencv-rust)

### Language specification

*   [shnewto/bnf (⭐191)](https://github.com/shnewto/bnf) — A library for parsing Backus–Naur form context-free grammars. [![build badge](https://api.travis-ci.org/shnewto/bnf.svg?branch=master)](https://travis-ci.org/shnewto/bnf)

### Logging

\[[log](https://crates.io/keywords/log)]

*   [estk/log4rs (⭐759)](https://github.com/estk/log4rs) — highly configurable logging framework modeled after Java's Logback and log4j libraries [![CircleCI](https://circleci.com/gh/estk/log4rs.svg?style=shield)](https://app.circleci.com/pipelines/github/estk/log4rs)
*   [jesusprubio/leg (⭐202)](https://github.com/jesusprubio/leg) — Elegant print for lazy devs. Make your CLIs nicer with minimal effort. [![Build Status](https://github.com/jesusprubio/leg/workflows/CI/badge.svg)](https://github.com/jesusprubio/leg/actions/workflows/ci.yml)
*   [rbatis/fast\_log (⭐111)](https://github.com/rbatis/fast_log) — Rust async log High-performance asynchronous logging [![Build Status](https://api.travis-ci.com/rbatis/fast_log.svg?branch=master)](https://travis-ci.org/rbatis/fast_log)
*   [rust-lang/log (⭐1.6k)](https://github.com/rust-lang/log) — Logging implementation for Rust [![Build Status](https://api.travis-ci.org/rust-lang/log.svg?branch=master)](https://travis-ci.org/rust-lang/log)
*   [seanmonstar/pretty-env-logger (⭐391)](https://github.com/seanmonstar/pretty-env-logger) — A pretty, easy-to-use logger for Rust. [![Build Status](https://api.travis-ci.org/seanmonstar/pretty-env-logger.svg?branch=master)](https://travis-ci.org/seanmonstar/pretty-env-logger)
*   [slog-rs/slog (⭐1.4k)](https://github.com/slog-rs/slog) — Structured, composable logging for Rust [![Build Status](https://api.travis-ci.org/slog-rs/slog.svg?branch=master)](https://travis-ci.org/slog-rs/slog)
*   [tokio-rs/tracing (⭐3.4k)](https://github.com/tokio-rs/tracing) — An application level tracing framework for async-aware structured logging, error handling, metrics, and more [![Build Status](https://github.com/tokio-rs/tracing/workflows/CI/badge.svg?branch=master)](https://github.com/tokio-rs/tracing/actions?query=workflow%3ACI)

### Macro

*   cute
    *   [mattgathu/cute (⭐308)](https://github.com/mattgathu/cute) — Macro for Python-esque list comprehensions in Rust. [![Build Status](https://api.travis-ci.org/mattgathu/cute.svg?branch=master)](https://travis-ci.org/tensorflow/rust)
*   [Linq-in-Rust (⭐93)](https://github.com/StardustDL/Linq-in-Rust) - Macro and methods for C#-LINQ-like expressions. [![CI](https://github.com/StardustDL/Linq-in-Rust/workflows/CI/badge.svg?branch=master)](https://github.com/StardustDL/Linq-in-Rust/actions?query=workflow%3ACI)

### Markup language

*   CommonMark
    *   [raphlinus/pulldown-cmark (⭐1.5k)](https://github.com/raphlinus/pulldown-cmark) — [CommonMark](https://commonmark.org/) parser in Rust

### Mobile

*   Android / iOS
    *   [ivanschuetz/rust\_android\_ios (⭐194)](https://github.com/ivanschuetz/rust_android_ios) — An example of using a shared Rust lib for Android and iOS using rust-swig and cbindgen respectively.
*   Generic
    *   [Geal/rust\_on\_mobile (⭐159)](https://github.com/Geal/rust_on_mobile)
*   iOS
    *   [TimNN/cargo-lipo (⭐437)](https://github.com/TimNN/cargo-lipo) — A cargo lipo subcommand which automatically creates a universal library for use with your iOS application. [![build badge](https://api.travis-ci.org/TimNN/cargo-lipo.svg?branch=master)](https://travis-ci.org/TimNN/cargo-lipo)

### Network programming

*   Bluetooth
    *   [bluez/bluer (⭐124)](https://github.com/bluez/bluer) \[[bluer](https://crates.io/crates/bluer)] — Official BlueZ bindings for Rust. [![build badge](https://github.com/bluez/bluer/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/bluez/bluer/actions/workflows/rust.yml)
*   CoAP
    *   [Covertness/coap-rs (⭐171)](https://github.com/Covertness/coap-rs) — A [Constrained Application Protocol(CoAP)](https://datatracker.ietf.org/doc/html/rfc7252) library for Rust. [![build badge](https://api.travis-ci.org/Covertness/coap-rs.svg?branch=master)](https://travis-ci.org/Covertness/coap-rs)
*   Docker
    *   [fussybeaver/bollard (⭐449)](https://github.com/fussybeaver/bollard) — Docker daemon API in Rust
*   FTP
    *   [mattnenterprise/rust-ftp (⭐158)](https://github.com/mattnenterprise/rust-ftp) — an [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol) client for Rust [![build badge](https://api.travis-ci.org/mattnenterprise/rust-ftp.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-ftp)
*   gRPC
    *   [tikv/grpc-rs (⭐1.6k)](https://github.com/tikv/grpc-rs) — The gRPC library for Rust built on C Core library and futures [![Build Status](https://api.travis-ci.org/tikv/grpc-rs.svg?branch=master)](https://travis-ci.org/tikv/grpc-rs)
*   HTTP
    *   [Hurl (⭐3.7k)](https://github.com/Orange-OpenSource/hurl) — Run and test HTTP requests with plain text and libcurl [![CI](https://github.com/Orange-OpenSource/hurl/workflows/CI/badge.svg)](https://github.com/Orange-OpenSource/hurl/actions)
*   IPNetwork
    *   [achanda/ipnetwork (⭐100)](https://github.com/achanda/ipnetwork) — A library to work with IP networks in pure Rust [![build badge](https://api.travis-ci.org/achanda/ipnetwork.svg?branch=master)](https://travis-ci.org/achanda/ipnetwork)
    *   [candrew/netsim (⭐117)](https://github.com/canndrew/netsim) — A Rust library for network simulation and testing [![build badge](https://api.travis-ci.org/canndrew/netsim.svg?branch=master)](https://travis-ci.org/canndrew/netsim)
    *   [jesusprubio/online (⭐122)](https://github.com/jesusprubio/online) — Library to check your Internet connectivity [![CI](https://github.com/jesusprubio/online/actions/workflows/ci.yml/badge.svg)](https://github.com/jesusprubio/online/actions/workflows/ci.yml)
*   Low level
    *   [actix/actix (⭐7.7k)](https://github.com/actix/actix) — Actor library for Rust [![build badge](https://api.travis-ci.org/actix/actix.svg?branch=master)](https://travis-ci.org/actix/actix)
    *   [dylanmckay/protocol (⭐158)](https://github.com/dylanmckay/protocol) — Custom TCP/UDP protocol definitions
    *   [libpnet/libpnet (⭐1.8k)](https://github.com/libpnet/libpnet) — A cross-platform, low level networking [![build badge](https://api.travis-ci.org/libpnet/libpnet.svg?branch=master)](https://travis-ci.org/libpnet/libpnet)
    *   [smoltcp-rs/smoltcp (⭐2.9k)](https://github.com/smoltcp-rs/smoltcp) — A standalone, event-driven TCP/IP stack that is designed for bare-metal, real-time systems [![build badge](https://api.travis-ci.org/smoltcp-rs/smoltcp.svg?branch=master)](https://travis-ci.org/smoltcp-rs/smoltcp)
    *   [tokio-rs/tokio (⭐19k)](https://github.com/tokio-rs/tokio) — A network application framework for rapid development and highly scalable production deployments of clients and servers.
*   message-io
    *   [lemunozm/message-io (⭐839)](https://github.com/lemunozm/message-io) — Event-driven message library to build network applications easy and fast. Supports TCP, UDP and WebSockets. [![build badge](https://img.shields.io/github/workflow/status/lemunozm/message-io/message-io%20ci)](https://github.com/lemunozm/message-io/actions?query=workflow%3A%22message-io+ci%22)
*   MQTT
    *   [bytebeamio/rumqtt (⭐853)](https://github.com/bytebeamio/rumqtt) - A library for developers to build applications that communicate with the [MQTT protocol](https://mqtt.org) over TCP and WebSockets, with or without TLS. [![Build and Test](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml/badge.svg)](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml)
*   NanoMsg
    *   [thehydroimpulse/nanomsg.rs (⭐370)](https://github.com/thehydroimpulse/nanomsg.rs) — [nanomsg](https://nanomsg.org/) bindings [![build badge](https://api.travis-ci.org/thehydroimpulse/nanomsg.rs.svg?branch=master)](https://travis-ci.org/thehydroimpulse/nanomsg.rs)
*   NATS
    *   [nats-io/nats.rs (⭐664)](https://github.com/nats-io/nats.rs) — Rust client for NATS, the cloud native messaging system. [![Build Status](https://github.com/nats-io/nats.rs/workflows/Rust/badge.svg?branch=master)](https://github.com/nats-io/nats.rs/actions)
*   Nng
    *   [neachdainn/nng-rs](https://gitlab.com/neachdainn/nng-rs) \[[Nng](https://crates.io/crates/nng)] — [Nng (nanomsg v2)](https://nng.nanomsg.org/index.html) bindings [![build badge](https://gitlab.com/neachdainn/nng-rs/badges/master/pipeline.svg)](https://gitlab.com/neachdainn/nng-rs/-/pipelines)
*   NNTP
    *   [mattnenterprise/rust-nntp (⭐13)](https://github.com/mattnenterprise/rust-nntp) \[[nntp](https://crates.io/crates/nntp)] — an [NNTP](https://en.wikipedia.org/wiki/Network_News_Transfer_Protocol) client for Rust [![build badge](https://api.travis-ci.org/mattnenterprise/rust-nntp.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-nntp)
*   P2P
    *   [libp2p/rust-libp2p (⭐3k)](https://github.com/libp2p/rust-libp2p) — The Rust Implementation of libp2p networking stack. [![Circle CI](https://circleci.com/gh/libp2p/rust-libp2p.svg?style=svg)](https://app.circleci.com/pipelines/github/libp2p/rust-libp2p)
*   POP3
    *   [mattnenterprise/rust-pop3 (⭐27)](https://github.com/mattnenterprise/rust-pop3) \[[pop3](https://crates.io/crates/pop3)] — A [POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol) client for Rust [![build badge](https://api.travis-ci.org/mattnenterprise/rust-pop3.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-pop3)
*   QUIC
    *   [cloudflare/quiche (⭐7.1k)](https://github.com/cloudflare/quiche) — cloudflare implementation of the QUIC transport protocol and HTTP/3 ![build](https://img.shields.io/github/workflow/status/cloudflare/quiche/Stable)
    *   [mozilla/neqo (⭐1.6k)](https://github.com/mozilla/neqo) — an Implementation of QUIC written in Rust
    *   [quinn-rs/quinn (⭐2.6k)](https://github.com/quinn-rs/quinn) — Futures-based QUIC implementation in Rust [![build badge](https://dev.azure.com/dochtman/Projects/_apis/build/status/Quinn?branchName=master)](https://dev.azure.com/dochtman/Projects/_build)
*   Raknet
    *   [b23r0/rust-raknet (⭐166)](https://github.com/b23r0/rust-raknet) — RakNet Protocol implementation by Rust [![Build Status](https://img.shields.io/github/workflow/status/b23r0/rust-raknet/Rust)](https://github.com/b23r0/rust-raknet/actions/workflows/rust.yml)
*   RPC
    *   [ENQT-GmbH/remoc (⭐101)](https://github.com/ENQT-GmbH/remoc) \[[remoc](https://crates.io/crates/remoc)] - Remoc provides channels (broadcast, mpsc, oneshot, watch) similar to Tokio's and trait calling over any remote transport. [![build badge](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml)
    *   [smallnest/rpcx-rs (⭐106)](https://github.com/smallnest/rpcx-rs) — A RPC library for Rust for developing microservices in easy and simple way. [![build badge](https://api.travis-ci.org/smallnest/rpcx-rs.svg?branch=master)](https://travis-ci.org/smallnest/rpcx-rs)
*   Socket.io
    *   [1c3t3a/rust-socketio (⭐194)](https://github.com/1c3t3a/rust-socketio) \[[rust\_socketio](https://crates.io/crates/rust_socketio)] — an implementation of a [socket.io](https://socket.io) client written in Rust. [![build badge](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml/badge.svg)](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml)
*   SSH
    *   [alexcrichton/ssh2-rs (⭐371)](https://github.com/alexcrichton/ssh2-rs) — [libssh2](https://www.libssh2.org/) bindings [![build badge](https://api.travis-ci.com/alexcrichton/ssh2-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/ssh2-rs)
    *   [Thrussh](https://pijul.org/thrussh) \[[thrussh](https://crates.io/crates/thrussh)] — an SSH library written from scratch in Rust, backed by [libsodium](https://doc.libsodium.org/)
*   Stomp
    *   [zslayton/stomp-rs (⭐84)](https://github.com/zslayton/stomp-rs) — A [STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html) client implementation in Rust [![build badge](https://api.travis-ci.org/zslayton/stomp-rs.svg?branch=master)](https://travis-ci.org/zslayton/stomp-rs)
*   ZeroMQ
    *   [erickt/rust-zmq (⭐747)](https://github.com/erickt/rust-zmq) — [ZeroMQ](https://zeromq.org/) bindings [![build badge](https://api.travis-ci.org/erickt/rust-zmq.svg?branch=master)](https://travis-ci.org/erickt/rust-zmq)

### Parsing

*   [comex/rust-shlex (⭐51)](https://github.com/comex/rust-shlex) \[[shlex](https://crates.io/crates/shlex)] — Split a string into shell words, like Python's shlex. [![build badge](https://github.com/comex/rust-shlex/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/comex/rust-shlex/actions/workflows/test.yml)
*   [Folyd/robotstxt (⭐74)](https://github.com/Folyd/robotstxt) - A native Rust port of Google's robots.txt parser and matcher C++ library
*   [freestrings/jsonpath (⭐97)](https://github.com/freestrings/jsonpath) — [JsonPath](https://goessner.net/articles/JsonPath/) engine written in Rust. Webassembly and Javascript support too [![Build Status](https://api.travis-ci.org/freestrings/jsonpath.svg?branch=master)](https://travis-ci.org/freestrings/jsonpath)
*   [hmeyer/stl\_io](https://crates.io/crates/stl_io) - A parser for STL (STereoLithography) files
*   [kevinmehall/rust-peg (⭐1.2k)](https://github.com/kevinmehall/rust-peg) — Parsing Expression Grammar (PEG) parser generator
*   [lalrpop/lalrpop (⭐2.4k)](https://github.com/lalrpop/lalrpop) — LR(1) parser generator for Rust [![Build status](https://api.travis-ci.org/lalrpop/lalrpop.svg?branch=master)](https://travis-ci.org/lalrpop/lalrpop)
*   [m4rw3r/chomp (⭐230)](https://github.com/m4rw3r/chomp) – A fast monadic-style parser combinator [![build badge](https://api.travis-ci.org/m4rw3r/chomp.svg?branch=master)](https://travis-ci.org/m4rw3r/chomp)
*   [Marwes/combine (⭐1.1k)](https://github.com/Marwes/combine) — parser combinator library [![build badge](https://api.travis-ci.org/Marwes/combine.svg?branch=master)](https://travis-ci.org/Marwes/combine)
*   [nrc/zero (⭐45)](https://github.com/nrc/zero) \[[zero](https://crates.io/crates/zero/)] — zero-allocation parsing of binary data
*   [pest-parser/pest (⭐3.5k)](https://github.com/pest-parser/pest) — The Elegant Parser [![Build Status](https://api.travis-ci.org/pest-parser/pest.svg?branch=master)](https://travis-ci.org/pest-parser/pest)
*   [ptal/oak (⭐138)](https://github.com/ptal/oak) — A typed PEG parser generator (compiler plugin)
*   [replicadse/wavefront\_rs (⭐4)](https://github.com/replicadse/wavefront_rs) — A parser for the Wavefront OBJ format. [![crates.io](https://img.shields.io/crates/v/wavefront_rs.svg)](https://crates.io/crates/wavefront_rs) [![crates.io](https://img.shields.io/crates/d/wavefront_rs?label=crates.io%20downloads)](https://crates.io/crates/wavefront_rs) [![build badge](https://github.com/replicadse/wavefront_rs/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/wavefront_rs/actions)
*   [rust-bakery/nom (⭐7.6k)](https://github.com/rust-bakery/nom) — parser combinator library [![build badge](https://api.travis-ci.org/rust-bakery/nom.svg?branch=master)](https://travis-ci.org/rust-bakery/nom)
*   [s-panferov/queryst (⭐67)](https://github.com/s-panferov/queryst) — A query string parsing library for Rust inspired by [gs (⭐7.6k)](https://github.com/ljharb/qs#readme)
*   [softdevteam/grmtools (⭐349)](https://github.com/softdevteam/grmtools/) - A LR parser with better error correction

### Peripherals

*   Serial Port
    *   [serialport/serialport-rs (⭐137)](https://github.com/serialport/serialport-rs) \[[serialport](https://crates.io/crates/serialport)] — A cross-platform library that provides access to a serial port

### Platform specific

*   Cross-platform
    *   [svartalf/rust-battery](https://crates.io/crates/battery) — Cross-platform information about the notebook batteries [![build badge](https://api.travis-ci.org/svartalf/rust-battery.svg?branch=master)](https://travis-ci.org/svartalf/rust-battery)
    *   [vityafx/thread-priority (⭐63)](https://github.com/vityafx/thread-priority/) - Simple, crossplatform thread priority management. [![CI](https://github.com/vityafx/thread-priority/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/thread-priority/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/thread-priority.svg)](https://crates.io/crates/thread-priority)
*   FreeBSD
    *   [fubarnetes/libjail-rs (⭐40)](https://github.com/fubarnetes/libjail-rs/) \[[jail](https://crates.io/crates/jail)] — Rust implementation of a FreeBSD jail library
*   Linux
    *   [hannobraun/inotify-rs (⭐220)](https://github.com/hannobraun/inotify-rs) — [inotify](https://en.wikipedia.org/wiki/Inotify) bindings [![Rust](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml)
    *   [pop-os/distinst (⭐201)](https://github.com/pop-os/distinst/) — Linux distribution installer
    *   [yaa110/rust-iptables (⭐66)](https://github.com/yaa110/rust-iptables) \[[iptables](https://crates.io/crates/iptables)] — [iptables](https://www.netfilter.org/projects/iptables/index.html) bindings [![build badge](https://api.travis-ci.org/yaa110/rust-iptables.svg?branch=master)](https://travis-ci.org/yaa110/rust-iptables)
*   Unix-like
    *   [nix-rust/nix (⭐2.1k)](https://github.com/nix-rust/nix) — Unix-like API bindings [![Cirrus Build Status](https://api.cirrus-ci.com/github/nix-rust/nix.svg)](https://cirrus-ci.com/github/nix-rust/nix)
    *   [rustix (⭐754)](https://github.com/bytecodealliance/rustix) — Safe Rust bindings to POSIX/Unix/Linux/Winsock2 syscalls [![Actions Status](https://github.com/bytecodealliance/rustix/workflows/CI/badge.svg)](https://github.com/bytecodealliance/rustix/actions?query=workflow%3ACI)
    *   [zargony/fuse-rs (⭐919)](https://github.com/zargony/fuse-rs) — [FUSE (⭐4.3k)](https://github.com/libfuse/libfuse) bindings
*   Windows
    *   [retep998/winapi-rs (⭐1.6k)](https://github.com/retep998/winapi-rs) — Windows API bindings [![Rust](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml/badge.svg?branch=dev)](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml)

### Scripting

\[[scripting](https://crates.io/keywords/scripting)]

*   [duckscript](https://crates.io/crates/duckscript) — [Simple, extendable and embeddable scripting language. (⭐368)](https://github.com/sagiegurari/duckscript) [![build badge](https://github.com/sagiegurari/duckscript/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/duckscript/actions)
*   [fleabitdev/gamelisp (⭐352)](https://github.com/fleabitdev/glsp) — A Lisp-like scripting language for Rust game development
*   [gluon-lang/gluon (⭐2.7k)](https://github.com/gluon-lang/gluon) —  A small, statically-typed, functional programming language
*   [KusionStack/KCLVM (⭐326)](https://github.com/KusionStack/KCLVM) - A constraint-based record & functional language mainly used in configuration and policy scenarios.
*   [metacall/core (⭐1.2k)](https://github.com/metacall/core) \[[metacall](https://crates.io/crates/metacall)] — Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, Wasm, Java, Cobol and more. [![build badge](https://gitlab.com/metacall/core/badges/master/pipeline.svg)](https://gitlab.com/metacall/core)
*   [mun (⭐1.5k)](https://github.com/mun-lang/mun) — A compiled, statically-typed scripting language with first class hot reloading support [![build badge](https://api.travis-ci.org/mun-lang/mun.svg?branch=master)](https://travis-ci.org/mun-lang/mun)
*   [murarth/ketos (⭐720)](https://github.com/murarth/ketos) — A Lisp dialect functional programming language serving as a scripting and extension language for rust
*   [PistonDevelopers/dyon (⭐1.5k)](https://github.com/PistonDevelopers/dyon) — A rusty dynamically typed scripting language
*   [rhaiscript/rhai (⭐2.5k)](https://github.com/rhaiscript/rhai) — A tiny and fast embedded scripting language resembling a combination of JavaScript and Rust [![build badge](https://github.com/rhaiscript/rhai/workflows/Build/badge.svg)](https://github.com/rhaiscript/rhai/actions)
*   [rune-rs/rune (⭐1.1k)](https://github.com/rune-rs/rune) — An embeddable dynamic programming language for Rust

### Simulation

\[[simulation](https://crates.io/keywords/simulation)]

*   [nyx-space](https://crates.io/crates/nyx-space) - High fidelity, fast, reliable and validated astrodynamical toolkit library, used for spacecraft mission design and orbit determination [![Build Status](https://gitlab.com/nyx-space/nyx/badges/master/pipeline.svg)](https://gitlab.com/nyx-space/nyx/-/pipelines)

### System

*   [ardaku/whoami (⭐77)](https://github.com/ardaku/whoami) \[[whoami](https://crates.io/crates/whoami)] — Rust crate to get the current user and environment. [![build badge](https://github.com/ardaku/whoami/actions/workflows/ci.yml/badge.svg?branch=stable)](https://github.com/ardaku/whoami/actions/workflows/ci.yml)
*   [GuillaumeGomez/sysinfo (⭐1.2k)](https://github.com/GuillaumeGomez/sysinfo) \[[sysinfo](https://crates.io/crates/sysinfo)] — Cross-platform library to fetch system information [![build badge](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml/badge.svg?branch=master)](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml)
*   [Phate6660/nixinfo (⭐38)](https://github.com/Phate6660/nixinfo) \[[nixinfo](https://crates.io/crates/nixinfo)] — A lib crate for gathering system info such as cpu, distro, environment, kernel, etc.

### Task scheduling

*   [delay-timer (⭐258)](https://github.com/BinChengZhao/delay-timer) — Time-manager of delayed tasks. Like crontab, but asynchronous tasks are possible.
    [![Build](https://github.com/BinChengZhao/delay-timer/actions/workflows/rust.yml/badge.svg)](https://github.com/BinChengZhao/delay-timer/actions)

### Template engine

*   Handlebars
    *   [botika/yarte (⭐252)](https://github.com/botika/yarte) — Yarte stands for **Y**et **A**nother **R**ust **T**emplate **E**ngine, is the fastest template engine. [![Build Status](https://api.travis-ci.org/botika/yarte.svg?branch=master)](https://travis-ci.org/botika/yarte)
    *   [sunng87/handlebars-rust (⭐943)](https://github.com/sunng87/handlebars-rust) — Handlebars template engine with inheritance, custom helper support. [![build badge](https://api.travis-ci.org/sunng87/handlebars-rust.svg?branch=master)](https://travis-ci.org/sunng87/handlebars-rust)
*   HTML
    *   [djc/askama (⭐2k)](https://github.com/djc/askama) — template rendering engine based on Jinja [![build badge](https://api.travis-ci.org/djc/askama.svg?branch=master)](https://travis-ci.org/djc/askama)
    *   [kaj/ructe (⭐348)](https://github.com/kaj/ructe) — HTML template system for Rust [![build badge](https://api.travis-ci.org/kaj/ructe.svg?branch=master)](https://travis-ci.org/kaj/ructe)
    *   [Keats/tera (⭐2.5k)](https://github.com/Keats/tera) — template engine based on Jinja2 and the Django template language. [![Actions Status](https://github.com/Keats/tera/workflows/ci/badge.svg?branch=master)](https://github.com/Keats/tera/actions)
    *   [lambda-fairy/maud (⭐1.4k)](https://github.com/lambda-fairy/maud) — compile-time HTML templates [![build badge](https://api.travis-ci.org/lambda-fairy/maud.svg?branch=master)](https://travis-ci.org/lambda-fairy/maud)
    *   [Stebalien/horrorshow-rs (⭐268)](https://github.com/Stebalien/horrorshow-rs) — compile-time HTML templates [![build badge](https://api.travis-ci.org/Stebalien/horrorshow-rs.svg?branch=master)](https://travis-ci.org/Stebalien/horrorshow-rs)
*   Mustache
    *   [rustache/rustache (⭐209)](https://github.com/rustache/rustache) — [![build badge](https://api.travis-ci.org/rustache/rustache.svg?branch=master)](https://travis-ci.org/rustache/rustache)

### Text processing

*   [becheran/wildmatch (⭐41)](https://github.com/becheran/wildmatch) \[[wildmatch](https://crates.io/crates/wildmatch)] — Simple string matching with questionmark- and star-wildcard operator [![Actions Status](https://github.com/becheran/wildmatch/workflows/Build/badge.svg?branch=master)](https://github.com/becheran/wildmatch/actions)
*   [BurntSushi/suffix (⭐208)](https://github.com/BurntSushi/suffix) — Linear time suffix array construction (with Unicode support) [![build badge](https://api.travis-ci.org/BurntSushi/suffix.svg?branch=master)](https://travis-ci.org/BurntSushi/suffix)
*   [BurntSushi/tabwriter (⭐212)](https://github.com/BurntSushi/tabwriter) — Elastic tab stops (i.e., text column alignment) [![build badge](https://api.travis-ci.org/BurntSushi/tabwriter.svg?branch=master)](https://travis-ci.org/BurntSushi/tabwriter)
*   [cpc (⭐83)](https://github.com/probablykasper/cpc) - Parses and calculates strings of math with support for units and unit conversion, from `1+2` to `1% of round(1 lightyear / 14!s to km/h)`.
*   [Daniel-Liu-c0deb0t/triple\_accel (⭐76)](https://github.com/Daniel-Liu-c0deb0t/triple_accel) \[[triple\_accel](https://crates.io/crates/triple_accel)] - Rust edit distance routines accelerated using SIMD; supports fast Hamming, Levenshtein, restricted Damerau-Levenshtein, etc. distance calculations and string search [![build badge](https://github.com/Daniel-Liu-c0deb0t/triple_accel/workflows/Test/badge.svg?branch=master)](https://github.com/Daniel-Liu-c0deb0t/triple_accel/actions)
*   [fancy-regex/fancy-regex (⭐304)](https://github.com/fancy-regex/fancy-regex) \[[fancy-regex](https://crates.io/crates/fancy-regex)] - Regular expressions implementation designed to support a relatively rich set of features such as look-around and backtracking. [![crates](https://img.shields.io/crates/v/fancy-regex.svg)](https://crates.io/crates/fancy-regex) [![build badge](https://github.com/fancy-regex/fancy-regex/workflows/ci/badge.svg)](https://github.com/fancy-regex/fancy-regex/actions/workflows/ci.yml)
*   [greyblake/whatlang-rs (⭐814)](https://github.com/greyblake/whatlang-rs) — Natural language detection library based on trigrams [![build badge](https://api.travis-ci.org/greyblake/whatlang-rs.svg?branch=master)](https://travis-ci.org/greyblake/whatlang-rs)
*   [Lucretiel/joinery (⭐72)](https://github.com/Lucretiel/joinery) \[[joinery](https://crates.io/crates/joinery)] – Generic string + iterable joining [![build badge](https://api.travis-ci.org/Lucretiel/joinery.svg?branch=master)](https://travis-ci.org/Lucretiel/joinery)
*   [mgeisler/textwrap (⭐328)](https://github.com/mgeisler/textwrap) \[[textwrap](https://crates.io/crates/textwrap)] — Word wrap text (with support for hyphenation) [![build badge](https://api.travis-ci.org/mgeisler/textwrap.svg?branch=master)](https://travis-ci.org/mgeisler/textwrap)
*   [ps1dr3x/easy\_reader (⭐82)](https://github.com/ps1dr3x/easy_reader) — A reader that allows forwards, backwards and random navigations through the lines of huge files without consuming iterators [![build badge](https://api.travis-ci.org/ps1dr3x/easy_reader.svg?branch=master)](https://travis-ci.org/ps1dr3x/easy_reader)
*   [pwoolcoc/ngrams (⭐26)](https://github.com/pwoolcoc/ngrams) \[[ngrams](https://crates.io/crates/ngrams)] — Construct [n-grams](https://en.wikipedia.org/wiki/N-gram) from arbitrary iterators [![build badge](https://api.travis-ci.org/pwoolcoc/ngrams.svg?branch=master)](https://travis-ci.org/pwoolcoc/ngrams)
*   [rust-lang/regex (⭐2.7k)](https://github.com/rust-lang/regex) — Regular expressions (RE2 style) [![build badge](https://api.travis-ci.com/rust-lang/regex.svg?branch=master)](https://travis-ci.org/rust-lang/regex)
*   [strsim-rs](https://crates.io/crates/strsim) — String similarity metrics [![build badge](https://api.travis-ci.org/dguo/strsim-rs.svg?branch=master)](https://travis-ci.org/dguo/strsim-rs)
*   [yaa110/rake-rs (⭐26)](https://github.com/yaa110/rake-rs) \[[rake](https://crates.io/crates/rake)] — Multilingual implementation of RAKE algorithm for Rust [![build badge](https://api.travis-ci.org/yaa110/rake-rs.svg?branch=master)](https://travis-ci.org/yaa110/rake-rs)

### Text search

*   [andylokandy/simsearch-rs (⭐117)](https://github.com/andylokandy/simsearch-rs) \[[simsearch](https://crates.io/crates/simsearch)] — A simple and lightweight fuzzy search engine that works in memory, searching for similar strings
*   [BurntSushi/fst (⭐1.5k)](https://github.com/BurntSushi/fst) \[[fst](https://crates.io/crates/fst)] — [![build badge](https://api.travis-ci.org/BurntSushi/fst.svg?branch=master)](https://travis-ci.org/BurntSushi/fst)
*   [CurrySoftware/perlin (⭐70)](https://github.com/CurrySoftware/perlin) \[[perlin](https://crates.io/crates/perlin)]
*   [meilisearch/MeiliSearch (⭐32k)](https://github.com/meilisearch/MeiliSearch) — Ultra relevant, instant and typo-tolerant full-text search API. [![Build Status](https://github.com/meilisearch/MeiliSearch/workflows/Cargo%20test/badge.svg?branch=master)](https://github.com/meilisearch/MeiliSearch/actions)
*   [tantivy (⭐7.6k)](https://github.com/quickwit-oss/tantivy) \[[tantivy](https://crates.io/crates/tantivy)] — A horse-speed full-text search engine library written in Rust. [![Build Status](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml/badge.svg)](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml)

### Unsafe

*   [zerocopy](https://crates.io/crates/zerocopy) — Utilities for safely reinterpreting arbitrary byte sequences as native Rust types

### Virtualization

*   [beneills/quantum (⭐215)](https://github.com/beneills/quantum) — Advanced Rust quantum computer simulator [![build badge](https://api.travis-ci.org/beneills/quantum.svg?branch=master)](https://travis-ci.org/beneills/quantum)
*   [bytecodealliance/wasmtime (⭐11k)](https://github.com/bytecodealliance/wasmtime) — A standalone runtime for WebAssembly [![Build Status](https://github.com/bytecodealliance/wasmtime/workflows/CI/badge.svg)](https://github.com/bytecodealliance/wasmtime/actions?query=workflow%3ACI)
*   [chromium/chromiumos/platform/crosvm](https://chromium.googlesource.com/chromiumos/platform/crosvm/) CrOSVM — Enables Chrome OS to run Linux apps inside a fast, secure virtualized environment
*   [oxidecomputer/propolis (⭐107)](https://github.com/oxidecomputer/propolis) - Rust-based userspace program for illumos bhyve kernel modules
*   [saurvs/hypervisor-rs (⭐57)](https://github.com/saurvs/hypervisor-rs) — Hardware-accelerated virtualization on OS X
*   [unicorn-rs/unicorn-rs (⭐129)](https://github.com/unicorn-rs/unicorn-rs) — Rust bindings for the unicorn CPU emulator [![Build Status](https://api.travis-ci.org/ekse/unicorn-rs.svg?branch=master)](https://travis-ci.org/ekse/unicorn-rs)

### Web programming

See also [Are we web yet?](https://www.arewewebyet.org) and [Rust web framework comparison (⭐3.7k)](https://github.com/flosse/rust-web-framework-comparison).

*   Client-side / WASM
    *   [cargo-web](https://crates.io/crates/cargo-web) — A Cargo subcommand for the client-side Web [![Build Status](https://api.travis-ci.org/koute/cargo-web.svg?branch=master)](https://travis-ci.org/koute/cargo-web)
    *   [sauron (⭐1.7k)](https://github.com/ivanceras/sauron) - Client side web framework which closely adheres to The Elm Architecture. [![Build Status](https://api.travis-ci.org/ivanceras/sauron.svg?branch=master)](https://travis-ci.org/ivanceras/sauron)
    *   [seed](https://seed-rs.org/) — A Rust framework for creating web apps
    *   [stdweb](https://crates.io/crates/stdweb) — A standard library for the client-side Web [![Build Status](https://api.travis-ci.org/koute/stdweb.svg?branch=master)](https://travis-ci.org/koute/stdweb)
    *   [yew](https://crates.io/crates/yew) — Rust framework for making client web apps
*   HTTP Client
    *   [alexcrichton/curl-rust (⭐894)](https://github.com/alexcrichton/curl-rust) — [libcurl](https://curl.se/libcurl/) bindings [![build badge](https://api.travis-ci.com/alexcrichton/curl-rust.svg?branch=master)](https://travis-ci.org/alexcrichton/curl-rust)
    *   [async-graphql (⭐2.7k)](https://github.com/async-graphql/async-graphql) - A GraphQL server library implemented in Rust [![Build Status](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_apis/build/status/graphql-rust.juniper)](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_build/latest?definitionId=1)
    *   [DoumanAsh/yukikaze](https://gitlab.com/Douman/yukikaze) \[[yukikaze](https://crates.io/crates/yukikaze)] — Beautiful and elegant Yukikaze is little HTTP client library based on hyper. [![build badge](https://gitlab.com/Douman/yukikaze/badges/master/pipeline.svg)](https://gitlab.com/Douman/yukikaze)
    *   [graphql-client (⭐925)](https://github.com/graphql-rust/graphql-client) — Typed, correct GraphQL requests and responses in Rust. [![Github actions Status](https://github.com/graphql-rust/graphql-client/workflows/CI/badge.svg?branch=master)](https://github.com/graphql-rust/graphql-client/actions)
    *   [hyperium/hyper (⭐11k)](https://github.com/hyperium/hyper) — an HTTP implementation [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
    *   [seanmonstar/reqwest (⭐6.9k)](https://github.com/seanmonstar/reqwest) — an ergonomic HTTP Client for Rust. [![build badge](https://api.travis-ci.org/seanmonstar/reqwest.svg?branch=master)](https://travis-ci.org/seanmonstar/reqwest)
*   HTTP Server
    *   [actix/actix-web (⭐16k)](https://github.com/actix/actix-web) — A lightweight async web framework for Rust with websocket support [![build badge](https://api.travis-ci.org/actix/actix-web.svg?branch=master)](https://travis-ci.org/actix/actix-web)
    *   [branca](https://crates.io/crates/branca) — A Pure Rust implementation of Branca for Authenticated and Encrypted API tokens. [![build badge](https://api.travis-ci.org/return/branca.svg?branch=master)](https://travis-ci.org/return/branca)
    *   [carllerche/tower-web (⭐968)](https://github.com/carllerche/tower-web) \[[tower-web](https://crates.io/crates/tower-web)] — A fast, boilerplate free, web framework for Rust [![build badge](https://api.travis-ci.org/carllerche/tower-web.svg?branch=master)](https://travis-ci.org/carllerche/tower-web)
    *   [danclive/sincere (⭐94)](https://github.com/danclive/sincere) — A micro web framework for Rust(stable) based on hyper and multithreading. [![build badge](https://api.travis-ci.org/danclive/sincere.svg?branch=master)](https://travis-ci.org/danclive/sincere)
    *   [GildedHonour/frank\_jwt (⭐246)](https://github.com/GildedHonour/frank_jwt) — JSON Web Token implementation in Rust. [![build badge](https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master)](https://travis-ci.org/GildedHonour/frank_jwt)
    *   [Gotham (⭐2.1k)](https://github.com/gotham-rs/gotham) — A flexible web framework that does not sacrifice safety, security or speed. [![build badge](https://api.travis-ci.org/gotham-rs/gotham.svg?branch=master)](https://travis-ci.org/gotham-rs/gotham)
    *   [Graphul (⭐303)](https://github.com/graphul-rs/graphul) — An Express-inspired web framework written in Rust. [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/graphul)
    *   [handlebars-rust (⭐943)](https://github.com/sunng87/handlebars-rust) — an Iron web framework middleware. [![build badge](https://api.travis-ci.org/sunng87/handlebars-iron.svg?branch=master)](https://travis-ci.org/sunng87/handlebars-iron)
    *   [hyperium/hyper (⭐11k)](https://github.com/hyperium/hyper) — an HTTP implementation [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
    *   [Iron (⭐6.1k)](https://github.com/iron/iron) — A middleware-based server framework [![build badge](https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master)](https://travis-ci.org/GildedHonour/frank_jwt)
    *   [Juniper (⭐4.9k)](https://github.com/graphql-rust/juniper) — GraphQL server library for Rust [![build badge](https://api.travis-ci.org/graphql-rust/juniper.svg?branch=master)](https://travis-ci.org/graphql-rust/juniper)
    *   [miketang84/sapper (⭐623)](https://github.com/miketang84/sapper) — A lightweight web framework built on async hyper, implemented in Rust language.
    *   [Nickel (⭐3k)](https://github.com/nickel-org/nickel.rs/) — inspired by [Express](http://expressjs.com/) [![build badge](https://api.travis-ci.org/nickel-org/nickel.rs.svg?branch=master)](https://travis-ci.org/nickel-org/nickel.rs)
    *   [Ogeon/rustful (⭐873)](https://github.com/Ogeon/rustful) — A RESTful web framework for Rust  [![build badge](https://api.travis-ci.org/Ogeon/rustful.svg?branch=master)](https://travis-ci.org/Ogeon/rustful)
    *   [poem-web/poem (⭐2.2k)](https://github.com/poem-web/poem) - A full-featured and easy-to-use web framework with the Rust programming language. [![CI](https://github.com/poem-web/poem/actions/workflows/ci.yml/badge.svg)](https://github.com/poem-web/poem/actions/workflows/ci.yml)
    *   [Rocket (⭐20k)](https://github.com/SergioBenitez/Rocket) — Rocket is web framework for Rust (nightly) with a focus on ease-of-use, expressability, and speed [![build badge](https://api.travis-ci.org/SergioBenitez/Rocket.svg?branch=master)](https://travis-ci.org/SergioBenitez/Rocket)
    *   [Rustless (⭐610)](https://github.com/rustless/rustless) — A REST-like API micro-framework inspired by [Grape (⭐9.7k)](https://github.com/ruby-grape/grape) and [Hyper (⭐11k)](https://github.com/hyperium/hyper) [![build badge](https://api.travis-ci.org/rustless/rustless.svg?branch=master)](https://travis-ci.org/rustless/rustless)
    *   [Salvo (⭐1.3k)](https://github.com/salvo-rs/salvo) — an easy to use webframework base on hyper and tokio. [![build build](https://github.com/salvo-rs/salvo/workflows/CI%20\(Linux\)/badge.svg?branch=master\&event=push)](https://github.com/salvo-rs/salvo/actions)
    *   [Saphir (⭐84)](https://github.com/richerarc/saphir) — A progressive web framework with low-level control, without the pain.
    *   [seanmonstar/warp (⭐7.6k)](https://github.com/seanmonstar/warp) — A super-easy, composable, web server framework for warp speeds. [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/warp)
    *   [tiny-http (⭐793)](https://github.com/tiny-http/tiny-http) — Low level HTTP server library [![build badge](https://api.travis-ci.org/tiny-http/tiny-http.svg?branch=master)](https://travis-ci.org/tiny-http/tiny-http)
    *   [tokio/axum (⭐8.3k)](https://github.com/tokio-rs/axum) - Ergonomic and modular web framework built with Tokio, Tower, and Hyper [![Build badge](https://github.com/tokio-rs/axum/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/tokio-rs/axum/actions/workflows/CI.yml)
    *   [tomaka/rouille (⭐861)](https://github.com/tomaka/rouille) — Web framework in Rust [![build badge](https://api.travis-ci.org/tomaka/rouille.svg?branch=master)](https://travis-ci.org/tomaka/rouille)
*   Miscellaneous
    *   [cargonauts (⭐179)](https://github.com/cargonauts-rs/cargonauts) — A web framework intended for building maintainable, well-factored web apps.
    *   [causal-agent/scraper (⭐1.2k)](https://github.com/causal-agent/scraper) \[[scraper](https://crates.io/crates/scraper)] - HTML parsing and querying with CSS selectors. [![Build Status](https://github.com/causal-agent/scraper/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/causal-agent/scraper/actions)
    *   [hominee/dyer (⭐125)](https://github.com/hominee/dyer) \[[dyer](https://crates.io/crates/dyer)] - dyer is designed for reliable, flexible and fast Request-Response based service, including data processing, web-crawling and so on, providing some friendly, flexible, comprehensive features without compromising speed.
    *   [juhaku/utoipa (⭐733)](https://github.com/juhaku/utoipa) - Simple, Fast, Code first and Compile time generated OpenAPI documentation for Rust [![crates.io](https://img.shields.io/crates/v/utoipa.svg?label=crates.io\&color=orange\&logo=rust)](https://crates.io/crates/utoipa) [![Utoipa build](https://github.com/juhaku/utoipa/actions/workflows/build.yaml/badge.svg)](https://github.com/juhaku/utoipa/actions/workflows/build.yaml)
    *   [osohq/oso (⭐2.9k)](https://github.com/osohq/oso) \[[oso](https://crates.io/crates/oso)] - A policy engine for authorization that's embedded in your application. [![Build Status](https://github.com/osohq/oso/workflows/Development/badge.svg?branch=main)](https://github.com/osohq/oso/actions?query=branch%3Amain+workflow%3ADevelopment)
    *   [pwoolcoc/soup](https://gitlab.com/pwoolcoc/soup) \[[soup](https://crates.io/crates/soup)] — A library similar to Python's BeautifulSoup, designed to enable quick and easy manipulation and querying of HTML documents. [![Build Status](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)
    *   [pyrossh/rust-embed (⭐1k)](https://github.com/pyrossh/rust-embed) — A macro to embed static assets into the rust binary
    *   [serenity-rs/serenity (⭐3.3k)](https://github.com/serenity-rs/serenity) \[[serenity](https://crates.io/crates/serenity)] - A Rust library for the Discord API
    *   [softprops/openapi (⭐109)](https://github.com/softprops/openapi) — A library for processing openapi spec files
    *   [svix/svix-webhooks (⭐1.1k)](https://github.com/svix/svix-webhooks) \[[svix](https://crates.io/crates/svix)]- A library for sending webhooks and verifying signatures.
    *   [tbot](https://gitlab.com/SnejUgal/tbot) \[[tbot](https://crates.io/crates/tbot)] - Make cool Telegram bots with Rust easily [![pipeline status](https://gitlab.com/SnejUgal/tbot/badges/master/pipeline.svg)](https://gitlab.com/SnejUgal/tbot/-/commits/master)
    *   [teloxide/teloxide (⭐1.7k)](https://github.com/teloxide/teloxide/) - An elegant Telegram bots framework for Rust [![Build Status](https://github.com/teloxide/teloxide/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/teloxide/teloxide/actions)
    *   [utkarshkukreti/select.rs (⭐849)](https://github.com/utkarshkukreti/select.rs) \[[select](https://crates.io/crates/select)] — A library to extract useful data from HTML documents, suitable for web scraping. [![Build Status](https://api.travis-ci.org/utkarshkukreti/select.rs.svg?branch=master)](https://travis-ci.org/utkarshkukreti/select.rs)
*   Reverse Proxy
    *   [sozu-proxy/sozu (⭐2k)](https://github.com/sozu-proxy/sozu) \[[sozu](https://crates.io/crates/sozu)] — A HTTP reverse proxy. [![CI](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml)
*   Static Site Generators
    *   [cobalt-org/cobalt.rs (⭐1.2k)](https://github.com/cobalt-org/cobalt.rs) — Static site generator written in Rust [![Build Status](https://dev.azure.com/cobalt-org/cobalt-org/_apis/build/status/cobalt.rs?branchName=master)](https://dev.azure.com/cobalt-org/cobalt-org/_build?definitionId=2)
    *   [FuGangqiang/mdblog.rs (⭐51)](https://github.com/FuGangqiang/mdblog.rs) \[[mdblog](https://crates.io/crates/mdblog)] — Static site generator from markdown files.
    *   [getzola/zola (⭐10k)](https://github.com/getzola/zola) \[[zola](https://www.getzola.org/)] — An opinionated static site generator with everything built-in. [![Build Status](https://dev.azure.com/getzola/zola/_apis/build/status/getzola.zola?branchName=master)](https://dev.azure.com/getzola/zola/_build)
    *   [grego/blades (⭐264)](https://github.com/grego/blades) \[[blades](https://getblades.org/)] — Blazing fast dead simple static site generator.
    *   [leven-the-blog/leven (⭐55)](https://github.com/leven-the-blog/leven) \[[leven](https://crates.io/crates/leven)] — A simple, parallelized blog generator. [![build badge](https://api.travis-ci.org/quadrupleslap/leven.svg?branch=master)](https://travis-ci.org/quadrupleslap/leven)
*   [WebSocket](https://datatracker.ietf.org/doc/rfc6455/)
    *   [housleyjk/ws-rs (⭐1.3k)](https://github.com/housleyjk/ws-rs) — lightweight, event-driven WebSockets for Rust [![build badge](https://api.travis-ci.org/housleyjk/ws-rs.svg?branch=stable)](https://travis-ci.org/housleyjk/ws-rs)
    *   [rust-websocket (⭐1.3k)](https://github.com/websockets-rs/rust-websocket) — A framework for dealing with WebSocket connections (both clients and servers) [![build badge](https://api.travis-ci.org/websockets-rs/rust-websocket.svg?branch=master)](https://travis-ci.org/websockets-rs/rust-websocket)
    *   [snapview/tungstenite-rs (⭐1.3k)](https://github.com/snapview/tungstenite-rs) — Lightweight stream-based WebSocket implementation for Rust.
    *   [vi/websocat (⭐5.1k)](https://github.com/vi/websocat) — CLI for interacting with WebSockets, with functionality of Netcat, Curl and Socat. [![build badge](https://api.travis-ci.org/vi/websocat.svg?branch=master)](https://travis-ci.org/vi/websocat)
    *   [vityafx/urlshortener-rs (⭐39)](https://github.com/vityafx/urlshortener-rs) — A very simple urlshortener library for Rust. [![CI](https://github.com/vityafx/urlshortener-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/urlshortener-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/urlshortener.svg)](https://crates.io/crates/urlshortener)

## Registries

A registry allows you to publish your Rust libraries as crate packages, to share them with others publicly and privately.

*   [Cloudsmith :heavy\_dollar\_sign:](https://cloudsmith.com/cargo-registry/) — A fully managed package management SaaS, with first-class support for public and private Cargo/Rust registries (plus many others). Has a generous free-tier and is also completely free for open-source.
*   [Crates](https://crates.io) — The official public registry for Rust/Cargo.
*   [w4/chartered (⭐121)](https://github.com/w4/chartered) - A private, authenticated, permissioned Cargo registry [![CI](https://github.com/w4/chartered/actions/workflows/ci.yml/badge.svg)](https://github.com/w4/chartered/actions/workflows/ci.yml)

## Resources

*   Benchmarks
    *   [TeXitoi/benchmarksgame-rs (⭐69)](https://github.com/TeXitoi/benchmarksgame-rs) — Rust implementations for the [The Computer Language Benchmarks Game](https://benchmarksgame-team.pages.debian.net/benchmarksgame/) [![build badge](https://api.travis-ci.org/TeXitoi/benchmarksgame-rs.svg?branch=master)](https://travis-ci.org/TeXitoi/benchmarksgame-rs)
*   Decks & Presentations
    *   [Learning systems programming with Rust](https://speakerdeck.com/jvns/learning-systems-programming-with-rust) — Presented by [Julia Evans](https://twitter.com/@b0rk) @ Rustconf 2016.
    *   [Rust: Hack Without Fear!](https://www.youtube.com/watch?v=lO1z-7cuRYI) — Presented by [Nicholas Matsakis](https://github.com/nikomatsakis) @ C++Now 2018
    *   [Shipping a Solid Rust Crate](https://www.youtube.com/watch?v=t4CyEKb-ywA) — Presented by [Michael Gattozzi](https://github.com/mgattozzi) @ RustConf 2017
*   [Discover Rust Libraries & Code Snippets](https://kandi.openweaver.com/explore/rust) - A curated list of Rust libraries, authors, kits, tutorials & learning resources on kandi
*   Learning
    *   [Awesome Rust Streaming (⭐595)](https://github.com/jamesmunns/awesome-rust-streaming) - A community curated list of livestreams about Rust.
    *   [awesome-rust-mentors](https://rustbeginners.github.io/awesome-rust-mentors/) — A list of helpful Rust mentors willing to take mentees and eductate them about Rust and programming.
    *   [Build a language VM](https://blog.subnetzero.io/post/building-language-vm-part-00/)
    *   [CodeCrafters.io](https://app.codecrafters.io/tracks/rust) — Build your own Redis, Git, Docker, or SQLite in Rust
    *   [Easy Rust (⭐7.4k)](https://github.com/Dhghomon/easy_rust) - Learn Rust in easy English.
    *   [exercism.org](https://exercism.org/tracks/rust) — programming exercises that help you learn new concepts in Rust.
    *   [Hands-on Rust](https://pragprog.com/titles/hwrust/hands-on-rust/) - A hands-on guide to learning Rust by making games - by [Herbert Wolverson](https://github.com/thebracket/) (paid)
    *   [Idiomatic Rust (⭐4.4k)](https://github.com/mre/idiomatic-rust) —  A peer-reviewed collection of articles/talks/repos which teach idiomatic Rust.
    *   [Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/) — in-depth exploration of Rust's memory management rules, through implementing a few different types of list structures.
    *   [Little Book of Rust Books](https://lborb.github.io/book/) - Curated list of rust books and how-tos.
    *   [Programming Community Curated Resources for Learning Rust](https://hackr.io/tutorials/learn-rust) — A list of recommended resources voted by the programming community.
    *   [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust) - A book that introduces to Rust language.
    *   [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
    *   [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) — A collection of simple examples that demonstrate good practices to accomplish common programming tasks, using the crates of the Rust ecosystem.
    *   [Rust for professionals](https://overexact.com/rust-for-professionals/) — A quick introduction to Rust for experienced software developers.
    *   [Rust Gym (⭐647)](https://github.com/warycat/rustgym) - A big collection of coding interview problems solved in Rust.
    *   [Rust in Action](https://www.manning.com/books/rust-in-action) — A hands-on guide to systems programming with Rust by [Tim McNamara](https://github.com/timClicks) (paid)
    *   [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols\&a_bid=6a993c2e) — A video series by [Carol Nichols](https://github.com/carols10cents) and [Jake Goulding](https://github.com/shepmaster) (paid)
    *   [Rust Language Cheat Sheet](https://cheats.rs/)
    *   [Rust Online Courses at Classpert](https://classpert.com/search/rust) — A list of Rust online courses (paid) from Classpert Online Course Search
    *   [Rust Tiếng Việt](https://rust-tieng-viet.github.io/) - Learn Rust in Vietnamese.
    *   [rust-how-do-i-start (⭐749)](https://github.com/jondot/rust-how-do-i-start) - A repo dedicated to answering the question: "So, Rust. How do I *start*?". A beginner only hand-picked resources and learning track.
    *   [rust-learning (⭐9.1k)](https://github.com/ctjhoa/rust-learning) — A collection of useful resources to learn Rust
    *   [Rustlings (⭐34k)](https://github.com/rust-lang/rustlings) — small exercises to get you used to reading and writing Rust code
    *   [Rusty CS (⭐629)](https://github.com/AbdesamedBendjeddou/Rusty-CS) - A Computer Science Curriculum that helps practice the acquired academic knowledge in Rust
    *   [stdx (⭐1.9k)](https://github.com/brson/stdx) — Learn these crates first as an extension to std
    *   [Take your first steps with Rust](https://learn.microsoft.com/en-us/training/paths/rust-first-steps/) - Lay the foundation of knowledge you need to build fast and effective programs in Rust.
    *   [University of Pennsylvania's Comp Sci Rust Programming Course](http://cis198-2016s.github.io/schedule/)
*   Podcasts
    *   [New Rustacean](https://newrustacean.com) — A podcast about learning Rust
    *   [Rustacean Station](https://rustacean-station.org/) — A community project for creating podcast content for Rust
*   [Rust Design Patterns (⭐6.6k)](https://github.com/rust-unofficial/patterns)
*   [Rust Guidelines](http://aturon.github.io/)
*   [Rust Servers, Services and Apps - MEAP](https://www.manning.com/books/rust-servers-services-and-apps) - Build backend servers, services, and front-ends in Rust to get fast, reliable, and maintainable applications.
*   [Rust Subreddit](https://www.reddit.com/r/rust/) — A subreddit(forum) where rust related questions, articles and resources are posted and discussed
*   [RustBooks (⭐2.2k)](https://github.com/sger/RustBooks) — list of RustBooks
*   [RustCamp 2015 Talks](https://www.youtube.com/playlist?list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t)
*   [RustViz (⭐2.3k)](https://github.com/rustviz/rustviz) — generates visualizations from simple Rust programs to assist users in better understanding the Rust Lifetime and Borrowing mechanism.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

