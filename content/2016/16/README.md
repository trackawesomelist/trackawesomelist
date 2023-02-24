# Awesome List Updates on Apr 18 - Apr 24, 2016

37 awesome lists updated this week.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Remote Job](/content/lukasz-madon/awesome-remote-job/week/README.md)

### Interviewing

*   [andreis/interview (⭐16k)](https://github.com/andreis/interview) - Everything you need to kick ass on your coding interview

## [2. Awesome Android](/content/JStumpp/awesome-android/week/README.md)

### Crash monitoring / Field Validation

*   [HockeyApp](https://www.hockeyapp.net/) - Distribution, Crash Reports, Feedback and Analytics

### Networking / Field Validation

*   [RESTMock (⭐751)](https://github.com/andrzejchm/RESTMock) - HTTP Web server for mocking API responses in Android Instrumentation tests.

## [3. Awesome Wicket](/content/PhantomYdn/awesome-wicket/week/README.md)

### Libraries

*   [wicket-modelfactory](http://wicketeer.org/wicket-modelfactory/) - Wicket-modelfactory is an API to create Wicket PropertyModels in a typesafe and refactoring-safe way.

### Libraries / WicketStuff

*   [Autocomplete TagIt (⭐335)](https://github.com/wicketstuff/core/wiki/Autocomplete-TagIt) - [TagIt](http://aehlke.github.com/tag-it/) integration with Wicket.
*   [BrowserId (⭐335)](https://github.com/wicketstuff/core/wiki/BrowserId) - [Mozilla Persona](https://login.persona.org/) integration with Wicket.
*   [DataTables (⭐335)](https://github.com/wicketstuff/core/wiki/DataTables) - [DataTables jQuery](http://www.datatables.net/) Plugin Integration.
*   [Eidogo (⭐335)](https://github.com/wicketstuff/core/wiki/Eidogo) - SGF viewer and editor for GO game (also called baduk, igo or weiqi).
*   [Fast Serializer (⭐335)](https://github.com/wicketstuff/core/wiki/FastSerializer) - Wicket Serializer using the Fast 1.x (FST) library.
*   [Fast Serializer 2 (⭐335)](https://github.com/wicketstuff/core/wiki/FastSerializer2) - Wicket Serializer using the Fast 2.x (FST) library.
*   [MBeanView (⭐335)](https://github.com/wicketstuff/core/wiki/MBeanView) - JMX panel, to view and operate the applications mbeans.
*   [WiQuery (⭐6)](https://github.com/wicketstuff/wiquery) - Wicket integration with jQuery and jQuery UI.

### Web Frameworks / WicketStuff

*   [Nocket (⭐9)](https://github.com/Nocket/nocket) - Naked Object based framework for wicket.
*   [Wicketopia (⭐18)](https://github.com/jwcarman/Wicketopia) - Rapid Application Development (RAD) library for the Wicket.

## [4. Awesome Git Addons](/content/stevemao/awesome-git-addons/week/README.md)

### [git-secret](https://github.com/sobolevn/git-secret)

### unpublish

    $ git unpublish master
    Unpublishing master.

<!---->

    $ git when-merged a2c9e695ecf3600f21fa731e705fd1a0503632d9
    refs/heads/master                      5a2ec1b1a6633f830bd4a2b1daab578c062e6975
    $ git when-merged HEAD
    refs/heads/master                      Commit is directly on this branch.

<!---->

    $ git playback README.md

![](https://camo.githubusercontent.com/9abe1d2de474dbc0d1ad4f48acf9e954ff0d0b30/68747470733a2f2f7261772e6769746875622e636f6d2f6a69616e6c692f6769742d706c61796261636b2f6d61737465722f616e696d6174696f6e2e676966)

    $ git branch-status
     4.0       [57 ahead and 38 behind master]    [up to date with origin/4.0]
     master    [current branch]                   [1 ahead of origin/master]

<!---->

    $ git open
    > open https://github.com/REMOTE_ORIGIN_USER/CURRENT_REPO/tree/CURRENT_BRANCH

    $ git open upstream
    > open https://github.com/REMOTE_UPSTREAM_USER/CURRENT_REPO/tree/CURRENT_BRANCH

    $ git open upstream master
    > open https://github.com/REMOTE_UPSTREAM_USER/CURRENT_REPO/tree/master

<!---->

    $ git my

    +------------------------------------------------------------------------------+
    | your name's remote branches in git@repo:repopath/reponame.git                |
    +------------------------------------------------------------------------------+

       local copy?  in master?  branch name
      ................[merged]. EC-242
      .....[local]....[merged]. commonjs-lazyload
      .....[local]............. enqueue-gpt
      ......................... defunct-ios-app-nag
      .....[local]............. factor-bundles

<!---->

    $ git ink

    • enqueue-gpt ........................................... 2015-08-31
    • factor-bundles ........................................ 2015-10-14
        - Pull out more modules into node_modules
        - Works but does not provide any gains
    • hbsfy ................................................. 2015-10-21
    ✓ master ................................................ 2015-10-22
    • nda-ads4 .............................................. 2015-10-22
    • remove-equalize_content_height ........................ 2015-10-21
    • remove-exorcise ....................................... 2015-10-21
        - Need to DRY up exorcise function
        - Does not map properly when uglified
        - Need to undo postCSS mapping changes
    • rm-convert_dates-order ................................ 2015-10-22
    • sass-lint ............................................. 2015-10-14
        - module does not work

<!---->

    $ git recursive-blame version package.json

    Commit: 247479d017f138c26be27c64a0ce27f5f21fc0af
    Author: Jeff Cross <middlefloor@gmail.com>
    Date:   Tue Oct 13 15:58:13 2015 -0700 (7 weeks ago)
    Path:   package.json
    Match:  1 of 1

        chore(release): bump angular version to alpha.42

    1) {
    2)   "name": "angular",
    3)   "version": "2.0.0-alpha.42",
    4)   "branchPattern": "2.0.*",
    5)   "description": "Angular 2 - a web framework for modern web apps",
    6)   "homepage": "https://github.com/angular/angular",
    7)   "bugs": "https://github.com/angular/angular/issues",

    Next action [r,n,p,c,d,q,?]? r

    Commit: bb9d299b3860f6d579192828451ccd7ace70e1d8
    Author: Igor Minar <igor@angularjs.org>
    Date:   Tue Oct 13 12:28:03 2015 -0700 (7 weeks ago)
    Path:   package.json
    Match:  1 of 1

        chore(release): bump angular version to alpha.41

    1) {
    2)   "name": "angular",
    3)   "version": "2.0.0-alpha.41",
    4)   "branchPattern": "2.0.*",
    5)   "description": "Angular 2 - a web framework for modern web apps",
    6)   "homepage": "https://github.com/angular/angular",
    7)   "bugs": "https://github.com/angular/angular/issues",

<!---->

    $ git hyper-blame -i 3ddda43c ipsum.txt
    c6eb3bfa (lorem 2014-08-11 23:15:57 +0000  1) LOREM IPSUM DOLOR SIT AMET, CONSECTETUR
    134200d1 (lorem 2014-04-10 08:54:46 +0000 2*) ADIPISCING ELIT, SED DO EIUSMOD TEMPOR
    a34a1d0d (ipsum 2014-04-11 11:25:04 +0000 3*) INCIDIDUNT UT LABORE ET DOLORE MAGNA
    134200d1 (lorem 2014-04-10 08:54:46 +0000 4*) ALIQUA. UT ENIM AD MINIM VENIAM, QUIS
    c6eb3bfa (lorem 2014-08-11 23:15:57 +0000  5) NOSTRUD EXERCITATION ULLAMCO LABORIS
    0f0d17bd (dolor 2014-06-02 11:31:48 +0000 6*) NISI UT ALIQUIP EX EA COMMODO CONSEQUAT.

<!---->

    $ git word-blame README.md
    results in /tmp/word-blame-output/
     - author_stats.tsv
     - commit_stats.tsv
     - word-blame-by-commit.html
     - word-blame-by-author.html
     - text-output

![git word-blame on this README](https://user-images.githubusercontent.com/1469823/57202569-0247eb00-6fa7-11e9-8549-f55d81299fab.png)

    $ git fire
    Switched to a new branch 'fire-master-maochenyan@gmail.com-1451379915'
    On branch fire-master-maochenyan@gmail.com-1451379915
    nothing to commit, working directory clean
    Counting objects: 2, done.
    Writing objects: 100% (2/2), 168 bytes | 0 bytes/s, done.
    Total 2 (delta 0), reused 0 (delta 0)
    To git@bitbucket.org:maochenyan/fire.git
     * [new branch]      fire-master-maochenyan@gmail.com-1451379915 -> fire-master-maochenyan@gmail.com-1451379915
    Branch fire-master-maochenyan@gmail.com-1451379915 set up to track remote branch fire-master-maochenyan@gmail.com-1451379915 from origin.


    Leave building!

TBD - PR Welcome!

    $ git blame-someone-else 'Steve Mao <maochenyan@gmail.com>' 2efb4e3a061a2e8aaa58033e9c13c3e0e5fcde4b
    Steve Mao  is now the author of 2efb4e3. You're officially an asshole.

<!---->

    $ git dsf

![diff-highlight vs diff-so-fancy](https://user-images.githubusercontent.com/3429760/32387617-44c873da-c082-11e7-829c-6160b853adcb.png)

![](http://i.imgur.com/PpM0i3v.png)

## [5. Awesome Microservices](/content/mfornos/awesome-microservices/week/README.md)

### PHP / Scala

*   [API Platform](https://api-platform.com/) - API-first web framework on top of Symfony with JSON-LD, Schema.org and Hydra support.
*   [Phalcon](https://phalconphp.com/) - Full-stack PHP framework delivered as a C-extension.

### API Gateways / Edge Services / Scala

*   [Fabio (⭐7.1k)](https://github.com/eBay/fabio) - A fast, modern, zero-conf load balancing HTTP/S router for deploying microservices managed by Consul.
*   [Neutrino (⭐300)](https://github.com/eBay/Neutrino) - Extensible software load balancer.

### Web APIs / Scala

*   [Hydra](http://www.hydra-cg.com/) - Specifications for interoperable, hypermedia-driven Web APIs.

### Data Formats / Scala

*   [JSON-LD](http://json-ld.org/) - JSON for Linking Data.

### Vocabularies / Scala

*   [Schema.org](http://schema.org/) - Collaborative, community activity with a mission to create, maintain, and promote schemas for structured data on the Internet, on web pages, in email messages, and beyond.

## [6. Awesome Book Authoring](/content/TalAter/awesome-book-authoring/week/README.md)

### Royalties, Advances, and Other Money Stuff

*   [Writing A Technical Book: Is It Worthwhile?](http://www.fasterj.com/articles/bookwriting.shtml) - The benefits for writing a technical book, and the basics of how book advances work.
*   [How Book Advances Work – A Simple Explanation for Writers](http://www.writersdigest.com/online-editor/how-book-advances-work-a-simple-explanation-for-writers)
*   [Typical O'Reilly Advance Structure](http://web.archive.org/web/20130704110948/http://oreilly.com/oreilly/author/ch03.html#advance)

## [7. Rbooks](/content/RomanTsegelskyi/rbooks/week/README.md)

### Data Science

#### Data Manipulation with R, Second Edition [\[Packt\]](https://www.packtpub.com/big-data-and-business-intelligence/data-manipulation-r-second-edition)

<img src="http://ecx.images-amazon.com/images/I/51Jwp-z343L._SX403_BO1,204,203,200_.jpg" width="200px" />

This book starts with the installation of R and how to go about using R and its libraries. We then discuss the mode of R objects and its classes and then highlight different R data types with their basic operations.

The primary focus on group-wise data manipulation with the split-apply-combine strategy has been explained with specific examples. The book also contains coverage of some specific libraries such as lubridate, reshape2, plyr, dplyr, stringr, and sqldf. You will not only learn about group-wise data manipulation, but also learn how to efficiently handle date, string, and factor variables along with different layouts of datasets using the reshape2 package.

By the end of this book, you will have learned about text manipulation using stringr, how to extract data from twitter using twitteR library, how to clean raw data, and how to structure your raw data for data mining.

## [8. Nlp with Ruby](/content/arbox/nlp-with-ruby/week/README.md)

### Segmentation / On-line APIs

*   [nlp-pure (⭐19)](https://github.com/parhamr/nlp-pure) -
    Natural language processing algorithms implemented in pure Ruby with minimal dependencies.

### Machine Learning Libraries / Constituency Parsing

*   [weka (⭐67)](https://github.com/paulgoetze/weka-jruby) -
    JRuby bindings for Weka, different ML algorithms implemented through Weka.

## [9. Awesome Vorpal](/content/vorpaljs/awesome-vorpal/week/README.md)

### Extensions / Toolbox

*   [comment (⭐5)](https://github.com/subk/vorpal-comment) - Bash-like comment support.

## [10. Awesome Emails](/content/jonathandion/awesome-emails/week/README.md)

### Resources / Misc

*   [Email toolbox](http://email-toolbox.com/) - Hand-picked resources for email marketers and designers.

## [11. Awesome Nodejs](/content/sindresorhus/awesome-nodejs/week/README.md)

### Packages / Templating

*   [Pug (⭐21k)](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml.

## [12. Awesome Npm](/content/sindresorhus/awesome-npm/week/README.md)

### Articles

*   [Why npm scripts?](https://css-tricks.com/why-npm-scripts/) - An introduction to npm scripts with common packages and scripts, as well as a boilerplate project.

### Other

*   [npm-upgrade (⭐312)](https://github.com/th0r/npm-upgrade) - Update outdated npm dependencies interactively.

## [13. Awesome Ruby](/content/markets/awesome-ruby/week/README.md)

### WebSocket

*   [Firehose (⭐725)](https://github.com/firehoseio/firehose) - Build realtime Ruby web applications.

## [14. Awesome Sketch](/content/diessica/awesome-sketch/week/README.md)

### Videos / Tutorial-only

*   **[Sketch 3 Tutorials](https://www.youtube.com/playlist?list=PLLnpHn493BHE6UIsdKYlS5zu-ZYvx22CS)** (25 *awesome* lessons for beginners)

### Other / Nice-to-have :thumbsup:

*   [SketchApp Rocks](http://sketchapp.rocks/)

## [15. Awesome Broadcasting](/content/ebu/awesome-broadcasting/week/README.md)

### Subtitling

*   [CCExtractor](http://ccextractor.sourceforge.net/about-ccextractor.html) - A tool that analyzes video files and produces stand-alone subtitle files.

## [16. Awesome Dotnet](/content/quozd/awesome-dotnet/week/README.md)

### API

*   [Mobius: C# API for Spark (⭐933)](https://github.com/Microsoft/Mobius) - Mobius adds C# language binding to Apache Spark, enabling the implementation of Spark driver code and data processing operations in C#.

## [17. Awesome Opensource Apps](/content/unicodeveloper/awesome-opensource-apps/week/README.md)

### Laravel

- Name: [Larasocial (⭐272)](https://github.com/msalom28/Larasocial)

  Description: A Social Network Application

  Link: <http://larasocial.info>


- Name: [Aimeos (⭐5.8k)](https://github.com/aimeos/aimeos-laravel)

  Description: Ecommerce package for high performance online shops

  Link: <https://aimeos.org/Laravel>



### Rails

- Name: [Copycopter (⭐684)](https://github.com/copycopter/copycopter-server)

  Description: A service for editing the copy text of a Rails application.

  Link: <http://copycopter.com>



## [18. Awesome Polymer](/content/Granze/awesome-polymer/week/README.md)

### Articles

*   [Encapsulated Routing with Elements](https://www.polymer-project.org/1.0/articles/routing.html)
*   [NET-A-PORTER case study](https://developers.google.com/web/showcase/case-study/net-a-porter)

## [19. Awesome Vulkan](/content/vinjn/awesome-vulkan/week/README.md)

### Tools

*   [CodeXL (⭐974)](https://github.com/GPUOpen-Tools/CodeXL) - CodeXL goes open source. \[MIT]

## [20. Awesome Dotnet Core](/content/thangchung/awesome-dotnet-core/week/README.md)

### Frameworks, Libraries and Tools / Caching

*   [Microsoft Caching (⭐481)](https://github.com/aspnet/Caching) - Libraries for in-memory caching and distributed caching.

### Frameworks, Libraries and Tools / Web Framework

*   [ReactJS.NET (⭐2.2k)](https://github.com/reactjs/React.NET) - .NET library for JSX compilation and server-side rendering of React components.

## [21. Awesome Elixir](/content/h4cc/awesome-elixir/week/README.md)

### Miscellaneous

*   [exldap (⭐57)](https://github.com/jmerriweather/exldap) - A module for working with LDAP from Elixir.
*   [phone (⭐100)](https://github.com/fcevado/phone) - A parser to get useful info from telephone numbers.

### Testing

*   [setup\_tag (⭐2)](https://github.com/vic/setup_tag) - Easily mix and match functions marked with tags to setup your test context.

### Third Party APIs

*   [pay (⭐27)](https://github.com/era/pay) - An Elixir Lib to deal with Paypal and other payment solutions.

## [22. Awesome Bigdata](/content/newTendermint/awesome-bigdata/week/README.md)

### Data Visualization

*   [chartd](http://chartd.co/) - responsive, retina-compatible charts with just an img tag.

## [23. Awesome Php](/content/ziadoz/awesome-php/week/README.md)

### Table of Contents / Data Structure and Storage

*   [JsonMapper (⭐1.4k)](https://github.com/cweiske/jsonmapper) - A library that maps nested JSON structures onto PHP classes.

## [24. Awesome Devenv](/content/jondot/awesome-devenv/week/README.md)

### Orchestration / Extensions

*   [azk (⭐906)](https://github.com/azukiapp/azk) - a lightweight open source engine to orchestrate development environments

## [25. Awesome Swift](/content/matteocrippa/awesome-swift/week/README.md)

### Auto Layout / Barcode

*   [EasyPeasy (⭐1.9k)](https://github.com/nakiostudio/EasyPeasy) - Auto Layout made easy.

### Video / Barcode

*   [PlayerView (⭐131)](https://github.com/davidlondono/PlayerView) - Easy to use video player using a UIView, manage rate of reproduction, screenshots and callbacks-delegate for player state.

## [26. Awesome R](/content/qinwf/awesome-R/week/README.md)

### Data Manipulation

*   [fuzzyjoin (⭐619)](https://github.com/dgrtwo/fuzzyjoin) - Join tables together on inexact matching.

### Other Interpreters

*   [CXXR](https://www.cs.kent.ac.uk/projects/cxxr/) - Refactorising R into C++.
*   [pqR](http://www.pqr-project.org/) - a "pretty quick" implementation of R
*   [renjin](http://www.renjin.org/) - a JVM-based interpreter for R.
*   [rho (⭐131)](https://github.com/rho-devel/rho) - Refactor the interpreter of the R language into a fully-compatible, efficient, VM for R.
*   [TERR](http://spotfire.tibco.com/discover-spotfire/what-does-spotfire-do/predictive-analytics/tibco-enterprise-runtime-for-r-terr) - TIBCO Enterprise Runtime for R.

## [27. Awesome Neo4j](/content/neueda/awesome-neo4j/week/README.md)

### REST API / Other

*   [GraphStory](https://www.graphstory.com/) - Neo4j enterprise cloud provider
*   [GraphAware Neo4j Elasticsearch Integration (⭐258)](https://github.com/graphaware/neo4j-to-elasticsearch) - GraphAware Framework Module for Integrating Neo4j with Elasticsearch.
*   [GraphAware Graph-Aided Search (⭐154)](https://github.com/graphaware/graph-aided-search) - Elasticsearch plugin offering Neo4j integration for Personalized Search.
*   [GraphAware Neo4j Expire (⭐30)](https://github.com/graphaware/neo4j-expire) - GraphAware Expire is a simple library that automatically deletes nodes and relationships from the database when they've reached their expiration date or time-to-live (TTL).
*   [Apoc : Awesome Procedures on Cypher (⭐1.5k)](https://github.com/neo4j-contrib/neo4j-apoc-procedures) - Collection of useful procedures for Neo4j 3.x
*   [Graphgen (⭐8)](https://github.com/graphaware/neo4j-graphgen-procedure) - Neo4j procedure for generating test data easily with Cypher

## [28. Awesome Cyclejs](/content/cyclejs-community/awesome-cyclejs/week/README.md)

### Learn / Slides

*   [Intro to Cycle.js](http://www.slideshare.net/aryelukashevski/cyclejs-introduction) - by Arye Lukashevki

### Learn / Example Applications

*   [grozen/trends-cycle ★3 (⭐3)](https://github.com/grozen/trends-cycle) - Slack trend searching written in Cycle.js
*   [MarcCloud/magic-cart ★6 (⭐6)](https://github.com/MarcCloud/magic-cart) - Simple shopping cart of a magic creatures store.
*   [kibin/cycle-example-who-to-follow ★16 (⭐15)](https://github.com/kibin/cycle-example-who-to-follow) - Small example partly implements twitter’s who to follow box using github api.

### Libraries / Utilities

*   [cgeorg/sinject ★10 (⭐10)](https://github.com/cgeorg/sinject) - a dependency injection tool supporting Cycle's circular dependencies
*   [madcapjake/earlhyperscript ★2 (⭐2)](https://github.com/MadcapJake/earl-hyperscript) - A helper function and macro for using Earl Grey's [document-building syntax](https://breuleux.github.io/earl-grey/doc.html#documentbuildingsyntax) with Cycle.js.

### Libraries / Components

*   [mciparelli/cyclejs-gravatar ★0 (⭐0)](https://github.com/mciparelli/cyclejs-gravatar) - Cycle.js component for rendering a gravatar profile image.

## [29. Awesome Salesforce](/content/mailtoharshit/awesome-salesforce/week/README.md)

### Javascript Libraries for Salesforce / Open Source Projects Repositories from Salesforce

*   [Formulon (⭐55)](https://github.com/leifg/formulon) - Formula parser completely implemented in ES6. [See Demo](http://formulon.io)

## [30. Awesome Tensorflow](/content/jtoy/awesome-tensorflow/week/README.md)

### Models/Projects

*   [Neural Turing Machine in TensorFlow (⭐1k)](https://github.com/carpedm20/NTM-tensorflow) - implementation of Neural Turing Machine

### Videos

*   [TensorFlow Guide 1](http://bit.ly/1OX8s8Y) - A guide to installation and use
*   [TensorFlow Basic Usage](http://bit.ly/1TCNmEY) - A guide going over basic usage
*   [TensorFlow Udacity Deep Learning](https://www.youtube.com/watch?v=ReaxoSIM5XQ) - Basic steps to install TensorFlow for free on the Cloud 9 online service with 1Gb of data

### Community

*   [Stack Overflow](http://stackoverflow.com/questions/tagged/tensorflow)

## [31. Awesome Elm](/content/sporto/awesome-elm/week/README.md)

### Articles / Outdated articles (Not relevant for current Elm architecture)

*   [Elm & Components](https://medium.com/p/elm-components-3d9c00c6c612) - A blog post describing a possible approach to reducing TEA boilerplate. Useful for component libraries and anyone interested in seeing the amazing things you can do with function types.

## [32. Awesome Audio Visualization](/content/willianjusten/awesome-audio-visualization/week/README.md)

### Experiments

*   [Adventure Machine](http://www.madeon.fr/adventuremachine/) - Campaign for Madeon's "Adventure" album.
*   [BBNG](https://uberviz.io/viz/bbng/) - WebGL Visualizer for "Confessions" (feat. Leland Whitty) by BADBADNOTGOOD.
*   [Born in the Echoes](http://bornintheechoes.com/) - Campaign for The Chemical Brothers' "Born in the Echoes" album.
*   [DENNIS](http://www.dennis.video/) - An interactive and audio responsive music video for "Dennis" by popcorn\_10's.
*   [Fluctus](http://jojo.ninja/fluctus/) - Experimental 3D Audio Visualizer by Jordan Machado.
*   [George & Jonathan III](http://www.georgeandjonathan.com/) - Campaign for George & Jonathan's "III" album.
*   [Lantern](https://www.uberviz.io/viz/lantern/) - WebGL Visualizer for "Lantern" by SBTRKT.
*   [Lines](http://labs.fluuu.id/lines/) - Visualising Joy Division album cover as a music spectrum by Silvio Paganini.
*   [Nero](https://www.uberviz.io/viz/nero/) - WebGL Visualizer for "In The Way" by Nero.
*   [Pareidolia](https://www.uberviz.io/viz/pareidolia/) - WebGL Visualizer for "Szerencsétlen" by Venetian Snares.
*   [Yume](http://unseen-music.com/yume/) - Campaign for Helios' "Yume" album.
*   [Spins](http://mattdesl.github.io/spins/) - Audio Visualizer rendering Waveforms in Polar Coordinates by Matt DesLauriers.
*   [Silk](http://mattdesl.github.io/codevember/21.html) - 3D Audio Visualizer by Matt DesLauriers.
*   [Wave](http://mattdesl.github.io/codevember/3.html) - 3D Audio Visualizer by Matt DesLauriers.
*   [Binaural](http://mattdesl.github.io/codevember/6.html) - Experiment using Binaural and Reverb audio effects by Matt DesLauriers.
*   [Beatgrid](http://mattdesl.github.io/codevember/8.html) - Experiment using Audio Beat Detection by Matt DesLauriers.
*   [Party](http://mattdesl.github.io/codevember/13.html) - 2D Audio Visualizer by Matt DesLauriers.
*   [Word Problems](https://www.uberviz.io/viz/word-problems/) - WebGL Visualizer for "Word Problems" by Harmonic 313.
*   [Glitch](http://naivesound.com/glitch/) - An algorithmic synthesizer to make music from math.
*   [105 Birthday Clara Rockmore](http://www.google.com/doodles/clara-rockmores-105th-birthday) - A Doodle for the Birthday of Clara Rockmore.
*   [Fireworks with WebGL](http://ondras.github.io/fireworks-webgl/) - Sound driven fireworks by Ondřej Žára.
*   [Tonalhub](https://alemangui.github.io/Tonalhub/?user=webaudio\&repository=web-audio-api) - Create music from your github repository by Alejandro Mantecon Guillen.
*   [Play a cornet to Donald Trump](http://trumpdonald.org/) - A funny site to play a cornet to Donald Trump by Animal Agency.
*   [Bohemian Rhapsichord](http://static.echonest.com/BohemianRhapsichord/index.html) - A web app that turns the song Bohemian Rhapsody into a musical instrument by Paul Lamere.
*   [Scrollsound](http://zya.github.io/scrollsound/) - Scrolling as a method of interaction with audio on the web by Ehsan Ziya.
*   [Experiment #8](http://brunoimbrizi.com/experiments/#/08) - Music Experiment by Bruno Imbrizi.
*   [Draw and Music](http://rugs.grindselect.com/) - Campaign for Rugs new album by Sam Greens.
*   [Moogfest Substrate](http://www.moogfest.com/_substrate) - Experimental site to Moogfest.
*   [Flame Gradient](http://rickycodes.github.io/audio-visualizer/gradient/) - Audio visualizer built with HTML5 web audio API by rickycodes.
*   [3D Grid](http://rickycodes.github.io/audio-visualizer/three/) - Audio visualizer built with HTML5 web audio API by rickycodes.
*   [obsidian](http://mrdoob.com/files/temp/xplsv_obsidian/) - 3D Audio Visualization made by the creator of Three.js.

### Experiments on Codepen

*   [SVG Animated Drum Kit](http://codepen.io/iamjoshellis/full/KVdQqm/) - Play an amazing Drum made with SVG and realistic sounds by @iamjoshellis.
*   [SVG Animated Guitar](http://codepen.io/iamjoshellis/full/qbBKZB/) - Play an amazing Guitar made with SVG and realistic sounds by @iamjoshellis.
*   [Audio Visualizer](http://codepen.io/Francext/full/yIogq/) - Abstract Audio Visualizer using Three.js by Francesco Trillini
*   [Awesome Audio Player](http://codepen.io/alexpierre/full/RNELPV/) - Radial Audio Player constructed by lines of frequency and amplitude by Alex Permyakov
*   [Wireframes](http://codepen.io/pat_hg/full/gamQwr/) - Wireframe WebGL Animation with Three.js by Patrick Heng
*   [Soundcloud Vinyl Search](http://codepen.io/chrisgannon/full/GpwqgG/) - An amazing experiment creating a realistic Vinyl player using DrawSVG and GSAP by Chris Gannon.
*   [Gooey Effect Audio](http://codepen.io/enjikaka/full/QbJmRJ/) - Upload your mp3 and visualize the song with this crazy effect by Jeremy Karlsson.
*   [CSS Audio Visualizer](http://codepen.io/njmcode/full/WbWyWz/) - Using audio frequency data from a hidden video to apply CSS scaling by Neil McCallion.
*   [Storytelling with Html5 + CSS3](http://codepen.io/rachelnabors/full/rCost/) - A great example of how to use music to create a Storytelling by Rachel Nabors.
*   [Step sequencer](http://codepen.io/woodwork/full/rxrLqa/) - Create music with this sequencer by Joe Harry.
*   [WebGL Soundcloud Visualizer using Three.js](http://codepen.io/luigimannoni/full/xbLgqB) - ThreeJS/WebGL Soundcloud player/visualizer based on HTML5 AudioContext API by Luigi Mannoni.
*   [Oscilator](http://codepen.io/easwee/pen/sFpmo) - Testing the oscillator node from HTML5 audio API by Anej Gorkič.
*   [Cubes Audio Visualizer](http://codepen.io/pat_hg/pen/zvMrRJ) - 10th contribution for codevember 2015 by Patrick Heng.

### Libraries Audio

*   [Beeplay.js](https://watilde.github.io/beeplay/) - Write a song In JavaScript.

### Libraries Visualization

*   [The Force (⭐238)](https://github.com/shawnlawson/The_Force) - Live coded shader editing with audio input.
*   [Hylogen (⭐470)](https://github.com/sleexyz/hylogen) - Purely functional language embedded in Haskell for expressive live coding of fragment shaders (with audio input).

### People to Follow

*   [Joshua Davis](http://www.joshuadavis.com/) - An American designer, technologist, author and artist in new media.
*   [Robert Hodgin](http://roberthodgin.com/) - A creative coder living in Brooklyn. Co-creator of the Cinder C++.
*   [Seb Lee-Delisle](http://seb.ly/) - An award-winning digital artist and speaker.
*   [Raven Kwok](http://ravenkwok.com/) - A visual artist, animator and creative programmer.
*   [Chris Wilson](https://github.com/cwilso/) - Open Web Guy, formerly of Microsoft and now working as a Developer Advocate at Google.
*   [Jason Sigal](https://github.com/therewasaguy) - Creative Coder in residence at NYU's and creator of web audio library for p5.js.
*   [Shawn Lawson](http://shawnlawson.com/) - An experiential media artist creating the computational sublime.
*   [Matt DesLauriers](https://github.com/mattdesl) - Creative coder at Jam 3.
*   [Patrick Heng](http://hengpatrick.fr/) - Creative front-end developer. Studied at Hetic and Gobelins and works at Grouek.

## [33. Awesome Electron](/content/sindresorhus/awesome-electron/week/README.md)

### Open Source / Featured

*   [WebTorrent (⭐9.1k)](https://github.com/feross/webtorrent-app) - Streaming torrent client.
*   [Visual Studio Code (⭐143k)](https://github.com/Microsoft/vscode) - Cross-platform IDE.

### Open Source / Other

*   [Git-it (⭐4.3k)](https://github.com/jlord/git-it-electron) - Teaches you Git and GitHub.
*   [Caprine (⭐6.6k)](https://github.com/sindresorhus/caprine) - Unofficial Facebook Messenger app.
*   [Simplenote (⭐4.3k)](https://github.com/Automattic/simplenote-electron) - Note keeper.
*   [Abricotine (⭐2.6k)](https://github.com/brrd/Abricotine) - Markdown editor with inline preview.
*   [Medis (⭐11k)](https://github.com/luin/medis) - Redis database management.
*   [SmartMirror (⭐2.7k)](https://github.com/evancohen/smart-mirror) - Voice controlled smart mirror.
*   [Google Play Music Desktop Player (⭐8.4k)](https://github.com/MarshallOfSound/Google-Play-Music-Desktop-Player-UNOFFICIAL-) - Unofficial Google Play Music app.
*   [Ansel (⭐360)](https://github.com/m0g/ansel) - Image organizer.

### Closed Source / Other

*   [GitKraken](http://www.gitkraken.com) - Git client.
*   [1Clipboard](http://1clipboard.io) - Universal clipboard manager.
*   [Postman](https://www.getpostman.com) - Create and send HTTP requests.

### For Electron / Other

*   [electron-is-dev (⭐407)](https://github.com/sindresorhus/electron-is-dev) - Check if Electron is running in development.
*   [electron-localshortcut (⭐397)](https://github.com/parro-it/electron-localshortcut) - Add keyboard shortcuts locally to a window.
*   [electron-dl (⭐1k)](https://github.com/sindresorhus/electron-dl) - Simplified file downloads.
*   [electron-release-server (⭐1.8k)](https://github.com/ArekSredzki/electron-release-server) - Self-hosted release server with front-end & auto-updater support.
*   [electron-download (⭐300)](https://github.com/electron-userland/electron-download) - Download the Electron release zip from GitHub.
*   [ember-electron (⭐807)](https://github.com/felixrieseberg/ember-electron) - Build, test, and package Ember apps.

### Using Electron / Other

*   [nativefier (⭐33k)](https://github.com/jiahaog/nativefier) - Create an app of any website.
*   [electron-pdf (⭐1.2k)](https://github.com/fraserxu/electron-pdf) - Generate PDF from URL, HTML, or Markdown files on the command-line.

### Components / Other

*   [chrome-tabs (⭐1.6k)](https://github.com/adamschwartz/chrome-tabs) - Chrome like tabs.

### Videos / Other

*   [Building Native Desktop apps using Electron](https://www.youtube.com/watch?v=nXIrFq5-FC8)

## [34. Awesome Fp Js](/content/stoeffel/awesome-fp-js/week/README.md)

### Libraries

*   [fn-curry (⭐6)](https://github.com/thunklife/fn-curry) – A simple function to curry a function.
*   [date-fp (⭐123)](https://github.com/cullophid/date-fp) – A functional utility library for working with JavaScript dates. All functions in date-fp are pure, autocurried and will not mutate the date objects they are applied to.

## [35. Awesome Sre](/content/dastergon/awesome-sre/week/README.md)

### Culture

*   [PostOps: A Non-Surgical Tale of Software, Fragility, and Reliability](https://www.usenix.org/conference/lisa13/technical-sessions/plenary/underwood)

### Monitoring & Observability & Alerting

*   [A Working Theory-of-Monitoring](https://www.usenix.org/conference/lisa13/working-theory-monitoring)

### On-Call

*   [Incident Response at Heroku](https://blog.heroku.com/archives/2014/5/9/incident-response-at-heroku)

### Service Level Agreement

*   [Service Level Agreements in the Cloud: Who cares?](http://www.wired.com/insights/2011/12/service-level-agreements-in-the-cloud-who-cares/)

## [36. Engineering Blogs](/content/kilimchoi/engineering-blogs/week/README.md)

### Individuals/Group Contributors / R individuals

*   Rachel Kroll <https://rachelbythebay.com/w/>

## [37. Awesome Network Analysis](/content/briatte/awesome-network-analysis/week/README.md)

### Books / Dissemination

*   *[Nexus. Small Worlds and the Groundbreaking Theory of Networks](http://books.wwnorton.com/books/Nexus/)*, by Mark Buchanan (2003).
*   *[Six Degrees: The Science of a Connected Age](http://books.wwnorton.com/books/detail.aspx?ID=7599)*, by Duncan J. Watts (2003).

### Books / General Overviews

*   *[Encyclopedia of Social Network Analysis and Mining](https://www.springer.com/us/book/9781461461692)*, edited by Reda Alhajj and Jon Rokne (2014).
*   *[The SAGE Handbook of Social Network Analysis](http://www.sagepub.in/books/Book232753/)*, edited by John Scott and Peter J. Carrington (2011).

### Books / Method-specific

*   *[Generalized Blockmodeling. Structural Analysis in the Social Sciences](http://www.cambridge.org/de/academic/subjects/sociology/sociology-general-interest/generalized-blockmodeling)*, by Patrick Doreian, Vladimir Batagelj and Anuška Ferligoj (2004).
*   *[Handbuch Historische Netzwerkforschung. Grundlagen und Anwendungen](http://www.lit-verlag.de/isbn/3-643-11705-2)*, edited by Marten Düring *et al.*, in German (2016).
*   *[An Introduction to Exponential Random Graph Modeling](https://uk.sagepub.com/en-gb/eur/an-introduction-to-exponential-random-graph-modeling/book237737)*, by Jenine K. Harris (2014).
*   *[Knoten und Kanten. Soziale Netzwerkanalyse in Wirtschafts- und Migrationsforschung](http://www.transcript-verlag.de/978-3-8376-1311-7/knoten-und-kanten)*, edited by Markus Gamper and Linda Reschke, in German (2010).
*   *[Knoten und Kanten 2.0. Soziale Netzwerkanalyse in Medienforschung und Kulturanthropologie](http://www.transcript-verlag.de/978-3-8376-1927-0/knoten-und-kanten-2.0)*, edited by Markus Gamper, Linda Reschke and Michael Schönhuth, in German (2012).
*   *[Knoten und Kanten III. Soziale Netzwerkanalyse in Geschichts- und Politikforschung](https://github.com/briatte/awesome-network-analysis/blob/master/README.md/)*, edited by Markus Gamper, Linda Reschke and Marten Düring, in German and English (2015).
*   *[Multivariate Network Visualization](https://www.springer.com/us/book/9783319067926)*, edited by Andreas Kerren, Helen C. Purchase and Matthew O. Ward (2014).
*   *[Understanding Large Temporal Networks and Spatial Networks](http://eu.wiley.com/WileyCDA/WileyTitle/productCd-0470714522.html)*, by Vladimir Batagelj *et al.* (2014).

### Books / Software-specific

*   *[Exploratory Social Network Analysis with Pajek](http://www.cambridge.org/us/academic/subjects/sociology/research-methods-sociology-and-criminology/exploratory-social-network-analysis-pajek-2nd-edition)*, by Wouter de Nooy, Andrej Mrvar and Vladimir Batagelj (2011; also [in Japanese](http://www.tdupress.jp/books/isbn978-4-501-54710-3.html) and [in Chinese](http://product.dangdang.com/22927985.html)).
*   *[Gephi Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/gephi-cookbook)* (2015).
*   *[Graph Drawing Software](http://link.springer.com/book/10.1007/978-3-642-18638-7)* (covering many programs), edited by Michael Jünger and Petra Mutzel (2004).
*   *[Mastering Gephi Network Visualization](https://www.packtpub.com/networking-and-servers/mastering-gephi-network-visualization)*, by Ken Cherven (2015).
*   *[Network Graph Analysis and Visualization with Gephi](https://www.packtpub.com/big-data-and-business-intelligence/network-graph-analysis-and-visualization-gephi)*, by Ken Cherven (2013).

### Books / Topic-specific

*   *[Comparing Policy Networks. Labor Politics in the U.S., Germany, and Japan](http://www.cambridge.org/ar/academic/subjects/politics-international-relations/comparative-politics/comparing-policy-networks-labor-politics-us-germany-and-japan)*, by David Knoke *et al.* (1996).
*   *[The Connected Past. Challenges to Network Studies in Archaeology and History](https://global.oup.com/academic/product/the-connected-past-9780198748519)* edited by Tom Brughmans, Anna Collar and Fiona Coward (2016; [companion website](http://connectedpast.net/)).
*   *[The Development of Social Network Analysis: A Study in the Sociology of Science](http://moreno.ss.uci.edu/)*, by Linton C. Freeman, in English and several other languages (2004; [follow-up paper, 2011](http://moreno.ss.uci.edu/91.pdf)).
*   *[Inside Criminal Networks](https://www.springer.com/us/book/9780387095257)*, by Carlo Morselli (2009).
*   *[Networks in Social Policy Problems](http://www.cambridge.org/mx/academic/subjects/physics/statistical-physics/networks-social-policy-problems)*, edited by Balázs Vedres and Marco Scotti (2012).
*   *[The Oxford Handbook of the Economics of Networks](https://global.oup.com/academic/product/the-oxford-handbook-of-the-economics-of-networks-9780199948277)*, edited by Yann Bramoullé, Andrea Galeotti and Brian Rogers (2016).
*   *[Policy Debates as Dynamic Networks: German Pension Politics and Privatization Discourse](http://www.campus.de/buecher-campus-verlag/wissenschaft/politikwissenschaft/policy_debates_as_dynamic_networks-10287.html)*, by Philip Leifeld (2016).
*   *[Theories of Communication Networks](https://global.oup.com/academic/product/theories-of-communication-networks-9780195160376)*, by Peter Monge and Nosh Contractor (2003).
*   *[Die Verbundenheit der Dinge. Eine Kulturgeschichte der Netze und Netzwerke \[The Connectedness of Things. A Cultural History of Nets and Networks\]](http://www.kulturverlag-kadmos.de/buch/die-verbundenheit-der-dinge.html)*, by Sebastian Gießmann, in German (2014).
*   *[Verdeckte soziale Netzwerke im Nationalsozialismus. Die Entstehung und Arbeitsweise von Berliner Hilfsnetzwerken für verfolgte Juden \[Hidden Social Networks in National Socialism: The origins and working methods of Berlin assistance networks for persecuted Jews\]](http://www.degruyter.com/view/product/432196)*, by Marten Düring, in German (2015; [related publications](http://martenduering.com/research/covert-networks-during-the-holocaust/) and [video presentation in English](https://www.youtube.com/watch?v=SlQ7stSU-9w)).

### Conferences / Topic-specific

*   [CompleNet - International Workshop on Complex Networks](http://complenet.org/).
*   [GD - International Symposium on Graph Drawing and Network Visualization](http://www.graphdrawing.org/symposia.html).
*   [Sunbelt - Social Networks Conference of the International Network for Social Network Analysis](http://www.insna.org/archives.html) - Organized by the International Network for Social Network Analysis (INSNA).

### Courses / Topic-specific

*   [Graph Theory (Mathematics)](http://www.personal.psu.edu/cxg286/Math485.pdf), by Christopher Griffin - Full lecture notes (Penn State University, 2012).
*   [Network Analysis and Modeling (Computer Science)](http://tuvalu.santafe.edu/\~aaronc/courses/5352/), by Aaron Clauset - Full lecture slides and readings (University of Colorado, 2014).
*   [Network Science (Computer Science)](http://www.cc.gatech.edu/\~dovrolis/Courses/NetSci/), by Constantine Dovrolis - Mostly open access readings (Georgia Tech, 2015).
*   [Social Network Analysis with Pajek](http://mrvar.fdv.uni-lj.si/sola/info4/), by Andrej Mrvar (University of Ljubljana, 2016).

### Datasets / Topic-specific

*   [Bill Cosponsorship Networks in European Parliaments (⭐13)](https://github.com/briatte/parlnet) - Legislative cosponsorship networks, in R format.
*   [Eric D. Kolaczyk’s Network Datasets](http://math.bu.edu/people/kolaczyk/datasets.html).
*   [KONECT - The Koblenz Network Collection](http://konect.uni-koblenz.de/) - Includes, among other things, networks of collaboration in DBpedia and Wikipedia, GitHub ([companion handbook](http://arxiv.org/abs/1402.5500)).
*   [James H. Fowler’s Cosponsorship Network Data Page](http://jhfowler.ucsd.edu/cosponsorship.htm).
*   [Linton Freeman’s Network Data](http://moreno.ss.uci.edu/data.html) - Over 300 datasets of all sorts, in UCINET format.
*   [Mangal](http://mangal.io/) - Online platform to analyze, archive and share ecological network data ([preprint](http://biorxiv.org/content/early/2015/02/24/002634), [Python package (⭐2)](https://github.com/mangal-wg/pymangal), [R package (⭐11)](https://github.com/mangal-wg/rmangal)).
*   [Mark E.J. Newman’s Network Data](http://www-personal.umich.edu/\~mejn/netdata/) ([example visualizations](http://www-personal.umich.edu/\~mejn/networks/)).
*   [Norwegian Interlocking Directorate, 2002-2011](http://www.boardsandgender.com/data.php) - Two-mode and one-mode data on gender representation in Norwegian firms.
*   [tnet Datasets](https://toreopsahl.com/datasets/) - Weighted network data.

### Professional Groups / Topic-specific

*   [GDR ARSHS - GDR Analyse de réseaux en sciences humaines et sociales](http://arshs.hypotheses.org/), in French - Research group based in Paris.
*   [NetSci - Network Science Society](http://www.netscisociety.net/).

### Professional Groups / Research Groups (USA)

*   [Channing Division of Network Medicine](http://www.brighamandwomens.org/research/depts/medicine/channing/default.aspx) - Research division within the Department of Medicine at Brigham and Women’s Hospital.
*   [Peter J. Mucha’s Research Group at the University of North Carolina at Chapel Hill](http://mucha.web.unc.edu/networks/).

### Professional Groups / Research Groups (Other)

*   [Complex Networks](http://www.complexnetworks.fr/) - Research group based in Paris.
*   [Forschungscluster der Universitäten Trier und Mainz “Gesellschaftliche Abhängigkeiten und soziale Netzwerke”](http://www.netzwerk-exzellenz.uni-trier.de/), in German.
*   [MelNet Social Network Research Group, Swinburne University of Technology](http://www.swinburne.edu.au/fbl/research/transformative-innovation/our-research/MelNet-social-network-group/).
*   [Netzwerkerei](http://netzwerkerei.org/) - Historical research project on the connections between Jewish intellectuals.
*   [Redes-Sociales](http://www.redes-sociales.net/), in Spanish - Information network based at the Universitat Autònoma de Barcelona.
*   [SoNAR-C - Social Network Analysis Research Center, University of Italian Switzerland (USi)](http://www.sonarcenter.eco.usi.ch/).
*   [Topographies of Entanglements. Mapping Medieval Networks](https://oeaw.academia.edu/TopographiesofEntanglements) - Research platform based at the Austrian Academy of Sciences that focuses on applying network theory and visualisation to medieval history.
*   [Virtual Observatory for the Study of Online Networks (VOSON)](http://vosonlab.net/) - Research and software development project located at the Australian National University.

### Review Articles / Archeological and Historical Networks

*   [Formale Methoden der Netzwerkanalyse in den Geschichtswissenschaften: Warum und Wie? \[Formal Network Methods in History: Why and How?\]](http://www.studienverlag.at/data.cfm?vpath=openaccess/oezg-12012-lemercier\&download=yes), in German ([preprint in English](http://halshs.archives-ouvertes.fr/halshs-00521527); *Österreichische Zeitschrift für Geschichtswissenschaften*, 2012).
*   [Introduction à la visualisation de données : l’analyse de réseau en histoire](http://www.martingrandjean.ch/introduction-visualisation-de-donnees-analyse-de-reseau-histoire/), in French (*Geschichte und Informatik*, 2015).
*   [Networks and History](http://onlinelibrary.wiley.com/doi/10.1002/cplx.10054/abstract) (*Complexity*, 2002).
*   [Networks of Power in Archaeology](http://www.annualreviews.org/doi/abs/10.1146/annurev-anthro-102313-025901) (*Annual Review of Anthropology*, 2014).
*   [Netzwerkanalyse in den Geschichtswissenschaften. Historische Netzwerkanalyse als Methode für die Erforschung von historischen Prozessen](https://www.academia.edu/449150/Netzwerkanalyse_in_den_Geschichtswissenschaften._Historische_Netzwerkanalyse_als_Methode_f%C3%BCr_die_Erforschung_von_historischen_Prozessen), in German (*[Prozesse. Formen, Dynamiken, Erklärungen](https://www.springer.com/de/book/9783531176604)*, 2015).
*   [The Roots and Shoots of Archaeological Network Analysis: A Citation Analysis and Review of the Archaeological Use of Formal Network Methods](https://www.academia.edu/6925120/Brughmans_T._2014_._The_roots_and_shoots_of_archaeological_network_analysis_A_citation_analysis_and_review_of_the_archaeological_use_of_formal_network_methods._Archaeological_Review_from_Cambridge_29_1_) (*Archaeological Review from Cambridge*, 2014).
*   [Thinking Through Networks: A Review of Formal Network Methods in Archaeology](http://link.springer.com/article/10.1007/s10816-012-9133-8) (*Journal of Archaeological Method and Theory*, 2013).

### Review Articles / Biological, Ecological and Disease Networks

*   [Structure and Dynamics of Molecular Networks: A Novel Paradigm of Drug Discovery. A Comprehensive Review](http://www.sciencedirect.com/science/article/pii/S0163725813000284) - Also includes an impressive list of network analysis software (*Pharmacology & Therapeutics*, 2013).

### Review Articles / Complex and Multilayer Networks

*   [Complex Systems and Networks](http://science.sciencemag.org/content/325/5939) (special issue of *Science*, 2009).
*   [The Structure and Function of Complex Networks](http://epubs.siam.org/doi/abs/10.1137/S003614450342480) (*SIAM Review*, 2003).

### Review Articles / Network Modeling

*   [Introduction to Stochastic Actor-Based Models for Network Dynamics](http://www.sciencedirect.com/science/article/pii/S0378873309000069) ([preprint](http://www.stats.ox.ac.uk/\~snijders/SnijdersSteglichVdBunt2009.pdf); *Social Networks*, 2010).
*   Navigating the Range of Statistical Tools for Inferential Network Analysis (*American Journal of Political Science*, forthcoming 2016).
*   [Statistical Models for Social Networks](http://www.annualreviews.org/doi/abs/10.1146/annurev.soc.012809.102709) (*Annual Review of Sociology*, 2011).
*   [A Survey of Statistical Network Models](https://dl.acm.org/citation.cfm?id=1734795) - Book-length review ([preprint](http://arxiv.org/abs/0912.5410); *Foundations and Trends in Machine Learning*, 2010).
*   [A Unified View of Generative Models for Networks: Models, Methods, Opportunities, and Challenges](http://arxiv.org/abs/1411.4070) ([video presentation](http://www.birs.ca/events/2015/5-day-workshops/15w5080/videos/watch/201504200944-Jacobs.html); [NIPS 2014 workshop](https://nips.cc/Conferences/2014/Schedule?type=Workshop) on “[Networks: From Graphs to Rich Data](https://410f84824e101297359cc81c78f45c7c079eb26c.googledrive.com/host/0Bz6WHrWac3FrWnA5MjZqb3lWa2c/)”).

### Review Articles / Network Visualization

*   [Graphical Techniques for Exploring Social Network Data](http://moreno.ss.uci.edu/87.pdf) (*Models and Methods in Social Network Analysis*, 2005).
*   [Methods of Social Network Visualization](http://moreno.ss.uci.edu/90.pdf) (*Encyclopedia of Complexity and Systems Science*, 2009; [poster version](http://www.pfeffer.at/data/visposter/)).
*   [Social Networks](http://moreno.ss.uci.edu/93.pdf) (*Handbook of Graph Drawing and Visualization*, 2013).

### Review Articles / Social, Economic and Political Networks

*   [Brokerage](http://www.annualreviews.org/doi/abs/10.1146/annurev-soc-081309-150054) (*Annual Review of Sociology*, 2012).
*   [Birds of a Feather: Homophily in Social Networks](http://www.annualreviews.org/doi/abs/10.1146/annurev.soc.27.1.415) (*Annual Review of Sociology*, 2001).

### Selected Papers / Social, Economic and Political Networks

*   [Birds of a Feather, Or Friend of a Friend? Using Exponential Random Graph Models to Investigate Adolescent Social Networks](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2831261/), by Steven M. Goodreau, James A. Kitts and Martina Morris - Accessible introduction to the logic and application of exponential random graph modeling (*Demography*, 2001).
*   [Chains of Affection: The Structure of Adolescent Romantic and Sexual Networks](http://www.soc.duke.edu/\~jmoody77/chains.pdf), by Peter S. Bearman, James Moody and Katherine Stovel - Classic example of topological network analysis applied to a network of affective and sexual ties (*American Journal of Sociology*, 2004).
*   [Coauthorship and Citation Patterns in the *Physical Review*](http://journals.aps.org/pre/abstract/10.1103/PhysRevE.88.012814), by Travis Martin *et al.* - Highly typical study of scientific publishing productivity and collaboration through temporal network analysis ([preprint](http://arxiv.org/abs/1304.0473); *Physical Review E*, 2013).
*   [The Convergence of Social and Technological Networks](https://www.cs.cornell.edu/home/kleinber/cacm08.pdf), by Jon Kleinberg - Discusses small-world effects and social contagion within the context of the Internet and social media (*Communications of the ACM*, 2008).
*   [Homophily and Contagion Are Generically Confounded in Observational Social Network Studies](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3328971/), by Cosma R. Shalizi and Andrew C. Thomas - Makes a very important point for the analysis of network diffusion and influence (*Sociological Methods and Research*, 2011).
*   [Network Theory, Plot Analysis](https://sydney.edu.au/intellectual-history/documents/moretti_network_theory_plot_analysis.pdf), by Franco Moretti - Example applications of (fictional) network analysis in literary studies (*New Left Review*, 2011).
*   [Social Networks and Causal Inference](http://link.springer.com/chapter/10.1007/978-94-007-6094-3_17), by Tyler J. VanderWeele and Weihua An - Reviews the different ways in which network analysis can produce meaningful causal statements, as well as the inherent limits of network analysis for doing so (*[Handbook of Causal Analysis for Social Research](http://link.springer.com/book/10.1007/978-94-007-6094-3)*, 2013).
*   [The Performativity of Networks](http://kieranhealy.org/files/papers/performativity.pdf), by Kieran Healy - Network analysis meets science studies: social networks, like financial markets, are highly subject to performativity, i.e. the possibility that reality might be altered by its theoretical inquiry (*European Journal of Sociology*, 2015).
*   [Robust Action and the Rise of the Medici, 1400-1434](http://home.uchicago.edu/\~jpadgett/papers/published/robust.pdf), by John F. Padgett and Christopher K. Ansell - Classic analysis of power relations in the Renaissance Florentine state (*American Journal of Sociology*, 1993).
*   [The Strength of Weak Ties](https://sociology.stanford.edu/sites/default/files/publications/the_strength_of_weak_ties_and_exch_w-gans.pdf), by Mark Granovetter - Arch-classic example of applying network analysis to a social issue: jobseeking (*American Journal of Sociology*, 1973).
*   [The Ties that Divide: A Network Analysis of the International Monetary System, 1890–1910](http://www.stats.ox.ac.uk/\~snijders/FlandreauJobst2005.pdf) (*The Journal of Economic History*, 2005) and [The Empirics of International Currencies: Network Externalities, History and Persistence](http://onlinelibrary.wiley.com/doi/10.1111/j.1468-0297.2009.02219.x/abstract) (*The Economic Journal*, 2009), both by Marc Flandreau and Clemens Jobst - Network analysis of the foreign exchange system in the late 19th century ([data](http://eh.net/database/international-currencies-1890-1910/)).

### Software / Social, Economic and Political Networks

*   [CFinder](http://www.cfinder.org/) - Cross-platform Java program to identify clusters and communities through the Clique Percolation Method (CPM).
*   [Circos](http://circos.ca/) - Cross-platform program to produce circular layouts of network data, written in Perl.
*   [E-Net](https://sites.google.com/site/enetsoftware1/) - Windows program for ego network analysis.
*   [easyN](http://www.esyn.org/) - Online tool aimed at representing and sharing gene interaction networks as well as Petri net models.
*   [Nodegoat](http://nodegoat.net/) - Web-based data management, network analysis and visualisation environment ([blog](http://nodegoat.net/blog)).
*   [Palladio](http://palladio.designhumanities.org/) - Web-based spatial network visualization tool by the [Humanities + Design research lab at Stanford University](http://hdlab.stanford.edu/projects/palladio/).
*   [PIGALE - Public Implementation of a Graph Algorithm Library and Editor](http://pigale.sourceforge.net/) - Windows program and C++ library to analyze planar graphs.
*   [PNet](http://www.swinburne.edu.au/fbl/research/transformative-innovation/our-research/MelNet-social-network-group/PNet-software/index.html) - Simulation and estimation of (one-mode and multilevel) exponential random graph models (ERGMs), written in Java for Windows.
*   [Segrada](http://segrada.org/) - Cross-platform tool to build and visualize semantic graph databases.
*   [SocNetV - Social Network Visualizer](http://socnetv.sourceforge.net/) - Cross-platform program that includes a [simple Web crawler](http://socnetv.sourceforge.net/news/?post=socnetv-v16-released-with-a-working-web-crawler) to construct hyperlink networks.
*   [SoNIA - Social Network Image Animator](http://web.stanford.edu/group/sonia/) - Tool to visualize dynamic or longitudinal network data. Formerly a [Java program](https://sourceforge.net/projects/sonia/) ([example movies](http://www.soc.duke.edu/\~jmoody77/NetMovies/index.htm)), now developed as the ndtv R package.
*   [SPaTo Visual Explorer](http://www.spato.net/) - Cross-platform program for the visualization and exploration of complex networks.
*   [StOCNET](http://www.gmw.rug.nl/\~stocnet/StOCNET.htm) - Several Windows programs developed by the same team as Siena.

### Software / Algorithms

*   [MixNet - Erdös-Rényi Mixture Model for Networks](http://ssbgroup.fr/mixnet.html) - Community detection method, available in C++ and R.
*   [OSLOM2 - Order Statistics Local Optimization Method](http://www.oslom.org/) - Clustering algorithm.

### Software / C / C++

*   [BGL - Boost Graph Library](http://www.boost.org/doc/libs/1_60_0/libs/graph/doc/) - C++ library that provides a generic interface to access graph structures.
*   [MapEquation](http://www.mapequation.org/) - C++ code for the Infomap method of multilevel community detection.
*   [OGDF - Open Graph Drawing Framework](http://www.ogdf.net/) - Self-contained C++ class library for diagram, network and tree layouts.

### Software / JavaScript

*   [Popoto.js](http://www.popotojs.com/) - Library based on d3.js that provides a graph based search interface.

### Software / MATLAB

*   [Complex Networks Package for MatLab](http://www.levmuchnik.net/Content/Networks/ComplexNetworksPackage.html).
*   [CONTEST](http://www.maths.strath.ac.uk/research/groups/numerical_analysis/contest) - Random network toolbox that implements nine network models.
*   [Generalized Louvain](http://netwiki.amath.unc.edu/GenLouvain/GenLouvain) - Variant of the Louvain community detection algorithm.
*   [MatlabBGL](http://dgleich.github.io/matlab-bgl/) - Graph library based on the C++ Boost Graph Library.

### Software / Python

*   [npartite (⭐12)](https://github.com/ike002jp/npartite) - Python algorithms for community detection in n-partite networks.
*   [python-louvain](http://perso.crans.org/aynaud/communities/) - A solid implementation of Louvain community detection algorithm.
*   [TQ (Temporal Quantities)](http://vladowiki.fmf.uni-lj.si/doku.php?id=tq) - Python 3 library for temporal network analysis.

### Software / R

*   [CCAS (⭐4)](https://github.com/matthewjdenny/CCAS) - Statistical model for communication networks.
*   [concoR (⭐8)](https://github.com/aslez/concoR) - Implementation of the CONCOR network blockmodeling algorithm ([blog post](http://badhessian.org/2015/05/concor-in-r/)).
*   [ContentStructure (⭐3)](https://github.com/matthewjdenny/ContentStructure) - Implements an extension to the [Topic-Partitioned Multinetwork Embeddings (TPME) model](http://dirichlet.net/pdf/krafft12topic-partitioned.pdf).
*   [lpNet](https://www.bioconductor.org/packages/release/bioc/html/lpNet.html) - Linear programming model aimed at infering biological (signalling, gene) networks.
*   [spectralGOF](http://people.bu.edu/jccs/spectralGOF.html) - Computes the spectral goodness of fit (SGOF), a measure of how well a network model explains the structure of an observed network.

### Software / Syntaxes

*   [GraphML](http://graphml.graphdrawing.org/) - Comprehensive and easy-to-use file format for graphs ([handbook chapter](https://www.uni-konstanz.de/mmsp/pubsys/publishedFiles/BrEiLe10.pdf)).
*   [JUNG - Java Universal Network/Graph Framework](http://jung.sourceforge.net/) - Extensible library to represent network objects.
*   [TLP - Tulip Software Graph Format](http://tulip.labri.fr/TulipDrupal/?q=tlp-file-format) - Graph syntax used by the Tulip software framework.
*   [Cypher](http://neo4j.com/docs/stable/cypher-query-lang.html) - Graph query language used by [Neo4j](http://neo4j.com/).

### Software / Tutorials

*   [Interactive and Dynamic Network Visualization in R](http://curleylab.psych.columbia.edu/netviz/) and JavaScript libraries (2016).
*   [Nodegoat and Palladio: Introductory Workshop](https://www.academia.edu/11450425/Nodegoat_and_Palladio_Introductory_Workshop_by_Emmanuelle_Chaze) - Aimed at humanists (2015).

### Varia / Tutorials

*   [Computer Technologies for the Historical Research of Intellectual Networks](https://www.youtube.com/playlist?list=PLz79Il7EOvUJxdQ9r2IefFtr--BNkfOa7) - Series of videos by historians, featuring Marten Düring and Scott Weingart.
*   [David Knoke on Network Analysis](https://thesocietypages.org/methods/2015/01/30/david-knoke-on-network-analysis/) - 20-minute interview that discusses the uses and benefits of network analysis, drawing upon Knoke’s research on terrorist networks.
*   [Glossary of Terms for Statistical Network Models](https://statnet.org/trac/raw-attachment/wiki/Resources/glossary.pdf).
*   [Linton C. Freeman’s Social Network Research Publications](http://moreno.ss.uci.edu/pubs.html), spanning from 1955 to today.
*   [Mapping the Republic of Letters](http://republicofletters.stanford.edu/) - Research project on early-modern scholarship ([underlying software](http://www.densitydesign.org/research/knot/)).
*   [NetSciEd - Network Science in Education](https://sites.google.com/a/binghamton.edu/netscied/home) - International initiative aimed at improving network literacy.
*   [The Networks Network](https://groups.google.com/forum/?hl=en-GB#!forum/the-networks-network) - Mailing-list (mostly historians from the HNR network).
*   [Should I do Social Network Analysis?](https://cvcedhlab.hypotheses.org/125).
*   [Social Network Analysis in DBpedia](http://othes.univie.ac.at/12285/1/2010-10-14_0703857.pdf) - Highly didactic Master’s dissertation, showing how to use SPARQL and Pajek.
*   [SNA-DE Mailing-List](https://dlist.server.uni-frankfurt.de/mailman/listinfo/sna-de), in German.
*   [SPARQL for R Tutorial - Hollywood Social Network Analysis](http://semanticweb.cs.vu.nl/R/sparql_hollywood/sparql_hollywood.html) - Also uses Gephi.
*   [A Sociology Citation Network](http://nealcaren.web.unc.edu/a-sociology-citation-network/) and [A Co-citation Network for Philosophy](https://kieranhealy.org/blog/archives/2013/06/18/a-co-citation-network-for-philosophy/) - Examples of scientific co-citation networks.
*   [Visual Complexity. An Exploration on Mapping Complex Networks](http://www.visualcomplexity.com/vc/) - Tons of beautiful network and tree visualizations ([book](http://www.visualcomplexity.com/vc/book/), also in Chinese and French).

### Varia / Blog Series

*   [Blog Posts About Networks by Aaron Clauset](https://www.cs.unm.edu/\~aaron/blog/archives/networks/index.htm).
*   [Blog Posts About Networks by Cosma R. Shalizi](http://bactra.org/weblog/cat_networks.html).
*   Blog posts about networks on [R-Bloggers](http://www.r-bloggers.com/), an aggregator of R blogs:
    *   [Networks](http://www.r-bloggers.com/?s=networks).
    *   [Social Network Analysis](http://www.r-bloggers.com/?s=social+network+analysis).
*   Martin Grandjean’s blog posts about (mostly) network visualization, in English and French:
    *   [Network Analysis](http://www.martingrandjean.ch/tag/analyse-de-reseau/).
    *   [Social Networks](http://www.martingrandjean.ch/tag/reseaux-sociaux/).
*   [Netze und Netzwerke](http://netzeundnetzwerke.de/), in English and German - Blog on the history of network analysis, by Sebastian Gießmann ([old blog](http://www.netzeundnetzwerke.de/old/)).
*   Yannick Rochat’s blog posts about digital humanities, in English and French:
    *   [Character Networks](http://yro.ch/tag/character-network/).
    *   [Network Analysis](http://yro.ch/tag/network-analysis/).

### Varia / Fictional Networks

*   [Character Co-Occurrences in Victor Hugo’s *Les Misérables*](http://bokeh.pydata.org/en/latest/docs/gallery/les_mis.html), plotted as an adjacency matrix, written in Python (+ Javascript).
*   [Events in the *Game of Thrones*](http://www.jeromecukier.net/projects/agot/events.html) and [Places in the *Game of Thrones*](http://www.jeromecukier.net/projects/agot/places.html) - Networked chronologies of character alliances, kills and travels in the book series, drawn with d3.js.
*   [Lessons on Exponential Random Graph Modeling from *Grey’s Anatomy* hook-ups](http://badhessian.org/2012/09/lessons-on-exponential-random-graph-modeling-from-greys-anatomy-hook-ups/) (using R).
*   [Network Analysis of Shakespeare’s *Macbeth*](https://mboudour.github.io/2015/10/28/Shakespeare's-Macbeth-Network.html) (using Python).
*   [The Network and Trajectories of Transitions among Sentential Co-Occurrences of Characters of Arthur Conan Doyle’s *A Study in Scarlet*](https://mboudour.github.io/2016/04/17/Arthur-Conan-Doyle's-A-Study-in-Scarlet-Network-&-Trajectories.html) (using Python; [code (⭐6)](https://github.com/mboudour/WordNets/blob/master/ArthurConanDoyle_AStudyInScarlet_Network%26Trajectories.ipynb)).
*   [Network Visualization: Mapping Shakespeare’s Tragedies](http://www.martingrandjean.ch/network-visualization-shakespeare/).
*   [Social Network Analysis of *Alice in Wonderland*](http://www.cs.columbia.edu/\~apoorv/Homepage/Publications_files/naacl2012.pdf).
*   [*Star Wars* Social Networks: The Force Awakens](http://evelinag.com/blog/2016/01-25-social-network-force-awakens/index.html) - Also an example of a social network analysis written in F#.
*   [Universal Properties of Mythological Networks](http://epljournal.edpsciences.org/articles/epl/abs/2012/14/epl14724/epl14724.html) ([preprint](http://arxiv.org/abs/1205.4324)).

### Varia / Network Science

*   [The Invasion of the Physicists](http://www.sciencedirect.com/science/article/pii/S0378873304000309) - How “network *science*” came up.
*   [Isolated Social Networkers](http://crookedtimber.org/2005/05/19/isolated-social-networkers/), [Networks and Netwars](http://bactra.org/weblog/347.html) and [The Inter-Disciplinary Politics of Interdisciplinary Research or, “Hey, That Was My Idea First.”](https://www.cs.unm.edu/\~aaron/blog/archives/2005/05/the_interdiscip.htm) - Series of blog posts that predate the advent of “network science” as a buzzword, but that touch upon the same issues as those now being discussed under that heading.

### Varia / Two-Mode Networks

*   [Basic Notions for the Analysis of Large Two-mode Networks](http://www.sciencedirect.com/science/article/pii/S0378873307000494)  ([preprint](https://www-complexnetworks.lip6.fr/\~latapy/Publis/socnet07.pdf), [related code](https://www-complexnetworks.lip6.fr/\~latapy/Bip/); *Social Networks*, 2008).
*   [Generalized Blockmodeling of Two-mode Network Data](http://www.sciencedirect.com/science/article/pii/S0378873304000036) ([preprint](http://vlado.fmf.uni-lj.si/pub/networks/doc/preprint/TwoMode.pdf)).
*   [Generalized Two-Mode Cores](http://www.sciencedirect.com/science/article/pii/S0378873315000271).
*   [Working with Bipartite/Affiliation Network Data in R](https://solomonmessing.wordpress.com/2012/09/30/working-with-bipartiteaffiliation-network-data-in-r/) (2012).

---

- Prev: [Apr 25 - May 01, 2016](/content/2016/17/README.md)
- Next: [Apr 11 - Apr 17, 2016](/content/2016/15/README.md)