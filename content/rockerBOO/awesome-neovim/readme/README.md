# Awesome Neovim Overview

Collections of awesome neovim plugins.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/rockerBOO/awesome-neovim/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 rockerBOO/awesome-neovim](https://github.com/rockerBOO/awesome-neovim) · ⭐ 20K · 🏷️ Editors

[ [Daily](/content/rockerBOO/awesome-neovim/README.md) / [Weekly](/content/rockerBOO/awesome-neovim/week/README.md) / Overview ]

---

# Awesome Neovim [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

<a href="https://neovim.io/"><img src="https://neovim.io/logos/neovim-mark-flat.png" align="right" width="144" /></a>

> Collections of awesome Neovim plugins. Mostly targeting Neovim specific features. This means Vim-compatible plugins are not listed here.

[Neovim](https://neovim.io/) is a Vim-based text editor engineered for extensibility and usability, to encourage new applications and contributions.

## Contents

*   [Plugin Manager](#plugin-manager)
*   [LSP](#lsp)
    *   [LSP Installer](#lsp-installer)
    *   [Diagnostics](#diagnostics)
*   [Completion](#completion)
*   [AI](#ai)
*   [Programming Languages Support](#programming-languages-support)
    *   [Golang](#golang)
    *   [YAML](#yaml)
    *   [Web Development](#web-development)
    *   [Markdown and LaTeX](#markdown-and-latex)
    *   [PHP](#php)
    *   [Powershell](#powershell)
    *   [Assembly](#assembly)
*   [Language](#language)
*   [Syntax](#syntax)
*   [Snippet](#snippet)
*   [Register](#register)
*   [Marks](#marks)
*   [Search](#search)
*   [Fuzzy Finder](#fuzzy-finder)
*   [File Explorer](#file-explorer)
*   [Project](#project)
*   [Color](#color)
*   [Colorscheme](#colorscheme)
    *   [Colorscheme Creation](#colorscheme-creation)
    *   [Colorscheme Switchers](#colorscheme-switchers)
*   [Bars and Lines](#bars-and-lines)
    *   [Statusline](#statusline)
    *   [Tabline](#tabline)
    *   [Cursorline](#cursorline)
*   [Startup](#startup)
*   [Icon](#icon)
*   [Media](#media)
*   [Note Taking](#note-taking)
*   [Utility](#utility)
    *   [CSV Files](#csv-files)
*   [Animation](#animation)
*   [Terminal Integration](#terminal-integration)
*   [Debugging](#debugging)
    *   [Quickfix](#quickfix)
*   [Deployment](#deployment)
*   [Test](#test)
*   [Code Runner](#code-runner)
*   [Neovim Lua Development](#neovim-lua-development)
*   [Fennel](#fennel)
*   [Dependency Management](#dependency-management)
*   [Git](#git)
    *   [GitHub](#github)
    *   [GitLab](#gitlab)
*   [Motion](#motion)
    *   [Tree-sitter Based](#tree-sitter-based)
*   [Keybinding](#keybinding)
*   [Mouse](#mouse)
*   [Scrolling](#scrolling)
    *   [Scrollbar](#scrollbar)
*   [Editing Support](#editing-support)
    *   [Comment](#comment)
*   [Formatting](#formatting)
    *   [Indent](#indent)
*   [Command Line](#command-line)
*   [Session](#session)
*   [Remote Development](#remote-development)
*   [Split and Window](#split-and-window)
    *   [Tmux](#tmux)
*   [Game](#game)
    *   [Competitive Programming](#competitive-programming)
*   [Workflow](#workflow)
*   [Database](#database)
*   [Preconfigured Configuration](#preconfigured-configuration)
*   [External](#external)
    *   [Version Manager](#version-manager)
    *   [Boilerplate](#boilerplate)
    *   [OS-specific](#os-specific)
*   [Wishlist](#wishlist)
*   [UI](#ui)
*   [Starter Templates](#starter-templates)
*   [Vim](#vim)
*   [Resource](#resource)

## Plugin Manager

*   [lewis6991/pckr.nvim (⭐339)](https://github.com/lewis6991/pckr.nvim) - Spiritual successor of `wbthomason/packer.nvim`.
*   [savq/paq-nvim (⭐707)](https://github.com/savq/paq-nvim) - Neovim package manager written in Lua.
*   [NTBBloodbath/cheovim (⭐344)](https://github.com/NTBBloodbath/cheovim) - Neovim configuration switcher written in Lua. Inspired by chemacs.
*   [folke/lazy.nvim (⭐20k)](https://github.com/folke/lazy.nvim) - A modern plugin manager, featuring a graphical interface, async execution, a lockfile and more.
*   [alex-popov-tech/store.nvim (⭐306)](https://github.com/alex-popov-tech/store.nvim) - Plugins discovery tool with hourly updated database, and one-key installation for `lazy.nvim` and `vim.pack`.
*   [nvim-neorocks/rocks.nvim (⭐988)](https://github.com/nvim-neorocks/rocks.nvim) - A modern approach to plugin management using Luarocks, inspired by Cargo.
*   [nvim-mini/mini.nvim#mini.deps (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-deps.md) - Module of `mini.nvim` for managing other plugins. Uses Git and built-in packages to install, update, clean, and snapshot plugins.
*   [wsdjeg/nvim-plug (⭐23)](https://github.com/wsdjeg/nvim-plug) - Asynchronous Neovim plugin manager written in Lua.
*   [alyxshang/nuwa.nvim (⭐7)](https://github.com/alyxshang/nuwa.nvim) - A light Neovim package manager.
*   [piersolenski/plugin-addict.nvim (⭐11)](https://github.com/piersolenski/plugin-addict.nvim) - A stupidly simple way to quickly install plugins.
*   [synapse.nvim (⭐4)](https://github.com/OriginCoderPulse/synapse.nvim) - A modern, lightweight plugin manager with beautiful UI, intelligent dependency management, tag/branch support, and post-install command execution.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## LSP

**(requires Neovim 0.5)**

*   [romus204/referencer.nvim (⭐27)](https://github.com/romus204/referencer.nvim) - Lightweight, asynchronous that uses the LSP to show references to functions, methods, types and other.
*   [Dan7h3x/signup.nvim (⭐52)](https://github.com/Dan7h3x/signup.nvim) - a little smart `lsp_signature` helper with awesome features.

<!--lint disable awesome-spell-check-->

*   [neovim/nvim-lspconfig (⭐13k)](https://github.com/neovim/nvim-lspconfig) - Quickstart configurations for the LSP client.

<!--lint enable awesome-spell-check-->

*   [nvim-lua/lsp-status.nvim (⭐656)](https://github.com/nvim-lua/lsp-status.nvim) - This is a plugin/library for generating statusline components from the built-in LSP client.
*   [nvimdev/lspsaga.nvim (⭐3.7k)](https://github.com/nvimdev/lspsaga.nvim) - A light-weight LSP plugin based on Neovim's built-in LSP with a highly performant UI.
*   [kosayoda/nvim-lightbulb (⭐868)](https://github.com/kosayoda/nvim-lightbulb) - The plugin shows a lightbulb in the sign column whenever a `textDocument/codeAction` is available at the current cursor position.
*   [onsails/lspkind.nvim (⭐1.6k)](https://github.com/onsails/lspkind.nvim) - The plugin adds VSCode-like icons to Neovim LSP completions.
*   [ojroques/nvim-lspfuzzy (⭐343)](https://github.com/ojroques/nvim-lspfuzzy) - A small plugin to make the LSP client use FZF.
*   [gfanto/fzf-lsp.nvim (⭐237)](https://github.com/gfanto/fzf-lsp.nvim) - Enable the power of FZF fuzzy search for the Neovim built in LSP.
*   [ray-x/lsp\_signature.nvim (⭐2.3k)](https://github.com/ray-x/lsp_signature.nvim) - LSP signature hint when you type.
*   [smjonas/inc-rename.nvim (⭐807)](https://github.com/smjonas/inc-rename.nvim) - Provides an incremental LSP rename command based on Neovim's command-preview feature.
*   [rmagatti/goto-preview (⭐1k)](https://github.com/rmagatti/goto-preview) - Previewing native LSP's goto definition calls in floating windows.
*   [jubnzv/virtual-types.nvim (⭐415)](https://github.com/jubnzv/virtual-types.nvim) - Show type annotations as virtual text.
*   [marilari88/twoslash-queries.nvim (⭐170)](https://github.com/marilari88/twoslash-queries.nvim) - Provide inline virtual text displaying TypeScript types for the inspected variables.
*   [ray-x/navigator.lua (⭐1.4k)](https://github.com/ray-x/navigator.lua) - Learn existing code quickly and navigate code like a breeze. A swiss army knife makes exploring LSP and Tree-sitter symbols a piece of cake.
*   [hedyhli/outline.nvim (⭐918)](https://github.com/hedyhli/outline.nvim) - A significantly enhanced and refactored fork of `symbols-outline.nvim`.
*   [stevearc/aerial.nvim (⭐2.2k)](https://github.com/stevearc/aerial.nvim) - A code outline window for skimming and quick navigation.
*   [SmiteshP/nvim-navbuddy (⭐878)](https://github.com/SmiteshP/nvim-navbuddy) - A simple popup display that provides breadcrumbs like navigation features using LSP.
*   [tamago324/nlsp-settings.nvim (⭐334)](https://github.com/tamago324/nlsp-settings.nvim) - Setup LSP with JSON or YAML files.
*   [jakewvincent/texmagic.nvim (⭐56)](https://github.com/jakewvincent/texmagic.nvim) - Enhance the lspconfig settings for Texlab by defining any number of custom LaTeX build engines and selecting them with magic comments.
*   [aznhe21/actions-preview.nvim (⭐501)](https://github.com/aznhe21/actions-preview.nvim) - Fully customizable previewer for LSP code actions.
*   [mfussenegger/nvim-lint (⭐2.6k)](https://github.com/mfussenegger/nvim-lint) - An asynchronous linter plugin, complementary to the built-in Language Server Protocol support.
*   [b0o/SchemaStore.nvim (⭐948)](https://github.com/b0o/SchemaStore.nvim) - Provide access to the [SchemaStore (⭐3.6k)](https://github.com/SchemaStore/schemastore) catalog.
*   [j-hui/fidget.nvim (⭐2.4k)](https://github.com/j-hui/fidget.nvim) - Standalone UI for LSP progress.
*   [scalameta/nvim-metals (⭐543)](https://github.com/scalameta/nvim-metals) - Neovim plugin for Metals, the Scala language server, using Neovim's builtin LSP.
*   [junnplus/lsp-setup.nvim (⭐236)](https://github.com/junnplus/lsp-setup.nvim) - A simple wrapper for nvim-lspconfig and nvim-lsp-installer to easily setup LSP servers.
*   [amrbashir/nvim-docs-view (⭐170)](https://github.com/amrbashir/nvim-docs-view) - Display LSP hover documentation in a side panel.
*   [mfussenegger/nvim-jdtls (⭐1.4k)](https://github.com/mfussenegger/nvim-jdtls) - Extensions for the built-in LSP support for eclipse.jdt.ls.
*   [Kasama/nvim-custom-diagnostic-highlight (⭐62)](https://github.com/Kasama/nvim-custom-diagnostic-highlight) - Inline diagnostics popup-highlight much like coc-nvim but based on `vim.diagnostic`.
*   [mrcjkb/haskell-tools.nvim (⭐561)](https://github.com/mrcjkb/haskell-tools.nvim) - Seamless integration of Neovim with Haskell development tools like haskell-language-server and Hoogle.
*   [p00f/clangd\_extensions.nvim (⭐565)](https://github.com/p00f/clangd_extensions.nvim) - Off-spec clangd features for Neovim's LSP client.
*   [ranjithshegde/ccls.nvim (⭐77)](https://github.com/ranjithshegde/ccls.nvim) - Use off-spec extensions of ccls LSP and browse AST.
*   [idanarye/nvim-buffls (⭐11)](https://github.com/idanarye/nvim-buffls) - Add LSP functionality to specific Neovim buffers.
*   [DNLHC/glance.nvim (⭐856)](https://github.com/DNLHC/glance.nvim) - A pretty window for previewing, navigating and editing your LSP locations.
*   [linrongbin16/lsp-progress.nvim (⭐232)](https://github.com/linrongbin16/lsp-progress.nvim) - A performant LSP progress status.
*   [jinzhongjia/LspUI.nvim (⭐265)](https://github.com/jinzhongjia/LspUI.nvim) - A modern and useful UI that wraps LSP operations.
*   [VidocqH/lsp-lens.nvim (⭐305)](https://github.com/VidocqH/lsp-lens.nvim) - Display function references above function definition like IDEA codelens.
*   [chrisgrieser/nvim-dr-lsp (⭐34)](https://github.com/chrisgrieser/nvim-dr-lsp) - Status line component showing the number of LSP definition and reference of the token under the cursor.
*   [Wansmer/symbol-usage.nvim (⭐453)](https://github.com/Wansmer/symbol-usage.nvim) - Display references, definitions and implementations of document symbols.
*   [creativenull/efmls-configs-nvim (⭐306)](https://github.com/creativenull/efmls-configs-nvim) - An unofficial collection of linters and formatters configured for efm-langserver to work with builtin LSP.
*   [creativenull/diagnosticls-configs-nvim (⭐92)](https://github.com/creativenull/diagnosticls-configs-nvim) - An unofficial collection of linters and formatters configured for diagnostic-languageserver to work with builtin LSP.
*   [hinell/lsp-timeout.nvim (⭐231)](https://github.com/hinell/lsp-timeout.nvim) - Automatically start/stop idle/unused LSP servers; keeps RAM usage low.
*   [nvimtools/none-ls.nvim (⭐3.2k)](https://github.com/nvimtools/none-ls.nvim) - Null-ls.nvim reloaded / Use Neovim as a language server to inject LSP diagnostics, code actions, and more via Lua.
*   [zeioth/none-ls-autoload.nvim (⭐26)](https://github.com/zeioth/none-ls-autoload.nvim) - Auto-load/Auto-unload none-ls sources installed with mason. It supports builtin sources and external sources.
*   [vxpm/ferris.nvim (⭐115)](https://github.com/vxpm/ferris.nvim) - Interact with Rust-Analyzer's LSP extensions.
*   [mrcjkb/rustaceanvim (⭐2.7k)](https://github.com/mrcjkb/rustaceanvim) - A heavily modified fork of rust-tools.nvim that does not require a `setup` call and does not depend on nvim-lspconfig.
*   [soulis-1256/eagle.nvim (⭐332)](https://github.com/soulis-1256/eagle.nvim) - Mouse-hover LSP hints.
*   [stevanmilic/nvim-lspimport (⭐79)](https://github.com/stevanmilic/nvim-lspimport) - Automatically resolves imports for undefined terms. Useful with `pyright` language server.
*   [jmbuhr/otter.nvim (⭐783)](https://github.com/jmbuhr/otter.nvim) - Provides LSP features and a nvim-cmp completion source for languages embedded in other documents.
*   [lopi-py/luau-lsp.nvim (⭐84)](https://github.com/lopi-py/luau-lsp.nvim) - A luau-lsp extension to improve your experience.
*   [LukasPietzschmann/boo.nvim (⭐36)](https://github.com/LukasPietzschmann/boo.nvim) - Quickly pop-up some LSP-powered information of the thing your cursor is on.
*   [zeioth/garbage-day.nvim (⭐490)](https://github.com/Zeioth/garbage-day.nvim) - Garbage collector that stops inactive LSP clients to free RAM.
*   [rachartier/tiny-inline-diagnostic.nvim (⭐1.5k)](https://github.com/rachartier/tiny-inline-diagnostic.nvim) - Display prettier diagnostic messages. Display one line diagnostic messages where the cursor is, with icons and colors.
*   [chrisgrieser/nvim-lsp-endhints (⭐217)](https://github.com/chrisgrieser/nvim-lsp-endhints) - Display LSP inlay hints at the end of the line, rather than within the line.
*   [rachartier/tiny-code-action.nvim (⭐429)](https://github.com/rachartier/tiny-code-action.nvim) - Provides a simple way to run and visualize code actions with Telescope.
*   [mawkler/refjump.nvim (⭐55)](https://github.com/mawkler/refjump.nvim) - Jump to next/previous LSP reference for item under cursor with `]r`/`[r`.
*   [alexpasmantier/pymple.nvim (⭐137)](https://github.com/alexpasmantier/pymple.nvim) - Refactor Python imports on file move/rename.
*   [esmuellert/nvim-eslint (⭐68)](https://github.com/esmuellert/nvim-eslint) - Bundle VSCode ESLint language server and utilize the native LSP client to provide a all-in-one ESLint experience.
*   [Fildo7525/pretty\_hover (⭐235)](https://github.com/Fildo7525/pretty_hover) - Highly customizable hover formatter, extendable to blink.cmp. As native hover supports multiple LSP servers.
*   [yarospace/dev-tools.nvim (⭐75)](https://github.com/yarospace/dev-tools.nvim) - In-process LSP server for custom code actions, enhanced actions picker, community actions library and a convenient interface to create your own actions.
*   [SunnyTamang/neodoc.nvim (⭐12)](https://github.com/SunnyTamang/neodoc.nvim) - DocString generator that helps writing function/classes docstrings in formats like `google`, `numpy`, `sphinx` with live preview.
*   [barreiroleo/ltex\_extra.nvim (⭐182)](https://github.com/barreiroleo/ltex_extra.nvim) - LTeX LSP extension providing external file handling (rules and dictionaries).

### LSP Installer

*   [williamboman/mason.nvim (⭐9.8k)](https://github.com/williamboman/mason.nvim) - Portable package manager that runs everywhere Neovim runs. Easily install and manage LSP servers, DAP servers, linters, and formatters.

### Diagnostics

*   [sontungexpt/better-diagnostic-virtual-text (⭐95)](https://github.com/sontungexpt/better-diagnostic-virtual-text) - Enhances the display of virtual text for diagnostics. This function aims to provide a more user-friendly and informative presentation of diagnostic messages directly within the editor.
*   [\~whynothugo/lsp\_lines.nvim](https://git.sr.ht/~whynothugo/lsp_lines.nvim) - Render diagnostics using virtual lines on top of the real line of code.
*   [folke/trouble.nvim (⭐6.6k)](https://github.com/folke/trouble.nvim) - A pretty diagnostics list to help you solve all the trouble your code is causing.
*   [piersolenski/wtf.nvim (⭐566)](https://github.com/piersolenski/wtf.nvim) - AI powered diagnostic debugging, helps explain complex errors and offers custom tailored solutions.
*   [chrisgrieser/nvim-rulebook (⭐107)](https://github.com/chrisgrieser/nvim-rulebook) - Add inline-comments to ignore rules, or lookup rule documentation online.
*   [artemave/workspace-diagnostics.nvim (⭐234)](https://github.com/artemave/workspace-diagnostics.nvim) - Populate diagnostics for all projects files, not just the opened ones.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Completion

*   [ms-jpq/coq\_nvim (⭐3.8k)](https://github.com/ms-jpq/coq_nvim) - Fast as FUCK Neovim completion. SQLite, concurrent scheduler, hundreds of hours of optimization.
*   [hrsh7th/nvim-cmp (⭐9.2k)](https://github.com/hrsh7th/nvim-cmp) - Completion engine written in Lua, successor of `nvim-compe`.
    *   [hrsh7th/cmp-cmdline (⭐609)](https://github.com/hrsh7th/cmp-cmdline) - `nvim-cmp` source for cmdline completion.
    *   [saadparwaiz1/cmp\_luasnip (⭐783)](https://github.com/saadparwaiz1/cmp_luasnip) - `nvim-cmp` source for `LuaSnip`.
    *   [hrsh7th/cmp-buffer (⭐666)](https://github.com/hrsh7th/cmp-buffer) - `nvim-cmp` source for buffer words.
    *   [hrsh7th/cmp-path (⭐684)](https://github.com/hrsh7th/cmp-path) - `nvim-cmp` source for filesystem paths.
    *   [hrsh7th/cmp-nvim-lsp (⭐1.5k)](https://github.com/hrsh7th/cmp-nvim-lsp) - `nvim-cmp` source for the Neovim builtin LSP client.
    *   [hrsh7th/cmp-nvim-lsp-signature-help (⭐677)](https://github.com/hrsh7th/cmp-nvim-lsp-signature-help) - `nvim-cmp` source for displaying function signatures from an LSP client.
    *   [hrsh7th/cmp-nvim-lua (⭐325)](https://github.com/hrsh7th/cmp-nvim-lua) - `nvim-cmp` source for the Neovim Lua API.
    *   [petertriho/cmp-git (⭐416)](https://github.com/petertriho/cmp-git) - `nvim-cmp` source for `git`.
    *   [lukas-reineke/cmp-under-comparator (⭐189)](https://github.com/lukas-reineke/cmp-under-comparator) - `nvim-cmp` function for better sorting.
    *   [SergioRibera/cmp-dotenv (⭐91)](https://github.com/SergioRibera/cmp-dotenv) - `nvim-cmp` source for environment variables (from system and `.env` files).
*   [nvim-mini/mini.nvim#mini.completion (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-completion.md) - Module of `mini.nvim` for asynchronous two-stage completion. Supports showing completion item info and independent function signature.
*   [saghen/blink.cmp (⭐5.7k)](https://github.com/saghen/blink.cmp) - Really fast completion with LSP & snippet support, along with signature help, cmdline completion, and autobracket support (based on semantic tokens).
    *   [saghen/blink.compat (⭐207)](https://github.com/saghen/blink.compat) - Compatibility layer for using `nvim-cmp` sources on `blink.cmp`.
    *   [Kasier-Yang/blink-cmp-avante (⭐99)](https://github.com/Kaiser-Yang/blink-cmp-avante) - `blink-cmp` source for Avante.
    *   [krissen/blink-cmp-bibtex (⭐9)](https://github.com/krissen/blink-cmp-bibtex) - `blink.cmp` source for BibTeX citation files.
    *   [Kaiser-Yang/blink-cmp-git (⭐80)](https://github.com/Kaiser-Yang/blink-cmp-git) - `blink.cmp` source for Git.
    *   [disrupted/blink-cmp-conventional-commits (⭐23)](https://github.com/disrupted/blink-cmp-conventional-commits) - `blink.cmp` source for [Conventional Commits](https://www.conventionalcommits.org/).
    *   [mikavilpas/blink-ripgrep.nvim (⭐101)](https://github.com/mikavilpas/blink-ripgrep.nvim) - `blink.cmp` source for `ripgrep` / `git grep`.
    *   [bydlw98/blink-cmp-env (⭐17)](https://github.com/bydlw98/blink-cmp-env) - `blink.cmp` source for environment variables.
    *   [bydlw98/blink-cmp-sshconfig (⭐5)](https://github.com/bydlw98/blink-cmp-sshconfig) - `blink.cmp` source for `sshconfig` files.
    *   [mgalliou/blink-cmp-tmux (⭐9)](https://github.com/mgalliou/blink-cmp-tmux) - `blink.cmp` source for [tmux (⭐40k)](https://github.com/tmux/tmux).
    *   [moyiz/blink-emoji.nvim (⭐68)](https://github.com/moyiz/blink-emoji.nvim) - `blink.cmp` source for GitHub Markdown emojis.
    *   [erooke/blink-cmp-latex (⭐11)](https://github.com/erooke/blink-cmp-latex) - `blink.cmp` source for LaTeX.
*   [zbirenbaum/copilot.lua (⭐3.9k)](https://github.com/zbirenbaum/copilot.lua) - Fully featured Lua replacement for [GitHub/copilot.vim (⭐11k)](https://github.com/github/copilot.vim).
*   [brianaung/compl.nvim (⭐45)](https://github.com/brianaung/compl.nvim) - A minimal and dependency-free auto-completion built on top of Vim's ins-completion mechanism.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## AI

*   [carlos-algms/agentic.nvim (⭐63)](https://github.com/carlos-algms/agentic.nvim) - Chat interface for AI ACP providers such as Claude, Gemini, Codex, OpenCode and Cursor.
*   [blob42/codegpt-ng.nvim (⭐8)](https://github.com/blob42/codegpt-ng.nvim) - Minimalist command based AI coding with a powerful template system. Supports Ollama, OpenAI and more.
*   [Aaronik/GPTModels.nvim (⭐74)](https://github.com/Aaronik/GPTModels.nvim) - GPTModels - a stable, clean, multi model, window based LLM AI tool.
*   [Robitx/gp.nvim (⭐1.3k)](https://github.com/Robitx/gp.nvim) - ChatGPT like sessions and instructable text/code operations in your favorite editor.
*   [jackMort/ChatGPT.nvim (⭐4k)](https://github.com/jackMort/ChatGPT.nvim) - Effortless Natural Language Generation with OpenAI's ChatGPT API.
*   [CamdenClark/flyboy (⭐46)](https://github.com/CamdenClark/flyboy) - Simple interaction with ChatGPT in a Markdown buffer. Supports GPT-4 and Azure OpenAI.
*   [gsuuon/model.nvim (⭐393)](https://github.com/gsuuon/model.nvim) - Integrate LLMs via a prompt builder interface. Multi-providers including OpenAI (+ compatibles), `PaLM`, `Hugging Face`, and local engines like `llamacpp`.
*   [dense-analysis/neural (⭐509)](https://github.com/dense-analysis/neural) - Integrate LLMs for generating code, interacting with chat bots, and more.
*   [jpmcb/nvim-llama (⭐274)](https://github.com/jpmcb/nvim-llama) - LLM (LLaMA 2 and `llama.cpp`) wrappers.
*   [David-Kunz/gen.nvim (⭐1.5k)](https://github.com/David-Kunz/gen.nvim) - Generate text using LLMs (via Ollama) with customizable prompts.
*   [kiddos/gemini.nvim (⭐196)](https://github.com/kiddos/gemini.nvim) - Bindings to Google Gemini API.
*   [olimorris/codecompanion.nvim (⭐5.8k)](https://github.com/olimorris/codecompanion.nvim) - Copilot Chat like experience, complete with inline assistant. Supports Anthropic, Gemini, Ollama and OpenAI.
*   [you-n-g/simplegpt.nvim (⭐31)](https://github.com/you-n-g/simplegpt.nvim) - Provide a simple yet flexible way to construct and send questions to ChatGPT.
*   [Exafunction/windsurf.nvim (⭐1.2k)](https://github.com/Exafunction/windsurf.nvim) - Free, ultrafast Copilot alternative. Supports LSP and Tree-sitter.
*   [GeorgesAlkhouri/nvim-aider (⭐365)](https://github.com/GeorgesAlkhouri/nvim-aider) - Seamlessly integrate Aider for an AI-assisted coding experience.
*   [CopilotC-Nvim/CopilotChat.nvim (⭐3.5k)](https://github.com/CopilotC-Nvim/CopilotChat.nvim) - A chat interface for GitHub Copilot that allows you to directly ask and receive answers to coding-related questions.
*   [tzachar/cmp-ai (⭐266)](https://github.com/tzachar/cmp-ai) - This is a general purpose AI source for nvim-cmp, easily adapted to any REST API supporting remote code completion.
*   [milanglacier/minuet-ai.nvim (⭐901)](https://github.com/milanglacier/minuet-ai.nvim) - Minuet offers code completion from LLM providers including OpenAI (compatible), Gemini, Claude, Ollama, Deepseek and more providers, with support for nvim-cmp, blink.cmp and virtual-text frontend.
*   [yetone/avante.nvim (⭐17k)](https://github.com/yetone/avante.nvim) - Chat with your code as if you are in Cursor AI IDE.
*   [Kurama622/llm.nvim (⭐426)](https://github.com/Kurama622/llm.nvim) - Free large language model (LLM) support, provides commands to interact with LLM.
*   [3v0k4/exit.nvim (⭐18)](https://github.com/3v0k4/exit.nvim) - Prompt LLMs (large language models) to write Vim commands.
*   [k2589/LLuMinate.nvim (⭐17)](https://github.com/k2589/lluminate.nvim) - Enrich context for LLM with LSP hover added to clipboard.
*   [milanglacier/yarepl.nvim#aider-extensions (⭐241)](https://github.com/milanglacier/yarepl.nvim/blob/main/extensions/README.md) - Integration with [aider-chat](https://aider.chat), a TUI AI coding assistant.
*   [Davidyz/VectorCode (⭐752)](https://github.com/davidyz/vectorcode) - Supercharge your LLM experience with repository-level RAG.
*   [dlants/magenta.nvim (⭐418)](https://github.com/dlants/magenta.nvim) - Leverage coding assistants for chat and code generation. Provides tools for the AI/LLM agent to explore and edit your code, like Aider, Cursor and Windsurf.
*   [Flemma-Dev/flemma.nvim (⭐37)](https://github.com/Flemma-Dev/flemma.nvim) - Flemma turns Neovim into a first-class AI workspace.
*   [heilgar/nochat.nvim (⭐11)](https://github.com/heilgar/nochat.nvim) - Cursor-like effortless natural language generation with multiple AI providers including Ollama, Anthropic (Claude), and ChatGPT.
*   [julwrites/llm-nvim (⭐8)](https://github.com/julwrites/llm-nvim) - Comprehensive integration with the [LLM (⭐11k)](https://github.com/simonw/llm) tool.
*   [azorng/goose.nvim (⭐296)](https://github.com/azorng/goose.nvim) - Seamless Neovim integration with [goose](https://block.github.io/goose) - work with a powerful AI agent without leaving your editor.
*   [mozanunal/sllm.nvim (⭐93)](https://github.com/mozanunal/sllm.nvim) - In-editor chat powered by Simon Willison's LLM CLI: stream replies in a Markdown buffer, manage rich context (files, URLs, selections, diagnostics, shell outputs), switch models interactively, and even see token-usage stats.
*   [chatvim/chatvim.nvim (⭐12)](https://github.com/chatvim/chatvim.nvim) - Chat with Markdown files using AI models from xAI, OpenAI and Anthropic.
*   [3ZsForInsomnia/code-companion-picker (⭐7)](https://github.com/3ZsForInsomnia/code-companion-picker) - Telescope and Snacks picker integrations for previewing CodeCompanion prompts.
*   [3ZsForInsomnia/vs-code-companion (⭐5)](https://github.com/3ZsForInsomnia/vs-code-companion) - Tool for importing VSCode's Markdown prompts into CodeCompanion.
*   [3ZsForInsomnia/token-count.nvim (⭐6)](https://github.com/3ZsForInsomnia/token-count.nvim) - Shows the token count for the current buffer, with integrations for Lualine and NeoTree.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Programming Languages Support

*   [Julian/lean.nvim (⭐450)](https://github.com/Julian/lean.nvim) - Neovim support for the [Lean Theorem Prover](https://leanprover.github.io/).
*   [nvim-flutter/flutter-tools.nvim (⭐1.3k)](https://github.com/nvim-flutter/flutter-tools.nvim) - Build Flutter and Dart applications using the native LSP.
*   [brendalf/mix.nvim (⭐28)](https://github.com/brendalf/mix.nvim) - Mix (from Elixir) wrapper plugin.
*   [AckslD/swenv.nvim (⭐248)](https://github.com/AckslD/swenv.nvim) - Tiny plugin to quickly switch Python virtual environments without restarting.
*   [gennaro-tedesco/nvim-jqx (⭐331)](https://github.com/gennaro-tedesco/nvim-jqx) - Interactive interface for JSON files.
*   [nanotee/sqls.nvim (⭐241)](https://github.com/nanotee/sqls.nvim) - SQL database connection plugin + LSP client.
*   [dmmulroy/tsc.nvim (⭐512)](https://github.com/dmmulroy/tsc.nvim) - Asynchronous project-wide TypeScript type-checking using the TypeScript compiler (`tsc`) with results loaded into a quickfix list.
*   [dmmulroy/ts-error-translator.nvim (⭐399)](https://github.com/dmmulroy/ts-error-translator.nvim) - A port of Matt Pocock's `ts-error-translator` for VSCode for turning messy and confusing TypeScript errors into plain English.
*   [chuwy/ucm.nvim (⭐6)](https://github.com/chuwy/ucm.nvim) - Navigating [Unison](https://unison-lang.org/) projects.
*   [niuiic/typst-preview.nvim (⭐47)](https://github.com/niuiic/typst-preview.nvim) - Preview Typst documents, respond to file changes.
*   [chomosuke/typst-preview.nvim (⭐748)](https://github.com/chomosuke/typst-preview.nvim) - Preview Typst documents in the browser, instant update on each keystroke, and cross jump between code and preview.
*   [quarto-dev/quarto-nvim (⭐483)](https://github.com/quarto-dev/quarto-nvim) - Tools for working with [Quarto](https://quarto.org/) documents.
*   [iabdelkareem/csharp.nvim (⭐273)](https://github.com/iabdelkareem/csharp.nvim) - Enhances the development experience for .NET developers.
*   [neolooong/whichpy.nvim (⭐32)](https://github.com/neolooong/whichpy.nvim) - Switch Python interpreter without restarting LSP.
*   [nvim-java/nvim-java (⭐1.5k)](https://github.com/nvim-java/nvim-java) - Everything you need for a painless Java experience.
*   [kiyoon/python-import.nvim (⭐56)](https://github.com/kiyoon/python-import.nvim) - Add Python import statements with Tree-sitter, LSP, and more.
*   [kiyoon/haskell-scope-highlighting.nvim (⭐29)](https://github.com/kiyoon/haskell-scope-highlighting.nvim) - Haskell syntax highlighting which considers variable scopes. Inspired from "Context Coloring" by prof. Douglas Crockford.
*   [apyra/nvim-unity.nvim (⭐82)](https://github.com/apyra/nvim-unity) - Use Neovim as your default Unity editor with full LSP support via OmniSharp.
*   [atomicptr/defold.nvim (⭐16)](https://github.com/atomicptr/defold.nvim) - Batteries-included development environment for the Defold game engine.
*   [onlyati/quadlet-lsp.nvim (⭐9)](https://github.com/onlyati/quadlet-lsp.nvim) - Provides completion, hover and other language server features for Podman Quadlet files.
*   [leblocks/hopcsharp.nvim (⭐10)](https://github.com/leblocks/hopcsharp.nvim) - Provides LSP-less navigation and type-hierarchy information in C# repositories.

### Golang

*   [romus204/go-tagger.nvim (⭐15)](https://github.com/romus204/go-tagger.nvim) - A lightweight plugin to manage struct field tags in Go files.
*   [ray-x/go.nvim (⭐2.6k)](https://github.com/ray-x/go.nvim) - Golang plugin based on LSP and Tree-sitter.
*   [crusj/structrue-go.nvim (⭐49)](https://github.com/crusj/structrue-go.nvim) - A better structured display of Golang symbols information.
*   [crispgm/nvim-go (⭐152)](https://github.com/crispgm/nvim-go) - A minimal implementation of Golang development plugin.
*   [olexsmir/gopher.nvim (⭐405)](https://github.com/olexsmir/gopher.nvim/) - Plugin for making Golang development easiest.
*   [rafaelsq/nvim-goc.lua (⭐55)](https://github.com/rafaelsq/nvim-goc.lua) - Highlight your buffer with Golang Code Coverage.
*   [crusj/hierarchy-tree-go.nvim (⭐35)](https://github.com/crusj/hierarchy-tree-go.nvim) - Neovim plugin for Golang, callHierarchy UI tree.
*   [yanskun/gotests.nvim (⭐26)](https://github.com/yanskun/gotests.nvim) - Make Go tests easy with [gotests (⭐5.3k)](https://github.com/cweill/gotests).
*   [maxandron/goplements.nvim (⭐86)](https://github.com/maxandron/goplements.nvim) - Visualize Go struct and interface implementations.
*   [Snikimonkd/cmp-go-pkgs (⭐31)](https://github.com/Snikimonkd/cmp-go-pkgs) - Cmp source for Go packages names.
*   [Yu-Leo/gosigns.nvim (⭐4)](https://github.com/Yu-Leo/gosigns.nvim) - Visualize some Go hints: struct, interface, and methods implementations; go comments.
*   [Yu-Leo/cmp-go-pkgs (⭐4)](https://github.com/Yu-Leo/cmp-go-pkgs) - Cmp source providing the names of Go packages to import.
*   [fredrikaverpil/godoc.nvim (⭐168)](https://github.com/fredrikaverpil/godoc.nvim) - Fuzzy search Go packages/symbols and view docs.

### YAML

*   [someone-stole-my-name/yaml-companion.nvim (⭐264)](https://github.com/someone-stole-my-name/yaml-companion.nvim) - Get, set and autodetect YAML schemas in your buffers.
*   [cuducos/yaml.nvim (⭐235)](https://github.com/cuducos/yaml.nvim) - Utils to work with YAML files.

### Web Development

*   [rest-nvim/rest.nvim (⭐2k)](https://github.com/rest-nvim/rest.nvim) - A fast Neovim HTTP client written in Lua.
*   [lima1909/resty.nvim (⭐51)](https://github.com/lima1909/resty.nvim) - Fast and easy-to-use HTTP-Rest-Client.
*   [mistweaverco/kulala.nvim (⭐1.8k)](https://github.com/mistweaverco/kulala.nvim) - A minimal HTTP-client interface.
*   [heilgar/nvim-http-client (⭐19)](https://github.com/heilgar/nvim-http-client) - Easy to use HTTP client with IntelliJ (JetBrains) HTTP client syntax compatibility.
*   [luckasRanarison/tailwind-tools.nvim (⭐584)](https://github.com/luckasRanarison/tailwind-tools.nvim) - Unofficial Tailwind CSS tooling.
*   [farias-hecdin/CSSVarViewer (⭐10)](https://github.com/farias-hecdin/CSSVarViewer) - Easily visualize the content of your CSS variables in a virtual text.
*   [farias-hecdin/CSSVarHighlight (⭐6)](https://github.com/farias-hecdin/CSSVarHighlight) - Quickly highlight the color you defined in your CSS variables with the help of `mini.hipatterns`.
*   [mawkler/jsx-element.nvim (⭐23)](https://github.com/mawkler/jsx-element.nvim) - JSX/TSX text-objects and motions.
*   [BibekBhusal0/nvim-shadcn (⭐10)](https://github.com/BibekBhusal0/nvim-shadcn) - Easily add Shadcn UI components with telescope.
*   [azratul/expose-localhost.nvim (⭐4)](https://github.com/azratul/expose-localhost.nvim) - Expose your local server to the internet with cloudflared or ngrok.
*   [yelog/i18n.nvim (⭐44)](https://github.com/yelog/i18n.nvim) - Internationalization (i18n) management with LSP support for `Vue`, `React`, `Java` and more.
*   [Kenzo-Wada/boundary.nvim (⭐24)](https://github.com/Kenzo-Wada/boundary.nvim) - Display `'use client'` markers inline in your JSX code to visualize client component boundaries.
*   [abidibo/nvim-httpyac (⭐13)](https://github.com/abidibo/nvim-httpyac) - Provides integration with `httpYac`.
*   [rodrigoscc/nurl.nvim (⭐9)](https://github.com/rodrigoscc/nurl.nvim) - HTTP client with requests defined in pure Lua.

### Markdown and LaTeX

*   [iamcco/markdown-preview.nvim (⭐7.6k)](https://github.com/iamcco/markdown-preview.nvim) - Preview Markdown on your modern browser with synchronised scrolling and flexible configuration.
*   [davidgranstrom/nvim-markdown-preview (⭐111)](https://github.com/davidgranstrom/nvim-markdown-preview) - Markdown preview in the browser using pandoc and live-server through Neovim's job-control API.
*   [jghauser/auto-pandoc.nvim (⭐40)](https://github.com/jghauser/auto-pandoc.nvim) - Easy pandoc conversion leveraging YAML blocks.
*   [jghauser/follow-md-links.nvim (⭐165)](https://github.com/jghauser/follow-md-links.nvim) - Press enter to follow internal Markdown links.
*   [jubnzv/mdeval.nvim (⭐217)](https://github.com/jubnzv/mdeval.nvim) - Evaluate code blocks inside Markdown documents.
*   [kdheepak/panvimdoc (⭐308)](https://github.com/kdheepak/panvimdoc) - A pandoc to vimdoc GitHub action.
*   [frabjous/knap (⭐376)](https://github.com/frabjous/knap) - Plugin for creating automatic updating-as-you-type previews for Markdown, LaTeX and other documents.
*   [jbyuki/carrot.nvim (⭐27)](https://github.com/jbyuki/carrot.nvim) - Markdown evaluator Lua code blocks.
*   [Nedra1998/nvim-mdlink (⭐32)](https://github.com/Nedra1998/nvim-mdlink) - Simplify creating and following Markdown links.
*   [nfrid/markdown-togglecheck (⭐23)](https://github.com/nfrid/markdown-togglecheck) - Simple Neovim plugin for toggling check boxes using Tree-sitter.
*   [toppair/peek.nvim (⭐819)](https://github.com/toppair/peek.nvim) - Preview Markdown in a webview window.
*   [yaocccc/nvim-hl-mdcodeblock.lua (⭐35)](https://github.com/yaocccc/nvim-hl-mdcodeblock.lua) - Highlight Markdown codeblock using Tree-sitter.
*   [kiran94/edit-markdown-table.nvim (⭐28)](https://github.com/kiran94/edit-markdown-table.nvim) - Edit Markdown Tables using Tree-sitter.
*   [richardbizik/nvim-toc (⭐44)](https://github.com/richardbizik/nvim-toc) - Easily generate table of contents for Markdown files.
*   [Zeioth/markmap.nvim (⭐211)](https://github.com/Zeioth/markmap.nvim) - Visualize your Markdown as mindmaps.
*   [tadmccorkle/markdown.nvim (⭐214)](https://github.com/tadmccorkle/markdown.nvim) - Configurable tools for Markdown files, including inline-style, link, and navigation keymaps, table of contents, improved list editing, and more.
*   [mpas/marp-nvim (⭐47)](https://github.com/mpas/marp-nvim) - Present using Markdown with [Marp](https://marp.app/).
*   [MeanderingProgrammer/render-markdown.nvim (⭐3.8k)](https://github.com/MeanderingProgrammer/render-markdown.nvim) - Improve viewing Markdown files directly.
*   [ChuufMaster/markdown-toc (⭐17)](https://github.com/ChuufMaster/markdown-toc) - Generate TOC in any Markdown file from any other Markdown file with customisable levels of headings and affordances for emojis and ensuring that it works on GitHub using relative paths.
*   [OXY2DEV/markview.nvim (⭐3.1k)](https://github.com/OXY2DEV/markview.nvim) - A hackable Markdown, Typst, LaTeX, HTML (inline) and YAML renderer.
*   [Kicamon/markdown-table-mode.nvim (⭐98)](https://github.com/Kicamon/markdown-table-mode.nvim) - Markdown format plugin like vim-table-mode but write in Lua.
*   [SCJangra/table-nvim (⭐68)](https://github.com/SCJangra/table-nvim) - A Markdown table editor that formats the table as you type.
*   [brianhuster/live-preview.nvim (⭐281)](https://github.com/brianhuster/live-preview.nvim) - Live preview HTML, Markdown and Asciidoc in the browser.
*   [timantipov/md-table-tidy.nvim (⭐13)](https://github.com/timantipov/md-table-tidy.nvim) - Simple Markdown tables formatting.
*   [nvim-telescope/telescope-bibtex.nvim (⭐132)](https://github.com/nvim-telescope/telescope-bibtex.nvim) - Telescope extension to search and paste BibTeX entries into your TeX files.
*   [Thiago4532/mdmath.nvim (⭐193)](https://github.com/Thiago4532/mdmath.nvim) - A Markdown equation previewer, using Kitty Graphics Protocol.
*   [OXY2DEV/markdoc.nvim (⭐48)](https://github.com/OXY2DEV/markdoc.nvim) - Tree-sitter based `markdown -> vimdoc` converter.
*   [YousefHadder/markdown-plus.nvim (⭐162)](https://github.com/YousefHadder/markdown-plus.nvim) - Provides a full editing experience for Markdown files which includes support for lists, links, TOC, and more with simple and fast keymaps.
*   [Myzel394/easytables.nvim (⭐133)](https://github.com/Myzel394/easytables.nvim) - Easily insert and edit Markdown tables with a live preview and useful helpers.
*   [tttol/md-outline.nvim (⭐4)](https://github.com/tttol/md-outline.nvim) - Automatically displays an outline for Markdown files.

### PHP

*   [gbprod/phpactor.nvim (⭐91)](https://github.com/gbprod/phpactor.nvim) - Lua version of [phpactor (⭐1.8k)](https://github.com/phpactor/phpactor).
*   [ta-tikoma/php.easy.nvim (⭐22)](https://github.com/ta-tikoma/php.easy.nvim) - Methods of assistance in PHP development: create classes, constants, methods, properties; simple copying and deleting of an entity.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

### Powershell

*   [TheLeoP/powershell.nvim (⭐72)](https://github.com/TheLeoP/powershell.nvim) - First class powershell editor integration. Includes LSP, debugging (requires nvim-dap) and $psEditor API support.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

### Assembly

*   [Who5673/who5673-nasm (⭐5)](https://github.com/Who5673/who5673-nasm) - Helps people program Netwide Assembler language faster and more convenient using snippets.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Language

*   [potamides/pantran.nvim (⭐324)](https://github.com/potamides/pantran.nvim) - Translate your text with an interactive translation window.
*   [niuiic/translate.nvim (⭐42)](https://github.com/niuiic/translate.nvim) - Invoke any translation engine via shell command.
*   [tanloong/interlaced.nvim (⭐11)](https://github.com/tanloong/interlaced.nvim) - Help align bilingual parallel texts.
*   [sontungexpt/vietnamese.nvim (⭐11)](https://github.com/sontungexpt/vietnamese.nvim) - A Vietnamese input method engine with native support to type Vietnamese in insert mode.
*   [doodleEsc/translator.nvim (⭐5)](https://github.com/doodleEsc/translator.nvim) - A powerful AI-powered translation plugin, leveraging OpenAI's GPT models to provide high-quality translations with natural language understanding.
*   [kiyoon/Korean-IME.nvim (⭐29)](https://github.com/kiyoon/Korean-IME.nvim) - OS-independent Korean input method that converts English inputs to Korean in-place.
*   [bennorichters/taal.nvim (⭐17)](https://github.com/bennorichters/taal.nvim) - Improve grammar and spelling errors in multiple languages using LLMs.
*   [walkersumida/deepl.nvim (⭐5)](https://github.com/walkersumida/deepl.nvim) - Translates text using the DeepL API with multiple output modes (float, replace, append).
*   [acidsugarx/babel.nvim (⭐8)](https://github.com/acidsugarx/babel.nvim) - Translate text using Google Translate with async support, float display, and multi-picker integration.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Syntax

*   [nvim-treesitter/nvim-treesitter (⭐13k)](https://github.com/nvim-treesitter/nvim-treesitter) - Neovim Tree-sitter configurations and abstraction layer.
*   [nvim-treesitter/nvim-treesitter-textobjects (⭐2.6k)](https://github.com/nvim-treesitter/nvim-treesitter-textobjects) - Create your own textobjects using Tree-sitter queries.
*   [RRethy/nvim-treesitter-textsubjects (⭐563)](https://github.com/RRethy/nvim-treesitter-textsubjects) - Location and syntax aware text objects which *do what you mean*.
*   [kylechui/nvim-surround (⭐4k)](https://github.com/kylechui/nvim-surround) - A plugin for adding/changing/deleting surrounding delimiter pairs.
*   [nvim-mini/mini.nvim#mini.surround (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-surround.md) - Module of `mini.nvim` for working with text surroundings (add, delete, replace, find, highlight). Supports dot-repeat, different search methods, "last"/"next" extended mappings, Tree-sitter integration, and more.
*   [Hdoc1509/gh-actions.nvim (⭐8)](https://github.com/Hdoc1509/gh-actions.nvim) - Tree-sitter grammar and LSP query configuration for GitHub Actions.
*   [m-demare/hlargs.nvim (⭐552)](https://github.com/m-demare/hlargs.nvim) - Highlight arguments' definitions and usages, using Tree-sitter.
*   [calops/hmts.nvim (⭐86)](https://github.com/calops/hmts.nvim) - Tree-sitter queries for Home Manager Nix files.
*   [LhKipp/nvim-nu (⭐158)](https://github.com/LhKipp/nvim-nu) - Basic editor support for the nushell language.
*   [desdic/agrolens.nvim (⭐67)](https://github.com/desdic/agrolens.nvim) - Navigate via Tree-sitter nodes using Telescope or FZF.
*   [IndianBoy42/tree-sitter-just (⭐174)](https://github.com/IndianBoy42/tree-sitter-just) - Tree-sitter grammar for [Justfiles (⭐29k)](https://github.com/casey/just).
*   [fei6409/log-highlight.nvim (⭐138)](https://github.com/fei6409/log-highlight.nvim) - Generic log syntax highlighting and log filetype management support.
*   [MeanderingProgrammer/treesitter-modules.nvim (⭐92)](https://github.com/MeanderingProgrammer/treesitter-modules.nvim) - Original modules from nvim-treesitter master branch.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Snippet

*   [L3MON4D3/LuaSnip (⭐4.2k)](https://github.com/L3MON4D3/LuaSnip) - A snippet engine written in Lua.
*   [nvim-mini/mini.nvim#mini.snippets (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-snippets.md) - Module of `mini.nvim` to manage and expand snippets. Supports LSP snippet syntax, flexible loaders, fuzzy prefix matching, interactive selection, snippet session with rich visualization, and more.
*   [smjonas/snippet-converter.nvim (⭐182)](https://github.com/smjonas/snippet-converter.nvim) - Convert snippets between the most common snippet formats and modify them using a few lines of Lua code.
*   [dcampos/nvim-snippy (⭐339)](https://github.com/dcampos/nvim-snippy) - Snippet plugin written in Lua with support for [vim-snippets (⭐4.9k)](https://github.com/honza/vim-snippets).
*   [ellisonleao/carbon-now.nvim (⭐190)](https://github.com/ellisonleao/carbon-now.nvim) - Create beautiful code snippets directly from Neovim.
*   [TobinPalmer/rayso.nvim (⭐82)](https://github.com/TobinPalmer/rayso.nvim) - Create code snippets in Neovim using [ray.so](https://ray.so).
*   [mrcjkb/haskell-snippets.nvim (⭐33)](https://github.com/mrcjkb/haskell-snippets.nvim) - Haskell snippets for LuaSnip, powered by Tree-sitter and LSP.
*   [rafamadriz/friendly-snippets (⭐2.6k)](https://github.com/rafamadriz/friendly-snippets) - Set of preconfigured snippets for different languages.
*   [cvigilv/esqueleto.nvim (⭐106)](https://github.com/cvigilv/esqueleto.nvim) - Simple templates to use when creating new files.
*   [chrisgrieser/nvim-scissors (⭐555)](https://github.com/chrisgrieser/nvim-scissors) - Automagical editing and creation of snippets.
*   [guilherme-puida/tesoura.nvim (⭐28)](https://github.com/guilherme-puida/tesoura.nvim) - A flexible snippet system using Neovim's new snippet API.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Register

*   [gennaro-tedesco/nvim-peekup (⭐328)](https://github.com/gennaro-tedesco/nvim-peekup) - Dynamically interact with Vim registers.
*   [tversteeg/registers.nvim (⭐617)](https://github.com/tversteeg/registers.nvim) - Non-obtrusive minimal preview of Vim registers.
*   [acksld/nvim-neoclip.lua (⭐1.1k)](https://github.com/AckslD/nvim-neoclip.lua) - Clipboard manager Neovim plugin with telescope integration.
*   [tenxsoydev/karen-yank.nvim (⭐89)](https://github.com/tenxsoydev/karen-yank.nvim) - More intentional register handling with delete, cut and yank mappings.
*   [desdic/macrothis.nvim (⭐34)](https://github.com/desdic/macrothis.nvim) - Save and load macros/registers.
*   [kr40/nvim-macros (⭐71)](https://github.com/kr40/nvim-macros) - Easy way to save and load Macros, with backup and formatting options.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Marks

*   [cbochs/grapple.nvim (⭐672)](https://github.com/cbochs/grapple.nvim) - Provides tagging, cursor tracking, and immediate navigation to important project files.
*   [chentoast/marks.nvim (⭐1.1k)](https://github.com/chentoast/marks.nvim) - A better user experience for viewing and interacting with Vim marks.
*   [ThePrimeagen/harpoon (⭐8.8k)](https://github.com/ThePrimeagen/harpoon/tree/harpoon2) - A per project, auto updating and editable marks utility for fast file navigation.
*   [otavioschwanck/arrow.nvim (⭐713)](https://github.com/otavioschwanck/arrow.nvim) - Like harpoon, but with a different UX, single keybinding needed and statusline support.
*   [ofirgall/open.nvim (⭐68)](https://github.com/ofirgall/open.nvim) - Open the current word with custom openers, GitHub shorthand for example.
*   [LeonHeidelbach/trailblazer.nvim (⭐280)](https://github.com/LeonHeidelbach/trailblazer.nvim) - TrailBlazer introduces a stack based mark system that enables a completely new dynamic and super fast workflow using project wide marks.
*   [tomasky/bookmarks.nvim (⭐183)](https://github.com/tomasky/bookmarks.nvim) - Bookmarks with global file storage, written in Lua.
*   [LintaoAmons/bookmarks.nvim (⭐277)](https://github.com/LintaoAmons/bookmarks.nvim) - Your new bookmarks option: simple yet powerful.
*   [heilgar/bookmarks.nvim (⭐24)](https://github.com/heilgar/bookmarks.nvim) - Manage line bookmarks with Telescope integration and SQLite storage.
*   [desdic/marlin.nvim (⭐31)](https://github.com/desdic/marlin.nvim) - Like harpoon, but with key differences like project path, split support, no UI.
*   [fnune/recall.nvim (⭐85)](https://github.com/fnune/recall.nvim) - Recall refines the use of marks by focusing on global marks, streamlining their usage and enhancing their visibility and navigability.
*   [niuiic/track.nvim (⭐24)](https://github.com/niuiic/track.nvim) - Enhanced mark with description. Track the thought process of reading source code.
*   [tristone13th/lspmark.nvim (⭐56)](https://github.com/tristone13th/lspmark.nvim) - Sane project-wise bookmarks with persistent storage based on LSP.
*   [EvWilson/spelunk.nvim (⭐144)](https://github.com/EvWilson/spelunk.nvim) - Create and manage bookmarks as stacks with a friendly UI.
*   [2KAbhishek/markit.nvim (⭐54)](https://github.com/2KAbhishek/markit.nvim) - Improved global marks and project wide bookmarks, to quickly navigate files.
*   [zongben/navimark.nvim (⭐20)](https://github.com/zongben/navimark.nvim) - An easy and powerful bookmark manager with telescope.
*   [Beargruug/skipper.nvim (⭐7)](https://github.com/Beargruug/skipper.nvim/) - Jump between functions in a file with ease.
*   [mohseenrm/marko.nvim (⭐9)](https://github.com/mohseenrm/marko.nvim) - Behind the scenes, global marks management for different projects.
*   [y3owk1n/warp.nvim (⭐11)](https://github.com/y3owk1n/warp.nvim) - Simple harpoon alternative that focuses on marking & navigating between files.
*   [walkersumida/fusen.nvim (⭐29)](https://github.com/walkersumida/fusen.nvim) - Sticky note bookmarks, per Git branch with hover annotations and Telescope integration.
*   [markgandolfo/dartboard.nvim (⭐15)](https://github.com/markgandolfo/dartboard.nvim) - Mark files and quickly access them, inspired by Harpoon and Lasso.
*   [dimtion/guttermarks.nvim (⭐42)](https://github.com/dimtion/guttermarks.nvim) - Display marks in the buffer gutter.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Search

*   [wurli/visimatch.nvim (⭐71)](https://github.com/wurli/visimatch.nvim) - Adds highlights to any text matching the current selection in visual mode.
*   [kevinhwang91/nvim-hlslens (⭐880)](https://github.com/kevinhwang91/nvim-hlslens) - Helps you better glance searched information, seamlessly jump matched instances.
*   [rktjmp/highlight-current-n.nvim (⭐92)](https://github.com/rktjmp/highlight-current-n.nvim) - Highlights the current /, ? or \* match under your cursor when pressing n or N and gets out of the way afterwards.
*   [ray-x/sad.nvim (⭐201)](https://github.com/ray-x/sad.nvim) - Space Age seD in Neovim. Batch file edit tool, a wrapper for [sad (⭐2k)](https://github.com/ms-jpq/sad)
*   [s1n7ax/nvim-search-and-replace (⭐71)](https://github.com/s1n7ax/nvim-search-and-replace) - Search and replace in multiple files at the same time from the current working directory.
*   [AckslD/muren.nvim (⭐365)](https://github.com/AckslD/muren.nvim/) - Multiple replacements through interactive UI.
*   [nvim-pack/nvim-spectre (⭐2.3k)](https://github.com/nvim-pack/nvim-spectre) - Search and replace panel.
*   [nvimdev/hlsearch.nvim (⭐78)](https://github.com/nvimdev/hlsearch.nvim) - Auto remove search highlight and rehighlight when using n or N.
*   [mangelozzi/rgflow.nvim (⭐105)](https://github.com/mangelozzi/rgflow.nvim) - Quickly get RipGrep results into an editable Quickfix list, while learning RipGrep's CLI.
*   [duane9/nvim-rg (⭐44)](https://github.com/duane9/nvim-rg) - Run RipGrep asynchronously and see results in a quickfix window.
*   [FabianWirth/search.nvim (⭐186)](https://github.com/FabianWirth/search.nvim) - Tabs for different Telescope pickers.
*   [backdround/improved-search.nvim (⭐60)](https://github.com/backdround/improved-search.nvim) - Add search abilities.
*   [polirritmico/telescope-lazy-plugins.nvim (⭐68)](https://github.com/polirritmico/telescope-lazy-plugins.nvim) - A Telescope picker to quickly access plugins configurations from the lazy.nvim spec.
*   [MagicDuck/grug-far.nvim (⭐1.7k)](https://github.com/MagicDuck/grug-far.nvim) - Buffer-based live search and replace with full power of `rg` flags. Grug like!
*   [chrisgrieser/nvim-rip-substitute (⭐296)](https://github.com/chrisgrieser/nvim-rip-substitute) - Search and replace in the current buffer with a modern UI and modern regex flavor. A substitute for Vim's `:substitute` using `ripgrep`.
*   [wsdjeg/flygrep.nvim (⭐17)](https://github.com/wsdjeg/flygrep.nvim) - Search text in a floating window asynchronously.
*   [prochri/telescope-all-recent.nvim (⭐149)](https://github.com/prochri/telescope-all-recent.nvim) - Frequency and recency sorter for any Telescope picker.
*   [mahyarmirrashed/search-and-replace.nvim (⭐8)](https://github.com/mahyarmirrashed/search-and-replace.nvim) - Simple, effective, search and replace functionality for the pragmatic engineer.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Fuzzy Finder

*   [nvim-telescope/telescope.nvim (⭐19k)](https://github.com/nvim-telescope/telescope.nvim) - Telescope.nvim is a highly [extendable (⭐19k)](https://github.com/nvim-telescope/telescope.nvim/wiki/Extensions) fuzzy finder over lists. Built on the latest awesome features from Neovim core. Telescope is centered around modularity, allowing for easy customization.
*   [vijaymarupudi/nvim-fzf (⭐347)](https://github.com/vijaymarupudi/nvim-fzf) - A Lua API for using FZF (Neovim >= 0.5). Allows for full asynchronicity for UI speed and usability.
*   [camspiers/snap (⭐505)](https://github.com/camspiers/snap) - An extensible fuzzy finder. Similar to Telescope, and optimized for performance, especially when grepping in large codebases.
*   [ibhagwan/fzf-lua (⭐3.9k)](https://github.com/ibhagwan/fzf-lua) - The Lua version of `fzf.vim`, high-performance and fully async, supports `nvim-web-devicons`, Git indicators, LSP, quickfix/location lists and more. Also supports [`skim`](https://github.com/lotabout/skim) as its fzf binary.
*   [jvgrootveld/telescope-zoxide (⭐366)](https://github.com/jvgrootveld/telescope-zoxide) - Telescope integration for [zoxide (⭐32k)](https://github.com/ajeetdsouza/zoxide), a smart directory picker that tracks your usage.
*   [nvim-mini/mini.nvim#mini.fuzzy (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-fuzzy.md) - Module of `mini.nvim` with functions to perform fuzzy matching of one string to others along with fast Telescope sorter.
*   [axkirillov/easypick.nvim (⭐406)](https://github.com/axkirillov/easypick.nvim) - Easypick lets you easily create Telescope pickers from arbitrary console commands.
*   [linrongbin16/fzfx.nvim (⭐152)](https://github.com/linrongbin16/fzfx.nvim) - A fuzzy finder that updates on every keystroke.
*   [nvim-mini/mini.nvim#mini.pick (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-pick.md) - Module of `mini.nvim` with general purpose interactive non-blocking picker that has one window design, toggleable preview, flexible and fast default match, and much more.
*   [nvim-mini/mini.nvim#mini.extra (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-extra.md) - Module of `mini.nvim` with extra functionality for its modules. Contains 20+ 'mini.pick' pickers, 'mini.ai' textobjects, and more.
*   [fdschmidt93/telescope-egrepify.nvim (⭐138)](https://github.com/fdschmidt93/telescope-egrepify.nvim) - Telescope plugin for better `rg` flags in `live_grep`.
*   [nvim-telescope/telescope-media-files.nvim (⭐520)](https://github.com/nvim-telescope/telescope-media-files.nvim) - Preview images, pdf, epub, video, and fonts using Telescope.
*   [crispgm/telescope-heading.nvim (⭐138)](https://github.com/crispgm/telescope-heading.nvim) - Telescope extension to switch between headings of AsciiDoc, Markdown, Vimdoc, etc.
*   [bassamsdata/namu.nvim (⭐392)](https://github.com/bassamsdata/namu.nvim) - Flexible and sleek fuzzy picker, LSP symbol navigator, and more.
*   [folke/snacks.nvim#picker (⭐6.7k)](https://github.com/folke/snacks.nvim/blob/main/docs/picker.md) - Modern fuzzy-finder to navigate the Neovim universe.
*   [dmtrKovalenko/fff.nvim (⭐1.2k)](https://github.com/dmtrKovalenko/fff.nvim) - Fuzzy file picker with a standalone native implementation of file indexing and typo resistant fuzzy matcher. Includes all the QOL features, file previews (and images), frecency sorting, last query matching, proximity, Git status bonuses and much more.
*   [wsdjeg/picker.nvim (⭐9)](https://github.com/wsdjeg/picker.nvim) - Simple fuzzy finder, including files, ctags outline, and more.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## File Explorer

*   [nvim-tree/nvim-tree.lua (⭐8.3k)](https://github.com/nvim-tree/nvim-tree.lua) - A simple and fast file explorer tree.
*   [luukvbaal/nnn.nvim (⭐451)](https://github.com/luukvbaal/nnn.nvim) - File explorer powered by [nnn (⭐21k)](https://github.com/jarun/nnn) and Lua.
*   [tamago324/lir.nvim (⭐369)](https://github.com/tamago324/lir.nvim) - Simple file explorer.
*   [kevinhwang91/rnvimr (⭐840)](https://github.com/kevinhwang91/rnvimr) - A simple yet amazing file explorer.
*   [Xuyuanp/yanil (⭐98)](https://github.com/Xuyuanp/yanil) - Yet Another Nerdtree In Lua.
*   [ms-jpq/chadtree (⭐1.7k)](https://github.com/ms-jpq/chadtree) - File manager. Better than NERDTree.
*   [rolv-apneseth/tfm.nvim (⭐96)](https://github.com/Rolv-Apneseth/tfm.nvim) - Similar to `fm-nvim`, this provides Neovim integration for several popular terminal file managers (including [yazi (⭐31k)](https://github.com/sxyazi/yazi)).
*   [nvim-neo-tree/neo-tree.nvim (⭐5.1k)](https://github.com/nvim-neo-tree/neo-tree.nvim) - Neo-tree is a Neovim plugin to browse the file system and other tree like structures in whatever style suits you, including sidebars, floating windows, netrw split style, or all of them at once.
*   [theblob42/drex.nvim (⭐95)](https://github.com/TheBlob42/drex.nvim) - A simple and configurable file explorer written in Lua.
*   [SidOfc/carbon.nvim (⭐184)](https://github.com/SidOfc/carbon.nvim) - The simple directory tree viewer written in Lua.
*   [kiran94/s3edit.nvim (⭐48)](https://github.com/kiran94/s3edit.nvim) - Edit files from Amazon S3 directly from Neovim.
*   [stevearc/oil.nvim (⭐6k)](https://github.com/stevearc/oil.nvim) - Edit your filesystem like a buffer.
*   [kelly-lin/ranger.nvim (⭐180)](https://github.com/kelly-lin/ranger.nvim) - [Ranger (⭐17k)](https://github.com/ranger/ranger) integration for Neovim.
*   [mikavilpas/yazi.nvim (⭐1.4k)](https://github.com/mikavilpas/yazi.nvim) - Integration with the Yazi terminal file manager.
*   [simonmclean/triptych.nvim (⭐245)](https://github.com/simonmclean/triptych.nvim) - A directory browser inspired by Ranger.
*   [nvim-mini/mini.nvim#mini.files (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-files.md) - Module of `mini.nvim` providing file explorer with column view capable of manipulating file system by editing text. Can create/delete/rename/copy/move files/directories inside and across directories.
*   [prichrd/netrw.nvim (⭐257)](https://github.com/prichrd/netrw.nvim) - Add icons and custom keybindings to netrw.
*   [X3eRo0/dired.nvim (⭐172)](https://github.com/X3eRo0/dired.nvim) - A file browser inspired by Emacs Dired.
*   [saifulapm/neotree-file-nesting-config (⭐26)](https://github.com/saifulapm/neotree-file-nesting-config) - Pre-defined file nesting rules for `neo-tree.nvim`.
*   [Enigama/miss.nvim (⭐11)](https://github.com/Enigama/miss.nvim) - Simple popup with changed `unsaved` files, allowing you to save and open them. Helps to avoid forgetting to add something to GitHub or similar.
*   [vodchella/hodur.nvim (⭐20)](https://github.com/vodchella/hodur.nvim) - Allows you to quickly open a file or copy URL located under cursor.
*   [A7Lavinraj/fyler.nvim (⭐637)](https://github.com/A7Lavinraj/fyler.nvim) - File manager which can edit file system like a buffer with tree view.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Project

*   [Abstract-IDE/penvim (⭐50)](https://github.com/Abstract-IDE/penvim) - Project's root directory and documents Indentation detector with project based config loader.
*   [windwp/nvim-projectconfig (⭐109)](https://github.com/windwp/nvim-projectconfig) - Load Neovim config depend on project directory.
*   [DrKJeff16/project.nvim (⭐100)](https://github.com/DrKJeff16/project.nvim) - An actively maintained fork of [`ahmedkhalf/project.nvim`](https://github.com/ahmedkhalf/project.nvim) with documented code, `fzf-lua` support and new features.
*   [klen/nvim-config-local (⭐173)](https://github.com/klen/nvim-config-local) - Secure load local config files from working directories.
*   [cljoly/telescope-repo.nvim (⭐236)](https://github.com/cljoly/telescope-repo.nvim) - Telescope picker to jump to any repository (Git or other) on the file system.
*   [otavioschwanck/telescope-alternate.nvim (⭐106)](https://github.com/otavioschwanck/telescope-alternate.nvim) - Alternate between common files using telescope.
*   [natecraddock/workspaces.nvim (⭐366)](https://github.com/natecraddock/workspaces.nvim) - Manage workspace directories.
*   [GnikDroy/projections.nvim (⭐246)](https://github.com/GnikDroy/projections.nvim) - Tiny project + session manager.
*   [nyngwang/suave.lua (⭐71)](https://github.com/nyngwang/suave.lua) - Multi-tabs project session automation.
*   [desdic/telescope-rooter.nvim (⭐26)](https://github.com/desdic/telescope-rooter.nvim) - Makes sure to always start telescope (and only telescope) from the project/root directory.
*   [SalOrak/whaler.nvim (⭐62)](https://github.com/SalOrak/whaler.nvim) - Telescope extension to move between directories blazingly fast.
*   [nvim-mini/mini.nvim#mini.visits (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-visits.md) - Module of `mini.nvim` to persistently track and reuse file system visits. Allows listing "recent"/"frequent"/"frecent" visits, adding/removing labels to visits and other data.
*   [LintaoAmons/cd-project.nvim (⭐124)](https://github.com/LintaoAmons/cd-project.nvim) - All you need is just an easier way to `cd` to another project directory.
*   [LucasTavaresA/headers.nvim (⭐4)](https://github.com/LucasTavaresA/headers.nvim) - Zero-config header/footer warnings.
*   [zongben/proot.nvim (⭐9)](https://github.com/zongben/proot.nvim) - Lightweight project navigator with telescope.
*   [wsdjeg/rooter.nvim (⭐20)](https://github.com/wsdjeg/rooter.nvim) - Change working directory to project root.
*   [mrjones2014/codesettings.nvim (⭐32)](https://github.com/mrjones2014/codesettings.nvim) - Load project-local settings (like `.vscode/settings.json`) into Neovim 0.11+ native LSP settings easily.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Color

*   [catgoose/nvim-colorizer.lua (⭐970)](https://github.com/catgoose/nvim-colorizer.lua) - A high-performance color highlighter which has no external dependencies.
*   [winston0410/range-highlight.nvim (⭐209)](https://github.com/winston0410/range-highlight.nvim) - An extremely lightweight plugin (\~ 120loc) that highlights ranges you have entered in commandline.
*   [folke/twilight.nvim (⭐1.5k)](https://github.com/folke/twilight.nvim) - Dim inactive portions of the code you're editing using Tree-sitter.
*   [uga-rosa/ccc.nvim (⭐946)](https://github.com/uga-rosa/ccc.nvim) - Super powerful color picker / colorizer plugin.
*   [lcheylus/overlength.nvim (⭐49)](https://github.com/lcheylus/overlength.nvim) - A small plugin to highlight too long lines.
*   [max397574/colortils.nvim (⭐433)](https://github.com/max397574/colortils.nvim) - A plugin providing utils to work with colors (picker, conversion) inside Neovim.
*   [Mr-LLLLL/interestingwords.nvim (⭐52)](https://github.com/Mr-LLLLL/interestingwords.nvim) - Highlight multiple word same time and navigate word under cursor with scrolling smoothly, display search count in virualtext.
*   [nvim-mini/mini.nvim#mini.hipatterns (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-hipatterns.md) - Module of `mini.nvim` to highlight patterns in text with configurable highlighters. Works asynchronously with configurable debounce delay.
*   [miversen33/sunglasses.nvim (⭐157)](https://github.com/miversen33/sunglasses.nvim) - Dynamic Colorscheme/highlight adjuster on window switching.
*   [rasulomaroff/reactive.nvim (⭐238)](https://github.com/rasulomaroff/reactive.nvim) - Set global and window-specific highlights or trigger callbacks when modes/operators change or windows are switched.
*   [moyiz/command-and-cursor.nvim (⭐22)](https://github.com/moyiz/command-and-cursor.nvim) - Highlight cursor and visual selections when entering command mode.
*   [rachartier/tiny-devicons-auto-colors.nvim (⭐128)](https://github.com/rachartier/tiny-devicons-auto-colors.nvim) - Automatically updates nvim-web-devicons colors based on your current colorscheme.
*   [TaDaa/vimade (⭐646)](https://github.com/TaDaa/vimade) - Dim, fade, tint, animate, and customize colors in your windows and buffers.
*   [xzbdmw/colorful-menu.nvim (⭐430)](https://github.com/xzbdmw/colorful-menu.nvim) - Colorize your auto completion menu using Tree-sitter.
*   [nvzone/minty (⭐566)](https://github.com/nvzone/minty) - Beautifully crafted color tools.
*   [3ZsForInsomnia/pacer.nvim (⭐2)](https://github.com/3ZsForInsomnia/pacer.nvim) - Creates a reading pacer by highlighting one word at a time and dimming all text outside the current paragraph-and-some to help you read faster.
*   [wsdjeg/cpicker.nvim (⭐8)](https://github.com/wsdjeg/cpicker.nvim) - A lightweight color palette plugin that supports a wide range of color models.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Colorscheme

Each colorscheme will have one or more of the tags listed below. If a tag is missing
then it is not supported:

<!--lint disable awesome-list-item-->

*   ***`[TS]`*** - Has Tree-sitter highlighting.
*   ***`[LSP]`*** - Has LSP Semantic Tokens support.
*   ***`[L/D]`*** - Has both "light" and "dark" variants.
*   ***`[Lua]`*** - Is written in Lua.
*   ***`[Fnl]`*** - Is written in Fennel.

<!--lint enable awesome-list-item-->

*   [kuri-sun/yoda.nvim (⭐10)](https://github.com/kuri-sun/yoda.nvim) - ***`[TS][LSP][L/D][Lua]`*** Muted green palette for focused, balanced editing.
*   [wurli/cobalt.nvim (⭐23)](https://github.com/wurli/cobalt.nvim) - ***`[TS][LSP][Lua]`*** A (mostly) faithful port of the classic blue theme from TextMate.
*   [datsfilipe/min-theme.nvim (⭐54)](https://github.com/datsfilipe/min-theme.nvim) - ***`[TS][LSP][Lua]`*** It's a port of Min, a minimal theme for VSCode, written in Lua.
*   [github-main-user/lytmode.nvim (⭐18)](https://github.com/github-main-user/lytmode.nvim) - ***`[TS][LSP][Lua]`*** A unique in-between theme inspired by LYT-Mode for Obsidian. Not quite dark, not quite light — just right.
*   [datsfilipe/vesper.nvim (⭐194)](https://github.com/datsfilipe/vesper.nvim) - ***`[TS][LSP][Lua]`*** It's a port of the popular VS Code theme Vesper, written in Lua.
*   [sontungexpt/witch (⭐72)](https://github.com/sontungexpt/witch) - ***`[TS][LSP][L/D][Lua]`*** The primary stinvim distro colorscheme includes the default feature of dimming inactive windows, along with various other customization options for users.
*   [Abstract-IDE/Abstract-cs (⭐111)](https://github.com/Abstract-IDE/Abstract-cs) - ***`[TS][LSP][Lua]`*** Colorscheme written in Lua, specially made for roshnivim with Tree-sitter support.
*   [rafamadriz/neon (⭐204)](https://github.com/rafamadriz/neon) - ***`[TS][LSP][L/D][Lua]`*** Customizable colorscheme with excellent italic and bold support, dark and light variants. Made to work and look good with Tree-sitter.
*   [tomasiser/vim-code-dark (⭐995)](https://github.com/tomasiser/vim-code-dark) - ***`[TS]`*** A dark color scheme heavily inspired by the look of the Dark+ scheme of VSCode.
*   [Mofiqul/vscode.nvim (⭐923)](https://github.com/Mofiqul/vscode.nvim) - ***`[TS][L/D][Lua]`*** A Lua port of vim-code-dark colorscheme with VSCode light and dark theme.
*   [askfiy/visual\_studio\_code (⭐211)](https://github.com/askfiy/visual_studio_code) - ***`[TS][LSP][L/D][Lua]`***  A Neovim theme that highly restores VSCode, so that your friends will no longer be surprised that you use Neovim, because they will think you are using VSCode.
*   [marko-cerovac/material.nvim (⭐1.1k)](https://github.com/marko-cerovac/material.nvim) - ***`[TS][LSP][L/D][Lua]`*** Material.nvim is a highly configurable colorscheme written in Lua and based on the material palette.
*   [bluz71/vim-nightfly-colors (⭐917)](https://github.com/bluz71/vim-nightfly-colors) - ***`[TS][LSP][Lua]`*** A dark midnight colorscheme with modern Neovim support including Tree-sitter.
*   [bluz71/vim-moonfly-colors (⭐1.2k)](https://github.com/bluz71/vim-moonfly-colors) - ***`[TS][LSP][Lua]`*** A dark charcoal colorscheme with modern Neovim support including Tree-sitter.
*   [ChristianChiarulli/nvcode-color-schemes.vim (⭐306)](https://github.com/ChristianChiarulli/nvcode-color-schemes.vim) - ***`[TS]`*** Nvcode, onedark, nord colorschemes with Tree-sitter support.
*   [folke/tokyonight.nvim (⭐7.7k)](https://github.com/folke/tokyonight.nvim) - ***`[TS][LSP][L/D][Lua]`*** A clean, dark and light Neovim theme written in Lua, with support for LSP, Tree-sitter and lots of plugins.
*   [comfysage/evergarden (⭐532)](https://github.com/comfysage/evergarden) - ***`[TS][LSP][L/D][Lua]`*** A comfy Neovim colorscheme for cozy morning coding.
*   [uhs-robert/oasis.nvim (⭐79)](https://github.com/uhs-robert/oasis.nvim) - ***`[TS][LSP][L/D][Lua]`*** Desert theme from Vim ported to Neovim and made modern with 12 variants, a collection of dark themes for every color of the rainbow.
*   [sainnhe/sonokai (⭐1.9k)](https://github.com/sainnhe/sonokai) - ***`[TS][LSP]`*** High Contrast & Vivid Color Scheme based on Monokai Pro.
*   [nyoom-engineering/oxocarbon.nvim (⭐1.5k)](https://github.com/nyoom-engineering/oxocarbon.nvim) - ***`[TS][LSP][L/D][Lua]`*** A dark and light Neovim theme written in fennel, inspired by IBM Carbon.
*   [mhartington/oceanic-next (⭐1.2k)](https://github.com/mhartington/oceanic-next) - ***`[TS][L/D]`*** Oceanic Next theme.
*   [nvimdev/zephyr-nvim (⭐372)](https://github.com/nvimdev/zephyr-nvim) - ***`[TS][Lua]`*** A dark colorscheme with Tree-sitter support.
*   [rockerBOO/boo-colorscheme-nvim (⭐234)](https://github.com/rockerBOO/boo-colorscheme-nvim) - ***`[TS][Lua]`*** A colorscheme with handcrafted support for LSP, Tree-sitter.
*   [jim-at-jibba/ariake.nvim (⭐23)](https://github.com/jim-at-jibba/ariake.nvim) - ***`[TS][LSP][Lua]`*** A port of the great Atom theme. Beautiful, dark colour scheme.
*   [Th3Whit3Wolf/onebuddy (⭐101)](https://github.com/Th3Whit3Wolf/onebuddy) - ***`[TS][L/D][Lua]`*** Light and dark atom one theme.
*   [ishan9299/modus-theme-vim (⭐177)](https://github.com/ishan9299/modus-theme-vim) - ***`[TS][L/D][Lua]`*** This is a color scheme developed by Protesilaos Stavrou for emacs.
*   [sainnhe/edge (⭐986)](https://github.com/sainnhe/edge) - ***`[TS][LSP][L/D]`*** Clean and Elegant Color Scheme inspired by Atom One and Material.
*   [bkegley/gloombuddy (⭐48)](https://github.com/bkegley/gloombuddy) - ***`[TS][Lua]`*** Gloom inspired theme.
*   [Th3Whit3Wolf/one-nvim (⭐115)](https://github.com/Th3Whit3Wolf/one-nvim) - ***`[TS][L/D][Lua]`*** An Atom One inspired dark and light colorscheme.
*   [Th3Whit3Wolf/space-nvim (⭐48)](https://github.com/Th3Whit3Wolf/space-nvim) - ***`[TS][L/D][Lua]`*** A spacemacs inspired dark and light colorscheme.
*   [ray-x/aurora (⭐370)](https://github.com/ray-x/aurora) - ***`[TS][LSP][Lua]`*** A 24-bit dark theme with Tree-sitter and LSP support.
*   [ray-x/starry.nvim (⭐242)](https://github.com/ray-x/starry.nvim) - ***`[TS][LSP][L/D][Lua]`*** A collection of modern Neovim colorschemes: material, moonlight, dracula (blood), monokai, mariana, emerald, earlysummer, middlenight\_blue, darksolar.
*   [tanvirtin/monokai.nvim (⭐381)](https://github.com/tanvirtin/monokai.nvim) - ***`[TS][LSP][Lua]`*** Monokai theme written in Lua.
*   [ofirgall/ofirkai.nvim (⭐133)](https://github.com/ofirgall/ofirkai.nvim) - ***`[TS][LSP][Lua]`*** Monokai theme that aims to feel like Sublime Text.
*   [savq/melange-nvim (⭐910)](https://github.com/savq/melange-nvim) - ***`[TS][LSP][L/D][Lua]`*** Warm colorscheme written in Lua with support for various terminal emulators.
*   [fenetikm/falcon (⭐822)](https://github.com/fenetikm/falcon) - ***`[TS][Lua]`*** A colour scheme for terminals, Vim and friends.
*   [andersevenrud/nordic.nvim (⭐175)](https://github.com/andersevenrud/nordic.nvim) - ***`[TS][Lua]`*** A nord-esque colorscheme.
*   [AlexvZyl/nordic.nvim (⭐959)](https://github.com/AlexvZyl/nordic.nvim) - ***`[TS][Lua]`*** Nord for Neovim, but warmer and darker. Supports a variety of plugins and other platforms.
*   [shaunsingh/nord.nvim (⭐965)](https://github.com/shaunsingh/nord.nvim) - ***`[TS][Lua]`*** Neovim theme based off of the Nord Color Palette.
*   [Tsuzat/NeoSolarized.nvim (⭐204)](https://github.com/Tsuzat/NeoSolarized.nvim) - ***`[TS][LSP][L/D][Lua]`*** NeoSolarized colorscheme with full transparency.
*   [svrana/neosolarized.nvim (⭐166)](https://github.com/svrana/neosolarized.nvim) - ***`[TS][LSP][Lua]`*** Dark solarized colorscheme using colorbuddy for easy customization.
*   [ishan9299/nvim-solarized-lua (⭐201)](https://github.com/ishan9299/nvim-solarized-lua) - ***`[TS][Lua]`*** Solarized colorscheme in Lua (Neovim >= 0.5).
*   [jthvai/lavender.nvim](https://codeberg.org/jthvai/lavender.nvim) - ***`[TS][LSP][Lua]`*** Purple-hued dark mode colorscheme; a complete rewrite of shaunsingh/moonlight.nvim.
*   [navarasu/onedark.nvim (⭐1.9k)](https://github.com/navarasu/onedark.nvim) - ***`[TS][LSP][Lua]`*** A One Dark Theme (Neovim >= 0.5) written in Lua based on Atom's One Dark Theme.
*   [sainnhe/gruvbox-material (⭐2.4k)](https://github.com/sainnhe/gruvbox-material) - ***`[TS][LSP]`*** Gruvbox modification with softer contrast and Tree-sitter support.
*   [sainnhe/everforest (⭐3.7k)](https://github.com/sainnhe/everforest) - ***`[TS][LSP][L/D]`*** A green based colorscheme designed to be warm, soft and easy on the eyes.
*   [neanias/everforest-nvim (⭐406)](https://github.com/neanias/everforest-nvim) - ***`[TS][LSP][L/D][Lua]`*** A Lua port of the Everforest colour scheme.
*   [NTBBloodbath/doom-one.nvim (⭐241)](https://github.com/NTBBloodbath/doom-one.nvim) - ***`[TS][L/D][Lua]`*** Lua port of doom-emacs' doom-one.
*   [dracula/vim (⭐1.4k)](https://github.com/dracula/vim) - ***`[TS][LSP]`*** Famous beautiful dark powered theme.
*   [Mofiqul/dracula.nvim (⭐745)](https://github.com/Mofiqul/dracula.nvim) - ***`[TS]`*** Dracula colorscheme for Neovim written in Lua.
*   [niyabits/calvera-dark.nvim (⭐160)](https://github.com/niyabits/calvera-dark.nvim) - ***`[TS][Lua]`*** A port of [VSCode Calvara Dark (⭐12)](https://github.com/saurabhdaware/vscode-calvera-dark) Theme to Neovim with Tree-sitter and many other plugins support.
*   [nxvu699134/vn-night.nvim (⭐44)](https://github.com/nxvu699134/vn-night.nvim) - ***`[Lua]`*** A dark colorscheme written in Lua.
*   [adisen99/codeschool.nvim (⭐44)](https://github.com/adisen99/codeschool.nvim) - ***`[TS][LSP][Lua]`*** Codeschool colorscheme written in Lua with Tree-sitter and built-in LSP support.
*   [projekt0n/github-nvim-theme (⭐2.4k)](https://github.com/projekt0n/github-nvim-theme) - ***`[TS][LSP][L/D][Lua]`*** A GitHub theme, kitty, alacritty written in Lua. Support built-in LSP and Tree-sitter.
*   [kdheepak/monochrome.nvim (⭐157)](https://github.com/kdheepak/monochrome.nvim) - ***`[TS][Lua]`*** A 16-bit monochrome colorscheme that uses [HSLuv](https://www.hsluv.org/) for perceptually distinct gray colors, with support for Tree-sitter and other commonly used plugins.

<!--lint disable awesome-spell-check-->

*   [rose-pine/neovim (⭐2.9k)](https://github.com/rose-pine/neovim) - ***`[TS][LSP][L/D][Lua]`*** All natural pine, faux fur and a bit of soho vibes for the classy minimalist.

<!--lint enable awesome-spell-check-->

*   [zenbones-theme/zenbones.nvim (⭐1k)](https://github.com/zenbones-theme/zenbones.nvim) - ***`[TS][LSP][L/D][Lua]`*** A collection of Vim/Neovim colorschemes designed to highlight code using contrasts and font variations.
*   [catppuccin/nvim (⭐7k)](https://github.com/catppuccin/nvim) - ***`[TS][LSP][L/D][Lua]`*** Warm mid-tone dark theme to show off your vibrant self! With support for native LSP, Tree-sitter, and more.
*   [FrenzyExists/aquarium-vim (⭐311)](https://github.com/FrenzyExists/aquarium-vim) - ***`[TS][L/D]`*** A dark, yet vibrant colorscheme.
*   [EdenEast/nightfox.nvim (⭐3.8k)](https://github.com/EdenEast/nightfox.nvim) - ***`[TS][LSP][L/D][Lua]`*** A soft dark, fully customizable colorscheme with support for LSP, Tree-sitter and a variety of plugins.
*   [ldelossa/vimdark (⭐69)](https://github.com/ldelossa/vimdark) - ***`[TS][L/D]`*** A minimal Vim theme for night time. Loosely based on vim-monotonic and chrome's dark reader extension. A light theme is included as well for the day time.
*   [Everblush/nvim (⭐289)](https://github.com/Everblush/nvim) - ***`[TS][LSP][Lua]`*** A dark, vibrant and beautiful colorscheme written in Lua.
*   [adisen99/apprentice.nvim (⭐46)](https://github.com/adisen99/apprentice.nvim) - ***`[TS][L/D][Lua]`*** Colorscheme written in Lua based on the [Apprentice (⭐914)](https://github.com/romainl/Apprentice) color palette with Tree-sitter and built-in LSP support.
*   [olimorris/onedarkpro.nvim (⭐1k)](https://github.com/olimorris/onedarkpro.nvim) - ***`[TS][L/D][Lua]`*** Atom's iconic One Dark theme. Cacheable, fully customisable, Tree-sitter and LSP semantic token support. Comes with light and dark variants.
*   [rmehri01/onenord.nvim (⭐616)](https://github.com/rmehri01/onenord.nvim) - ***`[TS][LSP][L/D][Lua]`*** A Neovim theme that combines the Nord and Atom One Dark color palettes for a more vibrant programming experience.
*   [nvim-mini/mini.nvim#colorschemes (⭐8.5k)](https://github.com/nvim-mini/mini.nvim#plugin-color-schemes) - ***`[TS][LSP][L/D][Lua]`*** Color schemes included in `mini.nvim`. All of them prioritize high contrast ratio for reading text and computing palettes in perceptually uniform color spaces.
*   [luisiacc/gruvbox-baby (⭐441)](https://github.com/luisiacc/gruvbox-baby) - ***`[TS][LSP][Lua]`*** A modern gruvbox theme with full Tree-sitter support.
*   [titanzero/zephyrium (⭐26)](https://github.com/titanzero/zephyrium) - ***`[TS][Lua]`*** A zephyr-esque theme, written in Lua, with Tree-sitter support.
*   [rebelot/kanagawa.nvim (⭐5.7k)](https://github.com/rebelot/kanagawa.nvim) - ***`[TS][LSP][L/D][Lua]`*** A dark colorscheme inspired by the colors of the famous painting by Katsushika Hokusai.
*   [thesimonho/kanagawa-paper.nvim (⭐340)](https://github.com/thesimonho/kanagawa-paper.nvim) - ***`[TS][LSP][L/D][Lua]`*** Remixed light and dark Kanagawa colourschemes with muted colors.
*   [kevinm6/kurayami.nvim (⭐9)](https://github.com/kevinm6/kurayami.nvim) - ***`[TS][LSP][Lua]`*** Dark only theme with Tree-sitter support.
*   [cpea2506/one\_monokai.nvim (⭐187)](https://github.com/cpea2506/one_monokai.nvim) - ***`[TS][LSP][Lua]`*** One Monokai theme written in Lua.
*   [phha/zenburn.nvim (⭐109)](https://github.com/phha/zenburn.nvim) - ***`[TS][Lua]`*** A low-contrast dark colorscheme with support for various plugins.
*   [chrsm/paramount-ng.nvim (⭐20)](https://github.com/chrsm/paramount-ng.nvim) - ***`[TS][Lua]`*** A dark color scheme written using Lush. Tree-sitter supported.
*   [qaptoR-nvim/chocolatier.nvim (⭐20)](https://github.com/qaptoR-nvim/chocolatier.nvim) - ***`[TS][LSP][Lua]`*** An espresso/kimbie inspired chocolatey theme adapted from ellisonleao/gruvbox.nvim theme as a code template.
*   [rockyzhang24/arctic.nvim (⭐205)](https://github.com/rockyzhang24/arctic.nvim) - ***`[TS][LSP][Lua]`*** A Neovim colorscheme ported from VSCode Dark+ theme with the strict and precise color picking for both the editor and UI.
*   [ramojus/mellifluous.nvim (⭐419)](https://github.com/ramojus/mellifluous.nvim) - ***`[TS][LSP][L/D][Lua]`*** Pleasant and productive colorscheme.
*   [lewpoly/sherbet.nvim (⭐71)](https://github.com/lewpoly/sherbet.nvim) - ***`[TS][Lua]`*** A soothing colorscheme with support for popular plugins and Tree-sitter.
*   [Mofiqul/adwaita.nvim (⭐274)](https://github.com/Mofiqul/adwaita.nvim) - ***`[TS][LSP][L/D][Lua]`*** Colorscheme based on GNOME Adwaita syntax with support for popular plugins.
*   [mellow-theme/mellow.nvim (⭐395)](https://github.com/mellow-theme/mellow.nvim) - ***`[TS][LSP][Lua]`*** A soothing dark color scheme with Tree-sitter support.
*   [gbprod/nord.nvim (⭐283)](https://github.com/gbprod/nord.nvim) - ***`[TS][LSP][Lua]`*** An arctic, north-bluish clean and elegant Neovim theme, based on Nord Palette.
*   [embark-theme/vim (⭐713)](https://github.com/embark-theme/vim) - ***`[TS]`*** A deep inky purple theme leveraging bright colors.
*   [nyngwang/nvimgelion (⭐130)](https://github.com/nyngwang/nvimgelion) - ***`[TS]`*** Neon Genesis Evangelion but for Vimmers.
*   [maxmx03/fluoromachine.nvim (⭐289)](https://github.com/maxmx03/fluoromachine.nvim) - ***`[TS][LSP][Lua]`*** Synthwave x Fluoromachine port.
*   [dasupradyumna/midnight.nvim (⭐232)](https://github.com/dasupradyumna/midnight.nvim) - ***`[TS][LSP][Lua]`*** A modern black Neovim theme with comfortable color contrast for a pleasant visual experience, with LSP and Tree-sitter support.
*   [sonjiku/yawnc.nvim (⭐15)](https://github.com/sonjiku/yawnc.nvim) - ***`[TS][LSP][Lua]`*** Theming using pywal, with a Base16 twist.
*   [uncleTen276/dark\_flat.nvim (⭐43)](https://github.com/uncleTen276/dark_flat.nvim) - ***`[TS][LSP][Lua]`*** A Neovim colorscheme written in Lua ported from Dark Flat iTerm2 theme, with LSP and Tree-sitter support.
*   [zootedb0t/citruszest.nvim (⭐243)](https://github.com/zootedb0t/citruszest.nvim) - ***`[TS][LSP][Lua]`*** A colorscheme that features a combination of bright and juicy colors reminiscent of various citrus fruits, with LSP and Tree-sitter support.
*   [2nthony/vitesse.nvim (⭐65)](https://github.com/2nthony/vitesse.nvim) - ***`[TS][LSP][Lua]`*** Vitesse theme Lua port.
*   [xero/miasma.nvim (⭐464)](https://github.com/xero/miasma.nvim) - ***`[TS][LSP]`*** A dark pastel color scheme inspired by the woods. Built using lush and supports Tree-sitter, diagnostics, CMP, Git-Signs, Telescope, Which-key, Lazy, and more.
*   [Verf/deepwhite.nvim (⭐143)](https://github.com/Verf/deepwhite.nvim) - ***`[TS][LSP][Lua]`*** A light colorscheme inspired by [flatwhite-syntax (⭐185)](https://github.com/biletskyy/flatwhite-syntax) and [elegant-emacs (⭐1.4k)](https://github.com/rougier/elegant-emacs).
*   [judaew/ronny.nvim (⭐16)](https://github.com/judaew/ronny.nvim) - ***`[TS][LSP][Lua]`*** A dark colorscheme, which mostly was inspired by the Monokai originally created by Wimem Hazenberg.
*   [ribru17/bamboo.nvim (⭐431)](https://github.com/ribru17/bamboo.nvim) - ***`[TS][LSP][Lua]`*** A warm green theme.
*   [cryptomilk/nightcity.nvim (⭐70)](https://github.com/cryptomilk/nightcity.nvim) - ***`[TS][LSP][Lua]`*** A dark colorscheme inspired by Inkpot, Jellybeans, Gruvbox and Tokyonight with LSP support.
*   [polirritmico/monokai-nightasty.nvim (⭐159)](https://github.com/polirritmico/monokai-nightasty.nvim) - ***`[TS][LSP][L/D][Lua]`*** A dark/light theme based on the Monokai color palette written in Lua, support for LSP, Tree-sitter and lots of plugins.
*   [oxfist/night-owl.nvim (⭐327)](https://github.com/oxfist/night-owl.nvim) - ***`[TS][LSP][Lua]`*** A [Night Owl colorscheme port from VSCode (⭐2.9k)](https://github.com/sdras/night-owl-vscode-theme) with support for Tree-sitter and semantic tokens.
*   [miikanissi/modus-themes.nvim (⭐383)](https://github.com/miikanissi/modus-themes.nvim) - ***`[TS][LSP][L/D][Lua]`*** Accessible theme, conforming with the highest standard for color contrast (WCAG AAA).
*   [alexmozaidze/palenight.nvim (⭐25)](https://github.com/alexmozaidze/palenight.nvim) - ***`[TS][LSP][Fnl]`*** Palenight colorscheme supporting Tree-sitter, LSP *(including semantic tokens)* and lots of plugins.
*   [scottmckendry/cyberdream.nvim (⭐1.2k)](https://github.com/scottmckendry/cyberdream.nvim) - ***`[TS][L/D][Lua]`*** A high-contrast, futuristic & vibrant coloursheme.
*   [HoNamDuong/hybrid.nvim (⭐141)](https://github.com/HoNamDuong/hybrid.nvim) - ***`[TS][LSP][Lua]`*** A dark theme written in Lua.
*   [sxwpb/halfspace.nvim](https://gitlab.com/sxwpb/halfspace.nvim) - ***`[TS][LSP][Lua]`*** A semi-light colorscheme for minimal eye melting.
*   [bartekjaszczak/distinct-nvim](https://gitlab.com/bartekjaszczak/distinct-nvim) - ***`[TS][LSP][L/D][Lua]`*** Theme with distinct syntax colours. Supports Tree-sitter and semantic highlighting. For people who love multi-colour syntax highlighting.
*   [samharju/synthweave.nvim (⭐60)](https://github.com/samharju/synthweave.nvim) - ***`[TS][LSP][Lua]`*** Synthwave '84 colorscheme port.
*   [loganswartz/sunburn.nvim (⭐21)](https://github.com/loganswartz/sunburn.nvim) - ***`[TS][Lua]`*** A colorscheme sitting somewhere between pastels and solarized, emphasizing readability and hue uniformity above all else.
*   [ptdewey/darkearth-nvim (⭐70)](https://github.com/ptdewey/darkearth-nvim) - ***`[TS][LSP][Fnl]`*** A dark and earthy colorscheme supporting Tree-sitter and LSP.
*   [uloco/bluloco.nvim (⭐399)](https://github.com/uloco/bluloco.nvim) - ***`[TS][LSP][L/D][Lua]`*** A fancy and sophisticated colorscheme for night and day coding. Supports LSP, Tree-sitter and all the plugins you love.
*   [slugbyte/lackluster.nvim (⭐501)](https://github.com/slugbyte/lackluster.nvim) - ***`[TS][LSP][Lua]`*** A delightful mostly grayscale colorscheme that is soft on the eyes, and supports heaps of plugins.
*   [0xstepit/flow.nvim (⭐280)](https://github.com/0xstepit/flow.nvim) - ***`[TS][L/D][Lua]`*** Carefully designed colors to help focusing during coding plus fluorescent details. Support many plugins and tools.
*   [samharju/serene.nvim (⭐45)](https://github.com/samharju/serene.nvim) - ***`[TS][Lua]`*** A soothing and dark Tree-sitter/LSP-supported theme for relaxing your eyes after using more vibrant colorschemes.
*   [killitar/obscure.nvim (⭐77)](https://github.com/killitar/obscure.nvim) - ***`[TS][LSP][Lua]`*** A pastel dark colorscheme inspired by the palette Mellow. Support Tree-sitter, LSP *(including semantic tokens)* and lots of plugins.
*   [bakageddy/alduin.nvim (⭐17)](https://github.com/bakageddy/alduin.nvim) - ***`[TS][LSP][Lua]`*** A port of [alduin (⭐482)](https://github.com/AlessandroYorba/alduin) theme to Lua with Tree-sitter and semantic highlights support.
*   [diegoulloao/neofusion.nvim (⭐226)](https://github.com/diegoulloao/neofusion.nvim) - ***`[TS][LSP][Lua]`*** A theme compatible with Tree-sitter inspired by `gruvbox.nvim`.
*   [bartekjaszczak/luma-nvim](https://gitlab.com/bartekjaszczak/luma-nvim) - ***`[TS][LSP][L/D][Lua]`*** A colorful theme with dark/light modes and adjustable contrast. Supports Tree-sitter and semantic highlighting.
*   [bartekjaszczak/finale-nvim](https://gitlab.com/bartekjaszczak/finale-nvim) - ***`[TS][LSP][Lua]`*** A balanced dark theme, blending vivid and pastel colors for a comfortable, high-contrast experience. Supports Tree-sitter and semantic highlighting.
*   [m15a/nvim-srcerite (⭐7)](https://github.com/m15a/nvim-srcerite) - ***`[TS][Lua]`*** A colorscheme inspired by [Srcery](https://srcery.sh/), based on `nvim-highlite`.
*   [neko-night/nvim (⭐60)](https://github.com/neko-night/nvim) - ***`[TS][LSP][L/D][Lua]`*** A buffet of colorschemes for every taste and mood.
*   [ptdewey/monalisa-nvim (⭐9)](https://github.com/ptdewey/monalisa-nvim) - ***`[TS][LSP][Lua]`*** A dark and colorful Mona Lisa inspired colorscheme.
*   [ntk148v/slack.nvim (⭐5)](https://github.com/ntk148v/slack.nvim) - ***`[TS][L/D][Lua]`*** A ported Slack colorscheme.
*   [y3owk1n/base16-pro-max.nvim (⭐6)](https://github.com/y3owk1n/base16-pro-max.nvim) - ***`[TS][LSP][Lua]`*** Base16 for modern Neovim — not just colors.
*   [ellisonleao/gruvbox.nvim (⭐2.4k)](https://github.com/ellisonleao/gruvbox.nvim) - ***`[TS][LSP][L/D][Lua]`*** Gruvbox community colorscheme Lua port.
*   [pmouraguedes/neodarcula.nvim (⭐11)](https://github.com/pmouraguedes/neodarcula.nvim) - ***`[TS][LSP][Lua]`*** A dark theme with support for transparency, dimming, LSP semantic tokens and more.
*   [jpwol/thorn.nvim (⭐58)](https://github.com/jpwol/thorn.nvim) - ***`[TS][LSP][L/D][Lua]`*** A rich green theme with dark and light options. Supports LSP, transparency, many plugins, and more.
*   [calind/selenized.nvim (⭐28)](https://github.com/calind/selenized.nvim) - ***`[TS][LSP][L/D][Lua]`*** Lua port of [selenized (⭐874)](https://github.com/jan-warchol/selenized) with support for Tree-sitter, `nvim-cmp`, GitSigns, and more.
*   [motaz-shokry/gruvbox.nvim](https://gitlab.com/motaz-shokry/gruvbox.nvim) - ***`[TS][L/D][Lua]`*** A new gruvbox theme with a different background color for the hard variant, and comes with 4 variants.
*   [pebeto/dookie.nvim (⭐9)](https://github.com/pebeto/dookie.nvim) - ***`[TS][Lua]`*** A color scheme inspired by Plan9's acme editor.
*   [metalelf0/jellybeans-nvim (⭐122)](https://github.com/metalelf0/jellybeans-nvim) - ***`[TS][Lua]`*** A port of jellybeans colorscheme.
*   [lalitmee/cobalt2.nvim (⭐112)](https://github.com/lalitmee/cobalt2.nvim) - ***`[Lua]`*** A port of cobalt2 colorscheme using colorbuddy.

### Colorscheme Creation

*   [tjdevries/colorbuddy.nvim (⭐752)](https://github.com/tjdevries/colorbuddy.nvim) - A colorscheme helper. Written in Lua! Quick & Easy Color Schemes.
*   [norcalli/nvim-base16.lua (⭐79)](https://github.com/norcalli/nvim-base16.lua) - Programmatic Lua library for setting base16 themes.
*   [rktjmp/lush.nvim (⭐1.7k)](https://github.com/rktjmp/lush.nvim) - Define Neovim themes as a DSL in Lua, with real-time feedback.
*   [Iron-E/nvim-highlite (⭐243)](https://github.com/Iron-E/nvim-highlite) - A colorscheme generator that is "lite" on logic for the developer.
*   [nvim-mini/mini.nvim#mini.base16 (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-base16.md) - Module of `mini.nvim` with fast implementation of base16 theme for manually supplied palette.
*   [ThemerCorp/themer.lua (⭐256)](https://github.com/ThemerCorp/themer.lua) - A simple highlighter plugin for Neovim. It has a huge collection of colorschemes. It also has ability to create colorschemes for Vim/Neovim and other supported apps (such as kitty and alacritty).
*   [nvim-mini/mini.nvim#mini.colors (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-colors.md) - Module of `mini.nvim` to tweak and save any color scheme. Also can animate transition and convert between some color spaces.
*   [nvim-mini/mini.nvim#mini.hues (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-hues.md) - Module of `mini.nvim` to generate configurable color scheme. Takes only background and foreground colors as required arguments. Can adjust number of hues for non-base colors, saturation, accent color, plugin integration.
*   [loganswartz/polychrome.nvim (⭐26)](https://github.com/loganswartz/polychrome.nvim) - A colorscheme micro-framework, with support for specifying colors directly in many different formats (sRGB, HSL, Oklab, XYZ and more, with intelligent chroma clipping), live editing preview, and a simple DSL.
*   [svermeulen/text-to-colorscheme (⭐316)](https://github.com/svermeulen/text-to-colorscheme) - Allows the user to generate colorschemes with a text prompt using OpenAI's GPT API.
*   [RRethy/base16-nvim (⭐611)](https://github.com/RRethy/base16-nvim) - A base16 colorscheme builder. Includes support for Tree-sitter and LSP highlight groups.

### Colorscheme Switchers

*   [itsfernn/auto-gnome-theme.nvim (⭐12)](https://github.com/itsfernn/auto-gnome-theme.nvim) - Fast colorscheme switcher following GNOME system's light/dark mode (based on `gsetting monitor`).
*   [flashcodes-themayankjha/fkthemes.nvim (⭐10)](https://github.com/flashcodes-themayankjha/fkthemes.nvim) - A fast, lightweight and powerful theme switcher written in Lua.
*   [4e554c4c/darkman.nvim (⭐36)](https://github.com/4e554c4c/darkman.nvim) - Follow the system dark-mode setting on Linux.
*   [f-person/auto-dark-mode.nvim (⭐463)](https://github.com/f-person/auto-dark-mode.nvim) - Follow the system appearance on macOS.
*   [zaldih/themery.nvim (⭐339)](https://github.com/zaldih/themery.nvim) - A new way to change the colorscheme on the fly like in VSCode.
*   [linrongbin16/colorbox.nvim (⭐44)](https://github.com/linrongbin16/colorbox.nvim) - Load all the ultra colorschemes into your Neovim player!
*   [CWood-sdf/pineapple (⭐55)](https://github.com/CWood-sdf/pineapple) - Install any colorscheme in your config without leaving your terminal. Collects every colorscheme on the internet and allows you to preview them all before installing.
*   [BrunoCiccarino/gardenal (⭐5)](https://github.com/BrunoCiccarino/gardenal) - Gardenal is a theme switcher, which allows the user to create keyboard shortcuts to switch between themes with one click.
*   [LmanTW/themify.nvim (⭐58)](https://github.com/LmanTW/themify.nvim/tree/main) - A lightweight colorscheme manager and switcher inspired by Themery.nvim and Lazy.nvim.
*   [nishu-murmu/ThemeSwitch.nvim (⭐4)](https://github.com/nishu-murmu/ThemeSwitch.nvim) - Light weight color scheme switcher.
*   [Erl-koenig/theme-hub.nvim (⭐23)](https://github.com/Erl-koenig/theme-hub.nvim) - Manage and install colorschemes via telescope-pickers.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Bars and Lines

*   [Bekaboo/deadcolumn.nvim (⭐338)](https://github.com/Bekaboo/deadcolumn.nvim) - Shows your colorcolumn dynamically.
*   [ecthelionvi/NeoColumn.nvim (⭐101)](https://github.com/ecthelionvi/NeoColumn.nvim) - Toggleable colorcolumn highlighting specific characters.
*   [m4xshen/smartcolumn.nvim (⭐351)](https://github.com/m4xshen/smartcolumn.nvim) - Hide your colorcolumn when unneeded.
*   [utilyre/barbecue.nvim (⭐880)](https://github.com/utilyre/barbecue.nvim) - A VSCode like winbar.
*   [Bekaboo/dropbar.nvim (⭐1.5k)](https://github.com/Bekaboo/dropbar.nvim) - IDE-like breadcrumbs, out of the box.
*   [SmiteshP/nvim-navic (⭐1.6k)](https://github.com/SmiteshP/nvim-navic) - A simple statusline/winbar component that uses LSP to show your current code context.
*   [luukvbaal/statuscol.nvim (⭐593)](https://github.com/luukvbaal/statuscol.nvim) - Configurable 'statuscolumn' with builtin segments and click handlers.
*   [mawkler/hml.nvim (⭐31)](https://github.com/mawkler/hml.nvim) - Adds `H`/`M`/`L` indicators to your line numbers.
*   [neur1n/noline.nvim (⭐1)](https://github.com/neur1n/noline.nvim) - Fully customizable bars and lines components with no presets nor constraints.
*   [OXY2DEV/bars.nvim (⭐92)](https://github.com/OXY2DEV/bars.nvim) - A starting point/guide for creating custom statusline, statuscolumn, tabline & winbar.

### Statusline

*   [NTBBloodbath/galaxyline.nvim (⭐166)](https://github.com/NTBBloodbath/galaxyline.nvim) - A light-weight and super fast statusline plugin written in Lua.
*   [tjdevries/express\_line.nvim (⭐314)](https://github.com/tjdevries/express_line.nvim) - Supports co-routines, functions and jobs.
*   [sontungexpt/witch-line (⭐53)](https://github.com/sontungexpt/witch-line) - A blazing fast statusline based on reference concept.
*   [nvim-lualine/lualine.nvim (⭐7.6k)](https://github.com/nvim-lualine/lualine.nvim) - A blazing fast and easy to configure Neovim statusline.
*   [adelarsq/neoline.vim (⭐258)](https://github.com/adelarsq/neoline.vim) - A light statusline/tabline plugin using Lua.
*   [ojroques/nvim-hardline (⭐197)](https://github.com/ojroques/nvim-hardline) - A statusline / bufferline inspired by [vim-airline (⭐18k)](https://github.com/vim-airline/vim-airline) that aims to be as light and simple as possible.
*   [beauwilliams/statusline.lua (⭐253)](https://github.com/beauwilliams/statusline.lua) - A zero-config minimal statusline written in Lua featuring awesome integrations and blazing speed!
*   [tamton-aquib/staline.nvim (⭐394)](https://github.com/tamton-aquib/staline.nvim) - A modern lightweight statusline in Lua. Mainly uses unicode symbols for showing info.
*   [windwp/windline.nvim (⭐513)](https://github.com/windwp/windline.nvim) - The next generation statusline. Animation statusline.
*   [konapun/vacuumline.nvim (⭐30)](https://github.com/konapun/vacuumline.nvim) - A galaxyline configuration inspired by airline.
*   [nvim-mini/mini.nvim#mini.statusline (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-statusline.md) - Module of `mini.nvim` for minimal and fast statusline. Supports content change depending on window width.
*   [b0o/incline.nvim (⭐983)](https://github.com/b0o/incline.nvim) - Lightweight floating statuslines, intended for use with Neovim's new global statusline.
*   [rebelot/heirline.nvim (⭐1.2k)](https://github.com/rebelot/heirline.nvim) - Heirline.nvim is a no-nonsense Neovim Statusline plugin designed around recursive inheritance to be exceptionally fast and versatile.
*   [Zeioth/heirline-components.nvim (⭐149)](https://github.com/Zeioth/heirline-components.nvim) - 30+ Heirline.nvim components you can use out of the box to create your perfect user interface.
*   [yaocccc/nvim-lines.lua (⭐39)](https://github.com/yaocccc/nvim-lines.lua) - A fast, light, customizable Neovim statusline and tabline(buffers) plugin.
*   [MunifTanjim/nougat.nvim (⭐202)](https://github.com/MunifTanjim/nougat.nvim) - Hyperextensible Statusline / Tabline / Winbar.
*   [Mr-LLLLL/lualine-ext.nvim (⭐20)](https://github.com/Mr-LLLLL/lualine-ext.nvim) - Show more information on lualine.
*   [mikesmithgh/git-prompt-string-lualine.nvim (⭐26)](https://github.com/mikesmithgh/git-prompt-string-lualine.nvim) - Add git-prompt-string to your statusline.
*   [sschleemilch/slimline.nvim (⭐121)](https://github.com/sschleemilch/slimline.nvim) - A slim, minimal and opinionated Lua statusline.

### Tabline

*   [romgrk/barbar.nvim (⭐2.6k)](https://github.com/romgrk/barbar.nvim) - The Neovim tabline plugin.
*   [akinsho/bufferline.nvim (⭐4.2k)](https://github.com/akinsho/bufferline.nvim) - A snazzy buffer line built using Lua.
*   [crispgm/nvim-tabline (⭐92)](https://github.com/crispgm/nvim-tabline) - Neovim port of tabline.vim with Lua.
*   [alvarosevilla95/luatab.nvim (⭐207)](https://github.com/alvarosevilla95/luatab.nvim) - A simple tabline written in Lua.
*   [johann2357/nvim-smartbufs (⭐51)](https://github.com/johann2357/nvim-smartbufs) - Smart buffer management.
*   [willothy/nvim-cokeline (⭐616)](https://github.com/willothy/nvim-cokeline) - A bufferline for people with addictive personalities.
*   [tomiis4/BufferTabs.nvim (⭐92)](https://github.com/tomiis4/BufferTabs.nvim) - Simple and Fancy tabline.
*   [nvim-mini/mini.nvim#mini.tabline (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-tabline.md) - Module of `mini.nvim` for minimal tabline showing listed buffers in case of one tab and falling back to default otherwise.
*   [rafcamlet/tabline-framework.nvim (⭐98)](https://github.com/rafcamlet/tabline-framework.nvim) - User-friendly framework for building your dream tabline in a few lines of code.
*   [nanozuki/tabby.nvim (⭐717)](https://github.com/nanozuki/tabby.nvim) - A minimal, configurable, Neovim style tabline. Use your Neovim tabs as workspace multiplexer.

### Cursorline

*   [ya2s/nvim-cursorline (⭐449)](https://github.com/ya2s/nvim-cursorline) - A plugin that highlights cursor words and lines.
*   [sontungexpt/stcursorword (⭐80)](https://github.com/sontungexpt/stcursorword) - Highlight the word under the cursor (Improved and compact version of nvim-cursorline).
*   [RRethy/vim-illuminate (⭐2.4k)](https://github.com/RRethy/vim-illuminate) - Highlight the word under the cursor. Neovim's builtin LSP is available, it can be used to highlight more intelligently.
*   [nvim-mini/mini.nvim#mini.cursorword (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-cursorword.md) - Module of `mini.nvim` for automatic highlighting of word under cursor (displayed after customizable delay).
*   [mawkler/modicator.nvim (⭐363)](https://github.com/mawkler/modicator.nvim) - Cursor line number mode indicator. Changes the `CursorLineNr` highlight based on Vim mode.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Startup

*   [nvimdev/dashboard-nvim (⭐2.7k)](https://github.com/nvimdev/dashboard-nvim) - A minimalist dashboard, inspired by doom-emacs.
*   [goolord/alpha-nvim (⭐2.3k)](https://github.com/goolord/alpha-nvim) - A fast and highly customizable greeter like [vim-startify (⭐5.4k)](https://github.com/mhinz/vim-startify)/dashboard-nvim.
*   [nvim-mini/mini.nvim#mini.starter (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-starter.md) - Module of `mini.nvim` for start screen. Displayed items are fully customizable, item selection can be done using prefix query with instant visual feedback.
*   [henriquehbr/nvim-startup.lua](https://sr.ht/~henriquehbr/nvim-startup.lua) - Displays Neovim startup time.
*   [max397574/startup.nvim (⭐493)](https://github.com/max397574/startup.nvim) - The fully customizable greeter for Neovim.
*   [TobinPalmer/Tip.nvim (⭐82)](https://github.com/TobinPalmer/Tip.nvim) - Get a simple tip when you launch Neovim.
*   [CWood-sdf/spaceport.nvim (⭐139)](https://github.com/CWood-sdf/spaceport.nvim) - The start screen that gets you to your projects blazingly fast.
*   [mong8se/actually.nvim (⭐62)](https://github.com/mong8se/actually.nvim) - Load the file you actually meant to load.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Icon

*   [nvim-tree/nvim-web-devicons (⭐2.6k)](https://github.com/nvim-tree/nvim-web-devicons) - A Lua fork of [vim-devicons (⭐5.8k)](https://github.com/ryanoasis/vim-devicons).
*   [nvim-mini/mini.nvim#mini.icons (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-icons.md) - Module of `mini.nvim` meant as a general icon provider. Uses fixed set of highlight groups. Supports various categories, icon and style customizations, caching for performance. Integrates with built-in filetype matching.
*   [2KAbhishek/nerdy.nvim (⭐359)](https://github.com/2KAbhishek/nerdy.nvim/) - Find and insert the latest nerd font glyphs.
*   [stephansama/fzf-nerdfont.nvim (⭐8)](https://github.com/stephansama/fzf-nerdfont.nvim) - A picker for selecting Nerd Font icons using `fzf-lua`.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Media

*   [melMass/echo.nvim (⭐11)](https://github.com/melMass/echo.nvim) - Seamless sound integration for your editing workflow.
*   [\~elisoli/nekovim](https://git.sr.ht/~elisoli/nekovim) - Flexible Discord rich presence.
*   [edluffy/hologram.nvim (⭐1.4k)](https://github.com/edluffy/hologram.nvim) - A cross platform terminal image viewer. Works on macOS and Linux.
*   [HakonHarnes/img-clip.nvim (⭐835)](https://github.com/HakonHarnes/img-clip.nvim) - Effortlessly embed images into any markup language, like LaTeX, Markdown or Typst.
*   [ekickx/clipboard-image.nvim (⭐333)](https://github.com/ekickx/clipboard-image.nvim) - Neovim Lua plugin to paste image from clipboard.
*   [niuiic/cp-image.nvim (⭐10)](https://github.com/niuiic/cp-image.nvim) - Paste image from clipboard and insert the reference code.
*   [askfiy/nvim-picgo (⭐64)](https://github.com/askfiy/nvim-picgo) - A picgo-core-based Neovim plugin, written in Lua, that allows you to upload images to the image bed, which means you can view your images from anywhere on the internet.
*   [davidgranstrom/scnvim (⭐253)](https://github.com/davidgranstrom/scnvim) - Neovim frontend for SuperCollider.
*   [Chaitanyabsrip/present.nvim (⭐156)](https://github.com/Chaitanyabsprip/present.nvim) - A Presentation plugin written in Lua.
*   [3rd/image.nvim (⭐1.8k)](https://github.com/3rd/image.nvim) - Add image support through Kitty's graphics protocol or ueberzugpp.
*   [adelarsq/image\_preview.nvim (⭐188)](https://github.com/adelarsq/image_preview.nvim) - Image preview based on terminal's Image Protocol support.
*   [niuiic/code-shot.nvim (⭐64)](https://github.com/niuiic/code-shot.nvim) - Take a picture of the code.
*   [AntonVanAssche/music-controls.nvim (⭐32)](https://github.com/AntonVanAssche/music-controls.nvim) - Quickly control your favorite music player (Spotify, VLC, and more).
*   [neo451/feed.nvim (⭐188)](https://github.com/neo451/feed.nvim) - Web feed reader written in Lua (RSS, Atom, JSON feed).
*   [vyfor/cord.nvim (⭐521)](https://github.com/vyfor/cord.nvim) - Highly extensible Rich Presence for Discord.
*   [iamt4nk/smm.nvim (⭐29)](https://github.com/iamt4nk/smm.nvim) - Small TUI that allows for controlling Spotify playback.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Note Taking

*   [flashcodes-themayankjha/Fknotes.nvim (⭐12)](https://github.com/flashcodes-themayankjha/Fknotes.nvim) - Take notes, TODOS from anywhere inside your project, search all todos, get reminders and more.
*   [apdot/doodle (⭐84)](https://github.com/apdot/doodle) - A developer-centric knowledge base with project/branch scoped notes, bi-directional linking, note-tagging, graph-view, telescope integration, and Git synchronization.
*   [jameswolensky/marker-groups.nvim (⭐51)](https://github.com/jameswolensky/marker-groups.nvim) - Take persistent code notes without modifying code.
*   [bngarren/checkmate.nvim (⭐333)](https://github.com/bngarren/checkmate.nvim) - A full-featured Markdown-based todo plugin.
*   [lfilho/note2cal.nvim (⭐25)](https://github.com/lfilho/note2cal.nvim) - Create calendar events from Markdown notes (macOS only).
*   [0styx0/abbreinder.nvim (⭐90)](https://github.com/0styx0/abbreinder.nvim) - Abbreviation reminders (Neovim >= 0.5).
*   [jakewvincent/mkdnflow.nvim (⭐769)](https://github.com/jakewvincent/mkdnflow.nvim) - Fluent Markdown notebook navigation & management (create links, follow links, create and manage to-do lists, reference bib files, and more).
*   [jbyuki/nabla.nvim (⭐731)](https://github.com/jbyuki/nabla.nvim) - Take your scientific notes.
*   [nvim-neorg/neorg (⭐7.1k)](https://github.com/nvim-neorg/neorg) - Modernity meets insane extensibility. The future of organizing your life.
*   [nvim-orgmode/orgmode (⭐3.6k)](https://github.com/nvim-orgmode/orgmode) - Orgmode clone written in Lua (Neovim >= 0.5).
*   [nfrid/due.nvim (⭐118)](https://github.com/nfrid/due.nvim) - Displays due for a date string as a virtual text.
*   [jbyuki/venn.nvim (⭐1.1k)](https://github.com/jbyuki/venn.nvim) - Draw ASCII diagrams.
*   [nvim-telekasten/telekasten.nvim (⭐1.6k)](https://github.com/nvim-telekasten/telekasten.nvim) - Work with a text-based, Markdown zettelkasten / wiki and mix it with a journal, based on telescope.nvim.
*   [zk-org/zk-nvim (⭐766)](https://github.com/zk-org/zk-nvim) - Neovim extension for zk, a plain text note-taking assistant.
*   [chrsm/impulse.nvim (⭐100)](https://github.com/chrsm/impulse.nvim) - Read Notion.so notes.
*   [obsidian-nvim/obsidian.nvim (⭐1.3k)](https://github.com/obsidian-nvim/obsidian.nvim) - Plugin for Obsidian, written in Lua.
*   [IlyasYOY/obs.nvim (⭐84)](https://github.com/IlyasYOY/obs.nvim) - Your Obsidian notes at the speed of thought.
*   [jghauser/papis.nvim (⭐174)](https://github.com/jghauser/papis.nvim) - Manage your bibliography from within your favourite editor.
*   [Ostralyan/scribe.nvim (⭐25)](https://github.com/Ostralyan/scribe.nvim) - Take notes, easily.
*   [serenevoid/kiwi.nvim (⭐240)](https://github.com/serenevoid/kiwi.nvim) - A stripped down VimWiki with necessary features.
*   [backdround/global-note.nvim (⭐141)](https://github.com/backdround/global-note.nvim) - One global note in a floating window.
*   [2KAbhishek/tdo.nvim (⭐94)](https://github.com/2KAbhishek/tdo.nvim) - Fast and simple note taking.
*   [slugbyte/whip.nvim (⭐12)](http://github.com/slugbyte/whip.nvim) - A super fast minimal scratchpad management plugin, biew biew biew.
*   [y3owk1n/dotmd.nvim (⭐22)](https://github.com/y3owk1n/dotmd.nvim) - Managing notes, TODO's, journal entries, and your inbox, all with Markdown.
*   [athar-qadri/scratchpad.nvim (⭐12)](https://github.com/athar-qadri/scratchpad.nvim) - Effortlessly manage scratchpads within your favorite editor.
*   [echaya/neowiki.nvim (⭐113)](https://github.com/echaya/neowiki.nvim) - The modern vimwiki successor offering a minimal, intuitive workflow out of the box for note-taking and Getting Things Done (GTD).
*   [happyeric77/joplin.nvim (⭐5)](https://github.com/happyeric77/joplin.nvim) - Joplin notes utilities: tree browser, search, open, and Telescope integration.
*   [ymich9963/mdnotes.nvim (⭐3)](https://github.com/ymich9963/mdnotes.nvim) - Simple and improved Markdown note taking.
*   [nbeversl/urtext\_neovim (⭐1)](https://github.com/nbeversl/urtext_neovim) - An implementation of Urtext.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Utility

*   [necrom4/calcium.nvim (⭐22)](https://github.com/necrom4/calcium.nvim) - A powerful [`lua-lib-math`](https://www.lua.org/pil/18.html) in-buffer calculator with visual mode, functions and variable support.
*   [necrom4/convy.nvim (⭐17)](https://github.com/necrom4/convy.nvim) - Easily convert strings between various formats.
*   [gisketch/triforce.nvim (⭐207)](https://github.com/gisketch/triforce.nvim) - Gamified stat tracker with XP, levels, achievements, and activity heatmaps for your coding sessions with lualine integration.
*   [gaborvecsei/usage-tracker.nvim (⭐129)](https://github.com/gaborvecsei/usage-tracker.nvim) - Track your Neovim usage and visualize statistics easily.
*   [mateuszwieloch/automkdir.nvim (⭐30)](https://github.com/mateuszwieloch/automkdir.nvim) - Automatically create non-existent parent directories when writing a file.
*   [jghauser/mkdir.nvim (⭐233)](https://github.com/jghauser/mkdir.nvim) - Automatically create missing directories when saving files.
*   [matbme/JABS.nvim (⭐283)](https://github.com/matbme/JABS.nvim) - Pretty and minimal buffer switcher window.
*   [j-morano/buffer\_manager.nvim (⭐366)](https://github.com/j-morano/buffer_manager.nvim) - Add one or more buffers, reorder them, save them inside a file or just delete them very easily from a small floating window.
*   [hat0uma/prelive.nvim (⭐23)](https://github.com/hat0uma/prelive.nvim) - A simple luv-based development server with live reloading.
*   [hat0uma/doxygen-previewer.nvim (⭐8)](https://github.com/hat0uma/doxygen-previewer.nvim) - Live previewing of Doxygen documentation.
*   [code-biscuits/nvim-biscuits (⭐319)](https://github.com/code-biscuits/nvim-biscuits) - A Neovim port of Assorted Biscuits. Ends up with more supported languages too.
*   [kazhala/close-buffers.nvim (⭐172)](https://github.com/kazhala/close-buffers.nvim) - Delete multiple Vim buffers based on different conditions.
*   [rktjmp/paperplanes.nvim (⭐98)](https://github.com/rktjmp/paperplanes.nvim) - Post selections or buffers to online paste bins.
*   [rcarriga/nvim-notify (⭐3.5k)](https://github.com/rcarriga/nvim-notify) - A fancy, configurable, notification manager.
*   [nvim-mini/mini.nvim#mini.notify (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-notify.md) - Module of `mini.nvim` to show one or more highlighted notifications in a single window. Provides maker of `vim.notify()` implementation and sets up automated LSP progress updates.
*   [folke/noice.nvim (⭐5.5k)](https://github.com/folke/noice.nvim) - Highly experimental plugin that completely replaces the UI for messages, cmdline and the popupmenu.
*   [sQVe/bufignore.nvim (⭐17)](https://github.com/sQVe/bufignore.nvim) - Unlist hidden buffers matching specified ignore sources.
*   [saifulapm/commasemi.nvim (⭐12)](https://github.com/saifulapm/commasemi.nvim) - Toggle comma and semicolon.
*   [jghauser/fold-cycle.nvim (⭐91)](https://github.com/jghauser/fold-cycle.nvim) - Cycle folds open or closed.
*   [rgroli/other.nvim (⭐480)](https://github.com/rgroli/other.nvim) - Open alternative files for the current buffer.
*   [toppair/reach.nvim (⭐245)](https://github.com/toppair/reach.nvim) - Buffer, mark, tabpage switcher.
*   [axieax/urlview.nvim (⭐271)](https://github.com/axieax/urlview.nvim) - Browse all URLs in the current buffer.
*   [cxwx/lazyUrlUpdate.nvim (⭐3)](https://github.com/cxwx/lazyUrlUpdate.nvim) - Update plugin under cursor by `lazy.nvim`.
*   [nkakouros-original/numbers.nvim (⭐38)](https://github.com/nkakouros-original/numbers.nvim) - Toggle relativenumber whenever it makes sense.
*   [ghillb/cybu.nvim (⭐320)](https://github.com/ghillb/cybu.nvim) - Displays a notification window with context when cycling buffers.
*   [sontungexpt/url-open (⭐105)](https://github.com/sontungexpt/url-open) - Open URLs under the cursor and create highlight effects for them.
*   [crusj/bookmarks.nvim (⭐242)](https://github.com/crusj/bookmarks.nvim) - Remember file locations and sort by time and frequency.
*   [m-demare/attempt.nvim (⭐92)](https://github.com/m-demare/attempt.nvim) - Manage and run temporary buffers.
*   [kevinhwang91/nvim-ufo (⭐2.8k)](https://github.com/kevinhwang91/nvim-ufo) - Ultra fold with modern looking and performance boosting.
*   [sitiom/nvim-numbertoggle (⭐210)](https://github.com/sitiom/nvim-numbertoggle) - Neovim plugin to automatically toggle between relative and absolute line numbers.
*   [nguyenvukhang/nvim-toggler (⭐190)](https://github.com/nguyenvukhang/nvim-toggler) - Invert text, such as toggling between `true` and `false`.
*   [CosmicNvim/cosmic-ui (⭐170)](https://github.com/CosmicNvim/cosmic-ui) - Cosmic-UI is a simple wrapper around specific Vim functionality. Built in order to provide a quick and easy way to create a Cosmic UI experience with Neovim!
*   [jbyuki/instant.nvim (⭐1.4k)](https://github.com/jbyuki/instant.nvim) - A collaborative editing plugin written in Lua with no dependencies.
*   [zbirenbaum/neodim (⭐338)](https://github.com/zbirenbaum/neodim) - Dimming the highlights of unused functions, variables, parameters, and more.
*   [bfredl/nvim-miniyank (⭐239)](https://github.com/bfredl/nvim-miniyank) - The killring-alike plugin with no default mappings.
*   [chrisgrieser/nvim-genghis (⭐219)](https://github.com/chrisgrieser/nvim-genghis) - Convenience file operations, written in Lua.
*   [chrisgrieser/nvim-recorder (⭐272)](https://github.com/chrisgrieser/nvim-recorder) - Simplifying and improving how you interact with macros.
*   [figsoda/nix-develop.nvim (⭐63)](https://github.com/figsoda/nix-develop.nvim) - Run `nix develop` without restarting Neovim.
*   [yaocccc/nvim-foldsign (⭐39)](https://github.com/yaocccc/nvim-foldsign) - Display folds on sign column.
*   [tenxsoydev/nx.nvim (⭐32)](https://github.com/tenxsoydev/nx.nvim) - Neovim API utility wrapper for more convenience with Lua keymaps, highlights, autocommands and options.
*   [zdcthomas/yop.nvim (⭐84)](https://github.com/zdcthomas/yop.nvim) - Easily create your own operators (like `d` and `y`).
*   [mluders/comfy-line-numbers.nvim (⭐105)](https://github.com/mluders/comfy-line-numbers.nvim) - Limits relative numbers to only show left-hand digits on the keyboard.
*   [cpea2506/relative-toggle.nvim (⭐34)](https://github.com/cpea2506/relative-toggle.nvim) - Toggles smoothly between number and relative numbers, supporting various number combinations, highly customizable.
*   [chrisgrieser/nvim-early-retirement (⭐244)](https://github.com/chrisgrieser/nvim-early-retirement) - Send buffers into early retirement by automatically closing them after x minutes of inactivity.
*   [axkirillov/hbac.nvim (⭐219)](https://github.com/axkirillov/hbac.nvim) - Automatically close buffers you are not working on.
*   [ragnarok22/whereami.nvim (⭐17)](https://github.com/ragnarok22/whereami.nvim) - Test your VPN by getting you current location.
*   [ecthelionvi/NeoComposer.nvim (⭐422)](https://github.com/ecthelionvi/NeoComposer.nvim) - Simplify macro management, enhance productivity, and create harmonious workflows.
*   [LukasPietzschmann/telescope-tabs (⭐281)](https://github.com/LukasPietzschmann/telescope-tabs) - Quickly navigate between tabs using telescope.
*   [RutaTang/compter.nvim (⭐29)](https://github.com/RutaTang/compter.nvim) - Power and extend the ability of `<C-a>` and `<C-x>` with customized patterns.
*   [yagiziskirik/AirSupport.nvim (⭐10)](https://github.com/yagiziskirik/AirSupport.nvim) - Searchable reminder window for your custom shortcuts and commands.
*   [aPeoplesCalendar/apc.nvim (⭐23)](https://github.com/aPeoplesCalendar/apc.nvim) - "On this day" style calendar, which provides information about worldwide history of working class movements and liberation struggles.
*   [subnut/nvim-ghost.nvim (⭐192)](https://github.com/subnut/nvim-ghost.nvim) - GhostText support with zero dependencies.
*   [malbertzard/inline-fold.nvim (⭐88)](https://github.com/malbertzard/inline-fold.nvim) - Hide certain elements inline like long CSS classes or `href` content.
*   [chrisgrieser/nvim-origami (⭐434)](https://github.com/chrisgrieser/nvim-origami) - Fold with relentless elegance.
*   [LintaoAmons/scratch.nvim (⭐269)](https://github.com/LintaoAmons/scratch.nvim) - Create and manage scratch files.
*   [0xJohnnyboy/scretch.nvim (⭐34)](https://github.com/0xJohnnyboy/scretch.nvim) - Create and manage scratch files, scratch templates, with picker integrations.
*   [yutkat/confirm-quit.nvim (⭐34)](https://github.com/yutkat/confirm-quit.nvim) - Confirm before quitting Neovim.
*   [bgaillard/readonly.nvim (⭐20)](https://github.com/bgaillard/readonly.nvim) - Secure edition of files containing sensible / secret information, passwords, API keys, SSH keys, etc.
*   [ariel-frischer/bmessages.nvim (⭐58)](https://github.com/ariel-frischer/bmessages.nvim) - Replace the default :messages window with a configurable, auto-updating buffer.
*   [backdround/tabscope.nvim (⭐56)](https://github.com/backdround/tabscope.nvim) - Make tab-local buffers.
*   [linrongbin16/gentags.nvim (⭐23)](https://github.com/linrongbin16/gentags.nvim) - The tags generator/management for old school vimers.
*   [mcauley-penney/visual-whitespace.nvim (⭐406)](https://github.com/mcauley-penney/visual-whitespace.nvim) - See whitespace characters in Visual selections, like VSCode.
*   [Zeioth/distroupdate.nvim (⭐10)](https://github.com/Zeioth/distroupdate.nvim) - Distro agnostic updater to get the latest changes from the Git repository of your config.
*   [SUSTech-data/neopyter (⭐147)](https://github.com/SUSTech-data/neopyter) - The bridge between Neovim and Jupyter lab, edit in Neovim and preview/run in Jupyter Lab.
*   [terje/simctl.nvim (⭐39)](https://github.com/terje/simctl.nvim) - Interact with iOS Simulators.
*   [mistricky/codesnap.nvim (⭐904)](https://github.com/mistricky/codesnap.nvim) - Snapshot plugin with rich features that can make pretty code snapshots.
*   [AlejandroSuero/freeze-code.nvim (⭐31)](https://github.com/AlejandroSuero/freeze-code.nvim) - Code screenshot plugin that makes use of [freeze (⭐4.2k)](https://github.com/charmbracelet/freeze) inside the editor, it lets you **copy** the generated image to **paste it anywhere**.
*   [ysmb-wtsg/in-and-out.nvim (⭐83)](https://github.com/ysmb-wtsg/in-and-out.nvim) - Quick navigation in and out of surrounding characters.
*   [ChuufMaster/buffer-vacuum (⭐13)](https://github.com/ChuufMaster/buffer-vacuum) - Set a maximum number of buffers to keep open and intelligently delete the oldest buffers over the maximum.
*   [mong8se/buffish.nvim (⭐5)](https://github.com/mong8se/buffish.nvim) - A buffer switcher in the spirit of dirvish or vinegar.
*   [niuiic/todo.nvim (⭐15)](https://github.com/niuiic/todo.nvim) - Simple but powerful todo manager based on text.
*   [SunnyTamang/pendulum.nvim (⭐14)](https://github.com/SunnyTamang/pendulum.nvim) - Simple timer for creating time based productive sessions for coders, competitive programmers, developers etc.
*   [ptdewey/pendulum-nvim (⭐105)](https://github.com/ptdewey/pendulum-nvim) - Track time spent coding and glean insights through on-demand time reports.
*   [rlychrisg/truncateline.nvim (⭐20)](https://github.com/rlychrisg/truncateline.nvim) - Truncate long lines to keep track of where you are when the start gets lost off the left side of the screen.
*   [ellisonleao/dotenv.nvim (⭐53)](https://github.com/ellisonleao/dotenv.nvim) - Minimalist .env support.
*   [dzfrias/arena.nvim (⭐102)](https://github.com/dzfrias/arena.nvim) - A smart (frecency-based) buffer switcher.
*   [MisanthropicBit/decipher.nvim (⭐43)](https://github.com/MisanthropicBit/decipher.nvim) - Encode and decode text using various codecs such as base64.
*   [philosofonusus/ecolog.nvim (⭐163)](https://github.com/philosofonusus/ecolog.nvim) - Sophisticated all-in-one toolkit to work with `.env` files and environment variables.
*   [theKnightsOfRohan/hexer.nvim (⭐10)](https://github.com/theKnightsOfRohan/hexer.nvim) - Easily convert between binary representations without a conversion table.
*   [josephburgess/nvumi (⭐54)](https://github.com/josephburgess/nvumi) - Natural language calculator in a scratch buffer.
*   [redoxahmii/json-to-types.nvim (⭐53)](https://github.com/redoxahmii/json-to-types.nvim) - Convert JSON objects to type definitions for multiple languages.
*   [ovk/endec.nvim (⭐32)](https://github.com/ovk/endec.nvim) - Encode, decode and re-encode text using Base64, Base64URL and URL (percent) encodings.
*   [kiyoon/jupynium.nvim (⭐717)](https://github.com/kiyoon/jupynium.nvim) - Selenium-automated Jupyter Notebook that is synchronised with Neovim in real-time.
*   [y3owk1n/time-machine.nvim (⭐66)](https://github.com/y3owk1n/time-machine.nvim) - Take control of your edit history with an interactive timeline, diff previews, taggings, live reloading trees and cleanup functions.
*   [BibekBhusal0/bufstack.nvim (⭐4)](https://github.com/BibekBhusal0/bufstack.nvim) - Track recently visited buffers and reopen recently closed buffers.
*   [OXY2DEV/ui.nvim (⭐150)](https://github.com/OXY2DEV/ui.nvim) - A blueprint/template/guide for customizing the UI.
*   [athar-qadri/weather.nvim (⭐13)](https://github.com/athar-qadri/weather.nvim) - Realtime Weather and Earthquake alerts with support for lualine integration (no api key required).
*   [penaz91/MiniDYM (⭐3)](https://github.com/Penaz91/MiniDYM) - A very small "Did you mean" plugin, suggesting files the user might have wanted to open instead of creating a new one.
*   [attilarepka/header.nvim (⭐32)](https://github.com/attilarepka/header.nvim) - Add or update copyright and license headers in any source file.
*   [Owen-Dechow/videre.nvim (⭐129)](https://github.com/Owen-Dechow/videre.nvim) - Explore JSON, YAML, and TOML files as nested unit/node-based graphical representations.
*   [mahyarmirrashed/famous-quotes.nvim (⭐3)](https://github.com/mahyarmirrashed/famous-quotes.nvim) - Get famous quotes from history to display on startup.
*   [iquzart/toggleword.nvim (⭐5)](https://github.com/iquzart/toggleword.nvim) - Toggle between common code keywords under the cursor such as true ⇄ false, on ⇄ off, enabled ⇄ disabled, and dev ⇄ prod.
*   [piersolenski/brewfile.nvim (⭐18)](https://github.com/piersolenski/brewfile.nvim) - Manage your [Homebrew](https://brew.sh/) [Brewfile](https://docs.brew.sh/Brew-Bundle-and-Brewfile).
*   [ravsii/timers.nvim (⭐13)](https://github.com/ravsii/timers.nvim) - Timer manager, a clean Lua API, supporting multiple timers, persistence, UI, and plugin integrations.
*   [francescarpi/buffon.nvim (⭐29)](https://github.com/francescarpi/buffon.nvim) - Buffers navigation, reorganize and close.
*   [ahkohd/buffer-sticks.nvim (⭐67)](https://github.com/ahkohd/buffer-sticks.nvim) - Cosmetic buffers indicator & picker.
*   [gpanders/nvim-moonwalk (⭐77)](https://github.com/gpanders/nvim-moonwalk) - Use any language that compiles to Lua anywhere in your Neovim configuration.
*   [markgandolfo/lightswitch.nvim (⭐22)](https://github.com/markgandolfo/lightswitch.nvim) - Toggle various options using the `nui.nvim` library.
*   [johannww/tts.nvim (⭐16)](https://github.com/johannww/tts.nvim) - Text to speech tool based on the Microsoft Edge online services.
*   [doctorfree/cheatsheet.nvim (⭐65)](https://github.com/doctorfree/cheatsheet.nvim) - Searchable cheatsheet.
*   [gaborvecsei/cryptoprice.nvim (⭐22)](https://github.com/gaborvecsei/cryptoprice.nvim) - Check the price of the defined cryptocurrencies.
*   [nxhung2304/lastplace.nvim (⭐21)](https://github.com/nxhung2304/lastplace.nvim) - Intelligently restore your cursor position when reopening files.
*   [wsdjeg/mru.nvim (⭐7)](https://github.com/wsdjeg/mru.nvim) - Manage and display your Most Recently Used (MRU) files.
*   [gruvw/strudel.nvim (⭐337)](https://github.com/gruvw/strudel.nvim) - Live coding controller for [strudel](https://strudel.cc).
*   [wsdjeg/ctags.nvim (⭐7)](https://github.com/wsdjeg/ctags.nvim) - Generate tags files and update tags option automatically.
*   [QuentinGruber/pomodoro.nvim (⭐45)](https://github.com/QuentinGruber/pomodoro.nvim) - Use the Pomodoro Technique with built-in session tracking and break reminders.
*   [leo-alvarenga/quoth.nvim (⭐3)](https://github.com/leo-alvarenga/quoth.nvim) - A lightweight, configurable random quote provider with lazy loading, custom tables, and filters.

### CSV Files

*   [VidocqH/data-viewer.nvim (⭐121)](https://github.com/VidocqH/data-viewer.nvim) - Provide a simple table view to inspect data files such as `csv`, `tsv`.
*   [theKnightsOfRohan/csvlens.nvim (⭐37)](https://github.com/theKnightsOfRohan/csvlens.nvim) - A port of [YS-L/csvlens (⭐3.3k)](https://github.com/YS-L/csvlens), for easy previewing of tabular data.
*   [emmanueltouzery/decisive.nvim (⭐122)](https://github.com/emmanueltouzery/decisive.nvim) - View and edit CSV files with ease and speed.
*   [hat0uma/csvview.nvim (⭐480)](https://github.com/hat0uma/csvview.nvim) - An asynchronous CSV/TSV table viewer with real-time updates, configurable comments and delimiters, and multiple display modes.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Animation

*   [LuxVim/nvim-luxmotion (⭐36)](https://github.com/LuxVim/nvim-luxmotion) - Smooth, high‑performance motion & scrolling animations — 60fps fluid cursor moves, word jumps, and viewport scrolling, all in one.
*   [sphamba/smear-cursor.nvim (⭐1.5k)](https://github.com/sphamba/smear-cursor.nvim) - Animate the cursor with a smear effect in all terminals. Inspired by Neovide's animated cursor.
*   [nvim-mini/mini.nvim#mini.animate (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-animate.md) - Module of `mini.nvim` to add out of the box animations for common built-in actions (cursor movement, scroll, resize, window open/close).
*   [rachartier/tiny-glimmer.nvim (⭐387)](https://github.com/rachartier/tiny-glimmer.nvim/) - Adds subtle animations to various operations.
*   [y3owk1n/undo-glow.nvim (⭐68)](https://github.com/y3owk1n/undo-glow.nvim/) - Animated glow/highlight effects for Neovim operations (undo, redo, yank, paste, etc.) with fully customizable animations and appearance.
*   [gen740/SmoothCursor.nvim (⭐386)](https://github.com/gen740/SmoothCursor.nvim) - Add fancy sub-cursor to signcolumn to show your scroll or jump direction.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Terminal Integration

*   [LuxVim/nvim-luxterm (⭐9)](https://github.com/LuxVim/nvim-luxterm) - A floating-window terminal session manager, offering elegant multi-terminal organization, live previews, and intuitive navigation with modern UI design. Manage, switch, and customize multiple terminals effortlessly.
*   [waiting-for-dev/ergoterm.nvim (⭐92)](https://github.com/waiting-for-dev/ergoterm.nvim) - Seamless terminal workflow integration with smart picker-based terminal selection, flexible text sending and persistent configuration.
*   [ingur/floatty.nvim (⭐20)](https://github.com/ingur/floatty.nvim) - A tiny (<200 LOC) but highly customizable floating terminal manager.
*   [imranzero/multiterm.nvim (⭐11)](https://github.com/imranZERO/multiterm.nvim) - Effortlessly manage multiple floating terminal windows.
*   [Dan7h3x/neaterm.nvim (⭐58)](https://github.com/Dan7h3x/neaterm.nvim) - A little smart terminal/REPL manager with awesome features.
*   [nikvdp/neomux (⭐369)](https://github.com/nikvdp/neomux) - Control Neovim from shells running inside Neovim.
*   [willothy/flatten.nvim (⭐685)](https://github.com/willothy/flatten.nvim) - Open files from terminal buffers in your current Neovim instance instead of launching a nested instance.
*   [akinsho/toggleterm.nvim (⭐5.3k)](https://github.com/akinsho/toggleterm.nvim) - Easily manage multiple terminal windows.
*   [norcalli/nvim-terminal.lua (⭐270)](https://github.com/norcalli/nvim-terminal.lua) - A high performance filetype mode which leverages conceal and highlights your buffer with the correct color codes.
*   [numToStr/FTerm.nvim (⭐797)](https://github.com/numToStr/FTerm.nvim) - No nonsense floating terminal written in Lua.
*   [jghauser/kitty-runner.nvim (⭐106)](https://github.com/jghauser/kitty-runner.nvim) - Poor man's REPL. Easily send buffer lines and commands to a kitty terminal.
*   [jlesquembre/nterm.nvim (⭐57)](https://github.com/jlesquembre/nterm.nvim) - Interact with the terminal, with notifications.
*   [s1n7ax/nvim-terminal (⭐121)](https://github.com/s1n7ax/nvim-terminal) - A simple & easy to use multi-terminal plugin.
*   [logicmagix/tide42 (⭐23)](https://github.com/logicmagix/tide42) - A fully integrated terminal IDE built on Neovim, tmux, and scriptable workflows.
*   [samjwill/nvim-unception (⭐235)](https://github.com/samjwill/nvim-unception) - Automatic unnesting of Neovim sessions started from terminal buffers.
*   [kassio/neoterm (⭐1.3k)](https://github.com/kassio/neoterm) - Wrapper of some `:terminal` functions.
*   [nyngwang/NeoTerm.lua (⭐67)](https://github.com/nyngwang/NeoTerm.lua) - Attach a terminal for each **buffer**, now with stable toggle and astonishing cursor restoring.
*   [idanarye/nvim-channelot (⭐7)](https://github.com/idanarye/nvim-channelot) - Operate Neovim jobs from Lua coroutines.
*   [chomosuke/term-edit.nvim (⭐207)](https://github.com/chomosuke/term-edit.nvim) - Allowing you to edit your command in the terminal just like any other buffer.
*   [mikesmithgh/kitty-scrollback.nvim (⭐784)](https://github.com/mikesmithgh/kitty-scrollback.nvim) - Open your Kitty scrollback buffer. Ameowzing.
*   [niuiic/terminal.nvim (⭐19)](https://github.com/niuiic/terminal.nvim) - Manage terminal as buffer, multiple terminals support.
*   [NeViRAIDE/nekifoch.nvim (⭐16)](https://github.com/NeViRAIDE/nekifoch.nvim) - Managing Kitty terminal font settings.
*   [2KAbhishek/termim.nvim (⭐79)](https://github.com/2KAbhishek/termim.nvim/) - Neovim Terminal, Improved.
*   [samharju/yeet.nvim (⭐118)](https://github.com/samharju/yeet.nvim) - Run shell commands in terminal buffers or tmux panes.
*   [isak102/ghostty.nvim (⭐44)](https://github.com/isak102/ghostty.nvim) - Automatically validate your Ghostty configuration on save.
*   [laktak/tome (⭐144)](https://github.com/laktak/tome) - Interactive Script playbooks for your terminal (optionally with Tmux).
*   [Axot017/multiterm.nvim (⭐5)](https://github.com/Axot017/multiterm.nvim) - A lightweight manager of multiple terminal instances with key bindings.
*   [da-moon/telescope-toggleterm.nvim (⭐40)](https://github.com/da-moon/telescope-toggleterm.nvim) - Telescope picker for terminal buffers.
*   [benoror/gpg.nvim (⭐18)](https://github.com/benoror/gpg.nvim) - Edit GPG encrypted files symmetrically.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Debugging

*   [mfussenegger/nvim-dap (⭐6.8k)](https://github.com/mfussenegger/nvim-dap) - Debug Adapter Protocol client implementation.
*   [sakhnik/nvim-gdb (⭐769)](https://github.com/sakhnik/nvim-gdb) - Thin wrapper for GDB, LLDB, PDB/PDB++ and BashDB.
*   [rcarriga/nvim-dap-ui (⭐3.2k)](https://github.com/rcarriga/nvim-dap-ui) - A UI for nvim-dap.
*   [pocco81/dap-buddy.nvim (⭐400)](https://github.com/pocco81/dap-buddy.nvim) - Manage several debuggers for nvim-dap.
*   [Weissle/persistent-breakpoints.nvim (⭐244)](https://github.com/Weissle/persistent-breakpoints.nvim) - Persistent breakpoints for nvim-dap.
*   [ofirgall/goto-breakpoints.nvim (⭐33)](https://github.com/ofirgall/goto-breakpoints.nvim) - Cycle between breakpoints for nvim-dap.
*   [andrewferrier/debugprint.nvim (⭐503)](https://github.com/andrewferrier/debugprint.nvim) - Debugging the print() way.
*   [t-troebst/perfanno.nvim (⭐337)](https://github.com/t-troebst/perfanno.nvim) - Annotate your code with callgraph profiling data. Native support for perf, flamegraph and the LuaJit profiler.
*   [niuiic/dap-utils (⭐40)](https://github.com/niuiic/dap-utils.nvim) - Utilities to provide a better experience for using nvim-dap.
*   [theHamsta/nvim-dap-virtual-text (⭐1k)](https://github.com/theHamsta/nvim-dap-virtual-text) - Virtual text support for nvim-dap.
*   [chrisgrieser/nvim-chainsaw (⭐132)](https://github.com/chrisgrieser/nvim-chainsaw) - Speed up log creation. Creates various kinds of language-specific log statements, like logs of variables, assertions, or time-measuring.
*   [Willem-J-an/visidata.nvim (⭐34)](https://github.com/Willem-J-an/visidata.nvim) - Render Pandas dataframes in `nvim-dap` using the power of visidata.
*   [igorlfs/nvim-dap-view (⭐570)](https://github.com/igorlfs/nvim-dap-view) - A modern, minimalistic UI for nvim-dap.
*   [Carcuis/dap-breakpoints.nvim (⭐17)](https://github.com/Carcuis/dap-breakpoints.nvim) - Manage and create advanced breakpoints with virtual text and popup reveal for nvim-dap.
*   [ravsii/nvim-dap-envfile (⭐12)](https://github.com/ravsii/nvim-dap-envfile) - Automatic `envFile` support for nvim-dap.
*   [fschaal/azfunc.nvim (⭐3)](https://github.com/fschaal/azfunc.nvim) - Seamlessly debug Azure Functions with automatic DAP integration.

### Quickfix

*   [kevinhwang91/nvim-bqf (⭐2k)](https://github.com/kevinhwang91/nvim-bqf) - The goal of nvim-bqf is to make Neovim's quickfix window better.
*   [yorickpeterse/nvim-pqf (⭐177)](https://github.com/yorickpeterse/nvim-pqf) - Prettier quickfix/location list windows.
*   [ashfinal/qfview.nvim (⭐54)](https://github.com/ashfinal/qfview.nvim) - Pretty quickfix/location view with consistent path-shorten and folding.
*   [niuiic/quickfix.nvim (⭐12)](https://github.com/niuiic/quickfix.nvim) - Extended functionality for quickfix, including store, restore, make, remove, etc.
*   [stevearc/quicker.nvim (⭐874)](https://github.com/stevearc/quicker.nvim) - Improved quickfix UI and editable quickfix buffer.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Deployment

*   [OscarCreator/rsync.nvim (⭐98)](https://github.com/OscarCreator/rsync.nvim) - Automatically sync up/down project to a remote with rsync.
*   [sachinsenal0x64/hot.nvim (⭐28)](https://github.com/sachinsenal0x64/hot.nvim) - A hot reloader that works with any programming language.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Test

*   [David-Kunz/jester (⭐213)](https://github.com/David-Kunz/jester) - Easily run and debug Jest tests.
*   [klen/nvim-test (⭐197)](https://github.com/klen/nvim-test) - A Neovim wrapper for running tests.
*   [nvim-neotest/neotest (⭐3k)](https://github.com/nvim-neotest/neotest) - An extensible framework for interacting with tests within Neovim.
*   [andythigpen/nvim-coverage (⭐415)](https://github.com/andythigpen/nvim-coverage) - Displays coverage information in the sign column.
*   [quolpr/quicktest.nvim (⭐100)](https://github.com/quolpr/quicktest.nvim) - Run your tests in split window or popup with live feedback.
*   [zkucekovic/tdd.nvim (⭐6)](https://github.com/zkucekovic/tdd.nvim) - Opens or creates the matching PHPUnit test file for a given class, based on PSR-4 namespace mappings.
*   [nvim-neotest/neotest-jest (⭐145)](https://github.com/nvim-neotest/neotest-jest) - Neotest adapter for running Jest tests.
*   [MisanthropicBit/neotest-busted (⭐15)](https://github.com/MisanthropicBit/neotest-busted) - Neotest adapter for running busted tests using Neovim as a Lua interpreter.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Code Runner

*   [michaelb/sniprun (⭐1.7k)](https://github.com/michaelb/sniprun) - Run parts of code of any language directly from Neovim.
*   [CRAG666/code\_runner.nvim (⭐663)](https://github.com/CRAG666/code_runner.nvim) - The best code runner you could have, with super powers.
*   [is0n/jaq-nvim (⭐178)](https://github.com/is0n/jaq-nvim) - Just Another Quickrun Plugin in Lua.
*   [jedrzejboczar/toggletasks.nvim (⭐158)](https://github.com/jedrzejboczar/toggletasks.nvim) - Task runner with JSON/YAML configs, using toggleterm.nvim and telescope.nvim.
*   [EthanJWright/vs-tasks.nvim (⭐207)](https://github.com/EthanJWright/vs-tasks.nvim) - Run and manage project jobs, supporting VSCode's `tasks.json` spec.
*   [stevearc/overseer.nvim (⭐1.8k)](https://github.com/stevearc/overseer.nvim) - A task runner and job management plugin.
*   [desdic/greyjoy.nvim (⭐31)](https://github.com/desdic/greyjoy.nvim) - A modular task runner for Makefiles, VSCode tasks, kitchen etc.
*   [Shatur/neovim-tasks (⭐124)](https://github.com/Shatur/neovim-tasks) - A stateful task manager focused on integration with build systems.
*   [krady21/compiler-explorer.nvim (⭐178)](https://github.com/krady21/compiler-explorer.nvim) - Asynchronous compilation using the [compiler-explorer](https://godbolt.org/) REST API.
*   [milanglacier/yarepl.nvim (⭐241)](https://github.com/milanglacier/yarepl.nvim) - Yet Another REPL, flexible, supporting multiple paradigms to interact with REPLs, and native dot repeat without other dependencies.
*   [Vigemus/iron.nvim (⭐1.3k)](https://github.com/Vigemus/iron.nvim) - Interactive REPLs of over 30 languages embedded.
*   [Civitasv/cmake-tools.nvim (⭐510)](https://github.com/Civitasv/cmake-tools.nvim) - CMake integration.
*   [idanarye/nvim-moonicipal (⭐19)](https://github.com/idanarye/nvim-moonicipal) - Task runner with focus on rapidly changing personal tasks.
*   [MarcHamamji/runner.nvim (⭐52)](https://github.com/MarcHamamji/runner.nvim) - A customizable Lua code runner.
*   [google/executor.nvim (⭐155)](https://github.com/google/executor.nvim) - Allows you to run command line tasks in the background and be notified of results.
*   [Zeioth/compiler.nvim (⭐637)](https://github.com/Zeioth/compiler.nvim) - Compiler for building and running your code without having to configure anything.
*   [Zeioth/makeit.nvim (⭐42)](https://github.com/Zeioth/makeit.nvim) - Makefile runner based on overseer.
*   [jaytyrrell13/static.nvim (⭐11)](https://github.com/jaytyrrell13/static.nvim) - Run static site generator commands.
*   [dasupradyumna/launch.nvim (⭐51)](https://github.com/dasupradyumna/launch.nvim) - A simple and quick task launcher which allows dynamically configuring tasks on the fly, with optional support for debugging.
*   [benlubas/molten-nvim (⭐1.1k)](https://github.com/benlubas/molten-nvim) - Enables running code chunks via the Jupyter kernel. Output (including image output) is rendered in a floating window below the code.
*   [pianocomposer321/officer.nvim (⭐22)](https://github.com/pianocomposer321/officer.nvim) - Like dispatch.vim but using overseer.nvim.
*   [speelbarrow/spLauncher.nvim (⭐7)](https://github.com/speelbarrow/spLauncher.nvim) - For launching tasks, I guess.
*   [al1-ce/just.nvim (⭐43)](https://github.com/al1-ce/just.nvim) - Task runner for justfiles.
*   [niuiic/task.nvim (⭐6)](https://github.com/niuiic/task.nvim) - Another highly configurable task manager that enables seamless interaction with tasks.
*   [chrisgrieser/nvim-justice (⭐34)](https://github.com/chrisgrieser/nvim-justice) - Lightweight integration of the `just` task runner.
*   [pewpewnor/pilot.nvim (⭐5)](https://github.com/pewpewnor/pilot.nvim) - Run your projects and files quickly with keybindings, and configure how to run them on the fly.
*   [ok97465/ipybridge.nvim (⭐8)](https://github.com/ok97465/ipybridge.nvim) - Run Python code, execute Jupyter cells, debug, and explore variables.
*   [wsdjeg/code-runner.nvim (⭐5)](https://github.com/wsdjeg/code-runner.nvim) - Async code runner with range support.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Neovim Lua Development

*   [folke/lazydev.nvim (⭐1.4k)](https://github.com/folke/lazydev.nvim) - Faster LuaLS setup.
*   [nvim-neorocks/luarocks-tag-release (⭐53)](https://github.com/nvim-neorocks/luarocks-tag-release) - A GitHub action that publishes your Neovim plugins to LuaRocks.
*   [svermeulen/vimpeccable (⭐349)](https://github.com/svermeulen/vimpeccable) - Commands to help write your .vimrc in Lua or any Lua based language.
*   [nvim-lua/plenary.nvim (⭐3.3k)](https://github.com/nvim-lua/plenary.nvim) - Plenary: full; complete; entire; absolute; unqualified. All the Lua functions I don't want to write twice.
*   [tjdevries/vlog.nvim (⭐141)](https://github.com/tjdevries/vlog.nvim) - Single file, no dependency, easy copy & paste log file to add to your Neovim Lua plugins.
*   [bfredl/nvim-luadev (⭐282)](https://github.com/bfredl/nvim-luadev) - REPL/debug console Lua plugins. The `:Luadev` command will open an scratch window which will show output from executing Lua code.
*   [jbyuki/one-small-step-for-vimkind (⭐530)](https://github.com/jbyuki/one-small-step-for-vimkind) - An adapter for the Neovim Lua language. It allows you to debug any Lua code running in a Neovim instance (A Lua plugin that can debug Neovim Lua plugins).
*   [kkharji/sqlite.lua (⭐562)](https://github.com/kkharji/sqlite.lua) - SQLite/LuaJIT binding for Lua and Neovim.
*   [MunifTanjim/nui.nvim (⭐2k)](https://github.com/MunifTanjim/nui.nvim) - UI Component Library.
*   [nvim-mini/mini.nvim#mini.doc (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-doc.md) - Module of `mini.nvim` for generation of help files from EmmyLua-like annotations. Allows flexible customization of output via hook functions.
*   [milisims/nvim-luaref (⭐126)](https://github.com/milisims/nvim-luaref) - A reference for builtin Lua functions.
*   [nvim-mini/mini.nvim#mini.test (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-test.md) - Module of `mini.nvim` with framework for writing extensive Neovim plugin tests. Supports hierarchical tests, hooks, parametrization, filtering, screen tests, "busted-style" emulation, customizable reporters, and more.
*   [ray-x/guihua.lua (⭐182)](https://github.com/ray-x/guihua.lua) - A Lua UI library. Includes a fzy search bar, list view and tree view modules.
*   [anuvyklack/animation.nvim (⭐47)](https://github.com/anuvyklack/animation.nvim) - Create animations.
*   [nfrid/treesitter-utils (⭐9)](https://github.com/nfrid/treesitter-utils) - Some useful Tree-sitter methods.
*   [svermeulen/nvim-lusc (⭐16)](https://github.com/svermeulen/nvim-lusc) - Adds support for Structured Async/Concurrency in Lua.
*   [gregorias/coop.nvim (⭐140)](https://github.com/gregorias/coop.nvim) - Structured concurrency with Lua coroutines.
*   [CWood-sdf/banana.nvim (⭐153)](https://github.com/CWood-sdf/banana.nvim) - HTML renderer for plugin UIs.
*   [OXY2DEV/helpview.nvim (⭐378)](https://github.com/OXY2DEV/helpview.nvim) - A hackable & fancy `vimdoc/help` file viewer.
*   [niuiic/omega.nvim (⭐6)](https://github.com/niuiic/omega.nvim) - Missing functions for Lua plugin development.
*   [2KAbhishek/utils.nvim (⭐10)](https://github.com/2KAbhishek/utils.nvim) - Powerful utilities to speed up plugin development.
*   [YaroSpace/lua-console.nvim (⭐85)](https://github.com/YaroSpace/lua-console.nvim) - A handy scratch pad / REPL / debug console for Lua development and Neovim exploration and configuration.
*   [DrKJeff16/wezterm-types (⭐142)](https://github.com/DrKJeff16/wezterm-types) - WezTerm config type annotations for Lua Language Server.
*   [chrisgve/databox.nvim (⭐12)](https://github.com/chrisgve/databox.nvim) - Encrypted storage for Lua tables using [age (⭐20k)](https://github.com/FiloSottile/age) or compatible encryption tools for cryptographic safety.
*   [BirdeeHub/lze (⭐89)](https://github.com/BirdeeHub/lze) - A lazy-loading library for Neovim plugins.
*   [lumen-oss/lz.n (⭐228)](https://github.com/lumen-oss/lz.n) - A simple lazy loading library for Neovim plugins.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Fennel

*   [aileot/nvim-thyme (⭐32)](https://github.com/aileot/nvim-thyme) - Zero-overhead Fennel JIT compiler with safety rollbacks and [parinfer-rust (⭐604)](https://github.com/eraserhd/parinfer-rust) integration.
*   [Olical/aniseed (⭐645)](https://github.com/Olical/aniseed) - Configure and extend Neovim with Fennel (Lisp to Lua).
*   [Olical/nfnl (⭐329)](https://github.com/Olical/nfnl) - Streamlined successor to Aniseed, compiling Fennel to Lua on file write.
*   [Olical/conjure (⭐2k)](https://github.com/Olical/conjure) - Interactive evaluation (Clojure, Fennel, Janet, Racket, Hy, MIT Scheme, Guile).
*   [rktjmp/hotpot.nvim (⭐385)](https://github.com/rktjmp/hotpot.nvim) - Seamless, transparent Fennel inside Neovim.
*   [udayvir-singh/tangerine.nvim (⭐226)](https://github.com/udayvir-singh/tangerine.nvim) - Tangerine provides a painless way to add fennel to your config.
*   [udayvir-singh/hibiscus.nvim (⭐106)](https://github.com/udayvir-singh/hibiscus.nvim) - Highly opinionated macros to elegantly write your config.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Dependency Management

*   [vuki656/package-info.nvim (⭐585)](https://github.com/vuki656/package-info.nvim) - Display latest package version as virtual text in package.json.
*   [Saecki/crates.nvim (⭐1.1k)](https://github.com/Saecki/crates.nvim) - Rust dependency management for `Cargo.toml`.
*   [piersolenski/import.nvim (⭐261)](https://github.com/piersolenski/import.nvim) - Import modules faster based on what you've already imported in your project.
*   [Silletr/LazyDeveloperHelper (⭐9)](https://github.com/Silletr/LazyDeveloperHelper) - Python dependencies manager, with auto-adding to your `requirements.txt` file.
*   [JesperLundberg/projektgunnar.nvim (⭐20)](https://github.com/JesperLundberg/projektgunnar.nvim) - C# dependency manager with support for handling references between projects and solution files.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Git

*   [mrloop/telescope-git-branch.nvim (⭐10)](https://github.com/mrloop/telescope-git-branch.nvim) - A telescope picker to find which files and preview what changes have been made to your Git branch across multiple commits.
*   [f-person/git-blame.nvim (⭐1k)](https://github.com/f-person/git-blame.nvim) - Show Git blame info.
*   [trevorhauter/gitportal.nvim (⭐88)](https://github.com/trevorhauter/gitportal.nvim) - Generate Git permalinks, open them in your browser, load files locally from permalinks, and more.
*   [lewis6991/gitsigns.nvim (⭐6.4k)](https://github.com/lewis6991/gitsigns.nvim) - Git integration: signs, hunk actions, blame, etc.
*   [nvim-mini/mini.nvim#mini.diff (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-diff.md) - Module of `mini.nvim` to interactively visualize difference between buffer text and its reference. Provides toggleable detailed overview in text area, built-in apply/reset/textobject/goto mappings, and more.
*   [nvim-mini/mini.nvim#mini.git (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-git.md) - Module of `mini.nvim` for enhanced Git integration with current Neovim process. Implements tracking of Git related data, `:Git` user command, and various helpers to explore Git history.
*   [NeogitOrg/neogit (⭐5k)](https://github.com/NeogitOrg/neogit) - A Magit clone that may change some things to fit the Vim philosophy.
*   [tveskag/nvim-blame-line (⭐187)](https://github.com/tveskag/nvim-blame-line) - A small plugin that uses Neovim's virtual text to print Git blame info at the end of the current line.
*   [linrongbin16/gitlinker.nvim (⭐256)](https://github.com/linrongbin16/gitlinker.nvim) - Maintained fork of "ruifm's gitlinker", refactored with bug fixes, ssh aliases, blame support and other improvements.
*   [tanvirtin/vgit.nvim (⭐832)](https://github.com/tanvirtin/vgit.nvim) - Visual Git Plugin to enhance your Git experience.
*   [sindrets/diffview.nvim (⭐5.2k)](https://github.com/sindrets/diffview.nvim) - Single tabpage interface for easily cycling through diffs for all modified files for any Git rev.
*   [kdheepak/lazygit.nvim (⭐2.1k)](https://github.com/kdheepak/lazygit.nvim) - Plugin for calling lazygit.
*   [AckslD/nvim-gfold.lua (⭐32)](https://github.com/AckslD/nvim-gfold.lua) - Plugin using [gfold (⭐377)](https://github.com/nickgerace/gfold) to switch repo and have statusline component.
*   [aaronhallaert/advanced-git-search.nvim (⭐387)](https://github.com/aaronhallaert/advanced-git-search.nvim) - Search your Git history by commit content, message and author with Telescope.
*   [9seconds/repolink.nvim (⭐24)](https://github.com/9seconds/repolink.nvim) - Generate shareable HTTP permalinks for various Git web frontends.
*   [chrisgrieser/nvim-tinygit (⭐200)](https://github.com/chrisgrieser/nvim-tinygit) - Lightweight and nimble Git client.
*   [niuiic/git-log.nvim (⭐20)](https://github.com/niuiic/git-log.nvim) - Check Git log of the selected code.
*   [2KAbhishek/co-author.nvim (⭐36)](https://github.com/2KAbhishek/co-author.nvim) - Quickly add co-authors to commits.
*   [isak102/telescope-git-file-history.nvim (⭐89)](https://github.com/isak102/telescope-git-file-history.nvim) - Open/preview contents of the current file at a specific commit, without using `git checkout`.
*   [moyiz/git-dev.nvim (⭐105)](https://github.com/moyiz/git-dev.nvim) - Open remote Git repositories in the comfort of Neovim.
*   [SuperBo/fugit2.nvim (⭐458)](https://github.com/SuperBo/fugit2.nvim) - Git GUI powered by [libgit2](https://libgit2.org).
*   [Yu-Leo/blame-column.nvim (⭐18)](https://github.com/Yu-Leo/blame-column.nvim) - Show Git blame info.
*   [yutkat/git-rebase-auto-diff.nvim (⭐30)](https://github.com/yutkat/git-rebase-auto-diff.nvim) - Show diff automatically when Git rebase.
*   [Kohei-Wada/yadm-git.nvim (⭐6)](https://github.com/Kohei-Wada/yadm-git.nvim) - Seamless Git plugin support for yadm dotfiles.
*   [axkirillov/unified.nvim (⭐116)](https://github.com/axkirillov/unified.nvim) - Displaying inline unified diffs directly in your buffer.
*   [StackInTheWild/headhunter.nvim (⭐54)](https://github.com/StackInTheWild/headhunter.nvim) - Hunt and resolve merge conflicts directly in Neovim — fast and simple.
*   [yus-works/csc.nvim (⭐37)](https://github.com/yus-works/csc.nvim) - Conventional commit scope completion that learns from Git history.
*   [404pilo/aicommits.nvim (⭐10)](https://github.com/404pilo/aicommits.nvim) - Generate conventional commit messages using AI.
*   [wsdjeg/git.nvim (⭐7)](https://github.com/wsdjeg/git.nvim) - An asynchronous Git command wrapper plugin, using `:Git` command instead of `:!git`.
*   [Mauritz8/gitstatus.nvim (⭐9)](https://github.com/Mauritz8/gitstatus.nvim) - Interactive Git status window with support for staging, unstaging, and committing files.
*   [esmuellert/vscode-diff.nvim (⭐585)](https://github.com/esmuellert/vscode-diff.nvim) - VSCode-style side-by-side diff with two-tier highlighting (line + character level) using VSCode's algorithm implemented in C.
*   [ajatdarojat45/commitmate.nvim (⭐2)](https://github.com/ajatdarojat45/commitmate.nvim) - An AI-assisted commit message generator following common commit conventions.

### GitHub

*   [pwntester/octo.nvim (⭐3k)](https://github.com/pwntester/octo.nvim) - Work with GitHub issues and PRs from Neovim. Just edit the issue description.
*   [ldelossa/gh.nvim (⭐632)](https://github.com/ldelossa/gh.nvim) - A fully featured GitHub integration for performing code reviews.
*   [topaxi/pipeline.nvim (⭐177)](https://github.com/topaxi/pipeline.nvim) - View and dispatch GitHub Actions workflow and GitLab CI pipeline runs.
*   [rawnly/gist.nvim (⭐209)](https://github.com/rawnly/gist.nvim) - Create a GitHub Gist from the current file (powered by gh).
*   [2KAbhishek/octohub.nvim (⭐78)](https://github.com/2KAbhishek/octohub.nvim) - Access all your gihub repos, stats and more in simple keystrokes.
*   [comatory/gh-co.nvim (⭐4)](https://github.com/comatory/gh-co.nvim) - Show the code owner(s) for files according to GitHub's `CODEOWNERS` specification.
*   [3ZsForInsomnia/revman.nvim (⭐7)](https://github.com/3ZsForInsomnia/revman.nvim) - Track PRs that need review automatically and open them in Octo.nvim.
*   [cd-4/git-needy.nvim (⭐3)](https://github.com/cd-4/git-needy.nvim) - Keeps a tally of workflows that need to be reviewed in your statusbar.
*   [claydugo/browsher.nvim (⭐14)](https://github.com/claydugo/browsher.nvim) - Create commit pinned links to GitHub hosted files/lines.

### GitLab

*   [harrisoncramer/GitLab.nvim (⭐348)](https://github.com/harrisoncramer/GitLab.nvim) - Review pull requests and manage other GitLab resources.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Motion

*   [HawkinsT/pathfinder.nvim (⭐59)](https://github.com/HawkinsT/pathfinder.nvim) - Enhances gf/gF/gx with look-ahead and smarter file, line/column number, and link resolution. Also provides visual targets for files/links, new motion commands, and link description retrieval.
*   [tris203/precognition.nvim (⭐1.3k)](https://github.com/tris203/precognition.nvim) - Precognition uses virtual text and gutter signs to show available motions.
*   [smoka7/hop.nvim (⭐741)](https://github.com/smoka7/hop.nvim) - Hop is an EasyMotion-like plugin allowing you to jump anywhere in a document with as few keystrokes as possible.
*   [ggandor/lightspeed.nvim (⭐1.6k)](https://github.com/ggandor/lightspeed.nvim) - A Sneak-like plugin offering unparalleled navigation speed via ahead-of-time displayed labels, that eliminate the pause between entering the search pattern and selecting the target.
*   [ggandor/leap.nvim (⭐5k)](https://github.com/ggandor/leap.nvim) - A refined successor of Lightspeed, aiming to establish a widely accepted standard interface extension for moving around in Vim-like editors.
*   [ggandor/flit.nvim (⭐405)](https://github.com/ggandor/flit.nvim) - Enhanced f/t motions for Leap.
*   [ggandor/leap-spooky.nvim (⭐281)](https://github.com/ggandor/leap-spooky.nvim) - Spooky (Leap) actions at a distance.
*   [rasulomaroff/telepath.nvim (⭐69)](https://github.com/rasulomaroff/telepath.nvim) - Another Leap extension for performing remote actions with a different approach.
*   [folke/flash.nvim (⭐3.8k)](https://github.com/folke/flash.nvim) - Navigate your code with search labels, enhanced character motions and Tree-sitter integration.
*   [nvim-mini/mini.nvim#mini.jump (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-jump.md) - Module of `mini.nvim` for smarter jumping to a single character.
*   [nvim-mini/mini.nvim#mini.jump2d (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-jump2d.md) - Module of `mini.nvim` for smarter jumping within visible lines via iterative label filtering. Supports custom jump targets (spots), labels, hooks, allowed windows and lines, and more.
*   [rlane/pounce.nvim (⭐362)](https://github.com/rlane/pounce.nvim) - An EasyMotion-like plugin for quick cursor movement using fuzzy search.
*   [xiaoshihou514/squirrel.nvim (⭐15)](https://github.com/xiaoshihou514/squirrel.nvim) - Quickly jump between Tree-sitter nodes.
*   [abecodes/tabout.nvim (⭐839)](https://github.com/abecodes/tabout.nvim) - Jump out of bracket pairs, quotes, objects, etc.
*   [woosaaahh/sj.nvim (⭐128)](https://github.com/woosaaahh/sj.nvim) - Search based navigation combined with quick jump features.
*   [cbochs/portal.nvim (⭐366)](https://github.com/cbochs/portal.nvim) - Build upon and enhance existing jumplist motions (i.e. `<c-i>` and `<c-o>`).
*   [nvim-mini/mini.nvim#mini.bracketed (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-bracketed.md) - Module of `mini.nvim` to go forward/backward with square brackets.
*   [liangxianzhe/nap.nvim (⭐102)](https://github.com/liangxianzhe/nap.nvim) - Jump between next/previous buffer, tab, diagnostic, etc, with a single key.
*   [chrisgrieser/nvim-spider (⭐818)](https://github.com/chrisgrieser/nvim-spider) - Use the w, e, b motions like a spider. Considers camelCase and skips insignificant punctuation.
*   [backdround/neowords.nvim (⭐60)](https://github.com/backdround/neowords.nvim) - Hops by any type of words. It gives fine control over `w`, `e`, `b`, `ge` movements.
*   [backdround/improved-ft.nvim (⭐44)](https://github.com/backdround/improved-ft.nvim) - Improve default `f`/`t` abilities.
*   [Mr-LLLLL/treesitter-outer (⭐9)](https://github.com/Mr-LLLLL/treesitter-outer) - Jump to outer node with smart.
*   [Aaronik/Treewalker.nvim (⭐574)](https://github.com/aaronik/Treewalker.nvim) - Move seamlessly around the abstract syntax tree.
*   [timseriakov/spamguard.nvim (⭐10)](https://github.com/timseriakov/spamguard.nvim) - Detects excessive key spamming (jjjj/kkkk) and suggests more efficient alternatives.
*   [millerjason/neovimacs.nvim (⭐4)](https://github.com/millerjason/neovimacs.nvim) - Provides Emacs movement and buffer keybindings while in insert mode.

### Tree-sitter Based

*   [mfussenegger/nvim-treehopper (⭐452)](https://github.com/mfussenegger/nvim-treehopper) - Region selection with hints on the AST nodes of a document powered by Tree-sitter.
*   [drybalka/tree-climber.nvim (⭐151)](https://github.com/drybalka/tree-climber.nvim) - Easy navigation around the Tree-sitter's tree that works in multi-language files and in normal mode.
*   [atusy/treemonkey.nvim (⭐31)](https://github.com/atusy/treemonkey.nvim) - Region selection with Tree-sitter nodes.
*   [kiyoon/treesitter-indent-object.nvim (⭐67)](https://github.com/kiyoon/treesitter-indent-object.nvim) - Context-aware indent textobject powered by Tree-sitter.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Keybinding

*   [sontungexpt/bim.nvim (⭐11)](https://github.com/sontungexpt/bim.nvim) - Enhances insert mode key mapping by showing typed keys in real time, without waiting for timeoutlen. It provides a responsive and intuitive insert-mode experience, ideal for complex input workflows like ime.
*   [folke/which-key.nvim (⭐6.8k)](https://github.com/folke/which-key.nvim) - Neovim plugin that shows a popup with possible keybindings of the command you started typing.
*   [nvim-mini/mini.nvim#mini.clue (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-clue.md) - Module of `mini.nvim` to show next key clues. Has opt-in triggers, shows next key information after customizable delay, allows hydra-like submodes, and more.
*   [mrjones2014/legendary.nvim (⭐1.2k)](https://github.com/mrjones2014/legendary.nvim) - Define your keymaps, commands, and autocommands as simple Lua tables, and create a legend for them at the same time (like VSCode's Command Palette), integrates with `which-key.nvim`.
*   [Iron-E/nvim-cartographer (⭐55)](https://github.com/Iron-E/nvim-cartographer) - a more convenient `:map`ping syntax for Lua environments.
*   [LionC/nest.nvim (⭐235)](https://github.com/LionC/nest.nvim) - Lua utility to map keys concisely using cascading trees. Also allows binding Lua functions to keys.
*   [slugbyte/unruly-worker.nvim (⭐38)](https://github.com/slugbyte/unruly-worker.nvim) - A ridiculously fun alternative keymap for the workman keyboard layout, with lots of powerful features for working with yank, marks, macros, LSP, and more. Built and configured with Lua.
*   [FeiyouG/commander.nvim (⭐413)](https://github.com/FeiyouG/commander.nvim) - Create and manage keybindings and commands in a more organized manner and search them quickly through Telescope.
*   [nvimtools/hydra.nvim (⭐258)](https://github.com/nvimtools/hydra.nvim) - Create custom submodes and menus. Port of Emacs Hydra. Maintained fork of anuvyklack/hydra.nvim.
*   [max397574/better-escape.nvim (⭐762)](https://github.com/max397574/better-escape.nvim) - Create shortcuts to escape insert mode without getting delay.
*   [TheBlob42/houdini.nvim (⭐41)](https://github.com/TheBlob42/houdini.nvim) - Create shortcut to escape modes without delay.
*   [Nexmean/caskey.nvim (⭐67)](https://github.com/Nexmean/caskey.nvim) - Utility to keymappings configuration using declarative cascading trees, optionally integrates with `which-key`.
*   [Wansmer/langmapper.nvim (⭐221)](https://github.com/Wansmer/langmapper.nvim) - Auto translating your mappings for non-English input methods.
*   [tris203/hawtkeys.nvim (⭐238)](https://github.com/tris203/hawtkeys.nvim) - Suggest new easy-to-hit keymaps and find issues with your current keymap configurations.
*   [mawkler/demicolon.nvim (⭐111)](https://github.com/mawkler/demicolon.nvim) - Use `;` and `,` keys to also repeat jumps to diagnostics (e.g. `]d`) and to [nvim-treesitter-textobjects (⭐2.6k)](https://github.com/nvim-treesitter/nvim-treesitter-textobjects?tab=readme-ov-file#text-objects-move) (e.g. `]f`), in addition to repeating `t`/`T`/`f`/`F`.
*   [nvim-mini/mini.nvim#mini.keymap (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-keymap.md) - Module of `mini.nvim` with utilities to make special key mappings: multi-step actions (with built-in steps for "smart" `<Tab>`, `<S-Tab>`, `<CR>`, `<BS>`), combos (more general version of "better escape" like behavior).

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Mouse

*   [notomo/gesture.nvim (⭐535)](https://github.com/notomo/gesture.nvim) - Mouse gesture plugin.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Scrolling

*   [saghen/filler-begone.nvim (⭐19)](https://github.com/saghen/filler-begone.nvim) - Prevents scrolling past the bottom of the buffer and showing unnecessary filler lines.
*   [karb94/neoscroll.nvim (⭐1.9k)](https://github.com/karb94/neoscroll.nvim) - Smooth scrolling.
*   [declancm/cinnamon.nvim (⭐392)](https://github.com/declancm/cinnamon.nvim) - Smooth scrolling for any movement command.
*   [niuiic/scroll.nvim (⭐17)](https://github.com/niuiic/scroll.nvim) - Smooth scrolling, custom smooth strategy.
*   [rlychrisg/keepcursor.nvim (⭐11)](https://github.com/rlychrisg/keepcursor.nvim) - A collection of functions to control how the screen is positioned around the cursor.

### Scrollbar

*   [Xuyuanp/scrollbar.nvim (⭐281)](https://github.com/Xuyuanp/scrollbar.nvim) - Scrollbar.
*   [dstein64/nvim-scrollview (⭐671)](https://github.com/dstein64/nvim-scrollview) - Display interactive scrollbars.
*   [petertriho/nvim-scrollbar (⭐1k)](https://github.com/petertriho/nvim-scrollbar) - Extensible scrollbar that shows diagnostics and search results.
*   [nvim-mini/mini.nvim#mini.map (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-map.md) - Module of `mini.nvim` to show floating window with buffer text overview, scrollbar, and highlights.
*   [gorbit99/codewindow.nvim (⭐474)](https://github.com/gorbit99/codewindow.nvim) - Minimap plugin, that is closely integrated with Tree-sitter and the builtin LSP to display more information to the user.
*   [lewis6991/satellite.nvim (⭐681)](https://github.com/lewis6991/satellite.nvim) - Decorate scrollbar.
*   [wsdjeg/scrollbar.nvim (⭐22)](https://github.com/wsdjeg/scrollbar.nvim) - Floating scrollbar.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Editing Support

*   [qwavies/smart-backspace.nvim (⭐20)](https://github.com/qwavies/smart-backspace.nvim) - Context-aware backspace which handles pairs, whitespace and indentation.
*   [TheLazyCat00/replace-nvim (⭐1)](https://github.com/TheLazyCat00/replace-nvim) - Replace part of your code with the contents of the `+` register using textobjects.
*   [wurli/split.nvim (⭐34)](https://github.com/wurli/split.nvim) - Provides a mapping to split text by delimiter, giving an inverse of the native J command.
*   [csessh/stopinsert.nvim (⭐33)](https://github.com/csessh/stopinsert.nvim) - Automatically exit Insert mode after inactivity.
*   [windwp/nvim-ts-autotag (⭐2k)](https://github.com/windwp/nvim-ts-autotag) - Use Tree-sitter to autoclose and autorename XML, HTML, JSX tag.
*   [windwp/nvim-autopairs (⭐3.9k)](https://github.com/windwp/nvim-autopairs) - A minimalist autopairs written by Lua.
*   [ZhiyuanLck/smart-pairs (⭐134)](https://github.com/ZhiyuanLck/smart-pairs) - Ultimate smart pairs written by Lua.
*   [nvim-mini/mini.nvim#mini.pairs (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-pairs.md) - Module of `mini.nvim` for autopairs which has minimal defaults and functionality to do per-key mapping.
*   [m4xshen/autoclose.nvim (⭐623)](https://github.com/m4xshen/autoclose.nvim) - A minimalist autoclose plugin written in Lua.
*   [altermo/ultimate-autopair.nvim (⭐568)](https://github.com/altermo/ultimate-autopair.nvim) - Autopair with extensions.
*   [monaqa/dial.nvim (⭐1k)](https://github.com/monaqa/dial.nvim) - Extended increment/decrement.
*   [HiPhish/rainbow-delimiters.nvim (⭐807)](https://github.com/HiPhish/rainbow-delimiters.nvim) - Rainbow delimiters with Tree-sitter.
*   [AckslD/nvim-trevJ.lua (⭐172)](https://github.com/AckslD/nvim-trevJ.lua) - Does the opposite of join-line (J) for arguments, powered by Tree-sitter.
*   [okuuva/auto-save.nvim (⭐288)](https://github.com/okuuva/auto-save.nvim) - Automatically saves your work as often as needed and as seldom as possible. Customizable with smart defaults. Maintained fork of Pocco81/auto-save.nvim.
*   [tmillr/sos.nvim (⭐20)](https://github.com/tmillr/sos.nvim) - Automatically save all your modified buffers according to a predefined timeout value.
*   [folke/zen-mode.nvim (⭐2.1k)](https://github.com/folke/zen-mode.nvim) - Distraction-free coding.
*   [andersevenrud/nvim\_context\_vt (⭐406)](https://github.com/andersevenrud/nvim_context_vt) - Shows virtual text of the current context.
*   [nvim-treesitter/nvim-treesitter-context (⭐3k)](https://github.com/nvim-treesitter/nvim-treesitter-context) - Shows floating hover with the current function/block context.
*   [mizlan/iswap.nvim (⭐524)](https://github.com/mizlan/iswap.nvim) - Interactively select and swap function arguments, list elements, and more. Powered by Tree-sitter.
*   [Wansmer/sibling-swap.nvim (⭐179)](https://github.com/Wansmer/sibling-swap.nvim) - Different way to swapping arguments and other siblings with Tree-sitter.
*   [Wansmer/binary-swap.nvim (⭐18)](https://github.com/Wansmer/binary-swap.nvim) - Swapping operands and operators in binary expressions: comparison and mathematical operations.
*   [nacro90/numb.nvim (⭐807)](https://github.com/nacro90/numb.nvim) - Peek lines in a non-obtrusive way.
*   [Allendang/nvim-expand-expr (⭐35)](https://github.com/AllenDang/nvim-expand-expr) - Expand and repeat expression to multiple lines.
*   [h-hg/fcitx.nvim (⭐97)](https://github.com/h-hg/fcitx.nvim) - Switching and restoring fcitx state for each buffer separately.
*   [keaising/im-select.nvim (⭐306)](https://github.com/keaising/im-select.nvim) - Switching and restoring input method automatically depends on Neovim's edit mode.
*   [nvim-mini/mini.nvim#mini.trailspace (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-trailspace.md) - Module of `mini.nvim` for automatic highlighting of trailing whitespace with functionality to remove it.
*   [smjonas/live-command.nvim (⭐539)](https://github.com/smjonas/live-command.nvim) - Text editing with immediate visual feedback: preview commands such as `:norm`, `:g`, macros and more.
*   [filipdutescu/renamer.nvim (⭐315)](https://github.com/filipdutescu/renamer.nvim) - VSCode-like renaming UI, written in Lua.
*   [gbprod/cutlass.nvim (⭐221)](https://github.com/gbprod/cutlass.nvim) - Plugin that adds a 'cut' operation separate from 'delete'.
*   [gbprod/substitute.nvim (⭐716)](https://github.com/gbprod/substitute.nvim) - Neovim plugin introducing a new operator motions to quickly replace and exchange text.
*   [gregorias/coerce.nvim (⭐158)](https://github.com/gregorias/coerce.nvim) - Change keyword case.
*   [nvim-mini/mini.nvim#mini.operators (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-operators.md) - Module of `mini.nvim` with various text edit operators: replace, exchange, multiply, sort, evaluate.
*   [gbprod/yanky.nvim (⭐1.2k)](https://github.com/gbprod/yanky.nvim) - Improved Yank and Put functionalities.
*   [sQVe/sort.nvim (⭐199)](https://github.com/sQVe/sort.nvim) - Sorting plugin that intelligently supports line-wise and delimiter sorting.
*   [booperlv/nvim-gomove (⭐203)](https://github.com/booperlv/nvim-gomove) - A complete plugin for moving and duplicating blocks and lines, with complete fold handling, reindenting, and undoing in one go.
*   [hinell/duplicate.nvim (⭐24)](https://github.com/hinell/duplicate.nvim) - Duplicate lines & blocks of lines easily; undo & unfolding support; full OOP.
*   [hinell/move.nvim (⭐13)](https://github.com/hinell/move.nvim) - Move chunks of text around; fork of [fedepujol/move.nvim (⭐363)](https://github.com/fedepujol/move.nvim).
*   [willothy/moveline.nvim (⭐150)](https://github.com/willothy/moveline.nvim) - Move lines and blocks up and down easily, with indenting handled automatically as you move. Written in Rust.
*   [nvim-mini/mini.nvim#mini.move (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-move.md) - Module of `mini.nvim` to move any selection (charwise, linewise, blockwise, current line in Normal mode) in any direction. Handles both `v:count` and undo history.
*   [gbprod/stay-in-place.nvim (⭐100)](https://github.com/gbprod/stay-in-place.nvim) - Neovim plugin that prevent cursor from moving when using shift and filter actions.
*   [nvim-mini/mini.nvim#mini.ai (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-ai.md) - Module of `mini.nvim` for extending and creating `a`/`i` textobjects. It enhances some builtin textobjects, creates extensive set of new ones (like `a*`, `a<Space>`, `a?`, and more), and allows user to create their own (via Lua patterns or functions). Supports dot-repeat, different search methods, consecutive application, and more.
*   [Wansmer/treesj (⭐1.3k)](https://github.com/Wansmer/treesj) - Splitting/joining blocks of code like arrays, hashes, statements, objects, dictionaries, etc. Using Tree-sitter. Inspired by greatest splitjoin.vim.
*   [bennypowers/splitjoin.nvim (⭐83)](https://github.com/bennypowers/splitjoin.nvim) - Split and join various syntax structures.
*   [nvim-mini/mini.nvim#mini.splitjoin (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-splitjoin.md) - Module of `mini.nvim` to split and join arguments. Has customizable pre and post hooks. Works inside comments.
*   [shortcuts/no-neck-pain.nvim (⭐880)](https://github.com/shortcuts/no-neck-pain.nvim) - Center the currently focused buffer to the middle of your terminal.
*   [debugloop/telescope-undo.nvim (⭐783)](https://github.com/debugloop/telescope-undo.nvim) - A telescope extension to visualize your undo tree and fuzzy-search changes in it.
*   [chrisgrieser/nvim-various-textobjs (⭐744)](https://github.com/chrisgrieser/nvim-various-textobjs) - Bundle of more than 30 new text objects.
*   [XXiaoA/ns-textobject.nvim (⭐37)](https://github.com/XXiaoA/ns-textobject.nvim) - Awesome textobject plugin works with nvim-surround.
*   [\~nedia/auto-save.nvim](https://git.sr.ht/~nedia/auto-save.nvim) - Extremely simple auto saving on `InsertLeave` & `TextChanged`. Based on Pocco81/AutoSave but lighter.
*   [nvim-mini/mini.nvim#mini.basics (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-basics.md) - Module of `mini.nvim` with customizable configuration presets for common options, mappings, and autocommands.
*   [niuiic/part-edit.nvim (⭐14)](https://github.com/niuiic/part-edit.nvim) - Edit a part of a file individually.
*   [niuiic/divider.nvim (⭐28)](https://github.com/niuiic/divider.nvim) - Custom code divider line.
*   [ckolkey/ts-node-action (⭐374)](https://github.com/CKolkey/ts-node-action) - A framework for executing functional transformations on Tree-sitter nodes.
*   [tomiis4/hypersonic.nvim (⭐230)](https://github.com/tomiis4/hypersonic.nvim) - Provides explanation for RegExp.
*   [chrisgrieser/nvim-puppeteer (⭐72)](https://github.com/chrisgrieser/nvim-puppeteer) - Automatically convert strings to f-strings or template strings and back.
*   [nat-418/boole.nvim (⭐182)](https://github.com/nat-418/boole.nvim) - Toggle booleans and common string values.
*   [cshuaimin/ssr.nvim (⭐983)](https://github.com/cshuaimin/ssr.nvim) - Tree-sitter based structural search and replace.
*   [Jxstxs/conceal.nvim (⭐76)](https://github.com/Jxstxs/conceal.nvim) - Use Tree-sitter to conceal common boilerplate code.
*   [hiberabyss/bzlops.vim (⭐4)](https://github.com/hiberabyss/bzlops.vim) - Help to manage your bazel build rule.
*   [altermo/iedit.nvim (⭐27)](https://github.com/altermo/iedit.nvim) - Edit one occurrence of text and simultaneously have other selected occurrences edited in the same way.
*   [ptdewey/yankbank-nvim (⭐123)](https://github.com/ptdewey/yankbank-nvim) - Enable streamlined access to recent yanks and deletions in a quick-access popup menu.
*   [SunnyTamang/select-undo.nvim (⭐91)](https://github.com/SunnyTamang/select-undo.nvim) - Allow users to undo specific line/lines or partial selections without affecting the rest of the file.
*   [OXY2DEV/foldtext.nvim (⭐114)](https://github.com/OXY2DEV/foldtext.nvim) - Dynamic & stylized foldtext.
*   [tummetott/unimpaired.nvim (⭐100)](https://github.com/tummetott/unimpaired.nvim) - Lua port of [tpope/vim-unimpaired (⭐3.4k)](https://github.com/tpope/vim-unimpaired).
*   [daltongd/yanklock.nvim (⭐20)](https://github.com/daltongd/yanklock.nvim) - Temporarily lock the paste register to `"0`, and use `d`, `c`, and `s` motions while keeping the most recent yanked content easily accessible.
*   [zongben/capsoff.nvim (⭐12)](https://github.com/zongben/capsoff.nvim) - Turns off CapsLock when you leaving insert mode.
*   [kobbikobb/move-lines.nvim (⭐8)](https://github.com/kobbikobb/move-lines.nvim) - Moves lines selected in virtual mode.
*   [kiyoon/telescope-insert-path.nvim (⭐42)](https://github.com/kiyoon/telescope-insert-path.nvim) - Insert file path in the current buffer using Telescope.
*   [zhisme/copy\_with\_context.nvim (⭐26)](https://github.com/zhisme/copy_with_context.nvim) - Copy lines with file path and line number metadata for sharing code snippets with context.
*   [jake-stewart/multicursor.nvim (⭐1.3k)](https://github.com/jake-stewart/multicursor.nvim) - Adds support for multiple cursors which work how you expect.
*   [brenton-leighton/multiple-cursors.nvim (⭐371)](https://github.com/brenton-leighton/multiple-cursors.nvim) - A multi-cursor plugin that works in normal, insert/replace, or visual modes, and with almost every command.
*   [smoka7/multicursors.nvim (⭐623)](https://github.com/smoka7/multicursors.nvim) - Provides a more intuitive way to edit repetitive text with multiple selections.
*   [tigion/swap.nvim (⭐15)](https://github.com/tigion/swap.nvim) - Quickly switch a word under the cursor or a pattern in the current line.
*   [XXiaoA/atone.nvim (⭐114)](https://github.com/XXiaoA/atone.nvim) - Undo tree for visualizing and managing undo history.

### Comment

*   [numToStr/Comment.nvim (⭐4.5k)](https://github.com/numToStr/Comment.nvim) - Smart and powerful comment plugin. Supports commentstring, motions, dot-repeat and more.
*   [b3nj5m1n/kommentary (⭐533)](https://github.com/b3nj5m1n/kommentary) - Commenting plugin written in Lua.
*   [gennaro-tedesco/nvim-commaround (⭐42)](https://github.com/gennaro-tedesco/nvim-commaround) - Fast and light commenting plugin written in Lua.
*   [folke/todo-comments.nvim (⭐4k)](https://github.com/folke/todo-comments.nvim) - Highlight, list and search todo comments in your projects.
*   [alexmozaidze/tree-comment.nvim (⭐10)](https://github.com/alexmozaidze/tree-comment.nvim) - Highlight and configure TODO comments for [tree-sitter-comment (⭐159)](https://github.com/stsewd/tree-sitter-comment).
*   [terrortylor/nvim-comment (⭐492)](https://github.com/terrortylor/nvim-comment) - Toggle comments using the built-in commentstring option.
*   [winston0410/commented.nvim (⭐114)](https://github.com/winston0410/commented.nvim) - A commenting plugin which supports counts and multiple comment patterns and much more.
*   [s1n7ax/nvim-comment-frame (⭐100)](https://github.com/s1n7ax/nvim-comment-frame) - Adds a comment frame based on the source file.
*   [danymat/neogen (⭐1.6k)](https://github.com/danymat/neogen) - A better annotation generator which supports multiple languages and annotation conventions.
*   [nvim-mini/mini.nvim#mini.comment (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-comment.md) - Module of `mini.nvim` for per-line commenting. Fully supports dot-repeat.
*   [LudoPinelli/comment-box.nvim (⭐472)](https://github.com/LudoPinelli/comment-box.nvim) - Clarify and beautify your comments using boxes and lines.
*   [JoosepAlviste/nvim-ts-context-commentstring (⭐1.3k)](https://github.com/JoosepAlviste/nvim-ts-context-commentstring) - Sets the `commentstring` option based on the cursor location in the file. The location is checked via Tree-sitter queries.
*   [LucasTavaresA/SingleComment.nvim (⭐9)](https://github.com/LucasTavaresA/SingleComment.nvim) - Always single line, comment sensitive, indentation preserving commenting.
*   [Zeioth/dooku.nvim (⭐48)](https://github.com/Zeioth/dooku.nvim) - Generate and open your HTML code documentation.
*   [soemre/commentless.nvim (⭐41)](https://github.com/soemre/commentless.nvim) - Fold all comments to better visualize your code logic, and unfold them whenever needed.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Formatting

*   [TheLazyCat00/simple-format (⭐4)](https://github.com/TheLazyCat00/simple-format) - Replace text using custom regex and highlight group rules.
*   [mhartington/formatter.nvim (⭐1.4k)](https://github.com/mhartington/formatter.nvim) - A format runner written in Lua.
*   [sbdchd/neoformat (⭐2k)](https://github.com/sbdchd/neoformat) - A code formatting runner.
*   [cappyzawa/trim.nvim (⭐151)](https://github.com/cappyzawa/trim.nvim) - Trims trailing whitespace and lines.
*   [MunifTanjim/prettier.nvim (⭐315)](https://github.com/MunifTanjim/prettier.nvim) - Prettier integration.
*   [nvim-mini/mini.nvim#mini.align (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-align.md) - Module of `mini.nvim` for aligning text interactively (with or without instant preview).
*   [emileferreira/nvim-strict (⭐38)](https://github.com/emileferreira/nvim-strict) - Strict, native code style formatting which exposes deep nesting, overlong lines, trailing whitespace, trailing empty lines, todos and inconsistent indentation.
*   [\~nedia/auto-format.nvim](https://git.sr.ht/~nedia/auto-format.nvim) - Sets up an autocommand to format on save, preferring `null-ls` over native LSP client formatting.
*   [tenxsoydev/tabs-vs-spaces.nvim (⭐26)](https://github.com/tenxsoydev/tabs-vs-spaces.nvim) - Hint and fix deviating indentation.
*   [bennypowers/svgo.nvim (⭐3)](https://github.com/bennypowers/svgo.nvim) - Optimize SVG files.
*   [niuiic/format.nvim (⭐34)](https://github.com/niuiic/format.nvim) - An asynchronous, multitasking, highly configurable formatting plugin.
*   [elentok/format-on-save.nvim (⭐172)](https://github.com/elentok/format-on-save.nvim) - A synchronous formatter that combines both LSP and non-LSP formatting (e.g. `shfmt`, `stylua`, `prettier`). Focused specifically for format-on-save.
*   [stevearc/conform.nvim (⭐4.8k)](https://github.com/stevearc/conform.nvim) - A lightweight formatting engine that plays nice with LSP.
*   [nvimdev/guard.nvim (⭐505)](https://github.com/nvimdev/guard.nvim) - Minimalist async formatting and linting plugin.
*   [paul-louyot/toggle-quotes.nvim (⭐7)](https://github.com/paul-louyot/toggle-quotes.nvim) - Toggle between quotes.
*   [wsdjeg/format.nvim (⭐14)](https://github.com/wsdjeg/format.nvim) - An asynchronous code formatting plugin.

### Indent

*   [saghen/blink.indent (⭐152)](https://github.com/saghen/blink.indent) - Performant indent guides with scope on every keystroke.
*   [nvimdev/indentmini.nvim (⭐271)](https://github.com/nvimdev/indentmini.nvim) - A minimal and blazing fast indentline plugin by using the `nvim_set_decoration_provide` API function.
*   [lukas-reineke/indent-blankline.nvim (⭐4.8k)](https://github.com/lukas-reineke/indent-blankline.nvim) - IndentLine replacement in Lua with more features and Tree-sitter support.
*   [LucasTavaresA/simpleIndentGuides.nvim (⭐10)](https://github.com/LucasTavaresA/simpleIndentGuides.nvim) - Indentation guides using the builtin variables.
*   [nvim-mini/mini.nvim#mini.indentscope (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-indentscope.md) - Module of `mini.nvim` for visualizing and operating on indent scope. Supports customization of debounce delay, animation style, and different granularity of options for scope computing algorithm.
*   [NMAC427/guess-indent.nvim (⭐590)](https://github.com/NMAC427/guess-indent.nvim) - Automatic indentation style detection.
*   [Darazaki/indent-o-matic (⭐200)](https://github.com/Darazaki/indent-o-matic) - Dumb automatic fast indentation detection written in Lua.
*   [yaocccc/nvim-hlchunk (⭐54)](https://github.com/yaocccc/nvim-hlchunk) - Highlight a `{}` chunk.
*   [shellRaining/hlchunk.nvim (⭐871)](https://github.com/shellRaining/hlchunk.nvim) - A Lua implementation of `nvim-hlchunk`, contains more features, such as highlight `{}` chunk, indent line, space blank etc.
*   [VidocqH/auto-indent.nvim (⭐88)](https://github.com/VidocqH/auto-indent.nvim) - Auto indent cursor when cursor at the first column and press `<TAB>` key like VSCode.
*   [Mr-LLLLL/cool-chunk.nvim (⭐28)](https://github.com/Mr-LLLLL/cool-chunk.nvim) - Simpler and faster chunking with animations.
*   [gh-liu/fold\_line.nvim (⭐55)](https://github.com/gh-liu/fold_line.nvim) - Lines for indicating code folding, which could achieve an effect similar to indentline by `:set fdm=indent`.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Command Line

*   [notomo/cmdbuf.nvim (⭐133)](https://github.com/notomo/cmdbuf.nvim) - Alternative command-line-window plugin.
*   [gelguy/wilder.nvim (⭐1.5k)](https://github.com/gelguy/wilder.nvim) - A plugin for fuzzy command line autocompletion.
*   [vzze/cmdline.nvim (⭐21)](https://github.com/vzze/cmdline.nvim) - Helix-like command line with fuzzy autocompletion.
*   [nvim-mini/mini.nvim#mini.cmdline (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-cmdline.md) - Module of `mini.nvim` for command line tweaks. Adds autocompletion with customizable delay, autocorrection for words with fixed candidates, and autopeek command range in a floating window.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Session

*   [rmagatti/auto-session (⭐1.7k)](https://github.com/rmagatti/auto-session) - A small automated session manager.
*   [nvim-mini/mini.nvim#mini.sessions (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-sessions.md) - Module of `mini.nvim` for session management (read, write, delete).
*   [gennaro-tedesco/nvim-possession (⭐286)](https://github.com/gennaro-tedesco/nvim-possession) - The no-nonsense session manager.
*   [olimorris/persisted.nvim (⭐515)](https://github.com/olimorris/persisted.nvim) - Simple session management with Git branching, autosave/autoload and Telescope support.
*   [folke/persistence.nvim (⭐931)](https://github.com/folke/persistence.nvim) - Simple automated session management.
*   [Shatur/neovim-session-manager (⭐607)](https://github.com/Shatur/neovim-session-manager) - A simple wrapper around :mksession.
*   [jedrzejboczar/possession.nvim (⭐391)](https://github.com/jedrzejboczar/possession.nvim) - Flexible session management with arbitrary persistent data stored as JSON.
*   [niuiic/multiple-session.nvim (⭐9)](https://github.com/niuiic/multiple-session.nvim) - Provides multi-session management capabilities.
*   [coffebar/neovim-project (⭐271)](https://github.com/coffebar/neovim-project) - Declarative project management, automatic saving of sessions, uses Telescope.
*   [njayman/season.nvim (⭐3)](https://github.com/njayman/season.nvim) - A lightweight plugin to manage session based on current working directory.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Remote Development

*   [inhesrom/remote-ssh.nvim (⭐79)](https://github.com/inhesrom/remote-ssh.nvim) - Duplicates the basic ground level functionality of VSCode's Remote-SSH plugin, with a focus on a local editing experience to avoid remote "lag". Browse remote files, edit "remote buffers" with a full local editing experience (LSP, Tree-sitter, Telescope integration, and a file watcher).
*   [chipsenkbeil/distant.nvim (⭐1.4k)](https://github.com/chipsenkbeil/distant.nvim) - Edit files, run programs, and work with LSP on a remote machine from the comfort of your local environment.
*   [jamestthompson3/nvim-remote-containers (⭐923)](https://github.com/jamestthompson3/nvim-remote-containers) - Develop inside Docker containers, just like VSCode.
*   [esensar/nvim-dev-container (⭐684)](https://github.com/esensar/nvim-dev-container) - Neovim devcontainer.json and general development container support.
*   [miversen33/netman.nvim (⭐365)](https://github.com/miversen33/netman.nvim) - Lua powered Network Resource Manager.
*   [niuiic/remote.nvim (⭐44)](https://github.com/niuiic/remote.nvim) - Edit remote files with local configuration.
*   [uhs-robert/sshfs.nvim (⭐14)](https://github.com/uhs-robert/sshfs.nvim) - Mount remote systems via SSHFS with smart picker auto-detect (Telescope/Oil/Snacks/Neo-tree/fzf-lua/Yazi/Ranger etc.).
*   [nosduco/remote-sshfs.nvim (⭐355)](https://github.com/nosduco/remote-sshfs.nvim) - Explore, edit, and develop on a remote machine via SSHFS.
*   [azratul/live-share.nvim (⭐232)](https://github.com/azratul/live-share.nvim) - Provides remote collaboration capabilities from anywhere, making it ideal for pair-programming scenarios.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Split and Window

*   [\~henriquehbr/ataraxis.lua](https://sr.ht/~henriquehbr/ataraxis.lua) - A zen mode for improving code readability on Neovim.
*   [yorickpeterse/nvim-window (⭐167)](https://github.com/yorickpeterse/nvim-window) - Easily jump between Neovim windows.
*   [sindrets/winshift.nvim (⭐527)](https://github.com/sindrets/winshift.nvim) - Rearrange your windows with ease.
*   [nvim-focus/focus.nvim (⭐801)](https://github.com/nvim-focus/focus.nvim) - Auto-Focusing and Auto-Resizing Splits/Windows written in Lua! Vim splits on steroids.
*   [anuvyklack/windows.nvim (⭐623)](https://github.com/anuvyklack/windows.nvim) - Automatically expand width of the current window. Maximizes and restore it. And all this with nice animations!
*   [nvim-zh/colorful-winsep.nvim (⭐623)](https://github.com/nvim-zh/colorful-winsep.nvim) - A configurable color split line.
*   [nyngwang/NeoNoName.lua (⭐29)](https://github.com/nyngwang/NeoNoName.lua) - Layout preserving buffer deletion.
*   [famiu/bufdelete.nvim (⭐518)](https://github.com/famiu/bufdelete.nvim) - Delete Neovim buffers without losing your window layout.
*   [nvim-mini/mini.nvim#mini.bufremove (⭐8.5k)](https://github.com/nvim-mini/mini.nvim/blob/main/readmes/mini-bufremove.md) - Module of `mini.nvim` for buffer removing (unshow, delete, wipeout) while saving window layout.
*   [jyscao/ventana.nvim (⭐21)](https://github.com/jyscao/ventana.nvim) - Convenient flips & shifts for your windows layout.
*   [mrjones2014/smart-splits.nvim (⭐1.5k)](https://github.com/mrjones2014/smart-splits.nvim) - Smart, seamless, directional navigation and resizing of splits.
*   [altermo/nwm (⭐336)](https://github.com/altermo/nwm) - X11 window manager.
*   [MisanthropicBit/winmove.nvim (⭐14)](https://github.com/MisanthropicBit/winmove.nvim) - Easily move, swap, and resize windows.
*   [ycdzj/win-mover.nvim (⭐11)](https://github.com/ycdzj/win-mover.nvim) - Window mover that avoids moving side windows.
*   [mkajsjo/windowcolumns.nvim (⭐7)](https://github.com/mkajsjo/windowcolumns.nvim) - Column-first window management.

### Tmux

*   [aserowy/tmux.nvim (⭐764)](https://github.com/aserowy/tmux.nvim) - Tmux integration features pane movement and resizing.
*   [danielpieper/telescope-tmuxinator.nvim (⭐25)](https://github.com/danielpieper/telescope-tmuxinator.nvim) - Integration for tmuxinator with telescope.nvim.
*   [hkupty/nvimux (⭐451)](https://github.com/hkupty/nvimux) - Neovim as tmux replacement.
*   [numToStr/Navigator.nvim (⭐433)](https://github.com/numToStr/Navigator.nvim) - Smoothly navigate between Neovim splits and Tmux panes.
*   [declancm/windex.nvim (⭐61)](https://github.com/declancm/windex.nvim) - Collection of window functions which includes moving between, closing and maximizing Neovim splits and Tmux panes.
*   [karshPrime/only-tmux.nvim (⭐11)](https://github.com/karshPrime/only-tmux.nvim) - Expand the functionality of `:only` with tmux panes in the same window, with either moving them to a new window or closing them.
*   [karshPrime/tmux-compile.nvim (⭐24)](https://github.com/karshPrime/tmux-compile.nvim) - Set up same key, like F5, to run any compile/run command per language, like `make` for C and `cargo build` for Rust, and have the project run or compile in a new tmux pane or window.
*   [EvWilson/slimux.nvim (⭐30)](https://github.com/EvWilson/slimux.nvim) - Send content from the current buffer to a configurable tmux pane.
*   [juselara1/tmutils.nvim (⭐16)](https://github.com/juselara1/tmutils.nvim) - Tmux utilities that enable sending lines, capturing content, creating terminals, and managing REPLs.
*   [kiyoon/tmux-send.nvim (⭐16)](https://github.com/kiyoon/tmux-send.nvim) - Copy and paste buffer content or file path in Nvim-Tree, Neo-Tree, Oil to another tmux pane in Neovim.
*   [jkeresman01/tmux-switch.nvim (⭐4)](https://github.com/jkeresman01/tmux-switch.nvim) - Provides fuzzy session switching for Tmux.
*   [salorak/libtmux.nvim (⭐3)](https://github.com/salorak/libtmux.nvim) - Thin wrapper for using the `tmux` API.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Game

*   [alec-gibson/nvim-tetris (⭐206)](https://github.com/alec-gibson/nvim-tetris) - Bringing Emacs' greatest feature to Neovim - Tetris!.
*   [seandewar/nvimesweeper (⭐107)](https://github.com/seandewar/nvimesweeper) - Play Minesweeper in your favourite text editor.
*   [seandewar/killersheep.nvim (⭐76)](https://github.com/seandewar/killersheep.nvim) - Neovim port of killersheep.
*   [rktjmp/playtime.nvim (⭐85)](https://github.com/rktjmp/playtime.nvim) - A collection of games such as Freecell, Shenzhen Solitaire and The Emissary.
*   [Eandrju/cellular-automaton.nvim (⭐2.1k)](https://github.com/Eandrju/cellular-automaton.nvim) - It lets you execute aesthetically pleasing, cellular automaton animations based on the content of Neovim buffer.
*   [alanfortlink/blackjack.nvim (⭐68)](https://github.com/alanfortlink/blackjack.nvim) - Classic Black Jack game.
*   [jim-fx/sudoku.nvim (⭐80)](https://github.com/jim-fx/sudoku.nvim) - Classic sudoku puzzle.
*   [csessh/aoc.vim (⭐7)](https://github.com/csessh/aoc.nvim) - Simple little elf who fetches Advent of Code puzzle input for you.
*   [seandewar/actually-doom.nvim (⭐125)](https://github.com/seandewar/actually-doom.nvim) - Editing text is boring; play DOOM instead!.
*   [piersolenski/skifree.nvim (⭐5)](https://github.com/piersolenski/skifree.nvim) - Play the Windows 3.1 SkiFree game.

### Competitive Programming

*   [p00f/cphelper.nvim (⭐145)](https://github.com/p00f/cphelper.nvim) - Neovim helper for competitive programming written in Lua.
*   [xeluxee/competitest.nvim (⭐546)](https://github.com/xeluxee/competitest.nvim) - A plugin to automate testcases management and checking for Competitive Programming contests.
*   [kawre/leetcode.nvim (⭐1.9k)](https://github.com/kawre/leetcode.nvim) - Solve Leetcode problems.
*   [2KAbhishek/exercism.nvim (⭐35)](https://github.com/2KAbhishek/exercism.nvim) - Browse and solve Exercism problems.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Workflow

*   [m4xshen/hardtime.nvim (⭐3.6k)](https://github.com/m4xshen/hardtime.nvim) - Helping you establish good command workflow and habit.
*   [saxon1964/neovim-tips (⭐426)](https://github.com/saxon1964/neovim-tips) - Provides hundreds of built-in Neovim tips, tricks, and shortcuts, with a custom picker interface and the ability to add your own tips.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Database

*   [zongben/dbout.nvim (⭐27)](https://github.com/zongben/dbout.nvim) - Manage database connections and run SQL queries directly in Neovim with JSON results.
*   [kndndrj/nvim-dbee (⭐1.2k)](https://github.com/kndndrj/nvim-dbee) - Interactive database client.
*   [tashikomaaa/neomongo.nvim (⭐6)](https://github.com/tashikomaaa/neomongo.nvim) - Explore, query, and edit MongoDB collections directly through a Telescope-powered dashboard.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Preconfigured Configuration

*   [pgosar/CyberNvim (⭐371)](https://github.com/pgosar/CyberNvim) - The world's simplest and most extensible Neovim distribution.
*   [sontungexpt/stinvim (⭐49)](https://github.com/sontungexpt/stinvim) - Ready Neovim's configuration for fullstack developers.
*   [Abstract-IDE/Abstract (⭐202)](https://github.com/Abstract-IDE/Abstract) - Abstract, The Neovim configuration to achieve the power of Modern IDE.
*   [SpaceVim/SpaceVim](https://spacevim.org) - A community-driven modular Vim/Neovim distribution, like spacemacs but for Vim/Neovim.
*   [CosmicNvim/CosmicNvim (⭐1.1k)](https://github.com/CosmicNvim/CosmicNvim) - CosmicNvim is a lightweight and opinionated Neovim config for web development, specifically designed to provide a COSMIC programming experience!
*   [artart222/CodeArt (⭐902)](https://github.com/artart222/CodeArt) - A fast general-purpose IDE written entirely in Lua with an installer for Linux/Windows/macOS and built in `:CodeArtUpdate` command for updating it.
*   [LazyVim/LazyVim (⭐24k)](https://github.com/LazyVim/LazyVim) - Full-fledged IDE powered by **lazy.nvim** to make it easy to customize and extend your config.
*   [legobeat/l7-devenv (⭐26)](https://github.com/legobeat/l7-devenv) - Security-focused IDE with a hackable (in the right way) framework based on Neovim and shell.
*   [crispybaccoon/chaivim (⭐73)](https://github.com/crispybaccoon/chaivim) - Easily configurable distro with solid defaults and a cozy editor experience.
*   [crivotz/nv-ide (⭐641)](https://github.com/crivotz/nv-ide) - Neovim custom configuration, oriented for full stack developers (Rails, Ruby, PHP, HTML, CSS, SCSS, JavaScript).
*   [LunarVim/LunarVim (⭐19k)](https://github.com/LunarVim/LunarVim) - This project aims to help one transition away from VSCode, and into a superior text editing experience.
*   [hackorum/VapourNvim (⭐561)](https://github.com/hackorum/VapourNvim) - A Neovim config for THE ULTIMATE Vim IDE-like experience.
*   [siduck76/NvChad (⭐28k)](https://github.com/siduck76/NvChad) - An attempt to make Neovim cli as functional as an IDE while being very beautiful and less bloated.
*   [cstsunfu/.sea.nvim (⭐146)](https://github.com/cstsunfu/.sea.nvim) - A modular Neovim configuration with beautiful UI and some useful features(Pomodoro Clock, Window Number).
*   [shaeinst/roshnivim (⭐202)](https://github.com/shaeinst/roshnivim) - Roshnivim, can be called Neovim's distro, is a predefined configs so that you don't need 1000hr to setup Neovim as an IDE.
*   [AstroNvim/AstroNvim (⭐14k)](https://github.com/AstroNvim/AstroNvim) - AstroNvim is an aesthetic and feature-rich Neovim config that is extensible and easy to use with a great set of plugins.
*   [shaunsingh/nyoom.nvim (⭐1.6k)](https://github.com/shaunsingh/nyoom.nvim) - Blazing fast, configurable, minimal and lispy Neovim config written in Fennel. Base config for users to extend and add upon, leading to a more unique editing experience.
*   [jrychn/moduleVim (⭐8)](https://github.com/jrychn/ModuleVim) - A very easy to use
    for backend and frontend, install LSP automatically.
*   [imbacraft/dusk.nvim (⭐55)](https://github.com/imbacraft/dusk.nvim) - Dusk is a lightweight, aesthetically minimal Neovim config, written in Lua, able to provide for web and Java development.
*   [nvim-lua/kickstart.nvim (⭐29k)](https://github.com/nvim-lua/kickstart.nvim) - A launch point for your personal Neovim configuration.
*   [dam9000/kickstart-modular.nvim (⭐922)](https://github.com/dam9000/kickstart-modular.nvim) - This is a fork of nvim-lua/kickstart.nvim that moves from a single file to a multi file configuration.
*   [cunderw/nvim (⭐11)](https://github.com/cunderw/nvim) - Neovim custom configuration, focused on JS/TS, Go, and Java development. Very IDE like.
*   [ldelossa/nvim-ide (⭐866)](https://github.com/ldelossa/nvim-ide) - A full featured IDE layer heavily inspired by VSCode.
*   [linrongbin16/lin.nvim (⭐87)](https://github.com/linrongbin16/lin.nvim) - A highly configured Neovim distribution integrated with tons of utilities for development, inspired by spf13-vim.
*   [doctorfree/nvim-lazyman (⭐410)](https://github.com/doctorfree/nvim-lazyman) - Neovim configuration manager and modular configuration, supports over 40 preconfigured configurations.
*   [NormalNvim/NormalNvim (⭐684)](https://github.com/NormalNvim/NormalNvim) - Focused on stability for your daily work. From the creator of Compiler.nvim.
*   [chrisgrieser/nvim-kickstart-python (⭐155)](https://github.com/chrisgrieser/nvim-kickstart-python) - A launch point for your Neovim configuration for Python.
*   [mrcjkb/kickstart-nix.nvim (⭐378)](https://github.com/mrcjkb/kickstart-nix.nvim) - A simple [Nix flake](https://wiki.nixos.org/wiki/Flakes) template repo for Neovim derivations, with the goal of simplifying the migration from existing Neovim configurations.
*   [drybalka/clean.nvim (⭐38)](https://github.com/drybalka/clean.nvim) - Cleaning up the default key mappings and plugins and leaving only the bare essentials to build upon.
*   [StratOS-Linux/StratVIM (⭐13)](https://github.com/StratOS-Linux/StratVIM) - A full-fledged Neovim distribution included by default in [StratOS](https://github.com/StratOS-Linux), an upcoming Arch-based Linux distro.
*   [Shaobin-Jiang/IceNvim (⭐281)](https://github.com/Shaobin-Jiang/IceNvim) - A beautiful, powerful and customizable config that is blazingly fast.
*   [ayamir/nvimdots (⭐3.3k)](https://github.com/ayamir/nvimdots) - A well-configured and structured configuration with NixOS support.
*   [adoyle-h/one.nvim (⭐175)](https://github.com/adoyle-h/one.nvim) - All-in-one config framework in Lua.
*   [nvim-mini/MiniMax (⭐225)](https://github.com/nvim-mini/MiniMax) - A collection of self-contained and extensively commented configurations which mostly use MINI tools.
*   [TheItcor/MoaiVim (⭐4)](https://github.com/TheItcor/MoaiVim) - A minimalist config that emulates a lightweight IDE.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## External

These tools are used externally to Neovim to enhance the experience.

### Version Manager

*   [MordechaiHadad/bob (⭐1.9k)](https://github.com/MordechaiHadad/bob) - A cross platform and easy to use Neovim version manager.
*   [NTBBloodbath/nvenv (⭐61)](https://github.com/NTBBloodbath/nvenv) - A lightweight and blazing fast Neovim version manager.
*   [y3owk1n/nvs (⭐27)](https://github.com/y3owk1n/nvs) - Another Neovim version manager with config switcher.

### Boilerplate

*   [gennaro-tedesco/boilit (⭐83)](https://github.com/gennaro-tedesco/boilit) - Create boilerplate structure plugins.
*   [m00qek/plugin-template.nvim (⭐131)](https://github.com/m00qek/plugin-template.nvim) - A plugin template that setups test infrastructure and GitHub Actions.
*   [ellisonleao/nvim-plugin-template (⭐424)](https://github.com/ellisonleao/nvim-plugin-template) - Another Neovim plugin template, using GitHub's template feature.
*   [2KAbhishek/template.nvim (⭐17)](https://github.com/2KAbhishek/template.nvim) - Opinionated template for starting plugin dev quickly.
*   [jkeresman01/spring-initializr.nvim (⭐16)](https://github.com/jkeresman01/spring-initializr.nvim) - Scaffold Spring Boot projects with a Telescope-powered UI.

### OS-specific

*   [chrisgrieser/alfred-neovim-utilities (⭐43)](https://github.com/chrisgrieser/alfred-neovim-utilities) - Search Neovim plugins and online `:help` via Alfred (macOS).
*   [massix/termux.nvim (⭐24)](https://github.com/massix/termux.nvim) - Interact with Termux APIs, useful to gather various information about your Android phone to display in the statusline (e.g. battery level).
*   [m15a/flake-awesome-neovim-plugins (⭐60)](https://github.com/m15a/flake-awesome-neovim-plugins) - Nix flake that provides Awesome Neovim plugins collection as Nix packages.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Wishlist

Have a problem a plugin can solve? Add it to the [nvim-lua wishlist (⭐249)](https://github.com/nvim-lua/wishlist).

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## UI

Neovim supports a wide variety of UI's.
You can find them listed on the [Neovim wiki (⭐95k)](https://github.com/neovim/neovim/wiki/Related-projects#gui)

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Starter Templates

*   [tokiory/neovim-boilerplate (⭐118)](https://github.com/tokiory/neovim-boilerplate) - Starter boilerplate for making new configurations.
*   [frans-johansson/lazy-nvim-starter (⭐96)](https://github.com/frans-johansson/lazy-nvim-starter) - Starter boilerplate with lazy plugin manager.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Vim

*   [Vimawesome](https://vimawesome.com/) - Showcases various plugins for Vim and has a [Neovim tag](https://vimawesome.com/?q=tag:neovim) for other plugins targeting Neovim.
*   [akrawchyk/awesome-vim#tools (⭐2.1k)](https://github.com/akrawchyk/awesome-vim#tools) - Short list of Vim plugins and helpful guides.
*   [altermo/vim-plugin-list (⭐142)](https://github.com/altermo/vim-plugin-list) - List of Vim and Neovim plugins.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

## Resource

*   [Neovimcraft](https://neovimcraft.com) - A site dedicated to searching specific plugins and guides for building plugins in Lua.
*   [Dotfyle](https://dotfyle.com) - A site for sharing and discovering Neovim configs and plugins.
*   [NeoLand](https://neoland.dev) - A beautifully crafted website for Neovim resources.
*   [Weyaaron/nvim-training (⭐108)](https://github.com/Weyaaron/nvim-training) - A beginner-friendly tool for training your 'muscle memory' using small, repeatable tasks.
*   [Nvim.app](https://nvim.app) - A modern search interface for Neovim plugins with fuzzy search, filtering, and self-service updates for plugin authors.

<!--lint disable double-link -->

**[⬆ back to top](#contents)**

<!--lint enable double-link -->

