# Awesome Rethinkdb Overview

A curated list of awesome RethinkDB resources, libraries, tools and applications

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/d3viant0ne/awesome-rethinkdb/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 d3viant0ne/awesome-rethinkdb](https://github.com/d3viant0ne/awesome-rethinkdb) · ⭐ 109 · 🏷️ Databases

[ [Daily](/content/d3viant0ne/awesome-rethinkdb/README.md) / [Weekly](/content/d3viant0ne/awesome-rethinkdb/week/README.md) / Overview ]

---

<h3 align="center">
	<img width="120" src="https://github.com/d3viant0ne/awesome-rethinkdb/raw/master/media/rethinkdb.jpg" alt="RethinkDB">
	<br>
</h3>
## Awesome RethinkDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome RethinkDB resources, libraries, tools and applications

Inspired by the [awesome (⭐223k)](https://github.com/sindresorhus/awesome) list. Feel free to improve this list by [contributing](https://github.com/d3viant0ne/awesome-rethinkdb/blob/master/README.md/CONTRIBUTING.md)!

### Table of Contents

*   [Resources](#resources)
*   [Documentation](#documentation)
*   [Community](#community)
*   [JavaScript](#javascript-libraries)
*   [Python](#python-libraries)
*   [Ruby](#ruby-libraries)
*   [Java](#java-libraries)
*   [Additional Languages](#additional-languages)
*   [Community Supported](#community-supported-drivers)
*   [Research and Training](#research-and-training)
*   [Articles](#articles)
*   [Talks](#talks)
*   [RethinkDB Examples](#rethinkdb-examples)
*   [Community Examples](#community-examples)
*   [Tools](#tools)
*   [Administration](#administrative-tools)
*   [Deployment](#deployment)

<br>
> <h3>RethinkDB Ecosystem</h3>

#### Documentation

*   [RethinkDB](http://rethinkdb.com/docs/) - RethinkDB Documentation
*   [ReQL API](http://rethinkdb.com/api/javascript/) - JavaScript ReQL command reference

#### Community

*   [Request Slack Invite](http://slack.rethinkdb.com/)
*   [RethinkDB StackOverflow](http://stackoverflow.com/tags/rethinkdb)
*   [RethinkDB Blog](https://www.rethinkdb.com/blog/)
*   [RethinkDB Google Group](https://groups.google.com/forum/#!forum/rethinkdb)
*   [RethinkDB YouTube Channel](https://www.youtube.com/channel/UC1kJkmSWt_snLDfuXgJnLnQ)
*   [RethinkDB Reddit](https://www.reddit.com/r/rethinkdb/)

<br>
> <h3>JavaScript Libraries</h3>

##### Drivers

*   [RethinkDB JavaScript](https://www.rethinkdb.com/docs/install-drivers/javascript/) - Officially Supported JavaScript Driver.
*   Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)
*   [RethinkDB Dash (⭐854)](https://github.com/neumino/rethinkdbdash) - An advanced Node.js driver for RethinkDB with connection pool and Streams Support.
*   Maintainer: `Michel`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/neumino) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/neumino)

##### ORM

*   [Thinky (⭐1.1k)](https://github.com/neumino/thinky) - JavaScript ORM for RethinkDB
*   Maintainer: `Michel`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/neumino) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/neumino)
*   [JSData RethinkDB (⭐32)](https://github.com/js-data/js-data-rethinkdb) - RethinkDB adapter for the js-data ORM.
*   Maintainer: `JS Data Organization`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/js-data)

##### Extension Libraries

*   [RethinkDB Pool (⭐20)](https://github.com/hden/rethinkdb-pool) - Connection-pool for RethinkDB.
*   Maintainer: `Hao-kang Den`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/hden)
*   [Express Session RethinkDB (⭐25)](https://github.com/armenfilipetyan/express-session-rethinkdb) - RethinkDB session store for Express 4.x.
*   Maintainer: `@armenfilipetyan`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/armenfilipetyan)

##### Technology Integrations

*   [Hapi RethinkDB CRUD (⭐3)](https://github.com/athlite/hapi-rethinkdb-crud) - CRUD handlers for Hapi interaction with Rethinkdb.
*   Maintainer: `Thomas Eng`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/athlite)
*   [Sails Hook Thinky (⭐19)](https://github.com/mwielbut/sails-hook-thinky) - A hook to enable the Thinky ORM for RethinkDB in Sails.
*   Maintainer: `Matt Wielbut`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/mwielbut) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/mwielbut)
*   [KOA RethinkDB (⭐17)](https://github.com/hden/koa-rethinkdb) - Koa middleware that gets you a RethinkDB client.
*   Maintainer: `Hao-kang Den`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/hden)
*   [RabbitMQ](http://rethinkdb.com/docs/rabbitmq/javascript/) - Integrating RethinkDB with RabbitMQ
*   Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)

**[Back to top](#table-of-contents)**

<br>
> <h3>Python Libraries</h3>

##### Drivers

*   [RethinkDB Python](https://www.rethinkdb.com/docs/install-drivers/python/) - Officially Supported JavaScript Driver.
*   Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)

##### ORM

*   [Remodel (⭐195)](https://github.com/linkyndy/remodel) - Very simple yet powerful and extensible Object Document Mapper for RethinkDB, written in Python.
*   Maintainer: `Andrei Horak`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/linkyndy) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/linkyndy)
*   [Rethink (⭐16)](https://github.com/caoimhghin/rethink) - Python RethinkDB Object Mapper Interface Inspired by Appengine NDB.
*   Maintainer: `Kevin Amerson`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/caoimhghin) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/kevinamerson)

##### Technology Integrations

*   [flask-rethinkdb (⭐27)](https://github.com/linkyndy/flask-rethinkdb) - Adds RethinkDB support to Flask.
*   Maintainer: `Andrei Horak`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/linkyndy) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/linkyndy)
*   [RabbitMQ](https://www.rethinkdb.com/docs/rabbitmq/python/) - Integrating RethinkDB with RabbitMQ
*   Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)

**[Back to top](#table-of-contents)**

<br>
> <h3>Ruby Libraries</h3>

##### Drivers

*   [RethinkDB Ruby](http://rethinkdb.com/docs/install-drivers/ruby/) - Officially Supported Ruby Driver.
*   Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)

##### ORM

*   [NoBrainer (⭐387)](https://github.com/nviennot/nobrainer) - Ruby ORM for RethinkDB.
*   Maintainer: `Nicolas Viennot`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/nviennot) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/nviennot)

##### Technology Integrations

*   [Epiphy (⭐8)](https://github.com/kureikain/epiphy) - Lightweight RethinkDB ORM.
*   Maintainer: `Vinh Quốc Nguyễn`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/kureikain) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/kureikain)
*   [lotus-rethinkdb (⭐6)](https://github.com/angeloashmore/lotus-rethinkdb) - RethinkDB adapter for Lotus::Model.
*   Maintainer: `Angelo Ashmore`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/angeloashmore) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/angeloashmore)
*   [RabbitMQ](https://www.rethinkdb.com/docs/rabbitmq/ruby/) - Integrating RethinkDB with RabbitMQ
*   Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)

**[Back to top](#table-of-contents)**

<br>
> <h3>Java Libraries</h3>

##### Drivers

*   [RethinkDB Java](http://rethinkdb.com/docs/install-drivers/java/) - Officially Supported Java Driver.
*   Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)
*   [Rethinker (⭐1)](https://github.com/futurechimp/rethinker) - A simplistic serialisation library for use alongside the official RethinkDb Java driver.
*   Maintainer: `Dave Hrycyszyn`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/futurechimp) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/futurechimp)
*   [Rethinkdb4j (⭐1)](https://github.com/tony-brewerio/rethinkdb4j) - Asynchronous Netty-based RethinkDB driver for Java.
*   Maintainer: `Anton Ustyuzhanin`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/tony-brewerio)

##### ORM

*   [RethinkDB Java ORM (⭐2)](https://github.com/PeterKnego/rethinkdb-java-orm) - A custom POJO converter for RethinkDB Java driver.
*   Maintainer: `Peter Knego`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/PeterKnego) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/peterknego)

##### Technology Integrations

*   [RabbitMQ](https://www.rethinkdb.com/docs/rabbitmq/java/) - Integrating RethinkDB with RabbitMQ
*   Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/raw/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)

**[Back to top](#table-of-contents)**

<br>
> <h3>Additional Languages</h3>

#### Community Supported Drivers

*   [C# (⭐373)](https://github.com/bchavez/RethinkDb.Driver) - A C#/.NET RethinkDB driver striving for 100% ReQL API coverage.
*   [C++ (⭐91)](https://github.com/AtnNn/librethinkdbxx) - RethinkDB driver for C++.
*   [Clojure (⭐199)](https://github.com/apa512/clj-rethinkdb) - A RethinkDB client for Clojure.
*   [Dart (⭐37)](https://github.com/billysometimes/rethinkdb) - A Dart driver for RethinkDB v2.0.3.
*   [Elixir (⭐498)](https://github.com/hamiltop/rethinkdb-elixir) - Multiplexed RethinkDB client in pure Elixir.
*   [Go (⭐1.6k)](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB.
*   [Haskell (⭐92)](https://github.com/AtnNn/haskell-rethinkdb) - RethinkDB client library for Haskell.
*   [Lisp (⭐44)](https://github.com/orthecreedence/cl-rethinkdb) - RethinkDB driver for Common Lisp.
*   [Lua](https://github.com/grandquista/Lua-ReQL) - Rethinkdb driver in Lua.
*   [Objective-C (⭐13)](https://github.com/dparnell/rethink-db-client) - A RethinkDB client written in Objective-C.
*   [Perl (⭐21)](https://github.com/njlg/perl-rethinkdb) - A Pure Perl RethinkDB Driver.
*   [PHP (⭐343)](https://github.com/danielmewes/php-rql) - A PHP client driver for the RethinkDB query language (ReQL).
*   [Scala (⭐100)](https://github.com/kclay/rethink-scala) - Scala Driver for RethinkDB.

**[Back to top](#table-of-contents)**

<br>
> <h3> Research And Training</h3>

#### Articles

*   [Shahid Shaikh | 08-Mar-16](https://codeforgeek.com/2016/03/building-real-time-polling-app-rethinkdb-nodejs/) - Building real time polling app using RethinkDB and Nodejs.
*   [Dr. Gleb Bahmutov PhD | 08-Feb-16](https://glebbahmutov.com/blog/redux-and-rethinkdb/) - Redux and RethinkDB
*   [Scott Hasbrouck | 13-Mar-16](http://www.scotthasbrouck.com/blog/2016/3/13/using-socketio-with-rethinkdb-changefeeds-to-build-a-reactive-backend) - Using Socket.Io With RethinkDB Changefeeds To Build A Reactive JavaScript Stack
*   [Khalid Abuhakmeh | 15-Nov-15](http://www.khalidabuhakmeh.com/getting-started-with-rethinkdb-and-asp-net-5) - Getting Started With RethinkDB and ASP.NET 5.
*   [Slava Akhmechet | 01-Sept-15](http://www.infoworld.com/article/2975838/database/build-real-time-web-apps-with-rethinkdb.html) - Build real-time Web apps with RethinkDB.
*   [Justin for Fanout | 20-May-15](http://blog.fanout.io/2015/05/20/building-a-realtime-api-with-rethinkdb/) - Building a realtime API with RethinkDB.
*   [Nicholas Duffy | 30-Apr-15](https://strongloop.com/strongblog/rethinkdb-connector-loopback-node-js-framework/) - Getting Started with the RethinkDB Connector for LoopBack.
*   [Rob Conery | 17-Apr-15](http://rob.conery.io/2015/04/17/rethinkdb-2-0-is-amazing/) - RethinkDB 2.0 Is Amazing.
*   [Gordon Dent | 01-Apr-15](https://www.airpair.com/rethinkdb/posts/moving-from-sql-to-rethinkdb) - A Comprehensive Guide to moving from SQL to RethinkDB.
*   [Gordon Dent | 11-Mar-15](http://blog.workshape.io/we-use-rethinkdb-at-workshapeio/) - We use RethinkDB at Workshape.io.

#### Talks

*   [Michael Glukhovsky at Clevertech | 30-Mar-16](https://www.youtube.com/watch?v=28XKxLPv0Hs) - RethinkDB Presentation to Clevertech.
*   [Ryan Paul at ForwardJS | 21-Jan-16](https://www.youtube.com/watch?v=xCU9RHDWXIY) - RethinkDB: Database for realtime apps.
*   [Rob Conery at DevDay 2015 | 17-Sept-15](https://www.youtube.com/watch?v=Ee1v_SuECRk) - Rethinking NoSQL.
*   [Jorge Silva at RethinkDB Meetup | 29-June-15](https://www.youtube.com/watch?v=vJtDNRsUozk) - Data Modeling in RethinkDB.
*   [Ben Tranter | 05-Apr-15](https://www.youtube.com/watch?v=d01rLeIjTLE) - A Simple REST API with Express, RethinkDB, and Thinky.
*   [Associated Source (⭐6)](https://github.com/bentranter/ampersand-rethink-express)
*   [Ryan Paul at Mattermark | 17-Feb-15](https://www.youtube.com/watch?v=dhb63boH8E8) - Build a realtime RethinkDB cluster monitoring app with live graphs.
*   [Associated Blog Post](http://rethinkdb.com/blog/realtime-cluster-monitoring/) - A realtime RethinkDB cluster monitoring app with live graphs.

#### RethinkDB Examples

*   [RethinkDB NodeJS Chat (⭐205)](https://github.com/rethinkdb/rethinkdb-example-nodejs-chat) - A node.js chat application running on rethinkdb.
*   [RethinkDB Flask Backbone ToDo (⭐123)](https://github.com/rethinkdb/rethinkdb-example-flask-backbone-todo) - A canonical backbone todo application running on flask and RethinkDB.
*   [RethinkDB ccoenraets/nodecellar Fork (⭐13)](https://github.com/rethinkdb/nodecellar-rethinkdb) - Sample app built with Backbone.js,Bootstrap, Node.js, Express, RethinkDB.
*   [RethinkDB PubNub Live Blog (⭐22)](https://github.com/rethinkdb/rethinkdb-pubnub-liveblog) - PubNub / Express Blog Example App.
*   [RethinkDB Angular Express Promise (⭐138)](https://github.com/rethinkdb/rethinkdb-example-nodejs/tree/master/todo-angular-express-promise) - Promise based Todo example with RethinkDB, ExpressJS and AngularJS .
*   [RethinkDB Angular Express (⭐138)](https://github.com/rethinkdb/rethinkdb-example-nodejs/tree/master/todo-angular-express) - Todo example with RethinkDB, ExpressJS and AngularJS.
*   [RethinkDB Angular KOA (⭐138)](https://github.com/rethinkdb/rethinkdb-example-nodejs/tree/master/todo-angular-koa) - Todo example with RethinkDB, KoaJS and AngularJS.

#### Community Examples

*   [RethinkDB Chat (⭐67)](https://github.com/thejsj/rethinkdb-chat) - A simple chat applications built with RethinkDB + Sockets.
*   [RethinkDB Reactjs (⭐22)](https://github.com/arkency/rethinkdb-reactjs) - rethinkdb + react.js + ActionController::Live (Rails) + Server Side Events.
*   [Realtime Chat RethinkDB (⭐26)](https://github.com/Unrestricted-Coding/realtime-chat-RethinkDB) - A realtime chatroom built with RethinkDB
*   [Boot RethinkDB (⭐38)](https://github.com/geowarin/boot-rethinkdb) - Chat example with spring boot and RethinkDB.
*   [Go RethinkDB ToDo (⭐64)](https://github.com/dancannon/GoRethink_TodoDemo) - Go RethinkDB Todo List Example Application.
*   [Meguca (⭐406)](https://github.com/bakape/meguca) - High performance real-time imageboard in Go, TypeScript and RethinkDB.
*   [VueJS RethinkDB (⭐63)](https://github.com/alexcheninfo/vuejs-rethinkdb-example) - Vuejs + Express + RethinkDB example.
*   [3ree (⭐855)](https://github.com/GordyD/3ree) - An example universal JS application written with the 3REE stack, React + Redux + RethinkDB + Express.
*   [Meteor GraphQL (⭐44)](https://github.com/AdamBrodzinski/Meteor-RethinkDB-GraphQL) - A Meteor and RethinkDB Example Using GraphQL.

**[Back to top](#table-of-contents)**

<br>
> <h3>Tools</h3>

#### Administrative Tools

*   [Chateau (⭐207)](https://github.com/neumino/chateau) - Another (awesome) data explorer for RethinkDB.
*   [RethinkDB CLI (⭐22)](https://github.com/athlite/rethinkdb-cli) - CLI and REPL for Rethinkdb.
*   [RethinkDB Nightly](https://github.com/robconery/rethinkdb_nightly) - A node module that will execute a nightly backup and push it to S3.

#### Deployment

*   [Vagrant (⭐47)](https://github.com/RyanAmos/rethinkdb-vagrant) - Install RethinkDB using Vagrant.
*   [Puppet (⭐4)](https://github.com/tmont/puppet-rethinkdb) - Puppet module for RethinkDB.
*   [Chef (⭐15)](https://github.com/AVVSDevelopment/chef-rethinkdb) - Chef RethinkDB cookbook.
*   [Wrecker (⭐10)](https://github.com/mies/box-rethinkdb) - Wercker box for RethinkDB.
*   [Docker (⭐299)](https://github.com/crosbymichael/Dockerfiles/blob/master/rethinkdb/Dockerfile) - Single node Dockerfile.

<br>
> <h3>License</h3>

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

