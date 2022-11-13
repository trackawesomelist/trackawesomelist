# Awesome Neovim Overview

Collections of awesome neovim plugins.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/rockerBOO/awesome-neovim/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 rockerBOO/awesome-neovim](https://github.com/rockerBOO/awesome-neovim) · ⭐ 7.4K · 🏷️ Editors

[ [Daily](/content/rockerBOO/awesome-neovim/README.md) / [Weekly](/content/rockerBOO/awesome-neovim/week/README.md) / Overview ]

---

<!-- lint ignore awesome-git-repo-age -->

<img src="https://neovim.io/logos/neovim-mark-flat.png" align="right" width="144" />

# Awesome Neovim [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<!-- Uncomment the awesome badge when the repository is added to awesome main list.
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
-->

> Collections of awesome Neovim plugins. Mostly targeting Neovim specific features.

[Neovim](https://neovim.io/) is a Vim-based text editor engineered for extensibility and usability, to encourage new applications and contributions.

## Contents

*   [Wishlist](#wishlist)
*   [UI](#ui)
*   [Plugin](#plugin)
    *   [Plugin Manager](#plugin-manager)
    *   [LSP](#lsp)
    *   [Completion](#completion)
    *   [Programming Languages Support](#programming-languages-support)
        *   [Golang](#golang)
        *   [YAML](#yaml)
        *   [Web Development](#web-development)
        *   [Markdown and LaTeX](#markdown-and-latex)
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
    *   [Bars and Lines](#bars-and-lines)
        *   [Statusline](#statusline)
        *   [Tabline](#tabline)
        *   [Winbar](#winbar)
        *   [Cursorline](#cursorline)
    *   [Startup](#startup)
    *   [Icon](#icon)
    *   [Media](#media)
    *   [Note Taking](#note-taking)
    *   [Utility](#utility)
    *   [Terminal Integration](#terminal-integration)
    *   [Debugging](#debugging)
        *   [Quickfix](#quickfix)
    *   [Test](#test)
    *   [Code Runner](#code-runner)
    *   [Neovim Lua Development](#neovim-lua-development)
    *   [Fennel](#fennel)
    *   [Dependency Management](#dependency-management)
    *   [Git](#git)
        *   [GitHub](#github)
    *   [Motion](#motion)
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
    *   [Preconfigured Configuration](#preconfigured-configuration)
*   [External](#external)
    *   [Version Manager](#version-manager)
    *   [Boilerplate](#boilerplate)
*   [Vim](#vim)
*   [Resource](#resource)

## Wishlist

Have a problem a plugin can solve? Add it to the [nvim-lua wishlist (⭐186)](https://github.com/nvim-lua/wishlist).

## UI

Neovim supports a wide variety of UI's.
You can find them listed on the [Neovim wiki (⭐59k)](https://github.com/neovim/neovim/wiki/Related-projects#gui)

## Plugin

### Plugin Manager

*   [wbthomason/packer.nvim (⭐4.5k)](https://github.com/wbthomason/packer.nvim) - A use-package inspired plugin manager. Uses native packages, supports Luarocks dependencies, written in Lua, allows for expressive config.
*   [savq/paq-nvim (⭐520)](https://github.com/savq/paq-nvim) - Neovim package manager written in Lua.
*   [NTBBloodbath/cheovim (⭐223)](https://github.com/NTBBloodbath/cheovim) - Neovim configuration switcher written in Lua. Inspired by chemacs.
*   [chiyadev/dep (⭐29)](https://github.com/chiyadev/dep) - An alternative to packer.nvim. It was built to be even better and easier to use. Context can be found [here](https://chiya.dev/posts/2021-11-27-why-package-manager).

### LSP

#### (requires Neovim 0.5)

*   [neovim/nvim-lspconfig (⭐6k)](https://github.com/neovim/nvim-lspconfig) - Quickstart configurations for the LSP client.
*   [nvim-lua/lsp-status.nvim (⭐535)](https://github.com/nvim-lua/lsp-status.nvim) - This is a plugin/library for generating statusline components from the built-in LSP client.
*   [RishabhRD/nvim-lsputils (⭐383)](https://github.com/RishabhRD/nvim-lsputils) - Better defaults for nvim-lsp actions.
*   [glepnir/lspsaga.nvim (⭐2.2k)](https://github.com/glepnir/lspsaga.nvim) - A light-weight LSP plugin based on Neovim's built-in LSP with a highly performant UI.
*   [kosayoda/nvim-lightbulb (⭐524)](https://github.com/kosayoda/nvim-lightbulb) - The plugin shows a lightbulb in the sign column whenever a `textDocument/codeAction` is available at the current cursor position.
*   [onsails/lspkind.nvim (⭐761)](https://github.com/onsails/lspkind.nvim) - The plugin adds vscode-like icons to Neovim LSP completions.
*   [ojroques/nvim-lspfuzzy (⭐282)](https://github.com/ojroques/nvim-lspfuzzy) - A small plugin to make the LSP client use FZF.
*   [gfanto/fzf-lsp.nvim (⭐161)](https://github.com/gfanto/fzf-lsp.nvim) - Enable the power of FZF fuzzy search for the Neovim built in LSP.
*   [ray-x/lsp\_signature.nvim (⭐1.2k)](https://github.com/ray-x/lsp_signature.nvim) - LSP signature hint when you type.
*   [smjonas/inc-rename.nvim (⭐230)](https://github.com/smjonas/inc-rename.nvim) - Provides an incremental LSP rename command based on Neovim's command-preview feature.
*   [rmagatti/goto-preview (⭐385)](https://github.com/rmagatti/goto-preview) - Previewing native LSP's goto definition calls in floating windows.
*   [jubnzv/virtual-types.nvim (⭐204)](https://github.com/jubnzv/virtual-types.nvim) - Show type annotations as virtual text.
*   [jose-elias-alvarez/typescript.nvim (⭐255)](https://github.com/jose-elias-alvarez/typescript.nvim) - Utilities to improve the TypeScript development experience for Neovim's built-in LSP client.
*   [ray-x/navigator.lua (⭐827)](https://github.com/ray-x/navigator.lua) - Learn existing code quickly and navigate code like a breeze. A swiss army knife makes exploring LSP and 🌲Treesitter symbols a piece of 🍰.
*   [simrat39/symbols-outline.nvim (⭐1.1k)](https://github.com/simrat39/symbols-outline.nvim) - A tree like view for symbols using the Language Server Protocol. Supports all your favourite languages.
*   [tamago324/nlsp-settings.nvim (⭐203)](https://github.com/tamago324/nlsp-settings.nvim) - A plugin for setting LSP with JSON files.
*   [stevearc/aerial.nvim (⭐637)](https://github.com/stevearc/aerial.nvim) - A code outline window for skimming and quick navigation.
*   [jose-elias-alvarez/null-ls.nvim (⭐2.2k)](https://github.com/jose-elias-alvarez/null-ls.nvim) - Use Neovim as a language server to inject LSP diagnostics, code actions, and more via Lua.
*   [jakewvincent/texmagic.nvim (⭐26)](https://github.com/jakewvincent/texmagic.nvim) - Enhance the lspconfig settings for Texlab by defining any number of custom LaTeX build engines and selecting them with magic comments.
*   [nanotee/nvim-lsp-basics (⭐26)](https://github.com/nanotee/nvim-lsp-basics) - Basic wrappers for LSP features.
*   [weilbith/nvim-code-action-menu (⭐400)](https://github.com/weilbith/nvim-code-action-menu) - A floating pop-up menu for code actions to show code action information and a diff preview.
*   [mfussenegger/nvim-lint (⭐458)](https://github.com/mfussenegger/nvim-lint) - An asynchronous linter plugin, complementary to the built-in Language Server Protocol support.
*   [b0o/SchemaStore.nvim (⭐305)](https://github.com/b0o/SchemaStore.nvim) - Provide access to the [SchemaStore (⭐2k)](https://github.com/SchemaStore/schemastore) catalog.
*   [ldelossa/litee.nvim (⭐294)](https://github.com/ldelossa/litee.nvim) - Neovim's missing IDE features.
*   [j-hui/fidget.nvim (⭐819)](https://github.com/j-hui/fidget.nvim) - Standalone UI for LSP progress.
*   [scalameta/nvim-metals (⭐251)](https://github.com/scalameta/nvim-metals) - Neovim plugin for Metals, the Scala language server, using Neovim's builtin LSP.
*   [junnplus/nvim-lsp-setup (⭐189)](https://github.com/Junnplus/nvim-lsp-setup) - A simple wrapper for nvim-lspconfig and nvim-lsp-installer to easily setup LSP servers.
*   [amrbashir/nvim-docs-view (⭐56)](https://github.com/amrbashir/nvim-docs-view) - Display LSP hover documentation in a side panel.
*   [mfussenegger/nvim-jdtls (⭐460)](https://github.com/mfussenegger/nvim-jdtls) - Extensions for the built-in LSP support for eclipse.jdt.ls.
*   [Kasama/nvim-custom-diagnostic-highlight (⭐32)](https://github.com/Kasama/nvim-custom-diagnostic-highlight) - Inline diagnostics popup-highlight much like coc-nvim but based on `vim.diagnostic`.
*   [MrcJkb/haskell-tools.nvim (⭐89)](https://github.com/MrcJkb/haskell-tools.nvim) - Seamless integration of Neovim with Haskell development tools like haskell-language-server and Hoogle.
*   [ranjithshegde/ccls.nvim (⭐34)](https://github.com/ranjithshegde/ccls.nvim) - Use off-spec extensions of ccls LSP and browse AST.

##### LSP Installer

*   [anott03/nvim-lspinstall (⭐88)](https://github.com/anott03/nvim-lspinstall) - Easy to install language servers.
*   [alexaandru/nvim-lspupdate (⭐88)](https://github.com/alexaandru/nvim-lspupdate) - Updates installed (or auto installs if missing) LSP servers.
*   [williamboman/mason.nvim (⭐2.4k)](https://github.com/williamboman/mason.nvim) - Portable package manager that runs everywhere Neovim runs. Easily install and manage LSP servers, DAP servers, linters, and formatters.

##### Diagnostics

*   [andrewferrier/textobj-diagnostic (⭐83)](https://github.com/andrewferrier/textobj-diagnostic.nvim) - Text object for diagnostics (such as those generated by LSP servers).
*   [\~whynothugo/lsp\_lines.nvim](https://git.sr.ht/\~whynothugo/lsp_lines.nvim) - Render diagnostics using virtual lines on top of the real line of code.
*   [onsails/diaglist.nvim (⭐124)](https://github.com/onsails/diaglist.nvim) - Live render workspace diagnostics in quickfix, buffer diagnostics in loclist.
*   [folke/trouble.nvim (⭐2.3k)](https://github.com/folke/trouble.nvim) - A pretty diagnostics list to help you solve all the trouble your code is causing.
*   [folke/lsp-colors.nvim (⭐377)](https://github.com/folke/lsp-colors.nvim) - A plugin that adds missing LSP diagnostics highlight groups for color schemes that don't yet support the builtin LSP client.

### Completion

*   [ms-jpq/coq\_nvim (⭐2.7k)](https://github.com/ms-jpq/coq_nvim) - Fast as FUCK Neovim completion. SQLite, concurrent scheduler, hundreds of hours of optimization.
*   [jameshiew/nvim-magic (⭐170)](https://github.com/jameshiew/nvim-magic) - Framework for integrating AI code assistance.
*   [hrsh7th/nvim-cmp (⭐4.2k)](https://github.com/hrsh7th/nvim-cmp) - A completion plugin written in Lua. New version of nvim-compe.
    *   [lukas-reineke/cmp-under-comparator (⭐100)](https://github.com/lukas-reineke/cmp-under-comparator) - A nvim-cmp function for better sorting.
*   [echasnovski/mini.nvim#mini.completion (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-completion.md) - Module of `mini.nvim` for asynchronous two-stage completion. Supports showing completion item info and independent function signature.
*   [noib3/nvim-compleet (⭐511)](https://github.com/noib3/nvim-compleet) - A Neovim autocompletion framework written in Rust.
*   [vigoux/complementree.nvim (⭐42)](https://github.com/vigoux/complementree.nvim) - Light and synchronous completion plugin based on tree-sitter and with a functional-programming interface.
*   [GitHub/copilot.vim (⭐3.7k)](https://github.com/github/copilot.vim) - GitHub Copilot.
*   [simrat39/rust-tools.nvim (⭐1.3k)](https://github.com/simrat39/rust-tools.nvim) - Tools for better development in Rust using Neovim's builtin LSP.

### Programming Languages Support

*   [Julian/lean.nvim (⭐101)](https://github.com/Julian/lean.nvim) - Neovim support for the [Lean Theorem Prover](https://leanprover.github.io/).
*   [akinsho/flutter-tools.nvim (⭐394)](https://github.com/akinsho/flutter-tools.nvim) - Build Flutter and Dart applications using the native LSP.
*   [gbprod/phpactor.nvim (⭐13)](https://github.com/gbprod/phpactor.nvim) - Lua version of the Phpactor Vim plugin to take advantage of the latest Neovim features.
*   [brendalf/mix.nvim (⭐17)](https://github.com/brendalf/mix.nvim) - Mix (from Elixir) wrapper plugin.
*   [AckslD/swenv.nvim (⭐56)](https://github.com/AckslD/swenv.nvim) - Tiny plugin to quickly switch Python virtual environments without restarting.
*   [gennaro-tedesco/nvim-jqx (⭐175)](https://github.com/gennaro-tedesco/nvim-jqx) - Interactive interface for JSON files.
*   [nanotee/sqls.nvim (⭐108)](https://github.com/nanotee/sqls.nvim) - SQL database connection plugin + LSP client.

#### Golang

*   [ray-x/go.nvim (⭐751)](https://github.com/ray-x/go.nvim) - Golang plugin based on lsp and Treesitter.
*   [crusj/structrue-go.nvim (⭐20)](https://github.com/crusj/structrue-go.nvim) - A better structured display of Golang symbols information.
*   [crispgm/nvim-go (⭐88)](https://github.com/crispgm/nvim-go) - A minimal implementation of Golang development plugin.
*   [edolphin-ydf/goimpl.nvim (⭐19)](https://github.com/edolphin-ydf/goimpl.nvim) - Generate interface stubs for a type.
*   [olexsmir/gopher.nvim (⭐58)](https://github.com/olexsmir/gopher.nvim/) - Plugin for making Golang development easiest.
*   [rafaelsq/nvim-goc.lua (⭐24)](https://github.com/rafaelsq/nvim-goc.lua) - Highlight your buffer with Golang Code Coverage.
*   [crusj/hierarchy-tree-go.nvim (⭐6)](https://github.com/crusj/hierarchy-tree-go.nvim) - Neovim plugin for Golang, callHierarchy UI tree.

#### YAML

*   [someone-stole-my-name/yaml-companion.nvim (⭐57)](https://github.com/someone-stole-my-name/yaml-companion.nvim) - Get, set and autodetect YAML schemas in your buffers.
*   [cuducos/yaml.nvim (⭐85)](https://github.com/cuducos/yaml.nvim) - Utils to work with YAML files.

#### Web Development

*   [NTBBloodbath/rest.nvim (⭐539)](https://github.com/NTBBloodbath/rest.nvim) - A fast Neovim HTTP client written in Lua.
*   [ray-x/web-tools.nvim (⭐47)](https://github.com/ray-x/web-tools.nvim) - Launch a local development server with live reload feature for static & dynamic pages, HTTP & CSS tag rename with LSP.

#### Markdown and LaTeX

*   [ellisonleao/glow.nvim (⭐730)](https://github.com/ellisonleao/glow.nvim) - Markdown preview using glow.
*   [davidgranstrom/nvim-markdown-preview (⭐85)](https://github.com/davidgranstrom/nvim-markdown-preview) - Markdown preview in the browser using pandoc and live-server through Neovim's job-control API.
*   [jghauser/auto-pandoc.nvim (⭐17)](https://github.com/jghauser/auto-pandoc.nvim) - Easy pandoc conversion leveraging yaml blocks.
*   [jghauser/follow-md-links.nvim (⭐70)](https://github.com/jghauser/follow-md-links.nvim) - Press enter to follow internal markdown links.
*   [jubnzv/mdeval.nvim (⭐95)](https://github.com/jubnzv/mdeval.nvim) - Evaluate code blocks inside markdown documents.
*   [kdheepak/panvimdoc (⭐116)](https://github.com/kdheepak/panvimdoc) - A pandoc to vimdoc GitHub action.
*   [frabjous/knap (⭐139)](https://github.com/frabjous/knap) - Plugin for creating automatic updating-as-you-type previews for markdown, LaTeX and other documents.
*   [jbyuki/carrot.nvim (⭐17)](https://github.com/jbyuki/carrot.nvim) - Markdown evaluator Lua code blocks.
*   [AckslD/nvim-FeMaco.lua (⭐181)](https://github.com/AckslD/nvim-FeMaco.lua) - Catalyze your Fenced Markdown Code-block editing.
*   [NFrid/markdown-togglecheck (⭐1)](https://github.com/NFrid/markdown-togglecheck) - Simple Neovim plugin for toggling check boxes using Treesitter.

### Language

*   [lewis6991/spellsitter.nvim (⭐443)](https://github.com/lewis6991/spellsitter.nvim) - Enable Neovim's spell checker with tree-sitter.
*   [potamides/pantran.nvim (⭐115)](https://github.com/potamides/pantran.nvim) - Translate your text with an interactive translation window.

### Syntax

*   [nvim-treesitter/nvim-treesitter (⭐5.2k)](https://github.com/nvim-treesitter/nvim-treesitter) - Neovim Treesitter configurations and abstraction layer.
*   [nvim-treesitter/nvim-treesitter-textobjects (⭐915)](https://github.com/nvim-treesitter/nvim-treesitter-textobjects) - Create your own textobjects using tree-sitter queries.
*   [RRethy/nvim-treesitter-textsubjects (⭐304)](https://github.com/RRethy/nvim-treesitter-textsubjects) - Location and syntax aware text objects which *do what you mean*.
*   [kylechui/nvim-surround (⭐977)](https://github.com/kylechui/nvim-surround) - A plugin for adding/changing/deleting surrounding delimiter pairs.
*   [echasnovski/mini.nvim#mini.surround (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-surround.md) - Module of `mini.nvim` for working with text surroundings (add, delete, replace, find, highlight). Supports dot-repeat, different search methods, "last"/"next" extended mappings, tree-sitter integration, and more.
*   [m-demare/hlargs.nvim (⭐210)](https://github.com/m-demare/hlargs.nvim) - Highlight arguments' definitions and usages, using Treesitter.

### Snippet

*   [norcalli/snippets.nvim (⭐244)](https://github.com/norcalli/snippets.nvim) - Snippets in Lua.
*   [L3MON4D3/LuaSnip (⭐1.5k)](https://github.com/L3MON4D3/LuaSnip) - A snippet engine written in Lua.
*   [smjonas/snippet-converter.nvim (⭐94)](https://github.com/smjonas/snippet-converter.nvim) - Convert snippets between the most common snippet formats and modify them using a few lines of Lua code.
*   [dcampos/nvim-snippy (⭐132)](https://github.com/dcampos/nvim-snippy) - Snippet plugin written in Lua with support for [vim-snippets (⭐4.4k)](https://github.com/honza/vim-snippets).
*   [ellisonleao/carbon-now.nvim (⭐59)](https://github.com/ellisonleao/carbon-now.nvim) - Create beautiful code snippets directly from Neovim.

### Register

*   [gennaro-tedesco/nvim-peekup (⭐190)](https://github.com/gennaro-tedesco/nvim-peekup) - Dynamically interact with Vim registers.
*   [tversteeg/registers.nvim (⭐476)](https://github.com/tversteeg/registers.nvim) - Non-obtrusive minimal preview of Vim registers.
*   [acksld/nvim-neoclip.lua (⭐540)](https://github.com/AckslD/nvim-neoclip.lua) - Clipboard manager Neovim plugin with telescope integration.

### Marks

*   [chentoast/marks.nvim (⭐409)](https://github.com/chentoast/marks.nvim) - A better user experience for viewing and interacting with Vim marks.
*   [ThePrimeagen/harpoon (⭐1.4k)](https://github.com/ThePrimeagen/harpoon) - A per project, auto updating and editable marks utility for fast file navigation.
*   [ofirgall/open.nvim (⭐4)](https://github.com/ofirgall/open.nvim) - Open the current word with custom openers, GitHub shorthand for example.

### Search

*   [kevinhwang91/nvim-hlslens (⭐488)](https://github.com/kevinhwang91/nvim-hlslens) - Helps you better glance searched information, seamlessly jump matched instances.
*   [rktjmp/highlight-current-n.nvim (⭐55)](https://github.com/rktjmp/highlight-current-n.nvim) - Highlights the current /, ? or \* match under your cursor when pressing n or N and gets out of the way afterwards.
*   [gaborvecsei/memento.nvim (⭐27)](https://github.com/gaborvecsei/memento.nvim) - Keeps track of your visited file history after a buffer is closed. Reopen files more easily.
*   [ray-x/sad.nvim (⭐57)](https://github.com/ray-x/sad.nvim) - Space Age seD in neovim. Batch file edit tool, a wrapper for [sad (⭐961)](https://github.com/ms-jpq/sad)

### Fuzzy Finder

*   [nvim-telescope/telescope.nvim (⭐7.8k)](https://github.com/nvim-telescope/telescope.nvim) - Telescope.nvim is a highly [extendable (⭐7.8k)](https://github.com/nvim-telescope/telescope.nvim/wiki/Extensions) fuzzy finder over lists. Built on the latest awesome features from Neovim core. Telescope is centered around modularity, allowing for easy customization.
*   [vijaymarupudi/nvim-fzf (⭐274)](https://github.com/vijaymarupudi/nvim-fzf) - A Lua API for using FZF (Neovim >= 0.5). Allows for full asynchronicity for UI speed and usability.
*   [camspiers/snap (⭐378)](https://github.com/camspiers/snap) - An extensible fuzzy finder. Similar to Telescope, and optimized for performance, especially when grepping in large codebases.
*   [ibhagwan/fzf-lua (⭐825)](https://github.com/ibhagwan/fzf-lua) - The Lua version of `fzf.vim`, high-performance and fully async, supports `nvim-web-devicons`, git indicators, LSP, quickfix/location lists and more. Also supports [`skim`](https://github.com/lotabout/skim) as its fzf binary.
*   [jvgrootveld/telescope-zoxide (⭐142)](https://github.com/jvgrootveld/telescope-zoxide) - Telescope integration for [zoxide (⭐8.1k)](https://github.com/ajeetdsouza/zoxide), a smart directory picker that tracks your usage.
*   [echasnovski/mini.nvim#mini.fuzzy (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-fuzzy.md) - Module of `mini.nvim` with functions to perform fuzzy matching of one string to others along with fast Telescope sorter.

### File Explorer

*   [kyazdani42/nvim-tree.lua (⭐3.6k)](https://github.com/kyazdani42/nvim-tree.lua) - A simple and fast file explorer tree.
*   [luukvbaal/nnn.nvim (⭐248)](https://github.com/luukvbaal/nnn.nvim) - File explorer powered by [nnn (⭐15k)](https://github.com/jarun/nnn) and Lua.
*   [tamago324/lir.nvim (⭐249)](https://github.com/tamago324/lir.nvim) - Simple file explorer.
*   [TimUntersberger/neofs (⭐48)](https://github.com/TimUntersberger/neofs) - A file manager written in Lua.
*   [kevinhwang91/rnvimr (⭐578)](https://github.com/kevinhwang91/rnvimr) - A simple yet amazing file explorer.
*   [Xuyuanp/yanil (⭐94)](https://github.com/Xuyuanp/yanil) - Yet Another Nerdtree In Lua.
*   [ms-jpq/chadtree (⭐1.4k)](https://github.com/ms-jpq/chadtree) - File manager. Better than NERDTree.
*   [is0n/fm-nvim (⭐155)](https://github.com/is0n/fm-nvim) - Neovim plugin that lets you use your favorite terminal file managers (and fuzzy finders).
*   [nvim-neo-tree/neo-tree.nvim (⭐887)](https://github.com/nvim-neo-tree/neo-tree.nvim) - Neo-tree is a Neovim plugin to browse the file system and other tree like structures in whatever style suits you, including sidebars, floating windows, netrw split style, or all of them at once.
*   [elihunter173/dirbuf.nvim (⭐307)](https://github.com/elihunter173/dirbuf.nvim) - A file manager which lets you edit your filesystem like you edit text.
*   [theblob42/drex.nvim (⭐35)](https://github.com/TheBlob42/drex.nvim) - A simple and configurable file explorer written in Lua.
*   [SidOfc/carbon.nvim (⭐78)](https://github.com/SidOfc/carbon.nvim) - The simple directory tree viewer written in Lua.
*   [kiran94/s3edit.nvim (⭐22)](https://github.com/kiran94/s3edit.nvim) - Edit files from Amazon S3 directly from Neovim.

### Project

*   [shaeinst/penvim (⭐28)](https://github.com/shaeinst/penvim) - Project's Root Directory and Documents Indentation detector with project based config loader.
*   [nyngwang/NeoRoot.lua (⭐53)](https://github.com/nyngwang/NeoRoot.lua) - Change your current working directory to the buffer your cursor is on, and try to go up 2 levels but stop after it encounters one of the project roots you define.
*   [windwp/nvim-projectconfig (⭐65)](https://github.com/windwp/nvim-projectconfig) - Load Neovim config depend on project directory.
*   [windwp/nvim-spectre (⭐639)](https://github.com/windwp/nvim-spectre) - Search and replace panel.
*   [ahmedkhalf/project.nvim (⭐639)](https://github.com/ahmedkhalf/project.nvim) - An all in one Neovim plugin that provides superior project management.
*   [klen/nvim-config-local (⭐62)](https://github.com/klen/nvim-config-local) - Secure load local config files from working directories.
*   [cljoly/telescope-repo.nvim](https://cj.rs/telescope-repo-nvim/) - Telescope picker to jump to any repository (git or other) on the file system.
*   [MunifTanjim/exrc.nvim (⭐41)](https://github.com/MunifTanjim/exrc.nvim) - Secure Project Local Config.

### Color

*   [NvChad/nvim-colorizer.lua (⭐175)](https://github.com/NvChad/nvim-colorizer.lua) - A high-performance color highlighter which has no external dependencies!.
*   [sunjon/Shade.nvim (⭐358)](https://github.com/sunjon/Shade.nvim) - Shade is a Neovim plugin that dims your inactive windows, making it easier to see the active window at a glance.
*   [winston0410/range-highlight.nvim (⭐132)](https://github.com/winston0410/range-highlight.nvim) - An extremely lightweight plugin (\~ 120loc) that highlights ranges you have entered in commandline.
*   [xiyaowong/nvim-transparent (⭐232)](https://github.com/xiyaowong/nvim-transparent) - Make your Neovim transparent.
*   [folke/twilight.nvim (⭐619)](https://github.com/folke/twilight.nvim) - Dim inactive portions of the code you're editing using TreeSitter.
*   [koenverburg/peepsight.nvim (⭐28)](https://github.com/koenverburg/peepsight.nvim) - Focus only the function your cursor is in.
*   [uga-rosa/ccc.nvim (⭐264)](https://github.com/uga-rosa/ccc.nvim) - Super powerful color picker / colorizer plugin.
*   [ziontee113/color-picker.nvim (⭐149)](https://github.com/ziontee113/color-picker.nvim) - Plugin that lets users choose & modify RGB/HSL/HEX colors inside Neovim.
*   [lcheylus/overlength.nvim (⭐27)](https://github.com/lcheylus/overlength.nvim) - A small plugin to highlight too long lines.
*   [brenoprata10/nvim-highlight-colors (⭐100)](https://github.com/brenoprata10/nvim-highlight-colors) - A plugin to highlight colors with Neovim.
*   [nvim-colortils/colortils.nvim (⭐170)](https://github.com/nvim-colortils/colortils.nvim) - A plugin providing utils to work with colors (picker, conversion) inside Neovim.

### Colorscheme

#### Tree-sitter Supported Colorscheme

Tree-sitter is a new system introduced in Neovim 0.5 that incrementally parses your code into a tree that works, even with errors in your syntax. These colorschemes have specifically set colors for Tree-sitter highlight groups. Vim colorschemes will work with the new groups out of the box.

*   [shaeinst/roshnivim-cs (⭐47)](https://github.com/shaeinst/roshnivim-cs) - Colorscheme written in Lua, specially made for roshnivim with Tree-sitter support.
*   [rafamadriz/neon (⭐107)](https://github.com/rafamadriz/neon) - Customizable colorscheme with excellent italic and bold support, dark and light variants. Made to work and look good with Tree-sitter.
*   [tomasiser/vim-code-dark (⭐809)](https://github.com/tomasiser/vim-code-dark) - A dark color scheme heavily inspired by the look of the Dark+ scheme of Visual Studio Code.
*   [Mofiqul/vscode.nvim (⭐310)](https://github.com/Mofiqul/vscode.nvim) - A Lua port of vim-code-dark colorscheme with vscode light and dark theme.
*   [marko-cerovac/material.nvim (⭐630)](https://github.com/marko-cerovac/material.nvim) - Material.nvim is a highly configurable colorscheme written in Lua and based on the material palette.
*   [bluz71/vim-nightfly-colors (⭐502)](https://github.com/bluz71/vim-nightfly-colors) - A dark midnight colorscheme with modern Neovim support including Tree-sitter.
*   [bluz71/vim-moonfly-colors (⭐505)](https://github.com/bluz71/vim-moonfly-colors) - A dark charcoal colorscheme with modern Neovim support including Tree-sitter.
*   [ChristianChiarulli/nvcode-color-schemes.vim (⭐275)](https://github.com/ChristianChiarulli/nvcode-color-schemes.vim) - Nvcode, onedark, nord colorschemes with Tree-sitter support.
*   [folke/tokyonight.nvim (⭐2.5k)](https://github.com/folke/tokyonight.nvim) - A clean, dark and light Neovim theme written in Lua, with support for LSP, Tree-sitter and lots of plugins.
*   [sainnhe/sonokai (⭐1k)](https://github.com/sainnhe/sonokai) - High Contrast & Vivid Color Scheme based on Monokai Pro.
*   [kyazdani42/blue-moon (⭐111)](https://github.com/kyazdani42/blue-moon) - A dark color scheme derived from palenight and carbonight.
*   [mhartington/oceanic-next (⭐1k)](https://github.com/mhartington/oceanic-next) - Oceanic Next theme.
*   [glepnir/zephyr-nvim (⭐251)](https://github.com/glepnir/zephyr-nvim) - A dark colorscheme with Tree-sitter support.
*   [rockerBOO/boo-colorscheme-nvim (⭐95)](https://github.com/rockerBOO/boo-colorscheme-nvim) - A colorscheme with handcrafted support for LSP, Tree-sitter.
*   [jim-at-jibba/ariake-vim-colors (⭐24)](https://github.com/jim-at-jibba/ariake-vim-colors) - A port of the great Atom theme. Dark and light with Tree-sitter support.
*   [Th3Whit3Wolf/onebuddy (⭐91)](https://github.com/Th3Whit3Wolf/onebuddy) - Light and dark atom one theme.
*   [ishan9299/modus-theme-vim (⭐110)](https://github.com/ishan9299/modus-theme-vim) - This is a color scheme developed by Protesilaos Stavrou for emacs.
*   [sainnhe/edge (⭐650)](https://github.com/sainnhe/edge) - Clean & Elegant Color Scheme inspired by Atom One and Material.
*   [theniceboy/nvim-deus (⭐46)](https://github.com/theniceboy/nvim-deus) - Vim-deus with Tree-sitter support.
*   [bkegley/gloombuddy (⭐28)](https://github.com/bkegley/gloombuddy) - Gloom inspired theme.
*   [Th3Whit3Wolf/one-nvim (⭐90)](https://github.com/Th3Whit3Wolf/one-nvim) - An Atom One inspired dark and light colorscheme.
*   [PHSix/nvim-hybrid (⭐17)](https://github.com/PHSix/nvim-hybrid) - A Neovim colorscheme write in Lua.
*   [Th3Whit3Wolf/space-nvim (⭐28)](https://github.com/Th3Whit3Wolf/space-nvim) - A spacemacs inspired dark and light colorscheme.
*   [yonlu/omni.vim (⭐52)](https://github.com/yonlu/omni.vim) - Omni color scheme for Vim.
*   [ray-x/aurora (⭐174)](https://github.com/ray-x/aurora) - A 24-bit dark theme with Tree-sitter and LSP support.
*   [ray-x/starry.nvim (⭐79)](https://github.com/ray-x/starry.nvim) - A collection of modern Neovim colorschemes: material, moonlight, dracula (blood), monokai, mariana, emerald, earlysummer, middlenight\_blue, darksolar.
*   [tanvirtin/monokai.nvim (⭐198)](https://github.com/tanvirtin/monokai.nvim) - Monokai theme written in Lua.
*   [ofirgall/ofirkai.nvim (⭐31)](https://github.com/ofirgall/ofirkai.nvim) - Monokai theme that aims to feel like Sublime Text.
*   [savq/melange (⭐320)](https://github.com/savq/melange) - Dark color scheme and Vim 🗡️.
*   [RRethy/nvim-base16 (⭐286)](https://github.com/RRethy/nvim-base16) - Neovim plugin for building base16 colorschemes. Includes support for Treesitter and LSP highlight groups.
*   [fenetikm/falcon (⭐608)](https://github.com/fenetikm/falcon) - A colour scheme for terminals, Vim and friends.
*   [andersevenrud/nordic.nvim (⭐138)](https://github.com/andersevenrud/nordic.nvim) - A nord-esque colorscheme.
*   [shaunsingh/nord.nvim (⭐491)](https://github.com/shaunsingh/nord.nvim) - Neovim theme based off of the Nord Color Palette.
*   [ishan9299/nvim-solarized-lua (⭐121)](https://github.com/ishan9299/nvim-solarized-lua) - Solarized colorscheme in Lua (Neovim >= 0.5).
*   [shaunsingh/moonlight.nvim (⭐125)](https://github.com/shaunsingh/moonlight.nvim) - Port of VSCode's Moonlight colorscheme, written in Lua with built-in support for native LSP, Tree-sitter and many more plugins.
*   [navarasu/onedark.nvim (⭐657)](https://github.com/navarasu/onedark.nvim) - A One Dark Theme (Neovim >= 0.5) written in Lua based on Atom's One Dark Theme.
*   [lourenci/github-colors (⭐57)](https://github.com/lourenci/github-colors) - GitHub colors leveraging Tree-sitter to get 100% accuracy.
*   [sainnhe/gruvbox-material (⭐1.1k)](https://github.com/sainnhe/gruvbox-material) - Gruvbox modification with softer contrast and Tree-sitter support.
*   [sainnhe/everforest (⭐1.4k)](https://github.com/sainnhe/everforest) - A green based colorscheme designed to be warm, soft and easy on the eyes.
*   [NTBBloodbath/doom-one.nvim (⭐121)](https://github.com/NTBBloodbath/doom-one.nvim) - Lua port of doom-emacs' doom-one.
*   [dracula/vim (⭐1.2k)](https://github.com/dracula/vim) - Famous beautiful dark powered theme.
*   [Mofiqul/dracula.nvim (⭐299)](https://github.com/Mofiqul/dracula.nvim) - Dracula colorscheme for neovim written in Lua.
*   [yashguptaz/calvera-dark.nvim (⭐109)](https://github.com/yashguptaz/calvera-dark.nvim) - A port of [VSCode Calvara Dark (⭐11)](https://github.com/saurabhdaware/vscode-calvera-dark) Theme to Neovim with Tree-sitter and many other plugins support.
*   [nxvu699134/vn-night.nvim (⭐27)](https://github.com/nxvu699134/vn-night.nvim) - A dark Neovim colorscheme written in Lua. Support built-in LSP and Tree-sitter.
*   [adisen99/codeschool.nvim (⭐26)](https://github.com/adisen99/codeschool.nvim) - Codeschool colorscheme written in Lua with Tree-sitter and built-in lsp support.
*   [projekt0n/github-nvim-theme (⭐1.1k)](https://github.com/projekt0n/github-nvim-theme) - A GitHub theme, kitty, alacritty written in Lua. Support built-in LSP and Tree-sitter.
*   [kdheepak/monochrome.nvim (⭐34)](https://github.com/kdheepak/monochrome.nvim) - A 16 bit monochrome colorscheme that uses hsluv for perceptually distinct gray colors, with support for Tree-sitter and other commonly used plugins.
*   [rose-pine/neovim (⭐491)](https://github.com/rose-pine/neovim) - All natural pine, faux fur and a bit of soho vibes for the classy minimalist.
*   [mcchrish/zenbones.nvim (⭐342)](https://github.com/mcchrish/zenbones.nvim) - A collection of Vim/Neovim colorschemes designed to highlight code using contrasts and font variations.
*   [catppuccin/nvim (⭐1.7k)](https://github.com/catppuccin/nvim) - Warm mid-tone dark theme to show off your vibrant self! with support for native LSP, Tree-sitter, and more 🍨!
*   [FrenzyExists/aquarium-vim (⭐195)](https://github.com/FrenzyExists/aquarium-vim) - A dark, yet vibrant colorscheme.
*   [EdenEast/nightfox.nvim (⭐1.5k)](https://github.com/EdenEast/nightfox.nvim) - A soft dark, fully customizable Neovim theme, with support for lsp, treesitter and a variety of plugins.
*   [kvrohit/substrata.nvim (⭐86)](https://github.com/kvrohit/substrata.nvim) - A cold, dark color scheme written in Lua ported from [arzg/vim-substrata (⭐177)](https://github.com/arzg/vim-substrata) theme.
*   [ldelossa/vimdark (⭐61)](https://github.com/ldelossa/vimdark) - A minimal Vim theme for night time. Loosely based on vim-monotonic and chrome's dark reader extension. A light theme is included as well for the day time.
*   [Everblush/everblush.nvim (⭐111)](https://github.com/Everblush/everblush.nvim) - A dark, vibrant and beautiful colorscheme written in Lua.
*   [adisen99/apprentice.nvim (⭐24)](https://github.com/adisen99/apprentice.nvim) - Colorscheme written in Lua based on the [Apprentice (⭐804)](https://github.com/romainl/Apprentice) color pattete with Tree-sitter and built-in lsp support.
*   [olimorris/onedarkpro.nvim (⭐344)](https://github.com/olimorris/onedarkpro.nvim) - One Dark Pro theme, written in Lua and based on the VS Code theme. Includes dark and light themes with completely customisable colors, styles and highlights.
*   [rmehri01/onenord.nvim (⭐295)](https://github.com/rmehri01/onenord.nvim) - A Neovim theme that combines the Nord and Atom One Dark color palettes for a more vibrant programming experience.
*   [RishabhRD/gruvy (⭐14)](https://github.com/RishabhRD/gruvy) - Gruvbuddy without colorbuddy using Lush.
*   [echasnovski/mini.nvim#minischeme (⭐1.1k)](https://github.com/echasnovski/mini.nvim#plugin-colorschemes) - Color scheme of `mini.nvim` which is a variant of base16 with accent colors chosen according to optimal perceptual uniformity.
*   [luisiacc/gruvbox-baby (⭐207)](https://github.com/luisiacc/gruvbox-baby) - A modern gruvbox theme with full treesitter support.
*   [titanzero/zephyrium (⭐15)](https://github.com/titanzero/zephyrium) - A zephyr-esque theme, written in Lua, with TreeSitter support.
*   [rebelot/kanagawa.nvim (⭐1.5k)](https://github.com/rebelot/kanagawa.nvim) - Neovim dark colorscheme inspired by the colors of the famous painting by Katsushika Hokusai.
*   [tiagovla/tokyodark.nvim (⭐262)](https://github.com/tiagovla/tokyodark.nvim) - A clean dark theme written in Lua (Neovim >= 0.5) and above.
*   [cpea2506/one\_monokai.nvim (⭐37)](https://github.com/cpea2506/one_monokai.nvim) - One Monokai theme written in Lua.
*   [phha/zenburn.nvim (⭐32)](https://github.com/phha/zenburn.nvim) - A low-contrast dark colorscheme with support for various plugins.
*   [kvrohit/rasmus.nvim (⭐58)](https://github.com/kvrohit/rasmus.nvim) - A dark color scheme written in Lua ported from [rsms/sublime-theme (⭐157)](https://github.com/rsms/sublime-theme) theme.
*   [chrsm/paramount-ng.nvim (⭐7)](https://github.com/chrsm/paramount-ng.nvim) - A dark color scheme written using Lush. Treesitter supported.
*   [kaiuri/nvim-juliana (⭐42)](https://github.com/kaiuri/nvim-juliana) - Port of Sublime's Mariana Theme to Neovim for short attention span developers with Tree-sitter support.
*   [lmburns/kimbox (⭐26)](https://github.com/lmburns/kimbox) - A colorscheme with a dark background, and vibrant foreground that is centered around the color brown. A modification of [Kimbie Dark](https://marketplace.visualstudio.com/items?itemName=dnamsons.kimbie-dark-plus).
*   [rockyzhang24/arctic.nvim (⭐29)](https://github.com/rockyzhang24/arctic.nvim) - A Neovim colorscheme ported from VSCode Dark+ theme with the strict and precise color picking for both the editor and UI.
*   [meliora-theme/neovim (⭐36)](https://github.com/meliora-theme/neovim) - Warm and cozy theme.
*   [Yazeed1s/minimal.nvim (⭐84)](https://github.com/yazeed1s/minimal.nvim) - Two tree-sitter supported colorschemes that are inspired by base16-tomorrow-night and monokai-pro.
*   [lewpoly/sherbet.nvim (⭐32)](https://github.com/lewpoly/sherbet.nvim) - A soothing colorscheme with support for popular plugins and tree-sitter.
*   [Mofiqul/adwaita.nvim (⭐99)](https://github.com/Mofiqul/adwaita.nvim) - Colorscheme based on GNOME Adwaita syntax with support for popular plugins.
*   [olivercederborg/poimandres.nvim (⭐64)](https://github.com/olivercederborg/poimandres.nvim) - Neovim port of [poimandres VSCode theme (⭐148)](https://github.com/drcmda/poimandres-theme) with Tree-sitter support, written in Lua.
*   [kvrohit/mellow.nvim (⭐41)](https://github.com/kvrohit/mellow.nvim) - A soothing dark color scheme with tree-sitter support.

#### Lua Colorscheme

These colorschemes may not specialize in Tree-sitter directly but are written in Lua.

*   [tjdevries/gruvbuddy.nvim (⭐83)](https://github.com/tjdevries/gruvbuddy.nvim) - Gruvbox colors.
*   [ellisonleao/gruvbox.nvim (⭐663)](https://github.com/ellisonleao/gruvbox.nvim) - Gruvbox community colorscheme Lua port.
*   [metalelf0/jellybeans-nvim (⭐62)](https://github.com/metalelf0/jellybeans-nvim) - A port of jellybeans colorscheme.
*   [lalitmee/cobalt2.nvim (⭐39)](https://github.com/lalitmee/cobalt2.nvim) - A port of cobalt2 colorscheme using colorbuddy.

#### Colorscheme Creation

*   [tjdevries/colorbuddy.nvim (⭐395)](https://github.com/tjdevries/colorbuddy.nvim) - A colorscheme helper. Written in Lua! Quick & Easy Color Schemes 😄.
*   [norcalli/nvim-base16.lua (⭐60)](https://github.com/norcalli/nvim-base16.lua) - Programmatic Lua library for setting base16 themes.
*   [rktjmp/lush.nvim (⭐877)](https://github.com/rktjmp/lush.nvim) - Define Neovim themes as a DSL in Lua, with real-time feedback.
*   [Iron-E/nvim-highlite (⭐164)](https://github.com/Iron-E/nvim-highlite) - A colorscheme template that is "lite" on logic for the developer.
*   [echasnovski/mini.nvim#mini.base16 (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-base16.md) - Module of `mini.nvim` with fast implementation of base16 theme for manually supplied palette.
*   [ThemerCorp/themer.lua (⭐195)](https://github.com/themercorp/themer.lua) - A simple highlighter plugin for neovim. It has a huge collection of colorschemes. It also has ability to create colorschemes for Vim/Neovim and other supported apps (such as kitty and alacritty).

### Bars and Lines

*   [SmiteshP/nvim-navic (⭐609)](https://github.com/SmiteshP/nvim-navic) - A simple statusline/winbar component that uses LSP to show your current code context.

#### Statusline

*   [NTBBloodbath/galaxyline.nvim (⭐140)](https://github.com/NTBBloodbath/galaxyline.nvim) - Galaxyline componentizes Vim's statusline by having a provider for each text area. This means you can use the api provided by galaxyline to create the statusline that you want, easily.
*   [tjdevries/express\_line.nvim (⭐207)](https://github.com/tjdevries/express_line.nvim) - Supports co-routines, functions and jobs.
*   [nvim-lualine/lualine.nvim (⭐2.7k)](https://github.com/nvim-lualine/lualine.nvim) - A blazing fast and easy to configure Neovim statusline.
*   [adelarsq/neoline.vim (⭐180)](https://github.com/adelarsq/neoline.vim) - A light statusline/tabline plugin using Lua.
*   [ojroques/nvim-hardline (⭐139)](https://github.com/ojroques/nvim-hardline) - A statusline / bufferline. It is inspired by [vim-airline (⭐17k)](https://github.com/vim-airline/vim-airline) but aims to be as light and simple as possible.
*   [datwaft/bubbly.nvim (⭐185)](https://github.com/datwaft/bubbly.nvim) - Bubbly status line.
*   [beauwilliams/statusline.lua (⭐143)](https://github.com/beauwilliams/statusline.lua) - A zero-config minimal statusline written in Lua featuring awesome integrations and blazing speed!
*   [tamton-aquib/staline.nvim (⭐203)](https://github.com/tamton-aquib/staline.nvim) - A modern lightweight statusline in Lua. Mainly uses unicode symbols for showing info.
*   [feline-nvim/feline.nvim (⭐948)](https://github.com/feline-nvim/feline.nvim) - A minimal, stylish and customizable statusline written in Lua.
*   [windwp/windline.nvim (⭐351)](https://github.com/windwp/windline.nvim) - The next generation statusline. Animation statusline.
*   [konapun/vacuumline.nvim (⭐24)](https://github.com/konapun/vacuumline.nvim) - A galaxyline configuration inspired by airline.
*   [echasnovski/mini.nvim#mini.statusline (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-statusline.md) - Module of `mini.nvim` for minimal and fast statusline. Supports content change depending on window width.
*   [b0o/incline.nvim (⭐279)](https://github.com/b0o/incline.nvim) - Lightweight floating statuslines, intended for use with Neovim's new global statusline.
*   [rebelot/heirline.nvim (⭐404)](https://github.com/rebelot/heirline.nvim) - Heirline.nvim is a no-nonsense Neovim Statusline plugin designed around recursive inheritance to be exceptionally fast and versatile.
*   [yaocccc/nvim-lines.lua (⭐15)](https://github.com/yaocccc/nvim-lines.lua) - A fast, light, customizable Neovim statusline and tabline(buffers) plugin.

#### Tabline

*   [romgrk/barbar.nvim (⭐1.3k)](https://github.com/romgrk/barbar.nvim) - The Neovim tabline plugin.
*   [akinsho/bufferline.nvim (⭐1.8k)](https://github.com/akinsho/bufferline.nvim) - A snazzy buffer line built using Lua.
*   [crispgm/nvim-tabline (⭐34)](https://github.com/crispgm/nvim-tabline) - Neovim port of tabline.vim with Lua.
*   [alvarosevilla95/luatab.nvim (⭐143)](https://github.com/alvarosevilla95/luatab.nvim) - A simple tabline written in Lua.
*   [johann2357/nvim-smartbufs (⭐22)](https://github.com/johann2357/nvim-smartbufs) - Smart buffer management.
*   [kdheepak/tabline.nvim (⭐187)](https://github.com/kdheepak/tabline.nvim) - A "buffer and tab" tabline.
*   [noib3/cokeline.nvim (⭐261)](https://github.com/noib3/cokeline.nvim) - A Neovim bufferline for people with addictive personalities.
*   [echasnovski/mini.nvim#mini.tabline (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-tabline.md) - Module of `mini.nvim` for minimal tabline showing listed buffers in case of one tab and falling back to default otherwise.
*   [rafcamlet/tabline-framework.nvim (⭐78)](https://github.com/rafcamlet/tabline-framework.nvim) - User-friendly framework for building your dream tabline in a few lines of code.
*   [nanozuki/tabby.nvim (⭐234)](https://github.com/nanozuki/tabby.nvim) - A minimal, configurable, Neovim style tabline. Use your Neovim tabs as workspace multiplexer.

#### Winbar

*   [utilyre/barbecue.nvim (⭐39)](https://github.com/utilyre/barbecue.nvim) - A VS Code like winbar.

#### Cursorline

*   [yamatsum/nvim-cursorline (⭐271)](https://github.com/yamatsum/nvim-cursorline) - A plugin that highlights cursor words and lines.
*   [xiyaowong/nvim-cursorword (⭐93)](https://github.com/xiyaowong/nvim-cursorword) - Part of nvim-cursorline. Highlight the word under the cursor.
*   [RRethy/vim-illuminate (⭐1.3k)](https://github.com/RRethy/vim-illuminate) - Highlight the word under the cursor. Neovim's builtin LSP is available, it can be used to highlight more intelligently.
*   [echasnovski/mini.nvim#mini.cursorword (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-cursorword.md) - Module of `mini.nvim` for automatic highlighting of word under cursor (displayed after customizable delay).
*   [melkster/modicator.nvim (⭐46)](https://github.com/melkster/modicator.nvim) - Cursor line number mode indicator. Changes the `CursorLineNr` highlight based on Vim mode.

### Startup

*   [glepnir/dashboard-nvim (⭐1.2k)](https://github.com/glepnir/dashboard-nvim) - A minimalist dashboard, inspired by doom-emacs.
*   [goolord/alpha-nvim (⭐763)](https://github.com/goolord/alpha-nvim) - A fast and highly customizable greeter like [vim-startify (⭐4.9k)](https://github.com/mhinz/vim-startify)/dashboard-nvim.
*   [echasnovski/mini.nvim#mini.starter (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-starter.md) - Module of `mini.nvim` for start screen. Displayed items are fully customizable, item selection can be done using prefix query with instant visual feedback.
*   [henriquehbr/nvim-startup.lua](https://sr.ht/\~henriquehbr/nvim-startup.lua) - Displays Neovim startup time.
*   [startup-nvim/startup.nvim (⭐176)](https://github.com/startup-nvim/startup.nvim) - The fully customizable greeter for neovim.

### Icon

*   [kyazdani42/nvim-web-devicons (⭐841)](https://github.com/kyazdani42/nvim-web-devicons) - A Lua fork of [vim-devicons (⭐5k)](https://github.com/ryanoasis/vim-devicons).
*   [yamatsum/nvim-nonicons (⭐252)](https://github.com/yamatsum/nvim-nonicons) - Collection of configurations for nvim-web-devicons.
*   [ziontee113/icon-picker.nvim (⭐103)](https://github.com/ziontee113/icon-picker.nvim) - Help you pick 𝑨𝕃𝚻 Font Characters, Symbols Σ, Nerd Font Icons  & Emojis ✨.

### Media

*   [ekickx/clipboard-image.nvim (⭐171)](https://github.com/ekickx/clipboard-image.nvim) - Neovim Lua plugin to paste image from clipboard.
*   [askfiy/nvim-picgo (⭐24)](https://github.com/askfiy/nvim-picgo) - A picgo-core-based Neovim plugin, written in Lua, that allows you to upload images to the image bed, which means you can view your images from anywhere on the internet.
*   [gwatcha/reaper-keys (⭐75)](https://github.com/gwatcha/reaper-keys) - Modal keybindings for Reaper DAW.
*   [madskjeldgaard/reaper-nvim (⭐38)](https://github.com/madskjeldgaard/reaper-nvim) - Remote control Reaper DAW from Neovim.
*   [davidgranstrom/scnvim (⭐115)](https://github.com/davidgranstrom/scnvim) - Neovim frontend for SuperCollider.
*   [andweeb/presence.nvim (⭐414)](https://github.com/andweeb/presence.nvim) - Fast and lite Discord Rich Presence plugin written in Lua.
*   [Chaitanyabsrip/present.nvim (⭐68)](https://github.com/Chaitanyabsprip/present.nvim) - A Presentation plugin written in Lua.
*   [krady21/compiler-explorer.nvim (⭐69)](https://github.com/krady21/compiler-explorer.nvim) - Async Lua plugin for interacting with [compiler-explorer](https://godbolt.org/).
*   [samodostal/image.nvim (⭐64)](https://github.com/samodostal/image.nvim) - Image Viewer as ASCII Art.
*   [adelarsq/image\_preview.nvim (⭐28)](https://github.com/adelarsq/image_preview.nvim) - Image preview based on terminal's Image Protocol support.

### Note Taking

*   [0styx0/abbreinder.nvim (⭐56)](https://github.com/0styx0/abbreinder.nvim) - Abbreviation reminders (Neovim >= 0.5).
*   [jakewvincent/mkdnflow.nvim (⭐262)](https://github.com/jakewvincent/mkdnflow.nvim) - Fluent markdown notebook navigation & management (create links, follow links, create and manage to-do lists, reference bib files, and more).
*   [oberblastmeister/neuron.nvim (⭐364)](https://github.com/oberblastmeister/neuron.nvim) - Note taking plugin for neuron that integrates with telescope.nvim.
*   [jbyuki/nabla.nvim (⭐365)](https://github.com/jbyuki/nabla.nvim) - Take your scientific notes.
*   [nvim-neorg/neorg (⭐2.9k)](https://github.com/nvim-neorg/neorg) - Modernity meets insane extensibility. The future of organizing your life.
*   [nvim-orgmode/orgmode (⭐1.8k)](https://github.com/nvim-orgmode/orgmode) - Orgmode clone written in Lua (Neovim >= 0.5).
*   [NFrid/due.nvim (⭐76)](https://github.com/NFrid/due.nvim) - Displays due for a date string as a virtual text.
*   [jbyuki/venn.nvim (⭐636)](https://github.com/jbyuki/venn.nvim) - Draw ASCII diagrams.
*   [stevearc/gkeep.nvim (⭐132)](https://github.com/stevearc/gkeep.nvim) - Google Keep integration.
*   [renerocksai/telekasten.nvim (⭐541)](https://github.com/renerocksai/telekasten.nvim) - A Neovim (lua) plugin for working with a text-based, markdown zettelkasten / wiki and mixing it with a journal, based on telescope.nvim.
*   [mickael-menu/zk-nvim (⭐225)](https://github.com/mickael-menu/zk-nvim) - Neovim extension for zk, a plain text note-taking assistant.
*   [chrsm/impulse.nvim (⭐37)](https://github.com/chrsm/impulse.nvim) - Read Notion.so notes.
*   [epwalsh/obsidian.nvim (⭐132)](https://github.com/epwalsh/obsidian.nvim) - Plugin for Obsidian, written in Lua.
*   [jghauser/papis.nvim (⭐59)](https://github.com/jghauser/papis.nvim) - Manage your bibliography from within your favourite editor.
*   [ostralyan/scribe.nvim (⭐11)](https://github.com/ostralyan/scribe.nvim) - Take notes, easily.

### Utility

*   [jghauser/mkdir.nvim (⭐123)](https://github.com/jghauser/mkdir.nvim) - Automatically create missing directories when saving files.
*   [matbme/JABS.nvim (⭐189)](https://github.com/matbme/JABS.nvim) - Pretty and minimal buffer switcher window.
*   [clojure-vim/jazz.nvim (⭐33)](https://github.com/clojure-vim/jazz.nvim) - Acid + Impromptu = Jazz.
*   [sudormrfbin/cheatsheet.nvim (⭐406)](https://github.com/sudormrfbin/cheatsheet.nvim) - Searchable cheatsheet.
*   [code-biscuits/nvim-biscuits (⭐138)](https://github.com/code-biscuits/nvim-biscuits) - A Neovim port of Assorted Biscuits. Ends up with more supported languages too.
*   [Pocco81/AbbrevMan.nvim (⭐83)](https://github.com/Pocco81/AbbrevMan.nvim) - Manage Vim abbreviations.
*   [kazhala/close-buffers.nvim (⭐83)](https://github.com/kazhala/close-buffers.nvim) - Delete multiple Vim buffers based on different conditions.
*   [rktjmp/paperplanes.nvim (⭐63)](https://github.com/rktjmp/paperplanes.nvim) - Post selections or buffers to online paste bins.
*   [rcarriga/nvim-notify (⭐1.7k)](https://github.com/rcarriga/nvim-notify) - A fancy, configurable, notification manager.
*   [folke/noice.nvim (⭐1.5k)](https://github.com/folke/noice.nvim) - Highly experimental plugin that completely replaces the UI for messages, cmdline and the popupmenu.
*   [saifulapm/chartoggle.nvim (⭐23)](https://github.com/saifulapm/chartoggle.nvim) - Toggle any character at end of line.
*   [stevearc/dressing.nvim (⭐707)](https://github.com/stevearc/dressing.nvim) - Improve the built-in `vim.ui` interfaces with telescope, fzf, etc.
*   [gaborvecsei/cryptoprice.nvim (⭐15)](https://github.com/gaborvecsei/cryptoprice.nvim) - Check the price of the defined cryptocurrencies.
*   [jghauser/fold-cycle.nvim (⭐39)](https://github.com/jghauser/fold-cycle.nvim) - Cycle folds open or closed.
*   [rgroli/other.nvim (⭐100)](https://github.com/rgroli/other.nvim) - Open alternative files for the current buffer.
*   [toppair/reach.nvim (⭐132)](https://github.com/toppair/reach.nvim) - Buffer, mark, tabpage switcher.
*   [axieax/urlview.nvim (⭐104)](https://github.com/axieax/urlview.nvim) - Browse all URLs in the current buffer.
*   [nkakouros-original/numbers.nvim (⭐17)](https://github.com/nkakouros-original/numbers.nvim) - Toggle relativenumber whenever it makes sense.
*   [ghillb/cybu.nvim (⭐177)](https://github.com/ghillb/cybu.nvim) - Displays a notification window with context when cycling buffers.
*   [crusj/bookmarks.nvim (⭐38)](https://github.com/crusj/bookmarks.nvim) - Remember file locations and sort by time and frequency.
*   [xiyaowong/virtcolumn.nvim (⭐23)](https://github.com/xiyaowong/virtcolumn.nvim) - Display a line as colorcolumn.
*   [m-demare/attempt.nvim (⭐55)](https://github.com/m-demare/attempt.nvim) - Manage and run temporary buffers.
*   [kevinhwang91/nvim-ufo (⭐772)](https://github.com/kevinhwang91/nvim-ufo) - Ultra fold with modern looking and performance boosting.
*   [xiyaowong/link-visitor.nvim (⭐15)](https://github.com/xiyaowong/link-visitor.nvim) - Let me help you open the links.
*   [sitiom/nvim-numbertoggle (⭐36)](https://github.com/sitiom/nvim-numbertoggle) - Neovim plugin to automatically toggle between relative and absolute line numbers.
*   [anuvyklack/fold-preview (⭐46)](https://github.com/anuvyklack/fold-preview.nvim) - Preview closed fold without opening it.
*   [nguyenvukhang/nvim-toggler (⭐61)](https://github.com/nguyenvukhang/nvim-toggler) - Invert text, such as toggling between `true` and `false`.
*   [CosmicNvim/cosmic-ui (⭐111)](https://github.com/CosmicNvim/cosmic-ui) - Cosmic-UI is a simple wrapper around specific Vim functionality. Built in order to provide a quick and easy way to create a Cosmic UI experience with Neovim!
*   [AckslD/messages.nvim (⭐57)](https://github.com/AckslD/messages.nvim) - Capture and show any messages in a customisable (floating) buffer.
*   [jbyuki/instant.nvim (⭐805)](https://github.com/jbyuki/instant.nvim) - A collaborative editing plugin written in Lua with no dependencies.
*   [numToStr/BufOnly.nvim (⭐26)](https://github.com/numToStr/BufOnly.nvim) - Lua/Neovim port of BufOnly.vim with some changes.
*   [zbirenbaum/neodim (⭐90)](https://github.com/zbirenbaum/neodim) - Dimming the highlights of unused functions, variables, parameters, and more.
*   [bfredl/nvim-miniyank (⭐217)](https://github.com/bfredl/nvim-miniyank) - The killring-alike plugin with no default mappings.

### Terminal Integration

*   [LoricAndre/OneTerm.nvim (⭐35)](https://github.com/LoricAndre/OneTerm.nvim) - Plugin framework for running commands in the terminal.
*   [nikvdp/neomux (⭐225)](https://github.com/nikvdp/neomux) - Control Neovim from shells running inside Neovim.
*   [akinsho/nvim-toggleterm.lua (⭐1.8k)](https://github.com/akinsho/nvim-toggleterm.lua) - A Neovim Lua plugin to help easily manage multiple terminal windows.
*   [norcalli/nvim-terminal.lua (⭐135)](https://github.com/norcalli/nvim-terminal.lua) - A high performance filetype mode which leverages conceal and highlights your buffer with the correct color codes.
*   [numToStr/FTerm.nvim (⭐505)](https://github.com/numToStr/FTerm.nvim) - No nonsense floating terminal written in Lua.
*   [pianocomposer321/consolation.nvim (⭐27)](https://github.com/pianocomposer321/consolation.nvim) - A general-purpose terminal wrapper and management plugin, written in Lua.
*   [jghauser/kitty-runner.nvim (⭐51)](https://github.com/jghauser/kitty-runner.nvim) - Poor man's REPL. Easily send buffer lines and commands to a kitty terminal.
*   [jlesquembre/nterm.nvim (⭐47)](https://github.com/jlesquembre/nterm.nvim) - Interact with the terminal, with notifications.
*   [s1n7ax/nvim-terminal (⭐80)](https://github.com/s1n7ax/nvim-terminal) - A simple & easy to use multi-terminal plugin.
*   [m00qek/baleia.nvim (⭐39)](https://github.com/m00qek/baleia.nvim) - Colorize text with ANSI escape sequences (8, 16, 256 or TrueColor).
*   [samjwill/nvim-unception (⭐113)](https://github.com/samjwill/nvim-unception) - Automatic unnesting of Neovim sessions started from terminal buffers.

### Debugging

*   [mfussenegger/nvim-dap (⭐2.5k)](https://github.com/mfussenegger/nvim-dap) - Debug Adapter Protocol client implementation.
*   [sakhnik/nvim-gdb (⭐524)](https://github.com/sakhnik/nvim-gdb) - Thin wrapper for GDB, LLDB, PDB/PDB++ and BashDB.
*   [rcarriga/nvim-dap-ui (⭐967)](https://github.com/rcarriga/nvim-dap-ui) - A UI for nvim-dap.
*   [Pocco81/DAPInstall.nvim (⭐360)](https://github.com/Pocco81/DAPInstall.nvim) - Manage several debuggers for nvim-dap.
*   [Weissle/persistent-breakpoints.nvim (⭐49)](https://github.com/Weissle/persistent-breakpoints.nvim) - Persistent breakpoints for nvim-dap.
*   [ofirgall/goto-breakpoints.nvim (⭐9)](https://github.com/ofirgall/goto-breakpoints.nvim) - Cycle between breakpoints for nvim-dap.
*   [andrewferrier/debugprint.nvim (⭐73)](https://github.com/andrewferrier/debugprint.nvim) - Debugging the print() way.

#### Quickfix

*   [kevinhwang91/nvim-bqf (⭐867)](https://github.com/kevinhwang91/nvim-bqf) - The goal of nvim-bqf is to make Neovim's quickfix window better.
*   [gitlab.com/yorickpeterse/nvim-pqf](https://gitlab.com/yorickpeterse/nvim-pqf) - Prettier quickfix/location list windows.

### Test

*   [David-Kunz/jester (⭐119)](https://github.com/David-Kunz/jester) - Easily run and debug Jest tests.
*   [klen/nvim-test (⭐88)](https://github.com/klen/nvim-test) - A Neovim wrapper for running tests.
*   [nvim-neotest/neotest (⭐813)](https://github.com/nvim-neotest/neotest) - An extensible framework for interacting with tests within Neovim.
*   [andythigpen/nvim-coverage (⭐104)](https://github.com/andythigpen/nvim-coverage) - Displays coverage information in the sign column.

### Code Runner

*   [michaelb/sniprun (⭐835)](https://github.com/michaelb/sniprun) - Run parts of code of any language directly from Neovim.
*   [pianocomposer321/yabs.nvim (⭐183)](https://github.com/pianocomposer321/yabs.nvim) - Yet Another Build System, written in Lua.
*   [CRAG666/code\_runner.nvim (⭐231)](https://github.com/CRAG666/code_runner.nvim) - The best code runner you could have, with super powers.
*   [is0n/jaq-nvim (⭐120)](https://github.com/is0n/jaq-nvim) - Just Another Quickrun Plugin in Lua.
*   [jedrzejboczar/toggletasks.nvim (⭐92)](https://github.com/jedrzejboczar/toggletasks.nvim) - Task runner with JSON/YAML configs, using toggleterm.nvim and telescope.nvim.
*   [EthanJWright/vs-tasks.nvim (⭐73)](https://github.com/EthanJWright/vs-tasks.nvim) - Telescope picker for VSCode style tasks.
*   [stevearc/overseer.nvim (⭐214)](https://github.com/stevearc/overseer.nvim) - A task runner and job management plugin.
*   [smzm/hydrovim (⭐18)](https://github.com/smzm/hydrovim) - Run python code inside Neovim.
*   [desdic/greyjoy.nvim (⭐16)](https://github.com/desdic/greyjoy.nvim) - A modular task runner for Makefiles, vscode tasks, kitchen etc.
*   [Shatur/neovim-tasks (⭐12)](https://github.com/Shatur/neovim-tasks) - A stateful task manager focused on integration with build systems.
*   [hkupty/iron.nvim (⭐518)](https://github.com/hkupty/iron.nvim) - Interactive REPLs of over 30 languages embedded.

### Neovim Lua Development

*   [tjdevries/nlua.nvim (⭐257)](https://github.com/tjdevries/nlua.nvim) - Lua Development.
*   [svermeulen/vimpeccable (⭐354)](https://github.com/svermeulen/vimpeccable) - Commands to help write your .vimrc in Lua or any Lua based language.
*   [nanotee/nvim-lua-guide (⭐4.7k)](https://github.com/nanotee/nvim-lua-guide) - A guide to using Lua in Neovim.
*   [rafcamlet/nvim-luapad (⭐345)](https://github.com/rafcamlet/nvim-luapad) - Interactive real time Neovim scratchpad for embedded Lua engine - Type and watch!.
*   [nvim-lua/plenary.nvim (⭐1.2k)](https://github.com/nvim-lua/plenary.nvim) - Plenary: full; complete; entire; absolute; unqualified. All the Lua functions I don't want to write twice.
*   [nvim-lua/popup.nvim (⭐284)](https://github.com/nvim-lua/popup.nvim) - An implementation of the Popup API from Vim.
*   [tjdevries/vlog.nvim (⭐78)](https://github.com/tjdevries/vlog.nvim) - Single file, no dependency, easy copy & paste log file to add to your Neovim Lua plugins.
*   [bfredl/nvim-luadev (⭐219)](https://github.com/bfredl/nvim-luadev) - REPL/debug console Lua plugins. The `:Luadev` command will open an scratch window which will show output from executing Lua code.
*   [jbyuki/one-small-step-for-vimkind (⭐185)](https://github.com/jbyuki/one-small-step-for-vimkind) - An adapter for the Neovim Lua language. It allows you to debug any Lua code running in a Neovim instance (A Lua plugin that can debug Neovim Lua plugins).
*   [kkharji/sqlite.lua (⭐291)](https://github.com/kkharji/sqlite.lua) - SQLite/LuaJIT binding for Lua and Neovim.
*   [folke/lua-dev.nvim (⭐566)](https://github.com/folke/lua-dev.nvim) - Dev setup for init.Lua and plugin development with full signature help, docs and completion for the Neovim Lua API.
*   [MunifTanjim/nui.nvim (⭐639)](https://github.com/MunifTanjim/nui.nvim) - UI Component Library.
*   [echasnovski/mini.nvim#mini.doc (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-doc.md) - Module of `mini.nvim` for generation of help files from EmmyLua-like annotations. Allows flexible customization of output via hook functions.
*   [nanotee/luv-vimdocs (⭐68)](https://github.com/nanotee/luv-vimdocs) - The luv docs in vimdoc format.
*   [milisims/nvim-luaref (⭐107)](https://github.com/milisims/nvim-luaref) - A reference for builtin Lua functions.
*   [echasnovski/mini.nvim#mini.test (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-test.md) - Module of `mini.nvim` with framework for writing extensive Neovim plugin tests. Supports hierarchical tests, hooks, parametrization, filtering, screen tests, "busted-style" emulation, customizable reporters, and more.
*   [miversen33/import.nvim (⭐157)](https://github.com/miversen33/import.nvim) - A safe require replacement with niceties.
*   [ray-x/guihua.lua (⭐91)](https://github.com/ray-x/guihua.lua) - A Lua UI library. Includes a fzy search bar, list view and tree view modules.
*   [anuvyklack/animation.nvim (⭐16)](https://github.com/anuvyklack/animation.nvim) - Create animations.
*   [NFrid/treesitter-utils (⭐1)](https://github.com/NFrid/treesitter-utils) - Some useful Treesitter methods.

### Fennel

*   [Olical/aniseed (⭐479)](https://github.com/Olical/aniseed) - Configure and extend Neovim with Fennel (Lisp to Lua).
*   [Olical/conjure (⭐1.1k)](https://github.com/Olical/conjure) - Interactive evaluation (Clojure, Fennel, Janet, Racket, Hy, MIT Scheme, Guile).
*   [rktjmp/hotpot.nvim (⭐215)](https://github.com/rktjmp/hotpot.nvim) - Seamless, transparent Fennel inside Neovim.
*   [udayvir-singh/tangerine.nvim (⭐120)](https://github.com/udayvir-singh/tangerine.nvim) - Sweet :tangerine: Fennel integration, aims to be as fast as possible.
*   [udayvir-singh/hibiscus.nvim (⭐58)](https://github.com/udayvir-singh/hibiscus.nvim) - Flavored :hibiscus: Fennel macro library.

### Dependency Management

*   [vuki656/package-info.nvim (⭐204)](https://github.com/vuki656/package-info.nvim) - Display latest package version as virtual text in package.json.
*   [Saecki/crates.nvim (⭐319)](https://github.com/Saecki/crates.nvim) - Rust dependency management for `Cargo.toml`.

### Git

*   [f-person/git-blame.nvim (⭐442)](https://github.com/f-person/git-blame.nvim) - Show git blame info.
*   [lewis6991/gitsigns.nvim (⭐2.3k)](https://github.com/lewis6991/gitsigns.nvim) - Git integration: signs, hunk actions, blame, etc.
*   [TimUntersberger/neogit (⭐1.8k)](https://github.com/TimUntersberger/neogit) - A Magit clone that may change some things to fit the Vim philosophy.
*   [tveskag/nvim-blame-line (⭐159)](https://github.com/tveskag/nvim-blame-line) - A small plugin that uses neovims virtual text to print git blame info at the end of the current line.
*   [ruifm/gitlinker.nvim (⭐268)](https://github.com/ruifm/gitlinker.nvim) - Generate shareable file permalinks for several git hosts. Inspired by tpope/vim-fugitive's :GBrowse.
*   [tanvirtin/vgit.nvim (⭐405)](https://github.com/tanvirtin/vgit.nvim) - Visual Git Plugin to enhance your git experience.
*   [sindrets/diffview.nvim (⭐1.6k)](https://github.com/sindrets/diffview.nvim) - Single tabpage interface for easily cycling through diffs for all modified files for any git rev.
*   [kdheepak/lazygit.nvim (⭐534)](https://github.com/kdheepak/lazygit.nvim) - Plugin for calling lazygit.
*   [AckslD/nvim-gfold.lua (⭐32)](https://github.com/AckslD/nvim-gfold.lua) - Plugin using [gfold (⭐196)](https://github.com/nickgerace/gfold) to switch repo and have statusline component.
*   [akinsho/git-conflict.nvim (⭐339)](https://github.com/akinsho/git-conflict.nvim) - A plugin to visualise and resolve merge conflicts.

#### GitHub

*   [pwntester/octo.nvim (⭐1.2k)](https://github.com/pwntester/octo.nvim) - Work with GitHub issues and PRs from Neovim. Just edit the issue description.
*   [pwntester/codeql.nvim (⭐65)](https://github.com/pwntester/codeql.nvim) - Neovim plugin to help writing and testing CodeQL queries.
*   [ldelossa/gh.nvim (⭐295)](https://github.com/ldelossa/gh.nvim) - A fully featured GitHub integration for performing code reviews.

### Motion

*   [phaazon/hop.nvim (⭐1.7k)](https://github.com/phaazon/hop.nvim) - Hop is an EasyMotion-like plugin allowing you to jump anywhere in a document with as few keystrokes as possible.
*   [ggandor/lightspeed.nvim (⭐1.4k)](https://github.com/ggandor/lightspeed.nvim) - A Sneak-like plugin offering unparalleled navigation speed via ahead-of-time displayed labels, that eliminate the pause between entering the search pattern and selecting the target.
*   [ggandor/leap.nvim (⭐2.1k)](https://github.com/ggandor/leap.nvim) - A refined successor of Lightspeed, aiming to establish a widely accepted standard interface extension for moving around in Vim-like editors.
*   [echasnovski/mini.nvim#mini.jump (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-jump.md) - Module of `mini.nvim` for smarter jumping to a single character.
*   [echasnovski/mini.nvim#mini.jump2d (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-jump2d.md) - Module of `mini.nvim` for smarter jumping within visible lines via iterative label filtering. Supports custom jump targets (spots), labels, hooks, allowed windows and lines, and more.
*   [rlane/pounce.nvim (⭐233)](https://github.com/rlane/pounce.nvim) - An EasyMotion-like plugin for quick cursor movement using fuzzy search.
*   [gen740/SmoothCursor.nvim (⭐163)](https://github.com/gen740/SmoothCursor.nvim) - Add fancy sub-cursor to signcolumn to show your scroll or jump direction.
*   [edluffy/specs.nvim (⭐314)](https://github.com/edluffy/specs.nvim) - A fast and lightweight Neovim Lua plugin to keep an eye on where your cursor has jumped.
*   [abecodes/tabout.nvim (⭐412)](https://github.com/abecodes/tabout.nvim) - Jump out of brackets, quotes, objects, etc.
*   [linty-org/readline.nvim (⭐80)](https://github.com/linty-org/readline.nvim) - Readline keyboard shortcuts.
*   [woosaaahh/sj.nvim (⭐63)](https://github.com/woosaaahh/sj.nvim) - Search based navigation combined with quick jump features.
*   [Weissle/easy-action (⭐3)](https://github.com/Weissle/easy-action) - Easily perform an action on where you can see.

#### Treesitter Based

*   [mfussenegger/nvim-ts-hint-textobject (⭐267)](https://github.com/mfussenegger/nvim-ts-hint-textobject) - Region selection with hints on the AST nodes of a document powered by Treesitter.
*   [ziontee113/syntax-tree-surfer (⭐304)](https://github.com/ziontee113/syntax-tree-surfer) - Navigate and swap Treesitter's AST Nodes. Step into, step out, step over, step back.
*   [drybalka/tree-climber.nvim (⭐70)](https://github.com/drybalka/tree-climber.nvim) - Easy navigation around the Treesitter's tree that works in multi-language files and in normal mode.

### Keybinding

*   [folke/which-key.nvim (⭐2.1k)](https://github.com/folke/which-key.nvim) - Neovim plugin that shows a popup with possible keybindings of the command you started typing.
*   [mrjones2014/legendary.nvim (⭐478)](https://github.com/mrjones2014/legendary.nvim) - Define your keymaps, commands, and autocommands as simple Lua tables, and create a legend for them at the same time (like VS Code's Command Palette), integrates with `which-key.nvim`.
*   [Iron-E/nvim-cartographer (⭐51)](https://github.com/Iron-E/nvim-cartographer) - a more convenient `:map`ping syntax for Lua environments.
*   [b0o/mapx.nvim (⭐201)](https://github.com/b0o/mapx.nvim) - A simpler key mapping API that mimics Neovim's `:map`-family of commands. Integrates with which-key.nvim.
*   [LionC/nest.nvim (⭐210)](https://github.com/LionC/nest.nvim) - Lua utility to map keys concisely using cascading trees. Also allows binding Lua functions to keys.
*   [LinArcX/telescope-command-palette.nvim (⭐188)](https://github.com/LinArcX/telescope-command-palette.nvim) - Lua plugin to create key-bindings and watch them with telescope.
*   [slugbyte/unruly-worker (⭐19)](https://github.com/slugbyte/unruly-worker) - A ridiculously fun alternative keymap for the workman keyboard layout with Neovim features like LSP support, built and configured with Lua.
*   [FeiyouG/command\_center.nvim (⭐156)](https://github.com/FeiyouG/command_center.nvim) - Create and manage keybindings and commands in a more organized manner and search them quickly through Telescope.
*   [linty-org/key-menu.nvim (⭐193)](https://github.com/linty-org/key-menu.nvim) - Key mapping hints in a floating window.
*   [anuvyklack/hydra.nvim (⭐634)](https://github.com/anuvyklack/hydra.nvim) - Create custom submodes and menus. Port of Emacs Hydra.
*   [anuvyklack/keymap-amend.nvim (⭐36)](https://github.com/anuvyklack/keymap-amend.nvim) - Amend the existing keymap.
*   [max397574/better-escape.nvim (⭐252)](https://github.com/max397574/better-escape.nvim) - Create shortcuts to escape insert mode without getting delay.

### Mouse

*   [notomo/gesture.nvim (⭐321)](https://github.com/notomo/gesture.nvim) - Mouse gesture plugin.

### Scrolling

*   [karb94/neoscroll.nvim (⭐690)](https://github.com/karb94/neoscroll.nvim) - Smooth scrolling.
*   [declancm/cinnamon.nvim (⭐150)](https://github.com/declancm/cinnamon.nvim) - Smooth scrolling for any movement command.

#### Scrollbar

*   [Xuyuanp/scrollbar.nvim (⭐239)](https://github.com/Xuyuanp/scrollbar.nvim) - Scrollbar.
*   [dstein64/nvim-scrollview (⭐331)](https://github.com/dstein64/nvim-scrollview) - Display interactive scrollbars.
*   [petertriho/nvim-scrollbar (⭐419)](https://github.com/petertriho/nvim-scrollbar) - Extensible scrollbar that shows diagnostics and search results.
*   [echasnovski/mini.nvim#mini.map (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-map.md) - Module of `mini.nvim` to show floating window with buffer text overview, scrollbar, and highlights.
*   [gorbit99/codewindow.nvim (⭐172)](https://github.com/gorbit99/codewindow.nvim) - Minimap plugin, that is closely integrated with treesitter and the builtin LSP to display more information to the user.

### Editing Support

*   [windwp/nvim-ts-autotag (⭐682)](https://github.com/windwp/nvim-ts-autotag) - Use treesitter to autoclose and autorename xml,html,jsx tag.
*   [windwp/nvim-autopairs (⭐1.4k)](https://github.com/windwp/nvim-autopairs) - A minimalist autopairs written by Lua.
*   [ZhiyuanLck/smart-pairs (⭐115)](https://github.com/ZhiyuanLck/smart-pairs) - Ultimate smart pairs written by Lua.
*   [echasnovski/mini.nvim#mini.pairs (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-pairs.md) - Module of `mini.nvim` for autopairs which has minimal defaults and functionality to do per-key mapping.
*   [m4xshen/autoclose.nvim (⭐58)](https://github.com/m4xshen/autoclose.nvim) - A minimalist autoclose plugin written in Lua.
*   [monaqa/dial.nvim (⭐366)](https://github.com/monaqa/dial.nvim) - Extended increment/decrement.
*   [p00f/nvim-ts-rainbow (⭐801)](https://github.com/p00f/nvim-ts-rainbow) - Rainbow :rainbow: parentheses using tree-sitter :rainbow:.
*   [AckslD/nvim-revJ.lua (⭐104)](https://github.com/AckslD/nvim-revJ.lua) - Neovim Lua plugin for doing the opposite of join-line (J) for arguments.
*   [Pocco81/TrueZen.nvim (⭐664)](https://github.com/Pocco81/TrueZen.nvim) - Clean and elegant distraction-free writing.
*   [Pocco81/HighStr.nvim (⭐207)](https://github.com/Pocco81/HighStr.nvim) - Highlight visual selections like in a normal document editor!
*   [Pocco81/AutoSave.nvim (⭐307)](https://github.com/Pocco81/AutoSave.nvim) - Save your work before the world collapses or you type :qa!
*   [folke/zen-mode.nvim (⭐598)](https://github.com/folke/zen-mode.nvim) - Distraction-free coding.
*   [haringsrob/nvim\_context\_vt (⭐260)](https://github.com/haringsrob/nvim_context_vt) - Shows virtual text of the current context.
*   [nvim-treesitter/nvim-treesitter-context (⭐1.1k)](https://github.com/nvim-treesitter/nvim-treesitter-context) - Shows floating hover with the current function/block context.
*   [mizlan/iswap.nvim (⭐369)](https://github.com/mizlan/iswap.nvim) - Interactively select and swap function arguments, list elements, and more. Powered by tree-sitter.
*   [nacro90/numb.nvim (⭐368)](https://github.com/nacro90/numb.nvim) - Peek lines in a non-obtrusive way.
*   [ethanholz/nvim-lastplace (⭐174)](https://github.com/ethanholz/nvim-lastplace) - Reopen files at your last edit position.
*   [Allendang/nvim-expand-expr (⭐31)](https://github.com/AllenDang/nvim-expand-expr) - Expand and repeat expression to multiple lines.
*   [h-hg/fcitx.nvim (⭐38)](https://github.com/h-hg/fcitx.nvim) - Switching and restoring fcitx state for each buffer separately.
*   [keaising/im-select.nvim (⭐36)](https://github.com/keaising/im-select.nvim) - Switching and restoring input method automatically depends on Neovim's edit mode.
*   [echasnovski/mini.nvim#mini.trailspace (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-trailspace.md) - Module of `mini.nvim` for automatic highlighting of trailing whitespace with functionality to remove it.
*   [smjonas/live-command.nvim (⭐258)](https://github.com/smjonas/live-command.nvim) - Text editing with immediate visual feedback: preview commands such as `:norm`, `:g`, macros and more.
*   [filipdutescu/renamer.nvim (⭐226)](https://github.com/filipdutescu/renamer.nvim) - VS Code-like renaming UI, written in Lua.
*   [gbprod/cutlass.nvim (⭐80)](https://github.com/gbprod/cutlass.nvim) - Plugin that adds a 'cut' operation separate from 'delete'.
*   [gbprod/substitute.nvim (⭐187)](https://github.com/gbprod/substitute.nvim) - Neovim plugin introducing a new operator motions to quickly replace and exchange text.
*   [gbprod/yanky.nvim (⭐240)](https://github.com/gbprod/yanky.nvim) - Improved Yank and Put functionalities.
*   [sQVe/sort.nvim (⭐75)](https://github.com/sQVe/sort.nvim) - Sorting plugin that intelligently supports line-wise and delimiter sorting.
*   [booperlv/nvim-gomove (⭐143)](https://github.com/booperlv/nvim-gomove) - A complete plugin for moving and duplicating blocks and lines, with complete fold handling, reindenting, and undoing in one go.
*   [anuvyklack/pretty-fold.nvim (⭐275)](https://github.com/anuvyklack/pretty-fold.nvim) - Foldtext customization.
*   [bennypowers/nvim-regexplainer (⭐348)](https://github.com/bennypowers/nvim-regexplainer) - Explain the regular expression under the cursor.
*   [gbprod/stay-in-place.nvim (⭐50)](https://github.com/gbprod/stay-in-place.nvim) - Neovim plugin that prevent cursor from moving when using shift and filter actions.
*   [echasnovski/mini.nvim#mini.ai (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-ai.md) - Module of `mini.nvim` for extending and creating `a`/`i` textobjects. It enhances some builtin textobjects, creates extensive set of new ones (like `a*`, `a<Space>`, `a?`, and more), and allows user to create their own (via Lua patterns or functions). Supports dot-repeat, different search methods, consecutive application, and more.
*   [Wansmer/treesj (⭐4)](https://github.com/Wansmer/treesj) - Splitting/joining blocks of code like arrays, hashes, statements, objects, dictionaries, etc. Using Tree-Sitter. Inspired by greatest splitjoin.vim.

#### Comment

*   [numToStr/Comment.nvim (⭐1.6k)](https://github.com/numToStr/Comment.nvim) - Smart and Powerful comment plugin. Supports commentstring, motions, dot-repeat and more.
*   [b3nj5m1n/kommentary (⭐521)](https://github.com/b3nj5m1n/kommentary) - Commenting plugin written in Lua.
*   [gennaro-tedesco/nvim-commaround (⭐40)](https://github.com/gennaro-tedesco/nvim-commaround) - Fast and light commenting plugin written in Lua.
*   [folke/todo-comments.nvim (⭐1.2k)](https://github.com/folke/todo-comments.nvim) - Highlight, list and search todo comments in your projects.
*   [terrortylor/nvim-comment (⭐328)](https://github.com/terrortylor/nvim-comment) - Toggle comments using the built-in commentstring option.
*   [winston0410/commented.nvim (⭐110)](https://github.com/winston0410/commented.nvim) - A commenting plugin that supports counts and multiple comment patterns and much more.
*   [s1n7ax/nvim-comment-frame (⭐83)](https://github.com/s1n7ax/nvim-comment-frame) - Adds a comment frame based on the source file.
*   [danymat/neogen (⭐582)](https://github.com/danymat/neogen) - A better annotation generator. Supports multiple languages and annotation conventions.
*   [echasnovski/mini.nvim#mini.comment (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-comment.md) - Module of `mini.nvim` for per-line commenting. Fully supports dot-repeat.
*   [LudoPinelli/comment-box.nvim (⭐111)](https://github.com/LudoPinelli/comment-box.nvim) - Clarify and beautify your comments using boxes and lines.
*   [JoosepAlviste/nvim-ts-context-commentstring (⭐639)](https://github.com/JoosepAlviste/nvim-ts-context-commentstring) - Sets the `commentstring` option based on the cursor location in the file. The location is checked via treesitter queries.

### Formatting

*   [gpanders/editorconfig.nvim (⭐233)](https://github.com/gpanders/editorconfig.nvim) - An EditorConfig plugin written in Fennel.
*   [mhartington/formatter.nvim (⭐671)](https://github.com/mhartington/formatter.nvim) - A format runner written in Lua.
*   [lukas-reineke/lsp-format.nvim (⭐370)](https://github.com/lukas-reineke/lsp-format.nvim) - A wrapper around Neovims native LSP formatting.
*   [sbdchd/neoformat (⭐1.6k)](https://github.com/sbdchd/neoformat) - A (Neo)vim plugin for formatting code.
*   [cappyzawa/trim.nvim (⭐48)](https://github.com/cappyzawa/trim.nvim) - This plugin trims trailing whitespace and lines.
*   [mcauley-penney/tidy.nvim (⭐74)](https://github.com/mcauley-penney/tidy.nvim) - Clear trailing whitespace and empty lines at end of file on every save.
*   [MunifTanjim/prettier.nvim (⭐92)](https://github.com/MunifTanjim/prettier.nvim) - Prettier integration.
*   [echasnovski/mini.nvim#mini.align (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-align.md) - Module of `mini.nvim` for aligning text interactively (with or without instant preview).

#### Indent

*   [glepnir/indent-guides.nvim (⭐146)](https://github.com/glepnir/indent-guides.nvim) - Indent plugin.
*   [lukas-reineke/indent-blankline.nvim (⭐2.1k)](https://github.com/lukas-reineke/indent-blankline.nvim) - IndentLine replacement in Lua with more features and treesitter support.
*   [echasnovski/mini.nvim#mini.indentscope (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-indentscope.md) - Module of `mini.nvim` for visualizing and operating on indent scope. Supports customization of debounce delay, animation style, and different granularity of options for scope computing algorithm.
*   [NMAC427/guess-indent.nvim (⭐138)](https://github.com/NMAC427/guess-indent.nvim) - Automatic indentation style detection.
*   [Darazaki/indent-o-matic (⭐105)](https://github.com/Darazaki/indent-o-matic) - Dumb automatic fast indentation detection written in Lua.
*   [Abstract-IDE/penvim (⭐28)](https://github.com/Abstract-IDE/penvim) - Project's root directory and documents Indentation detector with project based config loader.
*   [yaocccc/nvim-hlchunk (⭐24)](https://github.com/yaocccc/nvim-hlchunk) - Highlight a `{}` chunk.

### Command Line

*   [notomo/cmdbuf.nvim (⭐58)](https://github.com/notomo/cmdbuf.nvim) - Alternative command-line-window plugin.
*   [gelguy/wilder.nvim (⭐834)](https://github.com/gelguy/wilder.nvim) - A plugin for fuzzy command line autocompletion.

### Session

*   [rmagatti/auto-session (⭐612)](https://github.com/rmagatti/auto-session) - A small automated session manager.
*   [echasnovski/mini.nvim#mini.sessions (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-sessions.md) - Module of `mini.nvim` for session management (read, write, delete).
*   [olimorris/persisted.nvim (⭐107)](https://github.com/olimorris/persisted.nvim) - Simple session management with git branching, autosave/autoload and Telescope support.
*   [Shatur/neovim-session-manager (⭐243)](https://github.com/Shatur/neovim-session-manager) - A simple wrapper around :mksession.
*   [jedrzejboczar/possession.nvim (⭐152)](https://github.com/jedrzejboczar/possession.nvim) - Flexible session management with arbitrary persistent data stored as JSON.

### Remote Development

*   [chipsenkbeil/distant.nvim (⭐633)](https://github.com/chipsenkbeil/distant.nvim) - Edit files, run programs, and work with LSP on a remote machine from the comfort of your local environment.
*   [jamestthompson3/nvim-remote-containers (⭐431)](https://github.com/jamestthompson3/nvim-remote-containers) - Develop inside docker containers, just like VSCode.
*   [esensar/nvim-dev-container (⭐169)](https://github.com/esensar/nvim-dev-container) - Neovim devcontainer.json and general development container support.

### Split and Window

*   [\~henriquehbr/ataraxis.lua](https://sr.ht/\~henriquehbr/ataraxis.lua) - A zen mode for improving code readability on Neovim.
*   [gitlab.com/yorickpeterse/nvim-window](https://gitlab.com/yorickpeterse/nvim-window) - Easily jump between Neovim windows.
*   [sindrets/winshift.nvim (⭐270)](https://github.com/sindrets/winshift.nvim) - Rearrange your windows with ease.
*   [beauwilliams/focus.nvim (⭐430)](https://github.com/beauwilliams/focus.nvim) - Auto-Focusing and Auto-Resizing Splits/Windows written in Lua! Vim splits on steroids.
*   [luukvbaal/stabilize.nvim (⭐332)](https://github.com/luukvbaal/stabilize.nvim) - Stabilized window content on window open/close events.
*   [anuvyklack/windows.nvim (⭐266)](https://github.com/anuvyklack/windows.nvim) - Automatically expand width of the current window. Maximizes and restore it. And all this with nice animations!
*   [nvim-zh/colorful-winsep.nvim (⭐125)](https://github.com/nvim-zh/colorful-winsep.nvim) - A configurable color split line.
*   [nyngwang/NeoNoName.lua (⭐21)](https://github.com/nyngwang/NeoNoName.lua) - A layout-preserving buffer-deleter.
*   [famiu/bufdelete.nvim (⭐249)](https://github.com/famiu/bufdelete.nvim) - Delete Neovim buffers without losing your window layout.
*   [echasnovski/mini.nvim#mini.bufremove (⭐1.1k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-bufremove.md) - Module of `mini.nvim` for buffer removing (unshow, delete, wipeout) while saving window layout.

#### Tmux

*   [aserowy/tmux.nvim (⭐283)](https://github.com/aserowy/tmux.nvim) - Tmux integration features pane movement and resizing.
*   [danielpieper/telescope-tmuxinator.nvim (⭐13)](https://github.com/danielpieper/telescope-tmuxinator.nvim) - Integration for tmuxinator with telescope.nvim.
*   [hkupty/nvimux (⭐407)](https://github.com/hkupty/nvimux) - Neovim as tmux replacement.
*   [numToStr/Navigator.nvim (⭐195)](https://github.com/numToStr/Navigator.nvim) - Smoothly navigate between Neovim splits and Tmux panes.
*   [declancm/windex.nvim (⭐45)](https://github.com/declancm/windex.nvim) - Collection of window functions which includes moving between, closing and maximizing Neovim splits and Tmux panes.

### Game

*   [ThePrimeagen/vim-be-good (⭐960)](https://github.com/ThePrimeagen/vim-be-good) - Vim-be-good is a Neovim plugin designed to make you better at Vim Movements.
*   [alec-gibson/nvim-tetris (⭐125)](https://github.com/alec-gibson/nvim-tetris) - Bringing emacs' greatest feature to Neovim - Tetris!.
*   [seandewar/nvimesweeper (⭐64)](https://github.com/seandewar/nvimesweeper) - Play Minesweeper in your favourite text editor.
*   [seandewar/killersheep.nvim (⭐43)](https://github.com/seandewar/killersheep.nvim) - Neovim port of killersheep.
*   [rktjmp/shenzhen-solitaire.nvim (⭐14)](https://github.com/rktjmp/shenzhen-solitaire.nvim) - Shenzhen I/O Solitaire port.

#### Competitive Programming

*   [p00f/cphelper.nvim (⭐66)](https://github.com/p00f/cphelper.nvim) - Neovim helper for competitive programming written in Lua.
*   [xeluxee/competitest.nvim (⭐123)](https://github.com/xeluxee/competitest.nvim) - A plugin to automate testcases management and checking for Competitive Programming contests.

### Preconfigured Configuration

*   [Abstract-IDE/Abstract (⭐118)](https://github.com/Abstract-IDE/Abstract) - Abstract, The Neovim configuration to achieve the power of Modern IDE.
*   [SpaceVim/SpaceVim](https://spacevim.org) - A community-driven modular Vim/Neovim distribution, like spacemacs but for Vim/Neovim.
*   [CosmicNvim/CosmicNvim (⭐755)](https://github.com/CosmicNvim/CosmicNvim) - CosmicNvim is a lightweight and opinionated Neovim config for web development, specifically designed to provide a 💫 COSMIC programming experience!
*   [artart222/CodeArt (⭐809)](https://github.com/artart222/CodeArt) - A fast general-purpose IDE written entirely in Lua with an installer for Linux/Windows/macOS and built in `:CodeArtUpdate` command for updating it.
*   [NTBBloodbath/doom-nvim (⭐773)](https://github.com/NTBBloodbath/doom-nvim) - Port of the doom-emacs framework, its goal is to add useful functions to Neovim to start working in a stable and efficient development environment without spending a lot of time configuring everything.
*   [crivotz/nv-ide (⭐397)](https://github.com/crivotz/nv-ide) - Neovim custom configuration, oriented for full stack developers (rails, ruby, php, html, css, SCSS, JavaScript).
*   [LunarVim/LunarVim (⭐12k)](https://github.com/LunarVim/LunarVim) - This project aims to help one transition away from VSCode, and into a superior text editing experience.
*   [hackorum/VapourNvim (⭐437)](https://github.com/hackorum/VapourNvim) - A Neovim config for THE ULTIMATE Vim IDE-like experience.
*   [vi-tality/neovitality (⭐52)](https://github.com/vi-tality/neovitality) - A full-featured Neovim distribution, packaged with Nix Flake for easy installation and reproducibility.
*   [siduck76/NvChad (⭐13k)](https://github.com/siduck76/NvChad) - An attempt to make Neovim cli as functional as an IDE while being very beautiful and less bloated.
*   [nvoid-lua/nvoid (⭐72)](https://github.com/nvoid-lua/nvoid) - Simple Neovim config written in Lua with all the modern features available in any **IDE**
*   [cstsunfu/.sea.nvim (⭐89)](https://github.com/cstsunfu/.sea.nvim) - A modular Neovim configuration with beautiful UI and some useful features(Pomodoro Clock, Window Number).
*   [shaeinst/roshnivim (⭐118)](https://github.com/shaeinst/roshnivim) - Roshnivim, can be called neovim's distro, is a predefined configs so that you don't need 1000hr to setup neovim as an IDE.
*   [AstroNvim/AstroNvim (⭐5.5k)](https://github.com/AstroNvim/AstroNvim) - AstroNvim is an aesthetic and feature-rich Neovim config that is extensible and easy to use with a great set of plugins.
*   [shaunsingh/nyoom.nvim (⭐394)](https://github.com/shaunsingh/nyoom.nvim) - Blazing fast, configurable, minimal and lispy neovim config written in Fennel. Base config for users to extend and add upon, leading to a more unique editing experience.
*   [CanKolay3499/CNvim (⭐16)](https://github.com/CanKolay3499/CNvim) - A lightweight Neovim config for web development.
*   [jrychn/moduleVim (⭐5)](https://github.com/jrychn/ModuleVim) - A very easy to use
    for backend and frontend, install lsp automatically.
*   [askfiy/nvim (⭐145)](https://github.com/askfiy/nvim) - An excellent Neovim configuration, which is as powerful as Vscode, is lightning fast ⚡️.
*   [imbacraft/dusk.nvim (⭐11)](https://github.com/imbacraft/dusk.nvim) - Dusk is a lightweight, aesthetically minimal Neovim config, written in Lua, able to provide for web and Java development.
*   [nvim-lua/kickstart.nvim (⭐537)](https://github.com/nvim-lua/kickstart.nvim) - A launch point for your personal Neovim configuration.
*   [cunderw/nvim (⭐5)](https://github.com/cunderw/nvim) - Neovim custom configuration, focused on JS/TS, Go, and Java development. Very IDE like.

## External

These tools are used externally to Neovim to enhance the experience.

### Version Manager

*   [MordechaiHadad/bob (⭐309)](https://github.com/MordechaiHadad/bob) - A cross platform and easy to use Neovim version manager.
*   [NTBBloodbath/nvenv (⭐42)](https://github.com/NTBBloodbath/nvenv) - A lightweight and blazing fast Neovim version manager.
*   [shohi/neva (⭐11)](https://github.com/shohi/neva) - A Neovim version manager written in Lua.

### Boilerplate

*   [gennaro-tedesco/boilit (⭐49)](https://github.com/gennaro-tedesco/boilit) - Create boilerplate structure plugins.
*   [m00qek/plugin-template.nvim (⭐59)](https://github.com/m00qek/plugin-template.nvim) - A plugin template that setups test infrastructure and GitHub Actions.
*   [ellisonleao/nvim-plugin-template (⭐64)](https://github.com/ellisonleao/nvim-plugin-template) - Another neovim plugin template, using GitHub's template feature.

## Vim

*   [Vimawesome](https://vimawesome.com/) - Showcases various plugins for Vim and has a [neovim tag](https://vimawesome.com/?q=tag:neovim) for other plugins targeting Neovim.
*   [awesome-vim (⭐1.7k)](https://github.com/akrawchyk/awesome-vim#tools) - Short list of Vim plugins and helpful guides.
*   [vim-plugin-list (⭐24)](https://github.com/altermo/vim-plugin-list) - List of Vim and Neovim plugins.

## Resource

*   [Neovimcraft](https://neovimcraft.com) - A site dedicated to searching specific plugins and guides for building plugins in Lua.
*   [TWiN](https://this-week-in-neovim.org) - TWiN (this-week-in-neovim.org) is dedicated to providing weekly news about Neovim and its ecosystem.

