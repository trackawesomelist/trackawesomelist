# Awesome Gatling Overview

A collection of resources covering different aspects of Gatling load testing tool usage.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/aliesbelik/awesome-gatling/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 aliesbelik/awesome-gatling](https://github.com/aliesbelik/awesome-gatling) · ⭐ 72 · 🏷️ Testing

[ [Daily](/content/aliesbelik/awesome-gatling/README.md) / [Weekly](/content/aliesbelik/awesome-gatling/week/README.md) / Overview ]

---

# Awesome Gatling [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!--lint ignore double-link-->

[<img src="https://github.com/aliesbelik/awesome-gatling/raw/main/assets/images/gatling-logo.svg" align="right" width="260" alt="Gatling">](https://gatling.io/)

<!--lint ignore double-link-->

A curated collection of resources covering all aspects of load testing using [Gatling](https://gatling.io/) and related stuff: plugins, integrations, testing techniques, DevOps practices, etc.

<!--lint ignore double-link-->

> [Gatling](https://gatling.io/) is an open-source load and performance testing framework based on Scala, Akka and Netty.

## Contents

*   [Official Resources](#official-resources)
*   [Getting Started](#getting-started)
*   [Tutorials](#tutorials)
*   [Distributed Testing](#distributed-testing)
*   [Tools](#tools)
    *   [Plugins](#plugins)
    *   [Frameworks](#frameworks)
    *   [Reporting](#reporting)
    *   [Sandbox](#sandbox)
    *   [Miscellaneous](#miscellaneous)
*   [CI](#ci)
*   [Trainings & Courses](#trainings--courses)
*   [Videos](#videos)
    *   [Talks](#talks)
    *   [Video Tutorials](#video-tutorials)
*   [Community](#community)
*   [Related](#related)
    *   [Awesome Lists](#awesome-lists)
    *   [Other](#other)

## Official Resources

<!--lint ignore double-link-->

*   [Homepage](https://gatling.io/)
*   [Documentation](https://docs.gatling.io/)
*   [Source code (⭐6.7k)](https://github.com/gatling/gatling)

## Getting Started

*   [A first look at Gatling, a DSL based load test tool](https://callistaenterprise.se/blogg/teknik/2014/04/16/a-first-look-at-gatling-a-dsl-based-load-test-tool/)
*   [Gatling: Take your performance tests to the next level](https://www.thoughtworks.com/insights/blog/gatling-take-your-performance-tests-next-level)
*   [Load Testing with Gatling. The Complete Guide](https://www.james-willett.com/gatling-load-testing-complete-guide/)

## Tutorials

*   [Load testing gRPC services with Gatling](https://medium.com/@georgeleung_7777/load-testing-grpc-services-with-gatling-990025c77055)
*   [Creating a custom Gatling protocol for AWS Lambda](https://callistaenterprise.se/blogg/teknik/2016/11/26/gatling-custom-protocol/)
*   [Load testing ZeroMQ with a custom DSL for Gatling](https://mintbeans.com/load-testing-zeromq-with-gatling/)

## Distributed Testing

*   [Distributed load testing with Gatling and Kubernetes](https://debijenkorf.tech/https-medium-com-annashepeleva-distributed-load-testing-with-gatling-and-kubernetes-93ebce26edbe)
*   [Gatling – Scaling Out Your Load Tests](https://web.archive.org/web/20210625094528/http://www.nimrodstech.com/gatling-cluster-load-testing/)
*   [Distributed Gatling (⭐102)](https://github.com/Abiy/distGatling) - Solution to run Gatling simulation tests in a distributed/cluster environment.
*   [gatling-operator (⭐81)](https://github.com/st-tech/gatling-operator) - Automating distributed Gatling load testing using Kubernetes operator.

## Tools

### Plugins

*   [gatling-sbt-plugin (⭐107)](https://github.com/gatling/gatling-sbt-plugin) - Gatling SBT plugin to integrate Gatling with SBT, allowing to use Gatling as a testing framework.
*   [gatling-build-plugin (⭐3)](https://github.com/gatling/gatling-build-plugin) - An SBT plugin to share common settings across Gatling's projects' builds.
*   [gatling-maven-plugin (⭐37)](https://github.com/gatling/gatling-maven-plugin) - Gatling Maven Extensions.
*   [gatling-gradle-plugin (⭐29)](https://github.com/gatling/gatling-gradle-plugin) - Gatling plugin for Gradle.
*   [gatling-remote-sbt (⭐10)](https://github.com/Pravoru/gatling-remote-sbt) - Remote execution plugin for Gatling load tests.
*   [gatling-junitrunner (⭐3)](https://github.com/Pravoru/gatling-junitrunner) - JUnit wrapper around Gatling simulations.
*   [gatling-grpc (⭐127)](https://github.com/phiSgr/gatling-grpc) - Gatling load test plugin for gRPC.
*   [gatling-aws (⭐11)](https://github.com/callistaenterprise/gatling-aws) - Gatling custom protocol for AWS Lambda.
*   [gatling-xmpp-protocol (⭐4)](https://github.com/TLmaK0/gatling-xmpp-protocol) - XMPP protocol for stress test XMPP servers with Gatling.
*   [gatling-jwt](https://bitbucket.org/atlassianlabs/gatling-jwt/) - An extension to Gatling 2.0 to help make JWT-signed requests.
*   [gatling-mqtt (⭐43)](https://github.com/mnogu/gatling-mqtt) - A Gatling plugin for stress testing MQTT.
*   [gatling-kafka (⭐67)](https://github.com/mnogu/gatling-kafka) - A Gatling plugin for stress testing Apache Kafka protocol.
*   [gatling-kafka (⭐13)](https://github.com/Amerousful/gatling-kafka) - Gatling plugin for Kafka.
*   [gatling-kafka-plugin (⭐11)](https://github.com/galax-io/gatling-kafka-plugin) - Plugin for support Kafka in Gatling.
*   [gatling-amqp-plugin (⭐5)](https://github.com/galax-io/gatling-amqp-plugin) - Plugin for support performance testing with AMQP in Gatling (3.2.x).
*   [gatling-jdbc-plugin (⭐6)](https://github.com/galax-io/gatling-jdbc-plugin) - Simple Gatling plugin for JDBC support.
*   [gatling-picatinny (⭐4)](https://github.com/galax-io/gatling-picatinny) - Library with a bunch of useful functions that extend Gatling DSL.
*   [gatling-sql (⭐6)](https://github.com/tmcgrath/gatling-sql) - Gatling extension for JDBC or Spark Thrift Server stress testing.
*   [gatling-tcp-extensions (⭐23)](https://github.com/scalecube/gatling-tcp-extensions) - TCP extensions for Gatling.
*   [gatling-thrift (⭐18)](https://github.com/3tty0n/gatling-thrift) - Gatling third party plugin for Apache Thrift.
*   [gatling-bolt (⭐2)](https://github.com/sarmbruster/gatling-bolt) - Support Neo4j Bolt protocol for Gatling.
*   [gatling-zeromq (⭐5)](https://github.com/softwaremill/gatling-zeromq) - A Gatling stress test plugin for ZeroMQ protocol.
*   [gatling-dubbo (⭐151)](https://github.com/youzan/gatling-dubbo) - A Gatling plugin for running load tests on Apache Dubbo.
*   [gatling-wait (⭐7)](https://github.com/Amerousful/gatling-wait) - Plugin that simplifies waiting for specific events allowing customizable conditions, attempt management, and error handling.

### Frameworks

*   [Kraken (⭐117)](https://github.com/OctoPerf/kraken) - Load testing IDE based on Gatling by OctoPerf.
*   [Karate Gatling](https://karatelabs.github.io/karate/karate-gatling/) - Re-use Karate API-tests as performance tests executed by Gatling.
*   [Taurus](https://gettaurus.org/docs/Gatling/) - Gatling Executor in Taurus framework.
*   [Carrier](https://getcarrier.io/) - Continuous test execution platform with ability to perform load testing using customized JMeter and Gatling containers.

### Reporting

*   [gatling-report (⭐122)](https://github.com/nuxeo/gatling-report) - Parse Gatling simulation.log files to output CSV stats or build HTML reports with Plotly charts.
*   [gatling2allure (⭐6)](https://github.com/biski/gatling2allure) - Convert Gatling log to Allure report.
*   [gatling-elasticsearch (⭐12)](https://github.com/Amerousful/gatling-elasticsearch-logs) - Logger which parses raw Gatling logs and sends them to the Elasticsearch.

### Sandbox

*   [gatling-scaffold (⭐17)](https://github.com/robsonbittencourt/gatling-scaffold) - Base for load test project using Gatling, InfluxDB and Grafana.
*   [perfiz (⭐15)](https://github.com/znsio/perfiz) - A dockerised API performance test setup based on Gatling with Grafana dashboards and Prometheus monitoring.

### Miscellaneous

*   [dakiya (⭐37)](https://github.com/rupeshmore/dakiya) - Convert Postman collections to Gatling scripts.
*   [gatling.g8 (⭐8)](https://github.com/gatling/gatling.g8) - Giter8 template for Gatling.
*   [gatling-template.g8 (⭐3)](https://github.com/galax-io/gatling-template.g8) - A Giter8 template for Gatling performance test project.

## CI

*   [Gatling Jenkins Plugin (⭐35)](https://github.com/jenkinsci/gatling-plugin) - [Jenkins plugin](https://plugins.jenkins.io/gatling/) for Gatling.
*   [run-gatling (⭐5)](https://github.com/liatrio/run-gatling) - GitHub Action to easily integrate Gatling performance tests to GitHub workflows.

## Trainings & Courses

*   [Gatling Academy](https://academy.gatling.io/)
*   [Gatling Courses](https://www.udemy.com/topic/gatling/) - By Udemy.
*   [Performance Test Automation 101: Gatling, Lighthouse, & Jenkins](https://www.educative.io/courses/performance-test-automation-101-gatling-lighthouse-jenkins) - By Educative.

## Videos

### Talks

*   [Load Testing Done Right with Gatling](https://www.youtube.com/watch?v=VUPTaPms210) - Stéphane Landelle @ Voxxed Days Belgrade 2015.
*   [Load Testing Crash Course with Gatling](https://www.youtube.com/watch?v=RiM1GsVSbzM) - Stéphane Landelle @ Devoxx Belgium 2022.
*   [Load Testing Made Easy with Gatling](https://www.youtube.com/watch?v=8Eplj8BvugA) - Rafał Piotrowski @ Scala Days 2023 Madrid.

### Video Tutorials

*   [Performance Testing with Gatling](https://www.youtube.com/playlist?list=PLd4gvNaNZ4T3NCWsv3zwHYlLGtr9s1-Fz) - Tutorial series by Tomi Tiihonen.
*   [Gatling Tutorials for Beginners](https://www.youtube.com/playlist?list=PLw_jGKXm9lIYpTotIJ-R31pXS7qqwXstt) - Tutorial series by James Willett.

## Community

*   [Gatling Community](https://community.gatling.io/)
*   [`gatling` on Stack Overflow](https://stackoverflow.com/questions/tagged/gatling+or+scala-gatling+or+gatling-java+or+gatling-plugin)
*   [`@GatlingTool` on Twitter](https://twitter.com/gatlingtool)

## Related

### Awesome Lists

*   [Awesome Software Quality (⭐2.3k)](https://github.com/ligurio/sqa-wiki) - A list of free software testing and verification resources.
*   [Awesome Testing (⭐2k)](https://github.com/TheJambo/awesome-testing) - A curated list of testing resources.
*   [Awesome JMeter (⭐750)](https://github.com/aliesbelik/awesome-jmeter) - Open-source load testing and performance measurement tool, written in Java.
*   [Awesome Tsung (⭐22)](https://github.com/aliesbelik/awesome-tsung) - Open-source multi-protocol distributed load testing tool, developed in Erlang.
*   [Awesome k6 (⭐686)](https://github.com/grafana/awesome-k6) - Open-source, developer-centric performance monitoring and load testing solution.
*   [Awesome Locust (⭐104)](https://github.com/aliesbelik/awesome-locust) - Open-source scalable load testing framework written in Python.

### Other

*   [How They Load Test (⭐124)](https://github.com/aliesbelik/how-they-load) - A curated collection of publicly available resources on how companies around the world perform load testing.
*   [Load Testing Toolkit (⭐203)](https://github.com/aliesbelik/load-testing-toolkit) - Collection of open-source tools for debugging, benchmarking, load and stress testing your code or services.

## Contributing

Contributions are welcome!<br>
Please take a look at the [CONTRIBUTING](https://github.com/aliesbelik/awesome-gatling/blob/main/README.md/CONTRIBUTING.md) guidelines first.

