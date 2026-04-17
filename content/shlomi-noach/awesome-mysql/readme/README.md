# Awesome Mysql Overview

A curated list of awesome MySQL software, libraries, tools and resources

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/shlomi-noach/awesome-mysql/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 shlomi-noach/awesome-mysql](https://github.com/shlomi-noach/awesome-mysql) · ⭐ 2.6K · 🏷️ Databases

[ [Daily](/content/shlomi-noach/awesome-mysql/README.md) / [Weekly](/content/shlomi-noach/awesome-mysql/week/README.md) / Overview ]

---

# awesome-mysql

A curated list of awesome MySQL free and opensource software, libraries and resources. [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This list accepts and encourages pull requests. See [CONTRIBUTING (⭐2.6k)](https://github.com/shlomi-noach/awesome-mysql/blob/master/CONTRIBUTING.md)

### Contents

*   [Awesome MySQL](#awesome-mysql)
    *   [Analysis](#analysis)
    *   [Backup](#backup)
    *   [Benchmarking](#benchmarking)
    *   [Binlog Replication](#binlog-replication)
    *   [ChatOps](#chatops)
    *   [Configuration](#configuration)
    *   [Connectors](#connectors)
    *   [Deployment](#deployment)
    *   [Development](#development)
    *   [GUI](#gui)
    *   [HA](#ha)
    *   [MCP](#mcp)
    *   [Proxy](#proxy)
    *   [Replication](#replication)
    *   [Schema](#schema)
    *   [Security](#security)
    *   [Server](#server)
    *   [Sharding](#sharding)
    *   [Toolkits](#toolkits)

*   [Resources](#resources)
    *   [E-Books](#e-books)

## Analysis

*Performance, structure & data analysis tools*

*   [Anemometer (⭐1.4k)](https://github.com/box/Anemometer) - Box SQL slow query monitor.
*   [innodb-ruby (⭐1.8k)](https://github.com/jeremycole/innodb_ruby) - A parser for InnoDB file formats, in Ruby.
*   [innotop (⭐798)](https://github.com/innotop/innotop) - a 'top' clone for MySQL with many features and flexibility.
*   [MySQL Explain Analyzer (⭐97)](https://github.com/Preetam/explain-analyzer) - A web-based analyzer of `EXPLAIN FORMAT=JSON` output, providing comments, scalability analysis and permalinks for saved samples.
*   [mysql-statsd (⭐101)](https://github.com/db-art/mysql-statsd) - A Python daemon to collect information from MySQL and send it via StatsD to Graphite.
*   [MySQLTuner-perl (⭐9.4k)](https://github.com/major/MySQLTuner-perl) - A script that allows you to review a MySQL installation quickly and make adjustments to increase performance and stability.
*   [Prometheus (⭐64k)](https://github.com/prometheus/prometheus)/[mysqld\_exporter (⭐2.4k)](https://github.com/prometheus/mysqld_exporter) - Time series database for real-time monitoring and alerting.
*   [pstop (⭐210)](https://github.com/sjmudd/ps-top) - a top-like program for MySQL, collecting, aggregating and displaying information from performance\_schema.
*   [ReliaDB EXPLAIN Analyzer (⭐0)](https://github.com/Mughees52/mysql-explain-analyzer) - a browser-based MySQL and MariaDB EXPLAIN visualizer with issue detection, index recommendations, and query rewrites. 100% client-side.
*   [Wireshark](https://gitlab.com/wireshark/wireshark/) - a protocol analyzer that can decode the MySQL protocol.
*   [Dolphie (⭐1.1k)](https://github.com/charles-001/dolphie) - a modern terminal tool for real-time analytics into MySQL/MariaDB & ProxySQL
*   [sql-tap (⭐1.5k)](https://github.com/mickamy/sql-tap) - Real-time SQL traffic viewer.

## Backup

*Backup/restore/recovery tools*

*   [Databasus (⭐6.3k)](https://github.com/databasus/databasus) - tool for scheduled MySQL backups via web UI with external storages (local, S3, FTP, Google Drive, etc.), notifications (webhook, Discord, Slack, etc.) and team management.
*   [Dumpling (⭐40k)](https://github.com/pingcap/tidb/tree/master/dumpling) - Logical, parallel backup/dumper tool for MySQL/TiDB written in GoLang - support csv format output and integrated as library
*   [MyDumper (⭐3.1k)](https://github.com/mydumper/mydumper) - Logical, parallel backup/dumper tool for MySQL
*   [Percona Xtrabackup (⭐1.5k)](https://github.com/percona/percona-xtrabackup) - an open-source hot backup utility for MySQL - based servers that doesn’t lock your database during the backup.
*   [Portabase (⭐681)](https://github.com/Portabase/portabase) - Agent-based platform for MySQL backups and restores with decentralized execution and centralized orchestration.

## Benchmarking

*Tools to stress your servers*

*   [HammerDB (⭐749)](https://github.com/TPC-Council/HammerDB) - An open-source database benchmark for MySQL/MariaDB and other open source and commercial databases.
*   [go-tpc (⭐211)](https://github.com/pingcap/go-tpc) - A golang port of [TPCC](http://www.tpc.org/tpcc/) and [TPCH](http://www.tpc.org/tpch/) benchmark for MySQL.
*   [iibench-mysql (⭐46)](https://github.com/tmcallaghan/iibench-mysql) - Java based version of the Index Insertion Benchmark for MySQL/Percona/MariaDB.
*   [Sysbench (⭐6.7k)](https://github.com/akopytov/sysbench) - a modular, cross-platform and multi-threaded benchmark tool.
*   [TPCC-MySQL (⭐488)](https://github.com/Percona-Lab/tpcc-mysql) (archived) - A port of the popular [TPCC](http://www.tpc.org/tpcc/) benchmark for MySQL.

## Binlog-Replication

*   [DM (⭐456)](https://github.com/pingcap/tiflow) - A High-Availability data migration platform which supports migrating data from MySQL/MariaDB to TiDB and merging shard tables
*   [Kingbus (⭐897)](https://github.com/flike/kingbus) - A distributed MySQL binlog storage system built on Raft
*   [mysql-ripple (⭐377)](https://github.com/google/mysql-ripple) (archived) - Ripple, a server that can serve as a middleman in MySQL replication

## ChatOps

*Scripts integrated into chat rooms*

*   [Hubot MySQL ChatOps (⭐90)](https://github.com/samlambert/hubot-mysql-chatops)

## Configuration

*MySQL sample configuration and advisors*

*   [mysql-compatibility-config (⭐94)](https://github.com/morgo/mysql-compatibility-config) - make MySQL configuration behave more like newer (or older) releases of MySQL.

## Connectors

*MySQL connectors for various programming languages*

*   [ballerinax/mysql (⭐111)](https://github.com/ballerina-platform/module-ballerinax-mysql) - Official Ballerina connector for MySQL.
*   [DBD::MariaDB (⭐40)](https://github.com/perl5-dbi/DBD-MariaDB) - MariaDB and MySQL driver for the Perl5 Database Interface.
*   [DBD::mysql (⭐67)](https://github.com/perl5-dbi/DBD-mysql) - MySQL driver for the Perl5 Database Interface.
*   [go-sql-driver (⭐15k)](https://github.com/go-sql-driver/mysql) - a lightweight and fast MySQL-Driver for Go's (golang) database/sql package.
*   [libAttachSQL (⭐29)](https://github.com/libattachsql/libattachsql) - libAttachSQL is a lightweight, non-blocking C API for MySQL servers.
*   [MariaDB Connector/J (⭐358)](https://github.com/mariadb-corporation/mariadb-connector-j) - LGPL-licensed MariaDB Client Library for Java Applications.
*   [mex-mariadb (⭐2)](https://github.com/markuman/mex-mariadb) - MIT licensed MariaDB/MySQL Client Library for GNU Octave and Matlab.
*   [MySQL C API](https://dev.mysql.com/downloads/c-api/) - Official C driver for MySQL.
*   [MySQL Connector/C++ (⭐703)](https://github.com/mysql/mysql-connector-cpp) - Official C/C++ driver for MySQL.
*   [MySQL Connector/J (⭐1k)](https://github.com/mysql/mysql-connector-j) - a standardized database driver for the Java platforms and development.
*   [MySQL Connector/NET (⭐325)](https://github.com/mysql/mysql-connector-net) - a standardized database driver for .Net platforms and development.
*   [MySQL Connector/Node.js (⭐159)](https://github.com/mysql/mysql-connector-nodejs) - Official Node.js driver for MySQL.
*   [MySQL Connector/Python (⭐951)](https://github.com/mysql/mysql-connector-python) - a standardized database driver for Python platforms and development.
*   [mysqlclient-python (⭐2.5k)](https://github.com/PyMySQL/mysqlclient) - MySQL database connector for Python.
*   [node-mysql (⭐19k)](https://github.com/mysqljs/mysql) - A pure Nodejs Javascript client implementing the MySQL protocol.
*   [PHP mysqlnd](https://www.php.net/manual/en/book.mysqlnd.php) - MySQL native driver for PHP.
*   [PyMySQL (⭐7.8k)](https://github.com/PyMySQL/PyMySQL) - MySQL database connector for Python.
*   [Ruby Mysql2 gem (⭐2.3k)](https://github.com/brianmario/mysql2) - MySQL driver for Ruby and Rails projects.
*   [MyZql (⭐68)](https://github.com/speed2exe/myzql) - MySQL and MariaDB driver in native Zig.
*   [wtx (⭐346)](https://github.com/c410-f3r/wtx) - Client for MySQL/MariaDB/Percona written in Rust

## Deployment

*MySQL deployment tools*

*   [MariaDB4j (⭐896)](https://github.com/MariaDB4j/MariaDB4j) - A Java launcher to run MariaDB without installation or external dependencies.

## Development

*Tools to support MySQL-related development*

*   [Flywaydb (⭐9.7k)](https://github.com/flyway/flyway) - Database migrations; Evolve your database schema easily and reliably across all your instances
*   [dbsafe (⭐11)](https://github.com/nethalo/dbsafe) - Pre-execution safety analysis for MySQL DDL/DML operations
*   [Liquibase (⭐5.5k)](https://github.com/liquibase/liquibase) - Source control for your database
*   [Shift (⭐741)](https://github.com/square/shift) - An application that helps you run schema migrations on MySQL databases
*   [Skeema (⭐1.4k)](https://github.com/skeema/skeema) - Declarative pure-SQL schema management system for MySQL and MariaDB, with support for sharding and external online schema change tools
*   [SQLE (⭐1.5k)](https://github.com/actiontech/sqle/blob/main/README_en.md) - SQLE is a SQL audit platform for DBA or developer
*   [Test database (⭐4.4k)](https://github.com/datacharmer/test_db) - A sample MySQL database with an integrated test suite, used to test applications and servers
*   [cover\_me (⭐3)](https://github.com/verizonconnect/database-development) - code coverage tool for mysql stored procedures and functions

## GUI

*GUI frontends & applications*

*   [Adminer (⭐7.3k)](https://github.com/vrana/adminer/) - Database management in a single PHP file.
*   [DBeaver (⭐50k)](https://github.com/dbeaver/dbeaver/) - A cross-platform SQL and NoSQL database client.
*   [HeidiSQL (⭐5.9k)](https://github.com/HeidiSQL/HeidiSQL) - MySQL GUI frontend for Windows.
*   [ILLA Cloud (⭐12k)](https://github.com/illacloud/illa-builder) - Low-code internal tool builder integrated with Mysql, can be used as GUI for Mysql.
*   [mycli (⭐12k)](https://github.com/dbcli/mycli) - A Terminal Client for MySQL with AutoCompletion and Syntax Highlighting.
*   [MySQL Shell (⭐218)](https://github.com/mysql/mysql-shell/) - Advanced client and code editor for MySQL that supports development and administration for the MySQL Server and MySQL InnoDB cluster (AdminAPI) with an interactive JavaScript, Python, or SQL interface.
*   [MySQL Workbench (⭐988)](https://github.com/mysql/mysql-workbench) - provides DBAs and developers an integrated tools environment for database design & modeling; SQL devleopment; database administration.
*   [Ocelot GUI (⭐63)](https://github.com/ocelot-inc/ocelotgui) - GUI client for MySQL or MariaDB, including debugger.
*   [OmniDB: Web tool for database management (⭐3.3k)](https://github.com/OmniDB/OmniDB)
*   [Percona Monitoring and Management (⭐1k)](https://github.com/percona/pmm) - An open-source platform for managing and monitoring MySQL performance.
*   [phpMyAdmin (⭐7.9k)](https://github.com/phpmyadmin/phpmyadmin) - a free software tool written in PHP, intended to handle the administration of MySQL over the Web.
*   [pspg (⭐2.7k)](https://github.com/okbob/pspg) - provides a pager with enhanced visualization and navigation for tabular data. Originally implemented for PostgreSQL, but also supports MySQL.
*   [Sequel Ace (⭐7.3k)](https://github.com/Sequel-Ace/Sequel-Ace) - a Mac database management application for working with MySQL databases.
*   [SQLyog Community edition (⭐2.3k)](https://github.com/webyog/sqlyog-community) - SQLyog Community edition. For Windows, works fine under wine in Mac and Linux
*   [squix (⭐206)](https://github.com/eduardofuncao/squix) - SQL command-line client with query management and interactive results.
*   [WebDB (⭐335)](https://github.com/WebDB-App/app) – Open Source and Efficient Database IDE. Featuring Easy server connection, Modern ERD, Intelligent data generator, AI assistant, NoSQL structure manager, Time machine and Powerful query editor

## HA

*High availability solutions*

*   [Galera Cluster (⭐490)](https://github.com/codership/galera) - a true Multimaster Cluster based on synchronous replication.
*   [mha4mysql-node (⭐408)](https://github.com/yoshinorim/mha4mysql-node) and [mha4mysql-manager (⭐1.5k)](https://github.com/yoshinorim/mha4mysql-manager) (both unmaintained) - Master High Availability Manager and tools for MySQL.
*   [Orchestrator (⭐5.8k)](https://github.com/openark/orchestrator) (archived) - MySQL replication topology management and High Availability solution.
*   [Percona Replication Manager (⭐7)](https://github.com/percona/replication-manager) - Asynchronous MySQL replication manager agent for Pacemaker. Supports file and GTID based replication, geo-distributed clusters using booth.
*   [replication-manager (⭐726)](https://github.com/signal18/replication-manager) - a high availability solution to manage MariaDB 10.x and MySQL & Percona Server 5.7 GTID replication topologies.

## MCP

*   [MCP MariaDB Server (⭐164)](https://github.com/MariaDB/mcp) - the official MariaDB MCP server.
*   [MySQL MCP Server (⭐25)](https://github.com/askdba/mysql-mcp-server) - Advanced MCP server exposing MySQL via the Model Context Protocol
*   [TiDB MCP Server](https://pingcap.github.io/ai/integrations/tidb-mcp-server/) - MCP Server for TiDB.

## Proxy

*Proxies to MySQL*

*   [MySQL Router](https://dev.mysql.com/doc/mysql-router/en/) - MySQL Router is part of InnoDB cluster, and is a lightweight middleware that provides transparent routing between your application and back-end MySQL Servers.
*   [ProxySQL (⭐6.7k)](https://github.com/sysown/proxysql) - High performance proxy for MySQL.

## Replication

*Replication related software*

*   [data-diff (⭐3k)](https://github.com/datafold/data-diff) (archived) - Command-line tool and Python library to efficiently diff rows across two different databases.

## Schema

*Add-on schemas*

*   [common\_schema (⭐126)](https://github.com/shlomi-noach/common_schema) - DBA's framework for MySQL, providing a function library, views library and QueryScript interpreter.
*   [sys (⭐828)](https://github.com/mysql/mysql-sys) (archived) - A collection of views, functions and procedures to help MySQL administrators get insight in to MySQL Database usage. See [sys schema docs](https://dev.mysql.com/doc/refman/8.4/en/sys-schema.html)

## Security

*Tools that prevents leaking of sensitive data from database (encryption, masking and tokenization, honey-pots, etc)*

*   [Acra (⭐1.5k)](https://github.com/cossacklabs/acra) - SQL database protection suite: strong selective encryption, SQL injections prevention, intrusion detection system.
*   [myanon (⭐118)](https://github.com/ppomes/myanon) - Streaming anonymizer for MySQL dump files, reading mysqldump output from stdin and writing anonymized data to stdout. Supports deterministic hashing, fixed values, JSON field anonymization, and Python extensions.
*   [myldapsync (⭐0)](https://github.com/6eh01der/myldapsync) - Synchronize MySQL or MariaDB users with users in an LDAP directory.

## Server

*MySQL server flavors*

*   [MariaDB (⭐7.4k)](https://github.com/MariaDB/server) - Community developed fork of MySQL server.
*   [MySQL Server & MySQL Cluster (⭐12k)](https://github.com/mysql/mysql-server) - Official Oracle's MySQL server & MySQL Cluster distribution.
*   [MyVector (⭐8)](https://github.com/askdba/myvector) - Native vector search plugin for MySQL, shipped as a server plugin.
*   [Percona Server (⭐1.3k)](https://github.com/percona/percona-server) - An enhanced, drop-in MySQL replacement.
*   [TiDB (⭐40k)](https://github.com/pingcap/tidb) - A distributed HTAP database compatible with the MySQL protocol.

## Sharding

*Sharding solutions/frameworks*

*   [Jetpants (⭐1.1k)](https://github.com/tumblr/jetpants) - An automation suite for managing large range sharding clusters, by Tumblr.
*   [Vitess (⭐21k)](https://github.com/vitessio/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.

## Toolkits

*Toolkits, general purpose scripts*

*   [gh-ost (⭐13k)](https://github.com/github/gh-ost/) - GitHub's online schema migration for MySQL.
*   [go-mysql (⭐4.9k)](https://github.com/go-mysql-org/go-mysql) - A pure go library to handle MySQL network protocol and replication.
*   [MySQL Utilities (⭐276)](https://github.com/mysql/mysql-utilities) (deprecated) - a collection of command-line utilities, written in Python, that are used for maintaining and administering MySQL servers, either individually, or within Replication hierarchies.
*   [Percona Toolkit (⭐1.5k)](https://github.com/percona/percona-toolkit) - a collection of advanced command-line tools to perform a variety of MySQL server and system tasks that are too difficult or complex to perform manually.
*   [sql-splitter (⭐5)](https://github.com/HelgeSverre/sql-splitter) - High-performance CLI for splitting, merging, converting, validating, and sampling mysqldump files.
*   [Swoof (⭐29)](https://github.com/StirlingMarketingGroup/swoof) - Ultra fast MySQL table importer that stages swaps through temporary tables and supports file/clipboard targets.
*   [UnDROP (⭐420)](https://github.com/twindb/undrop-for-innodb) (archived) - a tool to recover data from dropped or corrupted InnoDB tables.

# Resources

*At this stage "resources" will not include websites, blogs, slides, presentation videos, etc. in fear of list size*

## e-books

*e-books as well as relevant materials on and around MySQL*

*   [Database Systems Lecture Notes](http://spots.augusta.edu/caubert/db/ln/) - lecture notes on Database Systems (available in pdf, html, odt and markdown) including a Chapter on SQL that covers basic set-up, exercises and problems.
*   [SQL-exercise (⭐1.5k)](https://github.com/XD-DENG/SQL-exercise) - contains several SQL exercises, including the schema description figure, SQL code to build schema, questions and solutions in SQL. Based on wikibook [SQL Exercises](https://en.wikibooks.org/wiki/SQL_Exercises).

## Incubating

Projects that are known to be non-production and yet have either traction or substance that warrants exposure.

*   [VillageSQL (⭐123)](https://github.com/villagesql/villagesql-server) - A drop-in replacement for MySQL with extensions for the agentic AI era.

