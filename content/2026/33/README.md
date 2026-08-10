# Awesome List Updates on Aug 17 - Aug 23, 2026

10 awesome lists updated this week.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Icons](/content/vkarampinis/awesome-icons/week/README.md)

### Archive of Icons

*   [IconSearch](https://iconsearch.info/) - Search and compare 355,000+ SVG icons across 229 open-source libraries.

## [2. Awesome Mqtt](/content/awesome-mqtt/awesome-mqtt/week/README.md)

### Tools

*   [MQTTForge (⭐0)](https://github.com/ibrahimilkhan/mqtt-forge) - Test console that builds a broker's topics into a live tree, shows every frame on the wire, and publishes by hand. Desktop app for macOS, Windows and Linux, or a single Docker image.
*   [RunMQTT MQTT Topic ACL Linter](https://runmqtt.com/mqtt-acl-linter) - Browser-based, local-only validator for MQTT topic-filter ACLs that checks wildcard breadth, tenant boundaries, publish/subscribe direction, placeholders, and overlapping rules. [Source and method (⭐0)](https://github.com/visoar/mqtt-acl-linter).

## [3. Awesome Iot](/content/HQarroum/awesome-iot/week/README.md)

### Software / Libraries and Tools

*   [MQTT ACL Linter (⭐0)](https://github.com/visoar/mqtt-acl-linter) - Local-only MQTT topic ACL static analysis with optional RunMQTT policy checks.

## [4. Tips](/content/git-tips/tips/week/README.md)

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

**Alternatives:**

```sh
git restore <file_name>
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

### Sparse checkout: clone only specific directories

```sh
git clone --filter=blob:none --sparse <url> && cd <repo> && git sparse-checkout set <dir1> <dir2>
```

### Show output in columns

```sh
git branch --column
```

**Alternatives:**

```sh
git tag --column
```

### List worktrees

```sh
git worktree list
```

### Remove a worktree

```sh
git worktree remove <path>
```

**Alternatives:**

```sh
git worktree prune
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

### Compare two versions of a rebased branch

```sh
git range-diff <base>..<old-tip> <base>..<new-tip>
```

**Alternatives:**

```sh
git range-diff <rev1>...<rev2>
```

### Automate bisect with a test script

```sh
git bisect start <bad> <good> && git bisect run <script>
```

### Blame with line range

```sh
git blame -L <start>,<end> <file>
```

**Alternatives:**

```sh
git blame -L :'<funcname>' <file>
```

### Detect moved or copied lines in blame

```sh
git blame -M -C <file>
```

**Alternatives:**

```sh
git blame -C -C -C <file>
```

### Log with graph in oneline format

```sh
git log --oneline --graph --all --decorate
```

### Find commits where a file was deleted

```sh
git log --diff-filter=D --summary | grep delete
```

**Alternatives:**

```sh
git log --all --full-history -- <file>
```

### Show commit count per author per time period

```sh
git shortlog -sn --since='1 year ago'
```

**Alternatives:**

```sh
git shortlog -sne --all
```

### Verify commit signatures

```sh
git verify-commit <commit>
```

**Alternatives:**

```sh
git log --show-signature
```

### Show diff with word-level granularity using color

```sh
git diff --color-words
```

**Alternatives:**

```sh
git diff --word-diff=color
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

### Create a fixup commit and auto-squash

```sh
git commit --fixup=<commit> && git rebase -i --autosquash <commit>~1
```

### Rebase interactively from the root commit

```sh
git rebase -i --root
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

### Create a bundle file for offline sharing

```sh
git bundle create <file>.bundle --all
```

**Alternatives:**

```sh
git bundle create <file>.bundle <branch-name>
```

### Clone from a bundle file

```sh
git clone <file>.bundle <directory>
```

### Partial clone: clone without blobs for faster fetch

```sh
git clone --filter=blob:none <url>
```

**Alternatives:**

```sh
git clone --filter=tree:0 <url>
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

### Enable background maintenance for faster operations

```sh
git maintenance start
```

**Alternatives:**

```sh
git maintenance run --task=gc
```

### Sign commits with SSH key instead of GPG

```sh
git config gpg.format ssh && git config user.signingkey ~/.ssh/id_ed25519.pub && git commit -S -m '<message>'
```

### Enable rerere to auto-resolve recurring merge conflicts

```sh
git config rerere.enabled true
```

### Set default branch name for new repos

```sh
git config --global init.defaultBranch main
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

### Stash only unstaged changes

```sh
git stash push --keep-index
```

### Stash specific files

```sh
git stash push -m '<message>' <file1> <file2>
```

### Show a diffstat summary of a stash

```sh
git stash show --stat <stash@{n}>
```

**Alternatives:**

```sh
git stash show -p <stash@{n}>
```

## [5. Awesome Datascience](/content/academic/awesome-datascience/week/README.md)

### Newsletters / Book Deals (Affiliated)

*   [Bamboo Weekly](https://www.bambooweekly.com) - Weekly pandas exercises based on current events and real-world public data, with fully worked solutions. Issues older than two years are free, as are the first two questions + answers in current issues. [Archive](https://www.bambooweekly.com/archive/).

## [6. Awesome Claude Code](/content/hesreallyhim/awesome-claude-code/week/README.md)

### Start Here

*   [A Field Guide to Claude Fable 5](https://claude.com/blog/a-field-guide-to-claude-fable-finding-your-unknowns) by [Thariq Shihipar, Anthropic](https://github.com/ThariqS) - Really solid, insightful guidance on working/thinking with Claude Fable, and with AI in general. Very well written. Hints of Rumsfeld epistemology, but otherwise it's a great piece.
*   [Beyond the Prompt: Claude Code](https://arps18.github.io/posts/claude-code-mastery) by [Arpan Patel](https://arps18.github.io/) - This has what you need. Remarkably clear, information-dense, it's Claude Code: the good parts, for beginners, advanced users, pets, anybody.

## [7. Awesome Go](/content/avelino/awesome-go/week/README.md)

### Images

*   [eagle-image-api (⭐31)](https://github.com/nicobistolfi/eagle-image-api) - Image optimization and transformation API using libvips, deployable to AWS Lambda and CloudFront.

## [8. Awesome Mac](/content/jaywcjlove/awesome-mac/week/README.md)

### Education / Audio Record and Process

*   [Leafy](https://leafyapp.uk/) - Look up any word on screen with ⌥A, including in PDFs and images, and save it to a searchable local library. ![Freeware](https://jaywcjlove.github.io/sb/ico/min-free.svg "Freeware")

## [9. Awesome Selfhosted](/content/awesome-selfhosted/awesome-selfhosted/week/README.md)

### Software / Automation

*   [Mylar3](https://mylar.nerdfirehurricane.com/) - Automated Comic Book (cbr/cbz) downloader program for use with NZB and torrents. ([Source Code (⭐98)](https://github.com/MylarComics/mylar3)) `GPL-3.0` `Python/Docker`

## [10. Typography](/content/deanhume/typography/week/README.md)

### Tools

*   [What Font Finder - Identify a font from an image in the browser, with a confidence score and no upload.](https://whatfontfinder.com/font-identifier/)

---

- Next: [Aug 10 - Aug 16, 2026](/content/2026/32/README.md)