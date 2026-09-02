# Awesome Streaming Overview

a curated list of awesome streaming frameworks, applications, etc

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/manuzhang/awesome-streaming/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 manuzhang/awesome-streaming](https://github.com/manuzhang/awesome-streaming) · ⭐ 3K · 🏷️ Big Data

[ [Daily](/content/manuzhang/awesome-streaming/README.md) / [Weekly](/content/manuzhang/awesome-streaming/week/README.md) / Overview ]

---

## Awesome Streaming  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://github.com/manuzhang/awesome-streaming/workflows/build/badge.svg)](https://github.com/manuzhang/awesome-streaming/actions)

A curated list of awesome [streaming (stream processing)](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) frameworks, applications, readings and other resources. Inspired by [other awesome projects (⭐497k)](https://github.com/sindresorhus/awesome).

## Website

<https://manuzhang.github.io/awesome-streaming/> is a more dynamic website where you can find **updates** of the awesome projects here.

## Table of Contents

*   [Engines and Platforms](#engines-and-platforms)
*   [Libraries, SDKs, and Programming Models](#libraries-sdks-and-programming-models)
*   [Data Integration and Pipelines](#data-integration-and-pipelines)
*   [Applications and Tools](#applications-and-tools)
*   [Managed and Closed Source](#managed-and-closed-source)
*   [Benchmarks](#benchmarks)
*   [Readings](#readings)

### Engines and Platforms

*   [Aeron (⭐8.8k)](https://github.com/aeron-io/aeron) <sub>![Java/C++][language-java-cpp]</sub> - Reliable UDP unicast, multicast, and IPC message transport.
*   [Apache Apex (⭐350)](https://github.com/apache/apex-core) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Unified platform for big data stream and batch processing.
*   [Apache Flink (⭐26k)](https://github.com/apache/flink) <sub>![Java][language-java]</sub> - Distributed engine for stateful computation over bounded and unbounded data streams.
*   [Apache Heron (⭐3.6k)](https://github.com/apache/incubator-heron) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Retired distributed, fault-tolerant stream processing engine originally developed at Twitter.
*   [Apache Kafka (⭐34k)](https://github.com/apache/kafka) <sub>![Java/Scala][language-java-scala]</sub> - Distributed event streaming platform for high-performance data pipelines and applications.
*   [Apache Pulsar (⭐15k)](https://github.com/apache/pulsar) <sub>![Java][language-java]</sub> - Distributed pub-sub messaging and event streaming platform.
*   [Apache RocketMQ (⭐23k)](https://github.com/apache/rocketmq) <sub>![Java][language-java]</sub> - Cloud-native messaging and streaming platform for event-driven applications.
*   [Apache Samza (⭐846)](https://github.com/apache/samza) <sub>![Java/Scala][language-java-scala]</sub> - Distributed stream processing framework built on Apache Kafka with standalone and YARN deployment options.
*   [Apache Spark Streaming (⭐44k)](https://github.com/apache/spark) <sub>![Scala/Java/Python/R][language-scala-java-python-r]</sub> - Scalable, fault-tolerant stream processing on Apache Spark.
*   [Apache Storm (⭐6.7k)](https://github.com/apache/storm) <sub>![Java][language-java]</sub> - Distributed real-time computation system for reliably processing unbounded streams of data.
*   [Apache StreamPipes (⭐744)](https://github.com/apache/streampipes) <sub>![Java/Python/TypeScript][language-java-python-typescript]</sub> - Self-service industrial IoT platform for connecting, analyzing, and exploring data streams.
*   [ArkFlow (⭐1.3k)](https://github.com/arkflow-rs/arkflow) <sub>![Rust][language-rust]</sub> - High-performance stream processing engine with pluggable sources, processors, and sinks.
*   [Arroyo (⭐5k)](https://github.com/ArroyoSystems/arroyo) <sub>![Rust][language-rust]</sub> - Distributed stream processing engine for stateful SQL computations over unbounded data.
*   [AthenaX (⭐1.2k)](https://github.com/uber-archive/AthenaX) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Uber's retired SQL-based streaming analytics platform.
*   [AutoMQ (⭐11k)](https://github.com/AutoMQ/automq) <sub>![Java/Scala][language-java-scala]</sub> - Diskless Kafka-compatible streaming platform that stores durable data in object storage.
*   [Bytewax (⭐2k)](https://github.com/bytewax/bytewax) <sub>![Python/Rust][language-python-rust]</sub> - Community-maintained Python framework with a Rust-based distributed engine for stateful stream processing.
*   [eKuiper (⭐1.7k)](https://github.com/lf-edge/ekuiper) <sub>![Go][language-go]</sub> - Lightweight data stream processing engine for resource-constrained IoT edge devices.
*   [Esper (⭐875)](https://github.com/espertechinc/esper) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Complex event processing, Streaming SQL, and event series analysis engine.
*   [Fluvio (⭐5.2k)](https://github.com/fluvio-community/fluvio) <sub>![Rust/WASM][language-rust-wasm]</sub> - Composable, stateful data streaming system with programmable in-line computation.
*   [Gazette (⭐796)](https://github.com/gazette/core) <sub>![Go][language-go]</sub> - Cloud-storage-backed streaming infrastructure that combines SQL, batch, and millisecond-latency stream processing.
*   [Gearpump (⭐755)](https://github.com/gearpump/gearpump) <sub>![Scala][language-scala]</sub> - Lightweight real-time distributed streaming engine built on Akka.
*   [hailstorm (⭐94)](https://github.com/hailstorm-hs/hailstorm) <sub>![Archived][archived-badge]</sub> <sub>![Haskell][language-haskell]</sub> - Distributed stream processing with exactly-once semantics based on Storm.
*   [Hazelcast Jet (⭐1.1k)](https://github.com/hazelcast/hazelcast-jet) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Stream and batch processing engine whose development moved into Hazelcast Platform.
*   [HStreamDB (⭐722)](https://github.com/hstreamdb/hstream) <sub>![Haskell][language-haskell]</sub> - Cloud-native streaming database for IoT data storage and real-time processing.
*   [ksqlDB (⭐315)](https://github.com/confluentinc/ksql) <sub>![Java][language-java]</sub> - Source-available database purpose-built for stream processing applications.
*   [LaminarDB (⭐45)](https://github.com/laminardb/laminardb) <sub>![Rust][language-rust]</sub> - Embeddable streaming SQL engine built on Apache Arrow and DataFusion.
*   [LightSaber (⭐73)](https://github.com/lsds/LightSaber) <sub>![Archived][archived-badge]</sub> <sub>![C++][language-cpp]</sub> - Multi-core stream processing engine using code generation for window aggregation.
*   [LogDevice (⭐1.9k)](https://github.com/facebookarchive/LogDevice) <sub>![Archived][archived-badge]</sub> <sub>![C++][language-cpp]</sub> - Facebook's archived distributed storage system for sequential data.
*   [Maki Nage (⭐42)](https://github.com/maki-nage/makinage) <sub>![Archived][archived-badge]</sub> <sub>![Python][language-python]</sub> - Stream processing framework for data scientists based on Kafka and ReactiveX.
*   [Mantis (⭐1.5k)](https://github.com/Netflix/mantis) <sub>![Java][language-java]</sub> - Netflix platform for building real-time, operations-focused stream processing applications.
*   [Materialize](https://materialize.com) <sub>![Rust][language-rust]</sub> - Incremental SQL engine for maintaining continuously updated views over changing data.
*   [Metaq (⭐1.3k)](https://github.com/killme2008/Metamorphosis) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Taobao distributed messaging system.
*   [mupd8 (Muppet) (⭐128)](https://github.com/walmartlabs/mupd8) <sub>![Archived][archived-badge]</sub> <sub>![Scala/Java][language-scala-java]</sub> - MapReduce-style framework for processing fast-moving data streams.
*   [NATS Streaming (⭐2.5k)](https://github.com/nats-io/nats-streaming-server) <sub>![Archived][archived-badge]</sub> <sub>![Go][language-go]</sub> - Deprecated disk-backed messaging system superseded by NATS JetStream.
*   [NebulaStream (⭐95)](https://github.com/nebulastream/nebulastream) <sub>![C++][language-cpp]</sub> - Data management system for cloud-edge-sensor environments.
*   [NSQ (⭐26k)](https://github.com/nsqio/nsq) <sub>![Go][language-go]</sub> - Real-time distributed messaging platform designed to operate at scale.
*   [Numaflow (⭐2.8k)](https://github.com/numaproj/numaflow) <sub>![Rust/Go/TypeScript][language-rust-go-typescript]</sub> - Kubernetes-native, language-agnostic platform for scalable event-driven applications.
*   [Onyx (⭐2.1k)](https://github.com/onyx-platform/onyx) <sub>![Archived][archived-badge]</sub> <sub>![Clojure][language-clojure]</sub> - Distributed, masterless, fault-tolerant data processing platform.
*   [PipelineDB (⭐2.7k)](https://github.com/pipelinedb/pipelinedb) <sub>![Archived][archived-badge]</sub> <sub>![C][language-c]</sub> - Unmaintained PostgreSQL extension for continuous SQL aggregation over time-series data.
*   [Proton (⭐2.3k)](https://github.com/timeplus-io/proton) <sub>![C++][language-cpp]</sub> - Unified streaming and historical data analytics database powered by ClickHouse.
*   [Redpanda (⭐12k)](https://github.com/redpanda-data/redpanda) <sub>![C++][language-cpp]</sub> - Kafka API-compatible streaming data platform without ZooKeeper or a JVM.
*   [RisingWave (⭐9.3k)](https://github.com/risingwavelabs/risingwave) <sub>![Rust][language-rust]</sub> - PostgreSQL-compatible streaming database for event-driven applications, real-time ETL, and continuous analytics.
*   [S4 (⭐43)](https://github.com/apache/incubator-retired-s4) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Retired distributed platform for processing continuous unbounded data streams.
*   [SABER (⭐44)](https://github.com/lsds/Saber) <sub>![Archived][archived-badge]</sub> <sub>![Java/C][language-java-c]</sub> - Window-based hybrid CPU/GPU stream processing engine.
*   [Scramjet Cloud Platform (⭐71)](https://github.com/scramjetorg/transform-hub) <sub>![TypeScript/Python][language-typescript-python]</sub> - Distributed runtime for running and managing data processing programs on edge, server, and cloud infrastructure.
*   [SensorBee (⭐231)](https://github.com/sensorbee/sensorbee) <sub>![Archived][archived-badge]</sub> <sub>![Go][language-go]</sub> - Discontinued lightweight stream processing engine for IoT.
*   [Siddhi (⭐1.6k)](https://github.com/siddhi-io/siddhi) <sub>![Java][language-java]</sub> - Streaming SQL and complex event processing engine.
*   [SPQR (⭐30)](https://github.com/ottogroup/SPQR) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Dynamic framework for processing high-volume data streams through pipelines.
*   [SQLFlow (⭐792)](https://github.com/turbolytics/sql-flow) <sub>![Go/Python][language-go-python]</sub> - Stream processing engine that runs DuckDB SQL over Kafka, WebSocket, and webhook streams.
*   [Squall (⭐274)](https://github.com/epfldata/squall) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Online SQL query processing engine built on Apache Storm.
*   [StreamCQL (⭐0)](https://github.com/Zhiqiang-He/StreamCQL) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Storm-based continuous query language for real-time computation.
*   [Teknek (⭐10)](https://github.com/edwardcapriolo/teknek-core) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Stream processing platform with the interactive Stream Operator Language shell.
*   [Tigon (⭐284)](https://github.com/cdapio/tigon) <sub>![Archived][archived-badge]</sub> <sub>![C++/Java][language-cpp-java]</sub> - High-throughput real-time stream processing framework built on Hadoop and HBase.
*   [Trill (⭐1.3k)](https://github.com/microsoft/Trill) <sub>![Archived][archived-badge]</sub> <sub>![C#][language-csharp]</sub> - Single-node query processor for temporal and streaming data from Microsoft Research.
*   [Wally (⭐1.5k)](https://github.com/WallarooLabs/wally) <sub>![Archived][archived-badge]</sub> <sub>![Pony][language-pony]</sub> - Distributed stream processing framework formerly named Wallaroo.
*   [Wingfoil (⭐217)](https://github.com/wingfoil-io/wingfoil) <sub>![Rust/Python/TypeScript][language-rust-python-typescript]</sub> - Graph-based stream processing engine for latency-critical systems.

### Libraries, SDKs, and Programming Models

*   [Akka (⭐13k)](https://github.com/akka/akka-core) <sub>![Scala/Java][language-scala-java]</sub> - Toolkit and runtime for concurrent, distributed, resilient applications on the JVM.
*   [Akka Streams (⭐13k)](https://github.com/akka/akka-core) <sub>![Scala/Java][language-scala-java]</sub> - Reactive Streams implementation built on Akka actors.
*   [Apache Beam (⭐8.6k)](https://github.com/apache/beam) <sub>![Java/Python/Go][language-java-python-go]</sub> - Unified programming model and language-specific SDKs for batch and streaming data processing.
*   [Apache Edgent (⭐222)](https://github.com/apache/incubator-retired-edgent) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Retired programming model and runtime for streaming analytics on gateways and edge devices.
*   [Apache Kafka Streams (⭐34k)](https://github.com/apache/kafka) <sub>![Java][language-java]</sub> - Stream processing library included with Apache Kafka.
*   [Apache Pekko (⭐1.6k)](https://github.com/apache/pekko) <sub>![Scala/Java][language-scala-java]</sub> - Open-source toolkit for concurrent, distributed, resilient applications, forked from Akka 2.6.
*   [Apache SAMOA (⭐251)](https://github.com/apache/incubator-samoa) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Retired distributed streaming machine learning framework.
*   [Apache StormCrawler (⭐994)](https://github.com/apache/stormcrawler) <sub>![Java][language-java]</sub> - Scalable web crawler SDK based on Apache Storm.
*   [CapyMOA (⭐144)](https://github.com/adaptive-machine-learning/CapyMOA) <sub>![Python/Java][language-python-java]</sub> - Machine learning library for data streams with a Python API and MOA backend.
*   [coast (⭐60)](https://github.com/bkirwi/coast) <sub>![Archived][archived-badge]</sub> <sub>![Scala][language-scala]</sub> - DSL that builds exactly-once dataflow graphs on top of Apache Samza.
*   [Daggy (⭐165)](https://github.com/synacker/daggy) <sub>![C++][language-cpp]</sub> - Utility and developer library for aggregating and capturing data streams.
*   [DataSketches (⭐959)](https://github.com/apache/datasketches-java) <sub>![Java][language-java]</sub> - Apache library of stochastic streaming algorithms known as sketches.
*   [FastStream (⭐5.3k)](https://github.com/ag2ai/faststream) <sub>![Python][language-python]</sub> - Asynchronous framework for building event-driven applications with Kafka, RabbitMQ, NATS, Redis, and MQTT.
*   [Faust (⭐6.8k)](https://github.com/robinhood/faust) <sub>![Archived][archived-badge]</sub> <sub>![Python][language-python]</sub> - Deprecated Python stream processing library inspired by Kafka Streams.
*   [FS2 (⭐2.5k)](https://github.com/typelevel/fs2) <sub>![Scala][language-scala]</sub> - Compositional streaming I/O library for Scala.
*   [Jubatus (⭐707)](https://github.com/jubatus/jubatus) <sub>![Archived][archived-badge]</sub> <sub>![C++][language-cpp]</sub> - Distributed processing framework and library for online machine learning.
*   [Kzmlabs StateFun Actors (⭐13)](https://github.com/kzmlabs/flink-statefun) <sub>![Java][language-java]</sub> - Stateful actors on Apache Flink 2.x with durable per-key state, exactly-once messaging, and Kafka and Kinesis I/O.
*   [MediaPipe (⭐37k)](https://github.com/google-ai-edge/mediapipe) <sub>![C++/Python/Java/TypeScript][language-cpp-python-java-typescript]</sub> - Cross-platform, customizable ML solutions for live and streaming media.
*   [Monix (⭐1.9k)](https://github.com/monix/monix) <sub>![Scala][language-scala]</sub> - High-performance Scala and Scala.js library for asynchronous and event-based programs.
*   [Numalogic (⭐172)](https://github.com/numaproj/numalogic) <sub>![Python][language-python]</sub> - Collection of machine learning models and tools for anomaly detection and forecasting on operational time-series data.
*   [Pulsar (⭐1.8k)](https://github.com/quantmind/pulsar) <sub>![Archived][archived-badge]</sub> <sub>![Python][language-python]</sub> - Actor-based event-driven concurrency framework for Python.
*   [Quix Streams (⭐1.6k)](https://github.com/quixio/quix-streams) <sub>![Python][language-python]</sub> - Python framework for real-time data engineering, analytics, and machine learning on Apache Kafka.
*   [River (⭐5.9k)](https://github.com/online-ml/river) <sub>![Python][language-python]</sub> - Online machine learning library for Python.
*   [samza-luwak (⭐100)](https://github.com/romseygeek/samza-luwak) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Integration of Apache Samza with the Luwak stored-query engine for full-text stream search.
*   [Scramjet C++ (⭐4)](https://github.com/scramjetorg/framework-cpp) <sub>![Archived][archived-badge]</sub> <sub>![C++][language-cpp]</sub> - Reactive stream programming framework for C++.
*   [Scramjet Python (⭐35)](https://github.com/scramjetorg/framework-python) <sub>![Archived][archived-badge]</sub> <sub>![Python][language-python]</sub> - Reactive stream programming framework for Python.
*   [Scramjet TypeScript (⭐41)](https://github.com/scramjetorg/framework-js) <sub>![Archived][archived-badge]</sub> <sub>![TypeScript][language-typescript]</sub> - Reactive stream programming framework for asynchronous JavaScript and TypeScript applications.
*   [StormCV (⭐174)](https://github.com/sensorstorm/StormCV) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Computer vision operations and data models for Apache Storm.
*   [Stream Ops (⭐50)](https://github.com/nanosai/stream-ops-java) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Embeddable data streaming engine and stream processing API for Java.
*   [streamDM (⭐496)](https://github.com/huawei-noah/streamDM) <sub>![Archived][archived-badge]</sub> <sub>![Scala][language-scala]</sub> - Huawei library for mining data streams with Spark Streaming.
*   [Streamiz.Kafka.Net (⭐543)](https://github.com/LGouellec/streamiz) <sub>![C#][language-csharp]</sub> - .NET stream processing library for Apache Kafka.
*   [Streamparse (⭐1.5k)](https://github.com/pystorm/streamparse) <sub>![Archived][archived-badge]</sub> <sub>![Python][language-python]</sub> - Python API, command-line tools, and topology DSL for Apache Storm.
*   [Streamz (⭐1.3k)](https://github.com/python-streamz/streamz) <sub>![Python][language-python]</sub> - Library for building continuous data pipelines with branching, joining, flow control, and back pressure.
*   [Summingbird (⭐2.1k)](https://github.com/twitter/summingbird) <sub>![Archived][archived-badge]</sub> <sub>![Scala][language-scala]</sub> - Retired library for expressing streaming MapReduce computations over Storm and Scalding.
*   [Swave (⭐173)](https://github.com/sirthias/swave) <sub>![Archived][archived-badge]</sub> <sub>![Scala][language-scala]</sub> - Lightweight Reactive Streams infrastructure toolkit for Scala.
*   [Tributary (⭐465)](https://github.com/1kbgz/tributary) <sub>![Python][language-python]</sub> - Python library for constructing synchronous, reactive, and lazy dataflow graphs.
*   [trident-ml (⭐383)](https://github.com/pmerienne/trident-ml) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Online machine learning library based on Apache Storm Trident.
*   [WindFlow (⭐88)](https://github.com/ParaGroup/WindFlow) <sub>![C++][language-cpp]</sub> - Data stream processing parallel library for multi-core CPUs and GPUs.
*   [Yurita (⭐109)](https://github.com/paypal/yurita) <sub>![Archived][archived-badge]</sub> <sub>![Scala][language-scala]</sub> - PayPal anomaly detection framework built on Spark Structured Streaming.

### Data Integration and Pipelines

*   [Apache Flume (⭐2.6k)](https://github.com/apache/logging-flume) <sub>![Java][language-java]</sub> - Distributed service for collecting, aggregating, and moving large amounts of log-like data.
*   [Brooklin (⭐966)](https://github.com/linkedin/Brooklin) <sub>![Java][language-java]</sub> - Distributed system for reliable nearline data streaming between heterogeneous systems at scale.
*   [Bruin (⭐1.7k)](https://github.com/bruin-data/bruin) <sub>![Go][language-go]</sub> - End-to-end data pipeline tool combining ingestion, SQL and Python transformations, and data quality checks.
*   [Camus (⭐878)](https://github.com/LinkedInAttic/camus) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - LinkedIn's retired, previous-generation Kafka-to-HDFS pipeline.
*   [CocoIndex (⭐11k)](https://github.com/cocoindex-io/cocoindex) <sub>![Rust/Python][language-rust-python]</sub> - Incremental data transformation engine for continuously updated AI and agent workloads.
*   [Databus (⭐3.7k)](https://github.com/linkedin/databus) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - LinkedIn source-agnostic distributed change data capture system.
*   [faucet-stream (⭐7)](https://github.com/faucet-hq/faucet-stream) <sub>![Rust][language-rust]</sub> - Config-driven platform and embeddable library for ETL, CDC, and streaming data movement.
*   [inGestr (⭐3.9k)](https://github.com/bruin-data/ingestr) <sub>![Go/Python][language-go-python]</sub> - Command-line application and Python SDK for copying data between databases, SaaS applications, and data warehouses.
*   [Pathway (⭐62k)](https://github.com/pathwaycom/pathway) <sub>![Python/Rust][language-python-rust]</sub> - Python ETL framework for stream processing, real-time analytics, and AI data pipelines.
*   [Redpanda Connect (⭐8.7k)](https://github.com/redpanda-data/connect) <sub>![Go][language-go]</sub> - Declarative stream processor for moving, enriching, transforming, and filtering data between sources and sinks.
*   [RudderStack (⭐4.5k)](https://github.com/rudderlabs/rudder-server) <sub>![Go][language-go]</sub> - Developer-focused customer data platform for event streaming and cloud-to-warehouse data pipelines.
*   [Suro (⭐797)](https://github.com/Netflix/suro) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Netflix data pipeline for collecting, aggregating, and dispatching application events.
*   [yasdb (⭐4)](https://github.com/JayJamieson/yasdb) <sub>![Go][language-go]</sub> - Durable Streams protocol server backed by SlateDB object storage, with offset-based catch-up reads and SSE or long-poll tailing.

### Applications and Tools

*   [beava (⭐138)](https://github.com/beava-dev/beava) <sub>![Rust/Python][language-rust-python]</sub> - Single-binary feature server for querying fresh per-entity counters and aggregates without a message broker.
*   [Eventum (⭐63)](https://github.com/eventum-generator/eventum) <sub>![Python/TypeScript][language-python-typescript]</sub> - Data generation platform for producing synthetic event streams.
*   [javactrl-kafka (⭐18)](https://github.com/javactrl/javactrl-kafka) <sub>![Java][language-java]</sub> - Code-first distributed workflow engine for microservice orchestration and business process automation.
*   [Nussknacker (⭐742)](https://github.com/TouK/nussknacker) <sub>![Scala][language-scala]</sub> - Visual tool for defining and running real-time decision algorithms.
*   [straw (⭐103)](https://github.com/rwalk/straw) <sub>![Archived][archived-badge]</sub> <sub>![Python/Java][language-python-java]</sub> - Platform for real-time streaming search.
*   [StreamAlert (⭐2.9k)](https://github.com/airbnb/streamalert) <sub>![Archived][archived-badge]</sub> <sub>![Python][language-python]</sub> - Airbnb serverless framework for real-time security log analysis and alerting.
*   [Streamdal (⭐615)](https://github.com/streamdal/streamdal) <sub>![Archived][archived-badge]</sub> <sub>![TypeScript][language-typescript]</sub> - Code-native data privacy controls for detecting PII in application data flows.
*   [StreamFlow (⭐257)](https://github.com/lmco/streamflow) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Tool for building and monitoring stream processing workflows.
*   [StreamingBandit (⭐85)](https://github.com/Nth-iteration-labs/streamingbandit) <sub>![Python][language-python]</sub> - Web application for setting up and evaluating contextual multi-armed bandit experiments.
*   [Streamline (⭐167)](https://github.com/hortonworks/streamline) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Hortonworks visual stream analytics framework built around engines such as Apache Storm.
*   [Substation (⭐405)](https://github.com/brexhq/substation) <sub>![Go][language-go]</sub> - Toolkit for routing, normalizing, and enriching security event and audit logs.
*   [Turbine (⭐833)](https://github.com/Netflix/Turbine) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Netflix tool for aggregating Server-Sent Event JSON streams.
*   [Zilla (⭐1.7k)](https://github.com/aklivity/zilla) <sub>![Java][language-java]</sub> - Multi-protocol gateway for connecting applications, APIs, agents, and devices to event streams.

### Managed and Closed Source

*   [Amazon Kinesis Data Streams](https://aws.amazon.com/kinesis/data-streams/) - Fully managed service for ingesting and processing real-time data streams on AWS.
*   [Azure Stream Analytics](https://azure.microsoft.com/en-us/products/stream-analytics) <sub>![SQL][language-sql]</sub> - Fully managed service for serverless real-time analytics in the cloud and at the edge.
*   [Concord](https://www.slideshare.net/concord-io/may-2016-data-by-the-bay-concord-simple-flexible-stream-processing-on-apache-mesos) <sub>![Archived][archived-badge]</sub> <sub>![C++][language-cpp]</sub> - Historical distributed stream processing framework built on Apache Mesos.
*   [Google Cloud Dataflow](https://cloud.google.com/dataflow/) <sub>![Java/Python/Go][language-java-python-go]</sub> - Fully managed service for running Apache Beam batch and streaming pipelines.
*   [IBM Streams](https://www.ibm.com/support/pages/ibm-streams-life-cycle-guidance) <sub>![Archived][archived-badge]</sub> <sub>![Python/Java/Scala][language-python-java-scala]</sub> - Discontinued proprietary platform for distributed stream processing and real-time analytics.
*   [NVIDIA DeepStream SDK](https://developer.nvidia.com/deepstream-sdk) <sub>![C/C++/Python][language-c-cpp-python]</sub> - GStreamer-based toolkit with open-source components and proprietary NVIDIA libraries for real-time AI streaming analytics and multi-sensor processing.

### Benchmarks

*   [Flotilla (⭐238)](https://github.com/tylertreat/Flotilla) <sub>![Archived][archived-badge]</sub> <sub>![Go][language-go]</sub> - Automated message queue orchestration for scaled-up benchmarking.
*   [storm-perf-test (⭐75)](https://github.com/yahoo/storm-perf-test) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Apache Storm performance and stress test.
*   [streaming-benchmarks (⭐648)](https://github.com/yahoo/streaming-benchmarks) <sub>![Archived][archived-badge]</sub> <sub>![Java][language-java]</sub> - Benchmarks for low-latency stream processing systems including Storm, Spark, and Flink.

### Readings

1.  [In-Stream Big Data Processing](https://highlyscalable.wordpress.com/2013/08/20/in-stream-big-data-processing/)
2.  [The world beyond batch: Streaming 101](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) by Tyler Akidau.
3.  [Real Time Analytics: Algorithms and Systems (VLDB 2015)](https://arxiv.org/abs/1708.02621)
4.  [Grokking Streaming Systems](https://www.manning.com/books/grokking-streaming-systems) by Josh Fischer & Ning Wang
5.  [Streaming Systems: The What, Where, When, and How of Large-Scale Data Processing](https://www.oreilly.com/library/view/streaming-systems/9781491983867/) by Reuven Lax, Slava Chernyak, and Tyler Akidau
6.  [Data Pipelines with Apache Airflow](https://www.manning.com/books/data-pipelines-with-apache-airflow) by Bas P. Harenslak and Julian Rutger de Ruiter
7.  [MillWheel: Fault-Tolerant Stream Processing at Internet Scale](https://research.google/pubs/millwheel-fault-tolerant-stream-processing-at-internet-scale/)

## License

![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/80x15.png)

Licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)

[archived-badge]: https://img.shields.io/badge/status-archived-lightgrey

[language-c]: https://img.shields.io/badge/language-C-blue

[language-c-cpp-python]: https://img.shields.io/badge/language-C%2FC%2B%2B%2FPython-blue

[language-csharp]: https://img.shields.io/badge/language-C%23-blue

[language-cpp]: https://img.shields.io/badge/language-C%2B%2B-blue

[language-cpp-java]: https://img.shields.io/badge/language-C%2B%2B%2FJava-blue

[language-cpp-python-java-typescript]: https://img.shields.io/badge/language-C%2B%2B%2FPython%2FJava%2FTypeScript-blue

[language-clojure]: https://img.shields.io/badge/language-Clojure-blue

[language-go]: https://img.shields.io/badge/language-Go-blue

[language-go-python]: https://img.shields.io/badge/language-Go%2FPython-blue

[language-haskell]: https://img.shields.io/badge/language-Haskell-blue

[language-java]: https://img.shields.io/badge/language-Java-blue

[language-java-c]: https://img.shields.io/badge/language-Java%2FC-blue

[language-java-cpp]: https://img.shields.io/badge/language-Java%2FC%2B%2B-blue

[language-java-python-go]: https://img.shields.io/badge/language-Java%2FPython%2FGo-blue

[language-java-python-typescript]: https://img.shields.io/badge/language-Java%2FPython%2FTypeScript-blue

[language-java-scala]: https://img.shields.io/badge/language-Java%2FScala-blue

[language-pony]: https://img.shields.io/badge/language-Pony-blue

[language-python]: https://img.shields.io/badge/language-Python-blue

[language-python-java]: https://img.shields.io/badge/language-Python%2FJava-blue

[language-python-java-scala]: https://img.shields.io/badge/language-Python%2FJava%2FScala-blue

[language-python-rust]: https://img.shields.io/badge/language-Python%2FRust-blue

[language-python-typescript]: https://img.shields.io/badge/language-Python%2FTypeScript-blue

[language-rust]: https://img.shields.io/badge/language-Rust-blue

[language-rust-go-typescript]: https://img.shields.io/badge/language-Rust%2FGo%2FTypeScript-blue

[language-rust-python]: https://img.shields.io/badge/language-Rust%2FPython-blue

[language-rust-python-typescript]: https://img.shields.io/badge/language-Rust%2FPython%2FTypeScript-blue

[language-rust-wasm]: https://img.shields.io/badge/language-Rust%2FWASM-blue

[language-scala]: https://img.shields.io/badge/language-Scala-blue

[language-scala-java]: https://img.shields.io/badge/language-Scala%2FJava-blue

[language-scala-java-python-r]: https://img.shields.io/badge/language-Scala%2FJava%2FPython%2FR-blue

[language-sql]: https://img.shields.io/badge/language-SQL-blue

[language-typescript]: https://img.shields.io/badge/language-TypeScript-blue

[language-typescript-python]: https://img.shields.io/badge/language-TypeScript%2FPython-blue

