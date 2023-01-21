# Awesome List Updates on Apr 23, 2016

8 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Git Addons](/content/stevemao/awesome-git-addons/README.md)

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

## [2. Awesome Cyclejs](/content/cyclejs-community/awesome-cyclejs/README.md)

### Learn / Example Applications

*   [grozen/trends-cycle ★3 (⭐3)](https://github.com/grozen/trends-cycle) - Slack trend searching written in Cycle.js
*   [MarcCloud/magic-cart ★6 (⭐6)](https://github.com/MarcCloud/magic-cart) - Simple shopping cart of a magic creatures store.
*   [kibin/cycle-example-who-to-follow ★16 (⭐15)](https://github.com/kibin/cycle-example-who-to-follow) - Small example partly implements twitter’s who to follow box using github api.

### Libraries / Utilities

*   [cgeorg/sinject ★10 (⭐10)](https://github.com/cgeorg/sinject) - a dependency injection tool supporting Cycle's circular dependencies
*   [madcapjake/earlhyperscript ★2 (⭐2)](https://github.com/MadcapJake/earl-hyperscript) - A helper function and macro for using Earl Grey's [document-building syntax](https://breuleux.github.io/earl-grey/doc.html#documentbuildingsyntax) with Cycle.js.

### Libraries / Components

*   [mciparelli/cyclejs-gravatar ★0 (⭐0)](https://github.com/mciparelli/cyclejs-gravatar) - Cycle.js component for rendering a gravatar profile image.

## [3. Awesome Microservices](/content/mfornos/awesome-microservices/README.md)

### PHP / Scala

*   [API Platform](https://api-platform.com/) - API-first web framework on top of Symfony with JSON-LD, Schema.org and Hydra support.
*   [Phalcon](https://phalconphp.com/) - Full-stack PHP framework delivered as a C-extension.

### Web APIs / Scala

*   [Hydra](http://www.hydra-cg.com/) - Specifications for interoperable, hypermedia-driven Web APIs.

### Data Formats / Scala

*   [JSON-LD](http://json-ld.org/) - JSON for Linking Data.

### Vocabularies / Scala

*   [Schema.org](http://schema.org/) - Collaborative, community activity with a mission to create, maintain, and promote schemas for structured data on the Internet, on web pages, in email messages, and beyond.

## [4. Awesome Elixir](/content/h4cc/awesome-elixir/README.md)

### Third Party APIs

*   [pay (⭐26)](https://github.com/era/pay) - An Elixir Lib to deal with Paypal and other payment solutions.

## [5. Awesome Network Analysis](/content/briatte/awesome-network-analysis/README.md)

### Books / Dissemination

*   *[Nexus. Small Worlds and the Groundbreaking Theory of Networks](http://books.wwnorton.com/books/Nexus/)*, by Mark Buchanan (2003).

### Books / Topic-specific

*   *[Theories of Communication Networks](https://global.oup.com/academic/product/theories-of-communication-networks-9780195160376)*, by Peter Monge and Nosh Contractor (2003).

### Conferences / Topic-specific

*   [CompleNet - International Workshop on Complex Networks](http://complenet.org/).

### Professional Groups / Research Groups (Other)

*   [Virtual Observatory for the Study of Online Networks (VOSON)](http://vosonlab.net/) - Research and software development project located at the Australian National University.

### Software / Social, Economic and Political Networks

*   [Circos](http://circos.ca/) - Cross-platform program to produce circular layouts of network data, written in Perl.
*   [easyN](http://www.esyn.org/) - Online tool aimed at representing and sharing gene interaction networks as well as Petri net models.
*   [Segrada](http://segrada.org/) - Cross-platform tool to build and visualize semantic graph databases.
*   [SPaTo Visual Explorer](http://www.spato.net/) - Cross-platform program for the visualization and exploration of complex networks.

### Software / C / C++

*   [MapEquation](http://www.mapequation.org/) - C++ code for the Infomap method of multilevel community detection.

### Software / JavaScript

*   [Popoto.js](http://www.popotojs.com/) - Library based on d3.js that provides a graph based search interface.

### Software / MATLAB

*   [Complex Networks Package for MatLab](http://www.levmuchnik.net/Content/Networks/ComplexNetworksPackage.html).
*   [Generalized Louvain](http://netwiki.amath.unc.edu/GenLouvain/GenLouvain) - Variant of the Louvain community detection algorithm.
*   [MatlabBGL](http://dgleich.github.io/matlab-bgl/) - Graph library based on the C++ Boost Graph Library.

### Software / Python

*   [npartite (⭐12)](https://github.com/ike002jp/npartite) - Python algorithms for community detection in n-partite networks.

### Varia / Tutorials

*   [Computer Technologies for the Historical Research of Intellectual Networks](https://www.youtube.com/playlist?list=PLz79Il7EOvUJxdQ9r2IefFtr--BNkfOa7) - Series of videos by historians, featuring Marten Düring and Scott Weingart.
*   [Mapping the Republic of Letters](http://republicofletters.stanford.edu/) - Research project on early-modern scholarship ([underlying software](http://www.densitydesign.org/research/knot/)).
*   [NetSciEd - Network Science in Education](https://sites.google.com/a/binghamton.edu/netscied/home) - International initiative aimed at improving network literacy.
*   [Visual Complexity. An Exploration on Mapping Complex Networks](http://www.visualcomplexity.com/vc/) - Tons of beautiful network and tree visualizations ([book](http://www.visualcomplexity.com/vc/book/), also in Chinese and French).

## [6. Awesome Book Authoring](/content/TalAter/awesome-book-authoring/README.md)

### Royalties, Advances, and Other Money Stuff

*   [Writing A Technical Book: Is It Worthwhile?](http://www.fasterj.com/articles/bookwriting.shtml) - The benefits for writing a technical book, and the basics of how book advances work.
*   [How Book Advances Work – A Simple Explanation for Writers](http://www.writersdigest.com/online-editor/how-book-advances-work-a-simple-explanation-for-writers)
*   [Typical O'Reilly Advance Structure](http://web.archive.org/web/20130704110948/http://oreilly.com/oreilly/author/ch03.html#advance)

## [7. Rbooks](/content/RomanTsegelskyi/rbooks/README.md)

### Data Science

#### Data Manipulation with R, Second Edition [\[Packt\]](https://www.packtpub.com/big-data-and-business-intelligence/data-manipulation-r-second-edition)

<img src="http://ecx.images-amazon.com/images/I/51Jwp-z343L._SX403_BO1,204,203,200_.jpg" width="200px" />

This book starts with the installation of R and how to go about using R and its libraries. We then discuss the mode of R objects and its classes and then highlight different R data types with their basic operations.

The primary focus on group-wise data manipulation with the split-apply-combine strategy has been explained with specific examples. The book also contains coverage of some specific libraries such as lubridate, reshape2, plyr, dplyr, stringr, and sqldf. You will not only learn about group-wise data manipulation, but also learn how to efficiently handle date, string, and factor variables along with different layouts of datasets using the reshape2 package.

By the end of this book, you will have learned about text manipulation using stringr, how to extract data from twitter using twitteR library, how to clean raw data, and how to structure your raw data for data mining.

## [8. Awesome R](/content/qinwf/awesome-R/README.md)

### Other Interpreters

*   [CXXR](https://www.cs.kent.ac.uk/projects/cxxr/) - Refactorising R into C++.
*   [pqR](http://www.pqr-project.org/) - a "pretty quick" implementation of R
*   [renjin](http://www.renjin.org/) - a JVM-based interpreter for R.
*   [rho (⭐131)](https://github.com/rho-devel/rho) - Refactor the interpreter of the R language into a fully-compatible, efficient, VM for R.
*   [TERR](http://spotfire.tibco.com/discover-spotfire/what-does-spotfire-do/predictive-analytics/tibco-enterprise-runtime-for-r-terr) - TIBCO Enterprise Runtime for R.

---

- Prev: [Apr 24, 2016](/content/2016/04/24/README.md)
- Next: [Apr 22, 2016](/content/2016/04/22/README.md)