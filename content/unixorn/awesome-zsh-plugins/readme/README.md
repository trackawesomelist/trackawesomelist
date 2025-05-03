# Awesome Zsh Plugins Overview

A collection of ZSH frameworks, plugins, themes and tutorials.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/unixorn/awesome-zsh-plugins/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 unixorn/awesome-zsh-plugins](https://github.com/unixorn/awesome-zsh-plugins) · ⭐ 16K · 🏷️ Development Environment

[ [Daily](/content/unixorn/awesome-zsh-plugins/README.md) / [Weekly](/content/unixorn/awesome-zsh-plugins/week/README.md) / Overview ]

---

# awesome-zsh-plugins

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Status

[![License](https://img.shields.io/github/license/unixorn/awesome-zsh-plugins.svg)](https://opensource.org/license/BSD-3-Clause)
![Awesomebot](https://github.com/unixorn/awesome-zsh-plugins/actions/workflows/awesomebot.yml/badge.svg)
[![GitHub stars](https://img.shields.io/github/stars/unixorn/awesome-zsh-plugins.svg)](https://github.com/unixorn/awesome-zsh-plugins/stargazers)
![Contributors](https://img.shields.io/github/contributors/unixorn/awesome-zsh-plugins.svg)
[![GitHub last commit](https://img.shields.io/github/last-commit/unixorn/awesome-zsh-plugins/main.svg)](https://github.com/unixorn/awesome-zsh-plugins)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/unixorn/awesome-zsh-plugins/)

A collection of ZSH frameworks, plugins, tutorials & themes inspired by the various awesome list collections out there.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

## Table of Contents

*   [Disclaimer](#disclaimer)
*   [Frameworks](#frameworks)
    *   [alf](#alf)
    *   [ansible-role-zsh](#ansible-role-zsh)
    *   [ant-zsh](#ant-zsh)
    *   [antibody](#antibody)
    *   [antidote](#antidote)
    *   [antigen-hs](#antigen-hs)
    *   [antigen](#antigen)
    *   [ax-zsh](#ax-zsh)
    *   [deer](#deer)
    *   [dotzsh](#dotzsh)
    *   [fresh](#fresh)
    *   [gh-source](#gh-source)
    *   [miniplug](#miniplug)
    *   [oh-my-zsh](#oh-my-zsh)
    *   [PMS](#pms)
    *   [prezto](#prezto)
    *   [pumice](#pumice)
    *   [ryzshrc](#ryzshrc)
    *   [sheldon](#sheldon)
    *   [shplug](#shplug)
    *   [TheFly](#thefly)
    *   [Toasty](#toasty)
    *   [uz](#uz)
    *   [x-cmd](#x-cmd)
    *   [yazt](#yazt)
    *   [yzsh](#yzsh)
    *   [zap](#zap)
    *   [zapack](#zapack)
    *   [zcomet](#zcomet)
    *   [zeesh](#zeesh)
    *   [zgem](#zgem)
    *   [zgen](#zgen)
    *   [zgenom](#zgenom)
    *   [zilsh](#zilsh)
    *   [zim](#zim)
    *   [Zinit](#zinit)
    *   [zinit-4](#zinit-4)
    *   [zit](#zit)
    *   [zlugin](#zlugin)
    *   [znap](#znap)
    *   [zoppo](#zoppo)
    *   [zpacker](#zpacker)
    *   [zpico](#zpico)
    *   [zplug](#zplug)
    *   [zpm](#zpm)
    *   [zr](#zr)
    *   [zshing](#zshing)
    *   [zsh-dot-plugin](#zsh-dot-plugin)
    *   [zsh-mgr](#zsh-mgr)
    *   [zshPlug](#zshplug)
    *   [ztanesh](#ztanesh)
    *   [ztheme](#ztheme)
    *   [ztupide](#ztupide)
    *   [zulu](#zulu)
*   [Setups](#setups)
    *   [zgenom](#zgenom-1)
    *   [zinit](#zinit)
*   [Prerequisites](#prerequisites)
*   [Tutorials](#tutorials)
    *   [Generic ZSH](#generic-zsh)
    *   [Antigen](#antigen)
    *   [Oh-My-Zsh](#oh-my-zsh)
    *   [Prezto](#prezto)
    *   [Zgen](#zgen)
    *   [Zinit (né zplugin)](#zinit-n%C3%A9-zplugin)
    *   [ZSH on Windows](#zsh-on-windows)
        *   [superconsole - Windows-only](#superconsole---windows-only)
*   [Plugins](#plugins)
*   [Completions](#completions)
*   [Themes](#themes)
*   [Fonts](#fonts)
*   [Installation](#installation)
    *   [Antigen](#antigen-1)
    *   [dotzsh](#dotzsh-1)
    *   [Oh-My-Zsh](#oh-my-zsh-1)
    *   [Prezto](#prezto-1)
    *   [Zgen](#zgen-1)
    *   [Zgenom](#zgenom)
    *   [zplug](#zplug-1)
    *   [zpm](#zpm-1)
*   [Writing New Plugins and Themes](#writing-new-plugins-and-themes)
*   [Other Resources](#other-resources)
    *   [ZSH Tools](#zsh-tools)
    *   [Other Useful Lists](#other-useful-lists)
    *   [Other References](#other-references)
*   [Thanks](#thanks)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

*Please read the [Contributing Guidelines](https://github.com/unixorn/awesome-zsh-plugins/blob/main/README.md/Contributing.md) before contributing.*

## Disclaimer

While I have done my best to not add entries with embedded malicious code, I don't have the time to sift through the source of every entry in the list.

THIS LIST IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

## Frameworks

These frameworks make customizing your ZSH setup easier.

You can find some interesting performance timing comparisons of various frameworks in the following locations.

*   [rossmacarthur/zsh-plugin-manager-benchmark (⭐98)](https://github.com/rossmacarthur/zsh-plugin-manager-benchmark) - Contains performance benchmarks for the most popular ZSH frameworks, including both install time and load time.
*   [pm-perf-test (⭐4)](https://github.com/z-shell/pm-perf-test) - Tooling for running performance tests on multiple ZSH frameworks.

### [alf (⭐115)](https://github.com/psyrendust/alf)

![GitHub last commit](https://img.shields.io/github/last-commit/psyrendust/alf) ![GitHub Repo stars](https://img.shields.io/github/stars/psyrendust/alf)

**Alf** is an out of this world super fast and configurable framework for ZSH; it's modeled after [Prezto (⭐14k)](https://github.com/sorin-ionescu/prezto) and [Antigen (⭐8.2k)](https://github.com/zsh-users/antigen) while utilizing [Oh-My-Zsh](https://ohmyz.sh) under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.

### [ansible-role-zsh (⭐354)](https://github.com/viasite-ansible/ansible-role-zsh)

![GitHub last commit](https://img.shields.io/github/last-commit/viasite-ansible/ansible-role-zsh) ![GitHub Repo stars](https://img.shields.io/github/stars/viasite-ansible/ansible-role-zsh)

**ansible-role-zsh** is an ansible role with zero-knowledge installation. It uses [antigen (⭐8.2k)](https://github.com/zsh-users/antigen) to manage bundles and [oh-my-zsh](https://github.com/unixorn/awesome-zsh-plugins/blob/main/README.md/ohmyz.sh). Can load bundles conditionally. By default it includes the powerlevel9k theme, autosuggestions, syntax-highlighting and [fzf-widgets (⭐90)](https://github.com/ytet5uy4/fzf-widgets) and [fzf-marks (⭐496)](https://github.com/urbainvaes/fzf-marks). Fully customizable.

### [ant-zsh (⭐31)](https://github.com/anthraxx/ant-zsh)

![GitHub last commit](https://img.shields.io/github/last-commit/anthraxx/ant-zsh)
![GitHub Repo stars](https://img.shields.io/github/stars/anthraxx/ant-zsh)

**Ant-zsh** is a tiny and lightweight ZSH configuration environment for special customization needs. It includes plugins, themes and a basic convenient setup.

### [antibody (⭐1.7k)](https://github.com/getantibody/antibody)

![GitHub last commit](https://img.shields.io/github/last-commit/getantibody/antibody)
![GitHub Repo stars](https://img.shields.io/github/stars/getantibody/antibody)

**Antibody** is a faster and simpler [antigen (⭐8.2k)](https://github.com/zsh-users/antigen) written in Golang. More details are available at <http://getantibody.github.io/>.

### [antidote](https://getantidote.github.io/)

![GitHub last commit](https://img.shields.io/github/last-commit/mattmc3/antidote)
![GitHub Repo stars](https://img.shields.io/github/stars/mattmc3/antidote)

**Antidote** is a ZSH plugin manager made from the ground up thinking about performance.

It is fast because it can do things concurrently, and generates an ultra-fast static plugin file that you can include in your ZSH config.

It is written natively in ZSH, is well tested, and picks up where [Antibody (⭐1.7k)](https://github.com/getantibody/antibody) left off.

[use-omz (⭐17)](https://github.com/getantidote/use-omz) enables easy use of [Oh-My-ZSH (⭐178k)](https://github.com/ohmyzsh/ohmyzsh) with antidote.

### [antigen-hs (⭐206)](https://github.com/Tarrasch/antigen-hs)

![GitHub last commit](https://img.shields.io/github/last-commit/Tarrasch/antigen-hs)
![GitHub Repo stars](https://img.shields.io/github/stars/Tarrasch/antigen-hs)

**antigen-hs** is a replacement for [antigen (⭐8.2k)](https://github.com/zsh-users/antigen) optimized for a low overhead when starting up a `zsh` session. It will automatically clone plugins for you.

### [antigen (⭐8.2k)](https://github.com/zsh-users/antigen)

![GitHub last commit](https://img.shields.io/github/last-commit/zsh-users/antigen)
![GitHub Repo stars](https://img.shields.io/github/stars/zsh-users/antigen)

**Antigen** is a small set of functions that help you easily manage your shell (ZSH) plugins, called bundles. The concept is pretty much the same as bundles in a typical vim+pathogen setup. Antigen is to ZSH, what Vundle is to vim. Antigen can load oh-my-zsh themes and plugins and will automatically clone them for you.

### [ax-zsh (⭐24)](https://github.com/alexbarton/ax-zsh)

![GitHub last commit](https://img.shields.io/github/last-commit/alexbarton/ax-zsh)
![GitHub Repo stars](https://img.shields.io/github/stars/alexbarton/ax-zsh)

**Ax-ZSH** is a modular configuration system for ZSH. It provides sane defaults and is extendable by plugins.

**Ax-ZSH** integrates well with [Powerlevel10k (⭐49k)](https://github.com/romkatv/powerlevel10k) and other extensions, including plugins compatible with [oh-my-zsh](https://ohmyz.sh/).

### [deer (⭐5)](https://github.com/ArtixLabs/deer)

![GitHub last commit](https://img.shields.io/github/last-commit/ArtixLabs/deer)
![GitHub Repo stars](https://img.shields.io/github/stars/ArtixLabs/deer)

A minimalist ZSH plugin manager.

### [dotzsh (⭐227)](https://github.com/dotphiles/dotzsh)

![GitHub last commit](https://img.shields.io/github/last-commit/dotphiles/dotzsh)
![GitHub Repo stars](https://img.shields.io/github/stars/dotphiles/dotzsh)

**Dotzsh** strives to be platform and version independent. Some functionality may be lost when running under older versions of ZSH, but it should degrade cleanly and allow you to use the same setup on multiple machines of differing OSes without problems.

### [fresh (⭐1.2k)](https://github.com/freshshell/fresh)

![GitHub last commit](https://img.shields.io/github/last-commit/freshshell/fresh)
![GitHub Repo stars](https://img.shields.io/github/stars/freshshell/fresh)

**fresh** is a tool to source shell configuration (aliases, functions, etc) from others into your own configuration files. We also support files such as ackrc and gitconfig. Think of it as [Bundler](https://bundler.io) for your dot files.

### [gh-source (⭐5)](https://github.com/Yarden-zamir/gh-source)

![GitHub last commit](https://img.shields.io/github/last-commit/Yarden-zamir/gh-source) ![GitHub Repo stars](https://img.shields.io/github/stars/Yarden-zamir/gh-source)

**gh-source** is a plugin manager for people who don't like plugin managers. It's a simple shell function that downloads and installs plugins from GitHub as part of the sourcing step. It's designed to be used with `zsh`, but it should work with any shell.

### [miniplug](https://sr.ht/~yerinalexey/miniplug)

![GitHub last commit](https://img.shields.io/github/last-commit/yerinalexey/miniplug) ![GitHub Repo stars](https://img.shields.io/github/stars/yerinalexey/miniplug)

**miniplug** is a minimalistic plugin manager for ZSH.

*   No crashes or double plugin loading when re-sourcing `.zshrc`
*   Unlike other frameworks, Miniplug does not pollute your `$PATH`
*   Only does the bare minimum for managing plugins

### [oh-my-zsh](https://ohmyz.sh/)

![GitHub last commit](https://img.shields.io/github/last-commit/ohmyzsh/ohmyzsh) ![GitHub Repo stars](https://img.shields.io/github/stars/ohmyzsh/oh-my-zsh)

**oh-my-zsh** is a community-driven framework for managing your ZSH configuration. Includes 120+ optional plugins (rails, `git`, macOS, `hub`, `capistrano`, `brew`, `ant`, MacPorts, etc), over 120 themes to spice up your morning, and an auto-update tool that makes it easy to keep up with the latest updates from the community.

### [PMS (⭐15)](https://github.com/JoshuaEstes/pms)

![GitHub last commit](https://img.shields.io/github/last-commit/JoshuaEstes/pms)
![GitHub Repo stars](https://img.shields.io/github/stars/JoshuaEstes/pms)

PMS allows you to manage your shell in a way to that helps decrease setup time and increases your productivity. It has support for themes (change the way your shell looks), plugins (adds functionality to your shell), and dotfile management.

The PMS framework also allows you to use the same framework in different shells. Use ZSH on your personal laptop, and use `bash` on remote servers. Wanna try `fish`? Go ahead, try out different shells.

### [prezto (⭐14k)](https://github.com/sorin-ionescu/prezto)

![GitHub last commit](https://img.shields.io/github/last-commit/sorin-ionescu/prezto)
![GitHub Repo stars](https://img.shields.io/github/stars/sorin-ionescu/prezto)

**Prezto** enriches the ZSH command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes. There are some [prezto (⭐14k)](https://github.com/sorin-ionescu/prezto)-specific plugins at [https://github.com/belak/prezto-contrib (⭐123)](https://github.com/belak/prezto-contrib).

### [pumice (⭐8)](https://github.com/ryutamaki/pumice)

![GitHub last commit](https://img.shields.io/github/last-commit/ryutamaki/pumice)
![GitHub Repo stars](https://img.shields.io/github/stars/ryutamaki/pumice)

**Pumice** is a lightweight plugin manager for ZSH.

### [ryzshrc (⭐4)](https://github.com/ryzshrc/ryzshrc)

![GitHub last commit](https://img.shields.io/github/last-commit/ryzshrc/ryzshrc)
![GitHub Repo stars](https://img.shields.io/github/stars/ryzshrc/ryzshrc)

ryzshrc is a smart, innovative plugin manager like [Oh My Zsh](https://ohmyz.sh/), designed to enhance your terminal experience with professional and cool features. It boosts productivity by providing efficient shell management, sleek themes, and powerful plugins. Perfect for developers seeking a modern and intelligent way to work with their terminal

### [sheldon (⭐1.2k)](https://github.com/rossmacarthur/sheldon)

![GitHub last commit](https://img.shields.io/github/last-commit/rossmacarthur/sheldon)
![GitHub Repo stars](https://img.shields.io/github/stars/rossmacarthur/sheldon)

A fast, configurable, shell plugin manager.

*   Can manage
    *   Any `git` repository.
        *   Branch/tag/commit support.
        *   Extra support for GitHub repositories.
        *   Extra support for Gists.
    *   Arbitrary remote files, simply specify the URL.
    *   Local plugins, simply specify the directory path.
*   Highly configurable install methods using [handlebars](http://handlebarsjs.com/) templating.
*   Super-fast parallel installation.
*   Configuration file using [TOML (⭐20k)](https://github.com/toml-lang/toml) syntax.
*   Uses a lock file for much faster loading of plugins.

### [shplug (⭐21)](https://github.com/dtrugman/shplug)

![GitHub last commit](https://img.shields.io/github/last-commit/dtrugman/shplug)
![GitHub Repo stars](https://img.shields.io/github/stars/dtrugman/shplug)

An easy solution for managing your shell environments. Works with both `bash` and `zsh`. Makes it easy to sync your environment across multiple machines with a `git` repository.

### [TheFly (⭐4)](https://github.com/joknarf/thefly)

![GitHub last commit](https://img.shields.io/github/last-commit/joknarf/thefly) ![GitHub Repo stars](https://img.shields.io/github/stars/joknarf/thefly)

`bash`/`zsh`/`ksh` plugin manager and env teleporter

Makes your shell env and plugins available everywhere (hosts/users)!

### [Toasty (⭐16)](https://github.com/CosmicToast/toasty-zsh)

![GitHub last commit](https://img.shields.io/github/last-commit/CosmicToast/toasty-zsh) ![GitHub Repo stars](https://img.shields.io/github/stars/CosmicToast/toasty-zsh)

**Toasty** is a ZSH framework made to facilitate management, not dictate it.

### [uz (⭐15)](https://github.com/maxrodrigo/uz)

![GitHub last commit](https://img.shields.io/github/last-commit/maxrodrigo/uz)
![GitHub Repo stars](https://img.shields.io/github/stars/maxrodrigo/uz)

A ZSH micro plugin manager.

### [x-cmd (⭐2k)](https://github.com/x-cmd/x-cmd)

![GitHub last commit](https://img.shields.io/github/last-commit/x-cmd/x-cmd)
![GitHub Repo stars](https://img.shields.io/github/stars/x-cmd/x-cmd)

**x-cmd** is a toolset implemented using posix shell and awk.It is very small in size and offers many interesting features. Here is a milestone demo: <https://x-cmd.com/>

Tools Provided by x-cmd:

*   [Wrappers for Common Commands (e.g., cd, ip, ps, tar, apt, brew)](https://x-cmd.com/mod/zuz): These wrapped commands are more intelligent and easier to use compared to the native commands.
*   [Lightweight Package Management Tool](https://x-cmd.com/pkg/): We have implemented a lightweight package management tool using shell and awk. Through it, you can quickly obtain most common software tools, such as jq, 7za, bat, nvim, python, node, go, etc.
*   [CLI for Useful Websites (e.g., github.com, cht.sh)](https://x-cmd.com/mod/cht): We have wrapped their APIs using shell and awk for daily use and to obtain corresponding services in scripts.
*   [AI Tools](https://x-cmd.com/mod/openai): We provide CLIs for ChatGPT, Gemini, Jina.ai, etc., and have wrapped corresponding shortcut commands for different application scenarios, such as `@gemini` for chatting with Gemini AI and `@zh` for using AI to translate specified content or command results.

### [yazt (⭐1)](https://github.com/bashelled/yazt)

![GitHub last commit](https://img.shields.io/github/last-commit/bashelled/yazt)
![GitHub Repo stars](https://img.shields.io/github/stars/bashelled/yazt)

**Yazt** is a simple ZSH theme manager in maintenance that is compatible with nearly everything. You can use prompts in plugins, mix 'n' match two themes and with a few modifications, you can even use it in `bash`.

### [yzsh (⭐1)](https://github.com/yunielrc/yzsh)

![GitHub last commit](https://img.shields.io/github/last-commit/yunielrc/yzsh)
![GitHub Repo stars](https://img.shields.io/github/stars/yunielrc/yzsh)

**yzsh** is a simple ZSH framework for managing plugins, themes, functions, aliases and environment variables.

### [zap (⭐1.1k)](https://github.com/zap-zsh/zap)

![GitHub last commit](https://img.shields.io/github/last-commit/zap-zsh/zap)
![GitHub Repo stars](https://img.shields.io/github/stars/zap-zsh/zap)

**zap** is a minimal ZSH plugin manager.

### [zapack (⭐7)](https://github.com/aiya000/zsh-zapack)

![GitHub last commit](https://img.shields.io/github/last-commit/aiya000/zsh-zapack)
![GitHub Repo stars](https://img.shields.io/github/stars/aiya000/zsh-zapack)

**zapack** is a basic fast minimal ZSH plugin loader.

### [zcomet (⭐211)](https://github.com/agkozak/zcomet)

![GitHub last commit](https://img.shields.io/github/last-commit/agkozak/zcomet)
![GitHub Repo stars](https://img.shields.io/github/stars/agkozak/zcomet)

**zcomet** is a minimalistic ZSH plugin manager that gets you to the prompt surprisingly quickly without caching (see the benchmarks). In addition to loading and updating plugins stored in `git` repositories, it supports lazy-loading plugins (further reducing startup time) as well as downloading and sourcing code snippets.

### [zeesh (⭐47)](https://github.com/zeekay/zeesh)

![GitHub last commit](https://img.shields.io/github/last-commit/zeekay/zeesh)
![GitHub Repo stars](https://img.shields.io/github/stars/zeekay/zeesh)

**Zeesh** is a cross-platform ZSH framework. It's similar to, but incompatible with, [oh-my-zsh](http://ohmyz.sh/). It has a modular plugin architecture making it easy to extend. It has a rich set of defaults, but is designed to be as lightweight as possible.

### [zgem (⭐11)](https://github.com/qoomon/zgem)

![GitHub last commit](https://img.shields.io/github/last-commit/qoomon/zgem)
![GitHub Repo stars](https://img.shields.io/github/stars/qoomon/zgem)

**zgem** is a plugin manager for ZSH that supports loading and updating plugins and themes from git, http and local files.

### [zgen (⭐1.5k)](https://github.com/tarjoilija/zgen)

![GitHub last commit](https://img.shields.io/github/last-commit/tarjoilija/zgen)
![GitHub Repo stars](https://img.shields.io/github/stars/tarjoilija/zgen)

**Zgen is currently not being actively maintained** and I recommend you use the [zgenom (⭐388)](https://github.com/jandamm/zgenom) fork instead, which is actively maintained and continues to get new features.

**Zgen** is a lightweight plugin manager for ZSH inspired by [Antigen (⭐8.2k)](https://github.com/zsh-users/antigen). The goal is to have minimal overhead when starting up the shell because nobody likes waiting.

### [zgenom (⭐388)](https://github.com/jandamm/zgenom)

![GitHub last commit](https://img.shields.io/github/last-commit/jandamm/zgenom)
![GitHub Repo stars](https://img.shields.io/github/stars/jandamm/zgenom)

A lightweight plugin manager for ZSH that is a fork that extends the brilliant [zgen (⭐1.5k)](https://github.com/tarjoilija/zgen) and provides more features and bugfixes while being fully backwards compatible.

To keep loading fast during new terminal sessions, `zgenom` generates a static `init.zsh` file which does nothing but source your plugins and append them to your `fpath`.

This minimizes startup time by not having to execute time consuming logic (plugin checking, updates, etc) during every shell session's startup. The downside is that you have to refresh the init script manually with `zgenom reset` whenever you update your plugin list in your `.zshrc`.

Zgenom can load [oh-my-zsh](http://ohmyz.sh/)-compatible and [prezto (⭐14k)](https://github.com/sorin-ionescu/prezto)-compatible plugins and themes, and will automagically `git clone` plugins for you when you add them to your plugin list.

### [zilsh (⭐31)](https://github.com/zilsh/zilsh)

![GitHub last commit](https://img.shields.io/github/last-commit/zilsh/zilsh)
![GitHub Repo stars](https://img.shields.io/github/stars/zilsh/zilsh)

**zilsh** is a ZSH config system that aims to appeal more to power-users and follow the simplistic approach of vim-pathogen.

### [zim (⭐4.1k)](https://github.com/zimfw/zimfw)

![GitHub last commit](https://img.shields.io/github/last-commit/zimfw/zimfw)
![GitHub Repo stars](https://img.shields.io/github/stars/zimfw/zimfw)

**Zim** is a ZSH configuration framework with blazing speed and modular extensions.

### [Zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit)

![GitHub last commit](https://img.shields.io/github/last-commit/zdharma-continuum/zinit) ![GitHub Repo stars](https://img.shields.io/github/stars/zdharma-continuum/zinit)

**Zinit** is an innovative and probably (because of the Turbo) the fastest plugin manager with support for:

*   Turbo mode – 80% faster ZSH startup! for example: instead of 200 ms, it'll be 40 ms
*   Completion management (selectively disable and enable completions)
*   Snippets (↔ regular files downloaded via-URL, e.g.: scripts) and through them Oh My Zsh and Prezto plugins support (→ low overhead)
*   Annexes (↔ Zinit extensions)
*   Reports (from the plugin loads – plugins are no longer black boxes)
*   Plugin unloading (allows e.g.: dynamic theme switching)
*   `bindkey` capturing and remapping
*   packages
*   Clean `fpath` (the array `$fpath` is not being used to add completions and autoload functions, hence it stays concise, not bloated)
*   Services ↔ a single-instance, background plugins
*   Also, in general: all the mechanisms from the ZSH Plugin Standard – Zinit is a reference implementation of the standard.

The project is very active – currently > 3100 commits.

### [zinit-4 (⭐28)](https://github.com/psprint/Zinit-4)

![GitHub last commit](https://img.shields.io/github/last-commit/psprint/Zinit-4)
![GitHub Repo stars](https://img.shields.io/github/stars/psprint/Zinit-4)

This is Zinit 4 from the [original author](https://github.com/psprint), who once removed the [Zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit) repository from GitHub. This spawned a community-driven [zdharma-continuum](https://github.com/zdharma-continuum) organization that revived all of psprint's ZSH projects. Its main innovations from the @zdharma-continuum fork are:

*   AppImage distribution (release link),
*   Action complete – press Alt-Shift-A and Alt-Shift-C to complete plugin names and ice modifiers,
*   Themes – set $ZITHEME to one of default, blue and gold to set a color set to use for Zinit 4 messages,
*   New ice `build` which is equivalent of three other ices: `null`, `configure` and `make install` and simply builds the project from sources, with support for autotools/CMake/Meson/Scons.

These are the most visible changes, but there are more (like e.g.: support for compiling with libraries from previously built projects/`$ZPFX`).

### [zit (⭐25)](https://github.com/thiagokokada/zit)

![GitHub last commit](https://img.shields.io/github/last-commit/thiagokokada/zit)
![GitHub Repo stars](https://img.shields.io/github/stars/thiagokokada/zit)

**zit** is a plugin manager for ZSH. It is minimal because it implements the bare minimum to be qualified as a plugin manager: it allows the user to install plugins from `git` repositories (and `git` repositories only, that's why the name), source plugins and update them. It does not implement fancy functions like cleanup of removed plugins, automatic compilation of installed plugins, alias for oh-my-zsh/prezto/other ZSH frameworks, building binaries, `$PATH` manipulation and others.

### [zlugin (⭐3)](https://github.com/DrgnFireYellow/zlugin)

![GitHub last commit](https://img.shields.io/github/last-commit/DrgnFireYellow/zlugin)
![GitHub Repo stars](https://img.shields.io/github/stars/DrgnFireYellow/zlugin)

**zlugin** is a very lightweight ZSH plugin manager.

### [znap (⭐1.4k)](https://github.com/marlonrichert/zsh-snap)

![GitHub last commit](https://img.shields.io/github/last-commit/marlonrichert/zsh-snap) ![GitHub Repo stars](https://img.shields.io/github/stars/marlonrichert/zsh-snap)

**:zap:Znap** is a light-weight plugin manager & `git` repository manager for ZSH that's easy to grok. While tailored for ZSH plugins specifically, **Znap** also functions as a general-purpose utility for managing `git` repositories.

Znap can:

*   Make any prompt appear instantly. Reduce your startup time from \~200ms to \~40ms with just one command.
*   Asynchronously compile your plugins and functions.
*   Cache those expensive `eval $(commands)`.
*   Clone or pull multiple repos in parallel.
*   Re-clone all your repos without you having to re-enter them.
*   Multi-repo management
*   Automatic `compinit` and `bashinit` - you no longer need them in your `.zshrc`, znap will do them automatically as needed.

### [zoppo (⭐34)](https://github.com/zoppo/zoppo)

![GitHub last commit](https://img.shields.io/github/last-commit/zoppo/zoppo)
![GitHub Repo stars](https://img.shields.io/github/stars/zoppo/zoppo)

**Zoppo** is the crippled configuration framework for ZSH. As an Italian saying goes: "chi va con lo zoppo, impara a zoppicare", we realized we were walking with a cripple and are now going to become crippled ourselves.

### [zpacker (⭐2)](https://github.com/happyslowly/zpacker)

![GitHub last commit](https://img.shields.io/github/last-commit/happyslowly/zpacker)
![GitHub Repo stars](https://img.shields.io/github/stars/happyslowly/zpacker)

**Zpacker** is a lightweight ZSH plugin & theme management framework.

### [zpico (⭐5)](https://github.com/thornjad/zpico)

![GitHub last commit](https://img.shields.io/github/last-commit/thornjad/zpico)
![GitHub Repo stars](https://img.shields.io/github/stars/thornjad/zpico)

The minuscule ZSH package manager. No frills, no bloat, just 2 kB of 100% ZSH code, providing complete package management for your ZSH environment.

ZSH package managers are abundant, but most are bloated, slow or have excessive requirements. On top of that, more than a few have been abandoned for years. Zpico does not seek to be the best of the best, rather to balance functionality against a tiny, fast footprint.

### [zplug (⭐5.9k)](https://github.com/zplug/zplug)

![GitHub last commit](https://img.shields.io/github/last-commit/zplug/zplug)
![GitHub Repo stars](https://img.shields.io/github/stars/zplug/zplug)

**:hibiscus: Zplug** is a next-generation ZSH plugin manager.

*   Can manage everything
    *   ZSH plugins/UNIX commands on [GitHub](https://github.com) and [Bitbucket](https://bitbucket.org)
    *   Gist files ([gist.github.com](https://gist.github.com/discover))
    *   Externally managed plugins e.g., [oh-my-zsh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh) and [prezto (⭐14k)](https://github.com/sorin-ionescu/prezto) plugins/themes
    *   Binary artifacts on [GitHub Releases](https://help.github.com/articles/about-releases/)
    *   Local plugins
    *   etc. (you can add your [own sources (⭐5.9k)](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
*   Super-fast parallel installation/update
*   Support for lazy-loading
*   Branch/tag/commit support
*   Post-update, post-load hooks
*   Dependencies between packages
*   Unlike [antigen (⭐8.2k)](https://github.com/zsh-users/antigen), no ZSH plugin files (`*.plugin.zsh`) are required
*   Interactive interface ([fzf (⭐70k)](https://github.com/junegunn/fzf), [peco (⭐7.7k)](https://github.com/peco/peco), [zaw (⭐576)](https://github.com/zsh-users/zaw), and so on)
*   Cache mechanism for reducing [the startup time (⭐5.9k)](https://github.com/zplug/zplug#vs)

### [zpm (⭐369)](https://github.com/zpm-zsh/zpm)

![GitHub last commit](https://img.shields.io/github/last-commit/zpm-zsh/zpm)
![GitHub Repo stars](https://img.shields.io/github/stars/zpm-zsh/zpm)

**zpm** ( ZSH Plugin Manager ) is a plugin manager for [ZSH](http://www.zsh.org/) which combines the imperative and declarative approach. At first run, zpm will do complex logic and generate a cache, after that will only use the cache, so it makes this framework very fast.

*   Fastest plugin manager (Really, after the first run, zpm will not be used at all)
*   Support for async loading
*   Dependencies between packages
*   **zpm** runs on Linux, macOS, FreeBSD and Android.
*   **zpm** plugins are compatible with [oh-my-zsh](http://ohmyz.sh/).

### [zr (⭐187)](https://github.com/jedahan/zr)

![GitHub last commit](https://img.shields.io/github/last-commit/jedahan/zr)
![GitHub Repo stars](https://img.shields.io/github/stars/jedahan/zr)

**zr** is a quick, simple ZSH plugin manager written in Rust and easily installable with `cargo install zr`.

### [zshing (⭐7)](https://github.com/zakariaGatter/zshing)

![GitHub last commit](https://img.shields.io/github/last-commit/zakariaGatter/zshing)
![GitHub Repo stars](https://img.shields.io/github/stars/zakariaGatter/zshing)

**zshing** is a ZSH plugin manager similar to Vundle/Vim and allows you to...

*   Keep track of and configure your plugins right in the `.zshrc`
*   Install ZSH plugins
*   Update ZSH plugins
*   Search by name all available ZSH Plugins
*   Clean unused plugins up
*   Run the above actions in a *single command*
*   Manages the **Source Plugins** of your installed Plugins

### [zsh-dot-plugin (⭐4)](https://github.com/DuckzCantFly/zsh-dot-plugin)

![GitHub last commit](https://img.shields.io/github/last-commit/DuckzCantFly/zsh-dot-plugin) ![GitHub Repo stars](https://img.shields.io/github/stars/DuckzCantFly/zsh-dot-plugin)

Customize your `.zshrc` with only \~21 lines of code. Based on [zsh-unplugged (⭐429)](https://github.com/mattmc3/zsh_unplugged).
![GitHub last commit](https://img.shields.io/github/last-commit/mattmc3/zsh_unplugged)
![GitHub Repo stars](https://img.shields.io/github/stars/mattmc3/zsh_unplugged)

### [zsh-mgr (⭐4)](https://github.com/amt911/zsh-mgr)

![GitHub last commit](https://img.shields.io/github/last-commit/amt911/zsh-mgr)
![GitHub Repo stars](https://img.shields.io/github/stars/amt911/zsh-mgr)

A simple plugin manager for zsh. Features:

*   Auto-updates all plugins.
*   Auto-updates itself.
*   Configurable time interval for both auto-updaters.

### [zshPlug (⭐0)](https://github.com/Atlas34/zshPlug)

![GitHub last commit](https://img.shields.io/github/last-commit/Atlas34/zshPlug)
![GitHub Repo stars](https://img.shields.io/github/stars/Atlas34/zshPlug)

**zshPlug** is a minimalist plugin manager heavily based on [zap (⭐1.1k)](https://github.com/zap-zsh/zap).

### [ztanesh (⭐271)](https://github.com/miohtama/ztanesh)

![GitHub last commit](https://img.shields.io/github/last-commit/miohtama/ztanesh)
![GitHub Repo stars](https://img.shields.io/github/stars/miohtama/ztanesh)

**Ztanesh** aims to improve your UNIX command line experience and productivity with the the configuration provided by the ztanesh project: the tools will make your shell more powerful and easier to use.

### [ztheme (⭐5)](https://github.com/SkyyySi/ztheme)

![GitHub last commit](https://img.shields.io/github/last-commit/SkyyySi/ztheme)
![GitHub Repo stars](https://img.shields.io/github/stars/SkyyySi/ztheme)

**ztheme** is a small and fast theme engine for ZSH.

### [ztupide (⭐8)](https://github.com/mpostaire/ztupide)

![GitHub last commit](https://img.shields.io/github/last-commit/mpostaire/ztupide)
![GitHub Repo stars](https://img.shields.io/github/stars/mpostaire/ztupide)

A simple and fast ZSH plugin manager. It uses `zcompile` and async loading to speed up your shell startup time.

### [zulu (⭐154)](https://github.com/zulu-zsh/zulu)

![GitHub last commit](https://img.shields.io/github/last-commit/zulu-zsh/zulu)
![GitHub Repo stars](https://img.shields.io/github/stars/zulu-zsh/zulu)

**Zulu** is a environment manager for ZSH 5 or later, which aims to make it easy to manage your shell without writing any code.

*   Easily manage your shell environment without editing files.
*   Create aliases, functions and environment variables, and have them available to you at the next shell startup.
*   Add and remove directories from `$path`, `$fpath` and `$cdpath` with simple commands.
*   Install packages, plugins and themes easily, and have them available to you immediately.

## Setups

This section is for full setup dropins - they aren't frameworks, but they're not simple plugins/themes either.

### zgenom

*   [zsh-quickstart-kit (⭐820)](https://github.com/unixorn/zsh-quickstart-kit) - A simple quickstart for using ZSH with [zgenom (⭐388)](https://github.com/jandamm/zgenom). This automatically configures ZSH to use [zgenom (⭐388)](https://github.com/jandamm/zgenom) to load a curated (but easily customizable) collection of plugins and periodically automatically update itself, the plugins, and the quickstart kit itself.

### zinit

*   [ZPWR (⭐197)](https://github.com/MenkeTechnologies/zpwr) - An extremely powerful custom terminal environment built on top of [Zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit) for maximum speed.  A full terminal configuration framework including `zsh`, `tmux`, `fzf`, `vim` and spacemacs configurations.  It includes:

*   12.9k+ tab completions

*   1.9k+ aliases

*   330+ git aliases

*   400+ zpwr subcommands

*   2.8k functions

*   175+ zpwr environment variables

*   175+ perl, python, bash, ZSH scripts

*   2.8k line README.md

*   50k+ LOC

*   1 line install

## Prerequisites

If you're on a Mac, the `zsh` that comes with it is usually pretty stale. You can use `brew install zsh` to update it.

Many of the themes here use special glyphs for things like displaying a branch icon. You'll need to use a [Nerd Font (⭐57k)](https://github.com/ryanoasis/nerd-fonts) or a Powerline-compatible font in your terminal program or you'll see ugly broken boxes where the symbols should be.

Here are a few good sources for Nerd Fonts and Powerline-compatible fonts:

*   [Awesome Terminal Fonts (⭐2.5k)](https://github.com/gabrielelana/awesome-terminal-fonts) - A family of fonts that include some nice monospaced Icons.
*   [Cascadia Code (⭐27k)](https://github.com/microsoft/cascadia-code) - Microsoft's Cascadia Code
*   [Fantasque Awesome Font (⭐36)](https://github.com/ztomer/fantasque_awesome_powerline) - A nice monospaced font, patched with Font-Awesome, Octoicons, and Powerline-Glyphs.
*   [Fira Mono (⭐5.1k)](https://github.com/mozilla/Fira) - Mozilla's Fira type family.
*   [Hack](http://sourcefoundry.org/hack/) - Another Powerline-compatible font designed for source code and terminal usage.
*   [Input Mono](https://input.djr.com/) - A family of fonts designed specifically for code. It offers both monospaced and proportional fonts and includes Powerline glyphs.
*   [Iosevka](https://be5invis.github.io/Iosevka/) - Iosevka is an open source slender monospace sans-serif and slab-serif typeface inspired by [Pragmata Pro](http://www.fsd.it/fonts/pragmatapro.htm), M+ and [PF DIN Mono](https://www.myfonts.com/fonts/parachute/pf-din-mono/), designed to be the ideal font for programming.
*   [Monoid](http://larsenwork.com/monoid/) - Monoid is customizable and optimized for coding with bitmap-like sharpness at 15px line-height even on low res displays.
*   [Mononoki](https://madmalik.github.io/mononoki/) - Mononoki is a typeface by Matthias Tellen, created to enhance code formatting.
*   [More Nerd Fonts](https://www.nerdfonts.com/font-downloads) - Another site to download nerd fonts.
*   [Nerd fonts (⭐57k)](https://github.com/ryanoasis/nerd-fonts) - A collection of over 20 patched fonts (over 1,700 variations) & the fontforge font patcher python script for Powerline, devicons, and vim-devicons: includes Droid Sans, Meslo, AnonymousPro, ProFont, Inconsolta, and many more. These can be installed with `brew` - do `brew tap homebrew/cask-fonts && brew install --cask fontname`
*   [Powerline patched font collection (⭐26k)](https://github.com/powerline/fonts) - A collection of a dozen or so fonts patched to include Powerline glyphs.
*   [Spacemono (⭐393)](https://github.com/googlefonts/spacemono) - Google's new original monospace display typeface family.
*   [Victor Mono](https://rubjo.github.io/victor-mono/) - Victor Mono is a free programming font with semi-connected cursive italics, symbol ligatures (!=, ->>, =>, ===, <=, >=, ++) and Latin, Cyrillic and Greek characters.

## Tutorials

### Generic ZSH

*   [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - Tutorial using a combination of [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto (⭐14k)](https://github.com/sorin-ionescu/prezto), [Tmux](https://tmux.github.io), and [Tmuxinator (⭐13k)](https://github.com/tmuxinator/tmuxinator) to make for an extremely productive developer workflow.
*   [A Guide to ZSH Completion With Examples](https://thevaluable.dev/zsh-completion-guide-examples/) - Explains ZSH autocompletion configuration with examples.
*   [adamnorwood-zsh (⭐11)](https://github.com/adamnorwood/adamnorwood-zsh/) - A minimalist but readable ZSH setup based on [oh-my-posh](https://ohmyposh.dev/).
*   [Arch Linux's ZSH introduction](https://wiki.archlinux.org/index.php/zsh) -  Not actually Arch or Linux-specific.
*   [GH (⭐68)](https://github.com/gustavohellwig/gh-zsh) - Setup ZSH on debian/Ubuntu-based linuxes. Installs [Powerlevel10k (⭐49k)](https://github.com/romkatv/powerlevel10k), [zsh-completions (⭐7.3k)](https://github.com/zsh-users/zsh-completions), [zsh-autosuggestions (⭐33k)](https://github.com/zsh-users/zsh-autosuggestions), [fast-syntax-highlighting (⭐1.3k)](https://github.com/zdharma-continuum/fast-syntax-highlighting/), and more.
*   [How To Make an Awesome Custom Shell with ZSH](https://linuxstans.com/how-to-make-an-awesome-custom-shell-with-zsh/) - A beginner-friendly tutorial on how to install and configure a ZSH shell.
*   [commandlinepoweruser.com](https://commandlinepoweruser.com/) - Wes Bos' videos introducing ZSH and oh-my-zsh.
*   [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) - covers some of the features that ZSH has that Bash doesn't, and using oh-my-zsh.
*   [Profiling ZSH](https://ellie.wtf/notes/profiling-zsh) - Good article about profiling your ZSH setup to optimize startup time.
*   [rs-example (⭐8)](https://github.com/al-jshen/zshplug-rs-example) - An example plugin showing how a Rust program can listen to and process commands from ZSH.
*   [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - slideshare presentation.
*   [zephyr (⭐156)](https://github.com/mattmc3/zephyr) - Zephyr uses built-in Zsh features to set up better default options, completions, keybindings, history, and much more.
*   [ZSH for Humans (⭐1.9k)](https://github.com/romkatv/zsh4humans) - A turnkey configuration for ZSH that aims to work really well out of the box. It combines a curated set of ZSH plugins into a coherent whole that feels like a finished product rather than a DIY starter kit.
*   [ZSH Pony (⭐180)](https://github.com/mika/zsh-pony) - Covers customizing ZSH without a framework.
*   [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - An exhaustive list of ZSH tips by Christian Schneider.
*   [ZSH Setup by Easy-Cloud-in (⭐2)](https://github.com/Easy-Cloud-in/zsh-setup) - A powerful Zsh environment setup with Oh My Posh themes, essential plugins, and advanced search capabilities. This repository provides scripts to automatically configure your terminal with modern features and aesthetics. Requires a Debian or Ubuntu based system.
*   [ZSH Unplugged (⭐429)](https://github.com/mattmc3/zsh_unplugged) - Good resource if you want to eliminate using a framework but still easily use plugins.

### Antigen

*   [belak/zsh-utils (⭐187)](https://github.com/belak/zsh-utils) - A minimal set of ZSH plugins designed to be low-friction and low-complexity.
*   [mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) - Michael Maclean's article about switching from oh-my-zsh to antigen.
*   [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis' introduction to Antigen.

### Oh-My-Zsh

*   [Configuration to use Hyper.js as a ZSH terminal with a Windows Subsystem Linux on windows 10, with Oh My Zsh and the Powerlevel10k theme (⭐7)](https://github.com/jkergal/hyperjs-wsl-zsh-powerlevel10k-config-on-windows/) - How-to for getting Oh-My-ZSH running on WSL.
*   [Getting started with oh-my-zsh](https://medium.com/@dienbui/using-oh-my-zsh-f65be6460d3f) - A beginners guide to oh-my-zsh by Dien Bui
*   [How to Install and Configure Z Shell in Ubuntu (⭐4)](https://github.com/profpan396/how-to-install-and-configure-zshell) - Amar Pan's article will walk you through the process of installing and configuring ZSH, including how to change themes and enable the time-saving autosuggestions plug-in.
*   [iTerm2 + Oh-My-ZSH: Supercharge Your Mac Terminal](https://catalins.tech/improve-mac-terminal) - Catalin Pit's tutorial on getting started with Oh-My-ZSH on macOS.
*   [Learn Zsh in 80 Minutes macOS](https://www.youtube.com/watch?v=MSPu-lYF-A8) - A beginners guide to using Oh My Zsh on macOS by Karl Hadwen
*   [Oh-My-Zsh! A Work of CLI Magic](https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb) - Michiel Mulders installation guide for Ubuntu
*   [One Key Linux Setup (⭐21)](https://github.com/miracleyoo/one-key-linux-setup) - Simple setup (ubuntu-only) of `zsh`, `oh-my-zsh`, `tmux`, `python` support and other packages.

### Prezto

*   [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss' blog post about using Prezto, [Tmux](https://tmux.github.io) & Tmuxinator.
*   [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert's blog post on migrating to Prezto.

### Zgen

*   [rad-shell (⭐40)](https://github.com/brandon-fryslie/rad-shell) - A fantastically feature rich, lightning-fast shell setup, powered by [ZSH](http://www.zsh.org/), [Prezto (⭐14k)](https://github.com/sorin-ionescu/prezto), and [Zgen (⭐1.5k)](https://github.com/tarjoilija/zgen).

### Zinit (né zplugin)

*   [BlaCk-Void-Zsh (⭐349)](https://github.com/black7375/BlaCk-Void-Zsh) - :crystal\_ball: Awesome, customizable Zsh Starter Kit :stars::stars:. Includes powerline, [fzf (⭐70k)](https://github.com/junegunn/fzf) integration, Weather and image viewing in some terminals.
*   [zinit-configs (⭐61)](https://github.com/zdharma-continuum/zinit-configs) - Real-world configuration files (basically a collection of `.zshrc` files) holding [zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit) invocations.

### ZSH on Windows

#### [superconsole (⭐89)](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   `ConEmu`/`zsh` out-of-the-box configured to restore previously opened tabs and shell working directories after `ConEmu` restart
*   Choose between clean and inherited environment when starting new SuperConsole sessions
*   Custom colorful scheme, colorful output for various commands
*   `MSYS2` included, `zsh` and necessary software preinstalled, uses zsh-grml-config
*   Uses [Antigen (⭐8.2k)](https://github.com/zsh-users/antigen) for ZSH theme and config management
*   Enabled number of ZSH plugins to activate completion, highlighting and history for most comfortable use
*   Git-for-Windows repo with proper `git` and `git lfs` support for `MSYS2` environment is configured, `git` client already installed.
*   `ssh-agent` for `git` works out-of-box, add your keys to `ConEmu/msys64/ConEmu/msys64/home/user/.ssh` dir
*   Non-blocking ZSH prompt status updates thanks to [agkozak-zsh-prompt (⭐309)](https://github.com/agkozak/agkozak-zsh-prompt)
*   Command-not-found handler customized for `MSYS2` suggests what package to install
*   Sets up `nano` as main editor, enables `nano` syntax highlighting
*   Custom helper scripts added to `ConEmu/msys64/3rdparty`

## Plugins

*   [1password (⭐3)](https://github.com/agpenton/1password-zsh-plugin) - Adds [1Password](https://1password.com/) functionality including a `opswd` command that wraps the `op` command. It takes a service name as an argument and copies the password for that service to the clipboard.
*   [256color (⭐143)](https://github.com/chrissicool/zsh-256color) - Enhances the terminal environment with 256 colors. It looks at the chosen `TERM` environment variable and sees if there is respective ncurses' terminfo with 256 colors available. The result is a multicolor terminal, if available.
*   [abbr (olets) (⭐641)](https://github.com/olets/zsh-abbr) - Manages auto-expanding abbreviations that expand inline when you hit space, inspired by fish shell.
*   [abbr-path (⭐12)](https://github.com/felixgravila/zsh-abbr-path) - Adds functionality of the `theme_title_use_abbreviated_path` parameter from some oh-my-fish themes.
*   [abbrev-alias (⭐121)](https://github.com/momo-lab/zsh-abbrev-alias) - Provides functionality similar to `vim`'s abbreviation expansion.
*   [actiona (⭐4)](https://github.com/matthieusb/act) - Make it easier to call [actiona (⭐564)](https://github.com/Jmgr/actiona) scripts from your command line. Includes tab completions.
*   [activate-py-environment (⭐28)](https://github.com/se-jaeger/zsh-activate-py-environment) - Automagically detects and activates your python environments (`poetry`, `virtualenv` and `conda`) while traversing directories.
*   [adguard-helper (⭐0)](https://github.com/MohamedElashri/adguard-helper) - Simplies interaction with the [AdGuard VPN CLI (⭐98)](https://github.com/AdguardTeam/AdGuardVPNCLI). It provides user-friendly commands that reduce the need to remember complex flags and commands by offering a more intuitive interface.
*   [adonisjs (⭐0)](https://github.com/baliestri/adonisjs.plugin.zsh) - Plugin for skipping the `node` part of the `ace` command.
*   [ai-commands (⭐30)](https://github.com/muePatrick/zsh-ai-commands) - Asks GPT (gpt-4-turbo-preview) for CLI commands that achieve the described target action.
*   [airpods-battery (⭐8)](https://github.com/louis-thevenet/zsh-airpods-battery/) - Looks for AirPods via Bluetooth and puts their battery charge state into `$RPROMPT`.
*   [aish (⭐29)](https://github.com/chr15m/aish) - Instant shell script solutions from OpenAI right in your prompt.
*   [alacritty (⭐11)](https://github.com/casonadams/alacritty-shell) - Control [alacritty (⭐58k)](https://github.com/alacritty/alacritty/wiki/Color-schemes) color schemes.
*   [alehouse (⭐16)](https://github.com/sticklerm3/alehouse) - Contains short aliases for [brew](https://brew.sh) commands, inspired by `betterbrew`.
*   [alias-finder (⭐16)](https://github.com/akash329d/zsh-alias-finder) - Displays an alias when you use a command you have aliased previously. Helpful for remembering aliases you have defined in the past. Written as a pure ZSH script for speed.
*   [alias-maker (⭐9)](https://github.com/MefitHp/alias-maker) - Allows you to easily create and manage aliases from the command line.
*   [alias-tips (⭐794)](https://github.com/djui/alias-tips) - An [oh-my-zsh](https://ohmyz.sh/) plugin to help remembering those aliases you defined once.
*   [allclear (⭐1)](https://github.com/givensuman/zsh-allclear) - Clears the terminal when you cd into `$HOME`.
*   [allergen (⭐3)](https://github.com/stanislas/allergen) - A collection of custom ZSH plugins to use with Antigen.
*   [almostontop (⭐92)](https://github.com/Valiev/almostontop) - Clears previous command output every time before new command executed in shell. Inspired by the [alwaysontop (⭐203)](https://github.com/swirepe/alwaysontop) plugin for `bash`.
*   [alt-and-select (⭐6)](https://github.com/raisty/alt-and-select) - Binds the alt-c (copy), alt-v (paste), alt-x (cut) keyboard shortcut to a commands: copy-region-as-kill, yank, kill-region. Remaps the execute command to Alt-Shift-X.
*   [ansible (⭐14)](https://github.com/sparsick/ansible-zsh) - A plugin for [Ansible](https://www.ansible.com/).
*   [ansimotd (⭐65)](https://github.com/yuhonas/zsh-ansimotd) - Adds old-school cool ANSI art when a login shell starts.
*   [ansiweather (⭐1.9k)](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols.
*   [antidote-use-omz (⭐17)](https://github.com/getantidote/use-omz) - Make using [oh-my-zsh](https://ohmyz.sh/) with [antidote](https://getantidote.github.io/) seamless.
*   [antigen-git-rebase (⭐6)](https://github.com/smallhadroncollider/antigen-git-rebase) - Antigen/ZSH script to aid with `git` rebasing.
*   [anyframe (⭐193)](https://github.com/mollifier/anyframe) - A `peco`/`percol`/`fzf` wrapper plugin for ZSH.
*   [apache2 (⭐6)](https://github.com/voronkovich/apache2.plugin.zsh) - Adds aliases and functions for managing Apache2.
*   [apparix (⭐43)](https://github.com/micans/apparix) - Command line directory bookmarks with jumping to bookmarks, subdirectory tab completion, distant listing etc.
*   [apple-touchbar (⭐351)](https://github.com/zsh-users/zsh-apple-touchbar) - Adds MacBook Pro touchbar support in [iTerm 2](https://iterm2.com).
*   [appup (⭐17)](https://github.com/Cloudstek/zsh-plugin-appup) - Adds `start`, `stop`, `up` and `down` commands when it detects a `docker-compose.yml` or `Vagrantfile` in the current directory (e.g. your application). Just run `up` and get coding!
*   [apt (⭐6)](https://github.com/GeoLMg/apt-zsh-plugin) - For distros with `apt` package manager. Offers to install missing programs for you.
*   [arc-search (⭐1)](https://github.com/michaelsousajr/zsh-arc-search) - Enables quick searches using Arc browser directly from your terminal. Features URL encoding for search terms.
*   [arc (⭐6)](https://github.com/anton-rudeshko/zsh-arc) - Adds aliases for Yandex version control system.
*   [archlinux (fourdim) (⭐1)](https://github.com/fourdim/zsh-archlinux) - Defines helper functions for `pacman` on Arch Linux.
*   [archlinux (junker) (⭐10)](https://github.com/Junker/zsh-archlinux) - Based on the oh-my-zsh [archlinux (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/archlinux) plugin. Defines helper functions and aliases.
*   [arduino (⭐5)](https://github.com/raghur/zsh-arduino) - Adds scripts to build, upload and monitor arduino sketches from a command line. Requires [`jq`](https://stedolan.github.io/jq/).
*   [artisan (⭐633)](https://github.com/jessarcher/zsh-artisan) - Laravel `artisan` plugin for ZSH to help you to run `artisan` from anywhere in the project tree, with tab completion!
*   [asciidoctor (⭐5)](https://github.com/sparsick/asciidoctor-zsh) - A plugin for AsciiDoctor.
*   [asdf (kiurchv) (⭐14)](https://github.com/kiurchv/asdf.plugin.zsh) - Integration and completions for [asdf (⭐23k)](https://github.com/asdf-vm/asdf), the extendable version manager, with support for Ruby, Node.js, Elixir, Erlang and more.
*   [asdf (zimfw) (⭐11)](https://github.com/zimfw/asdf) - Initializes [asdf (⭐23k)](https://github.com/asdf-vm/asdf), installing it using `git` if not installed yet. Also, bypasses the shims if you're using the [direnv (⭐576)](https://github.com/asdf-community/asdf-direnv) plugin, as suggested by the plugin [pro-tips (⭐576)](https://github.com/asdf-community/asdf-direnv/#pro-tips).
*   [asdf-direnv (⭐12)](https://github.com/redxtech/zsh-asdf-direnv) - Integration and completions for [asdf (⭐23k)](https://github.com/asdf-vm/asdf) and [direnv (⭐576)](https://github.com/asdf-community/asdf-direnv).
*   [asdf-prompt (⭐8)](https://github.com/CurryEleison/zsh-asdf-prompt) - Provides a function usable in prompts that displays version information for your current tool versions.
*   [ask (⭐73)](https://github.com/Licheam/zsh-ask) - Serves as a ChatGPT API frontend, enabling you to interact with ChatGPT directly from the ZSH shell using only `cURL` and `jq`.
*   [assume-role (⭐6)](https://github.com/weizard/assume-role) - Allows you to assume AWS IAM roles easily. Includes completions.
*   [async (⭐788)](https://github.com/mafredri/zsh-async) - Library for running asynchronous tasks in ZSH without requiring any external tools. Allows you to run multiple asynchronous jobs, enforce unique jobs (multiple instances of the same job will not run), flush all currently running jobs and create multiple workers (each with their own jobs).
*   [atom-plugin (⭐5)](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) - Based on the [Sublime (⭐4)](https://github.com/valentinocossar/sublime) plugin, lets you launch a file or folder in [Atom](https://atom.io) from [iTerm 2](https://iterm2.com).
*   [atuin (⭐24k)](https://github.com/ellie/atuin) - Replaces your existing shell history with a SQLite database, and records additional context for your commands. Additionally, it provides optional and fully encrypted synchronisation of your history between machines, via an Atuin server.
*   [aur-install (⭐1)](https://github.com/redxtech/zsh-aur-install) - Small plugin to install packages from the AUR.
*   [auto-color-ls (⭐57)](https://github.com/gretzky/auto-color-ls) - Automatically list directories with `colorls`.
*   [auto-fu.zsh (⭐431)](https://github.com/hchbaw/auto-fu.zsh) - Automatic complete-word and list-choices. Originally incr-0.2.zsh by y.fujii <y-fujii at mimosa-pudica.net>.
*   [auto-ls (commanda-panda) (⭐4)](https://github.com/commanda-panda/zsh-auto-ls) - Automatically runs `ls` or `color-ls` if available on `cd`.
*   [auto-ls (desyncr) (⭐89)](https://github.com/desyncr/auto-ls) - Automatically `ls` when cding to a new directory.
*   [auto-notify (⭐442)](https://github.com/MichaelAquilina/zsh-auto-notify) - Automatically sends out a notification when a long running task has completed.
*   [auto-nvm (⭐0)](https://github.com/manlao/zsh-auto-nvm) - Automatically switches to the node version specified in a given directory.
*   [auto-pnpm-use (⭐4)](https://github.com/brunomacedo/zsh-auto-pnpm-use) - Automatically loads the node version specified in `.nvmrc` or `.npmrc`.
*   [auto-venv (⭐5)](https://github.com/Skylor-Tang/auto-venv) - Automatically activates the Python virtual environment in the current directory or its parent directories.
*   [autocomplete (⭐5.8k)](https://github.com/marlonrichert/zsh-autocomplete) - Automatically lists completions as you type and provides intuitive keybindings for selecting and inserting them.
*   [autodark (cravend) (⭐2)](https://github.com/cravend/autodark) - Switches between user-specified light and dark themes. Only works on macOS.
*   [autodark (vbwx) (⭐0)](https://github.com/vbwx/zsh-autodark) - Switches to another Terminal profile if dark mode is enabled (macOS-only).
*   [autodotenv (⭐14)](https://github.com/nocttuam/autodotenv) - Will prompt you to load variables when you `cd` into a directory containing a `.env` file.
*   [autoenv-extended (⭐168)](https://github.com/zpm-zsh/autoenv) - Extended version of the [zsh-autoenv (⭐727)](https://github.com/Tarrasch/zsh-autoenv) plugin.
*   [autoenv (⭐5.8k)](https://github.com/hyperupcall/autoenv) - Directory-based environments.
*   [autojump (⭐17k)](https://github.com/wting/autojump) - A `cd` command that learns - easily navigate directories from the command line. Install autojump-zsh for best results.
*   [autopair (⭐562)](https://github.com/hlissner/zsh-autopair) - A ZSH plugin for auto-closing, deleting and skipping over matching delimiters. Only tested on ZSH 5.0.2 or later.
*   [autoquoter (⭐119)](https://github.com/ianthehenry/zsh-autoquoter) - A `zle` widget ("zsh plugin") that will automatically put quotes around arguments to certain commands.
*   [autosuggestions (⭐33k)](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)-like fast/unobtrusive autosuggestions for ZSH.
*   [autoswitch-virtualenv (⭐578)](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv) - ZSH plugin to automatically switch python virtualenvs and pipenvs when traversing directories. Automatically detects [pipenv](https://pypi.org/project/pipenv/) and [poetry](https://python-poetry.org/) projects.
*   [autoupdate-antibody (⭐0)](https://github.com/spikespaz/autoupdate-antibody-zsh) - A fork of [autoupdate-antigen (⭐27)](https://github.com/unixorn/autoupdate-antigen.zshplugin) for the [Antibody](https://getantibody.github.io) plugin manager, with the added ability to cooperate with static loading.
*   [autoupdate-antigen (⭐27)](https://github.com/unixorn/autoupdate-antigen.zshplugin) - [Antigen (⭐8.2k)](https://github.com/zsh-users/antigen) doesn't do automatic updates like [oh-my-zsh](https://ohmyz.sh/). This plugin adds auto updating for `antigen`, both of `antigen` and the bundles loaded in your configuration.
*   [autoupdate-oh-my-zsh-plugins (⭐280)](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) - [oh-my-zsh](https://ohmyz.sh/) doesn't automatically update non-core plugins, this plugin autoupdates `git` repositories in the `$ZSH_CUSTOM` directory.
*   [autovenv (linnnus) (⭐7)](https://github.com/linnnus/autovenv) - Automatically activates Python virtual environments when entering their parent directory.
*   [autovenv (snovra-dev) (⭐0)](https://github.com/snovra-dev/zsh-autovenv) - Automatically activates Python virtual environments when entering their parent directory.
*   [aws-cli-mfa (⭐20)](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) - AWS CLI MFA plugin based on sweharris' [aws-cli-mfa (⭐25)](https://github.com/sweharris/aws-cli-mfa). Supports specifying `mfa_device` in profile.
*   [aws-mfa (⭐3)](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) - Plugin for AWS MFA.
*   [aws-plugin (⭐2)](https://github.com/pookey/zsh-aws-plugin) - Adds helper functions for `aws` command. Includes mfa and `assume-role` helpers.
*   [aws-upload (⭐2)](https://github.com/borracciaBlu/aws-upload-zsh) - Boost your productivity with `aws-upload`.
*   [aws-vault-profiles (⭐0)](https://github.com/jonscheiding/zsh-plugin-aws-vault-profiles) - Plugin that integrates usage of [aws-vault (⭐8.7k)](https://github.com/99designs/aws-vault) with the `$AWS_PROFILE` environment variable.
*   [aws-vault (⭐90)](https://github.com/blimmer/zsh-aws-vault) - Plugin for [aws-vault (⭐8.7k)](https://github.com/99designs/aws-vault). Includes tab completions.
*   [aws (⭐1)](https://github.com/apachler/zsh-aws) - Forked from the original [oh-my-zsh](https://ohmyz.sh/) [aws (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/aws). Includes completions for `awscli` and a few utilities for managing AWS profiles and displaying them in your prompt.
*   [aws2 (⭐2)](https://github.com/drgr33n/oh-my-zsh_aws2-plugin) - Provides completion support for version 2 of the [awscli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) and a few utilities to manage AWS profiles and display them in the prompt.
*   [awsp (⭐0)](https://github.com/suonto/awsp-zsh-plugin) - AWS profile management for ZSH. Inspired by oh-my-zsh's [aws (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/aws/aws.plugin.zsh) plugin. Shows details of currently active AWS profile.
*   [awsssh (⭐3)](https://github.com/raisedadead/zsh-awsssh) - List, select and `ssh` into EC2 instances.
*   [awsume (⭐1)](https://github.com/Sordie/AWSume) - Plugin that enables showing the current [awsume (⭐550)](https://github.com/trek10inc/awsume) profile.
*   [azcli (⭐1)](https://github.com/dmakeienko/azcli) - Helper for using the Azure cli tools.
*   [azure-keyvault (⭐0)](https://github.com/milespossing/Azure-Keyvault-Zsh) - Makes using Azure keyvaults less verbose from the cli.
*   [azure-subscription (⭐2)](https://github.com/dmakeienko/azure-subscription-prompt) - Displays information about the Azure current Subscription and tenant.
*   [banner (⭐4)](https://github.com/drkhsh/zsh-banner) - Displays ANSI/ASCII art on session startup.
*   [baseballfunfacts (⭐3)](https://github.com/richardmoyer/baseballfunfacts) - Print random baseball related "fun facts" in your shell. Depends on `fortune` and `cowsay` being installed.
*   [bash-quote (⭐6)](https://github.com/jtprog/bash-quote) - Get random quote from Bash.im.
*   [bash (⭐40)](https://github.com/chrissicool/zsh-bash) - Makes ZSH more Bash compatible. It redefines the source command to act more like `bash` does. It also enables `bash` completions.
*   [bat (⭐38)](https://github.com/fdellwing/zsh-bat) - Adds some helper aliases for [bat (⭐52k)](https://github.com/sharkdp/bat) users.
*   [battery\_state (⭐8)](https://github.com/Jactry/zsh_battery_state) - Show battery state in right-prompt.
*   [bd (⭐426)](https://github.com/Tarrasch/zsh-bd) - Jump back to a specific directory, without doing `cd ../../..`.
*   [bepoptimist (⭐1)](https://github.com/sheoak/zsh-bepoptimist/) Remaps vi-mode for the French [bépo](http://bepo.fr/wiki/Accueil) keyboard.
*   [bitbucket-git-helpers (⭐17)](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - Adds helper scripts to allow you to create bitbucket PRs or open a directory in the current branch.
*   [bitwarden (casonadams) (⭐1)](https://github.com/casonadams/bitwarden-cli) - A [Bitwarden](https://bitwarden.com/download/) CLI fuzzy finder using [fzf (⭐70k)](https://github.com/junegunn/fzf). Requires [jq](https://stedolan.github.io/jq/).
*   [bitwarden (game4move78) (⭐24)](https://github.com/Game4Move78/zsh-bitwarden) - Adds functions to manage [bitwarden](https://bitwarden.com/) sessions.
*   [bitwarden (kalsowerus) (⭐12)](https://github.com/kalsowerus/zsh-bitwarden) - Opens a [fzf (⭐70k)](https://github.com/junegunn/fzf) widget containing your [Bitwarden](https://bitwarden.com/) vault items. Upon selecting an item either the username or password will be either written into the shell or copied into the clipboard. Requires `fzf`, `jq` and `bitwarden`.
*   [blackbox (⭐6.7k)](https://github.com/StackExchange/blackbox) - Stack Exchange's toolkit for storing keys/credentials securely in a `git` repository.
*   [bob (⭐3)](https://github.com/wintermi/zsh-bob) - Plugin for [bob (⭐1.6k)](https://github.com/MordechaiHadad/bob) a cross-platform and easy-to-use Neovim version manager.
*   [bofh (⭐3)](https://github.com/fundor333/bofh) - Adds functions to display random bofh fortunes.
*   [bol (⭐7)](https://github.com/ikhurramraza/bol) - Prints a random quote when you open a terminal window.
*   [boss-docker (⭐1)](https://github.com/bossjones/boss-docker-zsh-plugin) - Manages `docker` on macOS.
*   [boss-git (⭐8)](https://github.com/bossjones/boss-git-zsh-plugin) - Adds some convenience aliases for `git`.
*   [branch-manager (⭐18)](https://github.com/elstgav/branch-manager) - A plugin for managing `git` branches.
*   [brave (⭐0)](https://github.com/troykelly/oh-my-zsh-brave) - Manages [Brave](https://brave.com) profiles. With this plugin, you can start the Brave Browser with a specific user profile by using the brave command followed by the profile's name. The plugin also implements autocompletion for the profile names so you won't have to type the entire profile name manually.
*   [brew (rhuang2014) (⭐0)](https://github.com/rhuang2014/brew) - Standalone plugin for the [Homebrew](https://brew.sh/) Package Manager.
*   [brew (wintermi) (⭐6)](https://github.com/wintermi/zsh-brew) - Simple plugin for the [Homebrew](https://brew.sh/) Package Manager.
*   [brew (wolffaxn) (⭐0)](https://github.com/wolffaxn/brew-zsh-plugin) - Standalone plugin for the [Homebrew](https://brew.sh/) Package Manager.
*   [brew-install (⭐0)](https://github.com/marceloclp/zsh-brew-install) - Installs and loads [brew](https://brew.sh) on WSL.
*   [brew-switcher (⭐10)](https://github.com/fielding/zsh-brew-switcher) - Automatically switch between Homebrew installations based on the current active arch, arm64 or x86\_64, on Apple Silicon Macs.
*   [browse-commit (⭐17)](https://github.com/adolfoabegg/browse-commit) - Lets you open any commit in your browser from the command line.
*   [bruse (⭐2)](https://github.com/aubreypwd/zsh-plugin-bruse) - Makes it easy to `brew link` different versions of packages.
*   [bumblebee (⭐2)](https://github.com/Niverton/zsh-bumblebee-plugin) - A plugin to toggle prepending `optirun` in the command line.
*   [bw (⭐5)](https://github.com/begris/bw-zsh-plugin) - Provides formatting options and easy access to credentials stored in [Bitwarden](https://bitwarden.com) via the Bitwarden [CLI](https://bitwarden.com/download/). The plugin tries to retrieve a valid session before each action, therefore an explicit login is not nescessary beforehand.
*   [bws (⭐2)](https://github.com/elogiclab/zsh-bws) - Simplify and improve the retrieval of secrets from the [Bitwarden](https://bitwarden.com) Secret Manager.
*   [c (⭐3)](https://github.com/sebastiangraz/c) - Adds some `git` shortcuts.
*   [calc (arzzen) (⭐132)](https://github.com/arzzen/calc.plugin.zsh) - A calculator for ZSH.
*   [calc (sam-programs) (⭐5)](https://github.com/Sam-programs/zsh-calc) - Allows you to run math calculations with no prefixes.
*   [calibre-zaw-source (⭐3)](https://github.com/junkblocker/calibre-zaw-source) - [Calibre - E-book management](https://calibre-ebook.com/) source for [zaw (⭐576)](https://github.com/zsh-users/zaw)
*   [caniuse (⭐19)](https://github.com/walesmd/caniuse.plugin.zsh) - Add [Can I Use](https://caniuse.com) support to ZSH.
*   [caper-bush (⭐0)](https://github.com/kobylinski/caper-bush) - Enhances Git's tab autocomplete by using AI to generate concise, context-aware summaries of staged changes for thoughtful commit messages. Requires and OpenAI key, `jq` and `yq`.
*   [careful\_rm (⭐32)](https://github.com/MikeDacre/careful_rm) - A wrapper for `rm` that adds trash/recycling and useful warnings.
*   [case (⭐4)](https://github.com/rtuin/zsh-case) - A ZSH plugin that adds two aliases `tolower` and `toupper` to switch output case.
*   [cd-gitroot (⭐75)](https://github.com/mollifier/cd-gitroot) - A ZSH plugin to `cd` to the `git` repository root directory.
*   [cd-ls (⭐17)](https://github.com/zshzoo/cd-ls) - Automatically `ls` after `cd`.
*   [cd-reminder (⭐14)](https://github.com/bartboy011/cd-reminder) - Display reminders when `cd`-ing into specified directories.
*   [cd-reporoot (⭐2)](https://github.com/P4Cu/cd-reporoot) - A ZSH plugin to `cd` to the current repository checkout's root directory.
*   [cd-ssh (⭐2)](https://github.com/jeffwalter/zsh-plugin-cd-ssh) - `ssh` to a server when you accidentally `cd` to it.
*   [cdbk (⭐15)](https://github.com/MikeDacre/cdbk) - A ZSH plugin to allow easy named directory creation - shortcuts to any directory you want.
*   [cdc (⭐23)](https://github.com/evanthegrayt/cdc) - Makes it easier to change directories to directories that are subdirs of a user-defined list of directories. Includes tab-completion, session history and `pushd`, `popd` and `dirs` equivalents.
*   [cdh (⭐2)](https://github.com/johncassol/cdh) - Allows users to manage and navigate through a history of directories they have visited. It maintains a history file of directories and provides several commands to interact with this history.
*   [cdhist (⭐7)](https://github.com/joknarf/cdhist) - cd history/subdir/locatedir navigation. simple cd history, alias builtin `cd` to add `cd` history, rapidily swich to already visited directories, can use `locate`, `mlocate` or `plocate` to rapidly cd to any directory
*   [cdr (⭐17)](https://github.com/willghatch/zsh-cdr) - Easy setup of `cdr` for ZSH.
*   [change-case (⭐8)](https://github.com/mtxr/zsh-change-case) - Plugin for fast swap between upper and lower case in your command line. :sunglasses:
*   [cheatsheet (⭐12)](https://github.com/0b10/cheatsheet) - Plugin to easily view, create, and edit cheatsheets.
*   [check-deps (⭐3)](https://github.com/zpm-zsh/check-deps) - Helper for ZSH plugins that allows them to show how to install any missing dependencies. Works on Debian (and derivatives like Ubuntu), Arch and its derivatives, Node.js and ZSH plugins if you are using the [zpm (⭐369)](https://github.com/zpm-zsh/zpm) framework.
*   [chgo (⭐0)](https://github.com/sbfaulkner/chgo-plugin-zsh) - Clone of `chruby` modified to make it easy to switch between multiple Go versions.
*   [clean-project (⭐11)](https://github.com/wwilsman/zsh-clean-project) - Remove files from projects (automatically by default). Useful for keeping `.DS_Store` and `Thumbs.db` files from cluttering your directories.
*   [cleanzip (⭐0)](https://github.com/Xeferis/cleanzip) - Helps create zip files that don't have data that shouldn't be in there.
*   [clipboard (⭐39)](https://github.com/zpm-zsh/clipboard) - Adds a cross-platform helper function to access the system clipboard. Works on macOS, X11 (and Wayland) and Cygwin.
*   [cmaker (⭐9)](https://github.com/apalkk/Cmaker) - Makes using `cmake` easier.
*   [cmd-status (⭐3)](https://github.com/BlaineEXE/zsh-cmd-status) - Reports the status of commands including return code and duration.
*   [cmd-time (⭐2)](https://github.com/TomfromBerlin/zsh-cmd-time) - Collects the execution time of commands and exports the result to a variable that can be used elsewhere. It is similar to the built-in [REPORTTIME](http://zsh.sourceforge.net/Doc/Release/Parameters.html) function, but it is also slightly different. Unlike when you set `REPORTTIME`, it considers user and sytem time, not just CPU time.
*   [cmdtime (⭐33)](https://github.com/tom-auger/cmdtime) - Displays the duration of a command to the terminal forked from the [timer (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/timer) plugin.
*   [code-review (⭐3)](https://github.com/xorkevin/code-review-zsh) - Launches `git difftool` on `git merge-base target_branch base_branch` and `target_branch`.
*   [code-stats](https://gitlab.com/code-stats/code-stats-zsh) - Counts keypresses and logs stats to [Code::Stats](https://codestats.net/).
*   [codex (⭐1.6k)](https://github.com/tom-doerr/zsh_codex) - Enables you to use OpenAI's powerful Codex AI in the command line.
*   [coffee-time (⭐2)](https://github.com/gakimball/zsh-coffee-time) - Adds the `caf` alias, which runs `caffeinate -dims`. The extra flags keep everything awake: the system, the drive, and the display.
*   [color-logging (⭐2)](https://github.com/p1r473/zsh-color-logging) - provides a really easy to use logging library with notifications for pushbullet and pushover, colorizes tools like `cat` and `ls` and provides a color library.
*   [colored-man-pages-mod (⭐14)](https://github.com/zuxfoucault/colored-man-pages_mod) - Forked from [ohmyzsh/ohmyzsh/plugins/colored-man-pages (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh). Colorizes `man` output.
*   [colored-man-pages (⭐63)](https://github.com/ael-code/zsh-colored-man-pages) - Colorize `man` pages.
*   [colorize-functions (⭐4)](https://github.com/Freed-Wu/zsh-colorize-functions) - Colorizes functions for ZSH.
*   [colorize (⭐29)](https://github.com/zpm-zsh/colorize) - Colorize the output of various programs.
*   [colorls (⭐8)](https://github.com/Kallahan23/zsh-colorls) - Defines a few helpful shortcuts to some colorls functions.
*   [colors (Tarrasch) (⭐42)](https://github.com/Tarrasch/zsh-colors) - Makes it easier to colorize text from the CLI. `red foo` just works.
*   [colors (zpm-zsh) (⭐50)](https://github.com/zpm-zsh/colors) - Enhanced colors for ZSH.
*   [command-execution-timer (⭐10)](https://github.com/olets/command-execution-timer) - Displays the time an interactive shell command takes to execute.
*   [command-not-found (freed-wu) (⭐8)](https://github.com/Freed-Wu/zsh-command-not-found) - Uses the `command-not-found` package for ZSH to provide suggested packages to be installed if a command cannot be found.
*   [command-not-found (tarrasch) (⭐23)](https://github.com/Tarrasch/zsh-command-not-found) - A mirror of the [oh-my-zsh](https://ohmyz.sh) [command-not-found (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/command-not-found) plugin so you don't have to include all of oh-my-zsh.
*   [command-note (⭐13)](https://github.com/KKRainbow/zsh-command-note.plugin) - Record complex commands and comment on them.
*   [command-time (⭐200)](https://github.com/popstas/zsh-command-time) - Show execution time for long commands in ZSH and [powerlevel9k (⭐13k)](https://github.com/bhilburn/powerlevel9k). Similar to `REPORTTIME` builtin, but only outputs when user + system time >= `REPORTTIME`.
*   [communism (⭐25)](https://github.com/victoria-riley-barnett/Communism/) - Displays a Marx quote of the day.
*   [compe (⭐21)](https://github.com/tamago324/compe-zsh) - Add completion for [nvim-compe (⭐1.3k)](https://github.com/hrsh7th/nvim-compe).
*   [completion-generator (⭐281)](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically. Note that this doesn't do it automatically, you have to explicitly call the generator to create a completion script.
*   [conda (themysciradata) (⭐15)](https://github.com/ThemysciraData/conda.plugin.zsh) - Adds function to provide a prompt segment for [conda](https://conda.io) and aliases for some base functions.
*   [conda (wardhanisukoco) (⭐0)](https://github.com/wardhanisukoco/zsh-plugin-conda/) - Automatically loads `conda` and provides functions for detecting `conda` versions for use in themes.
*   [conda-init (⭐1)](https://github.com/commiyou/conda-init-zsh-plugin) - Cleans up environment variables so [conda](https://conda.io) doesn't mess up `tmux`.
*   [condaenv (⭐1)](https://github.com/saravanabalagi/zsh-plugin-condaenv) - Provides a `condaenv_prompt_info` function which returns the current `conda` environment name.
*   [confer (⭐6)](https://github.com/SleepyBag/zsh-confer) - Tries to find program configuration files automatically so you can do things like `conf vim` to edit your `vim` configuration files.
*   [containers (⭐5)](https://github.com/redxtech/zsh-containers) - Provides aliases and better interoperability between [podman](https://podman.io) and [docker](https://docker.com) commands based on which you have installed.
*   [copy-pasta (⭐31)](https://github.com/ChrisPenner/copy-pasta) - Copy and paste files in your terminal like you would in a GUI.
*   [copyzshell (⭐90)](https://github.com/rutchkiwi/copyzshell) - A ZSH plugin to copy your shell configuration to another machine over `ssh`.
*   [cowsay (⭐2)](https://github.com/phucleeuwu/cowsay.zsh) - Displays a joke with `cowsay` and `lolcat` every time you open a terminal.
*   [crash (⭐67)](https://github.com/molovo/crash) - Adds proper error handling, exceptions and try/catch for ZSH.
*   [crayon-syntax (⭐0)](https://github.com/gsemet/crayon-syntax-zsh) - ZSH syntax highlighting for the Crayon Plugin for Wordpress.
*   [cros-auto-notify (⭐0)](https://github.com/D3STY/cros-auto-notify-zsh) - Automatically sends out a notification when a long running task has completed. Works with macOS and linux (if `hterm-notify` is installed).
*   [crypto-prices (⭐11)](https://github.com/vincentdnl/zsh-crypto-prices) - Add a [powerlevel9k (⭐13k)](https://github.com/bhilburn/powerlevel9k) segment with the current bitcoin price.
*   [crystal (⭐26)](https://github.com/veelenga/crystal-zsh) - A plugin for [Crystal (⭐20k)](https://github.com/crystal-lang/crystal).
*   [cvideo (⭐1)](https://github.com/aubreypwd/zsh-plugin-cvideo) - Quickly compress video with `ffmpeg`.
*   [cycle-fav-dirs (⭐2)](https://github.com/cibinmathew/cycle-fav-dirs) - A plugin to cycle through your favourite directories.
*   [cycle-jobs (⭐4)](https://github.com/aemonge/zsh-cycle-jobs) - The ZSH Cycle Jobs Plugin is a simple yet powerful tool that enhances your terminal workflow by allowing you to cycle through background jobs using a single keyboard shortcut. This plugin is particularly useful for developers and system administrators who frequently work with multiple background processes.
*   [czhttpd (⭐58)](https://github.com/jsks/czhttpd) - A simple http server written in 99.9% pure ZSH.
*   [dbd (⭐3)](https://github.com/BlackFlame444/dpd-plugin) - Displays eye-catching banners whenever you change directories (cd). It uses figlet and lolcat to generate colorful banners, giving your terminal a stylish touch.
*   [ddev (⭐2)](https://github.com/voronkovich/ddev.plugin.zsh) - A ZSH plugin for the [ddev (⭐3.1k)](https://github.com/drud/ddev) tool for setting up PHP development environments.
*   [declare-zsh (⭐9)](https://github.com/z-shell/declare-zsh) - A parser for [zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit) commands in `.zshrc`. It allows you to perform the following actions on `.zshrc` from the command-line - enable and disable plugins add or remove snippets.
*   [deepx (⭐8)](https://github.com/GetAmbush/deepx-zsh-plugin) - Collection of useful and fun commands to improve workflow and quality of life.
*   [deer (⭐302)](https://github.com/Vifon/deer) - A file navigator for ZSH heavily inspired by [ranger](https://ranger.github.io/).
*   [def (⭐12)](https://github.com/thevinter/def) - Allows you to specify and run a default command in any directory of your choice.
*   [defer (⭐389)](https://github.com/romkatv/zsh-defer) - Defers execution of a `zsh` command until `zsh` has nothing else to do and is waiting for user input. Its intended purpose is staged `zsh` startup. It works similarly to Turbo mode in [zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit).
*   [delete-prompt (⭐5)](https://github.com/aoyama-val/zsh-delete-prompt) - ZSH widget to delete the prompt texts within the current line. It is useful when executing pasted commands from the web or a README. A leading non-alphanumeric character + space is detected as a prompt.
*   [deno (cowboyd) (⭐1)](https://github.com/cowboyd/zsh-deno) - Useful [deno](https://deno.land/) aliases and settings.
*   [deno (tricked-dev) (⭐0)](https://github.com/Tricked-dev/deno-zsh-plugin) - Automatically installs [deno](https://deno.land/) to `$HOME/.deno` on startup if deno is not already installed.
*   [depot-tools (⭐1)](https://github.com/kuoe0/zsh-depot-tools) - Simple [oh-my-zsh](https://ohmyz.sh/) plugin for installing the chromium depot\_tools. Installing this plugin will add all of the chromium depot\_tools to your `$PATH` automatically.
*   [dev (⭐5)](https://github.com/sbfaulkner/dev-plugin-zsh) - Provides a lightweight version of Shopify's internal dev tool
*   [dietpi (⭐4)](https://github.com/unixorn/dietpi.plugin.zsh) - Adds utilities for [dietpi](https://dietpi.com) to your `$PATH` (and includes aliases to automagically run them with `sudo`) when you log into a machine running  [dietpi](https://dietpi.com).
*   [diff-so-fancy (⭐22)](https://github.com/z-shell/zsh-diff-so-fancy) - Automatically installs [diff-so-fancy (⭐18k)](https://github.com/so-fancy/diff-so-fancy) and enables its use in ZSH and `git`.
*   [diractions (⭐33)](https://github.com/AdrieanKhisbe/diractions) - Allow you to map a short logical/mnemonic name to directories to quickly access them, or perform actions in them.
*   [dirbrowse (⭐1)](https://github.com/giovannilupi/dirbrowse/) - Customized version of the [dirbrowse (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/dircycle) plugin in [oh-my-zsh](https://ohmyz.sh).
*   [dircolors-solarized (joel-porquet) (⭐115)](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors plugin, with options for dark or light terminal backgrounds.
*   [dircolors-solarized (pinelibg) (⭐2)](https://github.com/pinelibg/dircolors-solarized-zsh) - Enables [Solarized Color Theme for GNU ls (⭐2.9k)](https://github.com/seebi/dircolors-solarized).
*   [dircycle (⭐21)](https://github.com/michaelxmcbride/zsh-dircycle) - Cycle through the directory stack.
*   [directory-history (⭐157)](https://github.com/tymm/zsh-directory-history) - A per directory history for ZSH which implements forward/backward navigation as well as substring search in a directory sensitive manner.
*   [direnv (⭐16)](https://github.com/ptavares/zsh-direnv) - A plugin for installing and loading [direnv](https://github.com/direnv/direnv.git). Inspired by [zsh-pyenv (⭐47)](https://github.com/mattberther/zsh-pyenv).
*   [dirrc (⭐28)](https://github.com/gmatheu/shell-plugins) - Executes `.dirc` when present in a directory you `cd` into.
*   [dirstack (⭐2)](https://github.com/gepoch/oh-my-zsh-dirstack) - Plugin for displaying the dirstack info on a single line.
*   [diskfree (⭐0)](https://github.com/alex-crouch/zsh-diskfree/) - Displays the free space on your disk in your prompt.
*   [doas (anatolykopyl) (⭐6)](https://github.com/anatolykopyl/doas-zsh-plugin) - Easily prefix your current or previous commands with `doas` by pressing `ESC` twice.
*   [doas (senderman) (⭐3)](https://github.com/Senderman/doas-zsh-plugin) - Easily prefix your current or previous commands with `doas` by pressing `ESC` twice.
*   [docker-aliases (⭐8)](https://github.com/webyneter/docker-aliases) - `Docker` aliases for everyday use.
*   [docker-compose (⭐49)](https://github.com/sroze/docker-compose-zsh-plugin) - Show `docker` container status in your prompt.
*   [docker-helpers (⭐29)](https://github.com/unixorn/docker-helpers.zshplugin) - A collection of `docker` helper scripts.
*   [docker-machine (⭐2)](https://github.com/asuran/zsh-docker-machine) - A docker-machine plugin for ZSH.
*   [docker-run (⭐47)](https://github.com/rawkode/zsh-docker-run) - Go back to running your commands "naturally", we'll handle the container.
*   [dogesh (⭐6)](https://github.com/keithhamilton/oh-my-dogesh) - Dogification plugin.
*   [dot-up (⭐2)](https://github.com/toku-sa-n/zsh-dot-up) - Converts `...`, `....`, `.....`, etc., into `cd` commands to navigate parent directories.
*   [dotbare (⭐698)](https://github.com/kazhala/dotbare) - Interactive dotfile management with the help of [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [dotfiles (⭐23)](https://github.com/vladmyr/dotfiles-plugin) - Keep your dotfiles in sync across multiple machines using `git`.
*   [dotpyvenv (⭐6)](https://github.com/jeanpantoja/dotpyvenv) - Automagically switch to a python virtual environment located (that you previously have created with virtualenv program) in a directory named `.pyvenv` when you `cd` into a directory.
*   [download (⭐2)](https://github.com/aubreypwd/zsh-plugin-download) - Helper to download files with `aria2c`.
*   [dropbox (⭐21)](https://github.com/zpm-zsh/dropbox) - A [dropbox](https://www.dropbox.com/) plugin for ZSH that provides `dropbox-cli` and `dropbox-uploader` commands.
*   [drupal (⭐1)](https://github.com/yhaefliger/zsh-drupal) - Adds aliases for common tasks and also tab-completion for `drush`. Inspired by [Artisan (⭐633)](https://github.com/jessarcher/zsh-artisan).
*   [dune-quotes (⭐10)](https://github.com/brokendisk/dune-quotes) - Random Dune quote generator plugin.
*   [duration (⭐0)](https://github.com/rtakasuke/zsh-duration) - Displays command duration if it exceeds a user-settable run time.
*   [dwim (⭐89)](https://github.com/oknowton/zsh-dwim) - Attempts to predict what you will want to do next. It provides a key binding (control-u) that will replace the current (or previous) command line with the command you will want to run next.
*   [easy-motion (⭐51)](https://github.com/IngoHeimbach/zsh-easy-motion) - A port of [vim-easymotion (⭐7.6k)](https://github.com/easymotion/vim-easymotion) for ZSH.
*   [ec2ssh (⭐10)](https://github.com/h3poteto/zsh-ec2ssh) - List EC2 instances and `ssh` login to the instances easily.
*   [editing-workbench (⭐2)](https://github.com/commiyou/zsh-editing-workbench) - Adds sane, complex command line editing (e.g. incremental history word completion).
*   [edward cli (⭐0)](https://github.com/matthieusb/zsh-edward) - Adds smart completions and alises for [edward CLI micro-service launcher (⭐171)](https://github.com/yext/edward).
*   [elixir (⭐155)](https://github.com/gusaiani/elixir-oh-my-zsh) - Adds shortcuts for Elixir, IEX, Mix, Kiex and Phoenix.
*   [emacs (cowboyd) (⭐0)](https://github.com/cowboyd/zsh-emacs) - Make Emacs the default for CLI operations like editing git commit messages; set up handy aliases.
*   [emacs (flinner) (⭐4)](https://github.com/Flinner/zsh-emacs) - Uses the Emacs daemon capability, allowing the user to quickly open frames, whether they are opened in a terminal via a `ssh` connection, or X frames opened on the same host.
*   [emoji-cli (⭐443)](https://github.com/b4b4r07/emoji-cli) - :scream: Emoji completion on the command line.
*   [emoji-fzf (⭐8)](https://github.com/pschmitt/emoji-fzf.zsh) - Configurable ZSH plugin for the excellent [emoji-fzf (⭐41)](https://github.com/noahp/emoji-fzf). It is heavily inspired by [emoji-cli (⭐443)](https://github.com/b4b4r07/emoji-cli).
*   [emojis (⭐14)](https://github.com/MichaelAquilina/zsh-emojis) - Adds numerous ASCII art emojis to your environment in convenient variables.
*   [enhancd (⭐2.6k)](https://github.com/b4b4r07/enhancd) - A simple tool that provides an enhanced `cd` command by memorizing all directories visited by a user and use it for the pathname resolution.
*   [ensure-kube-context (⭐0)](https://github.com/do-i-need-a-username/ensure-kube-context) - Ensures that the `--context` flag is passed to various Kubernetes commands like `kubectl`, `cilium`, `stern`, and more.
*   [envrc (⭐2)](https://github.com/fabiogibson/envrc-zsh-plugin) - Automatically loads and unloads environment variables if a `.envrc` file is found in a directory.
*   [escape-backtick (⭐1)](https://github.com/bezhermoso/zsh-escape-backtick) - Quickly insert escaped backticks when double-tapping "\`".
*   [evalcache (⭐216)](https://github.com/mroth/evalcache) - Caches the output of a binary initialization command like `eval "$(hub alias -s)"`, to help lower shell startup time by loading from cache instead of re-running every new shell session.
*   [evil-registers (⭐42)](https://github.com/zsh-vi-more/evil-registers) - Extends ZLE `vi` commands to remotely access named registers of the `vim` and `nvim` editors, and system selection and clipboard.
*   [exa (DarrinTisdale) (⭐117)](https://github.com/DarrinTisdale/zsh-aliases-exa) - Enables a number of aliases extending [exa (⭐24k)](https://github.com/ogham/exa), the modern replacement for `ls`.
*   [exa (mohamedelashri) (⭐18)](https://github.com/MohamedElashri/exa-zsh) - Adds aliases for [exa (⭐24k)](https://github.com/ogham/exa), a modern replacement for `ls`.
*   [exa (ptavares) (⭐11)](https://github.com/ptavares/zsh-exa) - Installs and loads [exa](https://github.com/ogham/exa.git).
*   [exa (ritchies) (⭐8)](https://github.com/RitchieS/zsh-exa/) - Adds aliases to make using [exa](https://github.com/ogham/exa.git) easier.
*   [exa (todie) (⭐1)](https://github.com/todie/exa.plugin.zsh) - Integration and completions for [exa (⭐24k)](https://github.com/ogham/exa), a modern replacement for `ls`.
*   [exa (zap-zsh) (⭐20)](https://github.com/zap-zsh/exa) - Overrides common commands to use exa instead.
*   [exa (zplugin) (⭐0)](https://github.com/zplugin/zsh-exa) - replace `ls` with [ogham/exa (⭐24k)](https://github.com/ogham/exa).
*   [exa (zshell) (⭐82)](https://github.com/z-shell/zsh-exa) - replace `ls` with [ogham/exa (⭐24k)](https://github.com/ogham/exa).
*   [exa-ls (zpm-zsh) (⭐100)](https://github.com/zpm-zsh/ls) - Zsh plugin for ls.
*   [exa-ls (⭐3)](https://github.com/birdhackor/zsh-exa-ls-plugin) - Adds aliases so that you can use [exa (⭐24k)](https://github.com/ogham/exa) as a drop-in replacement for `ls` and `tree`.
*   [exercism (⭐10)](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - A plugin for [exercism.io](http://exercism.io/).
*   [expand-ealias (⭐14)](https://github.com/zigius/expand-ealias.plugin.zsh) - Expand specific aliases with space.
*   [expand (⭐32)](https://github.com/MenkeTechnologies/zsh-expand) - Expands regular aliases, global aliases, incorrect spellings and phrases, globs, history expansion and $parameters with the spacebar key.
*   [expander (⭐4)](https://github.com/ianthehenry/zsh-expander) - A `zle` widget that allows you to write custom expanders and select them with [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [explain-shell (brokentoaster) (⭐4)](https://github.com/brokentoaster/zsh-explainshell) - Uses [lynx](https://lynx.browser.org/) to look up the current command line on [explainshell.com](https://explainshell.com).
*   [explain-shell (gmatheu) (⭐28)](https://github.com/gmatheu/shell-plugins) - Opens commands on [explainshell.com](https://explainshell.com).
*   [extend-history (⭐9)](https://github.com/xav-b/zsh-extend-history) - Extends command history by adding the exit code for each command in the history.
*   [ez-cmd (⭐1)](https://github.com/akgarhwal/ez-cmd) - Simplifies and streamlines common command-line tasks by providing easy-to-use shortcuts and aliases.
*   [ez-compinit (⭐17)](https://github.com/mattmc3/ez-compinit) - Wraps `compinit`, queueing up calls to `compdef`, and hooking the real `compinit` call to an event that runs at the end of your `.zshrc`. That way you get all the benefits of calling `compinit` early without any of the downsides.
*   [eza (clavelm) (⭐0)](https://github.com/clavelm/eza-omz-plugin) - Replaces `ls` with [eza-community/eza (⭐15k)](https://github.com/eza-community/eza).
*   [eza (mohamedelashri) (⭐4)](https://github.com/MohamedElashri/eza-zsh) - Adds aliases for [eza (⭐15k)](https://github.com/eza-community/eza), a modern replacement for `ls`.
*   [eza (twopizza9621536) (⭐4)](https://github.com/twopizza9621536/zsh-eza) - Replaces `ls` with [eza-community/eza (⭐15k)](https://github.com/eza-community/eza).
*   [eza (z-shell) (⭐82)](https://github.com/z-shell/zsh-eza) - Replaces `ls` with [eza-community/eza (⭐15k)](https://github.com/eza-community/eza).
*   [eza-ls (⭐1)](https://github.com/birdhackor/zsh-eza-ls-plugin) - Adds aliases allowing [eza (⭐15k)](https://github.com/eza-community/eza), to act as a drop-in replacement for `ls` and `tree`.
*   [f-shortcuts (⭐8)](https://github.com/zpm-zsh/f-shortcuts) - Makes a shortcuts toolbar using `F1` to `F12` keys.
*   [fancy-ctrl-z (⭐21)](https://github.com/mdumitru/fancy-ctrl-z) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of [oh-my-zsh](https://ohmyz.sh).
*   [fast-alias-tips (⭐13)](https://github.com/decayofmind/zsh-fast-alias-tips) - Helps remember the aliases you defined and forgot about. Ported from [djui/alias-tips (⭐794)](https://github.com/djui/alias-tips). Active fork of [sei40kr/zsh-fast-alias-tips (⭐60)](https://github.com/sei40kr/zsh-fast-alias-tips).
*   [fast-syntax-highlighting (⭐1.3k)](https://github.com/zdharma-continuum/fast-syntax-highlighting) - Optimized and improved `zsh-users/zsh-syntax-highlighting` – better response times, switchable highlight themes.
*   [fastcache (⭐38)](https://github.com/QuarticCat/zsh-fastcache) - Caches command output to improve shell startup time.
*   [fav (⭐4)](https://github.com/ddnexus/fav) - ZSH/[fzf (⭐70k)](https://github.com/junegunn/fzf) plugin that makes it really easy to add and recall named favorites of your important directories.
*   [favorite-directories (⭐8)](https://github.com/seletskiy/zsh-favorite-directories) - Fast jumps to your favorite directories.
*   [fd-plugin (⭐8)](https://github.com/MohamedElashri/fd-zsh) - Adds aliases for [fd (⭐38k)](https://github.com/sharkdp/fd), a modern replacement for `find`.
*   [fd (⭐7)](https://github.com/aubreypwd/zsh-plugin-fd) - Use [fzf (⭐70k)](https://github.com/junegunn/fzf) to browse directories.
*   [figures (⭐11)](https://github.com/zpm-zsh/figures) - Unicode symbols for ZSH.
*   [firebase (rmrs) (⭐5)](https://github.com/rmrs/firebase-zsh) - Add an indicator in the prompt that you're in a directory with a `firebase.json` file (aka "firebase project").
*   [firebase (seqi) (⭐9)](https://github.com/Seqi/firebase-zsh) - Display the current working project or project alias when in a Firebase project directory or subdirectory.
*   [firmine (⭐1)](https://github.com/GNUWood/firmine) - Includes decorators for user\@hostname, date & time, current directory and [Kaomoji](https://en.wikipedia.org/wiki/Kaomoji) icons for last command exit status.
*   [fixnumpad-osx (⭐3)](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh) - Enables numpad keys of Apple keyboards to be recognized in ZSH.
*   [flow-plugin (⭐44)](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - This plugin makes the `flow` command available inside every subdirectory of the TYPO3 Flow distribution.
*   [fnm (dominik-schwabe) (⭐16)](https://github.com/dominik-schwabe/zsh-fnm) - Installs and loads the [Fast Node Manager (fnm) (⭐21k)](https://github.com/Schniz/fnm) if it is missing.
*   [fnm (wintermi) (⭐3)](https://github.com/wintermi/zsh-fnm) - Helper plugin for the fast and simple Node.js version manager [fnm (⭐21k)](https://github.com/Schniz/fnm).
*   [forgit (⭐4.7k)](https://github.com/wfxr/forgit) - Utility tool for `git` which takes advantage of fuzzy finder [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [fuckmit (⭐0)](https://github.com/mingeme/zsh-fuckmit) - Provides useful aliases and functions for the [fuckmit (⭐0)](https://github.com/mingeme/fuckmit) command-line tool, an AI-powered git commit message generator.
*   [functional (⭐136)](https://github.com/Tarrasch/zsh-functional) - ZSH higher order functions.
*   [fuzzy-search-and-edit (⭐34)](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - ZSH plugin for fuzzy searching files and instantly opening a matched file on matched line.
*   [fuzzy-wd (⭐2)](https://github.com/spodin/zsh-fuzzy-wd) - Adds fuzzy search for directories warped with the [WD (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/wd) plugin.
*   [fz (⭐536)](https://github.com/changyuheng/fz) - Seamlessly adds fuzzy search to [z (⭐17k)](https://github.com/rupa/z)'s tab completion and lets you easily jump around among directories in your history.
*   [fzf (gimbo) (⭐0)](https://github.com/gimbo/fzf.zsh) - Helpers for using [fzf (⭐70k)](https://github.com/junegunn/fzf) in ZSH. Requires [brew.sh](https://brew.sh).
*   [fzf (unixorn) (⭐348)](https://github.com/unixorn/fzf-zsh-plugin/) - Enables [fzf (⭐70k)](https://github.com/junegunn/fzf) history and file searches.
*   [fzf-copyq-clipboard (⭐2)](https://github.com/magidc/fzf-copyq-clipboard-zsh-plugin) - Add [fzf (⭐70k)](https://github.com/junegunn/fzf) support for [CopyQ](https://hluk.github.io/CopyQ/).
*   [fzf-dir-navigator (⭐50)](https://github.com/KulkarniKaustubh/fzf-dir-navigator) - This is a cool and user-friendly directory navigation plugin for `zsh` using `fzf` that allows the user to switch to any directory from anywhere and to anywhere. It also maintains a history of recently visited directories. Additionally, you can use hotkeys to move back and forth between directories in the shell session.
*   [fzf-fasd (⭐57)](https://github.com/wookayin/fzf-fasd) - Integrates [fzf (⭐70k)](https://github.com/junegunn/fzf) and [fasd (⭐5.9k)](https://github.com/clvv/fasd) --- tab completion of `z` with `fzf`'s fuzzy search!
*   [fzf-finder (⭐19)](https://github.com/leophys/zsh-plugin-fzf-finder) - Plugin to have a cool search keybinding with [fzf (⭐70k)](https://github.com/junegunn/fzf) and (optionally) [bat (⭐52k)](https://github.com/sharkdp/bat) and [fd (⭐38k)](https://github.com/sharkdp/fd). Falls back to `find` and `cat`. Searches in the local tree of subdirectories for files.
*   [fzf-history-search (⭐381)](https://github.com/joshskidmore/zsh-fzf-history-search) - Replaces `Ctrl+R` with an [fzf (⭐70k)](https://github.com/junegunn/fzf)-driven history search that includes date/times.
*   [fzf-it (⭐5)](https://github.com/micakce/fzf-it) - Make any command interactive wrapping it with [fzf (⭐70k)](https://github.com/junegunn/fzf) functionality.
*   [fzf-marks (⭐496)](https://github.com/urbainvaes/fzf-marks) - Little script to create, navigate and delete bookmarks in `bash` and `zsh`, using the fuzzy finder [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [fzf-packagemanager (⭐1)](https://github.com/goarano/zsh-fzf-packagemanager) - Adds commands for installing tools via various package managers using [fzf (⭐70k)](https://github.com/junegunn/fzf). Supports `apt`, `brew` & `dnf`.
*   [fzf-pass (⭐6)](https://github.com/smeagol74/zsh-fzf-pass) - Better handling of passwords using [fzf (⭐70k)](https://github.com/junegunn/fzf) and [pass](https://www.passwordstore.org/).
*   [fzf-plugin (⭐1)](https://github.com/Atlas34/fzf-plugin) - [oh-my-zsh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh)'s `fzf` plugin extracted so it can be used easily with other plugin managers.
*   [fzf-prezto (⭐5)](https://github.com/lildude/fzf-prezto) - Prezto plugin that finds where [fzf (⭐70k)](https://github.com/junegunn/fzf) has been installed and enables its auto-completion and key-bindings. This plugin works as a Prezto `zstyle` configuration option.
*   [fzf-tab-widgets (⭐10)](https://github.com/tom-power/fzf-tab-widgets) - Adds widgets for [fzf-tab (⭐3.8k)](https://github.com/Aloxaf/fzf-tab).
*   [fzf-tab (⭐3.8k)](https://github.com/Aloxaf/fzf-tab) - Replace ZSH's default completion selection menu with [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [fzf-tools (⭐16)](https://github.com/happycod3r/fzf-tools) - Provides functions, aliases and key-bindings for commands such as `alias`, `find`, `ls`, `man`, `printenv` that are designed to enhance your command-line workflow by making them to default to filtering through [fzf (⭐70k)](https://github.com/junegunn/fzf), allowing you to quickly find files, search & run commands from history, run scripts of many supported types, browse `git` commits, and more.
*   [fzf-utils (⭐1)](https://github.com/redxtech/zsh-fzf-utils) - Provides functions to kill proceses and find in path with [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [fzf-widgets (⭐90)](https://github.com/ytet5uy4/fzf-widgets) - Adds some ZLE widgets for [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [fzfsh (⭐2)](https://github.com/ethan605/fzfsh) - Add [fzf (⭐70k)](https://github.com/junegunn/fzf) plugins for `chezmoi`, `docker`, `git`, `kubectl` and `pass`.
*   [fzy (⭐58)](https://github.com/aperezdc/zsh-fzy) - Plugin that uses [fzy (⭐3.1k)](https://github.com/jhawthorn/fzy) for certain fuzzy matching operations.
*   [gcloud-project (⭐10)](https://github.com/avivl/gcloud-project) - Easy selection of Google Cloud Projects.
*   [gcloud (⭐4)](https://github.com/wintermi/zsh-gcloud) - Finds the installed gcloud sdk and sources the zsh file there, along with the zsh completions file.
*   [gdbm (⭐0)](https://github.com/zdharma-continuum/zgdbm) - Adds GDBM as a plugin.
*   [gentoo (⭐4)](https://github.com/MattiaG-afk/gentoo-ohmyzsh) - Adds some aliases and functions to work with Gentoo Linux.
*   [geometry-datetime (⭐2)](https://github.com/desyncr/geometry-datetime) - [Geometry (⭐959)](https://github.com/geometry-zsh/geometry) datetime plugin. Shows datetime (`date` unix command) in your prompt.
*   [geometry-hydrate (⭐1)](https://github.com/jedahan/geometry-hydrate) - [Geometry (⭐959)](https://github.com/geometry-zsh/geometry) plugin to remind you to hydrate.
*   [geometry-npm-package-version (⭐1)](https://github.com/drager/geometry-npm-package-version) - [Geometry (⭐959)](https://github.com/geometry-zsh/geometry) plugin to display the current folder's npm package version.
*   [geometry-rust-version (⭐2)](https://github.com/drager/geometry-rust-version) - [Geometry (⭐959)](https://github.com/geometry-zsh/geometry) plugin to display the current folder's Rust version when either a `.rs` or `Cargo.toml` is present.
*   [get-jquery (⭐1)](https://github.com/voronkovich/get-jquery.plugin.zsh) - Plugin for fast downloading the jQuery library from [code.jquery.com](https://code.jquery.com).
*   [ghost-zeus (⭐2)](https://github.com/fontno/ghost_zeus) - Lets you use [zeus (⭐3.3k)](https://github.com/burke/zeus) with normal rails commands.
*   [gimbo-git (⭐1)](https://github.com/gimbo/gimbo-git.zsh) - A subset of the [oh-my-zsh](https://ohmyz.sh/) [git plugin (⭐178k)](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/git/git.plugin.zsh) aliases, plus some new aliases, plus a few handy functions.
*   [gimme (⭐2)](https://github.com/folixg/gimme-ohmyzsh-plugin) - Manage [Go](https://golang.org/) installations with [gimme (⭐711)](https://github.com/travis-ci/gimme/).
*   [git-acp (⭐6)](https://github.com/MenkeTechnologies/zsh-git-acp) - Take the current command line as the commit message and then run `git pull`, `git add`, `git commit` and `git push` with one keystroke.
*   [git-add-remote (⭐13)](https://github.com/caarlos0/git-add-remote) - Easily add the upstream remote to your `git` fork.
*   [git-aliases (mdumitru) (⭐30)](https://github.com/mdumitru/git-aliases) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of [oh-my-zsh](https://ohmyz.sh).
*   [git-aliases (peterhurford) (⭐83)](https://github.com/peterhurford/git-aliases.zsh) - Creates a lot of useful aliases for combinations of commonly used `git` commands.
*   [git-aliases (remino) (⭐0)](https://github.com/remino/omz-plugin-git-aliases) - Aliases all `git xyz` commands to `gxyz`. Also aliases `g` to `git`.
*   [git-arc (⭐0)](https://github.com/jlduran/git-arc-oh-my-zsh-plugin) - Adds aliases and functions for [git-arc (⭐8.2k)](https://github.com/freebsd/freebsd-src/tree/main/tools/tools/git), a FreeBSD development tool.
*   [git-branches (⭐8)](https://github.com/Schroefdop/git-branches) - Makes a menu of `git` branches you can switch to without having to type long branch names.
*   [git-check (⭐1)](https://github.com/git-girl/git-check) - Adds a ZSH hook to check if the origin of the current branch has changes to local in the background and sends a notification.
*   [git-clean-branch (⭐2)](https://github.com/gobriansteele/git-clean-branch) - Cleans up dead `git` branches.
*   [git-complete-urls (⭐3)](https://github.com/rapgenic/zsh-git-complete-urls) - Enhance `git` completion to include in the remotes completion (e.g. from `git clone`) any URL in the clipboard.
*   [git-extra-commands (⭐1.1k)](https://github.com/unixorn/git-extra-commands) - Extra `git` helper scripts packaged as a plugin.
*   [git-flow-avh (⭐6)](https://github.com/nekofar/zsh-git-flow-avh) - Adds short aliases for the `git-flow` commands.
*   [git-fuzzy (⭐2.4k)](https://github.com/bigH/git-fuzzy) - A CLI interface to `git` that relies heavily on [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [git-gen (⭐0)](https://github.com/sharif3271/git-gen) - Handle `git` bulk branch delete and create operations.
*   [git-ignore (⭐30)](https://github.com/laggardkernel/git-ignore) - Generates `.gitignore` files from gitignore.io **offline**. [fzf (⭐70k)](https://github.com/junegunn/fzf), completion, preview integrated.
*   [git-is-clean (⭐2)](https://github.com/aubreypwd/zsh-plugin-git-is-clean) - This function will return true or false depending on if it finds out your `git` repo is dirty or not.
*   [git-it-on (⭐113)](https://github.com/peterhurford/git-it-on.zsh) - Adds ability to open a folder in your current branch on GitHub.
*   [git-lfs (⭐3)](https://github.com/nekofar/zsh-git-lfs) - Adds short aliases for the `git-lfs` commands.
*   [git-patch (⭐0)](https://github.com/marvinroman/oh-my-zsh-git-patch-plugin) - Adds custom functions and aliases to the oh-my-zsh `git` plugin.
*   [git-plugin (dark-kitt) (⭐0)](https://github.com/dark-kitt/zsh-git-plugin) - `git` integration that displays the current directory and `git` branch.
*   [git-plugin (rcruzper) (⭐7)](https://github.com/rcruzper/zsh-git-plugin) - Adds some functions for `git`.
*   [git-prompt-enhanced (⭐2)](https://github.com/LFabre/zsh-git-prompt-enhanced) - Provides a more granular information about a `git` repository.
*   [git-prompt-useremail (⭐8)](https://github.com/mroth/git-prompt-useremail) - Adds prompt reminders for `git` user.email.
*   [git-prune (diazod) (⭐35)](https://github.com/diazod/git-prune) - Allows you to delete all branches that are already merged in your local `git` repository and/or that were merged in your remote origin `git` repository.
*   [git-prune (seinh) (⭐35)](https://github.com/Seinh/git-prune) - Plugin that simplifies deleting merged branches in a `git` repository.
*   [git-scripts (⭐1)](https://github.com/packruler/zsh-git-scripts) - Adds `git-squash-branch` and `git-remove-merged` commands.
*   [git-secret (⭐3.8k)](https://github.com/sobolevn/git-secret) - A bash-tool to store your private data inside a `git` repository.
*   [git-smart-commands (⭐12)](https://github.com/seletskiy/zsh-git-smart-commands) - Adds extra `git` commands to make some common `git` usages more efficient.
*   [git-smart-commends-wrapper (⭐0)](https://github.com/jelek21/omz-git-smart-commands) - Wraps [git-smart-commands (⭐12)](https://github.com/seletskiy/zsh-git-smart-commands) to make it compatible with the [oh-my-zsh](https://ohmyz.sh) plugins system.
*   [git-status (⭐3)](https://github.com/AyoubMounim/zsh-git-status/) - Exposes functions with information about the current `git` repository.
*   [git-switch-branch-skim (⭐0)](https://github.com/okhiroyuki/zsh-git-switch-branch-skim) - Allows you to switch `git` branches with [skim (⭐5.6k)](https://github.com/lotabout/skim)
*   [git-sync (⭐46)](https://github.com/caarlos0-graveyard/zsh-git-sync) - A ZSH plugin to sync `git` repositories and clean them up.
*   [git-tree (⭐1)](https://github.com/dehlen/git-tree-zsh) - [fzf (⭐70k)](https://github.com/junegunn/fzf) powered `git worktree` helper.
*   [git-worktree (⭐25)](https://github.com/alexiszamanidis/zsh-git-worktree) - Wraps some `git worktree` operations for simplicity and productivity. Includes [fzf (⭐70k)](https://github.com/junegunn/fzf) tooling.
*   [git-worktrees (⭐14)](https://github.com/egyptianbman/zsh-git-worktrees) - Makes `git` worktrees more functional. Includes tab completions.
*   [git (⭐49)](https://github.com/davidde/git) - Replacement for the stock [oh-my-zsh](https://ohmyz.sh/) `git` plugin. Provides quite a few useful aliases and functions. The motivation to replace the default plugin stems from the fact that it comes with some inconsistencies that make a few popular commands rather unintuitive, so this plugin makes the aliases consistent.
*   [gitcd (SukkaW) (⭐5)](https://github.com/SukkaW/zsh-gitcd) - Adds command to `git clone` a repository and `cd` into the resulting directory.
*   [gitcd (viko16) (⭐11)](https://github.com/viko16/gitcd.plugin.zsh) - Automatically `cd` to a `git` working directory after cloning it.
*   [gitfast (⭐8)](https://github.com/tevren/gitfast-zsh-plugin) - Updated fork of the [oh-my-zsh](https://ohmyz.sh/) `gitfast` plugin.
*   [gitgo (⭐11)](https://github.com/ltj/gitgo) - Open a GitHub/GitLab repository in your browser from the command line (macOS only).
*   [github-folders (⭐0)](https://github.com/buzuloiu/zsh-github-folders) - Organizes your GitHub checkouts for you.
*   [github (⭐1)](https://github.com/shakir-abdo/zsh-github-plugin) - Fork of the original [GitHub plugin (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/github) embedded in [oh-my-zsh](https://ohmyz.sh/).
*   [gitignore (valerius21) (⭐0)](https://github.com/valerius21/omz-gitignore) - [oh-my-zsh](https://ohmyz.sh)'s gitignore plugin extracted to be standalone
*   [gitignore (voronkovich) (⭐53)](https://github.com/voronkovich/gitignore.plugin.zsh) - Plugin for creating `.gitignore` files.
*   [gitio (denysdovhan) (⭐22)](https://github.com/denysdovhan/gitio-zsh) - A ZSH plugin for generating a GitHub short URL using [git.io](https://git.io).
*   [gitio (nicolodiamante) (⭐4)](https://github.com/nicolodiamante/gitio) - Uses [git.io](https://git.io/) to shorten `git` urls.
*   [gitsync (⭐4)](https://github.com/washtubs/gitsync) - ZSH plugin to improve workflows for one person developing on the same repository on multiple machines.
*   [goenv (bbenne10) (⭐6)](https://github.com/bbenne10/goenv) - Manage `$GOPATH` similarly to Python's virtualenvwrapper.
*   [goenv (cda0) (⭐1)](https://github.com/CDA0/zsh-goenv/) - Plugin for installing, updating and loading `goenv`.
*   [goenv (heyvito) (⭐1)](https://github.com/heyvito/goenv.zsh) - Automatically reads `.goenv` files in the current directory and sets `GOPRIVATE` environment variables.
*   [going\_places (⭐2)](https://github.com/or17191/going_places) - A plugin that helps to use, create and maintain a list of shell locations.
*   [golang (⭐5)](https://github.com/wintermi/zsh-golang) - Adds tooling for the Go programming language toolchain.
*   [golinks (⭐0)](https://github.com/slessans/oh-my-zsh-golinks-plugin) - Launch golinks from your terminal.
*   [gpg-agent (⭐12)](https://github.com/axtl/gpg-agent.zsh) - Plugin that tries to do the right thing when it comes to setting up the GPG agent to act as an SSH agent as well on macOS.
*   [gpg-crypt (⭐9)](https://github.com/Czocher/gpg-crypt) - ZSH plugin to encrypt and decrypt files or directories in place.
*   [gpg (⭐0)](https://github.com/marvinroman/oh-my-zsh-gpg-plugin) - Adds helpful aliases for using `gpg`.
*   [gpt (⭐20)](https://github.com/antonjs/zsh-gpt) - Enable querying ChatGPT from the command line.
*   [grep2awk (⭐27)](https://github.com/joepvd/grep2awk) - ZLE widget to transform `grep` command into `awk` command.
*   [grunt-plugin (⭐7)](https://github.com/clauswitt/zsh-grunt-plugin) - Add autocompletion for `grunt`.
*   [gsh (⭐1)](https://github.com/cjayross/gsh) - Collection of helper functions for `git`
*   [gtm-terminal-plugin (⭐16)](https://github.com/git-time-metric/gtm-terminal-plugin) - terminal plugin for [git time metrics (⭐992)](https://github.com/git-time-metric/gtm).
*   [gtr (⭐0)](https://github.com/Zocker1999NET/zsh-gtr) - Allows fast tagging of a release in `git` using the tag name \**release-YYYY-MM-DD-HH-MM*- and headline **Release YYYY-MM-DD HH:MM**.
*   [guish (⭐6)](https://github.com/gcarrarom/oh-my-guish) - Collection of utility functions and aliases.
*   [gumsible (⭐3)](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) - Wrapper plugin for [Molecule](https://molecule.readthedocs.io/).
*   [gunstage (⭐64)](https://github.com/LucasLarson/gunstage) - There are at least eight ways to unstage files in a `git` repository. This is a command-line shell plugin for undoing `git add`.
*   [gvm (dgnest) (⭐5)](https://github.com/dgnest/zsh-gvm-plugin) - A `gvm` (Go version manager) plugin for ZSH.
*   [gvm (yerinle) (⭐1)](https://github.com/yerinle/zsh-gvm) - Provides autocompletion for `gvm` (Groovy enVironment Manager).
*   [hab (⭐11)](https://github.com/alexdesousa/hab) - Automatically loads OS environment variables defined in the file `.envrc` if it's found when changing to a new directory.
*   [hacker-quotes (⭐96)](https://github.com/oldratlee/hacker-quotes) - Outputs a random hacker quote when you open a terminal.
*   [haiku (⭐2)](https://github.com/alesr/oh-my-zsh-haiku-plugin) - Prints a haiku promoting work-life balance and stress management once every 24 hours when the terminal is open.
*   [hanami (⭐7)](https://github.com/davydovanton/hanami-zsh) - ZSH plugin for [hanami](http://hanamirb.org) projects.
*   [hangul (⭐168)](https://github.com/gomjellie/zsh-hangul) - Auto correct hangul(한글, korean) to English when it was supposed to be typed in English. 영어를 타이핑 해야되는데 한글로 타이핑된경우 자동으로 수정합니다.
*   [hbt (⭐10)](https://github.com/lzambarda/hbt) - Heuristic ZSH suggestion system based on past command usage.
*   [hebzsh (⭐1)](https://github.com/admons/hebzsh) - If a command is not found as typed in Hebrew, translates the command as if it was typed on a keyboard with a US English layout and tries again.
*   [help (⭐14)](https://github.com/Freed-Wu/zsh-help) - Colorizes the output of commands run with `--help`.
*   [hints (⭐62)](https://github.com/joepvd/zsh-hints) - Display glob and parameter flags and other non completable info right under your editing buffer.
*   [hipchat (⭐13)](https://github.com/robertzk/hipchat.zsh) - Send hipchat messages from the shell.
*   [hist-delete (⭐1)](https://github.com/p1r473/zsh-hist-delete-fzf/) - Delete history items from zsh's [fzf (⭐70k)](https://github.com/junegunn/fzf) Ctrl+R history search.
*   [hist (⭐158)](https://github.com/marlonrichert/zsh-hist) - Edit your history in ZSH, without ever leaving the command line.
*   [histdb (⭐1.3k)](https://github.com/larkery/zsh-histdb) - Stores your history in an SQLite database. Can be integrated with [zsh-autosuggestions (⭐33k)](https://github.com/zsh-users/zsh-autosuggestions).
*   [historikeeper (⭐1)](https://github.com/stiliajohny/historikeeper) - Captures history in a database.
*   [history-enquirer (⭐89)](https://github.com/zthxxx/zsh-history-enquirer) - Enhances history search with more interaction and a multiline selection menu. Requires Node.js.
*   [history-filter (⭐32)](https://github.com/MichaelAquilina/zsh-history-filter) - Allows you to specify patterns that will automatically exclude commands from being inserted into your permanent history. Particularly useful for preventing secrets being written.
*   [history-here (⭐9)](https://github.com/leonjza/history-here) - Binds `^G` to quickly toggle the current shell history file location.
*   [history-on-success (⭐1)](https://github.com/nyoungstudios/zsh-history-on-success) - Save yourself from repeating the same mistakes by filtering out your unsuccessful commands from your zsh history file. Based on a [blog post](https://scarff.id.au/blog/2019/zsh-history-conditional-on-command-success/) by Dean Scarff.
*   [history-popup (⭐0)](https://github.com/lcrespom/oh-my-zsh-history-popup) - Captures the `PageUp` key and uses `dialog` to open a popup menu with the history, so the user can interactively navigate through it and pick the history line to bring back to the prompt.
*   [history-search-multi-word (⭐111)](https://github.com/zdharma-continuum/history-search-multi-word) - A syntax highlighted, multi-word history searcher for ZSH, bound to Ctrl-R, with advanced functions (e.g. bump of history entry to top of history).
*   [history-substring-search (⭐2.8k)](https://github.com/zsh-users/zsh-history-substring-search) - Needs to be loaded after `zsh-syntax-highlighting`, or they'll both break. You'll also need to bind keys to its functions, details are in the README.md.
*   [history-sync (vitobotta) (⭐25)](https://github.com/vitobotta/zsh-history-sync/) - Syncs your ZSH history across computers using a `git` private repository. Uses `openssl` to encrypt the history.
*   [history-sync (wulfgarpro) (⭐253)](https://github.com/wulfgarpro/history-sync) - An [oh-my-zsh](https://ohmyz.sh/) plugin for [GPG](https://www.gnupg.org/) encrypted, Internet synchronized ZSH history using `git`.
*   [history (⭐83)](https://github.com/b4b4r07/zsh-history) - Extend history so that it can be queried by SQL.
*   [histree (⭐4)](https://github.com/fuba/histree-zsh) - Integrates with [histree-core (⭐10)](https://github.com/fuba/histree-core) to provide enhanced command history logging with directory awareness.
*   [hitokoto (⭐13)](https://github.com/derry96/hitokoto) - Displays a random quote from [hitokoto.cn](https://hitokoto.cn/).
*   [homeassistant-cli (⭐3)](https://github.com/frosit/zsh-plugin-homeassistant-cli) - Provides completion and (configuration) helpers for the [Home Assistant Command-line interface (hass-cli) (⭐461)](https://github.com/home-assistant/home-assistant-cli). and allows command line interaction with [Home Assistant](https://home-assistant.io/) instances.
*   [homebrew (⭐6)](https://github.com/digitalraven/omz-homebrew) - Plugin for [homebrew](https://brew.sh) that supplements the one built into oh-my-zsh and can safely run with it enabled.
*   [hooks (⭐60)](https://github.com/willghatch/zsh-hooks) - Add missing hooks - for plugins and personal use.
*   [host-switch (⭐6)](https://github.com/LockonS/host-switch) - Make it easier to switch in different `/etc/hosts` files during development.
*   [hub-ci-zsh-plugin (⭐0)](https://github.com/raymondjcox/hub-ci-zsh-plugin) - A simple plugin for adding `hub` ci-status to your ZSH theme.
*   [hub (⭐9)](https://github.com/soraliu/zsh-hub) - ZSH plugin for forking model.
*   [hypnosnek (⭐0)](https://github.com/josephcourtney/hypnosnek) - Simple utilities with p10k integration for managing `python` environments.
*   [igit (⭐16)](https://github.com/ytakahashi/igit) - Interactive `git` commands using [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [incsearch (⭐5)](https://github.com/aoyama-val/zsh-incsearch) - Friendlier `vim` mode for ZSH. Moves cursor with incremental search within current line.
*   [ing (⭐3)](https://github.com/rummik/zsh-ing) - Streamlined `ping` output.
*   [instant-repl (⭐3)](https://github.com/jandamm/instant-repl.zsh) - Activate a REPL for any command in your current ZSH session.
*   [interactive-cd (⭐327)](https://github.com/changyuheng/zsh-interactive-cd) - Fish-like interactive tab completion for `cd`.
*   [iosctl (⭐4)](https://github.com/obayer/iosctl) - Quickly access App, Data, and Log of the running simulator.
*   [ipip (⭐16)](https://github.com/SukkaW/zsh-ipip) - Plugin for [IPIP](https://en.ipip.net).
*   [iterm-tab-color (⭐49)](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) - Adds function to set the tab color in iTerm2 and can automatically change color based on cwd or command being executed.
*   [iterm-tab-colors (⭐48)](https://github.com/tysonwolker/iterm-tab-colors) - Automatically changes iTerm 2 tab color based on the current working directory.
*   [iterm-tmux-color-tabs (⭐1)](https://github.com/remino/omz-plugin-iterm2-tmux-color-tabs) - Every new `tmux` tab opened in iTerm2 will have the next colour from the default or specified palette.
*   [iterm-touchbar (⭐689)](https://github.com/iam4x/zsh-iterm-touchbar) - Display iTerm2 feedback in the MacbookPro TouchBar (Current directory, git branch & status).
*   [iterm2-colors (⭐4)](https://github.com/shayneholmes/zsh-iterm2colors) - Manage your iTerm 2's color scheme from the command line.
*   [iterm2-shell-integration (⭐57)](https://github.com/gnachman/iterm2-shell-integration) - Shell integration and utilities for iTerm2.
*   [iterm2-tabs (⭐7)](https://github.com/gimbo/iterm2-tabs.zsh) - Set colors and titles of iTerm 2 tabs.
*   [iterm2 (⭐10)](https://github.com/laggardkernel/zsh-iterm2) - Packs iTerm 2's ZSH integration scripts into a ZSH plugin to avoid polluting your $HOME directory, with a negligible time increase of only 2ms.
*   [iwd (⭐3)](https://github.com/zshzoo/iwd) - Similar in concept to `$PWD`, this ZSH plugin saves your initial working directory in `$IWD` for easy returns to the starting point of your session.
*   [jabba (⭐5)](https://github.com/2m/zsh-jabba) - Adds shell integration code and completions for the [jabba (⭐3.2k)](https://github.com/shyiko/jabba) Java version manager.
*   [java-zsh-plugin (⭐1)](https://github.com/Xetius/java-zsh-plugin) - Adds a `setjdk` command so you can switch easily between different versions of the jdk.
*   [javaVersions (⭐7)](https://github.com/miguefl/javaVersions) - Change between different java versions with a single command.
*   [jdk-switch (⭐12)](https://github.com/LockonS/jdk-switch) - Switches between jdk versions. Works on macOS and Linux.
*   [jenkins (⭐6)](https://github.com/tomplex/jenkins-zsh) - A jenkins plugin for ZSH, heavily inspired by the excellent jira plugin.
*   [jenv-lazy (⭐7)](https://github.com/shihyuho/zsh-jenv-lazy) - A ZSH plugin for lazy loading of jEnv.
*   [jhipster (⭐39)](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - Adds commands for [jHipster](https://www.jhipster.tech/).
*   [jira-plus (⭐6)](https://github.com/gerges/oh-my-zsh-jira-plus) - Create JIRA tickets from the command line.
*   [jj (⭐0)](https://github.com/rkh/zsh-jj) - Add support for [jujitsu (⭐13k)](https://github.com/jj-vcs/jj) VCS.
*   [jq (⭐330)](https://github.com/reegnz/jq-zsh-plugin) - Interactively build [jq](https://stedolan.github.io/jq/) expressions. Also supports [gojq (⭐3.5k)](https://github.com/itchyny/gojq). Requires [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [jrgit (⭐0)](https://github.com/jrocha-dev/ohmyzsh-plugin-jrgit) - Provides a suite of functions to streamline the Git user experience. It includes features for installing and configuring Git, handling large files with Git LFS, improving diff outputs, and managing credentials and keys securely.
*   [jumper (⭐4)](https://github.com/thestuckster/jumper) - Saves your current path and allows you to quickly jump to others.
*   [jvm (⭐4)](https://github.com/mgryszko/jvm) - Allows selection of JDK on macOS.
*   [k (⭐1.8k)](https://github.com/supercrabtree/k) - Directory listings for ZSH with `git` status decorations.
*   [k3d (⭐8)](https://github.com/dwaynebradley/k3d-oh-my-zsh-plugin) - Adds aliases and tab completions for [k3d](https://k3d.io/).
*   [kctl (⭐3)](https://github.com/yzdann/kctl) - Add helper aliases for `kubectl`.
*   [kill-node (⭐7)](https://github.com/vmattos/kill-node) - ZSH plugin for murdering `node` process families.
*   [kitsunebook (⭐0)](https://github.com/d12frosted/kitsunebook.plugin.zsh) - KitsuneBook plugin for [oh-my-zsh](https://ohmyz.sh).
*   [kittyback (⭐0)](https://github.com/pickle-slime/kittyback) - Automatically updates and modifies the background image for the `kitty` terminal emulator.
*   [kiwi (⭐0)](https://github.com/fruitydog/kiwi.zsh-theme) - Dog-themed, includes `git` status and last command exit status decorators.
*   [konsole-theme-changer (⭐2)](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - Toggle konsole theme from ZSH.
*   [kube-aliases (⭐119)](https://github.com/Dbz/kube-aliases) - Adds functions and aliases to make working with `kubectl` more pleasant.
*   [kube-ps1 (⭐3.7k)](https://github.com/jonmosco/kube-ps1) - ZSH plugin for `kubectl` that adds current context and namespace.
*   [kubecolor (devopstales) (⭐7)](https://github.com/devopstales/zsh-kubecolor) - Adds aliases for the `kubecolor` command.
*   [kubecolor (droctothorpe) (⭐8)](https://github.com/droctothorpe/kubecolor) - Simplify and colorize the output of `kubectl get events -w`
*   [kubecolor (trejo08) (⭐4)](https://github.com/trejo08/kubecolor-zsh) - Prints colorized outputs from  `kubectl`. Includes helper functions.
*   [kubeconfig-mgr (⭐7)](https://github.com/yhlooo/zsh-kubeconfig-mgr) - Makes managing multiple kubeconfig files easier.
*   [kubectl-config-switcher (⭐2)](https://github.com/chmouel/kubectl-config-switcher/) - Switch between config files in `~/.kube` via the `KUBECTL` environment variable.
*   [kubectl-prompt (⭐575)](https://github.com/superbrothers/zsh-kubectl-prompt) - Display information about the kubectl current context and namespace in your ZSH prompt. Creates `ZSH_KUBECTL_CONTEXT`, `ZSH_KUBECTL_NAMESPACE`,`ZSH_KUBECTL_PROMPT` and `ZSH_KUBECTL_USER` variables you can use to customize your prompt.
*   [kubectl (⭐6)](https://github.com/mattbangert/kubectl-zsh-plugin) - ZSH plugin for managing `kubectl`.
*   [kubectlenv (⭐0)](https://github.com/rafalmasiarek/oh-my-zsh-kubectlenv-plugin) - Easily switch between multiple `kubectl` versions.
*   [kubectx (ptavares) (⭐0)](https://github.com/ptavares/zsh-kubectx) - Installs and loads [kubectx (⭐19k)](https://github.com/ahmetb/kubectx).
*   [kubectx (unixorn) (⭐7)](https://github.com/unixorn/kubectx-zshplugin) - Automatically installs [kubectx (⭐19k)](https://github.com/ahmetb/kubectx) and `kubens`.
*   [kubernetes (⭐119)](https://github.com/Dbz/zsh-kubernetes) - Add [kubernetes](https://kubernetes.io) helper functions and aliases.
*   [lacrimae (⭐2)](https://github.com/caIamity/lacrimae) - Prints a line from a collection of chants.
*   [lando (joshuabedford) (⭐8)](https://github.com/JoshuaBedford/lando-zsh) - A collection of alias functions to enable the use of the CLIs within [Lando](https://docs.lando.dev) without having to type lando to access them.
*   [lando (mannuel) (⭐0)](https://github.com/mannuel/lando-alias-zsh) - Adds aliases for various [Lando](https://docs.lando.dev/basics/usage.html#default-commands/) commands.
*   [laradock-workspace (⭐1)](https://github.com/rluders/laradock-workspace-zsh) - Provides an interface to [Laradock](http://laradock.io/)'s workspace.
*   [laravel (baliestri) (⭐0)](https://github.com/baliestri/laravel.plugin.zsh) - Plugin for skiping the `php` command when running `artisan` commands and `./sail` or `./vendor/bin/sail` when running `sail` commands.
*   [laravel (crazybooot) (⭐17)](https://github.com/crazybooot/laravel-zsh-plugin) - Add shortcuts for [Laravel](https://laravel.com/) 5, 5.1, 5.2 & 5.3.
*   [laravel-au (⭐8)](https://github.com/Saleh7/laravel-au-zsh-plugin) - Adds aliases for [Laravel](https://laravel.com/) 6.
*   [laravel-sail (⭐38)](https://github.com/ariaieboy/laravel-sail) - Adds shortcuts for `sail` commands.
*   [laravelx (⭐1)](https://github.com/rsthegeek/oh-my-zsh-laravelx) - Adds some aliases for common [Laravel](https://laravel.com/docs) commands.
*   [last-working-dir-tmux (⭐1)](https://github.com/Curly-Mo/last-working-dir-tmux) - Keeps track of the last used working directory globally and per [tmux (⭐37k)](https://github.com/tmux/tmux) session and automatically jumps into it for new shells.
*   [last-working-directory (⭐8)](https://github.com/mdumitru/last-working-dir) - Broken out copy of the version in [oh-my-zsh](http://ohmyz.sh/). Keeps track of the last used working directory and automatically jumps into it for new shells.
*   [lazy-load (⭐3)](https://github.com/goarano/zsh-lazy-load) - Lazy load tab completions only when you actually need them.
*   [lazyload (⭐129)](https://github.com/qoomon/zsh-lazyload) - Lazy load commands and speed up start up time of ZSH.
*   [learn (⭐6)](https://github.com/MenkeTechnologies/zsh-learn) - Learning collection in MySQL/MariadB to save, query and quiz everything you learn.
*   [lesaint-git (⭐0)](https://github.com/lesaint/lesaint-git) - Replacement `git` plugin for [oh-my-zsh](https://ohmyz.sh)-compatible frameworks.
*   [lesaint-mvn (⭐0)](https://github.com/lesaint/lesaint-mvn) - Maven plugins for [oh-my-zsh](https://ohmyz.sh).
*   [life-progress (⭐0)](https://github.com/bGZo/life-progress) - Shows your life progress in days, weeks, months, and age.
*   [liferay (⭐3)](https://github.com/david-gutierrez-mesa/liferay-zsh) - Adds scripts for [liferay (⭐2.1k)](https://github.com/liferay/liferay-portal) development.
*   [linkfile (⭐1)](https://github.com/JaumeRF/linkfile-zsh) - Add shortcuts to your favorite directories.
*   [linus-rants (⭐29)](https://github.com/bhayward93/Linus-rants-ZSH) - Outputs a random Linus Torvalds rant when opening a terminal.
*   [listbox (⭐46)](https://github.com/gko/listbox) - Listbox element for shell.
*   [llm-suggestions (⭐47)](https://github.com/stefanheule/zsh-llm-suggestions) - Type something in English at the prompt, hit a definable key, and it uses LLM to generate a command line for you.
*   [locate-sublime-projects-cli (⭐1)](https://github.com/david-treblig/locate-sublime-projects-cli) - Allows searching for [Sublime Text](https://www.sublimetext.com) projects and opens them in Sublime.
*   [loremipsum (⭐0)](https://github.com/pfahlr/zsh_plugin_loremipsum) - Generate lorem ipsum text on the command line. Gets its data from [lipsum.com](https://www.lipsum.com).
*   [ls (twopizza9621536) (⭐0)](https://github.com/TwoPizza9621536/zsh-ls) - Adds some more aliases for `ls`.
*   [ls (zpm-zsh) (⭐100)](https://github.com/zpm-zsh/ls) - Colorizes the output of `ls`.
*   [lsd (tankeryang) (⭐0)](https://github.com/tankeryang/zsh-lsd) - Replaces `ls` and `tree` commands with [lsd (⭐14k)](https://github.com/Peltoche/lsd).
*   [lsd (wintermi) (⭐6)](https://github.com/wintermi/zsh-lsd) - Override `ls` and `tree` commands with [lsd (⭐14k)](https://github.com/Peltoche/lsd).
*   [lsd (z-shell) (⭐13)](https://github.com/z-shell/zsh-lsd) - Replaces `ls` with [lsd (⭐14k)](https://github.com/Peltoche/lsd).
*   [lumberjack (⭐43)](https://github.com/molovo/lumberjack) - Lumberjack is a logging interface for shell scripts.
*   [lux (⭐35)](https://github.com/pndurette/zsh-lux) - ZSH plugin to toggle the light & dark modes of macOS, iTerm 2, Visual Studio Code and other items and applications via the `lux` command. Highly customizable: included items can be configured by defining variables. Highly extensible: items can be added by defining functions. Includes a `macos_is_dark` helper function to determine if the macOS dark mode is active for use in theming.
*   [mac-packaging (⭐1)](https://github.com/Temikus/mac-packaging) - A set of common functions used for enterprise Mac packaging with [Munki](https://www.munki.org/munki/).
*   [macos (joow) (⭐3)](https://github.com/joow/macos) - A ZSH plugin for macOS.
*   [macos (zshzoo) (⭐21)](https://github.com/zshzoo/macos) - ZSH goodies for macOS users.
*   [macos-theme (⭐0)](https://github.com/gakimball/zsh-macos-theme) - Adds the theme command, which toggles between light and dark mode in macOS. Requires [lux (⭐35)](https://github.com/pndurette/zsh-lux) plugin.
*   [mage2docker (⭐12)](https://github.com/lukaszolszewski/mage2docker) - Makes it easy to work with Docker and Magento 2. Speeds up and simplifies common commands like clean cache, setup upgrade, compile di and much more in Magento 2 on containers.
*   [magento-2 (⭐27)](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) - Adds `m2` function to run magento binary, adds tab completions.
*   [magic-enter (⭐16)](https://github.com/zshzoo/magic-enter) - Make your enter key magical by binding a ZSH command to it.
*   [manydots-magic (⭐45)](https://github.com/knu/zsh-manydots-magic) - A zle tweak for emulating `...'==`../..' etc.
*   [markedit (⭐7)](https://github.com/zakariaGatter/MarkEdit) - Mark files and edit them with autocompletion for existing marks.
*   [markgate (⭐7)](https://github.com/zakariaGatter/MarkGate) - Allows you to mark directories so you can jump directly to them.
*   [maven-plugin (⭐1)](https://github.com/KyleChamberlin/zsh_maven_plugin) - A fork of the [oh-my-zsh](https://ohmyz.sh/) maven plugin.
*   [media-sync (⭐0)](https://github.com/redxtech/zsh-media-sync) - A plugin to facilitate copying media between two `rclone` locations.
*   [mercurial (⭐2)](https://github.com/hcgraf/zsh-mercurial) - Extracted from [oh-my-zsh](https://ohmyz.sh) so you can use it without the rest of oh-my-zsh.
*   [mfunc (⭐7)](https://github.com/hlohm/mfunc) - Allows you to define persistent functions on-the-fly, without the need to add them to your config files. These functions are permanently available until you delete them.
*   [mise (⭐13)](https://github.com/wintermi/zsh-mise) - Plugin for [mise](https://mise.jdx.dev/) (formerly called rtx) a fast polyglot version manager, replacing tools like `nvm`, `nodenv`, `rbenv`, `rvm`, `chruby`, `pyenv`, etc.
*   [mkarch (⭐5)](https://github.com/0xRZ/mkarch) - ZSH plugin that allows you to create archives using multiple different compression formats.
*   [mkcd (⭐1)](https://github.com/marvinroman/oh-my-zsh-mkcd-plugin) - Allows user to create a directory and if successful, `cd` into it afterward.
*   [mode-switch.CLI (⭐3)](https://github.com/Gyumeijie/mode-switch.CLI) - A ZSH plugin for switching command line between normal mode and `vi` mode.
*   [monorepo-plugin (⭐2)](https://github.com/zilongqiu/monorepo-zsh-plugin) - ZSH plugin for monorepo management.
*   [monthrename (⭐1)](https://github.com/NotTheDr01ds/zsh-plugin-monthrename) - Renames month names to numbers in filenames.
*   [more-hooks-for-git (⭐2)](https://github.com/capsulescodes/more-hooks-for-git) - Adds extra hooks for `git add`, `git diff` and `git status`.
*   [mouse-status (⭐3)](https://github.com/gryffyn/mouse-status) - Changes mouse color based on status code, uses libratbag.
*   [msf (⭐14)](https://github.com/sathish09/zsh_plugins/tree/master/msf) - [Metasploit](https://www.metasploit.com/) handler plugin for starting handlers easily.
*   [multi-evalcache (⭐0)](https://github.com/rwwiv/multi-evalcache) - Cache multiple eval loads to improve startup time, inspired by [mroth/evalcache (⭐216)](https://github.com/mroth/evalcache).
*   [mvn-contexts (⭐3)](https://github.com/artemy/zsh-mvn-contexts) - Allows fast switching between `maven` configurations.
*   [mycli (⭐1)](https://github.com/remino/omz-plugin-mycli-alias) - Add alias for [`mycli`](https://www.mycli.net) with login path.
*   [mylocation (⭐10)](https://github.com/fALKENdk/mylocation) - A plugin to show your current location based on your IP address.
*   [myservice (⭐1)](https://github.com/jarlor/zsh-myservice) - Designed to help you manage custom systemd services and Docker containers more conveniently. This plugin provides user-friendly commands to list and check the status of your custom services and Docker containers straight from your command line.
*   [mysql-colorize (⭐106)](https://github.com/zpm-zsh/mysql-colorize) - Adds color for `mysql` tables.
*   [mysql-login (⭐0)](https://github.com/remino/omz-plugin-mysql-alias) - Adds alias for MySQL with login path.
*   [mysql (⭐17)](https://github.com/voronkovich/mysql.plugin.zsh) - Adds some functions for dealing with `mysql`.
*   [n (⭐10)](https://github.com/gretzky/n.zsh) - Auto-switches node versions based on project environment using [n (⭐19k)](https://github.com/tj/n).
*   [namelink (⭐4)](https://github.com/jthat/zsh-namelink) - Provides an automatically synchronized mapping of filesystem entries (typically symbolic links) in a set of directories to their counterparts in the named directory hash.
*   [navi (⭐2)](https://github.com/icatalina/zsh-navi-plugin/) - Plugin for [navi (⭐16k)](https://github.com/denisidoro/navi).
*   [navigation-tools (⭐10)](https://github.com/zdharma-continuum/zsh-navigation-tools) - Adds `htop`-like kill, directory bookmarks browser, a multi-word incremental history searcher and more.
*   [nerd-font-check (⭐0)](https://github.com/delorenj/nerd-font-check) - Offers to install [Nerd Fonts](https://www.nerdfonts.com/font-downloads) with [brew](https://brew.sh/) if not present.
*   [new-file-from-template (⭐14)](https://github.com/zpm-zsh/new-file-from-template) -  Generates file from template.
*   [newvwp (⭐2)](https://github.com/aubreypwd/zsh-plugin-newvwp) - Spins up a new WordPress site using Valet.
*   [nhl-schedule (⭐1)](https://github.com/Matt561/zsh-nhl-schedule) - Retrieves and displays the NHL schedule.
*   [nice-exit-code (⭐36)](https://github.com/bric3/nice-exit-code) - Maps exit status codes to human readable strings.
*   [nix-shell (⭐408)](https://github.com/chisui/zsh-nix-shell) - Plugin that lets you use ZSH as the default shell in a `nix-shell` environment.
*   [nlsh (⭐3)](https://github.com/PsychArch/nlsh) - Allows you to interact with your shell using natural language. Supports multiple LLM providers (OpenAI API compatible). Includes support for X.ai's Grok.
*   [nnvm (⭐4)](https://github.com/torifat/nnvm) - auto-switches node versions based on `.nvmrc`. Requires [n (⭐19k)](https://github.com/tj/n).
*   [no-ps2 (⭐22)](https://github.com/romkatv/zsh-no-ps2) - When this plugin is used, Enter inserts a newline if the typed command is incomplete. No PS2!
*   [nobility (⭐3)](https://github.com/Twilight4/nobility) - An organized colletion of shell modules designed to streamline your pentesting workflow by leveraging shell integrations such as autocompletion and prefilling, optimizing the productivity of your work and liberatating you from the hassle of juggling notes, endless copying and pasting, and tedious command editing.
*   [node-env-installer (⭐1)](https://github.com/shiro-saber/node-env-installer) - Uses `nvm` to install new versions and modules for the current project.
*   [node-path (⭐5)](https://github.com/andyrichardson/zsh-node-path) - Automatically adds the `npm` bin of your current directory to your `$PATH`.
*   [node (⭐5)](https://github.com/srijanshetty/node.plugin.zsh) - Srijan Shetty's Node.js plugin for ZSH with caching of `nvm` completions and autoloading of `nvm` if present.
*   [nodenv (c-uo) (⭐0)](https://github.com/C-uo/zsh-nodenv) - Looks for `nodenv` in your working directory and loads it when found.
*   [nodenv (jsahlen) (⭐4)](https://github.com/jsahlen/nodenv.plugin.zsh) - Auto-load `nodenv` and its completions into the shell.
*   [nodenv (mattberther) (⭐2)](https://github.com/mattberther/zsh-nodenv) - Installs, updates and loads `nodenv`. Inspired by [zsh-rbenv (⭐2)](https://github.com/Meroje/zsh-rbenv).
*   [nodo (⭐12)](https://github.com/nicolodiamante/nodo) - This plugin helps you prevent `node_modules` directories from filling your iCloud storage by un-syncing the directory or can save even more space by removing all `node_modules` directories within the chosen root directory. This is particularly useful for cleaning up a project that has multiple `node_modules` trees
*   [nohup (⭐8)](https://github.com/micrenda/zsh-nohup) - Add `nohup` to the current command pressing `Ctrl-H`.
*   [noreallyjustfuckingstopalready (⭐301)](https://github.com/eventi/noreallyjustfuckingstopalready) - macOS users know the pain of trying to figure out what command actually flushes the DNS cache on their version of macOS, and this plugin makes that annoyance go away.
*   [notenote (⭐4)](https://github.com/DrgnFireYellow/notenote/) - Makes it easy to take notes.
*   [notes (aperezdc) (⭐13)](https://github.com/aperezdc/zsh-notes) - Inspired by [terminal\_velocity](https://www.seanh.cc/terminal_velocity/), it provides a fast interface to create and access a set of [Markdown](https://en.wikipedia.org/wiki/Markdown) text files inside a directory.
*   [notes (chipsenkbeil) (⭐19)](https://github.com/chipsenkbeil/zsh-notes) - Provides a quick notes editing experience in ZSH.
*   [notify (luismayta) (⭐12)](https://github.com/luismayta/zsh-notify) - Notifications for ZSH with auto installation of dependencies and r2d2 sounds.
*   [notify (marzocchi) (⭐524)](https://github.com/marzocchi/zsh-notify) - A plugin for ZSH (on macOS and Linux) that posts desktop notifications when a command terminates with a non-zero exit status or when it took more than 30 seconds to complete, if the terminal application is in the background (or the command's terminal tab is inactive).
*   [npm (trystan2k) (⭐2)](https://github.com/trystan2k/zsh-npm-plugin) - Adds `npm` aliases. Based on the Oh-My-Zsh [npm (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) plugin.
*   [npm (zfben) (⭐1)](https://github.com/zfben/zsh-npm) - Use `n` as `npm` aliases with `noglob` prefix and more. Based on the Oh-My-Zsh [npm (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) plugin.
*   [npms (⭐9)](https://github.com/torifat/npms) - Utility powered by [fzf (⭐70k)](https://github.com/junegunn/fzf) for using npm scripts interactively. Requires [fzf (⭐70k)](https://github.com/junegunn/fzf) and [jq](https://stedolan.github.io/jq/).
*   [nvim-appname (⭐26)](https://github.com/mehalter/zsh-nvim-appname) - Maintain multiple Neovim configurations with `NVIM_APPNAME` with full tab completion of available flags, available neovim applications, and neovim arguments/flags. Requires neovim v0.9+
*   [nvim-switcher (⭐0)](https://github.com/dacarey/zsh-nvim-switcher)- Manages switching between `nvim` distributinons such as [Lazyvim](https://www.lazyvim.org/), [kickstart (⭐24k)](https://github.com/nvim-lua/kickstart.nvim) or a home made configuration.
*   [nvm-auto-use (jrr997) (⭐1)](https://github.com/jrr997/zsh-nvm-auto-use) - Automatically manages your Node.js versions with [nvm (⭐84k)](https://github.com/nvm-sh/nvm) based on your current directory.
*   [nvm-auto-use (martvdmoosdijk) (⭐0)](https://github.com/martvdmoosdijk/zsh-nvm-auto-use) - Automatically switches node version with `nvm use` when a `.nvmrc` is detected.
*   [nvm-auto-use (tomsquest) (⭐18)](https://github.com/tomsquest/nvm-auto-use.zsh) - Calls `nvm use` automatically whenever you enter a directory that contains an `.nvmrc` file with a string telling `nvm` which node to use.
*   [nvm-deferred (⭐0)](https://github.com/davidparsson/zsh-nvm-deferred) - Defers loading of the `nvm` oh-my-zsh plugin using [zsh-defer (⭐389)](https://github.com/romkatv/zsh-defer) to speed up shell startup.
*   [nvm-lazy (⭐5)](https://github.com/davidparsson/zsh-nvm-lazy) - Plugin for lazy loading of oh-my-zsh's \**nvm*- plugin. It supports lazy-loading `nvm` for more than one binary/entrypoint, with the defaults being `nvm`, `node` and `npm`.
*   [nvm-pnpm-auto-switch (⭐0)](https://github.com/spencerbeggs/zsh-nvm-pnpm-auto-switch) - Automatically switches Node.js versions (using `nvm`) and manages pnpm package manager versions (using `corepack`) when changing directories.
*   [nvm (⭐2.3k)](https://github.com/lukechilds/zsh-nvm) - ZSH plugin for installing, updating and loading `nvm`.
*   [oath (⭐8)](https://github.com/alexdesousa/oath) - Manages 2FA authentication 6 digit tokens. It was highly inspired by this article about [using oathtool for 2 step verification](https://www.cyberciti.biz/faq/use-oathtool-linux-command-line-for-2-step-verification-2fa/).
*   [oclif completion generator (⭐10)](https://github.com/MunifTanjim/oclif-plugin-completion) - Generates shell completions for commands lacking them.
*   [oh-my-gpt (⭐1)](https://github.com/vicotrbb/oh-my-gpt) - Provides an easy-to-use interface for interacting with OpenAI's GPT models directly from your terminal. It allows you to send queries, analyze files, and get AI-powered assistance for various tasks.
*   [oh-my-matrix (⭐24)](https://github.com/amstrad/oh-my-matrix) - Turn your terminal into the matrix.
*   [oh-my-posh-manager (⭐4)](https://github.com/wintermi/zsh-oh-my-posh) - Manages the oh-my-posh theme engine, along with providing a default powerline-like theme.
*   [oh-my-tmux-manager](https://github.com/unixorn/awesome-zsh-plugins/blob/main/README.md/omt-manager) - Lets you easily manage your tmux configurations.
*   [ollama (⭐33)](https://github.com/plutowang/zsh-ollama-command) - Integrates the OLLAMA AI model with [fzf (⭐70k)](https://github.com/junegunn/fzf) to provide intelligent command suggestions based on user input requirements.
*   [omz-full-autoupdate (⭐74)](https://github.com/Pilaton/OhMyZsh-full-autoupdate) - Automatically update [oh-my-zsh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh) plugins and themes.
*   [omz-git (⭐1)](https://github.com/aeons/omz-git) - [Oh-My-ZSH](https://ohmyz.sh/)'s [git (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git) plugin re-packaged to be standalone.
*   [omz-themes-standalone (⭐5)](https://github.com/zshzoo/omz-themes-standalone) - Gives you the [oh-my-zsh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh) themes without requiring everything else that comes with oh-my-zsh
*   [open-create-projects (⭐3)](https://github.com/marcossegovia/open-create-projects) - Open/Create projects in Jetbrains.
*   [open-pr (⭐65)](https://github.com/caarlos0/zsh-open-pr) - A ZSH plugin to open pull requests from command line.
*   [openshift-origin (⭐0)](https://github.com/ryanswart/openshift-origin-zsh-plugin) - Add a few shortcuts to common openshift origin (oc) actions.
*   [opera-git-plugin (⭐0)](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - `git` aliases.
*   [opera-gx (⭐0)](https://github.com/troykelly/oh-my-zsh-opera-gx) - Enables starting Opera GX with a specific user profile by using the `opgx` command followed by the profile's name. The plugin also implements autocompletion for profile names.
*   [opp (⭐233)](https://github.com/hchbaw/opp.zsh) - Vim's text-objects-ish for ZSH.
*   [opt-path (⭐13)](https://github.com/jreese/zsh-opt-path) - Automatically add `~/opt` subpaths to your `$PATH`.
*   [osx-autoproxy (⭐120)](https://github.com/SukkaW/zsh-osx-autoproxy) - Configures proxy environment variables based on macOS's system preferences.
*   [osx-dev (⭐14)](https://github.com/marshallmick007/osx-dev-zsh-plugin) - This plugin adds some commands for maintaining various server programs on a macOS install.
*   [osx (⭐20)](https://github.com/mwilliammyers/plugin-osx) - Add some common macOS related aliases and functions.
*   [paci (⭐2)](https://github.com/iloginow/zsh-paci) - Plugin for arch linux package managers.
*   [pack (⭐0)](https://github.com/fourdim/zsh-pack/) - Pack your source code with ZSH.
*   [package-any-node (⭐0)](https://github.com/zdharma-continuum/zsh-package-any-node) - Easy installing of any Node modules inside the plugin directory, exposing their binaries via shims (i.e.: forwarder scripts) created automatically by [Bin-Gem-Node (⭐7)](https://github.com/zdharma-continuum/z-a-bin-gem-node) annex.
*   [packer (⭐2)](https://github.com/BreakingPitt/zsh-packer) - Adds aliases and auto-completes for Hashicorp [packer](https://www.packer.io/).
*   [pantheon-terminal-notify (⭐11)](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin) - Background notifications for long running commands. Supports Elementary OS Freya.
*   [passwordless-history (⭐21)](https://github.com/jgogstad/passwordless-history) - Keeps passwords from entering your command line history.
*   [path-ethic (⭐9)](https://github.com/sha1n/path-ethic) - Helps manage your `$PATH` quickly and easily. Doesn't touch your existing `.zshrc`, `.zprofile`, but adds on top of your existing environment instead.
*   [pctl (⭐8)](https://github.com/ytet5uy4/pctl) - Toggle the environment variables for proxying.
*   [peco-history (⭐124)](https://github.com/jimeh/zsh-peco-history) - Search shell history with Peco when pressing `ctrl+R`.
*   [penmux (⭐2)](https://github.com/mfulz/zsh-penmux) - A session manager plugin meant to be used for penetration testing sessions and tracking the terminal sessions to be used in reports.
*   [pentest (⭐67)](https://github.com/jhwohlgemuth/oh-my-zsh-pentest-plugin) - Aliases and functions for the lazy penetration tester.
*   [per-directory-history (⭐324)](https://github.com/jimhester/per-directory-history) - Per directory history for ZSH, as well as global history, and the ability to toggle between them with `^G`.
*   [percol (⭐9)](https://github.com/robturtle/percol.plugin.zsh) - Interactively and incrementally search history/resume background jobs using [percol (⭐3.3k)](https://github.com/mooz/percol).
*   [perlbrew (⭐1)](https://github.com/tfiala/zsh-perlbrew/) - Installs [perlbrew](https://perlbrew.pl/) if not already installed and initializes it for your shell.
*   [pet (⭐0)](https://github.com/ppcamp/zsh-pet) - Adds support for [pet (⭐4.8k)](https://github.com/knqyf263/pet).
*   [pew (⭐2)](https://github.com/shosca/zsh-pew) - Sets up and manages Python virtualenvs using [pew (⭐1.2k)](https://github.com/berdario/pew) and automatically switches virtualenvs as you move directories.
*   [pg (⭐18)](https://github.com/caarlos0-graveyard/zsh-pg) - Adds utility functions to work with [PostgreSQL](https://www.postgresql.org/).
*   [pgconnect (⭐2)](https://github.com/ruslan-korneev/pgconnect-zsh) - Provides an easy way to manage and connect to PostgreSQL databases using `pgcli` and [fzf (⭐70k)](https://github.com/junegunn/fzf) for a seamless command-line experience.
*   [ph-marks (⭐11)](https://github.com/lainiwa/ph-marks) - Bookmark pornhub videos from your terminal.
*   [php-version-rcfile-switcher (⭐6)](https://github.com/xellos866/php-version_rcfile-switcher) - Automatically switch between php versions using [php-version (⭐678)](https://github.com/wilmoore/php-version) if an rc-file is present in a directory.
*   [php-version-switcher (⭐2)](https://github.com/Akollade/php-version-switcher.plugin.zsh) - Changes php versions if a `.php-version` file is found.
*   [phpcs (⭐2)](https://github.com/voronkovich/phpcs.plugin.zsh) - Plugin for [PHP code sniffer (⭐11k)](https://github.com/squizlabs/PHP_CodeSniffer).
*   [phpunit (⭐8)](https://github.com/voronkovich/phpunit.plugin.zsh) - Plugin for [PHPUnit](https://phpunit.de/).
*   [pins (⭐4)](https://github.com/mehalter/zsh-pins) - ZSH plugin for pinning directories. Like a CLI folder bookmark manager with tab completions.
*   [pip-app (⭐39)](https://github.com/sharat87/pip-app) - Makes it easy to install python applications into distinct Python virtualenvs so they don't conflict with any other python requirements on your system.
*   [pip-env (⭐4)](https://github.com/iboyperson/zsh-pipenv) - Automatic [pipenv](https://pipenv.readthedocs.io/en/latest/) activation upon entry into a `pipenv` project.
*   [pipe (⭐0)](https://github.com/pipe-felipe/zsh-pipe-plugin) - Includes `docker` and package-related scripts.
*   [pipenv (owenstranathan) (⭐18)](https://github.com/owenstranathan/pipenv.zsh) - Automatically activates a **pipenv** when entering a directory if there is Pipfile in that directory. Includes `pipenv` completions.
*   [pipenv (sudosubin) (⭐0)](https://github.com/sudosubin/zsh-pipenv) - Enables `pipenv`'s `$PATH` and adds completions.
*   [pipx (⭐7)](https://github.com/thuandt/zsh-pipx) - Autocompletions for [pipx (⭐12k)](https://github.com/pypa/pipx).
*   [pkenv (⭐1)](https://github.com/ptavares/zsh-pkenv) - Installs and loads [pkenv](https://github.com/iamhsa/pkenv.git).
*   [plenv (⭐1)](https://github.com/TwoPizza9621536/zsh-plenv) - Plugin for the perl [plenv (⭐522)](https://github.com/tokuhirom/plenv) version manager based on jenv.
*   [plugin-ibtool (⭐1)](https://github.com/rgalite/zsh-plugin-ibtool) - Adds ibtool shortcuts to generate localized XIB files.
*   [plugin-rails (⭐2)](https://github.com/paraqles/zsh-plugin-rails) - ZSH plugin for Rails.
*   [plugin-vscode (⭐17)](https://github.com/wuotr/zsh-plugin-vscode) - Plugin for Visual Studio Code, a text editor for macOS, Windows, and Linux.
*   [plugin (⭐12)](https://github.com/darrenbutcher/plugin) - Creates custom [oh-my-zsh](https://ohmyz.sh) plugins from a boilerplate template. Very oh-my-zsh centric, the generated plugins will need editing to work with other frameworks.
*   [pnpm (baliestri) (⭐9)](https://github.com/baliestri/pnpm.plugin.zsh) - Adds useful aliases for many common [pnpm](https://pnpm.io/) commands. Includes tab-completions.
*   [pnpm (leizhenpeng) (⭐5)](https://github.com/Leizhenpeng/zsh-plugin-pnpm) - Adds useful aliases for common [pnpm](https://pnpm.io/) commands.
*   [pnpm (mat2ja) (⭐3)](https://github.com/mat2ja/pnpm.plugin.zsh) - Better [pnpm](https://pnpm.io/) aliases.
*   [pnpm (ntnyq) (⭐78)](https://github.com/ntnyq/omz-plugin-pnpm) - Adds useful aliases for common [pnpm](https://pnpm.io/) commands.
*   [poetry (darvid) (⭐76)](https://github.com/darvid/zsh-poetry) - Automatically activates and deactivates [Poetry](https://poetry.eustace.io/)-created python virtualenvs.
*   [poetry (murku) (⭐0)](https://github.com/murku/omz_poetry_plugin) - Adds aliases for frequently used [Poetry](https://poetry.eustace.io/) commands
*   [poetry (sudosabin) (⭐5)](https://github.com/sudosubin/zsh-poetry) - Enables poetry `$PATH` and autocompletions.
*   [popman (⭐4)](https://github.com/jdsee/popman) - Ever found yourself in the middle of composing a long command and needing to check a man page? Popman lets you instantly pop open a man page for any command you're typing and jump right back to where you left off, making your command-line experience smoother and more efficient.
*   [portal (⭐4)](https://github.com/anasouardini/portal/) - A very basic script for jumping to/from paths without having to do write the whole path, open multiple terminal sessions or do a file system search using [fzf (⭐70k)](https://github.com/junegunn/fzf). Heavily inspired by [Z (⭐17k)](https://github.com/rupa/z).
*   [posh-git-bash (⭐382)](https://github.com/lyze/posh-git-sh) - Adds `git` status in your prompt.
*   [ppsmon (⭐0)](https://github.com/mzpqnxow/ppsmon) - Reads `/sys/class/net/$interface/` to keep track of packet transmission rates. It stores the current rate to a file in the RAM backed filesystem where it can be easily accessed for display in a shell-prompt. Linux-only due to use of `/sys`.
*   [pr-cwd (⭐2)](https://github.com/zpm-zsh/pr-cwd) - Creates a global variable with current working directory. Plugin has integration with [jocelynmallon/zshmarks (⭐279)](https://github.com/jocelynmallon/zshmarks).
*   [pr-eol (⭐0)](https://github.com/zpm-zsh/pr-eol) - Displays an EOL symbol which can be embedded in the prompt.
*   [pr-exec-time (⭐2)](https://github.com/zpm-zsh/pr-exec-time) - Adds a variable you can use to display the execution time of the last command run.
*   [pr-git (⭐2)](https://github.com/zpm-zsh/pr-git) - Creates a global variable with `git` status information that can be displayed in prompts.
*   [pr-is-root (⭐0)](https://github.com/zpm-zsh/pr-is-root) - Sets an environment variable you can use in a custom prompt when running as root.
*   [pr-jobs (⭐1)](https://github.com/zpm-zsh/pr-jobs) - Creates an environment variable which can be used to display background job information in a custom prompt.
*   [pr-node (⭐0)](https://github.com/zpm-zsh/pr-node) - Sets an environment variable which can be used to display Node.js information in a custom prompt.
*   [pr-return (⭐2)](https://github.com/zpm-zsh/pr-return) - Plugin for ZSH which displays the exit status of the last command run.
*   [pr-user (⭐1)](https://github.com/zpm-zsh/pr-user) - Creates a global variable that can be used in prompts.
*   [presenter-mode (⭐4)](https://github.com/idadzie/zsh-presenter-mode) - Expands aliases during presentations. It also increases the terminal window's contrast to enhance visibility.
*   [pretty-time (sindresorhus) (⭐71)](https://github.com/sindresorhus/pretty-time-zsh) - Convert seconds to a human readable string: 165392 → 1d 21h 56m 32s.
*   [pretty-time (zpm-zsh) (⭐2)](https://github.com/zpm-zsh/pretty-time) - Converts raw seconds into human-readable strings.
*   [prettyping (⭐4)](https://github.com/unixorn/prettyping) - Adds a wrapper around the standard ping tool with the objective of making the output prettier, more colorful, more compact, and easier to read.
*   [prezto-last-working-dir (⭐0)](https://github.com/JoniVanderheijden/prezto-last-working-dir) - Keeps track of the last used working directory and automatically jumps into it for new shells, unless the starting directory is not `$HOME`. Includes a `lwd` alias.
*   [print-alias (⭐15)](https://github.com/brymck/print-alias) - Prints commands with aliases expanded whenever you use an alias at the command line.
*   [printc (⭐14)](https://github.com/philFernandez/printc) - Allows you to print in any color in the RGB space via a simple `printc` call.
*   [printdocker (⭐0)](https://github.com/elvitin/printdocker-zsh-plugin) - Pretty print [docker](https://docker.com) objects.
*   [profile-secrets (⭐28)](https://github.com/gmatheu/shell-plugins) - Securely keep sensitive variables (api tokens, passwords, etc) as part of your terminal init files. Uses gpg to encrypt/decrypt the file with your secrets.
*   [project (gko) (⭐20)](https://github.com/gko/project) - Create node/python/ruby projects both locally and on GitHub (private or public repository).
*   [project (voronkovich) (⭐5)](https://github.com/voronkovich/project.plugin.zsh) - Plugin for managing projects.
*   [projen (⭐0)](https://github.com/p6m7g8/p6-zsh-projen-plugin) - Adds aliases for [projen (⭐2.8k)](https://github.com/projen/projen).
*   [prompt-dir-perms (⭐0)](https://github.com/xPMo/zsh-prompt-dir-perms) - Creates a segment displaying the permissions of the current directory you can use in your ZSH prompt.
*   [prompt-generator (⭐6)](https://github.com/the10thWiz/zsh-prompt-generator) - Generates custom themes. Some generated themes require powerline-compatible fonts.
*   [proxy-plugin (escalate) (⭐20)](https://github.com/escalate/oh-my-zsh-proxy-plugin) - Quickly enable and disable proxy shell environment settings.
*   [proxy-plugin (xooooooooox) (⭐1)](https://github.com/xooooooooox/zsh-proxy) - Helps manage proxy settings in your shell environment.
*   [proxy (⭐387)](https://github.com/SukkaW/zsh-proxy) - Configure proxy settings for some package managers and software.
*   [psgrep (⭐0)](https://github.com/voidzero/omz-plugin-psgrep/) - Makes `ps grep` hide its own process from the results of a `ps aux | grep`.
*   [purge-history-secrets (⭐4)](https://github.com/jotasixto/purge-history-secrets) - Uses [gitleaks (⭐20k)](https://github.com/gitleaks/gitleaks) to periodically scan your ZSH history for secrets and purge them if found. Requires [jq](https://jqlang.github.io/jq/).
*   [pwp (⭐5)](https://github.com/ttkalcevic/pwp) - Provides a convenient way to display the present working path in the terminal prompt and lists the current working directory along with its parent directories. Additionally, it includes a custom command .. to navigate to parent directories easily.
*   [pyenv (mattberther) (⭐47)](https://github.com/mattberther/zsh-pyenv) - Inspired by **zsh-rbenv**. Installs, updates or loads `pyenv`, and adds extra functionality.
*   [pyenv (twopizza9621536) (⭐0)](https://github.com/TwoPizza9621536/zsh-pyenv) - Based on the oh-my-zsh [pyenv (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/pyenv) plugin with modifications from the rbenv and jenv plugins.
*   [pyenv (xlshiz) (⭐2)](https://github.com/xlshiz/pyenv-zsh-plugin) - Loads [pyenv (⭐42k)](https://github.com/pyenv/pyenv) into the current shell and provides prompt info via the `pyenv_prompt_info` function. Also loads [pyenv-virtualenv (⭐6.6k)](https://github.com/pyenv/pyenv-virtualenv) if available.
*   [pyenv-lazy-load (⭐3)](https://github.com/erikced/zsh-pyenv-lazy-load) - Plugin for lazy-loading `pyenv` in ZSH.
*   [pyenv-lazy (⭐48)](https://github.com/davidparsson/zsh-pyenv-lazy) - Lazy load [pyenv (⭐42k)](https://github.com/pyenv/pyenv). The initial `eval "$(pyenv init -)"` is executed the first time `pyenv` is called.
*   [pyvenv-fast (⭐2)](https://github.com/ACmyles/pyvenv-fast) - Launch a Python `venv` with one command. Designed for use with [dotpyvenv (⭐6)](https://github.com/jeanpantoja/dotpyvenv).
*   [q (cal2195) (⭐69)](https://github.com/cal2195/q) - Add `vim`-like macro registers to your ZSH shell.
*   [q (tomsquest) (⭐0)](https://github.com/tomsquest/q.plugin.zsh) - Tail/remove the temp file for [Q (⭐1.5k)](https://github.com/y0ssar1an/q), the Dirty Debugging Tool.
*   [qiime2 (⭐2)](https://github.com/misialq/zsh-qiime2) - Adds functions and aliases to make working with [Quiime 2](https://qiime2.org/) easier.
*   [quiet-accept-zle (⭐14)](https://github.com/AdrieanKhisbe/zsh-quiet-accept-line) - Enables you to run typed zsh command without triggering new prompt, history entry, or having output being outputed.
*   [quoter (⭐8)](https://github.com/pxgamer/quoter-zsh) - Display a random quote when opening a new terminal session.
*   [quotify (⭐7)](https://github.com/dpretet/zsh-quotify) - Displays inspiring coding quotes from our pairs when starting up.
*   [qwy (⭐2)](https://github.com/Ryooooooga/qwy) - ZSH fuzzy completion plugin.
*   [randeme (⭐4)](https://github.com/ex-surreal/randeme) - Chooses a random theme for each session. If you not like the chosen theme you can run `randeme_rm` to never show that theme again.
*   [random-quotes (⭐8)](https://github.com/vkolagotla/zsh-random-quotes) - Displays random quotes or facts.
*   [ranger (niziL) (⭐0)](https://github.com/NiziL/ranger.plugin.zsh) - provide prompt element for [ranger (⭐16k)](https://github.com/ranger/ranger). Shows current `RANGER_LEVEL`, displaying nothing when the environment variable is unset, something when it is equals to 1, and something else when it is greater than 1.
*   [ranger (rc2dev) (⭐5)](https://github.com/rc2dev/ranger-zshz) - Integrates [zsh-z (⭐2.2k)](https://github.com/agkozak/zsh-z) into [ranger (⭐16k)](https://github.com/ranger/ranger).
*   [ranger-autojump (⭐71)](https://github.com/fdw/ranger-autojump) - Adds [autojump (⭐17k)](https://github.com/wting/autojump) support to the [ranger (⭐16k)](https://github.com/ranger/ranger) console file manager.
*   [raspberry-temp (⭐1)](https://github.com/cfunkz/zsh-raspberry-temp-plugin) - Measures temperature for raspberry pi via `rpi-temp` alias.
*   [raspberryPi4Temperature (⭐0)](https://github.com/KidesLeo/RaspberryPi4TemperaturePromptPlugin) - Puts the Raspberry Pi temperature into a spaceship prompt segment
*   [razer-status-code (⭐4)](https://github.com/michaelmcallister/razer-status-code) - Change the colour of your [Razer Mouse](https://openrazer.github.io/) based on the status of the last executed command. Requires [OpenRazer](https://openrazer.github.io) linux drivers.
*   [rbenv (elliottcable) (⭐4)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) - A faster fork of the `rbenv` plugin from [oh-my-zsh](https://ohmyz.sh/).
*   [rbenv (jsahlen) (⭐0)](https://github.com/jsahlen/rbenv.plugin.zsh) - Variant based on the original [oh-my-zsh](https://ohmyz.sh/) `rbenv` plugin.
*   [rbenv (meroje) (⭐2)](https://github.com/Meroje/zsh-rbenv) - Inspired by [https://github.com/lukechilds/zsh-nvm/ (⭐2.3k)](https://github.com/lukechilds/zsh-nvm/), makes it easier to work with ruby `rbenv` environments.
*   [rc-files (⭐2)](https://github.com/0b10/rc-files) - Adds shortcut functions for editing various rc files.
*   [recall (⭐18)](https://github.com/mango-tree/zsh-recall) - Makes using command history easier.
*   [redis (⭐5)](https://github.com/z-shell/redis) - Will run [redis-server](https://redis.io/) pointing it to the `redis.conf` configuration file. This can be used with the [zdharma/zredis (⭐5)](https://github.com/z-shell/zredis) plugin to share variables between shells.
*   [redo (⭐6)](https://github.com/joknarf/redo) - Adds an interactive history menu to replace `Ctrl-R` and `ESC+/`.
*   [reentry-hook (⭐6)](https://github.com/RobSis/zsh-reentry-hook) - Plugin that re-enters working directory if it has been removed and re-created.
*   [release-fetcher (⭐0)](https://github.com/Game4Move78/zsh-release-fetcher) - Fetches latest release and checks if you trust the identity used to sign the tag.
*   [reload (⭐7)](https://github.com/aubreypwd/zsh-plugin-reload) - Adds function to quickly reload your `.zshrc`.
*   [reminder (⭐38)](https://github.com/AlexisBRENON/oh-my-zsh-reminder) - A plugin which displays reminders above every prompt.
*   [replace-multiple-dots (⭐6)](https://github.com/momo-lab/zsh-replace-multiple-dots) - Converts `...` to `../..`
*   [require (⭐2)](https://github.com/aubreypwd/zsh-plugin-require) - Adds ability to `require commandname` and then (if [brew](https://brew.sh) is installed) automatically `brew install commandname` if it isn't already installed.
*   [revolver (⭐151)](https://github.com/molovo/revolver) - A progress spinner for ZSH scripts.
*   [riddle-me (⭐1)](https://github.com/vkolagotla/zsh-riddle-me) - Displays random riddles.
*   [ripz (⭐23)](https://github.com/jedahan/ripz) - Reminds you of your aliases, so you use them more. Depends on [ripgrep (⭐52k)](https://github.com/BurntSushi/ripgrep).
*   [robo (⭐2)](https://github.com/shengyou/robo-zsh-plugin) - A ZSH plugin for [Robo (⭐2.7k)](https://github.com/consolidation/robo/).
*   [rockz (⭐9)](https://github.com/aperezdc/rockz) - Lua + LuaRocks virtual environment manager based upon VirtualZ.
*   [ros2-env (⭐7)](https://github.com/Butakus/ros2-env) - Manage [ROS 2](https://github.com/ros2) environment and workspaces.
*   [rose-pine-man (⭐7)](https://github.com/const-void/rose-pine-man) - Colorizes `man` pages.
*   [run-scripts (⭐5)](https://github.com/Aireck2/zsh-run-scripts) - Runs scripts from `package.json`.
*   [rust (cowboyd) (⭐0)](https://github.com/cowboyd/zsh-rust) - Configure your [rust](https://www.rust-lang.org/) toolchain, installing [rustup](https://rustup.rs) if it is not currently installed already.
*   [rust (wintermi) (⭐8)](https://github.com/wintermi/zsh-rust) - Plugin for the [rust](https://www.rust-lang.org/) toolchain.
*   [rvm (⭐2)](https://github.com/johnhamelink/rvm-zsh) - Initiates [rvm (⭐5.2k)](https://github.com/rvm/rvm) and adds rubygem binaries (like compass) accessible in the user's `$PATH`.
*   [safe-kubectl (⭐5)](https://github.com/benjefferies/safe-kubectl) - Add some safety when running [kubectl](https://kubernetes.io/docs/reference/kubectl/) by warning what context you're in after a definable number of seconds since the last `kubectl` command.
*   [safe-paste (⭐12)](https://github.com/oz/safe-paste) - A safe-paste plugin. See Conrad Irwin's [bracketed-paste](https://cirw.in/blog/bracketed-paste) blog post.
*   [safe-rm (⭐22)](https://github.com/mattmc3/zsh-safe-rm) - Add safe-`rm` functionality so that `rm` will put files in your OS' trash instead of permanently deleting them.
*   [sail (⭐0)](https://github.com/Razzaghnoori/Sailor/) - Adds convenience aliases for [sail](https://laravel.com/docs/10.x/sail).
*   [saml2aws-auto (⭐5)](https://github.com/devndive/zsh-saml2aws-auto) - When using multiple AWS profiles, e.g. different accounts for your stages (development, pre-prod, prod), can be used to determine which profile is currently exported and if the token is still valid.
*   [saml2aws (⭐11)](https://github.com/onyxraven/zsh-saml2aws) - Add support for [saml2aws (⭐2.1k)](https://github.com/Versent/saml2aws).
*   [sandboxd (⭐238)](https://github.com/benvan/sandboxd) - Speed up your `.zshrc` & shell startup with lazy-loading by only running setup commands (e.g. `eval "$(rbenv init -)"`, etc) when you need them.
*   [saneopt (⭐21)](https://github.com/willghatch/zsh-saneopt) - Sane defaults for ZSH options, in the spirit of [vim-sensible (⭐5.2k)](https://github.com/tpope/vim-sensible).
*   [sb-upgrade (⭐0)](https://github.com/redxtech/zsh-sb-upgrade) - Script to automatically update apps on a seedbox.
*   [scad (⭐2)](https://github.com/MicahElliott/scad) - Shell Colorized Aliases for Docker/Podman (SCAD). Defines [docker](https://www.docker.com/) / [podman](https://podman.io) aliases and functions. These aliases adhere to the newer style of organizing and invoking `docker` with management commands rather than the notoriously confusing “random solo commands”. Requires [GRC (⭐2k)](https://github.com/garabik/grc) and [jq (⭐32k)](https://github.com/jqlang/jq).
*   [schroot (⭐1)](https://github.com/fshp/schroot.plugin.zsh) - Show current `chroot` name in your prompt.
*   [sdkman (⭐6)](https://github.com/ptavares/zsh-sdkman) - Installs [sdkman](https://github.com/sdkman) and adds completions and aliases for it.
*   [sealion (⭐10)](https://github.com/xyproto/sealion) - Allows you to set reminders that will appear in your terminal when your prompt is refreshed.
*   [search-directory-history (⭐3)](https://github.com/cmaahs/search-directory-history) - Allows complex search of per-directory history created using the [per-directory-history (⭐324)](https://github.com/jimhester/per-directory-history) plugin.
*   [sed-sub (⭐1)](https://github.com/MenkeTechnologies/zsh-sed-sub) - Adds keybindings to do global search and replace on current command line.
*   [select-history-skim (⭐0)](https://github.com/okhiroyuki/zsh-select-history-skim) Rummage through your history with [skim (⭐5.6k)](https://github.com/lotabout/skim).
*   [select-with-lf (⭐10)](https://github.com/chmouel/zsh-select-with-lf) - Lets user select files or a directory using [lf (⭐8.1k)](https://github.com/gokcehan/lf).
*   [select (⭐9)](https://github.com/z-shell/zsh-select) - Multi-term searched selection list with approximate matching and uniq mode.
*   [selector (⭐9)](https://github.com/joknarf/selector) - Make it easy to create selection menus.
*   [send (⭐31)](https://github.com/robertzk/send.zsh) - Single command to `git add`, `git commit`, and `git push` for much faster `git` workflow.
*   [sensei-git (⭐6)](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - Adds many `git` aliases and helper shell functions.
*   [senv (⭐0)](https://github.com/joepvd/senv) - Report presence of sensitive environment variables in the prompt
*   [session-sauce (⭐29)](https://github.com/ChrisPenner/session-sauce) - An [fzf (⭐70k)](https://github.com/junegunn/fzf) interface for tmux session creation and management for all your projects.
*   [setenv (⭐7)](https://github.com/kalpakrg/setenv) - Runs a script when you change directories.
*   [setpath (⭐0)](https://github.com/mys721tx/set_path) - Adds some local paths to your `fpath` and `$PATH`.
*   [shelf (⭐1)](https://github.com/ecmma/shelf) - Utility which can be used to bookmark and access directly any file using mnemonics.
*   [shell-fns (⭐3)](https://github.com/Hdoc1509/shell-fns) - Includes `git`, `neovim`, `npm`, `pip` extended functionality.
*   [shellcolor (⭐4)](https://github.com/SaltedBlowfish/zsh-shellcolor) - Changes the terminal background color based on the presence of a `.shellcolor` in the current directory.
*   [shellfirm (⭐862)](https://github.com/kaplanelad/shellfirm) - Shellfirm is a handy utility to help avoid running dangerous commands without an extra step of approval. When risky patterns is detected you will immediately get a small prompt challenge that will verify your action.
*   [shellsense (⭐4)](https://github.com/venopyX/shellsense) - AI-powered ZSH plugin designed to enhance your terminal experience with powerful features and AI-powered capabilities. Developed using Python, ShellSense offers a streamlined workflow for various tasks, making your terminal more efficient and user-friendly.
*   [shift-select (⭐143)](https://github.com/jirutka/zsh-shift-select) - Emacs shift-select mode for ZSH - select text in the command line using Shift, as in many text editors, browsers and other GUI programs.
*   [shortcuts (⭐6)](https://github.com/fairy-root/Zsh-Shortcuts-Plugin) - Enhance your terminal productivity with the Shortcuts plugin for [oh-my-zsh](https://ohmyz.sh/). Easily manage command shortcuts with robust features.
*   [show-git-user (⭐5)](https://github.com/luisprgr/zsh-show-git-user) - When you need to work with multiple `git` users on the same machine this plugin will show which `git` user name is active in your prompt.
*   [show-path (⭐3)](https://github.com/redxtech/zsh-show-path) - Provides a function shows the `$PATH` line by line.
*   [simpleserver (⭐14)](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) - Plugin to easily start python `SimpleHTTPServer` and `SimpleHTTPSServer`.
*   [singularityenv (⭐0)](https://github.com/saravanabalagi/zsh-plugin-singularityenv) - Provides a `singularityenv_prompt_info` function which returns the current singularity environment name
*   [skaffold (⭐1)](https://github.com/todie/skaffold.plugin.zsh) - ZSH integration and completions for [skaffold](https://skaffold.dev) local kubernetes development environment.
*   [skim (casonadams) (⭐2)](https://github.com/casonadams/skim.zsh) - Tries to determine where [skim (⭐5.6k)](https://github.com/lotabout/skim) is installed, then enables its fuzzy auto-completion and key bindings.
*   [skim (hackerchai) (⭐3)](https://github.com/hackerchai/skim-zsh) - Adds support for [skim (⭐5.6k)](https://github.com/lotabout/skim)
*   [slugify (⭐4)](https://github.com/lashoun/slugify) - Converts filenames and directories to a web friendly format.
*   [smart-cd (⭐17)](https://github.com/dbkaplun/smart-cd) - Runs `ls` and `git status` after chpwd.
*   [smart-files (⭐4)](https://github.com/vxfemboy/zsh-smart-files) - Enhances CLI by providing visual feedback for file paths and automatically creating directories when needed. It highlights paths in different colors based on their status (existing, new, or permission-denied) and handles directory creation automatically.
*   [smart-insert (⭐0)](https://github.com/lgdevlop/zsh-smart-insert) - provides interactive widgets to search for files and content using [`fd`](https://github.com/sharkdp/fd), [`rg`](https://github.com/BurntSushi/ripgrep), and [`fzf`](https://github.com/junegunn/fzf). It inserts the result directly into your shell with optional command prefixes.
*   [smartcache (⭐38)](https://github.com/QuarticCat/zsh-smartcache) - Caches command output to speed up shell startup time.
*   [smartinput (⭐7)](https://github.com/momo-lab/zsh-smartinput) - When you type brackets or quotes, the corresponding end brackets/quotes are automatically added.
*   [smile (⭐3)](https://github.com/fundor333/smile) - Adds function to display random smileys.
*   [snippets (⭐37)](https://github.com/willghatch/zsh-snippets) - Command line snippet expansion.
*   [snr (⭐1)](https://github.com/raisedadead/zsh-snr) - Passes the selected output of the first command to the next.
*   [solarized-man (⭐27)](https://github.com/zlsun/solarized-man) - A modified version of oh-my-zsh's plugin colored-man-pages, optimized for the [solarized dark (⭐16k)](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) theme in the terminal.
*   [some-peco (⭐1)](https://github.com/MoeBensu/zsh-some-peco/) - Enhances your command-line experience with [peco (⭐7.7k)](https://github.com/peco/peco) i.e. providing quick directory navigation and history search.
*   [spaceship-ocm (⭐2)](https://github.com/iamkirkbater/spaceship-ocm-plugin) - Queries your OpenShift Cluster Manager (ocm) configuration to show which environment you're connected to. Requires [NerdFont](https://www.nerdfonts.com/font-downloads) in your terminal.
*   [spack (⭐2)](https://github.com/Game4Move78/zsh-spack) - Includes some useful aliases and functions for loading/unloading [Spack (⭐4.6k)](https://github.com/spack/spack)-generated modules. As it makes use of the `module` command it is much more efficient than `spack load`.
*   [ssh-agent (⭐2)](https://github.com/sdiebolt/zsh-ssh-agent) - Automatically launches `ssh-agent` if it isn't already running.
*   [ssh-connect (⭐113)](https://github.com/gko/ssh-connect) - A simple `ssh` manager.
*   [ssh-plugin (⭐5)](https://github.com/paraqles/zsh-plugin-ssh) - Plugin for `ssh`.
*   [ssh-quickconnect (⭐1)](https://github.com/breda/zsh-ssh-quickconnect) - Simple utility to quickly connect to hosts from your `ssh` config & `known_hosts` file.
*   [sshpky (⭐0)](https://github.com/jeffzhangc/sshpky_zsh_plugin) - Auto updates git-repositories in the `$ZSH_CUSTOM` folder.
*   [sshukh (⭐7)](https://github.com/anatolykopyl/sshukh-zsh-plugin) - Will update your `known_hosts` file when you `ssh` into a server.
*   [startify (⭐3)](https://github.com/NorthIsMirror/zsh-startify) - Shows recently used `vim` files, shell-util files, active `tmux` sessions, recently-run `git` commands and more.
*   [startup-timer (⭐22)](https://github.com/paulmelnikow/zsh-startup-timer) - Print the time it takes for the shell to start up.
*   [stashy (⭐5)](https://github.com/MisterRios/stashy) - Plugin that simplifies using `git stash`.
*   [statify (⭐4)](https://github.com/vladmrnv/statify) - Plugin that does basic statistical analysis.
*   [sublime (⭐4)](https://github.com/valentinocossar/sublime) - Same as the official [Sublime](https://www.sublimetext.com/) plugin for [Oh My Zsh](https://ohmyz.sh/), but this opens files in the current Sublime window, if there is one already open.
*   [sudo (hcgraf) (⭐31)](https://github.com/hcgraf/zsh-sudo) - The `sudo` plugin from [oh-my-zsh](https://ohmyz.sh/), extracted to a standalone. Toggles `sudo` before the current/previous command by pressing \*ESC-ESC- in emacs-mode or vi-command mode.
*   [sudo (none9632) (⭐10)](https://github.com/none9632/zsh-sudo/) - Adds `sudo` as a prefix to the current command by typing `ESC`-`ESC`.
*   [suffix-alias (⭐4)](https://github.com/srijanshetty/zsh-suffix-alias) - Directly open files in the shell using ZSH's suffix aliases.
*   [sussysh (⭐0)](https://github.com/sussynuggetz/sussysh-zsh) - Based on xiong-chiamiov.
*   [svn-n-zsh (⭐5)](https://github.com/khrt/svn-n-zsh-plugin) - Rewrite of the stock [oh-my-zsh](https://ohmyz.sh/) [svn](https://subversion.apache.org/) plugin.
*   [switch-git (⭐1)](https://github.com/robin-mbg/switch-git) - Easy switching between `git` repositories. Just type `sgr <some part of you repo's name>`, press enter and you're there.
*   [symfony (voronkovich) (⭐5)](https://github.com/voronkovich/symfony.plugin.zsh) - ZSH plugin for [Symfony](https://symfony.com/).
*   [syntax-highlighting-filetypes (⭐155)](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - ZSH syntax highlighting with dircolors in realtime.
*   [syntax-highlighting (⭐21k)](https://github.com/zsh-users/zsh-syntax-highlighting) - Add syntax highlighting to your ZSH. Make sure you load this *before* [zsh-users/zsh-history-substring-search (⭐2.8k)](https://github.com/zsh-users/zsh-history-substring-search) or they will both break.
*   [sys-diver (⭐9)](https://github.com/ToruIwashita/sys-diver-zsh) - A ZSH plugin for directory change or editor startup with only key operations using widgets without typing commands.
*   [sysadmin-util (⭐975)](https://github.com/skx/sysadmin-util) - Steve Kemp's collection of tool scripts for sysadmins.
*   [system-clipboard (⭐159)](https://github.com/kutsan/zsh-system-clipboard) - Adds key bindings support for ZLE (Zsh Line Editor) clipboard operations for `vi` emulation keymaps. It works under Linux, macOS and Android (via Termux).
*   [systemd (⭐9)](https://github.com/le0me55i/zsh-systemd) - Adds many aliases for `systemd`.
*   [t32 (⭐2)](https://github.com/chrissicool/zsh-t32) - Plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset.
*   [tab-title (p1r473) (⭐1)](https://github.com/p1r473/tab-title/) - Rename [tmux (⭐37k)](https://github.com/tmux/tmux/wiki) and [screen](https://www.gnu.org/software/screen/manual/screen.html) panes and windows.
*   [tab-title (trystan2k) (⭐49)](https://github.com/trystan2k/zsh-tab-title) - Set the terminal tab title according to current directory or running process. Forked from [termsupport.zsh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/termsupport.zsh).
*   [tailf (⭐2)](https://github.com/rummik/zsh-tailf) - Adds `tailf` function with prefixed newlines instead of trailing newlines.
*   [take (⭐3)](https://github.com/amyreese/zsh-take) - Replicates `take` from [oh-my-zsh](https://ohmyz.sh/).
*   [tasko (⭐1)](https://github.com/knid/tasko) - Allows you to annotate [TaskWarrior (⭐4.8k)](https://github.com/GothenburgBitFactory/taskwarrior) tasks.
*   [telepresence (⭐0)](https://github.com/alexgervais/telepresence-ps1) - Add the current [Telepresence](https://www.telepresence.io/) connection status and context to your ZSH prompt.
*   [tempit (⭐0)](https://github.com/idirxv/tempit) - Helps you create, manage, and navigate temporary directories with ease. It provides a persistent tracking system so your temporary directories won't get lost.
*   [terminal-aliases (⭐10)](https://github.com/dvir-levy/terminal-aliases) - Adds convenience aliases for `terraform`, `git` and more.
*   [terminal-app (⭐12)](https://github.com/the8/terminal-app.zsh) - A plugin for integrating with the new macOS El Capitan Terminal.app features.
*   [terminal-title (⭐4)](https://github.com/AnimiVulpis/zsh-terminal-title) - Adds a `set-term-title` function you can use to title terminal windows.
*   [terminal-workload-report (⭐2)](https://github.com/LockonS/terminal-workload-report) - A plugin that calculates and displays how many commands have been run via terminal.
*   [termux (⭐4)](https://github.com/zpm-zsh/termux) - Adds compatibility for [Termux](https://termux.com/).
*   [terraform (hanjunlee) (⭐0)](https://github.com/hanjunlee/terraform-oh-my-zsh-plugin) - Add [terraform](https://www.terraform.io/) workspace to prompt.
*   [terraform (jsporna) (⭐4)](https://github.com/jsporna/terraform-zsh-plugin) - Extends the original [oh-my-zsh](https://ohmyz.sh/) plugin with aliases and tab completions. Adds workspace (when not default) to prompt.
*   [terraform (macunha1) (⭐19)](https://github.com/macunha1/zsh-terraform) - Add convenience aliases for [terraform](https://terraform.io/), tab completions and helper function to add your terraform workspace in the prompt.
*   [terraform (ptavares) (⭐2)](https://github.com/ptavares/zsh-terraform) - Adds aliases, functions and tab completions. Also installs [terraform-docs (⭐4.4k)](https://github.com/terraform-docs/terraform-docs), [tfsec (⭐6.8k)](https://github.com/aquasecurity/tfsec) and [tflint (⭐5.2k)](https://github.com/terraform-linters/tflint).
*   [terraform (thuandt) (⭐2)](https://github.com/thuandt/zsh-terraform) - Adds convenience aliases for [terraform](https://terraform.io/), along with completions for `terraform` and `terragrunt`.
*   [terragrunt (⭐5)](https://github.com/hanjunlee/terragrunt-oh-my-zsh-plugin) - Plugin for [Terragrunt (⭐8.6k)](https://github.com/gruntwork-io/terragrunt), a thin wrapper for [Terraform](https://terraform.io/) that provides extra tools.
*   [tfenv (⭐2)](https://github.com/CDA0/zsh-tfenv) - Installs, updates, and loads `tfenv` inspired by [zsh-pyenv (⭐47)](https://github.com/mattberther/zsh-pyenv)
*   [tfswitch (⭐1)](https://github.com/ptavares/zsh-tfswitch) - Installs and loads [tfswitch (⭐1.4k)](https://github.com/warrensbox/terraform-switcher).
*   [tgenv (⭐0)](https://github.com/ptavares/zsh-tgenv) - Installs and loads [tgenv](https://github.com/cunymatthieu/tgenv.git). Includes a function to manually update `tgenv`.
*   [tgswitch (⭐0)](https://github.com/ptavares/zsh-tgswitch) - Installs and loads [tgswitch (⭐152)](https://github.com/warrensbox/tgswitch).
*   [thefuck (⭐27)](https://github.com/laggardkernel/thefuck) - Loads [thefuck (⭐92k)](https://github.com/nvbn/thefuck) (a tool which corrects your previous command) with cache support, which reduces the loading time dramatically.
*   [theia-dev-tools (⭐0)](https://github.com/taPublic/zsh-theia-dev-tools) - Convenience functions for working with [theia-ide (⭐21k)](https://github.com/theia-ide/theia).
*   [tig (⭐1)](https://github.com/MenkeTechnologies/zsh-tig-plugin) - Adds a few advanced bindings for [tig (⭐13k)](https://github.com/jonas/tig) and also provides a `tig-pick` script.
*   [timewarrior (⭐54)](https://github.com/svenXY/timewarrior) - Adds support for [timewarrior](https://timewarrior.net/), a time-tracking application.
*   [tinted-shell (⭐68)](https://github.com/tinted-theming/tinted-shell) - Adds a script to allow you to change your shell's default ANSI colors but most importantly, colors 17 to 21 of your shell's 256 colorspace (if supported by your terminal). This script makes it possible to honor the original bright colors of your shell (e.g. bright green is still green and so on) while providing additional base16 colors to applications such as [Vim](https://www.vim.org).
*   [tipz (⭐27)](https://github.com/molovo/tipz) - Displays your alias if you have an alias for the command you just ran, similarly to [alias-tips (⭐794)](https://github.com/djui/alias-tips).
*   [title (⭐6)](https://github.com/zpm-zsh/title) - Allows you to set a terminal window title.
*   [titles (⭐57)](https://github.com/jreese/zsh-titles) - Automatic window and tab titles for [tmux](https://tmux.github.io) and xterm-compatible terminals.
*   [tm (⭐5)](https://github.com/kjhaber/tm.zsh) - Simplifies creating new [tmux](https://tmux.github.io) sessions, attaching to existing sessions, switching between sessions, and listing active sessions.
*   [tmux-auto-title (⭐22)](https://github.com/mbenford/zsh-tmux-auto-title) - Automatically sets the title of windows/panes as the current foreground command.
*   [tmux-rename (⭐4)](https://github.com/sei40kr/zsh-tmux-rename) - Rename [tmux](https://tmux.github.io) windows automatically.
*   [tmux-sessionizer (⭐1)](https://github.com/nikevsoft/tmux-sessionizer) - [tmux](https://tmux.github.io) sessionizer as seen on ThePrimeagen.
*   [tmux-simple (⭐6)](https://github.com/TBSliver/zsh-plugin-tmux-simple) - Simple plugin for using [tmux](https://tmux.github.io) with ZSH.
*   [tmux-ssh-syncing (⭐1)](https://github.com/alberti42/tmux-ssh-syncing) - Synchronize your `tmux` window names with active `ssh` sessions. This plugin dynamically updates the `tmux` window name to reflect the remote hosts of active `ssh` sessions in the same window. It also restores the original window name when all `ssh` sessions are closed.
*   [tmux-vim-integration (⭐4)](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) - Open files in a running `vim` (or NeoVim) session, from an adjacent [tmux](https://tmux.github.io) pane.
*   [tmux-zsh-vim-titles (⭐28)](https://github.com/MikeDacre/tmux-zsh-vim-titles) - Create unified terminal titles for `tmux`, ZSH, and Vim/NVIM, modular.
*   [tmux (⭐18)](https://github.com/zpm-zsh/tmux) - Plugin for [tmux](https://tmux.github.io).
*   [tmuxrepl (⭐25)](https://github.com/csurfer/tmuxrepl) - Simple ZSH plugin to have a R-EP-L [tmux](https://tmux.github.io) session.
*   [todotxt (⭐0)](https://github.com/Neluji/omz-todotxt) - Adds aliases for [todo.sh (⭐23)](https://github.com/benignoc/alfred-todotxt/).
*   [toggl (⭐5)](https://github.com/natterstefan/toggl-zsh-plugin) - Adds a `toggl-week` command to display the total working hours tracked on [toggl.com](https://toggl.com)
*   [toggle-command-prefix (⭐21)](https://github.com/xPMo/zsh-toggle-command-prefix) - Add a widget to toggle a prefix to a command. Binds Alt+s to prefix a command with `sudo` by default.
*   [toolbox (⭐0)](https://github.com/paxcoder/zsh-toolbox) - Automagically updates [homebrew](https://brew.sh) plugins. Allows enabling/disabling notice during startup and alias setup.
*   [touchplus (⭐3)](https://github.com/raisedadead/zsh-touchplus) - Create files with `touch` including the path.
*   [traista (⭐1)](https://github.com/exaluc/traista) - Includes `git` status decorations and color-coded exit status of the last command run. Better with dark terminal themes.
*   [travis (⭐4)](https://github.com/denolfe/zsh-travis) - Opens the [Travis CI](https://www.travis-ci.com/) page for the current repo if one exists.
*   [tre (⭐0)](https://github.com/redxtech/zsh-tre) - Makes using [tre (⭐996)](https://github.com/dduan/tre#editor-aliasing) easier.
*   [tsm (⭐17)](https://github.com/RobertAudi/tsm) - Adds a [tmux](https://tmux.github.io) Session Manager.
*   [tumult (⭐191)](https://github.com/unixorn/tumult.plugin.zsh) - Adds tools for macOS.
*   [ubuntualiases (⭐2)](https://github.com/GuilleDF/zsh-ubuntualiases) - Ubuntu 16 aliases.
*   [ugit (⭐1.5k)](https://github.com/Bhupesh-V/ugit) - Lets you undo your last `git` operation.
*   [uncloudium (⭐1)](https://github.com/Talon1024/omz-uncloudium) - Adds helper script to download crx files from the Google Chrome web store.
*   [undollar (⭐18)](https://github.com/zpm-zsh/undollar) - Strips the dollar sign from the beginning of the terminal prompt.
*   [unique-id (⭐6)](https://github.com/z-shell/zsh-unique-id) - Provides a unique number that identifies a running Zshell session, in its shell variable `$ZUID_ID`. Besides this unique number, also a unique codename is provided, in shell variable `$ZUID_CODENAME`. An example use case is to hold logs in files `.../mylog-${ZUID_CODENAME}.log`, so that two different Zshells will not write to the same file at the same time.
*   [unix-simple (⭐1)](https://github.com/redxtech/zsh-unix-simple) - A command that shows a graphic about the simplicity of unix.
*   [unraid (⭐2)](https://github.com/donbuehl/zsh-unraid) - Adds convenient aliases and functions for managing your Unraid server directly from the command line.
*   [unwrap (⭐7)](https://github.com/foxleigh81/unwrap-zsh-plugin) - Allows you to remove a directory without removing the contents - it puts them in the directory's parent directory.
*   [up (cjayross) (⭐4)](https://github.com/cjayross/up) - A simple way to navigate up through directories.
*   [up (peterhurford) (⭐42)](https://github.com/peterhurford/up.zsh) - Adds an up command to `cd` multiple levels up.
*   [up-dir (⭐0)](https://github.com/sgpthomas/zsh-up-dir) - Binds `ctrl-h` to navigating up a directory. This makes it very easy to go up a few directories without having to type any commands.
*   [update-zsh (⭐6)](https://github.com/AndrewHaluza/zsh-update-plugin) - Updates custom [oh-my-zsh](https://ohmyz.sh/) plugins. Only works with the oh-my-zsh framework.
*   [url-highlighter (⭐30)](https://github.com/ascii-soup/zsh-url-highlighter) - A plugin for the ZSH syntax highlighter that turns URLs green if they respond with a "good" status, and red otherwise. Useful for checking URL typos.
*   [uv-env (⭐4)](https://github.com/matthiasha/zsh-uv-env) - Automatically uses [uv (⭐52k)](https://github.com/astral-sh/uv) to activate a virtual environment based on the current directory.
*   [uvenv (⭐2)](https://github.com/vincentto13/uvenv.plugin.zsh) - Extends the functionality of the original [oh-my-zsh](https://ohmyz.sh/) `venv` module.
*   [vagrant-box-wrapper (⭐2)](https://github.com/evanthegrayt/vagrant-box-wrapper) - A wrapper plugin for [vagrant](https://www.vagrantup.com/) that allows for calling `vagrant` commands from outside of the box directory. The plugin also ships with a few extra commands that help to manage more than one box, along with custom tab-completion.
*   [valet (⭐9)](https://github.com/NasirNobin/zsh-valet/) - Reads `.valetphprc` from the project root and will switch to that PHP version automatically.
*   [vanilli.sh (⭐24)](https://github.com/yous/vanilli.sh) - A lightweight start point of shell configuration.
*   [vapor (⭐0)](https://github.com/notf0und/zsh-vapor) - Laravel [vapor (⭐310)](https://github.com/laravel/vapor-cli) plugin for ZSH to help you to run `vapor` from anywhere in the project tree, with auto-completion!
*   [vcshr (⭐0)](https://github.com/aubreypwd/zsh-plugin-vcshr) - Help vcsh users require GitHub repositories using `vcsh` for auto-installation in `~/.zshrc`, etc.
*   [velocity (⭐4)](https://github.com/rahulsalvi/velocity-python) - Powerline-based theme elements for ZSH and [tmux](https://tmux.github.io).
*   [venv-lite (⭐5)](https://github.com/gimbo/venv-lite.zsh) - A super-lightweight sort-of-clone of [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/); it pretty much expects you to be using [pyenv (⭐42k)](https://github.com/pyenv/pyenv) (though you don't \*have- to), and because it's based on the [`venv` module](https://docs.python.org/3/library/venv.html), (creation) only works for python >= 3.3.
*   [venv-wrapper (⭐2)](https://github.com/glostis/venv-wrapper) - Provides ZSH functions to ease the management of your virtual environments using `venv`.
*   [venv (⭐0)](https://github.com/lucasheartcliff/venv) - Run 'source venv/bin/activate' automatically every time there's a path `venv/bin/activate` file in the directory.
*   [venvs (⭐1)](https://github.com/pawnhearts/venvs) - Automatically switches Python virtualenvs. Supports both venvs in project folder(`~/myproject/venv`) and in global folder(like `~/.virtualenvs`)
*   [vi-increment (⭐9)](https://github.com/zsh-vi-more/vi-increment) - Add `vim`-like increment/decrement operations.
*   [vi-mode (jeffreytse) (⭐3.7k)](https://github.com/jeffreytse/zsh-vi-mode) - 💻 A better and friendly `vi`(`vim`) mode plugin for ZSH.
*   [vi-mode (nyquase) (⭐32)](https://github.com/Nyquase/vi-mode) - Add extra `vi`-like functionality.
*   [vi-mode (sinetoami) (⭐0)](https://github.com/sinetoami/vi-mode) - Add more `vi`-like functionality to ZSH.
*   [vi-motions (⭐39)](https://github.com/zsh-vi-more/vi-motions) - Add new motions and text objects including quoted/bracketed text and commands.
*   [vi-quote (⭐7)](https://github.com/zsh-vi-more/vi-quote) - Add an operation which quotes or unquotes a motion.
*   [viexchange (⭐16)](https://github.com/okapia/zsh-viexchange) - A `vi` mode plugin for easily swapping text between two places in the buffer, like vim-exchange.
*   [vim-mode (⭐356)](https://github.com/softmoth/zsh-vim-mode) - Friendly `vi`-mode bindings, adding basic Emacs keys, incremental search, mode indicators and more.
*   [vim-plugin (⭐20)](https://github.com/nviennot/zsh-vim-plugin) - Allows you to do `vim filename:123` to open a file with the cursor at a specific line.
*   [vimman (⭐20)](https://github.com/yonchu/vimman) - View `vim` plugin manuals (help) like `man` in ZSH.
*   [vimto (⭐29)](https://github.com/laurenkt/zsh-vimto) - Improved ZSH `vi` mode (bindkey -v) plugin.
*   [virtualenv-mod (⭐1)](https://github.com/mattcl/virtualenv-mod) - A modified virtualenv ZSH plugin for [oh-my-zsh](https://ohmyz.sh).
*   [virtualenv-prompt (⭐35)](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt) - A fork of the virtualenv plugin from upstream [oh-my-zsh](https://ohmyz.sh/). Adds support for customizing the virtualenv prompt in [oh-my-zsh](https://ohmyz.sh) themes.
*   [virtualz (⭐9)](https://github.com/aperezdc/virtualz) - Python [virtualenv](https://virtualenv.pypa.io/en/latest/) manager inspired by Adam Brenecki's [Virtualfish (⭐1.1k)](https://github.com/adambrenecki/virtualfish) for the [Fish shell](http://fishshell.com/), replaces virtualenvwrapper.
*   [virtuozzo-plugin (⭐1)](https://github.com/TamCore/virtuozzo-zsh-plugin) - An [oh-my-zsh](https://ohmyz.sh/) plugin for the [virtuozzo](https://docs.virtuozzo.com/master/index.html) bare-metal virtualization system.
*   [visit (⭐2)](https://github.com/justinpchang/visit) - Custom plugin for faster navigation.
*   [vivi (⭐0)](https://github.com/rufevean/vivi) - Integrates Google's [Gemini](https://gemini.google.com) language model (LLM) capabilities directly into your terminal. It allows you to send queries to the language model and receive AI-generated solutions, all within your terminal. The plugin supports session context and can dynamically execute received commands.
*   [vivid (⭐10)](https://github.com/ryanccn/vivid-zsh) - Make it easier to use `LSCOLORS` with [vivid (⭐1.9k)](https://github.com/sharkdp/vivid).
*   [volta (cowboyd) (⭐9)](https://github.com/cowboyd/zsh-volta) - Seamlessly install and configure the [Volta](https://volta.sh) Node.js toolchain manager.
*   [volta (⭐3)](https://github.com/ri7nz/zsh-volta) - Installs and loads [Volta: JS Toolchains as Code (⭐12k)](https://github.com/volta-cli/volta).
*   [vox (⭐8)](https://github.com/andrewbonnington/vox.plugin.zsh) - An [oh-my-zsh](https://ohmyz.sh/) plugin to control [VOX](https://vox.rocks/), a lightweight full-featured audio player for macOS that can play a variety of formats including FLAC and Ogg Vorbis.
*   [vsc (⭐2)](https://github.com/davidtong/vsc.plugin.zsh) - Plugin for [Visual Studio Code](https://code.visualstudio.com/) on macOS.
*   [vscode (kasperhesthaven) (⭐1)](https://github.com/kasperhesthaven/vscode) - Simple plugin to open [Visual Studio Code](https://code.visualstudio.com/) a little more easily across systems.
*   [vscode (qianxinfeng) (⭐33)](https://github.com/qianxinfeng/zsh-vscode) - Plugin for [Visual Studio Code](https://code.visualstudio.com/).
*   [vterm (⭐0)](https://github.com/randomphrase/vterm-zsh-plugin) - Lets you run `emacs` commands directly from [vterm (⭐92)](https://github.com/vterm/vterm) shell sessions.
*   [vtex (⭐0)](https://github.com/xdigu/zsh-vtex) - Adds helper aliases for [vtex](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-vtex-io-cli-command-reference#default-commands) cli commands.
*   [wakatime (sobolevn) (⭐91)](https://github.com/sobolevn/wakatime-zsh-plugin) - Track how much [time](https://wakatime.com/) you have spent in your terminal. Has per project stats.
*   [wakatime (wbingli) (⭐154)](https://github.com/wbingli/zsh-wakatime) - Automatic time tracking for commands in ZSH using [wakatime](https://wakatime.com/).
*   [warhol (⭐63)](https://github.com/unixorn/warhol.plugin.zsh) - Configures colorization with [grc (⭐2k)](https://github.com/garabik/grc).
*   [watch (⭐17)](https://github.com/enrico9034/zsh-watch-plugin) - Easily prefix your current or previous commands with watch by pressing `CTRL + W`.
*   [watson.zsh (⭐5)](https://github.com/bcho/Watson.zsh) - A plugin for the [watson (⭐2.5k)](https://github.com/TailorDev/Watson) time management system.
*   [wd (⭐712)](https://github.com/mfaerevaag/wd) - Warp directory lets you jump to custom directories in ZSH, without using `cd`. Why? Because `cd` seems inefficient when the folder is frequently visited or has a long path.
*   [web-search (anant-mishra1729) (⭐4)](https://github.com/Anant-mishra1729/web-search/) - Adds aliases for searching with Google, Bing, Wiki, YouTube, Yahoo, Duck Duck Go, GitHub, Stack Overflow and other services straight from the command line.
*   [web-search (sinetoami) (⭐3)](https://github.com/sinetoami/web-search) - Add commands to run bing, google, yahoo, & duckduckgo searches directly from the CLI.
*   [web-search (yabanahano) (⭐0)](https://github.com/Yabanahano/web-search) - Adds aliases for searching with Google, Wiki, Bing, YouTube and other popular services.
*   [welcome-banner (⭐4)](https://github.com/joshuadanpeterson/zsh-welcome-banner) - Displays a login banner with a random quote.
*   [westchange (⭐0)](https://github.com/TomiVidal99/westchange) - Allows you to quickly change between directories. Requires [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [which-jspm (⭐0)](https://github.com/zkuzmic/which-jspm/) - Adds `npm`, `yarn` or `pnpm` to the end of your prompt depending on what lockfile(s) it detects in the current directory.
*   [whisp (⭐0)](https://github.com/jaacob/whisp) - Adds idempotency and convenience features to OpenAI's Whisper CLI tool. It helps you efficiently transcribe audio files without duplicating work.
*   [whobrokemycode (⭐0)](https://github.com/cameronbroe/whobrokemycode) - Highlight where a particular line was last changed in a file using `git blame`.
*   [window-title (⭐33)](https://github.com/olets/zsh-window-title) - Adds informative tiles to your terminal windows.
*   [windows-title (⭐3)](https://github.com/mdarocha/zsh-windows-title) - Dynamically updates terminal window title with current directory and the last command run.
*   [wordle (⭐3)](https://github.com/zechris/zwordle) - Wordle for ZSH, with tab-completions.
*   [workon (⭐6)](https://github.com/bryanculver/workon.plugin.zsh) - Simple utility for jumping between projects.
*   [worktree (⭐3)](https://github.com/jspears/worktree) - Adds functions that wrap `git worktree`.
*   [wpm (⭐1)](https://github.com/btror/wpm) - Lets you test your typing speed in a terminal, track WPM, accuracy, and more. Results are saved in a handy JSON format for easy tracking.
*   [wsl (⭐2)](https://github.com/florentinl/omz-wsl) - Adds helper functions to make it easier to work in ZSH when running inside WSL.
*   [wsl2-ssh-pageant (⭐1)](https://github.com/antoinemartin/wsl2-ssh-pageant-oh-my-zsh-plugin) - Use your Yubikey stored GPG keys from WSL. This packages the instructions from [wsl2-ssh-pageant repo (⭐368)](https://github.com/BlackReloaded/wsl2-ssh-pageant) as a ZSH plugin.
*   [xdg-basedirs (⭐0)](https://github.com/krahlos/xdg-basedirs) - sets up the XDG base directories according to the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/latest/). This plugin ensures that your environment is configured properly for storing user data, cache,and configuration files.
*   [xxh (ninagrosse) (⭐0)](https://github.com/ninagrosse/xxh-plugin-zsh-ohmyzsh) - Plugin for [xxh (⭐5.6k)](https://github.com/xxh/xxh) that requires [xxh-plugin-prerun-cli-tools (⭐0)](https://github.com/ninagrosse/xxh-plugin-prerun-cli-tools).
*   [xxh (roman-geraskin) (⭐5)](https://github.com/roman-geraskin/xxh-plugin-zsh-zshrc) - plugin for [xxh-shell-zsh (⭐38)](https://github.com/xxh/xxh-shell-zsh) that copies your `~/.zshrc` to a remote host and sources it with [xxh-shell-zsh (⭐38)](https://github.com/xxh/xxh-shell-zsh).
*   [yadm (⭐9)](https://github.com/juanrgon/yadm-zsh) - Displays a warning if there are local `yadm` configuration changes.
*   [yapipenv (⭐0)](https://github.com/AnonGuy/yapipenv.zsh) - Automatically activate a directory's `pip` environment if `pipenv` detects the presence of one.
*   [yazi-mount (⭐0)](https://github.com/splixx05/zsh-yazi-mount) - Mount USB partitions via `udisksctl`, open them in [yazi (⭐24k)](https://github.com/sxyazi/yazi), and unmount them afterward – safe, clean, and user-friendly.
*   [yazi-zoxide (⭐7)](https://github.com/fdw/yazi-zoxide-zsh) - This plugin for [zsh](https://www.zsh.org) adds just one shortcut, but unfolds the magic of both [Zoxide (⭐26k)](https://github.com/ajeetdsouza/zoxide) and [yazi (⭐24k)](https://github.com/sxyazi/yazi/). Without arguments, `y` just opens yazi. If you supply an argument that is a directory, `yazi` is opened in that directory. But if you supply anything else as an argument, `zoxide` is called with the argument and `yazi` is opened there.
*   [yeoman (⭐40)](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez's [Yeoman](http://yeoman.io/) plugin for [oh-my-zsh](https://ohmyz.sh/), compatible with yeoman version ≥1.0 (includes options and command auto-completion).
*   [you-should-use (⭐1.7k)](https://github.com/MichaelAquilina/zsh-you-should-use) - ZSH plugin that reminds you to use those aliases you defined.
*   [youtube-dl-aliases (⭐7)](https://github.com/katrinleinweber/oh-my-zsh-youtube-dl-aliases) - Adds `yt` aliases to download videos from YouTube.
*   [youtube-dl (⭐2)](https://github.com/joow/youtube-dl) - Simple plugin for [youtube-dl](https://youtube-dl.org/).
*   [yup (⭐0)](https://github.com/redxtech/zsh-yup) - Adds helper function to upgrade all the dependencies in a `yarn`/`npm` project.
*   [z.lua (⭐3.1k)](https://github.com/skywind3000/z.lua) - A command line tool which helps you navigate faster by learning your habits. An alternative to [z.sh (⭐17k)](https://github.com/rupa/z) with Windows and posix shells support and various improvements. 10x faster than fasd and autojump, 3x faster than [z.sh (⭐17k)](https://github.com/rupa/z).
*   [zabb (⭐41)](https://github.com/Mellbourn/zabb) - `zabb` is a command that tries to figure out the shortest memorable abbreviation of a directory that is usable by [z (⭐26k)](https://github.com/ajeetdsouza/zoxide) to unambiguously jump to that directory.
*   [zabrze (⭐40)](https://github.com/Ryooooooga/zabrze) - A ZSH abbreviation expansion plugin.
*   [zapmarks (⭐1)](https://github.com/iliutaadrian/zapmarks) - Provides quick access to your most used command-line bookmarks. It allows you to save, search, and execute complex commands with ease.
*   [zautoload (⭐4)](https://github.com/Doc0x1/zautoload) - Autoloader for ZSH config files.
*   [zaw (⭐576)](https://github.com/zsh-users/zaw) - ZSH anything.el-like widget.
*   [zbrowse (⭐19)](https://github.com/zdharma-continuum/zbrowse) - When doing shell work, it is often the case that `echo $variable` is invoked multiple times, to check the result of a loop, etc. With ZBrowse, you just need to press `Ctrl-B`, which invokes the ZBrowse – Zshell variable browser.
*   [zce (⭐63)](https://github.com/hchbaw/zce.zsh) - Vim's EasyMotion / Emacs's ace-jump-mode for ZSH.
*   [zcolors (⭐82)](https://github.com/marlonrichert/zcolors) - Uses your `$LS_COLORS` to generate a coherent theme for Git and your Zsh prompt, completions and [ZSH syntax highlighting (⭐21k)](https://github.com/zsh-users/zsh-syntax-highlighting).
*   [zconvey (⭐3)](https://github.com/zdharma-continuum/zconvey) - Adds ability to send commands to other ZSH sessions, you can use this to `cd $PWD` on all active ZSH sessions, for example.
*   [zed (⭐7)](https://github.com/eendroroy/zed-zsh) - A simple wrapper for [z (⭐17k)](https://github.com/rupa/z) to install it via a ZSH plugin.
*   [zellij (jaeheonji) (⭐6)](https://github.com/jaeheonji/zsh-zellij-plugin) - Provides an environment that uses [zellij (⭐24k)](https://github.com/zellij-org/zellij). Requires [tmux (⭐37k)](https://github.com/tmux/tmux). Deprecated by author, now [supported natively](https://zellij.dev/documentation/integration.html#autostart-on-shell-creation).
*   [zellij (tranzystorek-io)](https://codeberg.org/tranzystorekk/zellij.zsh) - Provides an environment that autostarts [zellij (⭐24k)](https://github.com/zellij-org/zellij) as your terminal's multiplexer.
*   [zeno (⭐172)](https://github.com/yuki-yano/zeno.zsh) - Fuzzy completion and utility plugin powered by [Deno](https://deno.land/).
*   [zenplash (⭐3)](https://github.com/Chivier/zenplash) - Creates files from templates stored in a user directory.
*   [zenv (⭐2)](https://github.com/janitha/zenv) - Isolated working shell enviornments per directory (like direnv, but uses a new shell instance to provide cleaner isolation).
*   [zero (⭐16)](https://github.com/arlimus/zero.zsh) - Zero is both a plugin and a theme. See the GitHub page for installation details. Includes `git` and `hg` status decorators.
*   [zeza (⭐2)](https://github.com/duggum/zeza) - Manages and customizes [eza (⭐15k)](https://github.com/eza-community/eza), the very colorful `ls` replacement.
*   [zflai (⭐3)](https://github.com/zdharma-continuum/zflai) - A fast logging framework for ZSH.
*   [zfzf (⭐24)](https://github.com/b0o/zfzf) - A fzf-powered file picker for ZSH which allows you to quickly navigate the directory hierarchy.
*   [zgen-compinit-tweak (⭐3)](https://github.com/seletskiy/zsh-zgen-compinit-tweak) - Make `compinit` run only once after all loading is done by [zgen (⭐1.5k)](https://github.com/tarjoilija/zgen).
*   [zgenom-ext-eval (⭐4)](https://github.com/jandamm/zgenom-ext-eval/) - [zgenom (⭐388)](https://github.com/jandamm/zgenom) extension for creating plugins inline.
*   [zhooks (⭐63)](https://github.com/agkozak/zhooks) - Displays the contents of any ZSH hook arrays and the code of any hook functions that have been defined. Useful for debugging.
*   [zi-rbenv (⭐5)](https://github.com/z-shell/zi-rbenv) - Fast `rbenv` loads if you're using [zi (⭐789)](https://github.com/z-shell/zi/).
*   [zimfw-extras (⭐0)](https://github.com/PatTheMav/zimfw-extras) - Custom extras for [zimfw (⭐4.1k)](https://github.com/zimfw/zimfw), packaged into a zimfw plugin.
*   [zinfo\_line (⭐1)](https://github.com/kmhjs/zinfo_line) - Makes more information available to ZSH themes.
*   [zinit-annex-bin-gem-node (⭐7)](https://github.com/zdharma-continuum/zinit-annex-bin-gem-node) - [zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit) extension that exposes binaries without altering `$PATH`, installs Ruby gems and Node modules and easily exposes their binaries, and updates the gems and modules when the associated plugin or snippet is updated.
*   [zinit-annex-default-ice (⭐3)](https://github.com/zdharma-continuum/zinit-annex-default-ice) - Allows user to define ices active for multiple zinit commands.
*   [zinit-annex-man (⭐6)](https://github.com/zdharma-continuum/zinit-annex-man) - [Zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit) extension that generates man pages for all plugins and snippets
*   [zinit-annex-meta-plugins (⭐7)](https://github.com/zdharma-continuum/zinit-annex-meta-plugins) - Install groups of plugins with a single label ([zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit) only).
*   [zinit-annex-patch-dl (⭐3)](https://github.com/zdharma-continuum/zinit-annex-patch-dl) - [zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit) extension that downloads files and applies patches through the provided `dl` and `patch` zinit ices.
*   [zinit-annex-readurl (⭐7)](https://github.com/zdharma-continuum/zinit-annex-readurl) - Adds function to automatically download the newest version of a file to which URL is hosted on a webpage.
*   [zinit-annex-rust (⭐6)](https://github.com/zdharma-continuum/zinit-annex-rust) - [zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit) extension that that installs rust and cargo packages inside plugin directories.
*   [zinit-annex-submods (⭐6)](https://github.com/z-shell/z-a-submods) - [zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit) extension that allows installing and managing additional submodules within a plugin or snippet.
*   [zinit-annex-test (⭐0)](https://github.com/NorthIsMirror/z-a-test) - [zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit) extension that runs tests (via make test, for example) – if it finds any of them – after installing and updating a plugin or snippet.
*   [zinit-annex-unscope (⭐2)](https://github.com/zdharma-continuum/zinit-annex-unscope) - Allows installing plugins for [zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit) without specifying the user name by querying the Github API.
*   [zinit-console (⭐14)](https://github.com/z-shell/zinit-console) - A semigraphical (curses) consolette for the [zinit (⭐3.6k)](https://github.com/zdharma-continuum/zinit) plugin manager.
*   [zinsults (⭐16)](https://github.com/ahmubashshir/zinsults) - Prints insults if a command fails.
*   [zjump (⭐11)](https://github.com/qoomon/zjump) - Simplify ZSH directory navigation; jump to already visited, parent or sub folders.
*   [zlitefetch (⭐6)](https://github.com/ippee/zlitefetch) - Lightweight system information plugin.
*   [zload (⭐14)](https://github.com/mollifier/zload) - Hot Reload for ZSH functions. Enables rapid development.
*   [zlong\_alert (⭐47)](https://github.com/kevinywlui/zlong_alert.zsh) - Uses `notify-send` and rings a bell to alert you when a command that has taken a long time (default: 15 seconds) has completed.
*   [zman (⭐27)](https://github.com/mattmc3/zman) - Use [fzf (⭐70k)](https://github.com/junegunn/fzf) to quickly browse ZSH manuals.
*   [znotify (⭐0)](https://github.com/rudeigerc/znotify) - A simple plugin for sending notifications to other services.
*   [znvm (⭐1)](https://github.com/Ajnasz/znvm) - A [Node.js](https://nodejs.org) version manager for ZSH similar to [nvm.sh (⭐84k)](https://github.com/nvm-sh/nvm) but faster.
*   [zoxide (⭐26k)](https://github.com/ajeetdsouza/zoxide) - A fast alternative to `cd` that learns your habits.
*   [zplug-blame (⭐1)](https://github.com/jkcdarunday/zplug-blame) - A [zplug (⭐5.9k)](https://github.com/zplug/zplug)-specific plugin that displays how long each of your plugins took to load.
*   [zpy (⭐90)](https://github.com/AndydeCleyre/zpy) - Manage Python environments, dependencies, and isolated app installations, with a ZSH frontend for [uv (⭐52k)](https://github.com/astral-sh/uv) or [pip-tools (⭐7.9k)](https://github.com/jazzband/pip-tools).
*   [zredis-cmd (⭐4)](https://github.com/z-shell/zredis-cmd) - Utilizes variable sharing done by [zredis (⭐3)](https://github.com/zdharma-continuum/zredis) plugin to implement remote command execution.
*   [zredis (⭐3)](https://github.com/zdharma-continuum/zredis) - Adds [Redis](https://redis.io/) database support, with `database_key` <-> `shell_variable` binding. Supports all data types.
*   [zservice-py3http (⭐4)](https://github.com/z-shell/zservice-py3http) - Serve a given directory with Python 3's http server from the standard library.
*   [zsh-expand (⭐32)](https://github.com/MenkeTechnologies/zsh-expand) - Expands regular aliases, global aliases and incorrect spellings and phrases with the spacebar key. Native expansions such as globs, command/process substitution, `=command expansion`, history expansion and `$parameters` are also expanded by default but can be turned off.
*   [zsh-in-docker (⭐991)](https://github.com/deluan/zsh-in-docker) - Automates ZSH + [oh-my-zsh](https://ohmyz.sh/) installation into development containers. Works with Alpine, Ubuntu, Debian, CentOS or Amazon Linux.
*   [zshcp (⭐1)](https://github.com/michaelsousajr/zshcp) - A lightweight and intuitive clipboard management plugin for Zsh that enhances your command-line workflow with easy copy-paste operations.
*   [zsh-not-vim (⭐3)](https://github.com/redxtech/zsh-not-vim) - Provides a function that automatically shames the user for forgetting they weren't in `vim`.
*   [zsh-select (⭐9)](https://github.com/z-shell/zsh-select) - Displays a selection list. It is similar to `selecta`, but uses the curses library to do display, and when compared to [fzf (⭐70k)](https://github.com/junegunn/fzf), the main difference is approximate matching instead of fuzzy matching.
*   [zsh-watch (⭐5)](https://github.com/Thearas/zsh-watch) - Simple `watch` that supports alias and completion.
*   [zsh-z (agkozak) (⭐2.2k)](https://github.com/agkozak/zsh-z) - Jump quickly to directories that you have visited "frecently." A native ZSH port of `z.sh` - without `awk`, `sed`, `sort`, or `date`.
*   [zsh-z (ptavares) (⭐0)](https://github.com/ptavares/zsh-z) - Installs and loads [z](https://github.com/rupa/z.git).
*   [zshange\_directory\_recent (⭐0)](https://github.com/Kjeldgaard/zshange_directory_recent) - Change to a recent directory. Requires [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [zshmarks (⭐279)](https://github.com/jocelynmallon/zshmarks) - A port of Bashmarks (by Todd Werth), a simple command line bookmarking plugin, for [oh-my-zsh](https://ohmyz.sh).
*   [zshrc-sync (⭐3)](https://github.com/Skylor-Tang/zshrc-sync) - Detects changes to `.zshrc` and pushes them to github when `zsh` exits.
*   [zshrc (⭐5)](https://github.com/freak2geek/zshrc) - Load local `.zshrc` files from your project scopes.
*   [zshrpg (⭐1)](https://github.com/aliervo/zshrpg) - A wrapper that fully integrates [rpg-cli (⭐1.6k)](https://github.com/facundoolano/rpg-cli/) with ZSH!
*   [zsnapac (⭐2)](https://github.com/johnramsden/zsh-zsnapac) - Plugin for taking ZFS pre/post upgrade snapshots on Arch Linux.
*   [zsnapshot (⭐3)](https://github.com/zdharma-continuum/zsnapshot) - Adds command to dump the current ZSH state into a file, for later restoration by sourcing the snapshot file.
*   [ztouch (⭐3)](https://github.com/mjrafferty/ztouch) - Adds touchbar controls for recent history commands, directory stack, cycling between modes and user-mappable commands to the touchbar on macOS.
*   [ztrace (⭐8)](https://github.com/zdharma-continuum/ztrace) - Catches output of commands, allows to reuse that output, glue it with history content.
*   [zui (⭐12)](https://github.com/zdharma-continuum/zui) - ZSH User Interface library – CGI+DHTML-like rapid TUI application development with ZSH.)
*   [zypper-short (⭐0)](https://github.com/justanotherinternetguy/zypper-short) - Plugin for OpenSuse Tumbleweed's package manager, `zypper`.

## Completions

These plugins add tab completions without adding extra functions or aliases.

*   [1password-op (⭐10)](https://github.com/unixorn/1password-op.plugin.zsh) - Loads autocompletions for 1Password's [op](https://developer.1password.com/docs/cli/get-started/) command line tool.
*   [aider (⭐2)](https://github.com/hmgle/aider-zsh-complete) - Tab completions for [aider](https://aider.chat/).
*   [aircrack (⭐5)](https://github.com/Doc0x1/Aircrack-Zsh-Completions) - Adds completions for `airbase-ng`, `aircrack-ng`, `airdecap-ng`, `airdecloak-ng`, `aireplay-ng`, `airmon-ng`, `airodump-ng`, `airolib-ng`, `airserv-ng`, `airtun-ng`, `airventriloquist-ng`.
*   [aliyun (⭐0)](https://github.com/thuandt/zsh-aliyun) - Add completions for the [Aliyun CLI (⭐863)](https://github.com/aliyun/aliyun-cli).
*   [ansible-server (⭐3)](https://github.com/viasite-ansible/zsh-ansible-server) - Completions for [viasite-ansible/ansible-server (⭐14)](https://github.com/viasite-ansible/ansible-server).
*   [antibody (⭐0)](https://github.com/sinetoami/antibody-completion) - This plugin provides completion for the [Antibody (⭐1.7k)](https://github.com/getantibody/antibody) plugin manager.
*   [appspec (⭐6)](https://github.com/perlpunk/App-AppSpec-p5) - Generating completions for Bash and ZSH from YAML specs
*   [argc-completions (⭐327)](https://github.com/sigoden/argc-completions) - Uses [argc (⭐924)](https://github.com/sigoden/argc) and [jq (⭐32k)](https://github.com/stedolan/jq) to add ZSH tab completions.
*   [audogombleed.sh (⭐5)](https://github.com/i-love-coffee-i-love-tea/audogombleed.sh) - Makes it easy to generate completion files using a declarative syntax, quickly and without coding.
*   [autopkg-zsh-completion (⭐9)](https://github.com/fuzzylogiq/autopkg-zsh-completion) - Completions for autopkg.
*   [autorestic (⭐3)](https://github.com/naegling/zsh-autorestic) - automatically installs [Restic (⭐1.5k)](https://github.com/cupcakearmy/autorestic/)'s completions for you, and keeps them up to date as your autorestic version changes.
*   [aws\_manager completions (⭐2)](https://github.com/EslamElHusseiny/aws_manager_plugin) - Add completions for the `aws_manager` CLI.
*   [aws-completions (⭐5)](https://github.com/eastokes/aws-plugin-zsh) - Adds completion support for `awscli` to manage AWS profiles/regions and display them in the prompt.
*   [bash-completions-fallback (⭐63)](https://github.com/3v1n0/zsh-bash-completions-fallback) - Support `bash` completions for commands when no native ZSH one is available.
*   [batect (⭐1)](https://github.com/batect/batect-zsh-completion/) - Adds tab completions for [batect](https://batect.dev/) build system.
*   [berkshelf-completions (⭐17)](https://github.com/berkshelf/berkshelf-zsh-plugin) - Adds tab completion for berkshelf.
*   [better-npm-completion (⭐483)](https://github.com/lukechilds/zsh-better-npm-completion) - Better tab completion for `npm`.
*   [bio (⭐9)](https://github.com/yamaton/zsh-completions-bio/) - Completions for bioinformatics tools.
*   [bitbake (⭐3)](https://github.com/antznin/zsh-bitbake) - Completions for [bitbake](https://git.openembedded.org/bitbake).
*   [bosh (krujos) (⭐2)](https://github.com/krujos/bosh-zsh-autocompletion) - Adds [BOSH (⭐2.1k)](https://github.com/cloudfoundry/bosh) autocompletion.
*   [bosh (thomasmitchell) (⭐9)](https://github.com/thomasmitchell/bosh-complete) - Tab completion for [BOSH (⭐2.1k)](https://github.com/cloudfoundry/bosh).
*   [brew-completions (⭐9)](https://github.com/z-shell/brew-completions) - Brings [Homebrew Shell Completion](https://docs.brew.sh/Shell-Completion) under the control of ZSH & [ZI (⭐789)](https://github.com/z-shell/zi/).
*   [brew-services (⭐19)](https://github.com/vasyharan/zsh-brew-services) - Completion plugin for [homebrew](https://brew.sh) services.
*   [buidler (⭐3)](https://github.com/gonzalobellino/buidler-zsh) - Adds completion and useful aliases for NomicLabs Buidler tool.
*   [bw (⭐1)](https://github.com/CupricReki/zsh-bw-completion) - Adds completion for [Bitwarden](https://bitwarden.com/).
*   [cabal (d12frosted) (⭐0)](https://github.com/d12frosted/cabal.plugin.zsh) - Adds autocompletion for cabal.
*   [cabal (ehamberg) (⭐1)](https://github.com/ehamberg/zsh-cabal-completion) - Add tab completion for cabal.
*   [carapace-bin (⭐1.2k)](https://github.com/rsteube/carapace-bin) - Multi-shell multi-command argument completer.
*   [carapace (⭐575)](https://github.com/rsteube/carapace) - Completion generator for Bash, Elvish, Fish, Oil, Powershell, Xonsh and ZSH. Note - this does not automatically generate completions as needed, you have to explicitly run it to generate completions for a command.
*   [cargo (⭐30)](https://github.com/MenkeTechnologies/zsh-cargo-completion) - All the functionality of the original oh-my-zsh cargo completion, with additional support for remote crates via `cargo search` in `cargo add`.
*   [carthage (⭐1)](https://github.com/squarefrog/zsh-carthage) - Provides completions and aliases for use with [Carthage (⭐15k)](https://github.com/Carthage/Carthage).
*   [cf-zsh-autocomplete (⭐34)](https://github.com/norman-abramovitz/cf-zsh-autocomplete-plugin) - Adds autocomplete for all [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) commands.
*   [chezmoi (⭐4)](https://github.com/mass8326/zsh-chezmoi) - Adds completions and aliases for [chezmoi](https://www.chezmoi.io/). Detects if you have `git` aliases and generates `chezmoi` aliases for them.
*   [click-completion (⭐289)](https://github.com/click-contrib/click-completion) - Add automatic completion support for [Click](http://click.pocoo.org/), including displaying the options and commands help during the tab completion.
*   [cod (⭐529)](https://github.com/dim-an/cod) - A completion demon for `bash`/`fish`/`zsh` which creates completion functions on the fly when it sees you run something with `--help`.
*   [codeception (⭐12)](https://github.com/shengyou/codeception-zsh-plugin) - Adds command completion for the Codeception Testing Framework.
*   [comonicon (⭐0)](https://github.com/Roger-luo/ComoniconZSHCompletion.jl) - Tab completions for [comonicon (⭐285)](https://github.com/Roger-luo/Comonicon.jl).
*   [complete-lastf (⭐1)](https://github.com/chougousui/complete-lastf) - Adds a tab completion to select the most recently modified file or directory.
*   [complete-mac (⭐6)](https://github.com/vitkabele/complete-mac) - Add completions for macOS `ioreg`, `lsmp`, `scselect`, `system_profiler` and `tmutil` commands.
*   [completion-sync (⭐14)](https://github.com/BronzeDeer/zsh-completion-sync) - Automatically loads completions added dynamically to `FPATH` or `XDG_DATA_DIRS`.
*   [completions (clarketm) (⭐74)](https://github.com/clarketm/zsh-completions) - This includes the zsh-users[completions (⭐7.3k)](https://github.com/zsh-users/zsh-completions), zchee's [completions (⭐113)](https://github.com/zchee/zsh-completions), nilsonholger's [osx-zsh-completions (⭐12)](https://github.com/nilsonholger/osx-zsh-completions) and various other custom completions.
*   [completions (zchee) (⭐113)](https://github.com/zchee/zsh-completions) - Yet another collection of tab completions.
*   [completions (zsh-users) (⭐7.3k)](https://github.com/zsh-users/zsh-completions) - A collection of extra completions for ZSH.
*   [conda (⭐388)](https://github.com/conda-incubator/conda-zsh-completion) - ZSH tab completion for [conda](http://conda.pydata.org/).
*   [cpan (⭐2)](https://github.com/MenkeTechnologies/zsh-cpan-completion) - Adds `cpan install word<tab>` and `cpanm install <tab>` to complete remote CPAN package names.
*   [cross-compiler (⭐1)](https://github.com/Freed-Wu/zsh-completions-for-cross-compilers) - In cross compilations, there are many tools like x86\_64-w64-mingw32-gcc, x86\_64-linux-android32-clang, arm-none-eabi-gcc, etc. This plugin provides ZSH completions for them.
*   [ctop (⭐4)](https://github.com/gantsign/zsh-plugins/tree/master/ctop) - Tab completions for [ctop (⭐16k)](https://github.com/bcicen/ctop).
*   [dagger (⭐1)](https://github.com/jygastaud/dagger-oh-my-zsh) - Completions for dagger.
*   [dbic (⭐0)](https://github.com/lejeunerenard/dbic-migration-env) - Automatically sets up Environment variables for DBIx::Class::Migration's script and Dancer.
*   [ddc (⭐23)](https://github.com/Shougo/ddc-zsh) - Adds tab completions for [ddc (⭐709)](https://github.com/Shougo/ddc.vim).
*   [deno (⭐0)](https://github.com/marcelohmdias/zsh-deno) - Tab completions for [deno](https://deno.com/).
*   [deoplete (⭐50)](https://github.com/zchee/deoplete-zsh) - ZSH completion for [deoplete.nvim (⭐6k)](https://github.com/Shougo/deoplete.nvim)
*   [docker (chr-fritz) (⭐14)](https://github.com/chr-fritz/docker-completion.zshplugin) - Loads `docker` ZSH tab completions directly from **Docker for Mac**.
*   [docker (felixr) (⭐257)](https://github.com/felixr/docker-zsh-completion) - Add tab completions for `docker`.
*   [docker (greymd) (⭐66)](https://github.com/greymd/docker-zsh-completion) - Add tab completions for `docker` and `docker-compose`.
*   [dotnet (⭐2)](https://github.com/MenkeTechnologies/zsh-dotnet-completion) - Dotnet tab completion.
*   [dropbox (⭐21)](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands.
*   [drush\_zsh\_completion (⭐40)](https://github.com/webflo/drush_zsh_completion) - Drush autocomplete awesomeness for ZSH.
*   [duell (⭐2)](https://github.com/jcxavier/oh-my-zsh-duell) - A ZSH plugin for [duell (⭐40)](https://github.com/gameduell/duell).
*   [efibootmgr (⭐3)](https://github.com/wehlando/efibootmgr-zsh-completion) - Tab completions for `efibootmgr`.
*   [elm (⭐4)](https://github.com/kraklin/elm.plugin.zsh) - Tab completion for [elm](https://elm-lang.org/).
*   [etcdctl (⭐2)](https://github.com/sheax0r/etcdctl-zsh) - Adds etcdctl tab completions.
*   [expressvpn (⭐0)](https://github.com/tk7r/zsh-expressvpn) - Adds tab completions for the [expressVPN](https://www.expressvpn.com/support/vpn-setup/app-for-linux/) client.
*   [extract (le0me55i) (⭐18)](https://github.com/le0me55i/zsh-extract) - Defines a function called extract that extracts the archive file you pass it, and supports a wide variety of archive filetypes.
*   [extract (thetic) (⭐8)](https://github.com/thetic/extract) - Fork of the oh-my-zsh extract plugin.
*   [fancy-completions (⭐15)](https://github.com/z-shell/zsh-fancy-completions) - Provides various completions tools, libraries and integrations.
*   [flatpak (⭐38)](https://github.com/bilelmoussaoui/flatpak-zsh-completion) - Tab completions for [Flatpak](https://docs.flatpak.org/en/latest/using-flatpak.html).
*   [fluxcd (⭐0)](https://github.com/l-umaca/omz-fluxcd-plugin) - Adds tab completion for the [FluxCD command line](https://fluxcd.io/flux/cmd/) tool, as well as some aliases for the most common flux commands.
*   [fly-zsh-autocomplete (⭐1)](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - Adds autocompletion options for all [Concourse CLI](https://concourse-ci.org/fly.html) commands.
*   [fnm (⭐1)](https://github.com/zap-zsh/fnm) - Adds tab completions for Fast Node Manager [fnm (⭐21k)](https://github.com/Schniz/fnm).
*   [fvm (⭐1)](https://github.com/olrtg/zsh-fvm) - Adds tab completions for the [Flutter Version Manager (FVM)](https://fvm.app/).
*   [fzf-gcloud (⭐26)](https://github.com/mbhynes/fzf-gcloud) - Fuzzy completion to navigate and preview all Google Cloud SDK `gcloud` CLI commands
*   [fzf-rg (⭐0)](https://github.com/ppcamp/zsh-fzf-rg) - Add some functionalities to terminal using [fzf (⭐70k)](https://github.com/junegunn/fzf), [bat (⭐52k)](https://github.com/sharkdp/bat) and [ripgrep (⭐52k)](https://github.com/BurntSushi/ripgrep).
*   [fzf-tab-completion (⭐728)](https://github.com/lincheney/fzf-tab-completion) - Add tab completion for ZSH, `bash` & applications using GNU Readline.
*   [fzf-zsh-completions (⭐161)](https://github.com/chitoku-k/fzf-zsh-completions) - Fuzzy completions for [fzf (⭐70k)](https://github.com/junegunn/fzf) and [ZSH](https://www.zsh.org/) that can be triggered by a trigger sequence that defaults to `**`.
*   [fzshell (⭐77)](https://github.com/mnowotnik/fzshell) - Fetches fuzzy completions from sources predefined by a user.
*   [gardenctl (⭐0)](https://github.com/holgerkoser/gardenctl) - Tab completions for the [Gardener (⭐31)](https://github.com/gardener/gardenctl-v2) command-line interface, as well as some aliases for common gardenctl commands
*   [gcloud (littleq0903) (⭐79)](https://github.com/littleq0903/gcloud-zsh-completion) - Add completions for the Google Cloud SDK.
*   [gcloud (wintermi) (⭐4)](https://github.com/wintermi/zsh-gcloud) - Adds Google Cloud Command Line Interface ([gcloud](https://cloud.google.com/cli) CLI) completions.
*   [gentoo (⭐39)](https://github.com/gentoo/gentoo-zsh-completions) - Provides ZSH completion support to various Gentoo tools that lack completion scripts upstream.
*   [git-annex (⭐15)](https://github.com/Schnouki/git-annex-zsh-completion) - Allows tab completion for most git-annex commands.
*   [git-flow (⭐2.8k)](https://github.com/bobthecow/git-flow-completion) - ZSH completion support for [git-flow (⭐27k)](http://github.com/nvie/gitflow).
*   [git-fzf (⭐25)](https://github.com/alexiszamanidis/zsh-git-fzf) - ZSH plugin that wraps `git` operations for simplicity and productivity. It also contains completions and combines support for [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [git-profiles (⭐2)](https://github.com/baliestri/git-profiles.plugin.zsh) - Manages multiple git users in a single `.gitconfig` file.
*   [git-recent-branches (⭐1)](https://github.com/Zacharyjlo/git-recent-branches) - Makes it easy to check view and checkout recently checked-out branches.
*   [github-cli (⭐5)](https://github.com/sudosubin/zsh-github-cli) - Tab completions for the GitHub cli.
*   [gitlab-runner (⭐0)](https://github.com/pseyfert/zsh-gitlab-runner-completion) - ZSH completions for gitlab-ci-multi-runner.
*   [gradle-completion (gradle) (⭐1.1k)](https://github.com/gradle/gradle-completion) - Bash and ZSH completion support for gradle.
*   [gradle-completion (ninrod) (⭐1)](https://github.com/ninrod/gradle-zsh-completion) - ZSH completion support for gradle.
*   [grid5000 (⭐2)](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 plugin - adds theme, autocompletions.
*   [gstreamer (⭐2)](https://github.com/CraigCarey/gstreamer-tab) - Tab completion for [GStreamer](https://gstreamer.freedesktop.org/).
*   [gulp (akoenig) (⭐32)](https://github.com/akoenig/gulp.plugin.zsh) - Autocompletion for your gulp.js tasks in the Z-Shell (ZSH).
*   [gulp (srijanshetty) (⭐10)](https://github.com/srijanshetty/gulp-autocompletion-zsh) - Autocompletion for gulp.
*   [hashlink (⭐0)](https://github.com/tong/zsh.plugin.hashlink) - Completions for <https://hashlink.haxe.org/>.
*   [haskell (⭐19)](https://github.com/coot/zsh-haskell) - Adds completions for `cabal`, `ghc` and `ghc-pkgs` commands.
*   [haxelib (⭐1)](https://github.com/tong/zsh.plugin.haxelib) - Completions for haxelib.
*   [helmfile (⭐4)](https://github.com/Downager/zsh-helmfile) - Adds autocompletion for `helm`.
*   [inshellisense (⭐9.3k)](https://github.com/microsoft/inshellisense) - Provides IDE style autocomplete for shells. It's a terminal native runtime for autocomplete which has support for 600+ command line tools. inshellisense supports `bash`, `fish`, `zsh` and `pwsh` on the Windows, Linux, & MacOS operating systems.
*   [ipfs (⭐9)](https://github.com/hellounicorn/zsh-ipfs) - Completions for the [Interplanetary File System](https://ipfs.tech).
*   [jenv (⭐0)](https://github.com/cmuench/zsh-jenv) - Tab completions for [jEnv (⭐6.1k)](https://github.com/jenv/jenv).
*   [joe (⭐0)](https://github.com/corvofeng/joe-completion) - Adds completions for [joe (⭐2.9k)](https://github.com/karan/joe) gitignore editor.
*   [jtool-completion (⭐0)](https://github.com/beaugalbraith/jtool-completion) - ZSH completions for jtool.
*   [jx (⭐0)](https://github.com/haysclark/zsh-jx) - Adds tab completions for the Jenkins-X cli.
*   [kafka (⭐64)](https://github.com/Dabz/kafka-zsh-completions) - Completions for Apache [kafka](https://kafka.apache.org).
*   [keybase (⭐19)](https://github.com/rbirnie/oh-my-zsh-keybase) - Completions for [keybase](https://book.keybase.io/docs/cli).
*   [kind (⭐1)](https://github.com/TomerFi/zsh-kind)- Loads tab completions for [kind](https://kind.sigs.k8s.io/).
*   [kitty (⭐7)](https://github.com/redxtech/zsh-kitty) - Completions for [kitty](https://sw.kovidgoyal.net/kitty/) terminal emulator.
*   [kompose (⭐4)](https://github.com/gantsign/zsh-plugins/tree/master/kompose) - Add tab completions for [Kompose](http://kompose.io/).
*   [kubeadm (⭐4)](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) - Add tab completions for [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/).
*   [kubectl (chrishrb) (⭐3)](https://github.com/chrishrb/zsh-kubectl) - Automatically loads completions for [kubectl (⭐3k)](https://github.com/kubernetes/kubectl).
*   [kubectl-fzf (⭐453)](https://github.com/bonnefoa/kubectl-fzf) - Fast and powerful [fzf (⭐70k)](https://github.com/junegunn/fzf)-powered autocompletion for `kubectl`.
*   [kubectl-plugin (⭐13)](https://github.com/MartinSimango/kubectl-plugin_completion) - Generates `kubectl` completion scripts to extend the `kubectl` auto complete functionality to accomodate for plugin sub-commands.
*   [kustomize (⭐12)](https://github.com/ralgozino/oh-my-kustomize) - Adds tab completions for [kustomize](https://kustomize.io/)
*   [lazycomplete (⭐24)](https://github.com/rsteube/lazycomplete) - Lazy loading for shell completion scripts.
*   [lets-cli (⭐2)](https://github.com/lets-cli/lets-zsh-plugin) - Add autocompletion for [lets (⭐80)](https://github.com/lets-cli/lets) cli task runner.
*   [llm (⭐9)](https://github.com/eliyastein/llm-zsh-plugin) - Adds tab completions for the [LLM CLI tool](https://llm.datasette.io/).
*   [ls-go (⭐0)](https://github.com/MohamedElashri/ls-go-zsh) - Adds some useful aliases for [ls-go (⭐222)](https://github.com/acarl005/ls-go).
*   [mac (⭐186)](https://github.com/scriptingosx/mac-zsh-completions) - Completions files for macOS specific commands and third party tools.
*   [mcfly (⭐7.2k)](https://github.com/cantino/mcfly) - Replaces your default ctrl-r shell history search with an intelligent search engine that takes into account your working directory and the context of recently executed commands. McFly's suggestions are prioritized in real time with a small neural network.
*   [mill (⭐3)](https://github.com/carlosedp/mill-zsh-completions) - Tab completions for Scala's [Mill](http://mill-build.com/) build tool.
*   [miniconda (⭐1)](https://github.com/cmuench/zsh-miniconda) - Tab completions for [miniconda](https://docs.conda.io/en/latest/miniconda.html).
*   [misc-completions (⭐0)](https://github.com/syohex/zsh-misc-completions) - Adds completions for more unix and perl commands.
*   [mooseX-App (⭐0)](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) - completion generator for Perl module `MooseX::App`.
*   [more-completions (⭐45)](https://github.com/MenkeTechnologies/zsh-more-completions) - 13500 ZSH compsys completions! Most were generated by python scripts that parsed --help output and man page output. As such they are of varying quality. Architecture prefixed completions are in the `architecture_src` directory.
*   [msfvenom (⭐57)](https://github.com/Green-m/msfvenom-zsh-completion) - Tab completions for Metasploit.
*   [mx-honey (⭐9)](https://github.com/mukel/mx-honey) - Provides completions for [mx (⭐190)](https://github.com/graalvm/mx); a command-line tool used for the development of Graal projects. It's meant to improve the usual workflow `build unittest benchmark ...` ease discovery and provide handy aliases.
*   [myincr (⭐0)](https://github.com/gaojunbin/zsh-myincr/) - Speeds up pasting with autosuggest and incr.
*   [newman (⭐0)](https://github.com/selop/newman-autocomplete) - Provides autocompletion for the [Newman CLI (⭐7k)](https://github.com/postmanlabs/newman).
*   [ngrok (⭐1)](https://github.com/bostonaholic/ngrok.plugin.zsh) - Auto-loads [ngrok](https://ngrok.com) and its completions into the shell.
*   [nix (⭐241)](https://github.com/spwhitt/nix-zsh-completions) - Completions for [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/), and [NixOps](https://nixos.org/nixops/).
*   [node-ace (⭐6)](https://github.com/romch007/node-ace-zsh-completion) - Completions for `node ace`.
*   [nova (⭐6)](https://github.com/rbirnie/oh-my-zsh-nova) - Provides auto-complete for nova.
*   [npm-run (⭐54)](https://github.com/akoenig/npm-run.plugin.zsh) - Autocompletion support for `npm run`.
*   [npm-scripts-autocomplete (⭐102)](https://github.com/grigorii-zander/zsh-npm-scripts-autocomplete) - Shows autocomplete suggestions from scripts found in the current directory's `package.json`. Works with `npm` and `yarn`.
*   [nx (⭐141)](https://github.com/jscutlery/nx-completion) - Completions for [nx](https://nx.dev). Requires [`jq`](https://stedolan.github.io/jq/).
*   [oh-my-update (⭐4)](https://github.com/utox39/oh-my-update) - Updates plugins in [oh-my-zsh](https://ohmyz.sh/).
*   [okta (⭐1)](https://github.com/sirhc/okta.plugin.zsh) - Provides command line completions for the [`aws-okta`](https://github.com/segmentio/aws-okta) and [okta-awscli (⭐305)](https://github.com/jmhale/okta-awscli) commands.
*   [ollama (⭐5)](https://github.com/Katrovsky/zsh-ollama-completion) - Tab command completion for Ollama AI models management.
*   [op (⭐9)](https://github.com/sirhc/op.plugin.zsh) - Tab completions for [1Password](https://1password.com/)'s [op](https://1password.com/downloads/command-line/) command line tool.
*   [openstack (⭐2)](https://github.com/florentinl/openstack-zsh-plugin) - Add functions and aliases for managing [OpenStack](https://www.openstack.org/).
*   [osx-zsh-completions (⭐12)](https://github.com/nilsonholger/osx-zsh-completions) - Tab completions for some macOS-specific commands like `launchctl`.
*   [packer (⭐5)](https://github.com/wakeful/zsh-packer) - Adds tab completion for [packer](https://packer.io).
*   [pagerduty (⭐0)](https://github.com/jedelson-pagerduty/pagerduty-omz-plugin) - Adds completions for the pagerduty [cli (⭐94)](https://github.com/martindstone/pagerduty-cli)
*   [pandoc-completion (⭐14)](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc completion plugin.
*   [parallels (⭐9)](https://github.com/benclark/parallels-zsh-plugin) - Add completions for Parallels desktop.
*   [pass-zsh-completion (⭐10)](https://github.com/ninrod/pass-zsh-completion) - convenience repo to easily obtain [pass](https://www.passwordstore.org/) command completion for ZSH.
*   [pip-completion (⭐22)](https://github.com/srijanshetty/zsh-pip-completion) - Autocompletion plugin for pip.
*   [pipenv (AlexGascon) (⭐1)](https://github.com/AlexGascon/pipenv-oh-my-zsh) - Enables aliases for the most common pipenv commands.
*   [pipenv (gangleri) (⭐13)](https://github.com/gangleri/pipenv) - Completions for `pipenv`.
*   [pmy (⭐147)](https://github.com/relastle/pmy) - General purpose context-aware ZSH completion engine powered by [fzf (⭐70k)](https://github.com/junegunn/fzf).
*   [poetry (⭐3)](https://github.com/fourdim/zsh-poetry) - Tab completions for [poetry](https://python-poetry.org/).
*   [prettier (⭐0)](https://github.com/sambergo/zsh-prettier-completion/) - Tab completion for [prettier](https://prettier.io/.)
*   [pytest-fzf (⭐0)](https://github.com/jszczepaniak/zsh-pytest-fzf) - lets you select pytest tests using [fzf (⭐70k)](https://github.com/junegunn/fzf) and insert them into your terminal.
*   [quickjump (⭐1)](https://github.com/fikovnik/zsh-quickjump) - Adds tab completion support for [skim (⭐5.6k)](https://github.com/lotabout/skim) for recent files and directories using [fasd (⭐85)](https://github.com/whjvenyl/fasd).
*   [racket completion (⭐6)](https://github.com/racket/shell-completion) - Completion for [Racket](http://racket-lang.org).
*   [rake-completion (⭐8)](https://github.com/unixorn/rake-completion.zshplugin) - Add fast tab completion for rakefile targets.
*   [rancher (⭐9)](https://github.com/go/rancher-zsh-completion) - Add completions for the Rancher CLI.
*   [rhoas (⭐2)](https://github.com/craicoverflow/rhoas-zsh-plugin) - Adds completions for [rhoas](https://developers.redhat.com/products/red-hat-openshift-streams-for-apache-kafka/overview).
*   [rustup (⭐12)](https://github.com/pkulev/zsh-rustup-completion) - Tab completions for Rustup.
*   [s3cmd (⭐0)](https://github.com/FFKL/s3cmd-zsh-plugin) - Adds tab completions for [s3cmd](https://s3tools.org/s3cmd).
*   [salesforce-cli (⭐90)](https://github.com/wadewegner/salesforce-cli-zsh-completion) - ZSH command completion for the Salesforce CLI. Requires [jq](https://stedolan.github.io/jq/).
*   [saml2aws (⭐2)](https://github.com/sirhc/saml2aws.plugin.zsh) - Adds completions for [saml2aws (⭐2.1k)](https://github.com/Versent/saml2aws).
*   [sdkman (matthieusb) (⭐60)](https://github.com/matthieusb/zsh-sdkman) - Add tab completions for [sdkman](https://sdkman.io/).
*   [sdkman (yongxingzhao) (⭐0)](https://github.com/yongxingzhao/zsh-sdkman) - Add tab completions for [sdkman](https://sdkman.io/).
*   [sfdx-autocomplete (⭐11)](https://github.com/jayree/sfdx-autocomplete-plugin) - Autocomplete plugin for Salesforce [sfdx](https://developer.salesforce.com/tools/salesforcecli).
*   [speedtest (⭐2)](https://github.com/Yash-Singh1/zsh-plugin-speedtest) - Tab completions for the speedtest [cli](https://www.speedtest.net/insights/blog/introducing-speedtest-cli/).
*   [spring-boot-plugin (⭐10)](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - Adds autocompletions for [spring-boot](http://projects.spring.io/spring-boot/) commands.
*   [ssh (sunlei) (⭐164)](https://github.com/sunlei/zsh-ssh) - Better host completion for `ssh`.
*   [ssh (zpm-zsh) (⭐18)](https://github.com/zpm-zsh/ssh) - Add host completion for `ssh`.
*   [ssh-agent (bobsoppe) (⭐26)](https://github.com/bobsoppe/zsh-ssh-agent) - Manage `ssh-agent`.
*   [ssh-agent (hkupty) (⭐12)](https://github.com/hkupty/ssh-agent) - Automatically starts `ssh-agent` to set up and load whichever credentials you want for `ssh` connections.
*   [ssh-agent (twfksh) (⭐2)](https://github.com/twfksh/zsh-ssh-agent) - A bloat free utility plugin for managing ssh-agent in ZSH. This plugin automatically starts and manages `ssh-agent` whenever a new ternimal session starts. After running zsh-ssh-agent, you only need to `ssh-add` your keys once. The plugin will handle the rest.
*   [ssh-config-suggestions (⭐1)](https://github.com/yngc0der/zsh-ssh-config-suggestions)- Loads completions for `ssh` from `~/.ssh/config`.
*   [supabase (⭐0)](https://github.com/Taimoor-Tariq/zsh-supabase) - Tab completions for the [supabase cli](https://supabase.com/docs/guides/cli/getting-started)
*   [symfony (Akollade) (⭐4)](https://github.com/Akollade/symfony.plugin.zsh) - Adds completions for [Symfony](https://symfony.com/), including the `bin/console` and `sf` commands.
*   [symfony-complete (⭐7)](https://github.com/voronkovich/symfony-complete.plugin.zsh) - Universal completion for [Symfony](https://symfony.com/doc/current/components/console.html) based CLI applications: `composer`, `php-cs-fix`, `bin/console`, `artisan`, `php-cs-fixer` and etc. This supports autocompletion for subcommands and GNU-style options (`--help`)
*   [tailscale (heroeslament) (⭐8)](https://github.com/HeroesLament/zsh-tailscale-plugin) - Tab completion and aliases for [tailscale](https://www.tailscale.com/).
*   [tailscale (hsrzq) (⭐3)](https://github.com/hsrzq/PluginForTailscale) - Tab completions for [tailscale](https://www.tailscale.com/). Only works on macOS.
*   [tailscale-ssh (⭐0)](https://github.com/Seraphin-/zsh-tailscale-ssh) - Provides host completion based off tailscale status. It automatically strips the MagicDNS suffix, if present.
*   [talosctl (⭐2)](https://github.com/RusMephist/talosctl-zsh-plugin) - Tab completion for [Talos Linux](https://www.talos.dev/v1.6/introduction/what-is-talos/).
*   [task (⭐2)](https://github.com/targendaz2/taskfile) - Tab completions for [Task](https://taskfile.dev/).
*   [taskbook (⭐3)](https://github.com/mastern2k3/taskbook-zsh-plugin) - Auto-completes task numbers for taskbook.
*   [terragrunt (⭐17)](https://github.com/jkavan/terragrunt-oh-my-zsh-plugin) - Tab completion for [Terragrunt (⭐8.6k)](https://github.com/gruntwork-io/terragrunt).
*   [test-kitchen (⭐7)](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - Add completions for [Test Kitchen (⭐1.9k)](https://github.com/test-kitchen/test-kitchen)).
*   [tinygo (⭐16)](https://github.com/sago35/tinygo-autocmpl) - Add tab completions for [tinygo](https://tinygo.org/).
*   [tmux pane words](https://gist.github.com/blueyed/6856354) - Key bindings to complete words from your [tmux](https://tmux.github.io) pane.
*   [tofu (⭐0)](https://github.com/marknefedov/oh-my-zsh-tofu) - Autoloads tab completions for `tofu`.
*   [tugboat (⭐4)](https://github.com/DimitriSteyaert/Zsh-tugboat) - Adds autocompletion for [tugboat (⭐1.4k)](https://github.com/petems/tugboat) command.
*   [umake (⭐1)](https://github.com/zlsun/umake) - Tab completion for Ubuntu umake.
*   [url-httplink (⭐4)](https://github.com/Valodim/zsh-_url-httplink) - Extends ZSH's \_urls completion, allowing it to complete urls from html pages.
*   [uv (⭐1)](https://github.com/lipov3cz3k/zsh-uv) - Tab completion for [uv (⭐52k)](https://github.com/astral-sh/uv).
*   [vert.x (⭐0)](https://github.com/davidafsilva/vert.x-omz-plugin) - Provides autocomplete features for the [vertx](https://vertx.io/) command.
*   [vorpal (⭐1)](https://github.com/VorpalBlade/vorpal-zsh-completions) - Adds completions for some projects whose upstream appears dead, including [duperemove (⭐883)](https://github.com/markfasheh/duperemove), [optimus-manager (⭐2.4k)](https://github.com/Askannz/optimus-manager) and [pacutils (⭐118)](https://github.com/andrewgregory/pacutils).
*   [web-open (⭐1)](https://github.com/AndrewHaluza/zsh-web-open) - Adds alias to open web pages. Only works with Ubuntu 20.
*   [web-search (⭐2)](https://github.com/GowayLee/zsh_web_search) - Runs a search in the specified search engine in your default browser.
*   [wsl-notify (⭐1)](https://github.com/masonc15/wsl-notify-zsh) - Uses [wsl-notify-send (⭐136)](https://github.com/stuartleeks/wsl-notify-send) to notify when a command takes longer than 15 seconds. Windows-only.
*   [xcode (⭐61)](https://github.com/keith/zsh-xcode-completions) - Completions for some Xcode command line tools - `genstrings`, `nm`, `plutil`, `xcode-select`, `xcodebuild`, `xcrun`, `simctl`, `strings`, `swift-demangle`, `swift` and `lipo`.
*   [yabai (⭐16)](https://github.com/Amar1729/yabai-zsh-completions) - Add completions for macOS [yabai (⭐26k)](https://github.com/koekeishiya/yabai/) tiling window manager.
*   [yarn-extra-completion (⭐38)](https://github.com/BuonOmo/yarn-extra-completion) - Inspired by [lukechilds/zsh-better-npm-completion (⭐483)](https://github.com/lukechilds/zsh-better-npm-completion).
*   [yarn (⭐580)](https://github.com/g-plane/zsh-yarn-autocompletions) - Add autocompletions for `yarn add`, `yarn remove`, `yarn upgrade`, `yarn why` and `yarn run`.
*   [yt-dlp (⭐6)](https://github.com/clavelm/yt-dlp-omz-plugin) - Tab completions for [yt-dlp (⭐109k)](https://github.com/yt-dlp/yt-dlp).
*   [zargparse (⭐11)](https://github.com/ctil/zargparse) - Pass it a script that uses `argparse` and it will write a ZSH completion to your current directory.
*   [zenquotes (⭐0)](https://github.com/aminelch/zenquotes) - Displays a random quote from [zenquotes.io](https://zenquotes.io).
*   [zoxide (⭐0)](https://github.com/jnooree/zoxide-zsh-completion) - Tab completions for [zoxide (⭐26k)](https://github.com/ajeetdsouza/zoxide).
*   [zpacman (⭐0)](https://github.com/Yttehs-HDX/zsh-zpacman/) - Add tab completions for [zpacman](https://github.com/Yttehs-HDX/zpacman.git).

## Themes

*   [021011 (⭐100)](https://github.com/guesswhozzz/021011.zsh-theme) - Minimalist. Includes a single `git` marker for VS Code.
*   [0i0 (⭐15)](https://github.com/0i0/0i0.zsh-theme) - Optimized for dark terminal windows, uses nerdfont `git` status decorations.
*   [14degree (⭐2)](https://github.com/saims0n/14degree-zsh-theme/) - Includes `git`, `virtualenv` and `rvm` status decorations.
*   [1999 (⭐6)](https://github.com/DTan13/zsh1999) - Powerline-esque theme. Includes `git` status decorations, network and battery status.
*   [a (⭐3)](https://github.com/chammanganti/a-zsh-theme) - Simple theme with current directory and `git` status decorations.
*   [abbr (theme) (⭐2)](https://github.com/PhilsLab/abbr-zsh-theme) - Displays an abbreviated version of the current directory path, shows the Python virtualenv, Rust version, `git` status, and the exit code of last command. Works well on dark backgrounds by default but colors can be easily customized.
*   [abhiyan (⭐7)](https://github.com/abhiyandhakal/abhiyan.zsh/) - Segmented prompt. Includes decorators for `git` branch, staged file count, unstaged file count & untracked file count, username, current working directory and the time. Requires Powerline-compatible fonts.
*   [absolute (⭐41)](https://github.com/NelsonBrandao/absolute) - Very clean looking theme with decorators for `git` status, `node` version and the exit code from the last command.
*   [abzt (⭐0)](https://github.com/stentibbing/abzt-zsh-theme) - No nonsense theme with decorators for `git` status and directory information. Requires a nerdfont.
*   [acenoster (⭐14)](https://github.com/himdek/Acenoster-ZSH-Theme) - A multi-purpose theme with very detailed `git` and `mercurial` support. Also includes decorators for AWS profile name, virtual environment name if any, number of background tasks, current directory and previous command's exit code if non-zero.
*   [achab (⭐3)](https://github.com/niotna/antoinechab-theme) - Includes decorators for the current folder path, the current user and the current `git` branch. Decorator colors are easily customizable.
*   [adamdodev (⭐1)](https://github.com/adamdodev/adamdodev-zsh-theme) - Includes decorators for `git` status, the name of your AWS profile, the name of your Azure Service Principal, kubernetes context, terraform workspace, last command exit status and current working directory.
*   [adlee (⭐0)](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) - macOS theme, requires a Powerline-compatible font.
*   [af-magic-dynamic (⭐1)](https://github.com/rslavin/af-magic-dynamic) - Modified version of [af-magic (⭐7)](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) with dynamic path shortening.
*   [aflah-bhari (⭐0)](https://github.com/AflahB/aflah-bhari-zsh-theme) - Modified version of the [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme in oh-my-zsh.
*   [aftermath (⭐1)](https://github.com/schanur/aftermath) - Get a nice summary line after each command you run in your shell.
*   [agitnoster (⭐7)](https://github.com/dbestevez/agitnoster-theme) - Based on [agnoster](https://gist.github.com/3712874) theme included in [Oh My Zsh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh) and [bash-git-prompt (⭐6.8k)](https://github.com/magicmonty/bash-git-prompt). Shows detailed information about `git` status.
*   [agkozak (⭐309)](https://github.com/agkozak/agkozak-zsh-prompt) - Uses three asynchronous methods to keep the ZSH prompt responsive while displaying the `git` status and indicators of SSH connection, exit codes, and `vi` mode, along with an abbreviated, `PROMPT_DIRTRIM`-style path. Very customizable. Asynchronous even on Cygwin and MSYS2.
*   [agnopro (⭐1)](https://github.com/arhafizi/agnopro-zsh-theme) - A high-performance, feature-rich ZSH theme with intelligent context display, inspired by and based on Agnoster but enhanced with additional developer-friendly features. Includes decorators for current directory, nodejs version, golang version, .Net version, `git` status, AWS profile, user\@host, background jobs and Python environment.
*   [agnoster (fcamblor) (⭐248)](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) - Solarized [Agnoster](https://gist.github.com/agnoster/3712874) variant with `git` status information. Requires a unicode font and works best with a [solarized (⭐16k)](https://github.com/altercation/solarized) terminal.
*   [agnoster (fseguin) (⭐4)](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [agnoster](https://gist.github.com/agnoster/3712874) variant with a right prompt.
*   [agnoster-gentoo (⭐1)](https://github.com/r7l/agnoster-gentoo-zsh-theme) - A Gentoo flavored version of the [Agnoster ZSH Theme (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme) that includes user\@hostname and `git` status decorations. Works better with a unicode font.
*   [agnoster-j (⭐20)](https://github.com/apjanke/agnosterj-zsh-theme) - Optimized for [solarized](https://ethanschoonover.com/solarized/) color scheme, `git` or other VCS tools, and unicode-compatible fonts. Includes decorators for status of last command run, user\@hostname, `git` status, working directory, whether running as root, whether background jobs are running, and other information.
*   [agnoster-mod (⭐4)](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with a right-prompt.
*   [agnoster-multiline (⭐0)](https://github.com/mxkrsv/agnoster-multiline) - Based on [Agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme). Includes decorators for current directory and `git` status. Requires a font with powerline and `git` glyphs. Automatically disables non-ascii glyphs on linux ttys.
*   [agnoster-plus (⭐7)](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant optimized for use with [Solarized Dark (⭐16k)](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) terminal color scheme. Includes `git` status.
*   [agnoster-refresh (⭐4)](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) variant, includes battery and online status.
*   [agnoster-repopath (⭐2)](https://github.com/ivanfurlan/agnoster-repopath-theme) - Based on [Agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme) and [Passion (⭐313)](https://github.com/ChesterYue/ohmyzsh-theme-passion) themes. Includes `git` and `mercurial` status, current time and time the last command took decorations in the prompt.
*   [agnoster-timestamp-newline (⭐6)](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with timestamp and newline added.
*   [agnoster](https://gist.github.com/agnoster/3712874) - Optimized for solarized terminal color schemes, shows `git` decorations, user\@host, working directory, the previous command's exit status and whether you are running with root privileges. Requires a Powerline-compatible font.
*   [agnosterAfro (⭐6)](https://github.com/afrozalm/agnosterAfro) - Based on [Powerline (⭐2.9k)](https://github.com/Lokaltog/vim-powerline) and [Agnoster](https://gist.github.com/agnoster/3712874) themes and inspired by the [agnosterzak (⭐393)](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
*   [agnosterzak (⭐393)](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - Based on [Agnoster](https://gist.github.com/agnoster/3712874), shows battery life, date & time, `git` status, current directory and user & host information.
*   [ai-hayasaka (⭐0)](https://github.com/aeghost/ai-hayasaka-zsh-theme) - Minimalist theme with `git` status, ruby env and python virtualenv decorators.
*   [air (⭐0)](https://github.com/Ivan-Kuzmichev/air) - Minimalist theme with `git` status decorations.
*   [akzsh (⭐1)](https://github.com/awkimball/akzsh) - Works best with a dark terminal theme, includes `git` decorations.
*   [al-magic (⭐1)](https://github.com/Alustrat/al-magic/) - Clone of the oh-my-zsh [af-magic (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/af-magic.zsh-theme) theme with the time added at the right of the prompt.
*   [alarangeiras (⭐0)](https://github.com/alarangeiras/alarangeiras-zsh-theme/) - Minimalist theme with `git` status decorations.
*   [ale (⭐3)](https://github.com/alepimentel/ale-zsh) - Based on the fino theme. Includes `git`, `virtualenv` and `node` status decorations.
*   [alesrosina (⭐0)](https://github.com/alesrosina/oh-my-zsh-alesrosina-theme) - Includes decorators for `git` information, current directory and the last command's return status.
*   [alien-minimal (⭐153)](https://github.com/eendroroy/alien-minimal) - Minimalist ZSH theme with `git` status displayed.
*   [alien (⭐329)](https://github.com/eendroroy/alien) - Powerline-esque ZSH theme that shows `git` decorations and the exit code of the last command. Faster than many other prompts because it determines the `git` decorations asynchronously in a background process.
*   [almel (⭐26)](https://github.com/Ryooooooga/almel) - Inspired by [agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme), written in Rust. Includes `git` status, user\@host, last command exit status and working directory decorations
*   [aloy (garethclews) (⭐12)](https://github.com/garethclews/aloy) - Fork of [@elenapan's (⭐3.7k)](https://github.com/elenapan/dotfiles) lena theme. Includes magic enter from subnixr's [minimal (⭐264)](https://github.com/subnixr/minimal) where hitting enter without any further commands prints out some useful `ls`, `git` and current working directory information.
*   [aloy (karetsu) (⭐12)](https://github.com/karetsu/aloy) - Fork of [@elenapan's (⭐3.7k)](https://github.com/elenapan/dotfiles) lena ZSH theme. extended to give a little more information in it. It also includes the 'magic enter' from subnixr's [minimal (⭐264)](https://github.com/subnixr/minimal) where hitting enter without any further commands prints out some useful `ls`, `git` and current working directory information.
*   [alp (⭐0)](https://github.com/zrut747/alp/) - A simple theme with decorations for current directory, root status, username and host.
*   [alpha (⭐1)](https://github.com/Republic-Of-Lunar/alpha-zsh-theme) - Includes decorators for username\@hostname and current directory.
*   [alpharized (⭐11)](https://github.com/NicoSantangelo/Alpharized) - Optimized to work with [solarized](http://ethanschoonover.com/solarized) dark terminals. It's a modified version of the [avit theme (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme).
*   [amoyly (⭐1)](https://github.com/Br1an6/amoyly.zsh-theme) - An elegant and comfortable-reading theme based on [Agnoster](https://gist.github.com/agnoster/3712874).
*   [amplify (⭐0)](https://github.com/clintfoster/ohmyzsh-theme-amplify) - Minimalist, includes AWS Amplify envioronment and `git` status decorations.- [andy (⭐0)](https://github.com/andymcguinness/andys-theme) - Modified [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme with better `git` support.
*   [antoinechab (⭐3)](https://github.com/antoinechab/antoinechab-theme) - Includes `git` status, username, time and current directory decorations.
*   [antsy (⭐5)](https://github.com/jeffmhubbard/antsy-zsh-theme) - Shows `git` branch and status decorations, virtualenv, exit status, jobs count, and vi-mode indicator.
*   [aofxta (⭐0)](https://github.com/aofxta/aofxta.zsh-theme/) - Includes decorators for last command's execution time, `git` information, current directory and current time.
*   [ap2 (⭐0)](https://github.com/aungphyo-dev/ap2.zsh) - Minimalist them with decortators for time, OS, current directory, `git` status and the last command's exit status.
*   [aperiodic (⭐2)](https://github.com/piccobit/aperiodic-zsh-theme) - Shows `git` decorations, user, host, whether root, active Python virtual environment, current Ruby interpreter, visual and numeric status of the last command, power management status and time and date.
*   [aphrodite (⭐158)](https://github.com/win0err/aphrodite-terminal-theme) - Minimalistic theme without visual noise. Displays only the necessary information: current user, hostname, working directory, `git` branch if one exists. Looks great both with dark and white terminals.
*   [aplos (⭐4)](https://github.com/sunquan1991/aplos) - Minimal ZSH prompt with working directory, `git` local info, `git` remote info, time and exit code.
*   [apollo (⭐73)](https://github.com/mjrafferty/apollo-zsh-theme) - A heavily customizable, compatible and performant ZSH theme that uses modules to enable features.
*   [appa (⭐0)](https://github.com/givensuman/appa-zsh-theme) - A tidy little theme based on omz's [refined (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/refined.zsh-theme). Requires a Nerd Font.
*   [apple (aramirol) (⭐1)](https://github.com/aramirol/apple-zsh-custom-themes) - Based on [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme), includes `vcs` status decorations. Colors customizable by setting vars in your `.zshrc`.
*   [apple (bjrowlett2) (⭐0)](https://github.com/bjrowlett2/apple-zsh-theme) - Minimalist theme with `git` status decorations.
*   [arael (⭐0)](https://github.com/aknackd/zsh-themes) - Fork of [gallifrey (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
*   [archcraft (⭐23)](https://github.com/mrx04programmer/ZshTheme-ArchCraft) - Greenish theme, optimized for dark backgrounds. Includes `git` status decorations.
*   [archie (⭐2)](https://github.com/dcavalcante/archie) - Arch Linux inspired ZSH theme. Based on the [norm (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/norm.zsh-theme) theme.
*   [archmocha (⭐1)](https://github.com/mikkurogue/archmocha/) - Some of [catpucchin (⭐7)](https://github.com/JannoTjarks/catppuccin-zsh)'s mocha theming with an Arch Linux twist. Includes decorators for user\@hostname, current directory and `git` status.
*   [arctic-glow (⭐1)](https://github.com/Etto48/arcticglow-zsh-theme) - Based on [agnoster](https://gist.github.com/3712874). Includes decorators for `git` status, python virtual environment, current directory, username  and operating system.
*   [arity (⭐0)](https://github.com/hybras/Arity-Zsh-Theme) - A simple theme designed for readability and to give an overview at a glance. Includes path and `git` decorations.
*   [aronhoyer (⭐0)](https://github.com/aronhoyer/zsh-theme) - Minimalist theme with right-side `git` status decorations.
*   [arrow-minimal (⭐0)](https://github.com/maxim-usikov/arrow-minimal.zsh-theme) - A minimal ZSH theme with `git` decorations.
*   [arrow (⭐0)](https://github.com/milon/arrow-zsh-theme) - Minimal theme, includes `git` status decorations.
*   [asciigit (⭐6)](https://github.com/cemsbr/asciigit) - An ASCII-only theme for `git` users who don't want to use fonts with extra glyphs.
*   [astral (skippyr) (⭐0)](https://github.com/skippyr/astral) - Dual line theme with decorators for user\@hostname, current directory, python virtual environment and `git` information.
*   [astral (xwmx) (⭐17)](https://github.com/xwmx/astral) - Theme for dark backgrounds with zen mode. Works well with the zsh-users [zsh-syntax-highlighting (⭐21k)](https://github.com/zsh-users/zsh-syntax-highlighting) plugin. Includes decorators for execution time of last command, when it was run, its exit status, machine name, current path, `ssh` status, and `git` status.
*   [astro (⭐104)](https://github.com/iplaces/astro-zsh-theme) - Based on the `ys` and [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) themes.
*   [async (⭐4)](https://github.com/mje-nz/zsh-themes) - Shows current directory, `git` state, return value of last command if it had an error code, number of background jobs, execution time of long-running commands, current python virtualenv.
*   [aterminal (⭐37)](https://github.com/guiferpa/aterminal) - Displays Node.js, NPM, Docker, Go, Python, Elixir and Ruby information in the prompt.
*   [aub (⭐2)](https://github.com/FraSharp/aub) - Includes decorations for `git` and `hg` status and `username` at `host`.
*   [australis (⭐0)](https://github.com/Kimitzuni/australis-theme) - Lightweight theme with decorators for `git` information and current directory. Requires `git` plugin from [oh-my-zsh](https://github.com/ohmyzsh).
*   [avil (⭐0)](https://github.com/avil13/avil-zsh-theme) - Minimalist theme with `git` decorations.
*   [avit-d2k (⭐13)](https://github.com/fdaciuk/avit-da2k) - Based on the oh-my-zsh [avit (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) theme, with small changes.
*   [avit-mod (⭐0)](https://github.com/zlsun/avit-mod) - Modified version of oh-my-zsh's [avit (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) theme.
*   [avoleo (⭐1)](https://github.com/flameleo11/avoleo-zsh-theme) - Features a date and time prompt for each command, as well as a command number in history. In addition, it uses special symbols '⠾' and '⡶' to display `git` information if applicable in the current path. It also supports custom colors based on the Gnome-Terminal default color palette.
*   [aws (⭐1)](https://github.com/chiemerieezechukwu/aws-zsh-theme) - Based on [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell), with an extra decorator to show your `$AWS_PROFILE` when it is set.
*   [backbone (⭐2)](https://github.com/42LM/backbone-zsh-prompt) - A bare minimum single file prompt, fast as a roadrunner MEEP! MEEP. Includes `git` status and current directory decorations.
*   [baddcafe (⭐2)](https://github.com/dimgatz98/Baddcafe_zsh_theme) - Provides dynamic system information. Includes decorators for `git` status, cpu usage, memory usage, battery level, local and global IP addresses, current time, current directory and the exit status of the last command run.
*   [bahman (⭐1)](https://github.com/bahmanworld/bahman-zsh-theme) - Requires Nerd Font. Has `git` status decorator.
*   [banana (⭐6)](https://github.com/sorcererxw/banana-zsh-theme) - Includes `git` status decorations and current directory.
*   [bandit (⭐3)](https://github.com/Holger-Will/zsh_bandit) - Another Powerline variant.
*   [bar (anki-code) (⭐2)](https://github.com/anki-code/shell-prompt-theme-bar) - Minimalist settings for [p10k (⭐49k)](https://github.com/romkatv/powerlevel10k).
*   [bar (xp-bar) (⭐3)](https://github.com/xp-bar/zsh-bar-theme) - Includes username, host, pwd, `git` status decorations and  3x hour reminders to drink water.
*   [barion (⭐1)](https://github.com/SEbbaDK/barion) - A fast compiled prompt with a compact `git` status overview. Reminiscent of powerline. Requires [Crystal](https://crystal-lang.org/) to build.
*   [bash (⭐0)](https://github.com/starseekist/bash-zsh-theme) - Looks like the default `bash` prompt.
*   [bashi (⭐5)](https://github.com/eli-oat/bashi) - Optimized for Ahmet Sülek's [Flat UI Terminal (⭐624)](https://github.com/ahmetsulek/flat-terminal) theme and Pasquale D'Silva's [Saturn Terminal (⭐73)](https://github.com/psql/saturn-colors) theme.
*   [bashlover (⭐3)](https://github.com/Vu0811/bashlover) - Designed for those who appreciate the powerful features of ZSH shell but still prefer a simple, classic interface similar to the `bash` shell. Includes decorators for `git` information, user\@host and the current working directory
*   [bashplus (⭐0)](https://github.com/Elagoht/BashPlusZshTheme) - Colorized replica of the default `bash` prompt with decorators for `virtualenv` and `git` status.
*   [bastard (⭐2)](https://github.com/jsundqvist/bastard.zsh-theme) - Modified version of [gitster (⭐6)](https://github.com/zimfw/gitster) theme for [ZIM (⭐4.1k)](https://github.com/zimfw/zimfw).
*   [bearable (⭐1)](https://github.com/JanmanX/bearable-zsh) - Works well with dark terminal backgrounds.
*   [bearings (⭐199)](https://github.com/liamg/bearings) - A fast, clean, super-customizable shell prompt. Includes decorators for current directory, `git` status, exit code of last command, duration of last command, background jobs & username.
*   [bedbugs (⭐0)](https://github.com/justino/zsh-theme-bedbugs) - Inspired by [Agnoster](https://gist.github.com/agnoster/3712874), this multiline prompt includes decorators for `git` status information, background job count, working directory, user and hostname, Python virtualenv when present, colored return value of last command and root/user sigil.
*   [beer (⭐3)](https://github.com/tcnksm/oh-my-zsh-beer-theme) - Inspired by [cloud (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme), but with beer icons.
*   [bender (⭐9)](https://github.com/specious/bender) - Fancy two-line prompt with git integration.
*   [berghain (⭐1)](https://github.com/meshkinyar/berghain.zsh-theme) - Minimalist theme. Includes decorators for the exit code of the last command run and for `git` status.
*   [bernkastel (⭐1)](https://github.com/JamesLaverack/bernkastel) - Based on [ys (⭐178k)](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme). Includes decorations for kubernetes context, current directory, last command exit status and `git` status.
*   [bgnoster (⭐0)](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with unicode symbols baked in.
*   [bigshrimp (⭐2)](https://github.com/taksyon/BigShrimp-zsh-theme) - A clear and concise theme that includes decorators for username\@host, current directory and `git` status.
*   [bigyls (⭐3)](https://github.com/Bigyls/Bigyls-zsh-theme) - Based on [lpha3cho (⭐44)](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters). Includes decorators for date, time, IP address, `git` status, plugins and current directory.
*   [bira (⭐2)](https://github.com/zimfw/bira) - Fork of Oh-My-ZSH [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme. Includes decorators for working directory, username\@host, `git` status information, Python [venv](https://docs.python.org/3/library/venv.html) and a status code when the last command had an error.
*   [birame (⭐4)](https://github.com/maniat1k/birame) - Based on [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
*   [biraskull (⭐0)](https://github.com/Shahryar-Pirooz/biraSkull.zsh-theme) - Based on [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), includes root status and `git` status decorations.
*   [biratime (⭐3)](https://github.com/vemonet/biratime) - Based on the [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme, but displays the date instead of the username in the prompt.
*   [birav2 (⭐1)](https://github.com/shahid64/birav2-theme) - Based on [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme). Includes `git`, `rvm` and `virtualenv` status decorations.
*   [black-Void (⭐349)](https://github.com/black7375/BlaCk-Void-Zsh) - Includes account info, root user, using ssh, directory lotation, write permission, and vcs info decorations.
*   [blackrain (⭐6)](https://github.com/ginfuru/zsh-blackrain) - Another `git`-aware theme.
*   [blaze (⭐31)](https://github.com/danieltodor/blaze) - Visually similar to powerline. Requires `make` and `g++`. Works best with your terminal set to use a nerd font. Includes decorators for current directory, execution time of last command, exit status of last command, `git` status information, date, time, username and host. Can be extended with custom segments.
*   [blazux (⭐2)](https://github.com/blazux/omz-theme) - Includes `git` status decoration and a smiley/sad face indicator of the last command's exit status.
*   [blinks (max13ft) (⭐0)](https://github.com/max13fr/blinks.zsh-theme) - Adds mercurial support to oh-my-zsh's [blink (⭐0)](https://github.com/max13fr/blinks.zsh-theme) theme.
*   [blinks-xfan (⭐1)](https://github.com/ixfan/blinks-xfan) - Based on the existing theme [blinks (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme).
*   [bliss (⭐24)](https://github.com/joshjon/bliss-zsh) - A delicate theme that injects color without overwhelming your workspace. Designed to be used with the [bliss iTerm (⭐15)](https://github.com/joshjon/bliss-iterm) color scheme and [bliss dircolors (⭐70)](https://github.com/joshjon/bliss-dircolors). Includes `git` status decorations.
*   [blokkzh (⭐5)](https://github.com/KorvinSilver/blokkzh) - Theme based on oh-my-zsh's built in [gnzh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) theme. Requires a font with unicode support.
*   [blox (⭐60)](https://github.com/yardnsm/blox-zsh-theme) - A minimal and fast ZSH theme that shows you what you need. It consists of blocks: each block is shown inside a pair of \[square brackets], and you can add blocks by simply creating a function.
*   [bluehigh (⭐2)](https://github.com/hiroppy/bluehigh.zsh-theme) - Minimal theme, displays `git` information.
*   [bluelines (⭐2)](https://github.com/apbarrero/bluelines) - Clear and blue theme.
*   [bluo (⭐2)](https://github.com/varunpbardwaj/bluo) - Colorful prompt segments reminiscent of [bullet-train (⭐2.8k)](https://github.com/caiogondim/bullet-train.zsh) or [powerlevel10k (⭐49k)](https://github.com/romkatv/powerlevel10k). Includes `git` status decorations.
*   [boban (⭐1)](https://github.com/TheEdgeOfRage/boban-zsh) - A powerline-style file based on [Agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme). Includes decorators for user\@hostname, `git` status, current working directory, python venv, AWS profile, `$KUBECONFIG`, the terraform workspace and the exit status of the last command run. Requires a Nerd Font for symbols to render properly.
*   [bogo (⭐0)](https://github.com/cubasepp/zsh-bogo-theme) - Inspired by [zeta (⭐230)](https://github.com/skylerlee/zeta-zsh-theme). Includes `git` and ruby version decorations.
*   [boom (⭐3)](https://github.com/the0neWhoKnocks/zsh-theme-boom) - Multiline theme, best on dark backgrounds.
*   [born-in-the-purple (⭐1)](https://github.com/LeonardMH/born-in-the-purple) - Simple theme with a purple motif. Inspired by [Pure (⭐14k)](https://github.com/sindresorhus/pure).
*   [bouni (⭐0)](https://github.com/Bouni/bouni-zsh-theme) - Includes decorators for user\@host, current directory, active python virtualenv, and `git` status.
*   [boxy (⭐0)](https://github.com/evil-tim/boxy-zsh-theme) - Works well with solarized terminal colors. Includes decorators for `username@hostname`, current directory, `git` status, return code for last command, and time last command was run.
*   [braundo (⭐1)](https://github.com/Braundo/braundo-zsh-theme) - Straightforward theme with username, current directory, `git` status, and timestamp.
*   [bref (⭐3)](https://github.com/mpostaire/bref-zsh-prompt) - A simple prompt. It includes decorators to display `git` status asynchronously, a notification if the `ssh` session is remote, the battery level and the number of background jobs.
*   [brisa (⭐2)](https://github.com/ambrisolla/oh-my-zsh-brisa-theme) - Multiline theme based on [fino-time (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fino-time.zsh-theme). Includes decorations for username, host, current directory, and `git` status.
*   [bronze (⭐50)](https://github.com/reujab/bronze) - A cross-shell customizable powerline-like prompt with icons written in go. Requires [nerd-fonts (⭐57k)](https://github.com/ryanoasis/nerd-fonts).
*   [brs (⭐3)](https://github.com/evenhold/brs-zsh-theme) - Displays the current song in the prompt with `audtool`.
*   [bruh (⭐11)](https://github.com/haze/bruh) - Includes `git` status decorations.
*   [brunty (⭐4)](https://github.com/Brunty/omz-brunty) - Includes `git` status decorations.
*   [bryce-robbyrussell (⭐0)](https://github.com/Bryan-Cee/bryce-robbyrussell) - Inspired by the [powerline (⭐2.9k)](https://github.com/Lokaltog/vim-powerline) and [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) themes.
*   [bttf-color (⭐1)](https://github.com/yasuhiroki/bttf-color-zsh) - BTTF color theme. Includes `git` status decorations.
*   [bubblegum (⭐15)](https://github.com/ice-bear-forever/bubblegum-zsh) - Minimalist bright pink theme with a triangular glyph and your working directory, nothing else—leaving you with the cleanest shell possible.
*   [bubblified (hohmannr) (⭐75)](https://github.com/hohmannr/bubblified) - Inspired by [agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme). Works best with [nerdfonts (⭐57k)](https://github.com/ryanoasis/nerd-fonts).
*   [bubblified (varaki) (⭐0)](https://github.com/varaki/bubblified-varaki.zsh-theme) - Based on [bubblified (hohmannr) (⭐75)](https://github.com/hohmannr/bubblified). Changes color when root. Includes decorators to show user\@host and current directory.
*   [buddha (⭐0)](https://github.com/BuddhaDom/zsh-buddha) - Includes decorators for `git` status, current directory, exit status of last command run and username\@hostname.
*   [bullet-train (⭐2.8k)](https://github.com/caiogondim/bullet-train.zsh) - Inspired by the Powerline Vim plugin. It aims for simplicity, showing information only when it's relevant.
*   [bunnyruni.min (⭐1)](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni (⭐14)](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH theme, modified to just display time and directory.
*   [bunnyruni (⭐14)](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - Simple, clean, and beautiful theme.
*   [bureau-env (⭐1)](https://github.com/angus-lherrou/bureau-env) - Modification of the Oh-My-Zsh [Bureau (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bureau.zsh-theme) theme that adds a Python virtual environment label to the left of the `git` block.
*   [bureau-parrot (⭐1)](https://github.com/BenjaminGuzman/bureau-parrot) - Based on [bureau (⭐178k)](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bureau.zsh-theme). Includes `git` decorations.
*   [bureau (⭐39)](https://github.com/isqua/bureau) - A clear and informative two-lined prompt. Includes `git` status optimized for large repositories.
*   [burn (⭐1)](https://github.com/Xatra1/burn) - Includes decorators for user\@hostname and current directory.
*   [buster (⭐3)](https://github.com/grantbuster/buster_zsh_theme) - Plays well with WSL2. Based loosely on Fox and Jonathan themes from oh-my-zsh.
*   [cabovianco (⭐0)](https://github.com/cabovianco/cabovianco-zsh-theme) - Includes decorators for `git` status and current directory.
*   [cactus (⭐4)](https://github.com/welksonramos/cactus) - Minimalist theme with `git` status decorations.
*   [cafeconbits (⭐1)](https://github.com/ricard-ferrero/cafeconbits-zsh-theme) - Simple theme with a coffee cup icon. Includes decorators for `git` status, current directory and the exit status of the last command.
*   [calma (⭐3)](https://github.com/luislve17/calma) - Minimalist theme that works well on dark backgrounds. Includes decorators for truncated current directory, `git` information, time, and for the exit status of last command.
*   [candy-fantasy (⭐0)](https://github.com/fffelix-huang/candy-fantasy) - Modified version of [Candy Kingdowm (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/candy-kingdom.zsh-theme)theme.
*   [candy-light (⭐2)](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) - Light version of the candy theme.
*   [capsule (⭐6)](https://github.com/42LM/capsule) - A simple single file terminal prompt that is completely customizable. Display is divided into capsules (`TIMER` > `DIR` > `GIT` > `GIT ACTION`).
*   [carriage-return (⭐0)](https://github.com/treyssatvincent/carriage-return.zsh-theme) - omz's [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) with an added carriage return.
*   [catpuccin-kali (⭐0)](https://github.com/Robinx0/catpuccin-kali-theme.zsh-theme) - Inspired by oh-my-posh catpuccin theme. Includes decorators for username\@hostname, current directory and `git` status.
*   [catpuccin (⭐7)](https://github.com/JannoTjarks/catppuccin-zsh) - Minimalist theme. Includes decorators for current directory, exit status of last command and `git` status.
*   [cayun (⭐38)](https://github.com/comeacrossyun/ys-cayun.zsh-theme) - Shows active Python version and `git` decorations in the prompt.
*   [celestialorb (⭐1)](https://github.com/celestialorb/zsh-theme) - Powerline-inspired theme by @celestialorb. Includes `git` status decorations, Kubernetes cluster information (if any), current AWS profile and region, and  active virtualenv.
*   [cezhanne (⭐0)](https://github.com/gambardellawill/cezshanne) - Minimalist ZSH theme with `git` status decorators. Requires a [Nerd Font](https://www.nerdfonts.com).
*   [cf-ps1 (⭐0)](https://github.com/mdan16/cf-ps1) - Displays the current foundation and organization and space of [Cloud Foundry](https://www.cloudfoundry.org/) in your prompt.
*   [ch4rli3 (⭐0)](https://github.com/ch4rli3kop/ch4rli3.zsh-theme) - Lean and simple theme.
*   [chaffee (⭐5)](https://github.com/jasonchaffee/chaffee.zsh-theme) - Based on sorin. Shows the current active versions of Java, Scala, Go, Node, Python and Ruby.
*   [chaos (⭐1)](https://github.com/kusamaxi/chaos-zsh) - Inspired by dogenpunk and smt themes, optimized for `git` users and Python developers. Includes decorators for `git` status, python virtual environment, background jobs, error status of last command, user\@hostname and current directory. Requires a font with emoji.
*   [chaotic-beef (⭐1)](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme) - A tiny and beautiful theme for Oh-My-Zsh without anything superfluous. Includes `git` status decorations.
*   [charged (⭐6)](https://github.com/robwierzbowski/charged-zsh-theme) - A ZSH prompt optimized for the [solarized (⭐16k)](https://github.com/altercation/solarized) dark terminal theme.
*   [checkmate (⭐1)](https://github.com/skippyr/checkmate) - Decorated with chess pieces. Includes decorators for python venv, current directory, `git` status and whether you're running as root. Requires a Nerd Font.
*   [cheeky (⭐0)](https://github.com/kampanosg/zsh-cheeky-prompt) - Includes chicken emoji, decorators for current directory, `git` information and current GCP cluster and project.
*   [chello (⭐1)](https://github.com/Abdalla981/chello) - Works well on dark backgrounds. Depends on [autojump (⭐17k)](https://github.com/wting/autojump), [zsh-autosuggestions (⭐33k)](https://github.com/zsh-users/zsh-autosuggestions) and [zsh-syntax-highlighting (⭐21k)](https://github.com/zsh-users/zsh-syntax-highlighting).
*   [chi (⭐6)](https://github.com/akinjide/chi) - A ZSH theme optimized for iTerm 2 users on macOS.
*   [chill (⭐6)](https://github.com/JKerboeuf/chill.zsh-theme) - Has decorations for the current working directory, last command exit status and `git` status.
*   [chinatown (⭐2)](https://github.com/skippyr/chinatown) - Powerline-esque theme with decorators for the exit status of the last command run, user\@hostname, virtual environments and current directory. Requires a nerdfont font.
*   [chinipage (⭐1)](https://github.com/andresemartinez/chinipage-zsh-theme) - Minimalist theme that includes `git` decorations. Requires powerline-compatible fonts and the [git-prompt (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git-prompt) plugin.
*   [chrisandrew.cl (⭐3)](https://github.com/chrisandrewcl/chrisandrew.cl.zsh-theme) - Includes `git` decorations. Requires a powerline-compatible terminal font.
*   [cinnabar (⭐2)](https://github.com/nvillapiano/zsh-theme---cinnabar) - Shows timestamp, large line breaks, git branch and status.
*   [clarity (⭐6)](https://github.com/nbitmage/clarity.zsh) - Designed for for simpleness and extensibility.
*   [classic (⭐1)](https://github.com/freakinu/classic-zsh-theme) - A classic unix theme with decorators for username, host, current directory and `git` status.
*   [classyTouch (⭐53)](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - Minimal, clean theme with `git` support.
*   [classyTouchName (⭐1)](https://github.com/dylanroman03/classyTouchName) - Inspired by [classyTouch (⭐53)](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh). Works better with dark backgrounds. Includes `git` status decorations.
*   [clean (akz92) (⭐9)](https://github.com/akz92/clean) - Minimalist ZSH theme.
*   [clean (brandonRoehl) (⭐30)](https://github.com/BrandonRoehl/zsh-clean) - A minimalist variant of [pure (⭐14k)](https://github.com/sindresorhus/pure). Pure is not clean, clean is not pure.
*   [clean (patr1ot) (⭐0)](https://github.com/Patr1ot/clean.zsh-theme) - Fork of the upstream [clean (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#clean) with host information added.
*   [cleansh (⭐3)](https://github.com/diegoos/cleansh) - Minimalist, includes `git`, Ruby, node and Python version status decorations. Works with standard fonts.
*   [clearance (⭐2)](https://github.com/H00N24/clearance-theme-oh-my-zsh) - minimalist theme with `git`, nix-shell and virtualenv status decorations.
*   [clipper (⭐0)](https://github.com/Robert-96/clipper) - Minimalist ZSH theme with `git` support. It includes decorations for pwd, last command exit status code and `git` status & branch.
*   [cloudy (⭐29)](https://github.com/Huvik/Cloudy) - Minimal cloudy ZSH theme.
*   [clover (⭐4)](https://github.com/tzing/clover.zsh-theme) - Inspired by [zeta (⭐230)](https://github.com/skylerlee/zeta-zsh-theme) and [pure (⭐14k)](https://github.com/sindresorhus/pure).
*   [club-house (⭐0)](https://github.com/skippyr/club-house) - Requires a [Nerd Font (⭐57k)](https://github.com/ryanoasis/nerd-fonts). Has decorators for username, hostname, python virtual environment, current working directory, `git` status information and the exit code of the last command run.
*   [cmder-wsl (⭐0)](https://github.com/szyminson/cmder-wsl-zsh) - Configuration file for `cmder`that is configured to work in quake mode with ZSH and a modified [Agnoster](https://gist.github.com/agnoster/3712874) theme.
*   [cmder (⭐13)](https://github.com/potasiyam/cmder-zsh-theme) - A ZSH theme that matches the theme of Cmder, a popular terminal emulator for windows. Includes `node` and `git` status decorations.
*   [cn (⭐0)](https://github.com/shinqcn/cn-zsh/) - Includes `username`, `directory` and `git` status decorations.
*   [cobalt2 (⭐1.2k)](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos' Cobalt 2 theme for ZSH and iTerm 2.
*   [cobalt2git (⭐5)](https://github.com/alexeimun/cobalt2git) - Cobalt 2 theme with `git` extensions.
*   [codemachine (⭐6)](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Displays decorators for `git` info, whether you're logged in via `ssh`, and the return code of last command.
*   [coffeenostor (⭐1)](https://github.com/CoffeeVector/coffeenostor-zsh-theme) - Based on [agnoster](https://gist.github.com/3712874), with a right-prompt for vi-mode that displays `--INSERT--` and `--NORMAL--`, in a powerline look.
*   [coldark (⭐1)](https://github.com/ArmandPhilippot/coldark-zsh-theme) - A blue-grey theme designed for reading comfort. Includes `git` decorations.
*   [collon (⭐6)](https://github.com/lambdalisue/collon.zsh) - Lightweight theme with `git` status decorations, cwd, time, host, exit status of last command. Does not require special fonts.
*   [colorbira (⭐0)](https://github.com/CristianCantoro/colorbira-zsh-theme) - Allows per-host prompt coloring, displays `rvm`, `virtualenv` and `git` information.
*   [common (⭐363)](https://github.com/jackharrisonsherlock/common) - A simple, clean and minimal prompt, displays current working directory, hostname, AWS vault role, background jobs, current SHA, exit code of last command, and `git` branch and status.
*   [comxtohr (⭐3)](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) - Brightly colored theme optimized for dark backgrounds.
*   [coolmelon (⭐1)](https://github.com/omkarpai/coolmelon-zsh-theme/) - Includes decorators for user\@host, time, current directory, node version and `git` information.
*   [cordial (⭐20)](https://github.com/stevelacy/cordial-zsh-theme) - Clean and effective ZSH theme with git and npm support.
*   [cr (⭐1)](https://github.com/cruzrovira/cr-zsh-theme) - Includes directory, time, host name, last command exit status, and `git` status decorations.
*   [cramin (⭐6)](https://github.com/FelipeCRamos/craminzsh) - Minimal interface with support for GitHub plugins, based on [hyperzsh (⭐533)](https://github.com/tylerreckart/hyperzsh).
*   [cravend (⭐0)](https://github.com/cravend/theme) - Includes `hostname` decorator (only in active `ssh` sessions) and `git` status decorations.
*   [crème fraîche (⭐3)](https://github.com/koenwoortman/creme-fraiche-zsh-theme) - Works best with light terminal backgrounds, includes `git` and `vi`-mode status decorations.
*   [croque (⭐9)](https://github.com/Ryooooooga/croque) - Powerline-inspired theme with decorators for OS, user\@host, `git` information, `git` username, current directory and exit status of last command.
*   [cryo-long (⭐0)](https://github.com/cryocaustik/cryo-long-zsh-theme) - Variant of [cryo (⭐1)](https://github.com/cryocaustik/cryo-zsh-theme/) with added decorators for hostname and current directory.
*   [cryo (⭐1)](https://github.com/cryocaustik/cryo-zsh-theme) - A standalone clone of the original oh-my-zsh theme with date and time added.
*   [cryptic (⭐0)](https://github.com/thederpykrafter/cryptic.zsh-theme) - Based on [aphrodite-terminal-theme (⭐158)](https://github.com/win0err/aphrodite-terminal-theme). Includes decorators for current directory, `git` status, time, username, hostname and virtual environment.
*   [cute (⭐32)](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - A macOS oh-my-zsh shell theme with cute emoji based on the Powerline Vim plugin.
*   [cxzh (⭐0)](https://github.com/MakeWorkSimple/cxzh.zsh-theme) - Works well on dark background, has `git` status decorations.
*   [cybensis (⭐0)](https://github.com/cybensis/cybensis-zsh-theme) - Based on [af-magic (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/af-magic.zsh-theme). Includes decorators for `git` information, `hg` information, and python virtualenv.
*   [cypher-ruby (⭐1)](https://github.com/ston1x/cypher-ruby) - Similar to [cypher (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cypher.zsh-theme) but includes the active Ruby version.
*   [czsh (⭐3)](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) with [oh-my-zsh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh) and the [agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme) theme in a container.
*   [daily-emoji (⭐1)](https://github.com/huytran-wq/zsh-daily-emoji-theme/) - Shows random emoji at the beginning of each command depending on the day of the week.
*   [daily (⭐0)](https://github.com/ghlin/zsh-theme-daily) - Includes `git` and `ssh` status decorations.
*   [daivasmara (⭐84)](https://github.com/Daivasmara/daivasmara.zsh-theme) - Chill theme with decorators for current directory (truncated if necessary) and `git` information, including time since last commit.
*   [dalailahner (⭐0)](https://github.com/dalailahner/dalailahner.zsh-theme) - Minimalist theme with decorators for `git` status, username and current directory. Based on Steve Losh's [Prose (⭐351)](https://github.com/sjl/oh-my-zsh/blob/master/themes/prose.zsh-theme) theme.
*   [damino (⭐0)](https://github.com/njdom24/Damino-Zsh-Theme) - Minimal powerline-esque theme with `git` decorations.
*   [dangerroom (⭐1)](https://github.com/abbreviatedman/dangerroom) - Informative, minimal, and, above all, X-Men themed. Includes decorators for `git` status, working directory, parent directory and `vim` mode.
*   [dango (⭐3)](https://github.com/ann-kilzer/annkilzer.zsh-theme) - Includes decorations for current directory and `git` status.
*   [danielparks (⭐1)](https://github.com/danielparks/danielparks-zsh-theme) - Works well on dark backgrounds. Includes decorators for `git` status, user\@host when in an `ssh` session, success/failure of last command, working directory, python virtualenv, execution time of last command and whether running as `root`.
*   [daniloheraclio (⭐0)](https://github.com/daniloheraclio/daniloheraclio-zsh-theme) - Inspired by the [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme. Has `git` and last command exit status decorations. Requires a nerdfont to render properly.
*   [dark-modern (⭐1)](https://github.com/d-exclaimation/vscode-dark-modern.zsh-theme) - Includes decorators for `git` status and current directory.
*   [darkblood-modular (⭐1)](https://github.com/InAnimaTe/darkblood-modular) - This version of the popular [darkblood (⭐1)](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) theme has been enhanced with a near complete rewrite enabling modularity and a few new features.
*   [darksoku (⭐1)](https://github.com/TooSchoolForCool/darksoku-zsh-theme) - Based on the `ys` and [astro (⭐104)](https://github.com/iplaces/astro-zsh-theme) themes.
*   [dbern (⭐0)](https://github.com/dbernhard-0x7CD/zsh-dbern-theme) - Includes battery status and load average decorations.
*   [delta (asavoy) (⭐3)](https://github.com/asavoy/delta-zsh-theme) - Minimal ZSH theme to reduce distractions. Includes an iTerm color settings file.
*   [delta (dongri) (⭐0)](https://github.com/dongri/delta-zsh-theme) - Another minimal theme with embedded `git` status.
*   [delta-prompt (⭐10)](https://github.com/cusxio/delta-prompt) - A minimal ZSH prompt.
*   [devil-puppet (⭐0)](https://github.com/skippyr/devil-puppet) - Theme decorated by a pentagram. Has decorators for username, hostname, python virtual environment, current working directory, `git` status information and the exit code of the last command run.
*   [devj121 (⭐0)](https://github.com/cjeonguk/devj121-zsh-theme) - Includes `git` decorations with branch glyphs.
*   [dexter (⭐2)](https://github.com/shvenkat/zsh-theme-dexter) - A theme with an emphasis on the right side (hence the name) of the terminal.
*   [dfrx (⭐7)](https://github.com/Dofoerix/Dfrx-Prompt-Theme) - Oh-My-Posh theme. Includes decorators for current directory, execution time of last command, root status, and the time.
*   [dino (⭐7)](https://github.com/OdilonDamasceno/dino-zsh-theme) - Includes decorations for node, golang, flutter, lua, python & java, also includes `git` decorations. Requires nerdfonts.
*   [dissonance (⭐4)](https://github.com/RyanScottLewis/theme-dissonance-zsh) - Comes with custom `LSCOLORS` and `LS_COLORS` settings files, works with both dark and light terminal themes.
*   [diy-ys (⭐1)](https://github.com/aprilnops/zsh-theme) - Variant of [ys (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) without hostname or time.
*   [djkakaroto (⭐0)](https://github.com/djkakaroto/theme-zsh/) - Includes `git` status decorations, works with all fonts.
*   [dkniffin (⭐1)](https://github.com/dkniffin/zsh-theme) - Includes `ruby` version and `git` status.
*   [dmx (⭐1)](https://github.com/domix/dmx.zsh-theme) - Optimized for dark terminal windows.
*   [do-you-even-nix (⭐2)](https://github.com/miche1e/do-you-even-nix) - Simple powerline-esque theme designed to increase [nix](https://nixos.org) power. Includes decorators for username\@hostname, current directory, `git` status, whether you're in a nix shell, and whether there is a flake.nix or shell.nix file in the current directory.
*   [domixgit (⭐0)](https://github.com/tariqdomi/ohmyzsh-domixgit) - Prompt with `git` status and current directory decorators.
*   [doodleshell (⭐3)](https://github.com/cdodd/doodleshell-zsh-theme) - Minimalist theme, includes `git`, `terraform` and `aws` status decorations.
*   [doom (⭐5)](https://github.com/CMOISDEAD/doom-zsh) - Doom-inspired. Looks similar to powerline. Has customizable segments, decorators for `git` status, `rust`, `Node.js`, `python` and `ruby` versions.
*   [dp (⭐1)](https://github.com/davidparsson/zsh-dp-theme) - Low contrast theme that shows current git branch, if the repository is dirty and the value of `$PYENV_VERSION`.
*   [dr4kk0nnys\_v2 (⭐0)](https://github.com/Dr4kk0nnys/Dr4kk0nnys_theme_ohmyzsh_v2/) - Works well on dark backgrounds, includes `git` status decorations.
*   [dracula (⭐279)](https://github.com/dracula/zsh) - A dark theme for Atom, Alfred, Chrome DevTools, iTerm 2, Sublime Text, Textmate, Terminal.app, Vim, Xcode, and ZSH.
*   [dragon (jeop10) (⭐1)](https://github.com/jeop10/dragon) - Inspired by kali linux. Includes `git` status and working directory decorations.
*   [dragon (sabertaximi) (⭐13)](https://github.com/sabertazimi/dragon-zsh-theme) - Minimalistic, includes `git` status information.
*   [drkat (⭐3)](https://github.com/katrinaalaimo/drkat-zsh-theme) - Reminiscent of [Powerline (⭐15k)](https://github.com/powerline/powerline). Includes directory, `git` status, and hostname decorations.
*   [droolmaw (⭐0)](https://github.com/isuke/droolmaw) - Configurable prompt that resembles [Powerline (⭐15k)](https://github.com/powerline/powerline). Requires a Nerd font. Includes decorators for username, current directory, current directory path, datetime, `git` author, `git` status, `mise` language version and a configurable message based on the exit status of the last command run.
*   [droolscar (⭐5)](https://github.com/isuke/droolscar) - [Powerline (⭐15k)](https://github.com/powerline/powerline) variant.
*   [dtheme (⭐3)](https://github.com/OlukaDenis/DTheme) - Optimized for people using a solarized terminal color scheme and `git`. Works best with a unicode font.
*   [duckster (⭐5)](https://github.com/ducky/duckster) - A fork of the [gitster (⭐67)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) ZSH theme that's more ducky fresh.
*   [ducula (⭐46)](https://github.com/janjoswig/Ducula) - Inspired by Dracula project. Includes `git` status decorations, username and hostname abbreviations, virtual environment, current working directory, return status of last command and the time.
*   [dustmod (⭐1)](https://github.com/bmihaila/dustmod) - Derived from the [dst (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dst.zsh-theme) theme in oh-my-zsh.
*   [dyzsh (⭐0)](https://github.com/daotoyi/dyzsh-zsh-theme) - Based on [astro (⭐104)](https://github.com/iplaces/astro-zsh-theme). Includes decorators for `git` branch & hash, current directory, user, host & time.
*   [earthshaker (⭐1)](https://github.com/remusearthshaker/earthshaker.zsh) - A minimalist, earthy ZSH theme designed for developers who prefer warmth, subtle power, and a grounded aesthetic. Includes decorators for current directory, `git` status and username\@hostname.
*   [easytocloud (⭐0)](https://github.com/easytocloud/oh-my-easytocloud) - Based on [agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme). Includes decorators for AWS environment, `git` status, username and the current directory.
*   [eckig (⭐0)](https://github.com/fouladi/eckig) - Minimalist theme with utf-8 icons. Includes `git` status decorations and a clock.
*   [efritas (⭐4)](https://github.com/erikfritas/efritas) - Includes username, hostname, `venv`, `rvm` and `git` status decorations.
*   [eggshausted (⭐1)](https://github.com/inutano/eggshausted) - A `git`-aware theme for people who are tired of getting errors.
*   [elagoht (⭐0)](https://github.com/Elagoht/Elagoht.zsh-theme) - Includes decorators for user\@hostname, current directory, virtual environment, `git` status, whether it is running in an `ssh` session, and the execution time of the last command.
*   [elessar (⭐22)](https://github.com/fjpalacios/elessar-theme) - A `git`-aware theme based on [gitster (⭐67)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme). Requires a Powerline-compatible font.
*   [elm (⭐1)](https://github.com/gacallea/elm-zsh-theme) - Includes `git` status, user\@host, date, time and path decorators.
*   [elsa (⭐7)](https://github.com/faycito/elsa) - Includes root status, pwd and `git` status decorations.
*   [emojeer (⭐0)](https://github.com/lxynox/emojeer-ohmyzsh) - Emoji flavored [oh-my-zsh](https://ohmyz.sh/) theme.
*   [emoji (⭐20)](https://github.com/meiokubo-zz/emoji.zsh-theme) - Based on the [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh theme with the `git` prompt symbols replaced with emoji for better clarity.
*   [emojirussell (⭐1)](https://github.com/Bergiu/emojirussell) - Based on [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh theme, with status decorations for current working directory, last command exit status, `git` branch and status.
*   [endless-dog (⭐4)](https://github.com/qwelyt/endless-dog) - oh-my-zsh-compatible theme that mimics grml-zsh-config.
*   [enlightenment (⭐6)](https://github.com/w33tmaricich/enlightenment) - Includes decorations for `git` status, `vi`-mode indicator, and the time for last command to execute.
*   [enormous (⭐1)](https://github.com/leighmcculloch/zsh-theme-enormous) - Takes up an enormous amount of space in the terminal.
*   [erfan (⭐2)](https://github.com/ekm507/erfan-zsh-theme) - Combination of the of [af-magic (⭐7)](https://github.com/andyfleming/oh-my-zsh) and [macovsky (⭐19)](https://github.com/championswimmer/oh-my-zsh/blob/master/themes/macovsky.zsh-theme) themes. Includes `git` and `virtualenv` status decorations.
*   [eriner (⭐22)](https://github.com/zimfw/eriner) - A Zim fork of the Powerline-inspired [agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme) prompt theme. Includes `git` status decorations.
*   [escape (⭐2)](https://github.com/fesmjke/escape/) - Includes decorators for `git` information, username, time, current directory and last command exit status.
*   [eubw (⭐0)](https://github.com/eptaccio/eubw-oh-my-zsh-theme) - A simple theme with `git` information.
*   [eucalyptus (⭐2)](https://github.com/relastle/eucalyptus) - Simple one-line theme for minimalist vi-mode users inspired by [agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme) and [powerlevel9k (⭐13k)](https://github.com/bhilburn/powerlevel9k). Includes `git` status indicator, `vi`-mode indicator, current directory and current path.
*   [even-more-emojis (⭐0)](https://github.com/odunlop/even-more-emojis) - Customized version of [emoji (⭐20)](https://github.com/meiokubo-zz/emoji.zsh-theme) which adds more emojis and more information. Includes decorators for `git` status, current directory and the exit status of last command.
*   [excess (⭐4)](https://github.com/davydovanton/excess.zsh-theme) - Simple ZSH color theme.
*   [ez-pz (⭐1)](https://github.com/mangosmoothie/ez-pz) - Minimalist theme with `git` status decorations, inspired by [bureau (⭐39)](https://github.com/isqua/bureau).
*   [fall (⭐28)](https://github.com/jottenlips/seasonal-zshthemes) - Minimalist theme with fall icons. Includes `git` status decorations.
*   [fattyarrow (⭐0)](https://github.com/sohnryang/fattyarrow) - Minimal ZSH prompt that works better on dark backgrounds.
*   [fbi (⭐0)](https://github.com/bateman/fbi-zsh-theme) - Powerline-inspired fork of [Bureau (⭐39)](https://github.com/isqua/bureau) with decorators for `nvm` environment, `git` status, username\@hostname and current directory.
*   [fdT2K (⭐0)](https://github.com/FDT2k/FDT2K-theme)- Based on [agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme), preset to include virtualenv, last command status, `nvm`, `docker machine` and `git`, `hg` and `bzr` status decorations.
*   [fe80 (⭐0)](https://github.com/fe80/fe80.zsh-theme) - Includes decorators for `git` information, current directory, user\@hostname, time, and the return code of last command when it is nonzero.
*   [feder (⭐0)](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme) - Clean, simple, compatible and meaningful. Tested on Linux, Unix and Windows under ANSI colors.
*   [felipec (⭐0)](https://github.com/felipec/zsh-prompt-felipec) - Minimalist theme with decorators for current directory, `git` status, exit code of last command, and root status.
*   [filthy (⭐43)](https://github.com/molovo/filthy) - A disgustingly clean ZSH prompt.
*   [firefoxic (⭐0)](https://github.com/firefoxic/firefoxic-zsh-theme/) - Fork of [Bureau (⭐39)](https://github.com/isqua/bureau) with tweaks to the node and `git` decorators.
*   [fish (raniconduh) (⭐10)](https://github.com/Raniconduh/zshfish) - ZSH theme reminiscent of the default `fish` shell theme. Includes `git` status decorations.
*   [fish (sbfkcel) (⭐0)](https://github.com/sbfkcel/oh-my-zsh-theme) - Minimalist theme with decorators for `git` status, current directory and username.
*   [fishy-lite (⭐2)](https://github.com/sudorook/fishy-lite) - Fork of the original [fishy (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy) theme in oh-my-zsh with much of the extraneous stuff cut out to improve load speeds. Includes a battery gauge and `git` status display that can be enabled on the right-hand side of the prompt.
*   [fishy2 (⭐5)](https://github.com/akinjide/fishy2) - ZSH theme inspired by [original fishy (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy).
*   [fluent-git (⭐10)](https://github.com/RobertKozak/fluent-git) - Displays time of last command execution, error code, hostname, username, `git` status, kubernetes cluster and namespace, path and ssh connection status.
*   [flux (⭐0)](https://github.com/jmg-duarte/flux-zsh) - A no-nonsense minimalist theme with `git` status decorations.
*   [forerunner (⭐5)](https://github.com/OpenReplyDE/zsh-forerunner) - Custom setup for [powerlevel9k (⭐13k)](https://github.com/bhilburn/powerlevel9k). Includes `git` status decorations.
*   [fortuity (⭐2)](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) - Includes status of last command, `git` information and current directory.
*   [frank (⭐0)](https://github.com/ronmackley/frank-theme) - Frank keeps to the point, displaying information compactly but readably on a single line. Frank keeps to the facts and only tells you extra things when they are important.
*   [friendly-fiesta (⭐0)](https://github.com/bruino/friendly-fiesta) - Fork of [terminal-party (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/terminalparty.zsh-theme) theme.
*   [frisk-arrow (⭐1)](https://github.com/BakeRolls/frisk-arrow) - A theme based on the [frisk (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh-theme.
*   [frisk-red (⭐0)](https://github.com/aishsingh/zsh/tree/master/frisk-red) - Red version of the [frisk (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) theme from oh-my-zsh.
*   [fritz (⭐0)](https://github.com/fritzccc/fritz-zsh-theme) - Works well on dark backgrounds. Includes `git` status decorations.
*   [frlo (⭐1)](https://github.com/fiorillo/frlo) - Uses your computer's hostname to come up with a (hopefully) unique three-color theme to display in your prompt, so you know at a glance which machine you're logged into.
*   [funkyberlin (⭐3)](https://github.com/Ottootto2010/funkyberlin-zsh-theme) - A colorful two-line theme with support for `git` and `svn`.
*   [funkydrac (⭐2)](https://github.com/warshanks/funkydrac) - Multiple Dracula-themed omz themes based on [funky (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/funky.zsh-theme) and an [oh-my-posh (⭐19k)](https://github.com/JanDeDobbeleer/oh-my-posh) theme based on [alien (⭐19k)](https://github.com/JanDeDobbeleer/oh-my-posh/blob/main/themes/aliens.omp.json)
*   [furio (⭐17)](https://github.com/hectorpalmatellez/furio-theme) - Fork of the [Cloud (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme) oh-my-zsh theme. with different colors and emojis.
*   [furry-umbrella (⭐0)](https://github.com/kb10uy/zsh-theme-furry-umbrella) - Colorful theme, works better on a dark background.
*   [gabriel2m (⭐0)](https://github.com/gabriel2m/gabriel2m-oh-my-zsh-theme) - Minimalist theme with decorators for the current directory and `git` status.
*   [gaia (⭐5)](https://github.com/gcaracuel/gaia.zsh-theme) - Originally a fork of [Bureau (⭐39)](https://github.com/isqua/bureau) adds new virtual environments info to the prompt: Kubernetes, virtualenv, rbenv and Java versions. Includes `git` status integration.
*   [gal (⭐3)](https://github.com/x6r/gal) - Minimalist theme based on [gallois (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/commits/master/themes/gallois.zsh-theme).
*   [gallifrey-war (⭐1)](https://github.com/cdubos-fr/gallifrey-war) - Inspired by [gallifrey (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#gallifrey). Includes decorators for `git` information, user\@host and current directory.
*   [garden (⭐1)](https://github.com/fecat233/garden) - Works better with a dark terminal background, includes `git` status decorations.
*   [garrett (⭐157)](https://github.com/chauncey-garrett/zsh-prompt-garrett) - Prezto prompt with the information you need the moment you need it.
*   [gawaine (⭐3)](https://github.com/nicolaracco/gawaine.zsh-theme) - Nicola Racco's theme. Requires `rvm` & `git` plugins.
*   [gbt (⭐554)](https://github.com/jtyr/gbt) - Go Bullet Train is a very customizable prompt builder inspired by Bullet Train and [oh-my-zsh (⭐178k)](https://github.com/robbyrussell/oh-my-zsh) that runs much faster. Includes many different status cars. Includes a [prompt-forwarding (⭐554)](https://github.com/jtyr/gbt#prompt-forwarding) feature than enables the user to forward their user-defined prompt to a remote machine and have the same-looking prompt across all machines via SSH but also in Docker, Kubectl, Vagrant, MySQL or in Screen without the need to install anything remotely.
*   [gcloud-prompt (⭐22)](https://github.com/ocadaruma/zsh-gcloud-prompt) - Shows the current gcloud configuration in the prompt.
*   [gentoo (⭐1)](https://github.com/ikelos/gentoo-zsh-theme) - Breaks out the oh-my-zsh `gentoo` theme into a separate repository for non-omz users.
*   [geometry (⭐959)](https://github.com/geometry-zsh/geometry) - A minimal ZSH theme where any function can be added to the left prompt or (async) right prompt on the fly.
*   [geometryHostInfo (⭐1)](https://github.com/Fuzen-py/GeometryHostInfo) - Adds host info to the [geometry (⭐959)](https://github.com/geometry-zsh/geometry) theme.
*   [gerry (⭐0)](https://github.com/GerryLarios/gerry-prompt) - Based on [bureau (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#bureau), includes decorations for `git` status, current time, username, hostname and current directory.
*   [get-to-work (⭐1)](https://github.com/Diogo13Antunes/Get_To_Work) - Minimalistic design, includes decorators for `git` status, virtual environment and the time.
*   [gg (⭐0)](https://github.com/YourBrightSmile/ggZshTheme) - Includes decorators for time and `git` status.
*   [ghoti (⭐0)](https://github.com/lonr/ghoti) - Mimics the `fish-shell` default prompt. Includes `git` decorations.
*   [gianu-alternative (⭐1)](https://github.com/zbentzinger/gianu-alternative-theme) - An alternative to [OMZ Gianu (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/61dd3682e69aa990a8a3589c5c61ea2e1edf8312/themes/gianu.zsh-theme) that changes prompt based on privilege. Includes `git` status and current directory decorators.
*   [gideon (⭐0)](https://github.com/userhiren/oh-my-zsh-gideon-theme) - Inspired by [avit (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme), includes `git` decorations, IP address, host and path.
*   [gimbo (⭐2)](https://github.com/gimbo/gimbo.zsh-theme) - A variant of [purepower (⭐296)](https://github.com/romkatv/dotfiles-public/blob/master/.purepower) with more features, a little eye candy and context-sensitive extra lines. Includes `git` status decorations, history number, username/hostname context, directory status, status of last command if it failed, and the Python virtualenv name if present.
*   [gimme (⭐0)](https://github.com/nralbrecht/gimmezsh) - A simplistic theme for ZSH with `git` integration. Inspired by the [gitsome (⭐54)](https://github.com/mtully/gitsome) theme.
*   [girazz (⭐0)](https://github.com/mdentremont/girazz) - A modification to the gnzh theme which adds `vi` mode to the right prompt.
*   [git-kali (⭐7)](https://github.com/Green0wl/zsh-git-kali-prompt) - Based on [An informative `git` prompt for kali (⭐1.7k)](https://github.com/olivierverdier/zsh-git-prompt). Includes decorators for `git` status, username\@host, and the current directory.
*   [git-prompt (awgn) (⭐13)](https://github.com/awgn/git-prompt) - A fast `git` prompt for `bash`, `zsh` and `fish`.
*   [git-prompt (olivierverdier) (⭐1.7k)](https://github.com/olivierverdier/zsh-git-prompt) - Displays information about the current `git` repository. In particular the branch name, difference with remote branch, number of files staged or changed, etc.
*   [git-prompt (woefe) (⭐264)](https://github.com/woefe/git-prompt.zsh) - A fast, customizable, pure-shell, asynchronous `git`-aware prompt for ZSH heavily inspired by Olivier Verdier's [zsh-git-prompt (⭐1.7k)](https://github.com/olivierverdier/zsh-git-prompt) and very similar to the "Informative VCS" prompt of fish shell.
*   [git-prompt-kit (⭐8)](https://github.com/olets/git-prompt-kit) - A configurable set of components for creating feature rich, high performance Git-aware zsh prompts (aka themes) with minimal coding.
*   [git-simple (⭐1)](https://github.com/ZakharEl/git-simple-theme) - Simple theme that includes detailed `git` status decorations.
*   [git-venv-prompt (⭐1)](https://github.com/walkingshamrock/zsh-git-venv-prompt) - Enhances your Zsh prompt with information about the current Python virtual environment and the Git status (asynchronously). It uses zsh-async to provide async updates for Git status and displays the virtual environment in the second line of the prompt.
*   [gitbash (⭐2)](https://github.com/eddieantonio/gitbash-zsh-theme/) - Mimics the default prompt from [Git for Windows](https://gitforwindows.org/). Includes `git` status, user\@host and current directory decorators.
*   [github (⭐3)](https://github.com/Debdut/github.zsh-theme/) - A GitHub-inspired theme. Shows decorators for (truncated) current directory, hostname and `git` status. Includes both light and dark modes and detects system settings for that on macOS and Linux.
*   [gitneko (⭐3)](https://github.com/gynamics/zsh-gitneko/) - Has a neko `(^>ω<^)` prompt with `git` status information.
*   [gitprompt.sh (⭐1)](https://github.com/danieldietrich/gitprompt.sh) - Works with both `bash` and `git`. 256 color support. Includes decorators for `git` status and current directory.
*   [gitsome (⭐54)](https://github.com/mtully/gitsome) - Super simple prompt with `git` info, optimized for the [Flat Terminal (⭐624)](https://github.com/ahmetsulek/flat-terminal) color scheme.
*   [gitstatus (⭐5)](https://github.com/kimyvgy/gitstatus-zsh-theme) - Shows command and `git` status decorations.
*   [gitster (shashankmehta) (⭐67)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) - When in a `git` repo, it shows the location from the `git` repository root folder. When not in a `git` repo, it shows the path relative to home, `~`.
*   [gitster (zimfw) (⭐6)](https://github.com/zimfw/gitster) - Zim fork of shashankmehta's [gitster (⭐67)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) prompt theme
*   [gitsterv2 (⭐0)](https://github.com/xakraz/gisterv2-zsh-theme) - Forked from the original [gitster (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#gitster) theme.
*   [gk3000 (⭐0)](https://github.com/gk3000/gk3000-oh-my-zsh-theme) - Includes `git` status decorations and full path to current directory.
*   [glider (⭐1)](https://github.com/MrRedacted/zsh-glider) - Based on [strug (⭐2)](https://github.com/triplepointfive/oh-my-zsh/blob/master/themes/strug.zsh-theme). Includes decorators for `git` status, username, hostname and current directory.
*   [glimmer (⭐1)](https://github.com/martnu/glimmer) - Includes `git` branch, time and user\@host decorators.
*   [gn-z11 (⭐0)](https://github.com/xxidbr9/zsh_GN-z11-theme) - Includes decorators for `git` status and the last command's exit status.
*   [gndx (⭐48)](https://github.com/gndx/gndx-zsh-theme) - Includes `git` status, hostname, directory and last command exit status decorations.
*   [gnrnzh (⭐1)](https://github.com/PaoloneM/gnrnzh-zsh-theme) - Customization of [gnzh.zsh-theme (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) from oh-my-zsh.
*   [gocilla (⭐0)](https://github.com/goranvasic/gocilla-iterm-zsh) - Theme for iTerm 2 and ZSH. Uncludes `git` status, user\@host, path and date decorators.
*   [golden-prompt (⭐1)](https://github.com/Goldeneye128/golden-prompt) - A simple prompt that incorporates fish-like functionality and decorators for `git` status, current directory.
*   [goprompt (⭐4)](https://github.com/NonLogicalDev/shell.async-goprompt) - Lightning fast. Includes decorators for truncated current directory, last command duration & exit status, vim-mode indicators, `git` information, datetime and parent process name.
*   [gops (⭐10)](https://github.com/noxer/gops) - Fast powerline-like prompt. Includes `git` status, current directory, root status decorations.
*   [gorchak (⭐0)](https://github.com/evgenygorchakov/oh-my-zsh-gorchak-theme/) - Inspired by [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) and [af-magic (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#af-magic). Includes decorators for `git` information and Node.js version.
*   [grayt (⭐3)](https://github.com/evanthegrayt/grayt-zsh-theme) - Simple yet informative theme that includes `git` decorations and the return status of the last command.
*   [green-lambda (⭐0)](https://github.com/Ishidawg/minimal-green-lambda) - Minimalist Lambda theme. Includes `git` decorations.
*   [greencastle (⭐1)](https://github.com/GustavGroenborg/greencastle-zsh-theme/) - Minimalistic theme, that supports really, **really**, long branch names, without severely truncating the prompt. The theme is inspired by the [jonathan theme (⭐0)](https://github.com/thlorenz/oh-my-zsh/blob/master/themes/jonathan.zsh-theme) and the [robby russel theme (⭐0)](https://github.com/thlorenz/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme). Includes decorators for current directory, `git` information and the exit status of the last command run.
*   [greenclean (⭐0)](https://github.com/dmicha16/greenclean) - Fork of [akz92/clean (⭐9)](https://github.com/akz92/clean) with a bit more green and permanent clock on the right.
*   [griffin (⭐0)](https://github.com/GriffinLedingham/griffin.zsh-theme) - Minimalist, includes `git` status decorations.
*   [grs (⭐0)](https://github.com/gersontpc/zsh-theme-grs) - Includes `git` status, user id and working directory decorators.
*   [gruvbox (hgaiser) (⭐7)](https://github.com/hgaiser/gruvbox-zsh) - Sets colors from the [gruvbox (⭐14k)](https://github.com/morhetz/gruvbox) `vim` plugin.
*   [gruvbox (sbugzu) (⭐121)](https://github.com/sbugzu/gruvbox-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874), uses the same colors from the [gruvbox (⭐14k)](https://github.com/morhetz/gruvbox) `vim` plugin.
*   [guezwhoz (⭐100)](https://github.com/guesswhozzz/guezwhoz-zshell) - Minimalist, includes `git` status decorations.
*   [gugulenok (⭐1)](https://github.com/gugulen0k/gugulenok/) - Has both a dark and a light mode. Includes decorators for `git` status, time and current directory.
*   [guri (⭐22)](https://github.com/victorfsf/guri) - A Simple and fast Oh-My-Zsh theme, based on [Pure (⭐14k)](https://github.com/sindresorhus/pure)'s design.
*   [gus (⭐0)](https://github.com/gusye1234/Gus-zsh-theme/) - Hackable transient theme. Includes decorators for conda, `git` information and current directory.
*   [hackersaurus (⭐11)](https://github.com/bhilburn/hackersaurus) - A theme with `git` status and exit code of last command run decorators embedded in the prompt. Related to [powerlevel9k (⭐13k)](https://github.com/bhilburn/powerlevel9k).
*   [halfeld (⭐5)](https://github.com/IgorHalfeld/halfeld-zsh-theme) - Minimalist theme with `git` decorations.
*   [halil (⭐2)](https://github.com/5m0k3r/zsh-themes) - Fork of oh-my-zsh's [amuse (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) theme.
*   [hana-matcha (⭐2)](https://github.com/arturoalviar/hana-matcha-zsh-theme) - A simple theme with the first character being 花(hana), the kanji for flower. This theme was inspired by a keycap set called DSA Hana. This pairs well with the [hana atom (⭐0)](https://github.com/arturoalviar/hana-matcha-syntax) theme. Includes `git` status decorations.
*   [handy (⭐1)](https://github.com/hanleylee/handy) - Colorful and lightweight theme. Shows root status, `git` status, current directory and `user@hostname` decorations.
*   [hanpen (⭐0)](https://github.com/kojole/hanpen.zsh-theme) - Shows `git` branch and status, last command exit code, last command execution time if more than `ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`.
*   [hapin (⭐2)](https://github.com/hanamiyuna/hapin-zsh-theme/blob/master/hapin.zsh-theme) - Based on oxide, includes `git` status decorations and current user/host information.
*   [happy-coding (⭐2)](https://github.com/lexhuismans/happy-coding/) - Stripped down version of [passion (⭐313)](https://github.com/ChesterYue/ohmyzsh-theme-passion). Includes decorators for time, `git` branch, last command execution time and last command exit status.
*   [haribo (⭐8)](https://github.com/haribo/omz-haribo-theme) - Simple `git` status + timestamp in prompt.
*   [hcompact (⭐1)](https://github.com/fusion809/zsh-theme) - Displays time, OS (including distro if on Linux), directory and whether running as root.
*   [headline (⭐291)](https://github.com/Moarram/headline) - A responsive ZSH theme featuring Git status information and a colored line above the prompt.
*   [heapbytes (⭐80)](https://github.com/heapbytes/heapbytes-zsh) - Includes decorators for current directory, tun0 ip if on a VPN, wlan ip when not on VPN and `git` information.
*   [heart (⭐7)](https://github.com/gko/heart) - Heart themed prompt for light backgrounds.
*   [hedroed-bureau (⭐0)](https://github.com/Hedroed/hedroed-bureau.zsh-theme) - Based on [bureau (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bureau), with added `git` status decorations and `npm` status.
*   [helb (⭐0)](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old `bash` theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
*   [hematite (⭐0)](https://github.com/bigdave/hematite) - Minimalist promot that tries to show only the status decorations that are actively useful at a given time.
*   [hex (⭐0)](https://github.com/hectorBrown/hex-zsh) - Heavily based on [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira), and [gruvbox (⭐121)](https://github.com/sbugzu/gruvbox-zsh), which in turn is based on [agnoster](https://gist.github.com/agnoster/3712874). Includes decorators for current directory, `git` status information, active python virtualenv, exit status of the last command run. Requires a Powerline-compatible font.
*   [hexagon (⭐2)](https://github.com/diogoazevedos/hexagon) - Minimalist ZSH theme based on [geometry (⭐959)](https://github.com/geometry-zsh/geometry).
*   [hfulldate (⭐1)](https://github.com/fusion809/zsh-theme) - Displays time, date, OS (including distro if on Linux), directory and whether running as root.
*   [hhktony (⭐0)](https://github.com/hhktony/hhktony.zsh-theme) - Inspired by robbyrussell theme + ssh connection status prompt.
*   [hietan (⭐1)](https://github.com/Hietan/Hietan_ZshTheme) - Includes decorators for current directory, date & time, `git` status and the exit value of the last command run. Requires a Nerd Font.
*   [hijack (⭐1)](https://github.com/thegodheehee/hijack-zsh) - Includes decorators for user\@hostname, current directory, and `git` information.
*   [hina (⭐1)](https://github.com/ucpr/hina) - Written in `golang`, includes `git` status decoration and kubernetes context.
*   [hip-fellow (⭐0)](https://github.com/haitaim/hip-fellow) - Includes `git` status decorations and works with standard fonts.
*   [hipstersmoothie-p9x (⭐9)](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - A variant of [powerlevel9k (⭐13k)](https://github.com/bhilburn/powerlevel9k).
*   [ho-my-zsh (⭐1)](https://github.com/Mboukhal/hoMyZsh_theme) - Includes decorators for current directory and `git` information.
*   [hoffish (⭐0)](https://github.com/emilHof/hoffish-zsh-theme) - If the [agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme) theme and [fish](https://fishshell.com/) shell had a ZSH theme for a child. Includes decorators for `git` status, trimmed path to current directory, root status, exit status of the last command run and the active python virtualenv. Requires a Powerline font and the [zsh-autosuggestions (⭐33k)](https://github.com/zsh-users/zsh-autosuggestions) and [shrink-path (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/shrink-path/shrink-path.plugin.zsh) plugins.
*   [hogbal (⭐0)](https://github.com/hogbal/hogbal.zsh-theme) - Works best with a dark background and a 256 color terminal program. Includes decorators for `virtualenv`, `git` information, `username@hostname` and current directory.
*   [home (⭐3)](https://github.com/sheerun/home) - Pretty and short one-line theme that makes you feel at home.
*   [hometown (⭐10)](https://github.com/olets/hometown-prompt) - A feature rich, high performance `git`-aware ZSH theme with segments for the user, host, time, the current working directory and its parent, and detailed full Git status within a Git repo.
*   [honukai-iterm (⭐1.1k)](https://github.com/oskarkrawczyk/honukai-iterm-zsh) - Honukai theme and colors for oh-my-zsh and iTerm 2.
*   [hoozeeth (⭐1)](https://github.com/hooay233/Hoozeeth) - Minimalist theme, includes decorators for user\@hostname, the date & time, and the current working directory.
*   [horizontal (⭐3)](https://github.com/nuimk/horizontal) - Two line prompt with a horizontal separator.
*   [hornix (⭐1)](https://github.com/fusion809/zsh-theme) - Displays time & date, OS (including distro if on Linux), directory and whether running as root.
*   [horse-sh (⭐0)](https://github.com/emileswarts/horse-sh) - A very minimal brown/red ZSH theme.
*   [htb (⭐2)](https://github.com/ibyf0r3ns1cs/zsh-htb-theme) - Inspired by the pwnbox on a HackTheBox machine. Includes decorators for user\@host, IP address and the current directory.
*   [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - Simple and clean, includes the return code of the last command executed.
*   [humbled (⭐1)](https://github.com/saravanabalagi/zsh-theme-humbled) - A clean and humble theme with left-aligned `condaenv`, `virtualenv` and `git` status. Requires [condaenv (⭐1)](https://github.com/saravanabalagi/zsh-plugin-condaenv) plugin.
*   [hyper (⭐43)](https://github.com/willmendesneto/hyper-oh-my-zsh) - Designed to work with the hyper terminal theme, includes `git` status decorations.
*   [hyperzsh (⭐533)](https://github.com/tylerreckart/hyperzsh) - Gives you a comprehensive overview of the branch you're working on and the status of your repository without cluttering your terminal.
*   [iamskok (⭐3)](https://github.com/iamskok/iamskok.zsh-theme) - Works well on a dark background.
*   [iay (⭐7)](https://github.com/aaqaishtyaq/iay) - A `{ba,z}sh` prompt written in Rust. Includes decorations for the current directory and `git` status.
*   [ice (⭐1)](https://github.com/Lenart12/ice.zsh-theme) - Very lightly modified [bureau (⭐39)](https://github.com/isqua/bureau) theme combined with [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
*   [ichirei (⭐0)](https://github.com/ichirei/ichirei.zsh-theme) - Colorful. Includes decorators for `git` status, time & current directory. Requires a Nerd Font.
*   [icicle (⭐2)](https://github.com/JamesConlan96/Icicle) - Includes `git` status decorations, and whether running as root.
*   [iGeek (⭐0)](https://github.com/KalebHawkins/ohmyzsh-IGeek-OSX) - Modified iGeek theme. Works with macOS out-of the box, includes `git` status decorations.
*   [igeek (⭐38)](https://github.com/Saleh7/igeek-zsh-theme) - Displays system information when starting a new terminal session.
*   [iggy (⭐10)](https://github.com/eugenk/zsh-prompt-iggy) - A super happy awesome Powerline-style, `git`-aware **prezto only** theme.
*   [igorsilva (⭐11)](https://github.com/igor9silva/igorsilva-zsh-theme) - Shows current directory, customizable delimiter, current branch, and `git` status decorators.
*   [iguanidae (⭐2)](https://github.com/btd1337/iguanidae-zsh-theme) - Includes `git`, `nvm` and `venv` decorations.
*   [illusion (⭐3)](https://github.com/shabane/illusion) - Includes username, current working directory, `git` status and last command status decorators.
*   [illuvia-gitster (⭐1)](https://github.com/lopezator/lluvia-gitster) - Fork of [ergenekonyigit/lambda-gitster (⭐115)](https://github.com/ergenekonyigit/lambda-gitster) with spacing improvements and an updated icon. Includes `git` status information.
*   [imp (⭐28)](https://github.com/igormp/Imp) - Based on [zork (⭐15k)](https://github.com/Bash-it/bash-it/wiki/Themes#zork) and optimized for dark backgrounds.
*   [imranic (⭐2)](https://github.com/alimranahmed/zsh-imranic-themes) - Minimalist theme with decorators for `git` status, python virtualenv, rvm ruby version, conda version, kube status,  and current directory.
*   [infernus (⭐0)](https://github.com/jshiell/infernus-zsh-theme) - Minimalist theme, better on dark backgrounds.
*   [infoline (⭐4)](https://github.com/hevi9/infoline-zsh-theme) - Clean theme that shows `git` status, background jobs, remote host, and other information.
*   [integral (⭐0)](https://github.com/Readf0x/integral-prompt) - Math-inspired, includes decorators for time, current directory and `git` status.
*   [inthedeepspace (⭐0)](https://github.com/alionapermes/inthedeepspace/) - Based on [intheloop (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#user-content-intheloop) and inspired by [vim-deep-space (⭐307)](https://github.com/tyrannicaltoucan/vim-deep-space).
*   [intheloop-powerline (⭐1)](https://github.com/zyphrus/intheloop-powerline) - An extension of the [intheloop (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) theme to use powerline fonts.
*   [itg (⭐35)](https://github.com/itsthatguy/itg.zsh-theme) - itsthatguy's theme.
*   [itlbv (⭐0)](https://github.com/itlbv/itlbv-ohmyzsh-theme) - Minimalist. Includes decorators for `git` status and the current directory.
*   [ittecture (⭐0)](https://github.com/ittecture/ittecture-omz-theme) - Includes decorators for current directory and `git` information.
*   [ivabus (⭐7)](https://github.com/ivabus/ivabus-zsh-theme) - Inspired by the GitHub Codespaces prompt. Includes decorators for `git` status, username and current directory.
*   [ivy (⭐2)](https://github.com/ivyhjk/ohmyzsh-theme-ivy) - Works well on dark backgrounds. Includes user\@host, `git` status and time decorators. Based on the [obraun (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#obraun) theme.
*   [jacobin (⭐0)](https://github.com/Jsharkc/jacobin-zsh-theme) - Based on refined and ys themes, includes `git` status decorations. Includes an optional iterm2 color scheme.
*   [jake (⭐0)](https://github.com/JakeHuneau/Jake.zsh-theme) - Shows the time, the current directory, and `git` branch information including the branch name and a red + if the branch has un-pushed changes.
*   [jam (⭐3)](https://github.com/jesusangelm/Jam-Zsh-Theme) - Optimized for dark backgrounds, includes `git` status and `rvm` status.
*   [jax (⭐0)](https://github.com/jhammerberg/jax-theme) Reminiscent of Powerline. Includes decorators for current directory and current user.
*   [jc (⭐1)](https://github.com/jclementex/jc-zsh-theme) - For dark terminal backgrounds, includes `git` status information.
*   [jcl (⭐2)](https://github.com/jasonlewis/jcl-zsh-theme) - Loosely based on the `ys` theme.
*   [jeff (⭐0)](https://github.com/jbaranski/jeff-zsh-theme) - Based on [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira).  Includes decorators for user\@host, time, current directory and `git` status.
*   [jerome (⭐0)](https://github.com/jeromescuggs/jerome-theme) - Colorful theme based on the [dieter (⭐0)](https://github.com/jeromescuggs/jerome-theme) theme, but with a yellow hostname. Includes `git` decorations.
*   [jhleeeme (⭐2)](https://github.com/JHLeeeMe/JHLeeeMe-Zsh-Theme) - Includes `git` and python virtualenv status decorations, user, pwd,time and system name.
*   [jmsp (⭐0)](https://github.com/juacu7340/jmsp.zsh-theme) - Focused on simplicity and SSH usefullness. Includes `git` status and current directory decorators.
*   [jmtech (⭐1)](https://github.com/jmaaltech/jmtech-zsh-theme) - Customizable colors and symbols. Includes decorators for `git` status, exit status of last command run, `gpg` signing information and timestamps. Requires a [Nerd Font (⭐57k)](https://github.com/ryanoasis/nerd-fonts) for the `git` status icons.
*   [jnooree (⭐0)](https://github.com/jnooree/jnooree-zsh-theme) - Minimalist theme with colors adapted from the [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme. Includes decorators for `git` status, whether running as non-default user and current working directory.
*   [joje (⭐0)](https://github.com/joje6/joje.zsh-theme) - Includes decorators for `git` status and current directory.
*   [jon (⭐1)](https://github.com/Jon-Schneider/jon.zsh-theme) - A simplified [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) with the colors of [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme).
*   [jovial (⭐501)](https://github.com/zthxxx/jovial) - Shows decorators for host, user, path, development environment, `git` branch, and which `python` venv is active.
*   [jpegleg (⭐1)](https://github.com/jpegleg/zshrc) - Similar to dark blood theme, includes timestamp and `git` decorations.
*   [js-magic (⭐0)](https://github.com/JSextonn/js-magic) - A simplified take on [af-magic (⭐7)](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme). Includes current working directory and `git` status decorations.
*   [judgedim (⭐0)](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - Minimalist prompt.
*   [july (⭐0)](https://github.com/skippyr/july) - Minimalist prompt. Includes decorators for user, host and current directory.
*   [just-another (⭐0)](https://github.com/supertassu/another-theme) - Just another theme, with hostname when you're sshed to another machine.
*   [just-around-the-corner (⭐0)](https://github.com/DevinLeamy/just-around-the-corner) - Counts down the days until Christmas. Includes `git` status decorations.
*   [jwalter (⭐4)](https://github.com/jeffwalter/zsh-jwalter) - Powerline-style theme with `git`, `svn`, `npm`, `rvm` and network awareness. Requires Powerline-compatible terminal font.
*   [jyumpp (⭐0)](https://github.com/Jyumpp/jyumpp-zsh-theme) - Configuration file and installer for Powerlevel 10K.
*   [kali-like (⭐40)](https://github.com/clamy54/kali-like-zsh-theme) - Inspired by the Kali Linux default ZSH theme. Includes decorators for user\@host, current directory and `git` information.
*   [kali (⭐45)](https://github.com/h4ck3r0/kali-theme) - Includes `git` decorations.
*   [kalsowerus (⭐3)](https://github.com/kalsowerus/kalsowerus.zsh-theme) - Colorful powerline-inspired multi-line theme, includes decorations for `git` status, directory, last command exit status and `nvm` information.
*   [karu (⭐2)](https://github.com/zaari/karu) - Minimalist single line ZSH prompt.
*   [kawaii (⭐1)](https://github.com/LeonidPilyugin/kawaii-oh-my-zsh/) - Has terminal and virtual console modes. Includes decorators for username, directory, last command exit status, timestamp and `git` status.
*   [keloran (⭐2)](https://github.com/Keloran/keloran.zsh-theme) - Theme that includes a few features from other themes.
*   [kenton (⭐1)](https://github.com/notnek/zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
*   [kerneldiego (⭐2)](https://github.com/KernelDiego/kerneldiego-zsh-theme) - A minimal and informative Zsh theme with a clean box-style layout, Git integration, and colorful prompt indicators for productivity and visual clarity.
*   [kevin (⭐2)](https://github.com/KevinParnell/Kevin-zsh) - Colorful theme, includes iTerm 2 color schemes.
*   [kgzsh (⭐0)](https://github.com/Kashugoyal/kgzsh) - Includes `git` status deorations, works well on darker backgrounds.
*   [kido (⭐5)](https://github.com/KidoThunder/kido-zsh-theme) - Based on `ys` and `robbyrussell` themes. Includes decorators for the exit code of the last command run, python virtualenv and VCS status.
*   [kimwz (⭐9)](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - Minimal theme.
*   [kinda-fishy (⭐7)](https://github.com/folixg/kinda-fishy-theme) - Based on Fishy theme, but shows full paths instead of abbreviated directories and only shows user\@machine in `ssh` sessions and docker containers.
*   [kiss (⭐111)](https://github.com/rileytwo/kiss) - Simple theme for oh-my-zsh, VSCode, iTerm2, Neovim, and RStudio. Includes `git` status decorations.
*   [kketcham (⭐0)](https://github.com/prototype27/kketcham) - Theme with nifty colors on the `git` info.
*   [ko (⭐1)](https://github.com/JoshBenn/KoTheme-for-Oh-My-Zsh/) - Includes decorators for `git` status and current directory.
*   [korittg (⭐0)](https://github.com/dkorittki/korittg-zsh-theme) - Minimalistic but informative. Includes decorations for `git` status, current directory and the `kubectl` context and namespace.
*   [kote (⭐1)](https://github.com/wendygaoyuan/kote-zsh-theme) - Best for dark backgrounds. Includes `git` status decorations.
*   [kotterstep (⭐0)](https://github.com/sorenvonsarvort/kotterstep-zsh-theme) - Two line theme designed for dark terminals, has `git` decorations.
*   [krak3n (⭐1)](https://github.com/krak3n/zsh-theme) - Shows golang version and the current `git` branch.
*   [kraken (⭐1)](https://github.com/KrakenTheme/kraken-zsh) - A dark theme for ZSH.
*   [ksposh (⭐0)](https://github.com/KSposh/ksposh-zsh-theme) - Includes decorators for python virtual environment, `git` information, current directory and username.
*   [kube (⭐2)](https://github.com/tigerjz32/kube-zsh-theme) - Based on [macos-terminal (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#macos-terminal), includes `kubectl` context. Has time, directory, and `git` status decorations.
*   [kumavis (⭐0)](https://github.com/kumavis/kumavis-zsh-theme) - Agnoster fork optimized for solarized terminals. Requires powerline-compatible font.
*   [kw (⭐1)](https://github.com/Kwpolska/kw.zsh-theme) - Colorful theme with `git` and `hg` status information, ability to add host-specific colors to hostname.
*   [kyuu (⭐1)](https://github.com/arturoalviar/kyuu-zsh-theme) - A simple theme with the first character being 九(kyuu), the number 9. The primary color is blue with a magenta accent. Includes `git` status decorations.
*   [lacerate (⭐0)](https://github.com/Petrushevsky-A/Lacerate-zsh-theme) - Minimalist theme with decorations for `git`, `hg` and python `venv` status.
*   [laconic (⭐0)](https://github.com/Saka7/laconic.zsh-theme) - Simple theme with `git` status and current directory decorators.
*   [lagnoda (⭐3)](https://github.com/jashezan/lagnoda) Inspired by [agnoster](https://gist.github.com/agnoster/3712874) and `lambda` themes. Includes decorators for username\@hostname, current directory, `git`, `hg`, or `bzr` status, current virtualenv, exit status of last command run, and current aws profile.
*   [lagune (⭐1)](https://github.com/noplay/lagune) - A minimal ZSH theme.
*   [lambda (bluedragon1221) (⭐2)](https://github.com/bluedragon1221/zsh-lambda-prompt) - Includes decorators for current directory and `git` status.
*   [lambda (cdimascio) (⭐68)](https://github.com/cdimascio/lambda-zsh-theme) -  Inspired by the [lambda (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) theme. Includes `git` status decorations.
*   [lambda (halfo) (⭐467)](https://github.com/halfo/lambda-mod-zsh-theme/) - A ZSH theme optimized for `git` users who use unicode-compatible fonts and terminal applications.
*   [lambda-blazinggit (⭐0)](https://github.com/zalefin/lambda-blazinggit) - Includes blazing fast, detailed `git` information. Requires [Nerd Fonts (⭐57k)](https://github.com/ryanoasis/nerd-fonts) and the [gitstatus (⭐1.7k)](https://github.com/romkatv/gitstatus) plugin.
*   [lambda-gitster (⭐115)](https://github.com/ergenekonyigit/lambda-gitster) - Minimalist prompt that includes `git` information.
*   [lambda-minimal (⭐4)](https://github.com/sohnryang/lambda-minimal-theme) - Simple theme based on lambda with `git` status and virtualenv information.
*   [lambda-mod (⭐467)](https://github.com/halfo/lambda-mod-zsh-theme) - A simple ZSH theme, optimized for `git` usage.
*   [lambda-p (⭐0)](https://github.com/paimanbandi/lambda-p) - Inspired by the [lambda mod (⭐467)](https://github.com/halfo/lambda-mod-zsh-theme) and [Lambda V (⭐2)](https://github.com/vkaracic/lambdav-zsh-theme) themes. Includes `git` status decorations.
*   [lambda-pure (⭐123)](https://github.com/marszall87/lambda-pure) - A minimal ZSH theme, based on [pure (⭐14k)](https://github.com/sindresorhus/pure), with added Node.js version decorator.
*   [lambda-v (⭐2)](https://github.com/vkaracic/lambdav-zsh-theme) - A combination of the Lambda and Fishy themes, includes `git` status decorations.
*   [lambda-zen (⭐4)](https://github.com/seamile/lambda-zen) - inspired by [lambda mod theme (⭐467)](https://github.com/halfo/lambda-mod-zsh-theme) with graphical `git` status decorations.
*   [lambder (⭐0)](https://github.com/avillen/zsh-theme-lambder) - Includes `git` status decorations, works best with a dark terminal theme.
*   [laniksj (⭐0)](https://github.com/LanikSJ/laniksj-zsh-theme) - Works best on a dark background. Based on the great `ys` theme and [Honukai ZSH Theme (⭐1.1k)](https://github.com/oskarkrawczyk/honukai-iterm-zsh). Shows root status and `git` status decorations.
*   [lazyprodigy (⭐1)](https://github.com/drewlustro/lazyprodigy-zsh-theme) - Optimized for dark terminals, has variants for local and remote systems.
*   [leafia (⭐1)](https://github.com/Ghostrick/leafia-prompt) - Leafy prezto theme that shows `git` status information.
*   [lean (⭐154)](https://github.com/miekg/lean) - Inspired by [pure (⭐14k)](https://github.com/sindresorhus/pure). Has decorators for `git` status information, exit status of last command run, and the elapsed time of last command.
*   [lemon (⭐2)](https://github.com/carlosvitr/lemon_zsh) - Many beautiful colors for you to enjoy. done with care and patience. Includes `git` status and ruby version decorations.
*   [leon (⭐0)](https://github.com/prince-an/Leon_zshTheme) - Works well on light background. Includes `git` status, time, username\@host, working directory and last command exit status decorations.
*   [less-noise (⭐0)](https://github.com/ablil/less-noise) - Minimalist theme with decorators for `git` status, current directory and the current time.
*   [leverage (⭐1)](https://github.com/gschnall/leverage) - Based on [minimal (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/minimal.zsh-theme), uses colors, and an extra `¬` character, to better distinguish the command line prompt from your output.
*   [lewis (⭐0)](https://github.com/lewisflude/oh-my-lewis) - Black, white and red theme. Shows `git` status information.
*   [lgbt (⭐0)](https://github.com/nautilor/lgbt.zsh-theme) - Colorful theme with decorators for current directory and `git` status.
*   [lgbtq (⭐3)](https://github.com/PhoenixSmaug/zsh-lgbtq-themes) - A collection of lgbtq themes for your terminal.
*   [light (⭐0)](https://github.com/InfinityUniverse0/light-zsh) - Works best on a light background. Includes decorators for username\@hostname, `git` status and the current directory.
*   [lightbulb (⭐4)](https://github.com/lightbulb703/lightbulb-zsh-theme) - Includes decorations for kernel, OS version, uptime and `git`.
*   [lighthaus (⭐7)](https://github.com/lighthaus-theme/zsh) - A prompt that compliments the [Lighthaus (⭐28)](https://github.com/lighthaus-theme/lighthaus) theme. Shows `git` information, GitHub/GitLab logo and shows changes as and when they occur.
*   [lila (⭐0)](https://github.com/raphaelivan/lila-zsh-theme) - Minimalist theme, best on a dark terminal background.
*   [lildragon (⭐0)](https://github.com/skippyr/lildragon) - Dragon-themed. Includes decorators for `git` status, current directory & username. Requires a font with emoji glyphs.
*   [lilith (⭐0)](https://github.com/aknackd/zsh-themes) - Modification of [gallifrey (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme) and [hyperzsh (⭐533)](https://github.com/tylerreckart/hyperzsh).
*   [lime (⭐16)](https://github.com/yous/lime) - Simple and easily customizable ZSH theme.
*   [limpide (⭐0)](https://github.com/shooteram/limpide) - Modified version of [miloshadzic (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#miloshadzic) theme which displays parent and current directory.
*   [linear (⭐5)](https://github.com/MrYazdan/zsh-linear-theme) - Reminiscent of Powerline. Includes segments with `git` status, Pythonvirtualenv, current directory and current time.
*   [link (⭐1)](https://github.com/kylegl/link-zsh-theme) - Minimalist. Includes `git` status and last command exit decorations.
*   [linuxer (⭐2)](https://github.com/patrick330602/linuxer) - Inspired by Yaris Alex Gutierrez's [classyTouch (⭐53)](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh), Yad Smood's `ys`, and the [Bureau (⭐39)](https://github.com/isqua/bureau) theme.
*   [linuxero (⭐0)](https://github.com/andreshincapier/linuxero) - Minimalist. Includes decorations for root status, current directory, `git` status, current ruby rvm environment and current python virtualenv.
*   [liquidprompt (⭐4.6k)](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt with useful information when you need it. It shows you what you need when you need it. You will notice what changes when it changes, saving time and frustration.
*   [lish (⭐0)](https://github.com/bashelled/lish) - A casual theme. No roughness, just smooth. Includes `git`, user\@host, last command exit status, current directory, current time and root status decorators.
*   [liver (⭐0)](https://github.com/RenoirTan/liver.zsh-theme) - Colorful, includes `git` status, user, host, current and relative path to the current repository root decorations.
*   [llama (⭐6)](https://github.com/PsychoLlama/llama.zsh-theme) - Minimalist theme used by discerning llamas.
*   [logico (⭐3)](https://github.com/logico/logico-zsh-theme) - Has `git` decorations. Shows remote status and indicator for vi-mode.
*   [lone-star (⭐0)](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - Texas-themed theme based on Sindre Sorhus' pure theme.
*   [longsilvern (⭐1)](https://github.com/long263/longsilvern-zsh-theme) - Includes `git` and compact `pwd` decorations.
*   [lorond (⭐0)](https://github.com/lorond/zsh-lorond/) - Compact version of [af-magic (⭐7)](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme). Includes `git` status, works with standard fonts.
*   [lperezp (⭐0)](https://github.com/lperezp/lperezp-zsh-theme) - Includes decorators for user\@hostname, `git` status, current directory and the exit status of the last command run.
*   [lpha3cho (⭐44)](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters) - Modified version of the [intheloop (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) theme for pentesters which includes the date, time, and IP address for pentest logging.
*   [luceast (⭐0)](https://github.com/LucEast/luceast-zsh-theme) - Optimized for `git`. Includes decorations for username, host, time & working directory.
*   [luckycoding (⭐1)](https://github.com/ZitherPeng/oh-my-zsh-luckycoding-theme) - Based on the [robbyrussell (⭐178k)](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) theme, includes `git` decorations and the last command's exit code.
*   [ludvig (⭐0)](https://github.com/daviludvig/ludvig-theme-zsh) - Minimalist. Includes decorators for `git` status, current directory, current time and the last command's exit status.
*   [ludwigws (⭐0)](https://github.com/LudwigWS/my-zsh-theme) - Variant of [lambda-mod (⭐467)](https://github.com/halfo/lambda-mod-zsh-theme) theme. Has `git` decorations, requires a powerline-compatible terminal font.
*   [luke (⭐0)](https://github.com/xueguangl23/luke_zsh_theme) - Includes `git` decorations. Based on the [frisk (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh theme.
*   [lukerandall-extended (⭐1)](https://github.com/mpyw/oh-my-zsh-lukerandall-extended) - Extended version of the [lukerandall (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lukerandall.zsh-theme) theme. Includes decorations for `git` status and the status of the last command run.
*   [lunachar (⭐0)](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/lunachar.zsh-theme) - Minimalist theme.
*   [macos (⭐18)](https://github.com/alejandromume/macos-zsh-theme) - Includes `git` status decorations.
*   [mad (⭐0)](https://github.com/MartinWie/ohmyzsh-theme-mad) - Includes `git` status and last command execution time decorations.
*   [madas (⭐0)](https://github.com/utauyo/madas-zsh-theme) - Inspired by af-magic. Includes decorators for `git` status, user\@host, and whether the last command failed.
*   [magento (⭐0)](https://github.com/cmuench/zsh-magento-cloud/blob/main/zsh-magento-cloud.plugin.zsh) - Add Magento Cloud Command Line Interface ([magento-cloud CLI](https://experienceleague.adobe.com/docs/commerce-cloud-service/user-guide/dev-tools/cloud-cli.html?lang=en)) completions.
*   [magicmace (⭐5)](https://github.com/zimfw/magicmace) - Inspired by xero's ZSH prompt and [eriner's prompt (⭐22)](https://github.com/zimfw/eriner). Includes status codes for active python `venv`, exit status of last command, shortened working directory, `git` status decorations.
*   [magico (⭐0)](https://github.com/IOsonoTAN/magico) - IOsonoTAN's magico theme.
*   [magpie (⭐0)](https://github.com/wdjcodes/magpie) - Minimalist theme with custom logic to display paths relative to the root of the current `git`. Includes decorators for time, current directory, username\@hostname and `git` status.
*   [mainnika (⭐0)](https://github.com/mainnika/zsh-theme-mainnika/) - Includes decorators for last command exit status and the 1, 5 and 15 minute load averages.
*   [maivana (⭐2)](https://github.com/nylo-andry/zsh-themes) - Includes `kubectl` context, `git` status decorations.
*   [majemoji (⭐1)](https://github.com/metalogica/majemoji) - Adds a random emoji to each session's prompt. Includes `git` status decorations.
*   [malev (⭐0)](https://github.com/mvinan/malev-zsh-theme) - Has minimalist and normal variants. Includes decorators for hostname, directory, `git` status and the last command's exit status.
*   [mantis (⭐0)](https://github.com/dann254/mantis-zsh-theme) - Minimal theme with `git` status and information decorators.
*   [materialshell (⭐847)](https://github.com/carloscuesta/materialshell) - A [material design](https://material.io/guidelines/style/color.html) theme for your shell with a good contrast and color pops at the important parts. Designed to be easy on the eyes.
*   [matrix (⭐6)](https://github.com/pot-code/matrix-zsh-theme) - Variant of [powerlevel9k (⭐13k)](https://github.com/bhilburn/powerlevel9k) styled to look like something in the Matrix movie trilogy. Includes `git` status decorations.
*   [matter (⭐1)](https://github.com/mrobillard/matter-zsh-theme) - Shows `git` status, AWS vault role, background jobs, exit code of last command & hostname.
*   [mau (⭐3)](https://github.com/vichargrave/mau) - A ZSH theme with a cat twist. Includes `git` status decorations. Based on the [kphoen (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kphoen.zsh-theme) and [smt (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/smt.zsh-theme) themes.
*   [mbolis (⭐0)](https://github.com/mbolis/mbolis-zsh-theme) - Includes `git` decorations, changes prompt color if root user, active jobs, and [jenv (⭐6.1k)](https://github.com/jenv/jenv) integration.
*   [mdmini (⭐2)](https://github.com/MarioDena/MDmini) - Includes `git` and `ssh` status decorations.
*   [meganerd (⭐1)](https://github.com/meganerd/meganerd-zsh/) - Inspired by jonathan. Includes decorators for `git` status, user\@hostname, current directory, time and the last command's exit status.
*   [megaprompt (⭐4)](https://github.com/willghatch/zsh-megaprompt) - A maximalist prompt including keyboard mode, ownership info, and other contextual info, with λ as the prompt character. Requires the [hooks (⭐60)](https://github.com/willghatch/zsh-hooks) plugin.
*   [metalmajor (⭐0)](https://github.com/deblauwetom/metalmajor-zsh-theme) - Includes `git` status decorations, shows exit code of last command if nonzero.
*   [mexassi (⭐2)](https://github.com/Mexassi/mexassi-zsh-theme) - Checks the `/sys/class/power_supply` folders to determine if the system is installed on a laptop or desktop machine. Reads the battery percentage grepping acpi command and displays it in the prompt. Includes `git` decorations.
*   [mh-fzj (⭐1)](https://github.com/mh-firouzjaah/mh-fzj-oh-my-zsh-theme-v1) - Includes `rvm` and `git` status decorations.
*   [michaelpass (⭐1)](https://github.com/michaelpass/michaelpass.zsh-theme) - POSIX-friendly cross-platform [alanpeabody (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/alanpeabody.zsh-theme) mod w/ convenient timestamps and full git/ruby support.
*   [michelebira (⭐0)](https://github.com/mortinger91/michelebira) - Variation of the [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme. Includes decorators for `git` status, username, current directory and the return code of the last command run.
*   [midin (⭐0)](https://github.com/xlshiz/midin) - Works well on dark terminal background, includes `git` status decorations.
*   [mike-was-here (⭐0)](https://github.com/leguim-repo/mike-was-here-theme/) - Minimalist, includes `git` status decorations.
*   [milight (⭐0)](https://github.com/frodoslaw/milight-zsh) - Minimal ZSH prompt with `git` status display, works best with dark terminal backgrounds.
*   [mindful-space (⭐2)](https://github.com/syndbg/mindful-space-zsh-theme) - ZSH theme with space in mind.
*   [mini-simple (⭐1)](https://github.com/ysl2/mini-simple-zsh-prompt) - Minimalist. Includes `vcs` status decorations.
*   [minima (⭐3)](https://github.com/Brolly0204/zsh-minima) - Includes `git`, `node`, `golang`, `yarn`, `php`, `docker` and `python` status decorations.
*   [minimal (glsorre) (⭐0)](https://github.com/glsorre/minimal/) - A minimal asynchronous ZSH theme optimized for use with the [Fira Code (⭐79k)](https://github.com/tonsky/FiraCode) font and the [Solarized Light](https://ethanschoonover.com/solarized) terminal theme.
*   [minimal (subnixr) (⭐264)](https://github.com/subnixr/minimal) - Minimal yet feature-rich theme.
*   [minimal-improved (⭐27)](https://github.com/gdsrosa/minimal_improved) - Theme for dark terminals, includes `git` decorations in the right-side prompt.
*   [minimal-os (⭐2)](https://github.com/nkurata/zsh-theme) - A minimalist prompt with helpful `git` status and system-specific decorators.
*   [minimal-terminal (⭐60)](https://github.com/Lissy93/minimal-terminal-prompt) - Includes decorators for username\@host, current directory, `git` information and the last command's exit code.
*   [minimal2 (⭐12)](https://github.com/PatTheMav/minimal2) - A minimal and extensible ZSH theme. Forked from [subnixr's original (⭐264)](https://github.com/subnixr/minimal) and adapted for [Zimfw (⭐4.1k)](https://github.com/zimfw/zimfw).
*   [minimalx (⭐1)](https://github.com/lknix/zsh-theme-minimalx) - Inspired by kolo theme from oh-my-zsh.
*   [mint (⭐0)](https://github.com/FalconLee1011/mint-zsh-theme) - Includes decorators for current directory, whether running on a laptop or a desktop, and `git` status.
*   [mira (⭐0)](https://github.com/mbStavola/mira) - A modified [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) with time info and a simplified start prompt.
*   [mirage (⭐1)](https://github.com/robin-pfeiffer/ohmyzsh-mirage-theme/) - Includes prompt decorations for `git` status, last command exit code, whether `sudo` timestamp file is present and current active Python virtual environment.
*   [miramare (⭐1)](https://github.com/franbach/oh-my-deepin-miramare) - Includes `git` status decorations. Works best with [Deepin Terminal](https://www.deepin.org/en/original/deepin-terminal/).
*   [misa (⭐1)](https://github.com/misalabs/misa.zsh-theme) - Misalabs' ZSH theme.
*   [mixed (⭐0)](https://github.com/dekermendzhy/mixed-zsh-theme) - Optimized for dark backgrounds.
*   [mnml (⭐9)](https://github.com/mnml-theme/prompt) - Minimal theme with `git` status decorations.
*   [mochi (⭐6)](https://github.com/mochidaz/zsh-themes) - Simple theme, designed to resemble rust main function. Includes `git` and `hg` status decorations.
*   [mochi2 (⭐6)](https://github.com/mochidaz/zsh-themes) - Minimalist theme. Includes `git` and `hg` status decorations.
*   [modern (⭐0)](https://github.com/BadRat-in/zsh-modern-theme) - Automatically adapts to light and dark terminal themes. This theme provides a clean and informative prompt with git integration, command execution time, and a beautiful rainbow directory path.
*   [moderno (⭐1)](https://github.com/obrassard/moderno-zsh) - A simple and modern ZSH theme inspired by the [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme from Oh-My-ZSH. Includes `git` status decorations.
*   [modesty (⭐1)](https://github.com/saravanabalagi/zsh-theme-modesty) - A clean and modest ZSH theme with `condaenv`, `virtualenv` and `git` status decorations displayed neatly right aligned. Requires [condaenv (⭐1)](https://github.com/saravanabalagi/zsh-plugin-condaenv) plugin.
*   [molokai-powerline (⭐10)](https://github.com/prikhi/molokai-powerline-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874).
*   [momoyo (⭐1)](https://github.com/momoyo-droid/momoyo-zsh-theme) - Reminiscent of powerline. Includes decorations for `git` status, username, and working directory.
*   [monsi (⭐0)](https://github.com/rafa-wine/monsi_oh-my-zsh_theme) - Includes `git` status, last command exit status and current directory decorators.
*   [moonlight (⭐0)](https://github.com/vosalt/moonlight-zsh-theme) - Dark lunar aesthetic with celestial tokens for `git` status.Heavily inspired by the [daivasmara (⭐84)](https://github.com/Daivasmara/daivasmara.zsh-theme/tree/master) theme.
*   [moon-lite (⭐0)](https://github.com/anotherlusitano/moon-light) - Minimalist. Includes decorators for `git` status, current directory and the exit status of the last command run.
*   [moonbloom (⭐2)](https://github.com/moonbloom-theme/zsh) - Adapts to the color scheme of your terminal emulator. Includes decorators for current directory and `git` status.
*   [moonline (⭐16)](https://github.com/kagamilove0707/moonline.zsh) - Minimal but easily extensible prompt.
*   [moux (⭐0)](https://github.com/gagbo/moux) - Works well with a dark terminal background, includes `git` decorations in `RPROMPT`.
*   [msys2 (⭐0)](https://github.com/water-logger/MSYS2-Theme/) - Inspired by MSYS2. Includes decorators for user\@host, `git` status and the current directory.
*   [mu (⭐4)](https://github.com/seamile/mu-zsh-theme) - Improves display of multiple `git` statuses. Inspired by [lambda mod theme (⭐467)](https://github.com/halfo/lambda-mod-zsh-theme). Requires a powerline-compatible font.
*   [multi-shell-repo-prompt (⭐13)](https://github.com/dotcode/multi-shell-repo-prompt) - Provides useful information (in your prompt) about the repository that you are in. It currently works for [Git](https://git-scm.com/) and [Mercurial](https://www.mercurial-scm.org/), under [ZSH](https://en.wikipedia.org/wiki/Zsh) as well as [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
*   [multiline (⭐24)](https://github.com/jan-auer/zsh-multiline) - Powerline-esque theme based on [agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme).
*   [muslim (⭐6)](https://github.com/nksoff/muslim) - A simple minimal ZSH prompt theme.
*   [musy (⭐0)](https://github.com/THaGKI9/musy-zsh-theme) - Inspured by muse theme. Includes `git` status decorations.
*   [my (⭐0)](https://github.com/fabiendelpierre/my-zsh-theme/) - Variant of [kolo (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#kolo).
*   [myzsh (⭐0)](https://github.com/MaxUlysse/myzsh) - Maxime Garcia's myzsh theme.
*   [mzt (⭐1)](https://github.com/honbey/mzt) - Sets up `LS_COLORS`, colorizes `diff` and includes `git` status and current working directory decorations.
*   [nablaman (⭐0)](https://github.com/kokkonisd/nablaman-zsh-theme) - Similar to [powerlevel10k (⭐49k)](https://github.com/romkatv/powerlevel10k). Includes decorators for the last command's exit status, user\@hostname, `git` status and the current directory. Works best with a dark terminal theme.
*   [nanika (⭐1)](https://github.com/justforuse/nanika-zsh-theme/) - Optimized variant of [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell). Includes `git` status decorations.
*   [nanofish (⭐3)](https://github.com/tweekmonster/nanofish) - Adds fish-style directory prompt to nanotech theme.
*   [nbrylevv (⭐0)](https://github.com/nbrylevv/nbrylevv-zsh-theme) - Minimalist theme with text `git` status decorations.
*   [nctu (⭐5)](https://github.com/leovincentseles/nctu.zsh-theme) - Lightweight theme with an emphasis on speed. Includes `git` status decorations.
*   [neewbie (⭐0)](https://github.com/neewbee/neewbee.zsh-theme) - Minimal theme with `git` decorations. Based on [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell).
*   [neo++](https://gitlab.com/migoa/neo) - Simpler, more intuitive, and less clustered than the one above.
*   [neon-potato (⭐0)](https://github.com/algosuna/neon-potato) - Colorful and minimalist theme. Includes `git` decorations.
*   [neon (⭐13)](https://github.com/sahariko/neon) - A pretty and minimal ZSH theme with `git` decorations.
*   [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) - A prompt theme for ZSH which uses [Nerd Fonts (⭐57k)](https://github.com/ryanoasis/nerd-fonts).
*   [nerdp (⭐3)](https://github.com/joknarf/nerdp) - Nerd powerline-style prompt. Requires a nerd font. Includes decorators for `git` status, username\@hostname, current directory, Python virtualenv, filesystem usage check, 1 minute CPU load, available memory and the time.
*   [nerdps1 (⭐11)](https://github.com/joknarf/nerdps1) - Reminiscent of powerline. Requires a nerd font. Includes decorators for user\@hostname, `git` information, truncated current directory, python virtualenv, exit status of last command run and the time.
*   [nescalante (⭐2)](https://github.com/nescalante/zsh-theme) - Optimized for dark terminal backgrounds, includes `git` decorations.
*   [netmask (⭐0)](https://github.com/swomf/netmask-zsh-theme) - Termux-first theme. Includes decorators for ip address, full path to current directory, `git` status and python virtual environment.
*   [neurosimple (⭐1)](https://github.com/davidsierradz/neurosimple-oh-my-zsh-theme) - Includes `git` decorations and `vi`-mode indicator.
*   [newt (⭐11)](https://github.com/softmoth/zsh-prompt-newt) - Fat & fast theme – beautiful inside and out, styled segments done right. Extremely customizable, includes `git`, username, execution time, directory, background jobs and edit mode decorations.
*   [newton (⭐0)](https://github.com/sebastienfilion/zsh.newton) - Includes `git` status and external IP address decorations.
*   [nextbike (⭐4)](https://github.com/meierjan/nextbike-zsh-theme) - A very basic theme which just features an macOS bike icon.
*   [nidoranarion (⭐0)](https://github.com/NicolaiRuckel/nidoranarion) - Colorful, shows `git` status decorations.
*   [nikitakot (⭐0)](https://github.com/nikitakot/nikitakot-oh-my-zsh-theme) - Small and simple oh-my-zsh theme. Shows current directory and 2 directories behind, `git` and `nodejs` status decorations.
*   [ninik (⭐3)](https://github.com/NimaNikfar/ninik-zsh-theme) - Inspired by [agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme) and [ubunly (⭐26)](https://github.com/alejandromume/ubunly-zsh-theme). Includes decorators for OS, current directory, python virtualenv and `git` status. Requires a Nerd Font or Powerline-patched font.
*   [niotna (⭐3)](https://github.com/niotna/niotna-theme) - Includes decorators for `git` status and current directory. Customizable colors.
*   [nknu (⭐0)](https://github.com/aanc/oh-my-zsh-nknu-theme) - A simple oh-my-zsh theme.
*   [nmaxcom (⭐2)](https://github.com/nmaxcom/nmaxcom-zsh-theme) - Minimalist ZSH theme with `git` status decorations.
*   [node (⭐68)](https://github.com/skuridin/oh-my-zsh-node-theme) - oh-my-zsh's Node.js theme, broken out to make it easier to use with other plugin managers.
*   [nodeys (⭐37)](https://github.com/marszall87/nodeys-zsh-theme) - Based on the ys theme, with added Node.js version (from NVM plugin).
*   [noon (⭐0)](https://github.com/silky/noon.zsh-theme) - Has light and dark variants, shows `git` information.
*   [nord (⭐11)](https://github.com/TyWR/Nord-zsh) - Includes `git` status decorations and displays the active conda environment.
*   [normanius (⭐0)](https://github.com/normanius/normanius-zsh-theme) - Derived from [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme). Includes decorators for `git` status, `user@host`, python `virtualenv`, and ruby `rvm` version.
*   [nostalgia (⭐0)](https://github.com/skippyr/nostalgia) - Minimalist theme inspired by Windows CMD prompt. Includes decorators for user\@hostname, `git` status, current directory and python virtualenv.
*   [nothing (⭐32)](https://github.com/eendroroy/nothing) - Lightning fast and really simple because it has almost nothing in it.
*   [nova (⭐0)](https://github.com/body20002/nova) - Includes `git` status decroations. Overrides `LS_COLORS` and `LSCOLORS` settings.
*   [nox (⭐10)](https://github.com/kbrsh/nox) - Dark theme, displays the current working directory and git status.
*   [nt9 (⭐31)](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme) - A clean, distraction free and `git` focused development theme. Shows path relative to `git` root (or `~` when outside `git` repo), time since last commit, current SHA, branch and branch state.
*   [nunorc (⭐0)](https://github.com/nunorc/nunorc.zsh-theme) - Minimalist theme, works well on dark backgrounds. Includes `git`, `mercurial` and `svn` satus decorations.
*   [nuqle (⭐2)](https://github.com/Nuqlear/nuqlezsh.zsh-theme) - A simple theme for prezto and oh-my-zsh.
*   [nuts (⭐5)](https://github.com/rafaelsq/nuts.zsh-theme) - Minimalist theme, includes `git` status decorations and time.
*   [oblong (⭐2)](https://github.com/Ansimorph/oblong) - Simple `bash`-inspired theme based on [gitster (⭐67)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [basher](https://gitlab.com/Spriithy/basher). Includes status decorations to show if user is root, the exit status of last command run, `git` branch and its clean/dirty status.
*   [odie (⭐0)](https://github.com/masterodie/zsh-theme-odie/) - Works well on a dark background. Includes `git` status, python virtualenv and `vi`-mode status decorations.
*   [odin (⭐72)](https://github.com/tylerreckart/odin) - Odin is a `git`-flavored ZSH theme.
*   [odra (⭐2)](https://github.com/ErikBenavides/odra.zsh-theme) - Colorful, works well on dark backgrounds. Includes decorators for `git` status, current directory, username and exit status of the last command.
*   [oh-flowers (⭐1)](https://github.com/Flower7C3/oh-flowers-zsh-theme) - Multiline theme with `git` decorations.
*   [oh-my-git (⭐3.7k)](https://github.com/arialdomartini/oh-my-git) - An opinionated prompt for bash and ZSH.
*   [oh-my-posh](https://ohmyposh.dev/) - Not ZSH-specific, but very nice and works with ZSH. Allows you to use the same configuration for prompts in all shells.
*   [oh-my-via (⭐41)](https://github.com/badouralix/oh-my-via) - Theme for ZSH which mainly forks the historical theme used on VIA servers.
*   [ohelm (⭐0)](https://github.com/devopsguy/ohelm-zsh-theme) - Includes decorators for current directory, `git` status, exitatus of last command and `kubectl` context.
*   [ohh IP (⭐0)](https://github.com/Ohh-Raven/ohh_IP) - A theme designed for CTFs. Includes decorators for ip address and `git` status.
*   [ohmypc (⭐2)](https://github.com/joselpadronc/OhMyPC) - Works well with dark terminal windows. Includes `git` decorations.
*   [om (⭐1)](https://github.com/sirshikher/zsh-om) - Minimal theme, works with dark backgrounds, includes `git` status decorations.
*   [omszt (⭐2)](https://github.com/MU001999/omszt) - Minimalist theme with `git` decorations.
*   [omuse (⭐0)](https://github.com/ouuan/omuse-zsh-theme) - Based on Oh-My-ZSH's [amuse (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme). Has decorations for `git` status, time, absolute pwd, RAM usage, time used by last command, and last command exit status.
*   [operator (⭐5)](https://github.com/nivv/operator-theme) - Clean and simple theme, works best with [Menlo for Powerline (⭐791)](https://github.com/abertsch/Menlo-for-Powerline).
*   [ortiz (andres-ortizl) (⭐3)](https://github.com/andres-ortizl/ortiz-zsh-theme) - Fork of [eriner (⭐22)](https://github.com/zimfw/eriner) with decorations for the interval between commands and k8s context.
*   [ortiz (guezwhoz) (⭐100)](https://github.com/guesswhozzz/guezwhoz-zsh-theme) - Simplified fork of [eriner (⭐22)](https://github.com/zimfw/eriner) with `git` status, `kubectl` context and elapsed time decorations.
*   [osx2 (⭐2)](https://github.com/RizkiIqbal02/zsh-theme-custom) - Based on archcraft. Minimalist. Includes decorator for current directory.
*   [otter (⭐2)](https://github.com/OtterArkar/otter-zsh/) - Otter-themed theme with `git` status, user\@host and current directory decorators.
*   [outer-space (⭐2)](https://github.com/skippyr/outer-space) - Includes decorators for user\@hostname, active python virtual environment, current directory and `git` status.
*   [owczarczak (⭐0)](https://github.com/ThemysciraData/owczarczak.zsh-theme) - Inspired by bira, dieter and [fino-time (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fino-time.zsh-theme). Includes `venv` and vcs status decorations.
*   [owi (⭐0)](https://github.com/owitech/zsh-theme/) - Minimalist theme with `git` status decorations.
*   [owiewestside (⭐1)](https://github.com/owenstranathan/owiewestside.zsh-theme) - Includes `git` status and virtualenv information.
*   [oxide (⭐1.5k)](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) - A Minimalistic and Dark ZSH theme.
*   [ozono (⭐9)](https://github.com/sfabrizio/ozono-zsh-theme) - 🌏 OZ0NO - Let's Breathe a clean ZSH.
*   [p9k-theme-pastel (⭐4)](https://github.com/iboyperson/p9k-theme-pastel) - A theme for the [powerlevel10k (⭐49k)](https://github.com/romkatv/powerlevel10k) prompt that puts an emphasis on simplcity while still getting important information across.
*   [pacmandoh (⭐3)](https://github.com/pacmandoh/omz-theme-pacmandoh) - Enhance your command-line with a sleek theme. Includes decorators for `git` integration, permissions feedback, Python environment support, and dynamic prompts, all in one, customizable with a single installation script and selectable styles.
*   [pad (⭐4)](https://github.com/eproxus/pad.zsh-theme) - A concise and colorful oh-my-zsh theme.
*   [page (⭐2)](https://github.com/SLIB53/page-zsh-theme) - A simple theme with VCS support. The prompt shows 1 level of the current working directory, branch, and a color coded curved fat arrow.
*   [palenight (jenssegers) (⭐13)](https://github.com/jenssegers/palenight.zsh-theme) - Allows display of host information, includes `git` branch decoration.
*   [palenight (rhklite) (⭐0)](https://github.com/rhklite/palenight_zsh_theme) - Shows detailed `git` status information with icons in the prompt.
*   [panda (⭐0)](https://github.com/davymai/oh-my-zsh-panda-theme) - Includes `git` and `root` status decorations. Best on a dark background.
*   [papercolor (⭐10)](https://github.com/erikschreier/PaperColor-themes) - Color scheme for ZSH, `vim` and `tmux`. Includes `git` status decorations.
*   [paramour (⭐1)](https://github.com/espeon/paramour) - Simple and clean, has decorators for `git` status, username, time, current directory and username. Requires a nerd font in your terminal.
*   [paroape (⭐3)](https://github.com/ParoaPe/ParoaPe-zsh-theme) - Based on [lpha3cho (⭐44)](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters)
*   [parrot-htb (⭐0)](https://github.com/Lloyd-Leo/parrot-htb-zsh-theme) - Includes decorators for current directory, `git` status and username\@hostname.
*   [parrot (⭐13)](https://github.com/trabdlkarim/parrot-zsh-theme) - Based on Parrot OS bash theme. Includes decorators for user\@host, `git` information, exit status of last command, time and current directory.
*   [passion (⭐313)](https://github.com/ChesterYue/ohmyzsh-theme-passion) - Includes decorations for current time, `git` status, last command run time in milliseconds, and the exit status of the last command. Requires coreutils on macOS.
*   [pastel (⭐6)](https://github.com/iboyperson/pastel) - A ZSH theme inspired by [sugar-free (⭐3)](https://github.com/cbrock/sugar-free). Includes `git` decorations.
*   [paulmanjarres (⭐0)](https://github.com/paul-manjarres/paulmanjarres-zsh-theme) - Based on [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme), [agnoster](https://gist.github.com/agnoster/3712874) and [nuts (⭐5)](https://github.com/rafaelsq/nuts.zsh-theme). Includes decorators for current directory, `git` status and the time.
*   [paxton (⭐0)](https://github.com/p1xt4n/ohmyzsh-theme-paxton) - Inspired by powerline. Includes segments for `git` branch, time, last command exit status and current directory. Requires a powerline-compatible font.
*   [pbdevflow (⭐0)](https://github.com/pbarovsky/pbdevflow) - Designed and optimized for use with [Nerd Fonts (⭐57k)](https://github.com/ryanoasis/nerd-fonts). Includes decorators for current directory, `git` status and username.
*   [pbsegments (⭐0)](https://github.com/pbarovsky/pbsegments) -A  minimal and visually appealing custom theme for [oh-my-zsh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh). It features a clean, segment-based prompt, optimized for readability and usability. Includes decorators for `git` status, current directory and username.
*   [pecodez (⭐0)](https://github.com/pecodez/pecodez-zsh-theme) - Optimized for dark terminals. Has decorators for `snyk` version, `node` version, AWS profile, kubernetes context and `git` status.
*   [pedantic (⭐0)](https://github.com/nemeshnorbert/pedantic-zsh-theme) - Customizable colors and output. Includes decorators for detailed `git` information, root status, last command's exit status, user\@host, current directory and the time.
*   [pentest-report (⭐7)](https://github.com/sikumy/ohmy-pentest-report) - Designed for pentesters, offering a clean and efficient prompt to streamline daily tasks during audits and penetration testing. The theme includes decorators for real-time display of the date, time, IP address, current directory, and the result of the last executed command.
*   [persi (⭐3)](https://github.com/persiliao/persi-zsh-theme) - Includes `git`, hostname and current directory decorations. Works with both light and dark backgrounds.
*   [phalanx (⭐0)](https://github.com/d-danilov/phalanx-zsh-theme) - Minimal theme in the spirit of the [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) and Pure Shell themes.
*   [phi φ (⭐13)](https://github.com/LasaleFamine/phi-zsh-theme) - A clean and simple theme for ZSH inspired and forked from the [Lambda (Mod) ZSH (⭐467)](https://github.com/halfo/lambda-mod-zsh-theme) theme.
*   [pi (⭐107)](https://github.com/tobyjamesthomas/pi) - A minimalist theme with `git` status decorations.
*   [piboy (⭐1)](https://github.com/sflems/piboy-zsh-theme) - A simple and elegant multi-line theme for ZSH. Includes a colourized timestamp, `git` & syntax highlighting, and elevated root theme.
*   [pickaxe (⭐0)](https://github.com/mikhaben/pickaxe-zsh-theme) - Includes decorators for `user@host`, current directory, current time, conda environment, node version and `git` status.
*   [pico (⭐0)](https://github.com/PicoGeyer/zsh-pico-prompt) - Simple prompt modified from [zap-prompt (⭐27)](https://github.com/zap-zsh/zap-prompt) with decorators for `git` information, user\@hostname and working directory.
*   [pifabs (⭐0)](https://github.com/pifabs/pifabs-zsh-theme) - Minimal theme with decorators for `git` status, username, host and working directory.
*   [plain-ui (⭐0)](https://github.com/purveshpatel511/plain-ui) - Minimalist, but includes `git` status decorations.
*   [plain (⭐0)](https://github.com/jimeh/plain.zsh-theme) - A plain and simple theme for ZSH which shows basic `git` information.
*   [planet (⭐0)](https://github.com/borb/planet-zsh) - A slimmed down version of [steef (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) from [oh-my-zsh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh).
*   [plankton (⭐1)](https://github.com/tobiaseichert/plankton-zsh-theme) - Simple, no-frills theme.
*   [plantyhoe (⭐1)](https://github.com/totoroot/plantyhoe.zsh-theme) - Minimalist theme based on a love of plants and apples. Includes `git` status decorations.
*   [platypus (⭐1)](https://github.com/fdv/platypus) - Platypus is a simple and convenient theme for oh-my-zsh used by Frédéric de Villamil.
*   [pog7x (⭐1)](https://github.com/pog7x/pog7x-zsh-theme) - Works with unicode. Includes decorators for `git` information, current directory, last command exit status & execution time, time, virtualenv, nvm, rvm, rust, go, kubernetes context, and elixir.
*   [pointer (⭐1)](https://github.com/gpinkard/pointer-zsh-theme) - Shows working directory, the return status of the last command, and `git` current branch.
*   [polyglot (⭐188)](https://github.com/agkozak/polyglot) - a dynamic prompt for `zsh`, `bash`, `ksh93`, `mksh`, `pdksh`, `dash`, and busybox `ash` that uses basic ASCII symbols (and color, when possible) to show username, whether it is a local or remote `ssh` sesssion, abbreviated path, `git` branch and status, exit status of last command if non-zero, any virtual environment created with `virtualenv`, `venv`, `pipenv`, `poetry`, or `conda`.
*   [poncho (⭐3)](https://github.com/RainyDayMedia/oh-my-zsh-poncho) - RDM's basic oh-my-zsh custom theme.
*   [poor-programmer (⭐0)](https://github.com/vishaltelangre/poor-programmer.zsh-theme) - Programmer's theme with `git` status, ruby version and project path.
*   [powerbash (⭐1)](https://github.com/erikschreier/powerbash-zsh) - Works well with dark terminal backgrounds, includes `git` status decorations.
*   [powerless (⭐74)](https://github.com/martinrotter/powerless) - Tiny & simple pure ZSH prompt inspired by powerline.
*   [powerlevel10k (⭐49k)](https://github.com/romkatv/powerlevel10k) - A fast reimplementation of [powerlevel9k (⭐13k)](https://github.com/bhilburn/powerlevel9k) ZSH theme. Can be used as a drop-in replacement for powerlevel9k, when given the same configuration options it will generate the same prompt, only faster.
*   [powerlevel9k (⭐13k)](https://github.com/bhilburn/powerlevel9k) - Powerlevel9k is a theme for ZSH which uses [Powerline Fonts (⭐26k)](https://github.com/powerline/fonts). It can be used with vanilla ZSH or ZSH frameworks such as [Oh-My-Zsh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh), [Prezto (⭐14k)](https://github.com/sorin-ionescu/prezto), [Antigen (⭐8.2k)](https://github.com/zsh-users/antigen), and [many others (⭐13k)](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions).
*   [powerlevelHipstersmoothie (⭐9)](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - Add-on for [powerlevel9k (⭐13k)](https://github.com/bhilburn/powerlevel9k).
*   [powerline (brucehsu) (⭐11)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) - A two-line version of powerline: one for information, one for input.
*   [powerline (jeremy) (⭐1.2k)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) - Another take on a powerline theme. Nicely configurable, but requires at least a 256 color-capable terminal with a powerline-compatible terminal font.
*   [powerline (syui) (⭐1)](https://github.com/syui/powerline.zsh) - A `git` aware powerline theme.
*   [powerline-cute (⭐32)](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - Based on [bullet-train (⭐2.8k)](https://github.com/caiogondim/bullet-train.zsh).
*   [powerline-go (⭐2.8k)](https://github.com/justjanne/powerline-go) - A beautiful and useful low-latency prompt, written in golang. Includes `git` and `hg` status decorations, exit status of the last command run, current Python virtualenv, whether you're in a [nix](https://nixos.org/) shell, and is easy to extend.
*   [powerline-hs (⭐117)](https://github.com/rdnetto/powerline-hs) - A [Powerline (⭐15k)](https://github.com/powerline/powerline) clone written in Haskell. It is significantly faster than the original implementation, and makes the shell noticeably more responsive.
*   [powerline-pills (⭐20)](https://github.com/lucasqueiroz/powerline-pills-zsh) - Written in Ruby, uses powerline characters to simulate pills with useful information.
*   [powerline-shell (b-ryan) (⭐6.3k)](https://github.com/b-ryan/powerline-shell) - Beautiful and useful prompt generator for Bash, ZSH, Fish, and tcsh. Includes `git`, `svn`, `fossil` and `hg` decorations, Python virtualenv information, and last command exit status.
*   [powerline-shell (banga) (⭐6.3k)](https://github.com/b-ryan/powerline-shell) - A [powerline (⭐2.9k)](https://github.com/Lokaltog/vim-powerline)-like prompt for Bash, ZSH and Fish. Includes decorators for `git`/`svn`/`hg`/`fossil` branch, last command exit status, shortened path to current directory and the current python virtualenv and is easy to customize/extend.
*   [powerline-train (⭐5)](https://github.com/sherubthakur/powerline-train) - A powerline variant.
*   [powerline (⭐130)](https://github.com/carlcarl/powerline-zsh) - A [Powerline (⭐2.9k)](https://github.com/Lokaltog/vim-powerline)-like prompt, based on [powerline-bash (⭐15)](https://github.com/milkbikis/powerline-bash). Displays virtualenv, `git` status information and the exit code of the last command run.
*   [powermore (⭐0)](https://github.com/primejade/powermore-zsh) - Forked from [powerless (⭐74)](https://github.com/martinrotter/powerless). Simple prompt that shows `git` status and current directory.
*   [powerzeesh (⭐0)](https://github.com/sevaho/Powerzeesh) - A Powerline based ZSH theme. It aims for simplicity, showing information only when it's relevant, optimized for speed and look. Inspired by [Agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme) and [Powerline (⭐1.2k)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
*   [pre (⭐48)](https://github.com/leandromatos/pre-theme) - A collection of themes for Sublime Text, Terminal, iTerm 2 and ZSH.
*   [predawn-shell (⭐53)](https://github.com/jamiewilson/predawn-shell) - Theme optimized for dark terminal themes.
*   [prezto\_powerline (⭐116)](https://github.com/davidjrice/prezto_powerline) - Powerline for prezto. Shows git information, RVM version.
*   [prezto-cloud-prompt (⭐1)](https://github.com/klaude/prezto-cloud-prompt) - Prezto port of oh-my-zsh's cloud prompt.
*   [prezto-lambda (⭐0)](https://github.com/nixolas1/prezto-lambda) - Lambda theme (for prezto).
*   [princess (⭐3)](https://github.com/mellypop/princess) - Modeled after [abhiyan.zsh (⭐7)](https://github.com/abhiyandhakal/abhiyan.zsh) with perhaps a bit too much pink and arguably too few emojis. Includes decorators for current directory and `git` status.
*   [probe (⭐5)](https://github.com/probe2k/probe_zsh) - Includes `git` status decorations.
*   [prompt\_blocks (⭐1)](https://github.com/MiloradFilipovic/promptblocks) - A minimal node js + git theme. Includes decorators for `git` status, node version and current directory.
*   [prompt\_j2 (⭐0)](https://github.com/malinoskj2/prompt_j2) - Has a dynamic exit status indicator, can change to two lines dynamically to display context.
*   [prompt-powerline (⭐50)](https://github.com/Valodim/zsh-prompt-powerline) - A fairly heavyweight ZSH prompt, based on the powerline font from the popular eponymous `vim` plugin, which works well for a dark background.
*   [prompt (⭐0)](https://github.com/nathanblair/prompt) - A lightweight prompt consistent across `sh`, `dash`, `ash`, `zsh`, and `pwsh`. Includes `git` status decorations.
*   [promptor (⭐1)](https://github.com/MickaelBlet/Promptor) - Powerline-inspired. Includes decorators for `git` status, username, hostname, working directory and time.
*   [promptus (⭐15)](https://github.com/willeccles/promptus) - Simple, minimalist and configurable shell prompt program in C which can be used to make your prompt the same on any shell. Includes exit code and working directory decorations.
*   [pronto (arzezak) (⭐0)](https://github.com/arzezak/pronto) - A super simple prompt with decorators for the current directory and `git` information.
*   [pronto (jthat) (⭐1)](https://github.com/jthat/zsh-pronto) - Simple and fast theme with `git` decorations and timing information.
*   [prowpt (⭐1)](https://github.com/alpaca-honke/prowpt) - Simple, lightweight, and customizable Powerline-like prompt, with decorators for `git` information, user, hostname, current directory, time and exit status of the last command.
*   [ps1.py (⭐7)](https://github.com/jwodder/ps1.py) - Has `git` status, truncated directory, `chroot` and `virtualenv` prompt decorations.
*   [pskfyi (⭐0)](https://github.com/pskfyi/zsh-theme) - Based on [lambda (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#lambda). Themed for ubuntu but easily tweaked.
*   [punctual (⭐55)](https://github.com/dannynimmo/punctual-zsh-theme) - Easily customizable, influenced by [spaceship (⭐20k)](https://github.com/denysdovhan/spaceship-prompt).
*   [pure-agnoster (⭐4)](https://github.com/yourfin/pure-agnoster) - Mashup of [pure (⭐14k)](https://github.com/sindresorhus/pure) and [agnoster](https://gist.github.com/3712874). Has `git` decorations and works well with both dark and light terminal backgrounds.
*   [pure (⭐14k)](https://github.com/sindresorhus/pure) - A pretty, minimal and fast ZSH prompt. Includes `git` status decorations, prompt turns red if last command failed, username and host decorations when in a remote session or container, and current folder and command when a process is running.
*   [purify (banminkyoz) (⭐355)](https://github.com/banminkyoz/purify) - A simple, fast & cool prompt.
*   [purify (kyoz) (⭐355)](https://github.com/kyoz/purify) - A clean and vibrant theme, best on dark backgrounds. Includes `git` status decorations.
*   [purity (⭐14)](https://github.com/petermbenjamin/purity) - Inspired by the [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme and the [pure (⭐14k)](https://github.com/sindresorhus/pure) prompt.
*   [purpleblood (⭐0)](https://github.com/HFMorais/oh-my-zsh-purpleblood-theme/) - Based on [darkblood (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/darkblood.zsh-theme). Includes decorators for `username@host`, `git` status, and current directory.
*   [purr (⭐0)](https://github.com/mubinben/purr-zsh-theme) - Includes decorators for current directory and `git` status.
*   [purs (⭐254)](https://github.com/xcambar/purs) - A fast [pure (⭐14k)](https://github.com/sindresorhus/pure)-inspired prompt written in [Rust](https://www.rust-lang.org/).
*   [pustelto (⭐0)](https://github.com/Pustelto/shell_theme) - Colorful theme inspired by the [Spaceship (⭐20k)](https://github.com/denysdovhan/spaceship-prompt) theme, includes `git` decorations.
*   [pwn (⭐0)](https://github.com/gh05t-4/pwn-theme) - Includes decorators for user\@host, `git` & `hg` status, ruby version, python virtualenv and current working directory.
*   [pyhack (⭐1)](https://github.com/williamcanin/pyhack) - Works well with dark terminal themes. Shows Python version, Python package version (pyproject.toml) and `git` current branch information.
*   [qi3ber2 (⭐0)](https://github.com/nichus/qi3ber2) - A dark multiline theme. Includes `git`, load average and exit code of last command decorators.
*   [qoomon (⭐2)](https://github.com/qoomon/zsh-theme-qoomon) - Optimized for dark backgrounds, includes `git` information. Theme repo includes iTerm 2 and Terminal color settings.
*   [quewui (⭐1)](https://github.com/kauefontes/oh-my-quewui) - Simple and clean theme optimized for dark terminal themes. Includes decorations for the current time, user, directory and `git` status.
*   [r3-fresh (⭐0)](https://github.com/r3-fresh/r3-fresh-zsh-theme) - Includes decorators for `git` status, current directory, exit status of last command run.
*   [r3nic1e (⭐0)](https://github.com/r3nic1e/r3nic1e) - [Agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme) variant with battery status, `git/hg` status, time, kubernetes context and namespace, non-zero exit code of last command and date decorations. Requires Powerline font.
*   [rabbit (⭐0)](https://github.com/Hera-Moon/My-rabbit-Zsh-Theme) - Optimized for `git`. Requires a terminal program that works with unicode. Includes decorators for `git` status, current working directory and the current virtual environment.
*   [racotecnic (⭐10)](https://github.com/elboletaire/zsh-theme-racotecnic) - Based on af-magic and posh-git.
*   [radius (⭐1)](https://github.com/erikcc02/radius-zsh-theme) - Includes `git` status, username, hostname, and directory decorations, plus [desk (⭐2.5k)](https://github.com/jamesob/desk) support.
*   [rafiki (⭐52)](https://github.com/akabiru/rafiki-zsh) - Adds emojis to your ZSH terminal.
*   [ramiel (⭐0)](https://github.com/aknackd/zsh-themes) - Fork of the [node (⭐68)](https://github.com/skuridin/oh-my-zsh-node-theme).
*   [random-emoji-robbyrussell (⭐2)](https://github.com/parwatcodes/random-emoji-robbyrussell) - Based on [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) and `robbyrussell` themes.
*   [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - Random emoji.
*   [ranger-zoxide (⭐8)](https://github.com/fdw/ranger-zoxide) - Adds [zoxide (⭐26k)](https://github.com/ajeetdsouza/zoxide) support to the [ranger (⭐16k)](https://github.com/ranger/ranger) console file manager.
*   [raspberrysh (⭐0)](https://github.com/MaxMalinowski/raspberrysh) - Includes `git`, python, time, current host and path decorations.
*   [raytek (⭐0)](https://github.com/Raytek/raytek-zsh-theme) - Simple and colorful theme with `git` status decorations.
*   [raz (⭐2)](https://github.com/razman786/ohmyzsh-theme-raz) - Minimal prompt, includes `git` status decorations.
*   [rb (⭐4)](https://github.com/rberenguel/rb-zsh-theme) - Powerline-styled ZSH theme based on [Agnoster](https://gist.github.com/agnoster/3712874), optimized for `git` and solarized terminals. Requires a Powerline-compatible font.
*   [rbjorklin (⭐0)](https://github.com/rbjorklin/rbjorklin-zsh-theme) - Optimized for solarized terminal color schemes, includes `git` status decorations.
*   [redline (⭐1)](https://github.com/DrissTM/redline.zsh-theme) - Minimalist theme. Includes `git` status, time, user.
*   [refined-flower (⭐0)](https://github.com/idaMakelaWork/refined-flower) - Requires a terminal program that can handle emoji. Includes `git` status decorator.
*   [refpx (⭐0)](https://github.com/refpx/refpx-zsh-theme) - Includes `git` status, last command status, user\@hostname and directory decorations.
*   [reggae (⭐0)](https://github.com/nmercado1986/zsh-reggae-theme) - Compresses a lot of information into the prompt with color-coded status decorations.
*   [rei (⭐0)](https://github.com/arturoalviar/rei-zsh-theme) - A simple theme with the first character 零(rei), the number 0. Includes `git` status decorations.
*   [remiii (⭐7)](https://github.com/Remiii/remiii.zsh-theme) - Based on [Agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme), optimized for [solarized (⭐16k)](https://github.com/altercation/solarized) terminal themes.
*   [remolueoend (⭐0)](https://github.com/remolueoend/remolueoend.zsh-theme) - Based on [Agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme), using emojis for tracking `git` context. Only works with [Prezto (⭐14k)](https://github.com/sorin-ionescu/prezto).
*   [renanborgez (⭐2)](https://github.com/renanborgez/ohmyzsh-theme-renanborgez) - Works well on dark backgrounds. Includes decorators for `nvm` and `git` information.
*   [rho (⭐0)](https://github.com/andrii-rieznik/rho-zsh-theme) - Minimalist theme. Includes decorators for `git` status, hostname and current directory.
*   [ribbon (⭐0)](https://github.com/pyjamafish/ribbon-prompt) - Reminiscent of powerline. Includes Python `virtualenv` decorator.
*   [rie (⭐0)](https://github.com/andrii-rieznik/rie-zsh-theme) - Minimalist theme with decorators for username, `git` status and current directory.
*   [rigel (⭐0)](https://github.com/othiagos/rigel-zsh-theme/) - Includes decorators for `git` information, user\@hostname and current directory.
*   [risbow (⭐2)](https://github.com/waddupp00/risbow) - A [risto (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/risto.zsh-theme) inspired ZSH theme with a lolcat like rainbow effect.
*   [ritz (⭐0)](https://github.com/Ritzier/ritz.zsh-theme) - Includes decorators for time, current directory, `git` status, exit status and time used for last command run.
*   [river-dreams (⭐3)](https://github.com/skippyr/river-dreams) - Includes decorators for `git` information, machine's IP address, time, disk usage on `/`, current Python `venv`, current directory, root status, and the last command's exit status.
*   [river (⭐3)](https://github.com/revir/river-zsh-config) - Dark theme with `git` information.
*   [riverside (⭐0)](https://github.com/skippyr/riverside) - A more portable descendent of [River Dreams (⭐3)](https://github.com/skippyr/river_dreams) inspired by robbyrussell and kafeitu. Includes decorators for `git` status, user\@hostname, current directory and the current python virtual environment.
*   [rkj-logik (⭐0)](https://github.com/logik93/rkj-logik.zsh-theme) - Based on omz's [rkj (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/rkj.zsh-theme). Includes decorators for user\@host, current directory, time & date.
*   [rkj-with-conda (⭐0)](https://github.com/cain986/rkj-with-conda-zsh-theme) - Based on omz's [rkj (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/rkj.zsh-theme) and adds conda environment and `git` status decorators.
*   [robbyolivier (⭐1)](https://github.com/YuyeQingshan/robbyolivier) - Based on ideas from the the [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme and the project [zsh-git-prompt (⭐1.7k)](https://github.com/olivierverdier/zsh-git-prompt).
*   [robbyrussell-fullpath (⭐9)](https://github.com/toytag/robbyrussell-fullpath.zsh-theme) - The original [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) with a fullpath in the prompt.
*   [robbyrussell-plus (⭐0)](https://github.com/jackjyq/robbyrussell-plus-zsh-theme) - Based on [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme), adds a hostname decorator.
*   [robbyrussell-WIP (⭐8)](https://github.com/ecbrodie/robbyrussell-WIP-theme) - Decorates the `robbyrussell` theme with output to indicate a **WIP** commit.
*   [rocket (⭐2)](https://github.com/Alexandresl/rocket-zsh-theme) - Minimalist theme, includes `git` and `hg` status decoration.
*   [rougarou (⭐2)](https://github.com/RougarouTheme/rougarou-zsh) - A dark theme.
*   [rounded (⭐3)](https://github.com/daniilty/rounded-zsh-theme) - Includes current directory and `git` status decorations.
*   [roundy (⭐48)](https://github.com/nullxception/roundy) - Fast, cute and roundy theme. Includes decorators for `git` status, current directory and last command execution time. Requires a [Nerd Font (⭐57k)](https://github.com/ryanoasis/nerd-fonts) and a unicode-capable terminal application.
*   [rs (⭐0)](https://github.com/sam-621/rs-zsh-theme) - Includes `git` decorations. Requires unicode capable terminal.
*   [rufus (⭐0)](https://github.com/runarsf/rufus-zsh-theme) - Optimized for dark backgrounds.
*   [rummik (⭐0)](https://github.com/rummik/zsh-theme) - @rummik's theme. Supports [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin), and `git` status information in the prompt.
*   [russtone (⭐2)](https://github.com/russtone/prompt-russtone) - Inspired by [pure (⭐14k)](https://github.com/sindresorhus/pure) and [sorin (⭐14k)](https://github.com/sorin-ionescu/prezto). Includes `git` status decorations.
*   [ruweird (⭐0)](https://github.com/ruweird/ruweird.zsh-theme) - Minimalist. Has decorators for `git` status and current directory. Shows an umbrella with raindrops and exit code of the last command if non-zero.
*   [rwahasugui (⭐0)](https://github.com/rafawhs/rwahasugui.zsh-theme/) - Includes decorators for `git` information, current time, current working directory and active python  virtualenv.
*   [ryner (⭐1)](https://github.com/DoctorRyner/ryner-zsh-theme) - Colorful theme, includes `git` decorations and the current directory.
*   [rzh (⭐2)](https://github.com/patwhatev/rzh) - Theme with `git` states indicated by emojis.
*   [s1ck3r (⭐1)](https://github.com/pseifer/s1ck3r) - Sleek, transient and space-efficient. Includes decorators for `vi`-mode, elevated permissions, last command exit status, if background jobs are running, working directory and `git` status,
*   [s1ck94 (⭐5)](https://github.com/zimfw/s1ck94) - Fork of the (first deprecated, now extinct) minimal prompt by S1cK94. Shows whether user is root, background job status, vi-mode, exit status of last command, and `git` status decorations.
*   [s7c (⭐0)](https://github.com/Samega7Cattac/s7c.zsh-theme) - Works well with dark backgrounds. Includes `git` status decorations.
*   [sailormoon (⭐0)](https://github.com/Domanowska/zshSailorMoonThemes) - A collection of Sailor Moon themed themes.
*   [samshell (⭐1)](https://github.com/samuelb/samshell) - A minimalist ZSH theme with `git`, kubernetes and python virtualenv decorations.
*   [saraiva (⭐4)](https://github.com/ruisaraiva19/saraiva-theme) - Includes `git` status decorations, works well on a dark terminal background.
*   [sashimi (⭐0)](https://github.com/simonmader17/sashimi-zsh-theme) - Includes decorators for `git` status and the exit status of the last command run.
*   [saturn (⭐6)](https://github.com/gantoreno/saturn-prompt) - A soft & minimalistic prompt for those who love space and want to have a bit of it on their terminal, featuring cool emojis & highly customizable prompt elements (such as icons, colors, time format, and more).
*   [savior (⭐6)](https://github.com/Savecoders/Savior-zsh-theme) - Minimalist theme with decorators for current directory, exit status of last command run and `git` status.
*   [schminitz-v2 (⭐0)](https://github.com/mashdots/schminitz-v2) - Shows decorators for `git` status, `user@host` information, the exit status of last command, and whether running as root.
*   [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - Shows if `vim` is running in the background when using `:sh` command.
*   [scythe (⭐0)](https://github.com/kostoskistefan/scythe) - Powerline-reminiscent theme. Includes `git`, last command exit status and directory decorations.
*   [sdt (⭐0)](https://github.com/sdlea/omz-theme-sdt) - Includes decorators for current directory and `git` status.
*   [searocket (⭐1)](https://github.com/dk949/searocket/) - Slimmed down version of [spaceship (⭐20k)](https://github.com/denysdovhan/spaceship-prompt). Includes decorators for working directory, last command exit code, user, background jobs, `bun`, `d`, elm, go, nodejs, python, zig and `git` status. Requires `D` build chain.
*   [seashell (⭐28)](https://github.com/jottenlips/seasonal-zshthemes) - Minimal theme with sea-inspired emoji decorations. Includes `git` status decorations.
*   [seeker (⭐47)](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - This theme uses many special unicode characters to be fancy, but it may cause some problems without well supported fonts.
*   [seltzer (⭐0)](https://github.com/GrantSeltzer/seltzer.zsh-theme) - Inspired by the dieter theme, uses color-coding to provide information.
*   [senpai (⭐11)](https://github.com/hiroru/senpai-zsh) - Clean prompt theme for Devops. Includes decorators for `git` status, the kubernetes context, AWS profile, GCP project and Azure active cloud.
*   [sensa (⭐0)](https://github.com/miccou/sensa-theme) - Includes decorators for `git` status, GitHub username and current directory.
*   [sepshell (⭐17)](https://github.com/sepehr/sepshell) - Clean and minimal ZSH theme based on the old lost taybalt theme, with `git` bisecting/merging/rebasing modes and configurable prompt symbols.
*   [seti\_UX (⭐2)](https://github.com/ginfuru/iTerm-Seti_UX) - A simple oh-my-zsh-compatible theme with a corresponding iTerm 2 color scheme.
*   [sfz (⭐1)](https://github.com/mreinhardt/sfz-prompt.zsh) - An evolution of lean prompt which itself is a rewrite of pure.
*   [shades of purple (⭐8)](https://github.com/nmcc1212/shades-of-purple-windows-terminal/) - Purple theme for Windows terminal that is reminiscent of [powerline (⭐1.2k)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
*   [shadow (⭐2)](https://github.com/agentshadow/shadow-zsh-theme) - Includes `git` status, directory, host name, username and time decorations.
*   [shayan (⭐6)](https://github.com/shayanh/shayan-zsh-theme) - Simple theme with `git` status decorations.
*   [shelby (⭐194)](https://github.com/athul/shelby) - Fast, lightweight and minimal prompt written in pure `golang`. Includes decorations for last command exit status, `git` status and the current working directory.
*   [shellder (⭐295)](https://github.com/simnalamburt/shellder) - Minimal theme with a `git` branch decorator. Requires a Powerline-compatible font.
*   [shichi (⭐0)](https://github.com/arturoalviar/shichi-zsh-theme) - A simple theme with the first character being 七(shichi/nana), the number 7. The primary color is red with a yellow accent. Includes `git` status decorations.
*   [shiftys (⭐0)](https://github.com/shifty0g/shiftys-zsh-theme/) - Tweaked version of the kali theme.
*   [shiko (⭐1)](https://github.com/regarager/shiko-prompt) - Minimalist prompt with decorators for VCS information and current directory.
*   [shini (⭐0)](https://github.com/bashelled/shini) - A tiny theme that just shouts out small. Includes directory, username, hostname, time and `git` decorations.
*   [shinkansen (⭐1)](https://github.com/MRZ07/shinkansen.zsh-theme) - A fast, customizable and easily extended theme. Includes decorators for rhw python version in the active virtualenv, current ruby version if you're using `chruby`, current Node.js version, current java version, current go version, current perl version if using `chperl`, current elixir version, `git` status, time, current directory, exit code and execution time of the last command, and an optional custom message. Requires a powerline-compatible font.
*   [shirnschall (⭐0)](https://github.com/shirnschall/shirnschall-zsh-theme) - Includes `git` status and `user@hostname` decorations.
*   [shiro (arturDobrowolski) (⭐0)](https://github.com/ArturDobrowolski/shiro-zsh-theme) - Includes decorators for current directory, `git` status, and exit status and execution time of last command run.
*   [shiro (shirozuki) (⭐0)](https://github.com/shirozuki/shiro-zsh-theme) - Includes decorators for current directory, `git` status and execution time and exit status of last command run.
*   [shocm (⭐0)](https://github.com/ericvanjohnson/shocm-zsh-themes) - Forked from [sixlive (⭐4)](https://github.com/sixlive/sixlive-zsh-theme). Has `git` decorations.
*   [short-ys (⭐0)](https://github.com/OREOmini/short-ys-zsh-theme) - Based on the [ys (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) theme. Includes `git` and `hg` status decorations.
*   [shrikant (⭐0)](https://github.com/shr1k4nt/shrikant_zsh_theme) - Includes `git` decorations.
*   [shrug (⭐4)](https://github.com/to-var/shrug-zsh-theme) - Inspired by [beer-theme (⭐3)](https://github.com/tcnksm/oh-my-zsh-beer-theme), includes `git` status and current directory decorations.
*   [shuttle (⭐1)](https://github.com/Pandademic/Shuttle/) - Written in `golang`. Has decorators for OS, user, current directory, and the exit code of the last command run.
*   [siegerts (⭐0)](https://github.com/siegerts/zsh-theme) - Includes `git` status decorations in right prompt.
*   [silver (⭐474)](https://github.com/reujab/silver) - A cross-shell customizable powerline-like prompt heavily inspired by [Agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme). A faster rust port of [bronze (⭐50)](https://github.com/reujab/bronze). Requires [Nerd Fonts (⭐57k)](https://github.com/ryanoasis/nerd-fonts). Very configurable, includes `git` status decorations.
*   [simpalt (⭐2)](https://github.com/m-lima/simpalt) - An information-rich small-footprint theme for ZSH based on [Agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme).
*   [simpl (⭐0)](https://github.com/MrNeoTr1n0/simplzshell) - Minimalist theme focusing on elegance and simplicity. Decorators for root status, current directory and `git` status.
*   [simple-zsh-catppuccin (⭐0)](https://github.com/ezswan/simple-zsh-catppuccin) - Based on the [Catppuccin Mocha](https://catppuccin.com/) color scheme, adapted from the [Dracula (⭐279)](https://github.com/dracula/zsh) theme foundation. This theme features a simple and functional prompt with support for git status, time display, context, and directory information, enhanced with hex color support discovered by ezswan.
*   [simple (daopengz) (⭐0)](https://github.com/DaopengZ/simple-zsh-theme) - Works well with both light and dark terminal themes. Includes `vcs`, `username` and `path` decorations.
*   [simple (drNoob13) (⭐1)](https://github.com/drNoob13/SimpleZshTheme/) - Includes decorators for python virtual environment, `git` status and current directory.
*   [simple (pavdmyt) (⭐4)](https://github.com/pavdmyt/simple-oh-my-zsh-theme) - Minimalist theme based on [robbyrussel (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) that embeds `git` status information in iTerm's window title bar instead of using space in the prompt.
*   [simple (rkitover) (⭐2)](https://github.com/rkitover/sh-prompt-simple) - A simple, lightweight, and nice looking prompt that runs quickly even in very slow shells like MSYS2, Cygwin and WSL. It shows decorations for the short name of the current environment (distribution, OS, etc.) the `git` branch when in a `git` checkout, as well as the last command exit status (green checkmark for success and red X mark for non-zero exit).
*   [simple (savecoders) (⭐6)](https://github.com/Savecoders/simpleTheme-zsh-theme) - Simple and minimalist theme with `git`, `username` and execution status decorations.
*   [simple (tourcoder) (⭐0)](https://github.com/tourcoder/simple.zsh-theme) - Minimalist prompt, includes `git` status decorations.
*   [simple (yhiraki) (⭐0)](https://github.com/yhiraki/zsh-simple-prompt) - Minimal prompt, doesn't require special fonts.
*   [simple-agnoster (⭐3)](https://github.com/iwat/simple-agnoster.zsh-theme) - Powerline-inspired simple theme with `git` decorations.
*   [simple-chack (⭐0)](https://github.com/chack93/simple-chack.zsh-theme) - Works well with solarized terminal color scheme. Includes `git` status decorations.
*   [simple-git (⭐0)](https://github.com/BazaJayGee66/simple-git-theme) - Minimalist theme inspired by [gitstatus (⭐5)](https://github.com/kimyvgy/gitstatus-zsh-theme). Includes `git` decorations.
*   [simple-yet-beautiful (⭐0)](https://github.com/mathiasmoeller/simple-yet-beautiful-zsh-theme) - Minimalist theme. Includes `git` status and `user@host` prompt decorations.
*   [simplezsh (⭐2)](https://github.com/fr0zn/simplezsh) - Minimal theme with `git` info display.
*   [simply-perfect (⭐0)](https://github.com/SetOfAllSets/simply-perfect-zsh-theme/) - Reminiscent of Powerline and Bullettrain. Includes decorators for `git` status, current directory, last command exit status, current time and username.
*   [sinon (⭐0)](https://github.com/k-kinzal/oh-my-zsh-sinon-theme) - k-kinzal's sinon theme. Includes `git` status decorations.
*   [sit (⭐0)](https://github.com/svensen/sit.zsh-theme) - Minimalist theme with `git`, command exit status and path decorations.
*   [sixlive (⭐4)](https://github.com/sixlive/sixlive-zsh-theme) - This theme has a unique directory listing. When inside a `git` project, the directory display is scoped to the current repository root.
*   [sk9 (⭐0)](https://github.com/skeiter9/sk9-zsh) - Skeiter9's ZSH theme.
*   [skeletor-syntax (⭐17)](https://github.com/ramonmcros/skeletor-syntax) - Theme collection for Atom, Prism and ZSH inspired by Skeletor from He-Man and the Masters of the Universe.
*   [skgeek (⭐0)](https://github.com/skippyr/skgeek) - Includes decorators for hostname, directory and `git` branch.
*   [skiff (⭐0)](https://github.com/xiaoshihou514/skiff) - Lightweight ZSH theme with `git` status and current directory decorators.
*   [skill (asafaeirad) (⭐15)](https://github.com/ASafaeirad/oh-my-zsh-skill-theme) - Includes decorations for working directory, `git` working branch, working directory status and tracking branch status.
*   [skill (frontendmonster) (⭐15)](https://github.com/frontendmonster/oh-my-zsh-skill-theme) - Optimized for a dark terminal, displays `git` status decorations.
*   [skondrashov (⭐2)](https://github.com/sergkondr/skondrashov-zsh-theme) - Minimalist. Includes decorators for `git` status, current kubernetes context and current AWS profile.
*   [skull (⭐23)](https://github.com/tahadostifam/skull-zsh) - Includes `git` status, python virtual environment and ruby `rvm` status decorations.
*   [sleeplessmind (⭐1)](https://github.com/godbout/sleeplessmind-zsh-theme) - ZSH theme inspired by [gitster (⭐67)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [odin (⭐72)](https://github.com/tylerreckart/odin).
*   [slick (⭐22)](https://github.com/nbari/slick) - Inspired by the [pure (⭐14k)](https://github.com/sindresorhus/pure), [purs (⭐254)](https://github.com/xcambar/purs) and [zsh-efgit-prompt (⭐7)](https://github.com/ericfreese/zsh-efgit-prompt). Requires `cargo` for installation.
*   [slimline (⭐53)](https://github.com/mengelbrecht/slimline) - Minimal, fast and elegant ZSH prompt. Displays the right information at the right time.
*   [sm (⭐17)](https://github.com/blyndusk/sm-theme) - A **Simplist** & **Minimalist** theme for your **favorite** terminal. Includes `git` status decorations.
*   [smail (⭐13)](https://github.com/nimacpp/themes-zsh) - Includes decorators for `git` status, current directory and exit status of last command run.
*   [small-terminal-diy (⭐0)](https://github.com/Sokkam/small-terminal-diy-theme) - A variant of the [ys (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) theme in [oh-my-zsh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh).
*   [smelly (⭐0)](https://github.com/Vicfs/smelly-theme/) - Minimalist prompt that includes decorators for Python `venv` and `git` status.
*   [smiley (⭐6)](https://github.com/gsamokovarov/smiley.zsh-theme) - A prompt with happy and sad faces.
*   [snowflake (⭐3)](https://github.com/angelina-tsuboi/snowflake-zsh-theme) - An elegant, simple, and neat ZSH theme including an aesthetically pleasing cool color palette that harmonizes with dark themes.
*   [sobole (⭐153)](https://github.com/sobolevn/sobole-zsh-theme) - A minimalistic ZSH theme inspired by the old-fashioned hobbies. No verbose gimmicks, no emoji, no fidget spinners, and no other visual noise. Has both light and dark modes.
*   [softblobby (⭐4)](https://github.com/gsalami00/softblobby/) - A theme for people who love unicorns, pink and purple. Includes decorators for `git` information, current directory, time and username.
*   [solarized-powerline (houjunchen) (⭐11)](https://github.com/houjunchen/solarized-powerline) - Solarized powerline-style theme for ZSH.
*   [solarized-powerline (KuoE0) (⭐45)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) - Solarized powerline variant.
*   [solarizsh (⭐4)](https://github.com/paddykontschak/Solarizsh) - Color fix for robbyrussell's oh-my-zsh theme to work with [solarized (⭐16k)](https://github.com/altercation/solarized) terminals.
*   [sorin-modified-dark (⭐0)](https://github.com/hrmeetsingh/sorin-modified-dark) - Based on [sorin (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#sorin). Minimalist, adds decorators for `git` status and current directory.
*   [spaceship (⭐20k)](https://github.com/denysdovhan/spaceship-prompt) - Theme with `git`, `nvm`, rvm/rbenv/chruby, python, `ssh` and other useful status decorators.
*   [spectere (⭐1)](https://github.com/Spectere/spectere-omz-theme) - Powerline-esque. Includes decorators for current directory, root status, `user@hostname`, and `git` status.
*   [spowerline](https://mbauhardt.github.io/spowerline/) - Written in scala, inspired by [Agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme), [tmux](https://tmux.github.io) powerline, vim powerline and the vim status plugin.
*   [spyrhoo (⭐2)](https://github.com/FajarKim/spyrhoo-zsh-theme) - Includes time, `git` and current directory decorations.
*   [ssfprompt (⭐0)](https://github.com/hugoh/zsh-ssfprompt) - Simple, slim, fast. Includes `ssh`, virtualenv and vcs decorations.
*   [staples (⭐4)](https://github.com/dersam/staples) - Based on bureau, displays user\@host if connected through SSH.
*   [starboy (⭐1)](https://github.com/prdpx7/Starboy) - A simple ZSH theme.
*   [starship (wintermi) (⭐20)](https://github.com/wintermi/zsh-starship) - A simple plugin to use the Starship prompt, along with a powerline theme.
*   [starship](https://starship.rs/) - Minimal, fast, extremely customizable.
*   [starship2k (⭐5)](https://github.com/2KAbhishek/starship2k) - Includes powerline support, decorators for `git` information, multiple languages and a multiline prompt.
*   [statusline (⭐68)](https://github.com/el1t/statusline) - A responsive ZSH theme that provides informational segments when you need them.
*   [steef (danihodovic) (⭐4)](https://github.com/danihodovic/steeef) - Oh-my-zsh steeef theme as a standalone repository. The purpose behind this repo is avoid having a dependency on oh-my-zsh when using the steeef theme. ZSH plugin managers such as Antibody can use the theme without having to use oh-my-zsh.
*   [steef (zelongguo) (⭐0)](https://github.com/ZelongGuo/steeef) - Based on the [zimfw steef theme (⭐5)](https://github.com/zimfw/steeef). Includes decorators for username\@hostname, python venv, `git` status and current directory. Requires [git-info (⭐10)](https://github.com/zimfw/git-info).
*   [steef (zimfw) (⭐5)](https://github.com/zimfw/steeef) - A customizable version of [steeef's (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) theme.
*   [steeple (⭐0)](https://github.com/erwanjugand/steeple-zsh-theme) - Minimalist theme with `git` status decorations.
*   [stellachar (⭐0)](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/stellachar.zsh-theme) - Minimal, pastels.
*   [stigmata (⭐0)](https://github.com/VLtim43/stigmata.zsh-theme) - Includes decorators for user\@host and current directory.
*   [sublime (⭐0)](https://github.com/pjmp/sublime) - A sublime, clean, minimalistic ZSH theme with `git` status decorations.
*   [sugar-free (⭐3)](https://github.com/cbrock/sugar-free) - Based on the [Pure (⭐14k)](https://github.com/sindresorhus/pure) and [Candy (⭐1)](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/candy.zsh-theme) themes.
*   [sukeesh (⭐0)](https://github.com/sukeesh/sukeesh-zsh-theme) - Includes `git` status decorations. Works better on dark terminal backgrounds.
*   [sulfurium (⭐0)](https://github.com/Sulfurium/zsh-theme) - The official ZSH theme of sulfuriumOS.
*   [sunrise-ruby (⭐0)](https://github.com/ston1x/sunrise-ruby) - Similar to [sunrise (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/sunrise.zsh-theme) but includes the active Ruby version.
*   [sunrise (⭐0)](https://github.com/tech8i/zsh_sunrise) - Includes decorators for battery status, current directory, date and time.
*   [superkolo (⭐2)](https://github.com/Minipada/superkolo) - Add date and return status to the [kolo (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kolo.zsh-theme) theme.
*   [susi (⭐10)](https://github.com/carcruz/susi-zsh-iterm) - Includes `git` status decorations and an accompanying iTerm2 color scheme.
*   [svs (⭐0)](https://github.com/SvS30/svs-theme) - Clean and distraction free theme with `git` status and current path decorations.
*   [sy (⭐2)](https://github.com/ttttmr/sy-zsh-theme) - Based on [ys (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme), includes `git` status decorations.
*   [t2colorful (⭐3)](https://github.com/AmirhosseinAbutalebi/t2colorful-oh.my.zsh) - Includes decorators for `git` information, current directory, last command exit status, and current time.
*   [t2er (⭐0)](https://github.com/t2er/t2er-zsh-theme) - Minimalist theme with `git` decorations.
*   [tabaf (⭐3)](https://github.com/bvc3at/tabaf-zsh-theme) - Minimal ZSH theme optimized for dark backgrounds.
*   [tarcadia (⭐3)](https://github.com/Tarcadia/tarcadia-zsh-theme) - Based on [jonathan (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/jonathan.zsh-theme). Includes decorators for current directory and `git` status.
*   [tcr (⭐0)](https://github.com/tulioribeiro/zsh-tcr-theme) - Minimalist theme, shows decorators for current directory, `git` status information & `nvm` version.
*   [teajay (⭐0)](https://github.com/Teajey/teajey-zsh-theme) - Adapted from murilasso and fishy themes. Includes decorators for `git` status, and path to current directory (collapsed to show only most relevant parts) and the exit code of last command run.
*   [temeraf (⭐1)](https://github.com/filiptoma/temeraf-zsh) - Minimalist theme with decorations for `git` status, timestamps and last exit status.
*   [tepig-ys (⭐38)](https://github.com/thingerpig/tepig-ys.zsh-theme) - Includes `git` status decorations and conda/virtualenv status.
*   [termux (⭐1)](https://github.com/rooted-cyber/Termux-zsh-theme) - Minimalist theme.
*   [termuxer (⭐16)](https://github.com/patrick330602/termuxer) - Theme inspired by [Agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme) and linuxer.
*   [thayne (⭐1)](https://github.com/tmccombs/thayne.zsh-theme) - Includes decorators for exit status of last command, time to run if > 1 second, current time, current directory and `git` status. Requires a Nerd Font.
*   [the-time-lord (⭐0)](https://github.com/jhwhite/the-time-lord) - A theme based on [gallifrey (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
*   [theme-line (⭐12)](https://github.com/yw9381/oh-my-zsh_theme_line) - Colorful theme with `git` status.
*   [themer (⭐1)](https://github.com/MrRedacted/zsh-themer) - Includes multiple color scheme options, with `git` status decorators. There are also multiple icons to choose from within the `.zsh-theme` file. Based on [strug (⭐2)](https://github.com/triplepointfive/oh-my-zsh/blob/master/themes/strug.zsh-theme).
*   [themeraf (⭐0)](https://github.com/oliver-svrcek/Themeraf) - Has decorators for username, last two directories in working directory path, `git` status, timestamp, last exit status and also name of active virtual environment.
*   [theozera (⭐0)](https://github.com/theogandara/zsh-theme) - Includes decorators for `git` status, a truncated current directory, and the exit status of the last command run.
*   [theta-async (⭐1)](https://github.com/jesec/zsh_theme_theta-async) - Async version of [theta (⭐9)](https://github.com/eendroroy/theta). Includes vcs status information.
*   [theta (⭐9)](https://github.com/eendroroy/theta) - Includes `git` and `hg` status decorations. Also has java, python, ruby, node, go and elixir version information.
*   [theto (⭐9)](https://github.com/heyvito/theto-zsh-theme) - Simplistic theme.  Needs [Nerd Fonts](https://nerdfonts.com/), includes `vi`-mode status and `git` decorations.
*   [thetraveler (⭐2)](https://github.com/bassopenguin/thetraveler) - Inspired by theunraveler, uses symbols to display `git` status.
*   [thm (⭐3)](https://github.com/thm-unix/thm-zshtheme) - Includes decorators for virtualenv, current directory and `git` status.
*   [thnikk (⭐1)](https://github.com/thnikk/zsh-theme-thnikk) - A minimal version of the [spaceship (⭐20k)](https://github.com/denysdovhan/spaceship-prompt) theme.
*   [thygod (⭐0)](https://github.com/Thy-GoD/thy-god-zsh-theme) - Based off [gnzh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) and [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme). Includes a `git` status decorator and changes prompt to a red cross when a command fails.
*   [thyme (chenhao-ye) (⭐22)](https://github.com/chenhao-ye/thyme) - Seasoning for shells. Based on [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), [gnzh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme), and [bullet-train (⭐2.8k)](https://github.com/caiogondim/bullet-train.zsh/blob/master/bullet-train.zsh-theme).
*   [thyme (kawamurakazushi) (⭐1)](https://github.com/kawamurakazushi/thyme) - Simple theme with `git` status decorations.
*   [toledo (⭐7)](https://github.com/mmatongo/toledo) - Quick minimalist theme with `git` status decorations. Works with `zsh`, `bash`, `dash` and `yash`.
*   [tonni4 (⭐0)](https://github.com/AndreyPuzanov/tonni4-zsh-theme) - Includes time and `git` status decorators.
*   [topan (⭐1)](https://github.com/fudyartanto/topan-theme-oh-my-zsh) - Includes `git` information; best on dark backgrounds.
*   [torim (⭐0)](https://github.com/Aggrathon/torim) - Inspired by the [sorin (⭐7)](https://github.com/zimfw/sorin), [asciiship (⭐23)](https://github.com/zimfw/asciiship) and [mh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#mh) themes. Includes decorators for user\@hostname (when accessed by `ssh`), truncated path to working directory, whether running as root, error code of last command run if it failed, current time, duration of long running commands, current virtual environment and `git` status.
*   [tq (⭐2)](https://github.com/kitian616/tq-zsh-theme) - Displays `git` status, time, requires a Powerline font.
*   [traffic (⭐1)](https://github.com/fcce/traffic-zsh-theme) - A dark theme for ZSH.
*   [trajan (⭐1)](https://github.com/denisinla/trajan-zsh-theme) - A dark theme for ZSH.
*   [transient (⭐9)](https://github.com/olets/zsh-transient-prompt) - Add a transient prompt to your zsh command line — that is, make your current command line's prompt different from past command lines' prompts. For example, past prompts might not need to show as much contextual information. Or you might want to put past commands on their own line, instead of prefixed by a prompt, for easier selecting and copying. More details at [zsh-transient-prompt.olets.dev](https://zsh-transient-prompt.olets.dev/).
*   [trinity (⭐1)](https://github.com/de-luca/Trinity) - A simple theme based on [geometry (⭐959)](https://github.com/geometry-zsh/geometry). Includes `git` decorations.
*   [tron (⭐0)](https://github.com/iDoTron/tron-zsh-theme) - Includes `git` status, working directory, time, user\@host and return status of last command decorations.
*   [troopert (⭐0)](https://github.com/TrooperT/Troopert-theme/) - Includes decorators for `git` status, last return code if non-zero, full pwd and a configurable display of `$RPROMPT`.
*   [tsotra (⭐2)](https://github.com/nylo-andry/zsh-themes) - Minimalist theme, includes decorators for `git` status, k8s context, and `rvm` status.
*   [turs (⭐0)](https://github.com/eikendev/turs) - Fast, minimal [Purs (⭐254)](https://github.com/xcambar/purs)-inspired prompt.
*   [tvline (⭐2)](https://github.com/thvitt/tvline) - Derived from the [agnoster](https://gist.github.com/agnoster/3712874) theme, adds powerline font enhancements.
*   [twilight (⭐2)](https://github.com/Henryws/twilight-prompt) - Minimalist, but includes last command exit status, `git` status and `user@hostname` decorations.
*   [type0 (⭐0)](https://github.com/MikereDD/type0_zsh-theme) - Inspired by [classyTouch (⭐53)](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) by yarisgutierrez. Includes `git` decorations.
*   [typewritten (⭐926)](https://github.com/reobin/typewritten) - Minimal and informative theme that leaves room for what's important. Does asynchronous `git` decoration updates for speed.
*   [ubunly (⭐26)](https://github.com/alejandromume/ubunly-zsh-theme) - Mimics the Kali Linux console. Note - this theme also rebinds a lot of keys and sets a bunch of ZSH options that themes should leave alone.
*   [ubuntu-ish (⭐0)](https://github.com/Thesola10/zsh-ubuntu-ish) - Mimics the default Debian/Ubuntu `bash` prompt.
*   [ubuntu-with-vitamins (⭐0)](https://github.com/ureesoriano/zsh-ubuntu-with-vitamins-zim-theme) - Mimics the default Ubuntu prompt, but with `git` decorations.
*   [ubuntu (⭐1)](https://github.com/janstuemmel/zsh-ubuntu-theme) - Minimal theme, includes `git` status decorations.
*   [ultima (⭐100)](https://github.com/egorlem/ultima.zsh-theme) - Minimalist, includes `git` status and current directory decorators.
*   [ultimate (⭐12)](https://github.com/b4b4r07/ultimate) - Minimalist theme with decorators for `git` status, vim mode indicator and shortened path.
*   [ultimator (⭐0)](https://github.com/Ultimator14/ultimator-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874)-like theme. Includes decorators for current directory, `user@host`, python virtualenv, background jobs, last command exit status, and `git` status information. Requires [zsh-git-prompt (⭐0)](https://github.com/Ultimator14/zsh-git-prompt) plugin and Nerdfonts.
*   [ulyssesys (⭐0)](https://github.com/UlyssesZh/ulyssesys) - Has decorators for full path to current directory, exit code of last command and `git` status.
*   [unicorn (⭐1)](https://github.com/juliuscaesar/unicorn) - Includes decorators for root status, virtualenv, nvm, rvm, current directory, the time, current directory and emoji `git` information. Inspired by [wild cherry (⭐480)](https://github.com/mashaal/wild-cherry).
*   [unit-1 (⭐0)](https://github.com/nerdbude/Unit-1) - Minimalist theme with ITWTB colors.
*   [userandnode (⭐0)](https://github.com/timhilton/userandnode) - A clean theme with decorators for username, node version, current directory, and `git` info.
*   [valuca (⭐0)](https://github.com/keyaedisa/Valuca) - Variant of [ducula (⭐46)](https://github.com/janjoswig/Ducula). Includes decorators for background job status, username, hostname, virtualenv, current directory, last command's exit code, `git` information and the current time.
*   [vanan (⭐0)](https://github.com/avano/vanan.zsh-theme) - Enhances your terminal with detailed `git` information. Also includes decorators for `vi`-mode and status of the last command run.
*   [vehemence (⭐0)](https://github.com/H1N1-dev/vehemence-zsh) - Includes decorators for `pwd`, `user@host`, `tty`, time, last command exit code and `git` status.
*   [velvet (⭐0)](https://github.com/dor133/velvet-zsh-theme) - Includes decorators for `git` status, username, current directory, exit status of last command, and the time.
*   [vercel (⭐189)](https://github.com/vercel/zsh-theme) - Minimalist theme with `git` status decorations.
*   [vertepommes (⭐0)](https://github.com/TheRojam/vertepommes-theme) - Based on ys. Includes vcs status, username and current directory decorations.
*   [vinhnx (⭐7)](https://github.com/vinhnx/vinhnx.zsh-theme) - Modified from [mgutz (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/mgutz.zsh-theme). Looks great when using with a [Solarized (⭐16k)](https://github.com/altercation/solarized) color scheme.
*   [vitesse (⭐1)](https://github.com/rafaeldellaquila/zsh-vitesse-theme/blob/master/img/preview.png) - Inspired by VS Code's [Vitesse (⭐611)](https://github.com/antfu/vscode-theme-vitesse) theme. Includes `git` status decorations.
*   [voidy (⭐0)](https://github.com/rwejdling/voidy) - Borrows elements from [lambda (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) and [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) themes and adds the active [aws-vault (⭐8.7k)](https://github.com/99designs/aws-vault) profile to the right side of the prompt.
*   [vszambon-ocean (⭐0)](https://github.com/vzambon/vszambon_ocean-zsh-theme) - Includes decorators for current directory, `git` status, a day/night icon, whether or not it is running inside a `docker` container and the date and time.
*   [vtex (⭐0)](https://github.com/charleseduardome/oh-my-zsh-vtex) - Includes decorators for `git` status, current directory, vtex account and vtex workspace.
*   [vulcan (⭐0)](https://github.com/Bruceboy/vulcan-zsh-theme) - Minimal theme reminiscent of the default `bash` theme. Includes `git` decorations.
*   [wade (⭐5)](https://github.com/wadehammes/wade.zsh-theme) - Mashup of the popular ZSH themes [Agnoster](https://gist.github.com/agnoster/3712874) and [Fishy (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fishy.zsh-theme), with some visual tweaks.
*   [wang-iterm (⭐5)](https://github.com/0532/wang-iterm-zsh) - Based on the 0532 theme.
*   [warm-colours (⭐0)](https://github.com/BastionAtackDev/Warm-Colours.zsh-theme/) - Includes decorators for user\@host, current directory and datetime.
*   [warmblood (⭐2)](https://github.com/D42H5/warmblood) - Based on [darkblood (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/darkblood.zsh-theme). Includes decorators for `git` information, user\@hostname and the current directory.
*   [whale (⭐2)](https://github.com/whalesea520/whale-zsh-theme) - Fast reimplementation of the whale theme.
*   [whales (⭐0)](https://github.com/lbergelson/zsh_whales_theme) - Includes decorators for `git` status, java version, last command return status, and directory.
*   [wild-cherry (⭐480)](https://github.com/mashaal/wild-cherry) - A fairy-tale inspired theme for ZSH, iTerm 2, Sublime, Atom, & Mou.
*   [windows (⭐37)](https://github.com/juliavallina/windows-zsh-theme/) - Inspired by the Windows Command Prompt. Includes a decorator for the current directory.
*   [winline (⭐1)](https://github.com/khuei/winline) - Async version of Greg Hurrell's [prompt (⭐1.2k)](https://github.com/wincent/wincent/blob/master/aspects/dotfiles/files/.zshrc). Includes decorators for `git` status, duration of last command, current directory, nested shells, root status.
*   [wkentaro (⭐1)](https://github.com/wkentaro/wkentaro.zsh-theme) - A simple theme for Python users. Includes virtualenv and `git` status decorators.
*   [work-line (⭐6)](https://github.com/afnizarnur/work-line) - Theme with nice emojis.
*   [workbench (⭐4)](https://github.com/u8slvn/oh-my-zsh-workbench-theme) - Includes `git` status decorations, working directory, exit status of last command and current `virtualenv`.
*   [wormwood (⭐3)](https://github.com/ann-kilzer/annkilzer.zsh-theme) - Includes decorators for last command exit status, current directory and `git` status.
*   [x (⭐10)](https://github.com/tharindu899/x-theme) - Includes customizable banners
*   [xandermute (⭐0)](https://github.com/SoYoureAWaffleMan/xandermute-oh-my-zsh-theme/) - Minimalist theme with `git` and current directory decorations.
*   [xavi (⭐0)](https://github.com/onthedock/xavi.zsh-theme) - Modified version of the [gnzh (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) theme with emoji decorations for `git` status and current directory.
*   [xbira (⭐0)](https://github.com/ITAxReal/xbira) - Based on [bira (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), includes decorators for `git` status, user\@hostname, exit status of last command run and the current directory.
*   [xlk-simple (⭐1)](https://github.com/xuelingkang/xlk-simple-zsh-theme) - Simple theme with `git` decorations.
*   [xm (⭐0)](https://github.com/Shiaoming/xm) - Theme for dark terminals. Has `git` decorations.
*   [xor (⭐1)](https://github.com/xor3n/xor-zsh-theme) - Self described as minimalistic and 'feature-poor', includes `git` decorations.
*   [xremix (⭐1)](https://github.com/xremix/oh-my-zsh-xremix-theme) - An oh-my-zsh shell theme based on the Jreese theme plugin.
*   [xris47 (⭐1)](https://github.com/ivan-ristovic/xris47.zsh-theme) - Fast, simple and streamlined theme. Works best with [tmux (⭐37k)](https://github.com/tmux/tmux/wiki) and [vim-airline (⭐18k)](https://github.com/vim-airline/vim-airline).
*   [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - Shows the current `git` commit's shortened hash and message.
*   [yairshefi (⭐1)](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme) - Minimal theme with line separated prompts. Based on the [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme.
*   [yazpt (⭐7)](https://github.com/jakshin/yazpt) - A clean, fast, good-looking ZSH prompt theme that thoughtfully incorporates Git/Subversion/TFVC status info, integrates with popular plugin managers like Oh My Zsh, and is straightforward to customize and extend.
*   [yechen (⭐0)](https://github.com/liyechen/yechen.zsh-theme) - Minimalist theme with `git` status decorations.
*   [yeet (⭐0)](https://github.com/jeetelongname/Yeet-theme) - Minimalist prompt with `git` status decorations.
*   [yellow peach (⭐0)](https://github.com/tomorrowbye/yellow-peach-theme) - Clean minimalist design. Includes decorators for `user@hostname`, `git` status, current directory and the current time.
*   [yellow-sea-diamonds (⭐0)](https://github.com/jimratliff/yellow-sea-diamonds-zsh-theme) - Includes decorations for `git` status, current directory, active python virtual environment, and the exit status of the last command run.
*   [yindev (⭐2)](https://github.com/menyinch/yindev-zsh-theme) - Variant of `gndx`. Includes decorations for `git` status and current directory.
*   [ykmam (⭐1)](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - Modified from [ys (⭐0)](https://github.com/cristiancavalli/ys-zsh-custom-theme) theme and optimized for a dark background.
*   [ys-cluster (⭐1)](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme) - [ys (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) variant with support for working with batch submission systems for large clusters. Supports Slurm, LSF / IBM Spectrum LSF, and PBS.
*   [ys (⭐0)](https://github.com/cristiancavalli/ys-zsh-custom-theme) - Clean, simple, compatible and meaningful theme meant for dark backgrounds.
*   [ysm (⭐1)](https://github.com/hanbinpro/ysm-zsh-theme) - Simple ZSH theme with `git` status information.
*   [ysr (⭐0)](https://github.com/raykle/ysr-zsh-theme) - Based on [ys (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme). Includes `git` status decorations.
*   [yuki (⭐6)](https://github.com/yuki-torii/yuki-zsh-theme) - A dark optimized ZSH theme.
*   [yuyuko (⭐1)](https://github.com/hylwxqwq/yuyuko.zsh-theme) - Fork of [ys (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme), inspired by [yuyuko.vim (⭐36)](https://github.com/hylwxqwq/yuyuko.vim).
*   [yyl-ys (⭐38)](https://github.com/yunyuliu/yyl-ys.zsh-theme) - Includes conda and venv status.
*   [yz50 (⭐1)](https://github.com/lacanlale/yz50-zsh) - Colorful, based off of [robbyrussell (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) and [crunch (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/crunch.zsh-theme) themes. Includes `git` status decorations.
*   [z4rr3t (⭐1)](https://github.com/inimicus/z4rr3t) - Based on sindresorhus' [pure (⭐14k)](https://github.com/sindresorhus/pure) theme.
*   [zap-robbyrussell (⭐1)](https://github.com/devadathanmb/zap-robbyrussell) - The OMZ robbyrussell theme, patched to add compatibility with [zap](https://www.zapzsh.com/).
*   [zcmder (⭐1)](https://github.com/bwpge/zcmder) - inspired by [Cmder](https://cmder.app/) with decorators for `git` information, current directory and root status.
*   [zcraft (⭐1)](https://github.com/cpea2506/zcraft) - Minimalist theme with decorations for `git` status, last command exit status and the time taken by the last command.
*   [zeit (⭐189)](https://github.com/zeit/zeit.zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
*   [zelda (⭐2)](https://github.com/SuperKnerdBros/zelda.zsh-theme) - Zelda-inspired theme. Includes `git` status decorations.
*   [zemm-blinks (⭐7)](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - Customized version of oh-my-zsh [blinks (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme) with mercurial support and other changes.
*   [zemoji (⭐5)](https://github.com/therzka/zemoji) - Based on [wild-cherry (⭐480)](https://github.com/mashaal/wild-cherry/tree/master/zsh). Includes exit status, `virtualenv`, `nvm`, `rvm` and `git` status decorations.
*   [zen (cybardev) (⭐24)](https://github.com/cybardev/zen.zsh) - A minimalist theme for `*NIX` systems. Includes decorators for execution time of last command run, curreent directory and vcs status information.
*   [zen (TheCrazyGM) (⭐0)](https://github.com/TheCrazyGM/zen) - A clean, informative, and customizable theme for Oh-My-Zsh that provides essential information without cluttering your terminal. It was designed with Python developers in mind and includes smart features like SSH detection, detailed Git status information, and command execution time tracking.
*   [zenith (⭐0)](https://github.com/waki285/Zenith) - Minimalist. Includes decorators for username, current directory and `git` status.
*   [zero (arlimus) (⭐16)](https://github.com/arlimus/zero.zsh) - Zero's theme & plugin. Has variants for both light and dark terminal backgrounds.
*   [zero (shirozuki) (⭐0)](https://github.com/shirozuki/zero-zsh-theme) - Minimalistic prompt with decorators for `git` status, current directory, exit status and time to execute of last command run.
*   [zeroastro (⭐7)](https://github.com/zeroastro/zeroastro-zsh-theme) - Works best on dark backgrounds, includes `git` status decorations.
*   [zerocake (⭐0)](https://github.com/ZeroPoke/ZeroCake.zsh-theme) - Works better on dark brackgrounds.
*   [zest (⭐0)](https://github.com/hash-bang/zsh-theme-zest) - A functional theme for ZSH. Influenced by [zsh2000 (⭐102)](https://github.com/consolemaverick/zsh2000), [agnoster](https://gist.github.com/agnoster/3712874) and [powerline (⭐1.2k)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) themes.
*   [zeta (⭐230)](https://github.com/skylerlee/zeta-zsh-theme) - Shows decorations for username, `git` status information, machine name, the current working directory and success/fail status of last command.
*   [zhiyin (⭐68)](https://github.com/AmyangXYZ/zhiyin-zsh-theme) - Includes decorators for user @ host, current working directory and `git` status information.
*   [zido (⭐1)](https://github.com/SidonieBouthors/zido-zsh-theme) - Includes decorators for `git` status and current directory.
*   [zigbar (⭐20)](https://github.com/dbushell/zigbar) - Written in zig. Includes decorators for `git` status, current directory. Requires a [Nerd Font](https://www.nerdfonts.com/font-downloads).
*   [zinc](https://gitlab.com/robobenklein/zinc) - A blazing-fast, pure ZSH, mixed asynchronous prompt inspired by [Powerlevel9k (⭐13k)](https://github.com/bhilburn/powerlevel9k) and [Agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme) that's easily extensible and extremely configurable. It supports async segments using [zsh-async (⭐788)](https://github.com/mafredri/zsh-async).
*   [zish (⭐1)](https://github.com/RubixDev/zish/) - Based on the `fish` shell's default look.
*   [zlambda (⭐0)](https://github.com/wdhg/zlambda) - Minimalist, includes `git` decorations without special font requirements.
*   [zodiac (⭐0)](https://github.com/adamalsen/zsh-zodiac) - Includes an emoji for the animal corresponding to the current year.
*   [zoo (⭐2)](https://github.com/salamantos/zoo_sh) - Casual theme with animal emoji. Includes decorators for current directory, time and `git` status.
*   [zp (⭐7)](https://github.com/Karitham/zp) - Fast prompt, written in `zig`. Includes `git` status and current directory decorators.
*   [zprompts (⭐6)](https://github.com/z-shell/zprompts) - Themes (prompts) that use original `zsh` theming subsystem.
*   [zqt (⭐3)](https://github.com/ladychili/zqt-zsh-theme) - Modified version of oh-my-zsh's [maran (⭐178k)](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/maran.zsh-theme) theme.
*   [zsh1999 (⭐6)](https://github.com/DTan13/zsh1999) - Includes network connectivity, battery and `git` status decorations.
*   [zsh2000 (⭐102)](https://github.com/consolemaverick/zsh2000) - Theme which resembles Powerline and includes the `rvm` prompt, `git` status and branch, current time, user, hostname, pwd, exit status, whether running as root and background job status.
*   [zsh313 (⭐0)](https://github.com/amirali313/zsh313-theme) - Minimal theme with `git` status decorations.
*   [zshcomrade (⭐8)](https://github.com/landongn/zshcomrade) - A ZSH theme, comrade! Includes `git` status decorations.
*   [zshify (⭐3)](https://github.com/nrjdalal/zshify) - A minimalistic, one command installation to customize your prompt. Requires [npx](https://docs.npmjs.com/getting-started/installing-npm-packages-locally).
*   [zshiggy (⭐0)](https://github.com/malouro/zshiggy) - Includes decorators for `git` status, `node.js` version.
*   [zshpower (⭐14)](https://github.com/snakypy/zshpower) - Optimized for python developers. Includes `git` and `pyenv` status decorations, username and host. Tries to install other plugins and fonts, so read its instructions before installing.
*   [zshred (⭐1)](https://github.com/redxtech/zshred) - Shows current directory, `git` decorations, exit status of last command and time.
*   [zskai (⭐4)](https://github.com/dinizgab/zskai-theme) - Simple theme based on Monokai. Includes decorators for user\@hostname, time, `git` status and current working directory.
*   [zunder (⭐5)](https://github.com/Warbacon/zunder-prompt) - Simple and fast ZSH prompt based on [gitstatus (⭐1.7k)](https://github.com/romkatv/gitstatus).
*   [zwsh (⭐0)](https://github.com/naens/zwsh) - A Zpm3/Wordstar mode/theme for ZSH.
*   [zys (⭐10)](https://github.com/ZYSzys/zys-zsh-theme) - Similar to [Agnoster (⭐4.1k)](https://github.com/agnoster/agnoster-zsh-theme), designed to disclose information contextually, with a powerline aesthetic.
*   [zzshell (⭐0)](https://github.com/thezzisu/zzshell) - Inspired by the default [Oh-My-Zsh](http://ohmyz.sh/) theme. Displays exit code and `git` status decorations. Doesn't require Powerline fonts.

## Fonts

Some of the themes listed here require Powerline-compatible fonts, here are a few:

*   [Awesome Terminal Fonts (⭐2.5k)](https://github.com/gabrielelana/awesome-terminal-fonts) - A family of fonts that includes some nice monospaced Icons.
*   [Fantasque Awesome Font (⭐36)](https://github.com/ztomer/fantasque_awesome_powerline) - A nice monospaced font, patched with Font-Awesome, Octoicons and Powerline-Glyphs.
*   [Fantasque-sans (⭐7.1k)](https://github.com/belluzj/fantasque-sans) - Another Powerline-compatible font.
*   [Hack](https://sourcefoundry.org/hack/) - Another Powerline-compatible font designed specifically for source code.
*   [Input Mono](https://store.typenetwork.com/foundry/djr/series/input?family=input-mono) - A family of fonts designed specifically for code. It offers both monospaced and proportional fonts and includes powerline glyphs.
*   [Iosevka (⭐20k)](https://github.com/be5invis/Iosevka) - Coders' typeface, built from code. Highly customizable.
*   [Monoid](https://larsenwork.com/monoid/) - Monoid is customizable and optimized for coding with bitmap-like sharpness at 15px line-height even on low res displays.
*   [Nerd Fonts (⭐57k)](https://github.com/ryanoasis/nerd-fonts) - Collection of over 20 patched fonts (over 2,000 variations) & FontForge font patcher python script for Powerline, Font Awesome, Octicons, Devicons, and Vim Devicons. Includes: Droid Sans, Meslo, Source Code, AnonymousPro, Hack, ProFont, Inconsolata, and many more.
*   [Powerline patched font collection (⭐26k)](https://github.com/powerline/fonts) - A collection of a dozen or so fonts patched to include powerline gylphs.
*   [Terminus](http://files.ax86.net/terminus-ttf/) - TTF version of Terminus that includes powerline glyphs.

## Installation

I recommend [zgenom (⭐388)](https://github.com/jandamm/zgenom) if you don't already have a preferred ZSH framework. It adds minimal overhead during shell session startup because it generates a load script only when you change your plugin list, and that load script is sourced during startup instead of being recalculated every time.

### [Antigen (⭐8.2k)](https://github.com/zsh-users/antigen)

Most of these plugins can be installed by adding `antigen bundle githubuser/reponame` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start `zsh`. You can also add the plugin to a running ZSH with `antigen bundle githubuser/reponame` for testing before adding it to your `.zshrc`.

### [dotzsh (⭐227)](https://github.com/dotphiles/dotzsh)

1.  Clone new plugins into `.zsh.local/modules`
2.  Load the plugin module in `.zshrc`
3.  Open a new ZSH terminal window or tab

### [Oh-My-Zsh](http://ohmyz.sh/)

1.  `cd ~/.oh-my-zsh/custom/plugins`
2.  `git clone repo`
3.  Add the repo to your plugin list

### [Prezto (⭐14k)](https://github.com/sorin-ionescu/prezto)

1.  Clone the plugin into your prezto modules directory
2.  Add the plugin to your `.zpreztorc` file
3.  Open a new terminal window or tab

### [Zgen (⭐1.5k)](https://github.com/tarjoilija/zgen)

Zgen is not being actively maintained. I recommend that you switch to the [Zgenom (⭐388)](https://github.com/jandamm/zgenom) fork, which is.

### [Zgenom (⭐388)](https://github.com/jandamm/zgenom)

Most of these plugins can be installed by adding `zgenom load githubuser/reponame` to your `.zshrc` file in the same function you're doing your other `zgenom load` calls in.

Zgenom will automatically clone the plugin repositories for you when you do a `zgenom save`.

### [zplug (⭐5.9k)](https://github.com/zplug/zplug)

Most of these plugins can be installed by adding `zplug "githubuser/reponame"` to your `.zshrc` file.

### [zpm (⭐369)](https://github.com/zpm-zsh/zpm)

Most of these plugins can be installed by adding `zpm load "githubuser/reponame"` to your `.zshrc` file.

## Writing New Plugins and Themes

I've documented some recommendations for writing new plugin and themes [here (⭐16k)](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins_and_Themes.md).

There is also a more detailed [Zsh Plugin Standard](https://zdharma-continuum.github.io/Zsh-100-Commits-Club/Zsh-Plugin-Standard.html).

## Other Resources

### ZSH Tools

*   [argcomplete (⭐1.5k)](https://github.com/kislyuk/argcomplete) - Generates tab completions for programs using Python's `argparse` module.
*   [completion-generators (⭐1)](https://github.com/zetlen/zsh-completion-generators) - Has a table of tool names and the commands for outputting completion scripts for those tools. On every load, will check that table and run the completion command for every tool found in your `$PATH` and save its output to a file \_<toolname>. If the path of this repo is in `$fpath`, completions will work immediately.
*   [crazy-complete (⭐6)](https://github.com/crazy-complete/crazy-complete) - Every program should have autocompletion in the shell to enhance user experience and productivity. `crazy-complete` helps solve this task by generating robust and reliable autocompletion scripts.
*   [manpage-completion-generator (⭐39)](https://github.com/umlx5h/zsh-manpage-completion-generator) - Generats ZSH completions from man pages. Requires [create\_manpage\_completions.py (⭐30k)](https://github.com/fish-shell/fish-shell/blob/master/share/tools/create_manpage_completions.py) which is installed by the fish shell
*   [oh-plugin (⭐3)](https://github.com/mbergo/oh-plugin) - Helps you install plugins for [oh-my-zsh](https://ohmyz.sh) by typing `oh-plugin install repository_address`.
*   [shell-color-prompt-tool (⭐13)](https://github.com/kyletimmermans/shell-color-prompt-tool) - Helps you create a custom prompt for `ZSH` or `bash`.
*   [shellSpec (⭐1.2k)](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for dash, bash, ksh, ZSH and all POSIX shells.
*   [shtab (⭐397)](https://github.com/iterative/shtab) - Automatically generate shell tab completion scripts for Python CLI apps, supports `zsh`, `bash` and `tcsh`.
*   [zsh-ai-completions (⭐6)](https://github.com/iloveitaly/zsh-ai-completions) - AI-generated ZSH completions
*   [zsh-bench (⭐742)](https://github.com/romkatv/zsh-bench) - A benchmark for interactive ZSH. It measures user-visible latency of interactive `zsh`: input lag, command lag, etc.
*   [zshdb (⭐309)](https://github.com/rocky/zshdb) - A ZSH debugger.
*   [zshelldoc (⭐20)](https://github.com/zdharma-continuum/zshelldoc) - Doxygen for shell scripts. Parses ZSH and Bash scripts, outputs Asciidoc document with function lists, call trees, lists of exported variables, and more.
*   [zunit (⭐213)](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH.

### Other Useful Lists

*   [awesome-devenv (⭐2.9k)](https://github.com/jondot/awesome-devenv) - A curated list of awesome tools, resources and workflow tips making an awesome development environment.
*   [awesome-sysadmin (⭐29k)](https://github.com/n1trux/awesome-sysadmin) - A curated list of awesome open source sysadmin resources.
*   [Terminals Are Sexy (⭐12k)](https://github.com/k4m4/terminals-are-sexy) - A curated list for CLI lovers.

Find other useful awesome-\* lists at the [awesome collection (⭐357k)](https://github.com/sindresorhus/awesome)

### Other References

*   The [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) and [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) are indispensable.

*   [Mastering ZSH (⭐1.5k)](https://github.com/rothgar/mastering-zsh) is a great tutorial that builds on the basics to show you advanced ZSH usage, customizations, and practical examples.

## Thanks

Many thanks to all the contributors over the years. The list wouldn't be nearly as complete without all your help.

<a href="https://github.com/unixorn/awesome-zsh-plugins/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=unixorn/awesome-zsh-plugins" />
</a>

Made with [contributors-img](https://contributors-img.web.app).

