# Awesome Nix Overview

😎 A curated list of the best resources in the Nix community [maintainer=@cyntheticfox]

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/nix-community/awesome-nix/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 nix-community/awesome-nix](https://github.com/nix-community/awesome-nix) · ⭐ 5.3K · 🏷️ Platforms

[ [Daily](/content/nix-community/awesome-nix/README.md) / [Weekly](/content/nix-community/awesome-nix/week/README.md) / Overview ]

---

# Awesome Nix [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

<a href="https://nixos.org">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/NixOS/nixos-artwork/master/logo/nixos.svg">
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NixOS/nixos-artwork/master/logo/nixos-white.png">
    <img src="https://raw.githubusercontent.com/NixOS/nixos-artwork/master/logo/nixos.svg" align="right" width="250" alt="NixOS logo">
  </picture>
</a>

A curated list of the best resources in the Nix community.

<br>

[Nix (⭐17k)](https://github.com/nixos/nix) is a powerful package manager for Linux and other Unix systems that makes package management reliable and reproducible.

*Please read the [contribution guidelines](https://github.com/nix-community/awesome-nix/blob/main/README.md/CONTRIBUTING.md) before contributing.*

## Contents

*   [Resources](#resources)
    *   [Learning](#learning)
    *   [Discovery](#discovery)
*   [Installation Media](#installation-media)
*   [Channel History](#channel-history)
*   [Deployment Tools](#deployment-tools)
*   [Virtualisation](#virtualisation)
*   [Command-Line Tools](#command-line-tools)
*   [Development](#development)
*   [DevOps](#devops)
*   [Programming Languages](#programming-languages)
    *   [Arduino](#arduino)
    *   [Clojure](#clojure)
    *   [Crystal](#crystal)
    *   [Elm](#elm)
    *   [Gleam](#gleam)
    *   [Haskell](#haskell)
    *   [Haxe](#haxe)
    *   [Julia](#julia)
    *   [Lean](#lean)
    *   [Node.js](#nodejs)
    *   [OCaml](#ocaml)
    *   [PHP](#php)
    *   [PureScript](#purescript)
    *   [Python](#python)
    *   [Ruby](#ruby)
    *   [Rust](#rust)
    *   [Scala](#scala)
    *   [Zig](#zig)
*   [NixOS Modules](#nixos-modules)
*   [NixOS Configuration Editors](#nixos-configuration-editors)
*   [Overlays](#overlays)
*   [Distributions](#distributions)
*   [Community](#community)

## Resources

### Learning

*   [Building a Rust service with Nix](https://fasterthanli.me/series/building-a-rust-service-with-nix) - An in-depth blog series about creating a Rust application with Nix.
*   [Explainix](https://zaynetro.com/explainix) - Explain Nix syntax visually.
*   [How to Learn Nix](https://ianthehenry.com/posts/how-to-learn-nix/) - It's like a Let's Play, but for obscure software documentation.
*   [Nix - A One Pager](https://code.tvl.fyi/about/nix/nix-1p) - A one page introduction to the Nix language.
*   [nix-book](https://saylesss88.github.io) - A comprehensive guide to NixOS
    hardening and configuration.
*   [Nix from First Principles: Flake Edition](https://tonyfinn.com/blog/nix-from-first-principles-flake-edition/) - A modern crash-course to using Nix features, Flakes, and developing with Nix.
*   [Nix in 100 Seconds](https://www.youtube.com/watch?v=FJVFXsNzYZQ) - A YouTube video from Fireship presenting Nix in 100 seconds.
*   [Nix Notes (⭐61)](https://github.com/noteed/nix-notes) - A collection of short notes about Nix, each contributing to the same virtual machine image.
*   [Nix Pills](https://nixos.org/guides/nix-pills/) - The best way to learn, with examples.
*   [Nix Shorts (⭐24)](https://github.com/alper/nix-shorts) - A collection of short notes about how to use Nix, updated for Nix Flakes.
*   [Nix Starter Config (⭐3.7k)](https://github.com/Misterio77/nix-starter-configs) - A few simple Nix Flake templates for getting started with NixOS + home-manager.
*   [nix.dev](https://nix.dev/) - An opinionated guide for developers about getting things done using the Nix ecosystem.
*   [NixOS & Flakes Book (⭐3.2k)](https://github.com/ryan4yin/nixos-and-flakes-book) - An unofficial and opinionated NixOS & Flakes book for beginners.
*   [NixOS Asia Tutorial Series](https://nixos.asia/en/tutorial) - A series of high-level tutorials on using Nix Flakes, NixOS, home-manager, etc.
*   [NixOS in Production](https://leanpub.com/nixos-in-production) - Free (pay-what-you-want) book in pdf format.
*   [Official Nix manual](https://nix.dev/manual/nix/stable/) - Latest stable version of the official Nix manual, best used as reference guide. Receives updates when available.
*   [Official NixOS manual](https://nixos.org/manual/nixos/stable/) - Latest stable version of the official NixOS manual, mix of tutorial and reference guide. Receives updates when available.
*   [Official Nixpkgs manual](https://nixos.org/manual/nixpkgs/stable/) - Latest stable version of the official Nixpkgs reference manual. Receives updates when available.
*   [Tour of Nix](https://nixcloud.io/tour/) - An online interactive tutorial on Nix language constructs.
*   [Wombat's Book of Nix](https://mhwombat.codeberg.page/nix-book/) - A book-length introduction to Nix and flakes.
*   [Zero to Nix](https://zero-to-nix.com/) - A flake-centric guide to Nix and its concepts created by Determinate Systems to quickly onboard beginners.

### Discovery

*   [Home Manager Option Search](https://home-manager-options.extranix.com/) - Search through all 2000+ Home Manager options and read how to use them.

<!-- * [Hound](https://search.nix.gsc.io) - Handily search across all or selected Nix-related repositories. -->

*   [Nix Package Versions](https://lazamar.co.uk/nix-versions/) - Find all versions of a package that were available in a channel and the revision you can download it from.
*   [nix-search-tv (⭐269)](https://github.com/3timeslazy/nix-search-tv) - CLI fuzzy finder for packages and options from Nixpkgs, Home Manager, and more.
*   [Noogle](https://noogle.dev/) - Nix API search engine allowing to search functions based on their types and other attributes.
*   [NüschtOS Search (⭐160)](https://github.com/NuschtOS/search) - Simple and fast static-page NixOS option search.
*   [Searchix](https://searchix.ovh/) - Search Nix packages and options from NixOS, Darwin and Home Manager.

## Installation Media

*   [nix-installer-scripts (⭐95)](https://github.com/dnkmmr69420/nix-installer-scripts) - Runs the official installer but does some tweaking as well such as adding fcontext for selinux and installing nix outside of the default profile so you don't accidently uninstall it.
*   [nix-installer (⭐3.6k)](https://github.com/DeterminateSystems/nix-installer) - Opinionated alternative to the official Nix install scripts.
*   [nixos-anywhere (⭐3.3k)](https://github.com/nix-community/nixos-anywhere) - Install NixOS everywhere via SSH.
*   [nixos-generators (⭐2.4k)](https://github.com/nix-community/nixos-generators) -  Take a NixOS config and build multiple different images types including VirtualBox VMs, Azure images, and installation ISOs.
*   [nixos-infect (⭐1.9k)](https://github.com/elitak/nixos-infect) - Replace a running non-NixOS Linux host with NixOS.
*   [nixos-up (⭐255)](https://github.com/samuela/nixos-up) - Super easy NixOS installer that can be used from the installation ISO.

## Channel History

*   [`npc`](https://github.com/samestep/npc) - CLI to view and bisect Nixpkgs channel history.
*   [Nix Infra Status](https://status.nixos.org) - Get the age and current Git commit of each Nix channel.
*   [Nix Review Tools Reports](https://malob.github.io/nix-review-tools-reports/) - Reports showing problematic dependencies (dependencies causing the most failed builds) for major Hydra jobsets.

<!-- * [Nixpkgs Bot](https://git.maralorn.de/nixos-config/tree/packages/nixpkgs-bot) - A Matrix bot to track when a Nixpkgs pull request reaches a relevant branch. -->

*   [nixpkgs PR tracker](https://nixpk.gs/pr-tracker.html) - A tracker for whether a PR has made it into a channel yet.

## Deployment Tools

*   [bento (⭐324)](https://github.com/rapenne-s/bento/) - A KISS deployment tool to keep your NixOS fleet (servers & workstations) up to date.
*   [Clan](https://clan.lol) - A peer-to-peer deployment tool with inbuilt support for secrets and a module system to manage distributed networks.
*   [Colmena (⭐2.2k)](https://github.com/zhaofengli/colmena) - A simple, stateless NixOS deployment tool modeled after NixOps and morph.
*   [comin (⭐930)](https://github.com/nlewo/comin) - A deployment tool to continuously pull from Git repositories.
*   [deploy-rs (⭐2.2k)](https://github.com/serokell/deploy-rs) - A simple multi-profile Nix-flake deploy tool.
*   [krops](https://cgit.krebsco.de/krops/about/) - A lightweight toolkit to deploy NixOS systems, remotely or locally.
*   [KubeNix (⭐498)](https://github.com/hall/kubenix) - A Kubernetes resource builder using Nix.
*   [KuberNix (⭐819)](https://github.com/saschagrunert/kubernix) - Single-dependency Kubernetes clusters via Nix packages.
*   [morph (⭐1k)](https://github.com/DBCDK/morph) - A tool for managing existing NixOS hosts.
*   [Nixery (⭐2k)](https://github.com/tazjin/nixery) - A Docker-compatible container registry which builds images ad-hoc via Nix.
*   [Nixinate (⭐291)](https://github.com/MatthewCroughan/nixinate) - A Nix flake library to provide app outputs for managing existing NixOS hosts over SSH.
*   [Nixlets](https://gitlab.com/TECHNOFAB/nixlets) - Like Helm but using only Nix, uses Kubenix under the hood.
*   [NixOps (⭐2.2k)](https://github.com/NixOS/nixops) - The official Nix deployment tool, compatible with AWS, Hetzner, and more.
*   [pushnix (⭐34)](https://github.com/arnarg/pushnix) - Simple cli utility that pushes NixOS configuration and triggers a rebuild using ssh.
*   [terraform-nixos (⭐413)](https://github.com/nix-community/terraform-nixos) - A set of Terraform modules designed to deploy NixOS.
*   [terranix](https://terranix.org) - Use Nix and the NixOS module system to write your Terraform code.

## Virtualisation

*   [extra-container (⭐297)](https://github.com/erikarvstedt/extra-container) - Run declarative NixOS containers from the command line.
*   [microvm (⭐2.7k)](https://github.com/microvm-nix/microvm.nix) - NixOS-based MicroVMs.
*   [nixos-shell (⭐898)](https://github.com/Mic92/nixos-shell) - Simple headless VM configuration using Nix (similar to Vagrant).

## Command-Line Tools

*   [alejandra (⭐1.4k)](https://github.com/kamadorueda/alejandra) - An opinionated Nix code formatter optimized for speed and consistency.
*   [angrr (⭐138)](https://github.com/linyinfeng/angrr) - Auto Nix GC Roots Retention. This tool simply deletes auto GC roots based on the modified time of their symbolic link target.
*   [comma (⭐1.7k)](https://github.com/nix-community/comma) - Quickly run any binary; wraps together `nix run` and `nix-index`.
*   [deadnix (⭐766)](https://github.com/astro/deadnix) - Scan Nix files for dead code.
*   [devenv (⭐7.1k)](https://github.com/cachix/devenv) - A Nix-based tool for creating developer shell environments quickly and reproducibly.
*   [dix (⭐311)](https://github.com/faukah/dix) - Diff Nix; a super-fast tool to diff Nix related things.
*   [manix (⭐422)](https://github.com/mlvzk/manix) - Find configuration options and function documentation for Nixpkgs, NixOS, and Home Manager.
*   [nh (⭐2.9k)](https://github.com/nix-community/nh) - Better output for `nix`, `nixos-rebuild`, `home-manager` and nix-darwin CLI leveraging `dix` and `nix-output-monitor`.
*   [nix-alien (⭐838)](https://github.com/thiagokokada/nix-alien) - Run unpatched binaries on Nix/NixOS easily.
*   [nix-diff (⭐487)](https://github.com/Gabriella439/nix-diff) - A tool to explain why two Nix derivations differ.
*   [nix-du (⭐482)](https://github.com/symphorien/nix-du) - Visualise which gc-roots to delete to free some space in your Nix store.
*   [nix-index (⭐1.3k)](https://github.com/nix-community/nix-index) - Quickly locate Nix packages with specific files.
*   [nix-init (⭐1.4k)](https://github.com/nix-community/nix-init) - Generate Nix packages from URLs with hash prefetching, dependency inference, license detection, and more.
*   [nix-melt (⭐307)](https://github.com/nix-community/nix-melt) - A ranger-like flake.lock viewer.
*   [nix-output-monitor (⭐1.6k)](https://github.com/maralorn/nix-output-monitor) - A tool to produce useful graphs and statistics when building derivations.
*   [nix-prefetch (⭐149)](https://github.com/msteen/nix-prefetch) - A universal tool for updating source checksums.
*   [nix-tree (⭐1k)](https://github.com/utdemir/nix-tree) - Interactively browse the dependency graph of Nix derivations.
*   [nixfmt (⭐1.5k)](https://github.com/NixOS/nixfmt) - A formatter for Nix code, intended to easily apply a uniform style.
*   [nixos-cli (⭐388)](https://github.com/nix-community/nixos-cli) - Configurable all-in-one CLI for common NixOS tools with an emphasis on improved user experience.
*   [nixpkgs-hammering (⭐333)](https://github.com/jtojnar/nixpkgs-hammering) - An opinionated linter for Nixpkgs package expressions.
*   [nurl (⭐752)](https://github.com/nix-community/nurl) - Generate Nix fetcher calls from repository URLs.
*   [nvd](https://git.sr.ht/~khumba/nvd) - Diff package versions between two store paths; it's especially useful for comparing NixOS generations on rebuild.
*   [optnix](https://git.sr.ht/~watersucks/optnix) - A terminal-based options searcher for Nix module systems.
*   [statix (⭐927)](https://github.com/oppiliappan/statix) - A linter/fixer to check for and fix antipatterns in Nix code.

## Development

*   [Arion (⭐901)](https://github.com/hercules-ci/arion) - Run `docker-compose` with help from Nix/NixOS.
*   [attic (⭐2k)](https://github.com/zhaofengli/attic) - Multi-tenant Nix Binary Cache.
*   [cached-nix-shell (⭐229)](https://github.com/xzfc/cached-nix-shell) - A `nix-shell` replacement that uses caching to open subsequent shells quickly.
*   [Cachix](https://www.cachix.org) - Hosted binary cache service; free for open-source projects.
*   [compose2nix (⭐862)](https://github.com/aksiksi/compose2nix) - Generate a NixOS config from a Docker Compose project.
*   [Conflake](https://ratson.github.io/conflake/) - A batteries included, autoload files, convention-based configuration framework for `flake.nix`.
*   [Devbox (⭐12k)](https://github.com/jetify-com/devbox) - Instant, portable, and predictable development environments.
*   [devshell (⭐1.5k)](https://github.com/numtide/devshell) - `mkShell` with extra bits and a toml config option to be able to onboard non-nix users.
*   [dream2nix (⭐1.3k)](https://github.com/nix-community/dream2nix) - A framework for automatically converting packages from other build systems to Nix.
*   [flake-utils-plus (⭐550)](https://github.com/gytis-ivaskevicius/flake-utils-plus) - A lightweight Nix library flake for painless NixOS flake configuration.
*   [flake-utils (⭐1.6k)](https://github.com/numtide/flake-utils) - Pure Nix flake utility functions to help with writing flakes.
*   [flake.parts (⭐1.4k)](https://github.com/hercules-ci/flake-parts) - Minimal Nix modules framework for Flakes: split your flakes into modules and get things done with community modules.
*   [flakelight (⭐404)](https://github.com/nix-community/flakelight) - A modular flake framework aiming to minimize boilerplate.
*   [flox (⭐4k)](https://github.com/flox/flox) - Manage and share development environments, package projects, and publish artifacts anywhere.
*   [gitignore.nix (⭐286)](https://github.com/hercules-ci/gitignore.nix) - The most feature-complete and easy-to-use `.gitignore` integration.
*   [haumea (⭐413)](https://github.com/nix-community/haumea) - Filesystem-based module system for the Nix language similar to traditional programming languages, with support for file hierarchy and visibility.
*   [lorri (⭐863)](https://github.com/nix-community/lorri/) - A much better `nix-shell` for development that augments direnv.
*   [make-shell (⭐35)](https://github.com/nicknovitski/make-shell) - `mkShell` meets modules, a modular almost-drop-in replacement for `pkgs.mkShell` function.
*   [MCP-NixOS (⭐738)](https://github.com/utensils/mcp-nixos) - An MCP server that provides AI assistants with accurate information about NixOS packages, options, Home Manager, and nix-darwin configurations.
*   [namaka (⭐144)](https://github.com/nix-community/namaka) - Snapshot testing for Nix based on haumea.
*   [nil (⭐1.9k)](https://github.com/oxalica/nil) - NIx Language server, an incremental analysis assistent for writing in Nix.
*   [niv (⭐1.8k)](https://github.com/nmattia/niv/) - Easy dependency management for Nix projects with package pinning.
*   [nix2container (⭐868)](https://github.com/nlewo/nix2container) - An efficient container building workflow with Nix.
*   [nix-direnv (⭐2.7k)](https://github.com/nix-community/nix-direnv) - A fast loader and flake-compliant configuration for the direnv environment auto-loader.
*   [nix-health (⭐48)](https://github.com/juspay/nix-health) - A program to check the health of your Nix install. Furthermore, individual projects can configure their own health checks in their `flake.nix`.
*   [nix-oci (⭐105)](https://github.com/Dauliac/nix-oci) - A flake-parts module for building minimal, reproducible OCI containers using nix2container.
*   [nix-update (⭐825)](https://github.com/Mic92/nix-update) - Update versions/source hashes of nix packages.
*   [nixd (⭐1.4k)](https://github.com/nix-community/nixd) - Nix language server, based on Nix libraries.
*   [nixpkgs-review (⭐621)](https://github.com/Mic92/nixpkgs-review) - The best tool to verify that a pull-request in Nixpkgs is building properly.
*   [Nixtest](https://gitlab.com/TECHNOFAB/nixtest) - Testing framework for Nix, with snapshot and unit test support, JUnit generation etc.
*   [npins (⭐542)](https://github.com/andir/npins) - A simple tool for handling different types of dependencies in a Nix project. It is inspired by and comparable to Niv.
*   [pog (⭐181)](https://github.com/jpetrucciani/pog) - A new, powerful way to do bash scripts. Pog is a powerful Nix library that transforms the way developers create command-line interfaces (CLIs).
*   [pre-commit-hooks.nix (⭐839)](https://github.com/cachix/git-hooks.nix) - Run linters/formatters at commit time and on your CI.
*   [rnix-lsp (⭐710)](https://github.com/nix-community/rnix-lsp) - A syntax-checking language server for Nix.
*   [robotnix (⭐792)](https://github.com/nix-community/robotnix) - A declarative and reproducible build system for Android (AOSP) images.
*   [services-flake (⭐747)](https://github.com/juspay/services-flake) - A NixOS-like service configuration framework for Nix flakes.
*   [Snowfall Lib (⭐622)](https://github.com/snowfallorg/lib) - A library that makes it easy to manage your Nix flake by imposing an opinionated file structure.
*   [templates (⭐144)](https://github.com/nix-community/templates) - Project templates for many languages using Nix flakes.
*   [treefmt-nix (⭐619)](https://github.com/numtide/treefmt-nix) - A formatter that allows formatting all your project files with a single command, all via a single `.nix` file.

## DevOps

*   [Nix GitLab CI](https://gitlab.com/TECHNOFAB/nix-gitlab-ci) - Define GitLab CI pipelines in pure Nix with full access to all Nix packages (incl. caching).
*   [nixidy (⭐359)](https://github.com/arnarg/nixidy) - Kubernetes GitOps with Nix and Argo CD.
*   [Standard (⭐484)](https://github.com/divnix/std) - An opinionated Nix Flakes framework to keep Nix code in large projects organized, accompanied by a friendly CLI/TUI optized for DevOps scenarios.

## Programming Languages

### Arduino

*   [nixduino (⭐52)](https://github.com/boredom101/nixduino) - Nix-based tool to help build Arduino sketches.

### Clojure

*   [clj-nix (⭐181)](https://github.com/jlesquembre/clj-nix) - Nix helper functions for Clojure projects.

### Crystal

*   [crystal2nix (⭐19)](https://github.com/nix-community/crystal2nix) - Convert `shard.lock` into Nix expressions.

### Elm

*   [elm2nix (⭐124)](https://github.com/cachix/elm2nix) - Convert `elm.json` into Nix expressions.

### Gleam

*   [nix-gleam (⭐66)](https://github.com/arnarg/nix-gleam) - Generic Nix builder for Gleam applications.

### Haskell

*   [cabal2nix (⭐402)](https://github.com/NixOS/cabal2nix) - Converts a Cabal file into a Nix build expression.
*   [haskell-flake (⭐234)](https://github.com/srid/haskell-flake) - A `flake-parts` Nix module for Haskell development.
*   [haskell.nix (⭐627)](https://github.com/input-output-hk/haskell.nix) - Alternative Haskell Infrastructure for Nixpkgs.
*   [nix-haskell-mode (⭐29)](https://github.com/matthewbauer/nix-haskell-mode) - Automatic Haskell setup in Emacs.
*   [nixkell (⭐121)](https://github.com/pwm/nixkell) - A Haskell project template using Nix and direnv.

### Haxe

*   [haxix (⭐5)](https://github.com/MadMcCrow/haxix) - Nix flake to build haxe/Heaps.io projects.
*   [kebab (⭐2)](https://github.com/bwkam/kebab) - Haxe packages for Nix.

### Julia

*   [Manifest2Nix.jl](https://codeberg.org/aniva/Manifest2Nix.jl) - A Nix library for creating reproducible Julia builds and experiments via precompilation.

### Lean

*   [lean4-nix (⭐113)](https://github.com/lenianiva/lean4-nix) -  Nix flake build for Lean 4, and `lake2nix`.

### Node.js

*   [Napalm (⭐117)](https://github.com/nix-community/napalm) - Support for building npm packages in Nix with a lightweight npm registry.
*   [node2nix (⭐589)](https://github.com/svanderburg/node2nix) - Generate Nix expression from a `package.json` (or `package-lock.json`) (to be stored as files).
*   [npmlock2nix (⭐148)](https://github.com/nix-community/npmlock2nix) - Generate Nix expressions from a `package-lock.json` (in-memory), primarily for web projects.

### OCaml

*   [opam2nix (⭐93)](https://github.com/timbertson/opam2nix) - Generate Nix expressions from opam packages.

### PHP

*   [composer-plugin-nixify (⭐17)](https://github.com/stephank/composer-plugin-nixify) - Composer plugin to help with Nix packaging.
*   [composer2nix (⭐92)](https://github.com/svanderburg/composer2nix) - Generate Nix expressions to build composer packages.
*   [composition-c4 (⭐13)](https://github.com/fossar/composition-c4) - Support for building composer packages from a `composer.lock` (using IFD).
*   [nix-phps (⭐82)](https://github.com/fossar/nix-phps) - Flake containing old and unmaintained PHP versions (intended for CI use).
*   [nix-shell (⭐179)](https://github.com/loophp/nix-shell/) - Nix shells for PHP development.

### PureScript

*   [Easy PureScript Nix (⭐209)](https://github.com/justinwoo/easy-purescript-nix) - A project to easily use PureScript and other tools with Nix.
*   [purs-nix (⭐82)](https://github.com/purs-nix/purs-nix) - CLI and library combo designed for managing PureScript projects using Nix. It provides a Nix API that can be used within your projects, as well as a command-line interface for managing your development process.

### Python

*   [poetry2nix (⭐930)](https://github.com/nix-community/poetry2nix) - Build Python packages directly from [Poetry's](https://python-poetry.org/) `poetry.lock`. No conversion step needed.
*   [uv2nix (⭐755)](https://github.com/pyproject-nix/uv2nix) - Convert [`uv` workspaces](https://docs.astral.sh/uv/concepts/projects/workspaces/) into pure Nix derivations.

### Ruby

*   [Bundix (⭐181)](https://github.com/nix-community/bundix) - Generates a Nix expression for your Bundler-managed application.
*   [ruby-nix (⭐152)](https://github.com/inscapist/ruby-nix) - Generates reproducible ruby/bundler app environment with Nix.

### Rust

*   [cargo2nix (⭐466)](https://github.com/cargo2nix/cargo2nix) - Granular caching, development shell, Nix & Rust integration.
*   [crane (⭐1.4k)](https://github.com/ipetkov/crane) - A Nix library for building Cargo projects with incremental artifact caching.
*   [fenix (⭐1.1k)](https://github.com/nix-community/fenix) - Rust toolchains and Rust analyzer nightly for nix.
*   [naersk (⭐996)](https://github.com/nix-community/naersk) - Build Rust packages directly from `Cargo.lock`. No conversion step needed.
*   [nix-cargo-integration (⭐220)](https://github.com/90-008/nix-cargo-integration) - A library that allows easy and effortless integration for Cargo projects.
*   [nixpkgs-mozilla (⭐576)](https://github.com/mozilla/nixpkgs-mozilla) - Mozilla's overlay with Rust toolchains and Firefox.
*   [rust-nix-templater (⭐48)](https://github.com/90-008/rust-nix-templater) - Generates Nix build and development files for Rust projects.
*   [rust-overlay (⭐1.5k)](https://github.com/oxalica/rust-overlay) - Pure and reproducible nix overlay of binary distributed Rust toolchains.

### Scala

*   [sbt-derivation (⭐75)](https://github.com/zaninime/sbt-derivation) - mkDerivation for sbt, similar to buildGoModule.

### Zig

*   [zig2nix (⭐180)](https://github.com/Cloudef/zig2nix) - Flake for packaging, building and running Zig projects.
*   [zon2nix (⭐118)](https://github.com/nix-community/zon2nix) - Convert the dependencies in `build.zig.zon` to a Nix expression.

## NixOS Modules

*   [base16.nix (⭐283)](https://github.com/SenchoPens/base16.nix) - Flake way to theme programs in [base16 (⭐938)](https://github.com/chriskempson/base16) colorschemes, mustache template support included.
*   [Home Manager (⭐10k)](https://github.com/nix-community/home-manager) - Manage your user configuration just like NixOS.
*   [impermanence (⭐1.8k)](https://github.com/nix-community/impermanence) - Lets you choose what files and directories you want to keep between reboots.
*   [musnix (⭐929)](https://github.com/musnix/musnix) - Do real-time audio work in NixOS.
*   [nix-bitcoin (⭐608)](https://github.com/fort-nix/nix-bitcoin) - Modules and packages for Bitcoin nodes with higher-layer protocols with an emphasis on security.
*   [nix-darwin (⭐5.6k)](https://github.com/nix-darwin/nix-darwin) - Manage macOS configuration just like on NixOS.
*   [nix-mineral (⭐531)](https://github.com/cynicsketch/nix-mineral) - Conveniently and reasonably harden NixOS.
*   [nix-topology (⭐973)](https://github.com/oddlama/nix-topology) - Generate infrastructure and network diagrams directly from your NixOS configuration.
*   [NixOS hardware (⭐3.2k)](https://github.com/NixOS/nixos-hardware) - NixOS profiles to optimize settings for different hardware.
*   [NixOS-WSL (⭐3k)](https://github.com/nix-community/NixOS-WSL) - Modules for running NixOS on the Windows Subsystem for Linux.
*   [Nixvim (⭐2.9k)](https://github.com/nix-community/nixvim) - A pre-packaged Neovim distribution built with Nix modules and Nixpkgs.
*   [nvf (⭐1.6k)](https://github.com/NotAShelf/nvf) - A portable, modular Neovim configuration framework for Nix.
*   [Self Host Blocks (⭐463)](https://github.com/ibizaman/selfhostblocks) - Modular server management based on NixOS modules and focused on best practices.
*   [Simple Nixos Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - A complete mailserver, managed with NixOS modules.
*   [Stylix (⭐2.3k)](https://github.com/nix-community/stylix) - System-wide colorscheming and typography for NixOS.

## NixOS Configuration Editors

### Desktop apps

*   [Nix Software Center (⭐836)](https://github.com/snowfallorg/nix-software-center) - Install and manage Nix packages. Desktop app in Rust and GTK.
*   [NixOS Configuration Editor (⭐668)](https://github.com/snowfallorg/nixos-conf-editor) - Graphical editor for NixOS configuration. Desktop app in Rust and GTK.

### Webinterface

*   [MyNixOS](https://mynixos.com/) - Graphical editor for Nix flakes. Create and manage configurations and modules for NixOS and Nix home-manager. Rather a Nix generator than a Nix editor, because it does not allow to import Nix files.

## Overlays

*   [awesome-nix-hpc (⭐101)](https://github.com/freuk/awesome-nix-hpc) - High Performance Computing package sets.
*   [neovim-nightly-overlay (⭐416)](https://github.com/nix-community/neovim-nightly-overlay) - Daily bumped Neovim nightly package.
*   [nixpkgs-firefox-darwin (⭐75)](https://github.com/bandithedoge/nixpkgs-firefox-darwin) - Automatically updated Firefox binary packages for macOS.
*   [nixpkgs-wayland (⭐618)](https://github.com/nix-community/nixpkgs-wayland) - Bleeding-edge Wayland packages.
*   [NUR (⭐1.9k)](https://github.com/nix-community/NUR/) - Nix User Repositories. The mother of all overlays, allowing access to user repositories and installing packages via attributes.
*   [System Manager (⭐1.6k)](https://github.com/numtide/system-manager) - A non-NixOS Linux system configuration tool built on Nix.
*   [zig-overlay (⭐521)](https://github.com/mitchellh/zig-overlay) - A Nix flake packaging the Zig compiler. The flake mirrors the binaries built officially by Zig and does not build them from source.

## Distributions

*   [nixbsd (⭐990)](https://github.com/nixos-bsd/nixbsd) - A NixOS fork with a FreeBSD kernel.
*   [NixNG (⭐478)](https://github.com/nix-community/NixNG) - A GNU/Linux distribution similar to NixOS. The defining difference is a focus on containers and lightweightness.
*   [SnowflakeOS](https://snowflakeos.org/) - A NixOS-based Linux distribution focused on beginner friendliness and ease of use.

## Community

*   [#nix:nixos.org](https://matrix.to/#/#nix:nixos.org)
*   [#nixos on Libera.Chat](https://web.libera.chat/?nick=Guest?#nixos)
*   [Discord - Nix/Nixos (Unofficial)](https://discord.com/invite/BMUCQx6)
*   [Discourse](https://discourse.nixos.org/) - The best place to get help and discuss Nix-related topics.
*   [NixCon](https://nixcon.org/) - The annual community conference for contributors and users of Nix and NixOS.
*   [Wiki (Official)](https://wiki.nixos.org/wiki/Main_Page)
*   [Wiki (Unofficial)](https://nixos.wiki/wiki/Main_Page)

