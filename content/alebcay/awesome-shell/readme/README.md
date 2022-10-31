# Awesome Shell Overview

A curated list of awesome command-line frameworks, toolkits, guides and gizmos. Inspired by awesome-php.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/alebcay/awesome-shell/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 alebcay/awesome-shell](https://github.com/alebcay/awesome-shell) · ⭐ 25K · 🏷️ Development Environment

[ [Daily](/content/alebcay/awesome-shell/README.md) / [Weekly](/content/alebcay/awesome-shell/week/README.md) / Overview ]

---

     █████╗ ██╗    ██╗███████╗███████╗ ██████╗ ███╗   ███╗███████╗
    ██╔══██╗██║    ██║██╔════╝██╔════╝██╔═══██╗████╗ ████║██╔════╝
    ███████║██║ █╗ ██║█████╗  ███████╗██║   ██║██╔████╔██║█████╗
    ██╔══██║██║███╗██║██╔══╝  ╚════██║██║   ██║██║╚██╔╝██║██╔══╝
    ██║  ██║╚███╔███╔╝███████╗███████║╚██████╔╝██║ ╚═╝ ██║███████╗
    ╚═╝  ╚═╝ ╚══╝╚══╝ ╚══════╝╚══════╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝
    ███████╗██╗  ██╗███████╗██╗     ██╗
    ██╔════╝██║  ██║██╔════╝██║     ██║
    ███████╗███████║█████╗  ██║     ██║
    ╚════██║██╔══██║██╔══╝  ██║     ██║
    ███████║██║  ██║███████╗███████╗███████╗
    ╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝╚══════╝

# Awesome Shell [![Awesome][awesome-badge]][awesome-link]

A curated list of awesome command-line frameworks, toolkits, guides and gizmos. Inspired by awesome-php. This awesome collection is also available on [Unix-Shell.ZEEF.com](https://unix-shell.zeef.com/caleb.xu).

*   [Shells](#shells)
*   [Command-Line Productivity](#command-line-productivity)
    *   [Directory Navigation](#directory-navigation)
*   [Customization](#customization)
*   [For Developers](#for-developers)
*   [System Utilities](#system-utilities)
*   [Downloading and Serving](#downloading-and-serving)
*   [Multimedia and File Formats](#multimedia-and-file-formats)
*   [Applications](#applications)
*   [Games](#games)
*   [Shell Package Management](#shell-package-management)
*   [Shell Script Development](#shell-script-development)
*   [Guides](#guides)
*   [**Awesome Zsh**][awesome-zsh]  [![Awesome][awesome-badge]][awesome-zsh]
*   [**Awesome Fish**][awesome-fish] [![Awesome][awesome-badge]][awesome-fish]
*   [Other Awesome Lists](#other-awesome-lists)

## Shells

*Choose your base shell.*

*   [bash](https://www.gnu.org/software/bash/) - GNU Project's shell (Bourne Again SHell)
*   [elvish](https://elv.sh/) - Friendly, expressive shell features like anonymous functions and data structures
*   [es](https://wryun.github.io/es-shell/) - The extensible shell, based on Plan 9's [rc (⭐195)](https://github.com/rakitzis/rc) shell
*   [fish](https://fishshell.com) - Smart and user-friendly command line shell
*   [ion (⭐1.3k)](https://github.com/redox-os/ion) - A modern system shell that features a simple, yet powerful, syntax. It is written entirely in Rust.
*   [ksh93 (⭐460)](https://github.com/att/ast) - Korn Shell
*   [mksh (⭐171)](https://github.com/MirBSD/mksh) - MirBSD Korn Shell
*   [ngs (⭐1.2k)](https://github.com/ngs-lang/ngs) - Fully featured scripting language created specifically for Ops. REPL is being developed.
*   [nushell (⭐21k)](https://github.com/nushell/nushell) - A modern shell written in Rust
*   [oksh (⭐265)](https://github.com/ibara/oksh) - Portable OpenBSD ksh
*   [osh](https://www.oilshell.org) - Bash compatible, with new/modern Unix shell language called Oil
*   [pdksh](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/bin/ksh/) - Public domain Korn shell
*   [powershell](https://docs.microsoft.com/en-us/powershell/scripting/overview) a cross-platform task automation and configuration management framework, consisting of a command-line shell and scripting language
*   [shell++ (⭐111)](https://github.com/alexst07/shell-plus-plus) - Friendly and modern functional and object oriented shell script language
*   [shenv (⭐33)](https://github.com/shenv/shenv) - Simple shell version management
*   [tcsh](https://www.tcsh.org/) - C shell with file name completion and command line editing
*   [xonsh](https://xon.sh) - Python-ish, BASHwards-looking shell language and command prompt
*   [yash](https://yash.osdn.jp/) - A POSIX-compliant command line shell with built-in support for completion and prediction based on command history
*   [zsh](https://www.zsh.org) - Powerful shell with scripting language

## Command-Line Productivity

*Search, bookmarks, multiplexing, and other tools that make your terminal experience more productive.*

*   [AdvancedNewFile (⭐197)](https://github.com/tanrax/terminal-AdvancedNewFile) - Fast creation of files and directories in a recursive way. Inspired by the Vim plugin.
*   [ag (⭐24k)](https://github.com/ggreer/the_silver_searcher) - Super fast string search through a directory hierarchy
*   [aliases (⭐439)](https://github.com/sebglazebrook/aliases) - Contextual, dynamic, organized aliases for bash
*   [autoenv (⭐5k)](https://github.com/inishchith/autoenv) - Directory-based environments
*   [bartib (⭐311)](https://github.com/nikolassv/bartib) - A simple timetracker for the command line. It saves a log of all tracked activities as a plaintext file and allows you to create flexible reports.
*   [bashhub (⭐1k)](https://github.com/rcaloras/bashhub-client) - :cloud: Bash history in the cloud. Indexed and searchable.
*   [boilr (⭐1.5k)](https://github.com/tmrts/boilr) - A blazingly fast CLI tool for creating projects from boilerplate templates.
*   [boom (⭐1.2k)](https://github.com/holman/boom) - Store links and snippets in the command line
*   [borg (⭐1.6k)](https://github.com/ok-borg/borg) - A terminal based search engine for bash commands
*   [browsh (⭐15k)](https://github.com/browsh-org/browsh) - The modern text-based browser
*   [Buku (⭐5.3k)](https://github.com/jarun/Buku) - Powerful command-line bookmark manager
*   [byobu](https://www.byobu.org) - Text-based window manager and terminal multiplexer
*   [cod (⭐433)](https://github.com/dim-an/cod) — A completion daemon for shell that learns when you invoke `--help` commands
*   [CloudClip (⭐69)](https://github.com/skywind3000/CloudClip) - Your own clipboard in the cloud, copy and paste text with gist between different systems
*   [ddgr (⭐2.4k)](https://github.com/jarun/ddgr) - DuckDuckGo from the terminal
*   [desk (⭐2.5k)](https://github.com/jamesob/desk) - A lightweight workspace manager for the shell
*   [direnv (⭐9.7k)](https://github.com/direnv/direnv) - An environment switcher for the shell, compare with autoenv
*   [dnote (⭐2.4k)](https://github.com/dnote/dnote) - A simple command line notebook with multi-device sync and web interface
*   [eureka (⭐568)](https://github.com/simeg/eureka/) - :bulb: CLI tool to input and store your ideas without leaving the terminal
*   [fasd (⭐5.8k)](https://github.com/clvv/fasd) - Command-line productivity booster, offers quick access to files and directories
*   [fd (⭐25k)](https://github.com/sharkdp/fd) - A simple, fast and user-friendly alternative to find.
*   [foxy (⭐38)](https://github.com/s-p-k/foxy) - Plain text bookmarks for Firefox and surf browsers.
*   [fselect (⭐3.3k)](https://github.com/jhspetersson/fselect) - Find files with SQL-like queries.
*   [funky (⭐609)](https://github.com/bbugyi200/funky) - Extends functionality of shell functions making them more powerful and flexible.
*   [fz (⭐432)](https://github.com/changyuheng/fz) - Seamless fuzzy tab completion for z
*   [fzf (⭐48k)](https://github.com/junegunn/fzf) - A command-line fuzzy finder
*   [gitmux (⭐345)](https://github.com/arl/gitmux) - Show Git status in Tmux status bar
*   [googler (⭐5.8k)](https://github.com/jarun/googler) - Google Search, Google Site Search, Google News from the terminal
*   [googlr (⭐35)](https://github.com/Astranno/googlr) - Command line tool that lets you search Google from your terminal.
*   [has (⭐473)](https://github.com/kdabir/has) - `has` helps you check presence of various command line tools and their versions on path
*   [how2 (⭐5.5k)](https://github.com/santinic/how2) - `how2` finds the simplest way to do something in a unix shell. It's like `man`, but you can query it in natural language.
*   [navi (⭐12k)](https://github.com/denisidoro/navi) - An interactive cheatsheet tool for the command-line
*   [hhighlighter (⭐411)](https://github.com/paoloantinori/hhighlighter) - Colorize words in a command output
*   [hr (⭐1.2k)](https://github.com/LuRsT/hr) - `<hr />` for your terminal
*   [hss (⭐305)](https://github.com/six-ddc/hss) - An interactive parallel ssh client featuring autocomplete and asynchronous execution
*   [hstr (⭐3.3k)](https://github.com/dvorka/hstr) - Bash History Suggest Box
*   [k (⭐1.7k)](https://github.com/supercrabtree/k) - k is a Zsh script to make directory listings more readable, adding Git status, fileweight colors and rotting dates
*   [k alias (⭐16)](https://github.com/lingtalfi/k) - get kool aliases (and more) working with a simple one-liner
*   [lf.sh (⭐37)](https://github.com/suewonjp/lf.sh) - Quickly search files with fewer typings and do many more (grepping, copying path to clipboard, etc)
*   [lowcharts (⭐108)](https://github.com/juan-leon/lowcharts) - Draw low-resolution graphs in terminal
*   [Lmod](https://lmod.readthedocs.io/en/latest/) - Lua-based Environment Modules that enhances Tcl-based modules while being backward compatible (compare to modules)
*   [loop (⭐604)](https://github.com/Miserlou/Loop) - Write and control complex loops with as one-liners
*   [marker (⭐1.9k)](https://github.com/pindexis/marker) - Bookmark your shell commands
*   [mackup (⭐12k)](https://github.com/lra/mackup/) - Keep your application settings in sync (OS X/Linux)
*   [mcfly (⭐4.5k)](https://github.com/cantino/mcfly) - Fly through your shell history. Great Scot!
*   [modules](http://modules.sourceforge.net/) - Classical Tcl-based Environment Modules managing the shell environment (compare to Lmod, direnv, and autoenv)
*   [nnn (⭐15k)](https://github.com/jarun/nnn) - File browser and disk usage analyzer with excellent desktop integration
*   [parallel](https://www.gnu.org/software/parallel/) - Build and execute shell command lines from standard input in parallel
*   [pass](https://www.passwordstore.org/) - Manage passwords from the command line with GPG encryption and optional git integration.
*   [pathpicker (⭐4.8k)](https://github.com/facebook/PathPicker) - Accepts inputs like grep, searches, git etc; allows selecting files from the result of the input, which you can then open or provide as argument to a command.
*   [pdd (⭐281)](https://github.com/jarun/pdd) - Tiny date, time diff calculator with timers
*   [percol (⭐3.1k)](https://github.com/mooz/percol) - Adds flavor of interactive filtering to the traditional pipe concept of UNIX shell
*   [q (⭐58)](https://github.com/cal2195/q) - Vim like macro registers for your Bash and Zsh Shell
*   [qfc (⭐548)](https://github.com/pindexis/qfc) - File-completion widget for Bash and Zsh
*   [resh (⭐753)](https://github.com/curusarn/resh) - Contextual shell history for Zsh and Bash
*   [rg (⭐34k)](https://github.com/BurntSushi/ripgrep) - ripgrep is a line oriented search tool that combines the usability of The Silver Searcher with the raw speed of GNU grep
*   [screen](https://www.gnu.org/software/screen/) - GNU terminal multiplexer
*   [shell-history (⭐99)](https://github.com/pawamoy/shell-history) - Visualize your shell usage with Highcharts
*   [SHML (⭐420)](https://github.com/odb/shml) - Style framework for the terminal (Shell Markup Language)
*   [slugify (⭐280)](https://github.com/benlinton/slugify) - Command that converts filenames and directories to a web friendly format
*   [sman (⭐275)](https://github.com/tokozedg/sman) - :bug: A command-line snippet manager
*   [spark (⭐5.9k)](https://github.com/holman/spark) - ▁▂▃▅▂▇ in your shell
*   [spark.fish (⭐280)](https://github.com/jorgebucaran/spark.fish) - ▁▂▃▅ Sparkline Generator
*   [sheet (⭐245)](https://github.com/oscardelben/sheet) -  Text snippets for the command line
*   [spot (⭐896)](https://github.com/rauchg/spot) - Tiny file search utility

<!---->

*   [snips (⭐63)](https://github.com/srijanshetty/snips) - Command line tool to manage snippets of code.

<!---->

*   [sqlline (⭐534)](https://github.com/julianhyde/sqlline) - Shell for issuing SQL to relational databases via JDBC (multiline, completion, highlighting, dialect support)
*   [sshfs (⭐993)](https://github.com/osxfuse/sshfs) - A tool for mounting remote file systems over SSH
*   [sudocabulary (⭐147)](https://github.com/badarsh2/Sudocabulary) - Learn English Vocabulary from your terminal
*   [surfraw](https://gitlab.com/surfraw/Surfraw) - browse specific site and search the web from your terminal without browser.
*   [task-manager (⭐11)](https://github.com/lingtalfi/task-manager) - Execute all your scripts with just two or three keystrokes.
*   [td-cli (⭐152)](https://github.com/darrikonn/td-cli) - A todo command line manager to organize and manage your todos across multiple projects.
*   [thefuck (⭐74k)](https://github.com/nvbn/thefuck) - Fix common shell mistakes by using an easy to remember command
*   [tldr (⭐663)](https://github.com/raylee/tldr-sh-client) - A fully-functional bash client for tldr, simplified and community-driven man pages
*   [tmux](https://tmux.github.io/) - Amazing terminal multiplexer
*   [undollar (⭐111)](https://github.com/xtyrrell/undollar) - undollar bites the dollar sign off the tip of the command you just pasted into your terminal
*   [usql (⭐7.6k)](https://github.com/xo/usql) - Universal command-line interface for SQL databases.
*   [v (⭐423)](https://github.com/rupa/v) - z for vim.
*   [wemux (⭐3.5k)](https://github.com/zolrath/wemux) - Multi-User Tmux Made Easy
*   [xiki](https://xiki.org) - Makes the shell console more friendly and powerful
*   [xplr (⭐2.4k)](https://github.com/sayanarijit/xplr) -  A hackable, minimal, fast TUI file explorer
*   [xsv (⭐8.7k)](https://github.com/BurntSushi/xsv) - a fast CSV command line toolkit written in Rust
*   [xxh (⭐3.9k)](https://github.com/xxh/xxh) - Bring your favorite shell wherever you go through the SSH.

### Directory Navigation

*   [aliasme (⭐103)](https://github.com/Jintin/aliasme) - alias helper to change directory quickly
*   [autojump (⭐14k)](https://github.com/wting/autojump) - A cd command that learns - easily navigate directories from the command line
*   [bashmarks (⭐1.8k)](https://github.com/huyng/bashmarks) - Directory bookmarks for the shell
*   [bd (⭐885)](https://github.com/vigneshwaranr/bd) - Quickly go back to a parent directory
*   [commacd (⭐334)](https://github.com/shyiko/commacd) - A faster way to move around in Bash
*   [enhancd (⭐2.2k)](https://github.com/b4b4r07/enhancd) - :rocket: A next-generation cd command with an interactive filter
*   [goto (⭐813)](https://github.com/iridakos/goto) - A shell utility for navigation to aliased directories supporting auto-completion
*   [jump (⭐1.4k)](https://github.com/gsamokovarov/jump) - Jump helps you navigate your file system faster by learning your habits.
*   [lazy-cd (⭐20)](https://github.com/pedramamini/lazy-cd) - Simple bash commands for bookmarked navigation of the file system, complete with bash-completion.
*   [up (⭐143)](https://github.com/shannonmoeller/up) - Ascend directories by name or count; for bash, zsh, and fish.
*   [z (⭐15k)](https://github.com/rupa/z) - z is the new j, yo
*   [z.lua (⭐2.4k)](https://github.com/skywind3000/z.lua) - A new cd command that helps you navigate faster by learning your habits
*   [zoxide (⭐8k)](https://github.com/ajeetdsouza/zoxide) - A faster way to navigate your filesystem, written in Rust
*   [zpyi (⭐97)](https://github.com/sakshamsharma/zpyi) - Python in Zsh - Easy python scripting in shell

## Customization

*Custom prompts, color themes, etc.*

*   [base16-builder (⭐401)](https://github.com/base16-builder/base16-builder) - Base16-Builder
*   [bash-full-of-colors (⭐153)](https://github.com/slomkowski/bash-full-of-colors) - Powerful prompt with screen, tmux, git support and many more
*   [bash-git-prompt (⭐6.3k)](https://github.com/magicmonty/bash-git-prompt) - An informative and fancy Bash prompt for Git users
*   [bash-powerline (⭐839)](https://github.com/riobard/bash-powerline) - Powerline-style Bash prompt in pure Bash script
*   [bashstrap (⭐1.6k)](https://github.com/barryclark/bashstrap) - A quick way to spruce up OSX terminal
*   [bullet-train-oh-my-zsh-theme (⭐2.7k)](https://github.com/caiogondim/bullet-train.zsh) - :bullettrain\_side: An oh-my-zsh shell theme based on the Powerline Vim plugin
*   [emojify (⭐1.5k)](https://github.com/mrowa44/emojify) Emoji on the command line :scream:
*   [flatui-terminal-theme](https://dribbble.com/shots/1021755-Flat-UI-Terminal-Theme) - Nicer colors for terminal
*   [geometry (⭐850)](https://github.com/geometry-zsh/geometry) - A minimal ZSH theme where any function can be added to the left prompt or (async) right prompt on the fly.
*   [git-prompt (⭐324)](https://github.com/lvv/git-prompt) - Bash prompt with Git, SVN and HG modules
*   [gittify (⭐60)](https://github.com/momeni/gittify) - A colorful Bash prompt + customized Git aliases
*   [Gogh - Color Scheme (⭐7.3k)](https://github.com/Mayccoll/Gogh) - Color Scheme for Gnome Terminal
*   [liquidprompt (⭐4.2k)](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt for Bash & Zsh
*   [mysql-colorize (⭐91)](https://github.com/zpm-zsh/mysql-colorize) -  Colorization for mysql comand-line client
*   [oh-my-git (⭐3.6k)](https://github.com/arialdomartini/oh-my-git) - An opinionated git prompt for bash and zsh
*   [oh-my-posh](https://ohmyposh.dev) - Prompt theme engine for any shell and platform written in go.
*   [polyglot (⭐144)](https://github.com/agkozak/polyglot) - An informative Git prompt that works in bash, zsh, ksh, mksh, pdksh, dash, and busybox sh
*   [powerlevel10k (⭐32k)](https://github.com/romkatv/powerlevel10k) - Super flexible awesome powerline ZSH theme
*   [sexy-bash-prompt (⭐1.1k)](https://github.com/twolfson/sexy-bash-prompt) - Bash prompt with colors, Git statuses, and Git branches
*   [starship](https://starship.rs/) - Fast, customisable, cross-shell prompt written in rust
*   [synth-shell (⭐555)](https://github.com/andresgongora/synth-shell) - Greeter with a customizable status report and a fancy bash prompt

## For Developers

*Command-line development, version control, and deployment.*

*   [ack](https://beyondgrep.com/) - A grep-like search tool optimized for source code.
*   [add-gitignore (⭐549)](https://github.com/TejasQ/add-gitignore) - Interactive CLI that generates a .gitignore for your project based on your needs.
*   [bcal (⭐565)](https://github.com/jarun/bcal) - Byte CALculator for storage conversions and calculations
*   [bitwise (⭐468)](https://github.com/mellowcandle/bitwise) - Terminal based interactive bit manipulator in curses.
*   [bocker (⭐10k)](https://github.com/p8952/bocker) - Docker implemented in 100 lines of bash
*   [cloc (⭐15k)](https://github.com/AlDanial/cloc) - Count Lines of Code
*   [doclt (⭐43)](https://github.com/omgimanerd/doclt) - A command line interface to Digital Ocean
*   [dokku (⭐24k)](https://github.com/dokku/dokku) - Docker powered mini-Heroku. The smallest PaaS implementation you've ever seen.
*   [forgit (⭐3.5k)](https://github.com/wfxr/forgit) - Utility tool for `git` taking advantage of fuzzy finder fzf.
*   [git-extra-commands (⭐816)](https://github.com/unixorn/git-extra-commands) - Many Git extra utilities. Churn, cut-branch, improved-merge and many more.
*   [git-extras (⭐16k)](https://github.com/tj/git-extras) - Git utilities -- repo summary, repl, changelog population, author commit percentages and more
*   [git-open (⭐3k)](https://github.com/paulirish/git-open) - Type `git open` to open the GitHub page or website for a repository in your browser
*   [git-quick-stats (⭐5.5k)](https://github.com/arzzen/git-quick-stats) - Git quick statistics is a simple and efficient way to access various statistics in git repository.
*   [git-semver (⭐350)](https://github.com/markchalloner/git-semver) - Git plugin for easing semantic versioning and changelog validation
*   [git-sh (⭐725)](https://github.com/rtomayko/git-sh) - A customized Bash environment suitable for Git work
*   [gita (⭐1.2k)](https://github.com/nosarthur/gita) - A command-line tool to manage multiple git repos.
*   [hub (⭐22k)](https://github.com/github/hub) - hub helps you win at git.
*   [just (⭐7.4k)](https://github.com/casey/just) - Task runner for saving and running project-specific commands.
*   [licins (⭐19)](https://github.com/dogoncouch/licins) - Insert commented software licenses into source code.
*   [mkdkr (⭐303)](https://github.com/rosineygp/mkdkr) - Makefile + Docker = CI Pipeline
*   [mr](https://myrepos.branchable.com) - Multiple Repository management tool
*   [overcommit (⭐3.7k)](https://github.com/sds/overcommit) - A fully configurable and extendable Git hook manager
*   [pre-commit](https://pre-commit.com) - A framework for managing and maintaining multi-language pre-commit hooks
*   [rebound (⭐3.9k)](https://github.com/shobrook/rebound) - Instantly browse Stack Overflow results in your terminal when you get a compiler error
*   [repren (⭐308)](https://github.com/jlevy/repren) - Command-line search-and-replace and file-renaming swiss army knife
*   [slap (⭐6.1k)](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor that runs on Node.js
*   [shipit (⭐558)](https://github.com/sapegin/shipit) - Minimalistic SSH deployment
*   [starring (⭐154)](https://github.com/ritz078/starring) - Automatically star the npm-packages that you are using on GitHub.
*   [tag (⭐584)](https://github.com/aykamko/tag) - Instantly jump to your ag matches.
*   [wipe-modules (⭐325)](https://github.com/bntzio/wipe-modules) - A little agent that removes the node\_modules folder of non-active projects

## System Utilities

*OS-related tools, including system administration, system debugging, and file and process management.*

*   [atop](https://www.atoptool.nl) - ASCII full-screen performance monitor that is capable of reporting the activity of all processes
*   [bat (⭐38k)](https://github.com/sharkdp/bat) - A `cat` clone with wings
*   [bmon (⭐967)](https://github.com/tgraf/bmon) - Real-time network bandwidth monitor and rate estimator with human-friendly visual output
*   [btop (⭐9.2k)](https://github.com/aristocratos/btop) - Linux/OSX/FreeBSD resource monitor
*   [catcli (⭐158)](https://github.com/deadc0de6/catcli) -  The command line catalog tool for your offline data
*   [ccat (⭐3k)](https://github.com/owenthereal/ccat) - ccat is the colorizing cat. It works similar to cat but displays content with syntax highlighting.
*   [exa (⭐20k)](https://github.com/ogham/exa) - A modern version of `ls`.
*   [progress (⭐5.8k)](https://github.com/Xfennec/progress) - Linux tool to show progress for `cp`, `rm`, `dd`, and more...
*   [stronghold (⭐972)](https://github.com/alichtman/stronghold) - Easily configure MacOS security settings from the terminal.
*   [glances (⭐22k)](https://github.com/nicolargo/glances) - Glances an Eye on your system
*   [goaccess (⭐15k)](https://github.com/allinurl/goaccess) - GoAccess is a real-time web log analyzer and interactive viewer that runs in a terminal in \*nix systems.
*   [hblock (⭐1.1k)](https://github.com/hectorm/hblock) - Hosts-file based adblocker
*   [histstat (⭐88)](https://github.com/vesche/histstat) - History for netstat
*   [htop (⭐5.7k)](https://github.com/hishamhm/htop) - A ncurses based interactive process viewer which aims to be a better `top`
*   [lnav](https://lnav.org) - An advanced log file viewer for the small-scale
*   [logdissect (⭐122)](https://github.com/dogoncouch/logdissect) - CLI utility and Python API for analyzing log files and other data.
*   [ls++ (⭐484)](https://github.com/trapd00r/ls--) - Colorized ls on steroids
*   [lsd (⭐8.6k)](https://github.com/Peltoche/lsd) - LSDeluxe, rewrite of GNU ls with lot of added features like colors, icons, tree-view and more formatting options.
*   [lsp (⭐511)](https://github.com/dborzov/lsp) - An improved `ls`, with file descriptions in plain language and intelligent file grouping
*   [maza (⭐1.6k)](https://github.com/tanrax/maza-ad-blocking) - Local ad blocker. Like Pi-hole but local and using your operating system.
*   [mtr (⭐2.1k)](https://github.com/traviscross/mtr) - The functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool.
*   [ncdu](https://dev.yorhel.nl/ncdu) - NCurses Disk Usage
*   [nmtui (⭐257)](https://github.com/NetworkManager/NetworkManager) - Text User Interface for controlling NetworkManager
*   [powertop (⭐674)](https://github.com/fenrus75/powertop) - Battery/Power usage and device stats monitoring command-line tool, with tune-up options.
*   [prettyping (⭐1.1k)](https://github.com/denilsonsa/prettyping) - Making the output of `ping` prettier, more colorful, more compact, and easier to read.
*   [procdog (⭐73)](https://github.com/jlevy/procdog) - Lightweight command-line control of long-lived processes like servers
*   [quick-secure (⭐400)](https://github.com/marshyski/quick-secure) - Quickly secure and harden UNIX/Linux systems
*   [rng (⭐27)](https://github.com/nickolasburr/rng) - Copy range of lines from file or stdin to stdout.
*   [tiptop (⭐1.3k)](https://github.com/nschloe/tiptop) - Graphical command-line system monitor.
*   [wifi-wand (⭐59)](https://github.com/keithrbennett/wifiwand) - a Ruby command line application for managing WiFi on MacOS (install by `gem install wifi-wand`)
*   [xiringuito (⭐1k)](https://github.com/ivanilves/xiringuito) - SSH-based "VPN for poors"

## Downloading and Serving

*Self-hosted, lightweight servers and networking tools written in shell scripts.*

*   [aria2 (⭐28k)](https://github.com/aria2/aria2) - aria2 is a lightweight multi-protocol & multi-source, cross platform download utility operated in command-line. It supports HTTP/HTTPS, FTP, BitTorrent and Metalink
*   [balls (⭐838)](https://github.com/jneen/balls) - Bash on Balls
*   [bashttpd (⭐1.4k)](https://github.com/avleen/bashttpd) - A web server written in Bash
*   [bashhub-server (⭐249)](https://github.com/nicksherron/bashhub-server) - Private cloud shell history. Open source server for bashhub
*   [bitpocket (⭐1k)](https://github.com/sickill/bitpocket) - "DIY Dropbox" or "2-way directory (r)sync with proper deletion"
*   [Dropbox-Uploader (⭐6.4k)](https://github.com/andreafabrizi/Dropbox-Uploader) - Dropbox Uploader is a Bash script which can be used to upload, download, list or delete files from Dropbox
*   [httpie (⭐24k)](https://github.com/httpie/httpie) - HTTPie is a command line HTTP client, a user-friendly cURL replacement
*   [HTTPLab (⭐3.8k)](https://github.com/gchaincl/httplab) - The interactive web server, let you inspect HTTP requests and forge responses.
*   [ngincat (⭐164)](https://github.com/jaburns/ngincat) - Tiny Bash HTTP server using netcat
*   [resty (⭐2.6k)](https://github.com/micha/resty) - Little command line REST client that you can use in pipelines
*   [shell2http (⭐1k)](https://github.com/msoap/shell2http) - HTTP-server to execute shell commands. Designed for development, prototyping or remote control
*   [vesper (⭐193)](https://github.com/chris-rock/vesper) - 🍸Vesper is a HTTP framework for Bash/Unix Shell
*   [xh (⭐3.2k)](https://github.com/ducaale/xh) - Friendly and fast tool for sending HTTP requests
*   [youtube-dl](https://yt-dl.org/) - Small command-line program to download videos from YouTube.com and other video sites

## Multimedia and File Formats

*Tools for handling video and audio files.*

*   [adb-export (⭐96)](https://github.com/sromku/adb-export) - Export Android content providers to CSV format
*   [Android-Kitchen (⭐958)](https://github.com/dsixda/Android-Kitchen) - A text-based kitchen for Android ROM customization. Uses shell scripts and works with Cygwin/OS X/Linux
*   [Beets (⭐11k)](https://github.com/beetbox/beets) - Music library manager and MusicBrainz tagger
*   [cmus (⭐4.7k)](https://github.com/cmus/cmus) - Cross-platform cli audio player.
*   [dasel (⭐3.7k)](https://github.com/tomwright/dasel) - Query and update data structures using selectors from the command line. Comparable to [jq (⭐23k)](https://github.com/stedolan/jq) / [yq (⭐2k)](https://github.com/kislyuk/yq) but supports JSON, YAML, TOML and XML with zero runtime dependencies.
*   [fx (⭐15k)](https://github.com/antonmedv/fx) - Command-line JSON processing tool by anononymus JavaScript functions
*   [gifgen (⭐492)](https://github.com/lukechilds/gifgen) - Simple high quality GIF encoding
*   [image-scraper (⭐707)](https://github.com/sananth12/ImageScraper) - A cool command line image scraper with a lot of features.
*   [imgp (⭐901)](https://github.com/jarun/imgp) - Blazing fast batch image resizer and rotator
*   [jo (⭐4.3k)](https://github.com/jpmens/jo) - A small utility to create JSON objects from command-line arguments.
*   [jq (⭐23k)](https://github.com/stedolan/jq) - Sed for json data. You can use it to slice and filter and map and transform structured data
*   [korkut (⭐351)](https://github.com/oguzhaninan/korkut) - Quick and simple image processing at the command line.
*   [mpv](https://mpv.io/) - Lets you play most audio and video formats (using ASCII characters) in the shell as well as in a GUI.
*   [nehm (⭐85)](https://github.com/bogem/nehm) - Console tool, which downloads, sets IDv3 tags and adds to your iTunes (if you use it) your SoundCloud likes in convenient way
*   [PiCAST (⭐1.7k)](https://github.com/lanceseidman/PiCAST) - PiCAST turns your $35 Raspberry Pi in to a Chromecast like Device
*   [sejda (⭐410)](https://github.com/torakiki/sejda/) - Command line manipulation of PDF documents (split, merge, rotate, convert to jpg, extract text, etc)
*   [visidata (⭐6.1k)](https://github.com/saulpw/visidata) - A terminal spreadsheet multitool for exploring and arranging data (csv/json/xml/xls/yaml/etc)
*   [xidel (⭐511)](https://github.com/benibela/xidel/) - Cli tool to filter, map and create HTML/XML/JSON data with (Turing-complete) XPath and XQuery.
*   [xmlstarlet](http://xmlstar.sourceforge.net/) - Old but powerful tool for command-line XML formatting, filtering, and manipulation.
*   [yq (⭐6.6k)](https://github.com/mikefarah/yq) - yq is a portable command-line YAML processor

## Applications

*Command line-based applications or command line access to existing services.*

*   [ansiweather (⭐1.7k)](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols
*   [awless (⭐4.9k)](https://github.com/wallix/awless) - A powerful, innovative and small surface CLI to manage AWS.
*   [bashblog (⭐1.4k)](https://github.com/cfenollosa/bashblog) - A Bash script that handles blog posting
*   [carbon-now-cli (⭐5.4k)](https://github.com/mixn/carbon-now-cli) - 🎨 Beautiful images of your code — from right inside your terminal.
*   [choosealicense-cli (⭐65)](https://github.com/lord63/choosealicense-cli) - Choose an OSS license from the comfort of your terminal
*   [cointop (⭐3.4k)](https://github.com/miguelmota/cointop) - The fastest and most interactive terminal based UI application for tracking cryptocurrencies
*   [dstask (⭐657)](https://github.com/naggie/dstask) - Single binary terminal-based TODO manager with git-based sync + markdown notes per task
*   [editly (⭐3.7k)](https://github.com/mifi/editly) - Command line video editor
*   [facebook-cli (⭐372)](https://github.com/specious/facebook-cli) - Facebook command line tool
*   [fanyi (⭐1.2k)](https://github.com/afc163/fanyi) - Translate English to Chinese in terminal
*   [gcalcli (⭐2.9k)](https://github.com/insanum/gcalcli) - Google Calendar command line interface
*   [geeknote (⭐2.1k)](https://github.com/VitaliyRodnenko/geeknote) - Command line evernote client
*   [haxor-news (⭐3.8k)](https://github.com/donnemartin/haxor-news) - Browse Hacker News like a haxor
*   [hn-cli (⭐455)](https://github.com/rafaelrinaldi/hn-cli) - Browse Hacker News from the comfort of your Terminal
*   [iponmap (⭐283)](https://github.com/nogizhopaboroda/iponmap) - Draw point on world map using ip address
*   [isitup (⭐53)](https://github.com/lord63/isitup) - Check whether a website is up or down
*   [jrnl (⭐5.6k)](https://github.com/jrnl-org/jrnl) - A simple command line journal application that stores your journal in a plain text file
*   [kanban.bash (⭐756)](https://github.com/coderofsalvation/kanban.bash) - commandline asciii kanban board for minimalist productivity bash hackers (csv-based)
*   [ledger (⭐4.4k)](https://github.com/ledger/ledger) - Command line accounting
*   [licen (⭐33)](https://github.com/lord63/licen) - Generate your license. Yet another lice, but implement with Jinja2 and docopt
*   [md2png (⭐24)](https://github.com/weaming/md2png) - Convert markdown to PNG image
*   [moviemon (⭐183)](https://github.com/iCHAIT/moviemon) - Everything about your movies within the command line.
*   [nomino (⭐434)](https://github.com/yaa110/nomino) - Batch rename utility using regex, sort and map file options.
*   [pcalc (⭐170)](https://github.com/alt-romes/programmer-calculator) - Calculator made for programmers working with multiple number representations, sizes, and overall close to the bits.
*   [pockyt (⭐471)](https://github.com/achembarpu/pockyt) - Read, Manage, and Automate your [Pocket](https://getpocket.com) collection.
*   [pushblast (⭐96)](https://github.com/alebcay/pushblast) - Get PushBullet notifications when a shell program exits
*   [pushbullet-bash (⭐227)](https://github.com/Red5d/pushbullet-bash) - Bash interface to the PushBullet API
*   [ranger (⭐12k)](https://github.com/ranger/ranger) - A console file manager with VI key bindings.
*   [Reddit Terminal Viewer (⭐4.6k)](https://github.com/michael-lazar/rtv) - Browse Reddit from your terminal
*   [SAWS (⭐5k)](https://github.com/donnemartin/saws) - A Supercharged AWS CLI
*   [taskbook (⭐8.6k)](https://github.com/klaussinani/taskbook) - Tasks, boards & notes for the command-line habitat
*   [taskwarrior](https://taskwarrior.org/) - A command-line TODO list manager
*   [terjira (⭐801)](https://github.com/keepcosmos/terjira) - Command line power tool for Jira
*   [ticker (⭐4.4k)](https://github.com/achannarasappa/ticker) — Terminal stock ticker with live updates and position tracking
*   [transfer.sh](https://transfer.sh/) — Quickly upload and share files from your shell
*   [vl (⭐17)](https://github.com/ellisonleao/vl) - URL link checker on text documents
*   [wego (⭐7.2k)](https://github.com/schachmat/wego) - Weather app for the terminal
*   [whales (⭐348)](https://github.com/Gueils/whales) - A tool to automatically dockerize your applications
*   [whereami (⭐151)](https://github.com/rafaelrinaldi/whereami) - Get your geolocation information from the CLI
*   [wttr.in (⭐20k)](https://github.com/chubin/wttr.in) - :partly\_sunny: The right way to check the weather (curl wttr.in)

## Games

*All work and no play is a cruddy way to spend your day.*

*   [bash2048 (⭐849)](https://github.com/mydzor/bash2048) - Bash implementation of 2048 game
*   [minesweeper (⭐48)](https://github.com/feherke/Bash-script/tree/master/minesweeper) - Bash implementation of minesweeper
*   [nudoku (⭐256)](https://github.com/jubalh/nudoku) - ncurses based sudoku game written in C
*   [piu-piu (⭐679)](https://github.com/vaniacer/piu-piu-SH) - Horizontal scroller game in bash with multiplayer mode!
*   [sedtris (⭐441)](https://github.com/uuner/sedtris) - Tetris in sed
*   [sed-scripts (⭐40)](https://github.com/aureliojargas/sed-scripts) - Arkanoid and Sokoban written using sed
*   [SHTAP](https://notimetoplay.org/engines/shtap/) - Reusable text adventure engine for Bash 4
*   [tty-solitaire (⭐229)](https://github.com/mpereira/tty-solitaire) - Play solitaire in your terminal!

## Shell Package Management

*Tools for managing multiple shell configurations. For zsh-specific tools, see the Zsh section.*

*   [bash-it (⭐13k)](https://github.com/Bash-it/bash-it) - A community Bash framework
*   [basher (⭐971)](https://github.com/basherpm/basher) - A package manager for shell scripts
*   [bashing (⭐69)](https://github.com/xsc/bashing) - Smashing Bash into Pieces
*   [bpkg](https://www.bpkg.sh/) - JavaScript has npm, Ruby has Gems, Python has pip and now Shell has bpkg
*   [dotdrop (⭐1.4k)](https://github.com/deadc0de6/dotdrop) - Save your dotfiles once, deploy them everywhere
*   [dotfiler (⭐230)](https://github.com/svetlyak40wt/dotfiler) – Shell agnostic git based dotfiles package manager, written in Python.
*   [fresh (⭐1.1k)](https://github.com/freshshell/fresh) - Keep your dotfiles fresh
*   [homeshick (⭐1.9k)](https://github.com/andsens/homeshick) - Git dotfile synchronizer written in Bash
*   [shallow-backup (⭐968)](https://github.com/alichtman/shallow-backup) - Easily create lightweight documentation of installed packages, dotfiles, and more
*   [shundle (⭐78)](https://github.com/javier-lopez/shundle) - Plugin manager for shell scripts
*   [vcsh (⭐2k)](https://github.com/RichiH/vcsh) - Config manager based on Git
*   [yadm](https://yadm.io/) - Git-based dotfiles manager supporting encryption, alternates, and bootstrapping

## Shell Script Development

*Tools for writing, improving, or organizing Bash or other shell scripts*

*   [ansi (⭐438)](https://github.com/fidian/ansi) - ANSI escape codes in pure bash - change text color, position the cursor, much more
*   [assert.sh (⭐465)](https://github.com/lehmannro/assert.sh) - Bash unit testing framework
*   [bashew (⭐153)](https://github.com/pforret/bashew) - bash script creator - from small stand-alone script to complex projects with CI/CD and testing
*   [bashful (⭐567)](https://github.com/jmcantrell/bashful) - A collection of libraries to simplify writing Bash scripts
*   [Bashlets (⭐64)](https://github.com/reale/bashlets) - A modular extensible toolbox for Bash
*   [bashly](https://bashly.dannyb.co/) - Bash command line framework and CLI generator
*   [bashmanager (⭐85)](https://github.com/lingtalfi/bashmanager) - mini bash framework for creating command line tools
*   [bashwithnails (⭐26)](https://github.com/mindaugasbarysas/bashwithnails) - a Bash framework written just for fun with testing, dependency management & packaging
*   [bash-language-server (⭐1.4k)](https://github.com/bash-lsp/bash-language-server) - [LSP](https://microsoft.github.io/language-server-protocol/)-based Bash language server
*   [bash-modules (⭐94)](https://github.com/vlisivka/bash-modules) - functions for developing with [unofficial strict mode](http://redsymbol.net/articles/unofficial-bash-strict-mode/) enabled.
*   [bats (⭐3.5k)](https://github.com/bats-core/bats-core) - Bash Automated Testing System
*   [composure (⭐302)](https://github.com/erichs/composure) - Compose, document, version and organize your shell functions
*   [crash (⭐52)](https://github.com/molovo/crash) - Proper error handling, exceptions and try/catch for ZSH
*   [critic.sh (⭐449)](https://github.com/Checksum/critic.sh) - Dead simple testing framework for Bash with coverage reporting
*   [dispatch (⭐88)](https://github.com/Mosai/workshop/blob/master/doc/dispatch.md) - A command line argument parser in 50 lines of portable shell script.
*   [esh (⭐161)](https://github.com/jirutka/esh) - A simple templating engine based on shell, implemented in \~290 lines of POSIX shell and awk.
*   [Fishtape (⭐310)](https://github.com/jorgebucaran/fishtape) - TAP producer and test harness for fish
*   [getoptions (⭐238)](https://github.com/ko1nksm/getoptions) - An elegant option parser for shell scripts (sh, bash and all POSIX shells)
*   [getopts.fish (⭐196)](https://github.com/jorgebucaran/getopts.fish) - CLI parser for fish
*   [is.sh (⭐147)](https://github.com/qzb/is.sh) - An alternative for builtin test command, it will make your "if" statements pretty
*   [lumberjack (⭐35)](https://github.com/molovo/lumberjack) - A logging interface for shell scripts
*   [mo (⭐463)](https://github.com/tests-always-included/mo) - Mustache templates in pure bash
*   [optparse (⭐142)](https://github.com/nk412/optparse) - A BASH wrapper for getopts, for simple command line arguments.
*   [rerun (⭐431)](https://github.com/rerun/rerun) - A modular shell automation framework to organize your keeper scripts
*   [revolver (⭐128)](https://github.com/molovo/revolver) - A reusable progress spinner for shell scripts
*   [phases (⭐12)](https://github.com/sorokine/phases) - Minimally invasive bash preprocessor, select sections of your script to run
*   [powscript (⭐120)](https://github.com/coderofsalvation/powscript) - bash transpiler written in bash (coffeescript for bash)
*   [semver\_bash (⭐226)](https://github.com/cloudflare/semver_bash) - Semantic Versioning in Bash
*   [sh-semver (⭐29)](https://github.com/qzb/sh-semver) - Semver tool for bash - finds versions matching to specified rules
*   [shellcheck (⭐30k)](https://github.com/koalaman/shellcheck) - Static analysis tool for shell scripts
*   [shellfire (⭐1.2k)](https://github.com/shellfire-dev/shellfire) -  A repository of namespaced, composable shell (bash, sh and dash) function libraries
*   [shellspec (⭐772)](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for dash, bash, ksh, zsh and all POSIX shells
*   [shfmt (⭐5.1k)](https://github.com/mvdan/sh) - A shell parser, formatter, and interpreter with bash support; includes shfmt
*   [shpec (⭐366)](https://github.com/rylnd/shpec) - A shell testing framework
*   [shutit](https://ianmiell.github.io/shutit/) - Automation framework based on bash and pexpect
*   [sub (⭐1.7k)](https://github.com/basecamp/sub) - A delicious way to organize programs
*   [ts (⭐52)](https://github.com/thinkerbot/ts) - A shell test script
*   [urchin (⭐208)](https://github.com/tlevine/urchin) - An idiomatic shell testing framework that uses only shell commands
*   [shunit2 (⭐1.4k)](https://github.com/kward/shunit2) - A unit test framework for Bash scripts with a flavour of JUnit/PyUnit.
*   [rebash (⭐65)](https://github.com/jandob/rebash) - Scripting library/framework. Features: imports, exceptions, doc-tests ...
*   [zunit (⭐173)](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH

# Guides

*   [Bash Official Reference Manual](https://www.gnu.org/savannah-checkouts/gnu/bash/manual/bash.html)
*   [Bash Hackers Wiki](https://wiki.bash-hackers.org/)
*   [Greg Wooledge's (aka "greycat") wiki](https://mywiki.wooledge.org).
    Specifically [Bash Guide](https://mywiki.wooledge.org/BashGuide), [Bash FAQ](https://mywiki.wooledge.org/BashFAQ) and [Bash Pitfalls](https://mywiki.wooledge.org/BashPitfalls)
*   [Google's Shell Style Guide](https://google.github.io/styleguide/shell.xml)
*   [The Linux Documentation Project: Bash Programming - Intro/How-to](https://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html)
*   [The Linux Documentation Project: Advanced Bash Scripting Guide](https://tldp.org/LDP/abs/html/)
*   [WikiBooks: Bash Shell Scripting](https://en.wikibooks.org/wiki/Bash_Shell_Scripting)
*   [Use the Unofficial Bash Strict Mode (Unless You Looove Debugging)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
*   [The Art of Command Line (⭐112k)](https://github.com/jlevy/the-art-of-command-line)
*   [Learn Enough Command Line to Be Dangerous](https://www.learnenough.com/command-line-tutorial/basics)
*   [A guide to learn bash (⭐11k)](https://github.com/Idnan/bash-guide)
*   [Shell Field Guide](https://raimonster.com/scripting-field-guide/)

# Other Awesome Lists

Other amazingly awesome lists can be found in [awesome-awesome (⭐2.2k)](https://github.com/emijrp/awesome-awesome) and [awesome-awesomeness (⭐29k)](https://github.com/bayandin/awesome-awesomeness).

### See also

*   [awesome-cli-apps (⭐10k)](https://github.com/agarrharr/awesome-cli-apps)
*   [awesome-fish][awesome-fish]
*   [awesome-zsh][awesome-zsh]
*   [terminals-are-sexy (⭐11k)](https://github.com/k4m4/terminals-are-sexy)

[awesome-badge]: https://raw.githubusercontent.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg

[awesome-fish]: https://github.com/jorgebucaran/awsm.fish

[awesome-link]: https://github.com/sindresorhus/awesome

[awesome-zsh]: https://github.com/unixorn/awesome-zsh-plugins

