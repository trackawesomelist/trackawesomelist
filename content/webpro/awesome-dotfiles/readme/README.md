# Awesome Dotfiles Overview

A curated list of dotfiles resources.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/webpro/awesome-dotfiles/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 webpro/awesome-dotfiles](https://github.com/webpro/awesome-dotfiles) · ⭐ 8.1K · 🏷️ Development Environment

[ [Daily](/content/webpro/awesome-dotfiles/README.md) / [Weekly](/content/webpro/awesome-dotfiles/week/README.md) / Overview ]

---

# Awesome dotfiles

A curated list of dotfiles resources. Inspired by the [awesome (⭐268k)](https://github.com/sindresorhus/awesome) list thing.
Note that some articles or tools may look old or old-fashioned, but this usually means they're battle-tested and mature
(like dotfiles themselves). Feel free to propose new articles, projects or tools!

## Articles

### Introductions

*   [Getting started with dotfiles](https://www.webpro.nl/articles/getting-started-with-dotfiles)
    ([L. Kappert](https://github.com/webpro))
*   [Getting started with dotfiles](https://driesvints.com/blog/getting-started-with-dotfiles/)
    ([D. Vints](https://github.com/driesvints))
*   [Managing your dotfiles](https://www.webpro.nl/articles/managing-your-dotfiles)
*   [Dotfiles Are Meant to Be Forked](https://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/)
*   [Dotfile discovery](https://wynnnetherland.com/journal/dotfiles-discovery/)
*   [I do Dotfiles!](https://jogendra.dev/i-do-dotfiles)

### Tutorials

*   [Setting up a new (OS X) development machine: Part 3 - Dotfiles and custom SSH config](https://mattstauffer.com/blog/setting-up-a-new-os-x-development-machine-part-3-dotfiles-rc-files-and-ssh-config/)
*   [Setting Up a Mac Dev Machine From Zero to Hero With Dotfiles](https://code.tutsplus.com/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449t)
*   [Using Git and GitHub to manage your dotfiles](http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/)
*   [conf.d like directories for zsh/bash dotfiles](https://chr4.org/blog/2014/09/10/conf-dot-d-like-directories-for-zsh-slash-bash-dotfiles/)
*   [Managing your dotfiles](https://www.anishathalye.com/2014/08/03/managing-your-dotfiles/)
*   [The best way to store your dotfiles: A bare Git repository](https://www.atlassian.com/git/tutorials/dotfiles)
*   [Dotfiles Management](https://mitxela.com/projects/dotfiles_management)

### Shell startup

*   [Shell startup scripts](https://blog.flowblok.id.au/2013-02/shell-startup-scripts.html)
*   [Zsh/Bash startup files loading order](https://shreevatsa.wordpress.com/2008/03/30/zshbash-startup-files-loading-order-bashrc-zshrc-etc/)

### Using specific tools

*   [Using GNU Stow to manage your dotfiles](http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html)
*   [Managing Dotfile Symlinks with GNU Stow](https://spin.atomicobject.com/2014/12/26/manage-dotfiles-gnu-stow/)
*   [Dotfiles and dev tools provisioned by Ansible](http://palcu.blogspot.com/2014/06/dotfiles-and-dev-tools-provisioned-by.html)
*   [Manage a development machine with Ansible](http://kreusch.com.br/blog/2013/12/03/manage-a-development-machine-with-ansible)

## Find dotfiles repos

There are many great dotfiles repos out there, each containing their own inspiration and gems. One way to go through
them is to [search GitHub for "dotfiles"](https://github.com/search?q=dotfiles\&type=Repositories).

Also see:

*   [Google for "dotfiles"](https://www.google.nl/search?q=dotfiles)
*   [Archlinux collection](https://wiki.archlinux.org/index.php/Dotfiles)
*   Tip: search for a filename on GitHub, e.g.
    [in:path .gitconfig](https://github.com/search?utf8=%E2%9C%93\&type=Code\&q=in%3Apath+.gitconfig).

## Example dotfiles repos

A collection of the most popular, well-maintained, and collaborative dotfiles repositories & frameworks. Some projects
contain just the dotfiles. Others go further by allowing you to easily add your own custom dotfiles, and some include
scripts to manage dotfiles and plugins.

### Bash

| Title                                                                     | Description                                  | Focus                                                                                                                        |
| :------------------------------------------------------------------------ | :------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------- |
| [Bash it (⭐14k)](https://github.com/Bash-it/bash-it)                      | Community bash framework.                    | Autocompletion, themes, aliases, custom functions. Well-structured framework                                                 |
| [Mathias’s dotfiles (⭐29k)](https://github.com/mathiasbynens/dotfiles)    | Sensible hacker defaults for macOS           | 🔧 .files, including \~/.macos — sensible hacker defaults for macOS                                                          |
| [webpro's dotfiles (⭐983)](https://github.com/webpro/dotfiles)            | macOS dotfiles                               | Bash, Homebrew, Brew Cask, Git, Node.js, Hammerspoon.                                                                        |
| [rootbeersoup's dotfiles (⭐65)](https://github.com/darrylabbate/dotfiles) | Effortless Bash, Vim and macOS configuration | A `curl \| sh` installer and a Makefile offer portable and effortless setup for either permanent or temporary configuration. |

### Zsh

| Title                                                                 | Description                                                              | Focus                                                                                                                       |
| :-------------------------------------------------------------------- | :----------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------- |
| [thoughtbot dotfiles (⭐7.7k)](https://github.com/thoughtbot/dotfiles) | Set of vim, zsh, git, and tmux configuration files                       | Zsh, vim, tmux, git, homebrew. Uses [rcm (⭐3k)](https://github.com/thoughtbot/rcm).                                         |
| [oh-my-zsh](https://ohmyz.sh)                                         | Community-driven framework for managing your zsh configuration.          | Oh My Zsh is an open source, community-driven framework for managing your Zsh configuration                                 |
| [Prezto (⭐14k)](https://github.com/sorin-ionescu/prezto)              | The configuration framework for Zsh.                                     | Enriches the command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes. |
| [Dries's dotfiles (⭐1.9k)](https://github.com/driesvints/dotfiles)    | Simplified approach to dotfiles for macOS                                | Zsh, Oh My Zsh, macOS, Homebrew, Mackup                                                                                     |
| [sobolevn's dotfiles (⭐612)](https://github.com/sobolevn/dotfiles)    | Dotfiles for the developer happiness                                     | macos, zsh, brew, vscode, codespaces, python, node, elixir                                                                  |
| [yutkat's dotfiles (⭐524)](https://github.com/yutkat/dotfiles)        | Well-maintained dotfiles that use CI to test and measure startup speeds. | Zsh, Neovim, Wezterm, swaywm working on Arch/Ubuntu/Fedora Linux.                                                           |
| [Luke's voidrice (⭐4.1k)](https://github.com/LukeSmithxyz/voidrice)   | My dotfiles (deployed by LARBS)                                          | Zsh, vim/nvim, zsf                                                                                                          |

### Fish

| Title                                                            | Description                                                                    | Focus                                                                            |
| :--------------------------------------------------------------- | :----------------------------------------------------------------------------- | :------------------------------------------------------------------------------- |
| [oh-my-fish (⭐9.7k)](https://github.com/oh-my-fish/oh-my-fish)   | The Fish Shell Framework                                                       | Core infrastructure to allow you to install packages to extend/modify your shell |
| [Paul's dotfiles (⭐4.1k)](https://github.com/paulirish/dotfiles) | paul's fish, bash, git, etc config files. good stuff.                          | Fish, macOS, Homebrew, Custom Shell functions                                    |
| [rkalis's dotfiles (⭐228)](https://github.com/rkalis/dotfiles)   | Well-maintained dotfiles featuring Fish, repository management and Hammerspoon | Fish, macOS, Homebrew, Repository management, Hammerspoon                        |

### Ansible

| Title                                                          | Description                                  | Focus                                                                           |
| :------------------------------------------------------------- | :------------------------------------------- | :------------------------------------------------------------------------------ |
| [.dots (⭐78)](https://github.com/Addvilz/dots)                 | New and upgraded dotfiles, now with Ansible! | Completely automated desktop setup, configuration and maintenance using Ansible |
| [sloria's dotfiles (⭐141)](https://github.com/sloria/dotfiles) | sloria's dotfiles as Ansible roles           | Sets up a full local development environment with a single command              |

## Tools

*   [Ansible](https://www.ansible.com) - Radically simple configuration-management, application deployment,
    task-execution, and multinode orchestration engine.
*   [bashdot (⭐98)](https://github.com/bashdot/bashdot) - Minimalist dotfile management framework written entirely in bash.
*   [chezmoi (⭐10k)](https://github.com/twpayne/chezmoi) - Manage your dotfiles securely across multiple machines.
*   [comtrya (⭐370)](https://github.com/comtrya/comtrya) - Configuration management for localhost, written in Rust, for Linux,
    BSD, macOS, and Windows
*   [dotbare (⭐596)](https://github.com/kazhala/dotbare) - Manage dotfiles interactively with fzf.
*   [dotbot (⭐6.4k)](https://github.com/anishathalye/dotbot) - Tool that bootstraps your dotfiles.
*   [dotdrop (⭐1.7k)](https://github.com/deadc0de6/dotdrop) - Save your dotfiles once, deploy them everywhere.
*   [Fisher (⭐6.9k)](https://github.com/jorgebucaran/fisher) - A package manager for Fish
*   [fresh](https://freshshell.com) - Keep your dotfiles fresh. Fresh is a tool to source shell configuration (aliases,
    functions, etc) from others into your own configuration files.
*   [GNU Stow](http://www.gnu.org/software/stow/) - Symlink farm manager which takes distinct packages of software and/or
    data located in separate directories on the filesystem, and makes them appear to be installed in the same place.
*   [homeshick (⭐2k)](https://github.com/andsens/homeshick) - Git dotfile synchronizer written in Bash.
*   [mackup (⭐14k)](https://github.com/lra/mackup) - Keep your application settings in sync (OS X/Linux).
*   [Pearl (⭐219)](https://github.com/pearl-core/pearl) - Package manager that allows to control, sync, share dotfiles as
    packages automatically activated during shells or editors startup. There is a wide range of packages already available
    in the [Official Pearl Hub](https://github.com/pearl-hub) (for Linux and OSX).
*   [rcm (⭐3k)](https://github.com/thoughtbot/rcm) - rc file (dotfile) management.
*   [themer (⭐5.2k)](https://github.com/themerdev/themer) - Manage and generate themes across your development tools from within
    your dotfiles.
*   [toml-bombadil (⭐169)](https://github.com/oknozor/toml-bombadil) - Templatize and manage your dotfiles.
*   [yadm (⭐4.3k)](https://github.com/TheLocehiliosan/yadm) - Tool for managing a collection of files across multiple computers,
    using a shared Git repository and some additional features.

### macOS

*   [dockutil (⭐1.2k)](https://github.com/kcrawford/dockutil) - Command line tool for managing dock items
*   [mas (⭐10k)](https://github.com/mas-cli/mas) - Mac App Store command line interface
*   [zero (⭐249)](https://github.com/zero-sh/zero.sh) - Radically simple personal bootstrapping tool for macOS.

## Miscellaneous

*   [dotfiles.github.io](https://dotfiles.github.io/) - Your unofficial guide to dotfiles on GitHub.
*   [Filesystem Hierarchy Standard](https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard) - Directory structure and
    directory contents in Linux distributions.
*   [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) -
    [Summary](https://wiki.archlinux.org/title/XDG_Base_Directory)
*   [A lesson in shortcuts](https://www.reddit.com/r/linux/comments/at05xh/comment/egyj6lr/) - How the idea of "hidden" or
    "dot" files was born, by Rob Pike (originally posted on Google+)

## Related Lists

*   [Awesome Dev Env (⭐2.6k)](https://github.com/jondot/awesome-devenv) - Curated list of awesome tools, resources and workflow
    tips making an awesome development environment.
*   [Awesome Fish (⭐3.6k)](https://github.com/jorgebucaran/awsm.fish) - Curated list of packages, prompts, and resources for the
    fish shell.
*   [Awesome Shell (⭐28k)](https://github.com/alebcay/awesome-shell) - Curated list of awesome command-line frameworks, toolkits,
    guides and gizmos.
*   [Awesome Sysadmin (⭐20k)](https://github.com/awesome-foss/awesome-sysadmin) - A curated list of amazingly awesome open source
    sysadmin resources.
*   [Awesome Zsh Plugins (⭐13k)](https://github.com/unixorn/awesome-zsh-plugins) - List of Zsh plugins suitable for use with
    oh-my-zsh, antigen & Prezto.
*   [Terminals Are Sexy (⭐12k)](https://github.com/k4m4/terminals-are-sexy) - A curated list of Terminal frameworks, plugins &
    resources for CLI lovers.

## Archive/abandoned projects

*   [antigen](http://antigen.sharats.me)
*   [Bashstrap (⭐1.6k)](https://github.com/barryclark/bashstrap)
*   [battleschool (⭐417)](https://github.com/spencergibb/battleschool)
*   [Bork (⭐220)](https://github.com/mattly/bork)
*   [Cider (⭐841)](https://github.com/msanders/cider)
*   [dev-setup (⭐6k)](https://github.com/donnemartin/dev-setup)
*   [dotfiles (⭐563)](https://github.com/jbernard/dotfiles)
*   [dotstow (⭐96)](https://github.com/clayrisser/dotstow)
*   [Eduardo's dotfiles (⭐421)](https://github.com/eduardolundgren/dotfiles)
*   [ellipsis (⭐351)](https://github.com/ellipsis/ellipsis)
*   [emplace (⭐223)](https://github.com/tversteeg/emplace)
*   [holman does dotfiles (⭐7k)](https://github.com/holman/dotfiles)
*   [homesick (⭐2.4k)](https://github.com/technicalpickles/homesick)
*   [Kevin's dotfiles (⭐129)](https://github.com/kdeldycke/dotfiles)
*   [kody (⭐133)](https://github.com/jh3y/kody)
*   [OS X Defaults (⭐1.2k)](https://github.com/kevinSuttle/macOS-Defaults)
*   [osxc](http://osxc.github.io)
*   [vcsh (⭐2.1k)](https://github.com/RichiH/vcsh)
    ([article](https://blog.tfnico.com/2014/03/managing-dot-files-with-vcsh-and-myrepos.html),
    [article](https://www.kunxi.org/2014/02/manage-dotfiles-using-vcsh-and-mr/))
*   [YADR](http://skwp.github.io/dotfiles/)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Lars Kappert](https://www.webpro.nl) has waived all copyright and related or
neighboring rights to this work.

