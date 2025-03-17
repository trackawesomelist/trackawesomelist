# Awesome List Updates on Aug 25, 2015

12 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Rbooks](/content/RomanTsegelskyi/rbooks/README.md)

### Visualization

#### R Graphics Cookbook [\[Amazon\]](http://www.amazon.com/R-Graphics-Cookbook-Winston-Chang/dp/1449316956)

<img src="http://ecx.images-amazon.com/images/I/51gjgnl23VL._AA160_.jpg" width="200px"/>

This practical guide provides more than 150 recipes to help you generate high-quality graphs quickly, without having to comb through all the details of R’s graphing systems. Each recipe tackles a specific problem with a solution you can apply to your own project, and includes a discussion of how and why the recipe works.

Most of the recipes use the ggplot2 package, a powerful and flexible way to make graphs in R. If you have a basic understanding of the R language, you’re ready to get started.

Your contributions are always welcome and greately appreciated, just follow [the rules (⭐190)](https://github.com/RomanTsegelskyi/rbooks/blob/master/CONTRIBUTING.md)!

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## [2. Awesome Flexbox](/content/afonsopacifer/awesome-flexbox/README.md)

### Newsletter

*   [CSS Layout News](http://csslayout.news/)
*   [CSS Weekly](http://css-weekly.com/)

### Guides

*   [What IS Flexbox?](https://medium.com/@spaceninja/what-is-flexbox-6aed968555ef)

## [3. Tips](/content/git-tips/tips/README.md)

## Prunes references to remove branches that have been deleted in the remote.

```sh
git fetch -p
```

**Alternatives:**

```sh
git remote prune origin
```

## [4. Awesome Ruby](/content/markets/awesome-ruby/README.md)

### Mobile Development

*   [dryrun (⭐3.8k)](https://github.com/cesarferreira/dryrun) - Try any Android library on your smartphone directly from the command line.
*   [RubyMotion](http://www.rubymotion.com) - A revolutionary toolchain that lets you quickly develop and test full-fledged native iOS and OS X applications for iPhone, iPad, Mac and Android.

## [5. Awesome Jvm](/content/deephacks/awesome-jvm/README.md)

### Nix tools

*   [perf-tools (⭐8.7k)](https://github.com/brendangregg/perf-tools) - Performance analysis tools based on Linux perf\_events (aka perf) and ftrace.

## [6. Awesome Pascal](/content/Fr0sT-Brutal/awesome-pascal/README.md)

### Graphic

*   [AsciiImage (⭐35)](https://github.com/Memnarch/AsciiImage). `[Delphi]` AsciiImage-Implementation for Delphi by Alexander Benikowski based on AsciiImage by Charles Parnot. Read more on [his article](http://cocoamine.net/blog/2015/03/20/replacing-photoshop-with-nsstring).
    // *Creates scalable monochrome image from ASCII pixel map*

### Viewers

*   [HtmlViewer (⭐341)](https://github.com/BerndGabriel/HtmlViewer). `[Delphi]` `[FPC]` Delphi/Lazarus HtmlViewer/FrameViewer.
    // *Html visualiser supporting majority of tags, inline styles and CSS.*

## [7. Awesome Git Addons](/content/stevemao/awesome-git-addons/README.md)

### [git-extras](https://github.com/tj/git-extras)

### squash

    $ git squash fixed-cursor-styling "Fixed cursor styling"
    $ git squash 95b7c52
    $ git squash HEAD~3
### summary

    $ git summary

     project  : git
     repo age : 10 years
     active   : 11868 days
     commits  : 40530
     files    : 2825
     authors  :
     15401	Junio C Hamano                  38.0%
      1844	Jeff King                       4.5%
### line-summary

    $ git line-summary

     project  : gulp
     lines    : 3900
     authors  :
     1040 Contra                    26.7%
      828 Sindre Sorhus             21.2%
### effort

    $ git effort

      file                                          commits    active days

      .gitattributes............................... 3          3
      .gitignore................................... 265        226
      .mailmap..................................... 47         40
### authors

    $ git authors
    Contra <contra@maricopa.edu>
    Eric Schoffstall <contra@wearefractal.com>
    Sindre Sorhus <sindresorhus@gmail.com>
### changelog

    $ git changelog
    ## 3.9.0

    - add babel support
    - add transpiler fallback support
    - add support for some renamed transpilers (livescript, etc)
    - add JSCS
    - update dependecies (liftoff, interpret)
    - documentation tweaks

    ## 3.8.11

    - fix node 0.12/iojs problems
    - add node 0.12 and iojs to travis
    - update dependencies (liftoff, v8flags)
    - documentation tweaks
### commits-since

    $ git commits-since yesterday
    ... changes since yesterday
    TJ Holowaychuk - Fixed readme
### count

    $ git count
    total 855
### create-branch

    $ git create-branch development
    Total 3 (delta 0), reused 0 (delta 0)
    To https://github.com/tj/git-extras.git
     * [new branch]      HEAD -> development
    Branch development set up to track remote branch development from origin.
    Switched to a new branch 'development'
### delete-branch

    $ git delete-branch integration
    Deleted branch integration (was bfb8522).
    Deleted remote-tracking branch remote/integration (was bfb8522).
    To git@github.com:remote/gulp.git
     - [deleted]         integration
### delete-submodule

    $ git delete-submodule lib/foo
### delete-tag

    $ git delete-tag v0.1.1
    Deleted tag 'v0.1.1' (was 9fde751)
    To https://github.com/tj/git-extras.git
     - [deleted]         v0.1.1
### delete-merged-branches

    $ git delete-merged-branches
    Deleted feature/themes (was c029ab3).
    Deleted feature/live_preview (was a81b002).
    Deleted feature/dashboard (was 923befa).
### fresh-branch

    $ git fresh-branch docs
    Removing .DS_Store
    Removing .editorconfig
    Removing .gitignore
### guilt

    $ git guilt `git log --until="3 weeks ago" --format="%H" -n 1` HEAD
    Paul Schreiber                +++++++++++++++++++++++++++++++++++++++++++++(349)
    spacewander                   +++++++++++++++++++++++++++++++++++++++++++++(113)
    Mark Eissler                  ++++++++++++++++++++++++++
### merge-into

    $ git merge-into master
    Switched to branch 'master'
    Your branch is up-to-date with 'origin/master'.
    Updating 9fde751..e62edfa
    Fast-forward
     234 | 0
     1 file changed, 0 insertions(+), 0 deletions(-)
     create mode 100644 234
    Switched to branch 'development'
### graft

    $ git graft development
    Your branch is up-to-date with 'origin/master'.
    Merge made by the 'recursive' strategy.
     package.json | 2 +-
     1 file changed, 1 insertion(+), 1 deletion(-)
    Deleted branch development (was 64b3563).
### alias

    $ git alias last "cat-file commit HEAD"
    $ git alias
    last = cat-file commit HEAD
### ignore

    $ git ignore build "*.o" "*.log"
    ... added 'build'
    ... added '*.o'
    ... added '*.log'
### info

    $ git info

        ## Remote URLs:

        origin              git@github.com:sampleAuthor/git-extras.git (fetch)
        origin              git@github.com:sampleAuthor/git-extras.git (push)

        ## Remote Branches:

        origin/HEAD -> origin/master
        origin/myBranch

        ## Local Branches:

        myBranch
        * master

        ## Most Recent Commit:

        commit e3952df2c172c6f3eb533d8d0b1a6c77250769a7
        Author: Sample Author <sampleAuthor@gmail.com>

        Added git-info command.

        Type 'git log' for more commits, or 'git show <commit id>' for full commit details.

        ## Configuration (.git/config):

        color.diff=auto
        color.status=auto
### fork

    $ git fork LearnBoost/expect.js
### release

    $ git release 0.1.0
    ... releasing 0.1.0
    On branch development
    Your branch is up-to-date with 'origin/development'.
    nothing to commit, working directory clean
    Total 0 (delta 0), reused 0 (delta 0)
    To https://github.com/tj/git-extras.git
       9fde751..e62edfa  master -> master
    Counting objects: 1, done.
    Writing objects: 100% (1/1), 166 bytes | 0 bytes/s, done.
    Total 1 (delta 0), reused 0 (delta 0)
    To https://github.com/tj/git-extras.git
     * [new tag]         0.1.0 -> 0.1.0
    ... complete
### contrib

    $ git contrib visionmedia
    visionmedia (18):
      Export STATUS_CODES
      Replaced several Array.prototype.slice.call() calls with Array.prototype.unshift.call()
      Moved help msg to node-repl
### repl

    $ git repl

    git> ls-files
    History.md
    Makefile
### undo

    $ git undo
    Unstaged changes after reset:
    M	package.json
    M	readme.md
### gh-pages

    $ git gh-pages
### scp

    $ git scp staging HEAD
### setup

    $ git setup
    Initialized empty Git repository in /GitHub/test/gulp/.git/
    [master (root-commit) 9469797] Initial commit
     69 files changed, 3900 insertions(+)
     create mode 100644 .editorconfig
     create mode 100644 .gitignore
     create mode 100644 .jscsrc
### touch

    $ git touch index.js
### obliterate

    $ git obliterate secrets.json
    Rewrite 2357a4334051a6d1733037406ab7538255030d0b (1/981)rm 'secrets.json'
    Rewrite b5f62b2746c23150917d346bd0c50c467f01eb03 (2/981)rm 'secrets.json'
    Rewrite 3cd94f3395c2701848f6ff626a0a4f883d8a8433 (3/981)rm 'secrets.json'
### feature|refactor|bug|chore

    $ git feature dependencies
    $ git feature finish dependencies
    Already up-to-date.
    Deleted branch feature/dependencies (was f0fc4c7).
    Deleted remote-tracking branch origin/feature/dependencies (was f0fc4c7).
    To git@github.com:stevemao/gulp.git
     - [deleted]         feature/dependencies
### local-commits

    $ git local-commits
    commit 5f00a3c1bb71876ebdca059fac96b7185dea5467
    Merge: 7ad3ef9 841af4e
    Author: Blaine Bublitz <blaine@iceddev.com>
    Date:   Thu Aug 20 11:35:15 2015 -0700

        Merge pull request #1211 from JimiHFord/patch-1

        Update guidelines.md

    commit 841af4ee7aaf55b505354d0e86d7fb876d745e26
    Author: Jimi Ford <JimiHFord@users.noreply.github.com>
    Date:   Thu Aug 20 11:55:38 2015 -0400

        Update guidelines.md

        fixed typo
### archive-file

    $ git archive-file
    Building archive on branch "master"
    Saved to "gulp.v3.9.0-36-g47cb6b0.zip" ( 60K)
### missing

    $ git missing master
    < d14b8f0 only on current checked out branch
    > 97ef387 only on master
### lock

    $ git lock config/database.yml
### locked

    $ git locked
    config/database.yml
### unlock

    $ git unlock config/database.yml
### reset-file

    $ git reset-file README.md HEAD^
    Reset 'README.md' to HEAD^
### pr

    $ git pr 226
    From https://github.com/tj/git-extras
     * [new ref]       refs/pulls/226/head -> pr/226
    Switched to branch 'pr/226'
### root

    $ git root
    /GitHub/git
### delta

    $ git delta
    README.md
### merge-repo

    $ git merge-repo git@github.com:tj/git-extras.git master .
    git fetch git@github.com:tj/git-extras.git master
    warning: no common commits
    remote: Counting objects: 3507, done.
    remote: Compressing objects: 100% (5/5), done.
    remote: Total 3507 (delta 1), reused 0 (delta 0), pack-reused 3502
    Receiving objects: 100% (3507/3507), 821.12 KiB | 286.00 KiB/s, done.
    Resolving deltas: 100% (1986/1986), done.
    From github.com:tj/git-extras
     * branch            master     -> FETCH_HEAD
    Added dir 'git-merge-repo.E95m0gj'
    No local changes to save

### [gitflow (AVH Edition)](https://github.com/petervanderdoes/gitflow-avh)

### psykorebase

    $ git psykorebase master
    $ git psykorebase --continue
    $ git psykorebase master feature
### flow init

    $ git flow init

    Which branch should be used for bringing forth production releases?
       - changelog
       - master
    Branch name for production releases: [master]

    Which branch should be used for integration of the "next release"?
       - changelog
    Branch name for "next release" development: [master]
    Production and integration branches should differ.

### License

### Filter by author, range, and more

    $ git spend sum --author stevemao --author antoine@goutenoir.com --since tags/v1.0.0
    1 week 3 hours

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Steve Mao](https://github.com/stevemao) has waived all copyright and related or neighboring rights to this work.

## [8. Awesome Canvas](/content/raphamorim/awesome-canvas/README.md)

### Resources / Twitter

*   [@end3r](https://twitter.com/end3r) - HTML5 game developer and EnclaveGames indie studio founder

## [9. Engineering Blogs](/content/kilimchoi/engineering-blogs/README.md)

### Individuals/Group Contributors / H individuals

*   Huon Wilson <http://huonw.github.io/>

## [10. Awesome Cpp](/content/fffaraz/awesome-cpp/README.md)

### Frameworks

*   [Apache C++ Standard Library](http://stdcxx.apache.org/) - STDCXX, A collection of algorithms, containers, iterators, and other fundamental components. \[retired] \[Apache2]

## [11. Awesome Elixir](/content/h4cc/awesome-elixir/README.md)

### Framework Components

*   [raygun (⭐19)](https://github.com/cobenian/raygun) - Capture bugs and send them to Raygun.

## [12. Awesome Emails](/content/jonathandion/awesome-emails/README.md)

### Templates / Misc

*   [Campaign (⭐640)](https://github.com/bevacqua/campaign) - Compose responsive email templates easily, fill them with models, and send them out.

### Resources / Misc

*   [Mailchimp](http://mailchimp.com/resources/) - Super awesome resources from Mailchimp.

---

- Prev: [Aug 26, 2015](/content/2015/08/26/README.md)
- Next: [Aug 24, 2015](/content/2015/08/24/README.md)