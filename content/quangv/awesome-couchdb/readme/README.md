# Awesome Couchdb Overview

CouchDB - curated meta resources & best practices list

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/quangv/awesome-couchdb/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 quangv/awesome-couchdb](https://github.com/quangv/awesome-couchdb) · ⭐ 159 · 🏷️ Databases

[ [Daily](/content/quangv/awesome-couchdb/README.md) / [Weekly](/content/quangv/awesome-couchdb/week/README.md) / Overview ]

---

<p>
  <br>
  <img width="300" src="https://rawgit.com/quangv/awesome-couchdb/master/logo--couch.png" alt="awesome couchdb logo">
  <br>
</p>

# Awesome CouchDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

> A curated meta resources & best practices list for CouchDB.

**[CouchDB](http://couchdb.apache.org/)** is a document-oriented NoSQL database that syncs.

Pull-Requests are welcomed.

## Contents

*   [News & Blog Posts](#news--blog-posts)
*   [Patterns & Best Practices](#patterns--best-practices)
    *   [Map/Reduce](#mapreduce)
    *   [Joins](#joins)
    *   [Document Versioning](#document-versioning)
*   [Blogs](#blogs)
*   [Docs](#docs)
*   [Books](#books)
*   [Videos](#videos)
*   [Libraries](#libraries)
*   [Community](#community)
    *   [Mailing List](#mailing-list)
    *   [Companies](#companies)
        *   [Hosting](#hosting)
    *   [Related Projects](#related-projects)
*   [Misc/Technical](#misctechnical)
    *   [Attachments](#attachments)
    *   [Backups](#backups)
    *   [CouchApps](#couchapps)
    *   [Scaling](#scaling)
*   [Resource Lists](#resource-lists)
*   [License](#license)

## News & Blog Posts

*   [MiniCouchDB in Rust](https://www.garrensmith.com/blogs/mini-couch-hack-week)
*   [The Road to CouchDB 3.0: Prepare for 4.0](https://blog.couchdb.org/2020/02/26/the-road-to-couchdb-3-0-prepare-for-4-0/) *(02-26-2020)*

## Patterns & Best Practices

*   [Best Practices](http://ehealthafrica.github.io/couchdb-best-practices/) - Best Practices, eHealth Africa.
*   [Pagination strategies with PouchDB ](https://pouchdb.com/2014/04/14/pagination-strategies-with-pouchdb.html)
*   [12 pro tips for better code with PouchDB](https://pouchdb.com/2014/06/17/12-pro-tips-for-better-code-with-pouchdb.html)
*   [Linux tuning for better CouchDB performance (⭐34)](https://github.com/assafmo/couchdb-linux-performance)

### Map/Reduce

*   [PouchDB - Secondary Indexes](https://pouchdb.com/2014/05/01/secondary-indexes-have-landed-in-pouchdb.html)
*   [Cloudant - MapReduce Primer](https://cloudant.com/blog/mapreduce-from-the-basics-to-the-actually-useful/#.WIDBfRsrKUl) - Great intro on reduce, group, group\_level.
*   [Using View Collation](http://docs.couchdb.org/en/2.0.0/couchapp/views/joins.html#using-view-collation) - Index mapping (emits) for data joins.
*   [Views Collation](http://docs.couchdb.org/en/2.0.0/couchapp/views/collation.html) - More documentation on "View Collation".
*   [Cloudant - MapReduce and the Secondary Index (Video)](https://developer.ibm.com/clouddataservices/docs/cloudant/get-started/mapreduce-and-the-secondary-index/) - Great videos here on mapReduce, secondary indexes, and complex keys.
*   [Cloudant - Design Documents](https://docs.cloudant.com/design_documents.html) - Cloudant's documentation is also great resource for learning concepts of CouchDB.
*   [Cloudant - Design Document Management](https://docs.cloudant.com/design_document_management.html) - How to manage design doc changes in production.

### Joins

*   [Joins with Views](http://docs.couchdb.org/en/2.0.0/couchapp/views/joins.html#joins-with-views) - Must read for understanding approach on doing efficient joins for CouchDB/PouchDB.
*   [Grouping related documents together in Cloudant](https://docs.cloudant.com/transactions.html) - An approach that leverages CouchDB high availability nature.

### Document Versioning

*   [Document Revisions (from wiki)](https://wiki.apache.org/couchdb/Document_revisions?action=show\&redirect=DocumentRevisions)
*   [Simple Document Versioning](http://web.archive.org/web/20100701165612/http://blog.couch.io/post/632718824/simple-document-versioning-with-couchdb)

## Blogs

*   [Official Blog](https://blog.couchdb.org/)

## Docs

*   [Official Docs](http://docs.couchdb.org/)
*   [FAQ (old wiki)](https://wiki.apache.org/couchdb/Frequently_asked_questions) - Seems to have more faqs than the [new wiki](https://cwiki.apache.org/confluence/display/COUCHDB/Frequently+Asked+Questions).

## Books

*   [The Definitive Guide](http://guide.couchdb.org/) - CouchDB's *"Dog"* Book.
*   [List of books on the Wiki](https://cwiki.apache.org/confluence/display/COUCHDB/Books)

## Videos

*   [10 Common Misconceptions](https://www.youtube.com/watch?v=BKQ9kXKoHS810) - More videos from this [conference](http://conf.couchdb.org/).
*   [The NoSQL Tapes](http://nosqltapes.com) - CouchDB is discussed on [Volume 5 - CouchDB](http://nosqltapes.com/video/hoffman-and-kocoloski-on-cloudant-and-couchdb), [Volume 8 - MapReduce](http://nosqltapes.com/video/understanding-mapreduce-with-mike-miller).
*   [Scaling Out with BigCouch](http://www.oreilly.com/pub/e/1760) - O'Reilly video on scaling out with BigCouch.
*   [IBM - The New Builders Webinar Series](https://event.on24.com/eventRegistration/EventLobbyServlet?target=reg20.jsp\&partnerref=cdc\&eventid=1240121\&sessionid=1\&key=9E23B44802902EAD0BB2603F0434742E\&regTag=35370\&sourcepage=register)

## Libraries

*   [Jaki (⭐17)](https://github.com/pandeiro/jaki) - A simple ClojureScript CouchDB client

## Community

*   [IRC](http://webchat.freenode.net/?channels=couchdb) - `irc://irc.freenode.net/couchdb`
*   [Apache CouchDB Conf](http://conf.couchdb.org/) - Lots of video links.
*   [Bylaws](http://couchdb.apache.org/bylaws.html), [Minutes](https://whimsy.apache.org/board/minutes/CouchDB.html)

### Mailing List

> -dev is where developers of couchdb chat, -user is where users of couchdb chat
> and there's some crosstalk ofc
> -dev is appropriate if you're talking about changes to couchdb itself ("developer" doesn't mean you have to have a commit bit or anything) -rnewson

*   [Mailing Lists](https://mail-archives.apache.org/mod_mbox/#couchdb)
*   [Mailing Lists Description](http://svn.apache.org/repos/asf/couchdb/site/htdocs/community/lists.html?p=900000)
*   [Grokbase](http://grokbase.com/s/couchdb) - Mailing lists in a [Stack Overflow](http://stackoverflow.com/questions/tagged/couchdb)-like interface.

[:star2:**The** ***Amazing*** **CouchDB Committers** *and* **Project Managers** :heart\_eyes\_cat:](http://people.apache.org/committers-by-project.html#couchdb)

### Companies

*   [eHealth Africa](https://github.com/eHealthAfrica) - Big user of CouchDB, check out their [best practices (⭐311)](https://github.com/eHealthAfrica/couchdb-best-practices).

#### Hosting

*   [Cloudant](https://cloudant.com/) - Distributed database as a service (DBaaS).
*   [Fly.io](https://fly.io) use this [Guide](https://www.canrau.com/en/fly-couchdb) to host
*   [Bitnami Launchpad for Google Cloud Platform](https://bitnami.com/stack/couchdb/cloud/google) - Host CouchDB on Google Cloud Platform.

### Related Projects

*   [PouchDB](https://pouchdb.com/) - A pocket-sized database.
*   [FoundationDB](https://www.foundationdb.org/) - CouchDB 4.0 will utilize FoundationDB.
*   [Hoodie](http://hood.ie/) - A backend for Offline First applications.
*   [Couchbase](https://www.couchbase.com/) - NoSQL database.
    *   [Migrating from Apache CouchDB](https://docs.couchbase.com/server/current/install/migrate-couchdb.html) - Comparison of CouchDB and CouchBase
*   [RxDB](https://rxdb.info/) - NoSQL-database for JavaScript Applications. RxDB provides modules for realtime replication with any CouchDB compliant endpoint and also with custom GraphQL endpoints.

## Misc/Technical

*   [Dynamo and CouchDB Clusters](https://web.archive.org/web/20160311144130/https://cloudant.com/blog/dynamo-and-couchdb-clusters/#.WIEp4xsrKUk) - Article about scaling CouchDB, using clusters.
*   [Google’s paper on Sawzall](http://research.google.com/archive/sawzall.html) - Exotic Reductions Examples.
*   [What Every Developer Should Know About CouchDB](http://www.dimagi.com/blog/what-every-developer-should-know-about-couchdb/) - Article about lessons learned.
*   [CouchDB Maximum Database Size](http://www.nosql.se/2011/09/couchdb-maximum-database-size/)
*   [NOSQL Patterns](http://horicky.blogspot.com/2009/11/nosql-patterns.html)
*   [Persistent Trees in git, Clojure and CouchDB](https://eclipsesource.com/blogs/2009/12/13/persistent-trees-in-git-clojure-and-couchdb-data-structure-convergence/)
*   [CouchDB - JSON and B-trees and REST, oh my!](https://pozorvlak.livejournal.com/176385.html)

### Attachments

*   [PouchDB - Attachments are overrated](https://pouchdb.com/2014/06/17/12-pro-tips-for-better-code-with-pouchdb.html) - *"Update: since this post was written, the stability and performance of attachments in PouchDB has greatly improved. ..."*
*   [Cloudant - Attachments Performance Considerations](https://docs.cloudant.com/attachments.html#performance-considerations)
*   [Are attachments duplicated for each revision?](http://grokbase.com/t/couchdb/user/14a1phbzrb/are-attachments-duplicated-for-each-revision-as-well) - Mailing list discussion about attachments across revisions.

### Backups

*   [Simple CouchDB and Cloudant Backup](https://developer.ibm.com/clouddataservices/2016/03/22/simple-couchdb-and-cloudant-backup/) - Article on IBM about backups.
*   [Cloudant Backup Guide](https://docs.cloudant.com/backup-guide.html) - Cloudant docs on backups.

### CouchApps

*   [List of CouchApps](https://couchapp.readthedocs.io/en/latest/user/list-of-couchapps.html)
*   [Ddoc Lab](http://ddoc.me/) - Create couchapps and CouchDB design docs right in your browser.

### Scaling

*   [Bitnami CouchDB](https://bitnami.com/stack/couchdb) - Bitnami makes it easy to run CouchDB in the cloud.

## Resource Lists

*   [Official CouchDB Wiki](https://cwiki.apache.org/confluence/display/COUCHDB/Apache+CouchDB+Wiki)
*   [Official CouchDB Wiki (old)](https://wiki.apache.org/couchdb/) - Some things aren't on new wiki yet.
*   [Cloudant Official Guides](https://docs.cloudant.com/guides.html) - Applicable to CouchDB.
*   [List of CouchDB Clients](https://cwiki.apache.org/confluence/display/COUCHDB/CouchDB+clients)
*   [List of CouchDB Useful Utilities](https://cwiki.apache.org/confluence/display/COUCHDB/Useful+utilities)
*   [Old Wiki's Related Projects List](https://wiki.apache.org/couchdb/Related_Projects)

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

