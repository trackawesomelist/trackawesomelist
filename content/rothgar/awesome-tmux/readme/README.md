# Awesome Tmux Overview

A list of awesome resources for tmux

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/rothgar/awesome-tmux/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 rothgar/awesome-tmux](https://github.com/rothgar/awesome-tmux) · ⭐ 7.6K · 🏷️ Development Environment

[ [Daily](/content/rothgar/awesome-tmux/README.md) / [Weekly](/content/rothgar/awesome-tmux/week/README.md) / Overview ]

---

# Awesome [Tmux](https://tmux.github.io/)

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
*   [Tmux primer](https://danielmiessler.com/study/tmux/)
*   [Tmux and Vim together](https://www.bugsnag.com/blog/tmux-and-vim)

## <a name="cheatsheets"></a>Cheat Sheets

*   [tmux-cheatsheet.markdown](https://gist.github.com/MohamedAlaa/2961058)
*   [tmuxcheatsheet.com](https://tmuxcheatsheet.com/)

## Configuration

*   [Oh My Tmux! (⭐22k)](https://github.com/gpakosz/.tmux) Powerline-like theme, vim bindings, SSH aware, improved maximize pane, ...
*   [Example tmux config (⭐1.8k)](https://github.com/tony/tmux-config) :green\_book: Example tmux configuration - screen + vim key-bindings, system stat, cpu load bar
*   [Guide to customizing tmux.conf](https://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/)
*   [practical tmux](https://mutelight.org/practical-tmux)
*   [tmux-extra (⭐119)](https://github.com/brandur/tmux-extra) Configuration and scripts for sane Tmux default behavior
*   [tmux-keybtest (⭐1)](https://github.com/jaclu/tmux-keybtest) Check what keys tmux can detect from the terminal being used.
*   [tmux yank to system clipboard](https://www.grailbox.com/2020/08/use-system-clipboard-for-vi-copy-mode-in-tmux-in-macos-and-linux/) A way to get the System Clipboard to work with tmux yank on a Mac via `pbcopy` and linux via `xclip`

## <a name="tools"></a>Tools and session management

*   [automux (⭐8)](https://github.com/sriramkandukuri/automux) Wrappers to tmux commands, useful for tmux based automation
*   [disconnected (⭐13)](https://github.com/austinwilcox/disconnected) A session manager written in Deno with json as the config files
*   [dmux (⭐309)](https://github.com/zdcthomas/dmux) Configurable tmux workspace manager written in Rust
*   [harpoon (⭐12)](https://github.com/Chaitanyabsprip/tmux-harpoon) A tool to bookmark sessions and jump between them in a flash. Like ThePrimeagen/harpoon, but for tmux.
*   [libtmux (⭐1k)](https://github.com/tmux-python/libtmux) Python API for tmux
*   [moxide (⭐0)](https://github.com/dlurak/moxide) A tmux session manager with a modular config
*   [powerline (⭐14k)](https://github.com/powerline/powerline) Statusline plugin for vim, and provides statuslines and prompts for several other applications including tmux
*   [tmux-powerline (⭐3.4k)](https://github.com/erikw/tmux-powerline) A hackable statusbar for tmux consisting of dynamic & beautiful looking segments, inspired by vim-powerline, written purely in bash.
*   [sesh (⭐584)](https://github.com/joshmedeski/sesh) Smart session manager for the terminal
*   [smug (⭐691)](https://github.com/ivaaaan/smug) A session manager for tmux written in Go
*   [sessionx (⭐723)](https://github.com/omerxx/tmux-sessionx) A Tmux session manager, with preview, fuzzy finding, and MORE
*   [t (⭐325)](https://github.com/joshmedeski/t-smart-tmux-session-manager) The smart tmux session manager
*   [tat (⭐38)](https://github.com/ryandotsmith/tat) Tab completion for tmux sessions
*   [tea (⭐26)](https://github.com/2KAbhishek/tmux-tea) Session manager with previews, integration with tmuxinator, fzf and more, inspired by t
*   [teamocil (⭐2.4k)](https://github.com/remi/teamocil) A simple tool used to automatically create windows and panes in tmux with YAML files
*   [tmex (⭐88)](https://github.com/evnp/tmex) A minimalist tmux layout manager
*   [tmux-cssh (⭐81)](https://github.com/zinic/tmux-cssh) Tmux with a "ClusterSSH"-like behavior
*   [tmux-conf (⭐2)](https://github.com/jaclu/tmux-conf) Meant for users running tmux on multiple hosts, not always running the same version. Generates tmux config files using version checks
*   [tmux-nav-master (⭐6)](https://github.com/TheSast/tmux-nav-master) Easy cross-navigation between tmux and other terminal applications.
*   [tmux-project (⭐6)](https://github.com/sei40kr/tmux-project) Search projects and open them in a new session
*   [tmux-suspend (⭐126)](https://github.com/MunifTanjim/tmux-suspend) Suspend local session for painlessly working with nested remote session.
*   [tmux-up (⭐113)](https://github.com/jamesottaway/tmux-up) Bootstrap new `tmux` sessions without complex tools, DSLs, or dependencies
*   [tmuxake (⭐11)](https://github.com/nkh/tmuxake) A side-pane manager for tmux
*   [tmuxifier (⭐1.3k)](https://github.com/jimeh/tmuxifier) Tmuxify your Tmux. Powerful session, window & pane management for Tmux.
*   [tmuxinator (⭐13k)](https://github.com/tmuxinator/tmuxinator) Manage complex tmux sessions easily
*   [tmuxp (⭐4.1k)](https://github.com/tmux-python/tmuxp) :computer: tmux session manager and python library
*   [tmuxpair (⭐44)](https://github.com/goerz/tmuxpair) Command line script for setting up a temporary tmux session for pair programming
*   [tome (⭐43)](https://github.com/laktak/tome) 🔁 Playbooks for tmux & vim, replacing your shell history
*   [twm (⭐32)](https://github.com/vinnymeller/twm) A highly configurable workspace manager that is easy to extend with shell scripts, written in Rust
*   [vim-tmux-navigator (⭐5.3k)](https://github.com/christoomey/vim-tmux-navigator) Vim and tmux integration
*   [xpanes (⭐1.9k)](https://github.com/greymd/tmux-xpanes) Awesome tmux-based terminal divider

## Themes

*   [catppuccin (⭐1.8k)](https://github.com/catppuccin/tmux) Catppuccin `Latte`, `Frappe`, `Macchiato`, and `Mocha` themes for tmux.
*   [dracula/tmux (⭐646)](https://github.com/dracula/tmux) 🧛🏻‍♂️ The official [dracula theme](https://draculatheme.com/) for tmux
*   [minimal-tmux-status (⭐124)](https://github.com/niksingh710/minimal-tmux-status/): Minimal theme with only required information in status bar and prefix indicator. (changes only status bar)
*   [nord tmux (⭐1.1k)](https://github.com/arcticicestudio/nord-tmux) An arctic, north-bluish clean and elegant tmux color theme.
*   [rose-pine (⭐139)](https://github.com/rose-pine/tmux) - Soho vibes for tmux
*   [tmux-base16-statusline (⭐26)](https://github.com/jatap/tmux-base16-statusline) Statusline based on [base16-shell (⭐188)](https://github.com/chriskempson/base16-shell)
*   [tmux-colors-solarized (⭐1.1k)](https://github.com/seebi/tmux-colors-solarized) A color theme for the tmux terminal multiplexer using Ethan Schoonover’s Solarized color scheme
*   [tmux-dark-notify (⭐47)](https://github.com/erikw/tmux-dark-notify) - Make tmux's theme follow macOS dark/light mode.
*   [tmux-gruvbox (⭐512)](https://github.com/egel/tmux-gruvbox) Light and dark tmux theme
*   [tmux-nova (⭐173)](https://github.com/o0th/tmux-nova) Fully customizable tmux theme
*   [tmux-power (⭐538)](https://github.com/wfxr/tmux-power) 8 powerline style themes for tmux, easily to expand.
*   [tmux-snazzy (⭐14)](https://github.com/ivnvxd/tmux-snazzy) Elegant tmux theme with bright colors
*   [tmux-themepack (⭐1.7k)](https://github.com/jimeh/tmux-themepack) Various themes for tmux
*   [tmux-tokyo-night (⭐148)](https://github.com/fabioluciano/tmux-tokyo-night) A vim inspired tokyo night theme
*   [tokyo-night-tmux (⭐304)](https://github.com/janoamaral/tokyo-night-tmux) tokyo-night theme for tmux
*   [tomorrow (⭐45)](https://github.com/edouard-lopez/tmux-tomorrow/): 5 flavors of Tomorrow theme based on specifications from [Tomorrow Theme (⭐14k)](https://github.com/chriskempson/tomorrow-theme) (*i.e.* *dark*/*blue* and *light*).
*   [tmux2k (⭐179)](https://github.com/2KAbhishek/tmux2k): Colorful and informative tmux theme.
*   [tmux-kanagawa (⭐63)](https://github.com/Nybkox/tmux-kanagawa): Dark colorscheme inspired by the colors of the famous painting by Katsushika Hokusai.

## Status Bar

*   [aws-tmux (⭐30)](https://github.com/darko-mesaros/aws-tmux) Tmux plugin that gives you access to some (potentially) useful information about AWS.
*   [gitmux (⭐618)](https://github.com/arl/gitmux) Show Git status in tmux status bar
*   [muxbar (⭐8)](https://github.com/dlurak/muxbar) configure the status bar in Rust.
*   [tmux-battery (⭐498)](https://github.com/tmux-plugins/tmux-battery) Plug and play battery percentage and icon indicator for Tmux.
*   [tmux-clima (⭐12)](https://github.com/vascomfnunes/tmux-clima) Displays the current temperature and weather condition using the OpenWeather API.
*   [tmux-colortag (⭐96)](https://github.com/Determinant/tmux-colortag) a plugin/theme that colors the tmux window tags.
*   [tmux-cpu-info (⭐14)](https://github.com/jdxcode/tmux-cpu-info) CPU usage gauge to status bar
*   [tmux-cpu (⭐433)](https://github.com/tmux-plugins/tmux-cpu) Show CPU load with easy icons
*   [tmux-df (⭐30)](https://github.com/tassaron/tmux-df) - Show available disk space (output of df command)
*   [tmux-kripto (⭐5)](https://github.com/vascomfnunes/tmux-kripto) Add a cryptocurrency stock price to the statusbar.
*   [tmux-maildir-counter (⭐32)](https://github.com/tmux-plugins/tmux-maildir-counter) Plugin that counts files on a specific mail directory
*   [tmux-mem-cpu-load (⭐1k)](https://github.com/thewtex/tmux-mem-cpu-load) CPU, RAM memory, and load monitor for use with tmux
*   [tmux-mode-indicator (⭐144)](https://github.com/MunifTanjim/tmux-mode-indicator) Displays prompt indicating currently active Tmux mode.
*   [tmux-mpv-info (⭐4)](https://github.com/Feqzz/tmux-mpv-info) Displays the current song playing with MPV in your tmux status bar.
*   [tmux-mullvad (⭐7)](https://github.com/jaclu/tmux-mullvad) - Keep track of [Mullvad VPN](https://mullvad.net/) status.
*   [tmux-ludanta (⭐1)](https://github.com/vascomfnunes/tmux-ludanta) - What's playing
    on an MPD local server.
*   [tmux-nerd-font-window-name (⭐140)](https://github.com/joshmedeski/tmux-nerd-font-window-name) Nerd Font icons for your tmux windows
*   [tmux-network-bandwidth (⭐78)](https://github.com/xamut/tmux-network-bandwidth) Show
    network bandwidth
*   [tmux-nordvpn (⭐18)](https://github.com/maxrodrigo/tmux-nordvpn) Monitor the current NordVPN connection status.
*   [tmux-online-status (⭐169)](https://github.com/tmux-plugins/tmux-online-status) Tmux plugin that displays online status of your computer
*   [tmux-packet-loss (⭐10)](https://github.com/jaclu/tmux-packet-loss) - Displays packet loss % if at or above the specified threshold level
*   [tmux-piavpn (⭐8)](https://github.com/Brutuski/tmux-piavpn) Keep track of your [Private Internet Access](https://www.privateinternetaccess.com/) VPN status.
*   [tmux-plugin-playerctl (⭐11)](https://github.com/richin13/tmux-plugin-playerctl) Display [MPRIS](https://www.freedesktop.org/wiki/Specifications/mpris-spec/) metadata in Tmux (Spotify, Clementine, VLC, etc)
*   [tmux-pomodoro-plus (⭐312)](https://github.com/olimorris/tmux-pomodoro-plus) Incorporate the Pomodoro technique into your tmux workflow
*   [tmux-prefix-highlight (⭐571)](https://github.com/tmux-plugins/tmux-prefix-highlight) Plugin that highlights when you press tmux prefix key
*   [tmux-split-statusbar (⭐25)](https://github.com/charlietag/tmux-split-statusbar) Plugin for splitting status bar into 2 parts - window + left/right status
*   [tmux-spotify-info (⭐79)](https://github.com/jdxcode/tmux-spotify-info) Spotify track info on your status bar (OSX)
*   [tmux-spotify-info (⭐10)](https://github.com/Feqzz/tmux-spotify-info) Spotify track info on your status bar (Linux)
*   [tmux-transient-status (⭐13)](https://github.com/TheSast/tmux-transient-status) Automatically make your tmux status bar vanish when unneded.
*   [tmux-weather (⭐34)](https://github.com/jdxcode/tmux-weather) Add weather status via forcast.io
*   [tmux-weather (⭐66)](https://github.com/xamut/tmux-weather) Show current weather using wttr.in
*   [tmux-window-name (⭐208)](https://github.com/ofirgall/tmux-window-name) Names your tmux windows smartly.
*   [tmux-weather-info-yr (⭐1)](https://github.com/Feqzz/tmux-weather-info-yr) Displays the current temperature and weather based on your location via yr.no
*   [tmux-world-clock (⭐32)](https://github.com/alexanderjeurissen/tmux-world-clock) Show multiple timezones using Olson tz database.

## Plugins

*   [tmux2html (⭐710)](https://github.com/tweekmonster/tmux2html) :cat2: Render full tmux windows or individual panes as HTML
*   [tmux-better-mouse-mode (⭐913)](https://github.com/NHDaly/tmux-better-mouse-mode) A tmux plugin to better manage and configure the mouse.
*   [extrakto (⭐869)](https://github.com/laktak/extrakto) tmux clipboard copy and output completions
*   [kmux-status (⭐6)](https://github.com/tardunge/kmux-status) - Tmux plugin to render kubernetes context and other indicators on the status-line.
*   [muxile (⭐106)](https://github.com/bjesus/muxile) - View and control your tmux session from your mobile.
*   [tmux-autoreload (⭐78)](https://github.com/b0o/tmux-autoreload) - Watches your tmux configuration file and automatically reloads it on change.
*   [tmux-bitwarden (⭐37)](https://github.com/Alkindi42/tmux-bitwarden) Access your Bitwarden login items in a tmux pane.
*   [tmux-browser (⭐85)](https://github.com/ofirgall/tmux-browser) Web browser sessions attached to tmux sessions.
*   [tmux-cht-sh (⭐26)](https://github.com/kenos1/tmux-cht-sh) Access cheatsheets easily in a popup
*   [tmux-copytk (⭐59)](https://github.com/CrispyConductor/tmux-copy-toolkit) - Multi utility rapid copy toolkit.
*   [tmux-easy-motion (⭐80)](https://github.com/IngoMeyer441/tmux-easy-motion) vim-easymotion like navigation for tmux.
*   [tmux-filter (⭐5)](https://github.com/MaximilianGaedig/tmux-filter) Filter the current buffer by some text/pattern, very useful for viewing logs.
*   [tmux-fingers (⭐991)](https://github.com/Morantron/tmux-fingers) copy pasting in terminal with vimium/vimperator like hints.
*   [tmux-fuzzback (⭐132)](https://github.com/roosta/tmux-fuzzback) Search your scrollback buffer using fzf.
*   [tmux-fzf-url (⭐522)](https://github.com/wfxr/tmux-fzf-url) For opening urls from browser quickly without mouse.
*   [tmux-fzf-session-switch (⭐50)](https://github.com/thuanOwa/tmux-fzf-session-switch) Easy way to switch, when you have a ton of sessions.
*   [tmux-gh (⭐1)](https://github.com/tardunge/tmux-gh) - Tmux plugin to fetch the github helper profile. Displays, the currently actively authenticated git username.
*   [tmux-keylocker (⭐4)](https://github.com/TheSast/tmux-keylocker) Lock away your tmux keybinds temporarely.
*   [tmux-menus (⭐307)](https://github.com/jaclu/tmux-menus) - Popup menus to help with managing your environment.
*   [tmux-modal (⭐177)](https://github.com/whame/tmux-modal) - Execute complex tmux commands in just a few keystrokes with a modal mode that is designed to be efficient, easy to remember and comfortable.
*   [tmux-mouse-swipe (⭐12)](https://github.com/jaclu/tmux-mouse-swipe) - Switch Window or Session by clicking right mouse button and swiping.
*   [tmux-notify (⭐161)](https://github.com/rickstaa/tmux-notify) A plugin to notify you when processes are finished.
*   [tmux-open-nvim (⭐47)](https://github.com/trevarj/tmux-open-nvim) - A plugin to help open files in a running instance of Neovim. Pairs well with tmux-fingers or tmux-open.
*   [tmux-thumbs (⭐903)](https://github.com/fcsonline/tmux-thumbs) A lightning fast version of tmux-fingers written in Rust, copy/pasting tmux like vimium/vimperator
*   [tmux-1password (⭐252)](https://github.com/yardnsm/tmux-1password) Access your 1Password login items in a tmux pane.
*   [tmux-jump (⭐356)](https://github.com/schasse/tmux-jump) Vimium/Easymotion like navigation for tmux.
*   [tmux-power-zoom (⭐44)](https://github.com/jaclu/tmux-power-zoom) Zoom pane to separate window, then unzoom it back into it's original location.
*   [tmux-session-wizard (⭐179)](https://github.com/27medkamal/tmux-session-wizard) One prefix to control all your session creation, naming, switching, etc using [fzf (⭐64k)](https://github.com/junegunn/fzf) & [zoxide (⭐22k)](https://github.com/ajeetdsouza/zoxide).
*   [tmux-simple-git-status (⭐27)](https://github.com/kristijanhusak/tmux-simple-git-status) Show branch and number of changes in current git repository
*   [tmux-spotify (⭐112)](https://github.com/xamut/tmux-spotify) Show a nice menu to manage Spotify application
*   [tmux-spotify-playlists (⭐24)](https://github.com/danjeltahko/spotify-tmux) Another Spotify plugin, but for saving and playing your favorite playlists
*   [tmux-super-fingers (⭐84)](https://github.com/artemave/tmux_super_fingers) like fingers, but also opens files in vim.
*   [tmux-tilish (⭐413)](https://github.com/jabirali/tmux-tilish) Turn tmux into a dynamic window manager with intuitive keybindings (inspired by i3wm/sway)
*   [tmux-tilit (⭐28)](https://github.com/2KAbhishek/tmux-tilit) A more streamlined and enhanced version of tmux-tilish focusing on simplicity.
*   [tmux-timetrap (⭐2)](https://github.com/croxarens/tmux-timetrap) Keep your time tracked directly with TMUX (The plugin is just a wrapper for [timetrap (⭐1.5k)](https://github.com/samg/timetrap))
*   [tmux-wormhole (⭐98)](https://github.com/gcla/tmux-wormhole) Use tmux to download files with magic wormhole
*   [tmux-pianobar (⭐7)](https://github.com/GoHarder/tmux-pianobar) A menu and status bar widget for Pianobar
*   [tmux-plugins](https://github.com/tmux-plugins) Official tmux plugins
    *   [tmux-continuum (⭐3.3k)](https://github.com/tmux-plugins/tmux-continuum) Continuous saving of tmux environment. Automatic restore when tmux is started. Automatic tmux start when computer is turned on.
    *   [tmux-copycat (⭐1.1k)](https://github.com/tmux-plugins/tmux-copycat) A plugin that enhances tmux search
    *   [tmux-fpp (⭐308)](https://github.com/tmux-plugins/tmux-fpp) Quickly open any path on your terminal window in your $EDITOR of choice!
    *   [tmux-logging (⭐1k)](https://github.com/tmux-plugins/tmux-logging) Easy logging and screen capturing for Tmux.
    *   [tmux-open (⭐631)](https://github.com/tmux-plugins/tmux-open) Tmux key bindings for quick opening of a highlighted file or url
    *   [tmux-pain-control (⭐755)](https://github.com/tmux-plugins/tmux-pain-control) standard pane key-bindings for tmux
    *   [tmux-resurrect (⭐11k)](https://github.com/tmux-plugins/tmux-resurrect) Persists tmux environment across system restarts.
    *   [tmux-sessionist (⭐412)](https://github.com/tmux-plugins/tmux-sessionist) Lightweight tmux utils for manipulating sessions
    *   [tmux-sidebar (⭐536)](https://github.com/tmux-plugins/tmux-sidebar) A sidebar with the directory tree for the current path. Tries to make tmux more IDE like.
    *   [tmux-tpm (⭐12k)](https://github.com/tmux-plugins/tpm) Tmux Plugin Manager
    *   [tmux-urlview (⭐266)](https://github.com/tmux-plugins/tmux-urlview) Quickly open any url on your terminal window! (No commits since 2016, see tmux-urlscan or tmux-fzf-url for a maintained alternative.)
    *   [tmux-yank (⭐2.7k)](https://github.com/tmux-plugins/tmux-yank) Tmux plugin for copying to system clipboard. Works on OSX, Linux and Cygwin.

### Development and testing

*   [tmux-example-plugin (⭐45)](https://github.com/tmux-plugins/tmux-example-plugin) Example Tmux plugin that actually demonstrates how to build plugins for Tmux
*   [tmux-test (⭐16)](https://github.com/tmux-plugins/tmux-test) A small framework for isolated testing of tmux plugins.

## Books

*   [tmux 2: Productive Mouse-Free Development](https://pragprog.com/book/bhtmux2/tmux-2/)
*   [The Tao of tmux](https://leanpub.com/the-tao-of-tmux)

## Miscellaneous

*   [sixel-tmux (⭐472)](https://github.com/csdvrx/sixel-tmux) a fork of tmux, with just one goal: having the most reliable support of graphics
*   [Statically linked tmux](https://gist.github.com/rothgar/719ef460efc214c8d222) Install new version without root access
*   [sublime-tmux (⭐9)](https://github.com/huntie/sublime-tmux) Sublime Text plugin to interact with tmux sessions
*   [vim-tmux (⭐333)](https://github.com/tmux-plugins/vim-tmux) vim plugin for tmux.conf
*   [tmux-tail-f (⭐32)](https://github.com/mapio/tmux-tail-f) A tool to tail multiple files using tmux

