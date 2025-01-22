# Awesome List Updates on Oct 02, 2023

5 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Git Addons](/content/stevemao/awesome-git-addons/README.md)

### [Git Town](https://github.com/git-town/git-town)

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
### git hack

    $ git hack my-branch
    [main] git fetch --prune --tags

    [main] git rebase origin/main

    [main] git branch my-branch main

    [main] git checkout my-branch
### git sync

    $ git sync
    [my-branch] git fetch --prune --tags

    [my-branch] git checkout main

    [main] git rebase origin/main

    [main] git checkout my-branch

    [my-branch] git merge --no-edit main

    [my-branch] git push -u origin my-branch
     * [new branch]      my-branch -> my-branch
    Branch 'my-branch' set up to track remote branch 'my-branch' from 'origin'.
### git new-pull-request

    $ git new-pull-request
    [my-branch] git fetch --prune --tags

    [my-branch] git checkout main

    [main] git rebase origin/main

    [main] git checkout my-branch

    [my-branch] git merge --no-edit origin/my-branch

    [my-branch] git merge --no-edit main

    open <url to create pull request for current branch>

### [git-secret](https://github.com/sobolevn/git-secret)

### git ship

    [my-branch] git fetch --prune --tags

    [my-branch] git checkout main

    [main] git rebase origin/main

    [main] git checkout my-branch

    [my-branch] git merge --no-edit origin/my-branch

    [my-branch] git merge --no-edit main

    [my-branch] git checkout main

    [main] git merge --squash my-branch

    [main] git commit
     1 file changed, 2 insertions(+)

    [main] git push

    [main] git push origin :my-branch
     - [deleted]         my-branch

    [main] git branch -D my-branch
    Deleted branch my-branch (was 55cb0f7).

<!---->

    $ git blame-someone-else 'Steve Mao <maochenyan@gmail.com>' 2efb4e3a061a2e8aaa58033e9c13c3e0e5fcde4b
    Steve Mao  is now the author of 2efb4e3. You're officially an asshole.

<!---->

    $ git dsf

![diff-highlight vs diff-so-fancy](https://user-images.githubusercontent.com/3429760/32387617-44c873da-c082-11e7-829c-6160b853adcb.png)

![](http://i.imgur.com/PpM0i3v.png)

### [git-branchcut](https://github.com/dlsrb6342/git-branchcut)

### set the current git repository user to the home profile

    $ git profile use work

Currently there will be no output in case of success

TBD - PR Welcome!

TBD - PR Welcome!

Interactive UI and fuzzy-search for Git branches.

![git-jump interface demo](https://raw.githubusercontent.com/mykolaharmash/git-jump/main/img/demo.gif)

    git project open shoppinglist

<!---->

    git project add shoppinglist milk

<!---->

    $ git project board

     Project: shoppinglist
    +-----------+------+
    |   OPEN    | DONE |
    +-----------+------+
    | something | love |
    +-----------+------+
    | coffee    |      |
    +-----------+      +
    | sugar     |      |
    +-----------+      +
    | milk      |      |
    +-----------+------+

<!---->

    $ git project status

    Project: shoppinglist
      0|  ⭐  something
      1|  ⭐  coffee
      2|  ⭐  sugar
      3|  ⭐  milk
      4|  ✅  love

## [2. Web Development Resources](/content/markodenic/web-development-resources/README.md)

### Remote Jobs:

- Website: <https://echojobs.io>


- Website: <https://AiJobsTracker.com/remote>



### Icons:

- Website: <https://free-icons.github.io/free-icons>



### Youtube Channels:

- Website: [Corey Schafer](https://www.youtube.com/@coreyms)



### CSS Generators:

- Website: [Code Magic](https://code-magic.vercel.app/)

  Description: A free tool to make CSS easier by generating Tailwind and CSS code for effects, gradients and inputs



### Vue UI libraries:

- Website: [Quasar framework](https://quasar.dev/)

  Description: Quasar is an MIT licensed open-source Vue.js based framework. It enables web developers to create responsive++ websites/apps in various formats: SPAs, SSR (+ optional PWA client takeover), PWAs, BEX, Mobile Apps (Android, iOS, etc.), and Multi-platform Desktop Apps (using Electron). Quasar's motto is "write code once, deploy it as a website, Mobile App, and/or Electron App." It provides a state-of-the-art CLI and efficient Quasar web components, eliminating the need for additional heavy libraries like Hammer.js, Moment.js, or Bootstrap.



## [3. Awesome Music](/content/ciconia/awesome-music/README.md)

### Music Programming

*   [Strudel](https://strudel.tidalcycles.org/) - an experiment in making a language built on javascript for live coding patterns using web technologies.

## [4. Awesome Zsh Plugins](/content/unixorn/awesome-zsh-plugins/README.md)

### Plugins / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [sussysh (⭐0)](https://github.com/sussynuggetz/sussysh-zsh) - Based on xiong-chiamiov.

### Themes / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [minima (⭐3)](https://github.com/Brolly0204/zsh-minima) - Includes `git`, `node`, `golang`, `yarn`, `php`, `docker` and `python` status decorations.
*   [x](https://github.com/tharindu899/x-theme) - Includes customizable banners

## [5. Awesome Datascience](/content/academic/awesome-datascience/README.md)

### Algorithms / Three kinds of Machine Learning Systems

*   Based on training with human supervision
*   Based on learning incrementally on fly
*   Based on data points comparison and pattern detection

### Comparison / Supervised Learning

*   [Regression](https://en.wikipedia.org/wiki/Regression)
*   [Softmax Regression](https://d2l.ai/chapter_linear-classification/softmax-regression.html)

### Books / Visualization Tools

*   [Machine Learning For Absolute Beginners](https://www.amazon.in/Machine-Learning-Absolute-Beginners-Introduction-ebook/dp/B07335JNW1)

### Bloggers / Book Deals (Affiliated)

*   [Akhil Soni](https://medium.com/@akhil0435) - ML, DL and Data Science
*   [Akhil Soni](https://akhilworld.hashnode.dev/) - ML, DL and Data Science

---

- Prev: [Oct 03, 2023](/content/2023/10/03/README.md)
- Next: [Oct 01, 2023](/content/2023/10/01/README.md)