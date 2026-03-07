# Awesome List Updates on Mar 09 - Mar 15, 2026

48 awesome lists updated this week.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Api Clients](/content/stepci/awesome-api-clients/week/README.md)

### Desktop

*   [EasyPostman (⭐580)](https://github.com/lakernote/EasyPostman) - An open-source API debugging and performance testing tool inspired by Postman and a simplified JMeter

## [2. Awesome Mqtt](/content/awesome-mqtt/awesome-mqtt/week/README.md)

### Platforms

*   [Iotellect](https://iotellect.com/) - Low-code IoT/IIoT platform for industrial automation, SCADA, BMS and remote monitoring. Supports MQTT, OPC-UA, Modbus and 100+ protocols with visual development tools and edge-cloud integration.

## [3. Awesome Vue](/content/vuejs/awesome-vue/week/README.md)

### Projects Using Vue.js / Open Source

*   [JARVIS (⭐3)](https://github.com/hyhmrright/JARVIS) - Self-hosted AI assistant platform with Vue 3 frontend, Pinia state management, TypeScript, and real-time SSE streaming chat. FastAPI backend with LangGraph ReAct agents, RAG knowledge base, multi-LLM support (DeepSeek/OpenAI/Anthropic), and plugin SDK.
*   [MYDY Dashboard (⭐0)](https://github.com/pyramide-agency/mydy-dashboard) - Self-hosted personal productivity and finance management dashboard with AI assistant, Kanban board, time tracking, and Telegram Mini App integration. Built with Nuxt 4 and Laravel 11.

### Components & Libraries / UI Components

*   [@witqq/spreadsheet (⭐7)](https://github.com/witqq/spreadsheet) - A canvas-based spreadsheet engine with zero dependencies, rendering 100K+ rows at 60fps with sorting, filtering, formulas, and collaboration.
*   [vue-timepicker (⭐6)](https://github.com/manos02/vue3-time-picker) - A lightweight, customizable timepicker component for Vue 3 with TypeScript support. Supports single/range selection, multiple formats, easy styling, validation and more.
*   [vue-superselect (⭐23)](https://github.com/nemanjamalesija/vue-superselect) - Headless, accessible, TypeScript-first select/combobox for Vue 3 with dual compound component and composable APIs.

## [4. Awesome Wardley Maps](/content/wardley-maps-community/awesome-wardley-maps/week/README.md)

### Development

*   [cli-owm (⭐0)](https://github.com/monkeypants/cli-owm) - Command-line tool that renders OnlineWardleyMaps DSL text to SVG. Pipes stdin to stdout, ships as npm package and standalone binaries. Uses the OnlineWardleyMaps parser.

## [5. Awesome V](/content/vlang/awesome-v/week/README.md)

### Command-line

*   [dnshammer (⭐0)](https://github.com/tailsmails/dnshammer) - A covert communication channel that encodes data into DNS cache timing differences.

## [6. Awesome Lit](/content/web-padawan/awesome-lit/week/README.md)

### Extensions

*   [`@tanstack/lit-table`](https://tanstack.com/table/latest/docs/framework/lit/lit-table) - Headless UI for building powerful tables & datagrids with Lit.

## [7. Htaccess](/content/phanan/htaccess/week/README.md)

### Rewrite and Redirection / Force www

### Force www

```apacheconf
RewriteEngine on
RewriteCond %{HTTP_HOST} ^example\.com [NC]
RewriteRule ^(.*)$ https://www.example.com/$1 [L,R=301,NC]
```

### Rewrite and Redirection / Force non-www

### Force non-www

It’s [still](https://www.sitepoint.com/domain-www-or-no-www/) [open](https://devcenter.heroku.com/articles/apex-domains) [for](https://yes-www.org/) [debate](https://no-www.org/) whether www or non-www is the way to go, so if you happen to be a fan of bare domains, here you go:

```apacheconf
RewriteEngine on
RewriteCond %{HTTP_HOST} ^www\.example\.com [NC]
RewriteRule ^(.*)$ https://example.com/$1 [L,R=301]
```

### Rewrite and Redirection / Remove Trailing Slash

### Remove Trailing Slash

This snippet will redirect paths ending in slashes to their non-slash-terminated counterparts (except for actual directories), e.g. `https://www.example.com/blog/` to `https://www.example.com/blog`. This is important for SEO, since it’s [recommended](https://overit.com/blog/canonical-urls) to have a canonical URL for every page.

```apacheconf
RewriteCond %{REQUEST_FILENAME} !-d
RewriteCond %{REQUEST_URI} (.+)/$
RewriteRule ^ %1 [R=301,L]
```

[Source](https://stackoverflow.com/questions/21417263/htaccess-add-remove-trailing-slash-from-url#27264788)

### Rewrite and Redirection / Redirect an Entire Site

### Redirect an Entire Site

```apacheconf
Redirect 301 / https://newsite.com/
```

This way does it with links intact. That is `www.oldsite.com/some/crazy/link.html` will become `www.newsite.com/some/crazy/link.html`. This is extremely helpful when you are just “moving” a site to a new domain. [Source](https://css-tricks.com/snippets/htaccess/301-redirects/)

### Rewrite and Redirection / Redirect Using RedirectMatch

### Redirect Using RedirectMatch

```apacheconf
RedirectMatch 301 /subdirectory(.*) https://www.newsite.com/newfolder/$1
RedirectMatch 301 ^/(.*).htm$ /$1.html
RedirectMatch 301 ^/200([0-9])/([^01])(.*)$ /$2$3
RedirectMatch 301 ^/category/(.*)$ /$1
RedirectMatch 301 ^/(.*)/htaccesselite-ultimate-htaccess-article.html(.*) /htaccess/htaccess.html
RedirectMatch 301 ^/(.*).html/1/(.*) /$1.html$2
RedirectMatch 301 ^/manual/(.*)$ https://www.php.net/manual/$1
RedirectMatch 301 ^/old-directory/(.*)$ /new-directory/$1
RedirectMatch 301 ^/z/(.*)$ https://static.askapache.com/$1
```

[Source](https://www.askapache.com/htaccess/301-redirect-with-mod_rewrite-or-redirectmatch.html#301_Redirects_RedirectMatch)

### Rewrite and Redirection / Alias “Clean” URLs

### Alias “Clean” URLs

This snippet lets you use “clean” URLs -- those without a PHP extension, e.g. `example.com/users` instead of `example.com/users.php`.

```apacheconf
RewriteEngine On
RewriteCond %{SCRIPT_FILENAME} !-d
RewriteRule ^([^.]+)$ $1.php [NC,L]
```

[Source](https://www.abeautifulsite.net/access-pages-without-the-php-extension-using-htaccess/)

### Security / Deny All Access

### Deny All Access

```apacheconf
Require all denied
```

But wait, this will lock you out from your content as well! Thus introducing...

### Security / Deny All Access Except Yours

### Deny All Access Except Yours

```apacheconf
Require all denied
Require ip xxx.xxx.xxx.xxx
```

`xxx.xxx.xxx.xxx` is your IP. If you replace the last three digits with `0/12` for example, this will specify a range of IPs within the same network, thus saving you the trouble to list all allowed IPs separately. [Source](https://speckyboy.com/2013/01/08/useful-htaccess-snippets-and-hacks/)

Now of course there's a reversed version:

### Security / Allow All Access Except Spammers'

### Allow All Access Except Spammers'

```apacheconf
Require all granted
Require not ip xxx.xxx.xxx.xxx
Require not ip xxx.xxx.xxx.xxy
```

### Security / Disable Image Hotlinking

### Disable Image Hotlinking

```apacheconf
RewriteEngine on
# Remove the following line if you want to block blank referrer too
RewriteCond %{HTTP_REFERER} !^$

RewriteCond %{HTTP_REFERER} !^https?://(.+\.)?example.com [NC]
RewriteRule \.(jpe?g|png|gif|bmp|webp|avif|svg|ico)$ - [NC,F,L]

# If you want to display a “blocked” banner in place of the hotlinked image,
# replace the above rule with:
# RewriteRule \.(jpe?g|png|gif|bmp|webp|avif|svg|ico) https://example.com/blocked.png [R,L]
```

### Security / Disable Image Hotlinking for Specific Domains

### Disable Image Hotlinking for Specific Domains

Sometimes you want to disable image hotlinking from some bad guys only.

```apacheconf
RewriteEngine on
RewriteCond %{HTTP_REFERER} ^https?://(.+\.)?badsite\.com [NC,OR]
RewriteCond %{HTTP_REFERER} ^https?://(.+\.)?badsite2\.com [NC,OR]
RewriteRule \.(jpe?g|png|gif|bmp|webp|avif|svg|ico)$ - [NC,F,L]

# If you want to display a “blocked” banner in place of the hotlinked image,
# replace the above rule with:
# RewriteRule \.(jpe?g|png|gif|bmp|webp|avif|svg|ico) https://example.com/blocked.png [R,L]
```

### Security / Block Visitors by Referrer

### Block Visitors by Referrer

This denies access for all users who are coming from (referred by) a specific domain.
[Source](https://www.htaccess-guide.com/deny-visitors-by-referrer/)

```apacheconf
RewriteEngine on
# Options +FollowSymlinks
RewriteCond %{HTTP_REFERER} somedomain\.com [NC,OR]
RewriteCond %{HTTP_REFERER} anotherdomain\.com
RewriteRule .* - [F]
```

### Security / Block Specific User Agents

### Block Specific User Agents

This will block specific user agents from accessing your site, useful for blocking scrapers and bad bots.

```apacheconf
RewriteEngine on
RewriteCond %{HTTP_USER_AGENT} BadBot [NC,OR]
RewriteCond %{HTTP_USER_AGENT} EvilScraper [NC]
RewriteRule .* - [F,L]
```

### Security / Content Security Policy (CSP)

### Content Security Policy (CSP)

A Content Security Policy header helps mitigate cross-site scripting (XSS) and other code injection attacks by declaring which dynamic resources are allowed to load.

```apacheconf
<IfModule mod_headers.c>
    Header set Content-Security-Policy "default-src 'self'; script-src 'self'; style-src 'self'"
</IfModule>
```

Adjust the directives to fit your needs. See the [CSP reference](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy) for all available directives.

### Security / Prevent MIME Type Sniffing

### Prevent MIME Type Sniffing

This prevents browsers from trying to guess ("sniff") the MIME type of a resource, which can have security implications. The browser will trust what the server says and block the resource if it doesn't match the expected type.

```apacheconf
<IfModule mod_headers.c>
    Header set X-Content-Type-Options "nosniff"
</IfModule>
```

### Security / Set Referrer Policy

### Set Referrer Policy

Control how much referrer information is included with requests. This helps protect user privacy by preventing the full URL from leaking to external sites.

```apacheconf
<IfModule mod_headers.c>
    Header set Referrer-Policy "strict-origin-when-cross-origin"
</IfModule>
```

### Security / Set Permissions Policy

### Set Permissions Policy

Restrict which browser features your site can use, such as camera, microphone, geolocation, etc.

```apacheconf
<IfModule mod_headers.c>
    Header set Permissions-Policy "camera=(), microphone=(), geolocation=(), interest-cohort=()"
</IfModule>
```

### Performance / Remove Server Signature

### Remove Server Signature

Prevent Apache from exposing its version number and OS information in HTTP headers and error pages.

```apacheconf
ServerSignature Off
```

### Performance / Set Cache-Control Headers

### Set Cache-Control Headers

`Cache-Control` headers provide more fine-grained control over browser caching than Expires headers. You can use both together for maximum compatibility.

```apacheconf
<IfModule mod_headers.c>
    # Cache CSS and JS for 1 year
    <FilesMatch "\.(css|js)$">
        Header set Cache-Control "max-age=31536000, public"
    </FilesMatch>

    # Cache images for 1 month
    <FilesMatch "\.(jpe?g|png|gif|webp|avif|svg|ico)$">
        Header set Cache-Control "max-age=2592000, public"
    </FilesMatch>

    # Cache fonts for 1 month
    <FilesMatch "\.(woff2?|ttf|otf)$">
        Header set Cache-Control "max-age=2592000, public"
    </FilesMatch>

    # Do not cache HTML
    <FilesMatch "\.(html|htm)$">
        Header set Cache-Control "no-cache, no-store, must-revalidate"
    </FilesMatch>
</IfModule>
```

### Miscellaneous / Turn eTags Off

### Turn eTags Off

By removing the `ETag` header, you disable caches and browsers from being able to validate files, so they are forced to rely on your `Cache-Control` and `Expires` header. [Source](https://www.askapache.com/htaccess/apache-speed-etags.html)

```apacheconf
<IfModule mod_headers.c>
    Header unset ETag
</IfModule>
FileETag None
```

### Miscellaneous / Custom Error Pages

### Custom Error Pages

```apacheconf
ErrorDocument 500 "Houston, we have a problem."
ErrorDocument 401 https://error.example.com/mordor.html
ErrorDocument 404 /errors/halflife3.html
```

### Miscellaneous / Custom Maintenance Page

### Custom Maintenance Page

Redirect all traffic to a maintenance page while still allowing access from a specific IP address.

```apacheconf
RewriteEngine on
RewriteCond %{REMOTE_ADDR} !^xxx\.xxx\.xxx\.xxx
RewriteCond %{REQUEST_URI} !/maintenance.html$ [NC]
RewriteCond %{REQUEST_URI} !\.(css|js|png|jpe?g|gif|svg|ico)$ [NC]
RewriteRule .* /maintenance.html [R=503,L]
```

Replace `xxx.xxx.xxx.xxx` with your IP address to retain access while the site is under maintenance.

### Miscellaneous / Enable CORS

### Enable CORS

Enable Cross-Origin Resource Sharing (CORS) for your site, allowing other domains to make requests to your server.

```apacheconf
<IfModule mod_headers.c>
    Header set Access-Control-Allow-Origin "*"
    Header set Access-Control-Allow-Methods "GET, POST, PUT, DELETE, OPTIONS"
    Header set Access-Control-Allow-Headers "Content-Type, Authorization"
</IfModule>
```

To restrict access to specific domains, replace `*` with the domain, e.g. `https://example.com`.

### Miscellaneous / Set Custom MIME Types

### Set Custom MIME Types

Define custom MIME types for file formats that Apache may not recognize by default.

```apacheconf
AddType application/manifest+json .webmanifest
AddType application/wasm .wasm
AddType application/x-ndjson .ndjson
AddType text/vtt .vtt
```

### Miscellaneous / Switch to Another PHP Version

### Switch to Another PHP Version

If you’re on a shared host, chances are there are more than one version of PHP installed, and sometimes you want a specific version for your website. The following snippet should switch the PHP version for you.

```apacheconf
AddHandler application/x-httpd-php84 .php

# Alternatively, you can use AddType
AddType application/x-httpd-php84 .php
```

### Miscellaneous / Serve WebP/AVIF Images

### Serve WebP/AVIF Images

If a modern format image (AVIF or WebP) with the same name exists alongside the original jpg/png, it will be served instead. AVIF is preferred over WebP when the browser supports both.

```apacheconf
RewriteEngine On

# Serve AVIF if supported and available
RewriteCond %{HTTP_ACCEPT} image/avif
RewriteCond %{DOCUMENT_ROOT}/$1.avif -f
RewriteRule (.+)\.(jpe?g|png)$ $1.avif [T=image/avif,E=accept:1]

# Otherwise, serve WebP if supported and available
RewriteCond %{HTTP_ACCEPT} image/webp
RewriteCond %{DOCUMENT_ROOT}/$1.webp -f
RewriteRule (.+)\.(jpe?g|png)$ $1.webp [T=image/webp,E=accept:1]
```

## [8. Awesome Cli Apps in a Csv](/content/toolleeo/awesome-cli-apps-in-a-csv/week/README.md)

### AI terminal command generator

*   [Blitzdenk (⭐5)](https://github.com/Lommix/blitzdenk) - A minimal multi purpose personal AI TUI.

### Chat and instant messaging

*   [Endcord (⭐626)](https://github.com/mzivic7/endcord) - Discord TUI client.
*   [Gomphotherium (⭐103)](https://github.com/mrusme/gomphotherium) - A command line Mastodon client.
*   [gurk (⭐1.2k)](https://github.com/boxdot/gurk-rs) - Signal Messenger client for terminal.

### Clean up of files and directories

*   [NTC](https://codeberg.org/ItsZariep/ntc) - A program that, based on the contents of a folder, create tabs (subfolders inside the selected folder) and displays their contents.

### Command launchers

*   [Steam TUI (⭐992)](https://github.com/dmadisetti/steam-tui) - A simple TUI client for steamcmd, allows for the graphical launching, updating, and downloading of steam games through a simple terminal client.

### DevOps

*   [lazycontainer (⭐342)](https://github.com/andreybleme/lazycontainer) - TUI for managing Apple containers.
*   [podman-tui (⭐1.1k)](https://github.com/containers/podman-tui) - TUI for Podman environment.
*   [sen (⭐1k)](https://github.com/TomasTomecek/sen) - TUI for containers (manages interactively and inspects containers, dashboard view for containers and images, searching and filtering, real-time updates, tree view of all images).

### Editors

*   [Amp (⭐4k)](https://github.com/jmacdonald/amp) - A complete text editor for your terminal.
*   [C-EDIT (⭐294)](https://github.com/velorek1/c-edit) - A text editor in C with drop down menus in the style of MS-DOS Editor.
*   [Helix](https://helix-editor.com/) - A text editor with multiple selections, tree-sitter integration, powerful code manipulation, language server support and other modern builtin features.
*   [maki](https://sr.ht/~bscit/maki/) - A simple text editor with file navigation and an emphasis on preserving battery life.
*   [Turbo (⭐631)](https://github.com/magiblot/turbo) - An experimental text editor for the terminal, based on Scintilla and Turbo Vision.

### File manager

*   [adbtuifm (⭐184)](https://github.com/darkhz/adbtuifm) - A TUI file manager for the Android Debug Bridge, to make transfers between the device and client easier.
*   [Far2l (⭐2.1k)](https://github.com/elfmz/far2l) - Linux port of Far v2 file manager.
*   [fml (⭐95)](https://github.com/wick3dr0se/fml) - Simple and fast file manager written in BASH.
*   [sfm (⭐251)](https://github.com/afify/sfm) - Simple file manager for unix-like systems with kernel event notifications, monitoring filesystem events, dual pane and more.

### Games

*   [awkaster (⭐2.5k)](https://github.com/TheMozg/awk-raycaster) - Pseudo-3D shooter written completely in gawk using raycasting technique.
*   [Balatro TUI  (⭐162)](https://github.com/Passeriform/BalatroTUI) - A minimal TUI clone of Balatro built in Rust.
*   [botany (⭐515)](https://github.com/jifunks/botany/) - A command line, realtime, virtual plant buddy.
*   [Brick Game emulator (⭐22)](https://github.com/ilyakurdyukov/brickgame-4bit) - Brick Game emulator that uses 4-bit microcontroller from Holtek.
*   [Brogue CE](https://sites.google.com/site/broguegame/) - Single-player strategy game set in the halls of a mysterious and randomly-generated dungeon.
*   [csol (⭐97)](https://github.com/nielssp/csol) - Collection of solitaire/patience games, such as Klondike, FreeCell, Spider, and Yukon.
*   [DOOM-ASCII (⭐815)](https://github.com/wojciech-graj/doom-ascii) - Text-based DOOM running in terminal without sound.
*   [Gameboy Emulator (⭐1.6k)](https://github.com/gabrielrcouto/php-terminal-gameboy-emulator) - A PHP Terminal GameBoy Emulator.
*   [go-life (⭐144)](https://github.com/sachaos/go-life) - Terminal based Conway's Game of Life, implemented in Go.
*   [Micro Snake (⭐36)](https://github.com/troglobit/snake) - A small snake game, utilizing ANSI escape sequences to draw the board.
*   [Micro Tetris (⭐162)](https://github.com/troglobit/tetris) - One of the smallest Tetris implementations in the world, utilizing only ANSI escape sequences to draw the board.
*   [Moon-Buggy (⭐105)](https://github.com/seehuhn/moon-buggy) - Game where you drive a car across the moon and jump over craters.
*   [MyMan](https://sourceforge.net/projects/myman/) - Video game for color and monochrome text terminals in the genre of Namco's Pac-Man.
*   [nchess (⭐19)](https://github.com/billyvinning/nchess) - Chess in the terminal, written in C (player vs player in the same terminal).
*   [nInvaders](http://ninvaders.sourceforge.net/) - Game of Space Invaders for terminal.
*   [Noughts & Crosses (Tic Tac Toe) (⭐14)](https://github.com/vyalovvldmr/onx) - Noughts & Crosses client-server online game with your partner through websockets.
*   [nSnake (⭐218)](https://github.com/alexdantas/nSnake) - The classic snake game in terminal with textual interface.
*   [nudoku (⭐363)](https://github.com/jubalh/nudoku) - ncurses based sudoku game.
*   [snake (⭐113)](https://github.com/wick3dr0se/snake) - A minimal TUI snake game written in pure BASH v5\_1+.
*   [Square Tic Tac Toe (⭐961)](https://github.com/learnbyexample/TUI-apps/tree/main/SquareTicTacToe) - A game like Tic Tac Toe, but you have to form a square with 4 corners instead of a line.
*   [SSHTron (⭐2.5k)](https://github.com/zachlatta/sshtron) - Multiplayer lightcycle game that runs through SSH.
*   [sudoku-rs (⭐25)](https://github.com/MitchelPaulin/sudoku-rs) - Sudoku game for the terminal, built with tui-rs.
*   [Sweeper (⭐5)](https://github.com/igor47/sweeper) - Basic ncurses Minesweeper game, wirtten in python, using curtsies library.
*   [tty-solitaire (⭐334)](https://github.com/mpereira/tty-solitaire) - Solitaire game for the terminal ncurses based.
*   [Wocogo](https://codeberg.org/kedlubnowski/wocogo) - Terminal word game that challenges players to combine given segments into existing words, uses rich library.
*   [Wordle (⭐2)](https://github.com/m-dango/raku-wordle/) - Wordle game, written in Raku.
*   [Zigtris (⭐28)](https://github.com/ringtailsoftware/zigtris) - Terminal tetris game.
*   [Zoridor (⭐14)](https://github.com/ringtailsoftware/zoridor) - Terminal and web version of the Quoridor board game.

### Learning and didactic tools

*   [Maze TUI (⭐75)](https://github.com/agl-alexglopez/maze-tui) - Build mazes, solve them with various algorithms and visualize them.

### Networking

*   [Thymus (⭐26)](https://github.com/blademd/thymus) - An interactive browser & editor for network configuration files.

### Note taking

*   [Diary (⭐72)](https://github.com/actuday6418/Diary) - A diary app written in Rust that encrypts both text and file data, and can decrypt and build a rich HTML representation of your diary when required.

### Online search and resources

*   [MAL-Cli (⭐137)](https://github.com/L4z3x/mal-cli) - A terminal interface for the official myanimelist api written in Rust and Ratatui.

## [9. Typedb Awesome](/content/vaticle/typedb-awesome/week/README.md)

### Open source projects using TypeDB

*   [`go-typeql`](https://github.com/CaliLuke/go-typeql) - A Go ORM for TypeDB 3.x with type-safe CRUD, query building, migrations, and code generation.
*   [`skills`](https://github.com/CaliLuke/skills) - A collection of agent skills, including a TypeDB skill for agent workflows.

## [10. Awesome Cpp](/content/fffaraz/awesome-cpp/week/README.md)

### Frameworks

*   [WUI (⭐60)](https://github.com/intent-garden/wui) - WUI (Window User Interface Library) is a cross-platform library for creating graphical user interfaces in C++17+ \[Boost][website](https://libwui.org)

### Audio

*   [PocketSphinx (⭐4.3k)](https://github.com/cmusphinx/pocketsphinx) - A lightweight speech recognition engine. \[BSD-2-Clause] [website](https://cmusphinx.github.io/)

### Biology

*   [htslib (⭐910)](https://github.com/samtools/htslib) - A C library for reading/writing high-throughput sequencing data. \[MIT/BSD] [website](http://www.htslib.org/)

### CLI

*   [Ginseng (⭐65)](https://github.com/chewax/Ginseng) - A C++ command-line argument parser. \[MIT]

### Compression

*   [cmix (⭐694)](https://github.com/byronknoll/cmix) - A lossless data compression program that aims for the highest compression ratios at the cost of speed. \[GPL-3.0]
*   [LZSSE-SIMDe (⭐19)](https://github.com/nemequ/LZSSE-SIMDe) - A portable SIMD implementation of LZSSE compression. \[BSD-2-Clause]
*   [Zopfli (⭐3.6k)](https://github.com/google/zopfli) - A compression library that performs very good but slow deflate/zlib compression. \[Apache-2.0]

### Concurrency

*   [libcu++ (⭐2.3k)](https://github.com/NVIDIA/libcudacxx) - The NVIDIA C++ Standard Library, providing heterogeneous implementation of C++ Standard Library facilities. \[Apache-2.0]
*   [nvthreads (⭐26)](https://github.com/HewlettPackard/nvthreads) - A library for enabling efficient and persistent threading in C/C++. \[LGPL-2.1]

### Containers

*   [CRoaring (⭐1.8k)](https://github.com/RoaringBitmap/CRoaring) - Roaring bitmaps in C (and C++), with SIMD optimizations. \[Apache-2.0]
*   [fifo\_map (⭐209)](https://github.com/nlohmann/fifo_map) - A FIFO-ordered associative container for C++. \[MIT]
*   [ordered-map (⭐567)](https://github.com/Tessil/ordered-map) - A C++ hash map and hash set which preserves the order of insertion. \[MIT]

### Cryptography

*   [tiny-ECDH-c (⭐290)](https://github.com/kokke/tiny-ECDH-c) - Small and portable implementation of the ECDH key agreement protocol in C. \[PublicDomain]
*   [Qt-Secret (⭐267)](https://github.com/QuasarApp/Qt-Secret) - Simple encryption library based on Qt for C++ projects. \[LGPL]
*   [micro-ecc (⭐1.4k)](https://github.com/kmackay/micro-ecc) - A small and fast ECDH and ECDSA implementation for 8-bit, 32-bit, and 64-bit processors. \[BSD-2-Clause]
*   [crypto-algorithms (⭐2k)](https://github.com/B-Con/crypto-algorithms) - Basic implementations of standard cryptography algorithms (AES, SHA, etc.) in C. \[PublicDomain]
*   [aes-stream (⭐21)](https://github.com/jedisct1/aes-stream) - A fast AES-based stream cipher for C. \[ISC]

### Database

*   [constexpr-sql (⭐141)](https://github.com/mkitzan/constexpr-sql) - A compile-time SQL query parser and executor in C++17. \[MIT]
*   [NuDB (⭐409)](https://github.com/cppalliance/NuDB) - A fast, append-only key/value store for SSD drives. \[Boost]

### Data visualization

*   [matplotlib-cpp (⭐4.7k)](https://github.com/lava/matplotlib-cpp) - A C++ wrapper around the matplotlib Python plotting library. \[MIT]

### Debug

*   [Attest (⭐4)](https://github.com/tugglecore/attest) - Cross-platform, heap-free C test framework with parameterized and lifecycle-aware tests and assertions with ad-hoc formatted messages. \[MIT]
*   [MTuner (⭐2.8k)](https://github.com/milostosic/MTuner) - A C/C++ memory profiler and memory leak finder for Windows, PlayStation, and other platforms. \[BSD-2-Clause]
*   [heaptrack (⭐4k)](https://github.com/KDE/heaptrack) - A heap memory profiler for Linux. \[LGPL-2.1]

### GUI

*   [GuiLite (⭐7.7k)](https://github.com/idea4good/GuiLite) - The smallest header-only GUI library (5 KLOC) for all platforms. \[Apache-2.0]
*   [LCUI (⭐4.3k)](https://github.com/lc-soft/LCUI) - A small C library for building user interfaces with C, XML and CSS. \[MIT]

### Image Processing

*   [OpenImageDenoise (⭐2k)](https://github.com/OpenImageDenoise/oidn) - High-performance, high-quality denoising library for ray-traced images. \[Apache-2.0] [website](https://www.openimagedenoise.org/)
*   [bitmap (⭐178)](https://github.com/ArashPartow/bitmap) - C++ Bitmap Library for reading, writing, and processing BMP image files. \[MIT]

### JSON

*   [libdart (⭐80)](https://github.com/target/libdart) - A high-performance, network-optimized JSON manipulation library. \[MIT]

### Logging

*   [logfault (⭐63)](https://github.com/jgaa/logfault) - A simple, elegant and efficient C++ header-only logging library. \[MIT]

### Machine Learning

*   [TensorComprehensions (⭐1.8k)](https://github.com/facebookresearch/TensorComprehensions) - A fully-functional C++ library to automatically synthesize high-performance machine learning kernels. \[Apache-2.0]
*   [kann (⭐746)](https://github.com/attractivechaos/kann) - A lightweight C library for artificial neural networks. \[MIT]

### Math

*   [Fastor (⭐832)](https://github.com/romeric/Fastor) - A lightweight high performance tensor algebra framework for modern C++. \[MIT]
*   [geogram (⭐2.4k)](https://github.com/BrunoLevy/geogram) - A programming library of geometric algorithms. \[BSD-3-Clause]
*   [std-simd (⭐639)](https://github.com/VcDevel/std-simd) - A portable implementation of std::experimental::simd for C++. \[BSD-3-Clause]
*   [libdivide (⭐1.3k)](https://github.com/ridiculousfish/libdivide) - Optimized integer division for C/C++ using libdivide. \[zlib] [website](https://libdivide.com)
*   [fpsqrt (⭐94)](https://github.com/chmike/fpsqrt) - Fast fixed point and floating point square root for C. \[MIT]
*   [fastmod (⭐341)](https://github.com/lemire/fastmod) - Header-only fast C/C++ library for computing remainders and modular reductions. \[Apache-2.0]
*   [Spectra (⭐835)](https://github.com/yixuan/spectra) - A C++ library for large scale eigenvalue problems, built on top of Eigen. \[MPL2] [website](https://spectralib.org)
*   [FastNoiseSIMD (⭐627)](https://github.com/Auburns/FastNoiseSIMD) - A library for SIMD-accelerated noise generation functions. \[MIT]

### Memory Allocation

*   [Mesh (⭐1.8k)](https://github.com/plasma-umass/Mesh) - A memory allocator that automatically reduces the memory footprint of C/C++ applications. \[Apache-2.0]
*   [rpmalloc (⭐2.4k)](https://github.com/rampantpixels/rpmalloc) - A public domain cross-platform lock-free thread-caching 16-byte aligned memory allocator. \[PublicDomain]
*   [TLSF (⭐1.5k)](https://github.com/mattconte/tlsf) - Two-Level Segregated Fit memory allocator, a general purpose dynamic memory allocator. \[BSD]

### Networking

*   [OpenDDS (⭐1.5k)](https://github.com/objectcomputing/OpenDDS) - An open source C++ implementation of the Object Management Group (OMG) Data Distribution Service (DDS). \[Apache2]
*   [easyhttpcpp (⭐168)](https://github.com/sony/easyhttpcpp) - A cross-platform HTTP client library providing a caching facility from Sony. \[MIT]
*   [GameNetworkingSockets (⭐9.3k)](https://github.com/ValveSoftware/GameNetworkingSockets) - Reliable & unreliable messages over UDP by Valve. Connection-oriented API (like TCP). \[BSD-3-Clause]
*   [wepoll (⭐1.1k)](https://github.com/piscisaureus/wepoll) - A Windows epoll wrapper based on Winsock. \[BSD-2-Clause]

### Physics

*   [tungsten (⭐1.8k)](https://github.com/tunabrain/tungsten) - A high-performance physically based renderer in C++. \[zlib]

### Regular Expression

*   [Pawn.Regex (⭐47)](https://github.com/urShadow/Pawn.Regex) - A Pawn plugin that provides support for regular expressions using C++11 std::regex. \[MIT]

### Scripting

*   [MuJS](https://codeberg.org/ccxvii/mujs) - An embeddable Javascript interpreter in C. \[ISC] [website](http://mujs.com)
*   [hobbes (⭐1.2k)](https://github.com/Morgan-Stanley/hobbes) - A language and an embedded JIT compiler from Morgan Stanley. \[Apache-2.0]

### Serialization

*   [fbthrift (⭐2.7k)](https://github.com/facebook/fbthrift) - Facebook's branch of Apache Thrift, including a serialization library and RPC framework. \[Apache-2.0]

### Video

*   [libuvc (⭐1.1k)](https://github.com/libuvc/libuvc) - A cross-platform library for USB video devices. \[BSD]

### Web Application Framework

*   [aeronet (⭐34)](https://github.com/sjanel/aeronet) - High-performance, modular C++ HTTP/1.1, HTTP/2 and WebSocket microservices framework focused on performance and scalability. \[MIT]
*   [httpserver.h (⭐1.9k)](https://github.com/jeremycw/httpserver.h) - A single-header HTTP server library for C. \[MIT]
*   [libhttp (⭐1k)](https://github.com/lammertb/libhttp) - A cross-platform HTTP and HTTPS library in C/C++. \[MIT]

### Miscellaneous

*   [Dragonbox (⭐798)](https://github.com/jk-jeon/dragonbox) - Reference implementation of a new float-to-string conversion algorithm in C++. \[Apache2/BSL-1.0]
*   [Gear-Lib (⭐3.2k)](https://github.com/gozfree/gear-lib) - A collection of basic libraries in POSIX C for embedded and network service development. \[MIT]
*   [single\_file\_libs (⭐9.8k)](https://github.com/r-lyeh/single_file_libs) - C/C++ open-source libraries with minimal dependencies. \[Various]
*   [spy (⭐157)](https://github.com/jfalcou/spy) - A C++17 constexpr library for detecting OS, compiler, architecture, and SIMD at compile time. \[MIT]
*   [licensepp (⭐429)](https://github.com/amrayn/licensepp) - A software license management library for C++ projects. \[Apache-2.0]
*   [tinydir (⭐865)](https://github.com/cxong/tinydir) - A lightweight, portable, and easy to integrate C directory and file reader. \[BSD-2-Clause]
*   [Cello (⭐7.1k)](https://github.com/orangeduck/Cello) - Higher level programming in C, including generic data structures and polymorphism. \[BSD-2-Clause] [website](http://libcello.org/)
*   [dyno (⭐1k)](https://github.com/ldionne/dyno) - A C++ library for runtime polymorphism with value semantics. \[Boost]
*   [PolyHook (⭐924)](https://github.com/stevemk14ebr/PolyHook) - A C++ x86/x64 hooking library. \[MIT]
*   [Verdigris (⭐673)](https://github.com/woboq/verdigris) - A header-only library that allows using Qt without the need for moc. \[MIT]
*   [Flicks (⭐1.4k)](https://github.com/OculusVR/Flicks) - A unit of time defined by Facebook/Oculus for exact representation of common frame rates. \[BSD]
*   [Linq (⭐666)](https://github.com/pfultz2/Linq) - Provides a LINQ syntax for list comprehension in C++. \[Boost]
*   [libcorrect (⭐424)](https://github.com/quiet/libcorrect) - A C library for convolutional codes and Reed-Solomon error correction. \[BSD-3-Clause]
*   [libfsm (⭐978)](https://github.com/katef/libfsm) - A library for building and executing finite state machines, including regex and glob. \[BSD-2-Clause]
*   [origin (⭐134)](https://github.com/asutton/origin) - A C++ library for concepts, diagnostics, and other foundational utilities.

### Compiler

*   [sierra](https://sierra-lang.github.io/) - A CISC-oriented programming language focused on creating maintainable programs.
*   [movfuscator (⭐10k)](https://github.com/xoreaxeaxeax/movfuscator) - The single instruction C compiler, compiling programs into only mov instructions. \[MIT]

### Build Systems

*   [awesome-cmake (⭐5.3k)](https://github.com/onqtam/awesome-cmake) - A curated list of awesome CMake scripts, modules, and resources.
*   [boost-cmake (⭐408)](https://github.com/Orphis/boost-cmake) - CMake modules for Boost libraries. \[BSD-3-Clause]
*   [cmake-examples (⭐1.2k)](https://github.com/pr0g/cmake-examples) - A collection of useful CMake examples for various scenarios. \[MIT]

### Static Code Analysis

*   [CodeCompass (⭐589)](https://github.com/Ericsson/CodeCompass) - An open-source code comprehension tool for large C/C++ projects. \[GPL-3.0]
*   [CodeChecker (⭐2.5k)](https://github.com/Ericsson/codechecker) - An analyzer tooling, defect database and viewer extension for the Clang Static Analyzer and Clang-Tidy. \[Apache-2.0]

### Articles

*   [All C++20 core language features with examples](https://oleksandrkvl.github.io/2021/04/02/cpp-20-overview.html) - A reference of all C++20 core language features with examples.
*   [Memory Footprint of GUI Toolkits](https://szibele.com/memory-footprint-of-gui-toolkits/) - A comparison of the memory footprint of various GUI toolkits.
*   [C++ UI Libraries](https://philippegroarke.com/posts/2018/c++_ui_solutions/) - A comprehensive list of C++ UI solutions.
*   [C++ Compilation (⭐1.2k)](https://github.com/green7ea/cpp-compilation) - A short description of the C++ compilation process.
*   [Books on C++17](https://blogs.msdn.microsoft.com/vcblog/2018/09/25/books-on-c17/) - A list of books on C++17.
*   [modern-cpp-features (⭐22k)](https://github.com/AnthonyCalandra/modern-cpp-features) - A cheatsheet of modern C++ language and library features.
*   [Choosing Some C++ Over C](https://medium.com/@davidtstrauss/choosing-some-c-over-c-f5acb3dce4f5) - An article about when to use C++ instead of C.
*   [C++ 17 Features](http://www.bfilipek.com/2017/01/cpp17features.html) - A comprehensive list of C++17 features.
*   [Master C Programming with Open Source Books](https://www.ossblog.org/master-c-programming-with-open-source-books/) - A curated list of open source books for learning C programming.

### Websites

*   [C++ Resources](https://andreasfertig.com/cpp-resources/) - A collection of C++ resources including books, articles, and tools.
*   [CppPatterns (⭐1.5k)](https://github.com/sftrabbit/CppPatterns-Patterns) - A repository of modern C++ patterns and idioms. [website](https://cpppatterns.com)
*   [Function Pointers (⭐33)](https://github.com/jerryryle/fuckingfunctionpointers.com) - A guide to understanding function pointers in C/C++.

### Other Awesome Projects

*   [awesome-ld-preload (⭐911)](https://github.com/gaul/awesome-ld-preload) - A curated list of resources related to LD\_PRELOAD.
*   [awesome-static-analysis (⭐14k)](https://github.com/mre/awesome-static-analysis) - A curated list of static analysis tools for all programming languages.
*   [cpp\_functional\_programming (⭐700)](https://github.com/graninas/cpp_functional_programming) - A list of materials and links for C++ functional programming.
*   [algorithms\_and\_data\_structures (⭐6.1k)](https://github.com/mandliya/algorithms_and_data_structures) - Implementation of algorithms and data structures in C++.

## [11. Awesome Nextjs](/content/unicodeveloper/awesome-nextjs/week/README.md)

### Boilerplates

*   [Kaiforge Lite (⭐0)](https://github.com/DevxiaLabs/kaiforge-lite) - Free and open-source Next.js admin dashboard template with Tailwind CSS, dark mode, and multiple color themes.

## [12. Awesome Tmux](/content/rothgar/awesome-tmux/week/README.md)

### Tools and session management

*   [tmux-grip](https://github.com/leohenon/tmux-grip) Pin tmux sessions to fixed numbered slots with direct key jumps and a popup manager

## [13. Awesome Keycloak](/content/thomasdarimont/awesome-keycloak/week/README.md)

### Community Extensions

*   [Pin Code Authenticator for Keycloak ACR/LOA (⭐0)](https://github.com/ldesroch/keycloak-pin-code-authenticator)

## [14. Awesome Django](/content/wsvincent/awesome-django/week/README.md)

### Third-Party Packages / Admin

*   [dj-control-room](https://github.com/yassi/dj-control-room) - Build a control plane with a suite of operational tools inside the Django admin (Redis, cache, Celery, URLs, and more).

## [15. Awesome Godot](/content/godotengine/awesome-godot/week/README.md)

### 3D / Godot 4

*   [Sunder](https://codeberg.org/sunder/sunder) - An open-source, fast-paced multiplayer shooter game inspired by Tribes, with jetpacks, skis and vehicles.

### GDScript/C# editor support / Godot version unknown

*   [Neovim](https://github.com/Mathijs-Bakker/godotdev.nvim) - A batteries-included Neovim plugin for Godot 4.x game development. Use Neovim as a fully featured external editor for Godot, with minimal setup.

## [16. Awesome Chrome Devtools](/content/ChromeDevTools/awesome-chrome-devtools/week/README.md)

### Accessibility (A11y) / Ruby

*   [Chromelens](https://chromewebstore.google.com/detail/chromelens/idikgljglpfilbhaboonnpnnincjhjkd) - See how your web app will look to people with different types of vision and the path users will travel when tabbing through your page.

### Workflow / Ruby

*   [Clockwork](https://chromewebstore.google.com/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) - View PHP application profiling data.
*   [Emulated Device Lab](https://chromewebstore.google.com/detail/emulated-device-lab/oaonfodocibcdobdeelbbfggjombamff) - Experiment with multiple devices being emulated at the same time.
*   [RailsPanel](https://chromewebstore.google.com/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) - View Ruby on Rails application profiling data.
*   [React Developer Tools](https://chromewebstore.google.com/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) - Inspect the React component hierarchies.
*   [Ember.js Inspector](https://chromewebstore.google.com/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) - Allows you to inspect Ember.js objects in your application.
*   [Marionette Inspector](https://chromewebstore.google.com/detail/marionette-inspector/fbgfjlockdhidoaempmjcddibjklhpka) - Inspect a Marionette application's views, events, and live data.
*   [Backbone Debugger](https://chromewebstore.google.com/detail/backbone-debugger/bhljhndlimiafopmmhjlgfpnnchjjbhd) - Inspect a Backbone application's views, models, events, and routes.
*   [App Inspector for Sencha](https://chromewebstore.google.com/detail/app-inspector-for-sencha/pbeapidedgdpniokbedbfbaacglkceae) - Inspect a Sencha ExtJS/Touch application's component tree, data stores, events, and layouts.
*   [Redux Devtools](https://chromewebstore.google.com/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) - Inspect Redux with actions history, undo and replay.
*   [Three.js](https://chromewebstore.google.com/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea/) - Edit any three.js project.
*   [Metal.js Developer Tools](https://chromewebstore.google.com/detail/metaljs-developer-tools/fagnjmppkokolnbloalifcmcooldhiik) - Inspect the Metal component hierarchies.
*   [Web Component DevTools](https://chromewebstore.google.com/detail/web-component-devtools/gdniinfdlmmmjpnhgnkmfpffipenjljo) - Inspect, modify and observe Web Components on page.

### Themes / Ruby

*   [DevTools Author](https://chromewebstore.google.com/detail/devtools-author/egfhcfdfnajldliefpdoaojgahefjhhi) - A selection of themes to modify parts of DevTools related to authoring web applications.
*   [Zero Dark Matrix](https://chromewebstore.google.com/detail/devtools-theme-zero-dark/bomhdjeadceaggdgfoefmpeafkjhegbo) - Dark theme for Chrome Developer Tools.
*   [Material UI Theme](https://chromewebstore.google.com/detail/material-devtools-theme-c/jmefikbdhgocdjeejjnnepgnfkkbpgjo) - Provides various Material Design inspired themes.

## [17. Awesome Mac](/content/abordage/awesome-mac/week/README.md)

### System Tools / Menu Bar

*   [dwarvesf/hidden (⭐13k)](https://github.com/dwarvesf/hidden) — Ultra-light utility to hide menu bar icons ☆`13,437`

## [18. ALL About RSS](/content/AboutRSS/ALL-about-RSS/week/README.md)

### Self Hosted Readers / Outline Processor Markup Language

*   [Dashboard (⭐5)](https://github.com/Rozhovetskyi/Dashboard) - ![Open-Source Software](https://github.com/AboutRSS/ALL-about-RSS/raw/master/media/open-source.png)![Freeware](https://github.com/AboutRSS/ALL-about-RSS/raw/master/media/icons8-one-free-16.png) lightweight, customizable, client-side RSS feeds dashboard.

## [19. Awesome Web Archiving](/content/iipc/awesome-web-archiving/week/README.md)

### Tools & Software / Quality Assurance

*   [Chrome Check My Links](https://chromewebstore.google.com/detail/check-my-links/ojkcdipcgfaekbeaelaapakgnjflfglf) - Browser extension: a link checker with more options.
*   [Chrome link checker](https://chromewebstore.google.com/detail/link-checker/aibjbgmpmnidnmagaefhmcjhadpffaoi) - Browser extension: basic link checker.
*   [Chrome link gopher](https://chromewebstore.google.com/detail/bpjdkodgnbfalgghnbeggfbfjpcfamkf/publish-accepted?hl=en-US\&gl=US) - Browser extension: link harvester on a page.
*   [Chrome Open Multiple URLs](https://chromewebstore.google.com/detail/open-multiple-urls/oifijhaokejakekmnjmphonojcfkpbbh?hl=de) - Browser extension: opens multiple URLs and also extracts URLs from text.
*   [Chrome Revolver](https://chromewebstore.google.com/detail/revolver-tabs/dlknooajieciikpedpldejhhijacnbda) - Browser extension: switches between browser tabs.

## [20. Awesome Readme](/content/matiassingers/awesome-readme/week/README.md)

### Examples

*   [FileShot/FileShotZKE (⭐18)](https://github.com/FileShot/FileShotZKE#readme) - Well-structured security documentation. Clear API reference with code examples. Detailed how-it-works section covering key derivation, AES-256-GCM encryption, and upload pipeline. Browser support table and security policy.

### Articles

*   ["Top ten reasons why I wonâ€™t use your open source project"](https://changelog.com/posts/top-ten-reasons-why-i-wont-use-your-open-source-project) - *Adam Stacoviak*

## [21. Awesome Playcanvas](/content/playcanvas/awesome-playcanvas/week/README.md)

### 3D Gaussian Splatting / YouTube Playables

*   [Solaya](https://solaya.ai/) - Generate high-fidelity 3D digital twins as the foundation for unlimited visual assets.
*   [StorySplat](https://storysplat.com) - Transform your 3D captures into interactive stories.

## [22. Awesome WebExtensions](/content/fregante/Awesome-WebExtensions/week/README.md)

### Getting started

*   [Mozilla's WebExtensions documentation](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions) - MDN wiki for the WebExtensions API.
*   [Browser support for WebExtensions](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Browser_support_for_JavaScript_APIs) - Compatibility table for Chrome, Edge, Firefox, and Opera.

## [23. Awesome Opensource Apps](/content/unicodeveloper/awesome-opensource-apps/week/README.md)

### What do we have:

- Project Name: [2048 (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/2048)

  Contributors: [Krunal](https://github.com/gitkp11)


- Project Name: [AI chatbot](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Artificial-intelligence_bot)

  Contributors: [umar abdullahi](https://github.com/umarbrowser)


- Project Name: [AI for guess the number (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/AI_for_Guess_the_number)

  Contributors: [Omar Sameh](https://github.com/ShadowHunter15)


- Project Name: [Address locator](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Location_Of_Adress)

  Contributors: [Chris](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/)


- Project Name: [Asymmetric Encryption](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/asymmetric_cryptography)

  Contributors: [victor matheus](https://github.com/victormatheusc)


- Project Name: [Attachment Unique Mail](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Attachment_Unique_Mail)

  Contributors: [Arnav Dandekar](https://github.com/4rnv)


- Project Name: [Automated calendar](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/automated_calendar)

  Contributors: [J.A. Hernández](https://github.com/jesusalberto18)


- Project Name: [Automated emails](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/automated_email)

  Contributors: [Suvigya](https://github.com/SuvigyaJain1)


- Project Name: [Battery\_notification (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Battery_notification/)

  Contributors: [Krishna Sharma](https://github.com/krishnasharma1386)


- Project Name: [Better\_CSV\_Storage (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Better_CSV_Storage)

  Contributors: [Bhargav Kuvadiya](https://github.com/techdobz)


- Project Name: [Bitcoin price GUI](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Bitcoin-Price-GUI)

  Contributors: [Amirul Abu](https://github.com/amirulabu)


- Project Name: [CLI Calculator](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/cli_calculator)

  Contributors: [Willian GL](https://github.com/williangl)


- Project Name: [COVID visualiser (real-time) ](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/covid_visualiser)

  Contributors: [Tushar Gupta](https://github.com/tushar5526)


- Project Name: [CSV to Excel (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/CSV-to-Excel)

  Contributors: [xemeds](https://github.com/xemeds)


- Project Name: [Caesar Cipher](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/caesar_cipher)

  Contributors: [epi052](https://github.com/epi052)


- Project Name: [Checksum tool](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Checksum)

  Contributors: [Austin Ewens](https://github.com/aewens)


- Project Name: [Clean\_up\_photo](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Clean_up_photo_directory)

  Contributors: [sritanmay001](https://github.com/sritanmy001)


- Project Name: [Codechef autosubmitter](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Codechef-Code-Submitter)

  Contributors: [Harshit Mahajan](https://github.com/hmahajan99)


- Project Name: [Codeforces Checker](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/codeforcesChecker)

  Contributors: [Jinesh Parakh](https://github.com/jineshparakh)


- Project Name: [Colored B\&W Image Converter](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Color_to_BW_Converter)

  Contributors: [Nitish Srivastava](https://github.com/nitish-iiitd)


- Project Name: [Contact 'Leads' Distribution](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Contact-Distribution)

  Contributors: [Tiago Cordeiro](https://github.com/tiagocordeiro)


- Project Name: [Countdown (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Countdown)

  Contributors: [Jeremias Gomes](https://github.com/j3r3mias)


- Project Name: [csv\_to\_json (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/csv_to_json)

  Contributors: [MoiZ](https://github.com/TechBoyy6)


- Project Name: [Cricket Matches web Scraper](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/CricBuzz_Score_Update)

  Contributors: [Divy Ranjan](https://github.com/divyranjan17)


- Project Name: [Crypt socket](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Crypt_Socket)

  Contributors: [Willian GL](https://github.com/williangl)


- Project Name: [Cryptocurrency Converter](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Cryptocurrency-converter)

  Contributors: [AdnCodz](https://github.com/AdnCodez)


- Project Name: [Cryptocurrency Prices (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Cryptocurrency-Prices)

  Contributors: [xemeds](https://github.com/xemeds)


- Project Name: [Current City Weather](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Current_City_Weather)

  Contributors: [Jesse Bridge](https://github.com/jessebridge)


- Project Name: [DNA Analysis Toolkit (⭐13)](https://github.com/shmlkv/dna-claude-analysis)

  Contributors: [shmlkv](https://github.com/shmlkv)


- Project Name: [DOH DIG](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/DOH-Dig/)

  Contributors: [Ryan](https://github.com/awsumco)


- Project Name: [Database-As-Storage (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Database-As-Storage)

  Contributors: [Bhargav Kuvadiya](https://github.com/techdobz)


- Project Name: [Directory Tree Visualizer (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Directory_Tree_Generator)

  Contributors: [Harpreet Singh Saluja](https://github.com/hssaluja25/)


- Project Name: [Directory organizer](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Directory-organizer)

  Contributors: [Athul P](https://github.com/athulpn)


- Project Name: [Download Page as PDF (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Download-page-as-pdf)

  Contributors: [Jeremias Gomes](https://github.com/j3r3mias)


- Project Name: [Elasticsearch snapshot (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/elastic-snapshot)

  Contributors: [Joe Ryan](https://github.com/joeryan)


- Project Name: [English Theasaurus (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/English_Theasauras/)

  Contributors: [Ansh Dhingra](https://github.com/anshdhinhgra47)


- Project Name: [Excel Files Merger](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Excel_Files_Merger)

  Contributors: [Andrei N](https://github.com/Andrei-Niculae)


- Project Name: [Excel to List](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Excel_to_ListofList)

  Contributors: [Nitish Srivastava](https://github.com/nitish-iiitd)


- Project Name: [Extended\_ip\_address\_info](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/extended_ip_address_info)

  Contributors: [hafpaf](https://github.com/hafpaf)


- Project Name: [Face Recognition (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Face_recognition)

  Contributors: [LOKESH KHURANA](https://github.com/theluvvkhurana)


- Project Name: [Fibonacci\_Sequence\_Generator](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Fibonacci_Sequence_Generator)

  Contributors: [John Wesley Kommala](https://github.com/JohnWesleyK)


- Project Name: [File Carving (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/File_Carving)

  Contributors: [Yeryeong Kim](https://github.com/icarusicarus/)


- Project Name: [File Encrypt Decrypt](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/file-encrypt-decrypt)

  Contributors: [Aditya Arakeri](https://github.com/adityaarakeri)


- Project Name: [FileMagic Organizer](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/./FileMagic_Organizer)

  Contributors: [malivinayak](https://github.com/malivinayak)


- Project Name: [File Organizer](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/File-Organizer)

  Contributors: [Ayush Bhardwaj](https://github.com/hastagAB)


- Project Name: [File Sharing Bot](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/File-Sharing-Bot)

  Contributors: [Darshan Patel](https://github.com/DarshanPatel11)


- Project Name: [File explorer](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/File-Explorer-Dialog-Box)

  Contributors: [Nikhil Kumar Singh](https://github.com/nikhilkumarsingh)


- Project Name: [Find PhoneNumber in String](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Find-PhoneNumber-in-String)

  Contributors: [Austin Zuniga](https://github.com/AustinZuniga)


- Project Name: [Flash card quizzer](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Flash-card-Challenge)

  Contributors: [Utkarsh Sharma](https://github.com/Utkarsh1308)


- Project Name: [Folder Locker and hider (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Folder%20Locker%20%26%20Hider)

  Contributors: [Prajjwal Pathak](https://github.com/pyguru123)


- Project Name: [Folder Manager](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Folder_Manager)

  Contributors: [Harsh Raj](https://github.com/DeadProgrammer0)


- Project Name: [Frammed text generator](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/FramedText)

  Contributors: [jcdwalle](https://github.com/jcdwalle)


- Project Name: [Get Time By TimeZone (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Get_Time_TimezoneWise)

  Contributors: [Parth Shah](https://github.com/codingis4noobs)


- Project Name: [git\_automation (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/git_automation)

  Contributors: [loge1998](https://github.com/loge1998)


- Project Name: [Github repo creator (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Git_repo_creator)

  Contributors: [Harish Tiwari ](https://github.com/optimist2309)


- Project Name: [Github Review Bot (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Github-Review-Bot)

  Contributors: [Gaurav Giri](https://github.com/gaurovgiri)


- Project Name: [GithubBot (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Github_Bot)

  Contributors: [Abhilasha](https://github.com/Abhilasha06)


- Project Name: [Gmail Mailing Script](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/mailing)

  Contributors: [mayank-kapur](https://github.com/kapurm17)


- Project Name: [Google Meet Joiner (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/google_meet_joiner)

  Contributors: [JohanSanSebastian](https://github.com/JohanSanSebastian)


- Project Name: [HTML Table to List](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/HTML_Table_to_List)

  Contributors: [Nitish Srivastava](https://github.com/nitish-iiitd)


- Project Name: [Handwrting DNN recognizer](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Handwriting_Recognizer)

  Contributors: [Chris](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/)


- Project Name: [Harry Potter Cloak (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Harry-Potter-Cloak)

  Contributors: [thesmartdeveloperr](https://github.com/thesmartdeveloperr)


- Project Name: [IMDB TV Series Info Extractor](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/imdb_episode_ratings)

  Contributors: [Yash Raj Sarrof](https://github.com/yashYRS)


- Project Name: [IMDBQuerier](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/IMDBQuerier)

  Contributors: [Burak Bekci](https://github.com/Bekci)


- Project Name: [IP Address  (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/ipaddress)

  Contributors: [Xenium](https://github.com/xeniumcode)


- Project Name: [Image Compressor (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Image_Compressor)

  Contributors: [Prathima Kadari](https://github.com/prathimacode-hub)


- Project Name: [Image To PDF](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/images2pdf)

  Contributors: [msaoudallah](https://github.com/msaoudallah)


- Project Name: [Image Watermarker (batch)](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/imageWatermarker)

  Contributors: [Remco Halman](https://github.com/remcohalman)


- Project Name: [Image circle formatter](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Image-Circulator)

  Contributors: [Berk Gureken](https://github.com/bureken)


- Project Name: [Independent RSA Communication Algorithm (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/RSA_Communication)

  Contributors: [Miguel Santos](https://github.com/wi6n3l)


- Project Name: [Instadp Web Scrapper](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/InstadpShower)

  Contributors: [Psychiquest](https://github.com/psychiquest)


- Project Name: [Instagram Video Downloader (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/insta_video_downloader)

  Contributors: [Shobhit Bhosure](https://github.com/shobhit99)


- Project Name: [JSON file to YAML convertor (⭐1)](https://github.com/saksham117/Awesome-Python-Scripts/tree/master/json-to-yaml)

  Contributors: [Saksham Basandrai](https://github.com/saksham117)


- Project Name: [Keylogger](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Keylogger)

  Contributors: [Preet Mishra](https://github.com/preetmishra)


- Project Name: [Medium Article Downloader](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/medium_article_downloader)

  Contributors: [coolsonu39](https://github.com/coolsonu39)


- Project Name: [Minecraft Server in background](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Minecraft_server_in_background)

  Contributors: [Max von Forell](https://github.com/mvforell)


- Project Name: [Own IP locator](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Location_Of_Own_IP_Adress)

  Contributors: [Chris](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/)


- Project Name: [PDF2text](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/PDF2text)

  Contributors: [QuangPH](https://github.com/quangph-1686a)


- Project Name: [PDFsplitter](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/PDFsplitter)

  Contributors: [Prathamesh-Ghatole](https://github.com/Prathamesh-Ghatole)


- Project Name: [PX to REM (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/PX-to-REM)

  Contributors: [Atthaphon Urairat](https://github.com/uatthaphon)


- Project Name: [Pdf to AudioBook Converter (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/PdfToAudio)

  Contributors: [Ayesha Gull](https://github.com/ayeshag7/)


- Project Name: [Plagiarism\_detector (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Plagiarism_detector)

  Contributors: [Akshita Singhal](https://github.com/akshitasinghal4444)


- Project Name: [Port Scanner](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Port_Scanner)

  Contributors: [Plutoberth](https://github.com/Plutoberth)


- Project Name: [Pressure\_Converter (⭐0)](https://github.com/E-wave112/Awesome-Python-Scripts/tree/master/Pressure_Converter)

  Contributors: [E-Wave](https://github.com/E-wave112)


- Project Name: [Pretty CSV](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Pretty-CSV)

  Contributors: [Frizz925](https://github.com/Frizz925)


- Project Name: [PyRecorder](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/PyRecorder)

  Contributors: [Rocky Jain](https://github.com/jainrocky)


- Project Name: [py\_based\_music\_player (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/py_based_music_player)

  Contributors: [Bhargav Kuvadiya](https://github.com/techdobz)


- Project Name: [Py\_Cleaner](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Py_Cleaner)

  Contributors: [Abhishek Dobliyal](https://github.com/Abhishek-Dobliyal)


- Project Name: [Python Algebra Solver](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Algebra-Solver)

  Contributors: [Sengxay Xayachack](https://github.com/frankxayachack)


- Project Name: [RSA Algorithm (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/RSA_Algorithm)

  Contributors: [Chinmay Rane](https://github.com/Chinmayrane16)


- Project Name: [RSA Key Pair Generator](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/RSA-key-pairs)

  Contributors: [Aditya Parikh](https://github.com/obiwan69)


- Project Name: [Random Password Generators](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Random_Password_Generator)

  Contributors: [Hafpaf](https://github.com/hafpaf) and [Renderer-RCT2](https://github.com/Renderer-RCT2)


- Project Name: [Random name generator](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Random_Names_Generator)

  Contributors: [Ayush Bhardwaj](https://github.com/hastagAB)


- Project Name: [Random\_Email\_Generator](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Random_Email_Generator)

  Contributors: [Shubham Garg](https://github.com/shub-garg)


- Project Name: [Remove-Duplicate-Files](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Remove-Duplicate-Files)

  Contributors: [Aayushi Varma](https://github.com/aayuv17)


- Project Name: [Rock-Paper-Scissor Game (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Rock-Paper-Scissor)

  Contributors: [Punit Sakre](https://github.com/punitsakre23)


- Project Name: [send\_whatsapp\_message](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/send_whatsapp_message)

  Contributors: [Mukesh Prasad](https://github.com/mukeshprasad)


- Project Name: [Send messages to sqs in parallel](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/send_sqs_messages_in_parallel)

  Contributors: [Jinam Shah](https://github.com/jinamshah)


- Project Name: [Server Ping](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Ping_Server)

  Contributors: [prince](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/)


- Project Name: [Signature photo to PNG converter](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/signature2png)

  Contributors: [Rodolfo Ferro](https://github.com/RodolfoFerro)


- Project Name: [Simple Webpage Parser](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/SimpleWebpageParser)

  Contributors: [Nitish Srivastava](https://github.com/nitish-iiitd)


- Project Name: [Slideshare downloader](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Slideshare-Downloader)

  Contributors: [Chris Goes](https://github.com/GhostofGoes)


- Project Name: [SMS your location](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/SmsYourLocation)

  Contributors: [prince](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/)


- Project Name: [Spotify Downloader](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/spotify_downloader)

  Contributors: [Sagar Patel](https://github.com/sagar627)


- Project Name: [Squid installer for Ubuntu](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Squid-Proxy-Installer-for-Ubuntu16)

  Contributors: [Berkay Demir](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/)

  : 


- Project Name: [SSH Host adder (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/SSH_Host_Adder)

  Contributors: [NinoDoko](https://github.com/NinoDoko)


- Project Name: [Steg\_Tool (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Steg_Tool/)

  Contributors: [Shankar JP](https://github.com/shankarjp)


- Project Name: [sudoku-solver (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/sudoku-solver)

  Contributors: [Rishabh Umrao](https://github.com/ayedaemon)


- Project Name: [Subtitle downloader](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Subtitle-downloader)

  Contributors: [Kaushlendra Pratap](https://github.com/kaushl1998)


- Project Name: [TTS - Text to Speech Mp3 (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/TTS_Text_to_Speech_Mp3)

  Contributors: [Antonio Andrade](https://github.com/xAndrade)


- Project Name: [Take Screenshot](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Take_screenshot)

  Contributors: [Moad Mohammed Elhebri](https://github.com/moadmmh)


- Project Name: [Tambola\_Ticket\_Generator](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Tambola_Ticket_Generator)

  Contributors: [Amandeep\_Singh](https://github.com/Synster)


- Project Name: [Test Your Internet Speed (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/TestMyInternetSpeed)

  Contributors: [TheSmartDeveloperr](https://github.com/thesmartdeveloperr)


- Project Name: [TicTacToe AI and 2 players (⭐4)](https://github.com/ShadowHunter15/Awesome-Python-Scripts/tree/master/TicTacToe_AI_and_2_players)

  Contributors: [Omar Sameh](https://github.com/ShadowHunter15)


- Project Name: [To Do Bot](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/To%20Do%20Bot)

  Contributors: [Darshan Patel](https://github.com/DarshanPatel11)


- Project Name: [Top\_News](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Top_News)

  Contributors: [Attupatil](https://github.com/Attupatil)


- Project Name: [Translate CLI (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/TranslateCLI)

  Contributors: [Rodrigo Oliveira](https://github.com/rodrigocam)


- Project Name: [URL shortener](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/url_shortener)

  Contributors: [Sam Ebison](https://github.com/ebsa491)


- Project Name: [Upload Files to S3](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Upload_files_to_s3)

  Contributors: [Jayram Nai](https://github.com/jramnai)


- Project Name: [Vinegère Cipher](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/vigenere_cipher)

  Contributors: [victoni](https://github.com/victoni)


- Project Name: [Web proxy](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Proxy-Request)

  Contributors: [Nikhil Kumar Singh](https://github.com/nikhilkumarsingh)


- Project Name: [Website Url Detector](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Website_Url_Detector)

  Contributors: [sonniki](https://github.com/sonniki)


- Project Name: [Website blocker](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Website-Blocker)

  Contributors: [Ayush Bhardwaj](https://github.com/hastagAB)


- Project Name: [WiFi Password Viewer](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Wifi-Password)

  Contributors: [Sagar Patel](https://github.com/sagar627)


- Project Name: [Wikipedia-Search (⭐2.3k)](https://github.com/hastagAB/Awesome-Python-Scripts/tree/master/Wikipedia-Search)

  Contributors: [Nissaar](https://github.com/Nissaar)


- Project Name: [Word Frequency Counter](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Word_Frequency_Counter)

  Contributors: [sonniki](https://github.com/sonniki)


- Project Name: [Word generator](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Word-generator)

  Contributors: [TGLIDE](https://github.com/TGlide)


- Project Name: [Work log generator](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Work_Log_Generator)

  Contributors: [Maël Pedretti](https://github.com/73VW)


- Project Name: [X Scrapper](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/X_Scrapper)

  Contributors: [Shreeram](https://github.com/iamshreeram)


- Project Name: [YTS Torrents](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/yts_torrents)

  Contributors: [Mayank Nader](https://github.com/makkoncept)


- Project Name: [Yoda-speak Translator](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/speak_like_yoda)

  Contributors: [sonniki](https://github.com/sonniki)


- Project Name: [Youtube video downloader](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Youtube_Video_Downloader)

  Contributors: [Christopher He](https://github.com/hecris)


- Project Name: [Zabbix API](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/zabbix_api)

  Contributors: [msg4sunny](https://github.com/msg4sunny)


- Project Name: [Zip password cracker](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/zip_password_cracker)

  Contributors: [umar abdullahi](https://github.com/umarbrowser)


- Project Name: [Task Scheduler](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Task-Scheduler)

  Contributors: [heysagnik](https://github.com/heysagnik)


- Project Name: [PDF Password Decypter](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/PDF_Password_Decrypter)

  Contributors: [parthasdey2304](https://github.com/parthasdey2304)


- Project Name: [Password Strength Checker](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/Password_Strength-checker)

  Contributors: [Parveshiiii](https://github.com/Parveshiiii)


- Project Name: [QR Code Generator](https://github.com/unicodeveloper/awesome-opensource-apps/blob/master/README.md/QR-code-generator)

  Contributors: [Parveshiiii](https://github.com/Parveshiiii)



## [24. Awesome Sysadmin](/content/awesome-foss/awesome-sysadmin/week/README.md)

### Software / Identity Management - LDAP

*   [LTB Self-Service Password](https://www.ltb-project.org/documentation/self-service-password.html) - Web interface to change and reset LDAP passwords. ([Source Code (⭐1.3k)](https://github.com/ltb-project/self-service-password)) `GPL-3.0` `PHP`

## [25. Awesome Zsh Plugins](/content/unixorn/awesome-zsh-plugins/week/README.md)

### Plugins / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [edit-select (⭐5)](https://github.com/Michael-Matta1/zsh-edit-select) - Brings a full text-editor experience to the ZSH command line: copy, cut, paste, undo/redo, type-to-replace, and native X11/Wayland clipboard integration, with Shift+Arrow and mouse selection support.
*   [git-worktree-manager (⭐0)](https://github.com/tmbtech/zsh-git-worktree-manager) - Manage `git` worktrees with ease. Streamline your workflow when working with multiple branches simultaneously.
*   [gitignore (⭐54)](https://github.com/voronkovich/gitignore.plugin.zsh) - Plugin for creating `.gitignore` files.
*   [llm-replace (⭐2)](https://github.com/m3at/zsh-llm-replace) - Integrate LLMs into the shell for quick command generation. Requires `curl` and `jq`.

### Themes / [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

*   [ooh-matron (⭐0)](https://github.com/hulleyrob/ohmyzsh-theme-ooh-matron) - Real time prompt with decorators for exit status of last command, username\@hostname, IP address and `git` status.
*   [sentinelx (⭐0)](https://github.com/Robinx0/sentinelX-theme) - A lightweight, high-fidelity Zsh theme optimized for penetration testing and red teaming. It provides real-time situational awareness and process tracking for long-running security tools. Includes decorators for `git` status, a live process spinner, VPN status, root status and last command duration.

## [26. Awesome Game Remakes](/content/radek-sprta/awesome-game-remakes/week/README.md)

### FPS

*   [Barrett (⭐20)](https://github.com/lunarmeadow/barrett/) - Advanced and featureful Rise of the Triad source port for modern systems.
*   [Chasm-Reverse](https://github.com/Panzerschrek/Chasm-Reverse) - "PanzerChasm" is a free recreation of the game "Chash: - The Rift" by "ActionForms" using the original game data (CSM.BIN file).
*   [idTech4A++ (Harmattan Edition) (⭐518)](https://github.com/glKarin/com.n0n3m4.diii4a) - DOOM III/Quake 4/Prey(2006) GLES on Android/Windows/Linux, DOOM 3 BFG/The Dark Mod/RTCW/Quake 1 2 3/GZDOOM/ETW/RealRTCW/OpenJK/SeriousSam/Skin Deep on Android.
*   [jfsw (⭐92)](https://github.com/jonof/jfsw/) - Port of the 3D Realms game "Shadow Warrior".
*   [jftekwar (⭐26)](https://github.com/jonof/jftekwar) - No-promises port of the Capstone Software game "TekWar".
*   [jfwhaven (⭐25)](https://github.com/jonof/jfwhaven) - No-promises port of the Capstone Software game "Witchaven".
*   [OpenChasm](https://github.com/alexey-lysiuk/OpenChasm) - Free software reconstruction of Chasm: The Rift game.
*   [Raze (⭐835)](https://github.com/ZDoom/Raze) - Build engine port backed by GZDoom tech. Currently supports Duke Nukem 3D, Blood, Shadow Warrior, Redneck Rampage and Powerslave/Exhumed.

### Racing

*   [dRally (⭐70)](https://github.com/urxp/dRally) - Open Source Engine / Death Rally \[1996]
*   [dethrace](https://github.com/dethrace-labs/dethrace) - Reverse engineering the 1997 game "Carmageddon"
*   [hi-octane202x (⭐7)](https://github.com/woalexan/hi-octane202x) - Hi-Octane with level editor using Irrlicht engine.
*   [tube64 (⭐19)](https://github.com/rep-stosw/tube64) - 64-bit vesion of DOS game Tube (Bullfrog, 1994)

### Simulator

*   [Descent3 (⭐3k)](https://github.com/DescentDevelopers/Descent3) - Descent 3 by Outrage Entertainment

### Strategy

*   [Flame (⭐83)](https://github.com/DiaLight/Flame) - Dungeon Keeper II partial recompilation with bug fixes.
*   [OpenDungeonsPlus (⭐16)](https://github.com/tomluchowski/OpenDungeonsPlus) - Open source game inspired by Dungeon Keeper - Dark, damp and dangerous...
*   [OpenTPW (⭐145)](https://github.com/OpenTPW/OpenTPW) - An open-source re-implementation of Bullfrog's Sim Theme Park / Theme Park World (1999).

## [27. Awesome Windows](/content/0pandadev/awesome-windows/week/README.md)

### Communication

*   [Stoat](https://stoat.chat/) - Chat platform built with modern web tech. [![Open-Source Software](https://github.com/0PandaDEV/awesome-windows/raw/main/assets/opensource.svg)](https://github.com/revoltchat)

### IDEs

*   [VSCodium](https://vscodium.com/) - A VS Code fork without all the Microsoft bloat and telemetry. [![Open-Source Software](https://github.com/0PandaDEV/awesome-windows/raw/main/assets/opensource.svg)](https://github.com/vscodium/vscodium) ![star](https://github.com/0PandaDEV/awesome-windows/raw/main/assets/star.svg)

## [28. Awesome Zig](/content/zigcc/awesome-zig/week/README.md)

### Language Essentials / String Processing

*   [atman/zg](https://codeberg.org/atman/zg) - Provides Unicode text processing for Zig projects. It works correctly with the Russian language and other languages.

### Language Essentials / File Format Processing

*   [OrlovEvgeny/serde.zig (⭐8)](https://github.com/OrlovEvgeny/serde.zig) - Comptime serialization framework for Zig supporting JSON, MessagePack, TOML, YAML, ZON, and CSV.

### Network & Web / Network

*   [zat.dev/zat](https://tangled.org/zat.dev/zat) - AT Protocol building blocks for zig.

## [29. Awesome Computational Biology](/content/inoue0426/awesome-computational-biology/week/README.md)

### scRNA

*   [CZ CELLxGENE](https://cellxgene.cziscience.com/) — Single-cell dataset repository and interactive explorer from the Chan Zuckerberg Initiative.
*   [Human Cell Atlas](https://www.humancellatlas.org/) — Open global atlas of all cells in the human body.

### Compound

*   [HMDB (Human Metabolome Database)](https://hmdb.ca/) — Comprehensive database of small molecule metabolites found in the human body.
*   [DrugCentral](http://drugcentral.org/) — Online drug compendium with drug mode of action and indication information.

### Protein

*   [SAbDab](https://opig.stats.ox.ac.uk/webapps/sabdab-sabpred/sabdab) — Structural Antibody Database containing all antibody structures in the PDB.
*   [OADB (Observed Antibody Space Database)](http://opig.stats.ox.ac.uk/webapps/oas/) — Database of antibody sequences from immune repertoire sequencing.

### Genome

*   [ENCODE](https://www.encodeproject.org/) — Encyclopedia of DNA Elements; regulatory and functional genomic elements across the genome.
*   [Ensembl](https://www.ensembl.org/) — Genome browser and annotation database for vertebrate and other eukaryotic genomes.
*   [gnomAD](https://gnomad.broadinstitute.org/) — Genome Aggregation Database; genetic variation from large-scale sequencing projects.
*   [Rfam](https://rfam.org/) — Database of RNA families with sequence alignments and consensus structures.

### Disease

*   [DisGeNET](https://www.disgenet.org/) — Database of gene-disease associations integrating expert-curated and GWAS data.
*   [OMIM (Online Mendelian Inheritance in Man)](https://www.omim.org/) — Comprehensive database of human genes and genetic disorders.

### Protein-Protein Interaction

*   [IntAct](https://www.ebi.ac.uk/intact/home) — Open-source molecular interaction database and analysis system from EMBL-EBI.

### Benchmarks & Datasets

*   [BindingDB Curated Sets](https://www.bindingdb.org/rwd/bind/chemsearch/marvin/SDFdownload.jsp?all_download=yes) — Curated binding affinity datasets for protein–ligand interaction benchmarking.
*   [Cancer Therapeutics Response Portal (CTRP)](https://portals.broadinstitute.org/ctrp/) — Drug sensitivity profiles across \~900 cancer cell lines for >400 compounds.
*   [GuacaMol (⭐500)](https://github.com/BenevolentAI/guacamol) — Benchmark suite for generative molecular design models.
*   [MOSES (⭐957)](https://github.com/molecularsets/moses) — Benchmarking platform for molecular generation models.
*   [Therapeutics Data Commons (TDC)](https://tdcommons.ai/) — Unified benchmark suite covering ADMET, drug-target interaction, drug response, and more.

### Preprocessing Tools

*   [Biopython](https://biopython.org/) — Collection of Python tools for biological computation including sequence analysis, structure parsing, and database access.
*   [DeepChem (⭐6.6k)](https://github.com/deepchem/deepchem) — Deep learning library for drug discovery, quantum chemistry, and materials science.
*   [scvi-tools](https://scvi-tools.org/) — Probabilistic models for single-cell omics data analysis.
*   [CellTypist (⭐457)](https://github.com/Teichlab/celltypist) — Automated cell type annotation for scRNA-seq.
*   [GROMACS](https://www.gromacs.org/) — Molecular dynamics simulation package for biochemical molecules.
*   [MDAnalysis](https://www.mdanalysis.org/) — Python library for analyzing and altering molecular dynamics simulation trajectories.
*   [OpenMM](https://openmm.org/) — High-performance toolkit for molecular simulation and GPU-accelerated MD.

### Molecular Generation

*   [REINVENT (⭐370)](https://github.com/MolecularAI/Reinvent) — Reinforcement learning for de novo drug design.
*   [MolGPT (⭐169)](https://github.com/devalab/molgpt) — Transformer-based model for molecular generation.
*   [Molecular Transformer (⭐413)](https://github.com/pschwllr/MolecularTransformer) — Sequence-to-sequence model for retrosynthesis prediction.
*   [TargetDiff (⭐323)](https://github.com/guanjq/targetdiff) — 3D equivariant diffusion model for structure-based drug design.

### LLM for Biology

*   [ClawBio (⭐106)](https://github.com/ClawBio/ClawBio) — Bioinformatics-native AI agent skill library with local-first pharmacogenomics, ancestry PCA, semantic similarity, nutrigenomics, and metagenomics skills.

### Single-cell Foundation Models / Transcriptomics Foundation Models

*   [Geneformer](https://huggingface.co/ctheodoris/Geneformer) — Context-aware, attention-based deep learning model pretrained on a large corpus of single-cell transcriptomes.
*   [scBERT (⭐347)](https://github.com/TencentAILabHealthcare/scBERT) — BERT-based foundation model pretrained on large-scale scRNA-seq data for cell type annotation.
*   [CellPLM (⭐101)](https://github.com/OmicsML/CellPLM) — Cell pre-trained language model with inter-cell transformer architecture for diverse single-cell analysis tasks.

### Single-cell Foundation Models / Spatial Foundation Models

*   [GigaPath (⭐578)](https://github.com/prov-gigapath/prov-gigapath) — Slide-level digital pathology foundation model pretrained on 1.3 billion pathology image tokens from whole-slide images.
*   [UNI (⭐681)](https://github.com/mahmoodlab/UNI) — General-purpose self-supervised pathology foundation model trained on 100K+ whole-slide images for diverse computational pathology tasks.
*   [CONCH (⭐472)](https://github.com/mahmoodlab/CONCH) — Vision-language foundation model for computational pathology trained with contrastive captioning on pathology image–text pairs.
*   [Phikon](https://huggingface.co/owkin/phikon) — ViT-based pathology foundation model pretrained with iBOT self-supervision on TCGA whole-slide images.

### Single-cell Foundation Models / Multi-Omics Foundation Models

*   [scMulan (⭐62)](https://github.com/SuperBianC/scMulan) — Single-cell multi-omic language model pretrained on \~10M cells spanning transcriptomics, epigenomics, and proteomics for cross-omics transfer tasks.
*   [totalVI (⭐1.6k)](https://github.com/scverse/scvi-tools) — Probabilistic framework for joint analysis of paired scRNA-seq and protein (CITE-seq) data enabling multi-modal cell state representation across single-cell datasets.
*   [MultiVI (⭐1.6k)](https://github.com/scverse/scvi-tools) — Multi-modal variational autoencoder for integrating paired and unpaired single-cell RNA-seq and ATAC-seq measurements into a unified latent space.
*   [MIRA (⭐67)](https://github.com/cistrome/MIRA) — Probabilistic multimodal topic model jointly modeling single-cell transcriptomics and chromatin accessibility for regulatory network inference.
*   [GLUE (⭐455)](https://github.com/gao-lab/GLUE) — Graph-Linked Unified Embedding framework for unpaired single-cell multi-omics data integration across RNA, ATAC, methylation, and protein modalities.
*   [BABEL (⭐47)](https://github.com/wukevin/babel) — Cross-modality translation model enabling prediction between scRNA-seq and scATAC-seq profiles without requiring paired single-cell measurements.
*   [Multigrate (⭐31)](https://github.com/theislab/multigrate) — Asymmetric multi-omics variational autoencoder for integrating single-cell data across RNA, ATAC, and protein modalities with missing-modality support.
*   [MOFA+ (⭐384)](https://github.com/bioFAM/MOFA2) — Multi-Omics Factor Analysis framework identifying shared axes of variation across bulk and single-cell datasets including RNA, ATAC, proteomics, methylation, and copy number.
*   [GeneCompass (⭐111)](https://github.com/xCompass-AI/GeneCompass) — Large-scale foundation model integrating DNA regulatory sequences and single-cell transcriptomics from 120M+ cells across multiple species for gene regulation prediction.
*   [UnitedNet (⭐52)](https://github.com/LiuLab-Bioelectronics-Harvard/UnitedNet) — Interpretable multi-task deep neural network for single-cell multi-omics integration spanning transcriptomics, chromatin accessibility, and proteomics.
*   [SpatialGlue](https://github.com/zhanglabtools/SpatialGlue) — Graph attention network for spatial multi-omics integration jointly embedding spatial transcriptomics with chromatin accessibility or proteomics.
*   [MIDAS (⭐62)](https://github.com/labomics/midas) — Mosaic integration and differential accessibility model for single-cell multi-omics data that handles arbitrary missing-modality combinations across transcriptomics, chromatin accessibility, and proteomics.

### Single-cell Foundation Models / Domain Alignment

*   [scArches (⭐399)](https://github.com/theislab/scarches) — Transfer learning framework for mapping new single-cell datasets onto pre-trained reference atlases across batches, conditions, and modalities.
*   [TOSICA](https://github.com/JackieHanlaopo/TOSICA) — Transformer-based framework for one-stop interpretable cell-type annotation supporting cross-dataset and cross-species transfer.

### Protein Foundation Models / Protein Structure Prediction and Design

*   [AlphaFold3 (⭐7.7k)](https://github.com/google-deepmind/alphafold3) — Predicts structures of proteins, nucleic acids, small molecules, and their complexes.
*   [Boltz-1 (⭐3.8k)](https://github.com/jwohlwend/boltz) — Open-source all-atom biomolecular structure prediction model for proteins, nucleic acids, small molecules, and their complexes achieving AlphaFold3-level accuracy.
*   [Chai-1 (⭐1.9k)](https://github.com/chaidiscovery/chai-lab) — Unified molecular structure prediction model covering proteins, nucleic acids, small molecules, and complexes.
*   [ESM3 (⭐2.3k)](https://github.com/evolutionaryscale/esm) — Multimodal protein language model that jointly reasons over sequence, structure, and function for generative protein design and engineering.
*   [ESMFold (⭐4k)](https://github.com/facebookresearch/esm) — Fast protein structure prediction using language model embeddings.
*   [RFdiffusion (⭐2.8k)](https://github.com/RosettaCommons/RFdiffusion) — Generative model for protein backbone design using diffusion.
*   [ProteinMPNN (⭐1.6k)](https://github.com/dauparas/ProteinMPNN) — Deep learning model for protein sequence design given backbone structure.
*   [OmegaFold (⭐613)](https://github.com/HeliXonProtein/OmegaFold) — High-resolution de novo protein structure prediction from sequence.
*   [RoseTTAFold (⭐2.2k)](https://github.com/RosettaCommons/RoseTTAFold) — Three-track neural network for protein structure prediction.

### Multi-Modal Foundation Models / Protein Structure Prediction and Design

*   [CHIEF (⭐688)](https://github.com/hms-dbmi/CHIEF) — Clinical Histopathology Imaging Evaluation Foundation model integrating histology images and clinical context for pan-cancer analysis.
*   [BiomedCLIP](https://huggingface.co/microsoft/BiomedCLIP-PubMedBERT_256-vit_g_14) — CLIP-based vision-language foundation model for biomedical images and text trained on PubMed figure–caption pairs.

### Genomics Foundation Models / Protein Structure Prediction and Design

*   [Nucleotide Transformer (⭐831)](https://github.com/instadeepai/nucleotide-transformer) — Foundation model for genomic sequences across multiple species.
*   [DNABERT (⭐744)](https://github.com/jerryji1993/DNABERT) — Pre-trained bidirectional encoder for DNA sequence analysis.
*   [DNABERT-2 (⭐460)](https://github.com/Zhihan1996/DNABERT_2) — Improved genome foundation model with efficient tokenization.
*   [Enformer (⭐15k)](https://github.com/deepmind/deepmind-research/tree/master/enformer) — Transformer model predicting gene expression from DNA sequence.
*   [Basenji (⭐466)](https://github.com/calico/basenji) — Sequential regulatory activity prediction from DNA sequences.
*   [Caduceus (⭐226)](https://github.com/kuleshov-group/caduceus) — Bidirectional equivariant long-range DNA sequence model based on Mamba.
*   [Evo (⭐1.5k)](https://github.com/evo-design/evo) — Long-context genomic foundation model (up to 1M tokens).
*   [HyenaDNA (⭐764)](https://github.com/HazyResearch/hyena-dna) — Long-range genomic foundation model handling sequences up to 1M tokens with sub-quadratic attention.

## [30. Awesome Terraform](/content/shuaibiyy/awesome-terraform/week/README.md)

### Tools / Community providers

*   [ReleaseRun Terraform Provider Matrix](https://releaserun.com/tools/terraform-provider-matrix/) - Free browser tool to check Terraform provider version compatibility across Terraform and OpenTofu versions.
*   [terraform-ai-skills (⭐1)](https://github.com/anmolnagpal/terraform-ai-skills) - AI-powered skill for GitHub Copilot, Claude, and ChatGPT that automates bulk Terraform module management — provider upgrades, workflow standardization, and releases across 10–200+ repositories on AWS, GCP, Azure, and DigitalOcean.

## [31. Awesome Claude Code](/content/hesreallyhim/awesome-claude-code/week/README.md)

### Agent Skills 🤖 / General

*   [Claude Scientific Skills (⭐11k)](https://github.com/K-Dense-AI/claude-scientific-skills) by [K-Dense](https://github.com/K-Dense-AI/) - "A set of ready-to-use Agent Skills for research, science, engineering, analysis, finance and writing." That's their description - modest, simple. That's how you can tell this is really one of the best skills repos on GitHub. If you've ever thought about getting a PhD... just read all of these documents instead. Also I think it IS an AI agent or something? Awesome.

### Hooks 🪝 / General

*   [parry (⭐3)](https://github.com/vaporif/parry) by [Dmytro Onypko](https://github.com/vaporif) - Prompt injection scanner for Claude Code hooks. Scans tool inputs and outputs for injection attacks, secrets, and data exfiltration attempts. \[NOTE: Early development phase but worth a look.].

### Slash-Commands 🔪 / Version Control & Git

*   [/fix-issue (⭐46k)](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-issue.md) by [metabase](https://github.com/metabase) - Addresses GitHub issues by taking issue number as parameter, analyzing context, implementing solution, and testing/validating the fix for proper integration.
*   [/fix-pr (⭐46k)](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-pr.md) by [metabase](https://github.com/metabase) - Fetches and fixes unresolved PR comments by automatically retrieving feedback, addressing reviewer concerns, making targeted code improvements, and streamlining the review process.

### Slash-Commands 🔪 / Code Analysis & Testing

*   [/check (⭐22)](https://github.com/rygwdn/slack-tools/blob/main/.claude/commands/check.md) by [rygwdn](https://github.com/rygwdn) - Performs comprehensive code quality and security checks, featuring static analysis integration, security vulnerability scanning, code style enforcement, and detailed reporting.
*   [/repro-issue (⭐5)](https://github.com/rzykov/metabase/blob/master/.claude/commands/repro-issue.md) by [rzykov](https://github.com/rzykov) - Creates reproducible test cases for GitHub issues, ensuring tests fail reliably and documenting clear reproduction steps for developers.

### Slash-Commands 🔪 / Context Loading & Priming

*   [/load\_coo\_context (⭐1)](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_coo_context.md) by [Mjvolk3](https://github.com/Mjvolk3) - References specific files for sparse matrix operations, explains transform usage, compares with previous approaches, and sets data formatting context for development.
*   [/load\_dango\_pipeline (⭐1)](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_dango_pipeline.md) by [Mjvolk3](https://github.com/Mjvolk3) - Sets context for model training by referencing pipeline files, establishing working context, and preparing for pipeline work with relevant documentation.
*   [/prime (⭐33)](https://github.com/yzyydev/AI-Engineering-Structure/blob/main/.claude/commands/prime.md) by [yzyydev](https://github.com/yzyydev) - Sets up initial project context by viewing directory structure and reading key files, creating standardized context with directory visualization and key documentation focus.
*   [/rsi (⭐3)](https://github.com/ddisisto/si/blob/main/.claude/commands/rsi.md) by [ddisisto](https://github.com/ddisisto) - Reads all commands and key project files to optimize AI-assisted development by streamlining the process, loading command context, and setting up for better development workflow.

### Slash-Commands 🔪 / CI / Deployment

*   [/release (⭐5)](https://github.com/kelp/webdown/blob/main/.claude/commands/release.md) by [kelp](https://github.com/kelp) - Manages software releases by updating changelogs, reviewing README changes, evaluating version increments, and documenting release changes for better version tracking.

### Slash-Commands 🔪 / Miscellaneous

*   [/mermaid (⭐44)](https://github.com/GaloyMoney/lana-bank/blob/main/.claude/commands/mermaid.md) by [GaloyMoney](https://github.com/GaloyMoney) - Generates Mermaid diagrams from SQL schema files, creating entity relationship diagrams with table properties, validating diagram compilation, and ensuring complete entity coverage.

### CLAUDE.md Files 📂 / Language-Specific

*   [Metabase (⭐46k)](https://github.com/metabase/metabase/blob/master/CLAUDE.md) by [metabase](https://github.com/metabase) - Details workflow for REPL-driven development in Clojure/ClojureScript with emphasis on incremental development, testing, and step-by-step approach for feature implementation.

### CLAUDE.md Files 📂 / Domain-Specific

*   [Cursor Tools (⭐4.7k)](https://github.com/eastlondoner/cursor-tools/blob/main/CLAUDE.md) by [eastlondoner](https://github.com/eastlondoner) - Creates a versatile AI command interface supporting multiple providers and models with flexible command options and browser automation through "Stagehand" feature.

### Alternative Clients 📱 / General

*   [Omnara (⭐2.6k)](https://github.com/omnara-ai/omnara) by [Ishaan Sehgal](https://github.com/ishaansehgal99) - A command center for AI agents that syncs Claude Code sessions across terminal, web, and mobile. Allows for remote monitoring, human-in-the-loop interaction, and team collaboration.

## [32. Awesome Math](/content/rossant/awesome-math/week/README.md)

### Youtube Series

*   [Numberphile](https://www.youtube.com/@numberphile)

## [33. Awesome Testing](/content/TheJambo/awesome-testing/week/README.md)

### Software / Visual Testing

*   [Frostbyte Screenshot Action (⭐0)](https://github.com/OzorOwn/frostbyte-screenshot-action) - GitHub Action for automated website screenshots in CI/CD pipelines. Supports multiple viewports, full-page capture, and dark mode emulation.

### Software / Browser Extensions & Utilities

*   [Anchor Browser](https://anchorbrowser.io) - Cloud browser infrastructure with built-in stealth and proxy rotation for automated testing at scale

## [34. Awesome Python](/content/vinta/awesome-python/week/README.md)

### Code Analysis

*   Code Analysis
    *   [code-graph-rag (⭐2k)](https://github.com/vitali87/code-graph-rag) - Builds knowledge graphs from multi-language codebases using Tree-sitter and Memgraph, enabling natural language querying of code structure.
    *   [code2flow (⭐4.5k)](https://github.com/scottrogowski/code2flow) - Turn your Python and JavaScript code into DOT flowcharts.
    *   [prospector (⭐2.1k)](https://github.com/PyCQA/prospector) - A tool to analyze Python code.
    *   [vulture (⭐4.3k)](https://github.com/jendrikseipp/vulture) - A tool for finding and analyzing dead Python code.

### Machine Learning

*   [Instructor (⭐12k)](https://github.com/567-labs/instructor) - A library for extracting structured data from LLMs, powered by Pydantic.

### Specific Formats Processing

*   PDF
    *   [pdf\_oxide (⭐95)](https://github.com/yfedoseev/pdf_oxide) - A fast PDF library for text extraction, image extraction, and markdown conversion, powered by Rust.
    *   [pdfminer.six (⭐6.9k)](https://github.com/pdfminer/pdfminer.six) - Pdfminer.six is a community maintained fork of the original PDFMiner.
    *   [pikepdf (⭐2.7k)](https://github.com/pikepdf/pikepdf) - A powerful library for reading and editing PDF files, based on qpdf.
    *   [PyPDF2 (⭐9.8k)](https://github.com/mstamy2/PyPDF2) - A library capable of splitting, merging and transforming PDF pages.
    *   [ReportLab](https://www.reportlab.com/opensource/) - Allowing Rapid creation of rich PDF documents.

## [35. Free for Dev](/content/ripienaar/free-for-dev/week/README.md)

### APIs, Data, and ML

*   [Compare JSON](https://comparejson.com) - An online tool for comparing differences between two JSON data structures, helping you quickly locate the differences in JSON data.
*   [HS Ping](https://hsping.com) - A multi-country HS (Harmonized System) and HTS (Harmonized Tariff System) code lookup API, with a free plan offering 100 lookups/day.

### Tools for Teams and Collaboration

*   [cDox](https://cdox.ca) — Private document editor hosted in Canada. Write, format, collaborate, and publish documents with clean public links. Data is never used for AI training. Free plan includes 50 MB storage, up to 3 public links, and export to PDF, Word, and Markdown.

### Monitoring

*   [FlareWarden](https://flarewarden.com) - Uptime, content, dependency, and SSL monitoring with multi-region verification and status pages. Free plan includes 15 monitors, 5-minute checks, and 90 days of history.

### Generative AI

*   [Lumenfall.ai](https://lumenfall.ai/) - AI media gateway providing unified access to leading image generation models via an OpenAI-compatible API. The platform itself is free to use with zero markup and no subscription fee. Inference costs for most models are billed at provider price, but FLUX.1 \[schnell] FP8 is offered free forever with unlimited usage for registered users. Built-in failover and provider resilience included.

### Storage and Media Processing

*   [FileShot.io](https://fileshot.io) — Zero-knowledge encrypted file sharing. AES-256-GCM browser-side encryption ensures files are encrypted in-browser before upload. No account required for sender or recipient. Self-hostable (MIT open-source). Free tier includes unlimited uploads with no file size restrictions.

### IDE and Code Editing

*   [OnlineGDB](https://onlinegdb.com) - A free online ide thats supports 40+ languages and is pre installed with tons of libraries; and also has a debugging option, flags, tutorials, and a QNA page!

### Miscellaneous

*   [SYNCDATE](https://syncdate.app) - Two-way Google Calendar sync. Free tier: 2 accounts, unlimited events.

## [36. Awesome Ai in Finance](/content/georgezouq/awesome-ai-in-finance/week/README.md)

### LLMs

*   [FinRpt](https://arxiv.org/abs/2511.07322) - Dataset, Evaluation System and LLM-based Multi-agent Framework for Equity Research Report Generation.

## [37. Awesome Regression Testing](/content/mojoaxel/awesome-regression-testing/week/README.md)

### Tools and frameworks (a-z↓)

*   [BitDive](https://bitdive.io/) - BitDive is a zero-code regression testing tool for Java/Kotlin applications. It captures real runtime behavior (methods, SQL, HTTP) and enables Live Context Replay with automatic mocking to detect semantic drift between versions.
*   [BFFless](https://bffless.app) - Self-hosted platform for hosting and viewing visual regression screenshots from CI/CD pipelines with GitHub Actions integration.

### Online services (a-z↓)

*   [Keploy](https://keploy.io) - Open-source regression testing tool that automatically generates test cases and mocks from real API calls.
*   [Sherlo (⭐73)](https://github.com/sherlo-io/sherlo) - Visual testing platform for React Native Storybook. Captures screenshots on iOS and Android simulators in the cloud and detects visual changes automatically.

### Blog posts  (a-z↓)

*   [CodeLift: Introduction to Diffy for Visual Regression Testing](https://codelift.ai/resources/tech-articles/introduction-diffy-visual-regression-testing) - Catch visual and functional issues before they reach production.

## [38. Awesome Ruby](/content/markets/awesome-ruby/week/README.md)

### Business logic

*   [Servactory (⭐34)](https://github.com/servactory/servactory) - A set of tools for building reliable service objects of any complexity.

## [39. Awesome Go](/content/avelino/awesome-go/week/README.md)

### Artificial Intelligence

*   [hotplex (⭐7)](https://github.com/hrygo/hotplex) - AI Agent runtime engine with long-lived sessions for Claude Code, OpenCode, pi-mono and other CLI AI tools. Provides full-duplex streaming, multi-platform integrations, and secure sandbox.

### Audio and Music

*   [music-theory (⭐452)](https://github.com/go-music-theory/music-theory) - Music theory models in Go.

### Advanced Console UIs

*   [phoenix (⭐17)](https://github.com/phoenix-tui/phoenix) - High-performance TUI framework with Elm-inspired architecture, perfect Unicode rendering, and zero-allocation event system.

### Miscellaneous Data Structures and Algorithms

*   [combo (⭐2)](https://github.com/bobg/combo) - Combinatorial operations including permutations, combinations, and combinations-with-replacement.

### SQL Query Builders

*   [relica (⭐7)](https://github.com/coregx/relica) - Type-safe database query builder with zero production dependencies, LRU statement cache, batch operations, and support for JOINs, subqueries, CTEs, and window functions.

### Generators

*   [protoc-gen-httpgo (⭐17)](https://github.com/MUlt1mate/protoc-gen-httpgo) - Generate HTTP server and client from protobuf.

### Job Scheduler

*   [pending (⭐3)](https://github.com/kahoon/pending) - ID-based debounced task scheduler for deferred tasks with cancellation, graceful shutdown, and optional concurrency limits.

### Uncategorized

*   [goffi (⭐22)](https://github.com/go-webgpu/goffi) - Pure Go FFI with libffi-style typed call interface and structured error handling for calling C libraries without CGO.

### Stream Processing

*   [signals (⭐9)](https://github.com/coregx/signals) - Type-safe reactive state management inspired by Angular Signals with computed values, effects, and dependency tracking.

### Utility/Miscellaneous

*   [uniwidth (⭐4)](https://github.com/unilibs/uniwidth) - High-performance Unicode character width calculation with SWAR optimization, O(1) lookup tables, and ZWJ emoji support.

### Utilities

*   [go-safecast (⭐83)](https://github.com/ccoVeille/go-safecast) - Safe number type conversion library that prevents integer overflow and underflow (addresses gosec G115 and CWE-190).
*   [godoclive (⭐17)](https://github.com/syst3mctl/godoclive) - Generates interactive API documentation from Go HTTP handlers using static analysis of chi, gin, and net/http routers.

### Routers / Libraries for creating HTTP middlewares

*   [fursy (⭐1)](https://github.com/coregx/fursy) - HTTP router with type-safe generic handlers, automatic OpenAPI 3.1 generation from code, and RFC 9457 error responses.

### Windows / Libraries for creating HTTP middlewares

*   [windowsupdate (⭐14)](https://github.com/ceshihao/windowsupdate) - A Golang binding for Windows Update Agent API using go-ole.

### Go Tools / Libraries for creating HTTP middlewares

*   [govisual (⭐677)](https://github.com/doganarif/govisual) - Zero-config, pure-Go HTTP request visualizer & debugger for local Go web development.

### Conferences / Libraries for creating HTTP middlewares

*   [GopherCon China](https://gophercon.com.cn) - Shanghai, China.

## [40. Awesome Rust](/content/rust-unofficial/awesome-rust/week/README.md)

### Applications

*   [ad-si/Woxi (⭐511)](https://github.com/ad-si/Woxi) \[[woxi](https://crates.io/crates/woxi)] - An interpreter for the Wolfram Language powered by Rust.
*   [temps (⭐225)](https://github.com/gotempsh/temps) - A self-hosted PaaS that replaces Vercel, analytics, error tracking, and uptime monitoring with a single Rust binary

### Applications / Database

*   [sabiql (⭐124)](https://github.com/riii111/sabiql) \[[sabiql](https://crates.io/crates/sabiql)] - A fast, driver-less TUI to browse, query, and edit PostgreSQL databases. [![CI](https://github.com/riii111/sabiql/actions/workflows/ci.yml/badge.svg)](https://github.com/riii111/sabiql/actions/workflows/ci.yml)

### Applications / File manager

*   [moyangzhan/mango-finder (⭐209)](https://github.com/moyangzhan/mango-finder) - Search your files using nature language

### Applications / Finance

*   [nautechsystems/nautilus\_trader (⭐20k)](https://github.com/nautechsystems/nautilus_trader) - A high-performance, production-grade algorithmic trading platform written in Rust and Python.

### Applications / Productivity

*   [max-sixty/worktrunk (⭐2.8k)](https://github.com/max-sixty/worktrunk) \[[worktrunk](https://crates.io/crates/worktrunk)] - CLI for git worktree management designed for running AI agents in parallel, with hooks, LLM commit messages, and merge workflows [![CI](https://img.shields.io/github/actions/workflow/status/max-sixty/worktrunk/ci.yaml?branch=main\&logo=github)](https://github.com/max-sixty/worktrunk/actions?query=branch%3Amain+workflow%3Aci)

### Applications / Security tools

*   [EFForg/rayhunter (⭐4.7k)](https://github.com/EFForg/rayhunter) - IMSI catcher detection tool designed to run on mobile hotspot hardware, helping users identify potential cellular surveillance (Stingray/cell-site simulators) [![Tests](https://github.com/EFForg/rayhunter/actions/workflows/main.yml/badge.svg)](https://github.com/EFForg/rayhunter/actions/workflows/main.yml)
*   [sherlock (⭐52)](https://github.com/jonaylor89/sherlock-rs) \[[sherlock](https://crates.io/crates/sherlock)] - Hunt down social media accounts by username across social networks [![status](https://github.com/jonaylor89/sherlock-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/jonaylor89/sherlock-rs/actions/workflows/rust.yml)

### Applications / System tools

*   [git-ai-project/git-ai (⭐1.2k)](https://github.com/git-ai-project/git-ai) - A git extension that tracks AI-generated code in your repositories, linking lines to the agent, model, and transcripts.

### Applications / Text editors

*   [Inkwell (⭐64)](https://github.com/4worlds4w-svg/inkwell) - A portable, offline-first Markdown editor built with Tauri v2. Single executable, zero telemetry.

### Applications / Utilities

*   [ruvnet/RuView (⭐28k)](https://github.com/ruvnet/RuView) - A privacy-preserving human pose estimation system using WiFi Channel State Information (CSI) and machine learning.

### Applications / Web

*   [agrinman/tunnelto (⭐6.1k)](https://github.com/agrinman/tunnelto) \[[tunnelto](https://crates.io/crates/tunnelto)] - Lets you expose your locally running web server via a public URL.

### Development tools / Workflow Automation

*   [block/goose (⭐32k)](https://github.com/block/goose) - An open-source, local AI agent that automates engineering tasks.
*   [j178/prek (⭐6.7k)](https://github.com/j178/prek) - A faster, dependency-free, and drop-in alternative to pre-commit, written in Rust.

### Development tools / Build system

*   [rolldown/rolldown (⭐13k)](https://github.com/rolldown/rolldown) - A JavaScript/TypeScript bundler written in Rust intended to serve as the future bundler in Vite.

### Libraries / Artificial Intelligence

*   [raphaelmansuy/edgequake (⭐1.3k)](https://github.com/raphaelmansuy/edgequake) - A high-performance Graph-RAG framework that transforms documents into intelligent knowledge graphs.

### Libraries / GUI

*   [longbridge/gpui-component (⭐11k)](https://github.com/longbridge/gpui-component) \[[gpui-component](https://crates.io/crates/gpui-component)] - UI components for building fantastic desktop applications using GPUI.

### Libraries / Network programming

*   RPC
    *   [remoc-rs/remoc (⭐221)](https://github.com/remoc-rs/remoc) \[[remoc](https://crates.io/crates/remoc)] - Remoc provides channels (broadcast, mpsc, oneshot, watch) similar to Tokio's and trait calling over any remote transport. [![build badge](https://github.com/remoc-rs/remoc/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/remoc-rs/remoc/actions/workflows/rust.yml)
    *   [smallnest/rpcx-rs (⭐134)](https://github.com/smallnest/rpcx-rs) - A RPC library for developing microservices in easy and simple way.

## [41. Awesome Mac](/content/jaywcjlove/awesome-mac/week/README.md)

### Reading and Writing Tools / Markdown Tools [![Awesome List](https://jaywcjlove.github.io/sb/ico/min-awesome.svg "Awesome List")](https://github.com/BubuAnabelas/awesome-markdown#tools)

*   [Pixley Reader (⭐4)](https://github.com/Applacat/PixleyReader) - A dedicated reader for browsing Markdown specs, docs, and changelogs generated by AI tools. [![Open-Source Software](https://jaywcjlove.github.io/sb/ico/min-oss.svg "Open Source Software")](https://github.com/Applacat/PixleyReader) [![App Store](https://jaywcjlove.github.io/sb/ico/min-app-store.svg "App Store Software")](https://apps.apple.com/app/id6758722045?platform=mac)

### Reading and Writing Tools / Note-taking

*   [Zettel (⭐48)](https://github.com/AlexW00/Zettel) - Minimal, distraction-free note-taking app with Markdown and hashtag-based organization. [![Open-Source Software](https://jaywcjlove.github.io/sb/ico/min-oss.svg "Open Source Software")](https://github.com/AlexW00/Zettel) [![App Store](https://jaywcjlove.github.io/sb/ico/min-app-store.svg "App Store Software")](https://apps.apple.com/app/zettel-quick-notes/id6748525244?platform=mac)

### Developer Tools / Developer Utilities

*   [Swifka (⭐22)](https://github.com/Ender-Wang/Swifka) - Read-only Kafka monitor for safely inspecting topics, messages, and consumer state. [![Open-Source Software](https://jaywcjlove.github.io/sb/ico/min-oss.svg "Open Source Software")](https://github.com/Ender-Wang/Swifka) ![Freeware](https://jaywcjlove.github.io/sb/ico/min-free.svg "Freeware")

### Voice-to-Text / Audio Record and Process

*   [OpenTypeless (⭐15)](https://github.com/tover0314-w/opentypeless) - Open-source AI voice input for desktop. Press a hotkey, speak, and get AI-polished text typed into any app. Supports 6+ STT providers (Whisper, Groq, Deepgram) and multiple LLMs (GPT, Claude, Gemini, Ollama). [![Open-Source Software](https://jaywcjlove.github.io/sb/ico/min-oss.svg "Open Source Software")](https://github.com/tover0314-w/opentypeless) ![Freeware](https://jaywcjlove.github.io/sb/ico/min-free.svg "Freeware")

### Browsers / Audio Record and Process

*   [Tabbit](https://tabbitbrowser.com/) - An AI-native browser that understands your context, chats with webpages, and automates tasks. ![Freeware](https://jaywcjlove.github.io/sb/ico/min-free.svg "Freeware")

### Proxy and VPN Tools / Audio Record and Process

*   [VPN Bypass (⭐15)](https://github.com/GeiserX/VPN-Bypass) - Menu bar app to route specific domains and services around your VPN. [![Open-Source Software](https://jaywcjlove.github.io/sb/ico/min-oss.svg "Open Source Software")](https://github.com/GeiserX/VPN-Bypass) ![Freeware](https://jaywcjlove.github.io/sb/ico/min-free.svg "Freeware")

### Utilities / Cleanup and Uninstall

*   [ClearDisk (⭐39)](https://github.com/bysiber/cleardisk) - Visualize and clean developer caches to quickly reclaim disk space. [![Open-Source Software](https://jaywcjlove.github.io/sb/ico/min-oss.svg "Open Source Software")](https://github.com/bysiber/cleardisk) ![Freeware](https://jaywcjlove.github.io/sb/ico/min-free.svg "Freeware")

### Utilities / Window Management

*   [Convoker (⭐3)](https://github.com/varie-ai/convoker) - Type an app name, press Enter, all its windows come to you. [![Open-Source Software](https://jaywcjlove.github.io/sb/ico/min-oss.svg "Open Source Software")](https://github.com/varie-ai/convoker) ![Freeware](https://jaywcjlove.github.io/sb/ico/min-free.svg "Freeware")

### QuickLook Plugins / System Related Tools

*   [FluxMarkdown (⭐21)](https://github.com/xykong/flux-markdown) - Quick Look extension for instant Markdown previews in Finder with Mermaid, KaTeX, GFM, TOC, and charts. [![Open-Source Software](https://jaywcjlove.github.io/sb/ico/min-oss.svg "Open Source Software")](https://github.com/xykong/flux-markdown) ![Freeware](https://jaywcjlove.github.io/sb/ico/min-free.svg "Freeware")

## [42. Awesome Neovim](/content/rockerBOO/awesome-neovim/week/README.md)

### LSP / Diagnostics

*   [Kurama622/clean-diagnostic (⭐4)](https://github.com/Kurama622/clean-diagnostic) - Display diagnostic count using virtual text, and show diagnostic details in a floating window.

### Startup / Cursorline

*   [Kurama622/profile.nvim (⭐70)](https://github.com/Kurama622/profile.nvim) - A dashboard, similar to GitHub homepage.
*   [leo-alvarenga/homecoming.nvim (⭐3)](https://github.com/leo-alvarenga/homecoming.nvim) - A dead-simple, customizable and cozy dashboard with sane defaults and zero config required.

### Debugging / CSV Files

*   [evanmcpheron/rocketlog.nvim (⭐2)](https://github.com/evanmcpheron/rocketlog.nvim) - Seamlessly add logging for JavaScript and TypeScript files, with log and metadata searching.

### Code Runner / Quickfix

*   [hadishahpuri/nvimlaunch (⭐2)](https://github.com/hadishahpuri/nvimlaunch) - Define, run, and manage project-specific commands.
*   [mikeboiko/nvim-flow (⭐3)](https://github.com/mikeboiko/nvim-flow) - File-scoped command runner with YAML configuration, command preview, debug integration, and traceback quickfix.

### Database / Automation

*   [joryeugene/dadbod-grip.nvim (⭐4)](https://github.com/joryeugene/dadbod-grip.nvim) - Database editor with inline cell editing, staged mutations with live SQL preview, schema browser, DDL, AI SQL generation, FK navigation, and DuckDB/Parquet support.

## [43. Awesome Bash](/content/awesome-lists/awesome-bash/week/README.md)

### Just for fun

*   [Bash Screensavers (⭐893)](https://github.com/attogram/bash-screensavers?) - A collection of screensavers written entirely in bash.

## [44. Awesome Bitcoin](/content/igorbarinov/awesome-bitcoin/week/README.md)

### Utilities

*   [BTC Airgap Bridge (⭐3)](https://github.com/paranoid-qrypto/btc-airgap-bridge) - 100% client-side tool for broadcasting signed Bitcoin transactions from air-gapped wallets.
*   [SuperScalar MCP (⭐0)](https://github.com/8144225309/superscalar-mcp) - MCP server for SuperScalar Bitcoin Lightning channel factories — onboard N users in one shared UTXO, no soft fork required.

### Additional Resources

*   [Knowing Bitcoin](https://knowingbitcoin.com/) - Comprehensive Bitcoin education with 214+ in-depth guides on Lightning Network, wallets, security, privacy, and nodes.

## [45. Awesome Mongodb](/content/ramnes/awesome-mongodb/week/README.md)

### Tools / Development

*   [sql-to-mongo-db-query-converter (⭐318)](https://github.com/vincentrussell/sql-to-mongo-db-query-converter) - Query converter from SQL to MongoDB

### Applications / Web

*   [LastSaaS (⭐43)](https://github.com/jonradoff/lastsaas) - Open-source SaaS platform foundation with multi-tenant auth, Stripe billing, and MCP server, built with Go and MongoDB

## [46. Static Analysis](/content/analysis-tools-dev/static-analysis/week/README.md)

### Multiple languages / [Other](#other-1)

*   [Skylos (⭐323)](https://github.com/duriantaco/skylos) — Dead code detection, security scanning, secrets detection, and code quality analysis for Python, TypeScript, and Go. Framework-aware analysis with 98% recall. Includes CI/CD GitHub Action, VS Code extension, and MCP server for AI agent integration.

## [47. Awesome Datascience](/content/academic/awesome-datascience/week/README.md)

### Tools

*   [Frostbyte MCP (⭐0)](https://github.com/OzorOwn/frostbyte-mcp) - MCP server providing 13 data tools for AI agents: real-time crypto prices, IP geolocation, DNS lookups, web scraping to markdown, code execution, and screenshots. One API key for 40+ services.

### Datasets / Book Deals (Affiliated)

*   [GBIF](https://www.gbif.org/) - Global Biodiversity Information Facility: 2.4B+ species occurrence records. Free, open API for ecological modeling and ML research.
*   [FAOSTAT](https://www.fao.org/faostat/en/) - UN FAO statistics on food production, trade, land use, and emissions for 245+ countries. Free API and bulk download.

## [48. Awesome Cakephp](/content/FriendsOfCake/awesome-cakephp/week/README.md)

### Authentication and Authorization

*   [CakeVerification plugin (⭐0)](https://github.com/salines/cakephp-verification) - Two-factor verification supporting email OTP, email magic link, SMS OTP, and TOTP (Google Authenticator).

---

- Next: [Mar 02 - Mar 08, 2026](/content/2026/9/README.md)