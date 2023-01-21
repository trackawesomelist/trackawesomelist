# Awesome Nosql Guides Overview

:computer: Curated list of awesome resources and links about using NoSQL databases

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/erictleung/awesome-nosql-guides/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 erictleung/awesome-nosql-guides](https://github.com/erictleung/awesome-nosql-guides) · ⭐ 184 · 🏷️ Databases

[ [Daily](/content/erictleung/awesome-nosql-guides/README.md) / [Weekly](/content/erictleung/awesome-nosql-guides/week/README.md) / Overview ]

---

# Awesome NoSQL Guides [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated list of resources and links about *using* NoSQL databases and things to look for when deciding to use one.

A basic definition of NoSQL databases can be found on Wikipedia as:

> "A NoSQL (originally referring to 'non SQL' or 'non relational') database provides a mechanism for storage and retrieval of data which is modeled in means other than the tabular relations used in relational databases."

For actual NoSQL databases, you can go
[here (⭐223k)](https://github.com/sindresorhus/awesome#databases),
[here](https://hostingdata.co.uk/nosql-database/),
[here](https://db-engines.com/en/ranking),
[here](https://dbdb.io/),
[here (⭐4.5k)](https://github.com/igorbarinov/awesome-data-engineering#databases), or
[here (⭐22k)](https://github.com/kahun/awesome-sysadmin#nosql). Also, not to be confused with the relational database management system, [NoSQL](http://www.strozzi.it/cgi-bin/CSA/tw7/I/en_US/nosql/Home%20Page).

## Contents

*   [Overview of NoSQL](#overview-of-nosql)
*   [Data Structures and Modeling](#data-structures-and-modeling)
*   [Trade-Offs in CAP/Brewer's Theorem](#trade-offs-in-capbrewers-theorem)
*   [Crowd-Sourced Information](#crowd-sourced-information)
*   [Graph Databases](#graph-databases)
*   [Criticisms and Debates](#criticisms-and-debates)
*   [Miscellaneous](#miscellaneous)

## Overview of NoSQL

*   [Introduction To NoSQL - Martin Fowler (54:52)](https://www.youtube.com/watch?v=qI_g07C_Q5I) - Talk given at GOTO 2012 as a great introduction to NoSQL databases, the types of NoSQL databases, their history, pros and cons, and how and when to use them.
*   [NoSQL Distilled](https://martinfowler.com/books/nosql.html) - Very digestable and affordable book describing the different NoSQL databases and help you make the decision on whether using a NoSQL database is appropriate for your project.
*   [Seven Databases in Song (1:43)](https://www.youtube.com/watch?v=jyx8iP5tfCI) - Fun song from 2012 about seven (six are NoSQL) databases with a very condensed overview of how they each work.
*   [NoSQL Databases: a Survey and Decision Guidance (2016)](https://medium.baqend.com/nosql-databases-a-survey-and-decision-guidance-ea7823a822d) - "This NoSQL Toolbox allows us to derive a simple decision tree to help practitioners and researchers filter potential system candidates based on central application requirements".
*   [Data Management in the Cloud: Limitations and Opportunities (PDF)](http://www.cs.umd.edu/\~abadi/papers/abadi-cloud-ieee09.pdf) - Abadi (2009) discusses limitations and opportunities of data management and data analysis in the cloud.
*   [10 NoSQL Misconceptions](https://web.archive.org/web/20210701080816/https://www.dummies.com/programming/big-data/10-nosql-misconceptions/) - Some misconceptions about NoSQL databases relating to topics such as what they are, ACID-compliance, and security.
*   [10 Reasons Developers Love NoSQL](https://web.archive.org/web/20210701080841/https://www.dummies.com/programming/big-data/10-reasons-developers-love-nosql/) - A list of ten arguments for why developers like to use NoSQL databases.
*   [Distribution, Data, Deployment: Software Architecture Convergence in Big Data Systems (PDF)](https://resources.sei.cmu.edu/library/asset-view.cfm?assetID=90909) - Gorton and Klein (2014) paper to discuss software engineering concerns when dealing with big data systems in terms of distribution, data, and deployment. Also accessible [here](https://doi.org/10.1109/MS.2014.51).
*   [Use cases for NoSQL (2017)](https://stackoverflow.com/questions/2875432/use-cases-for-nosql) - Discussion on Stack Overflow on best use cases for using NoSQL databases over traditional SQL databases.
*   [Five Common Data Stores and When to Use Them (2019)](https://shopify.engineering/five-common-data-stores-usage) - Article describes five common data stores (relational database, non-relational (“NoSQL”) database, key-value store, full-text search engine, message queue) and their attributes.
*   [NoSQL Databases (PDF)](https://web.archive.org/web/20190927222738/https://www.christof-strauch.de/nosqldbs.pdf) - A 149-page document outlining motives and rationale for NoSQL databases, and common concepts, techniques and patterns among these databases; last updated around 2011.
*   [NoSQL Data Architecture & Data Governance: Everything You Need to Know (2018)](https://www.dataversity.net/nosql-data-architecture-data-governance-everything-need-know/) - Overview of different NoSQL database architectures with diagrams.
*   [NoSQL vs SQL: Demystifying NoSQL Databases (2019)](https://build5nines.com/nosql-vs-sql-demystifying-nosql-databases/) - General overview and examples of NoSQL database schema types, while covering CAP theorem tradeoffs.
*   [Comparing Database Types: How Database Types Evolved to Meet Different Needs](https://www.prisma.io/dataguide/intro/comparing-database-types) - Good overview of databases in general and how NoSQL database types differ and can be useful.
*   [The NoSQL Ecosystem](https://www.aosabook.org/en/nosql.html) - A chapter written by Adam Marcus from "The Architecture of Open Source Applications" book, this chapter is geared more towards systems architects needing to learn more in-depth understanding of how these systems are built.
*   [What is NoSQL - Amazon AWS](https://aws.amazon.com/nosql/) - Great high-level overview of NoSQL databases and how they compare to SQL database technologies and terminologies.  Serves as landing page for Amazon's AWS services for NoSQL options of key-value (Amazon DynamoDB), document (Amazon DocumentDB), graph (Amazon Neptune), in-memory (Amazon ElastiCache), and search-engine (Amazon Elasticsearch) database.
*   [NoSQL vs. SQL: Important Differences & Which One Is Best for Your Project (2021) - Upwork](https://www.upwork.com/resources/nosql-vs-sql) - Explanation comparing SQL and NoSQL databases, along with giving some advice on what database solution is right for your use case.
*   [NoSQL Database Tutorial – Full Course for Beginners (2:54:52)](https://www.youtube.com/watch?v=xh4gy1lbL2k) - Ania Kubow reviews the four types of NoSQL databases and provides two hands-on projects to experiment with what was reviewed.

## Data Structures and Modeling

*   [Structure Your Database](https://firebase.google.com/docs/database/android/structure-data) - Best practices (as of 2018) of structuring your data if your database uses JSON.
*   [NoSQL Data Modeling Techniques (2012)](https://highlyscalable.wordpress.com/2012/03/01/nosql-data-modeling-techniques/) - This article provides a short comparison of NoSQL system families from the data modeling point of view and digests several common modeling techniques.
*   [Data Models For MongoDB](https://www.mongodb.com/docs/manual/data-modeling/) - Data modeling help specific to MongoDB, ranging from schema validation and example patterns. However, concepts may carry over to other document NoSQL databases.
*   [Data Models Will Be Beautiful Again (2016)](https://tdwi.org/articles/2016/11/22/data-models-will-be-beautiful-again.aspx) - Essay argues that despite existing schema-less databases, thoughtful database modeling is important to gain knowledge and insights using algorithms.
*   [Unified Data Modeling for Relational and NoSQL Databases](https://www.infoq.com/articles/unified-data-modeling-for-relational-and-nosql-databases/) - Solution for managing both NoSQL and relational databases using the Unified Data Modeling technique.
*   [Unifying Relational, Document, Graph, and Temporal Data Models](https://fauna.com/blog/unifying-relational-document-graph-and-temporal-data-models) - Patterns for querying across multiple paradigms in the same database.
*   [How To Design Schema For Your NoSQL Database?](https://www.dataversity.net/how-to-design-schema-for-your-nosql-database/#) - Despite popular belief that NoSQL are schema-less, this article outlines how NoSQL databases follow "query driven design" and considerations for this flexibility in schema.
*   [Best Practices for NoSQL Database Design (2012)](https://softwareengineering.stackexchange.com/q/158790/) - A couple answers and links for NoSQL database design.

## Trade-Offs in CAP/Brewer's Theorem

*   [Visual Guide To NoSQL Systems (2010)](http://blog.nahurst.com/visual-guide-to-nosql-systems) - Visual display of trade-offs in the CAP theorem among different NoSQL databases.
*   [How to Choose The Right NoSQL Database For Your Application? (2018)](https://www.dataversity.net/choose-right-nosql-database-application/) - Reviews CAP theorem and maps common NoSQL databases to CAP categories to help choose one.

## Crowd-Sourced Information

*   [/r/nosql](https://www.reddit.com/r/nosql/) - Reddit page on NoSQL on general questions and discussions people may have about NoSQL databases.
*   [\[nosql\] Tag On Stack Overflow](https://stackoverflow.com/tags/nosql/info)
*   [Ask HN: Learning NoSQL, Papers and Books (2017)](https://news.ycombinator.com/item?id=15427932) - "In your opinion, which papers and books are mandatory to really understand NoSQL subject?"
*   [Difference Between Scaling Horizontally And Vertically For Databases](https://stackoverflow.com/q/11707879/6873133) - Common terms talked about in the database world and here are answers from others.
*   [NoSQL - Wikipedia](https://en.wikipedia.org/wiki/NoSQL) - Wikipedia entry on all things NoSQL databases.

## Graph Databases

*   [Graph Databases Use Cases](https://neo4j.com/use-cases/) - Although documents geared towards Neo4j, concepts are applicable to all graph databases.
*   [How The ICIJ Used Neo4j To Unravel The Panama Papers - Mar Cabra (32:02)](https://www.youtube.com/watch?v=S20XMQyvANY) - Learn how graph databases were key to explore who were the main names connected to companies in tax havens, including 140 politicians in more than 50 countries.
*   [Graph Databases For Beginners: The Basics Of Data Modeling](https://neo4j.com/blog/data-modeling-basics/) - Discusses the basics of modeling your data and which approach you should take.
*   [Graph Data Modeling Guidelines](https://neo4j.com/developer/guide-data-modeling/) - Directly related to Neo4j, but possibly applicable to any graph database.
*   [Graph Data Modeling Visualize Structure and Meaning](http://www.graphdatamodeling.com) - Brief introduction to graph data modeling and is an introduction to the book "Graph Data Modeling for NoSQL and SQL" by Thomas Frisendal.

## Criticisms and Debates

*   [Addressing the NoSQL Criticism (2011)](https://www.bradley-holt.com/2011/07/addressing-the-nosql-criticism/) - Argues against nine criticisms to NoSQL databases as they apply to CouchDB, but may apply to others as well.
*   [Thank You For Your Help NoSQL, But We Got It From Here (2020)](https://web.archive.org/web/20200913032621/https://www.memsql.com/blog/why-nosql-databases-wrong-tool-for-modern-application/) - Argument that NoSQL databases have pushed the evolution of databases given the problem of scaling, but now NewSQL has addressed those concerns (from the perspective of MemSQL).
*   [The Five Stages Of NoSQL (2016)](https://sookocheff.com/post/opinion/the-five-stages-of-nosql/) - Stages of going through picking and using a NoSQL database mirroring the five stages of grief.
*   [The Biggest Challenges Of Moving To NoSQL (2017)](https://dzone.com/articles/the-biggest-challenges-of-moving-to-nosql) - Speed and scalability and developer joy have been the gains found from enduring through challenges of moving to NoSQL.

## Miscellaneous

*   [What As A NoSQL Database? Learn By Writing One In Python](https://web.archive.org/web/20201109032031/https://jeffknupp.com/blog/2014/09/01/what-is-a-nosql-database-learn-by-writing-one-in-python/) - Excellent tutorial in learning NoSQL vs RDBMS through building a toy database using Python.
*   [Dynamo Vs Cassandra : Systems Design Of NoSQL Databases](https://sujithjay.com/data-systems/dynamo-cassandra/) - Blog post comparing and constrating system designs of two well known NoSQL databases.
*   [Why You Should Build Your Wwn NoSQL Database](https://medium.com/@marceloboeira/why-you-should-build-your-own-nosql-database-9bbba42039f5) - Brief overview of NoSQL databases and the spectrum of schema, along with a very basic implementation of a NoSQL database using the Crystal programming language.
*   [PostgreSQL, The NoSQL Database (2015)](https://www.linuxjournal.com/content/postgresql-nosql-database) - An argument for PostgreSQL being an alternative to NoSQL databases with NoSQL-like features using its new features like HStore (key-value store) and JSONB (document-based) as of Version 9.4.

