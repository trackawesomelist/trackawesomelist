# Track Awesome Nix Updates Daily

😎 A curated list of the best resources in the Nix community [maintainer=@cyntheticfox]

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/nix-community/awesome-nix/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 nix-community/awesome-nix](https://github.com/nix-community/awesome-nix) · ⭐ 4.6K · 🏷️ Platforms

[ Daily / [Weekly](/content/nix-community/awesome-nix/week/README.md) / [Overview](/content/nix-community/awesome-nix/readme/README.md) ]

## [Nov 24, 2025](/content/2025/11/24/README.md)

### Resources / Learning

*   [Nix in 100 Seconds](https://www.youtube.com/watch?v=FJVFXsNzYZQ) - A YouTube video from Fireship presenting Nix in 100 seconds.
*   [NixOS in Production](https://leanpub.com/nixos-in-production) - Free (pay-what-you-want) book in pdf format.
*   [Official Nix manual](https://nixos.org/manual/nix/stable) - Latest stable version of the official Nix manual, best used as reference guide. Receives updates when available.
*   [Official NixOS manual](https://nixos.org/manual/nixos/stable) - Latest stable version of the official NixOS manual, mix of tutorial and reference guide. Receives updates when available.
*   [Official Nixpkgs manual](https://nixos.org/manual/nixpkgs/stable) - Latest stable version of the official Nixpkgs reference manual. Receives updates when available.
*   [Tour of Nix](https://nixcloud.io/tour/) - An online interactive tutorial on Nix language constructs.

### Resources / Discovery

*   [Searchix](https://searchix.ovh/) - Search Nix packages and options from NixOS, Darwin and Home Manager.

### Deployment Tools / Discovery

*   [Nixlets](https://gitlab.com/TECHNOFAB/nixlets) - Like Helm but using only Nix, uses Kubenix under the hood.
*   [terraform-nixos (⭐390)](https://github.com/nix-community/terraform-nixos) - A set of Terraform modules designed to deploy NixOS.

### Virtualisation / Discovery

*   [microvm (⭐2k)](https://github.com/microvm-nix/microvm.nix) - NixOS-based MicroVMs.

### Command-Line Tools / Discovery

*   [angrr (⭐60)](https://github.com/linyinfeng/angrr) - Auto Nix GC Roots Retention. This tool simply deletes auto GC roots based on the modified time of their symbolic link target.
*   [dix (⭐186)](https://github.com/faukah/dix) - Diff Nix; a super-fast tool to diff Nix related things.
*   [nh (⭐2.1k)](https://github.com/nix-community/nh) - Better output for `nix`, `nixos-rebuild`, `home-manager` and nix-darwin CLI leveraging `dix` and `nix-output-monitor`.
*   [nix-index (⭐1.1k)](https://github.com/nix-community/nix-index) - Quickly locate Nix packages with specific files.
*   [nixos-cli (⭐335)](https://github.com/nix-community/nixos-cli) - Configurable all-in-one CLI for common NixOS tools with an emphasis on improved user experience.
*   [optnix](https://git.sr.ht/~watersucks/optnix) - A terminal-based options searcher for Nix module systems.
*   [statix (⭐767)](https://github.com/oppiliappan/statix) - A linter/fixer to check for and fix antipatterns in Nix code.

### Development / Discovery

*   [Cachix](https://www.cachix.org) - Hosted binary cache service; free for open-source projects.
*   [Devbox (⭐11k)](https://github.com/jetify-com/devbox) - Instant, portable, and predictable development environments.
*   [make-shell (⭐27)](https://github.com/nicknovitski/make-shell) - `mkShell` meets modules, a modular almost-drop-in replacement for `pkgs.mkShell` function.
*   [Nixtest](https://gitlab.com/TECHNOFAB/nixtest) - Testing framework for Nix, with snapshot and unit test support, JUnit generation etc.
*   [pog (⭐127)](https://github.com/jpetrucciani/pog) - A new, powerful way to do bash scripts. Pog is a powerful Nix library that transforms the way developers create command-line interfaces (CLIs).
*   [pre-commit-hooks.nix (⭐733)](https://github.com/cachix/git-hooks.nix) - Run linters/formatters at commit time and on your CI.
*   [robotnix (⭐730)](https://github.com/nix-community/robotnix) - A declarative and reproducible build system for Android (AOSP) images.

### DevOps / Discovery

*   [Nix GitLab CI](https://gitlab.com/TECHNOFAB/nix-gitlab-ci) - Define GitLab CI pipelines in pure Nix with full access to all Nix packages (incl. caching).

### Programming Languages / Julia

*   [Manifest2Nix.jl](https://codeberg.org/aniva/Manifest2Nix.jl) - A Nix library for creating reproducible Julia builds and experiments via precompilation.

### Programming Languages / Python

*   [uv2nix (⭐599)](https://github.com/pyproject-nix/uv2nix) - Convert [`uv` workspaces](https://docs.astral.sh/uv/concepts/projects/workspaces/) into pure Nix derivations.

### Programming Languages / Ruby

*   [ruby-nix (⭐145)](https://github.com/inscapist/ruby-nix) - Generates reproducible ruby/bundler app environment with Nix.

### Programming Languages / Rust

*   [naersk (⭐909)](https://github.com/nix-community/naersk) - Build Rust packages directly from `Cargo.lock`. No conversion step needed.
*   [nix-cargo-integration (⭐211)](https://github.com/90-008/nix-cargo-integration) - A library that allows easy and effortless integration for Cargo projects.
*   [rust-nix-templater (⭐49)](https://github.com/90-008/rust-nix-templater) - Generates Nix build and development files for Rust projects.

### NixOS Modules / Zig

*   [nix-darwin (⭐4.7k)](https://github.com/nix-darwin/nix-darwin) - Manage macOS configuration just like on NixOS.
*   [NixOS hardware (⭐2.8k)](https://github.com/NixOS/nixos-hardware) - NixOS profiles to optimize settings for different hardware.

### NixOS Configuration Editors / Desktop apps

*   [Nix Software Center (⭐749)](https://github.com/snowfallorg/nix-software-center) - Install and manage Nix packages. Desktop app in Rust and GTK.
*   [NixOS Configuration Editor (⭐601)](https://github.com/snowfallorg/nixos-conf-editor) - Graphical editor for NixOS configuration. Desktop app in Rust and GTK.

### Overlays / Webinterface

*   [neovim-nightly-overlay (⭐392)](https://github.com/nix-community/neovim-nightly-overlay) - Daily bumped Neovim nightly package.

## [Jul 14, 2025](/content/2025/07/14/README.md)

### Development / Discovery

*   [treefmt-nix (⭐504)](https://github.com/numtide/treefmt-nix) - A formatter that allows formatting all your project files with a single command, all via a single `.nix` file.

### NixOS Modules / Zig

*   [Stylix (⭐2k)](https://github.com/nix-community/stylix) - System-wide colorscheming and typography for NixOS.

## [May 18, 2025](/content/2025/05/18/README.md)

### Development / Discovery

*   [MCP-NixOS (⭐341)](https://github.com/utensils/mcp-nixos) - An MCP server that provides AI assistants with accurate information about NixOS packages, options, Home Manager, and nix-darwin configurations.

## [Apr 02, 2025](/content/2025/04/02/README.md)

### Deployment Tools / Discovery

*   [Clan](https://clan.lol) - A peer-to-peer deployment tool with inbuilt support for secrets and a module system to manage distributed networks.

## [Mar 03, 2025](/content/2025/03/03/README.md)

### Resources / Learning

*   [Nix Starter Config (⭐3.5k)](https://github.com/Misterio77/nix-starter-configs) - A few simple Nix Flake templates for getting started with NixOS + home-manager.

### Resources / Discovery

*   [nix-search-tv (⭐169)](https://github.com/3timeslazy/nix-search-tv) - CLI fuzzy finder for packages and options from Nixpkgs, Home Manager, and more.

### Command-Line Tools / Discovery

*   [nvd](https://git.sr.ht/~khumba/nvd) - Diff package versions between two store paths; it's especially useful for comparing NixOS generations on rebuild.

## [Jan 22, 2025](/content/2025/01/22/README.md)

### Command-Line Tools / Discovery

*   [nixfmt (⭐1.4k)](https://github.com/NixOS/nixfmt) - A formatter for Nix code, intended to easily apply a uniform style.

### Development / Discovery

*   [Conflake](https://ratson.github.io/conflake/) - A batteries included, autoload files, convention-based configuration framework for `flake.nix`.

## [Dec 05, 2024](/content/2024/12/05/README.md)

### Programming Languages / Lean

*   [lean4-nix (⭐68)](https://github.com/lenianiva/lean4-nix) -  Nix flake build for Lean 4, and `lake2nix`.

### NixOS Modules / Zig

*   [NixOS-WSL (⭐2.6k)](https://github.com/nix-community/NixOS-WSL) - Modules for running NixOS on the Windows Subsystem for Linux.

## [Oct 22, 2024](/content/2024/10/22/README.md)

### Development / Discovery

*   [npins (⭐423)](https://github.com/andir/npins) - A simple tool for handling different types of dependencies in a Nix project. It is inspired by and comparable to Niv.

## [Sep 15, 2024](/content/2024/09/15/README.md)

### Installation Media / Discovery

*   [nixos-anywhere (⭐2.6k)](https://github.com/nix-community/nixos-anywhere) - Install NixOS everywhere via SSH.

## [Aug 13, 2024](/content/2024/08/13/README.md)

### Distributions / Webinterface

*   [nixbsd (⭐802)](https://github.com/nixos-bsd/nixbsd) - A NixOS fork with a FreeBSD kernel.
*   [SnowflakeOS](https://snowflakeos.org/) - A NixOS-based Linux distribution focused on beginner friendliness and ease of use.

## [Aug 12, 2024](/content/2024/08/12/README.md)

### Resources / Discovery

*   [NüschtOS Search (⭐129)](https://github.com/NuschtOS/search) - Simple and fast static-page NixOS option search.

## [Aug 09, 2024](/content/2024/08/09/README.md)

### NixOS Modules / Zig

*   [Self Host Blocks (⭐383)](https://github.com/ibizaman/selfhostblocks) - Modular server management based on NixOS modules and focused on best practices.

## [Aug 07, 2024](/content/2024/08/07/README.md)

### Development / Discovery

*   [compose2nix (⭐718)](https://github.com/aksiksi/compose2nix) - Generate a NixOS config from a Docker Compose project.

### NixOS Modules / Zig

*   [nix-mineral (⭐378)](https://github.com/cynicsketch/nix-mineral) - Conveniently and reasonably harden NixOS.

## [Jul 22, 2024](/content/2024/07/22/README.md)

### DevOps / Discovery

*   [nixidy (⭐254)](https://github.com/arnarg/nixidy) - Kubernetes GitOps with Nix and Argo CD.

### Programming Languages / Gleam

*   [nix-gleam (⭐44)](https://github.com/arnarg/nix-gleam) - Generic Nix builder for Gleam applications.

## [Jul 07, 2024](/content/2024/07/07/README.md)

### Deployment Tools / Discovery

*   [KubeNix (⭐426)](https://github.com/hall/kubenix) - A Kubernetes resource builder using Nix.

### Programming Languages / Haxe

*   [haxix (⭐5)](https://github.com/MadMcCrow/haxix) - Nix flake to build haxe/Heaps.io projects.
*   [kebab (⭐2)](https://github.com/bwkam/kebab) - Haxe packages for Nix.

### Distributions / Webinterface

*   [NixNG (⭐412)](https://github.com/nix-community/NixNG) - A GNU/Linux distribution similar to NixOS, defining difference is a focus on containers and lightweightness.

## [Apr 17, 2024](/content/2024/04/17/README.md)

### NixOS Modules / Zig

*   [impermanence (⭐1.6k)](https://github.com/nix-community/impermanence) - Lets you choose what files and directories you want to keep between reboots.

## [Apr 10, 2024](/content/2024/04/10/README.md)

### Resources / Learning

*   [NixOS Asia Tutorial Series](https://nixos.asia/en/tutorial) - A series of high-level tutorials on using Nix Flakes, NixOS, home-manager, etc.

### Deployment Tools / Discovery

*   [comin (⭐742)](https://github.com/nlewo/comin) - A deployment tool to continuously pull from Git repositories.

### Development / Discovery

*   [nix-health (⭐40)](https://github.com/juspay/nix-health) - A program to check the health of your Nix install. Furthermore, individual projects can configure their own health checks in their `flake.nix`.

### Community / Webinterface

*   [Wiki (Official)](https://wiki.nixos.org)

## [Apr 09, 2024](/content/2024/04/09/README.md)

### NixOS Modules / Zig

*   [nix-topology (⭐807)](https://github.com/oddlama/nix-topology) - Generate infrastructure and network diagrams directly from your NixOS configuration.

## [Apr 07, 2024](/content/2024/04/07/README.md)

### Development / Discovery

*   [attic (⭐1.6k)](https://github.com/zhaofengli/attic) - Multi-tenant Nix Binary Cache.

## [Mar 05, 2024](/content/2024/03/05/README.md)

### Resources / Learning

*   [Explainix](https://zaynetro.com/explainix) - Explain Nix syntax visually.

### Installation Media / Discovery

*   [nix-installer-scripts (⭐93)](https://github.com/dnkmmr69420/nix-installer-scripts) - Runs the official installer but does some tweaking as well such as adding fcontext for selinux and installing nix outside of the default profile so you don't accidently uninstall it.

### Overlays / Webinterface

*   [System Manager (⭐1.2k)](https://github.com/numtide/system-manager) - A non-NixOS Linux system configuration tool built on Nix.

## [Feb 23, 2024](/content/2024/02/23/README.md)

### Command-Line Tools / Discovery

*   [nix-output-monitor (⭐1.3k)](https://github.com/maralorn/nix-output-monitor) - A tool to produce useful graphs and statistics when building derivations.

## [Feb 14, 2024](/content/2024/02/14/README.md)

### Community / Webinterface

*   [NixCon](https://nixcon.org/) - The annual community conference for contributors and users of Nix and NixOS.

## [Dec 27, 2023](/content/2023/12/27/README.md)

### Development / Discovery

*   [flakelight (⭐344)](https://github.com/nix-community/flakelight) - A modular flake framework aiming to minimize boilerplate.
*   [services-flake (⭐660)](https://github.com/juspay/services-flake) - A NixOS-like service configuration framework for Nix flakes.

## [Nov 30, 2023](/content/2023/11/30/README.md)

### Development / Discovery

*   [templates (⭐116)](https://github.com/nix-community/templates) - Project templates for many languages using Nix flakes.

## [Nov 13, 2023](/content/2023/11/13/README.md)

### Command-Line Tools / Discovery

*   [devenv (⭐6k)](https://github.com/cachix/devenv) - A Nix-based tool for creating developer shell environments quickly and reproducibly.

## [Nov 08, 2023](/content/2023/11/08/README.md)

### Development / Discovery

*   [Snowfall Lib (⭐582)](https://github.com/snowfallorg/lib) - A library that makes it easy to manage your Nix flake by imposing an opinionated file structure.

## [Sep 05, 2023](/content/2023/09/05/README.md)

### NixOS Modules / Zig

*   [NixVim (⭐2.5k)](https://github.com/nix-community/nixvim) - A NeoVim distribution built with Nix modules and Nixpkgs.

## [Sep 04, 2023](/content/2023/09/04/README.md)

### Programming Languages / Zig

*   [zon2nix (⭐104)](https://github.com/nix-community/zon2nix) - Convert the dependencies in `build.zig.zon` to a Nix expression.

## [Jul 02, 2023](/content/2023/07/02/README.md)

### Resources / Learning

*   [Wombat's Book of Nix](https://mhwombat.codeberg.page/nix-book/) - A book-length introduction to Nix and flakes.

## [Jun 30, 2023](/content/2023/06/30/README.md)

### Resources / Learning

*   [Nix - A One Pager](https://code.tvl.fyi/about/nix/nix-1p) - A one page introduction to the Nix language.
*   [NixOS & Flakes Book (⭐2.9k)](https://github.com/ryan4yin/nixos-and-flakes-book) - An unofficial and opinionated NixOS & Flakes book for beginners.

## [Jun 19, 2023](/content/2023/06/19/README.md)

### Development / Discovery

*   [nixd (⭐1.2k)](https://github.com/nix-community/nixd) - Nix language server, based on Nix libraries.

### Overlays / Webinterface

*   [chaotic-nyx (⭐618)](https://github.com/chaotic-cx/nyx) - Daily bumped bleeding edge packages like `mesa_git` & others that aren't yet in Nixpkgs. Created by the makers of [Chaotic-AUR](https://github.com/chaotic-aur/).

## [Jun 08, 2023](/content/2023/06/08/README.md)

### Command-Line Tools / Discovery

*   [nix-melt (⭐286)](https://github.com/nix-community/nix-melt) - A ranger-like flake.lock viewer.

## [Jun 02, 2023](/content/2023/06/02/README.md)

### Resources / Learning

*   [Building a Rust service with Nix](https://fasterthanli.me/series/building-a-rust-service-with-nix) - An in-depth blog series about creating a Rust application with Nix.
*   [Nix from First Principles: Flake Edition](https://tonyfinn.com/blog/nix-from-first-principles-flake-edition/) - A modern crash-course to using Nix features, Flakes, and developing with Nix.
*   [Nix Shorts (⭐23)](https://github.com/alper/nix-shorts) - A collection of short notes about how to use Nix, updated for Nix Flakes.
*   [Zero to Nix](https://zero-to-nix.com/) - A flake-centric guide to Nix and its concepts created by Determinate Systems to quickly onboard beginners.

## [May 26, 2023](/content/2023/05/26/README.md)

### Installation Media / Discovery

*   [nixos-infect (⭐1.7k)](https://github.com/elitak/nixos-infect) - Replace a running non-NixOS Linux host with NixOS.

### Development / Discovery

*   [flox (⭐3.6k)](https://github.com/flox/flox) - Manage and share development environments, package projects, and publish artifacts anywhere.
*   [haumea (⭐371)](https://github.com/nix-community/haumea) - Filesystem-based module system for the Nix language similar to traditional programming languages, with support for file hierarchy and visibility.
*   [namaka (⭐131)](https://github.com/nix-community/namaka) - Snapshot testing for Nix based on haumea.

## [Apr 17, 2023](/content/2023/04/17/README.md)

### Programming Languages / OCaml

*   [opam2nix (⭐92)](https://github.com/timbertson/opam2nix) - Generate Nix expressions from opam packages.

## [Apr 13, 2023](/content/2023/04/13/README.md)

### Installation Media / Discovery

*   [nix-installer (⭐3.3k)](https://github.com/DeterminateSystems/nix-installer) - Opinionated alternative to the official Nix install scripts.

## [Mar 11, 2023](/content/2023/03/11/README.md)

### Command-Line Tools / Discovery

*   [deadnix (⭐669)](https://github.com/astro/deadnix) - Scan Nix files for dead code.

## [Feb 26, 2023](/content/2023/02/26/README.md)

### Deployment Tools / Discovery

*   [bento (⭐307)](https://github.com/rapenne-s/bento/) - A KISS deployment tool to keep your NixOS fleet (servers & workstations) up to date.

### Programming Languages / Clojure

*   [clj-nix (⭐169)](https://github.com/jlesquembre/clj-nix) - Nix helper functions for Clojure projects.

## [Feb 21, 2023](/content/2023/02/21/README.md)

### Command-Line Tools / Discovery

*   [nix-init (⭐1.2k)](https://github.com/nix-community/nix-init) - Generate Nix packages from URLs with hash prefetching, dependency inference, license detection, and more.

### Programming Languages / PureScript

*   [purs-nix (⭐79)](https://github.com/purs-nix/purs-nix) - CLI and library combo designed for managing PureScript projects using Nix. It provides a Nix API that can be used within your projects, as well as a command-line interface for managing your development process.

## [Jan 12, 2023](/content/2023/01/12/README.md)

### Resources / Discovery

*   [Noogle](https://noogle.dev/) - Nix API search engine allowing to search functions based on their types and other attributes.

## [Jan 02, 2023](/content/2023/01/02/README.md)

### Virtualisation / Discovery

*   [extra-container (⭐259)](https://github.com/erikarvstedt/extra-container) - Run declarative NixOS containers from the command line.

### Command-Line Tools / Discovery

*   [nurl (⭐624)](https://github.com/nix-community/nurl) - Generate Nix fetcher calls from repository URLs.

### Development / Discovery

*   [nil (⭐1.7k)](https://github.com/oxalica/nil) - NIx Language server, an incremental analysis assistent for writing in Nix.
*   [nix-update (⭐677)](https://github.com/Mic92/nix-update) - Update versions/source hashes of nix packages.

## [Dec 17, 2022](/content/2022/12/17/README.md)

### Deployment Tools / Discovery

*   [Nixinate (⭐279)](https://github.com/MatthewCroughan/nixinate) - A Nix flake library to provide app outputs for managing existing NixOS hosts over SSH.

## [Nov 10, 2022](/content/2022/11/10/README.md)

### DevOps / Discovery

*   [Standard (⭐471)](https://github.com/divnix/std) - An opinionated Nix Flakes framework to keep Nix code in large projects organized, accompanied by a friendly CLI/TUI optized for DevOps scenarios.

## [Oct 31, 2022](/content/2022/10/31/README.md)

### Resources / Discovery

*   [Home Manager Option Search](https://mipmip.github.io/home-manager-option-search/) - Search through all 2000+ Home Manager options and read how to use them.

## [Oct 16, 2022](/content/2022/10/16/README.md)

### Command-Line Tools / Discovery

*   [nix-du (⭐452)](https://github.com/symphorien/nix-du) - Visualise which gc-roots to delete to free some space in your Nix store.

## [Sep 26, 2022](/content/2022/09/26/README.md)

### Development / Discovery

*   [flake-utils-plus (⭐535)](https://github.com/gytis-ivaskevicius/flake-utils-plus) - A lightweight Nix library flake for painless NixOS flake configuration.

### NixOS Configuration Editors / Webinterface

*   [MyNixOS](https://mynixos.com/) - Graphical editor for Nix flakes. Create and manage configurations and modules for NixOS and Nix home-manager. Rather a Nix generator than a Nix editor, because it does not allow to import Nix files.

## [Sep 21, 2022](/content/2022/09/21/README.md)

### Command-Line Tools / Discovery

*   [manix (⭐414)](https://github.com/mlvzk/manix) - Find configuration options and function documentation for Nixpkgs, NixOS, and Home Manager.

### Development / Discovery

*   [flake.parts (⭐1.1k)](https://github.com/hercules-ci/flake-parts) - Minimal Nix modules framework for Flakes: split your flakes into modules and get things done with community modules.

### Programming Languages / Haskell

*   [haskell-flake (⭐216)](https://github.com/srid/haskell-flake) - A `flake-parts` Nix module for Haskell development.

## [Sep 08, 2022](/content/2022/09/08/README.md)

### Command-Line Tools / Discovery

*   [nixpkgs-hammering (⭐314)](https://github.com/jtojnar/nixpkgs-hammering) - An opinionated linter for Nixpkgs package expressions.

## [Aug 14, 2022](/content/2022/08/14/README.md)

### Development / Discovery

*   [dream2nix (⭐1.2k)](https://github.com/nix-community/dream2nix) - A framework for automatically converting packages from other build systems to Nix.
*   [rnix-lsp (⭐712)](https://github.com/nix-community/rnix-lsp) - A syntax-checking language server for Nix.

### Programming Languages / Rust

*   [crane (⭐1.2k)](https://github.com/ipetkov/crane) - A Nix library for building Cargo projects with incremental artifact caching.

## [Jul 10, 2022](/content/2022/07/10/README.md)

### Resources / Learning

*   [Nix Pills](https://nixos.org/guides/nix-pills/) - The best way to learn, with examples.

### Deployment Tools / Discovery

*   [Nixery (⭐1.9k)](https://github.com/tazjin/nixery) - A Docker-compatible container registry which builds images ad-hoc via Nix.

### Command-Line Tools / Discovery

*   [comma (⭐1.4k)](https://github.com/nix-community/comma) - Quickly run any binary; wraps together `nix run` and `nix-index`.
*   [nix-diff (⭐450)](https://github.com/Gabriella439/nix-diff) - A tool to explain why two Nix derivations differ.

### Development / Discovery

*   [lorri (⭐832)](https://github.com/nix-community/lorri/) - A much better `nix-shell` for development that augments direnv.

### Programming Languages / Elm

*   [elm2nix (⭐119)](https://github.com/cachix/elm2nix) - Convert `elm.json` into Nix expressions.

### Programming Languages / Node.js

*   [Napalm (⭐116)](https://github.com/nix-community/napalm) - Support for building npm packages in Nix with a lightweight npm registry.
*   [npmlock2nix (⭐143)](https://github.com/nix-community/npmlock2nix) - Generate Nix expressions from a `package-lock.json` (in-memory), primarily for web projects.

### Programming Languages / Rust

*   [cargo2nix (⭐446)](https://github.com/cargo2nix/cargo2nix) - Granular caching, development shell, Nix & Rust integration.

## [May 07, 2022](/content/2022/05/07/README.md)

### Command-Line Tools / Discovery

*   [alejandra (⭐1.2k)](https://github.com/kamadorueda/alejandra) - An opinionated Nix code formatter optimized for speed and consistency.

## [Mar 24, 2022](/content/2022/03/24/README.md)

### DevOps / Discovery

*   [Makes (⭐497)](https://github.com/fluidattacks/makes) - A Nix-based CI/CD pipeline framework for building, testing, and releasing projects in any language, from anywhere.

## [Mar 21, 2022](/content/2022/03/21/README.md)

### NixOS Modules / Zig

*   [Home Manager (⭐8.9k)](https://github.com/nix-community/home-manager) - Manage your user configuration just like NixOS.

## [Mar 12, 2022](/content/2022/03/12/README.md)

### Channel History / Discovery

*   [Nix Review Tools Reports](https://malob.github.io/nix-review-tools-reports/) - Reports showing problematic dependencies (dependencies causing the most failed builds) for major Hydra jobsets.

## [Feb 17, 2022](/content/2022/02/17/README.md)

### Programming Languages / PHP

*   [composer-plugin-nixify (⭐17)](https://github.com/stephank/composer-plugin-nixify) - Composer plugin to help with Nix packaging.
*   [nix-shell (⭐176)](https://github.com/loophp/nix-shell/) - Nix shells for PHP development.

### NixOS Modules / Zig

*   [base16.nix (⭐257)](https://github.com/SenchoPens/base16.nix) - Flake way to theme programs in [base16 (⭐857)](https://github.com/chriskempson/base16) colorschemes, mustache template support included.

## [Jan 07, 2022](/content/2022/01/07/README.md)

### Overlays / Webinterface

*   [nixpkgs-firefox-darwin (⭐73)](https://github.com/bandithedoge/nixpkgs-firefox-darwin) - Automatically updated Firefox binary packages for macOS.

## [Dec 31, 2021](/content/2021/12/31/README.md)

### Deployment Tools / Discovery

*   [deploy-rs (⭐1.9k)](https://github.com/serokell/deploy-rs) - A simple multi-profile Nix-flake deploy tool.

## [Dec 29, 2021](/content/2021/12/29/README.md)

### Resources / Discovery

*   [Nix Package Versions](https://lazamar.co.uk/nix-versions/) - Find all versions of a package that were available in a channel and the revision you can download it from.

### Command-Line Tools / Discovery

*   [nix-alien (⭐722)](https://github.com/thiagokokada/nix-alien) - Run unpatched binaries on Nix/NixOS easily.

## [Dec 23, 2021](/content/2021/12/23/README.md)

### Overlays / Webinterface

*   [nixpkgs-wayland (⭐582)](https://github.com/nix-community/nixpkgs-wayland) - Bleeding-edge Wayland packages.

## [Nov 22, 2021](/content/2021/11/22/README.md)

### Resources / Learning

*   [How to Learn Nix](https://ianthehenry.com/posts/how-to-learn-nix/) - It's like a Let's Play, but for obscure software documentation.

## [Nov 19, 2021](/content/2021/11/19/README.md)

### Programming Languages / Scala

*   [sbt-derivation (⭐75)](https://github.com/zaninime/sbt-derivation) - mkDerivation for sbt, similar to buildGoModule.

## [Nov 03, 2021](/content/2021/11/03/README.md)

### Programming Languages / Rust

*   [fenix (⭐934)](https://github.com/nix-community/fenix) - Rust toolchains and Rust analyzer nightly for nix.
*   [nixpkgs-mozilla (⭐570)](https://github.com/mozilla/nixpkgs-mozilla) - Mozilla's overlay with Rust toolchains and Firefox.
*   [rust-overlay (⭐1.3k)](https://github.com/oxalica/rust-overlay) - Pure and reproducible nix overlay of binary distributed Rust toolchains.

### Community / Webinterface

*   [#nixos on Libera.Chat](https://web.libera.chat/?nick=Guest?#nixos)

## [Jul 12, 2021](/content/2021/07/12/README.md)

### Channel History / Discovery

*   [nixpkgs PR tracker](https://nixpk.gs/pr-tracker.html) - A tracker for whether a PR has made it into a channel yet.

### Development / Discovery

*   [devshell (⭐1.4k)](https://github.com/numtide/devshell) - `mkShell` with extra bits and a toml config option to be able to onboard non-nix users.
*   [flake-utils (⭐1.5k)](https://github.com/numtide/flake-utils) - Pure Nix flake utility functions to help with writing flakes.

## [Jul 08, 2021](/content/2021/07/08/README.md)

### Programming Languages / Node.js

*   [node2nix (⭐571)](https://github.com/svanderburg/node2nix) - Generate Nix expression from a `package.json` (or `package-lock.json`) (to be stored as files).

## [Jun 14, 2021](/content/2021/06/14/README.md)

### Programming Languages / PHP

*   [composer2nix (⭐93)](https://github.com/svanderburg/composer2nix) - Generate Nix expressions to build composer packages.
*   [composition-c4 (⭐11)](https://github.com/fossar/composition-c4) - Support for building composer packages from a `composer.lock` (using IFD).
*   [nix-phps (⭐79)](https://github.com/fossar/nix-phps) - Flake containing old and unmaintained PHP versions (intended for CI use).

## [May 25, 2021](/content/2021/05/25/README.md)

### Programming Languages / Haskell

*   [nix-haskell-mode (⭐29)](https://github.com/matthewbauer/nix-haskell-mode) - Automatic Haskell setup in Emacs.
*   [nixkell (⭐118)](https://github.com/pwm/nixkell) - A Haskell project template using Nix and direnv.

### Community / Webinterface

*   [#nix:nixos.org](https://matrix.to/#/#nix:nixos.org)

## [Apr 14, 2021](/content/2021/04/14/README.md)

### Installation Media / Discovery

*   [nixos-up (⭐251)](https://github.com/samuela/nixos-up) - Super easy NixOS installer that can be used from the installation ISO.

## [Apr 10, 2021](/content/2021/04/10/README.md)

### Deployment Tools / Discovery

*   [pushnix (⭐34)](https://github.com/arnarg/pushnix) - Simple cli utility that pushes NixOS configuration and triggers a rebuild using ssh.

## [Apr 07, 2021](/content/2021/04/07/README.md)

### Command-Line Tools / Discovery

*   [nix-tree (⭐939)](https://github.com/utdemir/nix-tree) - Interactively browse the dependency graph of Nix derivations.

## [Mar 31, 2021](/content/2021/03/31/README.md)

### Deployment Tools / Discovery

*   [Colmena (⭐1.9k)](https://github.com/zhaofengli/colmena) - A simple, stateless NixOS deployment tool modeled after NixOps and morph.

### Programming Languages / Crystal

*   [crystal2nix (⭐19)](https://github.com/nix-community/crystal2nix) - Convert `shard.lock` into Nix expressions.

## [Mar 30, 2021](/content/2021/03/30/README.md)

### Programming Languages / Arduino

*   [nixduino (⭐51)](https://github.com/boredom101/nixduino) - Nix-based tool to help build Arduino sketches.

## [Mar 24, 2021](/content/2021/03/24/README.md)

### Resources / Learning

*   [nix.dev](https://nix.dev/) - An opinionated guide for developers about getting things done using the Nix ecosystem.

### Installation Media / Discovery

*   [nixos-generators (⭐2.3k)](https://github.com/nix-community/nixos-generators) -  Take a NixOS config and build multiple different images types including VirtualBox VMs, Azure images, and installation ISOs.

### Channel History / Discovery

*   [Nix Infra Status](https://status.nixos.org) - Get the age and current git commit of each Nix channel.

### Deployment Tools / Discovery

*   [krops](https://cgit.krebsco.de/krops/about/) - A lightweight toolkit to deploy NixOS systems, remotely or locally.
*   [KuberNix (⭐796)](https://github.com/saschagrunert/kubernix) - Single-dependency Kubernetes clusters via Nix packages.
*   [NixOps (⭐2.1k)](https://github.com/NixOS/nixops) - The official Nix deployment tool, compatible with AWS, Hetzner, and more.

### Command-Line Tools / Discovery

*   [nix-prefetch (⭐142)](https://github.com/msteen/nix-prefetch) - A universal tool for updating source checksums.

### Development / Discovery

*   [Arion (⭐820)](https://github.com/hercules-ci/arion) - Run `docker-compose` with help from Nix/NixOS.
*   [cached-nix-shell (⭐226)](https://github.com/xzfc/cached-nix-shell) - A `nix-shell` replacement that uses caching to open subsequent shells quickly.
*   [gitignore.nix (⭐274)](https://github.com/hercules-ci/gitignore.nix) - The most feature-complete and easy-to-use `.gitignore` integration.
*   [niv (⭐1.8k)](https://github.com/nmattia/niv/) - Easy dependency management for Nix projects with package pinning.
*   [nixpkgs-review (⭐548)](https://github.com/Mic92/nixpkgs-review) - The best tool to verify that a pull-request in Nixpkgs is building properly.

### Programming Languages / PureScript

*   [Easy PureScript Nix (⭐206)](https://github.com/justinwoo/easy-purescript-nix) - A project to easily use PureScript and other tools with Nix.

### Programming Languages / Python

*   [poetry2nix (⭐936)](https://github.com/nix-community/poetry2nix) - Build Python packages directly from [Poetry's](https://python-poetry.org/) `poetry.lock`. No conversion step needed.

### Programming Languages / Ruby

*   [Bundix (⭐179)](https://github.com/nix-community/bundix) - Generates a Nix expression for your Bundler-managed application.

### NixOS Modules / Zig

*   [musnix (⭐803)](https://github.com/musnix/musnix) - Do real-time audio work in NixOS.
*   [nix-bitcoin (⭐581)](https://github.com/fort-nix/nix-bitcoin) - Modules and packages for Bitcoin nodes with higher-layer protocols with an emphasis on security.
*   [Simple Nixos Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - A complete mailserver, managed with NixOS modules.

### Overlays / Webinterface

*   [NUR (⭐1.7k)](https://github.com/nix-community/NUR/) - Nix User Repositories. The mother of all overlays, allowing access to user repositories and installing packages via attributes.

### Community / Webinterface

*   [Discourse](https://discourse.nixos.org/) - The best place to get help and discuss Nix-related topics.

## [Mar 23, 2021](/content/2021/03/23/README.md)

### Channel History / Discovery

*   [Channel History](https://channels.nix.gsc.io) - Get historical git commits for Nix channels.

## [Mar 22, 2021](/content/2021/03/22/README.md)

### Development / Discovery

*   [nix-direnv (⭐2.4k)](https://github.com/nix-community/nix-direnv) - A fast loader and flake-compliant configuration for the direnv environment auto-loader.

### Programming Languages / Haskell

*   [cabal2nix (⭐391)](https://github.com/NixOS/cabal2nix) - Converts a Cabal file into a Nix build expression.
*   [haskell.nix (⭐611)](https://github.com/input-output-hk/haskell.nix) - Alternative Haskell Infrastructure for Nixpkgs.

### Overlays / Webinterface

*   [awesome-nix-hpc (⭐91)](https://github.com/freuk/awesome-nix-hpc) - High Performance Computing package sets.

## [Feb 17, 2020](/content/2020/02/17/README.md)

### Virtualisation / Discovery

*   [nixos-shell (⭐788)](https://github.com/Mic92/nixos-shell) - Simple headless VM configuration using Nix (similar to Vagrant).

## [Dec 18, 2019](/content/2019/12/18/README.md)

### Resources / Learning

*   [Nix Notes (⭐59)](https://github.com/noteed/nix-notes) - A collection of short notes about Nix, each contributing to the same virtual machine image.

## [Sep 16, 2019](/content/2019/09/16/README.md)

### Community / Webinterface

*   [Wiki (Unofficial)](https://nixos.wiki)

## [Sep 12, 2019](/content/2019/09/12/README.md)

### Deployment Tools / Discovery

*   [morph (⭐993)](https://github.com/DBCDK/morph) - A tool for managing existing NixOS hosts.
*   [terranix](https://terranix.org) - Use Nix and the NixOS module system to write your Terraform code.

## [Sep 07, 2019](/content/2019/09/07/README.md)

### Community / Webinterface

*   [Discord - Nix/Nixos (Unofficial)](https://discord.gg/BMUCQx6)