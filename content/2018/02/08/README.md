# Awesome List Updates on Feb 08, 2018

5 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Git Addons](/content/stevemao/awesome-git-addons/README.md)

### [git-url](https://github.com/zdharma/git-url)

### git secret reveal

    $ git secret reveal

    You need a passphrase to unlock the secret key for
    user: "Test User <my@email.com>"
    2048-bit RSA key, ID #######, created 2015-01-01 (main key ID #######)

    gpg: gpg-agent is not available in this session
    File `hideme.txt' exists. Overwrite? (y/N) y
    done. all 1 files are revealed.

> Prevents you from committing passwords and other sensitive information to a git repository.

TBD - PR Welcome!

    $ git diff --cached -U0
    diff --git a/README.md b/README.md
    index 0c700d1..7a57cef 100644
    --- a/README.md
    +++ b/README.md
    @@ -1330 +1330 @@ $ git secret hide
    -done. all 1 files are hidden.
    +done. all 3 files are hidden.
    $ git fixup 6d623f6525dd94b4aaea6f6ae2e7a59edc39bdb8
    24aa3d9c10cc02fe813dc83d1ac792cc2e7d705d [F] add screenshot of git-stats <maochenyan@gmail.com>
    6d623f6525dd94b4aaea6f6ae2e7a59edc39bdb8 [L] changed gif with text <mail@sobolevn.me>

<!---->

    $ git recent

![git-recent screenshot](https://cloud.githubusercontent.com/assets/39191/17446638/039d4cee-5aff-11e6-9e11-4294f0020513.png)

    $ git rebase -i master

![git-interactive-rebase-tool screenshot](https://raw.githubusercontent.com/MitMaro/git-interactive-rebase-tool/master/docs/assets/images/git-interactive-rebase-demo.gif)

    $ git fiddle -h
    git-fiddle

    Edit commit meta information during an *interactive* rebase.

    `git-fiddle(1)' is a lightweight wrapper around `git-rebase(1)' that
    annotates each commit with it's *author* date, the author name, as well
    as the commit message. Changes to any of these will then be applied
    using an 'exec' script during the git-rebase sequence.

    Usage:
      $SCRIPT [--[no-]-fiddle-messages] [args...]

    Options:
      --[no-]fiddle-messages Do not edit commit messages. Useful for quick edits
                             to author or date. This value can also be set using
                             `git config fiddle.messages`.
      [args...]              These arguments are passed verbatim to git-rebase.

<!---->

    # add a work profile for Henry
    $ git user add work "Dr. Henry Jekyll" henry@jekyll.com
    Added profile 'work'

    # add a personal profile for Edward
    $ git user add home "Edward Hyde" hyde@night.com
    Added profile 'home'

    # list out our saved profiles
    $ git user list
    Global Profile:
      User: Henry <hjekyll@gmail.com>

    Saved Profiles:
      home: Edward Hyde <hyde@night.com>
      work: Dr. Henry Jekyll <henry@jekyll.com>

    # set the current git repository user to the home profile
    $ git user set home
    The user for the 'project' repository has been set too 'Edward Hyde <hyde@night.com>'

    # list profiles again, notice how the current repository profile is now set
    $ git user
    Project Profile:
      Path: /path/to/git/project
      User: Edward Hyde <hyde@night.com>

    Saved Profiles:
      home: Edward Hyde <hyde@night.com>
      work: Dr. Henry Jekyll <henry@jekyll.com>

TBD - PR Welcome!

TBD - PR Welcome!

![](https://camo.githubusercontent.com/eb306717b95724c33dd0de91faa535a4818cc7d0/687474703a2f2f696d6775722e636f6d2f7a7577324c71572e676966)

    $ git recall
    # By default (without options), the command will display commits from yesterday and
    # for the current user.

    $ git recall -d 5 -a "Doge"
    # Show all Doge's commits from 5 days ago.

    $ git recall -d 5 -a "all"
    # Show commits of all contributors from 5 days ago.

    $ git recall -f
    # Fetch commits beforehand.

<!---->

    $ git standup
    2f50b39c - docs(commit messages): use commitizen to generate Conventional Commits (12 hours ago) <Steve Mao>
    9af3600e - fix tests (12 hours ago) <Steve Mao>
    7f17ba97 - docs: title case (12 hours ago) <Steve Mao>
    a6d6203c - do not scroll when search is open (12 hours ago) <Steve Mao>
    53fe681a - chore(pkg): add repo url (12 hours ago) <Steve Mao>
    5e952ac0 - subtitle should be generic (13 hours ago) <Steve Mao>
    adbc5423 - add ci/cd to readme. (13 hours ago) <Steve Mao>
    a1097116 - add versioning to readme (14 hours ago) <Steve Mao>
    6b6e7465 - add test coverage (15 hours ago) <Steve Mao>

<!---->

    $ git cz
    cz-cli@2.9.6, cz-conventional-changelog@1.2.0


    Line 1 will be cropped at 100 characters. All other lines will be wrapped after 100 characters.

    ? Select the type of change that you're committing: (Use arrow keys)
    ❯ feat:     A new feature
      fix:      A bug fix
      docs:     Documentation only changes
      style:    Changes that do not affect the meaning of the code (white-space, formatting, missing semi
    -colons, etc)
      refactor: A code change that neither fixes a bug nor adds a feature
      perf:     A code change that improves performance
      test:     Adding missing tests or correcting existing tests

TBD - PR Welcome!

    $ git fs
    Mounting readonly filesystem on ./git/fs

## [2. Awesome Healthcare](/content/kakoni/awesome-healthcare/README.md)

### Contents / PHR

*   [HealthLocker (⭐72)](https://github.com/healthlocker/healthlocker) - Elixir-based personal health record.

## [3. Awesome Sre](/content/dastergon/awesome-sre/README.md)

### Culture

*   [What is Site Reliability Engineering? (VMware)](https://blogs.vmware.com/services-education-insights/2018/02/site-reliability-engineering.html)

### Books

*   [How to Monitoring the SRE Golden Signals (E-Book)](https://www.slideshare.net/OpsStack/how-to-monitoring-the-sre-golden-signals-ebook/)

### Reliability

*   [Why you should pick strong consistency, whenever possible](https://cloudplatform.googleblog.com/2018/01/why-you-should-pick-strong-consistency-whenever-possible.html)

### Monitoring & Observability & Alerting

*   [How to Monitor the SRE Golden Signals](https://medium.com/devopslinks/how-to-monitor-the-sre-golden-signals-1391cadc7524)

### On-Call

*   [SRE@Xero: Managing Incidents Part I](https://devblog.xero.com/sre-xero-managing-incidents-part-i-7d02d650a71c)
*   [SRE@Xero: Managing Incidents Part II](https://devblog.xero.com/sre-xero-managing-incidents-part-ii-224a6e06f426)
*   [How To Establish a High Severity Incident Management Program](https://www.gremlin.com/how-to-establish-a-high-severity-incident-management-program/)

## [4. Awesome Maintainers](/content/nayafia/awesome-maintainers/README.md)

*   [@ericholscher](https://github.com/ericholscher), [Read the Docs (⭐7.3k)](https://github.com/rtfd/readthedocs.org)
    *   "Maintainer Stories: Eric Holscher" ([video](https://www.youtube.com/watch?v=us_3IGG6leM\&t=1s))
    *   "The post I never published" ([post](http://ericholscher.com/blog/2018/feb/7/the-post-i-never-published/))

## [5. Awesome Vue](/content/vuejs/awesome-vue/README.md)

### Resources / Tutorials

*   [Vue.js debugging in Chrome and VS Code (⭐5.8k)](https://github.com/Microsoft/vscode-recipes/tree/master/vuejs-cli) This recipe shows how to use the Debugger for Chrome extension with VS Code to debug Vue.js applications generated by the Vue CLI.

### Resources / Examples

*   [Skeleton Vue+TypeScript (⭐25)](https://github.com/SierraSoftworks/vue-template) - TypeScript, VueJS, ElementUI, Vue Router, Vuex, Material Icons, BrowserSync, Dockerfile

---

- Prev: [Feb 09, 2018](/content/2018/02/09/README.md)
- Next: [Feb 07, 2018](/content/2018/02/07/README.md)