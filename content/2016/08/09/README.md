# Awesome List Updates on Aug 09, 2016

11 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Nodejs](/content/sindresorhus/awesome-nodejs/README.md)

### Packages / Filesystem

*   [filehound (⭐219)](https://github.com/nspragg/filehound) - Flexible and fluent interface for searching the file system.

## [2. Awesome Jvm](/content/deephacks/awesome-jvm/README.md)

### Communities

*   [Performance Java User's Group](https://plus.google.com/u/0/communities/107178245817384004088/) - For expert Java *developers* who want to push their systems to the next level

### Media

*   [Why JNI is slow?](https://www.youtube.com/watch?v=LoyBTqkSkZk) - Cliff Click
*   [JVM Language Summit 2016](https://www.youtube.com/playlist?list=PLX8CzqL3ArzUY6rQAQTwI_jKvqJxrRrP_) - JVM Language Summit 2016.

## [3. Awesome Php](/content/ziadoz/awesome-php/README.md)

### Table of Contents / Security

*   [VAddy](https://vaddy.net/) - A continuous security testing platform for web applications.

### Table of Contents / Build Tools

*   [Phing](https://www.phing.info/) - A PHP project build system inspired by Apache Ant.

## [4. Awesome Math](/content/rossant/awesome-math/README.md)

### Probability and Statistics / Statistics

*   [NIST Handbook of Statistical Methods](http://itl.nist.gov/div898/handbook/index.htm) - Resource on practical statistics directed towards scientists and engineers.

## [5. Awesome Elixir](/content/h4cc/awesome-elixir/README.md)

### Algorithms and Data structures

*   [data\_morph](https://hex.pm/packages/data_morph) - Create Elixir structs from data.

### HTTP

*   [Tube (⭐12)](https://github.com/narrowtux/Tube) - Pure Elixir WebSocket client library.

### Testing

*   [bypass (⭐912)](https://github.com/pspdfkit-labs/bypass) - Bypass provides a quick way to create a mock HTTP server with a custom plug.

### Third Party APIs

*   [exfacebook (⭐18)](https://github.com/oivoodoo/exfacebook) - Facebook API, written in Elixir using similar methods like Ruby koala gem.

## [6. Awesome Malware Analysis](/content/rshipp/awesome-malware-analysis/README.md)

### Debugging and Reverse Engineering / Other Resources

*   [RetDec](https://retdec.com/) - Retargetable machine-code decompiler with an
    [online decompilation service](https://retdec.com/decompilation/) and
    [API](https://retdec.com/api/) that you can use in your tools.

## [7. Awesome Dotnet Core](/content/thangchung/awesome-dotnet-core/README.md)

### Frameworks, Libraries and Tools / Security

*   [jose-jwt (⭐884)](https://github.com/dvsekhvalnov/jose-jwt) - Library for processing JOSE objects (JWT, JWA, JWS and related).

## [8. Awesome Dotnet](/content/quozd/awesome-dotnet/README.md)

### Game

*   [MonoGame (⭐10k)](https://github.com/MonoGame/MonoGame) - One framework for creating powerful cross-platform games

## [9. Git Cheat Sheet](/content/arslanbilal/git-cheat-sheet/README.md)

### Git-Flow

## Git-Flow

Improved [Git-flow (⭐5.2k)](https://github.com/petervanderdoes/gitflow-avh)

### Index

<hr>

### Setup

###### You need a working git installation as prerequisite. Git flow works on OSX, Linux and Windows.

##### OSX Homebrew:

    $ brew install git-flow-avh

##### OSX Macports:

    $ port install git-flow

##### Linux (Debian-based):

    $ sudo apt-get install git-flow

##### Windows (Cygwin):

###### You need wget and util-linux to install git-flow.

```bash
$ wget -q -O - --no-check-certificate https://raw.githubusercontent.com/petervanderdoes/gitflow/develop/contrib/gitflow-installer.sh install <state> | bash
```

<hr>

### Getting Started

###### Git flow needs to be initialized in order to customize your project setup. Start using git-flow by initializing it inside an existing git repository:

##### Initialize:

###### You'll have to answer a few questions regarding the naming conventions for your branches. It's recommended to use the default values.

```shell
git flow init
```

OR

###### To use default

```shell
git flow init -d
```

<hr>

### Features

###### Develop new features for upcoming releases. Typically exist in developers repos only.

##### Start a new feature:

###### This action creates a new feature branch based on 'develop' and switches to it.

    git flow feature start MYFEATURE

##### Finish up a feature:

###### Finish the development of a feature. This action performs the following:

###### 1) Merged MYFEATURE into 'develop'.

###### 2) Removes the feature branch.

###### 3) Switches back to 'develop' branch

    git flow feature finish MYFEATURE

##### Publish a feature:

###### Are you developing a feature in collaboration? Publish a feature to the remote server so it can be used by other users.

    git flow feature publish MYFEATURE

##### Getting a published feature:

###### Get a feature published by another user.

    git flow feature pull origin MYFEATURE

##### Tracking a origin feature:

###### You can track a feature on origin by using

    git flow feature track MYFEATURE

<hr>

### Make a Release

###### Support preparation of a new production release. Allow for minor bug fixes and preparing meta-data for a release

##### Start a release:

###### To start a release, use the git flow release command. It creates a release branch created from the 'develop' branch. You can optionally supply a \[BASE] commit sha-1 hash to start the release from. The commit must be on the 'develop' branch.

    git flow release start RELEASE [BASE]

###### It's wise to publish the release branch after creating it to allow release commits by other developers. Do it similar to feature publishing with the command:

    git flow release publish RELEASE

###### (You can track a remote release with the: `git flow release track RELEASE` command)

##### Finish up a release:

###### Finishing a release is one of the big steps in git branching. It performs several actions:

###### 1) Merges the release branch back into 'master'

###### 2) Tags the release with its name

###### 3) Back-merges the release into 'develop'

###### 4) Removes the release branch

    git flow release finish RELEASE

###### Don't forget to push your tags with `git push --tags`

<hr>

### Hotfixes

###### Hotfixes arise from the necessity to act immediately upon an undesired state of a live production version. May be branched off from the corresponding tag on the master branch that marks the production version.

##### Git flow hotfix start:

###### Like the other git flow commands, a hotfix is started with

    $ git flow hotfix start VERSION [BASENAME]

###### The version argument hereby marks the new hotfix release name. Optionally you can specify a basename to start from.

##### Finish a hotfix:

###### By finishing a hotfix it gets merged back into develop and master. Additionally the master merge is tagged with the hotfix version

    git flow hotfix finish VERSION

<hr>

### Commands

<p align="center">
    <img alt="Git" src="https://github.com/arslanbilal/git-cheat-sheet/raw/master/./Img/git-flow-commands.png" height="270" width="460">
</p>
<hr>

### Git flow schema

<p align="center">
    <img alt="Git" src="https://github.com/arslanbilal/git-cheat-sheet/raw/master/Img/git-flow-commands-without-flow.png">
</p>
<hr>

## [10. Awesome Tensorflow](/content/jtoy/awesome-tensorflow/README.md)

### Blog posts

*   [TensorFlow - Not Just For Deep Learning](http://terrytangyuan.github.io/2016/08/06/tensorflow-not-just-deep-learning/)

## [11. Awesome Choo](/content/choojs/awesome-choo/README.md)

### Contents / Official resources

*   [Docs (⭐6.7k)](https://github.com/yoshuawuyts/choo/blob/master/README.md)
*   [Handbook (⭐266)](https://github.com/yoshuawuyts/choo-handbook)
*   [Repo (⭐6.7k)](https://github.com/yoshuawuyts/choo)
*   [Twitter thread](https://twitter.com/yoshuawuyts/status/730087077803528193)

### Contents / Dependencies

*   [bel (⭐672)](https://github.com/shama/bel) - Create composable DOM elements using
    template strings.
*   [hyperx (⭐993)](https://github.com/substack/hyperx) - Convert template strings to
    library backends.
*   [nanoraf](https://github.com/yoshuawuyts/nanoraf) - Only call RAF when needed.

### Contents / Demos

*   [Input example](http://requirebin.com/?gist=e589473373b3100a6ace29f7bbee3186) - ([repo (⭐6.7k)](https://github.com/yoshuawuyts/choo/tree/master/examples/title))
*   [HTTP effects](https://hyperdev.com/#!/project/fork-fang)
*   [Mailbox routing (⭐6.7k)](https://github.com/yoshuawuyts/choo/tree/master/examples/mailbox)
*   [TodoMVC](http://shuheikagawa.com/todomvc-choo) - ([repo (⭐39)](https://github.com/shuhei/todomvc-choo))
*   [Grow](https://grow.static.land) - ([repo (⭐13)](https://github.com/sethvincent/grow))
*   [Chatbot](http://chootbot.herokuapp.com) - ([repo (⭐2)](https://github.com/plaey/chatbot))

### Contents / Community

*   [Freenode](https://webchat.freenode.net/?channels=choo)

### Contents / Resources

*   :movie\_camera: [TCBY community live hangout](https://www.youtube.com/watch?v=a97Mw2z1SAI)
*   :book: [A better frontend experience](https://medium.com/@yoshuawuyts/a-better-frontend-experience-7b0498c85658)
*   :book: [Composition in CycleJS, choo, React and Angular2](http://blog.krawaller.se/posts/composition-in-cyclejs-choo-react-and-angular2)
*   :book: [Stupidly smart components in choo](http://blog.krawaller.se/posts/stupidly-smart-components-in-choo)

### Contents / Projects using choo

*   [boxcar (⭐10)](https://github.com/toddself/boxcar) - A choo-based grid/spreadsheet editor.
*   [choo-sortable (⭐2)](https://github.com/willkessler/choo-sortable) - Building sortable code with choo.
*   [hacker-choo (⭐10)](https://github.com/mw222rs/hacker-choo) - Hacker Typer clone written in choo.
*   [footprint-rechoo (⭐4)](https://github.com/npeihl/footprint-rechoo) - A choo rewrite of [footprint-review (⭐6)](http://github.com/sjcgis/footprint-review).
*   [minidocs (⭐136)](https://github.com/freeman-lab/minidocs) – A documentation site generator built with choo.
*   [dataface (⭐43)](https://github.com/timwis/dataface) - Desktop application to manage databases.
*   [BlankUp (⭐38)](https://github.com/HoverBaum/BlankUp-Electron) - Multiplatform markdown editor.

---

- Prev: [Aug 10, 2016](/content/2016/08/10/README.md)
- Next: [Aug 08, 2016](/content/2016/08/08/README.md)