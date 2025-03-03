# Awesome Nix Overview

😎 A curated list of the best resources in the Nix community [maintainer=@cyntheticfox]

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/nix-community/awesome-nix/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 nix-community/awesome-nix](https://github.com/nix-community/awesome-nix) · ⭐ 3.7K · 🏷️ Platforms

[ [Daily](/content/nix-community/awesome-nix/README.md) / [Weekly](/content/nix-community/awesome-nix/week/README.md) / Overview ]

---

# Awesome Nix [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://nixos.org/logo/nixos-logo-only-hires.png" width="200" align="right" alt="NixOS">](https://nixos.org)

> A curated list of the best resources in the Nix community.

[Nix (⭐14k)](https://github.com/nixos/nix) is a powerful package manager for Linux and other Unix systems that makes package management reliable and reproducible.

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
*   [Nix from First Principles: Flake Edition](https://tonyfinn.com/blog/nix-from-first-principles-flake-edition/) - A modern crash-course to using Nix features, Flakes, and developing with Nix.
*   [Nix in 100 Seconds](https://youtu.be/FJVFXsNzYZQ?si=lf_HgLiHYAnX-_vx) - A YouTube video from Fireship presenting Nix in 100 seconds.
*   [Nix Notes (⭐58)](https://github.com/noteed/nix-notes) - A collection of short notes about Nix, each contributing to the same virtual machine image.
*   [Nix Pills](https://nixos.org/guides/nix-pills/) - The best way to learn, with examples.
*   [Nix Shorts (⭐19)](https://github.com/alper/nix-shorts) - A collection of short notes about how to use Nix, updated for Nix Flakes.
*   [Nix Starter Config (⭐2.9k)](https://github.com/Misterio77/nix-starter-configs) - A few simple Nix Flake templates for getting started with NixOS + home-manager.
*   [nix.dev](https://nix.dev/) - An opinionated guide for developers about getting things done using the Nix ecosystem.
*   [NixOS & Flakes Book (⭐2.3k)](https://github.com/ryan4yin/nixos-and-flakes-book) - An unofficial and opinionated NixOS & Flakes book for beginners.
*   [NixOS Asia Tutorial Series](https://nixos.asia/en/tutorial) - A series of high-level tutorials on using Nix Flakes, NixOS, home-manager, etc.
*   [Tour of Nix](https://nixcloud.io/tour) - An online interactive tutorial on Nix language constructs.
*   [Wombat's Book of Nix](https://mhwombat.codeberg.page/nix-book/) - A book-length introduction to Nix and flakes.
*   [Zero to Nix](https://zero-to-nix.com/) - A flake-centric guide to Nix and its concepts created by Determinate Systems to quickly onboard beginners.

### Discovery

<!-- * [Hound](https://search.nix.gsc.io) - Handily search across all or selected Nix-related repositories. -->

*   [Nix Package Versions](https://lazamar.co.uk/nix-versions/) - Find all versions of a package that were available in a channel and the revision you can download it from.
*   [nix-search-tv (⭐39)](https://github.com/3timeslazy/nix-search-tv) - CLI fuzzy finder for packages and options from Nixpkgs, Home Manager, and more.
*   [Noogle](https://noogle.dev/) - Nix API search engine allowing to search functions based on their types and other attributes.
*   [Home Manager Option Search](https://mipmip.github.io/home-manager-option-search/) - Search through all 2000+ Home Manager options and read how to use them.
*   [NüschtOS Search (⭐83)](https://github.com/NuschtOS/search) - Simple and fast static-page NixOS option search.
*   [Searchix](https://searchix.alanpearce.eu/) - Search Nix packages and options from NixOS, Darwin and Home Manager.

## Installation Media

*   [nixos-anywhere (⭐2k)](https://github.com/nix-community/nixos-anywhere) - Install NixOS everywhere via SSH.
*   [nixos-generators (⭐2k)](https://github.com/nix-community/nixos-generators) -  Take a NixOS config and build multiple different images types including VirtualBox VMs, Azure images, and installation ISOs.
*   [nixos-infect (⭐1.5k)](https://github.com/elitak/nixos-infect) - Replace a running non-NixOS Linux host with NixOS.
*   [nixos-up (⭐239)](https://github.com/samuela/nixos-up) - Super easy NixOS installer that can be used from the installation ISO.
*   [nix-installer (⭐2.6k)](https://github.com/DeterminateSystems/nix-installer) - Opinionated alternative to the official Nix install scripts.
*   [nix-installer-scripts (⭐91)](https://github.com/dnkmmr69420/nix-installer-scripts) - Runs the official installer but does some tweaking as well such as adding fcontext for selinux and installing nix outside of the default profile so you don't accidently uninstall it.

## Channel History

*   [Channel History](https://channels.nix.gsc.io) - Get historical git commits for Nix channels.
*   [Nix Infra Status](https://status.nixos.org) - Get the age and current git commit of each Nix channel.
*   [Nix Review Tools Reports](https://malob.github.io/nix-review-tools-reports/) - Reports showing problematic dependencies (dependencies causing the most failed builds) for major Hydra jobsets.

<!-- * [Nixpkgs Bot](https://git.maralorn.de/nixos-config/tree/packages/nixpkgs-bot) - A Matrix bot to track when a Nixpkgs pull request reaches a relevant branch. -->

*   [nixpkgs PR tracker](https://nixpk.gs/pr-tracker.html) - A tracker for whether a PR has made it into a channel yet.

## Deployment Tools

*   [bento (⭐263)](https://github.com/rapenne-s/bento/) - A KISS deployment tool to keep your NixOS fleet (servers & workstations) up to date.
*   [Colmena (⭐1.4k)](https://github.com/zhaofengli/colmena) - A simple, stateless NixOS deployment tool modeled after NixOps and morph.
*   [comin (⭐549)](https://github.com/nlewo/comin) - A deployment tool to continuously pull from Git repositories.
*   [deploy-rs (⭐1.5k)](https://github.com/serokell/deploy-rs) - A simple multi-profile Nix-flake deploy tool.
*   [krops](https://cgit.krebsco.de/krops/about/) - A lightweight toolkit to deploy NixOS systems, remotely or locally.
*   [KubeNix (⭐340)](https://github.com/hall/kubenix) - A Kubernetes resource builder using Nix.
*   [KuberNix (⭐772)](https://github.com/saschagrunert/kubernix) - Single-dependency Kubernetes clusters via Nix packages.
*   [morph (⭐880)](https://github.com/DBCDK/morph) - A tool for managing existing NixOS hosts.
*   [Nixery (⭐1.9k)](https://github.com/tazjin/nixery) - A Docker-compatible container registry which builds images ad-hoc via Nix.
*   [Nixinate (⭐256)](https://github.com/MatthewCroughan/nixinate) - A Nix flake library to provide app outputs for managing existing NixOS hosts over SSH.
*   [NixOps (⭐1.9k)](https://github.com/NixOS/nixops) - The official Nix deployment tool, compatible with AWS, Hetzner, and more.
*   [pushnix (⭐34)](https://github.com/arnarg/pushnix) - Simple cli utility that pushes NixOS configuration and triggers a rebuild using ssh.
*   [terraform-nixos (⭐350)](https://github.com/tweag/terraform-nixos) - A set of Terraform modules designed to deploy NixOS.
*   [terranix](https://terranix.org) - Use Nix and the NixOS module system to write your Terraform code.

## Virtualisation

*   [nixos-shell (⭐715)](https://github.com/Mic92/nixos-shell) - Simple headless VM configuration using Nix (similar to Vagrant).
*   [extra-container (⭐226)](https://github.com/erikarvstedt/extra-container) - Run declarative NixOS containers from the command line.
*   [microvm (⭐1.6k)](https://github.com/astro/microvm.nix) - NixOS-based MicroVMs.

## Command-Line Tools

*   [alejandra (⭐1k)](https://github.com/kamadorueda/alejandra) - An opinionated Nix code formatter optimized for speed and consistency.
*   [comma (⭐1.2k)](https://github.com/nix-community/comma) - Quickly run any binary; wraps together `nix run` and `nix-index`.
*   [deadnix (⭐549)](https://github.com/astro/deadnix) - Scan Nix files for dead code.
*   [devenv (⭐4.9k)](https://github.com/cachix/devenv) - A Nix-based tool for creating developer shell environments quickly and reproducibly.
*   [manix (⭐376)](https://github.com/mlvzk/manix) - Find configuration options and function documentation for Nixpkgs, NixOS, and Home Manager.
*   [nh (⭐1.3k)](https://github.com/viperML/nh) - Better output for `nix` `nixos-rebuild` and home-manger CLI using `nvd` and `nix-output-monitor`.
*   [nixfmt (⭐1k)](https://github.com/NixOS/nixfmt) - A formatter for Nix code, intended to easily apply a uniform style.
*   [nixpkgs-hammering (⭐263)](https://github.com/jtojnar/nixpkgs-hammering) - An opinionated linter for Nixpkgs package expressions.
*   [nix-alien (⭐599)](https://github.com/thiagokokada/nix-alien) - Run unpatched binaries on Nix/NixOS easily.
*   [nix-diff (⭐382)](https://github.com/Gabriella439/nix-diff) - A tool to explain why two Nix derivations differ.
*   [nix-du (⭐405)](https://github.com/symphorien/nix-du) - Visualise which gc-roots to delete to free some space in your Nix store.
*   [nix-index (⭐925)](https://github.com/bennofs/nix-index) - Quickly locate Nix packages with specific files.
*   [nix-init (⭐971)](https://github.com/nix-community/nix-init) - Generate Nix packages from URLs with hash prefetching, dependency inference, license detection, and more.
*   [nix-melt (⭐253)](https://github.com/nix-community/nix-melt) - A ranger-like flake.lock viewer.
*   [nix-output-monitor (⭐1k)](https://github.com/maralorn/nix-output-monitor) - A tool to produce useful graphs and statistics when building derivations.
*   [nix-prefetch (⭐130)](https://github.com/msteen/nix-prefetch) - A universal tool for updating source checksums.
*   [nix-tree (⭐818)](https://github.com/utdemir/nix-tree) - Interactively browse the dependency graph of Nix derivations.
*   [nurl (⭐526)](https://github.com/nix-community/nurl) - Generate Nix fetcher calls from repository URLs.
*   [nvd](https://git.sr.ht/~khumba/nvd) - Diff package versions between two store paths; it's especially useful for comparing NixOS generations on rebuild.
*   [statix (⭐602)](https://github.com/nerdypepper/statix) - A linter/fixer to check for and fix antipatterns in Nix code.

## Development

*   [attic (⭐1.2k)](https://github.com/zhaofengli/attic) - Multi-tenant Nix Binary Cache.
*   [Arion (⭐729)](https://github.com/hercules-ci/arion) - Run `docker-compose` with help from Nix/NixOS.
*   [cached-nix-shell (⭐218)](https://github.com/xzfc/cached-nix-shell) - A `nix-shell` replacement that uses caching to open subsequent shells quickly.
*   [Cachix](https://cachix.org/) - Hosted binary cache service; free for open-source projects.
*   [compose2nix (⭐502)](https://github.com/aksiksi/compose2nix) - Generate a NixOS config from a Docker Compose project.
*   [Conflake](https://ratson.github.io/conflake/) - A batteries included, autoload files, convention-based configuration framework for `flake.nix`.
*   [Devbox (⭐9.5k)](https://github.com/jetpack-io/devbox) - Instant, portable, and predictable development environments.
*   [devshell (⭐1.3k)](https://github.com/numtide/devshell) - `mkShell` with extra bits and a toml config option to be able to onboard non-nix users.
*   [dream2nix (⭐1.1k)](https://github.com/nix-community/dream2nix) - A framework for automatically converting packages from other build systems to Nix.
*   [flake.parts (⭐847)](https://github.com/hercules-ci/flake-parts) - Minimal Nix modules framework for Flakes: split your flakes into modules and get things done with community modules.
*   [flake-utils (⭐1.3k)](https://github.com/numtide/flake-utils) - Pure Nix flake utility functions to help with writing flakes.
*   [flake-utils-plus (⭐499)](https://github.com/gytis-ivaskevicius/flake-utils-plus) - A lightweight Nix library flake for painless NixOS flake configuration.
*   [flakelight (⭐260)](https://github.com/nix-community/flakelight) - A modular flake framework aiming to minimize boilerplate.
*   [flox (⭐3k)](https://github.com/flox/flox) - Manage and share development environments, package projects, and publish artifacts anywhere.
*   [gitignore.nix (⭐251)](https://github.com/hercules-ci/gitignore.nix) - The most feature-complete and easy-to-use `.gitignore` integration.
*   [haumea (⭐322)](https://github.com/nix-community/haumea) - Filesystem-based module system for the Nix language similar to traditional programming languages, with support for file hierarchy and visibility.
*   [lorri (⭐747)](https://github.com/nix-community/lorri/) - A much better `nix-shell` for development that augments direnv.
*   [namaka (⭐117)](https://github.com/nix-community/namaka) - Snapshot testing for Nix based on haumea.
*   [nil (⭐1.4k)](https://github.com/oxalica/nil) - NIx Language server, an incremental analysis assistent for writing in Nix.
*   [niv (⭐1.7k)](https://github.com/nmattia/niv/) - Easy dependency management for Nix projects with package pinning.
*   [nix-direnv (⭐2.1k)](https://github.com/nix-community/nix-direnv) - A fast loader and flake-compliant configuration for the direnv environment auto-loader.
*   [nix-health (⭐31)](https://github.com/juspay/nix-health) - A program to check the health of your Nix install. Furthermore, individual projects can configure their own health checks in their `flake.nix`.
*   [nix-update (⭐562)](https://github.com/Mic92/nix-update) - Update versions/source hashes of nix packages.
*   [nixd (⭐995)](https://github.com/nix-community/nixd) - Nix language server, based on Nix libraries.
*   [nixpkgs-review (⭐454)](https://github.com/Mic92/nixpkgs-review) - The best tool to verify that a pull-request in Nixpkgs is building properly.
*   [npins (⭐260)](https://github.com/andir/npins) - A simple tool for handling different types of dependencies in a Nix project. It is inspired by and comparable to Niv.
*   [pre-commit-hooks.nix (⭐598)](https://github.com/cachix/pre-commit-hooks.nix) - Run linters/formatters at commit time and on your CI.
*   [rnix-lsp (⭐707)](https://github.com/nix-community/rnix-lsp) - A syntax-checking language server for Nix.
*   [robotnix (⭐656)](https://github.com/danielfullmer/robotnix) - A declarative and reproducible build system for Android (AOSP) images.
*   [services-flake (⭐460)](https://github.com/juspay/services-flake) - A NixOS-like service configuration framework for Nix flakes.
*   [Snowfall Lib (⭐480)](https://github.com/snowfallorg/lib) - A library that makes it easy to manage your Nix flake by imposing an opinionated file structure.
*   [templates (⭐78)](https://github.com/nix-community/templates) - Project templates for many languages using Nix flakes.

## DevOps

*   [Makes (⭐471)](https://github.com/fluidattacks/makes) - A Nix-based CI/CD pipeline framework for building, testing, and releasing projects in any language, from anywhere.
*   [nixidy (⭐132)](https://github.com/arnarg/nixidy) - Kubernetes GitOps with Nix and Argo CD.
*   [Nix GitLab CI](https://gitlab.com/technofab/nix-gitlab-ci) - Define GitLab CI pipelines in pure Nix with full access to all Nix packages (incl. caching).
*   [Standard (⭐423)](https://github.com/divnix/std) - An opinionated Nix Flakes framework to keep Nix code in large projects organized, accompanied by a friendly CLI/TUI optized for DevOps scenarios.

## Programming Languages

### Arduino

*   [nixduino](https://github.com/boredom101/nixduino) - Nix-based tool to help build Arduino sketches.

### Clojure

*   [clj-nix (⭐160)](https://github.com/jlesquembre/clj-nix) - Nix helper functions for Clojure projects.

### Crystal

*   [crystal2nix (⭐15)](https://github.com/nix-community/crystal2nix) - Convert `shard.lock` into Nix expressions.

### Elm

*   [elm2nix (⭐114)](https://github.com/cachix/elm2nix) - Convert `elm.json` into Nix expressions.

### Gleam

*   [nix-gleam (⭐22)](https://github.com/arnarg/nix-gleam) - Generic Nix builder for Gleam applications.

### Haskell

*   [cabal2nix (⭐366)](https://github.com/NixOS/cabal2nix) - Converts a Cabal file into a Nix build expression.
*   [haskell-flake (⭐170)](https://github.com/srid/haskell-flake) - A `flake-parts` Nix module for Haskell development.
*   [haskell.nix (⭐574)](https://github.com/input-output-hk/haskell.nix) - Alternative Haskell Infrastructure for Nixpkgs.
*   [nix-haskell-mode (⭐28)](https://github.com/matthewbauer/nix-haskell-mode) - Automatic Haskell setup in Emacs.
*   [nixkell (⭐105)](https://github.com/pwm/nixkell) - A Haskell project template using Nix and direnv.

### Haxe

*   [haxix (⭐3)](https://github.com/MadMcCrow/haxix) - Nix flake to build haxe/Heaps.io projects.
*   [kebab (⭐2)](https://github.com/bwkam/kebab) - Haxe packages for Nix.

### Lean

*   [lean4-nix (⭐33)](https://github.com/lenianiva/lean4-nix) -  Nix flake build for Lean 4, and `lake2nix`.

### Node.js

*   [Napalm (⭐109)](https://github.com/nix-community/napalm) - Support for building npm packages in Nix with a lightweight npm registry.
*   [node2nix (⭐538)](https://github.com/svanderburg/node2nix) - Generate Nix expression from a `package.json` (or `package-lock.json`) (to be stored as files).
*   [npmlock2nix](https://github.com/nix-community/npmlock2nix) - Generate Nix expressions from a `package-lock.json` (in-memory), primarily for web projects.

### OCaml

*   [opam2nix (⭐94)](https://github.com/timbertson/opam2nix) - Generate Nix expressions from opam packages.

### PHP

*   [composer2nix (⭐89)](https://github.com/svanderburg/composer2nix) - Generate Nix expressions to build composer packages.
*   [composer-plugin-nixify (⭐17)](https://github.com/stephank/composer-plugin-nixify) - Composer plugin to help with Nix packaging.
*   [composition-c4 (⭐11)](https://github.com/fossar/composition-c4) - Support for building composer packages from a `composer.lock` (using IFD).
*   [nix-phps (⭐69)](https://github.com/fossar/nix-phps) - Flake containing old and unmaintained PHP versions (intended for CI use).
*   [nix-shell (⭐166)](https://github.com/loophp/nix-shell/) - Nix shells for PHP development.

### PureScript

*   [Easy PureScript Nix (⭐198)](https://github.com/justinwoo/easy-purescript-nix) - A project to easily use PureScript and other tools with Nix.
*   [purs-nix (⭐75)](https://github.com/purs-nix/purs-nix) - CLI and library combo designed for managing PureScript projects using Nix. It provides a Nix API that can be used within your projects, as well as a command-line interface for managing your development process.

### Python

*   [poetry2nix (⭐913)](https://github.com/nix-community/poetry2nix) - Build Python packages directly from [Poetry's](https://python-poetry.org/) `poetry.lock`. No conversion step needed.

### Ruby

*   [Bundix (⭐169)](https://github.com/nix-community/bundix) - Generates a Nix expression for your Bundler-managed application.
*   [ruby-nix (⭐125)](https://github.com/sagittaros/ruby-nix) - Generates reproducible ruby/bundler app environment with Nix.

### Rust

*   [cargo2nix (⭐400)](https://github.com/cargo2nix/cargo2nix) - Granular caching, development shell, Nix & Rust integration.
*   [crane (⭐1k)](https://github.com/ipetkov/crane) - A Nix library for building Cargo projects with incremental artifact caching.
*   [fenix (⭐763)](https://github.com/nix-community/fenix) - Rust toolchains and Rust analyzer nightly for nix.
*   [naersk (⭐784)](https://github.com/nmattia/naersk) - Build Rust packages directly from `Cargo.lock`. No conversion step needed.
*   [nix-cargo-integration](https://github.com/yusdacra/nix-cargo-integration) - A library that allows easy and effortless integration for Cargo projects.
*   [nixpkgs-mozilla (⭐543)](https://github.com/mozilla/nixpkgs-mozilla) - Mozilla's overlay with Rust toolchains and Firefox.
*   [rust-nix-templater (⭐49)](https://github.com/yusdacra/rust-nix-templater) - Generates Nix build and development files for Rust projects.
*   [rust-overlay (⭐1k)](https://github.com/oxalica/rust-overlay) - Pure and reproducible nix overlay of binary distributed Rust toolchains.

### Scala

*   [sbt-derivation (⭐67)](https://github.com/zaninime/sbt-derivation) - mkDerivation for sbt, similar to buildGoModule.

### Zig

*   [zon2nix (⭐81)](https://github.com/nix-community/zon2nix) - Convert the dependencies in `build.zig.zon` to a Nix expression.

## NixOS Modules

*   [base16.nix (⭐218)](https://github.com/SenchoPens/base16.nix) - Flake way to theme programs in [base16 (⭐745)](https://github.com/chriskempson/base16) colorschemes, mustache template support included.
*   [Home Manager (⭐7.6k)](https://github.com/nix-community/home-manager) - Manage your user configuration just like NixOS.
*   [nix-darwin (⭐3.7k)](https://github.com/LnL7/nix-darwin) - Manage macOS configuration just like on NixOS.
*   [NixOS-WSL](https://github.com/nix-community/NixOS-WSL) - Modules for running NixOS on the Windows Subsystem for Linux.
*   [musnix (⭐651)](https://github.com/musnix/musnix) - Do real-time audio work in NixOS.
*   [NixVim](https://github.com/nix-community/nixvim) - A NeoVim distribution built with Nix modules and Nixpkgs.
*   [Self Host Blocks (⭐240)](https://github.com/ibizaman/selfhostblocks) - Modular server management based on NixOS modules and focused on best practices.
*   [Simple Nixos Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - A complete mailserver, managed with NixOS modules.
*   [Stylix (⭐1.5k)](https://github.com/danth/stylix) - System-wide colorscheming and typography for NixOS.
*   [nix-bitcoin (⭐545)](https://github.com/fort-nix/nix-bitcoin) - Modules and packages for Bitcoin nodes with higher-layer protocols with an emphasis on security.
*   [nix-mineral (⭐223)](https://github.com/cynicsketch/nix-mineral) - Conveniently and reasonably harden NixOS.
*   [nix-topology (⭐644)](https://github.com/oddlama/nix-topology) - Generate infrastructure and network diagrams directly from your NixOS configuration.
*   [impermanence (⭐1.3k)](https://github.com/nix-community/impermanence) - Lets you choose what files and directories you want to keep between reboots.

## NixOS Configuration Editors

### Desktop apps

*   [NixOS Configuration Editor (⭐532)](https://github.com/vlinkz/nixos-conf-editor) - Graphical editor for NixOS configuration. Desktop app in Rust and GTK.
*   [Nix Software Center (⭐645)](https://github.com/vlinkz/nix-software-center) - Install and manage Nix packages. Desktop app in Rust and GTK.

### Webinterface

*   [MyNixOS](https://mynixos.com/) - Graphical editor for Nix flakes. Create and manage configurations and modules for NixOS and Nix home-manager. Rather a Nix generator than a Nix editor, because it does not allow to import Nix files.

## Overlays

*   [awesome-nix-hpc (⭐80)](https://github.com/freuk/awesome-nix-hpc) - High Performance Computing package sets.
*   [chaotic-nyx (⭐422)](https://github.com/chaotic-cx/nyx) - Daily bumped bleeding edge packages like `mesa_git` & others that aren't yet in Nixpkgs. Created by the makers of [Chaotic-AUR](https://github.com/chaotic-aur/).
*   [nixpkgs-firefox-darwin](https://github.com/bandithedoge/nixpkgs-firefox-darwin) - Automatically updated Firefox binary packages for macOS.
*   [nixpkgs-wayland (⭐542)](https://github.com/nix-community/nixpkgs-wayland) - Bleeding-edge Wayland packages.
*   [NUR](https://github.com/nix-community/NUR/) - Nix User Repositories. The mother of all overlays, allowing access to user repositories and installing packages via attributes.
*   [System Manager (⭐913)](https://github.com/numtide/system-manager) - A non-NixOS Linux system configuration tool built on Nix.

## Distributions

*   [nixbsd (⭐620)](https://github.com/nixos-bsd/nixbsd) - A NixOS fork with a FreeBSD kernel.
*   [NixNG (⭐343)](https://github.com/nix-community/NixNG) - A GNU/Linux distribution similar to NixOS, defining difference is a focus on containers and lightweightness.
*   [SnowflakeOS](https://snowflakeos.org/) - A NixOS-based Linux distribution focused on beginner friendliness and ease of use.

## Community

*   [#nix:nixos.org](https://matrix.to/#/#nix:nixos.org)
*   [#nixos on Libera.Chat](https://web.libera.chat/?nick=Guest?#nixos)
*   [Discord - Nix/Nixos (Unofficial)](https://discord.gg/BMUCQx6)
*   [Discourse](https://discourse.nixos.org/) - The best place to get help and discuss Nix-related topics.
*   [NixCon](https://nixcon.org/) - The annual community conference for contributors and users of Nix and NixOS.
*   [Wiki (Official)](https://wiki.nixos.org)
*   [Wiki (Unofficial)](https://nixos.wiki)

