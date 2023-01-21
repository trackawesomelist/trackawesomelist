# Awesome List Updates on Apr 21, 2015

6 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Git Cheat Sheet](/content/arslanbilal/git-cheat-sheet/README.md)

### Configuration Files

## Configuration Files

##### Repository specific configuration file \[--local]:

    <repo>/.git/config

##### User-specific configuration file \[--global]:

    ~/.gitconfig

##### System-wide configuration file \[--system]:

    /etc/gitconfig

<hr>

### Create

## Create

##### Clone an existing repository:

There are two ways:

Via SSH

    $ git clone ssh://user@domain.com/repo.git

Via HTTP

    $ git clone http://domain.com/user/repo.git

##### Create a new local repository in the current directory:

    $ git init

##### Create a new local repository in a specific directory:

    $ git init <directory>

<hr>

### Local Changes

## Local Changes

##### Changes in working directory:

    $ git status

##### Changes to tracked files:

    $ git diff

##### See changes/difference of a specific file:

    $ git diff <file>

##### Add all current changes to the next commit:

    $ git add .

##### Add some changes in \<file> to the next commit:

    $ git add -p <file>

##### Add only the mentioned files to the next commit:

    $ git add <filename1> <filename2>

##### Commit all local changes in tracked files:

    $ git commit -a

##### Commit previously staged changes:

    $ git commit

##### Commit with message:

    $ git commit -m 'message here'

##### Commit skipping the staging area and adding message:

    $ git commit -am 'message here'

##### Commit to some previous date:

    $ git commit --date="`date --date='n day ago'`" -am "<Commit Message Here>"

##### Change last commit:<br>

<em><sub>Don't amend published commits!</sub></em>

    $ git commit -a --amend

##### Amend with last commit but use the previous commit log message

<em><sub>Don't amend published commits!</sub></em>

```shell
$ git commit --amend --no-edit
```

##### Change committer date of last commit:

    GIT_COMMITTER_DATE="date" git commit --amend

##### Change Author date of last commit:

```shell
$ git commit --amend --date="date"
```

##### Move uncommitted changes from current branch to some other branch:<br>

    $ git stash
    $ git checkout branch2
    $ git stash pop

##### Restore stashed changes back to current branch:

```shell
$ git stash apply
```

#### Restore particular stash back to current branch:

*   *{stash\_number}* can be obtained from `git stash list`

```shell
$ git stash apply stash@{stash_number}
```

##### Remove the last set of stashed changes:

    $ git stash drop

<hr>

### Search

## Search

##### A text search on all files in the directory:

    $ git grep "Hello"

##### In any version of a text search:

    $ git grep "Hello" v2.5

##### Show commits that introduced a specific keyword

    $ git log -S 'keyword'

##### Show commits that introduced a specific keyword (using a regular expression)

    $ git log -S 'keyword' --pickaxe-regex

<hr>

### Commit History

## Commit History

##### Show all commits, starting with newest (it'll show the hash, author information, date of commit and title of the commit):

    $ git log

##### Show all the commits(it'll show just the commit hash and the commit message):

    $ git log --oneline

##### Show all commits of a specific user:

    $ git log --author="username"

##### Show changes over time for a specific file:

    $ git log -p <file>

##### Display commits that are present only in remote/branch in right side

    $ git log --oneline <origin/master>..<remote/master> --left-right

##### Who changed, what and when in \<file>:

    $ git blame <file>

##### Show Reference log:

    $ git reflog show

##### Delete Reference log:

    $ git reflog delete

<hr>

### Branches & Tags

## Branches & Tags

##### List all local branches:

    $ git branch

#### List local/remote branches

    $ git branch -a

##### List all remote branches:

    $ git branch -r

##### Switch HEAD branch:

    $ git checkout <branch>

##### Checkout single file from different branch

    $ git checkout <branch> -- <filename>

##### Create and switch new branch:

    $ git checkout -b <branch>

##### Switch to the previous branch, without saying the name explicitly:

    $ git checkout -

##### Create a new branch from an exiting branch and switch to new branch:

    $ git checkout -b <new_branch> <existing_branch>

#### Checkout and create a new branch from existing commit

    $ git checkout <commit-hash> -b <new_branch_name>

##### Create a new branch based on your current HEAD:

    $ git branch <new-branch>

##### Create a new tracking branch based on a remote branch:

    $ git branch --track <new-branch> <remote-branch>

##### Delete a local branch:

    $ git branch -d <branch>

##### Rename current branch to new branch name

```shell
$ git branch -m <new_branch_name>
```

##### Force delete a local branch:

<em><sub>You will lose unmerged changes!</sub></em>

    $ git branch -D <branch>

##### Apply specific commit from another branch:

    git cherry-pick <commit hash>

##### Mark `HEAD` with a tag:

    $ git tag <tag-name>

##### Mark `HEAD` with a tag and open the editor to include a message:

    $ git tag -a <tag-name>

##### Mark `HEAD` with a tag that includes a message:

    $ git tag <tag-name> -am 'message here'

##### List all tags:

    $ git tag

##### List all tags with their messages (tag message or commit message if tag has no message):

    $ git tag -n

<hr>

### Merge & Rebase

## Merge & Rebase

##### Merge branch into your current HEAD:

    $ git merge <branch>

#### List merged branches

    $ git branch --merged

##### Rebase your current HEAD onto \<branch>:<br>

<em><sub>Don't rebase published commit!</sub></em>

    $ git rebase <branch>

##### Abort a rebase:

    $ git rebase --abort

##### Continue a rebase after resolving conflicts:

    $ git rebase --continue

##### Use your editor to manually solve conflicts and (after resolving) mark file as resolved:

    $ git add <resolved-file>

<!---->

    $ git rm <resolved-file>

##### Squashing commits:

    $ git rebase -i <commit-just-before-first>

Now replace this,

    pick <commit_id>
    pick <commit_id2>
    pick <commit_id3>

to this,

    pick <commit_id>
    squash <commit_id2>
    squash <commit_id3>

<hr>

### Undo

## Undo

##### Discard all local changes in your working directory:

    $ git reset --hard HEAD

##### Get all the files out of the staging area(i.e. undo the last `git add`):

    $ git reset HEAD

##### Discard local changes in a specific file:

    $ git checkout HEAD <file>

##### Revert a commit (by producing a new commit with contrary changes):

    $ git revert <commit>

##### Reset your HEAD pointer to a previous commit and discard all changes since then:

    $ git reset --hard <commit>

##### Reset your HEAD pointer to a remote branch current state.

    $ git reset --hard <remote/branch> e.g., upstream/master, origin/my-feature

##### Reset your HEAD pointer to a previous commit and preserve all changes as unstaged changes:

    $ git reset <commit>

##### Reset your HEAD pointer to a previous commit and preserve uncommitted local changes:

    $ git reset --keep <commit>

##### Remove files that were accidentally committed before they were added to .gitignore

    $ git rm -r --cached .
    $ git add .
    $ git commit -m "remove xyz file"

<hr>

## [2. Awesome Answers](/content/cyberglot/awesome-answers/README.md)

### Functional Programming

*   [Why do some people not like OOP and prefer functional programming?](http://qr.ae/L5HJB)

### Miscellaneous / Ruby

*   [How does a visually impaired computer programmer do programming?](http://qr.ae/L5FfY)

## [3. Awesome Elixir](/content/h4cc/awesome-elixir/README.md)

### Images

*   [chunky\_svg (⭐29)](https://github.com/mmmries/chunky_svg) -  A library for drawing things with SVG.

## [4. Awesome Json](/content/burningtree/awesome-json/README.md)

### Command-line tools

*   [jsawk (⭐1.4k)](https://github.com/micha/jsawk) - Like awk, but for JSON.

### JSON Schema Tools

*   [DLL.js (⭐67)](https://github.com/moll/js-ddl) - Gets you a JSON Schema from PostgreSQL or SQLite3.

## [5. Awesome Polymer](/content/Granze/awesome-polymer/README.md)

### Boilerplates

*   [Seed element (⭐280)](https://github.com/polymerlabs/seed-element)

## [6. Awesome Machine Learning](/content/josephmisiti/awesome-machine-learning/README.md)

### General-Purpose Machine Learning / Data Analysis / Data Visualization

*   [MAChineLearning (⭐38)](https://github.com/gianlucabertani/MAChineLearning) - An Objective-C multilayer perceptron library, with full support for training through backpropagation. Implemented using vDSP and vecLib, it's 20 times faster than its Java equivalent. Includes sample code for use from Swift.

---

- Prev: [Apr 22, 2015](/content/2015/04/22/README.md)
- Next: [Apr 20, 2015](/content/2015/04/20/README.md)