# Awesome Web Archiving Overview

An Awesome List for getting started with web archiving

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/iipc/awesome-web-archiving/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 iipc/awesome-web-archiving](https://github.com/iipc/awesome-web-archiving) · ⭐ 2.5K · 🏷️ Miscellaneous

[ [Daily](/content/iipc/awesome-web-archiving/README.md) / [Weekly](/content/iipc/awesome-web-archiving/week/README.md) / Overview ]

---

<!--lint ignore awesome-github-->

# Awesome Web Archiving [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Web archiving is the process of collecting portions of the World Wide Web to ensure the information is preserved in an archive for future researchers, historians, and the public. Web archivists typically employ Web crawlers for automated capture due to the massive scale of the Web. Ever-evolving Web standards require continuous evolution of archiving tools to keep up with the changes in Web technologies to ensure reliable and meaningful capture and replay of archived web pages.

## Contents

*   [Training/Documentation](#trainingdocumentation)
    *   [Introductions to Web Archiving Concepts](#introductions-to-web-archiving-concepts)
    *   [Training Materials](#training-materials)
    *   [The WARC Standard](#the-warc-standard)
    *   [For Researchers using Web Archives](#for-researchers-using-web-archives)
*   [Resources for Web Publishers](#resources-for-web-publishers)
*   [Tools & Software](#tools--software)
    *   [Acquisition](#acquisition)
    *   [Replay](#replay)
    *   [Search & Discovery](#search--discovery)
    *   [Utilities](#utilities)
    *   [WARC I/O Libraries](#warc-io-libraries)
    *   [Analysis](#analysis)
    *   [Quality Assurance](#quality-assurance)
    *   [Curation](#curation)
*   [Community Resources](#community-resources)
    *   [Other Awesome Lists](#other-awesome-lists)
    *   [Blogs and Scholarship](#blogs-and-scholarship)
    *   [Mailing Lists](#mailing-lists)
    *   [Slack](#slack)
    *   [Discord](#discord)
    *   [Twitter](#twitter)
*   [Web Archiving Service Providers](#web-archiving-service-providers)
    *   [Self-hostable, Open Source](#self-hostable-open-source)
    *   [Hosted, Closed Source](#hosted-closed-source)
*   [Public Data](#public-data)

## Training/Documentation

This section provides a curated list of training materials, documentation, and educational resources for those interested in learning about web archiving practices, methodologies, and tools.

### Introductions to Web Archiving Concepts

*   [What is a web archive?](https://youtu.be/ubDHY-ynWi0) - A video from [the UK Web Archive YouTube Channel](https://www.youtube.com/channel/UCJukhTSw8VRj-VNTpBcqWkw)
*   [Wikipedia's List of Web Archiving Initiatives](https://en.wikipedia.org/wiki/List_of_Web_archiving_initiatives)
*   [Glossary of Archive-It and Web Archiving Terms](https://support.archive-it.org/hc/en-us/articles/208111686-Glossary-of-Archive-It-and-Web-Archiving-Terms)
*   [The Web Archiving Lifecycle Model](https://archive-it.org/blog/post/announcing-the-web-archiving-life-cycle-model/) - An attempt to incorporate the technological and programmatic arms of the web archiving into a framework that will be relevant to any organization seeking to archive content from the web. Archive-It, the web archiving service from the Internet Archive, developed the model based on its work with memory institutions around the world.
*   [Retrieving and Archiving Information from Websites by Wael Eskandar and Brad Murray](https://kit.exposingtheinvisible.org/en/web-archive.html/)

### Training Materials

*   [IIPC and DPC Training materials: module for beginners (8 sessions)](https://netpreserve.org/web-archiving/training-materials/)
*   [UNT Web Archiving Course (⭐23)](https://github.com/vphill/web-archiving-course)
*   [Continuing Education to Advance Web Archiving (CEDWARC)](https://cedwarc.github.io/)
*   [A Whirlwind Tour of Common Crawl's Datasets using Python (⭐43)](https://github.com/commoncrawl/whirlwind-python/)
*   [A Whirlwind Tour of Common Crawl's Datasets as a Python notebook (⭐3)](https://github.com/commoncrawl/whirlwind-python-notebook)
*   [A Whirlwind Tour of Common Crawl's Datasets using Java (⭐3)](https://github.com/commoncrawl/whirlwind-java/)

### The WARC Standard

*   [The warc-specifications](https://iipc.github.io/warc-specifications/) - A community HTML version of the official specification and hub for new proposals.
*   [Offical ISO 28500 WARC specification homepage](http://bibnum.bnf.fr/WARC/)

### For Researchers using Web Archives

*   [GLAM Workbench: Web Archives](https://glam-workbench.github.io/web-archives/) - See also [this related blog post on 'Asking questions with web archives'](https://netpreserveblog.wordpress.com/2020/05/28/asking-questions-with-web-archives/).
*   [Archives Unleashed Toolkit documentation](https://aut.docs.archivesunleashed.org/)
*   [Tutorial for Humanities researchers about how to explore Arquivo.pt](https://sobre.arquivo.pt/en/tutorial-for-humanities-researchers-about-how-to-use-arquivo-pt/)

## Resources for Web Publishers

These resources can help when working with individuals or organisations who publish on the web, and who want to make sure their site can be archived.

*   [Definition of Web Archivability](https://nullhandle.org/web-archivability/index.html) - This describes the ease with which web content can be preserved. ([Archived version from the Stanford Libraries](https://web.archive.org/web/20230728211501/https://library.stanford.edu/projects/web-archiving/archivability))
*   The [Archive Ready](http://archiveready.com/) tool, for estimating how likely a web page will be archived successfully.

## Tools & Software

This list of tools and software is intended to briefly describe some of the most important and widely-used tools related to web archiving. For more details, we recommend you refer to (and contribute to!) these excellent resources from other groups:

*   [Comparison of web archiving software (⭐99)](https://github.com/archivers-space/research/tree/master/web_archiving)
*   [Awesome Website Change Monitoring (⭐511)](https://github.com/edgi-govdata-archiving/awesome-website-change-monitoring)

### Acquisition

*   [ArchiveBox (⭐27k)](https://github.com/ArchiveBox/ArchiveBox) - A tool which maintains an additive archive from RSS feeds, bookmarks, and links using wget, Chrome headless, and other methods (formerly `Bookmark Archiver`). *(In Development)*
*   [archivenow (⭐432)](https://github.com/oduwsdl/archivenow) - A [Python library](http://ws-dl.blogspot.com/2017/02/2017-02-22-archive-now-archivenow.html) to push web resources into on-demand web archives. *(Stable)*
*   [ArchiveWeb.Page](https://webrecorder.net/archivewebpage/) - A plugin for Chrome and other Chromium based browsers that lets you interactively archive web pages, replay them, and export them as WARC & WACZ files. Also available as an Electron based desktop application.
*   [Auto Archiver (⭐1.1k)](https://github.com/bellingcat/auto-archiver) - Python script to automatically archive social media posts, videos, and images from a Google Sheets document. Read the [article about Auto Archiver on bellingcat.com](https://www.bellingcat.com/resources/2022/09/22/preserve-vital-online-content-with-bellingcats-auto-archiver-tool/).
*   [Browsertrix Crawler (⭐1k)](https://github.com/webrecorder/browsertrix-crawler) - A Chromium based high-fidelity crawling system, designed to run a complex, customizable browser-based crawl in a single Docker container. *(Stable)*
*   [Brozzler (⭐793)](https://github.com/internetarchive/brozzler) - A distributed web crawler (爬虫) that uses a real browser (Chrome or Chromium) to fetch pages and embedded urls and to extract links. *(Stable)*
*   [Cairn (⭐51)](https://github.com/wabarc/cairn) - A npm package and CLI tool for saving webpages. *(Stable)*
*   [Chronicler (⭐92)](https://github.com/CGamesPlay/chronicler) - Web browser with record and replay functionality. *(In Development)*
*   [Community Archive](https://www.community-archive.org/) - Open Twitter Database and API with tools and resources for building on archived Twitter data.
*   [crau (⭐64)](https://github.com/turicas/crau) - crau is the way (most) Brazilians pronounce crawl, it's the easiest command-line tool for archiving the Web and playing archives: you just need a list of URLs. *(Stable)*
*   [Crawl](https://git.autistici.org/ale/crawl) - A simple web crawler in Golang. *(Stable)*
*   [crocoite (⭐45)](https://github.com/PromyLOPh/crocoite) - Crawl websites using headless Google Chrome/Chromium and save resources, static DOM snapshot and page screenshots to WARC files. *(In Development)*
*   [DiskerNet (⭐3.9k)](https://github.com/DO-SAY-GO/dn) - A non-WARC-based tool which hooks into the Chrome browser and archives everything you browse making it available for offline replay. *(In Development)*
*   [F(b)arc (⭐78)](https://github.com/justinlittman/fbarc) - A commandline tool and Python library for archiving data from [Facebook](https://www.facebook.com/) using the [Graph API](https://developers.facebook.com/docs/graph-api). *(Stable)*
*   [freeze-dry (⭐302)](https://github.com/WebMemex/freeze-dry) - JavaScript library to turn page into static, self-contained HTML document; useful for browser extensions. *(In Development)*
*   [grab-site (⭐1.6k)](https://github.com/ArchiveTeam/grab-site) - The archivist's web crawler: WARC output, dashboard for all crawls, dynamic ignore patterns. *(Stable)*
*   [Heritrix (⭐3.2k)](https://github.com/internetarchive/heritrix3/wiki) - An open source, extensible, web-scale, archival quality web crawler. *(Stable)*
    *   [Heritrix Q\&A (⭐3.2k)](https://github.com/internetarchive/heritrix3/discussions/categories/q-a) - A discussion forum for asking questions and getting answers about using Heritrix.
    *   [Heritrix Walkthrough (⭐10)](https://github.com/web-archive-group/heritrix-walkthrough) *(In Development)*
*   [html2warc (⭐23)](https://github.com/steffenfritz/html2warc) - A simple script to convert offline data into a single WARC file. *(Stable)*
*   [HTTrack](http://www.httrack.com/) - An open source website copying utility. *(Stable)*
*   [monolith (⭐15k)](https://github.com/Y2Z/monolith) - CLI tool to save a web page as a single HTML file. *(Stable)*
*   [Obelisk (⭐311)](https://github.com/go-shiori/obelisk) - Go package and CLI tool for saving web page as single HTML file. *(Stable)*
*   [Scoop (⭐196)](https://github.com/harvard-lil/scoop) - High-fidelity, browser-based, single-page web archiving library and CLI for witnessing the web. *(Stable)*
*   [SingleFile (⭐21k)](https://github.com/gildas-lormeau/SingleFile) - Browser extension for Firefox/Chrome and CLI tool to save a faithful copy of a complete page as a single HTML file. *(Stable)*
*   [SiteStory](http://mementoweb.github.io/SiteStory/) - A transactional archive that selectively captures and stores transactions that take place between a web client (browser) and a web server. *(Stable)*
*   [Social Feed Manager](https://gwu-libraries.github.io/sfm-ui/) - Open source software that enables users to create social media collections from Twitter, Tumblr, Flickr, and Sina Weibo public APIs. *(Stable)*
*   [Squidwarc (⭐175)](https://github.com/N0taN3rd/Squidwarc) - An [open source, high-fidelity, page interacting](http://ws-dl.blogspot.com/2017/07/2017-07-24-replacing-heritrix-with.html) archival crawler that uses Chrome or Chrome Headless directly. *(In Development)*
*   [StormCrawler](http://stormcrawler.net/) - A collection of resources for building low-latency, scalable web crawlers on Apache Storm. *(Stable)*
*   [twarc (⭐1.4k)](https://github.com/DocNow/twarc) - A command line tool and Python library for archiving Twitter JSON data. *(Stable)*
*   [WAIL (⭐394)](https://github.com/machawk1/wail) - A graphical user interface (GUI) atop multiple web archiving tools intended to be used as an easy way for anyone to preserve and replay web pages; [Python](https://machawk1.github.io/wail/), [Electron (⭐128)](https://github.com/n0tan3rd/wail). *(Stable)*
*   [Warcprox (⭐447)](https://github.com/internetarchive/warcprox) - WARC-writing MITM HTTP/S proxy. *(Stable)*
*   [WARCreate](http://matkelly.com/warcreate/) - A [Google Chrome](https://www.google.com/intl/en/chrome/browser/) extension for archiving an individual webpage or website to a WARC file. *(Stable)*
*   [Warcworker (⭐62)](https://github.com/peterk/warcworker) - An open source, dockerized, queued, high fidelity web archiver based on Squidwarc with a simple web GUI. *(Stable)*
*   [Wayback (⭐2.2k)](https://github.com/wabarc/wayback) - A toolkit for snapshot webpage to Internet Archive, archive.today, IPFS and beyond. *(Stable)*
*   [Waybackpy (⭐572)](https://github.com/akamhy/waybackpy) -  Wayback Machine Save, CDX and availability API interface in Python and a command-line tool  *(Stable)*
*   [Web2Warc (⭐25)](https://github.com/helgeho/Web2Warc) - An easy-to-use and highly customizable crawler that enables anyone to create their own little Web archives (WARC/CDX). *(Stable)*
*   [Web Curator Tool](https://webcuratortool.org) - Open-source workflow management for selective web archiving. *(Stable)*
*   [WebMemex](https://github.com/WebMemex) - Browser extension for Firefox and Chrome which lets you archive web pages you visit. *(In Development)*
*   [Wget](http://www.gnu.org/software/wget/) - An open source file retrieval utility that of [version 1.14 supports writing warcs](http://www.archiveteam.org/index.php?title=Wget_with_WARC_output). *(Stable)*
*   [Wget-lua (⭐24)](https://github.com/alard/wget-lua) - Wget with Lua extension. *(Stable)*
*   [Wpull (⭐606)](https://github.com/ArchiveTeam/wpull) - A Wget-compatible (or remake/clone/replacement/alternative) web downloader and crawler. *(Stable)*

### Replay

*   [InterPlanetary Wayback (ipwb) (⭐650)](https://github.com/oduwsdl/ipwb) - Web Archive (WARC) indexing and replay using [IPFS](https://ipfs.io/).
*   [OpenWayback (⭐518)](https://github.com/iipc/openwayback/) - The open source project aimed to develop Wayback Machine, the key software used by web archives worldwide to play back archived websites in the user's browser. *(Stable)*
*   [PYWB (⭐1.6k)](https://github.com/webrecorder/pywb) - A Python 3 implementation of web archival replay tools, sometimes also known as 'Wayback Machine'. *(Stable)*
*   [Reconstructive](https://oduwsdl.github.io/Reconstructive/) - Reconstructive is a ServiceWorker module for client-side reconstruction of composite mementos by rerouting resource requests to corresponding archived copies (JavaScript).
*   [ReplayWeb.page](https://webrecorder.net/replaywebpage/) - A browser-based, fully client-side replay engine for both local and remote WARC & WACZ files. Also available as an Electron based desktop application. *(Stable)*
*   [warc2html (⭐53)](https://github.com/iipc/warc2html) - Converts WARC files to static HTML suitable for browsing offline or rehosting.

### Search & Discovery

*   [hyphe (⭐378)](https://github.com/medialab/hyphe) - A webcrawler built for research uses with a graphical user interface in order to build web corpuses made of lists of web actors and maps of links between them. *(Stable)*
*   [Mink (⭐58)](https://github.com/machawk1/Mink) - A [Google Chrome](https://www.google.com/intl/en/chrome/) extension for querying Memento aggregators while browsing and integrating live-archived web navigation. *(Stable)*
*   [PANDORÆ (⭐16)](https://github.com/Guillaume-Levrier/PANDORAE) - A desktop research software to be plugged on a Solr endpoint to query, retrieve, normalize and visually explore web archives. *(Stable)*
*   [playback (⭐13)](https://github.com/wabarc/playback) - A toolkit for searching archived webpages from <!--lint ignore double-link-->[Internet Archive](https://web.archive.org), [archive.today](https://archive.today), [Memento](http://timetravel.mementoweb.org) and beyond. *(In Development)*
*   [SecurityTrails](https://securitytrails.com/) - Web based archive for WHOIS and DNS records. REST API available free of charge.
*   [Tempas v1](http://tempas.L3S.de/v1) - Temporal web archive search based on [Delicious](https://en.wikipedia.org/wiki/Delicious_\(website\)) tags. *(Stable)*
*   [Tempas v2](http://tempas.L3S.de/v2) - Temporal web archive search based on links and anchor texts extracted from the German web from 1996 to 2013 (results are not limited to German pages, e.g., [Obama@2005-2009 in Tempas](http://tempas.l3s.de/v2/query?q=obama\&from=2005\&to=2009)). *(Stable)*
*   [webarchive-discovery (⭐132)](https://github.com/ukwa/webarchive-discovery) - WARC and ARC full-text indexing and discovery tools, with a number of associated tools capable of using the index shown below. *(Stable)*
*   [Shine (⭐43)](https://github.com/ukwa/shine) - A prototype web archives exploration UI, developed with researchers as part of the [Big UK Domain Data for the Arts and Humanities project](https://buddah.projects.history.ac.uk/). *(Stable)*
*   [SolrWayback (⭐137)](https://github.com/netarchivesuite/solrwayback) - A backend Java and frontend VUE JS project with freetext search and a build in playback engine. Require Warc files has been index with the Warc-Indexer. The web application also has a wide range of data visualization tools and data export tools that can be used on the whole webarchive. [SolrWayback 4 Bundle release (⭐137)](https://github.com/netarchivesuite/solrwayback/releases) contains all the software and dependencies in an out-of-the box solution that is easy to install.
*   [Warclight (⭐50)](https://github.com/archivesunleashed/warclight) - A Project Blacklight based Rails engine that supports the discovery of web archives held in the WARC and ARC formats. *(In Development)*
*   [Wasp (⭐27)](https://github.com/webis-de/wasp) - A fully functional prototype of a personal [web archive and search system](http://ceur-ws.org/Vol-2167/paper6.pdf). *(In Development)*
*   Other possible options for builting a front-end are listed on in the `webarchive-discovery` wiki, [here (⭐132)](https://github.com/ukwa/webarchive-discovery/wiki/Front-ends).

### Utilities

*   [ArchiveTools (⭐78)](https://github.com/recrm/ArchiveTools) - Collection of tools to extract and interact with WARC files (Python).
*   [bagnabit2warc (⭐1)](https://github.com/internetarchive/bagnabit2warc) - Convert a [bag-nabit (⭐38)](https://github.com/harvard-lil/bag-nabit) dataset stored in a ZIP into a full-content WARC.
*   [cdx-toolkit](https://pypi.org/project/cdx-toolkit/) - Library and CLI to consult cdx indexes and create WARC extractions of subsets. Abstracts away Common Crawl's unusual crawl structure. *(Stable)*
*   [duckdb-web-archive-cdx (⭐18)](https://github.com/midwork-finds-jobs/duckdb-web-archive) - DuckDB extension to query the Internet Archive and CommonCrawl CDX APIs directly from SQL. *(In Development)*
*   [Go Get Crawl (⭐175)](https://github.com/karust/gogetcrawl) - Extract web archive data using <!--lint ignore double-link-->[Wayback Machine](https://web.archive.org/) and [Common Crawl](https://commoncrawl.org/). *(Stable)*
*   [gowarcserver (⭐17)](https://github.com/nlnwa/gowarcserver) - [BadgerDB (⭐16k)](https://github.com/dgraph-io/badger)-based capture index (CDX) and WARC record server, used to index and serve WARC files (Go).
*   [har2warc (⭐55)](https://github.com/webrecorder/har2warc) - Convert HTTP Archive (HAR) -> Web Archive (WARC) format (Python).

<!--lint ignore double-link-->

*   [httpreserve.info](https://httpreserve.info) - Service to return the status of a web page or save it to the Internet Archive. HTTPreserve includes disambiguation of well-known short link services. It returns JSON via the browser or command line via CURL using GET. Describes web sites using earliest and latest dates in the Internet Archive and demonstrates the construction of Robust Links in its output using that range. (Golang). *(Stable)*
*   [HTTPreserve linkstat (⭐10)](https://github.com/httpreserve/linkstat) - Command line implementation of <!--lint ignore double-link-->[httpreserve.info](https://httpreserve.info) to describe the status of a web page. Can be easily scripted and provides JSON output to enable querying through tools like JQ. HTTPreserve Linkstat describes current status, and earliest and latest links on <!--lint ignore double-link-->[archive.org](https://archive.org/). (Golang). *(Stable)*
*   [Internet Archive Library (⭐1.9k)](https://github.com/jjjake/internetarchive) - A command line tool and Python library for interacting directly with <!--lint ignore double-link-->[archive.org](https://archive.org). (Python). *(Stable)*
*   [httrack2warc (⭐34)](https://github.com/nla/httrack2warc) - Convert HTTrack archives to WARC format (Java).
*   [MementoMap (⭐11)](https://github.com/oduwsdl/MementoMap) - A Tool to Summarize Web Archive Holdings (Python). *(In Development)*
*   [MemGator (⭐78)](https://github.com/oduwsdl/MemGator) - A Memento Aggregator CLI and Server (Golang). *(Stable)*
*   [node-cdxj (⭐2)](https://github.com/N0taN3rd/node-cdxj) - [CDXJ (⭐15)](https://github.com/oduwsdl/ORS/wiki/CDXJ) file parser (Node.js). *(Stable)*
*   [OutbackCDX (⭐42)](https://github.com/nla/outbackcdx) - RocksDB-based capture index (CDX) server supporting incremental updates and compression. Can be used as backend for OpenWayback, PyWb and [Heritrix (⭐11)](https://github.com/ukwa/ukwa-heritrix/blob/master/src/main/java/uk/bl/wap/modules/uriuniqfilters/OutbackCDXRecentlySeenUriUniqFilter.java). *(Stable)*
*   [py-wasapi-client (⭐16)](https://github.com/unt-libraries/py-wasapi-client) - Command line application to download crawls from WASAPI (Python). *(Stable)*
*   [The Unarchiver](https://theunarchiver.com/) - Program to extract the contents of many archive formats, inclusive of WARC, to a file system. Free variant of The Archive Browser (macOS only, Proprietary app).
*   [tikalinkextract (⭐11)](https://github.com/httpreserve/tikalinkextract) - Extract hyperlinks as a seed for web archiving from folders of document types that can be parsed by Apache Tika (Golang, Apache Tika Server). *(In Development)*
*   [wasapi-downloader (⭐7)](https://github.com/sul-dlss/wasapi-downloader) - Java command line application to download crawls from WASAPI. *(Stable)*
*   [Warchaeology](https://nlnwa.github.io/warchaeology/) - Warchaeology is a collection of tools for inspecting, manipulating, deduplicating and validating WARC-files. *(Stable)*
*   [warcdb (⭐404)](https://github.com/florents-Tselai/warcdb) - A command line utility (Python) for importing WARC files into a SQLite database. *(Stable)*
*   [warcbench (⭐12)](https://github.com/harvard-lil/warcbench) - A tool for exploring, analyzing, transforming, recombining, and extracting data from WARC (Web ARChive) files.
*   [warcdedupe](https://gitlab.com/taricorp/warcdedupe) - WARC deduplication tool (and WARC library) written in Rust. *(In Development)*
*   [warc-safe (⭐18)](https://github.com/natliblux/warc-safe) - Automatic detection of viruses and NSFW content in WARC files.
*   [WarcPartitioner (⭐1)](https://github.com/helgeho/WarcPartitioner) - Partition (W)ARC Files by MIME Type and Year. *(Stable)*
*   [warcrefs (⭐10)](https://github.com/arcalex/warcrefs) - Web archive deduplication tools. *(Stable)*
*   [webarchive-indexing (⭐47)](https://github.com/ikreymer/webarchive-indexing) - Tools for bulk indexing of WARC/ARC files on Hadoop, EMR or local file system.
*   [wikiteam (⭐833)](https://github.com/WikiTeam/wikiteam) - Tools for downloading and preserving wikis. *(Stable)*

### WARC I/O Libraries

*   [FastWARC (⭐136)](https://github.com/chatnoir-eu/chatnoir-resiliparse) - A high-performance WARC parsing library (Python).
*   [HadoopConcatGz (⭐9)](https://github.com/helgeho/HadoopConcatGz) - A Splitable Hadoop InputFormat for Concatenated GZIP Files (and `*.warc.gz`). *(Stable)*
*   [jwarc (⭐57)](https://github.com/iipc/jwarc) - Read and write WARC files with a type safe API (Java).
*   [Jwat (⭐4)](https://github.com/netarchivesuite/jwat) - Libraries for reading/writing/validating WARC/ARC/GZIP files (Java). *(Stable)*
*   [Jwat-Tools (⭐5)](https://github.com/netarchivesuite/jwat-tools) - Tools for reading/writing/validating WARC/ARC/GZIP files (Java). *(Stable)*
*   [node-warc (⭐104)](https://github.com/N0taN3rd/node-warc) - Parse WARC files or create WARC files using either [Electron](https://electron.atom.io/) or [chrome-remote-interface (⭐4.5k)](https://github.com/cyrus-and/chrome-remote-interface) (Node.js). *(Stable)*
*   [Sparkling (⭐16)](https://github.com/internetarchive/Sparkling) - Internet Archive's Sparkling Data Processing Library. *(Stable)*
*   [Unwarcit (⭐13)](https://github.com/emmadickson/unwarcit) - Command line interface to unzip WARC and WACZ files (Python).
*   [warc (⭐59)](https://github.com/jedireza/warc) - A Rust library for reading and writing WARC files. *(Stable)*
*   [Warcat (⭐165)](https://github.com/chfoo/warcat) - Tool and library for handling Web ARChive (WARC) files (Python). *(Stable)*
*   [Warcat-rs (⭐30)](https://github.com/chfoo/warcat-rs) - Command-line tool and Rust library for handling Web ARChive (WARC) files. *(In Development)*
*   [warcio (⭐453)](https://github.com/webrecorder/warcio) - Streaming WARC/ARC library for fast web archive IO (Python). *(Stable)*
*   [warctools (⭐172)](https://github.com/internetarchive/warctools) - Library to work with ARC and WARC files (Python).
*   [webarchive (⭐20)](https://github.com/richardlehane/webarchive) - Golang readers for ARC and WARC webarchive formats (Golang).

### Analysis

*   [Archives Research Compute Hub (⭐20)](https://github.com/internetarchive/arch) - Web application for distributed compute analysis of Archive-It web archive collections. *(Stable)*
*   [ArchiveSpark (⭐158)](https://github.com/helgeho/ArchiveSpark) - An Apache Spark framework (not only) for Web Archives that enables easy data processing, extraction as well as derivation. *(Stable)*
*   [Archives Unleashed Notebooks (⭐26)](https://github.com/archivesunleashed/notebooks) - Notebooks for working with web archives with the Archives Unleashed Toolkit, and derivatives generated by the Archives Unleashed Toolkit. *(Stable)*
*   [Archives Unleashed Toolkit (⭐156)](https://github.com/archivesunleashed/aut) - Archives Unleashed Toolkit (AUT) is an open-source platform for analyzing web archives with Apache Spark. *(Stable)*
*   [Common Crawl Columnar Index](https://commoncrawl.org/tag/columnar-index/) - SQL-queryable index, with CDX info plus language classification. *(Stable)*
*   [Common Crawl Web Graph](https://commoncrawl.org/category/web-graph/) - A host or domain-level graph of the web, with ranking information. *(Stable)*
*   [Common Crawl Jupyter notebooks (⭐65)](https://github.com/commoncrawl/cc-notebooks) - A collection of notebooks using Common Crawl's various datasets. *(Stable)*
*   [Tweet Archvies Unleashed Toolkit (⭐10)](https://github.com/archivesunleashed/twut) - An open-source toolkit for analyzing line-oriented JSON Twitter archives with Apache Spark. *(In Development)*
*   [Web Data Commons](http://webdatacommons.org/) - Structured data extracted from Common Crawl. *(Stable)*

### Quality Assurance

*   [Chrome Check My Links](https://chromewebstore.google.com/detail/check-my-links/ojkcdipcgfaekbeaelaapakgnjflfglf) - Browser extension: a link checker with more options.
*   [Chrome link checker](https://chromewebstore.google.com/detail/link-checker/aibjbgmpmnidnmagaefhmcjhadpffaoi) - Browser extension: basic link checker.
*   [Chrome link gopher](https://chromewebstore.google.com/detail/bpjdkodgnbfalgghnbeggfbfjpcfamkf/publish-accepted?hl=en-US\&gl=US) - Browser extension: link harvester on a page.
*   [Chrome Open Multiple URLs](https://chromewebstore.google.com/detail/open-multiple-urls/oifijhaokejakekmnjmphonojcfkpbbh?hl=de) - Browser extension: opens multiple URLs and also extracts URLs from text.
*   [Chrome Revolver](https://chromewebstore.google.com/detail/revolver-tabs/dlknooajieciikpedpldejhhijacnbda) - Browser extension: switches between browser tabs.
*   [FlameShot (⭐30k)](https://github.com/flameshot-org/flameshot) - Screen capture and annotation on Ubuntu.
*   [PlayOnLinux](https://www.playonlinux.com/en/) - For running Xenu and Notepad++ on Ubuntu.
*   [PlayOnMac](https://www.playonmac.com/en/) - For running Xenu and Notepad++ on macOS.
*   [Windows Snipping Tool](https://support.microsoft.com/en-gb/help/13776/windows-use-snipping-tool-to-capture-screenshots) - Windows built-in for partial screen capture and annotation. On macOS you can use Command + Shift + 4 (keyboard shortcut for taking partial screen capture).
*   [WineBottler](http://winebottler.kronenberg.org/) - For running Xenu and Notepad++ on macOS.
*   [xDoTool (⭐3.8k)](https://github.com/jordansissel/xdotool) - Click automation on Ubuntu.
*   [Xenu](http://home.snafu.de/tilman/xenulink.html) - Desktop link checker for Windows.

### Curation

*   [Zotero Robust Links Extension](https://robustlinks.mementoweb.org/zotero/) - A [Zotero](https://www.zotero.org/) extension that submits to and reads from web archives. Source [on GitHub (⭐21)](https://github.com/lanl/Zotero-Robust-Links-Extension). Supercedes [leonkt/zotero-memento (⭐353)](https://github.com/leonkt/zotero-memento).

## Community Resources

### Other Awesome Lists

*   [Web Archiving Community (⭐27k)](https://github.com/ArchiveBox/ArchiveBox/wiki/Web-Archiving-Community)
*   [Awesome Memento (⭐114)](https://github.com/machawk1/awesome-memento)
*   [The WARC Ecosystem](http://www.archiveteam.org/index.php?title=The_WARC_Ecosystem)
*   [The Web Crawl section of COPTR](http://coptr.digipres.org/Category:Web_Crawl)

### Blogs and Scholarship

*   [IIPC Blog](https://netpreserveblog.wordpress.com/)
*   [Web Archiving Roundtable](https://webarchivingrt.wordpress.com/) - Unofficial blog of the Web Archiving Roundtable of the [Society of American Archivists](https://www2.archivists.org/) maintained by the members of the Web Archiving Roundtable.
*   [The Web as History](https://www.uclpress.co.uk/products/84010) - An open-source book that provides a conceptual overview to web archiving research, as well as several case studies.
*   [WS-DL Blog](https://ws-dl.blogspot.com/) - Web Science and Digital Libraries Research Group blogs about various Web archiving related topics, scholarly work, and academic trip reports.
*   [DSHR's Blog](https://blog.dshr.org/) - David Rosenthal regularly reviews and summarizes work done in the Digital Preservation field.
*   [UK Web Archive Blog](https://blogs.bl.uk/webarchive/)
*   [Common Crawl Foundation Blog](https://commoncrawl.org/blog) - [rss](http://commoncrawl.org/blog/rss.xml)

### Mailing Lists

*   [Common Crawl](https://groups.google.com/g/common-crawl)
*   [IIPC](http://netpreserve.org/about-us/iipc-mailing-list/)
*   [OpenWayback](https://groups.google.com/g/openwayback-dev)
*   [WASAPI](https://groups.google.com/g/wasapi-community)

### Slack

*   [IIPC Slack](https://iipc.slack.com/) - Ask [@netpreserve](https://twitter.com/NetPreserve?s=20) for access.
*   [Archives Unleashed Slack](https://archivesunleashed.slack.com/) - [Fill out this request form](http://slack.archivesunleashed.org/) for access to a researcher group of people working with web archives.
*   [Archivers Slack](https://archivers.slack.com) - [Invite yourself](https://archivers-slack.herokuapp.com/) to a multi-disciplinary effort for archiving projects run in affiliation with [EDGI](https://envirodatagov.org/archiving/) and [Data Together](http://datatogether.org/).
*   [Common Crawl Foundation Partners](https://ccfpartners.slack.com/) (ask greg zat commoncrawl zot org for an invite)

### Discord

*   [Common Crawl Foundation](https://discord.gg/njaVFh7avF)

### Twitter

*   [@commoncrawl](https://twitter.com/commoncrawl) - Official Common Crawl Foundation handle.
*   [@NetPreserve](https://twitter.com/NetPreserve) - Official IIPC handle.
*   [@WebSciDL](https://twitter.com/WebSciDL) - ODU Web Science and Digital Libraries Research Group.
*   [#WebArchiving](https://twitter.com/search?q=%23webarchiving)
*   [#WebArchiveWednesday](https://twitter.com/hashtag/webarchivewednesday)

## Web Archiving Service Providers

The intention is that we only list services that allow web archives to be exported in standard formats (WARC or WACZ). But this is not an endorsement of these services, and readers should check and evaluate these options based on their needs.

### Self-hostable, Open Source

*   [Browsertrix](https://webrecorder.net/browsertrix/) - From [Webrecorder](https://webrecorder.net/), source available at [https://github.com/webrecorder/browsertrix (⭐402)](https://github.com/webrecorder/browsertrix).
*   [Conifer](https://conifer.rhizome.org/) - From [Rhizome](https://rhizome.org/), source available at <https://github.com/Rhizome-Conifer>.

### Hosted, Closed Source

*   [Archive-It](https://archive-it.org/) - From the Internet Archive.
*   [Arkiwera](https://arkiwera.se/wp/websites/)
*   [Hanzo](https://www.hanzo.co/chronicle)
*   [MirrorWeb](https://www.mirrorweb.com/solutions/capabilities/website-archiving)
*   [PageFreezer](https://www.pagefreezer.com/)
*   [Smarsh](https://www.smarsh.com/platform/compliance-management/web-archive)

## Public Data

This is a list of publicly available WARCs, Wayback Machines, CDX API endpoints, other indexes, and so on.

*   [Common Crawl files](https://data.commoncrawl.org/) - WARCs, CDX files, parquet url index, parquet host index, etc.
*   [Common Crawl CDX API](https://index.commoncrawl.org/)
*   [End of Term Archive](https://eotarchive.org/) - WARCs, CDX files, parquet url index
*   [Internet Archive Wayback](https://web.archive.org/)
*   [Webrecorder US GovArchive](https://govarchive.us/) - high-fidelity replay
*   [UK Government Web Archive](https://www.nationalarchives.gov.uk/webarchive/) - Wayback

