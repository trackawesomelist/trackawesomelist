# Awesome Tinkerpop Overview

A curated list of useful libraries for Apache TinkerPop3 and Tinkerpop2

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/mohataher/awesome-tinkerpop/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 mohataher/awesome-tinkerpop](https://github.com/mohataher/awesome-tinkerpop) · ⭐ 161 · 🏷️ Databases

[ [Daily](/content/mohataher/awesome-tinkerpop/README.md) / [Weekly](/content/mohataher/awesome-tinkerpop/week/README.md) / Overview ]

---

# Awesome TinkerPop [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

![alt tag](https://raw.githubusercontent.com/mohataher/awesome-tinkerpop/master/tinkerpop-splash.png)

A curated list of only awesome TinkerPop libraries on Github.

> Apache TinkerPop™ is a graph computing framework for both graph databases (OLTP) and graph analytic systems (OLAP).

### Table of Contents

*   [TinkerPop3](#tinkerpop3)
    *   [Implementations](#tinkerpop3-implementations)
    *   [Wrappers/Clients](#wrappers)
    *   [Query Languages](#qlang)
*   [TinkerPop2](#tinkerpop2)
*   [Communites](#communites)
*   [People to Follow](#people-to-follow)
*   [Tutorials and Resources](#tutorials-and-resources)
*   [How to Contribute](#contributing)
*   [License](#license)

### <A NAME="tinkerpop3"></A>TinkerPop3 Libraries

#### <A NAME="tinkerpop3-implementations"></A>Implementations

*   [TinkerPop3 implementation (⭐1.6k)](https://github.com/apache/tinkerpop) - Mirror of Apache TinkerPop.
*   [sqlg (⭐221)](https://github.com/pietermartin/sqlg) - Sqlg is a implementation of TinkerPop3 on a RDBMS.
*   [blazegraph (⭐724)](https://github.com/blazegraph/database) - TinkerPop3 [implementation (⭐56)](https://github.com/blazegraph/tinkerpop3) for Blaze Graph; a high performance graph database.
*   [tinkergraph-js (⭐67)](https://github.com/jbmusso/tinkergraph-js) - A pure JavaScript implementation of TinkerPop's TinkerGraph in-memory graph database.
*   [gremlin-javascript (⭐212)](https://github.com/jbmusso/gremlin-javascript) - JavaScript graph database client for TinkerPop3 Gremlin Server.
*   [Elastic Gremlin (⭐68)](https://github.com/rmagen/elastic-gremlin) - TinkerPop3 implementation on Elasticsearch backend.
*   [Hadoop (Giraph)](http://tinkerpop.apache.org/docs/current/reference/#giraphgraphcomputer) - OLAP graph processor using Giraph.
*   [Hadoop (Spark)](http://tinkerpop.apache.org/docs/current/reference/#sparkgraphcomputer) - OLAP graph processor using Spark.
*   [IBM Graph](https://console.ng.bluemix.net/catalog/services/ibm-graph/) - OLTP graph database as a service.
*   [Neo4j](http://tinkerpop.apache.org/docs/currentg/#neo4j-gremlin) - OLTP graph database.
*   [Stardog](http://stardog.com/) - RDF graph database with OLTP and OLAP support.
*   [TinkerGraph](http://tinkerpop.apache.org/docs/current/reference/#tinkergraph-gremlin) - In-memory OLTP and OLAP reference implementation.
*   [Unipop (⭐195)](https://github.com/rmagen/unipop) - OLTP Elasticsearch and JDBC backed graph.
*   [DuctileDB (⭐13)](https://github.com/PureSolTechnologies/DuctileDB) - Ductile DB is a graph database based on Hadoop/HBase which provides a vast set of features.
*   [hgraphdb (⭐246)](https://github.com/rayokota/hgraphdb) - HBase as a TinkerPop Graph Database.
*   [JanusGraph (⭐4.6k)](https://github.com/JanusGraph/janusgraph) - JanusGraph: an open-source, distributed graph database <http://janusgraph.org>
*   [JanusGraph for DynamoDB (Amazon) (⭐444)](https://github.com/awslabs/dynamodb-janusgraph-storage-backend) - The Amazon DynamoDB storage backend for JanusGraph.
*   [orientdb-gremlin (⭐89)](https://github.com/orientechnologies/orientdb-gremlin) - TinkerPop3 Graph Structure Implementation for OrientDB.

#### <A NAME="wrappers"></A>Wrappers/Clients

##### C# .NET

*   [Teva Gremlin](https://www.nuget.org/packages/Teva.Common.Data.Gremlin/) (.NET - C#) - A Gremlin Server driver for .NET.

##### Clojure

*   [ogre (⭐123)](https://github.com/clojurewerkz/ogre) - Clojure library for querying TinkerPop graphs.
*   [scalajs-gremlin-client (⭐6)](https://github.com/viagraphs/scalajs-gremlin-client) (scala) - A Gremlin-Server client with ad-hoc extensible, reactive, typeclass based API.

##### Go

*   [go-gremlin (⭐108)](https://github.com/go-gremlin/gremlin) - Go graph database client for TinkerPop3 Gremlin Server.
*   [Gremgo (⭐96)](https://github.com/qasaur/gremgo) - A fast, efficient, and easy-to-use Go client for the TinkerPop graph database stack.
*   [grammes (⭐112)](https://github.com/northwesternmutual/grammes) - A Go package built to communicate with Apache TinkerPop™ Graph computing framework using Gremlin.

##### Haskell

*   [greskell-websocket (⭐26)](https://github.com/debug-ito/greskell) - Haskell client for TinkerPop3 Gremlin Server.

##### Java

*   [gremlin-driver](http://tinkerpop.apache.org/docs/current/reference/#connecting-via-java) (java) - A Gremlin Server driver for Java.
*   [neo4j-tinkerpop-api (⭐6)](https://github.com/neo4j-contrib/neo4j-tinkerpop-api) - Apache Licensed Neo4j API for TinkerPop3.
*   [neo4j-gremlin-bolt](https://github.com/SteelBridgeLabs/neo4j-gremlin-bolt) - Allows use of the Apache Tinkerpop Java API with the neo4j server using the BOLT protocol.
*   [Ferma (⭐138)](https://github.com/Syncleus/Ferma) - An ORM / OGM for the TinkerPop graph stack.

##### Javascript

*   [ts-tinkerpop (⭐54)](https://github.com/RedSeal-co/ts-tinkerpop) - Utilities for using TinkerPop3 via the node-java API in Typescript.
*   [gremlin-javascript (⭐212)](https://github.com/jbmusso/gremlin-javascript) (js) - A Gremlin Server driver for JavaScript.

##### PHP

*   [gremlin-php (⭐75)](https://github.com/PommeVerte/gremlin-php) - gremlin-server php driver compatible with TinkerPop3. It will allow you to connect to gremlin-server and it's backends (Neo4J, Titan, etc.).

##### Python

*   [Mogwai (⭐36)](https://github.com/platinummonkey/mogwai) - TinkerPop3 Graph Database Library for Python.
*   [python-gremlin-rest (⭐7)](https://github.com/windj007/python-gremlin-rest) - A REST-based client for Gremlin Server.
*   [gremlinclient (⭐30)](https://github.com/davebshow/gremlinclient) - An asynchronous Python 2/3 client for Gremlin Server that allows for flexible coroutine syntax - Trollius, Tornado, Asyncio.
*   [aiogremlin (⭐47)](https://github.com/davebshow/aiogremlin) (python) - A Python 3 library based on asyncio and aiohttp that uses websockets to communicate with the Gremlin Server.
*   [gremlinrestclient](http://gremlinrestclient.readthedocs.org/en/latest/) (python) - Python 2/3 library that uses HTTP to communicate with the Gremlin Server over REST.
*   [goblin (⭐94)](https://github.com/ZEROFAIL/goblin) - OGM for TinkerPop3 Gremlin Server.
*   [goblin 3.5 (⭐94)](https://github.com/davebshow/goblin) - A Python 3.5 rewrite of the TinkerPop 3 OGM Goblin.

##### Reactive

*   [reactive-gremlin (⭐32)](https://github.com/coreyauger/reactive-gremlin) (scala) - An Akka HTTP Websocket Connector.

##### Scala

*   [Gremlin Scala (⭐479)](https://github.com/mpollmeier/gremlin-scala) - Scala wrapper for Apache TinkerPop3 Graph DSL.
*   [blueprints-scala (⭐77)](https://github.com/anvie/blueprints-scala) - Tinkerpop Blueprints Scala.

#### <A NAME="qlang"></A>Query Languages

*   [gremlin-py (⭐52)](https://github.com/emehrkay/gremlinpy) - Write pure Python Gremlin that can be sent to Gremlin Server.
*   [gremlin-scala (⭐479)](https://github.com/mpollmeier/gremlin-scala) - A Scala language wrapper for TinkerPop3.
*   [gremlin-template-string (⭐17)](https://github.com/jbmusso/gremlin-template-string) - A Javascript Gremlin language builder.
*   [ipython-gremlin (⭐44)](https://github.com/davebshow/ipython-gremlin) - Gremlin in IPython and Jupyter.
*   [ogre](http://ogre.clojurewerkz.org/) - A Clojure language wrapper for TinkerPop3.
*   [Peapod (⭐40)](https://github.com/bayofmany/peapod) - A new object-graph-wrapper for the Tinkerpop3 graph stack.
*   [sparql-gremlin (⭐68)](https://github.com/dkuppitz/sparql-gremlin) - A SPARQL to Gremlin traversal compiler.
*   [sql-gremlin (⭐70)](https://github.com/twilmes/sql-gremlin) - A SQL to Gremlin traversal compiler.
*   [greskell (⭐26)](https://github.com/debug-ito/greskell) - Haskell binding for Gremlin graph query language
*   [Cypher for Gremlin (⭐318)](https://github.com/opencypher/cypher-for-gremlin) -  Cypher for Gremlin adds Cypher support to any Gremlin graph database.

### <A NAME="tinkerpop2"></A>TinkerPop 2 Libraries

*   [Ferma (⭐138)](https://github.com/Syncleus/Ferma) - An ORM / OGM for the TinkerPop graph stack.
*   [Frames (⭐138)](https://github.com/tinkerpop/frames) - An Object to Graph Framework.
*   [Archimedes (⭐38)](https://github.com/clojurewerkz/archimedes) - Clojure library for Blueprints (part of the TinkerPop graph stack).
*   [AccumuloGraph (⭐33)](https://github.com/JHUAPL/AccumuloGraph) - An implementation of TinkerPop Blueprints using Accumulo.
*   [Frontenac (⭐28)](https://github.com/Loupi/Frontenac) - A .NET port of the TinkerPop Stack.
*   [Mogwai (⭐36)](https://github.com/platinummonkey/mogwai) - TinkerPop 2 Graph Database Library for Python.
*   [spring-data-gremlin (⭐69)](https://github.com/gjrwebber/spring-data-gremlin) - Spring data gremlin makes it easier to implement Graph based repositories. This module extends Spring Data to allow support for potentially any Graph database that implements the TinkerPop Blueprints 2.x API.
*   [blueprints-scala (⭐77)](https://github.com/anvie/blueprints-scala) - TinkerPop Blueprints Scala.

## <A NAME="communites"></A>Communities

*   [Gremlin-users](https://groups.google.com/forum/#!forum/gremlin-users) - Mailing list for Gremlin users.
*   [Stack Overflow](http://stackoverflow.com/questions/tagged/tinkerpop3) - Stack Overflow has a relatively active community.
*   [TinkerPop-dev](http://mail-archives.apache.org/mod_mbox/incubator-tinkerpop-dev/) - Mailing list for TP3 deverlopers.

## <A NAME="people-to-follow"></A>People to Follow

*   [Marko Rodriguez](https://markorodriguez.com/) - Founder of TinkerPop and Aurelius.
*   [Stephen Mallette](https://twitter.com/spmallette?lang=en-gb) - Senior developer for Gremlin, TinkerPop and Titan DB.
*   [Daniel Kuppitz](https://about.me/daniel.kuppitz) - One of the main developers of Gremlin.
*   [Jason Plurad](https://github.com/pluradj) - Senior Developer at IBM. TinkerPop committer and active on the community.

## <A NAME="tutorials-and-resources"></A>Tutorials and Resources

*   [Introduction to Gremlin](http://tinkerpop.apache.org/gremlin.html) - Official introduction to the Gremlin language.
*   [Datastax Introduction](https://academy.datastax.com/resources/getting-started-tinkerpop-and-gremlin) - A tutorial provided by Datastax to Gremlin and TinkerPop3.
*   [TinkerPop Book](http://www.tinkerpopbook.com/) - A long promised book for Tinkeprop but never fulfilled until now. You cans till request a notification.
*   [Linux Foundation Presentation](http://events.linuxfoundation.org/sites/events/files/slides/ApacheCon2015TinkerPop3.pdf) - A presentation by Linux Foundation given by David Robinson at IBM aboit Apache TinkerPop3.
*   [Getting Started with TinkerPop](http://tinkerpop.apache.org/docs/current/tutorials/getting-started/) - Learn the basics of getting up and going with TinkerPop.
*   [The Gremlin Console](http://tinkerpop.apache.org/docs/current/tutorials/the-gremlin-console/) - Discusses uses cases of the Gremlin Console and usage patterns.
*   [Gremlin Recipes](http://tinkerpop.apache.org/docs/3.2.1-SNAPSHOT/recipes/) - Reference for common traversal patterns and style.
*   [Gremlin Language Variants](http://tinkerpop.apache.org/docs/3.2.1-SNAPSHOT/tutorials/gremlin-language-variants/) - Learn how to embed Gremlin in a host programming language.
*   [SQL2Gremlin](http://sql2gremlin.com/) - Learn Gremlin using typical patterns found when querying data with SQL.
*   [Getting Started with Graph Databases](https://academy.datastax.com/demos/getting-started-graph-databases) - Compares relational databases to graph databases and SQL to Gremlin.
*   [Graph (⭐736)](https://github.com/krlawrence/graph) - Graph Databases, Gremlin and TinkerPop - A Tutorial.

## <A NAME="contributing"></A>How to Contribute

![alt tag](https://github.com/mohataher/awesome-tinkerpop/raw/master/awesome-tinkerpop.jpg)

Please follow the [guidelines here](https://github.com/mohataher/awesome-tinkerpop/blob/master/README.md/contributing.md). Please, make sure your contribution and PR are awesome!

## <A NAME="license"></A>License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [@mohataher](https://github.com/mohataher) has waived all copyright and related or neighboring rights to this work.

