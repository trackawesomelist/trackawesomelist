# Awesome List Updates on Mar 16 - Mar 22, 2026

19 awesome lists updated this week.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Jmeter](/content/aliesbelik/awesome-jmeter/week/README.md)

### Cloud Services / SaaS / Tutorials & Demo

*   [Azure Microsoft](https://azure.microsoft.com/en-us/products/app-testing/) - Azure Load Testing Service use Apache JMeter.

### Performance Testing / Streaming Protocols

*   [Easy and realistic Load Testing of HTTP Live Streaming (HLS) with Apache JMeter](https://ubik-ingenierie.com/blog/easy-and-realistic-load-testing-of-http-live-streaming-hls-with-apache-jmeter/)

### JMeter Performance / Utilities

*   [JMeter Performance and Tuning Tips](https://ubik-ingenierie.com/blog/jmeter_performance_tuning_tips/) - By Ubik Ingenierie.

### Trainings & Courses / Utilities

*   [Training courses on Load Testing with Apache JMeter](https://ubik-ingenierie.com/blog/jmeter-trainings-by-contributors-and-committers/) - By Ubik Ingenierie.

### Community / Blogs

*   [Ubik Load Pack Blog](https://ubik-ingenierie.com/blog/category/jmeter/) - Ubik Ingenierie blog.

## [2. Awesome Selenium](/content/christian-bromann/awesome-selenium/week/README.md)

### CSS Regression Testing / Dart

*   [Website-Diff (⭐0)](https://github.com/GeiserX/Website-Diff) - Intelligent web page comparison tool with Wayback Machine support and visual regression testing via Selenium.

## [3. Awesome Zig](/content/zigcc/awesome-zig/week/README.md)

### Language Essentials / File Format Processing

*   [mattnite/protobuf (⭐4)](https://github.com/mattnite/protobuf) - A pure-Zig Protocol Buffers library with a standalone .proto parser, build-time code generator, and transport-agnostic RPC stub generation. Supports proto2 and proto3.

## [4. Awesome Playcanvas](/content/playcanvas/awesome-playcanvas/week/README.md)

### Tutorials

*   [MDN Tutorial](https://developer.mozilla.org/en-US/docs/Games/Techniques/3D_on_the_web/Building_up_a_basic_demo_with_PlayCanvas) - Build up a basic demo with PlayCanvas.

## [5. Awesome Vue](/content/vuejs/awesome-vue/week/README.md)

### Components & Libraries / Frameworks

*   [@oneflowui/ui (⭐1)](https://github.com/qixi54/oneui) - Vue 3 + TypeScript component library for task management views, featuring Table, Kanban, Gantt timeline, Gallery, AI Chat, Dashboard charts, Rich Text Editor, MermaidChart and more. 75+ components out of the box.

### Components & Libraries / UI Components

*   [@ioi-dev/vue-table (⭐0)](https://github.com/Rawand-Hawez/ioi-vue-table) - Performance-first Vue 3 datatable with virtualization, selection, editing, and CSV export.

## [6. Tips](/content/git-tips/tips/week/README.md)

## Table of Contents
## Basic Operations

### List of all files till a commit

```sh
git ls-tree --name-only -r <commit-ish>
```

### Quickly switch to the previous branch

```sh
git checkout -
```

**Alternatives:**

```sh
git checkout @{-1}
```

### Delete remote branch

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

### Delete remote tag

```sh
git push origin :refs/tags/<tag-name>
```

### Undo local changes with the content in index(staging)

```sh
git checkout -- <file_name>
```

### Reword the previous commit message

```sh
git commit -v --amend
```

### See commit history for just the current branch

```sh
git cherry -v master
```

### Amend author.

```sh
git commit --amend --author='Author Name <email@address.com>'
```

### Stage parts of a changed file, instead of the entire file

```sh
git add -p
```

### Pick commits across branches using cherry-pick

```sh
git checkout <branch-name> && git cherry-pick <commit-ish>
```

### Grab a single file from a stash

```sh
git checkout <stash@{n}> -- <file_path>
```

**Alternatives:**

```sh
git checkout stash@{0} -- <file_path>
```

### Create new working tree from a repository (git 2.5)

```sh
git worktree add -b <branch-name> <path> <start-point>
```

### Create new working tree from HEAD state

```sh
git worktree add --detach <path> HEAD
```

### Show all commits in the current branch yet to be merged to master

```sh
git cherry -v master
```

**Alternatives:**

```sh
git cherry -v master <branch-to-be-merged>
```

### Modify previous commit without modifying the commit message

```sh
git add --all && git commit --amend --no-edit
```

### Prunes references to remove branches that have been deleted in the remote.

```sh
git fetch -p
```

**Alternatives:**

```sh
git remote prune origin
```

### Retrieve the commit hash of the initial revision.

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

### Import from a bundle

```sh
git clone repo.bundle <repo-dir> -b <branch-name>
```

### Ignore one file on commit (e.g. Changelog).

```sh
git update-index --assume-unchanged Changelog; git commit -a; git update-index --no-assume-unchanged Changelog
```

### Fetch pull request by ID to a local branch

```sh
git fetch origin pull/<id>/head:<branch-name>
```

**Alternatives:**

```sh
git pull origin pull/<id>/head:<branch-name>
```

### Restore deleted file.

```sh
git checkout <deleting_commit> -- <file_path>
```

### Restore file to a specific commit-hash

```sh
git checkout <commit-ish> -- <file_path>
```

### Marks your commit as a fix of a previous commit.

```sh
git commit --fixup <SHA-1>
```

### Skip staging area during commit.

```sh
git commit --only <file_path>
```

### Interactive staging.

```sh
git add -i
```

### Status of ignored files.

```sh
git status --ignored
```

### Checkout a new branch without any history

```sh
git checkout --orphan <branch_name>
```

### Find guilty with binary search

```sh
git bisect start                    # Search start 
git bisect bad                      # Set point to bad commit 
git bisect good v2.6.13-rc2         # Set point to good commit|tag 
git bisect bad                      # Say current state is bad 
git bisect good                     # Say current state is good 
git bisect reset                    # Finish search 

```

### Bypass pre-commit and commit-msg githooks

```sh
git commit --no-verify
```

### Clone a single branch

```sh
git clone -b <branch-name> --single-branch https://github.com/user/repo.git
```

### Create and switch new branch

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

### Show all local branches ordered by recent commits

```sh
git for-each-ref --sort=-committerdate --format='%(refname:short)' refs/heads/
```

### Clone a shallow copy of a repository

```sh
git clone https://github.com/user/repo.git --depth 1
```

### Force push to Remote Repository

```sh
git push -f <remote-name> <branch-name>
```

### Group commits by authors and title

```sh
git shortlog
```

### Forced push but still ensure you don't overwrite other's work

```sh
git push --force-with-lease <remote-name> <branch-name>
```

### Number of commits in a branch

```sh
git rev-list --count <branch-name>
```

### Add object notes

```sh
git notes add -m 'Note on the previous commit....'
```

### Apply commit from another repository

```sh
git --git-dir=<source-dir>/.git format-patch -k -1 --stdout <SHA1> | git am -3 -k
```

### Specific fetch reference

```sh
git fetch origin master:refs/remotes/origin/mymaster
```

### Generates a summary of pending changes

```sh
git request-pull v1.0 https://git.ko.xz/project master:for-linus
```

### Show git status short

```sh
git status --short --branch
```

### Checkout a commit prior to a day ago

```sh
git checkout master@{yesterday}
```

### Push the current branch to the same name on the remote repository

```sh
git push origin HEAD
```

### Push a new local branch to remote repository and track

```sh
git push -u origin <branch_name>
```

### Update a submodule to the latest commit

```sh
cd <path-to-submodule>
git pull origin <branch>
cd <root-of-your-main-project>
git add <path-to-submodule>
git commit -m "submodule updated"
```

### Duplicating a repository

```sh
git clone --bare https://github.com/exampleuser/old-repository.git

git push --mirror https://github.com/exampleuser/new-repository.git
```
## Branching

### List all branches that are already merged into master

```sh
git branch --merged master
```

### Remove branches that have already been merged with master

```sh
git branch --merged master | grep -v '^\*' | xargs -n 1 git branch -d
```

**Alternatives:**

```sh
git branch --merged master | grep -v '^\*\|  master' | xargs -n 1 git branch -d # will not delete master if master is not checked out
```

### List all branches and their upstreams, as well as last commit on branch

```sh
git branch -vv
```

### Track upstream branch

```sh
git branch -u origin/mybranch
```

### Delete local branch

```sh
git branch -d <local_branchname>
```

### Get list of all local and remote branches

```sh
git branch -a
```

### Get only remote branches

```sh
git branch -r
```

### Find out branches containing commit-hash

```sh
git branch -a --contains <commit-ish>
```

**Alternatives:**

```sh
git branch --contains <commit-ish>
```

### Rename a branch

```sh
git branch -m <new-branch-name>
```

**Alternatives:**

```sh
git branch -m [<old-branch-name>] <new-branch-name>
```

### Archive the `master` branch

```sh
git archive master --format=zip --output=master.zip
```

### Delete local branches that has been squash and merged in the remote.

```sh
git branch -vv | grep ': gone]' | awk '{print $1}' | xargs git branch -D
```

### Export a branch with history to a file.

```sh
git bundle create <file> <branch-name>
```

### Get the name of current branch.

```sh
git rev-parse --abbrev-ref HEAD
```

### Show the most recent tag on the current branch.

```sh
git describe --tags --abbrev=0
```

### List all branch is WIP

```sh
git checkout master && git branch --no-merged
```

### Preformatted patch file.

```sh
git format-patch -M upstream..topic
```

### Switch to a branch (modern alternative to checkout)

```sh
git switch <branch-name>
```

**Alternatives:**

```sh
git switch -c <new-branch-name>
```
## Log and History

### Show helpful guides that come with Git

```sh
git help -g
```

### Search change by content

```sh
git log -S'<a term in the source>'
```

### Show changes over time for specific file

```sh
git log -p <file_name>
```

### List all the conflicted files

```sh
git diff --name-only --diff-filter=U
```

### List of all files changed in a commit

```sh
git diff-tree --no-commit-id --name-only -r <commit-ish>
```

### Unstaged changes since last commit

```sh
git diff
```

### Changes staged for commit

```sh
git diff --cached
```

**Alternatives:**

```sh
git diff --staged
```

### Show both staged and unstaged changes

```sh
git diff HEAD
```

### What changed since two weeks?

```sh
git log --no-merges --raw --since='2 weeks ago'
```

**Alternatives:**

```sh
git whatchanged --since='2 weeks ago'
```

### See all commits made since forking from master

```sh
git log --no-merges --stat --reverse master..
```

### Show all tracked files

```sh
git ls-files -t
```

### Show all untracked files

```sh
git ls-files --others
```

### Show all ignored files

```sh
git ls-files --others -i --exclude-standard
```

### Visualize the version tree.

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

### Visualize the tree including commits that are only referenced from reflogs

```sh
git log --graph --decorate --oneline $(git rev-list --walk-reflogs --all)
```

### Show inline word diff.

```sh
git diff --word-diff
```

### Show changes using common diff tools.

```sh
git difftool [-t <tool>] <commit1> <commit2> <path>
```

### Commits in Branch1 that are not in Branch2

```sh
git log Branch1 ^Branch2
```

### List n last commits

```sh
git log -<n>
```

**Alternatives:**

```sh
git log -n <n>
```

### Open all conflicted files in an editor.

```sh
git diff --name-only | uniq | xargs $EDITOR
```

### View the GPG signatures in the commit log

```sh
git log --show-signature
```

### Extract file from another branch.

```sh
git show <branch_name>:<file_name>
```

### List only the root and merge commits.

```sh
git log --first-parent
```

### List commits and changes to a specific file (even through renaming)

```sh
git log --follow -p -- <file_path>
```

### Search Commit log across all branches for given text

```sh
git log --all --grep='<given-text>'
```

### Get first commit in a branch (from master)

```sh
git log --oneline master..<branch-name> | tail -1
```

**Alternatives:**

```sh
git log --reverse master..<branch-name> | head -6
```

### Show the author, time and last revision made to each line of a given file

```sh
git blame <file-name>
```

### Show how many lines does an author contribute

```sh
git log --author='_Your_Name_Here_' --pretty=tformat: --numstat | gawk '{ add += $1; subs += $2; loc += $1 - $2 } END { printf "added lines: %s removed lines: %s total lines: %s
", add, subs, loc }' -
```

**Alternatives:**

```sh
git log --author='_Your_Name_Here_' --pretty=tformat: --numstat | awk '{ add += $1; subs += $2; loc += $1 - $2 } END { printf "added lines: %s, removed lines: %s, total lines: %s
", add, subs, loc }' - # on Mac OSX
```

### Show all the git-notes

```sh
git log --show-notes='*'
```

### List unpushed git commits

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

### Add everything, but whitespace changes

```sh
git diff --ignore-all-space | git apply --cached
```

### blame on certain range

```sh
git blame -L <start>,<end>
```

### Show a Git logical variable.

```sh
git var -l | <variable>
```

### Get the repo name.

```sh
git rev-parse --show-toplevel
```

### logs between date range

```sh
git log --since='FEB 1 2017' --until='FEB 14 2017'
```

### Exclude author from logs

```sh
git log --perl-regexp --author='^((?!excluded-author-regex).*)$'
```

### View expanded details of changes in last commit

```sh
git show
```

### Visualize each position of HEAD in the last 30 days

```sh
git reflog
```
## Merging and Rebasing

### Rebases 'feature' to 'master' and merges it in to master

```sh
git rebase master feature && git checkout master && git merge -
```

### Stash changes before rebasing

```sh
git rebase --autostash
```

### Squash fixup commits normal commits.

```sh
git rebase -i --autosquash
```

### Change previous two commits with an interactive rebase.

```sh
git rebase --interactive HEAD~2
```

### Find common ancestor of two branches

```sh
git merge-base <branch-name> <other-branch-name>
```

### Change a branch base

```sh
git rebase --onto <new_base> <old_base>
```
## Miscellaneous

### Everyday Git in twenty commands or so

```sh
git help everyday
```

### Untrack files without deleting

```sh
git rm --cached <file_path>
```

**Alternatives:**

```sh
git rm --cached -r <directory_path>
```

### Don’t consider changes for tracked file.

```sh
git update-index --assume-unchanged <file_name>
```

### Check if the change was a part of a release.

```sh
git name-rev --name-only <SHA-1>
```

### List ignored files.

```sh
git check-ignore *
```

### Count unpacked number of objects and their disk consumption.

```sh
git count-objects --human-readable
```

### Prune all unreachable objects from the object database.

```sh
git gc --prune=now --aggressive
```

### Instantly browse your working repository in gitweb.

```sh
git instaweb [--local] [--httpd=<httpd>] [--port=<port>] [--browser=<browser>]
```

### Find lines matching the pattern (regex or string) in tracked files

```sh
git grep --heading --line-number 'foo bar'
```

### Backup untracked files.

```sh
git ls-files --others -i --exclude-standard | xargs zip untracked.zip
```

### Send a collection of patches as emails

```sh
git send-email [<options>] <file|directory>…

git send-email [<options>] <format-patch options>
```
## Remotes

### Changing a remote's URL

```sh
git remote set-url origin <URL>
```

### Get list of all remote references

```sh
git remote
```

**Alternatives:**

```sh
git remote show
```

### Adding Remote name

```sh
git remote add <remote-nickname> <remote-url>
```

### List all currently configured remotes

```sh
git remote -v
```

### List references in a remote repository

```sh
git ls-remote git://git.kernel.org/pub/scm/git/git.git
```

### Refresh the list of remote branches

```sh
git remote update origin --prune
```
## Setup and Config

### Remove sensitive data from history, after a push

```sh
git filter-branch --force --index-filter 'git rm --cached --ignore-unmatch <path-to-your-file>' --prune-empty --tag-name-filter cat -- --all && git push origin --force --all
```

### Reset author, after author has been changed in the global config.

```sh
git commit --amend --reset-author --no-edit
```

### Get git bash completion

```sh
curl -L http://git.io/vfhol > ~/.git-completion.bash && echo '[ -f ~/.git-completion.bash ] && . ~/.git-completion.bash' >> ~/.bashrc
```

### Git Aliases

```sh
git config --global alias.<handle> <command> 
git config --global alias.st status
```

### Always rebase instead of merge on pull.

```sh
git config --global pull.rebase true
```

**Alternatives:**

```sh
#git < 1.7.9
git config --global branch.autosetuprebase always
```

### List all the alias and configs.

```sh
git config --list
```

### Make git case sensitive.

```sh
git config --global core.ignorecase false
```

### Add custom editors.

```sh
git config --global core.editor '$EDITOR'
```

### Auto correct typos.

```sh
git config --global help.autocorrect 1
```

### Reuse recorded resolution, record and reuse previous conflicts resolutions.

```sh
git config --global rerere.enabled 1
```

### Remove entry in the global config.

```sh
git config --global --unset <entry-name>
```

### Ignore file mode changes on commits

```sh
git config core.fileMode false
```

### Turn off git colored terminal output

```sh
git config --global color.ui false
```

### Specific color settings

```sh
git config --global <specific command e.g branch, diff> <true, false or always>
```

### Alias: git undo

```sh
git config --global alias.undo '!f() { git reset --hard $(git rev-parse --abbrev-ref HEAD)@{${1-1}}; }; f'
```

### Edit \[local/global] git config

```sh
git config [--global] --edit
```

### List all git aliases

```sh
git config -l | grep alias | sed 's/^alias\.//g'
```

**Alternatives:**

```sh
git config -l | grep alias | cut -d '.' -f 2
```

### Use SSH instead of HTTPs for remotes

```sh
git config --global url.'git@github.com:'.insteadOf 'https://github.com/'
```

### Prevent auto replacing LF with CRLF

```sh
git config --global core.autocrlf false
```

### Edit config for each level

```sh
git config --edit --system

git config --edit --global

git config --edit --local
```
## Stashing

### Saving current state of tracked files without committing

```sh
git stash
```

**Alternatives:**

```sh
git stash push
```

### Saving current state of unstaged changes to tracked files

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

### Saving current state including untracked files

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

### Saving current state with message

```sh
git stash push -m <message>
```

**Alternatives:**

```sh
git stash push --message <message>
```

### Saving current state of all files (ignored, untracked, and tracked)

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

### Show list of all saved stashes

```sh
git stash list
```

### Show the contents of any stash in patch form

```sh
git stash show -p <stash@{n}>
```

### Apply any stash without deleting from the stashed list

```sh
git stash apply <stash@{n}>
```

### Apply last stashed state and delete it from stashed list

```sh
git stash pop
```

**Alternatives:**

```sh
git stash apply stash@{0} && git stash drop stash@{0}
```

### Delete all stored stashes

```sh
git stash clear
```

**Alternatives:**

```sh
git stash drop <stash@{n}>
```
## Submodules and Subtrees

### Update all the submodules

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

### Deploying git tracked subfolder to gh-pages

```sh
git subtree push --prefix subfolder_name origin gh-pages
```

**Alternatives:**

```sh
git subtree push --prefix subfolder_name origin branch_name
```

### Adding a project to repo using subtree

```sh
git subtree add --prefix=<directory_name>/<project_name> --squash git@github.com:<username>/<project_name>.git master
```

### Get latest changes in your repo for a linked project using subtree

```sh
git subtree pull --prefix=<directory_name>/<project_name> --squash git@github.com:<username>/<project_name>.git master
```
## Tagging

### Create local tag

```sh
git tag <tag-name>
```

### Delete local tag

```sh
git tag -d <tag-name>
```
## Undoing Changes

### Sync with remote, overwrite local changes

```sh
git fetch origin && git reset --hard origin/master && git clean -f -d
```

### Git reset first commit

```sh
git update-ref -d HEAD
```

### Reset: preserve uncommitted local changes

```sh
git reset --keep <commit>
```

### Revert: Undo a commit by creating a new commit

```sh
git revert <commit-ish>
```

### Reset: Discard commits, advised for private branch

```sh
git reset <commit-ish>
```

### Before deleting untracked files/directory, do a dry run to get the list of these files/directories

```sh
git clean -n
```

### Forcefully remove untracked files

```sh
git clean -f
```

### Forcefully remove untracked directory

```sh
git clean -f -d
```

### Undo assume-unchanged.

```sh
git update-index --no-assume-unchanged <file_name>
```

### Clean the files from `.gitignore`.

```sh
git clean -X -f
```

### Dry run. (any command that supports dry-run flag should do.)

```sh
git clean -fd --dry-run
```

### Unstaging Staged file

```sh
git reset HEAD <file-name>
```

### Revert: Reverting an entire merge

```sh
git revert -m 1 <commit-ish>
```

### Restore file (modern alternative to reset/checkout --)

```sh
git restore <file-name>
```

**Alternatives:**

```sh
git restore --staged <file-name>
```

## [7. Free Programming Books (Chinese)](/content/EbookFoundation/free-programming-books/books/free-programming-books-zh/week/README.md)

### 人工智能

*   [大规模语言模型：从理论到实践](https://llmbook-zh.github.io) - 张奇、桂韬、郑锐、黄沛 等
*   [动手学强化学习](https://hrl.boyuai.com) - 张伟楠、沈键、俞勇
*   [动手学深度学习](https://zh.d2l.ai) - 阿斯顿·张、李沐、扎卡里·C·立顿、亚历山大·J·斯莫拉
*   [南瓜书PumpkinBook](https://datawhalechina.github.io/pumpkin-book) - Datawhale
*   [深度学习500问 (⭐57k)](https://github.com/scutan90/DeepLearning-500-questions) - scutan90
*   [神经网络与深度学习](https://nndl.github.io) - 邱锡鹏

## [8. Awesome Cli Apps in a Csv](/content/toolleeo/awesome-cli-apps-in-a-csv/week/README.md)

### Chat and instant messaging

*   [Instagram CLI (⭐1.7k)](https://github.com/supreme-gg-gg/instagram-cli) - Instagram from your terminal; It allows you to use social media more intentionally (chat, stay updated with post and stories without falling into endless brainrot).
*   [nchat (⭐1.6k)](https://github.com/d99kris/nchat) - Terminal Telegram, WhatsApp and Signal client for LInux and macOS.
*   [nostratui (⭐5)](https://github.com/adamm-xyz/nostratui) - TUI for browsing Nostr posts, written in Rust.
*   [nostui (⭐64)](https://github.com/akiomik/nostui) - TUI client for Nostr.
*   [Sclack (⭐2.5k)](https://github.com/haskellcamargo/sclack) - CLI client for Slack.
*   [siggo (⭐327)](https://github.com/derricw/siggo) - TUI for signal-cli, written in Go, vim-style ux (quick messages, emoji support, configurable contacts, filter messages).
*   [slack-term (⭐6.6k)](https://github.com/erroneousboat/slack-term) - Slack client for the  terminal.
*   [tgt (⭐841)](https://github.com/FedericoBruzzone/tgt) - A TUI for Telegram written in Rust.
*   [tuisky (⭐159)](https://github.com/sugyan/tuisky) - TUI client for Bluesky.
*   [WeeChat](https://weechat.org/) - Fast and light chat client, customizable and extensible with scripts.
*   [Zulip Terminal (⭐818)](https://github.com/zulip/zulip-terminal) - Official Zulip terminal client with TUI.

### Containerization and virtualization

*   [EMU2 (⭐451)](https://github.com/dmsc/emu2) - A simple DOS emulator for the Linux text console, supporting basic DOS system calls and console I/O.

### DevOps

*   [Amazon EC2 Instance Selector (⭐927)](https://github.com/aws/amazon-ec2-instance-selector) - A CLI tool and go library which recommends instance types based on resource criteria like vcpus and memory.

### Fuzzy finders and option pickers

*   [Fnf (⭐46)](https://github.com/leo-arch/fnf) - An interactive fuzzy finder for the terminal; As you type a query, fnf  filters candidates and instantly updates the sorted list.

### Games

*   [tinytetris (⭐3.2k)](https://github.com/taylorconor/tinytetris) - 80x23 terminal tetris game.

### Graphics

*   [asciiMOL (⭐406)](https://github.com/dewberryants/asciiMol) - Curses based ASCII molecule viewer for terminals.
*   [GiF for CLI (⭐2.9k)](https://github.com/google/gif-for-cli) - Convert a GIF, short video or a query into ASCII art.

### Networking

*   [bluetui (⭐2.6k)](https://github.com/pythops/bluetui) - A TUI for managing bluetooth devices on Linux.

### Note taking

*   [Captain's Log (⭐363)](https://github.com/NikolaDucak/caps-log) - A small TUI journaling tool (daily entries saved as md files, tags for organizing entries, browse tags, calendar view, encrypted logs, storage using a git repository).

### Time trackers

*   [arttime (⭐1.3k)](https://github.com/reportaman/arttime) - A feature-rich clock/ timer/ pattern-based time manager in terminal with curated text-art.

## [9. Awesome Polars](/content/ddotta/awesome-polars/week/README.md)

### Polars plugins / Miscellaneous

*   [raffalib-python (⭐0)](https://github.com/raffaem/raffalib-python) - [STATA](https://www.stata.com/)-like logging capabilities by [@raffaem](https://github.com/raffaem).

## [10. Awesome Osint](/content/jivoi/awesome-osint/week/README.md)

### Data Breach Search Engines

*   [Leaker (⭐271)](https://github.com/vflame6/leaker) - Passive leak enumeration CLI tool that searches across 10 breach databases simultaneously.

### Speciality Search Engines

*   [SikkerAPI](https://www.sikkerapi.com/) - SikkerAPI is a free IP and threat intelligence provider, that publishes IP reputation scores, behavioral data and full attack sessions across 16+ different protocols.

### Social Media Tools / Twitter

*   [Xquik](https://xquik.com) - Real-time X (Twitter) data platform for tweet search, user lookup, follower/following extraction, engagement metrics, account monitoring, reply/retweet/quote extraction, community & Space data, and mutual follow checks.

### Username Check / GitHub

*   [Antisocial (⭐1)](https://github.com/lukeslp/antisocial) - Find forgotten accounts across 30+ platforms using three-tier verification: official APIs first, then browser automation, then HTTP content analysis. Reduces false positives to around 5%. Deep search mode adds 500+ platforms via the WhatsMyName database.

### People Investigations / GitHub

*   [BuscaPaginasBlancas (⭐0)](https://github.com/GeiserX/BuscaPaginasBlancas) - OSINT tool for extracting contact information from Spanish white pages (Paginas Blancas).

### Threat Intelligence / GitHub

*   [Pharos AI](https://conflicts.app) - Real-time open-source intelligence dashboard for conflict tracking with interactive geospatial visualization, multi-source RSS monitoring, and actor dossiers.

## [11. Awesome Mac](/content/jaywcjlove/awesome-mac/week/README.md)

### AI Client / Other Tools

*   [MiniClaw](https://miniclaw.bot) - macOS-native personal AI OS with 16 plugins, persistent vector memory, and multi-agent routing. Local-first, one-line install. [![Open-Source Software](https://jaywcjlove.github.io/sb/ico/min-oss.svg "Open Source Software") ![Freeware](https://jaywcjlove.github.io/sb/ico/min-free.svg "Freeware")](https://github.com/augmentedmike/miniclaw-os)

## [12. Awesome Graphql](/content/chentsulin/awesome-graphql/week/README.md)

### Tools - Testing, Prototyping & Mocking / React

*   [mockd (⭐2)](https://github.com/getmockd/mockd) - Multi-protocol mock server with GraphQL schema mocking, resolver configuration, and query validation. Also supports HTTP, gRPC, WebSocket, MQTT, and SOAP.

## [13. Free for Dev](/content/ripienaar/free-for-dev/week/README.md)

### APIs, Data, and ML

*   [SikkerAPI](https://sikkerapi.com) — Free IP Reputation & Threat Intelligence, powered by a globally distributed high interaction honeypot network and community reported abuse incidents. 1,000 free IP lookups, TAXII indicators & reports per day, pull 5,000 fresh IPs from our blacklists daily and monitor your own CIDR ranges (/16) free free.

### Monitoring

*   [supaguard.app](https://supaguard.app/) - Synthetic monitoring from 20+ global regions. The free tier includes 1,000 browser checks/mo with AI-driven self-healing and automated test generation.

## [14. Quick Look Plugins](/content/sindresorhus/quick-look-plugins/week/README.md)

### Plugins

### [Source Code Preview](https://anybox.ltd/source-code-preview) 💰

> Includes 10+ color themes and syntax highlighting for 50+ languages, including JavaScript, Python, Java, CSS, and JSON.

Purchase on the [App Store](https://apps.apple.com/app/source-code-preview/id6759270528).

[![](https://github.com/sindresorhus/quick-look-plugins/raw/main/screenshots/SourceCodePreview.png)](https://anybox.ltd/source-code-preview)

## [15. Awesome Go](/content/avelino/awesome-go/week/README.md)

### Bloom and Cuckoo Filters

*   [ribbonGo (⭐3)](https://github.com/RibbonGo/ribbonGo) - First pure Go implementation of Ribbon filters (practically smaller than Bloom and Xor) for space-efficient approximate set membership queries.

### Queues

*   [deheap (⭐15)](https://github.com/aalpar/deheap) - Doubly-ended heap (min-max heap) with O(log n) access to both minimum and maximum elements.

### Other Software / Libraries for creating HTTP middlewares

*   [onWatch (⭐277)](https://github.com/onllm-dev/onWatch) - Monitor AI API quotas across providers locally with historical tracking, alerts, and a web dashboard to avoid surprise throttling and budget overruns.

### Benchmarks / Libraries for creating HTTP middlewares

*   [vizb (⭐60)](https://github.com/goptics/vizb) - A CLI tool to visualize Go benchmark data in 4D.

## [16. Awesome Rust](/content/rust-unofficial/awesome-rust/week/README.md)

### Applications

*   [arimxyer/models (⭐262)](https://github.com/arimxyer/models) \[[modelsdev](https://crates.io/crates/modelsdev)] - A TUI for browsing AI models, benchmarks, and coding agents [![CI](https://github.com/arimxyer/models/actions/workflows/ci.yml/badge.svg)](https://github.com/arimxyer/models/actions/workflows/ci.yml)

### Development tools / Workflow Automation

*   [cachix/devenv (⭐6.5k)](https://github.com/cachix/devenv) - Fast, declarative, reproducible, and composable developer environments using Nix [![CI](https://github.com/cachix/devenv/actions/workflows/release.yml/badge.svg)](https://github.com/cachix/devenv/actions/workflows/release.yml)

### Libraries / Artificial Intelligence

*   [memvid/memvid (⭐13k)](https://github.com/memvid/memvid) \[[memvid-core](https://crates.io/crates/memvid-core)] - A single-file portable memory layer for AI agents with vector search, full-text search, and long-term recall packed into one `.mv2` file

## [17. Awesome Broadcasting](/content/ebu/awesome-broadcasting/week/README.md)

### Animation, Graphics & Video Playout

*   [OGraf (⭐60)](https://github.com/ebu/ograf) - Open specification for HTML based Graphics, used in live television and post production workflows.

### SCTE-35 & SCTE-104

*   [wireshark-scte (⭐2)](https://github.com/m1tk4/wireshark-scte) - SCTE-104 protocol dissector for Wireshark.

### Subtitling

*   [ttconv (⭐226)](https://github.com/sandflow/ttconv) - Subtitle conversion library and CLI tool. Converts between STL, SRT, TTML, SCC, TTML and WebVTT files.

## [18. Awesome Iot](/content/HQarroum/awesome-iot/week/README.md)

### Software / Miscellaneous

*   [PiSpot-Show (⭐0)](https://github.com/GeiserX/PiSpot-Show) - A Raspberry Pi captive portal that creates a WiFi hotspot displaying a customizable web page to connected users using hostapd, dnsmasq, and nginx. Useful for events, marketing, and education.

## [19. Awesome Ai in Finance](/content/georgezouq/awesome-ai-in-finance/week/README.md)

### Data Sources / Traditional Markets

*   [ValueRay](https://www.valueray.com/api) - Technical, quantitative and sentiment data for stocks and ETFs with risk metrics, peer percentiles and market regime signals. Optimized for AI/LLM agents.

### Data Sources / Crypto Currencies

*   [Frostbyte Crypto API](https://agent-gateway-kappa.vercel.app) - Free real-time cryptocurrency price data API. Supports BTC, ETH, SOL, and 20+ tokens. No signup or API key required for basic endpoints. JSON responses with price, 24h change, market cap, and volume.

---

- Next: [Mar 09 - Mar 15, 2026](/content/2026/10/README.md)