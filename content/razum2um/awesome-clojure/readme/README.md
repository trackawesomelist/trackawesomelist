# Awesome Clojure Overview

A curated list of awesome Clojure libraries and resources. Inspired by awesome-... stuff

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/razum2um/awesome-clojure/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 razum2um/awesome-clojure](https://github.com/razum2um/awesome-clojure) · ⭐ 2.6K · 🏷️ Programming Languages

[ [Daily](/content/razum2um/awesome-clojure/README.md) / [Weekly](/content/razum2um/awesome-clojure/week/README.md) / Overview ]

---

# Awesome Clojure [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

*   [Awesome products in Clojure](#awesome-products-in-clojure)
    *   [OneKeePass (⭐61)](https://github.com/OneKeePass/desktop): A secure password manager and [mobile app in ClojureScript (⭐38)](https://github.com/OneKeePass/mobile)
    *   [Penpot](https://penpot.app/): design and prototyping platform
    *   [LightTable (IDE)](http://lighttable.com/) (archived)
    *   [Maria.cloud (Online IDE for beginners)](https://www.maria.cloud/)
    *   [Riemann (Monitoring)](http://riemann.io/)
    *   [Precursor (Online prototyping tool)](https://precursorapp.com/)
    *   [Puppet Server (⭐282)](https://github.com/puppetlabs/puppet-server)
    *   [PuppetDB (⭐292)](https://github.com/puppetlabs/puppetdb)
    *   [Metabase (⭐35k)](https://github.com/metabase/metabase)
    *   [Metabase Datomic (⭐63)](https://github.com/lambdaisland/metabase-datomic)
    *   [CircleCI](https://circleci.com/)
    *   [Avi (vim rewrite) (⭐215)](https://github.com/maitria/avi)
    *   [Liquid (Text Editor) (⭐956)](https://github.com/mogenslund/liquid)
    *   [Clojupyter (⭐801)](https://github.com/clojupyter/clojupyter)
    *   [meins (⭐9)](https://github.com/matthiasn/meins)
    *   [Jepsen (⭐6.5k)](https://github.com/jepsen-io/jepsen)
    *   [Braid (⭐908)](https://github.com/braidchat/braid): a team-chat app with a novel UI that leads to better conversations
    *   [Accelerated Text (⭐778)](https://github.com/tokenmill/accelerated-text): a natural language generation environment (backend: Clojure, frontend: JS)
    *   [Ziggurat (⭐384)](https://github.com/gojek/ziggurat): a framework built to simplify Stream processing on Kafka
    *   [Nightcode (⭐1.4k)](https://github.com/oakes/Nightcode): An IDE for Clojure (archived)
    *   [Nightlight (⭐790)](https://github.com/oakes/Nightlight): text editor (archived)
    *   [Atea (⭐611)](https://github.com/pkamenarsky/atea): a minimalistic menu bar time tracker for MacOS (legacy, requires jvm 1.6)
    *   [herfi (⭐106)](https://github.com/ertugrulcetin/herfi) - 3D multiplayer game prototype written in Clojure and ClojureScript
    *   [racing-game-cljs (⭐232)](https://github.com/ertugrulcetin/racing-game-cljs) - A 3D racing game built with ClojureScript, React and ThreeJS

*   [Awesome SaaS (partially OSS) in Clojure](#awesome-saas-in-clojure)
    *   [Logseq (⭐27k)](https://github.com/logseq/logseq): knowledge management and collaboration (open frontend)

*   [Languages written with Clojure](#languages-written-with-clojure)
    *   [jank (⭐1.3k)](https://github.com/jeaye/jank)
    *   [lux (⭐1.6k)](https://github.com/LuxLang/lux)
    *   [mal (⭐9.6k)](https://github.com/kanaka/mal/tree/master/impls/clojure)
    *   [scheje (⭐140)](https://github.com/turbopape/scheje)
    *   [eden (⭐131)](https://github.com/benzap/eden)
    *   [ferret](https://ferret-lang.org)

*   [Awesome tools in Clojure](#awesome-tools-in-clojure)
    *   [Awesome macros usage](#awesome-macros-usage)
    *   [Advanced datastructures](#advanced-datastructures)
    *   [Web Framework](#web-framework)
    *   [Dependency injection](#dependency-injection)
    *   [Build Automation and Package management](#build-automation-and-package-management)
    *   [Version Control Management](#version-control-management)
    *   [Date and Time](#date-and-time)
    *   [GUI](#gui)
    *   [Audio](#audio)
    *   [HTTP](#http)
    *   [Database](#database)
    *   [Connection pools](#connection-pools)
    *   [Structural Migrations](#structural-migrations)
    *   [Redis](#redis)
    *   [JSON](#json)
    *   [Protocol Buffers and gRPC](#protocol-buffers-and-grpc)
    *   [ORM and SQL generation](#orm-and-sql-generation)
    *   [Security](#security)
    *   [RESTful API](#restful-api)
    *   [GraphQL API](#graphql-api)
    *   [Emails](#emails)
    *   [HTML Manipulation](#html-manipulation)
    *   [Data Validation](#data-validation)
    *   [Type System](#type-system)
    *   [Pattern Matching](#pattern-matching)
    *   [Async processing](#async-processing)
    *   [Monads](#monads)
    *   [WebSocket](#websocket)
    *   [Testing](#testing)
    *   [Webdriver automation](#webdriver-automation)
    *   [Code Analysis and Linter](#code-analysis-and-linter)
    *   [Science and Data Analysis](#science-and-data-analysis)
    *   [Machine Learning](#machine-learning)
    *   [Computer Vision](#computer-vision)
    *   [Text Processing](#text-processing)
    *   [Parsing](#parsing)
    *   [Editor Plugins](#editor-plugins)
    *   [Documentation](#documentation)
    *   [Literate Programming](#literate-programming)
    *   [Archives and Compression](#archives-and-compression)
    *   [Miscellaneous](#miscellaneous)
    *   [Debugging tools](#debugging)
    *   [CI](#ci)
    *   [Project Management](#project-management)
    *   [Terminal UI](#terminal-ui)
    *   [Graphviz](#graphviz)

*   [Resources](#resources)
    *   [Guides](#guides)
    *   [Video tutorials](#video-tutorials)
    *   [Websites](#websites)
    *   [Twitter](#twitter)
    *   [Exercises](#exercises)

## Awesome macros usage

*Answers why the lisp shines, killer features in action*

*   [core.async (⭐1.9k)](https://github.com/clojure/core.async) - transforms AST into CSP programs
*   [cloroutine (⭐217)](https://github.com/leonoel/cloroutine) - suspends and continuations (coroutines)
*   [missionary (⭐574)](https://github.com/leonoel/missionary) - a reactive dataflow programming toolkit
*   [photon (⭐7)](https://github.com/venantius/photon) - realtime web, like Meteor, but for Clojure(Script)
*   [metaclj (⭐79)](https://github.com/brandonbloom/metaclj) - staged compilation
*   [meander (⭐891)](https://github.com/noprompt/meander) - transparent data transformation using datastructure pattermatching
*   [proteus (⭐110)](https://github.com/ztellman/proteus) - introduce mutable variables (don't use, just learn how to map your mind into immutable world)

## Advanced datastructures

*   [specter (⭐2.5k)](https://github.com/redplanetlabs/specter): an elegant API for querying and transforming nested and recursive data
*   [meander (⭐891)](https://github.com/noprompt/meander): transparent data transformation (defined as pattern-matching)
*   [Persistent AVL trees (⭐122)](https://github.com/clojure/data.avl): persistent sorted maps and sets with log-time rank queries
*   [Finger Tree (⭐213)](https://github.com/clojure/data.finger-tree): double-list, counted-double-list, counted-sorted-set
*   [Hitchhiker Tree (⭐1.2k)](https://github.com/datacrypt-project/hitchhiker-tree): create fast, snapshottable, massively scalable databases
*   [Hierarchical set (⭐7)](https://github.com/llasram/hier-set)
*   [Ordered (⭐248)](https://github.com/amalloy/ordered): ordered sets and maps
*   [Lazy Map (⭐48)](https://github.com/Malabarba/lazy-map-clojure): whose values are only calculated when accessed
*   [Duratom (⭐190)](https://github.com/jimpil/duratom): persisted atoms
*   [Durable Queue (⭐379)](https://github.com/Factual/durable-queue): queue persisted on disk
*   [bifurcan (⭐953)](https://github.com/lacuna/bifurcan): linear map/set/list (stores entries contiguously in memory), ;writtern in java, but test suite (read: usage examples) [in clojure (⭐953)](https://github.com/lacuna/bifurcan/blob/master/test/bifurcan)

## Web Framework

*Actually don't search rails/django here, but compose them by yourself*

*   [Compojure (⭐4k)](https://github.com/weavejester/compojure)
*   [Compojure-api (⭐1.1k)](https://github.com/metosin/compojure-api)
*   [Luminus](http://www.luminusweb.net/)
*   [Duct (⭐1.1k)](https://github.com/weavejester/duct)
*   [Pedestal (⭐2.6k)](https://github.com/pedestal/pedestal)
*   [Datsys (⭐231)](https://github.com/metasoarous/datsys)
*   [yada (⭐729)](https://github.com/juxt/yada)
*   [Hoplon](http://hoplon.io/)
*   [Fulcro (⭐1.5k)](https://github.com/fulcrologic/fulcro)
*   [Coast](http://coastonclojure.com/)
*   [Reitit (⭐1.4k)](https://github.com/metosin/reitit)
*   [Tadam](https://www.tadam-framework.dev/)
*   [Column](https://gitlab.com/demonshreder/column)
*   [Biff](https://biffweb.com/)

## Dependency injection

*Managed lifecycle of stateful objects*

*   [Component (⭐2.1k)](https://github.com/stuartsierra/component)
*   [System (⭐603)](https://github.com/danielsz/system)
*   [mount (⭐1.2k)](https://github.com/tolitius/mount)
*   [Integrant (⭐1.2k)](https://github.com/weavejester/integrant)
*   [clip (⭐224)](https://github.com/juxt/clip)
*   [piotr-yuxuan/closeable-map (⭐54)](https://github.com/piotr-yuxuan/closeable-map)
*   [darkleaf/di (⭐31)](https://github.com/darkleaf/di)

## Build Automation and Package management

*Libraries for project build automation and package/dependency management.*

*   [Leiningen (⭐7.3k)](https://github.com/technomancy/leiningen)
*   [Boot (⭐1.8k)](https://github.com/boot-clj/boot)
*   [tools.build](https://www.clojure.org/guides/tools_build)
    *   [build.simple (⭐30)](https://github.com/gnl/build.simple)
*   [clojurephant (⭐170)](https://github.com/clojurephant/clojurephant) (Gradle plugin)
*   [shadow-cljs (⭐2.2k)](https://github.com/thheller/shadow-cljs) (Clojurescript)

## Version Control Management

*Code utilities for interacting with VCS software*

*   [clj-jgit (⭐242)](https://github.com/clj-jgit/clj-jgit)

## Date and Time

*Libraries for working with dates and times.*

*   [clj-time (⭐738)](https://github.com/clj-time/clj-time)
*   [clojure.java-time (⭐446)](https://github.com/dm3/clojure.java-time) - Java 8 Date-Time API
*   [timewords (⭐28)](https://github.com/tokenmill/timewords)
*   [tick (⭐570)](https://github.com/juxt/tick): Clojure(Script) library, intended as replacement for clj-time

## GUI

*   [seesaw (⭐1.4k)](https://github.com/daveray/seesaw)
*   [trikl (⭐143)](https://github.com/lambdaisland/trikl)
*   [fx-clj (⭐106)](https://github.com/aaronc/fx-clj)

## Audio

*   [Overtone](http://overtone.github.io/)
*   [Alda (⭐5.5k)](https://github.com/alda-lang/alda)

## HTTP

*Libraries for working with HTTP.*

*   [clj-http (⭐1.7k)](https://github.com/dakrone/clj-http) :  Apache HttpComponents client wrapper
*   [http-kit (⭐2.4k)](https://github.com/http-kit/http-kit) : Simple, high-performance event-driven HTTP client and server
*   [ring (⭐3.7k)](https://github.com/ring-clojure/ring) : HTTP server abstraction
*   [kvlt (⭐70)](https://github.com/nervous-systems/kvlt) : Uniform, asychronous client interface for HTTP across JVM / Node / browsers
*   [aleph (⭐2.5k)](https://github.com/clj-commons/aleph) : Async client/server based on Netty, with defaults for HTTP, TCP and UDP
*   [hato (⭐348)](https://github.com/gnarroway/hato) : An HTTP client for Clojure, wrapping JDK 11's HttpClient

## Database

*Databases and database client libraries*

*   [Datomic](http://www.datomic.com/)
*   [xtdb (⭐2.4k)](https://github.com/xtdb/xtdb): bitemporal database for SQL, Datalog & graph queries
*   [Datahike (⭐1.6k)](https://github.com/replikativ/datahike)
*   [Datascript (⭐5.3k)](https://github.com/tonsky/datascript)
*   [Datalevin (⭐980)](https://github.com/juji-io/datalevin)
*   [next.jdbc (⭐705)](https://github.com/seancorfield/next-jdbc)
*   [clojure.java.jdbc (⭐708)](https://github.com/clojure/java.jdbc)
*   [clojure.jdbc (⭐105)](https://github.com/funcool/clojure.jdbc)
*   [cravendb (⭐61)](https://github.com/robashton/cravendb)
*   [Monger](http://clojuremongodb.info/): for MongoDB
*   [Monglorious](https://baumandm.github.io/monglorious/): for MongoDB
*   [clj-rethinkdb (⭐203)](https://github.com/apa512/clj-rethinkdb): for RethinkDB
*   [Revise (⭐146)](https://github.com/bitemyapp/revise): for RethinkDB
*   [Spandex (⭐251)](https://github.com/mpenet/spandex): for ElasticSearch
*   [Elastisch](http://clojureelasticsearch.info/): for ElasticSearch
*   [neocons](http://clojureneo4j.info/): for Neo4j
*   [Alia (⭐242)](https://github.com/mpenet/alia): for Cassandra
*   [aerospike-clj (⭐29)](https://github.com/AppsFlyer/aerospike-clj): for Aerospike

## Connection pools

*Database connection pools*

*   [hikari-cp (⭐405)](https://github.com/tomekw/hikari-cp)
*   [metabase/connection-pool (⭐14)](https://github.com/metabase/connection-pool)

## Structural Migrations

*Keeps database and others in sync*

*   [Lobos (⭐266)](https://github.com/budu/lobos)
*   [Ragtime (⭐588)](https://github.com/weavejester/ragtime)
*   [Joplin (⭐312)](https://github.com/juxt/joplin)
*   [Migratus (⭐617)](https://github.com/yogthos/migratus)
*   [Drift (⭐121)](https://github.com/macourtney/drift)

## Redis

*   [carmine (⭐1.1k)](https://github.com/ptaoussanis/carmine)
*   [celtuce (⭐48)](https://github.com/lerouxrgd/celtuce)

## JSON

*   [cheshire (⭐1.5k)](https://github.com/dakrone/cheshire)
*   [jsonista (⭐391)](https://github.com/metosin/jsonista)

## Protocol Buffers and gRPC

*   [pronto (⭐100)](https://github.com/AppsFlyer/pronto)
*   [lein-protodeps (⭐25)](https://github.com/AppsFlyer/lein-protodeps)

## Database Cli

## ORM and SQL generation

*DSL for SQL generation.*

*   [Walkable (⭐438)](https://github.com/walkable-server/walkable)
*   [Korma (⭐1.5k)](https://github.com/korma/Korma)
*   [Specql (⭐127)](https://github.com/tatut/specql/)
*   [stch-library/sql (⭐40)](https://github.com/stch-library/sql)
*   [sqlingvo (⭐208)](https://github.com/r0man/sqlingvo)
*   [sqlium (⭐26)](https://github.com/TheLadders/sqlium/)
*   [honeysql (⭐1.7k)](https://github.com/jkk/honeysql)
*   [Toucan (⭐572)](https://github.com/metabase/toucan)

## Security

*Authentication, authorization and other security related libraries.*

*   [Buddy (⭐824)](https://github.com/funcool/buddy)
*   [caesium (⭐174)](https://github.com/lvh/caesium) (libsodium bindings)
*   [Friend (⭐1.2k)](https://github.com/cemerick/friend)
*   [secrets.clj (⭐88)](https://github.com/lk-geimfari/secrets.clj)
*   [bolt (⭐123)](https://github.com/juxt/bolt)

## RESTful API

*Libraries for developing RESTful APIs.*

*   [Liberator](http://clojure-liberator.github.io/liberator/)
*   [Compojure-api (⭐1.1k)](https://github.com/metosin/compojure-api)
*   [Friboo (⭐117)](https://github.com/zalando/friboo)
*   [yada (⭐729)](https://github.com/juxt/yada)
*   [router (⭐79)](https://github.com/darkleaf/router)
*   [reitit (⭐1.4k)](https://github.com/metosin/reitit)

## GraphQL API

*Libraries for developing GraphQL APIs.*

*   [Lacinia](https://lacinia.readthedocs.io/en/latest/)

## Emails

*   [postal (⭐578)](https://github.com/drewr/postal)

## HTML Manipulation

*Libraries for working with HTML.*

*   [Enlive (⭐1.6k)](https://github.com/cgrand/enlive/wiki)
*   [hiccup (⭐2.6k)](https://github.com/weavejester/hiccup)
*   [clostache (⭐317)](https://github.com/fhd/clostache)
*   [selmer (⭐945)](https://github.com/yogthos/Selmer)

## Data Validation

*Libraries for validating data.*

*   [Validateur](http://clojurevalidations.info/)
*   [Prismatic's schema (⭐2.4k)](https://github.com/plumatic/schema)
*   [Bouncer (⭐359)](https://github.com/leonardoborges/bouncer)
*   [clova (⭐14)](https://github.com/markwoodhall/clova)
*   [Orchestra (⭐617)](https://github.com/jeaye/orchestra)
*   [struct (⭐119)](https://github.com/funcool/struct)
*   [domaintypes (⭐6)](https://github.com/friemen/domaintypes)

## Type System

*Optional type system for Clojure*

*   [core.typed (⭐1.3k)](https://github.com/clojure/core.typed)

## Pattern Matching

*   [core.match (⭐1.2k)](https://github.com/clojure/core.match)
*   [defun (⭐462)](https://github.com/killme2008/defun)
*   [cats.match (⭐51)](https://github.com/zalando/cats.match)
*   [Akar (⭐174)](https://github.com/missingfaktor/akar)
*   [Meander (⭐891)](https://github.com/noprompt/meander)
*   [Verbal-Exprejon (⭐93)](https://github.com/WeshGuillaume/Verbal-Exprejon)

## Async processing

*   [core.async (⭐1.9k)](https://github.com/clojure/core.async/)
*   [pulsar (⭐903)](https://github.com/puniverse/pulsar)
*   [manifold (⭐997)](https://github.com/ztellman/manifold)
*   [goose (⭐233)](https://github.com/nilenso/goose)

## Monads

*   [cats (⭐939)](https://github.com/funcool/cats)
*   [algo.monads (⭐442)](https://github.com/clojure/algo.monads)
*   [Fluokitten (⭐451)](https://github.com/uncomplicate/fluokitten)

## WebSocket

*   [Chord (⭐436)](https://github.com/jarohen/chord)
*   [Sente (⭐1.7k)](https://github.com/ptaoussanis/sente)
*   [aleph (⭐2.5k)](https://github.com/ztellman/aleph)

## Testing

*   [Expectations (⭐395)](https://github.com/clojure-expectations/expectations)
*   [Midje (⭐1.7k)](https://github.com/marick/Midje)
*   [test-doubles (⭐36)](https://github.com/GreenPowerMonitor/test-doubles)
*   [kaocha (⭐760)](https://github.com/lambdaisland/kaocha)
*   [StateFlow (⭐291)](https://github.com/nubank/state-flow)
*   [Datest (⭐7)](https://github.com/amokfa/datest)

## Webdriver automation

*   [Etaoin (⭐883)](https://github.com/igrishaev/etaoin)

## Code Analysis and Linter

*   [Slamhound (⭐458)](https://github.com/technomancy/slamhound)
*   [eastwood (⭐1.1k)](https://github.com/jonase/eastwood)
*   [kibit (⭐1.7k)](https://github.com/jonase/kibit)
*   [yagni (⭐218)](https://github.com/venantius/yagni)
*   [lein-bikeshed (⭐177)](https://github.com/dakrone/lein-bikeshed)
*   [spectrum (⭐592)](https://github.com/arohner/spectrum)
*   [cloverage (⭐500)](https://github.com/cloverage/cloverage)
*   [clj-kondo (⭐1.6k)](https://github.com/borkdude/clj-kondo)
*   [splint (⭐71)](https://github.com/NoahTheDuke/splint)

## Science and Data Analysis

*Libraries, extended REPLs, and other tools for scientific and statistical data
anylysis and visualization.*

*   [Incanter (⭐2.2k)](https://github.com/incanter/incanter)
*   [Cascalog](http://cascalog.org/)
*   [Onyx (⭐2k)](https://github.com/onyx-platform/onyx)
*   [sparklling (⭐441)](https://github.com/gorillalabs/sparkling)
*   [flambo (⭐607)](https://github.com/yieldbot/flambo)
*   [Neanderthal (⭐1k)](https://github.com/uncomplicate/neanderthal)
*   [Streaming Histograms (⭐152)](https://github.com/bigmlcom/histogram)
*   [Gorilla REPL](http://gorilla-repl.org/)
*   [Bayadera - Bayesian Data Analysis on the GPU (⭐360)](https://github.com/uncomplicate/bayadera)
*   [ClojureCUDA (⭐172)](https://github.com/uncomplicate/clojurecuda)
*   [Neanderthal - fast matrix and linear algebra (⭐1k)](https://github.com/uncomplicate/neanderthal)
*   [ClojureCL - parallel computations with OpenCL (⭐276)](https://github.com/uncomplicate/clojurecl)
*   [Loom - graph library for Clojure (⭐873)](https://github.com/aysylu/loom)

## Machine Learning

*   [neanderthal (⭐1k)](https://github.com/uncomplicate/neanderthal): fast matrix library
*   [clojurecuda (⭐172)](https://github.com/uncomplicate/clojurecuda)
*   [clojurecl (⭐276)](https://github.com/uncomplicate/clojurecl)
*   [bayadera (⭐360)](https://github.com/uncomplicate/bayadera): bayesian data analysis on the GPU
*   [cortex (⭐1.3k)](https://github.com/originrose/cortex)
*   [Flare (⭐284)](https://github.com/aria42/flare)
*   [MXNet - Clojure API](https://mxnet.apache.org/versions/1.7.0/api/clojure)
*   [clj-bigml (⭐49)](https://github.com/bigmlcom/clj-bigml)
*   [Deeplearning4j (⭐13k)](https://github.com/deeplearning4j/deeplearning4j)
*   [Enclog (⭐136)](https://github.com/jimpil/enclog)
*   [lambda-ml (⭐75)](https://github.com/cloudkj/lambda-ml)
*   [clojure-tensorflow (⭐110)](https://github.com/kieranbrowne/clojure-tensorflow)
*   [dl4clj (deeplearning4j to clojure) (⭐99)](https://github.com/yetanalytics/dl4clj)
*   [Anglican](https://probprog.github.io/anglican/)
*   [clj-ml (⭐148)](https://github.com/antoniogarrote/clj-ml)
*   [Clatern (⭐67)](https://github.com/rinuboney/clatern)
*   [k9 (⭐104)](https://github.com/gigasquid/k9)
*   [Statistiker (⭐63)](https://github.com/clojurewerkz/statistiker)
*   [Synaptic (⭐88)](https://github.com/japonophile/synaptic)
*   [Infer (⭐176)](https://github.com/aria42/infer)
*   [clj-synapses (⭐1)](https://github.com/mrdimosthenis/clj-synapses)
*   [scicloj.ml (⭐190)](https://github.com/scicloj/scicloj.ml)

## Computer Vision

*   [origami (⭐112)](https://github.com/hellonico/origami): OpenCV 4 wrapper
*   [clj-tesseract (⭐55)](https://github.com/antoniogarrote/clj-tesseract)
*   [vision](http://nakkaya.com/vision.html)

## Text Processing

*   [clojure-opennlp (⭐745)](https://github.com/dakrone/clojure-opennlp)
*   [postagga (⭐157)](https://github.com/turbopape/postagga)
*   [beagle (⭐51)](https://github.com/tokenmill/beagle)
*   [lmgrep (⭐188)](https://github.com/dainiusjocas/lucene-grep)

## Parsing

*   [Instaparse (⭐2.7k)](https://github.com/Engelberg/instaparse)
*   [kern (⭐234)](https://github.com/blancas/kern)
*   [duckling (⭐1.3k)](https://github.com/wit-ai/duckling)
*   [buran (⭐30)](https://github.com/alekseysotnikov/buran) - RSS/Atom feed consumer and producer

## Exceptions and Error Handling

*   [Ex (⭐17)](https://github.com/mpenet/ex)
*   [Perseverance (⭐178)](https://github.com/grammarly/perseverance)
*   [Dire (⭐482)](https://github.com/MichaelDrogalis/dire)

## Rule-based Programming

*   [O'Doyle Rules (⭐505)](https://github.com/oakes/odoyle-rules)
*   [Clara Rules (⭐1.2k)](https://github.com/cerner/clara-rules)
*   [Arete (⭐15)](https://github.com/yipeeio/arete)

## Editor Plugins

*   [Calva (VSCode) (⭐1.3k)](https://github.com/BetterThanTomorrow/calva)
*   [clojure-lsp (multiple editors) (⭐1.1k)](https://github.com/clojure-lsp/clojure-lsp)
*   [CIDER (Emacs) (⭐3.5k)](https://github.com/clojure-emacs/cider)
*   [smartparens (Emacs) (⭐1.8k)](https://github.com/Fuco1/smartparens)
*   [rainbow-delimiters (Emacs) (⭐640)](https://github.com/Fanael/rainbow-delimiters)
*   [aggressive-indent (Emacs) (⭐824)](https://github.com/Malabarba/aggressive-indent-mode)
*   [Conjure (Neovim) (⭐1.5k)](https://github.com/Olical/conjure)
*   [vim-cljfmt (Vim) (⭐152)](https://github.com/venantius/vim-cljfmt)
*   [vim-eastwood (Vim) (⭐84)](https://github.com/venantius/vim-eastwood)
*   [vim-fireplace (Vim) (⭐1.7k)](https://github.com/tpope/vim-fireplace)
*   [vim-redl (Vim) (⭐107)](https://github.com/dgrnbrg/vim-redl)
*   [vim-leiningen (Vim) (⭐197)](https://github.com/tpope/vim-salve)
*   [rainbow\_parentheses.vim (Vim) (⭐377)](https://github.com/junegunn/rainbow_parentheses.vim)
*   [vim-iced (Vim) (⭐505)](https://github.com/liquidz/vim-iced)
*   [Cursive (IntelliJ)](https://cursive-ide.com/)
*   [proto-repl (Atom)](https://atom.io/packages/proto-repl)
*   [Parinfer (multiple editors)](http://shaunlebron.github.io/parinfer/)
*   [Bracket Pair Colorizer (VSCode)](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
*   [clojureVSCode (VSCode) (⭐207)](https://github.com/avli/clojureVSCode)
*   [Notepad++ (⭐20)](https://github.com/linpengcheng/ClojureBoxNpp): modified config files of Lisp

## Documentation

*Utilities and libraries for (non-LP) code and project documentation*

*   [codox (⭐657)](https://github.com/weavejester/codox)

## Literate Programming

*   [marginalia (⭐798)](https://github.com/gdeer81/marginalia)
*   [klipse (⭐3.1k)](https://github.com/viebel/klipse)

## Archives and Compression

*   [swindon (java.util.zip wrapper) (⭐2)](https://github.com/AeroNotix/swindon)

## Miscellaneous

*   [potemkin (⭐561)](https://github.com/ztellman/potemkin) - reexport vars in another ns / act like a clojure map
*   [clj-tuple (⭐179)](https://github.com/ztellman/clj-tuple)
*   [slingshot (⭐639)](https://github.com/scgilardi/slingshot)
*   [virgil (⭐274)](https://github.com/ztellman/virgil)
*   [javastar (⭐64)](https://github.com/tailrecursion/javastar)
*   [riddley (⭐193)](https://github.com/ztellman/riddley)
*   [kezban (⭐41)](https://github.com/ertugrulcetin/kezban)
*   [clj-grpc (⭐12)](https://github.com/otwieracz/clj-grpc)

## Debugging

*   [flow-storm-debugger (⭐591)](https://github.com/flow-storm/flow-storm-debugger)
*   [playback (⭐80)](https://github.com/gnl/playback)
*   [tools.trace (⭐353)](https://github.com/clojure/tools.trace)
*   [debugger (⭐263)](https://github.com/razum2um/clj-debugger)
*   [debug-repl (⭐150)](https://github.com/GeorgeJahad/debug-repl)
*   [ritz (⭐320)](https://github.com/pallet/ritz)
*   [redl (⭐33)](https://github.com/dgrnbrg/redl)
*   [limit-break (⭐26)](https://github.com/technomancy/limit-break)
*   [spyscope (⭐575)](https://github.com/dgrnbrg/spyscope)
*   [aprint (⭐129)](https://github.com/razum2um/aprint)
*   [packed-printer (⭐37)](https://github.com/cgrand/packed-printer)
*   [pretty (⭐580)](https://github.com/AvisoNovate/pretty)
*   [prone (⭐510)](https://github.com/magnars/prone)
*   [figwheel (⭐2.9k)](https://github.com/bhauman/lein-figwheel)
*   [ultra (⭐1.2k)](https://github.com/venantius/ultra)
*   [mate-clj (⭐59)](https://github.com/AppsFlyer/mate-clj)
*   [scope-capture (⭐546)](https://github.com/vvvvalvalval/scope-capture)

## CI

*   [lambdacd (⭐673)](https://github.com/flosell/lambdacd)

## Project Management

*   [milestones (⭐114)](https://github.com/turbopape/milestones)

## Terminal UI

*   [clojure-lanterna (⭐214)](https://github.com/MultiMUD/clojure-lanterna)
*   [triki (⭐143)](https://github.com/lambdaisland/trikl)
*   [zaffre (⭐101)](https://github.com/aaron-santos/zaffre)
*   [closh (⭐1.6k)](https://github.com/dundalek/closh)
*   [piotr-yuxuan/malli-cli (⭐48)](https://github.com/piotr-yuxuan/malli-cli)

## Graphviz

*   [zipper-viz (⭐8)](https://github.com/lambdaisland/zipper-viz)
*   [dorothy (⭐240)](https://github.com/daveray/dorothy)
*   [viz.cljc (⭐31)](https://github.com/jebberjeb/viz.cljc)
*   [fsmviz (⭐50)](https://github.com/jebberjeb/fsmviz)
*   [rhizome (⭐446)](https://github.com/ztellman/rhizome)
*   [re-frame-flow (⭐145)](https://github.com/ertugrulcetin/re-frame-flow) - Graph based visualization tool for re-frame event chains (ClojureScript)

## Game Development

*   [jme-clj (⭐128)](https://github.com/ertugrulcetin/jme-clj) - A Clojure 3D Game Engine (Wrapper), Powered by jMonkeyEngine
*   [play-cljc (⭐509)](https://github.com/oakes/play-cljc) - A Clojure and ClojureScript game library

## Guides

*   [The Clojure Style Guide (⭐4k)](https://github.com/bbatsov/clojure-style-guide)
*   [Clojure Distilled](http://yogthos.github.io/ClojureDistilled.html)
*   [clojure-cookbook (⭐2.6k)](https://github.com/clojure-cookbook/clojure-cookbook)
*   [A Brief Beginner's Guide To Clojure](http://www.unexpected-vortices.com/clojure/brief-beginners-guide/index.html)
*   [Clojure for the Brave and True](http://www.braveclojure.com/)
*   [Clojure from the ground up](https://aphyr.com/tags/Clojure-from-the-ground-up)
*   [Error message catalog (⭐446)](https://github.com/yogthos/clojure-error-message-catalog)
*   [Clojure by Example](https://kimh.github.io/clojure-by-example/)

## Video tutorials

### YouTube

*   [Misophistful's channel](https://www.youtube.com/user/Misophistful/videos): Understand concepts such as list comprehension, threading macros, generative testing, destructuring, core.match and introductions to Light Table, Datomic and Game development with Clojure
*   [Fred Overflow's channel](https://www.youtube.com/channel/UC9m7D4XKPJqTPCLSBym3BCg/search?query=Clojure): Introductions to Functional programming and TDD with Clojure
*   [Clojure Pills screencast](https://www.youtube.com/channel/UCH0CkLvbv6yEyrUnw9qujpQ/videos): Introduction to Clojure one function at a time
*   [Clojure Pills screencast](https://www.youtube.com/c/onthecodeagain/videos): Fun and beginner friendly content related to the overall clojure ecosystem
*   [Data persistance with Postgres, Clojure and JDBC](https://www.youtube.com/channel/UCrwwOZ4h2FQhAdTMfjyQfQA/playlists)
*   [Clojure Tutorials by Timothy Baldridge](https://www.youtube.com/channel/UC6yONKYeoE2P3bsahDtsimg/videos): More advanced videos on core.async, transducers, transients, logic programming and a "Function of the day" series.

## Websites

*   [Clojure](http://clojure.org/)
*   [Clojure Slack](http://clojurians.net/)
*   [clojuredocs](http://clojuredocs.org)
*   [clojure-doc](http://clojure-doc.org/)
*   [The Clojure Toolbox](http://www.clojure-toolbox.com/)
*   [ZEEF/Clojure](https://clojure.zeef.com/vlad.bokov)

## Twitter

*   [oss\_clj](https://twitter.com/oss_clj)

## Exercises

*   [rich4clojure (⭐182)](https://github.com/PEZ/rich4clojure)
*   [Wonderland Clojure Katas (⭐855)](https://github.com/gigasquid/wonderland-clojure-katas)
*   [Clojure Koans](http://clojurekoans.com)
*   [exercism.io](http://exercism.io/languages/clojure)
*   [Codewars](https://www.codewars.com/kata/search/clojure)

