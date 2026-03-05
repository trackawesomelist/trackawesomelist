# Awesome Tmux Overview

A list of awesome resources for tmux

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/rothgar/awesome-tmux/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 rothgar/awesome-tmux](https://github.com/rothgar/awesome-tmux) · ⭐ 9.6K · 🏷️ Development Environment

[ [Daily](/content/rothgar/awesome-tmux/README.md) / [Weekly](/content/rothgar/awesome-tmux/week/README.md) / Overview ]

---

![](https://github.com/rothgar/awesome-tmux/raw/main/./img/banner.png)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

List of helpful tmux links for various tutorials, plugins, and configuration settings.

## Table of Contents

*   [Tutorials](#tutorials)
*   [Cheat sheets](#cheatsheets)
*   [Configuration](#configuration)
*   [Tools and session management](#tools)
*   [Themes](#themes)
*   [Status Bar](#status-bar)
*   [Plugins](#plugins)
*   [Books](#books)
*   [Miscellaneous](#miscellaneous)

## Tutorials

*   [Automatically start tmux on SSH](http://marklodato.github.io/2013/10/31/autostart-tmux-on-ssh.html)
*   [Tmux crash course](https://thoughtbot.com/blog/a-tmux-crash-course)
*   [Tmux and Vim together](https://smartbear.com/blog/tmux-and-vim/)

## <a name="cheatsheets"></a>Cheat Sheets

*   [tmux-cheatsheet.markdown](https://gist.github.com/MohamedAlaa/2961058)
*   [tmuxcheatsheet.com](https://tmuxcheatsheet.com/)

## Configuration

*   [Oh My Tmux! (⭐24k)](https://github.com/gpakosz/.tmux) Powerline-like theme, vim bindings, SSH aware, improved maximize pane, ...
*   [Example tmux config (⭐1.8k)](https://github.com/tony/tmux-config) :green\_book: Example tmux configuration - screen + vim key-bindings, system stat, cpu load bar
*   [Guide to customizing tmux.conf](https://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/)
*   [mooks (⭐15)](https://github.com/TomhetArkitektur/mooks) A minimal tmux configuration framework designed for well-structured modular setups
*   [practical tmux](https://mutelight.org/practical-tmux)
*   [tmux-extra](https://github.com/brandur/tmux-extra) Configuration and scripts for sane Tmux default behavior
*   [tmux-keybtest (⭐6)](https://github.com/jaclu/tmux-keybtest) Check what keys tmux can detect from the terminal being used.
*   [tmux yank to system clipboard](https://www.grailbox.com/2020/08/use-system-clipboard-for-vi-copy-mode-in-tmux-in-macos-and-linux/) A way to get the System Clipboard to work with tmux yank on a Mac via `pbcopy` and linux via `xclip`

## <a name="tools"></a>Tools and session management

*   [automux](https://github.com/sriramkandukuri/automux) Wrappers to tmux commands, useful for tmux based automation
*   [ccb (⭐1.3k)](https://github.com/bfly123/claude_code_bridge) A CLI tool to orchestrate multiple LLMs (Claude, Gemini, etc.) in tmux panes with cross-agent interaction
*   [disconnected (⭐20)](https://github.com/austinwilcox/disconnected) A session manager written in Deno with json as the config files
*   [dmux (⭐365)](https://github.com/zdcthomas/dmux) Configurable tmux workspace manager written in Rust
*   [harpoon (⭐68)](https://github.com/Chaitanyabsprip/tmux-harpoon) A tool to bookmark sessions and jump between them in a flash. Like ThePrimeagen/harpoon, but for tmux.
*   [laio](https://laio.sh) A simple, flexbox-inspired, layout & session manager for tmux written in Rust.
*   [libtmux (⭐1.1k)](https://github.com/tmux-python/libtmux) Python API for tmux
*   [moxide (⭐15)](https://github.com/dlurak/moxide) A tmux session manager with a modular config
*   [mynav (⭐228)](https://github.com/GianlucaP106/mynav) Workspace and session management TUI built on tmux
*   [powerline (⭐15k)](https://github.com/powerline/powerline) Statusline plugin for vim, and provides statuslines and prompts for several other applications including tmux
*   [tmux-powerline (⭐3.7k)](https://github.com/erikw/tmux-powerline) A hackable statusbar for tmux consisting of dynamic & beautiful looking segments, inspired by vim-powerline, written purely in bash.
*   [sesh (⭐1.8k)](https://github.com/joshmedeski/sesh) Smart session manager for the terminal
*   [smug (⭐848)](https://github.com/ivaaaan/smug) A session manager for tmux written in Go
*   [sessionx (⭐1.2k)](https://github.com/omerxx/tmux-sessionx) A Tmux session manager, with preview, fuzzy finding, and MORE
*   [t (⭐348)](https://github.com/joshmedeski/t-smart-tmux-session-manager) The smart tmux session manager
*   [tat (⭐40)](https://github.com/ryandotsmith/tat) Tab completion for tmux sessions
*   [teamocil (⭐2.4k)](https://github.com/remi/teamocil) A simple tool used to automatically create windows and panes in tmux with YAML files
*   [tmex (⭐118)](https://github.com/evnp/tmex) A minimalist tmux layout manager
*   [tmux-canvas (⭐7)](https://github.com/juancruzfl/tmux-canvas) Create, save, and automate session layouts using executable shell script blueprints.
*   [tmux-cookie-cutter](https://github.com/AranBorkum/tmux-cookie-cutter) A YAML based session builder, configuring windows, panes and environments automatically
*   [tmux-cssh](https://github.com/zinic/tmux-cssh) Tmux with a "ClusterSSH"-like behavior
*   [tmux-conf (⭐5)](https://github.com/jaclu/tmux-conf) Meant for users running tmux on multiple hosts, not always running the same version. Generates tmux config files using version checks
*   [tmux-grip](https://github.com/leohenon/tmux-grip) Pin tmux sessions to fixed numbered slots with direct key jumps and a popup manager
*   [tmux-lazy-restore (⭐37)](https://github.com/bcampolo/tmux-lazy-restore) A session manager that allows sessions to be lazily restored in order to save memory and CPU cycles.
*   [tmux-nav-master (⭐7)](https://github.com/TheSast/tmux-nav-master) Easy cross-navigation between tmux and other terminal applications.
*   [tmux-poltergeist (⭐2)](https://github.com/dianoga-theory/tmux-poltergeist) Clipboard-like popup for injecting up to 10 text buffers
*   [tmux-powerkit (⭐485)](https://github.com/fabioluciano/tmux-powerkit) A tmux framework to create and distribute plugins and themes - Already have 36+ plugins, and 2 themes.
*   [tmux-project](https://github.com/sei40kr/tmux-project) Search projects and open them in a new session
*   [tmux-suspend (⭐158)](https://github.com/MunifTanjim/tmux-suspend) Suspend local session for painlessly working with nested remote session.
*   [tmux-task-monitor (⭐30)](https://github.com/YlanAllouche/tmux-task-monitor) a htop-like resource monitor popup that only shows the processes linked to the current session
*   [tmux-tea (⭐77)](https://github.com/2KAbhishek/tmux-tea) Session manager with previews, integrations with tmuxinator, fzf, neovim and more.
*   [tmux-tpad](https://github.com/Subbeh/tmux-tpad) A popup window session manager.
*   [tmux-up](https://github.com/jamesottaway/tmux-up) Bootstrap new `tmux` sessions without complex tools, DSLs, or dependencies
*   [tmuxake](https://github.com/nkh/tmuxake) A side-pane manager for tmux
*   [tmuxifier (⭐1.5k)](https://github.com/jimeh/tmuxifier) Tmuxify your Tmux. Powerful session, window & pane management for Tmux.
*   [tmuxinator (⭐13k)](https://github.com/tmuxinator/tmuxinator) Manage complex tmux sessions easily
*   [tmuxp (⭐4.4k)](https://github.com/tmux-python/tmuxp) :computer: tmux session manager and python library
*   [tmuxpair (⭐46)](https://github.com/goerz/tmuxpair) Command line script for setting up a temporary tmux session for pair programming
*   [tome (⭐155)](https://github.com/laktak/tome) 🔁 Playbooks for tmux & vim, replacing your shell history
*   [twm (⭐56)](https://github.com/vinnymeller/twm) A highly configurable workspace manager that is easy to extend with shell scripts, written in Rust
*   [vim-tmux-navigator (⭐6.1k)](https://github.com/christoomey/vim-tmux-navigator) Vim and tmux integration
*   [xpanes](https://github.com/greymd/tmux-xpanes) Awesome tmux-based terminal divider

## Themes

*   [amp (⭐1)](https://github.com/imdanielpiva/tmux-amp-theme) tmux theme based on the Amp Code website colors.
*   [catppuccin](https://github.com/catppuccin/tmux) Catppuccin `Latte`, `Frappe`, `Macchiato`, and `Mocha` themes for tmux.
*   [cole-tmux (⭐0)](https://github.com/thekylehuang/cole-tmux) Stationery-inspired minimal theme displayed in vintage earth tones
*   [dracula/tmux (⭐806)](https://github.com/dracula/tmux) 🧛🏻‍♂️ The official [dracula theme](https://draculatheme.com/) for tmux
*   [minimal-tmux-status (⭐255)](https://github.com/niksingh710/minimal-tmux-status/): Minimal theme with only required information in status bar and prefix indicator. (changes only status bar)
*   [nord tmux (⭐1.2k)](https://github.com/arcticicestudio/nord-tmux) An arctic, north-bluish clean and elegant tmux color theme.
*   [rose-pine](https://github.com/rose-pine/tmux) - Soho vibes for tmux
*   [tmux-base16-statusline (⭐28)](https://github.com/jatap/tmux-base16-statusline) Statusline based on [base16-shell](https://github.com/chriskempson/base16-shell)
*   [tmux-colors-solarized (⭐1.1k)](https://github.com/seebi/tmux-colors-solarized) A color theme for the tmux terminal multiplexer using Ethan Schoonover’s Solarized color scheme
*   [tmux-dark-notify (⭐86)](https://github.com/erikw/tmux-dark-notify) - Make tmux's theme follow macOS dark/light mode.
*   [tmux-gruvbox](https://github.com/egel/tmux-gruvbox) Light and dark tmux theme
*   [tmux-nova](https://github.com/o0th/tmux-nova) Fully customizable tmux theme
*   [tmux-power](https://github.com/wfxr/tmux-power) 8 powerline style themes for tmux, easily to expand.
*   [tmux-snazzy (⭐24)](https://github.com/ivnvxd/tmux-snazzy) Elegant tmux theme with bright colors
*   [tmux-themepack](https://github.com/jimeh/tmux-themepack) Various themes for tmux
*   [tokyo-night-tmux (⭐536)](https://github.com/janoamaral/tokyo-night-tmux) tokyo-night theme for tmux
*   [tomorrow (⭐48)](https://github.com/edouard-lopez/tmux-tomorrow/): 5 flavors of Tomorrow theme based on specifications from [Tomorrow Theme (⭐14k)](https://github.com/chriskempson/tomorrow-theme) (*i.e.* *dark*/*blue* and *light*).
*   [tmux-kanagawa](https://github.com/Nybkox/tmux-kanagawa): Dark colorscheme inspired by the colors of the famous painting by Katsushika Hokusai.
*   [gruvbox-tmux](https://gitlab.com/motaz-shokry/gruvbox-tmux): A clean Tmux theme that follows the [gruvbox (⭐15k)](https://github.com/morhetz/gruvbox) colors
*   [tmux-oasis](https://github.com/uhs-robert/tmux-oasis): Desert theme pack with 12 variants for every color of the rainbow and a dynamic statusline for all tmux modes.

## Status Bar

*   [aws-tmux (⭐34)](https://github.com/darko-mesaros/aws-tmux) Tmux plugin that gives you access to some (potentially) useful information about AWS.
*   [gitmux](https://github.com/arl/gitmux) Show Git status in tmux status bar
*   [muxbar (⭐37)](https://github.com/dlurak/muxbar) configure the status bar in Rust.
*   [tmux2k (⭐380)](https://github.com/2KAbhishek/tmux2k) Highly customizable tmux status bar framework, providing you with a sleek and informative status bar.
*   [tmux-battery](https://github.com/tmux-plugins/tmux-battery) Plug and play battery percentage and icon indicator for Tmux.
*   [tmux-clima (⭐22)](https://github.com/vascomfnunes/tmux-clima) Displays the current temperature and weather condition using the OpenWeather API.
*   [tmux-code-time (⭐5)](https://github.com/theo64oliver/tmux-code-time) - Tracks time spent in sessions. Displays session duration in your status bar.
*   [tmux-colortag (⭐101)](https://github.com/Determinant/tmux-colortag) a plugin/theme that colors the tmux window tags.
*   [tmux-cpu-info (⭐14)](https://github.com/jdxcode/tmux-cpu-info) CPU usage gauge to status bar
*   [tmux-cpu (⭐512)](https://github.com/tmux-plugins/tmux-cpu) Show CPU load with easy icons
*   [tmux-cpu-rs](https://github.com/playbahn/tmux-cpu-rs/) Blazingly fast, small Rust tool to display CPU usage with **caching** for efficiency and optional eye-candy.
*   [tmux-current-pane-hostname (⭐6)](https://github.com/tony-sol/tmux-current-pane-hostname) Show current user and hostname in ssh sessions
*   [tmux-df (⭐43)](https://github.com/tassaron/tmux-df) - Show available disk space (output of df command)
*   [tmux-kripto (⭐7)](https://github.com/vascomfnunes/tmux-kripto) Add a cryptocurrency stock price to the statusbar.
*   [tmux-kubectx (⭐6)](https://github.com/tony-sol/tmux-kubectx) Show kubernetes context in statusbar
*   [tmux-maildir-counter](https://github.com/tmux-plugins/tmux-maildir-counter) Plugin that counts files on a specific mail directory
*   [tmux-mem-cpu-load (⭐1.1k)](https://github.com/thewtex/tmux-mem-cpu-load) CPU, RAM memory, and load monitor for use with tmux
*   [tmux-mode-indicator (⭐191)](https://github.com/MunifTanjim/tmux-mode-indicator) Displays prompt indicating currently active Tmux mode.
*   [tmux-mpv-info (⭐5)](https://github.com/Feqzz/tmux-mpv-info) Displays the current song playing with MPV in your tmux status bar.
*   [tmux-mullvad](https://github.com/jaclu/tmux-mullvad) - Keep track of [Mullvad VPN](https://mullvad.net/) status.
*   [tmux-ludanta (⭐4)](https://github.com/vascomfnunes/tmux-ludanta) - What's playing
    on an MPD local server.
*   [tmux-nerd-font-window-name (⭐203)](https://github.com/joshmedeski/tmux-nerd-font-window-name) Nerd Font icons for your tmux windows
*   [tmux-network-bandwidth (⭐83)](https://github.com/xamut/tmux-network-bandwidth) Show
    network bandwidth
*   [tmux-nordvpn (⭐17)](https://github.com/maxrodrigo/tmux-nordvpn) Monitor the current NordVPN connection status.
*   [tmux-online-status (⭐181)](https://github.com/tmux-plugins/tmux-online-status) Tmux plugin that displays online status of your computer
*   [tmux-packet-loss (⭐13)](https://github.com/jaclu/tmux-packet-loss) - Displays packet loss % if at or above the specified threshold level
*   [tmux-piavpn (⭐10)](https://github.com/Brutuski/tmux-piavpn) Keep track of your [Private Internet Access](https://www.privateinternetaccess.com/) VPN status.
*   [tmux-plugin-playerctl (⭐15)](https://github.com/richin13/tmux-plugin-playerctl) Display [MPRIS](https://www.freedesktop.org/wiki/Specifications/mpris-spec/) metadata in Tmux (Spotify, Clementine, VLC, etc)
*   [tmux-pomodoro-plus (⭐446)](https://github.com/olimorris/tmux-pomodoro-plus) Incorporate the Pomodoro technique into your tmux workflow
*   [tmux-powerline-nostatus](https://gist.github.com/james1236/73bb8b7279dca0bc821518abada38f1e) Display your tmux window list directly in your terminal prompt, eliminating the tmux status bar.
*   [tmux-prefix-highlight (⭐655)](https://github.com/tmux-plugins/tmux-prefix-highlight) Plugin that highlights when you press tmux prefix key
*   [tmux-session-dots (⭐0)](https://github.com/jtmcginty/tmux-session-dots) Visual session indicator showing all sessions as dots with the current session highlighted.
*   [tmux-split-statusbar (⭐31)](https://github.com/charlietag/tmux-split-statusbar) Plugin for splitting status bar into 2 parts - window + left/right status
*   [tmux-speedtest](https://github.com/YousefHadder/tmux-speedtest) Run internet speed tests and display results in your status bar.
*   [tmux-spotify-info (⭐79)](https://github.com/jdxcode/tmux-spotify-info) Spotify track info on your status bar (OSX)
*   [tmux-spotify-info (⭐15)](https://github.com/Feqzz/tmux-spotify-info) Spotify track info on your status bar (Linux)
*   [tmux-transient-status (⭐21)](https://github.com/TheSast/tmux-transient-status) Automatically make your tmux status bar vanish when unneded.
*   [tmux-weather (⭐34)](https://github.com/jdxcode/tmux-weather) Add weather status via forcast.io
*   [tmux-weather (⭐82)](https://github.com/xamut/tmux-weather) Show current weather using wttr.in
*   [tmux-window-name (⭐275)](https://github.com/ofirgall/tmux-window-name) Names your tmux windows smartly.
*   [tmux-weather-info-yr (⭐2)](https://github.com/Feqzz/tmux-weather-info-yr) Displays the current temperature and weather based on your location via yr.no
*   [tmux-world-clock (⭐36)](https://github.com/alexanderjeurissen/tmux-world-clock) Show multiple timezones using Olson tz database.
*   [tmux-workspace-usage (⭐4)](https://github.com/sjdonado/tmux-workspace-usage) Displays the memory and CPU usage of your workspace processes.

## Plugins

*   [back-in-5 (⭐3)](https://github.com/hamolicious/back-in-5) display a "Back soon" message for remote collaboration
*   [tmux2html (⭐735)](https://github.com/tweekmonster/tmux2html) :cat2: Render full tmux windows or individual panes as HTML
*   [tmux-better-mouse-mode (⭐964)](https://github.com/NHDaly/tmux-better-mouse-mode) A tmux plugin to better manage and configure the mouse.
*   [extrakto (⭐1.1k)](https://github.com/laktak/extrakto) tmux clipboard copy and output completions
*   [kmux-status (⭐6)](https://github.com/tardunge/kmux-status) - Tmux plugin to render kubernetes context and other indicators on the status-line.
*   [muxile (⭐167)](https://github.com/bjesus/muxile) - View and control your tmux session from your mobile.
*   [nunchux (⭐63)](https://github.com/datamadsen/nunchux) A fuzzy launcher for apps, files, and build tasks with live status, keyboard shortcuts, and task runner integration.
*   [tmux-agent-indicator (⭐13)](https://github.com/accessd/tmux-agent-indicator) Track AI agent state (Claude, Codex, etc.) with pane borders, background colors, window titles, and status bar icons.
*   [tmux-autoreload (⭐118)](https://github.com/b0o/tmux-autoreload) - Watches your tmux configuration file and automatically reloads it on change.
*   [tmux-bitwarden](https://github.com/Alkindi42/tmux-bitwarden) Access your Bitwarden login items in a tmux pane.
*   [tmux-browser (⭐142)](https://github.com/ofirgall/tmux-browser) Web browser sessions attached to tmux sessions.
*   [tmux-cht-sh (⭐41)](https://github.com/kenos1/tmux-cht-sh) Access cheatsheets easily in a popup
*   [tmux-claude-sessions (⭐0)](https://github.com/aomerk/tmux-claude-sessions) Browse and resume Claude AI conversations from a fzf popup
*   [tmux-click-copy (⭐7)](https://github.com/aless3/tmux-click-copy) word/line copy on double/triple click without fixed timeout and without remaining stuck in copy mode
*   [tmux-compile (⭐18)](https://github.com/alexekdahl/tmux-compile) Run compile commands directly inside tmux with automatic pane handling.
*   [tmux-command-palette (⭐31)](https://github.com/lost-melody/tmux-command-palette) Search for keybindings and custom commands with fzf.
*   [tmux-copytk (⭐70)](https://github.com/CrispyConductor/tmux-copy-toolkit) - Multi utility rapid copy toolkit.
*   [tmux-devcontainers (⭐17)](https://github.com/phil/tmux-devcontainers) - Manage and interact with (Devcontainers)\[<https://containers.dev>]
*   [tmux-easy-motion (⭐99)](https://github.com/IngoMeyer441/tmux-easy-motion) vim-easymotion like navigation for tmux.
*   [tmux-easymotion (⭐43)](https://github.com/ddzero2c/tmux-easymotion) EasyMotion-like plugin with pane jumping capabilities in tmux.
*   [tmux-filter (⭐7)](https://github.com/MaximilianGaedig/tmux-filter) Filter the current buffer by some text/pattern, very useful for viewing logs.
*   [tmux-fingers (⭐1.3k)](https://github.com/Morantron/tmux-fingers) copy pasting in terminal with vimium/vimperator like hints.
*   [tmux-floating-plugin (⭐15)](https://github.com/lloydbond/tmux-floating-terminal) - A popup floating terminal window in tmux.
*   [tmux-fuzzback (⭐175)](https://github.com/roosta/tmux-fuzzback) Search your scrollback buffer using fzf.
*   [tmux-fzf-url](https://github.com/wfxr/tmux-fzf-url) For opening urls from browser quickly without mouse.
*   [tmux-fzf-session-switch](https://github.com/thuanOwa/tmux-fzf-session-switch) Easy way to switch, when you have a ton of sessions.
*   [tmux-gh (⭐2)](https://github.com/tardunge/tmux-gh) - Tmux plugin to fetch the github helper profile. Displays, the currently actively authenticated git username.
*   [tmux-grimoire (⭐102)](https://github.com/navahas/tmux-grimoire) - Customizable popup shells (aka shpells) driven by custom scripts.
*   [tmux-keylocker (⭐6)](https://github.com/TheSast/tmux-keylocker) Lock away your tmux keybinds temporarely.
*   [tmux-llm](https://github.com/hynek-urban/tmux-llm) Get quick responses to your terminal contents from LLM assistants.
*   [tmux-menus (⭐469)](https://github.com/jaclu/tmux-menus) - Popup menus to help with managing your environment.
*   [tmux-modal](https://github.com/whame/tmux-modal) - Execute complex tmux commands in just a few keystrokes with a modal mode that is designed to be efficient, easy to remember and comfortable.
*   [tmux-mouse-swipe](https://github.com/jaclu/tmux-mouse-swipe) - Switch Window or Session by clicking right mouse button and swiping.
*   [tmux-notify (⭐233)](https://github.com/rickstaa/tmux-notify) A plugin to notify you when processes are finished.
*   [tmux-open-nvim (⭐70)](https://github.com/trevarj/tmux-open-nvim) - A plugin to help open files in a running instance of Neovim. Pairs well with tmux-fingers or tmux-open.
*   [tmux-fzf-open-files-nvim](https://github.com/Peter-McKinney/tmux-fzf-open-files-nvim) - A plugin that parses pane text for files for selection in fzf to open in neovim.
*   [tmux-thumbs (⭐1k)](https://github.com/fcsonline/tmux-thumbs) A lightning fast version of tmux-fingers written in Rust, copy/pasting tmux like vimium/vimperator
*   [tmux-1password (⭐271)](https://github.com/yardnsm/tmux-1password) Access your 1Password login items in a tmux pane.
*   [tmux-jump (⭐433)](https://github.com/schasse/tmux-jump) Vimium/Easymotion like navigation for tmux.
*   [tmux-power-zoom (⭐62)](https://github.com/jaclu/tmux-power-zoom) Zoom pane to separate window, then unzoom it back into it's original location.
*   [tmux-session-wizard (⭐251)](https://github.com/27medkamal/tmux-session-wizard) One prefix to control all your session creation, naming, switching, etc using [fzf (⭐78k)](https://github.com/junegunn/fzf) & [zoxide (⭐34k)](https://github.com/ajeetdsouza/zoxide).
*   [tmux-simple-git-status (⭐31)](https://github.com/kristijanhusak/tmux-simple-git-status) Show branch and number of changes in current git repository
*   [tmux-spotify (⭐124)](https://github.com/xamut/tmux-spotify) Show a nice menu to manage Spotify application
*   [tmux-spotify-playlists (⭐25)](https://github.com/danjeltahko/spotify-tmux) Another Spotify plugin, but for saving and playing your favorite playlists
*   [tmux-super-fingers (⭐100)](https://github.com/artemave/tmux_super_fingers) like fingers, but also opens files in vim.
*   [tmux-tilish (⭐483)](https://github.com/jabirali/tmux-tilish) Turn tmux into a dynamic window manager with intuitive keybindings (inspired by i3wm/sway)
*   [tmux-tilit (⭐75)](https://github.com/2KAbhishek/tmux-tilit) Brings tiling window manager features and intuitive keybindings to your tmux workflow.
*   [tmux-timetrap](https://github.com/croxarens/tmux-timetrap) Keep your time tracked directly with TMUX (The plugin is just a wrapper for [timetrap (⭐1.5k)](https://github.com/samg/timetrap))
*   [tmux-toggle-scratch (⭐4)](https://github.com/momo-lab/tmux-toggle-scratch) Toggle scratch popup sessions for quick note-taking and temporary work.
*   [tmux-wormhole](https://github.com/gcla/tmux-wormhole) Use tmux to download files with magic wormhole
*   [tmux-pianobar (⭐7)](https://github.com/GoHarder/tmux-pianobar) A menu and status bar widget for Pianobar
*   [tmux-pane-focus](https://github.com/graemedavidson/tmux-pane-focus) Auto-Resizing splits to improve readability.
*   [tmux-plugins](https://github.com/tmux-plugins) Official tmux plugins
    *   [tmux-continuum (⭐3.8k)](https://github.com/tmux-plugins/tmux-continuum) Continuous saving of tmux environment. Automatic restore when tmux is started. Automatic tmux start when computer is turned on.
    *   [tmux-copycat](https://github.com/tmux-plugins/tmux-copycat) A plugin that enhances tmux search
    *   [tmux-fpp](https://github.com/tmux-plugins/tmux-fpp) Quickly open any path on your terminal window in your $EDITOR of choice!
    *   [tmux-logging (⭐1.2k)](https://github.com/tmux-plugins/tmux-logging) Easy logging and screen capturing for Tmux.
    *   [tmux-open (⭐716)](https://github.com/tmux-plugins/tmux-open) Tmux key bindings for quick opening of a highlighted file or url
    *   [tmux-pain-control](https://github.com/tmux-plugins/tmux-pain-control) standard pane key-bindings for tmux
    *   [tmux-resurrect](https://github.com/tmux-plugins/tmux-resurrect) Persists tmux environment across system restarts.
    *   [tmux-sessionist (⭐458)](https://github.com/tmux-plugins/tmux-sessionist) Lightweight tmux utils for manipulating sessions
    *   [tmux-sidebar](https://github.com/tmux-plugins/tmux-sidebar) A sidebar with the directory tree for the current path. Tries to make tmux more IDE like.
    *   [tmux-smooth-scroll (⭐55)](https://github.com/azorng/tmux-smooth-scroll) Smooth scrolling for tmux
    *   [tmux-tpm (⭐14k)](https://github.com/tmux-plugins/tpm) Tmux Plugin Manager
    *   [tmux-urlview (⭐286)](https://github.com/tmux-plugins/tmux-urlview) Quickly open any url on your terminal window! (No commits since 2016, see tmux-urlscan or tmux-fzf-url for a maintained alternative.)
    *   [tmux-yank (⭐3k)](https://github.com/tmux-plugins/tmux-yank) Tmux plugin for copying to system clipboard. Works on OSX, Linux and Cygwin.
*   [tmux-port (⭐4)](https://github.com/fiqryq/port) A tiny tmux plugin to view listening ports and kill processes — in a centered popup or split panes.

### Development and testing

*   [gotmux (⭐46)](https://github.com/GianlucaP106/gotmux) A golang library to interact with tmux.
*   [tmux-example-plugin](https://github.com/tmux-plugins/tmux-example-plugin) Example Tmux plugin that actually demonstrates how to build plugins for Tmux
*   [tmux-test](https://github.com/tmux-plugins/tmux-test) A small framework for isolated testing of tmux plugins.

## Books

*   [tmux 2: Productive Mouse-Free Development](https://pragprog.com/book/bhtmux2/tmux-2/)
*   [The Tao of tmux](https://leanpub.com/the-tao-of-tmux)

## Miscellaneous

*   [sixel-tmux](https://github.com/csdvrx/sixel-tmux) a fork of tmux, with just one goal: having the most reliable support of graphics
*   [Statically linked tmux](https://gist.github.com/rothgar/719ef460efc214c8d222) Install new version without root access
*   [sublime-tmux (⭐10)](https://github.com/huntie/sublime-tmux) Sublime Text plugin to interact with tmux sessions
*   [tmuxai](https://github.com/alvinunreal/tmuxai) AI-Powered, Non-Intrusive Terminal Assistant
*   [tmux-tail-f](https://github.com/mapio/tmux-tail-f) A tool to tail multiple files using tmux
*   [vim-tmux](https://github.com/tmux-plugins/vim-tmux) vim plugin for tmux.conf

