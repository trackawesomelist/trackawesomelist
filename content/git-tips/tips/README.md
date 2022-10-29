# Track Tips Updates Daily

Most commonly used git tips and tricks.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/git-tips/tips/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 git-tips/tips](https://github.com/git-tips/tips) · ⭐ 20K · 🏷️ Development Environment

[ Daily / [Weekly](/content/git-tips/tips/week/README.md) / [Overview](/content/git-tips/tips/readme/README.md) ]

## [May 04, 2021](/content/2021/05/04/README.md)

## Create local tag

```sh
git tag <tag-name>
```
## Show the contents of any stash in patch form

```sh
git stash show -p <stash@{n}>
```
## Push the current branch to the same name on the remote repository

```sh
git push origin HEAD
```

## [Mar 18, 2021](/content/2021/03/18/README.md)

## Delete local branches that has been squash and merged in the remote.

```sh
git branch -vv | grep ': gone]' | awk '{print <!-- @doxie.inject start -->}' | xargs git branch -D
```

## [Jul 16, 2020](/content/2020/07/16/README.md)

## Create and switch new branch

```sh
git checkout -b <branch-name>
```

**Alternatives:**

```sh
git branch <branch-name> && git checkout <branch-name>
```

```sh
git switch -c <branch-name>
```

## [Apr 18, 2019](/content/2019/04/18/README.md)

## Show changes over time for specific file

```sh
git log -p <file_name>
```
## Reset: preserve uncommitted local changes

```sh
git reset --keep <commit>
```
## Delete remote branch

```sh
git push origin --delete <remote_branchname>
```

**Alternatives:**

```sh
git push origin :<remote_branchname>
```

```sh
git branch -dr <remote/branch>
```
## List all currently configured remotes

```sh
git remote -v
```
## Update a submodule to the latest commit

```sh
cd <path-to-submodule>
git pull origin <branch>
cd <root-of-your-main-project>
git add <path-to-submodule>
git commit -m "submodule updated"
```

## [Oct 05, 2018](/content/2018/10/05/README.md)

## Visualize the tree including commits that are only referenced from reflogs

```sh
git log --graph --decorate --oneline $(git rev-list --walk-reflogs --all)
```

## [Jul 25, 2018](/content/2018/07/25/README.md)

## Use SSH instead of HTTPs for remotes

```sh
git config --global url.'git@github.com:'.insteadOf 'https://github.com/'
```

## [Mar 21, 2018](/content/2018/03/21/README.md)

## Change a branch base

```sh
git rebase --onto <new_base> <old_base>
```

## [Mar 08, 2018](/content/2018/03/08/README.md)

## Visualize the version tree.

```sh
git log --pretty=oneline --graph --decorate --all
```

**Alternatives:**

```sh
gitk --all
```

```sh
git log --graph --pretty=format:'%C(auto) %h | %s | %an | %ar%d'
```

## [Oct 30, 2017](/content/2017/10/30/README.md)

## Remove sensitive data from history, after a push

```sh
git filter-branch --force --index-filter 'git rm --cached --ignore-unmatch <path-to-your-file>' --prune-empty --tag-name-filter cat -- --all && git push origin --force --all
```

## [Aug 08, 2017](/content/2017/08/08/README.md)

## Push a new local branch to remote repository and track

```sh
git push -u origin <branch_name>
```

## [Apr 06, 2017](/content/2017/04/06/README.md)

## Checkout a commit prior to a day ago

```sh
git checkout master@{yesterday}
```

## [Mar 23, 2017](/content/2017/03/23/README.md)

## Search change by content

```sh
git log -S'<a term in the source>'
```

## [Feb 24, 2017](/content/2017/02/24/README.md)

## Saving current state of unstaged changes to tracked files

```sh
git stash -k
```

**Alternatives:**

```sh
git stash --keep-index
```

```sh
git stash push --keep-index
```
## Saving current state of all files (ignored, untracked, and tracked)

```sh
git stash -a
```

**Alternatives:**

```sh
git stash --all
```

```sh
git stash push --all
```

## [Feb 23, 2017](/content/2017/02/23/README.md)

## Show git status short

```sh
git status --short --branch
```

## [Feb 22, 2017](/content/2017/02/22/README.md)

## List all git aliases

```sh
git config -l | grep alias | sed 's/^alias\.//g'
```

**Alternatives:**

```sh
git config -l | grep alias | cut -d '.' -f 2
```

## [Feb 21, 2017](/content/2017/02/21/README.md)

## Saving current state with message

```sh
git stash push -m <message>
```

**Alternatives:**

```sh
git stash push --message <message>
```
## List n last commits

```sh
git log -<n>
```

**Alternatives:**

```sh
git log -n <n>
```

## [Feb 16, 2017](/content/2017/02/16/README.md)

## Quickly switch to the previous branch

```sh
git checkout -
```

**Alternatives:**

```sh
git checkout @{-1}
```

## [Jan 30, 2017](/content/2017/01/30/README.md)

## Backup untracked files.

```sh
git ls-files --others -i --exclude-standard | xargs zip untracked.zip
```

## [Jan 27, 2017](/content/2017/01/27/README.md)

## Generates a summary of pending changes

```sh
git request-pull v1.0 https://git.ko.xz/project master:for-linus
```
## List references in a remote repository

```sh
git ls-remote git://git.kernel.org/pub/scm/git/git.git
```

## [Jan 16, 2017](/content/2017/01/16/README.md)

## logs between date range

```sh
git log --since='FEB 1 2017' --until='FEB 14 2017'
```
## Exclude author from logs

```sh
git log --perl-regexp --author='^((?!excluded-author-regex).*)

```

## [Jan 08, 2017](/content/2017/01/08/README.md)

## Get the repo name.

```sh
git rev-parse --show-toplevel
```

## [Dec 25, 2016](/content/2016/12/25/README.md)

## Preformatted patch file.

```sh
git format-patch -M upstream..topic
```

## [Dec 12, 2016](/content/2016/12/12/README.md)

## Show a Git logical variable.

```sh
git var -l | <variable>
```

## [Oct 31, 2016](/content/2016/10/31/README.md)

## Edit \[local/global] git config

```sh
git config [--global] --edit
```
## blame on certain range

```sh
git blame -L <start>,<end>
```

## [Oct 24, 2016](/content/2016/10/24/README.md)

## Add everything, but whitespace changes

```sh
git diff --ignore-all-space | git apply --cached
```

## [Oct 11, 2016](/content/2016/10/11/README.md)

## List unpushed git commits

```sh
git log --branches --not --remotes
```

**Alternatives:**

```sh
git log @{u}..
```

```sh
git cherry -v
```

## [Oct 05, 2016](/content/2016/10/05/README.md)

## Always rebase instead of merge on pull.

```sh
git config --global pull.rebase true
```

**Alternatives:**

```sh
#git < 1.7.9
git config --global branch.autosetuprebase always
```

## [Oct 03, 2016](/content/2016/10/03/README.md)

## Specific fetch reference

```sh
git fetch origin master:refs/remotes/origin/mymaster
```

## [Sep 28, 2016](/content/2016/09/28/README.md)

## Apply commit from another repository

```sh
git --git-dir=<source-dir>/.git format-patch -k -1 --stdout <SHA1> | git am -3 -k
```
## Find common ancestor of two branches

```sh
git merge-base <branch-name> <other-branch-name>
```

## [Sep 24, 2016](/content/2016/09/24/README.md)

## Add object notes

```sh
git notes add -m 'Note on the previous commit....'
```
## Show all the git-notes

```sh
git log --show-notes='*'
```

## [Aug 26, 2016](/content/2016/08/26/README.md)

## Alias: git undo

```sh
git config --global alias.undo '!f() { git reset --hard $(git rev-parse --abbrev-ref HEAD)@{${1-1}}; }; f'
```

## [Aug 15, 2016](/content/2016/08/15/README.md)

## Revert: Reverting an entire merge

```sh
git revert -m 1 <commit-ish>
```

## [Aug 14, 2016](/content/2016/08/14/README.md)

## Number of commits in a branch

```sh
git rev-list --count <branch-name>
```

## [Aug 12, 2016](/content/2016/08/12/README.md)

## Show how many lines does an author contribute

```sh
git log --author='_Your_Name_Here_' --pretty=tformat: --numstat | gawk '{ add += <!-- @doxie.inject start -->; subs += <!-- @doxie.inject end -->; loc += <!-- @doxie.inject start --> - <!-- @doxie.inject end --> } END { printf "added lines: %s removed lines: %s total lines: %s
", add, subs, loc }' -
```

**Alternatives:**

```sh
git log --author='_Your_Name_Here_' --pretty=tformat: --numstat | awk '{ add += <!-- @doxie.inject start -->; subs += <!-- @doxie.inject end -->; loc += <!-- @doxie.inject start --> - <!-- @doxie.inject end --> } END { printf "added lines: %s, removed lines: %s, total lines: %s
", add, subs, loc }' - # on Mac OSX
```

## [Aug 10, 2016](/content/2016/08/10/README.md)

## Forced push but still ensure you don't overwrite other's work

```sh
git push --force-with-lease <remote-name> <branch-name>
```

## [Jul 16, 2016](/content/2016/07/16/README.md)

## Group commits by authors and title

```sh
git shortlog
```

## [Jul 07, 2016](/content/2016/07/07/README.md)

## Show changes using common diff tools.

```sh
git difftool [-t <tool>] <commit1> <commit2> <path>
```

## [Jul 03, 2016](/content/2016/07/03/README.md)

## Show the author, time and last revision made to each line of a given file

```sh
git blame <file-name>
```

## [Jun 30, 2016](/content/2016/06/30/README.md)

## Retrieve the commit hash of the initial revision.

```sh
 git rev-list --reverse HEAD | head -1
```

**Alternatives:**

```sh
git rev-list --max-parents=0 HEAD
```

```sh
git log --pretty=oneline | tail -1 | cut -c 1-40
```

```sh
git log --pretty=oneline --reverse | head -1 | cut -c 1-40
```

## [Jun 25, 2016](/content/2016/06/25/README.md)

## Force push to Remote Repository

```sh
git push -f <remote-name> <branch-name>
```
## Adding Remote name

```sh
git remote add <remote-nickname> <remote-url>
```

## [Jun 23, 2016](/content/2016/06/23/README.md)

## Unstaging Staged file

```sh
git reset HEAD <file-name>
```

## [Jun 22, 2016](/content/2016/06/22/README.md)

## Interactive staging.

```sh
git add -i
```

## [Jun 19, 2016](/content/2016/06/19/README.md)

## Update all the submodules

```sh
git submodule foreach git pull
```

**Alternatives:**

```sh
git submodule update --init --recursive
```

```sh
git submodule update --remote
```
## Get first commit in a branch (from master)

```sh
git log --oneline master..<branch-name> | tail -1
```

**Alternatives:**

```sh
git log --reverse master..<branch-name> | head -6
```

## [Jun 18, 2016](/content/2016/06/18/README.md)

## Search Commit log across all branches for given text

```sh
git log --all --grep='<given-text>'
```

## [Jun 17, 2016](/content/2016/06/17/README.md)

## Delete local tag

```sh
git tag -d <tag-name>
```
## Delete remote tag

```sh
git push origin :refs/tags/<tag-name>
```
## Clone a shallow copy of a repository

```sh
git clone https://github.com/user/repo.git --depth 1
```

## [Jun 16, 2016](/content/2016/06/16/README.md)

## Add custom editors.

```sh
git config --global core.editor '$EDITOR'
```
## Show all local branches ordered by recent commits

```sh
git for-each-ref --sort=-committerdate --format='%(refname:short)' refs/heads/
```
## Find lines matching the pattern (regex or string) in tracked files

```sh
git grep --heading --line-number 'foo bar'
```

## [Jun 13, 2016](/content/2016/06/13/README.md)

## Changes staged for commit

```sh
git diff --cached
```

**Alternatives:**

```sh
git diff --staged
```
## Remove branches that have already been merged with master

```sh
git branch --merged master | grep -v '^\*' | xargs -n 1 git branch -d
```

**Alternatives:**

```sh
git branch --merged master | grep -v '^\*\|  master' | xargs -n 1 git branch -d # will not delete master if master is not checked out
```
## See commit history for just the current branch

```sh
git cherry -v master
```
## Turn off git colored terminal output

```sh
git config --global color.ui false
```
## Specific color settings

```sh
git config --global <specific command e.g branch, diff> <true, false or always>
```

## [Jun 11, 2016](/content/2016/06/11/README.md)

## Ignore file mode changes on commits

```sh
git config core.fileMode false
```

## [Jun 10, 2016](/content/2016/06/10/README.md)

## Clone a single branch

```sh
git clone -b <branch-name> --single-branch https://github.com/user/repo.git
```

## [Jun 08, 2016](/content/2016/06/08/README.md)

## Bypass pre-commit and commit-msg githooks

```sh
git commit --no-verify
```
## List commits and changes to a specific file (even through renaming)

```sh
git log --follow -p -- <file_path>
```

## [Jun 07, 2016](/content/2016/06/07/README.md)

## List all branch is WIP

```sh
git checkout master && git branch --no-merged
```
## Find guilty with binary search

```sh
git bisect start                    # Search start 
git bisect bad                      # Set point to bad commit 
git bisect good v2.6.13-rc2         # Set point to good commit|tag 
git bisect bad                      # Say current state is bad 
git bisect good                     # Say current state is good 
git bisect reset                    # Finish search 

```

## [May 18, 2016](/content/2016/05/18/README.md)

## Change previous two commits with an interactive rebase.

```sh
git rebase --interactive HEAD~2
```

## [May 11, 2016](/content/2016/05/11/README.md)

## List only the root and merge commits.

```sh
git log --first-parent
```

## [Apr 29, 2016](/content/2016/04/29/README.md)

## Extract file from another branch.

```sh
git show <branch_name>:<file_name>
```

## [Apr 10, 2016](/content/2016/04/10/README.md)

## Checkout a new branch without any history

```sh
git checkout --orphan <branch_name>
```

## [Apr 06, 2016](/content/2016/04/06/README.md)

## View the GPG signatures in the commit log

```sh
git log --show-signature
```
## Remove entry in the global config.

```sh
git config --global --unset <entry-name>
```

## [Apr 02, 2016](/content/2016/04/02/README.md)

## Instantly browse your working repository in gitweb.

```sh
git instaweb [--local] [--httpd=<httpd>] [--port=<port>] [--browser=<browser>]
```

## [Mar 29, 2016](/content/2016/03/29/README.md)

## Count unpacked number of objects and their disk consumption.

```sh
git count-objects --human-readable
```
## Prune all unreachable objects from the object database.

```sh
git gc --prune=now --aggressive
```

## [Mar 11, 2016](/content/2016/03/11/README.md)

## Open all conflicted files in an editor.

```sh
git diff --name-only | uniq | xargs $EDITOR
```

## [Mar 09, 2016](/content/2016/03/09/README.md)

## Reuse recorded resolution, record and reuse previous conflicts resolutions.

```sh
git config --global rerere.enabled 1
```

## [Mar 06, 2016](/content/2016/03/06/README.md)

## Commits in Branch1 that are not in Branch2

```sh
git log Branch1 ^Branch2
```

## [Mar 02, 2016](/content/2016/03/02/README.md)

## List ignored files.

```sh
git check-ignore *
```
## Status of ignored files.

```sh
git status --ignored
```

## [Feb 26, 2016](/content/2016/02/26/README.md)

## Skip staging area during commit.

```sh
git commit --only <file_path>
```

## [Feb 22, 2016](/content/2016/02/22/README.md)

## Marks your commit as a fix of a previous commit.

```sh
git commit --fixup <SHA-1>
```
## Squash fixup commits normal commits.

```sh
git rebase -i --autosquash
```

## [Feb 12, 2016](/content/2016/02/12/README.md)

## Grab a single file from a stash

```sh
git checkout <stash@{n}> -- <file_path>
```

**Alternatives:**

```sh
git checkout stash@{0} -- <file_path>
```
## Untrack files without deleting

```sh
git rm --cached <file_path>
```

**Alternatives:**

```sh
git rm --cached -r <directory_path>
```
## Restore file to a specific commit-hash

```sh
git checkout <commit-ish> -- <file_path>
```

## [Feb 10, 2016](/content/2016/02/10/README.md)

## Dry run. (any command that supports dry-run flag should do.)

```sh
git clean -fd --dry-run
```

## [Feb 02, 2016](/content/2016/02/02/README.md)

## Check if the change was a part of a release.

```sh
git name-rev --name-only <SHA-1>
```

## [Jan 31, 2016](/content/2016/01/31/README.md)

## Make git case sensitive.

```sh
git config --global core.ignorecase false
```
## Auto correct typos.

```sh
git config --global help.autocorrect 1
```

## [Jan 29, 2016](/content/2016/01/29/README.md)

## List all the alias and configs.

```sh
git config --list
```

## [Jan 17, 2016](/content/2016/01/17/README.md)

## Amend author.

```sh
git commit --amend --author='Author Name <email@address.com>'
```
## Reset author, after author has been changed in the global config.

```sh
git commit --amend --reset-author --no-edit
```

## [Dec 27, 2015](/content/2015/12/27/README.md)

## Restore deleted file.

```sh
git checkout <deleting_commit> -- <file_path>
```

## [Dec 25, 2015](/content/2015/12/25/README.md)

## Clean the files from `.gitignore`.

```sh
git clean -X -f
```

## [Dec 19, 2015](/content/2015/12/19/README.md)

## Don’t consider changes for tracked file.

```sh
git update-index --assume-unchanged <file_name>
```
## Undo assume-unchanged.

```sh
git update-index --no-assume-unchanged <file_name>
```

## [Dec 18, 2015](/content/2015/12/18/README.md)

## Show inline word diff.

```sh
git diff --word-diff
```

## [Nov 18, 2015](/content/2015/11/18/README.md)

## Show helpful guides that come with Git

```sh
git help -g
```

## [Nov 03, 2015](/content/2015/11/03/README.md)

## Show the most recent tag on the current branch.

```sh
git describe --tags --abbrev=0
```

## [Oct 28, 2015](/content/2015/10/28/README.md)

## Everyday Git in twenty commands or so

```sh
git help everyday
```
## Stash changes before rebasing

```sh
git rebase --autostash
```
## Fetch pull request by ID to a local branch

```sh
git fetch origin pull/<id>/head:<branch-name>
```

**Alternatives:**

```sh
git pull origin pull/<id>/head:<branch-name>
```

## [Sep 29, 2015](/content/2015/09/29/README.md)

## Ignore one file on commit (e.g. Changelog).

```sh
git update-index --assume-unchanged Changelog; git commit -a; git update-index --no-assume-unchanged Changelog
```

## [Sep 19, 2015](/content/2015/09/19/README.md)

## Get the name of current branch.

```sh
git rev-parse --abbrev-ref HEAD
```

## [Sep 13, 2015](/content/2015/09/13/README.md)

## Export a branch with history to a file.

```sh
git bundle create <file> <branch-name>
```
## Import from a bundle

```sh
git clone repo.bundle <repo-dir> -b <branch-name>
```

## [Sep 02, 2015](/content/2015/09/02/README.md)

## Deploying git tracked subfolder to gh-pages

```sh
git subtree push --prefix subfolder_name origin gh-pages
```
## Adding a project to repo using subtree

```sh
git subtree add --prefix=<directory_name>/<project_name> --squash git@github.com:<username>/<project_name>.git master
```
## Get latest changes in your repo for a linked project using subtree

```sh
git subtree pull --prefix=<directory_name>/<project_name> --squash git@github.com:<username>/<project_name>.git master
```

## [Aug 25, 2015](/content/2015/08/25/README.md)

## Prunes references to remove branches that have been deleted in the remote.

```sh
git fetch -p
```

**Alternatives:**

```sh
git remote prune origin
```

## [Aug 22, 2015](/content/2015/08/22/README.md)

## Archive the `master` branch

```sh
git archive master --format=zip --output=master.zip
```
## Modify previous commit without modifying the commit message

```sh
git add --all && git commit --amend --no-edit
```

## [Aug 21, 2015](/content/2015/08/21/README.md)

## Rebases 'feature' to 'master' and merges it in to master

```sh
git rebase master feature && git checkout master && git merge -
```

## [Aug 19, 2015](/content/2015/08/19/README.md)

## Rename a branch

```sh
git branch -m <new-branch-name>
```

**Alternatives:**

```sh
git branch -m [<old-branch-name>] <new-branch-name>
```

## [Aug 16, 2015](/content/2015/08/16/README.md)

## Show all commits in the current branch yet to be merged to master

```sh
git cherry -v master
```

**Alternatives:**

```sh
git cherry -v master <branch-to-be-merged>
```

## [Aug 11, 2015](/content/2015/08/11/README.md)

## Before deleting untracked files/directory, do a dry run to get the list of these files/directories

```sh
git clean -n
```
## Forcefully remove untracked files

```sh
git clean -f
```
## Forcefully remove untracked directory

```sh
git clean -f -d
```

## [Aug 07, 2015](/content/2015/08/07/README.md)

## Saving current state of tracked files without commiting

```sh
git stash
```

**Alternatives:**

```sh
git stash push
```
## Saving current state including untracked files

```sh
git stash -u
```

**Alternatives:**

```sh
git stash push -u
```

```sh
git stash push --include-untracked
```

## [Jul 31, 2015](/content/2015/07/31/README.md)

## Revert: Undo a commit by creating a new commit

```sh
git revert <commit-ish>
```
## Reset: Discard commits, advised for private branch

```sh
git reset <commit-ish>
```

## [Jul 30, 2015](/content/2015/07/30/README.md)

## Create new working tree from a repository (git 2.5)

```sh
git worktree add -b <branch-name> <path> <start-point>
```
## Create new working tree from HEAD state

```sh
git worktree add --detach <path> HEAD
```

## [Jul 29, 2015](/content/2015/07/29/README.md)

## Reword the previous commit message

```sh
git commit -v --amend
```
## See all commits made since forking from master

```sh
git log --no-merges --stat --reverse master..
```
## Show all ignored files

```sh
git ls-files --others -i --exclude-standard
```

## [Jul 28, 2015](/content/2015/07/28/README.md)

## List of all files changed in a commit

```sh
git diff-tree --no-commit-id --name-only -r <commit-ish>
```
## Unstaged changes since last commit

```sh
git diff
```
## Show both staged and unstaged changes

```sh
git diff HEAD
```
## Show all tracked files

```sh
git ls-files -t
```
## Show all untracked files

```sh
git ls-files --others
```

## [Jul 27, 2015](/content/2015/07/27/README.md)

## Git Aliases

```sh
git config --global alias.<handle> <command> 
git config --global alias.st status
```
## Show list of all saved stashes

```sh
git stash list
```
## Apply any stash without deleting from the stashed list

```sh
git stash apply <stash@{n}>
```
## Apply last stashed state and delete it from stashed list

```sh
git stash pop
```

**Alternatives:**

```sh
git stash apply stash@{0} && git stash drop stash@{0}
```
## Delete all stored stashes

```sh
git stash clear
```

**Alternatives:**

```sh
git stash drop <stash@{n}>
```

## [Jul 25, 2015](/content/2015/07/25/README.md)

## Pick commits across branches using cherry-pick

```sh
git checkout <branch-name> && git cherry-pick <commit-ish>
```
## Find out branches containing commit-hash

```sh
git branch -a --contains <commit-ish>
```

**Alternatives:**

```sh
git branch --contains <commit-ish>
```

## [Jul 22, 2015](/content/2015/07/22/README.md)

## What changed since two weeks?

```sh
git log --no-merges --raw --since='2 weeks ago'
```

**Alternatives:**

```sh
git whatchanged --since='2 weeks ago'
```

## [Jul 17, 2015](/content/2015/07/17/README.md)

## Get list of all remote references

```sh
git remote
```

**Alternatives:**

```sh
git remote show
```
## Get list of all local and remote branches

```sh
git branch -a
```
## Get only remote branches

```sh
git branch -r
```
## Get git bash completion

```sh
curl -L http://git.io/vfhol > ~/.git-completion.bash && echo '[ -f ~/.git-completion.bash ] && . ~/.git-completion.bash' >> ~/.bashrc
```

## [Jul 16, 2015](/content/2015/07/16/README.md)

## Undo local changes with the last content in head

```sh
git checkout -- <file_name>
```
## Stage parts of a changed file, instead of the entire file

```sh
git add -p
```

## [Jul 15, 2015](/content/2015/07/15/README.md)

## git-tips

> Collection of `git-tips`, want to add your tips? Checkout [contributing.md](https://github.com/git-tips/tips/blob/master/README.md/./contributing.md)

[English](http://git.io/git-tips) | [中文 (⭐14k)](https://github.com/521xueweihan/git-tips) | [Русский (⭐586)](https://github.com/Imangazaliev/git-tips) | [한국어 (⭐965)](https://github.com/mingrammer/git-tips) | [Tiếng Việt (⭐20)](https://github.com/hprobotic/git-tips) | [日本語 (⭐227)](https://github.com/isotai/git-tips) | [नेपाली (⭐0)](https://github.com/amarduwal/git-tips) | [Polski (⭐4)](https://github.com/mbiesiad/tips) | [فارسی (⭐0)](https://github.com/javadnikbakht/git-tips)

### **Tools:**

*   [git-tip](https://www.npmjs.com/package/git-tip) - A handy CLI to make optimum use of these tips. ([Here in Docker container (⭐11)](https://github.com/djoudi5/docker-git-tip))

P.S: All these commands are tested on `git version 2.7.4 (Apple Git-66)`.

<!-- @doxie.inject start toc -->

<!-- Don’t remove or change the comment above – that can break automatic updates. -->

<!-- Don’t remove or change the comment below – that can break automatic updates. More info at <http://npm.im/doxie.inject>. -->

<!-- @doxie.inject end toc -->

<!-- @doxie.inject start -->

<!-- Don’t remove or change the comment above – that can break automatic updates. -->
## Sync with remote, overwrite local changes

```sh
git fetch origin && git reset --hard origin/master && git clean -f -d
```
## List of all files till a commit

```sh
git ls-tree --name-only -r <commit-ish>
```
## Git reset first commit

```sh
git update-ref -d HEAD
```
## List all the conflicted files

```sh
git diff --name-only --diff-filter=U
```
## List all branches that are already merged into master

```sh
git branch --merged master
```
## List all branches and their upstreams, as well as last commit on branch

```sh
git branch -vv
```
## Track upstream branch

```sh
git branch -u origin/mybranch
```
## Delete local branch

```sh
git branch -d <local_branchname>
```
## Changing a remote's URL

```sh
git remote set-url origin <URL>
```
## Prevent auto replacing LF with CRLF

```sh
git config --global core.autocrlf false
```

<!-- Don’t remove or change the comment below – that can break automatic updates. More info at <http://npm.im/doxie.inject>. -->

<!-- @doxie.inject end -->