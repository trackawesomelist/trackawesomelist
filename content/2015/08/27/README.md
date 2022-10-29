# Awesome List Updates on Aug 27, 2015

8 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c)



## [1. Awesome Linux Containers](/content/Friz-zy/awesome-linux-containers/README.md)

### Containers

*   [Bocker (⭐10k)](https://github.com/p8952/bocker)\
    Docker implemented in around 100 lines of bash.

## [2. Awesome Polymer](/content/Granze/awesome-polymer/README.md)

### Tutorials/Guides

*   [Flexbox layout with iron-flex-layout](https://elements.polymer-project.org/guides/flex-layout)
*   [Using Neon Animations](https://elements.polymer-project.org/guides/using-neon-animations)

## [3. Awesome Symfony Education](/content/pehapkari/awesome-symfony-education/README.md)

### EventDispatcher

*   [Decouple your application with (Domain-)Events](https://www.youtube.com/watch?v=K9jub4JPpcc) by Benjamin Eberlei \[2013]

### Decoupling

*   [The Framework as an implementation](https://www.youtube.com/watch?v=0L_9NutiJlc) by Marcello Duarte & Konstantin Kudryashov \[2013], [Github repository (⭐213)](https://github.com/MarcelloDuarte/hexagonal-symfony)

## [4. Awesome Jvm](/content/deephacks/awesome-jvm/README.md)

### Memory and concurrency

*   [Chronicle-Bytes (⭐325)](https://github.com/OpenHFT/Chronicle-Bytes) - Low level memory access wrappers.

### Nix tools

*   [hwloc](http://linux.die.net/man/7/hwloc) - Reports the structure of the processor, number of cores, hyperthreads and cache size.
*   [numactl](http://linux.die.net/man/8/numactl) - Control NUMA policy for processes or shared memory.
*   [oprofile](http://oprofile.sourceforge.net/news/) - System-wide hardware performance monitoring with easy-to-use interface at low overhead.

## [5. Awesome AutoHotkey](/content/ahkscript/awesome-AutoHotkey/README.md)

### Library Distributions / Web

*   [ASPDM (⭐58)](https://github.com/ahkscript/ASPDM) - package/stdlib distribution and management from the [ahkscript](https://github.com/ahkscript) folks. Trello [link](https://trello.com/b/XVP4M76d/package-stdlib-distribution-and-management).
*   [pAHKlight (⭐36)](https://github.com/hi5/pAHKlight) - Your Lightweight Guide to AutoHotkey libraries, classes, functions and tools.

## [6. Amas](/content/sindresorhus/amas/README.md)

### Ask these people anything!

*   [JD Ballard (⭐4)](https://github.com/Qix-/ama) - Idaho native, Chalk collaborator, sunshine burns us. Likes hypotheticals, dislikes bees.

## [7. Awesome Git Addons](/content/stevemao/awesome-git-addons/README.md)

### [hub](https://github.com/github/hub)

### flow support

    $ git flow support

<!---->

    $ git up
    Fetching origin
    4.0       fast-forwarding...
    changelog ahead of upstream
    master    fast-forwarding...
    returning to 4.0

### [git-imerge](https://github.com/mhagger/git-imerge)

### ci-status

    $ git ci-status
    success

<!---->

    $ git remote add production "user@example.com:/apps/mynewapp"
    $ git deploy setup -r "production"
    $ git deploy init
    $ git push production master

![68747470733a2f2f7261772e6769746875622e636f6d2f6b34727468696b2f6769742d63616c2f6d61737465722f73637265656e73686f74732f696d67322e706e67](https://cloud.githubusercontent.com/assets/6316590/12465623/17d828ea-c023-11e5-8077-2e9a284defd6.png)

    $ git hooks --install
    $ git hooks
    Git hooks ARE installed in this repository.

    Listing User, Project, and Global hooks:
    ---
    /Users/stevemao/.git_hooks:

    /GitHub/git-hooks/git_hooks:
    commit-msg/signed-off-by 	- Checks commit message for presence of Signed-off-by line.
    pre-commit/bsd 	- Check for the BSD license.

    /GitHub/git-hooks/.githooks:
### imerge merge

    $ git imerge merge 4.0
    Attempting automerge of 1-1...success.
    Attempting automerge of 1-6...success.
    Attempting automerge of 1-9...success.
    Attempting automerge of 1-10...success.
### imerge rebase

    $ git imerge rebase 4.0
    The following commits on the to-be-merged branch are merge commits:
        8e4931ae15971a14897cf347ac50b7d7fe125ac4
        d7c772142ce663a20210db73d9ad17cc8d59e0d6
        856df83c77b33029d2ddfb8eecd08efedeadc027

### [git-plus](https://github.com/tkrajina/git-plus)

### Issue Sha auto-completion

    $ git issue show [Tab]
    7dfa5b7 - An issue entered from the editor
    e6a95c9 - New issue entered from the command line

<!---->

    $ git lfs track "*.mp3"
    Tracking *.mp3

    $ git lfs track "*.zip"
    Tracking *.zip

    $ git lfs track
    Listing tracked paths
        *.mp3 (.gitattributes)
        *.zip (.gitattributes)

    $ git lfs untrack "*.zip"
    Untracking *.zip

    $ git lfs track
    Listing tracked paths
        *.mp3 (.gitattributes)

<!---->

    $ git now
    [master 1bd9ce8] [from now] 2015/08/27 10:39:10
     1 file changed, 1 insertion(+), 1 deletion(-)
    $ git log
    commit 1bd9ce878a76140f7db95afd9cfd4d7befbc7243
    Author: Steve Mao <maochenyan@gmail.com>
    Date:   Thu Aug 27 10:39:10 2015 +1000

        [from now] 2015/08/27 10:39:10

        diff --git a/package.json b/package.json
        index 8768569..540523a 100644
        --- a/package.json
        +++ b/package.json
        @@ -1,7 +1,7 @@
         {
           "name": "gulp",
           "description": "The streaming build system",
        -  "version": "3.9.0",
        +  "version": "3.10.0",
           "homepage": "http://gulpjs.com",
           "repository": "gulpjs/gulp",
           "author": "Fractal <contact@wearefractal.com> (http://wearefractal.com/)",
### multi

    $ git multi
    --------------------------------------------------------------------------------
    Executing git status -s
    --------------------------------------------------------------------------------
    chalk:
    	 M package.json

    gulp:
    	 D index.js
### relation

    $ git relation origin/4.0
    HEAD and origin/4.0 DIVERGED, common point is 657213a52d5e9c19b85df6a42f76341a98c08ae8

    Commits from 657213a52d5e9c19b85df6a42f76341a98c08ae8 to HEAD:
    Error retrieving log 657213a52d5e9c19b85df6a42f76341a98c08ae8..HEAD
### old-branches

    $ git old-branches -d 10
    Branch 4.0 is older than 10 days (139.86)!

### [legit](https://github.com/kennethreitz/legit)

### recent

    $ git recent
          3.64 days: master
         11.63 days: dev

<!---->

    $ git test -v
    4.0 ^origin/4.0 ^origin/master will test        2 commits
    iter commit  tree    result
    0000 57af4b0 f5ef0d8 pass (cached)
    0001 10ed389 434370f pass
### branches

    $ git branches
       4.0                        (published)
       development                (unpublished)
       everything-is-not-awesome  (published)
    *  master                     (published)
       old-master                 (published)
### sync

    $ git sync
    Pulling commits from the server.
    First, rewinding head to replay your work on top of it...
    Fast-forwarded 4.0 to origin/4.0.
    Pushing commits to the server.
### switch

    $ git switch master
    Saving local changes.
    Saved working directory and index state On developement: Legit: stashing before switching branches.
    HEAD is now at f0fc4c7 Merge branch 'development'
    Switching to master.
    Your branch is up-to-date with 'origin/master'.
    Restoring local changes.
    On branch master
    Your branch is up-to-date with 'origin/master'.
    Changes not staged for commit:
      (use "git add <file>..." to update what will be committed)
      (use "git checkout -- <file>..." to discard changes in working directory)

    	modified:   package.json

    no changes added to commit (use "git add" and/or "git commit -a")
    Dropped stash@{0} (86f5dc9066ff9f69c01c77e2f5a55643ad19f8f2)
### publish

    $ git publish
       4.0                        (published)
       changelog                  (published)
       everything-is-not-awesome  (published)
    *  master                     (unpublished)
    Branch None not found, using current branch master
    Publishing master.
    Branch master set up to track remote branch master from origin.

## [8. Rbooks](/content/RomanTsegelskyi/rbooks/README.md)

### R Development

#### Machine Learning with R [\[Amazon\]](http://www.amazon.com/Machine-Learning-R-Brett-Lantz/dp/1782162143) [\[O'Reilly\]](http://shop.oreilly.com/product/9781782162148.do)

<img src="http://ecx.images-amazon.com/images/I/518PBAYk%2BxL._SX404_BO1,204,203,200_.jpg" width="200px"/>

"Machine Learning with R" is a practical tutorial that uses hands-on examples to step through real-world application of machine learning. Without shying away from the technical details, we will explore Machine Learning with R using clear and practical examples. Well-suited to machine learning beginners or those with experience. Explore R to find the answer to all of your questions.

---

- Prev: [Aug 28, 2015](/content/2015/08/28/README.md)
- Next: [Aug 26, 2015](/content/2015/08/26/README.md)