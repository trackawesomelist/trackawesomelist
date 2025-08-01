# Awesome Elixir Overview

A curated list of amazingly awesome Elixir and Erlang libraries, resources and shiny things. Updates:

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/h4cc/awesome-elixir/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 h4cc/awesome-elixir](https://github.com/h4cc/awesome-elixir) · ⭐ 13K · 🏷️ Programming Languages

[ [Daily](/content/h4cc/awesome-elixir/README.md) / [Weekly](/content/h4cc/awesome-elixir/week/README.md) / Overview ]

---

# Awesome Elixir [![CI Badge](https://github.com/h4cc/awesome-elixir/actions/workflows/ci.yml/badge.svg)](https://github.com/h4cc/awesome-elixir) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of amazingly awesome Elixir libraries, resources, and shiny things inspired by [awesome-php (⭐32k)](https://github.com/ziadoz/awesome-php).

If you think a package should be added, please add a :+1: (`:+1:`) at the according issue or create a new one.

There are [other sites with curated lists of elixir packages](#other-awesome-lists) which you can have a look at.

*   [Awesome Elixir  ](#awesome-elixir--)
    *   [Actors](#actors)
    *   [Algorithms and Data structures](#algorithms-and-data-structures)
    *   [Applications](#applications)
    *   [Artificial Intelligence](#artificial-intelligence)
    *   [Audio and Sounds](#audio-and-sounds)
    *   [Authentication](#authentication)
    *   [Authorization](#authorization)
    *   [Behaviours and Interfaces](#behaviours-and-interfaces)
    *   [Benchmarking](#benchmarking)
    *   [Bittorrent](#bittorrent)
    *   [BSON](#bson)
    *   [Build Tools](#build-tools)
    *   [Caching](#caching)
    *   [Chatting](#chatting)
    *   [Cloud Infrastructure and Management](#cloud-infrastructure-and-management)
    *   [Code Analysis](#code-analysis)
    *   [Command Line Applications](#command-line-applications)
    *   [Configuration](#configuration)
    *   [Cryptography](#cryptography)
    *   [CSV](#csv)
    *   [Data Visualization](#data-visualization)
    *   [Date and Time](#date-and-time)
    *   [Debugging](#debugging)
    *   [Deployment](#deployment)
    *   [Documentation](#documentation)
    *   [Domain-specific language](#domain-specific-language)
    *   [ECMAScript](#ecmascript)
    *   [Email](#email)
    *   [Embedded Systems](#embedded-systems)
    *   [Encoding and Compression](#encoding-and-compression)
    *   [Errors and Exception Handling](#errors-and-exception-handling)
    *   [Eventhandling](#eventhandling)
    *   [Examples and funny stuff](#examples-and-funny-stuff)
    *   [Feature Flags and Toggles](#feature-flags-and-toggles)
    *   [Feeds](#feeds)
    *   [Files and Directories](#files-and-directories)
    *   [Forms](#forms)
    *   [Framework Components](#framework-components)
    *   [Frameworks](#frameworks)
    *   [Games](#games)
    *   [Geolocation](#geolocation)
    *   [GUI](#gui)
    *   [Hardware](#hardware)
    *   [HTML](#html)
    *   [HTTP](#http)
    *   [Images](#images)
    *   [Instrumenting / Monitoring](#instrumenting--monitoring)
    *   [JSON](#json)
    *   [Languages](#languages)
    *   [Lexical analysis](#lexical-analysis)
    *   [Logging](#logging)
    *   [Macros](#macros)
    *   [Markdown](#markdown)
    *   [Miscellaneous](#miscellaneous)
    *   [Native Implemented Functions](#native-implemented-functions)
    *   [Natural Language Processing (NLP)](#natural-language-processing-nlp)
    *   [Networking](#networking)
    *   [Office](#office)
    *   [ORM and Datamapping](#orm-and-datamapping)
    *   [OTP](#otp)
    *   [Package Management](#package-management)
    *   [PDF](#pdf)
    *   [Protocols](#protocols)
    *   [Queue](#queue)
    *   [QUIC](#quic)
    *   [Release Management](#release-management)
    *   [REST and API](#rest-and-api)
    *   [Search](#search)
    *   [Security](#security)
    *   [SMS](#sms)
    *   [Static Page Generation](#static-page-generation)
    *   [Statistics](#statistics)
    *   [Templating](#templating)
    *   [Testing](#testing)
    *   [Text and Numbers](#text-and-numbers)
    *   [Third Party APIs](#third-party-apis)
    *   [Translations and Internationalizations](#translations-and-internationalizations)
    *   [Utilities](#utilities)
    *   [Validations](#validations)
    *   [Version Control](#version-control)
    *   [Video](#video)
    *   [WebAssembly](#webassembly)
    *   [XML](#xml)
    *   [YAML](#yaml)
*   [Resources](#resources)
    *   [Books](#books)
    *   [Cheat Sheets](#cheat-sheets)
    *   [Community](#community)
    *   [Editors](#editors)
    *   [Newsletters](#newsletters)
    *   [Other Awesome Lists](#other-awesome-lists)
    *   [Podcasts](#podcasts)
    *   [Reading](#reading)
    *   [Screencasts](#screencasts)
    *   [Styleguides](#styleguides)
    *   [Websites](#websites)
*   [Contributing](#contributing)

## Actors

*Libraries and tools for working with actors and such.*

*   [alf (⭐209)](https://github.com/antonmi/ALF) - Flow-based Application Layer Framework.
*   [bpe (⭐272)](https://github.com/spawnproc/bpe) - Business Process Engine in Erlang. ([Doc](https://bpe.n2o.dev)).
*   [pooler (⭐311)](https://github.com/seth/pooler) - An OTP Process Pool Application.
*   [poolex (⭐76)](https://github.com/general-CbIC/poolex) - Pure elixir pool manager.
*   [spawn (⭐325)](https://github.com/eigr/spawn) - Elixir poliglot actors service mesh.

## Algorithms and Data structures

*Libraries and implementations of algorithms and data structures.*

*   [aja (⭐218)](https://github.com/sabiwara/aja) - High performance persistent vectors and ordered maps.
*   [array (⭐37)](https://github.com/takscape/elixir-array) - An Elixir wrapper library for Erlang's array.
*   [aruspex (⭐39)](https://github.com/dkendal/aruspex) - Aruspex is a configurable constraint solver, written purely in Elixir.
*   [bimap (⭐33)](https://github.com/mkaput/elixir-bimap) - Pure Elixir implementation of [bidirectional maps](https://en.wikipedia.org/wiki/Bidirectional_map) and multimaps.
*   [bitmap (⭐36)](https://github.com/hashd/bitmap-elixir) - Pure Elixir implementation of [bitmaps](https://en.wikipedia.org/wiki/Bitmap).
*   [blocking\_queue (⭐54)](https://github.com/joekain/BlockingQueue) - BlockingQueue is a simple queue implemented as a GenServer. It has a fixed maximum length established when it is created.
*   [bloomex (⭐112)](https://github.com/gmcabrita/bloomex) - A pure Elixir implementation of Scalable Bloom Filters.
*   [clope (⭐22)](https://github.com/ayrat555/clope) - Elixir implementation of CLOPE: A Fast and Effective Clustering Algorithm for Transactional Data.
*   [Closure Table (⭐35)](https://github.com/florinpatrascu/closure_table) - Closure Table for Elixir - a simple solution for storing and manipulating complex hierarchies. It provides in-memory and Ecto adapters.
*   [combination (⭐34)](https://github.com/seantanly/elixir-combination) - Elixir library to generate combinations and permutations from Enumerable collection.
*   [conrex (⭐55)](https://github.com/NAISorg/conrex) - An Elixir implementation of the CONREC algorithm for topographic or isochrone maps.
*   [count\_buffer (⭐2)](https://github.com/camshaft/count_buffer) - Buffer a large set of counters and flush periodically.
*   [cuckoo (⭐42)](https://github.com/gmcabrita/cuckoo) - A pure Elixir implementation of [Cuckoo Filters](https://www.cs.cmu.edu/%7Edga/papers/cuckoo-conext2014.pdf).
*   [cuid (⭐55)](https://github.com/duailibe/cuid) - Collision-resistant ids optimized for horizontal scaling and sequential lookup performance, written in Elixir.
*   [data\_morph](https://hex.pm/packages/data_morph) - Create Elixir structs from data.
*   [dataframe (⭐63)](https://github.com/JordiPolo/dataframe) - Package providing functionality similar to Python's Pandas or R's data.frame().
*   [datastructures (⭐216)](https://github.com/meh/elixir-datastructures) - A collection of protocols, implementations and wrappers to work with data structures.
*   [def\_memo (⭐33)](https://github.com/os6sense/DefMemo) - A memoization macro (defmemo) for elixir using a genserver backing store.
*   [dlist (⭐5)](https://github.com/stocks29/dlist) - Deque implementations in Elixir.
*   [eastar (⭐34)](https://github.com/herenowcoder/eastar) - A\* graph pathfinding in pure Elixir.
*   [ecto\_materialized\_path (⭐64)](https://github.com/asiniy/ecto_materialized_path) - Tree structure, hierarchy and ancestry for the ecto models.
*   [ecto\_state\_machine (⭐99)](https://github.com/asiniy/ecto_state_machine) - Finite state machine pattern implemented on Elixir and  adopted for Ecto.
*   [elistrix (⭐18)](https://github.com/tobz/elistrix) - A latency / fault tolerance library to help isolate your applications from an uncertain world of slow or failed services.
*   [emel (⭐107)](https://github.com/mrdimosthenis/emel) - A simple and functional machine learning library written in elixir.
*   [erlang-algorithms (⭐159)](https://github.com/aggelgian/erlang-algorithms) - Implementations of popular data structures and algorithms.
*   [exconstructor (⭐288)](https://github.com/appcues/exconstructor) - An Elixir library for generating struct constructors that handle external data with ease.
*   [exfsm (⭐11)](https://github.com/awetzel/exfsm) - Simple elixir library to define a static FSM.
*   [exmatrix (⭐58)](https://github.com/a115/exmatrix) - ExMatrix is a small library for working with matrices, originally developed for testing matrix multiplication in parallel.
*   [exor\_filter (⭐33)](https://github.com/mpope9/exor_filter) - Nif for xor\_filters.  'Faster and Smaller Than Bloom and Cuckoo Filters'.
*   [ezcryptex (⭐0)](https://github.com/stocks29/ezcryptex) - Thin layer on top of Cryptex.
*   [flow (⭐1.6k)](https://github.com/dashbitco/flow) - Computational parallel flows on top of GenStage.
*   [fnv (⭐5)](https://github.com/asaaki/fnv.ex) - Pure Elixir implementation of Fowler–Noll–Vo hash functions.
*   [fsm (⭐361)](https://github.com/sasa1977/fsm) - Finite state machine as a functional data structure.
*   [fuse (⭐511)](https://github.com/jlouis/fuse) - This application implements a so-called circuit-breaker for Erlang.
*   [gen\_fsm (⭐40)](https://github.com/pavlos/gen_fsm) - A generic finite state-machine - Elixir wrapper around OTP's gen\_fsm.
*   [graphex (⭐12)](https://github.com/stocks29/graphex) - A library for composing and executing task graphs in elixir.
*   [graphmath (⭐86)](https://github.com/crertel/graphmath) - An Elixir library for performing 2D and 3D mathematics.
*   [hash\_ring\_ex (⭐25)](https://github.com/reset/hash-ring-ex) - A consistent hash-ring implementation for Elixir.
*   [hypex (⭐20)](https://github.com/whitfin/hypex) - Fast Elixir implementation of HyperLogLog.
*   [indifferent (⭐19)](https://github.com/vic/indifferent) - Indifferent access for Elixir maps/list/tuples with custom key conversion.
*   [isaac (⭐4)](https://github.com/arianvp/elixir-isaac) - Isaac is an elixir module for ISAAC: a fast cryptographic random number generator.
*   [jumper (⭐12)](https://github.com/whitfin/jumper) - Jump consistent hash implementation in Elixir (without NIFs).
*   [key2value (⭐7)](https://github.com/okeuday/key2value) - Erlang 2-way Set Associative Map.
*   [lfsr (⭐8)](https://github.com/pma/lfsr) - Elixir implementation of a binary Galois Linear Feedback Shift Register.
*   [loom (⭐225)](https://github.com/asonge/loom) - A CRDT library with δ-CRDT support.
*   [luhn (⭐16)](https://github.com/ma2gedev/luhn_ex) - Luhn algorithm in Elixir.
*   [lz4 (⭐65)](https://github.com/szktty/erlang-lz4) - LZ4 bindings for Erlang for fast data compressing.
*   [machinery (⭐552)](https://github.com/joaomdmoura/machinery) - A state machine library for structs in general, it integrates with Phoenix out of the box.
*   [mason (⭐12)](https://github.com/spacepilots/mason) - Coerce maps into structs. This is helpful e.g. when you interface a REST API and want to create a struct from the response.
*   [matrex (⭐484)](https://github.com/versilov/matrex) - A blazing fast matrix library for Elixir/Erlang with C implementation using CBLAS.
*   [merkle\_tree (⭐96)](https://github.com/yosriady/merkle_tree) - A Merkle hash tree implementation in Elixir.
*   [minmaxlist (⭐4)](https://github.com/seantanly/elixir-minmaxlist) - Elixir library extending `Enum.min_by/2`, `Enum.max_by/2` and `Enum.min_max_by/2` to return a list of results instead of just one.
*   [mmath (⭐4)](https://github.com/dalmatinerdb/mmath) - A library for performing math on number 'arrays' in binaries.
*   [monadex (⭐308)](https://github.com/rob-brown/MonadEx) - Upgrade your Elixir pipelines with monads.
*   [murmur (⭐39)](https://github.com/gmcabrita/murmur) - A pure Elixir implementation of the non-cryptographic hash Murmur3.
*   [nary\_tree (⭐18)](https://github.com/medhiwidjaja/nary_tree) - An Elixir implementation of generic n-ary tree data structure.
*   [natural\_sort (⭐14)](https://github.com/DanCouper/natural_sort) - Elixir natural sort implementation for lists of strings.
*   [navigation\_tree (⭐2)](https://github.com/gutschilla/elixir-navigation-tree) - A navigation tree representation with helpers to generate HTML out of it.
*   [parallel\_stream (⭐102)](https://github.com/beatrichartz/parallel_stream) - A parallel stream implementation for Elixir.
*   [paratize (⭐28)](https://github.com/seantanly/elixir-paratize) - Elixir library providing some handy parallel processing (execution) facilities that support configuring number of workers and timeout.
*   [parex (⭐63)](https://github.com/StevenJL/parex) - Parallel Execute (Parex) is an Elixir module for executing multiple (slow) processes in parallel.
*   [qcomplex (⭐6)](https://github.com/q60/complex) - Elixir library implementing complex numbers and math operations for them.
*   [qex (⭐34)](https://github.com/princemaple/elixir-queue) - Wraps `:queue`, with improved API and `Inspect`, `Collectable` and `Enumerable` protocol implementations.
*   [qrational (⭐9)](https://github.com/q60/rational) - Elixir library implementing rational numbers and math operations for them.
*   [ratio (⭐41)](https://github.com/Qqwy/elixir-rational) - Adds Rational Numbers and allows them to be used in common arithmetic operations. Also supports conversion between Floats and Rational Numbers.
*   [red\_black\_tree (⭐37)](https://github.com/SenecaSystems/red_black_tree) - Red-Black tree implementation in Elixir.
*   [remodel (⭐141)](https://github.com/stavro/remodel) - An Elixir presenter package used to transform map structures.
*   [rendezvous (⭐9)](https://github.com/timdeputter/Rendezvous) - Implementation of the Rendezvous or Highest Random Weight (HRW) hashing algorithm in Elixir.
*   [rock (⭐12)](https://github.com/ayrat555/rock) - Elixir implementation of ROCK: A Robust Clustering Algorithm for Categorical Attributes.
*   [sfmt (⭐70)](https://github.com/jj1bdx/sfmt-erlang/) - SIMD-oriented Fast Mersenne Twister (SFMT) for Erlang.
*   [simhash (⭐22)](https://github.com/UniversalAvenue/simhash-ex) - Simhash implementation using Siphash and N-grams.
*   [sleeplocks (⭐61)](https://github.com/whitfin/sleeplocks) - BEAM friendly spinlocks for Elixir/Erlang.
*   [sorted\_set (⭐22)](https://github.com/SenecaSystems/sorted_set) - Sorted Sets for Elixir.
*   [spacesaving (⭐2)](https://github.com/rozap/spacesaving) - stream count distinct element estimation using the "space saving" algorithm.
*   [structurez (⭐14)](https://github.com/hamiltop/structurez) - A playground for data structures in Elixir.
*   [supermemo (⭐18)](https://github.com/edubkendo/supermemo) - An Elixir implementation of the [Supermemo 2 algorithm](https://www.supermemo.com/english/ol/sm2.htm).
*   [tfidf (⭐17)](https://github.com/OCannings/tf-idf) - An Elixir implementation of term frequency–inverse document frequency.
*   [the\_fuzz (⭐77)](https://github.com/smashedtoatoms/the_fuzz) - Fuzzy string-matching algorithm implementations.
*   [tinymt (⭐26)](https://github.com/jj1bdx/tinymt-erlang/) - Tiny Mersenne Twister (TinyMT) for Erlang.
*   [trie (⭐131)](https://github.com/okeuday/trie) - Erlang Trie Implementation.
*   [witchcraft (⭐1.2k)](https://github.com/expede/witchcraft) - Common algebraic structures and functions for Elixir.
*   [zipper\_tree (⭐19)](https://github.com/Dkendal/zipper_tree) - Variadic arity tree with a zipper for Elixir.

## Applications

*Standalone applications.*

*   [Caddishouse (⭐15)](https://github.com/caddishouse/reader) - A web-based document reader that connects to your cloud storage accounts using Phoenix/LiveView.
*   [CaptainFact (⭐186)](https://github.com/CaptainFact/captain-fact-api) - A collaborative, real-time video fact-checking platform. ([Docs](https://captainfact.io/)).
*   [chat (⭐8)](https://github.com/synrc/chat) - A tiny text chat sample based on N2O.
*   [Consolex (⭐125)](https://github.com/sivsushruth/consolex) - Consolex is a tool that allows you to attach a web based console to any mix project.
*   [dragonfly\_server (⭐41)](https://github.com/cloud8421/dragonfly-server) - Elixir app to serve Dragonfly images.
*   [exchat (⭐257)](https://github.com/tony612/exchat) - A Slack-like app by Elixir, Phoenix & React (redux).
*   [Exon (⭐23)](https://github.com/tchoutri/Exon) - A “mess manager” developed in Elixir and provides a simple API to manage & document your stuff. ([Docs](https://hexdocs.pm/exon/readme.html)).
*   [ExShop (⭐220)](https://github.com/authentic-pixels/ex-shop) - Digital goods shop & blog created using Phoenix framework.
*   [Harpoon (⭐14)](https://github.com/aschiavon91/harpoon) - A webhook receiver/inspector app, made using Phoenix and LiveView, it's basically a simplified version of [webhook.site](htts://webhook.site).
*   [Igthorn (⭐104)](https://github.com/cinderella-man/igthorn) - Cryptocurrecy trading platform / trading bot with admin panel.
*   [Lynx (⭐348)](https://github.com/clivern/lynx) - A Fast, Secure and Reliable Terraform Backend, Set up in Minutes.
*   [majremind](https://bitbucket.org/Anwen/majremind) - A self-maintained database of your updated server which tells you which one needs to be updated.
*   [medex (⭐6)](https://github.com/xerions/medex) - Medical Examination - application for register health check callbacks and represent their state via HTTP.
*   [medusa\_server (⭐8)](https://github.com/IcaliaLabs/medusa_server) - A simple cowboy web server written in Elixir to stack images. ([Docs](https://hexdocs.pm/medusa/0.2.0/api-reference.html)).
*   [Nvjorn (⭐16)](https://github.com/tchoutri/Nvjorn) - A multi-protocol network services monitor written in Elixir using Poolboy.
*   [Phoenix Battleship (⭐526)](https://github.com/bigardone/phoenix-battleship) - The Good Old game built with Elixir, Phoenix Framework, React and Redux.
*   [Phoenix Toggl (⭐173)](https://github.com/bigardone/phoenix-toggl) - Toggl tribute done in Elixir, Phoenix Framework, React and Redux.
*   [Phoenix Trello (⭐2.5k)](https://github.com/bigardone/phoenix-trello) - Trello tribute done in Elixir, Phoenix Framework, React and Redux.
*   [Plural (⭐1.4k)](https://github.com/pluralsh/plural) - Deploys your favorite open source applications like airflow and airbyte in your own cloud account with just two commands.  Written in Elixir and Phoenix Framework for server side, and React for frontend.
*   [poxa (⭐1.1k)](https://github.com/edgurgel/poxa) - Open Pusher implementation, compatible with Pusher libraries.
*   [Queerlink (⭐39)](https://github.com/Queertoo/Queerlink) - A simple yet efficient URL shortening service written in Elixir.
*   [RemoteRetro (⭐581)](https://github.com/stride-nyc/remote_retro) - A real-time application for conducting Agile retrospectives at [remoteretro.org](https://remoteretro.org) written in Elixir/Phoenix/React.
*   [Sprint Poker (⭐179)](https://github.com/elpassion/sprint-poker) - Online estimation tool for Agile teams, written using Elixir Lang, Phoenix Framework and React.
*   [Startup Job (⭐101)](https://github.com/tsurupin/job_search) - An umbrella project to search startup jobs scraped from websites written in Elixir/Phoenix and React/Redux.
*   [Tai (⭐476)](https://github.com/fremantle-capital/tai) - A composable, real time, cryptocurrency market data and trade execution toolkit.
*   [tty2048 (⭐156)](https://github.com/lexmag/tty2048) - Terminal-based 2048 game written in Elixir.
*   [uai\_shot (⭐63)](https://github.com/sergioaugrod/uai_shot) - A multiplayer ship game built with Elixir, Phoenix Framework and Phaser.
*   [utils (⭐11)](https://github.com/q60/utils) - Website with handy day-to-day utils: to do list, URL shortener, code bin and pie chart. Written in Elixir using Phoenix Framework.
*   [workbench (⭐120)](https://github.com/fremantle-industries/workbench) - From Idea to Execution - Manage your trading operation across a globally distributed cluster.

## Artificial Intelligence

*When your code becomes smarter than you.*

*   [AshAI (⭐104)](https://github.com/ash-project/ash_ai) - AI and LLM toolkit for Ash applications. MCP server, MCP dev tools, vector embeddings, chat interfaces, and more.
*   [Axon (⭐1.6k)](https://github.com/elixir-nx/axon) - Nx-powered Neural Networks.
*   [Beaver (⭐202)](https://github.com/beaver-lodge/beaver) - Beaver is a LLVM/MLIR Toolkit in Elixir and Zig.
*   [ExLLama (⭐13)](https://github.com/noizu-labs-ml/ex_llama) - LlamaCpp Nif Extensions for Elixir/Erlang. ([Docs](https://hexdocs.pm/ex_llama/ExLLama.html)).
*   [Exnn (⭐100)](https://github.com/zampino/exnn) - Evolutive Neural Networks framework à la G.Sher written in Elixir. ([Docs](http://zampino.github.io/exnn/)).
*   [GenAI (⭐24)](https://github.com/noizu-labs-ml/genai) - An extensible Generative AI Completion API Wrapper with basic chat completion with tool use support provided for Gemini, Anthropic, OpenAI, and Mistral models. ([Docs](https://hexdocs.pm/genai/GenAI.html)).
*   [m2cgen (⭐2.9k)](https://github.com/BayesWitnesses/m2cgen) - A CLI tool to transpile trained classic ML models into a native Elixir code with zero dependencies.
*   [Neat-Ex](https://gitlab.com/onnoowl/Neat-Ex) - An Elixir implementation of the NEAT algorithm. ([Docs](https://hexdocs.pm/neat_ex/Neat.html)).
*   [Noizu-OpenAi (⭐7)](https://github.com/noizu-labs/elixir-openai) - An Elixir Api for the OpenAI Library. ([Docs](https://hexdocs.pm/noizu_labs_open_ai/api-reference.html)).
*   [Nx (⭐2.8k)](https://github.com/elixir-nx/nx) - Multi-dimensional arrays (tensors) and numerical definitions for Elixir.
*   [Runhyve](https://runhyve.app) - Runhyve is complete virtual machines manager for bhyve on FreeBSD. It's written in Elixir and uses Phoenix framework.
*   [simple\_bayes (⭐392)](https://github.com/fredwu/simple_bayes) - A Simple Bayes / Naive Bayes implementation in Elixir.
*   [Synapses](https://mrdimosthenis.github.io/Synapses/?elixir) - A lightweight library for neural networks.
*   [Weaviate (⭐2)](https://github.com/noizu-labs-ml/elixir-weaviate) - Weaviate client and macros for declaring records. ([Docs](https://hexdocs.pm/noizu_weaviate/api-reference.html)).

## Audio and Sounds

*Libraries working with sounds and tones.*

*   [erlaudio (⭐27)](https://github.com/asonge/erlaudio) - Erlang PortAudio bindings.
*   [ex\_alsa (⭐2)](https://github.com/dulltools/ex_alsa) - Elixir ALSA bindings.
*   [ex\_jack (⭐5)](https://github.com/dulltools/ex_jack) - Elixir JACK bindings.
*   [firmata (⭐51)](https://github.com/entone/firmata) - This package implements the Firmata protocol.
*   [synthex (⭐45)](https://github.com/bitgamma/synthex) - A signal synthesis library.

## Authentication

*Libraries for implementing authentication schemes.*

*   [aeacus (⭐38)](https://github.com/zmoshansky/aeacus) - A simple configurable identity/password authentication module (Compatible with Ecto/Phoenix).
*   [apache\_passwd\_md5 (⭐5)](https://github.com/kevinmontuori/Apache.PasswdMD5) - Apache/APR Style Password Hashing.
*   [aws\_auth (⭐66)](https://github.com/bryanjos/aws_auth) - AWS Signature Version 4 Signing Library for Elixir.
*   [basic\_auth (⭐164)](https://github.com/CultivateHQ/basic_auth) - Elixir Plug to easily add HTTP basic authentication to an app.
*   [coherence (⭐1.3k)](https://github.com/smpallen99/coherence) - Coherence is a full featured, configurable authentication system for Phoenix. ([Docs](https://hexdocs.pm/coherence/Coherence.html)).
*   [doorman (⭐120)](https://github.com/BlakeWilliams/doorman) - Tools to make Elixir authentication simple and flexible.
*   [elixir\_auth\_google (⭐280)](https://github.com/dwyl/elixir-auth-google) - The simplest way to add Google OAuth authentication ("Sign in with Google") to your Elixir/Phoenix app.
*   [ex\_aws\_msk\_iam\_auth (⭐6)](https://github.com/BigThinkcode/ex_aws_msk_iam_auth) - AWS Managed Streaming for Apache Kafka (MSK) IAM Authentication plugin for Broadway Kafka.
*   [goth (⭐313)](https://github.com/peburrows/goth) - OAuth 2.0 library for server to server applications via Google Cloud APIs.
*   [guardian (⭐3.5k)](https://github.com/ueberauth/guardian) - An authentication framework for use with Elixir applications. ([Docs](https://hexdocs.pm/guardian/Guardian.html)).
*   [guardian\_db (⭐368)](https://github.com/ueberauth/guardian_db) - An extension to Guardian that tracks tokens in your application's database to prevent playback. ([Docs](https://hexdocs.pm/guardian_db/readme.html)).
*   [guardian\_redis (⭐4)](https://github.com/alexfilatov/guardian_redis) - Redis repository for Guardian DB. ([Docs](https://hexdocs.pm/guardian_redis/readme.html)).
*   [htpasswd (⭐4)](https://github.com/kevinmontuori/Apache.htpasswd) - Apache htpasswd file reader/writer in Elixir.
*   [mojoauth (⭐4)](https://github.com/mojolingo/mojo-auth.ex) - MojoAuth implementation in Elixir.
*   [oauth2 (⭐765)](https://github.com/scrogson/oauth2) - An OAuth 2.0 client library for Elixir.
*   [oauth2\_facebook (⭐4)](https://github.com/chrislaskey/oauth2_facebook) - A Facebook OAuth2 Provider for Elixir.
*   [oauth2\_github (⭐2)](https://github.com/chrislaskey/oauth2_github) - A GitHub OAuth2 Provider for Elixir.
*   [oauth2cli (⭐4)](https://github.com/mgamini/oauth2cli-elixir) - Simple OAuth2 client written for Elixir.
*   [oauth2ex (⭐56)](https://github.com/parroty/oauth2ex) - Another OAuth 2.0 client library for Elixir.
*   [oauther (⭐70)](https://github.com/lexmag/oauther) - An OAuth 1.0 implementation for Elixir.
*   [passwordless\_auth (⭐50)](https://github.com/madebymany/passwordless_auth) - Simple passwordless login or 2-factor / multi-factor authentication for Elixir.
*   [phauxth (⭐405)](https://github.com/riverrun/phauxth) - Authentication library for Phoenix 1.3 and other Plug-based apps.
*   [phoenix\_client\_ssl (⭐19)](https://github.com/jshmrtn/phoenix-client-ssl) - Client SSL Authentication Plugs for Phoenix and other Plug-based apps.
*   [pow (⭐1.6k)](https://github.com/danschultzer/pow) - Robust, modular, and extendable user authentication system ([Website](https://powauth.com) - [Doc](https://hex.pm/packages/pow)).
*   [samly (⭐133)](https://github.com/handnot2/samly) - SAML SP SSO made easy ([Doc](https://hexdocs.pm/samly/readme.html)).
*   [sesamex (⭐12)](https://github.com/khusnetdinov/sesamex) - Another simple and flexible authentication solution in 5 minutes!.
*   [sigaws (⭐13)](https://github.com/handnot2/sigaws) - AWS Signature V4 signing and verification library ([Doc](https://hexdocs.pm/sigaws/Sigaws.html)).
*   [ueberauth (⭐1.7k)](https://github.com/ueberauth/ueberauth) - An Elixir Authentication System for Plug-based Web Applications.
*   [ueberauth\_auth0](https://hex.pm/packages/ueberauth_auth0) - An Ueberauth strategy for using Auth0 to authenticate your users.
*   [ueberauth\_cas (⭐17)](https://github.com/marceldegraaf/ueberauth_cas) - Central Authentication Service strategy for Überauth.
*   [ueberauth\_facebook (⭐78)](https://github.com/ueberauth/ueberauth_Facebook) - Facebook OAuth2 Strategy for Überauth.
*   [ueberauth\_foursquare (⭐1)](https://github.com/borodiychuk/ueberauth_foursquare) - Foursquare OAuth2 Strategy for Überauth.
*   [ueberauth\_github (⭐102)](https://github.com/ueberauth/ueberauth_github) - A GitHub strategy for Überauth.
*   [ueberauth\_google (⭐172)](https://github.com/ueberauth/ueberauth_google) - A Google strategy for Überauth.
*   [ueberauth\_identity (⭐80)](https://github.com/ueberauth/ueberauth_identity) - A simple username/password strategy for Überauth.
*   [ueberauth\_line (⭐5)](https://github.com/alexfilatov/ueberauth_line) - LINE Strategy for Überauth.
*   [ueberauth\_microsoft (⭐37)](https://github.com/swelham/ueberauth_microsoft) - A Microsoft strategy for Überauth.
*   [ueberauth\_slack (⭐22)](https://github.com/ueberauth/ueberauth_slack) - A Slack strategy for Überauth.
*   [ueberauth\_twitter (⭐36)](https://github.com/ueberauth/ueberauth_twitter) - Twitter Strategy for Überauth.
*   [ueberauth\_vk (⭐19)](https://github.com/sobolevn/ueberauth_vk) - [vk.com](https://vk.com) Strategy for Überauth.
*   [ueberauth\_weibo (⭐11)](https://github.com/he9qi/ueberauth_weibo) - [Weibo](https://weibo.com) OAuth2 Strategy for Überauth.
*   [zachaeus (⭐19)](https://github.com/railsmechanic/zachaeus) - An easy to use licensing system, based on asymmetric cryptography.

## Authorization

*Libraries for implementing Authorization handling.*

*   [authorize (⭐100)](https://github.com/jfrolich/authorize) - Rule based authorization, for advanced authorization rules.
*   [bodyguard (⭐781)](https://github.com/schrockwell/bodyguard) - A flexible authorization library for Phoenix applications.
*   [canada (⭐454)](https://github.com/jarednorman/canada) - A simple authorization library that provides a friendly interface using declarative permission rules.
*   [canary (⭐477)](https://github.com/cpjk/canary) - An authorization library for Elixir applications that restricts what resources the current user is allowed to access. ([Docs](https://hexdocs.pm/canary/api-reference.html)).
*   [speakeasy (⭐85)](https://github.com/coryodaniel/speakeasy) - Middleware based authentication and authorization for Absinthe GraphQL powered by Bodyguard.
*   [terminator (⭐63)](https://github.com/MilosMosovsky/terminator) - Database based authorization (ACL), with custom DSL rules for requiring needed permissions. ([Docs](https://hexdocs.pm/terminator/readme.html)).

## Behaviours and Interfaces

*Definitions how something should behave, like Interfaces from OOP-World*

*   [connection (⭐266)](https://github.com/fishcakez/connection) - Connection behaviour for connection processes. The API is superset of the GenServer API.
*   [gen\_state\_machine (⭐311)](https://github.com/antipax/gen_state_machine) - Elixir wrapper for gen\_statem.
*   [stockastic (⭐18)](https://github.com/shanewilton/stockastic) - Simple Elixir wrapper for the Stockfighter API.

## Benchmarking

*Running code to see how long it takes, which is faster and/or if improvements have been made.*

*   [beamchmark (⭐83)](https://github.com/membraneframework/beamchmark) - A Tool for measuring EVM performance.
*   [benchee (⭐1.5k)](https://github.com/PragTob/benchee) - Easy and extensible benchmarking in Elixir.
*   [benchfella (⭐517)](https://github.com/alco/benchfella) - Benchmarking tool for Elixir.
*   [bmark (⭐71)](https://github.com/joekain/bmark) - A benchmarking tool for Elixir.

## Bittorrent

*Sharing is caring with Elixir*

*   [bento (⭐99)](https://github.com/folz/bento) - An incredibly fast, correct, pure-Elixir Bencoding library.
*   [tracker\_request (⭐14)](https://github.com/alehander42/tracker_request) - Dealing with bittorrent tracker requests and responses.
*   [wire (⭐19)](https://github.com/alehander42/wire) - Encode and decode bittorrent peer wire protocol messages with Elixir.

## BSON

*Libraries and implementations working with BSON.*

*   [BSONMap (⭐9)](https://github.com/Nebo15/bsoneach) - Elixir package that applies a function to each document in a BSON file and has a low memory consumption.
*   [cyanide (⭐12)](https://github.com/ispirata/cyanide) - An Elixir BSON encoding/decoding library.

## Build Tools

*Project build and automation tools.*

*   [active (⭐68)](https://github.com/synrc/active) - Recompilation and Reloading on FileSystem changes.
*   [coffee\_rotor (⭐16)](https://github.com/HashNuke/coffee_rotor) - Rotor plugin to compile CoffeeScript files.
*   [dismake (⭐4)](https://github.com/jarednorman/dismake) - Mix compiler running make.
*   [etude (⭐11)](https://github.com/exstruct/etude) - Parallel computation coordination compiler for Erlang/Elixir.
*   [Exscript (⭐7)](https://github.com/liveforeverx/exscript) - Elixir escript library.
*   [mad (⭐173)](https://github.com/synrc/mad) - Small and Fast Rebar Replacement.
*   [pc (⭐65)](https://github.com/blt/port_compiler) - A rebar3 port compiler.
*   [reaxt (⭐375)](https://github.com/awetzel/reaxt) - React template into your Elixir application for server rendering.
*   [rebar3\_abnfc\_plugin (⭐1)](https://github.com/surik/rebar3_abnfc_plugin) - Rebar3 abnfc compiler.
*   [rebar3\_asn1\_compiler (⭐0)](https://github.com/pyykkis/rebar3_asn1_compiler) - Plugin for compiling ASN.1 modules with Rebar3.
*   [rebar3\_auto (⭐55)](https://github.com/vans163/rebar3_auto) - Rebar3 plugin to auto compile and reload on file change.
*   [rebar3\_diameter\_compiler (⭐6)](https://github.com/carlosedp/rebar3_diameter_compiler) - Compile diameter .dia files in rebar3 projects.
*   [rebar3\_eqc (⭐13)](https://github.com/kellymclaughlin/rebar3-eqc-plugin) - A rebar3 plugin to enable the execution of Erlang QuickCheck properties.
*   [rebar3\_exunit (⭐2)](https://github.com/processone/rebar3_exunit) - A plugin to run Elixir ExUnit tests from rebar3 build tool.
*   [rebar3\_idl\_compiler (⭐0)](https://github.com/sebastiw/rebar3_idl_compiler) - This is a plugin for compiling Erlang IDL files using Rebar3.
*   [rebar3\_live (⭐3)](https://github.com/pvmart/rebar3_live) - Rebar3 live plugin.
*   [rebar3\_neotoma\_plugin (⭐2)](https://github.com/zamotivator/rebar3_neotoma_plugin) - Rebar3 neotoma (Parser Expression Grammar) compiler.
*   [rebar3\_protobuffs (⭐10)](https://github.com/benoitc/rebar3_protobuffs) - rebar3 protobuffs provider using protobuffs from Basho.
*   [rebar3\_run (⭐25)](https://github.com/tsloughter/rebar3_run) - Run a release with one simple command.
*   [rebar3\_yang\_plugin (⭐0)](https://github.com/surik/rebar3_yang_plugin) - Rebar3 yang compiler.
*   [reltool\_util (⭐26)](https://github.com/okeuday/reltool_util) - Erlang reltool utility functionality application.
*   [relx (⭐694)](https://github.com/erlware/relx) - A release assembler for Erlang.
*   [remix (⭐149)](https://github.com/AgilionApps/remix) - Automatic recompilation of Mix code on file change.
*   [rotor (⭐82)](https://github.com/HashNuke/rotor) - Super-simple build system for Elixir.
*   [sass\_elixir (⭐1)](https://github.com/zamith/sass_elixir) - A sass plugin for Elixir projects.

## Caching

*Libraries for caching data.*

*   [cachex (⭐1.7k)](https://github.com/whitfin/cachex) - A powerful caching library for Elixir with a wide featureset.
*   [con\_cache (⭐927)](https://github.com/sasa1977/con_cache) - ConCache is an ETS based key/value storage.
*   [elixir\_locker (⭐16)](https://github.com/tsharju/elixir_locker) - Locker is an Elixir wrapper for the locker Erlang library that provides some useful libraries that should make using locker a bit easier.
*   [jc (⭐26)](https://github.com/jr0senblum/jc) - In-memory, distributable cache with pub/sub, JSON-query and consistency support.
*   [lru\_cache (⭐37)](https://github.com/arago/lru_cache) - Simple LRU Cache, implemented with ets.
*   [memoize (⭐199)](https://github.com/melpon/memoize) - A memoization macro that easily cache function.
*   [nebulex (⭐1.3k)](https://github.com/cabol/nebulex) - A fast, flexible and extensible distributed and local caching library for Elixir.
*   [request\_cache\_plug (⭐26)](https://github.com/MikaAK/request_cache_plug) - Easy to use caching for requests in either Phoenix Controllers or GraphQL resolvers. Bypasses JSON encoding/decoding for a large speedup.
*   [stash (⭐52)](https://github.com/whitfin/stash) - A straightforward, fast, and user-friendly key/value store.

## Chatting

*Chatting via IRC, Slack, HipChat and other systems using Elixir.*

*   [alice (⭐113)](https://github.com/alice-bot/alice) - A Slack bot framework for Elixir.
*   [chatty (⭐37)](https://github.com/alco/chatty) - A basic IRC client that is most useful for writing a bot.
*   [cog (⭐917)](https://github.com/operable/cog) - Cog is an open chatops platform that gives you a secure, collaborative command line right in your chat window.
*   [ExGram (⭐197)](https://github.com/rockneurotiko/ex_gram) - a library to build Telegram Bots, you can use the low-level methods and models or use the really opinionated framework included. ([Docs](https://hexdocs.pm/ex_gram/readme.html)).
*   [ExIrc (⭐155)](https://github.com/bitwalker/exirc) - IRC client adapter for Elixir projects.
*   [ExMustang (⭐70)](https://github.com/techgaun/ex_mustang) - A simple, clueless slackbot and collection of responders.
*   [Guri (⭐21)](https://github.com/elvio/guri) - Automate tasks using chat messages.
*   [hedwig (⭐654)](https://github.com/hedwig-im/hedwig) - XMPP Client/Bot Framework for Elixir.([Docs](https://hexdocs.pm/hedwig/readme.html)).
*   [kaguya (⭐74)](https://github.com/Luminarys/Kaguya) - A small, powerful, and modular IRC bot.
*   [slacker (⭐82)](https://github.com/koudelka/slacker) - A bot library for the Slack chat service.
*   [yocingo (⭐39)](https://github.com/Yawolf/yocingo) - Create your own Telegram Bot.

## Cloud Infrastructure and Management

*Applications, tools and libraries for your own cloud service.*

*   [aws (⭐576)](https://github.com/aws-beam/aws-elixir) - AWS clients for Elixir.
*   [Batteries Included (⭐45)](https://github.com/batteries-included/batteries-included) - A self hostable platform for automation/UI driven Kubernetes; built in Elixir and Golang the entire UI is built with Phoenix Live View.
*   [Bonny (⭐402)](https://github.com/coryodaniel/bonny) - Kubernetes Operator Development Framework.
*   [Cloudi](http://cloudi.org/) - CloudI is for back-end server processing tasks that require soft-realtime transaction.
*   [discovery (⭐251)](https://github.com/undeadlabs/discovery) - An OTP application for auto-discovering services with Consul.
*   [erlcloud (⭐650)](https://github.com/erlcloud/erlcloud) - Cloud Computing library for Erlang (Amazon EC2, S3, SQS, SimpleDB, Mechanical Turk, ELB). ([Docs](https://hexdocs.pm/erlcloud/)).
*   [ex\_aws (⭐1.3k)](https://github.com/CargoSense/ex_aws) - AWS client, supporting Dynamo, Kinesis, Lambda, SQS, and S3.
*   [ex\_riak\_cs (⭐5)](https://github.com/ayrat555/ex_riak_cs) - Riak CS API client.
*   [fleet\_api (⭐9)](https://github.com/jordan0day/fleet-api) - A simple wrapper for the Fleet (CoreOS) API. Can be used with etcd tokens or via direct node URLs.
*   [Gandi (⭐0)](https://github.com/Ahamtech/elixir-Gandi) - Gandi Wrapper for Leaseweb infrastructure.
*   [IElixir (⭐363)](https://github.com/pprzetacznik/IElixir) - Jupyter's kernel for Elixir programming language.
*   [k8s (⭐326)](https://github.com/coryodaniel/k8s) - Kubernetes Elixir client with CRD support, multi-cluster support, pluggable auth, and configurable middleware.
*   [Kazan (⭐138)](https://github.com/obmarg/kazan) - Kubernetes client for Elixir, generated from the k8s open API specifications.
*   [Kubereq (⭐11)](https://github.com/mruoss/kubereq) - Kubernetes Client for Elixir based on Req.
*   [Kubex (⭐39)](https://github.com/ingerslevio/kubex) - Kubernetes client and integration for Elixir, written in pure Elixir.
*   [Leaseweb (⭐3)](https://github.com/Ahamtech/elixir-leaseweb) - Elixir Wrapper for Leaseweb infrastructure.
*   [libcluster (⭐2.1k)](https://github.com/bitwalker/libcluster) - Automatic cluster formation/healing for Elixir applications.([Docs](https://hexdocs.pm/libcluster/readme.html)).
*   [nodefinder (⭐61)](https://github.com/okeuday/nodefinder) - Strategies for automatic node discovery in Erlang.
*   [nomad (⭐85)](https://github.com/sashaafm/nomad) - Create cloud portable Elixir and Phoenix apps. Write once, use everywhere.
*   [sidejob (⭐104)](https://github.com/basho/sidejob) - Parallel worker and capacity limiting library for Erlang.
*   [sidetask (⭐73)](https://github.com/PSPDFKit-labs/sidetask) - SideTask is an alternative to Task.Supervisor using Basho's sidejob library with parallelism and capacity limiting.
*   [skycluster (⭐18)](https://github.com/Nebo15/skycluster) - Automatic Erlang cluster formation, messaging and management for Elixir/Erlang applications. Integrated with Kubernetes.
*   [vercel (⭐3)](https://github.com/Bounceapp/elixir-vercel) - An Elixir wrapper for Vercel's API.

## Code Analysis

*Libraries and tools for code base analysis, parsing, and manipulation.*

*   [belvedere (⭐18)](https://github.com/nirvana/belvedere) - An example of CircleCI integration with Elixir.
*   [coverex (⭐103)](https://github.com/alfert/coverex) - Coverage Reports for Elixir.
*   [credo (⭐5k)](https://github.com/rrrene/credo) - A static code analysis tool with a focus on code consistency and teaching Elixir. ([Docs](https://hexdocs.pm/credo/Credo.html)).
*   [DepViz](https://depviz.jasonaxelson.com/) - A visual tool to help developers understand Elixir recompilation in their projects. ([Code (⭐206)](https://github.com/axelson/dep_viz/)).
*   [dialyxir (⭐1.8k)](https://github.com/jeremyjh/dialyxir) - Mix tasks to simplify use of Dialyzer in Elixir projects.([Docs](https://hexdocs.pm/dialyzex/Mix.Tasks.Dialyzer.html)).
*   [ex\_check (⭐317)](https://github.com/karolsluszniak/ex_check) - One task to efficiently run all code analysis & testing tools in an Elixir project.
*   [excellent\_migrations (⭐264)](https://github.com/Artur-Sulej/excellent_migrations) - Detecting potentially dangerous operations in database migrations.
*   [excoveralls (⭐851)](https://github.com/parroty/excoveralls) - Coverage report tool for Elixir with coveralls.io integration.
*   [exprof (⭐180)](https://github.com/parroty/exprof) - A simple code profiler for Elixir, using eprof.
*   [int\_set (⭐10)](https://github.com/Cantido/int_set) - A time- and memory-efficient unordered data structure for positive integers.

## Command Line Applications

*Anything helpful for building CLI applications.*

*   [elementtui](https://codeberg.org/edwinvanl/elementtui) - Library to help create terminal user interfaces (TUI).
*   [ex\_cli (⭐215)](https://github.com/tuvistavie/ex_cli) - User friendly CLI apps for Elixir.
*   [ex\_prompt (⭐30)](https://github.com/behind-design/ex_prompt) - Helper package to add interactivity to your command line applications as easy as possible.
*   [firex (⭐26)](https://github.com/msoedov/firex) - Firex is a library for automatically generating command line interfaces (CLIs) from an elixir module.
*   [getopt (⭐253)](https://github.com/jcomellas/getopt) - Command-line options parser for Erlang.
*   [loki (⭐90)](https://github.com/khusnetdinov/loki) - Library for creating interactive command-line application.
*   [optimus (⭐14)](https://github.com/savonarola/optimus) - Command-line option parser for Elixir inspired by [clap.rs](https://clap.rs/).
*   [owl (⭐475)](https://github.com/fuelen/owl) - Owl is a toolkit for writing command-line user interfaces in Elixir.
*   [phoenix-cli](https://phoenix-cli.github.io/) - Command-line interface for Phoenix Framework like Rails commands.
*   [progress\_bar (⭐337)](https://github.com/henrik/progress_bar) - Command-line progress bars and spinners.
*   [prompt (⭐31)](https://github.com/silbermm/prompt) - Toolkit for building command line applications in Elixir.
*   [ratatouille (⭐783)](https://github.com/ndreynolds/ratatouille) - A TUI (terminal UI) kit for Elixir.
*   [scribe (⭐306)](https://github.com/codedge-llc/scribe) - Pretty-print tables of Elixir structs and maps. Inspired by hirb.
*   [table\_rex (⭐263)](https://github.com/djm/table_rex) - Generate configurable ASCII style tables for display.
*   [tabula (⭐96)](https://github.com/aerosol/tabula) - Pretty print list of Ecto query results / maps in ascii tables (GitHub Markdown/OrgMode).

## Configuration

*Libraries and tools working with configurations*

*   [confex (⭐304)](https://github.com/Nebo15/confex) - Helper module that provides a nice way to read environment configuration at runtime.
*   [configparser\_ex (⭐20)](https://github.com/easco/configparser_ex) - A simple Elixir parser for the same kind of files that Python's configparser library handles.
*   [conform (⭐377)](https://github.com/bitwalker/conform) - Easy release configuration for Elixir apps.
*   [dotenv (⭐239)](https://github.com/avdi/dotenv_elixir) - A port of dotenv to Elixir.
*   [enux (⭐3)](https://github.com/massivefermion/enux) - utility package for loading, validating and documenting your app's configuration variables from env, json and jsonc files at runtime and injecting them into your environment.
*   [figaro (⭐9)](https://github.com/trestrantham/ex_figaro) - Simple Elixir project configuration.
*   [figaro\_elixir (⭐11)](https://github.com/KamilLelonek/figaro-elixir) - Environmental variables manager for Elixir.
*   [hush (⭐135)](https://github.com/gordalina/hush) - Read and inject configuration at runtime, and in release mode with support for multiple providers.
*   [hush\_aws\_secrets\_manager (⭐19)](https://github.com/gordalina/hush_aws_secrets_manager) - AWS Secrets Manager provider for hush.
*   [hush\_gcp\_secret\_manager (⭐19)](https://github.com/gordalina/hush_gcp_secret_manager) - Google Secret Manager provider for hush.
*   [mahaul (⭐22)](https://github.com/emadalam/mahaul) - Supercharge your environment variables in Elixir. Parse and validate with compile time access guarantees, defaults, fallbacks and app pre-boot validations.
*   [skogsra (⭐105)](https://github.com/gmtprime/skogsra) - Library to manage OS environment variables and application configuration options with ease.
*   [sweetconfig (⭐3)](https://github.com/d0rc/sweetconfig) - Read YAML configuration files from any point at your app.
*   [weave](https://gitlab.com/gt8/open-source/elixir/weave) - JIT configuration loader that works with Kubernetes and Docker Swarm.

## Cryptography

*Encrypting and decrypting data*

*   [aescmac (⭐9)](https://github.com/kleinernik/elixir-aes-cmac) - AES CMAC ([RFC 4493](https://tools.ietf.org/html/rfc4493)) in Elixir.
*   [cipher (⭐61)](https://github.com/rubencaro/cipher) - Elixir crypto library to encrypt/decrypt arbitrary binaries.
*   [cloak (⭐602)](https://github.com/danielberkompas/cloak) - Cloak makes it easy to use encryption with Ecto.([Docs](https://hexdocs.pm/cloak/readme.html)).
*   [comeonin (⭐1.3k)](https://github.com/riverrun/comeonin) - Password hashing (argon2, bcrypt, pbkdf2\_sha512) library for Elixir.(<https://hexdocs.pm/comeonin/api-reference.html>).
*   [crypto\_rsassa\_pss (⭐12)](https://github.com/potatosalad/erlang-crypto_rsassa_pss) - RSASSA-PSS Public Key Cryptographic Signature Algorithm for Erlang.
*   [elixir\_tea (⭐3)](https://github.com/keichan34/elixir_tea) - TEA implementation in Elixir.
*   [ex\_bcrypt (⭐3)](https://github.com/manelli/ex_bcrypt) - Elixir wrapper for the OpenBSD bcrypt password hashing algorithm.
*   [ex\_crypto (⭐156)](https://github.com/ntrepid8/ex_crypto) - Elixir wrapper for Erlang `crypto` and `public_key` modules. Provides sensible defaults for many crypto functions to make them easier to use.([Docs](https://hexdocs.pm/ex_crypto/readme.html)).
*   [exgpg (⭐19)](https://github.com/rozap/exgpg) - Use gpg from Elixir.
*   [nimble\_totp (⭐433)](https://github.com/dashbitco/nimble_totp) - Allows implementation of Time-based One-Time Passwords (TOTP) for 2FA.
*   [ntru\_elixir (⭐18)](https://github.com/alisinabh/ntru_elixir) - Elixir wrapper for libntru. A post quantum cryptography system.
*   [pot (⭐239)](https://github.com/yuce/pot) - Erlang library for generating one time passwords compatible with Google Authenticator.
*   [rsa (⭐36)](https://github.com/trapped/elixir-rsa) - `public_key` cryptography wrapper for Elixir.
*   [rsa\_ex (⭐38)](https://github.com/anoskov/rsa-ex) - Library for working with RSA keys.
*   [siphash-elixir (⭐19)](https://github.com/whitfin/siphash-elixir) - Elixir implementation of the SipHash hash family.
*   [tea\_crypto (⭐0)](https://github.com/keichan34/tea_crypto_erl) - Tiny Encryption Algorithm implementation.

## CSV

*Libraries and implementations working with CSV.*

*   [cesso (⭐26)](https://github.com/meh/cesso) - CSV handling library for Elixir.
*   [csv (⭐512)](https://github.com/beatrichartz/csv) - CSV Decoding and Encoding for Elixir.
*   [csv2sql (⭐56)](https://github.com/Arp-G/csv2sql) - A fast and fully automated CSV to database importer.
*   [csvlixir (⭐33)](https://github.com/jimm/csvlixir) - A CSV reading/writing application for Elixir.
*   [ecsv (⭐0)](https://github.com/erpuno/ecsv) - Fast libcsv-based stream parser for Elixir.
*   [nimble\_csv (⭐792)](https://github.com/plataformatec/nimble_csv) - A simple and fast CSV parsing and dumping library for Elixir.

## Data Visualization

*Libraries for creating visualizations with data.*

*   [plox (⭐96)](https://github.com/gridpoint-com/plox) - Server-side rendered SVG graphing components for Phoenix and LiveView.
*   [tucan (⭐220)](https://github.com/pnezis/tucan) - An Elixir plotting library on top of VegaLite.
*   [vega\_lite (⭐197)](https://github.com/livebook-dev/vega_lite) - Elixir bindings for Vega-Lite.

## Date and Time

*Libraries for working with dates and times.*

*   [block\_timer (⭐10)](https://github.com/adamkittelson/block_timer) - Macros to use :timer.apply\_after and :timer.apply\_interval with a block.
*   [calendar (⭐467)](https://github.com/lau/calendar) - Calendar is a date and time library for Elixir.
*   [calendarific (⭐4)](https://github.com/Bounceapp/elixir-calendarific) - Calendarific is a wrapper for the holiday API Calendarific.
*   [calixir (⭐3)](https://github.com/rengel-de/calixir) - Calixir is a port of the Lisp calendar software calendrica-4.0 to Elixir.
*   [chronos (⭐90)](https://github.com/nurugger07/chronos) - An Elixir date/time library.
*   [cocktail (⭐227)](https://github.com/peek-travel/cocktail) - Elixir date recurrence library based on iCalendar events.
*   [cronex (⭐48)](https://github.com/jbernardo95/cronex) - Cron like system you can mount in your supervision tree.
*   [crontab (⭐96)](https://github.com/jshmrtn/crontab) - A Cron Expressions Parser, Composer & Date Candidate Finder.
*   [emojiclock (⭐3)](https://github.com/nathanhornby/emojiclock-elixir) - An Elixir module for giving you an emoji clock for a given hour.
*   [ex\_ical (⭐23)](https://github.com/fazibear/ex_ical) - ICalendar parser.
*   [filtrex (⭐198)](https://github.com/rcdilorenzo/filtrex) - A library for performing and validating complex SQL-like filters from a client (e.g. smart filters).
*   [good\_times (⭐46)](https://github.com/DevL/good_times) - Expressive and easy to use datetime functions.
*   [jalaali (⭐22)](https://github.com/jalaali/elixir-jalaali) - Jalaali calendar implementation for Elixir.
*   [milliseconds (⭐2)](https://github.com/davebryson/elixir_milliseconds) - Simple library to work with milliseconds in Elixir.
*   [moment (⭐28)](https://github.com/atabary/moment) - Parse, validate, manipulate, and display dates in Elixir.
*   [open\_hours (⭐51)](https://github.com/hopsor/open_hours) - Time calculations using business hours.
*   [quantum (⭐2.4k)](https://github.com/quantum-elixir/quantum-core) - Cron-like job scheduler for Elixir applications.
*   [repeatex (⭐53)](https://github.com/rcdilorenzo/repeatex) - Natural language parsing for repeating dates.
*   [timelier (⭐12)](https://github.com/ausimian/timelier) - A cron-style scheduler for Elixir.
*   [timex (⭐1.8k)](https://github.com/bitwalker/timex) - Easy to use Date and Time modules for Elixir.
*   [timex\_interval (⭐9)](https://github.com/atabary/timex-interval) - A date/time interval library for Elixir projects, based on Timex.
*   [tzdata (⭐315)](https://github.com/lau/tzdata) - The timezone database in Elixir.

## Debugging

*Libraries and tools for debugging code and applications.*

*   [beaker (⭐280)](https://github.com/hahuang65/beaker) - Statistics and Metrics library for Elixir.
*   [booter (⭐23)](https://github.com/eraserewind/booter) - Boot an Elixir application, step by step.
*   [dbg (⭐161)](https://github.com/fishcakez/dbg) - Distributed tracing for Elixir.
*   [eflame (⭐427)](https://github.com/proger/eflame) - Flame Graph profiler for Erlang.
*   [eper (⭐437)](https://github.com/massemanet/eper) - Erlang performance and debugging tools.
*   [ether (⭐6)](https://github.com/maarek/ether) - Ether provides functionality to hook Elixir into the Erlang debugger.
*   [ex\_debug\_toolbar (⭐408)](https://github.com/kagux/ex_debug_toolbar) - A toolbar for Phoenix projects to interactively debug code and display useful information about requests: logs, timelines, database queries etc.
*   [exrun (⭐121)](https://github.com/liveforeverx/exrun) - Distributed tracing for Elixir with rate limiting and simple macro-based interface.
*   [extrace (⭐60)](https://github.com/redink/extrace) - Elixir wrapper for Recon Trace.
*   [git\_hooks (⭐170)](https://github.com/qgadrian/elixir_git_hooks) - Add git hooks to Elixir projects.
*   [inspector (⭐15)](https://github.com/marciol/inspector) - A simple one-line module that allows a more friendly debugging experience.
*   [observer\_cli (⭐1.4k)](https://github.com/zhongwencool/observer_cli) - Visualize Elixir & Erlang nodes on the command line, it aims to help developers debug production systems.
*   [quaff (⭐83)](https://github.com/qhool/quaff) - The Debug module provides a simple helper interface for running Elixir code in the erlang graphical debugger.
*   [rexbug (⭐255)](https://github.com/nietaki/rexbug) - An Elixir wrapper for the `redbug` production-friendly Erlang tracing debugger.
*   [visualixir (⭐1.3k)](https://github.com/koudelka/visualixir) - A process visualizer for remote BEAM nodes.

## Deployment

*Installing and running your code automatically on other machines.*

*   [akd (⭐52)](https://github.com/annkissam/akd) - Capistrano like, Configurable, and easy to set up Elixir Deployment Automation Framework.
*   [ansible-elixir-stack (⭐297)](https://github.com/HashNuke/ansible-elixir-stack) - 1-command setup & deploys to servers, with first-class support for Phoenix apps.
*   [bootleg (⭐397)](https://github.com/labzero/bootleg) - Simple deployment and server automation for Elixir.
*   [bottler (⭐39)](https://github.com/rubencaro/bottler) - Bottler is a collection of tools that aims to help you generate releases, ship them to your servers, install them there, and get them live on production.
*   [edeliver (⭐2k)](https://github.com/boldpoker/edeliver) - Deployment for Elixir and Erlang.
*   [elixir-on-docker (⭐173)](https://github.com/CrowdHailer/elixir-on-docker) - A project template to get started developing clustered Elixir applications for cloud environments.
*   [exdm (⭐12)](https://github.com/joeyates/exdm) - Deploy Elixir applications via mix tasks.
*   [exreleasy (⭐13)](https://github.com/miros/exreleasy) - Dead simple and Mix friendly tool for releasing Elixir applications.
*   [gatling (⭐494)](https://github.com/hashrocket/gatling) - Collection of mix tasks to automatically create a exrm release from git and launch/upgrade it on your server.
*   [Gigalixir](https://www.gigalixir.com) - A fully-featured PaaS designed for Elixir. Supports clustering, hot upgrades, and remote console/observer. Free to try without a credit card.
*   [heroku-buildpack-elixir (⭐813)](https://github.com/HashNuke/heroku-buildpack-elixir) - Heroku buildpack to deploy Elixir apps to Heroku.

## Documentation

*Libraries and tools for creating documentation.*

*   [bureaucrat (⭐369)](https://github.com/api-hogs/bureaucrat) - Generate Phoenix API documentation from tests.
*   [ex\_doc (⭐1.5k)](https://github.com/elixir-lang/ex_doc) - ExDoc is a tool to generate documentation for your Elixir projects.
*   [ex\_doc\_dash (⭐64)](https://github.com/JonGretar/ExDocDash) - Formatter for ExDoc to generate docset documentation for use in Dash.app.
*   [hexdocset (⭐22)](https://github.com/yesmeck/hexdocset) - Convert hex doc to Dash.app's docset format.
*   [inch-ci](http://inch-ci.org/) - Documentation badges for Ruby & Elixir.
*   [maru\_swagger (⭐57)](https://github.com/falood/maru_swagger) - Add swagger compliant documentation to your maru API.
*   [phoenix\_api\_docs (⭐26)](https://github.com/smoku/phoenix_api_docs) - Generate API Blueprint documentation from controllers and tests in the Phoenix framework.
*   [phoenix\_swagger (⭐706)](https://github.com/xerions/phoenix_swagger) - Provides swagger integration to the Phoenix framework.
*   [xcribe (⭐61)](https://github.com/brainn-co/xcribe) - Generate API documentation from tests using Swagger (OpenAPI) or API Blueprint specification.

## Domain-specific language

*Specialized computer languages for a particular application domain.*

*   [Absinthe Graphql (⭐4.3k)](https://github.com/absinthe-graphql/absinthe) - Fully featured GraphQL library.
*   [absinthe\_gen (⭐29)](https://github.com/sashman/absinthe_gen) - Scaffold generator for Absithne.
*   [JSON-LD.ex (⭐79)](https://github.com/marcelotto/jsonld-ex) - An implementation of the [JSON-LD](http://www.w3.org/TR/json-ld/) standard for [RDF.ex (⭐120)](https://github.com/marcelotto/rdf-ex).
*   [RDF.ex (⭐120)](https://github.com/marcelotto/rdf-ex) - An implementation of the [RDF](https://www.w3.org/TR/rdf11-primer/) data model in Elixir.
*   [SPARQL.ex (⭐40)](https://github.com/marcelotto/sparql-ex) - An implementation of the [SPARQL](http://www.w3.org/TR/sparql11-overview/) standards in Elixir.

## ECMAScript

*Implementations working with JavaScript, JScript or ActionScript.*

*   [elixirscript (⭐1.6k)](https://github.com/elixirscript/elixirscript/) - A transcompiler from Elixir to Javascript.
*   [estree (⭐104)](https://github.com/bryanjos/elixir-estree) - A implementation of the SpiderMonkey Parser API in Elixir.
*   [phoenix\_gon (⭐101)](https://github.com/khusnetdinov/phoenix_gon) - Allow you to pass Phoenix environment or controller variables to JavaScript without problems.
*   [phoenix\_routes\_js (⭐21)](https://github.com/khusnetdinov/phoenix_routes_js) - Phoenix routes helpers in JavaScript code and browser console.

## Email

*Working with Email and stuff.*

*   [bamboo (⭐1.9k)](https://github.com/thoughtbot/bamboo) - Composable, testable and adapter based email library. Out of the box support for rendering with Phoenix and a plug for previewing sent emails in dev.
*   [burnex (⭐77)](https://github.com/Betree/burnex) - Burner email (temporary address) detector.
*   [echo (⭐30)](https://github.com/zmoshansky/echo) - A meta-notification system; Echo checks notification preferences & dispatches notifications.
*   [ex\_postmark (⭐4)](https://github.com/KamilLelonek/ex_postmark) - Postmark adapter for sending template emails in Elixir.
*   [gen\_smtp (⭐694)](https://github.com/Vagabond/gen_smtp) - A generic Erlang SMTP server and client that can be extended via callback modules.
*   [gmail (⭐53)](https://github.com/craigp/elixir-gmail) - A simple Gmail REST API client for Elixir.
*   [mail (⭐468)](https://github.com/DockYard/elixir-mail) - An RFC2822 implementation in Elixir, built for composability.
*   [mailer (⭐41)](https://github.com/antp/mailer) - A simple SMTP mailer.
*   [mailibex (⭐63)](https://github.com/awetzel/mailibex) - Library containing Email-related implementations in Elixir: dkim, spf, dmark, mimemail, smtp.
*   [mailman (⭐204)](https://github.com/kamilc/mailman) - Mailman provides a clean way of defining mailers in your Elixir applications.
*   [pop3mail](https://hex.pm/packages/pop3mail) - Pop3 client to download email (including attachments) from the inbox via the commandline or Elixir API.
*   [ravenx (⭐111)](https://github.com/acutario/ravenx) - Notification dispatch library for Elixir applications.
*   [smoothie (⭐46)](https://github.com/jfrolich/smoothie) - Smoothie inline styles of your email templates, and generates a plain text version from the HTML.
*   [swoosh (⭐1.5k)](https://github.com/swoosh/swoosh) - Compose, deliver and test your Emails (with attachments!) easily in Elixir with adapters for SMTP, Sendgrid, Mandrill, Mailgun, Postmark and lots others, plus Phoenix integration with mailbox preview.

## Embedded Systems

*Embedded systems development.*

*   [nerves](http://nerves-project.org) - A framework for writing embedded software in Elixir.

## Encoding and Compression

*Transforming data in different formats or compressing it.*

*   [ex\_rlp (⭐32)](https://github.com/exthereum/ex_rlp) - Elixir implementation of Ethereum's RLP (Recursive Length Prefix) encoding.
*   [huffman (⭐0)](https://github.com/tyre/huffman) - Huffman encoding and decoding in Elixir.

## Errors and Exception Handling

*Working with errors and exceptions.*

*   [AppSignal Elixir (⭐289)](https://github.com/appsignal/appsignal-elixir) - The official [AppSignal](https://appsignal.com/) package for Elixir.
*   [elixir\_error\_message (⭐38)](https://github.com/MikaAK/elixir_error_message) - Simple error helpers to make errors in your system predictable and easy to render to JSON or in logs.
*   [exceptional (⭐294)](https://github.com/expede/exceptional) - Helpers for happy-path programming & exception handling.
*   [happy (⭐45)](https://github.com/vic/happy) - Happy path programming, alternative to elixir `with` form.
*   [OK (⭐602)](https://github.com/CrowdHailer/OK) - Elegant error handling with result monads, featuring a simple & powerful `with` construct and a happy path pipe operator.
*   [sentry-elixir (⭐656)](https://github.com/getsentry/sentry-elixir) - The Official Elixir client for [Sentry](https://sentry.io/).

## Eventhandling

*Sending/Emitting and receiving/handling Events in Elixir.*

*   [cizen](https://gitlab.com/cizen/cizen) - Build highly concurrent, monitorable, and extensible applications with a collection of sagas.
*   [event\_bus (⭐702)](https://github.com/mustafaturan/event_bus) - Simple event bus implementation with topic filtering and built-in event store and event watcher.
*   [goldrush (⭐101)](https://github.com/DeadZen/goldrush) - Small, Fast event processing and monitoring for Erlang/OTP applications.
*   [reaxive (⭐286)](https://github.com/alfert/reaxive) - Reaxive is a reactive event handling library, inspired by [Elm](http://elm-lang.org) and Reactive Extensions.
*   [wait\_for\_it (⭐17)](https://github.com/jvoegele/wait_for_it) - Provides convenient and easy-to-use facilities for synchronizing concurrent activities.

## Examples and funny stuff

*Example code and stuff too funny or curious not to mention.*

*   [butler\_cage (⭐3)](https://github.com/keathley/butler_cage) - A Butler plugin for showing silly photos of Nick Cage.
*   [butler\_tableflip (⭐2)](https://github.com/keathley/butler_tableflip) - Flipping tables with butler.
*   [changelog.com (⭐2.7k)](https://github.com/thechangelog/changelog.com) - CMS that runs changelog.com built with Phoenix 1.4.
*   [coderplanets.com (⭐219)](https://github.com/coderplanets/coderplanets_server) - GraphQL api for coderplanets.com built with Phoenix 1.4 and Absinthe.
*   [dice (⭐14)](https://github.com/stocks29/dice) - Roll the dice, in Elixir.
*   [elixir\_koans (⭐2.3k)](https://github.com/elixirkoans/elixir-koans) - [Elixir koans](http://elixirkoans.io/) is a fun, easy way to get started with the elixir programming language.
*   [ex\_iss (⭐4)](https://github.com/cryptobird/ex_iss) - This package is for interfacing with the Open Notify API to information such as the ISS's current location, crew, and when it will pass over a location.
*   [feedx (⭐12)](https://github.com/erneestoc/feedx) - Add social feed functionality to current applications. Exemplify OTP umbrella app, with 3 apps. Thin phoenix controllers.
*   [harakiri (⭐21)](https://github.com/rubencaro/harakiri) - Help applications kill themselves.
*   [hello\_phoenix (⭐131)](https://github.com/bigardone/phoenix-react-redux-template) - Application template for SPAs with Phoenix, React and Redux.
*   [hexpm (⭐1.1k)](https://github.com/hexpm/hexpm) - Source code for the hex package manager site built with Phoenix 1.3.
*   [koans (⭐249)](https://github.com/dojo-toulouse/elixir-koans) - Learn Elixir by using elixir-koans.
*   [lolcat (⭐7)](https://github.com/restartr/ex-lolcat) - This is the clone of busyloop/lolcat. But it does not support animation and some features of the original.
*   [magnetissimo (⭐3.1k)](https://github.com/sergiotapia/magnetissimo) - Web application that indexes all popular torrent sites, and saves it to the local database.
*   [oop (⭐320)](https://github.com/wojtekmach/oop) - OOP in Elixir.
*   [phoenix-chat-example (⭐806)](https://github.com/dwyl/phoenix-chat-example) - A step-by-step example/tutorial for building a Chat app in Phoenix for complete beginners. Covers testing, docs and deployment. Phoenix `1.5.3`.
*   [phoenix-ecto-encryption-example (⭐284)](https://github.com/dwyl/phoenix-ecto-encryption-example) - A comprehensive example/tutorial showing people how to use Ecto Types to transparently encrypt/decrypt data in a Phoenix 1.4 app.
*   [phoenix-flux-react (⭐160)](https://github.com/fxg42/phoenix-flux-react) - An experiment with Phoenix Channels, GenEvents, React and Flux.
*   [phoenix-liveview-counter-tutorial (⭐406)](https://github.com/dwyl/phoenix-liveview-counter-tutorial) - complete beginners step-by-step tutorial building a real time counter in Phoenix `1.5.3` and LiveView `0.14.1`.
*   [phoenix-todo-list-tutorial (⭐208)](https://github.com/dwyl/phoenix-todo-list-tutorial) - A complete beginners step-by-step tutorial for building a Todo List from scratch in Phoenix `1.5.3`.
*   [real world example app (⭐894)](https://github.com/gothinkster/elixir-phoenix-realworld-example-app) - Elixir / Phoenix implementation of [RealWorld.io](https://realworld.io/) backend specs - a Medium clone.
*   [rollex](https://gitlab.com/olhado/rollex) - Elixir library using a Pratt Parser algorithm to calculate dice rolls.
*   [rubix (⭐3)](https://github.com/YellowApple/Rubix) - A very simple (and barely-functioning) Ruby runner for Elixir.
*   [stranger (⭐67)](https://github.com/cazrin/stranger) - Elixir Phoenix app to chat anonymously with a randomly chosen stranger.
*   [tilex (⭐499)](https://github.com/hashrocket/tilex) - Source code for Hashrocket's TIL website built with Phoenix 1.3.
*   [weather (⭐69)](https://github.com/tacticiankerala/elixir-weather) - A command line weather app built using Elixir.

## Feature Flags and Toggles

*Libraries to manage feature toggles (AKA feature flags): ON/OFF values that can be toggled at runtime through some interface*

*   [ConfigCat (⭐21)](https://github.com/configcat/elixir-sdk) - Elixir SDK for ConfigCat hosted feature flag service.
*   [flippant (⭐107)](https://github.com/sorentwo/flippant) - Feature flipping for the Elixir world.
*   [fun\_with\_flags (⭐1.1k)](https://github.com/tompave/fun_with_flags) - A feature toggle library using Redis or Ecto for persistence, an ETS cache for speed and PubSub for distributed cache busting. Comes with a management web UI for Phoenix and Plug.
*   [molasses (⭐78)](https://github.com/securingsincity/molasses) - A feature toggle library using redis or SQL (using Ecto) as a backing service.

## Feeds

*Libraries working with feeds like RSS or ATOM.*

*   [atomex (⭐64)](https://github.com/Betree/atomex) - ATOM feed builder with a focus on standards compliance, security and extensibility.
*   [feeder (⭐44)](https://github.com/michaelnisi/feeder) - Parse RSS and Atom feeds.
*   [feeder\_ex (⭐70)](https://github.com/manukall/feeder_ex) - RSS feed parser. Simple wrapper for feeder.
*   [feedme (⭐15)](https://github.com/umurgdk/elixir-feedme) - RSS/Atom parser built on erlang's xmerl xml parser.

## Files and Directories

*Libraries and implementations for working with files and directories.*

*   [Belt](https://bitbucket.org/pentacent/belt/) - Extensible file upload library with support for SFTP, S3 and Filesystem storage.
*   [dir\_walker (⭐44)](https://github.com/pragdave/dir_walker) - DirWalker lazily traverses one or more directory trees, depth first, returning successive file names.
*   [elixgrep (⭐28)](https://github.com/bbense/elixgrep) - A framework for doing Hadoop style Map/Reduce operations on collections of files.
*   [ex\_guard (⭐84)](https://github.com/slashmili/ex_guard) - ExGuard is a mix command to handle events on file system modifications.
*   [ex\_minimatch (⭐13)](https://github.com/gniquil/ex_minimatch) - Globbing paths without walking the tree!.
*   [exfile (⭐90)](https://github.com/keichan34/exfile) - File upload handling, persistence, and processing in Elixir and Plug.
*   [exfswatch (⭐274)](https://github.com/falood/exfswatch) - A file change watcher wrapper based on **fs**.
*   [eye\_drops (⭐53)](https://github.com/rkotze/eye_drops) - Configurable mix task to watch file changes and run the corresponding command.
*   [format\_parser.ex (⭐24)](https://github.com/ahtung/format_parser.ex) - Elixir library to figure out the type and the format of a file.
*   [fs (⭐240)](https://github.com/synrc/fs) - Erlang FileSystem Listener.
*   [fwatch (⭐4)](https://github.com/ryo33/fwatch-ex) - A callback-based file watcher based on **fs**.
*   [ivcu (⭐5)](https://github.com/elixir-ivcu/ivcu) - File Validator, Converter, and Uploader.
*   [librex (⭐36)](https://github.com/ricn/librex) - Elixir library to convert office documents to other formats using LibreOffice.
*   [Radpath (⭐22)](https://github.com/lowks/Radpath) - Path library for Elixir, inspired by Python's Enhpath.
*   [sentix (⭐16)](https://github.com/whitfin/sentix) - A cross-platform file watcher for Elixir based on fswatch.
*   [sizeable (⭐41)](https://github.com/arvidkahl/sizeable) - An Elixir library to make file sizes human-readable.
*   [waffle (⭐788)](https://github.com/elixir-waffle/waffle) - Flexible file upload and attachment library for Elixir.
*   [zarex (⭐29)](https://github.com/ricn/zarex) - Filename sanitization for Elixir.

## Forms

*Handling web forms and similar stuff.*

*   [forms (⭐39)](https://github.com/spawnproc/forms) - Erlang Business Documents Generator.

## Framework Components

*Standalone component from web development frameworks.*

*   [absinthe\_plug (⭐263)](https://github.com/absinthe-graphql/absinthe_plug) - Plug support for Absinthe.
*   [access pass (⭐70)](https://github.com/AppDoctorIo/accesspass) - Authentication framework that can be used with or outside of phoenix. Similar to Addict but geared towards API usage.([Docs](https://hexdocs.pm/access_pass/api-reference.html#content)).
*   [addict (⭐643)](https://github.com/trenpixster/addict) - User authentication for Phoenix Framework.
*   [airbrake\_plug (⭐5)](https://github.com/romul/airbrake_plug) - Report errors in your Plug stack or whatever to Airbrake.
*   [Backpex (⭐746)](https://github.com/naymspace/backpex) - Highly customizable administration panel for Phoenix LiveView applications. ([Docs](https://hexdocs.pm/backpex/), [Demo](https://backpex.live/)).
*   [better\_params (⭐97)](https://github.com/sheharyarn/better_params) - Elixir Plug for cleaner request params in web apps.
*   [blaguth (⭐20)](https://github.com/lexmag/blaguth) - Basic Access Authentication in Plug applications.
*   [commanded (⭐1.9k)](https://github.com/slashdotdash/commanded) - Command handling middleware for Command Query Responsibility Segregation (CQRS) applications.
*   [cors\_plug (⭐407)](https://github.com/mschae/cors_plug) - An Elixir plug that adds CORS headers to requests and responds to preflight requests (OPTIONS).
*   [corsica (⭐532)](https://github.com/whatyouhide/corsica) - Elixir library for dealing with CORS requests.
*   [crudex (⭐20)](https://github.com/bitgamma/crudex) - CRUD utilities for Phoenix and Ecto.
*   [dayron (⭐159)](https://github.com/inaka/Dayron) - A repository *similar* to `Ecto.Repo` that works with REST API requests instead of a database.
*   [ex\_admin (⭐1.2k)](https://github.com/smpallen99/ex_admin) - ExAdmin is an auto administration package for Elixir and the Phoenix Framework.
*   [exdjango (⭐21)](https://github.com/nicksanders/exdjango) - A few elixir libraries for working with django.
*   [exrecaptcha (⭐12)](https://github.com/adanselm/exrecaptcha) - Simple reCaptcha display/verify code for Elixir applications.
*   [filterable (⭐105)](https://github.com/omohokcoj/filterable) - Simple query params filtering for Phoenix framework inspired by Rails has\_scope.
*   [graphql\_parser (⭐22)](https://github.com/graphql-elixir/graphql_parser) - An Elixir binding for [libgraphqlparser (⭐1.1k)](https://github.com/graphql/libgraphqlparser).
*   [http\_router (⭐14)](https://github.com/sugar-framework/elixir-http-router) - HTTP Router with various macros to assist in developing your application and organizing your code.
*   [kerosene (⭐231)](https://github.com/elixirdrops/kerosene) - Pagination for Ecto and Phoenix.
*   [live\_vue (⭐339)](https://github.com/Valian/live_vue) - End-to-end reactivity for Phoenix LiveView and Vue.
*   [mellon (⭐16)](https://github.com/sajmoon/mellon) - An authentication module for Plug applications.
*   [multiverse (⭐95)](https://github.com/Nebo15/multiverse) - Plug that allows to add version compatibility layers via API Request/Response Gateways.
*   [params (⭐370)](https://github.com/vic/params) - Use Ecto to enforce/validate parameters structure, akin to Rails' strong parameters.
*   [phoenix\_ecto (⭐548)](https://github.com/phoenixframework/phoenix_ecto) - Phoenix and Ecto integration.
*   [phoenix\_haml (⭐158)](https://github.com/chrismccord/phoenix_haml) - Phoenix Template Engine for Haml.
*   [phoenix\_html (⭐438)](https://github.com/phoenixframework/phoenix_html) - Phoenix.HTML functions for working with HTML strings and templates.
*   [phoenix\_html\_sanitizer (⭐28)](https://github.com/elixirstatus/phoenix_html_sanitizer) - HTML Sanitizer integration for Phoenix.
*   [phoenix\_html\_simplified\_helpers (⭐31)](https://github.com/ikeikeikeike/phoenix_html_simplified_helpers) - Some helpers for phoenix html (truncate, time\_ago\_in\_words, number\_with\_delimiter).
*   [phoenix\_linguist (⭐18)](https://github.com/jxs/phoenix_linguist) - A project that integrates Phoenix with Linguist, providing a plug and view helpers. It looks abandoned: its last commit was on 2015 and its CI runs Elixir 1.0.3.
*   [phoenix\_live\_reload (⭐322)](https://github.com/phoenixframework/phoenix_live_reload) - Provides live-reload functionality for Phoenix.
*   [phoenix\_meta\_tags (⭐30)](https://github.com/hlongvu/phoenix_meta_tags) - Generate meta tags for a website.
*   [phoenix\_pubsub\_postgres (⭐28)](https://github.com/opendrops/phoenix-pubsub-postgres) - Postgresql PubSub adapter for Phoenix apps.
*   [phoenix\_pubsub\_rabbitmq (⭐45)](https://github.com/pma/phoenix_pubsub_rabbitmq) - RabbitMQ adapter for Phoenix's PubSub layer.
*   [phoenix\_pubsub\_redis (⭐179)](https://github.com/phoenixframework/phoenix_pubsub_redis) - The Redis PubSub adapter for the Phoenix framework.
*   [phoenix\_pubsub\_vernemq (⭐25)](https://github.com/larshesel/phoenix_pubsub_vernemq) - The VerneMQ MQTT pubsub adapter for the Phoenix framework.
*   [phoenix\_slime (⭐311)](https://github.com/slime-lang/phoenix_slime) - Slim template support for Phoenix.
*   [phoenix\_storybook (⭐805)](https://github.com/phenixdigital/phoenix_storybook) - A pluggable storybook for your Phoenix components.
*   [phoenix\_svg (⭐17)](https://github.com/jsonmaur/phoenix-svg) - Use inline SVGs in Phoenix.
*   [phoenix\_token\_auth (⭐163)](https://github.com/manukall/phoenix_token_auth) - Token authentication solution for Phoenix. Useful for APIs or single page apps.
*   [phoenix\_turnstile (⭐15)](https://github.com/jsonmaur/phoenix-turnstile) - Phoenix components and helpers for using CAPTCHAs with Cloudflare Turnstile.
*   [phx\_component\_helpers (⭐137)](https://github.com/cblavier/phx_component_helpers) - Extensible live\_components, without boilerplate.
*   [plug (⭐2.9k)](https://github.com/elixir-lang/plug) - A specification and conveniences for composable modules in between web applications.
*   [plug\_accesslog (⭐31)](https://github.com/mneudert/plug_accesslog) - Plug for writing access logs.
*   [plug\_and\_play (⭐15)](https://github.com/henrik/plug_and_play) - Set up a Plug application with less boilerplate.
*   [plug\_auth (⭐67)](https://github.com/bitgamma/plug_auth) - Collection of authentication-related plugs.
*   [plug\_canonical\_host (⭐40)](https://github.com/remiprev/plug_canonical_host) - Plug to ensure all requests are served from a single canonical host.
*   [plug\_checkup (⭐73)](https://github.com/ggpasqualino/plug_checkup) - Plug for adding simple health checks to your app.
*   [plug\_cloudflare (⭐23)](https://github.com/c-rack/plug_cloudflare) - Inspired by mod\_cloudflare, this Elixir plug parses Cloudflares CF-Connecting-IP HTTP request header into Plug.Conn's remote\_ip field.
*   [plug\_forward\_peer (⭐25)](https://github.com/awetzel/plug_forwarded_peer) - Very simple plug which reads X-Forwarded-For or Forwarded header according to RFC7239 and fill conn.remote\_ip with the root client ip.
*   [plug\_fprof (⭐4)](https://github.com/obmarg/plug_fprof) - A Plug that adds fprof tracing to requests, to allow for easy profiling.
*   [plug\_heartbeat (⭐36)](https://github.com/whatyouhide/plug_heartbeat) - A plug for responding to heartbeat requests.
*   [plug\_jwt (⭐39)](https://github.com/bryanjos/plug_jwt) - Plug for JWT authentication.
*   [plug\_password (⭐10)](https://github.com/azranel/plug_password) - Plug for adding simple cookie-based authentication.
*   [plug\_rails\_cookie\_session\_store (⭐97)](https://github.com/cconstantin/plug_rails_cookie_session_store) - Rails compatible Plug session store.
*   [plug\_redirect\_https (⭐7)](https://github.com/stocks29/plug_redirect_https) - Plug to redirect http requests to https requests behind a reverse proxy.
*   [plug\_require\_header (⭐27)](https://github.com/DevL/plug_require_header) - Require and extract HTTP headers and handle missing ones.
*   [plug\_response\_header (⭐12)](https://github.com/c-rack/plug_response_header) - easy manipulation of HTTP response headers.
*   [plug\_ribbon (⭐24)](https://github.com/stnly/plug_ribbon) - Injects a ribbon to your web application in the development environment.
*   [plug\_secex (⭐30)](https://github.com/techgaun/plug_secex) - Plug that adds various HTTP Headers to make Phoenix/Elixir app more secure.
*   [plug\_session\_memcached (⭐15)](https://github.com/gutschilla/plug-session-memcached) - A very simple memcached session store for Elixir's plug.
*   [plug\_sigaws (⭐1)](https://github.com/handnot2/plug_sigaws) - AWS Signature V4 authentication protection for Phoenix/Plug Routes ([Docs](https://hexdocs.pm/plug_sigaws/PlugSigaws.html)).
*   [plug\_statsd (⭐49)](https://github.com/jeffweiss/plug_statsd) - A plug for automatically sending timing and count metrics to statsd.
*   [pluggable (⭐18)](https://github.com/mruoss/pluggable) - Build `plug`-like pipelines with your own token (instead of `%Plug.Conn{}`).
*   [plugs (⭐19)](https://github.com/sugar-framework/plugs) - Collection of Plug middleware for web applications.
*   [plugsnag (⭐67)](https://github.com/jarednorman/plugsnag) - Bugsnag notifier for Elixir's plug.
*   [raygun (⭐19)](https://github.com/cobenian/raygun) - Capture bugs and send them to Raygun.
*   [react\_phoenix (⭐505)](https://github.com/geolessel/react-phoenix) - Render React.js components in Phoenix views focusing on easy installation and Brunch compatibility.
*   [recaptcha (⭐113)](https://github.com/samueljseay/recaptcha) - A simple reCaptcha 2 library for Elixir applications.
*   [resin (⭐4)](https://github.com/Frost/resin) - Resin is a plug that will add a configurable delay to every request that's passing through it, unless run in production.
*   [revision\_plate\_ex (⭐4)](https://github.com/KazuCocoa/revision_plate_ex) - Plug application and middleware that serves endpoint returns application's REVISION.
*   [rummage\_ecto (⭐212)](https://github.com/Excipients/rummage_ecto) - A configurable framework to search, sort and paginate Ecto Queries.
*   [rummage\_phoenix (⭐150)](https://github.com/Excipients/rummage_phoenix) - A support framework for searching, sorting and paginating models in Phoenix, with HTML support.
*   [scaffold (⭐7)](https://github.com/gausby/scaffold) - A mix task for creating new projects based on templates fetched from a Git-repo.
*   [scrivener (⭐558)](https://github.com/drewolson/scrivener) - Paginate your Ecto queries.
*   [scrivener\_headers (⭐53)](https://github.com/doomspork/scrivener_headers) - Helpers for paginating API responses with Scrivener and HTTP headers.
*   [scrivener\_html (⭐126)](https://github.com/mgwidmann/scrivener_html) - Helpers built to work with Scrivener's page struct to easily build HTML output for various CSS frameworks.
*   [sentinel (⭐105)](https://github.com/britton-jb/sentinel) - An authentication framework for Phoenix extending guardian with routing and other basic functionality.
*   [surface (⭐2.1k)](https://github.com/msaraiva/surface) - A server-side rendering component library for Phoenix.
*   [torch (⭐1.2k)](https://github.com/infinitered/torch) - Torch is a rapid admin generator for Phoenix apps. It uses generators rather than DSLs to ensure that the code remains maintainable.
*   [trailing\_format\_plug (⭐25)](https://github.com/mschae/trailing_format_plug) - An Elixir plug to support legacy APIs that use a rails-like trailing format.
*   [turn\_the\_page](https://hex.pm/packages/turn_the_page) - Fast, simple and lightweight pagination system for your Elixir application.
*   [webassembly (⭐72)](https://github.com/herenowcoder/webassembly) - Web DSL for Elixir.
*   [weebo (⭐2)](https://github.com/stevenschobert/weebo) - An XML-RPC parser/formatter for Elixir, with full support for datatype mapping.

## Frameworks

*Web development frameworks.*

*   [Ash Framework (⭐2k)](https://github.com/ash-project/ash) - A declarative, resource-oriented application framework for Elixir.
*   [exelli (⭐16)](https://github.com/pigmej/exelli) - An Elli Elixir wrapper with some sugar syntax goodies.
*   [Flowbite](https://flowbite.com/docs/getting-started/phoenix/) - An open-source UI component library built with Tailwind CSS and compatible with Phoenix/Elixir.
*   [Hologram (⭐674)](https://github.com/bartblast/hologram) - Full stack Elixir web framework that intelligently transpiles Elixir client-side code to JavaScript.
*   [kitto (⭐959)](https://github.com/kittoframework/kitto) - A framework for interactive dashboards.
*   [n2o (⭐1.3k)](https://github.com/synrc/n2o) - Distributed Application Server.
*   [nitro (⭐54)](https://github.com/synrc/nitro) - Nitrogen-compatible Web Framework.
*   [Petal Components (⭐1k)](https://github.com/petalframework/petal_components) - A set of HEEX components that makes it easy for Phoenix developers to build beautiful web apps.
*   [phoenix (⭐22k)](https://github.com/phoenixframework/phoenix) - Elixir Web Framework targeting full-featured, fault tolerant applications with realtime functionality.
*   [placid (⭐196)](https://github.com/slogsdon/placid) - A REST toolkit for building highly-scalable and fault-tolerant HTTP APIs with Elixir.
*   [rackla (⭐269)](https://github.com/AntonFagerberg/rackla) - API Gateways in Elixir.
*   [relax (⭐122)](https://github.com/AgilionApps/relax) - Simple Elixir implementation of a [jsonapi.org](http://jsonapi.org) server.
*   [rest (⭐83)](https://github.com/synrc/rest) - Micro-REST framework with typed JSON.
*   [RIG (⭐602)](https://github.com/Accenture/reactive-interaction-gateway) - Create low-latency, interactive user experiences for stateless microservices.
*   [sugar (⭐434)](https://github.com/sugar-framework/sugar) - Modular web framework for Elixir.
*   [trot (⭐420)](https://github.com/hexedpackets/trot) - An Elixir web micro-framework.

## Games

*Libraries for and implementations of games.*

*   [Binbo (⭐128)](https://github.com/DOBRO/binbo) - A chess representation written in Erlang using [Bitboards](https://www.chessprogramming.org/Bitboards), ready for use on game servers.
*   [ECSx](https://hexdocs.pm/ecsx/initial_setup.html) - An Entity-Component-System framework providing a battle ship game as a tutorial ([read more on Dockyard blog](https://dockyard.com/blog/2023/07/06/ecsx-a-new-approach-to-game-development-in-elixir)).
*   [entice (⭐121)](https://github.com/entice/entice) - A distributed Entity-Component-System framework, providing its own example MMORPG server.
*   [mines (⭐48)](https://github.com/kevlar1818/mines) - A minesweeper clone in the terminal.
*   [pictionary (⭐34)](https://github.com/Arp-G/pictionary) - A multiplayer guessing and drawing game ([skribbl.io](https://skribbl.io/) clone).
*   [rayex (⭐60)](https://github.com/shiryel/rayex) - Raylib bindings to Elixir for games programming.
*   [Rovex (⭐14)](https://github.com/emadb/rovex) - An implementation of the Mars Rover kata in Elixir transformed in a basic multiplayer game.
*   [vim\_snake (⭐22)](https://github.com/theanht1/vim_snake) - A classical multiplayer snake game with Vim-style keybinding built with Phoenix framework.

## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

*   [distance\_api\_matrix (⭐30)](https://github.com/C404/distance-matrix-api) - Provide distance and heading calculations via Google distance matrix api.
*   [geo (⭐657)](https://github.com/bryanjos/geo) - A collection of GIS functions for Elixir.
*   [geocalc (⭐153)](https://github.com/yltsrc/geocalc) - Calculate distance, bearing and more between latitude/longitude points.
*   [geocoder (⭐127)](https://github.com/knrz/geocoder) - A simple, efficient geocoder/reverse geocoder with a built-in cache.
*   [geohash (⭐28)](https://github.com/polmuz/elixir-geohash) - Geohash encode/decode library.
*   [geohash\_nif (⭐1)](https://github.com/wstucco/geohash_nif/) - Drop in replacement for Geohash encode/decode library implemented as a NIF.
*   [geohax (⭐12)](https://github.com/evuez/geohax) - Geohash encoding and decoding with neighbors finder.
*   [geoip (⭐123)](https://github.com/navinpeiris/geoip) - Find geolocation for a given IP, hostname or `Plug.Conn`.
*   [geolix (⭐191)](https://github.com/mneudert/geolix) - MaxMind GeoIP2 database reader/decoder.
*   [geonames (⭐24)](https://github.com/pareeohnos/geonames-elixir) - A simple Elixir wrapper around the GeoNames API.
*   [ip2location (⭐19)](https://github.com/nazipov/ip2location-elixir) - An Elixir library for IP2Location database.
*   [ipgeobase (⭐7)](https://github.com/sergey-chechaev/elixir_ipgeobase) - Find Russian and Ukraine city by IP address and find country for other country.
*   [proj (⭐9)](https://github.com/CandyGumdrop/proj) - Elixir coordinate conversion library using OSGeo's PROJ.4.
*   [segseg (⭐6)](https://github.com/pkinney/segseg_ex) - Segment-segment intersection classifier and calculator.
*   [srtm (⭐7)](https://github.com/adriankumpf/srtm) - Query locations for elevation data from the NASA Shuttle Radar Topography Mission.
*   [topo (⭐161)](https://github.com/pkinney/topo) - A Geometry library for Elixir that calculates spatial relationships between two geometries.
*   [wheretz (⭐11)](https://github.com/UA3MQJ/wheretz) - Elixir version of Ruby gem for lookup of timezone by georgraphic coordinates.

## GUI

*Libraries for writing Graphical User Interfaces.*

*   [scenic (⭐2k)](https://github.com/boydm/scenic) - Portable 2D UI framework.

## Hardware

*Hardware related things like I/O interfaces and such.*

*   [elixir-circuits](https://github.com/elixir-circuits) - Elixir access to hardware I/O interfaces such as GPIO, I2C, and SPI (old version [elixir\_ale (⭐344)](https://github.com/fhunleth/elixir_ale)).
*   [nerves (⭐2.4k)](https://github.com/nerves-project/nerves) - Framework for building firmware for platforms like Raspberry Pi and BeagleBone Black.

## HTML

*Libraries and implementations working with HTML (for xml tools please go to the [XML](#xml) section).*

*   [floki (⭐2.1k)](https://github.com/philss/floki) - A simple HTML parser that enables searching using CSS like selectors.
*   [html\_sanitize\_ex (⭐281)](https://github.com/rrrene/html_sanitize_ex) - HTML sanitizer for Elixir.
*   [meseeks (⭐322)](https://github.com/mischov/meeseeks#html) - A library for parsing and extracting data from HTML and XML with CSS or XPath selectors.
*   [modest\_ex (⭐31)](https://github.com/f34nk/modest_ex) - A library to do pipeable transformations on html strings with CSS selectors, e.g. find(), prepend(), append(), replace() etc.
*   [myhtmlex (⭐14)](https://github.com/Overbryd/myhtmlex) - Elixir/Erlang bindings for lexborisov's myhtml.
*   [readability (⭐278)](https://github.com/keepcosmos/readability) - Readability is for extracting and curating articles.
*   [texas](https://gitlab.com/dgmcguire/texas) - Texas is a powerful abstraction over updating your clients using server-side rendering and server-side Virtual DOM diff/patching.
*   [tidy\_ex (⭐9)](https://github.com/f34nk/tidy_ex) - Elixir binding to the granddaddy of HTML tools <http://www.html-tidy.org>.
*   [vnu-elixir (⭐55)](https://github.com/angelikatyborska/vnu-elixir) - Elixir client for the [Nu HTML Checker](https://validator.w3.org/nu/). Provides HTML, CSS, and SVG validation.

## HTTP

*Libraries for working with HTTP and scraping websites.*

*   [Ace (⭐305)](https://github.com/CrowdHailer/Ace) - HTTP web server and client, supports http1 and http2.
*   [cauldron (⭐72)](https://github.com/meh/cauldron) - An HTTP/SPDY server as a library.
*   [Crawler (⭐954)](https://github.com/fredwu/crawler) - A high performance web crawler in Elixir.
*   [Crawly (⭐1k)](https://github.com/oltarasenko/crawly) - high-level web crawling & scraping framework for Elixir.
*   [elli (⭐663)](https://github.com/knutin/elli) - Elli is a webserver you can run inside your Erlang application to expose an HTTP API.
*   [etag\_plug (⭐22)](https://github.com/sascha-wolf/etag_plug) - A simple to use shallow ETag plug.
*   [explode (⭐44)](https://github.com/pkinney/explode) - An easy utility for responding with standard HTTP/JSON error payloads in Plug- and Phoenix-based applications.
*   [exvcr (⭐739)](https://github.com/parroty/exvcr) - HTTP request/response recording library for Elixir, inspired by VCR.
*   [finch (⭐1.3k)](https://github.com/sneako/finch) - An HTTP client with a focus on performance, built on top of Mint and NimblePool.
*   [fuzzyurl (⭐20)](https://github.com/gamache/fuzzyurl.ex) - An Elixir library for parsing, constructing, and wildcard-matching URLs. Also available for [Ruby (⭐13)](https://github.com/gamache/fuzzyurl.rb) and [JavaScript (⭐4)](https://github.com/gamache/fuzzyurl.js).
*   [gun (⭐913)](https://github.com/ninenines/gun) - HTTP/1.1, HTTP/2 and Websocket client for Erlang/OTP.
*   [hackney (⭐1.4k)](https://github.com/benoitc/hackney) - Simple HTTP client written in Erlang.
*   [http (⭐12)](https://github.com/slogsdon/http) - HTTP server for Elixir.
*   [http\_digex (⭐5)](https://github.com/techgaun/http_digex) - A module to create basic digest HTTP auth header.
*   [http\_proxy (⭐60)](https://github.com/KazuCocoa/http_proxy) - Multi port HTTP Proxy.
*   [httpoison (⭐2.3k)](https://github.com/edgurgel/httpoison) - Yet Another HTTP client for Elixir powered by hackney.
*   [httpotion (⭐723)](https://github.com/myfreeweb/httpotion) - Fancy HTTP client for Elixir, based on ibrowse.
*   [ivar (⭐16)](https://github.com/swelham/ivar) - A lightweight wrapper around HTTPoison that provides a fluent and composable way to build http requests.
*   [lhttpc (⭐1)](https://github.com/talko/lhttpc) - A lightweight HTTP/1.1 client implemented in Erlang.
*   [mint (⭐1.4k)](https://github.com/ericmj/mint) - Functional HTTP client for Elixir with support for HTTP/1 and HTTP/2.
*   [mnemonic\_slugs (⭐29)](https://github.com/devshane/mnemonic_slugs) - A memorable, mnemonic slug generator in Elixir.
*   [mochiweb (⭐1.9k)](https://github.com/mochi/mochiweb) - MochiWeb is an Erlang library for building lightweight HTTP servers.
*   [neuron (⭐331)](https://github.com/uesteibar/neuron) - A GraphQL client for Elixir.
*   [plug\_wait1 (⭐1)](https://github.com/wait1/plug_wait1) - Plug adapter for the wait1 protocol.
*   [raxx (⭐408)](https://github.com/CrowdHailer/raxx) - Interface for HTTP webservers, frameworks and clients.
*   [req (⭐1.2k)](https://github.com/wojtekmach/req) - A batteries-included HTTP client for Elixir.
*   [river (⭐82)](https://github.com/peburrows/river) - An HTTP/2 client that is lightweight and lightning fast.
*   [scrape (⭐334)](https://github.com/Anonyfox/elixir-scrape) - Scrape any website, article or RSS/Atom Feed with ease.
*   [sparql\_client (⭐29)](https://github.com/marcelotto/sparql_client) - A [SPARQL protocol](https://www.w3.org/TR/sparql11-protocol/) client for Elixir.
*   [SpiderMan (⭐27)](https://github.com/feng19/spider_man) - A base-on Broadway fast high-level web crawling & scraping framework for Elixir.
*   [tesla (⭐2k)](https://github.com/teamon/tesla) - HTTP client library, with support for middleware and multiple adapters.
*   [Tube (⭐12)](https://github.com/narrowtux/Tube) - Pure Elixir WebSocket client library.
*   [uri\_query (⭐14)](https://github.com/shhavel/uri_query) - URI encode nested GET parameters and array values in Elixir.
*   [uri\_template (⭐18)](https://github.com/pezra/ex-uri-template) - RFC6570 compliant URI template processor for Elixir.
*   [web\_socket (⭐63)](https://github.com/slogsdon/plug-web-socket) - An exploration into a stand-alone library for Plug applications to easily adopt WebSockets.
*   [webdriver (⭐119)](https://github.com/stuart/elixir-webdriver) - This is an implementation of the WebDriver protocol client. It currently supports PhantomJS, FireFox, ChromeDriver and remote webdriver servers (e.g. Selenium).
*   [yuri (⭐13)](https://github.com/kemonomachi/yuri) - Simple struct for representing URIs.

## Images

*Libraries for working with and manipulating images.*

*   [alchemic\_avatar (⭐58)](https://github.com/zhangsoledad/alchemic_avatar) - Elixir library for generating letter avatar from string.
*   [artifact (⭐44)](https://github.com/doomspork/artifact) - File upload and on-the-fly processing for Elixir.
*   [bump (⭐4)](https://github.com/evanfarrar/ex_bump) - A BMP file writer in pure Elixir.
*   [chunky\_svg (⭐32)](https://github.com/mmmries/chunky_svg) -  A library for drawing things with SVG.
*   [cloudex (⭐106)](https://github.com/smeevil/cloudex) - Cloudex is an Elixir library that can upload image files or urls to Cloudinary.
*   [eikon (⭐12)](https://github.com/tchoutri/Eikon) - An Elixir library providing a read-only interface for image files.
*   [elixir\_exif (⭐13)](https://github.com/sschneider1207/ElixirExif) - Parse exif tags and thumbnail data from jpeg files.
*   [ex\_image\_info (⭐99)](https://github.com/rNoz/ex_image_info) - An Elixir library to parse images (binaries) and get the dimensions, detected mime-type and overall validity for a set of image formats.
*   [exexif (⭐44)](https://github.com/pragdave/exexif) - Pure Elixir library to extract TIFF and EFIX metadata from jpeg files.
*   [exfavicon (⭐8)](https://github.com/ikeikeikeike/exfavicon) - An Elixir library for discovering favicons.
*   [gi](https://github.com/LangPham/gi) - An Elixir wrapper for GraphicsMagick command line.
*   [identicon (⭐27)](https://github.com/rbishop/identicon) - An Elixir library for generating 5x5 identicons.
*   [image64](https://hex.pm/packages/image64) - A tool for working with base64 encoded images.
*   [imagineer (⭐118)](https://github.com/SenecaSystems/imagineer) - Image parsing in Elixir.
*   [imgex (⭐33)](https://github.com/ianwalter/imgex) - Unofficial client library for generating imgix URLs in Elixir.
*   [mogrify (⭐576)](https://github.com/route/mogrify) - An Elixir wrapper for ImageMagick command line.
*   [png (⭐57)](https://github.com/yuce/png) - A pure Erlang library for creating PNG images. It can currently create 8 and 16 bit RGB, RGB with alpha, indexed, grayscale and grayscale with alpha images.
*   [thumbnex (⭐75)](https://github.com/talklittle/thumbnex) - Create thumbnails from images and video screenshots.
*   [thumbor\_client (⭐4)](https://github.com/globocom/thumbor-client-ex) - Client for Thumbor.

## Instrumenting / Monitoring

*Libraries for collecting and exporting metrics.*

*   [app\_optex (⭐5)](https://github.com/sashman/app_optex) - Client for AppOptics API. Send metrics and tags to AppOptics time series service.
*   [appsignal-elixir (⭐289)](https://github.com/appsignal/appsignal-elixir/) - Collects error and performance data from your Elixir applications and sends it to [AppSignal](https://appsignal.com/).
*   [elixometer (⭐827)](https://github.com/pinterest/elixometer) - A light Elixir wrapper around exometer.
*   [erlang-metrics (⭐70)](https://github.com/benoitc/erlang-metrics) - A generic interface to different metrics systems in Erlang.
*   [exometer (⭐528)](https://github.com/Feuerlabs/exometer) - Basic measurement objects and probe behavior in Erlang.
*   [folsom\_ddb (⭐6)](https://github.com/dalmatinerdb/folsom_ddb) - DalmatinerDB backend to store folsom metrics.
*   [graphitex (⭐4)](https://github.com/msoedov/graphitex) - Graphite/Carbon client for Elixir.
*   [instream (⭐227)](https://github.com/mneudert/instream) - InfluxDB driver for Elixir.
*   [instrumental (⭐10)](https://github.com/undeadlabs/instrumental-ex) - An Elixir client for [Instrumental](https://instrumentalapp.com/).
*   [newrelic.ex (⭐63)](https://github.com/romul/newrelic.ex) - Collects metrics from your Elixir/Phoenix application and sends them to [NewRelic](https://newrelic.com/).
*   [prom\_ex (⭐663)](https://github.com/akoutmos/prom_ex) - Prometheus metrics and Grafana dashboards for all of your favorite Elixir libraries.
*   [prometheus (⭐351)](https://github.com/deadtrickster/prometheus.erl) - [Prometheus.io](https://prometheus.io) monitoring system and time series database client in Erlang.
*   [prometheus-ecto (⭐78)](https://github.com/deadtrickster/prometheus-ecto) - Ecto instrumenter for prometheus.ex.
*   [prometheus-phoenix (⭐72)](https://github.com/deadtrickster/prometheus-phoenix) - Phoenix instrumenter for prometheus.ex.
*   [prometheus-plugs (⭐54)](https://github.com/deadtrickster/prometheus-plugs) - Plugs instrumenters/exporter for prometheus.ex.
*   [prometheus.ex (⭐419)](https://github.com/deadtrickster/prometheus.ex) - Elixir-friendly [Prometheus.io](https://prometheus.io) monitoring system and time series database client.
*   [prometheus\_process\_collector (⭐52)](https://github.com/deadtrickster/prometheus_process_collector) - Prometheus collector which exports the current state of process metrics including cpu, memory, file descriptor usage and native threads count as well as the process start and up times.
*   [spandex (⭐342)](https://github.com/spandex-project/spandex) - Platform agnostic tracing library originally developed for Datadog APM.
*   [telemetry (⭐892)](https://github.com/beam-telemetry/telemetry) - Dynamic dispatching library for metrics and instrumentations.
*   [wobserver (⭐926)](https://github.com/shinyscorpion/wobserver) - Web based metrics, monitoring, and observer.

## JSON

*Libraries and implementations working with JSON.*

*   [exjson (⭐71)](https://github.com/guedes/exjson) - JSON parser and generator in Elixir.
*   [ja\_serializer (⭐639)](https://github.com/AgilionApps/ja_serializer) - JSONAPI.org Serialization in Elixir.
*   [jason (⭐1.6k)](https://github.com/michalmuskala/jason) - A blazing fast JSON parser and generator in pure Elixir.
*   [jazz (⭐60)](https://github.com/meh/jazz) - Yet another library to handle JSON in Elixir.
*   [joken (⭐794)](https://github.com/bryanjos/joken) - Encodes and decodes JSON Web Tokens.
*   [jose (⭐320)](https://github.com/potatosalad/erlang-jose) - JSON Object Signing and Encryption (JOSE) for Erlang and Elixir.
*   [json (⭐218)](https://github.com/cblage/elixir-json) - Native JSON library for Elixir.
*   [json\_pointer (⭐11)](https://github.com/xavier/json_pointer) - Implementation of RFC 6901 which defines a string syntax for identifying a specific value within a JSON document.
*   [json\_stream\_encoder (⭐8)](https://github.com/TreyE/json_stream_encoder) - JsonStreamEncoder is a streaming encoder for streaming JSON to an IOish thing in Elixir.
*   [json\_web\_token\_ex (⭐144)](https://github.com/garyf/json_web_token_ex) - An Elixir implementation of the JSON Web Token (JWT) Standards Track (RFC 7519).
*   [jsonapi (⭐501)](https://github.com/jeregrine/jsonapi) - A project that will render your data models into [JSONAPI Documents](http://jsonapi.org/format/).
*   [jsonc (⭐0)](https://github.com/massivefermion/jsonc) - Utilities for working with [jsonc](https://komkom.github.io/jsonc-playground), a superset of json.
*   [jsx (⭐699)](https://github.com/talentdeficit/jsx) - An Erlang application for consuming, producing, and manipulating json.
*   [jwalk (⭐7)](https://github.com/jr0senblum/jwalk) - Helper module for working with Erlang representations of JSON.
*   [jwtex (⭐5)](https://github.com/mschae/jwtex) - A library to encode and decode [JWT tokens](http://jwt.io/).
*   [poison (⭐2k)](https://github.com/devinus/poison) - Poison is a new JSON library for Elixir focusing on wicked-fast speed without sacrificing simplicity, completeness, or correctness.
*   [tiny (⭐47)](https://github.com/whitfin/tiny) - Tiny, fast and fully compliant JSON parser for Elixir.
*   [world\_json (⭐9)](https://github.com/camshaft/world_json_ex) - topojson country and state/province collections for elixir/erlang.

## Languages

*Languages built on top of Elixir.*

*   [Elchemy (⭐1.1k)](https://github.com/wende/elchemy) - Compiler allowing to translate Elm programming language code to Elixir.
*   [lighthouse\_scheme (⭐42)](https://github.com/jwhiteman/lighthouse-scheme) - A small Lisp-like language and interactive REPL, built in Elixir.
*   [Monkey (⭐141)](https://github.com/fabrik42/writing_an_interpreter_in_elixir) - Elixir implementation of an interpreter and REPL for the js-like Monkey programming language.

## Lexical analysis

*All about lexical analyser, lexer, scanner, tokenizer or compiler.*

*   [abnf\_parsec (⭐55)](https://github.com/princemaple/abnf_parsec) - ABNF in and parser out.
*   [ex\_abnf (⭐62)](https://github.com/marcelog/ex_abnf) - Parser for ABNF Grammars in Elixir.
*   [lex\_luthor (⭐33)](https://github.com/jamesotron/lex_luthor) - LexLuthor is a Lexer in Elixir which uses macros to generate a reusable lexers.

## Logging

*Logging infos and messages.*

*   [bunyan (⭐90)](https://github.com/bunyan-logger/bunyan) - Bunyan: An Elixir Logger.
*   [ecto\_dev\_logger (⭐178)](https://github.com/fuelen/ecto_dev_logger) - An alternative logger for Ecto queries that helps in debugging.
*   [exlager (⭐65)](https://github.com/khia/exlager) - Elixir binding for lager.
*   [gelf\_logger (⭐29)](https://github.com/jschniper/gelf_logger) - A Logger backend that will generate Graylog Extended Log Format (GELF) messages.
*   [honeybadger (⭐183)](https://github.com/honeybadger-io/honeybadger-elixir) - Send logs and custom events to [Honeybadger](https://www.honeybadger.io/).
*   [json\_logger (⭐24)](https://github.com/LeeroyDing/json_logger) - JSON Logger is a logger backend that outputs elixir logs in JSON format.
*   [lager (⭐41)](https://github.com/basho/lager) - A logging framework for Erlang/OTP by basho.com.
*   [lager\_logger (⭐29)](https://github.com/PSPDFKit-labs/lager_logger) - A lager backend that forwards all log messages to Elixir's Logger.
*   [logfmt (⭐27)](https://github.com/jclem/logfmt-elixir) - Logfmt is a module for encoding and decoding logfmt-style log lines.
*   [logger\_logstash\_backend (⭐72)](https://github.com/marcelog/logger_logstash_backend) - A backend for the Elixir Logger that will send logs to the Logstash UDP input.
*   [logglix (⭐10)](https://github.com/pragmaticivan/logglix) - A logger backend for posting errors to Loggly.
*   [logster (⭐210)](https://github.com/navinpeiris/logster) - Easily parsable, one-line logging for Phoenix and Plug applications, inspired by Lograge.
*   [metrix (⭐52)](https://github.com/rwdaigle/metrix) - Log custom app metrics to stdout for use by Librato and other downstream processors.
*   [mstore (⭐11)](https://github.com/dalmatinerdb/mstore) - MStore is a experimental metric store build in erlang, the primary functions are open, new, get and put.
*   [quiet\_logger (⭐2)](https://github.com/Driftrock/quiet_logger/pull/1) - A simple plug to suppress health check logging (e.g.: when using Kubernetes).
*   [rogger (⭐10)](https://github.com/duartejc/rogger) - Elixir logger to publish log messages in RabbitMQ.
*   [rollbax (⭐241)](https://github.com/elixir-addicts/rollbax) - Exception tracking and logging to [Rollbar](https://rollbar.com/).
*   [slack\_logger\_backend (⭐32)](https://github.com/craigp/slack_logger_backend) - A logger backend for posting errors to Slack.
*   [syslog (⭐86)](https://github.com/Vagabond/erlang-syslog) - Erlang port driver for interacting with syslog via syslog(3).
*   [timber (⭐214)](https://github.com/timberio/timber-elixir) - Structured logging platform; turns raw text logs into rich structured events.
*   [youtrack\_logger\_backend (⭐3)](https://github.com/unifysell/youtrack_logger_backend) - A logger backend that will post messages to [YouTrack](https://www.jetbrains.com/youtrack/) (an issue tracker made by JetBrains).

## Macros

*Macros for faster and easier development. Sugar for your code.*

*   [anaphora (⭐18)](https://github.com/sviridov/anaphora-elixir) - Anaphora is the anaphoric macro collection for Elixir. An anaphoric macro is one that deliberately captures a variable (typically it) from forms supplied to the macro.
*   [apix (⭐12)](https://github.com/liveforeverx/apix) - Simple convention and DSL for transformation of elixir functions to an API for later documentation and or validation.
*   [backports (⭐4)](https://github.com/leifg/backports) - Use new functions in Elixir 1.1 and 1.2.
*   [crudry (⭐93)](https://github.com/gabrielpra1/crudry) - Crudry is an elixir library for DRYing CRUD of Phoenix Contexts and Absinthe Resolvers.
*   [eventsourced (⭐105)](https://github.com/slashdotdash/eventsourced) - Build functional, event-sourced domain models.
*   [expat (⭐176)](https://github.com/vic/expat) - Reusable, composable patterns across Elixir libraries.
*   [guardsafe (⭐26)](https://github.com/DevL/guardsafe) - Macros expanding into code that can be safely used in guard clauses.
*   [kwfuns (⭐2)](https://github.com/RobertDober/lab42_defkw) - Macros to create functions with syntax based keyword parameters with default values.
*   [lineo (⭐0)](https://github.com/camshaft/lineo) - parse transform for accurate line numbers.
*   [matcha (⭐91)](https://github.com/christhekeele/matcha) - First-class match specifications for Elixir `:ets` querying and function call tracing.
*   [mdef (⭐49)](https://github.com/pragdave/mdef) - Easily define multiple function heads in Elixir.
*   [named\_args (⭐28)](https://github.com/mgwidmann/named_args) - Allows named arg style arguments in Elixir.
*   [ok\_jose (⭐100)](https://github.com/vic/ok_jose) - Pipe elixir functions that match `{:ok,_}`, `{:error,_}` tuples or custom patterns.
*   [opus (⭐369)](https://github.com/zorbash/opus) - A framework for pluggable business logic components.
*   [pathex (⭐356)](https://github.com/hissssst/pathex) - Zero-dependency, blazing fast functional lenses.
*   [pattern\_tap (⭐58)](https://github.com/mgwidmann/elixir-pattern_tap) - Macro for tapping into a pattern match while using the pipe operator.
*   [pipe\_here (⭐34)](https://github.com/vic/pipe_here) - Easily pipe values into any argument position.
*   [pipes (⭐325)](https://github.com/batate/elixir-pipes) - Macros for more flexible composition with the Elixir Pipe operator.
*   [pit (⭐29)](https://github.com/vic/pit) - Transform values as they flow inside a pipe.
*   [rebind (⭐0)](https://github.com/camshaft/rebind) - rebind parse transform for Erlang.
*   [rulex (⭐13)](https://github.com/awetzel/rulex) - Simple rule handler using Elixir pattern matching.
*   [shorter\_maps (⭐236)](https://github.com/meyercm/shorter_maps) - \~M sigil for map shorthand. `~M{id name} ~> %{id: id, name: name}`.
*   [typed\_struct (⭐753)](https://github.com/ejpcmac/typed_struct) - An Elixir library for defining structs with a type without writing boilerplate code.
*   [typed\_structor (⭐17)](https://github.com/elixir-typed-structor/typed_structor) - A library for defining structs with types effortlessly.
*   [unsafe (⭐12)](https://github.com/whitfin/unsafe) - Generate easy unsafe (!) bindings for Elixir functions.

## Markdown

*Libraries and tools working with Markdown and such.*

*   [cmark (⭐98)](https://github.com/asaaki/cmark.ex) - Elixir NIF for CommonMark (in C), a parser following the CommonMark spec.
*   [discount (⭐21)](https://github.com/asaaki/discount.ex) - Elixir NIF for discount, a Markdown parser.
*   [earmark (⭐894)](https://github.com/pragdave/earmark) - Markdown parser for Elixir.
*   [Markdown (⭐90)](https://github.com/devinus/markdown) - Implemented entirely as a NIF binding to the Hoedown library.
*   [Pandex (⭐64)](https://github.com/filterkaapi/pandex) - Lightweight Elixir wrapper for Pandoc. Converts Markdown, CommonMark, HTML, Latex, HTML, HTML5, opendocument, rtf, texttile, asciidoc to each other.

## Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

*   [address\_us (⭐30)](https://github.com/smashedtoatoms/address_us) - Library for parsing US Addresses into their individual parts.
*   [AlloyCI (⭐288)](https://github.com/AlloyCI/alloy_ci) - AlloyCI is a Continuous Integration, Deployment, and Delivery coordinator, written in Elixir, that takes advantage of the GitLab CI Runner, and its capabilities as executor, to prepare and run your pipelines.
*   [Apex (⭐279)](https://github.com/bjro/apex) - Awesome Print for Elixir.
*   [AtomVM (⭐1.8k)](https://github.com/bettio/AtomVM) - AtomVM allows to run Elixir/Erlang code on embedded devices such as ESP32 and STM32 microcontrollers.
*   [bupe (⭐84)](https://github.com/milmazz/bupe) - EPUB Generator and Parser.
*   [charm (⭐4)](https://github.com/tomgco/elixir-charm) - Use ANSI terminal characters to write colors and cursor positions.
*   [codec-beam (⭐171)](https://github.com/hkgumbs/codec-beam) - Generate Erlang VM byte code from Haskell.
*   [Countries (⭐155)](https://github.com/SebastianSzturo/countries) - Countries is a collection of all sorts of useful information for every country in the ISO 3166 standard.
*   [countriex (⭐31)](https://github.com/navinpeiris/countriex) - A pure elixir country data provider containing various information for every country in ISO 3166.
*   [cubdb (⭐610)](https://github.com/lucaong/cubdb) - CubDB is an embedded key-value database, written in the Elixir language. It runs locally, it is schema-less, and backed by a single file.
*   [dye (⭐21)](https://github.com/Kabie/dye) - A library for dyeing your terminal output.
*   [dynamic\_compile (⭐1)](https://github.com/okeuday/dynamic_compile) - Compile and load Erlang modules from string input.
*   [ecto\_autoslug\_field (⭐152)](https://github.com/sobolevn/ecto_autoslug_field) - Automatically creates slugs for your Ecto models.
*   [egaugex (⭐1)](https://github.com/Brightergy/egaugex) - Client to fetch and parse realtime data from egauge devices.
*   [elixir-browser (⭐106)](https://github.com/tuvistavie/elixir-browser) - Browser detection for Elixir.
*   [epub\_cover\_extractor (⭐6)](https://github.com/zelazna/epub_cover_extractor) - Extract cover from EPUB files.
*   [erlang\_term (⭐33)](https://github.com/okeuday/erlang_term) - Provide the in-memory size of Erlang terms, ignoring where these are stored.
*   [ex2ms (⭐201)](https://github.com/ericmj/ex2ms) - Translates Elixir functions to match specifications for use with `ets`.
*   [ex\_azure\_speech (⭐4)](https://github.com/ex-azure/ex_azure_speech) - An Elixir SDK implementation for the Microsoft Azure Speech Service.
*   [ex\_phone\_number (⭐268)](https://github.com/socialpaymentsbv/ex_phone_number) - Format, normalize, and validate phone numbers.
*   [ex\_rated (⭐457)](https://github.com/grempe/ex_rated) - Simple and flexible rate-limiting for API's or anything.
*   [exfcm (⭐1)](https://github.com/Hajto/ExFCM) - Simple wrapper for posting Firebase Cloud Messages.
*   [exisbn (⭐3)](https://github.com/solar05/exisbn) - ISBN validation and formatting library.
*   [exldap (⭐60)](https://github.com/jmerriweather/exldap) - A module for working with LDAP from Elixir.
*   [exlibris (⭐11)](https://github.com/pragdave/exlibris) - A collection of random library functions.
*   [expool (⭐29)](https://github.com/whitfin/expool) - A small process pooling library for parallel tasks in Elixir.
*   [exprint (⭐33)](https://github.com/parroty/exprintf) - A printf / sprintf library for Elixir, works as a wrapper for :io.format.
*   [expyplot (⭐33)](https://github.com/MaxStrange/expyplot) - Elixir interface for Plotting/Graphing library using matplotlib.pyplot.
*   [exquisite (⭐79)](https://github.com/meh/exquisite) - LINQ-like match\_spec generation for Elixir.
*   [exsync (⭐168)](https://github.com/falood/exsync) - Yet another Elixir reloader.
*   [funnel (⭐32)](https://github.com/chatgris/funnel) - Streaming Elixir API built upon ElasticSearch's percolation.
*   [gen\_task (⭐23)](https://github.com/Nebo15/gen_task) - Generic Task behavior that helps to encapsulate worker errors and recover from them in classic GenStage's.
*   [gimei\_ex (⭐7)](https://github.com/ma2gedev/gimei_ex) - Elixir port of gimei library.
*   [growl (⭐10)](https://github.com/zachallett/growl) - Simple wrapper for growl, the notification system for OSX.
*   [hammer (⭐858)](https://github.com/ExHammer/hammer) - A rate-limiter with pluggable storage backends, including Redis.
*   [html\_entities (⭐89)](https://github.com/martinsvalin/html_entities) - Elixir module for decoding HTML entities in a string.
*   [huex (⭐65)](https://github.com/xavier/huex) - Elixir client for Philips Hue connected light bulbs.
*   [indicado (⭐39)](https://github.com/thisiscetin/indicado) - Technical indicator library for Elixir with no dependencies.
*   [japan\_municipality\_key (⭐0)](https://github.com/hykw/japan_municipality_key) - Elixir Library for Japan municipality key converting.
*   [Jisho-Elixir (⭐35)](https://github.com/nbw/jisho_elixir) - An API wrapper for Jisho.org, an online Japanese dictionary. Allows users to search by word, symbol, and or tags (refer to docs).
*   [keys1value (⭐1)](https://github.com/okeuday/keys1value) - Erlang set associative map for key lists.
*   [licensir (⭐74)](https://github.com/unnawut/licensir) - A mix task that lists the license(s) of all installed packages in your project.
*   [mixgraph (⭐15)](https://github.com/sivsushruth/mixgraph) - An interactive dependency plotter for your Hex Package.
*   [mixstar (⭐12)](https://github.com/ma2gedev/mix-star) - MixStar starred GitHub repository that depends on your project.
*   [netrc (⭐4)](https://github.com/ma2gedev/netrcex) - Reads netrc files implemented in Elixir.
*   [notifier](https://hex.pm/packages/notifier) - A pluggable architecture for desktop notifications.
*   [onetime (⭐4)](https://github.com/ryo33/onetime-elixir) - An onetime key-value store for Elixir.
*   [pact (⭐77)](https://github.com/BlakeWilliams/pact) - Better dependency injection in Elixir for cleaner code and testing.
*   [passbook (⭐14)](https://github.com/Bounceapp/ex_passbook) - Elixir library to create Apple Wallet (.pkpass) files.
*   [phone (⭐106)](https://github.com/fcevado/phone) - A parser to get useful info from telephone numbers.
*   [porcelain (⭐957)](https://github.com/alco/porcelain) - Porcelain implements a saner approach to launching and communicating with external OS processes from Elixir.
*   [presentex (⭐12)](https://github.com/Cobenian/Presentex) - Elixir to HTML/JavaScript based presentation framework.
*   [quarantine (⭐4)](https://github.com/leorog/quarantine) - Quarantine is a tiny OTP application for feature toggles.
*   [ratekeeper (⭐14)](https://github.com/whitered/ratekeeper) - Rate limiter and rate-limited actions scheduler.
*   [ratx (⭐20)](https://github.com/liveforeverx/ratx) - Rate limiter and overload protection for erlang application.
*   [reprise (⭐43)](https://github.com/herenowcoder/reprise) - Simplified module reloader for Elixir.
*   [spawndir (⭐4)](https://github.com/jtmoulia/spawndir) - Spawns processes from the file system.
*   [spotify\_ex (⭐150)](https://github.com/jsncmgs1/spotify_ex) - An Elixir wrapper for the Spotify Web API.
*   [std\_json\_io (⭐30)](https://github.com/hassox/std_json_io) - Application for managing and communicating with IO servers via JSON.
*   [url\_unroller (⭐5)](https://github.com/semanticart/url_unroller) - Simple URL unroller (un-shortener) in Elixir.
*   [vessel (⭐24)](https://github.com/whitfin/vessel) - Elixir MapReduce interfaces with Hadoop Streaming integration.
*   [weighted\_random (⭐5)](https://github.com/JohnJocoo/weighted_random) - Weighted random picking.

## Native Implemented Functions

*Tools and libraries working with Erlang NIF.*

*   [hsnif (⭐25)](https://github.com/urbanserj/hsnif) - Tool that allows to write Erlang NIF libraries in Haskell.
*   [nifty (⭐29)](https://github.com/rossjones/nifty) - Helper script for setting up the boilerplate required when writing a NIF.
*   [Rustler (⭐4.5k)](https://github.com/hansihe/Rustler) - Library for writing NIFs for Erlang or Elixir safely in Rust. No segfaults.

## Natural Language Processing (NLP)

*Tools and libraries that work with human (natural) languages.*

*   [gibran (⭐65)](https://github.com/abitdodgy/gibran) - Gibran is an Elixir port of [WordsCounted (⭐162)](https://github.com/abitdodgy/words_counted), a natural language processor that extracts useful statistics from text.
*   [Paasaa (⭐121)](https://github.com/minibikini/paasaa) - Natural language detection for Elixir.
*   [Petrovich (⭐42)](https://github.com/petrovich/petrovich_elixir) - Elixir library to inflect Russian first, last, and middle names.
*   [Tongue (⭐19)](https://github.com/dannote/tongue) - Elixir port of Nakatani Shuyo's natural language detector.
*   [Woolly (⭐54)](https://github.com/pjhampton/woolly) - Woolly is an ambitious Text Mining and Natural Language Processing API for Elixir.

## Networking

*Libraries and tools for using network related stuff.*

*   [asn (⭐17)](https://github.com/ephe-meral/asn) - Can be used to map from IP to AS to ASN.
*   [chatter (⭐29)](https://github.com/dbeck/chatter_ex) - Secure message broadcasting based on a mixture of UDP multicast and TCP.
*   [download (⭐33)](https://github.com/asiniy/download) - Download files from the internet easily.
*   [eio (⭐14)](https://github.com/falood/eio) - Elixir server of engine.io.
*   [ExPcap (⭐33)](https://github.com/cobenian/expcap) - PCAP parser written in Elixir.
*   [Firezone (⭐7.4k)](https://github.com/firezone/firezone) - Open-source VPN server and egress firewall for Linux built on WireGuard. Firezone is easy to set up (all dependencies are bundled thanks to Chef Omnibus), secure, performant, and self hostable.
*   [FlyingDdns](https://gitlab.com/timopallach/FlyingDdns) - A dyndns server written in elixir.
*   [hades (⭐27)](https://github.com/fklement/hades) - A wrapper for NMAP written in Elixir.
*   [mac (⭐7)](https://github.com/ephe-meral/mac) - Can be used to find a vendor of a MAC given in hexadecimal string (according to IEEE).
*   [pool (⭐6)](https://github.com/slogsdon/pool) - Socket acceptor pool for Elixir.
*   [reagent (⭐92)](https://github.com/meh/reagent) - reagent is a socket acceptor pool for Elixir.
*   [sise (⭐0)](https://github.com/aytchell/sise) - A simple to use SSDP client.
*   [sockerl (⭐0)](https://github.com/Pouriya-Jahanbakhsh/sockerl) - Sockerl is an advanced Erlang/Elixir socket library for TCP protocols and provides fast, useful and easy-to-use API for implementing servers, clients and client connection pools.
*   [socket (⭐691)](https://github.com/meh/elixir-socket) - Socket wrapping for Elixir.
*   [sshkit (⭐156)](https://github.com/bitcrowd/sshkit.ex) - An Elixir toolkit for performing tasks on one or more servers, built on top of Erlang’s SSH application.
*   [torex (⭐10)](https://github.com/alexfilatov/torex) - Simple Tor connection library.
*   [tunnerl (⭐27)](https://github.com/surik/tunnerl) - SOCKS4 and SOCKS5 proxy server.
*   [wifi (⭐34)](https://github.com/gausby/wifi) - Various utility functions for working with the local Wifi network in Elixir.
*   [wpa\_supplicant (⭐5)](https://github.com/fhunleth/wpa_supplicant.ex) - Elixir interface to the wpa\_supplicant.

## Office

*Libraries for working with office suite documents.*

*   [elixlsx (⭐302)](https://github.com/xou/elixlsx) - A writer for XLSX files.
*   [excellent (⭐23)](https://github.com/leifg/excellent) - An OpenXL (Excel 2000) Parser for Elixir.
*   [xlsxir (⭐216)](https://github.com/kennellroxco/xlsxir) - Xlsx file parser with support for ISO 8601 date formats. Data is extracted to an Erlang Term Storage (ETS) table and is accessed through various functions.

## ORM and Datamapping

*Libraries that implement object-relational mapping or datamapping techniques.*

*   [amnesia (⭐703)](https://github.com/meh/amnesia) - Mnesia wrapper for Elixir.
*   [arbor (⭐241)](https://github.com/coryodaniel/arbor) - Ecto adjacency list and tree traversal.
*   [arc\_ecto (⭐255)](https://github.com/stavro/arc_ecto) - Arc.Ecto provides an integration with Arc and Ecto.
*   [atlas (⭐216)](https://github.com/chrismccord/atlas) - Object Relational Mapper for Elixir.
*   [barrel\_ex (⭐0)](https://github.com/jxub/barrel_ex) - [Barrel-db](https://barrel-db.org/) distributed document-oriented database REST client in Elixir.
*   [Bolt.Sips (⭐262)](https://github.com/florinpatrascu/bolt_sips) - Neo4j driver for Elixir using the Bolt protocol.
*   [boltun (⭐135)](https://github.com/bitgamma/boltun) - Transforms notifications from the Postgres LISTEN/NOTIFY mechanism into callback execution.
*   [caylir (⭐22)](https://github.com/mneudert/caylir) - Cayley driver for Elixir.
*   [comeonin\_ecto\_password (⭐35)](https://github.com/vic/comeonin_ecto_password) - Ecto custom type for storing encrypted password using Comeonin.
*   [couchdb\_connector (⭐97)](https://github.com/locolupo/couchdb_connector) - A connector for CouchDB, the Erlang-based, JSON document database.
*   [database\_url (⭐9)](https://github.com/s-m-i-t-a/database_url) - Parse database URL and return keyword list for use with Ecto.
*   [datomex (⭐47)](https://github.com/edubkendo/datomex) - Elixir driver for the Datomic REST API.
*   [ddb\_client (⭐11)](https://github.com/dalmatinerdb/ddb_client) - DalmatinerDB client.
*   [defql (⭐103)](https://github.com/fazibear/defql) - Create elixir functions with SQL as a body.
*   [dexts (⭐6)](https://github.com/meh/dexts) - Disk Elixir Terms Storage, dest wrapper.
*   [diver (⭐51)](https://github.com/novabyte/diver) - A HBase driver for Erlang/Elixir using Jinterface and the Asynchbase Java client to query the database.
*   [dproto (⭐1)](https://github.com/dalmatinerdb/dproto) - Protocols for DalmatinerDB.
*   [dqe (⭐10)](https://github.com/dalmatinerdb/dqe) - DalmatinerDB query engine.
*   [ecto (⭐6.3k)](https://github.com/elixir-ecto/ecto) - A database wrapper and language integrated query for Elixir.
*   [ecto\_anon (⭐92)](https://github.com/WTTJ/ecto_anon) - Simple way to handle data anonymization directly in your Ecto schemas.
*   [ecto\_cassandra (⭐86)](https://github.com/cafebazaar/ecto-cassandra) - Cassandra DB Adapter for Ecto.
*   [ecto\_enum (⭐567)](https://github.com/gjaldon/ecto_enum) - Ecto extension to support enums in models.
*   [ecto\_facade (⭐69)](https://github.com/azranel/ecto_facade) - Ecto facade that allows to separate writes and reads to different databases.
*   [ecto\_factory](https://hex.pm/packages/ecto_factory) - Easily generate structs based on your ecto schemas.
*   [ecto\_fixtures (⭐167)](https://github.com/DockYard/ecto_fixtures) - Fixtures for Elixir apps using Ecto.
*   [ecto\_lazy\_float (⭐7)](https://github.com/joshdholtz/ecto-lazy-float) - Ecto.LazyFloat - An Ecto.Float that accepts binary and integers.
*   [ecto\_list (⭐19)](https://github.com/popo63301/ecto_list) - Simple ordered model management with Ecto.
*   [ecto\_migrate (⭐35)](https://github.com/xerions/ecto_migrate) - Ecto auto migration library. It allows to generate and run migrations for initial and update migrations.
*   [ecto\_mnesia (⭐245)](https://github.com/Nebo15/ecto_mnesia) - Ecto adapter for Mnesia Erlang term database.
*   [ecto\_ordered (⭐40)](https://github.com/zovafit/ecto-ordered) - Ecto extension for ordered models.
*   [ecto\_paging (⭐14)](https://github.com/Nebo15/ecto_paging) - Cursor-based pagination for Ecto.
*   [ecto\_psql\_extras (⭐388)](https://github.com/pawurb/ecto_psql_extras) - Ecto PostgreSQL database performance insights.
*   [ecto\_rut (⭐114)](https://github.com/sheharyarn/ecto_rut) - Simple and Powerful Ecto Shortcuts to simplify and speed up development.
*   [ecto\_shortcuts (⭐29)](https://github.com/MishaConway/ecto_shortcuts) - Shortcuts for common operations in ecto.
*   [ecto\_shortuuid (⭐30)](https://github.com/gpedic/ecto_shortuuid) - Ecto type which adds support for [ShortUUIDs (⭐51)](https://github.com/gpedic/ex_shortuuid).
*   [ecto\_validation\_case (⭐11)](https://github.com/danielberkompas/ecto_validation_case) - Simplify your Ecto model validation tests. Loosely inspired by shoulda matchers, but simpler.
*   [ecto\_watch (⭐241)](https://github.com/cheerfulstoic/ecto_watch) - Allows you to easily get notifications about database changes directly from PostgreSQL.
*   [ectophile (⭐42)](https://github.com/gjaldon/ectophile) - Ecto extension to instantly support file uploads in models.
*   [elastic (⭐65)](https://github.com/radar/elastic) - A thin-veneer over HTTPotion to help you talk to Elastic Search.
*   [elastix (⭐253)](https://github.com/werbitzky/elastix) - A simple Elastic REST client written in Elixir.
*   [eredis (⭐44)](https://github.com/Nordix/eredis) - Erlang Redis client.
*   [erlastic\_search (⭐162)](https://github.com/tsloughter/erlastic_search) - An Erlang app for communicating with Elastic Search's rest interface.
*   [esqlite (⭐136)](https://github.com/mmzeeman/esqlite) - Erlang NIF for sqlite.
*   [eternal (⭐101)](https://github.com/whitfin/eternal) - Keep your ETS tables alive forever, safely and easily.
*   [ets\_map (⭐8)](https://github.com/antipax/ets_map) - An Elixir package that provides a Map-like interface (Map/Access/Enumerable/Collectable) backed by an ETS table.
*   [eventstore (⭐1.1k)](https://github.com/slashdotdash/eventstore) - A CQRS EventStore using Postgres for persistence, written in Elixir.
*   [ex\_bitcask (⭐12)](https://github.com/JonGretar/ExBitcask) - Elixir wrapper of Basho's Bitcask Key/Value store.
*   [ex\_sider (⭐6)](https://github.com/ephe-meral/ex_sider) - Elixir Map/List/Set interfaces for Redis data structures (uses Redix, but that is configurable).
*   [exleveldb (⭐44)](https://github.com/skovsgaard/exleveldb) - Elixir wrapper around Basho's eleveldb module for LevelDB.
*   [exnumerator (⭐65)](https://github.com/KamilLelonek/exnumerator) - Elixir enumerable type definition in a simple way to be used with any database.
*   [exredis (⭐357)](https://github.com/artemeff/exredis) - Redis client for Elixir.
*   [exseed (⭐17)](https://github.com/seaneshbaugh/exseed) - An Elixir library that provides a simple DSL for seeding databases through Ecto.
*   [exsolr (⭐22)](https://github.com/dcarneiro/exsolr) - A Solr wrapper written in Elixir.
*   [extreme (⭐132)](https://github.com/exponentially/extreme) - An Elixir library using [Eventstore](https://geteventstore.com) for persistence of events generated by aggregates (CQRS).
*   [exts (⭐7)](https://github.com/meh/exts) - Elixir Terms Storage, ets wrapper.
*   [github\_ecto (⭐121)](https://github.com/wojtekmach/github_ecto) - Ecto adapter for GitHub API.
*   [inquisitor (⭐170)](https://github.com/dockyard/inquisitor) - Composable query builder for Ecto.
*   [isn (⭐10)](https://github.com/Frost/isn) - Ecto types for the postgreSQL isn extension.
*   [kalecto (⭐148)](https://github.com/lau/calecto) - Glue between Kalends and Ecto for saving dates, times and datetimes.
*   [kvs (⭐175)](https://github.com/synrc/kvs) - Erlang Abstract Term Database.
*   [level (⭐5)](https://github.com/gausby/level) - Level for Elixir implements various helper functions and data types for working with Googles Level data store.
*   [libsqlex (⭐2)](https://github.com/danawanb/libsqlex) - Libsql driver for Elixir.
*   [mariaex (⭐262)](https://github.com/xerions/mariaex) - MariaDB/MySQL driver for Elixir.
*   [memento (⭐776)](https://github.com/sheharyarn/memento) - Simple Mnesia Interface in Elixir.
*   [moebius (⭐609)](https://github.com/robconery/moebius) - A functional query tool for Elixir and PostgreSQL.
*   [mongo (⭐101)](https://github.com/checkiz/elixir-mongo) - MongoDB driver for Elixir.
*   [mongodb (⭐572)](https://github.com/ericmj/mongodb) - MongoDB driver for Elixir.
*   [mongodb\_driver (⭐258)](https://github.com/zookzook/elixir-mongodb-driver) - Alternative driver for MongoDB with support for recent versions of MongoDB and comprehensive feature list.
*   [mongodb\_ecto (⭐377)](https://github.com/michalmuskala/mongodb_ecto) - MongoDB adapter for Ecto.
*   [mysql (⭐372)](https://github.com/mysql-otp/mysql-otp) - MySQL/OTP – MySQL driver for Erlang/OTP.
*   [mysqlex (⭐8)](https://github.com/tjheeta/mysqlex) - An Ecto-compatible wrapper around the mysql-otp library.
*   [neo4j\_sips (⭐81)](https://github.com/florinpatrascu/neo4j_sips) - Neo4j driver for Elixir.
*   [neo4j\_sips\_models (⭐6)](https://github.com/florinpatrascu/neo4j_sips_models) - Minimalistic Model support for the Neo4j.Sips Elixir driver.
*   [panoramix (⭐44)](https://github.com/gameanalytics/panoramix) - Apache Druid client for Elixir.
*   [paper\_trail (⭐585)](https://github.com/izelnakri/paper_trail) - Ecto plugin for tracking and recording all the changes in your database.
*   [pillar (⭐94)](https://github.com/sofakingworld/pillar) - Clickhouse HTTP based client.
*   [postgrex (⭐1.2k)](https://github.com/elixir-ecto/postgrex) - PostgreSQL driver for Elixir.
*   [ravix (⭐17)](https://github.com/YgorCastor/ravix) - RavenDB Driver for Elixir.
*   [ravix-ecto (⭐5)](https://github.com/YgorCastor/ravix-ecto) - RavenDB Ravix Driver adapter for Ecto.
*   [rediscl (⭐13)](https://github.com/akdilsiz/elixir-rediscl) - A minimal redis client with connection pooling and pipe query builder.
*   [redix (⭐1.1k)](https://github.com/whatyouhide/redix) - Superfast, pipelined, resilient Redis driver for Elixir.
*   [redo (⭐19)](https://github.com/heroku/redo) - Heroku's pipelining redis client for erlang.
*   [rethinkdb (⭐493)](https://github.com/hamiltop/rethinkdb-elixir) - Rethinkdb client in pure Elixir using JSON protocol.
*   [riak (⭐196)](https://github.com/drewkerrigan/riak-elixir-client) - A Riak client written in Elixir.
*   [riak\_ecto (⭐30)](https://github.com/pma/riak_ecto) - Riak adapter for Ecto.
*   [shards (⭐295)](https://github.com/cabol/shards) - Transparent and out-of-box Sharding support for Erlang/Elixir ETS tables.
*   [sql\_dust (⭐118)](https://github.com/bettyblocks/sql_dust) - Generate (complex) SQL queries using magical Elixir SQL dust.
*   [sqlite\_ecto (⭐76)](https://github.com/jazzyb/sqlite_ecto) - SQLite3 adapter for Ecto.
*   [ssdb\_elixir (⭐5)](https://github.com/lidashuang/ssdb-elixir) - ssdb client for Elixir, with focus on performance.
*   [tds (⭐118)](https://github.com/livehelpnow/tds) - MSSQL / TDS Database driver for Elixir.
*   [tds\_ecto (⭐57)](https://github.com/livehelpnow/tds_ecto) - MSSQL / TDS Adapter for Ecto.
*   [timex\_ecto (⭐164)](https://github.com/bitwalker/timex_ecto) - An adapter for using Timex DateTimes with Ecto.
*   [tirexs (⭐428)](https://github.com/Zatvobor/tirexs) - An Elixir flavored DSL for building JSON based requests to Elasticsearch engine.
*   [triplex (⭐490)](https://github.com/ateliware/triplex) - Database multitenancy with postgres schemas for Elixir applications.
*   [triton (⭐82)](https://github.com/blitzstudios/triton) - Pure Elixir Cassandra ORM built on top of Xandra.
*   [udpflux (⭐4)](https://github.com/timbuchwaldt/udpflux) - An opinionated InfluxDB UDP only client.
*   [walex (⭐323)](https://github.com/cpursley/walex) - PostgreSQL Change Data Capture (CDC) events listener in Elixir.
*   [xandra (⭐419)](https://github.com/lexhide/xandra) - Cassandra driver built natively in Elixir and focused on speed, simplicity, and robustness.
*   [yar (⭐8)](https://github.com/dantswain/yar) - Yet another Redis client for Elixir.

## OTP

*Libraries for working with OTP related things.*

*   [core (⭐43)](https://github.com/fishcakez/core) - Library for selective receive OTP processes.
*   [erlexec (⭐567)](https://github.com/saleyn/erlexec) - Execute and control OS processes from Erlang/OTP.
*   [immortal (⭐175)](https://github.com/danielberkompas/immortal) - Immortal is a small collection of helper modules intended to make it easier to build a fault-tolerant OTP application.
*   [libex\_config (⭐1)](https://github.com/reset/libex-config) - Helpers for accessing OTP application configuration.

## Package Management

*Libraries and tools for package and dependency management.*

*   [Hex](https://hex.pm/) - A package manager for the Erlang ecosystem.
*   [rebar3\_hex (⭐101)](https://github.com/hexpm/rebar3_hex) - Hex.pm plugin for rebar3.

## PDF

*Libraries and software for working with PDF files.*

*   [chromic\_pdf (⭐456)](https://github.com/bitcrowd/chromic_pdf) - A client for Chrome's DevTools API to generate PDFs (HTML to PDF).
*   [gutenex (⭐243)](https://github.com/SenecaSystems/gutenex) - Native PDF generation for Elixir.
*   [pdf2htmlex (⭐89)](https://github.com/ricn/pdf2htmlex) - Convert PDF docs to beautiful HTML files without losing text or format.
*   [pdf\_generator (⭐343)](https://github.com/gutschilla/elixir-pdf-generator) - A simple wrapper for wkhtmltopdf or puppeteer (HTML to PDF) for use in Elixir projects.
*   [puppeteer\_pdf (⭐100)](https://github.com/coletiv/puppeteer-pdf) - Another wrapper around puppeteer (HTML to PDF) for use in Elixir projects.

## Protocols

*Special protocol and format libraries.*

*   [borsh (⭐10)](https://github.com/alexfilatov/borsh) - Elixir implementation of the [BORSH](https://borsh.io) binary serializer.
*   [elixir\_radius (⭐15)](https://github.com/bearice/elixir-radius) - RADIUS Protocol on Elixir.
*   [ex\_hl7 (⭐42)](https://github.com/jcomellas/ex_hl7) - Health Level 7 (HL7) is a protocol designed to model and transfer health-related data electronically.
*   [ex\_marshal (⭐39)](https://github.com/gaynetdinov/ex_marshal) - Ruby Marshal format implemented in Elixir.
*   [exprotobuf (⭐484)](https://github.com/bitwalker/exprotobuf) - Protocol Buffers in Elixir, made easy.
*   [grpc-elixir (⭐1.5k)](https://github.com/tony612/grpc-elixir) - The Elixir implementation of gRPC.
*   [message\_pack (⭐71)](https://github.com/mururu/msgpack-elixir) - MessagePack Implementation for Elixir.
*   [msgpax (⭐291)](https://github.com/lexmag/msgpax) - MessagePack (de)serializer implementation for Elixir.
*   [protox (⭐292)](https://github.com/ahamez/protox) - Elixir implementation for Protocol Buffers.
*   [riffed (⭐306)](https://github.com/pinterest/riffed) - Provides idiomatic Elixir bindings for Apache Thrift.
*   [Sippet (⭐81)](https://github.com/balena/elixir-sippet) - An Elixir library designed to be used as SIP protocol middleware.
*   [SMPPEX (⭐5)](https://github.com/savonarola/smppex) - SMPP 3.4 protocol and framework implementation in Elixir.

## Queue

*Libraries for working with event and task queues.*

*   [adap (⭐16)](https://github.com/awetzel/adap) - Create a data stream across your information systems to query, augment and transform data according to Elixir matching rules.
*   [amqp (⭐689)](https://github.com/pma/amqp) - Simple Elixir wrapper for the Erlang RabbitMQ client, based on Langohr.
*   [broadway (⭐2.5k)](https://github.com/dashbitco/broadway) - Concurrent and multi-stage data ingestion and data processing with Elixir.
*   [conduit (⭐130)](https://github.com/conduitframework/conduit) - A framework for working with message queues, with adapters for SQS and AMQP, and plugs for reusable messaging patterns.
*   [cspex (⭐26)](https://github.com/costaraphael/cspex) - Simple, OTP compliant, Elixir implementation of CSP channels.
*   [dbus (⭐5)](https://github.com/aforward/sadbus) - A dumb message bus for sharing data between microservices decoupled using Redis.
*   [ecto\_job (⭐278)](https://github.com/mbuhot/ecto_job) - A transactional job queue built with Ecto, PostgreSQL and GenStage.
*   [elixir\_nsq (⭐91)](https://github.com/wistia/elixir_nsq) - NSQ client library for Elixir.
*   [elixir\_talk (⭐19)](https://github.com/jsvisa/elixir_talk) - An Elixir client for beanstalkd.
*   [enm (⭐120)](https://github.com/basho/enm) - enm is an Erlang port driver that wraps the nanomsg C library.
*   [exdisque (⭐17)](https://github.com/mosic/exdisque) - Elixir client for [Disque (⭐8k)](https://github.com/antirez/disque), an in-memory, distributed job queue.
*   [exq (⭐1.5k)](https://github.com/akira/exq) - Job processing library for Elixir - compatible with Resque/Sidekiq.
*   [exrabbit (⭐48)](https://github.com/d0rc/exrabbit) - RabbitMQ bindings and DSL for Elixir.
*   [faktory\_worker (⭐39)](https://github.com/opt-elixir/faktory_worker) - An Elixir library for working with [Faktory](https://contribsys.com/faktory/), a polyglot job processing system made by the author of Sidekiq.
*   [flume (⭐79)](https://github.com/scripbox/flume) - A blazing fast job processing system backed by GenStage & Redis.
*   [gen\_rmq (⭐180)](https://github.com/meltwater/gen_rmq) - Set of behaviours meant to be used to create RabbitMQ consumers and publishers.
*   [heapq (⭐8)](https://github.com/takscape/elixir-heapq) - A Heap-based Priority Queue Implementation in Elixir.
*   [honeycomb (⭐18)](https://github.com/Hentioe/honeycomb) - Another scheduling system, focusing on the collection of results for one-time tasks.
*   [honeydew (⭐724)](https://github.com/koudelka/honeydew) - Honeydew is a worker pool library for Elixir.
*   [kaffe (⭐161)](https://github.com/spreedly/kaffe) - Kafka client library for Elixir.
*   [mqs (⭐27)](https://github.com/synrc/mqs) - RabbitMQ client library, routing keys, RPC over MQ and other stuff.
*   [oban (⭐3.6k)](https://github.com/sorentwo/oban) - Robust asynchronous job processor powered by Elixir and modern PostgreSQL.
*   [opq (⭐269)](https://github.com/fredwu/opq) - A simple, in-memory queue with worker pooling and rate limiting in Elixir.
*   [pqueue (⭐170)](https://github.com/okeuday/pqueue) - Erlang Priority Queue Implementation.
*   [que (⭐675)](https://github.com/sheharyarn/que) - Simple Background Job Processing with Mnesia.
*   [queuex (⭐11)](https://github.com/falood/queuex) - Priority Queue with multiple backends.
*   [RBMQ (⭐21)](https://github.com/Nebo15/rbmq) - Simple API for spawning RabbitMQ Producers and Consumers.
*   [Rihanna (⭐449)](https://github.com/samphilipd/rihanna) - High performance postgres-backed job queue for Elixir.
*   [stream\_weaver](https://hex.pm/packages/stream_weaver) - Library for working with streams.
*   [task\_bunny (⭐201)](https://github.com/shinyscorpion/task_bunny) - background processing application written in Elixir and uses RabbitMQ as a messaging backend.
*   [verk (⭐726)](https://github.com/edgurgel/verk) - Verk is a job processing system backed by Redis. It uses the same job definition of Sidekiq/Resque.
*   [work\_queue (⭐40)](https://github.com/pragdave/work_queue) - Simple implementation of the hungry-consumer model in Elixir.

## QUIC

*Libraries and tools for QUIC transport layer network protocol.*

*   [quicer (⭐243)](https://github.com/emqx/quic) - QUIC protocol erlang library.

## Release Management

*Libraries and tools for release management.*

*   [changex (⭐49)](https://github.com/Gazler/changex) - Automated changelog generation from GIT logs.
*   [distillery (⭐3k)](https://github.com/bitwalker/distillery) - A pure Elixir implementation of release packaging functionality for the Erlang VM.
*   [eliver (⭐56)](https://github.com/glasnoster/eliver) - Interactive semantic versioning for Elixir packages.
*   [expublish (⭐25)](https://github.com/tfiedlerdejanze/expublish) - Automates semantic release versioning and best practices for elixir packages.
*   [relex (⭐59)](https://github.com/yrashk/relex) - Erlang/Elixir Release Assembler.
*   [renew (⭐33)](https://github.com/Nebo15/renew) - Mix task to create mix projects that builds into Docker containers.
*   [versioce (⭐30)](https://github.com/mpanarin/versioce) - An extensible version bumping and changelog generation for your mix project.

## REST and API

*Libraries and web tools for developing REST-ful APIs.*

*   [accent (⭐44)](https://github.com/sticksnleaves/accent) - Plug for handling the conversion of JSON API keys to different cases.
*   [detergent (⭐64)](https://github.com/devinus/detergent) - An emulsifying Erlang SOAP library.
*   [detergentex (⭐65)](https://github.com/r-icarus/detergentex) - Elixir binding to Detergent erlang library used to call WSDL/SOAP Services.
*   [maru (⭐1.3k)](https://github.com/falood/maru) - Elixir copy of grape for creating REST-like APIs.
*   [mazurka (⭐15)](https://github.com/exstruct/mazurka) - Hypermedia API toolkit.
*   [plug\_rest (⭐55)](https://github.com/christopheradams/plug_rest) - REST behaviour and Plug router for hypermedia web applications.
*   [signaturex (⭐27)](https://github.com/edgurgel/signaturex) - Simple key/secret based authentication for APIs.
*   [SOAP client (⭐140)](https://github.com/elixir-soap/soap) - Hex-documented SOAP client based on HTTPoison.
*   [urna (⭐94)](https://github.com/meh/urna) - Urna is a simple DSL around cauldron to implement REST services.
*   [versionary (⭐40)](https://github.com/sticksnleaves/versionary) - API versioning for Elixir Plug and Phoenix.

## Search

*Libraries related to search indexing, search algorithms and search clients.*

*   [algoliax (⭐62)](https://github.com/WTTJ/algoliax) - An Algolia library for Elixir, usable with Ecto schemas.
*   [elasticlunr (⭐191)](https://github.com/heywhy/ex_elasticlunr) - A small, full-text search library for use in the Elixir environment.
*   [elasticsearch (⭐423)](https://github.com/infinitered/elasticsearch-elixir) - A simple, no-nonsense Elasticsearch library for Elixir.
*   [elasticsearch\_elixir\_bulk\_processor (⭐14)](https://github.com/sashman/elasticsearch_elixir_bulk_processor) - An efficient and flexible way to insert into Elasticsearch.
*   [giza\_sphinxsearch (⭐19)](https://github.com/Tyler-pierce/giza_sphinxsearch) - Client for Sphinx Search compatible with Manticore.

## Security

*Libraries and tools regarding security.*

*   [ca (⭐18)](https://github.com/synrc/ca) - Certificate Authority.
*   [clamxir (⭐13)](https://github.com/ramortegui/clamxir) - ClamAV wrapper for elixir.
*   [code\_signing (⭐6)](https://github.com/benknowles/code_signing) - Signing and verifying BEAM files with Ed25519 signatures.
*   [Ockam (⭐4.5k)](https://github.com/ockam-network/ockam) - A suite of tools, programming libraries and infrastructure that make it easy to build devices that communicate securely, privately and trustfully with cloud services and other devices. [Docs](https://www.ockam.io/learn/concepts/) .
*   [pwned (⭐24)](https://github.com/thiamsantos/pwned) - Check if your password has been pwned.
*   [safetybox (⭐21)](https://github.com/aforward/safetybox) - Security oriented helper functions for Elixir.
*   [site\_encrypt (⭐485)](https://github.com/sasa1977/site_encrypt) - Integrated certification via Let's encrypt for Elixir-powered sites.
*   [sobelow (⭐1.7k)](https://github.com/nccgroup/sobelow) - Security-focused static analysis for the Phoenix Framework.
*   [ssl\_verify\_fun (⭐107)](https://github.com/deadtrickster/ssl_verify_fun.erl) - Collection of ssl verification functions for Erlang.

## SMS

*SMS related libraries and tools.*

*   [exsms](https://hex.pm/packages/exsms) - An Elixir library for sending transactional SMS - supports Sendinblue, mailjet, msg91 and textlocal.

## Static Page Generation

*Tools and libraries for generating static websites and content.*

*   [blogit (⭐41)](https://github.com/meddle0x53/blogit) - An OTP application for generating blogs from git repositories containing markdown files.
*   [coil (⭐68)](https://github.com/badosu/coil) - Minimalistic static content engine.
*   [glayu (⭐80)](https://github.com/pablomartinezalvarez/glayu) - A static site generator for mid-sized sites.
*   [NimblePublisher (⭐517)](https://github.com/dashbitco/nimble_publisher) - Minimal filesystem-based publisher with markdown and syntax highlighting.
*   [pardall\_markdown (⭐118)](https://github.com/alfredbaudisch/pardall_markdown) - Reactive publishing framework, filesystem-based with support for Markdown, nested hierarchies, and instant content rebuilding.
*   [phoenix\_pages (⭐78)](https://github.com/jsonmaur/phoenix-pages) - Add blogs, documentation, and other static pages to Phoenix apps.
*   [serum (⭐324)](https://github.com/Dalgona/Serum) - A simple static website generator written in Elixir.

## Statistics

*Libraries around the topic statistics.*

*   [descriptive\_statistics (⭐9)](https://github.com/pusewicz/descriptive_statistics) - Descriptive Statistics for Elixir.
*   [mtx (⭐19)](https://github.com/synrc/mtx) - MTX supports front-end API for tracking Histogram, Meter, Counter, Gauge, Timing keys.
*   [numerix (⭐189)](https://github.com/safwank/Numerix) - A collection of useful mathematical functions with a slant towards statistics, linear algebra and machine learning.
*   [simple\_stat\_ex (⭐12)](https://github.com/Tyler-pierce/simplestatex) - Ecto compatible library for simple stat keeping by time period.
*   [statistics (⭐140)](https://github.com/msharp/elixir-statistics) - Some basic statistical functions for Elixir.

## Templating

*Libraries parsing and helping with templates*

*   [bbmustache (⭐184)](https://github.com/soranoba/bbmustache) - Binary pattern match Based Mustache template engine for Erlang/OTP.
*   [calliope (⭐195)](https://github.com/nurugger07/calliope) - An Elixir HAML parser.
*   [eml (⭐114)](https://github.com/zambal/eml) - Library for writing and manipulating (HTML) markup in Elixir.
*   [exgen (⭐35)](https://github.com/rwdaigle/exgen) - A templating library for quickly generating Elixir projects.
*   [expug (⭐83)](https://github.com/rstacruz/expug) - Pug templates for Elixir.
*   [mustache (⭐65)](https://github.com/schultyy/Mustache.ex) - Mustache templates for Elixir.
*   [mustachex (⭐18)](https://github.com/jui/mustachex) - Mustache for Elixir - Logic-less templates.
*   [slime (⭐375)](https://github.com/slime-lang/slime) - An Elixir library for rendering slim-like templates.
*   [sneeze (⭐61)](https://github.com/JuneKelly/sneeze) - Render elixir data structures to HTML. Inspired by [hiccup (⭐2.7k)](https://github.com/weavejester/hiccup).
*   [taggart (⭐35)](https://github.com/ijcd/taggart) - HTML as code in Elixir.
*   [templates (⭐6)](https://github.com/sugar-framework/templates) - Helper library for adding templating to web applications.
*   [temple (⭐498)](https://github.com/mhanberg/temple) - An HTML DSL for Elixir and Phoenix.

## Testing

*Libraries for testing codebases and generating test data.*

*   [amrita (⭐199)](https://github.com/josephwilk/amrita) - A polite, well mannered and thoroughly upstanding testing framework for Elixir.
*   [apocryphal (⭐17)](https://github.com/coryodaniel/apocryphal) - Swagger based document driven development for ExUnit.
*   [blacksmith (⭐197)](https://github.com/batate/blacksmith) - Data generation framework for Elixir.
*   [blitzy (⭐84)](https://github.com/benjamintanweihao/blitzy) - A simple HTTP load tester in Elixir.
*   [bypass (⭐987)](https://github.com/pspdfkit-labs/bypass) - Bypass provides a quick way to create a mock HTTP server with a custom plug.
*   [chaperon (⭐135)](https://github.com/polleverywhere/chaperon) - An HTTP service performance & load testing framework written in Elixir.
*   [chemistry (⭐7)](https://github.com/genericlady/chemistry) - Testing Framework for Elixir.
*   [cobertura\_cover (⭐12)](https://github.com/PSPDFKit-labs/cobertura_cover) - Writes a coverage.xml from `mix test --cover` file compatible with Jenkins' Cobertura plugin.
*   [definject (⭐56)](https://github.com/definject/definject) - Unobtrusive dependency injector for Elixir.
*   [double (⭐49)](https://github.com/sonerdy/double) - Create stub dependencies for testing without overwriting global modules.
*   [ecto\_it (⭐3)](https://github.com/xerions/ecto_it) - Ecto plugin with default configuration for repos for testing different ecto plugins with databases.
*   [efrisby (⭐18)](https://github.com/FabioBatSilva/efrisby) - A REST API testing framework for erlang.
*   [efx (⭐89)](https://github.com/bravobike/efx) - A library to declaratively write asynchronously testable effects.
*   [elixir-auto-test (⭐0)](https://github.com/joaothallis/elixir-auto-test) - Run test when file is saved using inotify-tools.
*   [espec (⭐811)](https://github.com/antonmi/espec) - BDD test framework for Elixir inspired by RSpec.
*   [espec\_phoenix (⭐138)](https://github.com/antonmi/espec_phoenix) - ESpec for Phoenix web framework.
*   [ex\_integration\_coveralls (⭐4)](https://github.com/yeshan333/ex_integration_coveralls) - A library for Elixir run-time system code line-level coverage analysis. You can use it to evaluate the integration tests code coverage. [Introduction article (⭐4)](https://github.com/yeshan333/explore_ast_app/blob/main/examples/README.md).
*   [ex\_machina (⭐2k)](https://github.com/thoughtbot/ex_machina) - Flexible test factories for Elixir. Works out of the box with Ecto and Ecto associations.
*   [ex\_spec (⭐99)](https://github.com/drewolson/ex_spec) - BDD-like syntax for ExUnit.
*   [ex\_unit\_fixtures (⭐14)](https://github.com/obmarg/ex_unit_fixtures) - A library for defining modular dependencies for ExUnit tests.
*   [ex\_unit\_notifier (⭐132)](https://github.com/navinpeiris/ex_unit_notifier) - Desktop notifications for ExUnit.
*   [excheck (⭐315)](https://github.com/parroty/excheck) - Property-based testing library for Elixir (QuickCheck style).
*   [exkorpion (⭐31)](https://github.com/wesovilabs/exkorpion) - A BDD library for Elixir developers.
*   [factory\_girl\_elixir (⭐43)](https://github.com/sinetris/factory_girl_elixir) - Minimal implementation of Ruby's factory\_girl in Elixir.
*   [fake\_server (⭐72)](https://github.com/bernardolins/fake_server) - FakeServer is an HTTP server that simulates response and makes testing external APIs easier.
*   [faker (⭐1.1k)](https://github.com/igas/faker) - Faker is a pure Elixir library for generating fake data.
*   [faker\_elixir (⭐148)](https://github.com/GesJeremie/faker-elixir) - FakerElixir is an Elixir package that generates fake data for you.
*   [fqc (⭐1)](https://github.com/project-fifo/fqc) - FiFo Quickcheck helper, a set of helpers for running EQC.
*   [gimei (⭐2)](https://github.com/KazuCocoa/elixir-gimei) - Gimei is a pure Elixir library for generating Japanese fake data.
*   [hound (⭐1.4k)](https://github.com/HashNuke/hound) - Elixir library for writing integration tests and browser automation.
*   [hypermock (⭐24)](https://github.com/stevegraham/hypermock) - HTTP request stubbing and expectation Elixir library.
*   [ignorant (⭐14)](https://github.com/campezzi/ignorant) - Partial `Map` comparison that ensures fields are present while ignoring their values.
*   [katt (⭐120)](https://github.com/for-GET/katt) - KATT (Klarna API Testing Tool) is an HTTP-based API testing tool for Erlang.
*   [kovacs (⭐4)](https://github.com/antp/kovacs) - A simple ExUnit test runner.
*   [markdown\_test (⭐3)](https://github.com/MainShayne233/markdown_test) - A library that lets you test the Elixir code in your markdown files.
*   [meck (⭐820)](https://github.com/eproxus/meck) - A mocking library for Erlang.
*   [mecks\_unit (⭐55)](https://github.com/archan937/mecks_unit) - A package to elegantly mock module functions within (asynchronous) ExUnit tests using [meck (⭐820)](https://github.com/eproxus/meck).
*   [mix\_erlang\_tasks (⭐21)](https://github.com/alco/mix-erlang-tasks) - Common tasks for Erlang projects that use Mix.
*   [mix\_eunit (⭐17)](https://github.com/dantswain/mix_eunit) - A Mix task to execute eunit tests.
*   [mix\_test\_interactive (⭐114)](https://github.com/influxdata/mix_test_interactive) - Interactive test runner for mix test with watch mode.
*   [mix\_test\_watch (⭐948)](https://github.com/lpil/mix-test.watch) - Automatically run your Elixir project's tests each time you save a file.
*   [mixunit (⭐2)](https://github.com/talentdeficit/mixunit) - An EUnit task for Mix based projects.
*   [mneme (⭐133)](https://github.com/zachallaun/mneme) - Assertions that know how to update themselves, otherwise known as snapshot or approval testing.
*   [mock (⭐684)](https://github.com/jjh42/mock) - Mocking library for the Elixir language.
*   [mockery (⭐94)](https://github.com/appunite/mockery) - Simple mocking library for asynchronous testing.
*   [mockingbird (⭐3)](https://github.com/Driftrock/mockingbird) - A set of helpers to test code that involves http requests.
*   [mox (⭐1.4k)](https://github.com/dashbitco/mox) - Mocks and explicit contracts for Elixir.
*   [patch (⭐204)](https://github.com/ihumanable/patch) - Ergonomic Mocking for Elixir.
*   [pavlov (⭐128)](https://github.com/sproutapp/pavlov) - BDD framework for your Elixir projects.
*   [plug\_test\_helpers (⭐10)](https://github.com/xavier/plug_test_helpers) - A simple testing DSL for Plugs.
*   [ponos (⭐157)](https://github.com/klarna/ponos) - Ponos is an Erlang application that exposes a flexible load generator API.
*   [power\_assert (⭐214)](https://github.com/ma2gedev/power_assert_ex) - Power Assert in Elixir. Shows evaluation results each expression.
*   [propcheck (⭐384)](https://github.com/alfert/propcheck) - Property based testing for Elixir.
*   [proper (⭐894)](https://github.com/manopapad/proper) - PropEr (PROPerty-based testing tool for ERlang) is a QuickCheck-inspired open-source property-based testing tool for Erlang.
*   [setup\_tag (⭐2)](https://github.com/vic/setup_tag) - Easily mix and match functions marked with tags to setup your test context.
*   [shouldi (⭐135)](https://github.com/batate/shouldi) - Elixir testing libraries with nested contexts, superior readability, and ease of use.
*   [stream\_data (⭐903)](https://github.com/whatyouhide/stream_data) - A pure-Elixir data generation and property-based testing library.
*   [test\_selector (⭐14)](https://github.com/DefactoSoftware/test_selector) - A set of test helpers that make sure you always select the right elements in your Phoenix app.
*   [test\_that\_json (⭐10)](https://github.com/facto/test_that_json) - JSON assertions and helpers for your Elixir testing needs.
*   [toxiproxy\_ex (⭐56)](https://github.com/Jcambass/toxiproxy_ex) - API client for the resilience testing tool Toxiproxy.
*   [tuco\_tuco (⭐58)](https://github.com/stuart/tuco_tuco) - TucoTuco helps you test your web application by running a web browser and simulating user interaction with your application.
*   [Walkman (⭐54)](https://github.com/derekkraan/walkman) - Isolate tests from the real world, inspired by Ruby's VCR.
*   [wallaby (⭐1.7k)](https://github.com/keathley/wallaby) - Wallaby helps test your web applications by simulating user interactions concurrently and manages browsers.
*   [white\_bread (⭐228)](https://github.com/meadsteve/white-bread) - Story based BDD in Elixir using the gherkin syntax.

## Text and Numbers

*Libraries for parsing and manipulating text and numbers.*

*   [abacus (⭐96)](https://github.com/narrowtux/abacus) - Evaluate math terms in Elixir.
*   [base58 (⭐15)](https://github.com/jrdnull/base58) - Base58 encoding/decoding for Elixir.
*   [base58check (⭐17)](https://github.com/gjaldon/base58check) - Base58Check encoding/decoding for Bitcoin.
*   [base62 (⭐20)](https://github.com/igas/base62) - Base62 encoder/decoder in pure Elixir.
*   [bencode (⭐18)](https://github.com/gausby/bencode) - A Bencode encoder and decoder for Elixir. The decoder will return the checksum value of the info dictionary, if an info dictionary was found in the input.
*   [bencoder (⭐4)](https://github.com/alehander42/bencoder) - bencode in Elixir.
*   [bitcoinex (⭐74)](https://github.com/RiverFinancial/bitcoinex) - Bitcoin utilities in Elixir.
*   [brcpfcnpj (⭐76)](https://github.com/williamgueiros/Brcpfcnpj) - Number format and Validation for Brazilian documents (CPF/CNPJ).
*   [caustic (⭐6)](https://github.com/agro1986/caustic) - Elixir cryptocurrency library for Bitcoin, Ethereum, and other blockchains. Includes cryptography, number theory (prime, congruence), and general mathematics library for exploratory math.
*   [ccc (⭐4)](https://github.com/Joe-noh/ccc) - Character Code Converter.
*   [chinese\_translation (⭐91)](https://github.com/tyrchen/chinese_translation) - Translate between traditional chinese and simplified chinese based on wikipedia data, and translate chinese words/characters to pinyin (or slug with or without tone).
*   [cidr (⭐46)](https://github.com/c-rack/cidr-elixir) - Classless Inter-Domain Routing (CIDR) for Elixir.
*   [cirru\_parser (⭐0)](https://github.com/Cirru/parser.ex) - Cirru Parser in Elixir.
*   [colorful (⭐2)](https://github.com/Joe-noh/colorful) - Elixir macros to decorate characters on CUI.
*   [colors (⭐7)](https://github.com/lidashuang/colors) - Colors util written in Elixir.
*   [convertat (⭐17)](https://github.com/whatyouhide/convertat) - An Elixir library for converting from and to arbitrary bases.
*   [curtail (⭐32)](https://github.com/seankay/curtail) - HTML tag-safe string truncation.
*   [custom\_base (⭐22)](https://github.com/igas/custom_base) - Allow you to make custom base conversion in Elixir.
*   [decimal (⭐470)](https://github.com/ericmj/decimal) - Arbitrary precision decimal arithmetic for Elixir.
*   [eden (⭐38)](https://github.com/jfacorro/Eden) - [EDN (⭐2.7k)](https://github.com/edn-format/edn) encoder/decoder for Elixir.
*   [elixilorem (⭐10)](https://github.com/mgamini/elixilorem) - Lorem Ipsum generator for Elixir.
*   [elixir-range-extras (⭐8)](https://github.com/lnikkila/elixir-range-extras) - Elixir range utilities: constant-time random sampling and set operations.
*   [elixir\_bencode (⭐8)](https://github.com/AntonFagerberg/elixir_bencode) - Bencode implemented in Elixir.
*   [erldn (⭐28)](https://github.com/marianoguerra/erldn) - [EDN (⭐2.7k)](https://github.com/edn-format/edn) format parser for the Erlang platform.
*   [event\_source\_encoder (⭐4)](https://github.com/chatgris/event_source_encoder) - Encode data into EventSource compliant data.
*   [ex\_brace\_expansion (⭐5)](https://github.com/gniquil/ex_brace_expansion) - Brace expansion, as known from sh/bash, in Elixir.
*   [ex\_cldr (⭐1)](https://github.com/kipcole9/cldr) - Cldr is an Elixir library for the Unicode Consortium's Common Locale Data Repository (CLDR).
*   [ex\_pression (⭐11)](https://github.com/balance-platform/ex_pression) - Evaluate user input expressions.
*   [ex\_rfc3966 (⭐1)](https://github.com/marcelog/ex_rfc3966) - Elixir Tel URI parser compatible with RFC3966.
*   [ex\_rfc3986 (⭐10)](https://github.com/marcelog/ex_rfc3986) - RFC3986 URI/URL parser.
*   [ex\_uc (⭐21)](https://github.com/carturoch/ex_uc) - Extensible Units Converter for Elixir.
*   [exmoji (⭐106)](https://github.com/mroth/exmoji) - Emoji encoding Swiss Army knife for Elixir/Erlang.
*   [expletive (⭐44)](https://github.com/xavier/expletive) - Profanity filter library for Elixir.
*   [expr (⭐12)](https://github.com/Rob-bie/Expr) - An Elixir library for parsing and evaluating mathematical expressions.
*   [haikunator (⭐28)](https://github.com/knrz/Haikunator) - Generate Heroku-like memorable random names to use in your apps or anywhere else.
*   [hashids (⭐282)](https://github.com/alco/hashids-elixir) - Hashids lets you obfuscate numerical identifiers via reversible mapping.
*   [hexate (⭐30)](https://github.com/rjsamson/hexate) - Simple module for Hex encoding / decoding in Elixir.
*   [inet\_cidr (⭐50)](https://github.com/cobenian/inet_cidr) - Classless Inter-Domain Routing (CIDR) for Elixir that is compatible with :inet and supports both IPv4 and IPv6.
*   [inflex (⭐383)](https://github.com/nurugger07/inflex) - An Inflector library for Elixir.
*   [kitsune (⭐11)](https://github.com/edubkendo/kitsune) - An Elixir library for transforming the representation of data.
*   [ltsvex (⭐10)](https://github.com/ma2gedev/ltsvex) - LTSV parser implementation in Elixir.
*   [mbcs (⭐27)](https://github.com/woxtu/elixir-mbcs) - Wrapper for erlang-mbcs. This module provides functions for character encoding conversion.
*   [mimetype\_parser (⭐3)](https://github.com/camshaft/mimetype_parser) - parse mimetypes.
*   [minigen (⭐19)](https://github.com/mrdimosthenis/minigen) - Random data generators for the Erlang ecosystem.
*   [monetized (⭐46)](https://github.com/theocodes/monetized) - A lightweight solution for handling and storing money.
*   [money (⭐836)](https://github.com/liuggio/money) - Working with Money safer, easier, and fun, interpretation of the Fowler's Money pattern.
*   [mt940 (⭐9)](https://github.com/my-flow/mt940) - MT940 (standard structured SWIFT Customer Statement message) parser for Elixir.
*   [namor (⭐13)](https://github.com/jsonmaur/namor) - A name generator that creates random, url-friendly slugs.
*   [nanoid (⭐228)](https://github.com/railsmechanic/nanoid) - Elixir port of NanoID, a secure and URL-friendly unique ID generator.
*   [near\_api (⭐11)](https://github.com/alexfilatov/near_api) - A [NEAR](https://near.org) API in Elixir - a library for DApps development on the NEAR blockchain platform.
*   [neotomex (⭐69)](https://github.com/jtmoulia/neotomex) - A [PEG](http://bford.info/packrat/) implementation with a pleasant Elixir DSL.
*   [number (⭐229)](https://github.com/danielberkompas/number) - Number is a pretentiously-named Elixir library which provides functions to convert numbers into a variety of different formats.
*   [numero (⭐8)](https://github.com/alisinabh/numero) - A micro library for converting non-english utf-8 digits in elixir.
*   [palette (⭐2)](https://github.com/lpil/palette) - A handy library for colouring strings in Elixir.
*   [pinyin (⭐25)](https://github.com/lidashuang/pinyin) - Chinese Pinyin lib for Elixir.
*   [porterstemmer (⭐6)](https://github.com/frpaulas/porterstemmer) - Porter Stemmer in Elixir.
*   [pretty\_hex (⭐7)](https://github.com/polsab/pretty_hex) - A binary hex dumping library in Elixir.
*   [quickrand (⭐41)](https://github.com/okeuday/quickrand) - Quick Random Number Generation.
*   [RandomStringGenerator (⭐1)](https://github.com/caioceccon/random_string_generator) - A module to generate a random string based on a given string pattern.
*   [ref\_inspector (⭐14)](https://github.com/elixytics/ref_inspector) - Referer parser library in Elixir. Fetching info from URLs.
*   [remove\_emoji (⭐9)](https://github.com/guanting112/elixir_remove_emoji) - Emoji text sanitizer in Elixir. It can remove any emoji symbol.
*   [secure\_random (⭐97)](https://github.com/patricksrobertson/secure_random.ex) - Convenience library for random base64 strings modeled after my love for Ruby's SecureRandom.
*   [sentient (⭐35)](https://github.com/dantame/sentient) - Simple sentiment analysis based on the AFINN-111 wordlist.
*   [shortuuid (⭐51)](https://github.com/gpedic/ex_shortuuid) - Generate concise, unambiguous, URL-safe UUIDs.
*   [simetric (⭐62)](https://github.com/lexmag/simetric) - String similarity metrics for Elixir.
*   [slugger (⭐160)](https://github.com/h4cc/slugger) - Slugger can generate slugs from given strings that can be used in URLs or file names.
*   [smile (⭐6)](https://github.com/danigulyas/smile) - Small lib for converting emoji mappers to emoji characters, like in Slack messages.
*   [stemmer (⭐153)](https://github.com/fredwu/stemmer) - An English (Porter2) stemming implementation in Elixir.
*   [tau (⭐3)](https://github.com/FranklinChen/tau) - Provide the famous mathematical constant, tau, τ = 6.2831....
*   [tomlex (⭐32)](https://github.com/zamith/tomlex) - A TOML parser for Elixir.
*   [transformer (⭐0)](https://github.com/ByeongUkChoi/transformer) - Flexible type conversion lightweight library.
*   [ua\_inspector (⭐134)](https://github.com/elixytics/ua_inspector) - User agent parser library like `piwik/device-detector`.
*   [ua\_parser2 (⭐1)](https://github.com/nazipov/ua_parser2-elixir) - A port of ua-parser2 to Elixir. User agent parser library.
*   [unique\_names\_generator (⭐2)](https://github.com/jongirard/unique_names_generator) - Generate seeded random and unique names.
*   [unit\_fun (⭐21)](https://github.com/meadsteve/unit_fun) - Attempt to add units to numbers in elixir to give some added type safety when dealing with numeric quantities.
*   [uuid (⭐364)](https://github.com/zyro/elixir-uuid) - UUID generator and utilities for Elixir.
*   [uuid\_erl (⭐220)](https://github.com/okeuday/uuid) - Erlang Native UUID Generation.
*   [veritaserum (⭐83)](https://github.com/uesteibar/veritaserum) - Sentiment analysis based on afinn-165, emojis and some enhancements.

## Third Party APIs

*Libraries for accessing third party APIs.*

*   [airbrake (⭐27)](https://github.com/romul/airbrake-elixir) - An Elixir notifier for the Airbrake.
*   [airbrakex (⭐27)](https://github.com/fazibear/airbrakex) - Elixir client for the Airbrake service.
*   [amazon\_product\_advertising\_client (⭐38)](https://github.com/zachgarwood/elixir-amazon-product-advertising-client) - Amazon Product Advertising API client for Elixir.
*   [apns (⭐70)](https://github.com/chvanikoff/apns4ex) - Apple Push Notifications Service client library for elixir.
*   [asanaficator (⭐2)](https://github.com/trenpixster/asanaficator) - Simple Elixir wrapper for the Asana API. Based on Tentacat.
*   [askimet\_ex (⭐7)](https://github.com/mijailr/askimet_ex) - Elixir client for Askimet Anti-Spam service.
*   [assembla\_api (⭐0)](https://github.com/Assembla/ex_assembla_api) - Assembla API client for Elixir.
*   [balalaika\_bear (⭐12)](https://github.com/ayrat555/balalaika_bear) - Simple VK API client for Elixir.
*   [balanced (⭐4)](https://github.com/bryanjos/balanced-elixir) - Balanced API Client for Elixir.
*   [bandwidth (⭐5)](https://github.com/bandwidthcom/elixir-bandwidth) - An Elixir client library for the Bandwidth Application Platform.
*   [bing\_translator (⭐9)](https://github.com/ikeikeikeike/bing_translator) - A simple Elixir interface to Bing's translation API.
*   [bitmex (⭐9)](https://github.com/nobrick/bitmex) - BitMEX client library for Elixir.
*   [bitpay (⭐31)](https://github.com/bitpay/elixir-client) - Elixir core library for connecting to bitpay.com.
*   [cashier (⭐50)](https://github.com/swelham/cashier) - Payment gateway offering a common interface into multiple payment providers.
*   [chargebeex (⭐19)](https://github.com/WTTJ/chargebeex) - An Elixir client for Chargebee API.
*   [cleverbot (⭐3)](https://github.com/BlakeWilliams/Elixir-Cleverbot) - Simple implementation of the Cleverbot API in Elixir.
*   [coinbase (⭐13)](https://github.com/gregpardo/coinbase-elixir) - A unofficial Coinbase API v1 Client.
*   [commerce\_billing (⭐182)](https://github.com/joshnuss/commerce_billing) - A payment-processing library for Elixir that supports multiple gateways (e.g. Bogus & Stripe).
*   [conekta (⭐16)](https://github.com/echavezNS/conekta-elixir) - Elixir wrapper for Conekta API.
*   [correios\_cep (⭐38)](https://github.com/prodis/correios-cep-elixir) - Find Brazilian addresses by zip code, directly from Correios database. No HTML parsers.
*   [currently (⭐5)](https://github.com/chatgris/currently) - A tool to display cards currently assigns on Trello.
*   [darkskyx (⭐12)](https://github.com/techgaun/darkskyx) - A Darksky.com (formerly forecast.io) API client for Elixir.
*   [digitalocean (⭐15)](https://github.com/lukeed/elixir-digitalocean) - Elixir wrapper for the Digital Ocean API v2.
*   [digoc (⭐12)](https://github.com/kevinmontuori/digoc) - Digital Ocean API v2 Elixir Client.
*   [diplomat (⭐94)](https://github.com/peburrows/diplomat) - A [Google Cloud Datastore](https://cloud.google.com/datastore/) client.
*   [dnsimple (⭐51)](https://github.com/dnsimple/dnsimple-elixir) - Elixir client for the DNSimple API v2.
*   [docker (⭐26)](https://github.com/hexedpackets/docker-elixir) - Elixir client for the Docker Remote API.
*   [dockerex (⭐19)](https://github.com/hisea/dockerex) - Lightweight Docker Remote API Client with SSL/TLS login/connection support.
*   [dogstatsd (⭐40)](https://github.com/adamkittelson/dogstatsd-elixir) - An Elixir client for [DogStatsd](https://www.datadoghq.com/).
*   [dpd\_client (⭐1)](https://github.com/knewter/dpd_client) - An API client for the DPD service.
*   [dropbox (⭐13)](https://github.com/ammmir/elixir-dropbox) - Dropbox Core API client for Elixir.
*   [dublin\_bus\_api (⭐2)](https://github.com/carlo-colombo/dublin-bus-api) - Access to the Real Time Passenger Information (RTPI) for Dublin Bus services.
*   [edgarex (⭐3)](https://github.com/rozap/edgarex) - Elixir interface for fetching SEC filings from EDGAR.
*   [elixir\_authorizenet (⭐11)](https://github.com/marcelog/elixir_authorizenet) - Unofficial client for the Authorize.Net merchant API.
*   [elixir\_ipfs\_api (⭐47)](https://github.com/zabirauf/elixir-ipfs-api) - IPFS (InterPlanetary File System) API client for Elixir.
*   [elixirfm (⭐9)](https://github.com/jrichocean/Elixirfm) - Last.fm API wrapper for Elixir.
*   [elixtagram (⭐86)](https://github.com/zensavona/elixtagram) - Instagram API client for Elixir.
*   [ethereumex (⭐388)](https://github.com/exthereum/ethereumex) - Elixir JSON-RPC client for the Ethereum blockchain.
*   [everex (⭐10)](https://github.com/jwarlander/everex) - Evernote API client for Elixir.
*   [everyoneapi (⭐1)](https://github.com/knewter/everyoneapi) - API Client for EveryoneAPI.com.
*   [ex\_changerate (⭐4)](https://github.com/81dr/ex_changerate) - Elixir client for [exchangerate.host](https://exchangerate.host) API.
*   [ex\_codeship (⭐0)](https://github.com/securingsincity/ex_codeship) - API Client for Codeship.
*   [ex\_twilio (⭐343)](https://github.com/danielberkompas/ex_twilio) - Twilio API client for Elixir.
*   [ex\_twiml (⭐38)](https://github.com/danielberkompas/ex_twiml) - Generate TwiML for your Twilio integration, right inside Elixir.
*   [exdesk (⭐4)](https://github.com/deadkarma/exdesk) - Elixir library for the Desk.com API.
*   [exfacebook (⭐18)](https://github.com/oivoodoo/exfacebook) - Facebook API, written in Elixir using similar methods like Ruby koala gem.
*   [exgenius (⭐1)](https://github.com/jeffweiss/exgenius) - Elixir library for the (undocumented) Rap Genius API.
*   [exgravatar (⭐24)](https://github.com/scrogson/exgravatar) - An Elixir module for generating Gravatar URLs.
*   [exgrid (⭐8)](https://github.com/bradleyd/exgrid) - interact with Sendgrid's API.
*   [exjira (⭐6)](https://github.com/mattweldon/exjira) - JIRA client library for Elixir.
*   [explay (⭐16)](https://github.com/sheharyarn/explay) - Unofficial Google Play API in Elixir.
*   [extwitter (⭐410)](https://github.com/parroty/extwitter) - Twitter client library for Elixir.
*   [exurban (⭐2)](https://github.com/oscar-lopez/exurban) - Elixir wrapper for UrbanAirship API.
*   [facebook (⭐137)](https://github.com/mweibel/facebook.ex) - Facebook Graph API Wrapper written in Elixir.
*   [feedlex (⭐3)](https://github.com/essenciary/feedlex) - Feedly RSS reader client for Elixir.
*   [fluent\_client (⭐8)](https://github.com/trustatom-oss/elixir-fluent-client) - Minimalistic fluentd client.
*   [forcex (⭐52)](https://github.com/jeffweiss/forcex) - Elixir library for the Force.com REST API.
*   [forecast\_io (⭐8)](https://github.com/r-icarus/forecast_io) - Simple wrapper for Forecast.IO API.
*   [gcmex (⭐7)](https://github.com/dukex/gcmex) - Google Cloud Messaging client library for elixir.
*   [google-cloud (⭐1.1k)](https://github.com/GoogleCloudPlatform/elixir-google-api) - This repository contains all the client libraries to interact with Google APIs.
*   [google\_sheets (⭐41)](https://github.com/GrandCru/GoogleSheets) - Elixir library for fetching and polling Google spreadsheet data in CSV format.
*   [govtrack (⭐3)](https://github.com/walterbm/govtrack-elixir) - A simple Elixir wrapper for the [govtrack.us](https://www.govtrack.us/developers) API.
*   [gringotts (⭐492)](https://github.com/aviabird/gringotts) - A complete payment library for Elixir and Phoenix Framework similar to [ActiveMerchant (⭐4.6k)](https://github.com/activemerchant/active_merchant) from the Ruby world.
*   [honeywell (⭐0)](https://github.com/jeffutter/honeywell-elixir) - A client for the Honeywell Lyric, Round and Water Leak & Freeze Detector APIs.
*   [kane (⭐104)](https://github.com/peburrows/kane) - A [Google Cloud Pub/Sub](https://cloud.google.com/pubsub/overview) client.
*   [keenex (⭐28)](https://github.com/bryanjos/keenex) - A Keen.io API Client.
*   [link\_shrinkex (⭐8)](https://github.com/jonahoffline/link_shrinkex) - Elixir library for creating short URLs using Google's URL Shortener API.
*   [m2x](https://github.com/attm2x/m2x-elixir) - Elixir client for the AT\&T M2X, a cloud-based fully managed time-series data storage service for network connected machine-to-machine (M2M) devices and the Internet of Things (IoT). ([Erlang Version](https://github.com/attm2x/m2x-erlang)).
*   [mailchimp (⭐48)](https://github.com/duartejc/mailchimp) - A basic Elixir wrapper for version 3 of the MailChimp API.
*   [mailgun (⭐197)](https://github.com/chrismccord/mailgun) - Elixir Mailgun Client.
*   [mandrill (⭐50)](https://github.com/slogsdon/mandrill-elixir) - A Mandrill wrapper for Elixir.
*   [marvel (⭐10)](https://github.com/bryanjos/marvel) - CLI and Elixir API Client for the Marvel API.
*   [mexpanel (⭐2)](https://github.com/blendmedia/mexpanel) - An Elixir client for the Mixpanel HTTP API.
*   [mixpanel (⭐6)](https://github.com/michihuber/mixpanel_ex) - An Elixir client for the Mixpanel HTTP API.
*   [mixpanel\_data\_client (⭐4)](https://github.com/jeregrine/mixpanel_data_client) - Client for interacting with the Mixpanel Data Export API.
*   [mmExchangeRate (⭐0)](https://github.com/Arkar-Aung/mmExchangeRate) - A simple exchange rate checker and calculator based on Central Bank of Myanmar Api.
*   [nacha (⭐16)](https://github.com/RiverFinancial/nacha) - Elixir library for generating and parsing NACHA files for US ACH transfers.
*   [nadia (⭐364)](https://github.com/zhyu/nadia) - Telegram Bot API Wrapper written in Elixir.
*   [omise (⭐10)](https://github.com/omise/omise-elixir) - Omise client library for Elixir.
*   [opbeat (⭐7)](https://github.com/teodor-pripoae/opbeat) - Elixir client for Opbeat.
*   [pagexduty (⭐7)](https://github.com/ride/pagexduty) - A Pagerduty client for Elixir.
*   [parsex (⭐2)](https://github.com/maarek/ParsEx) - ParsEx is an Elixir HTTP Client for communicating with Parse.com's Restful API.
*   [particle (⭐6)](https://github.com/jeffutter/particle-elixir) - An Elixir client for the Particle IoT platform's HTTP API.
*   [pathway (⭐4)](https://github.com/novabyte/pathway) - An Erlang/Elixir client for the [Trak.io](http://trak.io/) REST API.
*   [pay (⭐27)](https://github.com/era/pay) - An Elixir Lib to deal with Paypal and other payment solutions.
*   [pay\_pal (⭐37)](https://github.com/zensavona/paypal) - Elixir library for working with the PayPal REST API.
*   [pigeon (⭐666)](https://github.com/codedge-llc/pigeon) - HTTP2-compliant wrapper for sending iOS and Android push notifications.
*   [pocketex (⭐7)](https://github.com/essenciary/pocketex) - Pocketex is an Elixir client for the Pocket read later service [getpocket.com](https://getpocket.com/).
*   [pusher (⭐27)](https://github.com/edgurgel/pusher) - Elixir library to access the Pusher REST API.
*   [qiniu (⭐60)](https://github.com/tony612/qiniu) - Qiniu SDK for Elixir.
*   [random\_user\_api](https://hex.pm/packages/random_user_api) - Another simple randomuser.me API client.
*   [reap (⭐4)](https://github.com/Raynes/reap) - Reap is a simple Elixir library for working with the refheap API.
*   [reddhl (⭐4)](https://github.com/MonkeyIsNull/reddhl) - An headline and link puller for Reddit and its various subreddits.
*   [redtube (⭐8)](https://github.com/kkirsche/Redtube_Elixir) - Redtube API Wrapper written in Elixir.
*   [reporter (⭐4)](https://github.com/KazuCocoa/simple_app_reporter_ex) - Reporter is simple reporting App reviews library. Support AppStore and GooglePlay.
*   [riemann (⭐57)](https://github.com/koudelka/elixir-riemann) - A [Riemann](http://riemann.io/) client for Elixir.
*   [rs\_twitter (⭐3)](https://github.com/radzserg/rstwitter) - Low Level Twitter Client for Elixir.
*   [semver (⭐2)](https://github.com/lee-dohm/semver) - Utilities for working with semver.org-compliant version strings.
*   [sendgrid (⭐87)](https://github.com/alexgaribay/sendgrid_elixir) - Send composable, transactional emails with SendGrid.
*   [shopify (⭐102)](https://github.com/nsweeting/shopify) - Easily access the Shopify API.
*   [sift\_ex (⭐13)](https://github.com/C404/sift_ex) - A Siftscience API Library for Elixir.
*   [simplex (⭐3)](https://github.com/adamkittelson/simplex) - An Elixir library for interacting with the Amazon SimpleDB API.
*   [slack (⭐677)](https://github.com/BlakeWilliams/Elixir-Slack) - Slack real time messaging client in Elixir.
*   [sparkpost (⭐44)](https://github.com/SparkPost/elixir-sparkpost) - An Elixir library for sending email using SparkPost.
*   [statix (⭐281)](https://github.com/lexmag/statix) - Expose app metrics in the StatsD protocol.
*   [stripity\_stripe (⭐1k)](https://github.com/robconery/stripity-stripe) - An Elixir Library for [Stripe](https://stripe.com/).
*   [tagplay (⭐0)](https://github.com/tagplay/elixir-tagplay) - Elixir client for Tagplay API.
*   [telegex (⭐157)](https://github.com/telegex/telegex) - Telegram bot framework and API client written in Elixir.
*   [telephonist (⭐41)](https://github.com/danielberkompas/telephonist) - Elixir state machines for Twilio calls.
*   [tentacat (⭐452)](https://github.com/edgurgel/tentacat) - Simple Elixir wrapper for the GitHub API.
*   [tg\_client (⭐14)](https://github.com/ccsteam/ex-telegram-client) - An Elixir wrapper which communicates with the Telegram-CLI.
*   [tradehub (⭐4)](https://github.com/anhmv/tradehub-elixir) - An Elixir client library for the Tradehub blockchain.
*   [traitify\_elixir (⭐2)](https://github.com/traitify/traitify_elixir) - An Elixir client library for the Traitify Developer's API.
*   [ui\_faces (⭐1)](https://github.com/katgironpe/ui_faces) - UIFaces API client for Elixir applications.
*   [unsplash-elixir (⭐15)](https://github.com/waynehoover/unsplash-elixir) - An Elixir library for Unsplash.
*   [vultr (⭐4)](https://github.com/avitex/elixir-vultr) - Simple wrapper for the Vultr API.
*   [xe (⭐22)](https://github.com/paulodiniz/xe) - Real time conversion for currencies.
*   [zanox (⭐1)](https://github.com/rafaelss/zanox) - Zanox API.

## Translations and Internationalizations

*Libraries and tools providing translations or internationalizations.*

*   [exkanji (⭐14)](https://github.com/ikeikeikeike/exkanji) - A Elixir library for translating between hiragana, katakana, romaji and kanji. It uses Mecab.
*   [exromaji (⭐9)](https://github.com/ikeikeikeike/exromaji) - A Elixir library for translating between hiragana, katakana and romaji.
*   [free PO editor](https://pofile.net/free-po-editor) - A tool for translating PO files.
*   [getatrex (⭐7)](https://github.com/alexfilatov/getatrex) - Automatic translation tool of Gettext locales with Google Translate for Elixir/Phoenix projects.
*   [gettext (⭐479)](https://github.com/elixir-lang/gettext) - Internationalization and localization support for Elixir.
*   [linguist (⭐183)](https://github.com/change/linguist) - Elixir Internationalization library.
*   [parabaikElixirConverter (⭐3)](https://github.com/Arkar-Aung/ParabaikElixirConverter) - ParabaikElixirConverter is just a Elixir version of Parabaik converter. It can convert from Unicode to Zawgyi-One and Zawgyi-One to Unicode vice versa.
*   [trans (⭐234)](https://github.com/belaustegui/trans) - A Elixir library to manage embedded translations into models leveraging PostgreSQL JSONB datatype.

## Utilities

*Utilities libraries.*

*   [ar2ecto (⭐13)](https://github.com/aforward/ar2ecto) - Ar2ecto is a set of mix tasks to help you migrate from ActiveRecord to Ecto.
*   [async\_with (⭐157)](https://github.com/fertapric/async_with) - A modifier for Elixir's "with" to execute all its clauses in parallel.
*   [crutches (⭐126)](https://github.com/mykewould/crutches) - Utility library for Elixir, designed to complement the standard library bundled with the language.
*   [deppie (⭐12)](https://github.com/whitfin/deppie) - Elixir's coolest deprecation logger.
*   [dot-notes (⭐8)](https://github.com/whitfin/dot-notes-elixir) - Simple dot/bracket notation parsing/conversion for Maps/Lists.
*   [dress (⭐61)](https://github.com/veelenga/dress) - Cli app that makes your stdout fancy.
*   [erlang-history (⭐494)](https://github.com/ferd/erlang-history) - Hacks to add shell history to Erlang's shell.
*   [erlsh (⭐62)](https://github.com/proger/erlsh) - Family of functions and ports involving interacting with the system shell, paths and external programs.
*   [erlware\_commons (⭐225)](https://github.com/erlware/erlware_commons) - Additional standard library for Erlang.
*   [ex\_progress (⭐6)](https://github.com/acj/ex_progress) - A library for tracking progress across many tasks and sub-tasks.
*   [exjprop (⭐0)](https://github.com/stocks29/exjprop) - Elixir library for reading Java properties files from various sources.
*   [fitex (⭐2)](https://github.com/timdeputter/FitEx) - FitEx is a Macro-Module which provides a bit of sugar for function definitions.
*   [global (⭐3)](https://github.com/mgwidmann/global) - Wrapper of the Erlang `:global` module.
*   [mandrake (⭐9)](https://github.com/mbasso/mandrake) - Mandrake is a functional programming library that bring something else magic in elixir.
*   [mnemonix (⭐39)](https://github.com/christhekeele/mnemonix) - A unified interface to key/value stores.
*   [once\_more (⭐7)](https://github.com/vegris/once_more) - Simple retries with composable backoff strategies.
*   [pachka (⭐16)](https://github.com/vegris/pachka) - Message batching library for Elixir applications.
*   [plasm (⭐91)](https://github.com/facto/plasm) - Plasm is Ecto's composable query multitool, containing higher-level functions such as .count, .random, .first, .last, .find, .inserted\_before, .inserted\_after, etc.
*   [plugmap (⭐3)](https://github.com/nerdslabs/plugmap) - Plugmap is sitemap generation library for Plug/Phoenix Framework.
*   [pubsub (⭐69)](https://github.com/simonewebdesign/elixir_pubsub) - A Publish-Subscribe utility library that implements a pub-sub mechanism to ease the burden of communication on the business logic processes.
*   [PubSubx (⭐2)](https://github.com/sonic182/pub_subx) - A simple publish-subscribe system built on Elixir's GenServer and Registry, allowing for dynamic topics, process monitoring, and automatic subscription management.
*   [quark (⭐320)](https://github.com/robot-overlord/quark) - A library for common functional programming idioms: combinators, currying, and partial application.
*   [retry (⭐453)](https://github.com/safwank/ElixirRetry) - Simple Elixir macros for linear retry, exponential backoff and wait with composable delays.
*   [sips\_downloader (⭐14)](https://github.com/DavsX/SipsDownloader) - Elixir module for downloading the ElixirSips episodes and all other files.
*   [sitemap (⭐106)](https://github.com/ikeikeikeike/sitemap) - Sitemap is the easiest way to generate Sitemaps in Elixir.
*   [sitemapper (⭐46)](https://github.com/tomtaylor/sitemapper) - A fast, stream based XML Sitemap generator.
*   [uef-lib (⭐16)](https://github.com/DOBRO/uef-lib) - Useful Erlang Functions Library that provides modules for manipulating lists, binaries, maps, numbers, date and time. It  contains some functions optimized for performance in specific cases (e.g. for file I/O operations or binary transformations).
*   [vert.x (⭐16)](https://github.com/PharosProduction/ExVertx) - Elixir event bus bridge to Vert.x services using TCP socket.

## Validations

*Libraries and implementations for validation of data.*

*   [bankster (⭐34)](https://github.com/railsmechanic/bankster) - A IBAN account number and BIC validation library for Elixir.
*   [ex\_gtin (⭐16)](https://github.com/kickinespresso/ex_gtin) - A validation library for GTIN codes under GS1 specification.
*   [ex\_nric (⭐2)](https://github.com/falti/ex_nric) - Validation for Singapore National Registration Identity Card numbers (NRIC).
*   [exop (⭐217)](https://github.com/madeinussr/exop) - A library that allows to encapsulate business logic and validate params with predefined contract.
*   [form (⭐39)](https://github.com/synrc/form) - Document forms and validation library.
*   [goal (⭐82)](https://github.com/martinthenth/goal) - A parameter validation library for LiveViews and JSON/HTML controllers - based on Ecto.
*   [is (⭐20)](https://github.com/bydooweedoo/is) - Fast, extensible and easy to use data structure validation for elixir with nested structures support.
*   [jeaux (⭐13)](https://github.com/zbarnes757/jeaux) - A light and easy schema validator.
*   [optimal (⭐50)](https://github.com/albert-io/optimal) - A schema based keyword list option validator.
*   [shape (⭐6)](https://github.com/prio/shape) - A data validation library for Elixir based on Prismatic Scheme.
*   [skooma (⭐141)](https://github.com/bcoop713/skooma) - Simple data validation library for describing and validating data structures.
*   [to\_atom\_in (⭐0)](https://github.com/JohnJocoo/to_atom_in) - Utility to safely convert string an atom in set.
*   [uk\_postcode (⭐10)](https://github.com/KushalP/uk_postcode) - UK postcode parsing and validation library.
*   [vex (⭐604)](https://github.com/CargoSense/vex) - An extensible data validation library for Elixir.

## Version Control

*Working with version control like git, mercury, subversion ...*

*   [gitex (⭐69)](https://github.com/awetzel/gitex) - Elixir implementation of the Git object storage, but with the goal to implement the same semantic with other storage and topics.

## Video

*Libraries for working with and manipulating video and multimedia.*

*   [ffmpex (⭐234)](https://github.com/talklittle/ffmpex) - FFmpeg command line wrapper.
*   [silent\_video (⭐21)](https://github.com/talklittle/silent_video) - Convert GIFs and videos to silent videos, optimized for mobile playback.

## WebAssembly

*Libraries for running WebAssembly (WASM) in Elixir or running Elixir on WebAssembly.*

*   [lumen (⭐3.6k)](https://github.com/lumen/lumen) - An alternative BEAM implementation, designed for WebAssembly.
*   [wasmex (⭐641)](https://github.com/tessi/wasmex/) - Execute WebAssembly / WASM binaries from Elixir.

## XML

*Libraries and implementations working with XML (for html tools please go to the [HTML](#html) section).*

*   [elixir-map-to-xml (⭐5)](https://github.com/gunnar2k/elixir-map-to-xml) - Converts an Elixir map to an XML document.
*   [elixir-xml-to-map (⭐54)](https://github.com/homanchou/elixir-xml-to-map) - Creates an Elixir Map data structure from an XML string.
*   [erlsom (⭐267)](https://github.com/willemdj/erlsom) - Erlsom is an Erlang library to parse (and generate) XML documents.
*   [exmerl (⭐12)](https://github.com/pwoolcoc/exmerl) - Elixir wrapper for xmerl.
*   [exml (⭐25)](https://github.com/expelledboy/exml) - Most simple Elixir wrapper for xmerl xpath.
*   [exoml (⭐7)](https://github.com/Overbryd/exoml) - A module to decode/encode xml into a tree structure.
*   [fast\_xml (⭐135)](https://github.com/processone/fast_xml) - Fast Expat based Erlang XML parsing library.
*   [meeseeks (⭐322)](https://github.com/mischov/meeseeks#xml) - A library for parsing and extracting data from HTML and XML with CSS or XPath selectors.
*   [quinn (⭐51)](https://github.com/nhu313/Quinn) - XML parser for Elixir.
*   [saxy (⭐290)](https://github.com/qcam/saxy) - Saxy is an XML parser and encoder in Elixir that focuses on speed and standard compliance.
*   [sweet\_xml (⭐368)](https://github.com/awetzel/sweet_xml) - Query XML simply and effectively.
*   [xml\_builder (⭐183)](https://github.com/joshnuss/xml_builder) - Elixir library for generating xml.
*   [xmlrpc (⭐40)](https://github.com/ewildgoose/elixir-xml_rpc) - Library for encoding and decoding XML-RPC for clients and servers.

## YAML

*Libraries and implementations working with YAML.*

*   [fast\_yaml (⭐51)](https://github.com/processone/fast_yaml) - Fast YAML is an Erlang wrapper for libyaml "C" library.
*   [yamerl (⭐208)](https://github.com/yakaz/yamerl) - YAML 1.2 parser in Erlang.
*   [yaml\_elixir (⭐175)](https://github.com/KamilLelonek/yaml-elixir) - Yaml parser for Elixir based on native Erlang implementation.
*   [ymlr (⭐23)](https://github.com/ufirstgroup/ymlr) - A YAML encoder for Elixir.
*   [yomel (⭐6)](https://github.com/Joe-noh/yomel) - libyaml interface for Elixir.

# Resources

Various resources, such as books, websites and articles, for improving your Elixir development skills and knowledge.

## Books

*Fantastic books and e-books.*

*   [Adopting Elixir](https://pragprog.com/book/tvmelixir/adopting-elixir) - Bring Elixir into your company, with real-life strategies from the people who built Elixir and use it successfully at scale. This book has all the information you need to take your application from concept to production (2017).
*   [Async Elixir (⭐170)](https://github.com/Arp-G/async-elixir) - Dive into Elixir's world of concurrency and processes with this interactive Livebook.
*   [Craft GraphQL APIs in Elixir with Absinthe](https://pragprog.com/book/wwgraphql/craft-graphql-apis-in-elixir-with-absinthe) - Upgrade your web API to GraphQL, leveraging its flexible queries to empower your users, and its declarative structure to simplify your code (2017).
*   [Elixir Cookbook](https://www.packtpub.com/application-development/elixir-cookbook) - This book is a set of recipes grouped by topic by Paulo A Pereira (2015).
*   [Elixir do zero à concorrência](https://www.casadocodigo.com.br/products/livro-elixir) - (Portuguese) The book provides introduction to functional and concurrent programming with Elixir by Tiago Davi (2014).
*   [Elixir in Action](https://www.manning.com/books/elixir-in-action) - A brief intro to the language followed by a more detailed look at building production-ready systems in Elixir by Saša Jurić (2015).
*   [Elixir in Action, Second Edition](https://www.manning.com/books/elixir-in-action-second-edition) - Revised and updated for Elixir 1.7, Elixir in Action, Second Edition teaches you how to apply Elixir to practical problems associated with scalability, fault tolerance, and high availability (2019).
*   [Elixir in Action, Third Edition](https://www.manning.com/books/elixir-in-action-third-edition) - Fully updated to Elixir 1.14, this authoritative bestseller reveals how Elixir tackles problems of scalability, fault tolerance, and high availability (2023).
*   [Elixir Succinctly](https://www.syncfusion.com/ebooks/elixir-succinctly) - A short book to learn the basic of Elixir and its ecosystem.
*   [Engineering Elixir Applications](https://pragprog.com/titles/beamops/engineering-elixir-applications/) - *(currently in Beta)* As the subtitle suggests, this book explores the technologies and skills that support navigating each stage of software delivery with confidence.
*   [Erlang and Elixir for Imperative Programmers](https://leanpub.com/erlangandelixirforimperativeprogrammers) - Introduction to Erlang and Elixir in the context of functional concepts by Wolfgang Loder (2016).
*   [Erlang in Anger](http://www.erlang-in-anger.com/) - This book intends to be a little guide about how to be the Erlang medic in a time of war by Fred Hebert (2014).
*   [Functional Web Development with Elixir, OTP, and Phoenix](https://pragprog.com/book/lhelph/functional-web-development-with-elixir-otp-and-phoenix) - Open doors to powerful new techniques that will get you thinking about web development in fundamentally new ways (2017).
*   [Getting Started - Elixir (⭐100)](https://github.com/potatogopher/elixir-getting-started) - PDF, MOBI, and EPUB documents for Elixir's Getting Started tutorial (2016).
*   [Hands-on Elixir & OTP: Cryptocurrency trading bot](https://www.elixircryptobot.com) - Want to learn Elixir & OTP by creating a real-world project? With Hands-on *Elixir & OTP: Cryptocurrency trading bot* you will gain hands-on experience by working on an interesting software project. We will explore all the key abstractions and essential principles through iterative implementation improvements. (2021).
*   [Introducing Elixir ](http://shop.oreilly.com/product/0636920030584.do) - A gentle introduction to the language, with lots of code examples and exercises by Simon St. Laurent and J. David Eisenberg (2013).
*   [Learn Functional Programming with Elixir](https://pragprog.com/book/cdc-elixir/learn-functional-programming-with-elixir) - Don’t board the Elixir train with an imperative mindset! To get the most out of functional languages, you need to think functionally (2017).
*   [Metaprogramming Elixir: Write Less Code, Get More Done (and Have Fun!)](https://pragprog.com/book/cmelixir/metaprogramming-elixir) - Thorough explanation on how to exploit Elixir's metaprogramming capabilities to improve your Elixir coding by Chris McCord (2015).
*   [Phoenix for Rails Developers](http://www.phoenixforrailsdevelopers.com) - This book shows how Rails developers can benefit from their existing knowledge to learn Phoenix. By Elvio Vicosa (2017).
*   [Phoenix in Action](https://manning.com/books/phoenix-in-action) - builds on your existing web dev skills, teaching you the unique benefits of Phoenix along with just enough Elixir to get the job done. By Geoffrey Lessel (2017).
*   [Phoenix Inside Out](https://shankardevy.com/phoenix-book/) - The goal of this series is to enable you as a Confident Phoenix developer. There are 3 different editions to address varied needs of devs jumping into Phoenix.
*   [Programming Elixir 1.6](https://pragprog.com/titles/elixir16/) - The book provides introduction to functional and concurrent programming with Elixir by Dave Thomas (2014).
*   [Programming Phoenix 1.4](https://pragprog.com/titles/phoenix14/) - Definitive guide to build web applications with the Phoenix framework by Chris McCord, José Valim and Bruce Tate (2015).
*   [The Beam Book](https://happi.github.io/theBeamBook/) - A description of the Erlang Runtime System ERTS and the virtual Machine BEAM.
*   [The Little Elixir & OTP Guidebook](https://www.manning.com/books/the-little-elixir-and-otp-guidebook) - A book for learning Elixir and OTP through small to medium-sized projects by Benjamin Tan Wei Hao (2014).
*   [The Phoenix LiveView Cookbook](https://www.liveviewcookbook.com/) - A Phoenix LiveView e-book containing tried and tested recipes for solving common problems.
*   [Études for Elixir](https://www.oreilly.com/library/view/etudes-for-elixir/9781491917640/) - A collection of exercises to program in Elixir by J. David Eisenberg (2013) ([Github Repo (⭐518)](https://github.com/oreillymedia/etudes-for-elixir)).

## Cheat Sheets

*Useful Elixir-related cheat sheets.*

*   [benjamintanweihao/elixir-cheatsheets (⭐106)](https://github.com/benjamintanweihao/elixir-cheatsheets/) - GenServer and Supervisor cheatsheets.
*   [elixir-lang/elixir](https://hexdocs.pm/elixir/main/enum-cheat.html) - Enum cheatsheets.

## Community

*Getting in contact with the community via chat or mailinglist.*

*   [#elixir-lang](http://webchat.freenode.net/?channels=elixir-lang) - The IRC Channel #elixir-lang on Freenode.
*   [Elixir Forum](https://elixirforum.com/) - Community run discussion forums for all things Elixir.
*   [elixir-lang-core](https://groups.google.com/d/forum/elixir-lang-core) - Mailinglist for Elixir Core development, use "talk" for questions and general discussions.
*   [elixir-lang-talk](https://groups.google.com/d/forum/elixir-lang-talk) - Official Elixir Mailinglist for questions and discussions.
*   [ElixirSlack](https://elixir-slackin.herokuapp.com/) - Elixir Slack Community.

## Editors

*Editors and IDEs useable for Elixir/Erlang*

*   [Alchemist (⭐908)](https://github.com/tonini/alchemist.el) - Elixir Tooling Integration Into Emacs.
*   [Alchemist-Server (⭐192)](https://github.com/tonini/alchemist-server) - Editor/IDE independent background server to inform about Elixir mix projects.
*   [Alchemist.vim (⭐648)](https://github.com/slashmili/alchemist.vim) - Elixir Tooling Integration Into Vim.
*   [Atom](https://atom.io/packages/language-elixir) - Elixir language support for Atom.
*   [atom-elixir (⭐405)](https://github.com/msaraiva/atom-elixir) - An Atom package for Elixir.
*   [atom-iex (⭐14)](https://github.com/indiejames/atom-iex) - Run an IEx session in Atom.
*   [elixir-ls (⭐846)](https://github.com/JakeBecker/elixir-ls) - A frontend-independent IDE "smartness" server for Elixir. Implements the JSON-based "Language Server Protocol" standard and provides debugger support via VS Code's debugger protocol.
*   [elixir-tmbundle (⭐261)](https://github.com/elixir-lang/elixir-tmbundle) - A TextMate and SublimeText bundle for Elixir.
*   [elixir\_generator (⭐9)](https://github.com/jadercorrea/elixir_generator.vim) - Vim plugin to generate Elixir module and test files with one command.
*   [ElixirSublime (⭐365)](https://github.com/vishnevskiy/ElixirSublime) - Elixir plugin for SublimeText 3 that provides code completion and linting.
*   [Jetbrains (⭐1.9k)](https://github.com/KronicDeth/intellij-elixir) - Elixir for IntelliJ IDEA, RubyMine, WebStorm, PhpStorm, PyCharm, AppCode, Android Studio, 0xDBE.
*   [mix.nvim (⭐28)](https://github.com/brendalf/mix.nvim) - Mix wrapper plugin for Neovim.
*   [Notepad++ (⭐7)](https://github.com/Hades32/elixir-udl-npp) - Elixir syntax highlighting for Notepad++.
*   [Nova Elixir (⭐9)](https://github.com/stollcri/elixir.novaextension) - Syntax highlighting and code completion for Elixir files (.ex, .exs, .eex) in Nova.
*   [nvim (⭐28)](https://github.com/dm1try/nvim) - Neovim host for writing plugins in Elixir.
*   [phoenix-snippets (⭐5)](https://github.com/phoenixframework-Brazil/phoenix-snippets) - Phoenix Snippets for Atom.
*   [vim-elixir (⭐1.3k)](https://github.com/elixir-lang/vim-elixir) - Vim configuration files for Elixir.
*   [vim-ex\_test (⭐4)](https://github.com/moofish32/vim-ex_test) - Vim test runner based on Thoughtbots vim-rspec.
*   [vim-mix-format (⭐220)](https://github.com/mhinz/vim-mix-format) - Async `mix format` for Vim and Neovim.
*   [vscode-elixir (⭐4)](https://github.com/mat-mcloughlin/vscode-elixir) - Elixir Support for Visual Studio Code.
*   [vscode-elixir-ls (⭐388)](https://github.com/JakeBecker/vscode-elixir-ls) - Elixir language support and debugger for VS Code, powered by ElixirLS.

## Newsletters

*Useful Elixir-related newsletters.*

*   [Elixir Digest](http://elixirdigest.net) - A weekly newsletter with the latest articles on Elixir and Phoenix.
*   [Elixir Merge](https://elixirmerge.com) - A daily newsletter which delivers two curated updates (articles, tutorials, videos, podcasts) in each edition in quick-read format.
*   [Elixir Radar](http://plataformatec.com.br/elixir-radar) - The "official" Elixir newsletter, published weekly via email by Plataformatec.
*   [ElixirWeekly](https://elixirweekly.net) - The Elixir community newsletter, covering stuff you easily miss, shared on [ElixirStatus](http://elixirstatus.com) and the web.

## Other Awesome Lists

*Other amazingly awesome lists can be found at [jnv/lists (⭐10k)](https://github.com/jnv/lists#lists-of-lists) or [bayandin/awesome-awesomeness (⭐33k)](https://github.com/bayandin/awesome-awesomeness#awesome-awesomeness).*

*   [Awesome Elixir and CQRS (⭐729)](https://github.com/slashdotdash/awesome-elixir-cqrs) - A curated list of awesome Elixir and Command Query Responsibility Segregation (CQRS) and event sourcing resources.
*   [Awesome Elixir by LibHunt](https://elixir.libhunt.com) - A curated list of awesome Elixir and Erlang packages and resources.
*   [Awesome Erlang (⭐1.7k)](https://github.com/drobakowski/awesome-erlang) - A curated list of awesome Erlang libraries, resources and shiny things.
*   [Curated Elixir Resources](https://hackr.io/tutorials/learn-elixir) - A collection of top recommended Elixir resources.
*   [Erlang Bookmarks (⭐1.2k)](https://github.com/0xAX/erlang-bookmarks) - A collection of links for Erlang developers.

## Podcasts

*Podcasts discussing the Elixir language and community.*

*   [Elixir Fountain](https://soundcloud.com/elixirfountain) - The Elixir Fountain podcast.
*   [Elixir Mix](https://devchat.tv/elixir-mix/) - The Elixir Mix podcast.
*   [Elixir Outlaws](https://elixiroutlaws.com) - The Elixir Outlaws podcast.
*   [Elixir Talk](https://soundcloud.com/elixirtalk) - The Elixir Talk podcast.
*   [Thinking Elixir](https://podcast.thinkingelixir.com) - The Thinking Elixir podcast.

## Reading

*Elixir-related reading materials.*

*   [Discover Elixir & Phoenix](https://www.ludu.co/course/discover-elixir-phoenix/) - An online course that teaches both the Elixir language and the Phoenix framework.
*   [Elixir Cheat-Sheet](http://media.pragprog.com/titles/elixir/ElixirCheat.pdf) - A Elixir cheat sheet, by Andy Hunt & Dave Thomas.
*   [Elixir Code Smells (⭐1.5k)](https://github.com/lucasvegi/Elixir-Code-Smells) - A catalog of Elixir-specific code smells that can harm the quality of software developed using this language.
*   [Elixir Functional Programming (⭐362)](https://github.com/kblake/functional-programming) - Material to introduce functional programming using the Elixir language.
*   [Elixir Refactorings (⭐175)](https://github.com/lucasvegi/Elixir-Refactorings) - A catalog of refactoring strategies to promote the redesign and improve the quality of code developed with Elixir.
*   [Elixir School](https://elixirschool.com/) - Lessons about the Elixir programming language.
*   [Elixir Tab (⭐104)](https://github.com/efexen/elixir-tab) - Chrome Extension which helps you learn the Elixir core lib.
*   [Elixir vs Ruby | How Switching To Elixir Made Our Team Better](https://foxbox.com/blog/elixir-vs-ruby/) - Long-form post that explains in detail when and why you should choose Elixir over Ruby.
*   [Learn With Me: Elixir](https://inquisitivedeveloper.com/tag/lwm-elixir/) - A series where I learn Elixir and you can learn along with me.
*   [The Little Schemer in Elixir (⭐349)](https://github.com/jwhiteman/a-little-elixir-goes-a-long-way) - Exercises and algorithms from the Little Schemer book, ported to Elixir.
*   [xElixir (⭐643)](https://github.com/exercism/xelixir) - Exercism Exercises in Elixir.

## Screencasts

*Cool video tutorials.*

*   [Alchemist Camp](https://alchemist.camp) - Alchemist.Camp has many hours of free, project-based Elixir-learning screencasts.
*   [Confreaks (Elixir)](http://confreaks.tv/tags/40) - Elixir related conference talks.
*   [Curso de Elixir de 0 a 100](https://www.youtube.com/watch?v=-K74G9nlzSY\&list=PLMLox3fRb_I4_4-DnU3yS_EglDAuVpeEg) - Complete course of elixir (in spanish) for free.
*   [Elixir for Programmers](https://codestool.coding-gnome.com/courses/elixir-for-programmers) - Functional, Parallel, Reliable (and fun!), taught by Dave Thomas.
*   [Elixir Foundation](https://www.youtube.com/playlist?list=PLjQo0sojbbxXc4aWg5i2umjv7U8YDoHQT) - Learn Elixir by building a practical example. Learn how GenServer, Agents and many other elixir primitives work.
*   [Elixir Sips](http://elixirsips.com/) - Tiny screencasts for learning Elixir.
*   [ElixirCasts.io](https://elixircasts.io/) - Simple screencasts to help you learn Elixir and Phoenix.
*   [ExCasts](https://excasts.com) - Elixir and Phoenix screencasts for all skill levels.
*   [Kamil Skowron](https://www.youtube.com/c/kamilskowron) - YouTube channel dedicated to promote functional programming, publishing "real world" programming videos in Elixir like "Hands-on Elixir & OTP: Cryptocurrency trading bot" series.
*   [LearnElixir.tv](https://www.learnelixir.tv/) - Beginner friendly, in-depth, step by step screencasts.
*   [LearnPhoenix.tv](https://www.learnphoenix.tv/) - Learn how to build fast, dependable web apps with Phoenix.
*   [Meet Elixir](https://www.pluralsight.com/courses/meet-elixir) - Walk through some features and concepts of Elixir by José Valim.

## Styleguides

*Styleguides for ensuring consistency while coding.*

*   [christopheradams/elixir\_style\_guide (⭐4.4k)](https://github.com/christopheradams/elixir_style_guide) - A community-driven style guide for Elixir.
*   [lexmag/elixir-style-guide (⭐523)](https://github.com/lexmag/elixir-style-guide) - An opinionated Elixir style guide.
*   [rrrene/elixir-style-guide (⭐399)](https://github.com/rrrene/elixir-style-guide) - Style guide checked by [Credo (⭐5k)](https://github.com/rrrene/credo).

## Websites

*Useful Elixir-related websites.*

*   [30 Days of Elixir (⭐3k)](https://github.com/seven1m/30-days-of-elixir) - A walk through the Elixir language in 30 exercises.
*   [BEAM Community](http://beamcommunity.github.io/) - From distributed systems, to robust servers and language design on the Erlang VM.
*   [Benjamin Tan - Learnings & Writings](http://benjamintan.io/blog/tags/elixir/) - A blog consisting of mostly Elixir posts.
*   [Elixir Career](https://elixir.career/) - A job board for Elixir, and community of Elixir developers.
*   [Elixir Examples](http://elixir-examples.github.io/) - A collection of small Elixir programming language examples.
*   [Elixir Flashcards](https://elixircards.co.uk/) - Flashcards are a powerful way to improve your knowledge. Elixircards are hand crafted, professionally printed flashcards for levelling up your Elixir.
*   [Elixir Github Repository (⭐25k)](https://github.com/elixir-lang/elixir) - The project repository.
*   [Elixir Github Wiki (⭐25k)](https://github.com/elixir-lang/elixir/wiki) - The project's wiki, containing much useful information.
*   [Elixir Online Courses list - Classpert](https://classpert.com/elixir-programming) - A list of Elixir Online Courses (some are free) from Classpert Online Course Search.
*   [Elixir Quiz](http://elixirquiz.github.io/) - Weekly programming problems to help you learn Elixir.
*   [Elixir Recipes](http://elixir-recipes.github.io/) - Collection of patterns & solutions to common problems in Elixir.
*   [ElixirLibs](https://elixirlibs.com) - A curated list of Elixir libraries.
*   [Hashrocket Today I Learned - Elixir](https://til.hashrocket.com/elixir) - Small posts about Elixir from the team at Hashrocket.
*   [How I start - Elixir](http://howistart.org/posts/elixir/1) - Explanation and intro to Elixir by José Valim.
*   [Learning Elixir](http://learningelixir.joekain.com/) - A blog about a Professional Software Engineer learning Elixir.

# Contributing

Please see [CONTRIBUTING (⭐13k)](https://github.com/h4cc/awesome-elixir/blob/master/.github/CONTRIBUTING.md) for details.

