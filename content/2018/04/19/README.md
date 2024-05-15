# Awesome List Updates on Apr 19, 2018

9 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Recursion Schemes](/content/passy/awesome-recursion-schemes/README.md)

### Articles

*   [Recursion Schemes, Part V: Hello, Hylomorphisms](http://blog.sumtypeofway.com/recursion-schemes-part-v/)

## [2. Awesome Aws](/content/donnemartin/awesome-aws/README.md)

### Open Source Repos / Miscellaneous Repos

*   [devops-israel/aws-inventory :fire::fire: (⭐386)](https://github.com/devops-israel/aws-inventory) - Display all your AWS resources on a single web page.

## [3. Awesome Ocaml](/content/ocaml-community/awesome-ocaml/README.md)

### Community

*   [OCaml Discord Chat](https://discord.gg/ZBgYuvR)

## [4. Julia.jl](/content/svaksha/Julia.jl/README.md)

### §2.1. AGPLv3 and ODbL

*   The **data** (aggregated and curated decibans of knowledge resources for Julia language) in this repository (`Julia.jl`) is released under the [Open Database License](https://opendatacommons.org/licenses/odbl/1-0/) (ODbL-v1.0). The Open Database License (ODbL) grants anyone the freedom to share, create and adapt the data or database with proper **credit attribution** as specified in the license and **offer any new work under the same terms**, and **release a public copy if using the new work for commercial purposes**.
*   The **software** used in `Julia.jl` is released under the [AGPLv3 License](http://www.gnu.org/licenses/agpl-3.0.html), and above, as detailed in the [LICENSE-AGPLv3.md (⭐1.3k)](https://github.com/svaksha/Julia.jl/blob/master/LICENSE-AGPLv3.md) file.
*   ALL copies and forks of this work must retain the Copyright, respective Licence files for program code (AGPLv3) and data (ODbL) along with this permission notice in all copies or substantial portions of the new work.

## [5. Awesome Network Analysis](/content/briatte/awesome-network-analysis/README.md)

### Books / Dissemination

*   *[Network Literacy: Essential Concepts and Core ideas](https://sites.google.com/a/binghamton.edu/netscied/teaching-learning/network-concepts)*, by the NetSciEd team (c. 2016) - Available in several languages ([paper](https://academic.oup.com/comnet/article-abstract/4/3/457/1745356)).

### Books / Method-specific

*   *[Network Analysis in Archaeology](https://global.oup.com/academic/product/network-analysis-in-archaeology-9780199697090)*, edited by Carl Knappett (2013; [review in French](https://doi.org/10.4000/nda.2383)).

### Journals / Topic-specific

*   *[NETCOM. Networks and Communication Studies](https://journals.openedition.org/netcom/)*, in English and in French (Revues.org).

### Selected Papers / Social, Economic and Political Networks

*   [Aux sources des grands réseaux d’interactions. Retour sur quelques propriétés déterminantes des réseaux sociaux issus de corpus documentaires](https://www.cairn.info/revue-reseaux1-2008-6-page-21.htm), by Pascal Cristofoli, in French - Reviews the current state of relational sociology and network analysis in light of the large-scale and online data (*Réseaux*, 2008).

### Varia / Network Science

*   [Editing a Normal Science Journal in Social Science](https://journals.openedition.org/bms/595) - Reflections on the *Social Networks* journal by its founding editor.

### Varia / Two-Mode Networks

*   [Fitting Large Signed Two-mode Blockmodels: Problems and Prospects](http://patrickdoreian.com/wp-content/uploads/2017/12/large-signed-2mode-networks_UNGA.pdf).
*   [Partitioning Signed Two-Mode Networks](http://patrickdoreian.com/wp-content/uploads/2017/12/partitioning-signed-social-networks.pdf).

## [6. Awesome R](/content/qinwf/awesome-R/README.md)

### Reference Cards / Book/monograph Lists and Reviews

*   [RStudio Cheat Sheets](https://www.rstudio.com/resources/cheatsheets/)

## [7. Awesome Selfhosted](/content/awesome-selfhosted/awesome-selfhosted/README.md)

### Software / Conference Management

*   [pretalx](https://pretalx.org) - Web-based event management, including running a Call for Papers, reviewing submissions, and scheduling talks. Exports and imports for various related tools. ([Source Code (⭐662)](https://github.com/pretalx/pretalx)) `Apache-2.0` `Python`

## [8. Awesome Groovy](/content/kdabir/awesome-groovy/README.md)

### Testing

*   [Dru](https://agorapulse.github.io/dru/) - Data Reconstruction Utility loads data from external sources JSON, YML for easy testing GORM, DynamoDB or just plain POJOs.
*   [Gru](https://agorapulse.github.io/gru/) - Groovy HTTP Testing Framework for running integration and semi-ingetration tests for any HTTP backend with native unit test support for Grails and Spring MVC.

### DSLs

*   [spreadsheet-builder](http://spreadsheet.dsl.builders/) - Spreadsheet builder provides convenient way how to create MS Excel OfficeOpenXML Documents (XSLX)

## [9. Awesome Git Addons](/content/stevemao/awesome-git-addons/README.md)

### [git-issue](https://github.com/dspinellis/git-issue)

### Initialize issue repository

    $ git issue init
    Initialized empty Issues repository in /home/dds/src/gi/.issues
    $ git issue new -s 'New issue entered from the command line'
    Added issue e6a95c9
### Create a new issue (opens editor window)

    $ git issue new
    Added issue 7dfa5b7
### List open issues

    $ git issue list
    7dfa5b7 An issue entered from the editor
    e6a95c9 New issue entered from the command line
### Add an issue comment (opens editor window)

    $ git issue comment e6a95c9
    Added comment 8c0d5b3
### Add tag to an issue

    $ git issue tag e6a9 urgent
    Added tag urgent
### Add two more tags

    $ git issue tag e6a9 gui crash
    Added tag gui
    Added tag crash
### Remove a tag

    $ git issue tag -r e6a9 urgent
    Removed tag urgent
### Assign issue

    $ git issue assign e6a9 joe@example.com
    Assigned to joe@example.com
### Add issue watcher

    $ git issue watcher e6a9 jane@example.com
    Added watcher jane@example.com
### List issues tagged as gui

    $ git issue list gui
    e6a95c9 New issue entered from the command line
### Push issues repository to a server

    $ git issue git remote add origin git@github.com:dspinellis/gi-example.git
    $ git issue git push -u origin master
    Counting objects: 60, done.
    Compressing objects: 100% (50/50), done.
    Writing objects: 100% (60/60), 5.35 KiB | 0 bytes/s, done.
    Total 60 (delta 8), reused 0 (delta 0)
    To git@github.com:dspinellis/gi-example.git
     * [new branch]      master -> master
    Branch master set up to track remote branch master from origin.
### Clone issues repository from server

    $ git issue clone git@github.com:dspinellis/gi-example.git my-issues
    Cloning into '.issues'...
    remote: Counting objects: 60, done.
    remote: Compressing objects: 100% (42/42), done.
    remote: Total 60 (delta 8), reused 60 (delta 8), pack-reused 0
    Receiving objects: 100% (60/60), 5.35 KiB | 0 bytes/s, done.
    Resolving deltas: 100% (8/8), done.
    Checking connectivity... done.
    Cloned git@github.com:dspinellis/gi-example.git into my-issues
### Create new issue

    $ git issue new -s 'Issue added on another host'
    Added issue abc9adc
### Push changes to server

    $ git issue push
    Counting objects: 7, done.
    Compressing objects: 100% (6/6), done.
    Writing objects: 100% (7/7), 767 bytes | 0 bytes/s, done.
    Total 7 (delta 0), reused 0 (delta 0)
    To git@github.com:dspinellis/gi-example.git
       d6be890..740f9a0  master -> master
### Show issue added on the other host

    $ git issue show 7dfa5b7
    issue 7dfa5b7f4591ecaa8323716f229b84ad40f5275b
    Author: Diomidis Spinellis <dds@aueb.gr>
    Date:   Fri, 29 Jan 2016 01:03:24 +0200
    Tags:   open

        An issue entered from the editor

        Here is a longer description.
### Show issue and comments

    $ git issue show -c e6a95c9
    issue e6a95c91b31ded8fc229a41cc4bd7d281ce6e0f1
    Author: Diomidis Spinellis <dds@aueb.gr>
    Date:   Fri, 29 Jan 2016 01:03:20 +0200
    Tags:   open urgent gui crash
    Watchers:       jane@example.com
    Assigned-to: joe@example.com

        New issue entered from the command line

    comment 8c0d5b3d77bf93b937cb11038b129f927d49e34a
    Author: Diomidis Spinellis <dds@aueb.gr>
    Date:   Fri, 29 Jan 2016 01:03:57 +0200

        First comment regarding the issue.
### Pull in remote changes (on the original host)

    $ git issue pull
    remote: Counting objects: 7, done.
    remote: Compressing objects: 100% (6/6), done.
    remote: Total 7 (delta 0), reused 7 (delta 0), pack-reused 0
    Unpacking objects: 100% (7/7), done.
    From github.com:dspinellis/gi-example
       d6be890..740f9a0  master     -> origin/master
    Updating d6be890..740f9a0
    Fast-forward
     issues/ab/c9adc61025a3cb73b0c67470b65cefc133a8d0/description | 1 +
     issues/ab/c9adc61025a3cb73b0c67470b65cefc133a8d0/tags        | 1 +
     2 files changed, 2 insertions(+)
     create mode 100644 issues/ab/c9adc61025a3cb73b0c67470b65cefc133a8d0/description
     create mode 100644 issues/ab/c9adc61025a3cb73b0c67470b65cefc133a8d0/tags
### List open issues

    $ git issue list
    7dfa5b7 An issue entered from the editor
    abc9adc Issue added on another host
    e6a95c9 New issue entered from the command line
### Sub-command auto-completion

    $ git issue [Tab]
    assign   clone    comment  git      init     log      pull     show     watcher
    attach   close    edit     help     list     new      push     tag

---

- Prev: [Apr 20, 2018](/content/2018/04/20/README.md)
- Next: [Apr 18, 2018](/content/2018/04/18/README.md)