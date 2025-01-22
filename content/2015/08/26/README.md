# Awesome List Updates on Aug 26, 2015

7 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Dart](/content/yissachar/awesome-dart/README.md)

### Tools

*   [gulp-dart (⭐4)](https://github.com/agudulin/gulp-dart) - A gulp plugin for compiling Dart code to JavaScript using dart2js.

## [2. Awesome Clojure](/content/razum2um/awesome-clojure/README.md)

### GUI

*   [seesaw (⭐1.4k)](https://github.com/daveray/seesaw)

## [3. Awesome Jvm](/content/deephacks/awesome-jvm/README.md)

### Bytecode

*   [asmtools](https://wiki.openjdk.java.net/display/CodeTools/asmtools) - Used to develop tools for the production of Java .class files.

### Memory and concurrency

*   [fasttuple (⭐137)](https://github.com/boundary/fasttuple) - Collections that are laid out adjacently in both on- and off-heap memory.
*   [netty-buffers](http://netty.io/wiki/using-as-a-generic-library.html#wiki-h2-1) - Memory buffer pool implementation similar to jemalloc.
*   [ObjectLayout](http://objectlayout.org) - A layout-optimized Java data structure package.

### Network

*   [pcap4j (⭐1k)](https://github.com/kaitoy/pcap4j) - Java library for capturing, crafting, and sending packets using libpcap.

### Nix tools

*   [jstat](https://docs.oracle.com/javase/8/docs/technotes/tools/unix/jstat.html) - Monitors GC and compiler statistics in the JVM.

### Profilers

*   [JOL](http://openjdk.java.net/projects/code-tools/jol/) - Analyze actual object layout schemes, footprint, and references in JVMs.

## [4. Awesome Pascal](/content/Fr0sT-Brutal/awesome-pascal/README.md)

### RAD Studio IDE plugins/wizards

*   [Delphi Package Installer (DelphiPI)](https://bitbucket.org/idursun/delphipi). Tool which aids you installing components to your Delphi IDE. DelphiPI automatically resolves dependencies between packages, compiles, installs and adds source paths to your IDE.
*   [ResEd (⭐82)](https://github.com/chaosben/theunknownones). Expert for Delphi 2005, 2006, 2007, 2009, 2010 and XE. This expert is designed for editing the resource files (.res; .resx) that are linked to the active project. It will automatically search for all occurrences of {$R xyz.res} lines and will open/create resourcefiles for them. The expert registers itself in the menubar of Delphi under View.

### Other

*   [WMI Delphi Code Creator (⭐161)](https://github.com/RRUZ/wmi-delphi-code-creator). Allows you to generate Object Pascal, Oxygene, C++ and C# code to access the WMI (Windows Management Instrumentation) classes, events and methods. Also includes a set of tools to explorer and Query the content of the WMI.
*   [Delphi Dev. Shell Tools (⭐129)](https://github.com/RRUZ/delphi-dev-shell-tools). Windows shell extension with useful tasks for Object Pascal Developers (Delphi, Free Pascal).

## [5. Awesome Git Addons](/content/stevemao/awesome-git-addons/README.md)

### [gitflow (AVH Edition)](https://github.com/petervanderdoes/gitflow-avh)

### flow feature

    $ git flow feature
    $ git flow feature start awesome-feature
    $ git flow feature finish awesome-feature
    $ git flow feature delete awesome-feature

    $ git flow feature publish awesome-feature
    $ git flow feature pull remote awesome-feature
### flow release

    $ git flow release
    $ git flow release start awesome-release
    $ git flow release finish awesome-release
    $ git flow release delete awesome-release
### flow hotfix

    $ git flow hotfix
    $ git flow hotfix start awesome-release
    $ git flow hotfix finish awesome-release
    $ git flow hotfix delete awesome-release

### [hub](https://github.com/github/hub)

### clone

    $ git clone schacon/ticgit
    > git clone git://github.com/schacon/ticgit.git

    $ git clone -p schacon/ticgit
    > git clone git@github.com:schacon/ticgit.git

    $ git clone resque
    > git clone git@github.com/YOUR_USER/resque.git
### remote add

    $ git remote add rtomayko
    > git remote add rtomayko git://github.com/rtomayko/CURRENT_REPO.git

    $ git remote add -p rtomayko
    > git remote add rtomayko git@github.com:rtomayko/CURRENT_REPO.git

    $ git remote add origin
    > git remote add origin git://github.com/YOUR_USER/CURRENT_REPO.git
### fetch

    $ git fetch mislav
    > git remote add mislav git://github.com/mislav/REPO.git
    > git fetch mislav

    $ git fetch mislav,xoebus
    > git remote add mislav ...
    > git remote add xoebus ...
    > git fetch --multiple mislav xoebus
### cherry-pick

    $ git cherry-pick https://github.com/mislav/REPO/commit/SHA
    > git remote add -f --no-tags mislav git://github.com/mislav/REPO.git
    > git cherry-pick SHA

    $ git cherry-pick mislav@SHA
    > git remote add -f --no-tags mislav git://github.com/mislav/CURRENT_REPO.git
    > git cherry-pick SHA

    $ git cherry-pick mislav@SHA
    > git fetch mislav
    > git cherry-pick SHA
### am

    $ git am https://github.com/github/hub/pull/55
    [ downloads patch via API ]
    > git am /tmp/55.patch

    $ git am --ignore-whitespace https://github.com/davidbalbert/hub/commit/fdb9921
    [ downloads patch via API ]
    > git am --ignore-whitespace /tmp/fdb9921.patch
### apply

    $ git apply https://gist.github.com/8da7fb575debd88c54cf
    [ downloads patch via API ]
    > git apply /tmp/gist-8da7fb575debd88c54cf.txt
### fork

    $ git fork
    [ repo forked on GitHub ]
    > git remote add -f YOUR_USER git@github.com:YOUR_USER/CURRENT_REPO.git
### pull-request

    $ git pull-request
    [ opens text editor to edit title & body for the request ]
    [ opened pull request on GitHub for "YOUR_USER:feature" ]
### checkout

    $ git checkout https://github.com/github/hub/pull/73
    > git remote add -f --no-tags -t feature mislav git://github.com/mislav/hub.git
    > git checkout --track -B mislav-feature mislav/feature
### merge

    $ git merge https://github.com/github/hub/pull/73
    > git fetch git://github.com/mislav/hub.git +refs/heads/feature:refs/remotes/mislav/feature
    > git merge mislav/feature --no-ff -m 'Merge pull request #73 from mislav/feature...'
### create

    $ git create
    [ repo created on GitHub ]
    > git remote add origin git@github.com:YOUR_USER/CURRENT_REPO.git
### init

    $ git init -g
    > git init
    > git remote add origin git@github.com:YOUR_USER/REPO.git
### push

    $ git push origin,staging,qa bert_timeout
    > git push origin bert_timeout
    > git push staging bert_timeout
    > git push qa bert_timeout
### browse

    $ git browse
    > open https://github.com/YOUR_USER/CURRENT_REPO
### compare

    $ git compare refactor
    > open https://github.com/CURRENT_REPO/compare/refactor
### submodule

    $ git submodule add wycats/bundler vendor/bundler
    > git submodule add git://github.com/wycats/bundler.git vendor/bundler

## [6. Awesome Dotnet](/content/quozd/awesome-dotnet/README.md)

### Artificial Intelligence

*   [AIMLBot (Program#)](http://aimlbot.sourceforge.net/) - A small, fast, standards-compliant yet easily customizable implementation of an AIML (Artificial Intelligence Markup Language) based chatter bot in C#.

## [7. Awesome Elixir](/content/h4cc/awesome-elixir/README.md)

### Third Party APIs

*   [nadia (⭐365)](https://github.com/zhyu/nadia) - Telegram Bot API Wrapper written in Elixir.

---

- Prev: [Aug 27, 2015](/content/2015/08/27/README.md)
- Next: [Aug 25, 2015](/content/2015/08/25/README.md)